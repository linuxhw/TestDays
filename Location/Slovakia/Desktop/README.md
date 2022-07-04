Linux in Slovakia - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Slovakia.

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

Total: 346

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Shuttle       | FH61V                       | [465dc41fdb](https://linux-hardware.org/?probe=465dc41fdb) | Jun 08, 2022 |
| MSI           | Z390-A PRO                  | [8baf319c52](https://linux-hardware.org/?probe=8baf319c52) | May 21, 2022 |
| Intel         | DG41KR AAE62839-304         | [d6fa39e82f](https://linux-hardware.org/?probe=d6fa39e82f) | May 16, 2022 |
| Foxconn       | 2ADA                        | [215ded6566](https://linux-hardware.org/?probe=215ded6566) | May 16, 2022 |
| Acer          | H57M01                      | [9116ecebcb](https://linux-hardware.org/?probe=9116ecebcb) | May 15, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [52c0b4a6e0](https://linux-hardware.org/?probe=52c0b4a6e0) | May 14, 2022 |
| Acer          | H57M01                      | [42100344af](https://linux-hardware.org/?probe=42100344af) | May 14, 2022 |
| Gigabyte      | H55M-S2H                    | [0b3c6ab0f7](https://linux-hardware.org/?probe=0b3c6ab0f7) | May 14, 2022 |
| ASRock        | H61M-VG4                    | [92f92ef4ee](https://linux-hardware.org/?probe=92f92ef4ee) | Apr 28, 2022 |
| ASRock        | H61M-VG4                    | [fff58f97e8](https://linux-hardware.org/?probe=fff58f97e8) | Apr 27, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [4b9faf4848](https://linux-hardware.org/?probe=4b9faf4848) | Apr 26, 2022 |
| Unknown       | RS780-SB700                 | [eb3aa5fa60](https://linux-hardware.org/?probe=eb3aa5fa60) | Apr 20, 2022 |
| Gigabyte      | Z490M                       | [2138ce9310](https://linux-hardware.org/?probe=2138ce9310) | Apr 18, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [e6aa0c6166](https://linux-hardware.org/?probe=e6aa0c6166) | Apr 09, 2022 |
| Acer          | Revo RL80                   | [414f1870b3](https://linux-hardware.org/?probe=414f1870b3) | Apr 04, 2022 |
| Gigabyte      | H61M-S1                     | [a10a00d2f1](https://linux-hardware.org/?probe=a10a00d2f1) | Apr 03, 2022 |
| Lenovo        | MAHOBAY NOK                 | [ba7b7abd34](https://linux-hardware.org/?probe=ba7b7abd34) | Apr 02, 2022 |
| HP            | 18E5                        | [39cb47db55](https://linux-hardware.org/?probe=39cb47db55) | Mar 28, 2022 |
| HP            | 18E5                        | [061d716ce1](https://linux-hardware.org/?probe=061d716ce1) | Mar 27, 2022 |
| Shuttle       | FH61V                       | [9b18d7b2ed](https://linux-hardware.org/?probe=9b18d7b2ed) | Mar 23, 2022 |
| VIA Techno... | KM266-8235                  | [ad3f9e9e12](https://linux-hardware.org/?probe=ad3f9e9e12) | Mar 20, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [e508dbbb0f](https://linux-hardware.org/?probe=e508dbbb0f) | Mar 05, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [455f94f1d3](https://linux-hardware.org/?probe=455f94f1d3) | Mar 04, 2022 |
| HP            | 339A                        | [820ebf5859](https://linux-hardware.org/?probe=820ebf5859) | Feb 26, 2022 |
| HP            | 339A                        | [118fee2993](https://linux-hardware.org/?probe=118fee2993) | Feb 26, 2022 |
| Dell          | 0773VG A00                  | [d24a3aebe9](https://linux-hardware.org/?probe=d24a3aebe9) | Feb 23, 2022 |
| Gigabyte      | H61M-S1                     | [e667cfc4cf](https://linux-hardware.org/?probe=e667cfc4cf) | Feb 20, 2022 |
| Gigabyte      | H55M-S2H                    | [3031d8a880](https://linux-hardware.org/?probe=3031d8a880) | Feb 20, 2022 |
| Fujitsu Si... | D1784 S26361-D1784          | [2734c5a939](https://linux-hardware.org/?probe=2734c5a939) | Feb 19, 2022 |
| Fujitsu Si... | D1784 S26361-D1784          | [7baecb9fce](https://linux-hardware.org/?probe=7baecb9fce) | Feb 19, 2022 |
| HP            | 339A                        | [d35aeac271](https://linux-hardware.org/?probe=d35aeac271) | Feb 16, 2022 |
| HP            | 339A                        | [aac8acdafe](https://linux-hardware.org/?probe=aac8acdafe) | Feb 16, 2022 |
| Gigabyte      | Z77-HD3                     | [c72849033f](https://linux-hardware.org/?probe=c72849033f) | Feb 15, 2022 |
| Dell          | 02YYK5 A01                  | [bfeed2f132](https://linux-hardware.org/?probe=bfeed2f132) | Feb 14, 2022 |
| ASUSTek       | P8H77-M                     | [b6851e2e2d](https://linux-hardware.org/?probe=b6851e2e2d) | Feb 13, 2022 |
| ASUSTek       | P6T                         | [5084dfc411](https://linux-hardware.org/?probe=5084dfc411) | Feb 12, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [4a136af33b](https://linux-hardware.org/?probe=4a136af33b) | Feb 12, 2022 |
| ASUSTek       | P6T                         | [10a6e04458](https://linux-hardware.org/?probe=10a6e04458) | Feb 10, 2022 |
| Fujitsu Si... | D1784 S26361-D1784          | [843210cfb0](https://linux-hardware.org/?probe=843210cfb0) | Feb 06, 2022 |
| Dell          | 0WR7PY A02                  | [2b3c148135](https://linux-hardware.org/?probe=2b3c148135) | Feb 06, 2022 |
| Gigabyte      | 970A-DS3P                   | [ed2a250420](https://linux-hardware.org/?probe=ed2a250420) | Feb 04, 2022 |
| Gigabyte      | 970A-DS3P                   | [d598fc04e1](https://linux-hardware.org/?probe=d598fc04e1) | Feb 04, 2022 |
| Lenovo        | 3176 NOK                    | [d3a3d5276b](https://linux-hardware.org/?probe=d3a3d5276b) | Feb 02, 2022 |
| Gigabyte      | B250M-D3H-CF                | [5b4a8e5bc4](https://linux-hardware.org/?probe=5b4a8e5bc4) | Jan 29, 2022 |
| Shuttle       | FH61V                       | [6d6980d0bb](https://linux-hardware.org/?probe=6d6980d0bb) | Jan 18, 2022 |
| ASUSTek       | H81M-K                      | [637ad5d9e4](https://linux-hardware.org/?probe=637ad5d9e4) | Jan 18, 2022 |
| ASRock        | AM1H-ITX                    | [0a01195a57](https://linux-hardware.org/?probe=0a01195a57) | Jan 16, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [9fab263b02](https://linux-hardware.org/?probe=9fab263b02) | Jan 11, 2022 |
| ASUSTek       | P5GC-MX                     | [2126180fa9](https://linux-hardware.org/?probe=2126180fa9) | Jan 06, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [3867022c38](https://linux-hardware.org/?probe=3867022c38) | Dec 25, 2021 |
| Gigabyte      | Z77-HD3                     | [a9eceeac28](https://linux-hardware.org/?probe=a9eceeac28) | Dec 14, 2021 |
| Shuttle       | FH61V                       | [b4c8a91d0f](https://linux-hardware.org/?probe=b4c8a91d0f) | Dec 13, 2021 |
| Dell          | 0HN7XN A01                  | [f17f39439e](https://linux-hardware.org/?probe=f17f39439e) | Dec 13, 2021 |
| Gigabyte      | Z77-HD3                     | [75755e4033](https://linux-hardware.org/?probe=75755e4033) | Dec 12, 2021 |
| Gigabyte      | Z77-HD3                     | [7d3626d44d](https://linux-hardware.org/?probe=7d3626d44d) | Dec 12, 2021 |
| ASUSTek       | Z170-K                      | [eb723f5cb0](https://linux-hardware.org/?probe=eb723f5cb0) | Dec 09, 2021 |
| Gigabyte      | H410M S2H                   | [8b917483ef](https://linux-hardware.org/?probe=8b917483ef) | Nov 30, 2021 |
| ASUSTek       | P5QL PRO                    | [ad0c0d07cf](https://linux-hardware.org/?probe=ad0c0d07cf) | Nov 28, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [77a39f82ff](https://linux-hardware.org/?probe=77a39f82ff) | Nov 28, 2021 |
| ASUSTek       | M4A77T/USB3                 | [e23dea02cf](https://linux-hardware.org/?probe=e23dea02cf) | Nov 26, 2021 |
| Gigabyte      | 970A-DS3P                   | [b718c829fa](https://linux-hardware.org/?probe=b718c829fa) | Nov 24, 2021 |
| Intel         | DH77EB AAG39073-304         | [bf7d34f5c1](https://linux-hardware.org/?probe=bf7d34f5c1) | Nov 15, 2021 |
| Intel         | DH77EB AAG39073-304         | [d1e04ead11](https://linux-hardware.org/?probe=d1e04ead11) | Nov 15, 2021 |
| Acer          | EM61SM/EM61PM               | [6a42469739](https://linux-hardware.org/?probe=6a42469739) | Nov 13, 2021 |
| ASRock        | B550M Steel Legend          | [fada2e4c02](https://linux-hardware.org/?probe=fada2e4c02) | Nov 06, 2021 |
| Gigabyte      | GA-M56S-S3                  | [d6285c81a2](https://linux-hardware.org/?probe=d6285c81a2) | Nov 05, 2021 |
| Gigabyte      | H61M-S1                     | [17d03d73f7](https://linux-hardware.org/?probe=17d03d73f7) | Oct 30, 2021 |
| ASRock        | N68C-S UCC                  | [c74421666a](https://linux-hardware.org/?probe=c74421666a) | Oct 20, 2021 |
| Lenovo        | SHARKBAY 31900058 STD       | [cdc6d847a7](https://linux-hardware.org/?probe=cdc6d847a7) | Oct 18, 2021 |
| Gigabyte      | H310M S2H x.x               | [d0b704d0ff](https://linux-hardware.org/?probe=d0b704d0ff) | Oct 06, 2021 |
| Gigabyte      | H81M-S2V                    | [ef8dfe0673](https://linux-hardware.org/?probe=ef8dfe0673) | Oct 02, 2021 |
| ASUSTek       | Maximus VIII HERO           | [1fce457ac6](https://linux-hardware.org/?probe=1fce457ac6) | Oct 01, 2021 |
| MSI           | E3M WORKSTATION V5          | [6924705831](https://linux-hardware.org/?probe=6924705831) | Sep 20, 2021 |
| Gigabyte      | H61M-S1                     | [6207dd28b2](https://linux-hardware.org/?probe=6207dd28b2) | Sep 09, 2021 |
| MSI           | E3M WORKSTATION V5          | [fa6adf65a6](https://linux-hardware.org/?probe=fa6adf65a6) | Aug 23, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [9bf7d4afd7](https://linux-hardware.org/?probe=9bf7d4afd7) | Aug 14, 2021 |
| Dell          | 08HPGT A01                  | [d827460e02](https://linux-hardware.org/?probe=d827460e02) | Aug 04, 2021 |
| ASUSTek       | PRIME B450M-A               | [dc8f396ad8](https://linux-hardware.org/?probe=dc8f396ad8) | Aug 02, 2021 |
| ASUSTek       | M4A88T-V EVO/USB3           | [30b94a4a43](https://linux-hardware.org/?probe=30b94a4a43) | Jul 27, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [925ddff018](https://linux-hardware.org/?probe=925ddff018) | Jul 25, 2021 |
| HP            | ProLiant MicroServer Gen... | [756bb76029](https://linux-hardware.org/?probe=756bb76029) | Jul 25, 2021 |
| ASUSTek       | Z87-K                       | [f548a06642](https://linux-hardware.org/?probe=f548a06642) | Jul 23, 2021 |
| MSI           | B450I GAMING PLUS AC        | [04bf0287f0](https://linux-hardware.org/?probe=04bf0287f0) | Jul 21, 2021 |
| ASUSTek       | PRIME A320M-K 2021-06-11    | [39037104b7](https://linux-hardware.org/?probe=39037104b7) | Jul 17, 2021 |
| ASUSTek       | PRIME A320M-K 2021-06-11    | [a82245240b](https://linux-hardware.org/?probe=a82245240b) | Jul 15, 2021 |
| Intel         | S3000AHLX D40858-208        | [2acfd9617b](https://linux-hardware.org/?probe=2acfd9617b) | Jul 10, 2021 |
| HP            | 843C                        | [01dc34eeb4](https://linux-hardware.org/?probe=01dc34eeb4) | Jul 07, 2021 |
| HP            | 0A54h                       | [10aa52cef5](https://linux-hardware.org/?probe=10aa52cef5) | Jul 06, 2021 |
| ASUSTek       | H81M-K                      | [9d12a5bba7](https://linux-hardware.org/?probe=9d12a5bba7) | Jul 05, 2021 |
| ASRock        | X570M Pro4                  | [a00aea4331](https://linux-hardware.org/?probe=a00aea4331) | Jul 03, 2021 |
| ASUSTek       | PRIME X470-PRO              | [e649a4f85c](https://linux-hardware.org/?probe=e649a4f85c) | Jun 30, 2021 |
| MSI           | H110M PRO-VD                | [83b2318c6a](https://linux-hardware.org/?probe=83b2318c6a) | Jun 26, 2021 |
| Foxconn       | 945 7AD Series              | [9a763d1e1e](https://linux-hardware.org/?probe=9a763d1e1e) | Jun 25, 2021 |
| MSI           | H110M PRO-VD                | [856b9bc825](https://linux-hardware.org/?probe=856b9bc825) | Jun 24, 2021 |
| Intel         | X99                         | [436dda258b](https://linux-hardware.org/?probe=436dda258b) | Jun 21, 2021 |
| Gigabyte      | GA-K8NF-9-RH                | [0cfd20f720](https://linux-hardware.org/?probe=0cfd20f720) | Jun 16, 2021 |
| Gigabyte      | GA-K8NF-9-RH                | [e33a8c0c69](https://linux-hardware.org/?probe=e33a8c0c69) | Jun 16, 2021 |
| ASUSTek       | B85M-G                      | [a390d934b1](https://linux-hardware.org/?probe=a390d934b1) | Jun 13, 2021 |
| Intel         | S3000AHLX D40858-208        | [ab61e363eb](https://linux-hardware.org/?probe=ab61e363eb) | Jun 12, 2021 |
| HP            | 3397                        | [e171bcda3f](https://linux-hardware.org/?probe=e171bcda3f) | Jun 11, 2021 |
| MSI           | B450I GAMING PLUS AC        | [74201da57b](https://linux-hardware.org/?probe=74201da57b) | Jun 11, 2021 |
| HP            | ProLiant ML350 G5           | [297ef6b999](https://linux-hardware.org/?probe=297ef6b999) | Jun 06, 2021 |
| ASRock        | B550 Phantom Gaming-ITX/... | [7c519c91ca](https://linux-hardware.org/?probe=7c519c91ca) | Jun 02, 2021 |
| ASUSTek       | F2A85-V PRO                 | [7950140465](https://linux-hardware.org/?probe=7950140465) | Jun 02, 2021 |
| ASUSTek       | PRIME A320M-K 2020-03-20    | [500976e7d1](https://linux-hardware.org/?probe=500976e7d1) | May 30, 2021 |
| Lenovo        | 0.1                         | [77d8358e26](https://linux-hardware.org/?probe=77d8358e26) | May 28, 2021 |
| Lenovo        | 0.1                         | [d0fbef90ca](https://linux-hardware.org/?probe=d0fbef90ca) | May 27, 2021 |
| Gigabyte      | X58A-UD3R                   | [0b27475327](https://linux-hardware.org/?probe=0b27475327) | May 26, 2021 |
| Pegatron      | 2AD5                        | [794531a511](https://linux-hardware.org/?probe=794531a511) | May 25, 2021 |
| Lenovo        | Tiger Hill                  | [3f61f1be35](https://linux-hardware.org/?probe=3f61f1be35) | May 25, 2021 |
| HP            | 3047h                       | [4fce80ed03](https://linux-hardware.org/?probe=4fce80ed03) | May 20, 2021 |
| MSI           | A75A-G55                    | [f9773bff22](https://linux-hardware.org/?probe=f9773bff22) | May 17, 2021 |
| Intel         | DH87RL AAG74240-402         | [cdb24d5d69](https://linux-hardware.org/?probe=cdb24d5d69) | May 16, 2021 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [e311ba55e3](https://linux-hardware.org/?probe=e311ba55e3) | May 13, 2021 |
| HP            | 843C                        | [e69ec57276](https://linux-hardware.org/?probe=e69ec57276) | May 10, 2021 |
| HP            | 3048h                       | [74f738bae1](https://linux-hardware.org/?probe=74f738bae1) | May 01, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | [b4ef2db7c1](https://linux-hardware.org/?probe=b4ef2db7c1) | May 01, 2021 |
| MSI           | E3M WORKSTATION V5          | [995ec93eb1](https://linux-hardware.org/?probe=995ec93eb1) | Apr 27, 2021 |
| MSI           | E3M WORKSTATION V5          | [228ac8147b](https://linux-hardware.org/?probe=228ac8147b) | Apr 24, 2021 |
| ASUSTek       | PRIME Z370-A                | [19b23587fa](https://linux-hardware.org/?probe=19b23587fa) | Apr 20, 2021 |
| ASUSTek       | PRIME Z370-A                | [80fac11897](https://linux-hardware.org/?probe=80fac11897) | Apr 20, 2021 |
| Foxconn       | G41MX/G41MX-K 2.0 1.0       | [c6ed3bc2f4](https://linux-hardware.org/?probe=c6ed3bc2f4) | Apr 18, 2021 |
| ASRock        | N68C-S UCC                  | [79c0025946](https://linux-hardware.org/?probe=79c0025946) | Apr 04, 2021 |
| MSI           | 760GM-P23                   | [aef62f4f18](https://linux-hardware.org/?probe=aef62f4f18) | Apr 02, 2021 |
| ASUSTek       | PRIME A320M-K 2020-03-20    | [19aaa9b56e](https://linux-hardware.org/?probe=19aaa9b56e) | Mar 30, 2021 |
| Foxconn       | G41MX/G41MX-K 2.0 1.0       | [b72dc7a1c6](https://linux-hardware.org/?probe=b72dc7a1c6) | Mar 29, 2021 |
| ASUSTek       | A8R-MVP                     | [43a7b44e3f](https://linux-hardware.org/?probe=43a7b44e3f) | Mar 27, 2021 |
| ASUSTek       | A8R-MVP                     | [6daa2a372c](https://linux-hardware.org/?probe=6daa2a372c) | Mar 27, 2021 |
| MSI           | E3M WORKSTATION V5          | [0ee0070622](https://linux-hardware.org/?probe=0ee0070622) | Mar 27, 2021 |
| ASUSTek       | P5Q SE2                     | [bcc4de28fb](https://linux-hardware.org/?probe=bcc4de28fb) | Mar 26, 2021 |
| ASRock        | K8A780LM                    | [b8f4c7c2cb](https://linux-hardware.org/?probe=b8f4c7c2cb) | Mar 22, 2021 |
| ASUSTek       | AM1M-A                      | [c3909a14fe](https://linux-hardware.org/?probe=c3909a14fe) | Mar 22, 2021 |
| Gigabyte      | B450M S2H                   | [285b5b2d08](https://linux-hardware.org/?probe=285b5b2d08) | Mar 17, 2021 |
| ASRock        | K8A780LM                    | [d95a56d80f](https://linux-hardware.org/?probe=d95a56d80f) | Mar 15, 2021 |
| Shuttle       | FH61V                       | [3e811ec55d](https://linux-hardware.org/?probe=3e811ec55d) | Mar 13, 2021 |
| ASRock        | H81M-ITX                    | [0f5f41e1ca](https://linux-hardware.org/?probe=0f5f41e1ca) | Mar 08, 2021 |
| ASRock        | H81M-ITX                    | [8599b883d6](https://linux-hardware.org/?probe=8599b883d6) | Mar 08, 2021 |
| ASRock        | FM2A68M-HD+                 | [a9a3d7da6f](https://linux-hardware.org/?probe=a9a3d7da6f) | Mar 05, 2021 |
| ASRock        | B550M Steel Legend          | [4c28c6d22c](https://linux-hardware.org/?probe=4c28c6d22c) | Mar 03, 2021 |
| Shuttle       | FH61V                       | [70d3424aad](https://linux-hardware.org/?probe=70d3424aad) | Mar 02, 2021 |
| ASUSTek       | Rampage II GENE             | [02ec8d4fff](https://linux-hardware.org/?probe=02ec8d4fff) | Mar 01, 2021 |
| Gigabyte      | X58A-UD3R                   | [323b7be7ea](https://linux-hardware.org/?probe=323b7be7ea) | Feb 27, 2021 |
| ASUSTek       | P5KPL-AM SE                 | [3c402e56a5](https://linux-hardware.org/?probe=3c402e56a5) | Feb 26, 2021 |
| Dell          | 0F8096                      | [307334b9d5](https://linux-hardware.org/?probe=307334b9d5) | Feb 24, 2021 |
| Shuttle       | FH61V                       | [f4fe921fe3](https://linux-hardware.org/?probe=f4fe921fe3) | Feb 24, 2021 |
| ASRock        | H81M-ITX                    | [d58331ce9b](https://linux-hardware.org/?probe=d58331ce9b) | Feb 23, 2021 |
| ASUSTek       | M2N-MX SE Plus              | [94f0202173](https://linux-hardware.org/?probe=94f0202173) | Feb 23, 2021 |
| ASUSTek       | A8R-MVP                     | [ce881d4659](https://linux-hardware.org/?probe=ce881d4659) | Feb 23, 2021 |
| ASRock        | K8A780LM                    | [6543fc448e](https://linux-hardware.org/?probe=6543fc448e) | Feb 23, 2021 |
| ASRock        | K8A780LM                    | [ce0076fd09](https://linux-hardware.org/?probe=ce0076fd09) | Feb 23, 2021 |
| ASUSTek       | PRIME B250M-A               | [e33b6a55d2](https://linux-hardware.org/?probe=e33b6a55d2) | Feb 20, 2021 |
| Intel         | D815EEA AAA45884-401        | [248565d49c](https://linux-hardware.org/?probe=248565d49c) | Feb 20, 2021 |
| Intel         | D815EEA AAA45884-401        | [3acc2f0b1e](https://linux-hardware.org/?probe=3acc2f0b1e) | Feb 20, 2021 |
| Gigabyte      | F2A78M-HD2                  | [b8e8be8f5e](https://linux-hardware.org/?probe=b8e8be8f5e) | Feb 20, 2021 |
| ASUSTek       | M4A88T-V EVO/USB3           | [bfbf37268c](https://linux-hardware.org/?probe=bfbf37268c) | Feb 17, 2021 |
| Gigabyte      | X58A-UD3R                   | [f16fabf13a](https://linux-hardware.org/?probe=f16fabf13a) | Feb 16, 2021 |
| MSI           | Z97S SLI Krait Edition      | [9f04601c65](https://linux-hardware.org/?probe=9f04601c65) | Feb 14, 2021 |
| Gigabyte      | B450 AORUS PRO-CF           | [abdd5f9208](https://linux-hardware.org/?probe=abdd5f9208) | Feb 14, 2021 |
| Gigabyte      | G31M-S2L                    | [b664ab9762](https://linux-hardware.org/?probe=b664ab9762) | Feb 11, 2021 |
| Gigabyte      | G31M-S2L                    | [aa7f6024cf](https://linux-hardware.org/?probe=aa7f6024cf) | Feb 10, 2021 |
| ASUSTek       | PRIME X470-PRO              | [715d706afe](https://linux-hardware.org/?probe=715d706afe) | Feb 10, 2021 |
| Dell          | 0PU052                      | [8e0d1be6bf](https://linux-hardware.org/?probe=8e0d1be6bf) | Feb 09, 2021 |
| ASUSTek       | M2N-MX SE Plus              | [a8985150bd](https://linux-hardware.org/?probe=a8985150bd) | Feb 08, 2021 |
| ASUSTek       | P5KPL-SE                    | [83be789e3c](https://linux-hardware.org/?probe=83be789e3c) | Feb 07, 2021 |
| ASUSTek       | P5KPL-SE                    | [ca67f71815](https://linux-hardware.org/?probe=ca67f71815) | Feb 06, 2021 |
| ASRock        | H81M-ITX                    | [7b2d6774c8](https://linux-hardware.org/?probe=7b2d6774c8) | Feb 05, 2021 |
| Dell          | 0PU052                      | [cc4b4c54d6](https://linux-hardware.org/?probe=cc4b4c54d6) | Feb 01, 2021 |
| MSI           | MS-7388                     | [6fc9a5690d](https://linux-hardware.org/?probe=6fc9a5690d) | Feb 01, 2021 |
| Gigabyte      | B360M H 2019-01-02          | [6b2b3ee651](https://linux-hardware.org/?probe=6b2b3ee651) | Jan 28, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [845de5bee0](https://linux-hardware.org/?probe=845de5bee0) | Jan 22, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [a875950ed5](https://linux-hardware.org/?probe=a875950ed5) | Jan 22, 2021 |
| ASUSTek       | PRIME X470-PRO              | [b28f7278cd](https://linux-hardware.org/?probe=b28f7278cd) | Jan 21, 2021 |
| Dell          | 0F8096                      | [27186bb8eb](https://linux-hardware.org/?probe=27186bb8eb) | Jan 18, 2021 |
| Intel         | DH87RL AAG74240-402         | [926473c2ac](https://linux-hardware.org/?probe=926473c2ac) | Jan 16, 2021 |
| Intel         | S3000AHLX D40858-208        | [8508696f16](https://linux-hardware.org/?probe=8508696f16) | Jan 16, 2021 |
| ASRock        | K8A780LM                    | [2e54aedb9e](https://linux-hardware.org/?probe=2e54aedb9e) | Jan 14, 2021 |
| ASRock        | H81M-ITX                    | [50e5d36672](https://linux-hardware.org/?probe=50e5d36672) | Jan 14, 2021 |
| ASUSTek       | A8R-MVP                     | [62ab746796](https://linux-hardware.org/?probe=62ab746796) | Jan 14, 2021 |
| ASUSTek       | M2N-MX SE Plus              | [f6a8e9eaf5](https://linux-hardware.org/?probe=f6a8e9eaf5) | Jan 14, 2021 |
| ASUSTek       | A8R-MVP                     | [00e4deffa2](https://linux-hardware.org/?probe=00e4deffa2) | Jan 14, 2021 |
| Intel         | DH87RL AAG74240-402         | [dcbc8e3b20](https://linux-hardware.org/?probe=dcbc8e3b20) | Jan 14, 2021 |
| Intel         | DH87RL AAG74240-402         | [4877506709](https://linux-hardware.org/?probe=4877506709) | Jan 14, 2021 |
| MSI           | E3M WORKSTATION V5          | [67805433c0](https://linux-hardware.org/?probe=67805433c0) | Jan 13, 2021 |
| Intel         | DH87RL AAG74240-402         | [5e67f36f68](https://linux-hardware.org/?probe=5e67f36f68) | Jan 12, 2021 |
| HP            | 1495                        | [ffb9d2f433](https://linux-hardware.org/?probe=ffb9d2f433) | Jan 08, 2021 |
| ASRock        | B550M Steel Legend          | [a6b6bbef69](https://linux-hardware.org/?probe=a6b6bbef69) | Jan 07, 2021 |
| ASUSTek       | B85M-G                      | [5e66fb7f43](https://linux-hardware.org/?probe=5e66fb7f43) | Jan 07, 2021 |
| ASUSTek       | B85M-G                      | [e7c1c02ce7](https://linux-hardware.org/?probe=e7c1c02ce7) | Jan 07, 2021 |
| Gigabyte      | 970A-DS3P                   | [fa54fc6400](https://linux-hardware.org/?probe=fa54fc6400) | Jan 05, 2021 |
| HP            | 843C                        | [e6c805f9dd](https://linux-hardware.org/?probe=e6c805f9dd) | Jan 04, 2021 |
| Gigabyte      | M4HM87P-00                  | [3523a7845f](https://linux-hardware.org/?probe=3523a7845f) | Jan 04, 2021 |
| Gigabyte      | P35-DS3R                    | [af4f72e797](https://linux-hardware.org/?probe=af4f72e797) | Jan 04, 2021 |
| ASUSTek       | Z170-K                      | [1cdae8bcc1](https://linux-hardware.org/?probe=1cdae8bcc1) | Jan 01, 2021 |
| Gigabyte      | B250M-D3H-CF                | [192fd63a7c](https://linux-hardware.org/?probe=192fd63a7c) | Dec 27, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [e9db8f5ca6](https://linux-hardware.org/?probe=e9db8f5ca6) | Dec 23, 2020 |
| ASRock        | B550M Steel Legend          | [a733d01196](https://linux-hardware.org/?probe=a733d01196) | Dec 22, 2020 |
| ASRock        | B550M Steel Legend          | [bd927d4e12](https://linux-hardware.org/?probe=bd927d4e12) | Dec 22, 2020 |
| ASRock        | B550M Steel Legend          | [a41b1e7e12](https://linux-hardware.org/?probe=a41b1e7e12) | Dec 22, 2020 |
| ASUSTek       | M4A88T-V EVO/USB3           | [7a5a80d939](https://linux-hardware.org/?probe=7a5a80d939) | Dec 20, 2020 |
| MSI           | B85-G43 GAMING              | [915d83d090](https://linux-hardware.org/?probe=915d83d090) | Dec 19, 2020 |
| Gigabyte      | F2A68HM-DS2                 | [7746ff0cda](https://linux-hardware.org/?probe=7746ff0cda) | Dec 15, 2020 |
| Gigabyte      | GA-MA78GM-US2H              | [0719c37bbd](https://linux-hardware.org/?probe=0719c37bbd) | Dec 13, 2020 |
| ASUSTek       | P5QL-E                      | [b74c06cc19](https://linux-hardware.org/?probe=b74c06cc19) | Dec 03, 2020 |
| ASUSTek       | P5QL-E                      | [c3770ada06](https://linux-hardware.org/?probe=c3770ada06) | Dec 03, 2020 |
| ASUSTek       | Rampage II GENE             | [53d482a443](https://linux-hardware.org/?probe=53d482a443) | Nov 17, 2020 |
| ASUSTek       | Rampage II GENE             | [1ab17cdc86](https://linux-hardware.org/?probe=1ab17cdc86) | Nov 15, 2020 |
| HP            | 3646h                       | [747ede17e0](https://linux-hardware.org/?probe=747ede17e0) | Nov 12, 2020 |
| MSI           | B450 TOMAHAWK MAX           | [8a6ca29d49](https://linux-hardware.org/?probe=8a6ca29d49) | Nov 08, 2020 |
| ASUSTek       | P5LD2-X/1333                | [fec864df41](https://linux-hardware.org/?probe=fec864df41) | Nov 01, 2020 |
| HP            | 3396                        | [73bbba4a08](https://linux-hardware.org/?probe=73bbba4a08) | Oct 29, 2020 |
| HP            | 0AA8h                       | [49ed8250dd](https://linux-hardware.org/?probe=49ed8250dd) | Oct 27, 2020 |
| Gigabyte      | P67X-UD3-B3                 | [67dbb5a0d2](https://linux-hardware.org/?probe=67dbb5a0d2) | Oct 18, 2020 |
| Gigabyte      | P67X-UD3-B3                 | [9f49d2fb4f](https://linux-hardware.org/?probe=9f49d2fb4f) | Oct 18, 2020 |
| Dell          | 0RN474                      | [766ce09345](https://linux-hardware.org/?probe=766ce09345) | Oct 17, 2020 |
| ASUSTek       | F2A55-M LK2 PLUS            | [1457975a9b](https://linux-hardware.org/?probe=1457975a9b) | Oct 12, 2020 |
| Gigabyte      | Z270X-Gaming 5              | [152291e032](https://linux-hardware.org/?probe=152291e032) | Oct 07, 2020 |
| MSI           | B360 GAMING PLUS            | [a75b777bc2](https://linux-hardware.org/?probe=a75b777bc2) | Oct 04, 2020 |
| Insyde        | SugarBay                    | [ec1ec65380](https://linux-hardware.org/?probe=ec1ec65380) | Oct 01, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | [e77ec16bac](https://linux-hardware.org/?probe=e77ec16bac) | Sep 29, 2020 |
| Dell          | 0T10XW A00                  | [78018fdd06](https://linux-hardware.org/?probe=78018fdd06) | Sep 20, 2020 |
| HP            | 86FB MVB A                  | [71e7c31b65](https://linux-hardware.org/?probe=71e7c31b65) | Sep 15, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [cad15a6d4c](https://linux-hardware.org/?probe=cad15a6d4c) | Sep 04, 2020 |
| ASUSTek       | PRIME A320M-K               | [d968666b2d](https://linux-hardware.org/?probe=d968666b2d) | Sep 03, 2020 |
| Gigabyte      | H61M-S1                     | [afc3f83ad0](https://linux-hardware.org/?probe=afc3f83ad0) | Sep 02, 2020 |
| Gigabyte      | G31M-S2L                    | [b2fd45876a](https://linux-hardware.org/?probe=b2fd45876a) | Aug 30, 2020 |
| ASUSTek       | P5GC-MX/1333                | [566417bef1](https://linux-hardware.org/?probe=566417bef1) | Aug 30, 2020 |
| ASUSTek       | M5A78L-M LX                 | [2fbe460b8a](https://linux-hardware.org/?probe=2fbe460b8a) | Aug 16, 2020 |
| ASUSTek       | P8Z68-V PRO                 | [5ffffc7647](https://linux-hardware.org/?probe=5ffffc7647) | Aug 06, 2020 |
| Intel         | D945GCCR AAD78647-300       | [c0beab131f](https://linux-hardware.org/?probe=c0beab131f) | Jul 25, 2020 |
| Intel         | D945GCCR AAD78647-300       | [153c0aab66](https://linux-hardware.org/?probe=153c0aab66) | Jul 25, 2020 |
| Gigabyte      | GC330UD                     | [bdfbe25730](https://linux-hardware.org/?probe=bdfbe25730) | Jul 25, 2020 |
| ASUSTek       | H110M-A/M.2                 | [c570792811](https://linux-hardware.org/?probe=c570792811) | Jul 24, 2020 |
| ASUSTek       | H110M-A/M.2                 | [a3dc30f185](https://linux-hardware.org/?probe=a3dc30f185) | Jul 21, 2020 |
| ASUSTek       | H110M-A/M.2                 | [ef6922214a](https://linux-hardware.org/?probe=ef6922214a) | Jul 20, 2020 |
| ASUSTek       | M5A78L-M LX                 | [332ddc42d4](https://linux-hardware.org/?probe=332ddc42d4) | Jul 16, 2020 |
| ASUSTek       | PRIME Z270-A                | [dc205c9f7e](https://linux-hardware.org/?probe=dc205c9f7e) | Jul 13, 2020 |
| ASUSTek       | PRIME Z270-A                | [b02e3bb9e8](https://linux-hardware.org/?probe=b02e3bb9e8) | Jul 13, 2020 |
| ASRock        | H61M-VG4                    | [2f9520527b](https://linux-hardware.org/?probe=2f9520527b) | Jul 11, 2020 |
| ASRock        | H61M-VG4                    | [b36bc5f47e](https://linux-hardware.org/?probe=b36bc5f47e) | Jul 11, 2020 |
| ASUSTek       | F2A55-M LK2 PLUS            | [08f2adba8a](https://linux-hardware.org/?probe=08f2adba8a) | Jul 11, 2020 |
| ASUSTek       | F2A55-M LK2 PLUS            | [c6ed1cd30d](https://linux-hardware.org/?probe=c6ed1cd30d) | Jul 11, 2020 |
| ASUSTek       | P5KPL-AM EPU                | [6ab55c2cfa](https://linux-hardware.org/?probe=6ab55c2cfa) | Jul 03, 2020 |
| ASUSTek       | P5KPL-AM EPU                | [a4b6a8dfb6](https://linux-hardware.org/?probe=a4b6a8dfb6) | Jul 02, 2020 |
| ASUSTek       | M4N78-AM V2                 | [ce2c44ec00](https://linux-hardware.org/?probe=ce2c44ec00) | Jun 16, 2020 |
| ASUSTek       | P7P55D                      | [eeef655b1c](https://linux-hardware.org/?probe=eeef655b1c) | Jun 07, 2020 |
| ASUSTek       | P5P43TD PRO                 | [bdafad0c82](https://linux-hardware.org/?probe=bdafad0c82) | Jun 06, 2020 |
| MSI           | B150M MORTAR                | [7cdf6f047d](https://linux-hardware.org/?probe=7cdf6f047d) | Jun 01, 2020 |
| ASUSTek       | P5P43TD PRO                 | [38acad164f](https://linux-hardware.org/?probe=38acad164f) | May 25, 2020 |
| Pegatron      | 2A73h                       | [0161ecea31](https://linux-hardware.org/?probe=0161ecea31) | May 19, 2020 |
| Pegatron      | 2A73h                       | [42d74e715d](https://linux-hardware.org/?probe=42d74e715d) | May 15, 2020 |
| ASUSTek       | Maximus IX APEX             | [0725349aa7](https://linux-hardware.org/?probe=0725349aa7) | May 11, 2020 |
| Gigabyte      | H61M-S1                     | [b14767e270](https://linux-hardware.org/?probe=b14767e270) | May 07, 2020 |
| ASUSTek       | P5QL-E                      | [d1b8d74839](https://linux-hardware.org/?probe=d1b8d74839) | May 05, 2020 |
| ASUSTek       | M2N-CM DVI                  | [723d371342](https://linux-hardware.org/?probe=723d371342) | Apr 27, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [ebd71cc64d](https://linux-hardware.org/?probe=ebd71cc64d) | Apr 18, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [bbd20923db](https://linux-hardware.org/?probe=bbd20923db) | Apr 18, 2020 |
| Gigabyte      | EP35-DS3                    | [686cd298e3](https://linux-hardware.org/?probe=686cd298e3) | Apr 13, 2020 |
| HP            | 3646h                       | [96421cb602](https://linux-hardware.org/?probe=96421cb602) | Apr 06, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [e6c9f406df](https://linux-hardware.org/?probe=e6c9f406df) | Apr 04, 2020 |
| HP            | 86FB MVB A                  | [91e5642800](https://linux-hardware.org/?probe=91e5642800) | Apr 02, 2020 |
| HP            | 86FB MVB A                  | [95ece68ba4](https://linux-hardware.org/?probe=95ece68ba4) | Apr 02, 2020 |
| ASRock        | 960GC-GS FX                 | [a450257a10](https://linux-hardware.org/?probe=a450257a10) | Mar 31, 2020 |
| Lenovo        | SHARKBAY 31900058 STD       | [92917041c1](https://linux-hardware.org/?probe=92917041c1) | Mar 31, 2020 |
| MSI           | B150M MORTAR                | [99a354df1f](https://linux-hardware.org/?probe=99a354df1f) | Mar 31, 2020 |
| ASUSTek       | VM42                        | [29c87fb102](https://linux-hardware.org/?probe=29c87fb102) | Mar 25, 2020 |
| Intel         | DH87RL AAG74240-402         | [fce111bb71](https://linux-hardware.org/?probe=fce111bb71) | Mar 19, 2020 |
| ASUSTek       | P5LD2-X/1333                | [d278f46944](https://linux-hardware.org/?probe=d278f46944) | Mar 19, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [4af2951135](https://linux-hardware.org/?probe=4af2951135) | Mar 02, 2020 |
| Gigabyte      | X58A-UD3R                   | [58c69a16ec](https://linux-hardware.org/?probe=58c69a16ec) | Feb 29, 2020 |
| Gigabyte      | H61M-S1                     | [b5ef9a6442](https://linux-hardware.org/?probe=b5ef9a6442) | Feb 28, 2020 |
| Gigabyte      | X58A-UD3R                   | [4e592e37d9](https://linux-hardware.org/?probe=4e592e37d9) | Feb 28, 2020 |
| Gigabyte      | AB350-Gaming 3-CF           | [b0a4a95414](https://linux-hardware.org/?probe=b0a4a95414) | Feb 22, 2020 |
| ASUSTek       | M2N-CM DVI                  | [e808fea491](https://linux-hardware.org/?probe=e808fea491) | Feb 14, 2020 |
| MSI           | MS-6702                     | [86b96afa86](https://linux-hardware.org/?probe=86b96afa86) | Feb 07, 2020 |
| Lenovo        | ThinkCentre M58p 7484WHT    | [69debaef8a](https://linux-hardware.org/?probe=69debaef8a) | Feb 06, 2020 |
| MSI           | MS-6702                     | [16256584cd](https://linux-hardware.org/?probe=16256584cd) | Jan 29, 2020 |
| Gigabyte      | AB350-Gaming 3-CF           | [b839b04f7b](https://linux-hardware.org/?probe=b839b04f7b) | Jan 24, 2020 |
| Intel         | Bearlake Fab D              | [6c46de300b](https://linux-hardware.org/?probe=6c46de300b) | Jan 20, 2020 |
| ASRock        | K8A780LM                    | [e0d3030787](https://linux-hardware.org/?probe=e0d3030787) | Jan 18, 2020 |
| ASRock        | K8A780LM                    | [83dca94e72](https://linux-hardware.org/?probe=83dca94e72) | Jan 17, 2020 |
| ASRock        | K8A780LM                    | [a5e0479887](https://linux-hardware.org/?probe=a5e0479887) | Jan 16, 2020 |
| MSI           | MS-6702                     | [e78238313a](https://linux-hardware.org/?probe=e78238313a) | Jan 13, 2020 |
| Gigabyte      | P31-ES3G                    | [57ed00d8a8](https://linux-hardware.org/?probe=57ed00d8a8) | Jan 08, 2020 |
| ASUSTek       | P5QL-E                      | [6949452f0e](https://linux-hardware.org/?probe=6949452f0e) | Dec 25, 2019 |
| ASUSTek       | P5LD2-X/1333                | [e643b8ed58](https://linux-hardware.org/?probe=e643b8ed58) | Dec 25, 2019 |
| Unknown       | Unknown                     | [4050b2d0d1](https://linux-hardware.org/?probe=4050b2d0d1) | Dec 25, 2019 |
| Unknown       | Unknown                     | [ca23ab1ec8](https://linux-hardware.org/?probe=ca23ab1ec8) | Dec 25, 2019 |
| ASRock        | H81M-ITX                    | [c51735ee45](https://linux-hardware.org/?probe=c51735ee45) | Dec 21, 2019 |
| MSI           | MS-7199                     | [8fe7e9e6a6](https://linux-hardware.org/?probe=8fe7e9e6a6) | Dec 21, 2019 |
| ASUSTek       | VM42                        | [66ad05d5ab](https://linux-hardware.org/?probe=66ad05d5ab) | Dec 12, 2019 |
| Intel         | DZ77GA-70K AAG39009-401     | [44917a35a9](https://linux-hardware.org/?probe=44917a35a9) | Dec 12, 2019 |
| MSI           | MS-6702                     | [792cf869f8](https://linux-hardware.org/?probe=792cf869f8) | Nov 26, 2019 |
| MSI           | 09AC                        | [9188878c2a](https://linux-hardware.org/?probe=9188878c2a) | Nov 19, 2019 |
| ASUSTek       | M2N-E                       | [bb3948f168](https://linux-hardware.org/?probe=bb3948f168) | Nov 15, 2019 |
| ASUSTek       | M2N-E                       | [dc0d15703c](https://linux-hardware.org/?probe=dc0d15703c) | Nov 15, 2019 |
| ASUSTek       | M2N-E                       | [8a49a38575](https://linux-hardware.org/?probe=8a49a38575) | Nov 14, 2019 |
| ASUSTek       | M2N-E                       | [6522851ca9](https://linux-hardware.org/?probe=6522851ca9) | Nov 14, 2019 |
| MSI           | MS-6702                     | [05aa9bf00f](https://linux-hardware.org/?probe=05aa9bf00f) | Nov 13, 2019 |
| Gigabyte      | B360M D3H-CF                | [1c1d5c438a](https://linux-hardware.org/?probe=1c1d5c438a) | Nov 11, 2019 |
| Acer          | Aspire TC-705               | [b732ce4528](https://linux-hardware.org/?probe=b732ce4528) | Nov 04, 2019 |
| ASUSTek       | A8N-E                       | [16b128fafe](https://linux-hardware.org/?probe=16b128fafe) | Nov 04, 2019 |
| ASRock        | H81M-ITX                    | [431ea0cbed](https://linux-hardware.org/?probe=431ea0cbed) | Oct 25, 2019 |
| Dell          | 0F8096                      | [d1f6910c12](https://linux-hardware.org/?probe=d1f6910c12) | Oct 20, 2019 |
| ASUSTek       | M2N-MX SE Plus              | [f4fcd6e28c](https://linux-hardware.org/?probe=f4fcd6e28c) | Oct 20, 2019 |
| ASRock        | H81M-ITX                    | [c5f47f2f27](https://linux-hardware.org/?probe=c5f47f2f27) | Oct 20, 2019 |
| ASUSTek       | M2N-E                       | [96f3d49886](https://linux-hardware.org/?probe=96f3d49886) | Oct 11, 2019 |
| ASUSTek       | M2N-E                       | [5d2552d841](https://linux-hardware.org/?probe=5d2552d841) | Oct 11, 2019 |
| ASUSTek       | M2N-E                       | [c7128161ce](https://linux-hardware.org/?probe=c7128161ce) | Sep 22, 2019 |
| MSI           | MS-6702                     | [72a17e9871](https://linux-hardware.org/?probe=72a17e9871) | Sep 17, 2019 |
| ASUSTek       | H97-PLUS                    | [fc8496dd5a](https://linux-hardware.org/?probe=fc8496dd5a) | Sep 07, 2019 |
| MSI           | MS-6702                     | [3049044a80](https://linux-hardware.org/?probe=3049044a80) | Aug 26, 2019 |
| MSI           | MS-6702                     | [ab947df2c3](https://linux-hardware.org/?probe=ab947df2c3) | Aug 18, 2019 |
| MSI           | MS-6702                     | [3f6b808c8b](https://linux-hardware.org/?probe=3f6b808c8b) | Aug 14, 2019 |
| Dell          | 0DN075                      | [07c3b02228](https://linux-hardware.org/?probe=07c3b02228) | Aug 09, 2019 |
| ASUSTek       | H110M-C                     | [75e32af34d](https://linux-hardware.org/?probe=75e32af34d) | Jul 13, 2019 |
| ASUSTek       | P5L-MX                      | [0c62c4c191](https://linux-hardware.org/?probe=0c62c4c191) | Jun 23, 2019 |
| ASUSTek       | H81M-PLUS                   | [068460eef5](https://linux-hardware.org/?probe=068460eef5) | Jun 15, 2019 |
| MSI           | MS-7407 100                 | [245e00b979](https://linux-hardware.org/?probe=245e00b979) | May 31, 2019 |
| MSI           | MS-6702                     | [1ed53a3a07](https://linux-hardware.org/?probe=1ed53a3a07) | May 05, 2019 |
| ASUSTek       | H110M-C                     | [49d390f38b](https://linux-hardware.org/?probe=49d390f38b) | Apr 14, 2019 |
| ASUSTek       | H110M-C                     | [f48d00866d](https://linux-hardware.org/?probe=f48d00866d) | Apr 10, 2019 |
| Intel         | D925XECV2 AAC83685-205      | [8987ff9068](https://linux-hardware.org/?probe=8987ff9068) | Apr 06, 2019 |
| ASUSTek       | P8Z77-V LX2                 | [6266e950d1](https://linux-hardware.org/?probe=6266e950d1) | Apr 05, 2019 |
| ASUSTek       | M2N-E                       | [59375f9231](https://linux-hardware.org/?probe=59375f9231) | Apr 03, 2019 |
| MSI           | MS-6702                     | [dc92061311](https://linux-hardware.org/?probe=dc92061311) | Apr 02, 2019 |
| MSI           | MS-6702                     | [d62caac198](https://linux-hardware.org/?probe=d62caac198) | Apr 01, 2019 |
| Lenovo        | Tiger Hill                  | [edb984c4e6](https://linux-hardware.org/?probe=edb984c4e6) | Mar 05, 2019 |
| Gigabyte      | F2A68HM-DS2                 | [0ca153c41c](https://linux-hardware.org/?probe=0ca153c41c) | Feb 02, 2019 |
| Dell          | Precision WorkStation 39... | [6040d653c3](https://linux-hardware.org/?probe=6040d653c3) | Jan 09, 2019 |
| Gigabyte      | GA-MA78GM-US2H              | [505cff22f1](https://linux-hardware.org/?probe=505cff22f1) | Nov 11, 2018 |
| Gigabyte      | Z77X-D3H                    | [d9fcab9ba7](https://linux-hardware.org/?probe=d9fcab9ba7) | Nov 03, 2018 |
| HP            | 3047h                       | [bd13661f57](https://linux-hardware.org/?probe=bd13661f57) | Oct 26, 2018 |
| HP            | 3047h                       | [64f2865562](https://linux-hardware.org/?probe=64f2865562) | Oct 26, 2018 |
| Dell          | 0DN075                      | [2951e393ca](https://linux-hardware.org/?probe=2951e393ca) | Jun 02, 2018 |
| MSI           | G41TM-P33                   | [1622e88ef5](https://linux-hardware.org/?probe=1622e88ef5) | Apr 25, 2018 |
| MSI           | G41TM-P33                   | [e05768e40a](https://linux-hardware.org/?probe=e05768e40a) | Apr 12, 2018 |
| MSI           | A88X-G45 GAMING             | [985c8f6bb3](https://linux-hardware.org/?probe=985c8f6bb3) | Jan 25, 2018 |
| MSI           | G41TM-P33                   | [3175c5de11](https://linux-hardware.org/?probe=3175c5de11) | Nov 13, 2017 |
| Gigabyte      | P41-ES3G                    | [f6a2b721dc](https://linux-hardware.org/?probe=f6a2b721dc) | Oct 12, 2017 |
| ASUSTek       | N3700T                      | [175b0f5a5d](https://linux-hardware.org/?probe=175b0f5a5d) | Oct 01, 2017 |
| ASUSTek       | TUF Z270 MARK 1             | [2308897059](https://linux-hardware.org/?probe=2308897059) | Jul 03, 2017 |
| MSI           | G41TM-P33                   | [54f6608d0d](https://linux-hardware.org/?probe=54f6608d0d) | Mar 29, 2017 |
| Gigabyte      | P41-ES3G                    | [f2e7fc2411](https://linux-hardware.org/?probe=f2e7fc2411) | Mar 13, 2017 |
| MSI           | G41TM-P33                   | [f585f0a037](https://linux-hardware.org/?probe=f585f0a037) | Feb 22, 2017 |
| MSI           | G41TM-P33                   | [a14f2598e7](https://linux-hardware.org/?probe=a14f2598e7) | Feb 22, 2017 |
| Gigabyte      | M61PME-S2P                  | [f27dd0a73e](https://linux-hardware.org/?probe=f27dd0a73e) | Feb 15, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Ubuntu 20.04       | 33       | 15%     |
| Ubuntu 18.04       | 18       | 8.18%   |
| OpenMandriva 4.2   | 13       | 5.91%   |
| BlackPanther 18.1  | 12       | 5.45%   |
| ROSA R10           | 6        | 2.73%   |
| Linux Mint 20.1    | 6        | 2.73%   |
| Ubuntu 19.10       | 5        | 2.27%   |
| ROSA R9            | 5        | 2.27%   |
| Linux Mint 20.2    | 5        | 2.27%   |
| OpenMandriva 4.50  | 4        | 1.82%   |
| OpenMandriva 4.3   | 4        | 1.82%   |
| MX 19              | 4        | 1.82%   |
| Linux Mint 20.3    | 4        | 1.82%   |
| Linux Mint 20      | 4        | 1.82%   |
| Xubuntu 18.04      | 3        | 1.36%   |
| Ubuntu 18.10       | 3        | 1.36%   |
| ROSA R11           | 3        | 1.36%   |
| Pop!_OS 21.10      | 3        | 1.36%   |
| Pop!_OS 20.04      | 3        | 1.36%   |
| MX 18              | 3        | 1.36%   |
| Manjaro 20.1       | 3        | 1.36%   |
| Linux Mint 19.3    | 3        | 1.36%   |
| Fedora 34          | 3        | 1.36%   |
| Fedora 33          | 3        | 1.36%   |
| Debian 10          | 3        | 1.36%   |
| Zorin 16           | 2        | 0.91%   |
| Ubuntu 22.04       | 2        | 0.91%   |
| Ubuntu 20.10       | 2        | 0.91%   |
| ROSA R8            | 2        | 0.91%   |
| Pop!_OS 20.10      | 2        | 0.91%   |
| openSUSE Leap-15.3 | 2        | 0.91%   |
| Manjaro            | 2        | 0.91%   |
| Linux Mint 19.1    | 2        | 0.91%   |
| Linux Mint 19      | 2        | 0.91%   |
| Kubuntu 20.04      | 2        | 0.91%   |
| KDE neon 20.04     | 2        | 0.91%   |
| Gentoo 2.7         | 2        | 0.91%   |
| Fedora 31          | 2        | 0.91%   |
| Devuan 3           | 2        | 0.91%   |
| Debian 11          | 2        | 0.91%   |
| ArcoLinux Rolling  | 2        | 0.91%   |
| Arch Rolling       | 2        | 0.91%   |
| Arch               | 2        | 0.91%   |
| Xubuntu 20.10      | 1        | 0.45%   |
| Xubuntu 19.10      | 1        | 0.45%   |
| Xubuntu 18.10      | 1        | 0.45%   |
| Xubuntu 16.04      | 1        | 0.45%   |
| Ubuntu 21.04       | 1        | 0.45%   |
| Ubuntu 19.04       | 1        | 0.45%   |
| Ubuntu 16.04       | 1        | 0.45%   |
| ROSA R8.1          | 1        | 0.45%   |
| ROSA R11.1         | 1        | 0.45%   |
| Pop!_OS 22.04      | 1        | 0.45%   |
| OpenMandriva 4.1   | 1        | 0.45%   |
| MX 17              | 1        | 0.45%   |
| Manjaro 21.2.6     | 1        | 0.45%   |
| Manjaro 20.0.3     | 1        | 0.45%   |
| Lubuntu 21.10      | 1        | 0.45%   |
| LMDE 4             | 1        | 0.45%   |
| Kubuntu 20.10      | 1        | 0.45%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 62       | 30.39%  |
| Linux Mint   | 22       | 10.78%  |
| OpenMandriva | 21       | 10.29%  |
| ROSA         | 14       | 6.86%   |
| BlackPanther | 13       | 6.37%   |
| Pop!_OS      | 9        | 4.41%   |
| Fedora       | 9        | 4.41%   |
| MX           | 7        | 3.43%   |
| Manjaro      | 7        | 3.43%   |
| Xubuntu      | 6        | 2.94%   |
| Debian       | 6        | 2.94%   |
| Arch         | 4        | 1.96%   |
| Kubuntu      | 3        | 1.47%   |
| Gentoo       | 3        | 1.47%   |
| Devuan       | 3        | 1.47%   |
| Zorin        | 2        | 0.98%   |
| openSUSE     | 2        | 0.98%   |
| KDE neon     | 2        | 0.98%   |
| ArcoLinux    | 2        | 0.98%   |
| Lubuntu      | 1        | 0.49%   |
| LMDE         | 1        | 0.49%   |
| Garuda Linux | 1        | 0.49%   |
| Endless      | 1        | 0.49%   |
| CentOS       | 1        | 0.49%   |
| BunsenLabs   | 1        | 0.49%   |
| antiX        | 1        | 0.49%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                          | Desktops | Percent |
|----------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002         | 12       | 4.65%   |
| 4.18.16-desktop-1bP              | 12       | 4.65%   |
| 5.4.0-58-generic                 | 6        | 2.33%   |
| 4.19.0-14-amd64                  | 5        | 1.94%   |
| 4.19.0-13-amd64                  | 5        | 1.94%   |
| 5.8.0-44-generic                 | 4        | 1.55%   |
| 5.16.7-desktop-1omv4003          | 4        | 1.55%   |
| 5.4.0-90-generic                 | 3        | 1.16%   |
| 5.4.0-77-generic                 | 3        | 1.16%   |
| 5.4.0-65-generic                 | 3        | 1.16%   |
| 5.4.0-52-generic                 | 3        | 1.16%   |
| 5.4.0-26-generic                 | 3        | 1.16%   |
| 5.3.0-40-generic                 | 3        | 1.16%   |
| 4.9.60-nrj-desktop-1rosa-x86_64  | 3        | 1.16%   |
| 4.18.0-17-generic                | 3        | 1.16%   |
| 4.15.0-66-generic                | 3        | 1.16%   |
| 5.8.0-43-generic                 | 2        | 0.78%   |
| 5.8.0-41-generic                 | 2        | 0.78%   |
| 5.4.0-7634-generic               | 2        | 0.78%   |
| 5.4.0-74-generic                 | 2        | 0.78%   |
| 5.4.0-73-generic                 | 2        | 0.78%   |
| 5.4.0-66-generic                 | 2        | 0.78%   |
| 5.4.0-42-generic                 | 2        | 0.78%   |
| 5.4.0-33-generic                 | 2        | 0.78%   |
| 5.3.0-42-generic                 | 2        | 0.78%   |
| 5.3.0-26-generic                 | 2        | 0.78%   |
| 5.3.0-24-generic                 | 2        | 0.78%   |
| 5.16.11-76051611-generic         | 2        | 0.78%   |
| 5.15.0-27-generic                | 2        | 0.78%   |
| 5.13.0-37-generic                | 2        | 0.78%   |
| 5.13.0-28-generic                | 2        | 0.78%   |
| 5.12.4-desktop-1omv4050          | 2        | 0.78%   |
| 5.11.0-7614-generic              | 2        | 0.78%   |
| 5.11.0-41-generic                | 2        | 0.78%   |
| 5.11.0-27-generic                | 2        | 0.78%   |
| 4.9.9-nrj-desktop-1rosa-x86_64   | 2        | 0.78%   |
| 4.9.20-nrj-desktop-1rosa-x86_64  | 2        | 0.78%   |
| 4.9.124-nrj-desktop-1rosa-x86_64 | 2        | 0.78%   |
| 4.19.0-6-amd64                   | 2        | 0.78%   |
| 4.18.0-18-generic                | 2        | 0.78%   |
| 4.15.0-96-generic                | 2        | 0.78%   |
| 4.15.0-22-generic                | 2        | 0.78%   |
| 5.9.16-gentoo-x86_64             | 1        | 0.39%   |
| 5.9.16-200.fc33.x86_64           | 1        | 0.39%   |
| 5.9.15-gentoo-x86_64             | 1        | 0.39%   |
| 5.9.14-200.fc33.x86_64           | 1        | 0.39%   |
| 5.8.3-2-MANJARO                  | 1        | 0.39%   |
| 5.8.18-300.fc33.x86_64           | 1        | 0.39%   |
| 5.8.18-1-MANJARO                 | 1        | 0.39%   |
| 5.8.0-7630-generic               | 1        | 0.39%   |
| 5.8.0-63-generic                 | 1        | 0.39%   |
| 5.8.0-59-generic                 | 1        | 0.39%   |
| 5.8.0-55-generic                 | 1        | 0.39%   |
| 5.8.0-50-generic                 | 1        | 0.39%   |
| 5.8.0-48-generic                 | 1        | 0.39%   |
| 5.8.0-40-generic                 | 1        | 0.39%   |
| 5.8.0-34-generic                 | 1        | 0.39%   |
| 5.8.0-14-generic                 | 1        | 0.39%   |
| 5.8.0-0.bpo.2-amd64              | 1        | 0.39%   |
| 5.7.9-100.fc31.x86_64            | 1        | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 44       | 18.97%  |
| 4.15.0  | 20       | 8.62%   |
| 5.8.0   | 17       | 7.33%   |
| 5.3.0   | 13       | 5.6%    |
| 4.18.16 | 13       | 5.6%    |
| 5.10.14 | 12       | 5.17%   |
| 5.11.0  | 9        | 3.88%   |
| 5.13.0  | 8        | 3.45%   |
| 4.18.0  | 8        | 3.45%   |
| 4.19.0  | 7        | 3.02%   |
| 5.16.7  | 4        | 1.72%   |
| 5.15.0  | 3        | 1.29%   |
| 4.9.60  | 3        | 1.29%   |
| 5.9.16  | 2        | 0.86%   |
| 5.8.18  | 2        | 0.86%   |
| 5.3.18  | 2        | 0.86%   |
| 5.16.11 | 2        | 0.86%   |
| 5.13.4  | 2        | 0.86%   |
| 5.12.4  | 2        | 0.86%   |
| 5.10.0  | 2        | 0.86%   |
| 5.0.0   | 2        | 0.86%   |
| 4.9.9   | 2        | 0.86%   |
| 4.9.20  | 2        | 0.86%   |
| 4.9.124 | 2        | 0.86%   |
| 4.9.0   | 2        | 0.86%   |
| 5.9.15  | 1        | 0.43%   |
| 5.9.14  | 1        | 0.43%   |
| 5.8.3   | 1        | 0.43%   |
| 5.7.9   | 1        | 0.43%   |
| 5.7.19  | 1        | 0.43%   |
| 5.7.17  | 1        | 0.43%   |
| 5.7.15  | 1        | 0.43%   |
| 5.7.1   | 1        | 0.43%   |
| 5.7.0   | 1        | 0.43%   |
| 5.5.12  | 1        | 0.43%   |
| 5.5.0   | 1        | 0.43%   |
| 5.4.83  | 1        | 0.43%   |
| 5.4.64  | 1        | 0.43%   |
| 5.4.188 | 1        | 0.43%   |
| 5.3.8   | 1        | 0.43%   |
| 5.2.21  | 1        | 0.43%   |
| 5.16.19 | 1        | 0.43%   |
| 5.16.10 | 1        | 0.43%   |
| 5.16.0  | 1        | 0.43%   |
| 5.15.8  | 1        | 0.43%   |
| 5.15.2  | 1        | 0.43%   |
| 5.15.13 | 1        | 0.43%   |
| 5.14.7  | 1        | 0.43%   |
| 5.14.18 | 1        | 0.43%   |
| 5.14.16 | 1        | 0.43%   |
| 5.13.7  | 1        | 0.43%   |
| 5.13.16 | 1        | 0.43%   |
| 5.13.12 | 1        | 0.43%   |
| 5.12.6  | 1        | 0.43%   |
| 5.12.12 | 1        | 0.43%   |
| 5.12.10 | 1        | 0.43%   |
| 5.11.7  | 1        | 0.43%   |
| 5.11.15 | 1        | 0.43%   |
| 5.11.12 | 1        | 0.43%   |
| 5.10.61 | 1        | 0.43%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 47       | 20.8%   |
| 4.18    | 21       | 9.29%   |
| 5.8     | 20       | 8.85%   |
| 4.15    | 20       | 8.85%   |
| 5.10    | 17       | 7.52%   |
| 5.3     | 16       | 7.08%   |
| 4.9     | 12       | 5.31%   |
| 5.13    | 11       | 4.87%   |
| 5.11    | 11       | 4.87%   |
| 5.16    | 9        | 3.98%   |
| 4.19    | 8        | 3.54%   |
| 5.7     | 6        | 2.65%   |
| 5.15    | 6        | 2.65%   |
| 5.12    | 5        | 2.21%   |
| 5.9     | 3        | 1.33%   |
| 5.14    | 3        | 1.33%   |
| 5.5     | 2        | 0.88%   |
| 5.0     | 2        | 0.88%   |
| 4.1     | 2        | 0.88%   |
| 5.2     | 1        | 0.44%   |
| 5.1     | 1        | 0.44%   |
| 4.7     | 1        | 0.44%   |
| 4.4     | 1        | 0.44%   |
| 4.11    | 1        | 0.44%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 181      | 91.88%  |
| i686   | 16       | 8.12%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 73       | 36.14%  |
| KDE5       | 50       | 24.75%  |
| XFCE       | 24       | 11.88%  |
| Unknown    | 21       | 10.4%   |
| X-Cinnamon | 12       | 5.94%   |
| KDE4       | 6        | 2.97%   |
| MATE       | 5        | 2.48%   |
| KDE        | 4        | 1.98%   |
| Cinnamon   | 3        | 1.49%   |
| Unity      | 2        | 0.99%   |
| LXQt       | 1        | 0.5%    |
| bspwm      | 1        | 0.5%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 170      | 83.74%  |
| Wayland | 17       | 8.37%   |
| Unknown | 14       | 6.9%    |
| Tty     | 2        | 0.99%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 97       | 47.09%  |
| SDDM    | 52       | 25.24%  |
| LightDM | 15       | 7.28%   |
| GDM     | 13       | 6.31%   |
| GDM3    | 12       | 5.83%   |
| TDM     | 8        | 3.88%   |
| KDM     | 6        | 2.91%   |
| SLiM    | 3        | 1.46%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| sk_SK   | 77       | 37.93%  |
| en_US   | 56       | 27.59%  |
| Unknown | 52       | 25.62%  |
| cs_CZ   | 8        | 3.94%   |
| en_GB   | 4        | 1.97%   |
| hu_HU   | 2        | 0.99%   |
| C       | 2        | 0.99%   |
| POSIX   | 1        | 0.49%   |
| en_AU   | 1        | 0.49%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 149      | 76.02%  |
| EFI  | 47       | 23.98%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 137      | 67.16%  |
| Overlay | 35       | 17.16%  |
| Btrfs   | 16       | 7.84%   |
| Unknown | 10       | 4.9%    |
| Xfs     | 3        | 1.47%   |
| Zfs     | 2        | 0.98%   |
| Ext2    | 1        | 0.49%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 106      | 52.48%  |
| MBR     | 59       | 29.21%  |
| GPT     | 37       | 18.32%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 160      | 76.19%  |
| Yes       | 50       | 23.81%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 130      | 63.73%  |
| Yes       | 74       | 36.27%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 66       | 33.85%  |
| Gigabyte Technology | 37       | 18.97%  |
| MSI                 | 19       | 9.74%   |
| Hewlett-Packard     | 16       | 8.21%   |
| ASRock              | 13       | 6.67%   |
| Dell                | 11       | 5.64%   |
| Intel               | 10       | 5.13%   |
| Lenovo              | 7        | 3.59%   |
| Foxconn             | 4        | 2.05%   |
| Acer                | 4        | 2.05%   |
| Pegatron            | 2        | 1.03%   |
| Unknown             | 2        | 1.03%   |
| VIA Technologies    | 1        | 0.51%   |
| Shuttle             | 1        | 0.51%   |
| Insyde              | 1        | 0.51%   |
| Fujitsu Siemens     | 1        | 0.51%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUS All Series                      | 9        | 4.62%   |
| Gigabyte F2A68HM-DS2                 | 3        | 1.54%   |
| MSI MS-7C02                          | 2        | 1.03%   |
| Lenovo IdeaCentre Q180 10087&3110    | 2        | 1.03%   |
| HP Compaq 8000 Elite SFF PC          | 2        | 1.03%   |
| HP Compaq 6005 Pro SFF PC            | 2        | 1.03%   |
| Gigabyte H61M-S1                     | 2        | 1.03%   |
| Gigabyte GA-MA78GM-US2H              | 2        | 1.03%   |
| Gigabyte AB350-Gaming 3              | 2        | 1.03%   |
| Gigabyte 970A-DS3P                   | 2        | 1.03%   |
| Foxconn G41MX/G41MX-K 2.0 1.0        | 2        | 1.03%   |
| Dell Precision WorkStation 390       | 2        | 1.03%   |
| Dell OptiPlex 7010                   | 2        | 1.03%   |
| ASUS ROG STRIX X570-E GAMING         | 2        | 1.03%   |
| ASUS P5QL-E                          | 2        | 1.03%   |
| ASUS M4A88T-V EVO/USB3               | 2        | 1.03%   |
| ASUS F2A55-M LK2 PLUS                | 2        | 1.03%   |
| ASRock N68C-S UCC                    | 2        | 1.03%   |
| ASRock K8A780LM                      | 2        | 1.03%   |
| Unknown                              | 2        | 1.03%   |
| VIA KM266-8235                       | 1        | 0.51%   |
| Shuttle XH61V                        | 1        | 0.51%   |
| Pegatron Elite 7500 Series MT        | 1        | 0.51%   |
| Pegatron Compaq dx2400 Microtower PC | 1        | 0.51%   |
| MSI MS-7B98                          | 1        | 0.51%   |
| MSI MS-7B22                          | 1        | 0.51%   |
| MSI MS-7A44                          | 1        | 0.51%   |
| MSI MS-7A40                          | 1        | 0.51%   |
| MSI MS-7996                          | 1        | 0.51%   |
| MSI MS-7972                          | 1        | 0.51%   |
| MSI MS-7922                          | 1        | 0.51%   |
| MSI MS-7900                          | 1        | 0.51%   |
| MSI MS-7816                          | 1        | 0.51%   |
| MSI MS-7695                          | 1        | 0.51%   |
| MSI MS-7641                          | 1        | 0.51%   |
| MSI MS-7592                          | 1        | 0.51%   |
| MSI MS-7388                          | 1        | 0.51%   |
| MSI MS-7199                          | 1        | 0.51%   |
| MSI MS-6702                          | 1        | 0.51%   |
| MSI MS-6470                          | 1        | 0.51%   |
| MSI dx5150 MT(EP572ES)               | 1        | 0.51%   |
| Lenovo V530-15ICR 11BH0028XS         | 1        | 0.51%   |
| Lenovo ThinkCentre M92p 3209B4G      | 1        | 0.51%   |
| Lenovo ThinkCentre M58p 7484WHT      | 1        | 0.51%   |
| Lenovo H50-50 90B600KECK             | 1        | 0.51%   |
| Lenovo 3000 870020z                  | 1        | 0.51%   |
| Intel X99                            | 1        | 0.51%   |
| Intel S3000AHLX D40858-208           | 1        | 0.51%   |
| Intel DZ77GA-70K AAG39009-401        | 1        | 0.51%   |
| Intel DH87RL AAG74240-402            | 1        | 0.51%   |
| Intel DH77EB AAG39073-304            | 1        | 0.51%   |
| Intel DG41KR AAE62839-304            | 1        | 0.51%   |
| Intel D945GCCR AAD78647-300          | 1        | 0.51%   |
| Intel D925XECV2 AAC83685-205         | 1        | 0.51%   |
| Intel D815EEA AAA45884-401           | 1        | 0.51%   |
| Intel Bearlake Fab D                 | 1        | 0.51%   |
| Insyde SugarBay                      | 1        | 0.51%   |
| HP ProLiant ML350 G5                 | 1        | 0.51%   |
| HP ProLiant MicroServer Gen8         | 1        | 0.51%   |
| HP EliteDesk 800 G1 USDT             | 1        | 0.51%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| HP Compaq               | 11       | 5.64%   |
| ASUS All                | 9        | 4.62%   |
| Dell OptiPlex           | 7        | 3.59%   |
| ASUS ROG                | 7        | 3.59%   |
| ASUS PRIME              | 6        | 3.08%   |
| Gigabyte F2A68HM-DS2    | 3        | 1.54%   |
| Dell Precision          | 3        | 1.54%   |
| ASUS TUF                | 3        | 1.54%   |
| Acer Aspire             | 3        | 1.54%   |
| MSI MS-7C02             | 2        | 1.03%   |
| Lenovo ThinkCentre      | 2        | 1.03%   |
| Lenovo IdeaCentre       | 2        | 1.03%   |
| HP ProLiant             | 2        | 1.03%   |
| Gigabyte H61M-S1        | 2        | 1.03%   |
| Gigabyte GA-MA78GM-US2H | 2        | 1.03%   |
| Gigabyte AB350-Gaming   | 2        | 1.03%   |
| Gigabyte 970A-DS3P      | 2        | 1.03%   |
| Foxconn G41MX           | 2        | 1.03%   |
| ASUS P5QL-E             | 2        | 1.03%   |
| ASUS P5KPL-AM           | 2        | 1.03%   |
| ASUS P5GC-MX            | 2        | 1.03%   |
| ASUS Maximus            | 2        | 1.03%   |
| ASUS M5A78L-M           | 2        | 1.03%   |
| ASUS M4A88T-V           | 2        | 1.03%   |
| ASUS F2A55-M            | 2        | 1.03%   |
| ASRock N68C-S           | 2        | 1.03%   |
| ASRock K8A780LM         | 2        | 1.03%   |
| Unknown                 | 2        | 1.03%   |
| VIA KM266-8235          | 1        | 0.51%   |
| Shuttle XH61V           | 1        | 0.51%   |
| Pegatron Elite          | 1        | 0.51%   |
| Pegatron Compaq         | 1        | 0.51%   |
| MSI MS-7B98             | 1        | 0.51%   |
| MSI MS-7B22             | 1        | 0.51%   |
| MSI MS-7A44             | 1        | 0.51%   |
| MSI MS-7A40             | 1        | 0.51%   |
| MSI MS-7996             | 1        | 0.51%   |
| MSI MS-7972             | 1        | 0.51%   |
| MSI MS-7922             | 1        | 0.51%   |
| MSI MS-7900             | 1        | 0.51%   |
| MSI MS-7816             | 1        | 0.51%   |
| MSI MS-7695             | 1        | 0.51%   |
| MSI MS-7641             | 1        | 0.51%   |
| MSI MS-7592             | 1        | 0.51%   |
| MSI MS-7388             | 1        | 0.51%   |
| MSI MS-7199             | 1        | 0.51%   |
| MSI MS-6702             | 1        | 0.51%   |
| MSI MS-6470             | 1        | 0.51%   |
| MSI dx5150              | 1        | 0.51%   |
| Lenovo V530-15ICR       | 1        | 0.51%   |
| Lenovo H50-50           | 1        | 0.51%   |
| Lenovo 3000             | 1        | 0.51%   |
| Intel X99               | 1        | 0.51%   |
| Intel S3000AHLX         | 1        | 0.51%   |
| Intel DZ77GA-70K        | 1        | 0.51%   |
| Intel DH87RL            | 1        | 0.51%   |
| Intel DH77EB            | 1        | 0.51%   |
| Intel DG41KR            | 1        | 0.51%   |
| Intel D945GCCR          | 1        | 0.51%   |
| Intel D925XECV2         | 1        | 0.51%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 25       | 12.82%  |
| 2009 | 19       | 9.74%   |
| 2008 | 18       | 9.23%   |
| 2013 | 16       | 8.21%   |
| 2014 | 14       | 7.18%   |
| 2018 | 13       | 6.67%   |
| 2006 | 13       | 6.67%   |
| 2019 | 12       | 6.15%   |
| 2007 | 11       | 5.64%   |
| 2011 | 10       | 5.13%   |
| 2010 | 10       | 5.13%   |
| 2020 | 9        | 4.62%   |
| 2016 | 8        | 4.1%    |
| 2015 | 6        | 3.08%   |
| 2017 | 5        | 2.56%   |
| 2005 | 2        | 1.03%   |
| 2021 | 1        | 0.51%   |
| 2002 | 1        | 0.51%   |
| 2001 | 1        | 0.51%   |
| 2000 | 1        | 0.51%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 195      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 190      | 97.44%  |
| Enabled  | 5        | 2.56%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 195      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 3.01-4.0    | 55       | 26.83%  |
| 8.01-16.0   | 41       | 20%     |
| 4.01-8.0    | 38       | 18.54%  |
| 16.01-24.0  | 30       | 14.63%  |
| 32.01-64.0  | 12       | 5.85%   |
| 1.01-2.0    | 11       | 5.37%   |
| 2.01-3.0    | 6        | 2.93%   |
| 64.01-256.0 | 4        | 1.95%   |
| 0.51-1.0    | 4        | 1.95%   |
| 24.01-32.0  | 3        | 1.46%   |
| 0.01-0.5    | 1        | 0.49%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 84       | 36.84%  |
| 2.01-3.0   | 41       | 17.98%  |
| 0.51-1.0   | 29       | 12.72%  |
| 0.01-0.5   | 22       | 9.65%   |
| 3.01-4.0   | 21       | 9.21%   |
| 4.01-8.0   | 16       | 7.02%   |
| 8.01-16.0  | 13       | 5.7%    |
| 24.01-32.0 | 1        | 0.44%   |
| 16.01-24.0 | 1        | 0.44%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 87       | 40.28%  |
| 2      | 68       | 31.48%  |
| 3      | 30       | 13.89%  |
| 4      | 15       | 6.94%   |
| 5      | 11       | 5.09%   |
| 6      | 3        | 1.39%   |
| 7      | 1        | 0.46%   |
| 0      | 1        | 0.46%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 118      | 58.42%  |
| No        | 84       | 41.58%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 190      | 96.94%  |
| No        | 6        | 3.06%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 135      | 67.84%  |
| Yes       | 64       | 32.16%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 165      | 83.33%  |
| Yes       | 33       | 16.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Desktops | Percent |
|----------|----------|---------|
| Slovakia | 195      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Bratislava             | 60       | 27.65%  |
| Košice                | 17       | 7.83%   |
| Nitra                  | 9        | 4.15%   |
| Nové Zámky           | 7        | 3.23%   |
| Poprad                 | 6        | 2.76%   |
| Žilina                | 4        | 1.84%   |
| Zvolen                 | 3        | 1.38%   |
| Trnava                 | 3        | 1.38%   |
| Rimavská Sobota       | 3        | 1.38%   |
| Nitrianske Hrnciarovce | 3        | 1.38%   |
| Liptovský Mikuláš   | 3        | 1.38%   |
| Levice                 | 3        | 1.38%   |
| Banská Bystrica       | 3        | 1.38%   |
| Trenčín              | 2        | 0.92%   |
| Tornaľa               | 2        | 0.92%   |
| Soblahov               | 2        | 0.92%   |
| Skalica                | 2        | 0.92%   |
| Šaľa                 | 2        | 0.92%   |
| Ružomberok            | 2        | 0.92%   |
| Prešov                | 2        | 0.92%   |
| PetrЕѕalka           | 2        | 0.92%   |
| Miloslavov             | 2        | 0.92%   |
| Martin                 | 2        | 0.92%   |
| Malacky                | 2        | 0.92%   |
| Lučenec               | 2        | 0.92%   |
| Kostolne Kracany       | 2        | 0.92%   |
| Kmetovce               | 2        | 0.92%   |
| Kalna                  | 2        | 0.92%   |
| Cechynce               | 2        | 0.92%   |
| Bardejov               | 2        | 0.92%   |
| Zlate Moravce          | 1        | 0.46%   |
| Ziar nad Hronom        | 1        | 0.46%   |
| Zahradne               | 1        | 0.46%   |
| Vysoké Tatry          | 1        | 0.46%   |
| Vrable                 | 1        | 0.46%   |
| Velky Saris            | 1        | 0.46%   |
| Valaliky               | 1        | 0.46%   |
| Stropkov               | 1        | 0.46%   |
| Stefanov               | 1        | 0.46%   |
| Spissky Hrhov          | 1        | 0.46%   |
| Spišská Nová Ves    | 1        | 0.46%   |
| Spacince               | 1        | 0.46%   |
| Smizany                | 1        | 0.46%   |
| Senica                 | 1        | 0.46%   |
| Senec                  | 1        | 0.46%   |
| Samorin                | 1        | 0.46%   |
| Rožňava              | 1        | 0.46%   |
| Rajec                  | 1        | 0.46%   |
| Pribeta                | 1        | 0.46%   |
| Precin                 | 1        | 0.46%   |
| Praha                  | 1        | 0.46%   |
| Partizánske           | 1        | 0.46%   |
| Nová Dubnica          | 1        | 0.46%   |
| Nova Bana              | 1        | 0.46%   |
| Nizny Klatov           | 1        | 0.46%   |
| Neresnica              | 1        | 0.46%   |
| Nemecka                | 1        | 0.46%   |
| Myjava                 | 1        | 0.46%   |
| Modra                  | 1        | 0.46%   |
| Matejovce              | 1        | 0.46%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 83       | 159    | 23.71%  |
| Seagate                   | 75       | 120    | 21.43%  |
| Samsung Electronics       | 57       | 98     | 16.29%  |
| Hitachi                   | 22       | 32     | 6.29%   |
| Toshiba                   | 12       | 17     | 3.43%   |
| Patriot                   | 12       | 16     | 3.43%   |
| Kingston                  | 12       | 13     | 3.43%   |
| A-DATA Technology         | 12       | 21     | 3.43%   |
| Intel                     | 11       | 18     | 3.14%   |
| Maxtor                    | 7        | 12     | 2%      |
| SanDisk                   | 5        | 5      | 1.43%   |
| Crucial                   | 4        | 5      | 1.14%   |
| Unknown                   | 3        | 4      | 0.86%   |
| Phison                    | 3        | 3      | 0.86%   |
| KingDian                  | 3        | 3      | 0.86%   |
| HGST                      | 3        | 4      | 0.86%   |
| Realtek Semiconductor     | 2        | 2      | 0.57%   |
| OCZ                       | 2        | 2      | 0.57%   |
| IBM/Hitachi               | 2        | 2      | 0.57%   |
| Gigabyte Technology       | 2        | 2      | 0.57%   |
| Corsair                   | 2        | 3      | 0.57%   |
| China                     | 2        | 4      | 0.57%   |
| ULTIMATE                  | 1        | 2      | 0.29%   |
| PNY                       | 1        | 2      | 0.29%   |
| Micron/Crucial Technology | 1        | 1      | 0.29%   |
| Micron Technology         | 1        | 2      | 0.29%   |
| LITEONIT                  | 1        | 1      | 0.29%   |
| Intenso                   | 1        | 2      | 0.29%   |
| HS-SSD-E100               | 1        | 1      | 0.29%   |
| HGST HTS                  | 1        | 1      | 0.29%   |
| Hewlett-Packard           | 1        | 3      | 0.29%   |
| Fujitsu                   | 1        | 2      | 0.29%   |
| FORESEE                   | 1        | 2      | 0.29%   |
| Apacer                    | 1        | 1      | 0.29%   |
| AMD                       | 1        | 1      | 0.29%   |
| addlink                   | 1        | 1      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| WDC WD10EZEX-08WN4A0 1TB               | 6        | 1.45%   |
| Samsung SSD 860 EVO 250GB              | 6        | 1.45%   |
| Seagate ST3500418AS 500GB              | 5        | 1.21%   |
| Samsung SSD 850 EVO 250GB              | 5        | 1.21%   |
| Patriot Burst 120GB SSD                | 5        | 1.21%   |
| Toshiba DT01ACA100 1TB                 | 4        | 0.97%   |
| Seagate ST3320311CS 320GB              | 4        | 0.97%   |
| Seagate ST2000DM001-1CH164 2TB         | 4        | 0.97%   |
| WDC WD10EZEX-00KUWA0 1TB               | 3        | 0.72%   |
| Seagate ST500DM002-1BD142 500GB        | 3        | 0.72%   |
| Seagate ST3808110AS 80GB               | 3        | 0.72%   |
| Seagate ST2000DM008-2FR102 2TB         | 3        | 0.72%   |
| Seagate ST1000DM003-1SB102 1TB         | 3        | 0.72%   |
| Seagate ST1000DM003-1CH162 1TB         | 3        | 0.72%   |
| Kingston SV300S37A120G 120GB SSD       | 3        | 0.72%   |
| Hitachi HTS543232A7A384 320GB          | 3        | 0.72%   |
| Hitachi HDS722020ALA330 2TB            | 3        | 0.72%   |
| Hitachi HDP725050GLA360 500GB          | 3        | 0.72%   |
| A-DATA SU700 120GB SSD                 | 3        | 0.72%   |
| A-DATA SP600 32GB SSD                  | 3        | 0.72%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 2        | 0.48%   |
| WDC WD6400AAKS-22A7B0 640GB            | 2        | 0.48%   |
| WDC WD5000AAKX-75U6AA0 500GB           | 2        | 0.48%   |
| WDC WD5000AAKX-22ERMA0 500GB           | 2        | 0.48%   |
| WDC WD40EZRZ-00GXCB0 4TB               | 2        | 0.48%   |
| WDC WD400JB-00JJC0 40GB                | 2        | 0.48%   |
| WDC WD3200BB-00KEA0 320GB              | 2        | 0.48%   |
| WDC WD3200AAKS-00VYA0 320GB            | 2        | 0.48%   |
| WDC WD2502ABYS-01B7A0 256GB            | 2        | 0.48%   |
| WDC WD20EZRZ-00Z5HB0 2TB               | 2        | 0.48%   |
| WDC WD20EZRX-00D8PB0 2TB               | 2        | 0.48%   |
| WDC WD20EARX-00PASB0 2TB               | 2        | 0.48%   |
| WDC WD10EZRX-00D8PB0 1TB               | 2        | 0.48%   |
| WDC WD10EZEX-60WN4A0 1TB               | 2        | 0.48%   |
| WDC WD10EZEX-21M2NA0 1TB               | 2        | 0.48%   |
| WDC WD1002FBYS-18W8B1 1TB              | 2        | 0.48%   |
| Toshiba MK5065GSX 500GB                | 2        | 0.48%   |
| Seagate ST9500325AS 500GB              | 2        | 0.48%   |
| Seagate ST4000VN008-2DR166 4TB         | 2        | 0.48%   |
| Seagate ST380815AS 80GB                | 2        | 0.48%   |
| Seagate ST3500413AS 500GB              | 2        | 0.48%   |
| Seagate ST3320413CS 320GB              | 2        | 0.48%   |
| Seagate ST3250318AS 250GB              | 2        | 0.48%   |
| Seagate ST2000DL003-9VT166 2TB         | 2        | 0.48%   |
| SanDisk SDSSDA240G 240GB               | 2        | 0.48%   |
| SanDisk NVMe SSD Drive 1TB             | 2        | 0.48%   |
| Samsung SSD 970 PRO 512GB              | 2        | 0.48%   |
| Samsung SSD 970 EVO 500GB              | 2        | 0.48%   |
| Samsung SSD 970 EVO 1TB                | 2        | 0.48%   |
| Samsung SSD 860 EVO 500GB              | 2        | 0.48%   |
| Samsung SSD 850 EVO 500GB              | 2        | 0.48%   |
| Samsung SSD 840 EVO 250GB              | 2        | 0.48%   |
| Samsung SP2514N 250GB                  | 2        | 0.48%   |
| Samsung SM963 2.5" NVMe PCIe SSD 500GB | 2        | 0.48%   |
| Samsung NVMe SSD Drive 250GB           | 2        | 0.48%   |
| Samsung HD322HJ 320GB                  | 2        | 0.48%   |
| Samsung HD154UI 1TB                    | 2        | 0.48%   |
| Samsung HD103SJ 1TB                    | 2        | 0.48%   |
| Patriot Burst 240GB SSD                | 2        | 0.48%   |
| Maxtor 6E040L0 41GB                    | 2        | 0.48%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 82       | 154    | 36.77%  |
| Seagate             | 74       | 118    | 33.18%  |
| Hitachi             | 22       | 32     | 9.87%   |
| Samsung Electronics | 20       | 28     | 8.97%   |
| Toshiba             | 10       | 13     | 4.48%   |
| Maxtor              | 7        | 12     | 3.14%   |
| HGST                | 3        | 4      | 1.35%   |
| IBM/Hitachi         | 2        | 2      | 0.9%    |
| Unknown             | 1        | 1      | 0.45%   |
| Hewlett-Packard     | 1        | 3      | 0.45%   |
| Fujitsu             | 1        | 2      | 0.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 29       | 41     | 30.21%  |
| Patriot             | 11       | 15     | 11.46%  |
| A-DATA Technology   | 11       | 20     | 11.46%  |
| Intel               | 9        | 16     | 9.38%   |
| Kingston            | 8        | 9      | 8.33%   |
| WDC                 | 4        | 4      | 4.17%   |
| Crucial             | 4        | 5      | 4.17%   |
| SanDisk             | 3        | 3      | 3.13%   |
| OCZ                 | 2        | 2      | 2.08%   |
| Gigabyte Technology | 2        | 2      | 2.08%   |
| China               | 2        | 4      | 2.08%   |
| ULTIMATE            | 1        | 2      | 1.04%   |
| Toshiba             | 1        | 1      | 1.04%   |
| PNY                 | 1        | 2      | 1.04%   |
| Micron Technology   | 1        | 2      | 1.04%   |
| LITEONIT            | 1        | 1      | 1.04%   |
| KingDian            | 1        | 1      | 1.04%   |
| Intenso             | 1        | 2      | 1.04%   |
| FORESEE             | 1        | 2      | 1.04%   |
| Corsair             | 1        | 1      | 1.04%   |
| Apacer              | 1        | 1      | 1.04%   |
| AMD                 | 1        | 1      | 1.04%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 159      | 369    | 57.19%  |
| SSD     | 84       | 137    | 30.22%  |
| NVMe    | 29       | 54     | 10.43%  |
| Unknown | 6        | 7      | 2.16%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 186      | 505    | 83.78%  |
| NVMe | 29       | 54     | 13.06%  |
| SAS  | 7        | 8      | 3.15%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 162      | 326    | 61.36%  |
| 0.51-1.0   | 60       | 111    | 22.73%  |
| 1.01-2.0   | 26       | 38     | 9.85%   |
| 3.01-4.0   | 9        | 18     | 3.41%   |
| 2.01-3.0   | 6        | 12     | 2.27%   |
| 4.01-10.0  | 1        | 1      | 0.38%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 54       | 24.11%  |
| 251-500        | 40       | 17.86%  |
| 501-1000       | 28       | 12.5%   |
| 1-20           | 27       | 12.05%  |
| Unknown        | 20       | 8.93%   |
| 51-100         | 17       | 7.59%   |
| 1001-2000      | 16       | 7.14%   |
| 21-50          | 10       | 4.46%   |
| 2001-3000      | 7        | 3.13%   |
| More than 3000 | 5        | 2.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 87       | 38.5%   |
| 21-50          | 37       | 16.37%  |
| 101-250        | 25       | 11.06%  |
| Unknown        | 20       | 8.85%   |
| 251-500        | 16       | 7.08%   |
| 51-100         | 15       | 6.64%   |
| 501-1000       | 14       | 6.19%   |
| 1001-2000      | 8        | 3.54%   |
| More than 3000 | 2        | 0.88%   |
| 2001-3000      | 2        | 0.88%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST9500325AS 500GB             | 2        | 3      | 5.26%   |
| Seagate ST3320413CS 320GB             | 2        | 2      | 5.26%   |
| WDC WD800JD-60LSA0 80GB               | 1        | 1      | 2.63%   |
| WDC WD3200AAJS-56B4A0 320GB           | 1        | 2      | 2.63%   |
| WDC WD2500AAKX-753CA1 250GB           | 1        | 1      | 2.63%   |
| WDC WD20EZRZ-00Z5HB0 2TB              | 1        | 1      | 2.63%   |
| WDC WD20EURS-63S48Y0 2TB              | 1        | 1      | 2.63%   |
| WDC WD1600JS-61MHB1 160GB             | 1        | 1      | 2.63%   |
| WDC WD10EZEX-75WN4A0 1TB              | 1        | 2      | 2.63%   |
| WDC WD10EZEX-08WN4A0 1TB              | 1        | 1      | 2.63%   |
| WDC WD10EZEX-00RKKA0 1TB              | 1        | 1      | 2.63%   |
| WDC WD10EZEX-00KUWA0 1TB              | 1        | 1      | 2.63%   |
| WDC WD10EALX-009BA0 1TB               | 1        | 1      | 2.63%   |
| Toshiba MK7575GSX 752GB               | 1        | 2      | 2.63%   |
| Seagate ST980811AS 80GB               | 1        | 1      | 2.63%   |
| Seagate ST9250315AS 250GB             | 1        | 1      | 2.63%   |
| Seagate ST500DM002-1BD142 500GB       | 1        | 1      | 2.63%   |
| Seagate ST3500312CS 500GB             | 1        | 1      | 2.63%   |
| Seagate ST320LT007-9ZV142 320GB       | 1        | 1      | 2.63%   |
| Seagate ST31000322CS 1TB              | 1        | 2      | 2.63%   |
| Seagate ST250DM000-1BD141 250GB       | 1        | 1      | 2.63%   |
| Seagate ST2000VX000-1CU164 2TB        | 1        | 1      | 2.63%   |
| Seagate ST1000LM035-1RK172 1TB        | 1        | 1      | 2.63%   |
| Samsung Electronics SSD 970 EVO 500GB | 1        | 1      | 2.63%   |
| Samsung Electronics HD753LJ 752GB     | 1        | 4      | 2.63%   |
| Samsung Electronics HD320KJ 320GB     | 1        | 1      | 2.63%   |
| Samsung Electronics HD154UI 1TB       | 1        | 1      | 2.63%   |
| OCZ VERTEX4 256GB SSD                 | 1        | 1      | 2.63%   |
| Maxtor 6L200M0 208GB                  | 1        | 1      | 2.63%   |
| Maxtor 6L080P0 81GB                   | 1        | 1      | 2.63%   |
| Maxtor 6E040L0 41GB                   | 1        | 1      | 2.63%   |
| IBM/Hitachi IC25N030ATCS04-0 32GB     | 1        | 1      | 2.63%   |
| Hitachi HTS543232A7A384 320GB         | 1        | 1      | 2.63%   |
| Hitachi HDP725032GLA360 320GB         | 1        | 1      | 2.63%   |
| Fujitsu MHV2060BH PL 64GB             | 1        | 2      | 2.63%   |
| A-DATA Technology SU700 120GB SSD     | 1        | 1      | 2.63%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 13       | 15     | 35.14%  |
| WDC                 | 10       | 13     | 27.03%  |
| Samsung Electronics | 4        | 7      | 10.81%  |
| Maxtor              | 3        | 3      | 8.11%   |
| Hitachi             | 2        | 2      | 5.41%   |
| Toshiba             | 1        | 2      | 2.7%    |
| OCZ                 | 1        | 1      | 2.7%    |
| IBM/Hitachi         | 1        | 1      | 2.7%    |
| Fujitsu             | 1        | 2      | 2.7%    |
| A-DATA Technology   | 1        | 1      | 2.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 13       | 15     | 38.24%  |
| WDC                 | 10       | 13     | 29.41%  |
| Samsung Electronics | 3        | 6      | 8.82%   |
| Maxtor              | 3        | 3      | 8.82%   |
| Hitachi             | 2        | 2      | 5.88%   |
| Toshiba             | 1        | 2      | 2.94%   |
| IBM/Hitachi         | 1        | 1      | 2.94%   |
| Fujitsu             | 1        | 2      | 2.94%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 31       | 44     | 91.18%  |
| SSD  | 2        | 2      | 5.88%   |
| NVMe | 1        | 1      | 2.94%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Toshiba MK5065GSX 500GB           | 2        | 2      | 40%     |
| Seagate ST3500418AS 500GB         | 1        | 2      | 20%     |
| Seagate ST2000DM001-1CH164 2TB    | 1        | 1      | 20%     |
| Samsung Electronics HD321HJ 320GB | 1        | 2      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Toshiba             | 2        | 2      | 40%     |
| Seagate             | 2        | 3      | 40%     |
| Samsung Electronics | 1        | 2      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 111      | 283    | 47.64%  |
| Works    | 84       | 230    | 36.05%  |
| Malfunc  | 33       | 47     | 14.16%  |
| Failed   | 5        | 7      | 2.15%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 124      | 49.6%   |
| AMD                          | 55       | 22%     |
| Samsung Electronics          | 14       | 5.6%    |
| JMicron Technology           | 13       | 5.2%    |
| Nvidia                       | 11       | 4.4%    |
| Phison Electronics           | 5        | 2%      |
| Marvell Technology Group     | 5        | 2%      |
| ASMedia Technology           | 5        | 2%      |
| Kingston Technology Company  | 4        | 1.6%    |
| VIA Technologies             | 3        | 1.2%    |
| SanDisk                      | 3        | 1.2%    |
| Realtek Semiconductor        | 2        | 0.8%    |
| ULi Electronics              | 1        | 0.4%    |
| Toshiba America Info Systems | 1        | 0.4%    |
| Micron/Crucial Technology    | 1        | 0.4%    |
| LSI Logic / Symbios Logic    | 1        | 0.4%    |
| Hewlett-Packard              | 1        | 0.4%    |
| ADATA Technology             | 1        | 0.4%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 26       | 7.51%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 24       | 6.94%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 21       | 6.07%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 14       | 4.05%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 13       | 3.76%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 12       | 3.47%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 10       | 2.89%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 10       | 2.89%   |
| AMD 400 Series Chipset SATA Controller                                                  | 10       | 2.89%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 9        | 2.6%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 8        | 2.31%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 8        | 2.31%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 8        | 2.31%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 7        | 2.02%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 5        | 1.45%   |
| Nvidia MCP61 SATA Controller                                                            | 5        | 1.45%   |
| Nvidia MCP61 IDE                                                                        | 5        | 1.45%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 5        | 1.45%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 5        | 1.45%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5        | 1.45%   |
| Intel SATA Controller [RAID mode]                                                       | 4        | 1.16%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4        | 1.16%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 4        | 1.16%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 4        | 1.16%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 4        | 1.16%   |
| AMD 500 Series Chipset SATA Controller                                                  | 4        | 1.16%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 3        | 0.87%   |
| Phison E12 NVMe Controller                                                              | 3        | 0.87%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 3        | 0.87%   |
| Kingston Company A2000 NVMe SSD                                                         | 3        | 0.87%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3        | 0.87%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 3        | 0.87%   |
| AMD FCH SATA Controller D                                                               | 3        | 0.87%   |
| AMD FCH IDE Controller                                                                  | 3        | 0.87%   |
| VIA VIA VT6420 SATA RAID Controller                                                     | 2        | 0.58%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2        | 0.58%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 0.58%   |
| Realtek Realtek Non-Volatile memory controller                                          | 2        | 0.58%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2        | 0.58%   |
| Nvidia CK804 Serial ATA Controller                                                      | 2        | 0.58%   |
| Nvidia CK804 IDE                                                                        | 2        | 0.58%   |
| JMicron JMB368 IDE controller                                                           | 2        | 0.58%   |
| JMicron JMB361 AHCI/IDE                                                                 | 2        | 0.58%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2        | 0.58%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 0.58%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 2        | 0.58%   |
| Intel 82801IB (ICH9) 4 port SATA Controller [AHCI mode]                                 | 2        | 0.58%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                                | 2        | 0.58%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 0.58%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 0.58%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2        | 0.58%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2        | 0.58%   |
| AMD IXP SB4x0 Serial ATA Controller                                                     | 2        | 0.58%   |
| AMD IXP SB4x0 IDE Controller                                                            | 2        | 0.58%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 2        | 0.58%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2        | 0.58%   |
| ULi ULi M5288 SATA                                                                      | 1        | 0.29%   |
| ULi M5229 IDE                                                                           | 1        | 0.29%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 1        | 0.29%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 0.29%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 129      | 50.59%  |
| IDE  | 88       | 34.51%  |
| NVMe | 29       | 11.37%  |
| RAID | 8        | 3.14%   |
| SCSI | 1        | 0.39%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 124      | 63.59%  |
| AMD          | 70       | 35.9%   |
| CentaurHauls | 1        | 0.51%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz       | 5        | 2.54%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 5        | 2.54%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 4        | 2.03%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 3        | 1.52%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 3        | 1.52%   |
| Intel Core i3-9100 CPU @ 3.60GHz            | 3        | 1.52%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 3        | 1.52%   |
| Intel Core i3-4170 CPU @ 3.70GHz            | 3        | 1.52%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 3        | 1.52%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 3        | 1.52%   |
| Intel Pentium 4 CPU 3.00GHz                 | 2        | 1.02%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 2        | 1.02%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 2        | 1.02%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 2        | 1.02%   |
| Intel Core i7 CPU 920 @ 2.67GHz             | 2        | 1.02%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2        | 1.02%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 2        | 1.02%   |
| Intel Core i3-3225 CPU @ 3.30GHz            | 2        | 1.02%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 2        | 1.02%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 1.02%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 2        | 1.02%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 2        | 1.02%   |
| Intel Celeron CPU G1610 @ 2.60GHz           | 2        | 1.02%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 2        | 1.02%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 2        | 1.02%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 2        | 1.02%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2        | 1.02%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 2        | 1.02%   |
| AMD Phenom II X2 555 Processor              | 2        | 1.02%   |
| AMD Athlon Dual Core Processor 4850e        | 2        | 1.02%   |
| AMD Athlon 64 Processor 3200+               | 2        | 1.02%   |
| AMD A4-5300 APU with Radeon HD Graphics     | 2        | 1.02%   |
| Intel Xeon CPU X3220 @ 2.40GHz              | 1        | 0.51%   |
| Intel Xeon CPU E5645 @ 2.40GHz              | 1        | 0.51%   |
| Intel Xeon CPU E5335 @ 2.00GHz              | 1        | 0.51%   |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz         | 1        | 0.51%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz          | 1        | 0.51%   |
| Intel Xeon CPU E3-1230 v5 @ 3.40GHz         | 1        | 0.51%   |
| Intel Xeon CPU 3050 @ 2.13GHz               | 1        | 0.51%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 0.51%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 0.51%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1        | 0.51%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1        | 0.51%   |
| Intel Pentium D CPU 2.80GHz                 | 1        | 0.51%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1        | 0.51%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 1        | 0.51%   |
| Intel Pentium CPU G4600 @ 3.60GHz           | 1        | 0.51%   |
| Intel Pentium CPU G3258 @ 3.20GHz           | 1        | 0.51%   |
| Intel Pentium CPU G3250 @ 3.20GHz           | 1        | 0.51%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 1        | 0.51%   |
| Intel Pentium 4 CPU 3.40GHz                 | 1        | 0.51%   |
| Intel Genuine CPU 2140 @ 1.60GHz            | 1        | 0.51%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 0.51%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1        | 0.51%   |
| Intel Core i7-4770R CPU @ 3.20GHz           | 1        | 0.51%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 1        | 0.51%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 0.51%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 1        | 0.51%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 1        | 0.51%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1        | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 26       | 13.2%   |
| Intel Core i3           | 19       | 9.64%   |
| Intel Core i7           | 16       | 8.12%   |
| Intel Core 2 Duo        | 15       | 7.61%   |
| Intel Core 2 Quad       | 12       | 6.09%   |
| AMD Ryzen 5             | 11       | 5.58%   |
| Intel Celeron           | 8        | 4.06%   |
| Intel Xeon              | 7        | 3.55%   |
| AMD Athlon 64 X2        | 7        | 3.55%   |
| Intel Pentium           | 6        | 3.05%   |
| AMD Ryzen 9             | 6        | 3.05%   |
| AMD Ryzen 7             | 5        | 2.54%   |
| AMD Athlon II X2        | 5        | 2.54%   |
| AMD Sempron             | 4        | 2.03%   |
| AMD Athlon 64           | 4        | 2.03%   |
| Intel Pentium 4         | 3        | 1.52%   |
| Intel Core 2            | 3        | 1.52%   |
| Intel Atom              | 3        | 1.52%   |
| AMD Phenom              | 3        | 1.52%   |
| AMD FX                  | 3        | 1.52%   |
| AMD Athlon X4           | 3        | 1.52%   |
| AMD A10                 | 3        | 1.52%   |
| Intel Pentium Dual-Core | 2        | 1.02%   |
| Intel Pentium Dual      | 2        | 1.02%   |
| AMD Phenom II X4        | 2        | 1.02%   |
| AMD Phenom II X2        | 2        | 1.02%   |
| AMD Athlon Dual Core    | 2        | 1.02%   |
| AMD Athlon              | 2        | 1.02%   |
| AMD A4                  | 2        | 1.02%   |
| Other                   | 1        | 0.51%   |
| Intel Pentium D         | 1        | 0.51%   |
| Intel Genuine           | 1        | 0.51%   |
| CentaurHauls VIA Esther | 1        | 0.51%   |
| AMD Ryzen 5 PRO         | 1        | 0.51%   |
| AMD Ryzen 3             | 1        | 0.51%   |
| AMD Phenom II X6        | 1        | 0.51%   |
| AMD Athlon XP           | 1        | 0.51%   |
| AMD Athlon II X4        | 1        | 0.51%   |
| AMD A8                  | 1        | 0.51%   |
| AMD A6                  | 1        | 0.51%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 79       | 39.9%   |
| 2       | 76       | 38.38%  |
| 1       | 14       | 7.07%   |
| 6       | 12       | 6.06%   |
| 8       | 8        | 4.04%   |
| 12      | 5        | 2.53%   |
| Unknown | 2        | 1.01%   |
| 20      | 1        | 0.51%   |
| 16      | 1        | 0.51%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 194      | 99.49%  |
| 2      | 1        | 0.51%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 120      | 61.22%  |
| 2       | 74       | 37.76%  |
| Unknown | 2        | 1.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 191      | 97.95%  |
| 32-bit         | 3        | 1.54%   |
| 64-bit         | 1        | 0.51%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 42       | 20.59%  |
| 0x306c3    | 16       | 7.84%   |
| 0x1067a    | 16       | 7.84%   |
| 0x306a9    | 15       | 7.35%   |
| 0x6fb      | 11       | 5.39%   |
| 0x906e9    | 7        | 3.43%   |
| 0x506e3    | 6        | 2.94%   |
| 0x206a7    | 6        | 2.94%   |
| 0x010000c8 | 6        | 2.94%   |
| 0x6fd      | 5        | 2.45%   |
| 0x906eb    | 4        | 1.96%   |
| 0x6f2      | 4        | 1.96%   |
| 0x08701021 | 4        | 1.96%   |
| 0x06001119 | 4        | 1.96%   |
| 0x08108109 | 3        | 1.47%   |
| 0x0800820d | 3        | 1.47%   |
| 0x01000083 | 3        | 1.47%   |
| 0xf43      | 2        | 0.98%   |
| 0xa0653    | 2        | 0.98%   |
| 0x30661    | 2        | 0.98%   |
| 0x106a5    | 2        | 0.98%   |
| 0x0a201016 | 2        | 0.98%   |
| 0x0a201009 | 2        | 0.98%   |
| 0x08701013 | 2        | 0.98%   |
| 0x0700010f | 2        | 0.98%   |
| 0x06003106 | 2        | 0.98%   |
| 0x010000c7 | 2        | 0.98%   |
| 0xf64      | 1        | 0.49%   |
| 0xf4a      | 1        | 0.49%   |
| 0x906ec    | 1        | 0.49%   |
| 0x906ea    | 1        | 0.49%   |
| 0x6f6      | 1        | 0.49%   |
| 0x686      | 1        | 0.49%   |
| 0x406c3    | 1        | 0.49%   |
| 0x40661    | 1        | 0.49%   |
| 0x40651    | 1        | 0.49%   |
| 0x306f2    | 1        | 0.49%   |
| 0x206d7    | 1        | 0.49%   |
| 0x206c2    | 1        | 0.49%   |
| 0x20652    | 1        | 0.49%   |
| 0x106e5    | 1        | 0.49%   |
| 0x106c2    | 1        | 0.49%   |
| 0x10676    | 1        | 0.49%   |
| 0x0a50000c | 1        | 0.49%   |
| 0x0810100b | 1        | 0.49%   |
| 0x0800820b | 1        | 0.49%   |
| 0x08001138 | 1        | 0.49%   |
| 0x08001137 | 1        | 0.49%   |
| 0x06003104 | 1        | 0.49%   |
| 0x06000852 | 1        | 0.49%   |
| 0x0600063e | 1        | 0.49%   |
| 0x03000025 | 1        | 0.49%   |
| 0x010000db | 1        | 0.49%   |
| 0x010000bf | 1        | 0.49%   |
| 0x01000095 | 1        | 0.49%   |
| 0x01000086 | 1        | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Core        | 21       | 10.71%  |
| Haswell     | 19       | 9.69%   |
| Penryn      | 18       | 9.18%   |
| IvyBridge   | 17       | 8.67%   |
| KabyLake    | 16       | 8.16%   |
| K10         | 16       | 8.16%   |
| K8 Hammer   | 15       | 7.65%   |
| SandyBridge | 9        | 4.59%   |
| Zen+        | 8        | 4.08%   |
| Zen 2       | 7        | 3.57%   |
| Skylake     | 6        | 3.06%   |
| Piledriver  | 6        | 3.06%   |
| Zen 3       | 5        | 2.55%   |
| Zen         | 4        | 2.04%   |
| Steamroller | 4        | 2.04%   |
| NetBurst    | 4        | 2.04%   |
| Nehalem     | 4        | 2.04%   |
| Bonnell     | 3        | 1.53%   |
| Westmere    | 2        | 1.02%   |
| Jaguar      | 2        | 1.02%   |
| CometLake   | 2        | 1.02%   |
| Unknown     | 2        | 1.02%   |
| Silvermont  | 1        | 0.51%   |
| P6          | 1        | 0.51%   |
| K6          | 1        | 0.51%   |
| K10 Llano   | 1        | 0.51%   |
| Excavator   | 1        | 0.51%   |
| Bulldozer   | 1        | 0.51%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 77       | 36.84%  |
| AMD                        | 75       | 35.89%  |
| Intel                      | 54       | 25.84%  |
| VIA Technologies           | 1        | 0.48%   |
| S3 Graphics                | 1        | 0.48%   |
| Matrox Electronics Systems | 1        | 0.48%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 9        | 4.02%   |
| Nvidia GK208B [GeForce GT 710]                                                | 8        | 3.57%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                           | 6        | 2.68%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                     | 6        | 2.68%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 6        | 2.68%   |
| Nvidia GP108 [GeForce GT 1030]                                                | 5        | 2.23%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 5        | 2.23%   |
| AMD RS780L [Radeon 3000]                                                      | 5        | 2.23%   |
| Nvidia GT218 [GeForce 210]                                                    | 4        | 1.79%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                        | 4        | 1.79%   |
| Intel HD Graphics 530                                                         | 4        | 1.79%   |
| Intel 82945G/GZ Integrated Graphics Controller                                | 4        | 1.79%   |
| Nvidia GT216 [GeForce GT 220]                                                 | 3        | 1.34%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                            | 3        | 1.34%   |
| Nvidia GM206 [GeForce GTX 960]                                                | 3        | 1.34%   |
| Nvidia GF108 [GeForce GT 630]                                                 | 3        | 1.34%   |
| Nvidia G96C [GeForce 9500 GT]                                                 | 3        | 1.34%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 3        | 1.34%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 3        | 1.34%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]           | 3        | 1.34%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                         | 2        | 0.89%   |
| Nvidia GK208B [GeForce GT 730]                                                | 2        | 0.89%   |
| Nvidia GK208 [GeForce GT 630 Rev. 2]                                          | 2        | 0.89%   |
| Nvidia GF119 [GeForce GT 610]                                                 | 2        | 0.89%   |
| Nvidia GA102 [GeForce RTX 3090]                                               | 2        | 0.89%   |
| Nvidia G92 [GeForce 9800 GT]                                                  | 2        | 0.89%   |
| Intel HD Graphics 630                                                         | 2        | 0.89%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                      | 2        | 0.89%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                        | 2        | 0.89%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                      | 2        | 0.89%   |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                             | 2        | 0.89%   |
| AMD Trinity 2 [Radeon HD 7480D]                                               | 2        | 0.89%   |
| AMD RV635 [Radeon HD 3650/3750/4570/4580]                                     | 2        | 0.89%   |
| AMD RV516 [Radeon X1300/X1550 Series] (Secondary)                             | 2        | 0.89%   |
| AMD RV516 [Radeon X1300/X1550 Series]                                         | 2        | 0.89%   |
| AMD RV515 [Radeon X1300/X1550]                                                | 2        | 0.89%   |
| AMD RV515 [Radeon X1300/X1550 Series] (Secondary)                             | 2        | 0.89%   |
| AMD RS880 [Radeon HD 4200]                                                    | 2        | 0.89%   |
| AMD Redwood XT [Radeon HD 5670/5690/5730]                                     | 2        | 0.89%   |
| AMD Pitcairn XT [Radeon HD 7870 GHz Edition]                                  | 2        | 0.89%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]         | 2        | 0.89%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                       | 2        | 0.89%   |
| AMD Kaveri [Radeon R7 Graphics]                                               | 2        | 0.89%   |
| AMD Juniper XT [Radeon HD 5770]                                               | 2        | 0.89%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                              | 2        | 0.89%   |
| AMD Caicos [Radeon HD 6450A/7450A]                                            | 2        | 0.89%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                            | 2        | 0.89%   |
| VIA Technologies CN700/P4M800 Pro/P4M800 CE/VN800 Graphics [S3 UniChrome Pro] | 1        | 0.45%   |
| S3 Graphics VT8375 [ProSavage8 KM266/KL266]                                   | 1        | 0.45%   |
| Nvidia TU116 [GeForce GTX 1660]                                               | 1        | 0.45%   |
| Nvidia TU106 [GeForce RTX 2070]                                               | 1        | 0.45%   |
| Nvidia NV43 [GeForce 6600 GT]                                                 | 1        | 0.45%   |
| Nvidia GT215 [GeForce GT 320]                                                 | 1        | 0.45%   |
| Nvidia GT215 [GeForce GT 240]                                                 | 1        | 0.45%   |
| Nvidia GT215 [GeForce GT 220]                                                 | 1        | 0.45%   |
| Nvidia GP104 [GeForce GTX 1080]                                               | 1        | 0.45%   |
| Nvidia GP104 [GeForce GTX 1070]                                               | 1        | 0.45%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                            | 1        | 0.45%   |
| Nvidia GM206GL [Quadro M2000]                                                 | 1        | 0.45%   |
| Nvidia GM206 [GeForce GTX 950]                                                | 1        | 0.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 71       | 35.5%   |
| 1 x AMD         | 61       | 30.5%   |
| 1 x Intel       | 48       | 24%     |
| 2 x AMD         | 10       | 5%      |
| AMD + Nvidia    | 4        | 2%      |
| Intel + Nvidia  | 2        | 1%      |
| 3 x AMD         | 1        | 0.5%    |
| 1 x VIA         | 1        | 0.5%    |
| 1 x S3 Graphics | 1        | 0.5%    |
| 1 x Matrox      | 1        | 0.5%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 158      | 76.7%   |
| Proprietary | 35       | 16.99%  |
| Unknown     | 13       | 6.31%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 72       | 33.96%  |
| 0.01-0.5   | 46       | 21.7%   |
| 0.51-1.0   | 35       | 16.51%  |
| 1.01-2.0   | 26       | 12.26%  |
| 3.01-4.0   | 13       | 6.13%   |
| 7.01-8.0   | 8        | 3.77%   |
| 5.01-6.0   | 7        | 3.3%    |
| 2.01-3.0   | 2        | 0.94%   |
| 16.01-24.0 | 2        | 0.94%   |
| 8.01-16.0  | 1        | 0.47%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 33       | 15.87%  |
| Goldstar             | 21       | 10.1%   |
| BenQ                 | 21       | 10.1%   |
| Philips              | 19       | 9.13%   |
| Hewlett-Packard      | 16       | 7.69%   |
| Ancor Communications | 15       | 7.21%   |
| Dell                 | 13       | 6.25%   |
| NEC Computers        | 8        | 3.85%   |
| AOC                  | 8        | 3.85%   |
| Acer                 | 8        | 3.85%   |
| Iiyama               | 5        | 2.4%    |
| Fujitsu Siemens      | 5        | 2.4%    |
| LG Electronics       | 4        | 1.92%   |
| Unknown              | 3        | 1.44%   |
| Eizo                 | 3        | 1.44%   |
| Sony                 | 2        | 0.96%   |
| RTD                  | 2        | 0.96%   |
| FUS                  | 2        | 0.96%   |
| CVT                  | 2        | 0.96%   |
| Valve                | 1        | 0.48%   |
| S2-Tek               | 1        | 0.48%   |
| PTC                  | 1        | 0.48%   |
| Pioneer              | 1        | 0.48%   |
| Onkyo                | 1        | 0.48%   |
| MSI                  | 1        | 0.48%   |
| Lite-On              | 1        | 0.48%   |
| Lenovo               | 1        | 0.48%   |
| Jean                 | 1        | 0.48%   |
| InfoVision           | 1        | 0.48%   |
| IBM                  | 1        | 0.48%   |
| FZC                  | 1        | 0.48%   |
| Elo Touch            | 1        | 0.48%   |
| DENON                | 1        | 0.48%   |
| D&T                  | 1        | 0.48%   |
| ASUSTek Computer     | 1        | 0.48%   |
| Arnos Instruments    | 1        | 0.48%   |
| ADV                  | 1        | 0.48%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch    | 6        | 2.67%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch       | 3        | 1.33%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                 | 3        | 1.33%   |
| NEC Computers LCD19WV NEC671C 1440x900 410x256mm 19.0-inch              | 3        | 1.33%   |
| Unknown 1780 07E7 1280x1024 337x270mm 17.0-inch                         | 2        | 0.89%   |
| Samsung Electronics SyncMaster SAM05CC 1920x1080 530x300mm 24.0-inch    | 2        | 0.89%   |
| Samsung Electronics SyncMaster SAM0420 1680x1050 474x296mm 22.0-inch    | 2        | 0.89%   |
| Samsung Electronics S27D390 SAM0B67 1920x1080 600x340mm 27.2-inch       | 2        | 0.89%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 2        | 0.89%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 480x270mm 21.7-inch   | 2        | 0.89%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 890x500mm 40.2-inch   | 2        | 0.89%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 2        | 0.89%   |
| RTD LR762 RTD2023 1280x1024 307x230mm 15.1-inch                         | 2        | 0.89%   |
| Philips 196VL PHLC07F 1366x768 409x230mm 18.5-inch                      | 2        | 0.89%   |
| Hewlett-Packard LA1951 HWP285A 1280x1024 380x300mm 19.1-inch            | 2        | 0.89%   |
| Dell U2515H DELD06F 2560x1440 553x311mm 25.0-inch                       | 2        | 0.89%   |
| Dell 2209WA DELF011 1680x1050 474x296mm 22.0-inch                       | 2        | 0.89%   |
| CVT CVTE TV CVT0003 1920x1080 575x323mm 26.0-inch                       | 2        | 0.89%   |
| BenQ GW2470 BNQ78E4 1920x1080 527x296mm 23.8-inch                       | 2        | 0.89%   |
| Ancor Communications VE228 ACI22FA 1920x1080 480x270mm 21.7-inch        | 2        | 0.89%   |
| Ancor Communications ASUS VW193D ACI19D5 1440x900 410x260mm 19.1-inch   | 2        | 0.89%   |
| Ancor Communications ASUS MK241 ACI24A1 1920x1200 550x350mm 25.7-inch   | 2        | 0.89%   |
| Valve Index HMD VLV91A8                                                 | 1        | 0.44%   |
| Unknown LCD Monitor BenQG2222HDL 1920x1080                              | 1        | 0.44%   |
| Sony TV *00 SNY8404 3840x2160 1218x685mm 55.0-inch                      | 1        | 0.44%   |
| Sony TV *00 SNY4904 3840x2160 1600x900mm 72.3-inch                      | 1        | 0.44%   |
| Samsung Electronics SyncMaster SAM0589 1920x1080 521x293mm 23.5-inch    | 1        | 0.44%   |
| Samsung Electronics SyncMaster SAM049C 1920x1080 477x268mm 21.5-inch    | 1        | 0.44%   |
| Samsung Electronics SMS27A550H SAM07CC 1920x1080 598x336mm 27.0-inch    | 1        | 0.44%   |
| Samsung Electronics SMS24A850 SAM082F 1920x1200 518x324mm 24.1-inch     | 1        | 0.44%   |
| Samsung Electronics SMB2430L SAM0645 1920x1080 520x290mm 23.4-inch      | 1        | 0.44%   |
| Samsung Electronics SA300/SA350 SAM0795 1920x1080 521x293mm 23.5-inch   | 1        | 0.44%   |
| Samsung Electronics S24C300 SAM0A24 1920x1080 531x299mm 24.0-inch       | 1        | 0.44%   |
| Samsung Electronics S24B300 SAM08CC 1920x1080 521x293mm 23.5-inch       | 1        | 0.44%   |
| Samsung Electronics S19B150 SAM08A2 1366x768 410x230mm 18.5-inch        | 1        | 0.44%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1080                    | 1        | 0.44%   |
| Samsung Electronics LCD Monitor SAM0BB4 3840x2160 1872x1053mm 84.6-inch | 1        | 0.44%   |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 885x498mm 40.0-inch   | 1        | 0.44%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 890x500mm 40.2-inch   | 1        | 0.44%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 410x230mm 18.5-inch    | 1        | 0.44%   |
| Samsung Electronics LCD Monitor SAM0669 1920x1080                       | 1        | 0.44%   |
| Samsung Electronics C27JG5x SAM0FDB 2560x1440 597x336mm 27.0-inch       | 1        | 0.44%   |
| S2-Tek TV STK531A 1920x1080 930x530mm 42.1-inch                         | 1        | 0.44%   |
| PTC 4K Grabber PTCC101 3840x2160 621x341mm 27.9-inch                    | 1        | 0.44%   |
| Pioneer VSX-330 PIO1027 2560x1440 597x336mm 27.0-inch                   | 1        | 0.44%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                 | 1        | 0.44%   |
| Philips PHL 240V5A PHLC10C 1920x1080 527x296mm 23.8-inch                | 1        | 0.44%   |
| Philips LCD Monitor PHL08B0 1920x1080 530x300mm 24.0-inch               | 1        | 0.44%   |
| Philips 26PFL3404 EU PHLD05F 1360x768 575x323mm 26.0-inch               | 1        | 0.44%   |
| Philips 247ELPH PHLC086 1920x1080 521x293mm 23.5-inch                   | 1        | 0.44%   |
| Philips 241BLPY PHL08B3 1920x1080 531x299mm 24.0-inch                   | 1        | 0.44%   |
| Philips 226VL PHLC081 1920x1080 480x268mm 21.6-inch                     | 1        | 0.44%   |
| Philips 221T PHLC041 1920x1080 476x268mm 21.5-inch                      | 1        | 0.44%   |
| Philips 200XW PHL084D 1680x1050 433x271mm 20.1-inch                     | 1        | 0.44%   |
| Philips 200V4 PHLC0BF 1600x900 432x240mm 19.5-inch                      | 1        | 0.44%   |
| Philips 192E PHLC04D 1366x768 410x230mm 18.5-inch                       | 1        | 0.44%   |
| Philips 190S PHL086B 1280x1024 376x301mm 19.0-inch                      | 1        | 0.44%   |
| Philips 170S PHL082B 1280x1024 338x270mm 17.0-inch                      | 1        | 0.44%   |
| Philips 107B (17 ZOLL/CM6800) PHL6800 1280x1024 300x225mm 14.8-inch     | 1        | 0.44%   |
| Onkyo TX-NR616 ONK0C61 1920x1080 698x392mm 31.5-inch                    | 1        | 0.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 87       | 42.23%  |
| 1280x1024 (SXGA)   | 29       | 14.08%  |
| 1680x1050 (WSXGA+) | 16       | 7.77%   |
| 1440x900 (WXGA+)   | 13       | 6.31%   |
| 3840x2160 (4K)     | 11       | 5.34%   |
| 1920x1200 (WUXGA)  | 11       | 5.34%   |
| 2560x1440 (QHD)    | 10       | 4.85%   |
| 1366x768 (WXGA)    | 9        | 4.37%   |
| 1600x1200          | 6        | 2.91%   |
| 1600x900 (HD+)     | 4        | 1.94%   |
| 3440x1440          | 3        | 1.46%   |
| 1360x768           | 2        | 0.97%   |
| 1024x768 (XGA)     | 2        | 0.97%   |
| 1280x960           | 1        | 0.49%   |
| 1280x720 (HD)      | 1        | 0.49%   |
| Unknown            | 1        | 0.49%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 30       | 14.08%  |
| 24      | 26       | 12.21%  |
| 21      | 24       | 11.27%  |
| 19      | 24       | 11.27%  |
| 27      | 20       | 9.39%   |
| 17      | 17       | 7.98%   |
| Unknown | 17       | 7.98%   |
| 22      | 9        | 4.23%   |
| 25      | 7        | 3.29%   |
| 18      | 7        | 3.29%   |
| 20      | 6        | 2.82%   |
| 26      | 4        | 1.88%   |
| 84      | 2        | 0.94%   |
| 72      | 2        | 0.94%   |
| 54      | 2        | 0.94%   |
| 48      | 2        | 0.94%   |
| 46      | 2        | 0.94%   |
| 34      | 2        | 0.94%   |
| 31      | 2        | 0.94%   |
| 15      | 2        | 0.94%   |
| 65      | 1        | 0.47%   |
| 42      | 1        | 0.47%   |
| 35      | 1        | 0.47%   |
| 32      | 1        | 0.47%   |
| 14      | 1        | 0.47%   |
| 11      | 1        | 0.47%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 75       | 36.76%  |
| 401-500     | 61       | 29.9%   |
| 301-350     | 19       | 9.31%   |
| Unknown     | 17       | 8.33%   |
| 351-400     | 11       | 5.39%   |
| 1001-1500   | 7        | 3.43%   |
| 1501-2000   | 4        | 1.96%   |
| 701-800     | 3        | 1.47%   |
| 601-700     | 3        | 1.47%   |
| 201-300     | 2        | 0.98%   |
| 801-900     | 1        | 0.49%   |
| 901-1000    | 1        | 0.49%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 105      | 52.24%  |
| 16/10   | 37       | 18.41%  |
| 5/4     | 28       | 13.93%  |
| Unknown | 14       | 6.97%   |
| 4/3     | 11       | 5.47%   |
| 3/2     | 3        | 1.49%   |
| 21/9    | 3        | 1.49%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 72       | 34.29%  |
| 151-200        | 38       | 18.1%   |
| 141-150        | 23       | 10.95%  |
| 301-350        | 20       | 9.52%   |
| 251-300        | 18       | 8.57%   |
| Unknown        | 17       | 8.1%    |
| More than 1000 | 9        | 4.29%   |
| 351-500        | 6        | 2.86%   |
| 501-1000       | 3        | 1.43%   |
| 101-110        | 2        | 0.95%   |
| 51-60          | 1        | 0.48%   |
| 111-120        | 1        | 0.48%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 135      | 68.53%  |
| 101-120 | 31       | 15.74%  |
| Unknown | 17       | 8.63%   |
| 1-50    | 8        | 4.06%   |
| 121-160 | 4        | 2.03%   |
| 161-240 | 2        | 1.02%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 162      | 79.8%   |
| 2     | 30       | 14.78%  |
| 0     | 8        | 3.94%   |
| 3     | 3        | 1.48%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 112      | 43.92%  |
| Intel                                  | 58       | 22.75%  |
| Qualcomm Atheros                       | 15       | 5.88%   |
| TP-Link                                | 10       | 3.92%   |
| Ralink Technology                      | 9        | 3.53%   |
| Qualcomm Atheros Communications        | 9        | 3.53%   |
| Nvidia                                 | 9        | 3.53%   |
| Broadcom                               | 8        | 3.14%   |
| Marvell Technology Group               | 4        | 1.57%   |
| Broadcom Limited                       | 4        | 1.57%   |
| Edimax Technology                      | 2        | 0.78%   |
| ASUSTek Computer                       | 2        | 0.78%   |
| WiseGroup                              | 1        | 0.39%   |
| VIA Technologies                       | 1        | 0.39%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.39%   |
| Samsung Electronics                    | 1        | 0.39%   |
| Pulse-Eight                            | 1        | 0.39%   |
| Prestigio                              | 1        | 0.39%   |
| National Semiconductor                 | 1        | 0.39%   |
| Microsoft                              | 1        | 0.39%   |
| Micro Star International               | 1        | 0.39%   |
| Huawei Technologies                    | 1        | 0.39%   |
| D-Link                                 | 1        | 0.39%   |
| ASIX Electronics                       | 1        | 0.39%   |
| Accton Technology                      | 1        | 0.39%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 91       | 32.38%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 10       | 3.56%   |
| Intel I211 Gigabit Network Connection                             | 10       | 3.56%   |
| Qualcomm Atheros AR9271 802.11n                                   | 9        | 3.2%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8        | 2.85%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 7        | 2.49%   |
| Intel Ethernet Connection (2) I219-V                              | 7        | 2.49%   |
| Intel Wi-Fi 6 AX200                                               | 5        | 1.78%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 4        | 1.42%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4        | 1.42%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 4        | 1.42%   |
| Nvidia MCP61 Ethernet                                             | 4        | 1.42%   |
| Intel 82579V Gigabit Network Connection                           | 4        | 1.42%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 1.42%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 1.07%   |
| Ralink MT7601U Wireless Adapter                                   | 3        | 1.07%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 3        | 1.07%   |
| Intel Wireless 8260                                               | 3        | 1.07%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 1.07%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                             | 2        | 0.71%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2        | 0.71%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 2        | 0.71%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2        | 0.71%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 0.71%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2        | 0.71%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 0.71%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2        | 0.71%   |
| Intel Ethernet Controller I225-V                                  | 2        | 0.71%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 0.71%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2        | 0.71%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 0.71%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 0.71%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2        | 0.71%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 2        | 0.71%   |
| Broadcom Limited NetXtreme BCM5754 Gigabit Ethernet PCI Express   | 2        | 0.71%   |
| ASUS USB-N14 802.11b/g/n (2x2) Wireless Adapter [Ralink RT5372]   | 2        | 0.71%   |
| WiseGroup Deluxe Dance Mat                                        | 1        | 0.36%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.36%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1        | 0.36%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                         | 1        | 0.36%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1        | 0.36%   |
| TP-Link 802.11ac NIC                                              | 1        | 0.36%   |
| Sony Ericsson Mobile AB E5823                                     | 1        | 0.36%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.36%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1        | 0.36%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1        | 0.36%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1        | 0.36%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 1        | 0.36%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                            | 1        | 0.36%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter          | 1        | 0.36%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.36%   |
| Ralink RT5370 Wireless Adapter                                    | 1        | 0.36%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                 | 1        | 0.36%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.36%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.36%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 0.36%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 1        | 0.36%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.36%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.36%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.36%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 14       | 21.21%  |
| Realtek Semiconductor           | 12       | 18.18%  |
| TP-Link                         | 10       | 15.15%  |
| Ralink Technology               | 9        | 13.64%  |
| Qualcomm Atheros Communications | 9        | 13.64%  |
| Qualcomm Atheros                | 2        | 3.03%   |
| Edimax Technology               | 2        | 3.03%   |
| Broadcom                        | 2        | 3.03%   |
| ASUSTek Computer                | 2        | 3.03%   |
| Microsoft                       | 1        | 1.52%   |
| Micro Star International        | 1        | 1.52%   |
| D-Link                          | 1        | 1.52%   |
| Accton Technology               | 1        | 1.52%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR9271 802.11n                                               | 9        | 13.64%  |
| Intel Wi-Fi 6 AX200                                                           | 5        | 7.58%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 4        | 6.06%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 4        | 6.06%   |
| Ralink MT7601U Wireless Adapter                                               | 3        | 4.55%   |
| Intel Wireless 8260                                                           | 3        | 4.55%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                         | 2        | 3.03%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 2        | 3.03%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 2        | 3.03%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 2        | 3.03%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 2        | 3.03%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 2        | 3.03%   |
| ASUS USB-N14 802.11b/g/n (2x2) Wireless Adapter [Ralink RT5372]               | 2        | 3.03%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 1        | 1.52%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                                     | 1        | 1.52%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 1        | 1.52%   |
| TP-Link 802.11ac NIC                                                          | 1        | 1.52%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1        | 1.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 1        | 1.52%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 1        | 1.52%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 1        | 1.52%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                        | 1        | 1.52%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                      | 1        | 1.52%   |
| Ralink RT5370 Wireless Adapter                                                | 1        | 1.52%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                             | 1        | 1.52%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 1        | 1.52%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1        | 1.52%   |
| Microsoft Xbox 360 Wireless Adapter                                           | 1        | 1.52%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070]    | 1        | 1.52%   |
| Intel Wireless-AC 9260                                                        | 1        | 1.52%   |
| Intel Centrino Advanced-N 6235                                                | 1        | 1.52%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT3070]                      | 1        | 1.52%   |
| Edimax 802.11ac WLAN Adapter                                                  | 1        | 1.52%   |
| D-Link DWA-125 Wireless N 150 Adapter(rev.A3) [Ralink RT5370]                 | 1        | 1.52%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 1        | 1.52%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller           | 1        | 1.52%   |
| Accton SMCWUSB-G 802.11bg                                                     | 1        | 1.52%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 110      | 53.92%  |
| Intel                                  | 51       | 25%     |
| Qualcomm Atheros                       | 13       | 6.37%   |
| Nvidia                                 | 9        | 4.41%   |
| Broadcom                               | 6        | 2.94%   |
| Marvell Technology Group               | 4        | 1.96%   |
| Broadcom Limited                       | 4        | 1.96%   |
| VIA Technologies                       | 1        | 0.49%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.49%   |
| Samsung Electronics                    | 1        | 0.49%   |
| Prestigio                              | 1        | 0.49%   |
| National Semiconductor                 | 1        | 0.49%   |
| Huawei Technologies                    | 1        | 0.49%   |
| ASIX Electronics                       | 1        | 0.49%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 91       | 42.72%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 10       | 4.69%   |
| Intel I211 Gigabit Network Connection                             | 10       | 4.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8        | 3.76%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 7        | 3.29%   |
| Intel Ethernet Connection (2) I219-V                              | 7        | 3.29%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4        | 1.88%   |
| Nvidia MCP61 Ethernet                                             | 4        | 1.88%   |
| Intel 82579V Gigabit Network Connection                           | 4        | 1.88%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 1.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 1.41%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 3        | 1.41%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 1.41%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 0.94%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2        | 0.94%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 0.94%   |
| Intel Ethernet Controller I225-V                                  | 2        | 0.94%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 0.94%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 0.94%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 0.94%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2        | 0.94%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 2        | 0.94%   |
| Broadcom Limited NetXtreme BCM5754 Gigabit Ethernet PCI Express   | 2        | 0.94%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.47%   |
| Sony Ericsson Mobile AB E5823                                     | 1        | 0.47%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.47%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.47%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.47%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.47%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 0.47%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.47%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.47%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.47%   |
| Prestigio PSP5453DUO                                              | 1        | 0.47%   |
| Nvidia MCP77 Ethernet                                             | 1        | 0.47%   |
| Nvidia MCP67 Ethernet                                             | 1        | 0.47%   |
| Nvidia MCP65 Ethernet                                             | 1        | 0.47%   |
| Nvidia MCP55 Ethernet                                             | 1        | 0.47%   |
| Nvidia CK804 Ethernet Controller                                  | 1        | 0.47%   |
| National DP83815 (MacPhyter) Ethernet Controller                  | 1        | 0.47%   |
| Marvell Group 88E8050 PCI-E ASF Gigabit Ethernet Controller       | 1        | 0.47%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.47%   |
| Intel PRO/100 VE Network Connection                               | 1        | 0.47%   |
| Intel Ethernet Connection I217-V                                  | 1        | 0.47%   |
| Intel Ethernet Connection (5) I219-V                              | 1        | 0.47%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 0.47%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 0.47%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1        | 0.47%   |
| Intel 82573E Gigabit Ethernet Controller (Copper)                 | 1        | 0.47%   |
| Intel 82566DM Gigabit Network Connection                          | 1        | 0.47%   |
| Intel 82562V-2 10/100 Network Connection                          | 1        | 0.47%   |
| Intel 82541GI Gigabit Ethernet Controller                         | 1        | 0.47%   |
| Huawei COL-L29                                                    | 1        | 0.47%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 1        | 0.47%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1        | 0.47%   |
| Broadcom Limited NetXtreme II BCM5708 Gigabit Ethernet            | 1        | 0.47%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express   | 1        | 0.47%   |
| ASIX AX88772                                                      | 1        | 0.47%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 190      | 74.22%  |
| WiFi     | 64       | 25%     |
| Modem    | 1        | 0.39%   |
| Unknown  | 1        | 0.39%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 158      | 80.2%   |
| WiFi     | 39       | 19.8%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 152      | 76.77%  |
| 2     | 34       | 17.17%  |
| 3     | 6        | 3.03%   |
| 0     | 5        | 2.53%   |
| 4     | 1        | 0.51%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 190      | 96.94%  |
| Yes  | 6        | 3.06%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 14       | 42.42%  |
| Cambridge Silicon Radio         | 6        | 18.18%  |
| Realtek Semiconductor           | 2        | 6.06%   |
| Micro Star International        | 2        | 6.06%   |
| HTC (High Tech Computer)        | 2        | 6.06%   |
| ASUSTek Computer                | 2        | 6.06%   |
| Qualcomm Atheros Communications | 1        | 3.03%   |
| Integrated System Solution      | 1        | 3.03%   |
| IMC Networks                    | 1        | 3.03%   |
| Broadcom                        | 1        | 3.03%   |
| Belkin Components               | 1        | 3.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 6        | 18.18%  |
| Intel AX200 Bluetooth                                                | 5        | 15.15%  |
| Intel Bluetooth wireless interface                                   | 3        | 9.09%   |
| Micro Star International Bluetooth Device                            | 2        | 6.06%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 2        | 6.06%   |
| Intel AX210 Bluetooth                                                | 2        | 6.06%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 2        | 6.06%   |
| ASUS Bluetooth Radio                                                 | 2        | 6.06%   |
| Realtek RTL8723B Bluetooth                                           | 1        | 3.03%   |
| Realtek Bluetooth Radio                                              | 1        | 3.03%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 1        | 3.03%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 1        | 3.03%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 1        | 3.03%   |
| Integrated System Solution Bluetooth Device                          | 1        | 3.03%   |
| IMC Networks Bluetooth Radio                                         | 1        | 3.03%   |
| Broadcom BCM2045 Bluetooth                                           | 1        | 3.03%   |
| Belkin Components Bluetooth Mini Dongle                              | 1        | 3.03%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 118      | 38.56%  |
| AMD                    | 79       | 25.82%  |
| Nvidia                 | 73       | 23.86%  |
| C-Media Electronics    | 9        | 2.94%   |
| Creative Labs          | 6        | 1.96%   |
| VIA Technologies       | 4        | 1.31%   |
| Creative Technology    | 4        | 1.31%   |
| Blue Microphones       | 2        | 0.65%   |
| ASUSTek Computer       | 2        | 0.65%   |
| Valve Software         | 1        | 0.33%   |
| ULi Electronics        | 1        | 0.33%   |
| SteelSeries ApS        | 1        | 0.33%   |
| Logitech               | 1        | 0.33%   |
| Lenovo                 | 1        | 0.33%   |
| GN Netcom              | 1        | 0.33%   |
| Fortemedia             | 1        | 0.33%   |
| Barco Display Systems  | 1        | 0.33%   |
| AKAI Professional M.I. | 1        | 0.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 22       | 6.2%    |
| AMD SBx00 Azalia (Intel HDA)                                                      | 18       | 5.07%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 14       | 3.94%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 14       | 3.94%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 12       | 3.38%   |
| AMD FCH Azalia Controller                                                         | 12       | 3.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 10       | 2.82%   |
| AMD Starship/Matisse HD Audio Controller                                          | 10       | 2.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 9        | 2.54%   |
| Intel 200 Series PCH HD Audio                                                     | 9        | 2.54%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 8        | 2.25%   |
| Nvidia High Definition Audio Controller                                           | 7        | 1.97%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 7        | 1.97%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 7        | 1.97%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 7        | 1.97%   |
| Nvidia GP106 High Definition Audio Controller                                     | 6        | 1.69%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 6        | 1.69%   |
| Nvidia MCP61 High Definition Audio                                                | 5        | 1.41%   |
| Nvidia GP108 High Definition Audio Controller                                     | 5        | 1.41%   |
| Nvidia GF108 High Definition Audio Controller                                     | 5        | 1.41%   |
| Intel Cannon Lake PCH cAVS                                                        | 5        | 1.41%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 5        | 1.41%   |
| Nvidia GM206 High Definition Audio Controller                                     | 4        | 1.13%   |
| Nvidia GK107 HDMI Audio Controller                                                | 4        | 1.13%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 4        | 1.13%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                    | 4        | 1.13%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 4        | 1.13%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                    | 4        | 1.13%   |
| AMD Family 17h/19h HD Audio Controller                                            | 4        | 1.13%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 4        | 1.13%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                         | 3        | 0.85%   |
| Nvidia GT216 HDMI Audio Controller                                                | 3        | 0.85%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 3        | 0.85%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 3        | 0.85%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]         | 3        | 0.85%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                     | 3        | 0.85%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 3        | 0.85%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 3        | 0.85%   |
| Nvidia TU104 HD Audio Controller                                                  | 2        | 0.56%   |
| Nvidia GP104 High Definition Audio Controller                                     | 2        | 0.56%   |
| Nvidia GK106 HDMI Audio Controller                                                | 2        | 0.56%   |
| Nvidia GF119 HDMI Audio Controller                                                | 2        | 0.56%   |
| Nvidia GA102 High Definition Audio Controller                                     | 2        | 0.56%   |
| Nvidia CK804 AC'97 Audio Controller                                               | 2        | 0.56%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 2        | 0.56%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                     | 2        | 0.56%   |
| C-Media Electronics Blue Snowball                                                 | 2        | 0.56%   |
| Blue Microphones Yeti Stereo Microphone                                           | 2        | 0.56%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                        | 2        | 0.56%   |
| AMD Tahiti HDMI Audio [Radeon HD 7870 XT / 7950/7970]                             | 2        | 0.56%   |
| AMD RV770 HDMI Audio [Radeon HD 4850/4870]                                        | 2        | 0.56%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 2        | 0.56%   |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                                   | 2        | 0.56%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 2        | 0.56%   |
| AMD Navi 10 HDMI Audio                                                            | 2        | 0.56%   |
| AMD Kaveri HDMI/DP Audio Controller                                               | 2        | 0.56%   |
| AMD Kabini HDMI/DP Audio                                                          | 2        | 0.56%   |
| AMD IXP SB400 AC'97 Audio Controller                                              | 2        | 0.56%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 2        | 0.56%   |
| VIA Technologies ICE1712 [Envy24] PCI Multi-Channel I/O Controller                | 1        | 0.28%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 33       | 28.45%  |
| Kingston            | 32       | 27.59%  |
| Crucial             | 10       | 8.62%   |
| Corsair             | 8        | 6.9%    |
| Samsung Electronics | 7        | 6.03%   |
| Patriot             | 5        | 4.31%   |
| G.Skill             | 5        | 4.31%   |
| SK hynix            | 4        | 3.45%   |
| Elpida              | 4        | 3.45%   |
| Micron Technology   | 3        | 2.59%   |
| Unknown (8AC8)      | 1        | 0.86%   |
| Transcend           | 1        | 0.86%   |
| Hewlett-Packard     | 1        | 0.86%   |
| A-DATA Technology   | 1        | 0.86%   |
| Unknown             | 1        | 0.86%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s             | 4        | 2.88%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s     | 3        | 2.16%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s            | 2        | 1.44%   |
| Unknown RAM Module 2048MB DIMM DDR2 333MT/s             | 2        | 1.44%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                  | 2        | 1.44%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                 | 2        | 1.44%   |
| Unknown RAM Module 1024MB DIMM DDR 333MT/s              | 2        | 1.44%   |
| Samsung RAM M378B5773DH0-CH9 2048MB DIMM DDR3 1333MT/s  | 2        | 1.44%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s     | 2        | 1.44%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s       | 2        | 1.44%   |
| Kingston RAM KHX1600C9D3/2GX 2GB DIMM DDR3 1600MT/s     | 2        | 1.44%   |
| Kingston RAM 99U5584-001.A00LF 4GB DIMM DDR3 1600MT/s   | 2        | 1.44%   |
| Kingston RAM 2G-UDIMM 2048MB DIMM DDR2 800MT/s          | 2        | 1.44%   |
| Corsair RAM CML8GX3M2A1600C9 4GB DIMM DDR3 1867MT/s     | 2        | 1.44%   |
| Unknown RAM Module 64MB DIMM DRAM 100MT/s               | 1        | 0.72%   |
| Unknown RAM Module 512MB DIMM DDR 400MT/s               | 1        | 0.72%   |
| Unknown RAM Module 512MB DIMM DDR 333MT/s               | 1        | 0.72%   |
| Unknown RAM Module 512MB DIMM DDR 200MT/s               | 1        | 0.72%   |
| Unknown RAM Module 512MB DIMM 533MT/s                   | 1        | 0.72%   |
| Unknown RAM Module 4GB FB-DIMM DDR2 667MT/s             | 1        | 0.72%   |
| Unknown RAM Module 4GB DIMM 400MT/s                     | 1        | 0.72%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s            | 1        | 0.72%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                 | 1        | 0.72%   |
| Unknown RAM Module 4096MB DIMM 1066MT/s                 | 1        | 0.72%   |
| Unknown RAM Module 2GB FB-DIMM DDR2 667MT/s             | 1        | 0.72%   |
| Unknown RAM Module 2GB DIMM SDRAM                       | 1        | 0.72%   |
| Unknown RAM Module 2GB DIMM DDR 667MT/s                 | 1        | 0.72%   |
| Unknown RAM Module 256MB DIMM DRAM 100MT/s              | 1        | 0.72%   |
| Unknown RAM Module 256MB DIMM DDR 333MT/s               | 1        | 0.72%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s            | 1        | 0.72%   |
| Unknown RAM Module 2048MB DIMM SDRAM                    | 1        | 0.72%   |
| Unknown RAM Module 2048MB DIMM DDR3 1600MT/s            | 1        | 0.72%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s            | 1        | 0.72%   |
| Unknown RAM Module 2048MB DIMM DDR2 1067MT/s            | 1        | 0.72%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                  | 1        | 0.72%   |
| Unknown RAM Module 1GB FB-DIMM DDR2 667MT/s             | 1        | 0.72%   |
| Unknown RAM Module 1GB DIMM DDR2 266MT/s                | 1        | 0.72%   |
| Unknown RAM Module 128MB DIMM DRAM 100MT/s              | 1        | 0.72%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s             | 1        | 0.72%   |
| Unknown RAM Module 1024MB DIMM DDR2 57535MT/s           | 1        | 0.72%   |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s              | 1        | 0.72%   |
| Unknown RAM Module 1024MB DIMM DDR 200MT/s              | 1        | 0.72%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                  | 1        | 0.72%   |
| Unknown RAM Module 1024MB DIMM 533MT/s                  | 1        | 0.72%   |
| Unknown RAM Module 1024MB DIMM                          | 1        | 0.72%   |
| Unknown (8AC8) RAM Module 4GB SODIMM DDR3 1600MT/s      | 1        | 0.72%   |
| Transcend RAM Module 2GB DIMM DDR2 667MT/s              | 1        | 0.72%   |
| SK hynix RAM HYMP164U64CP6-Y5 512MB DIMM DDR2 667MT/s   | 1        | 0.72%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s    | 1        | 0.72%   |
| SK hynix RAM HMT41GU6AFR8A-PB 8192MB DIMM DDR3 1600MT/s | 1        | 0.72%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s  | 1        | 0.72%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s    | 1        | 0.72%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s    | 1        | 0.72%   |
| Samsung RAM M393B1G70BH0-YK0 8192MB DIMM DDR3 1600MT/s  | 1        | 0.72%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s     | 1        | 0.72%   |
| Samsung RAM M378B2873EH1-CH9 1GB DIMM DDR3 1334MT/s     | 1        | 0.72%   |
| Samsung RAM M378A1K43CB2-CTD 8192MB DIMM DDR4 3200MT/s  | 1        | 0.72%   |
| Patriot RAM PSD44G266681 4GB DIMM DDR4 2400MT/s         | 1        | 0.72%   |
| Patriot RAM PSD34G160081 4GB DIMM DDR3 1600MT/s         | 1        | 0.72%   |
| Patriot RAM PSD34G16002S 4096MB DIMM DDR3 1600MT/s      | 1        | 0.72%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 36       | 34.29%  |
| DDR4    | 29       | 27.62%  |
| DDR2    | 16       | 15.24%  |
| Unknown | 10       | 9.52%   |
| SDRAM   | 8        | 7.62%   |
| DDR     | 5        | 4.76%   |
| DRAM    | 1        | 0.95%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 99       | 97.06%  |
| SODIMM  | 2        | 1.96%   |
| FB-DIMM | 1        | 0.98%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 31       | 25.83%  |
| 4096  | 30       | 25%     |
| 8192  | 28       | 23.33%  |
| 1024  | 12       | 10%     |
| 16384 | 8        | 6.67%   |
| 512   | 5        | 4.17%   |
| 32768 | 2        | 1.67%   |
| 256   | 2        | 1.67%   |
| 128   | 1        | 0.83%   |
| 64    | 1        | 0.83%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 27       | 22.5%   |
| 1333    | 10       | 8.33%   |
| 800     | 10       | 8.33%   |
| 667     | 8        | 6.67%   |
| 3200    | 7        | 5.83%   |
| 2400    | 7        | 5.83%   |
| 1867    | 5        | 4.17%   |
| 333     | 5        | 4.17%   |
| 3600    | 4        | 3.33%   |
| 3466    | 3        | 2.5%    |
| 2667    | 3        | 2.5%    |
| 400     | 3        | 2.5%    |
| Unknown | 3        | 2.5%    |
| 3800    | 2        | 1.67%   |
| 3733    | 2        | 1.67%   |
| 2133    | 2        | 1.67%   |
| 1066    | 2        | 1.67%   |
| 533     | 2        | 1.67%   |
| 57535   | 1        | 0.83%   |
| 4000    | 1        | 0.83%   |
| 3533    | 1        | 0.83%   |
| 3400    | 1        | 0.83%   |
| 3333    | 1        | 0.83%   |
| 3000    | 1        | 0.83%   |
| 2666    | 1        | 0.83%   |
| 1866    | 1        | 0.83%   |
| 1800    | 1        | 0.83%   |
| 1639    | 1        | 0.83%   |
| 1334    | 1        | 0.83%   |
| 1067    | 1        | 0.83%   |
| 266     | 1        | 0.83%   |
| 200     | 1        | 0.83%   |
| 100     | 1        | 0.83%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 11       | 78.57%  |
| Star Micronics      | 1        | 7.14%   |
| Samsung Electronics | 1        | 7.14%   |
| Canon               | 1        | 7.14%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| HP LaserJet 1020                                | 4        | 28.57%  |
| HP Deskjet 1050 J410                            | 2        | 14.29%  |
| Star Micronics IP1000 Printer USB001            | 1        | 7.14%   |
| Samsung M262x/M282x Xpress Series Laser Printer | 1        | 7.14%   |
| HP OfficeJet 6950                               | 1        | 7.14%   |
| HP LaserJet M14-M17                             | 1        | 7.14%   |
| HP LaserJet M101-M106                           | 1        | 7.14%   |
| HP LaserJet 1150                                | 1        | 7.14%   |
| HP Deskjet 1510                                 | 1        | 7.14%   |
| Canon PIXMA MP230                               | 1        | 7.14%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Canon   | 2        | 66.67%  |
| Minolta | 1        | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Minolta Dimage Scan Dual III AF-2840 (2889) | 1        | 33.33%  |
| Canon CanoScan LiDE 90                      | 1        | 33.33%  |
| Canon CanoScan LIDE 25                      | 1        | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Microsoft                   | 7        | 21.88%  |
| Logitech                    | 7        | 21.88%  |
| Microdia                    | 5        | 15.63%  |
| Creative Technology         | 3        | 9.38%   |
| Z-Star Microelectronics     | 2        | 6.25%   |
| Valve Software              | 1        | 3.13%   |
| Unknown                     | 1        | 3.13%   |
| Syntek                      | 1        | 3.13%   |
| MacroSilicon                | 1        | 3.13%   |
| KYE Systems (Mouse Systems) | 1        | 3.13%   |
| Cubeternet                  | 1        | 3.13%   |
| Apple                       | 1        | 3.13%   |
| Alcor Micro                 | 1        | 3.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| Microdia Sonix USB 2.0 Camera             | 3        | 9.38%   |
| Microsoft LifeCam Cinema                  | 2        | 6.25%   |
| Creative Live! Cam Sync HD [VF0770]       | 2        | 6.25%   |
| Z-Star Vega USB 2.0 Camera                | 1        | 3.13%   |
| Z-Star A4 TECH HD PC Camera               | 1        | 3.13%   |
| Valve Software 3D Camera                  | 1        | 3.13%   |
| Unknown HD camera                         | 1        | 3.13%   |
| Syntek Integrated RGB Camera              | 1        | 3.13%   |
| Microsoft MicrosoftÃ‚ LifeCam VX-5500  | 1        | 3.13%   |
| Microsoft LifeCam VX-800                  | 1        | 3.13%   |
| Microsoft LifeCam VX-700                  | 1        | 3.13%   |
| Microsoft LifeCam VX-500 [1357]           | 1        | 3.13%   |
| Microsoft LifeCam HD-3000                 | 1        | 3.13%   |
| Microdia USB 2.0 Camera                   | 1        | 3.13%   |
| Microdia Camera                           | 1        | 3.13%   |
| MacroSilicon MiraBox Capture              | 1        | 3.13%   |
| Logitech Webcam C930e                     | 1        | 3.13%   |
| Logitech Webcam C925e                     | 1        | 3.13%   |
| Logitech Webcam C270                      | 1        | 3.13%   |
| Logitech Webcam C200                      | 1        | 3.13%   |
| Logitech HD Webcam C525                   | 1        | 3.13%   |
| Logitech HD Pro Webcam C920               | 1        | 3.13%   |
| Logitech C505e HD Webcam                  | 1        | 3.13%   |
| KYE Systems (Mouse Systems) FaceCam 1000X | 1        | 3.13%   |
| Cubeternet HDMI to U3 capture             | 1        | 3.13%   |
| Creative Live! Cam Chat HD [VF0700]       | 1        | 3.13%   |
| Apple iPhone 5/5C/5S/6/SE                 | 1        | 3.13%   |
| Alcor Micro USB 2.0 PC Camera             | 1        | 3.13%   |

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
| Gemalto (was Gemplus) | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 171      | 84.24%  |
| 1     | 30       | 14.78%  |
| 2     | 2        | 0.99%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 17       | 51.52%  |
| Net/wireless             | 5        | 15.15%  |
| Sound                    | 2        | 6.06%   |
| Bluetooth                | 2        | 6.06%   |
| Unassigned class         | 1        | 3.03%   |
| Network                  | 1        | 3.03%   |
| Net/ethernet             | 1        | 3.03%   |
| Multimedia controller    | 1        | 3.03%   |
| Communication controller | 1        | 3.03%   |
| Chipcard                 | 1        | 3.03%   |
| Card reader              | 1        | 3.03%   |

