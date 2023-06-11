Linux - Tested Hardware & Statistics (Desktops)
-----------------------------------------------

A project to collect tested hardware configurations for Linux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This report is for real hardware. Report for virtual hardware: [TestDays_VE](https://github.com/linuxhw/TestDays_VE)

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

Total: 125360

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | P35-S3G                     | [71339b40ec](https://linux-hardware.org/?probe=71339b40ec) | Jun 10, 2023 |
| ASUSTek       | F2A85-V PRO                 | [43991c533e](https://linux-hardware.org/?probe=43991c533e) | Jun 10, 2023 |
| Intel         | DP45SG AAE27733-404         | [7abba8629e](https://linux-hardware.org/?probe=7abba8629e) | Jun 10, 2023 |
| Gigabyte      | Z87X-UD4H-CF                | [abd31d2f92](https://linux-hardware.org/?probe=abd31d2f92) | Jun 10, 2023 |
| MSI           | X370 GAMING M7 ACK          | [450b8ab5a7](https://linux-hardware.org/?probe=450b8ab5a7) | Jun 10, 2023 |
| Intel         | DP45SG AAE27733-404         | [afaced265f](https://linux-hardware.org/?probe=afaced265f) | Jun 10, 2023 |
| ASRock        | G41M-VS3                    | [d592b19e9b](https://linux-hardware.org/?probe=d592b19e9b) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [7ab0866235](https://linux-hardware.org/?probe=7ab0866235) | Jun 10, 2023 |
| ASUSTek       | P7H55D-M PRO                | [6049b3d69d](https://linux-hardware.org/?probe=6049b3d69d) | Jun 10, 2023 |
| Intel         | DH55TC AAE70932-302         | [6090a53f8a](https://linux-hardware.org/?probe=6090a53f8a) | Jun 10, 2023 |
| Dell          | 0KC9NP A01                  | [ab5b79d6fd](https://linux-hardware.org/?probe=ab5b79d6fd) | Jun 10, 2023 |
| Lenovo        | 32E9 SDK0T76465 WIN 3422... | [2ac8db1b4c](https://linux-hardware.org/?probe=2ac8db1b4c) | Jun 10, 2023 |
| ASUSTek       | P5B                         | [794635cbea](https://linux-hardware.org/?probe=794635cbea) | Jun 10, 2023 |
| Gigabyte      | H57M-USB3                   | [91b1655f60](https://linux-hardware.org/?probe=91b1655f60) | Jun 10, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [dedc98e84e](https://linux-hardware.org/?probe=dedc98e84e) | Jun 10, 2023 |
| Gigabyte      | 8I865GVMK-775               | [3d90d76b7b](https://linux-hardware.org/?probe=3d90d76b7b) | Jun 10, 2023 |
| HP            | 339A                        | [348ce53f71](https://linux-hardware.org/?probe=348ce53f71) | Jun 10, 2023 |
| HP            | 81B4                        | [2d7748536f](https://linux-hardware.org/?probe=2d7748536f) | Jun 10, 2023 |
| Dell          | 0N4YC8 A00                  | [bc832400b4](https://linux-hardware.org/?probe=bc832400b4) | Jun 10, 2023 |
| Gigabyte      | B650M GAMING X AX           | [5affc12294](https://linux-hardware.org/?probe=5affc12294) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [4cb72d56f7](https://linux-hardware.org/?probe=4cb72d56f7) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [6c8e1de1cf](https://linux-hardware.org/?probe=6c8e1de1cf) | Jun 10, 2023 |
| Gigabyte      | H410M H                     | [dfba5357ee](https://linux-hardware.org/?probe=dfba5357ee) | Jun 10, 2023 |
| ASRock        | B450M Pro4                  | [c23450b0df](https://linux-hardware.org/?probe=c23450b0df) | Jun 10, 2023 |
| Gigabyte      | GA-880GM-D2H                | [2e46385299](https://linux-hardware.org/?probe=2e46385299) | Jun 10, 2023 |
| ASRock        | H61M-DGS R2.0               | [cc206f52b1](https://linux-hardware.org/?probe=cc206f52b1) | Jun 10, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | [63c110632a](https://linux-hardware.org/?probe=63c110632a) | Jun 10, 2023 |
| ASUSTek       | P8H61-M LX                  | [9d9872a84a](https://linux-hardware.org/?probe=9d9872a84a) | Jun 10, 2023 |
| Gigabyte      | GA-MA770-US3                | [704cc1c02b](https://linux-hardware.org/?probe=704cc1c02b) | Jun 10, 2023 |
| MSI           | MS-B9321                    | [a7a878dbe6](https://linux-hardware.org/?probe=a7a878dbe6) | Jun 10, 2023 |
| Gigabyte      | B560M H                     | [fadb7a6aa8](https://linux-hardware.org/?probe=fadb7a6aa8) | Jun 10, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [1f8c419c47](https://linux-hardware.org/?probe=1f8c419c47) | Jun 10, 2023 |
| ASUSTek       | PRIME B460M-K               | [873975925d](https://linux-hardware.org/?probe=873975925d) | Jun 10, 2023 |
| HP            | 2B4B                        | [3ade78a07e](https://linux-hardware.org/?probe=3ade78a07e) | Jun 10, 2023 |
| HP            | 2B4B                        | [2da60252b5](https://linux-hardware.org/?probe=2da60252b5) | Jun 10, 2023 |
| Pegatron      | Benicia                     | [c57fee6ea0](https://linux-hardware.org/?probe=c57fee6ea0) | Jun 10, 2023 |
| HP            | 339A                        | [d1fa07d03f](https://linux-hardware.org/?probe=d1fa07d03f) | Jun 10, 2023 |
| Huanan        | X99 F8D V2.2                | [1eeaac2701](https://linux-hardware.org/?probe=1eeaac2701) | Jun 10, 2023 |
| MSI           | MAG B760 TOMAHAWK WIFI      | [88955e82f2](https://linux-hardware.org/?probe=88955e82f2) | Jun 10, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [0eae3567d9](https://linux-hardware.org/?probe=0eae3567d9) | Jun 10, 2023 |
| MSI           | B450M PRO-VDH MAX           | [4dcc51e897](https://linux-hardware.org/?probe=4dcc51e897) | Jun 10, 2023 |
| ASRock        | B365M Pro4-F                | [e54f1a9447](https://linux-hardware.org/?probe=e54f1a9447) | Jun 10, 2023 |
| Gigabyte      | B450M S2H                   | [82adaa06b7](https://linux-hardware.org/?probe=82adaa06b7) | Jun 10, 2023 |
| MSI           | MS-7309                     | [9c6db3b61d](https://linux-hardware.org/?probe=9c6db3b61d) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [d58405f7c1](https://linux-hardware.org/?probe=d58405f7c1) | Jun 10, 2023 |
| ASRock        | FM2A58M-VG3+ R2.0           | [3e4b7afb1e](https://linux-hardware.org/?probe=3e4b7afb1e) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [08114e8a97](https://linux-hardware.org/?probe=08114e8a97) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [86b377710d](https://linux-hardware.org/?probe=86b377710d) | Jun 10, 2023 |
| Dell          | 0D883F A06                  | [f0d5120461](https://linux-hardware.org/?probe=f0d5120461) | Jun 10, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [dfac11ccad](https://linux-hardware.org/?probe=dfac11ccad) | Jun 10, 2023 |
| ASRock        | B550AM Gaming               | [eca79c3bbb](https://linux-hardware.org/?probe=eca79c3bbb) | Jun 10, 2023 |
| ASRock        | H610M-ITX/ac                | [80002221f5](https://linux-hardware.org/?probe=80002221f5) | Jun 10, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [93555cfd25](https://linux-hardware.org/?probe=93555cfd25) | Jun 10, 2023 |
| Unknown       | Unknown                     | [4c9c3d929b](https://linux-hardware.org/?probe=4c9c3d929b) | Jun 10, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [2e6d82c14f](https://linux-hardware.org/?probe=2e6d82c14f) | Jun 10, 2023 |
| Gigabyte      | B550 GAMING X V2            | [03ef8fea42](https://linux-hardware.org/?probe=03ef8fea42) | Jun 10, 2023 |
| MP            | MS-7848                     | [cd63c98850](https://linux-hardware.org/?probe=cd63c98850) | Jun 10, 2023 |
| Wistron       | ProLiant ML110 G5           | [eea1c44d94](https://linux-hardware.org/?probe=eea1c44d94) | Jun 10, 2023 |
| ASUSTek       | K30BF_M32BF                 | [65b3c16165](https://linux-hardware.org/?probe=65b3c16165) | Jun 10, 2023 |
| ASRockRack    | X470D4U2-2T                 | [8e10de95af](https://linux-hardware.org/?probe=8e10de95af) | Jun 10, 2023 |
| MSI           | MS-7388                     | [6d3a406400](https://linux-hardware.org/?probe=6d3a406400) | Jun 10, 2023 |
| GuoGuang      | IC2M1028V-J                 | [d7c1b01b69](https://linux-hardware.org/?probe=d7c1b01b69) | Jun 10, 2023 |
| ASRock        | X570 Phantom Gaming X       | [0c4db9b922](https://linux-hardware.org/?probe=0c4db9b922) | Jun 10, 2023 |
| Pegatron      | 2A99                        | [0a25cd49a5](https://linux-hardware.org/?probe=0a25cd49a5) | Jun 10, 2023 |
| HP            | 1496                        | [68db57fde8](https://linux-hardware.org/?probe=68db57fde8) | Jun 10, 2023 |
| MSI           | X99A RAIDER                 | [4ab556e4b8](https://linux-hardware.org/?probe=4ab556e4b8) | Jun 10, 2023 |
| ASRock        | FM2A88X Extreme6+           | [212c44c43f](https://linux-hardware.org/?probe=212c44c43f) | Jun 10, 2023 |
| Dell          | 0DWPVW A00                  | [ffad802816](https://linux-hardware.org/?probe=ffad802816) | Jun 10, 2023 |
| HP            | 8949 11                     | [f5e1f4b6c9](https://linux-hardware.org/?probe=f5e1f4b6c9) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [cac24c37e5](https://linux-hardware.org/?probe=cac24c37e5) | Jun 10, 2023 |
| Seco          | C40 C                       | [4d990c8a0c](https://linux-hardware.org/?probe=4d990c8a0c) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [5446a0003e](https://linux-hardware.org/?probe=5446a0003e) | Jun 10, 2023 |
| MSI           | AM1M                        | [42a7d49c03](https://linux-hardware.org/?probe=42a7d49c03) | Jun 10, 2023 |
| ASUSTek       | M5A97 R2.0                  | [d9e9a51e48](https://linux-hardware.org/?probe=d9e9a51e48) | Jun 10, 2023 |
| Acer          | Predator G3600              | [02a0cf3a71](https://linux-hardware.org/?probe=02a0cf3a71) | Jun 10, 2023 |
| Gigabyte      | H81M-H                      | [fc025a599d](https://linux-hardware.org/?probe=fc025a599d) | Jun 10, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | [f04b28a0e5](https://linux-hardware.org/?probe=f04b28a0e5) | Jun 10, 2023 |
| Gigabyte      | H81M-H                      | [f32fbdf6ea](https://linux-hardware.org/?probe=f32fbdf6ea) | Jun 10, 2023 |
| MSI           | B250M PRO-VH                | [16b496c21d](https://linux-hardware.org/?probe=16b496c21d) | Jun 10, 2023 |
| HP            | 0B4Ch D                     | [672a491915](https://linux-hardware.org/?probe=672a491915) | Jun 09, 2023 |
| Intel         | H81                         | [6a51c76e81](https://linux-hardware.org/?probe=6a51c76e81) | Jun 09, 2023 |
| Acer          | Aspire XC600 v1.0           | [754d228b9b](https://linux-hardware.org/?probe=754d228b9b) | Jun 09, 2023 |
| Dell          | 0PU052                      | [84db4b658c](https://linux-hardware.org/?probe=84db4b658c) | Jun 09, 2023 |
| ASUSTek       | P5GC-MX/1333                | [b47fab6285](https://linux-hardware.org/?probe=b47fab6285) | Jun 09, 2023 |
| ASUSTek       | P8H61-M LX                  | [bd22edfae7](https://linux-hardware.org/?probe=bd22edfae7) | Jun 09, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [0e34d2ee28](https://linux-hardware.org/?probe=0e34d2ee28) | Jun 09, 2023 |
| Dell          | 0PU052                      | [145d296b59](https://linux-hardware.org/?probe=145d296b59) | Jun 09, 2023 |
| Dell          | 0WMJ54 A01                  | [a4d08407bb](https://linux-hardware.org/?probe=a4d08407bb) | Jun 09, 2023 |
| ASRock        | B360M Pro4                  | [9b52b20f3e](https://linux-hardware.org/?probe=9b52b20f3e) | Jun 09, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [afa2a30d75](https://linux-hardware.org/?probe=afa2a30d75) | Jun 09, 2023 |
| HP            | 82C9                        | [b696990030](https://linux-hardware.org/?probe=b696990030) | Jun 09, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [a1877cb5b3](https://linux-hardware.org/?probe=a1877cb5b3) | Jun 09, 2023 |
| ASUSTek       | P8P67 LE                    | [212ff65852](https://linux-hardware.org/?probe=212ff65852) | Jun 09, 2023 |
| HP            | 339B                        | [bc6de07e07](https://linux-hardware.org/?probe=bc6de07e07) | Jun 09, 2023 |
| ASRock        | H61M-DGS R2.0               | [37c25e136f](https://linux-hardware.org/?probe=37c25e136f) | Jun 09, 2023 |
| Gigabyte      | B550M DS3H                  | [ea724e204b](https://linux-hardware.org/?probe=ea724e204b) | Jun 09, 2023 |
| Gigabyte      | B460M DS3H                  | [63c9d6c822](https://linux-hardware.org/?probe=63c9d6c822) | Jun 09, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [92fd36b27a](https://linux-hardware.org/?probe=92fd36b27a) | Jun 09, 2023 |
| ASUSTek       | PRIME X370-PRO              | [77145a587d](https://linux-hardware.org/?probe=77145a587d) | Jun 09, 2023 |
| ASUSTek       | ROG ZENITH EXTREME          | [b4de2ccda4](https://linux-hardware.org/?probe=b4de2ccda4) | Jun 09, 2023 |
| MSI           | 970A-G46                    | [e4471b7a38](https://linux-hardware.org/?probe=e4471b7a38) | Jun 09, 2023 |
| Gigabyte      | B450 AORUS M                | [280baa2765](https://linux-hardware.org/?probe=280baa2765) | Jun 09, 2023 |
| Dell          | 0XCR8D A03                  | [e37bceb6fb](https://linux-hardware.org/?probe=e37bceb6fb) | Jun 09, 2023 |
| ASUSTek       | M2N68-AM SE2                | [4f69ba649a](https://linux-hardware.org/?probe=4f69ba649a) | Jun 09, 2023 |
| Lenovo        | ThinkStation E20 422237U    | [2756905647](https://linux-hardware.org/?probe=2756905647) | Jun 09, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [6491127e6e](https://linux-hardware.org/?probe=6491127e6e) | Jun 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [0f42ca8c95](https://linux-hardware.org/?probe=0f42ca8c95) | Jun 09, 2023 |
| Gigabyte      | P67A-D3-B3                  | [142fc47b59](https://linux-hardware.org/?probe=142fc47b59) | Jun 09, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [f9677c0861](https://linux-hardware.org/?probe=f9677c0861) | Jun 09, 2023 |
| ASUSTek       | P8H61-M LX2                 | [3fb94f0c4b](https://linux-hardware.org/?probe=3fb94f0c4b) | Jun 09, 2023 |
| Gigabyte      | P55A-UD3                    | [2c8c27897b](https://linux-hardware.org/?probe=2c8c27897b) | Jun 09, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | [f02bc23dd0](https://linux-hardware.org/?probe=f02bc23dd0) | Jun 09, 2023 |
| Dell          | 07T4MC A02                  | [ad310dd147](https://linux-hardware.org/?probe=ad310dd147) | Jun 09, 2023 |
| ECS           | G31T-M9                     | [d8ca98b733](https://linux-hardware.org/?probe=d8ca98b733) | Jun 09, 2023 |
| ASRock        | AB350M Pro4                 | [8f0087d741](https://linux-hardware.org/?probe=8f0087d741) | Jun 09, 2023 |
| Nvidia        | MCP79                       | [8203509a77](https://linux-hardware.org/?probe=8203509a77) | Jun 09, 2023 |
| Gigabyte      | 970A-DS3P                   | [1bae25f67b](https://linux-hardware.org/?probe=1bae25f67b) | Jun 09, 2023 |
| MSI           | H81I                        | [c7c19346a2](https://linux-hardware.org/?probe=c7c19346a2) | Jun 09, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [cc1f571000](https://linux-hardware.org/?probe=cc1f571000) | Jun 09, 2023 |
| Gigabyte      | G41M-ES2L                   | [22e9021ae3](https://linux-hardware.org/?probe=22e9021ae3) | Jun 09, 2023 |
| MSI           | A520M-A PRO                 | [8a9223ce9f](https://linux-hardware.org/?probe=8a9223ce9f) | Jun 09, 2023 |
| Gigabyte      | B450M S2H V2                | [fb883c82bc](https://linux-hardware.org/?probe=fb883c82bc) | Jun 09, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [b2c39972c2](https://linux-hardware.org/?probe=b2c39972c2) | Jun 09, 2023 |
| Gigabyte      | B450M H                     | [e54b5ce7da](https://linux-hardware.org/?probe=e54b5ce7da) | Jun 09, 2023 |
| Gigabyte      | B550 AORUS PRO              | [61a0a2ea5f](https://linux-hardware.org/?probe=61a0a2ea5f) | Jun 09, 2023 |
| MSI           | Boston                      | [cc58f8cdf3](https://linux-hardware.org/?probe=cc58f8cdf3) | Jun 09, 2023 |
| ASUSTek       | PRIME B450M-A II            | [95bc101c80](https://linux-hardware.org/?probe=95bc101c80) | Jun 09, 2023 |
| Gigabyte      | H61M-DS2                    | [8b8c6949b6](https://linux-hardware.org/?probe=8b8c6949b6) | Jun 09, 2023 |
| HP            | 09E0h                       | [b6bb01441c](https://linux-hardware.org/?probe=b6bb01441c) | Jun 09, 2023 |
| Gigabyte      | B450M GAMING                | [8ab2ec8df4](https://linux-hardware.org/?probe=8ab2ec8df4) | Jun 09, 2023 |
| Dell          | 0YXT71 A00                  | [477afe615b](https://linux-hardware.org/?probe=477afe615b) | Jun 09, 2023 |
| Gigabyte      | Q87M-D2H                    | [56421d7b0f](https://linux-hardware.org/?probe=56421d7b0f) | Jun 09, 2023 |
| Dell          | 0YXT71 A00                  | [463dfa5d83](https://linux-hardware.org/?probe=463dfa5d83) | Jun 09, 2023 |
| Biostar       | A68N-2100K                  | [9ac86a512d](https://linux-hardware.org/?probe=9ac86a512d) | Jun 09, 2023 |
| ASUSTek       | PRIME A520M-A II            | [176b4ca0bb](https://linux-hardware.org/?probe=176b4ca0bb) | Jun 09, 2023 |
| Gigabyte      | B450 AORUS M                | [50b022f065](https://linux-hardware.org/?probe=50b022f065) | Jun 09, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | [5833483fe2](https://linux-hardware.org/?probe=5833483fe2) | Jun 09, 2023 |
| MSI           | 760GM-P23                   | [abc3a3d8a1](https://linux-hardware.org/?probe=abc3a3d8a1) | Jun 09, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | [a597fc235e](https://linux-hardware.org/?probe=a597fc235e) | Jun 09, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | [6a368b8ecc](https://linux-hardware.org/?probe=6a368b8ecc) | Jun 09, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [bcad738da6](https://linux-hardware.org/?probe=bcad738da6) | Jun 09, 2023 |
| MSI           | MAG Z490 TOMAHAWK           | [40f18ae1f4](https://linux-hardware.org/?probe=40f18ae1f4) | Jun 09, 2023 |
| MSI           | B350M MORTAR                | [6e5323aa42](https://linux-hardware.org/?probe=6e5323aa42) | Jun 09, 2023 |
| MSI           | B350M MORTAR                | [fc4b07cbb0](https://linux-hardware.org/?probe=fc4b07cbb0) | Jun 09, 2023 |
| MSI           | 760GM-P23                   | [fc826b3cb1](https://linux-hardware.org/?probe=fc826b3cb1) | Jun 09, 2023 |
| ECS           | H81H3-M4                    | [b457e63434](https://linux-hardware.org/?probe=b457e63434) | Jun 09, 2023 |
| ASUSTek       | P8H61-M LX                  | [28d0a897d3](https://linux-hardware.org/?probe=28d0a897d3) | Jun 09, 2023 |
| Gigabyte      | X570 GAMING X               | [576a624a1b](https://linux-hardware.org/?probe=576a624a1b) | Jun 09, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | [26262445d4](https://linux-hardware.org/?probe=26262445d4) | Jun 09, 2023 |
| ASUSTek       | STRIX B250F GAMING          | [c0fd33b9cc](https://linux-hardware.org/?probe=c0fd33b9cc) | Jun 09, 2023 |
| ASUSTek       | PRIME H410M-E               | [f40a243bba](https://linux-hardware.org/?probe=f40a243bba) | Jun 09, 2023 |
| ASUSTek       | M2N68-AM Plus               | [7411937d5b](https://linux-hardware.org/?probe=7411937d5b) | Jun 09, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | [f4f543eaa6](https://linux-hardware.org/?probe=f4f543eaa6) | Jun 09, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [1189f6696f](https://linux-hardware.org/?probe=1189f6696f) | Jun 09, 2023 |
| ASUSTek       | STRIX B250F GAMING          | [76c3e6625b](https://linux-hardware.org/?probe=76c3e6625b) | Jun 09, 2023 |
| Dell          | 0FDY5C A00                  | [1caf029f79](https://linux-hardware.org/?probe=1caf029f79) | Jun 09, 2023 |
| ASUSTek       | M4A785G-HTPC                | [76304dfb4a](https://linux-hardware.org/?probe=76304dfb4a) | Jun 09, 2023 |
| AZW           | SEi                         | [2b085e7ed2](https://linux-hardware.org/?probe=2b085e7ed2) | Jun 09, 2023 |
| Unknown       | GSUO H61V10C                | [0daf816953](https://linux-hardware.org/?probe=0daf816953) | Jun 09, 2023 |
| HP            | 2B35                        | [5921b94b60](https://linux-hardware.org/?probe=5921b94b60) | Jun 09, 2023 |
| HP            | 3646h                       | [046f5d1a5b](https://linux-hardware.org/?probe=046f5d1a5b) | Jun 09, 2023 |
| ASRock        | A320M-HD                    | [9e88454384](https://linux-hardware.org/?probe=9e88454384) | Jun 09, 2023 |
| Fujitsu       | D2942-B1 S26361-D2942-B1    | [9fb55abc56](https://linux-hardware.org/?probe=9fb55abc56) | Jun 08, 2023 |
| ASUSTek       | PRIME B650M-A WIFI II       | [e68e693394](https://linux-hardware.org/?probe=e68e693394) | Jun 08, 2023 |
| ASUSTek       | PRIME A320M-K               | [2dfd2a0844](https://linux-hardware.org/?probe=2dfd2a0844) | Jun 08, 2023 |
| ASUSTek       | Z97M-PLUS                   | [24f6f6e727](https://linux-hardware.org/?probe=24f6f6e727) | Jun 08, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [8173a6e67f](https://linux-hardware.org/?probe=8173a6e67f) | Jun 08, 2023 |
| HP            | 3397                        | [c754fea198](https://linux-hardware.org/?probe=c754fea198) | Jun 08, 2023 |
| Supermicro    | C7H61                       | [7eef5b7873](https://linux-hardware.org/?probe=7eef5b7873) | Jun 08, 2023 |
| HP            | 18E7                        | [d80810b7f8](https://linux-hardware.org/?probe=d80810b7f8) | Jun 08, 2023 |
| Dell          | 0KRC95 A02                  | [585c31e8d3](https://linux-hardware.org/?probe=585c31e8d3) | Jun 08, 2023 |
| Gigabyte      | G41M-ES2L                   | [a707a562b8](https://linux-hardware.org/?probe=a707a562b8) | Jun 08, 2023 |
| ASRock        | Z690M-ITX/ax                | [f0bad84fca](https://linux-hardware.org/?probe=f0bad84fca) | Jun 08, 2023 |
| MSI           | H110M PRO-D                 | [ad5baed526](https://linux-hardware.org/?probe=ad5baed526) | Jun 08, 2023 |
| ASUSTek       | Z97M-PLUS                   | [8d4e2bedde](https://linux-hardware.org/?probe=8d4e2bedde) | Jun 08, 2023 |
| Supermicro    | X10DRG-Q                    | [c03c5ea1b9](https://linux-hardware.org/?probe=c03c5ea1b9) | Jun 08, 2023 |
| HP            | 18EA                        | [d6e48a99e7](https://linux-hardware.org/?probe=d6e48a99e7) | Jun 08, 2023 |
| ASRock        | H81M-HDS                    | [e1ff6f4e2f](https://linux-hardware.org/?probe=e1ff6f4e2f) | Jun 08, 2023 |
| Dell          | 0K83V0 A00                  | [fc7fa0850a](https://linux-hardware.org/?probe=fc7fa0850a) | Jun 08, 2023 |
| Gigabyte      | H61M-S1                     | [3063c26aca](https://linux-hardware.org/?probe=3063c26aca) | Jun 08, 2023 |
| Gigabyte      | H81M-S2H                    | [fc60082dfe](https://linux-hardware.org/?probe=fc60082dfe) | Jun 08, 2023 |
| Gigabyte      | X570 UD                     | [98a10d2fd9](https://linux-hardware.org/?probe=98a10d2fd9) | Jun 08, 2023 |
| ASUSTek       | Maximus VI HERO             | [5861bc7cef](https://linux-hardware.org/?probe=5861bc7cef) | Jun 08, 2023 |
| ASRock        | X670E Pro RS                | [9770971a47](https://linux-hardware.org/?probe=9770971a47) | Jun 08, 2023 |
| Gigabyte      | B75M-D3H                    | [8c84a543bf](https://linux-hardware.org/?probe=8c84a543bf) | Jun 08, 2023 |
| Colorful T... | A520M-K PRO V14             | [48c4aa3d8c](https://linux-hardware.org/?probe=48c4aa3d8c) | Jun 08, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [b9e1c5e320](https://linux-hardware.org/?probe=b9e1c5e320) | Jun 08, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [bf2fc7d3b7](https://linux-hardware.org/?probe=bf2fc7d3b7) | Jun 08, 2023 |
| Gigabyte      | Z97M-DS3H                   | [5d8df77ade](https://linux-hardware.org/?probe=5d8df77ade) | Jun 08, 2023 |
| ASUSTek       | PRIME B350M-A               | [ba4bfc1fe1](https://linux-hardware.org/?probe=ba4bfc1fe1) | Jun 08, 2023 |
| ASUSTek       | H81M-R                      | [10d01671ad](https://linux-hardware.org/?probe=10d01671ad) | Jun 08, 2023 |
| Biostar       | H610MH                      | [a2c82f65b6](https://linux-hardware.org/?probe=a2c82f65b6) | Jun 08, 2023 |
| Dell          | 0GY6Y8 A02                  | [65f988a0c3](https://linux-hardware.org/?probe=65f988a0c3) | Jun 08, 2023 |
| Gigabyte      | H81M-S2H                    | [5533070ec1](https://linux-hardware.org/?probe=5533070ec1) | Jun 08, 2023 |
| ASRock        | B450 Steel Legend           | [483ac7223f](https://linux-hardware.org/?probe=483ac7223f) | Jun 08, 2023 |
| HJS           | OPSH110D4                   | [bfb0ead991](https://linux-hardware.org/?probe=bfb0ead991) | Jun 08, 2023 |
| MSI           | X470 GAMING PLUS            | [eea4cea0e0](https://linux-hardware.org/?probe=eea4cea0e0) | Jun 08, 2023 |
| AZW           | GK mini                     | [d9d37cb11a](https://linux-hardware.org/?probe=d9d37cb11a) | Jun 08, 2023 |
| MSI           | A55M-E35                    | [7800efb785](https://linux-hardware.org/?probe=7800efb785) | Jun 08, 2023 |
| AZW           | SEi                         | [399b4a7add](https://linux-hardware.org/?probe=399b4a7add) | Jun 08, 2023 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | [9de320e96f](https://linux-hardware.org/?probe=9de320e96f) | Jun 08, 2023 |
| ASRock        | Z270 Gaming K6              | [31a7447d8b](https://linux-hardware.org/?probe=31a7447d8b) | Jun 08, 2023 |
| Gigabyte      | H61M-DS2                    | [829912d683](https://linux-hardware.org/?probe=829912d683) | Jun 08, 2023 |
| ASRock        | Z270 Gaming K6              | [267154b0d2](https://linux-hardware.org/?probe=267154b0d2) | Jun 08, 2023 |
| Dell          | 0GDG8Y A00                  | [4789561d79](https://linux-hardware.org/?probe=4789561d79) | Jun 08, 2023 |
| Inventec      | VXC Class A02               | [c2bc26120f](https://linux-hardware.org/?probe=c2bc26120f) | Jun 08, 2023 |
| MSI           | A55M-E35                    | [fa4eba3787](https://linux-hardware.org/?probe=fa4eba3787) | Jun 08, 2023 |
| Dell          | 088DT1 A01                  | [173e9a0e0c](https://linux-hardware.org/?probe=173e9a0e0c) | Jun 08, 2023 |
| MSI           | B450M PRO-VDH MAX           | [c96be9f4cd](https://linux-hardware.org/?probe=c96be9f4cd) | Jun 08, 2023 |
| ASUSTek       | M4A78T-E                    | [fa22309a62](https://linux-hardware.org/?probe=fa22309a62) | Jun 08, 2023 |
| MSI           | Z87-G43                     | [554f8ea405](https://linux-hardware.org/?probe=554f8ea405) | Jun 08, 2023 |
| Gigabyte      | H61M-DS2                    | [f995c68d61](https://linux-hardware.org/?probe=f995c68d61) | Jun 08, 2023 |
| Biostar       | H610MH                      | [2cd4e157d4](https://linux-hardware.org/?probe=2cd4e157d4) | Jun 08, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [35c7fcb130](https://linux-hardware.org/?probe=35c7fcb130) | Jun 08, 2023 |
| Gigabyte      | Z170X-Gaming 6              | [21eaab076a](https://linux-hardware.org/?probe=21eaab076a) | Jun 08, 2023 |
| Unknown       | Unknown                     | [2c3b00b1ae](https://linux-hardware.org/?probe=2c3b00b1ae) | Jun 08, 2023 |
| MSI           | X58M                        | [7f0ef36058](https://linux-hardware.org/?probe=7f0ef36058) | Jun 08, 2023 |
| MSI           | B450M-A PRO MAX             | [230465c003](https://linux-hardware.org/?probe=230465c003) | Jun 08, 2023 |
| ASRock        | H81M-VG4                    | [04d84e44a5](https://linux-hardware.org/?probe=04d84e44a5) | Jun 08, 2023 |
| ASUSTek       | P5B                         | [32baec6c0f](https://linux-hardware.org/?probe=32baec6c0f) | Jun 08, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [f4e1a7a712](https://linux-hardware.org/?probe=f4e1a7a712) | Jun 08, 2023 |
| MSI           | H510M-A PRO                 | [86dfe28c7a](https://linux-hardware.org/?probe=86dfe28c7a) | Jun 08, 2023 |
| HP            | 1494                        | [7e431c0351](https://linux-hardware.org/?probe=7e431c0351) | Jun 08, 2023 |
| Gigabyte      | F2A88XM-D3H                 | [610c9c318f](https://linux-hardware.org/?probe=610c9c318f) | Jun 08, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [744c44deca](https://linux-hardware.org/?probe=744c44deca) | Jun 08, 2023 |
| AZW           | Green G4 10                 | [326b499893](https://linux-hardware.org/?probe=326b499893) | Jun 08, 2023 |
| Gigabyte      | B75M-D3H                    | [65e06561cf](https://linux-hardware.org/?probe=65e06561cf) | Jun 08, 2023 |
| Gigabyte      | X99-UD4-CF                  | [a2c63b86b0](https://linux-hardware.org/?probe=a2c63b86b0) | Jun 08, 2023 |
| Lenovo        | 317C SDK0J40700 WIN 3258... | [d5d7ffe9df](https://linux-hardware.org/?probe=d5d7ffe9df) | Jun 08, 2023 |
| Gigabyte      | GA-A75M-D2H                 | [f78a07f792](https://linux-hardware.org/?probe=f78a07f792) | Jun 08, 2023 |
| Gigabyte      | Z77MX-D3H                   | [e1fdfde650](https://linux-hardware.org/?probe=e1fdfde650) | Jun 08, 2023 |
| HPE           | ProLiant MicroServer Gen... | [e95900bc0c](https://linux-hardware.org/?probe=e95900bc0c) | Jun 08, 2023 |
| Gigabyte      | M68M-S2P                    | [ee2b6b0279](https://linux-hardware.org/?probe=ee2b6b0279) | Jun 08, 2023 |
| BESSTAR Te... | UM700                       | [92645b42ac](https://linux-hardware.org/?probe=92645b42ac) | Jun 08, 2023 |
| Gigabyte      | A520M H                     | [302bb0628a](https://linux-hardware.org/?probe=302bb0628a) | Jun 08, 2023 |
| GuoGuang      | IC2M1028V-J                 | [04527d6ad9](https://linux-hardware.org/?probe=04527d6ad9) | Jun 08, 2023 |
| ASUSTek       | PRIME X570-P                | [a91f24af7a](https://linux-hardware.org/?probe=a91f24af7a) | Jun 08, 2023 |
| ASUSTek       | PRIME X570-P                | [96e1e7ea7e](https://linux-hardware.org/?probe=96e1e7ea7e) | Jun 08, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [a8724dfd68](https://linux-hardware.org/?probe=a8724dfd68) | Jun 08, 2023 |
| Dell          | 0HN7XN A01                  | [c44abee9e7](https://linux-hardware.org/?probe=c44abee9e7) | Jun 08, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [cc54139aa6](https://linux-hardware.org/?probe=cc54139aa6) | Jun 08, 2023 |
| MSI           | PRO B550M-VC WIFI           | [ac442da472](https://linux-hardware.org/?probe=ac442da472) | Jun 08, 2023 |
| MSI           | PRO B550M-VC WIFI           | [70c409a2b8](https://linux-hardware.org/?probe=70c409a2b8) | Jun 08, 2023 |
| Shenzhen M... | F7BFD                       | [74cf1d0b63](https://linux-hardware.org/?probe=74cf1d0b63) | Jun 08, 2023 |
| Shenzhen M... | F7BFD                       | [88cbeea389](https://linux-hardware.org/?probe=88cbeea389) | Jun 08, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | [ddefeff960](https://linux-hardware.org/?probe=ddefeff960) | Jun 08, 2023 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [74f55613b5](https://linux-hardware.org/?probe=74f55613b5) | Jun 08, 2023 |
| Lenovo        | ThinkServer TS140           | [e9ca405eff](https://linux-hardware.org/?probe=e9ca405eff) | Jun 08, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [20d28155d8](https://linux-hardware.org/?probe=20d28155d8) | Jun 08, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [517cbd7f48](https://linux-hardware.org/?probe=517cbd7f48) | Jun 08, 2023 |
| ASRock        | M3A770DE                    | [aa9ddf538e](https://linux-hardware.org/?probe=aa9ddf538e) | Jun 08, 2023 |
| Techvision    | TVI7309X B0                 | [57b238a5ff](https://linux-hardware.org/?probe=57b238a5ff) | Jun 08, 2023 |
| ASRock        | A320M-DVS R4.0              | [aaf59358b7](https://linux-hardware.org/?probe=aaf59358b7) | Jun 07, 2023 |
| Gigabyte      | H610M H DDR4                | [e7cdd7e89b](https://linux-hardware.org/?probe=e7cdd7e89b) | Jun 07, 2023 |
| ASRock        | B85M-HDS                    | [e563fa3fe2](https://linux-hardware.org/?probe=e563fa3fe2) | Jun 07, 2023 |
| AMI           | Cherry Trail CR             | [5816e6a1cf](https://linux-hardware.org/?probe=5816e6a1cf) | Jun 07, 2023 |
| ASUSTek       | H110M-A                     | [a9ca37ac88](https://linux-hardware.org/?probe=a9ca37ac88) | Jun 07, 2023 |
| ASUSTek       | P8Z77-V LE PLUS             | [45cc99775f](https://linux-hardware.org/?probe=45cc99775f) | Jun 07, 2023 |
| ASUSTek       | WS Z390 PRO                 | [7346eaf346](https://linux-hardware.org/?probe=7346eaf346) | Jun 07, 2023 |
| HP            | 3033h                       | [86a8a0bf1a](https://linux-hardware.org/?probe=86a8a0bf1a) | Jun 07, 2023 |
| Gigabyte      | GA-880GM-D2H                | [328aaf23c9](https://linux-hardware.org/?probe=328aaf23c9) | Jun 07, 2023 |
| Gigabyte      | Z390 GAMING SLI-CF          | [5f0e8ab63a](https://linux-hardware.org/?probe=5f0e8ab63a) | Jun 07, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [2ad7aefc45](https://linux-hardware.org/?probe=2ad7aefc45) | Jun 07, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [87f789c059](https://linux-hardware.org/?probe=87f789c059) | Jun 07, 2023 |
| Gigabyte      | Z87X-UD5H-CF                | [fd156e669f](https://linux-hardware.org/?probe=fd156e669f) | Jun 07, 2023 |
| MSI           | P67A-C45                    | [673f3774bc](https://linux-hardware.org/?probe=673f3774bc) | Jun 07, 2023 |
| AZW           | EQ                          | [98e574abed](https://linux-hardware.org/?probe=98e574abed) | Jun 07, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [1d84d556bf](https://linux-hardware.org/?probe=1d84d556bf) | Jun 07, 2023 |
| Unknown       | Unknown                     | [b2c6247a0e](https://linux-hardware.org/?probe=b2c6247a0e) | Jun 07, 2023 |
| Apple         | Mac-F4208DC8 PVT            | [1b2b9fd7f2](https://linux-hardware.org/?probe=1b2b9fd7f2) | Jun 07, 2023 |
| ASUSTek       | NARRA2                      | [e33a2ba9dc](https://linux-hardware.org/?probe=e33a2ba9dc) | Jun 07, 2023 |
| Fujitsu Si... | MS-7504VP-PV                | [3c89a2a6a2](https://linux-hardware.org/?probe=3c89a2a6a2) | Jun 07, 2023 |
| ASUSTek       | NARRA2                      | [e05fc7beed](https://linux-hardware.org/?probe=e05fc7beed) | Jun 07, 2023 |
| MSI           | A88XM-E35                   | [efe1285363](https://linux-hardware.org/?probe=efe1285363) | Jun 07, 2023 |
| HP            | 1905                        | [0617f4e698](https://linux-hardware.org/?probe=0617f4e698) | Jun 07, 2023 |
| Lenovo        | SHARKBAY NOK                | [cf560e91e7](https://linux-hardware.org/?probe=cf560e91e7) | Jun 07, 2023 |
| Gigabyte      | 970A-DS3P                   | [540fc1c58d](https://linux-hardware.org/?probe=540fc1c58d) | Jun 07, 2023 |
| Gigabyte      | B85M-D3H                    | [befd126f43](https://linux-hardware.org/?probe=befd126f43) | Jun 07, 2023 |
| ASUSTek       | STRIX Z270I GAMING          | [f836a7d0ff](https://linux-hardware.org/?probe=f836a7d0ff) | Jun 07, 2023 |
| Gigabyte      | B85M-D3H                    | [e146923f12](https://linux-hardware.org/?probe=e146923f12) | Jun 07, 2023 |
| ASUSTek       | M5A97 R2.0                  | [369f5d3044](https://linux-hardware.org/?probe=369f5d3044) | Jun 07, 2023 |
| Gigabyte      | GA-MA770-US3                | [c22850601d](https://linux-hardware.org/?probe=c22850601d) | Jun 07, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [73bc5d84c9](https://linux-hardware.org/?probe=73bc5d84c9) | Jun 07, 2023 |
| HP            | 8169                        | [45543e5040](https://linux-hardware.org/?probe=45543e5040) | Jun 07, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [96256dca48](https://linux-hardware.org/?probe=96256dca48) | Jun 07, 2023 |
| HP            | 8350                        | [113be26d4c](https://linux-hardware.org/?probe=113be26d4c) | Jun 07, 2023 |
| ASUSTek       | B85M-E                      | [9ea0a82205](https://linux-hardware.org/?probe=9ea0a82205) | Jun 07, 2023 |
| HP            | 339B                        | [a1739aa36b](https://linux-hardware.org/?probe=a1739aa36b) | Jun 07, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [933978a1ae](https://linux-hardware.org/?probe=933978a1ae) | Jun 07, 2023 |
| HP            | 3397                        | [d86a6fc258](https://linux-hardware.org/?probe=d86a6fc258) | Jun 07, 2023 |
| ASUSTek       | PRIME B360-PLUS             | [8b82994313](https://linux-hardware.org/?probe=8b82994313) | Jun 07, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [276844abe2](https://linux-hardware.org/?probe=276844abe2) | Jun 07, 2023 |
| HP            | 2B36                        | [45ee697eed](https://linux-hardware.org/?probe=45ee697eed) | Jun 07, 2023 |
| HP            | 2B36                        | [0f36ecaa7e](https://linux-hardware.org/?probe=0f36ecaa7e) | Jun 07, 2023 |
| ASRock        | B365M Pro4-F                | [7ed0f0346c](https://linux-hardware.org/?probe=7ed0f0346c) | Jun 07, 2023 |
| Gigabyte      | Z270N-WIFI-CF               | [26be42ecb8](https://linux-hardware.org/?probe=26be42ecb8) | Jun 07, 2023 |
| Dell          | 0G9322                      | [e81a7f788a](https://linux-hardware.org/?probe=e81a7f788a) | Jun 07, 2023 |
| Gigabyte      | H77N-WIFI                   | [1c8078b748](https://linux-hardware.org/?probe=1c8078b748) | Jun 07, 2023 |
| ECS           | GF8100VM-M5                 | [6aa065057f](https://linux-hardware.org/?probe=6aa065057f) | Jun 07, 2023 |
| Kraftway      | KWH510                      | [3a5ccb373b](https://linux-hardware.org/?probe=3a5ccb373b) | Jun 07, 2023 |
| ASUSTek       | H97M-E                      | [97140e9688](https://linux-hardware.org/?probe=97140e9688) | Jun 07, 2023 |
| HP            | 3396                        | [ca540b449f](https://linux-hardware.org/?probe=ca540b449f) | Jun 07, 2023 |
| Lenovo        | 1036 SDK0K17763 WIN 1801... | [1d36e85f27](https://linux-hardware.org/?probe=1d36e85f27) | Jun 07, 2023 |
| HP            | 1494                        | [0f032c101b](https://linux-hardware.org/?probe=0f032c101b) | Jun 07, 2023 |
| HP            | 2B34                        | [d0b5c9767f](https://linux-hardware.org/?probe=d0b5c9767f) | Jun 07, 2023 |
| Gigabyte      | X670 GAMING X AX            | [05d49007a4](https://linux-hardware.org/?probe=05d49007a4) | Jun 07, 2023 |
| Gigabyte      | B250M-D3H-CF                | [14016f0f6f](https://linux-hardware.org/?probe=14016f0f6f) | Jun 07, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [12736be80e](https://linux-hardware.org/?probe=12736be80e) | Jun 07, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [793b86c807](https://linux-hardware.org/?probe=793b86c807) | Jun 07, 2023 |
| Gigabyte      | Z270N-WIFI-CF               | [6ba5aae544](https://linux-hardware.org/?probe=6ba5aae544) | Jun 07, 2023 |
| Gigabyte      | B550 VISION D               | [94cf7f5675](https://linux-hardware.org/?probe=94cf7f5675) | Jun 07, 2023 |
| System76      | Thelio Mira thelio-mira-... | [d7d155d89d](https://linux-hardware.org/?probe=d7d155d89d) | Jun 07, 2023 |
| ASUSTek       | PRIME B550M-K               | [e45ed702a4](https://linux-hardware.org/?probe=e45ed702a4) | Jun 07, 2023 |
| MSI           | MS-7513                     | [ed69341f3c](https://linux-hardware.org/?probe=ed69341f3c) | Jun 07, 2023 |
| DIEBOLD       | B85H3-M5                    | [7e56b1fd68](https://linux-hardware.org/?probe=7e56b1fd68) | Jun 07, 2023 |
| MSI           | MPG B650I EDGE WIFI         | [d43ce99616](https://linux-hardware.org/?probe=d43ce99616) | Jun 07, 2023 |
| HP            | 0A60h                       | [f0498c1a54](https://linux-hardware.org/?probe=f0498c1a54) | Jun 07, 2023 |
| Lenovo        | ThinkCentre A58e 0841B4Y    | [fe410cd5db](https://linux-hardware.org/?probe=fe410cd5db) | Jun 07, 2023 |
| Lenovo        | 3704 SDK0J40700 WIN 3258... | [b18ffc5311](https://linux-hardware.org/?probe=b18ffc5311) | Jun 07, 2023 |
| ASUSTek       | PRIME H610M-E D4            | [827f6ecac2](https://linux-hardware.org/?probe=827f6ecac2) | Jun 07, 2023 |
| Dell          | 0R6PCT A01                  | [e1623fbc8e](https://linux-hardware.org/?probe=e1623fbc8e) | Jun 07, 2023 |
| ASUSTek       | X99-DELUXE II               | [aab84214f1](https://linux-hardware.org/?probe=aab84214f1) | Jun 06, 2023 |
| MSI           | B350M GAMING PRO            | [eb3fbddd2c](https://linux-hardware.org/?probe=eb3fbddd2c) | Jun 06, 2023 |
| ASUSTek       | PRIME Z690M-PLUS D4         | [468f6fe603](https://linux-hardware.org/?probe=468f6fe603) | Jun 06, 2023 |
| Foxconn       | H55M-S                      | [83b86844c0](https://linux-hardware.org/?probe=83b86844c0) | Jun 06, 2023 |
| Gigabyte      | B250-FinTech-CF             | [022138ad16](https://linux-hardware.org/?probe=022138ad16) | Jun 06, 2023 |
| ASRock        | Z790 Taichi Carrara         | [bdea2092aa](https://linux-hardware.org/?probe=bdea2092aa) | Jun 06, 2023 |
| Lenovo        | Kabini CRB 31900058 STD     | [8f3282c700](https://linux-hardware.org/?probe=8f3282c700) | Jun 06, 2023 |
| HP            | 822A                        | [8cf8694f03](https://linux-hardware.org/?probe=8cf8694f03) | Jun 06, 2023 |
| Dell          | 06D7TR A01                  | [8db1a8c132](https://linux-hardware.org/?probe=8db1a8c132) | Jun 06, 2023 |
| Gigabyte      | H67MA-USB3-B3               | [c2f52c637b](https://linux-hardware.org/?probe=c2f52c637b) | Jun 06, 2023 |
| MSI           | B550M-A PRO                 | [5fb7d63e80](https://linux-hardware.org/?probe=5fb7d63e80) | Jun 06, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [bc00b26e0a](https://linux-hardware.org/?probe=bc00b26e0a) | Jun 06, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [ee25039289](https://linux-hardware.org/?probe=ee25039289) | Jun 06, 2023 |
| HP            | 3646h                       | [02353b5e9f](https://linux-hardware.org/?probe=02353b5e9f) | Jun 06, 2023 |
| MSI           | B85-G43 GAMING              | [326a620bbd](https://linux-hardware.org/?probe=326a620bbd) | Jun 06, 2023 |
| ASRock        | B450M Steel Legend          | [5d75bba35e](https://linux-hardware.org/?probe=5d75bba35e) | Jun 06, 2023 |
| ASRock        | H310M-HG4                   | [47b2817d31](https://linux-hardware.org/?probe=47b2817d31) | Jun 06, 2023 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | [bcb9105121](https://linux-hardware.org/?probe=bcb9105121) | Jun 06, 2023 |
| Gigabyte      | Z68P-DS3                    | [3371099509](https://linux-hardware.org/?probe=3371099509) | Jun 06, 2023 |
| Gigabyte      | M68MT-S2                    | [2ff7b71aed](https://linux-hardware.org/?probe=2ff7b71aed) | Jun 06, 2023 |
| Dell          | 0427JK A00                  | [addb15771e](https://linux-hardware.org/?probe=addb15771e) | Jun 06, 2023 |
| HP            | 8643 SMVB                   | [0fd8af3392](https://linux-hardware.org/?probe=0fd8af3392) | Jun 06, 2023 |
| Lenovo        | 317C SDK0J40700 WIN 3258... | [23b41d16db](https://linux-hardware.org/?probe=23b41d16db) | Jun 06, 2023 |
| HP            | 8617                        | [7f5df3475c](https://linux-hardware.org/?probe=7f5df3475c) | Jun 06, 2023 |
| ASUSTek       | PRIME B550M-A               | [e7c8a1c727](https://linux-hardware.org/?probe=e7c8a1c727) | Jun 06, 2023 |
| MSI           | B85-G43 GAMING              | [9cfd61dae7](https://linux-hardware.org/?probe=9cfd61dae7) | Jun 06, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [624a84a2fc](https://linux-hardware.org/?probe=624a84a2fc) | Jun 06, 2023 |
| Dell          | 0NW6H5 A00                  | [631e6bba84](https://linux-hardware.org/?probe=631e6bba84) | Jun 06, 2023 |
| Intel         | E5 V1.0                     | [077c08c2dc](https://linux-hardware.org/?probe=077c08c2dc) | Jun 06, 2023 |
| ASRock        | G41C-GS R2.0                | [6e4835c7bc](https://linux-hardware.org/?probe=6e4835c7bc) | Jun 06, 2023 |
| HP            | 8053                        | [29a84ce224](https://linux-hardware.org/?probe=29a84ce224) | Jun 06, 2023 |
| Gigabyte      | Z390 UD                     | [1bf88bda62](https://linux-hardware.org/?probe=1bf88bda62) | Jun 06, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [db42ab94ee](https://linux-hardware.org/?probe=db42ab94ee) | Jun 06, 2023 |
| HP            | 2820h                       | [eb7322ad95](https://linux-hardware.org/?probe=eb7322ad95) | Jun 06, 2023 |
| Nvidia        | MCP79                       | [bf109ed28f](https://linux-hardware.org/?probe=bf109ed28f) | Jun 06, 2023 |
| Dell          | 06X1TJ A00                  | [c3f02841f4](https://linux-hardware.org/?probe=c3f02841f4) | Jun 06, 2023 |
| Gigabyte      | H61M-DS2                    | [10ecbb2117](https://linux-hardware.org/?probe=10ecbb2117) | Jun 06, 2023 |
| Win elemen... | M600                        | [360ab80d9b](https://linux-hardware.org/?probe=360ab80d9b) | Jun 06, 2023 |
| Gigabyte      | H61M-S2PV                   | [a34c3550be](https://linux-hardware.org/?probe=a34c3550be) | Jun 06, 2023 |
| Dell          | 06X1TJ A00                  | [4cec4f0517](https://linux-hardware.org/?probe=4cec4f0517) | Jun 06, 2023 |
| ASUSTek       | PRIME H410I-PLUS            | [83988ad739](https://linux-hardware.org/?probe=83988ad739) | Jun 06, 2023 |
| Chuwi         | RZBOX                       | [f395c0f429](https://linux-hardware.org/?probe=f395c0f429) | Jun 06, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [ae164f9998](https://linux-hardware.org/?probe=ae164f9998) | Jun 06, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [6ae325ff9d](https://linux-hardware.org/?probe=6ae325ff9d) | Jun 06, 2023 |
| HP            | 3397                        | [f85e642ee3](https://linux-hardware.org/?probe=f85e642ee3) | Jun 06, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [77e1fa9533](https://linux-hardware.org/?probe=77e1fa9533) | Jun 06, 2023 |
| Gigabyte      | H310M M.2 x.x               | [602e1c8875](https://linux-hardware.org/?probe=602e1c8875) | Jun 06, 2023 |
| Gigabyte      | Q87M-D2H                    | [05a3b3210a](https://linux-hardware.org/?probe=05a3b3210a) | Jun 06, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [c33bc572fd](https://linux-hardware.org/?probe=c33bc572fd) | Jun 06, 2023 |
| HP            | 83E1                        | [227e410c6f](https://linux-hardware.org/?probe=227e410c6f) | Jun 06, 2023 |
| Lenovo        | 30D0 NOK                    | [045b011b7a](https://linux-hardware.org/?probe=045b011b7a) | Jun 06, 2023 |
| MSI           | 2AE0                        | [15b3c478d3](https://linux-hardware.org/?probe=15b3c478d3) | Jun 06, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [79f63dcf8e](https://linux-hardware.org/?probe=79f63dcf8e) | Jun 06, 2023 |
| ASUSTek       | PRIME B365M-A               | [c33a9e5ccb](https://linux-hardware.org/?probe=c33a9e5ccb) | Jun 06, 2023 |
| ASUSTek       | PRIME H370M-PLUS            | [bbbe24d6b6](https://linux-hardware.org/?probe=bbbe24d6b6) | Jun 06, 2023 |
| ASRockRack    | X470D4U2-2T                 | [9c282e76a6](https://linux-hardware.org/?probe=9c282e76a6) | Jun 06, 2023 |
| Gigabyte      | F2A88XM-D3H                 | [6640281a3b](https://linux-hardware.org/?probe=6640281a3b) | Jun 06, 2023 |
| MSI           | X99A RAIDER                 | [d70fe31101](https://linux-hardware.org/?probe=d70fe31101) | Jun 06, 2023 |
| ASRock        | FM2A88X Extreme6+           | [3c3708dcec](https://linux-hardware.org/?probe=3c3708dcec) | Jun 06, 2023 |
| ASUSTek       | M3A78-CM                    | [50304f8088](https://linux-hardware.org/?probe=50304f8088) | Jun 06, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | [77fe6db865](https://linux-hardware.org/?probe=77fe6db865) | Jun 06, 2023 |
| Gigabyte      | B560M AORUS ELITE           | [f06cb8954c](https://linux-hardware.org/?probe=f06cb8954c) | Jun 06, 2023 |
| Acer          | EQ45LM                      | [73f7a3078f](https://linux-hardware.org/?probe=73f7a3078f) | Jun 06, 2023 |
| Intel         | DP55WB AAE64798-204         | [fe09edbecc](https://linux-hardware.org/?probe=fe09edbecc) | Jun 06, 2023 |
| Acer          | WMCP78M                     | [a7a466de8a](https://linux-hardware.org/?probe=a7a466de8a) | Jun 06, 2023 |
| Gigabyte      | Z590 VISION G               | [ee1abb360e](https://linux-hardware.org/?probe=ee1abb360e) | Jun 06, 2023 |
| ASUSTek       | TUF Z370-PLUS GAMING        | [6cd3cfcacf](https://linux-hardware.org/?probe=6cd3cfcacf) | Jun 06, 2023 |
| Unknown       | Unknown                     | [e8df83921f](https://linux-hardware.org/?probe=e8df83921f) | Jun 06, 2023 |
| HP            | 8918                        | [917b8c425f](https://linux-hardware.org/?probe=917b8c425f) | Jun 06, 2023 |
| Dell          | 0RY007                      | [49c7cbbfde](https://linux-hardware.org/?probe=49c7cbbfde) | Jun 06, 2023 |
| ASUSTek       | PRIME Z790-A WIFI           | [fe852e8a1d](https://linux-hardware.org/?probe=fe852e8a1d) | Jun 06, 2023 |
| HP            | 8918                        | [6f94c9caa9](https://linux-hardware.org/?probe=6f94c9caa9) | Jun 06, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [d981de6f45](https://linux-hardware.org/?probe=d981de6f45) | Jun 06, 2023 |
| Pegatron      | H81-M1                      | [2641e6773e](https://linux-hardware.org/?probe=2641e6773e) | Jun 05, 2023 |
| Dell          | 0Y2K8N A01                  | [13a93fdc21](https://linux-hardware.org/?probe=13a93fdc21) | Jun 05, 2023 |
| ASRock        | X370 Gaming X               | [558e181232](https://linux-hardware.org/?probe=558e181232) | Jun 05, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [d288737b23](https://linux-hardware.org/?probe=d288737b23) | Jun 05, 2023 |
| ASUSTek       | M5A78L-M LE/USB3            | [1bd1a651bb](https://linux-hardware.org/?probe=1bd1a651bb) | Jun 05, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [fa3bffbe76](https://linux-hardware.org/?probe=fa3bffbe76) | Jun 05, 2023 |
| HP            | 339A                        | [f2147ed11b](https://linux-hardware.org/?probe=f2147ed11b) | Jun 05, 2023 |
| HP            | 8265                        | [7afc259b97](https://linux-hardware.org/?probe=7afc259b97) | Jun 05, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [9286154198](https://linux-hardware.org/?probe=9286154198) | Jun 05, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [0b48c563e5](https://linux-hardware.org/?probe=0b48c563e5) | Jun 05, 2023 |
| ASUSTek       | M5A88-M                     | [bb29b433c0](https://linux-hardware.org/?probe=bb29b433c0) | Jun 05, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [6f1c2a6a61](https://linux-hardware.org/?probe=6f1c2a6a61) | Jun 05, 2023 |
| ASUSTek       | M3A78-CM                    | [1df787c227](https://linux-hardware.org/?probe=1df787c227) | Jun 05, 2023 |
| ASUSTek       | CM1730,CM1830               | [2cc76d0cd9](https://linux-hardware.org/?probe=2cc76d0cd9) | Jun 05, 2023 |
| MSI           | H110M ECO                   | [4215fc5993](https://linux-hardware.org/?probe=4215fc5993) | Jun 05, 2023 |
| ASUSTek       | PRIME B550M-A AC            | [de614b2bc7](https://linux-hardware.org/?probe=de614b2bc7) | Jun 05, 2023 |
| HP            | 1495                        | [32cfd162b8](https://linux-hardware.org/?probe=32cfd162b8) | Jun 05, 2023 |
| ASUSTek       | PRIME Z370-P II             | [5a66eed08e](https://linux-hardware.org/?probe=5a66eed08e) | Jun 05, 2023 |
| ASUSTek       | CM1730,CM1830               | [7dc46d923e](https://linux-hardware.org/?probe=7dc46d923e) | Jun 05, 2023 |
| Gigabyte      | B550M DS3H                  | [4895fe7746](https://linux-hardware.org/?probe=4895fe7746) | Jun 05, 2023 |
| HP            | 1495                        | [f6c9f689ec](https://linux-hardware.org/?probe=f6c9f689ec) | Jun 05, 2023 |
| Unknown       | X79                         | [8c1de0f494](https://linux-hardware.org/?probe=8c1de0f494) | Jun 05, 2023 |
| MSI           | B360M PRO-VH                | [8d150fb2b0](https://linux-hardware.org/?probe=8d150fb2b0) | Jun 05, 2023 |
| MSI           | 990FXA GAMING               | [1c99e1316c](https://linux-hardware.org/?probe=1c99e1316c) | Jun 05, 2023 |
| MSI           | 990FXA GAMING               | [60fb09bf5e](https://linux-hardware.org/?probe=60fb09bf5e) | Jun 05, 2023 |
| ECS           | G31T-M9                     | [8bb444bdd6](https://linux-hardware.org/?probe=8bb444bdd6) | Jun 05, 2023 |
| ASUSTek       | P5Q                         | [85c6e06d3b](https://linux-hardware.org/?probe=85c6e06d3b) | Jun 05, 2023 |
| HP            | 3397                        | [ea59ba572e](https://linux-hardware.org/?probe=ea59ba572e) | Jun 05, 2023 |
| Gigabyte      | G31M-ES2L                   | [6f15ff21e4](https://linux-hardware.org/?probe=6f15ff21e4) | Jun 05, 2023 |
| ASUSTek       | PRIME Z590-P                | [933aa24820](https://linux-hardware.org/?probe=933aa24820) | Jun 05, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [91ee57c108](https://linux-hardware.org/?probe=91ee57c108) | Jun 05, 2023 |
| Gigabyte      | B250-FinTech-CF             | [e22c496628](https://linux-hardware.org/?probe=e22c496628) | Jun 05, 2023 |
| Gigabyte      | Q87M-D2H                    | [eeaf6dbd4c](https://linux-hardware.org/?probe=eeaf6dbd4c) | Jun 05, 2023 |
| HP            | 1998                        | [c6183bd564](https://linux-hardware.org/?probe=c6183bd564) | Jun 05, 2023 |
| Gigabyte      | M68MT-S2                    | [2ec944c5d0](https://linux-hardware.org/?probe=2ec944c5d0) | Jun 05, 2023 |
| Unknown       | Unknown                     | [8896a460d4](https://linux-hardware.org/?probe=8896a460d4) | Jun 05, 2023 |
| AMD           | A88                         | [a7f64b7e4b](https://linux-hardware.org/?probe=a7f64b7e4b) | Jun 05, 2023 |
| Gigabyte      | M68MT-S2                    | [d392dff6bb](https://linux-hardware.org/?probe=d392dff6bb) | Jun 05, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | [cc575f0073](https://linux-hardware.org/?probe=cc575f0073) | Jun 05, 2023 |
| Dell          | 0VD5HY A07                  | [4e11e5ab66](https://linux-hardware.org/?probe=4e11e5ab66) | Jun 05, 2023 |
| ASRock        | 960GM-GS3 FX                | [72702690e5](https://linux-hardware.org/?probe=72702690e5) | Jun 05, 2023 |
| LORD ELECT... | I915 Series V1.0            | [d693b7baec](https://linux-hardware.org/?probe=d693b7baec) | Jun 05, 2023 |
| HP            | 8768 A                      | [17d0560a85](https://linux-hardware.org/?probe=17d0560a85) | Jun 05, 2023 |
| ASRock        | G41M-GS3                    | [f8789775fe](https://linux-hardware.org/?probe=f8789775fe) | Jun 05, 2023 |
| MSI           | B450M MORTAR                | [6d2c05fd11](https://linux-hardware.org/?probe=6d2c05fd11) | Jun 05, 2023 |
| Intel         | DE3815TYKH H26998-402       | [d2f97c16e9](https://linux-hardware.org/?probe=d2f97c16e9) | Jun 05, 2023 |
| ASRock        | A320M-HDV R4.0              | [5e9fd3f392](https://linux-hardware.org/?probe=5e9fd3f392) | Jun 05, 2023 |
| ECS           | G31T-M9                     | [630360ab38](https://linux-hardware.org/?probe=630360ab38) | Jun 05, 2023 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | [54e2e07ac6](https://linux-hardware.org/?probe=54e2e07ac6) | Jun 05, 2023 |
| AMI           | Intel                       | [7990e6561b](https://linux-hardware.org/?probe=7990e6561b) | Jun 05, 2023 |
| Intel         | DP965LT AAD41694-301        | [f72bcbf0a2](https://linux-hardware.org/?probe=f72bcbf0a2) | Jun 05, 2023 |
| Dell          | 0DF42J A00                  | [c68dff0dd7](https://linux-hardware.org/?probe=c68dff0dd7) | Jun 05, 2023 |
| Unknown       | Unknown                     | [292269611c](https://linux-hardware.org/?probe=292269611c) | Jun 05, 2023 |
| Dell          | 055H3G A01                  | [3fc296df33](https://linux-hardware.org/?probe=3fc296df33) | Jun 05, 2023 |
| Gigabyte      | X299 AORUS Gaming 7         | [6f6ddfe780](https://linux-hardware.org/?probe=6f6ddfe780) | Jun 05, 2023 |
| ASUSTek       | M5A78L-M LX3 PLUS           | [1f07862108](https://linux-hardware.org/?probe=1f07862108) | Jun 05, 2023 |
| ASRock        | N68C-S UCC                  | [741e39b142](https://linux-hardware.org/?probe=741e39b142) | Jun 05, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | [4ba1a29c23](https://linux-hardware.org/?probe=4ba1a29c23) | Jun 05, 2023 |
| Gigabyte      | F2A55M-DS2                  | [74b01a9071](https://linux-hardware.org/?probe=74b01a9071) | Jun 05, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [3a1c1daa3d](https://linux-hardware.org/?probe=3a1c1daa3d) | Jun 05, 2023 |
| Gigabyte      | M68MT-S2                    | [991c5472ac](https://linux-hardware.org/?probe=991c5472ac) | Jun 05, 2023 |
| HP            | 83E2                        | [522273fe60](https://linux-hardware.org/?probe=522273fe60) | Jun 05, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [292e41c0e9](https://linux-hardware.org/?probe=292e41c0e9) | Jun 05, 2023 |
| ASUSTek       | SABERTOOTH 55i              | [c208cb2024](https://linux-hardware.org/?probe=c208cb2024) | Jun 05, 2023 |
| MSI           | B250 GAMING PRO CARBON      | [32da3735d9](https://linux-hardware.org/?probe=32da3735d9) | Jun 05, 2023 |
| ASRock        | B150M Pro4                  | [0b59eacbd3](https://linux-hardware.org/?probe=0b59eacbd3) | Jun 05, 2023 |
| Dell          | 00010C A00                  | [fb12198605](https://linux-hardware.org/?probe=fb12198605) | Jun 05, 2023 |
| Dell          | 00010C A00                  | [d94442285c](https://linux-hardware.org/?probe=d94442285c) | Jun 05, 2023 |
| ASRockRack    | X470D4U2-2T                 | [4592ff63f3](https://linux-hardware.org/?probe=4592ff63f3) | Jun 05, 2023 |
| ASUSTek       | PRIME B550M-A AC            | [0cf4dfc5e4](https://linux-hardware.org/?probe=0cf4dfc5e4) | Jun 05, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | [8ba3a60a93](https://linux-hardware.org/?probe=8ba3a60a93) | Jun 05, 2023 |
| ASRock        | FM2A88X Extreme6+           | [79b80daf83](https://linux-hardware.org/?probe=79b80daf83) | Jun 05, 2023 |
| Biostar       | B350GT3                     | [b425f8d45a](https://linux-hardware.org/?probe=b425f8d45a) | Jun 05, 2023 |
| MSI           | X99A RAIDER                 | [36173d5a42](https://linux-hardware.org/?probe=36173d5a42) | Jun 05, 2023 |
| ASUSTek       | Z170-K                      | [a2c31cdc69](https://linux-hardware.org/?probe=a2c31cdc69) | Jun 05, 2023 |
| HP            | 3397                        | [e9dd850e23](https://linux-hardware.org/?probe=e9dd850e23) | Jun 05, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [580ae6529e](https://linux-hardware.org/?probe=580ae6529e) | Jun 05, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [43c70efbe7](https://linux-hardware.org/?probe=43c70efbe7) | Jun 05, 2023 |
| Dell          | 0D24M8 A00                  | [92fe930ecf](https://linux-hardware.org/?probe=92fe930ecf) | Jun 05, 2023 |
| MSI           | B360M PRO-VH                | [8e4ad66edc](https://linux-hardware.org/?probe=8e4ad66edc) | Jun 05, 2023 |
| Dell          | 0KWVT8 A03                  | [e974c8cdcd](https://linux-hardware.org/?probe=e974c8cdcd) | Jun 05, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [d275c3c00b](https://linux-hardware.org/?probe=d275c3c00b) | Jun 05, 2023 |
| Pegatron      | 2AC2                        | [6182103d25](https://linux-hardware.org/?probe=6182103d25) | Jun 05, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [8c6a275a93](https://linux-hardware.org/?probe=8c6a275a93) | Jun 05, 2023 |
| HP            | 1850                        | [bddc14be8b](https://linux-hardware.org/?probe=bddc14be8b) | Jun 05, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | [8cbfe4cdf0](https://linux-hardware.org/?probe=8cbfe4cdf0) | Jun 05, 2023 |
| ASUSTek       | PRIME B350M-A               | [3a0576b177](https://linux-hardware.org/?probe=3a0576b177) | Jun 05, 2023 |
| Dell          | 0HD5W2 A01                  | [917462f8c8](https://linux-hardware.org/?probe=917462f8c8) | Jun 05, 2023 |
| BY OEM        | ZRD1103                     | [316792c3ac](https://linux-hardware.org/?probe=316792c3ac) | Jun 05, 2023 |
| ASUSTek       | PRIME Z590-V                | [d0fd3fd90a](https://linux-hardware.org/?probe=d0fd3fd90a) | Jun 04, 2023 |
| ASUSTek       | PRIME Z590-V                | [bc93ac1588](https://linux-hardware.org/?probe=bc93ac1588) | Jun 04, 2023 |
| Gigabyte      | H470M DS3H                  | [e7bbac1b14](https://linux-hardware.org/?probe=e7bbac1b14) | Jun 04, 2023 |
| MSI           | Boston                      | [9f5efc29ad](https://linux-hardware.org/?probe=9f5efc29ad) | Jun 04, 2023 |
| MSI           | B450-A PRO MAX              | [202c4ee201](https://linux-hardware.org/?probe=202c4ee201) | Jun 04, 2023 |
| AMI           | Intel                       | [966c93cbdb](https://linux-hardware.org/?probe=966c93cbdb) | Jun 04, 2023 |
| ASRock        | B450M Pro4 R2.0             | [8e0a13cdd1](https://linux-hardware.org/?probe=8e0a13cdd1) | Jun 04, 2023 |
| ASUSTek       | M5A88-M                     | [e750392f99](https://linux-hardware.org/?probe=e750392f99) | Jun 04, 2023 |
| Dell          | 042P49 A01                  | [50f682ce84](https://linux-hardware.org/?probe=50f682ce84) | Jun 04, 2023 |
| HP            | 8643 SMVB                   | [697cc43136](https://linux-hardware.org/?probe=697cc43136) | Jun 04, 2023 |
| Lenovo        | ThinkCentre Edge 91Z 707... | [a6804d8ca1](https://linux-hardware.org/?probe=a6804d8ca1) | Jun 04, 2023 |
| ASUSTek       | PRIME B550M-A               | [d6befa925e](https://linux-hardware.org/?probe=d6befa925e) | Jun 04, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [d9dba3ffdf](https://linux-hardware.org/?probe=d9dba3ffdf) | Jun 04, 2023 |
| Intel         | DH55HC AAE70933-503         | [b3d5e112eb](https://linux-hardware.org/?probe=b3d5e112eb) | Jun 04, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [ba0e7c7d59](https://linux-hardware.org/?probe=ba0e7c7d59) | Jun 04, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [3af6e03b1c](https://linux-hardware.org/?probe=3af6e03b1c) | Jun 04, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [3d29012888](https://linux-hardware.org/?probe=3d29012888) | Jun 04, 2023 |
| Gigabyte      | B360M HD3                   | [fcb1b60578](https://linux-hardware.org/?probe=fcb1b60578) | Jun 04, 2023 |
| MSI           | H81M-E34                    | [4c5f5c7903](https://linux-hardware.org/?probe=4c5f5c7903) | Jun 04, 2023 |
| Gigabyte      | B85M-D3H                    | [0bd595e07a](https://linux-hardware.org/?probe=0bd595e07a) | Jun 04, 2023 |
| Medion        | TJ4125                      | [3faed0102f](https://linux-hardware.org/?probe=3faed0102f) | Jun 04, 2023 |
| Gigabyte      | B450M DS3H-CF               | [4b162cac99](https://linux-hardware.org/?probe=4b162cac99) | Jun 04, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [0dbe01becf](https://linux-hardware.org/?probe=0dbe01becf) | Jun 04, 2023 |
| Gigabyte      | X570 AORUS PRO              | [efa9cac1df](https://linux-hardware.org/?probe=efa9cac1df) | Jun 04, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [74e71defee](https://linux-hardware.org/?probe=74e71defee) | Jun 04, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [d7ae224bea](https://linux-hardware.org/?probe=d7ae224bea) | Jun 04, 2023 |
| HP            | 8949 11                     | [06bca18276](https://linux-hardware.org/?probe=06bca18276) | Jun 04, 2023 |
| Gigabyte      | Z87-HD3                     | [228a46e465](https://linux-hardware.org/?probe=228a46e465) | Jun 04, 2023 |
| ASRock        | J5040-ITX                   | [5e1bb16065](https://linux-hardware.org/?probe=5e1bb16065) | Jun 04, 2023 |
| Gigabyte      | B660M GAMING X DDR4         | [0bd883cae2](https://linux-hardware.org/?probe=0bd883cae2) | Jun 04, 2023 |
| Gigabyte      | A520M S2H                   | [81caf6e8cf](https://linux-hardware.org/?probe=81caf6e8cf) | Jun 04, 2023 |
| ASRock        | QC5000M-ITX/PH              | [bdf4ee4d4f](https://linux-hardware.org/?probe=bdf4ee4d4f) | Jun 04, 2023 |
| MSI           | B450M MORTAR MAX            | [72ccbe10aa](https://linux-hardware.org/?probe=72ccbe10aa) | Jun 04, 2023 |
| Gigabyte      | G33M-S2                     | [17ed1704c5](https://linux-hardware.org/?probe=17ed1704c5) | Jun 04, 2023 |
| HP            | 1495                        | [0cbf6bee1f](https://linux-hardware.org/?probe=0cbf6bee1f) | Jun 04, 2023 |
| ASRock        | A75M-HVS                    | [69bc52dc4f](https://linux-hardware.org/?probe=69bc52dc4f) | Jun 04, 2023 |
| MSI           | GF615M-P33                  | [84f237f434](https://linux-hardware.org/?probe=84f237f434) | Jun 04, 2023 |
| HP            | 21B4 A01                    | [5d394c52ed](https://linux-hardware.org/?probe=5d394c52ed) | Jun 04, 2023 |
| HP            | 1493                        | [b7432a020a](https://linux-hardware.org/?probe=b7432a020a) | Jun 04, 2023 |
| Acer          | Predator G3-710             | [7193d24262](https://linux-hardware.org/?probe=7193d24262) | Jun 04, 2023 |
| Gigabyte      | F2A88XM-D3H                 | [f88c53fd11](https://linux-hardware.org/?probe=f88c53fd11) | Jun 04, 2023 |
| Acer          | Predator G3-710             | [96834ea12b](https://linux-hardware.org/?probe=96834ea12b) | Jun 04, 2023 |
| HP            | 83E2                        | [3684f8562d](https://linux-hardware.org/?probe=3684f8562d) | Jun 04, 2023 |
| Acer          | Predator G3-710             | [c200dbb9cf](https://linux-hardware.org/?probe=c200dbb9cf) | Jun 04, 2023 |
| Acer          | Veriton X4630G V:1.0        | [5106e40f32](https://linux-hardware.org/?probe=5106e40f32) | Jun 04, 2023 |
| Gigabyte      | G33M-S2                     | [82bab4dd6d](https://linux-hardware.org/?probe=82bab4dd6d) | Jun 04, 2023 |
| Gigabyte      | G41MT-S2P                   | [aa5ed8cbc0](https://linux-hardware.org/?probe=aa5ed8cbc0) | Jun 04, 2023 |
| ASRock        | X670E PG Lightning          | [7cd25ddbda](https://linux-hardware.org/?probe=7cd25ddbda) | Jun 04, 2023 |
| SYWZ          | S200 Series                 | [577c490fb7](https://linux-hardware.org/?probe=577c490fb7) | Jun 04, 2023 |
| Gigabyte      | H310M HD2                   | [b28787ecb7](https://linux-hardware.org/?probe=b28787ecb7) | Jun 04, 2023 |
| ASRock        | G31M-GS                     | [558dec9114](https://linux-hardware.org/?probe=558dec9114) | Jun 04, 2023 |
| HP            | 8643 SMVB                   | [88fbd57dac](https://linux-hardware.org/?probe=88fbd57dac) | Jun 04, 2023 |
| Unknown       | Unknown                     | [77d585fa03](https://linux-hardware.org/?probe=77d585fa03) | Jun 04, 2023 |
| ASRock        | X670E Taichi                | [6616151cda](https://linux-hardware.org/?probe=6616151cda) | Jun 04, 2023 |
| Dell          | 09D7F7 A00                  | [9b80703b01](https://linux-hardware.org/?probe=9b80703b01) | Jun 04, 2023 |
| Biostar       | B350GT5                     | [18e1da8cce](https://linux-hardware.org/?probe=18e1da8cce) | Jun 04, 2023 |
| Dell          | 0Y5DDC A00                  | [5713168678](https://linux-hardware.org/?probe=5713168678) | Jun 04, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [70e5950511](https://linux-hardware.org/?probe=70e5950511) | Jun 04, 2023 |
| ASUSTek       | H81M-A                      | [9636642e65](https://linux-hardware.org/?probe=9636642e65) | Jun 04, 2023 |
| ASRock        | A320M-HDV R4.0              | [f472cba5a6](https://linux-hardware.org/?probe=f472cba5a6) | Jun 04, 2023 |
| ASUSTek       | H170-PRO                    | [b9fd75507c](https://linux-hardware.org/?probe=b9fd75507c) | Jun 04, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [6167898a10](https://linux-hardware.org/?probe=6167898a10) | Jun 04, 2023 |
| Biostar       | B350GT5                     | [123beb390f](https://linux-hardware.org/?probe=123beb390f) | Jun 04, 2023 |
| ASUSTek       | P5G41T-M                    | [8706eff580](https://linux-hardware.org/?probe=8706eff580) | Jun 04, 2023 |
| ASUSTek       | M4N72-E                     | [51d39945ec](https://linux-hardware.org/?probe=51d39945ec) | Jun 04, 2023 |
| MSI           | Z270-A PRO                  | [1da4d78c3b](https://linux-hardware.org/?probe=1da4d78c3b) | Jun 04, 2023 |
| ASUSTek       | B75M-A                      | [55139a968d](https://linux-hardware.org/?probe=55139a968d) | Jun 04, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [5b35735d26](https://linux-hardware.org/?probe=5b35735d26) | Jun 04, 2023 |
| Unknown       | Intel X79                   | [0e2e65a79e](https://linux-hardware.org/?probe=0e2e65a79e) | Jun 04, 2023 |
| MSI           | X470 GAMING PLUS            | [7af9263ba9](https://linux-hardware.org/?probe=7af9263ba9) | Jun 04, 2023 |
| ASUSTek       | P8Z77-V LE                  | [9a66179aaf](https://linux-hardware.org/?probe=9a66179aaf) | Jun 04, 2023 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | [413aba0d3f](https://linux-hardware.org/?probe=413aba0d3f) | Jun 04, 2023 |
| MSI           | X470 GAMING PLUS            | [ae24cbf98d](https://linux-hardware.org/?probe=ae24cbf98d) | Jun 04, 2023 |
| Lenovo        | 32E9 SDK0T76465 WIN 3422... | [fa41f1f3c2](https://linux-hardware.org/?probe=fa41f1f3c2) | Jun 04, 2023 |
| MSI           | PRO Z790-P WIFI             | [fb0c1a4922](https://linux-hardware.org/?probe=fb0c1a4922) | Jun 04, 2023 |
| MSI           | H81M-P32                    | [f2423b3ef9](https://linux-hardware.org/?probe=f2423b3ef9) | Jun 04, 2023 |
| MSI           | H81M-P32                    | [f1d0b1d487](https://linux-hardware.org/?probe=f1d0b1d487) | Jun 04, 2023 |
| ASRock        | B550 PG Velocita            | [12833898d1](https://linux-hardware.org/?probe=12833898d1) | Jun 04, 2023 |
| HP            | 2AE5 A01                    | [ab3ab74fb6](https://linux-hardware.org/?probe=ab3ab74fb6) | Jun 04, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | [60749b6e47](https://linux-hardware.org/?probe=60749b6e47) | Jun 04, 2023 |
| MSI           | Boston                      | [95b4d5183d](https://linux-hardware.org/?probe=95b4d5183d) | Jun 04, 2023 |
| MSI           | P55-CD53                    | [88efe4b48c](https://linux-hardware.org/?probe=88efe4b48c) | Jun 04, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | [f71eae78c5](https://linux-hardware.org/?probe=f71eae78c5) | Jun 04, 2023 |
| MSI           | A55M-E33                    | [336b7f877d](https://linux-hardware.org/?probe=336b7f877d) | Jun 04, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [aafda7cf63](https://linux-hardware.org/?probe=aafda7cf63) | Jun 04, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [82542c4daa](https://linux-hardware.org/?probe=82542c4daa) | Jun 04, 2023 |
| Dell          | 01XK1W A00                  | [8690705151](https://linux-hardware.org/?probe=8690705151) | Jun 04, 2023 |
| ASUSTek       | ROG STRIX B360-I GAMING     | [0c8afa948b](https://linux-hardware.org/?probe=0c8afa948b) | Jun 04, 2023 |
| HP            | 843C                        | [e69fbf77e4](https://linux-hardware.org/?probe=e69fbf77e4) | Jun 04, 2023 |
| HP            | 2B43                        | [d66cd5f48e](https://linux-hardware.org/?probe=d66cd5f48e) | Jun 04, 2023 |
| HP            | 843C                        | [21751c1221](https://linux-hardware.org/?probe=21751c1221) | Jun 04, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [06752ca793](https://linux-hardware.org/?probe=06752ca793) | Jun 04, 2023 |
| Foxconn       | G41MD                       | [f988a585c9](https://linux-hardware.org/?probe=f988a585c9) | Jun 04, 2023 |
| Dell          | 0KWVT8 A03                  | [2250609446](https://linux-hardware.org/?probe=2250609446) | Jun 04, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [a90856c944](https://linux-hardware.org/?probe=a90856c944) | Jun 04, 2023 |
| Gigabyte      | B250M-D3H-CF                | [d8f9165fec](https://linux-hardware.org/?probe=d8f9165fec) | Jun 04, 2023 |
| Dell          | 0KWVT8 A03                  | [7f73996b8e](https://linux-hardware.org/?probe=7f73996b8e) | Jun 04, 2023 |
| Gigabyte      | Z77X-UD5H                   | [b0efe96508](https://linux-hardware.org/?probe=b0efe96508) | Jun 04, 2023 |
| Unknown       | Unknown                     | [8c2d7ce6e2](https://linux-hardware.org/?probe=8c2d7ce6e2) | Jun 04, 2023 |
| MSI           | B450 TOMAHAWK               | [aaed1b39af](https://linux-hardware.org/?probe=aaed1b39af) | Jun 03, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | [8b790b76a6](https://linux-hardware.org/?probe=8b790b76a6) | Jun 03, 2023 |
| Dell          | 0N4NF7 A00                  | [e1348eb2c2](https://linux-hardware.org/?probe=e1348eb2c2) | Jun 03, 2023 |
| ASRock        | Z590 Phantom Gaming 4       | [1e9eef0102](https://linux-hardware.org/?probe=1e9eef0102) | Jun 03, 2023 |
| Dell          | 0N4NF7 A00                  | [6ff177257b](https://linux-hardware.org/?probe=6ff177257b) | Jun 03, 2023 |
| Foxconn       | A74ML-K                     | [7a4f7e239b](https://linux-hardware.org/?probe=7a4f7e239b) | Jun 03, 2023 |
| Gigabyte      | Z690 AORUS ULTRA            | [50cdb8a60a](https://linux-hardware.org/?probe=50cdb8a60a) | Jun 03, 2023 |
| Lenovo        | ThinkStation D30 42234T7    | [18cb6a946b](https://linux-hardware.org/?probe=18cb6a946b) | Jun 03, 2023 |
| Gigabyte      | X570 AORUS PRO              | [309d09ae8c](https://linux-hardware.org/?probe=309d09ae8c) | Jun 03, 2023 |
| MSI           | B460M PRO-VDH WIFI          | [b92c18e955](https://linux-hardware.org/?probe=b92c18e955) | Jun 03, 2023 |
| Huanan        | X79 V7.11                   | [79bbc880ba](https://linux-hardware.org/?probe=79bbc880ba) | Jun 03, 2023 |
| Gigabyte      | F2A88XM-D3H                 | [c142ea01cd](https://linux-hardware.org/?probe=c142ea01cd) | Jun 03, 2023 |
| ASUSTek       | Pro B550M-C                 | [094889a0e2](https://linux-hardware.org/?probe=094889a0e2) | Jun 03, 2023 |
| MSI           | B550M PRO-VDH               | [d09ba05086](https://linux-hardware.org/?probe=d09ba05086) | Jun 03, 2023 |
| Intel         | X99 V102                    | [ed5a67e8a5](https://linux-hardware.org/?probe=ed5a67e8a5) | Jun 03, 2023 |
| ASUSTek       | P8B75-M LE                  | [640faccae0](https://linux-hardware.org/?probe=640faccae0) | Jun 03, 2023 |
| ASRock        | FM2A88X Extreme6+           | [2745284306](https://linux-hardware.org/?probe=2745284306) | Jun 03, 2023 |
| HP            | 8949 11                     | [f06749002f](https://linux-hardware.org/?probe=f06749002f) | Jun 03, 2023 |
| MSI           | B550M PRO-VDH               | [9f13a5184c](https://linux-hardware.org/?probe=9f13a5184c) | Jun 03, 2023 |
| Acer          | Aspire TC-705               | [8aa3bc4947](https://linux-hardware.org/?probe=8aa3bc4947) | Jun 03, 2023 |
| ASUSTek       | PRIME B365M-A               | [5c280bbd6c](https://linux-hardware.org/?probe=5c280bbd6c) | Jun 03, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [0523005c68](https://linux-hardware.org/?probe=0523005c68) | Jun 03, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | [4d24b9b7d5](https://linux-hardware.org/?probe=4d24b9b7d5) | Jun 03, 2023 |
| Gigabyte      | B450M AORUS ELITE           | [f17ae033ef](https://linux-hardware.org/?probe=f17ae033ef) | Jun 03, 2023 |
| MSI           | B150M MORTAR                | [3fc6303165](https://linux-hardware.org/?probe=3fc6303165) | Jun 03, 2023 |
| Acer          | Veriton M2631 V:1.0         | [e64369d2ec](https://linux-hardware.org/?probe=e64369d2ec) | Jun 03, 2023 |
| Biostar       | B450MX-S                    | [ccc6b5c4b5](https://linux-hardware.org/?probe=ccc6b5c4b5) | Jun 03, 2023 |
| Biostar       | B450MX-S                    | [6a01df1d69](https://linux-hardware.org/?probe=6a01df1d69) | Jun 03, 2023 |
| MSI           | H97M-G43                    | [6bd1b61977](https://linux-hardware.org/?probe=6bd1b61977) | Jun 03, 2023 |
| MSI           | B450M BAZOOKA V2            | [e0008bd879](https://linux-hardware.org/?probe=e0008bd879) | Jun 03, 2023 |
| ECS           | G31T-M                      | [55d38b75c7](https://linux-hardware.org/?probe=55d38b75c7) | Jun 03, 2023 |
| MSI           | H310M PRO-VD PLUS           | [5ee3eec233](https://linux-hardware.org/?probe=5ee3eec233) | Jun 03, 2023 |
| MSI           | B450M BAZOOKA V2            | [979df15914](https://linux-hardware.org/?probe=979df15914) | Jun 03, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [72fc2eea56](https://linux-hardware.org/?probe=72fc2eea56) | Jun 03, 2023 |
| ASUSTek       | Z97-PRO GAMER               | [8d783c6b00](https://linux-hardware.org/?probe=8d783c6b00) | Jun 03, 2023 |
| MSI           | B450M PRO-M2 V2             | [fc8a306ca0](https://linux-hardware.org/?probe=fc8a306ca0) | Jun 03, 2023 |
| Gigabyte      | A520M S2H                   | [0169222312](https://linux-hardware.org/?probe=0169222312) | Jun 03, 2023 |
| ASUSTek       | P5Q-PRO                     | [76cd01b045](https://linux-hardware.org/?probe=76cd01b045) | Jun 03, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [5387bcbf7d](https://linux-hardware.org/?probe=5387bcbf7d) | Jun 03, 2023 |
| Gigabyte      | X79-UP4                     | [e3fd506f5e](https://linux-hardware.org/?probe=e3fd506f5e) | Jun 03, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [9966a3f6d1](https://linux-hardware.org/?probe=9966a3f6d1) | Jun 03, 2023 |
| Gigabyte      | H67MA-USB3-B3               | [1908e7e6f5](https://linux-hardware.org/?probe=1908e7e6f5) | Jun 03, 2023 |
| ASRock        | FM2A68M-DG3+                | [3e7ad22b6b](https://linux-hardware.org/?probe=3e7ad22b6b) | Jun 03, 2023 |
| SZMZ          | X99M-G2                     | [e9b164885c](https://linux-hardware.org/?probe=e9b164885c) | Jun 03, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [881df8f45c](https://linux-hardware.org/?probe=881df8f45c) | Jun 03, 2023 |
| HP            | 3397                        | [530b98edd5](https://linux-hardware.org/?probe=530b98edd5) | Jun 03, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [51868dd3c8](https://linux-hardware.org/?probe=51868dd3c8) | Jun 03, 2023 |
| Dell          | 0KRC95 A02                  | [3fb87e5a0e](https://linux-hardware.org/?probe=3fb87e5a0e) | Jun 03, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [0dd3be3300](https://linux-hardware.org/?probe=0dd3be3300) | Jun 03, 2023 |
| Gigabyte      | B365M H                     | [b7a585d1f1](https://linux-hardware.org/?probe=b7a585d1f1) | Jun 03, 2023 |
| ASUSTek       | PRIME Z390-P                | [64c321d474](https://linux-hardware.org/?probe=64c321d474) | Jun 03, 2023 |
| MSI           | A320M PRO-VH PLUS           | [8ba76b1e88](https://linux-hardware.org/?probe=8ba76b1e88) | Jun 03, 2023 |
| Dell          | 0D6H9T A01                  | [1ebbe353ba](https://linux-hardware.org/?probe=1ebbe353ba) | Jun 03, 2023 |
| Dell          | 0D6H9T A01                  | [0bb2080b31](https://linux-hardware.org/?probe=0bb2080b31) | Jun 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [7b513e678c](https://linux-hardware.org/?probe=7b513e678c) | Jun 03, 2023 |
| ASUSTek       | PRIME A520M-A               | [7dac003c12](https://linux-hardware.org/?probe=7dac003c12) | Jun 03, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [44571410f0](https://linux-hardware.org/?probe=44571410f0) | Jun 03, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [d54d77b051](https://linux-hardware.org/?probe=d54d77b051) | Jun 03, 2023 |
| ASUSTek       | H97-PRO                     | [bfe6623b23](https://linux-hardware.org/?probe=bfe6623b23) | Jun 03, 2023 |
| ASUSTek       | H97-PRO                     | [c3dae64ee6](https://linux-hardware.org/?probe=c3dae64ee6) | Jun 03, 2023 |
| Dell          | 0G9322                      | [a1c5ec8909](https://linux-hardware.org/?probe=a1c5ec8909) | Jun 03, 2023 |
| ASUSTek       | Maximus VIII HERO ALPHA     | [48eb50cc43](https://linux-hardware.org/?probe=48eb50cc43) | Jun 03, 2023 |
| Gigabyte      | X79-UD3                     | [e459d2654f](https://linux-hardware.org/?probe=e459d2654f) | Jun 03, 2023 |
| ASRock        | AB350M Pro4                 | [30a95a3f53](https://linux-hardware.org/?probe=30a95a3f53) | Jun 03, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [8d4d1f7313](https://linux-hardware.org/?probe=8d4d1f7313) | Jun 03, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [8e46a969c7](https://linux-hardware.org/?probe=8e46a969c7) | Jun 03, 2023 |
| Gigabyte      | B550 AORUS MASTER           | [80e9681888](https://linux-hardware.org/?probe=80e9681888) | Jun 03, 2023 |
| MSI           | PRO Z790-A WIFI             | [1c7cc37995](https://linux-hardware.org/?probe=1c7cc37995) | Jun 03, 2023 |
| HP            | 3047h                       | [1825675e99](https://linux-hardware.org/?probe=1825675e99) | Jun 03, 2023 |
| MSI           | H110M PRO-VH PLUS           | [79e14478a3](https://linux-hardware.org/?probe=79e14478a3) | Jun 03, 2023 |
| MSI           | B250 GAMING PRO CARBON      | [ef7acf6baa](https://linux-hardware.org/?probe=ef7acf6baa) | Jun 03, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [c0f64d3436](https://linux-hardware.org/?probe=c0f64d3436) | Jun 03, 2023 |
| Dell          | 0NW6H5 A00                  | [01387c3030](https://linux-hardware.org/?probe=01387c3030) | Jun 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [20260fb3b3](https://linux-hardware.org/?probe=20260fb3b3) | Jun 03, 2023 |
| ASUSTek       | Z170-A                      | [4f512af4c2](https://linux-hardware.org/?probe=4f512af4c2) | Jun 03, 2023 |
| Positivo      | POS-EINM70CS POS            | [80260b495c](https://linux-hardware.org/?probe=80260b495c) | Jun 03, 2023 |
| Positivo      | POS-PIG41BA                 | [f630c0b9cd](https://linux-hardware.org/?probe=f630c0b9cd) | Jun 03, 2023 |
| Dell          | 0M6C7G A00                  | [93bdbbdafb](https://linux-hardware.org/?probe=93bdbbdafb) | Jun 03, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [21b7236d20](https://linux-hardware.org/?probe=21b7236d20) | Jun 03, 2023 |
| ASUSTek       | PRIME Z790-A WIFI           | [4e17d7c6e8](https://linux-hardware.org/?probe=4e17d7c6e8) | Jun 03, 2023 |
| ASUSTek       | PRIME Z790-A WIFI           | [965de576c7](https://linux-hardware.org/?probe=965de576c7) | Jun 03, 2023 |
| ASUSTek       | PRIME B650M-A AX            | [983a81f19e](https://linux-hardware.org/?probe=983a81f19e) | Jun 03, 2023 |
| MSI           | MAG B550M MORTAR            | [3d911ac9c9](https://linux-hardware.org/?probe=3d911ac9c9) | Jun 03, 2023 |
| Gigabyte      | B650M GAMING X AX           | [610ba5871f](https://linux-hardware.org/?probe=610ba5871f) | Jun 03, 2023 |
| Intel         | B75                         | [2387f30645](https://linux-hardware.org/?probe=2387f30645) | Jun 03, 2023 |
| ASRock        | H81M-HDS                    | [248372dd54](https://linux-hardware.org/?probe=248372dd54) | Jun 03, 2023 |
| Positivo      | POS-RIB360EE 11144907       | [7837922f5b](https://linux-hardware.org/?probe=7837922f5b) | Jun 02, 2023 |
| HP            | 339A                        | [bb4619f4eb](https://linux-hardware.org/?probe=bb4619f4eb) | Jun 02, 2023 |
| MSI           | MPG Z790 EDGE WIFI          | [dae8469b17](https://linux-hardware.org/?probe=dae8469b17) | Jun 02, 2023 |
| HP            | 3397                        | [046df77f81](https://linux-hardware.org/?probe=046df77f81) | Jun 02, 2023 |
| Dell          | 0RY007                      | [f3028ff55d](https://linux-hardware.org/?probe=f3028ff55d) | Jun 02, 2023 |
| Dell          | 08NPPY A00                  | [de331bfb5c](https://linux-hardware.org/?probe=de331bfb5c) | Jun 02, 2023 |
| MSI           | B450M PRO-VDH PLUS          | [9a0f40789b](https://linux-hardware.org/?probe=9a0f40789b) | Jun 02, 2023 |
| Biostar       | TA970XE                     | [11936a0f0f](https://linux-hardware.org/?probe=11936a0f0f) | Jun 02, 2023 |
| ASUSTek       | P8Z68-V                     | [59e64db8de](https://linux-hardware.org/?probe=59e64db8de) | Jun 02, 2023 |
| Medion        | TJ4125                      | [6244ae0e43](https://linux-hardware.org/?probe=6244ae0e43) | Jun 02, 2023 |
| Gigabyte      | B85M-D3H                    | [908f094e9d](https://linux-hardware.org/?probe=908f094e9d) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-A II            | [11e04db670](https://linux-hardware.org/?probe=11e04db670) | Jun 02, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | [d8f3391b68](https://linux-hardware.org/?probe=d8f3391b68) | Jun 02, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [d2189d4a5f](https://linux-hardware.org/?probe=d2189d4a5f) | Jun 02, 2023 |
| Dell          | 0GX832 A01                  | [19b718a96c](https://linux-hardware.org/?probe=19b718a96c) | Jun 02, 2023 |
| Gigabyte      | P75-D3                      | [a56c3ceb55](https://linux-hardware.org/?probe=a56c3ceb55) | Jun 02, 2023 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | [c8fca2b92d](https://linux-hardware.org/?probe=c8fca2b92d) | Jun 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d6561ecd7b](https://linux-hardware.org/?probe=d6561ecd7b) | Jun 02, 2023 |
| Lenovo        | 3188 SDK0J40697 WIN 3305... | [c64fbbcad9](https://linux-hardware.org/?probe=c64fbbcad9) | Jun 02, 2023 |
| HP            | 2AE5 A01                    | [c37afc3b8a](https://linux-hardware.org/?probe=c37afc3b8a) | Jun 02, 2023 |
| Unknown       | X99                         | [0ffca5934a](https://linux-hardware.org/?probe=0ffca5934a) | Jun 02, 2023 |
| HP            | 8918                        | [b03f8a6eb3](https://linux-hardware.org/?probe=b03f8a6eb3) | Jun 02, 2023 |
| Gigabyte      | A320M-S2H-CF                | [914fa73266](https://linux-hardware.org/?probe=914fa73266) | Jun 02, 2023 |
| ASRock        | B365 Pro4                   | [35fff15a30](https://linux-hardware.org/?probe=35fff15a30) | Jun 02, 2023 |
| ASRock        | B365 Pro4                   | [54fcb811b8](https://linux-hardware.org/?probe=54fcb811b8) | Jun 02, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [70a097a219](https://linux-hardware.org/?probe=70a097a219) | Jun 02, 2023 |
| Gigabyte      | Z590 UD AC                  | [da5b2056e4](https://linux-hardware.org/?probe=da5b2056e4) | Jun 02, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [25721b28d3](https://linux-hardware.org/?probe=25721b28d3) | Jun 02, 2023 |
| Positivo      | POS-RIB360EE 11144907       | [b4ba7702cb](https://linux-hardware.org/?probe=b4ba7702cb) | Jun 02, 2023 |
| HC Technol... | HCAR357-NR                  | [58f698b10a](https://linux-hardware.org/?probe=58f698b10a) | Jun 02, 2023 |
| ASUSTek       | P8Z77-V LK                  | [d50ca19dc3](https://linux-hardware.org/?probe=d50ca19dc3) | Jun 02, 2023 |
| Gigabyte      | H81M-S2H                    | [2604bac5a5](https://linux-hardware.org/?probe=2604bac5a5) | Jun 02, 2023 |
| ASRock        | X670E Steel Legend          | [c1cfe9f08d](https://linux-hardware.org/?probe=c1cfe9f08d) | Jun 02, 2023 |
| MSI           | G31TM-P21                   | [964377db0b](https://linux-hardware.org/?probe=964377db0b) | Jun 02, 2023 |
| Acer          | Aspire X3950                | [82aa882647](https://linux-hardware.org/?probe=82aa882647) | Jun 02, 2023 |
| ASRockRack    | X470D4U2-2T                 | [43901d3db7](https://linux-hardware.org/?probe=43901d3db7) | Jun 02, 2023 |
| ECS           | Nettle2                     | [6fe297e475](https://linux-hardware.org/?probe=6fe297e475) | Jun 02, 2023 |
| Dell          | 0VNM11 A01                  | [df3c87a033](https://linux-hardware.org/?probe=df3c87a033) | Jun 02, 2023 |
| Acer          | Aspire X3950                | [1c7f0f7567](https://linux-hardware.org/?probe=1c7f0f7567) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [853bd25ca5](https://linux-hardware.org/?probe=853bd25ca5) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [3a9fb692f1](https://linux-hardware.org/?probe=3a9fb692f1) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [9b549fe65a](https://linux-hardware.org/?probe=9b549fe65a) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [db685837d0](https://linux-hardware.org/?probe=db685837d0) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [968b38e0b9](https://linux-hardware.org/?probe=968b38e0b9) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [c9a04d8da0](https://linux-hardware.org/?probe=c9a04d8da0) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [238931757a](https://linux-hardware.org/?probe=238931757a) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [e190e991a6](https://linux-hardware.org/?probe=e190e991a6) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [0816e77499](https://linux-hardware.org/?probe=0816e77499) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | [ff143ac918](https://linux-hardware.org/?probe=ff143ac918) | Jun 02, 2023 |
| ASUSTek       | Z87-C                       | [20242d8299](https://linux-hardware.org/?probe=20242d8299) | Jun 02, 2023 |
| Intel         | DB85FL AAG89861-202         | [8ededa47e6](https://linux-hardware.org/?probe=8ededa47e6) | Jun 02, 2023 |
| Intel         | DB85FL AAG89861-202         | [7bd893ebe1](https://linux-hardware.org/?probe=7bd893ebe1) | Jun 02, 2023 |
| HP            | 212B                        | [15c4a7b64f](https://linux-hardware.org/?probe=15c4a7b64f) | Jun 02, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [3f032ab035](https://linux-hardware.org/?probe=3f032ab035) | Jun 02, 2023 |
| ASRock        | H470M-HDV                   | [abf4b3f5d2](https://linux-hardware.org/?probe=abf4b3f5d2) | Jun 02, 2023 |
| Dell          | 06X1TJ A00                  | [16d662673f](https://linux-hardware.org/?probe=16d662673f) | Jun 02, 2023 |
| ASRock        | H470M-HDV                   | [4092d4fe1b](https://linux-hardware.org/?probe=4092d4fe1b) | Jun 02, 2023 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [b86be4f1de](https://linux-hardware.org/?probe=b86be4f1de) | Jun 02, 2023 |
| Gigabyte      | H77N-WIFI                   | [8dce973d6b](https://linux-hardware.org/?probe=8dce973d6b) | Jun 02, 2023 |
| Gigabyte      | B550M DS3H                  | [a8f8239e40](https://linux-hardware.org/?probe=a8f8239e40) | Jun 02, 2023 |
| HP            | 802E                        | [1837c96bfd](https://linux-hardware.org/?probe=1837c96bfd) | Jun 02, 2023 |
| ASUSTek       | P8H61                       | [7e9f999121](https://linux-hardware.org/?probe=7e9f999121) | Jun 02, 2023 |
| Pegatron      | H81-M1                      | [cdb426bfb4](https://linux-hardware.org/?probe=cdb426bfb4) | Jun 02, 2023 |
| ASUSTek       | B85M-E                      | [ba95473e9c](https://linux-hardware.org/?probe=ba95473e9c) | Jun 02, 2023 |
| Gigabyte      | Z690 AORUS ELITE DDR4       | [c716b12ee2](https://linux-hardware.org/?probe=c716b12ee2) | Jun 02, 2023 |
| MSI           | H97 GAMING 3                | [f9c0a669c5](https://linux-hardware.org/?probe=f9c0a669c5) | Jun 02, 2023 |
| ASUSTek       | Maximus Formula             | [6a70fa0a86](https://linux-hardware.org/?probe=6a70fa0a86) | Jun 02, 2023 |
| Gigabyte      | B85-HD3                     | [9931f8e663](https://linux-hardware.org/?probe=9931f8e663) | Jun 02, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [5562bc75b8](https://linux-hardware.org/?probe=5562bc75b8) | Jun 02, 2023 |
| Dell          | 0NNNCT A01                  | [1a1e7426a3](https://linux-hardware.org/?probe=1a1e7426a3) | Jun 02, 2023 |
| MSI           | PRO X670-P WIFI             | [714ed7283d](https://linux-hardware.org/?probe=714ed7283d) | Jun 02, 2023 |
| MSI           | PRO X670-P WIFI             | [bb2776b990](https://linux-hardware.org/?probe=bb2776b990) | Jun 02, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [7a83a98e37](https://linux-hardware.org/?probe=7a83a98e37) | Jun 02, 2023 |
| MSI           | MS-7388                     | [fc12ac6b90](https://linux-hardware.org/?probe=fc12ac6b90) | Jun 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [c9e073b763](https://linux-hardware.org/?probe=c9e073b763) | Jun 02, 2023 |
| ASUSTek       | H61M-K                      | [c6ee1e5e32](https://linux-hardware.org/?probe=c6ee1e5e32) | Jun 02, 2023 |
| Dell          | 0GY6Y8 A02                  | [7f2c514dff](https://linux-hardware.org/?probe=7f2c514dff) | Jun 02, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [a78aee5f7f](https://linux-hardware.org/?probe=a78aee5f7f) | Jun 02, 2023 |
| Gateway       | SX2851                      | [262ddffda9](https://linux-hardware.org/?probe=262ddffda9) | Jun 02, 2023 |
| MSI           | P55-CD53                    | [4f87990649](https://linux-hardware.org/?probe=4f87990649) | Jun 02, 2023 |
| Alienware     | 0N43JM A00                  | [047bfb6e8e](https://linux-hardware.org/?probe=047bfb6e8e) | Jun 02, 2023 |
| Dell          | 04Y8V0 A02                  | [ce749a8df5](https://linux-hardware.org/?probe=ce749a8df5) | Jun 02, 2023 |
| HP            | 1497                        | [9ce66d3e2e](https://linux-hardware.org/?probe=9ce66d3e2e) | Jun 02, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [ded9a8f554](https://linux-hardware.org/?probe=ded9a8f554) | Jun 02, 2023 |
| Dell          | 01XK1W A00                  | [5846820609](https://linux-hardware.org/?probe=5846820609) | Jun 02, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [07e5342fb8](https://linux-hardware.org/?probe=07e5342fb8) | Jun 02, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [9a91f8aedc](https://linux-hardware.org/?probe=9a91f8aedc) | Jun 02, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | [d61bd0903e](https://linux-hardware.org/?probe=d61bd0903e) | Jun 02, 2023 |
| Gigabyte      | GA-880GMA-USB3              | [3feb5e9cb5](https://linux-hardware.org/?probe=3feb5e9cb5) | Jun 02, 2023 |
| Acer          | Aspire XC-780               | [7789b12750](https://linux-hardware.org/?probe=7789b12750) | Jun 02, 2023 |
| Pegatron      | H81-M1                      | [35eb509619](https://linux-hardware.org/?probe=35eb509619) | Jun 02, 2023 |
| Pegatron      | NARRA5                      | [1d9f5bc60f](https://linux-hardware.org/?probe=1d9f5bc60f) | Jun 02, 2023 |
| Gigabyte      | Z97M-DS3H                   | [1a4437e831](https://linux-hardware.org/?probe=1a4437e831) | Jun 02, 2023 |
| Intel         | DH61WW AAG23116-204         | [2bfe32ef05](https://linux-hardware.org/?probe=2bfe32ef05) | Jun 02, 2023 |
| MSI           | H81M-E34                    | [26362cac22](https://linux-hardware.org/?probe=26362cac22) | Jun 02, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [def2c6020b](https://linux-hardware.org/?probe=def2c6020b) | Jun 01, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [8aab7c6536](https://linux-hardware.org/?probe=8aab7c6536) | Jun 01, 2023 |
| MSI           | H81M-E34                    | [9f04387a7c](https://linux-hardware.org/?probe=9f04387a7c) | Jun 01, 2023 |
| Biostar       | A10N-8800E                  | [906dbab25c](https://linux-hardware.org/?probe=906dbab25c) | Jun 01, 2023 |
| Gigabyte      | AX370-Gaming K7             | [7baed02e0e](https://linux-hardware.org/?probe=7baed02e0e) | Jun 01, 2023 |
| ASRock        | ALiveDual-eSATA2            | [0f490d3b39](https://linux-hardware.org/?probe=0f490d3b39) | Jun 01, 2023 |
| MSI           | H510M-A PRO                 | [f517c1893a](https://linux-hardware.org/?probe=f517c1893a) | Jun 01, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [f22933cdb1](https://linux-hardware.org/?probe=f22933cdb1) | Jun 01, 2023 |
| ASUSTek       | PRIME X570-P                | [cde4aaef3e](https://linux-hardware.org/?probe=cde4aaef3e) | Jun 01, 2023 |
| Gigabyte      | H61M-S2PV                   | [6c86bd69e0](https://linux-hardware.org/?probe=6c86bd69e0) | Jun 01, 2023 |
| ASRock        | Z77M                        | [eae1adee21](https://linux-hardware.org/?probe=eae1adee21) | Jun 01, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [7070e55aa0](https://linux-hardware.org/?probe=7070e55aa0) | Jun 01, 2023 |
| HP            | 18E5                        | [9d89c3065b](https://linux-hardware.org/?probe=9d89c3065b) | Jun 01, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [5430a83fca](https://linux-hardware.org/?probe=5430a83fca) | Jun 01, 2023 |
| Itautec       | ST 4265 ST-4265 Padrao 0... | [7ac5ec7c05](https://linux-hardware.org/?probe=7ac5ec7c05) | Jun 01, 2023 |
| Gigabyte      | Q87M-D2H                    | [8f3525a119](https://linux-hardware.org/?probe=8f3525a119) | Jun 01, 2023 |
| MSI           | PRO B650-P WIFI             | [53d24a5962](https://linux-hardware.org/?probe=53d24a5962) | Jun 01, 2023 |
| Gigabyte      | Z390 AORUS ELITE-CF         | [75c4e47bea](https://linux-hardware.org/?probe=75c4e47bea) | Jun 01, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | [e98b2555d7](https://linux-hardware.org/?probe=e98b2555d7) | Jun 01, 2023 |
| Gigabyte      | H61M-DS2                    | [f3b666f725](https://linux-hardware.org/?probe=f3b666f725) | Jun 01, 2023 |
| Gigabyte      | Z390 UD                     | [b66cbe20f8](https://linux-hardware.org/?probe=b66cbe20f8) | Jun 01, 2023 |
| MSI           | PRO B650-P WIFI             | [0143308fee](https://linux-hardware.org/?probe=0143308fee) | Jun 01, 2023 |
| MSI           | H81M-E33                    | [50f664d550](https://linux-hardware.org/?probe=50f664d550) | Jun 01, 2023 |
| MSI           | H81M-E33                    | [eb2a33204c](https://linux-hardware.org/?probe=eb2a33204c) | Jun 01, 2023 |
| Gigabyte      | Z390 UD                     | [3cca879110](https://linux-hardware.org/?probe=3cca879110) | Jun 01, 2023 |
| HP            | 1906                        | [ac98480bd2](https://linux-hardware.org/?probe=ac98480bd2) | Jun 01, 2023 |
| ASUSTek       | P8H61/USB3                  | [d93dbf6db3](https://linux-hardware.org/?probe=d93dbf6db3) | Jun 01, 2023 |
| ASUSTek       | P8H61/USB3                  | [16c7ca187a](https://linux-hardware.org/?probe=16c7ca187a) | Jun 01, 2023 |
| Dell          | 0VNM11 A01                  | [308b943182](https://linux-hardware.org/?probe=308b943182) | Jun 01, 2023 |
| HP            | 18E7                        | [a3f557389e](https://linux-hardware.org/?probe=a3f557389e) | Jun 01, 2023 |
| ASRock        | H310M-HDV                   | [3dc5138ecd](https://linux-hardware.org/?probe=3dc5138ecd) | Jun 01, 2023 |
| ChangWang     | CW56-58                     | [e00e626ea6](https://linux-hardware.org/?probe=e00e626ea6) | Jun 01, 2023 |
| ASRock        | H170M Pro4                  | [d936c663d3](https://linux-hardware.org/?probe=d936c663d3) | Jun 01, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [e242ec473b](https://linux-hardware.org/?probe=e242ec473b) | Jun 01, 2023 |
| MSI           | H510M-A PRO                 | [8557cd4efa](https://linux-hardware.org/?probe=8557cd4efa) | Jun 01, 2023 |
| Gigabyte      | H61M-DS2                    | [1cf7ec0aa5](https://linux-hardware.org/?probe=1cf7ec0aa5) | Jun 01, 2023 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [abc4bba144](https://linux-hardware.org/?probe=abc4bba144) | Jun 01, 2023 |
| ASRock        | J3455M                      | [ca1db2cfb9](https://linux-hardware.org/?probe=ca1db2cfb9) | Jun 01, 2023 |
| HP            | 845A                        | [b68054952b](https://linux-hardware.org/?probe=b68054952b) | Jun 01, 2023 |
| Fujitsu Si... | D2740-A2 S26361-D2740-A2    | [165491db1f](https://linux-hardware.org/?probe=165491db1f) | Jun 01, 2023 |
| ASRock        | B450 Gaming K4              | [24ccc7665f](https://linux-hardware.org/?probe=24ccc7665f) | Jun 01, 2023 |
| Gigabyte      | B360M DS3H                  | [09b2200a7f](https://linux-hardware.org/?probe=09b2200a7f) | Jun 01, 2023 |
| Gigabyte      | H61M-DS2                    | [7f9d81bd57](https://linux-hardware.org/?probe=7f9d81bd57) | Jun 01, 2023 |
| ASRock        | B450 Gaming K4              | [af6c8f3355](https://linux-hardware.org/?probe=af6c8f3355) | Jun 01, 2023 |
| Gigabyte      | H410M S2H V3                | [78e4d7a22b](https://linux-hardware.org/?probe=78e4d7a22b) | Jun 01, 2023 |
| MSI           | 890FXA-GD70                 | [bcc4cd9597](https://linux-hardware.org/?probe=bcc4cd9597) | Jun 01, 2023 |
| ASUSTek       | H81M-C                      | [5fc6ec135b](https://linux-hardware.org/?probe=5fc6ec135b) | Jun 01, 2023 |
| Portwell      | CAPB-3000VR                 | [53558af2be](https://linux-hardware.org/?probe=53558af2be) | Jun 01, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [a13bd80e8a](https://linux-hardware.org/?probe=a13bd80e8a) | Jun 01, 2023 |
| Gigabyte      | B550M DS3H                  | [df7287f2c8](https://linux-hardware.org/?probe=df7287f2c8) | Jun 01, 2023 |
| ASUSTek       | B85M-E                      | [57f47246aa](https://linux-hardware.org/?probe=57f47246aa) | Jun 01, 2023 |
| Gigabyte      | B450 GAMING X               | [b92d2128ad](https://linux-hardware.org/?probe=b92d2128ad) | Jun 01, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | [fc4e2630c0](https://linux-hardware.org/?probe=fc4e2630c0) | Jun 01, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | [f02c7845e5](https://linux-hardware.org/?probe=f02c7845e5) | Jun 01, 2023 |
| ASUSTek       | Z97-P                       | [b819db60d1](https://linux-hardware.org/?probe=b819db60d1) | Jun 01, 2023 |
| Lenovo        | SHARKBAY NOK                | [108cb2ce17](https://linux-hardware.org/?probe=108cb2ce17) | Jun 01, 2023 |
| ASRock        | H81M-HDS                    | [775913e245](https://linux-hardware.org/?probe=775913e245) | Jun 01, 2023 |
| HP            | 339A                        | [24ab8463bb](https://linux-hardware.org/?probe=24ab8463bb) | Jun 01, 2023 |
| ASUSTek       | Z97-K                       | [1bd92e67d7](https://linux-hardware.org/?probe=1bd92e67d7) | Jun 01, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [9afffc17a1](https://linux-hardware.org/?probe=9afffc17a1) | Jun 01, 2023 |
| ASUSTek       | PRIME B550M-A               | [8799da8513](https://linux-hardware.org/?probe=8799da8513) | Jun 01, 2023 |
| ASRock        | X370 Pro4                   | [aaeac4c226](https://linux-hardware.org/?probe=aaeac4c226) | Jun 01, 2023 |
| ASUSTek       | ROG STRIX X299-E GAMING     | [216bea3b6f](https://linux-hardware.org/?probe=216bea3b6f) | Jun 01, 2023 |
| Supermicro    | X11SCD-F                    | [4646e2fe85](https://linux-hardware.org/?probe=4646e2fe85) | Jun 01, 2023 |
| Supermicro    | X11SCD-F                    | [80072f2519](https://linux-hardware.org/?probe=80072f2519) | Jun 01, 2023 |
| Supermicro    | X11SCD-F                    | [365eeba4c9](https://linux-hardware.org/?probe=365eeba4c9) | Jun 01, 2023 |
| Supermicro    | X12STD-F                    | [df7c4a738e](https://linux-hardware.org/?probe=df7c4a738e) | Jun 01, 2023 |
| Gigabyte      | J1900M-D2P                  | [0e89db7255](https://linux-hardware.org/?probe=0e89db7255) | Jun 01, 2023 |
| Supermicro    | X12STD-F                    | [8511ce89ad](https://linux-hardware.org/?probe=8511ce89ad) | Jun 01, 2023 |
| ASRock        | J4125-ITX                   | [31e0f624be](https://linux-hardware.org/?probe=31e0f624be) | Jun 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | [9a28272d6e](https://linux-hardware.org/?probe=9a28272d6e) | Jun 01, 2023 |
| ASRock        | N68C-S UCC                  | [ef4a96955c](https://linux-hardware.org/?probe=ef4a96955c) | Jun 01, 2023 |
| ASRock        | N68C-S UCC                  | [a106c6a98a](https://linux-hardware.org/?probe=a106c6a98a) | Jun 01, 2023 |
| Gigabyte      | B450M DS3H-CF               | [923c9a18ff](https://linux-hardware.org/?probe=923c9a18ff) | Jun 01, 2023 |
| ASRock        | B550 Pro4                   | [34e92ccc34](https://linux-hardware.org/?probe=34e92ccc34) | Jun 01, 2023 |
| HP            | 83E2                        | [eaf5f90360](https://linux-hardware.org/?probe=eaf5f90360) | Jun 01, 2023 |
| MSI           | X99A RAIDER                 | [b951e6223c](https://linux-hardware.org/?probe=b951e6223c) | Jun 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | [df9086deb4](https://linux-hardware.org/?probe=df9086deb4) | Jun 01, 2023 |
| Gigabyte      | EP45T-DS3                   | [0dd3baa28d](https://linux-hardware.org/?probe=0dd3baa28d) | Jun 01, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [976fcb80b0](https://linux-hardware.org/?probe=976fcb80b0) | Jun 01, 2023 |
| Dell          | 03NVJ6 A00                  | [1f295f3ec2](https://linux-hardware.org/?probe=1f295f3ec2) | Jun 01, 2023 |
| HP            | 212A                        | [a0e56b03e2](https://linux-hardware.org/?probe=a0e56b03e2) | Jun 01, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [259865e80e](https://linux-hardware.org/?probe=259865e80e) | Jun 01, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX DDR4    | [5f1045564e](https://linux-hardware.org/?probe=5f1045564e) | Jun 01, 2023 |
| Inventec      | D CLASS A02                 | [433df815db](https://linux-hardware.org/?probe=433df815db) | Jun 01, 2023 |
| HP            | 8055                        | [ff75f76129](https://linux-hardware.org/?probe=ff75f76129) | Jun 01, 2023 |
| HP            | 8055                        | [f54c954f94](https://linux-hardware.org/?probe=f54c954f94) | Jun 01, 2023 |
| OEM           | Intel H81                   | [b62ec659fa](https://linux-hardware.org/?probe=b62ec659fa) | Jun 01, 2023 |
| ASUSTek       | M3A78-T                     | [e59673dcf2](https://linux-hardware.org/?probe=e59673dcf2) | Jun 01, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [9faf2de183](https://linux-hardware.org/?probe=9faf2de183) | Jun 01, 2023 |
| MSI           | H110M PRO-VH PLUS           | [cfabc605f7](https://linux-hardware.org/?probe=cfabc605f7) | Jun 01, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [0586d2c0e2](https://linux-hardware.org/?probe=0586d2c0e2) | Jun 01, 2023 |
| ASUSTek       | P8Z77-V LE PLUS             | [d94ba8fb27](https://linux-hardware.org/?probe=d94ba8fb27) | Jun 01, 2023 |
| MSI           | P55-GD55                    | [1400fdf705](https://linux-hardware.org/?probe=1400fdf705) | May 31, 2023 |
| Acer          | WG43M                       | [cdd78e1cac](https://linux-hardware.org/?probe=cdd78e1cac) | May 31, 2023 |
| MSI           | MEG X670E ACE               | [8bc281486e](https://linux-hardware.org/?probe=8bc281486e) | May 31, 2023 |
| MSI           | PRO X670-P WIFI             | [10f4ef3e86](https://linux-hardware.org/?probe=10f4ef3e86) | May 31, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [01692ad602](https://linux-hardware.org/?probe=01692ad602) | May 31, 2023 |
| ASUSTek       | PRIME TRX40-PRO             | [6b3efa1ef7](https://linux-hardware.org/?probe=6b3efa1ef7) | May 31, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [270fcf5e69](https://linux-hardware.org/?probe=270fcf5e69) | May 31, 2023 |
| ASUSTek       | PRIME H510M-K               | [f6f91b620c](https://linux-hardware.org/?probe=f6f91b620c) | May 31, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [3b9639141c](https://linux-hardware.org/?probe=3b9639141c) | May 31, 2023 |
| Dell          | 0RY007                      | [b726df555b](https://linux-hardware.org/?probe=b726df555b) | May 31, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [417320253a](https://linux-hardware.org/?probe=417320253a) | May 31, 2023 |
| Dell          | 0RY007                      | [32e931c79b](https://linux-hardware.org/?probe=32e931c79b) | May 31, 2023 |
| HP            | 1497                        | [cc138de04b](https://linux-hardware.org/?probe=cc138de04b) | May 31, 2023 |
| Intel         | DB75EN AAG39650-302         | [9872e0cb5c](https://linux-hardware.org/?probe=9872e0cb5c) | May 31, 2023 |
| ASRock        | 970M Pro3                   | [58b09c521b](https://linux-hardware.org/?probe=58b09c521b) | May 31, 2023 |
| Pegatron      | 2ACB                        | [cfd38fc71a](https://linux-hardware.org/?probe=cfd38fc71a) | May 31, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | [32a85827df](https://linux-hardware.org/?probe=32a85827df) | May 31, 2023 |
| ASRock        | H81M-HDS R2.0               | [810f6b35ea](https://linux-hardware.org/?probe=810f6b35ea) | May 31, 2023 |
| Gigabyte      | Q87M-D2H                    | [7400ec0f1a](https://linux-hardware.org/?probe=7400ec0f1a) | May 31, 2023 |
| ASUSTek       | Z77-A                       | [a313036ec2](https://linux-hardware.org/?probe=a313036ec2) | May 31, 2023 |
| ASRock        | H110M-HDV R3.0              | [670044aef5](https://linux-hardware.org/?probe=670044aef5) | May 31, 2023 |
| MSI           | B85M-G43                    | [38fb05719a](https://linux-hardware.org/?probe=38fb05719a) | May 31, 2023 |
| MSI           | X370 GAMING PLUS            | [ba0b4e2430](https://linux-hardware.org/?probe=ba0b4e2430) | May 31, 2023 |
| ECS           | A890GXM-A2                  | [c207b5f41c](https://linux-hardware.org/?probe=c207b5f41c) | May 31, 2023 |
| ASUSTek       | PRIME A320M-K               | [ebd7782079](https://linux-hardware.org/?probe=ebd7782079) | May 31, 2023 |
| ASRock        | FM2A88X-ITX+                | [6a2cd16e95](https://linux-hardware.org/?probe=6a2cd16e95) | May 31, 2023 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | [c0ff761729](https://linux-hardware.org/?probe=c0ff761729) | May 31, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [79de4bed98](https://linux-hardware.org/?probe=79de4bed98) | May 31, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [953ee1ef05](https://linux-hardware.org/?probe=953ee1ef05) | May 31, 2023 |
| ASUSTek       | P5Q                         | [e936e44332](https://linux-hardware.org/?probe=e936e44332) | May 31, 2023 |
| ASUSTek       | Z97-DELUXE                  | [2723d218b7](https://linux-hardware.org/?probe=2723d218b7) | May 31, 2023 |
| ASUSTek       | P9X79                       | [c677ff5b2d](https://linux-hardware.org/?probe=c677ff5b2d) | May 31, 2023 |
| ASUSTek       | B85M-E                      | [08e31c6634](https://linux-hardware.org/?probe=08e31c6634) | May 31, 2023 |
| Foxconn       | 2ABF                        | [ca4691fd95](https://linux-hardware.org/?probe=ca4691fd95) | May 31, 2023 |
| Lenovo        | ThinkServer TS140           | [e8e3834bf8](https://linux-hardware.org/?probe=e8e3834bf8) | May 31, 2023 |
| Lenovo        | ThinkServer TS140           | [48cf9db6cd](https://linux-hardware.org/?probe=48cf9db6cd) | May 31, 2023 |
| ASUSTek       | P5G41T-M LX3                | [483bf9a882](https://linux-hardware.org/?probe=483bf9a882) | May 31, 2023 |
| ASUSTek       | PRIME Z390-A                | [9131b2b568](https://linux-hardware.org/?probe=9131b2b568) | May 31, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [eda1870d76](https://linux-hardware.org/?probe=eda1870d76) | May 31, 2023 |
| Gigabyte      | X99-UD7 WIFI-CF             | [955e65b76f](https://linux-hardware.org/?probe=955e65b76f) | May 31, 2023 |
| ASRock        | Z77 Extreme3                | [e45b1707bd](https://linux-hardware.org/?probe=e45b1707bd) | May 31, 2023 |
| MSI           | B450 TOMAHAWK               | [0ddd2982db](https://linux-hardware.org/?probe=0ddd2982db) | May 31, 2023 |
| MSI           | B450 TOMAHAWK               | [93d1ee7e2d](https://linux-hardware.org/?probe=93d1ee7e2d) | May 31, 2023 |
| MSI           | MAG B460 TOMAHAWK           | [8389c76bd3](https://linux-hardware.org/?probe=8389c76bd3) | May 31, 2023 |
| MSI           | B350M BAZOOKA               | [a494d94087](https://linux-hardware.org/?probe=a494d94087) | May 31, 2023 |
| ASUSTek       | PRIME B365M-A               | [0005e56720](https://linux-hardware.org/?probe=0005e56720) | May 31, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [16f1d67220](https://linux-hardware.org/?probe=16f1d67220) | May 31, 2023 |
| Gigabyte      | F2A78M-HD2                  | [c76d767402](https://linux-hardware.org/?probe=c76d767402) | May 31, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [6c3655186f](https://linux-hardware.org/?probe=6c3655186f) | May 31, 2023 |
| HP            | 158A                        | [39d4ab7307](https://linux-hardware.org/?probe=39d4ab7307) | May 31, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [1383313bbb](https://linux-hardware.org/?probe=1383313bbb) | May 31, 2023 |
| Gigabyte      | H270-HD3-CF                 | [d2912dfb69](https://linux-hardware.org/?probe=d2912dfb69) | May 31, 2023 |
| Dell          | 0T7D40 A01                  | [0c0dc06847](https://linux-hardware.org/?probe=0c0dc06847) | May 31, 2023 |
| ASRock        | A320D4-P1                   | [195945844b](https://linux-hardware.org/?probe=195945844b) | May 31, 2023 |
| ECS           | G31T-M9                     | [f227323587](https://linux-hardware.org/?probe=f227323587) | May 31, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [3718997542](https://linux-hardware.org/?probe=3718997542) | May 31, 2023 |
| ZOTAC         | Unknown                     | [0626de1b2a](https://linux-hardware.org/?probe=0626de1b2a) | May 31, 2023 |
| ASUSTek       | PRIME A320M-K               | [6bcba3e54d](https://linux-hardware.org/?probe=6bcba3e54d) | May 31, 2023 |
| Gigabyte      | GA-E6010N                   | [563074319d](https://linux-hardware.org/?probe=563074319d) | May 31, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d1f02a3055](https://linux-hardware.org/?probe=d1f02a3055) | May 31, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [54b872a39b](https://linux-hardware.org/?probe=54b872a39b) | May 31, 2023 |
| ASUSTek       | Maximus VIII RANGER         | [354e883340](https://linux-hardware.org/?probe=354e883340) | May 31, 2023 |
| ASRockRack    | X470D4U2-2T                 | [cffbd92b9f](https://linux-hardware.org/?probe=cffbd92b9f) | May 31, 2023 |
| ASUSTek       | G10DK                       | [75cde40262](https://linux-hardware.org/?probe=75cde40262) | May 31, 2023 |
| HP            | 8648                        | [11e777087a](https://linux-hardware.org/?probe=11e777087a) | May 31, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [2c6c547437](https://linux-hardware.org/?probe=2c6c547437) | May 31, 2023 |
| Dell          | 0N4YC8 A00                  | [4a3e8c4d6f](https://linux-hardware.org/?probe=4a3e8c4d6f) | May 31, 2023 |
| MSI           | X99A RAIDER                 | [3404cb6c67](https://linux-hardware.org/?probe=3404cb6c67) | May 31, 2023 |
| ASRock        | FM2A88X Extreme6+           | [4a908da319](https://linux-hardware.org/?probe=4a908da319) | May 31, 2023 |
| Lenovo        | 3730 SDK0T76463 WIN 3422... | [4dfacbbeb1](https://linux-hardware.org/?probe=4dfacbbeb1) | May 31, 2023 |
| ASRock        | G41M-VS3                    | [166031ba4d](https://linux-hardware.org/?probe=166031ba4d) | May 31, 2023 |
| ASRock        | G41M-VS3                    | [8f55c9aa98](https://linux-hardware.org/?probe=8f55c9aa98) | May 31, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [ad79be40f5](https://linux-hardware.org/?probe=ad79be40f5) | May 31, 2023 |
| AZW           | GTR V02                     | [bd1740c7b2](https://linux-hardware.org/?probe=bd1740c7b2) | May 31, 2023 |
| AZW           | GTR V02                     | [cab90f1838](https://linux-hardware.org/?probe=cab90f1838) | May 31, 2023 |
| Dell          | 01XK1W A00                  | [8a18b7bada](https://linux-hardware.org/?probe=8a18b7bada) | May 31, 2023 |
| Dell          | 01XK1W A00                  | [611cf59f44](https://linux-hardware.org/?probe=611cf59f44) | May 31, 2023 |
| ASRock        | B650E Steel Legend WiFi     | [88d16bf040](https://linux-hardware.org/?probe=88d16bf040) | May 31, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | [9d3023fd1d](https://linux-hardware.org/?probe=9d3023fd1d) | May 31, 2023 |
| Dell          | 07WP95 A01                  | [b9f3afed0c](https://linux-hardware.org/?probe=b9f3afed0c) | May 31, 2023 |
| Lenovo        | 3730 SDK0T76463 WIN 3422... | [da8705e5a7](https://linux-hardware.org/?probe=da8705e5a7) | May 31, 2023 |
| MSI           | B450M MORTAR MAX            | [1d0c56937c](https://linux-hardware.org/?probe=1d0c56937c) | May 31, 2023 |
| ASUSTek       | PRIME B450M-K II            | [2703e7856e](https://linux-hardware.org/?probe=2703e7856e) | May 30, 2023 |
| Intel         | X99                         | [cef654d9c5](https://linux-hardware.org/?probe=cef654d9c5) | May 30, 2023 |
| ASRock        | Q1900B-ITX                  | [88e4924fa2](https://linux-hardware.org/?probe=88e4924fa2) | May 30, 2023 |
| System76      | Thelio Mira                 | [d5fe3a3749](https://linux-hardware.org/?probe=d5fe3a3749) | May 30, 2023 |
| ASUSTek       | P4S8L                       | [c26269028e](https://linux-hardware.org/?probe=c26269028e) | May 30, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [698e3b5e35](https://linux-hardware.org/?probe=698e3b5e35) | May 30, 2023 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | [6dbaa9e2ff](https://linux-hardware.org/?probe=6dbaa9e2ff) | May 30, 2023 |
| ASUSTek       | PRIME A320M-R               | [2881299761](https://linux-hardware.org/?probe=2881299761) | May 30, 2023 |
| ASUSTek       | PRIME B450M-A               | [4833d37ec3](https://linux-hardware.org/?probe=4833d37ec3) | May 30, 2023 |
| Gigabyte      | B250-FinTech-CF             | [1903d991a3](https://linux-hardware.org/?probe=1903d991a3) | May 30, 2023 |
| Gigabyte      | Z97-HD3                     | [8505864d45](https://linux-hardware.org/?probe=8505864d45) | May 30, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [45e5adbb22](https://linux-hardware.org/?probe=45e5adbb22) | May 30, 2023 |
| ASRock        | H470M-HDV                   | [f73c3032af](https://linux-hardware.org/?probe=f73c3032af) | May 30, 2023 |
| ASRock        | H470M-HDV                   | [12fe930fb2](https://linux-hardware.org/?probe=12fe930fb2) | May 30, 2023 |
| Shenzhen M... | F7BFC                       | [c496e8a74f](https://linux-hardware.org/?probe=c496e8a74f) | May 30, 2023 |
| ASUSTek       | PRIME B550M-A               | [349eb108ab](https://linux-hardware.org/?probe=349eb108ab) | May 30, 2023 |
| Gigabyte      | Z270X-Gaming 7              | [4ed64d3d45](https://linux-hardware.org/?probe=4ed64d3d45) | May 30, 2023 |
| ASRock        | B450M Steel Legend          | [87c3dbc5df](https://linux-hardware.org/?probe=87c3dbc5df) | May 30, 2023 |
| TPV-INVENT... | 2AC6 A01                    | [1ac394c97c](https://linux-hardware.org/?probe=1ac394c97c) | May 30, 2023 |
| Intel         | STK2M3W64CC H89289-504      | [a7e599b1f5](https://linux-hardware.org/?probe=a7e599b1f5) | May 30, 2023 |
| ASRock        | B550M Steel Legend          | [ab97cb7f09](https://linux-hardware.org/?probe=ab97cb7f09) | May 30, 2023 |
| Gigabyte      | X399 AORUS PRO-CF           | [b00cd1c84e](https://linux-hardware.org/?probe=b00cd1c84e) | May 30, 2023 |
| ASRock        | H110M-DS/Hyper              | [a29a16d74c](https://linux-hardware.org/?probe=a29a16d74c) | May 30, 2023 |
| Intel         | STK2M3W64CC H89289-504      | [c471536b99](https://linux-hardware.org/?probe=c471536b99) | May 30, 2023 |
| Gigabyte      | M68MT-S2                    | [c56271ea6a](https://linux-hardware.org/?probe=c56271ea6a) | May 30, 2023 |
| Cincoze       | 1.0.01.001                  | [1552e93368](https://linux-hardware.org/?probe=1552e93368) | May 30, 2023 |
| MSI           | B350M PRO-VD PLUS           | [ca4e5a8f82](https://linux-hardware.org/?probe=ca4e5a8f82) | May 30, 2023 |
| Biostar       | B450MH                      | [36947ca7e1](https://linux-hardware.org/?probe=36947ca7e1) | May 30, 2023 |
| BESSTAR Te... | HM90                        | [cb78f83d80](https://linux-hardware.org/?probe=cb78f83d80) | May 30, 2023 |
| ASRock        | H110M-DS/Hyper              | [05e7ed23f3](https://linux-hardware.org/?probe=05e7ed23f3) | May 30, 2023 |
| Biostar       | H610MH                      | [708df29fd6](https://linux-hardware.org/?probe=708df29fd6) | May 30, 2023 |
| ASRock        | H310CM-HG4                  | [9fa8d9d320](https://linux-hardware.org/?probe=9fa8d9d320) | May 30, 2023 |
| ASRock        | B550 Phantom Gaming 4       | [c23ef58095](https://linux-hardware.org/?probe=c23ef58095) | May 30, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | [5271bd0b88](https://linux-hardware.org/?probe=5271bd0b88) | May 30, 2023 |
| MSI           | PRO Z790-A WIFI             | [676d83919f](https://linux-hardware.org/?probe=676d83919f) | May 30, 2023 |
| ASUSTek       | PRIME TRX40-PRO             | [4cbc2f9044](https://linux-hardware.org/?probe=4cbc2f9044) | May 30, 2023 |
| Dell          | 02N3WF A01                  | [c02695ea7d](https://linux-hardware.org/?probe=c02695ea7d) | May 30, 2023 |
| Gigabyte      | M68MT-S2                    | [a0ffb7fd40](https://linux-hardware.org/?probe=a0ffb7fd40) | May 30, 2023 |
| Gigabyte      | H61M-S2PV                   | [446d026ac1](https://linux-hardware.org/?probe=446d026ac1) | May 30, 2023 |
| Gigabyte      | B560M D3H                   | [8579e0281a](https://linux-hardware.org/?probe=8579e0281a) | May 30, 2023 |
| Lenovo        | 3098 SDK0E50510 WIN         | [2334995ee9](https://linux-hardware.org/?probe=2334995ee9) | May 30, 2023 |
| Dell          | 002KVM A01                  | [09d2d63c82](https://linux-hardware.org/?probe=09d2d63c82) | May 30, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [de30e713bf](https://linux-hardware.org/?probe=de30e713bf) | May 30, 2023 |
| Dell          | 07WP95 A01                  | [a58adc500e](https://linux-hardware.org/?probe=a58adc500e) | May 30, 2023 |
| MSI           | H55M-ED55                   | [a89bdc8ec0](https://linux-hardware.org/?probe=a89bdc8ec0) | May 30, 2023 |
| Gigabyte      | Z170-HD3P-CF                | [e51651a755](https://linux-hardware.org/?probe=e51651a755) | May 30, 2023 |
| HP            | 0B54h D                     | [c7813156eb](https://linux-hardware.org/?probe=c7813156eb) | May 30, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [d2ce08a746](https://linux-hardware.org/?probe=d2ce08a746) | May 30, 2023 |
| ASRock        | A320M-DVS R4.0              | [611b47056d](https://linux-hardware.org/?probe=611b47056d) | May 30, 2023 |
| ASUSTek       | P9X79                       | [dacfbfd038](https://linux-hardware.org/?probe=dacfbfd038) | May 30, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [c2d144c313](https://linux-hardware.org/?probe=c2d144c313) | May 30, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [4d7ccd868f](https://linux-hardware.org/?probe=4d7ccd868f) | May 30, 2023 |
| Intel         | DH61BF AAG81311-102         | [22123492ab](https://linux-hardware.org/?probe=22123492ab) | May 30, 2023 |
| Gigabyte      | H61M-S1                     | [5d33af1d5a](https://linux-hardware.org/?probe=5d33af1d5a) | May 30, 2023 |
| Gigabyte      | H61M-S1                     | [6872b07bb6](https://linux-hardware.org/?probe=6872b07bb6) | May 30, 2023 |
| HP            | 8307                        | [c8d0506eda](https://linux-hardware.org/?probe=c8d0506eda) | May 30, 2023 |
| Lenovo        | 3740 NOK                    | [c15d9d37c7](https://linux-hardware.org/?probe=c15d9d37c7) | May 30, 2023 |
| ASRock        | AB350M Pro4                 | [4f23de2827](https://linux-hardware.org/?probe=4f23de2827) | May 30, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [ffbccb8f47](https://linux-hardware.org/?probe=ffbccb8f47) | May 30, 2023 |
| MSI           | A68HM-E33 V2                | [24775c04a5](https://linux-hardware.org/?probe=24775c04a5) | May 30, 2023 |
| Dell          | 0H4VK7 A01                  | [35d979d6e9](https://linux-hardware.org/?probe=35d979d6e9) | May 30, 2023 |
| MSI           | A68HM-E33 V2                | [d6a2216b0f](https://linux-hardware.org/?probe=d6a2216b0f) | May 30, 2023 |
| Lenovo        | 36C5 SDK0Q55724 WIN 3273... | [01076d8e8b](https://linux-hardware.org/?probe=01076d8e8b) | May 30, 2023 |

...


System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Ubuntu 20.04       | 9562     | 10.9%   |
| Ubuntu 18.04       | 5379     | 6.13%   |
| Ubuntu 22.04       | 3293     | 3.75%   |
| Debian 11          | 2372     | 2.7%    |
| OpenMandriva 4.2   | 2268     | 2.58%   |
| ROSA R10           | 2140     | 2.44%   |
| ROSA R11           | 2088     | 2.38%   |
| OpenMandriva 4.3   | 2058     | 2.35%   |
| ROSA R8            | 1892     | 2.16%   |
| ROSA R6            | 1778     | 2.03%   |
| ROSA R7            | 1692     | 1.93%   |
| ROSA R8.1          | 1459     | 1.66%   |
| Arch Rolling       | 1433     | 1.63%   |
| ROSA R9            | 1277     | 1.46%   |
| BlackPanther 18.1  | 1242     | 1.42%   |
| Linux Mint 20.3    | 1186     | 1.35%   |
| ROSA R11.1         | 1174     | 1.34%   |
| KDE neon 20.04     | 1147     | 1.31%   |
| Manjaro            | 1145     | 1.3%    |
| Zorin 16           | 1130     | 1.29%   |
| Arch               | 1042     | 1.19%   |
| ROSA 12.2          | 1033     | 1.18%   |
| Pop!_OS 22.04      | 976      | 1.11%   |
| Linux Mint 20.1    | 913      | 1.04%   |
| Linux Mint 20.2    | 903      | 1.03%   |
| OpenMandriva 23.01 | 891      | 1.02%   |
| Linux Mint 19.3    | 863      | 0.98%   |
| Pop!_OS 20.04      | 859      | 0.98%   |
| Xubuntu 20.04      | 832      | 0.95%   |
| Linux Mint 21.1    | 793      | 0.9%    |
| Linux Mint 20      | 792      | 0.9%    |
| Debian 10          | 746      | 0.85%   |
| Ubuntu 19.04       | 745      | 0.85%   |
| Ubuntu 19.10       | 742      | 0.85%   |
| Ubuntu 20.10       | 736      | 0.84%   |
| ArcoLinux Rolling  | 724      | 0.83%   |
| Pop!_OS 21.04      | 718      | 0.82%   |
| Ubuntu 21.10       | 711      | 0.81%   |
| Fedora 36          | 682      | 0.78%   |
| Pop!_OS 20.10      | 672      | 0.77%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 22046    | 27.26%  |
| ROSA          | 13176    | 16.29%  |
| Linux Mint    | 6446     | 7.97%   |
| OpenMandriva  | 6206     | 7.67%   |
| Debian        | 3750     | 4.64%   |
| Fedora        | 3673     | 4.54%   |
| Pop!_OS       | 3459     | 4.28%   |
| Manjaro       | 2538     | 3.14%   |
| Arch          | 2426     | 3%      |
| Zorin         | 1752     | 2.17%   |
| Xubuntu       | 1593     | 1.97%   |
| KDE neon      | 1512     | 1.87%   |
| Kubuntu       | 1397     | 1.73%   |
| BlackPanther  | 1302     | 1.61%   |
| openSUSE      | 803      | 0.99%   |
| ArcoLinux     | 783      | 0.97%   |
| Gentoo        | 662      | 0.82%   |
| Endless       | 654      | 0.81%   |
| Ubuntu MATE   | 540      | 0.67%   |
| Ubuntu Unity  | 450      | 0.56%   |
| Elementary    | 410      | 0.51%   |
| Lubuntu       | 400      | 0.49%   |
| CentOS        | 337      | 0.42%   |
| EndeavourOS   | 311      | 0.38%   |
| Clear Linux   | 302      | 0.37%   |
| LMDE          | 277      | 0.34%   |
| Kali          | 263      | 0.33%   |
| Nobara        | 243      | 0.3%    |
| ALT Linux     | 233      | 0.29%   |
| MX            | 187      | 0.23%   |
| Ubuntu Budgie | 179      | 0.22%   |
| Garuda Linux  | 166      | 0.21%   |
| Red OS        | 145      | 0.18%   |
| RED           | 125      | 0.15%   |
| Parrot        | 104      | 0.13%   |
| Peppermint    | 97       | 0.12%   |
| SteamOS       | 88       | 0.11%   |
| LinuxFX       | 88       | 0.11%   |
| RHEL          | 84       | 0.1%    |
| Ubuntu Studio | 77       | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Desktops | Percent |
|------------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002           | 2200     | 2.26%   |
| 5.16.7-desktop-1omv4003            | 1936     | 1.99%   |
| 5.4.0-42-generic                   | 1389     | 1.42%   |
| 4.9.60-nrj-desktop-1rosa-x86_64    | 1048     | 1.07%   |
| 4.18.16-desktop-1bP                | 960      | 0.98%   |
| 3.14.44-nrj-desktop-2rosa-x86_64   | 951      | 0.98%   |
| 4.9.20-nrj-desktop-1rosa-x86_64    | 947      | 0.97%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 921      | 0.94%   |
| 4.15.0-desktop-45.1rosa-x86_64     | 917      | 0.94%   |
| 4.1.25-nrj-desktop-1rosa-x86_64    | 863      | 0.88%   |
| 6.1.1-desktop-1omv2290             | 805      | 0.83%   |
| 4.1.15-nrj-desktop-1rosa-x86_64    | 745      | 0.76%   |
| 5.15.0-56-generic                  | 725      | 0.74%   |
| 5.4.0-58-generic                   | 695      | 0.71%   |
| 5.4.0-52-generic                   | 633      | 0.65%   |
| 5.4.0-48-generic                   | 629      | 0.65%   |
| 6.2.6-desktop-1omv2390             | 627      | 0.64%   |
| 5.15.0-52-generic                  | 530      | 0.54%   |
| 5.15.0-58-generic                  | 527      | 0.54%   |
| 5.10.0-7-amd64                     | 517      | 0.53%   |
| 5.4.0-26-generic                   | 508      | 0.52%   |
| 4.1.34-nrj-desktop-2rosa-x86_64    | 500      | 0.51%   |
| 5.4.0-40-generic                   | 450      | 0.46%   |
| 5.15.0-46-generic                  | 438      | 0.45%   |
| 3.14.44-nrj-desktop-2rosa-i586     | 437      | 0.45%   |
| 5.3.0-40-generic                   | 427      | 0.44%   |
| 4.9.124-nrj-desktop-1rosa-x86_64   | 413      | 0.42%   |
| 5.4.0-29-generic                   | 411      | 0.42%   |
| 5.4.0-54-generic                   | 409      | 0.42%   |
| 5.15.0-48-generic                  | 401      | 0.41%   |
| 5.4.0-37-generic                   | 399      | 0.41%   |
| 5.4.0-65-generic                   | 375      | 0.38%   |
| 5.11.0-27-generic                  | 373      | 0.38%   |
| 5.3.0-28-generic                   | 370      | 0.38%   |
| 5.3.0-46-generic                   | 361      | 0.37%   |
| 5.19.0-35-generic                  | 355      | 0.36%   |
| 4.1.38-nrj-desktop-2rosa-x86_64    | 351      | 0.36%   |
| 5.6.14-desktop-2bP                 | 350      | 0.36%   |
| 5.13.0-39-generic                  | 346      | 0.35%   |
| 5.8.0-43-generic                   | 345      | 0.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 13090    | 14.28%  |
| 4.15.0  | 6622     | 7.22%   |
| 5.15.0  | 5784     | 6.31%   |
| 5.8.0   | 3867     | 4.22%   |
| 5.11.0  | 3639     | 3.97%   |
| 5.13.0  | 3055     | 3.33%   |
| 5.3.0   | 2769     | 3.02%   |
| 5.10.0  | 2455     | 2.68%   |
| 5.10.14 | 2220     | 2.42%   |
| 5.0.0   | 1974     | 2.15%   |
| 5.16.7  | 1955     | 2.13%   |
| 5.19.0  | 1929     | 2.1%    |
| 4.18.0  | 1537     | 1.68%   |
| 3.14.44 | 1382     | 1.51%   |
| 4.9.60  | 1298     | 1.42%   |
| 4.9.20  | 1247     | 1.36%   |
| 4.1.25  | 1162     | 1.27%   |
| 4.18.16 | 984      | 1.07%   |
| 4.1.15  | 961      | 1.05%   |
| 5.10.74 | 937      | 1.02%   |
| 6.1.1   | 901      | 0.98%   |
| 6.2.6   | 874      | 0.95%   |
| 4.19.0  | 792      | 0.86%   |
| 4.1.34  | 690      | 0.75%   |
| 4.1.38  | 588      | 0.64%   |
| 4.9.9   | 503      | 0.55%   |
| 4.9.124 | 490      | 0.53%   |
| 5.6.14  | 387      | 0.42%   |
| 4.9.155 | 365      | 0.4%    |
| 4.1.16  | 329      | 0.36%   |
| 4.9.76  | 327      | 0.36%   |
| 4.9.41  | 308      | 0.34%   |
| 5.17.5  | 305      | 0.33%   |
| 6.1.0   | 303      | 0.33%   |
| 6.0.12  | 296      | 0.32%   |
| 5.4.32  | 293      | 0.32%   |
| 4.4.0   | 263      | 0.29%   |
| 6.2.0   | 253      | 0.28%   |
| 5.4.83  | 246      | 0.27%   |
| 5.12.4  | 236      | 0.26%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 14578    | 16.41%  |
| 5.15    | 8192     | 9.22%   |
| 5.10    | 7201     | 8.1%    |
| 4.15    | 6656     | 7.49%   |
| 5.8     | 4841     | 5.45%   |
| 4.9     | 4513     | 5.08%   |
| 5.11    | 4414     | 4.97%   |
| 4.1     | 3927     | 4.42%   |
| 5.13    | 3658     | 4.12%   |
| 5.3     | 3164     | 3.56%   |
| 5.16    | 3017     | 3.4%    |
| 5.19    | 2736     | 3.08%   |
| 4.18    | 2566     | 2.89%   |
| 6.1     | 2392     | 2.69%   |
| 5.0     | 2106     | 2.37%   |
| 6.2     | 1899     | 2.14%   |
| 3.14    | 1774     | 2%      |
| 6.0     | 1463     | 1.65%   |
| 5.18    | 1083     | 1.22%   |
| 5.6     | 1082     | 1.22%   |
| 5.17    | 1019     | 1.15%   |
| 4.19    | 998      | 1.12%   |
| 5.9     | 894      | 1.01%   |
| 5.14    | 843      | 0.95%   |
| 5.12    | 778      | 0.88%   |
| 5.7     | 664      | 0.75%   |
| 5.5     | 364      | 0.41%   |
| 4.4     | 345      | 0.39%   |
| 6.3     | 332      | 0.37%   |
| 3.10    | 247      | 0.28%   |
| 5.2     | 161      | 0.18%   |
| 5.1     | 132      | 0.15%   |
| 4.13    | 122      | 0.14%   |
| 4.14    | 91       | 0.1%    |
| 4.12    | 84       | 0.09%   |
| 4.8     | 67       | 0.08%   |
| 4.10    | 65       | 0.07%   |
| 4.20    | 62       | 0.07%   |
| 4.16    | 44       | 0.05%   |
| 4.17    | 40       | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| x86_64      | 73878    | 94.42%  |
| i686        | 4296     | 5.49%   |
| armv7l      | 11       | 0.01%   |
| ppc64       | 10       | 0.01%   |
| riscv64     | 8        | 0.01%   |
| aarch64     | 8        | 0.01%   |
| ppc64le     | 5        | 0.01%   |
| ppc         | 5        | 0.01%   |
| e2k         | 4        | 0.01%   |
| mips64      | 3        | 0.004%  |
| i586        | 3        | 0.004%  |
| loongarch64 | 2        | 0.003%  |
| armv5tel    | 2        | 0.003%  |
| unknow      | 1        | 0.001%  |
| sparc64     | 1        | 0.001%  |
| sh4a        | 1        | 0.001%  |
| s390x       | 1        | 0.001%  |
| armv6l      | 1        | 0.001%  |
| Unknown     | 1        | 0.001%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| GNOME             | 28104    | 34.16%  |
| KDE5              | 16542    | 20.11%  |
| Unknown           | 9609     | 11.68%  |
| KDE4              | 9326     | 11.34%  |
| XFCE              | 4828     | 5.87%   |
| X-Cinnamon        | 4824     | 5.86%   |
| MATE              | 2196     | 2.67%   |
| KDE               | 1914     | 2.33%   |
| Cinnamon          | 945      | 1.15%   |
| LXQt              | 898      | 1.09%   |
| Unity             | 453      | 0.55%   |
| Pantheon          | 396      | 0.48%   |
| LXDE              | 375      | 0.46%   |
| Budgie            | 321      | 0.39%   |
| i3                | 310      | 0.38%   |
| Deepin            | 185      | 0.22%   |
| GNOME Flashback   | 168      | 0.2%    |
| GNUstep           | 129      | 0.16%   |
| GNOME Classic     | 113      | 0.14%   |
| awesome           | 82       | 0.1%    |
| Openbox           | 72       | 0.09%   |
| sway              | 54       | 0.07%   |
| bspwm             | 50       | 0.06%   |
| qtile             | 44       | 0.05%   |
| lightdm-xsession  | 38       | 0.05%   |
| Hyprland          | 36       | 0.04%   |
| Trinity           | 31       | 0.04%   |
| DWM               | 30       | 0.04%   |
| xmonad            | 28       | 0.03%   |
| Enlightenment     | 21       | 0.03%   |
| LeftWM            | 20       | 0.02%   |
| icewm             | 20       | 0.02%   |
| chadwm            | 10       | 0.01%   |
| i3-with-shmlog    | 8        | 0.01%   |
| herbstluftwm      | 6        | 0.01%   |
| Yaru:ubuntu:GNOME | 5        | 0.01%   |
| fly               | 5        | 0.01%   |
| fluxbox           | 5        | 0.01%   |
| UKUI              | 4        | 0.005%  |
| fvwm              | 4        | 0.005%  |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| X11         | 64524    | 80.51%  |
| Wayland     | 8834     | 11.02%  |
| Unknown     | 4829     | 6.03%   |
| Tty         | 1937     | 2.42%   |
| Web         | 20       | 0.02%   |
| Unspecified | 4        | 0.005%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 35466    | 43.43%  |
| SDDM    | 15278    | 18.71%  |
| KDM     | 9410     | 11.52%  |
| GDM     | 6990     | 8.56%   |
| GDM3    | 6183     | 7.57%   |
| LightDM | 5625     | 6.89%   |
| TDM     | 2294     | 2.81%   |
| XDM     | 128      | 0.16%   |
| SLiM    | 96       | 0.12%   |
| LXDM    | 58       | 0.07%   |
| MDM     | 45       | 0.06%   |
| Ly      | 37       | 0.05%   |
| GREETD  | 17       | 0.02%   |
| NODM    | 12       | 0.01%   |
| FLY-DM  | 6        | 0.01%   |
| SLIMSKI | 5        | 0.01%   |
| WDM     | 2        | 0.002%  |
| XINIT   | 1        | 0.001%  |
| SU      | 1        | 0.001%  |
| LYNDE   | 1        | 0.001%  |
| LY-DM   | 1        | 0.001%  |
| LDM     | 1        | 0.001%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 24525    | 30.55%  |
| Unknown | 18997    | 23.67%  |
| ru_RU   | 5921     | 7.38%   |
| de_DE   | 5352     | 6.67%   |
| pt_BR   | 3111     | 3.88%   |
| en_GB   | 3092     | 3.85%   |
| fr_FR   | 2829     | 3.52%   |
| it_IT   | 1753     | 2.18%   |
| es_ES   | 1412     | 1.76%   |
| en_CA   | 1411     | 1.76%   |
| C       | 1103     | 1.37%   |
| pl_PL   | 1075     | 1.34%   |
| en_AU   | 1063     | 1.32%   |
| en_IN   | 604      | 0.75%   |
| nl_NL   | 521      | 0.65%   |
| es_AR   | 472      | 0.59%   |
| es_MX   | 390      | 0.49%   |
| hu_HU   | 366      | 0.46%   |
| cs_CZ   | 363      | 0.45%   |
| de_AT   | 315      | 0.39%   |
| ja_JP   | 272      | 0.34%   |
| en_ZA   | 245      | 0.31%   |
| sv_SE   | 244      | 0.3%    |
| pt_PT   | 244      | 0.3%    |
| ru_UA   | 213      | 0.27%   |
| zh_CN   | 205      | 0.26%   |
| fi_FI   | 197      | 0.25%   |
| de_CH   | 186      | 0.23%   |
| fr_CA   | 179      | 0.22%   |
| tr_TR   | 177      | 0.22%   |
| en_NZ   | 177      | 0.22%   |
| el_GR   | 161      | 0.2%    |
| en_IE   | 136      | 0.17%   |
| es_CO   | 135      | 0.17%   |
| fr_BE   | 131      | 0.16%   |
| nl_BE   | 129      | 0.16%   |
| es_CL   | 120      | 0.15%   |
| uk_UA   | 110      | 0.14%   |
| sk_SK   | 109      | 0.14%   |
| ro_RO   | 104      | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 51143    | 64.06%  |
| EFI  | 28689    | 35.94%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Desktops | Percent |
|---------------------|----------|---------|
| Ext4                | 54508    | 67.43%  |
| Unknown             | 10182    | 12.6%   |
| Overlay             | 7797     | 9.65%   |
| Btrfs               | 5437     | 6.73%   |
| Xfs                 | 1182     | 1.46%   |
| Zfs                 | 566      | 0.7%    |
| Tmpfs               | 506      | 0.63%   |
| Ext2                | 211      | 0.26%   |
| Ext3                | 209      | 0.26%   |
| F2fs                | 112      | 0.14%   |
| Reiserfs            | 28       | 0.03%   |
| Aufs                | 26       | 0.03%   |
| Jfs                 | 21       | 0.03%   |
| Rootfs              | 13       | 0.02%   |
| XXXXXXX             | 9        | 0.01%   |
| SAMSUNG             | 6        | 0.01%   |
| XXXX                | 3        | 0.004%  |
| XXXXX               | 2        | 0.002%  |
| XXX4                | 2        | 0.002%  |
| XXX                 | 2        | 0.002%  |
| ExX4                | 2        | 0.002%  |
| XXXfs               | 1        | 0.001%  |
| SquXshfs            | 1        | 0.001%  |
| Fuse.sshfs          | 1        | 0.001%  |
| Fuse.snapfuse       | 1        | 0.001%  |
| Fuse.fuse-overlayfs | 1        | 0.001%  |
| Exfat               | 1        | 0.001%  |
| 2G                  | 1        | 0.001%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 38340    | 47.4%   |
| GPT     | 24553    | 30.36%  |
| MBR     | 17992    | 22.24%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 64646    | 80.53%  |
| Yes       | 15633    | 19.47%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 53570    | 66.75%  |
| Yes       | 26690    | 33.25%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 21611    | 27.76%  |
| Gigabyte Technology | 14191    | 18.23%  |
| MSI                 | 8982     | 11.54%  |
| ASRock              | 7481     | 9.61%   |
| Dell                | 5594     | 7.19%   |
| Hewlett-Packard     | 4833     | 6.21%   |
| Lenovo              | 2232     | 2.87%   |
| Intel               | 2136     | 2.74%   |
| Acer                | 1286     | 1.65%   |
| Unknown             | 1007     | 1.29%   |
| Foxconn             | 807      | 1.04%   |
| Biostar             | 778      | 1%      |
| ECS                 | 774      | 0.99%   |
| Pegatron            | 769      | 0.99%   |
| Fujitsu             | 669      | 0.86%   |
| Medion              | 356      | 0.46%   |
| Supermicro          | 233      | 0.3%    |
| Fujitsu Siemens     | 213      | 0.27%   |
| Apple               | 197      | 0.25%   |
| Huanan              | 193      | 0.25%   |
| Positivo            | 192      | 0.25%   |
| Packard Bell        | 160      | 0.21%   |
| Shuttle             | 153      | 0.2%    |
| Alienware           | 150      | 0.19%   |
| AZW                 | 120      | 0.15%   |
| Gateway             | 115      | 0.15%   |
| PCWare              | 114      | 0.15%   |
| eMachines           | 110      | 0.14%   |
| BESSTAR Tech        | 107      | 0.14%   |
| OEM                 | 79       | 0.1%    |
| AMI                 | 77       | 0.1%    |
| ASRockRack          | 71       | 0.09%   |
| EVGA                | 67       | 0.09%   |
| ABIT                | 63       | 0.08%   |
| IBM                 | 49       | 0.06%   |
| System76            | 48       | 0.06%   |
| AMD                 | 48       | 0.06%   |
| Semp Toshiba        | 46       | 0.06%   |
| Inventec            | 44       | 0.06%   |
| Itautec             | 43       | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| ASUS All Series              | 1990     | 2.56%   |
| Unknown                      | 1110     | 1.43%   |
| Dell OptiPlex 7010           | 384      | 0.49%   |
| ASUS TUF Gaming X570-PLUS    | 346      | 0.44%   |
| MSI MS-7C37                  | 344      | 0.44%   |
| Gigabyte B450M DS3H          | 316      | 0.41%   |
| MSI MS-7C02                  | 305      | 0.39%   |
| ASUS PRIME A320M-K           | 291      | 0.37%   |
| MSI MS-7817                  | 280      | 0.36%   |
| Dell OptiPlex 9020           | 266      | 0.34%   |
| Gigabyte 970A-DS3P           | 260      | 0.33%   |
| MSI MS-7B86                  | 241      | 0.31%   |
| Dell OptiPlex 780            | 233      | 0.3%    |
| ASUS M5A78L-M/USB3           | 223      | 0.29%   |
| Dell OptiPlex 790            | 221      | 0.28%   |
| MSI MS-7721                  | 218      | 0.28%   |
| MSI MS-7693                  | 216      | 0.28%   |
| ASUS M5A97 R2.0              | 211      | 0.27%   |
| MSI MS-7A38                  | 198      | 0.25%   |
| ASRock B450M Pro4            | 195      | 0.25%   |
| ASUS PRIME B450M-A           | 194      | 0.25%   |
| Dell OptiPlex 3020           | 192      | 0.25%   |
| ASUS ROG STRIX B450-F GAMING | 188      | 0.24%   |
| MSI MS-7B79                  | 186      | 0.24%   |
| MSI MS-7C91                  | 180      | 0.23%   |
| HP Compaq Elite 8300 SFF     | 180      | 0.23%   |
| ASUS ROG STRIX B550-F GAMING | 180      | 0.23%   |
| Dell OptiPlex 755            | 173      | 0.22%   |
| Gigabyte A320M-S2H           | 167      | 0.21%   |
| Gigabyte G31M-ES2L           | 158      | 0.2%    |
| Dell OptiPlex 3010           | 154      | 0.2%    |
| MSI MS-7C56                  | 152      | 0.2%    |
| MSI MS-7B89                  | 146      | 0.19%   |
| ASRock N68C-S UCC            | 145      | 0.19%   |
| HP EliteDesk 800 G1 SFF      | 143      | 0.18%   |
| ASUS PRIME B350-PLUS         | 142      | 0.18%   |
| MSI MS-7A34                  | 139      | 0.18%   |
| Dell OptiPlex 990            | 139      | 0.18%   |
| ASUS SABERTOOTH 990FX R2.0   | 139      | 0.18%   |
| ASUS M5A97 LE R2.0           | 139      | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 3309     | 4.25%   |
| ASUS PRIME             | 3306     | 4.25%   |
| ASUS ROG               | 2066     | 2.65%   |
| ASUS All               | 1990     | 2.56%   |
| HP Compaq              | 1822     | 2.34%   |
| Lenovo ThinkCentre     | 1352     | 1.74%   |
| ASUS TUF               | 1346     | 1.73%   |
| Unknown                | 1110     | 1.43%   |
| Dell Precision         | 823      | 1.06%   |
| Acer Aspire            | 800      | 1.03%   |
| ASUS M5A78L-M          | 710      | 0.91%   |
| Gigabyte X570          | 597      | 0.77%   |
| Dell Inspiron          | 565      | 0.73%   |
| HP EliteDesk           | 559      | 0.72%   |
| Gigabyte B450M         | 553      | 0.71%   |
| ASUS P8H61-M           | 515      | 0.66%   |
| ASUS M5A97             | 495      | 0.64%   |
| Gigabyte B450          | 479      | 0.62%   |
| Fujitsu ESPRIMO        | 448      | 0.58%   |
| HP ProDesk             | 431      | 0.55%   |
| ASUS P8Z77-V           | 390      | 0.5%    |
| ASRock B450M           | 362      | 0.47%   |
| MSI MS-7C37            | 344      | 0.44%   |
| ASUS SABERTOOTH        | 333      | 0.43%   |
| MSI MS-7C02            | 305      | 0.39%   |
| ASUS P5KPL-AM          | 300      | 0.39%   |
| Acer Veriton           | 295      | 0.38%   |
| Gigabyte GA-78LMT-USB3 | 292      | 0.38%   |
| ASUS P5G41T-M          | 285      | 0.37%   |
| Gigabyte B550          | 282      | 0.36%   |
| Dell XPS               | 281      | 0.36%   |
| MSI MS-7817            | 280      | 0.36%   |
| Gigabyte 970A-DS3P     | 278      | 0.36%   |
| Dell Vostro            | 277      | 0.36%   |
| Gigabyte Z390          | 259      | 0.33%   |
| ASUS P5K               | 256      | 0.33%   |
| Lenovo IdeaCentre      | 253      | 0.33%   |
| HP Pavilion            | 246      | 0.32%   |
| ASRock B450            | 243      | 0.31%   |
| ASRock X570            | 242      | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2012    | 8088     | 10.39%  |
| 2018    | 7431     | 9.55%   |
| 2013    | 6410     | 8.23%   |
| 2011    | 6133     | 7.88%   |
| 2019    | 5265     | 6.76%   |
| 2009    | 5051     | 6.49%   |
| 2010    | 4954     | 6.36%   |
| 2020    | 4751     | 6.1%    |
| 2014    | 4658     | 5.98%   |
| 2017    | 4499     | 5.78%   |
| 2008    | 3856     | 4.95%   |
| 2015    | 3331     | 4.28%   |
| 2007    | 3251     | 4.18%   |
| 2016    | 3069     | 3.94%   |
| 2021    | 2766     | 3.55%   |
| 2006    | 1784     | 2.29%   |
| 2022    | 1162     | 1.49%   |
| 2005    | 726      | 0.93%   |
| 2004    | 236      | 0.3%    |
| Unknown | 132      | 0.17%   |
| 2003    | 129      | 0.17%   |
| 2023    | 107      | 0.14%   |
| 2002    | 31       | 0.04%   |
| 2001    | 17       | 0.02%   |
| 2000    | 9        | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 77846    | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 76347    | 97.76%  |
| Enabled  | 1746     | 2.24%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 77773    | 99.9%   |
| Yes  | 74       | 0.1%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 17266    | 21.5%   |
| 8.01-16.0       | 15793    | 19.67%  |
| 3.01-4.0        | 14411    | 17.95%  |
| 4.01-8.0        | 11491    | 14.31%  |
| 32.01-64.0      | 9722     | 12.11%  |
| 1.01-2.0        | 3725     | 4.64%   |
| 64.01-256.0     | 3225     | 4.02%   |
| 2.01-3.0        | 1998     | 2.49%   |
| 24.01-32.0      | 1732     | 2.16%   |
| 0.51-1.0        | 570      | 0.71%   |
| Unknown         | 190      | 0.24%   |
| More than 256.0 | 112      | 0.14%   |
| 0.01-0.5        | 57       | 0.07%   |
| 0               | 1        | 0.001%  |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB         | Desktops | Percent |
|-----------------|----------|---------|
| 1.01-2.0        | 31721    | 35.88%  |
| 2.01-3.0        | 17937    | 20.29%  |
| 0.51-1.0        | 12371    | 13.99%  |
| 4.01-8.0        | 10607    | 12%     |
| 3.01-4.0        | 8897     | 10.06%  |
| 8.01-16.0       | 3392     | 3.84%   |
| 0.01-0.5        | 1967     | 2.22%   |
| 16.01-24.0      | 697      | 0.79%   |
| Unknown         | 263      | 0.3%    |
| 24.01-32.0      | 250      | 0.28%   |
| 32.01-64.0      | 237      | 0.27%   |
| 64.01-256.0     | 61       | 0.07%   |
| 0               | 4        | 0.005%  |
| More than 256.0 | 2        | 0.002%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 33737    | 40.97%  |
| 2       | 23254    | 28.24%  |
| 3       | 12309    | 14.95%  |
| 4       | 6399     | 7.77%   |
| 5       | 3035     | 3.69%   |
| 6       | 1375     | 1.67%   |
| 0       | 746      | 0.91%   |
| 7       | 659      | 0.8%    |
| 8       | 311      | 0.38%   |
| 9       | 180      | 0.22%   |
| 10      | 91       | 0.11%   |
| 11      | 70       | 0.09%   |
| 12      | 36       | 0.04%   |
| 13      | 31       | 0.04%   |
| Unknown | 24       | 0.03%   |
| 14      | 13       | 0.02%   |
| 20      | 7        | 0.01%   |
| 17      | 7        | 0.01%   |
| 16      | 7        | 0.01%   |
| 15      | 7        | 0.01%   |
| 25      | 5        | 0.01%   |
| 18      | 5        | 0.01%   |
| 21      | 4        | 0.005%  |
| 24      | 3        | 0.004%  |
| 23      | 3        | 0.004%  |
| 22      | 3        | 0.004%  |
| 19      | 3        | 0.004%  |
| 28      | 2        | 0.002%  |
| 27      | 2        | 0.002%  |
| 71      | 1        | 0.001%  |
| 68      | 1        | 0.001%  |
| 51      | 1        | 0.001%  |
| 46      | 1        | 0.001%  |
| 45      | 1        | 0.001%  |
| 38      | 1        | 0.001%  |
| 32      | 1        | 0.001%  |
| 29      | 1        | 0.001%  |
| 26      | 1        | 0.001%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 39754    | 50.12%  |
| No        | 39568    | 49.88%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 77049    | 98.96%  |
| No        | 806      | 1.04%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 48705    | 61.47%  |
| Yes       | 30531    | 38.53%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 58962    | 74.51%  |
| Yes       | 20166    | 25.49%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 12675    | 16.07%  |
| Russia       | 11982    | 15.19%  |
| Germany      | 7452     | 9.45%   |
| Brazil       | 4614     | 5.85%   |
| Unknown      | 4135     | 5.24%   |
| France       | 3436     | 4.36%   |
| UK           | 2854     | 3.62%   |
| Italy        | 2592     | 3.29%   |
| Canada       | 2400     | 3.04%   |
| Spain        | 1919     | 2.43%   |
| Poland       | 1696     | 2.15%   |
| Hungary      | 1508     | 1.91%   |
| Australia    | 1390     | 1.76%   |
| Netherlands  | 1330     | 1.69%   |
| Ukraine      | 1318     | 1.67%   |
| India        | 934      | 1.18%   |
| Switzerland  | 802      | 1.02%   |
| Sweden       | 782      | 0.99%   |
| Argentina    | 742      | 0.94%   |
| Austria      | 691      | 0.88%   |
| Mexico       | 682      | 0.86%   |
| Czechia      | 621      | 0.79%   |
| Belgium      | 618      | 0.78%   |
| Finland      | 591      | 0.75%   |
| Greece       | 522      | 0.66%   |
| Romania      | 508      | 0.64%   |
| Japan        | 501      | 0.64%   |
| Portugal     | 425      | 0.54%   |
| Turkey       | 402      | 0.51%   |
| China        | 393      | 0.5%    |
| South Africa | 377      | 0.48%   |
| Norway       | 342      | 0.43%   |
| Bulgaria     | 338      | 0.43%   |
| Belarus      | 331      | 0.42%   |
| Denmark      | 314      | 0.4%    |
| Serbia       | 305      | 0.39%   |
| New Zealand  | 282      | 0.36%   |
| Indonesia    | 282      | 0.36%   |
| Slovakia     | 267      | 0.34%   |
| Israel       | 261      | 0.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Unknown           | 4156     | 4.93%   |
| Moscow            | 2073     | 2.46%   |
| St Petersburg     | 831      | 0.99%   |
| Voronezh          | 810      | 0.96%   |
| Sao Paulo         | 633      | 0.75%   |
| Berlin            | 609      | 0.72%   |
| Budapest          | 530      | 0.63%   |
| Paris             | 438      | 0.52%   |
| Pecherskoye       | 421      | 0.5%    |
| Vienna            | 392      | 0.46%   |
| Novosibirsk       | 391      | 0.46%   |
| Sydney            | 386      | 0.46%   |
| Warsaw            | 350      | 0.41%   |
| Hamburg           | 332      | 0.39%   |
| Yekaterinburg     | 328      | 0.39%   |
| Rio de Janeiro    | 316      | 0.37%   |
| Milan             | 311      | 0.37%   |
| Rome              | 305      | 0.36%   |
| Madrid            | 300      | 0.36%   |
| Munich            | 294      | 0.35%   |
| Krasnodar         | 280      | 0.33%   |
| Zurich            | 276      | 0.33%   |
| Athens            | 276      | 0.33%   |
| Melbourne         | 275      | 0.33%   |
| Kyiv              | 264      | 0.31%   |
| Amsterdam         | 257      | 0.3%    |
| Samara            | 252      | 0.3%    |
| Frankfurt am Main | 252      | 0.3%    |
| Nizhniy Novgorod  | 245      | 0.29%   |
| Toronto           | 244      | 0.29%   |
| Helsinki          | 238      | 0.28%   |
| Montreal          | 230      | 0.27%   |
| Rostov-on-Don     | 228      | 0.27%   |
| Brisbane          | 211      | 0.25%   |
| Perm              | 204      | 0.24%   |
| Barcelona         | 199      | 0.24%   |
| London            | 198      | 0.23%   |
| Chelyabinsk       | 198      | 0.23%   |
| Prague            | 186      | 0.22%   |
| Buenos Aires      | 184      | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 28596    | 48445  | 20.6%   |
| WDC                       | 28491    | 49683  | 20.53%  |
| Samsung Electronics       | 19761    | 34295  | 14.24%  |
| Kingston                  | 8120     | 11637  | 5.85%   |
| Toshiba                   | 7405     | 11074  | 5.34%   |
| Hitachi                   | 5597     | 8060   | 4.03%   |
| Sandisk                   | 5284     | 7515   | 3.81%   |
| Crucial                   | 5224     | 7703   | 3.76%   |
| A-DATA Technology         | 2166     | 2946   | 1.56%   |
| Intel                     | 2124     | 3112   | 1.53%   |
| Maxtor                    | 1499     | 1978   | 1.08%   |
| China                     | 1377     | 1853   | 0.99%   |
| Unknown                   | 1328     | 2089   | 0.96%   |
| HGST                      | 1286     | 2129   | 0.93%   |
| Phison                    | 1224     | 1791   | 0.88%   |
| SPCC                      | 1016     | 1381   | 0.73%   |
| OCZ                       | 1007     | 1357   | 0.73%   |
| PNY                       | 893      | 1222   | 0.64%   |
| Corsair                   | 713      | 978    | 0.51%   |
| Silicon Motion            | 710      | 981    | 0.51%   |
| Patriot                   | 679      | 932    | 0.49%   |
| Intenso                   | 638      | 909    | 0.46%   |
| SK hynix                  | 608      | 831    | 0.44%   |
| Micron/Crucial Technology | 548      | 773    | 0.39%   |
| Transcend                 | 539      | 706    | 0.39%   |
| Micron Technology         | 524      | 694    | 0.38%   |
| GOODRAM                   | 451      | 694    | 0.32%   |
| Phison Electronics        | 446      | 615    | 0.32%   |
| Apacer                    | 416      | 558    | 0.3%    |
| Plextor                   | 410      | 611    | 0.3%    |
| Hewlett-Packard           | 374      | 566    | 0.27%   |
| XPG                       | 353      | 485    | 0.25%   |
| Team                      | 349      | 463    | 0.25%   |
| Gigabyte Technology       | 344      | 498    | 0.25%   |
| JMicron Technology        | 323      | 419    | 0.23%   |
| Realtek Semiconductor     | 270      | 340    | 0.19%   |
| Fujitsu                   | 264      | 329    | 0.19%   |
| KingSpec                  | 256      | 335    | 0.18%   |
| ASMT                      | 230      | 330    | 0.17%   |
| Unknown                   | 225      | 261    | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB                     | 2316     | 1.42%   |
| Kingston SA400S37240G 240GB SSD                     | 1736     | 1.07%   |
| Seagate ST1000DM010-2EP102 1TB                      | 1679     | 1.03%   |
| Toshiba DT01ACA100 1TB                              | 1403     | 0.86%   |
| Samsung SSD 850 EVO 250GB                           | 1326     | 0.82%   |
| Samsung SSD 860 EVO 500GB                           | 1325     | 0.82%   |
| Seagate ST2000DM008-2FR102 2TB                      | 1229     | 0.76%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 1212     | 0.75%   |
| Kingston SA400S37120G 120GB SSD                     | 1145     | 0.7%    |
| Seagate ST3500418AS 500GB                           | 1100     | 0.68%   |
| Seagate ST1000DM003-1CH162 1TB                      | 1077     | 0.66%   |
| Samsung SSD 850 EVO 500GB                           | 990      | 0.61%   |
| Kingston SV300S37A120G 120GB SSD                    | 973      | 0.6%    |
| Toshiba DT01ACA050 500GB                            | 934      | 0.57%   |
| Seagate ST1000DM003-1ER162 1TB                      | 916      | 0.56%   |
| Samsung SSD 860 EVO 1TB                             | 843      | 0.52%   |
| Kingston SA400S37480G 480GB SSD                     | 835      | 0.51%   |
| Samsung NVMe SSD Drive 500GB                        | 812      | 0.5%    |
| Toshiba HDWD110 1TB                                 | 809      | 0.5%    |
| Samsung SSD 860 EVO 250GB                           | 763      | 0.47%   |
| Crucial CT500MX500SSD1 500GB                        | 718      | 0.44%   |
| Seagate ST31000528AS 1TB                            | 675      | 0.42%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 675      | 0.42%   |
| Seagate ST2000DM001-1ER164 2TB                      | 655      | 0.4%    |
| Crucial CT1000MX500SSD1 1TB                         | 644      | 0.4%    |
| Samsung NVMe SSD Drive 1TB                          | 640      | 0.39%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 631      | 0.39%   |
| Seagate ST2000DM001-1CH164 2TB                      | 623      | 0.38%   |
| Seagate ST4000DM004-2CV104 4TB                      | 621      | 0.38%   |
| Crucial CT240BX500SSD1 240GB                        | 621      | 0.38%   |
| Toshiba DT01ACA200 2TB                              | 617      | 0.38%   |
| Seagate ST2000DM006-2DM164 2TB                      | 603      | 0.37%   |
| Seagate ST31000524AS 1TB                            | 600      | 0.37%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 515      | 0.32%   |
| Seagate ST3500413AS 500GB                           | 509      | 0.31%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 497      | 0.31%   |
| WDC WD5000AAKX-001CA0 500GB                         | 474      | 0.29%   |
| Samsung SSD 840 EVO 250GB                           | 473      | 0.29%   |
| Seagate Expansion 1TB                               | 472      | 0.29%   |
| Seagate ST1000DM003-1SB102 1TB                      | 470      | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 28198    | 47521  | 36.91%  |
| WDC                 | 25830    | 44399  | 33.81%  |
| Toshiba             | 6754     | 9998   | 8.84%   |
| Hitachi             | 5596     | 8059   | 7.32%   |
| Samsung Electronics | 5322     | 7833   | 6.97%   |
| Maxtor              | 1467     | 1923   | 1.92%   |
| HGST                | 1280     | 2070   | 1.68%   |
| Unknown             | 518      | 718    | 0.68%   |
| Fujitsu             | 254      | 311    | 0.33%   |
| Hewlett-Packard     | 142      | 225    | 0.19%   |
| Apple               | 93       | 104    | 0.12%   |
| ASMT                | 89       | 151    | 0.12%   |
| Intenso             | 85       | 125    | 0.11%   |
| External            | 58       | 66     | 0.08%   |
| ExcelStor           | 57       | 69     | 0.07%   |
| WD MediaMax         | 48       | 73     | 0.06%   |
| USB3.0              | 48       | 56     | 0.06%   |
| ASMedia             | 48       | 69     | 0.06%   |
| JMicron Technology  | 39       | 78     | 0.05%   |
| IBM/Hitachi         | 33       | 39     | 0.04%   |
| HPE                 | 29       | 49     | 0.04%   |
| QUANTUM             | 23       | 25     | 0.03%   |
| LaCie               | 22       | 40     | 0.03%   |
| HGST HTS            | 21       | 22     | 0.03%   |
| ASMT109x            | 20       | 30     | 0.03%   |
| USB                 | 18       | 23     | 0.02%   |
| SSK                 | 18       | 19     | 0.02%   |
| MARVELL             | 18       | 25     | 0.02%   |
| Inateck             | 17       | 22     | 0.02%   |
| SABRENT             | 14       | 22     | 0.02%   |
| Magnetic Data       | 14       | 15     | 0.02%   |
| Unknown             | 13       | 17     | 0.02%   |
| KESU                | 12       | 22     | 0.02%   |
| IBM                 | 11       | 16     | 0.01%   |
| RSH-319             | 9        | 9      | 0.01%   |
| PHD 3.0             | 9        | 10     | 0.01%   |
| Synology            | 8        | 17     | 0.01%   |
| USB 3.0             | 7        | 15     | 0.01%   |
| SAGE                | 7        | 9      | 0.01%   |
| Maxone              | 7        | 9      | 0.01%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 10328    | 16504  | 22.43%  |
| Kingston            | 7137     | 10110  | 15.5%   |
| Crucial             | 4764     | 7030   | 10.34%  |
| SanDisk             | 3765     | 5272   | 8.18%   |
| WDC                 | 2990     | 4105   | 6.49%   |
| A-DATA Technology   | 1817     | 2447   | 3.95%   |
| China               | 1362     | 1835   | 2.96%   |
| Intel               | 1227     | 1781   | 2.66%   |
| OCZ                 | 994      | 1318   | 2.16%   |
| SPCC                | 922      | 1247   | 2%      |
| PNY                 | 830      | 1143   | 1.8%    |
| Patriot             | 634      | 878    | 1.38%   |
| Toshiba             | 512      | 741    | 1.11%   |
| Transcend           | 489      | 633    | 1.06%   |
| Corsair             | 479      | 651    | 1.04%   |
| Intenso             | 466      | 648    | 1.01%   |
| GOODRAM             | 433      | 663    | 0.94%   |
| Micron Technology   | 385      | 514    | 0.84%   |
| Apacer              | 382      | 512    | 0.83%   |
| Plextor             | 371      | 549    | 0.81%   |
| Team                | 319      | 412    | 0.69%   |
| SK hynix            | 248      | 342    | 0.54%   |
| KingSpec            | 248      | 327    | 0.54%   |
| Gigabyte Technology | 225      | 327    | 0.49%   |
| Lexar               | 185      | 211    | 0.4%    |
| JMicron Technology  | 184      | 216    | 0.4%    |
| Seagate             | 169      | 235    | 0.37%   |
| KingDian            | 167      | 221    | 0.36%   |
| LITEON              | 165      | 204    | 0.36%   |
| Hewlett-Packard     | 165      | 223    | 0.36%   |
| Netac               | 151      | 253    | 0.33%   |
| SABRENT             | 144      | 179    | 0.31%   |
| LITEONIT            | 137      | 163    | 0.3%    |
| Smartbuy            | 135      | 190    | 0.29%   |
| ASMT                | 133      | 170    | 0.29%   |
| Unknown             | 133      | 153    | 0.29%   |
| Mushkin             | 131      | 191    | 0.28%   |
| AMD                 | 130      | 181    | 0.28%   |
| Unknown             | 87       | 115    | 0.19%   |
| TO Exter            | 87       | 106    | 0.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 58412    | 124533 | 51.11%  |
| SSD     | 37746    | 66164  | 33.03%  |
| NVMe    | 15743    | 26091  | 13.78%  |
| Unknown | 2021     | 3020   | 1.77%   |
| MMC     | 357      | 447    | 0.31%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 72433    | 185149 | 77.32%  |
| NVMe | 15731    | 26028  | 16.79%  |
| SAS  | 5164     | 8631   | 5.51%   |
| MMC  | 357      | 447    | 0.38%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| 0.01-0.5        | 56495    | 106397 | 53.77%  |
| 0.51-1.0        | 28551    | 48184  | 27.17%  |
| 1.01-2.0        | 10683    | 17846  | 10.17%  |
| 3.01-4.0        | 3725     | 6878   | 3.55%   |
| 2.01-3.0        | 2743     | 4905   | 2.61%   |
| 4.01-10.0       | 2286     | 5076   | 2.18%   |
| 10.01-20.0      | 581      | 1396   | 0.55%   |
| 20.01-50.0      | 6        | 10     | 0.01%   |
| 0               | 5        | 4      | 0.005%  |
| More than 100.0 | 1        | 1      | 0.001%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 18734    | 21.9%   |
| 251-500        | 14857    | 17.37%  |
| 501-1000       | 12400    | 14.5%   |
| 1001-2000      | 8745     | 10.22%  |
| 1-20           | 7009     | 8.19%   |
| More than 3000 | 6801     | 7.95%   |
| 51-100         | 5599     | 6.55%   |
| Unknown        | 4167     | 4.87%   |
| 2001-3000      | 3929     | 4.59%   |
| 21-50          | 3292     | 3.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 33846    | 38.62%  |
| 21-50          | 11472    | 13.09%  |
| 101-250        | 9093     | 10.38%  |
| 51-100         | 7765     | 8.86%   |
| 251-500        | 6641     | 7.58%   |
| 501-1000       | 6150     | 7.02%   |
| 1001-2000      | 4239     | 4.84%   |
| Unknown        | 4167     | 4.75%   |
| More than 3000 | 2593     | 2.96%   |
| 2001-3000      | 1660     | 1.89%   |
| 0              | 15       | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 497      | 638    | 2.86%   |
| Seagate ST3500418AS 500GB         | 299      | 397    | 1.72%   |
| Seagate ST31000528AS 1TB          | 164      | 205    | 0.94%   |
| WDC WD5000AAKX-001CA0 500GB       | 162      | 205    | 0.93%   |
| Seagate ST3250410AS 250GB         | 148      | 189    | 0.85%   |
| Seagate ST3250310AS 250GB         | 143      | 206    | 0.82%   |
| Kingston SV300S37A120G 120GB SSD  | 130      | 149    | 0.75%   |
| Seagate ST1000DM003-1CH162 1TB    | 127      | 171    | 0.73%   |
| Seagate ST31000524AS 1TB          | 124      | 156    | 0.71%   |
| Seagate ST1000DM003-9YN162 1TB    | 121      | 139    | 0.7%    |
| Seagate ST3320613AS 320GB         | 111      | 145    | 0.64%   |
| WDC WD10EARS-00Y5B1 1TB           | 108      | 156    | 0.62%   |
| WDC WD5000AADS-00S9B0 500GB       | 101      | 117    | 0.58%   |
| Hitachi HDS721010CLA332 1TB       | 101      | 123    | 0.58%   |
| Seagate ST3160815AS 160GB         | 98       | 114    | 0.56%   |
| Seagate ST3250318AS 250GB         | 97       | 127    | 0.56%   |
| Hitachi HDS721050CLA362 500GB     | 96       | 124    | 0.55%   |
| Seagate ST3500413AS 500GB         | 95       | 108    | 0.55%   |
| Seagate ST31500341AS 1TB          | 94       | 127    | 0.54%   |
| Toshiba DT01ACA100 1TB            | 93       | 125    | 0.54%   |
| Toshiba DT01ACA050 500GB          | 90       | 115    | 0.52%   |
| Hitachi HDP725050GLA360 500GB     | 83       | 108    | 0.48%   |
| Seagate ST2000DM001-1CH164 2TB    | 82       | 100    | 0.47%   |
| Samsung Electronics HD080HJ/ 80GB | 82       | 99     | 0.47%   |
| WDC WD3200AAJS-00L7A0 320GB       | 76       | 86     | 0.44%   |
| Samsung Electronics HD161HJ 160GB | 76       | 89     | 0.44%   |
| WDC WD5000AAKX-00ERMA0 500GB      | 75       | 93     | 0.43%   |
| Seagate ST380011A 80GB            | 75       | 85     | 0.43%   |
| Seagate ST3320620AS 320GB         | 75       | 101    | 0.43%   |
| Seagate ST9500325AS 500GB         | 74       | 85     | 0.43%   |
| Seagate ST250DM000-1BD141 250GB   | 74       | 96     | 0.43%   |
| Hitachi HDS721616PLA380 160GB     | 74       | 93     | 0.43%   |
| Seagate ST3160811AS 160GB         | 73       | 101    | 0.42%   |
| Seagate ST3500320AS 500GB         | 72       | 90     | 0.41%   |
| Seagate ST3320418AS 320GB         | 70       | 89     | 0.4%    |
| Samsung Electronics HD160JJ 160GB | 70       | 100    | 0.4%    |
| Maxtor STM3250310AS 250GB         | 69       | 89     | 0.4%    |
| Samsung Electronics HD103UJ 1TB   | 66       | 94     | 0.38%   |
| Seagate ST380815AS 80GB           | 65       | 83     | 0.37%   |
| Seagate ST1000DM010-2EP102 1TB    | 65       | 78     | 0.37%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5298     | 7334   | 32.44%  |
| WDC                 | 4663     | 6424   | 28.55%  |
| Samsung Electronics | 1675     | 2231   | 10.26%  |
| Hitachi             | 1341     | 1771   | 8.21%   |
| Toshiba             | 597      | 750    | 3.66%   |
| Maxtor              | 493      | 602    | 3.02%   |
| Kingston            | 408      | 492    | 2.5%    |
| Intel               | 200      | 279    | 1.22%   |
| Crucial             | 194      | 248    | 1.19%   |
| SanDisk             | 181      | 215    | 1.11%   |
| A-DATA Technology   | 156      | 196    | 0.96%   |
| HGST                | 137      | 184    | 0.84%   |
| OCZ                 | 114      | 150    | 0.7%    |
| SPCC                | 75       | 95     | 0.46%   |
| Corsair             | 69       | 105    | 0.42%   |
| China               | 49       | 57     | 0.3%    |
| Fujitsu             | 48       | 56     | 0.29%   |
| Hewlett-Packard     | 39       | 43     | 0.24%   |
| SK hynix            | 30       | 51     | 0.18%   |
| Micron Technology   | 30       | 45     | 0.18%   |
| Kingmax             | 30       | 57     | 0.18%   |
| Intenso             | 24       | 31     | 0.15%   |
| KingSpec            | 22       | 25     | 0.13%   |
| Plextor             | 21       | 35     | 0.13%   |
| IBM/Hitachi         | 21       | 27     | 0.13%   |
| ASMT                | 20       | 31     | 0.12%   |
| Patriot             | 19       | 20     | 0.12%   |
| Unknown             | 16       | 19     | 0.1%    |
| LITEONIT            | 15       | 15     | 0.09%   |
| Transcend           | 14       | 23     | 0.09%   |
| AMD                 | 14       | 17     | 0.09%   |
| WD MediaMax         | 13       | 18     | 0.08%   |
| Netac               | 13       | 13     | 0.08%   |
| ExcelStor           | 13       | 15     | 0.08%   |
| Apacer              | 13       | 18     | 0.08%   |
| XPG                 | 12       | 15     | 0.07%   |
| Unknown             | 10       | 15     | 0.06%   |
| PNY                 | 10       | 11     | 0.06%   |
| LITEON              | 10       | 10     | 0.06%   |
| GOODRAM             | 10       | 10     | 0.06%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5297     | 7331   | 37.86%  |
| WDC                 | 4570     | 6285   | 32.67%  |
| Samsung Electronics | 1376     | 1852   | 9.84%   |
| Hitachi             | 1341     | 1771   | 9.59%   |
| Toshiba             | 587      | 740    | 4.2%    |
| Maxtor              | 493      | 602    | 3.52%   |
| HGST                | 137      | 184    | 0.98%   |
| Fujitsu             | 48       | 56     | 0.34%   |
| Hewlett-Packard     | 24       | 28     | 0.17%   |
| IBM/Hitachi         | 21       | 27     | 0.15%   |
| WD MediaMax         | 13       | 18     | 0.09%   |
| ExcelStor           | 13       | 15     | 0.09%   |
| ASMT                | 10       | 16     | 0.07%   |
| IBM                 | 9        | 11     | 0.06%   |
| Unknown             | 8        | 13     | 0.06%   |
| QUANTUM             | 5        | 5      | 0.04%   |
| ASMedia             | 5        | 7      | 0.04%   |
| HPE                 | 4        | 5      | 0.03%   |
| Apple               | 4        | 4      | 0.03%   |
| Unknown             | 4        | 5      | 0.03%   |
| USB3.0              | 3        | 3      | 0.02%   |
| MDT                 | 2        | 2      | 0.01%   |
| Intenso             | 2        | 2      | 0.01%   |
| TPH00100500GB       | 1        | 1      | 0.01%   |
| SAGE                | 1        | 1      | 0.01%   |
| RSH-339             | 1        | 1      | 0.01%   |
| RSH-319             | 1        | 1      | 0.01%   |
| MaxDigital          | 1        | 1      | 0.01%   |
| Magnetic Data       | 1        | 1      | 0.01%   |
| LaCie               | 1        | 1      | 0.01%   |
| Inateck             | 1        | 1      | 0.01%   |
| ICY BOX             | 1        | 1      | 0.01%   |
| IB                  | 1        | 1      | 0.01%   |
| HGST HTS            | 1        | 1      | 0.01%   |
| FEASSO              | 1        | 2      | 0.01%   |
| DAS                 | 1        | 3      | 0.01%   |
| China               | 1        | 1      | 0.01%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 12326    | 18999  | 84.21%  |
| SSD     | 2065     | 2713   | 14.11%  |
| NVMe    | 246      | 321    | 1.68%   |
| Unknown | 1        | 1      | 0.01%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST3500418AS 500GB         | 20       | 23     | 4.29%   |
| Seagate ST31000528AS 1TB          | 15       | 18     | 3.22%   |
| Samsung Electronics HD502HJ 500GB | 10       | 12     | 2.15%   |
| Hitachi HDS721010DLE630 1TB       | 10       | 17     | 2.15%   |
| Seagate ST500DM002-1BD142 500GB   | 9        | 10     | 1.93%   |
| Seagate ST31000524AS 1TB          | 8        | 10     | 1.72%   |
| Samsung Electronics HD103SJ 1TB   | 7        | 9      | 1.5%    |
| Seagate ST3500412AS 500GB         | 6        | 8      | 1.29%   |
| Seagate ST3250318AS 250GB         | 6        | 10     | 1.29%   |
| Samsung Electronics HD252HJ 250GB | 6        | 10     | 1.29%   |
| Toshiba DT01ACA100 1TB            | 5        | 6      | 1.07%   |
| Seagate ST3500410AS 500GB         | 5        | 7      | 1.07%   |
| Samsung Electronics SSD 980 500GB | 5        | 6      | 1.07%   |
| Samsung Electronics SSD 980 1TB   | 5        | 5      | 1.07%   |
| Samsung Electronics HD502IJ 500GB | 5        | 5      | 1.07%   |
| Samsung Electronics HD322GJ 320GB | 5        | 6      | 1.07%   |
| Seagate ST31500341AS 1TB          | 4        | 6      | 0.86%   |
| Seagate ST31000333AS 1TB          | 4        | 4      | 0.86%   |
| Samsung Electronics SP0411N 40GB  | 4        | 5      | 0.86%   |
| Hitachi HDS721050DLE630 500GB     | 4        | 4      | 0.86%   |
| Hitachi HDS721010CLA332 1TB       | 4        | 4      | 0.86%   |
| HGST HTS545050A7E380 500GB        | 4        | 4      | 0.86%   |
| Apple HDD HTS541010A9E662 1TB     | 4        | 4      | 0.86%   |
| WDC WD5000AAKS-00V1A0 500GB       | 3        | 4      | 0.64%   |
| WDC WD3200AAJS-00L7A0 320GB       | 3        | 4      | 0.64%   |
| WDC WD20EARS-00MVWB0 2TB          | 3        | 4      | 0.64%   |
| WDC WD15EARS-00MVWB0 1TB          | 3        | 6      | 0.64%   |
| Toshiba MK5065GSX 500GB           | 3        | 3      | 0.64%   |
| Toshiba DT01ACA200 2TB            | 3        | 3      | 0.64%   |
| Toshiba DT01ACA050 500GB          | 3        | 3      | 0.64%   |
| Seagate ST500DM002-1BC142 500GB   | 3        | 3      | 0.64%   |
| Seagate ST3750528AS 752GB         | 3        | 3      | 0.64%   |
| Seagate ST3320613AS 320GB         | 3        | 4      | 0.64%   |
| Seagate ST32000542AS 2TB          | 3        | 5      | 0.64%   |
| Samsung Electronics HD204UI 2TB   | 3        | 3      | 0.64%   |
| Samsung Electronics HD103UJ 1TB   | 3        | 4      | 0.64%   |
| Maxtor 6Y080L0 82GB               | 3        | 3      | 0.64%   |
| Hitachi HDS721025CLA382 250GB     | 3        | 3      | 0.64%   |
| WDC WD800JD-00LSA0 80GB           | 2        | 3      | 0.43%   |
| WDC WD7501AALS-00J7B0 752GB       | 2        | 3      | 0.43%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 144      | 176    | 31.1%   |
| Samsung Electronics | 101      | 119    | 21.81%  |
| WDC                 | 99       | 121    | 21.38%  |
| Hitachi             | 37       | 45     | 7.99%   |
| Toshiba             | 30       | 34     | 6.48%   |
| Maxtor              | 11       | 11     | 2.38%   |
| HGST                | 11       | 11     | 2.38%   |
| Hewlett-Packard     | 4        | 8      | 0.86%   |
| Apple               | 4        | 4      | 0.86%   |
| Kingston            | 3        | 3      | 0.65%   |
| Intel               | 3        | 3      | 0.65%   |
| Crucial             | 2        | 2      | 0.43%   |
| Zheino              | 1        | 1      | 0.22%   |
| Unknown             | 1        | 1      | 0.22%   |
| Transcend           | 1        | 1      | 0.22%   |
| TPH00800640GB       | 1        | 1      | 0.22%   |
| SPCC                | 1        | 1      | 0.22%   |
| Patriot             | 1        | 2      | 0.22%   |
| OCZ-AGIL            | 1        | 1      | 0.22%   |
| OCZ                 | 1        | 1      | 0.22%   |
| Mushkin             | 1        | 1      | 0.22%   |
| Intenso             | 1        | 1      | 0.22%   |
| Inland              | 1        | 1      | 0.22%   |
| GOODRAM             | 1        | 1      | 0.22%   |
| Corsair             | 1        | 1      | 0.22%   |
| A-DATA Technology   | 1        | 1      | 0.22%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 40690    | 111626 | 45.14%  |
| Works    | 34900    | 86039  | 38.72%  |
| Malfunc  | 14091    | 22034  | 15.63%  |
| Failed   | 456      | 552    | 0.51%   |
| Limited  | 4        | 4      | 0.004%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 49116    | 46.14%  |
| AMD                              | 24649    | 23.15%  |
| Samsung Electronics              | 6613     | 6.21%   |
| ASMedia Technology               | 3594     | 3.38%   |
| Nvidia                           | 3417     | 3.21%   |
| JMicron Technology               | 3241     | 3.04%   |
| Marvell Technology Group         | 2805     | 2.63%   |
| SanDisk                          | 2394     | 2.25%   |
| Phison Electronics               | 2115     | 1.99%   |
| Kingston Technology Company      | 1274     | 1.2%    |
| Micron/Crucial Technology        | 1020     | 0.96%   |
| Silicon Motion                   | 1001     | 0.94%   |
| VIA Technologies                 | 855      | 0.8%    |
| ADATA Technology                 | 681      | 0.64%   |
| Realtek Semiconductor            | 451      | 0.42%   |
| SK hynix                         | 356      | 0.33%   |
| LSI Logic / Symbios Logic        | 353      | 0.33%   |
| Silicon Image                    | 309      | 0.29%   |
| Broadcom / LSI                   | 307      | 0.29%   |
| Toshiba America Info Systems     | 236      | 0.22%   |
| Seagate Technology               | 178      | 0.17%   |
| Adaptec                          | 175      | 0.16%   |
| Micron Technology                | 167      | 0.16%   |
| Silicon Integrated Systems [SiS] | 149      | 0.14%   |
| KIOXIA                           | 137      | 0.13%   |
| Integrated Technology Express    | 120      | 0.11%   |
| Lite-On Technology               | 110      | 0.1%    |
| MAXIO Technology (Hangzhou)      | 109      | 0.1%    |
| Shenzhen Longsys Electronics     | 60       | 0.06%   |
| Hewlett-Packard                  | 54       | 0.05%   |
| Promise Technology               | 35       | 0.03%   |
| INNOGRIT                         | 35       | 0.03%   |
| OCZ Technology Group             | 34       | 0.03%   |
| ULi Electronics                  | 33       | 0.03%   |
| HighPoint Technologies           | 28       | 0.03%   |
| Netac Technology                 | 24       | 0.02%   |
| 3ware                            | 24       | 0.02%   |
| Union Memory (Shenzhen)          | 22       | 0.02%   |
| Lite-On IT Corp. / Plextor       | 18       | 0.02%   |
| Solid State Storage Technology   | 16       | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 13342    | 9.5%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5443     | 3.88%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5195     | 3.7%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4839     | 3.45%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4819     | 3.43%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4084     | 2.91%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4034     | 2.87%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3992     | 2.84%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3587     | 2.55%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3541     | 2.52%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3384     | 2.41%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3360     | 2.39%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3348     | 2.38%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3015     | 2.15%   |
| Intel SATA Controller [RAID mode]                                                       | 2592     | 1.85%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2386     | 1.7%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2337     | 1.66%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2326     | 1.66%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2069     | 1.47%   |
| Nvidia MCP61 SATA Controller                                                            | 1806     | 1.29%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1729     | 1.23%   |
| Nvidia MCP61 IDE                                                                        | 1545     | 1.1%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1325     | 0.94%   |
| AMD FCH SATA Controller D                                                               | 1275     | 0.91%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1241     | 0.88%   |
| AMD 300 Series Chipset SATA Controller                                                  | 1217     | 0.87%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1173     | 0.84%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1145     | 0.82%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1057     | 0.75%   |
| Phison E12 NVMe Controller                                                              | 1033     | 0.74%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 1008     | 0.72%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1003     | 0.71%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 993      | 0.71%   |
| JMicron JMB368 IDE controller                                                           | 938      | 0.67%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 919      | 0.65%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 884      | 0.63%   |
| AMD FCH IDE Controller                                                                  | 824      | 0.59%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 816      | 0.58%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 801      | 0.57%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 759      | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 57654    | 54.58%  |
| IDE  | 26337    | 24.93%  |
| NVMe | 15928    | 15.08%  |
| RAID | 4770     | 4.52%   |
| SAS  | 590      | 0.56%   |
| SCSI | 351      | 0.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 49934    | 64.14%  |
| AMD                      | 27832    | 35.75%  |
| CentaurHauls             | 20       | 0.03%   |
| Unknown                  | 19       | 0.02%   |
| ARM                      | 10       | 0.01%   |
| CHRP IBM,8233-E8B        | 5        | 0.01%   |
| sifive,u74-mc            | 4        | 0.01%   |
| Marvell Semiconductor    | 4        | 0.01%   |
| sifive,bullet0           | 3        | 0.004%  |
| PowerNV C1P9S01 REV 1.01 | 3        | 0.004%  |
| CHRP IBM,9131-52A        | 2        | 0.003%  |
| PowerNV FP5466G2         | 1        | 0.001%  |
| PowerNV C829UAG3         | 1        | 0.001%  |
| PowerMac8,1              | 1        | 0.001%  |
| PowerMac7,2              | 1        | 0.001%  |
| PowerMac3,6              | 1        | 0.001%  |
| PowerMac11,2             | 1        | 0.001%  |
| PowerMac10,2             | 1        | 0.001%  |
| PowerBook6,7             | 1        | 0.001%  |
| PowerBook5,5             | 1        | 0.001%  |
| MBE8C-PC                 | 1        | 0.001%  |
| Loongson                 | 1        | 0.001%  |
| IBM/S390                 | 1        | 0.001%  |
| FSP-1                    | 1        | 0.001%  |
| Elbrus-MCST              | 1        | 0.001%  |
| E8C/EATX                 | 1        | 0.001%  |
| E8C-SWTX                 | 1        | 0.001%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 1376     | 1.75%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 1039     | 1.32%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 959      | 1.22%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 947      | 1.21%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 857      | 1.09%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 827      | 1.05%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 771      | 0.98%   |
| AMD FX-8350 Eight-Core Processor            | 731      | 0.93%   |
| AMD FX-6300 Six-Core Processor              | 705      | 0.9%    |
| Intel Core i7-4790 CPU @ 3.60GHz            | 677      | 0.86%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 669      | 0.85%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 654      | 0.83%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 634      | 0.81%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 608      | 0.78%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 603      | 0.77%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 603      | 0.77%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 589      | 0.75%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 571      | 0.73%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 536      | 0.68%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 534      | 0.68%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 517      | 0.66%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 485      | 0.62%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 480      | 0.61%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 479      | 0.61%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 475      | 0.61%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 465      | 0.59%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 458      | 0.58%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 449      | 0.57%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 445      | 0.57%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 438      | 0.56%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 433      | 0.55%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 428      | 0.55%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 406      | 0.52%   |
| Intel Pentium 4 CPU 3.00GHz                 | 401      | 0.51%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 390      | 0.5%    |
| Intel Core i5-8400 CPU @ 2.80GHz            | 385      | 0.49%   |
| AMD Athlon II X2 250 Processor              | 382      | 0.49%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 366      | 0.47%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 363      | 0.46%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 363      | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 12845    | 16.41%  |
| Intel Core i7           | 9205     | 11.76%  |
| AMD Ryzen 5             | 5939     | 7.59%   |
| Intel Core i3           | 5857     | 7.48%   |
| AMD Ryzen 7             | 3935     | 5.03%   |
| Intel Xeon              | 3582     | 4.58%   |
| Intel Core 2 Duo        | 3580     | 4.57%   |
| AMD FX                  | 3408     | 4.35%   |
| Intel Celeron           | 2742     | 3.5%    |
| Intel Pentium           | 2394     | 3.06%   |
| Intel Core 2 Quad       | 2043     | 2.61%   |
| AMD Ryzen 9             | 1909     | 2.44%   |
| Intel Pentium Dual-Core | 1770     | 2.26%   |
| Other                   | 1629     | 2.08%   |
| AMD Athlon 64 X2        | 1375     | 1.76%   |
| AMD Athlon II X2        | 1300     | 1.66%   |
| AMD Phenom II X4        | 1206     | 1.54%   |
| AMD Ryzen 3             | 1179     | 1.51%   |
| Intel Pentium 4         | 962      | 1.23%   |
| AMD A8                  | 831      | 1.06%   |
| Intel Core 2            | 759      | 0.97%   |
| AMD A10                 | 745      | 0.95%   |
| Intel Pentium Dual      | 697      | 0.89%   |
| Intel Core i9           | 660      | 0.84%   |
| Intel Atom              | 621      | 0.79%   |
| AMD Athlon II X4        | 609      | 0.78%   |
| AMD A4                  | 557      | 0.71%   |
| AMD Phenom II X6        | 466      | 0.6%    |
| Intel Pentium D         | 465      | 0.59%   |
| AMD Athlon              | 464      | 0.59%   |
| AMD A6                  | 464      | 0.59%   |
| AMD Ryzen Threadripper  | 445      | 0.57%   |
| AMD Phenom              | 363      | 0.46%   |
| AMD Sempron             | 320      | 0.41%   |
| AMD Athlon II X3        | 317      | 0.41%   |
| AMD Athlon 64           | 306      | 0.39%   |
| AMD Athlon X4           | 248      | 0.32%   |
| Intel Pentium Gold      | 225      | 0.29%   |
| AMD Phenom II X2        | 196      | 0.25%   |
| AMD Ryzen 5 PRO         | 168      | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 28986    | 36.84%  |
| 2       | 23454    | 29.81%  |
| 6       | 10042    | 12.76%  |
| 8       | 6360     | 8.08%   |
| 1       | 3025     | 3.84%   |
| 12      | 1884     | 2.39%   |
| 3       | 1513     | 1.92%   |
| Unknown | 1308     | 1.66%   |
| 16      | 1122     | 1.43%   |
| 10      | 460      | 0.58%   |
| 24      | 188      | 0.24%   |
| 32      | 103      | 0.13%   |
| 14      | 74       | 0.09%   |
| 20      | 42       | 0.05%   |
| 18      | 37       | 0.05%   |
| 64      | 25       | 0.03%   |
| 28      | 24       | 0.03%   |
| 5       | 10       | 0.01%   |
| 44      | 7        | 0.01%   |
| 36      | 6        | 0.01%   |
| 22      | 6        | 0.01%   |
| 40      | 4        | 0.01%   |
| 48      | 3        | 0.004%  |
| 128     | 2        | 0.003%  |
| 15      | 1        | 0.001%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 76876    | 98.69%  |
| 2       | 925      | 1.19%   |
| Unknown | 89       | 0.11%   |
| 4       | 4        | 0.01%   |
| 0       | 3        | 0.004%  |
| 16      | 1        | 0.001%  |
| 6       | 1        | 0.001%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 39498    | 50.3%   |
| 1       | 37682    | 47.99%  |
| Unknown | 1308     | 1.67%   |
| 4       | 20       | 0.03%   |
| 8       | 8        | 0.01%   |
| 12      | 2        | 0.003%  |
| 6       | 2        | 0.003%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 76050    | 97.3%   |
| Unknown        | 1408     | 1.8%    |
| 32-bit         | 608      | 0.78%   |
| 64-bit         | 96       | 0.12%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 17006    | 20.94%  |
| 0x306c3    | 5971     | 7.35%   |
| 0x206a7    | 4703     | 5.79%   |
| 0x306a9    | 4639     | 5.71%   |
| 0x1067a    | 4551     | 5.6%    |
| 0x506e3    | 2523     | 3.11%   |
| 0x08701021 | 2254     | 2.77%   |
| 0x010000c8 | 1980     | 2.44%   |
| 0x906ea    | 1823     | 2.24%   |
| 0x906e9    | 1746     | 2.15%   |
| 0x0800820d | 1612     | 1.98%   |
| 0x06000852 | 1590     | 1.96%   |
| 0x06001119 | 1164     | 1.43%   |
| 0x6fb      | 1127     | 1.39%   |
| 0x6fd      | 1126     | 1.39%   |
| 0x08701013 | 1056     | 1.3%    |
| 0x10676    | 941      | 1.16%   |
| 0x08108109 | 769      | 0.95%   |
| 0x106e5    | 718      | 0.88%   |
| 0xa0653    | 690      | 0.85%   |
| 0x08001138 | 652      | 0.8%    |
| 0x906ed    | 621      | 0.76%   |
| 0xa0655    | 588      | 0.72%   |
| 0x0a201016 | 583      | 0.72%   |
| 0x20655    | 565      | 0.7%    |
| 0x306f2    | 550      | 0.68%   |
| 0x06003106 | 547      | 0.67%   |
| 0x010000db | 537      | 0.66%   |
| 0x106a5    | 500      | 0.62%   |
| 0x206d7    | 488      | 0.6%    |
| 0x08001137 | 466      | 0.57%   |
| 0x6f6      | 444      | 0.55%   |
| 0x08101016 | 442      | 0.54%   |
| 0x0a201009 | 436      | 0.54%   |
| 0x906eb    | 430      | 0.53%   |
| 0xa0671    | 425      | 0.52%   |
| 0x0600063e | 417      | 0.51%   |
| 0x20652    | 402      | 0.49%   |
| 0x206c2    | 372      | 0.46%   |
| 0x90672    | 356      | 0.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 8105     | 10.36%  |
| Penryn           | 6364     | 8.13%   |
| KabyLake         | 6246     | 7.98%   |
| SandyBridge      | 6071     | 7.76%   |
| IvyBridge        | 5932     | 7.58%   |
| K10              | 4803     | 6.14%   |
| Zen 2            | 4733     | 6.05%   |
| Piledriver       | 4063     | 5.19%   |
| Core             | 3655     | 4.67%   |
| Skylake          | 3502     | 4.48%   |
| Zen+             | 3409     | 4.36%   |
| Zen 3            | 2809     | 3.59%   |
| Zen              | 2780     | 3.55%   |
| K8 Hammer        | 2003     | 2.56%   |
| NetBurst         | 1729     | 2.21%   |
| CometLake        | 1681     | 2.15%   |
| Westmere         | 1575     | 2.01%   |
| Nehalem          | 1512     | 1.93%   |
| Unknown          | 1268     | 1.62%   |
| Silvermont       | 774      | 0.99%   |
| Steamroller      | 734      | 0.94%   |
| Bulldozer        | 709      | 0.91%   |
| Alderlake Hybrid | 498      | 0.64%   |
| Excavator        | 443      | 0.57%   |
| Bonnell          | 435      | 0.56%   |
| K10 Llano        | 389      | 0.5%    |
| Icelake          | 331      | 0.42%   |
| Goldmont plus    | 327      | 0.42%   |
| Broadwell        | 321      | 0.41%   |
| Jaguar           | 255      | 0.33%   |
| Bobcat           | 251      | 0.32%   |
| Goldmont         | 202      | 0.26%   |
| Puma             | 116      | 0.15%   |
| Tremont          | 105      | 0.13%   |
| K6               | 60       | 0.08%   |
| TigerLake        | 34       | 0.04%   |
| P6               | 22       | 0.03%   |
| Gracemont        | 5        | 0.01%   |
| K8 & K10 hybrid  | 3        | 0.004%  |
| Geode            | 2        | 0.003%  |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Nvidia                                       | 34492    | 41.45%  |
| AMD                                          | 24798    | 29.8%   |
| Intel                                        | 23159    | 27.83%  |
| Matrox Electronics Systems                   | 231      | 0.28%   |
| ASPEED Technology                            | 226      | 0.27%   |
| VIA Technologies                             | 135      | 0.16%   |
| Silicon Integrated Systems [SiS]             | 54       | 0.06%   |
| ATI Technologies                             | 43       | 0.05%   |
| XGI Technology (eXtreme Graphics Innovation) | 27       | 0.03%   |
| S3 Graphics                                  | 18       | 0.02%   |
| Silicon Motion                               | 11       | 0.01%   |
| Loongson Technology                          | 4        | 0.005%  |
| Zhaoxin                                      | 3        | 0.004%  |
| Conexant Systems                             | 2        | 0.002%  |
| Trident Microsystems                         | 1        | 0.001%  |
| Red Hat                                      | 1        | 0.001%  |
| NVidia / SGS Thomson (Joint Venture)         | 1        | 0.001%  |
| Moore Threads Technology                     | 1        | 0.001%  |
| Dome Imaging Systems                         | 1        | 0.001%  |
| Cirrus Logic                                 | 1        | 0.001%  |
| Alliance Semiconductor                       | 1        | 0.001%  |
| 3DLabs                                       | 1        | 0.001%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3524     | 4.08%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3272     | 3.79%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2771     | 3.21%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2081     | 2.41%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1842     | 2.13%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1810     | 2.1%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1733     | 2.01%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1584     | 1.84%   |
| Nvidia GT218 [GeForce 210]                                                  | 1410     | 1.63%   |
| Intel HD Graphics 530                                                       | 1405     | 1.63%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1145     | 1.33%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 989      | 1.15%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 984      | 1.14%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 968      | 1.12%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 963      | 1.12%   |
| Intel HD Graphics 630                                                       | 931      | 1.08%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 885      | 1.03%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 833      | 0.97%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 822      | 0.95%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 805      | 0.93%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 774      | 0.9%    |
| Nvidia GK208B [GeForce GT 730]                                              | 765      | 0.89%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 761      | 0.88%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 711      | 0.82%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 709      | 0.82%   |
| Nvidia GF119 [GeForce GT 610]                                               | 706      | 0.82%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 701      | 0.81%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 667      | 0.77%   |
| AMD RS780L [Radeon 3000]                                                    | 644      | 0.75%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 619      | 0.72%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 605      | 0.7%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 604      | 0.7%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 548      | 0.64%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 542      | 0.63%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 515      | 0.6%    |
| Nvidia GF108 [GeForce GT 630]                                               | 515      | 0.6%    |
| Nvidia GK107 [GeForce GTX 650]                                              | 513      | 0.59%   |
| Intel Core Processor Integrated Graphics Controller                         | 503      | 0.58%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 497      | 0.58%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 484      | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| 1 x Nvidia                        | 32178    | 40.56%  |
| 1 x AMD                           | 22308    | 28.12%  |
| 1 x Intel                         | 19772    | 24.92%  |
| 2 x AMD                           | 1388     | 1.75%   |
| Intel + Nvidia                    | 1139     | 1.44%   |
| AMD + Nvidia                      | 644      | 0.81%   |
| Intel + AMD                       | 474      | 0.6%    |
| 2 x Nvidia                        | 418      | 0.53%   |
| 1 x Matrox                        | 197      | 0.25%   |
| 1 x ASPEED                        | 158      | 0.2%    |
| 1 x VIA                           | 133      | 0.17%   |
| Other                             | 102      | 0.13%   |
| 2 x Intel                         | 70       | 0.09%   |
| 1 x SiS                           | 53       | 0.07%   |
| Nvidia + ASPEED                   | 44       | 0.06%   |
| Intel + 2 x Nvidia                | 27       | 0.03%   |
| 1 x XGI                           | 23       | 0.03%   |
| Nvidia + Matrox                   | 23       | 0.03%   |
| 3 x AMD                           | 18       | 0.02%   |
| Intel + AMD + 1 x Nvidia          | 18       | 0.02%   |
| 1 x S3 Graphics                   | 15       | 0.02%   |
| AMD + ASPEED                      | 15       | 0.02%   |
| Intel + 2 x AMD                   | 14       | 0.02%   |
| 3 x Nvidia                        | 12       | 0.02%   |
| AMD + Matrox                      | 12       | 0.02%   |
| 2 x AMD + 1 x Nvidia              | 11       | 0.01%   |
| AMD + 2 x Nvidia                  | 9        | 0.01%   |
| 1 x Silicon Motion                | 8        | 0.01%   |
| 2 x Nvidia + 1 x ASPEED           | 3        | 0.004%  |
| Nvidia + XGI                      | 3        | 0.004%  |
| 1 x Intel + 3 x Nvidia            | 3        | 0.004%  |
| 4 x Nvidia                        | 2        | 0.003%  |
| 2 x AMD + 1 x Nvidia + 1 x ASPEED | 2        | 0.003%  |
| 2 x AMD + 1 x ASPEED              | 2        | 0.003%  |
| 1 x Zhaoxin                       | 2        | 0.003%  |
| 1 x Loongson Technology           | 2        | 0.003%  |
| 1 x Intel + 4 x Nvidia            | 2        | 0.003%  |
| 1 x Intel + 3 x AMD               | 2        | 0.003%  |
| Intel + Silicon Motion            | 2        | 0.003%  |
| 6 x Nvidia                        | 1        | 0.001%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 57148    | 71.09%  |
| Proprietary | 18524    | 23.04%  |
| Unknown     | 4716     | 5.87%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 30932    | 37.76%  |
| 1.01-2.0   | 12523    | 15.29%  |
| 0.51-1.0   | 10696    | 13.06%  |
| 0.01-0.5   | 10175    | 12.42%  |
| 3.01-4.0   | 6243     | 7.62%   |
| 7.01-8.0   | 5928     | 7.24%   |
| 5.01-6.0   | 2418     | 2.95%   |
| 8.01-16.0  | 1739     | 2.12%   |
| 2.01-3.0   | 956      | 1.17%   |
| 16.01-24.0 | 231      | 0.28%   |
| 4.01-5.0   | 56       | 0.07%   |
| 32.01-64.0 | 6        | 0.01%   |
| 24.01-32.0 | 6        | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 14579    | 18.04%  |
| Goldstar             | 9208     | 11.4%   |
| Dell                 | 7836     | 9.7%    |
| Acer                 | 6434     | 7.96%   |
| Hewlett-Packard      | 5037     | 6.23%   |
| BenQ                 | 4216     | 5.22%   |
| AOC                  | 4001     | 4.95%   |
| Philips              | 3804     | 4.71%   |
| Ancor Communications | 3733     | 4.62%   |
| ViewSonic            | 2081     | 2.58%   |
| Iiyama               | 1389     | 1.72%   |
| LG Electronics       | 1130     | 1.4%    |
| ASUSTek Computer     | 1114     | 1.38%   |
| Unknown              | 1075     | 1.33%   |
| Lenovo               | 994      | 1.23%   |
| Sony                 | 971      | 1.2%    |
| NEC Computers        | 814      | 1.01%   |
| Eizo                 | 566      | 0.7%    |
| Fujitsu Siemens      | 565      | 0.7%    |
| Vizio                | 419      | 0.52%   |
| HannStar             | 416      | 0.51%   |
| MSI                  | 379      | 0.47%   |
| Sceptre Tech         | 351      | 0.43%   |
| Medion               | 338      | 0.42%   |
| Toshiba              | 327      | 0.4%    |
| Panasonic            | 299      | 0.37%   |
| Unknown              | 223      | 0.28%   |
| Gigabyte Technology  | 221      | 0.27%   |
| Vestel Elektronik    | 198      | 0.25%   |
| Hitachi              | 191      | 0.24%   |
| Idek Iiyama          | 173      | 0.21%   |
| Sharp                | 172      | 0.21%   |
| Plain Tree Systems   | 172      | 0.21%   |
| Belinea              | 170      | 0.21%   |
| ___                  | 169      | 0.21%   |
| Packard Bell         | 160      | 0.2%    |
| Insignia             | 145      | 0.18%   |
| AUS                  | 129      | 0.16%   |
| MStar                | 127      | 0.16%   |
| HKC                  | 127      | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 390      | 0.45%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 371      | 0.43%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 270      | 0.31%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 258      | 0.3%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 239      | 0.28%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 232      | 0.27%   |
| Unknown                                                               | 223      | 0.26%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 207      | 0.24%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 197      | 0.23%   |
| Vestel Elektronik 43UHD_LCD_TV VES3700 3840x2160 950x540mm 43.0-inch  | 196      | 0.23%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                   | 178      | 0.21%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 170      | 0.2%    |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 167      | 0.19%   |
| AOC 24B2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                    | 165      | 0.19%   |
| Samsung Electronics U28E590 SAM0C4D 1680x1050 610x350mm 27.7-inch     | 160      | 0.19%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 159      | 0.18%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch  | 156      | 0.18%   |
| AOC 27P2DG5 AOC2702 1920x1080 598x336mm 27.0-inch                     | 156      | 0.18%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch  | 154      | 0.18%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch  | 144      | 0.17%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                     | 142      | 0.16%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 134      | 0.16%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 128      | 0.15%   |
| BenQ GW2270 BNQ78DB 1920x1080 480x270mm 21.7-inch                     | 127      | 0.15%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch      | 123      | 0.14%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                      | 121      | 0.14%   |
| Acer AL1716 ACRAD46 1280x1024 338x270mm 17.0-inch                     | 116      | 0.13%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                    | 115      | 0.13%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                      | 111      | 0.13%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 110      | 0.13%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch             | 110      | 0.13%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                       | 108      | 0.13%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 106      | 0.12%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch      | 106      | 0.12%   |
| Panasonic TV MEIA296 3840x2160 708x398mm 32.0-inch                    | 105      | 0.12%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                       | 105      | 0.12%   |
| Goldstar W2243 GSM56FE 1920x1080 477x269mm 21.6-inch                  | 104      | 0.12%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch              | 104      | 0.12%   |
| AOC 2460G5 AOC2460 1920x1080 531x299mm 24.0-inch                      | 104      | 0.12%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                        | 104      | 0.12%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 34132    | 43.01%  |
| 1280x1024 (SXGA)   | 8199     | 10.33%  |
| 3840x2160 (4K)     | 5627     | 7.09%   |
| 2560x1440 (QHD)    | 4736     | 5.97%   |
| 1680x1050 (WSXGA+) | 4713     | 5.94%   |
| 1366x768 (WXGA)    | 3316     | 4.18%   |
| 1440x900 (WXGA+)   | 3197     | 4.03%   |
| 1600x900 (HD+)     | 2500     | 3.15%   |
| 1920x1200 (WUXGA)  | 2163     | 2.73%   |
| Unknown            | 1970     | 2.48%   |
| 1360x768           | 1452     | 1.83%   |
| 3440x1440          | 1127     | 1.42%   |
| 2560x1080          | 1110     | 1.4%    |
| 3840x1080          | 837      | 1.05%   |
| 1024x768 (XGA)     | 776      | 0.98%   |
| 1600x1200          | 499      | 0.63%   |
| 1920x540           | 464      | 0.58%   |
| 1280x720 (HD)      | 258      | 0.33%   |
| 2560x1600          | 150      | 0.19%   |
| 2288x1287          | 130      | 0.16%   |
| 3840x1600          | 105      | 0.13%   |
| 3840x1200          | 101      | 0.13%   |
| 4480x1440          | 99       | 0.12%   |
| 2048x1152          | 92       | 0.12%   |
| 5760x1080          | 87       | 0.11%   |
| 3200x1080          | 83       | 0.1%    |
| 1400x1050          | 82       | 0.1%    |
| 1280x960           | 81       | 0.1%    |
| 5120x1440          | 66       | 0.08%   |
| 1152x864           | 66       | 0.08%   |
| 5760x2160          | 65       | 0.08%   |
| 3600x1080          | 62       | 0.08%   |
| 7680x2160          | 51       | 0.06%   |
| 1280x768           | 49       | 0.06%   |
| 3360x1080          | 33       | 0.04%   |
| 3520x1080          | 31       | 0.04%   |
| 4480x1080          | 28       | 0.04%   |
| 2048x1536          | 28       | 0.04%   |
| 3286x1080          | 27       | 0.03%   |
| 1280x800 (WXGA)    | 27       | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 9538     | 11.85%  |
| 24      | 9518     | 11.82%  |
| 21      | 9269     | 11.51%  |
| 27      | 8999     | 11.18%  |
| Unknown | 7931     | 9.85%   |
| 19      | 6763     | 8.4%    |
| 17      | 4074     | 5.06%   |
| 18      | 3709     | 4.61%   |
| 22      | 3161     | 3.93%   |
| 20      | 3096     | 3.84%   |
| 31      | 2664     | 3.31%   |
| 34      | 1806     | 2.24%   |
| 15      | 1520     | 1.89%   |
| 84      | 918      | 1.14%   |
| 72      | 835      | 1.04%   |
| 32      | 778      | 0.97%   |
| 40      | 719      | 0.89%   |
| 54      | 550      | 0.68%   |
| 25      | 541      | 0.67%   |
| 26      | 328      | 0.41%   |
| 28      | 260      | 0.32%   |
| 48      | 259      | 0.32%   |
| 52      | 244      | 0.3%    |
| 46      | 213      | 0.26%   |
| 42      | 191      | 0.24%   |
| 16      | 189      | 0.23%   |
| 65      | 187      | 0.23%   |
| 37      | 178      | 0.22%   |
| 29      | 164      | 0.2%    |
| 49      | 149      | 0.19%   |
| 33      | 135      | 0.17%   |
| 12      | 127      | 0.16%   |
| 39      | 123      | 0.15%   |
| 47      | 116      | 0.14%   |
| 36      | 111      | 0.14%   |
| 35      | 110      | 0.14%   |
| 14      | 109      | 0.14%   |
| 43      | 102      | 0.13%   |
| 142     | 94       | 0.12%   |
| 13      | 91       | 0.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 25958    | 33.2%   |
| 401-500        | 21606    | 27.64%  |
| Unknown        | 7931     | 10.14%  |
| 301-350        | 5449     | 6.97%   |
| 351-400        | 4445     | 5.69%   |
| 601-700        | 4114     | 5.26%   |
| 701-800        | 2812     | 3.6%    |
| 1001-1500      | 2014     | 2.58%   |
| 1501-2000      | 1881     | 2.41%   |
| 801-900        | 1151     | 1.47%   |
| 901-1000       | 382      | 0.49%   |
| 201-300        | 321      | 0.41%   |
| More than 2000 | 105      | 0.13%   |
| 101-200        | 10       | 0.01%   |
| 1-100          | 3        | 0.004%  |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 45275    | 60.22%  |
| 16/10   | 9926     | 13.2%   |
| 5/4     | 7629     | 10.15%  |
| Unknown | 6924     | 9.21%   |
| 21/9    | 2160     | 2.87%   |
| 4/3     | 1996     | 2.66%   |
| 3/2     | 498      | 0.66%   |
| 32/9    | 301      | 0.4%    |
| 6/5     | 259      | 0.34%   |
| 1.00    | 109      | 0.14%   |
| 1.96    | 47       | 0.06%   |
| 0.56    | 11       | 0.01%   |
| 3.20    | 10       | 0.01%   |
| 2.00    | 8        | 0.01%   |
| 2.12    | 4        | 0.01%   |
| 11/10   | 4        | 0.01%   |
| 0.80    | 4        | 0.01%   |
| 0.89    | 3        | 0.004%  |
| 0.25    | 2        | 0.003%  |
| 3.76    | 1        | 0.001%  |
| 2.65    | 1        | 0.001%  |
| 2.01    | 1        | 0.001%  |
| 1.03    | 1        | 0.001%  |
| 0.75    | 1        | 0.001%  |
| 0.57    | 1        | 0.001%  |
| 0.31    | 1        | 0.001%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 25425    | 32.18%  |
| 151-200        | 12657    | 16.02%  |
| 301-350        | 9197     | 11.64%  |
| Unknown        | 7931     | 10.04%  |
| 141-150        | 6699     | 8.48%   |
| 351-500        | 5664     | 7.17%   |
| 251-300        | 3648     | 4.62%   |
| More than 1000 | 3418     | 4.33%   |
| 501-1000       | 2108     | 2.67%   |
| 101-110        | 1149     | 1.45%   |
| 111-120        | 417      | 0.53%   |
| 131-140        | 248      | 0.31%   |
| 71-80          | 144      | 0.18%   |
| 121-130        | 109      | 0.14%   |
| 91-100         | 82       | 0.1%    |
| 81-90          | 75       | 0.09%   |
| 51-60          | 16       | 0.02%   |
| 1-40           | 13       | 0.02%   |
| 41-50          | 9        | 0.01%   |
| 61-70          | 6        | 0.01%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 47481    | 62.77%  |
| 101-120       | 13621    | 18.01%  |
| Unknown       | 7932     | 10.49%  |
| 1-50          | 3284     | 4.34%   |
| 121-160       | 2308     | 3.05%   |
| 161-240       | 994      | 1.31%   |
| More than 240 | 17       | 0.02%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 62577    | 78.36%  |
| 2     | 10910    | 13.66%  |
| 0     | 4981     | 6.24%   |
| 3     | 1239     | 1.55%   |
| 4     | 136      | 0.17%   |
| 5     | 10       | 0.01%   |
| 6     | 4        | 0.01%   |
| 7     | 1        | 0.001%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 48126    | 44.26%  |
| Intel                             | 27298    | 25.1%   |
| Qualcomm Atheros                  | 7832     | 7.2%    |
| Broadcom                          | 3184     | 2.93%   |
| Ralink Technology                 | 2958     | 2.72%   |
| Nvidia                            | 2862     | 2.63%   |
| TP-Link                           | 1829     | 1.68%   |
| Ralink                            | 1426     | 1.31%   |
| Marvell Technology Group          | 1077     | 0.99%   |
| Qualcomm Atheros Communications   | 886      | 0.81%   |
| Broadcom Limited                  | 728      | 0.67%   |
| MediaTek                          | 704      | 0.65%   |
| D-Link System                     | 639      | 0.59%   |
| Huawei Technologies               | 609      | 0.56%   |
| VIA Technologies                  | 603      | 0.55%   |
| D-Link                            | 596      | 0.55%   |
| NetGear                           | 571      | 0.53%   |
| Samsung Electronics               | 558      | 0.51%   |
| Microsoft                         | 543      | 0.5%    |
| ASUSTek Computer                  | 498      | 0.46%   |
| Aquantia                          | 445      | 0.41%   |
| Xiaomi                            | 337      | 0.31%   |
| ASIX Electronics                  | 253      | 0.23%   |
| Edimax Technology                 | 242      | 0.22%   |
| Belkin Components                 | 212      | 0.19%   |
| Linksys                           | 201      | 0.18%   |
| IMC Networks                      | 159      | 0.15%   |
| ZTE WCDMA Technologies MSM        | 131      | 0.12%   |
| Motorola PCS                      | 127      | 0.12%   |
| 3Com                              | 124      | 0.11%   |
| Sundance Technology Inc / IC Plus | 111      | 0.1%    |
| AVM                               | 109      | 0.1%    |
| Silicon Integrated Systems [SiS]  | 105      | 0.1%    |
| Qualcomm                          | 97       | 0.09%   |
| Mellanox Technologies             | 97       | 0.09%   |
| DisplayLink                       | 91       | 0.08%   |
| Gemtek                            | 81       | 0.07%   |
| Google                            | 77       | 0.07%   |
| OPPO Electronics                  | 76       | 0.07%   |
| Arduino SA                        | 73       | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 38575    | 31.82%  |
| Intel I211 Gigabit Network Connection                             | 3960     | 3.27%   |
| Intel Wi-Fi 6 AX200                                               | 2835     | 2.34%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2749     | 2.27%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2648     | 2.18%   |
| Intel Ethernet Connection (2) I219-V                              | 2632     | 2.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2204     | 1.82%   |
| Nvidia MCP61 Ethernet                                             | 1577     | 1.3%    |
| Intel Ethernet Connection I217-LM                                 | 1483     | 1.22%   |
| Intel Ethernet Controller I225-V                                  | 1375     | 1.13%   |
| Intel 82579V Gigabit Network Connection                           | 1371     | 1.13%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1356     | 1.12%   |
| Ralink MT7601U Wireless Adapter                                   | 1283     | 1.06%   |
| Intel Ethernet Connection (7) I219-V                              | 1186     | 0.98%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1115     | 0.92%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1062     | 0.88%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 920      | 0.76%   |
| Intel Ethernet Connection (2) I218-V                              | 847      | 0.7%    |
| Intel Ethernet Connection I217-V                                  | 830      | 0.68%   |
| Intel Wireless-AC 9260                                            | 769      | 0.63%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 743      | 0.61%   |
| Qualcomm Atheros AR9271 802.11n                                   | 736      | 0.61%   |
| Intel 82574L Gigabit Network Connection                           | 736      | 0.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 705      | 0.58%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 703      | 0.58%   |
| Realtek 802.11ac NIC                                              | 654      | 0.54%   |
| Intel Ethernet Connection (2) I219-LM                             | 622      | 0.51%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 607      | 0.5%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 567      | 0.47%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 553      | 0.46%   |
| Ralink RT5370 Wireless Adapter                                    | 550      | 0.45%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 545      | 0.45%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 533      | 0.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 486      | 0.4%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 477      | 0.39%   |
| Intel I210 Gigabit Network Connection                             | 472      | 0.39%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 469      | 0.39%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 463      | 0.38%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 460      | 0.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 455      | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 8768     | 26.68%  |
| Realtek Semiconductor                 | 7385     | 22.47%  |
| Qualcomm Atheros                      | 3606     | 10.97%  |
| Ralink Technology                     | 2958     | 9%      |
| TP-Link                               | 1658     | 5.05%   |
| Ralink                                | 1424     | 4.33%   |
| Broadcom                              | 1282     | 3.9%    |
| Qualcomm Atheros Communications       | 886      | 2.7%    |
| D-Link                                | 576      | 1.75%   |
| NetGear                               | 564      | 1.72%   |
| MediaTek                              | 557      | 1.7%    |
| Microsoft                             | 537      | 1.63%   |
| ASUSTek Computer                      | 479      | 1.46%   |
| D-Link System                         | 362      | 1.1%    |
| Edimax Technology                     | 242      | 0.74%   |
| Belkin Components                     | 207      | 0.63%   |
| Linksys                               | 191      | 0.58%   |
| Broadcom Limited                      | 169      | 0.51%   |
| IMC Networks                          | 159      | 0.48%   |
| AVM                                   | 109      | 0.33%   |
| Gemtek                                | 62       | 0.19%   |
| Sitecom Europe                        | 60       | 0.18%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 57       | 0.17%   |
| Mercucys                              | 50       | 0.15%   |
| ZyDAS                                 | 49       | 0.15%   |
| ZyXEL Communications                  | 46       | 0.14%   |
| Marvell Technology Group              | 38       | 0.12%   |
| Wilocity                              | 32       | 0.1%    |
| BUFFALO                               | 31       | 0.09%   |
| Micro Star International              | 30       | 0.09%   |
| Realtek                               | 25       | 0.08%   |
| Wacom                                 | 20       | 0.06%   |
| TRENDnet                              | 20       | 0.06%   |
| Texas Instruments                     | 19       | 0.06%   |
| Accton Technology                     | 18       | 0.05%   |
| Xiaomi                                | 14       | 0.04%   |
| Guillemot                             | 14       | 0.04%   |
| PLANEX                                | 13       | 0.04%   |
| AboCom Systems                        | 13       | 0.04%   |
| Philips (or NXP)                      | 10       | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 2835     | 8.5%    |
| Ralink MT7601U Wireless Adapter                                | 1283     | 3.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1115     | 3.34%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1062     | 3.18%   |
| Intel Wireless-AC 9260                                         | 769      | 2.31%   |
| Qualcomm Atheros AR9271 802.11n                                | 736      | 2.21%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 705      | 2.11%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 703      | 2.11%   |
| Realtek 802.11ac NIC                                           | 654      | 1.96%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 567      | 1.7%    |
| Ralink RT5370 Wireless Adapter                                 | 550      | 1.65%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 533      | 1.6%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 477      | 1.43%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 460      | 1.38%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 444      | 1.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 439      | 1.32%   |
| Intel Wireless 7260                                            | 422      | 1.27%   |
| Intel Wireless 3165                                            | 392      | 1.18%   |
| Intel Wireless 7265                                            | 372      | 1.12%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 371      | 1.11%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 365      | 1.09%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 351      | 1.05%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 348      | 1.04%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 341      | 1.02%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 332      | 1%      |
| Intel Wireless 8260                                            | 307      | 0.92%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 304      | 0.91%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 300      | 0.9%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 289      | 0.87%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 281      | 0.84%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 273      | 0.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 265      | 0.79%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 259      | 0.78%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 258      | 0.77%   |
| Microsoft Xbox 360 Wireless Adapter                            | 256      | 0.77%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 246      | 0.74%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 242      | 0.73%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 242      | 0.73%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 240      | 0.72%   |
| Intel Wireless 8265 / 8275                                     | 235      | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 45263    | 53.99%  |
| Intel                                  | 22928    | 27.35%  |
| Qualcomm Atheros                       | 4559     | 5.44%   |
| Nvidia                                 | 2859     | 3.41%   |
| Broadcom                               | 1957     | 2.33%   |
| Marvell Technology Group               | 1042     | 1.24%   |
| VIA Technologies                       | 584      | 0.7%    |
| Broadcom Limited                       | 560      | 0.67%   |
| Aquantia                               | 445      | 0.53%   |
| Samsung Electronics                    | 391      | 0.47%   |
| Xiaomi                                 | 323      | 0.39%   |
| Huawei Technologies                    | 299      | 0.36%   |
| D-Link System                          | 278      | 0.33%   |
| ASIX Electronics                       | 253      | 0.3%    |
| TP-Link                                | 179      | 0.21%   |
| MediaTek                               | 141      | 0.17%   |
| 3Com                                   | 123      | 0.15%   |
| ZTE WCDMA Technologies MSM             | 118      | 0.14%   |
| Sundance Technology Inc / IC Plus      | 111      | 0.13%   |
| Silicon Integrated Systems [SiS]       | 103      | 0.12%   |
| DisplayLink                            | 91       | 0.11%   |
| Qualcomm                               | 90       | 0.11%   |
| Motorola PCS                           | 84       | 0.1%    |
| Mellanox Technologies                  | 79       | 0.09%   |
| OPPO Electronics                       | 75       | 0.09%   |
| Google                                 | 75       | 0.09%   |
| JMicron Technology                     | 54       | 0.06%   |
| HTC (High Tech Computer)               | 53       | 0.06%   |
| Apple                                  | 46       | 0.05%   |
| ICS Advent                             | 35       | 0.04%   |
| Sony Ericsson Mobile Communications AB | 34       | 0.04%   |
| ADMtek                                 | 31       | 0.04%   |
| T & A Mobile Phones                    | 29       | 0.03%   |
| OnePlus Technology (Shenzhen)          | 29       | 0.03%   |
| HMD Global                             | 29       | 0.03%   |
| American Megatrends                    | 27       | 0.03%   |
| Spreadtrum Communications              | 24       | 0.03%   |
| Lenovo                                 | 24       | 0.03%   |
| LG Electronics                         | 23       | 0.03%   |
| Accton Technology                      | 23       | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 38575    | 44.63%  |
| Intel I211 Gigabit Network Connection                             | 3960     | 4.58%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2749     | 3.18%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2648     | 3.06%   |
| Intel Ethernet Connection (2) I219-V                              | 2632     | 3.05%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2204     | 2.55%   |
| Nvidia MCP61 Ethernet                                             | 1577     | 1.82%   |
| Intel Ethernet Connection I217-LM                                 | 1483     | 1.72%   |
| Intel Ethernet Controller I225-V                                  | 1375     | 1.59%   |
| Intel 82579V Gigabit Network Connection                           | 1371     | 1.59%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1356     | 1.57%   |
| Intel Ethernet Connection (7) I219-V                              | 1186     | 1.37%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 920      | 1.06%   |
| Intel Ethernet Connection (2) I218-V                              | 847      | 0.98%   |
| Intel Ethernet Connection I217-V                                  | 830      | 0.96%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 743      | 0.86%   |
| Intel 82574L Gigabit Network Connection                           | 736      | 0.85%   |
| Intel Ethernet Connection (2) I219-LM                             | 622      | 0.72%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 607      | 0.7%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 553      | 0.64%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 545      | 0.63%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 486      | 0.56%   |
| Intel I210 Gigabit Network Connection                             | 472      | 0.55%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 469      | 0.54%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 463      | 0.54%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 455      | 0.53%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 451      | 0.52%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 388      | 0.45%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 356      | 0.41%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 324      | 0.37%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 307      | 0.36%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 303      | 0.35%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 289      | 0.33%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 283      | 0.33%   |
| Intel 82578DM Gigabit Network Connection                          | 277      | 0.32%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 275      | 0.32%   |
| Nvidia MCP77 Ethernet                                             | 262      | 0.3%    |
| Intel Ethernet Connection (14) I219-V                             | 262      | 0.3%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 261      | 0.3%    |
| Intel Ethernet Connection (7) I219-LM                             | 258      | 0.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 77027    | 70.74%  |
| WiFi     | 30460    | 27.97%  |
| Modem    | 1169     | 1.07%   |
| Unknown  | 232      | 0.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 62507    | 78.08%  |
| WiFi     | 17491    | 21.85%  |
| Modem    | 27       | 0.03%   |
| Unknown  | 27       | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 53773    | 68.42%  |
| 2     | 20737    | 26.38%  |
| 3     | 2690     | 3.42%   |
| 0     | 673      | 0.86%   |
| 4     | 420      | 0.53%   |
| 5     | 158      | 0.2%    |
| 6     | 76       | 0.1%    |
| 7     | 26       | 0.03%   |
| 8     | 14       | 0.02%   |
| 9     | 8        | 0.01%   |
| 13    | 4        | 0.01%   |
| 10    | 4        | 0.01%   |
| 18    | 3        | 0.004%  |
| 17    | 2        | 0.003%  |
| 12    | 2        | 0.003%  |
| 33    | 1        | 0.001%  |
| 32    | 1        | 0.001%  |
| 21    | 1        | 0.001%  |
| 14    | 1        | 0.001%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Desktops | Percent |
|---------|----------|---------|
| No      | 63776    | 79.75%  |
| Yes     | 12124    | 15.16%  |
| Unknown | 4068     | 5.09%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 8011     | 38.57%  |
| Cambridge Silicon Radio         | 5654     | 27.22%  |
| ASUSTek Computer                | 1482     | 7.13%   |
| Realtek Semiconductor           | 1377     | 6.63%   |
| Broadcom                        | 1179     | 5.68%   |
| Qualcomm Atheros Communications | 780      | 3.76%   |
| IMC Networks                    | 366      | 1.76%   |
| MediaTek                        | 318      | 1.53%   |
| Apple                           | 290      | 1.4%    |
| TP-Link                         | 172      | 0.83%   |
| Integrated System Solution      | 167      | 0.8%    |
| Lite-On Technology              | 139      | 0.67%   |
| Belkin Components               | 99       | 0.48%   |
| Dynex                           | 90       | 0.43%   |
| Foxconn / Hon Hai               | 81       | 0.39%   |
| Edimax Technology               | 63       | 0.3%    |
| HTC (High Tech Computer)        | 53       | 0.26%   |
| Micro Star International        | 46       | 0.22%   |
| Ralink                          | 41       | 0.2%    |
| Logitech                        | 38       | 0.18%   |
| Dell                            | 36       | 0.17%   |
| Conwise Technology              | 35       | 0.17%   |
| Hewlett-Packard                 | 33       | 0.16%   |
| Realtek                         | 32       | 0.15%   |
| ISSC                            | 24       | 0.12%   |
| SINO WEALTH                     | 14       | 0.07%   |
| Roper                           | 13       | 0.06%   |
| Primax Electronics              | 13       | 0.06%   |
| Actions                         | 13       | 0.06%   |
| Unknown                         | 13       | 0.06%   |
| Toshiba                         | 12       | 0.06%   |
| D-Link System                   | 11       | 0.05%   |
| D-Link                          | 8        | 0.04%   |
| Kensington                      | 7        | 0.03%   |
| Creative Technology             | 6        | 0.03%   |
| Sitecom Europe                  | 5        | 0.02%   |
| Mobile Action Technology        | 5        | 0.02%   |
| Fujitsu                         | 5        | 0.02%   |
| Accel Semiconductor             | 5        | 0.02%   |
| Qcom                            | 4        | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 5653     | 27.15%  |
| Intel AX200 Bluetooth                                                | 2620     | 12.58%  |
| Intel Bluetooth wireless interface                                   | 1724     | 8.28%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 1076     | 5.17%   |
| Realtek Bluetooth Radio                                              | 964      | 4.63%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 741      | 3.56%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 666      | 3.2%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 560      | 2.69%   |
| Intel AX201 Bluetooth                                                | 545      | 2.62%   |
| Intel AX210 Bluetooth                                                | 524      | 2.52%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 510      | 2.45%   |
| MediaTek Wireless_Device                                             | 317      | 1.52%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 273      | 1.31%   |
| Qualcomm Atheros  Bluetooth Device                                   | 258      | 1.24%   |
| ASUS Bluetooth Radio                                                 | 258      | 1.24%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 221      | 1.06%   |
| IMC Networks Bluetooth Radio                                         | 201      | 0.97%   |
| ASUS ASUS USB-BT500                                                  | 186      | 0.89%   |
| TP-Link UB500 Adapter                                                | 172      | 0.83%   |
| Intel Bluetooth Device                                               | 140      | 0.67%   |
| ASUS BCM20702A0                                                      | 136      | 0.65%   |
| Apple Bluetooth Host Controller                                      | 128      | 0.61%   |
| ASUS Bluetooth Adapter                                               | 121      | 0.58%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 116      | 0.56%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 110      | 0.53%   |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 101      | 0.49%   |
| Lite-On Bluetooth Device                                             | 94       | 0.45%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 90       | 0.43%   |
| Integrated System Solution Bluetooth Device                          | 90       | 0.43%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 90       | 0.43%   |
| Broadcom BCM2045 Bluetooth                                           | 89       | 0.43%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 80       | 0.38%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                | 77       | 0.37%   |
| Realtek RTL8821A Bluetooth                                           | 76       | 0.37%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 76       | 0.37%   |
| ASUS Bluetooth Device                                                | 74       | 0.36%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 59       | 0.28%   |
| IMC Networks Bluetooth Device                                        | 59       | 0.28%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 53       | 0.25%   |
| Foxconn / Hon Hai Wireless_Device                                    | 51       | 0.24%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 47118    | 36.54%  |
| AMD                                  | 32904    | 25.52%  |
| Nvidia                               | 31420    | 24.37%  |
| C-Media Electronics                  | 3386     | 2.63%   |
| Creative Labs                        | 1869     | 1.45%   |
| Logitech                             | 1237     | 0.96%   |
| Texas Instruments                    | 643      | 0.5%    |
| VIA Technologies                     | 588      | 0.46%   |
| JMTek                                | 552      | 0.43%   |
| Kingston Technology                  | 488      | 0.38%   |
| Creative Technology                  | 461      | 0.36%   |
| ASUSTek Computer                     | 442      | 0.34%   |
| Generalplus Technology               | 394      | 0.31%   |
| Focusrite-Novation                   | 394      | 0.31%   |
| Razer USA                            | 383      | 0.3%    |
| Corsair                              | 361      | 0.28%   |
| SteelSeries ApS                      | 360      | 0.28%   |
| GN Netcom                            | 296      | 0.23%   |
| Plantronics                          | 243      | 0.19%   |
| Blue Microphones                     | 230      | 0.18%   |
| Micro Star International             | 178      | 0.14%   |
| Tenx Technology                      | 169      | 0.13%   |
| Realtek Semiconductor                | 148      | 0.11%   |
| Samson Technologies                  | 142      | 0.11%   |
| Silicon Integrated Systems [SiS]     | 140      | 0.11%   |
| BEHRINGER International              | 138      | 0.11%   |
| Sony                                 | 129      | 0.1%    |
| M-Audio                              | 122      | 0.09%   |
| Yamaha                               | 121      | 0.09%   |
| Dell                                 | 115      | 0.09%   |
| GYROCOM C&C                          | 112      | 0.09%   |
| DSEA A/S                             | 107      | 0.08%   |
| Giga-Byte Technology                 | 100      | 0.08%   |
| XMOS                                 | 99       | 0.08%   |
| RODE Microphones                     | 93       | 0.07%   |
| SAVITECH                             | 90       | 0.07%   |
| Ensoniq                              | 82       | 0.06%   |
| Microsoft                            | 79       | 0.06%   |
| Thesycon Systemsoftware & Consulting | 70       | 0.05%   |
| Astro Gaming                         | 70       | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                                      | 6995     | 4.69%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 6418     | 4.3%    |
| AMD Starship/Matisse HD Audio Controller                                          | 6168     | 4.13%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 5788     | 3.88%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 5213     | 3.49%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 4307     | 2.89%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 3993     | 2.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 3873     | 2.6%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 3616     | 2.42%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 3335     | 2.23%   |
| AMD Family 17h/19h HD Audio Controller                                            | 3326     | 2.23%   |
| Intel 200 Series PCH HD Audio                                                     | 3283     | 2.2%    |
| AMD FCH Azalia Controller                                                         | 2893     | 1.94%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 2808     | 1.88%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 2455     | 1.64%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 2379     | 1.59%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 2284     | 1.53%   |
| Intel Cannon Lake PCH cAVS                                                        | 2270     | 1.52%   |
| Nvidia High Definition Audio Controller                                           | 2159     | 1.45%   |
| Nvidia GF108 High Definition Audio Controller                                     | 1839     | 1.23%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 1824     | 1.22%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 1770     | 1.19%   |
| Nvidia GP106 High Definition Audio Controller                                     | 1763     | 1.18%   |
| Nvidia MCP61 High Definition Audio                                                | 1749     | 1.17%   |
| Nvidia GP104 High Definition Audio Controller                                     | 1680     | 1.13%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 1668     | 1.12%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 1412     | 0.95%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 1407     | 0.94%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 1364     | 0.91%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 1310     | 0.88%   |
| Nvidia TU116 High Definition Audio Controller                                     | 1301     | 0.87%   |
| AMD Navi 10 HDMI Audio                                                            | 1284     | 0.86%   |
| Nvidia GK107 HDMI Audio Controller                                                | 1254     | 0.84%   |
| Nvidia GF119 HDMI Audio Controller                                                | 1187     | 0.8%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 1114     | 0.75%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 1107     | 0.74%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1097     | 0.74%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 998      | 0.67%   |
| Nvidia GP108 High Definition Audio Controller                                     | 960      | 0.64%   |
| Nvidia TU106 High Definition Audio Controller                                     | 952      | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 12694    | 24.5%   |
| Kingston            | 9075     | 17.51%  |
| Corsair             | 5287     | 10.2%   |
| Samsung Electronics | 4303     | 8.3%    |
| Crucial             | 3934     | 7.59%   |
| SK hynix            | 3473     | 6.7%    |
| G.Skill             | 3382     | 6.53%   |
| Micron Technology   | 1857     | 3.58%   |
| A-DATA Technology   | 853      | 1.65%   |
| Patriot             | 769      | 1.48%   |
| Team                | 609      | 1.18%   |
| Nanya Technology    | 580      | 1.12%   |
| AMD                 | 362      | 0.7%    |
| Unknown             | 330      | 0.64%   |
| Elpida              | 325      | 0.63%   |
| Ramaxel Technology  | 314      | 0.61%   |
| GOODRAM             | 309      | 0.6%    |
| Transcend           | 288      | 0.56%   |
| Kingmax             | 190      | 0.37%   |
| Apacer              | 184      | 0.36%   |
| Silicon Power       | 172      | 0.33%   |
| GeIL                | 143      | 0.28%   |
| Smart               | 139      | 0.27%   |
| Unknown (ABCD)      | 129      | 0.25%   |
| Unifosa             | 101      | 0.19%   |
| PNY                 | 99       | 0.19%   |
| Qumo                | 82       | 0.16%   |
| Goldkey             | 80       | 0.15%   |
| Qimonda             | 79       | 0.15%   |
| Foxline             | 64       | 0.12%   |
| Avant               | 64       | 0.12%   |
| Kllisre             | 60       | 0.12%   |
| Atermiter           | 50       | 0.1%    |
| CSX                 | 49       | 0.09%   |
| KETECH              | 42       | 0.08%   |
| Hewlett-Packard     | 41       | 0.08%   |
| ASint Technology    | 39       | 0.08%   |
| OCZ                 | 36       | 0.07%   |
| Ramos Technology    | 34       | 0.07%   |
| Hikvision           | 33       | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s             | 640      | 1.1%    |
| Unknown RAM Module 2048MB DIMM SDRAM                    | 610      | 1.04%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                 | 576      | 0.99%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                  | 569      | 0.97%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                 | 520      | 0.89%   |
| Unknown RAM Module 1024MB DIMM SDRAM                    | 491      | 0.84%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s   | 465      | 0.8%    |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s             | 381      | 0.65%   |
| Unknown                                                 | 330      | 0.57%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s     | 325      | 0.56%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s   | 323      | 0.55%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s     | 303      | 0.52%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                  | 299      | 0.51%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s             | 294      | 0.5%    |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s            | 282      | 0.48%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s             | 279      | 0.48%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 267      | 0.46%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                | 250      | 0.43%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s       | 248      | 0.42%   |
| Unknown RAM Module 2GB DIMM SDRAM                       | 245      | 0.42%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s     | 242      | 0.41%   |
| G.Skill RAM F4-3200C16-16GVK 16384MB DIMM DDR4 3600MT/s | 230      | 0.39%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s    | 224      | 0.38%   |
| Unknown RAM Module 2GB DIMM 800MT/s                     | 216      | 0.37%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                 | 212      | 0.36%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s     | 210      | 0.36%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                  | 209      | 0.36%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                  | 200      | 0.34%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s    | 196      | 0.34%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s  | 195      | 0.33%   |
| Kingston RAM KHX2400C15/8G 8192MB DIMM DDR4 3400MT/s    | 194      | 0.33%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s               | 188      | 0.32%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s  | 185      | 0.32%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                    | 183      | 0.31%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                  | 183      | 0.31%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s     | 178      | 0.3%    |
| Unknown RAM Module 512MB DIMM SDRAM                     | 177      | 0.3%    |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s   | 174      | 0.3%    |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s     | 167      | 0.29%   |
| Unknown RAM Module 1024MB DIMM                          | 165      | 0.28%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind         | Desktops | Percent |
|--------------|----------|---------|
| DDR4         | 16561    | 35.81%  |
| DDR3         | 15790    | 34.15%  |
| Unknown      | 5196     | 11.24%  |
| DDR2         | 4078     | 8.82%   |
| SDRAM        | 3091     | 6.68%   |
| DDR          | 918      | 1.99%   |
| DDR5         | 365      | 0.79%   |
| LPDDR4       | 175      | 0.38%   |
| DRAM         | 49       | 0.11%   |
| LPDDR3       | 16       | 0.03%   |
| DDR2 FB-DIMM | 2        | 0.004%  |
| RAM          | 1        | 0.002%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| DIMM            | 43162    | 95.07%  |
| SODIMM          | 2020     | 4.45%   |
| RIMM            | 87       | 0.19%   |
| FB-DIMM         | 84       | 0.19%   |
| Row Of Chips    | 33       | 0.07%   |
| Unknown         | 10       | 0.02%   |
| Proprietary Car | 1        | 0.002%  |
| Chip            | 1        | 0.002%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Desktops | Percent |
|---------|----------|---------|
| 8192    | 14996    | 29.23%  |
| 4096    | 13144    | 25.62%  |
| 2048    | 10224    | 19.93%  |
| 16384   | 5709     | 11.13%  |
| 1024    | 4426     | 8.63%   |
| 32768   | 1582     | 3.08%   |
| 512     | 963      | 1.88%   |
| 256     | 198      | 0.39%   |
| 65536   | 14       | 0.03%   |
| 128     | 11       | 0.02%   |
| 32      | 7        | 0.01%   |
| 16      | 7        | 0.01%   |
| 1536    | 4        | 0.01%   |
| 64      | 4        | 0.01%   |
| 3072    | 2        | 0.004%  |
| Unknown | 2        | 0.004%  |
| 131072  | 1        | 0.002%  |
| 13      | 1        | 0.002%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 8969     | 17.65%  |
| 1333    | 6956     | 13.69%  |
| 800     | 3576     | 7.04%   |
| 3200    | 3281     | 6.46%   |
| 2400    | 2841     | 5.59%   |
| 3600    | 2614     | 5.14%   |
| Unknown | 2395     | 4.71%   |
| 667     | 2194     | 4.32%   |
| 2133    | 2178     | 4.29%   |
| 2667    | 2072     | 4.08%   |
| 1867    | 1057     | 2.08%   |
| 1866    | 846      | 1.66%   |
| 3400    | 742      | 1.46%   |
| 3000    | 740      | 1.46%   |
| 400     | 735      | 1.45%   |
| 1066    | 713      | 1.4%    |
| 2666    | 614      | 1.21%   |
| 1800    | 587      | 1.16%   |
| 2933    | 539      | 1.06%   |
| 533     | 456      | 0.9%    |
| 3733    | 405      | 0.8%    |
| 3800    | 360      | 0.71%   |
| 3533    | 353      | 0.69%   |
| 2800    | 334      | 0.66%   |
| 333     | 333      | 0.66%   |
| 3466    | 331      | 0.65%   |
| 3866    | 322      | 0.63%   |
| 1067    | 322      | 0.63%   |
| 3266    | 245      | 0.48%   |
| 1334    | 199      | 0.39%   |
| 2048    | 183      | 0.36%   |
| 4800    | 170      | 0.33%   |
| 3666    | 169      | 0.33%   |
| 2000    | 153      | 0.3%    |
| 266     | 144      | 0.28%   |
| 3333    | 130      | 0.26%   |
| 1648    | 129      | 0.25%   |
| 1639    | 114      | 0.22%   |
| 3534    | 113      | 0.22%   |
| 49926   | 107      | 0.21%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Hewlett-Packard                 | 1733     | 34.74%  |
| Canon                           | 851      | 17.06%  |
| Brother Industries              | 776      | 15.56%  |
| Samsung Electronics             | 599      | 12.01%  |
| Seiko Epson                     | 438      | 8.78%   |
| Xerox                           | 70       | 1.4%    |
| Prolific Technology             | 64       | 1.28%   |
| Dymo-CoStar                     | 53       | 1.06%   |
| Lexmark International           | 51       | 1.02%   |
| QinHeng Electronics             | 49       | 0.98%   |
| Kyocera                         | 49       | 0.98%   |
| Pantum                          | 42       | 0.84%   |
| Ricoh                           | 32       | 0.64%   |
| Panasonic (Matsushita)          | 31       | 0.62%   |
| Zebra                           | 21       | 0.42%   |
| STMicroelectronics              | 14       | 0.28%   |
| Dell                            | 13       | 0.26%   |
| Fuji Xerox                      | 12       | 0.24%   |
| Oki Data                        | 11       | 0.22%   |
| Apple                           | 9        | 0.18%   |
| Konica Minolta                  | 6        | 0.12%   |
| Star Micronics                  | 5        | 0.1%    |
| TSC Auto ID Technology          | 4        | 0.08%   |
| Citizen                         | 4        | 0.08%   |
| WinChipHead                     | 3        | 0.06%   |
| Sharp                           | 3        | 0.06%   |
| NXP Semiconductors              | 3        | 0.06%   |
| Magic Control Technology        | 3        | 0.06%   |
| Datamax-O'Neil                  | 3        | 0.06%   |
| Custom Engineering SPA          | 3        | 0.06%   |
| BESTEASY                        | 3        | 0.06%   |
| ATEN International              | 3        | 0.06%   |
| Zhuhai Poskey Technology        | 2        | 0.04%   |
| Toshiba TEC                     | 2        | 0.04%   |
| Seiko Instruments               | 2        | 0.04%   |
| Samsung Info. Systems America   | 2        | 0.04%   |
| GODEX INTERNATIONAL             | 2        | 0.04%   |
| cab Produkttechnik GmbH & Co KG | 2        | 0.04%   |
| Yurex                           | 1        | 0.02%   |
| Sato                            | 1        | 0.02%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| HP LaserJet 1020                      | 92       | 1.82%   |
| HP LaserJet 1018                      | 67       | 1.33%   |
| Prolific PL2305 Parallel Port         | 64       | 1.27%   |
| HP DeskJet 2600 series                | 60       | 1.19%   |
| Brother Printer                       | 57       | 1.13%   |
| Samsung SCX-4200 series               | 50       | 0.99%   |
| Samsung M2020 Series                  | 50       | 0.99%   |
| Samsung M2070 Series                  | 49       | 0.97%   |
| QinHeng CH340S                        | 49       | 0.97%   |
| HP LaserJet P1102                     | 48       | 0.95%   |
| HP DeskJet 2130 series                | 48       | 0.95%   |
| Seiko Epson Printer                   | 47       | 0.93%   |
| Samsung SCX-3400 Series               | 45       | 0.89%   |
| HP LaserJet P1005                     | 44       | 0.87%   |
| Canon LBP2900                         | 43       | 0.85%   |
| Canon PIXMA MG2500 Series             | 41       | 0.81%   |
| HP ENVY 4520 series                   | 40       | 0.79%   |
| Brother HL-2030 Laser Printer         | 37       | 0.73%   |
| HP LaserJet 1010                      | 35       | 0.69%   |
| Samsung ML-1640 Series Laser Printer  | 34       | 0.67%   |
| HP DeskJet 3630 series                | 33       | 0.65%   |
| HP Deskjet 2050 J510                  | 32       | 0.63%   |
| Canon PIXMA MX920 Series              | 32       | 0.63%   |
| Samsung SCX-3200 Series               | 28       | 0.55%   |
| Samsung ML-216x Series Laser Printer  | 28       | 0.55%   |
| Canon MF4410                          | 28       | 0.55%   |
| Canon iP7200 series                   | 28       | 0.55%   |
| Seiko Epson USB2.0 Printer (Hi-speed) | 26       | 0.51%   |
| HP Deskjet 2540 series                | 26       | 0.51%   |
| Canon LiDE 300                        | 26       | 0.51%   |
| Brother HL-2130 series                | 26       | 0.51%   |
| HP LaserJet 1200                      | 25       | 0.49%   |
| HP Deskjet 1050 J410                  | 25       | 0.49%   |
| Brother HL-1110 series                | 25       | 0.49%   |
| HP LaserJet Professional P 1102w      | 24       | 0.48%   |
| HP DeskJet 2700 series                | 24       | 0.48%   |
| HP LaserJet Professional P1102w       | 23       | 0.46%   |
| HP ENVY 5000 series                   | 23       | 0.46%   |
| Canon PIXMA MG3600 Series             | 23       | 0.46%   |
| Canon MF3010                          | 23       | 0.46%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Canon                       | 604      | 51.54%  |
| Seiko Epson                 | 251      | 21.42%  |
| Hewlett-Packard             | 164      | 13.99%  |
| Mustek Systems              | 68       | 5.8%    |
| Ultima Electronics          | 23       | 1.96%   |
| Acer Peripherals (now BenQ) | 21       | 1.79%   |
| AGFA-Gevaert NV             | 15       | 1.28%   |
| KYE Systems (Mouse Systems) | 7        | 0.6%    |
| Plustek                     | 4        | 0.34%   |
| Fujitsu                     | 3        | 0.26%   |
| UMAX                        | 2        | 0.17%   |
| Microtek International      | 2        | 0.17%   |
| Avision                     | 2        | 0.17%   |
| Visioneer                   | 1        | 0.09%   |
| Syscan                      | 1        | 0.09%   |
| Salix Technology            | 1        | 0.09%   |
| Nikon                       | 1        | 0.09%   |
| Minolta                     | 1        | 0.09%   |
| Canon Electronics           | 1        | 0.09%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 110                                                               | 88       | 7.49%   |
| Canon CanoScan LiDE 210                                                               | 74       | 6.3%    |
| Canon CanoScan LIDE 25                                                                | 73       | 6.21%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 62       | 5.28%   |
| Canon CanoScan LiDE 220                                                               | 51       | 4.34%   |
| Canon CanoScan LiDE 120                                                               | 47       | 4%      |
| Canon CanoScan LiDE 100                                                               | 36       | 3.06%   |
| HP ScanJet 2400c                                                                      | 31       | 2.64%   |
| Canon CanoScan N1240U/LiDE 30                                                         | 31       | 2.64%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 23       | 1.96%   |
| Canon CanoScan LiDE 60                                                                | 22       | 1.87%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 21       | 1.79%   |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 21       | 1.79%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]                                           | 20       | 1.7%    |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 20       | 1.7%    |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 18       | 1.53%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 18       | 1.53%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 17       | 1.45%   |
| Canon CanoScan LiDE 200                                                               | 17       | 1.45%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 14       | 1.19%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 13       | 1.11%   |
| Seiko Epson GT-7400U [Perfection 1270]                                                | 11       | 0.94%   |
| Canon CanoScan LiDE 90                                                                | 11       | 0.94%   |
| Mustek Systems SNAPSCAN e22                                                           | 10       | 0.85%   |
| Mustek Systems ScanExpress 1200 UB                                                    | 10       | 0.85%   |
| Canon CanoScan LiDE 700F                                                              | 10       | 0.85%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                         | 9        | 0.77%   |
| HP ScanJet 3800c                                                                      | 9        | 0.77%   |
| Canon CanoScan N650U/N656U                                                            | 9        | 0.77%   |
| Canon CanoScan 9000F Mark II                                                          | 9        | 0.77%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo]                               | 8        | 0.68%   |
| HP ScanJet 3970c                                                                      | 8        | 0.68%   |
| Seiko Epson Scanner                                                                   | 7        | 0.6%    |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                                           | 7        | 0.6%    |
| Seiko Epson GT-F700 [Perfection V350]                                                 | 7        | 0.6%    |
| Seiko Epson GT-F670 [Perfection V200 Photo]                                           | 7        | 0.6%    |
| Mustek Systems BearPaw 2400 CU Plus                                                   | 7        | 0.6%    |
| HP PSC 1200                                                                           | 7        | 0.6%    |
| Canon CanoScan 4400F                                                                  | 7        | 0.6%    |
| Seiko Epson Perfection 660                                                            | 6        | 0.51%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 5555     | 37.46%  |
| Microdia                      | 1219     | 8.22%   |
| Microsoft                     | 951      | 6.41%   |
| Z-Star Microelectronics       | 890      | 6%      |
| Samsung Electronics           | 496      | 3.34%   |
| Apple                         | 369      | 2.49%   |
| Sunplus Innovation Technology | 364      | 2.45%   |
| Chicony Electronics           | 345      | 2.33%   |
| KYE Systems (Mouse Systems)   | 305      | 2.06%   |
| Generalplus Technology        | 297      | 2%      |
| Realtek Semiconductor         | 279      | 1.88%   |
| Cubeternet                    | 255      | 1.72%   |
| Creative Technology           | 247      | 1.67%   |
| GEMBIRD                       | 238      | 1.6%    |
| Aveo Technology               | 205      | 1.38%   |
| ARC International             | 177      | 1.19%   |
| Arkmicro Technologies         | 174      | 1.17%   |
| Pixart Imaging                | 144      | 0.97%   |
| MacroSilicon                  | 122      | 0.82%   |
| Jieli Technology              | 120      | 0.81%   |
| Alcor Micro                   | 116      | 0.78%   |
| Hewlett-Packard               | 105      | 0.71%   |
| Razer USA                     | 81       | 0.55%   |
| Trust                         | 79       | 0.53%   |
| Huawei Technologies           | 78       | 0.53%   |
| Genesys Logic                 | 71       | 0.48%   |
| LG Electronics                | 69       | 0.47%   |
| webcam                        | 67       | 0.45%   |
| IMC Networks                  | 60       | 0.4%    |
| Guillemot                     | 59       | 0.4%    |
| AVerMedia Technologies        | 58       | 0.39%   |
| Valve Software                | 49       | 0.33%   |
| Philips (or NXP)              | 49       | 0.33%   |
| Sunplus IT                    | 48       | 0.32%   |
| Sonix Technology              | 48       | 0.32%   |
| A4Tech                        | 41       | 0.28%   |
| Lenovo                        | 36       | 0.24%   |
| Unknown                       | 34       | 0.23%   |
| WaveRider Communications      | 33       | 0.22%   |
| Silicon Motion                | 32       | 0.22%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 1396     | 9.36%   |
| Logitech HD Pro Webcam C920                       | 878      | 5.89%   |
| Samsung Galaxy series, misc. (MTP mode)           | 486      | 3.26%   |
| Z-Star Venus USB2.0 Camera                        | 390      | 2.61%   |
| Microsoft LifeCam HD-3000                         | 351      | 2.35%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                   | 323      | 2.17%   |
| Logitech Webcam C310                              | 316      | 2.12%   |
| Microdia Camera                                   | 310      | 2.08%   |
| Logitech HD Webcam C525                           | 306      | 2.05%   |
| Logitech C922 Pro Stream Webcam                   | 273      | 1.83%   |
| Logitech Webcam C170                              | 271      | 1.82%   |
| Microdia Webcam Vitade AF                         | 257      | 1.72%   |
| Logitech HD Webcam C615                           | 218      | 1.46%   |
| Generalplus GENERAL WEBCAM                        | 199      | 1.33%   |
| Z-Star A4 TECH USB2.0 PC Camera J                 | 186      | 1.25%   |
| ARC International Camera                          | 173      | 1.16%   |
| Z-Star A4 TECH USB2.0 PC Camera E                 | 168      | 1.13%   |
| Arkmicro USB2.0 PC CAMERA                         | 149      | 1%      |
| Microdia Sonix USB 2.0 Camera                     | 147      | 0.99%   |
| Logitech BRIO Ultra HD Webcam                     | 143      | 0.96%   |
| Logitech Webcam C210                              | 131      | 0.88%   |
| Microdia USB 2.0 Camera                           | 126      | 0.84%   |
| Microdia CameraA                                  | 126      | 0.84%   |
| GEMBIRD USB2.0 PC CAMERA                          | 125      | 0.84%   |
| Logitech HD Webcam C910                           | 123      | 0.82%   |
| Microsoft LifeCam Cinema                          | 120      | 0.8%    |
| Jieli USB PHY 2.0                                 | 120      | 0.8%    |
| Logitech Webcam C930e                             | 116      | 0.78%   |
| Logitech QuickCam Pro 9000                        | 112      | 0.75%   |
| Realtek FULL HD 1080P Webcam                      | 110      | 0.74%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro              | 108      | 0.72%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 107      | 0.72%   |
| Cubeternet GL-UPC822 UVC WebCam                   | 102      | 0.68%   |
| Logitech HD Webcam C510                           | 101      | 0.68%   |
| Logitech Webcam Pro 9000                          | 100      | 0.67%   |
| MacroSilicon usb video                            | 97       | 0.65%   |
| Generalplus 808 Camera #9 (web-cam mode)          | 95       | 0.64%   |
| Microdia Integrated Camera                        | 92       | 0.62%   |
| Logitech Webcam C110                              | 84       | 0.56%   |
| Aveo USB2.0 Camera                                | 84       | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Elan Microelectronics      | 36       | 24.32%  |
| LighTuning Technology      | 16       | 10.81%  |
| AuthenTec                  | 16       | 10.81%  |
| Synaptics                  | 15       | 10.14%  |
| STMicroelectronics         | 13       | 8.78%   |
| DigitalPersona             | 13       | 8.78%   |
| Shenzhen Goodix Technology | 10       | 6.76%   |
| Microsoft                  | 10       | 6.76%   |
| Upek                       | 6        | 4.05%   |
| Dell                       | 5        | 3.38%   |
| Validity Sensors           | 4        | 2.7%    |
| Futronic Technology        | 2        | 1.35%   |
| Suprema                    | 1        | 0.68%   |
| Focal-systems.Corp         | 1        | 0.68%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Elan fingerprint sensor [FeinTech FPS00200]                 | 36       | 24.32%  |
| Synaptics  WBDI Fingerprint Reader - USB 052                | 15       | 10.14%  |
| STMicroelectronics Fingerprint Reader                       | 13       | 8.78%   |
| DigitalPersona Fingerprint Reader                           | 12       | 8.11%   |
| Microsoft Fingerprint Reader                                | 10       | 6.76%   |
| LighTuning Fingerprint Sensor                               | 10       | 6.76%   |
| Shenzhen Goodix  Fingerprint Device                         | 9        | 6.08%   |
| AuthenTec AES1600                                           | 6        | 4.05%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor      | 5        | 3.38%   |
| Dell MS819 Wired Mouse With Fingerprint Reader              | 5        | 3.38%   |
| AuthenTec Fingerprint Sensor                                | 5        | 3.38%   |
| LighTuning ES603 Swipe Fingerprint Sensor                   | 4        | 2.7%    |
| AuthenTec AES2550 Fingerprint Sensor                        | 3        | 2.03%   |
| Validity Sensors VFS 5011 fingerprint sensor                | 2        | 1.35%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor | 2        | 1.35%   |
| LighTuning EgisTec Touch Fingerprint Sensor                 | 2        | 1.35%   |
| Futronic FS81 Fingerprint Scanner Module                    | 2        | 1.35%   |
| AuthenTec AES2501 Fingerprint Sensor                        | 2        | 1.35%   |
| Upek TCS1C EIM/STM32 Fingerprint sensor                     | 1        | 0.68%   |
| Suprema SUP-SFR400(A) BioMini Fingerprint Reader            | 1        | 0.68%   |
| Shenzhen Goodix Fingerprint Reader                          | 1        | 0.68%   |
| Focal-systems.Corp FT9201Fingerprint.                       | 1        | 0.68%   |
| DigitalPersona Fingerprint Scanner, U.are.U 2000            | 1        | 0.68%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                                  | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Alcor Micro                             | 87       | 15.05%  |
| Advanced Card Systems                   | 61       | 10.55%  |
| SCM Microsystems                        | 59       | 10.21%  |
| Gemalto (was Gemplus)                   | 54       | 9.34%   |
| OmniKey                                 | 45       | 7.79%   |
| Realtek Semiconductor                   | 38       | 6.57%   |
| Reiner SCT Kartensysteme                | 25       | 4.33%   |
| Aladdin Knowledge Systems               | 24       | 4.15%   |
| Yubico.com                              | 18       | 3.11%   |
| Chicony Electronics                     | 18       | 3.11%   |
| VASCO Data Security International       | 17       | 2.94%   |
| Clay Logic                              | 16       | 2.77%   |
| Aktiv                                   | 16       | 2.77%   |
| Cherry                                  | 14       | 2.42%   |
| BIT4ID                                  | 14       | 2.42%   |
| Hewlett-Packard                         | 11       | 1.9%    |
| Fujitsu Siemens Computers               | 11       | 1.9%    |
| Aladdin R.D.                            | 8        | 1.38%   |
| Athena Smartcard Solutions              | 7        | 1.21%   |
| Giesecke & Devrient                     | 5        | 0.87%   |
| Castles Technology                      | 4        | 0.69%   |
| Lenovo                                  | 3        | 0.52%   |
| Kobil Systems                           | 3        | 0.52%   |
| Watchdata                               | 2        | 0.35%   |
| In Focus Systems                        | 2        | 0.35%   |
| Feitian Technologies                    | 2        | 0.35%   |
| C3PO                                    | 2        | 0.35%   |
| Avtor                                   | 2        | 0.35%   |
| ST-Ericsson                             | 1        | 0.17%   |
| Purism, SPC                             | 1        | 0.17%   |
| Precise Biometrics                      | 1        | 0.17%   |
| Microchip Technology                    | 1        | 0.17%   |
| Mako Technologies                       | 1        | 0.17%   |
| Jing-Mold Enterprise                    | 1        | 0.17%   |
| HID Global                              | 1        | 0.17%   |
| Future Technology Devices International | 1        | 0.17%   |
| BLUTRONICS                              | 1        | 0.17%   |
| BIFIT                                   | 1        | 0.17%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                        | 55       | 9.48%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                          | 48       | 8.28%   |
| Realtek Semiconductor Smart Card Reader Interface                          | 38       | 6.55%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                     | 35       | 6.03%   |
| Advanced Card Systems ACR38 SmartCard Reader                               | 34       | 5.86%   |
| Alcor Micro Watchdata W 1981                                               | 32       | 5.52%   |
| Aladdin Knowledge Systems Token JC                                         | 24       | 4.14%   |
| OmniKey CardMan 3021 / 3121                                                | 20       | 3.45%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                       | 18       | 3.1%    |
| OmniKey CardMan 1021                                                       | 15       | 2.59%   |
| Aktiv Rutoken lite                                                         | 15       | 2.59%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 13       | 2.24%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                            | 12       | 2.07%   |
| VASCO Data Security International Digipass 905 SmartCard Reader            | 12       | 2.07%   |
| Clay Logic Nitrokey Pro                                                    | 12       | 2.07%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                              | 11       | 1.9%    |
| BIT4ID miniLector EVO                                                      | 11       | 1.9%    |
| Advanced Card Systems ACR122U                                              | 11       | 1.9%    |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                | 9        | 1.55%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                              | 8        | 1.38%   |
| SCM Microsystems SCR331 SmartCard Reader                                   | 7        | 1.21%   |
| Reiner SCT Kartensysteme cyberJack one                                     | 7        | 1.21%   |
| Athena Smartcard Solutions ASEDrive CCID                                   | 7        | 1.21%   |
| Aladdin R.D. JaCarta                                                       | 7        | 1.21%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                           | 6        | 1.03%   |
| Advanced Card Systems ACR39U                                               | 6        | 1.03%   |
| SCM Microsystems SCR335 SmartCard Reader                                   | 5        | 0.86%   |
| Advanced Card Systems ACR1281 1S Dual Reader                               | 5        | 0.86%   |
| Yubico.com Yubikey 4/5 CCID                                                | 4        | 0.69%   |
| VASCO Data Security International DIGIPASS 870                             | 4        | 0.69%   |
| OmniKey 3x21 Smart Card Reader                                             | 4        | 0.69%   |
| Giesecke & Devrient StarSign CUT S                                         | 4        | 0.69%   |
| Castles Technology EZCCID Smart Card Reader                                | 4        | 0.69%   |
| Reiner SCT Kartensysteme tanJack USB                                       | 3        | 0.52%   |
| OmniKey CardMan 3121 (HID Technologies)                                    | 3        | 0.52%   |
| Lenovo Smartcard Keyboard                                                  | 3        | 0.52%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                        | 2        | 0.34%   |
| Watchdata USB Key                                                          | 2        | 0.34%   |
| SCM Microsystems SCR35xx Smart Card Reader                                 | 2        | 0.34%   |
| SCM Microsystems SCR3500 A Contact Reader                                  | 2        | 0.34%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 66249    | 82.83%  |
| 1     | 11706    | 14.64%  |
| 2     | 1502     | 1.88%   |
| 3     | 293      | 0.37%   |
| 4     | 116      | 0.15%   |
| 5     | 61       | 0.08%   |
| 6     | 27       | 0.03%   |
| 7     | 15       | 0.02%   |
| 8     | 7        | 0.01%   |
| 9     | 3        | 0.004%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 6214     | 39.91%  |
| Net/wireless             | 3533     | 22.69%  |
| Communication controller | 1342     | 8.62%   |
| Unassigned class         | 996      | 6.4%    |
| Multimedia controller    | 565      | 3.63%   |
| Sound                    | 564      | 3.62%   |
| Camera                   | 368      | 2.36%   |
| Chipcard                 | 363      | 2.33%   |
| Bluetooth                | 307      | 1.97%   |
| Net/ethernet             | 262      | 1.68%   |
| Network                  | 198      | 1.27%   |
| Storage/raid             | 152      | 0.98%   |
| Fingerprint reader       | 129      | 0.83%   |
| Modem                    | 124      | 0.8%    |
| Card reader              | 122      | 0.78%   |
| Storage/ide              | 83       | 0.53%   |
| Dvb card                 | 78       | 0.5%    |
| Firewire controller      | 54       | 0.35%   |
| Tv card                  | 28       | 0.18%   |
| Storage/ata              | 27       | 0.17%   |
| Storage                  | 23       | 0.15%   |
| Storage/nvme             | 17       | 0.11%   |
| Video                    | 9        | 0.06%   |
| Wireless                 | 6        | 0.04%   |
| Unclassified device      | 5        | 0.03%   |

