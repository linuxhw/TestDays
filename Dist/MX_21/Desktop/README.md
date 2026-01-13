MX 21 - Tested Hardware & Statistics (Desktops)
-----------------------------------------------

A project to collect tested hardware configurations for MX 21.

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

Total: 167

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | M5A78L-M LX PLUS            | [212a29eda9](https://linux-hardware.org/?probe=212a29eda9) | Dec 01, 2025 |
| ECS           | P43G                        | [399e8e60fa](https://linux-hardware.org/?probe=399e8e60fa) | Jul 22, 2025 |
| HP            | 18E5                        | [ad19b3112b](https://linux-hardware.org/?probe=ad19b3112b) | Jan 23, 2025 |
| Unknown       | Unknown                     | [8d647549f4](https://linux-hardware.org/?probe=8d647549f4) | Jan 15, 2025 |
| Unknown       | Unknown                     | [c3d2f04421](https://linux-hardware.org/?probe=c3d2f04421) | Jan 15, 2025 |
| Acer          | Aspire XC-605               | [5b81ea0b2c](https://linux-hardware.org/?probe=5b81ea0b2c) | Oct 27, 2024 |
| Dell          | 0P096C A00                  | [e67dbd9311](https://linux-hardware.org/?probe=e67dbd9311) | Sep 29, 2024 |
| ASUSTek       | GRYPHON Z87                 | [01b1c8c6cc](https://linux-hardware.org/?probe=01b1c8c6cc) | Jul 24, 2024 |
| ASUSTek       | SABERTOOTH 990FX            | [dc7cef1fe5](https://linux-hardware.org/?probe=dc7cef1fe5) | Apr 25, 2024 |
| ASRock        | X399 Taichi                 | [0aeb871159](https://linux-hardware.org/?probe=0aeb871159) | Apr 22, 2024 |
| Gateway       | H57M01                      | [4254102990](https://linux-hardware.org/?probe=4254102990) | Mar 19, 2024 |
| Gateway       | H57M01                      | [162b2ed3b3](https://linux-hardware.org/?probe=162b2ed3b3) | Mar 17, 2024 |
| ASUSTek       | PRIME B560-PLUS             | [5dc203d476](https://linux-hardware.org/?probe=5dc203d476) | Mar 10, 2024 |
| HP            | 8950                        | [ee925d29a1](https://linux-hardware.org/?probe=ee925d29a1) | Mar 08, 2024 |
| HP            | 8950                        | [f2b8f96540](https://linux-hardware.org/?probe=f2b8f96540) | Mar 08, 2024 |
| ASRock        | A300M-STX                   | [a92e2761aa](https://linux-hardware.org/?probe=a92e2761aa) | Mar 06, 2024 |
| Foxconn       | 45GM/45CM/45CM-S            | [1dab02eb79](https://linux-hardware.org/?probe=1dab02eb79) | Feb 24, 2024 |
| Lenovo        | 3741 SDK0T76461 WIN 3422... | [3cf24bd897](https://linux-hardware.org/?probe=3cf24bd897) | Feb 18, 2024 |
| Lenovo        | 3741 SDK0T76461 WIN 3422... | [144333e02b](https://linux-hardware.org/?probe=144333e02b) | Feb 15, 2024 |
| ASUSTek       | H110M-A/M.2                 | [9c0a07bf2b](https://linux-hardware.org/?probe=9c0a07bf2b) | Feb 08, 2024 |
| ASUSTek       | H110M-A/M.2                 | [7350797e64](https://linux-hardware.org/?probe=7350797e64) | Feb 07, 2024 |
| ASUSTek       | H81M-PLUS                   | [029706288d](https://linux-hardware.org/?probe=029706288d) | Jan 04, 2024 |
| ASUSTek       | M4A87TD/USB3                | [df3eb3c253](https://linux-hardware.org/?probe=df3eb3c253) | Dec 17, 2023 |
| Dell          | 03NVJ6 A03                  | [9a5c924695](https://linux-hardware.org/?probe=9a5c924695) | Nov 26, 2023 |
| Dell          | 0MNPJ9 A01                  | [80ded618fb](https://linux-hardware.org/?probe=80ded618fb) | Nov 19, 2023 |
| ASUSTek       | Maximus VIII HERO           | [0d65b73ae2](https://linux-hardware.org/?probe=0d65b73ae2) | Nov 07, 2023 |
| MSI           | A68HM-E33 V2                | [f6a5fcd391](https://linux-hardware.org/?probe=f6a5fcd391) | Oct 21, 2023 |
| ASUSTek       | PRIME H510M-D               | [e583e35b95](https://linux-hardware.org/?probe=e583e35b95) | Oct 03, 2023 |
| ASUSTek       | PRIME H510M-D               | [538889d79f](https://linux-hardware.org/?probe=538889d79f) | Oct 03, 2023 |
| MSI           | A68HM-E33 V2                | [af96cda252](https://linux-hardware.org/?probe=af96cda252) | Sep 02, 2023 |
| Foxconn       | 2A92                        | [50ca8342d7](https://linux-hardware.org/?probe=50ca8342d7) | Sep 01, 2023 |
| ASUSTek       | F1A75-M LE                  | [f059d25382](https://linux-hardware.org/?probe=f059d25382) | Aug 14, 2023 |
| MSI           | A68HM-E33 V2                | [44556227ff](https://linux-hardware.org/?probe=44556227ff) | Aug 05, 2023 |
| OEM           | Intel H81                   | [82606b5050](https://linux-hardware.org/?probe=82606b5050) | Aug 03, 2023 |
| Gigabyte      | B560 AORUS PRO AX           | [c7e057da76](https://linux-hardware.org/?probe=c7e057da76) | Aug 02, 2023 |
| Intel         | JSL MRD                     | [feb19ee725](https://linux-hardware.org/?probe=feb19ee725) | Jul 29, 2023 |
| Intel         | JSL MRD                     | [ca5990cfa3](https://linux-hardware.org/?probe=ca5990cfa3) | Jul 29, 2023 |
| ASUSTek       | LEUCITE3                    | [bb2046286f](https://linux-hardware.org/?probe=bb2046286f) | Jul 26, 2023 |
| ASUSTek       | LEUCITE3                    | [6ced09890f](https://linux-hardware.org/?probe=6ced09890f) | Jul 26, 2023 |
| ASRock        | B660M-HDV                   | [3a0685bcf0](https://linux-hardware.org/?probe=3a0685bcf0) | Jul 18, 2023 |
| Medion        | MS-7667                     | [52ff08b634](https://linux-hardware.org/?probe=52ff08b634) | Jul 09, 2023 |
| AOpen         | D1009 A1A4                  | [2819e086aa](https://linux-hardware.org/?probe=2819e086aa) | Jul 02, 2023 |
| ASRock        | A620M Pro RS WiFi           | [d04862302e](https://linux-hardware.org/?probe=d04862302e) | Jul 01, 2023 |
| MSI           | B350M MORTAR                | [6e5323aa42](https://linux-hardware.org/?probe=6e5323aa42) | Jun 09, 2023 |
| MSI           | B350M MORTAR                | [fc4b07cbb0](https://linux-hardware.org/?probe=fc4b07cbb0) | Jun 09, 2023 |
| Lenovo        | 3188 SDK0J40697 WIN 3305... | [c64fbbcad9](https://linux-hardware.org/?probe=c64fbbcad9) | Jun 02, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [7070e55aa0](https://linux-hardware.org/?probe=7070e55aa0) | Jun 01, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | [5ae19394fc](https://linux-hardware.org/?probe=5ae19394fc) | May 20, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | [14548bc77a](https://linux-hardware.org/?probe=14548bc77a) | May 20, 2023 |
| ASRock        | Z390 Phantom Gaming 9       | [5ca1acbf9b](https://linux-hardware.org/?probe=5ca1acbf9b) | May 19, 2023 |
| Unknown       | Unknown                     | [58066198c4](https://linux-hardware.org/?probe=58066198c4) | May 18, 2023 |
| Dell          | 06X1TJ A00                  | [d3107c9603](https://linux-hardware.org/?probe=d3107c9603) | May 14, 2023 |
| Gigabyte      | 990FXA-UD3                  | [3bc96663a8](https://linux-hardware.org/?probe=3bc96663a8) | May 14, 2023 |
| Gigabyte      | X670 GAMING X AX            | [ebd2a32ce2](https://linux-hardware.org/?probe=ebd2a32ce2) | May 12, 2023 |
| Gigabyte      | X670 GAMING X AX            | [352c0902e9](https://linux-hardware.org/?probe=352c0902e9) | May 11, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [f894b9a2c4](https://linux-hardware.org/?probe=f894b9a2c4) | May 07, 2023 |
| ASRock        | P55 Extreme                 | [e8721751c6](https://linux-hardware.org/?probe=e8721751c6) | May 03, 2023 |
| ASRock        | P55 Extreme                 | [e426e8e40b](https://linux-hardware.org/?probe=e426e8e40b) | May 03, 2023 |
| ASRock        | N68-S UCC                   | [f62abcbed6](https://linux-hardware.org/?probe=f62abcbed6) | May 02, 2023 |
| Dell          | 0PC5F7 A02                  | [2d1086090c](https://linux-hardware.org/?probe=2d1086090c) | May 01, 2023 |
| ASUSTek       | Z97-P                       | [8d94344086](https://linux-hardware.org/?probe=8d94344086) | Apr 26, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [4939e609de](https://linux-hardware.org/?probe=4939e609de) | Apr 24, 2023 |
| HP            | 090Ch                       | [01d609bbab](https://linux-hardware.org/?probe=01d609bbab) | Apr 23, 2023 |
| ASRock        | Z690 Pro RS                 | [acb9cde3d7](https://linux-hardware.org/?probe=acb9cde3d7) | Apr 23, 2023 |
| Gateway       | DX4860                      | [5583641f1b](https://linux-hardware.org/?probe=5583641f1b) | Apr 22, 2023 |
| ASUSTek       | GRYPHON Z87                 | [045a79a6e4](https://linux-hardware.org/?probe=045a79a6e4) | Apr 18, 2023 |
| HP            | 3646h                       | [c36653d824](https://linux-hardware.org/?probe=c36653d824) | Apr 12, 2023 |
| HP            | 18E5                        | [441d2678ff](https://linux-hardware.org/?probe=441d2678ff) | Apr 07, 2023 |
| ASUSTek       | P8P67 LE                    | [aea33c89a1](https://linux-hardware.org/?probe=aea33c89a1) | Apr 05, 2023 |
| ASUSTek       | Z97-P                       | [86d8d7f80f](https://linux-hardware.org/?probe=86d8d7f80f) | Apr 05, 2023 |
| HP            | 3029h                       | [153b913406](https://linux-hardware.org/?probe=153b913406) | Mar 27, 2023 |
| Unknown       | GB01                        | [ad0e76307c](https://linux-hardware.org/?probe=ad0e76307c) | Mar 24, 2023 |
| MSI           | B360M PRO-VH                | [2706ed39b7](https://linux-hardware.org/?probe=2706ed39b7) | Mar 23, 2023 |
| HP            | 3048h                       | [cd326ce9fa](https://linux-hardware.org/?probe=cd326ce9fa) | Mar 22, 2023 |
| ASRock        | AB350 Pro4                  | [4a452568eb](https://linux-hardware.org/?probe=4a452568eb) | Mar 16, 2023 |
| Shenzhen M... | F6BFC                       | [46cb84be25](https://linux-hardware.org/?probe=46cb84be25) | Mar 14, 2023 |
| MSI           | CSM-H87M-G43                | [9df13e200e](https://linux-hardware.org/?probe=9df13e200e) | Mar 14, 2023 |
| Lenovo        | ThinkCentre M58 7638CB8     | [d303f78e26](https://linux-hardware.org/?probe=d303f78e26) | Mar 14, 2023 |
| Gigabyte      | PH67A-D3-B3                 | [145a0a3b7d](https://linux-hardware.org/?probe=145a0a3b7d) | Mar 05, 2023 |
| HP            | 8184 X4                     | [b42f6862c7](https://linux-hardware.org/?probe=b42f6862c7) | Mar 04, 2023 |
| Unknown       | 1.0                         | [bab30a1ac1](https://linux-hardware.org/?probe=bab30a1ac1) | Feb 24, 2023 |
| Dell          | 0D441T A03                  | [351a527308](https://linux-hardware.org/?probe=351a527308) | Feb 18, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [482c922bbc](https://linux-hardware.org/?probe=482c922bbc) | Feb 14, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [13492935fd](https://linux-hardware.org/?probe=13492935fd) | Feb 09, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | [11f3874a6f](https://linux-hardware.org/?probe=11f3874a6f) | Feb 07, 2023 |
| ASUSTek       | Z97M-PLUS                   | [99a4bb9e50](https://linux-hardware.org/?probe=99a4bb9e50) | Feb 05, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | [42e242e6bf](https://linux-hardware.org/?probe=42e242e6bf) | Feb 04, 2023 |
| Unknown       | Unknown                     | [793f52c99a](https://linux-hardware.org/?probe=793f52c99a) | Feb 03, 2023 |
| ECS           | P4M800PRO-M                 | [f446d61863](https://linux-hardware.org/?probe=f446d61863) | Feb 02, 2023 |
| Intel         | D34010WYK H14771-303        | [31485ae6ec](https://linux-hardware.org/?probe=31485ae6ec) | Feb 01, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | [dd017ac78a](https://linux-hardware.org/?probe=dd017ac78a) | Jan 31, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | [a32a9ba13a](https://linux-hardware.org/?probe=a32a9ba13a) | Jan 30, 2023 |
| Gigabyte      | GA-MA770-UD3                | [554aa8592c](https://linux-hardware.org/?probe=554aa8592c) | Jan 28, 2023 |
| BESSTAR Te... | UM340                       | [77efbbb270](https://linux-hardware.org/?probe=77efbbb270) | Jan 27, 2023 |
| MSI           | Z390-A PRO                  | [28c31b639b](https://linux-hardware.org/?probe=28c31b639b) | Jan 25, 2023 |
| Gigabyte      | Z77X-D3H                    | [e81c0bcfc4](https://linux-hardware.org/?probe=e81c0bcfc4) | Jan 22, 2023 |
| Dell          | 0PC5F7 A02                  | [7671c99c3c](https://linux-hardware.org/?probe=7671c99c3c) | Jan 19, 2023 |
| HP            | 3396                        | [2085b91098](https://linux-hardware.org/?probe=2085b91098) | Jan 15, 2023 |
| Pegatron      | 2AD5                        | [d41fde4498](https://linux-hardware.org/?probe=d41fde4498) | Jan 15, 2023 |
| ASRock        | X370 Taichi                 | [9c3ea14006](https://linux-hardware.org/?probe=9c3ea14006) | Jan 09, 2023 |
| ASUSTek       | H81M-E                      | [165bb4a9ab](https://linux-hardware.org/?probe=165bb4a9ab) | Jan 06, 2023 |
| Dell          | 0D881F A06                  | [21e5ad204d](https://linux-hardware.org/?probe=21e5ad204d) | Jan 04, 2023 |
| Dell          | 0D881F A06                  | [00dddfca31](https://linux-hardware.org/?probe=00dddfca31) | Jan 03, 2023 |
| Gigabyte      | B550M DS3H                  | [677feeeca9](https://linux-hardware.org/?probe=677feeeca9) | Jan 03, 2023 |
| ZOTAC         | Unknown                     | [c3d5155637](https://linux-hardware.org/?probe=c3d5155637) | Jan 01, 2023 |
| MSI           | Z390-A PRO                  | [3a3375e173](https://linux-hardware.org/?probe=3a3375e173) | Dec 29, 2022 |
| MSI           | Z270 GAMING PRO CARBON      | [f422489705](https://linux-hardware.org/?probe=f422489705) | Dec 27, 2022 |
| Dell          | 0HY9JP A02                  | [c195f58592](https://linux-hardware.org/?probe=c195f58592) | Dec 24, 2022 |
| Lenovo        | 3741 SDK0T76461 WIN 3422... | [70e125f0d0](https://linux-hardware.org/?probe=70e125f0d0) | Dec 23, 2022 |
| Fujitsu       | D3498-A1 S26361-D3498-A1    | [03cd265cef](https://linux-hardware.org/?probe=03cd265cef) | Dec 05, 2022 |
| ASUSTek       | PRIME A320M-K               | [6487bbd7b7](https://linux-hardware.org/?probe=6487bbd7b7) | Dec 05, 2022 |
| SIRAGON       | AIO-5150                    | [90476603fa](https://linux-hardware.org/?probe=90476603fa) | Dec 04, 2022 |
| HP            | 304Ah                       | [15db22accc](https://linux-hardware.org/?probe=15db22accc) | Nov 30, 2022 |
| ASRock        | B365M Pro4                  | [0f0d4f70b0](https://linux-hardware.org/?probe=0f0d4f70b0) | Nov 20, 2022 |
| Foxconn       | 2ABF                        | [aa4bde7d79](https://linux-hardware.org/?probe=aa4bde7d79) | Nov 20, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [1a0674de42](https://linux-hardware.org/?probe=1a0674de42) | Nov 14, 2022 |
| ASRock        | B365M Pro4                  | [f5305c9730](https://linux-hardware.org/?probe=f5305c9730) | Nov 04, 2022 |
| MSI           | X570-A PRO                  | [c60d9aa72d](https://linux-hardware.org/?probe=c60d9aa72d) | Oct 31, 2022 |
| Biostar       | H61MH                       | [f505de310c](https://linux-hardware.org/?probe=f505de310c) | Oct 27, 2022 |
| Lenovo        | 318E NOK                    | [6b190bfb4f](https://linux-hardware.org/?probe=6b190bfb4f) | Oct 25, 2022 |
| Pegatron      | NARRA3                      | [1588e60c57](https://linux-hardware.org/?probe=1588e60c57) | Oct 12, 2022 |
| ASUSTek       | Z170-P                      | [2f3c79dd55](https://linux-hardware.org/?probe=2f3c79dd55) | Sep 29, 2022 |
| ASUSTek       | P5GC-MX/CKD/SI              | [72bb90ea71](https://linux-hardware.org/?probe=72bb90ea71) | Sep 28, 2022 |
| ASUSTek       | P5G41T-M LX                 | [8e429edcd6](https://linux-hardware.org/?probe=8e429edcd6) | Sep 25, 2022 |
| ASUSTek       | PRIME B450M-A               | [bdb353fd2c](https://linux-hardware.org/?probe=bdb353fd2c) | Sep 20, 2022 |
| HP            | 1632                        | [8309a8acf0](https://linux-hardware.org/?probe=8309a8acf0) | Sep 10, 2022 |
| Medion        | H110H4-EM                   | [1b22e5560d](https://linux-hardware.org/?probe=1b22e5560d) | Sep 07, 2022 |
| Gigabyte      | B560M DS3H V2               | [c430bf0275](https://linux-hardware.org/?probe=c430bf0275) | Sep 03, 2022 |
| Biostar       | A780L3B                     | [62782d600f](https://linux-hardware.org/?probe=62782d600f) | Aug 14, 2022 |
| Intel         | DH55TC AAE70932-303         | [f275229d83](https://linux-hardware.org/?probe=f275229d83) | Jul 31, 2022 |
| MP            | MS-7848                     | [f7696965e0](https://linux-hardware.org/?probe=f7696965e0) | Jul 22, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [85782181c7](https://linux-hardware.org/?probe=85782181c7) | Jul 21, 2022 |
| ASUSTek       | P8H61/USB3 R2.0             | [1076f6d59a](https://linux-hardware.org/?probe=1076f6d59a) | Jul 19, 2022 |
| AOpen         | D1009 A1A4                  | [d8edf66887](https://linux-hardware.org/?probe=d8edf66887) | Jul 13, 2022 |
| Dell          | 0DR845                      | [4c4a530cc5](https://linux-hardware.org/?probe=4c4a530cc5) | Jul 06, 2022 |
| MSI           | B350 TOMAHAWK               | [5a66940742](https://linux-hardware.org/?probe=5a66940742) | Jun 23, 2022 |
| MSI           | Z77A-G41                    | [d0f55f3c0b](https://linux-hardware.org/?probe=d0f55f3c0b) | Jun 22, 2022 |
| Dell          | 0200DY A01                  | [bc8030c1d5](https://linux-hardware.org/?probe=bc8030c1d5) | Jun 22, 2022 |
| Dell          | 0DR845                      | [56b4af8d26](https://linux-hardware.org/?probe=56b4af8d26) | Jun 20, 2022 |
| Gigabyte      | H410M S2H V3                | [b57b3a635c](https://linux-hardware.org/?probe=b57b3a635c) | Jun 02, 2022 |
| ASUSTek       | SABERTOOTH X99              | [b627953ad4](https://linux-hardware.org/?probe=b627953ad4) | May 11, 2022 |
| Intel         | V1.3                        | [a01993f2fa](https://linux-hardware.org/?probe=a01993f2fa) | Apr 30, 2022 |
| ASUSTek       | SABERTOOTH X99              | [51cc264c62](https://linux-hardware.org/?probe=51cc264c62) | Apr 22, 2022 |
| Gigabyte      | B550M S2H                   | [208972e3b5](https://linux-hardware.org/?probe=208972e3b5) | Apr 19, 2022 |
| ASRock        | N3150M                      | [0ee71f6582](https://linux-hardware.org/?probe=0ee71f6582) | Apr 19, 2022 |
| Gigabyte      | B550M S2H                   | [1127f26185](https://linux-hardware.org/?probe=1127f26185) | Apr 17, 2022 |
| Dell          | 0YXT71 A01                  | [5de0fab8f2](https://linux-hardware.org/?probe=5de0fab8f2) | Apr 04, 2022 |
| Lenovo        | 1046 NO DPK                 | [561b1c3324](https://linux-hardware.org/?probe=561b1c3324) | Mar 17, 2022 |
| Gigabyte      | Z390 UD                     | [d0b555e0ba](https://linux-hardware.org/?probe=d0b555e0ba) | Mar 17, 2022 |
| HP            | 3647h                       | [fd6766aabb](https://linux-hardware.org/?probe=fd6766aabb) | Mar 11, 2022 |
| ASUSTek       | P5GC-MX/MEDION/SI           | [772e020316](https://linux-hardware.org/?probe=772e020316) | Mar 09, 2022 |
| MSI           | MS-7091                     | [71aaa6a920](https://linux-hardware.org/?probe=71aaa6a920) | Mar 09, 2022 |
| MSI           | MS-7091                     | [b08ddd1115](https://linux-hardware.org/?probe=b08ddd1115) | Mar 09, 2022 |
| ASUSTek       | ROG Maximus XIII HERO       | [e58223cc60](https://linux-hardware.org/?probe=e58223cc60) | Feb 18, 2022 |
| Huanan        | X99-F8 V2.0                 | [23c722f6cf](https://linux-hardware.org/?probe=23c722f6cf) | Feb 18, 2022 |
| Huanan        | X99-F8 V2.0                 | [f4fec6a5be](https://linux-hardware.org/?probe=f4fec6a5be) | Feb 17, 2022 |
| MSI           | Z97 GAMING 5                | [7c66c1b404](https://linux-hardware.org/?probe=7c66c1b404) | Feb 09, 2022 |
| ASUSTek       | X99-DELUXE                  | [4ffe151e7a](https://linux-hardware.org/?probe=4ffe151e7a) | Jan 29, 2022 |
| HP            | 0B4Ch D                     | [ecaec39529](https://linux-hardware.org/?probe=ecaec39529) | Jan 05, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [78d4e04363](https://linux-hardware.org/?probe=78d4e04363) | Dec 16, 2021 |
| GALAX         | B550M                       | [a6866c8a45](https://linux-hardware.org/?probe=a6866c8a45) | Dec 04, 2021 |
| Lenovo        | SHARKBAY NO DPK             | [fd5f409df8](https://linux-hardware.org/?probe=fd5f409df8) | Nov 14, 2021 |
| Lenovo        | SHARKBAY NO DPK             | [a85cc99f78](https://linux-hardware.org/?probe=a85cc99f78) | Nov 14, 2021 |
| ASRock        | X570 Steel Legend           | [18391015f7](https://linux-hardware.org/?probe=18391015f7) | Nov 11, 2021 |
| Gigabyte      | X570 AORUS PRO              | [fbd2076eee](https://linux-hardware.org/?probe=fbd2076eee) | Oct 28, 2021 |
| Gigabyte      | B550M DS3H                  | [ee6a141211](https://linux-hardware.org/?probe=ee6a141211) | Oct 19, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | [5d136cb09b](https://linux-hardware.org/?probe=5d136cb09b) | Aug 13, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Desktops | Percent |
|----------------------------|----------|---------|
| 5.10.0-21-amd64            | 14       | 10.29%  |
| 5.10.0-20-amd64            | 13       | 9.56%   |
| 6.0.0-6mx-amd64            | 12       | 8.82%   |
| 5.14.0-4mx-amd64           | 7        | 5.15%   |
| 5.10.0-23-amd64            | 7        | 5.15%   |
| 5.10.0-18-amd64            | 7        | 5.15%   |
| 5.10.0-19-amd64            | 6        | 4.41%   |
| 5.10.0-13-amd64            | 5        | 3.68%   |
| 6.0.0-10.1-liquorix-amd64  | 4        | 2.94%   |
| 5.18.0-4mx-amd64           | 4        | 2.94%   |
| 5.10.0-16-amd64            | 4        | 2.94%   |
| 5.10.0-15-amd64            | 4        | 2.94%   |
| 5.16.0-5mx-amd64           | 3        | 2.21%   |
| 5.10.0-33-amd64            | 3        | 2.21%   |
| 5.14.0-3mx-amd64           | 2        | 1.47%   |
| 5.10.0-9-amd64             | 2        | 1.47%   |
| 5.10.0-28-amd64            | 2        | 1.47%   |
| 5.10.0-11-amd64            | 2        | 1.47%   |
| 6.7.12-1-liquorix-amd64    | 1        | 0.74%   |
| 6.5.9-2-liquorix-amd64     | 1        | 0.74%   |
| 6.5.0-5mx-ahs-amd64        | 1        | 0.74%   |
| 6.2.14-1-liquorix-amd64    | 1        | 0.74%   |
| 6.12.6-1-liquorix-amd64    | 1        | 0.74%   |
| 6.1.15-2-liquorix-amd64    | 1        | 0.74%   |
| 6.1.0-2mx-amd64            | 1        | 0.74%   |
| 6.0.5-x64v1-xanmod1        | 1        | 0.74%   |
| 6.0.0-4mx-rt-amd64         | 1        | 0.74%   |
| 6.0.0-13.3-liquorix-amd64  | 1        | 0.74%   |
| 5.19.0-4.2-liquorix-amd64  | 1        | 0.74%   |
| 5.19.0-2mx-amd64           | 1        | 0.74%   |
| 5.19.0-17.2-liquorix-amd64 | 1        | 0.74%   |
| 5.19.0-14.1-liquorix-amd64 | 1        | 0.74%   |
| 5.17.0-3mx-amd64           | 1        | 0.74%   |
| 5.17.0-2mx-amd64           | 1        | 0.74%   |
| 5.16.0-rc5-hwmon-next+     | 1        | 0.74%   |
| 5.16.0-6mx-amd64           | 1        | 0.74%   |
| 5.15.0-2-amd64             | 1        | 0.74%   |
| 5.15.0-0.bpo.2-amd64       | 1        | 0.74%   |
| 5.14.0-2mx-amd64           | 1        | 0.74%   |
| 5.10.52-antix.1-amd64-smp  | 1        | 0.74%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.10.0   | 77       | 57.46%  |
| 6.0.0    | 18       | 13.43%  |
| 5.14.0   | 10       | 7.46%   |
| 5.16.0   | 5        | 3.73%   |
| 5.19.0   | 4        | 2.99%   |
| 5.18.0   | 4        | 2.99%   |
| 5.17.0   | 2        | 1.49%   |
| 5.15.0   | 2        | 1.49%   |
| 6.7.12   | 1        | 0.75%   |
| 6.5.9    | 1        | 0.75%   |
| 6.5.0    | 1        | 0.75%   |
| 6.2.14   | 1        | 0.75%   |
| 6.12.6   | 1        | 0.75%   |
| 6.1.15   | 1        | 0.75%   |
| 6.1.0    | 1        | 0.75%   |
| 6.0.5    | 1        | 0.75%   |
| 5.10.52  | 1        | 0.75%   |
| 5.10.113 | 1        | 0.75%   |
| 5.10.111 | 1        | 0.75%   |
| 4.19.0   | 1        | 0.75%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 80       | 59.7%   |
| 6.0     | 19       | 14.18%  |
| 5.14    | 10       | 7.46%   |
| 5.16    | 5        | 3.73%   |
| 5.19    | 4        | 2.99%   |
| 5.18    | 4        | 2.99%   |
| 6.5     | 2        | 1.49%   |
| 6.1     | 2        | 1.49%   |
| 5.17    | 2        | 1.49%   |
| 5.15    | 2        | 1.49%   |
| 6.7     | 1        | 0.75%   |
| 6.2     | 1        | 0.75%   |
| 6.12    | 1        | 0.75%   |
| 4.19    | 1        | 0.75%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 131      | 97.76%  |
| i686   | 3        | 2.24%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| XFCE             | 104      | 77.61%  |
| KDE5             | 27       | 20.15%  |
| lightdm-xsession | 2        | 1.49%   |
| Unknown          | 1        | 0.75%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 134      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 104      | 77.61%  |
| SDDM    | 25       | 18.66%  |
| SLiM    | 4        | 2.99%   |
| GDM     | 1        | 0.75%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 58       | 43.28%  |
| de_DE | 17       | 12.69%  |
| it_IT | 8        | 5.97%   |
| en_GB | 8        | 5.97%   |
| ru_RU | 5        | 3.73%   |
| es_AR | 5        | 3.73%   |
| pl_PL | 4        | 2.99%   |
| sv_SE | 3        | 2.24%   |
| es_VE | 3        | 2.24%   |
| es_ES | 3        | 2.24%   |
| en_AU | 3        | 2.24%   |
| de_CH | 3        | 2.24%   |
| pt_BR | 2        | 1.49%   |
| fr_FR | 2        | 1.49%   |
| es_MX | 2        | 1.49%   |
| sk_SK | 1        | 0.75%   |
| hu_HU | 1        | 0.75%   |
| hr_HR | 1        | 0.75%   |
| fi_FI | 1        | 0.75%   |
| es_CO | 1        | 0.75%   |
| en_NZ | 1        | 0.75%   |
| en_CA | 1        | 0.75%   |
| el_GR | 1        | 0.75%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 80       | 59.7%   |
| EFI  | 54       | 40.3%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 119      | 88.81%  |
| Overlay  | 9        | 6.72%   |
| Btrfs    | 2        | 1.49%   |
| Xfs      | 1        | 0.75%   |
| Tmpfs    | 1        | 0.75%   |
| Reiserfs | 1        | 0.75%   |
| Ext3     | 1        | 0.75%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 78       | 57.78%  |
| MBR  | 57       | 42.22%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 86       | 62.77%  |
| Yes       | 51       | 37.23%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 71       | 52.99%  |
| No        | 63       | 47.01%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 31       | 23.13%  |
| Gigabyte Technology                  | 15       | 11.19%  |
| ASRock                               | 13       | 9.7%    |
| MSI                                  | 12       | 8.96%   |
| Dell                                 | 12       | 8.96%   |
| Hewlett-Packard                      | 11       | 8.21%   |
| Lenovo                               | 6        | 4.48%   |
| Unknown                              | 5        | 3.73%   |
| Intel                                | 4        | 2.99%   |
| Foxconn                              | 3        | 2.24%   |
| Pegatron                             | 2        | 1.49%   |
| Medion                               | 2        | 1.49%   |
| Gateway                              | 2        | 1.49%   |
| Fujitsu                              | 2        | 1.49%   |
| ECS                                  | 2        | 1.49%   |
| Biostar                              | 2        | 1.49%   |
| ZOTAC                                | 1        | 0.75%   |
| SIRAGON                              | 1        | 0.75%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.75%   |
| OEM                                  | 1        | 0.75%   |
| MP                                   | 1        | 0.75%   |
| Huanan                               | 1        | 0.75%   |
| GALAX                                | 1        | 0.75%   |
| BESSTAR Tech                         | 1        | 0.75%   |
| AOpen                                | 1        | 0.75%   |
| Acer                                 | 1        | 0.75%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Desktops | Percent |
|---------------------------------------------|----------|---------|
| ASUS All Series                             | 9        | 6.72%   |
| Unknown                                     | 6        | 4.48%   |
| MSI MS-7C91                                 | 2        | 1.49%   |
| HP EliteDesk 800 G1 USDT                    | 2        | 1.49%   |
| Gigabyte GA-MA785GM-US2H                    | 2        | 1.49%   |
| Dell OptiPlex 9020                          | 2        | 1.49%   |
| Dell OptiPlex 780                           | 2        | 1.49%   |
| Dell OptiPlex 755                           | 2        | 1.49%   |
| ASUS ROG Maximus XIII HERO                  | 2        | 1.49%   |
| SIRAGON AIO-5150                            | 1        | 0.75%   |
| Shenzhen Meigao Electronic Equipment UM450  | 1        | 0.75%   |
| Pegatron FQ425AA-ABA a6655f                 | 1        | 0.75%   |
| Pegatron 2AD5                               | 1        | 0.75%   |
| OEM Intel H81                               | 1        | 0.75%   |
| MSI MS-7E12                                 | 1        | 0.75%   |
| MSI MS-7C37                                 | 1        | 0.75%   |
| MSI MS-7B98                                 | 1        | 0.75%   |
| MSI MS-7B53                                 | 1        | 0.75%   |
| MSI MS-7A63                                 | 1        | 0.75%   |
| MSI MS-7A34                                 | 1        | 0.75%   |
| MSI MS-7917                                 | 1        | 0.75%   |
| MSI MS-7823                                 | 1        | 0.75%   |
| MSI MS-7758                                 | 1        | 0.75%   |
| MSI MS-7721                                 | 1        | 0.75%   |
| MP MS-7848                                  | 1        | 0.75%   |
| Medion MS-7667                              | 1        | 0.75%   |
| Medion Akoya P5330 E MD8876/2458            | 1        | 0.75%   |
| Lenovo V50s-07IMB 11HB002AFR                | 1        | 0.75%   |
| Lenovo ThinkStation P620 30E0CTO1WW         | 1        | 0.75%   |
| Lenovo ThinkCentre M75s Gen 2 11JAS0CJ00    | 1        | 0.75%   |
| Lenovo ThinkCentre M58 7638CB8              | 1        | 0.75%   |
| Lenovo IdeaCentre Gaming5 17IAB7 90T00007US | 1        | 0.75%   |
| Lenovo 10AAS1QB0B                           | 1        | 0.75%   |
| Intel V1.3                                  | 1        | 0.75%   |
| Intel Jasper Lake Client Platform           | 1        | 0.75%   |
| Intel DH55TC AAE70932-303                   | 1        | 0.75%   |
| Intel D34010WYK H14771-303                  | 1        | 0.75%   |
| Huanan X99-F8                               | 1        | 0.75%   |
| HP Z400 Workstation                         | 1        | 0.75%   |
| HP Elite Tower 600 G9 Desktop PC            | 1        | 0.75%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Dell OptiPlex                              | 9        | 6.72%   |
| ASUS All                                   | 9        | 6.72%   |
| Unknown                                    | 6        | 4.48%   |
| HP Compaq                                  | 4        | 2.99%   |
| ASUS ROG                                   | 3        | 2.24%   |
| ASUS PRIME                                 | 3        | 2.24%   |
| MSI MS-7C91                                | 2        | 1.49%   |
| Lenovo ThinkCentre                         | 2        | 1.49%   |
| HP EliteDesk                               | 2        | 1.49%   |
| Gigabyte GA-MA785GM-US2H                   | 2        | 1.49%   |
| Gigabyte B550M                             | 2        | 1.49%   |
| Dell Precision                             | 2        | 1.49%   |
| ASUS TUF                                   | 2        | 1.49%   |
| ASUS P5GC-MX                               | 2        | 1.49%   |
| SIRAGON AIO-5150                           | 1        | 0.75%   |
| Shenzhen Meigao Electronic Equipment UM450 | 1        | 0.75%   |
| Pegatron FQ425AA-ABA                       | 1        | 0.75%   |
| Pegatron 2AD5                              | 1        | 0.75%   |
| OEM Intel                                  | 1        | 0.75%   |
| MSI MS-7E12                                | 1        | 0.75%   |
| MSI MS-7C37                                | 1        | 0.75%   |
| MSI MS-7B98                                | 1        | 0.75%   |
| MSI MS-7B53                                | 1        | 0.75%   |
| MSI MS-7A63                                | 1        | 0.75%   |
| MSI MS-7A34                                | 1        | 0.75%   |
| MSI MS-7917                                | 1        | 0.75%   |
| MSI MS-7823                                | 1        | 0.75%   |
| MSI MS-7758                                | 1        | 0.75%   |
| MSI MS-7721                                | 1        | 0.75%   |
| MP MS-7848                                 | 1        | 0.75%   |
| Medion MS-7667                             | 1        | 0.75%   |
| Medion Akoya                               | 1        | 0.75%   |
| Lenovo V50s-07IMB                          | 1        | 0.75%   |
| Lenovo ThinkStation                        | 1        | 0.75%   |
| Lenovo IdeaCentre                          | 1        | 0.75%   |
| Lenovo 10AAS1QB0B                          | 1        | 0.75%   |
| Intel V1.3                                 | 1        | 0.75%   |
| Intel Jasper                               | 1        | 0.75%   |
| Intel DH55TC                               | 1        | 0.75%   |
| Intel D34010WYK                            | 1        | 0.75%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 14       | 10.45%  |
| 2022 | 12       | 8.96%   |
| 2021 | 12       | 8.96%   |
| 2011 | 11       | 8.21%   |
| 2020 | 9        | 6.72%   |
| 2018 | 9        | 6.72%   |
| 2014 | 8        | 5.97%   |
| 2010 | 8        | 5.97%   |
| 2009 | 8        | 5.97%   |
| 2016 | 7        | 5.22%   |
| 2012 | 7        | 5.22%   |
| 2019 | 6        | 4.48%   |
| 2008 | 6        | 4.48%   |
| 2007 | 6        | 4.48%   |
| 2015 | 4        | 2.99%   |
| 2017 | 3        | 2.24%   |
| 2023 | 2        | 1.49%   |
| 2006 | 1        | 0.75%   |
| 2004 | 1        | 0.75%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 134      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 134      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 134      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 32       | 23.7%   |
| 4.01-8.0    | 27       | 20%     |
| 32.01-64.0  | 23       | 17.04%  |
| 16.01-24.0  | 22       | 16.3%   |
| 3.01-4.0    | 17       | 12.59%  |
| 24.01-32.0  | 6        | 4.44%   |
| 64.01-256.0 | 4        | 2.96%   |
| 2.01-3.0    | 2        | 1.48%   |
| 0.51-1.0    | 2        | 1.48%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 54       | 39.13%  |
| 2.01-3.0   | 36       | 26.09%  |
| 4.01-8.0   | 18       | 13.04%  |
| 3.01-4.0   | 17       | 12.32%  |
| 0.51-1.0   | 6        | 4.35%   |
| 8.01-16.0  | 5        | 3.62%   |
| 16.01-24.0 | 2        | 1.45%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 48       | 35.56%  |
| 2      | 33       | 24.44%  |
| 3      | 29       | 21.48%  |
| 4      | 15       | 11.11%  |
| 5      | 5        | 3.7%    |
| 8      | 3        | 2.22%   |
| 9      | 1        | 0.74%   |
| 7      | 1        | 0.74%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 69       | 51.49%  |
| No        | 65       | 48.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 133      | 99.25%  |
| No        | 1        | 0.75%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 71       | 52.99%  |
| No        | 63       | 47.01%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 91       | 67.91%  |
| Yes       | 43       | 32.09%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Desktops | Percent |
|------------------------|----------|---------|
| USA                    | 30       | 22.39%  |
| Germany                | 17       | 12.69%  |
| Italy                  | 8        | 5.97%   |
| Russia                 | 5        | 3.73%   |
| Poland                 | 5        | 3.73%   |
| Canada                 | 5        | 3.73%   |
| Australia              | 5        | 3.73%   |
| Argentina              | 5        | 3.73%   |
| Venezuela              | 4        | 2.99%   |
| UK                     | 4        | 2.99%   |
| Sweden                 | 4        | 2.99%   |
| Finland                | 4        | 2.99%   |
| Switzerland            | 3        | 2.24%   |
| Spain                  | 3        | 2.24%   |
| India                  | 3        | 2.24%   |
| France                 | 3        | 2.24%   |
| Singapore              | 2        | 1.49%   |
| Mexico                 | 2        | 1.49%   |
| Greece                 | 2        | 1.49%   |
| Brazil                 | 2        | 1.49%   |
| Ukraine                | 1        | 0.75%   |
| South Africa           | 1        | 0.75%   |
| Slovakia               | 1        | 0.75%   |
| Romania                | 1        | 0.75%   |
| New Zealand            | 1        | 0.75%   |
| Netherlands            | 1        | 0.75%   |
| Lithuania              | 1        | 0.75%   |
| Jamaica                | 1        | 0.75%   |
| Ireland                | 1        | 0.75%   |
| Indonesia              | 1        | 0.75%   |
| Hungary                | 1        | 0.75%   |
| French Guiana          | 1        | 0.75%   |
| Estonia                | 1        | 0.75%   |
| Denmark                | 1        | 0.75%   |
| Croatia                | 1        | 0.75%   |
| Colombia               | 1        | 0.75%   |
| Bosnia and Herzegovina | 1        | 0.75%   |
| Belgium                | 1        | 0.75%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Sydney                | 3        | 2.24%   |
| Moscow                | 3        | 2.24%   |
| Toronto               | 2        | 1.49%   |
| Singapore             | 2        | 1.49%   |
| Mesquite              | 2        | 1.49%   |
| Krakow                | 2        | 1.49%   |
| Houston               | 2        | 1.49%   |
| Helsinki              | 2        | 1.49%   |
| Göttingen            | 2        | 1.49%   |
| Ettingen              | 2        | 1.49%   |
| Córdoba              | 2        | 1.49%   |
| Berlin                | 2        | 1.49%   |
| Bengaluru             | 2        | 1.49%   |
| Alma                  | 2        | 1.49%   |
| Zagreb                | 1        | 0.75%   |
| Volos                 | 1        | 0.75%   |
| Voghera               | 1        | 0.75%   |
| Vilnius               | 1        | 0.75%   |
| Vilhelmina            | 1        | 0.75%   |
| Vasco da Gama         | 1        | 0.75%   |
| Vaidasoo              | 1        | 0.75%   |
| Tuglie                | 1        | 0.75%   |
| Tlalnepantla          | 1        | 0.75%   |
| Tampere               | 1        | 0.75%   |
| Surrey                | 1        | 0.75%   |
| Stockholm             | 1        | 0.75%   |
| Stevens Point         | 1        | 0.75%   |
| Stafford              | 1        | 0.75%   |
| St Petersburg         | 1        | 0.75%   |
| Spanish Town          | 1        | 0.75%   |
| Sollentuna            | 1        | 0.75%   |
| Seelbach              | 1        | 0.75%   |
| Seattle               | 1        | 0.75%   |
| Santa Rita do Sapucai | 1        | 0.75%   |
| San Fernando          | 1        | 0.75%   |
| San Diego             | 1        | 0.75%   |
| Rzeszów              | 1        | 0.75%   |
| Rosporden             | 1        | 0.75%   |
| Reno                  | 1        | 0.75%   |
| Rathenow              | 1        | 0.75%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Samsung Electronics       | 46       | 74     | 17.69%  |
| WDC                       | 45       | 57     | 17.31%  |
| Seagate                   | 44       | 68     | 16.92%  |
| Kingston                  | 24       | 25     | 9.23%   |
| Sandisk                   | 15       | 17     | 5.77%   |
| Toshiba                   | 11       | 12     | 4.23%   |
| China                     | 11       | 12     | 4.23%   |
| Crucial                   | 8        | 8      | 3.08%   |
| Hitachi                   | 6        | 7      | 2.31%   |
| Unknown                   | 5        | 9      | 1.92%   |
| PNY                       | 5        | 6      | 1.92%   |
| Corsair                   | 3        | 3      | 1.15%   |
| Transcend                 | 2        | 2      | 0.77%   |
| Team                      | 2        | 2      | 0.77%   |
| Silicon Motion            | 2        | 2      | 0.77%   |
| Intel                     | 2        | 3      | 0.77%   |
| GOODRAM                   | 2        | 2      | 0.77%   |
| Apacer                    | 2        | 2      | 0.77%   |
| A-DATA Technology         | 2        | 2      | 0.77%   |
| XPG                       | 1        | 1      | 0.38%   |
| WALRAM                    | 1        | 1      | 0.38%   |
| Vaseky                    | 1        | 1      | 0.38%   |
| SPCC                      | 1        | 1      | 0.38%   |
| Rogueware                 | 1        | 2      | 0.38%   |
| Phison Electronics        | 1        | 1      | 0.38%   |
| Phison                    | 1        | 1      | 0.38%   |
| Patriot                   | 1        | 1      | 0.38%   |
| OCZ                       | 1        | 1      | 0.38%   |
| Mushkin                   | 1        | 1      | 0.38%   |
| Micron/Crucial Technology | 1        | 1      | 0.38%   |
| Micron Technology         | 1        | 1      | 0.38%   |
| Maxtor                    | 1        | 1      | 0.38%   |
| Lexar                     | 1        | 1      | 0.38%   |
| KingSpec                  | 1        | 1      | 0.38%   |
| JMicron Technology        | 1        | 1      | 0.38%   |
| Hoodisk                   | 1        | 1      | 0.38%   |
| HGST                      | 1        | 1      | 0.38%   |
| Gigabyte Technology       | 1        | 1      | 0.38%   |
| External                  | 1        | 1      | 0.38%   |
| CT1000P3                  | 1        | 1      | 0.38%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Kingston SA400S37480G 480GB SSD  | 7        | 2.27%   |
| Samsung SSD 850 EVO 250GB        | 6        | 1.94%   |
| Kingston SV300S37A240G 240GB SSD | 5        | 1.62%   |
| Seagate ST4000DM004-2CV104 4TB   | 4        | 1.29%   |
| Seagate ST2000DM008-2FR102 2TB   | 4        | 1.29%   |
| Samsung SSD 970 EVO Plus 1TB     | 4        | 1.29%   |
| Seagate ST500LM021-1KJ152 500GB  | 3        | 0.97%   |
| Seagate ST3500413AS 500GB        | 3        | 0.97%   |
| Seagate ST2000DM001-1ER164 2TB   | 3        | 0.97%   |
| SanDisk SDSSDA240G 240GB         | 3        | 0.97%   |
| SanDisk NVMe SSD Drive 1TB       | 3        | 0.97%   |
| Samsung SSD 980 PRO 1TB          | 3        | 0.97%   |
| Samsung SSD 970 EVO Plus 500GB   | 3        | 0.97%   |
| Samsung SSD 850 EVO 1TB          | 3        | 0.97%   |
| Samsung SSD 840 Series 120GB     | 3        | 0.97%   |
| Kingston SA400S37240G 240GB SSD  | 3        | 0.97%   |
| WDC WD3200AAKS-75B3A0 320GB      | 2        | 0.65%   |
| WDC WD10EZEX-00BN5A0 1TB         | 2        | 0.65%   |
| WDC WD10EZEX-00BBHA0 1TB         | 2        | 0.65%   |
| Unknown SD/MMC/MS PRO 2GB        | 2        | 0.65%   |
| Unknown SD/MMC 16GB              | 2        | 0.65%   |
| Unknown M.S./M.S.Pro/HG 16GB     | 2        | 0.65%   |
| Unknown Compact Flash 977MB      | 2        | 0.65%   |
| Toshiba HDWD110 1TB              | 2        | 0.65%   |
| Toshiba DT01ACA100 1TB           | 2        | 0.65%   |
| Seagate ST500DM002-1BD142 500GB  | 2        | 0.65%   |
| Seagate ST250DM000-1BD141 250GB  | 2        | 0.65%   |
| Seagate ST1000DM010-2EP102 1TB   | 2        | 0.65%   |
| Seagate ST1000DM003-1CH162 1TB   | 2        | 0.65%   |
| Seagate Expansion 2TB            | 2        | 0.65%   |
| SanDisk SSD PLUS 1000GB          | 2        | 0.65%   |
| SanDisk SDSSDA120G 120GB         | 2        | 0.65%   |
| Samsung SSD 980 500GB            | 2        | 0.65%   |
| Samsung SSD 970 PRO 512GB        | 2        | 0.65%   |
| Samsung SSD 870 QVO 1TB          | 2        | 0.65%   |
| Samsung SSD 870 EVO 500GB        | 2        | 0.65%   |
| Samsung SSD 860 EVO 500GB        | 2        | 0.65%   |
| Samsung SSD 860 EVO 250GB        | 2        | 0.65%   |
| Samsung SSD 850 EVO 500GB        | 2        | 0.65%   |
| Samsung HD501LJ 500GB            | 2        | 0.65%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 44       | 68     | 38.94%  |
| WDC                 | 41       | 53     | 36.28%  |
| Toshiba             | 11       | 12     | 9.73%   |
| Samsung Electronics | 6        | 8      | 5.31%   |
| Hitachi             | 6        | 7      | 5.31%   |
| Unknown             | 2        | 2      | 1.77%   |
| Maxtor              | 1        | 1      | 0.88%   |
| HGST                | 1        | 1      | 0.88%   |
| External            | 1        | 1      | 0.88%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 30       | 38     | 28.04%  |
| Kingston            | 21       | 22     | 19.63%  |
| China               | 11       | 12     | 10.28%  |
| SanDisk             | 10       | 11     | 9.35%   |
| Crucial             | 6        | 6      | 5.61%   |
| PNY                 | 4        | 4      | 3.74%   |
| WDC                 | 2        | 2      | 1.87%   |
| Transcend           | 2        | 2      | 1.87%   |
| Team                | 2        | 2      | 1.87%   |
| GOODRAM             | 2        | 2      | 1.87%   |
| A-DATA Technology   | 2        | 2      | 1.87%   |
| WALRAM              | 1        | 1      | 0.93%   |
| Vaseky              | 1        | 1      | 0.93%   |
| SPCC                | 1        | 1      | 0.93%   |
| Rogueware           | 1        | 2      | 0.93%   |
| Patriot             | 1        | 1      | 0.93%   |
| OCZ                 | 1        | 1      | 0.93%   |
| Mushkin             | 1        | 1      | 0.93%   |
| Micron Technology   | 1        | 1      | 0.93%   |
| KingSpec            | 1        | 1      | 0.93%   |
| Intel               | 1        | 1      | 0.93%   |
| Hoodisk             | 1        | 1      | 0.93%   |
| CT1000P3            | 1        | 1      | 0.93%   |
| Avant               | 1        | 1      | 0.93%   |
| Apacer              | 1        | 1      | 0.93%   |
| Acer                | 1        | 1      | 0.93%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 88       | 153    | 40%     |
| SSD     | 86       | 119    | 39.09%  |
| NVMe    | 42       | 57     | 19.09%  |
| Unknown | 3        | 7      | 1.36%   |
| MMC     | 1        | 1      | 0.45%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 119      | 258    | 68%     |
| NVMe | 42       | 57     | 24%     |
| SAS  | 13       | 21     | 7.43%   |
| MMC  | 1        | 1      | 0.57%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 94       | 147    | 50.27%  |
| 0.51-1.0   | 51       | 61     | 27.27%  |
| 1.01-2.0   | 24       | 34     | 12.83%  |
| 3.01-4.0   | 7        | 8      | 3.74%   |
| 4.01-10.0  | 5        | 13     | 2.67%   |
| 2.01-3.0   | 4        | 5      | 2.14%   |
| 10.01-20.0 | 2        | 4      | 1.07%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 32       | 23.7%   |
| 251-500        | 26       | 19.26%  |
| 501-1000       | 18       | 13.33%  |
| 1001-2000      | 15       | 11.11%  |
| More than 3000 | 14       | 10.37%  |
| 2001-3000      | 12       | 8.89%   |
| 51-100         | 10       | 7.41%   |
| 1-20           | 4        | 2.96%   |
| 21-50          | 3        | 2.22%   |
| Unknown        | 1        | 0.74%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 32       | 23.53%  |
| 21-50          | 23       | 16.91%  |
| 101-250        | 22       | 16.18%  |
| 51-100         | 18       | 13.24%  |
| 1001-2000      | 11       | 8.09%   |
| 251-500        | 9        | 6.62%   |
| 501-1000       | 9        | 6.62%   |
| More than 3000 | 8        | 5.88%   |
| 2001-3000      | 3        | 2.21%   |
| Unknown        | 1        | 0.74%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| China SSD 512GB                          | 2        | 2      | 4.55%   |
| WDC WDS100T2B0A-00SM50 1TB SSD           | 1        | 1      | 2.27%   |
| WDC WD40EZRX-00SPEB0 4TB                 | 1        | 1      | 2.27%   |
| WDC WD3200AAKS-00UU3A0 320GB             | 1        | 1      | 2.27%   |
| WDC WD3200AAJS-00L7A0 320GB              | 1        | 1      | 2.27%   |
| WDC WD3200AAJS-00B4A0 320GB              | 1        | 1      | 2.27%   |
| WDC WD2500AAJS-00B4A0 250GB              | 1        | 1      | 2.27%   |
| WDC WD20EFRX-68EUZN0 2TB                 | 1        | 2      | 2.27%   |
| WDC WD20EARS-00J99B0 2TB                 | 1        | 1      | 2.27%   |
| WDC WD10EZRZ-00HTKB0 1TB                 | 1        | 1      | 2.27%   |
| WDC WD10EZEX-00RKKA0 1TB                 | 1        | 1      | 2.27%   |
| WDC WD10EADS-98M2B0 1TB                  | 1        | 1      | 2.27%   |
| WDC WD10EADS-00M2B0 1TB                  | 1        | 1      | 2.27%   |
| Toshiba MQ01ABF050 500GB                 | 1        | 1      | 2.27%   |
| Toshiba MK1234GSX 120GB                  | 1        | 1      | 2.27%   |
| Seagate ST500LT012-9WS142 500GB          | 1        | 1      | 2.27%   |
| Seagate ST500LM021-1KJ152 500GB          | 1        | 1      | 2.27%   |
| Seagate ST500DM002-1BD142 500GB          | 1        | 1      | 2.27%   |
| Seagate ST380815AS 80GB                  | 1        | 1      | 2.27%   |
| Seagate ST3500413AS 500GB                | 1        | 1      | 2.27%   |
| Seagate ST3360320AS 360GB                | 1        | 1      | 2.27%   |
| Seagate ST3320620AS 320GB                | 1        | 1      | 2.27%   |
| Seagate ST3320418AS 320GB                | 1        | 1      | 2.27%   |
| Seagate ST320LT020-9YG142 320GB          | 1        | 1      | 2.27%   |
| Seagate ST320LT012-1DG14C 320GB          | 1        | 2      | 2.27%   |
| Seagate ST250DM000-1BD141 250GB          | 1        | 1      | 2.27%   |
| Seagate ST2000DM001-1ER164 2TB           | 1        | 1      | 2.27%   |
| Seagate ST1000VM002-1CT162 1TB           | 1        | 1      | 2.27%   |
| Seagate ST1000DM003-9YN162 1TB           | 1        | 1      | 2.27%   |
| SanDisk SDSSDX120GG25 120GB              | 1        | 1      | 2.27%   |
| Samsung Electronics SSD 870 EVO 500GB    | 1        | 2      | 2.27%   |
| Samsung Electronics SSD 850 EVO 500GB    | 1        | 1      | 2.27%   |
| Samsung Electronics SSD 850 EVO 1TB      | 1        | 2      | 2.27%   |
| Samsung Electronics SSD 840 Series 120GB | 1        | 1      | 2.27%   |
| Samsung Electronics HD103SI 1TB          | 1        | 1      | 2.27%   |
| Maxtor 4K040H2 40GB                      | 1        | 1      | 2.27%   |
| Lexar 500GB SSD                          | 1        | 1      | 2.27%   |
| Kingston SA400S37480G 480GB SSD          | 1        | 1      | 2.27%   |
| KingSpec P4-960 960GB                    | 1        | 1      | 2.27%   |
| Hitachi HTS545050A7E380 500GB            | 1        | 1      | 2.27%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 14       | 15     | 32.56%  |
| WDC                 | 12       | 13     | 27.91%  |
| Samsung Electronics | 5        | 7      | 11.63%  |
| Toshiba             | 2        | 2      | 4.65%   |
| China               | 2        | 2      | 4.65%   |
| SanDisk             | 1        | 1      | 2.33%   |
| Maxtor              | 1        | 1      | 2.33%   |
| Lexar               | 1        | 1      | 2.33%   |
| Kingston            | 1        | 1      | 2.33%   |
| KingSpec            | 1        | 1      | 2.33%   |
| Hitachi             | 1        | 2      | 2.33%   |
| HGST                | 1        | 1      | 2.33%   |
| GOODRAM             | 1        | 1      | 2.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 14       | 15     | 45.16%  |
| WDC                 | 11       | 12     | 35.48%  |
| Toshiba             | 2        | 2      | 6.45%   |
| Samsung Electronics | 1        | 1      | 3.23%   |
| Maxtor              | 1        | 1      | 3.23%   |
| Hitachi             | 1        | 2      | 3.23%   |
| HGST                | 1        | 1      | 3.23%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 28       | 34     | 71.79%  |
| SSD  | 10       | 13     | 25.64%  |
| NVMe | 1        | 1      | 2.56%   |

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
| Works    | 122      | 255    | 67.78%  |
| Malfunc  | 39       | 48     | 21.67%  |
| Detected | 19       | 34     | 10.56%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 93       | 45.81%  |
| AMD                         | 38       | 18.72%  |
| Samsung Electronics         | 18       | 8.87%   |
| ASMedia Technology          | 11       | 5.42%   |
| Phison Electronics          | 8        | 3.94%   |
| SanDisk                     | 7        | 3.45%   |
| Marvell Technology Group    | 4        | 1.97%   |
| JMicron Technology          | 4        | 1.97%   |
| Silicon Motion              | 3        | 1.48%   |
| Micron/Crucial Technology   | 3        | 1.48%   |
| LSI Logic / Symbios Logic   | 3        | 1.48%   |
| Kingston Technology Company | 3        | 1.48%   |
| VIA Technologies            | 2        | 0.99%   |
| Nvidia                      | 2        | 0.99%   |
| ULi Electronics             | 1        | 0.49%   |
| Silicon Image               | 1        | 0.49%   |
| MAXIO Technology (Hangzhou) | 1        | 0.49%   |
| ADATA Technology            | 1        | 0.49%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 13       | 5.24%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 12       | 4.84%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 12       | 4.84%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 10       | 4.03%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 7        | 2.82%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 7        | 2.82%   |
| AMD 500 Series Chipset SATA Controller                                                  | 7        | 2.82%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6        | 2.42%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 6        | 2.42%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5        | 2.02%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5        | 2.02%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5        | 2.02%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4        | 1.61%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 1.61%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4        | 1.61%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 4        | 1.61%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4        | 1.61%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 4        | 1.61%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 4        | 1.61%   |
| AMD 600 Series Chipset SATA Controller                                                  | 4        | 1.61%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 3        | 1.21%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                                   | 3        | 1.21%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 3        | 1.21%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 3        | 1.21%   |
| Phison E12 NVMe Controller                                                              | 3        | 1.21%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 3        | 1.21%   |
| Intel SATA Controller [RAID mode]                                                       | 3        | 1.21%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3        | 1.21%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 3        | 1.21%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 1.21%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 1.21%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3        | 1.21%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 3        | 1.21%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 3        | 1.21%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 3        | 1.21%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3        | 1.21%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)               | 2        | 0.81%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 0.81%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 0.81%   |
| Nvidia MCP61 IDE                                                                        | 2        | 0.81%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 118      | 59%     |
| NVMe | 41       | 20.5%   |
| IDE  | 32       | 16%     |
| RAID | 7        | 3.5%    |
| SAS  | 1        | 0.5%    |
| SCSI | 1        | 0.5%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 94       | 70.15%  |
| AMD    | 40       | 29.85%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 4        | 2.99%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 3        | 2.24%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 3        | 2.24%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 3        | 2.24%   |
| Intel Core i7-5820K CPU @ 3.30GHz           | 2        | 1.49%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 1.49%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 2        | 1.49%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2        | 1.49%   |
| Intel Core i7 CPU 870 @ 2.93GHz             | 2        | 1.49%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 2        | 1.49%   |
| Intel Core i5-4690K CPU @ 3.50GHz           | 2        | 1.49%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 2        | 1.49%   |
| Intel Core i5-4570S CPU @ 2.90GHz           | 2        | 1.49%   |
| Intel Core i5-3350P CPU @ 3.10GHz           | 2        | 1.49%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 2        | 1.49%   |
| Intel 12th Gen Core i7-12700                | 2        | 1.49%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz      | 2        | 1.49%   |
| AMD Ryzen 9 7900X 12-Core Processor         | 2        | 1.49%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 2        | 1.49%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 2        | 1.49%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 2        | 1.49%   |
| AMD Athlon II X4 630 Processor              | 2        | 1.49%   |
| Intel Xeon W-2123 CPU @ 3.60GHz             | 1        | 0.75%   |
| Intel Xeon CPU W3565 @ 3.20GHz              | 1        | 0.75%   |
| Intel Xeon CPU E5520 @ 2.27GHz              | 1        | 0.75%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz         | 1        | 0.75%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz          | 1        | 0.75%   |
| Intel Pentium Gold G7400                    | 1        | 0.75%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 1        | 0.75%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1        | 0.75%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1        | 0.75%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz      | 1        | 0.75%   |
| Intel Pentium D CPU 2.80GHz                 | 1        | 0.75%   |
| Intel Pentium CPU 2030M @ 2.50GHz           | 1        | 0.75%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1        | 0.75%   |
| Intel Pentium 4 CPU 2.80GHz                 | 1        | 0.75%   |
| Intel Genuine CPU 2160 @ 1.80GHz            | 1        | 0.75%   |
| Intel Core M-5Y10c CPU @ 0.80GHz            | 1        | 0.75%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1        | 0.75%   |
| Intel Core i9-10850K CPU @ 3.60GHz          | 1        | 0.75%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 26       | 19.4%   |
| Intel Core i7           | 19       | 14.18%  |
| Intel Core i3           | 11       | 8.21%   |
| AMD Ryzen 5             | 10       | 7.46%   |
| Intel Core 2 Duo        | 8        | 5.97%   |
| Other                   | 7        | 5.22%   |
| AMD Ryzen 7             | 7        | 5.22%   |
| Intel Xeon              | 5        | 3.73%   |
| Intel Celeron           | 5        | 3.73%   |
| AMD Ryzen 9             | 3        | 2.24%   |
| AMD Phenom II X4        | 3        | 2.24%   |
| AMD FX                  | 3        | 2.24%   |
| AMD Athlon II X4        | 3        | 2.24%   |
| Intel Pentium Dual-Core | 2        | 1.49%   |
| Intel Pentium Dual      | 2        | 1.49%   |
| Intel Pentium 4         | 2        | 1.49%   |
| Intel Core i9           | 2        | 1.49%   |
| AMD Ryzen Threadripper  | 2        | 1.49%   |
| AMD Ryzen 3             | 2        | 1.49%   |
| AMD Phenom              | 2        | 1.49%   |
| Intel Pentium Gold      | 1        | 0.75%   |
| Intel Pentium D         | 1        | 0.75%   |
| Intel Pentium           | 1        | 0.75%   |
| Intel Genuine           | 1        | 0.75%   |
| Intel Core M            | 1        | 0.75%   |
| AMD Ryzen 5 PRO         | 1        | 0.75%   |
| AMD Phenom II X6        | 1        | 0.75%   |
| AMD Athlon              | 1        | 0.75%   |
| AMD A8                  | 1        | 0.75%   |
| AMD A4                  | 1        | 0.75%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 57       | 42.54%  |
| 2      | 33       | 24.63%  |
| 6      | 16       | 11.94%  |
| 8      | 13       | 9.7%    |
| 12     | 7        | 5.22%   |
| 1      | 3        | 2.24%   |
| 16     | 2        | 1.49%   |
| 10     | 2        | 1.49%   |
| 3      | 1        | 0.75%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 133      | 99.25%  |
| 2      | 1        | 0.75%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 72       | 53.73%  |
| 1      | 62       | 46.27%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 133      | 99.25%  |
| 32-bit         | 1        | 0.75%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 16       | 11.94%  |
| 0x306c3    | 15       | 11.19%  |
| 0x306a9    | 7        | 5.22%   |
| 0x206a7    | 7        | 5.22%   |
| 0x1067a    | 6        | 4.48%   |
| 0xa0653    | 4        | 2.99%   |
| 0x906ed    | 4        | 2.99%   |
| 0x6fd      | 4        | 2.99%   |
| 0x506e3    | 4        | 2.99%   |
| 0x106e5    | 4        | 2.99%   |
| 0x0800820d | 4        | 2.99%   |
| 0x0a601203 | 3        | 2.24%   |
| 0x08701021 | 3        | 2.24%   |
| 0x08108109 | 3        | 2.24%   |
| 0x010000db | 3        | 2.24%   |
| 0xa0671    | 2        | 1.49%   |
| 0x306f2    | 2        | 1.49%   |
| 0x20655    | 2        | 1.49%   |
| 0x0a20120a | 2        | 1.49%   |
| 0x010000dc | 2        | 1.49%   |
| 0x01000083 | 2        | 1.49%   |
| 0xf49      | 1        | 0.75%   |
| 0xf47      | 1        | 0.75%   |
| 0xf34      | 1        | 0.75%   |
| 0xb0671    | 1        | 0.75%   |
| 0xa0655    | 1        | 0.75%   |
| 0x906ea    | 1        | 0.75%   |
| 0x906e9    | 1        | 0.75%   |
| 0x906c0    | 1        | 0.75%   |
| 0x906a4    | 1        | 0.75%   |
| 0x90675    | 1        | 0.75%   |
| 0x90672    | 1        | 0.75%   |
| 0x806ea    | 1        | 0.75%   |
| 0x706a8    | 1        | 0.75%   |
| 0x706a1    | 1        | 0.75%   |
| 0x6f2      | 1        | 0.75%   |
| 0x506c9    | 1        | 0.75%   |
| 0x50654    | 1        | 0.75%   |
| 0x406c3    | 1        | 0.75%   |
| 0x40651    | 1        | 0.75%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 22       | 16.42%  |
| SandyBridge      | 9        | 6.72%   |
| K10              | 9        | 6.72%   |
| Zen+             | 8        | 5.97%   |
| Penryn           | 8        | 5.97%   |
| Unknown          | 8        | 5.97%   |
| KabyLake         | 7        | 5.22%   |
| IvyBridge        | 7        | 5.22%   |
| Zen 3            | 6        | 4.48%   |
| Skylake          | 6        | 4.48%   |
| Nehalem          | 6        | 4.48%   |
| Zen 2            | 5        | 3.73%   |
| Core             | 5        | 3.73%   |
| CometLake        | 5        | 3.73%   |
| Zen              | 3        | 2.24%   |
| NetBurst         | 3        | 2.24%   |
| Westmere         | 2        | 1.49%   |
| Icelake          | 2        | 1.49%   |
| Goldmont plus    | 2        | 1.49%   |
| Bulldozer        | 2        | 1.49%   |
| Alderlake Hybrid | 2        | 1.49%   |
| Tremont          | 1        | 0.75%   |
| Steamroller      | 1        | 0.75%   |
| Silvermont       | 1        | 0.75%   |
| Piledriver       | 1        | 0.75%   |
| K10 Llano        | 1        | 0.75%   |
| Goldmont         | 1        | 0.75%   |
| Broadwell        | 1        | 0.75%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 53       | 35.81%  |
| Intel  | 51       | 34.46%  |
| AMD    | 44       | 29.73%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 7        | 4.67%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 6        | 4%      |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 5        | 3.33%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 5        | 3.33%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 4        | 2.67%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 4        | 2.67%   |
| AMD Raphael                                                                 | 4        | 2.67%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 4        | 2.67%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 3        | 2%      |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3        | 2%      |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 2%      |
| Intel 82945G/GZ Integrated Graphics Controller                              | 3        | 2%      |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 2%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 2%      |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 3        | 2%      |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 1.33%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 1.33%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 1.33%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 1.33%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 2        | 1.33%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 2        | 1.33%   |
| Intel Skylake-S GT2 [HD Graphics 530]                                       | 2        | 1.33%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 2        | 1.33%   |
| Intel Core Processor Integrated Graphics Controller                         | 2        | 1.33%   |
| Intel Alder Lake-S GT1 [UHD Graphics 770]                                   | 2        | 1.33%   |
| AMD RS880 [Radeon HD 4200]                                                  | 2        | 1.33%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 2        | 1.33%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 1.33%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 1.33%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 0.67%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 0.67%   |
| Nvidia NV44A [GeForce 6200]                                                 | 1        | 0.67%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 0.67%   |
| Nvidia GP107GL [Quadro P620]                                                | 1        | 0.67%   |
| Nvidia GP107GL [Quadro P1000]                                               | 1        | 0.67%   |
| Nvidia GM107GL [Quadro K620]                                                | 1        | 0.67%   |
| Nvidia GK208 [GeForce GT 635]                                               | 1        | 0.67%   |
| Nvidia GK110 [GeForce GTX 780]                                              | 1        | 0.67%   |
| Nvidia GK107GL [Quadro K600]                                                | 1        | 0.67%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Nvidia   | 48       | 35.56%  |
| 1 x Intel    | 42       | 31.11%  |
| 1 x AMD      | 38       | 28.15%  |
| AMD + Nvidia | 5        | 3.7%    |
| Intel + AMD  | 2        | 1.48%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 98       | 73.13%  |
| Proprietary | 30       | 22.39%  |
| Unknown     | 6        | 4.48%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 51       | 37.78%  |
| 1.01-2.0   | 24       | 17.78%  |
| 3.01-4.0   | 14       | 10.37%  |
| 7.01-8.0   | 13       | 9.63%   |
| 0.51-1.0   | 13       | 9.63%   |
| 0.01-0.5   | 11       | 8.15%   |
| 8.01-16.0  | 6        | 4.44%   |
| 2.01-3.0   | 2        | 1.48%   |
| 5.01-6.0   | 1        | 0.74%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 19       | 13.38%  |
| Dell                 | 15       | 10.56%  |
| Acer                 | 15       | 10.56%  |
| AOC                  | 11       | 7.75%   |
| Hewlett-Packard      | 9        | 6.34%   |
| Goldstar             | 8        | 5.63%   |
| Philips              | 7        | 4.93%   |
| Sony                 | 6        | 4.23%   |
| BenQ                 | 6        | 4.23%   |
| Ancor Communications | 6        | 4.23%   |
| ViewSonic            | 4        | 2.82%   |
| Fujitsu Siemens      | 4        | 2.82%   |
| Medion               | 3        | 2.11%   |
| Lenovo               | 3        | 2.11%   |
| Iiyama               | 3        | 2.11%   |
| Eizo                 | 3        | 2.11%   |
| Vestel Elektronik    | 2        | 1.41%   |
| MSI                  | 2        | 1.41%   |
| ASUSTek Computer     | 2        | 1.41%   |
| Xiaomi               | 1        | 0.7%    |
| Vizio                | 1        | 0.7%    |
| Sangyo               | 1        | 0.7%    |
| SAC                  | 1        | 0.7%    |
| RTK                  | 1        | 0.7%    |
| Panasonic            | 1        | 0.7%    |
| NEC Computers        | 1        | 0.7%    |
| MiTAC                | 1        | 0.7%    |
| LG Electronics       | 1        | 0.7%    |
| Hitachi              | 1        | 0.7%    |
| HannStar             | 1        | 0.7%    |
| Grundig              | 1        | 0.7%    |
| Gigabyte Technology  | 1        | 0.7%    |
| CTV                  | 1        | 0.7%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| ViewSonic VX1935wm-3 VSCB81E 1440x900 410x256mm 19.0-inch             | 2        | 1.34%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 880x500mm 39.8-inch  | 2        | 1.34%   |
| Sony SDM-M81 SNY0480 1280x1024 359x287mm 18.1-inch                    | 2        | 1.34%   |
| Samsung Electronics C32JG5x SAM0FE0 2560x1440 697x392mm 31.5-inch     | 2        | 1.34%   |
| MSI G27C6 MSI5CA9 1920x1080 598x336mm 27.0-inch                       | 2        | 1.34%   |
| Medion MD22322 MEB8101 2560x1440 699x393mm 31.6-inch                  | 2        | 1.34%   |
| Fujitsu Siemens B22W-7 LED FUS0838 1680x1050 474x296mm 22.0-inch      | 2        | 1.34%   |
| AOC 24G2W1G3 AOC2402 1920x1080 527x296mm 23.8-inch                    | 2        | 1.34%   |
| Xiaomi Mi TV XMD004A 3840x2160 708x398mm 32.0-inch                    | 1        | 0.67%   |
| Vizio E260MV VIZ0062 1920x1080 509x286mm 23.0-inch                    | 1        | 0.67%   |
| ViewSonic VX2433wm VSC3822 1920x1080 520x290mm 23.4-inch              | 1        | 0.67%   |
| ViewSonic VA2012wSERIES VSC6A1C 1680x1050 433x271mm 20.1-inch         | 1        | 0.67%   |
| Sony TV SNY0801 1360x768                                              | 1        | 0.67%   |
| Sony TV *30 SNY7105 3840x2160 1218x685mm 55.0-inch                    | 1        | 0.67%   |
| Sony SDM-HS74P SNY3170 1280x1024 338x270mm 17.0-inch                  | 1        | 0.67%   |
| Sony SDM-HS53 SNY2250 1024x768 304x228mm 15.0-inch                    | 1        | 0.67%   |
| Sangyo LCD Monitor M27A3 1920x1080                                    | 1        | 0.67%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch     | 1        | 0.67%   |
| Samsung Electronics U28H75x SAM0DFE 3840x2160 608x345mm 27.5-inch     | 1        | 0.67%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 1        | 0.67%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                      | 1        | 0.67%   |
| Samsung Electronics SyncMaster SAM0594 1680x1050 459x296mm 21.5-inch  | 1        | 0.67%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch  | 1        | 0.67%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch   | 1        | 0.67%   |
| Samsung Electronics SyncMaster SAM0286 1280x720 372x209mm 16.8-inch   | 1        | 0.67%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch  | 1        | 0.67%   |
| Samsung Electronics SyncMaster SAM0117 1280x1024 312x234mm 15.4-inch  | 1        | 0.67%   |
| Samsung Electronics SMB2030 SAM063C 1600x900 443x249mm 20.0-inch      | 1        | 0.67%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1        | 0.67%   |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x287mm 23.0-inch     | 1        | 0.67%   |
| Samsung Electronics LCD Monitor SMT24A550                             | 1        | 0.67%   |
| Samsung Electronics LCD Monitor SAM0DF6 3840x2160 890x500mm 40.2-inch | 1        | 0.67%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 1        | 0.67%   |
| Samsung Electronics LCD Monitor C32R50x 3840x1080                     | 1        | 0.67%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 1        | 0.67%   |
| SAC DP SAC2700 1920x1080 600x330mm 27.0-inch                          | 1        | 0.67%   |
| RTK FHD HDR RTKBC32 1920x1080 597x336mm 27.0-inch                     | 1        | 0.67%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch              | 1        | 0.67%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch              | 1        | 0.67%   |
| Philips PHL 271E1 PHLC208 1920x1080 598x336mm 27.0-inch               | 1        | 0.67%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 59       | 42.45%  |
| 3840x2160 (4K)     | 15       | 10.79%  |
| 2560x1440 (QHD)    | 14       | 10.07%  |
| 1680x1050 (WSXGA+) | 12       | 8.63%   |
| 1280x1024 (SXGA)   | 11       | 7.91%   |
| 1366x768 (WXGA)    | 6        | 4.32%   |
| 1440x900 (WXGA+)   | 5        | 3.6%    |
| 3440x1440          | 3        | 2.16%   |
| 1920x1200 (WUXGA)  | 2        | 1.44%   |
| 1600x900 (HD+)     | 2        | 1.44%   |
| 1360x768           | 2        | 1.44%   |
| 1280x720 (HD)      | 2        | 1.44%   |
| Unknown            | 2        | 1.44%   |
| 3840x1080          | 1        | 0.72%   |
| 2560x1080          | 1        | 0.72%   |
| 1920x1440          | 1        | 0.72%   |
| 1024x768 (XGA)     | 1        | 0.72%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 21       | 14.89%  |
| 23      | 19       | 13.48%  |
| 24      | 18       | 12.77%  |
| 21      | 13       | 9.22%   |
| 31      | 11       | 7.8%    |
| 22      | 11       | 7.8%    |
| 19      | 7        | 4.96%   |
| Unknown | 7        | 4.96%   |
| 18      | 6        | 4.26%   |
| 17      | 6        | 4.26%   |
| 34      | 4        | 2.84%   |
| 84      | 3        | 2.13%   |
| 15      | 3        | 2.13%   |
| 54      | 2        | 1.42%   |
| 20      | 2        | 1.42%   |
| 75      | 1        | 0.71%   |
| 72      | 1        | 0.71%   |
| 65      | 1        | 0.71%   |
| 61      | 1        | 0.71%   |
| 52      | 1        | 0.71%   |
| 40      | 1        | 0.71%   |
| 26      | 1        | 0.71%   |
| 16      | 1        | 0.71%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 53       | 38.41%  |
| 401-500     | 34       | 24.64%  |
| 601-700     | 14       | 10.14%  |
| 301-350     | 8        | 5.8%    |
| 351-400     | 7        | 5.07%   |
| Unknown     | 7        | 5.07%   |
| 1501-2000   | 5        | 3.62%   |
| 1001-1500   | 5        | 3.62%   |
| 701-800     | 4        | 2.9%    |
| 801-900     | 1        | 0.72%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 88       | 66.17%  |
| 16/10   | 21       | 15.79%  |
| 5/4     | 10       | 7.52%   |
| Unknown | 6        | 4.51%   |
| 21/9    | 4        | 3.01%   |
| 4/3     | 3        | 2.26%   |
| 3/2     | 1        | 0.75%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 46       | 33.33%  |
| 301-350        | 21       | 15.22%  |
| 151-200        | 18       | 13.04%  |
| 351-500        | 15       | 10.87%  |
| More than 1000 | 10       | 7.25%   |
| 251-300        | 8        | 5.8%    |
| 141-150        | 8        | 5.8%    |
| Unknown        | 7        | 5.07%   |
| 121-130        | 1        | 0.72%   |
| 111-120        | 1        | 0.72%   |
| 101-110        | 1        | 0.72%   |
| 501-1000       | 1        | 0.72%   |
| 91-100         | 1        | 0.72%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 90       | 66.67%  |
| 101-120 | 23       | 17.04%  |
| 1-50    | 8        | 5.93%   |
| Unknown | 7        | 5.19%   |
| 121-160 | 6        | 4.44%   |
| 161-240 | 1        | 0.74%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 108      | 80.6%   |
| 2     | 20       | 14.93%  |
| 0     | 4        | 2.99%   |
| 3     | 2        | 1.49%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 81       | 39.51%  |
| Intel                           | 60       | 29.27%  |
| Qualcomm Atheros                | 14       | 6.83%   |
| Ralink Technology               | 7        | 3.41%   |
| MediaTek                        | 7        | 3.41%   |
| TP-Link                         | 6        | 2.93%   |
| Broadcom Limited                | 5        | 2.44%   |
| Broadcom                        | 3        | 1.46%   |
| Ralink                          | 2        | 0.98%   |
| OPPO Electronics                | 2        | 0.98%   |
| Nvidia                          | 2        | 0.98%   |
| Microsoft                       | 2        | 0.98%   |
| Linksys                         | 2        | 0.98%   |
| Xiaomi                          | 1        | 0.49%   |
| VIA Technologies                | 1        | 0.49%   |
| Samsung Electronics             | 1        | 0.49%   |
| Qualcomm Atheros Communications | 1        | 0.49%   |
| Mercucys                        | 1        | 0.49%   |
| JMicron Technology              | 1        | 0.49%   |
| IMC Networks                    | 1        | 0.49%   |
| Edimax Technology               | 1        | 0.49%   |
| D-Link System                   | 1        | 0.49%   |
| D-Link                          | 1        | 0.49%   |
| AVM                             | 1        | 0.49%   |
| Aquantia                        | 1        | 0.49%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 57       | 24.78%  |
| Intel Ethernet Controller I225-V                                       | 9        | 3.91%   |
| Realtek RTL8125 2.5GbE Controller                                      | 8        | 3.48%   |
| Ralink MT7601U Wireless Adapter                                        | 5        | 2.17%   |
| Intel I211 Gigabit Network Connection                                  | 5        | 2.17%   |
| Intel Ethernet Connection I217-LM                                      | 5        | 2.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 5        | 2.17%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 5        | 2.17%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 4        | 1.74%   |
| Intel Ethernet Connection (2) I219-V                                   | 4        | 1.74%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 3        | 1.3%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 3        | 1.3%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 3        | 1.3%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 3        | 1.3%    |
| Qualcomm Atheros Attansic L2 Fast Ethernet                             | 3        | 1.3%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 3        | 1.3%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 3        | 1.3%    |
| Intel Wi-Fi 6 AX200                                                    | 3        | 1.3%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 3        | 1.3%    |
| Intel Ethernet Connection I217-V                                       | 3        | 1.3%    |
| Intel Ethernet Connection (2) I218-V                                   | 3        | 1.3%    |
| Intel Ethernet Connection (14) I219-V                                  | 3        | 1.3%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 2        | 0.87%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                 | 2        | 0.87%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                        | 2        | 0.87%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2        | 0.87%   |
| Realtek 802.11ac NIC                                                   | 2        | 0.87%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 2        | 0.87%   |
| OPPO Ace 3V                                                            | 2        | 0.87%   |
| Nvidia MCP61 Ethernet                                                  | 2        | 0.87%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 2        | 0.87%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 2        | 0.87%   |
| Intel 82578DM Gigabit Network Connection                               | 2        | 0.87%   |
| Intel 82578DC Gigabit Network Connection                               | 2        | 0.87%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 2        | 0.87%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1        | 0.43%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 1        | 0.43%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                  | 1        | 0.43%   |
| TP-Link 802.11n NIC                                                    | 1        | 0.43%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 23       | 28.05%  |
| Intel                           | 16       | 19.51%  |
| Ralink Technology               | 7        | 8.54%   |
| Qualcomm Atheros                | 7        | 8.54%   |
| MediaTek                        | 7        | 8.54%   |
| TP-Link                         | 6        | 7.32%   |
| Ralink                          | 2        | 2.44%   |
| Microsoft                       | 2        | 2.44%   |
| Linksys                         | 2        | 2.44%   |
| Broadcom Limited                | 2        | 2.44%   |
| Qualcomm Atheros Communications | 1        | 1.22%   |
| Mercucys                        | 1        | 1.22%   |
| IMC Networks                    | 1        | 1.22%   |
| Edimax Technology               | 1        | 1.22%   |
| D-Link System                   | 1        | 1.22%   |
| D-Link                          | 1        | 1.22%   |
| Broadcom                        | 1        | 1.22%   |
| AVM                             | 1        | 1.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                                | 5        | 6.02%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                  | 4        | 4.82%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                             | 3        | 3.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 3        | 3.61%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 3        | 3.61%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                               | 3        | 3.61%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                      | 3        | 3.61%   |
| Intel Wi-Fi 6 AX200                                                            | 3        | 3.61%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                        | 3        | 3.61%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                   | 2        | 2.41%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                         | 2        | 2.41%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                | 2        | 2.41%   |
| Realtek 802.11ac NIC                                                           | 2        | 2.41%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                        | 2        | 2.41%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 2        | 2.41%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                          | 1        | 1.2%    |
| TP-Link 802.11n NIC                                                            | 1        | 1.2%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                    | 1        | 1.2%    |
| Realtek RTL8821CE PCIe 802.11ac Wireless Network Controller                    | 1        | 1.2%    |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                            | 1        | 1.2%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                        | 1        | 1.2%    |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                | 1        | 1.2%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 1        | 1.2%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 1        | 1.2%    |
| Realtek RTL8188EE Wireless Network Adapter                                     | 1        | 1.2%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1        | 1.2%    |
| Realtek 802.11ax WLAN Adapter                                                  | 1        | 1.2%    |
| Realtek 802.11ac WLAN Adapter                                                  | 1        | 1.2%    |
| Ralink RT3572 Wireless Adapter                                                 | 1        | 1.2%    |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 1        | 1.2%    |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                      | 1        | 1.2%    |
| Ralink RT2561/RT61 802.11g PCI                                                 | 1        | 1.2%    |
| Qualcomm Atheros AR9271 802.11n                                                | 1        | 1.2%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                               | 1        | 1.2%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 1        | 1.2%    |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 1        | 1.2%    |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]  | 1        | 1.2%    |
| Microsoft Xbox Wireless Adapter for Windows                                    | 1        | 1.2%    |
| Microsoft Xbox 360 Wireless Adapter                                            | 1        | 1.2%    |
| Mercucys MW300UM RTL8192EU wifi                                                | 1        | 1.2%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 68       | 47.22%  |
| Intel                 | 55       | 38.19%  |
| Qualcomm Atheros      | 7        | 4.86%   |
| Broadcom Limited      | 3        | 2.08%   |
| OPPO Electronics      | 2        | 1.39%   |
| Nvidia                | 2        | 1.39%   |
| Broadcom              | 2        | 1.39%   |
| Xiaomi                | 1        | 0.69%   |
| VIA Technologies      | 1        | 0.69%   |
| Samsung Electronics   | 1        | 0.69%   |
| JMicron Technology    | 1        | 0.69%   |
| Aquantia              | 1        | 0.69%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 57       | 38.78%  |
| Intel Ethernet Controller I225-V                                               | 9        | 6.12%   |
| Realtek RTL8125 2.5GbE Controller                                              | 8        | 5.44%   |
| Intel I211 Gigabit Network Connection                                          | 5        | 3.4%    |
| Intel Ethernet Connection I217-LM                                              | 5        | 3.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 5        | 3.4%    |
| Intel 82567LM-3 Gigabit Network Connection                                     | 5        | 3.4%    |
| Intel Ethernet Connection (2) I219-V                                           | 4        | 2.72%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 3        | 2.04%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                     | 3        | 2.04%   |
| Intel Ethernet Connection I217-V                                               | 3        | 2.04%   |
| Intel Ethernet Connection (2) I218-V                                           | 3        | 2.04%   |
| Intel Ethernet Connection (14) I219-V                                          | 3        | 2.04%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2        | 1.36%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2        | 1.36%   |
| OPPO Ace 3V                                                                    | 2        | 1.36%   |
| Nvidia MCP61 Ethernet                                                          | 2        | 1.36%   |
| Intel 82578DM Gigabit Network Connection                                       | 2        | 1.36%   |
| Intel 82578DC Gigabit Network Connection                                       | 2        | 1.36%   |
| Intel 82566DM-2 Gigabit Network Connection                                     | 2        | 1.36%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1        | 0.68%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 1        | 0.68%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1        | 0.68%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1        | 0.68%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1        | 0.68%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1        | 0.68%   |
| Intel NM10/ICH7 Family LAN Controller                                          | 1        | 0.68%   |
| Intel I210 Gigabit Network Connection                                          | 1        | 0.68%   |
| Intel Ethernet Connection I218-V                                               | 1        | 0.68%   |
| Intel Ethernet Connection (7) I219-V                                           | 1        | 0.68%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1        | 0.68%   |
| Intel Ethernet Connection (17) I219-V                                          | 1        | 0.68%   |
| Intel Ethernet Connection (17) I219-LM                                         | 1        | 0.68%   |
| Intel Alder Lake-S PCH CNVi WiFi                                               | 1        | 0.68%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 1        | 0.68%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 1        | 0.68%   |
| Broadcom Limited NetXtreme BCM5782 Gigabit Ethernet                            | 1        | 0.68%   |
| Broadcom Limited NetXtreme BCM5754 Gigabit Ethernet PCI Express                | 1        | 0.68%   |
| Broadcom Limited NetXtreme BCM5722 Gigabit Ethernet PCI Express                | 1        | 0.68%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 1        | 0.68%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 133      | 65.52%  |
| WiFi     | 70       | 34.48%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 93       | 66.43%  |
| WiFi     | 47       | 33.57%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 83       | 61.94%  |
| 2     | 45       | 33.58%  |
| 3     | 6        | 4.48%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 97       | 72.39%  |
| Yes  | 37       | 27.61%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 14       | 31.82%  |
| Cambridge Silicon Radio | 8        | 18.18%  |
| Realtek Semiconductor   | 5        | 11.36%  |
| MediaTek                | 5        | 11.36%  |
| Broadcom                | 4        | 9.09%   |
| Foxconn / Hon Hai       | 3        | 6.82%   |
| TP-Link                 | 2        | 4.55%   |
| ASUSTek Computer        | 2        | 4.55%   |
| Apple                   | 1        | 2.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 8        | 18.18%  |
| Realtek Bluetooth Radio                               | 5        | 11.36%  |
| MediaTek Wireless_Device                              | 5        | 11.36%  |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 4        | 9.09%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 3        | 6.82%   |
| Intel Bluetooth wireless interface                    | 3        | 6.82%   |
| Intel AX200 Bluetooth                                 | 3        | 6.82%   |
| Foxconn / Hon Hai Bluetooth Device                    | 3        | 6.82%   |
| TP-Link TP-T@- UB500 Adapter                          | 2        | 4.55%   |
| Intel AX210 Bluetooth                                 | 2        | 4.55%   |
| Intel Wireless-AC 3168 Bluetooth                      | 1        | 2.27%   |
| Intel Bluetooth Device                                | 1        | 2.27%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 1        | 2.27%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 1        | 2.27%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 2.27%   |
| Apple Bluetooth Host Controller                       | 1        | 2.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 91       | 39.39%  |
| AMD                     | 54       | 23.38%  |
| Nvidia                  | 47       | 20.35%  |
| C-Media Electronics     | 8        | 3.46%   |
| Creative Labs           | 5        | 2.16%   |
| VIA Technologies        | 2        | 0.87%   |
| Texas Instruments       | 2        | 0.87%   |
| ROCCAT                  | 2        | 0.87%   |
| JMTek                   | 2        | 0.87%   |
| GYROCOM C&C             | 2        | 0.87%   |
| Generalplus Technology  | 2        | 0.87%   |
| TerraTec Electronic     | 1        | 0.43%   |
| Tenx Technology         | 1        | 0.43%   |
| Setek Elektronik        | 1        | 0.43%   |
| Schiit Audio            | 1        | 0.43%   |
| Razer USA               | 1        | 0.43%   |
| M-Audio                 | 1        | 0.43%   |
| Kingston Technology     | 1        | 0.43%   |
| Jieli Technology        | 1        | 0.43%   |
| GN Netcom               | 1        | 0.43%   |
| Giga-Byte Technology    | 1        | 0.43%   |
| Ensoniq                 | 1        | 0.43%   |
| Digidesign              | 1        | 0.43%   |
| Cambridge Silicon Radio | 1        | 0.43%   |
| BEHRINGER International | 1        | 0.43%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                           | Desktops | Percent |
|-------------------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                             | 13       | 4.87%   |
| AMD Ryzen HD Audio Controller                                                                   | 12       | 4.49%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                | 10       | 3.75%   |
| AMD SBx00 Azalia (Intel HDA)                                                                    | 10       | 3.75%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                      | 9        | 3.37%   |
| Nvidia GP107GL High Definition Audio Controller                                                 | 7        | 2.62%   |
| AMD Starship/Matisse HD Audio Controller                                                        | 7        | 2.62%   |
| Nvidia GP104 High Definition Audio Controller                                                   | 6        | 2.25%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                         | 6        | 2.25%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                             | 6        | 2.25%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                        | 6        | 2.25%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                             | 6        | 2.25%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                      | 6        | 2.25%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                             | 5        | 1.87%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                             | 5        | 1.87%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                         | 5        | 1.87%   |
| Nvidia GP108 High Definition Audio Controller                                                   | 4        | 1.5%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                   | 4        | 1.5%    |
| Intel Cannon Lake PCH cAVS                                                                      | 4        | 1.5%    |
| Intel Alder Lake-S HD Audio Controller                                                          | 4        | 1.5%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                 | 4        | 1.5%    |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                               | 4        | 1.5%    |
| AMD Radeon High Definition Audio Controller                                                     | 4        | 1.5%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                           | 3        | 1.12%   |
| Intel Smart Sound Technology (SST) Audio Controller                                             | 3        | 1.12%   |
| Intel C610/X99 series chipset HD Audio Controller                                               | 3        | 1.12%   |
| Intel 9 Series Chipset Family HD Audio Controller                                               | 3        | 1.12%   |
| Intel 200 Series PCH HD Audio                                                                   | 3        | 1.12%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 3        | 1.12%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                     | 3        | 1.12%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                         | 3        | 1.12%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                          | 3        | 1.12%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]               | 3        | 1.12%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                    | 3        | 1.12%   |
| Texas Instruments PCM2902 Audio Codec                                                           | 2        | 0.75%   |
| ROCCAT ROCCAT Khan AIMO                                                                         | 2        | 0.75%   |
| Nvidia TU104 HD Audio Controller                                                                | 2        | 0.75%   |
| Nvidia MCP61 High Definition Audio                                                              | 2        | 0.75%   |
| Nvidia GM206 High Definition Audio Controller                                                   | 2        | 0.75%   |
| Nvidia GK107 HDMI Audio Controller                                                              | 2        | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 22       | 14.47%  |
| Kingston            | 22       | 14.47%  |
| Samsung Electronics | 19       | 12.5%   |
| Corsair             | 18       | 11.84%  |
| SK hynix            | 11       | 7.24%   |
| G.Skill             | 10       | 6.58%   |
| Crucial             | 10       | 6.58%   |
| Ramaxel Technology  | 7        | 4.61%   |
| A-DATA Technology   | 7        | 4.61%   |
| Nanya Technology    | 6        | 3.95%   |
| Unknown (ABCD)      | 3        | 1.97%   |
| Micron Technology   | 3        | 1.97%   |
| Transcend           | 2        | 1.32%   |
| Unknown             | 2        | 1.32%   |
| Unknown (AB)        | 1        | 0.66%   |
| Unknown (0x0E9D)    | 1        | 0.66%   |
| Unifosa             | 1        | 0.66%   |
| Patriot             | 1        | 0.66%   |
| Lexar Co Limited    | 1        | 0.66%   |
| Golden Empire       | 1        | 0.66%   |
| Elpida              | 1        | 0.66%   |
| CSX                 | 1        | 0.66%   |
| Avant               | 1        | 0.66%   |
| Apacer              | 1        | 0.66%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 4        | 2.45%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2133MT/s   | 3        | 1.84%   |
| Unknown RAM Module 4GB DIMM SDRAM                                | 2        | 1.23%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                         | 2        | 1.23%   |
| Unknown RAM Module 2GB DIMM 667MT/s                              | 2        | 1.23%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2        | 1.23%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s             | 2        | 1.23%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s              | 2        | 1.23%   |
| Kingston RAM 9905471-006.A00LF 4GB DIMM DDR3 1333MT/s            | 2        | 1.23%   |
| G.Skill RAM F4-4000C18-16GTZR 16GB DIMM DDR4 2667MT/s            | 2        | 1.23%   |
| Crucial RAM BLS8G4D32AESBK.M8FE1 8GB DIMM DDR4 3600MT/s          | 2        | 1.23%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1800MT/s            | 2        | 1.23%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM SDRAM 1800MT/s             | 2        | 1.23%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3800MT/s           | 2        | 1.23%   |
| Unknown                                                          | 2        | 1.23%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 1        | 0.61%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 1        | 0.61%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1        | 0.61%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                        | 1        | 0.61%   |
| Unknown RAM Module 4GB DIMM DDR2 533MT/s                         | 1        | 0.61%   |
| Unknown RAM Module 4GB DIMM 667MT/s                              | 1        | 0.61%   |
| Unknown RAM Module 4GB DIMM                                      | 1        | 0.61%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 1        | 0.61%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 1        | 0.61%   |
| Unknown RAM Module 2GB DIMM DDR2 1067MT/s                        | 1        | 0.61%   |
| Unknown RAM Module 2GB DIMM DDR2                                 | 1        | 0.61%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 1        | 0.61%   |
| Unknown RAM Module 2GB DIMM 1600MT/s                             | 1        | 0.61%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 1        | 0.61%   |
| Unknown RAM Module 1GB DIMM SDRAM                                | 1        | 0.61%   |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s                         | 1        | 0.61%   |
| Unknown (AB) RAM Module 2GB DIMM LPDDR3 1333MT/s                 | 1        | 0.61%   |
| Unknown (0x0E9D) RAM KINSOTIN8GB2666MHZ 8GB SODIMM DDR4 2667MT/s | 1        | 0.61%   |
| Unifosa RAM Module 2GB DIMM DDR3 1333MT/s                        | 1        | 0.61%   |
| Transcend RAM JM800QLU-2G 2GB DIMM DDR2 2048MT/s                 | 1        | 0.61%   |
| Transcend RAM JM1333KLN-8GK 4GB DIMM DDR3 1333MT/s               | 1        | 0.61%   |
| SK hynix RAM HMT451U6AFR8A-PB 4GB DIMM DDR3 1600MT/s             | 1        | 0.61%   |
| SK hynix RAM HMT41GU6MFR8C 8GB DIMM DDR3 1866MT/s                | 1        | 0.61%   |
| SK hynix RAM HMT41GU6BFR8C-PB 8GB DIMM DDR3 1600MT/s             | 1        | 0.61%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1        | 0.61%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 52       | 37.14%  |
| DDR3    | 47       | 33.57%  |
| SDRAM   | 12       | 8.57%   |
| DDR2    | 10       | 7.14%   |
| Unknown | 9        | 6.43%   |
| DDR5    | 5        | 3.57%   |
| LPDDR4  | 3        | 2.14%   |
| LPDDR3  | 1        | 0.71%   |
| DDR     | 1        | 0.71%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 119      | 90.15%  |
| SODIMM | 13       | 9.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 39       | 27.27%  |
| 8192  | 34       | 23.78%  |
| 16384 | 28       | 19.58%  |
| 2048  | 26       | 18.18%  |
| 32768 | 8        | 5.59%   |
| 1024  | 7        | 4.9%    |
| 256   | 1        | 0.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 24       | 16.55%  |
| 1333    | 21       | 14.48%  |
| 3200    | 14       | 9.66%   |
| 3600    | 13       | 8.97%   |
| 2400    | 8        | 5.52%   |
| 2667    | 7        | 4.83%   |
| Unknown | 6        | 4.14%   |
| 1800    | 5        | 3.45%   |
| 800     | 5        | 3.45%   |
| 667     | 5        | 3.45%   |
| 6000    | 3        | 2.07%   |
| 3000    | 3        | 2.07%   |
| 3800    | 2        | 1.38%   |
| 3733    | 2        | 1.38%   |
| 2666    | 2        | 1.38%   |
| 2133    | 2        | 1.38%   |
| 2048    | 2        | 1.38%   |
| 1866    | 2        | 1.38%   |
| 1067    | 2        | 1.38%   |
| 533     | 2        | 1.38%   |
| 333     | 2        | 1.38%   |
| 8400    | 1        | 0.69%   |
| 5800    | 1        | 0.69%   |
| 4800    | 1        | 0.69%   |
| 4133    | 1        | 0.69%   |
| 3866    | 1        | 0.69%   |
| 3266    | 1        | 0.69%   |
| 3066    | 1        | 0.69%   |
| 2933    | 1        | 0.69%   |
| 2200    | 1        | 0.69%   |
| 2000    | 1        | 0.69%   |
| 1867    | 1        | 0.69%   |
| 1066    | 1        | 0.69%   |
| 400     | 1        | 0.69%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 3        | 42.86%  |
| Hewlett-Packard    | 2        | 28.57%  |
| Brother Industries | 2        | 28.57%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model               | Desktops | Percent |
|---------------------|----------|---------|
| Canon MF641C        | 2        | 28.57%  |
| HP ENVY 4500 series | 1        | 14.29%  |
| HP Deskjet 1510     | 1        | 14.29%  |
| Canon MG5700 series | 1        | 14.29%  |
| Brother Printer     | 1        | 14.29%  |
| Brother MFC-7340    | 1        | 14.29%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 2        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 1        | 50%     |
| Canon CanoScan LiDE 210            | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 11       | 37.93%  |
| Microdia                      | 4        | 13.79%  |
| Sunplus Innovation Technology | 3        | 10.34%  |
| Microsoft                     | 3        | 10.34%  |
| Chicony Electronics           | 2        | 6.9%    |
| Sonix Technology              | 1        | 3.45%   |
| Pixart Imaging                | 1        | 3.45%   |
| Hewlett-Packard               | 1        | 3.45%   |
| Generalplus Technology        | 1        | 3.45%   |
| Cubeternet                    | 1        | 3.45%   |
| Arkmicro Technologies         | 1        | 3.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Logitech Webcam C270                 | 4        | 13.79%  |
| Logitech Webcam C930e                | 3        | 10.34%  |
| Sunplus Full HD webcam               | 2        | 6.9%    |
| Microsoft LifeCam HD-3000            | 2        | 6.9%    |
| Sunplus Aukey-PC-LM1E Camera         | 1        | 3.45%   |
| Sonix USB Camera                     | 1        | 3.45%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro | 1        | 3.45%   |
| Microsoft LifeCam VX-500 [1357]      | 1        | 3.45%   |
| Microdia USB 2.0 Camera              | 1        | 3.45%   |
| Microdia Sonix USB 2.0 Camera        | 1        | 3.45%   |
| Microdia Integrated Camera           | 1        | 3.45%   |
| Microdia Camera                      | 1        | 3.45%   |
| Logitech Webcam C600                 | 1        | 3.45%   |
| Logitech Webcam C310                 | 1        | 3.45%   |
| Logitech Webcam C110                 | 1        | 3.45%   |
| Logitech HD Webcam C615              | 1        | 3.45%   |
| HP Webcam HD 2300                    | 1        | 3.45%   |
| Generalplus GENERAL WEBCAM           | 1        | 3.45%   |
| Cubeternet USB2.0 Camera             | 1        | 3.45%   |
| Chicony HP Prem AF Webcam KQ245AA    | 1        | 3.45%   |
| Chicony HD Webcam                    | 1        | 3.45%   |
| Arkmicro USB2.0 PC CAMERA            | 1        | 3.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor    | Desktops | Percent |
|-----------|----------|---------|
| Microsoft | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                        | Desktops | Percent |
|------------------------------|----------|---------|
| Microsoft Fingerprint Reader | 1        | 100%    |

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
| 0     | 111      | 82.84%  |
| 1     | 20       | 14.93%  |
| 2     | 2        | 1.49%   |
| 3     | 1        | 0.75%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 9        | 36%     |
| Net/wireless             | 7        | 28%     |
| Unassigned class         | 3        | 12%     |
| Communication controller | 3        | 12%     |
| Fingerprint reader       | 1        | 4%      |
| Dvb card                 | 1        | 4%      |
| Card reader              | 1        | 4%      |

