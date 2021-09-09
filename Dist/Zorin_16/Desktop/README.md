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
| 5.11.0-27-generic | 46       | 57.5%   |
| 5.8.0-53-generic  | 7        | 8.75%   |
| 5.8.0-55-generic  | 5        | 6.25%   |
| 5.8.0-50-generic  | 5        | 6.25%   |
| 5.11.0-34-generic | 5        | 6.25%   |
| 5.8.0-59-generic  | 3        | 3.75%   |
| 5.8.0-49-generic  | 3        | 3.75%   |
| 5.11.0-25-generic | 3        | 3.75%   |
| 5.8.0-63-generic  | 2        | 2.5%    |
| 5.8.0-45-generic  | 1        | 1.25%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11.0  | 54       | 68.35%  |
| 5.8.0   | 25       | 31.65%  |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11    | 54       | 68.35%  |
| 5.8     | 25       | 31.65%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 78       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| GNOME    | 77       | 97.47%  |
| XFCE     | 1        | 1.27%   |
| Cinnamon | 1        | 1.27%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 78       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 73       | 93.59%  |
| GDM     | 4        | 5.13%   |
| TDM     | 1        | 1.28%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 31       | 39.74%  |
| de_DE | 10       | 12.82%  |
| pt_BR | 8        | 10.26%  |
| en_GB | 7        | 8.97%   |
| es_ES | 3        | 3.85%   |
| pl_PL | 2        | 2.56%   |
| es_MX | 2        | 2.56%   |
| en_ZA | 2        | 2.56%   |
| en_IN | 2        | 2.56%   |
| nl_NL | 1        | 1.28%   |
| nl_BE | 1        | 1.28%   |
| it_IT | 1        | 1.28%   |
| hu_HU | 1        | 1.28%   |
| es_PE | 1        | 1.28%   |
| es_PA | 1        | 1.28%   |
| es_CL | 1        | 1.28%   |
| en_SG | 1        | 1.28%   |
| en_CA | 1        | 1.28%   |
| de_CH | 1        | 1.28%   |
| cs_CZ | 1        | 1.28%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 39       | 50%     |
| EFI  | 39       | 50%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 73       | 93.59%  |
| Overlay | 3        | 3.85%   |
| Zfs     | 2        | 2.56%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 73       | 93.59%  |
| GPT     | 4        | 5.13%   |
| MBR     | 1        | 1.28%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 76       | 96.2%   |
| Yes       | 3        | 3.8%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 67       | 85.9%   |
| Yes       | 11       | 14.1%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 25       | 32.05%  |
| Gigabyte Technology | 12       | 15.38%  |
| MSI                 | 10       | 12.82%  |
| Hewlett-Packard     | 7        | 8.97%   |
| Dell                | 6        | 7.69%   |
| Lenovo              | 5        | 6.41%   |
| Intel               | 4        | 5.13%   |
| ASRock              | 3        | 3.85%   |
| Biostar             | 2        | 2.56%   |
| Positivo            | 1        | 1.28%   |
| Pegatron            | 1        | 1.28%   |
| Fujitsu             | 1        | 1.28%   |
| Acer                | 1        | 1.28%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Desktops | Percent |
|-----------------------------------------|----------|---------|
| ASUS All Series                         | 3        | 3.85%   |
| Intel DQ77MK-R01                        | 2        | 2.56%   |
| Gigabyte A320M-S2H                      | 2        | 2.56%   |
| Dell OptiPlex 990                       | 2        | 2.56%   |
| ASUS M5A97 LE R2.0                      | 2        | 2.56%   |
| ASUS M5A78L-M/USB3                      | 2        | 2.56%   |
| Positivo POS-PIH81DI                    | 1        | 1.28%   |
| Pegatron NE502AV-ABA a6750t             | 1        | 1.28%   |
| MSI WE136AA-UUZ p6337ch                 | 1        | 1.28%   |
| MSI Pro 3515 Series                     | 1        | 1.28%   |
| MSI MS-7D18                             | 1        | 1.28%   |
| MSI MS-7C37                             | 1        | 1.28%   |
| MSI MS-7B89                             | 1        | 1.28%   |
| MSI MS-7B84                             | 1        | 1.28%   |
| MSI MS-7A71                             | 1        | 1.28%   |
| MSI MS-7914                             | 1        | 1.28%   |
| MSI MS-7817                             | 1        | 1.28%   |
| MSI MS-7816                             | 1        | 1.28%   |
| Lenovo ThinkCentre M83 MT-M 10AJ-0003MB | 1        | 1.28%   |
| Lenovo ThinkCentre M78 10BTA00ELM       | 1        | 1.28%   |
| Lenovo SHARKBAY SDK0E50510 WIN          | 1        | 1.28%   |
| Lenovo IdeaCentre 510S-08IKL 90GB004RUS | 1        | 1.28%   |
| Lenovo Board                            | 1        | 1.28%   |
| Intel X79M-S                            | 1        | 1.28%   |
| Intel DB75EN AAG39650-303               | 1        | 1.28%   |
| HP Z240 SFF Workstation                 | 1        | 1.28%   |
| HP Z1 Entry Tower G5                    | 1        | 1.28%   |
| HP t620 Dual Core TC                    | 1        | 1.28%   |
| HP Compaq Pro 6300 SFF                  | 1        | 1.28%   |
| HP Compaq 6200 Pro SFF PC               | 1        | 1.28%   |
| HP 870-158ng                            | 1        | 1.28%   |
| HP 290 G2 MT Business PC                | 1        | 1.28%   |
| Gigabyte Z490 AORUS ELITE               | 1        | 1.28%   |
| Gigabyte Komputer OPTIMUS               | 1        | 1.28%   |
| Gigabyte H61M-USB3-B3                   | 1        | 1.28%   |
| Gigabyte G31M-ES2L                      | 1        | 1.28%   |
| Gigabyte B85M-D3H                       | 1        | 1.28%   |
| Gigabyte B85-HD3                        | 1        | 1.28%   |
| Gigabyte B550M H                        | 1        | 1.28%   |
| Gigabyte B550M DS3H                     | 1        | 1.28%   |
| Gigabyte B460MDS3H                      | 1        | 1.28%   |
| Gigabyte B450 AORUS ELITE               | 1        | 1.28%   |
| Fujitsu ESPRIMO P520                    | 1        | 1.28%   |
| Dell XPS420                             | 1        | 1.28%   |
| Dell Precision WorkStation T3500        | 1        | 1.28%   |
| Dell OptiPlex 790                       | 1        | 1.28%   |
| Dell Inspiron 3847                      | 1        | 1.28%   |
| Biostar X470NH                          | 1        | 1.28%   |
| Biostar A320MH                          | 1        | 1.28%   |
| ASUS Z170I PRO GAMING                   | 1        | 1.28%   |
| ASUS UNLOCK INSTALL                     | 1        | 1.28%   |
| ASUS TUF GAMING B550-PLUS               | 1        | 1.28%   |
| ASUS ROG STRIX Z490-E GAMING            | 1        | 1.28%   |
| ASUS PRIME X570-PRO                     | 1        | 1.28%   |
| ASUS PRIME X570-P                       | 1        | 1.28%   |
| ASUS PRIME B450M-GAMING/BR              | 1        | 1.28%   |
| ASUS P8Z77-V LX                         | 1        | 1.28%   |
| ASUS P8Z77-V LE                         | 1        | 1.28%   |
| ASUS P8H61-M LX2 R2.0                   | 1        | 1.28%   |
| ASUS P8H61-M LE                         | 1        | 1.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ASUS M5A97            | 4        | 5.13%   |
| Dell OptiPlex         | 3        | 3.85%   |
| ASUS PRIME            | 3        | 3.85%   |
| ASUS All              | 3        | 3.85%   |
| Lenovo ThinkCentre    | 2        | 2.56%   |
| Intel DQ77MK-R01      | 2        | 2.56%   |
| HP Compaq             | 2        | 2.56%   |
| Gigabyte B550M        | 2        | 2.56%   |
| Gigabyte A320M-S2H    | 2        | 2.56%   |
| ASUS P8Z77-V          | 2        | 2.56%   |
| ASUS P8H61-M          | 2        | 2.56%   |
| ASUS M5A78L-M         | 2        | 2.56%   |
| Positivo POS-PIH81DI  | 1        | 1.28%   |
| Pegatron NE502AV-ABA  | 1        | 1.28%   |
| MSI WE136AA-UUZ       | 1        | 1.28%   |
| MSI Pro               | 1        | 1.28%   |
| MSI MS-7D18           | 1        | 1.28%   |
| MSI MS-7C37           | 1        | 1.28%   |
| MSI MS-7B89           | 1        | 1.28%   |
| MSI MS-7B84           | 1        | 1.28%   |
| MSI MS-7A71           | 1        | 1.28%   |
| MSI MS-7914           | 1        | 1.28%   |
| MSI MS-7817           | 1        | 1.28%   |
| MSI MS-7816           | 1        | 1.28%   |
| Lenovo SHARKBAY       | 1        | 1.28%   |
| Lenovo IdeaCentre     | 1        | 1.28%   |
| Lenovo Board          | 1        | 1.28%   |
| Intel X79M-S          | 1        | 1.28%   |
| Intel DB75EN          | 1        | 1.28%   |
| HP Z240               | 1        | 1.28%   |
| HP Z1                 | 1        | 1.28%   |
| HP t620               | 1        | 1.28%   |
| HP 870-158ng          | 1        | 1.28%   |
| HP 290                | 1        | 1.28%   |
| Gigabyte Z490         | 1        | 1.28%   |
| Gigabyte Komputer     | 1        | 1.28%   |
| Gigabyte H61M-USB3-B3 | 1        | 1.28%   |
| Gigabyte G31M-ES2L    | 1        | 1.28%   |
| Gigabyte B85M-D3H     | 1        | 1.28%   |
| Gigabyte B85-HD3      | 1        | 1.28%   |
| Gigabyte B460MDS3H    | 1        | 1.28%   |
| Gigabyte B450         | 1        | 1.28%   |
| Fujitsu ESPRIMO       | 1        | 1.28%   |
| Dell XPS420           | 1        | 1.28%   |
| Dell Precision        | 1        | 1.28%   |
| Dell Inspiron         | 1        | 1.28%   |
| Biostar X470NH        | 1        | 1.28%   |
| Biostar A320MH        | 1        | 1.28%   |
| ASUS Z170I            | 1        | 1.28%   |
| ASUS UNLOCK           | 1        | 1.28%   |
| ASUS TUF              | 1        | 1.28%   |
| ASUS ROG              | 1        | 1.28%   |
| ASUS P5K              | 1        | 1.28%   |
| ASUS P5G41T-M         | 1        | 1.28%   |
| ASUS M4A88TD-V        | 1        | 1.28%   |
| ASUS KQ514AA-ABA      | 1        | 1.28%   |
| ASUS A0000001         | 1        | 1.28%   |
| ASRock Z390           | 1        | 1.28%   |
| ASRock Q1900M         | 1        | 1.28%   |
| ASRock 990FX          | 1        | 1.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 11       | 14.1%   |
| 2014 | 10       | 12.82%  |
| 2020 | 9        | 11.54%  |
| 2018 | 8        | 10.26%  |
| 2012 | 8        | 10.26%  |
| 2019 | 6        | 7.69%   |
| 2015 | 6        | 7.69%   |
| 2013 | 5        | 6.41%   |
| 2016 | 4        | 5.13%   |
| 2010 | 3        | 3.85%   |
| 2011 | 2        | 2.56%   |
| 2009 | 2        | 2.56%   |
| 2008 | 2        | 2.56%   |
| 2017 | 1        | 1.28%   |
| 2007 | 1        | 1.28%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 78       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 73       | 93.59%  |
| Enabled  | 5        | 6.41%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 78       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 26       | 32.5%   |
| 16.01-24.0  | 20       | 25%     |
| 32.01-64.0  | 13       | 16.25%  |
| 4.01-8.0    | 11       | 13.75%  |
| 3.01-4.0    | 8        | 10%     |
| 64.01-256.0 | 1        | 1.25%   |
| 1.01-2.0    | 1        | 1.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1.01-2.0 | 42       | 52.5%   |
| 2.01-3.0 | 23       | 28.75%  |
| 4.01-8.0 | 8        | 10%     |
| 3.01-4.0 | 6        | 7.5%    |
| 0.51-1.0 | 1        | 1.25%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 27       | 34.62%  |
| 1      | 23       | 29.49%  |
| 3      | 12       | 15.38%  |
| 4      | 9        | 11.54%  |
| 5      | 3        | 3.85%   |
| 8      | 2        | 2.56%   |
| 6      | 1        | 1.28%   |
| 0      | 1        | 1.28%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 46       | 58.97%  |
| No        | 32       | 41.03%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 78       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 43       | 55.13%  |
| Yes       | 35       | 44.87%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 54       | 69.23%  |
| Yes       | 24       | 30.77%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 21       | 26.92%  |
| Germany      | 9        | 11.54%  |
| Brazil       | 8        | 10.26%  |
| UK           | 7        | 8.97%   |
| Spain        | 3        | 3.85%   |
| Switzerland  | 2        | 2.56%   |
| South Africa | 2        | 2.56%   |
| Poland       | 2        | 2.56%   |
| Mexico       | 2        | 2.56%   |
| Malaysia     | 2        | 2.56%   |
| India        | 2        | 2.56%   |
| Hungary      | 2        | 2.56%   |
| Chile        | 2        | 2.56%   |
| Canada       | 2        | 2.56%   |
| Taiwan       | 1        | 1.28%   |
| Serbia       | 1        | 1.28%   |
| Peru         | 1        | 1.28%   |
| Panama       | 1        | 1.28%   |
| Netherlands  | 1        | 1.28%   |
| Italy        | 1        | 1.28%   |
| Denmark      | 1        | 1.28%   |
| Czechia      | 1        | 1.28%   |
| Belgium      | 1        | 1.28%   |
| Austria      | 1        | 1.28%   |
| Australia    | 1        | 1.28%   |
| Argentina    | 1        | 1.28%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Santiago               | 2        | 2.56%   |
| Rio de Janeiro         | 2        | 2.56%   |
| Mentor                 | 2        | 2.56%   |
| Livingston             | 2        | 2.56%   |
| Kuala Lumpur           | 2        | 2.56%   |
| Contagem               | 2        | 2.56%   |
| Zurich                 | 1        | 1.28%   |
| Xalapa                 | 1        | 1.28%   |
| Wylie                  | 1        | 1.28%   |
| Vienna                 | 1        | 1.28%   |
| Vespasiano             | 1        | 1.28%   |
| Vancouver              | 1        | 1.28%   |
| Vadodara               | 1        | 1.28%   |
| Trujillo               | 1        | 1.28%   |
| SÃ£o Bernardo do Campo | 1        | 1.28%   |
| Szombathely            | 1        | 1.28%   |
| Szigetvar              | 1        | 1.28%   |
| Sheffield              | 1        | 1.28%   |
| Sechelt                | 1        | 1.28%   |
| Santa Cruz de Tenerife | 1        | 1.28%   |
| Sacramento             | 1        | 1.28%   |
| Redruth                | 1        | 1.28%   |
| Porto Seguro           | 1        | 1.28%   |
| P?™?­bram              | 1        | 1.28%   |
| Pascoag                | 1        | 1.28%   |
| Panama City            | 1        | 1.28%   |
| Palm Coast             | 1        | 1.28%   |
| Oscoda                 | 1        | 1.28%   |
| Oak Creek              | 1        | 1.28%   |
| Niter??i               | 1        | 1.28%   |
| New Malden             | 1        | 1.28%   |
| Miami                  | 1        | 1.28%   |
| Melbourne              | 1        | 1.28%   |
| Marshall               | 1        | 1.28%   |
| Marpingen              | 1        | 1.28%   |
| Machhagan              | 1        | 1.28%   |
| Lynchburg              | 1        | 1.28%   |
| Ludwigsburg            | 1        | 1.28%   |
| Laziska Gorne          | 1        | 1.28%   |
| Johannesburg           | 1        | 1.28%   |
| Idaho Falls            | 1        | 1.28%   |
| Helensburgh            | 1        | 1.28%   |
| Hamburg                | 1        | 1.28%   |
| Griesheim              | 1        | 1.28%   |
| Gilmer                 | 1        | 1.28%   |
| Ghent                  | 1        | 1.28%   |
| Gdynia                 | 1        | 1.28%   |
| Fort Worth             | 1        | 1.28%   |
| Emmendingen            | 1        | 1.28%   |
| Duluth                 | 1        | 1.28%   |
| Delaware               | 1        | 1.28%   |
| Copenhagen             | 1        | 1.28%   |
| Cologne                | 1        | 1.28%   |
| Chipiona               | 1        | 1.28%   |
| Chiayi City            | 1        | 1.28%   |
| Charlottesville        | 1        | 1.28%   |
| Carlsbad               | 1        | 1.28%   |
| Carlisle               | 1        | 1.28%   |
| Cape Town              | 1        | 1.28%   |
| Borna                  | 1        | 1.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 28       | 38     | 18.06%  |
| WDC                       | 27       | 38     | 17.42%  |
| Samsung Electronics       | 21       | 30     | 13.55%  |
| Sandisk                   | 13       | 18     | 8.39%   |
| Kingston                  | 13       | 14     | 8.39%   |
| Toshiba                   | 8        | 8      | 5.16%   |
| Hitachi                   | 6        | 8      | 3.87%   |
| Silicon Motion            | 4        | 6      | 2.58%   |
| Phison                    | 4        | 5      | 2.58%   |
| Unknown                   | 3        | 5      | 1.94%   |
| Crucial                   | 3        | 5      | 1.94%   |
| China                     | 3        | 3      | 1.94%   |
| Micron/Crucial Technology | 2        | 2      | 1.29%   |
| Hewlett-Packard           | 2        | 2      | 1.29%   |
| Gigabyte Technology       | 2        | 2      | 1.29%   |
| A-DATA Technology         | 2        | 2      | 1.29%   |
| XPG                       | 1        | 1      | 0.65%   |
| Team                      | 1        | 1      | 0.65%   |
| Patriot                   | 1        | 1      | 0.65%   |
| OCZ                       | 1        | 1      | 0.65%   |
| Netac                     | 1        | 1      | 0.65%   |
| Micron Technology         | 1        | 1      | 0.65%   |
| Maxtor                    | 1        | 1      | 0.65%   |
| Lexar                     | 1        | 1      | 0.65%   |
| KIOXIA-EXCERIA            | 1        | 1      | 0.65%   |
| KingFast                  | 1        | 1      | 0.65%   |
| JMicron                   | 1        | 1      | 0.65%   |
| Intenso                   | 1        | 1      | 0.65%   |
| HGST                      | 1        | 1      | 0.65%   |
| Apacer                    | 1        | 1      | 0.65%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB     | 5        | 2.73%   |
| Seagate ST1000DM010-2EP102 1TB      | 4        | 2.19%   |
| Kingston SA400S37240G 240GB SSD     | 4        | 2.19%   |
| WDC WD10EZEX-08WN4A0 1TB            | 3        | 1.64%   |
| Toshiba HDWD110 1TB                 | 3        | 1.64%   |
| Seagate ST2000DM001-9YN164 2TB      | 3        | 1.64%   |
| Samsung SSD 860 EVO 500GB           | 3        | 1.64%   |
| Samsung NVMe SSD Drive 500GB        | 3        | 1.64%   |
| Samsung HD103UJ 1TB                 | 3        | 1.64%   |
| Phison NVMe SSD Drive 1TB           | 3        | 1.64%   |
| Kingston SV300S37A120G 120GB SSD    | 3        | 1.64%   |
| WDC WD5000AAKX-08U6AA0 500GB        | 2        | 1.09%   |
| WDC WD10EZEX-60M2NA0 1TB            | 2        | 1.09%   |
| Unknown SD/MMC/MS PRO 64GB          | 2        | 1.09%   |
| Silicon Motion NVMe SSD Drive 128GB | 2        | 1.09%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 2        | 1.09%   |
| Seagate ST1000DM003-1CH162 1TB      | 2        | 1.09%   |
| SanDisk SDSSDA120G 120GB            | 2        | 1.09%   |
| Samsung SSD 840 EVO 120GB           | 2        | 1.09%   |
| Samsung HD103SJ 1TB                 | 2        | 1.09%   |
| Kingston SV300S37A240G 240GB SSD    | 2        | 1.09%   |
| Kingston SA400S37120G 120GB SSD     | 2        | 1.09%   |
| Hitachi HDT725050VLA360 500GB       | 2        | 1.09%   |
| Gigabyte GP-GSTFS31120GNTD 120GB    | 2        | 1.09%   |
| XPG NVMe SSD Drive 1024GB           | 1        | 0.55%   |
| WDC WDS250G2B0A-00SM50 250GB SSD    | 1        | 0.55%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 1        | 0.55%   |
| WDC WDS100T2B0A-00SM50 1TB SSD      | 1        | 0.55%   |
| WDC WD7500AARS-00Y5B1 752GB         | 1        | 0.55%   |
| WDC WD7500AADS-00M2B0 752GB         | 1        | 0.55%   |
| WDC WD6400AAKS-65A7B0 640GB         | 1        | 0.55%   |
| WDC WD5000AAKS-00YGA0 500GB         | 1        | 0.55%   |
| WDC WD5000AADS-00S9B0 500GB         | 1        | 0.55%   |
| WDC WD40EZAZ-00SF3B0 4TB            | 1        | 0.55%   |
| WDC WD40EFRX-68N32N0 4TB            | 1        | 0.55%   |
| WDC WD3200BUCT-63TWBY0 320GB        | 1        | 0.55%   |
| WDC WD30EZRX-00D8PB0 3TB            | 1        | 0.55%   |
| WDC WD20EZRZ-00Z5HB0  2TB           | 1        | 0.55%   |
| WDC WD20EZRX-00D8PB0 2TB            | 1        | 0.55%   |
| WDC WD20EURX-61T0FY0 2TB            | 1        | 0.55%   |
| WDC WD20EFRX-68EUZN0 2TB            | 1        | 0.55%   |
| WDC WD1600AAJS-75M0A0 160GB         | 1        | 0.55%   |
| WDC WD1600AAJS-22PSA0 160GB         | 1        | 0.55%   |
| WDC WD10EZEX-75M2NA0 1TB            | 1        | 0.55%   |
| WDC WD10EZEX-60WN4A0 1TB            | 1        | 0.55%   |
| WDC WD10EZEX-21M2NA0 1TB            | 1        | 0.55%   |
| WDC WD10EZEX-08M2NA0 1TB            | 1        | 0.55%   |
| WDC WD10EZEX-00MFCA0 1TB            | 1        | 0.55%   |
| WDC WD10EZEX-00KUWA0 1TB            | 1        | 0.55%   |
| WDC WD10EURX-63FH1Y0 1TB            | 1        | 0.55%   |
| WDC WD10EADX-22TDHB0 1TB            | 1        | 0.55%   |
| WDC WD1003FBYZ-010FB0 1TB           | 1        | 0.55%   |
| WDC WD1002FAEX-00Y9A0 1TB           | 1        | 0.55%   |
| Unknown BFDT50S 500GB               | 1        | 0.55%   |
| Toshiba MQ01ABD032V -63 320GB       | 1        | 0.55%   |
| Toshiba MK3265GSX 320GB             | 1        | 0.55%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD | 1        | 0.55%   |
| Toshiba DT01ACA300 3TB              | 1        | 0.55%   |
| Toshiba DT01ABA200 2TB              | 1        | 0.55%   |
| Team TEAML5Lite3D1T 1TB SSD         | 1        | 0.55%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 28       | 36     | 36.36%  |
| WDC                 | 27       | 35     | 35.06%  |
| Toshiba             | 7        | 7      | 9.09%   |
| Hitachi             | 6        | 8      | 7.79%   |
| Samsung Electronics | 5        | 7      | 6.49%   |
| Hewlett-Packard     | 2        | 2      | 2.6%    |
| Maxtor              | 1        | 1      | 1.3%    |
| HGST                | 1        | 1      | 1.3%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 13       | 16     | 22.41%  |
| Kingston            | 11       | 12     | 18.97%  |
| SanDisk             | 10       | 14     | 17.24%  |
| WDC                 | 3        | 3      | 5.17%   |
| Crucial             | 3        | 5      | 5.17%   |
| China               | 3        | 3      | 5.17%   |
| Gigabyte Technology | 2        | 2      | 3.45%   |
| A-DATA Technology   | 2        | 2      | 3.45%   |
| Team                | 1        | 1      | 1.72%   |
| Seagate             | 1        | 1      | 1.72%   |
| PHISON              | 1        | 1      | 1.72%   |
| Patriot             | 1        | 1      | 1.72%   |
| OCZ                 | 1        | 1      | 1.72%   |
| Netac               | 1        | 1      | 1.72%   |
| Micron Technology   | 1        | 1      | 1.72%   |
| Lexar               | 1        | 1      | 1.72%   |
| KIOXIA-EXCERIA      | 1        | 1      | 1.72%   |
| Intenso             | 1        | 1      | 1.72%   |
| Apacer              | 1        | 1      | 1.72%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 57       | 97     | 44.53%  |
| SSD     | 45       | 68     | 35.16%  |
| NVMe    | 20       | 27     | 15.63%  |
| Unknown | 6        | 8      | 4.69%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 72       | 166    | 74.23%  |
| NVMe | 20       | 27     | 20.62%  |
| SAS  | 5        | 7      | 5.15%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 55       | 80     | 49.55%  |
| 0.51-1.0   | 36       | 58     | 32.43%  |
| 1.01-2.0   | 13       | 19     | 11.71%  |
| 3.01-4.0   | 4        | 4      | 3.6%    |
| 4.01-10.0  | 2        | 2      | 1.8%    |
| 2.01-3.0   | 1        | 2      | 0.9%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 19       | 24.36%  |
| 501-1000       | 14       | 17.95%  |
| 251-500        | 12       | 15.38%  |
| 1001-2000      | 11       | 14.1%   |
| 51-100         | 7        | 8.97%   |
| More than 3000 | 5        | 6.41%   |
| 1-20           | 4        | 5.13%   |
| 2001-3000      | 3        | 3.85%   |
| Unknown        | 2        | 2.56%   |
| 21-50          | 1        | 1.28%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 31       | 38.75%  |
| 21-50          | 15       | 18.75%  |
| 51-100         | 9        | 11.25%  |
| 101-250        | 7        | 8.75%   |
| 501-1000       | 5        | 6.25%   |
| More than 3000 | 4        | 5%      |
| 251-500        | 3        | 3.75%   |
| 1001-2000      | 3        | 3.75%   |
| Unknown        | 2        | 2.5%    |
| 2001-3000      | 1        | 1.25%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                    | Desktops | Drives | Percent |
|--------------------------|----------|--------|---------|
| WDC WD10EZEX-21M2NA0 1TB | 1        | 2      | 50%     |
| Toshiba MK3265GSX 320GB  | 1        | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 2      | 50%     |
| Toshiba | 1        | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 2      | 50%     |
| Toshiba | 1        | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 2        | 3      | 100%    |

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
| Detected | 73       | 190    | 90.12%  |
| Works    | 6        | 7      | 7.41%   |
| Malfunc  | 2        | 3      | 2.47%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 51       | 46.79%  |
| AMD                          | 26       | 23.85%  |
| Samsung Electronics          | 5        | 4.59%   |
| Silicon Motion               | 4        | 3.67%   |
| Phison Electronics           | 4        | 3.67%   |
| ASMedia Technology           | 4        | 3.67%   |
| Sandisk                      | 3        | 2.75%   |
| Silicon Image                | 2        | 1.83%   |
| Micron/Crucial Technology    | 2        | 1.83%   |
| Kingston Technology Company  | 2        | 1.83%   |
| VIA Technologies             | 1        | 0.92%   |
| Toshiba America Info Systems | 1        | 0.92%   |
| Nvidia                       | 1        | 0.92%   |
| Marvell Technology Group     | 1        | 0.92%   |
| JMicron Technology           | 1        | 0.92%   |
| ADATA Technology             | 1        | 0.92%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 12       | 9.3%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 11       | 8.53%   |
| Intel SATA Controller [RAID mode]                                                       | 6        | 4.65%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 6        | 4.65%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5        | 3.88%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 4        | 3.1%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4        | 3.1%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4        | 3.1%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 3.1%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 3.1%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 4        | 3.1%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4        | 3.1%    |
| AMD FCH SATA Controller D                                                               | 4        | 3.1%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3        | 2.33%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 3        | 2.33%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3        | 2.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3        | 2.33%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 3        | 2.33%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2        | 1.55%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 1.55%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 1.55%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2        | 1.55%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 2        | 1.55%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 2        | 1.55%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 1.55%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 1.55%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 0.78%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                    | 1        | 0.78%   |
| Silicon Image SiI 3512 [SATALink/SATARaid] Serial ATA Controller                        | 1        | 0.78%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                        | 1        | 0.78%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 0.78%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.78%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.78%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1        | 0.78%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 0.78%   |
| Nvidia MCP61 IDE                                                                        | 1        | 0.78%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 1        | 0.78%   |
| Micron/Crucial NVMe Controller                                                          | 1        | 0.78%   |
| Marvell Group 88SE9120 SATA 6Gb/s Controller                                            | 1        | 0.78%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                   | 1        | 0.78%   |
| Kingston Company A2000 NVMe SSD                                                         | 1        | 0.78%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 0.78%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 0.78%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1        | 0.78%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 1        | 0.78%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 1        | 0.78%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 1        | 0.78%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1        | 0.78%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1        | 0.78%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1        | 0.78%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1        | 0.78%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 1        | 0.78%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 60       | 57.69%  |
| NVMe | 20       | 19.23%  |
| IDE  | 16       | 15.38%  |
| RAID | 8        | 7.69%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 51       | 65.38%  |
| AMD    | 27       | 34.62%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-4790 CPU @ 3.60GHz            | 4        | 5.13%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 3.85%   |
| AMD Ryzen 5 3600 6-Core Processor           | 3        | 3.85%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 3        | 3.85%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 2        | 2.56%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 2        | 2.56%   |
| Intel Core i5-3340 CPU @ 3.10GHz            | 2        | 2.56%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 2        | 2.56%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 2        | 2.56%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 2.56%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 2        | 2.56%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2        | 2.56%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 2        | 2.56%   |
| AMD FX-8320E Eight-Core Processor           | 2        | 2.56%   |
| Intel Xeon CPU X5650 @ 2.67GHz              | 1        | 1.28%   |
| Intel Xeon CPU X3220 @ 2.40GHz              | 1        | 1.28%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz         | 1        | 1.28%   |
| Intel Pentium Gold G6400 CPU @ 4.00GHz      | 1        | 1.28%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1        | 1.28%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 1.28%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1        | 1.28%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz      | 1        | 1.28%   |
| Intel Core i9-10900K CPU @ 3.70GHz          | 1        | 1.28%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1        | 1.28%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 1.28%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 1.28%   |
| Intel Core i7-10700K CPU @ 3.80GHz          | 1        | 1.28%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1        | 1.28%   |
| Intel Core i5-4690K CPU @ 3.50GHz           | 1        | 1.28%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1        | 1.28%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1        | 1.28%   |
| Intel Core i5-4430 CPU @ 3.00GHz            | 1        | 1.28%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 1        | 1.28%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1        | 1.28%   |
| Intel Core i5-2500S CPU @ 2.70GHz           | 1        | 1.28%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1        | 1.28%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1        | 1.28%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 1        | 1.28%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 1        | 1.28%   |
| Intel Core i3-4360T CPU @ 3.20GHz           | 1        | 1.28%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 1        | 1.28%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 1        | 1.28%   |
| Intel Core i3-3225 CPU @ 3.30GHz            | 1        | 1.28%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 1        | 1.28%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 1        | 1.28%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 1        | 1.28%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 1        | 1.28%   |
| AMD Ryzen 5 3600XT 6-Core Processor         | 1        | 1.28%   |
| AMD Ryzen 3 1200 Quad-Core Processor        | 1        | 1.28%   |
| AMD Phenom II X4 965 Processor              | 1        | 1.28%   |
| AMD GX-217GA SOC with Radeon HD Graphics    | 1        | 1.28%   |
| AMD FX-9590 Eight-Core Processor            | 1        | 1.28%   |
| AMD FX-6350 Six-Core Processor              | 1        | 1.28%   |
| AMD FX-6300 Six-Core Processor              | 1        | 1.28%   |
| AMD FX-6100 Six-Core Processor              | 1        | 1.28%   |
| AMD Athlon II X3 445 Processor              | 1        | 1.28%   |
| AMD Athlon 64 X2 Dual Core Processor 5400+  | 1        | 1.28%   |
| AMD A6-5400K APU with Radeon HD Graphics    | 1        | 1.28%   |
| AMD A6-5400B APU with Radeon HD Graphics    | 1        | 1.28%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 18       | 23.08%  |
| Intel Core i3           | 11       | 14.1%   |
| Intel Core i7           | 10       | 12.82%  |
| AMD Ryzen 3             | 6        | 7.69%   |
| AMD FX                  | 6        | 7.69%   |
| AMD Ryzen 7             | 4        | 5.13%   |
| AMD Ryzen 5             | 4        | 5.13%   |
| Intel Xeon              | 3        | 3.85%   |
| Intel Pentium Dual-Core | 2        | 2.56%   |
| Intel Pentium Dual      | 2        | 2.56%   |
| Intel Core 2 Quad       | 2        | 2.56%   |
| AMD A6                  | 2        | 2.56%   |
| Intel Pentium Gold      | 1        | 1.28%   |
| Intel Core i9           | 1        | 1.28%   |
| Intel Celeron           | 1        | 1.28%   |
| AMD Ryzen 9             | 1        | 1.28%   |
| AMD Phenom II X4        | 1        | 1.28%   |
| AMD GX                  | 1        | 1.28%   |
| AMD Athlon II X3        | 1        | 1.28%   |
| AMD Athlon 64 X2        | 1        | 1.28%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 40       | 51.28%  |
| 2      | 17       | 21.79%  |
| 8      | 7        | 8.97%   |
| 6      | 6        | 7.69%   |
| 3      | 4        | 5.13%   |
| 1      | 2        | 2.56%   |
| 12     | 1        | 1.28%   |
| 10     | 1        | 1.28%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 78       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 41       | 52.56%  |
| 1      | 37       | 47.44%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 78       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 14       | 17.95%  |
| 0x306a9    | 7        | 8.97%   |
| 0x206a7    | 6        | 7.69%   |
| 0x08701021 | 6        | 7.69%   |
| 0x06000852 | 5        | 6.41%   |
| 0x6fb      | 4        | 5.13%   |
| 0x506e3    | 4        | 5.13%   |
| Unknown    | 4        | 5.13%   |
| 0xa0655    | 2        | 2.56%   |
| 0xa0653    | 2        | 2.56%   |
| 0x906eb    | 2        | 2.56%   |
| 0x1067a    | 2        | 2.56%   |
| 0x08108109 | 2        | 2.56%   |
| 0x08101016 | 2        | 2.56%   |
| 0x0800820d | 2        | 2.56%   |
| 0x06001119 | 2        | 2.56%   |
| 0x010000c8 | 2        | 2.56%   |
| 0x906ec    | 1        | 1.28%   |
| 0x6fd      | 1        | 1.28%   |
| 0x306e4    | 1        | 1.28%   |
| 0x30678    | 1        | 1.28%   |
| 0x206c2    | 1        | 1.28%   |
| 0x20652    | 1        | 1.28%   |
| 0x08701013 | 1        | 1.28%   |
| 0x08001138 | 1        | 1.28%   |
| 0x0700010f | 1        | 1.28%   |
| 0x0600063e | 1        | 1.28%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 14       | 17.95%  |
| IvyBridge   | 8        | 10.26%  |
| Zen 2       | 7        | 8.97%   |
| SandyBridge | 7        | 8.97%   |
| Piledriver  | 7        | 8.97%   |
| Core        | 5        | 6.41%   |
| Zen+        | 4        | 5.13%   |
| Zen         | 4        | 5.13%   |
| Skylake     | 4        | 5.13%   |
| KabyLake    | 4        | 5.13%   |
| CometLake   | 4        | 5.13%   |
| Westmere    | 2        | 2.56%   |
| Penryn      | 2        | 2.56%   |
| K10         | 2        | 2.56%   |
| Silvermont  | 1        | 1.28%   |
| K8 Hammer   | 1        | 1.28%   |
| Jaguar      | 1        | 1.28%   |
| Bulldozer   | 1        | 1.28%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 39       | 47.56%  |
| Intel  | 22       | 26.83%  |
| AMD    | 21       | 25.61%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 6        | 7.23%   |
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 4.82%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4        | 4.82%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 3        | 3.61%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 3.61%   |
| Nvidia GK208B [GeForce GT 730]                                              | 3        | 3.61%   |
| Nvidia GF119 [GeForce GT 610]                                               | 3        | 3.61%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3        | 3.61%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3        | 3.61%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 3        | 3.61%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 2.41%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 2.41%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 2.41%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 2.41%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 2.41%   |
| AMD Trinity 2 [Radeon HD 7540D]                                             | 2        | 2.41%   |
| AMD RS780L [Radeon 3000]                                                    | 2        | 2.41%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 2.41%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 1.2%    |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1        | 1.2%    |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 1.2%    |
| Nvidia TU104 [GeForce RTX 2060]                                             | 1        | 1.2%    |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 1.2%    |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.2%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 1.2%    |
| Nvidia GM107GL [Quadro K620]                                                | 1        | 1.2%    |
| Nvidia GM107GL [Quadro K1200]                                               | 1        | 1.2%    |
| Nvidia GK208 [GeForce GT 720]                                               | 1        | 1.2%    |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 1.2%    |
| Nvidia GK107 [GeForce GT 640]                                               | 1        | 1.2%    |
| Nvidia GK106 [GeForce GTX 660]                                              | 1        | 1.2%    |
| Nvidia GK104 [GeForce GTX 680]                                              | 1        | 1.2%    |
| Nvidia GF110 [GeForce GTX 570 Rev. 2]                                       | 1        | 1.2%    |
| Nvidia GF108 [GeForce GT 730]                                               | 1        | 1.2%    |
| Nvidia GF100GL [Quadro 5000]                                                | 1        | 1.2%    |
| Nvidia GA106 [GeForce RTX 3060]                                             | 1        | 1.2%    |
| Nvidia GA102 [GeForce RTX 3090]                                             | 1        | 1.2%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 1.2%    |
| Intel HD Graphics 630                                                       | 1        | 1.2%    |
| Intel HD Graphics 530                                                       | 1        | 1.2%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1        | 1.2%    |
| Intel 82945G/GZ Integrated Graphics Controller                              | 1        | 1.2%    |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 1.2%    |
| AMD RV730 PRO [Radeon HD 4650]                                              | 1        | 1.2%    |
| AMD RS880 [Radeon HD 4250]                                                  | 1        | 1.2%    |
| AMD Picasso                                                                 | 1        | 1.2%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 1        | 1.2%    |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 1.2%    |
| AMD Kabini [Radeon HD 8280E]                                                | 1        | 1.2%    |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 1        | 1.2%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Nvidia | 39       | 49.37%  |
| 1 x AMD    | 21       | 26.58%  |
| 1 x Intel  | 18       | 22.78%  |
| 2 x AMD    | 1        | 1.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 45       | 57.69%  |
| Proprietary | 31       | 39.74%  |
| Unknown     | 2        | 2.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 23       | 29.49%  |
| 1.01-2.0   | 17       | 21.79%  |
| 0.51-1.0   | 11       | 14.1%   |
| 3.01-4.0   | 7        | 8.97%   |
| 0.01-0.5   | 6        | 7.69%   |
| 7.01-8.0   | 5        | 6.41%   |
| 5.01-6.0   | 5        | 6.41%   |
| 2.01-3.0   | 3        | 3.85%   |
| 16.01-24.0 | 1        | 1.28%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 16       | 19.28%  |
| Acer                 | 9        | 10.84%  |
| Goldstar             | 6        | 7.23%   |
| AOC                  | 6        | 7.23%   |
| Philips              | 5        | 6.02%   |
| Unknown              | 4        | 4.82%   |
| Hewlett-Packard      | 4        | 4.82%   |
| Dell                 | 4        | 4.82%   |
| LG Electronics       | 3        | 3.61%   |
| BenQ                 | 3        | 3.61%   |
| Ancor Communications | 3        | 3.61%   |
| Vizio                | 2        | 2.41%   |
| Vestel               | 2        | 2.41%   |
| Sony                 | 2        | 2.41%   |
| NEC Computers        | 2        | 2.41%   |
| Lenovo               | 2        | 2.41%   |
| Iiyama               | 2        | 2.41%   |
| Xiaomi               | 1        | 1.2%    |
| ViewSonic            | 1        | 1.2%    |
| Sceptre Tech         | 1        | 1.2%    |
| HPN                  | 1        | 1.2%    |
| Gigabyte Technology  | 1        | 1.2%    |
| Gateway              | 1        | 1.2%    |
| Fujitsu Siemens      | 1        | 1.2%    |
| AUS                  | 1        | 1.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Vestel LCD Monitor 48UHD_LCD_TV 3840x2160                               | 2        | 2.33%   |
| Xiaomi Mi TV XMD00E2 3840x2160 800x450mm 36.1-inch                      | 1        | 1.16%   |
| Vizio VO37LFHDTV10A VIZ0043 1920x1080 820x460mm 37.0-inch               | 1        | 1.16%   |
| Vizio E241i-A1 VIZ1005 1920x1080 521x293mm 23.5-inch                    | 1        | 1.16%   |
| ViewSonic LCD Monitor VA2256 Series 1920x1080                           | 1        | 1.16%   |
| Unknown LCD Monitor SAMSUNG 2464x900                                    | 1        | 1.16%   |
| Unknown LCD Monitor RTK                                                 | 1        | 1.16%   |
| Unknown LCD Monitor OPD PX227H-HDMI1 4160x1440                          | 1        | 1.16%   |
| Unknown LCD Monitor LHC TE-3125 1920x1080                               | 1        | 1.16%   |
| Unknown LCD Monitor Kingston Technology 40'TV 1834x1031                 | 1        | 1.16%   |
| Sony TV *00 SNYA405 3840x2160 952x535mm 43.0-inch                       | 1        | 1.16%   |
| Sony AVAMP SNY9301 1280x720 708x398mm 32.0-inch                         | 1        | 1.16%   |
| Sceptre Tech H32 SPT0CB8 1920x1080 575x323mm 26.0-inch                  | 1        | 1.16%   |
| Samsung Electronics U32R59x SAM0F96 3840x2160 697x392mm 31.5-inch       | 1        | 1.16%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch       | 1        | 1.16%   |
| Samsung Electronics U28D590 SAM0B81 3840x2160 608x345mm 27.5-inch       | 1        | 1.16%   |
| Samsung Electronics SyncMaster SAM0604 1920x1080                        | 1        | 1.16%   |
| Samsung Electronics SyncMaster SAM0546 1920x1080 510x287mm 23.0-inch    | 1        | 1.16%   |
| Samsung Electronics S27R35A SAM7126 1920x1080 598x336mm 27.0-inch       | 1        | 1.16%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch       | 1        | 1.16%   |
| Samsung Electronics S19D300 SAM0B34 1280x720 410x230mm 18.5-inch        | 1        | 1.16%   |
| Samsung Electronics LCD Monitor SAM7017 3840x2160 1872x1053mm 84.6-inch | 1        | 1.16%   |
| Samsung Electronics LCD Monitor SAM0C3C 1920x1080 700x390mm 31.5-inch   | 1        | 1.16%   |
| Samsung Electronics LCD Monitor SAM0AC6 1920x1080 700x390mm 31.5-inch   | 1        | 1.16%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 1060x626mm 48.5-inch  | 1        | 1.16%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 1020x570mm 46.0-inch  | 1        | 1.16%   |
| Samsung Electronics LCD Monitor SA300/SA350 1920x1080                   | 1        | 1.16%   |
| Samsung Electronics LCD Monitor C27R50x 1920x1080                       | 1        | 1.16%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1190x340mm 48.7-inch      | 1        | 1.16%   |
| Philips PHL 278E9Q PHLC17F 1920x1080 598x336mm 27.0-inch                | 1        | 1.16%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                 | 1        | 1.16%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                 | 1        | 1.16%   |
| Philips LCD Monitor 240B 1920x1200                                      | 1        | 1.16%   |
| Philips LCD Monitor 227EQPH 1920x1080                                   | 1        | 1.16%   |
| NEC Computers LCD Monitor E231W 3840x1080                               | 1        | 1.16%   |
| NEC Computers LCD Monitor E231W                                         | 1        | 1.16%   |
| NEC Computers EA244WMi NEC68D7 1920x1080 520x320mm 24.0-inch            | 1        | 1.16%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                         | 1        | 1.16%   |
| LG Electronics LCD Monitor EW224 1920x1080                              | 1        | 1.16%   |
| LG Electronics LCD Monitor 23MP55 1920x1080                             | 1        | 1.16%   |
| Lenovo LEN T23i-10 LEN61AB 1920x1080 509x286mm 23.0-inch                | 1        | 1.16%   |
| Lenovo D22-20 LEN66AD 1920x1080 477x268mm 21.5-inch                     | 1        | 1.16%   |
| Iiyama PLE2483H IVM6113 1920x1080 531x299mm 24.0-inch                   | 1        | 1.16%   |
| Iiyama PL3461WQ IVM7615 3440x1440 800x335mm 34.1-inch                   | 1        | 1.16%   |
| HPN LCD Monitor HP 24ea 1920x1080                                       | 1        | 1.16%   |
| Hewlett-Packard w17e HWP26E0 1440x900 408x255mm 18.9-inch               | 1        | 1.16%   |
| Hewlett-Packard LCD Monitor w1907 3120x1050                             | 1        | 1.16%   |
| Hewlett-Packard E222 HWP3263 1920x1080 476x268mm 21.5-inch              | 1        | 1.16%   |
| Hewlett-Packard Compaq WF1907 HWP26A5 1440x900 408x255mm 18.9-inch      | 1        | 1.16%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 476x268mm 21.5-inch             | 1        | 1.16%   |
| Goldstar W1942 GSM4B6F 1440x900 408x255mm 18.9-inch                     | 1        | 1.16%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                 | 1        | 1.16%   |
| Goldstar LCD Monitor GSM580C 1680x1050 510x290mm 23.1-inch              | 1        | 1.16%   |
| Goldstar L1950SQ GSM4AD3 1280x1024 376x301mm 19.0-inch                  | 1        | 1.16%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 1        | 1.16%   |
| Goldstar 24GM77 GSM5A92 1920x1080 530x300mm 24.0-inch                   | 1        | 1.16%   |
| Gigabyte Technology G34WQC GBT3400 3440x1440 797x334mm 34.0-inch        | 1        | 1.16%   |
| Gateway VX930 GWY232D 1600x1200 350x262mm 17.2-inch                     | 1        | 1.16%   |
| Fujitsu Siemens LSL 3260W FUS07AE 1920x1200 550x344mm 25.5-inch         | 1        | 1.16%   |
| Dell SE2216H DELF070 1920x1080 476x268mm 21.5-inch                      | 1        | 1.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 40       | 50%     |
| 3840x2160 (4K)     | 10       | 12.5%   |
| Unknown            | 5        | 6.25%   |
| 3840x1080          | 4        | 5%      |
| 1366x768 (WXGA)    | 3        | 3.75%   |
| 3440x1440          | 2        | 2.5%    |
| 1920x1200 (WUXGA)  | 2        | 2.5%    |
| 1680x1050 (WSXGA+) | 2        | 2.5%    |
| 1280x1024 (SXGA)   | 2        | 2.5%    |
| 4160x1440          | 1        | 1.25%   |
| 3120x1050          | 1        | 1.25%   |
| 2560x1440 (QHD)    | 1        | 1.25%   |
| 2464x900           | 1        | 1.25%   |
| 1834x1031          | 1        | 1.25%   |
| 1600x900 (HD+)     | 1        | 1.25%   |
| 1600x1200          | 1        | 1.25%   |
| 1440x900 (WXGA+)   | 1        | 1.25%   |
| 1280x720 (HD)      | 1        | 1.25%   |
| 1024x768 (XGA)     | 1        | 1.25%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 27       | 34.18%  |
| 27      | 8        | 10.13%  |
| 24      | 6        | 7.59%   |
| 21      | 6        | 7.59%   |
| 31      | 5        | 6.33%   |
| 23      | 5        | 6.33%   |
| 19      | 3        | 3.8%    |
| 18      | 3        | 3.8%    |
| 48      | 2        | 2.53%   |
| 34      | 2        | 2.53%   |
| 22      | 2        | 2.53%   |
| 84      | 1        | 1.27%   |
| 46      | 1        | 1.27%   |
| 43      | 1        | 1.27%   |
| 41      | 1        | 1.27%   |
| 40      | 1        | 1.27%   |
| 36      | 1        | 1.27%   |
| 32      | 1        | 1.27%   |
| 25      | 1        | 1.27%   |
| 17      | 1        | 1.27%   |
| 15      | 1        | 1.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| Unknown     | 27       | 35.53%  |
| 501-600     | 17       | 22.37%  |
| 401-500     | 12       | 15.79%  |
| 601-700     | 6        | 7.89%   |
| 701-800     | 4        | 5.26%   |
| 1001-1500   | 3        | 3.95%   |
| 301-350     | 2        | 2.63%   |
| 901-1000    | 2        | 2.63%   |
| 801-900     | 1        | 1.32%   |
| 351-400     | 1        | 1.32%   |
| 1501-2000   | 1        | 1.32%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 35       | 48.61%  |
| Unknown | 26       | 36.11%  |
| 16/10   | 5        | 6.94%   |
| 4/3     | 2        | 2.78%   |
| 21/9    | 2        | 2.78%   |
| 5/4     | 1        | 1.39%   |
| 32/9    | 1        | 1.39%   |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inchÂ² | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 27       | 34.62%  |
| 201-250        | 16       | 20.51%  |
| 351-500        | 8        | 10.26%  |
| 301-350        | 8        | 10.26%  |
| 501-1000       | 6        | 7.69%   |
| 151-200        | 5        | 6.41%   |
| 141-150        | 3        | 3.85%   |
| More than 1000 | 2        | 2.56%   |
| 251-300        | 2        | 2.56%   |
| 101-110        | 1        | 1.28%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 29       | 38.67%  |
| Unknown | 27       | 36%     |
| 101-120 | 10       | 13.33%  |
| 1-50    | 4        | 5.33%   |
| 121-160 | 4        | 5.33%   |
| 161-240 | 1        | 1.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 65       | 82.28%  |
| 2     | 13       | 16.46%  |
| 0     | 1        | 1.27%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 53       | 46.9%   |
| Intel                    | 25       | 22.12%  |
| Qualcomm Atheros         | 9        | 7.96%   |
| TP-Link                  | 6        | 5.31%   |
| Ralink Technology        | 6        | 5.31%   |
| Ralink                   | 3        | 2.65%   |
| Xiaomi                   | 1        | 0.88%   |
| Samsung Electronics      | 1        | 0.88%   |
| Nvidia                   | 1        | 0.88%   |
| NetGear                  | 1        | 0.88%   |
| Motorola PCS             | 1        | 0.88%   |
| Marvell Technology Group | 1        | 0.88%   |
| Linksys                  | 1        | 0.88%   |
| Edimax Technology        | 1        | 0.88%   |
| DisplayLink              | 1        | 0.88%   |
| D-Link System            | 1        | 0.88%   |
| Broadcom                 | 1        | 0.88%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 43       | 33.86%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 7        | 5.51%   |
| Realtek 802.11ac NIC                                                   | 4        | 3.15%   |
| Ralink MT7601U Wireless Adapter                                        | 4        | 3.15%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3        | 2.36%   |
| Intel Ethernet Connection (2) I218-V                                   | 3        | 2.36%   |
| TP-Link 802.11ac WLAN Adapter                                          | 2        | 1.57%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 2        | 1.57%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 2        | 1.57%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 2        | 1.57%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2        | 1.57%   |
| Ralink RT5370 Wireless Adapter                                         | 2        | 1.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 2        | 1.57%   |
| Intel Ethernet Connection I217-LM                                      | 2        | 1.57%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 2        | 1.57%   |
| Intel 82574L Gigabit Network Connection                                | 2        | 1.57%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1        | 0.79%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 1        | 0.79%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 1        | 0.79%   |
| TP-Link Archer T4U ver.3                                               | 1        | 0.79%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                 | 1        | 0.79%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1        | 0.79%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                             | 1        | 0.79%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1        | 0.79%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter               | 1        | 0.79%   |
| Ralink RT5592 PCIe Wireless Network Adapter                            | 1        | 0.79%   |
| Ralink RT2600 802.11 MIMO                                              | 1        | 0.79%   |
| Ralink RT2561/RT61 802.11g PCI                                         | 1        | 0.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 1        | 0.79%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1        | 0.79%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 1        | 0.79%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1        | 0.79%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1        | 0.79%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                          | 1        | 0.79%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1        | 0.79%   |
| Nvidia MCP61 Ethernet                                                  | 1        | 0.79%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]            | 1        | 0.79%   |
| Motorola PCS Moto G (4)                                                | 1        | 0.79%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 1        | 0.79%   |
| Linksys WUSB6300 802.11a/b/g/n/ac Wireless Adapter [Realtek RTL8812AU] | 1        | 0.79%   |
| Intel Wireless-AC 9260                                                 | 1        | 0.79%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                 | 1        | 0.79%   |
| Intel Wi-Fi 6 AX200                                                    | 1        | 0.79%   |
| Intel I211 Gigabit Network Connection                                  | 1        | 0.79%   |
| Intel I210 Gigabit Network Connection                                  | 1        | 0.79%   |
| Intel Ethernet Controller I225-V                                       | 1        | 0.79%   |
| Intel Ethernet Connection I217-V                                       | 1        | 0.79%   |
| Intel Ethernet Connection (7) I219-V                                   | 1        | 0.79%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1        | 0.79%   |
| Intel Ethernet Connection (2) I219-V                                   | 1        | 0.79%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1        | 0.79%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 1        | 0.79%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 1        | 0.79%   |
| Intel 82579V Gigabit Network Connection                                | 1        | 0.79%   |
| Intel 82566DC-2 Gigabit Network Connection                             | 1        | 0.79%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]         | 1        | 0.79%   |
| DisplayLink USB 3.0 Dual Video Dock                                    | 1        | 0.79%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                        | 1        | 0.79%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 1        | 0.79%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 10       | 25.64%  |
| Intel                 | 7        | 17.95%  |
| TP-Link               | 6        | 15.38%  |
| Ralink Technology     | 6        | 15.38%  |
| Qualcomm Atheros      | 4        | 10.26%  |
| Ralink                | 3        | 7.69%   |
| NetGear               | 1        | 2.56%   |
| Linksys               | 1        | 2.56%   |
| Edimax Technology     | 1        | 2.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek 802.11ac NIC                                                   | 4        | 10%     |
| Ralink MT7601U Wireless Adapter                                        | 4        | 10%     |
| TP-Link 802.11ac WLAN Adapter                                          | 2        | 5%      |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 2        | 5%      |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 2        | 5%      |
| Ralink RT5370 Wireless Adapter                                         | 2        | 5%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 2        | 5%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 2        | 5%      |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 1        | 2.5%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 1        | 2.5%    |
| TP-Link Archer T4U ver.3                                               | 1        | 2.5%    |
| TP-Link Archer T3U [Realtek RTL8812BU]                                 | 1        | 2.5%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                             | 1        | 2.5%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1        | 2.5%    |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter               | 1        | 2.5%    |
| Ralink RT5592 PCIe Wireless Network Adapter                            | 1        | 2.5%    |
| Ralink RT2600 802.11 MIMO                                              | 1        | 2.5%    |
| Ralink RT2561/RT61 802.11g PCI                                         | 1        | 2.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 1        | 2.5%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 1        | 2.5%    |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]            | 1        | 2.5%    |
| Linksys WUSB6300 802.11a/b/g/n/ac Wireless Adapter [Realtek RTL8812AU] | 1        | 2.5%    |
| Intel Wireless-AC 9260                                                 | 1        | 2.5%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                 | 1        | 2.5%    |
| Intel Wi-Fi 6 AX200                                                    | 1        | 2.5%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 1        | 2.5%    |
| Intel Comet Lake PCH CNVi WiFi                                         | 1        | 2.5%    |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]         | 1        | 2.5%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 50       | 59.52%  |
| Intel                    | 21       | 25%     |
| Qualcomm Atheros         | 5        | 5.95%   |
| Xiaomi                   | 1        | 1.19%   |
| Samsung Electronics      | 1        | 1.19%   |
| Nvidia                   | 1        | 1.19%   |
| Motorola PCS             | 1        | 1.19%   |
| Marvell Technology Group | 1        | 1.19%   |
| DisplayLink              | 1        | 1.19%   |
| D-Link System            | 1        | 1.19%   |
| Broadcom                 | 1        | 1.19%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 43       | 49.43%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7        | 8.05%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 3.45%   |
| Intel Ethernet Connection (2) I218-V                              | 3        | 3.45%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 2.3%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 2.3%    |
| Intel Ethernet Connection I217-LM                                 | 2        | 2.3%    |
| Intel 82574L Gigabit Network Connection                           | 2        | 2.3%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 1.15%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 1.15%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 1.15%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 1.15%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 1.15%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1        | 1.15%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 1.15%   |
| Nvidia MCP61 Ethernet                                             | 1        | 1.15%   |
| Motorola PCS Moto G (4)                                           | 1        | 1.15%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 1.15%   |
| Intel I211 Gigabit Network Connection                             | 1        | 1.15%   |
| Intel I210 Gigabit Network Connection                             | 1        | 1.15%   |
| Intel Ethernet Controller I225-V                                  | 1        | 1.15%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.15%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.15%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.15%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 1.15%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 1.15%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.15%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1        | 1.15%   |
| DisplayLink USB 3.0 Dual Video Dock                               | 1        | 1.15%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 1.15%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 1.15%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 78       | 69.03%  |
| WiFi     | 35       | 30.97%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 78       | 75%     |
| WiFi     | 26       | 25%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 59       | 75.64%  |
| 2     | 18       | 23.08%  |
| 3     | 1        | 1.28%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 53       | 67.09%  |
| Yes  | 26       | 32.91%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 7        | 28%     |
| Cambridge Silicon Radio         | 6        | 24%     |
| Realtek Semiconductor           | 5        | 20%     |
| Qualcomm Atheros Communications | 2        | 8%      |
| ASUSTek Computer                | 2        | 8%      |
| Lite-On Technology              | 1        | 4%      |
| Dell                            | 1        | 4%      |
| Broadcom                        | 1        | 4%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6        | 24%     |
| Realtek Bluetooth Radio                             | 5        | 20%     |
| Intel Bluetooth Device                              | 5        | 20%     |
| Qualcomm Atheros Bluetooth                          | 1        | 4%      |
| Qualcomm Atheros AR9462 Bluetooth                   | 1        | 4%      |
| Lite-On Bluetooth Device                            | 1        | 4%      |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 4%      |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 4%      |
| Dell BT Mini-Receiver                               | 1        | 4%      |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 4%      |
| ASUS Qualcomm Bluetooth 4.1                         | 1        | 4%      |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 4%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 49       | 35.77%  |
| Nvidia              | 38       | 27.74%  |
| AMD                 | 32       | 23.36%  |
| C-Media Electronics | 4        | 2.92%   |
| JMTek               | 2        | 1.46%   |
| Creative Labs       | 2        | 1.46%   |
| XMOS                | 1        | 0.73%   |
| Texas Instruments   | 1        | 0.73%   |
| Razer USA           | 1        | 0.73%   |
| Numark              | 1        | 0.73%   |
| Logitech            | 1        | 0.73%   |
| Klipsch Audio       | 1        | 0.73%   |
| iConnectivity       | 1        | 0.73%   |
| GN Netcom           | 1        | 0.73%   |
| GEMBIRD             | 1        | 0.73%   |
| Focusrite-Novation  | 1        | 0.73%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 10       | 6.29%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 9        | 5.66%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 8        | 5.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8        | 5.03%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 8        | 5.03%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6        | 3.77%   |
| AMD Starship/Matisse HD Audio Controller                                   | 6        | 3.77%   |
| Nvidia GP106 High Definition Audio Controller                              | 5        | 3.14%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 5        | 3.14%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4        | 2.52%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4        | 2.52%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4        | 2.52%   |
| Nvidia GM204 High Definition Audio Controller                              | 3        | 1.89%   |
| Nvidia GF119 HDMI Audio Controller                                         | 3        | 1.89%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 1.89%   |
| Intel Cannon Lake PCH cAVS                                                 | 3        | 1.89%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3        | 1.89%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3        | 1.89%   |
| AMD FCH Azalia Controller                                                  | 3        | 1.89%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3        | 1.89%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3        | 1.89%   |
| Nvidia TU106 High Definition Audio Controller                              | 2        | 1.26%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2        | 1.26%   |
| JMTek USB PnP Audio Device                                                 | 2        | 1.26%   |
| Intel Comet Lake PCH cAVS                                                  | 2        | 1.26%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 1.26%   |
| C-Media Electronics USB Advanced Audio Device                              | 2        | 1.26%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                     | 2        | 1.26%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2        | 1.26%   |
| XMOS Gustard USB Audio 2.0                                                 | 1        | 0.63%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                          | 1        | 0.63%   |
| Razer USA Razer USB Sound Card                                             | 1        | 0.63%   |
| Razer USA Razer Seiren Mini                                                | 1        | 0.63%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 0.63%   |
| Nvidia TU104 HD Audio Controller                                           | 1        | 0.63%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 0.63%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 0.63%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 0.63%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1        | 0.63%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 0.63%   |
| Nvidia GF110 High Definition Audio Controller                              | 1        | 0.63%   |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 0.63%   |
| Nvidia GF100 High Definition Audio Controller                              | 1        | 0.63%   |
| Nvidia GA102 High Definition Audio Controller                              | 1        | 0.63%   |
| Nvidia Audio device                                                        | 1        | 0.63%   |
| Numark MixTrack Pro                                                        | 1        | 0.63%   |
| Logitech H600 [Wireless Headset]                                           | 1        | 0.63%   |
| Klipsch Audio Klipsch KG-200 Headphones                                    | 1        | 0.63%   |
| Intel Comet Lake PCH-V Smart Sound Technology Audio Controller             | 1        | 0.63%   |
| Intel Audio device                                                         | 1        | 0.63%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1        | 0.63%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 0.63%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1        | 0.63%   |
| Intel 200 Series PCH HD Audio                                              | 1        | 0.63%   |
| iConnectivity mio                                                          | 1        | 0.63%   |
| GN Netcom Jabra Link 370                                                   | 1        | 0.63%   |
| GEMBIRD Multimedia audio controller                                        | 1        | 0.63%   |
| Focusrite-Novation Launchpad Mini                                          | 1        | 0.63%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 1        | 0.63%   |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]                 | 1        | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 3        | 42.86%  |
| Corsair | 2        | 28.57%  |
| Team    | 1        | 14.29%  |
| G.Skill | 1        | 14.29%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM TM44D18UD04MU-NUK 4096MB DIMM DDR4 2400MT/s  | 1        | 11.11%  |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                | 1        | 11.11%  |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 1        | 11.11%  |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s             | 1        | 11.11%  |
| Unknown RAM 04S2400CL17A 4096MB DIMM DDR4 2400MT/s       | 1        | 11.11%  |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 2667MT/s       | 1        | 11.11%  |
| G.Skill RAM F4-3600C19-8GVRB 8192MB DIMM DDR4 2933MT/s   | 1        | 11.11%  |
| Corsair RAM CMW64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s   | 1        | 11.11%  |
| Corsair RAM CMD16GX4M2A2666C15 8192MB DIMM DDR4 2667MT/s | 1        | 11.11%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 5        | 71.43%  |
| DDR3    | 1        | 14.29%  |
| Unknown | 1        | 14.29%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 7        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 4        | 50%     |
| 4096  | 2        | 25%     |
| 32768 | 1        | 12.5%   |
| 2048  | 1        | 12.5%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 2667  | 2        | 28.57%  |
| 1333  | 2        | 28.57%  |
| 3200  | 1        | 14.29%  |
| 2933  | 1        | 14.29%  |
| 2400  | 1        | 14.29%  |

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


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Logitech               | 3        | 30%     |
| Teslong Camera         | 1        | 10%     |
| Razer USA              | 1        | 10%     |
| Microsoft              | 1        | 10%     |
| Microdia               | 1        | 10%     |
| Jieli Technology       | 1        | 10%     |
| Generalplus Technology | 1        | 10%     |
| ARC International      | 1        | 10%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Teslong Camera Teslong Camera        | 1        | 10%     |
| Razer USA Razer Kiyo                 | 1        | 10%     |
| Microsoft Microsoft?‚ LifeCam Cinema | 1        | 10%     |
| Microdia PC Camera (SN9C110)         | 1        | 10%     |
| Logitech Webcam C270                 | 1        | 10%     |
| Logitech HD Webcam C910              | 1        | 10%     |
| Logitech HD Pro Webcam C920          | 1        | 10%     |
| Jieli USB PHY 2.0                    | 1        | 10%     |
| Generalplus GENERAL WEBCAM           | 1        | 10%     |
| ARC International Camera             | 1        | 10%     |

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
| 0     | 63       | 80.77%  |
| 1     | 13       | 16.67%  |
| 2     | 2        | 2.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 10       | 66.67%  |
| Graphics card            | 2        | 13.33%  |
| Sound                    | 1        | 6.67%   |
| Communication controller | 1        | 6.67%   |
| Camera                   | 1        | 6.67%   |

