OpenMandriva - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for OpenMandriva.

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

Total: 5417

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | 0VHWTR A01                  | [7544868958](https://linux-hardware.org/?probe=7544868958) | Feb 01, 2023 |
| MSI           | A520M-A PRO                 | [f7a88d0dea](https://linux-hardware.org/?probe=f7a88d0dea) | Feb 01, 2023 |
| AMI           | Cherry Trail CR             | [162e744903](https://linux-hardware.org/?probe=162e744903) | Feb 01, 2023 |
| ASUSTek       | Z87-A                       | [1b880dbac2](https://linux-hardware.org/?probe=1b880dbac2) | Feb 01, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [aa3b7e2dc8](https://linux-hardware.org/?probe=aa3b7e2dc8) | Feb 01, 2023 |
| Dell          | 0PU052                      | [d2f241353d](https://linux-hardware.org/?probe=d2f241353d) | Feb 01, 2023 |
| Dell          | 0WG860                      | [002a1f805c](https://linux-hardware.org/?probe=002a1f805c) | Feb 01, 2023 |
| ASUSTek       | F2A85-V                     | [c68678a1a5](https://linux-hardware.org/?probe=c68678a1a5) | Jan 31, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [f4e30fc177](https://linux-hardware.org/?probe=f4e30fc177) | Jan 31, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [25b35d4826](https://linux-hardware.org/?probe=25b35d4826) | Jan 31, 2023 |
| HP            | 21EF                        | [0aacd43b02](https://linux-hardware.org/?probe=0aacd43b02) | Jan 31, 2023 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | [19d65de9b6](https://linux-hardware.org/?probe=19d65de9b6) | Jan 31, 2023 |
| ASUSTek       | Maximus VII GENE            | [c936c07925](https://linux-hardware.org/?probe=c936c07925) | Jan 31, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | [d8d386cb1d](https://linux-hardware.org/?probe=d8d386cb1d) | Jan 31, 2023 |
| MSI           | G41M-P28                    | [7f37c4b40e](https://linux-hardware.org/?probe=7f37c4b40e) | Jan 31, 2023 |
| ASRock        | H77 Pro4-M                  | [a37090dd20](https://linux-hardware.org/?probe=a37090dd20) | Jan 31, 2023 |
| Jetway        | I61G-ITX                    | [24cf6ad56e](https://linux-hardware.org/?probe=24cf6ad56e) | Jan 31, 2023 |
| ASUSTek       | PRIME B360M-A               | [1196b501d5](https://linux-hardware.org/?probe=1196b501d5) | Jan 31, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [3be362b4aa](https://linux-hardware.org/?probe=3be362b4aa) | Jan 31, 2023 |
| ASUSTek       | P8H77-V LE                  | [9edd1a1969](https://linux-hardware.org/?probe=9edd1a1969) | Jan 30, 2023 |
| Intel         | DQ77MK AAG39642-500         | [3e004045f7](https://linux-hardware.org/?probe=3e004045f7) | Jan 30, 2023 |
| ASUSTek       | P5KPL-C/1600                | [dba6d97191](https://linux-hardware.org/?probe=dba6d97191) | Jan 30, 2023 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [3c8b3f4e7d](https://linux-hardware.org/?probe=3c8b3f4e7d) | Jan 30, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [cbfcb68cc6](https://linux-hardware.org/?probe=cbfcb68cc6) | Jan 30, 2023 |
| MSI           | H81M-P33                    | [32149d3b64](https://linux-hardware.org/?probe=32149d3b64) | Jan 30, 2023 |
| ASUSTek       | PRIME X570-P                | [a05f6f2f6c](https://linux-hardware.org/?probe=a05f6f2f6c) | Jan 30, 2023 |
| ASUSTek       | H81M2                       | [304b95972c](https://linux-hardware.org/?probe=304b95972c) | Jan 30, 2023 |
| HP            | 8526 MVB, A                 | [eaa1bf595f](https://linux-hardware.org/?probe=eaa1bf595f) | Jan 30, 2023 |
| ASUSTek       | PRIME B450M-A               | [f0000c6ae7](https://linux-hardware.org/?probe=f0000c6ae7) | Jan 30, 2023 |
| ASUSTek       | PRIME B350M-A               | [e2721d08d6](https://linux-hardware.org/?probe=e2721d08d6) | Jan 30, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [ef9c1299e6](https://linux-hardware.org/?probe=ef9c1299e6) | Jan 30, 2023 |
| HP            | 339A                        | [3bc7df3921](https://linux-hardware.org/?probe=3bc7df3921) | Jan 30, 2023 |
| ViewSonic     | VOT132                      | [a8ecfadd53](https://linux-hardware.org/?probe=a8ecfadd53) | Jan 30, 2023 |
| ASRock        | J4125M                      | [535c1b6821](https://linux-hardware.org/?probe=535c1b6821) | Jan 30, 2023 |
| Acer          | Aspire TC-895 V:1.0         | [190e9b4aee](https://linux-hardware.org/?probe=190e9b4aee) | Jan 30, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [11b07d4e11](https://linux-hardware.org/?probe=11b07d4e11) | Jan 29, 2023 |
| HC            | HCAR357-MI V1.0             | [986dd858ba](https://linux-hardware.org/?probe=986dd858ba) | Jan 29, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | [da2056876e](https://linux-hardware.org/?probe=da2056876e) | Jan 29, 2023 |
| ASUSTek       | PRIME B550M-A AC            | [c11ff840dd](https://linux-hardware.org/?probe=c11ff840dd) | Jan 29, 2023 |
| Intel         | H61                         | [0ce404915f](https://linux-hardware.org/?probe=0ce404915f) | Jan 29, 2023 |
| ASUSTek       | PRIME H310I-PLUS R2.0       | [1b8a1f7b64](https://linux-hardware.org/?probe=1b8a1f7b64) | Jan 29, 2023 |
| ASUSTek       | B150M-C                     | [6eb1a5b38e](https://linux-hardware.org/?probe=6eb1a5b38e) | Jan 29, 2023 |
| ASUSTek       | M5A97 R2.0                  | [703a3a2694](https://linux-hardware.org/?probe=703a3a2694) | Jan 29, 2023 |
| ASRock        | B450 Gaming K4              | [000203af81](https://linux-hardware.org/?probe=000203af81) | Jan 29, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [a6f17c156d](https://linux-hardware.org/?probe=a6f17c156d) | Jan 29, 2023 |
| ASRock        | H610M-HVS                   | [2774d547be](https://linux-hardware.org/?probe=2774d547be) | Jan 29, 2023 |
| ASUSTek       | Z97-K                       | [e3f865cd20](https://linux-hardware.org/?probe=e3f865cd20) | Jan 28, 2023 |
| Intel         | X79G V2.x                   | [40bc764c73](https://linux-hardware.org/?probe=40bc764c73) | Jan 28, 2023 |
| ASRock        | N68C-S UCC                  | [de8739d9d5](https://linux-hardware.org/?probe=de8739d9d5) | Jan 28, 2023 |
| ASUSTek       | H110M-K                     | [73b3f84699](https://linux-hardware.org/?probe=73b3f84699) | Jan 28, 2023 |
| ASUSTek       | P8H61-M LE/CSM R2.0         | [7120eb3310](https://linux-hardware.org/?probe=7120eb3310) | Jan 28, 2023 |
| Gigabyte      | GA-73PVM-S2                 | [fcf91f09b4](https://linux-hardware.org/?probe=fcf91f09b4) | Jan 28, 2023 |
| Unknown       | GB01                        | [e907445f6c](https://linux-hardware.org/?probe=e907445f6c) | Jan 28, 2023 |
| Intel         | DH77EB AAG39073-304         | [8965805130](https://linux-hardware.org/?probe=8965805130) | Jan 27, 2023 |
| Dell          | 0VRWRC A00                  | [dac4a44a62](https://linux-hardware.org/?probe=dac4a44a62) | Jan 27, 2023 |
| ASUSTek       | PRIME X299-DELUXE II        | [c7e2bde422](https://linux-hardware.org/?probe=c7e2bde422) | Jan 27, 2023 |
| Gigabyte      | H81N                        | [e7cf6a4216](https://linux-hardware.org/?probe=e7cf6a4216) | Jan 27, 2023 |
| Dell          | 0RW199                      | [04c4f5174d](https://linux-hardware.org/?probe=04c4f5174d) | Jan 27, 2023 |
| Hardkernel    | ODROID-H3                   | [56f9bb1456](https://linux-hardware.org/?probe=56f9bb1456) | Jan 27, 2023 |
| Intel         | DH61BE AAG14062-211         | [e4a05d50b7](https://linux-hardware.org/?probe=e4a05d50b7) | Jan 27, 2023 |
| Medion        | TJ4125                      | [eaca458ea2](https://linux-hardware.org/?probe=eaca458ea2) | Jan 26, 2023 |
| HP            | 1497                        | [21a3e07346](https://linux-hardware.org/?probe=21a3e07346) | Jan 26, 2023 |
| Gigabyte      | Z87X-D3H-CF                 | [7fb86baa0e](https://linux-hardware.org/?probe=7fb86baa0e) | Jan 26, 2023 |
| ASUSTek       | P8H77-V LE                  | [0305833fbd](https://linux-hardware.org/?probe=0305833fbd) | Jan 26, 2023 |
| Gigabyte      | GA-MA78G-DS3H               | [9a1bab8f2c](https://linux-hardware.org/?probe=9a1bab8f2c) | Jan 26, 2023 |
| HP            | 225E                        | [bace147a01](https://linux-hardware.org/?probe=bace147a01) | Jan 26, 2023 |
| Acer          | RS740DVF                    | [6aaeb06f9a](https://linux-hardware.org/?probe=6aaeb06f9a) | Jan 26, 2023 |
| HP            | 3397                        | [1584c8c840](https://linux-hardware.org/?probe=1584c8c840) | Jan 26, 2023 |
| Shenzhen M... | F6BFC                       | [fab7cead8c](https://linux-hardware.org/?probe=fab7cead8c) | Jan 26, 2023 |
| Lenovo        | 3642 SDK0J40700 WIN 3258... | [ce46ecced0](https://linux-hardware.org/?probe=ce46ecced0) | Jan 26, 2023 |
| MSI           | PRO Z690-A                  | [4b063ab512](https://linux-hardware.org/?probe=4b063ab512) | Jan 26, 2023 |
| Dell          | 0773VG A00                  | [328dae4014](https://linux-hardware.org/?probe=328dae4014) | Jan 26, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [8128876a22](https://linux-hardware.org/?probe=8128876a22) | Jan 26, 2023 |
| ASUSTek       | PRIME X370-A                | [b1371b8883](https://linux-hardware.org/?probe=b1371b8883) | Jan 26, 2023 |
| Gigabyte      | EX38-DS4                    | [4d5b828cfc](https://linux-hardware.org/?probe=4d5b828cfc) | Jan 25, 2023 |
| BESSTAR Te... | TH50                        | [da185120e5](https://linux-hardware.org/?probe=da185120e5) | Jan 25, 2023 |
| Intel         | B75                         | [20853a8c8d](https://linux-hardware.org/?probe=20853a8c8d) | Jan 25, 2023 |
| HP            | 3048h                       | [caabf4189f](https://linux-hardware.org/?probe=caabf4189f) | Jan 25, 2023 |
| ASRock        | X300M-STX                   | [f111e4de3b](https://linux-hardware.org/?probe=f111e4de3b) | Jan 25, 2023 |
| ASUSTek       | M5A99X EVO                  | [14b3eb9a58](https://linux-hardware.org/?probe=14b3eb9a58) | Jan 25, 2023 |
| ASRock        | G31M-S                      | [e1d742770d](https://linux-hardware.org/?probe=e1d742770d) | Jan 25, 2023 |
| AZW           | U59                         | [6d2b672b77](https://linux-hardware.org/?probe=6d2b672b77) | Jan 25, 2023 |
| ASUSTek       | P5L-MX                      | [c66369d864](https://linux-hardware.org/?probe=c66369d864) | Jan 25, 2023 |
| ASRock        | B550AM Gaming               | [215973c00f](https://linux-hardware.org/?probe=215973c00f) | Jan 25, 2023 |
| Dell          | 0KRC95 A00                  | [bf9e573abf](https://linux-hardware.org/?probe=bf9e573abf) | Jan 25, 2023 |
| ASRock        | 775XFire-VSTA               | [e80788f790](https://linux-hardware.org/?probe=e80788f790) | Jan 24, 2023 |
| HP            | 8433 11                     | [de1465f90e](https://linux-hardware.org/?probe=de1465f90e) | Jan 24, 2023 |
| Intel         | DH67CL AAG10212-203         | [0e7c3464ac](https://linux-hardware.org/?probe=0e7c3464ac) | Jan 24, 2023 |
| HP            | 2AF7                        | [a7cb391a5c](https://linux-hardware.org/?probe=a7cb391a5c) | Jan 24, 2023 |
| MSI           | G41M-P28                    | [465a715dc7](https://linux-hardware.org/?probe=465a715dc7) | Jan 24, 2023 |
| Pegatron      | 2AEE                        | [1c59133176](https://linux-hardware.org/?probe=1c59133176) | Jan 24, 2023 |
| Dell          | 06FW8P A02                  | [091ff86983](https://linux-hardware.org/?probe=091ff86983) | Jan 24, 2023 |
| Unknown       | Unknown                     | [108bb60066](https://linux-hardware.org/?probe=108bb60066) | Jan 24, 2023 |
| ASUSTek       | PRIME B450M-A               | [da95f58140](https://linux-hardware.org/?probe=da95f58140) | Jan 23, 2023 |
| Gigabyte      | Z690 UD DDR4                | [872cd0446b](https://linux-hardware.org/?probe=872cd0446b) | Jan 23, 2023 |
| Lenovo        | 312A NOK                    | [ef4e303beb](https://linux-hardware.org/?probe=ef4e303beb) | Jan 23, 2023 |
| Gigabyte      | H81M-S1                     | [ab746d7557](https://linux-hardware.org/?probe=ab746d7557) | Jan 23, 2023 |
| ASUSTek       | H81M-K                      | [3c25197bac](https://linux-hardware.org/?probe=3c25197bac) | Jan 23, 2023 |
| Gigabyte      | B360HD3                     | [a9b7912b52](https://linux-hardware.org/?probe=a9b7912b52) | Jan 23, 2023 |
| Dell          | 0J3C2F A02                  | [e4b2eae84b](https://linux-hardware.org/?probe=e4b2eae84b) | Jan 23, 2023 |
| Gigabyte      | EP35-DS3L                   | [5be0362f3e](https://linux-hardware.org/?probe=5be0362f3e) | Jan 23, 2023 |
| Gigabyte      | B250M-DS3H-CF               | [af23cdf7e9](https://linux-hardware.org/?probe=af23cdf7e9) | Jan 23, 2023 |
| HP            | 0AACh                       | [7c566e8951](https://linux-hardware.org/?probe=7c566e8951) | Jan 23, 2023 |
| ASRock        | FM2A55M-VG3+                | [c5da4a997d](https://linux-hardware.org/?probe=c5da4a997d) | Jan 23, 2023 |
| ASUSTek       | PRIME H270-PRO              | [ac4fa9fd5f](https://linux-hardware.org/?probe=ac4fa9fd5f) | Jan 23, 2023 |
| ASUSTek       | F2A55-M LK2                 | [93db1bee75](https://linux-hardware.org/?probe=93db1bee75) | Jan 23, 2023 |
| ASUSTek       | H81M-E                      | [2a20dabdd7](https://linux-hardware.org/?probe=2a20dabdd7) | Jan 23, 2023 |
| Biostar       | N61PB-M2S                   | [bce8692808](https://linux-hardware.org/?probe=bce8692808) | Jan 22, 2023 |
| Dell          | 0HH807                      | [984a0f6134](https://linux-hardware.org/?probe=984a0f6134) | Jan 22, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [076a3479fa](https://linux-hardware.org/?probe=076a3479fa) | Jan 22, 2023 |
| Dell          | 06D7TR A02                  | [f61052df5e](https://linux-hardware.org/?probe=f61052df5e) | Jan 22, 2023 |
| Gigabyte      | A320M-S2H-CF                | [7545ee3eb0](https://linux-hardware.org/?probe=7545ee3eb0) | Jan 22, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [dcecec2239](https://linux-hardware.org/?probe=dcecec2239) | Jan 22, 2023 |
| ASRock        | FM2A85X Extreme4-M          | [f51082b385](https://linux-hardware.org/?probe=f51082b385) | Jan 22, 2023 |
| ASRock        | X370 Pro4                   | [6a8cc962ad](https://linux-hardware.org/?probe=6a8cc962ad) | Jan 22, 2023 |
| ASUSTek       | A68HM-K                     | [770d2f3bb4](https://linux-hardware.org/?probe=770d2f3bb4) | Jan 22, 2023 |
| Lenovo        | SHARKBAY SDK0E50519 WIN     | [e2bec99703](https://linux-hardware.org/?probe=e2bec99703) | Jan 22, 2023 |
| ASRock        | B75M-GL R2.0                | [19b61442fe](https://linux-hardware.org/?probe=19b61442fe) | Jan 22, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [2851ee7994](https://linux-hardware.org/?probe=2851ee7994) | Jan 22, 2023 |
| HP            | 1905                        | [aaa3a9557c](https://linux-hardware.org/?probe=aaa3a9557c) | Jan 22, 2023 |
| HP            | 1998                        | [5fcedbdb28](https://linux-hardware.org/?probe=5fcedbdb28) | Jan 22, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | [f660cd6d78](https://linux-hardware.org/?probe=f660cd6d78) | Jan 22, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [447e624609](https://linux-hardware.org/?probe=447e624609) | Jan 22, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [476d23dca7](https://linux-hardware.org/?probe=476d23dca7) | Jan 21, 2023 |
| Lenovo        | MT-M4157-16U                | [3507cef137](https://linux-hardware.org/?probe=3507cef137) | Jan 21, 2023 |
| ASUSTek       | PRIME H510M-A               | [42e0ba4db2](https://linux-hardware.org/?probe=42e0ba4db2) | Jan 21, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d27e517254](https://linux-hardware.org/?probe=d27e517254) | Jan 21, 2023 |
| Gigabyte      | H510M H                     | [40cc1bf7d9](https://linux-hardware.org/?probe=40cc1bf7d9) | Jan 21, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [0a6759f639](https://linux-hardware.org/?probe=0a6759f639) | Jan 21, 2023 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [0f3a750cdc](https://linux-hardware.org/?probe=0f3a750cdc) | Jan 21, 2023 |
| Acer          | Aspire TC-885 V:1.1         | [7475608215](https://linux-hardware.org/?probe=7475608215) | Jan 21, 2023 |
| ASRock        | B550M Pro4                  | [22b030cc5c](https://linux-hardware.org/?probe=22b030cc5c) | Jan 21, 2023 |
| MSI           | X470 GAMING PLUS            | [441e45daa2](https://linux-hardware.org/?probe=441e45daa2) | Jan 21, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | [46a3691da9](https://linux-hardware.org/?probe=46a3691da9) | Jan 21, 2023 |
| ASRock        | AB350M Pro4 R2.0            | [e601a547c8](https://linux-hardware.org/?probe=e601a547c8) | Jan 21, 2023 |
| ASRock        | B550 Extreme4               | [329f1d0701](https://linux-hardware.org/?probe=329f1d0701) | Jan 21, 2023 |
| MSI           | H110M PRO-VH                | [7068e861ba](https://linux-hardware.org/?probe=7068e861ba) | Jan 21, 2023 |
| Gigabyte      | N3050ND3H                   | [1663928526](https://linux-hardware.org/?probe=1663928526) | Jan 21, 2023 |
| ASUSTek       | PRIME Z390M-PLUS            | [6134837cfe](https://linux-hardware.org/?probe=6134837cfe) | Jan 21, 2023 |
| Lenovo        | SHARKBAY NOK                | [bc8b02043e](https://linux-hardware.org/?probe=bc8b02043e) | Jan 20, 2023 |
| Intel         | B75                         | [40da372747](https://linux-hardware.org/?probe=40da372747) | Jan 20, 2023 |
| AZW           | U59                         | [de70883bbf](https://linux-hardware.org/?probe=de70883bbf) | Jan 20, 2023 |
| ASRock        | A520M-HDVP/DASH             | [72421e0506](https://linux-hardware.org/?probe=72421e0506) | Jan 20, 2023 |
| HP            | 843B                        | [2af17234ba](https://linux-hardware.org/?probe=2af17234ba) | Jan 20, 2023 |
| ASUSTek       | P8H61-M LX2 R2.0            | [2d420c3acb](https://linux-hardware.org/?probe=2d420c3acb) | Jan 20, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [ddf8638851](https://linux-hardware.org/?probe=ddf8638851) | Jan 20, 2023 |
| ASUSTek       | M5A78L-M LE                 | [af00f739f8](https://linux-hardware.org/?probe=af00f739f8) | Jan 20, 2023 |
| Gigabyte      | H61M-D2-B3                  | [e261893ec4](https://linux-hardware.org/?probe=e261893ec4) | Jan 20, 2023 |
| Lenovo        | 3642 SDK0J40700 WIN 3258... | [bb1826bf63](https://linux-hardware.org/?probe=bb1826bf63) | Jan 20, 2023 |
| ECS           | APLD-MINI                   | [78e90e4760](https://linux-hardware.org/?probe=78e90e4760) | Jan 20, 2023 |
| ASRock        | B450M Pro4-F                | [031b7e3b0a](https://linux-hardware.org/?probe=031b7e3b0a) | Jan 20, 2023 |
| Gigabyte      | M61PME-S2                   | [110d9cb0f9](https://linux-hardware.org/?probe=110d9cb0f9) | Jan 20, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [1a80b30106](https://linux-hardware.org/?probe=1a80b30106) | Jan 20, 2023 |
| HP            | 339A                        | [5d86fd4411](https://linux-hardware.org/?probe=5d86fd4411) | Jan 20, 2023 |
| ASUSTek       | PRIME B350M-A               | [17bdbada47](https://linux-hardware.org/?probe=17bdbada47) | Jan 20, 2023 |
| Gigabyte      | G1.SNIPER B7-CF             | [b82a8b3c9e](https://linux-hardware.org/?probe=b82a8b3c9e) | Jan 20, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [1320f35331](https://linux-hardware.org/?probe=1320f35331) | Jan 20, 2023 |
| Pegatron      | Narra6                      | [ac9462ee8e](https://linux-hardware.org/?probe=ac9462ee8e) | Jan 20, 2023 |
| MSI           | B560M-A PRO                 | [b7771b2b5d](https://linux-hardware.org/?probe=b7771b2b5d) | Jan 19, 2023 |
| BESSTAR Te... | UM350                       | [4a2292e809](https://linux-hardware.org/?probe=4a2292e809) | Jan 19, 2023 |
| Gigabyte      | G31M-ES2L                   | [79a45b9ea0](https://linux-hardware.org/?probe=79a45b9ea0) | Jan 19, 2023 |
| Intel         | H110                        | [532f2a340e](https://linux-hardware.org/?probe=532f2a340e) | Jan 19, 2023 |
| Gigabyte      | F2A68HM-DS2                 | [0fc911e254](https://linux-hardware.org/?probe=0fc911e254) | Jan 19, 2023 |
| ASRock        | B550M-C                     | [267e3db2cb](https://linux-hardware.org/?probe=267e3db2cb) | Jan 19, 2023 |
| ASUSTek       | PRIME A320M-K               | [b48e8ac2ee](https://linux-hardware.org/?probe=b48e8ac2ee) | Jan 19, 2023 |
| Acer          | Aspire XC-105               | [8192fe90a8](https://linux-hardware.org/?probe=8192fe90a8) | Jan 19, 2023 |
| Gigabyte      | B550M DS3H AC               | [dae35d1c18](https://linux-hardware.org/?probe=dae35d1c18) | Jan 19, 2023 |
| Digitron      | G31T-M7                     | [ee9978ae25](https://linux-hardware.org/?probe=ee9978ae25) | Jan 19, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [35e6e9ba34](https://linux-hardware.org/?probe=35e6e9ba34) | Jan 19, 2023 |
| ASUSTek       | Z77-A                       | [10081492a7](https://linux-hardware.org/?probe=10081492a7) | Jan 19, 2023 |
| MSI           | B550-A PRO[CEC]             | [fc45338444](https://linux-hardware.org/?probe=fc45338444) | Jan 18, 2023 |
| ASRock        | X570 PG Velocita            | [dc43ddb50c](https://linux-hardware.org/?probe=dc43ddb50c) | Jan 18, 2023 |
| ASUSTek       | PRIME B250M-A               | [d2ecbd7302](https://linux-hardware.org/?probe=d2ecbd7302) | Jan 18, 2023 |
| Intel         | H61                         | [be9b2384b0](https://linux-hardware.org/?probe=be9b2384b0) | Jan 18, 2023 |
| ASUSTek       | C60M1-I                     | [defd3912ae](https://linux-hardware.org/?probe=defd3912ae) | Jan 18, 2023 |
| MSI           | H510M-A PRO                 | [9f9fa2e0be](https://linux-hardware.org/?probe=9f9fa2e0be) | Jan 18, 2023 |
| Unknown       | HX90                        | [2b034e44e2](https://linux-hardware.org/?probe=2b034e44e2) | Jan 18, 2023 |
| ASUSTek       | PRIME B450M-K II            | [7f1cfd2c02](https://linux-hardware.org/?probe=7f1cfd2c02) | Jan 18, 2023 |
| Gigabyte      | MZBSWMP-00                  | [8f292282cb](https://linux-hardware.org/?probe=8f292282cb) | Jan 18, 2023 |
| MSI           | Z170A GAMING M7             | [d58a30b560](https://linux-hardware.org/?probe=d58a30b560) | Jan 18, 2023 |
| ASRock        | H110M-HDV R3.0              | [70c0fea989](https://linux-hardware.org/?probe=70c0fea989) | Jan 18, 2023 |
| ASUSTek       | Z87-PRO                     | [8647a8be86](https://linux-hardware.org/?probe=8647a8be86) | Jan 18, 2023 |
| Dell          | 0KWVT8 A03                  | [14b74c6ec1](https://linux-hardware.org/?probe=14b74c6ec1) | Jan 18, 2023 |
| ASRock        | B550M Pro4                  | [b781eb32d2](https://linux-hardware.org/?probe=b781eb32d2) | Jan 18, 2023 |
| HP            | 1589                        | [5b3a7234f6](https://linux-hardware.org/?probe=5b3a7234f6) | Jan 18, 2023 |
| Toshiba       | STI 014293                  | [8e47b89089](https://linux-hardware.org/?probe=8e47b89089) | Jan 18, 2023 |
| Medion        | MS-7621                     | [67b535d88f](https://linux-hardware.org/?probe=67b535d88f) | Jan 18, 2023 |
| Dell          | 0M017G A00                  | [7fa3b1ee60](https://linux-hardware.org/?probe=7fa3b1ee60) | Jan 18, 2023 |
| MSI           | H510M-A PRO                 | [221830de98](https://linux-hardware.org/?probe=221830de98) | Jan 17, 2023 |
| ASUSTek       | PRIME B450M-K II            | [e44a974b71](https://linux-hardware.org/?probe=e44a974b71) | Jan 17, 2023 |
| ASUSTek       | PRIME B450M-K II            | [04e8f0fb25](https://linux-hardware.org/?probe=04e8f0fb25) | Jan 17, 2023 |
| HP            | 3047h                       | [ad1e495439](https://linux-hardware.org/?probe=ad1e495439) | Jan 17, 2023 |
| MSI           | H510M-A PRO                 | [7d05783196](https://linux-hardware.org/?probe=7d05783196) | Jan 17, 2023 |
| ASUSTek       | M4N68T-M-V2                 | [53b9512a96](https://linux-hardware.org/?probe=53b9512a96) | Jan 17, 2023 |
| Gigabyte      | F2A55M-HD2                  | [74a62575d2](https://linux-hardware.org/?probe=74a62575d2) | Jan 17, 2023 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [1a8a1eea59](https://linux-hardware.org/?probe=1a8a1eea59) | Jan 17, 2023 |
| Gigabyte      | H410M S2H V3                | [0e4dd4c424](https://linux-hardware.org/?probe=0e4dd4c424) | Jan 17, 2023 |
| HP            | 2B5E                        | [42896b55bb](https://linux-hardware.org/?probe=42896b55bb) | Jan 17, 2023 |
| Login Info... | LOG-H110M-G3                | [74defcfa62](https://linux-hardware.org/?probe=74defcfa62) | Jan 17, 2023 |
| Dell          | 0KC9NP A01                  | [c48a8fe525](https://linux-hardware.org/?probe=c48a8fe525) | Jan 17, 2023 |
| MSI           | A320M-A PRO MAX             | [5a0f8a7ea6](https://linux-hardware.org/?probe=5a0f8a7ea6) | Jan 17, 2023 |
| ASRock        | G965M-S                     | [c1a6d7685b](https://linux-hardware.org/?probe=c1a6d7685b) | Jan 17, 2023 |
| Gigabyte      | Z170-HD3P-CF                | [851c4f03fc](https://linux-hardware.org/?probe=851c4f03fc) | Jan 17, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [6c3aa30aa8](https://linux-hardware.org/?probe=6c3aa30aa8) | Jan 17, 2023 |
| Gigabyte      | F2A68HM-HD2                 | [fc8a27e6c5](https://linux-hardware.org/?probe=fc8a27e6c5) | Jan 17, 2023 |
| ASRock        | H61M-HVGS                   | [2256e1c087](https://linux-hardware.org/?probe=2256e1c087) | Jan 17, 2023 |
| Acer          | Aspire M5910                | [d2d4e86b49](https://linux-hardware.org/?probe=d2d4e86b49) | Jan 17, 2023 |
| Gigabyte      | H310M H                     | [faa3746295](https://linux-hardware.org/?probe=faa3746295) | Jan 17, 2023 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | [41839ed038](https://linux-hardware.org/?probe=41839ed038) | Jan 17, 2023 |
| Gigabyte      | 945GCM-S2C                  | [23a3b53ebd](https://linux-hardware.org/?probe=23a3b53ebd) | Jan 17, 2023 |
| ASRock        | B550M/ac                    | [6b05cd1500](https://linux-hardware.org/?probe=6b05cd1500) | Jan 17, 2023 |
| Dell          | 01D4TT A00                  | [509404e50f](https://linux-hardware.org/?probe=509404e50f) | Jan 17, 2023 |
| ASUSTek       | M2N68-AM SE2                | [72e3ebc3b8](https://linux-hardware.org/?probe=72e3ebc3b8) | Jan 17, 2023 |
| ASUSTek       | PRIME H410M-E               | [57aec688e4](https://linux-hardware.org/?probe=57aec688e4) | Jan 17, 2023 |
| MSI           | 970A-G43                    | [086e04b65f](https://linux-hardware.org/?probe=086e04b65f) | Jan 17, 2023 |
| ASUSTek       | H81-PLUS                    | [e95534600a](https://linux-hardware.org/?probe=e95534600a) | Jan 16, 2023 |
| Foxconn       | ALOE                        | [0b3564ef16](https://linux-hardware.org/?probe=0b3564ef16) | Jan 16, 2023 |
| Toshiba       | STI 007030                  | [c0eb39ae66](https://linux-hardware.org/?probe=c0eb39ae66) | Jan 16, 2023 |
| Lenovo        | 3102 SDK0K13476 WIN 3306... | [fd843f48f5](https://linux-hardware.org/?probe=fd843f48f5) | Jan 16, 2023 |
| ASUSTek       | P8B75-V                     | [276102bb1a](https://linux-hardware.org/?probe=276102bb1a) | Jan 16, 2023 |
| MSI           | 990FXA-GD80                 | [bbddcc3653](https://linux-hardware.org/?probe=bbddcc3653) | Jan 16, 2023 |
| Dell          | 0M017G A00                  | [ff8b522fba](https://linux-hardware.org/?probe=ff8b522fba) | Jan 16, 2023 |
| Dell          | 0VHWTR A02                  | [c8711437d8](https://linux-hardware.org/?probe=c8711437d8) | Jan 16, 2023 |
| Dell          | 0VHWTR A02                  | [08c2c9425e](https://linux-hardware.org/?probe=08c2c9425e) | Jan 16, 2023 |
| ASUSTek       | PRIME X370-PRO              | [9b1e965bca](https://linux-hardware.org/?probe=9b1e965bca) | Jan 16, 2023 |
| MSI           | Z87-G41 PC Mate             | [7787cf2783](https://linux-hardware.org/?probe=7787cf2783) | Jan 16, 2023 |
| MSI           | H61M-P20                    | [bf79928a7a](https://linux-hardware.org/?probe=bf79928a7a) | Jan 16, 2023 |
| ASRock        | FM2A88X+ Killer             | [ce91a77f1c](https://linux-hardware.org/?probe=ce91a77f1c) | Jan 16, 2023 |
| ASUSTek       | H87M-PLUS                   | [48f796fb17](https://linux-hardware.org/?probe=48f796fb17) | Jan 15, 2023 |
| ASRock        | Z68 Pro3 Gen3               | [242329daf8](https://linux-hardware.org/?probe=242329daf8) | Jan 15, 2023 |
| ASUSTek       | TUF Gaming H470-PRO         | [6d67c981b3](https://linux-hardware.org/?probe=6d67c981b3) | Jan 15, 2023 |
| ASRock        | B450M Pro4                  | [87212d094f](https://linux-hardware.org/?probe=87212d094f) | Jan 15, 2023 |
| Dell          | 0C27VV A00                  | [119d4062db](https://linux-hardware.org/?probe=119d4062db) | Jan 15, 2023 |
| Medion        | MS-7501                     | [abd269d539](https://linux-hardware.org/?probe=abd269d539) | Jan 15, 2023 |
| Gigabyte      | EP43-DS3L                   | [b6b45a8594](https://linux-hardware.org/?probe=b6b45a8594) | Jan 15, 2023 |
| ASRock        | B450 Pro4                   | [4b28ddc6ca](https://linux-hardware.org/?probe=4b28ddc6ca) | Jan 15, 2023 |
| Lenovo        | SDK0F82993 WIN              | [48f294dfb4](https://linux-hardware.org/?probe=48f294dfb4) | Jan 15, 2023 |
| Dell          | 0WK833                      | [100d6694e5](https://linux-hardware.org/?probe=100d6694e5) | Jan 15, 2023 |
| MSI           | Z170A GAMING M5             | [c4f311b801](https://linux-hardware.org/?probe=c4f311b801) | Jan 15, 2023 |
| Gigabyte      | G41M-ES2L                   | [b69b2d21e9](https://linux-hardware.org/?probe=b69b2d21e9) | Jan 15, 2023 |
| Dell          | 0M863N A01                  | [4d7e5c21fc](https://linux-hardware.org/?probe=4d7e5c21fc) | Jan 15, 2023 |
| ASUSTek       | PRIME A320M-K               | [7fefb8d34c](https://linux-hardware.org/?probe=7fefb8d34c) | Jan 15, 2023 |
| Gigabyte      | B560M DS3H                  | [be77d8e20d](https://linux-hardware.org/?probe=be77d8e20d) | Jan 15, 2023 |
| BESSTAR Te... | UM340                       | [c6abd16019](https://linux-hardware.org/?probe=c6abd16019) | Jan 15, 2023 |
| ASUSTek       | P5B-VM                      | [53b563ef2f](https://linux-hardware.org/?probe=53b563ef2f) | Jan 15, 2023 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | [34e15e96ea](https://linux-hardware.org/?probe=34e15e96ea) | Jan 15, 2023 |
| Gateway       | SX2110GA                    | [9e5e1cbe03](https://linux-hardware.org/?probe=9e5e1cbe03) | Jan 15, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [d95820725a](https://linux-hardware.org/?probe=d95820725a) | Jan 15, 2023 |
| ASRock        | B550M-ITX/ac                | [80ba7958b2](https://linux-hardware.org/?probe=80ba7958b2) | Jan 15, 2023 |
| PLEXHD        | X79T rev. V1.0              | [9c8c729f1c](https://linux-hardware.org/?probe=9c8c729f1c) | Jan 15, 2023 |
| ASUSTek       | STRIX Z270I GAMING          | [6ff8ef1eb3](https://linux-hardware.org/?probe=6ff8ef1eb3) | Jan 15, 2023 |
| MSI           | Z97-GD65 GAMING             | [da67dabbd2](https://linux-hardware.org/?probe=da67dabbd2) | Jan 15, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [291dceb273](https://linux-hardware.org/?probe=291dceb273) | Jan 14, 2023 |
| ASUSTek       | M5A97 R2.0                  | [182fdab654](https://linux-hardware.org/?probe=182fdab654) | Jan 14, 2023 |
| Intel         | D34010WYK H14771-302        | [7c336f50d2](https://linux-hardware.org/?probe=7c336f50d2) | Jan 14, 2023 |
| Acer          | Aspire XC-830               | [1d9206b1f1](https://linux-hardware.org/?probe=1d9206b1f1) | Jan 14, 2023 |
| Gigabyte      | Z97M-D3H                    | [305ff29dad](https://linux-hardware.org/?probe=305ff29dad) | Jan 14, 2023 |
| MSI           | B450M MORTAR MAX            | [1e42d818dd](https://linux-hardware.org/?probe=1e42d818dd) | Jan 14, 2023 |
| ASRock        | H110 Pro BTC+               | [306cc23f03](https://linux-hardware.org/?probe=306cc23f03) | Jan 14, 2023 |
| ASUSTek       | PRIME H310M-E               | [7732b2e5e1](https://linux-hardware.org/?probe=7732b2e5e1) | Jan 14, 2023 |
| Gigabyte      | H410M H                     | [85605e8c5b](https://linux-hardware.org/?probe=85605e8c5b) | Jan 14, 2023 |
| Gigabyte      | B550M AORUS PRO             | [0b375cb78b](https://linux-hardware.org/?probe=0b375cb78b) | Jan 14, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | [b77188ec3e](https://linux-hardware.org/?probe=b77188ec3e) | Jan 14, 2023 |
| HP            | 18E4                        | [64ced7ce97](https://linux-hardware.org/?probe=64ced7ce97) | Jan 14, 2023 |
| Gigabyte      | H55M-UD2H                   | [a14f62fa30](https://linux-hardware.org/?probe=a14f62fa30) | Jan 14, 2023 |
| Gigabyte      | F2A88XM-D3H                 | [5b24b51770](https://linux-hardware.org/?probe=5b24b51770) | Jan 14, 2023 |
| ASUSTek       | PRIME X570-P                | [32026c5c05](https://linux-hardware.org/?probe=32026c5c05) | Jan 14, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [67d3d3c57a](https://linux-hardware.org/?probe=67d3d3c57a) | Jan 14, 2023 |
| ASRock        | 970M Pro3                   | [041c698c85](https://linux-hardware.org/?probe=041c698c85) | Jan 14, 2023 |
| ASRock        | B450M Pro4                  | [3ae4aad8a2](https://linux-hardware.org/?probe=3ae4aad8a2) | Jan 14, 2023 |
| ASUSTek       | H110M-K                     | [8975ee2ce6](https://linux-hardware.org/?probe=8975ee2ce6) | Jan 14, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [63ae151c66](https://linux-hardware.org/?probe=63ae151c66) | Jan 14, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [7f29ebf729](https://linux-hardware.org/?probe=7f29ebf729) | Jan 14, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [9774dee993](https://linux-hardware.org/?probe=9774dee993) | Jan 14, 2023 |
| MACHINIST     | B75 PRO V1.0                | [c0728b5e41](https://linux-hardware.org/?probe=c0728b5e41) | Jan 14, 2023 |
| Gigabyte      | Z77-D3H                     | [d09a603b10](https://linux-hardware.org/?probe=d09a603b10) | Jan 14, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [79d2961429](https://linux-hardware.org/?probe=79d2961429) | Jan 14, 2023 |
| Gigabyte      | B85M-D3H                    | [c54bd7b409](https://linux-hardware.org/?probe=c54bd7b409) | Jan 14, 2023 |
| HP            | 8054                        | [faf1c97cea](https://linux-hardware.org/?probe=faf1c97cea) | Jan 14, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | [1a25eeba6f](https://linux-hardware.org/?probe=1a25eeba6f) | Jan 14, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [dc3317fe82](https://linux-hardware.org/?probe=dc3317fe82) | Jan 14, 2023 |
| HP            | 18E5                        | [614faa708b](https://linux-hardware.org/?probe=614faa708b) | Jan 14, 2023 |
| ASUSTek       | GL10DH                      | [c1f3c3b1c4](https://linux-hardware.org/?probe=c1f3c3b1c4) | Jan 14, 2023 |
| MSI           | X99A SLI PLUS               | [4ab9753ab5](https://linux-hardware.org/?probe=4ab9753ab5) | Jan 14, 2023 |
| ASUSTek       | TUF Gaming B660M-E D4       | [79753b9bcd](https://linux-hardware.org/?probe=79753b9bcd) | Jan 14, 2023 |
| Gigabyte      | B75M-D2V                    | [8f9d1f85ee](https://linux-hardware.org/?probe=8f9d1f85ee) | Jan 14, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [ed18454667](https://linux-hardware.org/?probe=ed18454667) | Jan 14, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [c541b9f1cd](https://linux-hardware.org/?probe=c541b9f1cd) | Jan 14, 2023 |
| Pegatron      | IPM41-D3                    | [23a918874b](https://linux-hardware.org/?probe=23a918874b) | Jan 14, 2023 |
| MSI           | B450 TOMAHAWK               | [ebb69311f7](https://linux-hardware.org/?probe=ebb69311f7) | Jan 14, 2023 |
| Dell          | 0P01GV A03                  | [0d1982257b](https://linux-hardware.org/?probe=0d1982257b) | Jan 13, 2023 |
| Lenovo        | ThinkCentre XXXX 7360EHF    | [fdfe8c5881](https://linux-hardware.org/?probe=fdfe8c5881) | Jan 13, 2023 |
| ASRock        | 970M Pro3                   | [692331d7d2](https://linux-hardware.org/?probe=692331d7d2) | Jan 13, 2023 |
| PCWare        | IPX1800E2                   | [57e454fc85](https://linux-hardware.org/?probe=57e454fc85) | Jan 13, 2023 |
| MSI           | Z370 GAMING PRO CARBON      | [05f1e26e96](https://linux-hardware.org/?probe=05f1e26e96) | Jan 13, 2023 |
| MSI           | A320M-A PRO MAX             | [d2c2664a15](https://linux-hardware.org/?probe=d2c2664a15) | Jan 13, 2023 |
| Gigabyte      | 970A-DS3                    | [c6819f38a0](https://linux-hardware.org/?probe=c6819f38a0) | Jan 13, 2023 |
| MSI           | B560M-A PRO                 | [182428165f](https://linux-hardware.org/?probe=182428165f) | Jan 13, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [dc7954e720](https://linux-hardware.org/?probe=dc7954e720) | Jan 13, 2023 |
| ASRock        | Z68 Pro3                    | [40c7685a12](https://linux-hardware.org/?probe=40c7685a12) | Jan 13, 2023 |
| Biostar       | B250MHC                     | [100bfd62e6](https://linux-hardware.org/?probe=100bfd62e6) | Jan 13, 2023 |
| HP            | 8643 SMVB                   | [f00915b680](https://linux-hardware.org/?probe=f00915b680) | Jan 13, 2023 |
| Fujitsu       | D3401-A1 S26361-D3401-A1    | [6cc45bde0b](https://linux-hardware.org/?probe=6cc45bde0b) | Jan 13, 2023 |
| ASUSTek       | Z170-DELUXE                 | [433bc4fddd](https://linux-hardware.org/?probe=433bc4fddd) | Jan 13, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [ba09b2045b](https://linux-hardware.org/?probe=ba09b2045b) | Jan 13, 2023 |
| Biostar       | G41D3+                      | [f610665116](https://linux-hardware.org/?probe=f610665116) | Jan 13, 2023 |
| Gigabyte      | B75M-D3H                    | [cfa8ec5fcb](https://linux-hardware.org/?probe=cfa8ec5fcb) | Jan 13, 2023 |
| ASUSTek       | B85M-G                      | [8c2c6b3355](https://linux-hardware.org/?probe=8c2c6b3355) | Jan 13, 2023 |
| MSI           | H310M PRO-VD PLUS           | [e33042f453](https://linux-hardware.org/?probe=e33042f453) | Jan 13, 2023 |
| MSI           | B450M MORTAR MAX            | [e840ab1f61](https://linux-hardware.org/?probe=e840ab1f61) | Jan 13, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [c331071e8a](https://linux-hardware.org/?probe=c331071e8a) | Jan 13, 2023 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [12f29d53ba](https://linux-hardware.org/?probe=12f29d53ba) | Jan 13, 2023 |
| MSI           | A68HM-E33                   | [8e81067cd2](https://linux-hardware.org/?probe=8e81067cd2) | Jan 13, 2023 |
| HP            | 2ADC                        | [69bb1386c0](https://linux-hardware.org/?probe=69bb1386c0) | Jan 13, 2023 |
| ECS           | H81H3-M4                    | [08638b9441](https://linux-hardware.org/?probe=08638b9441) | Jan 13, 2023 |
| MSI           | Z490-A PRO                  | [c3063ff121](https://linux-hardware.org/?probe=c3063ff121) | Jan 13, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [178c6f90fa](https://linux-hardware.org/?probe=178c6f90fa) | Jan 13, 2023 |
| ASUSTek       | H110S2                      | [d783389831](https://linux-hardware.org/?probe=d783389831) | Jan 13, 2023 |
| Pegatron      | IPM31G                      | [04e04dc57b](https://linux-hardware.org/?probe=04e04dc57b) | Jan 12, 2023 |
| HP            | 21F5                        | [141aa3faa6](https://linux-hardware.org/?probe=141aa3faa6) | Jan 12, 2023 |
| ASRock        | B450M Pro4                  | [da5cb78b32](https://linux-hardware.org/?probe=da5cb78b32) | Jan 12, 2023 |
| MSI           | B550-A PRO                  | [a71025c173](https://linux-hardware.org/?probe=a71025c173) | Jan 12, 2023 |
| ASUSTek       | PRIME H510M-A               | [252041601b](https://linux-hardware.org/?probe=252041601b) | Jan 12, 2023 |
| ASRock        | B450M Steel Legend          | [8309c81fdf](https://linux-hardware.org/?probe=8309c81fdf) | Jan 12, 2023 |
| Gigabyte      | H110M-S2H-CF                | [bd4173beb3](https://linux-hardware.org/?probe=bd4173beb3) | Jan 12, 2023 |
| Lenovo        | 3102 SDK0K17763 WIN 1801... | [a3ce2fe598](https://linux-hardware.org/?probe=a3ce2fe598) | Jan 12, 2023 |
| Fujitsu Si... | D2804-A1 S26361-D2804-A1    | [2cf01973f4](https://linux-hardware.org/?probe=2cf01973f4) | Jan 12, 2023 |
| Fujitsu       | D3654-C1 S26361-D3654-C1    | [0d5c20b240](https://linux-hardware.org/?probe=0d5c20b240) | Jan 12, 2023 |
| Dell          | 0Y5DDC A00                  | [76d5a2b12b](https://linux-hardware.org/?probe=76d5a2b12b) | Jan 12, 2023 |
| MSI           | B450 GAMING PLUS            | [48effb0720](https://linux-hardware.org/?probe=48effb0720) | Jan 12, 2023 |
| ASRock        | H170M Pro4                  | [15648a0bb0](https://linux-hardware.org/?probe=15648a0bb0) | Jan 12, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [190d9b58b8](https://linux-hardware.org/?probe=190d9b58b8) | Jan 12, 2023 |
| HP            | 87D6 SMVB                   | [cf2b65f039](https://linux-hardware.org/?probe=cf2b65f039) | Jan 12, 2023 |
| Lenovo        | Win8 Pro DPK TPG            | [cc5b67471e](https://linux-hardware.org/?probe=cc5b67471e) | Jan 12, 2023 |
| Gigabyte      | P55-US3L                    | [49e7dc9b0b](https://linux-hardware.org/?probe=49e7dc9b0b) | Jan 12, 2023 |
| Dell          | 0X9M3X A01                  | [0dd66e3ec4](https://linux-hardware.org/?probe=0dd66e3ec4) | Jan 12, 2023 |
| Gigabyte      | GA-880GM-UD2H               | [ab77db0611](https://linux-hardware.org/?probe=ab77db0611) | Jan 12, 2023 |
| Gigabyte      | G41MT-S2                    | [25b6ab4c75](https://linux-hardware.org/?probe=25b6ab4c75) | Jan 12, 2023 |
| ASUSTek       | H81M-K                      | [8c3dc4bac3](https://linux-hardware.org/?probe=8c3dc4bac3) | Jan 12, 2023 |
| MSI           | Z170A GAMING M3             | [28a76b6042](https://linux-hardware.org/?probe=28a76b6042) | Jan 12, 2023 |
| Acer          | Aspire M3450                | [0ed84a21b2](https://linux-hardware.org/?probe=0ed84a21b2) | Jan 12, 2023 |
| ASUSTek       | G11CD                       | [f39178befb](https://linux-hardware.org/?probe=f39178befb) | Jan 12, 2023 |
| HP            | 8648                        | [df76c90c20](https://linux-hardware.org/?probe=df76c90c20) | Jan 12, 2023 |
| ASRock        | Z97 Pro4                    | [575b855a32](https://linux-hardware.org/?probe=575b855a32) | Jan 12, 2023 |
| Dell          | 0T1D10 A01                  | [6b01c0475f](https://linux-hardware.org/?probe=6b01c0475f) | Jan 12, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [1a68bed616](https://linux-hardware.org/?probe=1a68bed616) | Jan 12, 2023 |
| Lenovo        | 317E SDK0J40700 WIN 3258... | [fd6ec2fcb0](https://linux-hardware.org/?probe=fd6ec2fcb0) | Jan 12, 2023 |
| MSI           | Z97A SLI Krait Edition      | [a392a885f1](https://linux-hardware.org/?probe=a392a885f1) | Jan 12, 2023 |
| EVGA          | X570 DARK.0                 | [69ff77b438](https://linux-hardware.org/?probe=69ff77b438) | Jan 12, 2023 |
| Gigabyte      | X570S UD                    | [e3458505fd](https://linux-hardware.org/?probe=e3458505fd) | Jan 12, 2023 |
| Gigabyte      | B450 AORUS M                | [a1f2661396](https://linux-hardware.org/?probe=a1f2661396) | Jan 11, 2023 |
| MSI           | X370 SLI PLUS               | [201f89bdd9](https://linux-hardware.org/?probe=201f89bdd9) | Jan 11, 2023 |
| ASRock        | FM2A68M-DG3+                | [acc9ea9c40](https://linux-hardware.org/?probe=acc9ea9c40) | Jan 11, 2023 |
| ECS           | A55F-M2                     | [b891de98a1](https://linux-hardware.org/?probe=b891de98a1) | Jan 11, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [e608d09ac5](https://linux-hardware.org/?probe=e608d09ac5) | Jan 11, 2023 |
| Intel         | DQ35JO AAD82085-803         | [e45bb07b6d](https://linux-hardware.org/?probe=e45bb07b6d) | Jan 11, 2023 |
| MSI           | PRO H610M-B DDR4            | [1d6a667a5b](https://linux-hardware.org/?probe=1d6a667a5b) | Jan 11, 2023 |
| Dell          | 0MN1TX A02                  | [e0099da561](https://linux-hardware.org/?probe=e0099da561) | Jan 11, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [366e5b92d7](https://linux-hardware.org/?probe=366e5b92d7) | Jan 11, 2023 |
| HP            | 304Ah                       | [c79a932800](https://linux-hardware.org/?probe=c79a932800) | Jan 11, 2023 |
| ELSKY         | QM10u                       | [c9bde314b5](https://linux-hardware.org/?probe=c9bde314b5) | Jan 11, 2023 |
| HP            | 3397                        | [0057e1b40e](https://linux-hardware.org/?probe=0057e1b40e) | Jan 11, 2023 |
| HP            | 18E4                        | [9cad3411ab](https://linux-hardware.org/?probe=9cad3411ab) | Jan 11, 2023 |
| Gigabyte      | H81M-S2PV                   | [72e7e2e1cf](https://linux-hardware.org/?probe=72e7e2e1cf) | Jan 11, 2023 |
| HP            | 82A2                        | [21321971f7](https://linux-hardware.org/?probe=21321971f7) | Jan 11, 2023 |
| Lenovo        | 30C7 SDK0J40700 WIN 3258... | [994306b125](https://linux-hardware.org/?probe=994306b125) | Jan 11, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [72eca4e860](https://linux-hardware.org/?probe=72eca4e860) | Jan 11, 2023 |
| Dell          | 0HN7XN A01                  | [f0ba373485](https://linux-hardware.org/?probe=f0ba373485) | Jan 11, 2023 |
| HP            | 83F2                        | [7482186165](https://linux-hardware.org/?probe=7482186165) | Jan 11, 2023 |
| HP            | 8906 SMVB                   | [7d56f2f733](https://linux-hardware.org/?probe=7d56f2f733) | Jan 11, 2023 |
| Gigabyte      | F2A78M-D3H                  | [28d357840c](https://linux-hardware.org/?probe=28d357840c) | Jan 11, 2023 |
| ASUSTek       | Z170-A                      | [0f0b38970a](https://linux-hardware.org/?probe=0f0b38970a) | Jan 11, 2023 |
| Dell          | 054KM3 A00                  | [4ea59c00f3](https://linux-hardware.org/?probe=4ea59c00f3) | Jan 11, 2023 |
| Gigabyte      | B550M DS3H                  | [1058c3d279](https://linux-hardware.org/?probe=1058c3d279) | Jan 11, 2023 |
| HP            | 87D6 SMVB                   | [da121a82bd](https://linux-hardware.org/?probe=da121a82bd) | Jan 11, 2023 |
| ASUSTek       | PRIME A320M-K               | [46679246b9](https://linux-hardware.org/?probe=46679246b9) | Jan 11, 2023 |
| Lenovo        | SDK0E50510 WIN 262508703... | [23733b2174](https://linux-hardware.org/?probe=23733b2174) | Jan 11, 2023 |
| Gigabyte      | Z790 AERO G                 | [0d6b77da1a](https://linux-hardware.org/?probe=0d6b77da1a) | Jan 11, 2023 |
| Gigabyte      | M68MT-S2P                   | [97f4c3c67a](https://linux-hardware.org/?probe=97f4c3c67a) | Jan 11, 2023 |
| HP            | 18E7                        | [a714978ee0](https://linux-hardware.org/?probe=a714978ee0) | Jan 11, 2023 |
| ASUSTek       | PRIME B360M-A               | [75584dc48c](https://linux-hardware.org/?probe=75584dc48c) | Jan 11, 2023 |
| Acer          | Veriton X2640G V:1.0        | [0daf81fe54](https://linux-hardware.org/?probe=0daf81fe54) | Jan 11, 2023 |
| Dell          | 0D28YY A00                  | [736f7a2f65](https://linux-hardware.org/?probe=736f7a2f65) | Jan 11, 2023 |
| HP            | 3047h                       | [0dd7c7c08f](https://linux-hardware.org/?probe=0dd7c7c08f) | Jan 11, 2023 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | [1705a3f042](https://linux-hardware.org/?probe=1705a3f042) | Jan 11, 2023 |
| ASUSTek       | PRIME B450M-A II            | [744948f1ee](https://linux-hardware.org/?probe=744948f1ee) | Jan 10, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | [805d82d697](https://linux-hardware.org/?probe=805d82d697) | Jan 10, 2023 |
| HP            | 3029h                       | [00d4bd6122](https://linux-hardware.org/?probe=00d4bd6122) | Jan 10, 2023 |
| Pegatron      | Benicia                     | [3a64456800](https://linux-hardware.org/?probe=3a64456800) | Jan 10, 2023 |
| Gigabyte      | B450M AORUS ELITE           | [f4d9052764](https://linux-hardware.org/?probe=f4d9052764) | Jan 10, 2023 |
| Gigabyte      | X79-UP4                     | [89397e1c47](https://linux-hardware.org/?probe=89397e1c47) | Jan 10, 2023 |
| HP            | 8433 11                     | [2036bb2c1a](https://linux-hardware.org/?probe=2036bb2c1a) | Jan 10, 2023 |
| ASUSTek       | BT6130                      | [53c9ec0145](https://linux-hardware.org/?probe=53c9ec0145) | Jan 10, 2023 |
| Gigabyte      | H61M-S2PV                   | [8248661973](https://linux-hardware.org/?probe=8248661973) | Jan 10, 2023 |
| ASUSTek       | PRIME Z690-P                | [6181f2fd4a](https://linux-hardware.org/?probe=6181f2fd4a) | Jan 10, 2023 |
| ASUSTek       | M5A97 R2.0                  | [333595c9de](https://linux-hardware.org/?probe=333595c9de) | Jan 10, 2023 |
| MSI           | MAG X570S TORPEDO MAX       | [71f6d7912a](https://linux-hardware.org/?probe=71f6d7912a) | Jan 10, 2023 |
| Gigabyte      | EP45-DS3                    | [5bf59df74c](https://linux-hardware.org/?probe=5bf59df74c) | Jan 10, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [8c480c028a](https://linux-hardware.org/?probe=8c480c028a) | Jan 10, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [f91cb1b0e7](https://linux-hardware.org/?probe=f91cb1b0e7) | Jan 10, 2023 |
| ECS           | G31T-M7                     | [161442b256](https://linux-hardware.org/?probe=161442b256) | Jan 10, 2023 |
| Dell          | 0HR330                      | [ea19c0e95b](https://linux-hardware.org/?probe=ea19c0e95b) | Jan 10, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [eefd133e1f](https://linux-hardware.org/?probe=eefd133e1f) | Jan 10, 2023 |
| ASUSTek       | PRIME H310M-K               | [146f307b8e](https://linux-hardware.org/?probe=146f307b8e) | Jan 10, 2023 |
| ASUSTek       | TUF B450-PRO GAMING         | [19658b1d4e](https://linux-hardware.org/?probe=19658b1d4e) | Jan 10, 2023 |
| Gigabyte      | H97M-Gaming 3               | [22ee51c3f8](https://linux-hardware.org/?probe=22ee51c3f8) | Jan 10, 2023 |
| ECS           | BSWI-D2                     | [74f6bf3564](https://linux-hardware.org/?probe=74f6bf3564) | Jan 10, 2023 |
| Dell          | 0M5DCD A00                  | [4f6e8d1ac5](https://linux-hardware.org/?probe=4f6e8d1ac5) | Jan 10, 2023 |
| Gigabyte      | B450M DS3H-CF               | [d1c53542d8](https://linux-hardware.org/?probe=d1c53542d8) | Jan 10, 2023 |
| HP            | 82F2 A01                    | [6fdcfd6469](https://linux-hardware.org/?probe=6fdcfd6469) | Jan 10, 2023 |
| ASUSTek       | M5A78L-M LE/USB3            | [e6ecb9037e](https://linux-hardware.org/?probe=e6ecb9037e) | Jan 10, 2023 |
| ASUSTek       | ROG Maximus Z690 APEX       | [51261623fa](https://linux-hardware.org/?probe=51261623fa) | Jan 10, 2023 |
| ASUSTek       | H110M-A/M.2                 | [5656924057](https://linux-hardware.org/?probe=5656924057) | Jan 10, 2023 |
| ASUSTek       | PRIME Z390M-PLUS            | [b0475049e8](https://linux-hardware.org/?probe=b0475049e8) | Jan 10, 2023 |
| Gigabyte      | A520M DS3H                  | [d4ea636610](https://linux-hardware.org/?probe=d4ea636610) | Jan 10, 2023 |
| MSI           | B450M MORTAR MAX            | [36530dbc41](https://linux-hardware.org/?probe=36530dbc41) | Jan 10, 2023 |
| Intel         | DZ77GA-70K AAG39009-500     | [c40b7ab05c](https://linux-hardware.org/?probe=c40b7ab05c) | Jan 10, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [3eb47733df](https://linux-hardware.org/?probe=3eb47733df) | Jan 10, 2023 |
| ASUSTek       | PRIME B450M-A               | [be24cf68d4](https://linux-hardware.org/?probe=be24cf68d4) | Jan 10, 2023 |
| Gigabyte      | H170-D3H-CF                 | [8064745798](https://linux-hardware.org/?probe=8064745798) | Jan 10, 2023 |
| Gigabyte      | H110M-S2HP-CF               | [061e82a658](https://linux-hardware.org/?probe=061e82a658) | Jan 09, 2023 |
| Gigabyte      | Z370 HD3P-CF                | [5ac16a435c](https://linux-hardware.org/?probe=5ac16a435c) | Jan 09, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [ec34483710](https://linux-hardware.org/?probe=ec34483710) | Jan 09, 2023 |
| Fujitsu       | D3348-A1 S26361-D3348-A1    | [45b391774f](https://linux-hardware.org/?probe=45b391774f) | Jan 09, 2023 |
| MSI           | MS-B0A21                    | [1905ffef34](https://linux-hardware.org/?probe=1905ffef34) | Jan 09, 2023 |
| HP            | 1850                        | [2f158b74c6](https://linux-hardware.org/?probe=2f158b74c6) | Jan 09, 2023 |
| Gigabyte      | H61N-USB3                   | [fd5a06c33f](https://linux-hardware.org/?probe=fd5a06c33f) | Jan 09, 2023 |
| ASUSTek       | P7H55-M PRO                 | [f2895e4b94](https://linux-hardware.org/?probe=f2895e4b94) | Jan 09, 2023 |
| Pegatron      | 2ACF                        | [c8ebabadf8](https://linux-hardware.org/?probe=c8ebabadf8) | Jan 09, 2023 |
| HP            | 82B4                        | [889e00de1c](https://linux-hardware.org/?probe=889e00de1c) | Jan 09, 2023 |
| SYWZ          | S210HA Series               | [0cabf3b51e](https://linux-hardware.org/?probe=0cabf3b51e) | Jan 09, 2023 |
| Gigabyte      | GA-MA74GM-S2                | [691c4c5380](https://linux-hardware.org/?probe=691c4c5380) | Jan 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [1f77d36501](https://linux-hardware.org/?probe=1f77d36501) | Jan 09, 2023 |
| Dell          | 0RY007                      | [a57bb8137b](https://linux-hardware.org/?probe=a57bb8137b) | Jan 09, 2023 |
| MSI           | B550-A PRO                  | [183b311eb2](https://linux-hardware.org/?probe=183b311eb2) | Jan 09, 2023 |
| MSI           | MS-7378                     | [965cd11e84](https://linux-hardware.org/?probe=965cd11e84) | Jan 09, 2023 |
| MSI           | Z77A-GD65                   | [f4b0c86cfa](https://linux-hardware.org/?probe=f4b0c86cfa) | Jan 09, 2023 |
| Dell          | 0GY6Y8 A02                  | [29fb2659fd](https://linux-hardware.org/?probe=29fb2659fd) | Jan 09, 2023 |
| MSI           | MAG B550M MORTAR            | [1549344aef](https://linux-hardware.org/?probe=1549344aef) | Jan 09, 2023 |
| ASUSTek       | GR8 II-K                    | [8a78bd7c0c](https://linux-hardware.org/?probe=8a78bd7c0c) | Jan 09, 2023 |
| MSI           | FM2-A75MA-E35               | [4bbe8325bd](https://linux-hardware.org/?probe=4bbe8325bd) | Jan 09, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [af255fa9f7](https://linux-hardware.org/?probe=af255fa9f7) | Jan 09, 2023 |
| ASUSTek       | PRIME B360M-A               | [d903601066](https://linux-hardware.org/?probe=d903601066) | Jan 09, 2023 |
| ASRock        | H87 Performance             | [8e1b7a9033](https://linux-hardware.org/?probe=8e1b7a9033) | Jan 09, 2023 |
| ASUSTek       | Z97M-PLUS                   | [6746287398](https://linux-hardware.org/?probe=6746287398) | Jan 09, 2023 |
| Gigabyte      | B85M-D2V                    | [03dd6fafbb](https://linux-hardware.org/?probe=03dd6fafbb) | Jan 09, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [8a9affbdfd](https://linux-hardware.org/?probe=8a9affbdfd) | Jan 09, 2023 |
| Dell          | 0K3CM7 A00                  | [4e7bbe1c34](https://linux-hardware.org/?probe=4e7bbe1c34) | Jan 09, 2023 |
| Acer          | Veriton N4660G              | [8f27f893b1](https://linux-hardware.org/?probe=8f27f893b1) | Jan 09, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [29ac3deef8](https://linux-hardware.org/?probe=29ac3deef8) | Jan 09, 2023 |
| HP            | 0AA4h                       | [e0776de36f](https://linux-hardware.org/?probe=e0776de36f) | Jan 09, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [56d0991873](https://linux-hardware.org/?probe=56d0991873) | Jan 09, 2023 |
| Gigabyte      | 965P-DS3                    | [1b27c7404f](https://linux-hardware.org/?probe=1b27c7404f) | Jan 09, 2023 |
| Dell          | 0MGK50 A02                  | [045695f1d5](https://linux-hardware.org/?probe=045695f1d5) | Jan 09, 2023 |
| HP            | 802F                        | [1dd3655605](https://linux-hardware.org/?probe=1dd3655605) | Jan 09, 2023 |
| Gigabyte      | J1900N-D2H                  | [62be43a4a3](https://linux-hardware.org/?probe=62be43a4a3) | Jan 09, 2023 |
| ASRock        | X470 Taichi                 | [9312051b13](https://linux-hardware.org/?probe=9312051b13) | Jan 09, 2023 |
| Dell          | 088DT1 A00                  | [f7632cc6ba](https://linux-hardware.org/?probe=f7632cc6ba) | Jan 09, 2023 |
| ASRock        | 980DE3/U3S3                 | [92d7b143d8](https://linux-hardware.org/?probe=92d7b143d8) | Jan 09, 2023 |
| ASUSTek       | P8H61-M LX3 R2.0            | [699eb66c12](https://linux-hardware.org/?probe=699eb66c12) | Jan 09, 2023 |
| ASRock        | AB350 Pro4                  | [66805743c5](https://linux-hardware.org/?probe=66805743c5) | Jan 09, 2023 |
| Gigabyte      | B560M DS3H AC               | [3b4f027444](https://linux-hardware.org/?probe=3b4f027444) | Jan 09, 2023 |
| Gigabyte      | Z77-D3H                     | [8d02a61d53](https://linux-hardware.org/?probe=8d02a61d53) | Jan 09, 2023 |
| Gigabyte      | B85M-HD3                    | [9b25d7ee46](https://linux-hardware.org/?probe=9b25d7ee46) | Jan 09, 2023 |
| Gigabyte      | Z68XP-UD3                   | [e2f62062de](https://linux-hardware.org/?probe=e2f62062de) | Jan 09, 2023 |
| Gigabyte      | B660M DS3H DDR4             | [2ef8678dd1](https://linux-hardware.org/?probe=2ef8678dd1) | Jan 09, 2023 |
| Gigabyte      | B450M DS3H-CF               | [4dd5ee2fa8](https://linux-hardware.org/?probe=4dd5ee2fa8) | Jan 09, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | [50032f13ef](https://linux-hardware.org/?probe=50032f13ef) | Jan 09, 2023 |
| Gigabyte      | A520M AORUS ELITE           | [053d4d7c4b](https://linux-hardware.org/?probe=053d4d7c4b) | Jan 09, 2023 |
| Dell          | 0M9KCM A02                  | [8df180f808](https://linux-hardware.org/?probe=8df180f808) | Jan 09, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | [33d864b46a](https://linux-hardware.org/?probe=33d864b46a) | Jan 09, 2023 |
| Dell          | 0654JC A01                  | [c3016e1823](https://linux-hardware.org/?probe=c3016e1823) | Jan 09, 2023 |
| ECS           | G31T-M                      | [a4d5bf52bd](https://linux-hardware.org/?probe=a4d5bf52bd) | Jan 09, 2023 |
| MSI           | PRO B550M-P GEN3            | [5b62f9f024](https://linux-hardware.org/?probe=5b62f9f024) | Jan 09, 2023 |
| ASUSTek       | J1900I-C                    | [6a2ef2080d](https://linux-hardware.org/?probe=6a2ef2080d) | Jan 09, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [3fdcef1927](https://linux-hardware.org/?probe=3fdcef1927) | Jan 09, 2023 |
| Acer          | H57M01                      | [41ee28ae4b](https://linux-hardware.org/?probe=41ee28ae4b) | Jan 09, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [7292771aad](https://linux-hardware.org/?probe=7292771aad) | Jan 09, 2023 |
| ASUSTek       | P5QL PRO                    | [1f97553f11](https://linux-hardware.org/?probe=1f97553f11) | Jan 08, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [8ddf09108e](https://linux-hardware.org/?probe=8ddf09108e) | Jan 08, 2023 |
| ASUSTek       | PRIME B450M-A               | [21354f2103](https://linux-hardware.org/?probe=21354f2103) | Jan 08, 2023 |
| Dell          | 084J0R A00                  | [7aaeb8fbfc](https://linux-hardware.org/?probe=7aaeb8fbfc) | Jan 08, 2023 |
| Dell          | 0WG855                      | [0a2e7733bf](https://linux-hardware.org/?probe=0a2e7733bf) | Jan 08, 2023 |
| ASUSTek       | PRIME Z590-A                | [2d9714284d](https://linux-hardware.org/?probe=2d9714284d) | Jan 08, 2023 |
| ASUSTek       | PRIME A320M-K               | [61f4028846](https://linux-hardware.org/?probe=61f4028846) | Jan 08, 2023 |
| ASUSTek       | PRIME H410M-R               | [cfc6e0c455](https://linux-hardware.org/?probe=cfc6e0c455) | Jan 08, 2023 |
| ASUSTek       | M5A97 R2.0                  | [ca7597c4fb](https://linux-hardware.org/?probe=ca7597c4fb) | Jan 08, 2023 |
| ASUSTek       | PRIME B550-PLUS AC-HES      | [3b96cc0df8](https://linux-hardware.org/?probe=3b96cc0df8) | Jan 08, 2023 |
| Gigabyte      | GA-MA770T-UD3               | [8ef8c9baa7](https://linux-hardware.org/?probe=8ef8c9baa7) | Jan 08, 2023 |
| MSI           | X570-A PRO                  | [cccac0a924](https://linux-hardware.org/?probe=cccac0a924) | Jan 08, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E EXTR... | [58839b1334](https://linux-hardware.org/?probe=58839b1334) | Jan 08, 2023 |
| Gigabyte      | 990XA-UD3                   | [1c85ed2f4b](https://linux-hardware.org/?probe=1c85ed2f4b) | Jan 08, 2023 |
| MSI           | B450M MORTAR MAX            | [474907a53e](https://linux-hardware.org/?probe=474907a53e) | Jan 08, 2023 |
| Pegatron      | 2ACD                        | [29d4752ccf](https://linux-hardware.org/?probe=29d4752ccf) | Jan 08, 2023 |
| Dell          | 0P01GV A03                  | [c343ff064d](https://linux-hardware.org/?probe=c343ff064d) | Jan 08, 2023 |
| ASUSTek       | PRIME Z270-P                | [b39a58c2e6](https://linux-hardware.org/?probe=b39a58c2e6) | Jan 08, 2023 |
| HP            | 82F2                        | [091100b10f](https://linux-hardware.org/?probe=091100b10f) | Jan 08, 2023 |
| HP            | 8767 A                      | [8e15e2561a](https://linux-hardware.org/?probe=8e15e2561a) | Jan 08, 2023 |
| MSI           | B550-A PRO                  | [cfb62074a7](https://linux-hardware.org/?probe=cfb62074a7) | Jan 08, 2023 |
| ASUSTek       | A88XM-A                     | [b365fa99b3](https://linux-hardware.org/?probe=b365fa99b3) | Jan 08, 2023 |
| Gigabyte      | B450 AORUS M                | [e8e8ca3959](https://linux-hardware.org/?probe=e8e8ca3959) | Jan 08, 2023 |
| HP            | 8265                        | [83897e98cf](https://linux-hardware.org/?probe=83897e98cf) | Jan 08, 2023 |
| ASUSTek       | P8H77-V                     | [85e7e56c1d](https://linux-hardware.org/?probe=85e7e56c1d) | Jan 08, 2023 |
| Medion        | MS-7728                     | [27c0dc6078](https://linux-hardware.org/?probe=27c0dc6078) | Jan 08, 2023 |
| Lenovo        | SKYBAY NOK                  | [9bbe57d371](https://linux-hardware.org/?probe=9bbe57d371) | Jan 08, 2023 |
| Gigabyte      | A520M S2H                   | [a303af0bcf](https://linux-hardware.org/?probe=a303af0bcf) | Jan 08, 2023 |
| MSI           | 990XA-GD55                  | [b4525a8431](https://linux-hardware.org/?probe=b4525a8431) | Jan 08, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [b808a6be1a](https://linux-hardware.org/?probe=b808a6be1a) | Jan 08, 2023 |
| ASUSTek       | H110M-A                     | [8866a21a4b](https://linux-hardware.org/?probe=8866a21a4b) | Jan 08, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [1b0920cbac](https://linux-hardware.org/?probe=1b0920cbac) | Jan 08, 2023 |
| Foxconn       | ETON                        | [f30a00babb](https://linux-hardware.org/?probe=f30a00babb) | Jan 08, 2023 |
| HP            | 18E5                        | [6eaba9a7e7](https://linux-hardware.org/?probe=6eaba9a7e7) | Jan 08, 2023 |
| Fujitsu       | D3531-A1 S26361-D3531-A1    | [90aefc5fbd](https://linux-hardware.org/?probe=90aefc5fbd) | Jan 08, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [79551dad5b](https://linux-hardware.org/?probe=79551dad5b) | Jan 08, 2023 |
| HP            | 3029h                       | [8d20c516df](https://linux-hardware.org/?probe=8d20c516df) | Jan 08, 2023 |
| Gigabyte      | B550M DS3H                  | [10ae4cbb25](https://linux-hardware.org/?probe=10ae4cbb25) | Jan 08, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [a763320a37](https://linux-hardware.org/?probe=a763320a37) | Jan 08, 2023 |
| Foxconn       | H55MXV Series               | [8722a85ee1](https://linux-hardware.org/?probe=8722a85ee1) | Jan 08, 2023 |
| MSI           | MS-7390                     | [79306f7c2b](https://linux-hardware.org/?probe=79306f7c2b) | Jan 08, 2023 |
| Lenovo        | 317E SDK0J40700 WIN 3258... | [e3474e5d10](https://linux-hardware.org/?probe=e3474e5d10) | Jan 08, 2023 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [78ed7a1a24](https://linux-hardware.org/?probe=78ed7a1a24) | Jan 08, 2023 |
| MSI           | H270I GAMING PRO AC         | [42fc244fad](https://linux-hardware.org/?probe=42fc244fad) | Jan 08, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [d895c070e2](https://linux-hardware.org/?probe=d895c070e2) | Jan 08, 2023 |
| MSI           | Z97 MPOWER MAX AC           | [53a4b9ea17](https://linux-hardware.org/?probe=53a4b9ea17) | Jan 08, 2023 |
| MSI           | H110M GAMING                | [b5a1687141](https://linux-hardware.org/?probe=b5a1687141) | Jan 08, 2023 |
| HP            | 212A                        | [0ed4b05f68](https://linux-hardware.org/?probe=0ed4b05f68) | Jan 08, 2023 |
| ASUSTek       | Rampage V EDITION 10        | [7457474ac1](https://linux-hardware.org/?probe=7457474ac1) | Jan 08, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [7773146220](https://linux-hardware.org/?probe=7773146220) | Jan 08, 2023 |
| ASRock        | A320M-HDV R4.0              | [fba9812651](https://linux-hardware.org/?probe=fba9812651) | Jan 08, 2023 |
| MSI           | MAG B560 TORPEDO            | [570d25dbe5](https://linux-hardware.org/?probe=570d25dbe5) | Jan 08, 2023 |
| HP            | 844C                        | [bb6139031a](https://linux-hardware.org/?probe=bb6139031a) | Jan 08, 2023 |
| ASUSTek       | PRIME Z490-P                | [134b412a5f](https://linux-hardware.org/?probe=134b412a5f) | Jan 08, 2023 |
| Dell          | 0N820C A02                  | [6fa7639fd2](https://linux-hardware.org/?probe=6fa7639fd2) | Jan 07, 2023 |
| ASRock        | H470M-STX                   | [60b8fb9dc4](https://linux-hardware.org/?probe=60b8fb9dc4) | Jan 07, 2023 |
| Foxconn       | 2AB7                        | [af291c7251](https://linux-hardware.org/?probe=af291c7251) | Jan 07, 2023 |
| ASUSTek       | P8Z68-V LX                  | [f090331efa](https://linux-hardware.org/?probe=f090331efa) | Jan 07, 2023 |
| ASUSTek       | M4A785-M                    | [be50406f89](https://linux-hardware.org/?probe=be50406f89) | Jan 07, 2023 |
| ASRock        | B450M Pro4                  | [4ec4e3eb9b](https://linux-hardware.org/?probe=4ec4e3eb9b) | Jan 07, 2023 |
| ASUSTek       | PRIME A520M-K               | [804544aa64](https://linux-hardware.org/?probe=804544aa64) | Jan 07, 2023 |
| Acer          | Aspire XC-603G              | [6eec7b8895](https://linux-hardware.org/?probe=6eec7b8895) | Jan 07, 2023 |
| Intel         | DZ77GA-70K AAG39009-500     | [bc8eca0e06](https://linux-hardware.org/?probe=bc8eca0e06) | Jan 07, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [24b5e0ba8e](https://linux-hardware.org/?probe=24b5e0ba8e) | Jan 07, 2023 |
| ASUSTek       | P5KPL-CM                    | [625bf5665f](https://linux-hardware.org/?probe=625bf5665f) | Jan 07, 2023 |
| Dell          | 0HH807                      | [29ebe8d64c](https://linux-hardware.org/?probe=29ebe8d64c) | Jan 07, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [cedf3a8ef8](https://linux-hardware.org/?probe=cedf3a8ef8) | Jan 07, 2023 |
| Dell          | 07KY25 A00                  | [8c8fd6402e](https://linux-hardware.org/?probe=8c8fd6402e) | Jan 07, 2023 |
| ASRock        | AB350 Pro4                  | [f70583b34b](https://linux-hardware.org/?probe=f70583b34b) | Jan 07, 2023 |
| HP            | 8653 A                      | [604431e12a](https://linux-hardware.org/?probe=604431e12a) | Jan 07, 2023 |
| Shuttle       | NC01U V1.0                  | [248dbe6335](https://linux-hardware.org/?probe=248dbe6335) | Jan 07, 2023 |
| MSI           | PRO Z690-A DDR4             | [980ee9f42c](https://linux-hardware.org/?probe=980ee9f42c) | Jan 07, 2023 |
| HP            | ProLiant ML115 G5           | [a052401dd5](https://linux-hardware.org/?probe=a052401dd5) | Jan 07, 2023 |
| Gigabyte      | B450M S2H                   | [afd3f452a1](https://linux-hardware.org/?probe=afd3f452a1) | Jan 07, 2023 |
| ASRock        | AB350 Gaming-ITX/ac         | [2b9a607e74](https://linux-hardware.org/?probe=2b9a607e74) | Jan 07, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [8865a695e5](https://linux-hardware.org/?probe=8865a695e5) | Jan 07, 2023 |
| ASUSTek       | Z97-C                       | [2b61136e8d](https://linux-hardware.org/?probe=2b61136e8d) | Jan 07, 2023 |
| Pegatron      | Eureka3                     | [c3aacdc606](https://linux-hardware.org/?probe=c3aacdc606) | Jan 07, 2023 |
| MSI           | PRO B660M-B DDR4            | [cceab9ef33](https://linux-hardware.org/?probe=cceab9ef33) | Jan 07, 2023 |
| Gigabyte      | Z390 GAMING X-CF            | [237f175ef3](https://linux-hardware.org/?probe=237f175ef3) | Jan 07, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | [c1c8654cde](https://linux-hardware.org/?probe=c1c8654cde) | Jan 07, 2023 |
| ASUSTek       | PRIME B450M-A               | [829138fad9](https://linux-hardware.org/?probe=829138fad9) | Jan 07, 2023 |
| Dell          | 09M8Y8 A01                  | [f6d81f424d](https://linux-hardware.org/?probe=f6d81f424d) | Jan 07, 2023 |
| ASRock        | 970 Pro3 R2.0               | [beca9fd3ae](https://linux-hardware.org/?probe=beca9fd3ae) | Jan 07, 2023 |
| Dell          | 04MFRM A02                  | [7b29154637](https://linux-hardware.org/?probe=7b29154637) | Jan 07, 2023 |
| Foxconn       | 2ABF                        | [58e0667c6a](https://linux-hardware.org/?probe=58e0667c6a) | Jan 07, 2023 |
| Gigabyte      | GA-A55M-DS2                 | [850d5a392b](https://linux-hardware.org/?probe=850d5a392b) | Jan 07, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [9767004b24](https://linux-hardware.org/?probe=9767004b24) | Jan 07, 2023 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | [c4ae03416f](https://linux-hardware.org/?probe=c4ae03416f) | Jan 07, 2023 |
| ASUSTek       | P8Z77-V LX2                 | [bb893b2d93](https://linux-hardware.org/?probe=bb893b2d93) | Jan 07, 2023 |
| Gigabyte      | Z97X-UD5H-BK                | [531eaa88b5](https://linux-hardware.org/?probe=531eaa88b5) | Jan 07, 2023 |
| ASUSTek       | ROG STRIX B660-A GAMING ... | [87c4201895](https://linux-hardware.org/?probe=87c4201895) | Jan 07, 2023 |
| ASUSTek       | P8H77-M PRO                 | [03524fa074](https://linux-hardware.org/?probe=03524fa074) | Jan 07, 2023 |
| Dell          | 0VXN67 A01                  | [843a02520e](https://linux-hardware.org/?probe=843a02520e) | Jan 07, 2023 |
| HP            | 89B5 A                      | [4fcef21d82](https://linux-hardware.org/?probe=4fcef21d82) | Jan 07, 2023 |
| Gigabyte      | GA-MA770T-UD3               | [af95c3e61e](https://linux-hardware.org/?probe=af95c3e61e) | Jan 07, 2023 |
| HP            | 83EE                        | [cb43945233](https://linux-hardware.org/?probe=cb43945233) | Jan 07, 2023 |
| HP            | 8399                        | [eccd5189f5](https://linux-hardware.org/?probe=eccd5189f5) | Jan 07, 2023 |
| MSI           | Z590 PRO WIFI               | [98af54429b](https://linux-hardware.org/?probe=98af54429b) | Jan 07, 2023 |
| ASUSTek       | M5A99X EVO                  | [d4111f62a5](https://linux-hardware.org/?probe=d4111f62a5) | Jan 07, 2023 |
| HP            | 89D8 SMVB                   | [dac20769fc](https://linux-hardware.org/?probe=dac20769fc) | Jan 07, 2023 |
| Medion        | MS-7621                     | [da2d61d475](https://linux-hardware.org/?probe=da2d61d475) | Jan 07, 2023 |
| MSI           | H510M-A PRO                 | [38bc046bdd](https://linux-hardware.org/?probe=38bc046bdd) | Jan 07, 2023 |
| Acer          | Veriton N4640G              | [3392dd3c90](https://linux-hardware.org/?probe=3392dd3c90) | Jan 07, 2023 |
| ASUSTek       | P8H61-M LE R2.0             | [4f26146dd8](https://linux-hardware.org/?probe=4f26146dd8) | Jan 07, 2023 |
| Alienware     | 04VWF2 A02                  | [15f4ed4e31](https://linux-hardware.org/?probe=15f4ed4e31) | Jan 07, 2023 |
| ASUSTek       | PRIME B450M-A II            | [30bf1793c5](https://linux-hardware.org/?probe=30bf1793c5) | Jan 06, 2023 |
| Gigabyte      | X79-UP4                     | [01459563cf](https://linux-hardware.org/?probe=01459563cf) | Jan 06, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | [122079f900](https://linux-hardware.org/?probe=122079f900) | Jan 06, 2023 |
| Acer          | Veriton M2631G V:1.0        | [ddeffc27a7](https://linux-hardware.org/?probe=ddeffc27a7) | Jan 05, 2023 |
| ASRock        | M3A770DE                    | [952caf04f8](https://linux-hardware.org/?probe=952caf04f8) | Jan 05, 2023 |
| ASUSTek       | M2N68 Plus                  | [12309f8c91](https://linux-hardware.org/?probe=12309f8c91) | Jan 05, 2023 |
| Pegatron      | 2AC3                        | [4ce129e600](https://linux-hardware.org/?probe=4ce129e600) | Jan 05, 2023 |
| Dell          | 0M5DCD A00                  | [c64a1198cd](https://linux-hardware.org/?probe=c64a1198cd) | Jan 04, 2023 |
| MSI           | A320M PRO-VH PLUS           | [aa23d3d6f0](https://linux-hardware.org/?probe=aa23d3d6f0) | Jan 04, 2023 |
| MSI           | A88X-G45 GAMING             | [1caf5c85d9](https://linux-hardware.org/?probe=1caf5c85d9) | Jan 04, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [af7d9dfd51](https://linux-hardware.org/?probe=af7d9dfd51) | Jan 04, 2023 |
| Gigabyte      | Z690 AORUS ULTRA            | [55627fc077](https://linux-hardware.org/?probe=55627fc077) | Jan 03, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [5f0eeeb9e7](https://linux-hardware.org/?probe=5f0eeeb9e7) | Jan 03, 2023 |
| Gigabyte      | H61M-S1                     | [5ea753453b](https://linux-hardware.org/?probe=5ea753453b) | Jan 03, 2023 |
| Dell          | 0XCR8D A03                  | [faccba61cf](https://linux-hardware.org/?probe=faccba61cf) | Jan 03, 2023 |
| Fujitsu       | D3432-A1 S26361-D3432-A1    | [afe5105302](https://linux-hardware.org/?probe=afe5105302) | Jan 03, 2023 |
| ASUSTek       | Berkeley                    | [746d7be693](https://linux-hardware.org/?probe=746d7be693) | Jan 03, 2023 |
| Dell          | 0MM599                      | [95763443e3](https://linux-hardware.org/?probe=95763443e3) | Jan 03, 2023 |
| ASRock        | AB350M Pro4                 | [42b1f8124d](https://linux-hardware.org/?probe=42b1f8124d) | Jan 03, 2023 |
| HP            | 304Bh                       | [cfe1407faf](https://linux-hardware.org/?probe=cfe1407faf) | Jan 02, 2023 |
| ASRock        | B450M-HDV R4.0              | [df9ca70fa3](https://linux-hardware.org/?probe=df9ca70fa3) | Jan 02, 2023 |
| ASRock        | QC5000M                     | [ea11df2a20](https://linux-hardware.org/?probe=ea11df2a20) | Jan 02, 2023 |
| Gigabyte      | H61M-S2PV                   | [85ad98c994](https://linux-hardware.org/?probe=85ad98c994) | Jan 02, 2023 |
| AZW           | MINI S                      | [ad7c4329eb](https://linux-hardware.org/?probe=ad7c4329eb) | Jan 02, 2023 |
| Gigabyte      | B550M DS3H                  | [509cc939cc](https://linux-hardware.org/?probe=509cc939cc) | Jan 01, 2023 |
| OEM           | Intel H81                   | [1700a7a4c7](https://linux-hardware.org/?probe=1700a7a4c7) | Jan 01, 2023 |
| Gigabyte      | B365 HD3                    | [195240c264](https://linux-hardware.org/?probe=195240c264) | Jan 01, 2023 |
| ASUSTek       | Rampage V EXTREME           | [b1911d1ae5](https://linux-hardware.org/?probe=b1911d1ae5) | Jan 01, 2023 |
| ASUSTek       | PRIME A320M-K               | [afbe6b4362](https://linux-hardware.org/?probe=afbe6b4362) | Dec 31, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [7295ec02b5](https://linux-hardware.org/?probe=7295ec02b5) | Dec 31, 2022 |
| ASUSTek       | UN45                        | [bde2e2efb1](https://linux-hardware.org/?probe=bde2e2efb1) | Dec 31, 2022 |
| MSI           | MS-7502 Fab D               | [9126e1035f](https://linux-hardware.org/?probe=9126e1035f) | Dec 31, 2022 |
| Dell          | 0VNP2H A02                  | [5d3da04d45](https://linux-hardware.org/?probe=5d3da04d45) | Dec 31, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [b0dd8fc6b5](https://linux-hardware.org/?probe=b0dd8fc6b5) | Dec 31, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [de6ea0ae2e](https://linux-hardware.org/?probe=de6ea0ae2e) | Dec 30, 2022 |
| ASUSTek       | STRIKER II EXTREME          | [3258ffa0c1](https://linux-hardware.org/?probe=3258ffa0c1) | Dec 29, 2022 |
| Gigabyte      | H61M-D2H                    | [28aede6faf](https://linux-hardware.org/?probe=28aede6faf) | Dec 29, 2022 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [a72887241e](https://linux-hardware.org/?probe=a72887241e) | Dec 29, 2022 |
| MSI           | Z97 PC Mate                 | [1b7e70ab6e](https://linux-hardware.org/?probe=1b7e70ab6e) | Dec 29, 2022 |
| HP            | 0B4Ch D                     | [ed3b8e2e69](https://linux-hardware.org/?probe=ed3b8e2e69) | Dec 29, 2022 |
| ASUSTek       | P5K SE/EPU                  | [3f0c89985c](https://linux-hardware.org/?probe=3f0c89985c) | Dec 29, 2022 |
| Gigabyte      | MJPLNBB-00                  | [879a5b77ff](https://linux-hardware.org/?probe=879a5b77ff) | Dec 28, 2022 |
| Dell          | 0HN7XN A01                  | [43a0d87199](https://linux-hardware.org/?probe=43a0d87199) | Dec 28, 2022 |
| Pegatron      | APX85-GS                    | [82db9f15c6](https://linux-hardware.org/?probe=82db9f15c6) | Dec 27, 2022 |
| Acer          | Aspire TC-865 V:1.1         | [0c8add55fe](https://linux-hardware.org/?probe=0c8add55fe) | Dec 27, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [bc68280036](https://linux-hardware.org/?probe=bc68280036) | Dec 26, 2022 |
| Lenovo        | SHARKBAY NOK                | [46123218f3](https://linux-hardware.org/?probe=46123218f3) | Dec 26, 2022 |
| Gigabyte      | G41MT-S2PT                  | [14611d6c99](https://linux-hardware.org/?probe=14611d6c99) | Dec 26, 2022 |
| HP            | 2AF7                        | [96344d97ba](https://linux-hardware.org/?probe=96344d97ba) | Dec 26, 2022 |
| Gigabyte      | Z590 AORUS ULTRA            | [4ab759533b](https://linux-hardware.org/?probe=4ab759533b) | Dec 25, 2022 |
| Huanan        | B660-D4 V1.0                | [2a3d5dc01f](https://linux-hardware.org/?probe=2a3d5dc01f) | Dec 25, 2022 |
| Gigabyte      | B450M S2H                   | [500abd4186](https://linux-hardware.org/?probe=500abd4186) | Dec 25, 2022 |
| ASUSTek       | NARRA3                      | [cc0a64d0df](https://linux-hardware.org/?probe=cc0a64d0df) | Dec 25, 2022 |
| Pegatron      | IPPPV-D3G                   | [4d1a2299dc](https://linux-hardware.org/?probe=4d1a2299dc) | Dec 24, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [9e269ee2a4](https://linux-hardware.org/?probe=9e269ee2a4) | Dec 24, 2022 |
| ASRock        | FM2A68M-DG3+                | [11eb39826a](https://linux-hardware.org/?probe=11eb39826a) | Dec 24, 2022 |
| Dell          | 0M863N A00                  | [ce9fc7a224](https://linux-hardware.org/?probe=ce9fc7a224) | Dec 24, 2022 |
| Foxconn       | 2AA9                        | [07650be639](https://linux-hardware.org/?probe=07650be639) | Dec 24, 2022 |
| ASRock        | B75 Pro3-M                  | [e24692f75f](https://linux-hardware.org/?probe=e24692f75f) | Dec 24, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [27612d2f72](https://linux-hardware.org/?probe=27612d2f72) | Dec 24, 2022 |
| ASRock        | B550 Phantom Gaming 4/ac    | [2d3121d44e](https://linux-hardware.org/?probe=2d3121d44e) | Dec 24, 2022 |
| Dell          | 0J3C2F A00                  | [f993ebb9ed](https://linux-hardware.org/?probe=f993ebb9ed) | Dec 23, 2022 |
| MSI           | 880GM-E41                   | [2880803d71](https://linux-hardware.org/?probe=2880803d71) | Dec 23, 2022 |
| ASUSTek       | TUF B360-PRO GAMING         | [561b98afc3](https://linux-hardware.org/?probe=561b98afc3) | Dec 23, 2022 |
| Dell          | 0JJW8N A03                  | [5917cccca0](https://linux-hardware.org/?probe=5917cccca0) | Dec 23, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [87da3fdf4d](https://linux-hardware.org/?probe=87da3fdf4d) | Dec 23, 2022 |
| ASRock        | FM2A88M-HD+                 | [18b83ae613](https://linux-hardware.org/?probe=18b83ae613) | Dec 22, 2022 |
| ASUSTek       | P5K                         | [406d3a2d92](https://linux-hardware.org/?probe=406d3a2d92) | Dec 22, 2022 |
| MSI           | 2A9C                        | [031afb1b20](https://linux-hardware.org/?probe=031afb1b20) | Dec 22, 2022 |
| Acer          | Aspire M3920                | [803cd5d8f9](https://linux-hardware.org/?probe=803cd5d8f9) | Dec 22, 2022 |
| Gigabyte      | EP43-DS3                    | [d0f0cd82f9](https://linux-hardware.org/?probe=d0f0cd82f9) | Dec 22, 2022 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | [003ac98d7f](https://linux-hardware.org/?probe=003ac98d7f) | Dec 21, 2022 |
| PERTOSA       | GA-H110TN-M                 | [048d8cca49](https://linux-hardware.org/?probe=048d8cca49) | Dec 21, 2022 |
| HP            | 212A                        | [32c96df530](https://linux-hardware.org/?probe=32c96df530) | Dec 20, 2022 |
| Dell          | 0VHWTR A01                  | [a5070ec279](https://linux-hardware.org/?probe=a5070ec279) | Dec 20, 2022 |
| ASUSTek       | P5K                         | [e88b53b804](https://linux-hardware.org/?probe=e88b53b804) | Dec 20, 2022 |
| HP            | 8906 SMVB                   | [c7b2f48d96](https://linux-hardware.org/?probe=c7b2f48d96) | Dec 20, 2022 |
| Acer          | Aspire XC-830               | [ee5a538a22](https://linux-hardware.org/?probe=ee5a538a22) | Dec 20, 2022 |
| ECS           | G31T-M7                     | [327ac25b68](https://linux-hardware.org/?probe=327ac25b68) | Dec 20, 2022 |
| Gigabyte      | 945GCMX-S2                  | [3b9937e6df](https://linux-hardware.org/?probe=3b9937e6df) | Dec 20, 2022 |
| MSI           | H81M-E34                    | [3aa811568d](https://linux-hardware.org/?probe=3aa811568d) | Dec 19, 2022 |
| ASUSTek       | P5QL PRO                    | [5f3343c803](https://linux-hardware.org/?probe=5f3343c803) | Dec 19, 2022 |
| Gigabyte      | H61M-DS2                    | [b5c4e6cf61](https://linux-hardware.org/?probe=b5c4e6cf61) | Dec 19, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [743b2176f1](https://linux-hardware.org/?probe=743b2176f1) | Dec 19, 2022 |
| Dell          | 0M858N A00                  | [e46a95080d](https://linux-hardware.org/?probe=e46a95080d) | Dec 18, 2022 |
| MSI           | 790GX-G65                   | [7ad3c8f807](https://linux-hardware.org/?probe=7ad3c8f807) | Dec 18, 2022 |
| Gigabyte      | MQLP3AP-WG                  | [bdb3b0161e](https://linux-hardware.org/?probe=bdb3b0161e) | Dec 18, 2022 |
| Dell          | 0RY007                      | [3791fa08dd](https://linux-hardware.org/?probe=3791fa08dd) | Dec 18, 2022 |
| MSI           | A520M-A PRO                 | [164b37d0e5](https://linux-hardware.org/?probe=164b37d0e5) | Dec 18, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | [45eafa4ade](https://linux-hardware.org/?probe=45eafa4ade) | Dec 17, 2022 |
| Gigabyte      | X399 AORUS PRO-CF           | [71ebf721cc](https://linux-hardware.org/?probe=71ebf721cc) | Dec 17, 2022 |
| Biostar       | H81MHV3 5.0                 | [57191b83bb](https://linux-hardware.org/?probe=57191b83bb) | Dec 17, 2022 |
| HP            | 8055                        | [6c7fa83dc9](https://linux-hardware.org/?probe=6c7fa83dc9) | Dec 17, 2022 |
| MSI           | MS-B1711                    | [a5b142e258](https://linux-hardware.org/?probe=a5b142e258) | Dec 17, 2022 |
| ASUSTek       | PRIME H510M-K               | [ca088f2039](https://linux-hardware.org/?probe=ca088f2039) | Dec 16, 2022 |
| Biostar       | A10N-8800E                  | [bc96dc9caf](https://linux-hardware.org/?probe=bc96dc9caf) | Dec 16, 2022 |
| Dell          | 0RW203                      | [2f5bede488](https://linux-hardware.org/?probe=2f5bede488) | Dec 16, 2022 |
| ASUSTek       | B75M-A                      | [e350e12e7c](https://linux-hardware.org/?probe=e350e12e7c) | Dec 15, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [226bab8281](https://linux-hardware.org/?probe=226bab8281) | Dec 15, 2022 |
| Gigabyte      | F2A85X-UP4                  | [80358a5ba1](https://linux-hardware.org/?probe=80358a5ba1) | Dec 15, 2022 |
| Acer          | Veriton N2620G              | [a626bf668e](https://linux-hardware.org/?probe=a626bf668e) | Dec 15, 2022 |
| Pegatron      | IPM41-D3                    | [a41e0d92a7](https://linux-hardware.org/?probe=a41e0d92a7) | Dec 15, 2022 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | [ffe60f958c](https://linux-hardware.org/?probe=ffe60f958c) | Dec 15, 2022 |
| Dell          | 0FR6WH A01                  | [46d6c645fe](https://linux-hardware.org/?probe=46d6c645fe) | Dec 15, 2022 |
| Gigabyte      | F2A68HM-H                   | [f18234034f](https://linux-hardware.org/?probe=f18234034f) | Dec 15, 2022 |
| HP            | 2AFB                        | [4c57ea0ee7](https://linux-hardware.org/?probe=4c57ea0ee7) | Dec 15, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [587fac961e](https://linux-hardware.org/?probe=587fac961e) | Dec 15, 2022 |
| Dell          | 0VD92X A00                  | [9feb549665](https://linux-hardware.org/?probe=9feb549665) | Dec 15, 2022 |
| Gigabyte      | H410M H V3                  | [cf668e53f4](https://linux-hardware.org/?probe=cf668e53f4) | Dec 15, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [ad1e402db3](https://linux-hardware.org/?probe=ad1e402db3) | Dec 15, 2022 |
| MSI           | Z77MA-G45                   | [24a7d4b636](https://linux-hardware.org/?probe=24a7d4b636) | Dec 15, 2022 |
| ASUSTek       | EX-A320M-GAMING             | [6bd184b75a](https://linux-hardware.org/?probe=6bd184b75a) | Dec 15, 2022 |
| Dell          | 00V62H A01                  | [8b003bd5f2](https://linux-hardware.org/?probe=8b003bd5f2) | Dec 15, 2022 |
| Dell          | 05XGC8 A01                  | [f0e99676be](https://linux-hardware.org/?probe=f0e99676be) | Dec 14, 2022 |
| ASUSTek       | P8H61-M LX2/CSM             | [cc6e7dae77](https://linux-hardware.org/?probe=cc6e7dae77) | Dec 14, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [0a564c9f0f](https://linux-hardware.org/?probe=0a564c9f0f) | Dec 14, 2022 |
| Gigabyte      | B150-HD3-CF                 | [173dde2177](https://linux-hardware.org/?probe=173dde2177) | Dec 14, 2022 |
| Datto         | SSD                         | [a9bff0a51c](https://linux-hardware.org/?probe=a9bff0a51c) | Dec 14, 2022 |
| ASUSTek       | M5A97 R2.0                  | [c337db1381](https://linux-hardware.org/?probe=c337db1381) | Dec 14, 2022 |
| ASRock        | M3A770DE                    | [2e6b1f9c2d](https://linux-hardware.org/?probe=2e6b1f9c2d) | Dec 13, 2022 |
| HP            | 304Ah                       | [d8b600f39e](https://linux-hardware.org/?probe=d8b600f39e) | Dec 13, 2022 |
| ECS           | H61H2-M2                    | [8525777743](https://linux-hardware.org/?probe=8525777743) | Dec 13, 2022 |
| Dell          | 0T10XW A02                  | [1539e12262](https://linux-hardware.org/?probe=1539e12262) | Dec 13, 2022 |
| AZW           | U59                         | [fd5ccbfbd2](https://linux-hardware.org/?probe=fd5ccbfbd2) | Dec 13, 2022 |
| ASUSTek       | Z10PH-D16 Series            | [18911cf243](https://linux-hardware.org/?probe=18911cf243) | Dec 13, 2022 |
| ASUSTek       | NODUS M                     | [c415b9aeb6](https://linux-hardware.org/?probe=c415b9aeb6) | Dec 12, 2022 |
| Gigabyte      | H310M S2V                   | [6895902fe7](https://linux-hardware.org/?probe=6895902fe7) | Dec 12, 2022 |
| ASUSTek       | AM1M-A                      | [260a382d54](https://linux-hardware.org/?probe=260a382d54) | Dec 12, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [62f6fd5f8d](https://linux-hardware.org/?probe=62f6fd5f8d) | Dec 12, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [9537bff125](https://linux-hardware.org/?probe=9537bff125) | Dec 11, 2022 |
| HP            | 8265                        | [da426053be](https://linux-hardware.org/?probe=da426053be) | Dec 11, 2022 |
| Dell          | 0KG317                      | [cf7f697a0a](https://linux-hardware.org/?probe=cf7f697a0a) | Dec 11, 2022 |
| Dell          | 042P49 A02                  | [8b97211b80](https://linux-hardware.org/?probe=8b97211b80) | Dec 11, 2022 |
| ASUSTek       | PRIME X370-PRO              | [4bb3c91677](https://linux-hardware.org/?probe=4bb3c91677) | Dec 10, 2022 |
| ASUSTek       | P8Z77-V LX                  | [d53608f3e3](https://linux-hardware.org/?probe=d53608f3e3) | Dec 10, 2022 |
| ASUSTek       | P8Z77-V LX                  | [363ac45af6](https://linux-hardware.org/?probe=363ac45af6) | Dec 10, 2022 |
| Dell          | 01TKCC A01                  | [0dc9bb1cf4](https://linux-hardware.org/?probe=0dc9bb1cf4) | Dec 09, 2022 |
| Lenovo        | ThinkCentre M70e 0829RB4    | [5a5b271c35](https://linux-hardware.org/?probe=5a5b271c35) | Dec 09, 2022 |
| HP            | 18E7                        | [9759493e06](https://linux-hardware.org/?probe=9759493e06) | Dec 09, 2022 |
| Dell          | 0C27VV A03                  | [ef9e07a125](https://linux-hardware.org/?probe=ef9e07a125) | Dec 09, 2022 |
| ASRock        | 945GCM-S                    | [926787ea67](https://linux-hardware.org/?probe=926787ea67) | Dec 09, 2022 |
| Pegatron      | 2AB5                        | [6392174b0f](https://linux-hardware.org/?probe=6392174b0f) | Dec 09, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [aae285b0ea](https://linux-hardware.org/?probe=aae285b0ea) | Dec 09, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | [945412b0cc](https://linux-hardware.org/?probe=945412b0cc) | Dec 09, 2022 |
| Dell          | 0P301D A02                  | [8ab7a916f1](https://linux-hardware.org/?probe=8ab7a916f1) | Dec 08, 2022 |
| MSI           | 760GM-P23                   | [29337f7359](https://linux-hardware.org/?probe=29337f7359) | Dec 08, 2022 |
| ASRock        | B550 Taichi                 | [0203e79add](https://linux-hardware.org/?probe=0203e79add) | Dec 08, 2022 |
| ASUSTek       | H110-PLUS                   | [57e0d3651c](https://linux-hardware.org/?probe=57e0d3651c) | Dec 08, 2022 |
| Gigabyte      | Z370M D3H-CF                | [dabda33265](https://linux-hardware.org/?probe=dabda33265) | Dec 07, 2022 |
| ASUSTek       | P5Q-E                       | [fb93b5bdfa](https://linux-hardware.org/?probe=fb93b5bdfa) | Dec 06, 2022 |
| MAXSUN        | MS-TZZ A320M.2-VH           | [c3fc86b5d4](https://linux-hardware.org/?probe=c3fc86b5d4) | Dec 06, 2022 |
| HC Technol... | HCAR4000-MI                 | [596c3680f3](https://linux-hardware.org/?probe=596c3680f3) | Dec 06, 2022 |
| Gigabyte      | GA-MA770-ES3                | [70c1a43352](https://linux-hardware.org/?probe=70c1a43352) | Dec 06, 2022 |
| ASUSTek       | P8Z77-V LX                  | [e64c5d7bdc](https://linux-hardware.org/?probe=e64c5d7bdc) | Dec 06, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | [664d064b07](https://linux-hardware.org/?probe=664d064b07) | Dec 06, 2022 |
| ASUSTek       | P6T                         | [8268d853c9](https://linux-hardware.org/?probe=8268d853c9) | Dec 06, 2022 |
| Lenovo        | 0x36A017AA 31900058 STD     | [ccc212b757](https://linux-hardware.org/?probe=ccc212b757) | Dec 06, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [a4a47ea164](https://linux-hardware.org/?probe=a4a47ea164) | Dec 05, 2022 |
| Intel         | HURONRIVER                  | [d8a4f4a923](https://linux-hardware.org/?probe=d8a4f4a923) | Dec 05, 2022 |
| HP            | ProLiant ML350e Gen8        | [984fe41e3c](https://linux-hardware.org/?probe=984fe41e3c) | Dec 05, 2022 |
| ECS           | 945P/PL-A                   | [8db8eec28d](https://linux-hardware.org/?probe=8db8eec28d) | Dec 05, 2022 |
| ASUSTek       | A_F_K31AN                   | [440d9055ff](https://linux-hardware.org/?probe=440d9055ff) | Dec 05, 2022 |
| ASRock        | B450 Pro4                   | [f96de923f4](https://linux-hardware.org/?probe=f96de923f4) | Dec 05, 2022 |
| ASUSTek       | A55BM-K                     | [e78b25a518](https://linux-hardware.org/?probe=e78b25a518) | Dec 05, 2022 |
| Gigabyte      | GA-78LMT-S2                 | [fa3aeacc17](https://linux-hardware.org/?probe=fa3aeacc17) | Dec 05, 2022 |
| MSI           | Z490-A PRO                  | [34157244aa](https://linux-hardware.org/?probe=34157244aa) | Dec 05, 2022 |
| ASUSTek       | Z170 PRO GAMING             | [60d47a3b37](https://linux-hardware.org/?probe=60d47a3b37) | Dec 05, 2022 |
| Dell          | 0M863N A01                  | [ee8183087b](https://linux-hardware.org/?probe=ee8183087b) | Dec 04, 2022 |
| Pegatron      | 2ACF                        | [2d39768d80](https://linux-hardware.org/?probe=2d39768d80) | Dec 04, 2022 |
| Positivo      | POS-PIQ77CL POSITIVO        | [e98fcde376](https://linux-hardware.org/?probe=e98fcde376) | Dec 04, 2022 |
| Lenovo        | SHARKBAY NOK                | [ef7a013f9b](https://linux-hardware.org/?probe=ef7a013f9b) | Dec 04, 2022 |
| ACTION        | ACTINA GA-G31M-S2L          | [2a2934f919](https://linux-hardware.org/?probe=2a2934f919) | Dec 04, 2022 |
| Lenovo        | Win8 Pro DPK TPG            | [1dbda8e648](https://linux-hardware.org/?probe=1dbda8e648) | Dec 04, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [1f3b1d433c](https://linux-hardware.org/?probe=1f3b1d433c) | Dec 04, 2022 |
| ASUSTek       | PRIME B560M-A AC            | [576dda0a6e](https://linux-hardware.org/?probe=576dda0a6e) | Dec 04, 2022 |
| Acer          | Aspire X3950                | [96044c1932](https://linux-hardware.org/?probe=96044c1932) | Dec 03, 2022 |
| ASUSTek       | H97-PLUS                    | [c79b15a3cf](https://linux-hardware.org/?probe=c79b15a3cf) | Dec 03, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [7fe4c21bf6](https://linux-hardware.org/?probe=7fe4c21bf6) | Dec 03, 2022 |
| HP            | 3648h                       | [099f2cd973](https://linux-hardware.org/?probe=099f2cd973) | Dec 03, 2022 |
| Gigabyte      | 970A-DS3P                   | [a4a8d6dcec](https://linux-hardware.org/?probe=a4a8d6dcec) | Dec 03, 2022 |
| Dell          | 02YYK5 A01                  | [eb9887d9d4](https://linux-hardware.org/?probe=eb9887d9d4) | Dec 02, 2022 |
| HP            | 8648                        | [79673ee467](https://linux-hardware.org/?probe=79673ee467) | Dec 02, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [85eab170d2](https://linux-hardware.org/?probe=85eab170d2) | Dec 02, 2022 |
| ASUSTek       | P7P55D PRO                  | [b566591b3c](https://linux-hardware.org/?probe=b566591b3c) | Dec 02, 2022 |
| ASUSTek       | M5A97 PLUS                  | [63820e3937](https://linux-hardware.org/?probe=63820e3937) | Dec 01, 2022 |
| ASUSTek       | PRIME B250M-K               | [97a1793680](https://linux-hardware.org/?probe=97a1793680) | Dec 01, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [1ebd8b1b89](https://linux-hardware.org/?probe=1ebd8b1b89) | Dec 01, 2022 |
| ASUSTek       | P5K WS                      | [f3608476bf](https://linux-hardware.org/?probe=f3608476bf) | Dec 01, 2022 |
| Medion        | MS-7748                     | [0e92aa55ca](https://linux-hardware.org/?probe=0e92aa55ca) | Nov 30, 2022 |
| Dell          | 0N4YC8 A00                  | [2e53fa79ed](https://linux-hardware.org/?probe=2e53fa79ed) | Nov 30, 2022 |
| ASUSTek       | Z170-E                      | [5e68d23175](https://linux-hardware.org/?probe=5e68d23175) | Nov 30, 2022 |
| Medion        | MS-7800                     | [a5658a6933](https://linux-hardware.org/?probe=a5658a6933) | Nov 30, 2022 |
| ASRock        | N68-S3 UCC                  | [1d20e4ba6d](https://linux-hardware.org/?probe=1d20e4ba6d) | Nov 30, 2022 |
| MACHINIST     | X99-D8-MAX V1.0             | [c2430965a1](https://linux-hardware.org/?probe=c2430965a1) | Nov 30, 2022 |
| ASRock        | H470M-HDV/M.2               | [c01129a199](https://linux-hardware.org/?probe=c01129a199) | Nov 29, 2022 |
| MSI           | D2414 S26361-D2414-A10      | [ef1367a574](https://linux-hardware.org/?probe=ef1367a574) | Nov 29, 2022 |
| ECS           | 945P/PL-A                   | [ff47651dd8](https://linux-hardware.org/?probe=ff47651dd8) | Nov 29, 2022 |
| Biostar       | H81MHV3 5.0                 | [d89a05dd31](https://linux-hardware.org/?probe=d89a05dd31) | Nov 29, 2022 |
| Gigabyte      | B450 AORUS M                | [d20243efed](https://linux-hardware.org/?probe=d20243efed) | Nov 28, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [e479f87a66](https://linux-hardware.org/?probe=e479f87a66) | Nov 28, 2022 |
| ASRock        | B550M-ITX/ac                | [31f70fbb3e](https://linux-hardware.org/?probe=31f70fbb3e) | Nov 27, 2022 |
| ASUSTek       | PRIME X570-PRO              | [c218724cb4](https://linux-hardware.org/?probe=c218724cb4) | Nov 27, 2022 |
| MSI           | Z77MA-G45                   | [feb165c344](https://linux-hardware.org/?probe=feb165c344) | Nov 27, 2022 |
| ASRock        | A88M-G                      | [323199813d](https://linux-hardware.org/?probe=323199813d) | Nov 27, 2022 |
| MSI           | P55-CD53                    | [a602949484](https://linux-hardware.org/?probe=a602949484) | Nov 26, 2022 |
| ASUSTek       | PRIME H410M-R               | [b680eec959](https://linux-hardware.org/?probe=b680eec959) | Nov 26, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [02b1483a02](https://linux-hardware.org/?probe=02b1483a02) | Nov 26, 2022 |
| HP            | 3397                        | [c943f7435d](https://linux-hardware.org/?probe=c943f7435d) | Nov 26, 2022 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [9419d2017e](https://linux-hardware.org/?probe=9419d2017e) | Nov 26, 2022 |
| Gigabyte      | G31M-ES2L                   | [1eb32c408c](https://linux-hardware.org/?probe=1eb32c408c) | Nov 26, 2022 |
| HP            | 0AECh D                     | [857616948b](https://linux-hardware.org/?probe=857616948b) | Nov 26, 2022 |
| HP            | 1589                        | [077a89fb54](https://linux-hardware.org/?probe=077a89fb54) | Nov 26, 2022 |
| Dell          | 0VRWRC A00                  | [26bfa13122](https://linux-hardware.org/?probe=26bfa13122) | Nov 25, 2022 |
| ASUSTek       | P8B75-M LX PLUS             | [7948a35f59](https://linux-hardware.org/?probe=7948a35f59) | Nov 25, 2022 |
| Acer          | Veriton L6620G v1.0         | [33f168992e](https://linux-hardware.org/?probe=33f168992e) | Nov 25, 2022 |
| HP            | 2215                        | [0134898651](https://linux-hardware.org/?probe=0134898651) | Nov 25, 2022 |
| MSI           | B75A-G43                    | [7f635dae7f](https://linux-hardware.org/?probe=7f635dae7f) | Nov 24, 2022 |
| Wistron       | ProLiant ML110 G6           | [7d448ab5cc](https://linux-hardware.org/?probe=7d448ab5cc) | Nov 24, 2022 |
| ASUSTek       | M4A87TD/USB3                | [81a2eaf6e4](https://linux-hardware.org/?probe=81a2eaf6e4) | Nov 24, 2022 |
| ASRock        | X670E Taichi Carrara        | [7e844d7172](https://linux-hardware.org/?probe=7e844d7172) | Nov 24, 2022 |
| Foxconn       | 2A92                        | [e21715c047](https://linux-hardware.org/?probe=e21715c047) | Nov 24, 2022 |
| Supermicro    | PDSMi+                      | [3a70b82d42](https://linux-hardware.org/?probe=3a70b82d42) | Nov 24, 2022 |
| Intel         | B75                         | [a8932d4a21](https://linux-hardware.org/?probe=a8932d4a21) | Nov 24, 2022 |
| Foxconn       | 2ADA                        | [3be30a3d31](https://linux-hardware.org/?probe=3be30a3d31) | Nov 23, 2022 |
| Wistron       | ProLiant ML110 G5           | [67cc68fbfe](https://linux-hardware.org/?probe=67cc68fbfe) | Nov 23, 2022 |
| MSI           | B450M-A PRO MAX             | [e4904d14cc](https://linux-hardware.org/?probe=e4904d14cc) | Nov 23, 2022 |
| Dell          | 0M863N A01                  | [ca7e5eab8d](https://linux-hardware.org/?probe=ca7e5eab8d) | Nov 23, 2022 |
| Gigabyte      | 970A-DS3P                   | [681bcb945c](https://linux-hardware.org/?probe=681bcb945c) | Nov 23, 2022 |
| ASUSTek       | P5KPL-AM SE                 | [eca478ef1d](https://linux-hardware.org/?probe=eca478ef1d) | Nov 23, 2022 |
| Intel         | DG41TY AAE47335-302         | [ae2fb8d0b3](https://linux-hardware.org/?probe=ae2fb8d0b3) | Nov 22, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [324b5a49e4](https://linux-hardware.org/?probe=324b5a49e4) | Nov 22, 2022 |
| ASUSTek       | V-P5G43 R1.04G              | [b400ca5e29](https://linux-hardware.org/?probe=b400ca5e29) | Nov 21, 2022 |
| HP            | 3399                        | [bce6df1ffb](https://linux-hardware.org/?probe=bce6df1ffb) | Nov 21, 2022 |
| Gigabyte      | Z77-D3H                     | [aecddcf17e](https://linux-hardware.org/?probe=aecddcf17e) | Nov 21, 2022 |
| ASUSTek       | F1A55-M LE                  | [f2120128c1](https://linux-hardware.org/?probe=f2120128c1) | Nov 21, 2022 |
| Gigabyte      | H61M-DS2 x.x                | [cd65013120](https://linux-hardware.org/?probe=cd65013120) | Nov 21, 2022 |
| ASRock        | B450M Steel Legend          | [4792cdbba2](https://linux-hardware.org/?probe=4792cdbba2) | Nov 21, 2022 |
| Lenovo        | 32E9 SDK0T76465 WIN 3422... | [ec30826806](https://linux-hardware.org/?probe=ec30826806) | Nov 21, 2022 |
| Lenovo        | MAHOBAY                     | [d74e4882d8](https://linux-hardware.org/?probe=d74e4882d8) | Nov 21, 2022 |
| Pegatron      | NARRA5                      | [d8632e2872](https://linux-hardware.org/?probe=d8632e2872) | Nov 21, 2022 |
| ASRock        | P67 Extreme4                | [569fd8178d](https://linux-hardware.org/?probe=569fd8178d) | Nov 21, 2022 |
| Pegatron      | NARRA5                      | [42e5fe9c22](https://linux-hardware.org/?probe=42e5fe9c22) | Nov 21, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [049f06f11d](https://linux-hardware.org/?probe=049f06f11d) | Nov 21, 2022 |
| AZW           | SEi                         | [a8e813c483](https://linux-hardware.org/?probe=a8e813c483) | Nov 21, 2022 |
| HP            | 2AF3                        | [babcb0bf93](https://linux-hardware.org/?probe=babcb0bf93) | Nov 21, 2022 |
| Dell          | 00NNT0 A00                  | [c25787d8b9](https://linux-hardware.org/?probe=c25787d8b9) | Nov 20, 2022 |
| ASUSTek       | M2N-E                       | [150565ed00](https://linux-hardware.org/?probe=150565ed00) | Nov 20, 2022 |
| ASUSTek       | H81M-PLUS                   | [880e6565e8](https://linux-hardware.org/?probe=880e6565e8) | Nov 20, 2022 |
| ASUSTek       | Z97-C                       | [733140c078](https://linux-hardware.org/?probe=733140c078) | Nov 20, 2022 |
| MSI           | PRO Z690-A WIFI             | [5b31194732](https://linux-hardware.org/?probe=5b31194732) | Nov 20, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [61738f6d8a](https://linux-hardware.org/?probe=61738f6d8a) | Nov 19, 2022 |
| Shuttle       | FS61                        | [7a940c8fa3](https://linux-hardware.org/?probe=7a940c8fa3) | Nov 19, 2022 |
| Pegatron      | 2A94h                       | [be99475703](https://linux-hardware.org/?probe=be99475703) | Nov 19, 2022 |
| ECS           | G41T-M7                     | [f97036df33](https://linux-hardware.org/?probe=f97036df33) | Nov 18, 2022 |
| Intel         | X99                         | [c95c1d173b](https://linux-hardware.org/?probe=c95c1d173b) | Nov 18, 2022 |
| ASUSTek       | P8H61-M PLUS V2             | [ff279b1860](https://linux-hardware.org/?probe=ff279b1860) | Nov 18, 2022 |
| TPV-INVENT... | 2AC6 A01                    | [04b3ba4242](https://linux-hardware.org/?probe=04b3ba4242) | Nov 18, 2022 |
| Gigabyte      | 970A-DS3P                   | [fc7b21bd04](https://linux-hardware.org/?probe=fc7b21bd04) | Nov 18, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [a61b66e4ed](https://linux-hardware.org/?probe=a61b66e4ed) | Nov 18, 2022 |
| Gigabyte      | A520M H                     | [c2ad29d3e8](https://linux-hardware.org/?probe=c2ad29d3e8) | Nov 18, 2022 |
| Fujitsu Si... | D2364-A3 S26361-D2364-A3    | [62ce7f9a0b](https://linux-hardware.org/?probe=62ce7f9a0b) | Nov 18, 2022 |
| Huanan        | X99-8M-F V1.1               | [b1d1b0ad4c](https://linux-hardware.org/?probe=b1d1b0ad4c) | Nov 18, 2022 |
| ASUSTek       | P5KPL/1600                  | [24b13d1967](https://linux-hardware.org/?probe=24b13d1967) | Nov 16, 2022 |
| HP            | 843B                        | [373e5cc61d](https://linux-hardware.org/?probe=373e5cc61d) | Nov 16, 2022 |
| Intel         | H61                         | [faeac27433](https://linux-hardware.org/?probe=faeac27433) | Nov 16, 2022 |
| Medion        | MS-7728                     | [813d86814d](https://linux-hardware.org/?probe=813d86814d) | Nov 16, 2022 |
| Acer          | Veriton N4630G              | [f4566a57a9](https://linux-hardware.org/?probe=f4566a57a9) | Nov 16, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [90662fa2e9](https://linux-hardware.org/?probe=90662fa2e9) | Nov 16, 2022 |
| ALDO          | C2016-BSWI-D2               | [0e4c4c6806](https://linux-hardware.org/?probe=0e4c4c6806) | Nov 16, 2022 |
| AZW           | Gemini M                    | [683123c4f5](https://linux-hardware.org/?probe=683123c4f5) | Nov 16, 2022 |
| ASUSTek       | H81M-A                      | [ff63827781](https://linux-hardware.org/?probe=ff63827781) | Nov 15, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [e7f05e6eac](https://linux-hardware.org/?probe=e7f05e6eac) | Nov 15, 2022 |
| ASRock        | B450M Steel Legend          | [6cb0948dfd](https://linux-hardware.org/?probe=6cb0948dfd) | Nov 15, 2022 |
| MSI           | H61M-P31/W8                 | [a7d3a01ab2](https://linux-hardware.org/?probe=a7d3a01ab2) | Nov 15, 2022 |
| HP            | 22F8                        | [754ebee9c8](https://linux-hardware.org/?probe=754ebee9c8) | Nov 14, 2022 |
| Gigabyte      | H77-DS3H                    | [f28540c049](https://linux-hardware.org/?probe=f28540c049) | Nov 14, 2022 |
| ASUSTek       | P8Z77-V LX                  | [2d904e2be7](https://linux-hardware.org/?probe=2d904e2be7) | Nov 13, 2022 |
| MSI           | B450M PRO-M2 MAX            | [27d4e1c496](https://linux-hardware.org/?probe=27d4e1c496) | Nov 13, 2022 |
| HP            | 84FD                        | [6ee4b6828c](https://linux-hardware.org/?probe=6ee4b6828c) | Nov 13, 2022 |
| Deltron       | H81H3-M4                    | [49530f2e0b](https://linux-hardware.org/?probe=49530f2e0b) | Nov 13, 2022 |
| MSI           | H97 GUARD-PRO               | [3ea9d7a74a](https://linux-hardware.org/?probe=3ea9d7a74a) | Nov 13, 2022 |
| Gigabyte      | H87-HD3                     | [e5a8d4700d](https://linux-hardware.org/?probe=e5a8d4700d) | Nov 12, 2022 |
| ASRock        | B450M Pro4 R2.0             | [c5952a73e7](https://linux-hardware.org/?probe=c5952a73e7) | Nov 12, 2022 |
| ASUSTek       | H81M-K                      | [052f42f29a](https://linux-hardware.org/?probe=052f42f29a) | Nov 12, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [2677116eee](https://linux-hardware.org/?probe=2677116eee) | Nov 12, 2022 |
| ASUSTek       | P5K SE/EPU                  | [d5e58b3718](https://linux-hardware.org/?probe=d5e58b3718) | Nov 11, 2022 |
| ASUSTek       | PRIME B450M-K               | [ccd759a684](https://linux-hardware.org/?probe=ccd759a684) | Nov 11, 2022 |
| Gigabyte      | H61M-S1                     | [19dc931962](https://linux-hardware.org/?probe=19dc931962) | Nov 10, 2022 |
| ASRock        | B365M Pro4-F                | [aa006ea111](https://linux-hardware.org/?probe=aa006ea111) | Nov 10, 2022 |
| Dell          | 04YP6J A02                  | [6a3833051e](https://linux-hardware.org/?probe=6a3833051e) | Nov 10, 2022 |
| Gigabyte      | H61M-DS2 x.x                | [4488e0a71a](https://linux-hardware.org/?probe=4488e0a71a) | Nov 10, 2022 |
| Acer          | RS880M05                    | [cb216f090c](https://linux-hardware.org/?probe=cb216f090c) | Nov 09, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [fb87099a0d](https://linux-hardware.org/?probe=fb87099a0d) | Nov 09, 2022 |
| Gigabyte      | GA-MA78GM-S2H               | [ac916f47fc](https://linux-hardware.org/?probe=ac916f47fc) | Nov 08, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [08be836975](https://linux-hardware.org/?probe=08be836975) | Nov 08, 2022 |
| ASUSTek       | P5E-VM SE                   | [a41a51330d](https://linux-hardware.org/?probe=a41a51330d) | Nov 08, 2022 |
| Acer          | Aspire X1700                | [764516b8f0](https://linux-hardware.org/?probe=764516b8f0) | Nov 08, 2022 |
| Dell          | 0VD92X A00                  | [a22087073b](https://linux-hardware.org/?probe=a22087073b) | Nov 08, 2022 |
| Gigabyte      | EP45-UD3L                   | [2b3eb32895](https://linux-hardware.org/?probe=2b3eb32895) | Nov 07, 2022 |
| Gigabyte      | G41MT-S2                    | [4c91fc2a59](https://linux-hardware.org/?probe=4c91fc2a59) | Nov 07, 2022 |
| HP            | 0B4Ch D                     | [6921f657bf](https://linux-hardware.org/?probe=6921f657bf) | Nov 07, 2022 |
| ASRock        | Z170 Extreme4               | [f0b56da15d](https://linux-hardware.org/?probe=f0b56da15d) | Nov 07, 2022 |
| MSI           | B450M MORTAR TITANIUM       | [b6768dd5b7](https://linux-hardware.org/?probe=b6768dd5b7) | Nov 07, 2022 |
| Gigabyte      | Z68MA-D2H-B3                | [09c5b6e39e](https://linux-hardware.org/?probe=09c5b6e39e) | Nov 06, 2022 |
| Gigabyte      | H81M-DS2                    | [5deb773641](https://linux-hardware.org/?probe=5deb773641) | Nov 06, 2022 |
| Pegatron      | 2AE3                        | [19ae75aacc](https://linux-hardware.org/?probe=19ae75aacc) | Nov 06, 2022 |
| ASRock        | 4CoreDual-SATA2             | [e1a81edea7](https://linux-hardware.org/?probe=e1a81edea7) | Nov 05, 2022 |
| MSI           | GF615M-P33                  | [8aec7634ab](https://linux-hardware.org/?probe=8aec7634ab) | Nov 05, 2022 |
| Gigabyte      | GA-MA770-DS3                | [f435ef302a](https://linux-hardware.org/?probe=f435ef302a) | Nov 05, 2022 |
| HP            | 2820h                       | [6378a2e9c3](https://linux-hardware.org/?probe=6378a2e9c3) | Nov 05, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [7db5fcb7b0](https://linux-hardware.org/?probe=7db5fcb7b0) | Nov 05, 2022 |
| Dell          | 09D2HH A00                  | [7a4477cf7b](https://linux-hardware.org/?probe=7a4477cf7b) | Nov 05, 2022 |
| VS Company    | MCP61M                      | [ef6adc510d](https://linux-hardware.org/?probe=ef6adc510d) | Nov 05, 2022 |
| Gigabyte      | A320M-S2H-CF                | [3f2ef35b32](https://linux-hardware.org/?probe=3f2ef35b32) | Nov 04, 2022 |
| Foxconn       | 2ABF                        | [75884710cd](https://linux-hardware.org/?probe=75884710cd) | Nov 04, 2022 |
| MSI           | Z97-G43                     | [85701968ed](https://linux-hardware.org/?probe=85701968ed) | Nov 04, 2022 |
| ASUSTek       | H170I-PLUS D3               | [74df37995c](https://linux-hardware.org/?probe=74df37995c) | Nov 04, 2022 |
| Acer          | Veriton M480                | [9aa34be941](https://linux-hardware.org/?probe=9aa34be941) | Nov 03, 2022 |
| ASUSTek       | PRIME B365M-K               | [e2e281d38d](https://linux-hardware.org/?probe=e2e281d38d) | Nov 03, 2022 |
| Fujitsu       | D3219-A1 S26361-D3219-A1    | [bdc77dbc53](https://linux-hardware.org/?probe=bdc77dbc53) | Nov 03, 2022 |
| Lenovo        | 3716                        | [5a04bbf315](https://linux-hardware.org/?probe=5a04bbf315) | Nov 03, 2022 |
| Gigabyte      | 970A-DS3P                   | [a9f10f8922](https://linux-hardware.org/?probe=a9f10f8922) | Nov 02, 2022 |
| ASUSTek       | H61M-K                      | [3773260366](https://linux-hardware.org/?probe=3773260366) | Nov 02, 2022 |
| Gigabyte      | H97-HD3                     | [22214c7851](https://linux-hardware.org/?probe=22214c7851) | Nov 02, 2022 |
| ASRock        | N68-S3 FX                   | [22f68458d4](https://linux-hardware.org/?probe=22f68458d4) | Nov 02, 2022 |
| Acer          | Aspire X1430                | [f48a8d45d8](https://linux-hardware.org/?probe=f48a8d45d8) | Nov 01, 2022 |
| VS Company    | G31T-M                      | [75eb6866e0](https://linux-hardware.org/?probe=75eb6866e0) | Nov 01, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [8b208b8383](https://linux-hardware.org/?probe=8b208b8383) | Oct 31, 2022 |
| ASUSTek       | M4A78 PLUS                  | [bac044cd22](https://linux-hardware.org/?probe=bac044cd22) | Oct 31, 2022 |
| ASUSTek       | PRIME B450M-A II            | [c23efa8caa](https://linux-hardware.org/?probe=c23efa8caa) | Oct 31, 2022 |
| Dell          | 0GXM1W A00                  | [598d815c17](https://linux-hardware.org/?probe=598d815c17) | Oct 31, 2022 |
| Pegatron      | IPPCR-SS                    | [9427da0212](https://linux-hardware.org/?probe=9427da0212) | Oct 31, 2022 |
| Gigabyte      | H410M S2H V3                | [202065a62d](https://linux-hardware.org/?probe=202065a62d) | Oct 30, 2022 |
| HP            | 18E7                        | [6393aa1211](https://linux-hardware.org/?probe=6393aa1211) | Oct 30, 2022 |
| Gigabyte      | 970A-UD3P                   | [5f7d9d2a04](https://linux-hardware.org/?probe=5f7d9d2a04) | Oct 30, 2022 |
| Apple         | Mac-F221BEC8                | [12b6232cdd](https://linux-hardware.org/?probe=12b6232cdd) | Oct 30, 2022 |
| Dell          | 02YYK5 A01                  | [b7760774ca](https://linux-hardware.org/?probe=b7760774ca) | Oct 30, 2022 |
| Gigabyte      | Z690 AORUS MASTER           | [2a7d6b757b](https://linux-hardware.org/?probe=2a7d6b757b) | Oct 29, 2022 |
| ASUSTek       | ROG Maximus XII HERO        | [048348c6ba](https://linux-hardware.org/?probe=048348c6ba) | Oct 29, 2022 |
| MSI           | P45 Platinum                | [5507d45c35](https://linux-hardware.org/?probe=5507d45c35) | Oct 29, 2022 |
| MSI           | X570-A PRO                  | [1d3ff229c6](https://linux-hardware.org/?probe=1d3ff229c6) | Oct 29, 2022 |
| ASUSTek       | M5A78L-M LX PLUS            | [345683b134](https://linux-hardware.org/?probe=345683b134) | Oct 29, 2022 |
| ASRock        | H81M-ITX                    | [56f93814ea](https://linux-hardware.org/?probe=56f93814ea) | Oct 28, 2022 |
| ASUSTek       | P5K                         | [6d87562df6](https://linux-hardware.org/?probe=6d87562df6) | Oct 28, 2022 |
| ASUSTek       | M5A87                       | [88e6b582c9](https://linux-hardware.org/?probe=88e6b582c9) | Oct 28, 2022 |
| Dell          | 0WMJ54 A01                  | [41e9e7aba7](https://linux-hardware.org/?probe=41e9e7aba7) | Oct 28, 2022 |
| Unknown       | Unknown                     | [8d93ee0286](https://linux-hardware.org/?probe=8d93ee0286) | Oct 28, 2022 |
| Intel         | DG965OT AAD63733-203        | [28ad26edff](https://linux-hardware.org/?probe=28ad26edff) | Oct 28, 2022 |
| MSI           | MPG Z390I GAMING EDGE AC    | [1627ad94ef](https://linux-hardware.org/?probe=1627ad94ef) | Oct 27, 2022 |
| ASUSTek       | P8B75-V                     | [ca5c26654a](https://linux-hardware.org/?probe=ca5c26654a) | Oct 27, 2022 |
| ASRock        | B550M-HDV                   | [4d5068a3be](https://linux-hardware.org/?probe=4d5068a3be) | Oct 27, 2022 |
| ASUSTek       | P8H61-M LE R2.0             | [6b01f2f498](https://linux-hardware.org/?probe=6b01f2f498) | Oct 27, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [22dedf6886](https://linux-hardware.org/?probe=22dedf6886) | Oct 27, 2022 |
| Acer          | Veriton M275                | [c4604d6f2a](https://linux-hardware.org/?probe=c4604d6f2a) | Oct 26, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [d8343e2db5](https://linux-hardware.org/?probe=d8343e2db5) | Oct 26, 2022 |
| ASUSTek       | P8H67-M PRO                 | [b50585b578](https://linux-hardware.org/?probe=b50585b578) | Oct 26, 2022 |
| Gigabyte      | B365M DS3H                  | [2dd0f7f115](https://linux-hardware.org/?probe=2dd0f7f115) | Oct 26, 2022 |
| Dell          | 0WR7PY A03                  | [fa0daeab26](https://linux-hardware.org/?probe=fa0daeab26) | Oct 26, 2022 |
| Acer          | Veriton NBU                 | [7be04cd3ed](https://linux-hardware.org/?probe=7be04cd3ed) | Oct 25, 2022 |
| ASUSTek       | M2N-MX SE Plus              | [eca0e58bd8](https://linux-hardware.org/?probe=eca0e58bd8) | Oct 25, 2022 |
| HP            | 21B4 A01                    | [ec46b18fd5](https://linux-hardware.org/?probe=ec46b18fd5) | Oct 25, 2022 |
| Gigabyte      | G41MT-S2PT                  | [2fb43f4be2](https://linux-hardware.org/?probe=2fb43f4be2) | Oct 25, 2022 |
| ASUSTek       | M3N78-VM                    | [1c68e176b6](https://linux-hardware.org/?probe=1c68e176b6) | Oct 25, 2022 |
| ASRock        | G41C-GS                     | [218d55e0ca](https://linux-hardware.org/?probe=218d55e0ca) | Oct 25, 2022 |
| ASUSTek       | P5Q3 DELUXE                 | [a25c84e8f1](https://linux-hardware.org/?probe=a25c84e8f1) | Oct 25, 2022 |
| ASRock        | B660M Pro RS                | [e3b389cb66](https://linux-hardware.org/?probe=e3b389cb66) | Oct 25, 2022 |
| Dell          | 0GX297                      | [a047bbd7a0](https://linux-hardware.org/?probe=a047bbd7a0) | Oct 24, 2022 |
| ASRock        | N68-VS3 UCC                 | [82afa0e5bc](https://linux-hardware.org/?probe=82afa0e5bc) | Oct 24, 2022 |
| Gigabyte      | H310M S2H x.x               | [cce2975614](https://linux-hardware.org/?probe=cce2975614) | Oct 24, 2022 |
| ASUSTek       | P5QL-E                      | [41810c587a](https://linux-hardware.org/?probe=41810c587a) | Oct 24, 2022 |
| Gigabyte      | G41M-ES2L                   | [a995e58f10](https://linux-hardware.org/?probe=a995e58f10) | Oct 24, 2022 |
| Dell          | 0200DY A02                  | [69327d2615](https://linux-hardware.org/?probe=69327d2615) | Oct 24, 2022 |
| HP            | 8767 A                      | [7ecf583dab](https://linux-hardware.org/?probe=7ecf583dab) | Oct 24, 2022 |
| Gigabyte      | Z97-D3H-CF                  | [5ff7cf2e42](https://linux-hardware.org/?probe=5ff7cf2e42) | Oct 23, 2022 |
| ASUSTek       | PB62                        | [ddec39293d](https://linux-hardware.org/?probe=ddec39293d) | Oct 23, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [e59cef718b](https://linux-hardware.org/?probe=e59cef718b) | Oct 23, 2022 |
| Acer          | WMCP78M                     | [f4e3945dea](https://linux-hardware.org/?probe=f4e3945dea) | Oct 23, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | [5b61c1c241](https://linux-hardware.org/?probe=5b61c1c241) | Oct 23, 2022 |
| ASUSTek       | F2A85-V PRO                 | [ff4b30eab7](https://linux-hardware.org/?probe=ff4b30eab7) | Oct 23, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [3d217d0a43](https://linux-hardware.org/?probe=3d217d0a43) | Oct 23, 2022 |
| ASRock        | B450M Pro4                  | [12b83ecfd4](https://linux-hardware.org/?probe=12b83ecfd4) | Oct 22, 2022 |
| Dell          | 0HX555                      | [86339c4a3f](https://linux-hardware.org/?probe=86339c4a3f) | Oct 22, 2022 |
| Philco        | DTC-A55                     | [5c7d64ff3f](https://linux-hardware.org/?probe=5c7d64ff3f) | Oct 22, 2022 |
| Acer          | WG43M                       | [e520a7dfca](https://linux-hardware.org/?probe=e520a7dfca) | Oct 22, 2022 |
| ASUSTek       | H110M-A                     | [7bd1ee25b3](https://linux-hardware.org/?probe=7bd1ee25b3) | Oct 21, 2022 |
| Gigabyte      | GA-790FXTA-UD5              | [78218a5b63](https://linux-hardware.org/?probe=78218a5b63) | Oct 21, 2022 |
| MSI           | H310M PRO-VD                | [9ce99513bc](https://linux-hardware.org/?probe=9ce99513bc) | Oct 21, 2022 |
| MSI           | H61M-P20                    | [a50648c486](https://linux-hardware.org/?probe=a50648c486) | Oct 21, 2022 |
| Gigabyte      | G41MT-S2PT                  | [1ad0ed065f](https://linux-hardware.org/?probe=1ad0ed065f) | Oct 21, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [6c32002395](https://linux-hardware.org/?probe=6c32002395) | Oct 20, 2022 |
| ASUSTek       | P7P55-M                     | [3ff254b938](https://linux-hardware.org/?probe=3ff254b938) | Oct 20, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [7a1b569725](https://linux-hardware.org/?probe=7a1b569725) | Oct 20, 2022 |
| ASRock        | H81 Pro BTC R2.0            | [2ead6c088f](https://linux-hardware.org/?probe=2ead6c088f) | Oct 20, 2022 |
| HP            | 1825                        | [e0a35f1d0f](https://linux-hardware.org/?probe=e0a35f1d0f) | Oct 19, 2022 |
| Dell          | 0M5DCD A00                  | [e14791bb51](https://linux-hardware.org/?probe=e14791bb51) | Oct 19, 2022 |
| ASRock        | H81M-HG4 R4.0               | [de13cd2a09](https://linux-hardware.org/?probe=de13cd2a09) | Oct 19, 2022 |
| HP            | 805D                        | [a70ef30fce](https://linux-hardware.org/?probe=a70ef30fce) | Oct 19, 2022 |
| Intel         | DH61BF AAG81311-101         | [770d8bf876](https://linux-hardware.org/?probe=770d8bf876) | Oct 19, 2022 |
| ASUSTek       | A88XM-A                     | [9622704d8f](https://linux-hardware.org/?probe=9622704d8f) | Oct 18, 2022 |
| Gigabyte      | 970A-DS3P                   | [e4c3a71575](https://linux-hardware.org/?probe=e4c3a71575) | Oct 18, 2022 |
| ASUSTek       | P5KPL-E                     | [2f1e1cbbf4](https://linux-hardware.org/?probe=2f1e1cbbf4) | Oct 18, 2022 |
| ASUSTek       | TUF Gaming B460-PLUS        | [5823a0c5d0](https://linux-hardware.org/?probe=5823a0c5d0) | Oct 18, 2022 |
| Gigabyte      | 970A-DS3P                   | [c5beaeaf05](https://linux-hardware.org/?probe=c5beaeaf05) | Oct 17, 2022 |
| Dell          | 02YYK5 A01                  | [5872b35f8c](https://linux-hardware.org/?probe=5872b35f8c) | Oct 17, 2022 |
| ASUSTek       | PRIME B560M-K               | [8d9bc873e4](https://linux-hardware.org/?probe=8d9bc873e4) | Oct 17, 2022 |
| ASRock        | Z87 Pro3                    | [364a0afaff](https://linux-hardware.org/?probe=364a0afaff) | Oct 16, 2022 |
| Dell          | 0XFWHV A00                  | [4a5716d169](https://linux-hardware.org/?probe=4a5716d169) | Oct 16, 2022 |
| Gigabyte      | F2A88XM-HD3P                | [b5c41a9fef](https://linux-hardware.org/?probe=b5c41a9fef) | Oct 16, 2022 |
| HP            | 1850                        | [eda9bb7861](https://linux-hardware.org/?probe=eda9bb7861) | Oct 15, 2022 |
| Gigabyte      | H61M-D2H                    | [3c51ad7454](https://linux-hardware.org/?probe=3c51ad7454) | Oct 15, 2022 |
| Intel         | DP45SG AAE27733-403         | [f391a78f4d](https://linux-hardware.org/?probe=f391a78f4d) | Oct 15, 2022 |
| Dell          | 0J3C2F A01                  | [b30840548a](https://linux-hardware.org/?probe=b30840548a) | Oct 15, 2022 |
| HP            | 3648h                       | [ce5e78d7e3](https://linux-hardware.org/?probe=ce5e78d7e3) | Oct 14, 2022 |
| ASUSTek       | PRIME H510M-A               | [720d282dfe](https://linux-hardware.org/?probe=720d282dfe) | Oct 14, 2022 |
| Gigabyte      | F2A55M-DS2                  | [1feb9942e8](https://linux-hardware.org/?probe=1feb9942e8) | Oct 14, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [60e6bd1280](https://linux-hardware.org/?probe=60e6bd1280) | Oct 14, 2022 |
| ASUSTek       | H81M-K                      | [57e988db9d](https://linux-hardware.org/?probe=57e988db9d) | Oct 14, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/OpenMandriva/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| OpenMandriva 4.2    | 2244     | 42.29%  |
| OpenMandriva 4.3    | 1924     | 36.26%  |
| OpenMandriva 23.01  | 527      | 9.93%   |
| OpenMandriva 4.50   | 398      | 7.5%    |
| OpenMandriva 4.90   | 153      | 2.88%   |
| OpenMandriva 22.12  | 40       | 0.75%   |
| OpenMandriva 4.1    | 10       | 0.19%   |
| OpenMandriva 22.11  | 4        | 0.08%   |
| OpenMandriva 2014.0 | 3        | 0.06%   |
| OpenMandriva 4.0    | 2        | 0.04%   |
| OpenMandriva 4.0.1  | 1        | 0.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| OpenMandriva | 5290     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Desktops | Percent |
|--------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002       | 2174     | 40.77%  |
| 5.16.7-desktop-1omv4003        | 1859     | 34.86%  |
| 6.1.1-desktop-1omv2290         | 510      | 9.56%   |
| 5.12.4-desktop-1omv4050        | 204      | 3.83%   |
| 5.18.12-desktop-3omv4090       | 142      | 2.66%   |
| 5.11.12-desktop-1omv4002       | 78       | 1.46%   |
| 5.19.5-desktop-1omv4090        | 75       | 1.41%   |
| 5.16.13-desktop-1omv4003       | 58       | 1.09%   |
| 5.19.12-desktop-2omv4090       | 52       | 0.98%   |
| 6.0.10-desktop-2omv22090       | 39       | 0.73%   |
| 5.14.7-desktop-1omv4050        | 21       | 0.39%   |
| 5.12.7-desktop-1omv4003        | 10       | 0.19%   |
| 5.5.12-desktop-1omv4001        | 9        | 0.17%   |
| 5.19.11-desktop-2omv4090       | 9        | 0.17%   |
| 6.1.4-desktop-1omv2301         | 8        | 0.15%   |
| 5.14.14-desktop-1omv4050       | 8        | 0.15%   |
| 6.1.2-desktop-1omv2301         | 7        | 0.13%   |
| 5.11.0-desktop-clang-1omv4002  | 5        | 0.09%   |
| 5.10.13-desktop-1omv4002       | 5        | 0.09%   |
| 5.16.3-desktop-2omv4050        | 4        | 0.08%   |
| 5.19.0-desktop-1omv4090        | 3        | 0.06%   |
| 6.1.4-desktop-gcc-1omv2301     | 2        | 0.04%   |
| 5.18.9-desktop-gcc-1omv4090    | 2        | 0.04%   |
| 5.17.7-desktop-1omv4090        | 2        | 0.04%   |
| 5.17.1-desktop-2omv4050        | 2        | 0.04%   |
| 5.16.5-desktop-2omv4003        | 2        | 0.04%   |
| 5.13.2-desktop-clang-1omv4050  | 2        | 0.04%   |
| 5.12.7-desktop-clang-1omv4003  | 2        | 0.04%   |
| 5.11.11-desktop-clang-1omv4050 | 2        | 0.04%   |
| 4.1.12-nrj-server-1omv         | 2        | 0.04%   |
| 6.0.9-desktop-gcc-1omv22090    | 1        | 0.02%   |
| 6.0.9-desktop-2.0omv4.3mjn     | 1        | 0.02%   |
| 6.0.9-desktop-1omv22090        | 1        | 0.02%   |
| 6.0.2-desktop-1omv4050         | 1        | 0.02%   |
| 6.0.0-desktop-gcc-1omv4050     | 1        | 0.02%   |
| 6.0.0-desktop-1omv4050         | 1        | 0.02%   |
| 6.0.0-desktop-0.rc3.1omv4090   | 1        | 0.02%   |
| 5.8.13-desktop-clang-1omv4002  | 1        | 0.02%   |
| 5.5.0-desktop-1omv4001         | 1        | 0.02%   |
| 5.3.7-desktop-1omv4000         | 1        | 0.02%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.14 | 2174     | 40.77%  |
| 5.16.7  | 1860     | 34.88%  |
| 6.1.1   | 510      | 9.56%   |
| 5.12.4  | 204      | 3.83%   |
| 5.18.12 | 142      | 2.66%   |
| 5.11.12 | 78       | 1.46%   |
| 5.19.5  | 75       | 1.41%   |
| 5.16.13 | 58       | 1.09%   |
| 5.19.12 | 53       | 0.99%   |
| 6.0.10  | 39       | 0.73%   |
| 5.14.7  | 21       | 0.39%   |
| 5.12.7  | 12       | 0.23%   |
| 6.1.4   | 10       | 0.19%   |
| 5.19.11 | 10       | 0.19%   |
| 5.5.12  | 9        | 0.17%   |
| 5.14.14 | 8        | 0.15%   |
| 6.1.2   | 7        | 0.13%   |
| 5.11.0  | 5        | 0.09%   |
| 5.10.13 | 5        | 0.09%   |
| 5.16.3  | 4        | 0.08%   |
| 6.0.9   | 3        | 0.06%   |
| 6.0.0   | 3        | 0.06%   |
| 5.19.0  | 3        | 0.06%   |
| 5.16.5  | 3        | 0.06%   |
| 5.13.2  | 3        | 0.06%   |
| 5.18.9  | 2        | 0.04%   |
| 5.17.7  | 2        | 0.04%   |
| 5.17.1  | 2        | 0.04%   |
| 5.11.11 | 2        | 0.04%   |
| 4.1.12  | 2        | 0.04%   |
| 6.0.2   | 1        | 0.02%   |
| 5.8.13  | 1        | 0.02%   |
| 5.5.0   | 1        | 0.02%   |
| 5.3.7   | 1        | 0.02%   |
| 5.19.8  | 1        | 0.02%   |
| 5.19.1  | 1        | 0.02%   |
| 5.18.13 | 1        | 0.02%   |
| 5.18.1  | 1        | 0.02%   |
| 5.16.8  | 1        | 0.02%   |
| 5.16.0  | 1        | 0.02%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 2183     | 40.96%  |
| 5.16    | 1925     | 36.12%  |
| 6.1     | 527      | 9.89%   |
| 5.12    | 220      | 4.13%   |
| 5.18    | 146      | 2.74%   |
| 5.19    | 143      | 2.68%   |
| 5.11    | 85       | 1.6%    |
| 6.0     | 46       | 0.86%   |
| 5.14    | 30       | 0.56%   |
| 5.5     | 10       | 0.19%   |
| 5.17    | 4        | 0.08%   |
| 5.13    | 3        | 0.06%   |
| 4.1     | 3        | 0.06%   |
| 5.1     | 2        | 0.04%   |
| 5.8     | 1        | 0.02%   |
| 5.3     | 1        | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 5290     | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| KDE5     | 5166     | 97.62%  |
| GNOME    | 100      | 1.89%   |
| LXQt     | 11       | 0.21%   |
| Unknown  | 10       | 0.19%   |
| XFCE     | 2        | 0.04%   |
| KDE4     | 1        | 0.02%   |
| KDE      | 1        | 0.02%   |
| Cinnamon | 1        | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 5148     | 97.3%   |
| Wayland | 141      | 2.66%   |
| Unknown | 2        | 0.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 5184     | 98%     |
| GDM     | 100      | 1.89%   |
| Unknown | 3        | 0.06%   |
| LightDM | 2        | 0.04%   |
| KDM     | 1        | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 2914     | 54.92%  |
| de_DE   | 408      | 7.69%   |
| ru_RU   | 373      | 7.03%   |
| fr_FR   | 286      | 5.39%   |
| pt_BR   | 224      | 4.22%   |
| pl_PL   | 163      | 3.07%   |
| it_IT   | 129      | 2.43%   |
| es_ES   | 119      | 2.24%   |
| en_GB   | 80       | 1.51%   |
| cs_CZ   | 57       | 1.07%   |
| es_AR   | 52       | 0.98%   |
| hu_HU   | 49       | 0.92%   |
| de_AT   | 45       | 0.85%   |
| es_MX   | 41       | 0.77%   |
| en_AU   | 28       | 0.53%   |
| fr_CA   | 26       | 0.49%   |
| nl_NL   | 25       | 0.47%   |
| en_CA   | 21       | 0.4%    |
| en_IN   | 19       | 0.36%   |
| de_CH   | 19       | 0.36%   |
| ru_UA   | 16       | 0.3%    |
| tr_TR   | 15       | 0.28%   |
| es_CO   | 14       | 0.26%   |
| pt_PT   | 13       | 0.25%   |
| fr_BE   | 13       | 0.25%   |
| da_DK   | 13       | 0.25%   |
| Unknown | 13       | 0.25%   |
| es_VE   | 12       | 0.23%   |
| es_CL   | 11       | 0.21%   |
| en_HK   | 9        | 0.17%   |
| ro_RO   | 8        | 0.15%   |
| en_IL   | 8        | 0.15%   |
| es_PE   | 7        | 0.13%   |
| uk_UA   | 6        | 0.11%   |
| nl_BE   | 6        | 0.11%   |
| en_ZA   | 6        | 0.11%   |
| nb_NO   | 5        | 0.09%   |
| es_SV   | 5        | 0.09%   |
| es_UY   | 4        | 0.08%   |
| es_EC   | 4        | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 3076     | 58.11%  |
| EFI  | 2217     | 41.89%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Overlay  | 4479     | 84.14%  |
| Ext4     | 791      | 14.86%  |
| Btrfs    | 28       | 0.53%   |
| Xfs      | 6        | 0.11%   |
| F2fs     | 5        | 0.09%   |
| Ext3     | 5        | 0.09%   |
| Unknown  | 4        | 0.08%   |
| Reiserfs | 2        | 0.04%   |
| Jfs      | 2        | 0.04%   |
| Ext2     | 1        | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 3152     | 59.48%  |
| MBR     | 2120     | 40.01%  |
| Unknown | 27       | 0.51%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 3370     | 63.52%  |
| No        | 1935     | 36.48%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 2876     | 54.28%  |
| No        | 2422     | 45.72%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 1291     | 24.4%   |
| Gigabyte Technology | 963      | 18.2%   |
| MSI                 | 578      | 10.93%  |
| ASRock              | 498      | 9.41%   |
| Hewlett-Packard     | 434      | 8.2%    |
| Dell                | 423      | 8%      |
| Lenovo              | 204      | 3.86%   |
| Intel               | 146      | 2.76%   |
| Acer                | 118      | 2.23%   |
| Pegatron            | 70       | 1.32%   |
| Fujitsu             | 65       | 1.23%   |
| Biostar             | 64       | 1.21%   |
| Foxconn             | 63       | 1.19%   |
| ECS                 | 44       | 0.83%   |
| Medion              | 41       | 0.78%   |
| Unknown             | 36       | 0.68%   |
| Positivo            | 20       | 0.38%   |
| BESSTAR Tech        | 14       | 0.26%   |
| AZW                 | 13       | 0.25%   |
| Shuttle             | 12       | 0.23%   |
| PCWare              | 12       | 0.23%   |
| Packard Bell        | 11       | 0.21%   |
| Fujitsu Siemens     | 11       | 0.21%   |
| Supermicro          | 9        | 0.17%   |
| Gateway             | 9        | 0.17%   |
| Alienware           | 9        | 0.17%   |
| MACHINIST           | 8        | 0.15%   |
| OEM                 | 7        | 0.13%   |
| Huanan              | 6        | 0.11%   |
| Semp Toshiba        | 5        | 0.09%   |
| Itautec             | 5        | 0.09%   |
| Inventec            | 5        | 0.09%   |
| Apple               | 5        | 0.09%   |
| Philco              | 4        | 0.08%   |
| Wistron             | 3        | 0.06%   |
| MouseComputer       | 3        | 0.06%   |
| Login Informatica   | 3        | 0.06%   |
| eMachines           | 3        | 0.06%   |
| AMD                 | 3        | 0.06%   |
| ABIT                | 3        | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| ASUS All Series              | 113      | 2.14%   |
| Unknown                      | 39       | 0.74%   |
| Dell OptiPlex 780            | 36       | 0.68%   |
| Dell OptiPlex 7010           | 35       | 0.66%   |
| Gigabyte H410M H V3          | 27       | 0.51%   |
| ASUS PRIME A320M-K           | 24       | 0.45%   |
| Gigabyte 970A-DS3P           | 22       | 0.42%   |
| Dell OptiPlex 9020           | 21       | 0.4%    |
| Intel H61                    | 20       | 0.38%   |
| ASUS SABERTOOTH Z77          | 20       | 0.38%   |
| HP Compaq Pro 6300 SFF       | 19       | 0.36%   |
| Gigabyte B450M DS3H          | 19       | 0.36%   |
| Dell OptiPlex 790            | 19       | 0.36%   |
| Dell OptiPlex 3020           | 19       | 0.36%   |
| ASUS TUF Gaming X570-PLUS    | 19       | 0.36%   |
| ASUS PRIME B450M-A           | 19       | 0.36%   |
| MSI MS-7C37                  | 18       | 0.34%   |
| MSI MS-7817                  | 18       | 0.34%   |
| MSI MS-7721                  | 18       | 0.34%   |
| HP EliteDesk 800 G1 SFF      | 18       | 0.34%   |
| Gigabyte A320M-S2H           | 17       | 0.32%   |
| ASUS M5A78L-M/USB3           | 17       | 0.32%   |
| Dell OptiPlex 380            | 15       | 0.28%   |
| ASUS PRIME B450M-A II        | 15       | 0.28%   |
| HP Compaq 8200 Elite SFF PC  | 14       | 0.26%   |
| ASUS M5A97 R2.0              | 14       | 0.26%   |
| MSI MS-7C02                  | 13       | 0.25%   |
| Gigabyte GA-78LMT-USB3 6.0   | 13       | 0.25%   |
| Dell OptiPlex 390            | 13       | 0.25%   |
| ASUS ROG STRIX B550-F GAMING | 13       | 0.25%   |
| MSI MS-7C91                  | 12       | 0.23%   |
| MSI MS-7C56                  | 12       | 0.23%   |
| MSI MS-7C52                  | 12       | 0.23%   |
| MSI MS-7B86                  | 12       | 0.23%   |
| MSI MS-7B79                  | 12       | 0.23%   |
| MSI MS-7693                  | 12       | 0.23%   |
| MSI MS-7641                  | 12       | 0.23%   |
| Gigabyte G31M-ES2L           | 12       | 0.23%   |
| Gigabyte B75M-D3H            | 12       | 0.23%   |
| Gigabyte B450 AORUS ELITE    | 12       | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 289      | 5.46%   |
| ASUS PRIME             | 238      | 4.5%    |
| HP Compaq              | 161      | 3.04%   |
| Lenovo ThinkCentre     | 128      | 2.42%   |
| ASUS All               | 113      | 2.14%   |
| ASUS ROG               | 94       | 1.78%   |
| ASUS TUF               | 83       | 1.57%   |
| Acer Aspire            | 82       | 1.55%   |
| HP EliteDesk           | 66       | 1.25%   |
| Fujitsu ESPRIMO        | 58       | 1.1%    |
| ASUS M5A78L-M          | 56       | 1.06%   |
| HP ProDesk             | 52       | 0.98%   |
| Gigabyte B450M         | 41       | 0.78%   |
| Unknown                | 39       | 0.74%   |
| Dell Precision         | 37       | 0.7%    |
| Dell Inspiron          | 36       | 0.68%   |
| ASUS SABERTOOTH        | 36       | 0.68%   |
| ASUS P8H61-M           | 36       | 0.68%   |
| Gigabyte B450          | 35       | 0.66%   |
| Gigabyte H410M         | 34       | 0.64%   |
| Dell Vostro            | 34       | 0.64%   |
| Lenovo IdeaCentre      | 32       | 0.6%    |
| HP Pavilion            | 32       | 0.6%    |
| Gigabyte X570          | 31       | 0.59%   |
| ASUS M5A97             | 29       | 0.55%   |
| Acer Veriton           | 27       | 0.51%   |
| ASUS P8Z77-V           | 26       | 0.49%   |
| ASRock B450M           | 26       | 0.49%   |
| Gigabyte GA-78LMT-USB3 | 25       | 0.47%   |
| Intel H61              | 22       | 0.42%   |
| Gigabyte 970A-DS3P     | 22       | 0.42%   |
| Gigabyte A320M-S2H     | 21       | 0.4%    |
| ASUS P5K               | 19       | 0.36%   |
| MSI MS-7C37            | 18       | 0.34%   |
| MSI MS-7817            | 18       | 0.34%   |
| MSI MS-7721            | 18       | 0.34%   |
| Gigabyte Z390          | 18       | 0.34%   |
| ASUS P5G41T-M          | 16       | 0.3%    |
| Gigabyte B550M         | 15       | 0.28%   |
| ASRock B450            | 14       | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 593      | 11.21%  |
| 2013 | 481      | 9.09%   |
| 2018 | 472      | 8.92%   |
| 2011 | 424      | 8.02%   |
| 2014 | 367      | 6.94%   |
| 2010 | 354      | 6.69%   |
| 2009 | 335      | 6.33%   |
| 2020 | 329      | 6.22%   |
| 2019 | 325      | 6.14%   |
| 2017 | 284      | 5.37%   |
| 2008 | 265      | 5.01%   |
| 2021 | 250      | 4.73%   |
| 2015 | 232      | 4.39%   |
| 2016 | 222      | 4.2%    |
| 2007 | 168      | 3.18%   |
| 2006 | 113      | 2.14%   |
| 2022 | 53       | 1%      |
| 2005 | 18       | 0.34%   |
| 2004 | 5        | 0.09%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 5290     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 5290     | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 5290     | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 1205     | 22.75%  |
| 16.01-24.0      | 1110     | 20.96%  |
| 3.01-4.0        | 1064     | 20.09%  |
| 4.01-8.0        | 1029     | 19.43%  |
| 32.01-64.0      | 465      | 8.78%   |
| 1.01-2.0        | 172      | 3.25%   |
| 24.01-32.0      | 95       | 1.79%   |
| 64.01-256.0     | 92       | 1.74%   |
| 2.01-3.0        | 50       | 0.94%   |
| 0.51-1.0        | 10       | 0.19%   |
| More than 256.0 | 4        | 0.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 3772     | 70.93%  |
| 0.51-1.0   | 848      | 15.95%  |
| 2.01-3.0   | 457      | 8.59%   |
| 0.01-0.5   | 149      | 2.8%    |
| 3.01-4.0   | 56       | 1.05%   |
| 4.01-8.0   | 26       | 0.49%   |
| 8.01-16.0  | 9        | 0.17%   |
| 16.01-24.0 | 1        | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 2321     | 43.81%  |
| 2      | 1406     | 26.54%  |
| 3      | 738      | 13.93%  |
| 4      | 411      | 7.76%   |
| 5      | 169      | 3.19%   |
| 0      | 110      | 2.08%   |
| 6      | 72       | 1.36%   |
| 7      | 33       | 0.62%   |
| 8      | 23       | 0.43%   |
| 9      | 6        | 0.11%   |
| 12     | 3        | 0.06%   |
| 15     | 2        | 0.04%   |
| 18     | 1        | 0.02%   |
| 17     | 1        | 0.02%   |
| 11     | 1        | 0.02%   |
| 10     | 1        | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 3201     | 60.46%  |
| No        | 2093     | 39.54%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 5237     | 99%     |
| No        | 53       | 1%      |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 3474     | 65.65%  |
| Yes       | 1818     | 34.35%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 4110     | 77.68%  |
| Yes       | 1181     | 22.32%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 672      | 12.7%   |
| Germany     | 615      | 11.63%  |
| Russia      | 486      | 9.19%   |
| France      | 384      | 7.26%   |
| Brazil      | 366      | 6.92%   |
| Poland      | 265      | 5.01%   |
| Italy       | 222      | 4.2%    |
| Spain       | 174      | 3.29%   |
| Canada      | 164      | 3.1%    |
| UK          | 159      | 3.01%   |
| Australia   | 102      | 1.93%   |
| Mexico      | 82       | 1.55%   |
| Hungary     | 79       | 1.49%   |
| Czechia     | 78       | 1.47%   |
| Ukraine     | 71       | 1.34%   |
| Argentina   | 70       | 1.32%   |
| Netherlands | 67       | 1.27%   |
| India       | 67       | 1.27%   |
| Austria     | 64       | 1.21%   |
| Japan       | 53       | 1%      |
| Romania     | 45       | 0.85%   |
| Sweden      | 42       | 0.79%   |
| Switzerland | 41       | 0.78%   |
| Finland     | 41       | 0.78%   |
| Belgium     | 41       | 0.78%   |
| Serbia      | 39       | 0.74%   |
| Greece      | 39       | 0.74%   |
| Portugal    | 34       | 0.64%   |
| Slovakia    | 32       | 0.6%    |
| Indonesia   | 31       | 0.59%   |
| Turkey      | 30       | 0.57%   |
| Israel      | 29       | 0.55%   |
| Bulgaria    | 27       | 0.51%   |
| Egypt       | 25       | 0.47%   |
| Norway      | 21       | 0.4%    |
| Denmark     | 21       | 0.4%    |
| Venezuela   | 20       | 0.38%   |
| Peru        | 19       | 0.36%   |
| China       | 19       | 0.36%   |
| Belarus     | 19       | 0.36%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Moscow           | 88       | 1.66%   |
| Sao Paulo        | 45       | 0.85%   |
| Warsaw           | 38       | 0.72%   |
| Berlin           | 36       | 0.68%   |
| St Petersburg    | 35       | 0.66%   |
| Paris            | 32       | 0.6%    |
| Vienna           | 30       | 0.57%   |
| Rio de Janeiro   | 29       | 0.55%   |
| Mexico City      | 28       | 0.53%   |
| Milan            | 25       | 0.47%   |
| Rome             | 24       | 0.45%   |
| Gonikoppal       | 22       | 0.42%   |
| Melbourne        | 21       | 0.4%    |
| Madrid           | 20       | 0.38%   |
| Sydney           | 19       | 0.36%   |
| Nizhniy Novgorod | 19       | 0.36%   |
| Hamburg          | 19       | 0.36%   |
| Strzyzow         | 18       | 0.34%   |
| Budapest         | 18       | 0.34%   |
| Novosibirsk      | 17       | 0.32%   |
| Yekaterinburg    | 16       | 0.3%    |
| Prague           | 16       | 0.3%    |
| Munich           | 16       | 0.3%    |
| Helsinki         | 16       | 0.3%    |
| Cairo            | 16       | 0.3%    |
| Belgrade         | 16       | 0.3%    |
| Nuremberg        | 15       | 0.28%   |
| Montreal         | 15       | 0.28%   |
| Buenos Aires     | 15       | 0.28%   |
| Athens           | 15       | 0.28%   |
| Porto Alegre     | 14       | 0.26%   |
| Brisbane         | 14       | 0.26%   |
| Barcelona        | 14       | 0.26%   |
| Stuttgart        | 13       | 0.25%   |
| San José        | 13       | 0.25%   |
| Kyiv             | 12       | 0.23%   |
| Chelyabinsk      | 12       | 0.23%   |
| Perm             | 11       | 0.21%   |
| Marseille        | 11       | 0.21%   |
| Lima             | 11       | 0.21%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 1906     | 2466   | 21.17%  |
| Seagate             | 1764     | 2218   | 19.59%  |
| Samsung Electronics | 1130     | 1484   | 12.55%  |
| Kingston            | 562      | 633    | 6.24%   |
| Toshiba             | 517      | 578    | 5.74%   |
| Crucial             | 433      | 521    | 4.81%   |
| Hitachi             | 333      | 360    | 3.7%    |
| SanDisk             | 315      | 357    | 3.5%    |
| A-DATA Technology   | 218      | 235    | 2.42%   |
| China               | 115      | 129    | 1.28%   |
| Unknown             | 111      | 140    | 1.23%   |
| Intel               | 90       | 98     | 1%      |
| Maxtor              | 87       | 98     | 0.97%   |
| PNY                 | 71       | 83     | 0.79%   |
| Patriot             | 70       | 74     | 0.78%   |
| SPCC                | 68       | 78     | 0.76%   |
| Intenso             | 67       | 74     | 0.74%   |
| GOODRAM             | 67       | 75     | 0.74%   |
| HGST                | 60       | 72     | 0.67%   |
| Apacer              | 52       | 57     | 0.58%   |
| Phison              | 48       | 62     | 0.53%   |
| OCZ                 | 47       | 48     | 0.52%   |
| Corsair             | 43       | 45     | 0.48%   |
| Transcend           | 39       | 41     | 0.43%   |
| Gigabyte Technology | 35       | 38     | 0.39%   |
| JMicron Technology  | 33       | 34     | 0.37%   |
| Team                | 30       | 32     | 0.33%   |
| Netac               | 30       | 31     | 0.33%   |
| Hewlett-Packard     | 29       | 34     | 0.32%   |
| Unknown             | 28       | 29     | 0.31%   |
| SK hynix            | 27       | 27     | 0.3%    |
| Micron Technology   | 26       | 27     | 0.29%   |
| ASMT                | 24       | 26     | 0.27%   |
| Silicon Motion      | 23       | 25     | 0.26%   |
| XPG                 | 22       | 26     | 0.24%   |
| Plextor             | 18       | 20     | 0.2%    |
| KingSpec            | 17       | 17     | 0.19%   |
| Fujitsu             | 17       | 17     | 0.19%   |
| KIOXIA-EXCERIA      | 16       | 16     | 0.18%   |
| LITEON              | 13       | 13     | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 174      | 1.68%   |
| Seagate ST1000DM010-2EP102 1TB   | 135      | 1.31%   |
| Kingston SA400S37240G 240GB SSD  | 135      | 1.31%   |
| Toshiba DT01ACA100 1TB           | 101      | 0.98%   |
| Seagate ST2000DM008-2FR102 2TB   | 91       | 0.88%   |
| WDC WD10EZEX-08WN4A0 1TB         | 85       | 0.82%   |
| Toshiba DT01ACA050 500GB         | 77       | 0.74%   |
| Samsung SSD 860 EVO 500GB        | 71       | 0.69%   |
| Kingston SA400S37480G 480GB SSD  | 67       | 0.65%   |
| Seagate ST3500418AS 500GB        | 66       | 0.64%   |
| Kingston SV300S37A120G 120GB SSD | 66       | 0.64%   |
| Seagate ST1000DM003-1ER162 1TB   | 65       | 0.63%   |
| Kingston SA400S37120G 120GB SSD  | 64       | 0.62%   |
| Crucial CT500MX500SSD1 500GB     | 62       | 0.6%    |
| Samsung SSD 860 EVO 250GB        | 60       | 0.58%   |
| Unknown SD/MMC/MS PRO 2GB        | 57       | 0.55%   |
| Samsung SSD 850 EVO 250GB        | 57       | 0.55%   |
| Toshiba HDWD110 1TB              | 55       | 0.53%   |
| Crucial CT1000MX500SSD1 1TB      | 55       | 0.53%   |
| Crucial CT240BX500SSD1 240GB     | 51       | 0.49%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 49       | 0.47%   |
| Samsung SSD 970 EVO Plus 500GB   | 49       | 0.47%   |
| Seagate ST3500413AS 500GB        | 48       | 0.46%   |
| Toshiba DT01ACA200 2TB           | 47       | 0.45%   |
| WDC WD10EZEX-00BN5A0 1TB         | 44       | 0.43%   |
| Seagate ST1000DM003-1CH162 1TB   | 44       | 0.43%   |
| Seagate ST2000DM001-1ER164 2TB   | 42       | 0.41%   |
| Seagate ST1000DM003-1SB102 1TB   | 42       | 0.41%   |
| Samsung SSD 850 EVO 500GB        | 41       | 0.4%    |
| Crucial CT480BX500SSD1 480GB     | 41       | 0.4%    |
| WDC WD20EZRZ-00Z5HB0 2TB         | 37       | 0.36%   |
| Samsung SSD 860 EVO 1TB          | 37       | 0.36%   |
| Seagate ST2000DM006-2DM164 2TB   | 36       | 0.35%   |
| Seagate ST2000DM001-1CH164 2TB   | 34       | 0.33%   |
| Samsung HD103SJ 1TB              | 34       | 0.33%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 33       | 0.32%   |
| Samsung HD502HJ 500GB            | 33       | 0.32%   |
| Seagate ST31000528AS 1TB         | 31       | 0.3%    |
| Seagate ST31000524AS 1TB         | 31       | 0.3%    |
| Seagate ST3500312CS 500GB        | 30       | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1742     | 2184   | 35.37%  |
| WDC                 | 1665     | 2082   | 33.81%  |
| Toshiba             | 473      | 528    | 9.6%    |
| Samsung Electronics | 373      | 418    | 7.57%   |
| Hitachi             | 333      | 360    | 6.76%   |
| Maxtor              | 86       | 97     | 1.75%   |
| Unknown             | 61       | 61     | 1.24%   |
| HGST                | 60       | 72     | 1.22%   |
| ASMT                | 24       | 26     | 0.49%   |
| Fujitsu             | 16       | 16     | 0.32%   |
| SABRENT             | 8        | 10     | 0.16%   |
| Hewlett-Packard     | 8        | 8      | 0.16%   |
| WD MediaMax         | 7        | 8      | 0.14%   |
| USB3.0              | 7        | 7      | 0.14%   |
| Intenso             | 7        | 7      | 0.14%   |
| Apple               | 7        | 7      | 0.14%   |
| IBM/Hitachi         | 5        | 5      | 0.1%    |
| ExcelStor           | 5        | 5      | 0.1%    |
| Quantum             | 4        | 4      | 0.08%   |
| HPE                 | 4        | 4      | 0.08%   |
| ASMedia             | 4        | 4      | 0.08%   |
| Unknown             | 3        | 3      | 0.06%   |
| MDT                 | 2        | 2      | 0.04%   |
| Magnetic Data       | 2        | 2      | 0.04%   |
| JMicron Technology  | 2        | 2      | 0.04%   |
| HGST HTS            | 2        | 2      | 0.04%   |
| China               | 2        | 2      | 0.04%   |
| USB 3.0             | 1        | 2      | 0.02%   |
| USB                 | 1        | 1      | 0.02%   |
| TPH00800640GB       | 1        | 1      | 0.02%   |
| StoreJet            | 1        | 1      | 0.02%   |
| RSH-339             | 1        | 1      | 0.02%   |
| RSH-319             | 1        | 1      | 0.02%   |
| Promise             | 1        | 1      | 0.02%   |
| MARVELL             | 1        | 1      | 0.02%   |
| KESU                | 1        | 1      | 0.02%   |
| IB                  | 1        | 2      | 0.02%   |
| FC-1307             | 1        | 1      | 0.02%   |
| Config              | 1        | 1      | 0.02%   |
| ASMT106x            | 1        | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 564      | 701    | 17.39%  |
| Kingston            | 485      | 542    | 14.95%  |
| Crucial             | 364      | 437    | 11.22%  |
| SanDisk             | 282      | 315    | 8.69%   |
| WDC                 | 225      | 247    | 6.94%   |
| A-DATA Technology   | 186      | 196    | 5.73%   |
| China               | 113      | 127    | 3.48%   |
| PNY                 | 64       | 74     | 1.97%   |
| GOODRAM             | 64       | 70     | 1.97%   |
| Patriot             | 61       | 65     | 1.88%   |
| Intenso             | 60       | 66     | 1.85%   |
| SPCC                | 53       | 61     | 1.63%   |
| Intel               | 48       | 52     | 1.48%   |
| OCZ                 | 47       | 48     | 1.45%   |
| Apacer              | 46       | 50     | 1.42%   |
| Toshiba             | 40       | 40     | 1.23%   |
| Transcend           | 33       | 34     | 1.02%   |
| Team                | 26       | 27     | 0.8%    |
| Micron Technology   | 24       | 25     | 0.74%   |
| Netac               | 23       | 24     | 0.71%   |
| Unknown             | 23       | 24     | 0.71%   |
| Corsair             | 22       | 23     | 0.68%   |
| Gigabyte Technology | 20       | 20     | 0.62%   |
| JMicron Technology  | 19       | 20     | 0.59%   |
| KingSpec            | 17       | 17     | 0.52%   |
| Unknown             | 15       | 16     | 0.46%   |
| Hewlett-Packard     | 15       | 17     | 0.46%   |
| KIOXIA-EXCERIA      | 13       | 13     | 0.4%    |
| SK hynix            | 12       | 12     | 0.37%   |
| Plextor             | 12       | 14     | 0.37%   |
| LITEON              | 10       | 10     | 0.31%   |
| KingFast            | 10       | 11     | 0.31%   |
| XrayDisk            | 9        | 9      | 0.28%   |
| TO Exter            | 9        | 9      | 0.28%   |
| Lexar               | 9        | 9      | 0.28%   |
| KingDian            | 9        | 10     | 0.28%   |
| Seagate             | 8        | 8      | 0.25%   |
| Leven               | 8        | 8      | 0.25%   |
| Colorful            | 7        | 7      | 0.22%   |
| Verbatim            | 6        | 6      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 3853     | 5941   | 52%     |
| SSD     | 2578     | 3651   | 34.79%  |
| NVMe    | 884      | 1138   | 11.93%  |
| Unknown | 80       | 110    | 1.08%   |
| MMC     | 15       | 17     | 0.2%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 4957     | 9236   | 79.52%  |
| NVMe | 878      | 1126   | 14.08%  |
| SAS  | 384      | 478    | 6.16%   |
| MMC  | 15       | 17     | 0.24%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 3926     | 5803   | 56.86%  |
| 0.51-1.0   | 1876     | 2446   | 27.17%  |
| 1.01-2.0   | 642      | 769    | 9.3%    |
| 2.01-3.0   | 172      | 206    | 2.49%   |
| 3.01-4.0   | 143      | 187    | 2.07%   |
| 4.01-10.0  | 125      | 159    | 1.81%   |
| 10.01-20.0 | 21       | 22     | 0.3%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 2670     | 50.12%  |
| Unknown        | 880      | 16.52%  |
| 101-250        | 616      | 11.56%  |
| 251-500        | 411      | 7.72%   |
| 501-1000       | 230      | 4.32%   |
| 51-100         | 183      | 3.44%   |
| 21-50          | 174      | 3.27%   |
| 1001-2000      | 91       | 1.71%   |
| 2001-3000      | 37       | 0.69%   |
| More than 3000 | 35       | 0.66%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 3978     | 74.8%   |
| Unknown        | 880      | 16.55%  |
| 101-250        | 110      | 2.07%   |
| 51-100         | 82       | 1.54%   |
| 21-50          | 81       | 1.52%   |
| 251-500        | 75       | 1.41%   |
| 501-1000       | 62       | 1.17%   |
| 1001-2000      | 32       | 0.6%    |
| More than 3000 | 9        | 0.17%   |
| 2001-3000      | 9        | 0.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 71       | 73     | 3.67%   |
| Seagate ST3500418AS 500GB         | 30       | 31     | 1.55%   |
| WDC WD5000AAKX-001CA0 500GB       | 17       | 18     | 0.88%   |
| Seagate ST31000524AS 1TB          | 17       | 17     | 0.88%   |
| Toshiba DT01ACA100 1TB            | 16       | 16     | 0.83%   |
| Toshiba DT01ACA050 500GB          | 16       | 16     | 0.83%   |
| Samsung Electronics HD322HJ 320GB | 16       | 17     | 0.83%   |
| Kingston SV300S37A120G 120GB SSD  | 16       | 16     | 0.83%   |
| Seagate ST9500325AS 500GB         | 15       | 15     | 0.77%   |
| Seagate ST3500413AS 500GB         | 15       | 15     | 0.77%   |
| Seagate ST3320418AS 320GB         | 13       | 13     | 0.67%   |
| Seagate ST1000DM010-2EP102 1TB    | 13       | 13     | 0.67%   |
| Seagate ST1000DM003-9YN162 1TB    | 13       | 13     | 0.67%   |
| Samsung Electronics HD161HJ 160GB | 13       | 13     | 0.67%   |
| Seagate ST31000528AS 1TB          | 12       | 12     | 0.62%   |
| Seagate ST2000DM001-1CH164 2TB    | 12       | 12     | 0.62%   |
| Samsung Electronics HD502HJ 500GB | 12       | 12     | 0.62%   |
| Hitachi HDS721050CLA362 500GB     | 12       | 13     | 0.62%   |
| Seagate ST250DM000-1BD141 250GB   | 11       | 11     | 0.57%   |
| Samsung Electronics HD103SJ 1TB   | 11       | 12     | 0.57%   |
| WDC WD5000AADS-00S9B0 500GB       | 10       | 10     | 0.52%   |
| Seagate ST2000DL003-9VT166 2TB    | 10       | 11     | 0.52%   |
| Samsung Electronics HD103UJ 1TB   | 10       | 10     | 0.52%   |
| Samsung Electronics HD103SI 1TB   | 10       | 10     | 0.52%   |
| WDC WD5000AAKX-75U6AA0 500GB      | 9        | 9      | 0.46%   |
| WDC WD5000AAKX-003CA0 500GB       | 9        | 9      | 0.46%   |
| WDC WD3200AAJS-00L7A0 320GB       | 9        | 9      | 0.46%   |
| Seagate ST3320613AS 320GB         | 9        | 9      | 0.46%   |
| Seagate ST3250820AS 250GB         | 9        | 10     | 0.46%   |
| Maxtor STM3250310AS 250GB         | 9        | 9      | 0.46%   |
| WDC WDS240G2G0A-00JH30 240GB SSD  | 8        | 8      | 0.41%   |
| WDC WD5000AAKS-00V1A0 500GB       | 8        | 8      | 0.41%   |
| WDC WD20EZRZ-00Z5HB0 2TB          | 8        | 8      | 0.41%   |
| WDC WD20EARS-00MVWB0 2TB          | 8        | 8      | 0.41%   |
| Seagate ST3250318AS 249GB         | 8        | 8      | 0.41%   |
| Seagate ST3250310AS 250GB         | 8        | 8      | 0.41%   |
| Seagate ST1000DM003-1SB102 1TB    | 8        | 8      | 0.41%   |
| Seagate ST1000DM003-1CH162 1TB    | 8        | 9      | 0.41%   |
| Samsung Electronics SP2504C 250GB | 8        | 8      | 0.41%   |
| Kingston SA400S37480G 480GB SSD   | 8        | 9      | 0.41%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 556      | 608    | 30.23%  |
| WDC                 | 554      | 623    | 30.13%  |
| Samsung Electronics | 200      | 216    | 10.88%  |
| Hitachi             | 139      | 151    | 7.56%   |
| Toshiba             | 71       | 72     | 3.86%   |
| Maxtor              | 54       | 56     | 2.94%   |
| Kingston            | 53       | 55     | 2.88%   |
| SanDisk             | 30       | 30     | 1.63%   |
| HGST                | 18       | 19     | 0.98%   |
| Crucial             | 18       | 19     | 0.98%   |
| A-DATA Technology   | 17       | 17     | 0.92%   |
| Intel               | 13       | 13     | 0.71%   |
| China               | 11       | 11     | 0.6%    |
| OCZ                 | 7        | 7      | 0.38%   |
| GOODRAM             | 7        | 7      | 0.38%   |
| ASMT                | 7        | 7      | 0.38%   |
| Fujitsu             | 6        | 6      | 0.33%   |
| Unknown             | 6        | 6      | 0.33%   |
| SPCC                | 5        | 5      | 0.27%   |
| Micron Technology   | 4        | 4      | 0.22%   |
| Corsair             | 4        | 4      | 0.22%   |
| SK hynix            | 3        | 3      | 0.16%   |
| Patriot             | 3        | 3      | 0.16%   |
| Netac               | 3        | 3      | 0.16%   |
| IBM/Hitachi         | 3        | 3      | 0.16%   |
| Hewlett-Packard     | 3        | 3      | 0.16%   |
| XPG                 | 2        | 2      | 0.11%   |
| WD MediaMax         | 2        | 2      | 0.11%   |
| USB3.0              | 2        | 2      | 0.11%   |
| LITEON              | 2        | 2      | 0.11%   |
| KingSpec            | 2        | 2      | 0.11%   |
| Intenso             | 2        | 2      | 0.11%   |
| Initio              | 2        | 2      | 0.11%   |
| HPE                 | 2        | 2      | 0.11%   |
| Apacer              | 2        | 3      | 0.11%   |
| WDC WDS2            | 1        | 1      | 0.05%   |
| Transcend           | 1        | 1      | 0.05%   |
| TO Exter            | 1        | 1      | 0.05%   |
| TEXTORM             | 1        | 1      | 0.05%   |
| Team                | 1        | 1      | 0.05%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 556      | 608    | 35.26%  |
| WDC                 | 533      | 599    | 33.8%   |
| Samsung Electronics | 176      | 190    | 11.16%  |
| Hitachi             | 139      | 151    | 8.81%   |
| Toshiba             | 70       | 71     | 4.44%   |
| Maxtor              | 54       | 56     | 3.42%   |
| HGST                | 18       | 19     | 1.14%   |
| ASMT                | 7        | 7      | 0.44%   |
| Fujitsu             | 6        | 6      | 0.38%   |
| IBM/Hitachi         | 3        | 3      | 0.19%   |
| WD MediaMax         | 2        | 2      | 0.13%   |
| USB3.0              | 2        | 2      | 0.13%   |
| HPE                 | 2        | 2      | 0.13%   |
| Hewlett-Packard     | 2        | 2      | 0.13%   |
| RSH-339             | 1        | 1      | 0.06%   |
| Quantum             | 1        | 1      | 0.06%   |
| IB                  | 1        | 1      | 0.06%   |
| ExcelStor           | 1        | 1      | 0.06%   |
| China               | 1        | 1      | 0.06%   |
| ASMedia             | 1        | 1      | 0.06%   |
| Unknown             | 1        | 1      | 0.06%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 1402     | 1725   | 84.41%  |
| SSD  | 240      | 252    | 14.45%  |
| NVMe | 19       | 20     | 1.14%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Desktops | Drives | Percent |
|--------------------------------------------------|----------|--------|---------|
| Seagate ST3250318AS 249GB                        | 3        | 3      | 5.77%   |
| Samsung Electronics HD103SJ 1TB                  | 3        | 3      | 5.77%   |
| Apple HDD HTS541010A9E662 1TB                    | 3        | 3      | 5.77%   |
| WDC WD800JD-00LSA0 80GB                          | 2        | 2      | 3.85%   |
| WDC WD20EZRX-00D8PB0 2TB                         | 2        | 2      | 3.85%   |
| Seagate ST3500418AS 500GB                        | 2        | 3      | 3.85%   |
| Samsung Electronics HD502HJ 500GB                | 2        | 2      | 3.85%   |
| Samsung Electronics HD103UJ 1TB                  | 2        | 2      | 3.85%   |
| WDC WD800JD-75MSA3 80GB                          | 1        | 1      | 1.92%   |
| WDC WD7501AALS-00J7B0 752GB                      | 1        | 1      | 1.92%   |
| WDC WD7500BPVT-22HXZT3 752GB                     | 1        | 1      | 1.92%   |
| WDC WD5000AAKS-00C8A0 500GB                      | 1        | 1      | 1.92%   |
| WDC WD3200AAJS-60Z0A0 320GB                      | 1        | 1      | 1.92%   |
| WDC WD20EARS-00MVWB0 2TB                         | 1        | 1      | 1.92%   |
| WDC WD1600YS-23SHB0 160GB                        | 1        | 1      | 1.92%   |
| WDC WD10JPVT-75A1YT0 1TB                         | 1        | 1      | 1.92%   |
| WDC WD10EALX-759BA1 1TB                          | 1        | 1      | 1.92%   |
| TPH00800640GB 640GB                              | 1        | 1      | 1.92%   |
| Toshiba MQ01ABD050 500GB                         | 1        | 1      | 1.92%   |
| Toshiba MK3256GSY 320GB                          | 1        | 1      | 1.92%   |
| Toshiba DT01ACA100 1TB                           | 1        | 1      | 1.92%   |
| Seagate STM3250318AS 250GB                       | 1        | 1      | 1.92%   |
| Seagate STM31000528AS 1TB                        | 1        | 1      | 1.92%   |
| Seagate ST980811AS 80GB                          | 1        | 1      | 1.92%   |
| Seagate ST500DM002-1BD142 500GB                  | 1        | 1      | 1.92%   |
| Seagate ST3750640NS 752GB                        | 1        | 1      | 1.92%   |
| Seagate ST3320418AS 320GB                        | 1        | 1      | 1.92%   |
| Seagate ST3250820AS 250GB                        | 1        | 1      | 1.92%   |
| Seagate ST3160215A 160GB                         | 1        | 1      | 1.92%   |
| Seagate ST31000528AS 1TB                         | 1        | 1      | 1.92%   |
| Samsung Electronics SSD 980 500GB                | 1        | 1      | 1.92%   |
| Samsung Electronics MZ7TY128HDHP-000L1 128GB SSD | 1        | 1      | 1.92%   |
| Samsung Electronics HM160HI 160GB                | 1        | 1      | 1.92%   |
| Samsung Electronics HD501LJ 500GB                | 1        | 1      | 1.92%   |
| Maxtor STM3500320AS 500GB                        | 1        | 1      | 1.92%   |
| Kingston SMS200S360G 64GB SSD                    | 1        | 1      | 1.92%   |
| Hitachi HTS725050A7E630 500GB                    | 1        | 1      | 1.92%   |
| Hitachi HDS721010DLE630 1TB                      | 1        | 1      | 1.92%   |
| Hitachi HDS721010CLA332 1TB                      | 1        | 1      | 1.92%   |
| Hitachi HDP725050GLA360 500GB                    | 1        | 1      | 1.92%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 14       | 15     | 26.92%  |
| WDC                 | 13       | 13     | 25%     |
| Samsung Electronics | 11       | 11     | 21.15%  |
| Hitachi             | 4        | 4      | 7.69%   |
| Toshiba             | 3        | 3      | 5.77%   |
| Apple               | 3        | 3      | 5.77%   |
| TPH00800640GB       | 1        | 1      | 1.92%   |
| Maxtor              | 1        | 1      | 1.92%   |
| Kingston            | 1        | 1      | 1.92%   |
| GOODRAM             | 1        | 1      | 1.92%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 4224     | 8058   | 65.51%  |
| Malfunc  | 1613     | 1997   | 25.02%  |
| Detected | 561      | 749    | 8.7%    |
| Failed   | 50       | 53     | 0.78%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 3371     | 48.99%  |
| AMD                              | 1707     | 24.81%  |
| Samsung Electronics              | 303      | 4.4%    |
| ASMedia Technology               | 198      | 2.88%   |
| JMicron Technology               | 194      | 2.82%   |
| Nvidia                           | 184      | 2.67%   |
| Marvell Technology Group         | 171      | 2.49%   |
| SanDisk                          | 155      | 2.25%   |
| Phison Electronics               | 123      | 1.79%   |
| Kingston Technology Company      | 88       | 1.28%   |
| Micron/Crucial Technology        | 72       | 1.05%   |
| Silicon Motion                   | 68       | 0.99%   |
| VIA Technologies                 | 58       | 0.84%   |
| ADATA Technology                 | 31       | 0.45%   |
| Realtek Semiconductor            | 22       | 0.32%   |
| SK hynix                         | 14       | 0.2%    |
| Seagate Technology               | 14       | 0.2%    |
| Silicon Image                    | 12       | 0.17%   |
| Toshiba America Info Systems     | 11       | 0.16%   |
| Micron Technology                | 10       | 0.15%   |
| LSI Logic / Symbios Logic        | 9        | 0.13%   |
| Lite-On Technology               | 8        | 0.12%   |
| MAXIO Technology (Hangzhou)      | 7        | 0.1%    |
| Integrated Technology Express    | 7        | 0.1%    |
| Broadcom / LSI                   | 7        | 0.1%    |
| Shenzhen Longsys Electronics     | 6        | 0.09%   |
| KIOXIA                           | 6        | 0.09%   |
| Lite-On IT Corp. / Plextor       | 4        | 0.06%   |
| Adaptec                          | 3        | 0.04%   |
| Union Memory (Shenzhen)          | 2        | 0.03%   |
| Silicon Integrated Systems [SiS] | 2        | 0.03%   |
| Promise Technology               | 2        | 0.03%   |
| Netac Technology                 | 2        | 0.03%   |
| INNOGRIT                         | 2        | 0.03%   |
| Hewlett-Packard                  | 2        | 0.03%   |
| 3ware                            | 2        | 0.03%   |
| Yangtze Memory Technologies      | 1        | 0.01%   |
| Solid State Storage Technology   | 1        | 0.01%   |
| OCZ Technology Group             | 1        | 0.01%   |
| Biwin Storage Technology         | 1        | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 898      | 9.97%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 449      | 4.98%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 341      | 3.79%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 331      | 3.67%   |
| AMD 400 Series Chipset SATA Controller                                                  | 326      | 3.62%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 298      | 3.31%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 262      | 2.91%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 251      | 2.79%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 243      | 2.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 232      | 2.58%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 226      | 2.51%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 185      | 2.05%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 181      | 2.01%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 174      | 1.93%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 165      | 1.83%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 164      | 1.82%   |
| Intel SATA Controller [RAID mode]                                                       | 158      | 1.75%   |
| AMD 500 Series Chipset SATA Controller                                                  | 156      | 1.73%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 146      | 1.62%   |
| AMD FCH SATA Controller D                                                               | 118      | 1.31%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 113      | 1.25%   |
| Nvidia MCP61 SATA Controller                                                            | 106      | 1.18%   |
| Nvidia MCP61 IDE                                                                        | 96       | 1.07%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 95       | 1.05%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 91       | 1.01%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 86       | 0.95%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 83       | 0.92%   |
| AMD 300 Series Chipset SATA Controller                                                  | 79       | 0.88%   |
| AMD FCH IDE Controller                                                                  | 77       | 0.85%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 72       | 0.8%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 69       | 0.77%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 62       | 0.69%   |
| Phison E12 NVMe Controller                                                              | 60       | 0.67%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 59       | 0.65%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 57       | 0.63%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 56       | 0.62%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 55       | 0.61%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 53       | 0.59%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 53       | 0.59%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 53       | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 4049     | 58.74%  |
| IDE  | 1699     | 24.65%  |
| NVMe | 871      | 12.64%  |
| RAID | 246      | 3.57%   |
| SAS  | 17       | 0.25%   |
| SCSI | 11       | 0.16%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 3419     | 64.63%  |
| AMD    | 1871     | 35.37%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 87       | 1.64%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 73       | 1.38%   |
| AMD Ryzen 5 3600 6-Core Processor           | 71       | 1.34%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 61       | 1.15%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 58       | 1.1%    |
| Intel Core i3-2120 CPU @ 3.30GHz            | 56       | 1.06%   |
| AMD FX-8350 Eight-Core Processor            | 56       | 1.06%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 55       | 1.04%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 54       | 1.02%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 52       | 0.98%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 52       | 0.98%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 50       | 0.95%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 48       | 0.91%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 46       | 0.87%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 45       | 0.85%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 45       | 0.85%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 41       | 0.78%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 40       | 0.76%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 39       | 0.74%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 39       | 0.74%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 37       | 0.7%    |
| AMD Ryzen 5 5600G with Radeon Graphics      | 37       | 0.7%    |
| Intel Core i5-6500 CPU @ 3.20GHz            | 36       | 0.68%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 35       | 0.66%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 34       | 0.64%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 34       | 0.64%   |
| AMD FX-6300 Six-Core Processor              | 33       | 0.62%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 32       | 0.6%    |
| Intel Core i5-7400 CPU @ 3.00GHz            | 32       | 0.6%    |
| AMD Ryzen 9 3900X 12-Core Processor         | 32       | 0.6%    |
| AMD Ryzen 7 2700X Eight-Core Processor      | 31       | 0.59%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 31       | 0.59%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 30       | 0.57%   |
| AMD Athlon II X2 250 Processor              | 30       | 0.57%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 29       | 0.55%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 28       | 0.53%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 28       | 0.53%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 28       | 0.53%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 27       | 0.51%   |
| AMD Phenom II X4 955 Processor              | 27       | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 963      | 18.2%   |
| Intel Core i3           | 535      | 10.11%  |
| Intel Core i7           | 485      | 9.17%   |
| AMD Ryzen 5             | 381      | 7.2%    |
| Intel Core 2 Duo        | 268      | 5.07%   |
| AMD FX                  | 226      | 4.27%   |
| Intel Pentium           | 211      | 3.99%   |
| AMD Ryzen 7             | 210      | 3.97%   |
| Intel Celeron           | 200      | 3.78%   |
| Intel Core 2 Quad       | 160      | 3.02%   |
| Intel Xeon              | 148      | 2.8%    |
| Intel Pentium Dual-Core | 128      | 2.42%   |
| AMD Ryzen 3             | 107      | 2.02%   |
| AMD A8                  | 93       | 1.76%   |
| Other                   | 92       | 1.74%   |
| AMD Athlon II X2        | 88       | 1.66%   |
| AMD Phenom II X4        | 84       | 1.59%   |
| AMD Ryzen 9             | 75       | 1.42%   |
| AMD Athlon 64 X2        | 67       | 1.27%   |
| AMD A10                 | 66       | 1.25%   |
| AMD A4                  | 61       | 1.15%   |
| Intel Core 2            | 60       | 1.13%   |
| AMD Athlon              | 52       | 0.98%   |
| AMD A6                  | 50       | 0.95%   |
| Intel Pentium Dual      | 39       | 0.74%   |
| AMD Athlon II X4        | 35       | 0.66%   |
| AMD Phenom              | 32       | 0.6%    |
| AMD Phenom II X6        | 29       | 0.55%   |
| Intel Core i9           | 26       | 0.49%   |
| Intel Pentium 4         | 25       | 0.47%   |
| Intel Atom              | 25       | 0.47%   |
| Intel Pentium D         | 24       | 0.45%   |
| Intel Pentium Gold      | 23       | 0.43%   |
| AMD Athlon II X3        | 22       | 0.42%   |
| AMD Sempron             | 20       | 0.38%   |
| AMD Ryzen 5 PRO         | 17       | 0.32%   |
| AMD Athlon X4           | 17       | 0.32%   |
| AMD Phenom II X2        | 16       | 0.3%    |
| AMD Athlon 64           | 15       | 0.28%   |
| AMD Ryzen Threadripper  | 12       | 0.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 2040     | 38.56%  |
| 2       | 1903     | 35.97%  |
| 6       | 640      | 12.1%   |
| 8       | 312      | 5.9%    |
| 1       | 163      | 3.08%   |
| 3       | 93       | 1.76%   |
| 12      | 71       | 1.34%   |
| 16      | 34       | 0.64%   |
| 10      | 19       | 0.36%   |
| 14      | 5        | 0.09%   |
| 24      | 3        | 0.06%   |
| 32      | 2        | 0.04%   |
| 28      | 2        | 0.04%   |
| 44      | 1        | 0.02%   |
| 20      | 1        | 0.02%   |
| Unknown | 1        | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 5266     | 99.55%  |
| 2      | 24       | 0.45%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 2707     | 51.17%  |
| 2       | 2575     | 48.68%  |
| 4       | 6        | 0.11%   |
| 6       | 1        | 0.02%   |
| Unknown | 1        | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 5287     | 99.94%  |
| Unknown        | 3        | 0.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 564      | 10.66%  |
| 0x306a9    | 428      | 8.09%   |
| 0x1067a    | 413      | 7.8%    |
| 0x206a7    | 379      | 7.16%   |
| 0x08701021 | 196      | 3.7%    |
| 0x506e3    | 184      | 3.48%   |
| Unknown    | 171      | 3.23%   |
| 0x906ea    | 151      | 2.85%   |
| 0x906e9    | 132      | 2.49%   |
| 0x06001119 | 114      | 2.15%   |
| 0x010000c8 | 109      | 2.06%   |
| 0x0800820d | 102      | 1.93%   |
| 0x08101016 | 82       | 1.55%   |
| 0xa0653    | 80       | 1.51%   |
| 0x08108109 | 78       | 1.47%   |
| 0x6fb      | 76       | 1.44%   |
| 0x06000822 | 73       | 1.38%   |
| 0xa0655    | 72       | 1.36%   |
| 0x6fd      | 70       | 1.32%   |
| 0x10676    | 58       | 1.1%    |
| 0x06003106 | 58       | 1.1%    |
| 0x08001138 | 56       | 1.06%   |
| 0x106e5    | 52       | 0.98%   |
| 0x010000b6 | 51       | 0.96%   |
| 0x906eb    | 48       | 0.91%   |
| 0x20655    | 43       | 0.81%   |
| 0x0a201016 | 43       | 0.81%   |
| 0xa0671    | 40       | 0.76%   |
| 0x0600081c | 38       | 0.72%   |
| 0x0a50000c | 37       | 0.7%    |
| 0x906ed    | 35       | 0.66%   |
| 0x106a5    | 35       | 0.66%   |
| 0x6f6      | 32       | 0.6%    |
| 0x08701013 | 31       | 0.59%   |
| 0x0600611a | 31       | 0.59%   |
| 0x6f2      | 29       | 0.55%   |
| 0x30678    | 29       | 0.55%   |
| 0x20652    | 29       | 0.55%   |
| 0x10677    | 29       | 0.55%   |
| 0x08600106 | 29       | 0.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 604      | 11.42%  |
| Penryn           | 504      | 9.53%   |
| IvyBridge        | 450      | 8.51%   |
| KabyLake         | 415      | 7.84%   |
| SandyBridge      | 408      | 7.71%   |
| K10              | 329      | 6.22%   |
| Piledriver       | 309      | 5.84%   |
| Zen 2            | 270      | 5.1%    |
| Zen+             | 219      | 4.14%   |
| Core             | 218      | 4.12%   |
| Zen              | 207      | 3.91%   |
| Skylake          | 197      | 3.72%   |
| Zen 3            | 160      | 3.02%   |
| CometLake        | 154      | 2.91%   |
| K8 Hammer        | 100      | 1.89%   |
| Nehalem          | 92       | 1.74%   |
| Westmere         | 85       | 1.61%   |
| Steamroller      | 73       | 1.38%   |
| Silvermont       | 60       | 1.13%   |
| NetBurst         | 56       | 1.06%   |
| Excavator        | 47       | 0.89%   |
| Bulldozer        | 47       | 0.89%   |
| K10 Llano        | 38       | 0.72%   |
| Alderlake Hybrid | 36       | 0.68%   |
| Icelake          | 33       | 0.62%   |
| Goldmont plus    | 33       | 0.62%   |
| Jaguar           | 28       | 0.53%   |
| Puma             | 23       | 0.43%   |
| Bonnell          | 22       | 0.42%   |
| Bobcat           | 19       | 0.36%   |
| Broadwell        | 16       | 0.3%    |
| Goldmont         | 15       | 0.28%   |
| Tremont          | 11       | 0.21%   |
| Unknown          | 10       | 0.19%   |
| TigerLake        | 2        | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 1956     | 35.8%   |
| Intel                      | 1815     | 33.22%  |
| AMD                        | 1674     | 30.64%  |
| Matrox Electronics Systems | 9        | 0.16%   |
| VIA Technologies           | 6        | 0.11%   |
| ATI Technologies           | 2        | 0.04%   |
| Conexant Systems           | 1        | 0.02%   |
| ASPEED Technology          | 1        | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 297      | 5.36%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 226      | 4.08%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 187      | 3.37%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 187      | 3.37%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 161      | 2.91%   |
| Nvidia GK208B [GeForce GT 710]                                              | 150      | 2.71%   |
| Nvidia GT218 [GeForce 210]                                                  | 121      | 2.18%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 110      | 1.98%   |
| Intel HD Graphics 530                                                       | 103      | 1.86%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 99       | 1.79%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 92       | 1.66%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 87       | 1.57%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 86       | 1.55%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 85       | 1.53%   |
| Nvidia GK208B [GeForce GT 730]                                              | 77       | 1.39%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 77       | 1.39%   |
| Intel HD Graphics 630                                                       | 72       | 1.3%    |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 63       | 1.14%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 54       | 0.97%   |
| Nvidia GF119 [GeForce GT 610]                                               | 52       | 0.94%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 52       | 0.94%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 50       | 0.9%    |
| AMD RS780L [Radeon 3000]                                                    | 49       | 0.88%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 48       | 0.87%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 46       | 0.83%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 46       | 0.83%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 45       | 0.81%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 45       | 0.81%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 42       | 0.76%   |
| Nvidia GF108 [GeForce GT 630]                                               | 41       | 0.74%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 39       | 0.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 39       | 0.7%    |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 37       | 0.67%   |
| Intel Core Processor Integrated Graphics Controller                         | 35       | 0.63%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 34       | 0.61%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 33       | 0.6%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 32       | 0.58%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 31       | 0.56%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 31       | 0.56%   |
| AMD Renoir                                                                  | 30       | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 1862     | 35.19%  |
| 1 x Intel                | 1647     | 31.13%  |
| 1 x AMD                  | 1564     | 29.56%  |
| 2 x AMD                  | 66       | 1.25%   |
| Intel + Nvidia           | 56       | 1.06%   |
| AMD + Nvidia             | 24       | 0.45%   |
| 2 x Intel                | 22       | 0.42%   |
| Intel + AMD              | 20       | 0.38%   |
| 2 x Nvidia               | 11       | 0.21%   |
| 1 x Matrox               | 8        | 0.15%   |
| 1 x VIA                  | 6        | 0.11%   |
| 3 x AMD                  | 1        | 0.02%   |
| Nvidia + Matrox          | 1        | 0.02%   |
| Nvidia + ASPEED          | 1        | 0.02%   |
| Intel + 2 x Nvidia       | 1        | 0.02%   |
| Intel + Conexant Systems | 1        | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 5113     | 96.64%  |
| Unknown     | 170      | 3.21%   |
| Proprietary | 8        | 0.15%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1798     | 33.98%  |
| 1.01-2.0   | 930      | 17.57%  |
| 0.51-1.0   | 859      | 16.23%  |
| 0.01-0.5   | 723      | 13.66%  |
| 3.01-4.0   | 385      | 7.28%   |
| 7.01-8.0   | 332      | 6.27%   |
| 5.01-6.0   | 140      | 2.65%   |
| 2.01-3.0   | 57       | 1.08%   |
| 8.01-16.0  | 57       | 1.08%   |
| 16.01-24.0 | 8        | 0.15%   |
| 4.01-5.0   | 3        | 0.06%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 932      | 17.98%  |
| Goldstar             | 638      | 12.31%  |
| Hewlett-Packard      | 457      | 8.82%   |
| Dell                 | 450      | 8.68%   |
| Acer                 | 404      | 7.79%   |
| Philips              | 322      | 6.21%   |
| AOC                  | 295      | 5.69%   |
| BenQ                 | 234      | 4.51%   |
| Ancor Communications | 211      | 4.07%   |
| ViewSonic            | 130      | 2.51%   |
| Iiyama               | 111      | 2.14%   |
| ASUSTek Computer     | 71       | 1.37%   |
| Lenovo               | 60       | 1.16%   |
| Sony                 | 53       | 1.02%   |
| Eizo                 | 50       | 0.96%   |
| Fujitsu Siemens      | 48       | 0.93%   |
| NEC Computers        | 46       | 0.89%   |
| HannStar             | 36       | 0.69%   |
| Medion               | 27       | 0.52%   |
| Panasonic            | 23       | 0.44%   |
| Toshiba              | 22       | 0.42%   |
| Sceptre Tech         | 22       | 0.42%   |
| Vizio                | 20       | 0.39%   |
| Vestel Elektronik    | 20       | 0.39%   |
| Unknown              | 17       | 0.33%   |
| MSI                  | 15       | 0.29%   |
| Belinea              | 15       | 0.29%   |
| Hitachi              | 14       | 0.27%   |
| Packard Bell         | 13       | 0.25%   |
| MStar                | 13       | 0.25%   |
| Sharp                | 12       | 0.23%   |
| ___                  | 11       | 0.21%   |
| Gigabyte Technology  | 11       | 0.21%   |
| Unknown (XXX)        | 9        | 0.17%   |
| Insignia             | 9        | 0.17%   |
| CHD                  | 9        | 0.17%   |
| TCL                  | 8        | 0.15%   |
| IOD                  | 8        | 0.15%   |
| HKC                  | 8        | 0.15%   |
| Gateway              | 8        | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 39       | 0.74%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 27       | 0.51%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 24       | 0.46%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch           | 22       | 0.42%   |
| Dell D1918H DEL2005 1366x768 410x230mm 18.5-inch                      | 22       | 0.42%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                       | 22       | 0.42%   |
| Vestel Elektronik 50FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch | 20       | 0.38%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 16       | 0.3%    |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 520x290mm 23.4-inch | 16       | 0.3%    |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 15       | 0.28%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                      | 15       | 0.28%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 14       | 0.27%   |
| Philips 273PQPY PHLC096 1920x1080 597x336mm 27.0-inch                 | 14       | 0.27%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch | 14       | 0.27%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 13       | 0.25%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 13       | 0.25%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 12       | 0.23%   |
| Panasonic TV MEIA296 1920x1080 1280x720mm 57.8-inch                   | 12       | 0.23%   |
| Hewlett-Packard w1907 HWP26A2 1440x900 408x255mm 18.9-inch            | 12       | 0.23%   |
| Goldstar W2243 GSM56FE 1920x1080 477x268mm 21.5-inch                  | 12       | 0.23%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch               | 12       | 0.23%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch     | 11       | 0.21%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                      | 11       | 0.21%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 11       | 0.21%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                   | 11       | 0.21%   |
| AOC 936W AOC1936 1366x768 410x230mm 18.5-inch                         | 11       | 0.21%   |
| AOC 24G2W1G4 AOC2402 1920x1080 527x296mm 23.8-inch                    | 11       | 0.21%   |
| AOC 2460 AOC2460 1920x1080 531x299mm 24.0-inch                        | 11       | 0.21%   |
| Acer G246HL ACR02FF 1920x1080 531x299mm 24.0-inch                     | 11       | 0.21%   |
| Ancor Communications VS278 ACI27A1 1920x1080 598x336mm 27.0-inch      | 10       | 0.19%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch  | 9        | 0.17%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 9        | 0.17%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                   | 9        | 0.17%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                | 9        | 0.17%   |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch              | 9        | 0.17%   |
| AOC 24B1W1G5 AOC2401 1920x1080 527x296mm 23.8-inch                    | 9        | 0.17%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch  | 8        | 0.15%   |
| Samsung Electronics SMB1930N SAM0632 1360x768 410x230mm 18.5-inch     | 8        | 0.15%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 600x340mm 27.2-inch     | 8        | 0.15%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch     | 8        | 0.15%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 2530     | 49.54%  |
| 1280x1024 (SXGA)   | 479      | 9.38%   |
| 3840x2160 (4K)     | 375      | 7.34%   |
| 1680x1050 (WSXGA+) | 345      | 6.76%   |
| 1366x768 (WXGA)    | 282      | 5.52%   |
| 2560x1440 (QHD)    | 239      | 4.68%   |
| 1440x900 (WXGA+)   | 230      | 4.5%    |
| 1600x900 (HD+)     | 173      | 3.39%   |
| 1920x1200 (WUXGA)  | 127      | 2.49%   |
| 1360x768           | 95       | 1.86%   |
| 3440x1440          | 47       | 0.92%   |
| 2560x1080          | 42       | 0.82%   |
| 1920x540           | 29       | 0.57%   |
| 1024x768 (XGA)     | 26       | 0.51%   |
| 1600x1200          | 23       | 0.45%   |
| 1280x720 (HD)      | 13       | 0.25%   |
| 1280x960           | 10       | 0.2%    |
| 2560x1600          | 7        | 0.14%   |
| 2048x1152          | 7        | 0.14%   |
| 3840x1080          | 6        | 0.12%   |
| 2288x1287          | 6        | 0.12%   |
| 1280x768           | 5        | 0.1%    |
| 3840x1600          | 3        | 0.06%   |
| 1152x864           | 2        | 0.04%   |
| 3840x1200          | 1        | 0.02%   |
| 2048x1536          | 1        | 0.02%   |
| 1536x2048          | 1        | 0.02%   |
| 1400x1050          | 1        | 0.02%   |
| 1024x600           | 1        | 0.02%   |
| Unknown            | 1        | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 780      | 15.04%  |
| 21      | 735      | 14.17%  |
| 27      | 629      | 12.13%  |
| 24      | 590      | 11.37%  |
| 19      | 449      | 8.66%   |
| 18      | 322      | 6.21%   |
| 17      | 263      | 5.07%   |
| 22      | 257      | 4.95%   |
| 31      | 207      | 3.99%   |
| 20      | 194      | 3.74%   |
| 34      | 84       | 1.62%   |
| 15      | 79       | 1.52%   |
| 84      | 78       | 1.5%    |
| Unknown | 61       | 1.18%   |
| 32      | 60       | 1.16%   |
| 40      | 47       | 0.91%   |
| 72      | 41       | 0.79%   |
| 54      | 37       | 0.71%   |
| 25      | 30       | 0.58%   |
| 26      | 26       | 0.5%    |
| 52      | 22       | 0.42%   |
| 28      | 17       | 0.33%   |
| 65      | 13       | 0.25%   |
| 33      | 12       | 0.23%   |
| 48      | 11       | 0.21%   |
| 46      | 11       | 0.21%   |
| 37      | 11       | 0.21%   |
| 35      | 11       | 0.21%   |
| 29      | 11       | 0.21%   |
| 43      | 10       | 0.19%   |
| 39      | 10       | 0.19%   |
| 42      | 9        | 0.17%   |
| 49      | 7        | 0.13%   |
| 60      | 6        | 0.12%   |
| 47      | 6        | 0.12%   |
| 142     | 5        | 0.1%    |
| 74      | 5        | 0.1%    |
| 55      | 5        | 0.1%    |
| 36      | 5        | 0.1%    |
| 16      | 5        | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 1903     | 37.31%  |
| 401-500        | 1725     | 33.82%  |
| 301-350        | 328      | 6.43%   |
| 601-700        | 300      | 5.88%   |
| 351-400        | 259      | 5.08%   |
| 701-800        | 160      | 3.14%   |
| 1501-2000      | 126      | 2.47%   |
| 1001-1500      | 126      | 2.47%   |
| 801-900        | 80       | 1.57%   |
| Unknown        | 61       | 1.2%    |
| 901-1000       | 21       | 0.41%   |
| 201-300        | 7        | 0.14%   |
| More than 2000 | 5        | 0.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 3581     | 71.29%  |
| 16/10   | 724      | 14.41%  |
| 5/4     | 464      | 9.24%   |
| 21/9    | 94       | 1.87%   |
| 4/3     | 85       | 1.69%   |
| 3/2     | 39       | 0.78%   |
| 6/5     | 12       | 0.24%   |
| 32/9    | 10       | 0.2%    |
| 1.00    | 5        | 0.1%    |
| Unknown | 5        | 0.1%    |
| 3.20    | 1        | 0.02%   |
| 2.01    | 1        | 0.02%   |
| 1.96    | 1        | 0.02%   |
| 0.75    | 1        | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 1929     | 37.61%  |
| 151-200        | 905      | 17.64%  |
| 301-350        | 651      | 12.69%  |
| 141-150        | 506      | 9.87%   |
| 351-500        | 378      | 7.37%   |
| More than 1000 | 232      | 4.52%   |
| 251-300        | 230      | 4.48%   |
| 501-1000       | 130      | 2.53%   |
| Unknown        | 61       | 1.19%   |
| 101-110        | 56       | 1.09%   |
| 111-120        | 21       | 0.41%   |
| 131-140        | 15       | 0.29%   |
| 71-80          | 5        | 0.1%    |
| 91-100         | 4        | 0.08%   |
| 121-130        | 3        | 0.06%   |
| 81-90          | 2        | 0.04%   |
| 41-50          | 1        | 0.02%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 3592     | 71.34%  |
| 101-120 | 974      | 19.34%  |
| 1-50    | 215      | 4.27%   |
| 121-160 | 127      | 2.52%   |
| 161-240 | 66       | 1.31%   |
| Unknown | 61       | 1.21%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 4812     | 90.95%  |
| 2     | 363      | 6.86%   |
| 0     | 83       | 1.57%   |
| 3     | 28       | 0.53%   |
| 4     | 3        | 0.06%   |
| 7     | 1        | 0.02%   |
| 5     | 1        | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 3407     | 49.21%  |
| Intel                           | 1722     | 24.87%  |
| Qualcomm Atheros                | 517      | 7.47%   |
| Ralink Technology               | 184      | 2.66%   |
| Broadcom                        | 166      | 2.4%    |
| Nvidia                          | 156      | 2.25%   |
| Ralink                          | 98       | 1.42%   |
| TP-Link                         | 77       | 1.11%   |
| Marvell Technology Group        | 56       | 0.81%   |
| Qualcomm Atheros Communications | 51       | 0.74%   |
| Broadcom Limited                | 50       | 0.72%   |
| D-Link System                   | 32       | 0.46%   |
| D-Link                          | 28       | 0.4%    |
| VIA Technologies                | 25       | 0.36%   |
| MediaTek                        | 24       | 0.35%   |
| Huawei Technologies             | 24       | 0.35%   |
| NetGear                         | 21       | 0.3%    |
| ASUSTek Computer                | 20       | 0.29%   |
| Samsung Electronics             | 19       | 0.27%   |
| Microsoft                       | 18       | 0.26%   |
| Belkin Components               | 18       | 0.26%   |
| Aquantia                        | 18       | 0.26%   |
| ZTE WCDMA Technologies MSM      | 14       | 0.2%    |
| Motorola PCS                    | 13       | 0.19%   |
| IMC Networks                    | 13       | 0.19%   |
| Edimax Technology               | 12       | 0.17%   |
| ASIX Electronics                | 12       | 0.17%   |
| 3Com                            | 11       | 0.16%   |
| Xiaomi                          | 8        | 0.12%   |
| Linksys                         | 8        | 0.12%   |
| AVM                             | 7        | 0.1%    |
| OPPO Electronics                | 5        | 0.07%   |
| JMicron Technology              | 5        | 0.07%   |
| DisplayLink                     | 5        | 0.07%   |
| Wilocity                        | 4        | 0.06%   |
| Mercucys                        | 4        | 0.06%   |
| ZyDAS                           | 3        | 0.04%   |
| Qualcomm                        | 3        | 0.04%   |
| Mellanox Technologies           | 3        | 0.04%   |
| HTC (High Tech Computer)        | 3        | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2886     | 37.91%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 206      | 2.71%   |
| Intel I211 Gigabit Network Connection                             | 170      | 2.23%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 160      | 2.1%    |
| Intel Wi-Fi 6 AX200                                               | 145      | 1.9%    |
| Realtek RTL8125 2.5GbE Controller                                 | 144      | 1.89%   |
| Intel Ethernet Connection I217-LM                                 | 143      | 1.88%   |
| Intel Ethernet Connection (2) I219-V                              | 142      | 1.87%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 107      | 1.41%   |
| Intel 82579V Gigabit Network Connection                           | 100      | 1.31%   |
| Nvidia MCP61 Ethernet                                             | 94       | 1.23%   |
| Ralink MT7601U Wireless Adapter                                   | 86       | 1.13%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 74       | 0.97%   |
| Intel Ethernet Controller I225-V                                  | 71       | 0.93%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 70       | 0.92%   |
| Intel Ethernet Connection (7) I219-V                              | 69       | 0.91%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 68       | 0.89%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 55       | 0.72%   |
| Intel Wireless-AC 9260                                            | 48       | 0.63%   |
| Intel Ethernet Connection I217-V                                  | 47       | 0.62%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 45       | 0.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 43       | 0.56%   |
| Qualcomm Atheros AR9271 802.11n                                   | 42       | 0.55%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 42       | 0.55%   |
| Intel Ethernet Connection (2) I218-V                              | 38       | 0.5%    |
| Ralink RT5370 Wireless Adapter                                    | 37       | 0.49%   |
| Intel 82574L Gigabit Network Connection                           | 37       | 0.49%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 35       | 0.46%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 33       | 0.43%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 33       | 0.43%   |
| Intel Ethernet Connection (2) I219-LM                             | 33       | 0.43%   |
| Intel Wireless 7260                                               | 32       | 0.42%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 31       | 0.41%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 31       | 0.41%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 31       | 0.41%   |
| Intel Wireless 3165                                               | 30       | 0.39%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 29       | 0.38%   |
| Intel Wireless 7265                                               | 29       | 0.38%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 28       | 0.37%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 27       | 0.35%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 514      | 27.31%  |
| Realtek Semiconductor                 | 465      | 24.71%  |
| Qualcomm Atheros                      | 248      | 13.18%  |
| Ralink Technology                     | 184      | 9.78%   |
| Ralink                                | 98       | 5.21%   |
| TP-Link                               | 74       | 3.93%   |
| Qualcomm Atheros Communications       | 51       | 2.71%   |
| Broadcom                              | 40       | 2.13%   |
| D-Link                                | 28       | 1.49%   |
| ASUSTek Computer                      | 20       | 1.06%   |
| NetGear                               | 19       | 1.01%   |
| Microsoft                             | 18       | 0.96%   |
| Belkin Components                     | 18       | 0.96%   |
| MediaTek                              | 16       | 0.85%   |
| IMC Networks                          | 13       | 0.69%   |
| D-Link System                         | 13       | 0.69%   |
| Edimax Technology                     | 12       | 0.64%   |
| Linksys                               | 8        | 0.43%   |
| AVM                                   | 7        | 0.37%   |
| Broadcom Limited                      | 6        | 0.32%   |
| Wilocity                              | 4        | 0.21%   |
| Mercucys                              | 4        | 0.21%   |
| ZyDAS                                 | 3        | 0.16%   |
| Wacom                                 | 2        | 0.11%   |
| PLANEX                                | 2        | 0.11%   |
| Philips (or NXP)                      | 2        | 0.11%   |
| Guillemot                             | 2        | 0.11%   |
| Chu Yuen Enterprise                   | 2        | 0.11%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2        | 0.11%   |
| ZyXEL Communications                  | 1        | 0.05%   |
| TRENDnet                              | 1        | 0.05%   |
| Sweex                                 | 1        | 0.05%   |
| Sitecom Europe                        | 1        | 0.05%   |
| Logitec                               | 1        | 0.05%   |
| Gemtek                                | 1        | 0.05%   |
| BUFFALO                               | 1        | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 145      | 7.66%   |
| Ralink MT7601U Wireless Adapter                                | 86       | 4.54%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 70       | 3.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 68       | 3.59%   |
| Intel Wireless-AC 9260                                         | 48       | 2.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 45       | 2.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 43       | 2.27%   |
| Qualcomm Atheros AR9271 802.11n                                | 42       | 2.22%   |
| Ralink RT5370 Wireless Adapter                                 | 37       | 1.95%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 35       | 1.85%   |
| Intel Wireless 7260                                            | 32       | 1.69%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 31       | 1.64%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 31       | 1.64%   |
| Intel Wireless 3165                                            | 30       | 1.58%   |
| Intel Wireless 7265                                            | 29       | 1.53%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 28       | 1.48%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 27       | 1.43%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 26       | 1.37%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 25       | 1.32%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 25       | 1.32%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 25       | 1.32%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 24       | 1.27%   |
| Realtek 802.11ac NIC                                           | 23       | 1.22%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 21       | 1.11%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 20       | 1.06%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 20       | 1.06%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 20       | 1.06%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 20       | 1.06%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 20       | 1.06%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 20       | 1.06%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 19       | 1%      |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 19       | 1%      |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 19       | 1%      |
| Intel Wireless 8260                                            | 17       | 0.9%    |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 14       | 0.74%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 13       | 0.69%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 13       | 0.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 13       | 0.69%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 13       | 0.69%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 13       | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 3266     | 58.72%  |
| Intel                             | 1407     | 25.3%   |
| Qualcomm Atheros                  | 290      | 5.21%   |
| Nvidia                            | 156      | 2.8%    |
| Broadcom                          | 126      | 2.27%   |
| Marvell Technology Group          | 56       | 1.01%   |
| Broadcom Limited                  | 44       | 0.79%   |
| VIA Technologies                  | 23       | 0.41%   |
| Huawei Technologies               | 23       | 0.41%   |
| Samsung Electronics               | 19       | 0.34%   |
| D-Link System                     | 19       | 0.34%   |
| Aquantia                          | 18       | 0.32%   |
| ZTE WCDMA Technologies MSM        | 13       | 0.23%   |
| ASIX Electronics                  | 12       | 0.22%   |
| 3Com                              | 11       | 0.2%    |
| Xiaomi                            | 8        | 0.14%   |
| MediaTek                          | 8        | 0.14%   |
| Motorola PCS                      | 7        | 0.13%   |
| OPPO Electronics                  | 5        | 0.09%   |
| JMicron Technology                | 5        | 0.09%   |
| DisplayLink                       | 5        | 0.09%   |
| TP-Link                           | 4        | 0.07%   |
| Qualcomm                          | 3        | 0.05%   |
| Mellanox Technologies             | 3        | 0.05%   |
| HTC (High Tech Computer)          | 3        | 0.05%   |
| T & A Mobile Phones               | 2        | 0.04%   |
| Sundance Technology Inc / IC Plus | 2        | 0.04%   |
| Spreadtrum Communications         | 2        | 0.04%   |
| Silicon Integrated Systems [SiS]  | 2        | 0.04%   |
| OnePlus Technology (Shenzhen)     | 2        | 0.04%   |
| NetGear                           | 2        | 0.04%   |
| LG Electronics                    | 2        | 0.04%   |
| ICS Advent                        | 2        | 0.04%   |
| HMD Global                        | 2        | 0.04%   |
| SysKonnect                        | 1        | 0.02%   |
| Netchip Technology                | 1        | 0.02%   |
| Lenovo                            | 1        | 0.02%   |
| IBM                               | 1        | 0.02%   |
| Foxconn / Hon Hai                 | 1        | 0.02%   |
| Emulex                            | 1        | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2886     | 50.68%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 206      | 3.62%   |
| Intel I211 Gigabit Network Connection                             | 170      | 2.99%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 160      | 2.81%   |
| Realtek RTL8125 2.5GbE Controller                                 | 144      | 2.53%   |
| Intel Ethernet Connection I217-LM                                 | 143      | 2.51%   |
| Intel Ethernet Connection (2) I219-V                              | 142      | 2.49%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 107      | 1.88%   |
| Intel 82579V Gigabit Network Connection                           | 100      | 1.76%   |
| Nvidia MCP61 Ethernet                                             | 94       | 1.65%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 74       | 1.3%    |
| Intel Ethernet Controller I225-V                                  | 71       | 1.25%   |
| Intel Ethernet Connection (7) I219-V                              | 69       | 1.21%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 55       | 0.97%   |
| Intel Ethernet Connection I217-V                                  | 47       | 0.83%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 42       | 0.74%   |
| Intel Ethernet Connection (2) I218-V                              | 38       | 0.67%   |
| Intel 82574L Gigabit Network Connection                           | 37       | 0.65%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 33       | 0.58%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 33       | 0.58%   |
| Intel Ethernet Connection (2) I219-LM                             | 33       | 0.58%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 31       | 0.54%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 29       | 0.51%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 25       | 0.44%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 24       | 0.42%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 24       | 0.42%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 23       | 0.4%    |
| Intel 82578DM Gigabit Network Connection                          | 23       | 0.4%    |
| Intel 82578DC Gigabit Network Connection                          | 21       | 0.37%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 20       | 0.35%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 19       | 0.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 19       | 0.33%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 19       | 0.33%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 17       | 0.3%    |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 17       | 0.3%    |
| Intel Ethernet Connection (14) I219-V                             | 16       | 0.28%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 15       | 0.26%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 15       | 0.26%   |
| Intel Ethernet Connection (11) I219-V                             | 15       | 0.26%   |
| Nvidia MCP77 Ethernet                                             | 13       | 0.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 5238     | 73.98%  |
| WiFi     | 1817     | 25.66%  |
| Modem    | 13       | 0.18%   |
| Unknown  | 12       | 0.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 4455     | 85.56%  |
| WiFi     | 752      | 14.44%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 3794     | 71.69%  |
| 2     | 1325     | 25.04%  |
| 3     | 116      | 2.19%   |
| 0     | 39       | 0.74%   |
| 4     | 15       | 0.28%   |
| 7     | 1        | 0.02%   |
| 6     | 1        | 0.02%   |
| 5     | 1        | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Desktops | Percent |
|---------|----------|---------|
| No      | 3903     | 73.71%  |
| Yes     | 1391     | 26.27%  |
| Unknown | 1        | 0.02%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 467      | 39.21%  |
| Cambridge Silicon Radio         | 343      | 28.8%   |
| Realtek Semiconductor           | 94       | 7.89%   |
| ASUSTek Computer                | 79       | 6.63%   |
| Broadcom                        | 59       | 4.95%   |
| Qualcomm Atheros Communications | 43       | 3.61%   |
| IMC Networks                    | 30       | 2.52%   |
| Lite-On Technology              | 11       | 0.92%   |
| MediaTek                        | 10       | 0.84%   |
| Integrated System Solution      | 9        | 0.76%   |
| TP-Link                         | 7        | 0.59%   |
| Belkin Components               | 7        | 0.59%   |
| Apple                           | 7        | 0.59%   |
| Ralink                          | 4        | 0.34%   |
| Primax Electronics              | 3        | 0.25%   |
| Dynex                           | 3        | 0.25%   |
| Unknown                         | 2        | 0.17%   |
| Realtek                         | 2        | 0.17%   |
| Hewlett-Packard                 | 2        | 0.17%   |
| Foxconn / Hon Hai               | 2        | 0.17%   |
| Unknown                         | 2        | 0.17%   |
| SIN                             | 1        | 0.08%   |
| Micro Star International        | 1        | 0.08%   |
| i.Tech Dynamic Limited          | 1        | 0.08%   |
| Edimax Technology               | 1        | 0.08%   |
| Dell                            | 1        | 0.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 343      | 28.78%  |
| Intel AX200 Bluetooth                                    | 135      | 11.33%  |
| Intel Bluetooth wireless interface                       | 122      | 10.23%  |
| Intel Wireless-AC 3168 Bluetooth                         | 66       | 5.54%   |
| Realtek Bluetooth Radio                                  | 60       | 5.03%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 42       | 3.52%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 37       | 3.1%    |
| Intel Bluetooth Device                                   | 33       | 2.77%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 32       | 2.68%   |
| Realtek  Bluetooth 4.2 Adapter                           | 29       | 2.43%   |
| Intel AX210 Bluetooth                                    | 24       | 2.01%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 24       | 2.01%   |
| IMC Networks Bluetooth Radio                             | 23       | 1.93%   |
| Qualcomm Atheros  Bluetooth Device                       | 18       | 1.51%   |
| ASUS Bluetooth Radio                                     | 14       | 1.17%   |
| MediaTek Wireless_Device                                 | 10       | 0.84%   |
| ASUS ASUS USB-BT500                                      | 10       | 0.84%   |
| Lite-On Bluetooth Device                                 | 9        | 0.76%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 9        | 0.76%   |
| Qualcomm Atheros AR3011 Bluetooth                        | 8        | 0.67%   |
| ASUS Qualcomm Bluetooth 4.1                              | 8        | 0.67%   |
| TP-Link TPuLink UB500 Adapter                            | 7        | 0.59%   |
| Qualcomm Atheros AR9462 Bluetooth                        | 7        | 0.59%   |
| ASUS Bluetooth Device                                    | 7        | 0.59%   |
| ASUS Bluetooth Adapter                                   | 7        | 0.59%   |
| Integrated System Solution Bluetooth Device              | 6        | 0.5%    |
| Broadcom BCM2045 Bluetooth                               | 5        | 0.42%   |
| Belkin Components Bluetooth Mini Dongle                  | 5        | 0.42%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE    | 5        | 0.42%   |
| Ralink RT3290 Bluetooth                                  | 4        | 0.34%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                   | 4        | 0.34%   |
| Qualcomm Atheros Bluetooth USB Host Controller           | 4        | 0.34%   |
| ASUS BCM20702A0                                          | 4        | 0.34%   |
| Primax Rocketfish RF-FLBTAD Bluetooth Adapter            | 3        | 0.25%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter    | 3        | 0.25%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 3        | 0.25%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter         | 3        | 0.25%   |
| Broadcom BCM2035 Bluetooth dongle                        | 3        | 0.25%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                     | 3        | 0.25%   |
| Apple Bluetooth USB Host Controller                      | 3        | 0.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 3283     | 40.64%  |
| AMD                                             | 2181     | 27%     |
| Nvidia                                          | 1820     | 22.53%  |
| C-Media Electronics                             | 183      | 2.27%   |
| Creative Labs                                   | 144      | 1.78%   |
| Logitech                                        | 54       | 0.67%   |
| Texas Instruments                               | 38       | 0.47%   |
| JMTek                                           | 27       | 0.33%   |
| VIA Technologies                                | 25       | 0.31%   |
| Creative Technology                             | 24       | 0.3%    |
| Generalplus Technology                          | 22       | 0.27%   |
| ASUSTek Computer                                | 20       | 0.25%   |
| Razer USA                                       | 13       | 0.16%   |
| GN Netcom                                       | 11       | 0.14%   |
| Tenx Technology                                 | 10       | 0.12%   |
| Kingston Technology                             | 9        | 0.11%   |
| Giga-Byte Technology                            | 8        | 0.1%    |
| XMOS                                            | 7        | 0.09%   |
| KTMicro                                         | 7        | 0.09%   |
| Focusrite-Novation                              | 7        | 0.09%   |
| Plantronics                                     | 6        | 0.07%   |
| Blue Microphones                                | 6        | 0.07%   |
| Yamaha                                          | 5        | 0.06%   |
| Thesycon Systemsoftware & Consulting            | 5        | 0.06%   |
| SteelSeries ApS                                 | 5        | 0.06%   |
| Sony                                            | 5        | 0.06%   |
| SAVITECH                                        | 5        | 0.06%   |
| M-Audio                                         | 5        | 0.06%   |
| GYROCOM C&C                                     | 5        | 0.06%   |
| Ensoniq                                         | 5        | 0.06%   |
| BEHRINGER International                         | 5        | 0.06%   |
| Trust                                           | 4        | 0.05%   |
| Samson Technologies                             | 4        | 0.05%   |
| PreSonus Audio Electronics                      | 4        | 0.05%   |
| Hewlett-Packard                                 | 4        | 0.05%   |
| Dell                                            | 4        | 0.05%   |
| ROCCAT                                          | 3        | 0.04%   |
| Realtek Semiconductor                           | 3        | 0.04%   |
| Micro Star International                        | 3        | 0.04%   |
| Licensed by Sony Computer Entertainment America | 3        | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                                      | 484      | 5.08%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 471      | 4.95%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 463      | 4.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 340      | 3.57%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 340      | 3.57%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 331      | 3.48%   |
| AMD Starship/Matisse HD Audio Controller                                          | 305      | 3.2%    |
| AMD FCH Azalia Controller                                                         | 296      | 3.11%   |
| AMD Family 17h/19h HD Audio Controller                                            | 294      | 3.09%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 246      | 2.58%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 228      | 2.39%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 224      | 2.35%   |
| Intel 200 Series PCH HD Audio                                                     | 196      | 2.06%   |
| Nvidia High Definition Audio Controller                                           | 187      | 1.96%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 168      | 1.76%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 162      | 1.7%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 162      | 1.7%    |
| Intel Cannon Lake PCH cAVS                                                        | 156      | 1.64%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 148      | 1.55%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 138      | 1.45%   |
| Nvidia GF108 High Definition Audio Controller                                     | 129      | 1.35%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 118      | 1.24%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 117      | 1.23%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 109      | 1.14%   |
| Nvidia GF119 HDMI Audio Controller                                                | 103      | 1.08%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 103      | 1.08%   |
| Nvidia MCP61 High Definition Audio                                                | 102      | 1.07%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 97       | 1.02%   |
| Nvidia GP108 High Definition Audio Controller                                     | 85       | 0.89%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 85       | 0.89%   |
| Nvidia GP106 High Definition Audio Controller                                     | 82       | 0.86%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 82       | 0.86%   |
| Nvidia TU116 High Definition Audio Controller                                     | 81       | 0.85%   |
| Nvidia GK107 HDMI Audio Controller                                                | 79       | 0.83%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 72       | 0.76%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 71       | 0.75%   |
| AMD Navi 10 HDMI Audio                                                            | 69       | 0.72%   |
| AMD Trinity HDMI Audio Controller                                                 | 68       | 0.71%   |
| Intel Audio device                                                                | 66       | 0.69%   |
| AMD Kabini HDMI/DP Audio                                                          | 66       | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 1217     | 19.7%   |
| Kingston            | 1114     | 18.03%  |
| Samsung Electronics | 631      | 10.21%  |
| Corsair             | 497      | 8.04%   |
| SK hynix            | 488      | 7.9%    |
| Crucial             | 440      | 7.12%   |
| G.Skill             | 370      | 5.99%   |
| Micron Technology   | 309      | 5%      |
| A-DATA Technology   | 134      | 2.17%   |
| Nanya Technology    | 89       | 1.44%   |
| Patriot             | 77       | 1.25%   |
| Team                | 69       | 1.12%   |
| Unknown             | 68       | 1.1%    |
| Ramaxel Technology  | 58       | 0.94%   |
| GOODRAM             | 55       | 0.89%   |
| Elpida              | 54       | 0.87%   |
| Transcend           | 34       | 0.55%   |
| Smart               | 32       | 0.52%   |
| AMD                 | 28       | 0.45%   |
| Apacer              | 26       | 0.42%   |
| Kingmax             | 23       | 0.37%   |
| GeIL                | 20       | 0.32%   |
| Unifosa             | 18       | 0.29%   |
| Unknown (ABCD)      | 17       | 0.28%   |
| Silicon Power       | 17       | 0.28%   |
| Qimonda             | 14       | 0.23%   |
| PNY                 | 11       | 0.18%   |
| Multilaser          | 9        | 0.15%   |
| Teikon              | 8        | 0.13%   |
| Avant               | 8        | 0.13%   |
| OCZ                 | 6        | 0.1%    |
| KLEVV               | 6        | 0.1%    |
| Goldkey             | 6        | 0.1%    |
| CSX                 | 6        | 0.1%    |
| Atermiter           | 6        | 0.1%    |
| Toshiba             | 5        | 0.08%   |
| Timetec             | 5        | 0.08%   |
| TakeMS              | 5        | 0.08%   |
| Super Talent        | 5        | 0.08%   |
| Ramos Technology    | 5        | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM 800MT/s                    | 87       | 1.27%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s               | 82       | 1.2%    |
| Unknown RAM Module 2GB DIMM SDRAM                      | 78       | 1.14%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 77       | 1.13%   |
| Unknown                                                | 68       | 0.99%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s              | 55       | 0.8%    |
| Unknown RAM Module 2GB DIMM 1333MT/s                   | 53       | 0.78%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s  | 48       | 0.7%    |
| Unknown RAM Module 4GB DIMM 1600MT/s                   | 42       | 0.61%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s    | 41       | 0.6%    |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3             | 40       | 0.59%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s               | 39       | 0.57%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s    | 38       | 0.56%   |
| Unknown RAM Module 1GB DIMM SDRAM                      | 37       | 0.54%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s    | 37       | 0.54%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s              | 36       | 0.53%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s   | 36       | 0.53%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s    | 36       | 0.53%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s    | 34       | 0.5%    |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s               | 33       | 0.48%   |
| Unknown RAM Module 2GB DIMM 400MT/s                    | 32       | 0.47%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s      | 32       | 0.47%   |
| Unknown RAM Module 1GB DIMM 800MT/s                    | 29       | 0.42%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s    | 29       | 0.42%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                   | 27       | 0.39%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s              | 27       | 0.39%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s   | 27       | 0.39%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s    | 27       | 0.39%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s    | 27       | 0.39%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s               | 26       | 0.38%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s              | 25       | 0.37%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s      | 25       | 0.37%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s  | 25       | 0.37%   |
| Unknown RAM Module 4GB DIMM SDRAM                      | 24       | 0.35%   |
| Unknown RAM Module 1GB DIMM 667MT/s                    | 24       | 0.35%   |
| Kingston RAM KHX1866C10D3/8G 8192MB DIMM DDR3 2133MT/s | 24       | 0.35%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s    | 23       | 0.34%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s    | 23       | 0.34%   |
| Unknown RAM Module 4GB DIMM 400MT/s                    | 22       | 0.32%   |
| Unknown RAM Module 2GB DIMM 667MT/s                    | 22       | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 2191     | 40.79%  |
| DDR4    | 1768     | 32.91%  |
| Unknown | 513      | 9.55%   |
| DDR2    | 424      | 7.89%   |
| SDRAM   | 361      | 6.72%   |
| DDR     | 80       | 1.49%   |
| LPDDR4  | 20       | 0.37%   |
| DDR5    | 11       | 0.2%    |
| LPDDR3  | 2        | 0.04%   |
| DRAM    | 2        | 0.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 4937     | 94.33%  |
| SODIMM       | 285      | 5.45%   |
| FB-DIMM      | 6        | 0.11%   |
| RIMM         | 5        | 0.1%    |
| Row Of Chips | 1        | 0.02%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 1850     | 31.24%  |
| 4096  | 1843     | 31.12%  |
| 2048  | 1246     | 21.04%  |
| 16384 | 448      | 7.57%   |
| 1024  | 394      | 6.65%   |
| 32768 | 84       | 1.42%   |
| 512   | 52       | 0.88%   |
| 256   | 2        | 0.03%   |
| 3072  | 1        | 0.02%   |
| 64    | 1        | 0.02%   |
| 32    | 1        | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 1291     | 21.52%  |
| 1333    | 947      | 15.78%  |
| 800     | 372      | 6.2%    |
| 2400    | 323      | 5.38%   |
| 3200    | 316      | 5.27%   |
| 2667    | 264      | 4.4%    |
| 3600    | 256      | 4.27%   |
| 2133    | 248      | 4.13%   |
| 667     | 245      | 4.08%   |
| Unknown | 198      | 3.3%    |
| 1867    | 140      | 2.33%   |
| 1866    | 108      | 1.8%    |
| 2666    | 98       | 1.63%   |
| 3400    | 91       | 1.52%   |
| 1066    | 86       | 1.43%   |
| 3000    | 76       | 1.27%   |
| 400     | 74       | 1.23%   |
| 2933    | 69       | 1.15%   |
| 1800    | 67       | 1.12%   |
| 1067    | 59       | 0.98%   |
| 533     | 55       | 0.92%   |
| 3466    | 52       | 0.87%   |
| 3866    | 37       | 0.62%   |
| 2800    | 34       | 0.57%   |
| 3733    | 33       | 0.55%   |
| 1334    | 33       | 0.55%   |
| 2048    | 30       | 0.5%    |
| 3800    | 25       | 0.42%   |
| 2000    | 24       | 0.4%    |
| 333     | 21       | 0.35%   |
| 49926   | 20       | 0.33%   |
| 3066    | 18       | 0.3%    |
| 1648    | 18       | 0.3%    |
| 1639    | 15       | 0.25%   |
| 3666    | 14       | 0.23%   |
| 2200    | 13       | 0.22%   |
| 3500    | 12       | 0.2%    |
| 3334    | 12       | 0.2%    |
| 2733    | 12       | 0.2%    |
| 3266    | 11       | 0.18%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 135      | 40.42%  |
| Brother Industries    | 71       | 21.26%  |
| Canon                 | 43       | 12.87%  |
| Samsung Electronics   | 30       | 8.98%   |
| Seiko Epson           | 26       | 7.78%   |
| Lexmark International | 6        | 1.8%    |
| QinHeng Electronics   | 5        | 1.5%    |
| Prolific Technology   | 5        | 1.5%    |
| Kyocera               | 3        | 0.9%    |
| Dymo-CoStar           | 3        | 0.9%    |
| Xerox                 | 2        | 0.6%    |
| Ricoh                 | 2        | 0.6%    |
| Oki Data              | 1        | 0.3%    |
| NXP Semiconductors    | 1        | 0.3%    |
| Citizen               | 1        | 0.3%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| HP DeskJet 2600 series               | 6        | 1.78%   |
| Samsung M2020 Series                 | 5        | 1.48%   |
| QinHeng CH340S                       | 5        | 1.48%   |
| Prolific PL2305 Parallel Port        | 5        | 1.48%   |
| HP ENVY 4520 series                  | 5        | 1.48%   |
| HP DeskJet 3630 series               | 5        | 1.48%   |
| HP DeskJet 2700 series               | 5        | 1.48%   |
| Samsung ML-1640 Series Laser Printer | 4        | 1.19%   |
| HP LaserJet P1006                    | 4        | 1.19%   |
| HP Ink Tank Wireless 410 series      | 4        | 1.19%   |
| Canon PIXMA MX920 Series             | 4        | 1.19%   |
| Brother Printer                      | 4        | 1.19%   |
| Samsung M2070 Series                 | 3        | 0.89%   |
| HP LaserJet Pro M148f-M149f          | 3        | 0.89%   |
| HP LaserJet P1005                    | 3        | 0.89%   |
| HP LaserJet 1020                     | 3        | 0.89%   |
| HP LaserJet 1018                     | 3        | 0.89%   |
| HP LaserJet 1010                     | 3        | 0.89%   |
| HP DeskJet 2130 series               | 3        | 0.89%   |
| HP Deskjet 1050 J410                 | 3        | 0.89%   |
| Canon PIXMA MG3600 Series            | 3        | 0.89%   |
| Brother MFC-L2710DW series           | 3        | 0.89%   |
| Brother MFC-J470DW                   | 3        | 0.89%   |
| Brother HL-L2390DW                   | 3        | 0.89%   |
| Brother HL-L2360D series             | 3        | 0.89%   |
| Seiko Epson XP-243 245 247 Series    | 2        | 0.59%   |
| Seiko Epson L365 Series              | 2        | 0.59%   |
| Seiko Epson L120 Series              | 2        | 0.59%   |
| Seiko Epson ET-4760 Series           | 2        | 0.59%   |
| Samsung SCX-3400 Series              | 2        | 0.59%   |
| Samsung ML-2010P Mono Laser Printer  | 2        | 0.59%   |
| Samsung CLP-310 Color Laser Printer  | 2        | 0.59%   |
| HP OfficeJet Pro 7720 series         | 2        | 0.59%   |
| HP OfficeJet Pro 6960                | 2        | 0.59%   |
| HP OfficeJet 6950                    | 2        | 0.59%   |
| HP Officejet 6600                    | 2        | 0.59%   |
| HP LaserJet P1102                    | 2        | 0.59%   |
| HP LaserJet M14-M17                  | 2        | 0.59%   |
| HP LaserJet 1200                     | 2        | 0.59%   |
| HP LaserJet 1022                     | 2        | 0.59%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Canon                       | 38       | 54.29%  |
| Hewlett-Packard             | 11       | 15.71%  |
| Seiko Epson                 | 9        | 12.86%  |
| Mustek Systems              | 7        | 10%     |
| AGFA-Gevaert NV             | 3        | 4.29%   |
| Plustek                     | 1        | 1.43%   |
| KYE Systems (Mouse Systems) | 1        | 1.43%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 210                                  | 6        | 8.57%   |
| Canon CanoScan LiDE 100                                  | 6        | 8.57%   |
| Canon CanoScan LiDE 110                                  | 5        | 7.14%   |
| Canon CanoScan LiDE 120                                  | 4        | 5.71%   |
| Mustek Systems ScanExpress 1200 UB                       | 3        | 4.29%   |
| Canon CanoScan LIDE 25                                   | 3        | 4.29%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]            | 2        | 2.86%   |
| HP ScanJet 4500C/5550C                                   | 2        | 2.86%   |
| Canon CanoScan N670U/N676U/LiDE 20                       | 2        | 2.86%   |
| Canon CanoScan N1240U/LiDE 30                            | 2        | 2.86%   |
| Canon CanoScan LiDE 220                                  | 2        | 2.86%   |
| Canon CanoScan LiDE 200                                  | 2        | 2.86%   |
| AGFA-Gevaert NV SnapScan e20                             | 2        | 2.86%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]              | 1        | 1.43%   |
| Seiko Epson GT-X770 [Perfection V500]                    | 1        | 1.43%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]  | 1        | 1.43%   |
| Seiko Epson GT-F700 [Perfection V350]                    | 1        | 1.43%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]        | 1        | 1.43%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1        | 1.43%   |
| Seiko Epson GT-7400U [Perfection 1270]                   | 1        | 1.43%   |
| Plustek 600DPI USB Scanner                               | 1        | 1.43%   |
| Mustek Systems SNAPSCAN e22                              | 1        | 1.43%   |
| Mustek Systems ScanExpress 1200 CU                       | 1        | 1.43%   |
| Mustek Systems BearPaw 2448 CU Pro                       | 1        | 1.43%   |
| Mustek Systems BearPaw 1200 CU Plus                      | 1        | 1.43%   |
| KYE Systems (Mouse Systems) ColorPage-Vivid4             | 1        | 1.43%   |
| HP ScanJet G4010                                         | 1        | 1.43%   |
| HP ScanJet 4570c                                         | 1        | 1.43%   |
| HP ScanJet 4370                                          | 1        | 1.43%   |
| HP ScanJet 3800c                                         | 1        | 1.43%   |
| HP ScanJet 3670                                          | 1        | 1.43%   |
| HP ScanJet 2400c                                         | 1        | 1.43%   |
| HP ScanJet 2300c                                         | 1        | 1.43%   |
| HP ScanJet 2200c                                         | 1        | 1.43%   |
| HP PSC 1200                                              | 1        | 1.43%   |
| Canon CanoScan N650U/N656U                               | 1        | 1.43%   |
| Canon CanoScan LiDE 700F                                 | 1        | 1.43%   |
| Canon CanoScan LiDE 70                                   | 1        | 1.43%   |
| Canon CanoScan LiDE 60                                   | 1        | 1.43%   |
| Canon CanoScan LiDE 500F                                 | 1        | 1.43%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 275      | 38.09%  |
| Microdia                               | 61       | 8.45%   |
| Microsoft                              | 49       | 6.79%   |
| Z-Star Microelectronics                | 26       | 3.6%    |
| Chicony Electronics                    | 22       | 3.05%   |
| GEMBIRD                                | 17       | 2.35%   |
| Realtek Semiconductor                  | 16       | 2.22%   |
| Generalplus Technology                 | 15       | 2.08%   |
| Aveo Technology                        | 15       | 2.08%   |
| Sunplus Innovation Technology          | 14       | 1.94%   |
| Samsung Electronics                    | 14       | 1.94%   |
| KYE Systems (Mouse Systems)            | 14       | 1.94%   |
| Creative Technology                    | 13       | 1.8%    |
| Cubeternet                             | 11       | 1.52%   |
| ARC International                      | 11       | 1.52%   |
| Apple                                  | 10       | 1.39%   |
| Jieli Technology                       | 9        | 1.25%   |
| Huawei Technologies                    | 9        | 1.25%   |
| Hewlett-Packard                        | 9        | 1.25%   |
| Trust                                  | 7        | 0.97%   |
| Arkmicro Technologies                  | 6        | 0.83%   |
| Unknown                                | 5        | 0.69%   |
| Pixart Imaging                         | 5        | 0.69%   |
| MacroSilicon                           | 5        | 0.69%   |
| Genesys Logic                          | 5        | 0.69%   |
| IMC Networks                           | 4        | 0.55%   |
| Alcor Micro                            | 4        | 0.55%   |
| A4Tech                                 | 4        | 0.55%   |
| WCM_USB                                | 3        | 0.42%   |
| WaveRider Communications               | 3        | 0.42%   |
| Sonix Technology                       | 3        | 0.42%   |
| Silicon Motion                         | 3        | 0.42%   |
| Razer USA                              | 3        | 0.42%   |
| Guillemot                              | 3        | 0.42%   |
| Cheng Uei Precision Industry (Foxlink) | 3        | 0.42%   |
| AVerMedia Technologies                 | 3        | 0.42%   |
| 2M UVC CAMERA                          | 3        | 0.42%   |
| Teslong Camera                         | 2        | 0.28%   |
| Sweex                                  | 2        | 0.28%   |
| SunplusIT                              | 2        | 0.28%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 67       | 9.25%   |
| Logitech HD Pro Webcam C920                       | 35       | 4.83%   |
| Logitech Webcam C310                              | 29       | 4.01%   |
| Logitech HD Webcam C525                           | 21       | 2.9%    |
| Microsoft LifeCam HD-3000                         | 19       | 2.62%   |
| Logitech Webcam C170                              | 17       | 2.35%   |
| Microdia USB 2.0 Camera                           | 16       | 2.21%   |
| Microdia Camera                                   | 16       | 2.21%   |
| Samsung Galaxy A5 (MTP)                           | 14       | 1.93%   |
| Generalplus GENERAL WEBCAM                        | 13       | 1.8%    |
| Microdia Webcam Vitade AF                         | 11       | 1.52%   |
| Logitech QuickCam Pro 9000                        | 11       | 1.52%   |
| Aveo USB2.0 Camera                                | 11       | 1.52%   |
| ARC International Camera                          | 11       | 1.52%   |
| Logitech HD Webcam C615                           | 10       | 1.38%   |
| Apple iPhone 5/5C/5S/6/SE                         | 10       | 1.38%   |
| Jieli USB PHY 2.0                                 | 9        | 1.24%   |
| Huawei UVC Camera                                 | 9        | 1.24%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 9        | 1.24%   |
| Z-Star Vimicro USB Camera (Altair)                | 8        | 1.1%    |
| GEMBIRD USB2.0 PC CAMERA                          | 8        | 1.1%    |
| Microdia Sonix USB 2.0 Camera                     | 7        | 0.97%   |
| Logitech HD Webcam C910                           | 7        | 0.97%   |
| Logitech C922 Pro Stream Webcam                   | 7        | 0.97%   |
| Cubeternet USB2.0 Camera                          | 7        | 0.97%   |
| Z-Star Venus USB2.0 Camera                        | 6        | 0.83%   |
| Microsoft LifeCam Cinema                          | 6        | 0.83%   |
| Microdia Laptop_Integrated_Webcam_FHD             | 6        | 0.83%   |
| Logitech Webcam C250                              | 6        | 0.83%   |
| Z-Star A4 TECH USB2.0 PC Camera J                 | 5        | 0.69%   |
| Realtek Full HD webcam                            | 5        | 0.69%   |
| Microsoft LifeCam VX-5000                         | 5        | 0.69%   |
| MacroSilicon USB Video                            | 5        | 0.69%   |
| Logitech Webcam Pro 9000                          | 5        | 0.69%   |
| Logitech Webcam C930e                             | 5        | 0.69%   |
| Logitech Webcam C300                              | 5        | 0.69%   |
| Logitech HD Webcam C510                           | 5        | 0.69%   |
| KYE Systems (Mouse Systems) iSlim 321R            | 5        | 0.69%   |
| HP Webcam HD 2300                                 | 5        | 0.69%   |
| Creative Live! Cam Sync HD [VF0770]               | 5        | 0.69%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| AuthenTec             | 3        | 37.5%   |
| Upek                  | 2        | 25%     |
| Validity Sensors      | 1        | 12.5%   |
| LighTuning Technology | 1        | 12.5%   |
| DigitalPersona        | 1        | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2        | 25%     |
| AuthenTec AES1600                                      | 2        | 25%     |
| Validity Sensors VFS 5011 fingerprint sensor           | 1        | 12.5%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1        | 12.5%   |
| DigitalPersona Fingerprint Reader                      | 1        | 12.5%   |
| AuthenTec Fingerprint Sensor                           | 1        | 12.5%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Alcor Micro                       | 5        | 19.23%  |
| SCM Microsystems                  | 4        | 15.38%  |
| Realtek Semiconductor             | 3        | 11.54%  |
| Gemalto (was Gemplus)             | 3        | 11.54%  |
| Reiner SCT Kartensysteme          | 2        | 7.69%   |
| OmniKey                           | 2        | 7.69%   |
| BIT4ID                            | 2        | 7.69%   |
| Advanced Card Systems             | 2        | 7.69%   |
| VASCO Data Security International | 1        | 3.85%   |
| Fujitsu Siemens Computers         | 1        | 3.85%   |
| Cherry                            | 1        | 3.85%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface                          | 3        | 11.54%  |
| Alcor Micro AU9540 Smartcard Reader                                        | 3        | 11.54%  |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 2        | 7.69%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                          | 2        | 7.69%   |
| BIT4ID miniLector EVO                                                      | 2        | 7.69%   |
| Alcor Micro Watchdata W 1981                                               | 2        | 7.69%   |
| Advanced Card Systems ACR38 SmartCard Reader                               | 2        | 7.69%   |
| VASCO Data Security International Digipass 905 SmartCard Reader            | 1        | 3.85%   |
| SCM Microsystems uTrust 3700 F CL Reader                                   | 1        | 3.85%   |
| SCM Microsystems SCR335 SmartCard Reader                                   | 1        | 3.85%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                     | 1        | 3.85%   |
| SCM Microsystems CLOUD 2700 F Smart Card Reader                            | 1        | 3.85%   |
| OmniKey CardMan 3021 / 3121                                                | 1        | 3.85%   |
| OmniKey CardMan 1021                                                       | 1        | 3.85%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                           | 1        | 3.85%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                              | 1        | 3.85%   |
| Cherry Smart Terminal XX44                                                 | 1        | 3.85%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 4823     | 91.15%  |
| 1     | 431      | 8.15%   |
| 2     | 31       | 0.59%   |
| 3     | 3        | 0.06%   |
| 7     | 1        | 0.02%   |
| 6     | 1        | 0.02%   |
| 4     | 1        | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 210      | 42.08%  |
| Net/wireless             | 112      | 22.44%  |
| Unassigned class         | 33       | 6.61%   |
| Communication controller | 31       | 6.21%   |
| Multimedia controller    | 29       | 5.81%   |
| Chipcard                 | 24       | 4.81%   |
| Camera                   | 12       | 2.4%    |
| Bluetooth                | 12       | 2.4%    |
| Fingerprint reader       | 8        | 1.6%    |
| Network                  | 6        | 1.2%    |
| Card reader              | 5        | 1%      |
| Sound                    | 4        | 0.8%    |
| Wireless                 | 3        | 0.6%    |
| Net/ethernet             | 3        | 0.6%    |
| Modem                    | 3        | 0.6%    |
| Storage/ata              | 2        | 0.4%    |
| Unclassified device      | 1        | 0.2%    |
| Storage/raid             | 1        | 0.2%    |

