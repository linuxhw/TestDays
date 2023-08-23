Ubuntu MATE 22.04 - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu MATE 22.04.

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

Total: 180

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Biostar       | A10N-8800E                  | [5ccf8e7d00](https://linux-hardware.org/?probe=5ccf8e7d00) | Aug 11, 2023 |
| Unknown       | Unknown                     | [78f477986b](https://linux-hardware.org/?probe=78f477986b) | Aug 10, 2023 |
| MACHINIST     | E5 MR9A PRO MAX V1.1        | [0c4903c4d2](https://linux-hardware.org/?probe=0c4903c4d2) | Aug 10, 2023 |
| Gigabyte      | B85M-D3H                    | [32e3874db3](https://linux-hardware.org/?probe=32e3874db3) | Jul 28, 2023 |
| Lenovo        | 3740 NOK                    | [9e156dd92f](https://linux-hardware.org/?probe=9e156dd92f) | Jul 26, 2023 |
| Gigabyte      | B85M-D3H                    | [67daf82d15](https://linux-hardware.org/?probe=67daf82d15) | Jul 24, 2023 |
| Gigabyte      | B550 GAMING X V2            | [0a3cc7970c](https://linux-hardware.org/?probe=0a3cc7970c) | Jul 23, 2023 |
| ASUSTek       | PRIME Z590-P                | [02903e0210](https://linux-hardware.org/?probe=02903e0210) | Jul 22, 2023 |
| Gigabyte      | G41MT-S2                    | [d625267663](https://linux-hardware.org/?probe=d625267663) | Jul 17, 2023 |
| Gigabyte      | B85M-D3H                    | [1e85aec604](https://linux-hardware.org/?probe=1e85aec604) | Jul 09, 2023 |
| Gigabyte      | B85M-D3H                    | [f73623381d](https://linux-hardware.org/?probe=f73623381d) | Jul 08, 2023 |
| Gigabyte      | B85M-D3H                    | [d37d74ba93](https://linux-hardware.org/?probe=d37d74ba93) | Jul 07, 2023 |
| ASRock        | Z370 Killer SLI             | [b7a676e2fc](https://linux-hardware.org/?probe=b7a676e2fc) | Jul 05, 2023 |
| ASRock        | Z370 Killer SLI             | [e7c0ca1bfc](https://linux-hardware.org/?probe=e7c0ca1bfc) | Jul 05, 2023 |
| Unknown       | Unknown                     | [23956fd693](https://linux-hardware.org/?probe=23956fd693) | Jul 04, 2023 |
| Gigabyte      | B85M-D3H                    | [ce2d3b5375](https://linux-hardware.org/?probe=ce2d3b5375) | Jul 02, 2023 |
| Gigabyte      | B85M-D3H                    | [0bb17f7e1b](https://linux-hardware.org/?probe=0bb17f7e1b) | Jul 01, 2023 |
| ASUSTek       | PRIME Z590-P                | [fb7e164f62](https://linux-hardware.org/?probe=fb7e164f62) | Jul 01, 2023 |
| ASUSTek       | PRIME Z590-P                | [2774be84e6](https://linux-hardware.org/?probe=2774be84e6) | Jul 01, 2023 |
| Gigabyte      | B85M-D3H                    | [99b07ae636](https://linux-hardware.org/?probe=99b07ae636) | Jun 30, 2023 |
| Gigabyte      | B85M-D3H                    | [498eb9b539](https://linux-hardware.org/?probe=498eb9b539) | Jun 30, 2023 |
| ASUSTek       | H61M-K                      | [ddc5e387cb](https://linux-hardware.org/?probe=ddc5e387cb) | Jun 24, 2023 |
| ASUSTek       | P7P55 LX                    | [e700828afa](https://linux-hardware.org/?probe=e700828afa) | Jun 23, 2023 |
| ASUSTek       | P7P55 LX                    | [cd9b9aae75](https://linux-hardware.org/?probe=cd9b9aae75) | Jun 23, 2023 |
| Gigabyte      | B85M-D3H                    | [033c027010](https://linux-hardware.org/?probe=033c027010) | Jun 18, 2023 |
| Gigabyte      | B85M-D3H                    | [fe0d892e82](https://linux-hardware.org/?probe=fe0d892e82) | Jun 16, 2023 |
| HP            | 8643 SMVB                   | [db301ecd59](https://linux-hardware.org/?probe=db301ecd59) | Jun 11, 2023 |
| Gigabyte      | B85M-D3H                    | [befd126f43](https://linux-hardware.org/?probe=befd126f43) | Jun 07, 2023 |
| Gigabyte      | B85M-D3H                    | [e146923f12](https://linux-hardware.org/?probe=e146923f12) | Jun 07, 2023 |
| HP            | 1998                        | [c6183bd564](https://linux-hardware.org/?probe=c6183bd564) | Jun 05, 2023 |
| Gigabyte      | B85M-D3H                    | [0bd595e07a](https://linux-hardware.org/?probe=0bd595e07a) | Jun 04, 2023 |
| Gigabyte      | B85M-D3H                    | [908f094e9d](https://linux-hardware.org/?probe=908f094e9d) | Jun 02, 2023 |
| MSI           | H97 GAMING 3                | [f9c0a669c5](https://linux-hardware.org/?probe=f9c0a669c5) | Jun 02, 2023 |
| ASUSTek       | H61M-K                      | [c6ee1e5e32](https://linux-hardware.org/?probe=c6ee1e5e32) | Jun 02, 2023 |
| Unknown       | HX90                        | [d38fff55af](https://linux-hardware.org/?probe=d38fff55af) | May 28, 2023 |
| Gigabyte      | B85M-D3H                    | [67122d7cd6](https://linux-hardware.org/?probe=67122d7cd6) | May 12, 2023 |
| Gigabyte      | B85M-D3H                    | [9c8ffba5f4](https://linux-hardware.org/?probe=9c8ffba5f4) | May 12, 2023 |
| Gigabyte      | B85M-D3H                    | [11a41c975d](https://linux-hardware.org/?probe=11a41c975d) | May 07, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [b6ec076cc6](https://linux-hardware.org/?probe=b6ec076cc6) | May 05, 2023 |
| Acer          | Aspire X1430                | [4bdb74f57e](https://linux-hardware.org/?probe=4bdb74f57e) | May 04, 2023 |
| Gigabyte      | B85M-D3H                    | [f9c27ab898](https://linux-hardware.org/?probe=f9c27ab898) | May 02, 2023 |
| Gigabyte      | B85M-D3H                    | [2fe28d7f43](https://linux-hardware.org/?probe=2fe28d7f43) | Apr 29, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [ef3f4d1ac1](https://linux-hardware.org/?probe=ef3f4d1ac1) | Apr 29, 2023 |
| Gigabyte      | B85M-D3H                    | [c0c226bf8c](https://linux-hardware.org/?probe=c0c226bf8c) | Apr 28, 2023 |
| Gigabyte      | P55-UD3                     | [cb8885f205](https://linux-hardware.org/?probe=cb8885f205) | Apr 25, 2023 |
| Gigabyte      | P55-UD3                     | [cacc141f4f](https://linux-hardware.org/?probe=cacc141f4f) | Apr 25, 2023 |
| Gigabyte      | B85M-D3H                    | [88a6d9040e](https://linux-hardware.org/?probe=88a6d9040e) | Apr 23, 2023 |
| ASUSTek       | Z170-P                      | [b003b5c775](https://linux-hardware.org/?probe=b003b5c775) | Apr 22, 2023 |
| ASUSTek       | M5A97 R2.0                  | [90e0cff0ad](https://linux-hardware.org/?probe=90e0cff0ad) | Apr 22, 2023 |
| AMI           | Intel                       | [b7a63bbfc7](https://linux-hardware.org/?probe=b7a63bbfc7) | Apr 15, 2023 |
| AMI           | Intel                       | [ec0a5e657e](https://linux-hardware.org/?probe=ec0a5e657e) | Apr 14, 2023 |
| Gigabyte      | B85M-D3H                    | [7041b36ac5](https://linux-hardware.org/?probe=7041b36ac5) | Apr 14, 2023 |
| Lenovo        | ThinkStation D20 4158GK1    | [44d9536051](https://linux-hardware.org/?probe=44d9536051) | Apr 14, 2023 |
| HP            | 1494                        | [9c5dc1a221](https://linux-hardware.org/?probe=9c5dc1a221) | Apr 13, 2023 |
| Gigabyte      | B85M-D3H                    | [87be7a6dc0](https://linux-hardware.org/?probe=87be7a6dc0) | Apr 09, 2023 |
| Dell          | 0J3C2F A00                  | [e2c3600e8b](https://linux-hardware.org/?probe=e2c3600e8b) | Apr 07, 2023 |
| ASUSTek       | M5A97 R2.0                  | [248ef68079](https://linux-hardware.org/?probe=248ef68079) | Apr 03, 2023 |
| Gigabyte      | B85M-D3H                    | [77187502c9](https://linux-hardware.org/?probe=77187502c9) | Apr 01, 2023 |
| Gigabyte      | B85M-D3H                    | [a074e581b0](https://linux-hardware.org/?probe=a074e581b0) | Mar 28, 2023 |
| ASUSTek       | M5A97 R2.0                  | [d56f48b9d1](https://linux-hardware.org/?probe=d56f48b9d1) | Mar 27, 2023 |
| Shenzhen M... | HX90G                       | [fb3f1be00d](https://linux-hardware.org/?probe=fb3f1be00d) | Mar 26, 2023 |
| Gigabyte      | B85M-D3H                    | [890cd39d63](https://linux-hardware.org/?probe=890cd39d63) | Mar 26, 2023 |
| ASUSTek       | H61M-K                      | [dcae89c3e5](https://linux-hardware.org/?probe=dcae89c3e5) | Mar 21, 2023 |
| ASUSTek       | H61M-K                      | [9ff80f0344](https://linux-hardware.org/?probe=9ff80f0344) | Mar 21, 2023 |
| CCE           | NM70-I                      | [3e99b6e12d](https://linux-hardware.org/?probe=3e99b6e12d) | Mar 21, 2023 |
| ASUSTek       | M5A78L LE                   | [e18778e282](https://linux-hardware.org/?probe=e18778e282) | Mar 20, 2023 |
| Lenovo        | Bantry CRB 31900058 STD     | [bbe02b925a](https://linux-hardware.org/?probe=bbe02b925a) | Mar 19, 2023 |
| Lenovo        | Bantry CRB 31900058 STD     | [d376f92f8d](https://linux-hardware.org/?probe=d376f92f8d) | Mar 19, 2023 |
| Gigabyte      | B85M-D3H                    | [605bc3d5b0](https://linux-hardware.org/?probe=605bc3d5b0) | Mar 19, 2023 |
| Gigabyte      | B85M-D3H                    | [4cee2dc95e](https://linux-hardware.org/?probe=4cee2dc95e) | Mar 18, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | [7298c4b04b](https://linux-hardware.org/?probe=7298c4b04b) | Mar 17, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | [794bc239ab](https://linux-hardware.org/?probe=794bc239ab) | Mar 17, 2023 |
| ASUSTek       | M5A97 R2.0                  | [526e33e980](https://linux-hardware.org/?probe=526e33e980) | Mar 15, 2023 |
| ASRock        | A320M-HDV R4.0              | [8d2ca6cedc](https://linux-hardware.org/?probe=8d2ca6cedc) | Mar 14, 2023 |
| ASUSTek       | M5A97 R2.0                  | [2f69480899](https://linux-hardware.org/?probe=2f69480899) | Mar 14, 2023 |
| HP            | 339A                        | [fa78907d67](https://linux-hardware.org/?probe=fa78907d67) | Mar 12, 2023 |
| Gigabyte      | B85M-D3H                    | [f9dfd84f86](https://linux-hardware.org/?probe=f9dfd84f86) | Mar 12, 2023 |
| Gigabyte      | B85M-D3H                    | [ee115bdfb8](https://linux-hardware.org/?probe=ee115bdfb8) | Mar 11, 2023 |
| MSI           | X370 SLI PLUS               | [d2ac8dd020](https://linux-hardware.org/?probe=d2ac8dd020) | Mar 07, 2023 |
| Gigabyte      | B85M-D3H                    | [adce83e80e](https://linux-hardware.org/?probe=adce83e80e) | Mar 07, 2023 |
| Gigabyte      | B85M-D3H                    | [9178ffc6f9](https://linux-hardware.org/?probe=9178ffc6f9) | Mar 05, 2023 |
| MSI           | X570-A PRO                  | [7d1b3a73f9](https://linux-hardware.org/?probe=7d1b3a73f9) | Mar 05, 2023 |
| Gigabyte      | B85M-D3H                    | [9f5aaa2900](https://linux-hardware.org/?probe=9f5aaa2900) | Mar 04, 2023 |
| ASUSTek       | M5A78L-M LX                 | [0cd2798326](https://linux-hardware.org/?probe=0cd2798326) | Mar 03, 2023 |
| Gigabyte      | B85M-D3H                    | [b6128fb3e9](https://linux-hardware.org/?probe=b6128fb3e9) | Feb 28, 2023 |
| MSI           | A320M-A PRO MAX             | [64cf10c762](https://linux-hardware.org/?probe=64cf10c762) | Feb 26, 2023 |
| Gigabyte      | B85M-D3H                    | [b1a38edcc2](https://linux-hardware.org/?probe=b1a38edcc2) | Feb 25, 2023 |
| MSI           | A320M-A PRO MAX             | [24b1205b0c](https://linux-hardware.org/?probe=24b1205b0c) | Feb 24, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [1029c7f3bb](https://linux-hardware.org/?probe=1029c7f3bb) | Feb 17, 2023 |
| ASUSTek       | PRIME B360M-C               | [d380600b31](https://linux-hardware.org/?probe=d380600b31) | Feb 15, 2023 |
| Gigabyte      | B85M-D3H                    | [ba06eb3e9c](https://linux-hardware.org/?probe=ba06eb3e9c) | Feb 11, 2023 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | [14bde69d96](https://linux-hardware.org/?probe=14bde69d96) | Feb 10, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [190a780b8a](https://linux-hardware.org/?probe=190a780b8a) | Jan 29, 2023 |
| Gigabyte      | B550 GAMING X V2            | [4f24524e7d](https://linux-hardware.org/?probe=4f24524e7d) | Jan 19, 2023 |
| Gigabyte      | H510M H                     | [e8cc3131fc](https://linux-hardware.org/?probe=e8cc3131fc) | Jan 15, 2023 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [d92a983612](https://linux-hardware.org/?probe=d92a983612) | Jan 12, 2023 |
| Gigabyte      | B85M-D3H                    | [e83827b548](https://linux-hardware.org/?probe=e83827b548) | Jan 11, 2023 |
| Gigabyte      | B85M-D3H                    | [0e81ffb471](https://linux-hardware.org/?probe=0e81ffb471) | Jan 11, 2023 |
| HP            | ProLiant MicroServer        | [4bdffcda7f](https://linux-hardware.org/?probe=4bdffcda7f) | Jan 07, 2023 |
| HP            | ProLiant ML350p Gen8        | [8a7807ff8c](https://linux-hardware.org/?probe=8a7807ff8c) | Jan 03, 2023 |
| HP            | ProLiant ML350p Gen8        | [1b66a8a1a8](https://linux-hardware.org/?probe=1b66a8a1a8) | Jan 02, 2023 |
| ASUSTek       | M5A78L-M LX                 | [b0f7933824](https://linux-hardware.org/?probe=b0f7933824) | Dec 29, 2022 |
| ASUSTek       | H110M-K                     | [4dab06b05f](https://linux-hardware.org/?probe=4dab06b05f) | Dec 29, 2022 |
| Gigabyte      | B85M-D3H                    | [4283e3bb1e](https://linux-hardware.org/?probe=4283e3bb1e) | Dec 27, 2022 |
| Dell          | 0J1C3P A00                  | [b65b20a073](https://linux-hardware.org/?probe=b65b20a073) | Dec 22, 2022 |
| ASUSTek       | P8Z77-V PRO                 | [2ad8b45619](https://linux-hardware.org/?probe=2ad8b45619) | Dec 21, 2022 |
| ASUSTek       | P8Z77-V PRO                 | [0e53e0be48](https://linux-hardware.org/?probe=0e53e0be48) | Dec 21, 2022 |
| ASRock        | B550M-ITX/ac                | [21a91196b1](https://linux-hardware.org/?probe=21a91196b1) | Dec 19, 2022 |
| ASUSTek       | PRIME Z590-P WIFI           | [34ac0b3211](https://linux-hardware.org/?probe=34ac0b3211) | Dec 17, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [ac15fdcc8b](https://linux-hardware.org/?probe=ac15fdcc8b) | Dec 16, 2022 |
| HP            | 2215                        | [78151a5e1b](https://linux-hardware.org/?probe=78151a5e1b) | Dec 16, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [976923f807](https://linux-hardware.org/?probe=976923f807) | Dec 12, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | [7ae8aecc25](https://linux-hardware.org/?probe=7ae8aecc25) | Dec 08, 2022 |
| ASRock        | B550M-ITX/ac                | [1d97601be2](https://linux-hardware.org/?probe=1d97601be2) | Dec 08, 2022 |
| ASRock        | B550M-ITX/ac                | [4943e0aa12](https://linux-hardware.org/?probe=4943e0aa12) | Dec 08, 2022 |
| ASUSTek       | P7P55 LX                    | [be0753651f](https://linux-hardware.org/?probe=be0753651f) | Dec 07, 2022 |
| ASRock        | 990FX Extreme3              | [84b8daa5c4](https://linux-hardware.org/?probe=84b8daa5c4) | Nov 20, 2022 |
| HP            | 1998                        | [f9746a4ae0](https://linux-hardware.org/?probe=f9746a4ae0) | Nov 15, 2022 |
| MSI           | B75A-IE35                   | [57b74e4ca2](https://linux-hardware.org/?probe=57b74e4ca2) | Nov 01, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [91bf754e64](https://linux-hardware.org/?probe=91bf754e64) | Oct 24, 2022 |
| ASRock        | Z77 Extreme4                | [7d12ed56e5](https://linux-hardware.org/?probe=7d12ed56e5) | Oct 19, 2022 |
| Gigabyte      | B450M DS3H-CF               | [6e45f7ecd7](https://linux-hardware.org/?probe=6e45f7ecd7) | Oct 15, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | [d1a5c91196](https://linux-hardware.org/?probe=d1a5c91196) | Oct 14, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | [b69b373cc1](https://linux-hardware.org/?probe=b69b373cc1) | Oct 14, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [175ebd8462](https://linux-hardware.org/?probe=175ebd8462) | Oct 14, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [1ba5f65f98](https://linux-hardware.org/?probe=1ba5f65f98) | Oct 10, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [41dd35ae5f](https://linux-hardware.org/?probe=41dd35ae5f) | Oct 10, 2022 |
| ASUSTek       | M5A78L LE                   | [69023fe30e](https://linux-hardware.org/?probe=69023fe30e) | Oct 09, 2022 |
| Lenovo        | T530-28ICB                  | [b87998cf32](https://linux-hardware.org/?probe=b87998cf32) | Oct 09, 2022 |
| MSI           | B550-A PRO                  | [be6a0fda35](https://linux-hardware.org/?probe=be6a0fda35) | Oct 08, 2022 |
| Lenovo        | T530-28ICB                  | [175a71260e](https://linux-hardware.org/?probe=175a71260e) | Oct 06, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [85eb59fc6d](https://linux-hardware.org/?probe=85eb59fc6d) | Oct 05, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | [cb5d0d1945](https://linux-hardware.org/?probe=cb5d0d1945) | Oct 01, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | [3af0c5cc5f](https://linux-hardware.org/?probe=3af0c5cc5f) | Oct 01, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [db15c7b708](https://linux-hardware.org/?probe=db15c7b708) | Oct 01, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [608c715bab](https://linux-hardware.org/?probe=608c715bab) | Sep 26, 2022 |
| MSI           | H81M-P33                    | [108817dc0f](https://linux-hardware.org/?probe=108817dc0f) | Sep 21, 2022 |
| ASRock        | HM55-HT                     | [64fff8f065](https://linux-hardware.org/?probe=64fff8f065) | Sep 20, 2022 |
| MSI           | 870-G45                     | [74af87b0c5](https://linux-hardware.org/?probe=74af87b0c5) | Sep 17, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [081d4b1d50](https://linux-hardware.org/?probe=081d4b1d50) | Sep 16, 2022 |
| ASUSTek       | M2A74-AM                    | [25c30e4e54](https://linux-hardware.org/?probe=25c30e4e54) | Sep 14, 2022 |
| ASUSTek       | M2A74-AM                    | [24e6ffe552](https://linux-hardware.org/?probe=24e6ffe552) | Sep 14, 2022 |
| ASUSTek       | P7P55 LX                    | [cc28ed218f](https://linux-hardware.org/?probe=cc28ed218f) | Sep 13, 2022 |
| Acer          | Aspire X3950                | [22d1319220](https://linux-hardware.org/?probe=22d1319220) | Sep 06, 2022 |
| ASUSTek       | P5GZ-MX                     | [883739db23](https://linux-hardware.org/?probe=883739db23) | Sep 05, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [f16d383b65](https://linux-hardware.org/?probe=f16d383b65) | Sep 05, 2022 |
| HP            | 2ADC                        | [d9e5d2b511](https://linux-hardware.org/?probe=d9e5d2b511) | Sep 04, 2022 |
| HP            | 18E4                        | [c58c0043cb](https://linux-hardware.org/?probe=c58c0043cb) | Sep 03, 2022 |
| HP            | 3397                        | [5cd2349a9c](https://linux-hardware.org/?probe=5cd2349a9c) | Sep 02, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | [2be9b66ba1](https://linux-hardware.org/?probe=2be9b66ba1) | Aug 30, 2022 |
| AZW           | GK55                        | [0ae52e1fdf](https://linux-hardware.org/?probe=0ae52e1fdf) | Aug 21, 2022 |
| MSI           | H170M PRO-VDH               | [4d7aa09763](https://linux-hardware.org/?probe=4d7aa09763) | Aug 16, 2022 |
| Dell          | 08NPPY A00                  | [1b78691cac](https://linux-hardware.org/?probe=1b78691cac) | Aug 14, 2022 |
| Dell          | 08NPPY A00                  | [b41823f392](https://linux-hardware.org/?probe=b41823f392) | Aug 14, 2022 |
| MSI           | MS-77311                    | [86b4d71bc0](https://linux-hardware.org/?probe=86b4d71bc0) | Aug 11, 2022 |
| HP            | 8433 11                     | [cd790281b5](https://linux-hardware.org/?probe=cd790281b5) | Aug 02, 2022 |
| Dell          | 0KWVT8 A03                  | [cdca6713e9](https://linux-hardware.org/?probe=cdca6713e9) | Jul 31, 2022 |
| Dell          | 0KWVT8 A03                  | [1444843fcd](https://linux-hardware.org/?probe=1444843fcd) | Jul 31, 2022 |
| MSI           | 2AE0                        | [5c0034d313](https://linux-hardware.org/?probe=5c0034d313) | Jul 22, 2022 |
| MSI           | 2AE0                        | [df441346da](https://linux-hardware.org/?probe=df441346da) | Jul 22, 2022 |
| Medion        | MS-7797                     | [caf13d5392](https://linux-hardware.org/?probe=caf13d5392) | Jul 14, 2022 |
| Dell          | 0GM819                      | [3d18cc2632](https://linux-hardware.org/?probe=3d18cc2632) | Jul 08, 2022 |
| Gigabyte      | Z87-HD3                     | [95e6ec0822](https://linux-hardware.org/?probe=95e6ec0822) | Jul 05, 2022 |
| HP            | 3646h                       | [9e0737f23f](https://linux-hardware.org/?probe=9e0737f23f) | Jul 04, 2022 |
| Gigabyte      | Z87-HD3                     | [28429fdd32](https://linux-hardware.org/?probe=28429fdd32) | Jul 02, 2022 |
| HP            | 8169                        | [18c6ea7678](https://linux-hardware.org/?probe=18c6ea7678) | Jul 01, 2022 |
| HP            | 8169                        | [c479baadc1](https://linux-hardware.org/?probe=c479baadc1) | Jul 01, 2022 |
| Acer          | Aspire X3950                | [81797815d2](https://linux-hardware.org/?probe=81797815d2) | Jun 13, 2022 |
| Unknown       | Unknown                     | [c62add2d70](https://linux-hardware.org/?probe=c62add2d70) | Jun 13, 2022 |
| HP            | 3397                        | [55bcbdbc1f](https://linux-hardware.org/?probe=55bcbdbc1f) | Jun 07, 2022 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | [5407d4a1f6](https://linux-hardware.org/?probe=5407d4a1f6) | Jun 07, 2022 |
| ASUSTek       | P5G41T-M LX2/BR             | [9044b2e4e2](https://linux-hardware.org/?probe=9044b2e4e2) | May 18, 2022 |
| Unknown       | HX90                        | [3a7e2628b0](https://linux-hardware.org/?probe=3a7e2628b0) | May 09, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [246c63d834](https://linux-hardware.org/?probe=246c63d834) | May 06, 2022 |
| HP            | 8433 11                     | [a5b829538b](https://linux-hardware.org/?probe=a5b829538b) | Apr 29, 2022 |
| Gigabyte      | X99P-SLI-CF                 | [19055b80bc](https://linux-hardware.org/?probe=19055b80bc) | Apr 16, 2022 |
| ASUSTek       | PRIME H410M-A               | [9352c21f95](https://linux-hardware.org/?probe=9352c21f95) | Mar 17, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [4368bd67ac](https://linux-hardware.org/?probe=4368bd67ac) | Nov 23, 2021 |
| ASUSTek       | PRIME B550-PLUS             | [686454975b](https://linux-hardware.org/?probe=686454975b) | Nov 23, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | [36ac197007](https://linux-hardware.org/?probe=36ac197007) | Nov 17, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Desktops | Percent |
|----------------------|----------|---------|
| 5.15.0-56-generic    | 13       | 11.4%   |
| 5.15.0-47-generic    | 11       | 9.65%   |
| 5.15.0-48-generic    | 7        | 6.14%   |
| 5.15.0-67-generic    | 6        | 5.26%   |
| 5.15.0-60-generic    | 6        | 5.26%   |
| 5.15.0-50-generic    | 5        | 4.39%   |
| 5.19.0-32-generic    | 4        | 3.51%   |
| 5.15.0-76-generic    | 4        | 3.51%   |
| 5.15.0-52-generic    | 4        | 3.51%   |
| 5.19.0-38-generic    | 3        | 2.63%   |
| 5.15.0-46-generic    | 3        | 2.63%   |
| 5.15.0-40-generic    | 3        | 2.63%   |
| 5.15.0-27-generic    | 3        | 2.63%   |
| 5.15.0-25-generic    | 3        | 2.63%   |
| 6.2.0-26-generic     | 2        | 1.75%   |
| 5.19.0-35-generic    | 2        | 1.75%   |
| 5.15.0-71-generic    | 2        | 1.75%   |
| 5.15.0-70-generic    | 2        | 1.75%   |
| 5.15.0-69-generic    | 2        | 1.75%   |
| 5.15.0-58-generic    | 2        | 1.75%   |
| 5.15.0-57-generic    | 2        | 1.75%   |
| 5.15.0-41-generic    | 2        | 1.75%   |
| 5.15.0-37-generic    | 2        | 1.75%   |
| 6.4.0-060400-generic | 1        | 0.88%   |
| 5.19.0-50-generic    | 1        | 0.88%   |
| 5.19.0-43-generic    | 1        | 0.88%   |
| 5.19.0-42-generic    | 1        | 0.88%   |
| 5.19.0-41-generic    | 1        | 0.88%   |
| 5.19.0-40-generic    | 1        | 0.88%   |
| 5.19.0-37-generic    | 1        | 0.88%   |
| 5.18.0-1-generic     | 1        | 0.88%   |
| 5.15.0-75-generic    | 1        | 0.88%   |
| 5.15.0-73-generic    | 1        | 0.88%   |
| 5.15.0-58-lowlatency | 1        | 0.88%   |
| 5.15.0-56-lowlatency | 1        | 0.88%   |
| 5.15.0-43-generic    | 1        | 0.88%   |
| 5.15.0-39-generic    | 1        | 0.88%   |
| 5.15.0-35-generic    | 1        | 0.88%   |
| 5.15.0-30-generic    | 1        | 0.88%   |
| 5.15.0-22-generic    | 1        | 0.88%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 80       | 78.43%  |
| 5.19.0  | 15       | 14.71%  |
| 6.2.0   | 2        | 1.96%   |
| 5.13.0  | 2        | 1.96%   |
| 6.4.0   | 1        | 0.98%   |
| 5.18.0  | 1        | 0.98%   |
| 5.14.0  | 1        | 0.98%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 80       | 78.43%  |
| 5.19    | 15       | 14.71%  |
| 6.2     | 2        | 1.96%   |
| 5.13    | 2        | 1.96%   |
| 6.4     | 1        | 0.98%   |
| 5.18    | 1        | 0.98%   |
| 5.14    | 1        | 0.98%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 100      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| MATE   | 97       | 97%     |
| KDE5   | 1        | 1%      |
| GNOME  | 1        | 1%      |
| Budgie | 1        | 1%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 94       | 94%     |
| Wayland | 3        | 3%      |
| Tty     | 3        | 3%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 81       | 79.41%  |
| GDM3    | 11       | 10.78%  |
| Unknown | 10       | 9.8%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 35       | 35%     |
| fr_FR | 14       | 14%     |
| de_DE | 10       | 10%     |
| it_IT | 8        | 8%      |
| en_AU | 4        | 4%      |
| pt_BR | 3        | 3%      |
| ru_RU | 2        | 2%      |
| hr_HR | 2        | 2%      |
| es_AR | 2        | 2%      |
| en_CA | 2        | 2%      |
| de_CH | 2        | 2%      |
| C     | 2        | 2%      |
| zh_TW | 1        | 1%      |
| nl_NL | 1        | 1%      |
| hu_HU | 1        | 1%      |
| fi_FI | 1        | 1%      |
| et_EE | 1        | 1%      |
| es_PE | 1        | 1%      |
| es_MX | 1        | 1%      |
| es_ES | 1        | 1%      |
| en_IL | 1        | 1%      |
| en_GB | 1        | 1%      |
| de_AT | 1        | 1%      |
| da_DK | 1        | 1%      |
| cs_CZ | 1        | 1%      |
| ar_KW | 1        | 1%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 61       | 59.8%   |
| EFI  | 41       | 40.2%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 85       | 83.33%  |
| Btrfs   | 5        | 4.9%    |
| Tmpfs   | 4        | 3.92%   |
| Overlay | 4        | 3.92%   |
| Xfs     | 2        | 1.96%   |
| Zfs     | 1        | 0.98%   |
| Ext2    | 1        | 0.98%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 67       | 65.69%  |
| Unknown | 22       | 21.57%  |
| MBR     | 13       | 12.75%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 80       | 79.21%  |
| Yes       | 21       | 20.79%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 63       | 62.38%  |
| Yes       | 38       | 37.62%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 29       | 29%     |
| Hewlett-Packard                      | 15       | 15%     |
| MSI                                  | 14       | 14%     |
| Gigabyte Technology                  | 10       | 10%     |
| ASRock                               | 7        | 7%      |
| Lenovo                               | 6        | 6%      |
| Dell                                 | 5        | 5%      |
| Unknown                              | 5        | 5%      |
| Acer                                 | 2        | 2%      |
| Shenzhen Meigao Electronic Equipment | 1        | 1%      |
| Medion                               | 1        | 1%      |
| MACHINIST                            | 1        | 1%      |
| CCE                                  | 1        | 1%      |
| Biostar                              | 1        | 1%      |
| AZW                                  | 1        | 1%      |
| AMI                                  | 1        | 1%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Unknown                                    | 5        | 5%      |
| HP EliteDesk 800 G1 SFF                    | 2        | 2%      |
| HP Compaq Elite 8300 SFF                   | 2        | 2%      |
| ASUS M5A78L LE                             | 2        | 2%      |
| Shenzhen Meigao Electronic Equipment HX90G | 1        | 1%      |
| MSI p6-2330                                | 1        | 1%      |
| MSI MS-7D43                                | 1        | 1%      |
| MSI MS-7C56                                | 1        | 1%      |
| MSI MS-7C52                                | 1        | 1%      |
| MSI MS-7C37                                | 1        | 1%      |
| MSI MS-7C09                                | 1        | 1%      |
| MSI MS-7C02                                | 1        | 1%      |
| MSI MS-7A33                                | 1        | 1%      |
| MSI MS-7982                                | 1        | 1%      |
| MSI MS-7918                                | 1        | 1%      |
| MSI MS-7817                                | 1        | 1%      |
| MSI MS-7758                                | 1        | 1%      |
| MSI MS-7599                                | 1        | 1%      |
| MSI B02311                                 | 1        | 1%      |
| Medion MS-7797                             | 1        | 1%      |
| MACHINIST E5 MR9A PRO MAX V1.1             | 1        | 1%      |
| Lenovo ThinkStation D20 4158GK1            | 1        | 1%      |
| Lenovo ThinkCentre neo 50t Gen 3 11SE      | 1        | 1%      |
| Lenovo ThinkCentre M710q 10MQSC0N00        | 1        | 1%      |
| Lenovo T530-28ICB                          | 1        | 1%      |
| Lenovo IdeaCentre 5 14IAB7 90T2000SUS      | 1        | 1%      |
| Lenovo H50-55 90BG000TFR                   | 1        | 1%      |
| HP ProLiant ML350p Gen8                    | 1        | 1%      |
| HP ProLiant MicroServer                    | 1        | 1%      |
| HP ProDesk 600 G2 DM                       | 1        | 1%      |
| HP Pavilion 590-p0049 3LC38AA              | 1        | 1%      |
| HP EliteDesk 800 G1 TWR                    | 1        | 1%      |
| HP EliteDesk 705 G1 SFF                    | 1        | 1%      |
| HP Desktop M01-F0xxx                       | 1        | 1%      |
| HP Compaq Pro 6300 MT                      | 1        | 1%      |
| HP Compaq 8200 Elite CMT PC                | 1        | 1%      |
| HP Compaq 8000 Elite SFF PC                | 1        | 1%      |
| HP 23-d027c                                | 1        | 1%      |
| Gigabyte Z87-HD3                           | 1        | 1%      |
| Gigabyte X99P-SLI-CF                       | 1        | 1%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS PRIME                                 | 7        | 7%      |
| HP Compaq                                  | 5        | 5%      |
| Unknown                                    | 5        | 5%      |
| HP EliteDesk                               | 4        | 4%      |
| ASUS ROG                                   | 4        | 4%      |
| Dell OptiPlex                              | 3        | 3%      |
| Lenovo ThinkCentre                         | 2        | 2%      |
| HP ProLiant                                | 2        | 2%      |
| ASUS M5A78L-M                              | 2        | 2%      |
| ASUS M5A78L                                | 2        | 2%      |
| Acer Aspire                                | 2        | 2%      |
| Shenzhen Meigao Electronic Equipment HX90G | 1        | 1%      |
| MSI p6-2330                                | 1        | 1%      |
| MSI MS-7D43                                | 1        | 1%      |
| MSI MS-7C56                                | 1        | 1%      |
| MSI MS-7C52                                | 1        | 1%      |
| MSI MS-7C37                                | 1        | 1%      |
| MSI MS-7C09                                | 1        | 1%      |
| MSI MS-7C02                                | 1        | 1%      |
| MSI MS-7A33                                | 1        | 1%      |
| MSI MS-7982                                | 1        | 1%      |
| MSI MS-7918                                | 1        | 1%      |
| MSI MS-7817                                | 1        | 1%      |
| MSI MS-7758                                | 1        | 1%      |
| MSI MS-7599                                | 1        | 1%      |
| MSI B02311                                 | 1        | 1%      |
| Medion MS-7797                             | 1        | 1%      |
| MACHINIST E5                               | 1        | 1%      |
| Lenovo ThinkStation                        | 1        | 1%      |
| Lenovo T530-28ICB                          | 1        | 1%      |
| Lenovo IdeaCentre                          | 1        | 1%      |
| Lenovo H50-55                              | 1        | 1%      |
| HP ProDesk                                 | 1        | 1%      |
| HP Pavilion                                | 1        | 1%      |
| HP Desktop                                 | 1        | 1%      |
| HP 23-d027c                                | 1        | 1%      |
| Gigabyte Z87-HD3                           | 1        | 1%      |
| Gigabyte X99P-SLI-CF                       | 1        | 1%      |
| Gigabyte P55-UD3                           | 1        | 1%      |
| Gigabyte H510M                             | 1        | 1%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 11       | 11%     |
| 2021 | 10       | 10%     |
| 2018 | 10       | 10%     |
| 2013 | 10       | 10%     |
| 2011 | 8        | 8%      |
| 2022 | 6        | 6%      |
| 2020 | 6        | 6%      |
| 2019 | 6        | 6%      |
| 2017 | 6        | 6%      |
| 2015 | 5        | 5%      |
| 2014 | 5        | 5%      |
| 2010 | 5        | 5%      |
| 2009 | 5        | 5%      |
| 2016 | 3        | 3%      |
| 2023 | 1        | 1%      |
| 2008 | 1        | 1%      |
| 2007 | 1        | 1%      |
| 2006 | 1        | 1%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 100      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 94       | 94%     |
| Enabled  | 6        | 6%      |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 100      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 20       | 20%     |
| 32.01-64.0  | 19       | 19%     |
| 16.01-24.0  | 18       | 18%     |
| 4.01-8.0    | 15       | 15%     |
| 3.01-4.0    | 15       | 15%     |
| 64.01-256.0 | 7        | 7%      |
| 24.01-32.0  | 4        | 4%      |
| 2.01-3.0    | 1        | 1%      |
| 1.01-2.0    | 1        | 1%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 36       | 34.62%  |
| 1.01-2.0   | 31       | 29.81%  |
| 4.01-8.0   | 18       | 17.31%  |
| 3.01-4.0   | 8        | 7.69%   |
| 8.01-16.0  | 8        | 7.69%   |
| 0.51-1.0   | 2        | 1.92%   |
| 24.01-32.0 | 1        | 0.96%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 36       | 36%     |
| 2      | 25       | 25%     |
| 3      | 16       | 16%     |
| 4      | 11       | 11%     |
| 6      | 5        | 5%      |
| 5      | 2        | 2%      |
| 0      | 2        | 2%      |
| 20     | 1        | 1%      |
| 8      | 1        | 1%      |
| 7      | 1        | 1%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 57       | 57%     |
| No        | 43       | 43%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 100      | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 54       | 54%     |
| Yes       | 46       | 46%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 69       | 69%     |
| Yes       | 31       | 31%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 15       | 15%     |
| France       | 13       | 13%     |
| Germany      | 10       | 10%     |
| Italy        | 9        | 9%      |
| Brazil       | 5        | 5%      |
| Australia    | 4        | 4%      |
| Portugal     | 3        | 3%      |
| Croatia      | 3        | 3%      |
| Canada       | 3        | 3%      |
| Austria      | 3        | 3%      |
| Switzerland  | 2        | 2%      |
| Russia       | 2        | 2%      |
| Poland       | 2        | 2%      |
| Hungary      | 2        | 2%      |
| Finland      | 2        | 2%      |
| Denmark      | 2        | 2%      |
| Belgium      | 2        | 2%      |
| Argentina    | 2        | 2%      |
| Ukraine      | 1        | 1%      |
| UK           | 1        | 1%      |
| Taiwan       | 1        | 1%      |
| Spain        | 1        | 1%      |
| Saudi Arabia | 1        | 1%      |
| Peru         | 1        | 1%      |
| New Zealand  | 1        | 1%      |
| Netherlands  | 1        | 1%      |
| Morocco      | 1        | 1%      |
| Moldova      | 1        | 1%      |
| Mexico       | 1        | 1%      |
| Israel       | 1        | 1%      |
| Isle of Man  | 1        | 1%      |
| Greece       | 1        | 1%      |
| Estonia      | 1        | 1%      |
| Czechia      | 1        | 1%      |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Zagreb           | 2        | 1.89%   |
| Rome             | 2        | 1.89%   |
| Melbourne        | 2        | 1.89%   |
| Lansdale         | 2        | 1.89%   |
| Zottegem         | 1        | 0.94%   |
| York             | 1        | 0.94%   |
| Wuelfrath        | 1        | 0.94%   |
| Wittingen        | 1        | 0.94%   |
| Whanganui        | 1        | 0.94%   |
| Washington       | 1        | 0.94%   |
| Warsaw           | 1        | 0.94%   |
| Villefontaine    | 1        | 0.94%   |
| Viljandi         | 1        | 0.94%   |
| Viana do Castelo | 1        | 0.94%   |
| Versailles       | 1        | 0.94%   |
| Velyki Mosty     | 1        | 0.94%   |
| Vancouver        | 1        | 0.94%   |
| Uberaba          | 1        | 0.94%   |
| Turku            | 1        | 0.94%   |
| Toulon           | 1        | 0.94%   |
| Torring          | 1        | 0.94%   |
| Tighina          | 1        | 0.94%   |
| Terrace          | 1        | 0.94%   |
| Tel Aviv         | 1        | 0.94%   |
| Taranto          | 1        | 0.94%   |
| Talence          | 1        | 0.94%   |
| St Petersburg    | 1        | 0.94%   |
| Split            | 1        | 0.94%   |
| Seia             | 1        | 0.94%   |
| Schmelz          | 1        | 0.94%   |
| Samara           | 1        | 0.94%   |
| Saint-Etienne    | 1        | 0.94%   |
| Saint Paul       | 1        | 0.94%   |
| Rochester        | 1        | 0.94%   |
| Rio Bonito       | 1        | 0.94%   |
| Pocking          | 1        | 0.94%   |
| Pindamonhangaba  | 1        | 0.94%   |
| Perth            | 1        | 0.94%   |
| Paris            | 1        | 0.94%   |
| Palermo          | 1        | 0.94%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 35       | 56     | 20%     |
| Seagate             | 31       | 57     | 17.71%  |
| Samsung Electronics | 27       | 53     | 15.43%  |
| Kingston            | 11       | 15     | 6.29%   |
| Crucial             | 11       | 15     | 6.29%   |
| Sandisk             | 8        | 11     | 4.57%   |
| Toshiba             | 6        | 30     | 3.43%   |
| Hitachi             | 5        | 6      | 2.86%   |
| Unknown             | 4        | 7      | 2.29%   |
| A-DATA Technology   | 4        | 4      | 2.29%   |
| Phison Electronics  | 3        | 3      | 1.71%   |
| Phison              | 3        | 3      | 1.71%   |
| SPCC                | 2        | 4      | 1.14%   |
| China               | 2        | 2      | 1.14%   |
| Transcend           | 1        | 5      | 0.57%   |
| Team                | 1        | 1      | 0.57%   |
| SK hynix            | 1        | 1      | 0.57%   |
| RZX                 | 1        | 1      | 0.57%   |
| PNY                 | 1        | 1      | 0.57%   |
| Pichau              | 1        | 1      | 0.57%   |
| OCZ                 | 1        | 1      | 0.57%   |
| NGFF                | 1        | 1      | 0.57%   |
| Maxtor              | 1        | 1      | 0.57%   |
| LDLC                | 1        | 1      | 0.57%   |
| KIOXIA-EXCERIA      | 1        | 1      | 0.57%   |
| KingSpec            | 1        | 1      | 0.57%   |
| KingFast            | 1        | 1      | 0.57%   |
| Kimtigo             | 1        | 1      | 0.57%   |
| KESU                | 1        | 1      | 0.57%   |
| Intenso             | 1        | 1      | 0.57%   |
| Hewlett-Packard     | 1        | 2      | 0.57%   |
| GOODRAM             | 1        | 1      | 0.57%   |
| DAS                 | 1        | 6      | 0.57%   |
| Corsair             | 1        | 1      | 0.57%   |
| BAITITON            | 1        | 1      | 0.57%   |
| Apacer              | 1        | 1      | 0.57%   |
| Unknown             | 1        | 1      | 0.57%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB                     | 5        | 2.34%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 4        | 1.87%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 3        | 1.4%    |
| Seagate ST2000DM008-2FR102 2TB                      | 3        | 1.4%    |
| Seagate ST2000DM001-1ER164 2TB                      | 3        | 1.4%    |
| Seagate ST1000DM003-1ER162 1TB                      | 3        | 1.4%    |
| Samsung SSD 870 QVO 1TB                             | 3        | 1.4%    |
| Kingston SA400S37120G 120GB SSD                     | 3        | 1.4%    |
| WDC WD5000AAKX-00ERMA0 500GB                        | 2        | 0.93%   |
| WDC WD40EZAZ-00SF3B0 4TB                            | 2        | 0.93%   |
| WDC WD30EFRX-68EUZN0 3TB                            | 2        | 0.93%   |
| Unknown SD/MMC 2GB                                  | 2        | 0.93%   |
| Unknown M.S./M.S.Pro/HG 16GB                        | 2        | 0.93%   |
| Seagate ST4000DM004-2CV104 4TB                      | 2        | 0.93%   |
| Samsung SSD 870 QVO 2TB                             | 2        | 0.93%   |
| Samsung SSD 870 EVO 500GB                           | 2        | 0.93%   |
| Samsung SSD 860 QVO 1TB                             | 2        | 0.93%   |
| Samsung SSD 840 Series 120GB                        | 2        | 0.93%   |
| Samsung NVMe SSD Drive 1TB                          | 2        | 0.93%   |
| Crucial CT240BX500SSD1 240GB                        | 2        | 0.93%   |
| Crucial CT2000MX500SSD1 2TB                         | 2        | 0.93%   |
| Crucial CT1000BX500SSD1 1TB                         | 2        | 0.93%   |
| A-DATA SU800 256GB SSD                              | 2        | 0.93%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1        | 0.47%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                      | 1        | 0.47%   |
| WDC WDBNCE0010PNC 1TB SSD                           | 1        | 0.47%   |
| WDC WD8001FZBX-00ASYA0 8TB                          | 1        | 0.47%   |
| WDC WD6400AAKS-00E4A0 640GB                         | 1        | 0.47%   |
| WDC WD60 EFAX-68JH4N1 6TB                           | 1        | 0.47%   |
| WDC WD5003AZEX-00K1GA0 500GB                        | 1        | 0.47%   |
| WDC WD5001AALS-00J7B1 500GB                         | 1        | 0.47%   |
| WDC WD5000AZRX-00A8LB0 500GB                        | 1        | 0.47%   |
| WDC WD5000AZLX-75K2TA0 500GB                        | 1        | 0.47%   |
| WDC WD5000AAKX-08ERMA0 500GB                        | 1        | 0.47%   |
| WDC WD5000AAKX-083CA1 500GB                         | 1        | 0.47%   |
| WDC WD5000AAKX-003CA0 500GB                         | 1        | 0.47%   |
| WDC WD5000AAKS-65TMA0 500GB                         | 1        | 0.47%   |
| WDC WD5000AAKS-00A7B0 500GB                         | 1        | 0.47%   |
| WDC WD5000AADS-00S9B0 500GB                         | 1        | 0.47%   |
| WDC WD40EZRZ-22GXCB0 4TB                            | 1        | 0.47%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 33       | 52     | 40.24%  |
| Seagate             | 31       | 57     | 37.8%   |
| Toshiba             | 6        | 30     | 7.32%   |
| Hitachi             | 5        | 6      | 6.1%    |
| Samsung Electronics | 3        | 8      | 3.66%   |
| Maxtor              | 1        | 1      | 1.22%   |
| KESU                | 1        | 1      | 1.22%   |
| Hewlett-Packard     | 1        | 2      | 1.22%   |
| DAS                 | 1        | 6      | 1.22%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 19       | 30     | 28.36%  |
| Crucial             | 10       | 14     | 14.93%  |
| Kingston            | 8        | 12     | 11.94%  |
| SanDisk             | 4        | 6      | 5.97%   |
| WDC                 | 3        | 3      | 4.48%   |
| A-DATA Technology   | 3        | 3      | 4.48%   |
| SPCC                | 2        | 4      | 2.99%   |
| China               | 2        | 2      | 2.99%   |
| Unknown             | 1        | 1      | 1.49%   |
| Transcend           | 1        | 5      | 1.49%   |
| Team                | 1        | 1      | 1.49%   |
| RZX                 | 1        | 1      | 1.49%   |
| PNY                 | 1        | 1      | 1.49%   |
| Pichau              | 1        | 1      | 1.49%   |
| OCZ                 | 1        | 1      | 1.49%   |
| NGFF                | 1        | 1      | 1.49%   |
| LDLC                | 1        | 1      | 1.49%   |
| KIOXIA-EXCERIA      | 1        | 1      | 1.49%   |
| KingSpec            | 1        | 1      | 1.49%   |
| KingFast            | 1        | 1      | 1.49%   |
| GOODRAM             | 1        | 1      | 1.49%   |
| BAITITON            | 1        | 1      | 1.49%   |
| Apacer              | 1        | 1      | 1.49%   |
| Unknown             | 1        | 1      | 1.49%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 66       | 163    | 43.14%  |
| SSD     | 57       | 94     | 37.25%  |
| NVMe    | 27       | 35     | 17.65%  |
| Unknown | 2        | 6      | 1.31%   |
| MMC     | 1        | 1      | 0.65%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 89       | 244    | 71.77%  |
| NVMe | 27       | 35     | 21.77%  |
| SAS  | 7        | 19     | 5.65%   |
| MMC  | 1        | 1      | 0.81%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 68       | 114    | 47.55%  |
| 0.51-1.0   | 38       | 73     | 26.57%  |
| 1.01-2.0   | 19       | 22     | 13.29%  |
| 3.01-4.0   | 10       | 12     | 6.99%   |
| 4.01-10.0  | 5        | 29     | 3.5%    |
| 2.01-3.0   | 3        | 7      | 2.1%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 24       | 23.53%  |
| 251-500        | 22       | 21.57%  |
| 501-1000       | 18       | 17.65%  |
| More than 3000 | 13       | 12.75%  |
| 1001-2000      | 10       | 9.8%    |
| 2001-3000      | 4        | 3.92%   |
| 1-20           | 4        | 3.92%   |
| 21-50          | 3        | 2.94%   |
| 51-100         | 2        | 1.96%   |
| Unknown        | 2        | 1.96%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 26       | 25.24%  |
| 101-250        | 15       | 14.56%  |
| 21-50          | 14       | 13.59%  |
| 51-100         | 11       | 10.68%  |
| 501-1000       | 10       | 9.71%   |
| More than 3000 | 8        | 7.77%   |
| 251-500        | 7        | 6.8%    |
| 1001-2000      | 7        | 6.8%    |
| 2001-3000      | 3        | 2.91%   |
| Unknown        | 2        | 1.94%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Desktops | Drives | Percent |
|-----------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB         | 2        | 2      | 14.29%  |
| WDC WD5000AADS-00S9B0 500GB             | 1        | 1      | 7.14%   |
| WDC WD10EAVS-00D7B0 1TB                 | 1        | 1      | 7.14%   |
| Seagate ST3250312AS 250GB               | 1        | 1      | 7.14%   |
| Seagate ST2000DM001-1ER164 2TB          | 1        | 1      | 7.14%   |
| Seagate ST1000DM003-1ER162 1TB          | 1        | 1      | 7.14%   |
| Samsung Electronics SSD 960 PRO 1TB     | 1        | 1      | 7.14%   |
| OCZ AGILITY3 240GB SSD                  | 1        | 1      | 7.14%   |
| NGFF 2280 256GB SSD                     | 1        | 1      | 7.14%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD | 1        | 1      | 7.14%   |
| Hitachi HTS721080G9SA00 80GB            | 1        | 1      | 7.14%   |
| DAS TerraMaster 500GB                   | 1        | 3      | 7.14%   |
| China SSD 180GB                         | 1        | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5        | 5      | 35.71%  |
| WDC                 | 2        | 2      | 14.29%  |
| Samsung Electronics | 1        | 1      | 7.14%   |
| OCZ                 | 1        | 1      | 7.14%   |
| NGFF                | 1        | 1      | 7.14%   |
| Kingston            | 1        | 1      | 7.14%   |
| Hitachi             | 1        | 1      | 7.14%   |
| DAS                 | 1        | 3      | 7.14%   |
| China               | 1        | 1      | 7.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 5        | 5      | 55.56%  |
| WDC     | 2        | 2      | 22.22%  |
| Hitachi | 1        | 1      | 11.11%  |
| DAS     | 1        | 3      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 8        | 11     | 61.54%  |
| SSD  | 4        | 4      | 30.77%  |
| NVMe | 1        | 1      | 7.69%   |

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
| Works    | 57       | 176    | 50.44%  |
| Detected | 43       | 107    | 38.05%  |
| Malfunc  | 13       | 16     | 11.5%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 61       | 44.85%  |
| AMD                         | 37       | 27.21%  |
| Samsung Electronics         | 10       | 7.35%   |
| Phison Electronics          | 7        | 5.15%   |
| SanDisk                     | 5        | 3.68%   |
| ASMedia Technology          | 5        | 3.68%   |
| Kingston Technology Company | 3        | 2.21%   |
| JMicron Technology          | 2        | 1.47%   |
| SK hynix                    | 1        | 0.74%   |
| Silicon Motion              | 1        | 0.74%   |
| Micron/Crucial Technology   | 1        | 0.74%   |
| Marvell Technology Group    | 1        | 0.74%   |
| Hewlett-Packard             | 1        | 0.74%   |
| ADATA Technology            | 1        | 0.74%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 21       | 12.14%  |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 10       | 5.78%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7        | 4.05%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 6        | 3.47%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 6        | 3.47%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 6        | 3.47%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 6        | 3.47%   |
| AMD 400 Series Chipset SATA Controller                                         | 6        | 3.47%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5        | 2.89%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 5        | 2.89%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 5        | 2.89%   |
| AMD 500 Series Chipset SATA Controller                                         | 4        | 2.31%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3        | 1.73%   |
| Intel SATA Controller [RAID mode]                                              | 3        | 1.73%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3        | 1.73%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 3        | 1.73%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 3        | 1.73%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3        | 1.73%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3        | 1.73%   |
| AMD 300 Series Chipset SATA Controller                                         | 3        | 1.73%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2        | 1.16%   |
| Phison PS5013 E13 NVMe Controller                                              | 2        | 1.16%   |
| Phison E8 PCIe3 NVMe Controller                                                | 2        | 1.16%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2        | 1.16%   |
| Kingston Company NVMe Controller                                               | 2        | 1.16%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2        | 1.16%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2        | 1.16%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 2        | 1.16%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]  | 2        | 1.16%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2        | 1.16%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 2        | 1.16%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 2        | 1.16%   |
| AMD X370 Series Chipset SATA Controller                                        | 2        | 1.16%   |
| AMD FCH SATA Controller D                                                      | 2        | 1.16%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 1        | 0.58%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 1        | 0.58%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1        | 0.58%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                             | 1        | 0.58%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1        | 0.58%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 1        | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 85       | 59.44%  |
| NVMe | 27       | 18.88%  |
| IDE  | 22       | 15.38%  |
| RAID | 9        | 6.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 63       | 63%     |
| AMD    | 37       | 37%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| AMD Ryzen 9 5900HX with Radeon Graphics       | 3        | 3%      |
| AMD Ryzen 5 2600 Six-Core Processor           | 3        | 3%      |
| Intel Core i7-8700K CPU @ 3.70GHz             | 2        | 2%      |
| Intel Core i7-4790 CPU @ 3.60GHz              | 2        | 2%      |
| Intel Core i5-3470 CPU @ 3.20GHz              | 2        | 2%      |
| Intel Core i5-2400 CPU @ 3.10GHz              | 2        | 2%      |
| Intel 11th Gen Core i5-11600K @ 3.90GHz       | 2        | 2%      |
| AMD Ryzen 5 3600 6-Core Processor             | 2        | 2%      |
| AMD Ryzen 5 2400G with Radeon Vega Graphics   | 2        | 2%      |
| AMD FX-6300 Six-Core Processor                | 2        | 2%      |
| AMD A8-9600 RADEON R7, 10 COMPUTE CORES 4C+6G | 2        | 2%      |
| Intel Xeon D-2796TE CPU @ 2.00GHz             | 1        | 1%      |
| Intel Xeon CPU E5620 @ 2.40GHz                | 1        | 1%      |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz           | 1        | 1%      |
| Intel Xeon CPU E5-2650 v3 @ 2.30GHz           | 1        | 1%      |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz            | 1        | 1%      |
| Intel Xeon CPU E3-1245 v3 @ 3.40GHz           | 1        | 1%      |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz   | 1        | 1%      |
| Intel Pentium CPU G4400 @ 3.30GHz             | 1        | 1%      |
| Intel Pentium CPU G3240 @ 3.10GHz             | 1        | 1%      |
| Intel Pentium CPU G3220 @ 3.00GHz             | 1        | 1%      |
| Intel Pentium CPU G2020 @ 2.90GHz             | 1        | 1%      |
| Intel Pentium 4 CPU 3.06GHz                   | 1        | 1%      |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1        | 1%      |
| Intel Core i7-6700K CPU @ 4.00GHz             | 1        | 1%      |
| Intel Core i7-4770K CPU @ 3.50GHz             | 1        | 1%      |
| Intel Core i7-3770K CPU @ 3.50GHz             | 1        | 1%      |
| Intel Core i5-9600K CPU @ 3.70GHz             | 1        | 1%      |
| Intel Core i5-9400F CPU @ 2.90GHz             | 1        | 1%      |
| Intel Core i5-8400 CPU @ 2.80GHz              | 1        | 1%      |
| Intel Core i5-7400T CPU @ 2.40GHz             | 1        | 1%      |
| Intel Core i5-6600 CPU @ 3.30GHz              | 1        | 1%      |
| Intel Core i5-6500T CPU @ 2.50GHz             | 1        | 1%      |
| Intel Core i5-6500 CPU @ 3.20GHz              | 1        | 1%      |
| Intel Core i5-6400 CPU @ 2.70GHz              | 1        | 1%      |
| Intel Core i5-4570 CPU @ 3.20GHz              | 1        | 1%      |
| Intel Core i5-4460 CPU @ 3.20GHz              | 1        | 1%      |
| Intel Core i5-3570 CPU @ 3.40GHz              | 1        | 1%      |
| Intel Core i5-3330S CPU @ 2.70GHz             | 1        | 1%      |
| Intel Core i5-2320 CPU @ 3.00GHz              | 1        | 1%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 19       | 19%     |
| AMD Ryzen 5             | 11       | 11%     |
| Other                   | 10       | 10%     |
| Intel Core i7           | 8        | 8%      |
| Intel Core i3           | 7        | 7%      |
| Intel Xeon              | 6        | 6%      |
| AMD FX                  | 5        | 5%      |
| Intel Pentium           | 4        | 4%      |
| Intel Celeron           | 4        | 4%      |
| AMD Ryzen 9             | 3        | 3%      |
| AMD Ryzen 7             | 3        | 3%      |
| AMD A8                  | 3        | 3%      |
| Intel Core 2 Duo        | 2        | 2%      |
| AMD E                   | 2        | 2%      |
| AMD Athlon II X2        | 2        | 2%      |
| Intel Pentium Dual-Core | 1        | 1%      |
| Intel Pentium 4         | 1        | 1%      |
| Intel Core 2 Quad       | 1        | 1%      |
| AMD Turion II Neo       | 1        | 1%      |
| AMD Ryzen 3             | 1        | 1%      |
| AMD Phenom II X6        | 1        | 1%      |
| AMD Athlon II X4        | 1        | 1%      |
| AMD Athlon              | 1        | 1%      |
| AMD A6                  | 1        | 1%      |
| AMD A4                  | 1        | 1%      |
| AMD A10                 | 1        | 1%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 32       | 32%     |
| 2      | 26       | 26%     |
| 6      | 19       | 19%     |
| 8      | 10       | 10%     |
| 3      | 3        | 3%      |
| 1      | 3        | 3%      |
| 12     | 2        | 2%      |
| 10     | 2        | 2%      |
| 20     | 1        | 1%      |
| 16     | 1        | 1%      |
| 14     | 1        | 1%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 98       | 98%     |
| 2      | 2        | 2%      |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 60       | 60%     |
| 1      | 40       | 40%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 100      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 44       | 43.56%  |
| 0x306c3    | 5        | 4.95%   |
| 0x206a7    | 5        | 4.95%   |
| 0xa0671    | 4        | 3.96%   |
| 0x506e3    | 4        | 3.96%   |
| 0x306a9    | 4        | 3.96%   |
| 0x906ea    | 3        | 2.97%   |
| 0x0a50000c | 3        | 2.97%   |
| 0x0800820d | 3        | 2.97%   |
| 0x20655    | 2        | 1.98%   |
| 0x08108109 | 2        | 1.98%   |
| 0x0600611a | 2        | 1.98%   |
| 0x06001119 | 2        | 1.98%   |
| 0x05000119 | 2        | 1.98%   |
| 0xa0653    | 1        | 0.99%   |
| 0x906ed    | 1        | 0.99%   |
| 0x90672    | 1        | 0.99%   |
| 0x706a1    | 1        | 0.99%   |
| 0x6fd      | 1        | 0.99%   |
| 0x606c1    | 1        | 0.99%   |
| 0x306f2    | 1        | 0.99%   |
| 0x206d7    | 1        | 0.99%   |
| 0x106e5    | 1        | 0.99%   |
| 0x10677    | 1        | 0.99%   |
| 0x0a50000d | 1        | 0.99%   |
| 0x06003106 | 1        | 0.99%   |
| 0x06000852 | 1        | 0.99%   |
| 0x0600063e | 1        | 0.99%   |
| 0x010000dc | 1        | 0.99%   |
| 0x010000c8 | 1        | 0.99%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 10       | 9.9%    |
| KabyLake         | 7        | 6.93%   |
| IvyBridge        | 7        | 6.93%   |
| Unknown          | 7        | 6.93%   |
| Zen+             | 6        | 5.94%   |
| Zen 3            | 6        | 5.94%   |
| Skylake          | 6        | 5.94%   |
| SandyBridge      | 6        | 5.94%   |
| Piledriver       | 5        | 4.95%   |
| K10              | 5        | 4.95%   |
| Zen              | 4        | 3.96%   |
| Westmere         | 4        | 3.96%   |
| Icelake          | 4        | 3.96%   |
| Zen 2            | 3        | 2.97%   |
| Penryn           | 3        | 2.97%   |
| Excavator        | 3        | 2.97%   |
| Goldmont plus    | 2        | 1.98%   |
| CometLake        | 2        | 1.98%   |
| Bulldozer        | 2        | 1.98%   |
| Bobcat           | 2        | 1.98%   |
| Tremont          | 1        | 0.99%   |
| Steamroller      | 1        | 0.99%   |
| NetBurst         | 1        | 0.99%   |
| Nehalem          | 1        | 0.99%   |
| Core             | 1        | 0.99%   |
| Broadwell        | 1        | 0.99%   |
| Alderlake Hybrid | 1        | 0.99%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 38       | 35.85%  |
| AMD                        | 35       | 33.02%  |
| Nvidia                     | 31       | 29.25%  |
| Matrox Electronics Systems | 1        | 0.94%   |
| ASPEED Technology          | 1        | 0.94%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5        | 4.63%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 5        | 4.63%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 4        | 3.7%    |
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 3.7%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 4        | 3.7%    |
| Intel HD Graphics 530                                                       | 4        | 3.7%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 4        | 3.7%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3        | 2.78%   |
| Nvidia GK208B [GeForce GT 730]                                              | 3        | 2.78%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 3        | 2.78%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3        | 2.78%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 2        | 1.85%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 2        | 1.85%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                   | 2        | 1.85%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 1.85%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.85%   |
| AMD Redwood PRO [Radeon HD 5550/5570/5630/6510/6610/7570]                   | 2        | 1.85%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2        | 1.85%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2        | 1.85%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 0.93%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 0.93%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 0.93%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 0.93%   |
| Nvidia GP107GL [Quadro P620]                                                | 1        | 0.93%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 0.93%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 0.93%   |
| Nvidia GM206GL [Quadro M2000]                                               | 1        | 0.93%   |
| Nvidia GM107GL [Quadro K620]                                                | 1        | 0.93%   |
| Nvidia GM107 [GeForce GTX 745]                                              | 1        | 0.93%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 0.93%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 1        | 0.93%   |
| Nvidia GK104 [GeForce GTX 680]                                              | 1        | 0.93%   |
| Nvidia GF119 [GeForce GT 520]                                               | 1        | 0.93%   |
| Nvidia GF106GL [Quadro 2000]                                                | 1        | 0.93%   |
| Nvidia GA106 [Geforce RTX 3050]                                             | 1        | 0.93%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                              | 1        | 0.93%   |
| Matrox Electronics Systems MGA G200EH                                       | 1        | 0.93%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller              | 1        | 0.93%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 0.93%   |
| Intel HD Graphics 630                                                       | 1        | 0.93%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 33       | 33%     |
| 1 x AMD        | 31       | 31%     |
| 1 x Nvidia     | 28       | 28%     |
| 2 x AMD        | 2        | 2%      |
| Intel + Nvidia | 2        | 2%      |
| 1 x Matrox     | 1        | 1%      |
| Intel + AMD    | 1        | 1%      |
| 1 x ASPEED     | 1        | 1%      |
| AMD + Nvidia   | 1        | 1%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 78       | 78%     |
| Proprietary | 20       | 20%     |
| Unknown     | 2        | 2%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 56       | 56%     |
| 0.51-1.0   | 11       | 11%     |
| 1.01-2.0   | 9        | 9%      |
| 0.01-0.5   | 8        | 8%      |
| 3.01-4.0   | 7        | 7%      |
| 7.01-8.0   | 4        | 4%      |
| 5.01-6.0   | 3        | 3%      |
| 2.01-3.0   | 1        | 1%      |
| 8.01-16.0  | 1        | 1%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 21       | 19.09%  |
| Goldstar             | 17       | 15.45%  |
| Philips              | 9        | 8.18%   |
| Hewlett-Packard      | 8        | 7.27%   |
| Dell                 | 8        | 7.27%   |
| Acer                 | 8        | 7.27%   |
| Iiyama               | 6        | 5.45%   |
| BenQ                 | 5        | 4.55%   |
| Ancor Communications | 4        | 3.64%   |
| ViewSonic            | 2        | 1.82%   |
| Sony                 | 2        | 1.82%   |
| Lenovo               | 2        | 1.82%   |
| Westinghouse         | 1        | 0.91%   |
| VMO                  | 1        | 0.91%   |
| Vizio                | 1        | 0.91%   |
| Vita                 | 1        | 0.91%   |
| SNC                  | 1        | 0.91%   |
| NEC Computers        | 1        | 0.91%   |
| Medion               | 1        | 0.91%   |
| Lenovo Group Limited | 1        | 0.91%   |
| Kogan                | 1        | 0.91%   |
| Insignia             | 1        | 0.91%   |
| Idek Iiyama          | 1        | 0.91%   |
| Gateway              | 1        | 0.91%   |
| Fujitsu Siemens      | 1        | 0.91%   |
| Envision Peripherals | 1        | 0.91%   |
| D&T                  | 1        | 0.91%   |
| CHR                  | 1        | 0.91%   |
| ASUSTek Computer     | 1        | 0.91%   |
| AOC                  | 1        | 0.91%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics S23B550 SAM0919 1920x1080 510x287mm 23.0-inch     | 2        | 1.77%   |
| Goldstar E2240 GSM57A3 1920x1080 477x268mm 21.5-inch                  | 2        | 1.77%   |
| Acer ET322QU ACR0687 2560x1440 698x393mm 31.5-inch                    | 2        | 1.77%   |
| Westinghouse DWM40F1D1 WDT7811 1920x1080 890x500mm 40.2-inch          | 1        | 0.88%   |
| VMO LCD WQXGA HDM VMO1506 2560x1600 1600x1000mm 74.3-inch             | 1        | 0.88%   |
| Vizio M470NV VIZ0063 1920x1080 1040x585mm 47.0-inch                   | 1        | 0.88%   |
| Vita LCD Monitor VIT0780 1920x1080                                    | 1        | 0.88%   |
| ViewSonic VA2431 Series VSCD824 1920x1080 521x293mm 23.5-inch         | 1        | 0.88%   |
| ViewSonic VA2046 SERIES VSC6D2E 1600x900 432x240mm 19.5-inch          | 1        | 0.88%   |
| Sony TV SNY3002 1920x1080 531x299mm 24.0-inch                         | 1        | 0.88%   |
| Sony LCD Monitor TV 3840x1080                                         | 1        | 0.88%   |
| Sony LCD Monitor TV                                                   | 1        | 0.88%   |
| SNC SKP_E20-32 SNC3200 1920x1080 477x268mm 21.5-inch                  | 1        | 0.88%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 1        | 0.88%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch  | 1        | 0.88%   |
| Samsung Electronics SyncMaster SAM0225 1440x900 410x257mm 19.1-inch   | 1        | 0.88%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch  | 1        | 0.88%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch    | 1        | 0.88%   |
| Samsung Electronics SA300/SA350 SAM078E 1920x1080 477x268mm 21.5-inch | 1        | 0.88%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch  | 1        | 0.88%   |
| Samsung Electronics S32F351 SAM0D24 1920x1080 698x393mm 31.5-inch     | 1        | 0.88%   |
| Samsung Electronics S27F358 SAM0D72 1920x1080 598x336mm 27.0-inch     | 1        | 0.88%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch     | 1        | 0.88%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1        | 0.88%   |
| Samsung Electronics S22E450 SAM0C79 1920x1080 477x268mm 21.5-inch     | 1        | 0.88%   |
| Samsung Electronics S19C301 SAM0B07 1366x768 410x230mm 18.5-inch      | 1        | 0.88%   |
| Samsung Electronics LCD Monitor SyncMaster 3840x1080                  | 1        | 0.88%   |
| Samsung Electronics LCD Monitor SAM0D4B 1366x768 609x347mm 27.6-inch  | 1        | 0.88%   |
| Samsung Electronics LCD Monitor SAM03D3 1360x768 410x256mm 19.0-inch  | 1        | 0.88%   |
| Samsung Electronics LCD Monitor S24E650 3840x1200                     | 1        | 0.88%   |
| Samsung Electronics LCD Monitor S24C650                               | 1        | 0.88%   |
| Samsung Electronics EPSON PJ SECA605 1600x1200                        | 1        | 0.88%   |
| Samsung Electronics C27F398 SAM0D44 1920x1080 598x336mm 27.0-inch     | 1        | 0.88%   |
| Philips PHL BDL3220QL PHLD230 1920x1080 698x393mm 31.5-inch           | 1        | 0.88%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch              | 1        | 0.88%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch               | 1        | 0.88%   |
| Philips PHL 272B8Q PHL0918 2560x1440 597x336mm 27.0-inch              | 1        | 0.88%   |
| Philips PHL 242E2F PHLC238 1920x1080 527x296mm 23.8-inch              | 1        | 0.88%   |
| Philips PHL 227E6 PHLC0E5 1920x1080 477x268mm 21.5-inch               | 1        | 0.88%   |
| Philips 246EL2SBH PHLC074 1920x1080 521x293mm 23.5-inch               | 1        | 0.88%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 54       | 54%     |
| 3840x2160 (4K)     | 6        | 6%      |
| 1280x1024 (SXGA)   | 6        | 6%      |
| 2560x1440 (QHD)    | 5        | 5%      |
| 1680x1050 (WSXGA+) | 5        | 5%      |
| 1366x768 (WXGA)    | 4        | 4%      |
| 3440x1440          | 3        | 3%      |
| 1440x900 (WXGA+)   | 3        | 3%      |
| Unknown            | 3        | 3%      |
| 3840x1080          | 2        | 2%      |
| 1360x768           | 2        | 2%      |
| 3840x1600          | 1        | 1%      |
| 3840x1200          | 1        | 1%      |
| 2560x1600          | 1        | 1%      |
| 2560x1080          | 1        | 1%      |
| 1920x1200 (WUXGA)  | 1        | 1%      |
| 1600x900 (HD+)     | 1        | 1%      |
| 1280x720 (HD)      | 1        | 1%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 18       | 17.14%  |
| 21      | 16       | 15.24%  |
| 23      | 14       | 13.33%  |
| 24      | 11       | 10.48%  |
| 31      | 8        | 7.62%   |
| 19      | 6        | 5.71%   |
| 17      | 6        | 5.71%   |
| Unknown | 6        | 5.71%   |
| 34      | 4        | 3.81%   |
| 22      | 3        | 2.86%   |
| 18      | 3        | 2.86%   |
| 38      | 2        | 1.9%    |
| 74      | 1        | 0.95%   |
| 72      | 1        | 0.95%   |
| 54      | 1        | 0.95%   |
| 46      | 1        | 0.95%   |
| 40      | 1        | 0.95%   |
| 26      | 1        | 0.95%   |
| 25      | 1        | 0.95%   |
| 15      | 1        | 0.95%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 38       | 37.25%  |
| 401-500     | 27       | 26.47%  |
| 601-700     | 12       | 11.76%  |
| 301-350     | 7        | 6.86%   |
| Unknown     | 6        | 5.88%   |
| 701-800     | 4        | 3.92%   |
| 801-900     | 3        | 2.94%   |
| 1501-2000   | 2        | 1.96%   |
| 1001-1500   | 2        | 1.96%   |
| 351-400     | 1        | 0.98%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 66       | 69.47%  |
| 16/10   | 13       | 13.68%  |
| 5/4     | 7        | 7.37%   |
| 21/9    | 5        | 5.26%   |
| Unknown | 4        | 4.21%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 34       | 33.66%  |
| 301-350        | 18       | 17.82%  |
| 351-500        | 12       | 11.88%  |
| 151-200        | 9        | 8.91%   |
| 141-150        | 9        | 8.91%   |
| Unknown        | 6        | 5.94%   |
| 251-300        | 5        | 4.95%   |
| 501-1000       | 4        | 3.96%   |
| More than 1000 | 3        | 2.97%   |
| 101-110        | 1        | 0.99%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 62       | 63.92%  |
| 101-120 | 21       | 21.65%  |
| Unknown | 6        | 6.19%   |
| 1-50    | 4        | 4.12%   |
| 121-160 | 4        | 4.12%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 75       | 73.53%  |
| 2     | 24       | 23.53%  |
| 0     | 3        | 2.94%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 67       | 48.2%   |
| Intel                           | 41       | 29.5%   |
| Broadcom                        | 8        | 5.76%   |
| Qualcomm Atheros                | 6        | 4.32%   |
| TP-Link                         | 3        | 2.16%   |
| Ralink                          | 3        | 2.16%   |
| MediaTek                        | 3        | 2.16%   |
| Xiaomi                          | 1        | 0.72%   |
| Qualcomm Atheros Communications | 1        | 0.72%   |
| NetXen Incorporated             | 1        | 0.72%   |
| NetGear                         | 1        | 0.72%   |
| Motorola PCS                    | 1        | 0.72%   |
| Marvell Technology Group        | 1        | 0.72%   |
| Broadcom Limited                | 1        | 0.72%   |
| ASUSTek Computer                | 1        | 0.72%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 52       | 33.33%  |
| Intel Ethernet Controller I225-V                                  | 8        | 5.13%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5        | 3.21%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5        | 3.21%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 2.56%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 3        | 1.92%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3        | 1.92%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 1.92%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 3        | 1.92%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2        | 1.28%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 2        | 1.28%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2        | 1.28%   |
| Intel Wireless 7265                                               | 2        | 1.28%   |
| Intel I211 Gigabit Network Connection                             | 2        | 1.28%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2        | 1.28%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 2        | 1.28%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.64%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1        | 0.64%   |
| TP-Link Archer T4U ver.3                                          | 1        | 0.64%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1        | 0.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.64%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.64%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1        | 0.64%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                            | 1        | 0.64%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1        | 0.64%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1        | 0.64%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1        | 0.64%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1        | 0.64%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.64%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1        | 0.64%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 0.64%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.64%   |
| Realtek 802.11ac NIC                                              | 1        | 0.64%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter            | 1        | 0.64%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1        | 0.64%   |
| Ralink RT2561/RT61 802.11g PCI                                    | 1        | 0.64%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 0.64%   |
| Qualcomm Atheros AR9271 802.11n                                   | 1        | 0.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1        | 0.64%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1        | 0.64%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 15       | 32.61%  |
| Intel                           | 15       | 32.61%  |
| TP-Link                         | 3        | 6.52%   |
| Ralink                          | 3        | 6.52%   |
| MediaTek                        | 3        | 6.52%   |
| Qualcomm Atheros                | 2        | 4.35%   |
| Broadcom                        | 2        | 4.35%   |
| Qualcomm Atheros Communications | 1        | 2.17%   |
| NetGear                         | 1        | 2.17%   |
| ASUSTek Computer                | 1        | 2.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 3        | 6.52%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 3        | 6.52%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 3        | 6.52%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2        | 4.35%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 2        | 4.35%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2        | 4.35%   |
| Intel Wireless 7265                                            | 2        | 4.35%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2        | 4.35%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1        | 2.17%   |
| TP-Link Archer T4U ver.3                                       | 1        | 2.17%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1        | 2.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1        | 2.17%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1        | 2.17%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1        | 2.17%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 1        | 2.17%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1        | 2.17%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1        | 2.17%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1        | 2.17%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1        | 2.17%   |
| Realtek 802.11ac NIC                                           | 1        | 2.17%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter         | 1        | 2.17%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1        | 2.17%   |
| Ralink RT2561/RT61 802.11g PCI                                 | 1        | 2.17%   |
| Qualcomm Atheros AR9271 802.11n                                | 1        | 2.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1        | 2.17%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1        | 2.17%   |
| NetGear A6150                                                  | 1        | 2.17%   |
| Intel Wireless 3165                                            | 1        | 2.17%   |
| Intel Wireless 3160                                            | 1        | 2.17%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1        | 2.17%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 1        | 2.17%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1        | 2.17%   |
| Broadcom Network controller                                    | 1        | 2.17%   |
| Broadcom BCM43142 802.11b/g/n                                  | 1        | 2.17%   |
| ASUS 802.11ac NIC                                              | 1        | 2.17%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 60       | 56.6%   |
| Intel                    | 31       | 29.25%  |
| Broadcom                 | 6        | 5.66%   |
| Qualcomm Atheros         | 4        | 3.77%   |
| Xiaomi                   | 1        | 0.94%   |
| NetXen Incorporated      | 1        | 0.94%   |
| Motorola PCS             | 1        | 0.94%   |
| Marvell Technology Group | 1        | 0.94%   |
| Broadcom Limited         | 1        | 0.94%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 52       | 47.27%  |
| Intel Ethernet Controller I225-V                                     | 8        | 7.27%   |
| Realtek RTL8125 2.5GbE Controller                                    | 5        | 4.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 5        | 4.55%   |
| Intel Ethernet Connection (2) I219-V                                 | 4        | 3.64%   |
| Intel Ethernet Connection I217-LM                                    | 3        | 2.73%   |
| Intel I211 Gigabit Network Connection                                | 2        | 1.82%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                      | 2        | 1.82%   |
| Xiaomi Mi/Redmi series (RNDIS)                                       | 1        | 0.91%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 1        | 0.91%   |
| Realtek RTL8152 Fast Ethernet Adapter                                | 1        | 0.91%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 1        | 0.91%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                | 1        | 0.91%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller            | 1        | 0.91%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                             | 1        | 0.91%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                        | 1        | 0.91%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                             | 1        | 0.91%   |
| NetXen Incorporated NX3031 Multifunction 1/10-Gigabit Server Adapter | 1        | 0.91%   |
| Motorola PCS XT1032                                                  | 1        | 0.91%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                    | 1        | 0.91%   |
| Intel I210 Gigabit Network Connection                                | 1        | 0.91%   |
| Intel Ethernet Controller I225-IT                                    | 1        | 0.91%   |
| Intel Ethernet Connection I217-V                                     | 1        | 0.91%   |
| Intel Ethernet Connection E823-C for SFP                             | 1        | 0.91%   |
| Intel Ethernet Connection (7) I219-V                                 | 1        | 0.91%   |
| Intel Ethernet Connection (2) I219-LM                                | 1        | 0.91%   |
| Intel Ethernet Connection (2) I218-V                                 | 1        | 0.91%   |
| Intel Ethernet Connection (17) I219-V                                | 1        | 0.91%   |
| Intel Ethernet Connection (17) I219-LM                               | 1        | 0.91%   |
| Intel 82579V Gigabit Network Connection                              | 1        | 0.91%   |
| Intel 82567LM-3 Gigabit Network Connection                           | 1        | 0.91%   |
| Intel 82566DM-2 Gigabit Network Connection                           | 1        | 0.91%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                     | 1        | 0.91%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express              | 1        | 0.91%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                     | 1        | 0.91%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                     | 1        | 0.91%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express      | 1        | 0.91%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 100      | 68.49%  |
| WiFi     | 46       | 31.51%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 83       | 82.18%  |
| WiFi     | 18       | 17.82%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 55       | 55%     |
| 2     | 39       | 39%     |
| 3     | 3        | 3%      |
| 6     | 1        | 1%      |
| 5     | 1        | 1%      |
| 4     | 1        | 1%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 74       | 73.27%  |
| Yes  | 27       | 26.73%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 12       | 38.71%  |
| Realtek Semiconductor   | 5        | 16.13%  |
| MediaTek                | 3        | 9.68%   |
| TP-Link                 | 2        | 6.45%   |
| Cambridge Silicon Radio | 2        | 6.45%   |
| Broadcom                | 2        | 6.45%   |
| Belkin Components       | 2        | 6.45%   |
| Ralink                  | 1        | 3.23%   |
| IMC Networks            | 1        | 3.23%   |
| ASUSTek Computer        | 1        | 3.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| MediaTek Wireless_Device                              | 3        | 9.68%   |
| Intel Bluetooth wireless interface                    | 3        | 9.68%   |
| Intel AX201 Bluetooth                                 | 3        | 9.68%   |
| TP-Link UB500 Adapter                                 | 2        | 6.45%   |
| Realtek RTL8723B Bluetooth                            | 2        | 6.45%   |
| Realtek  Bluetooth 4.2 Adapter                        | 2        | 6.45%   |
| Intel Wireless-AC 3168 Bluetooth                      | 2        | 6.45%   |
| Intel AX210 Bluetooth                                 | 2        | 6.45%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 2        | 6.45%   |
| Realtek Bluetooth Radio                               | 1        | 3.23%   |
| Ralink RT3290 Bluetooth                               | 1        | 3.23%   |
| Intel Bluetooth Device                                | 1        | 3.23%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 1        | 3.23%   |
| IMC Networks Bluetooth Radio                          | 1        | 3.23%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter      | 1        | 3.23%   |
| Broadcom BCM43142 Bluetooth 4.0                       | 1        | 3.23%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter | 1        | 3.23%   |
| Belkin Components F8T013 Bluetooth Adapter            | 1        | 3.23%   |
| ASUS Bluetooth Radio                                  | 1        | 3.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 59       | 36.65%  |
| AMD                       | 44       | 27.33%  |
| Nvidia                    | 31       | 19.25%  |
| C-Media Electronics       | 9        | 5.59%   |
| ASUSTek Computer          | 3        | 1.86%   |
| Generalplus Technology    | 2        | 1.24%   |
| TerraTec Electronic       | 1        | 0.62%   |
| SteelSeries ApS           | 1        | 0.62%   |
| Sennheiser Communications | 1        | 0.62%   |
| Kingston Technology       | 1        | 0.62%   |
| JMTek                     | 1        | 0.62%   |
| GN Netcom                 | 1        | 0.62%   |
| Focusrite-Novation        | 1        | 0.62%   |
| Creative Technology       | 1        | 0.62%   |
| Corsair                   | 1        | 0.62%   |
| Cambridge Silicon Radio   | 1        | 0.62%   |
| Best Buy                  | 1        | 0.62%   |
| Anlya.cn                  | 1        | 0.62%   |
| Alesis                    | 1        | 0.62%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                               | 10       | 5.15%   |
| AMD Family 17h/19h HD Audio Controller                                     | 10       | 5.15%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 9        | 4.64%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8        | 4.12%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 7        | 3.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6        | 3.09%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 6        | 3.09%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 6        | 3.09%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 5        | 2.58%   |
| Intel Alder Lake-S HD Audio Controller                                     | 5        | 2.58%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5        | 2.58%   |
| Nvidia GP108 High Definition Audio Controller                              | 4        | 2.06%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 2.06%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4        | 2.06%   |
| Intel 200 Series PCH HD Audio                                              | 4        | 2.06%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4        | 2.06%   |
| AMD FCH Azalia Controller                                                  | 4        | 2.06%   |
| Nvidia GP106 High Definition Audio Controller                              | 3        | 1.55%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 1.55%   |
| Intel Cannon Lake PCH cAVS                                                 | 3        | 1.55%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 3        | 1.55%   |
| ASUSTek Computer USB Audio                                                 | 3        | 1.55%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3        | 1.55%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 3        | 1.55%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3        | 1.55%   |
| AMD Kabini HDMI/DP Audio                                                   | 3        | 1.55%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 3        | 1.55%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3        | 1.55%   |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 1.03%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 1.03%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2        | 1.03%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2        | 1.03%   |
| Generalplus Technology USB Audio Device                                    | 2        | 1.03%   |
| AMD Wrestler HDMI Audio                                                    | 2        | 1.03%   |
| AMD Trinity HDMI Audio Controller                                          | 2        | 1.03%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 1.03%   |
| TerraTec Electronic Aureon Dual USB                                        | 1        | 0.52%   |
| SteelSeries ApS SteelSeries Arctis 5                                       | 1        | 0.52%   |
| Sennheiser Communications Headset [PC 8]                                   | 1        | 0.52%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 12       | 16%     |
| Unknown             | 11       | 14.67%  |
| Corsair             | 11       | 14.67%  |
| SK hynix            | 9        | 12%     |
| Crucial             | 9        | 12%     |
| Samsung Electronics | 7        | 9.33%   |
| Micron Technology   | 4        | 5.33%   |
| G.Skill             | 3        | 4%      |
| Unknown (ABCD)      | 1        | 1.33%   |
| Unifosa             | 1        | 1.33%   |
| Team                | 1        | 1.33%   |
| Ramaxel Technology  | 1        | 1.33%   |
| Hewlett-Packard     | 1        | 1.33%   |
| HBS                 | 1        | 1.33%   |
| GOODRAM             | 1        | 1.33%   |
| Atermiter           | 1        | 1.33%   |
| A-DATA Technology   | 1        | 1.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                         | 2        | 2.53%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s               | 2        | 2.53%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s             | 2        | 2.53%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                         | 1        | 1.27%   |
| Unknown RAM Module 4GB DIMM DDR2 800MT/s                          | 1        | 1.27%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                          | 1        | 1.27%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                              | 1        | 1.27%   |
| Unknown RAM Module 4GB DIMM                                       | 1        | 1.27%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                          | 1        | 1.27%   |
| Unknown RAM Module 2GB DIMM 667MT/s                               | 1        | 1.27%   |
| Unknown RAM DDR4 NB 8G 2400 8192MB SODIMM DDR4 2667MT/s           | 1        | 1.27%   |
| Unknown RAM DDR4 NB 16G 2666 16384MB SODIMM DDR4 2667MT/s         | 1        | 1.27%   |
| Unknown RAM 1866 CL10 Series 8192MB DIMM DDR3 933MT/s             | 1        | 1.27%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 1        | 1.27%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s                 | 1        | 1.27%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s                | 1        | 1.27%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s                        | 1        | 1.27%   |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s               | 1        | 1.27%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1648MT/s              | 1        | 1.27%   |
| SK hynix RAM HMT351U7BFR8C-H9 4GB DIMM DDR3 1333MT/s              | 1        | 1.27%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s              | 1        | 1.27%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s              | 1        | 1.27%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB DIMM DDR3 1333MT/s              | 1        | 1.27%   |
| SK hynix RAM HMT325U6EFR8C-PB 2GB DIMM DDR3 1600MT/s              | 1        | 1.27%   |
| SK hynix RAM HMABAGL7ABR4N-XN 128GB DIMM DDR4 3200MT/s            | 1        | 1.27%   |
| SK hynix RAM HMA82GU6JJR8N-VK 16GB DIMM DDR4 2667MT/s             | 1        | 1.27%   |
| Samsung RAM Module 4GB DIMM DDR3 1333MT/s                         | 1        | 1.27%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s            | 1        | 1.27%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s               | 1        | 1.27%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s               | 1        | 1.27%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3266MT/s               | 1        | 1.27%   |
| Samsung RAM M323R2GA3BB0-CQKOL 16GB DIMM DDR5 4802MT/s            | 1        | 1.27%   |
| Samsung RAM M3 78T2953EZ3-CF7 1GB DIMM DDR2 800MT/s               | 1        | 1.27%   |
| Ramaxel RAM RMR1870EC58E9 4GB DIMM DDR3 1333MT/s                  | 1        | 1.27%   |
| Micron RAM 8JTF25664AZ-1G6M1 2GB DIMM DDR3 1600MT/s               | 1        | 1.27%   |
| Micron RAM 8ATF1G64AZ-2G6E1 8GB DIMM DDR4 2667MT/s                | 1        | 1.27%   |
| Kingston RAM Module 8GB DIMM DDR3 1333MT/s                        | 1        | 1.27%   |
| Kingston RAM Module 4GB DIMM DDR3 1333MT/s                        | 1        | 1.27%   |
| Kingston RAM KHX2666C13/16GX 16GB DIMM DDR4 3200MT/s              | 1        | 1.27%   |
| Kingston RAM KHX1600C9D3LK2/8GX 4GB DIMM DDR3 1600MT/s            | 1        | 1.27%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 32       | 49.23%  |
| DDR3    | 25       | 38.46%  |
| Unknown | 3        | 4.62%   |
| DDR2    | 2        | 3.08%   |
| LPDDR4  | 1        | 1.54%   |
| DDR5    | 1        | 1.54%   |
| DDR     | 1        | 1.54%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 58       | 89.23%  |
| SODIMM | 7        | 10.77%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size   | Desktops | Percent |
|--------|----------|---------|
| 8192   | 22       | 29.73%  |
| 4096   | 21       | 28.38%  |
| 16384  | 20       | 27.03%  |
| 2048   | 5        | 6.76%   |
| 32768  | 4        | 5.41%   |
| 131072 | 1        | 1.35%   |
| 1024   | 1        | 1.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 12       | 17.39%  |
| 1333    | 11       | 15.94%  |
| 3200    | 6        | 8.7%    |
| 2400    | 6        | 8.7%    |
| 2667    | 4        | 5.8%    |
| 3600    | 3        | 4.35%   |
| 1800    | 3        | 4.35%   |
| 3533    | 2        | 2.9%    |
| 3400    | 2        | 2.9%    |
| 3333    | 2        | 2.9%    |
| 2133    | 2        | 2.9%    |
| 1866    | 2        | 2.9%    |
| 800     | 2        | 2.9%    |
| 4802    | 1        | 1.45%   |
| 4000    | 1        | 1.45%   |
| 3933    | 1        | 1.45%   |
| 3800    | 1        | 1.45%   |
| 3266    | 1        | 1.45%   |
| 3100    | 1        | 1.45%   |
| 2800    | 1        | 1.45%   |
| 2747    | 1        | 1.45%   |
| 2666    | 1        | 1.45%   |
| 1648    | 1        | 1.45%   |
| 667     | 1        | 1.45%   |
| Unknown | 1        | 1.45%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Hewlett-Packard    | 2        | 33.33%  |
| Brother Industries | 2        | 33.33%  |
| Seiko Epson        | 1        | 16.67%  |
| Graphtec America   | 1        | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Seiko Epson XP-4100 Series        | 1        | 16.67%  |
| HP LaserJet Professional P1102w   | 1        | 16.67%  |
| HP DeskJet 2700 series            | 1        | 16.67%  |
| Graphtec America Graphtec Printer | 1        | 16.67%  |
| Brother HL-3140CW series          | 1        | 16.67%  |
| Brother DCP-L5500DN series        | 1        | 16.67%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 2        | 66.67%  |
| Hewlett-Packard | 1        | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| HP ScanJet G4010        | 1        | 33.33%  |
| Canon CanoScan LiDE 120 | 1        | 33.33%  |
| Canon CanoScan LiDE 110 | 1        | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 6        | 31.58%  |
| Microdia                      | 2        | 10.53%  |
| Generalplus Technology        | 2        | 10.53%  |
| Z-Star Microelectronics       | 1        | 5.26%   |
| Sunplus Innovation Technology | 1        | 5.26%   |
| Samsung Electronics           | 1        | 5.26%   |
| Realtek Semiconductor         | 1        | 5.26%   |
| Razer USA                     | 1        | 5.26%   |
| Microsoft                     | 1        | 5.26%   |
| ARC International             | 1        | 5.26%   |
| Apple                         | 1        | 5.26%   |
| Alcorlink                     | 1        | 5.26%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Microdia Webcam Vitade AF                | 2        | 10.53%  |
| Logitech Webcam C270                     | 2        | 10.53%  |
| Z-Star HP 3-MegaPixel Webcam GX607AA     | 1        | 5.26%   |
| Sunplus Integrated_Webcam_HD             | 1        | 5.26%   |
| Samsung Galaxy series, misc. (MTP mode)  | 1        | 5.26%   |
| Realtek HP 1.0MP High Definition Webcam  | 1        | 5.26%   |
| Razer USA Gaming Webcam [Kiyo]           | 1        | 5.26%   |
| Microsoft LifeCam VX-500 [1357]          | 1        | 5.26%   |
| Logitech Webcam C925e                    | 1        | 5.26%   |
| Logitech QuickCam E 3500                 | 1        | 5.26%   |
| Logitech HD Pro Webcam C920              | 1        | 5.26%   |
| Logitech C920 PRO HD Webcam              | 1        | 5.26%   |
| Generalplus GENERAL WEBCAM               | 1        | 5.26%   |
| Generalplus 808 Camera #9 (web-cam mode) | 1        | 5.26%   |
| ARC International Camera                 | 1        | 5.26%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X          | 1        | 5.26%   |
| Alcorlink USB 2.0 Camera                 | 1        | 5.26%   |

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


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| SCM Microsystems | 1        | 50%     |
| OmniKey          | 1        | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| SCM Microsystems Identiv SmartOS Reader | 1        | 50%     |
| OmniKey CardMan 1021                    | 1        | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 90       | 89.11%  |
| 1     | 9        | 8.91%   |
| 3     | 1        | 0.99%   |
| 2     | 1        | 0.99%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 4        | 30.77%  |
| Graphics card            | 3        | 23.08%  |
| Unassigned class         | 2        | 15.38%  |
| Communication controller | 1        | 7.69%   |
| Chipcard                 | 1        | 7.69%   |
| Card reader              | 1        | 7.69%   |
| Bluetooth                | 1        | 7.69%   |

