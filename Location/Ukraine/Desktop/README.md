Linux in Ukraine - Tested Hardware & Statistics (Desktops)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Ukraine.

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

Total: 1923

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [285e8cd1a5](https://linux-hardware.org/?probe=285e8cd1a5) | Oct 25, 2022 |
| Acer          | Aspire X3990                | [e741844a8f](https://linux-hardware.org/?probe=e741844a8f) | Oct 23, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [03d7b75880](https://linux-hardware.org/?probe=03d7b75880) | Oct 21, 2022 |
| ASUSTek       | H97M-PLUS                   | [f094b82a05](https://linux-hardware.org/?probe=f094b82a05) | Oct 17, 2022 |
| Gigabyte      | Z87X-UD5H-CF                | [8d0d1ba821](https://linux-hardware.org/?probe=8d0d1ba821) | Oct 12, 2022 |
| Gigabyte      | B560M AORUS ELITE           | [81e6a3e257](https://linux-hardware.org/?probe=81e6a3e257) | Oct 09, 2022 |
| ASUSTek       | H110M-R                     | [4a6d780641](https://linux-hardware.org/?probe=4a6d780641) | Oct 05, 2022 |
| MSI           | Z87 MPOWER                  | [75177d19fc](https://linux-hardware.org/?probe=75177d19fc) | Oct 04, 2022 |
| ASUSTek       | H110M-R                     | [ad1e756112](https://linux-hardware.org/?probe=ad1e756112) | Oct 03, 2022 |
| ASUSTek       | M4A88TD-M EVO               | [6e0ea7e989](https://linux-hardware.org/?probe=6e0ea7e989) | Oct 03, 2022 |
| MSI           | Z87 MPOWER                  | [092a0bd2e3](https://linux-hardware.org/?probe=092a0bd2e3) | Oct 02, 2022 |
| MSI           | B560M PRO-VDH               | [34db101d55](https://linux-hardware.org/?probe=34db101d55) | Sep 22, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [5b22a32f45](https://linux-hardware.org/?probe=5b22a32f45) | Sep 20, 2022 |
| ASUSTek       | M2A74-AM                    | [25c30e4e54](https://linux-hardware.org/?probe=25c30e4e54) | Sep 14, 2022 |
| ASUSTek       | M2A74-AM                    | [24e6ffe552](https://linux-hardware.org/?probe=24e6ffe552) | Sep 14, 2022 |
| Gigabyte      | F2A55M-S1                   | [a5ce933202](https://linux-hardware.org/?probe=a5ce933202) | Sep 12, 2022 |
| ASUSTek       | PRIME Z390-P                | [80a20ec3fe](https://linux-hardware.org/?probe=80a20ec3fe) | Sep 11, 2022 |
| ECS           | H61H2-M6                    | [99f3146843](https://linux-hardware.org/?probe=99f3146843) | Sep 10, 2022 |
| ASRock        | G41M-VS3                    | [021bcda428](https://linux-hardware.org/?probe=021bcda428) | Sep 10, 2022 |
| Gigabyte      | MSQ87TN-00                  | [af31e1b75a](https://linux-hardware.org/?probe=af31e1b75a) | Sep 04, 2022 |
| Gigabyte      | 970A-DS3P                   | [5ba20eb04b](https://linux-hardware.org/?probe=5ba20eb04b) | Sep 01, 2022 |
| ASUSTek       | F1A75-M-PRO R2.0            | [e7e057dd6d](https://linux-hardware.org/?probe=e7e057dd6d) | Aug 27, 2022 |
| ASRock        | 960GM-VGS3 FX               | [55c4e8059c](https://linux-hardware.org/?probe=55c4e8059c) | Aug 14, 2022 |
| ASUSTek       | M5A97 R2.0                  | [4b083cc768](https://linux-hardware.org/?probe=4b083cc768) | Aug 10, 2022 |
| ASUSTek       | H81M-K                      | [e115d77240](https://linux-hardware.org/?probe=e115d77240) | Aug 07, 2022 |
| ASUSTek       | Z170-P                      | [8ed3ede567](https://linux-hardware.org/?probe=8ed3ede567) | Aug 06, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [e963ce265b](https://linux-hardware.org/?probe=e963ce265b) | Aug 04, 2022 |
| ASRock        | A780LM-S                    | [83b44b9bd6](https://linux-hardware.org/?probe=83b44b9bd6) | Jul 31, 2022 |
| ASRock        | A780LM-S                    | [2a1ce55c1b](https://linux-hardware.org/?probe=2a1ce55c1b) | Jul 31, 2022 |
| ASUSTek       | H81M-K                      | [46201e4773](https://linux-hardware.org/?probe=46201e4773) | Jul 27, 2022 |
| ASUSTek       | M5A78L LE                   | [4ade852983](https://linux-hardware.org/?probe=4ade852983) | Jul 23, 2022 |
| Gigabyte      | P31-DS3L                    | [3b8118fb89](https://linux-hardware.org/?probe=3b8118fb89) | Jul 19, 2022 |
| ASRock        | H61M                        | [6a10cdfa42](https://linux-hardware.org/?probe=6a10cdfa42) | Jul 18, 2022 |
| ASRock        | N68-VS3 UCC                 | [37e5cc640d](https://linux-hardware.org/?probe=37e5cc640d) | Jul 14, 2022 |
| Gigabyte      | H310M H x.x                 | [41c609be91](https://linux-hardware.org/?probe=41c609be91) | Jul 05, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS            | [df4856796e](https://linux-hardware.org/?probe=df4856796e) | Jul 04, 2022 |
| Acer          | Aspire M3910                | [ad06b5a93e](https://linux-hardware.org/?probe=ad06b5a93e) | Jun 28, 2022 |
| ASUSTek       | M5A78L-M LX3                | [0ea9a6be3a](https://linux-hardware.org/?probe=0ea9a6be3a) | Jun 28, 2022 |
| ASUSTek       | M2N-E                       | [47cddfb141](https://linux-hardware.org/?probe=47cddfb141) | Jun 25, 2022 |
| ASUSTek       | M2N-E                       | [ad5514340b](https://linux-hardware.org/?probe=ad5514340b) | Jun 25, 2022 |
| ASRock        | A320M-DVS R3.0              | [9244f4847e](https://linux-hardware.org/?probe=9244f4847e) | Jun 22, 2022 |
| Gigabyte      | B450M DS3H V2               | [684cf228c4](https://linux-hardware.org/?probe=684cf228c4) | Jun 15, 2022 |
| ASRock        | B450M Pro4                  | [041f94473b](https://linux-hardware.org/?probe=041f94473b) | Jun 15, 2022 |
| ASUSTek       | PRIME B560-PLUS             | [246525a65f](https://linux-hardware.org/?probe=246525a65f) | Jun 11, 2022 |
| Gigabyte      | EX58-UD5                    | [ffcbf35eec](https://linux-hardware.org/?probe=ffcbf35eec) | Jun 11, 2022 |
| Intel         | DG33BU AAD79951-407         | [5df0f93da9](https://linux-hardware.org/?probe=5df0f93da9) | Jun 10, 2022 |
| ASRock        | Z87M Extreme4               | [5ca7bb09b0](https://linux-hardware.org/?probe=5ca7bb09b0) | Jun 05, 2022 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [49c5364599](https://linux-hardware.org/?probe=49c5364599) | Jun 04, 2022 |
| ASUSTek       | F1A75-M-PRO R2.0            | [070e59ce1e](https://linux-hardware.org/?probe=070e59ce1e) | May 30, 2022 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [f1ed3c6a46](https://linux-hardware.org/?probe=f1ed3c6a46) | May 30, 2022 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [bcc7398945](https://linux-hardware.org/?probe=bcc7398945) | May 29, 2022 |
| ASUSTek       | B150-PLUS                   | [bdcda1dabc](https://linux-hardware.org/?probe=bdcda1dabc) | May 27, 2022 |
| Gigabyte      | EX58-UD5                    | [0b675c4390](https://linux-hardware.org/?probe=0b675c4390) | May 24, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [63acfbdc55](https://linux-hardware.org/?probe=63acfbdc55) | May 18, 2022 |
| ASUSTek       | P5Q                         | [614f6cf0c6](https://linux-hardware.org/?probe=614f6cf0c6) | May 16, 2022 |
| Gigabyte      | Z97-HD3                     | [2c91bb6c51](https://linux-hardware.org/?probe=2c91bb6c51) | May 16, 2022 |
| Gigabyte      | F2A55M-S1                   | [ecacfd48de](https://linux-hardware.org/?probe=ecacfd48de) | May 14, 2022 |
| ASUSTek       | H110M-R                     | [adbb3eb389](https://linux-hardware.org/?probe=adbb3eb389) | May 12, 2022 |
| ASUSTek       | Q170T                       | [7b142a9bf8](https://linux-hardware.org/?probe=7b142a9bf8) | May 10, 2022 |
| MSI           | X99A SLI PLUS               | [d329ab7f27](https://linux-hardware.org/?probe=d329ab7f27) | May 10, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [1906da1cb4](https://linux-hardware.org/?probe=1906da1cb4) | May 08, 2022 |
| Gigabyte      | H170-D3H-CF                 | [9f255eb7d5](https://linux-hardware.org/?probe=9f255eb7d5) | May 06, 2022 |
| Gigabyte      | IMB1900N                    | [8ed8cb17d5](https://linux-hardware.org/?probe=8ed8cb17d5) | May 04, 2022 |
| Gigabyte      | B75-D3V                     | [08bd0f2662](https://linux-hardware.org/?probe=08bd0f2662) | May 04, 2022 |
| Gigabyte      | H57M-USB3                   | [2f061f5e18](https://linux-hardware.org/?probe=2f061f5e18) | May 03, 2022 |
| Intel         | X79 V2.72B                  | [396faf60b6](https://linux-hardware.org/?probe=396faf60b6) | Apr 29, 2022 |
| Gigabyte      | X570 UD                     | [67f24b974b](https://linux-hardware.org/?probe=67f24b974b) | Apr 27, 2022 |
| Biostar       | G31M+                       | [b756b9bc9f](https://linux-hardware.org/?probe=b756b9bc9f) | Apr 26, 2022 |
| MSI           | MS-7267                     | [d0d0dc78d5](https://linux-hardware.org/?probe=d0d0dc78d5) | Apr 22, 2022 |
| Biostar       | H61MHV2                     | [e05349d6a0](https://linux-hardware.org/?probe=e05349d6a0) | Apr 14, 2022 |
| MSI           | X99A SLI PLUS               | [eae6b5ed56](https://linux-hardware.org/?probe=eae6b5ed56) | Apr 12, 2022 |
| ASUSTek       | A88XM-PLUS                  | [54f7cac3d4](https://linux-hardware.org/?probe=54f7cac3d4) | Apr 11, 2022 |
| MSI           | X99A SLI PLUS               | [f0045560de](https://linux-hardware.org/?probe=f0045560de) | Apr 09, 2022 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [263621f796](https://linux-hardware.org/?probe=263621f796) | Apr 08, 2022 |
| ASRock        | Z270 Extreme4               | [526a5a16bd](https://linux-hardware.org/?probe=526a5a16bd) | Apr 07, 2022 |
| Gigabyte      | H81M-S2H                    | [ac5d29c839](https://linux-hardware.org/?probe=ac5d29c839) | Apr 05, 2022 |
| Dell          | 0CT017                      | [27bdeec11d](https://linux-hardware.org/?probe=27bdeec11d) | Apr 04, 2022 |
| ASUSTek       | P8H61-I                     | [2e1b862b8b](https://linux-hardware.org/?probe=2e1b862b8b) | Mar 28, 2022 |
| Gigabyte      | 945GCM-S2L                  | [c9cc022a93](https://linux-hardware.org/?probe=c9cc022a93) | Mar 28, 2022 |
| Gigabyte      | Z97-HD3                     | [46c12ec623](https://linux-hardware.org/?probe=46c12ec623) | Mar 21, 2022 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [725c0249b8](https://linux-hardware.org/?probe=725c0249b8) | Mar 19, 2022 |
| ASRock        | Z68 Pro3-M                  | [2a053f027f](https://linux-hardware.org/?probe=2a053f027f) | Mar 12, 2022 |
| Gigabyte      | H410M H                     | [13a9aa4fb3](https://linux-hardware.org/?probe=13a9aa4fb3) | Mar 08, 2022 |
| ASRock        | B450 Pro4                   | [9f1edfd714](https://linux-hardware.org/?probe=9f1edfd714) | Mar 07, 2022 |
| ASUSTek       | PRIME H270-PLUS             | [9e62e2e6d8](https://linux-hardware.org/?probe=9e62e2e6d8) | Mar 07, 2022 |
| ASUSTek       | P8H67-M LE                  | [be99e3e64a](https://linux-hardware.org/?probe=be99e3e64a) | Mar 07, 2022 |
| ASUSTek       | P5P43TD                     | [c11fd047fb](https://linux-hardware.org/?probe=c11fd047fb) | Feb 28, 2022 |
| Unknown       | TB-4000                     | [dc43686a5a](https://linux-hardware.org/?probe=dc43686a5a) | Feb 27, 2022 |
| ASRock        | P4i65G                      | [aa7a236464](https://linux-hardware.org/?probe=aa7a236464) | Feb 26, 2022 |
| ASRock        | J4005M                      | [bff0e9d532](https://linux-hardware.org/?probe=bff0e9d532) | Feb 22, 2022 |
| Gigabyte      | H57M-USB3                   | [4c10662fd3](https://linux-hardware.org/?probe=4c10662fd3) | Feb 21, 2022 |
| Pegatron      | EVE                         | [facec46bd5](https://linux-hardware.org/?probe=facec46bd5) | Feb 20, 2022 |
| ASRock        | J4005M                      | [aa149b39ea](https://linux-hardware.org/?probe=aa149b39ea) | Feb 20, 2022 |
| ASUSTek       | M5A78L-M LX3                | [90a12c2aa1](https://linux-hardware.org/?probe=90a12c2aa1) | Feb 20, 2022 |
| Gigabyte      | H410M H                     | [7c32edcf20](https://linux-hardware.org/?probe=7c32edcf20) | Feb 18, 2022 |
| ASRock        | N68-VS3 UCC                 | [f5b5daa4cb](https://linux-hardware.org/?probe=f5b5daa4cb) | Feb 18, 2022 |
| ASUSTek       | PRIME A320M-K               | [e6cca953ed](https://linux-hardware.org/?probe=e6cca953ed) | Feb 18, 2022 |
| ASRock        | H61M-VS                     | [20a40d4eea](https://linux-hardware.org/?probe=20a40d4eea) | Feb 17, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | [e3f921b6a5](https://linux-hardware.org/?probe=e3f921b6a5) | Feb 17, 2022 |
| Dell          | 0FXD80 A00                  | [46450d22d3](https://linux-hardware.org/?probe=46450d22d3) | Feb 17, 2022 |
| ASUSTek       | F1A55-M LX PLUS             | [7de981a63c](https://linux-hardware.org/?probe=7de981a63c) | Feb 17, 2022 |
| Lenovo        | MAHOBAY NOK                 | [4e3b8bfbb1](https://linux-hardware.org/?probe=4e3b8bfbb1) | Feb 16, 2022 |
| MSI           | 870A-G54                    | [3aa654a3fe](https://linux-hardware.org/?probe=3aa654a3fe) | Feb 14, 2022 |
| ASUSTek       | P5QL/EPU                    | [2a5bcaeec9](https://linux-hardware.org/?probe=2a5bcaeec9) | Feb 14, 2022 |
| ASUSTek       | P5K SE/EPU                  | [003f3cafc0](https://linux-hardware.org/?probe=003f3cafc0) | Feb 13, 2022 |
| ASRock        | 970A-G                      | [7b3694013f](https://linux-hardware.org/?probe=7b3694013f) | Feb 13, 2022 |
| ASUSTek       | M5A78L-M LE                 | [341f21c92c](https://linux-hardware.org/?probe=341f21c92c) | Feb 13, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [2038767b43](https://linux-hardware.org/?probe=2038767b43) | Feb 12, 2022 |
| ASUSTek       | PRIME A320M-K               | [5f4de1e2b0](https://linux-hardware.org/?probe=5f4de1e2b0) | Feb 12, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [a98c8db3ad](https://linux-hardware.org/?probe=a98c8db3ad) | Feb 12, 2022 |
| ASUSTek       | P8Z68-V PRO GEN3            | [9637033a52](https://linux-hardware.org/?probe=9637033a52) | Feb 12, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [c2a1175605](https://linux-hardware.org/?probe=c2a1175605) | Feb 12, 2022 |
| Gigabyte      | EP45-DS3L                   | [9829aba3d7](https://linux-hardware.org/?probe=9829aba3d7) | Feb 10, 2022 |
| ASUSTek       | P8H61                       | [ee693a0a41](https://linux-hardware.org/?probe=ee693a0a41) | Feb 10, 2022 |
| ASUSTek       | PRIME B450M-K               | [dbb1d3b9dd](https://linux-hardware.org/?probe=dbb1d3b9dd) | Feb 09, 2022 |
| ASRock        | N68C-GS UCC                 | [42dfb79217](https://linux-hardware.org/?probe=42dfb79217) | Feb 09, 2022 |
| ASUSTek       | P8B75-V                     | [fd04c0293f](https://linux-hardware.org/?probe=fd04c0293f) | Feb 08, 2022 |
| Acer          | Aspire TC-780               | [96ab8fecfb](https://linux-hardware.org/?probe=96ab8fecfb) | Feb 08, 2022 |
| ASUSTek       | M4A78L-M LE                 | [06fca38713](https://linux-hardware.org/?probe=06fca38713) | Feb 08, 2022 |
| ASUSTek       | H81M-K                      | [e362930c92](https://linux-hardware.org/?probe=e362930c92) | Feb 08, 2022 |
| Gigabyte      | B450M GAMING                | [16aaa53716](https://linux-hardware.org/?probe=16aaa53716) | Feb 07, 2022 |
| ASUSTek       | M2NPV-VM                    | [2d4a85af0e](https://linux-hardware.org/?probe=2d4a85af0e) | Feb 07, 2022 |
| ASUSTek       | P5K SE                      | [4c53e240bc](https://linux-hardware.org/?probe=4c53e240bc) | Feb 07, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [72a1b5ae56](https://linux-hardware.org/?probe=72a1b5ae56) | Feb 07, 2022 |
| Foxconn       | M61PMV FAB A1               | [1a31d1ca9f](https://linux-hardware.org/?probe=1a31d1ca9f) | Feb 06, 2022 |
| MSI           | Z77A-GD65 GAMING            | [8d2cf11a20](https://linux-hardware.org/?probe=8d2cf11a20) | Feb 06, 2022 |
| MSI           | B450-A PRO MAX              | [95c601fd3e](https://linux-hardware.org/?probe=95c601fd3e) | Feb 05, 2022 |
| ASUSTek       | P5L1394                     | [4969e4fecb](https://linux-hardware.org/?probe=4969e4fecb) | Feb 02, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [f1062af79c](https://linux-hardware.org/?probe=f1062af79c) | Feb 01, 2022 |
| Biostar       | NF560-A2G                   | [49802d698d](https://linux-hardware.org/?probe=49802d698d) | Feb 01, 2022 |
| Seco          | C40 C                       | [acbee1977b](https://linux-hardware.org/?probe=acbee1977b) | Feb 01, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [f54779e17e](https://linux-hardware.org/?probe=f54779e17e) | Jan 30, 2022 |
| ASRock        | H81M-DGS                    | [05fc3bd63b](https://linux-hardware.org/?probe=05fc3bd63b) | Jan 29, 2022 |
| ASUSTek       | P8Z68-V PRO                 | [c8c3cf77c4](https://linux-hardware.org/?probe=c8c3cf77c4) | Jan 29, 2022 |
| ASUSTek       | P5QL/EPU                    | [c1e858090a](https://linux-hardware.org/?probe=c1e858090a) | Jan 28, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [83cdfa61a4](https://linux-hardware.org/?probe=83cdfa61a4) | Jan 28, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [4ba7714220](https://linux-hardware.org/?probe=4ba7714220) | Jan 27, 2022 |
| ASUSTek       | M5A78L-M LX3                | [f34ec65c4f](https://linux-hardware.org/?probe=f34ec65c4f) | Jan 27, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [2aff79c6af](https://linux-hardware.org/?probe=2aff79c6af) | Jan 25, 2022 |
| Gigabyte      | H57M-USB3                   | [6210f4db07](https://linux-hardware.org/?probe=6210f4db07) | Jan 25, 2022 |
| Lenovo        | 3717 NO DPK                 | [7c0b9aaab5](https://linux-hardware.org/?probe=7c0b9aaab5) | Jan 24, 2022 |
| Foxconn       | 2ABF                        | [e5723eaa42](https://linux-hardware.org/?probe=e5723eaa42) | Jan 23, 2022 |
| ASUSTek       | H81M-R                      | [d324ae2959](https://linux-hardware.org/?probe=d324ae2959) | Jan 22, 2022 |
| Foxconn       | 2ABF                        | [af38735785](https://linux-hardware.org/?probe=af38735785) | Jan 22, 2022 |
| ASRock        | H310CM-HDV                  | [39cfe3259d](https://linux-hardware.org/?probe=39cfe3259d) | Jan 22, 2022 |
| ASRock        | H310CM-HDV                  | [2bae4483c9](https://linux-hardware.org/?probe=2bae4483c9) | Jan 21, 2022 |
| MSI           | PRO Z690-A DDR4             | [b69ed1da65](https://linux-hardware.org/?probe=b69ed1da65) | Jan 20, 2022 |
| ASUSTek       | Q170T                       | [5712025f97](https://linux-hardware.org/?probe=5712025f97) | Jan 19, 2022 |
| ASUSTek       | H81M-E                      | [0cf59407cd](https://linux-hardware.org/?probe=0cf59407cd) | Jan 17, 2022 |
| ASUSTek       | P5KPL-AM                    | [4f313ddd6a](https://linux-hardware.org/?probe=4f313ddd6a) | Jan 17, 2022 |
| ASUSTek       | Q170T                       | [6538d8f8be](https://linux-hardware.org/?probe=6538d8f8be) | Jan 15, 2022 |
| ASRock        | FM2A88X Pro3+               | [3b7ba9382f](https://linux-hardware.org/?probe=3b7ba9382f) | Jan 15, 2022 |
| Gigabyte      | Z390 UD V2                  | [e9207f1244](https://linux-hardware.org/?probe=e9207f1244) | Jan 13, 2022 |
| MSI           | PRO Z690-A DDR4             | [8b1d1eb56c](https://linux-hardware.org/?probe=8b1d1eb56c) | Jan 12, 2022 |
| ASUSTek       | M5A78L-M LX3                | [9046bc1e4a](https://linux-hardware.org/?probe=9046bc1e4a) | Jan 11, 2022 |
| Dell          | 0D6H9T A01                  | [8bc2b6cc7c](https://linux-hardware.org/?probe=8bc2b6cc7c) | Jan 09, 2022 |
| ASUSTek       | PRIME A320M-K               | [e5b5e85b94](https://linux-hardware.org/?probe=e5b5e85b94) | Jan 07, 2022 |
| ASUSTek       | H110M-R                     | [fb66ba0eeb](https://linux-hardware.org/?probe=fb66ba0eeb) | Jan 05, 2022 |
| Gigabyte      | Z87X-UD5H-CF                | [a1a7854f7a](https://linux-hardware.org/?probe=a1a7854f7a) | Jan 04, 2022 |
| Gigabyte      | 970A-DS3P FX                | [c6baa48783](https://linux-hardware.org/?probe=c6baa48783) | Jan 03, 2022 |
| ASUSTek       | P5G41T-M LX3                | [2a3dbdc07a](https://linux-hardware.org/?probe=2a3dbdc07a) | Jan 01, 2022 |
| MSI           | 970 GAMING                  | [c5797ca176](https://linux-hardware.org/?probe=c5797ca176) | Dec 30, 2021 |
| Dell          | 0DFRFW A00                  | [f27e8a7f9e](https://linux-hardware.org/?probe=f27e8a7f9e) | Dec 30, 2021 |
| ASRock        | J4105M                      | [37f37bbbfd](https://linux-hardware.org/?probe=37f37bbbfd) | Dec 28, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [425784d870](https://linux-hardware.org/?probe=425784d870) | Dec 28, 2021 |
| Gigabyte      | Z97-HD3                     | [6b3bff90d6](https://linux-hardware.org/?probe=6b3bff90d6) | Dec 28, 2021 |
| Biostar       | H55A+                       | [0a4141bcc2](https://linux-hardware.org/?probe=0a4141bcc2) | Dec 28, 2021 |
| ECS           | H61H2-M6                    | [da70905a9d](https://linux-hardware.org/?probe=da70905a9d) | Dec 24, 2021 |
| Intel         | X79 V1.3                    | [fbd3ea5fee](https://linux-hardware.org/?probe=fbd3ea5fee) | Dec 23, 2021 |
| HP            | 198E                        | [bb9b36a65b](https://linux-hardware.org/?probe=bb9b36a65b) | Dec 22, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [dd197ecb62](https://linux-hardware.org/?probe=dd197ecb62) | Dec 21, 2021 |
| ASUSTek       | PRIME H270-PLUS             | [9c1cf57d74](https://linux-hardware.org/?probe=9c1cf57d74) | Dec 20, 2021 |
| MSI           | X370 SLI PLUS               | [adb27f9347](https://linux-hardware.org/?probe=adb27f9347) | Dec 19, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [dc5f8e3963](https://linux-hardware.org/?probe=dc5f8e3963) | Dec 17, 2021 |
| ASUSTek       | PRIME B360M-A               | [d34989fcaa](https://linux-hardware.org/?probe=d34989fcaa) | Dec 16, 2021 |
| ASUSTek       | PRIME B360M-A               | [7587f8f78a](https://linux-hardware.org/?probe=7587f8f78a) | Dec 16, 2021 |
| ASUSTek       | M2N68-AM SE2                | [0b7832c8d4](https://linux-hardware.org/?probe=0b7832c8d4) | Dec 16, 2021 |
| Biostar       | H61MLC                      | [ff1c843adf](https://linux-hardware.org/?probe=ff1c843adf) | Dec 15, 2021 |
| ASUSTek       | P5GC-MX/1333                | [64d0453982](https://linux-hardware.org/?probe=64d0453982) | Dec 15, 2021 |
| Gigabyte      | G41M-Combo                  | [666796bd7e](https://linux-hardware.org/?probe=666796bd7e) | Dec 12, 2021 |
| ASUSTek       | B150M-C                     | [f2f2c5cb49](https://linux-hardware.org/?probe=f2f2c5cb49) | Dec 10, 2021 |
| ASRock        | X570 Taichi                 | [b2de2f8f6a](https://linux-hardware.org/?probe=b2de2f8f6a) | Dec 10, 2021 |
| ASUSTek       | M2N68-AM SE2                | [623b76cf55](https://linux-hardware.org/?probe=623b76cf55) | Dec 09, 2021 |
| MSI           | B450 TOMAHAWK               | [4b39700892](https://linux-hardware.org/?probe=4b39700892) | Dec 09, 2021 |
| ASUSTek       | PRIME Z370-P                | [a9cb8442ac](https://linux-hardware.org/?probe=a9cb8442ac) | Dec 08, 2021 |
| ASRock        | N68C-GS UCC                 | [9da859a341](https://linux-hardware.org/?probe=9da859a341) | Dec 08, 2021 |
| ASUSTek       | B150M-C                     | [a3e2cda715](https://linux-hardware.org/?probe=a3e2cda715) | Dec 07, 2021 |
| Gigabyte      | P55-USB3                    | [6cbec7b450](https://linux-hardware.org/?probe=6cbec7b450) | Dec 06, 2021 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [0a69990530](https://linux-hardware.org/?probe=0a69990530) | Dec 05, 2021 |
| ASUSTek       | A8N5X                       | [69533e4c80](https://linux-hardware.org/?probe=69533e4c80) | Dec 05, 2021 |
| ABIT          | AN52                        | [c77f120f57](https://linux-hardware.org/?probe=c77f120f57) | Dec 05, 2021 |
| ASUSTek       | M4A87TD/USB3                | [6550b760b5](https://linux-hardware.org/?probe=6550b760b5) | Dec 05, 2021 |
| ASUSTek       | PRIME Z270-P                | [dea0e367e1](https://linux-hardware.org/?probe=dea0e367e1) | Dec 04, 2021 |
| Gigabyte      | 970A-DS3P                   | [4ad98be831](https://linux-hardware.org/?probe=4ad98be831) | Dec 02, 2021 |
| Gigabyte      | Z390 UD V2                  | [c45fd8b141](https://linux-hardware.org/?probe=c45fd8b141) | Dec 02, 2021 |
| MSI           | B150M MORTAR                | [cb85954441](https://linux-hardware.org/?probe=cb85954441) | Dec 02, 2021 |
| MSI           | 0AB8                        | [4bf8e40af9](https://linux-hardware.org/?probe=4bf8e40af9) | Dec 01, 2021 |
| ECS           | H61H2-M6                    | [e044b4f23e](https://linux-hardware.org/?probe=e044b4f23e) | Nov 30, 2021 |
| ASUSTek       | PRIME B365M-A               | [c7cbb50843](https://linux-hardware.org/?probe=c7cbb50843) | Nov 30, 2021 |
| MSI           | 760GM-P23                   | [1e66a980fc](https://linux-hardware.org/?probe=1e66a980fc) | Nov 30, 2021 |
| ASUSTek       | P8Z77-V DELUXE              | [ab1b265412](https://linux-hardware.org/?probe=ab1b265412) | Nov 29, 2021 |
| ASUSTek       | P7P55D                      | [85f288d39b](https://linux-hardware.org/?probe=85f288d39b) | Nov 29, 2021 |
| ASUSTek       | M2N                         | [f76f2473ac](https://linux-hardware.org/?probe=f76f2473ac) | Nov 28, 2021 |
| ASRock        | A320M-HDV R3.0              | [5df73b5935](https://linux-hardware.org/?probe=5df73b5935) | Nov 28, 2021 |
| Gigabyte      | B450M S2H V2                | [caf3c5f8f2](https://linux-hardware.org/?probe=caf3c5f8f2) | Nov 25, 2021 |
| ASUSTek       | P5QL-VM EPU                 | [1331462ff8](https://linux-hardware.org/?probe=1331462ff8) | Nov 25, 2021 |
| ASUSTek       | PRIME A320M-K               | [2b85ea4d74](https://linux-hardware.org/?probe=2b85ea4d74) | Nov 25, 2021 |
| HP            | 834F                        | [ee1361ee2f](https://linux-hardware.org/?probe=ee1361ee2f) | Nov 25, 2021 |
| Gigabyte      | B450M S2H V2                | [ea4dbbbf15](https://linux-hardware.org/?probe=ea4dbbbf15) | Nov 25, 2021 |
| ASUSTek       | M5A78L-M LX3                | [5d13ed6397](https://linux-hardware.org/?probe=5d13ed6397) | Nov 22, 2021 |
| MSI           | B450M-A PRO MAX             | [92375d0ecc](https://linux-hardware.org/?probe=92375d0ecc) | Nov 21, 2021 |
| ASUSTek       | P5QL-VM EPU                 | [cd70e0831d](https://linux-hardware.org/?probe=cd70e0831d) | Nov 19, 2021 |
| Gigabyte      | 945GCMX-S2                  | [709a24d01f](https://linux-hardware.org/?probe=709a24d01f) | Nov 19, 2021 |
| ASUSTek       | M5A97 EVO R2.0              | [f72f0b000f](https://linux-hardware.org/?probe=f72f0b000f) | Nov 19, 2021 |
| MSI           | 970 GAMING                  | [e08a7ab20c](https://linux-hardware.org/?probe=e08a7ab20c) | Nov 18, 2021 |
| ASUSTek       | D500SA                      | [7d7e6c76f2](https://linux-hardware.org/?probe=7d7e6c76f2) | Nov 18, 2021 |
| ASUSTek       | D500SA                      | [eb06af468d](https://linux-hardware.org/?probe=eb06af468d) | Nov 18, 2021 |
| ASUSTek       | M2N                         | [ba2f298ff6](https://linux-hardware.org/?probe=ba2f298ff6) | Nov 18, 2021 |
| Gigabyte      | B560M DS3H                  | [5622f1a3b7](https://linux-hardware.org/?probe=5622f1a3b7) | Nov 17, 2021 |
| ASUSTek       | P5GC-MX/1333                | [def67fa4e7](https://linux-hardware.org/?probe=def67fa4e7) | Nov 16, 2021 |
| Gigabyte      | 945GCMX-S2                  | [dbcdfd8eef](https://linux-hardware.org/?probe=dbcdfd8eef) | Nov 15, 2021 |
| ASUSTek       | P5VD2-MX                    | [2159202a53](https://linux-hardware.org/?probe=2159202a53) | Nov 12, 2021 |
| ASUSTek       | P5QL-VM EPU                 | [91ee92932b](https://linux-hardware.org/?probe=91ee92932b) | Nov 10, 2021 |
| MSI           | 970 GAMING                  | [dd0ca535f4](https://linux-hardware.org/?probe=dd0ca535f4) | Nov 10, 2021 |
| ASUSTek       | P5L1394                     | [77429f6d4e](https://linux-hardware.org/?probe=77429f6d4e) | Nov 10, 2021 |
| MSI           | 970 GAMING                  | [dd576aec32](https://linux-hardware.org/?probe=dd576aec32) | Nov 10, 2021 |
| ASRock        | AB350 Gaming K4             | [618e78d70c](https://linux-hardware.org/?probe=618e78d70c) | Nov 08, 2021 |
| ASUSTek       | M4A78LT-M LX                | [417b74c746](https://linux-hardware.org/?probe=417b74c746) | Nov 07, 2021 |
| MSI           | Z370-A PRO                  | [5b4e37e135](https://linux-hardware.org/?probe=5b4e37e135) | Nov 06, 2021 |
| ASUSTek       | M4A89GTD-PRO                | [4964ad307b](https://linux-hardware.org/?probe=4964ad307b) | Nov 06, 2021 |
| ASRock        | H81M-DG4                    | [33d4154b93](https://linux-hardware.org/?probe=33d4154b93) | Nov 06, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [c1b8176c1c](https://linux-hardware.org/?probe=c1b8176c1c) | Nov 06, 2021 |
| MSI           | A320M-A PRO MAX             | [bfe89af8ab](https://linux-hardware.org/?probe=bfe89af8ab) | Nov 04, 2021 |
| ASUSTek       | M5A78L-M LX3                | [94d9e3af73](https://linux-hardware.org/?probe=94d9e3af73) | Nov 04, 2021 |
| ASUSTek       | P5QL-VM EPU                 | [dff36c2e91](https://linux-hardware.org/?probe=dff36c2e91) | Nov 03, 2021 |
| ASUSTek       | PRIME B360M-A               | [e8ef49b867](https://linux-hardware.org/?probe=e8ef49b867) | Nov 03, 2021 |
| ECS           | H61H2-M6                    | [703edac8b2](https://linux-hardware.org/?probe=703edac8b2) | Nov 02, 2021 |
| Pegatron      | IPPCR-SS                    | [0179d16327](https://linux-hardware.org/?probe=0179d16327) | Nov 02, 2021 |
| MSI           | B250 GAMING M3              | [0d30aebcbf](https://linux-hardware.org/?probe=0d30aebcbf) | Nov 01, 2021 |
| ASUSTek       | M2N-E                       | [775aeb5400](https://linux-hardware.org/?probe=775aeb5400) | Oct 31, 2021 |
| Gigabyte      | H55N-USB3                   | [02dffbfea8](https://linux-hardware.org/?probe=02dffbfea8) | Oct 30, 2021 |
| MSI           | X370 GAMING PRO CARBON      | [3abf73fb8a](https://linux-hardware.org/?probe=3abf73fb8a) | Oct 30, 2021 |
| ASUSTek       | M2N-E                       | [6f6e2fefcb](https://linux-hardware.org/?probe=6f6e2fefcb) | Oct 30, 2021 |
| ASUSTek       | H110M-R                     | [07067fe66c](https://linux-hardware.org/?probe=07067fe66c) | Oct 29, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [df0c058313](https://linux-hardware.org/?probe=df0c058313) | Oct 28, 2021 |
| HP            | 3647h                       | [2db1dbef9f](https://linux-hardware.org/?probe=2db1dbef9f) | Oct 28, 2021 |
| Intel         | D945GCPE AAD97209-201       | [26a126da3e](https://linux-hardware.org/?probe=26a126da3e) | Oct 26, 2021 |
| MSI           | A320M GRENADE               | [bb422d7efe](https://linux-hardware.org/?probe=bb422d7efe) | Oct 24, 2021 |
| HP            | 1906                        | [62c3738cf9](https://linux-hardware.org/?probe=62c3738cf9) | Oct 23, 2021 |
| ASUSTek       | P5B-Deluxe                  | [7c56a7a321](https://linux-hardware.org/?probe=7c56a7a321) | Oct 23, 2021 |
| ASUSTek       | P7H55-M LX                  | [c29ee7ca9f](https://linux-hardware.org/?probe=c29ee7ca9f) | Oct 23, 2021 |
| MSI           | B450-A PRO MAX              | [648098ebf7](https://linux-hardware.org/?probe=648098ebf7) | Oct 23, 2021 |
| Acer          | WG43M                       | [f4e981b2c3](https://linux-hardware.org/?probe=f4e981b2c3) | Oct 22, 2021 |
| HP            | 1906                        | [6ed76a9994](https://linux-hardware.org/?probe=6ed76a9994) | Oct 21, 2021 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [cedb153d12](https://linux-hardware.org/?probe=cedb153d12) | Oct 21, 2021 |
| ASUSTek       | P7H55-M LX                  | [4b9b11b7b3](https://linux-hardware.org/?probe=4b9b11b7b3) | Oct 20, 2021 |
| Gigabyte      | P35-DS3R                    | [01145b2627](https://linux-hardware.org/?probe=01145b2627) | Oct 18, 2021 |
| Intel         | X79G V2.x                   | [6e4d8a1bd8](https://linux-hardware.org/?probe=6e4d8a1bd8) | Oct 17, 2021 |
| ASRock        | 970 Extreme4                | [0a65b6d93e](https://linux-hardware.org/?probe=0a65b6d93e) | Oct 15, 2021 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [1a088aa55a](https://linux-hardware.org/?probe=1a088aa55a) | Oct 15, 2021 |
| ASRock        | N68-VS3 UCC                 | [4d34b74685](https://linux-hardware.org/?probe=4d34b74685) | Oct 13, 2021 |
| ASUSTek       | SABERTOOTH 990FX            | [4581d872f7](https://linux-hardware.org/?probe=4581d872f7) | Oct 12, 2021 |
| ASRock        | G31M-VS                     | [0c8b706839](https://linux-hardware.org/?probe=0c8b706839) | Oct 11, 2021 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [e776648230](https://linux-hardware.org/?probe=e776648230) | Oct 11, 2021 |
| HP            | 1589                        | [46c635d9ab](https://linux-hardware.org/?probe=46c635d9ab) | Oct 10, 2021 |
| ASUSTek       | PRIME H410M-K               | [67ba4012a3](https://linux-hardware.org/?probe=67ba4012a3) | Oct 09, 2021 |
| ASRock        | B75 Pro3-M                  | [62522e187a](https://linux-hardware.org/?probe=62522e187a) | Oct 09, 2021 |
| Fujitsu       | D3162-B1 S26361-D3162-B1    | [5cb0ac4fda](https://linux-hardware.org/?probe=5cb0ac4fda) | Oct 08, 2021 |
| ASRock        | G31M-VS                     | [17021380ec](https://linux-hardware.org/?probe=17021380ec) | Oct 08, 2021 |
| Fujitsu       | D3162-B1 S26361-D3162-B1    | [c8950610f7](https://linux-hardware.org/?probe=c8950610f7) | Oct 08, 2021 |
| ASUSTek       | P8H61-MX                    | [7aee651d14](https://linux-hardware.org/?probe=7aee651d14) | Oct 02, 2021 |
| Biostar       | A770L3                      | [f2cada0c21](https://linux-hardware.org/?probe=f2cada0c21) | Oct 02, 2021 |
| ASRock        | H110M-DGS R3.0              | [2000cd0457](https://linux-hardware.org/?probe=2000cd0457) | Oct 01, 2021 |
| Gigabyte      | H110M-S2-CF                 | [e32907f808](https://linux-hardware.org/?probe=e32907f808) | Oct 01, 2021 |
| Gigabyte      | GA-78LMT-S2                 | [3977fe7bd2](https://linux-hardware.org/?probe=3977fe7bd2) | Sep 29, 2021 |
| Gigabyte      | H170-D3H-CF                 | [42784959b9](https://linux-hardware.org/?probe=42784959b9) | Sep 28, 2021 |
| ASUSTek       | P8Z77-V DELUXE              | [8c1b272056](https://linux-hardware.org/?probe=8c1b272056) | Sep 27, 2021 |
| ASUSTek       | P8Z77-V DELUXE              | [9ebf40dd91](https://linux-hardware.org/?probe=9ebf40dd91) | Sep 27, 2021 |
| ASRock        | X399M Taichi                | [eba541c6b9](https://linux-hardware.org/?probe=eba541c6b9) | Sep 25, 2021 |
| ASUSTek       | M2N-E                       | [6ee658b67a](https://linux-hardware.org/?probe=6ee658b67a) | Sep 25, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [aa7607a2b7](https://linux-hardware.org/?probe=aa7607a2b7) | Sep 24, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [6dad1e6449](https://linux-hardware.org/?probe=6dad1e6449) | Sep 24, 2021 |
| ASRock        | P41C-DE                     | [1db6c915d2](https://linux-hardware.org/?probe=1db6c915d2) | Sep 24, 2021 |
| Gigabyte      | 945GCMX-S2                  | [adc4b6963d](https://linux-hardware.org/?probe=adc4b6963d) | Sep 24, 2021 |
| Gigabyte      | B550 AORUS PRO V2           | [1b83642f22](https://linux-hardware.org/?probe=1b83642f22) | Sep 23, 2021 |
| Gigabyte      | B550 AORUS PRO V2           | [e91ed1214e](https://linux-hardware.org/?probe=e91ed1214e) | Sep 23, 2021 |
| Gigabyte      | H77-D3H                     | [88d1a0c19e](https://linux-hardware.org/?probe=88d1a0c19e) | Sep 22, 2021 |
| MSI           | H270 GAMING M3              | [3cd206163b](https://linux-hardware.org/?probe=3cd206163b) | Sep 21, 2021 |
| Biostar       | AM1ML                       | [dd9c920c24](https://linux-hardware.org/?probe=dd9c920c24) | Sep 21, 2021 |
| Fujitsu       | D3064-A1 S26361-D3064-A1    | [23a2576fa8](https://linux-hardware.org/?probe=23a2576fa8) | Sep 20, 2021 |
| MSI           | 0AB8                        | [613aa45d0a](https://linux-hardware.org/?probe=613aa45d0a) | Sep 14, 2021 |
| MSI           | B360M PRO-VD                | [4672f48ccd](https://linux-hardware.org/?probe=4672f48ccd) | Sep 13, 2021 |
| Intel         | BTC-S37                     | [7915f6eae4](https://linux-hardware.org/?probe=7915f6eae4) | Sep 11, 2021 |
| ECS           | H61H2-M6                    | [b4a203ac5e](https://linux-hardware.org/?probe=b4a203ac5e) | Sep 10, 2021 |
| ASUSTek       | P5KPL-AM                    | [ecd516a1e0](https://linux-hardware.org/?probe=ecd516a1e0) | Sep 09, 2021 |
| ASUSTek       | P5QC                        | [fee02db17d](https://linux-hardware.org/?probe=fee02db17d) | Sep 08, 2021 |
| ASUSTek       | STRIX B250H GAMING          | [265822ee2e](https://linux-hardware.org/?probe=265822ee2e) | Sep 06, 2021 |
| ASUSTek       | P8Z77-M PRO                 | [b2af983536](https://linux-hardware.org/?probe=b2af983536) | Sep 06, 2021 |
| ASUSTek       | P8Z77-M PRO                 | [f6595cb3ab](https://linux-hardware.org/?probe=f6595cb3ab) | Sep 06, 2021 |
| ASUSTek       | P8Z77-V DELUXE              | [85860b751d](https://linux-hardware.org/?probe=85860b751d) | Sep 04, 2021 |
| Dell          | 02N3WF A01                  | [438ea99933](https://linux-hardware.org/?probe=438ea99933) | Sep 02, 2021 |
| Huanan        | X99-F8                      | [67f35844cd](https://linux-hardware.org/?probe=67f35844cd) | Sep 01, 2021 |
| Huanan        | X99-F8                      | [33e8040986](https://linux-hardware.org/?probe=33e8040986) | Aug 31, 2021 |
| Huanan        | X99-F8                      | [adc113ad6f](https://linux-hardware.org/?probe=adc113ad6f) | Aug 31, 2021 |
| ASRock        | H61M-HVGS                   | [1891b3e9ed](https://linux-hardware.org/?probe=1891b3e9ed) | Aug 31, 2021 |
| Unknown       | Unknown                     | [356d160178](https://linux-hardware.org/?probe=356d160178) | Aug 31, 2021 |
| Gigabyte      | 945GCMX-S2                  | [f3d68ec126](https://linux-hardware.org/?probe=f3d68ec126) | Aug 27, 2021 |
| ASRock        | P4i65G                      | [43ce3e711f](https://linux-hardware.org/?probe=43ce3e711f) | Aug 24, 2021 |
| Lenovo        | SDK0J40705 WIN 342504252... | [5141221da1](https://linux-hardware.org/?probe=5141221da1) | Aug 24, 2021 |
| ASUSTek       | GA35DX                      | [3843ea048e](https://linux-hardware.org/?probe=3843ea048e) | Aug 24, 2021 |
| HP            | 1589                        | [4d308c9d28](https://linux-hardware.org/?probe=4d308c9d28) | Aug 23, 2021 |
| MSI           | Z270-A PRO                  | [73b14ecca0](https://linux-hardware.org/?probe=73b14ecca0) | Aug 23, 2021 |
| ECS           | H81H3-M3                    | [1ef75e65b1](https://linux-hardware.org/?probe=1ef75e65b1) | Aug 22, 2021 |
| ECS           | H81H3-M3                    | [07cf30b2f6](https://linux-hardware.org/?probe=07cf30b2f6) | Aug 21, 2021 |
| MSI           | X370 SLI PLUS               | [4a611b712a](https://linux-hardware.org/?probe=4a611b712a) | Aug 21, 2021 |
| MSI           | Z270-A PRO                  | [e59c9482f6](https://linux-hardware.org/?probe=e59c9482f6) | Aug 21, 2021 |
| ASRock        | H61M-VG3                    | [7e1f4b1620](https://linux-hardware.org/?probe=7e1f4b1620) | Aug 20, 2021 |
| ASRock        | H61M-VG3                    | [7257c7b0bb](https://linux-hardware.org/?probe=7257c7b0bb) | Aug 20, 2021 |
| Gigabyte      | B450M DS3H V2               | [2a277158ef](https://linux-hardware.org/?probe=2a277158ef) | Aug 19, 2021 |
| ASUSTek       | M2N                         | [feb08a099a](https://linux-hardware.org/?probe=feb08a099a) | Aug 19, 2021 |
| ECS           | H61H2-M6                    | [89267dacbf](https://linux-hardware.org/?probe=89267dacbf) | Aug 19, 2021 |
| Gigabyte      | H81M-S2H                    | [894c915ecc](https://linux-hardware.org/?probe=894c915ecc) | Aug 17, 2021 |
| ASRock        | FM2A68M-DG3+                | [d04f948953](https://linux-hardware.org/?probe=d04f948953) | Aug 17, 2021 |
| Gigabyte      | 945GCMX-S2                  | [0c58808ea0](https://linux-hardware.org/?probe=0c58808ea0) | Aug 17, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | [1a371ea24e](https://linux-hardware.org/?probe=1a371ea24e) | Aug 16, 2021 |
| ASUSTek       | STRIX B250H GAMING          | [88160f850f](https://linux-hardware.org/?probe=88160f850f) | Aug 15, 2021 |
| ASUSTek       | M5A78L-M LX3                | [16dc0450e2](https://linux-hardware.org/?probe=16dc0450e2) | Aug 15, 2021 |
| ASUSTek       | M5A78L-M LX3                | [48c2b7a173](https://linux-hardware.org/?probe=48c2b7a173) | Aug 15, 2021 |
| MSI           | Z370 KRAIT GAMING           | [26e5da2e9c](https://linux-hardware.org/?probe=26e5da2e9c) | Aug 14, 2021 |
| MSI           | B450M-A PRO MAX             | [14e0f895ae](https://linux-hardware.org/?probe=14e0f895ae) | Aug 11, 2021 |
| Fujitsu       | D2778-C1 S26361-D2778-C1    | [b07993a438](https://linux-hardware.org/?probe=b07993a438) | Aug 11, 2021 |
| ASUSTek       | STRIX B250H GAMING          | [78223998b6](https://linux-hardware.org/?probe=78223998b6) | Aug 10, 2021 |
| ASUSTek       | TUF Gaming H570-PRO         | [990a72e285](https://linux-hardware.org/?probe=990a72e285) | Aug 06, 2021 |
| MSI           | B85M-E45                    | [85f98480a8](https://linux-hardware.org/?probe=85f98480a8) | Aug 05, 2021 |
| Lenovo        | SDK0J40705 WIN 342504252... | [65e0d03193](https://linux-hardware.org/?probe=65e0d03193) | Aug 03, 2021 |
| ASRock        | H470M-HVS                   | [97dbb1b8b9](https://linux-hardware.org/?probe=97dbb1b8b9) | Jul 30, 2021 |
| ASRock        | M3A770DE                    | [ea959bb531](https://linux-hardware.org/?probe=ea959bb531) | Jul 30, 2021 |
| Huanan        | X99-F8 V2.0                 | [5d51c3756f](https://linux-hardware.org/?probe=5d51c3756f) | Jul 29, 2021 |
| Huanan        | X79 249PC V2.3              | [216df9e1f6](https://linux-hardware.org/?probe=216df9e1f6) | Jul 29, 2021 |
| Gigabyte      | Z87X-UD5H-CF                | [88ddc09b9e](https://linux-hardware.org/?probe=88ddc09b9e) | Jul 28, 2021 |
| Gigabyte      | H81M-S2H                    | [f52713e401](https://linux-hardware.org/?probe=f52713e401) | Jul 28, 2021 |
| ASRock        | N68C-GS FX                  | [660f13d25d](https://linux-hardware.org/?probe=660f13d25d) | Jul 27, 2021 |
| Foxconn       | 915MH Series                | [6a3ae85dfc](https://linux-hardware.org/?probe=6a3ae85dfc) | Jul 27, 2021 |
| ASRock        | J4105-ITX                   | [ba7a9ed588](https://linux-hardware.org/?probe=ba7a9ed588) | Jul 27, 2021 |
| MSI           | B85M-E45                    | [d06bc5e141](https://linux-hardware.org/?probe=d06bc5e141) | Jul 26, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | [e9ddc17233](https://linux-hardware.org/?probe=e9ddc17233) | Jul 26, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | [6623f96b90](https://linux-hardware.org/?probe=6623f96b90) | Jul 26, 2021 |
| ASUSTek       | M5A78L-M LX3                | [2c05790c36](https://linux-hardware.org/?probe=2c05790c36) | Jul 26, 2021 |
| ASUSTek       | B85-PRO GAMER               | [fffec5c87f](https://linux-hardware.org/?probe=fffec5c87f) | Jul 26, 2021 |
| ASUSTek       | M5A78L-M LX3                | [fcd103f100](https://linux-hardware.org/?probe=fcd103f100) | Jul 26, 2021 |
| Gigabyte      | Z170M-D3H-CF                | [9301420a7b](https://linux-hardware.org/?probe=9301420a7b) | Jul 25, 2021 |
| ASRock        | FM2A68M-DG3+                | [884f8f2850](https://linux-hardware.org/?probe=884f8f2850) | Jul 25, 2021 |
| Lenovo        | SDK0J40705 WIN 342504252... | [f0937920ce](https://linux-hardware.org/?probe=f0937920ce) | Jul 24, 2021 |
| ASUSTek       | M4A89GTD-PRO                | [58278684c5](https://linux-hardware.org/?probe=58278684c5) | Jul 23, 2021 |
| ASUSTek       | PRIME Z370M-PLUS II         | [ba13052b2e](https://linux-hardware.org/?probe=ba13052b2e) | Jul 23, 2021 |
| ASUSTek       | PRIME Z370M-PLUS II         | [50bcb2f7ac](https://linux-hardware.org/?probe=50bcb2f7ac) | Jul 23, 2021 |
| Gigabyte      | 945GCMX-S2                  | [c9d0df911e](https://linux-hardware.org/?probe=c9d0df911e) | Jul 23, 2021 |
| ASUSTek       | P5G41T-M LX3                | [df48823117](https://linux-hardware.org/?probe=df48823117) | Jul 22, 2021 |
| Colorful T... | C.H81A-BTC V20              | [1196c4098b](https://linux-hardware.org/?probe=1196c4098b) | Jul 20, 2021 |
| ASUSTek       | M4A89GTD-PRO                | [a556f90b28](https://linux-hardware.org/?probe=a556f90b28) | Jul 20, 2021 |
| ASUSTek       | P5LD2                       | [9e97498649](https://linux-hardware.org/?probe=9e97498649) | Jul 19, 2021 |
| Biostar       | NF520D3                     | [3c302b5285](https://linux-hardware.org/?probe=3c302b5285) | Jul 18, 2021 |
| Gigabyte      | A55M-DS2                    | [6144ed6dc1](https://linux-hardware.org/?probe=6144ed6dc1) | Jul 18, 2021 |
| ASRock        | B450 Pro4                   | [7d45be2522](https://linux-hardware.org/?probe=7d45be2522) | Jul 17, 2021 |
| ASUSTek       | M4A89GTD-PRO                | [6b1b434e27](https://linux-hardware.org/?probe=6b1b434e27) | Jul 17, 2021 |
| ECS           | H81H3-M3                    | [645830ed64](https://linux-hardware.org/?probe=645830ed64) | Jul 15, 2021 |
| Medion        | MS-7616                     | [a22f78a7b2](https://linux-hardware.org/?probe=a22f78a7b2) | Jul 14, 2021 |
| ASUSTek       | P8Z77-V LX2                 | [fc51a5eb49](https://linux-hardware.org/?probe=fc51a5eb49) | Jul 13, 2021 |
| MSI           | 0AB8                        | [4599275ed5](https://linux-hardware.org/?probe=4599275ed5) | Jul 12, 2021 |
| ASUSTek       | A68HM-K                     | [03c69f44e3](https://linux-hardware.org/?probe=03c69f44e3) | Jul 12, 2021 |
| Biostar       | H61MHV2                     | [7bf699ed8e](https://linux-hardware.org/?probe=7bf699ed8e) | Jul 10, 2021 |
| ASUSTek       | PRIME A320M-K               | [1f7d8d2d39](https://linux-hardware.org/?probe=1f7d8d2d39) | Jul 07, 2021 |
| ASRock        | 880GXH/USB3                 | [eb1fe5a371](https://linux-hardware.org/?probe=eb1fe5a371) | Jul 06, 2021 |
| Gigabyte      | 970A-DS3P FX                | [b873d586f3](https://linux-hardware.org/?probe=b873d586f3) | Jul 03, 2021 |
| MSI           | A320M-A PRO                 | [9d356e787a](https://linux-hardware.org/?probe=9d356e787a) | Jul 01, 2021 |
| MSI           | B450 TOMAHAWK               | [ac2a4b3aea](https://linux-hardware.org/?probe=ac2a4b3aea) | Jul 01, 2021 |
| Gigabyte      | GA-78LMT-S2 R2 sex          | [0deed339a3](https://linux-hardware.org/?probe=0deed339a3) | Jun 30, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | [1032d8b0ff](https://linux-hardware.org/?probe=1032d8b0ff) | Jun 29, 2021 |
| ASUSTek       | P5GC-MX/1333                | [1b5c62b9d0](https://linux-hardware.org/?probe=1b5c62b9d0) | Jun 29, 2021 |
| MSI           | B75A-G43                    | [b251de3cbc](https://linux-hardware.org/?probe=b251de3cbc) | Jun 26, 2021 |
| Gigabyte      | 945GCM-S2L                  | [b042f1413c](https://linux-hardware.org/?probe=b042f1413c) | Jun 26, 2021 |
| Biostar       | TA770E                      | [e91f400988](https://linux-hardware.org/?probe=e91f400988) | Jun 26, 2021 |
| MSI           | B75A-G43                    | [db8082eb27](https://linux-hardware.org/?probe=db8082eb27) | Jun 26, 2021 |
| Biostar       | NF520-A2 TE                 | [53072a0af9](https://linux-hardware.org/?probe=53072a0af9) | Jun 25, 2021 |
| Biostar       | NF520-A2 TE                 | [b5c0eda1f8](https://linux-hardware.org/?probe=b5c0eda1f8) | Jun 24, 2021 |
| ASUSTek       | M5A97 R2.0                  | [be30616f33](https://linux-hardware.org/?probe=be30616f33) | Jun 23, 2021 |
| TYAN Compu... | Toledo i3210W/i3200R S52... | [cfacd9e7ce](https://linux-hardware.org/?probe=cfacd9e7ce) | Jun 21, 2021 |
| Gigabyte      | A320M-H-CF                  | [626be63b85](https://linux-hardware.org/?probe=626be63b85) | Jun 20, 2021 |
| ASUSTek       | P8H61-M LX3                 | [96aab075cd](https://linux-hardware.org/?probe=96aab075cd) | Jun 19, 2021 |
| ASUSTek       | PRIME B560-PLUS             | [ba370ceb36](https://linux-hardware.org/?probe=ba370ceb36) | Jun 18, 2021 |
| ASUSTek       | PRIME B560-PLUS             | [9379620c8f](https://linux-hardware.org/?probe=9379620c8f) | Jun 18, 2021 |
| ASUSTek       | TUF Gaming B460-PRO         | [1541cb2248](https://linux-hardware.org/?probe=1541cb2248) | Jun 16, 2021 |
| ASUSTek       | TUF Gaming B460-PRO         | [fa2bc4e41d](https://linux-hardware.org/?probe=fa2bc4e41d) | Jun 16, 2021 |
| Gigabyte      | Z77M-D3H                    | [fc3ab06806](https://linux-hardware.org/?probe=fc3ab06806) | Jun 15, 2021 |
| ASUSTek       | TUF Gaming B460-PRO         | [7bd31027c9](https://linux-hardware.org/?probe=7bd31027c9) | Jun 14, 2021 |
| ASUSTek       | TUF Gaming B460-PRO         | [156f0e85be](https://linux-hardware.org/?probe=156f0e85be) | Jun 12, 2021 |
| Gigabyte      | GA-MA770T-UD3               | [88fb2527e3](https://linux-hardware.org/?probe=88fb2527e3) | Jun 12, 2021 |
| ASUSTek       | M5A78L-M LX                 | [fae540293a](https://linux-hardware.org/?probe=fae540293a) | Jun 10, 2021 |
| ASUSTek       | M5A78L-M LX                 | [87ba6489f8](https://linux-hardware.org/?probe=87ba6489f8) | Jun 09, 2021 |
| ASUSTek       | P8H77-V                     | [d3cea8b700](https://linux-hardware.org/?probe=d3cea8b700) | Jun 09, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | [c7ef032a3f](https://linux-hardware.org/?probe=c7ef032a3f) | Jun 08, 2021 |
| MSI           | KA790GX                     | [6171bacf26](https://linux-hardware.org/?probe=6171bacf26) | Jun 08, 2021 |
| MSI           | Z390-A PRO                  | [8d4983662d](https://linux-hardware.org/?probe=8d4983662d) | Jun 08, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [e5a30a171e](https://linux-hardware.org/?probe=e5a30a171e) | Jun 08, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [043878564d](https://linux-hardware.org/?probe=043878564d) | Jun 08, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | [ef79bc6b0f](https://linux-hardware.org/?probe=ef79bc6b0f) | Jun 07, 2021 |
| Acer          | WG43M                       | [f575dddee3](https://linux-hardware.org/?probe=f575dddee3) | Jun 06, 2021 |
| Intel         | E5 M2L-8D                   | [7cca14c70d](https://linux-hardware.org/?probe=7cca14c70d) | Jun 05, 2021 |
| ASUSTek       | P8P67 LE                    | [19f07435fc](https://linux-hardware.org/?probe=19f07435fc) | Jun 05, 2021 |
| ASUSTek       | PRIME H310M-D               | [5f98fdcb02](https://linux-hardware.org/?probe=5f98fdcb02) | Jun 03, 2021 |
| MSI           | A68HM-E33 V2                | [01c5e2e798](https://linux-hardware.org/?probe=01c5e2e798) | May 31, 2021 |
| Gigabyte      | B450M H                     | [3453dec709](https://linux-hardware.org/?probe=3453dec709) | May 31, 2021 |
| ASUSTek       | ROG STRIX B360-I GAMING     | [36ebf65d44](https://linux-hardware.org/?probe=36ebf65d44) | May 30, 2021 |
| ASUSTek       | TUF Gaming B460-PRO         | [8b3c2193cc](https://linux-hardware.org/?probe=8b3c2193cc) | May 30, 2021 |
| ASUSTek       | TUF Gaming B460-PRO         | [93390ed697](https://linux-hardware.org/?probe=93390ed697) | May 29, 2021 |
| ASUSTek       | M2N-SLI DELUXE              | [476250f98c](https://linux-hardware.org/?probe=476250f98c) | May 29, 2021 |
| ASUSTek       | M4N68T                      | [1c28ab7987](https://linux-hardware.org/?probe=1c28ab7987) | May 28, 2021 |
| ASUSTek       | M4N68T                      | [95733f70ee](https://linux-hardware.org/?probe=95733f70ee) | May 27, 2021 |
| ASRock        | H77 Pro4-M                  | [f0450b570d](https://linux-hardware.org/?probe=f0450b570d) | May 27, 2021 |
| Gigabyte      | Z370M D3H-CF                | [50557b5f38](https://linux-hardware.org/?probe=50557b5f38) | May 27, 2021 |
| MSI           | X470 GAMING M7 AC           | [5913b80a19](https://linux-hardware.org/?probe=5913b80a19) | May 26, 2021 |
| MSI           | X470 GAMING M7 AC           | [fa6dd15d4f](https://linux-hardware.org/?probe=fa6dd15d4f) | May 26, 2021 |
| ASUSTek       | P5PL2                       | [4b68ac1130](https://linux-hardware.org/?probe=4b68ac1130) | May 23, 2021 |
| ASUSTek       | A68HM-K                     | [d62c1cc4aa](https://linux-hardware.org/?probe=d62c1cc4aa) | May 22, 2021 |
| ZOTAC         | NM10                        | [fbd56b7e5c](https://linux-hardware.org/?probe=fbd56b7e5c) | May 22, 2021 |
| ECS           | H81H3-M3                    | [3f8e53510c](https://linux-hardware.org/?probe=3f8e53510c) | May 21, 2021 |
| ASUSTek       | TUF Z390M-PRO GAMING        | [6566f6cabc](https://linux-hardware.org/?probe=6566f6cabc) | May 21, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [1c2f94847e](https://linux-hardware.org/?probe=1c2f94847e) | May 20, 2021 |
| Gigabyte      | Z68M-D2H                    | [75877fb3b1](https://linux-hardware.org/?probe=75877fb3b1) | May 19, 2021 |
| Gigabyte      | Z68M-D2H                    | [91cee123e9](https://linux-hardware.org/?probe=91cee123e9) | May 19, 2021 |
| Lenovo        | ThinkCentre M81 5048W4M     | [1b01ff9935](https://linux-hardware.org/?probe=1b01ff9935) | May 19, 2021 |
| MSI           | G31TM-P21                   | [001a25aa68](https://linux-hardware.org/?probe=001a25aa68) | May 19, 2021 |
| Gigabyte      | AB350M-DS3H V2-CF           | [93e7cae0d5](https://linux-hardware.org/?probe=93e7cae0d5) | May 17, 2021 |
| Biostar       | NF560-A2G                   | [0b6aa7d521](https://linux-hardware.org/?probe=0b6aa7d521) | May 17, 2021 |
| MSI           | A68HM-E33 V2                | [6f51becb58](https://linux-hardware.org/?probe=6f51becb58) | May 16, 2021 |
| ECS           | nForce4-A754                | [b1d8ef79df](https://linux-hardware.org/?probe=b1d8ef79df) | May 14, 2021 |
| ASUSTek       | M2A-MX                      | [9e451d88ab](https://linux-hardware.org/?probe=9e451d88ab) | May 14, 2021 |
| Gigabyte      | Z68M-D2H                    | [ec195ffe95](https://linux-hardware.org/?probe=ec195ffe95) | May 12, 2021 |
| Gigabyte      | A520M S2H                   | [0356377ab9](https://linux-hardware.org/?probe=0356377ab9) | May 11, 2021 |
| Gigabyte      | B450M DS3H-CF               | [9bc8b1b4e5](https://linux-hardware.org/?probe=9bc8b1b4e5) | May 11, 2021 |
| Gigabyte      | H77-DS3H                    | [cce8fbcd40](https://linux-hardware.org/?probe=cce8fbcd40) | May 10, 2021 |
| Gigabyte      | GA-780T-D3L                 | [ea1264332e](https://linux-hardware.org/?probe=ea1264332e) | May 09, 2021 |
| Gigabyte      | GA-780T-D3L                 | [a9533ecc6b](https://linux-hardware.org/?probe=a9533ecc6b) | May 09, 2021 |
| Gigabyte      | A520M S2H                   | [9fc600c1ad](https://linux-hardware.org/?probe=9fc600c1ad) | May 07, 2021 |
| Dell          | 0M5DCD A00                  | [913643000d](https://linux-hardware.org/?probe=913643000d) | May 04, 2021 |
| MSI           | Z97-G43                     | [6a06e4709b](https://linux-hardware.org/?probe=6a06e4709b) | May 01, 2021 |
| MSI           | Z97-G43                     | [86053cd13f](https://linux-hardware.org/?probe=86053cd13f) | May 01, 2021 |
| MSI           | A320M-A PRO M2              | [b87c7b7c87](https://linux-hardware.org/?probe=b87c7b7c87) | May 01, 2021 |
| ASUSTek       | PRIME A320M-K               | [63cbca2443](https://linux-hardware.org/?probe=63cbca2443) | Apr 30, 2021 |
| ASUSTek       | PRIME Z270-A                | [aff27ae264](https://linux-hardware.org/?probe=aff27ae264) | Apr 29, 2021 |
| HP            | 212B                        | [9216cfb736](https://linux-hardware.org/?probe=9216cfb736) | Apr 29, 2021 |
| ASUSTek       | P7P55-M                     | [5634ac753e](https://linux-hardware.org/?probe=5634ac753e) | Apr 28, 2021 |
| Gigabyte      | B150-HD3-CF                 | [e91c8823fa](https://linux-hardware.org/?probe=e91c8823fa) | Apr 28, 2021 |
| Intel         | DH61WW AAG23116-203         | [32aae9ea9a](https://linux-hardware.org/?probe=32aae9ea9a) | Apr 24, 2021 |
| HP            | 805F                        | [fa498b2f05](https://linux-hardware.org/?probe=fa498b2f05) | Apr 23, 2021 |
| HP            | 805F                        | [10f64bfe1f](https://linux-hardware.org/?probe=10f64bfe1f) | Apr 23, 2021 |
| Gigabyte      | H57M-USB3                   | [da796c7dcf](https://linux-hardware.org/?probe=da796c7dcf) | Apr 23, 2021 |
| Gigabyte      | M61PME-S2                   | [3f4bd0bcf5](https://linux-hardware.org/?probe=3f4bd0bcf5) | Apr 23, 2021 |
| Gigabyte      | M61PME-S2                   | [b1113e9106](https://linux-hardware.org/?probe=b1113e9106) | Apr 23, 2021 |
| ASUSTek       | M5A78L-M LX3                | [1aa3233f77](https://linux-hardware.org/?probe=1aa3233f77) | Apr 23, 2021 |
| ASUSTek       | M5A97 R2.0                  | [f6207dd67e](https://linux-hardware.org/?probe=f6207dd67e) | Apr 21, 2021 |
| Gigabyte      | F2A68HM-S1                  | [4a0e2da1ba](https://linux-hardware.org/?probe=4a0e2da1ba) | Apr 20, 2021 |
| ASUSTek       | P5GV-MX                     | [95148df3e9](https://linux-hardware.org/?probe=95148df3e9) | Apr 20, 2021 |
| Unknown       | Unknown                     | [39a0744819](https://linux-hardware.org/?probe=39a0744819) | Apr 20, 2021 |
| ASUSTek       | F1A55-M LX                  | [630bbb748a](https://linux-hardware.org/?probe=630bbb748a) | Apr 17, 2021 |
| Gigabyte      | Z68M-D2H                    | [c2c4591ef9](https://linux-hardware.org/?probe=c2c4591ef9) | Apr 16, 2021 |
| ASUSTek       | P9X79 PRO                   | [28a07ac7f9](https://linux-hardware.org/?probe=28a07ac7f9) | Apr 16, 2021 |
| Dell          | 02N3WF A01                  | [bffe1498c5](https://linux-hardware.org/?probe=bffe1498c5) | Apr 14, 2021 |
| Gigabyte      | A320M-H-CF                  | [a17c745ab0](https://linux-hardware.org/?probe=a17c745ab0) | Apr 14, 2021 |
| ASRock        | Z390 Taichi                 | [7df513ad5b](https://linux-hardware.org/?probe=7df513ad5b) | Apr 13, 2021 |
| Unknown       | Unknown                     | [5ed47267b8](https://linux-hardware.org/?probe=5ed47267b8) | Apr 13, 2021 |
| ECS           | H61H2-M6                    | [933e4ffba3](https://linux-hardware.org/?probe=933e4ffba3) | Apr 12, 2021 |
| Biostar       | TA890GXE                    | [4d8a08c8fc](https://linux-hardware.org/?probe=4d8a08c8fc) | Apr 12, 2021 |
| Dell          | 02N3WF A01                  | [3cdbee502b](https://linux-hardware.org/?probe=3cdbee502b) | Apr 12, 2021 |
| MSI           | PH67S-C43                   | [bf84a891cc](https://linux-hardware.org/?probe=bf84a891cc) | Apr 10, 2021 |
| ASRock        | FM2A68M-HD+                 | [f14fbaa5be](https://linux-hardware.org/?probe=f14fbaa5be) | Apr 10, 2021 |
| MSI           | H310M PRO-VD PLUS           | [de7b86720f](https://linux-hardware.org/?probe=de7b86720f) | Apr 10, 2021 |
| ASUSTek       | P8H61-MX                    | [9212747e6a](https://linux-hardware.org/?probe=9212747e6a) | Apr 08, 2021 |
| ECS           | H61H2-M6                    | [52a3904255](https://linux-hardware.org/?probe=52a3904255) | Apr 07, 2021 |
| Biostar       | P35D2-A7                    | [e43984d7d0](https://linux-hardware.org/?probe=e43984d7d0) | Apr 06, 2021 |
| ASUSTek       | M5A97 R2.0                  | [2041e11d53](https://linux-hardware.org/?probe=2041e11d53) | Apr 05, 2021 |
| ASRock        | A785GXH/128M                | [7a27db094e](https://linux-hardware.org/?probe=7a27db094e) | Apr 04, 2021 |
| Unknown       | Unknown                     | [831b3f8c68](https://linux-hardware.org/?probe=831b3f8c68) | Apr 04, 2021 |
| Dell          | 0YXT71 A03                  | [a693d293f1](https://linux-hardware.org/?probe=a693d293f1) | Apr 03, 2021 |
| ASUSTek       | PRIME H310M-R R2.0          | [db4d099b65](https://linux-hardware.org/?probe=db4d099b65) | Apr 03, 2021 |
| ASRock        | H410M-HDV                   | [47c1d0db47](https://linux-hardware.org/?probe=47c1d0db47) | Apr 02, 2021 |
| Biostar       | H61MLC                      | [e373b143ec](https://linux-hardware.org/?probe=e373b143ec) | Apr 01, 2021 |
| ECS           | 945PL-A                     | [4893e30a87](https://linux-hardware.org/?probe=4893e30a87) | Mar 31, 2021 |
| ASUSTek       | H61M-E                      | [fcc9dabb3d](https://linux-hardware.org/?probe=fcc9dabb3d) | Mar 30, 2021 |
| ASUSTek       | H61M-E                      | [ed7f2979b9](https://linux-hardware.org/?probe=ed7f2979b9) | Mar 30, 2021 |
| ASUSTek       | A88XM-A/USB                 | [ac50582416](https://linux-hardware.org/?probe=ac50582416) | Mar 29, 2021 |
| ASUSTek       | A68HM-K                     | [ef5acde9af](https://linux-hardware.org/?probe=ef5acde9af) | Mar 28, 2021 |
| MSI           | 0AB8                        | [196cdbc09e](https://linux-hardware.org/?probe=196cdbc09e) | Mar 25, 2021 |
| ASUSTek       | Z170 PRO GAMING             | [bb2ba9b142](https://linux-hardware.org/?probe=bb2ba9b142) | Mar 24, 2021 |
| ASUSTek       | H81M-A                      | [6f2378bbe5](https://linux-hardware.org/?probe=6f2378bbe5) | Mar 22, 2021 |
| MSI           | B460M PRO                   | [1dc8484ff4](https://linux-hardware.org/?probe=1dc8484ff4) | Mar 22, 2021 |
| ASUSTek       | P8H67-V                     | [17a10fd615](https://linux-hardware.org/?probe=17a10fd615) | Mar 22, 2021 |
| MSI           | B365M PRO-VDH               | [85eae8241f](https://linux-hardware.org/?probe=85eae8241f) | Mar 22, 2021 |
| ECS           | P4M890T-M                   | [72bfcda4bf](https://linux-hardware.org/?probe=72bfcda4bf) | Mar 22, 2021 |
| Gigabyte      | H61M-S2PV                   | [bbe4962b33](https://linux-hardware.org/?probe=bbe4962b33) | Mar 22, 2021 |
| Huanan        | X58 V110                    | [ba7a123679](https://linux-hardware.org/?probe=ba7a123679) | Mar 21, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [6b26a69326](https://linux-hardware.org/?probe=6b26a69326) | Mar 21, 2021 |
| ASRock        | ConRoe945G-DVI              | [fe64d52a52](https://linux-hardware.org/?probe=fe64d52a52) | Mar 21, 2021 |
| ASRock        | AD425PV3                    | [20089c34b5](https://linux-hardware.org/?probe=20089c34b5) | Mar 20, 2021 |
| Gigabyte      | F2A88XM-HD3                 | [d4deba7888](https://linux-hardware.org/?probe=d4deba7888) | Mar 20, 2021 |
| ASUSTek       | M2N                         | [56db54e530](https://linux-hardware.org/?probe=56db54e530) | Mar 19, 2021 |
| MSI           | H310M PRO-VD PLUS           | [8d30426b55](https://linux-hardware.org/?probe=8d30426b55) | Mar 19, 2021 |
| MSI           | B350 TOMAHAWK               | [d77d6984e4](https://linux-hardware.org/?probe=d77d6984e4) | Mar 19, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [9fdca2136a](https://linux-hardware.org/?probe=9fdca2136a) | Mar 19, 2021 |
| MSI           | X370 GAMING PRO CARBON      | [45cb6a5741](https://linux-hardware.org/?probe=45cb6a5741) | Mar 18, 2021 |
| ASUSTek       | TUF Z390M-PRO GAMING        | [c721b98942](https://linux-hardware.org/?probe=c721b98942) | Mar 18, 2021 |
| Gigabyte      | Z68AP-D3                    | [a3df91d556](https://linux-hardware.org/?probe=a3df91d556) | Mar 18, 2021 |
| ASRock        | AB350M Pro4 R2.0            | [d5ddb563ac](https://linux-hardware.org/?probe=d5ddb563ac) | Mar 18, 2021 |
| ASUSTek       | M4A88T-V EVO/USB3           | [fbf0cd6c8d](https://linux-hardware.org/?probe=fbf0cd6c8d) | Mar 17, 2021 |
| ASRock        | AB350M Pro4 R2.0            | [af9b948ec2](https://linux-hardware.org/?probe=af9b948ec2) | Mar 17, 2021 |
| Lenovo        | NO DPK                      | [3bec5ddc17](https://linux-hardware.org/?probe=3bec5ddc17) | Mar 17, 2021 |
| MSI           | B450M PRO-VDH MAX           | [00a14a97a2](https://linux-hardware.org/?probe=00a14a97a2) | Mar 17, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | [069769819b](https://linux-hardware.org/?probe=069769819b) | Mar 17, 2021 |
| ASRock        | H370M-HDV                   | [d926961a40](https://linux-hardware.org/?probe=d926961a40) | Mar 17, 2021 |
| ASRock        | H370M-HDV                   | [42a50971b8](https://linux-hardware.org/?probe=42a50971b8) | Mar 17, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [4d8d7a3551](https://linux-hardware.org/?probe=4d8d7a3551) | Mar 17, 2021 |
| Gigabyte      | 970A-DS3P                   | [eeebc66137](https://linux-hardware.org/?probe=eeebc66137) | Mar 17, 2021 |
| Gigabyte      | 970A-DS3P                   | [fdf4e6d366](https://linux-hardware.org/?probe=fdf4e6d366) | Mar 17, 2021 |
| Intel         | Thurley                     | [f543a35f4c](https://linux-hardware.org/?probe=f543a35f4c) | Mar 17, 2021 |
| Gigabyte      | Z68AP-D3                    | [7c2ac274a5](https://linux-hardware.org/?probe=7c2ac274a5) | Mar 17, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [7cc0dfac27](https://linux-hardware.org/?probe=7cc0dfac27) | Mar 17, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [a4a19eb4bb](https://linux-hardware.org/?probe=a4a19eb4bb) | Mar 17, 2021 |
| MSI           | B450-A PRO                  | [b843e6454a](https://linux-hardware.org/?probe=b843e6454a) | Mar 17, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [6124e0aa83](https://linux-hardware.org/?probe=6124e0aa83) | Mar 17, 2021 |
| Dell          | 0M9KCM A00                  | [14861d9819](https://linux-hardware.org/?probe=14861d9819) | Mar 17, 2021 |
| ASUSTek       | PRIME A320M-K               | [2a000e48f4](https://linux-hardware.org/?probe=2a000e48f4) | Mar 17, 2021 |
| ASUSTek       | A88XM-E                     | [7820059f6a](https://linux-hardware.org/?probe=7820059f6a) | Mar 17, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [07cd9eac56](https://linux-hardware.org/?probe=07cd9eac56) | Mar 17, 2021 |
| Dell          | 02N3WF A01                  | [a6f2c9e61f](https://linux-hardware.org/?probe=a6f2c9e61f) | Mar 15, 2021 |
| ASRock        | G31M-S                      | [cc4812e5d3](https://linux-hardware.org/?probe=cc4812e5d3) | Mar 14, 2021 |
| ASRock        | Z97 Killer                  | [fbbf57d9ef](https://linux-hardware.org/?probe=fbbf57d9ef) | Mar 13, 2021 |
| ASUSTek       | PRIME B360M-K               | [f16d7116c9](https://linux-hardware.org/?probe=f16d7116c9) | Mar 13, 2021 |
| ASUSTek       | P5G-MX                      | [52e0e4c9a6](https://linux-hardware.org/?probe=52e0e4c9a6) | Mar 12, 2021 |
| Gigabyte      | Z87X-UD5H-CF                | [d4570ea6b2](https://linux-hardware.org/?probe=d4570ea6b2) | Mar 12, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [bf856bd378](https://linux-hardware.org/?probe=bf856bd378) | Mar 11, 2021 |
| ASRock        | N68-S                       | [a31c408337](https://linux-hardware.org/?probe=a31c408337) | Mar 10, 2021 |
| HP            | 1589                        | [d66c109c0e](https://linux-hardware.org/?probe=d66c109c0e) | Mar 10, 2021 |
| ASUSTek       | P5K SE                      | [c121ebf1b4](https://linux-hardware.org/?probe=c121ebf1b4) | Mar 08, 2021 |
| ASUSTek       | PRIME B450M-A II            | [028235c250](https://linux-hardware.org/?probe=028235c250) | Mar 06, 2021 |
| ASUSTek       | PRIME B450M-A II            | [ccd14c8f38](https://linux-hardware.org/?probe=ccd14c8f38) | Mar 06, 2021 |
| Gigabyte      | 945GCM-S2L                  | [6ddfd23c4d](https://linux-hardware.org/?probe=6ddfd23c4d) | Mar 05, 2021 |
| MSI           | A68HM-P33 V2                | [e96e28079a](https://linux-hardware.org/?probe=e96e28079a) | Mar 05, 2021 |
| ASUSTek       | P4P800-MX                   | [1b67f298e5](https://linux-hardware.org/?probe=1b67f298e5) | Mar 05, 2021 |
| ASUSTek       | M5A78L-M LX                 | [cefdf64d5f](https://linux-hardware.org/?probe=cefdf64d5f) | Mar 04, 2021 |
| ASUSTek       | PRIME H410M-K               | [f685fefbec](https://linux-hardware.org/?probe=f685fefbec) | Mar 04, 2021 |
| ASRock        | X570 Phantom Gaming 4       | [ded40db2a0](https://linux-hardware.org/?probe=ded40db2a0) | Mar 03, 2021 |
| Dell          | 09M8Y8 A01                  | [4997df5506](https://linux-hardware.org/?probe=4997df5506) | Mar 03, 2021 |
| ASUSTek       | CM1735                      | [dfaf35d9ff](https://linux-hardware.org/?probe=dfaf35d9ff) | Mar 02, 2021 |
| ASUSTek       | CM1735                      | [83a3d8a0e2](https://linux-hardware.org/?probe=83a3d8a0e2) | Mar 02, 2021 |
| ASUSTek       | H110M-K                     | [163b15bc2b](https://linux-hardware.org/?probe=163b15bc2b) | Mar 01, 2021 |
| Gigabyte      | A320M-H-CF                  | [9a9b6a09e0](https://linux-hardware.org/?probe=9a9b6a09e0) | Feb 27, 2021 |
| ASUSTek       | P5KC                        | [7ca92abd15](https://linux-hardware.org/?probe=7ca92abd15) | Feb 26, 2021 |
| MSI           | A55M-P33                    | [2d5b2c84e5](https://linux-hardware.org/?probe=2d5b2c84e5) | Feb 25, 2021 |
| Dell          | 02N3WF A01                  | [1d6e8ad9da](https://linux-hardware.org/?probe=1d6e8ad9da) | Feb 24, 2021 |
| MSI           | H87-G43 GAMING              | [84a36237d0](https://linux-hardware.org/?probe=84a36237d0) | Feb 24, 2021 |
| ASUSTek       | P5K-VM                      | [39270c836f](https://linux-hardware.org/?probe=39270c836f) | Feb 23, 2021 |
| Gigabyte      | Z68M-D2H                    | [b7084c4301](https://linux-hardware.org/?probe=b7084c4301) | Feb 22, 2021 |
| Gigabyte      | H310M S2V x.x               | [87b8d58707](https://linux-hardware.org/?probe=87b8d58707) | Feb 22, 2021 |
| Gigabyte      | B550 AORUS PRO V2           | [78c9f0a694](https://linux-hardware.org/?probe=78c9f0a694) | Feb 21, 2021 |
| ASUSTek       | TUF B360M-E GAMING          | [fb24c9d115](https://linux-hardware.org/?probe=fb24c9d115) | Feb 21, 2021 |
| Biostar       | G31D-M7                     | [da8af8faaa](https://linux-hardware.org/?probe=da8af8faaa) | Feb 20, 2021 |
| ASUSTek       | M2A-VM                      | [db0f2329b1](https://linux-hardware.org/?probe=db0f2329b1) | Feb 19, 2021 |
| ASUSTek       | M2A-VM                      | [cebb004dbe](https://linux-hardware.org/?probe=cebb004dbe) | Feb 19, 2021 |
| Unknown       | Intel X79                   | [9915f91e29](https://linux-hardware.org/?probe=9915f91e29) | Feb 19, 2021 |
| MSI           | B450M PRO-VDH MAX           | [9d3377e42c](https://linux-hardware.org/?probe=9d3377e42c) | Feb 19, 2021 |
| ASUSTek       | M5A78L/USB3                 | [818882ee76](https://linux-hardware.org/?probe=818882ee76) | Feb 18, 2021 |
| ASUSTek       | M5A97 PRO                   | [24ab5e1b15](https://linux-hardware.org/?probe=24ab5e1b15) | Feb 18, 2021 |
| ASUSTek       | P8H61-M LX3 R2.0            | [994dadf394](https://linux-hardware.org/?probe=994dadf394) | Feb 18, 2021 |
| ASUSTek       | Crosshair IV Formula        | [d72f0f38e7](https://linux-hardware.org/?probe=d72f0f38e7) | Feb 18, 2021 |
| ASRock        | 970A-G                      | [47cd142b28](https://linux-hardware.org/?probe=47cd142b28) | Feb 18, 2021 |
| Gigabyte      | Q170M-D3H                   | [9d1c5dc708](https://linux-hardware.org/?probe=9d1c5dc708) | Feb 17, 2021 |
| ASUSTek       | P5Q SE/R                    | [bc752ecf37](https://linux-hardware.org/?probe=bc752ecf37) | Feb 17, 2021 |
| Biostar       | H81MHV3                     | [dd2f04f1ee](https://linux-hardware.org/?probe=dd2f04f1ee) | Feb 16, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [beb052cdd4](https://linux-hardware.org/?probe=beb052cdd4) | Feb 15, 2021 |
| ASUSTek       | M5A78L/USB3                 | [3b41a4f922](https://linux-hardware.org/?probe=3b41a4f922) | Feb 15, 2021 |
| ASUSTek       | TUF Gaming X570-PRO         | [05ec6fa609](https://linux-hardware.org/?probe=05ec6fa609) | Feb 14, 2021 |
| Intel         | E5 M2L-8D                   | [4dd4400b16](https://linux-hardware.org/?probe=4dd4400b16) | Feb 14, 2021 |
| ASRock        | N68C-S UCC                  | [9d5bbf4186](https://linux-hardware.org/?probe=9d5bbf4186) | Feb 14, 2021 |
| ASRock        | B450M-HDV R4.0              | [b7a9aecefb](https://linux-hardware.org/?probe=b7a9aecefb) | Feb 14, 2021 |
| ASUSTek       | P5G41-M SI                  | [9c14de0766](https://linux-hardware.org/?probe=9c14de0766) | Feb 14, 2021 |
| Biostar       | A880GU3                     | [a1ab95c322](https://linux-hardware.org/?probe=a1ab95c322) | Feb 13, 2021 |
| MSI           | H87-G43 GAMING              | [1de518df69](https://linux-hardware.org/?probe=1de518df69) | Feb 13, 2021 |
| HP            | 3029h                       | [c1957854cc](https://linux-hardware.org/?probe=c1957854cc) | Feb 13, 2021 |
| Lenovo        | ThinkCentre M90p 5852A34    | [1248d4feaf](https://linux-hardware.org/?probe=1248d4feaf) | Feb 13, 2021 |
| ASUSTek       | PRIME Z390-P                | [edd81948e5](https://linux-hardware.org/?probe=edd81948e5) | Feb 13, 2021 |
| ASRock        | X570 Extreme4               | [3f2929b8fd](https://linux-hardware.org/?probe=3f2929b8fd) | Feb 11, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [d993271043](https://linux-hardware.org/?probe=d993271043) | Feb 11, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [ab8c311c17](https://linux-hardware.org/?probe=ab8c311c17) | Feb 11, 2021 |
| Unknown       | Unknown                     | [84cb0d787d](https://linux-hardware.org/?probe=84cb0d787d) | Feb 09, 2021 |
| Unknown       | Unknown                     | [7956910c59](https://linux-hardware.org/?probe=7956910c59) | Feb 09, 2021 |
| ASRock        | FM2A58M-DG3+                | [fbc7b4875e](https://linux-hardware.org/?probe=fbc7b4875e) | Feb 09, 2021 |
| ASRock        | N68C-S UCC                  | [c35f0c5e8f](https://linux-hardware.org/?probe=c35f0c5e8f) | Feb 08, 2021 |
| Gigabyte      | H81M-S2H                    | [f9e5b1d3c6](https://linux-hardware.org/?probe=f9e5b1d3c6) | Feb 08, 2021 |
| Gigabyte      | P35-DS3L                    | [f7a94fa35c](https://linux-hardware.org/?probe=f7a94fa35c) | Feb 05, 2021 |
| MSI           | 0AB8                        | [311a3ce6a2](https://linux-hardware.org/?probe=311a3ce6a2) | Feb 05, 2021 |
| Gigabyte      | Z87X-UD5H-CF                | [aea262050c](https://linux-hardware.org/?probe=aea262050c) | Feb 04, 2021 |
| Intel         | D510MO AAE76523-403         | [57a684a276](https://linux-hardware.org/?probe=57a684a276) | Feb 03, 2021 |
| MSI           | 0AB8                        | [bc2c33d34e](https://linux-hardware.org/?probe=bc2c33d34e) | Feb 03, 2021 |
| Gigabyte      | M61SME-S2                   | [46bb3326d0](https://linux-hardware.org/?probe=46bb3326d0) | Feb 02, 2021 |
| Gigabyte      | M61SME-S2                   | [676a5488b6](https://linux-hardware.org/?probe=676a5488b6) | Feb 02, 2021 |
| ASUSTek       | P4S800-MX SE                | [d3c1b192f2](https://linux-hardware.org/?probe=d3c1b192f2) | Feb 02, 2021 |
| ASRock        | FM2A58M-DG3+                | [1e81f470ad](https://linux-hardware.org/?probe=1e81f470ad) | Feb 02, 2021 |
| MSI           | H87-G43 GAMING              | [45072c8d06](https://linux-hardware.org/?probe=45072c8d06) | Feb 01, 2021 |
| MSI           | H110M PRO-VD                | [aaa9079804](https://linux-hardware.org/?probe=aaa9079804) | Feb 01, 2021 |
| ASRock        | Q1900M                      | [aa19143907](https://linux-hardware.org/?probe=aa19143907) | Jan 31, 2021 |
| MSI           | H87-G43 GAMING              | [d725b3aeb9](https://linux-hardware.org/?probe=d725b3aeb9) | Jan 31, 2021 |
| MSI           | H87-G43 GAMING              | [26b37cbedb](https://linux-hardware.org/?probe=26b37cbedb) | Jan 31, 2021 |
| Dell          | 0MH651                      | [92e88d1629](https://linux-hardware.org/?probe=92e88d1629) | Jan 29, 2021 |
| Biostar       | H55 HD                      | [d72bebb046](https://linux-hardware.org/?probe=d72bebb046) | Jan 29, 2021 |
| Biostar       | H55 HD                      | [9a0c67e588](https://linux-hardware.org/?probe=9a0c67e588) | Jan 28, 2021 |
| ASUSTek       | M2A-VM                      | [1eea8cf301](https://linux-hardware.org/?probe=1eea8cf301) | Jan 26, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [8c7c26863a](https://linux-hardware.org/?probe=8c7c26863a) | Jan 26, 2021 |
| ASUSTek       | P4S800-MX SE                | [167bca13aa](https://linux-hardware.org/?probe=167bca13aa) | Jan 25, 2021 |
| ASRock        | H81 Pro BTC R2.0            | [d74a177843](https://linux-hardware.org/?probe=d74a177843) | Jan 23, 2021 |
| Gigabyte      | EP45-UD3LR                  | [148a187bd0](https://linux-hardware.org/?probe=148a187bd0) | Jan 23, 2021 |
| Gigabyte      | GA-E6010N                   | [547a17b62b](https://linux-hardware.org/?probe=547a17b62b) | Jan 22, 2021 |
| Gigabyte      | GA-E6010N                   | [d8654fa020](https://linux-hardware.org/?probe=d8654fa020) | Jan 22, 2021 |
| ASRock        | N68C-S UCC                  | [37c09056d7](https://linux-hardware.org/?probe=37c09056d7) | Jan 22, 2021 |
| ASRock        | N68C-S UCC                  | [de38296c90](https://linux-hardware.org/?probe=de38296c90) | Jan 22, 2021 |
| Gigabyte      | G41M-Combo                  | [ec8fc2def5](https://linux-hardware.org/?probe=ec8fc2def5) | Jan 21, 2021 |
| ECS           | A85F2-A GOLDEN              | [783674fdbd](https://linux-hardware.org/?probe=783674fdbd) | Jan 21, 2021 |
| Dell          | 0HN7XN A01                  | [c6f7cbb8e0](https://linux-hardware.org/?probe=c6f7cbb8e0) | Jan 21, 2021 |
| ASRock        | H81 Pro BTC R2.0            | [28a1344890](https://linux-hardware.org/?probe=28a1344890) | Jan 19, 2021 |
| MSI           | MEG X570 GODLIKE            | [5964a40d34](https://linux-hardware.org/?probe=5964a40d34) | Jan 17, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | [db1cede116](https://linux-hardware.org/?probe=db1cede116) | Jan 16, 2021 |
| HP            | 1905                        | [75ca56479e](https://linux-hardware.org/?probe=75ca56479e) | Jan 16, 2021 |
| Dell          | 0200DY A03                  | [a895f2ae1f](https://linux-hardware.org/?probe=a895f2ae1f) | Jan 16, 2021 |
| HP            | 3032h                       | [1b0cabb46f](https://linux-hardware.org/?probe=1b0cabb46f) | Jan 16, 2021 |
| Gigabyte      | B85M-HD3                    | [ac5155fe4a](https://linux-hardware.org/?probe=ac5155fe4a) | Jan 16, 2021 |
| HP            | 1496                        | [1c57303a1d](https://linux-hardware.org/?probe=1c57303a1d) | Jan 16, 2021 |
| HP            | 1905                        | [70ed25a75a](https://linux-hardware.org/?probe=70ed25a75a) | Jan 16, 2021 |
| HP            | 1589                        | [3361782896](https://linux-hardware.org/?probe=3361782896) | Jan 16, 2021 |
| ASUSTek       | P8P67-M                     | [18a5491597](https://linux-hardware.org/?probe=18a5491597) | Jan 12, 2021 |
| Gigabyte      | F2A55M-DS2                  | [badc244439](https://linux-hardware.org/?probe=badc244439) | Jan 12, 2021 |
| ASUSTek       | P8Z68-V GEN3                | [cedfff2f2b](https://linux-hardware.org/?probe=cedfff2f2b) | Jan 11, 2021 |
| MSI           | H110M PRO-VD                | [3df8f336fd](https://linux-hardware.org/?probe=3df8f336fd) | Jan 11, 2021 |
| MSI           | MPG B550 GAMING PLUS        | [43c95e5481](https://linux-hardware.org/?probe=43c95e5481) | Jan 10, 2021 |
| MSI           | MPG B550 GAMING PLUS        | [81c0976ee7](https://linux-hardware.org/?probe=81c0976ee7) | Jan 10, 2021 |
| ASUSTek       | Crosshair IV Formula        | [9cafb3ad7a](https://linux-hardware.org/?probe=9cafb3ad7a) | Jan 10, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | [d2e7afe72d](https://linux-hardware.org/?probe=d2e7afe72d) | Jan 10, 2021 |
| MSI           | B450M BAZOOKA MAX WIFI      | [91f401bd7c](https://linux-hardware.org/?probe=91f401bd7c) | Jan 09, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | [5f70979d18](https://linux-hardware.org/?probe=5f70979d18) | Jan 09, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | [e5a628c858](https://linux-hardware.org/?probe=e5a628c858) | Jan 09, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [ca1596d645](https://linux-hardware.org/?probe=ca1596d645) | Jan 08, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | [5594066cc2](https://linux-hardware.org/?probe=5594066cc2) | Jan 07, 2021 |
| ASUSTek       | PRIME Z490-P                | [b6b00009f2](https://linux-hardware.org/?probe=b6b00009f2) | Jan 06, 2021 |
| Biostar       | TA890GXE                    | [ca3466941e](https://linux-hardware.org/?probe=ca3466941e) | Jan 05, 2021 |
| ASUSTek       | P8B75-V                     | [a8ba58ce8d](https://linux-hardware.org/?probe=a8ba58ce8d) | Jan 03, 2021 |
| ASRock        | H61M-VG3                    | [917ce2ed36](https://linux-hardware.org/?probe=917ce2ed36) | Jan 03, 2021 |
| ASUSTek       | P4P800-MX                   | [8b8aa94fa0](https://linux-hardware.org/?probe=8b8aa94fa0) | Jan 03, 2021 |
| ASRock        | H61M-VG3                    | [36bc1e558a](https://linux-hardware.org/?probe=36bc1e558a) | Jan 03, 2021 |
| Gigabyte      | P35-DS3L                    | [f353e484eb](https://linux-hardware.org/?probe=f353e484eb) | Jan 02, 2021 |
| ASUSTek       | ROG STRIX B360-I GAMING     | [32aae7f223](https://linux-hardware.org/?probe=32aae7f223) | Dec 31, 2020 |
| ASUSTek       | ROG STRIX B360-I GAMING     | [2331e1bc7b](https://linux-hardware.org/?probe=2331e1bc7b) | Dec 31, 2020 |
| Gigabyte      | EP35-DS3                    | [270e42f6f6](https://linux-hardware.org/?probe=270e42f6f6) | Dec 30, 2020 |
| Lenovo        | ThinkCentre M81 0385A2U     | [043a0e2bc4](https://linux-hardware.org/?probe=043a0e2bc4) | Dec 29, 2020 |
| MSI           | H61M-P20                    | [f402863234](https://linux-hardware.org/?probe=f402863234) | Dec 29, 2020 |
| Lenovo        | ThinkCentre M81 0385A2U     | [248cc36df9](https://linux-hardware.org/?probe=248cc36df9) | Dec 29, 2020 |
| Gigabyte      | B450M DS3H-CF               | [017a456b07](https://linux-hardware.org/?probe=017a456b07) | Dec 28, 2020 |
| Gigabyte      | B450M S2H                   | [7ccb916116](https://linux-hardware.org/?probe=7ccb916116) | Dec 28, 2020 |
| ASUSTek       | A68HM-K                     | [759f17e2d4](https://linux-hardware.org/?probe=759f17e2d4) | Dec 27, 2020 |
| ASUSTek       | M2N-MX                      | [3f582a2ab7](https://linux-hardware.org/?probe=3f582a2ab7) | Dec 26, 2020 |
| ASRock        | X99 Extreme4                | [989ea774a3](https://linux-hardware.org/?probe=989ea774a3) | Dec 25, 2020 |
| ASUSTek       | PRIME B450M-A               | [af98e95e15](https://linux-hardware.org/?probe=af98e95e15) | Dec 25, 2020 |
| ASUSTek       | P5QL-ASUS-SE                | [cf23b1c141](https://linux-hardware.org/?probe=cf23b1c141) | Dec 25, 2020 |
| Dell          | 0MH651                      | [e4fbc4bf76](https://linux-hardware.org/?probe=e4fbc4bf76) | Dec 25, 2020 |
| Intel         | D510MO AAE76523-403         | [6186cd45a4](https://linux-hardware.org/?probe=6186cd45a4) | Dec 25, 2020 |
| Intel         | D510MO AAE76523-403         | [fe7f047ac2](https://linux-hardware.org/?probe=fe7f047ac2) | Dec 25, 2020 |
| ASUSTek       | P5Q SE                      | [0f5e8185c5](https://linux-hardware.org/?probe=0f5e8185c5) | Dec 24, 2020 |
| Gigabyte      | X58A-UD3R                   | [1f0a156af2](https://linux-hardware.org/?probe=1f0a156af2) | Dec 24, 2020 |
| ASUSTek       | P8H61-M LX3                 | [a2bf03f948](https://linux-hardware.org/?probe=a2bf03f948) | Dec 21, 2020 |
| HP            | 339A                        | [39b7ad53ba](https://linux-hardware.org/?probe=39b7ad53ba) | Dec 21, 2020 |
| Unknown       | Unknown                     | [4a9d2bc028](https://linux-hardware.org/?probe=4a9d2bc028) | Dec 20, 2020 |
| MSI           | A320M-A PRO                 | [61d571a59b](https://linux-hardware.org/?probe=61d571a59b) | Dec 19, 2020 |
| Fujitsu       | D3064-A1 S26361-D3064-A1    | [d32251bcff](https://linux-hardware.org/?probe=d32251bcff) | Dec 17, 2020 |
| Fujitsu       | D3064-A1 S26361-D3064-A1    | [7d4e787996](https://linux-hardware.org/?probe=7d4e787996) | Dec 17, 2020 |
| Unknown       | Unknown                     | [e13b034567](https://linux-hardware.org/?probe=e13b034567) | Dec 17, 2020 |
| Gigabyte      | J3455N-D3H                  | [3600589bf6](https://linux-hardware.org/?probe=3600589bf6) | Dec 15, 2020 |
| ASUSTek       | PRIME A320M-K               | [81f8694c10](https://linux-hardware.org/?probe=81f8694c10) | Dec 14, 2020 |
| ASUSTek       | P8H77-I                     | [94300ffd04](https://linux-hardware.org/?probe=94300ffd04) | Dec 12, 2020 |
| Lenovo        | ThinkCentre M90p 5852A34    | [948258068e](https://linux-hardware.org/?probe=948258068e) | Dec 11, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [b035fc6450](https://linux-hardware.org/?probe=b035fc6450) | Dec 11, 2020 |
| MSI           | B150 PC MATE                | [e7676b68da](https://linux-hardware.org/?probe=e7676b68da) | Dec 11, 2020 |
| ASUSTek       | A68HM-K                     | [60ff39db0c](https://linux-hardware.org/?probe=60ff39db0c) | Dec 10, 2020 |
| MSI           | B75MA-IE35                  | [6934b45049](https://linux-hardware.org/?probe=6934b45049) | Dec 08, 2020 |
| ASUSTek       | A68HM-K                     | [5e804c56ae](https://linux-hardware.org/?probe=5e804c56ae) | Dec 07, 2020 |
| MSI           | H97M-G43                    | [80a28f1635](https://linux-hardware.org/?probe=80a28f1635) | Dec 06, 2020 |
| Lenovo        | NO DPK                      | [31f0311b11](https://linux-hardware.org/?probe=31f0311b11) | Dec 06, 2020 |
| MSI           | A320M-A PRO                 | [7e8fb3f3d5](https://linux-hardware.org/?probe=7e8fb3f3d5) | Dec 05, 2020 |
| MSI           | B460M PRO                   | [972c8bfc2f](https://linux-hardware.org/?probe=972c8bfc2f) | Dec 04, 2020 |
| ASUSTek       | M5A78L-M LX3                | [5d7577fc5d](https://linux-hardware.org/?probe=5d7577fc5d) | Dec 04, 2020 |
| ASUSTek       | P5G41-M LX2/GB              | [a68e82eecc](https://linux-hardware.org/?probe=a68e82eecc) | Dec 01, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [d950be920b](https://linux-hardware.org/?probe=d950be920b) | Dec 01, 2020 |
| MSI           | B450M BAZOOKA MAX WIFI      | [5b17a6a565](https://linux-hardware.org/?probe=5b17a6a565) | Dec 01, 2020 |
| ASUSTek       | M4N68T LE V2                | [5b38ecc4b2](https://linux-hardware.org/?probe=5b38ecc4b2) | Dec 01, 2020 |
| ASUSTek       | P5K SE/EPU                  | [9ed4b482dc](https://linux-hardware.org/?probe=9ed4b482dc) | Nov 29, 2020 |
| ASUSTek       | P8Z77-V DELUXE              | [8f730488d9](https://linux-hardware.org/?probe=8f730488d9) | Nov 28, 2020 |
| ASRock        | P4i65G                      | [572e521aa4](https://linux-hardware.org/?probe=572e521aa4) | Nov 28, 2020 |
| ASRock        | P4i65G                      | [995cfa0da3](https://linux-hardware.org/?probe=995cfa0da3) | Nov 27, 2020 |
| Gigabyte      | H77-DS3H                    | [ce0031111c](https://linux-hardware.org/?probe=ce0031111c) | Nov 25, 2020 |
| HP            | 0ACCh                       | [7f4d2a2df4](https://linux-hardware.org/?probe=7f4d2a2df4) | Nov 23, 2020 |
| HP            | 0ACCh                       | [d28f3f3195](https://linux-hardware.org/?probe=d28f3f3195) | Nov 23, 2020 |
| Gigabyte      | H81M-S2H                    | [009e2519cb](https://linux-hardware.org/?probe=009e2519cb) | Nov 22, 2020 |
| ASUSTek       | M4A77T                      | [8f463afca3](https://linux-hardware.org/?probe=8f463afca3) | Nov 22, 2020 |
| ASUSTek       | M4A77T                      | [8e1b9c4d71](https://linux-hardware.org/?probe=8e1b9c4d71) | Nov 22, 2020 |
| ASUSTek       | P8H61-M LX                  | [3bea549ad3](https://linux-hardware.org/?probe=3bea549ad3) | Nov 20, 2020 |
| HP            | 2B34                        | [9b79f2dda7](https://linux-hardware.org/?probe=9b79f2dda7) | Nov 20, 2020 |
| ASUSTek       | M5A97 PRO                   | [2376307934](https://linux-hardware.org/?probe=2376307934) | Nov 20, 2020 |
| ASUSTek       | P8H67                       | [49e3e677c5](https://linux-hardware.org/?probe=49e3e677c5) | Nov 19, 2020 |
| ASUSTek       | H81M-R                      | [0ba62ef30a](https://linux-hardware.org/?probe=0ba62ef30a) | Nov 19, 2020 |
| ASRock        | A785GMH/128M                | [3f81285b4e](https://linux-hardware.org/?probe=3f81285b4e) | Nov 19, 2020 |
| ASUSTek       | PRIME B360M-A               | [f32649e5f6](https://linux-hardware.org/?probe=f32649e5f6) | Nov 18, 2020 |
| ASUSTek       | PRIME B360M-A               | [156d203922](https://linux-hardware.org/?probe=156d203922) | Nov 18, 2020 |
| ASUSTek       | Q170T                       | [f671213525](https://linux-hardware.org/?probe=f671213525) | Nov 15, 2020 |
| ASUSTek       | ROG ZENITH EXTREME ALPHA    | [ae4f337d8f](https://linux-hardware.org/?probe=ae4f337d8f) | Nov 15, 2020 |
| Acer          | FIH57                       | [c7f3d900b3](https://linux-hardware.org/?probe=c7f3d900b3) | Nov 14, 2020 |
| Gigabyte      | B450M S2H                   | [1021a9847b](https://linux-hardware.org/?probe=1021a9847b) | Nov 14, 2020 |
| ASUSTek       | P5GZ-MX                     | [38ced91f1b](https://linux-hardware.org/?probe=38ced91f1b) | Nov 14, 2020 |
| ASUSTek       | P5GZ-MX                     | [70834d52e8](https://linux-hardware.org/?probe=70834d52e8) | Nov 13, 2020 |
| Biostar       | A10N-8800E                  | [5444a8df74](https://linux-hardware.org/?probe=5444a8df74) | Nov 13, 2020 |
| ASUSTek       | M3A32-MVP DELUXE            | [594001cad5](https://linux-hardware.org/?probe=594001cad5) | Nov 11, 2020 |
| MSI           | H310M PRO-VD                | [18c316813f](https://linux-hardware.org/?probe=18c316813f) | Nov 11, 2020 |
| Gigabyte      | P85-D3                      | [3c7676cec2](https://linux-hardware.org/?probe=3c7676cec2) | Nov 11, 2020 |
| ASUSTek       | M5A78L-M LX3                | [bafa163e0a](https://linux-hardware.org/?probe=bafa163e0a) | Nov 11, 2020 |
| MSI           | B450-A PRO                  | [a69a8b77d7](https://linux-hardware.org/?probe=a69a8b77d7) | Nov 10, 2020 |
| ASUSTek       | P8H61-M LX                  | [96c14111f8](https://linux-hardware.org/?probe=96c14111f8) | Nov 10, 2020 |
| ASUSTek       | P8H67                       | [f044b43d51](https://linux-hardware.org/?probe=f044b43d51) | Nov 10, 2020 |
| Dell          | 0HN7XN A01                  | [fcb80e4af9](https://linux-hardware.org/?probe=fcb80e4af9) | Nov 09, 2020 |
| Gigabyte      | H110M-S2-CF                 | [4858fd1da2](https://linux-hardware.org/?probe=4858fd1da2) | Nov 08, 2020 |
| ASUSTek       | P8H67                       | [1b9d632f57](https://linux-hardware.org/?probe=1b9d632f57) | Nov 07, 2020 |
| Biostar       | A10N-8800E                  | [6304ed546b](https://linux-hardware.org/?probe=6304ed546b) | Nov 07, 2020 |
| Gigabyte      | 970-GAMING                  | [27d72d4f03](https://linux-hardware.org/?probe=27d72d4f03) | Nov 07, 2020 |
| Gigabyte      | 970-GAMING                  | [edd78bf9af](https://linux-hardware.org/?probe=edd78bf9af) | Nov 07, 2020 |
| Dell          | 0HN7XN A01                  | [cd12fff60a](https://linux-hardware.org/?probe=cd12fff60a) | Nov 06, 2020 |
| MSI           | B85M-E45                    | [383b2181e0](https://linux-hardware.org/?probe=383b2181e0) | Nov 06, 2020 |
| Gigabyte      | B450M S2H                   | [e26ce61aa3](https://linux-hardware.org/?probe=e26ce61aa3) | Nov 04, 2020 |
| ASUSTek       | P5P43TD                     | [4d4e9641d5](https://linux-hardware.org/?probe=4d4e9641d5) | Nov 04, 2020 |
| Unknown       | i845                        | [cc0e3c35e7](https://linux-hardware.org/?probe=cc0e3c35e7) | Nov 03, 2020 |
| Gigabyte      | H170-D3H-CF                 | [8220a96972](https://linux-hardware.org/?probe=8220a96972) | Nov 02, 2020 |
| ASUSTek       | M5A97 R2.0                  | [b0b7e81d99](https://linux-hardware.org/?probe=b0b7e81d99) | Oct 30, 2020 |
| Gigabyte      | GA-780T-D3L                 | [eb0b812639](https://linux-hardware.org/?probe=eb0b812639) | Oct 30, 2020 |
| Gigabyte      | GA-780T-D3L                 | [612bc5042e](https://linux-hardware.org/?probe=612bc5042e) | Oct 30, 2020 |
| Gigabyte      | Z170-HD3P-CF                | [f01fbc2512](https://linux-hardware.org/?probe=f01fbc2512) | Oct 30, 2020 |
| ASRock        | X570 Phantom Gaming 4S      | [37b305be7d](https://linux-hardware.org/?probe=37b305be7d) | Oct 28, 2020 |
| Gigabyte      | H55M-S2V                    | [a4e6dcd1e8](https://linux-hardware.org/?probe=a4e6dcd1e8) | Oct 26, 2020 |
| Biostar       | N61PB-M2S                   | [43719f7617](https://linux-hardware.org/?probe=43719f7617) | Oct 25, 2020 |
| ASUSTek       | P5P43TD                     | [4c29740078](https://linux-hardware.org/?probe=4c29740078) | Oct 24, 2020 |
| ASUSTek       | PRIME Z390-P                | [7e20defaed](https://linux-hardware.org/?probe=7e20defaed) | Oct 24, 2020 |
| MSI           | A68HM-P33 V2                | [eb7cff2f60](https://linux-hardware.org/?probe=eb7cff2f60) | Oct 24, 2020 |
| ASRock        | H77M                        | [79eb206e14](https://linux-hardware.org/?probe=79eb206e14) | Oct 23, 2020 |
| Biostar       | B350GT5                     | [2c6c750609](https://linux-hardware.org/?probe=2c6c750609) | Oct 23, 2020 |
| ASUSTek       | M2A-VM                      | [31e48d87df](https://linux-hardware.org/?probe=31e48d87df) | Oct 23, 2020 |
| ASUSTek       | PRIME A320M-K               | [d46ffd3882](https://linux-hardware.org/?probe=d46ffd3882) | Oct 22, 2020 |
| Jingsha/Kl... | X99 Beta vk.com/@2485616    | [1d99070f82](https://linux-hardware.org/?probe=1d99070f82) | Oct 21, 2020 |
| ASUSTek       | M2A-VM                      | [89b395fc7f](https://linux-hardware.org/?probe=89b395fc7f) | Oct 21, 2020 |
| ASUSTek       | M2A-VM                      | [602a093104](https://linux-hardware.org/?probe=602a093104) | Oct 21, 2020 |
| ASUSTek       | Maximus VI IMPACT           | [36c8fb3de6](https://linux-hardware.org/?probe=36c8fb3de6) | Oct 20, 2020 |
| Gigabyte      | GA-78LMT-S2                 | [f62b980eb0](https://linux-hardware.org/?probe=f62b980eb0) | Oct 19, 2020 |
| ASUSTek       | EB1012G                     | [95a54c7d29](https://linux-hardware.org/?probe=95a54c7d29) | Oct 19, 2020 |
| ASUSTek       | Maximus VI IMPACT           | [047afd8c7b](https://linux-hardware.org/?probe=047afd8c7b) | Oct 19, 2020 |
| ASUSTek       | J3455M-E                    | [48b82345ab](https://linux-hardware.org/?probe=48b82345ab) | Oct 19, 2020 |
| ASUSTek       | J3455M-E                    | [03d2612264](https://linux-hardware.org/?probe=03d2612264) | Oct 19, 2020 |
| ASUSTek       | P8H61-M LX3                 | [f6f6bc4823](https://linux-hardware.org/?probe=f6f6bc4823) | Oct 19, 2020 |
| ASUSTek       | PRIME Z390-P                | [98ab87075c](https://linux-hardware.org/?probe=98ab87075c) | Oct 18, 2020 |
| Gigabyte      | Z370P D3-CF                 | [3ce499dd7d](https://linux-hardware.org/?probe=3ce499dd7d) | Oct 17, 2020 |
| Gigabyte      | Z370P D3-CF                 | [05ed14e5f3](https://linux-hardware.org/?probe=05ed14e5f3) | Oct 17, 2020 |
| ASUSTek       | P9X79                       | [e0a6bc45ee](https://linux-hardware.org/?probe=e0a6bc45ee) | Oct 17, 2020 |
| ASUSTek       | P9X79                       | [d14403a73b](https://linux-hardware.org/?probe=d14403a73b) | Oct 17, 2020 |
| ASUSTek       | P8H61-M LX3                 | [f7026abc5a](https://linux-hardware.org/?probe=f7026abc5a) | Oct 16, 2020 |
| Biostar       | H81MLV3                     | [d5c06dea29](https://linux-hardware.org/?probe=d5c06dea29) | Oct 16, 2020 |
| ASUSTek       | M2A-VM                      | [1c0ef6e25d](https://linux-hardware.org/?probe=1c0ef6e25d) | Oct 16, 2020 |
| ASUSTek       | M2A-VM                      | [b8a0c6dc95](https://linux-hardware.org/?probe=b8a0c6dc95) | Oct 16, 2020 |
| MSI           | 760GM-P23                   | [677c251a9b](https://linux-hardware.org/?probe=677c251a9b) | Oct 15, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [aea7dc9a63](https://linux-hardware.org/?probe=aea7dc9a63) | Oct 14, 2020 |
| ASUSTek       | P8Z77-V LX                  | [172e3d65db](https://linux-hardware.org/?probe=172e3d65db) | Oct 14, 2020 |
| ASUSTek       | P5Q3                        | [9d6e8131e9](https://linux-hardware.org/?probe=9d6e8131e9) | Oct 14, 2020 |
| ASUSTek       | P5Q3                        | [35e64cec70](https://linux-hardware.org/?probe=35e64cec70) | Oct 14, 2020 |
| ASUSTek       | P8B75-M LE                  | [d0dd87e199](https://linux-hardware.org/?probe=d0dd87e199) | Oct 13, 2020 |
| ASUSTek       | Z10PE-D16 WS                | [7bf945cd18](https://linux-hardware.org/?probe=7bf945cd18) | Oct 13, 2020 |
| ASUSTek       | H81M-R                      | [b8448dff96](https://linux-hardware.org/?probe=b8448dff96) | Oct 13, 2020 |
| Hardkernel    | ODROID-H2                   | [a5d75a24e5](https://linux-hardware.org/?probe=a5d75a24e5) | Oct 13, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [c0ea5b4beb](https://linux-hardware.org/?probe=c0ea5b4beb) | Oct 13, 2020 |
| ASUSTek       | Maximus VI IMPACT           | [323bcccd39](https://linux-hardware.org/?probe=323bcccd39) | Oct 13, 2020 |
| ASRock        | X570M Pro4                  | [11624f2e68](https://linux-hardware.org/?probe=11624f2e68) | Oct 12, 2020 |
| HP            | 1495                        | [1225d21cda](https://linux-hardware.org/?probe=1225d21cda) | Oct 12, 2020 |
| ASRock        | N68-VS3 UCC                 | [4331cfa1fc](https://linux-hardware.org/?probe=4331cfa1fc) | Oct 11, 2020 |
| Gigabyte      | A320M-H-CF                  | [2c0322f113](https://linux-hardware.org/?probe=2c0322f113) | Oct 10, 2020 |
| MSI           | Z270 SLI                    | [5b7d47c841](https://linux-hardware.org/?probe=5b7d47c841) | Oct 07, 2020 |
| MSI           | Z270 SLI                    | [54020e2494](https://linux-hardware.org/?probe=54020e2494) | Oct 07, 2020 |
| MSI           | H310M PRO-VD PLUS           | [90021d6e51](https://linux-hardware.org/?probe=90021d6e51) | Oct 05, 2020 |
| Gigabyte      | H170-D3H-CF                 | [c73f4878af](https://linux-hardware.org/?probe=c73f4878af) | Oct 04, 2020 |
| ASUSTek       | TUF B450-PRO GAMING         | [0d929d023c](https://linux-hardware.org/?probe=0d929d023c) | Oct 02, 2020 |
| ASUSTek       | P8P67 LE                    | [ead5ba8555](https://linux-hardware.org/?probe=ead5ba8555) | Oct 02, 2020 |
| ASUSTek       | M5A97 R2.0                  | [9ef1953e5b](https://linux-hardware.org/?probe=9ef1953e5b) | Sep 28, 2020 |
| ASRock        | X570 Taichi                 | [d1c0a4fbe3](https://linux-hardware.org/?probe=d1c0a4fbe3) | Sep 28, 2020 |
| ASUSTek       | P5P43TD                     | [cebf875c2a](https://linux-hardware.org/?probe=cebf875c2a) | Sep 28, 2020 |
| Gigabyte      | EP41-UD3L                   | [ac9a3861d4](https://linux-hardware.org/?probe=ac9a3861d4) | Sep 28, 2020 |
| ASUSTek       | PRIME B550-PLUS             | [d9d829abad](https://linux-hardware.org/?probe=d9d829abad) | Sep 26, 2020 |
| Gigabyte      | H310M S2V x.x               | [67121d83ac](https://linux-hardware.org/?probe=67121d83ac) | Sep 25, 2020 |
| MSI           | Z270 SLI                    | [0cf802440d](https://linux-hardware.org/?probe=0cf802440d) | Sep 25, 2020 |
| ASUSTek       | M4N68T-M LE                 | [1b34fcd995](https://linux-hardware.org/?probe=1b34fcd995) | Sep 24, 2020 |
| ASUSTek       | P4P800-MX                   | [43697b92f4](https://linux-hardware.org/?probe=43697b92f4) | Sep 24, 2020 |
| Gigabyte      | MZBSWMP-00                  | [3bd3cd506e](https://linux-hardware.org/?probe=3bd3cd506e) | Sep 23, 2020 |
| Gigabyte      | B150M-D3V-CF                | [54a8ccd94a](https://linux-hardware.org/?probe=54a8ccd94a) | Sep 22, 2020 |
| MSI           | Z270 SLI                    | [5921ce7613](https://linux-hardware.org/?probe=5921ce7613) | Sep 22, 2020 |
| Gigabyte      | Z68M-D2H                    | [d746ae5a52](https://linux-hardware.org/?probe=d746ae5a52) | Sep 19, 2020 |
| ASUSTek       | F2A55-M LE                  | [b3e51decec](https://linux-hardware.org/?probe=b3e51decec) | Sep 18, 2020 |
| Gigabyte      | P41T-D3P                    | [7115241a45](https://linux-hardware.org/?probe=7115241a45) | Sep 18, 2020 |
| ASUSTek       | PRIME B550-PLUS             | [2139937829](https://linux-hardware.org/?probe=2139937829) | Sep 15, 2020 |
| MSI           | Z270 SLI                    | [f84871cd9d](https://linux-hardware.org/?probe=f84871cd9d) | Sep 15, 2020 |
| ASUSTek       | P8H61-M LX2                 | [b501542a04](https://linux-hardware.org/?probe=b501542a04) | Sep 11, 2020 |
| ASUSTek       | P8H61-M LX2                 | [d9afdd4279](https://linux-hardware.org/?probe=d9afdd4279) | Sep 11, 2020 |
| ASUSTek       | PRIME B450M-A               | [094f8c8c6d](https://linux-hardware.org/?probe=094f8c8c6d) | Sep 11, 2020 |
| ASUSTek       | PRIME H310M-K R2.0          | [0c934022c7](https://linux-hardware.org/?probe=0c934022c7) | Sep 10, 2020 |
| MSI           | B450 TOMAHAWK MAX           | [a1c5ad725e](https://linux-hardware.org/?probe=a1c5ad725e) | Sep 10, 2020 |
| ASUSTek       | M5A78L-M LE                 | [21857331ee](https://linux-hardware.org/?probe=21857331ee) | Sep 10, 2020 |
| Gigabyte      | B450M DS3H-CF               | [8a6c8ee9e6](https://linux-hardware.org/?probe=8a6c8ee9e6) | Sep 10, 2020 |
| Lenovo        | CRESCENTBAY No DPK          | [1dbe6d65ef](https://linux-hardware.org/?probe=1dbe6d65ef) | Sep 06, 2020 |
| Biostar       | NF520D3                     | [8ce3b974c7](https://linux-hardware.org/?probe=8ce3b974c7) | Sep 06, 2020 |
| MSI           | 0AB8                        | [7e3adeac5e](https://linux-hardware.org/?probe=7e3adeac5e) | Sep 01, 2020 |
| Gigabyte      | Z87X-UD5H-CF                | [cbab4d3ea3](https://linux-hardware.org/?probe=cbab4d3ea3) | Aug 31, 2020 |
| ASUSTek       | PRIME A320M-K               | [bf75297123](https://linux-hardware.org/?probe=bf75297123) | Aug 30, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [ef8e25ea53](https://linux-hardware.org/?probe=ef8e25ea53) | Aug 29, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [635af33b30](https://linux-hardware.org/?probe=635af33b30) | Aug 29, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [9a13e7dfb5](https://linux-hardware.org/?probe=9a13e7dfb5) | Aug 29, 2020 |
| MSI           | Z77IA-E53                   | [bf99082e95](https://linux-hardware.org/?probe=bf99082e95) | Aug 28, 2020 |
| ASUSTek       | PRIME Z390-P                | [cfa898d2df](https://linux-hardware.org/?probe=cfa898d2df) | Aug 28, 2020 |
| ASUSTek       | P8H61-M LX3                 | [58b23e106e](https://linux-hardware.org/?probe=58b23e106e) | Aug 26, 2020 |
| ASRock        | Z390 Extreme4               | [b4bf4e6942](https://linux-hardware.org/?probe=b4bf4e6942) | Aug 26, 2020 |
| ASRock        | Z390 Extreme4               | [88c8515a10](https://linux-hardware.org/?probe=88c8515a10) | Aug 26, 2020 |
| ASRock        | Z390 Extreme4               | [b22caa8431](https://linux-hardware.org/?probe=b22caa8431) | Aug 26, 2020 |
| Gigabyte      | H55M-S2V                    | [ad1eb0bf61](https://linux-hardware.org/?probe=ad1eb0bf61) | Aug 21, 2020 |
| Unknown       | X79                         | [a38602b576](https://linux-hardware.org/?probe=a38602b576) | Aug 21, 2020 |
| ASUSTek       | P5KPL-AM SE                 | [310bdac819](https://linux-hardware.org/?probe=310bdac819) | Aug 20, 2020 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [d5b08aff8e](https://linux-hardware.org/?probe=d5b08aff8e) | Aug 18, 2020 |
| ECS           | A85F2-A GOLDEN              | [aadd40841f](https://linux-hardware.org/?probe=aadd40841f) | Aug 18, 2020 |
| Gigabyte      | H55M-S2V                    | [17b83799b0](https://linux-hardware.org/?probe=17b83799b0) | Aug 17, 2020 |
| ASUSTek       | TUF B450-PRO GAMING         | [07fb1a68cb](https://linux-hardware.org/?probe=07fb1a68cb) | Aug 16, 2020 |
| Biostar       | NF520D3                     | [3425ae54cc](https://linux-hardware.org/?probe=3425ae54cc) | Aug 15, 2020 |
| ASRock        | Z87 Pro3                    | [f5a72d7805](https://linux-hardware.org/?probe=f5a72d7805) | Aug 15, 2020 |
| Biostar       | NF520D3                     | [bac6a33585](https://linux-hardware.org/?probe=bac6a33585) | Aug 13, 2020 |
| Gigabyte      | A320M-S2H V2-CF             | [8a1d277305](https://linux-hardware.org/?probe=8a1d277305) | Aug 12, 2020 |
| Gigabyte      | B75M-D3H                    | [cd5789f91b](https://linux-hardware.org/?probe=cd5789f91b) | Aug 11, 2020 |
| Gigabyte      | A320M-S2H V2-CF             | [5b88f5404c](https://linux-hardware.org/?probe=5b88f5404c) | Aug 10, 2020 |
| ASUSTek       | PRIME H370M-PLUS            | [0c50242cc5](https://linux-hardware.org/?probe=0c50242cc5) | Aug 09, 2020 |
| ASRock        | Z87 Pro3                    | [9fc26dbca3](https://linux-hardware.org/?probe=9fc26dbca3) | Aug 07, 2020 |
| ASRock        | Z87 Pro3                    | [fda49e84b2](https://linux-hardware.org/?probe=fda49e84b2) | Aug 06, 2020 |
| Intel         | E5 (INTEL Xeon E5/Core i... | [3917eb1849](https://linux-hardware.org/?probe=3917eb1849) | Aug 05, 2020 |
| MSI           | A68HM-P33 V2                | [87b074d7e9](https://linux-hardware.org/?probe=87b074d7e9) | Aug 04, 2020 |
| MSI           | 870A-G54                    | [1caec041cb](https://linux-hardware.org/?probe=1caec041cb) | Aug 03, 2020 |
| Gigabyte      | P35-DS4                     | [d9b3b9a12e](https://linux-hardware.org/?probe=d9b3b9a12e) | Aug 02, 2020 |
| Gigabyte      | P35-DS4                     | [3a33cfc73c](https://linux-hardware.org/?probe=3a33cfc73c) | Aug 02, 2020 |
| ASUSTek       | A88XM-A                     | [08ce52da89](https://linux-hardware.org/?probe=08ce52da89) | Aug 01, 2020 |
| Gigabyte      | B450 AORUS PRO-CF           | [b70c7089e2](https://linux-hardware.org/?probe=b70c7089e2) | Jul 28, 2020 |
| ASUSTek       | M4N78 SE                    | [8d923c87e6](https://linux-hardware.org/?probe=8d923c87e6) | Jul 28, 2020 |
| ASUSTek       | M2N-E SLI                   | [4421861eba](https://linux-hardware.org/?probe=4421861eba) | Jul 26, 2020 |
| ASUSTek       | M2A74-AM SE                 | [505cf8635f](https://linux-hardware.org/?probe=505cf8635f) | Jul 26, 2020 |
| ASUSTek       | M2A74-AM SE                 | [b83a4fee7b](https://linux-hardware.org/?probe=b83a4fee7b) | Jul 26, 2020 |
| MSI           | 870-C45                     | [ba924ecb3d](https://linux-hardware.org/?probe=ba924ecb3d) | Jul 26, 2020 |
| ASUSTek       | J3455M-E                    | [6e1e02a364](https://linux-hardware.org/?probe=6e1e02a364) | Jul 25, 2020 |
| ASUSTek       | B150M-A D3                  | [5b142bd4cd](https://linux-hardware.org/?probe=5b142bd4cd) | Jul 25, 2020 |
| ASRock        | X570M Pro4                  | [9d082a4d26](https://linux-hardware.org/?probe=9d082a4d26) | Jul 24, 2020 |
| Gigabyte      | B360M DS3H                  | [be78e318ef](https://linux-hardware.org/?probe=be78e318ef) | Jul 23, 2020 |
| ASUSTek       | P8H61-M LX3                 | [29612d6567](https://linux-hardware.org/?probe=29612d6567) | Jul 23, 2020 |
| ASUSTek       | P8H61-M LX3                 | [13433e1686](https://linux-hardware.org/?probe=13433e1686) | Jul 23, 2020 |
| Gigabyte      | G31M-ES2L                   | [cbad09cb89](https://linux-hardware.org/?probe=cbad09cb89) | Jul 21, 2020 |
| Gigabyte      | 8I945GMF                    | [9f69fe7461](https://linux-hardware.org/?probe=9f69fe7461) | Jul 21, 2020 |
| ASUSTek       | ROG STRIX B360-F GAMING     | [73f6841b3c](https://linux-hardware.org/?probe=73f6841b3c) | Jul 18, 2020 |
| ASRock        | H61M-VG3                    | [16e3dae154](https://linux-hardware.org/?probe=16e3dae154) | Jul 14, 2020 |
| ASUSTek       | P5PL2                       | [d25ecd5ae3](https://linux-hardware.org/?probe=d25ecd5ae3) | Jul 14, 2020 |
| Gigabyte      | H110-D3A-CF                 | [1088c491f3](https://linux-hardware.org/?probe=1088c491f3) | Jul 13, 2020 |
| Gigabyte      | H110-D3A-CF                 | [f18a2acbc2](https://linux-hardware.org/?probe=f18a2acbc2) | Jul 13, 2020 |
| Intel         | D945GTP AAC97837-301        | [58a8455982](https://linux-hardware.org/?probe=58a8455982) | Jul 12, 2020 |
| ASUSTek       | P4P800-MX                   | [26ebac5a96](https://linux-hardware.org/?probe=26ebac5a96) | Jul 09, 2020 |
| ASUSTek       | M4N78 SE                    | [55f920ebf4](https://linux-hardware.org/?probe=55f920ebf4) | Jul 09, 2020 |
| ASUSTek       | M4N78 SE                    | [c5a14558f3](https://linux-hardware.org/?probe=c5a14558f3) | Jul 09, 2020 |
| Gigabyte      | F2A68HM-D3H                 | [1dafa03f3b](https://linux-hardware.org/?probe=1dafa03f3b) | Jul 03, 2020 |
| ASUSTek       | PRIME B450M-A               | [5b37542530](https://linux-hardware.org/?probe=5b37542530) | Jul 03, 2020 |
| ASRock        | A320M-HDV R4.0              | [32a97c32d2](https://linux-hardware.org/?probe=32a97c32d2) | Jul 03, 2020 |
| Gigabyte      | 945GCM-S2L                  | [95b419a5f1](https://linux-hardware.org/?probe=95b419a5f1) | Jul 02, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [56fdbfc5b9](https://linux-hardware.org/?probe=56fdbfc5b9) | Jul 01, 2020 |
| ASUSTek       | P5K                         | [a083847a4c](https://linux-hardware.org/?probe=a083847a4c) | Jun 29, 2020 |
| MSI           | H61M-P20                    | [ff1dc7710d](https://linux-hardware.org/?probe=ff1dc7710d) | Jun 29, 2020 |
| ASUSTek       | F1A75-V EVO                 | [6b7ccf96c5](https://linux-hardware.org/?probe=6b7ccf96c5) | Jun 28, 2020 |
| ASUSTek       | P8H61-MX                    | [2e8e1e312c](https://linux-hardware.org/?probe=2e8e1e312c) | Jun 27, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ccb9b97aab](https://linux-hardware.org/?probe=ccb9b97aab) | Jun 27, 2020 |
| ASRock        | 760GM-GS3                   | [c6327c8dfc](https://linux-hardware.org/?probe=c6327c8dfc) | Jun 27, 2020 |
| HP            | 3648h                       | [eeb1828e8c](https://linux-hardware.org/?probe=eeb1828e8c) | Jun 27, 2020 |
| Gigabyte      | 970-GAMING                  | [e78780d56d](https://linux-hardware.org/?probe=e78780d56d) | Jun 24, 2020 |
| Gigabyte      | 970-GAMING                  | [f3886361af](https://linux-hardware.org/?probe=f3886361af) | Jun 24, 2020 |
| Biostar       | NF61S-M2A                   | [c071fa24d8](https://linux-hardware.org/?probe=c071fa24d8) | Jun 21, 2020 |
| ASRock        | Z370 Pro4                   | [6ff0ce6501](https://linux-hardware.org/?probe=6ff0ce6501) | Jun 17, 2020 |
| HP            | 3648h                       | [a95b864dfd](https://linux-hardware.org/?probe=a95b864dfd) | Jun 13, 2020 |
| ASUSTek       | M4A77D                      | [7deecc52f7](https://linux-hardware.org/?probe=7deecc52f7) | Jun 12, 2020 |
| ASUSTek       | PRIME Z490-P                | [a3e534b4f8](https://linux-hardware.org/?probe=a3e534b4f8) | Jun 10, 2020 |
| ASUSTek       | PRIME H310I-PLUS R2.0       | [c64e574a2c](https://linux-hardware.org/?probe=c64e574a2c) | Jun 08, 2020 |
| Gigabyte      | H370M D3H-CF                | [127d130733](https://linux-hardware.org/?probe=127d130733) | Jun 05, 2020 |
| Dell          | 0YXT71 A03                  | [52ca2fd2ed](https://linux-hardware.org/?probe=52ca2fd2ed) | Jun 05, 2020 |
| Gigabyte      | H55M-S2V                    | [dd9d5892ff](https://linux-hardware.org/?probe=dd9d5892ff) | Jun 03, 2020 |
| ASUSTek       | ROG Maximus X FORMULA       | [31b2fe665f](https://linux-hardware.org/?probe=31b2fe665f) | Jun 02, 2020 |
| ASUSTek       | ROG Maximus X FORMULA       | [57c2569070](https://linux-hardware.org/?probe=57c2569070) | Jun 02, 2020 |
| Gigabyte      | H55M-S2V                    | [2f39d3e79e](https://linux-hardware.org/?probe=2f39d3e79e) | May 31, 2020 |
| ASUSTek       | P8Z77-V DELUXE              | [67caf783f8](https://linux-hardware.org/?probe=67caf783f8) | May 31, 2020 |
| Gigabyte      | Z68M-D2H                    | [fbbc2c4d98](https://linux-hardware.org/?probe=fbbc2c4d98) | May 30, 2020 |
| Gigabyte      | Z68M-D2H                    | [ca71847ca1](https://linux-hardware.org/?probe=ca71847ca1) | May 30, 2020 |
| MSI           | B450 TOMAHAWK MAX           | [63626997c7](https://linux-hardware.org/?probe=63626997c7) | May 30, 2020 |
| ASUSTek       | P8Z68-V GEN3                | [8b634e5359](https://linux-hardware.org/?probe=8b634e5359) | May 29, 2020 |
| HP            | 2B34                        | [e04fb10b73](https://linux-hardware.org/?probe=e04fb10b73) | May 29, 2020 |
| Gigabyte      | Z370M D3H-CF                | [9cb29140d4](https://linux-hardware.org/?probe=9cb29140d4) | May 26, 2020 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [71c90f0d94](https://linux-hardware.org/?probe=71c90f0d94) | May 26, 2020 |
| ASUSTek       | M5A97 R2.0                  | [2bcd432598](https://linux-hardware.org/?probe=2bcd432598) | May 26, 2020 |
| ASUSTek       | TUF B350M-PLUS GAMING       | [0387f23f41](https://linux-hardware.org/?probe=0387f23f41) | May 25, 2020 |
| MSI           | B250M PRO-VD                | [04e199ebc9](https://linux-hardware.org/?probe=04e199ebc9) | May 25, 2020 |
| Gigabyte      | H81M-S1                     | [a498548a5c](https://linux-hardware.org/?probe=a498548a5c) | May 25, 2020 |
| ASUSTek       | P7P55D PRO                  | [2ea71d8f5d](https://linux-hardware.org/?probe=2ea71d8f5d) | May 25, 2020 |
| ASUSTek       | P7P55D PRO                  | [3cd640ef5e](https://linux-hardware.org/?probe=3cd640ef5e) | May 25, 2020 |
| ASUSTek       | A8N5X                       | [0a1b9c0d45](https://linux-hardware.org/?probe=0a1b9c0d45) | May 25, 2020 |
| ASUSTek       | PRIME B350-PLUS             | [93ee9d0fdb](https://linux-hardware.org/?probe=93ee9d0fdb) | May 25, 2020 |
| Dell          | 0DR845                      | [1f3a84e812](https://linux-hardware.org/?probe=1f3a84e812) | May 25, 2020 |
| ASRock        | N68-GS3 UCC                 | [39c1c9ea3b](https://linux-hardware.org/?probe=39c1c9ea3b) | May 23, 2020 |
| ASUSTek       | M4A78LT-M-LE                | [b80e9b6750](https://linux-hardware.org/?probe=b80e9b6750) | May 22, 2020 |
| Gigabyte      | H55M-S2V                    | [a18834aa45](https://linux-hardware.org/?probe=a18834aa45) | May 21, 2020 |
| ASUSTek       | P5PE-VM                     | [298c1239dd](https://linux-hardware.org/?probe=298c1239dd) | May 20, 2020 |
| Gigabyte      | X58A-UD3R                   | [b67c54f0c4](https://linux-hardware.org/?probe=b67c54f0c4) | May 19, 2020 |
| Dell          | 09M8Y8 A01                  | [3a804e8e43](https://linux-hardware.org/?probe=3a804e8e43) | May 18, 2020 |
| MSI           | B450 TOMAHAWK MAX           | [f12e44db8e](https://linux-hardware.org/?probe=f12e44db8e) | May 17, 2020 |
| MSI           | B450 TOMAHAWK MAX           | [6a94503f31](https://linux-hardware.org/?probe=6a94503f31) | May 17, 2020 |
| Gigabyte      | Z68M-D2H                    | [70c167639c](https://linux-hardware.org/?probe=70c167639c) | May 15, 2020 |
| ASUSTek       | P8Z68-V LX                  | [47c3a2cc2e](https://linux-hardware.org/?probe=47c3a2cc2e) | May 14, 2020 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | [76b4a9e5f4](https://linux-hardware.org/?probe=76b4a9e5f4) | May 14, 2020 |
| ASUSTek       | Z87-A                       | [ba975fca11](https://linux-hardware.org/?probe=ba975fca11) | May 14, 2020 |
| ASUSTek       | P8Z68-V LX                  | [a07aa56904](https://linux-hardware.org/?probe=a07aa56904) | May 13, 2020 |
| ASUSTek       | H110I-PLUS                  | [1c1568f41e](https://linux-hardware.org/?probe=1c1568f41e) | May 13, 2020 |
| Dell          | 09M8Y8 A01                  | [b7320814a2](https://linux-hardware.org/?probe=b7320814a2) | May 12, 2020 |
| Gigabyte      | 945GCMX-S2                  | [e68c65a99d](https://linux-hardware.org/?probe=e68c65a99d) | May 11, 2020 |
| MSI           | Z390-A PRO                  | [604b07cdcf](https://linux-hardware.org/?probe=604b07cdcf) | May 11, 2020 |
| Gigabyte      | 945GCMX-S2                  | [568a188623](https://linux-hardware.org/?probe=568a188623) | May 11, 2020 |
| ASUSTek       | P8B75-V                     | [05258aea35](https://linux-hardware.org/?probe=05258aea35) | May 11, 2020 |
| ASUSTek       | P8Z68-V PRO                 | [444d38822f](https://linux-hardware.org/?probe=444d38822f) | May 08, 2020 |
| MSI           | H81M-P33                    | [dd13d43263](https://linux-hardware.org/?probe=dd13d43263) | May 08, 2020 |
| ASUSTek       | P5QL                        | [ee2cb4e2d9](https://linux-hardware.org/?probe=ee2cb4e2d9) | May 05, 2020 |
| ASUSTek       | P5KPL-AM                    | [0721a0e6d2](https://linux-hardware.org/?probe=0721a0e6d2) | May 05, 2020 |
| MSI           | A88XM-E35                   | [5299d28e83](https://linux-hardware.org/?probe=5299d28e83) | May 04, 2020 |
| ASUSTek       | PRIME A320M-R               | [c00bf5a392](https://linux-hardware.org/?probe=c00bf5a392) | May 03, 2020 |
| ASUSTek       | P8Z68-V LX                  | [73139715b7](https://linux-hardware.org/?probe=73139715b7) | May 02, 2020 |
| Intel         | X79 V2.4F                   | [2a8dbc42f7](https://linux-hardware.org/?probe=2a8dbc42f7) | May 01, 2020 |
| ASUSTek       | P8B75-M LE                  | [96df54c342](https://linux-hardware.org/?probe=96df54c342) | May 01, 2020 |
| Dell          | 0WR7PY A02                  | [fdc9bf0c1b](https://linux-hardware.org/?probe=fdc9bf0c1b) | May 01, 2020 |
| ASUSTek       | F1A55-M LX3                 | [5c0845dd0a](https://linux-hardware.org/?probe=5c0845dd0a) | Apr 30, 2020 |
| ASUSTek       | P5LD2-X                     | [823d3f341c](https://linux-hardware.org/?probe=823d3f341c) | Apr 29, 2020 |
| ASRock        | 960GC-GS FX                 | [e08f749ff4](https://linux-hardware.org/?probe=e08f749ff4) | Apr 29, 2020 |
| ASRock        | 960GC-GS FX                 | [19044d1ae2](https://linux-hardware.org/?probe=19044d1ae2) | Apr 28, 2020 |
| Gigabyte      | B75M-D3H                    | [b10c21c02f](https://linux-hardware.org/?probe=b10c21c02f) | Apr 28, 2020 |
| Gigabyte      | B450M DS3H-CF               | [a1323325ae](https://linux-hardware.org/?probe=a1323325ae) | Apr 27, 2020 |
| Gigabyte      | B450M DS3H-CF               | [d32eea4750](https://linux-hardware.org/?probe=d32eea4750) | Apr 27, 2020 |
| ASUSTek       | M4A87TD/USB3                | [cee7560096](https://linux-hardware.org/?probe=cee7560096) | Apr 26, 2020 |
| ASUSTek       | F1A75-V PRO                 | [818c11a5f3](https://linux-hardware.org/?probe=818c11a5f3) | Apr 26, 2020 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | [c232324d73](https://linux-hardware.org/?probe=c232324d73) | Apr 23, 2020 |
| ASUSTek       | M5A97 PRO                   | [49aba0085a](https://linux-hardware.org/?probe=49aba0085a) | Apr 23, 2020 |
| ASRock        | J4205-ITX                   | [4fc5d5a325](https://linux-hardware.org/?probe=4fc5d5a325) | Apr 22, 2020 |
| ASUSTek       | H110M-C                     | [451ad08bd2](https://linux-hardware.org/?probe=451ad08bd2) | Apr 22, 2020 |
| ASUSTek       | M5A97 PRO                   | [856b65674a](https://linux-hardware.org/?probe=856b65674a) | Apr 21, 2020 |
| Gigabyte      | GA-78LMT-S2                 | [cb626d886c](https://linux-hardware.org/?probe=cb626d886c) | Apr 19, 2020 |
| ASUSTek       | P5LD2-X                     | [bcf9bd4015](https://linux-hardware.org/?probe=bcf9bd4015) | Apr 16, 2020 |
| ASUSTek       | H110I-PLUS                  | [fc563af1c9](https://linux-hardware.org/?probe=fc563af1c9) | Apr 16, 2020 |
| ASUSTek       | H110I-PLUS                  | [de5d8e4425](https://linux-hardware.org/?probe=de5d8e4425) | Apr 16, 2020 |
| ASRock        | H110M-HDV R3.0              | [898f8c5426](https://linux-hardware.org/?probe=898f8c5426) | Apr 16, 2020 |
| ASRock        | H110M-HDV R3.0              | [407ab4e058](https://linux-hardware.org/?probe=407ab4e058) | Apr 16, 2020 |
| ASUSTek       | F2A85-V                     | [191873340a](https://linux-hardware.org/?probe=191873340a) | Apr 15, 2020 |
| ASUSTek       | P5LD2-X                     | [ab71658860](https://linux-hardware.org/?probe=ab71658860) | Apr 14, 2020 |
| ASUSTek       | M5A97 R2.0                  | [c04f443549](https://linux-hardware.org/?probe=c04f443549) | Apr 14, 2020 |
| ASUSTek       | P5LD2-X                     | [94dd753215](https://linux-hardware.org/?probe=94dd753215) | Apr 14, 2020 |
| ASUSTek       | P5LD2-X                     | [2e3b3342b9](https://linux-hardware.org/?probe=2e3b3342b9) | Apr 14, 2020 |
| ASRock        | A320M-DVS R3.0              | [57e24e4122](https://linux-hardware.org/?probe=57e24e4122) | Apr 13, 2020 |
| Gigabyte      | Z68M-D2H                    | [3db29a7f67](https://linux-hardware.org/?probe=3db29a7f67) | Apr 12, 2020 |
| Gigabyte      | B75M-D3H                    | [5d26772088](https://linux-hardware.org/?probe=5d26772088) | Apr 12, 2020 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [21cf23bd85](https://linux-hardware.org/?probe=21cf23bd85) | Apr 10, 2020 |
| ASUSTek       | P5LD2-X                     | [08961ef3bf](https://linux-hardware.org/?probe=08961ef3bf) | Apr 09, 2020 |
| ASUSTek       | P5GV-MX                     | [edce750bf7](https://linux-hardware.org/?probe=edce750bf7) | Apr 07, 2020 |
| ASRock        | A75 Pro4-M                  | [41e33cac51](https://linux-hardware.org/?probe=41e33cac51) | Apr 07, 2020 |
| MSI           | MS-7255 V2.0                | [1a8cbca9d7](https://linux-hardware.org/?probe=1a8cbca9d7) | Apr 06, 2020 |
| MSI           | MS-7255 V2.0                | [9d5c20570d](https://linux-hardware.org/?probe=9d5c20570d) | Apr 06, 2020 |
| MSI           | MS-7255 V2.0                | [d332ed410e](https://linux-hardware.org/?probe=d332ed410e) | Apr 06, 2020 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [e27a3990b6](https://linux-hardware.org/?probe=e27a3990b6) | Apr 05, 2020 |
| Gigabyte      | H77M-D3H                    | [1051a269d3](https://linux-hardware.org/?probe=1051a269d3) | Apr 03, 2020 |
| ASRock        | N68C-S UCC                  | [a9ed6dc2ca](https://linux-hardware.org/?probe=a9ed6dc2ca) | Apr 01, 2020 |
| ASRock        | A75 Pro4-M                  | [521384031f](https://linux-hardware.org/?probe=521384031f) | Apr 01, 2020 |
| Gigabyte      | H110-D3A-CF                 | [4cbfd9f89d](https://linux-hardware.org/?probe=4cbfd9f89d) | Mar 31, 2020 |
| ASUSTek       | M5A97 PLUS                  | [a4d1612137](https://linux-hardware.org/?probe=a4d1612137) | Mar 30, 2020 |
| Dell          | 09M8Y8 A01                  | [9039b2afe5](https://linux-hardware.org/?probe=9039b2afe5) | Mar 30, 2020 |
| ASUSTek       | P7P55D PRO                  | [613e28f489](https://linux-hardware.org/?probe=613e28f489) | Mar 29, 2020 |
| ASUSTek       | P7P55D PRO                  | [d439ad5058](https://linux-hardware.org/?probe=d439ad5058) | Mar 29, 2020 |
| Dell          | 0WR7PY A02                  | [56dc897dde](https://linux-hardware.org/?probe=56dc897dde) | Mar 29, 2020 |
| Intel         | E5 V3.3A                    | [208481e214](https://linux-hardware.org/?probe=208481e214) | Mar 28, 2020 |
| MSI           | 0AB8                        | [ccee368075](https://linux-hardware.org/?probe=ccee368075) | Mar 27, 2020 |
| ASRock        | J3455-ITX                   | [9be6518d3f](https://linux-hardware.org/?probe=9be6518d3f) | Mar 26, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Ukraine/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| ROSA R10         | 138      | 9.74%   |
| ROSA R11         | 119      | 8.4%    |
| ROSA R8.1        | 104      | 7.34%   |
| Ubuntu 20.04     | 88       | 6.21%   |
| Ubuntu 18.04     | 77       | 5.43%   |
| ROSA R9          | 74       | 5.22%   |
| ROSA R8          | 73       | 5.15%   |
| ROSA R11.1       | 63       | 4.45%   |
| OpenMandriva 4.2 | 40       | 2.82%   |
| Arch             | 27       | 1.91%   |
| OpenMandriva 4.3 | 26       | 1.83%   |
| ROSA 12.2        | 25       | 1.76%   |
| KDE neon 20.04   | 25       | 1.76%   |
| Arch Rolling     | 20       | 1.41%   |
| Debian 11        | 19       | 1.34%   |
| Linux Mint 20    | 18       | 1.27%   |
| Linux Mint 20.2  | 16       | 1.13%   |
| Linux Mint 19.3  | 16       | 1.13%   |
| Linux Mint 20.1  | 15       | 1.06%   |
| Kubuntu 20.04    | 15       | 1.06%   |
| Manjaro          | 13       | 0.92%   |
| Ubuntu 16.04     | 12       | 0.85%   |
| ROSA 12.1        | 12       | 0.85%   |
| Linux Mint 19.1  | 12       | 0.85%   |
| Xubuntu 20.04    | 11       | 0.78%   |
| Xubuntu 18.04    | 11       | 0.78%   |
| Ubuntu 19.10     | 11       | 0.78%   |
| Fedora 33        | 11       | 0.78%   |
| Debian 10        | 11       | 0.78%   |
| Ubuntu 20.10     | 10       | 0.71%   |
| Manjaro 20.2.1   | 10       | 0.71%   |
| Linux Mint 18.3  | 10       | 0.71%   |
| Ubuntu 21.04     | 9        | 0.64%   |
| Ubuntu 19.04     | 9        | 0.64%   |
| ROSA 12          | 8        | 0.56%   |
| Linux Mint 19.2  | 8        | 0.56%   |
| Gentoo 2.7       | 8        | 0.56%   |
| Fedora 34        | 8        | 0.56%   |
| Ubuntu 21.10     | 7        | 0.49%   |
| Fedora 35        | 7        | 0.49%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| ROSA          | 533      | 41.03%  |
| Ubuntu        | 226      | 17.4%   |
| Linux Mint    | 106      | 8.16%   |
| OpenMandriva  | 69       | 5.31%   |
| Manjaro       | 50       | 3.85%   |
| Arch          | 46       | 3.54%   |
| Fedora        | 37       | 2.85%   |
| Debian        | 34       | 2.62%   |
| KDE neon      | 27       | 2.08%   |
| Xubuntu       | 26       | 2%      |
| Kubuntu       | 26       | 2%      |
| Endless       | 13       | 1%      |
| Pop!_OS       | 11       | 0.85%   |
| Gentoo        | 10       | 0.77%   |
| Zorin         | 7        | 0.54%   |
| Ubuntu Unity  | 6        | 0.46%   |
| Ubuntu MATE   | 5        | 0.38%   |
| openSUSE      | 5        | 0.38%   |
| LMDE          | 5        | 0.38%   |
| CentOS        | 5        | 0.38%   |
| BlackPanther  | 5        | 0.38%   |
| Kali          | 4        | 0.31%   |
| ArcoLinux     | 4        | 0.31%   |
| Ubuntu Budgie | 3        | 0.23%   |
| Mageia        | 3        | 0.23%   |
| Elementary    | 3        | 0.23%   |
| Devuan        | 3        | 0.23%   |
| RHEL          | 2        | 0.15%   |
| RELS          | 2        | 0.15%   |
| Clear Linux   | 2        | 0.15%   |
| ALT Linux     | 2        | 0.15%   |
| XF            | 1        | 0.08%   |
| UbuntuDDE     | 1        | 0.08%   |
| Trisquel      | 1        | 0.08%   |
| RED           | 1        | 0.08%   |
| Reborn OS     | 1        | 0.08%   |
| Peppermint    | 1        | 0.08%   |
| Parrot        | 1        | 0.08%   |
| NixOS         | 1        | 0.08%   |
| MX            | 1        | 0.08%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Desktops | Percent |
|-------------------------------------|----------|---------|
| 4.9.60-nrj-desktop-1rosa-x86_64     | 57       | 3.75%   |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 55       | 3.62%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 46       | 3.03%   |
| 5.10.14-desktop-1omv4002            | 39       | 2.57%   |
| 4.1.34-nrj-desktop-2rosa-x86_64     | 34       | 2.24%   |
| 5.10.74-generic-2rosa2021.1-x86_64  | 31       | 2.04%   |
| 4.1.38-nrj-desktop-2rosa-x86_64     | 28       | 1.84%   |
| 5.16.7-desktop-1omv4003             | 26       | 1.71%   |
| 4.1.34-nrj-desktop-2rosa-i586       | 25       | 1.65%   |
| 4.9.9-nrj-desktop-1rosa-x86_64      | 23       | 1.51%   |
| 4.9.60-nrj-desktop-1rosa-i586       | 23       | 1.51%   |
| 4.9.20-nrj-desktop-1rosa-i586       | 21       | 1.38%   |
| 5.4.0-42-generic                    | 20       | 1.32%   |
| 4.15.0-desktop-45.1rosa-i586        | 19       | 1.25%   |
| 4.9.124-nrj-desktop-1rosa-x86_64    | 18       | 1.18%   |
| 4.9.76-nrj-desktop-1rosa-x86_64     | 16       | 1.05%   |
| 5.3.0-40-generic                    | 14       | 0.92%   |
| 4.15.0-desktop-47.2rosa-x86_64      | 14       | 0.92%   |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 14       | 0.92%   |
| 4.1.38-nrj-desktop-2rosa-i586       | 14       | 0.92%   |
| 4.9.9-nrj-desktop-1rosa-i586        | 13       | 0.86%   |
| 4.9.41-nrj-desktop-1rosa-x86_64     | 13       | 0.86%   |
| 4.9.155-nrj-desktop-1rosa-x86_64    | 13       | 0.86%   |
| 4.15.0-desktop-94.1rosa-x86_64      | 13       | 0.86%   |
| 5.4.83-generic-2rosa-x86_64         | 11       | 0.72%   |
| 5.4.0-48-generic                    | 11       | 0.72%   |
| 4.15.0-desktop-68.5rosa-x86_64      | 11       | 0.72%   |
| 5.4.32-generic-2rosa-x86_64         | 10       | 0.66%   |
| 5.4.0-66-generic                    | 10       | 0.66%   |
| 5.4.0-58-generic                    | 10       | 0.66%   |
| 4.9.95-nrj-desktop-2rosa-x86_64     | 10       | 0.66%   |
| 5.8.0-50-generic                    | 9        | 0.59%   |
| 5.4.0-65-generic                    | 9        | 0.59%   |
| 5.4.0-54-generic                    | 9        | 0.59%   |
| 5.4.0-52-generic                    | 9        | 0.59%   |
| 5.10.0-8-amd64                      | 9        | 0.59%   |
| 5.4.0-89-generic                    | 8        | 0.53%   |
| 5.10.71-generic-1rosa2021.1-x86_64  | 8        | 0.53%   |
| 5.0.0-37-generic                    | 7        | 0.46%   |
| 5.4.0-91-generic                    | 6        | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 4.15.0   | 206      | 14.16%  |
| 5.4.0    | 164      | 11.27%  |
| 4.9.60   | 79       | 5.43%   |
| 4.9.20   | 76       | 5.22%   |
| 4.1.34   | 58       | 3.99%   |
| 5.8.0    | 51       | 3.51%   |
| 5.3.0    | 49       | 3.37%   |
| 4.1.38   | 47       | 3.23%   |
| 5.10.14  | 40       | 2.75%   |
| 5.0.0    | 39       | 2.68%   |
| 5.11.0   | 37       | 2.54%   |
| 4.9.9    | 35       | 2.41%   |
| 5.10.74  | 31       | 2.13%   |
| 5.16.7   | 26       | 1.79%   |
| 5.10.0   | 24       | 1.65%   |
| 4.9.124  | 23       | 1.58%   |
| 5.13.0   | 22       | 1.51%   |
| 4.9.76   | 21       | 1.44%   |
| 4.19.0   | 21       | 1.44%   |
| 4.18.0   | 19       | 1.31%   |
| 4.9.41   | 16       | 1.1%    |
| 5.4.32   | 14       | 0.96%   |
| 4.9.155  | 14       | 0.96%   |
| 4.9.95   | 13       | 0.89%   |
| 5.4.83   | 12       | 0.82%   |
| 5.15.0   | 9        | 0.62%   |
| 4.4.0    | 9        | 0.62%   |
| 5.6.14   | 8        | 0.55%   |
| 5.10.71  | 8        | 0.55%   |
| 4.9.111  | 7        | 0.48%   |
| 5.7.19   | 5        | 0.34%   |
| 5.11.6   | 5        | 0.34%   |
| 5.10.118 | 5        | 0.34%   |
| 5.9.16   | 4        | 0.27%   |
| 5.8.18   | 4        | 0.27%   |
| 5.15.8   | 4        | 0.27%   |
| 5.10.27  | 4        | 0.27%   |
| 4.9.87   | 4        | 0.27%   |
| 4.13.0   | 4        | 0.27%   |
| 4.10.0   | 4        | 0.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.9     | 270      | 19.24%  |
| 5.4     | 216      | 15.4%   |
| 4.15    | 206      | 14.68%  |
| 5.10    | 128      | 9.12%   |
| 4.1     | 103      | 7.34%   |
| 5.8     | 62       | 4.42%   |
| 5.3     | 56       | 3.99%   |
| 5.11    | 51       | 3.64%   |
| 5.0     | 41       | 2.92%   |
| 5.16    | 32       | 2.28%   |
| 5.13    | 30       | 2.14%   |
| 5.15    | 29       | 2.07%   |
| 4.19    | 27       | 1.92%   |
| 4.18    | 25       | 1.78%   |
| 5.6     | 19       | 1.35%   |
| 5.9     | 16       | 1.14%   |
| 5.12    | 14       | 1%      |
| 5.7     | 13       | 0.93%   |
| 4.4     | 10       | 0.71%   |
| 5.14    | 8        | 0.57%   |
| 5.5     | 6        | 0.43%   |
| 4.8     | 6        | 0.43%   |
| 5.17    | 4        | 0.29%   |
| 4.14    | 4        | 0.29%   |
| 4.13    | 4        | 0.29%   |
| 4.10    | 4        | 0.29%   |
| 4.16    | 3        | 0.21%   |
| 5.2     | 2        | 0.14%   |
| 5.19    | 2        | 0.14%   |
| 5.18    | 2        | 0.14%   |
| 4.12    | 2        | 0.14%   |
| 3.10    | 2        | 0.14%   |
| 5.1     | 1        | 0.07%   |
| 4.7     | 1        | 0.07%   |
| 4.20    | 1        | 0.07%   |
| 4.17    | 1        | 0.07%   |
| 3.16    | 1        | 0.07%   |
| 3.14    | 1        | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 1110     | 86.92%  |
| i686   | 167      | 13.08%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| KDE4            | 363      | 26.99%  |
| KDE5            | 314      | 23.35%  |
| GNOME           | 251      | 18.66%  |
| Unknown         | 120      | 8.92%   |
| XFCE            | 81       | 6.02%   |
| X-Cinnamon      | 46       | 3.42%   |
| Cinnamon        | 42       | 3.12%   |
| MATE            | 39       | 2.9%    |
| KDE             | 38       | 2.83%   |
| LXQt            | 13       | 0.97%   |
| Unity           | 6        | 0.45%   |
| i3              | 6        | 0.45%   |
| Deepin          | 6        | 0.45%   |
| Budgie          | 6        | 0.45%   |
| Pantheon        | 4        | 0.3%    |
| LXDE            | 4        | 0.3%    |
| GNOME Flashback | 3        | 0.22%   |
| GNOME Classic   | 2        | 0.15%   |
| Trinity         | 1        | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 1131     | 87.13%  |
| Wayland | 93       | 7.16%   |
| Unknown | 54       | 4.16%   |
| Tty     | 20       | 1.54%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 377      | 28.22%  |
| KDM     | 366      | 27.4%   |
| SDDM    | 304      | 22.75%  |
| GDM     | 116      | 8.68%   |
| TDM     | 90       | 6.74%   |
| LightDM | 50       | 3.74%   |
| GDM3    | 15       | 1.12%   |
| MDM     | 6        | 0.45%   |
| XDM     | 4        | 0.3%    |
| SLiM    | 4        | 0.3%    |
| Ly      | 2        | 0.15%   |
| NODM    | 1        | 0.07%   |
| LXDM    | 1        | 0.07%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang           | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 595      | 45.21%  |
| ru_RU          | 221      | 16.79%  |
| ru_UA          | 189      | 14.36%  |
| en_US          | 186      | 14.13%  |
| uk_UA          | 94       | 7.14%   |
| C              | 15       | 1.14%   |
| pl_PL          | 4        | 0.3%    |
| en_GB          | 4        | 0.3%    |
| es_ES          | 2        | 0.15%   |
| ru_RU.UTF_8    | 1        | 0.08%   |
| POSIX          | 1        | 0.08%   |
| hu_HU          | 1        | 0.08%   |
| en_US.US-ASCII | 1        | 0.08%   |
| en_CA          | 1        | 0.08%   |
| C.UTF8         | 1        | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 948      | 73.95%  |
| EFI  | 334      | 26.05%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 805      | 61.31%  |
| Unknown | 334      | 25.44%  |
| Overlay | 82       | 6.25%   |
| Btrfs   | 59       | 4.49%   |
| Xfs     | 10       | 0.76%   |
| Ext2    | 9        | 0.69%   |
| Zfs     | 7        | 0.53%   |
| Ext3    | 4        | 0.3%    |
| Tmpfs   | 1        | 0.08%   |
| SAMSUNG | 1        | 0.08%   |
| Aufs    | 1        | 0.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 523      | 39.44%  |
| MBR     | 505      | 38.08%  |
| GPT     | 298      | 22.47%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1059     | 81.84%  |
| Yes       | 235      | 18.16%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 847      | 64.56%  |
| Yes       | 465      | 35.44%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 487      | 38.62%  |
| Gigabyte Technology | 216      | 17.13%  |
| ASRock              | 170      | 13.48%  |
| MSI                 | 137      | 10.86%  |
| Biostar             | 49       | 3.89%   |
| Hewlett-Packard     | 30       | 2.38%   |
| Intel               | 26       | 2.06%   |
| Dell                | 26       | 2.06%   |
| ECS                 | 17       | 1.35%   |
| Unknown             | 17       | 1.35%   |
| Lenovo              | 16       | 1.27%   |
| Acer                | 12       | 0.95%   |
| Fujitsu             | 9        | 0.71%   |
| Foxconn             | 9        | 0.71%   |
| Huanan              | 7        | 0.56%   |
| Pegatron            | 4        | 0.32%   |
| WinFast             | 3        | 0.24%   |
| Nvidia              | 3        | 0.24%   |
| Fujitsu Siemens     | 3        | 0.24%   |
| ZOTAC               | 2        | 0.16%   |
| Supermicro          | 2        | 0.16%   |
| Colorful Technology | 2        | 0.16%   |
| VIA Technologies    | 1        | 0.08%   |
| TYAN Computer       | 1        | 0.08%   |
| Seco                | 1        | 0.08%   |
| Sapphire            | 1        | 0.08%   |
| Packard Bell        | 1        | 0.08%   |
| NF-M2SV             | 1        | 0.08%   |
| Medion              | 1        | 0.08%   |
| Koloe               | 1        | 0.08%   |
| Jingsha/Kllisre     | 1        | 0.08%   |
| IBM                 | 1        | 0.08%   |
| Hardkernel          | 1        | 0.08%   |
| Compaq              | 1        | 0.08%   |
| ABIT                | 1        | 0.08%   |
| 3Q                  | 1        | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                      | Desktops | Percent |
|---------------------------|----------|---------|
| ASUS All Series           | 25       | 1.98%   |
| Unknown                   | 17       | 1.35%   |
| ASUS M5A78L-M LX3         | 12       | 0.95%   |
| ASRock N68C-S UCC         | 12       | 0.95%   |
| ASUS M5A97 R2.0           | 9        | 0.71%   |
| Gigabyte G41M-Combo       | 7        | 0.56%   |
| ECS H61H2-M6              | 7        | 0.56%   |
| ASUS P5Q                  | 6        | 0.48%   |
| ASUS P5GC-MX/1333         | 6        | 0.48%   |
| MSI MS-7B86               | 5        | 0.4%    |
| MSI MS-7817               | 5        | 0.4%    |
| MSI MS-7788               | 5        | 0.4%    |
| Gigabyte B450M DS3H       | 5        | 0.4%    |
| Gigabyte 945GCMX-S2       | 5        | 0.4%    |
| ASUS PRIME B350-PLUS      | 5        | 0.4%    |
| ASUS P8H61-MX             | 5        | 0.4%    |
| ASUS M5A78L-M/USB3        | 5        | 0.4%    |
| ASUS Impression           | 5        | 0.4%    |
| ASUS H110M-R              | 5        | 0.4%    |
| ASRock FM2A68M-DG3+       | 5        | 0.4%    |
| MSI MS-7C52               | 4        | 0.32%   |
| MSI MS-7895               | 4        | 0.32%   |
| MSI MS-7721               | 4        | 0.32%   |
| MSI MS-7641               | 4        | 0.32%   |
| MSI MS-7592               | 4        | 0.32%   |
| Gigabyte H55M-S2V         | 4        | 0.32%   |
| Gigabyte F2A68HM-S1       | 4        | 0.32%   |
| Gigabyte B450M S2H        | 4        | 0.32%   |
| Gigabyte B450 AORUS ELITE | 4        | 0.32%   |
| Gigabyte 970A-DS3P        | 4        | 0.32%   |
| Gigabyte 945GCM-S2L       | 4        | 0.32%   |
| ASUS TUF B450-PRO GAMING  | 4        | 0.32%   |
| ASUS PRIME B450M-A        | 4        | 0.32%   |
| ASUS PRIME A320M-K        | 4        | 0.32%   |
| ASUS P8B75-V              | 4        | 0.32%   |
| ASUS P5Q SE               | 4        | 0.32%   |
| ASUS P5P43TD              | 4        | 0.32%   |
| ASUS P5K SE/EPU           | 4        | 0.32%   |
| ASUS M4A77TD              | 4        | 0.32%   |
| ASUS M2A-VM               | 4        | 0.32%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUS PRIME          | 48       | 3.81%   |
| ASUS All            | 25       | 1.98%   |
| ASUS M5A78L-M       | 24       | 1.9%    |
| Dell OptiPlex       | 20       | 1.59%   |
| ASUS M5A97          | 18       | 1.43%   |
| Unknown             | 17       | 1.35%   |
| ASUS TUF            | 16       | 1.27%   |
| HP Compaq           | 15       | 1.19%   |
| Gigabyte B450M      | 14       | 1.11%   |
| ASUS ROG            | 13       | 1.03%   |
| ASUS P8H61-M        | 13       | 1.03%   |
| ASUS P5Q            | 12       | 0.95%   |
| ASRock N68C-S       | 12       | 0.95%   |
| ASUS P8Z68-V        | 11       | 0.87%   |
| ASUS P5K            | 11       | 0.87%   |
| Lenovo ThinkCentre  | 9        | 0.71%   |
| ASUS P8Z77-V        | 8        | 0.63%   |
| ASUS P5G41T-M       | 8        | 0.63%   |
| Gigabyte G41M-Combo | 7        | 0.56%   |
| Gigabyte B450       | 7        | 0.56%   |
| ECS H61H2-M6        | 7        | 0.56%   |
| ASUS P5GC-MX        | 7        | 0.56%   |
| ASUS M2N-MX         | 7        | 0.56%   |
| Acer Aspire         | 7        | 0.56%   |
| Intel X79           | 6        | 0.48%   |
| Fujitsu ESPRIMO     | 6        | 0.48%   |
| ASUS P8H61-MX       | 6        | 0.48%   |
| ASUS P5KPL-AM       | 6        | 0.48%   |
| MSI MS-7B86         | 5        | 0.4%    |
| MSI MS-7817         | 5        | 0.4%    |
| MSI MS-7788         | 5        | 0.4%    |
| Gigabyte 970A-DS3P  | 5        | 0.4%    |
| Gigabyte 945GCMX-S2 | 5        | 0.4%    |
| ASUS P8B75-M        | 5        | 0.4%    |
| ASUS M5A78L         | 5        | 0.4%    |
| ASUS M4A77TD        | 5        | 0.4%    |
| ASUS Impression     | 5        | 0.4%    |
| ASUS H110M-R        | 5        | 0.4%    |
| ASUS F1A55-M        | 5        | 0.4%    |
| ASRock X570         | 5        | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2012    | 152      | 12.05%  |
| 2010    | 119      | 9.44%   |
| 2011    | 115      | 9.12%   |
| 2018    | 104      | 8.25%   |
| 2007    | 98       | 7.77%   |
| 2009    | 94       | 7.45%   |
| 2008    | 73       | 5.79%   |
| 2013    | 70       | 5.55%   |
| 2017    | 66       | 5.23%   |
| 2006    | 64       | 5.08%   |
| 2014    | 61       | 4.84%   |
| 2016    | 55       | 4.36%   |
| 2015    | 46       | 3.65%   |
| 2019    | 45       | 3.57%   |
| 2020    | 39       | 3.09%   |
| 2005    | 31       | 2.46%   |
| 2021    | 17       | 1.35%   |
| 2004    | 5        | 0.4%    |
| 2003    | 3        | 0.24%   |
| 2002    | 2        | 0.16%   |
| 2022    | 1        | 0.08%   |
| Unknown | 1        | 0.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 1261     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 1254     | 99.37%  |
| Enabled  | 8        | 0.63%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1261     | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 3.01-4.0        | 319      | 24.46%  |
| 8.01-16.0       | 283      | 21.7%   |
| 4.01-8.0        | 205      | 15.72%  |
| 16.01-24.0      | 199      | 15.26%  |
| 1.01-2.0        | 106      | 8.13%   |
| 32.01-64.0      | 72       | 5.52%   |
| 2.01-3.0        | 57       | 4.37%   |
| 0.51-1.0        | 29       | 2.22%   |
| 24.01-32.0      | 17       | 1.3%    |
| 64.01-256.0     | 15       | 1.15%   |
| More than 256.0 | 1        | 0.08%   |
| 0.01-0.5        | 1        | 0.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 535      | 37.57%  |
| 0.51-1.0   | 334      | 23.46%  |
| 2.01-3.0   | 230      | 16.15%  |
| 4.01-8.0   | 132      | 9.27%   |
| 3.01-4.0   | 108      | 7.58%   |
| 8.01-16.0  | 42       | 2.95%   |
| 0.01-0.5   | 36       | 2.53%   |
| 16.01-24.0 | 5        | 0.35%   |
| 24.01-32.0 | 2        | 0.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 626      | 47.35%  |
| 2      | 402      | 30.41%  |
| 3      | 179      | 13.54%  |
| 4      | 55       | 4.16%   |
| 5      | 30       | 2.27%   |
| 0      | 17       | 1.29%   |
| 6      | 8        | 0.61%   |
| 7      | 3        | 0.23%   |
| 8      | 2        | 0.15%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 737      | 57.35%  |
| Yes       | 548      | 42.65%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1237     | 98.1%   |
| No        | 24       | 1.9%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 967      | 75.61%  |
| Yes       | 312      | 24.39%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1102     | 85.83%  |
| Yes       | 182      | 14.17%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Ukraine | 1261     | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Desktops | Percent |
|-----------------|----------|---------|
| Kyiv            | 250      | 19.08%  |
| Kharkiv         | 98       | 7.48%   |
| Simferopol      | 58       | 4.43%   |
| Dnipro          | 54       | 4.12%   |
| Odessa          | 52       | 3.97%   |
| Sevastopol      | 51       | 3.89%   |
| Lviv            | 44       | 3.36%   |
| Donetsk         | 40       | 3.05%   |
| Mykolayiv       | 21       | 1.6%    |
| Zaporizhzhia    | 19       | 1.45%   |
| Mariupol        | 19       | 1.45%   |
| Kryvyi Rih      | 17       | 1.3%    |
| Zaporizhzhya    | 15       | 1.15%   |
| Novopskov       | 15       | 1.15%   |
| Kherson         | 14       | 1.07%   |
| Yasinovataya    | 13       | 0.99%   |
| Poltava         | 13       | 0.99%   |
| Luhansk         | 13       | 0.99%   |
| Horlivka        | 13       | 0.99%   |
| Lutsk           | 12       | 0.92%   |
| Uzhhorod        | 11       | 0.84%   |
| Bucha           | 11       | 0.84%   |
| Vinnytsia       | 10       | 0.76%   |
| Makiivka        | 10       | 0.76%   |
| Bila Tserkva    | 10       | 0.76%   |
| Kramatorsk      | 9        | 0.69%   |
| Chernihiv       | 9        | 0.69%   |
| Zhytomyr        | 8        | 0.61%   |
| Kremenchug      | 8        | 0.61%   |
| Chernivtsi      | 8        | 0.61%   |
| Cherkasy        | 8        | 0.61%   |
| Syeverodonets'k | 7        | 0.53%   |
| Samsonove       | 7        | 0.53%   |
| Nova Kakhovka   | 7        | 0.53%   |
| Kerch           | 7        | 0.53%   |
| Vasylkiv        | 6        | 0.46%   |
| Rivne           | 6        | 0.46%   |
| Khartsyzsk      | 6        | 0.46%   |
| Chystyakove     | 6        | 0.46%   |
| Brovary         | 6        | 0.46%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 471      | 737    | 22.84%  |
| Seagate             | 392      | 571    | 19.01%  |
| Samsung Electronics | 315      | 465    | 15.28%  |
| Kingston            | 168      | 226    | 8.15%   |
| Toshiba             | 140      | 179    | 6.79%   |
| Hitachi             | 126      | 158    | 6.11%   |
| Goodram             | 51       | 62     | 2.47%   |
| Patriot             | 39       | 44     | 1.89%   |
| HGST                | 28       | 47     | 1.36%   |
| Team                | 24       | 35     | 1.16%   |
| Apacer              | 24       | 25     | 1.16%   |
| A-DATA Technology   | 24       | 34     | 1.16%   |
| Crucial             | 23       | 27     | 1.12%   |
| SPCC                | 20       | 23     | 0.97%   |
| Maxtor              | 20       | 23     | 0.97%   |
| SanDisk             | 16       | 16     | 0.78%   |
| China               | 16       | 18     | 0.78%   |
| Transcend           | 14       | 23     | 0.68%   |
| Intel               | 13       | 15     | 0.63%   |
| Silicon Motion      | 12       | 16     | 0.58%   |
| AMD                 | 11       | 32     | 0.53%   |
| Leven               | 10       | 12     | 0.48%   |
| KingDian            | 10       | 14     | 0.48%   |
| Unknown             | 8        | 11     | 0.39%   |
| OCZ                 | 8        | 8      | 0.39%   |
| Plextor             | 6        | 6      | 0.29%   |
| KingSpec            | 5        | 5      | 0.24%   |
| Fujitsu             | 5        | 5      | 0.24%   |
| Smartbuy            | 4        | 5      | 0.19%   |
| Phison              | 4        | 5      | 0.19%   |
| JMicron Technology  | 4        | 8      | 0.19%   |
| XPG                 | 3        | 3      | 0.15%   |
| SK hynix            | 3        | 3      | 0.15%   |
| HUAWEI              | 3        | 3      | 0.15%   |
| Corsair             | 3        | 3      | 0.15%   |
| Verbatim            | 2        | 2      | 0.1%    |
| Micron Technology   | 2        | 3      | 0.1%    |
| LITEONIT            | 2        | 3      | 0.1%    |
| Indilinx            | 2        | 2      | 0.1%    |
| DeTech              | 2        | 2      | 0.1%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB           | 38       | 1.64%   |
| Seagate ST500DM002-1BD142 500GB  | 32       | 1.38%   |
| Toshiba DT01ACA050 500GB         | 31       | 1.34%   |
| Kingston SA400S37240G 240GB SSD  | 28       | 1.21%   |
| Kingston SA400S37120G 120GB SSD  | 28       | 1.21%   |
| Samsung SSD 860 EVO 250GB        | 25       | 1.08%   |
| Toshiba HDWD110 1TB              | 23       | 0.99%   |
| Seagate ST3500418AS 500GB        | 21       | 0.91%   |
| WDC WD10EZEX-08WN4A0 1TB         | 20       | 0.86%   |
| Kingston SV300S37A120G 120GB SSD | 17       | 0.73%   |
| Patriot Burst 240GB SSD          | 15       | 0.65%   |
| Seagate ST1000DM003-1CH162 1TB   | 14       | 0.6%    |
| Samsung HD103SJ 1TB              | 14       | 0.6%    |
| Seagate ST31000524AS 1TB         | 13       | 0.56%   |
| Seagate ST1000DM010-2EP102 1TB   | 12       | 0.52%   |
| Samsung SSD 860 EVO 500GB        | 12       | 0.52%   |
| WDC WD5000AAKX-001CA0 500GB      | 11       | 0.47%   |
| WDC WD5000AADS-00S9B0 500GB      | 11       | 0.47%   |
| Toshiba DT01ACA200 2TB           | 11       | 0.47%   |
| Seagate ST3320620AS 320GB        | 11       | 0.47%   |
| Seagate ST2000DM008-2FR102 2TB   | 11       | 0.47%   |
| Kingston SA400S37480G 480GB SSD  | 11       | 0.47%   |
| WDC WD10EZEX-22MFCA0 1TB         | 10       | 0.43%   |
| Seagate ST3250410AS 250GB        | 10       | 0.43%   |
| Seagate ST31000528AS 1TB         | 10       | 0.43%   |
| Samsung SSD 850 EVO 250GB        | 10       | 0.43%   |
| Samsung HD321KJ 320GB            | 10       | 0.43%   |
| Samsung HD161HJ 160GB            | 10       | 0.43%   |
| Patriot Burst 120GB SSD          | 10       | 0.43%   |
| Hitachi HDS721010CLA332 1TB      | 10       | 0.43%   |
| WDC WD5000AAKX-00ERMA0 500GB     | 9        | 0.39%   |
| WDC WD10EZEX-00WN4A0 1TB         | 9        | 0.39%   |
| Seagate ST3250318AS 250GB        | 9        | 0.39%   |
| Samsung HD502HJ 500GB            | 9        | 0.39%   |
| Samsung HD160JJ 160GB            | 9        | 0.39%   |
| Samsung HD080HJ 80GB             | 9        | 0.39%   |
| Hitachi HDS721616PLA380 160GB    | 9        | 0.39%   |
| Hitachi HDS721050CLA362 500GB    | 9        | 0.39%   |
| WDC WD10EZRZ-00HTKB0 1TB         | 8        | 0.35%   |
| Seagate ST9500325AS 500GB        | 8        | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 461      | 718    | 33.31%  |
| Seagate             | 390      | 569    | 28.18%  |
| Samsung Electronics | 205      | 298    | 14.81%  |
| Toshiba             | 139      | 175    | 10.04%  |
| Hitachi             | 126      | 158    | 9.1%    |
| HGST                | 28       | 47     | 2.02%   |
| Maxtor              | 20       | 23     | 1.45%   |
| Fujitsu             | 5        | 5      | 0.36%   |
| Unknown             | 3        | 4      | 0.22%   |
| TPH00100500GB       | 1        | 1      | 0.07%   |
| JMicron Technology  | 1        | 3      | 0.07%   |
| Ext Hard            | 1        | 1      | 0.07%   |
| Config              | 1        | 1      | 0.07%   |
| China               | 1        | 1      | 0.07%   |
| ASMT                | 1        | 4      | 0.07%   |
| Apple               | 1        | 1      | 0.07%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 156      | 205    | 27.04%  |
| Samsung Electronics | 84       | 120    | 14.56%  |
| Goodram             | 48       | 58     | 8.32%   |
| Patriot             | 38       | 43     | 6.59%   |
| Team                | 23       | 31     | 3.99%   |
| Crucial             | 23       | 27     | 3.99%   |
| Apacer              | 22       | 23     | 3.81%   |
| A-DATA Technology   | 19       | 29     | 3.29%   |
| SPCC                | 17       | 19     | 2.95%   |
| China               | 15       | 17     | 2.6%    |
| SanDisk             | 13       | 13     | 2.25%   |
| WDC                 | 12       | 13     | 2.08%   |
| Transcend           | 11       | 17     | 1.91%   |
| Intel               | 11       | 13     | 1.91%   |
| KingDian            | 10       | 14     | 1.73%   |
| AMD                 | 10       | 31     | 1.73%   |
| Leven               | 9        | 11     | 1.56%   |
| OCZ                 | 8        | 8      | 1.39%   |
| Plextor             | 5        | 5      | 0.87%   |
| KingSpec            | 5        | 5      | 0.87%   |
| Toshiba             | 4        | 4      | 0.69%   |
| Smartbuy            | 4        | 5      | 0.69%   |
| Corsair             | 3        | 3      | 0.52%   |
| Verbatim            | 2        | 2      | 0.35%   |
| LITEONIT            | 2        | 3      | 0.35%   |
| CHN25SATAS1         | 2        | 6      | 0.35%   |
| ASMedia             | 2        | 2      | 0.35%   |
| Zheino              | 1        | 1      | 0.17%   |
| WALRAM              | 1        | 1      | 0.17%   |
| Super Talent        | 1        | 1      | 0.17%   |
| SP                  | 1        | 1      | 0.17%   |
| Reeinno             | 1        | 1      | 0.17%   |
| PNY                 | 1        | 1      | 0.17%   |
| Pioneer             | 1        | 1      | 0.17%   |
| Palit               | 1        | 2      | 0.17%   |
| Micron Technology   | 1        | 1      | 0.17%   |
| KIOXIA-EXCERIA      | 1        | 2      | 0.17%   |
| JIAWEI              | 1        | 1      | 0.17%   |
| Intenso             | 1        | 2      | 0.17%   |
| i-FlashDisk         | 1        | 1      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1062     | 2009   | 63.14%  |
| SSD     | 507      | 749    | 30.14%  |
| NVMe    | 99       | 145    | 5.89%   |
| Unknown | 12       | 15     | 0.71%   |
| MMC     | 2        | 2      | 0.12%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 1225     | 2743   | 90.88%  |
| NVMe | 98       | 143    | 7.27%   |
| SAS  | 23       | 32     | 1.71%   |
| MMC  | 2        | 2      | 0.15%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 1046     | 1888   | 64.49%  |
| 0.51-1.0   | 408      | 613    | 25.15%  |
| 1.01-2.0   | 106      | 156    | 6.54%   |
| 2.01-3.0   | 29       | 49     | 1.79%   |
| 3.01-4.0   | 20       | 36     | 1.23%   |
| 4.01-10.0  | 12       | 15     | 0.74%   |
| 10.01-20.0 | 1        | 1      | 0.06%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 334      | 24.19%  |
| 251-500        | 220      | 15.93%  |
| 501-1000       | 161      | 11.66%  |
| 1-20           | 157      | 11.37%  |
| 51-100         | 153      | 11.08%  |
| 1001-2000      | 126      | 9.12%   |
| 21-50          | 116      | 8.4%    |
| More than 3000 | 45       | 3.26%   |
| 2001-3000      | 42       | 3.04%   |
| Unknown        | 27       | 1.96%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 635      | 45.65%  |
| 21-50          | 173      | 12.44%  |
| 101-250        | 173      | 12.44%  |
| 51-100         | 115      | 8.27%   |
| 251-500        | 95       | 6.83%   |
| 501-1000       | 89       | 6.4%    |
| 1001-2000      | 50       | 3.59%   |
| Unknown        | 27       | 1.94%   |
| More than 3000 | 19       | 1.37%   |
| 2001-3000      | 15       | 1.08%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 11       | 13     | 2.21%   |
| Seagate ST3500418AS 500GB         | 9        | 10     | 1.81%   |
| Samsung Electronics HD321KJ 320GB | 8        | 11     | 1.61%   |
| WDC WD5000AADS-00S9B0 500GB       | 7        | 7      | 1.41%   |
| Seagate ST31000524AS 1TB          | 7        | 9      | 1.41%   |
| Seagate ST3250318AS 250GB         | 6        | 8      | 1.21%   |
| Samsung Electronics HD080HJ 80GB  | 6        | 6      | 1.21%   |
| WDC WD5000AAKX-001CA0 500GB       | 5        | 5      | 1.01%   |
| WDC WD10EZEX-60ZF5A0 1TB          | 5        | 6      | 1.01%   |
| Toshiba DT01ACA050 500GB          | 5        | 6      | 1.01%   |
| Seagate ST9500325AS 500GB         | 5        | 5      | 1.01%   |
| Seagate ST3320620AS 320GB         | 5        | 7      | 1.01%   |
| Seagate ST3160811AS 160GB         | 5        | 5      | 1.01%   |
| Samsung Electronics SP2514N 250GB | 5        | 6      | 1.01%   |
| Samsung Electronics SP2504C 250GB | 5        | 6      | 1.01%   |
| Samsung Electronics HD403LJ 400GB | 5        | 6      | 1.01%   |
| Samsung Electronics HD103SJ 1TB   | 5        | 7      | 1.01%   |
| Maxtor STM3250820AS 250GB         | 5        | 6      | 1.01%   |
| Toshiba DT01ACA100 1TB            | 4        | 6      | 0.8%    |
| Seagate ST3250410AS 250GB         | 4        | 7      | 0.8%    |
| Seagate ST3250310AS 250GB         | 4        | 5      | 0.8%    |
| Seagate ST1000DM003-1CH162 1TB    | 4        | 6      | 0.8%    |
| Samsung Electronics SP2004C 200GB | 4        | 4      | 0.8%    |
| Samsung Electronics SP0802N 80GB  | 4        | 4      | 0.8%    |
| Samsung Electronics HD322HJ 320GB | 4        | 4      | 0.8%    |
| Samsung Electronics HD200HJ 200GB | 4        | 5      | 0.8%    |
| Samsung Electronics HD160JJ 160GB | 4        | 6      | 0.8%    |
| Hitachi HDT725025VLA380 250GB     | 4        | 4      | 0.8%    |
| Hitachi HDS721616PLA380 160GB     | 4        | 4      | 0.8%    |
| Hitachi HDS721010DLE630 1TB       | 4        | 5      | 0.8%    |
| Hitachi HDP725025GLA380 250GB     | 4        | 5      | 0.8%    |
| WDC WD5000AAKX-00ERMA0 500GB      | 3        | 4      | 0.6%    |
| WDC WD5000AAKS-00V1A0 500GB       | 3        | 4      | 0.6%    |
| WDC WD5000AAKS-00UU3A0 500GB      | 3        | 3      | 0.6%    |
| WDC WD3200AAJS-00L7A0 320GB       | 3        | 3      | 0.6%    |
| Seagate ST380815AS 80GB           | 3        | 4      | 0.6%    |
| Seagate ST3500320AS 500GB         | 3        | 4      | 0.6%    |
| Seagate ST3320613AS 320GB         | 3        | 6      | 0.6%    |
| Samsung Electronics SP0842N 80GB  | 3        | 6      | 0.6%    |
| Samsung Electronics HD161HJ 160GB | 3        | 3      | 0.6%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 130      | 165    | 26.97%  |
| WDC                 | 122      | 148    | 25.31%  |
| Samsung Electronics | 103      | 124    | 21.37%  |
| Hitachi             | 55       | 70     | 11.41%  |
| Toshiba             | 22       | 26     | 4.56%   |
| Kingston            | 12       | 16     | 2.49%   |
| Maxtor              | 11       | 13     | 2.28%   |
| Intel               | 4        | 4      | 0.83%   |
| Patriot             | 3        | 3      | 0.62%   |
| A-DATA Technology   | 3        | 4      | 0.62%   |
| SPCC                | 2        | 3      | 0.41%   |
| SanDisk             | 2        | 2      | 0.41%   |
| Fujitsu             | 2        | 2      | 0.41%   |
| Transcend           | 1        | 1      | 0.21%   |
| TPH00100500GB       | 1        | 1      | 0.21%   |
| OCZ                 | 1        | 1      | 0.21%   |
| Micron Technology   | 1        | 1      | 0.21%   |
| JMicron Technology  | 1        | 1      | 0.21%   |
| JIAWEI              | 1        | 1      | 0.21%   |
| HGST                | 1        | 2      | 0.21%   |
| Goodram             | 1        | 1      | 0.21%   |
| Crucial             | 1        | 1      | 0.21%   |
| Corsair             | 1        | 1      | 0.21%   |
| Apple               | 1        | 1      | 0.21%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 130      | 165    | 29.21%  |
| WDC                 | 122      | 148    | 27.42%  |
| Samsung Electronics | 100      | 121    | 22.47%  |
| Hitachi             | 55       | 70     | 12.36%  |
| Toshiba             | 22       | 26     | 4.94%   |
| Maxtor              | 11       | 13     | 2.47%   |
| Fujitsu             | 2        | 2      | 0.45%   |
| TPH00100500GB       | 1        | 1      | 0.22%   |
| HGST                | 1        | 2      | 0.22%   |
| Apple               | 1        | 1      | 0.22%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 374      | 549    | 91%     |
| SSD  | 35       | 41     | 8.52%   |
| NVMe | 2        | 2      | 0.49%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD5000AAKS-00V1A0 500GB       | 1        | 2      | 5%      |
| WDC WD3200AAJS-60Z0A0 320GB       | 1        | 1      | 5%      |
| WDC WD2500JS-22NCB1 250GB         | 1        | 1      | 5%      |
| WDC WD1600AAJB-00WRA0 160GB       | 1        | 1      | 5%      |
| WDC WD1001FALS-00E8B0 1TB         | 1        | 1      | 5%      |
| Toshiba MK5065GSX 500GB           | 1        | 1      | 5%      |
| Seagate ST9250315AS 250GB         | 1        | 1      | 5%      |
| Seagate ST3750525AS 752GB         | 1        | 1      | 5%      |
| Seagate ST3500418AS 500GB         | 1        | 1      | 5%      |
| Seagate ST3500410AS 500GB         | 1        | 1      | 5%      |
| Seagate ST320DM001 HD322GJ 320GB  | 1        | 1      | 5%      |
| Seagate ST31000528AS 1TB          | 1        | 1      | 5%      |
| Seagate ST31000524AS 1TB          | 1        | 1      | 5%      |
| Seagate ST31000340NS 1TB          | 1        | 1      | 5%      |
| Samsung Electronics HM321HI 320GB | 1        | 1      | 5%      |
| Samsung Electronics HM251JI 250GB | 1        | 1      | 5%      |
| Samsung Electronics HD502HJ 500GB | 1        | 1      | 5%      |
| Samsung Electronics HD252HJ 250GB | 1        | 4      | 5%      |
| Hitachi HTS547575A9E384 752GB     | 1        | 1      | 5%      |
| Hitachi HDS721010DLE630 1TB       | 1        | 1      | 5%      |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 8        | 8      | 40%     |
| WDC                 | 5        | 6      | 25%     |
| Samsung Electronics | 4        | 7      | 20%     |
| Hitachi             | 2        | 2      | 10%     |
| Toshiba             | 1        | 1      | 5%      |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 662      | 1403   | 44.25%  |
| Detected | 415      | 901    | 27.74%  |
| Malfunc  | 399      | 592    | 26.67%  |
| Failed   | 20       | 24     | 1.34%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 736      | 47.58%  |
| AMD                              | 388      | 25.08%  |
| Nvidia                           | 120      | 7.76%   |
| JMicron Technology               | 74       | 4.78%   |
| Marvell Technology Group         | 53       | 3.43%   |
| ASMedia Technology               | 41       | 2.65%   |
| Samsung Electronics              | 36       | 2.33%   |
| Silicon Motion                   | 18       | 1.16%   |
| VIA Technologies                 | 15       | 0.97%   |
| Kingston Technology Company      | 13       | 0.84%   |
| Phison Electronics               | 9        | 0.58%   |
| ADATA Technology                 | 8        | 0.52%   |
| SanDisk                          | 7        | 0.45%   |
| Silicon Image                    | 5        | 0.32%   |
| ULi Electronics                  | 3        | 0.19%   |
| SK hynix                         | 3        | 0.19%   |
| Silicon Integrated Systems [SiS] | 3        | 0.19%   |
| Shenzhen Longsys Electronics     | 3        | 0.19%   |
| Integrated Technology Express    | 3        | 0.19%   |
| Realtek Semiconductor            | 2        | 0.13%   |
| Broadcom / LSI                   | 2        | 0.13%   |
| Seagate Technology               | 1        | 0.06%   |
| Micron/Crucial Technology        | 1        | 0.06%   |
| Micron Technology                | 1        | 0.06%   |
| MAXIO Technology (Hangzhou)      | 1        | 0.06%   |
| Lite-On Technology               | 1        | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 166      | 7.43%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 129      | 5.77%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 124      | 5.55%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 105      | 4.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 87       | 3.89%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 76       | 3.4%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 75       | 3.36%   |
| Nvidia MCP61 SATA Controller                                                            | 73       | 3.27%   |
| Nvidia MCP61 IDE                                                                        | 68       | 3.04%   |
| AMD 400 Series Chipset SATA Controller                                                  | 56       | 2.51%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 55       | 2.46%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 49       | 2.19%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 49       | 2.19%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 49       | 2.19%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 42       | 1.88%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 41       | 1.84%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 40       | 1.79%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 31       | 1.39%   |
| JMicron JMB368 IDE controller                                                           | 29       | 1.3%    |
| AMD FCH IDE Controller                                                                  | 28       | 1.25%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 27       | 1.21%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 27       | 1.21%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 26       | 1.16%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 25       | 1.12%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 24       | 1.07%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 20       | 0.9%    |
| AMD FCH SATA Controller D                                                               | 20       | 0.9%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 19       | 0.85%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 19       | 0.85%   |
| AMD 300 Series Chipset SATA Controller                                                  | 19       | 0.85%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 18       | 0.81%   |
| Intel SATA Controller [RAID mode]                                                       | 16       | 0.72%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 16       | 0.72%   |
| JMicron JMB362 SATA Controller                                                          | 15       | 0.67%   |
| AMD SB600 IDE                                                                           | 15       | 0.67%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                               | 14       | 0.63%   |
| Intel 82801EB/ER (ICH5/ICH5R) IDE Controller                                            | 14       | 0.63%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 13       | 0.58%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 13       | 0.58%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 13       | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 815      | 50.72%  |
| IDE  | 649      | 40.39%  |
| NVMe | 98       | 6.1%    |
| RAID | 40       | 2.49%   |
| SAS  | 4        | 0.25%   |
| SCSI | 1        | 0.06%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 754      | 59.79%  |
| AMD    | 507      | 40.21%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Athlon II X2 250 Processor              | 26       | 2.04%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 17       | 1.33%   |
| AMD FX-8350 Eight-Core Processor            | 15       | 1.18%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 14       | 1.1%    |
| Intel Core i3-3220 CPU @ 3.30GHz            | 14       | 1.1%    |
| Intel Core i3-2100 CPU @ 3.10GHz            | 13       | 1.02%   |
| Intel Core i3 CPU 540 @ 3.07GHz             | 12       | 0.94%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 12       | 0.94%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 11       | 0.86%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 11       | 0.86%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 11       | 0.86%   |
| AMD Athlon 64 X2 Dual Core Processor 4200+  | 11       | 0.86%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 10       | 0.78%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 10       | 0.78%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 10       | 0.78%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 9        | 0.71%   |
| Intel Pentium 4 CPU 3.00GHz                 | 9        | 0.71%   |
| AMD Ryzen 5 3600 6-Core Processor           | 9        | 0.71%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 9        | 0.71%   |
| AMD Ryzen 3 1200 Quad-Core Processor        | 9        | 0.71%   |
| AMD Phenom II X4 965 Processor              | 9        | 0.71%   |
| AMD Athlon II X2 240 Processor              | 9        | 0.71%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 8        | 0.63%   |
| Intel Pentium CPU G3260 @ 3.30GHz           | 8        | 0.63%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 8        | 0.63%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 8        | 0.63%   |
| AMD FX-8300 Eight-Core Processor            | 8        | 0.63%   |
| AMD FX-6300 Six-Core Processor              | 8        | 0.63%   |
| Intel Pentium Dual-Core CPU E6300 @ 2.80GHz | 7        | 0.55%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 7        | 0.55%   |
| Intel Pentium D CPU 3.00GHz                 | 7        | 0.55%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 7        | 0.55%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 7        | 0.55%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 7        | 0.55%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 7        | 0.55%   |
| Intel Core 2 Duo CPU E6750 @ 2.66GHz        | 7        | 0.55%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 7        | 0.55%   |
| AMD Phenom II X4 955 Processor              | 7        | 0.55%   |
| AMD Athlon II X4 640 Processor              | 7        | 0.55%   |
| AMD Athlon II X2 220 Processor              | 7        | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 148      | 11.64%  |
| Intel Core i3           | 118      | 9.28%   |
| Intel Celeron           | 81       | 6.37%   |
| Intel Core 2 Duo        | 78       | 6.14%   |
| Intel Xeon              | 65       | 5.11%   |
| AMD FX                  | 65       | 5.11%   |
| AMD Athlon II X2        | 64       | 5.04%   |
| Intel Pentium           | 57       | 4.48%   |
| AMD Athlon 64 X2        | 52       | 4.09%   |
| Intel Core i7           | 49       | 3.86%   |
| AMD Ryzen 5             | 49       | 3.86%   |
| AMD Phenom II X4        | 35       | 2.75%   |
| Intel Core 2 Quad       | 31       | 2.44%   |
| Intel Pentium 4         | 29       | 2.28%   |
| Intel Pentium Dual-Core | 27       | 2.12%   |
| AMD Ryzen 7             | 26       | 2.05%   |
| AMD Athlon II X4        | 23       | 1.81%   |
| AMD Ryzen 3             | 22       | 1.73%   |
| AMD A4                  | 22       | 1.73%   |
| Intel Core 2            | 18       | 1.42%   |
| AMD Athlon II X3        | 17       | 1.34%   |
| AMD Athlon              | 17       | 1.34%   |
| Intel Pentium D         | 16       | 1.26%   |
| AMD A8                  | 16       | 1.26%   |
| Intel Pentium Dual      | 15       | 1.18%   |
| AMD Sempron             | 14       | 1.1%    |
| AMD Athlon X4           | 13       | 1.02%   |
| Other                   | 12       | 0.94%   |
| AMD Athlon 64           | 11       | 0.87%   |
| AMD Ryzen 9             | 10       | 0.79%   |
| AMD A6                  | 10       | 0.79%   |
| AMD A10                 | 9        | 0.71%   |
| Intel Atom              | 8        | 0.63%   |
| Intel Genuine           | 6        | 0.47%   |
| AMD Ryzen Threadripper  | 5        | 0.39%   |
| Intel Pentium Gold      | 4        | 0.31%   |
| AMD Phenom II X6        | 4        | 0.31%   |
| AMD Athlon X2           | 3        | 0.24%   |
| AMD Turion 64 X2 Mobile | 2        | 0.16%   |
| AMD Ryzen 5 PRO         | 2        | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 528      | 40.93%  |
| 4       | 392      | 30.39%  |
| 6       | 101      | 7.83%   |
| 1       | 87       | 6.74%   |
| Unknown | 77       | 5.97%   |
| 8       | 45       | 3.49%   |
| 3       | 33       | 2.56%   |
| 12      | 13       | 1.01%   |
| 16      | 7        | 0.54%   |
| 10      | 3        | 0.23%   |
| 36      | 1        | 0.08%   |
| 32      | 1        | 0.08%   |
| 24      | 1        | 0.08%   |
| 14      | 1        | 0.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 1254     | 99.44%  |
| 2       | 6        | 0.48%   |
| Unknown | 1        | 0.08%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 758      | 58.76%  |
| 2       | 455      | 35.27%  |
| Unknown | 77       | 5.97%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 1233     | 97.47%  |
| 32-bit         | 19       | 1.5%    |
| Unknown        | 13       | 1.03%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 189      | 14.56%  |
| 0x1067a    | 95       | 7.32%   |
| 0x010000c8 | 95       | 7.32%   |
| 0x206a7    | 86       | 6.63%   |
| 0x306a9    | 67       | 5.16%   |
| 0x306c3    | 63       | 4.85%   |
| 0x506e3    | 38       | 2.93%   |
| 0x06001119 | 34       | 2.62%   |
| 0x906e9    | 29       | 2.23%   |
| 0x10676    | 29       | 2.23%   |
| 0x06000852 | 29       | 2.23%   |
| 0x906ea    | 23       | 1.77%   |
| 0x6fb      | 21       | 1.62%   |
| 0x6fd      | 20       | 1.54%   |
| 0x03000027 | 18       | 1.39%   |
| 0x010000c7 | 18       | 1.39%   |
| 0x906eb    | 17       | 1.31%   |
| 0x0800820d | 15       | 1.16%   |
| 0x08001137 | 15       | 1.16%   |
| 0x06003106 | 15       | 1.16%   |
| 0xf41      | 13       | 1%      |
| 0x20655    | 13       | 1%      |
| 0x08701013 | 13       | 1%      |
| 0x010000db | 13       | 1%      |
| 0x08108109 | 12       | 0.92%   |
| 0x08101016 | 12       | 0.92%   |
| 0x08001138 | 12       | 0.92%   |
| 0x0600084f | 12       | 0.92%   |
| 0x6f6      | 11       | 0.85%   |
| 0x6f2      | 11       | 0.85%   |
| 0x206d7    | 10       | 0.77%   |
| 0x08701021 | 10       | 0.77%   |
| 0x20652    | 9        | 0.69%   |
| 0x106e5    | 9        | 0.69%   |
| 0x0600063e | 9        | 0.69%   |
| 0xf65      | 8        | 0.62%   |
| 0xf49      | 8        | 0.62%   |
| 0x306e4    | 8        | 0.62%   |
| 0x0600063d | 8        | 0.62%   |
| 0xa0671    | 7        | 0.54%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| K10              | 152      | 11.96%  |
| Penryn           | 136      | 10.7%   |
| SandyBridge      | 109      | 8.58%   |
| Piledriver       | 85       | 6.69%   |
| KabyLake         | 84       | 6.61%   |
| IvyBridge        | 84       | 6.61%   |
| K8 Hammer        | 80       | 6.29%   |
| Haswell          | 77       | 6.06%   |
| Core             | 77       | 6.06%   |
| Zen              | 55       | 4.33%   |
| NetBurst         | 55       | 4.33%   |
| Skylake          | 41       | 3.23%   |
| Zen+             | 35       | 2.75%   |
| Zen 2            | 30       | 2.36%   |
| Westmere         | 28       | 2.2%    |
| K10 Llano        | 18       | 1.42%   |
| Steamroller      | 16       | 1.26%   |
| Bulldozer        | 15       | 1.18%   |
| Unknown          | 15       | 1.18%   |
| CometLake        | 14       | 1.1%    |
| Nehalem          | 13       | 1.02%   |
| Silvermont       | 9        | 0.71%   |
| Zen 3            | 8        | 0.63%   |
| Goldmont         | 7        | 0.55%   |
| Bonnell          | 7        | 0.55%   |
| Excavator        | 6        | 0.47%   |
| Goldmont plus    | 4        | 0.31%   |
| Broadwell        | 3        | 0.24%   |
| Puma             | 2        | 0.16%   |
| Jaguar           | 2        | 0.16%   |
| K6               | 1        | 0.08%   |
| Icelake          | 1        | 0.08%   |
| Bobcat           | 1        | 0.08%   |
| Alderlake Hybrid | 1        | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Nvidia                                       | 589      | 44.15%  |
| AMD                                          | 424      | 31.78%  |
| Intel                                        | 317      | 23.76%  |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 0.07%   |
| VIA Technologies                             | 1        | 0.07%   |
| Silicon Integrated Systems [SiS]             | 1        | 0.07%   |
| Matrox Electronics Systems                   | 1        | 0.07%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 50       | 3.6%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 45       | 3.24%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 32       | 2.31%   |
| Nvidia GK208B [GeForce GT 710]                                              | 27       | 1.95%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 27       | 1.95%   |
| Nvidia GT218 [GeForce 210]                                                  | 26       | 1.87%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 24       | 1.73%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 24       | 1.73%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 21       | 1.51%   |
| Nvidia GF108 [GeForce GT 440]                                               | 21       | 1.51%   |
| Nvidia G94 [GeForce 9600 GT]                                                | 20       | 1.44%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 19       | 1.37%   |
| Intel HD Graphics 530                                                       | 17       | 1.22%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 17       | 1.22%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 16       | 1.15%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 16       | 1.15%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 16       | 1.15%   |
| Nvidia GF108 [GeForce GT 630]                                               | 16       | 1.15%   |
| Nvidia G84 [GeForce 8600 GT]                                                | 14       | 1.01%   |
| AMD RS780L [Radeon 3000]                                                    | 14       | 1.01%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 14       | 1.01%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 13       | 0.94%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 13       | 0.94%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 13       | 0.94%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 13       | 0.94%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 13       | 0.94%   |
| Nvidia GT215 [GeForce GT 240]                                               | 12       | 0.86%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 12       | 0.86%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 12       | 0.86%   |
| Nvidia GK208B [GeForce GT 730]                                              | 12       | 0.86%   |
| Nvidia GF108 [GeForce GT 430]                                               | 12       | 0.86%   |
| Intel Core Processor Integrated Graphics Controller                         | 12       | 0.86%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 12       | 0.86%   |
| AMD Redwood XT [Radeon HD 5670/5690/5730]                                   | 12       | 0.86%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 12       | 0.86%   |
| Nvidia GF119 [GeForce GT 610]                                               | 11       | 0.79%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 11       | 0.79%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 11       | 0.79%   |
| Nvidia GF106 [GeForce GTS 450]                                              | 10       | 0.72%   |
| Nvidia G92 [GeForce 9800 GT]                                                | 10       | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| 1 x Nvidia             | 573      | 44.49%  |
| 1 x AMD                | 379      | 29.43%  |
| 1 x Intel              | 273      | 21.2%   |
| 2 x AMD                | 33       | 2.56%   |
| Intel + AMD            | 8        | 0.62%   |
| Intel + Nvidia         | 7        | 0.54%   |
| AMD + Nvidia           | 4        | 0.31%   |
| 2 x Nvidia             | 2        | 0.16%   |
| Intel + 2 x Nvidia     | 2        | 0.16%   |
| 3 x Nvidia             | 1        | 0.08%   |
| 1 x XGI                | 1        | 0.08%   |
| 1 x VIA                | 1        | 0.08%   |
| 1 x SiS                | 1        | 0.08%   |
| 1 x Matrox             | 1        | 0.08%   |
| 1 x Intel + 7 x Nvidia | 1        | 0.08%   |
| Intel + 2 x AMD        | 1        | 0.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 943      | 72.26%  |
| Proprietary | 302      | 23.14%  |
| Unknown     | 60       | 4.6%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 314      | 23.91%  |
| 0.01-0.5   | 301      | 22.92%  |
| 0.51-1.0   | 268      | 20.41%  |
| 1.01-2.0   | 218      | 16.6%   |
| 3.01-4.0   | 111      | 8.45%   |
| 7.01-8.0   | 47       | 3.58%   |
| 5.01-6.0   | 24       | 1.83%   |
| 2.01-3.0   | 21       | 1.6%    |
| 8.01-16.0  | 9        | 0.69%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 336      | 26.33%  |
| Goldstar                | 275      | 21.55%  |
| Philips                 | 129      | 10.11%  |
| Dell                    | 92       | 7.21%   |
| Acer                    | 74       | 5.8%    |
| Ancor Communications    | 61       | 4.78%   |
| BenQ                    | 49       | 3.84%   |
| AOC                     | 39       | 3.06%   |
| ViewSonic               | 25       | 1.96%   |
| Hewlett-Packard         | 25       | 1.96%   |
| Iiyama                  | 21       | 1.65%   |
| LG Electronics          | 20       | 1.57%   |
| NEC Computers           | 15       | 1.18%   |
| Sony                    | 11       | 0.86%   |
| Unknown                 | 9        | 0.71%   |
| ASUSTek Computer        | 9        | 0.71%   |
| Belinea                 | 6        | 0.47%   |
| ___                     | 4        | 0.31%   |
| Plain Tree Systems      | 4        | 0.31%   |
| Lenovo                  | 3        | 0.24%   |
| HannStar                | 3        | 0.24%   |
| XYK                     | 2        | 0.16%   |
| Xiaomi                  | 2        | 0.16%   |
| TCL                     | 2        | 0.16%   |
| SAC                     | 2        | 0.16%   |
| PNP                     | 2        | 0.16%   |
| NEW                     | 2        | 0.16%   |
| HannStar Display        | 2        | 0.16%   |
| Gigabyte Technology     | 2        | 0.16%   |
| Eizo                    | 2        | 0.16%   |
| Compaq Computer         | 2        | 0.16%   |
| Chi Mei Optoelectronics | 2        | 0.16%   |
| BBK                     | 2        | 0.16%   |
| Xerox                   | 1        | 0.08%   |
| VMO                     | 1        | 0.08%   |
| Unknown (ADA)           | 1        | 0.08%   |
| Toshiba                 | 1        | 0.08%   |
| SVT                     | 1        | 0.08%   |
| Sun                     | 1        | 0.08%   |
| SK hynix                | 1        | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch            | 19       | 1.42%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch | 13       | 0.97%   |
| Goldstar W2243 GSM56FE 1920x1080 477x268mm 21.5-inch                 | 11       | 0.82%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch            | 10       | 0.75%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch | 9        | 0.67%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 340x270mm 17.1-inch | 9        | 0.67%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch              | 7        | 0.52%   |
| Philips 196VL PHLC07F 1366x768 409x230mm 18.5-inch                   | 7        | 0.52%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 7        | 0.52%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 7        | 0.52%   |
| Samsung Electronics SyncMaster SAM0593 1920x1080 477x268mm 21.5-inch | 6        | 0.45%   |
| Samsung Electronics SyncMaster SAM0108 1280x1024 312x234mm 15.4-inch | 6        | 0.45%   |
| Samsung Electronics S22B300 SAM08AA 1920x1080 477x268mm 21.5-inch    | 6        | 0.45%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                  | 6        | 0.45%   |
| Philips 220WS PHL0851 1680x1050 434x270mm 20.1-inch                  | 6        | 0.45%   |
| Goldstar L194W GSM4B6A 1440x900 408x255mm 18.9-inch                  | 6        | 0.45%   |
| Goldstar IPS234 GSM58D9 1920x1080 510x290mm 23.1-inch                | 6        | 0.45%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch    | 5        | 0.37%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch    | 5        | 0.37%   |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                 | 5        | 0.37%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch    | 5        | 0.37%   |
| Philips PHL 246E9Q PHLC17C 1920x1080 527x296mm 23.8-inch             | 5        | 0.37%   |
| Philips 241E PHLC035 1920x1080 521x293mm 23.5-inch                   | 5        | 0.37%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch             | 5        | 0.37%   |
| Goldstar L1953TR GSM4B43 1280x1024 338x270mm 17.0-inch               | 5        | 0.37%   |
| Goldstar L1953S GSM4B3E 1280x1024 376x301mm 19.0-inch                | 5        | 0.37%   |
| Goldstar L1918S GSM4B31 1280x1024 376x301mm 19.0-inch                | 5        | 0.37%   |
| Goldstar L1730S GSM438D 1280x1024 338x270mm 17.0-inch                | 5        | 0.37%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 5        | 0.37%   |
| Goldstar FULL HD GSM5AB9 1920x1080 480x270mm 21.7-inch               | 5        | 0.37%   |
| Samsung Electronics SyncMaster SAM03C2 1680x1050 459x296mm 21.5-inch | 4        | 0.3%    |
| Samsung Electronics SyncMaster SAM036E 1280x1024 380x300mm 19.1-inch | 4        | 0.3%    |
| Samsung Electronics SyncMaster SAM0285 1440x900 410x257mm 19.1-inch  | 4        | 0.3%    |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch | 4        | 0.3%    |
| Samsung Electronics SyncMaster SAM0259 1280x1024 380x300mm 19.1-inch | 4        | 0.3%    |
| Samsung Electronics S22D300 SAM0B3B 1920x1080 477x268mm 21.5-inch    | 4        | 0.3%    |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch              | 4        | 0.3%    |
| Goldstar L204WT GSM4E48 1680x1050 434x270mm 20.1-inch                | 4        | 0.3%    |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                     | 4        | 0.3%    |
| Goldstar 22EA53 GSM59A4 1920x1080 477x268mm 21.5-inch                | 4        | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 532      | 42.29%  |
| 1280x1024 (SXGA)   | 230      | 18.28%  |
| 1680x1050 (WSXGA+) | 124      | 9.86%   |
| 1440x900 (WXGA+)   | 58       | 4.61%   |
| 1366x768 (WXGA)    | 57       | 4.53%   |
| 2560x1440 (QHD)    | 37       | 2.94%   |
| 3840x2160 (4K)     | 32       | 2.54%   |
| 1920x1200 (WUXGA)  | 29       | 2.31%   |
| 1600x900 (HD+)     | 27       | 2.15%   |
| 1360x768           | 20       | 1.59%   |
| 1600x1200          | 19       | 1.51%   |
| Unknown            | 19       | 1.51%   |
| 1024x768 (XGA)     | 15       | 1.19%   |
| 2560x1080          | 10       | 0.79%   |
| 3440x1440          | 5        | 0.4%    |
| 2048x1536          | 5        | 0.4%    |
| 1920x540           | 5        | 0.4%    |
| 3840x1080          | 4        | 0.32%   |
| 1400x1050          | 3        | 0.24%   |
| 4480x1440          | 2        | 0.16%   |
| 3200x1080          | 2        | 0.16%   |
| 2048x1152          | 2        | 0.16%   |
| 1280x960           | 2        | 0.16%   |
| 1280x720 (HD)      | 2        | 0.16%   |
| 7040x2160          | 1        | 0.08%   |
| 5520x1080          | 1        | 0.08%   |
| 5280x1200          | 1        | 0.08%   |
| 5120x1440          | 1        | 0.08%   |
| 4000x1440          | 1        | 0.08%   |
| 3926x1440          | 1        | 0.08%   |
| 3360x1080          | 1        | 0.08%   |
| 2960x1050          | 1        | 0.08%   |
| 2640x1024          | 1        | 0.08%   |
| 2560x1600          | 1        | 0.08%   |
| 2288x1287          | 1        | 0.08%   |
| 2048x768           | 1        | 0.08%   |
| 1920x1440          | 1        | 0.08%   |
| 1280x800 (WXGA)    | 1        | 0.08%   |
| 1280x768           | 1        | 0.08%   |
| 1152x864           | 1        | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 222      | 17.47%  |
| 23      | 170      | 13.38%  |
| 19      | 153      | 12.04%  |
| 24      | 112      | 8.81%   |
| 17      | 103      | 8.1%    |
| Unknown | 100      | 7.87%   |
| 20      | 72       | 5.66%   |
| 27      | 70       | 5.51%   |
| 18      | 69       | 5.43%   |
| 22      | 62       | 4.88%   |
| 15      | 40       | 3.15%   |
| 31      | 15       | 1.18%   |
| 32      | 13       | 1.02%   |
| 34      | 11       | 0.87%   |
| 54      | 7        | 0.55%   |
| 16      | 7        | 0.55%   |
| 72      | 6        | 0.47%   |
| 42      | 5        | 0.39%   |
| 40      | 4        | 0.31%   |
| 26      | 4        | 0.31%   |
| 25      | 4        | 0.31%   |
| 12      | 4        | 0.31%   |
| 48      | 2        | 0.16%   |
| 13      | 2        | 0.16%   |
| 142     | 1        | 0.08%   |
| 75      | 1        | 0.08%   |
| 52      | 1        | 0.08%   |
| 47      | 1        | 0.08%   |
| 46      | 1        | 0.08%   |
| 43      | 1        | 0.08%   |
| 39      | 1        | 0.08%   |
| 37      | 1        | 0.08%   |
| 36      | 1        | 0.08%   |
| 29      | 1        | 0.08%   |
| 28      | 1        | 0.08%   |
| 14      | 1        | 0.08%   |
| 10      | 1        | 0.08%   |
| 7       | 1        | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 401-500        | 474      | 38.07%  |
| 501-600        | 328      | 26.35%  |
| 301-350        | 140      | 11.24%  |
| 351-400        | 115      | 9.24%   |
| Unknown        | 100      | 8.03%   |
| 701-800        | 25       | 2.01%   |
| 601-700        | 22       | 1.77%   |
| 1001-1500      | 12       | 0.96%   |
| 201-300        | 8        | 0.64%   |
| 1501-2000      | 7        | 0.56%   |
| 801-900        | 6        | 0.48%   |
| 901-1000       | 6        | 0.48%   |
| More than 2000 | 1        | 0.08%   |
| 101-200        | 1        | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 648      | 52.9%   |
| 5/4     | 198      | 16.16%  |
| 16/10   | 191      | 15.59%  |
| Unknown | 87       | 7.1%    |
| 4/3     | 68       | 5.55%   |
| 3/2     | 15       | 1.22%   |
| 21/9    | 11       | 0.9%    |
| 6/5     | 6        | 0.49%   |
| 1.00    | 1        | 0.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 488      | 38.95%  |
| 151-200        | 270      | 21.55%  |
| 141-150        | 155      | 12.37%  |
| Unknown        | 100      | 7.98%   |
| 301-350        | 72       | 5.75%   |
| 351-500        | 41       | 3.27%   |
| 251-300        | 34       | 2.71%   |
| 111-120        | 27       | 2.15%   |
| More than 1000 | 18       | 1.44%   |
| 501-1000       | 15       | 1.2%    |
| 101-110        | 14       | 1.12%   |
| 121-130        | 6        | 0.48%   |
| 131-140        | 5        | 0.4%    |
| 71-80          | 4        | 0.32%   |
| 81-90          | 1        | 0.08%   |
| 41-50          | 1        | 0.08%   |
| 1-40           | 1        | 0.08%   |
| 91-100         | 1        | 0.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 799      | 65.92%  |
| 101-120 | 265      | 21.86%  |
| Unknown | 100      | 8.25%   |
| 1-50    | 21       | 1.73%   |
| 121-160 | 16       | 1.32%   |
| 161-240 | 11       | 0.91%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1101     | 86.22%  |
| 2     | 108      | 8.46%   |
| 0     | 54       | 4.23%   |
| 3     | 14       | 1.1%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 836      | 51.67%  |
| Intel                             | 220      | 13.6%   |
| Qualcomm Atheros                  | 159      | 9.83%   |
| Nvidia                            | 99       | 6.12%   |
| Ralink Technology                 | 72       | 4.45%   |
| Qualcomm Atheros Communications   | 31       | 1.92%   |
| TP-Link                           | 26       | 1.61%   |
| Broadcom                          | 18       | 1.11%   |
| VIA Technologies                  | 16       | 0.99%   |
| Marvell Technology Group          | 16       | 0.99%   |
| Ralink                            | 14       | 0.87%   |
| Huawei Technologies               | 13       | 0.8%    |
| Sundance Technology Inc / IC Plus | 10       | 0.62%   |
| D-Link System                     | 10       | 0.62%   |
| Broadcom Limited                  | 10       | 0.62%   |
| Xiaomi                            | 9        | 0.56%   |
| ASUSTek Computer                  | 8        | 0.49%   |
| Samsung Electronics               | 4        | 0.25%   |
| Aquantia                          | 4        | 0.25%   |
| Silicon Integrated Systems [SiS]  | 3        | 0.19%   |
| MediaTek                          | 3        | 0.19%   |
| IMC Networks                      | 3        | 0.19%   |
| D-Link                            | 3        | 0.19%   |
| Curitel Communications            | 3        | 0.19%   |
| Microsoft                         | 2        | 0.12%   |
| Linksys                           | 2        | 0.12%   |
| HMD Global                        | 2        | 0.12%   |
| Google                            | 2        | 0.12%   |
| Edimax Technology                 | 2        | 0.12%   |
| STMicroelectronics                | 1        | 0.06%   |
| Standard Microsystems [SMC]       | 1        | 0.06%   |
| Sitecom Europe                    | 1        | 0.06%   |
| Qualcomm                          | 1        | 0.06%   |
| OpenMoko                          | 1        | 0.06%   |
| NetGear                           | 1        | 0.06%   |
| Montage                           | 1        | 0.06%   |
| Microchip Technology              | 1        | 0.06%   |
| LSI                               | 1        | 0.06%   |
| LG Electronics                    | 1        | 0.06%   |
| ICS Advent                        | 1        | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 669      | 38.96%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 100      | 5.82%   |
| Nvidia MCP61 Ethernet                                                      | 62       | 3.61%   |
| Ralink MT7601U Wireless Adapter                                            | 42       | 2.45%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 39       | 2.27%   |
| Intel I211 Gigabit Network Connection                                      | 30       | 1.75%   |
| Intel Ethernet Connection (2) I219-V                                       | 26       | 1.51%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 25       | 1.46%   |
| Qualcomm Atheros AR9271 802.11n                                            | 24       | 1.4%    |
| Intel Wi-Fi 6 AX200                                                        | 23       | 1.34%   |
| Intel 82579V Gigabit Network Connection                                    | 21       | 1.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 20       | 1.16%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                              | 19       | 1.11%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 19       | 1.11%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 16       | 0.93%   |
| Ralink RT5370 Wireless Adapter                                             | 15       | 0.87%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                 | 13       | 0.76%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 12       | 0.7%    |
| VIA VT6105/VT6106S [Rhine-III]                                             | 11       | 0.64%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                               | 11       | 0.64%   |
| Realtek RTL8125 2.5GbE Controller                                          | 11       | 0.64%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                  | 11       | 0.64%   |
| Nvidia MCP51 Ethernet Controller                                           | 11       | 0.64%   |
| Intel Ethernet Connection (7) I219-V                                       | 10       | 0.58%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 10       | 0.58%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                          | 9        | 0.52%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                           | 9        | 0.52%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 9        | 0.52%   |
| Nvidia CK804 Ethernet Controller                                           | 9        | 0.52%   |
| Intel Ethernet Connection I217-V                                           | 9        | 0.52%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 8        | 0.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 8        | 0.47%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                   | 8        | 0.47%   |
| Intel Wireless-AC 9260                                                     | 8        | 0.47%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 7        | 0.41%   |
| Intel Ethernet Connection (2) I218-V                                       | 7        | 0.41%   |
| Intel 82566DM-2 Gigabit Network Connection                                 | 7        | 0.41%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 6        | 0.35%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                 | 6        | 0.35%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 6        | 0.35%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Ralink Technology               | 72       | 21.82%  |
| Realtek Semiconductor           | 58       | 17.58%  |
| Intel                           | 49       | 14.85%  |
| Qualcomm Atheros                | 39       | 11.82%  |
| Qualcomm Atheros Communications | 31       | 9.39%   |
| TP-Link                         | 25       | 7.58%   |
| Ralink                          | 14       | 4.24%   |
| Broadcom                        | 8        | 2.42%   |
| ASUSTek Computer                | 8        | 2.42%   |
| D-Link System                   | 6        | 1.82%   |
| IMC Networks                    | 3        | 0.91%   |
| D-Link                          | 3        | 0.91%   |
| Microsoft                       | 2        | 0.61%   |
| Linksys                         | 2        | 0.61%   |
| Edimax Technology               | 2        | 0.61%   |
| Broadcom Limited                | 2        | 0.61%   |
| Xiaomi                          | 1        | 0.3%    |
| Sitecom Europe                  | 1        | 0.3%    |
| NetGear                         | 1        | 0.3%    |
| MediaTek                        | 1        | 0.3%    |
| LG Electronics                  | 1        | 0.3%    |
| Gemtek                          | 1        | 0.3%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                | Desktops | Percent |
|--------------------------------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                                      | 42       | 12.65%  |
| Qualcomm Atheros AR9271 802.11n                                                      | 24       | 7.23%   |
| Intel Wi-Fi 6 AX200                                                                  | 23       | 6.93%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 16       | 4.82%   |
| Ralink RT5370 Wireless Adapter                                                       | 15       | 4.52%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                         | 11       | 3.31%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                    | 9        | 2.71%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                     | 9        | 2.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 8        | 2.41%   |
| Intel Wireless-AC 9260                                                               | 8        | 2.41%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                           | 6        | 1.81%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                | 5        | 1.51%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                           | 4        | 1.2%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                              | 4        | 1.2%    |
| Realtek 802.11ac NIC                                                                 | 4        | 1.2%    |
| Ralink RT2561/RT61 rev B 802.11g                                                     | 4        | 1.2%    |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                           | 4        | 1.2%    |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]        | 4        | 1.2%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                     | 4        | 1.2%    |
| TP-Link TL-WN822N Version 4 RTL8192EU                                                | 3        | 0.9%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                  | 3        | 0.9%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                      | 3        | 0.9%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                                               | 3        | 0.9%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                      | 3        | 0.9%    |
| Realtek B1690189192                                                                  | 3        | 0.9%    |
| Ralink RT3060 Wireless 802.11n 1T/1R                                                 | 3        | 0.9%    |
| Ralink RT2561/RT61 802.11g PCI                                                       | 3        | 0.9%    |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 3        | 0.9%    |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271]        | 3        | 0.9%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                     | 3        | 0.9%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                       | 3        | 0.9%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                   | 3        | 0.9%    |
| ASUS USB-N10 802.11n Network Adapter [Realtek RTL8188SU]                             | 3        | 0.9%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                          | 2        | 0.6%    |
| TP-Link Archer T3U [Realtek RTL8812BU]                                               | 2        | 0.6%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                                   | 2        | 0.6%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                      | 2        | 0.6%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                | 2        | 0.6%    |
| Realtek RTL8188EE Wireless Network Adapter                                           | 2        | 0.6%    |
| Realtek RTL8187 Wireless Adapter                                                     | 2        | 0.6%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 806      | 60.42%  |
| Intel                             | 196      | 14.69%  |
| Qualcomm Atheros                  | 125      | 9.37%   |
| Nvidia                            | 99       | 7.42%   |
| VIA Technologies                  | 16       | 1.2%    |
| Marvell Technology Group          | 16       | 1.2%    |
| Sundance Technology Inc / IC Plus | 10       | 0.75%   |
| Broadcom                          | 10       | 0.75%   |
| Huawei Technologies               | 9        | 0.67%   |
| Xiaomi                            | 8        | 0.6%    |
| Broadcom Limited                  | 8        | 0.6%    |
| Samsung Electronics               | 4        | 0.3%    |
| D-Link System                     | 4        | 0.3%    |
| Aquantia                          | 4        | 0.3%    |
| Silicon Integrated Systems [SiS]  | 3        | 0.22%   |
| HMD Global                        | 2        | 0.15%   |
| Google                            | 2        | 0.15%   |
| TP-Link                           | 1        | 0.07%   |
| Standard Microsystems [SMC]       | 1        | 0.07%   |
| Qualcomm                          | 1        | 0.07%   |
| Microchip Technology              | 1        | 0.07%   |
| MediaTek                          | 1        | 0.07%   |
| ICS Advent                        | 1        | 0.07%   |
| HTC (High Tech Computer)          | 1        | 0.07%   |
| Hangzhou Silan Microelectronics   | 1        | 0.07%   |
| DisplayLink                       | 1        | 0.07%   |
| Apple                             | 1        | 0.07%   |
| AMD                               | 1        | 0.07%   |
| ADMtek                            | 1        | 0.07%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 669      | 48.73%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 100      | 7.28%   |
| Nvidia MCP61 Ethernet                                                      | 62       | 4.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 39       | 2.84%   |
| Intel I211 Gigabit Network Connection                                      | 30       | 2.18%   |
| Intel Ethernet Connection (2) I219-V                                       | 26       | 1.89%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 25       | 1.82%   |
| Intel 82579V Gigabit Network Connection                                    | 21       | 1.53%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 20       | 1.46%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                              | 19       | 1.38%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 19       | 1.38%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                 | 13       | 0.95%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 12       | 0.87%   |
| VIA VT6105/VT6106S [Rhine-III]                                             | 11       | 0.8%    |
| Realtek RTL8125 2.5GbE Controller                                          | 11       | 0.8%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                  | 11       | 0.8%    |
| Nvidia MCP51 Ethernet Controller                                           | 11       | 0.8%    |
| Intel Ethernet Connection (7) I219-V                                       | 10       | 0.73%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 10       | 0.73%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 9        | 0.66%   |
| Nvidia CK804 Ethernet Controller                                           | 9        | 0.66%   |
| Intel Ethernet Connection I217-V                                           | 9        | 0.66%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 8        | 0.58%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                   | 8        | 0.58%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 7        | 0.51%   |
| Intel Ethernet Connection (2) I218-V                                       | 7        | 0.51%   |
| Intel 82566DM-2 Gigabit Network Connection                                 | 7        | 0.51%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 6        | 0.44%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 6        | 0.44%   |
| Intel Ethernet Connection I217-LM                                          | 6        | 0.44%   |
| VIA VT6102/VT6103 [Rhine-II]                                               | 5        | 0.36%   |
| Nvidia MCP55 Ethernet                                                      | 5        | 0.36%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                    | 5        | 0.36%   |
| Intel Ethernet Controller I225-V                                           | 5        | 0.36%   |
| Huawei E353/E3131                                                          | 5        | 0.36%   |
| Nvidia MCP77 Ethernet                                                      | 4        | 0.29%   |
| Nvidia MCP67 Ethernet                                                      | 4        | 0.29%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                    | 4        | 0.29%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                          | 4        | 0.29%   |
| Intel 82574L Gigabit Network Connection                                    | 4        | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1235     | 79.27%  |
| WiFi     | 311      | 19.96%  |
| Modem    | 11       | 0.71%   |
| Unknown  | 1        | 0.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1090     | 85.16%  |
| WiFi     | 190      | 14.84%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1007     | 79.29%  |
| 2     | 212      | 16.69%  |
| 0     | 26       | 2.05%   |
| 3     | 23       | 1.81%   |
| 6     | 1        | 0.08%   |
| 4     | 1        | 0.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1256     | 99.52%  |
| Yes  | 6        | 0.48%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 84       | 45.65%  |
| Intel                           | 45       | 24.46%  |
| ASUSTek Computer                | 14       | 7.61%   |
| Qualcomm Atheros Communications | 12       | 6.52%   |
| Broadcom                        | 8        | 4.35%   |
| Realtek Semiconductor           | 6        | 3.26%   |
| IMC Networks                    | 3        | 1.63%   |
| Conwise Technology              | 3        | 1.63%   |
| D-Link                          | 2        | 1.09%   |
| Realtek                         | 1        | 0.54%   |
| Logitech                        | 1        | 0.54%   |
| Integrated System Solution      | 1        | 0.54%   |
| Hewlett-Packard                 | 1        | 0.54%   |
| Edimax Technology               | 1        | 0.54%   |
| D-Link System                   | 1        | 0.54%   |
| Apple                           | 1        | 0.54%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 84       | 45.65%  |
| Intel AX200 Bluetooth                                 | 22       | 11.96%  |
| Qualcomm Atheros AR3011 Bluetooth                     | 10       | 5.43%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 8        | 4.35%   |
| Realtek Bluetooth Radio                               | 6        | 3.26%   |
| Intel Bluetooth wireless interface                    | 5        | 2.72%   |
| ASUS Bluetooth Adapter                                | 5        | 2.72%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 4        | 2.17%   |
| Broadcom BCM2045 Bluetooth                            | 4        | 2.17%   |
| Intel Wireless-AC 3168 Bluetooth                      | 3        | 1.63%   |
| Conwise CW6622                                        | 3        | 1.63%   |
| ASUS BCM20702A0                                       | 3        | 1.63%   |
| Qualcomm Atheros  Bluetooth Device                    | 2        | 1.09%   |
| Intel AX210 Bluetooth                                 | 2        | 1.09%   |
| IMC Networks Bluetooth Radio                          | 2        | 1.09%   |
| D-Link DBT-122 Bluetooth adapter                      | 2        | 1.09%   |
| ASUS Qualcomm Bluetooth 4.1                           | 2        | 1.09%   |
| ASUS Bluetooth Radio                                  | 2        | 1.09%   |
| Realtek Bluetooth Radio                               | 1        | 0.54%   |
| Logitech BT Mini-Receiver (HCI mode)                  | 1        | 0.54%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 1        | 0.54%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 0.54%   |
| IMC Networks Bluetooth Module                         | 1        | 0.54%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]         | 1        | 0.54%   |
| Edimax Bluetooth Adapter                              | 1        | 0.54%   |
| D-Link System DBT-122 Bluetooth                       | 1        | 0.54%   |
| Broadcom Bluetooth dongle                             | 1        | 0.54%   |
| Broadcom Bluetooth 3.0+HS USB Adapter                 | 1        | 0.54%   |
| Broadcom Bluetooth 2.0+eDR dongle                     | 1        | 0.54%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter      | 1        | 0.54%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 1        | 0.54%   |
| ASUS ASUS USB-BT500                                   | 1        | 0.54%   |
| Apple Bluetooth USB Host Controller                   | 1        | 0.54%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 708      | 35.92%  |
| AMD                              | 544      | 27.6%   |
| Nvidia                           | 523      | 26.53%  |
| C-Media Electronics              | 58       | 2.94%   |
| Creative Labs                    | 44       | 2.23%   |
| Logitech                         | 9        | 0.46%   |
| VIA Technologies                 | 8        | 0.41%   |
| ASUSTek Computer                 | 8        | 0.41%   |
| Generalplus Technology           | 6        | 0.3%    |
| JMTek                            | 5        | 0.25%   |
| Texas Instruments                | 4        | 0.2%    |
| Plantronics                      | 4        | 0.2%    |
| ULi Electronics                  | 3        | 0.15%   |
| Silicon Integrated Systems [SiS] | 3        | 0.15%   |
| Ensoniq                          | 3        | 0.15%   |
| Creative Technology              | 3        | 0.15%   |
| Yamaha                           | 2        | 0.1%    |
| Tenx Technology                  | 2        | 0.1%    |
| SteelSeries ApS                  | 2        | 0.1%    |
| Sennheiser Communications        | 2        | 0.1%    |
| SAVITECH                         | 2        | 0.1%    |
| Realtek Semiconductor            | 2        | 0.1%    |
| Razer USA                        | 2        | 0.1%    |
| BEHRINGER International          | 2        | 0.1%    |
| ZOOM                             | 1        | 0.05%   |
| Vitana                           | 1        | 0.05%   |
| ROCCAT                           | 1        | 0.05%   |
| Nokia Mobile Phones              | 1        | 0.05%   |
| No brand                         | 1        | 0.05%   |
| Microsoft                        | 1        | 0.05%   |
| M-Audio                          | 1        | 0.05%   |
| Kingston Technology              | 1        | 0.05%   |
| iConnectivity                    | 1        | 0.05%   |
| Hangzhou Worlde                  | 1        | 0.05%   |
| GYROCOM C&C                      | 1        | 0.05%   |
| Guillemot                        | 1        | 0.05%   |
| GN Netcom                        | 1        | 0.05%   |
| Giga-Byte Technology             | 1        | 0.05%   |
| Elite Silicon                    | 1        | 0.05%   |
| EGO SYStems                      | 1        | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                                      | 165      | 7.41%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 120      | 5.39%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 119      | 5.34%   |
| AMD FCH Azalia Controller                                                         | 77       | 3.46%   |
| Nvidia MCP61 High Definition Audio                                                | 72       | 3.23%   |
| Nvidia GF108 High Definition Audio Controller                                     | 60       | 2.69%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 56       | 2.51%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 55       | 2.47%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 52       | 2.33%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 49       | 2.2%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 49       | 2.2%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 45       | 2.02%   |
| Intel 200 Series PCH HD Audio                                                     | 44       | 1.97%   |
| Nvidia High Definition Audio Controller                                           | 43       | 1.93%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 43       | 1.93%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 42       | 1.89%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 39       | 1.75%   |
| AMD Family 17h/19h HD Audio Controller                                            | 37       | 1.66%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 35       | 1.57%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 33       | 1.48%   |
| AMD Starship/Matisse HD Audio Controller                                          | 32       | 1.44%   |
| Nvidia GK107 HDMI Audio Controller                                                | 30       | 1.35%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 30       | 1.35%   |
| Intel Cannon Lake PCH cAVS                                                        | 29       | 1.3%    |
| Nvidia GP106 High Definition Audio Controller                                     | 28       | 1.26%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 27       | 1.21%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 25       | 1.12%   |
| Nvidia GP104 High Definition Audio Controller                                     | 23       | 1.03%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 20       | 0.9%    |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                    | 20       | 0.9%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 19       | 0.85%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                     | 19       | 0.85%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 19       | 0.85%   |
| Nvidia GF116 High Definition Audio Controller                                     | 17       | 0.76%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 17       | 0.76%   |
| Nvidia TU116 High Definition Audio Controller                                     | 16       | 0.72%   |
| Nvidia GP108 High Definition Audio Controller                                     | 16       | 0.72%   |
| Nvidia GK106 HDMI Audio Controller                                                | 16       | 0.72%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                     | 16       | 0.72%   |
| AMD Trinity HDMI Audio Controller                                                 | 16       | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Unknown                    | 448      | 41.95%  |
| Kingston                   | 183      | 17.13%  |
| Samsung Electronics        | 56       | 5.24%   |
| SK hynix                   | 51       | 4.78%   |
| Crucial                    | 40       | 3.75%   |
| GOODRAM                    | 36       | 3.37%   |
| Team                       | 35       | 3.28%   |
| G.Skill                    | 27       | 2.53%   |
| Corsair                    | 24       | 2.25%   |
| Micron Technology          | 21       | 1.97%   |
| Transcend                  | 16       | 1.5%    |
| AMD                        | 16       | 1.5%    |
| Silicon Power              | 15       | 1.4%    |
| Patriot                    | 11       | 1.03%   |
| Exceleram                  | 11       | 1.03%   |
| Nanya Technology           | 8        | 0.75%   |
| Apacer                     | 7        | 0.66%   |
| GeIL                       | 6        | 0.56%   |
| Kllisre                    | 5        | 0.47%   |
| TwinMOS                    | 4        | 0.37%   |
| Elpida                     | 4        | 0.37%   |
| A-DATA Technology          | 4        | 0.37%   |
| TakeMS                     | 3        | 0.28%   |
| Swissbit                   | 3        | 0.28%   |
| Wilk                       | 2        | 0.19%   |
| Qumo                       | 2        | 0.19%   |
| Qimonda                    | 2        | 0.19%   |
| PNY                        | 2        | 0.19%   |
| Kingmax                    | 2        | 0.19%   |
| KETECH                     | 2        | 0.19%   |
| HMD                        | 2        | 0.19%   |
| Goldkey                    | 2        | 0.19%   |
| Unknown                    | 2        | 0.19%   |
| Wilk Elektronik            | 1        | 0.09%   |
| Unknown (ABCD)             | 1        | 0.09%   |
| Unknown (00FFFFFFFFFFFFFF) | 1        | 0.09%   |
| Unifosa                    | 1        | 0.09%   |
| Toshiba                    | 1        | 0.09%   |
| TOP MEDIA                  | 1        | 0.09%   |
| OCZ                        | 1        | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s          | 36       | 2.97%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s              | 25       | 2.06%   |
| Unknown RAM Module 1024MB DIMM SDRAM                 | 23       | 1.9%    |
| Unknown RAM Module 2048MB DIMM 800MT/s               | 21       | 1.73%   |
| Unknown RAM Module 2048MB DIMM SDRAM                 | 19       | 1.57%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s              | 17       | 1.4%    |
| Unknown RAM Module 4096MB DIMM 400MT/s               | 14       | 1.16%   |
| Unknown RAM Module 2048MB DIMM 667MT/s               | 12       | 0.99%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s          | 12       | 0.99%   |
| Unknown RAM Module 1024MB DIMM 667MT/s               | 12       | 0.99%   |
| Unknown RAM Module 1024MB DIMM                       | 12       | 0.99%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s         | 10       | 0.83%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s | 10       | 0.83%   |
| Unknown RAM Module 512MB DIMM SDRAM                  | 9        | 0.74%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s         | 9        | 0.74%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s          | 9        | 0.74%   |
| Unknown RAM Module 2048MB DIMM 1066MT/s              | 9        | 0.74%   |
| Unknown RAM Module 512MB DIMM                        | 8        | 0.66%   |
| Unknown RAM Module 2048MB DIMM 400MT/s               | 8        | 0.66%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s    | 8        | 0.66%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                 | 7        | 0.58%   |
| Unknown RAM Module 2048MB DIMM                       | 7        | 0.58%   |
| Unknown RAM Module 1024MB DIMM DDR2 333MT/s          | 7        | 0.58%   |
| Unknown RAM Module 1024MB DIMM DDR2                  | 7        | 0.58%   |
| Team RAM Elite-1600 8GB DIMM DDR3 1600MT/s           | 7        | 0.58%   |
| Unknown RAM Module 2048MB DIMM DDR2 333MT/s          | 6        | 0.5%    |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s  | 6        | 0.5%    |
| GOODRAM RAM GR1333D364L9/2G 2GB DIMM DDR3 1333MT/s   | 6        | 0.5%    |
| Unknown RAM Module 4096MB DIMM 1600MT/s              | 5        | 0.41%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s             | 5        | 0.41%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s             | 5        | 0.41%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s          | 5        | 0.41%   |
| Team RAM Elite-1333 4GB DIMM DDR3 1333MT/s           | 5        | 0.41%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s  | 5        | 0.41%   |
| Kingston RAM KHX3200C18D4/8G 8GB DIMM DDR4 3333MT/s  | 5        | 0.41%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s  | 5        | 0.41%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1866MT/s  | 5        | 0.41%   |
| GOODRAM RAM GR1333D364L9/4G 4GB DIMM DDR3 1600MT/s   | 5        | 0.41%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s            | 4        | 0.33%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                 | 4        | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 303      | 32.1%   |
| Unknown | 194      | 20.55%  |
| DDR4    | 191      | 20.23%  |
| DDR2    | 149      | 15.78%  |
| SDRAM   | 73       | 7.73%   |
| DDR     | 33       | 3.5%    |
| LPDDR4  | 1        | 0.11%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 905      | 97.63%  |
| SODIMM  | 20       | 2.16%   |
| RIMM    | 1        | 0.11%   |
| FB-DIMM | 1        | 0.11%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 318      | 29.44%  |
| 4096  | 273      | 25.28%  |
| 8192  | 243      | 22.5%   |
| 1024  | 143      | 13.24%  |
| 16384 | 44       | 4.07%   |
| 512   | 35       | 3.24%   |
| 32768 | 16       | 1.48%   |
| 256   | 8        | 0.74%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 166      | 16.15%  |
| 1333    | 165      | 16.05%  |
| 800     | 114      | 11.09%  |
| Unknown | 93       | 9.05%   |
| 667     | 78       | 7.59%   |
| 2400    | 48       | 4.67%   |
| 2133    | 44       | 4.28%   |
| 400     | 36       | 3.5%    |
| 3200    | 31       | 3.02%   |
| 1867    | 26       | 2.53%   |
| 3600    | 24       | 2.33%   |
| 2667    | 24       | 2.33%   |
| 1866    | 18       | 1.75%   |
| 1066    | 17       | 1.65%   |
| 333     | 17       | 1.65%   |
| 533     | 13       | 1.26%   |
| 3466    | 10       | 0.97%   |
| 3000    | 8        | 0.78%   |
| 1067    | 8        | 0.78%   |
| 1800    | 7        | 0.68%   |
| 3400    | 6        | 0.58%   |
| 3333    | 6        | 0.58%   |
| 3066    | 6        | 0.58%   |
| 1639    | 6        | 0.58%   |
| 266     | 6        | 0.58%   |
| 49926   | 4        | 0.39%   |
| 3866    | 4        | 0.39%   |
| 2933    | 4        | 0.39%   |
| 2866    | 4        | 0.39%   |
| 3800    | 3        | 0.29%   |
| 2666    | 3        | 0.29%   |
| 2134    | 3        | 0.29%   |
| 2048    | 3        | 0.29%   |
| 1400    | 3        | 0.29%   |
| 3334    | 2        | 0.19%   |
| 2800    | 2        | 0.19%   |
| 2465    | 2        | 0.19%   |
| 2000    | 2        | 0.19%   |
| 1334    | 2        | 0.19%   |
| 66      | 2        | 0.19%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Canon                 | 23       | 34.33%  |
| Samsung Electronics   | 20       | 29.85%  |
| Hewlett-Packard       | 8        | 11.94%  |
| Seiko Epson           | 5        | 7.46%   |
| Brother Industries    | 3        | 4.48%   |
| WinChipHead           | 2        | 2.99%   |
| Prolific Technology   | 2        | 2.99%   |
| Zebra                 | 1        | 1.49%   |
| Xerox                 | 1        | 1.49%   |
| Oki Data              | 1        | 1.49%   |
| Lexmark International | 1        | 1.49%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Samsung SCX-4200 series                       | 6        | 8.96%   |
| Samsung ML-1520 Laser Printer                 | 3        | 4.48%   |
| Canon MP160                                   | 3        | 4.48%   |
| Canon MF4410                                  | 3        | 4.48%   |
| WinChipHead CH34x printer adapter cable       | 2        | 2.99%   |
| Samsung Xerox Phaser 3117 Laser Printer       | 2        | 2.99%   |
| Samsung ML-1710 Printer                       | 2        | 2.99%   |
| Samsung M2070 Series                          | 2        | 2.99%   |
| Samsung M2020 Series                          | 2        | 2.99%   |
| Prolific PL2305 Parallel Port                 | 2        | 2.99%   |
| HP LaserJet 1020                              | 2        | 2.99%   |
| HP LaserJet 1012                              | 2        | 2.99%   |
| Canon MF4320-4350                             | 2        | 2.99%   |
| Canon LaserShot LBP-1120 Printer              | 2        | 2.99%   |
| Canon iP2700 series                           | 2        | 2.99%   |
| Zebra ZTC S4M-200dpi ZPL                      | 1        | 1.49%   |
| Xerox Printing Support                        | 1        | 1.49%   |
| Seiko Epson XP-243 245 247 Series             | 1        | 1.49%   |
| Seiko Epson Printer                           | 1        | 1.49%   |
| Seiko Epson ME 340 Series/Stylus NX130 Series | 1        | 1.49%   |
| Seiko Epson L380 Series                       | 1        | 1.49%   |
| Seiko Epson L210 Series                       | 1        | 1.49%   |
| Samsung Xerox Phaser 3150                     | 1        | 1.49%   |
| Samsung SCX-4100 Scanner                      | 1        | 1.49%   |
| Samsung ML-1660 Series                        | 1        | 1.49%   |
| Oki Data USB Device                           | 1        | 1.49%   |
| Lexmark International 3300 series             | 1        | 1.49%   |
| HP LaserJet P1005                             | 1        | 1.49%   |
| HP LaserJet 1018                              | 1        | 1.49%   |
| HP LaserJet 1010                              | 1        | 1.49%   |
| HP DeskJet F2100 Printer series               | 1        | 1.49%   |
| Canon PIXMA MP280                             | 1        | 1.49%   |
| Canon PIXMA MP230                             | 1        | 1.49%   |
| Canon PIXMA MG3600 Series                     | 1        | 1.49%   |
| Canon PIXMA iP1800 Printer                    | 1        | 1.49%   |
| Canon MF4010 series                           | 1        | 1.49%   |
| Canon MF3110                                  | 1        | 1.49%   |
| Canon MF3010                                  | 1        | 1.49%   |
| Canon LBP6020                                 | 1        | 1.49%   |
| Canon LBP3010/LBP3018/LBP3050                 | 1        | 1.49%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 6        | 31.58%  |
| Seiko Epson        | 5        | 26.32%  |
| Ultima Electronics | 3        | 15.79%  |
| Hewlett-Packard    | 3        | 15.79%  |
| Mustek Systems     | 2        | 10.53%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 3        | 15.79%  |
| Canon CanoScan LIDE 25                                                                | 3        | 15.79%  |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 2        | 10.53%  |
| Seiko Epson Scanner                                                                   | 1        | 5.26%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 1        | 5.26%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]                                     | 1        | 5.26%   |
| Mustek Systems SNAPSCAN e22                                                           | 1        | 5.26%   |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 1        | 5.26%   |
| HP ScanJet 4400c                                                                      | 1        | 5.26%   |
| HP ScanJet 3800c                                                                      | 1        | 5.26%   |
| HP ScanJet 2400c                                                                      | 1        | 5.26%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 1        | 5.26%   |
| Canon CanoScan LiDE 60                                                                | 1        | 5.26%   |
| Canon CanoScan LiDE 110                                                               | 1        | 5.26%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 104      | 33.02%  |
| Z-Star Microelectronics                | 69       | 21.9%   |
| Microdia                               | 35       | 11.11%  |
| Aveo Technology                        | 18       | 5.71%   |
| KYE Systems (Mouse Systems)            | 16       | 5.08%   |
| Pixart Imaging                         | 10       | 3.17%   |
| Microsoft                              | 9        | 2.86%   |
| Cubeternet                             | 7        | 2.22%   |
| GEMBIRD                                | 6        | 1.9%    |
| Hewlett-Packard                        | 4        | 1.27%   |
| Arkmicro Technologies                  | 4        | 1.27%   |
| Apple                                  | 4        | 1.27%   |
| Silicon Motion                         | 3        | 0.95%   |
| Realtek Semiconductor                  | 3        | 0.95%   |
| Unknown                                | 2        | 0.63%   |
| Sunplus Innovation Technology          | 2        | 0.63%   |
| Samsung Electronics                    | 2        | 0.63%   |
| Google                                 | 2        | 0.63%   |
| Generalplus Technology                 | 2        | 0.63%   |
| Trust                                  | 1        | 0.32%   |
| Teslong Camera                         | 1        | 0.32%   |
| SJ-180517-N                            | 1        | 0.32%   |
| Novatek Microelectronics               | 1        | 0.32%   |
| lihappe8                               | 1        | 0.32%   |
| LG Electronics                         | 1        | 0.32%   |
| Jieli Technology                       | 1        | 0.32%   |
| IMC Networks                           | 1        | 0.32%   |
| HTC (High Tech Computer)               | 1        | 0.32%   |
| Chicony Electronics                    | 1        | 0.32%   |
| Cheng Uei Precision Industry (Foxlink) | 1        | 0.32%   |
| Alcor Micro                            | 1        | 0.32%   |
| Unknown                                | 1        | 0.32%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 38       | 12.06%  |
| Z-Star Venus USB2.0 Camera                        | 33       | 10.48%  |
| Microdia Camera                                   | 17       | 5.4%    |
| Logitech Webcam C310                              | 16       | 5.08%   |
| Z-Star A4 TECH USB2.0 PC Camera J                 | 13       | 4.13%   |
| Logitech Webcam C170                              | 13       | 4.13%   |
| Z-Star USB2.0 Camera                              | 12       | 3.81%   |
| Microdia Sonix USB 2.0 Camera                     | 11       | 3.49%   |
| Aveo Camera                                       | 11       | 3.49%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro              | 10       | 3.17%   |
| Z-Star Full HD 1080P PC Camera                    | 8        | 2.54%   |
| Microsoft LifeCam HD-3000                         | 7        | 2.22%   |
| Microdia USB 2.0 Camera                           | 6        | 1.9%    |
| Logitech Webcam C210                              | 6        | 1.9%    |
| Logitech Logitech Webcam C100                     | 6        | 1.9%    |
| KYE Systems (Mouse Systems) iLook 320             | 5        | 1.59%   |
| Logitech Webcam C200                              | 4        | 1.27%   |
| Aveo USB2.0 Camera                                | 4        | 1.27%   |
| Arkmicro USB2.0 PC CAMERA                         | 4        | 1.27%   |
| Realtek FULL HD 1080P Webcam                      | 3        | 0.95%   |
| Logitech HD Webcam C525                           | 3        | 0.95%   |
| Logitech HD Webcam B910                           | 3        | 0.95%   |
| KYE Systems (Mouse Systems) Genius FaceCam 320    | 3        | 0.95%   |
| GEMBIRD USB2.0 PC CAMERA                          | 3        | 0.95%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 3        | 0.95%   |
| Cubeternet WebCam                                 | 3        | 0.95%   |
| Apple iPhone 5/5C/5S/6/SE                         | 3        | 0.95%   |
| Z-Star Vimicro USB2.0 UVC PC Camera               | 2        | 0.63%   |
| Unknown HD camera                                 | 2        | 0.63%   |
| Silicon Motion SM731 Camera                       | 2        | 0.63%   |
| Samsung Galaxy series, misc. (MTP mode)           | 2        | 0.63%   |
| Logitech Webcam C600                              | 2        | 0.63%   |
| Logitech Webcam C120                              | 2        | 0.63%   |
| Logitech Webcam C110                              | 2        | 0.63%   |
| Logitech Logitech Webcam C160                     | 2        | 0.63%   |
| Logitech HD Webcam C510                           | 2        | 0.63%   |
| KYE Systems (Mouse Systems) Genius iSlim 330      | 2        | 0.63%   |
| Google Nexus/Pixel Device (MTP + debug)           | 2        | 0.63%   |
| Cubeternet USB2.0 Camera                          | 2        | 0.63%   |
| Z-Star USB 2.0 PC Camera                          | 1        | 0.32%   |

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
| Avtor                 | 2        | 50%     |
| Alcor Micro           | 1        | 25%     |
| Advanced Card Systems | 1        | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Avtor SecureToken                   | 2        | 50%     |
| Alcor Micro AU9540 Smartcard Reader | 1        | 25%     |
| Advanced Card Systems ACR122U       | 1        | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 1139     | 88.91%  |
| 1     | 123      | 9.6%    |
| 2     | 16       | 1.25%   |
| 3     | 2        | 0.16%   |
| 7     | 1        | 0.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 68       | 44.44%  |
| Net/wireless             | 28       | 18.3%   |
| Communication controller | 16       | 10.46%  |
| Unassigned class         | 10       | 6.54%   |
| Sound                    | 9        | 5.88%   |
| Camera                   | 6        | 3.92%   |
| Multimedia controller    | 4        | 2.61%   |
| Chipcard                 | 3        | 1.96%   |
| Bluetooth                | 3        | 1.96%   |
| Storage/ide              | 2        | 1.31%   |
| Storage/raid             | 1        | 0.65%   |
| Storage                  | 1        | 0.65%   |
| Modem                    | 1        | 0.65%   |
| Dvb card                 | 1        | 0.65%   |

