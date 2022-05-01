Xubuntu 20.04 - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for Xubuntu 20.04.

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

Total: 1210

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Unknown       | Intel X79                   | [95d09d79ca](https://linux-hardware.org/?probe=95d09d79ca) | Apr 29, 2022 |
| MSI           | Z390-A PRO                  | [6c64775a71](https://linux-hardware.org/?probe=6c64775a71) | Apr 24, 2022 |
| Gigabyte      | G33M-DS2R                   | [d2cd51f72d](https://linux-hardware.org/?probe=d2cd51f72d) | Apr 22, 2022 |
| Gigabyte      | H310M S2H x.x               | [bde3fa1f37](https://linux-hardware.org/?probe=bde3fa1f37) | Apr 22, 2022 |
| ASUSTek       | P8Z77-V                     | [40e958c5e1](https://linux-hardware.org/?probe=40e958c5e1) | Apr 19, 2022 |
| Dell          | 0WR7PY A01                  | [6fa162f829](https://linux-hardware.org/?probe=6fa162f829) | Apr 19, 2022 |
| HP            | 18E5                        | [211d35a24b](https://linux-hardware.org/?probe=211d35a24b) | Apr 17, 2022 |
| Fujitsu       | D3091-A1 S26361-D3091-A1    | [d2559a2f19](https://linux-hardware.org/?probe=d2559a2f19) | Apr 17, 2022 |
| Apple         | Mac-F221BEC8                | [32bdb05198](https://linux-hardware.org/?probe=32bdb05198) | Apr 16, 2022 |
| HP            | 21B4 A01                    | [ddd3a601b3](https://linux-hardware.org/?probe=ddd3a601b3) | Apr 15, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [0e7314b7c9](https://linux-hardware.org/?probe=0e7314b7c9) | Apr 14, 2022 |
| MSI           | B450M MORTAR TITANIUM       | [6b11750e41](https://linux-hardware.org/?probe=6b11750e41) | Apr 13, 2022 |
| Acer          | Nitro N50-610               | [f3581a0d9d](https://linux-hardware.org/?probe=f3581a0d9d) | Apr 11, 2022 |
| Dell          | 0GY6Y8 A03                  | [1fb7e31b37](https://linux-hardware.org/?probe=1fb7e31b37) | Apr 10, 2022 |
| Gigabyte      | P55A-UD3                    | [9c6781cf90](https://linux-hardware.org/?probe=9c6781cf90) | Apr 10, 2022 |
| Dell          | 00V62H A01                  | [6d0445b848](https://linux-hardware.org/?probe=6d0445b848) | Apr 09, 2022 |
| ASUSTek       | P5G41T-M LX                 | [db8350499d](https://linux-hardware.org/?probe=db8350499d) | Apr 09, 2022 |
| MSI           | Z77A-G45 GAMING             | [622ecbb225](https://linux-hardware.org/?probe=622ecbb225) | Apr 09, 2022 |
| ASUSTek       | Maximus V EXTREME           | [3718d92d8a](https://linux-hardware.org/?probe=3718d92d8a) | Apr 08, 2022 |
| ASUSTek       | Maximus V EXTREME           | [f6d9a139de](https://linux-hardware.org/?probe=f6d9a139de) | Apr 08, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [b43ffa5ce5](https://linux-hardware.org/?probe=b43ffa5ce5) | Apr 07, 2022 |
| ASUSTek       | M51BC                       | [e205187536](https://linux-hardware.org/?probe=e205187536) | Apr 07, 2022 |
| Apple         | Mac-F221BEC8                | [e092f62bc4](https://linux-hardware.org/?probe=e092f62bc4) | Apr 07, 2022 |
| Dell          | 0GY6Y8 A03                  | [a971341576](https://linux-hardware.org/?probe=a971341576) | Apr 05, 2022 |
| Dell          | OptiPlex 760                | [fa3babeea9](https://linux-hardware.org/?probe=fa3babeea9) | Apr 04, 2022 |
| Dell          | OptiPlex 760                | [ca42b9f058](https://linux-hardware.org/?probe=ca42b9f058) | Apr 03, 2022 |
| Gigabyte      | H97-D3H-CF                  | [e7b9989223](https://linux-hardware.org/?probe=e7b9989223) | Apr 02, 2022 |
| HP            | 18E5                        | [3474ce6335](https://linux-hardware.org/?probe=3474ce6335) | Apr 02, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [521a29d065](https://linux-hardware.org/?probe=521a29d065) | Mar 31, 2022 |
| Dell          | OptiPlex 760                | [b916133743](https://linux-hardware.org/?probe=b916133743) | Mar 30, 2022 |
| Gigabyte      | E350N WIN8                  | [a56241f1a8](https://linux-hardware.org/?probe=a56241f1a8) | Mar 30, 2022 |
| Dell          | OptiPlex 760                | [1ecb9c1cf3](https://linux-hardware.org/?probe=1ecb9c1cf3) | Mar 29, 2022 |
| HP            | 21B4 A01                    | [963752fd6f](https://linux-hardware.org/?probe=963752fd6f) | Mar 28, 2022 |
| Unknown       | T3 MRD                      | [3e12cb02f8](https://linux-hardware.org/?probe=3e12cb02f8) | Mar 26, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [1de7956cf2](https://linux-hardware.org/?probe=1de7956cf2) | Mar 26, 2022 |
| Pegatron      | Benicia                     | [cb852b48fb](https://linux-hardware.org/?probe=cb852b48fb) | Mar 25, 2022 |
| ASUSTek       | PRIME H270M-PLUS            | [b27c4a7fe4](https://linux-hardware.org/?probe=b27c4a7fe4) | Mar 24, 2022 |
| ASRock        | B550 Phantom Gaming 4       | [39dc1025e9](https://linux-hardware.org/?probe=39dc1025e9) | Mar 24, 2022 |
| Gigabyte      | H310M H x.x                 | [5adb4614c4](https://linux-hardware.org/?probe=5adb4614c4) | Mar 23, 2022 |
| Gigabyte      | H310M H x.x                 | [d277e5c6bc](https://linux-hardware.org/?probe=d277e5c6bc) | Mar 23, 2022 |
| Unknown       | T3 MRD                      | [3ec2149915](https://linux-hardware.org/?probe=3ec2149915) | Mar 23, 2022 |
| ASRock        | B550 Phantom Gaming 4       | [2f0764ceb3](https://linux-hardware.org/?probe=2f0764ceb3) | Mar 23, 2022 |
| ECS           | H87H3-M                     | [f15990212f](https://linux-hardware.org/?probe=f15990212f) | Mar 20, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [a226a58819](https://linux-hardware.org/?probe=a226a58819) | Mar 19, 2022 |
| ASUSTek       | A68HM-K                     | [4491d23e02](https://linux-hardware.org/?probe=4491d23e02) | Mar 16, 2022 |
| Acer          | Aspire X1920                | [2b3d54ec4a](https://linux-hardware.org/?probe=2b3d54ec4a) | Mar 14, 2022 |
| Gigabyte      | GA-MA78GM-S2H               | [dfef2d9492](https://linux-hardware.org/?probe=dfef2d9492) | Mar 13, 2022 |
| Dell          | 0RW199                      | [2298b1db14](https://linux-hardware.org/?probe=2298b1db14) | Mar 13, 2022 |
| HP            | 18E5                        | [638dc06bc0](https://linux-hardware.org/?probe=638dc06bc0) | Mar 10, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [54c4f70c98](https://linux-hardware.org/?probe=54c4f70c98) | Mar 08, 2022 |
| Acer          | TPDS05 R3700                | [48fc5c9d8b](https://linux-hardware.org/?probe=48fc5c9d8b) | Mar 08, 2022 |
| Dell          | 00V62H A00                  | [b9ca0e3bde](https://linux-hardware.org/?probe=b9ca0e3bde) | Mar 07, 2022 |
| Dell          | 00V62H A00                  | [6f5adc1704](https://linux-hardware.org/?probe=6f5adc1704) | Mar 07, 2022 |
| MSI           | B350 TOMAHAWK               | [2525f81966](https://linux-hardware.org/?probe=2525f81966) | Mar 06, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [2623cf5090](https://linux-hardware.org/?probe=2623cf5090) | Feb 28, 2022 |
| Lenovo        | NO DPK                      | [a720d5bcaf](https://linux-hardware.org/?probe=a720d5bcaf) | Feb 27, 2022 |
| Dell          | 042P49 A02                  | [9efbb51081](https://linux-hardware.org/?probe=9efbb51081) | Feb 25, 2022 |
| Acer          | TPDS05 R3700                | [df877f2b77](https://linux-hardware.org/?probe=df877f2b77) | Feb 24, 2022 |
| Acer          | TPDS05 R3700                | [4957d6525b](https://linux-hardware.org/?probe=4957d6525b) | Feb 24, 2022 |
| MSI           | G41M-P25                    | [c8ebea2807](https://linux-hardware.org/?probe=c8ebea2807) | Feb 23, 2022 |
| Pegatron      | 2AB5                        | [f2ee067b5f](https://linux-hardware.org/?probe=f2ee067b5f) | Feb 23, 2022 |
| ASRock        | K10N78M                     | [f8a578c070](https://linux-hardware.org/?probe=f8a578c070) | Feb 21, 2022 |
| MSI           | A55M-P33                    | [d891e34be9](https://linux-hardware.org/?probe=d891e34be9) | Feb 20, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [8f1ce82db7](https://linux-hardware.org/?probe=8f1ce82db7) | Feb 15, 2022 |
| MSI           | MEG X570 ACE                | [4cb6628353](https://linux-hardware.org/?probe=4cb6628353) | Feb 14, 2022 |
| MSI           | MEG X570 ACE                | [43ac6b6d18](https://linux-hardware.org/?probe=43ac6b6d18) | Feb 14, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [6f11ea4988](https://linux-hardware.org/?probe=6f11ea4988) | Feb 14, 2022 |
| HP            | 3031h                       | [1475e006cd](https://linux-hardware.org/?probe=1475e006cd) | Feb 13, 2022 |
| ASUSTek       | PRIME H570M-PLUS            | [adc14fca30](https://linux-hardware.org/?probe=adc14fca30) | Feb 12, 2022 |
| Unknown       | Intel X79                   | [f0dd6357fe](https://linux-hardware.org/?probe=f0dd6357fe) | Feb 12, 2022 |
| ASUSTek       | M5A97 R2.0                  | [0301e86e1b](https://linux-hardware.org/?probe=0301e86e1b) | Feb 09, 2022 |
| Unknown       | Intel X79                   | [089b663f84](https://linux-hardware.org/?probe=089b663f84) | Feb 06, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [1feae56050](https://linux-hardware.org/?probe=1feae56050) | Feb 06, 2022 |
| Gigabyte      | GA-870A-UD3                 | [e4b5396bf7](https://linux-hardware.org/?probe=e4b5396bf7) | Feb 04, 2022 |
| Dell          | 0XCR8D A01                  | [a68034b1e8](https://linux-hardware.org/?probe=a68034b1e8) | Feb 03, 2022 |
| Dell          | 051FJ8 A00                  | [da74a4ea79](https://linux-hardware.org/?probe=da74a4ea79) | Feb 01, 2022 |
| Fujitsu       | D3613-A1 S26361-D3613-A1    | [27b9e98a16](https://linux-hardware.org/?probe=27b9e98a16) | Feb 01, 2022 |
| ASRock        | M3A UCC                     | [8ca7699b4c](https://linux-hardware.org/?probe=8ca7699b4c) | Jan 28, 2022 |
| Pegatron      | Benicia                     | [8d1af3f3af](https://linux-hardware.org/?probe=8d1af3f3af) | Jan 27, 2022 |
| Unknown       | Unknown                     | [018c871f94](https://linux-hardware.org/?probe=018c871f94) | Jan 25, 2022 |
| ASUSTek       | H87M-PLUS                   | [986b65d292](https://linux-hardware.org/?probe=986b65d292) | Jan 21, 2022 |
| Lenovo        | Myrtle CRB SDK0J40700 WI... | [44b718700d](https://linux-hardware.org/?probe=44b718700d) | Jan 19, 2022 |
| Gigabyte      | MZBSWBP-00                  | [a8699a0a00](https://linux-hardware.org/?probe=a8699a0a00) | Jan 18, 2022 |
| ASUSTek       | P9X79                       | [2afe3ef5cc](https://linux-hardware.org/?probe=2afe3ef5cc) | Jan 16, 2022 |
| Dell          | 0PP150 A00                  | [554774c3c8](https://linux-hardware.org/?probe=554774c3c8) | Jan 16, 2022 |
| Gigabyte      | EX58-UD4P                   | [368d168909](https://linux-hardware.org/?probe=368d168909) | Jan 15, 2022 |
| Lenovo        | ThinkCentre A70 7099A5G     | [78902354bb](https://linux-hardware.org/?probe=78902354bb) | Jan 14, 2022 |
| ASUSTek       | M4A78L-M                    | [dfb87ada40](https://linux-hardware.org/?probe=dfb87ada40) | Jan 13, 2022 |
| HP            | 3031h                       | [46b02ff904](https://linux-hardware.org/?probe=46b02ff904) | Jan 11, 2022 |
| HP            | 3031h                       | [2e78e6c7f8](https://linux-hardware.org/?probe=2e78e6c7f8) | Jan 10, 2022 |
| ASUSTek       | H87M-PLUS                   | [eb70946711](https://linux-hardware.org/?probe=eb70946711) | Jan 09, 2022 |
| ASUSTek       | M4A88T-M                    | [7f20d8ac9a](https://linux-hardware.org/?probe=7f20d8ac9a) | Jan 09, 2022 |
| MSI           | H61M-P23                    | [14690b4128](https://linux-hardware.org/?probe=14690b4128) | Jan 08, 2022 |
| ASRock        | N68-VS3 UCC                 | [0ea3f1d6fa](https://linux-hardware.org/?probe=0ea3f1d6fa) | Jan 08, 2022 |
| Dell          | 073MMW A03                  | [65c164f304](https://linux-hardware.org/?probe=65c164f304) | Jan 07, 2022 |
| Gigabyte      | GA-970A-D3                  | [0fe418c7b1](https://linux-hardware.org/?probe=0fe418c7b1) | Jan 07, 2022 |
| Gigabyte      | Z97X-UD3H-BK-CF             | [ef69bbfd12](https://linux-hardware.org/?probe=ef69bbfd12) | Jan 07, 2022 |
| HP            | 0AA8h                       | [9abf55a71f](https://linux-hardware.org/?probe=9abf55a71f) | Jan 05, 2022 |
| HP            | 0AA8h                       | [44c9ba4231](https://linux-hardware.org/?probe=44c9ba4231) | Jan 03, 2022 |
| Intel         | DP35DP AAD81073-209         | [f6ec40d0f8](https://linux-hardware.org/?probe=f6ec40d0f8) | Jan 01, 2022 |
| ASUSTek       | P5K-E                       | [f1c3532217](https://linux-hardware.org/?probe=f1c3532217) | Dec 31, 2021 |
| ECS           | G41T-M2                     | [6b4159a357](https://linux-hardware.org/?probe=6b4159a357) | Dec 29, 2021 |
| Gigabyte      | H110M-H-CF                  | [d8a2a90482](https://linux-hardware.org/?probe=d8a2a90482) | Dec 27, 2021 |
| Gigabyte      | H110M-H-CF                  | [63b3337725](https://linux-hardware.org/?probe=63b3337725) | Dec 26, 2021 |
| ASRock        | A75M-ITX                    | [1070ea74d9](https://linux-hardware.org/?probe=1070ea74d9) | Dec 25, 2021 |
| ASRock        | X570M Pro4                  | [602d3e0afd](https://linux-hardware.org/?probe=602d3e0afd) | Dec 23, 2021 |
| HP            | 3398                        | [759e3821b8](https://linux-hardware.org/?probe=759e3821b8) | Dec 22, 2021 |
| Dell          | 0M5DCD A00                  | [d29b59a855](https://linux-hardware.org/?probe=d29b59a855) | Dec 21, 2021 |
| Gigabyte      | B150M-D3H-CF                | [22f2f5c84b](https://linux-hardware.org/?probe=22f2f5c84b) | Dec 21, 2021 |
| HP            | 18E7                        | [b233eb9f3e](https://linux-hardware.org/?probe=b233eb9f3e) | Dec 20, 2021 |
| ASUSTek       | PRIME H310M-R R2.0          | [32340d057e](https://linux-hardware.org/?probe=32340d057e) | Dec 20, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [8986819d3f](https://linux-hardware.org/?probe=8986819d3f) | Dec 19, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [eef4da77d4](https://linux-hardware.org/?probe=eef4da77d4) | Dec 19, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | [a94bf3ef84](https://linux-hardware.org/?probe=a94bf3ef84) | Dec 19, 2021 |
| Dell          | 0VD5HY A04                  | [2aaa0df82d](https://linux-hardware.org/?probe=2aaa0df82d) | Dec 18, 2021 |
| ASUSTek       | P5GC-MX                     | [499a024e97](https://linux-hardware.org/?probe=499a024e97) | Dec 18, 2021 |
| Biostar       | H110MHC                     | [bb74f304fd](https://linux-hardware.org/?probe=bb74f304fd) | Dec 16, 2021 |
| MSI           | MS-B0501 100                | [ca4048db98](https://linux-hardware.org/?probe=ca4048db98) | Dec 14, 2021 |
| Gigabyte      | EX58-UD4P                   | [aa8da2e23c](https://linux-hardware.org/?probe=aa8da2e23c) | Dec 14, 2021 |
| Dell          | 0T656F A02                  | [c6fcad51e9](https://linux-hardware.org/?probe=c6fcad51e9) | Dec 13, 2021 |
| Gigabyte      | GA-MA78LMT-US2H             | [45a5dc5b06](https://linux-hardware.org/?probe=45a5dc5b06) | Dec 13, 2021 |
| Dell          | 073MMW A00                  | [c5c064c84f](https://linux-hardware.org/?probe=c5c064c84f) | Dec 13, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [1f799f28c2](https://linux-hardware.org/?probe=1f799f28c2) | Dec 12, 2021 |
| ASUSTek       | M51BC                       | [11ff47f723](https://linux-hardware.org/?probe=11ff47f723) | Dec 12, 2021 |
| ASUSTek       | M51BC                       | [0dd637c0b8](https://linux-hardware.org/?probe=0dd637c0b8) | Dec 12, 2021 |
| ASUSTek       | P5G41T-M LX                 | [8b03acc524](https://linux-hardware.org/?probe=8b03acc524) | Dec 11, 2021 |
| Lenovo        | ThinkCentre A70 7844H9G     | [1b7f8b1fb9](https://linux-hardware.org/?probe=1b7f8b1fb9) | Dec 11, 2021 |
| ASUSTek       | M5A97 PLUS                  | [8684f34a9e](https://linux-hardware.org/?probe=8684f34a9e) | Dec 10, 2021 |
| Dell          | 06D7TR A00                  | [a4f61b0f15](https://linux-hardware.org/?probe=a4f61b0f15) | Dec 09, 2021 |
| Acer          | Veriton E430 v1.0           | [5c857f1bb6](https://linux-hardware.org/?probe=5c857f1bb6) | Dec 08, 2021 |
| ECS           | Nettle2                     | [bb67b27e67](https://linux-hardware.org/?probe=bb67b27e67) | Dec 07, 2021 |
| Dell          | 01W26N A00                  | [7c3e61ec94](https://linux-hardware.org/?probe=7c3e61ec94) | Dec 06, 2021 |
| Gigabyte      | EP35-DS4                    | [570104ad1e](https://linux-hardware.org/?probe=570104ad1e) | Dec 04, 2021 |
| Gigabyte      | B450M DS3H-CF               | [2e34a3a698](https://linux-hardware.org/?probe=2e34a3a698) | Dec 04, 2021 |
| Medion        | H81M-P33                    | [29b3a27675](https://linux-hardware.org/?probe=29b3a27675) | Dec 02, 2021 |
| Gigabyte      | GA-E350N                    | [10d55dd433](https://linux-hardware.org/?probe=10d55dd433) | Dec 02, 2021 |
| HP            | 0AA4h                       | [f7438f59ac](https://linux-hardware.org/?probe=f7438f59ac) | Dec 01, 2021 |
| Gigabyte      | X99-UD4-CF                  | [190d1b6a29](https://linux-hardware.org/?probe=190d1b6a29) | Dec 01, 2021 |
| Shuttle       | NC03U                       | [2453ada3ba](https://linux-hardware.org/?probe=2453ada3ba) | Nov 30, 2021 |
| ASUSTek       | H81M-PLUS                   | [6d6caad964](https://linux-hardware.org/?probe=6d6caad964) | Nov 29, 2021 |
| ASUSTek       | B150-PLUS                   | [b2079cdb96](https://linux-hardware.org/?probe=b2079cdb96) | Nov 29, 2021 |
| ASUSTek       | A68HM-K                     | [29e9d64420](https://linux-hardware.org/?probe=29e9d64420) | Nov 29, 2021 |
| ASUSTek       | P7P55D                      | [85f288d39b](https://linux-hardware.org/?probe=85f288d39b) | Nov 29, 2021 |
| Acer          | EG43LMK                     | [28e31230a4](https://linux-hardware.org/?probe=28e31230a4) | Nov 28, 2021 |
| HP            | 0AA8h                       | [1d80d6636e](https://linux-hardware.org/?probe=1d80d6636e) | Nov 26, 2021 |
| ASUSTek       | B150-PLUS                   | [b91114141e](https://linux-hardware.org/?probe=b91114141e) | Nov 26, 2021 |
| Medion        | H110H4-EM                   | [8b1485f27d](https://linux-hardware.org/?probe=8b1485f27d) | Nov 25, 2021 |
| ASRock        | B450M Pro4                  | [76361c26c6](https://linux-hardware.org/?probe=76361c26c6) | Nov 24, 2021 |
| ASRock        | N68-GS4 FX R2.0             | [d61128f6f4](https://linux-hardware.org/?probe=d61128f6f4) | Nov 24, 2021 |
| Gigabyte      | Z97X-UD3H-CF                | [fe8ad04ad3](https://linux-hardware.org/?probe=fe8ad04ad3) | Nov 23, 2021 |
| Lenovo        | ThinkCentre A70 7844H9G     | [baea0d315f](https://linux-hardware.org/?probe=baea0d315f) | Nov 21, 2021 |
| ASUSTek       | M3N78-EM                    | [b358f07f1d](https://linux-hardware.org/?probe=b358f07f1d) | Nov 21, 2021 |
| Dell          | 0WMJ54 A01                  | [b1f845a48f](https://linux-hardware.org/?probe=b1f845a48f) | Nov 20, 2021 |
| ASUSTek       | M3N78-EM                    | [930c018424](https://linux-hardware.org/?probe=930c018424) | Nov 20, 2021 |
| HP            | 0AA8h                       | [3b1a84d622](https://linux-hardware.org/?probe=3b1a84d622) | Nov 20, 2021 |
| Dell          | 014GRG A02                  | [c23455dd49](https://linux-hardware.org/?probe=c23455dd49) | Nov 20, 2021 |
| ASUSTek       | B150-PLUS                   | [3c4c353831](https://linux-hardware.org/?probe=3c4c353831) | Nov 19, 2021 |
| MSI           | 3666h                       | [21f11d2850](https://linux-hardware.org/?probe=21f11d2850) | Nov 19, 2021 |
| ASRock        | Z97 Extreme4                | [fc86b0fc2e](https://linux-hardware.org/?probe=fc86b0fc2e) | Nov 18, 2021 |
| MSI           | 3666h                       | [aad8cfbf76](https://linux-hardware.org/?probe=aad8cfbf76) | Nov 18, 2021 |
| ASUSTek       | P5LD2-VM                    | [befbf7345c](https://linux-hardware.org/?probe=befbf7345c) | Nov 17, 2021 |
| HP            | 0AA8h                       | [5cd5f5de04](https://linux-hardware.org/?probe=5cd5f5de04) | Nov 16, 2021 |
| ASRock        | H470 Phantom Gaming 4       | [07ef26c830](https://linux-hardware.org/?probe=07ef26c830) | Nov 16, 2021 |
| Lenovo        | ThinkCentre A58e 0841A2U    | [a8398f9036](https://linux-hardware.org/?probe=a8398f9036) | Nov 13, 2021 |
| ASUSTek       | PRIME B550M-A               | [269b146e10](https://linux-hardware.org/?probe=269b146e10) | Nov 10, 2021 |
| Fujitsu       | D3417-B2 S26361-D3417-B2    | [ab14080e40](https://linux-hardware.org/?probe=ab14080e40) | Nov 09, 2021 |
| Medion        | H110H4-EM                   | [3ecf7775d6](https://linux-hardware.org/?probe=3ecf7775d6) | Nov 09, 2021 |
| ASUSTek       | PRIME B550M-A               | [9456930b53](https://linux-hardware.org/?probe=9456930b53) | Nov 08, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [425b956614](https://linux-hardware.org/?probe=425b956614) | Nov 07, 2021 |
| NCR           | Pocono BIOS.3.1             | [985620ce15](https://linux-hardware.org/?probe=985620ce15) | Nov 07, 2021 |
| Medion        | MS-7366                     | [da9961f1ee](https://linux-hardware.org/?probe=da9961f1ee) | Nov 04, 2021 |
| Acer          | Aspire X3990                | [967427d98c](https://linux-hardware.org/?probe=967427d98c) | Oct 29, 2021 |
| Acer          | Aspire X3990                | [7ccc4b3004](https://linux-hardware.org/?probe=7ccc4b3004) | Oct 29, 2021 |
| HP            | 8433 11                     | [6183f8775b](https://linux-hardware.org/?probe=6183f8775b) | Oct 29, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [164b215164](https://linux-hardware.org/?probe=164b215164) | Oct 29, 2021 |
| ASUSTek       | P5KC                        | [109cb750a6](https://linux-hardware.org/?probe=109cb750a6) | Oct 25, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [2b52b81540](https://linux-hardware.org/?probe=2b52b81540) | Oct 24, 2021 |
| Dell          | 042P49 A00                  | [7bb7c6c3cb](https://linux-hardware.org/?probe=7bb7c6c3cb) | Oct 23, 2021 |
| MSI           | Z97 GAMING 5                | [0273030434](https://linux-hardware.org/?probe=0273030434) | Oct 22, 2021 |
| HP            | 1998                        | [db3a3fbce2](https://linux-hardware.org/?probe=db3a3fbce2) | Oct 21, 2021 |
| Dell          | 0PU052                      | [7e7d0bc489](https://linux-hardware.org/?probe=7e7d0bc489) | Oct 21, 2021 |
| ASUSTek       | PRIME H310T                 | [b0e10a4766](https://linux-hardware.org/?probe=b0e10a4766) | Oct 20, 2021 |
| MSI           | B350 TOMAHAWK               | [a119d97189](https://linux-hardware.org/?probe=a119d97189) | Oct 20, 2021 |
| ASRock        | G31M-VS2                    | [555bb7179c](https://linux-hardware.org/?probe=555bb7179c) | Oct 19, 2021 |
| MSI           | H170M PRO-VDH               | [63cab5e07f](https://linux-hardware.org/?probe=63cab5e07f) | Oct 19, 2021 |
| MSI           | H170M PRO-VDH               | [355e464f7f](https://linux-hardware.org/?probe=355e464f7f) | Oct 19, 2021 |
| HP            | 8717                        | [23f7ea44ce](https://linux-hardware.org/?probe=23f7ea44ce) | Oct 18, 2021 |
| Gigabyte      | M68MT-D3P                   | [9debdd654c](https://linux-hardware.org/?probe=9debdd654c) | Oct 15, 2021 |
| NCR           | Pocono BIOS.3.1             | [53cafab8f3](https://linux-hardware.org/?probe=53cafab8f3) | Oct 15, 2021 |
| Clientron     | Pineview-D                  | [59bf0b789c](https://linux-hardware.org/?probe=59bf0b789c) | Oct 13, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | [e922eda008](https://linux-hardware.org/?probe=e922eda008) | Oct 12, 2021 |
| Foxconn       | 2AB1h                       | [6216ce3f5c](https://linux-hardware.org/?probe=6216ce3f5c) | Oct 12, 2021 |
| MSI           | H170M PRO-VDH               | [56135a7fa6](https://linux-hardware.org/?probe=56135a7fa6) | Oct 11, 2021 |
| MSI           | H170M PRO-VDH               | [d7676eeb32](https://linux-hardware.org/?probe=d7676eeb32) | Oct 11, 2021 |
| Gigabyte      | B450 AORUS ELITE V2         | [c49cbf2f7a](https://linux-hardware.org/?probe=c49cbf2f7a) | Oct 11, 2021 |
| Biostar       | G41D3C                      | [433bc7cf78](https://linux-hardware.org/?probe=433bc7cf78) | Oct 10, 2021 |
| Medion        | B360H4-EM V1.0              | [6d2f43a452](https://linux-hardware.org/?probe=6d2f43a452) | Oct 09, 2021 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [6beb9ddceb](https://linux-hardware.org/?probe=6beb9ddceb) | Oct 09, 2021 |
| Gigabyte      | H510M S2H                   | [77205a87c4](https://linux-hardware.org/?probe=77205a87c4) | Oct 09, 2021 |
| ASUSTek       | PRIME H410M-K               | [a4da124d05](https://linux-hardware.org/?probe=a4da124d05) | Oct 08, 2021 |
| Gigabyte      | X38-DS4                     | [5e06d3cb35](https://linux-hardware.org/?probe=5e06d3cb35) | Oct 08, 2021 |
| Dell          | 05DN3X A00                  | [248c508eb0](https://linux-hardware.org/?probe=248c508eb0) | Oct 07, 2021 |
| Dell          | 05DN3X A00                  | [0735063fbe](https://linux-hardware.org/?probe=0735063fbe) | Oct 07, 2021 |
| Lenovo        | ThinkCentre A55 92658HG     | [edc1f2768d](https://linux-hardware.org/?probe=edc1f2768d) | Oct 05, 2021 |
| Acer          | Aspire X1430                | [0864e39368](https://linux-hardware.org/?probe=0864e39368) | Oct 05, 2021 |
| Acer          | Aspire X1430                | [ced0bae8da](https://linux-hardware.org/?probe=ced0bae8da) | Oct 05, 2021 |
| Biostar       | G41D3C                      | [90dc88db01](https://linux-hardware.org/?probe=90dc88db01) | Oct 02, 2021 |
| MSI           | MPG Z390 GAMING EDGE AC     | [37caf69047](https://linux-hardware.org/?probe=37caf69047) | Oct 02, 2021 |
| ASRock        | Z170 Gaming K4              | [f107c84c00](https://linux-hardware.org/?probe=f107c84c00) | Sep 30, 2021 |
| Insyde        | Harrisonville               | [2b7a8ba5fc](https://linux-hardware.org/?probe=2b7a8ba5fc) | Sep 30, 2021 |
| HP            | 2175                        | [856907ec52](https://linux-hardware.org/?probe=856907ec52) | Sep 28, 2021 |
| ASUSTek       | PRIME H310T                 | [58721f0765](https://linux-hardware.org/?probe=58721f0765) | Sep 28, 2021 |
| Dell          | 0N826N A03                  | [fc1d74c246](https://linux-hardware.org/?probe=fc1d74c246) | Sep 27, 2021 |
| ASUSTek       | PRIME H510M-K               | [c11c48b5d6](https://linux-hardware.org/?probe=c11c48b5d6) | Sep 24, 2021 |
| ASUSTek       | PRIME H510M-K               | [66900d1009](https://linux-hardware.org/?probe=66900d1009) | Sep 24, 2021 |
| HP            | 21F5                        | [d6613e1901](https://linux-hardware.org/?probe=d6613e1901) | Sep 22, 2021 |
| AAEON         | GENE-APL5 V1.0              | [7abd7a20df](https://linux-hardware.org/?probe=7abd7a20df) | Sep 21, 2021 |
| NCR           | Pocono                      | [bbd821ad81](https://linux-hardware.org/?probe=bbd821ad81) | Sep 18, 2021 |
| Medion        | H110H4-EM                   | [a531e60d2b](https://linux-hardware.org/?probe=a531e60d2b) | Sep 18, 2021 |
| ASUSTek       | P8H67                       | [ad597e71b6](https://linux-hardware.org/?probe=ad597e71b6) | Sep 16, 2021 |
| ASUSTek       | M5A78L LE                   | [ddb041ded0](https://linux-hardware.org/?probe=ddb041ded0) | Sep 15, 2021 |
| ASUSTek       | M5A78L LE                   | [a9335318aa](https://linux-hardware.org/?probe=a9335318aa) | Sep 15, 2021 |
| Gigabyte      | B550 AORUS PRO AC           | [ea9fbdbba6](https://linux-hardware.org/?probe=ea9fbdbba6) | Sep 14, 2021 |
| Dell          | 0XHGV1 A00                  | [c7f133cbb9](https://linux-hardware.org/?probe=c7f133cbb9) | Sep 14, 2021 |
| Foxconn       | 2A8C                        | [f7b2ed152f](https://linux-hardware.org/?probe=f7b2ed152f) | Sep 12, 2021 |
| Foxconn       | 2A8C                        | [de95109559](https://linux-hardware.org/?probe=de95109559) | Sep 11, 2021 |
| ASUSTek       | M3N18L T-M3N8200            | [bd8410bceb](https://linux-hardware.org/?probe=bd8410bceb) | Sep 09, 2021 |
| Biostar       | G41D3C                      | [fc87e33227](https://linux-hardware.org/?probe=fc87e33227) | Sep 07, 2021 |
| ASUSTek       | H170M-PLUS                  | [7b81d32161](https://linux-hardware.org/?probe=7b81d32161) | Sep 07, 2021 |
| OEM           | BayTrail JHS365             | [e82d82c85b](https://linux-hardware.org/?probe=e82d82c85b) | Sep 03, 2021 |
| ASUSTek       | P8Z68-V LX                  | [899954b326](https://linux-hardware.org/?probe=899954b326) | Sep 02, 2021 |
| Acer          | Aspire XC-603G              | [888a6f7244](https://linux-hardware.org/?probe=888a6f7244) | Sep 02, 2021 |
| HP            | 3032h                       | [4b261dcd37](https://linux-hardware.org/?probe=4b261dcd37) | Sep 02, 2021 |
| Gigabyte      | G41M-ES2L                   | [b9fdcaf2f7](https://linux-hardware.org/?probe=b9fdcaf2f7) | Sep 02, 2021 |
| Biostar       | G41D3C                      | [985970ad93](https://linux-hardware.org/?probe=985970ad93) | Sep 01, 2021 |
| Biostar       | G41D3C                      | [a94c446d8d](https://linux-hardware.org/?probe=a94c446d8d) | Sep 01, 2021 |
| MSI           | Z97-G43                     | [364baf5248](https://linux-hardware.org/?probe=364baf5248) | Aug 31, 2021 |
| ASRock        | Q1900M                      | [bdb4eba3e4](https://linux-hardware.org/?probe=bdb4eba3e4) | Aug 31, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [89c397b882](https://linux-hardware.org/?probe=89c397b882) | Aug 29, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [aa1a98a9d6](https://linux-hardware.org/?probe=aa1a98a9d6) | Aug 25, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [fae18649fd](https://linux-hardware.org/?probe=fae18649fd) | Aug 24, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [f0824b7193](https://linux-hardware.org/?probe=f0824b7193) | Aug 24, 2021 |
| Acer          | Aspire TC-885 V:1.1         | [8d43ff5f35](https://linux-hardware.org/?probe=8d43ff5f35) | Aug 23, 2021 |
| Acer          | Aspire TC-885 V:1.1         | [23fcf2122e](https://linux-hardware.org/?probe=23fcf2122e) | Aug 23, 2021 |
| Gigabyte      | B450M DS3H-CF               | [f128b4ee5a](https://linux-hardware.org/?probe=f128b4ee5a) | Aug 23, 2021 |
| Acer          | Aspire XC-603G              | [3aca23ef5f](https://linux-hardware.org/?probe=3aca23ef5f) | Aug 22, 2021 |
| Foxconn       | 2A8C                        | [f3ae3bb84c](https://linux-hardware.org/?probe=f3ae3bb84c) | Aug 21, 2021 |
| Alienware     | 0N4R4N A00                  | [bf5947b943](https://linux-hardware.org/?probe=bf5947b943) | Aug 20, 2021 |
| ASRock        | A320M-HDV                   | [42ab0a8ca5](https://linux-hardware.org/?probe=42ab0a8ca5) | Aug 20, 2021 |
| Acer          | Aspire X1470                | [79d5cfd4fd](https://linux-hardware.org/?probe=79d5cfd4fd) | Aug 20, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [dbb548b728](https://linux-hardware.org/?probe=dbb548b728) | Aug 18, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [49de44e735](https://linux-hardware.org/?probe=49de44e735) | Aug 17, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [4740529a1f](https://linux-hardware.org/?probe=4740529a1f) | Aug 17, 2021 |
| MSI           | Boston                      | [eb189f6da8](https://linux-hardware.org/?probe=eb189f6da8) | Aug 17, 2021 |
| HP            | 0B54h D                     | [f68a448d75](https://linux-hardware.org/?probe=f68a448d75) | Aug 17, 2021 |
| Gateway       | SX2185                      | [6e9745ae09](https://linux-hardware.org/?probe=6e9745ae09) | Aug 17, 2021 |
| HP            | 0B54h D                     | [9fd9d289f2](https://linux-hardware.org/?probe=9fd9d289f2) | Aug 17, 2021 |
| ASUSTek       | B85-PLUS                    | [10fd5746f0](https://linux-hardware.org/?probe=10fd5746f0) | Aug 14, 2021 |
| ASRock        | A300M-STX                   | [3ff1b8f6dc](https://linux-hardware.org/?probe=3ff1b8f6dc) | Aug 14, 2021 |
| HP            | 0B54h D                     | [49eb423362](https://linux-hardware.org/?probe=49eb423362) | Aug 11, 2021 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [c69570237c](https://linux-hardware.org/?probe=c69570237c) | Aug 10, 2021 |
| Gigabyte      | X99-UD4-CF                  | [0b019ac936](https://linux-hardware.org/?probe=0b019ac936) | Aug 09, 2021 |
| ASUSTek       | H87M-PLUS                   | [c2ed04ce87](https://linux-hardware.org/?probe=c2ed04ce87) | Aug 09, 2021 |
| Intel         | D945GNT AAC96315-402        | [a2d256eee3](https://linux-hardware.org/?probe=a2d256eee3) | Aug 08, 2021 |
| Dell          | 0WMJ54 A00                  | [d577241d35](https://linux-hardware.org/?probe=d577241d35) | Aug 08, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [c45499e754](https://linux-hardware.org/?probe=c45499e754) | Aug 07, 2021 |
| HP            | 0B54h D                     | [1d475ecd05](https://linux-hardware.org/?probe=1d475ecd05) | Aug 07, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [40033bb091](https://linux-hardware.org/?probe=40033bb091) | Aug 06, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [c3ac112d1b](https://linux-hardware.org/?probe=c3ac112d1b) | Aug 06, 2021 |
| HP            | 1998                        | [e6d0744e85](https://linux-hardware.org/?probe=e6d0744e85) | Aug 04, 2021 |
| HP            | 1998                        | [b3b909d152](https://linux-hardware.org/?probe=b3b909d152) | Aug 04, 2021 |
| HP            | 3646h                       | [60fb363058](https://linux-hardware.org/?probe=60fb363058) | Aug 02, 2021 |
| HP            | 2B29                        | [06babd8c13](https://linux-hardware.org/?probe=06babd8c13) | Aug 01, 2021 |
| Medion        | H110H4-EM                   | [cae542af6c](https://linux-hardware.org/?probe=cae542af6c) | Aug 01, 2021 |
| HP            | 0B54h D                     | [a7f0b16b1f](https://linux-hardware.org/?probe=a7f0b16b1f) | Jul 31, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [0aae2dd454](https://linux-hardware.org/?probe=0aae2dd454) | Jul 30, 2021 |
| MSI           | MS-7181                     | [f2c624a258](https://linux-hardware.org/?probe=f2c624a258) | Jul 26, 2021 |
| WinFast       | 6100M2MA FAB1.0             | [f994eb2a66](https://linux-hardware.org/?probe=f994eb2a66) | Jul 26, 2021 |
| Intel         | DQ67SW AAG12527-310         | [36a4037b9d](https://linux-hardware.org/?probe=36a4037b9d) | Jul 26, 2021 |
| Gigabyte      | GA-MA74GM-S2H               | [69bc249119](https://linux-hardware.org/?probe=69bc249119) | Jul 25, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [d6e4e7f445](https://linux-hardware.org/?probe=d6e4e7f445) | Jul 25, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [7d7ebd3f1e](https://linux-hardware.org/?probe=7d7ebd3f1e) | Jul 25, 2021 |
| Gigabyte      | GA-MA74GM-S2H               | [56198fa6c1](https://linux-hardware.org/?probe=56198fa6c1) | Jul 24, 2021 |
| Dell          | 03KWTV A02                  | [b292aa69b5](https://linux-hardware.org/?probe=b292aa69b5) | Jul 24, 2021 |
| HP            | 1589                        | [2885bdaad2](https://linux-hardware.org/?probe=2885bdaad2) | Jul 23, 2021 |
| MSI           | Z370-A PRO                  | [b125a65313](https://linux-hardware.org/?probe=b125a65313) | Jul 22, 2021 |
| ASUSTek       | PRIME Z390-A                | [f8767723e4](https://linux-hardware.org/?probe=f8767723e4) | Jul 18, 2021 |
| ASRock        | 880GM-LE                    | [4808dde963](https://linux-hardware.org/?probe=4808dde963) | Jul 18, 2021 |
| Dell          | 0VNP2H A00                  | [167ec81986](https://linux-hardware.org/?probe=167ec81986) | Jul 17, 2021 |
| Gigabyte      | Z77X-D3H                    | [8263a1f725](https://linux-hardware.org/?probe=8263a1f725) | Jul 17, 2021 |
| ASRock        | X300M-STX                   | [3a35cafb7f](https://linux-hardware.org/?probe=3a35cafb7f) | Jul 17, 2021 |
| ASUSTek       | M3A-H/HDMI                  | [6c97b09b3f](https://linux-hardware.org/?probe=6c97b09b3f) | Jul 14, 2021 |
| Gigabyte      | H55M-UD2H                   | [d871a17735](https://linux-hardware.org/?probe=d871a17735) | Jul 14, 2021 |
| ASRock        | Z490 Phantom Gaming 4       | [ee2fa49a14](https://linux-hardware.org/?probe=ee2fa49a14) | Jul 13, 2021 |
| HP            | 0A64h                       | [317c62b0b9](https://linux-hardware.org/?probe=317c62b0b9) | Jul 13, 2021 |
| HP            | 0A64h                       | [7495976a12](https://linux-hardware.org/?probe=7495976a12) | Jul 13, 2021 |
| ASUSTek       | A68HM-K                     | [03c69f44e3](https://linux-hardware.org/?probe=03c69f44e3) | Jul 12, 2021 |
| Gigabyte      | Z77X-D3H                    | [5416b8d0da](https://linux-hardware.org/?probe=5416b8d0da) | Jul 10, 2021 |
| ASUSTek       | ROG STRIX Z590-A GAMING ... | [252d84e173](https://linux-hardware.org/?probe=252d84e173) | Jul 05, 2021 |
| MSI           | Boston                      | [72f1bfa2f0](https://linux-hardware.org/?probe=72f1bfa2f0) | Jul 05, 2021 |
| MSI           | Boston                      | [ff82275c70](https://linux-hardware.org/?probe=ff82275c70) | Jul 04, 2021 |
| ASRock        | J4105M                      | [b732da09a3](https://linux-hardware.org/?probe=b732da09a3) | Jul 04, 2021 |
| ASRock        | J4105M                      | [a2d5afa1d6](https://linux-hardware.org/?probe=a2d5afa1d6) | Jul 04, 2021 |
| Gigabyte      | F2A78M-HD2                  | [7974efd1a4](https://linux-hardware.org/?probe=7974efd1a4) | Jul 03, 2021 |
| Dell          | 0M863N A00                  | [a505e284ec](https://linux-hardware.org/?probe=a505e284ec) | Jun 27, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | [1e4e8c8638](https://linux-hardware.org/?probe=1e4e8c8638) | Jun 27, 2021 |
| Lenovo        | ThinkStation D20 4158CM1    | [004bd0bb8e](https://linux-hardware.org/?probe=004bd0bb8e) | Jun 26, 2021 |
| HP            | 18E5                        | [9081019c28](https://linux-hardware.org/?probe=9081019c28) | Jun 24, 2021 |
| Gigabyte      | B450M DS3H-CF               | [c40b02d888](https://linux-hardware.org/?probe=c40b02d888) | Jun 24, 2021 |
| HP            | 0AA8h                       | [8de391044c](https://linux-hardware.org/?probe=8de391044c) | Jun 24, 2021 |
| HP            | 0AA8h                       | [a477bc402f](https://linux-hardware.org/?probe=a477bc402f) | Jun 24, 2021 |
| MSI           | MPG X570 GAMING PRO CARB... | [f697fb056b](https://linux-hardware.org/?probe=f697fb056b) | Jun 24, 2021 |
| MSI           | B350M PRO-VDH               | [c1009474e9](https://linux-hardware.org/?probe=c1009474e9) | Jun 21, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | [d2519fe6fd](https://linux-hardware.org/?probe=d2519fe6fd) | Jun 21, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [d5ebc8bdc6](https://linux-hardware.org/?probe=d5ebc8bdc6) | Jun 18, 2021 |
| Dell          | 0WG855                      | [02b09ef628](https://linux-hardware.org/?probe=02b09ef628) | Jun 17, 2021 |
| Dell          | 0WR7PY A02                  | [fb27aaebe4](https://linux-hardware.org/?probe=fb27aaebe4) | Jun 15, 2021 |
| MSI           | B350M PRO-VDH               | [36e3984e75](https://linux-hardware.org/?probe=36e3984e75) | Jun 15, 2021 |
| MSI           | B350M PRO-VDH               | [b2d3b7546a](https://linux-hardware.org/?probe=b2d3b7546a) | Jun 15, 2021 |
| Gigabyte      | H55M-USB3                   | [3372e4c0ab](https://linux-hardware.org/?probe=3372e4c0ab) | Jun 14, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [1357359d3f](https://linux-hardware.org/?probe=1357359d3f) | Jun 13, 2021 |
| HP            | 1589                        | [531fd7a206](https://linux-hardware.org/?probe=531fd7a206) | Jun 12, 2021 |
| ASRock        | X300M-STX                   | [fd6970af13](https://linux-hardware.org/?probe=fd6970af13) | Jun 12, 2021 |
| Gigabyte      | B450M DS3H-CF               | [28cc50b8af](https://linux-hardware.org/?probe=28cc50b8af) | Jun 11, 2021 |
| Gigabyte      | H81M-D2W                    | [a5cf29d3fa](https://linux-hardware.org/?probe=a5cf29d3fa) | Jun 11, 2021 |
| ASUSTek       | Z170 PRO GAMING/AURA        | [6b3ad983d3](https://linux-hardware.org/?probe=6b3ad983d3) | Jun 11, 2021 |
| Packard Be... | WMCP78M                     | [c267385b22](https://linux-hardware.org/?probe=c267385b22) | Jun 11, 2021 |
| Dell          | 0MWYPT A01                  | [fb7b10919d](https://linux-hardware.org/?probe=fb7b10919d) | Jun 09, 2021 |
| Gigabyte      | 945PL-S3                    | [885dc78ef1](https://linux-hardware.org/?probe=885dc78ef1) | Jun 08, 2021 |
| Gateway       | SX2185                      | [541a86ceb1](https://linux-hardware.org/?probe=541a86ceb1) | Jun 08, 2021 |
| Intel         | H61                         | [50b0503c3c](https://linux-hardware.org/?probe=50b0503c3c) | Jun 07, 2021 |
| Gigabyte      | X58A-UD3R                   | [216d963387](https://linux-hardware.org/?probe=216d963387) | Jun 05, 2021 |
| MSI           | X99A SLI Krait Edition      | [f9626d011c](https://linux-hardware.org/?probe=f9626d011c) | Jun 05, 2021 |
| ASRock        | A320M-DVS R4.0              | [4ce3673d2d](https://linux-hardware.org/?probe=4ce3673d2d) | Jun 04, 2021 |
| Lenovo        | ThinkCentre A70 7844H9G     | [8684efd5c9](https://linux-hardware.org/?probe=8684efd5c9) | Jun 04, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [5dbe42cf75](https://linux-hardware.org/?probe=5dbe42cf75) | Jun 03, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [07eb1feeb4](https://linux-hardware.org/?probe=07eb1feeb4) | Jun 03, 2021 |
| HP            | 3032h                       | [dade0cb1d6](https://linux-hardware.org/?probe=dade0cb1d6) | Jun 03, 2021 |
| Packard Be... | imedia S2110A               | [34a921fd71](https://linux-hardware.org/?probe=34a921fd71) | Jun 03, 2021 |
| QTQD          | Board                       | [f7d66120da](https://linux-hardware.org/?probe=f7d66120da) | Jun 01, 2021 |
| Intel         | DH61WW AAG23116-204         | [5b590117dd](https://linux-hardware.org/?probe=5b590117dd) | Jun 01, 2021 |
| MSI           | B250M PRO-VD                | [c90bb6eca1](https://linux-hardware.org/?probe=c90bb6eca1) | May 31, 2021 |
| HP            | 3032h                       | [ea009f77d1](https://linux-hardware.org/?probe=ea009f77d1) | May 31, 2021 |
| NCR           | Pocono                      | [73bfada83a](https://linux-hardware.org/?probe=73bfada83a) | May 30, 2021 |
| Intel         | DH61WW AAG23116-204         | [f109707413](https://linux-hardware.org/?probe=f109707413) | May 29, 2021 |
| MSI           | A68HM-E33 V2                | [a9971ed939](https://linux-hardware.org/?probe=a9971ed939) | May 29, 2021 |
| HP            | 18E7                        | [dbb0731dd9](https://linux-hardware.org/?probe=dbb0731dd9) | May 27, 2021 |
| Medion        | H110H4-EM                   | [09ca813f06](https://linux-hardware.org/?probe=09ca813f06) | May 25, 2021 |
| ASRock        | H110M-ITX/ac                | [f03f0287f4](https://linux-hardware.org/?probe=f03f0287f4) | May 24, 2021 |
| ECS           | H61H2-M2                    | [a6e86907bf](https://linux-hardware.org/?probe=a6e86907bf) | May 22, 2021 |
| ASUSTek       | A68HM-K                     | [d62c1cc4aa](https://linux-hardware.org/?probe=d62c1cc4aa) | May 22, 2021 |
| Acer          | H57M01                      | [8b9e2fb5f2](https://linux-hardware.org/?probe=8b9e2fb5f2) | May 19, 2021 |
| Fujitsu       | D3091-A1 S26361-D3091-A1    | [21bb7408e3](https://linux-hardware.org/?probe=21bb7408e3) | May 18, 2021 |
| Pegatron      | NARRA3                      | [38ac9a9ea6](https://linux-hardware.org/?probe=38ac9a9ea6) | May 18, 2021 |
| Gigabyte      | C847N                       | [7a17d8efef](https://linux-hardware.org/?probe=7a17d8efef) | May 17, 2021 |
| Gigabyte      | C847N                       | [deb3c6a79f](https://linux-hardware.org/?probe=deb3c6a79f) | May 17, 2021 |
| Acer          | H57M01                      | [a80686767d](https://linux-hardware.org/?probe=a80686767d) | May 16, 2021 |
| Intel         | BTC-T37                     | [dcfc697c0a](https://linux-hardware.org/?probe=dcfc697c0a) | May 16, 2021 |
| Acer          | H57M01                      | [9648df97b7](https://linux-hardware.org/?probe=9648df97b7) | May 15, 2021 |
| Lenovo        | MAHOBAY                     | [0299025f98](https://linux-hardware.org/?probe=0299025f98) | May 15, 2021 |
| Acer          | TPDS05 R3700                | [9abf1ed283](https://linux-hardware.org/?probe=9abf1ed283) | May 15, 2021 |
| Gigabyte      | A320M-S2H-CF                | [48f873b6de](https://linux-hardware.org/?probe=48f873b6de) | May 14, 2021 |
| MSI           | B450-A PRO MAX              | [7b40989bc7](https://linux-hardware.org/?probe=7b40989bc7) | May 13, 2021 |
| MSI           | B450-A PRO MAX              | [acff281d6b](https://linux-hardware.org/?probe=acff281d6b) | May 12, 2021 |
| Gigabyte      | EP45-UD3R                   | [25abeee3ef](https://linux-hardware.org/?probe=25abeee3ef) | May 12, 2021 |
| Gigabyte      | A320M-S2H-CF                | [a3f9e2334a](https://linux-hardware.org/?probe=a3f9e2334a) | May 11, 2021 |
| Gigabyte      | A320M-S2H-CF                | [4033e8e77e](https://linux-hardware.org/?probe=4033e8e77e) | May 11, 2021 |
| Dell          | 0CU409                      | [151b11acfc](https://linux-hardware.org/?probe=151b11acfc) | May 11, 2021 |
| Dell          | 0CU409                      | [3ea181ca1b](https://linux-hardware.org/?probe=3ea181ca1b) | May 10, 2021 |
| Acer          | H57M01                      | [40e56381c8](https://linux-hardware.org/?probe=40e56381c8) | May 10, 2021 |
| Medion        | H110H4-CM2                  | [c622bcf1bb](https://linux-hardware.org/?probe=c622bcf1bb) | May 09, 2021 |
| Acer          | H57M01                      | [ec79128c45](https://linux-hardware.org/?probe=ec79128c45) | May 09, 2021 |
| Gigabyte      | A520I AC                    | [eb32404ebf](https://linux-hardware.org/?probe=eb32404ebf) | May 07, 2021 |
| Lenovo        | ThinkStation D30 4223B35    | [e3c6a7b793](https://linux-hardware.org/?probe=e3c6a7b793) | May 06, 2021 |
| Gigabyte      | H110N-CF                    | [d03c007deb](https://linux-hardware.org/?probe=d03c007deb) | May 06, 2021 |
| HP            | 2B05                        | [0bfbf859ca](https://linux-hardware.org/?probe=0bfbf859ca) | May 05, 2021 |
| Huanan        | X58-RX3.0 V111              | [5181d65714](https://linux-hardware.org/?probe=5181d65714) | May 04, 2021 |
| ASUSTek       | PRIME X570-PRO              | [e1b742d511](https://linux-hardware.org/?probe=e1b742d511) | May 04, 2021 |
| HP            | 198E                        | [396de7f15d](https://linux-hardware.org/?probe=396de7f15d) | May 03, 2021 |
| Gigabyte      | H81M-DS2                    | [747c5516a4](https://linux-hardware.org/?probe=747c5516a4) | May 03, 2021 |
| Dell          | 02YRK5 A02                  | [0ff2e7f046](https://linux-hardware.org/?probe=0ff2e7f046) | May 02, 2021 |
| MSI           | Z490M-S01                   | [b2de3af507](https://linux-hardware.org/?probe=b2de3af507) | May 02, 2021 |
| Foxconn       | H67M-S/H67M-V/H67           | [f22a2df347](https://linux-hardware.org/?probe=f22a2df347) | May 01, 2021 |
| HP            | 158A                        | [2fac0fa486](https://linux-hardware.org/?probe=2fac0fa486) | May 01, 2021 |
| Gigabyte      | A320M-S2H-CF                | [0deafa542c](https://linux-hardware.org/?probe=0deafa542c) | Apr 29, 2021 |
| Foxconn       | 2AB1h                       | [e4a4169db1](https://linux-hardware.org/?probe=e4a4169db1) | Apr 29, 2021 |
| Gigabyte      | A320M-S2H-CF                | [04d81bb2f6](https://linux-hardware.org/?probe=04d81bb2f6) | Apr 29, 2021 |
| MSI           | Boston                      | [5cca21c281](https://linux-hardware.org/?probe=5cca21c281) | Apr 26, 2021 |
| Acer          | FC51GM                      | [ace5e495f5](https://linux-hardware.org/?probe=ace5e495f5) | Apr 26, 2021 |
| HP            | 21B4 A01                    | [9193163279](https://linux-hardware.org/?probe=9193163279) | Apr 26, 2021 |
| ASUSTek       | H87M-PLUS                   | [7ecfe05882](https://linux-hardware.org/?probe=7ecfe05882) | Apr 25, 2021 |
| Gigabyte      | Z68MA-D2H-B3                | [f6e266a897](https://linux-hardware.org/?probe=f6e266a897) | Apr 25, 2021 |
| ASRock        | Z170 Gaming K4              | [69ec5d246b](https://linux-hardware.org/?probe=69ec5d246b) | Apr 25, 2021 |
| ASRock        | N68-VS3 FX                  | [b92a431094](https://linux-hardware.org/?probe=b92a431094) | Apr 24, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [ef264215af](https://linux-hardware.org/?probe=ef264215af) | Apr 24, 2021 |
| Intel         | DH61WW AAG23116-203         | [32aae9ea9a](https://linux-hardware.org/?probe=32aae9ea9a) | Apr 24, 2021 |
| HP            | 339A                        | [ed44deea1a](https://linux-hardware.org/?probe=ed44deea1a) | Apr 21, 2021 |
| Lenovo        | ThinkCentre A70 7844H9G     | [2517cbf080](https://linux-hardware.org/?probe=2517cbf080) | Apr 20, 2021 |
| MSI           | 770-G45                     | [85ebceeb24](https://linux-hardware.org/?probe=85ebceeb24) | Apr 20, 2021 |
| Dell          | 0M5DCD A02                  | [ef0ddc38ce](https://linux-hardware.org/?probe=ef0ddc38ce) | Apr 19, 2021 |
| Dell          | 0KRC95 A03                  | [61da77da82](https://linux-hardware.org/?probe=61da77da82) | Apr 18, 2021 |
| HP            | 3047h                       | [c426bd5393](https://linux-hardware.org/?probe=c426bd5393) | Apr 18, 2021 |
| Huanan        | X58-RX3.0 V111              | [52841d2dbf](https://linux-hardware.org/?probe=52841d2dbf) | Apr 17, 2021 |
| HP            | ML110 G4                    | [443a299302](https://linux-hardware.org/?probe=443a299302) | Apr 17, 2021 |
| Dell          | 0M5DCD A02                  | [91f1b586b4](https://linux-hardware.org/?probe=91f1b586b4) | Apr 16, 2021 |
| Acer          | TPDS05 R3700                | [4c7b9482f3](https://linux-hardware.org/?probe=4c7b9482f3) | Apr 15, 2021 |
| ASUSTek       | P8P67 EVO                   | [5e98e0ae38](https://linux-hardware.org/?probe=5e98e0ae38) | Apr 14, 2021 |
| Pegatron      | 2AC2A                       | [87fa4f3888](https://linux-hardware.org/?probe=87fa4f3888) | Apr 13, 2021 |
| ASUSTek       | AM1I-A                      | [6c2469b32a](https://linux-hardware.org/?probe=6c2469b32a) | Apr 11, 2021 |
| Acer          | Aspire X1430                | [b3b59b7e37](https://linux-hardware.org/?probe=b3b59b7e37) | Apr 11, 2021 |
| ASUSTek       | AM1I-A                      | [56f187f014](https://linux-hardware.org/?probe=56f187f014) | Apr 11, 2021 |
| ASRock        | H270M-ITX/ac                | [071ce283c1](https://linux-hardware.org/?probe=071ce283c1) | Apr 11, 2021 |
| ASRock        | H270M-ITX/ac                | [73cf10f10a](https://linux-hardware.org/?probe=73cf10f10a) | Apr 11, 2021 |
| ASRock        | B450M/ac                    | [ef79828d94](https://linux-hardware.org/?probe=ef79828d94) | Apr 11, 2021 |
| Dell          | 0GM819                      | [95f4b4a653](https://linux-hardware.org/?probe=95f4b4a653) | Apr 10, 2021 |
| Gigabyte      | X99-UD4-CF                  | [2189f9be68](https://linux-hardware.org/?probe=2189f9be68) | Apr 10, 2021 |
| ASRock        | B450 Pro4                   | [e97c041e12](https://linux-hardware.org/?probe=e97c041e12) | Apr 10, 2021 |
| MSI           | 970A-G43                    | [4618a9eef4](https://linux-hardware.org/?probe=4618a9eef4) | Apr 09, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [cb6c7d5ecb](https://linux-hardware.org/?probe=cb6c7d5ecb) | Apr 09, 2021 |
| ASUSTek       | P5VD2-VM SE                 | [922a324d57](https://linux-hardware.org/?probe=922a324d57) | Apr 09, 2021 |
| HP            | EG157AA-ABF m1260.fr        | [cf4f87aefd](https://linux-hardware.org/?probe=cf4f87aefd) | Apr 08, 2021 |
| MSI           | B75A-G43                    | [87a3e8d42c](https://linux-hardware.org/?probe=87a3e8d42c) | Apr 07, 2021 |
| Gigabyte      | B450M DS3H-CF               | [a66003eab5](https://linux-hardware.org/?probe=a66003eab5) | Apr 05, 2021 |
| Gigabyte      | H270-HD3-CF                 | [987824d49a](https://linux-hardware.org/?probe=987824d49a) | Apr 05, 2021 |
| Biostar       | TB250-BTC                   | [a1b3b845a7](https://linux-hardware.org/?probe=a1b3b845a7) | Apr 05, 2021 |
| Biostar       | TB250-BTC                   | [908171f266](https://linux-hardware.org/?probe=908171f266) | Apr 05, 2021 |
| ASUSTek       | B150I PRO GAMING/AURA       | [b33866b71b](https://linux-hardware.org/?probe=b33866b71b) | Apr 03, 2021 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | [817d1bb360](https://linux-hardware.org/?probe=817d1bb360) | Apr 03, 2021 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | [ca1692012f](https://linux-hardware.org/?probe=ca1692012f) | Apr 03, 2021 |
| Foxconn       | 2ABF                        | [9414f40cf2](https://linux-hardware.org/?probe=9414f40cf2) | Apr 03, 2021 |
| Gigabyte      | 990FXA-UD3                  | [327a4888d5](https://linux-hardware.org/?probe=327a4888d5) | Apr 03, 2021 |
| Fujitsu       | D3654-C1 S26361-D3654-C1    | [4cd56bcfa1](https://linux-hardware.org/?probe=4cd56bcfa1) | Apr 02, 2021 |
| Lenovo        | ThinkCentre A70 7844H9G     | [8643a89256](https://linux-hardware.org/?probe=8643a89256) | Apr 01, 2021 |
| ASUSTek       | P8H61                       | [cb9797346b](https://linux-hardware.org/?probe=cb9797346b) | Mar 30, 2021 |
| Huanan        | X58-RX3.0 V111              | [c18bd3abe8](https://linux-hardware.org/?probe=c18bd3abe8) | Mar 30, 2021 |
| ASRock        | K10N78D                     | [500f4c7c38](https://linux-hardware.org/?probe=500f4c7c38) | Mar 29, 2021 |
| ASUSTek       | P5KC                        | [0f3e839c63](https://linux-hardware.org/?probe=0f3e839c63) | Mar 29, 2021 |
| ASUSTek       | A68HM-K                     | [ef5acde9af](https://linux-hardware.org/?probe=ef5acde9af) | Mar 28, 2021 |
| eMachines     | EL1850                      | [7c2d95778c](https://linux-hardware.org/?probe=7c2d95778c) | Mar 27, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [47323e14e8](https://linux-hardware.org/?probe=47323e14e8) | Mar 26, 2021 |
| ASUSTek       | P8Z68 DELUXE                | [8ce30ac5a9](https://linux-hardware.org/?probe=8ce30ac5a9) | Mar 26, 2021 |
| HP            | 3646h                       | [b529769ddc](https://linux-hardware.org/?probe=b529769ddc) | Mar 25, 2021 |
| ASUSTek       | P5KC                        | [0d1ffacb54](https://linux-hardware.org/?probe=0d1ffacb54) | Mar 24, 2021 |
| Gigabyte      | F2A78M-HD2                  | [5ccc7045e0](https://linux-hardware.org/?probe=5ccc7045e0) | Mar 23, 2021 |
| Gigabyte      | Z97X-Gaming 3               | [56e94aaad4](https://linux-hardware.org/?probe=56e94aaad4) | Mar 23, 2021 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | [ca09a97564](https://linux-hardware.org/?probe=ca09a97564) | Mar 23, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [7b7a266de6](https://linux-hardware.org/?probe=7b7a266de6) | Mar 22, 2021 |
| AAEON         | GENE-APL5 V1.0              | [ee93b490f0](https://linux-hardware.org/?probe=ee93b490f0) | Mar 22, 2021 |
| Lenovo        | ThinkCentre A70 7844H9G     | [070c4000e1](https://linux-hardware.org/?probe=070c4000e1) | Mar 22, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [4af21b4682](https://linux-hardware.org/?probe=4af21b4682) | Mar 20, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [f2c6db22bc](https://linux-hardware.org/?probe=f2c6db22bc) | Mar 19, 2021 |
| Gigabyte      | B450M S2H                   | [deb06f914c](https://linux-hardware.org/?probe=deb06f914c) | Mar 19, 2021 |
| MSI           | Z97-G43                     | [984145ba36](https://linux-hardware.org/?probe=984145ba36) | Mar 18, 2021 |
| ASRock        | AB350M Pro4 R2.0            | [d5ddb563ac](https://linux-hardware.org/?probe=d5ddb563ac) | Mar 18, 2021 |
| ASRock        | AB350M Pro4 R2.0            | [af9b948ec2](https://linux-hardware.org/?probe=af9b948ec2) | Mar 17, 2021 |
| Intel         | X99                         | [eff3e65d6d](https://linux-hardware.org/?probe=eff3e65d6d) | Mar 17, 2021 |
| ASUSTek       | M4A78 PRO                   | [0d75059dc8](https://linux-hardware.org/?probe=0d75059dc8) | Mar 17, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [7cc0dfac27](https://linux-hardware.org/?probe=7cc0dfac27) | Mar 17, 2021 |
| Intel         | X99                         | [1f84949851](https://linux-hardware.org/?probe=1f84949851) | Mar 17, 2021 |
| MSI           | A88XM-E45                   | [96048dac39](https://linux-hardware.org/?probe=96048dac39) | Mar 17, 2021 |
| HP            | 2B17                        | [753cbbeb9e](https://linux-hardware.org/?probe=753cbbeb9e) | Mar 16, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [d9155d61f2](https://linux-hardware.org/?probe=d9155d61f2) | Mar 15, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [f96e12d97e](https://linux-hardware.org/?probe=f96e12d97e) | Mar 15, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [d9f29b65da](https://linux-hardware.org/?probe=d9f29b65da) | Mar 15, 2021 |
| ASRock        | B450 Pro4                   | [eb6c19a371](https://linux-hardware.org/?probe=eb6c19a371) | Mar 14, 2021 |
| ASRock        | FM2A88X-ITX+                | [7a38886add](https://linux-hardware.org/?probe=7a38886add) | Mar 14, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [7def74a79a](https://linux-hardware.org/?probe=7def74a79a) | Mar 13, 2021 |
| Dell          | 0T656F A02                  | [708eb1bf51](https://linux-hardware.org/?probe=708eb1bf51) | Mar 13, 2021 |
| HP            | 339A                        | [355b85c060](https://linux-hardware.org/?probe=355b85c060) | Mar 13, 2021 |
| Medion        | H110H4-EM                   | [c0f324b6aa](https://linux-hardware.org/?probe=c0f324b6aa) | Mar 13, 2021 |
| HP            | 18E7                        | [c0793d8023](https://linux-hardware.org/?probe=c0793d8023) | Mar 13, 2021 |
| HP            | 339A                        | [a24b4dd571](https://linux-hardware.org/?probe=a24b4dd571) | Mar 13, 2021 |
| ASUSTek       | P5KC                        | [d20831473f](https://linux-hardware.org/?probe=d20831473f) | Mar 12, 2021 |
| HP            | 212B                        | [6afcf12073](https://linux-hardware.org/?probe=6afcf12073) | Mar 12, 2021 |
| Dell          | 0T656F A02                  | [cc36a18a02](https://linux-hardware.org/?probe=cc36a18a02) | Mar 12, 2021 |
| Acer          | Aspire TC-780               | [5ac5e5625a](https://linux-hardware.org/?probe=5ac5e5625a) | Mar 12, 2021 |
| MSI           | B450M MORTAR MAX            | [a4da5e59df](https://linux-hardware.org/?probe=a4da5e59df) | Mar 11, 2021 |
| ASUSTek       | PRIME H310M-D R2.0          | [5f4e258cd5](https://linux-hardware.org/?probe=5f4e258cd5) | Mar 11, 2021 |
| Gigabyte      | B450M DS3H-CF               | [0d5694c1b3](https://linux-hardware.org/?probe=0d5694c1b3) | Mar 10, 2021 |
| ASUSTek       | P5K Premium                 | [868aaae2fd](https://linux-hardware.org/?probe=868aaae2fd) | Mar 09, 2021 |
| HP            | 21B4 A01                    | [1b6837c321](https://linux-hardware.org/?probe=1b6837c321) | Mar 08, 2021 |
| HP            | 339A                        | [dd14e6b8f8](https://linux-hardware.org/?probe=dd14e6b8f8) | Mar 08, 2021 |
| Gigabyte      | 970-GAMING                  | [f05a49c047](https://linux-hardware.org/?probe=f05a49c047) | Mar 08, 2021 |
| ASUSTek       | P5K Premium                 | [551f3363c1](https://linux-hardware.org/?probe=551f3363c1) | Mar 07, 2021 |
| HP            | 212B                        | [acee068006](https://linux-hardware.org/?probe=acee068006) | Mar 06, 2021 |
| ASUSTek       | P5KPL-AM/PS                 | [32e4837219](https://linux-hardware.org/?probe=32e4837219) | Mar 05, 2021 |
| ASUSTek       | M2N68-AM Plus               | [18268633d9](https://linux-hardware.org/?probe=18268633d9) | Mar 03, 2021 |
| ASUSTek       | M2N68-AM Plus               | [c4e5bc819d](https://linux-hardware.org/?probe=c4e5bc819d) | Mar 02, 2021 |
| ASUSTek       | P5KC                        | [b10d594dac](https://linux-hardware.org/?probe=b10d594dac) | Mar 02, 2021 |
| Gigabyte      | A320M-H-CF                  | [bfa3a17409](https://linux-hardware.org/?probe=bfa3a17409) | Mar 02, 2021 |
| Gigabyte      | A320M-H-CF                  | [4b9649e87e](https://linux-hardware.org/?probe=4b9649e87e) | Mar 02, 2021 |
| Gigabyte      | M61PME-S2P                  | [39f661106f](https://linux-hardware.org/?probe=39f661106f) | Mar 01, 2021 |
| Unknown       | Intel X79                   | [85e2bda5cc](https://linux-hardware.org/?probe=85e2bda5cc) | Feb 28, 2021 |
| Unknown       | Intel X79                   | [cbe66f456c](https://linux-hardware.org/?probe=cbe66f456c) | Feb 28, 2021 |
| Acer          | Veriton X2611G V1.0         | [0f52aff29d](https://linux-hardware.org/?probe=0f52aff29d) | Feb 27, 2021 |
| ASRock        | A320M-HDV R4.0              | [9057e2fabf](https://linux-hardware.org/?probe=9057e2fabf) | Feb 27, 2021 |
| Acer          | Veriton X2611G V1.0         | [ba907b59a6](https://linux-hardware.org/?probe=ba907b59a6) | Feb 27, 2021 |
| Gigabyte      | F2A78M-HD2                  | [fe1c2fef81](https://linux-hardware.org/?probe=fe1c2fef81) | Feb 26, 2021 |
| ASUSTek       | Rampage V EXTREME           | [8912ddde77](https://linux-hardware.org/?probe=8912ddde77) | Feb 23, 2021 |
| ASUSTek       | P5K                         | [26b7e4d025](https://linux-hardware.org/?probe=26b7e4d025) | Feb 22, 2021 |
| Gigabyte      | F2A78M-HD2                  | [d171438f90](https://linux-hardware.org/?probe=d171438f90) | Feb 21, 2021 |
| Intel         | DP55WB AAE64798-204         | [6e9ac2a13d](https://linux-hardware.org/?probe=6e9ac2a13d) | Feb 20, 2021 |
| ASUSTek       | A4110                       | [26905e1ebd](https://linux-hardware.org/?probe=26905e1ebd) | Feb 19, 2021 |
| eMachines     | WMCP61M                     | [087382e171](https://linux-hardware.org/?probe=087382e171) | Feb 18, 2021 |
| eMachines     | WMCP61M                     | [a1a77aa715](https://linux-hardware.org/?probe=a1a77aa715) | Feb 18, 2021 |
| ASUSTek       | M5A78L/USB3                 | [10ee841597](https://linux-hardware.org/?probe=10ee841597) | Feb 17, 2021 |
| Biostar       | H61MLC                      | [be5a5130e5](https://linux-hardware.org/?probe=be5a5130e5) | Feb 17, 2021 |
| Gigabyte      | M68MT-S2P                   | [74f31779a2](https://linux-hardware.org/?probe=74f31779a2) | Feb 15, 2021 |
| Seco          | C40 C                       | [1d98beaf5d](https://linux-hardware.org/?probe=1d98beaf5d) | Feb 14, 2021 |
| ASUSTek       | M2N68-AM SE2                | [4679546f16](https://linux-hardware.org/?probe=4679546f16) | Feb 14, 2021 |
| Dell          | 0C27VV A01                  | [bd2590461c](https://linux-hardware.org/?probe=bd2590461c) | Feb 13, 2021 |
| Gateway       | SX2185                      | [650152fe14](https://linux-hardware.org/?probe=650152fe14) | Feb 12, 2021 |
| MSI           | Z87-G45 GAMING              | [232dc2ff7f](https://linux-hardware.org/?probe=232dc2ff7f) | Feb 09, 2021 |
| Lenovo        | Board                       | [1ac9efa4af](https://linux-hardware.org/?probe=1ac9efa4af) | Feb 08, 2021 |
| ASRock        | N68C-S UCC                  | [c35f0c5e8f](https://linux-hardware.org/?probe=c35f0c5e8f) | Feb 08, 2021 |
| Gigabyte      | B85M-HD3                    | [d4efd5185b](https://linux-hardware.org/?probe=d4efd5185b) | Feb 08, 2021 |
| MSI           | X470 GAMING PLUS            | [5e431277e8](https://linux-hardware.org/?probe=5e431277e8) | Feb 08, 2021 |
| MSI           | X470 GAMING PLUS            | [f487bd28cd](https://linux-hardware.org/?probe=f487bd28cd) | Feb 07, 2021 |
| ASUSTek       | P5G41-M LE                  | [760db7896e](https://linux-hardware.org/?probe=760db7896e) | Feb 07, 2021 |
| ASUSTek       | P5KPL-AM/PS                 | [da10acb66c](https://linux-hardware.org/?probe=da10acb66c) | Feb 07, 2021 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [67b240fcfb](https://linux-hardware.org/?probe=67b240fcfb) | Feb 06, 2021 |
| Dell          | 0C2KJT A00                  | [cf78c04cc2](https://linux-hardware.org/?probe=cf78c04cc2) | Feb 06, 2021 |
| Dell          | 0C2KJT A00                  | [aeb4ab8839](https://linux-hardware.org/?probe=aeb4ab8839) | Feb 06, 2021 |
| ASUSTek       | P5VD2-MX                    | [f0f594baaf](https://linux-hardware.org/?probe=f0f594baaf) | Feb 04, 2021 |
| ASRock        | HM87-MXM                    | [95efd1e9a2](https://linux-hardware.org/?probe=95efd1e9a2) | Feb 04, 2021 |
| Apple         | Mac-F221BEC8                | [04273ebc86](https://linux-hardware.org/?probe=04273ebc86) | Feb 04, 2021 |
| Gigabyte      | EP45-UD3LR                  | [a3dadb268d](https://linux-hardware.org/?probe=a3dadb268d) | Feb 03, 2021 |
| AMI           | Cherry Trail CR             | [61c97edba3](https://linux-hardware.org/?probe=61c97edba3) | Feb 03, 2021 |
| Gigabyte      | F2A78M-HD2                  | [e0d27f7d08](https://linux-hardware.org/?probe=e0d27f7d08) | Feb 01, 2021 |
| HP            | 1589                        | [9f0f12f814](https://linux-hardware.org/?probe=9f0f12f814) | Jan 31, 2021 |
| Packard Be... | imedia S3840                | [c0a7dff96d](https://linux-hardware.org/?probe=c0a7dff96d) | Jan 31, 2021 |
| Gigabyte      | GA-780T-D3L                 | [e745405951](https://linux-hardware.org/?probe=e745405951) | Jan 29, 2021 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | [193f9e8bab](https://linux-hardware.org/?probe=193f9e8bab) | Jan 28, 2021 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | [c0dd8179cd](https://linux-hardware.org/?probe=c0dd8179cd) | Jan 28, 2021 |
| HP            | 18E5                        | [2a72f13e4c](https://linux-hardware.org/?probe=2a72f13e4c) | Jan 27, 2021 |
| Gigabyte      | F2A75M-HD2                  | [66c8d532cc](https://linux-hardware.org/?probe=66c8d532cc) | Jan 26, 2021 |
| Gigabyte      | F2A75M-HD2                  | [068a50df4d](https://linux-hardware.org/?probe=068a50df4d) | Jan 26, 2021 |
| ASRock        | B450 Pro4                   | [ffcfe53f7d](https://linux-hardware.org/?probe=ffcfe53f7d) | Jan 26, 2021 |
| ASRock        | B450 Pro4                   | [b78244d995](https://linux-hardware.org/?probe=b78244d995) | Jan 26, 2021 |
| NEC Comput... | IS8XM                       | [5ef77bc965](https://linux-hardware.org/?probe=5ef77bc965) | Jan 25, 2021 |
| NEC Comput... | IS8XM                       | [c215122b86](https://linux-hardware.org/?probe=c215122b86) | Jan 25, 2021 |
| NCR           | Pocono                      | [8bd94573e3](https://linux-hardware.org/?probe=8bd94573e3) | Jan 25, 2021 |
| Gigabyte      | GA-MA770-DS3                | [c9af16a580](https://linux-hardware.org/?probe=c9af16a580) | Jan 24, 2021 |
| Gigabyte      | X99-UD4-CF                  | [27d1050290](https://linux-hardware.org/?probe=27d1050290) | Jan 24, 2021 |
| HP            | 2AFE                        | [f9e753f06a](https://linux-hardware.org/?probe=f9e753f06a) | Jan 23, 2021 |
| MSI           | B85-G43                     | [4955170f6b](https://linux-hardware.org/?probe=4955170f6b) | Jan 23, 2021 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [a16e38020e](https://linux-hardware.org/?probe=a16e38020e) | Jan 23, 2021 |
| ASUSTek       | PRIME X470-PRO              | [bf6fd8e5ac](https://linux-hardware.org/?probe=bf6fd8e5ac) | Jan 22, 2021 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [2f3b56a94e](https://linux-hardware.org/?probe=2f3b56a94e) | Jan 22, 2021 |
| MSI           | G41TM-E43                   | [2d830938bf](https://linux-hardware.org/?probe=2d830938bf) | Jan 21, 2021 |
| ASUSTek       | Z97-PRO GAMER               | [79ea9e0ea5](https://linux-hardware.org/?probe=79ea9e0ea5) | Jan 21, 2021 |
| ASUSTek       | P8Z77-V LX                  | [8d943aea44](https://linux-hardware.org/?probe=8d943aea44) | Jan 21, 2021 |
| Dell          | 0D28YY A03                  | [e74dbb590d](https://linux-hardware.org/?probe=e74dbb590d) | Jan 21, 2021 |
| ASUSTek       | P8H61-MX USB3               | [5f6d7de9fe](https://linux-hardware.org/?probe=5f6d7de9fe) | Jan 20, 2021 |
| Dell          | 033FF6 A00                  | [37d767af07](https://linux-hardware.org/?probe=37d767af07) | Jan 20, 2021 |
| Intel         | DG31GL AAE33912-200         | [14491b53d7](https://linux-hardware.org/?probe=14491b53d7) | Jan 20, 2021 |
| Lenovo        | 30BE SDK0J40697 WIN 3305... | [cd75d76c4a](https://linux-hardware.org/?probe=cd75d76c4a) | Jan 19, 2021 |
| HP            | 18E5                        | [5af2f3397e](https://linux-hardware.org/?probe=5af2f3397e) | Jan 17, 2021 |
| ASL           | Fusion JHS652               | [446053ce45](https://linux-hardware.org/?probe=446053ce45) | Jan 17, 2021 |
| Google        | Zako                        | [dec016baf8](https://linux-hardware.org/?probe=dec016baf8) | Jan 17, 2021 |
| Dell          | 07PR60 A01                  | [c28e9c99eb](https://linux-hardware.org/?probe=c28e9c99eb) | Jan 17, 2021 |
| Dell          | 07PR60 A01                  | [d97f00549e](https://linux-hardware.org/?probe=d97f00549e) | Jan 17, 2021 |
| Foxconn       | 2AB1h                       | [22d2a8fbf1](https://linux-hardware.org/?probe=22d2a8fbf1) | Jan 16, 2021 |
| HP            | 18E5                        | [bdf60e9cde](https://linux-hardware.org/?probe=bdf60e9cde) | Jan 16, 2021 |
| Foxconn       | 2AB1h                       | [fb2271744d](https://linux-hardware.org/?probe=fb2271744d) | Jan 16, 2021 |
| ASUSTek       | P8H61-M LX2                 | [81d37f44c6](https://linux-hardware.org/?probe=81d37f44c6) | Jan 16, 2021 |
| Acer          | Aspire XC-602 V1.0          | [f9111a7765](https://linux-hardware.org/?probe=f9111a7765) | Jan 16, 2021 |
| HP            | 2129                        | [449a9223a3](https://linux-hardware.org/?probe=449a9223a3) | Jan 15, 2021 |
| ASUSTek       | P8H61-M LX2                 | [3e9c7bed90](https://linux-hardware.org/?probe=3e9c7bed90) | Jan 13, 2021 |
| Intel         | DQ965GF AAD41676-402        | [2e9a342427](https://linux-hardware.org/?probe=2e9a342427) | Jan 13, 2021 |
| ASRock        | 880GM-LE                    | [21afeee128](https://linux-hardware.org/?probe=21afeee128) | Jan 11, 2021 |
| Gigabyte      | B450M S2H                   | [13edd89415](https://linux-hardware.org/?probe=13edd89415) | Jan 11, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [0265add193](https://linux-hardware.org/?probe=0265add193) | Jan 10, 2021 |
| Gigabyte      | B450M DS3H-CF               | [8b0a9a71b3](https://linux-hardware.org/?probe=8b0a9a71b3) | Jan 10, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [497bf4005e](https://linux-hardware.org/?probe=497bf4005e) | Jan 10, 2021 |
| ASUSTek       | P8Z77-V DELUXE              | [18722316d8](https://linux-hardware.org/?probe=18722316d8) | Jan 10, 2021 |
| ASRock        | X399 Professional Gaming    | [cc3cbc6c76](https://linux-hardware.org/?probe=cc3cbc6c76) | Jan 10, 2021 |
| Foxconn       | 2A92                        | [88f28ae2bf](https://linux-hardware.org/?probe=88f28ae2bf) | Jan 09, 2021 |
| HP            | 3648h                       | [95ce8ac6d8](https://linux-hardware.org/?probe=95ce8ac6d8) | Jan 09, 2021 |
| Foxconn       | 2A92                        | [4b75fd00b3](https://linux-hardware.org/?probe=4b75fd00b3) | Jan 09, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | [e5a628c858](https://linux-hardware.org/?probe=e5a628c858) | Jan 09, 2021 |
| HP            | 2B46                        | [9fc7425e3d](https://linux-hardware.org/?probe=9fc7425e3d) | Jan 09, 2021 |
| Fujitsu       | D3643-H1 S26361-D3643-H1    | [f09e35f12c](https://linux-hardware.org/?probe=f09e35f12c) | Jan 08, 2021 |
| Acer          | Aspire XC-602 V1.0          | [0e8be5137f](https://linux-hardware.org/?probe=0e8be5137f) | Jan 08, 2021 |
| ASUSTek       | P5LD2-VM SE                 | [71eec0354c](https://linux-hardware.org/?probe=71eec0354c) | Jan 07, 2021 |
| HP            | 158A                        | [0539eeeeb8](https://linux-hardware.org/?probe=0539eeeeb8) | Jan 07, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [4a237e25c2](https://linux-hardware.org/?probe=4a237e25c2) | Jan 06, 2021 |
| Gigabyte      | EX58-UD4P                   | [391d558985](https://linux-hardware.org/?probe=391d558985) | Jan 06, 2021 |
| Gigabyte      | EX58-UD4P                   | [d30a2aceb1](https://linux-hardware.org/?probe=d30a2aceb1) | Jan 06, 2021 |
| Dell          | 0RY007                      | [91aeb1441d](https://linux-hardware.org/?probe=91aeb1441d) | Jan 05, 2021 |
| Dell          | 0X501H A03                  | [64a89d74d6](https://linux-hardware.org/?probe=64a89d74d6) | Jan 05, 2021 |
| Acer          | WMCP78M                     | [c5a4dd4ee4](https://linux-hardware.org/?probe=c5a4dd4ee4) | Jan 04, 2021 |
| MSI           | B150M MORTAR                | [467cca1579](https://linux-hardware.org/?probe=467cca1579) | Jan 04, 2021 |
| Acer          | Aspire XC-602 V1.0          | [bb166b2faa](https://linux-hardware.org/?probe=bb166b2faa) | Jan 03, 2021 |
| Unknown       | Intel X79                   | [6184467f17](https://linux-hardware.org/?probe=6184467f17) | Jan 02, 2021 |
| Acer          | Aspire X3400                | [da9e0d0bb4](https://linux-hardware.org/?probe=da9e0d0bb4) | Jan 02, 2021 |
| MSI           | P55-CD53                    | [4d4128c3a2](https://linux-hardware.org/?probe=4d4128c3a2) | Jan 01, 2021 |
| ASUSTek       | PRIME H370M-PLUS            | [403e79415b](https://linux-hardware.org/?probe=403e79415b) | Jan 01, 2021 |
| ASUSTek       | PRIME H370M-PLUS            | [120cc88a70](https://linux-hardware.org/?probe=120cc88a70) | Dec 31, 2020 |
| Dell          | 0K83V0 A00                  | [3bcb7a7dc7](https://linux-hardware.org/?probe=3bcb7a7dc7) | Dec 31, 2020 |
| Dell          | 07PR60 A01                  | [405faad886](https://linux-hardware.org/?probe=405faad886) | Dec 31, 2020 |
| Dell          | 07PR60 A01                  | [de6e7ceac7](https://linux-hardware.org/?probe=de6e7ceac7) | Dec 31, 2020 |
| ASUSTek       | TUF GAMING B550M-PLUS       | [db7addea20](https://linux-hardware.org/?probe=db7addea20) | Dec 30, 2020 |
| ASUSTek       | H81M-P                      | [e532649d15](https://linux-hardware.org/?probe=e532649d15) | Dec 30, 2020 |
| Lenovo        | MAHOBAY                     | [bc1f9200d8](https://linux-hardware.org/?probe=bc1f9200d8) | Dec 30, 2020 |
| Gigabyte      | X570 AORUS MASTER           | [84cb4ded95](https://linux-hardware.org/?probe=84cb4ded95) | Dec 30, 2020 |
| HP            | 1850                        | [b86e749745](https://linux-hardware.org/?probe=b86e749745) | Dec 30, 2020 |
| Medion        | MS-7728                     | [1c026dd4cb](https://linux-hardware.org/?probe=1c026dd4cb) | Dec 29, 2020 |
| HP            | 2B29                        | [3161742f5a](https://linux-hardware.org/?probe=3161742f5a) | Dec 28, 2020 |
| Lenovo        | ThinkServer TS140           | [41ce3f2b0a](https://linux-hardware.org/?probe=41ce3f2b0a) | Dec 28, 2020 |
| MSI           | MS-B1831                    | [8aeb261956](https://linux-hardware.org/?probe=8aeb261956) | Dec 27, 2020 |
| Gigabyte      | H61M-S2PV                   | [9f886b4496](https://linux-hardware.org/?probe=9f886b4496) | Dec 27, 2020 |
| Lenovo        | ThinkServer TS140           | [6a398c9b27](https://linux-hardware.org/?probe=6a398c9b27) | Dec 26, 2020 |
| Lenovo        | ThinkServer TS140           | [96b3895113](https://linux-hardware.org/?probe=96b3895113) | Dec 26, 2020 |
| ASRock        | X570M Pro4                  | [6c57972a71](https://linux-hardware.org/?probe=6c57972a71) | Dec 26, 2020 |
| ASUSTek       | P8P67 LE                    | [627ed8e703](https://linux-hardware.org/?probe=627ed8e703) | Dec 25, 2020 |
| ASUSTek       | M4A88T-M                    | [67714f54b0](https://linux-hardware.org/?probe=67714f54b0) | Dec 25, 2020 |
| Foxconn       | 2ABF                        | [9f73be02e9](https://linux-hardware.org/?probe=9f73be02e9) | Dec 24, 2020 |
| MSI           | MS-B1831                    | [2ece565439](https://linux-hardware.org/?probe=2ece565439) | Dec 23, 2020 |
| ECS           | H110M-C3D/C3V               | [aa44a6674f](https://linux-hardware.org/?probe=aa44a6674f) | Dec 23, 2020 |
| Dell          | 0Y958C A00                  | [1a60b18b20](https://linux-hardware.org/?probe=1a60b18b20) | Dec 23, 2020 |
| HP            | 18E4                        | [2c5cdbbd62](https://linux-hardware.org/?probe=2c5cdbbd62) | Dec 23, 2020 |
| HP            | 2B34                        | [e0d288fe64](https://linux-hardware.org/?probe=e0d288fe64) | Dec 22, 2020 |
| Dell          | 0Y958C A00                  | [edd17e8864](https://linux-hardware.org/?probe=edd17e8864) | Dec 22, 2020 |
| Gigabyte      | M61PME-S2P                  | [51114c4b75](https://linux-hardware.org/?probe=51114c4b75) | Dec 22, 2020 |
| ASUSTek       | Z170-P                      | [53291d247a](https://linux-hardware.org/?probe=53291d247a) | Dec 21, 2020 |
| ECS           | nForce3-A                   | [0150835d63](https://linux-hardware.org/?probe=0150835d63) | Dec 21, 2020 |
| ECS           | nForce3-A                   | [c08a9c2d3a](https://linux-hardware.org/?probe=c08a9c2d3a) | Dec 21, 2020 |
| Unknown       | mqmaker MiQi                | [7113abee46](https://linux-hardware.org/?probe=7113abee46) | Dec 21, 2020 |
| HP            | 158A                        | [d48f153026](https://linux-hardware.org/?probe=d48f153026) | Dec 21, 2020 |
| Minix         | NEO Z83-4 V1.1              | [19e83c7c24](https://linux-hardware.org/?probe=19e83c7c24) | Dec 21, 2020 |
| Gigabyte      | X570 AORUS MASTER           | [77f93a017c](https://linux-hardware.org/?probe=77f93a017c) | Dec 21, 2020 |
| Gigabyte      | X570 AORUS MASTER           | [a6654cf4f1](https://linux-hardware.org/?probe=a6654cf4f1) | Dec 21, 2020 |
| Gigabyte      | F2A78M-HD2                  | [f9d69e13f0](https://linux-hardware.org/?probe=f9d69e13f0) | Dec 21, 2020 |
| Gigabyte      | F2A78M-HD2                  | [e30f78c281](https://linux-hardware.org/?probe=e30f78c281) | Dec 20, 2020 |
| ASUSTek       | M3N78-EMH HDMI              | [72db0d0125](https://linux-hardware.org/?probe=72db0d0125) | Dec 20, 2020 |
| ASUSTek       | M4A88T-M                    | [ee7d610e8e](https://linux-hardware.org/?probe=ee7d610e8e) | Dec 20, 2020 |
| ASUSTek       | TUF GAMING X570-PLUS_BR     | [a129449d5f](https://linux-hardware.org/?probe=a129449d5f) | Dec 19, 2020 |
| Gigabyte      | GA-770T-D3L                 | [f819b316d4](https://linux-hardware.org/?probe=f819b316d4) | Dec 17, 2020 |
| ASUSTek       | Z170-P                      | [d99338778f](https://linux-hardware.org/?probe=d99338778f) | Dec 16, 2020 |
| ASUSTek       | Z170-P                      | [5ac3192ff3](https://linux-hardware.org/?probe=5ac3192ff3) | Dec 16, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [94b7599bed](https://linux-hardware.org/?probe=94b7599bed) | Dec 16, 2020 |
| Minix         | NEO Z83-4 V1.1              | [8f8f606051](https://linux-hardware.org/?probe=8f8f606051) | Dec 16, 2020 |
| Dell          | 03NVJ6 A01                  | [8226cd7051](https://linux-hardware.org/?probe=8226cd7051) | Dec 15, 2020 |
| ASUSTek       | Z170-P                      | [c70d8ca3f9](https://linux-hardware.org/?probe=c70d8ca3f9) | Dec 14, 2020 |
| ASUSTek       | H81M-K                      | [fb9204c5ef](https://linux-hardware.org/?probe=fb9204c5ef) | Dec 13, 2020 |
| Gigabyte      | J3455N-D3H                  | [a9a1ba9727](https://linux-hardware.org/?probe=a9a1ba9727) | Dec 13, 2020 |
| Foxconn       | 2ADA                        | [0b3c20a9d9](https://linux-hardware.org/?probe=0b3c20a9d9) | Dec 12, 2020 |
| Foxconn       | 2ADA                        | [1aedfd747c](https://linux-hardware.org/?probe=1aedfd747c) | Dec 12, 2020 |
| Gigabyte      | H110M-H-CF                  | [168e6322d7](https://linux-hardware.org/?probe=168e6322d7) | Dec 12, 2020 |
| ASUSTek       | P9X79 WS                    | [5a4110ac7b](https://linux-hardware.org/?probe=5a4110ac7b) | Dec 11, 2020 |
| Dell          | 0J3C2F A00                  | [b2e5d9d8b0](https://linux-hardware.org/?probe=b2e5d9d8b0) | Dec 09, 2020 |
| ASUSTek       | M4A88TD-M/USB3              | [2291f0c106](https://linux-hardware.org/?probe=2291f0c106) | Dec 08, 2020 |
| Medion        | MS-7728                     | [e1af3f1d3c](https://linux-hardware.org/?probe=e1af3f1d3c) | Dec 08, 2020 |
| Dell          | 0Y958C A00                  | [b325213f3f](https://linux-hardware.org/?probe=b325213f3f) | Dec 07, 2020 |
| Gigabyte      | GA-MA785GM-US2H             | [f9f42752ca](https://linux-hardware.org/?probe=f9f42752ca) | Dec 07, 2020 |
| Dell          | 0Y958C A00                  | [8a8d020fab](https://linux-hardware.org/?probe=8a8d020fab) | Dec 07, 2020 |
| HP            | 2B29                        | [7a5d8033c4](https://linux-hardware.org/?probe=7a5d8033c4) | Dec 06, 2020 |
| Dell          | 04YP6J A02                  | [6c15ba650c](https://linux-hardware.org/?probe=6c15ba650c) | Dec 06, 2020 |
| ECS           | G31T-M7                     | [da86a0de6d](https://linux-hardware.org/?probe=da86a0de6d) | Dec 06, 2020 |
| HP            | 2B29                        | [0de16218a6](https://linux-hardware.org/?probe=0de16218a6) | Dec 04, 2020 |
| Dell          | 0Y958C A00                  | [8dc6bd07d9](https://linux-hardware.org/?probe=8dc6bd07d9) | Dec 02, 2020 |
| HP            | 304Ah                       | [e0127b5745](https://linux-hardware.org/?probe=e0127b5745) | Dec 02, 2020 |
| ASUSTek       | STRIX B250G GAMING          | [442ae34c4c](https://linux-hardware.org/?probe=442ae34c4c) | Dec 02, 2020 |
| ASRock        | B450M Pro4-F                | [1e395f258f](https://linux-hardware.org/?probe=1e395f258f) | Dec 01, 2020 |
| HP            | 2B29                        | [8d711e1e2b](https://linux-hardware.org/?probe=8d711e1e2b) | Dec 01, 2020 |
| ASUSTek       | M4N68T-M LE                 | [f500a90ee5](https://linux-hardware.org/?probe=f500a90ee5) | Dec 01, 2020 |
| ASUSTek       | M4N68T-M LE                 | [edda2cb008](https://linux-hardware.org/?probe=edda2cb008) | Dec 01, 2020 |
| HP            | 2B29                        | [0a7d054f34](https://linux-hardware.org/?probe=0a7d054f34) | Nov 29, 2020 |
| HP            | 2B29                        | [0f5898cf39](https://linux-hardware.org/?probe=0f5898cf39) | Nov 29, 2020 |
| MSI           | MS-7387                     | [c0b3272c7c](https://linux-hardware.org/?probe=c0b3272c7c) | Nov 29, 2020 |
| HP            | ProLiant ML370 G6           | [0c4b40cafd](https://linux-hardware.org/?probe=0c4b40cafd) | Nov 29, 2020 |
| ASRock        | 990FX Extreme4              | [2168e642ab](https://linux-hardware.org/?probe=2168e642ab) | Nov 29, 2020 |
| eMachines     | EL1352                      | [b7646b7bf3](https://linux-hardware.org/?probe=b7646b7bf3) | Nov 29, 2020 |
| Gigabyte      | H61M-D2H-USB3               | [5de3c42e69](https://linux-hardware.org/?probe=5de3c42e69) | Nov 28, 2020 |
| Gigabyte      | X570 AORUS ELITE            | [294c2bf2e7](https://linux-hardware.org/?probe=294c2bf2e7) | Nov 28, 2020 |
| Lenovo        | Board                       | [44fbb2b2f8](https://linux-hardware.org/?probe=44fbb2b2f8) | Nov 27, 2020 |
| Lenovo        | Board                       | [d45b996432](https://linux-hardware.org/?probe=d45b996432) | Nov 27, 2020 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | [2ff8c7a3f8](https://linux-hardware.org/?probe=2ff8c7a3f8) | Nov 26, 2020 |
| Dell          | 0GXM1W A02                  | [baca597036](https://linux-hardware.org/?probe=baca597036) | Nov 26, 2020 |
| Dell          | 0GXM1W A02                  | [06de0c3923](https://linux-hardware.org/?probe=06de0c3923) | Nov 25, 2020 |
| Intel         | DB85FL AAG89861-201         | [936daa5428](https://linux-hardware.org/?probe=936daa5428) | Nov 25, 2020 |
| ASRock        | HM87-MXM                    | [02111cb44f](https://linux-hardware.org/?probe=02111cb44f) | Nov 25, 2020 |
| HP            | 0ACCh                       | [7f4d2a2df4](https://linux-hardware.org/?probe=7f4d2a2df4) | Nov 23, 2020 |
| HP            | 0ACCh                       | [d28f3f3195](https://linux-hardware.org/?probe=d28f3f3195) | Nov 23, 2020 |
| ASRock        | 990FX Extreme4              | [deffb50091](https://linux-hardware.org/?probe=deffb50091) | Nov 23, 2020 |
| ASRock        | FM2A88X Extreme6+           | [0ddc71518c](https://linux-hardware.org/?probe=0ddc71518c) | Nov 22, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [7e1033e8f3](https://linux-hardware.org/?probe=7e1033e8f3) | Nov 22, 2020 |
| ASUSTek       | M4A78L-M                    | [2c715cff4c](https://linux-hardware.org/?probe=2c715cff4c) | Nov 22, 2020 |
| ASUSTek       | PRIME Z390-A                | [c5b35954b5](https://linux-hardware.org/?probe=c5b35954b5) | Nov 22, 2020 |
| ASUSTek       | M4A77T                      | [8f463afca3](https://linux-hardware.org/?probe=8f463afca3) | Nov 22, 2020 |
| ASUSTek       | M4A77T                      | [8e1b9c4d71](https://linux-hardware.org/?probe=8e1b9c4d71) | Nov 22, 2020 |
| Lenovo        | Board                       | [cf9c213443](https://linux-hardware.org/?probe=cf9c213443) | Nov 21, 2020 |
| Foxconn       | 2ABF                        | [fa95d7cd22](https://linux-hardware.org/?probe=fa95d7cd22) | Nov 21, 2020 |
| Lenovo        | Board                       | [66d1757c3f](https://linux-hardware.org/?probe=66d1757c3f) | Nov 21, 2020 |
| HP            | 3032h                       | [1a10cb8912](https://linux-hardware.org/?probe=1a10cb8912) | Nov 20, 2020 |
| HP            | 3397                        | [8c4414f5e6](https://linux-hardware.org/?probe=8c4414f5e6) | Nov 20, 2020 |
| ASRock        | Q1900M                      | [2d0b876209](https://linux-hardware.org/?probe=2d0b876209) | Nov 20, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [90e2e642cf](https://linux-hardware.org/?probe=90e2e642cf) | Nov 18, 2020 |
| Gigabyte      | G41M-Combo                  | [34ac1118fc](https://linux-hardware.org/?probe=34ac1118fc) | Nov 18, 2020 |
| ASRock        | B450 Gaming K4              | [f900377694](https://linux-hardware.org/?probe=f900377694) | Nov 18, 2020 |
| ASUSTek       | H81M-P                      | [32ccf4d815](https://linux-hardware.org/?probe=32ccf4d815) | Nov 18, 2020 |
| Gigabyte      | G41M-Combo                  | [43fc3c5473](https://linux-hardware.org/?probe=43fc3c5473) | Nov 17, 2020 |
| Lenovo        | ThinkServer TS140           | [303ae16f51](https://linux-hardware.org/?probe=303ae16f51) | Nov 17, 2020 |
| ASUSTek       | PRIME X570-PRO              | [e1e045ba6c](https://linux-hardware.org/?probe=e1e045ba6c) | Nov 16, 2020 |
| Dell          | 0F6X5P A00                  | [c5ed241b08](https://linux-hardware.org/?probe=c5ed241b08) | Nov 16, 2020 |
| Dell          | 088DT1 A01                  | [ac8f81ddbc](https://linux-hardware.org/?probe=ac8f81ddbc) | Nov 15, 2020 |
| HP            | 18E5                        | [9da8cd466f](https://linux-hardware.org/?probe=9da8cd466f) | Nov 15, 2020 |
| Lenovo        | MAHOBAY NO DPK              | [be10f2c608](https://linux-hardware.org/?probe=be10f2c608) | Nov 13, 2020 |
| MSI           | Z77A-G45                    | [f3741b744f](https://linux-hardware.org/?probe=f3741b744f) | Nov 13, 2020 |
| Dell          | 088DT1 A01                  | [6fe876bc14](https://linux-hardware.org/?probe=6fe876bc14) | Nov 13, 2020 |
| Lenovo        | MAHOBAY NO DPK              | [c79b58ba5b](https://linux-hardware.org/?probe=c79b58ba5b) | Nov 13, 2020 |
| ASUSTek       | PRIME X370-A                | [6618ea7285](https://linux-hardware.org/?probe=6618ea7285) | Nov 12, 2020 |
| Gigabyte      | GA-MA785GM-US2H             | [79ba5e5e77](https://linux-hardware.org/?probe=79ba5e5e77) | Nov 11, 2020 |
| Gigabyte      | EX58-UD4P                   | [d5dfd8ab5b](https://linux-hardware.org/?probe=d5dfd8ab5b) | Nov 10, 2020 |
| HP            | 0A00h                       | [5515bf006a](https://linux-hardware.org/?probe=5515bf006a) | Nov 08, 2020 |
| Fujitsu Si... | D2587-A1 S26361-D2587-A1    | [d584773eee](https://linux-hardware.org/?probe=d584773eee) | Nov 08, 2020 |
| NEC Comput... | IS8XM                       | [fbcda877e4](https://linux-hardware.org/?probe=fbcda877e4) | Nov 07, 2020 |
| Gigabyte      | GA-970A-DS3                 | [58a8f1077b](https://linux-hardware.org/?probe=58a8f1077b) | Nov 06, 2020 |
| Medion        | MS-7797                     | [7e6563d31c](https://linux-hardware.org/?probe=7e6563d31c) | Nov 06, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [424e7b661d](https://linux-hardware.org/?probe=424e7b661d) | Nov 06, 2020 |
| Apple         | Mac-F221BEC8                | [ac6556242f](https://linux-hardware.org/?probe=ac6556242f) | Nov 06, 2020 |
| Apple         | Mac-F221BEC8                | [56d223bda7](https://linux-hardware.org/?probe=56d223bda7) | Nov 06, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [233cd75348](https://linux-hardware.org/?probe=233cd75348) | Nov 05, 2020 |
| Intel         | H61                         | [071d57e367](https://linux-hardware.org/?probe=071d57e367) | Nov 05, 2020 |
| Dell          | 0X501H A03                  | [967d89d420](https://linux-hardware.org/?probe=967d89d420) | Nov 05, 2020 |
| Dell          | 0X501H A03                  | [f7f33657cf](https://linux-hardware.org/?probe=f7f33657cf) | Nov 05, 2020 |
| NEC Comput... | IS8XM                       | [ca22c03b0e](https://linux-hardware.org/?probe=ca22c03b0e) | Nov 04, 2020 |
| MSI           | Z77A-G45                    | [22367ac4af](https://linux-hardware.org/?probe=22367ac4af) | Nov 04, 2020 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [f27791145e](https://linux-hardware.org/?probe=f27791145e) | Nov 03, 2020 |
| ASRock        | HM87-MXM                    | [403aa7d431](https://linux-hardware.org/?probe=403aa7d431) | Nov 03, 2020 |
| ASRock        | HM87-MXM                    | [d47723e369](https://linux-hardware.org/?probe=d47723e369) | Nov 03, 2020 |
| ASRock        | A300M-STX                   | [d16cbe4e3e](https://linux-hardware.org/?probe=d16cbe4e3e) | Nov 03, 2020 |
| Intel         | H61M-S1                     | [f31ad89e75](https://linux-hardware.org/?probe=f31ad89e75) | Nov 02, 2020 |
| Intel         | H61M-S1                     | [f381b5e487](https://linux-hardware.org/?probe=f381b5e487) | Nov 02, 2020 |
| ASUSTek       | CS-B                        | [4e0f76c433](https://linux-hardware.org/?probe=4e0f76c433) | Nov 02, 2020 |
| Gigabyte      | X570 UD                     | [607e02b996](https://linux-hardware.org/?probe=607e02b996) | Nov 02, 2020 |
| HP            | 0A58h                       | [796cd4ef09](https://linux-hardware.org/?probe=796cd4ef09) | Nov 02, 2020 |
| ASUSTek       | M5A99FX PRO R2.0            | [55c65411a0](https://linux-hardware.org/?probe=55c65411a0) | Nov 01, 2020 |
| ASUSTek       | M5A99FX PRO R2.0            | [9f09e4b2e0](https://linux-hardware.org/?probe=9f09e4b2e0) | Nov 01, 2020 |
| ASUSTek       | M5A99FX PRO R2.0            | [8e7396c5f2](https://linux-hardware.org/?probe=8e7396c5f2) | Nov 01, 2020 |
| Gigabyte      | B150M-D3H-CF                | [57d7a8f5f7](https://linux-hardware.org/?probe=57d7a8f5f7) | Oct 31, 2020 |
| HP            | 3397                        | [cf461d2903](https://linux-hardware.org/?probe=cf461d2903) | Oct 31, 2020 |
| ASUSTek       | M4A785-M                    | [af85b28568](https://linux-hardware.org/?probe=af85b28568) | Oct 31, 2020 |
| HP            | 304Ah                       | [ebc4ca37d5](https://linux-hardware.org/?probe=ebc4ca37d5) | Oct 30, 2020 |
| Dell          | 04GJJT A00                  | [fc31c33025](https://linux-hardware.org/?probe=fc31c33025) | Oct 30, 2020 |
| ASUSTek       | P5KPL-AM SE                 | [b916a2471b](https://linux-hardware.org/?probe=b916a2471b) | Oct 29, 2020 |
| Foxconn       | 2AB1h                       | [dd42a7e94c](https://linux-hardware.org/?probe=dd42a7e94c) | Oct 29, 2020 |
| ASUSTek       | H87M-PLUS                   | [7df4485d80](https://linux-hardware.org/?probe=7df4485d80) | Oct 28, 2020 |
| Foxconn       | 2ABF                        | [98e0846229](https://linux-hardware.org/?probe=98e0846229) | Oct 28, 2020 |
| ASUSTek       | PRIME X570-PRO              | [7a0aaf6d26](https://linux-hardware.org/?probe=7a0aaf6d26) | Oct 27, 2020 |
| Dell          | 0K83V0 A00                  | [caa3f7d5c2](https://linux-hardware.org/?probe=caa3f7d5c2) | Oct 27, 2020 |
| Dell          | 0K83V0 A00                  | [8fc67df632](https://linux-hardware.org/?probe=8fc67df632) | Oct 27, 2020 |
| ASUSTek       | PRIME B360M-A               | [f52d2d566a](https://linux-hardware.org/?probe=f52d2d566a) | Oct 27, 2020 |
| HP            | 3397                        | [0c7f93cb53](https://linux-hardware.org/?probe=0c7f93cb53) | Oct 26, 2020 |
| Dell          | 0Y5DDC A00                  | [4a6901b354](https://linux-hardware.org/?probe=4a6901b354) | Oct 25, 2020 |
| Gigabyte      | Z170-HD3P-CF                | [e3920e0ddd](https://linux-hardware.org/?probe=e3920e0ddd) | Oct 24, 2020 |
| Dell          | 0X9M3X A03                  | [0fbdc774f7](https://linux-hardware.org/?probe=0fbdc774f7) | Oct 23, 2020 |
| ASRock        | N68C-S UCC                  | [e8b5a5c6c1](https://linux-hardware.org/?probe=e8b5a5c6c1) | Oct 22, 2020 |
| ASRock        | 970 Extreme3 R2.0           | [e9eab6369f](https://linux-hardware.org/?probe=e9eab6369f) | Oct 22, 2020 |
| ASRock        | 970 Extreme3 R2.0           | [ee3c78e7f9](https://linux-hardware.org/?probe=ee3c78e7f9) | Oct 22, 2020 |
| HP            | 18E7                        | [9b75d72659](https://linux-hardware.org/?probe=9b75d72659) | Oct 21, 2020 |
| MSI           | B85M-E45                    | [7d562c5a0b](https://linux-hardware.org/?probe=7d562c5a0b) | Oct 21, 2020 |
| HP            | 1589                        | [97e2a8328c](https://linux-hardware.org/?probe=97e2a8328c) | Oct 21, 2020 |
| HP            | 1589                        | [c01a481fe5](https://linux-hardware.org/?probe=c01a481fe5) | Oct 21, 2020 |
| Intel         | DH55HC AAE70933-501         | [6542fc1f81](https://linux-hardware.org/?probe=6542fc1f81) | Oct 20, 2020 |
| Lenovo        | ThinkServer TS140           | [cc871fe1eb](https://linux-hardware.org/?probe=cc871fe1eb) | Oct 20, 2020 |
| ASUSTek       | TUF GAMING X570-PLUS        | [8892c91b74](https://linux-hardware.org/?probe=8892c91b74) | Oct 19, 2020 |
| ASRock        | N68C-S UCC                  | [2c05125698](https://linux-hardware.org/?probe=2c05125698) | Oct 19, 2020 |
| ASRock        | H55M/USB3                   | [74202436b2](https://linux-hardware.org/?probe=74202436b2) | Oct 18, 2020 |
| Intel         | DH67CF AAG10215-207         | [bdad9ec53e](https://linux-hardware.org/?probe=bdad9ec53e) | Oct 18, 2020 |
| ASRock        | N68C-GS FX                  | [9e5b81cf31](https://linux-hardware.org/?probe=9e5b81cf31) | Oct 17, 2020 |
| HP            | 82F2 A01                    | [9f775578b2](https://linux-hardware.org/?probe=9f775578b2) | Oct 17, 2020 |
| ASUSTek       | M4A78LT-M                   | [05d6ef0ede](https://linux-hardware.org/?probe=05d6ef0ede) | Oct 17, 2020 |
| Dell          | 0X501H A03                  | [e70a2099d3](https://linux-hardware.org/?probe=e70a2099d3) | Oct 17, 2020 |
| ASRock        | X570 Phantom Gaming-ITX/... | [877be0d702](https://linux-hardware.org/?probe=877be0d702) | Oct 16, 2020 |
| ASRock        | X570 Phantom Gaming-ITX/... | [10afcab1dd](https://linux-hardware.org/?probe=10afcab1dd) | Oct 16, 2020 |
| Itautec       | ST 4265 ST-4265 Padrao 0... | [4c66a9acab](https://linux-hardware.org/?probe=4c66a9acab) | Oct 16, 2020 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [cacf226be4](https://linux-hardware.org/?probe=cacf226be4) | Oct 16, 2020 |
| HP            | 3397                        | [33fdc768a1](https://linux-hardware.org/?probe=33fdc768a1) | Oct 15, 2020 |
| ASRock        | 970 Extreme4                | [da013f2159](https://linux-hardware.org/?probe=da013f2159) | Oct 15, 2020 |
| ASRock        | A320M-HDV R4.0              | [753273ae7d](https://linux-hardware.org/?probe=753273ae7d) | Oct 14, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [aea7dc9a63](https://linux-hardware.org/?probe=aea7dc9a63) | Oct 14, 2020 |
| ASRock        | 990FX Professional          | [97ce7ab2bc](https://linux-hardware.org/?probe=97ce7ab2bc) | Oct 12, 2020 |
| ASUSTek       | PRIME X570-PRO              | [f01f497eb1](https://linux-hardware.org/?probe=f01f497eb1) | Oct 12, 2020 |
| ASUSTek       | P8H61-M LX2                 | [ec63552e89](https://linux-hardware.org/?probe=ec63552e89) | Oct 11, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [964d90f42f](https://linux-hardware.org/?probe=964d90f42f) | Oct 11, 2020 |
| Lenovo        | MAHOBAY                     | [6427fb47dd](https://linux-hardware.org/?probe=6427fb47dd) | Oct 10, 2020 |
| Dell          | 096JG8 A01                  | [1c591aa639](https://linux-hardware.org/?probe=1c591aa639) | Oct 10, 2020 |
| HP            | 1495                        | [95e7609af2](https://linux-hardware.org/?probe=95e7609af2) | Oct 10, 2020 |
| Dell          | 0Y5DDC A00                  | [63d4ae5e3d](https://linux-hardware.org/?probe=63d4ae5e3d) | Oct 10, 2020 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [19ef25af06](https://linux-hardware.org/?probe=19ef25af06) | Oct 09, 2020 |
| MSI           | B450M-A PRO MAX             | [3712afebf5](https://linux-hardware.org/?probe=3712afebf5) | Oct 09, 2020 |
| HP            | 304Ah                       | [c05b24bee0](https://linux-hardware.org/?probe=c05b24bee0) | Oct 09, 2020 |
| HP            | 0A64h                       | [83fa351a56](https://linux-hardware.org/?probe=83fa351a56) | Oct 07, 2020 |
| MSI           | 970A-G46                    | [299e4a7770](https://linux-hardware.org/?probe=299e4a7770) | Oct 07, 2020 |
| Gigabyte      | P55M-UD2                    | [cf07ea3801](https://linux-hardware.org/?probe=cf07ea3801) | Oct 05, 2020 |
| MSI           | A68HM-E33 V2                | [a88be898c1](https://linux-hardware.org/?probe=a88be898c1) | Oct 05, 2020 |
| ASUSTek       | H87M-PLUS                   | [3eb7622018](https://linux-hardware.org/?probe=3eb7622018) | Oct 04, 2020 |
| MSI           | MEG X570 ACE                | [707d8920a5](https://linux-hardware.org/?probe=707d8920a5) | Oct 04, 2020 |
| HP            | 0A64h                       | [212a85da51](https://linux-hardware.org/?probe=212a85da51) | Oct 04, 2020 |
| Dell          | 0TP406                      | [b9e8cd1651](https://linux-hardware.org/?probe=b9e8cd1651) | Oct 04, 2020 |
| ASUSTek       | M5A78L-M LX V2              | [8174433592](https://linux-hardware.org/?probe=8174433592) | Oct 04, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [3c907dd84e](https://linux-hardware.org/?probe=3c907dd84e) | Oct 03, 2020 |
| Gigabyte      | Z97X-Gaming 3               | [b1aeaa645b](https://linux-hardware.org/?probe=b1aeaa645b) | Oct 03, 2020 |
| Gigabyte      | Z97X-Gaming 3               | [45bfa5eb3c](https://linux-hardware.org/?probe=45bfa5eb3c) | Oct 03, 2020 |
| HP            | 82F2 A01                    | [624aa6976f](https://linux-hardware.org/?probe=624aa6976f) | Oct 02, 2020 |
| Dell          | 0PU052                      | [e2e65a1fa7](https://linux-hardware.org/?probe=e2e65a1fa7) | Oct 02, 2020 |
| ASRock        | N68C-S UCC                  | [b82b064a51](https://linux-hardware.org/?probe=b82b064a51) | Oct 02, 2020 |
| ASUSTek       | P5K                         | [c1c290f102](https://linux-hardware.org/?probe=c1c290f102) | Oct 02, 2020 |
| Dell          | 0M863N A00                  | [4ffc77e348](https://linux-hardware.org/?probe=4ffc77e348) | Oct 02, 2020 |
| Dell          | 0M863N A00                  | [3719f7c699](https://linux-hardware.org/?probe=3719f7c699) | Oct 02, 2020 |
| ASUSTek       | Z87-A                       | [63e9e30049](https://linux-hardware.org/?probe=63e9e30049) | Oct 02, 2020 |
| Intel         | DG41TX AAE78178-303         | [2ba4c11c35](https://linux-hardware.org/?probe=2ba4c11c35) | Oct 02, 2020 |
| Dell          | 0WR7PY A02                  | [44ffa409aa](https://linux-hardware.org/?probe=44ffa409aa) | Oct 01, 2020 |
| ASUSTek       | H87M-PLUS                   | [07387013eb](https://linux-hardware.org/?probe=07387013eb) | Sep 30, 2020 |
| HP            | 1495                        | [0b848e88ef](https://linux-hardware.org/?probe=0b848e88ef) | Sep 30, 2020 |
| Dell          | 0M863N A00                  | [ff7dbf0c44](https://linux-hardware.org/?probe=ff7dbf0c44) | Sep 29, 2020 |
| Dell          | 0M863N A00                  | [355f17e5ec](https://linux-hardware.org/?probe=355f17e5ec) | Sep 29, 2020 |
| Unknown       | Unknown                     | [4ebc73788d](https://linux-hardware.org/?probe=4ebc73788d) | Sep 29, 2020 |
| MSI           | X470 GAMING PLUS            | [cfb285ef78](https://linux-hardware.org/?probe=cfb285ef78) | Sep 29, 2020 |
| ASUSTek       | PRIME B450M-A               | [0f6dc81b18](https://linux-hardware.org/?probe=0f6dc81b18) | Sep 29, 2020 |
| MSI           | X570-A PRO                  | [601b9c7dcf](https://linux-hardware.org/?probe=601b9c7dcf) | Sep 29, 2020 |
| Gigabyte      | H61M-S2PV                   | [97d6fcdf95](https://linux-hardware.org/?probe=97d6fcdf95) | Sep 28, 2020 |
| ASUSTek       | P5KPL-AM                    | [d42399006f](https://linux-hardware.org/?probe=d42399006f) | Sep 27, 2020 |
| Fujitsu       | D3091-A1 S26361-D3091-A1    | [30a2037cce](https://linux-hardware.org/?probe=30a2037cce) | Sep 26, 2020 |
| Intel         | H61                         | [0ddeefc2fc](https://linux-hardware.org/?probe=0ddeefc2fc) | Sep 26, 2020 |
| HP            | 0AA8h                       | [244549772f](https://linux-hardware.org/?probe=244549772f) | Sep 25, 2020 |
| Intel         | H61                         | [87b485d42f](https://linux-hardware.org/?probe=87b485d42f) | Sep 25, 2020 |
| Lenovo        | MAHOBAY NOK                 | [052bf49b84](https://linux-hardware.org/?probe=052bf49b84) | Sep 25, 2020 |
| Dell          | 0F8098                      | [a2217fa6a7](https://linux-hardware.org/?probe=a2217fa6a7) | Sep 25, 2020 |
| Dell          | 0F8098                      | [2c747bcc47](https://linux-hardware.org/?probe=2c747bcc47) | Sep 25, 2020 |
| HP            | 0AA8h                       | [80cbff87bd](https://linux-hardware.org/?probe=80cbff87bd) | Sep 24, 2020 |
| ASUSTek       | M5A78L-M LX V2              | [918e747daf](https://linux-hardware.org/?probe=918e747daf) | Sep 24, 2020 |
| Gigabyte      | B450M DS3H-CF               | [c52887d7df](https://linux-hardware.org/?probe=c52887d7df) | Sep 24, 2020 |
| Dell          | 02K9CR A01                  | [c2e31c7ce8](https://linux-hardware.org/?probe=c2e31c7ce8) | Sep 24, 2020 |
| Positivo      | POS-AG31AP                  | [9dc1ba771f](https://linux-hardware.org/?probe=9dc1ba771f) | Sep 23, 2020 |
| Dell          | 0F6X5P A00                  | [a1cbd8f918](https://linux-hardware.org/?probe=a1cbd8f918) | Sep 23, 2020 |
| Dell          | 0X501H A03                  | [ebeee4544c](https://linux-hardware.org/?probe=ebeee4544c) | Sep 22, 2020 |
| Dell          | 0X501H A03                  | [09aae352fc](https://linux-hardware.org/?probe=09aae352fc) | Sep 22, 2020 |
| Dell          | 0F6X5P A00                  | [0b548f3a3f](https://linux-hardware.org/?probe=0b548f3a3f) | Sep 22, 2020 |
| Dell          | 0F6X5P A00                  | [de2d0e80f8](https://linux-hardware.org/?probe=de2d0e80f8) | Sep 22, 2020 |
| Dell          | 0X501H A03                  | [8772871786](https://linux-hardware.org/?probe=8772871786) | Sep 21, 2020 |
| Dell          | 0X501H A03                  | [4a8ba3857a](https://linux-hardware.org/?probe=4a8ba3857a) | Sep 21, 2020 |
| Acer          | Aspire X3400G               | [80fdbf7a1b](https://linux-hardware.org/?probe=80fdbf7a1b) | Sep 20, 2020 |
| ASUSTek       | A88XM-PLUS                  | [bdae1a68a5](https://linux-hardware.org/?probe=bdae1a68a5) | Sep 18, 2020 |
| ASRock        | X99 WS-E/10G                | [cd3238583f](https://linux-hardware.org/?probe=cd3238583f) | Sep 17, 2020 |
| ASRock        | X99 WS-E/10G                | [bf1047170e](https://linux-hardware.org/?probe=bf1047170e) | Sep 16, 2020 |
| HP            | 1495                        | [94de1a6e23](https://linux-hardware.org/?probe=94de1a6e23) | Sep 16, 2020 |
| PCWare        | IPMH310G                    | [7231f076bd](https://linux-hardware.org/?probe=7231f076bd) | Sep 15, 2020 |
| PCWare        | IPMH310G                    | [181e5467d9](https://linux-hardware.org/?probe=181e5467d9) | Sep 15, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [2399ed18fd](https://linux-hardware.org/?probe=2399ed18fd) | Sep 14, 2020 |
| ASUSTek       | P6X58D-E                    | [09428a86cd](https://linux-hardware.org/?probe=09428a86cd) | Sep 14, 2020 |
| ASUSTek       | P5KPL-AM                    | [3f22ea2e15](https://linux-hardware.org/?probe=3f22ea2e15) | Sep 13, 2020 |
| ECS           | G31T-M7                     | [70c5208ec6](https://linux-hardware.org/?probe=70c5208ec6) | Sep 13, 2020 |
| Lenovo        | Board                       | [f8dc9acb3f](https://linux-hardware.org/?probe=f8dc9acb3f) | Sep 13, 2020 |
| Lenovo        | Board                       | [9f4325cb06](https://linux-hardware.org/?probe=9f4325cb06) | Sep 13, 2020 |
| Dell          | 0WG864                      | [fa12f9413f](https://linux-hardware.org/?probe=fa12f9413f) | Sep 12, 2020 |
| ASUSTek       | P5Q DELUXE                  | [960c7e17db](https://linux-hardware.org/?probe=960c7e17db) | Sep 12, 2020 |
| Dell          | 0WG864                      | [456382938e](https://linux-hardware.org/?probe=456382938e) | Sep 12, 2020 |
| ASRock        | X79 Extreme4                | [7cd6a3625c](https://linux-hardware.org/?probe=7cd6a3625c) | Sep 10, 2020 |
| ASUSTek       | P8H61-M LE                  | [4fdffb335a](https://linux-hardware.org/?probe=4fdffb335a) | Sep 08, 2020 |
| ASUSTek       | P8H61-M LE                  | [7c9c74b288](https://linux-hardware.org/?probe=7c9c74b288) | Sep 08, 2020 |
| Lenovo        | ThinkStation D20 4158CM1    | [a6077c212e](https://linux-hardware.org/?probe=a6077c212e) | Sep 08, 2020 |
| ASUSTek       | H87-PLUS                    | [ad2897518b](https://linux-hardware.org/?probe=ad2897518b) | Sep 08, 2020 |
| ASRock        | ALiveNF6P-VSTA              | [dd876ba784](https://linux-hardware.org/?probe=dd876ba784) | Sep 08, 2020 |
| ASRock        | ALiveNF6P-VSTA              | [42997fd9bd](https://linux-hardware.org/?probe=42997fd9bd) | Sep 08, 2020 |
| HP            | 339A                        | [109949681c](https://linux-hardware.org/?probe=109949681c) | Sep 06, 2020 |
| Dell          | 0200DY A02                  | [cfe26c9023](https://linux-hardware.org/?probe=cfe26c9023) | Sep 05, 2020 |
| ASRock        | Z87E-ITX                    | [d1095a7a24](https://linux-hardware.org/?probe=d1095a7a24) | Sep 05, 2020 |
| ASUSTek       | PRIME B450M-A               | [d4d40f1808](https://linux-hardware.org/?probe=d4d40f1808) | Sep 04, 2020 |
| ASUSTek       | H87-PLUS                    | [1602fc1f70](https://linux-hardware.org/?probe=1602fc1f70) | Sep 04, 2020 |
| MSI           | Z77A-G45                    | [278850fdd4](https://linux-hardware.org/?probe=278850fdd4) | Sep 04, 2020 |
| Medion        | MS-7797                     | [cae7e7f201](https://linux-hardware.org/?probe=cae7e7f201) | Sep 04, 2020 |
| ASRock        | Q2900-ITX                   | [1707f849a6](https://linux-hardware.org/?probe=1707f849a6) | Sep 04, 2020 |
| Dell          | 0Y5DDC A00                  | [beef376967](https://linux-hardware.org/?probe=beef376967) | Sep 04, 2020 |
| Medion        | MS-7708                     | [c58e461f9d](https://linux-hardware.org/?probe=c58e461f9d) | Sep 03, 2020 |
| MSI           | X570-A PRO                  | [18e8b1b893](https://linux-hardware.org/?probe=18e8b1b893) | Sep 03, 2020 |
| ASRock        | B450 Pro4                   | [4b4eb09724](https://linux-hardware.org/?probe=4b4eb09724) | Sep 03, 2020 |
| Acer          | Batman A01                  | [e9d0e3d9d4](https://linux-hardware.org/?probe=e9d0e3d9d4) | Sep 02, 2020 |
| ASRock        | TRX40 Creator               | [e8bbe1674e](https://linux-hardware.org/?probe=e8bbe1674e) | Sep 01, 2020 |
| Fujitsu Si... | D2587-A1 S26361-D2587-A1    | [89e7ddc6ec](https://linux-hardware.org/?probe=89e7ddc6ec) | Sep 01, 2020 |
| Medion        | MS-7857                     | [9ab3e2ae3f](https://linux-hardware.org/?probe=9ab3e2ae3f) | Aug 31, 2020 |
| Shuttle       | FH87                        | [087c5627a0](https://linux-hardware.org/?probe=087c5627a0) | Aug 30, 2020 |
| Medion        | MS-7857                     | [311d3d4895](https://linux-hardware.org/?probe=311d3d4895) | Aug 30, 2020 |
| Dell          | 0JC474                      | [0f799b70a5](https://linux-hardware.org/?probe=0f799b70a5) | Aug 29, 2020 |
| ASRock        | H170M Pro4                  | [10d84618d9](https://linux-hardware.org/?probe=10d84618d9) | Aug 29, 2020 |
| MSI           | B450M-A PRO MAX             | [e46d6617a9](https://linux-hardware.org/?probe=e46d6617a9) | Aug 28, 2020 |
| ASUSTek       | M4A78LT-M                   | [af3c3aee59](https://linux-hardware.org/?probe=af3c3aee59) | Aug 27, 2020 |
| ASUSTek       | M4A78LT-M                   | [cae2109038](https://linux-hardware.org/?probe=cae2109038) | Aug 27, 2020 |
| ASUSTek       | ET1612I                     | [9cc05b2a9e](https://linux-hardware.org/?probe=9cc05b2a9e) | Aug 27, 2020 |
| ASRock        | B85 Pro4                    | [b75833748d](https://linux-hardware.org/?probe=b75833748d) | Aug 26, 2020 |
| ASUSTek       | ET1612I                     | [82b55a1903](https://linux-hardware.org/?probe=82b55a1903) | Aug 25, 2020 |
| ASUSTek       | X99-E                       | [c3e2a36b7e](https://linux-hardware.org/?probe=c3e2a36b7e) | Aug 25, 2020 |
| NCR           | Pocono                      | [96fac7c428](https://linux-hardware.org/?probe=96fac7c428) | Aug 25, 2020 |
| ASUSTek       | H87M-PLUS                   | [a3c38540b4](https://linux-hardware.org/?probe=a3c38540b4) | Aug 25, 2020 |
| ASUSTek       | ET1612I                     | [a69dacee1d](https://linux-hardware.org/?probe=a69dacee1d) | Aug 24, 2020 |
| Gigabyte      | P61-USB3-B3                 | [9ecd34fe2e](https://linux-hardware.org/?probe=9ecd34fe2e) | Aug 24, 2020 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [00834d5b62](https://linux-hardware.org/?probe=00834d5b62) | Aug 23, 2020 |
| MSI           | MS-B0501 100                | [12c7b9ccc6](https://linux-hardware.org/?probe=12c7b9ccc6) | Aug 22, 2020 |
| ASRock        | FM2A88M Extreme4+           | [bc5631611b](https://linux-hardware.org/?probe=bc5631611b) | Aug 21, 2020 |
| Gigabyte      | M68MT-S2                    | [da3fea7987](https://linux-hardware.org/?probe=da3fea7987) | Aug 21, 2020 |
| Dell          | 0PU052                      | [ad5edd5c3c](https://linux-hardware.org/?probe=ad5edd5c3c) | Aug 21, 2020 |
| MSI           | B450 TOMAHAWK MAX           | [532be87782](https://linux-hardware.org/?probe=532be87782) | Aug 20, 2020 |
| ASUSTek       | H87M-PLUS                   | [110ab24197](https://linux-hardware.org/?probe=110ab24197) | Aug 20, 2020 |
| Dell          | 096JG8 A01                  | [76d74f26bd](https://linux-hardware.org/?probe=76d74f26bd) | Aug 20, 2020 |
| HP            | 3397                        | [fcdcfc7812](https://linux-hardware.org/?probe=fcdcfc7812) | Aug 20, 2020 |
| MSI           | B350 TOMAHAWK               | [d4c9b039ff](https://linux-hardware.org/?probe=d4c9b039ff) | Aug 20, 2020 |
| Dell          | 096JG8 A01                  | [083a1b24a2](https://linux-hardware.org/?probe=083a1b24a2) | Aug 20, 2020 |
| Dell          | 096JG8 A01                  | [b2e7162b8f](https://linux-hardware.org/?probe=b2e7162b8f) | Aug 19, 2020 |
| ASRock        | B450M Pro4                  | [49081ef429](https://linux-hardware.org/?probe=49081ef429) | Aug 19, 2020 |
| ASRock        | B450M Pro4                  | [d2851c54e9](https://linux-hardware.org/?probe=d2851c54e9) | Aug 18, 2020 |
| Biostar       | G41-M7                      | [dc33e9b8b5](https://linux-hardware.org/?probe=dc33e9b8b5) | Aug 18, 2020 |
| Biostar       | G41-M7                      | [c9bd27ee3c](https://linux-hardware.org/?probe=c9bd27ee3c) | Aug 18, 2020 |
| Fujitsu       | D3091-A1 S26361-D3091-A1    | [ea5ade72ff](https://linux-hardware.org/?probe=ea5ade72ff) | Aug 17, 2020 |
| Foxconn       | 2ABF                        | [24c499fe18](https://linux-hardware.org/?probe=24c499fe18) | Aug 17, 2020 |
| Foxconn       | 2ABF                        | [1fbfbf3d96](https://linux-hardware.org/?probe=1fbfbf3d96) | Aug 17, 2020 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [dfd46d88c4](https://linux-hardware.org/?probe=dfd46d88c4) | Aug 16, 2020 |
| MSI           | E350DM-E33                  | [67f718b80b](https://linux-hardware.org/?probe=67f718b80b) | Aug 16, 2020 |
| MSI           | E350DM-E33                  | [df8f51adcb](https://linux-hardware.org/?probe=df8f51adcb) | Aug 16, 2020 |
| Gigabyte      | M68MT-S2                    | [064e495c95](https://linux-hardware.org/?probe=064e495c95) | Aug 16, 2020 |
| Gigabyte      | M68MT-S2                    | [cdeea77503](https://linux-hardware.org/?probe=cdeea77503) | Aug 16, 2020 |
| Dell          | 0PU052                      | [f7616a2cae](https://linux-hardware.org/?probe=f7616a2cae) | Aug 16, 2020 |
| ASRock        | B85 Pro4                    | [eeee284e00](https://linux-hardware.org/?probe=eeee284e00) | Aug 16, 2020 |
| Gigabyte      | P35T-DQ6                    | [5a25041427](https://linux-hardware.org/?probe=5a25041427) | Aug 15, 2020 |
| Pegatron      | IPM41-D3                    | [e51377d34f](https://linux-hardware.org/?probe=e51377d34f) | Aug 14, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [137f2fa928](https://linux-hardware.org/?probe=137f2fa928) | Aug 13, 2020 |
| HP            | 0B4Ch D                     | [fe39d25754](https://linux-hardware.org/?probe=fe39d25754) | Aug 11, 2020 |
| ASUSTek       | P7P55 LX                    | [c40dc64451](https://linux-hardware.org/?probe=c40dc64451) | Aug 11, 2020 |
| ASUSTek       | PRIME A320M-K/BR            | [09d2e03b31](https://linux-hardware.org/?probe=09d2e03b31) | Aug 11, 2020 |
| ASUSTek       | TUF GAMING X570-PLUS        | [437b159ba3](https://linux-hardware.org/?probe=437b159ba3) | Aug 10, 2020 |
| HP            | 1998                        | [98779de9f0](https://linux-hardware.org/?probe=98779de9f0) | Aug 09, 2020 |
| Dell          | 0RW199                      | [5d2cb2e44b](https://linux-hardware.org/?probe=5d2cb2e44b) | Aug 09, 2020 |
| Dell          | 0JC474                      | [0c56e58a46](https://linux-hardware.org/?probe=0c56e58a46) | Aug 08, 2020 |
| Dell          | 0JC474                      | [f7f2128996](https://linux-hardware.org/?probe=f7f2128996) | Aug 08, 2020 |
| ASRock        | N68C-S UCC                  | [0c80b9688e](https://linux-hardware.org/?probe=0c80b9688e) | Aug 08, 2020 |
| ASRock        | N68C-S UCC                  | [28a4ff7761](https://linux-hardware.org/?probe=28a4ff7761) | Aug 07, 2020 |
| MSI           | X470 GAMING PLUS            | [9708e21a27](https://linux-hardware.org/?probe=9708e21a27) | Aug 07, 2020 |
| Intel         | MAHOBAY                     | [c0dde75b94](https://linux-hardware.org/?probe=c0dde75b94) | Aug 06, 2020 |
| Intel         | MAHOBAY                     | [538f4ce956](https://linux-hardware.org/?probe=538f4ce956) | Aug 05, 2020 |
| ASRock        | Z68 Extreme3 Gen3           | [ab2cdb31ec](https://linux-hardware.org/?probe=ab2cdb31ec) | Aug 05, 2020 |
| Dell          | 0RY206                      | [52b96832f5](https://linux-hardware.org/?probe=52b96832f5) | Aug 05, 2020 |
| Dell          | 0RY206                      | [fea85531ff](https://linux-hardware.org/?probe=fea85531ff) | Aug 05, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [7571c5427f](https://linux-hardware.org/?probe=7571c5427f) | Aug 03, 2020 |
| Dell          | 0200DY A02                  | [88fc41cab0](https://linux-hardware.org/?probe=88fc41cab0) | Aug 01, 2020 |
| Dell          | 0200DY A02                  | [6ce85894b6](https://linux-hardware.org/?probe=6ce85894b6) | Aug 01, 2020 |
| ASUSTek       | P8P67 PRO                   | [2a5cd28ee2](https://linux-hardware.org/?probe=2a5cd28ee2) | Aug 01, 2020 |
| MSI           | A75MA-G55                   | [f6e27145ee](https://linux-hardware.org/?probe=f6e27145ee) | Aug 01, 2020 |
| Dell          | 0RW199                      | [336760aa9b](https://linux-hardware.org/?probe=336760aa9b) | Jul 31, 2020 |
| Intel         | MAHOBAY                     | [f79f3b002e](https://linux-hardware.org/?probe=f79f3b002e) | Jul 31, 2020 |
| Dell          | 0VNP2H A02                  | [def480a828](https://linux-hardware.org/?probe=def480a828) | Jul 29, 2020 |
| Dell          | 0M863N A00                  | [0359c45784](https://linux-hardware.org/?probe=0359c45784) | Jul 29, 2020 |
| Dell          | 0M863N A00                  | [6b435bdcb8](https://linux-hardware.org/?probe=6b435bdcb8) | Jul 29, 2020 |
| Acer          | EQ35M                       | [0a38bdbb37](https://linux-hardware.org/?probe=0a38bdbb37) | Jul 29, 2020 |
| ASRock        | G41M-VS3                    | [bfa97b70c7](https://linux-hardware.org/?probe=bfa97b70c7) | Jul 29, 2020 |
| Intel         | DG31PR AAD97573-302         | [56ad5a6a22](https://linux-hardware.org/?probe=56ad5a6a22) | Jul 29, 2020 |
| ASRock        | FM2A88M Extreme4+           | [94a586edcd](https://linux-hardware.org/?probe=94a586edcd) | Jul 28, 2020 |
| Positivo      | POS-PIG41BO POSITIVO        | [c815c1ad30](https://linux-hardware.org/?probe=c815c1ad30) | Jul 27, 2020 |
| Medion        | B360H4-EM V1.0              | [26e62910da](https://linux-hardware.org/?probe=26e62910da) | Jul 26, 2020 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [5e834a1db4](https://linux-hardware.org/?probe=5e834a1db4) | Jul 26, 2020 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [0957708294](https://linux-hardware.org/?probe=0957708294) | Jul 26, 2020 |
| Gigabyte      | B365M D3H-CF                | [d573d41540](https://linux-hardware.org/?probe=d573d41540) | Jul 25, 2020 |
| Intel         | DG31PR AAD97573-302         | [8081f20c91](https://linux-hardware.org/?probe=8081f20c91) | Jul 25, 2020 |
| HP            | 1497                        | [ef31cca294](https://linux-hardware.org/?probe=ef31cca294) | Jul 25, 2020 |
| NCR           | Pocono                      | [c6a553142f](https://linux-hardware.org/?probe=c6a553142f) | Jul 25, 2020 |
| Positivo      | POS-MI945AA                 | [70488a83b5](https://linux-hardware.org/?probe=70488a83b5) | Jul 25, 2020 |
| Gigabyte      | GA-78LMT-S2                 | [71c07410ee](https://linux-hardware.org/?probe=71c07410ee) | Jul 25, 2020 |
| Gigabyte      | F2A78M-HD2                  | [25ca74bc56](https://linux-hardware.org/?probe=25ca74bc56) | Jul 24, 2020 |
| Gigabyte      | F2A78M-HD2                  | [319c98c8a1](https://linux-hardware.org/?probe=319c98c8a1) | Jul 24, 2020 |
| MSI           | G31TM-P35                   | [956c575a24](https://linux-hardware.org/?probe=956c575a24) | Jul 24, 2020 |
| Toshiba       | STI 910133                  | [21c7264a49](https://linux-hardware.org/?probe=21c7264a49) | Jul 24, 2020 |
| ASUSTek       | PRIME B250M-PLUS/BR         | [974995c15c](https://linux-hardware.org/?probe=974995c15c) | Jul 24, 2020 |
| ASRock        | A320M-HD                    | [2a85bda9fa](https://linux-hardware.org/?probe=2a85bda9fa) | Jul 24, 2020 |
| ASUSTek       | B150M-C D3/BR               | [b46f40c38a](https://linux-hardware.org/?probe=b46f40c38a) | Jul 24, 2020 |
| ASUSTek       | H81M-C/BR                   | [d21c458a4f](https://linux-hardware.org/?probe=d21c458a4f) | Jul 24, 2020 |
| HP            | 1790                        | [7e30cf0101](https://linux-hardware.org/?probe=7e30cf0101) | Jul 23, 2020 |
| Gigabyte      | H110M-H-CF                  | [c96a8407b9](https://linux-hardware.org/?probe=c96a8407b9) | Jul 22, 2020 |
| HP            | 2AF7                        | [fadc92035e](https://linux-hardware.org/?probe=fadc92035e) | Jul 22, 2020 |
| Gigabyte      | G31M-ES2L                   | [cbad09cb89](https://linux-hardware.org/?probe=cbad09cb89) | Jul 21, 2020 |
| HP            | ProLiant ML10 v2            | [84badf8a6a](https://linux-hardware.org/?probe=84badf8a6a) | Jul 21, 2020 |
| MSI           | A75MA-G55                   | [9061f7d6fb](https://linux-hardware.org/?probe=9061f7d6fb) | Jul 20, 2020 |
| HP            | 158A                        | [68f61abed8](https://linux-hardware.org/?probe=68f61abed8) | Jul 20, 2020 |
| Lenovo        | Board                       | [f25b0e7108](https://linux-hardware.org/?probe=f25b0e7108) | Jul 19, 2020 |
| ASRock        | FM2A88M Extreme4+           | [a51dee5095](https://linux-hardware.org/?probe=a51dee5095) | Jul 19, 2020 |
| Gigabyte      | H110M-H-CF                  | [10ce1ef592](https://linux-hardware.org/?probe=10ce1ef592) | Jul 18, 2020 |
| Gigabyte      | H110M-H-CF                  | [f076c0e711](https://linux-hardware.org/?probe=f076c0e711) | Jul 18, 2020 |
| Pegatron      | 2AC2                        | [a7985ac6dc](https://linux-hardware.org/?probe=a7985ac6dc) | Jul 17, 2020 |
| Dell          | 0GM819                      | [b1fc765931](https://linux-hardware.org/?probe=b1fc765931) | Jul 15, 2020 |
| Dell          | 0RW199                      | [ad897861e2](https://linux-hardware.org/?probe=ad897861e2) | Jul 14, 2020 |
| ASUSTek       | PRIME Z270-P                | [a50c792692](https://linux-hardware.org/?probe=a50c792692) | Jul 14, 2020 |
| ASUSTek       | SABERTOOTH 990FX            | [6afbd4537c](https://linux-hardware.org/?probe=6afbd4537c) | Jul 14, 2020 |
| Gigabyte      | B365M D3H-CF                | [019ca65c62](https://linux-hardware.org/?probe=019ca65c62) | Jul 14, 2020 |
| Gigabyte      | B365M D3H-CF                | [6458f60483](https://linux-hardware.org/?probe=6458f60483) | Jul 14, 2020 |
| HP            | 304Ah                       | [5e67b190e0](https://linux-hardware.org/?probe=5e67b190e0) | Jul 13, 2020 |
| HP            | 0A54h                       | [944573af57](https://linux-hardware.org/?probe=944573af57) | Jul 13, 2020 |
| Unknown       | A6VMX                       | [c1db401dad](https://linux-hardware.org/?probe=c1db401dad) | Jul 13, 2020 |
| HP            | 158A                        | [f5c2d58594](https://linux-hardware.org/?probe=f5c2d58594) | Jul 13, 2020 |
| Gigabyte      | F2A78M-HD2                  | [478381d890](https://linux-hardware.org/?probe=478381d890) | Jul 12, 2020 |
| Medion        | MS-7616                     | [c0bca959eb](https://linux-hardware.org/?probe=c0bca959eb) | Jul 12, 2020 |
| eMachines     | EL1352                      | [95bca495a4](https://linux-hardware.org/?probe=95bca495a4) | Jul 11, 2020 |
| Foxconn       | 8657MF-series               | [3c9a2f5db5](https://linux-hardware.org/?probe=3c9a2f5db5) | Jul 11, 2020 |
| Dell          | 0RW199                      | [d3a2cbaa35](https://linux-hardware.org/?probe=d3a2cbaa35) | Jul 11, 2020 |
| Acer          | Extensa X2610G              | [12b9c02a39](https://linux-hardware.org/?probe=12b9c02a39) | Jul 11, 2020 |
| HP            | 0B4Ch D                     | [8a1cc0ea02](https://linux-hardware.org/?probe=8a1cc0ea02) | Jul 11, 2020 |
| HP            | 158A                        | [52e8f357cc](https://linux-hardware.org/?probe=52e8f357cc) | Jul 10, 2020 |
| HP            | 0B4Ch D                     | [33ab28c151](https://linux-hardware.org/?probe=33ab28c151) | Jul 10, 2020 |
| Dell          | 0F6X5P A00                  | [39f78be0f7](https://linux-hardware.org/?probe=39f78be0f7) | Jul 08, 2020 |
| HP            | 1790                        | [2cef9e73a0](https://linux-hardware.org/?probe=2cef9e73a0) | Jul 07, 2020 |
| HP            | 1790                        | [01fcef55ed](https://linux-hardware.org/?probe=01fcef55ed) | Jul 07, 2020 |
| Intel         | DX38BT AAD85848-503         | [6884fbae7e](https://linux-hardware.org/?probe=6884fbae7e) | Jul 07, 2020 |
| Unknown       | Unknown                     | [84ef219ac1](https://linux-hardware.org/?probe=84ef219ac1) | Jul 07, 2020 |
| Intel         | DP55WG AAE57269-406         | [2207d5fce7](https://linux-hardware.org/?probe=2207d5fce7) | Jul 06, 2020 |
| ASUSTek       | M4A89GTD-PRO                | [b066fd06df](https://linux-hardware.org/?probe=b066fd06df) | Jul 06, 2020 |
| Dell          | 0PTTT9 A01                  | [9f5a7645a2](https://linux-hardware.org/?probe=9f5a7645a2) | Jul 06, 2020 |
| Unknown       | Unknown                     | [b47a2fdc9f](https://linux-hardware.org/?probe=b47a2fdc9f) | Jul 05, 2020 |
| ASUSTek       | M4N78-AM V2                 | [f19b8c2801](https://linux-hardware.org/?probe=f19b8c2801) | Jul 05, 2020 |
| Dell          | 0200DY A02                  | [ebe0e51b56](https://linux-hardware.org/?probe=ebe0e51b56) | Jul 05, 2020 |
| Dell          | 0VNP2H A02                  | [4a6497b51d](https://linux-hardware.org/?probe=4a6497b51d) | Jul 04, 2020 |
| Dell          | 0200DY A02                  | [51ecc177d5](https://linux-hardware.org/?probe=51ecc177d5) | Jul 04, 2020 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [99517f7724](https://linux-hardware.org/?probe=99517f7724) | Jul 02, 2020 |
| Dell          | 0CR984 A01                  | [e7c68c86df](https://linux-hardware.org/?probe=e7c68c86df) | Jun 30, 2020 |
| ASUSTek       | PRIME X399-A                | [bb6d6e1681](https://linux-hardware.org/?probe=bb6d6e1681) | Jun 30, 2020 |
| ASRock        | AM2NF6G-VSTA                | [81cb2b3479](https://linux-hardware.org/?probe=81cb2b3479) | Jun 30, 2020 |
| Acer          | Veriton X4630G              | [504ec0d230](https://linux-hardware.org/?probe=504ec0d230) | Jun 30, 2020 |
| MSI           | D2415 S26361-D2415-A10      | [cdeb87380b](https://linux-hardware.org/?probe=cdeb87380b) | Jun 30, 2020 |
| Dell          | 084J0R A00                  | [1d98c0ae1e](https://linux-hardware.org/?probe=1d98c0ae1e) | Jun 30, 2020 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [e3494b485e](https://linux-hardware.org/?probe=e3494b485e) | Jun 30, 2020 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [72f4001d32](https://linux-hardware.org/?probe=72f4001d32) | Jun 30, 2020 |
| Dell          | 0RW199                      | [eb2e75e011](https://linux-hardware.org/?probe=eb2e75e011) | Jun 29, 2020 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [dece2951c4](https://linux-hardware.org/?probe=dece2951c4) | Jun 29, 2020 |
| ASRock        | J3455M                      | [0fc2987e1c](https://linux-hardware.org/?probe=0fc2987e1c) | Jun 29, 2020 |
| Acer          | Aspire X3400G               | [8ecd5df128](https://linux-hardware.org/?probe=8ecd5df128) | Jun 27, 2020 |
| ASRock        | N68C-S UCC                  | [19c8257ed1](https://linux-hardware.org/?probe=19c8257ed1) | Jun 26, 2020 |
| ASRock        | N68C-S UCC                  | [a56bd9dd64](https://linux-hardware.org/?probe=a56bd9dd64) | Jun 26, 2020 |
| ASUSTek       | X99-DELUXE                  | [1adcab5b3c](https://linux-hardware.org/?probe=1adcab5b3c) | Jun 26, 2020 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [5f75d137ed](https://linux-hardware.org/?probe=5f75d137ed) | Jun 26, 2020 |
| Dell          | 0RW203                      | [8ba004d478](https://linux-hardware.org/?probe=8ba004d478) | Jun 25, 2020 |
| Gigabyte      | H110M-S2-CF                 | [063d50afa1](https://linux-hardware.org/?probe=063d50afa1) | Jun 25, 2020 |
| Packard Be... | MCP73VT-PM                  | [1af9bd68bf](https://linux-hardware.org/?probe=1af9bd68bf) | Jun 24, 2020 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [176c1bcb0a](https://linux-hardware.org/?probe=176c1bcb0a) | Jun 24, 2020 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | [22b31e99cc](https://linux-hardware.org/?probe=22b31e99cc) | Jun 24, 2020 |
| Dell          | 0RW203                      | [7e50eb34dc](https://linux-hardware.org/?probe=7e50eb34dc) | Jun 24, 2020 |
| Dell          | 0RW203                      | [b853674a1a](https://linux-hardware.org/?probe=b853674a1a) | Jun 24, 2020 |
| Dell          | 0RW199                      | [c74695aacf](https://linux-hardware.org/?probe=c74695aacf) | Jun 24, 2020 |
| Acer          | EQ35M                       | [f2dbd9e441](https://linux-hardware.org/?probe=f2dbd9e441) | Jun 23, 2020 |
| Acer          | EQ35M                       | [5ebf9a4f1a](https://linux-hardware.org/?probe=5ebf9a4f1a) | Jun 23, 2020 |
| Nvidia        | NF-MCP68                    | [6b42b5244e](https://linux-hardware.org/?probe=6b42b5244e) | Jun 23, 2020 |
| Gigabyte      | B85M-D3H                    | [48f5b587fe](https://linux-hardware.org/?probe=48f5b587fe) | Jun 23, 2020 |
| Lenovo        | ThinkStation D20 4158CM1    | [59660a488b](https://linux-hardware.org/?probe=59660a488b) | Jun 22, 2020 |
| Gigabyte      | H110N-CF                    | [919163ff41](https://linux-hardware.org/?probe=919163ff41) | Jun 22, 2020 |
| Lenovo        | ThinkStation D20 4158CM1    | [d1ef95aafa](https://linux-hardware.org/?probe=d1ef95aafa) | Jun 22, 2020 |
| ASRock        | ALiveNF7G-GLAN              | [747c29d2f3](https://linux-hardware.org/?probe=747c29d2f3) | Jun 21, 2020 |
| ASRock        | A75M-HVS                    | [729f379298](https://linux-hardware.org/?probe=729f379298) | Jun 20, 2020 |
| Dell          | 0RW199                      | [afdc1b6a20](https://linux-hardware.org/?probe=afdc1b6a20) | Jun 20, 2020 |
| HP            | 3032h                       | [b95914d3ef](https://linux-hardware.org/?probe=b95914d3ef) | Jun 20, 2020 |
| ASUSTek       | H87M-PLUS                   | [03ab491206](https://linux-hardware.org/?probe=03ab491206) | Jun 20, 2020 |
| Gigabyte      | Z370 HD3-CF                 | [b22002ee7d](https://linux-hardware.org/?probe=b22002ee7d) | Jun 20, 2020 |
| HP            | 3032h                       | [7daea29a60](https://linux-hardware.org/?probe=7daea29a60) | Jun 19, 2020 |
| ASUSTek       | PRIME X399-A                | [48e5b1d9fe](https://linux-hardware.org/?probe=48e5b1d9fe) | Jun 19, 2020 |
| Gigabyte      | MZBSWBP-00                  | [02c5eb9954](https://linux-hardware.org/?probe=02c5eb9954) | Jun 18, 2020 |
| Dell          | 0WG233                      | [a830ee5f45](https://linux-hardware.org/?probe=a830ee5f45) | Jun 18, 2020 |
| Dell          | 0WG233                      | [29530016f6](https://linux-hardware.org/?probe=29530016f6) | Jun 18, 2020 |
| ASUSTek       | H87M-PLUS                   | [d7ea78f109](https://linux-hardware.org/?probe=d7ea78f109) | Jun 18, 2020 |
| Dell          | 084J0R A00                  | [bb9b6a638d](https://linux-hardware.org/?probe=bb9b6a638d) | Jun 17, 2020 |
| Dell          | 084J0R A00                  | [b5ed051f73](https://linux-hardware.org/?probe=b5ed051f73) | Jun 17, 2020 |
| Dell          | 0200DY A03                  | [28fa360e16](https://linux-hardware.org/?probe=28fa360e16) | Jun 17, 2020 |
| MSI           | D2415 S26361-D2415-A10      | [047a92b8b5](https://linux-hardware.org/?probe=047a92b8b5) | Jun 17, 2020 |
| HP            | 1497                        | [7e8347d308](https://linux-hardware.org/?probe=7e8347d308) | Jun 17, 2020 |
| Dell          | 03NVJ6 A00                  | [a129d8050e](https://linux-hardware.org/?probe=a129d8050e) | Jun 16, 2020 |
| Qbex          | H61H2-M2                    | [41819671fb](https://linux-hardware.org/?probe=41819671fb) | Jun 15, 2020 |
| ASUSTek       | M4N78-AM V2                 | [388c7aac3a](https://linux-hardware.org/?probe=388c7aac3a) | Jun 15, 2020 |
| NCR           | Pocono                      | [a44ee61726](https://linux-hardware.org/?probe=a44ee61726) | Jun 15, 2020 |
| Unknown       | P4M800CE-8237               | [1e85cb931c](https://linux-hardware.org/?probe=1e85cb931c) | Jun 14, 2020 |
| ASRock        | 870 Extreme3                | [6fd6b24f09](https://linux-hardware.org/?probe=6fd6b24f09) | Jun 14, 2020 |
| ASRock        | 870 Extreme3                | [cff93a50da](https://linux-hardware.org/?probe=cff93a50da) | Jun 14, 2020 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [a3681caed5](https://linux-hardware.org/?probe=a3681caed5) | Jun 14, 2020 |
| ECS           | Z77H2-A2X Deluxe            | [5bb6af2e45](https://linux-hardware.org/?probe=5bb6af2e45) | Jun 14, 2020 |
| ECS           | Z77H2-A2X Deluxe            | [c06f108477](https://linux-hardware.org/?probe=c06f108477) | Jun 14, 2020 |
| Dell          | 0KP561                      | [0a700a55b8](https://linux-hardware.org/?probe=0a700a55b8) | Jun 13, 2020 |
| ASRock        | P67 Pro3                    | [deaf1b5c77](https://linux-hardware.org/?probe=deaf1b5c77) | Jun 13, 2020 |
| Gigabyte      | Z170MX-Gaming 5             | [2680b47951](https://linux-hardware.org/?probe=2680b47951) | Jun 13, 2020 |
| Gigabyte      | Z170MX-Gaming 5             | [731af3411f](https://linux-hardware.org/?probe=731af3411f) | Jun 13, 2020 |
| Gigabyte      | Z170MX-Gaming 5             | [e21c7882b6](https://linux-hardware.org/?probe=e21c7882b6) | Jun 12, 2020 |
| Gigabyte      | Z170MX-Gaming 5             | [46f3f502e7](https://linux-hardware.org/?probe=46f3f502e7) | Jun 12, 2020 |
| Gigabyte      | H61M-USB3V                  | [4765048ec9](https://linux-hardware.org/?probe=4765048ec9) | Jun 12, 2020 |
| ASUSTek       | H87M-PLUS                   | [ab4e5215f2](https://linux-hardware.org/?probe=ab4e5215f2) | Jun 11, 2020 |
| ASUSTek       | D820MT_D820SF_BM3CE         | [e30aeca065](https://linux-hardware.org/?probe=e30aeca065) | Jun 11, 2020 |
| MSI           | 970 GAMING                  | [053fd50552](https://linux-hardware.org/?probe=053fd50552) | Jun 11, 2020 |
| ASUSTek       | PRIME Z490-P                | [a3e534b4f8](https://linux-hardware.org/?probe=a3e534b4f8) | Jun 10, 2020 |
| Gigabyte      | H110N-CF                    | [35a51da451](https://linux-hardware.org/?probe=35a51da451) | Jun 09, 2020 |
| Intel         | D54250WYK H13922-304        | [3447a97b5f](https://linux-hardware.org/?probe=3447a97b5f) | Jun 07, 2020 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | [b35f2a71dd](https://linux-hardware.org/?probe=b35f2a71dd) | Jun 07, 2020 |
| ASRock        | B85 Pro4                    | [a24fcca14f](https://linux-hardware.org/?probe=a24fcca14f) | Jun 06, 2020 |
| ASRock        | N68C-GS FX                  | [a59a5c001f](https://linux-hardware.org/?probe=a59a5c001f) | Jun 06, 2020 |
| ASUSTek       | P8H67-M PRO                 | [c60bd8dd4d](https://linux-hardware.org/?probe=c60bd8dd4d) | Jun 06, 2020 |
| Acer          | EG43M                       | [52485c6237](https://linux-hardware.org/?probe=52485c6237) | Jun 06, 2020 |
| Gigabyte      | H61M-USB3V                  | [747637fba1](https://linux-hardware.org/?probe=747637fba1) | Jun 05, 2020 |
| Qbex          | H61H2-M2                    | [77201fbc96](https://linux-hardware.org/?probe=77201fbc96) | Jun 05, 2020 |
| ASUSTek       | P8B75-M                     | [c2d585b9a7](https://linux-hardware.org/?probe=c2d585b9a7) | Jun 05, 2020 |
| Acer          | Predator G3620              | [2b5cf13491](https://linux-hardware.org/?probe=2b5cf13491) | Jun 05, 2020 |
| Acer          | Predator G3620              | [6120afc333](https://linux-hardware.org/?probe=6120afc333) | Jun 05, 2020 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [22ab1ab49c](https://linux-hardware.org/?probe=22ab1ab49c) | Jun 04, 2020 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [546a8d0043](https://linux-hardware.org/?probe=546a8d0043) | Jun 04, 2020 |
| Dell          | 0CT017                      | [7a9a09ec49](https://linux-hardware.org/?probe=7a9a09ec49) | Jun 03, 2020 |
| Gigabyte      | H110N-CF                    | [3e9da1e0fc](https://linux-hardware.org/?probe=3e9da1e0fc) | Jun 02, 2020 |
| ASUSTek       | PRIME X570-PRO              | [c9f4ab0214](https://linux-hardware.org/?probe=c9f4ab0214) | Jun 02, 2020 |
| Gigabyte      | H61M-USB3V                  | [de39075832](https://linux-hardware.org/?probe=de39075832) | Jun 02, 2020 |
| ASUSTek       | M5A88-M                     | [afcc06eda5](https://linux-hardware.org/?probe=afcc06eda5) | May 31, 2020 |
| HP            | 1497                        | [5d74a91abd](https://linux-hardware.org/?probe=5d74a91abd) | May 31, 2020 |
| Dell          | 0GXM1W A02                  | [dcfdf5c797](https://linux-hardware.org/?probe=dcfdf5c797) | May 30, 2020 |
| MSI           | 970 GAMING                  | [458224380d](https://linux-hardware.org/?probe=458224380d) | May 29, 2020 |
| ASUSTek       | P5G41T-M LX3                | [e07f3a61e2](https://linux-hardware.org/?probe=e07f3a61e2) | May 29, 2020 |
| ASUSTek       | PRIME B450-PLUS             | [315a06e722](https://linux-hardware.org/?probe=315a06e722) | May 29, 2020 |
| HP            | 1497                        | [e2564ed256](https://linux-hardware.org/?probe=e2564ed256) | May 28, 2020 |
| HP            | 1497                        | [6240722860](https://linux-hardware.org/?probe=6240722860) | May 28, 2020 |
| HP            | 1497                        | [0260e1cca8](https://linux-hardware.org/?probe=0260e1cca8) | May 28, 2020 |
| MSI           | 970 GAMING                  | [95565ae92d](https://linux-hardware.org/?probe=95565ae92d) | May 27, 2020 |
| MSI           | Z97 MPOWER                  | [526e3a4646](https://linux-hardware.org/?probe=526e3a4646) | May 27, 2020 |
| Fujitsu       | D3162-C1 S26361-D3162-C1    | [0315d9c9c4](https://linux-hardware.org/?probe=0315d9c9c4) | May 27, 2020 |
| ASUSTek       | B150M-A                     | [6e5665e630](https://linux-hardware.org/?probe=6e5665e630) | May 27, 2020 |
| ASUSTek       | B150M-A                     | [b56e76e2e2](https://linux-hardware.org/?probe=b56e76e2e2) | May 27, 2020 |
| ASRock        | 985GM-GS3 FX                | [bde47e7839](https://linux-hardware.org/?probe=bde47e7839) | May 27, 2020 |
| Dell          | 0M858N A01                  | [1f0f11722b](https://linux-hardware.org/?probe=1f0f11722b) | May 26, 2020 |
| Gigabyte      | Z97X-UD5H                   | [19610eb160](https://linux-hardware.org/?probe=19610eb160) | May 25, 2020 |
| ASUSTek       | P7H55                       | [4533b1206a](https://linux-hardware.org/?probe=4533b1206a) | May 25, 2020 |
| ASUSTek       | PRIME Z270-K                | [e8253aea47](https://linux-hardware.org/?probe=e8253aea47) | May 25, 2020 |
| ASUSTek       | X79-DELUXE                  | [c41528bf74](https://linux-hardware.org/?probe=c41528bf74) | May 25, 2020 |
| ASUSTek       | X79-DELUXE                  | [a26d27687f](https://linux-hardware.org/?probe=a26d27687f) | May 25, 2020 |
| ASUSTek       | X79-DELUXE                  | [122ff2be33](https://linux-hardware.org/?probe=122ff2be33) | May 25, 2020 |
| Fujitsu       | D3162-C1 S26361-D3162-C1    | [66e358b202](https://linux-hardware.org/?probe=66e358b202) | May 24, 2020 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [63e6a5472b](https://linux-hardware.org/?probe=63e6a5472b) | May 24, 2020 |
| ASUSTek       | TUF B450-PLUS GAMING        | [c993e8d96e](https://linux-hardware.org/?probe=c993e8d96e) | May 24, 2020 |
| AOpen         | D1001 C26361-D1001          | [1c0ca9ced6](https://linux-hardware.org/?probe=1c0ca9ced6) | May 24, 2020 |
| Gigabyte      | P55M-UD2                    | [6898645243](https://linux-hardware.org/?probe=6898645243) | May 20, 2020 |
| Gigabyte      | GA-MA78GM-S2H               | [f88515ee3b](https://linux-hardware.org/?probe=f88515ee3b) | May 19, 2020 |
| ASUSTek       | Z87-PRO                     | [a623e40ce4](https://linux-hardware.org/?probe=a623e40ce4) | May 18, 2020 |
| ASUSTek       | Z87-PRO                     | [1d492b07d8](https://linux-hardware.org/?probe=1d492b07d8) | May 18, 2020 |
| ASUSTek       | Z87-PRO                     | [986ae187fd](https://linux-hardware.org/?probe=986ae187fd) | May 18, 2020 |
| ASRock        | N68-GS4 FX                  | [93091cc8d8](https://linux-hardware.org/?probe=93091cc8d8) | May 17, 2020 |
| Fujitsu       | D2950-A1 S26361-D2950-A1    | [8a0cfc27c5](https://linux-hardware.org/?probe=8a0cfc27c5) | May 17, 2020 |
| ASRock        | N68-GS4 FX                  | [8c0ff90434](https://linux-hardware.org/?probe=8c0ff90434) | May 17, 2020 |
| ASRock        | N68-GS4 FX                  | [a7bd57f74b](https://linux-hardware.org/?probe=a7bd57f74b) | May 17, 2020 |
| ASRock        | N68-GS4 FX                  | [becbe89d27](https://linux-hardware.org/?probe=becbe89d27) | May 17, 2020 |
| Acer          | Aspire XC-230               | [20a5ed6ba5](https://linux-hardware.org/?probe=20a5ed6ba5) | May 17, 2020 |
| Acer          | Aspire XC-230               | [848203d79a](https://linux-hardware.org/?probe=848203d79a) | May 16, 2020 |
| ASUSTek       | PRIME B450-PLUS             | [0c373b0975](https://linux-hardware.org/?probe=0c373b0975) | May 16, 2020 |
| Fujitsu       | D3091-A1 S26361-D3091-A1    | [9a52c07d15](https://linux-hardware.org/?probe=9a52c07d15) | May 16, 2020 |
| ASRock        | N68-GS4 FX                  | [4bdd011b5f](https://linux-hardware.org/?probe=4bdd011b5f) | May 16, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [96677ee210](https://linux-hardware.org/?probe=96677ee210) | May 16, 2020 |
| Dell          | 0T568R A00                  | [067d6bd987](https://linux-hardware.org/?probe=067d6bd987) | May 16, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [15d0451825](https://linux-hardware.org/?probe=15d0451825) | May 16, 2020 |
| ASUSTek       | P5KC                        | [430457f5ee](https://linux-hardware.org/?probe=430457f5ee) | May 15, 2020 |
| ASUSTek       | PRIME B450-PLUS             | [4d70fb1cea](https://linux-hardware.org/?probe=4d70fb1cea) | May 14, 2020 |
| MSI           | B450 TOMAHAWK               | [d8691a0cb1](https://linux-hardware.org/?probe=d8691a0cb1) | May 14, 2020 |
| Gigabyte      | X299X AORUS MASTER          | [e9d37a665e](https://linux-hardware.org/?probe=e9d37a665e) | May 14, 2020 |
| HP            | 339A                        | [ab1afaacc9](https://linux-hardware.org/?probe=ab1afaacc9) | May 14, 2020 |
| Gigabyte      | H81M-S2V                    | [735da03dae](https://linux-hardware.org/?probe=735da03dae) | May 12, 2020 |
| Dell          | 0M5DCD A00                  | [fedf72db4b](https://linux-hardware.org/?probe=fedf72db4b) | May 12, 2020 |
| ASUSTek       | TUF B450-PLUS GAMING        | [b511620a0f](https://linux-hardware.org/?probe=b511620a0f) | May 11, 2020 |
| ASUSTek       | TUF B450-PLUS GAMING        | [26b8c415b9](https://linux-hardware.org/?probe=26b8c415b9) | May 11, 2020 |
| Fujitsu Si... | D1931 S26361-D1931          | [2fe7775c8f](https://linux-hardware.org/?probe=2fe7775c8f) | May 11, 2020 |
| Fujitsu Si... | D2584-A1 S26361-D2584-A1    | [4951f4a759](https://linux-hardware.org/?probe=4951f4a759) | May 11, 2020 |
| Fujitsu Si... | D2584-A1 S26361-D2584-A1    | [1b9e4e9933](https://linux-hardware.org/?probe=1b9e4e9933) | May 11, 2020 |
| Gigabyte      | GA-880GM-UD2H               | [6e911b9178](https://linux-hardware.org/?probe=6e911b9178) | May 11, 2020 |
| MSI           | X470 GAMING PLUS MAX        | [350782a4b1](https://linux-hardware.org/?probe=350782a4b1) | May 11, 2020 |
| MSI           | X299 GAMING M7 ACK          | [98aab5531b](https://linux-hardware.org/?probe=98aab5531b) | May 11, 2020 |
| Fujitsu       | D3091-A1 S26361-D3091-A1    | [7f2672b702](https://linux-hardware.org/?probe=7f2672b702) | May 10, 2020 |
| Gigabyte      | GA-970A-UD3                 | [efad785981](https://linux-hardware.org/?probe=efad785981) | May 09, 2020 |
| ASRock        | N68-GS4 FX                  | [8a18014920](https://linux-hardware.org/?probe=8a18014920) | May 09, 2020 |
| ASRock        | N68-GS4 FX                  | [111f9b3fa0](https://linux-hardware.org/?probe=111f9b3fa0) | May 09, 2020 |
| ASRock        | N68-GS4 FX                  | [1e283f366d](https://linux-hardware.org/?probe=1e283f366d) | May 09, 2020 |
| ASUSTek       | P9X79 WS                    | [78e4f8dc9f](https://linux-hardware.org/?probe=78e4f8dc9f) | May 09, 2020 |
| MSI           | X99S SLI PLUS               | [a48b719552](https://linux-hardware.org/?probe=a48b719552) | May 08, 2020 |
| ASRock        | N68-GS4 FX                  | [3a44deaa73](https://linux-hardware.org/?probe=3a44deaa73) | May 08, 2020 |
| ASRock        | N68-GS4 FX                  | [f70ba23054](https://linux-hardware.org/?probe=f70ba23054) | May 08, 2020 |
| Fujitsu       | D3091-A1 S26361-D3091-A1    | [3b00d6e44c](https://linux-hardware.org/?probe=3b00d6e44c) | May 08, 2020 |
| HP            | 805D                        | [16daf16986](https://linux-hardware.org/?probe=16daf16986) | May 07, 2020 |
| Dell          | 0GU083 A00                  | [5f05efe407](https://linux-hardware.org/?probe=5f05efe407) | May 06, 2020 |
| BCM           | MX280NI                     | [69678caf19](https://linux-hardware.org/?probe=69678caf19) | May 06, 2020 |
| BCM           | MX280NI                     | [f8a9460c9e](https://linux-hardware.org/?probe=f8a9460c9e) | May 06, 2020 |
| ASUSTek       | P8H61-I LX R2.0             | [0ac9cd75b4](https://linux-hardware.org/?probe=0ac9cd75b4) | May 06, 2020 |
| ASUSTek       | A68HM-PLUS                  | [e7912d8ef0](https://linux-hardware.org/?probe=e7912d8ef0) | May 06, 2020 |
| Dell          | 0T568R A00                  | [b2771ebd93](https://linux-hardware.org/?probe=b2771ebd93) | May 06, 2020 |
| Lenovo        | Board                       | [21286af23b](https://linux-hardware.org/?probe=21286af23b) | May 06, 2020 |
| EVGA          | P55 SLI LE E653 Ibex Pea... | [251ae449b6](https://linux-hardware.org/?probe=251ae449b6) | May 06, 2020 |
| MSI           | Z68A-G45                    | [6a2075dd33](https://linux-hardware.org/?probe=6a2075dd33) | May 04, 2020 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [28c7267fc9](https://linux-hardware.org/?probe=28c7267fc9) | May 04, 2020 |
| ASUSTek       | H81M-C/BR                   | [07ca6e636a](https://linux-hardware.org/?probe=07ca6e636a) | May 03, 2020 |
| Lenovo        | Board                       | [94dc4b06b1](https://linux-hardware.org/?probe=94dc4b06b1) | May 03, 2020 |
| ASRock        | B450M-HDV R4.0              | [95aefb5e5e](https://linux-hardware.org/?probe=95aefb5e5e) | May 01, 2020 |
| ASUSTek       | P5KPL-AM SE                 | [1862a67c79](https://linux-hardware.org/?probe=1862a67c79) | Apr 30, 2020 |
| ASUSTek       | P5KPL-AM SE                 | [1e4c905191](https://linux-hardware.org/?probe=1e4c905191) | Apr 30, 2020 |
| Dell          | 0FJ030                      | [8cae3f8b96](https://linux-hardware.org/?probe=8cae3f8b96) | Apr 29, 2020 |
| ASRock        | AOD790GX/128M               | [8ba6b55d11](https://linux-hardware.org/?probe=8ba6b55d11) | Apr 28, 2020 |
| ASUSTek       | P5K                         | [c77f4d5237](https://linux-hardware.org/?probe=c77f4d5237) | Apr 28, 2020 |
| Gigabyte      | GA-880GM-UD2H               | [b98a1c50e8](https://linux-hardware.org/?probe=b98a1c50e8) | Apr 28, 2020 |
| Medion        | B350A4-EM                   | [3163f6a0fa](https://linux-hardware.org/?probe=3163f6a0fa) | Apr 28, 2020 |
| HP            | 3397                        | [bdcea30c27](https://linux-hardware.org/?probe=bdcea30c27) | Apr 27, 2020 |
| Gigabyte      | GA-880GM-UD2H               | [1c46568976](https://linux-hardware.org/?probe=1c46568976) | Apr 26, 2020 |
| EVGA          | 120-LF-E650                 | [b79bcdee65](https://linux-hardware.org/?probe=b79bcdee65) | Apr 26, 2020 |
| Lenovo        | MAHOBAY                     | [90b21482b9](https://linux-hardware.org/?probe=90b21482b9) | Apr 26, 2020 |
| ASUSTek       | P8Z68-V                     | [a5d4bc9b8a](https://linux-hardware.org/?probe=a5d4bc9b8a) | Apr 25, 2020 |
| ASRock        | G31M-GS                     | [2c7362b9cb](https://linux-hardware.org/?probe=2c7362b9cb) | Apr 25, 2020 |
| Gigabyte      | Z370 HD3-CF                 | [4672efc222](https://linux-hardware.org/?probe=4672efc222) | Apr 25, 2020 |
| Gigabyte      | Z370 HD3-CF                 | [aed74d2030](https://linux-hardware.org/?probe=aed74d2030) | Apr 25, 2020 |
| MSI           | B450 TOMAHAWK               | [047b4bf38a](https://linux-hardware.org/?probe=047b4bf38a) | Apr 24, 2020 |
| HP            | 3397                        | [f9141c1b9d](https://linux-hardware.org/?probe=f9141c1b9d) | Apr 20, 2020 |
| MSI           | MPG Z390 GAMING PLUS        | [e42a1e57a6](https://linux-hardware.org/?probe=e42a1e57a6) | Apr 07, 2020 |
| MSI           | MPG Z390 GAMING PLUS        | [27dca0b99c](https://linux-hardware.org/?probe=27dca0b99c) | Apr 05, 2020 |
| Gigabyte      | H170M-DS3H-CF               | [28730747e6](https://linux-hardware.org/?probe=28730747e6) | Jan 07, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Desktops | Percent |
|---------------------|----------|---------|
| 5.4.0-42-generic    | 41       | 4.74%   |
| 5.4.0-48-generic    | 28       | 3.24%   |
| 5.4.0-42-lowlatency | 23       | 2.66%   |
| 5.4.0-52-generic    | 22       | 2.54%   |
| 5.4.0-58-generic    | 19       | 2.2%    |
| 5.4.0-54-generic    | 19       | 2.2%    |
| 5.4.0-37-generic    | 18       | 2.08%   |
| 5.4.0-65-generic    | 17       | 1.97%   |
| 5.4.0-26-generic    | 17       | 1.97%   |
| 5.4.0-29-generic    | 16       | 1.85%   |
| 5.4.0-40-generic    | 15       | 1.73%   |
| 5.4.0-40-lowlatency | 14       | 1.62%   |
| 5.4.0-29-lowlatency | 14       | 1.62%   |
| 5.4.0-52-lowlatency | 13       | 1.5%    |
| 5.4.0-72-generic    | 12       | 1.39%   |
| 5.4.0-66-generic    | 12       | 1.39%   |
| 5.4.0-91-generic    | 11       | 1.27%   |
| 5.4.0-70-generic    | 11       | 1.27%   |
| 5.4.0-47-lowlatency | 11       | 1.27%   |
| 5.4.0-37-lowlatency | 11       | 1.27%   |
| 5.4.0-33-generic    | 11       | 1.27%   |
| 5.4.0-74-generic    | 10       | 1.16%   |
| 5.4.0-58-lowlatency | 10       | 1.16%   |
| 5.4.0-48-lowlatency | 10       | 1.16%   |
| 5.4.0-47-generic    | 10       | 1.16%   |
| 5.4.0-45-generic    | 10       | 1.16%   |
| 5.4.0-89-generic    | 8        | 0.92%   |
| 5.4.0-88-generic    | 8        | 0.92%   |
| 5.4.0-80-generic    | 8        | 0.92%   |
| 5.4.0-77-generic    | 8        | 0.92%   |
| 5.4.0-65-lowlatency | 8        | 0.92%   |
| 5.4.0-31-generic    | 8        | 0.92%   |
| 5.11.0-37-generic   | 8        | 0.92%   |
| 5.8.0-50-generic    | 7        | 0.81%   |
| 5.4.0-81-generic    | 7        | 0.81%   |
| 5.4.0-73-generic    | 7        | 0.81%   |
| 5.4.0-60-generic    | 7        | 0.81%   |
| 5.4.0-56-generic    | 7        | 0.81%   |
| 5.4.0-51-generic    | 7        | 0.81%   |
| 5.4.0-39-generic    | 7        | 0.81%   |
| 5.4.0-26-lowlatency | 7        | 0.81%   |
| 5.4.0-107-generic   | 7        | 0.81%   |
| 5.8.0-43-generic    | 6        | 0.69%   |
| 5.4.0-77-lowlatency | 6        | 0.69%   |
| 5.4.0-72-lowlatency | 6        | 0.69%   |
| 5.4.0-70-lowlatency | 6        | 0.69%   |
| 5.4.0-66-lowlatency | 6        | 0.69%   |
| 5.13.0-30-generic   | 6        | 0.69%   |
| 5.11.0-40-generic   | 6        | 0.69%   |
| 5.11.0-27-generic   | 6        | 0.69%   |
| 5.8.0-48-lowlatency | 5        | 0.58%   |
| 5.8.0-48-generic    | 5        | 0.58%   |
| 5.4.0-91-lowlatency | 5        | 0.58%   |
| 5.4.0-90-generic    | 5        | 0.58%   |
| 5.4.0-67-lowlatency | 5        | 0.58%   |
| 5.4.0-64-lowlatency | 5        | 0.58%   |
| 5.4.0-62-generic    | 5        | 0.58%   |
| 5.4.0-56-lowlatency | 5        | 0.58%   |
| 5.4.0-53-lowlatency | 5        | 0.58%   |
| 5.4.0-53-generic    | 5        | 0.58%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 571      | 76.34%  |
| 5.8.0   | 64       | 8.56%   |
| 5.11.0  | 60       | 8.02%   |
| 5.13.0  | 29       | 3.88%   |
| 5.9.16  | 2        | 0.27%   |
| 5.6.0   | 2        | 0.27%   |
| 5.9.14  | 1        | 0.13%   |
| 5.9.0   | 1        | 0.13%   |
| 5.8.5   | 1        | 0.13%   |
| 5.8.1   | 1        | 0.13%   |
| 5.7.17  | 1        | 0.13%   |
| 5.7.1   | 1        | 0.13%   |
| 5.6.6   | 1        | 0.13%   |
| 5.4.64  | 1        | 0.13%   |
| 5.3.0   | 1        | 0.13%   |
| 5.16.0  | 1        | 0.13%   |
| 5.15.1  | 1        | 0.13%   |
| 5.12.2  | 1        | 0.13%   |
| 5.12.17 | 1        | 0.13%   |
| 5.12.12 | 1        | 0.13%   |
| 5.12.10 | 1        | 0.13%   |
| 5.11.16 | 1        | 0.13%   |
| 5.10.27 | 1        | 0.13%   |
| 5.10.13 | 1        | 0.13%   |
| 4.4.0   | 1        | 0.13%   |
| 4.15.0  | 1        | 0.13%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 572      | 76.68%  |
| 5.8     | 66       | 8.85%   |
| 5.11    | 60       | 8.04%   |
| 5.13    | 29       | 3.89%   |
| 5.9     | 4        | 0.54%   |
| 5.6     | 3        | 0.4%    |
| 5.12    | 3        | 0.4%    |
| 5.7     | 2        | 0.27%   |
| 5.10    | 2        | 0.27%   |
| 5.3     | 1        | 0.13%   |
| 5.16    | 1        | 0.13%   |
| 5.15    | 1        | 0.13%   |
| 4.4     | 1        | 0.13%   |
| 4.15    | 1        | 0.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 730      | 99.86%  |
| armv7l | 1        | 0.14%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| XFCE     | 705      | 96.44%  |
| GNOME    | 22       | 3.01%   |
| KDE5     | 2        | 0.27%   |
| LXQt     | 1        | 0.14%   |
| Cinnamon | 1        | 0.14%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 705      | 96.44%  |
| Tty     | 20       | 2.74%   |
| Web     | 3        | 0.41%   |
| Wayland | 2        | 0.27%   |
| Unknown | 1        | 0.14%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 421      | 56.21%  |
| LightDM | 158      | 21.09%  |
| TDM     | 156      | 20.83%  |
| GDM     | 8        | 1.07%   |
| XDM     | 3        | 0.4%    |
| GDM3    | 2        | 0.27%   |
| SDDM    | 1        | 0.13%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 238      | 32.47%  |
| de_DE | 94       | 12.82%  |
| fr_FR | 67       | 9.14%   |
| pt_BR | 41       | 5.59%   |
| en_GB | 34       | 4.64%   |
| en_CA | 33       | 4.5%    |
| it_IT | 29       | 3.96%   |
| ru_RU | 27       | 3.68%   |
| es_ES | 15       | 2.05%   |
| C     | 14       | 1.91%   |
| pl_PL | 13       | 1.77%   |
| en_AU | 12       | 1.64%   |
| nl_NL | 11       | 1.5%    |
| ja_JP | 11       | 1.5%    |
| hu_HU | 10       | 1.36%   |
| es_AR | 10       | 1.36%   |
| es_MX | 7        | 0.95%   |
| fr_CA | 6        | 0.82%   |
| sv_SE | 4        | 0.55%   |
| ro_RO | 4        | 0.55%   |
| fr_BE | 4        | 0.55%   |
| es_CO | 4        | 0.55%   |
| de_CH | 4        | 0.55%   |
| de_AT | 4        | 0.55%   |
| zh_TW | 3        | 0.41%   |
| ru_UA | 3        | 0.41%   |
| fr_CH | 3        | 0.41%   |
| fi_FI | 3        | 0.41%   |
| es_UY | 3        | 0.41%   |
| sl_SI | 2        | 0.27%   |
| pt_PT | 2        | 0.27%   |
| en_ZA | 2        | 0.27%   |
| en_IN | 2        | 0.27%   |
| zh_CN | 1        | 0.14%   |
| uk_UA | 1        | 0.14%   |
| th_TH | 1        | 0.14%   |
| nl_BE | 1        | 0.14%   |
| lv_LV | 1        | 0.14%   |
| lt_LT | 1        | 0.14%   |
| id_ID | 1        | 0.14%   |
| es_NI | 1        | 0.14%   |
| en_NZ | 1        | 0.14%   |
| en_IL | 1        | 0.14%   |
| el_GR | 1        | 0.14%   |
| da_DK | 1        | 0.14%   |
| cs_CZ | 1        | 0.14%   |
| bs_BA | 1        | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 526      | 71.37%  |
| EFI  | 211      | 28.63%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 689      | 93.74%  |
| Overlay | 19       | 2.59%   |
| Zfs     | 11       | 1.5%    |
| Btrfs   | 10       | 1.36%   |
| Xfs     | 5        | 0.68%   |
| Ext3    | 1        | 0.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 491      | 67.08%  |
| GPT     | 126      | 17.21%  |
| MBR     | 115      | 15.71%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 572      | 77.09%  |
| Yes       | 170      | 22.91%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 424      | 57.22%  |
| Yes       | 317      | 42.78%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 151      | 20.66%  |
| Gigabyte Technology | 100      | 13.68%  |
| Dell                | 84       | 11.49%  |
| Hewlett-Packard     | 75       | 10.26%  |
| ASRock              | 71       | 9.71%   |
| MSI                 | 60       | 8.21%   |
| Lenovo              | 28       | 3.83%   |
| Acer                | 25       | 3.42%   |
| Intel               | 23       | 3.15%   |
| Fujitsu             | 14       | 1.92%   |
| Medion              | 13       | 1.78%   |
| Unknown             | 11       | 1.5%    |
| ECS                 | 9        | 1.23%   |
| Foxconn             | 8        | 1.09%   |
| Pegatron            | 7        | 0.96%   |
| Biostar             | 5        | 0.68%   |
| Packard Bell        | 4        | 0.55%   |
| Fujitsu Siemens     | 4        | 0.55%   |
| eMachines           | 4        | 0.55%   |
| Positivo            | 3        | 0.41%   |
| Apple               | 3        | 0.41%   |
| Shuttle             | 2        | 0.27%   |
| NCR                 | 2        | 0.27%   |
| EVGA                | 2        | 0.27%   |
| AAEON               | 2        | 0.27%   |
| WinFast             | 1        | 0.14%   |
| Semp Toshiba        | 1        | 0.14%   |
| Seco                | 1        | 0.14%   |
| QTQD                | 1        | 0.14%   |
| Qbex                | 1        | 0.14%   |
| PCWare              | 1        | 0.14%   |
| OEM                 | 1        | 0.14%   |
| Nvidia              | 1        | 0.14%   |
| NEC Computers       | 1        | 0.14%   |
| Minix               | 1        | 0.14%   |
| Itautec             | 1        | 0.14%   |
| Insyde              | 1        | 0.14%   |
| Huanan              | 1        | 0.14%   |
| Google              | 1        | 0.14%   |
| Gateway             | 1        | 0.14%   |
| Clientron           | 1        | 0.14%   |
| BCM                 | 1        | 0.14%   |
| ASL                 | 1        | 0.14%   |
| AOpen               | 1        | 0.14%   |
| AMI                 | 1        | 0.14%   |
| Alienware           | 1        | 0.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| ASUS All Series                        | 16       | 2.19%   |
| Unknown                                | 11       | 1.5%    |
| Dell OptiPlex 7010                     | 7        | 0.96%   |
| Dell OptiPlex 780                      | 5        | 0.68%   |
| MSI MS-7B79                            | 4        | 0.55%   |
| HP Compaq dc7900 Convertible Minitower | 4        | 0.55%   |
| Gigabyte B450M DS3H                    | 4        | 0.55%   |
| Dell OptiPlex 9020                     | 4        | 0.55%   |
| Dell OptiPlex 760                      | 4        | 0.55%   |
| Dell OptiPlex 755                      | 4        | 0.55%   |
| Dell OptiPlex 390                      | 4        | 0.55%   |
| ASUS TUF GAMING X570-PLUS              | 4        | 0.55%   |
| ASRock N68C-S UCC                      | 4        | 0.55%   |
| MSI MS-7A34                            | 3        | 0.41%   |
| MSI MS-7721                            | 3        | 0.41%   |
| MSI MS-7693                            | 3        | 0.41%   |
| Intel H61                              | 3        | 0.41%   |
| HP Z420 Workstation                    | 3        | 0.41%   |
| HP ProDesk 600 G1 SFF                  | 3        | 0.41%   |
| HP EliteDesk 800 G1 SFF                | 3        | 0.41%   |
| HP Compaq Elite 8300 SFF               | 3        | 0.41%   |
| HP Compaq 8100 Elite SFF PC            | 3        | 0.41%   |
| HP Compaq 6200 Pro MT PC               | 3        | 0.41%   |
| Gigabyte H61M-USB3V                    | 3        | 0.41%   |
| Fujitsu ESPRIMO E705                   | 3        | 0.41%   |
| Dell Precision WorkStation T7400       | 3        | 0.41%   |
| Dell OptiPlex 990                      | 3        | 0.41%   |
| Dell OptiPlex 3020                     | 3        | 0.41%   |
| ASUS TUF GAMING B550M-PLUS             | 3        | 0.41%   |
| ASUS P5K                               | 3        | 0.41%   |
| Apple MacPro5,1                        | 3        | 0.41%   |
| MSI MS-7C35                            | 2        | 0.27%   |
| MSI MS-7C02                            | 2        | 0.27%   |
| MSI MS-7B89                            | 2        | 0.27%   |
| MSI MS-7816                            | 2        | 0.27%   |
| MSI MS-7752                            | 2        | 0.27%   |
| MSI MS-7592                            | 2        | 0.27%   |
| Medion MS-7797                         | 2        | 0.27%   |
| HP Z620 Workstation                    | 2        | 0.27%   |
| HP t620 Quad Core TC                   | 2        | 0.27%   |
| HP Compaq Pro 6300 SFF                 | 2        | 0.27%   |
| HP Compaq dc7900 Small Form Factor     | 2        | 0.27%   |
| HP Compaq dc7800p Small Form Factor    | 2        | 0.27%   |
| HP Compaq 8200 Elite MT PC             | 2        | 0.27%   |
| HP Compaq 8000 Elite SFF PC            | 2        | 0.27%   |
| Gigabyte Z97X-Gaming 3                 | 2        | 0.27%   |
| Gigabyte Z370 HD3                      | 2        | 0.27%   |
| Gigabyte X570 AORUS MASTER             | 2        | 0.27%   |
| Gigabyte GB-BACE-3150                  | 2        | 0.27%   |
| Gigabyte GA-MA78GM-S2H                 | 2        | 0.27%   |
| Gigabyte GA-MA785GM-US2H               | 2        | 0.27%   |
| Gigabyte GA-880GM-UD2H                 | 2        | 0.27%   |
| Gigabyte F2A78M-HD2                    | 2        | 0.27%   |
| Gigabyte B450M S2H                     | 2        | 0.27%   |
| Gigabyte B150M-D3H-CF                  | 2        | 0.27%   |
| Foxconn Pro3500 Series                 | 2        | 0.27%   |
| eMachines EL1352                       | 2        | 0.27%   |
| ECS G31T-M7                            | 2        | 0.27%   |
| Dell Studio XPS 8100                   | 2        | 0.27%   |
| Dell Precision T1700                   | 2        | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| Dell OptiPlex            | 47       | 6.43%   |
| HP Compaq                | 34       | 4.65%   |
| ASUS PRIME               | 24       | 3.28%   |
| Lenovo ThinkCentre       | 19       | 2.6%    |
| ASUS All                 | 16       | 2.19%   |
| Acer Aspire              | 15       | 2.05%   |
| Fujitsu ESPRIMO          | 11       | 1.5%    |
| Dell Precision           | 11       | 1.5%    |
| Dell Inspiron            | 11       | 1.5%    |
| ASUS TUF                 | 11       | 1.5%    |
| Unknown                  | 11       | 1.5%    |
| HP ProDesk               | 7        | 0.96%   |
| Gigabyte X570            | 6        | 0.82%   |
| Gigabyte B450M           | 6        | 0.82%   |
| ASUS ROG                 | 6        | 0.82%   |
| HP EliteDesk             | 5        | 0.68%   |
| Acer Veriton             | 5        | 0.68%   |
| Packard Bell imedia      | 4        | 0.55%   |
| MSI MS-7B79              | 4        | 0.55%   |
| Lenovo ThinkStation      | 4        | 0.55%   |
| Dell Studio              | 4        | 0.55%   |
| ASUS P5KPL-AM            | 4        | 0.55%   |
| ASUS P5K                 | 4        | 0.55%   |
| ASUS M5A78L-M            | 4        | 0.55%   |
| ASRock N68C-S            | 4        | 0.55%   |
| ASRock B450M             | 4        | 0.55%   |
| MSI MS-7A34              | 3        | 0.41%   |
| MSI MS-7721              | 3        | 0.41%   |
| MSI MS-7693              | 3        | 0.41%   |
| Lenovo IdeaCentre        | 3        | 0.41%   |
| Intel H61                | 3        | 0.41%   |
| HP Z420                  | 3        | 0.41%   |
| HP ProLiant              | 3        | 0.41%   |
| Gigabyte H61M-USB3V      | 3        | 0.41%   |
| ASUS SABERTOOTH          | 3        | 0.41%   |
| ASUS P9X79               | 3        | 0.41%   |
| ASUS P8Z77-V             | 3        | 0.41%   |
| ASUS P8P67               | 3        | 0.41%   |
| ASRock B450              | 3        | 0.41%   |
| ASRock A320M-HDV         | 3        | 0.41%   |
| Apple MacPro5            | 3        | 0.41%   |
| MSI MS-7C35              | 2        | 0.27%   |
| MSI MS-7C02              | 2        | 0.27%   |
| MSI MS-7B89              | 2        | 0.27%   |
| MSI MS-7816              | 2        | 0.27%   |
| MSI MS-7752              | 2        | 0.27%   |
| MSI MS-7592              | 2        | 0.27%   |
| Medion MS-7797           | 2        | 0.27%   |
| Medion Akoya             | 2        | 0.27%   |
| Intel DH61WW             | 2        | 0.27%   |
| HP Z620                  | 2        | 0.27%   |
| HP t620                  | 2        | 0.27%   |
| HP Pavilion              | 2        | 0.27%   |
| Gigabyte Z97X-Gaming     | 2        | 0.27%   |
| Gigabyte Z370            | 2        | 0.27%   |
| Gigabyte H310M           | 2        | 0.27%   |
| Gigabyte GB-BACE-3150    | 2        | 0.27%   |
| Gigabyte GA-MA78GM-S2H   | 2        | 0.27%   |
| Gigabyte GA-MA785GM-US2H | 2        | 0.27%   |
| Gigabyte GA-880GM-UD2H   | 2        | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2012    | 74       | 10.12%  |
| 2013    | 73       | 9.99%   |
| 2011    | 70       | 9.58%   |
| 2010    | 68       | 9.3%    |
| 2009    | 63       | 8.62%   |
| 2018    | 57       | 7.8%    |
| 2014    | 46       | 6.29%   |
| 2019    | 45       | 6.16%   |
| 2008    | 43       | 5.88%   |
| 2015    | 37       | 5.06%   |
| 2007    | 37       | 5.06%   |
| 2017    | 36       | 4.92%   |
| 2020    | 28       | 3.83%   |
| 2016    | 23       | 3.15%   |
| 2006    | 15       | 2.05%   |
| 2005    | 8        | 1.09%   |
| 2021    | 6        | 0.82%   |
| Unknown | 2        | 0.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 731      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 710      | 97.13%  |
| Enabled  | 21       | 2.87%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 730      | 99.86%  |
| Yes  | 1        | 0.14%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 3.01-4.0    | 159      | 21.46%  |
| 8.01-16.0   | 156      | 21.05%  |
| 16.01-24.0  | 142      | 19.16%  |
| 4.01-8.0    | 115      | 15.52%  |
| 32.01-64.0  | 69       | 9.31%   |
| 1.01-2.0    | 49       | 6.61%   |
| 64.01-256.0 | 24       | 3.24%   |
| 24.01-32.0  | 13       | 1.75%   |
| 2.01-3.0    | 10       | 1.35%   |
| 0.51-1.0    | 4        | 0.54%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 369      | 45.78%  |
| 2.01-3.0   | 170      | 21.09%  |
| 4.01-8.0   | 89       | 11.04%  |
| 0.51-1.0   | 88       | 10.92%  |
| 3.01-4.0   | 62       | 7.69%   |
| 8.01-16.0  | 20       | 2.48%   |
| 24.01-32.0 | 4        | 0.5%    |
| 16.01-24.0 | 4        | 0.5%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 292      | 38.78%  |
| 2      | 230      | 30.54%  |
| 3      | 127      | 16.87%  |
| 4      | 52       | 6.91%   |
| 5      | 27       | 3.59%   |
| 6      | 10       | 1.33%   |
| 7      | 7        | 0.93%   |
| 0      | 3        | 0.4%    |
| 10     | 2        | 0.27%   |
| 9      | 2        | 0.27%   |
| 8      | 1        | 0.13%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 439      | 59.73%  |
| No        | 296      | 40.27%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 725      | 99.18%  |
| No        | 6        | 0.82%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 443      | 59.62%  |
| Yes       | 300      | 40.38%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 588      | 79.57%  |
| Yes       | 151      | 20.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Desktops | Percent |
|------------------------|----------|---------|
| USA                    | 146      | 19.92%  |
| Germany                | 105      | 14.32%  |
| France                 | 68       | 9.28%   |
| Brazil                 | 46       | 6.28%   |
| Canada                 | 45       | 6.14%   |
| Italy                  | 36       | 4.91%   |
| UK                     | 32       | 4.37%   |
| Russia                 | 30       | 4.09%   |
| Netherlands            | 21       | 2.86%   |
| Spain                  | 18       | 2.46%   |
| Australia              | 14       | 1.91%   |
| Japan                  | 13       | 1.77%   |
| Poland                 | 12       | 1.64%   |
| Ukraine                | 11       | 1.5%    |
| Argentina              | 11       | 1.5%    |
| Sweden                 | 10       | 1.36%   |
| Mexico                 | 9        | 1.23%   |
| Hungary                | 9        | 1.23%   |
| Switzerland            | 8        | 1.09%   |
| Romania                | 8        | 1.09%   |
| Belgium                | 8        | 1.09%   |
| Austria                | 7        | 0.95%   |
| Finland                | 6        | 0.82%   |
| Portugal               | 4        | 0.55%   |
| Indonesia              | 4        | 0.55%   |
| Colombia               | 4        | 0.55%   |
| Uruguay                | 3        | 0.41%   |
| Thailand               | 3        | 0.41%   |
| Taiwan                 | 3        | 0.41%   |
| Slovenia               | 3        | 0.41%   |
| Greece                 | 3        | 0.41%   |
| South Africa           | 2        | 0.27%   |
| Latvia                 | 2        | 0.27%   |
| Israel                 | 2        | 0.27%   |
| Czechia                | 2        | 0.27%   |
| Croatia                | 2        | 0.27%   |
| Bulgaria               | 2        | 0.27%   |
| Bosnia and Herzegovina | 2        | 0.27%   |
| Vietnam                | 1        | 0.14%   |
| Venezuela              | 1        | 0.14%   |
| Singapore              | 1        | 0.14%   |
| Serbia                 | 1        | 0.14%   |
| RГ©union             | 1        | 0.14%   |
| Puerto Rico            | 1        | 0.14%   |
| Philippines            | 1        | 0.14%   |
| Peru                   | 1        | 0.14%   |
| Norway                 | 1        | 0.14%   |
| Nicaragua              | 1        | 0.14%   |
| New Zealand            | 1        | 0.14%   |
| Malaysia               | 1        | 0.14%   |
| Lithuania              | 1        | 0.14%   |
| Ireland                | 1        | 0.14%   |
| Iceland                | 1        | 0.14%   |
| Greenland              | 1        | 0.14%   |
| Egypt                  | 1        | 0.14%   |
| Denmark                | 1        | 0.14%   |
| Belarus                | 1        | 0.14%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Berlin            | 11       | 1.42%   |
| Vancouver         | 8        | 1.03%   |
| Sydney            | 7        | 0.9%    |
| Madrid            | 7        | 0.9%    |
| Budapest          | 7        | 0.9%    |
| Sao Paulo         | 6        | 0.77%   |
| Paris             | 6        | 0.77%   |
| Moscow            | 6        | 0.77%   |
| Milan             | 6        | 0.77%   |
| Cologne           | 6        | 0.77%   |
| Rio de Janeiro    | 5        | 0.65%   |
| Montreal          | 5        | 0.65%   |
| Hamburg           | 5        | 0.65%   |
| Frankfurt am Main | 5        | 0.65%   |
| Eindhoven         | 5        | 0.65%   |
| Turin             | 4        | 0.52%   |
| Toronto           | 4        | 0.52%   |
| Tampere           | 4        | 0.52%   |
| Oldenburg         | 4        | 0.52%   |
| Kyiv              | 4        | 0.52%   |
| Houston           | 4        | 0.52%   |
| Hanover           | 4        | 0.52%   |
| Chicago           | 4        | 0.52%   |
| Cheboksary        | 4        | 0.52%   |
| Waterford         | 3        | 0.39%   |
| Warsaw            | 3        | 0.39%   |
| Suwanee           | 3        | 0.39%   |
| Springfield       | 3        | 0.39%   |
| Naples            | 3        | 0.39%   |
| Munich            | 3        | 0.39%   |
| Essen             | 3        | 0.39%   |
| Bucharest         | 3        | 0.39%   |
| Belo Horizonte    | 3        | 0.39%   |
| Zurich            | 2        | 0.26%   |
| Valencia          | 2        | 0.26%   |
| Toulon            | 2        | 0.26%   |
| The Hague         | 2        | 0.26%   |
| Surrey            | 2        | 0.26%   |
| Strasbourg        | 2        | 0.26%   |
| Steubenville      | 2        | 0.26%   |
| Seattle           | 2        | 0.26%   |
| Rostov-on-Don     | 2        | 0.26%   |
| Rome              | 2        | 0.26%   |
| Riverside         | 2        | 0.26%   |
| Riga              | 2        | 0.26%   |
| Reno              | 2        | 0.26%   |
| Quilmes           | 2        | 0.26%   |
| Puebla City       | 2        | 0.26%   |
| Potsdam           | 2        | 0.26%   |
| Phuket            | 2        | 0.26%   |
| Peine             | 2        | 0.26%   |
| Oxnard            | 2        | 0.26%   |
| Oryol             | 2        | 0.26%   |
| Orlando           | 2        | 0.26%   |
| Odessa            | 2        | 0.26%   |
| Nuremberg         | 2        | 0.26%   |
| New Taipei        | 2        | 0.26%   |
| Montevideo        | 2        | 0.26%   |
| Minneapolis       | 2        | 0.26%   |
| Mexico City       | 2        | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 283      | 469    | 22.21%  |
| WDC                       | 279      | 436    | 21.9%   |
| Samsung Electronics       | 165      | 249    | 12.95%  |
| Hitachi                   | 68       | 91     | 5.34%   |
| Toshiba                   | 58       | 73     | 4.55%   |
| Kingston                  | 57       | 69     | 4.47%   |
| SanDisk                   | 53       | 66     | 4.16%   |
| Crucial                   | 38       | 53     | 2.98%   |
| A-DATA Technology         | 24       | 28     | 1.88%   |
| MAXTOR                    | 20       | 25     | 1.57%   |
| Intel                     | 18       | 28     | 1.41%   |
| Unknown                   | 16       | 18     | 1.26%   |
| Patriot                   | 15       | 18     | 1.18%   |
| HGST                      | 12       | 15     | 0.94%   |
| China                     | 12       | 12     | 0.94%   |
| Intenso                   | 11       | 20     | 0.86%   |
| PNY                       | 9        | 15     | 0.71%   |
| Transcend                 | 8        | 9      | 0.63%   |
| Phison                    | 7        | 8      | 0.55%   |
| OCZ                       | 7        | 10     | 0.55%   |
| SK Hynix                  | 5        | 5      | 0.39%   |
| Micron Technology         | 5        | 6      | 0.39%   |
| Hewlett-Packard           | 5        | 7      | 0.39%   |
| Fujitsu                   | 5        | 6      | 0.39%   |
| SPCC                      | 4        | 8      | 0.31%   |
| Silicon Motion            | 4        | 4      | 0.31%   |
| Corsair                   | 4        | 4      | 0.31%   |
| Apacer                    | 4        | 4      | 0.31%   |
| Team                      | 3        | 4      | 0.24%   |
| Realtek Semiconductor     | 3        | 5      | 0.24%   |
| KIOXIA                    | 3        | 4      | 0.24%   |
| KingDian                  | 3        | 3      | 0.24%   |
| Integral                  | 3        | 3      | 0.24%   |
| ASMT                      | 3        | 3      | 0.24%   |
| XPG                       | 2        | 7      | 0.16%   |
| WD MediaMax               | 2        | 2      | 0.16%   |
| USB3.0                    | 2        | 3      | 0.16%   |
| TO Exter                  | 2        | 2      | 0.16%   |
| Smartbuy                  | 2        | 2      | 0.16%   |
| SABRENT                   | 2        | 2      | 0.16%   |
| OCZ-VERTEX3               | 2        | 2      | 0.16%   |
| Micron/Crucial Technology | 2        | 3      | 0.16%   |
| LITEONIT                  | 2        | 2      | 0.16%   |
| Lexar                     | 2        | 2      | 0.16%   |
| Kingmax                   | 2        | 2      | 0.16%   |
| GOODRAM                   | 2        | 3      | 0.16%   |
| XrayDisk                  | 1        | 1      | 0.08%   |
| WDC WDS                   | 1        | 1      | 0.08%   |
| Verbatim                  | 1        | 1      | 0.08%   |
| Vaseky                    | 1        | 1      | 0.08%   |
| Super Talent              | 1        | 1      | 0.08%   |
| SUNEAST                   | 1        | 1      | 0.08%   |
| SMI                       | 1        | 1      | 0.08%   |
| Qumox                     | 1        | 1      | 0.08%   |
| Q7                        | 1        | 1      | 0.08%   |
| PLEXTOR                   | 1        | 1      | 0.08%   |
| PCCOOLER                  | 1        | 1      | 0.08%   |
| OCZ-VERTEX2               | 1        | 1      | 0.08%   |
| Mushkin                   | 1        | 1      | 0.08%   |
| Mercury                   | 1        | 1      | 0.08%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 23       | 1.54%   |
| Seagate ST1000DM010-2EP102 1TB   | 16       | 1.07%   |
| Kingston SA400S37240G 240GB SSD  | 15       | 1.01%   |
| Seagate ST2000DM008-2FR102 2TB   | 12       | 0.8%    |
| Seagate ST2000DM001-1CH164 2TB   | 11       | 0.74%   |
| Samsung SSD 860 EVO 500GB        | 11       | 0.74%   |
| Kingston SA400S37480G 480GB SSD  | 11       | 0.74%   |
| Seagate ST1000DM003-1CH162 1TB   | 10       | 0.67%   |
| Samsung SSD 850 EVO 250GB        | 10       | 0.67%   |
| Seagate Expansion+ 2TB           | 9        | 0.6%    |
| Patriot Burst 120GB SSD          | 9        | 0.6%    |
| Unknown SD/MMC/MS PRO 16GB       | 8        | 0.54%   |
| Toshiba DT01ACA100 1TB           | 8        | 0.54%   |
| Seagate ST380815AS 80GB          | 8        | 0.54%   |
| Seagate ST3500418AS 500GB        | 8        | 0.54%   |
| Seagate ST31000528AS 1TB         | 8        | 0.54%   |
| Seagate ST1000DM003-1ER162 1TB   | 8        | 0.54%   |
| Samsung SSD 860 EVO 1TB          | 8        | 0.54%   |
| WDC WD10EZEX-00BN5A0 1TB         | 7        | 0.47%   |
| Seagate ST4000DM004-2CV104 4TB   | 7        | 0.47%   |
| Seagate ST3250310AS 250GB        | 7        | 0.47%   |
| Seagate ST31000524AS 1TB         | 7        | 0.47%   |
| Seagate ST2000DM001-1ER164 2TB   | 7        | 0.47%   |
| Kingston SV300S37A120G 120GB SSD | 7        | 0.47%   |
| Crucial CT1000MX500SSD1 1TB      | 7        | 0.47%   |
| WDC WD10EZEX-08WN4A0 1TB         | 6        | 0.4%    |
| Seagate ST2000DM006-2DM164 2TB   | 6        | 0.4%    |
| Samsung SSD 860 EVO 250GB        | 6        | 0.4%    |
| Samsung SSD 840 Series 120GB     | 6        | 0.4%    |
| Samsung NVMe SSD Drive 1TB       | 6        | 0.4%    |
| Samsung HD502HJ 500GB            | 6        | 0.4%    |
| Samsung HD103SJ 1TB              | 6        | 0.4%    |
| Crucial CT500MX500SSD1 500GB     | 6        | 0.4%    |
| WDC WDS120G2G0A-00JH30 120GB SSD | 5        | 0.34%   |
| WDC WD20EARX-00PASB0 2TB         | 5        | 0.34%   |
| WDC WD10EZEX-00WN4A0 1TB         | 5        | 0.34%   |
| WDC WD1002FAEX-00Z3A0 1TB        | 5        | 0.34%   |
| Toshiba HDWD110 1TB              | 5        | 0.34%   |
| Seagate ST500LT012-1DG142 500GB  | 5        | 0.34%   |
| Seagate ST3250820AS 250GB        | 5        | 0.34%   |
| Seagate ST3160815AS 160GB        | 5        | 0.34%   |
| Seagate ST2000DM001-9YN164 2TB   | 5        | 0.34%   |
| Seagate Expansion Desk 4TB       | 5        | 0.34%   |
| Seagate Backup+ Hub BK 4TB       | 5        | 0.34%   |
| SanDisk SSD PLUS 240GB           | 5        | 0.34%   |
| Samsung SSD 850 EVO 500GB        | 5        | 0.34%   |
| Samsung SSD 840 Series 250GB     | 5        | 0.34%   |
| Samsung SSD 840 EVO 250GB        | 5        | 0.34%   |
| Samsung NVMe SSD Drive 500GB     | 5        | 0.34%   |
| Samsung HD160JJ 160GB            | 5        | 0.34%   |
| Kingston SA400S37120G 120GB SSD  | 5        | 0.34%   |
| Hitachi HDS721010CLA332 1TB      | 5        | 0.34%   |
| Hitachi HDP725025GLA380 250GB    | 5        | 0.34%   |
| A-DATA SU650 240GB SSD           | 5        | 0.34%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 4        | 0.27%   |
| WDC WD5000AADS-00S9B0 500GB      | 4        | 0.27%   |
| WDC WD40EZRZ-00GXCB0 4TB         | 4        | 0.27%   |
| WDC WD20EFRX-68EUZN0 2TB         | 4        | 0.27%   |
| WDC WD10EZEX-00RKKA0 1TB         | 4        | 0.27%   |
| WDC WD10EARS-00Y5B1 1TB          | 4        | 0.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 278      | 462    | 35.92%  |
| WDC                 | 255      | 392    | 32.95%  |
| Hitachi             | 68       | 91     | 8.79%   |
| Samsung Electronics | 64       | 84     | 8.27%   |
| Toshiba             | 48       | 59     | 6.2%    |
| MAXTOR              | 19       | 24     | 2.45%   |
| HGST                | 12       | 15     | 1.55%   |
| Unknown             | 9        | 10     | 1.16%   |
| Fujitsu             | 5        | 6      | 0.65%   |
| Intenso             | 3        | 6      | 0.39%   |
| WD MediaMax         | 2        | 2      | 0.26%   |
| Hewlett-Packard     | 2        | 2      | 0.26%   |
| ASMT                | 2        | 2      | 0.26%   |
| USB3.0              | 1        | 2      | 0.13%   |
| SABRENT             | 1        | 1      | 0.13%   |
| LaCie               | 1        | 3      | 0.13%   |
| ICY BOX             | 1        | 1      | 0.13%   |
| HPE                 | 1        | 4      | 0.13%   |
| ExcelStor           | 1        | 1      | 0.13%   |
| Apple               | 1        | 1      | 0.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 89       | 121    | 21.29%  |
| Kingston            | 53       | 64     | 12.68%  |
| SanDisk             | 48       | 59     | 11.48%  |
| Crucial             | 33       | 48     | 7.89%   |
| WDC                 | 28       | 37     | 6.7%    |
| A-DATA Technology   | 20       | 23     | 4.78%   |
| Patriot             | 15       | 18     | 3.59%   |
| Intel               | 15       | 22     | 3.59%   |
| China               | 12       | 12     | 2.87%   |
| PNY                 | 9        | 15     | 2.15%   |
| Transcend           | 7        | 7      | 1.67%   |
| OCZ                 | 6        | 8      | 1.44%   |
| Intenso             | 6        | 8      | 1.44%   |
| Toshiba             | 5        | 9      | 1.2%    |
| Micron Technology   | 5        | 6      | 1.2%    |
| SPCC                | 4        | 8      | 0.96%   |
| SK Hynix            | 4        | 4      | 0.96%   |
| Corsair             | 4        | 4      | 0.96%   |
| Apacer              | 4        | 4      | 0.96%   |
| Team                | 3        | 4      | 0.72%   |
| KingDian            | 3        | 3      | 0.72%   |
| Integral            | 3        | 3      | 0.72%   |
| Hewlett-Packard     | 3        | 5      | 0.72%   |
| TO Exter            | 2        | 2      | 0.48%   |
| Smartbuy            | 2        | 2      | 0.48%   |
| OCZ-VERTEX3         | 2        | 2      | 0.48%   |
| LITEONIT            | 2        | 2      | 0.48%   |
| Lexar               | 2        | 2      | 0.48%   |
| Kingmax             | 2        | 2      | 0.48%   |
| GOODRAM             | 2        | 3      | 0.48%   |
| WDC WDS             | 1        | 1      | 0.24%   |
| Verbatim            | 1        | 1      | 0.24%   |
| USB3.0              | 1        | 1      | 0.24%   |
| Super Talent        | 1        | 1      | 0.24%   |
| SUNEAST             | 1        | 1      | 0.24%   |
| Seagate             | 1        | 1      | 0.24%   |
| SABRENT             | 1        | 1      | 0.24%   |
| Qumox               | 1        | 1      | 0.24%   |
| PLEXTOR             | 1        | 1      | 0.24%   |
| PHISON              | 1        | 2      | 0.24%   |
| OCZ-VERTEX2         | 1        | 1      | 0.24%   |
| Mushkin             | 1        | 1      | 0.24%   |
| Mercury             | 1        | 1      | 0.24%   |
| MAXTOR              | 1        | 1      | 0.24%   |
| LITEON              | 1        | 1      | 0.24%   |
| KIOXIA-EXCERIA      | 1        | 2      | 0.24%   |
| JMicron             | 1        | 1      | 0.24%   |
| HS-SSD-E100N        | 1        | 1      | 0.24%   |
| FREEBSD             | 1        | 2      | 0.24%   |
| FORESEE             | 1        | 1      | 0.24%   |
| DREVO               | 1        | 1      | 0.24%   |
| Dogfish             | 1        | 1      | 0.24%   |
| ASMT                | 1        | 1      | 0.24%   |
| AMD                 | 1        | 1      | 0.24%   |
| Unknown             | 1        | 1      | 0.24%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 568      | 1168   | 55.04%  |
| SSD     | 358      | 535    | 34.69%  |
| NVMe    | 81       | 123    | 7.85%   |
| Unknown | 18       | 23     | 1.74%   |
| MMC     | 7        | 8      | 0.68%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 704      | 1645   | 82.82%  |
| NVMe | 81       | 123    | 9.53%   |
| SAS  | 58       | 81     | 6.82%   |
| MMC  | 7        | 8      | 0.82%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 558      | 969    | 55.14%  |
| 0.51-1.0   | 254      | 391    | 25.1%   |
| 1.01-2.0   | 106      | 179    | 10.47%  |
| 3.01-4.0   | 39       | 72     | 3.85%   |
| 2.01-3.0   | 29       | 51     | 2.87%   |
| 4.01-10.0  | 25       | 40     | 2.47%   |
| 10.01-20.0 | 1        | 1      | 0.1%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 215      | 28.36%  |
| 251-500        | 133      | 17.55%  |
| 501-1000       | 114      | 15.04%  |
| 1001-2000      | 84       | 11.08%  |
| More than 3000 | 70       | 9.23%   |
| 51-100         | 51       | 6.73%   |
| 2001-3000      | 31       | 4.09%   |
| 21-50          | 28       | 3.69%   |
| 1-20           | 26       | 3.43%   |
| Unknown        | 6        | 0.79%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 247      | 31.42%  |
| 21-50          | 128      | 16.28%  |
| 101-250        | 118      | 15.01%  |
| 51-100         | 89       | 11.32%  |
| 501-1000       | 59       | 7.51%   |
| 251-500        | 56       | 7.12%   |
| 1001-2000      | 40       | 5.09%   |
| More than 3000 | 27       | 3.44%   |
| 2001-3000      | 16       | 2.04%   |
| Unknown        | 6        | 0.76%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 4        | 4      | 5.33%   |
| WDC WD4000FYYZ-01UL1B1 4TB            | 2        | 3      | 2.67%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 2        | 2      | 2.67%   |
| Kingston SA400S37240G 240GB SSD       | 2        | 2      | 2.67%   |
| WDC WD6400AAKS-22A7B2 640GB           | 1        | 1      | 1.33%   |
| WDC WD6400AAKS-22A7B0 640GB           | 1        | 1      | 1.33%   |
| WDC WD5000LPVX-08V0TT5 500GB          | 1        | 1      | 1.33%   |
| WDC WD5000LPCX-00VHAT0 500GB          | 1        | 1      | 1.33%   |
| WDC WD5000BEVT-22ZAT0 500GB           | 1        | 1      | 1.33%   |
| WDC WD5000AAKX-08U6AA0 500GB          | 1        | 1      | 1.33%   |
| WDC WD5000AAKS-22V1A0 500GB           | 1        | 1      | 1.33%   |
| WDC WD400EB-00CPF0 40GB               | 1        | 1      | 1.33%   |
| WDC WD3200BEVT-75ZCT1 320GB           | 1        | 1      | 1.33%   |
| WDC WD3200AVJS-63TBA0 320GB           | 1        | 1      | 1.33%   |
| WDC WD3200AAKS-00L9A0 320GB           | 1        | 1      | 1.33%   |
| WDC WD3200AAJS-08L7A0 320GB           | 1        | 1      | 1.33%   |
| WDC WD20EZRX-00D8PB0 2TB              | 1        | 2      | 1.33%   |
| WDC WD20EFRX-68EUZN0 2TB              | 1        | 1      | 1.33%   |
| WDC WD1600AAJS-00L7A0 160GB           | 1        | 1      | 1.33%   |
| WDC WD10EZRX-00A8LB0 1TB              | 1        | 1      | 1.33%   |
| WDC WD10EZEX-00RKKA0 1TB              | 1        | 1      | 1.33%   |
| WDC WD10EFRX-68PJCN0 1TB              | 1        | 1      | 1.33%   |
| WDC WD10EFRX-68JCSN0 1TB              | 1        | 1      | 1.33%   |
| WDC WD10EAVS-22D7B0 1TB               | 1        | 1      | 1.33%   |
| WDC WD10EADX-22TDHB0 1TB              | 1        | 1      | 1.33%   |
| WDC WD10EADS-22M2B0 1TB               | 1        | 1      | 1.33%   |
| Toshiba MQ01ABF050 500GB              | 1        | 1      | 1.33%   |
| Toshiba MK3263GSX 320GB               | 1        | 1      | 1.33%   |
| Toshiba HDWE140 4TB                   | 1        | 1      | 1.33%   |
| Toshiba HDWD110 1TB                   | 1        | 1      | 1.33%   |
| Toshiba DT01ACA050 500GB              | 1        | 1      | 1.33%   |
| SK Hynix SH920 2.5 7MM 256GB SSD      | 1        | 1      | 1.33%   |
| SK Hynix HFS128G39MNC-2300A 128GB SSD | 1        | 1      | 1.33%   |
| Seagate ST980310AS 80GB               | 1        | 1      | 1.33%   |
| Seagate ST500LM000-SSHD-8GB           | 1        | 1      | 1.33%   |
| Seagate ST500DM005 HD502HJ 500GB      | 1        | 1      | 1.33%   |
| Seagate ST5000DM000-1FK178 5TB        | 1        | 1      | 1.33%   |
| Seagate ST380811AS 80GB               | 1        | 1      | 1.33%   |
| Seagate ST3400620NS 400GB             | 1        | 1      | 1.33%   |
| Seagate ST3320418AS 320GB             | 1        | 1      | 1.33%   |
| Seagate ST3250318AS 250GB             | 1        | 1      | 1.33%   |
| Seagate ST31000528AS 1TB              | 1        | 1      | 1.33%   |
| Seagate ST3000DM001-9YN166 3TB        | 1        | 1      | 1.33%   |
| Seagate ST250LT007-9ZV14C 250GB       | 1        | 1      | 1.33%   |
| Seagate ST2000DX001-1NS164 2TB        | 1        | 1      | 1.33%   |
| Seagate ST1000VM002-9ZL162 1TB        | 1        | 1      | 1.33%   |
| Seagate ST1000DM003-1SB102 1TB        | 1        | 2      | 1.33%   |
| Seagate ST1000DL002-9TT153 1TB        | 1        | 1      | 1.33%   |
| Samsung Electronics SP2504C 250GB     | 1        | 1      | 1.33%   |
| Samsung Electronics HM321HI 320GB     | 1        | 1      | 1.33%   |
| Samsung Electronics HD753LJ 752GB     | 1        | 1      | 1.33%   |
| Samsung Electronics HD501LJ 500GB     | 1        | 2      | 1.33%   |
| Samsung Electronics HD160JJ 160GB     | 1        | 1      | 1.33%   |
| Samsung Electronics HD103SJ 1TB       | 1        | 1      | 1.33%   |
| Samsung Electronics HD103SI 1TB       | 1        | 1      | 1.33%   |
| Samsung Electronics HD081GJ 80GB      | 1        | 1      | 1.33%   |
| MAXTOR STM3160215AS 160GB             | 1        | 1      | 1.33%   |
| Kingston SA400S37480G 480GB SSD       | 1        | 1      | 1.33%   |
| Intel SSDSC2BW120A4 120GB             | 1        | 1      | 1.33%   |
| ICY BOX IB-250StU3+BH15 2TB           | 1        | 1      | 1.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 24       | 28     | 33.33%  |
| Seagate             | 19       | 20     | 26.39%  |
| Samsung Electronics | 7        | 9      | 9.72%   |
| Toshiba             | 5        | 5      | 6.94%   |
| Hitachi             | 5        | 5      | 6.94%   |
| Kingston            | 3        | 3      | 4.17%   |
| SK Hynix            | 2        | 2      | 2.78%   |
| A-DATA Technology   | 2        | 2      | 2.78%   |
| MAXTOR              | 1        | 1      | 1.39%   |
| Intel               | 1        | 1      | 1.39%   |
| ICY BOX             | 1        | 1      | 1.39%   |
| HGST                | 1        | 1      | 1.39%   |
| FORESEE             | 1        | 1      | 1.39%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 24       | 28     | 38.1%   |
| Seagate             | 19       | 20     | 30.16%  |
| Samsung Electronics | 7        | 9      | 11.11%  |
| Toshiba             | 5        | 5      | 7.94%   |
| Hitachi             | 5        | 5      | 7.94%   |
| MAXTOR              | 1        | 1      | 1.59%   |
| ICY BOX             | 1        | 1      | 1.59%   |
| HGST                | 1        | 1      | 1.59%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 58       | 70     | 86.57%  |
| SSD  | 9        | 9      | 13.43%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| WDC WD10EAVS-00D7B1 1TB          | 1        | 1      | 25%     |
| Toshiba DT01ACA200 2TB           | 1        | 1      | 25%     |
| Seagate ST500DM002-1BC142 500GB  | 1        | 1      | 25%     |
| A-DATA Technology SP800 32GB SSD | 1        | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor            | Desktops | Drives | Percent |
|-------------------|----------|--------|---------|
| WDC               | 1        | 1      | 25%     |
| Toshiba           | 1        | 1      | 25%     |
| Seagate           | 1        | 1      | 25%     |
| A-DATA Technology | 1        | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 504      | 1316   | 63.08%  |
| Works    | 226      | 458    | 28.29%  |
| Malfunc  | 65       | 79     | 8.14%   |
| Failed   | 4        | 4      | 0.5%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 487      | 53.05%  |
| AMD                           | 196      | 21.35%  |
| Nvidia                        | 41       | 4.47%   |
| ASMedia Technology            | 31       | 3.38%   |
| Samsung Electronics           | 29       | 3.16%   |
| JMicron Technology            | 28       | 3.05%   |
| Marvell Technology Group      | 25       | 2.72%   |
| VIA Technologies              | 13       | 1.42%   |
| Sandisk                       | 8        | 0.87%   |
| Phison Electronics            | 7        | 0.76%   |
| ADATA Technology              | 7        | 0.76%   |
| Micron/Crucial Technology     | 6        | 0.65%   |
| Silicon Motion                | 5        | 0.54%   |
| LSI Logic / Symbios Logic     | 5        | 0.54%   |
| Toshiba America Info Systems  | 4        | 0.44%   |
| Realtek Semiconductor         | 4        | 0.44%   |
| Kingston Technology Company   | 4        | 0.44%   |
| Broadcom / LSI                | 3        | 0.33%   |
| Silicon Image                 | 2        | 0.22%   |
| Promise Technology            | 2        | 0.22%   |
| KIOXIA                        | 2        | 0.22%   |
| Integrated Technology Express | 2        | 0.22%   |
| Adaptec                       | 2        | 0.22%   |
| Seagate Technology            | 1        | 0.11%   |
| OCZ Technology Group          | 1        | 0.11%   |
| Micron Technology             | 1        | 0.11%   |
| Lite-On Technology            | 1        | 0.11%   |
| Hewlett-Packard               | 1        | 0.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 109      | 8.61%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 54       | 4.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 51       | 4.03%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 50       | 3.95%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 48       | 3.79%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 37       | 2.92%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 36       | 2.84%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 35       | 2.76%   |
| AMD 400 Series Chipset SATA Controller                                                  | 34       | 2.69%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 32       | 2.53%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 29       | 2.29%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 29       | 2.29%   |
| Intel SATA Controller [RAID mode]                                                       | 28       | 2.21%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 21       | 1.66%   |
| Nvidia MCP61 SATA Controller                                                            | 21       | 1.66%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 21       | 1.66%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 21       | 1.66%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 20       | 1.58%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 20       | 1.58%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 20       | 1.58%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 19       | 1.5%    |
| Nvidia MCP61 IDE                                                                        | 18       | 1.42%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 17       | 1.34%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 15       | 1.18%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 14       | 1.11%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 13       | 1.03%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 12       | 0.95%   |
| AMD 300 Series Chipset SATA Controller                                                  | 12       | 0.95%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 11       | 0.87%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 10       | 0.79%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 10       | 0.79%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 10       | 0.79%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 9        | 0.71%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 9        | 0.71%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 8        | 0.63%   |
| AMD FCH SATA Controller D                                                               | 8        | 0.63%   |
| AMD FCH IDE Controller                                                                  | 8        | 0.63%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 7        | 0.55%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 7        | 0.55%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 7        | 0.55%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 7        | 0.55%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 7        | 0.55%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                              | 7        | 0.55%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                              | 7        | 0.55%   |
| AMD 500 Series Chipset SATA Controller                                                  | 7        | 0.55%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 7        | 0.55%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 6        | 0.47%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                            | 6        | 0.47%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 6        | 0.47%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 6        | 0.47%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 6        | 0.47%   |
| AMD SB600 IDE                                                                           | 6        | 0.47%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 5        | 0.39%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 5        | 0.39%   |
| Phison E12 NVMe Controller                                                              | 5        | 0.39%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 5        | 0.39%   |
| JMicron JMB368 IDE controller                                                           | 5        | 0.39%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 5        | 0.39%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 5        | 0.39%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 5        | 0.39%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 519      | 54.52%  |
| IDE  | 292      | 30.67%  |
| NVMe | 78       | 8.19%   |
| RAID | 49       | 5.15%   |
| SAS  | 8        | 0.84%   |
| SCSI | 6        | 0.63%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 495      | 67.72%  |
| AMD    | 235      | 32.15%  |
| ARM    | 1        | 0.14%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 14       | 1.9%    |
| Intel Core i5-2400 CPU @ 3.10GHz            | 13       | 1.77%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 12       | 1.63%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 11       | 1.49%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 10       | 1.36%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 10       | 1.36%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 9        | 1.22%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 8        | 1.09%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 8        | 1.09%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 8        | 1.09%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 8        | 1.09%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 8        | 1.09%   |
| AMD FX-8350 Eight-Core Processor            | 8        | 1.09%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 7        | 0.95%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 7        | 0.95%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 7        | 0.95%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 7        | 0.95%   |
| AMD Ryzen 5 3600 6-Core Processor           | 7        | 0.95%   |
| AMD Phenom II X4 955 Processor              | 7        | 0.95%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 6        | 0.82%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 6        | 0.82%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 6        | 0.82%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 6        | 0.82%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 6        | 0.82%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz          | 5        | 0.68%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 5        | 0.68%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 5        | 0.68%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 5        | 0.68%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 5        | 0.68%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 5        | 0.68%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 4        | 0.54%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 4        | 0.54%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 4        | 0.54%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 4        | 0.54%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 4        | 0.54%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 4        | 0.54%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 4        | 0.54%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 4        | 0.54%   |
| Intel Core i5-4690K CPU @ 3.50GHz           | 4        | 0.54%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 4        | 0.54%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 4        | 0.54%   |
| Intel Core i5-4440 CPU @ 3.10GHz            | 4        | 0.54%   |
| Intel Core i5 CPU 760 @ 2.80GHz             | 4        | 0.54%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 4        | 0.54%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 4        | 0.54%   |
| Intel Core 2 CPU 6600 @ 2.40GHz             | 4        | 0.54%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 4        | 0.54%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 4        | 0.54%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 4        | 0.54%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 4        | 0.54%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 4        | 0.54%   |
| AMD FX-4300 Quad-Core Processor             | 4        | 0.54%   |
| Intel Xeon CPU E5462 @ 2.80GHz              | 3        | 0.41%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 3        | 0.41%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 3        | 0.41%   |
| Intel Core i7-4930K CPU @ 3.40GHz           | 3        | 0.41%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 3        | 0.41%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 3        | 0.41%   |
| Intel Core i5-3550 CPU @ 3.30GHz            | 3        | 0.41%   |
| Intel Core i3 CPU 530 @ 2.93GHz             | 3        | 0.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 123      | 16.73%  |
| Intel Core i7           | 91       | 12.38%  |
| Intel Core i3           | 53       | 7.21%   |
| Intel Core 2 Duo        | 44       | 5.99%   |
| Intel Xeon              | 39       | 5.31%   |
| AMD Ryzen 5             | 37       | 5.03%   |
| Intel Celeron           | 28       | 3.81%   |
| Intel Pentium           | 27       | 3.67%   |
| AMD FX                  | 25       | 3.4%    |
| Intel Core 2 Quad       | 24       | 3.27%   |
| AMD Ryzen 7             | 24       | 3.27%   |
| Intel Pentium Dual-Core | 23       | 3.13%   |
| AMD Phenom II X4        | 17       | 2.31%   |
| AMD Athlon II X2        | 17       | 2.31%   |
| AMD Athlon 64 X2        | 13       | 1.77%   |
| AMD Ryzen 3             | 12       | 1.63%   |
| AMD Ryzen 9             | 11       | 1.5%    |
| Intel Core 2            | 10       | 1.36%   |
| AMD A8                  | 9        | 1.22%   |
| AMD A10                 | 9        | 1.22%   |
| Intel Atom              | 8        | 1.09%   |
| Intel Pentium Dual      | 7        | 0.95%   |
| Intel Pentium 4         | 6        | 0.82%   |
| Intel Core i9           | 6        | 0.82%   |
| AMD Athlon II X4        | 6        | 0.82%   |
| AMD Phenom II X6        | 5        | 0.68%   |
| AMD Phenom              | 5        | 0.68%   |
| AMD E                   | 5        | 0.68%   |
| AMD A4                  | 5        | 0.68%   |
| Other                   | 4        | 0.54%   |
| Intel Pentium D         | 4        | 0.54%   |
| AMD Athlon II X3        | 4        | 0.54%   |
| AMD Athlon 64           | 4        | 0.54%   |
| AMD Sempron             | 3        | 0.41%   |
| AMD Ryzen Threadripper  | 3        | 0.41%   |
| AMD E1                  | 3        | 0.41%   |
| AMD Athlon Dual Core    | 3        | 0.41%   |
| AMD Athlon              | 3        | 0.41%   |
| AMD A6                  | 3        | 0.41%   |
| Intel Pentium Gold      | 2        | 0.27%   |
| AMD Phenom II X2        | 2        | 0.27%   |
| AMD GX                  | 2        | 0.27%   |
| AMD Turion 64 X2 Mobile | 1        | 0.14%   |
| AMD Ryzen Embedded      | 1        | 0.14%   |
| AMD Ryzen 5 PRO         | 1        | 0.14%   |
| AMD Athlon X4           | 1        | 0.14%   |
| AMD Athlon X2           | 1        | 0.14%   |
| AMD Athlon II           | 1        | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 314      | 42.78%  |
| 2      | 258      | 35.15%  |
| 6      | 64       | 8.72%   |
| 8      | 44       | 5.99%   |
| 1      | 23       | 3.13%   |
| 12     | 13       | 1.77%   |
| 3      | 8        | 1.09%   |
| 16     | 7        | 0.95%   |
| 10     | 2        | 0.27%   |
| 24     | 1        | 0.14%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 717      | 98.08%  |
| 2      | 14       | 1.92%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 418      | 57.03%  |
| 2      | 315      | 42.97%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 730      | 99.86%  |
| Unknown        | 1        | 0.14%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 91       | 12.2%   |
| 0x206a7    | 64       | 8.58%   |
| 0x306c3    | 62       | 8.31%   |
| 0x1067a    | 61       | 8.18%   |
| 0x306a9    | 45       | 6.03%   |
| 0x010000c8 | 29       | 3.89%   |
| 0x506e3    | 26       | 3.49%   |
| 0x06000852 | 20       | 2.68%   |
| 0x08701021 | 19       | 2.55%   |
| 0x0800820d | 18       | 2.41%   |
| 0x906e9    | 15       | 2.01%   |
| 0x6fd      | 14       | 1.88%   |
| 0x6fb      | 14       | 1.88%   |
| 0x906ea    | 13       | 1.74%   |
| 0x106e5    | 13       | 1.74%   |
| 0x10676    | 13       | 1.74%   |
| 0x08108109 | 12       | 1.61%   |
| 0x206d7    | 11       | 1.47%   |
| 0x06001119 | 9        | 1.21%   |
| 0x6f6      | 8        | 1.07%   |
| 0x20655    | 8        | 1.07%   |
| 0x010000db | 8        | 1.07%   |
| 0x306f2    | 7        | 0.94%   |
| 0x08701013 | 7        | 0.94%   |
| 0x010000c7 | 7        | 0.94%   |
| 0x906ed    | 6        | 0.8%    |
| 0x106a5    | 6        | 0.8%    |
| 0x0700010f | 6        | 0.8%    |
| 0x406c3    | 5        | 0.67%   |
| 0x206c2    | 5        | 0.67%   |
| 0x0a201009 | 5        | 0.67%   |
| 0x08001137 | 5        | 0.67%   |
| 0x0600063e | 5        | 0.67%   |
| 0x03000027 | 5        | 0.67%   |
| 0x010000dc | 5        | 0.67%   |
| 0xa0653    | 4        | 0.54%   |
| 0x406c4    | 4        | 0.54%   |
| 0x306e4    | 4        | 0.54%   |
| 0x20652    | 4        | 0.54%   |
| 0x08001138 | 4        | 0.54%   |
| 0x06003106 | 4        | 0.54%   |
| 0xf65      | 3        | 0.4%    |
| 0xf43      | 3        | 0.4%    |
| 0xa0655    | 3        | 0.4%    |
| 0x30678    | 3        | 0.4%    |
| 0x10677    | 3        | 0.4%    |
| 0x05000119 | 3        | 0.4%    |
| 0x05000029 | 3        | 0.4%    |
| 0x01000095 | 3        | 0.4%    |
| 0xf64      | 2        | 0.27%   |
| 0xf41      | 2        | 0.27%   |
| 0xa0671    | 2        | 0.27%   |
| 0x906eb    | 2        | 0.27%   |
| 0x6f2      | 2        | 0.27%   |
| 0x506ca    | 2        | 0.27%   |
| 0x40651    | 2        | 0.27%   |
| 0x106ca    | 2        | 0.27%   |
| 0x0a50000c | 2        | 0.27%   |
| 0x08600106 | 2        | 0.27%   |
| 0x08101016 | 2        | 0.27%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 82       | 11.19%  |
| SandyBridge   | 80       | 10.91%  |
| Penryn        | 78       | 10.64%  |
| K10           | 58       | 7.91%   |
| IvyBridge     | 54       | 7.37%   |
| KabyLake      | 43       | 5.87%   |
| Core          | 43       | 5.87%   |
| Zen 2         | 32       | 4.37%   |
| Zen+          | 30       | 4.09%   |
| Skylake       | 30       | 4.09%   |
| Piledriver    | 30       | 4.09%   |
| K8 Hammer     | 25       | 3.41%   |
| Zen           | 20       | 2.73%   |
| Nehalem       | 20       | 2.73%   |
| Westmere      | 18       | 2.46%   |
| Silvermont    | 14       | 1.91%   |
| NetBurst      | 11       | 1.5%    |
| Zen 3         | 8        | 1.09%   |
| CometLake     | 8        | 1.09%   |
| Jaguar        | 6        | 0.82%   |
| Bobcat        | 6        | 0.82%   |
| K10 Llano     | 5        | 0.68%   |
| Goldmont      | 5        | 0.68%   |
| Excavator     | 5        | 0.68%   |
| Bulldozer     | 5        | 0.68%   |
| Steamroller   | 4        | 0.55%   |
| Bonnell       | 4        | 0.55%   |
| Unknown       | 4        | 0.55%   |
| Puma          | 2        | 0.27%   |
| Broadwell     | 2        | 0.27%   |
| Goldmont plus | 1        | 0.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 309      | 40.13%  |
| Intel                      | 247      | 32.08%  |
| AMD                        | 210      | 27.27%  |
| VIA Technologies           | 2        | 0.26%   |
| Matrox Electronics Systems | 2        | 0.26%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 36       | 4.49%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 36       | 4.49%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 35       | 4.37%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 27       | 3.37%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 27       | 3.37%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 25       | 3.12%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 19       | 2.37%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 16       | 2%      |
| Nvidia GT218 [GeForce 210]                                                               | 15       | 1.87%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 15       | 1.87%   |
| Intel HD Graphics 530                                                                    | 13       | 1.62%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 12       | 1.5%    |
| Nvidia GP108 [GeForce GT 1030]                                                           | 10       | 1.25%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 10       | 1.25%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 10       | 1.25%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 9        | 1.12%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9        | 1.12%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 7        | 0.87%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 7        | 0.87%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 7        | 0.87%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 7        | 0.87%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 7        | 0.87%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 7        | 0.87%   |
| AMD RS880 [Radeon HD 4250]                                                               | 7        | 0.87%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 7        | 0.87%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 6        | 0.75%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 6        | 0.75%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 5        | 0.62%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5        | 0.62%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 5        | 0.62%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 5        | 0.62%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 5        | 0.62%   |
| AMD RS880 [Radeon HD 4200]                                                               | 5        | 0.62%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 5        | 0.62%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 4        | 0.5%    |
| Nvidia GT216 [GeForce GT 220]                                                            | 4        | 0.5%    |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 4        | 0.5%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 4        | 0.5%    |
| Nvidia GM206 [GeForce GTX 960]                                                           | 4        | 0.5%    |
| Nvidia GK104 [GeForce GTX 760]                                                           | 4        | 0.5%    |
| Nvidia GF119 [GeForce GT 520]                                                            | 4        | 0.5%    |
| Nvidia GF106 [GeForce GTS 450]                                                           | 4        | 0.5%    |
| Nvidia G92 [GeForce GTS 250]                                                             | 4        | 0.5%    |
| Nvidia G92 [GeForce 9800 GT]                                                             | 4        | 0.5%    |
| Nvidia G86 [GeForce 8500 GT]                                                             | 4        | 0.5%    |
| Nvidia C77 [GeForce 8200]                                                                | 4        | 0.5%    |
| Intel Core Processor Integrated Graphics Controller                                      | 4        | 0.5%    |
| Intel 82Q963/Q965 Integrated Graphics Controller                                         | 4        | 0.5%    |
| AMD Juniper XT [Radeon HD 5770]                                                          | 4        | 0.5%    |
| AMD Barts PRO [Radeon HD 6850]                                                           | 4        | 0.5%    |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 4        | 0.5%    |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 4        | 0.5%    |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 3        | 0.37%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 3        | 0.37%   |
| Nvidia GT218 [GeForce 310]                                                               | 3        | 0.37%   |
| Nvidia GT215 [GeForce GT 240]                                                            | 3        | 0.37%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 3        | 0.37%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 3        | 0.37%   |
| Nvidia GK106GL [Quadro K4000]                                                            | 3        | 0.37%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                                        | 3        | 0.37%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 291      | 39.43%  |
| 1 x Intel                | 223      | 30.22%  |
| 1 x AMD                  | 185      | 25.07%  |
| 2 x AMD                  | 14       | 1.9%    |
| Intel + Nvidia           | 6        | 0.81%   |
| 2 x Nvidia               | 4        | 0.54%   |
| Intel + AMD              | 4        | 0.54%   |
| AMD + Nvidia             | 3        | 0.41%   |
| Other                    | 2        | 0.27%   |
| 1 x VIA                  | 2        | 0.27%   |
| 1 x Matrox               | 2        | 0.27%   |
| 2 x AMD + 1 x Nvidia     | 1        | 0.14%   |
| Intel + AMD + 1 x Nvidia | 1        | 0.14%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 521      | 70.5%   |
| Proprietary | 192      | 25.98%  |
| Unknown     | 26       | 3.52%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 275      | 36.86%  |
| 0.51-1.0   | 123      | 16.49%  |
| 0.01-0.5   | 118      | 15.82%  |
| 1.01-2.0   | 112      | 15.01%  |
| 3.01-4.0   | 65       | 8.71%   |
| 7.01-8.0   | 30       | 4.02%   |
| 5.01-6.0   | 10       | 1.34%   |
| 8.01-16.0  | 7        | 0.94%   |
| 2.01-3.0   | 5        | 0.67%   |
| 4.01-5.0   | 1        | 0.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 123      | 16.29%  |
| Dell                    | 89       | 11.79%  |
| Hewlett-Packard         | 58       | 7.68%   |
| Goldstar                | 58       | 7.68%   |
| Acer                    | 57       | 7.55%   |
| Philips                 | 44       | 5.83%   |
| Ancor Communications    | 29       | 3.84%   |
| AOC                     | 26       | 3.44%   |
| BenQ                    | 25       | 3.31%   |
| Unknown                 | 21       | 2.78%   |
| LG Electronics          | 18       | 2.38%   |
| ViewSonic               | 17       | 2.25%   |
| Sony                    | 16       | 2.12%   |
| Fujitsu Siemens         | 16       | 2.12%   |
| HannStar                | 12       | 1.59%   |
| NEC Computers           | 11       | 1.46%   |
| Panasonic               | 10       | 1.32%   |
| Iiyama                  | 9        | 1.19%   |
| Medion                  | 7        | 0.93%   |
| Lenovo                  | 7        | 0.93%   |
| Eizo                    | 6        | 0.79%   |
| ASUSTek Computer        | 5        | 0.66%   |
| Vizio                   | 4        | 0.53%   |
| Vestel Elektronik       | 3        | 0.4%    |
| Lenovo Group Limited    | 3        | 0.4%    |
| Idek Iiyama             | 3        | 0.4%    |
| Haier                   | 3        | 0.4%    |
| Chi Mei Optoelectronics | 3        | 0.4%    |
| Tech Concepts           | 2        | 0.26%   |
| Sharp                   | 2        | 0.26%   |
| Packard Bell            | 2        | 0.26%   |
| ONN                     | 2        | 0.26%   |
| MStar                   | 2        | 0.26%   |
| IOD                     | 2        | 0.26%   |
| Insignia                | 2        | 0.26%   |
| IBM                     | 2        | 0.26%   |
| HPN                     | 2        | 0.26%   |
| Gateway                 | 2        | 0.26%   |
| DENON                   | 2        | 0.26%   |
| CVT                     | 2        | 0.26%   |
| CHR                     | 2        | 0.26%   |
| AGO                     | 2        | 0.26%   |
| ___                     | 1        | 0.13%   |
| Westinghouse            | 1        | 0.13%   |
| Viotek                  | 1        | 0.13%   |
| Vestel                  | 1        | 0.13%   |
| Unknown (AAA)           | 1        | 0.13%   |
| TEO                     | 1        | 0.13%   |
| TechniMedia             | 1        | 0.13%   |
| TCL                     | 1        | 0.13%   |
| Targa Visionary         | 1        | 0.13%   |
| Skyworth                | 1        | 0.13%   |
| SGT                     | 1        | 0.13%   |
| SENSY                   | 1        | 0.13%   |
| Seiki                   | 1        | 0.13%   |
| Sceptre Tech            | 1        | 0.13%   |
| Sceptre                 | 1        | 0.13%   |
| RTK                     | 1        | 0.13%   |
| RS                      | 1        | 0.13%   |
| PRI                     | 1        | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Panasonic TV MEIA296 3840x2160 1280x720mm 57.8-inch                    | 6        | 0.75%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                  | 4        | 0.5%    |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch  | 4        | 0.5%    |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 890x500mm 40.2-inch   | 3        | 0.37%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch      | 3        | 0.37%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch      | 3        | 0.37%   |
| Samsung Electronics LCD Monitor SyncMaster                             | 3        | 0.37%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 3        | 0.37%   |
| Philips 196VL PHLC07F 1366x768 409x230mm 18.5-inch                     | 3        | 0.37%   |
| Hewlett-Packard P19A HWP3087 1280x1024 338x270mm 17.0-inch             | 3        | 0.37%   |
| Goldstar LCD Monitor GSM5AB8 1920x1080 480x270mm 21.7-inch             | 3        | 0.37%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 3        | 0.37%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                      | 3        | 0.37%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 3        | 0.37%   |
| Dell 1908FP DEL4026 1280x1024 376x301mm 19.0-inch                      | 3        | 0.37%   |
| Acer AL1716A ACRAD46 1280x1024 338x270mm 17.0-inch                     | 3        | 0.37%   |
| ViewSonic VX2250 SERIES VSCCB25 1920x1080 477x268mm 21.5-inch          | 2        | 0.25%   |
| Unknown LCD Monitor SAMSUNG 3840x1080                                  | 2        | 0.25%   |
| Samsung Electronics U32J59x SAM0F33 3840x2160 697x392mm 31.5-inch      | 2        | 0.25%   |
| Samsung Electronics SyncMaster SAM03C2 1680x1050 459x296mm 21.5-inch   | 2        | 0.25%   |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x260mm 19.1-inch    | 2        | 0.25%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch   | 2        | 0.25%   |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 598x336mm 27.0-inch   | 2        | 0.25%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 518x324mm 24.1-inch    | 2        | 0.25%   |
| Samsung Electronics SMB1930N SAM0632 1360x768 410x230mm 18.5-inch      | 2        | 0.25%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch      | 2        | 0.25%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch      | 2        | 0.25%   |
| Samsung Electronics S22D390 SAM0B63 1920x1080 477x268mm 21.5-inch      | 2        | 0.25%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch      | 2        | 0.25%   |
| Samsung Electronics LS32R75 SAM0F92 3840x2160 697x392mm 31.5-inch      | 2        | 0.25%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1080                   | 2        | 0.25%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                   | 2        | 0.25%   |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 1060x626mm 48.5-inch | 2        | 0.25%   |
| Samsung Electronics C27R50x SAM0F9D 1920x1080 600x340mm 27.2-inch      | 2        | 0.25%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                | 2        | 0.25%   |
| Philips 227E4Q PHLC0A9 1920x1080 477x268mm 21.5-inch                   | 2        | 0.25%   |
| Philips 221V PHL0888 1920x1080 480x270mm 21.7-inch                     | 2        | 0.25%   |
| Philips 170S PHL0839 1280x1024 338x270mm 17.0-inch                     | 2        | 0.25%   |
| ONN 100002487 ONN0101 1920x1080 517x323mm 24.0-inch                    | 2        | 0.25%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                       | 2        | 0.25%   |
| Medion MD 20144 MED3634 1920x1080 521x293mm 23.5-inch                  | 2        | 0.25%   |
| LG Electronics LCD Monitor LG TV 1920x1080                             | 2        | 0.25%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                        | 2        | 0.25%   |
| Lenovo Group Limited LCD Monitor LEN LT2452pwC 1920x1200               | 2        | 0.25%   |
| Iiyama PLE2483H IVM6113 1920x1080 530x300mm 24.0-inch                  | 2        | 0.25%   |
| Hewlett-Packard LP2465 HWP2676 1920x1200 519x324mm 24.1-inch           | 2        | 0.25%   |
| Hewlett-Packard LE2201w HWP2843 1680x1050 473x296mm 22.0-inch          | 2        | 0.25%   |
| Hewlett-Packard LE1901w HWP2842 1440x900 410x256mm 19.0-inch           | 2        | 0.25%   |
| Hewlett-Packard L1740 HWP2648 1280x1024 338x270mm 17.0-inch            | 2        | 0.25%   |
| Hewlett-Packard E201 HWP305C 1600x900 443x249mm 20.0-inch              | 2        | 0.25%   |
| Hewlett-Packard Compaq S1922 HWP290B 1366x768 413x234mm 18.7-inch      | 2        | 0.25%   |
| HannStar HW191D HSD8991 1440x900 408x255mm 18.9-inch                   | 2        | 0.25%   |
| HannStar HF225 HSP18BB 1920x1080 477x268mm 21.5-inch                   | 2        | 0.25%   |
| HannStar Hanns.G Hi221 HSD2469 1680x1050 474x297mm 22.0-inch           | 2        | 0.25%   |
| Haier HL24XD2 HAR2410 1920x1080 520x290mm 23.4-inch                    | 2        | 0.25%   |
| Goldstar W2242 GSM4B6F 1680x1050 474x296mm 22.0-inch                   | 2        | 0.25%   |
| Goldstar W2241 GSM56B3 1680x1050 474x296mm 22.0-inch                   | 2        | 0.25%   |
| Goldstar ULTRAWIDE GSM76E4 3440x1440 800x335mm 34.1-inch               | 2        | 0.25%   |
| Goldstar L1730S GSM438D 1280x1024 338x270mm 17.0-inch                  | 2        | 0.25%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                       | 2        | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 301      | 40.29%  |
| 1280x1024 (SXGA)   | 85       | 11.38%  |
| 1680x1050 (WSXGA+) | 48       | 6.43%   |
| 1440x900 (WXGA+)   | 42       | 5.62%   |
| 1366x768 (WXGA)    | 41       | 5.49%   |
| 3840x2160 (4K)     | 40       | 5.35%   |
| 1920x1200 (WUXGA)  | 32       | 4.28%   |
| Unknown            | 31       | 4.15%   |
| 2560x1440 (QHD)    | 25       | 3.35%   |
| 1600x900 (HD+)     | 23       | 3.08%   |
| 1360x768           | 12       | 1.61%   |
| 3840x1080          | 11       | 1.47%   |
| 1600x1200          | 8        | 1.07%   |
| 1024x768 (XGA)     | 8        | 1.07%   |
| 3440x1440          | 4        | 0.54%   |
| 1920x540           | 4        | 0.54%   |
| 1280x720 (HD)      | 4        | 0.54%   |
| 5120x1440          | 3        | 0.4%    |
| 3200x1080          | 3        | 0.4%    |
| 3840x1200          | 2        | 0.27%   |
| 3286x1080          | 2        | 0.27%   |
| 2960x1050          | 2        | 0.27%   |
| 2560x1600          | 2        | 0.27%   |
| 2560x1080          | 2        | 0.27%   |
| 5760x2160          | 1        | 0.13%   |
| 5280x2160          | 1        | 0.13%   |
| 5280x1080          | 1        | 0.13%   |
| 4480x1440          | 1        | 0.13%   |
| 3600x1080          | 1        | 0.13%   |
| 3360x1080          | 1        | 0.13%   |
| 3280x1080          | 1        | 0.13%   |
| 3200x900           | 1        | 0.13%   |
| 2640x768           | 1        | 0.13%   |
| 2288x1287          | 1        | 0.13%   |
| 1400x1050          | 1        | 0.13%   |
| 1280x800 (WXGA)    | 1        | 0.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 125      | 16.94%  |
| 19      | 79       | 10.7%   |
| 21      | 73       | 9.89%   |
| 24      | 72       | 9.76%   |
| 23      | 71       | 9.62%   |
| 27      | 56       | 7.59%   |
| 17      | 42       | 5.69%   |
| 18      | 36       | 4.88%   |
| 20      | 35       | 4.74%   |
| 22      | 31       | 4.2%    |
| 31      | 21       | 2.85%   |
| 15      | 13       | 1.76%   |
| 84      | 10       | 1.36%   |
| 40      | 8        | 1.08%   |
| 72      | 7        | 0.95%   |
| 32      | 7        | 0.95%   |
| 34      | 5        | 0.68%   |
| 25      | 5        | 0.68%   |
| 54      | 4        | 0.54%   |
| 28      | 4        | 0.54%   |
| 26      | 4        | 0.54%   |
| 14      | 4        | 0.54%   |
| 52      | 3        | 0.41%   |
| 48      | 3        | 0.41%   |
| 37      | 2        | 0.27%   |
| 29      | 2        | 0.27%   |
| 13      | 2        | 0.27%   |
| 142     | 1        | 0.14%   |
| 69      | 1        | 0.14%   |
| 65      | 1        | 0.14%   |
| 60      | 1        | 0.14%   |
| 57      | 1        | 0.14%   |
| 49      | 1        | 0.14%   |
| 47      | 1        | 0.14%   |
| 46      | 1        | 0.14%   |
| 41      | 1        | 0.14%   |
| 39      | 1        | 0.14%   |
| 38      | 1        | 0.14%   |
| 16      | 1        | 0.14%   |
| 12      | 1        | 0.14%   |
| 11      | 1        | 0.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 401-500        | 199      | 27.45%  |
| 501-600        | 194      | 26.76%  |
| Unknown        | 125      | 17.24%  |
| 301-350        | 53       | 7.31%   |
| 351-400        | 51       | 7.03%   |
| 601-700        | 35       | 4.83%   |
| 1501-2000      | 18       | 2.48%   |
| 1001-1500      | 16       | 2.21%   |
| 801-900        | 12       | 1.66%   |
| 701-800        | 12       | 1.66%   |
| 201-300        | 8        | 1.1%    |
| More than 2000 | 1        | 0.14%   |
| 901-1000       | 1        | 0.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 360      | 50.99%  |
| Unknown | 118      | 16.71%  |
| 16/10   | 113      | 16.01%  |
| 5/4     | 83       | 11.76%  |
| 4/3     | 19       | 2.69%   |
| 21/9    | 5        | 0.71%   |
| 6/5     | 3        | 0.42%   |
| 3/2     | 3        | 0.42%   |
| 1.96    | 1        | 0.14%   |
| 1.00    | 1        | 0.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 200      | 27.4%   |
| 151-200        | 138      | 18.9%   |
| Unknown        | 125      | 17.12%  |
| 141-150        | 64       | 8.77%   |
| 301-350        | 58       | 7.95%   |
| 351-500        | 36       | 4.93%   |
| 251-300        | 36       | 4.93%   |
| More than 1000 | 32       | 4.38%   |
| 101-110        | 16       | 2.19%   |
| 501-1000       | 16       | 2.19%   |
| 131-140        | 4        | 0.55%   |
| 81-90          | 2        | 0.27%   |
| 71-80          | 1        | 0.14%   |
| 51-60          | 1        | 0.14%   |
| 91-100         | 1        | 0.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 427      | 60.83%  |
| Unknown | 125      | 17.81%  |
| 101-120 | 93       | 13.25%  |
| 1-50    | 29       | 4.13%   |
| 121-160 | 26       | 3.7%    |
| 161-240 | 2        | 0.28%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 593      | 80.24%  |
| 2     | 102      | 13.8%   |
| 0     | 36       | 4.87%   |
| 3     | 6        | 0.81%   |
| 4     | 2        | 0.27%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 419      | 39.83%  |
| Intel                                 | 289      | 27.47%  |
| Qualcomm Atheros                      | 72       | 6.84%   |
| Broadcom                              | 45       | 4.28%   |
| Nvidia                                | 36       | 3.42%   |
| Ralink Technology                     | 28       | 2.66%   |
| TP-Link                               | 21       | 2%      |
| Qualcomm Atheros Communications       | 15       | 1.43%   |
| Ralink                                | 11       | 1.05%   |
| D-Link System                         | 11       | 1.05%   |
| Marvell Technology Group              | 9        | 0.86%   |
| Broadcom Limited                      | 9        | 0.86%   |
| NetGear                               | 8        | 0.76%   |
| D-Link                                | 8        | 0.76%   |
| Huawei Technologies                   | 7        | 0.67%   |
| VIA Technologies                      | 6        | 0.57%   |
| Samsung Electronics                   | 4        | 0.38%   |
| Microsoft                             | 4        | 0.38%   |
| MediaTek                              | 4        | 0.38%   |
| Edimax Technology                     | 4        | 0.38%   |
| Belkin Components                     | 4        | 0.38%   |
| Linksys                               | 3        | 0.29%   |
| AVM                                   | 3        | 0.29%   |
| Aquantia                              | 3        | 0.29%   |
| Xiaomi                                | 2        | 0.19%   |
| TRENDnet                              | 2        | 0.19%   |
| Qualcomm                              | 2        | 0.19%   |
| IMC Networks                          | 2        | 0.19%   |
| ASUSTek Computer                      | 2        | 0.19%   |
| ASIX Electronics                      | 2        | 0.19%   |
| Arduino SA                            | 2        | 0.19%   |
| 3Com                                  | 2        | 0.19%   |
| ZyXEL Communications                  | 1        | 0.1%    |
| ZyDAS                                 | 1        | 0.1%    |
| Wacom                                 | 1        | 0.1%    |
| Van Ooijen Technische Informatica     | 1        | 0.1%    |
| STMicroelectronics                    | 1        | 0.1%    |
| Philips (or NXP)                      | 1        | 0.1%    |
| Mellanox Technologies                 | 1        | 0.1%    |
| Manta                                 | 1        | 0.1%    |
| LSI                                   | 1        | 0.1%    |
| LG Electronics                        | 1        | 0.1%    |
| DisplayLink                           | 1        | 0.1%    |
| Apple                                 | 1        | 0.1%    |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 330      | 28.92%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 46       | 4.03%   |
| Intel Ethernet Connection I217-LM                                 | 26       | 2.28%   |
| Intel I211 Gigabit Network Connection                             | 24       | 2.1%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 23       | 2.02%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 22       | 1.93%   |
| Nvidia MCP61 Ethernet                                             | 20       | 1.75%   |
| Intel Wi-Fi 6 AX200                                               | 20       | 1.75%   |
| Intel Ethernet Connection (2) I219-V                              | 19       | 1.67%   |
| Intel 82579V Gigabit Network Connection                           | 19       | 1.67%   |
| Ralink MT7601U Wireless Adapter                                   | 15       | 1.31%   |
| Qualcomm Atheros AR9271 802.11n                                   | 13       | 1.14%   |
| Realtek RTL8125 2.5GbE Controller                                 | 12       | 1.05%   |
| Intel 82574L Gigabit Network Connection                           | 12       | 1.05%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 11       | 0.96%   |
| Intel Ethernet Connection I217-V                                  | 11       | 0.96%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 11       | 0.96%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 10       | 0.88%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 10       | 0.88%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 9        | 0.79%   |
| Nvidia MCP77 Ethernet                                             | 9        | 0.79%   |
| Intel Ethernet Connection (2) I218-V                              | 8        | 0.7%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 7        | 0.61%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 7        | 0.61%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 7        | 0.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 7        | 0.61%   |
| Intel Ethernet Connection (7) I219-V                              | 7        | 0.61%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 6        | 0.53%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 6        | 0.53%   |
| Intel Wireless-AC 9260                                            | 6        | 0.53%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 6        | 0.53%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 6        | 0.53%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 5        | 0.44%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 5        | 0.44%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 5        | 0.44%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 5        | 0.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 5        | 0.44%   |
| Intel Ethernet Connection (2) I219-LM                             | 5        | 0.44%   |
| Intel 82578DC Gigabit Network Connection                          | 5        | 0.44%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 5        | 0.44%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 5        | 0.44%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 5        | 0.44%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 4        | 0.35%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 4        | 0.35%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 4        | 0.35%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 4        | 0.35%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 4        | 0.35%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 4        | 0.35%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 4        | 0.35%   |
| NetGear A6210                                                     | 4        | 0.35%   |
| Intel Wireless 3160                                               | 4        | 0.35%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4        | 0.35%   |
| Intel 82566DM Gigabit Network Connection                          | 4        | 0.35%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 3        | 0.26%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                            | 3        | 0.26%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 3        | 0.26%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 3        | 0.26%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3        | 0.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 0.26%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 3        | 0.26%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 80       | 24.54%  |
| Intel                                 | 54       | 16.56%  |
| Qualcomm Atheros                      | 44       | 13.5%   |
| Ralink Technology                     | 28       | 8.59%   |
| TP-Link                               | 21       | 6.44%   |
| Broadcom                              | 17       | 5.21%   |
| Qualcomm Atheros Communications       | 15       | 4.6%    |
| Ralink                                | 11       | 3.37%   |
| NetGear                               | 8        | 2.45%   |
| D-Link                                | 8        | 2.45%   |
| D-Link System                         | 7        | 2.15%   |
| Microsoft                             | 4        | 1.23%   |
| Edimax Technology                     | 4        | 1.23%   |
| Belkin Components                     | 4        | 1.23%   |
| Linksys                               | 3        | 0.92%   |
| Broadcom Limited                      | 3        | 0.92%   |
| AVM                                   | 3        | 0.92%   |
| TRENDnet                              | 2        | 0.61%   |
| IMC Networks                          | 2        | 0.61%   |
| ASUSTek Computer                      | 2        | 0.61%   |
| ZyXEL Communications                  | 1        | 0.31%   |
| ZyDAS                                 | 1        | 0.31%   |
| Wacom                                 | 1        | 0.31%   |
| Philips (or NXP)                      | 1        | 0.31%   |
| Marvell Technology Group              | 1        | 0.31%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.31%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                           | 20       | 6.08%   |
| Ralink MT7601U Wireless Adapter                                                               | 15       | 4.56%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 13       | 3.95%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 11       | 3.34%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 10       | 3.04%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 9        | 2.74%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 7        | 2.13%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 7        | 2.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 7        | 2.13%   |
| Intel Wireless-AC 9260                                                                        | 6        | 1.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 6        | 1.82%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                            | 6        | 1.82%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 5        | 1.52%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 5        | 1.52%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 5        | 1.52%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 5        | 1.52%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 4        | 1.22%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 4        | 1.22%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 4        | 1.22%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                              | 4        | 1.22%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 4        | 1.22%   |
| NetGear A6210                                                                                 | 4        | 1.22%   |
| Intel Wireless 3160                                                                           | 4        | 1.22%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 4        | 1.22%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 3        | 0.91%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                                        | 3        | 0.91%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 3        | 0.91%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 3        | 0.91%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 3        | 0.91%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 3        | 0.91%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                              | 3        | 0.91%   |
| Intel Wireless 7260                                                                           | 3        | 0.91%   |
| Intel Wireless 3165                                                                           | 3        | 0.91%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                           | 2        | 0.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 2        | 0.61%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 2        | 0.61%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                       | 2        | 0.61%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                                        | 2        | 0.61%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                                     | 2        | 0.61%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 2        | 0.61%   |
| Realtek 802.11ac NIC                                                                          | 2        | 0.61%   |
| Ralink RT5370 Wireless Adapter                                                                | 2        | 0.61%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                             | 2        | 0.61%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 2        | 0.61%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                     | 2        | 0.61%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                                     | 2        | 0.61%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 2        | 0.61%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg]                | 2        | 0.61%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                                    | 2        | 0.61%   |
| Microsoft XBOX ACC                                                                            | 2        | 0.61%   |
| Microsoft Xbox 360 Wireless Adapter                                                           | 2        | 0.61%   |
| Intel Wireless 8260                                                                           | 2        | 0.61%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 2        | 0.61%   |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]                                          | 2        | 0.61%   |
| D-Link DWA-160 802.11abgn Xtreme N Dual Band Adapter(rev.B2) [Ralink RT5572]                  | 2        | 0.61%   |
| D-Link DWA-121 802.11n Wireless N 150 Pico Adapter [Realtek RTL8188CUS]                       | 2        | 0.61%   |
| D-Link 802.11 n WLAN                                                                          | 2        | 0.61%   |
| Broadcom BCM43228 802.11a/b/g/n                                                               | 2        | 0.61%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                        | 2        | 0.61%   |
| Belkin Components F7D2101 802.11n Surf & Share Wireless Adapter v1000 [Realtek RTL8192SU]     | 2        | 0.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 379      | 48.22%  |
| Intel                    | 256      | 32.57%  |
| Nvidia                   | 36       | 4.58%   |
| Qualcomm Atheros         | 34       | 4.33%   |
| Broadcom                 | 29       | 3.69%   |
| Marvell Technology Group | 8        | 1.02%   |
| VIA Technologies         | 6        | 0.76%   |
| Broadcom Limited         | 6        | 0.76%   |
| Huawei Technologies      | 5        | 0.64%   |
| Samsung Electronics      | 4        | 0.51%   |
| MediaTek                 | 4        | 0.51%   |
| D-Link System            | 4        | 0.51%   |
| Aquantia                 | 3        | 0.38%   |
| Xiaomi                   | 2        | 0.25%   |
| Qualcomm                 | 2        | 0.25%   |
| ASIX Electronics         | 2        | 0.25%   |
| 3Com                     | 2        | 0.25%   |
| Mellanox Technologies    | 1        | 0.13%   |
| LG Electronics           | 1        | 0.13%   |
| DisplayLink              | 1        | 0.13%   |
| Apple                    | 1        | 0.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 330      | 41.1%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 46       | 5.73%   |
| Intel Ethernet Connection I217-LM                                 | 26       | 3.24%   |
| Intel I211 Gigabit Network Connection                             | 24       | 2.99%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 23       | 2.86%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 22       | 2.74%   |
| Nvidia MCP61 Ethernet                                             | 20       | 2.49%   |
| Intel Ethernet Connection (2) I219-V                              | 19       | 2.37%   |
| Intel 82579V Gigabit Network Connection                           | 19       | 2.37%   |
| Realtek RTL8125 2.5GbE Controller                                 | 12       | 1.49%   |
| Intel 82574L Gigabit Network Connection                           | 12       | 1.49%   |
| Intel Ethernet Connection I217-V                                  | 11       | 1.37%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 11       | 1.37%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 10       | 1.25%   |
| Nvidia MCP77 Ethernet                                             | 9        | 1.12%   |
| Intel Ethernet Connection (2) I218-V                              | 8        | 1%      |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 7        | 0.87%   |
| Intel Ethernet Connection (7) I219-V                              | 7        | 0.87%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 6        | 0.75%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 6        | 0.75%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 5        | 0.62%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 5        | 0.62%   |
| Intel Ethernet Connection (2) I219-LM                             | 5        | 0.62%   |
| Intel 82578DC Gigabit Network Connection                          | 5        | 0.62%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 5        | 0.62%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 5        | 0.62%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 4        | 0.5%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 4        | 0.5%    |
| Intel 82566DM Gigabit Network Connection                          | 4        | 0.5%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3        | 0.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 0.37%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 3        | 0.37%   |
| Nvidia MCP51 Ethernet Controller                                  | 3        | 0.37%   |
| MediaTek NOA N2                                                   | 3        | 0.37%   |
| Intel I210 Gigabit Network Connection                             | 3        | 0.37%   |
| Intel Ethernet Connection (11) I219-V                             | 3        | 0.37%   |
| Intel 82578DM Gigabit Network Connection                          | 3        | 0.37%   |
| Intel 82573L Gigabit Ethernet Controller                          | 3        | 0.37%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 3        | 0.37%   |
| Huawei JNY-LX1                                                    | 3        | 0.37%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                   | 3        | 0.37%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 3        | 0.37%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 0.25%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2        | 0.25%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.25%   |
| Qualcomm Mobile Router                                            | 2        | 0.25%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2        | 0.25%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2        | 0.25%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2        | 0.25%   |
| Nvidia MCP73 Ethernet                                             | 2        | 0.25%   |
| Intel Ethernet Controller I225-V                                  | 2        | 0.25%   |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 0.25%   |
| Intel Ethernet Connection (2) I218-LM                             | 2        | 0.25%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 0.25%   |
| Intel 82566DC Gigabit Network Connection                          | 2        | 0.25%   |
| Intel 82562V-2 10/100 Network Connection                          | 2        | 0.25%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 2        | 0.25%   |
| Intel 82541PI Gigabit Ethernet Controller                         | 2        | 0.25%   |
| D-Link System RTL8139 Ethernet                                    | 2        | 0.25%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2        | 0.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 725      | 70.12%  |
| WiFi     | 300      | 29.01%  |
| Modem    | 7        | 0.68%   |
| Unknown  | 2        | 0.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 610      | 73.58%  |
| WiFi     | 219      | 26.42%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 536      | 73.02%  |
| 2     | 164      | 22.34%  |
| 3     | 23       | 3.13%   |
| 0     | 6        | 0.82%   |
| 4     | 4        | 0.54%   |
| 5     | 1        | 0.14%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 631      | 85.39%  |
| Yes  | 108      | 14.61%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 52       | 33.77%  |
| Cambridge Silicon Radio         | 40       | 25.97%  |
| Broadcom                        | 18       | 11.69%  |
| Qualcomm Atheros Communications | 13       | 8.44%   |
| ASUSTek Computer                | 7        | 4.55%   |
| Realtek Semiconductor           | 5        | 3.25%   |
| IMC Networks                    | 5        | 3.25%   |
| Integrated System Solution      | 3        | 1.95%   |
| Apple                           | 3        | 1.95%   |
| Lite-On Technology              | 2        | 1.3%    |
| Edimax Technology               | 2        | 1.3%    |
| Sitecom Europe                  | 1        | 0.65%   |
| Dell                            | 1        | 0.65%   |
| Conwise Technology              | 1        | 0.65%   |
| Unknown                         | 1        | 0.65%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)       | 40       | 25.97%  |
| Intel AX200 Bluetooth                                     | 22       | 14.29%  |
| Intel Bluetooth wireless interface                        | 11       | 7.14%   |
| Broadcom BCM20702A0 Bluetooth 4.0                         | 10       | 6.49%   |
| Qualcomm Atheros AR3011 Bluetooth                         | 6        | 3.9%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                  | 6        | 3.9%    |
| Intel Wireless-AC 3168 Bluetooth                          | 6        | 3.9%    |
| Qualcomm Atheros  Bluetooth Device                        | 5        | 3.25%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)            | 5        | 3.25%   |
| Realtek Bluetooth Radio                                   | 3        | 1.95%   |
| Integrated System Solution Bluetooth Device               | 3        | 1.95%   |
| IMC Networks BCM20702A0                                   | 3        | 1.95%   |
| Broadcom ANYCOM Blue USB-UHE 200/250                      | 3        | 1.95%   |
| ASUS Broadcom BCM20702A0 Bluetooth                        | 3        | 1.95%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                      | 3        | 1.95%   |
| Lite-On Bluetooth Device                                  | 2        | 1.3%    |
| Intel Bluetooth Device                                    | 2        | 1.3%    |
| Broadcom BCM2045 Bluetooth                                | 2        | 1.3%    |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE     | 2        | 1.3%    |
| ASUS BCM20702A0                                           | 2        | 1.3%    |
| Sitecom Europe Sitecom bluetooth2.0 class 2 dongle CN-512 | 1        | 0.65%   |
| Realtek RTL8821A Bluetooth                                | 1        | 0.65%   |
| Realtek  Bluetooth 4.2 Adapter                            | 1        | 0.65%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                    | 1        | 0.65%   |
| Qualcomm Atheros AR9462 Bluetooth                         | 1        | 0.65%   |
| IMC Networks Bluetooth Radio                              | 1        | 0.65%   |
| IMC Networks Bluetooth Device                             | 1        | 0.65%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter   | 1        | 0.65%   |
| Edimax Bluetooth Adapter                                  | 1        | 0.65%   |
| Dell Wireless 365 Bluetooth                               | 1        | 0.65%   |
| Conwise CW6622                                            | 1        | 0.65%   |
| Broadcom BCM92046DG-CL1ROM                                | 1        | 0.65%   |
| Broadcom BCM43142A0 Bluetooth Device                      | 1        | 0.65%   |
| Broadcom BCM20702A0                                       | 1        | 0.65%   |
| Unknown                                                   | 1        | 0.65%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 472      | 39.93%  |
| Nvidia                                          | 281      | 23.77%  |
| AMD                                             | 265      | 22.42%  |
| Creative Labs                                   | 28       | 2.37%   |
| C-Media Electronics                             | 26       | 2.2%    |
| VIA Technologies                                | 12       | 1.02%   |
| Texas Instruments                               | 12       | 1.02%   |
| Logitech                                        | 10       | 0.85%   |
| Yamaha                                          | 8        | 0.68%   |
| Focusrite-Novation                              | 6        | 0.51%   |
| M-Audio                                         | 5        | 0.42%   |
| JMTek                                           | 4        | 0.34%   |
| GN Netcom                                       | 3        | 0.25%   |
| EGO SYStems                                     | 3        | 0.25%   |
| TEAC                                            | 2        | 0.17%   |
| Sennheiser Communications                       | 2        | 0.17%   |
| ESI Audiotechnik                                | 2        | 0.17%   |
| Creative Technology                             | 2        | 0.17%   |
| Alesis                                          | 2        | 0.17%   |
| AKAI Professional M.I.                          | 2        | 0.17%   |
| ZOOM                                            | 1        | 0.08%   |
| Xilinx                                          | 1        | 0.08%   |
| Unknown                                         | 1        | 0.08%   |
| Thesycon Systemsoftware & Consulting            | 1        | 0.08%   |
| Textech International                           | 1        | 0.08%   |
| TerraTec Electronic                             | 1        | 0.08%   |
| Tenx Technology                                 | 1        | 0.08%   |
| Syntek                                          | 1        | 0.08%   |
| STUDIOLOGIC                                     | 1        | 0.08%   |
| Sony                                            | 1        | 0.08%   |
| Samson Technologies                             | 1        | 0.08%   |
| Razer USA                                       | 1        | 0.08%   |
| Plantronics                                     | 1        | 0.08%   |
| Pioneer DJ                                      | 1        | 0.08%   |
| Philips (or NXP)                                | 1        | 0.08%   |
| ONN                                             | 1        | 0.08%   |
| Onkyo                                           | 1        | 0.08%   |
| Microchip Technology                            | 1        | 0.08%   |
| Line6                                           | 1        | 0.08%   |
| Licensed by Sony Computer Entertainment America | 1        | 0.08%   |
| Lautsprecher Teufel                             | 1        | 0.08%   |
| KORG                                            | 1        | 0.08%   |
| Holtek Semiconductor                            | 1        | 0.08%   |
| HiFimeDIY Audio                                 | 1        | 0.08%   |
| Generalplus Technology                          | 1        | 0.08%   |
| FiiO Electronics Technology                     | 1        | 0.08%   |
| Ensoniq                                         | 1        | 0.08%   |
| Elitegroup Computer Systems (ECS)               | 1        | 0.08%   |
| DigiTech                                        | 1        | 0.08%   |
| Corsair                                         | 1        | 0.08%   |
| Cambridge Silicon Radio                         | 1        | 0.08%   |
| Blue Microphones                                | 1        | 0.08%   |
| Atmel                                           | 1        | 0.08%   |
| ASUSTek Computer                                | 1        | 0.08%   |
| ARTURIA                                         | 1        | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 72       | 5.32%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 67       | 4.95%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 59       | 4.36%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 48       | 3.55%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 44       | 3.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 42       | 3.1%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 37       | 2.73%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 34       | 2.51%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 30       | 2.22%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 29       | 2.14%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 28       | 2.07%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 28       | 2.07%   |
| AMD FCH Azalia Controller                                                                         | 28       | 2.07%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 28       | 2.07%   |
| Nvidia High Definition Audio Controller                                                           | 24       | 1.77%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 24       | 1.77%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 24       | 1.77%   |
| Intel 200 Series PCH HD Audio                                                                     | 24       | 1.77%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 22       | 1.62%   |
| Nvidia MCP61 High Definition Audio                                                                | 21       | 1.55%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 20       | 1.48%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 19       | 1.4%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 18       | 1.33%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 15       | 1.11%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 15       | 1.11%   |
| Intel Cannon Lake PCH cAVS                                                                        | 14       | 1.03%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 13       | 0.96%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 13       | 0.96%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 12       | 0.89%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 12       | 0.89%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 11       | 0.81%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 10       | 0.74%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 10       | 0.74%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 10       | 0.74%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 10       | 0.74%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 10       | 0.74%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 9        | 0.66%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 9        | 0.66%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 9        | 0.66%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 9        | 0.66%   |
| AMD Kabini HDMI/DP Audio                                                                          | 9        | 0.66%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 9        | 0.66%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 8        | 0.59%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 7        | 0.52%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 7        | 0.52%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 7        | 0.52%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 7        | 0.52%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 7        | 0.52%   |
| Creative Labs EMU20k1 [Sound Blaster X-Fi Series]                                                 | 7        | 0.52%   |
| Creative Labs CA0106/CA0111 [SB Live!/Audigy/X-Fi Series]                                         | 7        | 0.52%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 7        | 0.52%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 7        | 0.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6        | 0.44%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 6        | 0.44%   |
| AMD Wrestler HDMI Audio                                                                           | 6        | 0.44%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                                    | 6        | 0.44%   |
| AMD Barts HDMI Audio [Radeon HD 6790/6850/6870 / 7720 OEM]                                        | 6        | 0.44%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 5        | 0.37%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 5        | 0.37%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 5        | 0.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 72       | 20.69%  |
| Kingston            | 49       | 14.08%  |
| Samsung Electronics | 43       | 12.36%  |
| SK Hynix            | 35       | 10.06%  |
| Crucial             | 34       | 9.77%   |
| Corsair             | 26       | 7.47%   |
| G.Skill             | 22       | 6.32%   |
| Micron Technology   | 19       | 5.46%   |
| Nanya Technology    | 7        | 2.01%   |
| Elpida              | 7        | 2.01%   |
| Team                | 6        | 1.72%   |
| Transcend           | 3        | 0.86%   |
| Patriot             | 3        | 0.86%   |
| A-DATA Technology   | 3        | 0.86%   |
| Unifosa             | 2        | 0.57%   |
| GOODRAM             | 2        | 0.57%   |
| Walton Chaintech    | 1        | 0.29%   |
| Toshiba             | 1        | 0.29%   |
| Smart               | 1        | 0.29%   |
| Sesame              | 1        | 0.29%   |
| S                   | 1        | 0.29%   |
| Ramaxel Technology  | 1        | 0.29%   |
| Qumo                | 1        | 0.29%   |
| Positivo            | 1        | 0.29%   |
| M                   | 1        | 0.29%   |
| GEIL                | 1        | 0.29%   |
| CSX                 | 1        | 0.29%   |
| Axiom               | 1        | 0.29%   |
| Avant               | 1        | 0.29%   |
| Apacer              | 1        | 0.29%   |
| Aeneon              | 1        | 0.29%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                           | 7        | 1.76%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s            | 6        | 1.51%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s            | 6        | 1.51%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                        | 5        | 1.26%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                        | 5        | 1.26%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                   | 3        | 0.76%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                   | 3        | 0.76%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                    | 3        | 0.76%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                     | 3        | 0.76%   |
| SK Hynix RAM HYMP112U64CP8-S6 1024MB DIMM DDR2 800MT/s         | 3        | 0.76%   |
| SK Hynix RAM HMT351U6EFR8C-PB 4096MB DIMM DDR3 1800MT/s        | 3        | 0.76%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s           | 3        | 0.76%   |
| Samsung RAM M3 78T5663QZ3-CF7 2048MB DIMM DDR2 1639MT/s        | 3        | 0.76%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s            | 3        | 0.76%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s           | 3        | 0.76%   |
| Crucial RAM CT51264BA160BJ.C8F 4GB DIMM DDR3 1600MT/s          | 3        | 0.76%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 3        | 0.76%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                   | 2        | 0.5%    |
| Unknown RAM Module 4096MB DIMM DDR2                            | 2        | 0.5%    |
| Unknown RAM Module 4096MB DIMM DDR 1333MT/s                    | 2        | 0.5%    |
| Unknown RAM Module 2GB DIMM SDRAM                              | 2        | 0.5%    |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                    | 2        | 0.5%    |
| Unknown RAM Module 2048MB DIMM DDR2 400MT/s                    | 2        | 0.5%    |
| Unknown RAM Module 1024MB DIMM DDR2 400MT/s                    | 2        | 0.5%    |
| Unknown RAM Module 1024MB DIMM DDR2                            | 2        | 0.5%    |
| Unknown RAM Module 1024MB DIMM                                 | 2        | 0.5%    |
| Transcend RAM TS256MSK64W8N 2GB SODIMM DDR3 1866MT/s           | 2        | 0.5%    |
| SK Hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s          | 2        | 0.5%    |
| SK Hynix RAM HMT325U7CFR8C-PB 2GB DIMM DDR3 1600MT/s           | 2        | 0.5%    |
| SK Hynix RAM HMT112U6BFR8C-H9 1GB DIMM DDR3 1333MT/s           | 2        | 0.5%    |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM SDRAM 1867MT/s           | 2        | 0.5%    |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s            | 2        | 0.5%    |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s            | 2        | 0.5%    |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s            | 2        | 0.5%    |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s            | 2        | 0.5%    |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3200MT/s            | 2        | 0.5%    |
| Micron RAM 8ATF1G64AZ-2G3H1 8192MB DIMM DDR4 2400MT/s          | 2        | 0.5%    |
| Micron RAM 16JTF1G64AZ-1G6E1 8GB DIMM SDRAM 1600MT/s           | 2        | 0.5%    |
| Kingston RAM KHX2133C14/8G 8192MB DIMM DDR4 2400MT/s           | 2        | 0.5%    |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s            | 2        | 0.5%    |
| Kingston RAM 99U5584-003.A00LF 4GB DIMM DDR3 1600MT/s          | 2        | 0.5%    |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s            | 2        | 0.5%    |
| G.Skill RAM F4-3000C16-16GISB 16GB DIMM DDR4 3000MT/s          | 2        | 0.5%    |
| Elpida RAM EBE21UE8AFFA-8G-F 2GB DIMM DDR2 800MT/s             | 2        | 0.5%    |
| Crucial RAM CT8G4DFS8266.M8FJ 8GB DIMM DDR4 2667MT/s           | 2        | 0.5%    |
| Crucial RAM CT8G4DFS8266.M8FD 8GB DIMM DDR4 2667MT/s           | 2        | 0.5%    |
| Crucial RAM BLS8G3D1609DS1S00. 8192MB DIMM DDR3 1600MT/s       | 2        | 0.5%    |
| Corsair RAM CMZ8GX3M2A1600C9 4096MB DIMM DDR3 1600MT/s         | 2        | 0.5%    |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s         | 2        | 0.5%    |
| Walton Chaintech RAM AU4G833-13GH902 4096MB DIMM DDR3 1333MT/s | 1        | 0.25%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                      | 1        | 0.25%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                           | 1        | 0.25%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2400MT/s                 | 1        | 0.25%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                 | 1        | 0.25%   |
| Unknown RAM Module 8192MB DIMM DDR4 2667MT/s                   | 1        | 0.25%   |
| Unknown RAM Module 8192MB DIMM DDR3 1066MT/s                   | 1        | 0.25%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                        | 1        | 0.25%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                        | 1        | 0.25%   |
| Unknown RAM Module 512MB DIMM DDR2 667MT/s                     | 1        | 0.25%   |
| Unknown RAM Module 512MB DIMM DDR 533MT/s                      | 1        | 0.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 123      | 39.68%  |
| DDR4    | 99       | 31.94%  |
| DDR2    | 32       | 10.32%  |
| Unknown | 24       | 7.74%   |
| SDRAM   | 22       | 7.1%    |
| DDR     | 9        | 2.9%    |
| LPDDR4  | 1        | 0.32%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 284      | 94.35%  |
| SODIMM  | 16       | 5.32%   |
| FB-DIMM | 1        | 0.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 96       | 28.57%  |
| 8192  | 91       | 27.08%  |
| 2048  | 72       | 21.43%  |
| 16384 | 42       | 12.5%   |
| 1024  | 27       | 8.04%   |
| 512   | 5        | 1.49%   |
| 32768 | 3        | 0.89%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 70       | 20.47%  |
| 1333    | 51       | 14.91%  |
| 2400    | 24       | 7.02%   |
| 800     | 24       | 7.02%   |
| 2667    | 18       | 5.26%   |
| Unknown | 17       | 4.97%   |
| 3200    | 16       | 4.68%   |
| 2133    | 16       | 4.68%   |
| 3600    | 12       | 3.51%   |
| 1867    | 10       | 2.92%   |
| 1866    | 9        | 2.63%   |
| 667     | 9        | 2.63%   |
| 2666    | 8        | 2.34%   |
| 1066    | 7        | 2.05%   |
| 1800    | 6        | 1.75%   |
| 3000    | 5        | 1.46%   |
| 533     | 5        | 1.46%   |
| 400     | 4        | 1.17%   |
| 49926   | 3        | 0.88%   |
| 3800    | 3        | 0.88%   |
| 1639    | 3        | 0.88%   |
| 3400    | 2        | 0.58%   |
| 2800    | 2        | 0.58%   |
| 2733    | 2        | 0.58%   |
| 2200    | 2        | 0.58%   |
| 2048    | 2        | 0.58%   |
| 4333    | 1        | 0.29%   |
| 3533    | 1        | 0.29%   |
| 3466    | 1        | 0.29%   |
| 3266    | 1        | 0.29%   |
| 3100    | 1        | 0.29%   |
| 2933    | 1        | 0.29%   |
| 2866    | 1        | 0.29%   |
| 2000    | 1        | 0.29%   |
| 1334    | 1        | 0.29%   |
| 1067    | 1        | 0.29%   |
| 333     | 1        | 0.29%   |
| 200     | 1        | 0.29%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 26       | 40.63%  |
| Brother Industries  | 15       | 23.44%  |
| Canon               | 9        | 14.06%  |
| Samsung Electronics | 5        | 7.81%   |
| Zebra               | 4        | 6.25%   |
| Seiko Epson         | 2        | 3.13%   |
| QinHeng Electronics | 1        | 1.56%   |
| Pantum              | 1        | 1.56%   |
| Dymo-CoStar         | 1        | 1.56%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| HP LaserJet 400 M401dne                                               | 4        | 6.25%   |
| Zebra ZP 450 Printer                                                  | 3        | 4.69%   |
| HP OfficeJet Pro 7730 series                                          | 2        | 3.13%   |
| HP LaserJet P1005                                                     | 2        | 3.13%   |
| Brother HL-5370DW series                                              | 2        | 3.13%   |
| Brother HL-5340 series                                                | 2        | 3.13%   |
| Zebra ZTC ZP 500 (ZPL)                                                | 1        | 1.56%   |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 1        | 1.56%   |
| Seiko Epson L222 Series                                               | 1        | 1.56%   |
| Samsung Xerox Phaser 3117 Laser Printer                               | 1        | 1.56%   |
| Samsung SCX-4200 series                                               | 1        | 1.56%   |
| Samsung ML-2525W Series                                               | 1        | 1.56%   |
| Samsung M2070 Series                                                  | 1        | 1.56%   |
| Samsung M2020 Series                                                  | 1        | 1.56%   |
| QinHeng CH340S                                                        | 1        | 1.56%   |
| Pantum P2000 Series                                                   | 1        | 1.56%   |
| HP OfficeJet Pro 9010 series                                          | 1        | 1.56%   |
| HP OfficeJet Pro 6960                                                 | 1        | 1.56%   |
| HP Officejet Pro 6230                                                 | 1        | 1.56%   |
| HP LaserJet P2055 series                                              | 1        | 1.56%   |
| HP LaserJet P2015 series                                              | 1        | 1.56%   |
| HP LaserJet P1006                                                     | 1        | 1.56%   |
| HP LaserJet M14-M17                                                   | 1        | 1.56%   |
| HP LaserJet CP 1025                                                   | 1        | 1.56%   |
| HP LaserJet 1320                                                      | 1        | 1.56%   |
| HP LaserJet 1018                                                      | 1        | 1.56%   |
| HP ENVY 4520 series                                                   | 1        | 1.56%   |
| HP Deskjet F4400 series                                               | 1        | 1.56%   |
| HP DeskJet F300 series                                                | 1        | 1.56%   |
| HP DeskJet 5850c                                                      | 1        | 1.56%   |
| HP DeskJet 3700 series                                                | 1        | 1.56%   |
| HP DeskJet 3630 series                                                | 1        | 1.56%   |
| HP Deskjet 3050A                                                      | 1        | 1.56%   |
| HP Color LaserJet CP1215                                              | 1        | 1.56%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                                | 1        | 1.56%   |
| Canon TS3100 series                                                   | 1        | 1.56%   |
| Canon TR8500 series                                                   | 1        | 1.56%   |
| Canon PIXMA MX530 Series                                              | 1        | 1.56%   |
| Canon PIXMA MP190                                                     | 1        | 1.56%   |
| Canon PIXMA MG3600 Series                                             | 1        | 1.56%   |
| Canon MG2400 series                                                   | 1        | 1.56%   |
| Canon iP4700 series                                                   | 1        | 1.56%   |
| Canon G6000 series                                                    | 1        | 1.56%   |
| Canon E4200 series                                                    | 1        | 1.56%   |
| Brother MFC-7460DN                                                    | 1        | 1.56%   |
| Brother HL-L2395DW series                                             | 1        | 1.56%   |
| Brother HL-L2340D series                                              | 1        | 1.56%   |
| Brother HL-L2320D series                                              | 1        | 1.56%   |
| Brother HL-5150D series                                               | 1        | 1.56%   |
| Brother HL-2270DW Laser Printer                                       | 1        | 1.56%   |
| Brother HL-2130 series                                                | 1        | 1.56%   |
| Brother HL-1210W series                                               | 1        | 1.56%   |
| Brother HL-1110 series                                                | 1        | 1.56%   |
| Brother DCP-7030                                                      | 1        | 1.56%   |
| Brother DCP-1510                                                      | 1        | 1.56%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 11       | 64.71%  |
| Seiko Epson     | 3        | 17.65%  |
| Hewlett-Packard | 2        | 11.76%  |
| Mustek Systems  | 1        | 5.88%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                      | 2        | 11.76%  |
| Seiko Epson GT-X770 [Perfection V500]                       | 1        | 5.88%   |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO] | 1        | 5.88%   |
| Seiko Epson GT-7700U [Perfection 1240U]                     | 1        | 5.88%   |
| Mustek Systems ScanExpress 1200 CU                          | 1        | 5.88%   |
| HP ScanJet 82x0C                                            | 1        | 5.88%   |
| HP ScanJet 5590                                             | 1        | 5.88%   |
| Canon CanoScan N670U/N676U/LiDE 20                          | 1        | 5.88%   |
| Canon CanoScan LiDE 90                                      | 1        | 5.88%   |
| Canon CanoScan LIDE 25                                      | 1        | 5.88%   |
| Canon CanoScan LiDE 220                                     | 1        | 5.88%   |
| Canon CanoScan LiDE 210                                     | 1        | 5.88%   |
| Canon CanoScan LiDE 200                                     | 1        | 5.88%   |
| Canon CanoScan LiDE 120                                     | 1        | 5.88%   |
| Canon CanoScan LiDE 110                                     | 1        | 5.88%   |
| Canon CanoScan FB630U                                       | 1        | 5.88%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 47       | 37.3%   |
| Microdia                      | 14       | 11.11%  |
| Microsoft                     | 9        | 7.14%   |
| Samsung Electronics           | 4        | 3.17%   |
| MacroSilicon                  | 4        | 3.17%   |
| Jieli Technology              | 4        | 3.17%   |
| Trust                         | 3        | 2.38%   |
| Sunplus Innovation Technology | 3        | 2.38%   |
| Hewlett-Packard               | 3        | 2.38%   |
| Generalplus Technology        | 3        | 2.38%   |
| Cubeternet                    | 3        | 2.38%   |
| Apple                         | 3        | 2.38%   |
| Z-Star Microelectronics       | 2        | 1.59%   |
| Realtek Semiconductor         | 2        | 1.59%   |
| Razer USA                     | 2        | 1.59%   |
| Creative Technology           | 2        | 1.59%   |
| Arkmicro Technologies         | 2        | 1.59%   |
| ARC International             | 2        | 1.59%   |
| USB3.0 HD Audio Capture       | 1        | 0.79%   |
| Sunplus IT                    | 1        | 0.79%   |
| PrehKeyTec                    | 1        | 0.79%   |
| Pixart Imaging                | 1        | 0.79%   |
| OPPO Electronics              | 1        | 0.79%   |
| Nintendo                      | 1        | 0.79%   |
| Mimaki Engineering            | 1        | 0.79%   |
| Linux Foundation              | 1        | 0.79%   |
| KYE Systems (Mouse Systems)   | 1        | 0.79%   |
| IMC Networks                  | 1        | 0.79%   |
| Huawei Technologies           | 1        | 0.79%   |
| GEMBIRD                       | 1        | 0.79%   |
| Chicony Electronics           | 1        | 0.79%   |
| Aveo Technology               | 1        | 0.79%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Logitech Webcam C270                            | 13       | 10.32%  |
| Logitech HD Pro Webcam C920                     | 9        | 7.14%   |
| Samsung Galaxy A5 (MTP)                         | 4        | 3.17%   |
| Microdia Webcam Vitade AF                       | 4        | 3.17%   |
| MacroSilicon USB Video                          | 4        | 3.17%   |
| Jieli USB PHY 2.0                               | 4        | 3.17%   |
| Trust USB Camera                                | 3        | 2.38%   |
| Microsoft LifeCam Cinema                        | 3        | 2.38%   |
| Logitech HD Webcam C525                         | 3        | 2.38%   |
| Logitech HD Webcam B910                         | 3        | 2.38%   |
| Apple iPhone 5/5C/5S/6/SE                       | 3        | 2.38%   |
| Realtek FULL HD 1080P Webcam                    | 2        | 1.59%   |
| Microsoft LifeCam HD-3000                       | 2        | 1.59%   |
| Microdia USB 2.0 Camera                         | 2        | 1.59%   |
| Microdia Sonix USB 2.0 Camera                   | 2        | 1.59%   |
| Microdia Camera                                 | 2        | 1.59%   |
| Logitech Webcam B500                            | 2        | 1.59%   |
| Logitech QuickCam Pro 9000                      | 2        | 1.59%   |
| Logitech Logitech Webcam C160                   | 2        | 1.59%   |
| Logitech C922 Pro Stream Webcam                 | 2        | 1.59%   |
| Generalplus GENERAL WEBCAM                      | 2        | 1.59%   |
| Cubeternet GL-UPC822 UVC WebCam                 | 2        | 1.59%   |
| Creative VF0610 Live! Cam Socialize HD          | 2        | 1.59%   |
| Arkmicro USB2.0 PC CAMERA                       | 2        | 1.59%   |
| ARC International Camera                        | 2        | 1.59%   |
| Z-Star Venus USB2.0 Camera                      | 1        | 0.79%   |
| Z-Star A4 TECH HD PC Camera                     | 1        | 0.79%   |
| USB3.0 HD Audio Capture USB3.0 HD Video Capture | 1        | 0.79%   |
| Sunplus IT Full HD webcam                       | 1        | 0.79%   |
| Sunplus Live Camera                             | 1        | 0.79%   |
| Sunplus Canyon CNS CWC5 Webcam                  | 1        | 0.79%   |
| Sunplus Aukey-PC-LM1E Camera                    | 1        | 0.79%   |
| Razer USA Razer Kiyo Pro                        | 1        | 0.79%   |
| Razer USA Gaming Webcam [Kiyo]                  | 1        | 0.79%   |
| PrehKeyTec TA-0120-AS                           | 1        | 0.79%   |
| Pixart Imaging USB2.0_Camera                    | 1        | 0.79%   |
| OPPO Reno4 5G                                   | 1        | 0.79%   |
| Nintendo USB Camera                             | 1        | 0.79%   |
| Mimaki Engineering USB 2.0 Camera               | 1        | 0.79%   |
| Microsoft MicrosoftÃ‚ LifeCam HD-5001        | 1        | 0.79%   |
| Microsoft MicrosoftÂ LifeCam Studio            | 1        | 0.79%   |
| Microsoft LifeCam VX-800                        | 1        | 0.79%   |
| Microsoft LifeCam VX-5000                       | 1        | 0.79%   |
| Microdia MSI Starcam Racer                      | 1        | 0.79%   |
| Microdia Laptop_Integrated_Webcam_FHD           | 1        | 0.79%   |
| Microdia Integrated Webcam                      | 1        | 0.79%   |
| Microdia Defender G-Lens 2577 HD720p Camera     | 1        | 0.79%   |
| Logitech Webcam Pro 9000                        | 1        | 0.79%   |
| Logitech Webcam C600                            | 1        | 0.79%   |
| Logitech Webcam C310                            | 1        | 0.79%   |
| Logitech Webcam C300                            | 1        | 0.79%   |
| Logitech Webcam C170                            | 1        | 0.79%   |
| Logitech StreamCam                              | 1        | 0.79%   |
| Logitech QuickCam Pro 5000                      | 1        | 0.79%   |
| Logitech QuickCam Communicate MP/S5500          | 1        | 0.79%   |
| Logitech Portable Webcam C905                   | 1        | 0.79%   |
| Logitech HD Webcam C615                         | 1        | 0.79%   |
| Logitech Acer Camera                            | 1        | 0.79%   |
| Linux Foundation EEM Gadget                     | 1        | 0.79%   |
| KYE Systems (Mouse Systems) FaceCam 1000X       | 1        | 0.79%   |

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


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| OmniKey                   | 2        | 33.33%  |
| Lenovo                    | 1        | 16.67%  |
| Fujitsu Siemens Computers | 1        | 16.67%  |
| Cherry                    | 1        | 16.67%  |
| Alcor Micro               | 1        | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| OmniKey CardMan 3021 / 3121                   | 2        | 33.33%  |
| Lenovo Smartcard Keyboard                     | 1        | 16.67%  |
| Fujitsu Siemens Computers SmartCard Reader 2A | 1        | 16.67%  |
| Cherry SmartTerminal XX44                     | 1        | 16.67%  |
| Alcor Micro AU9540 Smartcard Reader           | 1        | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 652      | 87.87%  |
| 1     | 73       | 9.84%   |
| 2     | 11       | 1.48%   |
| 4     | 3        | 0.4%    |
| 3     | 3        | 0.4%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 33       | 31.13%  |
| Net/wireless             | 26       | 24.53%  |
| Communication controller | 13       | 12.26%  |
| Unassigned class         | 9        | 8.49%   |
| Sound                    | 7        | 6.6%    |
| Chipcard                 | 5        | 4.72%   |
| Multimedia controller    | 4        | 3.77%   |
| Net/ethernet             | 2        | 1.89%   |
| Card reader              | 2        | 1.89%   |
| Camera                   | 2        | 1.89%   |
| Storage/raid             | 1        | 0.94%   |
| Network                  | 1        | 0.94%   |
| Modem                    | 1        | 0.94%   |

