Zorin 16 - Tested Hardware & Statistics (Desktops)
--------------------------------------------------

A project to collect tested hardware configurations for Zorin 16.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=zorin-16

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

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock   | B450 Pro4                   | [042032eec7](https://linux-hardware.org/?probe=042032eec7) | Sep 16, 2021 |
| Intel    | X99                         | [814b3326d1](https://linux-hardware.org/?probe=814b3326d1) | Sep 15, 2021 |
| NCR      | Talladega                   | [95445fa221](https://linux-hardware.org/?probe=95445fa221) | Sep 14, 2021 |
| MSI      | B75MA-P45                   | [93a071ca7e](https://linux-hardware.org/?probe=93a071ca7e) | Sep 14, 2021 |
| Foxconn  | 17A0                        | [06052023d3](https://linux-hardware.org/?probe=06052023d3) | Sep 14, 2021 |
| MSI      | B75MA-P45                   | [874dcada55](https://linux-hardware.org/?probe=874dcada55) | Sep 14, 2021 |
| ASUSTek  | M5A97 LE R2.0               | [b3b1991c64](https://linux-hardware.org/?probe=b3b1991c64) | Sep 14, 2021 |
| ASUSTek  | NARRA3                      | [93db4618cc](https://linux-hardware.org/?probe=93db4618cc) | Sep 14, 2021 |
| ASUSTek  | Benicia                     | [2a764dd662](https://linux-hardware.org/?probe=2a764dd662) | Sep 13, 2021 |
| ASUSTek  | Maximus VIII RANGER         | [6928772253](https://linux-hardware.org/?probe=6928772253) | Sep 12, 2021 |
| ASUSTek  | Maximus VIII RANGER         | [93a0d7ac6a](https://linux-hardware.org/?probe=93a0d7ac6a) | Sep 12, 2021 |
| HP       | 339A                        | [9284a70a92](https://linux-hardware.org/?probe=9284a70a92) | Sep 12, 2021 |
| ASUSTek  | P5Q                         | [8693b86435](https://linux-hardware.org/?probe=8693b86435) | Sep 12, 2021 |
| NCR      | Talladega                   | [6de6d8c2a3](https://linux-hardware.org/?probe=6de6d8c2a3) | Sep 12, 2021 |
| ASUSTek  | NARRA3                      | [6b02d3fa6f](https://linux-hardware.org/?probe=6b02d3fa6f) | Sep 11, 2021 |
| Gigabyte | 970A-DS3P                   | [8b0f703471](https://linux-hardware.org/?probe=8b0f703471) | Sep 11, 2021 |
| Lenovo   | SDK0E50519 WIN              | [7c58527193](https://linux-hardware.org/?probe=7c58527193) | Sep 11, 2021 |
| Intel    | X79M-S                      | [95d22f6e90](https://linux-hardware.org/?probe=95d22f6e90) | Sep 11, 2021 |
| ASUSTek  | P5GC-MX/1333                | [1ff7b16ce4](https://linux-hardware.org/?probe=1ff7b16ce4) | Sep 10, 2021 |
| ASUSTek  | Z170 PRO GAMING             | [dab9a23b27](https://linux-hardware.org/?probe=dab9a23b27) | Sep 10, 2021 |
| Gigabyte | B450 AORUS PRO WIFI-CF      | [34e6b7697f](https://linux-hardware.org/?probe=34e6b7697f) | Sep 09, 2021 |
| ASUSTek  | ROG Maximus X HERO          | [5ce713a2f7](https://linux-hardware.org/?probe=5ce713a2f7) | Sep 09, 2021 |
| ASUSTek  | NARRA3                      | [52b22746e0](https://linux-hardware.org/?probe=52b22746e0) | Sep 09, 2021 |
| HP       | 2187 A01                    | [0c11e3b726](https://linux-hardware.org/?probe=0c11e3b726) | Sep 09, 2021 |
| MSI      | B450M MORTAR MAX            | [f40c6b596c](https://linux-hardware.org/?probe=f40c6b596c) | Sep 08, 2021 |
| Dell     | 09KPNV A01                  | [f3c9b271f1](https://linux-hardware.org/?probe=f3c9b271f1) | Sep 08, 2021 |
| MSI      | B450M MORTAR MAX            | [7dbf053877](https://linux-hardware.org/?probe=7dbf053877) | Sep 08, 2021 |
| MSI      | H81M-P33                    | [92b799f852](https://linux-hardware.org/?probe=92b799f852) | Sep 08, 2021 |
| MSI      | B450M MORTAR MAX            | [17c58396b6](https://linux-hardware.org/?probe=17c58396b6) | Sep 08, 2021 |
| MSI      | B450M MORTAR MAX            | [dfe73847d3](https://linux-hardware.org/?probe=dfe73847d3) | Sep 08, 2021 |
| Dell     | 0D28YY A03                  | [3eb7b9cb7b](https://linux-hardware.org/?probe=3eb7b9cb7b) | Sep 08, 2021 |
| ASUSTek  | P5G41T-M LX3                | [2f680da4b8](https://linux-hardware.org/?probe=2f680da4b8) | Sep 07, 2021 |
| Unknown  | Unknown                     | [b00795951c](https://linux-hardware.org/?probe=b00795951c) | Sep 07, 2021 |
| MSI      | B560M PRO-VDH               | [807eed7553](https://linux-hardware.org/?probe=807eed7553) | Sep 06, 2021 |
| ASRock   | Q1900M                      | [3f08533d5f](https://linux-hardware.org/?probe=3f08533d5f) | Sep 06, 2021 |
| ASRock   | Q1900M                      | [d342919044](https://linux-hardware.org/?probe=d342919044) | Sep 06, 2021 |
| Intel    | X79M-S                      | [e45160873d](https://linux-hardware.org/?probe=e45160873d) | Sep 06, 2021 |
| ASUSTek  | M5A97                       | [28754f0456](https://linux-hardware.org/?probe=28754f0456) | Sep 06, 2021 |
| Gigabyte | G31M-ES2L                   | [d94c35ce11](https://linux-hardware.org/?probe=d94c35ce11) | Sep 05, 2021 |
| MSI      | IONA                        | [8a4454604a](https://linux-hardware.org/?probe=8a4454604a) | Sep 05, 2021 |
| ASUSTek  | M5A97 LE R2.0               | [791768dfbd](https://linux-hardware.org/?probe=791768dfbd) | Sep 04, 2021 |
| MSI      | IONA                        | [b775cef84a](https://linux-hardware.org/?probe=b775cef84a) | Sep 04, 2021 |
| ASUSTek  | NARRA3                      | [920ab9b385](https://linux-hardware.org/?probe=920ab9b385) | Sep 04, 2021 |
| Gigabyte | Z490 AORUS ELITE            | [149099265c](https://linux-hardware.org/?probe=149099265c) | Sep 04, 2021 |
| Intel    | DQ77MK AAG39642-500         | [391c101a92](https://linux-hardware.org/?probe=391c101a92) | Sep 04, 2021 |
| HP       | 2B4B                        | [d36296bddf](https://linux-hardware.org/?probe=d36296bddf) | Sep 04, 2021 |
| ASUSTek  | Z170I PRO GAMING            | [9e6ccaa1f3](https://linux-hardware.org/?probe=9e6ccaa1f3) | Sep 04, 2021 |
| Biostar  | X470NH                      | [f0449b9946](https://linux-hardware.org/?probe=f0449b9946) | Sep 04, 2021 |
| Gigabyte | A320M-S2H-CF                | [126d9974b1](https://linux-hardware.org/?probe=126d9974b1) | Sep 03, 2021 |
| HP       | 1497                        | [fd4cf5c840](https://linux-hardware.org/?probe=fd4cf5c840) | Sep 01, 2021 |
| Gigabyte | B460M DS3H                  | [ef23780b19](https://linux-hardware.org/?probe=ef23780b19) | Aug 31, 2021 |
| Positivo | POS-PIH81DI                 | [baa289fe51](https://linux-hardware.org/?probe=baa289fe51) | Aug 31, 2021 |
| Positivo | POS-PIH81DI                 | [cc326a093e](https://linux-hardware.org/?probe=cc326a093e) | Aug 31, 2021 |
| HP       | 339A                        | [5a5ab8d1c2](https://linux-hardware.org/?probe=5a5ab8d1c2) | Aug 31, 2021 |
| HP       | 339A                        | [c0043e4c4c](https://linux-hardware.org/?probe=c0043e4c4c) | Aug 31, 2021 |
| ASUSTek  | TUF GAMING B550-PLUS        | [4c711d446d](https://linux-hardware.org/?probe=4c711d446d) | Aug 31, 2021 |
| ASUSTek  | TUF GAMING B550-PLUS        | [efb9bccc60](https://linux-hardware.org/?probe=efb9bccc60) | Aug 31, 2021 |
| Intel    | DQ77MK AAG39642-500         | [000d760a55](https://linux-hardware.org/?probe=000d760a55) | Aug 30, 2021 |
| Positivo | POS-PIH81DI                 | [3b05a7b317](https://linux-hardware.org/?probe=3b05a7b317) | Aug 30, 2021 |
| MSI      | Z87-G43                     | [a219ff197d](https://linux-hardware.org/?probe=a219ff197d) | Aug 29, 2021 |
| MSI      | MPG X570 GAMING PLUS        | [01a43874df](https://linux-hardware.org/?probe=01a43874df) | Aug 28, 2021 |
| ASUSTek  | PRIME A320M-K               | [f7a948129f](https://linux-hardware.org/?probe=f7a948129f) | Aug 28, 2021 |
| ASUSTek  | P8H61-M LX2 R2.0            | [5cd3f43e28](https://linux-hardware.org/?probe=5cd3f43e28) | Aug 28, 2021 |
| Gigabyte | A320M-S2H-CF                | [6ed5f8c32b](https://linux-hardware.org/?probe=6ed5f8c32b) | Aug 27, 2021 |
| ASRock   | Z390 Phantom Gaming 4-IB    | [b01269fbc1](https://linux-hardware.org/?probe=b01269fbc1) | Aug 27, 2021 |
| Lenovo   | SHARKBAY SDK0E50510 WIN     | [51661e959e](https://linux-hardware.org/?probe=51661e959e) | Aug 26, 2021 |
| Lenovo   | SHARKBAY SDK0E50510 WIN     | [3a7eb89cd8](https://linux-hardware.org/?probe=3a7eb89cd8) | Aug 25, 2021 |
| HP       | 802E                        | [3ee51e8a56](https://linux-hardware.org/?probe=3ee51e8a56) | Aug 25, 2021 |
| ASUSTek  | P8Z77-V LX                  | [314859d762](https://linux-hardware.org/?probe=314859d762) | Aug 25, 2021 |
| ASUSTek  | P8Z77-V LX                  | [faaf8bc158](https://linux-hardware.org/?probe=faaf8bc158) | Aug 25, 2021 |
| Dell     | 088DT1 A01                  | [8620323354](https://linux-hardware.org/?probe=8620323354) | Aug 25, 2021 |
| Dell     | 0TP406                      | [72a3d9ac12](https://linux-hardware.org/?probe=72a3d9ac12) | Aug 25, 2021 |
| HP       | 2B4B                        | [4c5411522b](https://linux-hardware.org/?probe=4c5411522b) | Aug 25, 2021 |
| Gigabyte | B85M-D3H                    | [906a3e006c](https://linux-hardware.org/?probe=906a3e006c) | Aug 24, 2021 |
| Gigabyte | B85M-D3H                    | [9f369218ff](https://linux-hardware.org/?probe=9f369218ff) | Aug 24, 2021 |
| ASUSTek  | P8Z77-V LE                  | [a720e3326a](https://linux-hardware.org/?probe=a720e3326a) | Aug 23, 2021 |
| MSI      | B450M PRO-M2 MAX            | [e6f053c5be](https://linux-hardware.org/?probe=e6f053c5be) | Aug 22, 2021 |
| ASUSTek  | ROG STRIX Z490-E GAMING     | [15175b4f4f](https://linux-hardware.org/?probe=15175b4f4f) | Aug 22, 2021 |
| ASUSTek  | ROG STRIX Z490-E GAMING     | [02ccc1eb70](https://linux-hardware.org/?probe=02ccc1eb70) | Aug 22, 2021 |
| ASUSTek  | M5A97 R2.0                  | [372a125910](https://linux-hardware.org/?probe=372a125910) | Aug 22, 2021 |
| Lenovo   | Board                       | [b4e9579228](https://linux-hardware.org/?probe=b4e9579228) | Aug 21, 2021 |
| Lenovo   | Board                       | [12088eed17](https://linux-hardware.org/?probe=12088eed17) | Aug 21, 2021 |
| MSI      | B450M PRO-M2 MAX            | [68c6a2734b](https://linux-hardware.org/?probe=68c6a2734b) | Aug 21, 2021 |
| Intel    | DB75EN AAG39650-303         | [4bbb9f60f9](https://linux-hardware.org/?probe=4bbb9f60f9) | Aug 20, 2021 |
| Fujitsu  | D3220-A1 S26361-D3220-A1    | [63cbb9e7fd](https://linux-hardware.org/?probe=63cbb9e7fd) | Aug 19, 2021 |
| MSI      | Z97 XPOWER AC               | [c68138439d](https://linux-hardware.org/?probe=c68138439d) | Aug 19, 2021 |
| ASUSTek  | M5A78L-M/USB3               | [d78450d852](https://linux-hardware.org/?probe=d78450d852) | Aug 19, 2021 |
| Acer     | Aspire XC-605G              | [8bb6f8ef72](https://linux-hardware.org/?probe=8bb6f8ef72) | Aug 18, 2021 |
| ASUSTek  | B85M-G R2.0                 | [daf6bf889f](https://linux-hardware.org/?probe=daf6bf889f) | Aug 18, 2021 |
| MSI      | Z270-A PRO                  | [3be5b7f90e](https://linux-hardware.org/?probe=3be5b7f90e) | Aug 18, 2021 |
| Gigabyte | B550M DS3H                  | [4b687b4c17](https://linux-hardware.org/?probe=4b687b4c17) | Aug 16, 2021 |
| ASUSTek  | Z97-C                       | [97b71d18de](https://linux-hardware.org/?probe=97b71d18de) | Aug 16, 2021 |
| ASUSTek  | Z97-C                       | [06872ddde7](https://linux-hardware.org/?probe=06872ddde7) | Aug 16, 2021 |
| ASUSTek  | Z97-C                       | [a1f448c1f6](https://linux-hardware.org/?probe=a1f448c1f6) | Aug 15, 2021 |
| ASUSTek  | PRIME X570-PRO              | [fb7eb46b29](https://linux-hardware.org/?probe=fb7eb46b29) | Aug 11, 2021 |
| ASUSTek  | SABERTOOTH Z97 MARK 1       | [fb8a0b07d1](https://linux-hardware.org/?probe=fb8a0b07d1) | Aug 10, 2021 |
| ASUSTek  | M5A97 LE R2.0               | [4d9eaaf5a8](https://linux-hardware.org/?probe=4d9eaaf5a8) | Aug 09, 2021 |
| Gigabyte | B550M H                     | [b26c567912](https://linux-hardware.org/?probe=b26c567912) | Aug 03, 2021 |
| ASUSTek  | M5A78L-M/USB3               | [9c841a04d6](https://linux-hardware.org/?probe=9c841a04d6) | Aug 01, 2021 |
| Gigabyte | H61M-USB3-B3                | [3c2020fbb6](https://linux-hardware.org/?probe=3c2020fbb6) | Jul 30, 2021 |
| Gigabyte | H61M-USB3-B3                | [b3bbc6d937](https://linux-hardware.org/?probe=b3bbc6d937) | Jul 30, 2021 |
| Dell     | 0V8WGR A00                  | [2cf38ffd15](https://linux-hardware.org/?probe=2cf38ffd15) | Jul 14, 2021 |
| ASUSTek  | P8H61-M LE                  | [b0270beb17](https://linux-hardware.org/?probe=b0270beb17) | Jul 11, 2021 |
| ASUSTek  | P8H61-M LE                  | [896e6feb8a](https://linux-hardware.org/?probe=896e6feb8a) | Jul 11, 2021 |
| Lenovo   | 36C5 SDK0J40700 WIN 3258... | [20bf622c31](https://linux-hardware.org/?probe=20bf622c31) | Jun 25, 2021 |
| ASUSTek  | PRIME B450M-GAMING/BR       | [35605881d6](https://linux-hardware.org/?probe=35605881d6) | Jun 23, 2021 |
| MSI      | 2AE0                        | [bce75d51cd](https://linux-hardware.org/?probe=bce75d51cd) | Jun 23, 2021 |
| MSI      | 2AE0                        | [0412c710eb](https://linux-hardware.org/?probe=0412c710eb) | Jun 22, 2021 |
| ASUSTek  | PRIME B450M-GAMING/BR       | [b9d86eb932](https://linux-hardware.org/?probe=b9d86eb932) | Jun 17, 2021 |
| ASUSTek  | PRIME B450M-GAMING/BR       | [71de5617aa](https://linux-hardware.org/?probe=71de5617aa) | Jun 17, 2021 |
| ASUSTek  | PRIME X570-P                | [bca1e1b92f](https://linux-hardware.org/?probe=bca1e1b92f) | Jun 16, 2021 |
| ASUSTek  | PRIME X570-P                | [b3f6c76103](https://linux-hardware.org/?probe=b3f6c76103) | Jun 16, 2021 |
| Gigabyte | B85-HD3                     | [c73931b3ff](https://linux-hardware.org/?probe=c73931b3ff) | Jun 13, 2021 |
| HP       | 843C                        | [ccff6e4f39](https://linux-hardware.org/?probe=ccff6e4f39) | Jun 08, 2021 |
| ASRock   | 990FX Extreme6              | [fc3b27abac](https://linux-hardware.org/?probe=fc3b27abac) | Jun 03, 2021 |
| HP       | 8591                        | [6f71430d88](https://linux-hardware.org/?probe=6f71430d88) | Jun 01, 2021 |
| HP       | 8591                        | [fc12c57885](https://linux-hardware.org/?probe=fc12c57885) | Jun 01, 2021 |
| ASRock   | 990FX Extreme6              | [0a228b18c1](https://linux-hardware.org/?probe=0a228b18c1) | May 30, 2021 |
| ASUSTek  | PRIME B450M-GAMING/BR       | [0144616bb9](https://linux-hardware.org/?probe=0144616bb9) | May 27, 2021 |
| Gigabyte | 945GCM-S2L                  | [9890da0efd](https://linux-hardware.org/?probe=9890da0efd) | May 27, 2021 |
| Gigabyte | 945GCM-S2L                  | [61e1972b06](https://linux-hardware.org/?probe=61e1972b06) | May 27, 2021 |
| Lenovo   | SHARKBAY 0B98401 PRO        | [887dbc1614](https://linux-hardware.org/?probe=887dbc1614) | May 24, 2021 |
| Biostar  | A320MH                      | [db3a18e1c3](https://linux-hardware.org/?probe=db3a18e1c3) | May 23, 2021 |
| Biostar  | A320MH                      | [ccb22fc057](https://linux-hardware.org/?probe=ccb22fc057) | May 23, 2021 |
| Lenovo   | SHARKBAY 0B98401 PRO        | [0c314899c1](https://linux-hardware.org/?probe=0c314899c1) | May 23, 2021 |
| ASUSTek  | PRIME B450M-GAMING/BR       | [c41eec9cd3](https://linux-hardware.org/?probe=c41eec9cd3) | May 21, 2021 |
| ASUSTek  | PRIME B450M-GAMING/BR       | [ca773b28ee](https://linux-hardware.org/?probe=ca773b28ee) | May 19, 2021 |
| ASUSTek  | P8H61-I R2.0                | [c641f2aee4](https://linux-hardware.org/?probe=c641f2aee4) | May 16, 2021 |
| ASUSTek  | P8H61-I R2.0                | [500443b449](https://linux-hardware.org/?probe=500443b449) | May 16, 2021 |
| Lenovo   | Annapurna CRB NOK           | [7d4224df3f](https://linux-hardware.org/?probe=7d4224df3f) | May 13, 2021 |
| Lenovo   | Annapurna CRB NOK           | [adef2ac504](https://linux-hardware.org/?probe=adef2ac504) | May 13, 2021 |
| Dell     | 06D7TR A00                  | [1ccb5b0600](https://linux-hardware.org/?probe=1ccb5b0600) | May 01, 2021 |
| Pegatron | Benicia                     | [df847c36d5](https://linux-hardware.org/?probe=df847c36d5) | Apr 25, 2021 |
| Gigabyte | B450 AORUS ELITE            | [7f46cdb7ab](https://linux-hardware.org/?probe=7f46cdb7ab) | Apr 24, 2021 |
| ASUSTek  | M4A88TD-V EVO/USB3          | [b00e95f3db](https://linux-hardware.org/?probe=b00e95f3db) | Apr 22, 2021 |
| ASUSTek  | P5K                         | [0149b6c450](https://linux-hardware.org/?probe=0149b6c450) | Apr 22, 2021 |
| Dell     | 0PGKWF A02                  | [f963717b2c](https://linux-hardware.org/?probe=f963717b2c) | Apr 18, 2021 |
| Acer     | Aspire XC-605G              | [79d3d3a05e](https://linux-hardware.org/?probe=79d3d3a05e) | Mar 18, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.11.0-27-generic | 48       | 50.53%  |
| 5.11.0-34-generic | 18       | 18.95%  |
| 5.8.0-53-generic  | 7        | 7.37%   |
| 5.8.0-55-generic  | 5        | 5.26%   |
| 5.8.0-50-generic  | 5        | 5.26%   |
| 5.8.0-59-generic  | 3        | 3.16%   |
| 5.8.0-49-generic  | 3        | 3.16%   |
| 5.11.0-25-generic | 3        | 3.16%   |
| 5.8.0-63-generic  | 2        | 2.11%   |
| 5.8.0-45-generic  | 1        | 1.05%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11.0  | 69       | 73.4%   |
| 5.8.0   | 25       | 26.6%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11    | 69       | 73.4%   |
| 5.8     | 25       | 26.6%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 93       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| GNOME    | 92       | 97.87%  |
| XFCE     | 1        | 1.06%   |
| Cinnamon | 1        | 1.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 93       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 87       | 93.55%  |
| GDM     | 5        | 5.38%   |
| TDM     | 1        | 1.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 35       | 37.63%  |
| de_DE | 12       | 12.9%   |
| en_GB | 9        | 9.68%   |
| pt_BR | 8        | 8.6%    |
| nl_NL | 3        | 3.23%   |
| es_ES | 3        | 3.23%   |
| pl_PL | 2        | 2.15%   |
| es_MX | 2        | 2.15%   |
| en_ZA | 2        | 2.15%   |
| en_IN | 2        | 2.15%   |
| en_AU | 2        | 2.15%   |
| pt_PT | 1        | 1.08%   |
| nl_BE | 1        | 1.08%   |
| it_IT | 1        | 1.08%   |
| hu_HU | 1        | 1.08%   |
| fr_CA | 1        | 1.08%   |
| es_PE | 1        | 1.08%   |
| es_PA | 1        | 1.08%   |
| es_GT | 1        | 1.08%   |
| es_CL | 1        | 1.08%   |
| en_SG | 1        | 1.08%   |
| en_CA | 1        | 1.08%   |
| de_CH | 1        | 1.08%   |
| cs_CZ | 1        | 1.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 48       | 51.61%  |
| EFI  | 45       | 48.39%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 88       | 94.62%  |
| Overlay | 3        | 3.23%   |
| Zfs     | 2        | 2.15%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 87       | 93.55%  |
| GPT     | 5        | 5.38%   |
| MBR     | 1        | 1.08%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 91       | 96.81%  |
| Yes       | 3        | 3.19%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 79       | 84.95%  |
| Yes       | 14       | 15.05%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 31       | 33.33%  |
| Gigabyte Technology | 14       | 15.05%  |
| MSI                 | 11       | 11.83%  |
| Hewlett-Packard     | 8        | 8.6%    |
| Lenovo              | 6        | 6.45%   |
| Dell                | 6        | 6.45%   |
| Intel               | 5        | 5.38%   |
| ASRock              | 4        | 4.3%    |
| Biostar             | 2        | 2.15%   |
| Positivo            | 1        | 1.08%   |
| Pegatron            | 1        | 1.08%   |
| NCR                 | 1        | 1.08%   |
| Fujitsu             | 1        | 1.08%   |
| Foxconn             | 1        | 1.08%   |
| Acer                | 1        | 1.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Desktops | Percent |
|-----------------------------------------|----------|---------|
| ASUS All Series                         | 3        | 3.23%   |
| Intel DQ77MK-R01                        | 2        | 2.15%   |
| Gigabyte A320M-S2H                      | 2        | 2.15%   |
| Dell OptiPlex 990                       | 2        | 2.15%   |
| ASUS M5A97 LE R2.0                      | 2        | 2.15%   |
| ASUS M5A78L-M/USB3                      | 2        | 2.15%   |
| Positivo POS-PIH81DI                    | 1        | 1.08%   |
| Pegatron NE502AV-ABA a6750t             | 1        | 1.08%   |
| NCR xxxx-xxxx-xxxx                      | 1        | 1.08%   |
| MSI WE136AA-UUZ p6337ch                 | 1        | 1.08%   |
| MSI Pro 3515 Series                     | 1        | 1.08%   |
| MSI MS-7D18                             | 1        | 1.08%   |
| MSI MS-7C37                             | 1        | 1.08%   |
| MSI MS-7B89                             | 1        | 1.08%   |
| MSI MS-7B84                             | 1        | 1.08%   |
| MSI MS-7A71                             | 1        | 1.08%   |
| MSI MS-7914                             | 1        | 1.08%   |
| MSI MS-7817                             | 1        | 1.08%   |
| MSI MS-7816                             | 1        | 1.08%   |
| MSI MS-7798                             | 1        | 1.08%   |
| Lenovo ThinkCentre M83 MT-M 10AJ-0003MB | 1        | 1.08%   |
| Lenovo ThinkCentre M78 10BTA00ELM       | 1        | 1.08%   |
| Lenovo ThinkCentre M73 10B7S02L00       | 1        | 1.08%   |
| Lenovo SHARKBAY SDK0E50510 WIN          | 1        | 1.08%   |
| Lenovo IdeaCentre 510S-08IKL 90GB004RUS | 1        | 1.08%   |
| Lenovo Board                            | 1        | 1.08%   |
| Intel X99                               | 1        | 1.08%   |
| Intel X79M-S                            | 1        | 1.08%   |
| Intel DB75EN AAG39650-303               | 1        | 1.08%   |
| HP Z240 SFF Workstation                 | 1        | 1.08%   |
| HP Z1 Entry Tower G5                    | 1        | 1.08%   |
| HP t620 Dual Core TC                    | 1        | 1.08%   |
| HP Compaq Pro 6300 SFF                  | 1        | 1.08%   |
| HP Compaq Pro 6300 MT                   | 1        | 1.08%   |
| HP Compaq 6200 Pro SFF PC               | 1        | 1.08%   |
| HP 870-158ng                            | 1        | 1.08%   |
| HP 290 G2 MT Business PC                | 1        | 1.08%   |
| Gigabyte Z490 AORUS ELITE               | 1        | 1.08%   |
| Gigabyte Komputer OPTIMUS               | 1        | 1.08%   |
| Gigabyte H61M-USB3-B3                   | 1        | 1.08%   |
| Gigabyte G31M-ES2L                      | 1        | 1.08%   |
| Gigabyte B85M-D3H                       | 1        | 1.08%   |
| Gigabyte B85-HD3                        | 1        | 1.08%   |
| Gigabyte B550M H                        | 1        | 1.08%   |
| Gigabyte B550M DS3H                     | 1        | 1.08%   |
| Gigabyte B460MDS3H                      | 1        | 1.08%   |
| Gigabyte B450 AORUS PRO WIFI            | 1        | 1.08%   |
| Gigabyte B450 AORUS ELITE               | 1        | 1.08%   |
| Gigabyte 970A-DS3P                      | 1        | 1.08%   |
| Fujitsu ESPRIMO P520                    | 1        | 1.08%   |
| Foxconn Pro 3330 MT                     | 1        | 1.08%   |
| Dell XPS420                             | 1        | 1.08%   |
| Dell Precision WorkStation T3500        | 1        | 1.08%   |
| Dell OptiPlex 790                       | 1        | 1.08%   |
| Dell Inspiron 3847                      | 1        | 1.08%   |
| Biostar X470NH                          | 1        | 1.08%   |
| Biostar A320MH                          | 1        | 1.08%   |
| ASUS Z170I PRO GAMING                   | 1        | 1.08%   |
| ASUS Z170 PRO GAMING                    | 1        | 1.08%   |
| ASUS UNLOCK INSTALL                     | 1        | 1.08%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ASUS M5A97            | 4        | 4.3%    |
| Lenovo ThinkCentre    | 3        | 3.23%   |
| HP Compaq             | 3        | 3.23%   |
| Dell OptiPlex         | 3        | 3.23%   |
| ASUS PRIME            | 3        | 3.23%   |
| ASUS All              | 3        | 3.23%   |
| Intel DQ77MK-R01      | 2        | 2.15%   |
| Gigabyte B550M        | 2        | 2.15%   |
| Gigabyte B450         | 2        | 2.15%   |
| Gigabyte A320M-S2H    | 2        | 2.15%   |
| ASUS ROG              | 2        | 2.15%   |
| ASUS P8Z77-V          | 2        | 2.15%   |
| ASUS P8H61-M          | 2        | 2.15%   |
| ASUS M5A78L-M         | 2        | 2.15%   |
| Positivo POS-PIH81DI  | 1        | 1.08%   |
| Pegatron NE502AV-ABA  | 1        | 1.08%   |
| NCR xxxx-xxxx-xxxx    | 1        | 1.08%   |
| MSI WE136AA-UUZ       | 1        | 1.08%   |
| MSI Pro               | 1        | 1.08%   |
| MSI MS-7D18           | 1        | 1.08%   |
| MSI MS-7C37           | 1        | 1.08%   |
| MSI MS-7B89           | 1        | 1.08%   |
| MSI MS-7B84           | 1        | 1.08%   |
| MSI MS-7A71           | 1        | 1.08%   |
| MSI MS-7914           | 1        | 1.08%   |
| MSI MS-7817           | 1        | 1.08%   |
| MSI MS-7816           | 1        | 1.08%   |
| MSI MS-7798           | 1        | 1.08%   |
| Lenovo SHARKBAY       | 1        | 1.08%   |
| Lenovo IdeaCentre     | 1        | 1.08%   |
| Lenovo Board          | 1        | 1.08%   |
| Intel X99             | 1        | 1.08%   |
| Intel X79M-S          | 1        | 1.08%   |
| Intel DB75EN          | 1        | 1.08%   |
| HP Z240               | 1        | 1.08%   |
| HP Z1                 | 1        | 1.08%   |
| HP t620               | 1        | 1.08%   |
| HP 870-158ng          | 1        | 1.08%   |
| HP 290                | 1        | 1.08%   |
| Gigabyte Z490         | 1        | 1.08%   |
| Gigabyte Komputer     | 1        | 1.08%   |
| Gigabyte H61M-USB3-B3 | 1        | 1.08%   |
| Gigabyte G31M-ES2L    | 1        | 1.08%   |
| Gigabyte B85M-D3H     | 1        | 1.08%   |
| Gigabyte B85-HD3      | 1        | 1.08%   |
| Gigabyte B460MDS3H    | 1        | 1.08%   |
| Gigabyte 970A-DS3P    | 1        | 1.08%   |
| Fujitsu ESPRIMO       | 1        | 1.08%   |
| Foxconn Pro           | 1        | 1.08%   |
| Dell XPS420           | 1        | 1.08%   |
| Dell Precision        | 1        | 1.08%   |
| Dell Inspiron         | 1        | 1.08%   |
| Biostar X470NH        | 1        | 1.08%   |
| Biostar A320MH        | 1        | 1.08%   |
| ASUS Z170I            | 1        | 1.08%   |
| ASUS Z170             | 1        | 1.08%   |
| ASUS UNLOCK           | 1        | 1.08%   |
| ASUS TUF              | 1        | 1.08%   |
| ASUS P5Q              | 1        | 1.08%   |
| ASUS P5K              | 1        | 1.08%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 13       | 13.98%  |
| 2014 | 12       | 12.9%   |
| 2021 | 11       | 11.83%  |
| 2018 | 9        | 9.68%   |
| 2012 | 9        | 9.68%   |
| 2015 | 7        | 7.53%   |
| 2013 | 7        | 7.53%   |
| 2019 | 6        | 6.45%   |
| 2016 | 4        | 4.3%    |
| 2010 | 4        | 4.3%    |
| 2008 | 4        | 4.3%    |
| 2011 | 3        | 3.23%   |
| 2009 | 2        | 2.15%   |
| 2017 | 1        | 1.08%   |
| 2007 | 1        | 1.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 93       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 87       | 93.55%  |
| Enabled  | 6        | 6.45%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 93       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 29       | 30.53%  |
| 16.01-24.0  | 24       | 25.26%  |
| 32.01-64.0  | 14       | 14.74%  |
| 3.01-4.0    | 13       | 13.68%  |
| 4.01-8.0    | 12       | 12.63%  |
| 64.01-256.0 | 2        | 2.11%   |
| 1.01-2.0    | 1        | 1.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1.01-2.0 | 48       | 50.53%  |
| 2.01-3.0 | 29       | 30.53%  |
| 4.01-8.0 | 9        | 9.47%   |
| 3.01-4.0 | 8        | 8.42%   |
| 0.51-1.0 | 1        | 1.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 30       | 32.26%  |
| 1      | 30       | 32.26%  |
| 3      | 14       | 15.05%  |
| 4      | 10       | 10.75%  |
| 5      | 5        | 5.38%   |
| 8      | 2        | 2.15%   |
| 6      | 1        | 1.08%   |
| 0      | 1        | 1.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 56       | 60.22%  |
| No        | 37       | 39.78%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 93       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 51       | 54.84%  |
| Yes       | 42       | 45.16%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 66       | 70.97%  |
| Yes       | 27       | 29.03%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 24       | 25.81%  |
| Germany      | 11       | 11.83%  |
| UK           | 9        | 9.68%   |
| Brazil       | 8        | 8.6%    |
| Spain        | 3        | 3.23%   |
| Netherlands  | 3        | 3.23%   |
| Canada       | 3        | 3.23%   |
| Australia    | 3        | 3.23%   |
| Switzerland  | 2        | 2.15%   |
| South Africa | 2        | 2.15%   |
| Poland       | 2        | 2.15%   |
| Mexico       | 2        | 2.15%   |
| Malaysia     | 2        | 2.15%   |
| India        | 2        | 2.15%   |
| Hungary      | 2        | 2.15%   |
| Chile        | 2        | 2.15%   |
| Taiwan       | 1        | 1.08%   |
| Serbia       | 1        | 1.08%   |
| Peru         | 1        | 1.08%   |
| Panama       | 1        | 1.08%   |
| Mozambique   | 1        | 1.08%   |
| Italy        | 1        | 1.08%   |
| Indonesia    | 1        | 1.08%   |
| Guatemala    | 1        | 1.08%   |
| Denmark      | 1        | 1.08%   |
| Czechia      | 1        | 1.08%   |
| Belgium      | 1        | 1.08%   |
| Austria      | 1        | 1.08%   |
| Argentina    | 1        | 1.08%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Santiago               | 2        | 2.15%   |
| Rio de Janeiro         | 2        | 2.15%   |
| Mentor                 | 2        | 2.15%   |
| Melbourne              | 2        | 2.15%   |
| Livingston             | 2        | 2.15%   |
| Kuala Lumpur           | 2        | 2.15%   |
| Contagem               | 2        | 2.15%   |
| Zurich                 | 1        | 1.08%   |
| Xalapa                 | 1        | 1.08%   |
| Wylie                  | 1        | 1.08%   |
| Wandsworth             | 1        | 1.08%   |
| Vienna                 | 1        | 1.08%   |
| Vespasiano             | 1        | 1.08%   |
| Vancouver              | 1        | 1.08%   |
| Vadodara               | 1        | 1.08%   |
| Utrecht                | 1        | 1.08%   |
| Trujillo               | 1        | 1.08%   |
| SÃ£o Bernardo do Campo | 1        | 1.08%   |
| Szombathely            | 1        | 1.08%   |
| Szigetvar              | 1        | 1.08%   |
| Solingen               | 1        | 1.08%   |
| Sheffield              | 1        | 1.08%   |
| Sechelt                | 1        | 1.08%   |
| Santa Cruz de Tenerife | 1        | 1.08%   |
| Salt Lake City         | 1        | 1.08%   |
| Salem                  | 1        | 1.08%   |
| Sacramento             | 1        | 1.08%   |
| Redruth                | 1        | 1.08%   |
| Porto Seguro           | 1        | 1.08%   |
| P?™?­bram              | 1        | 1.08%   |
| Pascoag                | 1        | 1.08%   |
| Panama City            | 1        | 1.08%   |
| Palm Coast             | 1        | 1.08%   |
| Oscoda                 | 1        | 1.08%   |
| Oak Creek              | 1        | 1.08%   |
| Niter??i               | 1        | 1.08%   |
| New Malden             | 1        | 1.08%   |
| Miami                  | 1        | 1.08%   |
| Marshall               | 1        | 1.08%   |
| Marpingen              | 1        | 1.08%   |
| Maputo                 | 1        | 1.08%   |
| Machhagan              | 1        | 1.08%   |
| Lynchburg              | 1        | 1.08%   |
| Ludwigsburg            | 1        | 1.08%   |
| Laziska Gorne          | 1        | 1.08%   |
| Johannesburg           | 1        | 1.08%   |
| Idaho Falls            | 1        | 1.08%   |
| Helensburgh            | 1        | 1.08%   |
| Hamburg                | 1        | 1.08%   |
| Hagen                  | 1        | 1.08%   |
| Hackney                | 1        | 1.08%   |
| Guatemala City         | 1        | 1.08%   |
| Griesheim              | 1        | 1.08%   |
| Granby                 | 1        | 1.08%   |
| Gilmer                 | 1        | 1.08%   |
| Ghent                  | 1        | 1.08%   |
| Gdynia                 | 1        | 1.08%   |
| Fort Worth             | 1        | 1.08%   |
| Fitzroy North          | 1        | 1.08%   |
| Emmendingen            | 1        | 1.08%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 33       | 43     | 18.13%  |
| WDC                       | 32       | 45     | 17.58%  |
| Samsung Electronics       | 25       | 34     | 13.74%  |
| Sandisk                   | 13       | 18     | 7.14%   |
| Kingston                  | 13       | 14     | 7.14%   |
| Toshiba                   | 10       | 10     | 5.49%   |
| Hitachi                   | 7        | 9      | 3.85%   |
| Unknown                   | 5        | 8      | 2.75%   |
| Phison                    | 5        | 6      | 2.75%   |
| Crucial                   | 5        | 7      | 2.75%   |
| Silicon Motion            | 4        | 6      | 2.2%    |
| China                     | 3        | 3      | 1.65%   |
| A-DATA Technology         | 3        | 3      | 1.65%   |
| Micron/Crucial Technology | 2        | 2      | 1.1%    |
| Lexar                     | 2        | 2      | 1.1%    |
| HGST                      | 2        | 3      | 1.1%    |
| Hewlett-Packard           | 2        | 2      | 1.1%    |
| Gigabyte Technology       | 2        | 2      | 1.1%    |
| XPG                       | 1        | 1      | 0.55%   |
| Team                      | 1        | 1      | 0.55%   |
| Patriot                   | 1        | 1      | 0.55%   |
| OWC                       | 1        | 1      | 0.55%   |
| OCZ                       | 1        | 1      | 0.55%   |
| Netac                     | 1        | 1      | 0.55%   |
| Micron Technology         | 1        | 1      | 0.55%   |
| Maxtor                    | 1        | 1      | 0.55%   |
| KIOXIA-EXCERIA            | 1        | 1      | 0.55%   |
| KingFast                  | 1        | 1      | 0.55%   |
| JMicron                   | 1        | 1      | 0.55%   |
| Intenso                   | 1        | 1      | 0.55%   |
| Config                    | 1        | 1      | 0.55%   |
| Apacer                    | 1        | 1      | 0.55%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB     | 5        | 2.34%   |
| Seagate ST1000DM010-2EP102 1TB      | 4        | 1.87%   |
| Kingston SA400S37240G 240GB SSD     | 4        | 1.87%   |
| WDC WD10EZEX-08WN4A0 1TB            | 3        | 1.4%    |
| Toshiba HDWD110 1TB                 | 3        | 1.4%    |
| Seagate ST2000DM001-9YN164 2TB      | 3        | 1.4%    |
| Samsung SSD 860 EVO 500GB           | 3        | 1.4%    |
| Samsung NVMe SSD Drive 500GB        | 3        | 1.4%    |
| Samsung HD103UJ 1TB                 | 3        | 1.4%    |
| Phison NVMe SSD Drive 1TB           | 3        | 1.4%    |
| Kingston SV300S37A120G 120GB SSD    | 3        | 1.4%    |
| WDC WD5000AAKX-08U6AA0 500GB        | 2        | 0.93%   |
| WDC WD1600AAJS-75M0A0 160GB         | 2        | 0.93%   |
| WDC WD10EZEX-60M2NA0 1TB            | 2        | 0.93%   |
| Unknown SD/MMC/MS PRO 64GB          | 2        | 0.93%   |
| Silicon Motion NVMe SSD Drive 128GB | 2        | 0.93%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 2        | 0.93%   |
| Seagate ST1000DM003-1CH162 1TB      | 2        | 0.93%   |
| SanDisk SDSSDA120G 120GB            | 2        | 0.93%   |
| Samsung SSD 840 EVO 250GB           | 2        | 0.93%   |
| Samsung SSD 840 EVO 120GB           | 2        | 0.93%   |
| Samsung HD103SJ 1TB                 | 2        | 0.93%   |
| Phison NVMe SSD Drive 512GB         | 2        | 0.93%   |
| Kingston SV300S37A240G 240GB SSD    | 2        | 0.93%   |
| Kingston SA400S37120G 120GB SSD     | 2        | 0.93%   |
| Hitachi HDT725050VLA360 500GB       | 2        | 0.93%   |
| Gigabyte GP-GSTFS31120GNTD 120GB    | 2        | 0.93%   |
| Crucial CT480BX500SSD1 480GB        | 2        | 0.93%   |
| Crucial CT240BX500SSD1 240GB        | 2        | 0.93%   |
| A-DATA SU750 256GB SSD              | 2        | 0.93%   |
| XPG NVMe SSD Drive 1024GB           | 1        | 0.47%   |
| WDC WDS250G2B0A-00SM50 250GB SSD    | 1        | 0.47%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 1        | 0.47%   |
| WDC WDS100T2B0A-00SM50 1TB SSD      | 1        | 0.47%   |
| WDC WD7500AARS-00Y5B1 752GB         | 1        | 0.47%   |
| WDC WD7500AADS-00M2B0 752GB         | 1        | 0.47%   |
| WDC WD6400AAKS-65A7B0 640GB         | 1        | 0.47%   |
| WDC WD5000AAKX-603CA0 500GB         | 1        | 0.47%   |
| WDC WD5000AAKS-00YGA0 500GB         | 1        | 0.47%   |
| WDC WD5000AADS-00S9B0 500GB         | 1        | 0.47%   |
| WDC WD40EZAZ-00SF3B0 4TB            | 1        | 0.47%   |
| WDC WD40EFRX-68N32N0 4TB            | 1        | 0.47%   |
| WDC WD3200BUCT-63TWBY0 320GB        | 1        | 0.47%   |
| WDC WD3200AAKS-75L9A0 320GB         | 1        | 0.47%   |
| WDC WD30EZRX-00D8PB0 3TB            | 1        | 0.47%   |
| WDC WD20EZRZ-00Z5HB0 2TB            | 1        | 0.47%   |
| WDC WD20EZRX-22D8PB0 2TB            | 1        | 0.47%   |
| WDC WD20EZRX-00D8PB0 2TB            | 1        | 0.47%   |
| WDC WD20EURX-61T0FY0 2TB            | 1        | 0.47%   |
| WDC WD20EFRX-68EUZN0 2TB            | 1        | 0.47%   |
| WDC WD20EARS-00MVWB0 2TB            | 1        | 0.47%   |
| WDC WD1600AAJS-22PSA0 160GB         | 1        | 0.47%   |
| WDC WD10EZEX-75M2NA0 1TB            | 1        | 0.47%   |
| WDC WD10EZEX-60WN4A0 1TB            | 1        | 0.47%   |
| WDC WD10EZEX-21M2NA0 1TB            | 1        | 0.47%   |
| WDC WD10EZEX-08M2NA0 1TB            | 1        | 0.47%   |
| WDC WD10EZEX-00WN4A0 1TB            | 1        | 0.47%   |
| WDC WD10EZEX-00MFCA0 1TB            | 1        | 0.47%   |
| WDC WD10EZEX-00KUWA0 1TB            | 1        | 0.47%   |
| WDC WD10EZEX-00BN5A0 1TB            | 1        | 0.47%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 33       | 41     | 35.11%  |
| WDC                 | 32       | 42     | 34.04%  |
| Toshiba             | 9        | 9      | 9.57%   |
| Hitachi             | 7        | 9      | 7.45%   |
| Samsung Electronics | 6        | 8      | 6.38%   |
| Unknown             | 2        | 4      | 2.13%   |
| HGST                | 2        | 3      | 2.13%   |
| Hewlett-Packard     | 2        | 2      | 2.13%   |
| Maxtor              | 1        | 1      | 1.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 15       | 18     | 23.08%  |
| Kingston            | 11       | 12     | 16.92%  |
| SanDisk             | 10       | 14     | 15.38%  |
| Crucial             | 5        | 7      | 7.69%   |
| WDC                 | 3        | 3      | 4.62%   |
| China               | 3        | 3      | 4.62%   |
| A-DATA Technology   | 3        | 3      | 4.62%   |
| Lexar               | 2        | 2      | 3.08%   |
| Gigabyte Technology | 2        | 2      | 3.08%   |
| Team                | 1        | 1      | 1.54%   |
| Seagate             | 1        | 1      | 1.54%   |
| PHISON              | 1        | 1      | 1.54%   |
| Patriot             | 1        | 1      | 1.54%   |
| OWC                 | 1        | 1      | 1.54%   |
| OCZ                 | 1        | 1      | 1.54%   |
| Netac               | 1        | 1      | 1.54%   |
| Micron Technology   | 1        | 1      | 1.54%   |
| KIOXIA-EXCERIA      | 1        | 1      | 1.54%   |
| Intenso             | 1        | 1      | 1.54%   |
| Apacer              | 1        | 1      | 1.54%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 70       | 119    | 46.67%  |
| SSD     | 51       | 75     | 34%     |
| NVMe    | 22       | 29     | 14.67%  |
| Unknown | 7        | 8      | 4.67%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 87       | 191    | 74.36%  |
| NVMe | 22       | 29     | 18.8%   |
| SAS  | 8        | 11     | 6.84%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 70       | 100    | 52.63%  |
| 0.51-1.0   | 41       | 63     | 30.83%  |
| 1.01-2.0   | 14       | 21     | 10.53%  |
| 3.01-4.0   | 5        | 6      | 3.76%   |
| 4.01-10.0  | 2        | 2      | 1.5%    |
| 2.01-3.0   | 1        | 2      | 0.75%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 23       | 24.73%  |
| 251-500        | 17       | 18.28%  |
| 501-1000       | 16       | 17.2%   |
| 1001-2000      | 12       | 12.9%   |
| 51-100         | 9        | 9.68%   |
| More than 3000 | 6        | 6.45%   |
| 1-20           | 4        | 4.3%    |
| 2001-3000      | 3        | 3.23%   |
| Unknown        | 2        | 2.15%   |
| 21-50          | 1        | 1.08%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 40       | 42.11%  |
| 21-50          | 17       | 17.89%  |
| 51-100         | 10       | 10.53%  |
| 101-250        | 9        | 9.47%   |
| More than 3000 | 5        | 5.26%   |
| 501-1000       | 5        | 5.26%   |
| 251-500        | 3        | 3.16%   |
| 1001-2000      | 3        | 3.16%   |
| Unknown        | 2        | 2.11%   |
| 2001-3000      | 1        | 1.05%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC WD10EZEX-21M2NA0 1TB  | 1        | 2      | 33.33%  |
| Toshiba MK3265GSX 320GB   | 1        | 1      | 33.33%  |
| Seagate ST9500420AS 500GB | 1        | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 2      | 33.33%  |
| Toshiba | 1        | 1      | 33.33%  |
| Seagate | 1        | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 2      | 33.33%  |
| Toshiba | 1        | 1      | 33.33%  |
| Seagate | 1        | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 3        | 4      | 100%    |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 88       | 220    | 90.72%  |
| Works    | 6        | 7      | 6.19%   |
| Malfunc  | 3        | 4      | 3.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 63       | 49.22%  |
| AMD                          | 29       | 22.66%  |
| Samsung Electronics          | 6        | 4.69%   |
| Phison Electronics           | 5        | 3.91%   |
| ASMedia Technology           | 5        | 3.91%   |
| Silicon Motion               | 4        | 3.13%   |
| Sandisk                      | 3        | 2.34%   |
| Silicon Image                | 2        | 1.56%   |
| Micron/Crucial Technology    | 2        | 1.56%   |
| Marvell Technology Group     | 2        | 1.56%   |
| Kingston Technology Company  | 2        | 1.56%   |
| VIA Technologies             | 1        | 0.78%   |
| Toshiba America Info Systems | 1        | 0.78%   |
| Nvidia                       | 1        | 0.78%   |
| JMicron Technology           | 1        | 0.78%   |
| ADATA Technology             | 1        | 0.78%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 14       | 9.15%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 11       | 7.19%   |
| Intel SATA Controller [RAID mode]                                                       | 7        | 4.58%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 7        | 4.58%   |
| AMD 400 Series Chipset SATA Controller                                                  | 7        | 4.58%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 6        | 3.92%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5        | 3.27%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5        | 3.27%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5        | 3.27%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 4        | 2.61%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4        | 2.61%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 2.61%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 2.61%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 2.61%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4        | 2.61%   |
| AMD FCH SATA Controller D                                                               | 4        | 2.61%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 3        | 1.96%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3        | 1.96%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3        | 1.96%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3        | 1.96%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 3        | 1.96%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2        | 1.31%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 1.31%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2        | 1.31%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 2        | 1.31%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 2        | 1.31%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 1.31%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 0.65%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                    | 1        | 0.65%   |
| Silicon Image SiI 3512 [SATALink/SATARaid] Serial ATA Controller                        | 1        | 0.65%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                        | 1        | 0.65%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 0.65%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.65%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.65%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1        | 0.65%   |
| Phison E12 NVMe Controller                                                              | 1        | 0.65%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 0.65%   |
| Nvidia MCP61 IDE                                                                        | 1        | 0.65%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 1        | 0.65%   |
| Micron/Crucial NVMe Controller                                                          | 1        | 0.65%   |
| Marvell Group 88SE9120 SATA 6Gb/s Controller                                            | 1        | 0.65%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1        | 0.65%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                   | 1        | 0.65%   |
| Kingston Company A2000 NVMe SSD                                                         | 1        | 0.65%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 0.65%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 0.65%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 1        | 0.65%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1        | 0.65%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 1        | 0.65%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 1        | 0.65%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1        | 0.65%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 1        | 0.65%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 1        | 0.65%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 1        | 0.65%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1        | 0.65%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1        | 0.65%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1        | 0.65%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 1        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 71       | 57.72%  |
| NVMe | 22       | 17.89%  |
| IDE  | 21       | 17.07%  |
| RAID | 9        | 7.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 63       | 67.74%  |
| AMD    | 30       | 32.26%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 5        | 5.38%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 4        | 4.3%    |
| Intel Core i5-6600K CPU @ 3.50GHz           | 3        | 3.23%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 3.23%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 3        | 3.23%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 2        | 2.15%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 2        | 2.15%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 2.15%   |
| Intel Core i5-3340 CPU @ 3.10GHz            | 2        | 2.15%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 2        | 2.15%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 2        | 2.15%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 2        | 2.15%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 2.15%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 2        | 2.15%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2        | 2.15%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 2        | 2.15%   |
| AMD FX-8320E Eight-Core Processor           | 2        | 2.15%   |
| Intel Xeon CPU X5650 @ 2.67GHz              | 1        | 1.08%   |
| Intel Xeon CPU X3220 @ 2.40GHz              | 1        | 1.08%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz         | 1        | 1.08%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz         | 1        | 1.08%   |
| Intel Pentium Gold G6400 CPU @ 4.00GHz      | 1        | 1.08%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1        | 1.08%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 1.08%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz      | 1        | 1.08%   |
| Intel Core i9-10900K CPU @ 3.70GHz          | 1        | 1.08%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1        | 1.08%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1        | 1.08%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 1.08%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 1.08%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 1.08%   |
| Intel Core i7-10700K CPU @ 3.80GHz          | 1        | 1.08%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1        | 1.08%   |
| Intel Core i5-4690K CPU @ 3.50GHz           | 1        | 1.08%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1        | 1.08%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1        | 1.08%   |
| Intel Core i5-4430 CPU @ 3.00GHz            | 1        | 1.08%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 1        | 1.08%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1        | 1.08%   |
| Intel Core i5-2500S CPU @ 2.70GHz           | 1        | 1.08%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1        | 1.08%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1        | 1.08%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 1        | 1.08%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 1        | 1.08%   |
| Intel Core i3-4360T CPU @ 3.20GHz           | 1        | 1.08%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 1        | 1.08%   |
| Intel Core i3-3225 CPU @ 3.30GHz            | 1        | 1.08%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 1        | 1.08%   |
| Intel Core 2 Quad CPU Q9505 @ 2.83GHz       | 1        | 1.08%   |
| Intel Core 2 Quad CPU Q6700 @ 2.66GHz       | 1        | 1.08%   |
| Intel Core 2 Duo CPU E6400 @ 2.13GHz        | 1        | 1.08%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 1        | 1.08%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 1        | 1.08%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 1        | 1.08%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 1        | 1.08%   |
| AMD Ryzen 5 3600XT 6-Core Processor         | 1        | 1.08%   |
| AMD Ryzen 3 1200 Quad-Core Processor        | 1        | 1.08%   |
| AMD Phenom II X4 965 Processor              | 1        | 1.08%   |
| AMD GX-217GA SOC with Radeon HD Graphics    | 1        | 1.08%   |
| AMD FX-9590 Eight-Core Processor            | 1        | 1.08%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 21       | 22.58%  |
| Intel Core i3           | 13       | 13.98%  |
| Intel Core i7           | 12       | 12.9%   |
| AMD FX                  | 7        | 7.53%   |
| AMD Ryzen 5             | 6        | 6.45%   |
| AMD Ryzen 3             | 6        | 6.45%   |
| Intel Xeon              | 4        | 4.3%    |
| Intel Core 2 Quad       | 4        | 4.3%    |
| AMD Ryzen 7             | 4        | 4.3%    |
| Intel Pentium Dual      | 3        | 3.23%   |
| Intel Pentium Dual-Core | 2        | 2.15%   |
| AMD A6                  | 2        | 2.15%   |
| Intel Pentium Gold      | 1        | 1.08%   |
| Intel Core i9           | 1        | 1.08%   |
| Intel Core 2 Duo        | 1        | 1.08%   |
| Intel Celeron           | 1        | 1.08%   |
| AMD Ryzen 9             | 1        | 1.08%   |
| AMD Phenom II X4        | 1        | 1.08%   |
| AMD GX                  | 1        | 1.08%   |
| AMD Athlon II X3        | 1        | 1.08%   |
| AMD Athlon 64 X2        | 1        | 1.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 47       | 50.54%  |
| 2      | 21       | 22.58%  |
| 6      | 10       | 10.75%  |
| 8      | 7        | 7.53%   |
| 3      | 4        | 4.3%    |
| 1      | 2        | 2.15%   |
| 12     | 1        | 1.08%   |
| 10     | 1        | 1.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 93       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 49       | 52.69%  |
| 1      | 44       | 47.31%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 93       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 15       | 16.13%  |
| 0x306a9    | 10       | 10.75%  |
| 0x08701021 | 8        | 8.6%    |
| 0x506e3    | 6        | 6.45%   |
| 0x206a7    | 6        | 6.45%   |
| 0x06000852 | 6        | 6.45%   |
| 0x6fb      | 5        | 5.38%   |
| Unknown    | 4        | 4.3%    |
| 0x6fd      | 3        | 3.23%   |
| 0x1067a    | 3        | 3.23%   |
| 0xa0655    | 2        | 2.15%   |
| 0xa0653    | 2        | 2.15%   |
| 0x906eb    | 2        | 2.15%   |
| 0x08108109 | 2        | 2.15%   |
| 0x08101016 | 2        | 2.15%   |
| 0x0800820d | 2        | 2.15%   |
| 0x06001119 | 2        | 2.15%   |
| 0x010000c8 | 2        | 2.15%   |
| 0x906ec    | 1        | 1.08%   |
| 0x906ea    | 1        | 1.08%   |
| 0x306f2    | 1        | 1.08%   |
| 0x306e4    | 1        | 1.08%   |
| 0x30678    | 1        | 1.08%   |
| 0x206c2    | 1        | 1.08%   |
| 0x20652    | 1        | 1.08%   |
| 0x08701013 | 1        | 1.08%   |
| 0x08001138 | 1        | 1.08%   |
| 0x0700010f | 1        | 1.08%   |
| 0x0600063e | 1        | 1.08%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 16       | 17.2%   |
| IvyBridge   | 11       | 11.83%  |
| Zen 2       | 9        | 9.68%   |
| Piledriver  | 8        | 8.6%    |
| Core        | 8        | 8.6%    |
| SandyBridge | 7        | 7.53%   |
| Skylake     | 6        | 6.45%   |
| KabyLake    | 5        | 5.38%   |
| Zen+        | 4        | 4.3%    |
| Zen         | 4        | 4.3%    |
| CometLake   | 4        | 4.3%    |
| Penryn      | 3        | 3.23%   |
| Westmere    | 2        | 2.15%   |
| K10         | 2        | 2.15%   |
| Silvermont  | 1        | 1.08%   |
| K8 Hammer   | 1        | 1.08%   |
| Jaguar      | 1        | 1.08%   |
| Bulldozer   | 1        | 1.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 46       | 47.42%  |
| Intel  | 26       | 26.8%   |
| AMD    | 25       | 25.77%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 6        | 6.12%   |
| Nvidia GK208B [GeForce GT 710]                                              | 5        | 5.1%    |
| Nvidia GF119 [GeForce GT 610]                                               | 4        | 4.08%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4        | 4.08%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4        | 4.08%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 3        | 3.06%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 3.06%   |
| Nvidia GK208B [GeForce GT 730]                                              | 3        | 3.06%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 3.06%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 3.06%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3        | 3.06%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 3        | 3.06%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 2.04%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 2.04%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 2.04%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 2.04%   |
| AMD Trinity 2 [Radeon HD 7540D]                                             | 2        | 2.04%   |
| AMD RS780L [Radeon 3000]                                                    | 2        | 2.04%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 2.04%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 1.02%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 1.02%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1        | 1.02%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 1.02%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 1.02%   |
| Nvidia TU104 [GeForce RTX 2060]                                             | 1        | 1.02%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 1.02%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.02%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 1.02%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 1.02%   |
| Nvidia GM107GL [Quadro K620]                                                | 1        | 1.02%   |
| Nvidia GM107GL [Quadro K1200]                                               | 1        | 1.02%   |
| Nvidia GK208 [GeForce GT 720]                                               | 1        | 1.02%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 1.02%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1        | 1.02%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 1        | 1.02%   |
| Nvidia GK104 [GeForce GTX 680]                                              | 1        | 1.02%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                           | 1        | 1.02%   |
| Nvidia GF110 [GeForce GTX 570 Rev. 2]                                       | 1        | 1.02%   |
| Nvidia GF108 [GeForce GT 730]                                               | 1        | 1.02%   |
| Nvidia GF100GL [Quadro 5000]                                                | 1        | 1.02%   |
| Nvidia GA106 [GeForce RTX 3060]                                             | 1        | 1.02%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 1        | 1.02%   |
| Nvidia G96C [GeForce 9400 GT]                                               | 1        | 1.02%   |
| Intel HD Graphics 630                                                       | 1        | 1.02%   |
| Intel HD Graphics 530                                                       | 1        | 1.02%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 1        | 1.02%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1        | 1.02%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 1        | 1.02%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 1.02%   |
| AMD RV730 PRO [Radeon HD 4650]                                              | 1        | 1.02%   |
| AMD RS880 [Radeon HD 4250]                                                  | 1        | 1.02%   |
| AMD Picasso                                                                 | 1        | 1.02%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 1        | 1.02%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 1        | 1.02%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 1.02%   |
| AMD Kabini [Radeon HD 8280E]                                                | 1        | 1.02%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                          | 1        | 1.02%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 1        | 1.02%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 1        | 1.02%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Nvidia | 46       | 48.94%  |
| 1 x AMD    | 25       | 26.6%   |
| 1 x Intel  | 22       | 23.4%   |
| 2 x AMD    | 1        | 1.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 54       | 58.06%  |
| Proprietary | 34       | 36.56%  |
| Unknown     | 5        | 5.38%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 31       | 33.33%  |
| 1.01-2.0   | 18       | 19.35%  |
| 0.51-1.0   | 13       | 13.98%  |
| 3.01-4.0   | 9        | 9.68%   |
| 7.01-8.0   | 6        | 6.45%   |
| 0.01-0.5   | 6        | 6.45%   |
| 5.01-6.0   | 5        | 5.38%   |
| 2.01-3.0   | 3        | 3.23%   |
| 16.01-24.0 | 1        | 1.08%   |
| 8.01-16.0  | 1        | 1.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 18       | 19.57%  |
| Acer                 | 9        | 9.78%   |
| AOC                  | 8        | 8.7%    |
| Goldstar             | 7        | 7.61%   |
| Unknown              | 5        | 5.43%   |
| Philips              | 5        | 5.43%   |
| LG Electronics       | 4        | 4.35%   |
| Hewlett-Packard      | 4        | 4.35%   |
| Dell                 | 4        | 4.35%   |
| BenQ                 | 4        | 4.35%   |
| Ancor Communications | 3        | 3.26%   |
| Vizio                | 2        | 2.17%   |
| Vestel               | 2        | 2.17%   |
| Sony                 | 2        | 2.17%   |
| NEC Computers        | 2        | 2.17%   |
| Lenovo               | 2        | 2.17%   |
| Iiyama               | 2        | 2.17%   |
| Xiaomi               | 1        | 1.09%   |
| ViewSonic            | 1        | 1.09%   |
| Vestel Elektronik    | 1        | 1.09%   |
| Sceptre Tech         | 1        | 1.09%   |
| HPN                  | 1        | 1.09%   |
| Gigabyte Technology  | 1        | 1.09%   |
| Gateway              | 1        | 1.09%   |
| Fujitsu Siemens      | 1        | 1.09%   |
| AUS                  | 1        | 1.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Vestel LCD Monitor 48UHD_LCD_TV 3840x2160                               | 2        | 2.11%   |
| Xiaomi Mi TV XMD00E2 3840x2160 800x450mm 36.1-inch                      | 1        | 1.05%   |
| Vizio VO37LFHDTV10A VIZ0043 1920x1080 820x460mm 37.0-inch               | 1        | 1.05%   |
| Vizio E241i-A1 VIZ1005 1920x1080 521x293mm 23.5-inch                    | 1        | 1.05%   |
| ViewSonic LCD Monitor VA2256 Series 1920x1080                           | 1        | 1.05%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch  | 1        | 1.05%   |
| Unknown LCD Monitor SAMSUNG 2464x900                                    | 1        | 1.05%   |
| Unknown LCD Monitor RTK                                                 | 1        | 1.05%   |
| Unknown LCD Monitor OPD PX227H-HDMI1 4160x1440                          | 1        | 1.05%   |
| Unknown LCD Monitor LHC TE-3125 1920x1080                               | 1        | 1.05%   |
| Unknown LCD Monitor Kingston Technology 40'TV 1834x1031                 | 1        | 1.05%   |
| Unknown LCD Monitor GKK MONITOR 1920x1080                               | 1        | 1.05%   |
| Sony TV *00 SNYA405 3840x2160 952x535mm 43.0-inch                       | 1        | 1.05%   |
| Sony AVAMP SNY9301 1280x720 708x398mm 32.0-inch                         | 1        | 1.05%   |
| Sceptre Tech H32 SPT0CB8 1920x1080 575x323mm 26.0-inch                  | 1        | 1.05%   |
| Samsung Electronics U32R59x SAM0F96 3840x2160 697x392mm 31.5-inch       | 1        | 1.05%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch       | 1        | 1.05%   |
| Samsung Electronics U28D590 SAM0B81 3840x2160 608x345mm 27.5-inch       | 1        | 1.05%   |
| Samsung Electronics SyncMaster SAM0604 1920x1080                        | 1        | 1.05%   |
| Samsung Electronics SyncMaster SAM0546 1920x1080 510x287mm 23.0-inch    | 1        | 1.05%   |
| Samsung Electronics S27R35A SAM7126 1920x1080 598x336mm 27.0-inch       | 1        | 1.05%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch       | 1        | 1.05%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch       | 1        | 1.05%   |
| Samsung Electronics S19D300 SAM0B34 1280x720 410x230mm 18.5-inch        | 1        | 1.05%   |
| Samsung Electronics LCD Monitor SAM7017 3840x2160 1872x1053mm 84.6-inch | 1        | 1.05%   |
| Samsung Electronics LCD Monitor SAM0C3C 1920x1080 700x390mm 31.5-inch   | 1        | 1.05%   |
| Samsung Electronics LCD Monitor SAM0AC6 1920x1080 700x390mm 31.5-inch   | 1        | 1.05%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 1060x626mm 48.5-inch  | 1        | 1.05%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 1020x570mm 46.0-inch  | 1        | 1.05%   |
| Samsung Electronics LCD Monitor SAM07BC 1360x768                        | 1        | 1.05%   |
| Samsung Electronics LCD Monitor SA300/SA350 1920x1080                   | 1        | 1.05%   |
| Samsung Electronics LCD Monitor C27R50x 1920x1080                       | 1        | 1.05%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1190x340mm 48.7-inch      | 1        | 1.05%   |
| Philips PHL 278E9Q PHLC17F 1920x1080 598x336mm 27.0-inch                | 1        | 1.05%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                 | 1        | 1.05%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                 | 1        | 1.05%   |
| Philips LCD Monitor 240B 1920x1200                                      | 1        | 1.05%   |
| Philips LCD Monitor 227EQPH 1920x1080                                   | 1        | 1.05%   |
| NEC Computers LCD Monitor E231W 3840x1080                               | 1        | 1.05%   |
| NEC Computers LCD Monitor E231W                                         | 1        | 1.05%   |
| NEC Computers EA244WMi NEC68D7 1920x1080 520x320mm 24.0-inch            | 1        | 1.05%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                         | 1        | 1.05%   |
| LG Electronics LCD Monitor IPS235 2944x1080                             | 1        | 1.05%   |
| LG Electronics LCD Monitor EW224 1920x1080                              | 1        | 1.05%   |
| LG Electronics LCD Monitor 23MP55 1920x1080                             | 1        | 1.05%   |
| Lenovo LEN T23i-10 LEN61AB 1920x1080 509x286mm 23.0-inch                | 1        | 1.05%   |
| Lenovo D22-20 LEN66AD 1920x1080 477x268mm 21.5-inch                     | 1        | 1.05%   |
| Iiyama PLE2483H IVM6113 1920x1080 531x299mm 24.0-inch                   | 1        | 1.05%   |
| Iiyama PL3461WQ IVM7615 3440x1440 800x335mm 34.1-inch                   | 1        | 1.05%   |
| HPN LCD Monitor HP 24ea 1920x1080                                       | 1        | 1.05%   |
| Hewlett-Packard w17e HWP26E0 1440x900 408x255mm 18.9-inch               | 1        | 1.05%   |
| Hewlett-Packard LCD Monitor w1907 3120x1050                             | 1        | 1.05%   |
| Hewlett-Packard E222 HWP3263 1920x1080 476x268mm 21.5-inch              | 1        | 1.05%   |
| Hewlett-Packard Compaq WF1907 HWP26A5 1440x900 408x255mm 18.9-inch      | 1        | 1.05%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 476x268mm 21.5-inch             | 1        | 1.05%   |
| Goldstar W2261 GSM56CE 1920x1080 477x268mm 21.5-inch                    | 1        | 1.05%   |
| Goldstar W1942 GSM4B6F 1440x900 408x255mm 18.9-inch                     | 1        | 1.05%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                 | 1        | 1.05%   |
| Goldstar LCD Monitor GSM580C 1680x1050 510x290mm 23.1-inch              | 1        | 1.05%   |
| Goldstar L1950SQ GSM4AD3 1280x1024 376x301mm 19.0-inch                  | 1        | 1.05%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 44       | 49.44%  |
| 3840x2160 (4K)     | 11       | 12.36%  |
| Unknown            | 5        | 5.62%   |
| 3840x1080          | 4        | 4.49%   |
| 3440x1440          | 3        | 3.37%   |
| 1920x1200 (WUXGA)  | 3        | 3.37%   |
| 1366x768 (WXGA)    | 3        | 3.37%   |
| 1680x1050 (WSXGA+) | 2        | 2.25%   |
| 1280x1024 (SXGA)   | 2        | 2.25%   |
| 4160x1440          | 1        | 1.12%   |
| 3120x1050          | 1        | 1.12%   |
| 2944x1080          | 1        | 1.12%   |
| 2560x1440 (QHD)    | 1        | 1.12%   |
| 2464x900           | 1        | 1.12%   |
| 1834x1031          | 1        | 1.12%   |
| 1600x900 (HD+)     | 1        | 1.12%   |
| 1600x1200          | 1        | 1.12%   |
| 1440x900 (WXGA+)   | 1        | 1.12%   |
| 1360x768           | 1        | 1.12%   |
| 1280x720 (HD)      | 1        | 1.12%   |
| 1024x768 (XGA)     | 1        | 1.12%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 29       | 32.95%  |
| 27      | 8        | 9.09%   |
| 24      | 8        | 9.09%   |
| 21      | 8        | 9.09%   |
| 31      | 6        | 6.82%   |
| 23      | 5        | 5.68%   |
| 34      | 3        | 3.41%   |
| 19      | 3        | 3.41%   |
| 18      | 3        | 3.41%   |
| 84      | 2        | 2.27%   |
| 48      | 2        | 2.27%   |
| 22      | 2        | 2.27%   |
| 46      | 1        | 1.14%   |
| 43      | 1        | 1.14%   |
| 41      | 1        | 1.14%   |
| 40      | 1        | 1.14%   |
| 36      | 1        | 1.14%   |
| 32      | 1        | 1.14%   |
| 25      | 1        | 1.14%   |
| 17      | 1        | 1.14%   |
| 15      | 1        | 1.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| Unknown     | 29       | 34.12%  |
| 501-600     | 19       | 22.35%  |
| 401-500     | 14       | 16.47%  |
| 601-700     | 7        | 8.24%   |
| 701-800     | 5        | 5.88%   |
| 1001-1500   | 3        | 3.53%   |
| 301-350     | 2        | 2.35%   |
| 1501-2000   | 2        | 2.35%   |
| 901-1000    | 2        | 2.35%   |
| 801-900     | 1        | 1.18%   |
| 351-400     | 1        | 1.18%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 39       | 48.15%  |
| Unknown | 28       | 34.57%  |
| 16/10   | 7        | 8.64%   |
| 21/9    | 3        | 3.7%    |
| 4/3     | 2        | 2.47%   |
| 5/4     | 1        | 1.23%   |
| 32/9    | 1        | 1.23%   |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inchÂ² | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 29       | 33.33%  |
| 201-250        | 18       | 20.69%  |
| 351-500        | 10       | 11.49%  |
| 301-350        | 8        | 9.2%    |
| 501-1000       | 6        | 6.9%    |
| 151-200        | 5        | 5.75%   |
| 251-300        | 4        | 4.6%    |
| More than 1000 | 3        | 3.45%   |
| 141-150        | 3        | 3.45%   |
| 101-110        | 1        | 1.15%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 33       | 39.29%  |
| Unknown | 29       | 34.52%  |
| 101-120 | 12       | 14.29%  |
| 1-50    | 5        | 5.95%   |
| 121-160 | 4        | 4.76%   |
| 161-240 | 1        | 1.19%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 75       | 79.79%  |
| 2     | 14       | 14.89%  |
| 0     | 5        | 5.32%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 60       | 44.78%  |
| Intel                    | 33       | 24.63%  |
| Qualcomm Atheros         | 11       | 8.21%   |
| TP-Link                  | 6        | 4.48%   |
| Ralink Technology        | 6        | 4.48%   |
| Ralink                   | 4        | 2.99%   |
| Xiaomi                   | 2        | 1.49%   |
| Samsung Electronics      | 1        | 0.75%   |
| Nvidia                   | 1        | 0.75%   |
| NetGear                  | 1        | 0.75%   |
| Motorola PCS             | 1        | 0.75%   |
| MediaTek                 | 1        | 0.75%   |
| Marvell Technology Group | 1        | 0.75%   |
| Linksys                  | 1        | 0.75%   |
| Gemtek                   | 1        | 0.75%   |
| Edimax Technology        | 1        | 0.75%   |
| DisplayLink              | 1        | 0.75%   |
| D-Link System            | 1        | 0.75%   |
| Broadcom                 | 1        | 0.75%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 50       | 32.68%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8        | 5.23%   |
| Realtek 802.11ac NIC                                                   | 4        | 2.61%   |
| Ralink MT7601U Wireless Adapter                                        | 4        | 2.61%   |
| Intel Ethernet Connection (2) I219-V                                   | 4        | 2.61%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 3        | 1.96%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 3        | 1.96%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3        | 1.96%   |
| Intel Wi-Fi 6 AX200                                                    | 3        | 1.96%   |
| Intel Ethernet Connection (2) I218-V                                   | 3        | 1.96%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 3        | 1.96%   |
| Xiaomi SDM660-MTP _SN:6C524624                                         | 2        | 1.31%   |
| TP-Link 802.11ac WLAN Adapter                                          | 2        | 1.31%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 2        | 1.31%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2        | 1.31%   |
| Ralink RT5370 Wireless Adapter                                         | 2        | 1.31%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 2        | 1.31%   |
| Intel I211 Gigabit Network Connection                                  | 2        | 1.31%   |
| Intel Ethernet Connection I217-LM                                      | 2        | 1.31%   |
| Intel 82574L Gigabit Network Connection                                | 2        | 1.31%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 1        | 0.65%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 1        | 0.65%   |
| TP-Link Archer T4U ver.3                                               | 1        | 0.65%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                 | 1        | 0.65%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1        | 0.65%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                | 1        | 0.65%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                             | 1        | 0.65%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1        | 0.65%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter               | 1        | 0.65%   |
| Ralink RT5592 PCIe Wireless Network Adapter                            | 1        | 0.65%   |
| Ralink RT2600 802.11 MIMO                                              | 1        | 0.65%   |
| Ralink RT2561/RT61 802.11g PCI                                         | 1        | 0.65%   |
| Ralink RT2500 Wireless 802.11bg                                        | 1        | 0.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 1        | 0.65%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1        | 0.65%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                             | 1        | 0.65%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 1        | 0.65%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                       | 1        | 0.65%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1        | 0.65%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1        | 0.65%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                          | 1        | 0.65%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1        | 0.65%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 1        | 0.65%   |
| Nvidia MCP61 Ethernet                                                  | 1        | 0.65%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]            | 1        | 0.65%   |
| Motorola PCS Moto E (4)                                                | 1        | 0.65%   |
| MediaTek TECNO Camon CX                                                | 1        | 0.65%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 1        | 0.65%   |
| Linksys WUSB6300 802.11a/b/g/n/ac Wireless Adapter [Realtek RTL8812AU] | 1        | 0.65%   |
| Intel Wireless-AC 9260                                                 | 1        | 0.65%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                 | 1        | 0.65%   |
| Intel I210 Gigabit Network Connection                                  | 1        | 0.65%   |
| Intel Ethernet Controller I225-V                                       | 1        | 0.65%   |
| Intel Ethernet Connection I217-V                                       | 1        | 0.65%   |
| Intel Ethernet Connection (7) I219-V                                   | 1        | 0.65%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1        | 0.65%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1        | 0.65%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 1        | 0.65%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 1        | 0.65%   |
| Intel 82579V Gigabit Network Connection                                | 1        | 0.65%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 12       | 25.53%  |
| Intel                 | 10       | 21.28%  |
| TP-Link               | 6        | 12.77%  |
| Ralink Technology     | 6        | 12.77%  |
| Qualcomm Atheros      | 5        | 10.64%  |
| Ralink                | 4        | 8.51%   |
| NetGear               | 1        | 2.13%   |
| Linksys               | 1        | 2.13%   |
| Gemtek                | 1        | 2.13%   |
| Edimax Technology     | 1        | 2.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek 802.11ac NIC                                                   | 4        | 8.33%   |
| Ralink MT7601U Wireless Adapter                                        | 4        | 8.33%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 3        | 6.25%   |
| Intel Wi-Fi 6 AX200                                                    | 3        | 6.25%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 3        | 6.25%   |
| TP-Link 802.11ac WLAN Adapter                                          | 2        | 4.17%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 2        | 4.17%   |
| Ralink RT5370 Wireless Adapter                                         | 2        | 4.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 2        | 4.17%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 1        | 2.08%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 1        | 2.08%   |
| TP-Link Archer T4U ver.3                                               | 1        | 2.08%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                 | 1        | 2.08%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                | 1        | 2.08%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                             | 1        | 2.08%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1        | 2.08%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter               | 1        | 2.08%   |
| Ralink RT5592 PCIe Wireless Network Adapter                            | 1        | 2.08%   |
| Ralink RT2600 802.11 MIMO                                              | 1        | 2.08%   |
| Ralink RT2561/RT61 802.11g PCI                                         | 1        | 2.08%   |
| Ralink RT2500 Wireless 802.11bg                                        | 1        | 2.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 1        | 2.08%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 1        | 2.08%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                       | 1        | 2.08%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]            | 1        | 2.08%   |
| Linksys WUSB6300 802.11a/b/g/n/ac Wireless Adapter [Realtek RTL8812AU] | 1        | 2.08%   |
| Intel Wireless-AC 9260                                                 | 1        | 2.08%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                 | 1        | 2.08%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 1        | 2.08%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 1        | 2.08%   |
| Gemtek WUBR-177G [Ralink RT2571W]                                      | 1        | 2.08%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]         | 1        | 2.08%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 57       | 56.44%  |
| Intel                    | 27       | 26.73%  |
| Qualcomm Atheros         | 7        | 6.93%   |
| Xiaomi                   | 2        | 1.98%   |
| Samsung Electronics      | 1        | 0.99%   |
| Nvidia                   | 1        | 0.99%   |
| Motorola PCS             | 1        | 0.99%   |
| MediaTek                 | 1        | 0.99%   |
| Marvell Technology Group | 1        | 0.99%   |
| DisplayLink              | 1        | 0.99%   |
| D-Link System            | 1        | 0.99%   |
| Broadcom                 | 1        | 0.99%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 50       | 47.62%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8        | 7.62%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 3.81%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3        | 2.86%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 2.86%   |
| Intel Ethernet Connection (2) I218-V                              | 3        | 2.86%   |
| Xiaomi SDM660-MTP _SN:6C524624                                    | 2        | 1.9%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 1.9%    |
| Intel I211 Gigabit Network Connection                             | 2        | 1.9%    |
| Intel Ethernet Connection I217-LM                                 | 2        | 1.9%    |
| Intel 82574L Gigabit Network Connection                           | 2        | 1.9%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.95%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.95%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 0.95%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.95%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.95%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1        | 0.95%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.95%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.95%   |
| Nvidia MCP61 Ethernet                                             | 1        | 0.95%   |
| Motorola PCS Moto E (4)                                           | 1        | 0.95%   |
| MediaTek TECNO Camon CX                                           | 1        | 0.95%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.95%   |
| Intel I210 Gigabit Network Connection                             | 1        | 0.95%   |
| Intel Ethernet Controller I225-V                                  | 1        | 0.95%   |
| Intel Ethernet Connection I217-V                                  | 1        | 0.95%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 0.95%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.95%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 0.95%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 0.95%   |
| Intel 82566DM Gigabit Network Connection                          | 1        | 0.95%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1        | 0.95%   |
| DisplayLink USB 3.0 Dual Video Dock                               | 1        | 0.95%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 0.95%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 0.95%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 93       | 68.89%  |
| WiFi     | 42       | 31.11%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 93       | 74.4%   |
| WiFi     | 32       | 25.6%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 68       | 73.12%  |
| 2     | 24       | 25.81%  |
| 3     | 1        | 1.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 64       | 68.09%  |
| Yes  | 30       | 31.91%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 9        | 32.14%  |
| Cambridge Silicon Radio         | 6        | 21.43%  |
| Realtek Semiconductor           | 5        | 17.86%  |
| ASUSTek Computer                | 3        | 10.71%  |
| Qualcomm Atheros Communications | 2        | 7.14%   |
| Lite-On Technology              | 1        | 3.57%   |
| Dell                            | 1        | 3.57%   |
| Broadcom                        | 1        | 3.57%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6        | 21.43%  |
| Realtek Bluetooth Radio                             | 5        | 17.86%  |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 7.14%   |
| Intel Bluetooth wireless interface                  | 2        | 7.14%   |
| Intel AX200 Bluetooth                               | 2        | 7.14%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2        | 7.14%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 3.57%   |
| Qualcomm Atheros Bluetooth                          | 1        | 3.57%   |
| Lite-On Bluetooth Device                            | 1        | 3.57%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 3.57%   |
| Intel Bluetooth Device                              | 1        | 3.57%   |
| Intel AX210 Bluetooth                               | 1        | 3.57%   |
| Dell BT Mini-Receiver                               | 1        | 3.57%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 3.57%   |
| ASUS Qualcomm Bluetooth 4.1                         | 1        | 3.57%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 61       | 37.65%  |
| Nvidia              | 44       | 27.16%  |
| AMD                 | 37       | 22.84%  |
| C-Media Electronics | 5        | 3.09%   |
| Razer USA           | 2        | 1.23%   |
| JMTek               | 2        | 1.23%   |
| Creative Labs       | 2        | 1.23%   |
| XMOS                | 1        | 0.62%   |
| Texas Instruments   | 1        | 0.62%   |
| Numark              | 1        | 0.62%   |
| Logitech            | 1        | 0.62%   |
| Klipsch Audio       | 1        | 0.62%   |
| iConnectivity       | 1        | 0.62%   |
| GN Netcom           | 1        | 0.62%   |
| GEMBIRD             | 1        | 0.62%   |
| Focusrite-Novation  | 1        | 0.62%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 11       | 5.88%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 10       | 5.35%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 9        | 4.81%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 9        | 4.81%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 9        | 4.81%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8        | 4.28%   |
| AMD Starship/Matisse HD Audio Controller                                   | 8        | 4.28%   |
| Nvidia GP106 High Definition Audio Controller                              | 5        | 2.67%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5        | 2.67%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 5        | 2.67%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 5        | 2.67%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4        | 2.14%   |
| Nvidia GF119 HDMI Audio Controller                                         | 4        | 2.14%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4        | 2.14%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4        | 2.14%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4        | 2.14%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4        | 2.14%   |
| Nvidia TU106 High Definition Audio Controller                              | 3        | 1.6%    |
| Nvidia GM204 High Definition Audio Controller                              | 3        | 1.6%    |
| Intel Cannon Lake PCH cAVS                                                 | 3        | 1.6%    |
| AMD FCH Azalia Controller                                                  | 3        | 1.6%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3        | 1.6%    |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 1.07%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2        | 1.07%   |
| JMTek USB PnP Audio Device                                                 | 2        | 1.07%   |
| Intel Comet Lake PCH cAVS                                                  | 2        | 1.07%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 1.07%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 1.07%   |
| Intel 200 Series PCH HD Audio                                              | 2        | 1.07%   |
| C-Media Electronics USB Advanced Audio Device                              | 2        | 1.07%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                     | 2        | 1.07%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2        | 1.07%   |
| XMOS Gustard USB Audio 2.0                                                 | 1        | 0.53%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                          | 1        | 0.53%   |
| Razer USA Razer USB Sound Card                                             | 1        | 0.53%   |
| Razer USA Razer Seiren Mini                                                | 1        | 0.53%   |
| Razer USA Kraken Tournament Edition                                        | 1        | 0.53%   |
| Nvidia TU104 HD Audio Controller                                           | 1        | 0.53%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 0.53%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 0.53%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 0.53%   |
| Nvidia GM206 High Definition Audio Controller                              | 1        | 0.53%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1        | 0.53%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 0.53%   |
| Nvidia GF114 HDMI Audio Controller                                         | 1        | 0.53%   |
| Nvidia GF110 High Definition Audio Controller                              | 1        | 0.53%   |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 0.53%   |
| Nvidia GF100 High Definition Audio Controller                              | 1        | 0.53%   |
| Nvidia GA102 High Definition Audio Controller                              | 1        | 0.53%   |
| Nvidia Audio device                                                        | 1        | 0.53%   |
| Numark MixTrack Pro                                                        | 1        | 0.53%   |
| Logitech H600 [Wireless Headset]                                           | 1        | 0.53%   |
| Klipsch Audio Klipsch KG-200 Headphones                                    | 1        | 0.53%   |
| Intel Comet Lake PCH-V Smart Sound Technology Audio Controller             | 1        | 0.53%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1        | 0.53%   |
| Intel Audio device                                                         | 1        | 0.53%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1        | 0.53%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1        | 0.53%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1        | 0.53%   |
| iConnectivity mio                                                          | 1        | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Unknown            | 3        | 33.33%  |
| Corsair            | 2        | 22.22%  |
| Team               | 1        | 11.11%  |
| SK Hynix           | 1        | 11.11%  |
| Ramaxel Technology | 1        | 11.11%  |
| G.Skill            | 1        | 11.11%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM TM44D18UD04MU-NUK 4096MB DIMM DDR4 2400MT/s  | 1        | 9.09%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                | 1        | 9.09%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 1        | 9.09%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s             | 1        | 9.09%   |
| Unknown RAM 04S2400CL17A 4096MB DIMM DDR4 2400MT/s       | 1        | 9.09%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 2667MT/s       | 1        | 9.09%   |
| SK Hynix RAM HMT325U6EFR8C-PB 2048MB DIMM DDR3 1600MT/s  | 1        | 9.09%   |
| Ramaxel RAM RMR5030ED58E8W1600 2048MB DIMM DDR3 1600MT/s | 1        | 9.09%   |
| G.Skill RAM F4-3600C19-8GVRB 8192MB DIMM DDR4 2933MT/s   | 1        | 9.09%   |
| Corsair RAM CMW64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s   | 1        | 9.09%   |
| Corsair RAM CMD16GX4M2A2666C15 8192MB DIMM DDR4 2667MT/s | 1        | 9.09%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 5        | 62.5%   |
| DDR3    | 2        | 25%     |
| Unknown | 1        | 12.5%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 8        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 4        | 44.44%  |
| 4096  | 2        | 22.22%  |
| 2048  | 2        | 22.22%  |
| 32768 | 1        | 11.11%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 2667  | 2        | 25%     |
| 1333  | 2        | 25%     |
| 3200  | 1        | 12.5%   |
| 2933  | 1        | 12.5%   |
| 2400  | 1        | 12.5%   |
| 1600  | 1        | 12.5%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 2        | 40%     |
| Canon               | 2        | 40%     |
| Samsung Electronics | 1        | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Samsung SCX-3400 Series         | 1        | 20%     |
| HP OfficeJet 4650 series        | 1        | 20%     |
| HP LaserJet Professional P1102w | 1        | 20%     |
| Canon PIXMA MG2500 Series       | 1        | 20%     |
| Canon LiDE 400                  | 1        | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                | Desktops | Percent |
|----------------------|----------|---------|
| Canon CanoScan 8800F | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Logitech               | 3        | 27.27%  |
| Microdia               | 2        | 18.18%  |
| Teslong Camera         | 1        | 9.09%   |
| Razer USA              | 1        | 9.09%   |
| Microsoft              | 1        | 9.09%   |
| Jieli Technology       | 1        | 9.09%   |
| Generalplus Technology | 1        | 9.09%   |
| ARC International      | 1        | 9.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Teslong Camera Teslong Camera        | 1        | 9.09%   |
| Razer USA Gaming Webcam [Kiyo]       | 1        | 9.09%   |
| Microsoft Microsoft?‚ LifeCam Cinema | 1        | 9.09%   |
| Microdia Webcam Vitade AF            | 1        | 9.09%   |
| Microdia PC Camera (SN9C110)         | 1        | 9.09%   |
| Logitech Webcam C270                 | 1        | 9.09%   |
| Logitech HD Webcam C910              | 1        | 9.09%   |
| Logitech HD Pro Webcam C920          | 1        | 9.09%   |
| Jieli USB PHY 2.0                    | 1        | 9.09%   |
| Generalplus GENERAL WEBCAM           | 1        | 9.09%   |
| ARC International Camera             | 1        | 9.09%   |

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

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 73       | 78.49%  |
| 1     | 17       | 18.28%  |
| 2     | 3        | 3.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 11       | 55%     |
| Graphics card            | 5        | 25%     |
| Unassigned class         | 1        | 5%      |
| Sound                    | 1        | 5%      |
| Communication controller | 1        | 5%      |
| Camera                   | 1        | 5%      |

