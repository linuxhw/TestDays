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

Total: 162

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| 5.10.0-21-amd64            | 14       | 10.61%  |
| 5.10.0-20-amd64            | 13       | 9.85%   |
| 6.0.0-6mx-amd64            | 12       | 9.09%   |
| 5.14.0-4mx-amd64           | 7        | 5.3%    |
| 5.10.0-23-amd64            | 7        | 5.3%    |
| 5.10.0-18-amd64            | 7        | 5.3%    |
| 5.10.0-19-amd64            | 6        | 4.55%   |
| 5.10.0-13-amd64            | 5        | 3.79%   |
| 6.0.0-10.1-liquorix-amd64  | 4        | 3.03%   |
| 5.18.0-4mx-amd64           | 4        | 3.03%   |
| 5.10.0-16-amd64            | 4        | 3.03%   |
| 5.10.0-15-amd64            | 4        | 3.03%   |
| 5.16.0-5mx-amd64           | 3        | 2.27%   |
| 5.14.0-3mx-amd64           | 2        | 1.52%   |
| 5.10.0-9-amd64             | 2        | 1.52%   |
| 5.10.0-28-amd64            | 2        | 1.52%   |
| 5.10.0-11-amd64            | 2        | 1.52%   |
| 6.7.12-1-liquorix-amd64    | 1        | 0.76%   |
| 6.5.9-2-liquorix-amd64     | 1        | 0.76%   |
| 6.5.0-5mx-ahs-amd64        | 1        | 0.76%   |
| 6.2.14-1-liquorix-amd64    | 1        | 0.76%   |
| 6.1.15-2-liquorix-amd64    | 1        | 0.76%   |
| 6.1.0-2mx-amd64            | 1        | 0.76%   |
| 6.0.5-x64v1-xanmod1        | 1        | 0.76%   |
| 6.0.0-4mx-rt-amd64         | 1        | 0.76%   |
| 6.0.0-13.3-liquorix-amd64  | 1        | 0.76%   |
| 5.19.0-4.2-liquorix-amd64  | 1        | 0.76%   |
| 5.19.0-2mx-amd64           | 1        | 0.76%   |
| 5.19.0-17.2-liquorix-amd64 | 1        | 0.76%   |
| 5.19.0-14.1-liquorix-amd64 | 1        | 0.76%   |
| 5.17.0-3mx-amd64           | 1        | 0.76%   |
| 5.17.0-2mx-amd64           | 1        | 0.76%   |
| 5.16.0-rc5-hwmon-next+     | 1        | 0.76%   |
| 5.16.0-6mx-amd64           | 1        | 0.76%   |
| 5.15.0-2-amd64             | 1        | 0.76%   |
| 5.15.0-0.bpo.2-amd64       | 1        | 0.76%   |
| 5.14.0-2mx-amd64           | 1        | 0.76%   |
| 5.10.52-antix.1-amd64-smp  | 1        | 0.76%   |
| 5.10.113-lkdtm-i386pae     | 1        | 0.76%   |
| 5.10.111-tkg-cfs           | 1        | 0.76%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.10.0   | 74       | 56.92%  |
| 6.0.0    | 18       | 13.85%  |
| 5.14.0   | 10       | 7.69%   |
| 5.16.0   | 5        | 3.85%   |
| 5.19.0   | 4        | 3.08%   |
| 5.18.0   | 4        | 3.08%   |
| 5.17.0   | 2        | 1.54%   |
| 5.15.0   | 2        | 1.54%   |
| 6.7.12   | 1        | 0.77%   |
| 6.5.9    | 1        | 0.77%   |
| 6.5.0    | 1        | 0.77%   |
| 6.2.14   | 1        | 0.77%   |
| 6.1.15   | 1        | 0.77%   |
| 6.1.0    | 1        | 0.77%   |
| 6.0.5    | 1        | 0.77%   |
| 5.10.52  | 1        | 0.77%   |
| 5.10.113 | 1        | 0.77%   |
| 5.10.111 | 1        | 0.77%   |
| 4.19.0   | 1        | 0.77%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 77       | 59.23%  |
| 6.0     | 19       | 14.62%  |
| 5.14    | 10       | 7.69%   |
| 5.16    | 5        | 3.85%   |
| 5.19    | 4        | 3.08%   |
| 5.18    | 4        | 3.08%   |
| 6.5     | 2        | 1.54%   |
| 6.1     | 2        | 1.54%   |
| 5.17    | 2        | 1.54%   |
| 5.15    | 2        | 1.54%   |
| 6.7     | 1        | 0.77%   |
| 6.2     | 1        | 0.77%   |
| 4.19    | 1        | 0.77%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 127      | 97.69%  |
| i686   | 3        | 2.31%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| XFCE             | 100      | 76.92%  |
| KDE5             | 27       | 20.77%  |
| lightdm-xsession | 2        | 1.54%   |
| Unknown          | 1        | 0.77%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 130      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 101      | 77.69%  |
| SDDM    | 25       | 19.23%  |
| SLiM    | 3        | 2.31%   |
| GDM     | 1        | 0.77%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 57       | 43.85%  |
| de_DE | 16       | 12.31%  |
| it_IT | 8        | 6.15%   |
| en_GB | 8        | 6.15%   |
| ru_RU | 5        | 3.85%   |
| es_AR | 5        | 3.85%   |
| pl_PL | 4        | 3.08%   |
| sv_SE | 3        | 2.31%   |
| es_ES | 3        | 2.31%   |
| de_CH | 3        | 2.31%   |
| pt_BR | 2        | 1.54%   |
| fr_FR | 2        | 1.54%   |
| es_VE | 2        | 1.54%   |
| es_MX | 2        | 1.54%   |
| en_AU | 2        | 1.54%   |
| sk_SK | 1        | 0.77%   |
| hu_HU | 1        | 0.77%   |
| hr_HR | 1        | 0.77%   |
| fi_FI | 1        | 0.77%   |
| es_CO | 1        | 0.77%   |
| en_NZ | 1        | 0.77%   |
| en_CA | 1        | 0.77%   |
| el_GR | 1        | 0.77%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 76       | 58.46%  |
| EFI  | 54       | 41.54%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 115      | 88.46%  |
| Overlay  | 9        | 6.92%   |
| Btrfs    | 2        | 1.54%   |
| Xfs      | 1        | 0.77%   |
| Tmpfs    | 1        | 0.77%   |
| Reiserfs | 1        | 0.77%   |
| Ext3     | 1        | 0.77%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 76       | 58.02%  |
| MBR  | 55       | 41.98%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 83       | 62.41%  |
| Yes       | 50       | 37.59%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 68       | 52.31%  |
| No        | 62       | 47.69%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 30       | 23.08%  |
| Gigabyte Technology                  | 15       | 11.54%  |
| ASRock                               | 13       | 10%     |
| MSI                                  | 12       | 9.23%   |
| Dell                                 | 12       | 9.23%   |
| Hewlett-Packard                      | 10       | 7.69%   |
| Lenovo                               | 6        | 4.62%   |
| Intel                                | 4        | 3.08%   |
| Unknown                              | 4        | 3.08%   |
| Foxconn                              | 3        | 2.31%   |
| Pegatron                             | 2        | 1.54%   |
| Medion                               | 2        | 1.54%   |
| Gateway                              | 2        | 1.54%   |
| Fujitsu                              | 2        | 1.54%   |
| Biostar                              | 2        | 1.54%   |
| ZOTAC                                | 1        | 0.77%   |
| SIRAGON                              | 1        | 0.77%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.77%   |
| OEM                                  | 1        | 0.77%   |
| MP                                   | 1        | 0.77%   |
| Huanan                               | 1        | 0.77%   |
| GALAX                                | 1        | 0.77%   |
| ECS                                  | 1        | 0.77%   |
| BESSTAR Tech                         | 1        | 0.77%   |
| AOpen                                | 1        | 0.77%   |
| Acer                                 | 1        | 0.77%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Desktops | Percent |
|---------------------------------------------|----------|---------|
| ASUS All Series                             | 9        | 6.92%   |
| Unknown                                     | 5        | 3.85%   |
| MSI MS-7C91                                 | 2        | 1.54%   |
| Gigabyte GA-MA785GM-US2H                    | 2        | 1.54%   |
| Dell OptiPlex 9020                          | 2        | 1.54%   |
| Dell OptiPlex 780                           | 2        | 1.54%   |
| Dell OptiPlex 755                           | 2        | 1.54%   |
| ASUS ROG Maximus XIII HERO                  | 2        | 1.54%   |
| SIRAGON AIO-5150                            | 1        | 0.77%   |
| Shenzhen Meigao Electronic Equipment UM450  | 1        | 0.77%   |
| Pegatron FQ425AA-ABA a6655f                 | 1        | 0.77%   |
| Pegatron 2AD5                               | 1        | 0.77%   |
| OEM Intel H81                               | 1        | 0.77%   |
| MSI MS-7E12                                 | 1        | 0.77%   |
| MSI MS-7C37                                 | 1        | 0.77%   |
| MSI MS-7B98                                 | 1        | 0.77%   |
| MSI MS-7B53                                 | 1        | 0.77%   |
| MSI MS-7A63                                 | 1        | 0.77%   |
| MSI MS-7A34                                 | 1        | 0.77%   |
| MSI MS-7917                                 | 1        | 0.77%   |
| MSI MS-7823                                 | 1        | 0.77%   |
| MSI MS-7758                                 | 1        | 0.77%   |
| MSI MS-7721                                 | 1        | 0.77%   |
| MP MS-7848                                  | 1        | 0.77%   |
| Medion MS-7667                              | 1        | 0.77%   |
| Medion Akoya P5330 E MD8876/2458            | 1        | 0.77%   |
| Lenovo V50s-07IMB 11HB002AFR                | 1        | 0.77%   |
| Lenovo ThinkStation P620 30E0CTO1WW         | 1        | 0.77%   |
| Lenovo ThinkCentre M75s Gen 2 11JAS0CJ00    | 1        | 0.77%   |
| Lenovo ThinkCentre M58 7638CB8              | 1        | 0.77%   |
| Lenovo IdeaCentre Gaming5 17IAB7 90T00007US | 1        | 0.77%   |
| Lenovo 10AAS1QB0B                           | 1        | 0.77%   |
| Intel V1.3                                  | 1        | 0.77%   |
| Intel Jasper Lake Client Platform           | 1        | 0.77%   |
| Intel DH55TC AAE70932-303                   | 1        | 0.77%   |
| Intel D34010WYK H14771-303                  | 1        | 0.77%   |
| Huanan X99-F8                               | 1        | 0.77%   |
| HP Z400 Workstation                         | 1        | 0.77%   |
| HP EliteDesk 800 G1 USDT                    | 1        | 0.77%   |
| HP Elite Tower 600 G9 Desktop PC            | 1        | 0.77%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Dell OptiPlex                              | 9        | 6.92%   |
| ASUS All                                   | 9        | 6.92%   |
| Unknown                                    | 5        | 3.85%   |
| HP Compaq                                  | 4        | 3.08%   |
| ASUS ROG                                   | 3        | 2.31%   |
| ASUS PRIME                                 | 3        | 2.31%   |
| MSI MS-7C91                                | 2        | 1.54%   |
| Lenovo ThinkCentre                         | 2        | 1.54%   |
| Gigabyte GA-MA785GM-US2H                   | 2        | 1.54%   |
| Gigabyte B550M                             | 2        | 1.54%   |
| Dell Precision                             | 2        | 1.54%   |
| ASUS TUF                                   | 2        | 1.54%   |
| ASUS P5GC-MX                               | 2        | 1.54%   |
| SIRAGON AIO-5150                           | 1        | 0.77%   |
| Shenzhen Meigao Electronic Equipment UM450 | 1        | 0.77%   |
| Pegatron FQ425AA-ABA                       | 1        | 0.77%   |
| Pegatron 2AD5                              | 1        | 0.77%   |
| OEM Intel                                  | 1        | 0.77%   |
| MSI MS-7E12                                | 1        | 0.77%   |
| MSI MS-7C37                                | 1        | 0.77%   |
| MSI MS-7B98                                | 1        | 0.77%   |
| MSI MS-7B53                                | 1        | 0.77%   |
| MSI MS-7A63                                | 1        | 0.77%   |
| MSI MS-7A34                                | 1        | 0.77%   |
| MSI MS-7917                                | 1        | 0.77%   |
| MSI MS-7823                                | 1        | 0.77%   |
| MSI MS-7758                                | 1        | 0.77%   |
| MSI MS-7721                                | 1        | 0.77%   |
| MP MS-7848                                 | 1        | 0.77%   |
| Medion MS-7667                             | 1        | 0.77%   |
| Medion Akoya                               | 1        | 0.77%   |
| Lenovo V50s-07IMB                          | 1        | 0.77%   |
| Lenovo ThinkStation                        | 1        | 0.77%   |
| Lenovo IdeaCentre                          | 1        | 0.77%   |
| Lenovo 10AAS1QB0B                          | 1        | 0.77%   |
| Intel V1.3                                 | 1        | 0.77%   |
| Intel Jasper                               | 1        | 0.77%   |
| Intel DH55TC                               | 1        | 0.77%   |
| Intel D34010WYK                            | 1        | 0.77%   |
| Huanan X99-F8                              | 1        | 0.77%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 13       | 10%     |
| 2022 | 12       | 9.23%   |
| 2021 | 12       | 9.23%   |
| 2011 | 10       | 7.69%   |
| 2018 | 9        | 6.92%   |
| 2020 | 8        | 6.15%   |
| 2014 | 8        | 6.15%   |
| 2010 | 8        | 6.15%   |
| 2009 | 8        | 6.15%   |
| 2016 | 7        | 5.38%   |
| 2012 | 7        | 5.38%   |
| 2019 | 6        | 4.62%   |
| 2007 | 6        | 4.62%   |
| 2008 | 5        | 3.85%   |
| 2015 | 4        | 3.08%   |
| 2017 | 3        | 2.31%   |
| 2023 | 2        | 1.54%   |
| 2006 | 1        | 0.77%   |
| 2004 | 1        | 0.77%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 130      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 130      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 130      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 32       | 24.43%  |
| 4.01-8.0    | 26       | 19.85%  |
| 32.01-64.0  | 23       | 17.56%  |
| 16.01-24.0  | 21       | 16.03%  |
| 3.01-4.0    | 15       | 11.45%  |
| 24.01-32.0  | 6        | 4.58%   |
| 64.01-256.0 | 4        | 3.05%   |
| 2.01-3.0    | 2        | 1.53%   |
| 0.51-1.0    | 2        | 1.53%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 52       | 38.81%  |
| 2.01-3.0   | 34       | 25.37%  |
| 4.01-8.0   | 18       | 13.43%  |
| 3.01-4.0   | 17       | 12.69%  |
| 0.51-1.0   | 6        | 4.48%   |
| 8.01-16.0  | 5        | 3.73%   |
| 16.01-24.0 | 2        | 1.49%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 46       | 35.11%  |
| 2      | 33       | 25.19%  |
| 3      | 27       | 20.61%  |
| 4      | 15       | 11.45%  |
| 5      | 5        | 3.82%   |
| 8      | 3        | 2.29%   |
| 9      | 1        | 0.76%   |
| 7      | 1        | 0.76%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 67       | 51.54%  |
| No        | 63       | 48.46%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 129      | 99.23%  |
| No        | 1        | 0.77%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 70       | 53.85%  |
| No        | 60       | 46.15%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 88       | 67.69%  |
| Yes       | 42       | 32.31%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Desktops | Percent |
|------------------------|----------|---------|
| USA                    | 30       | 23.08%  |
| Germany                | 16       | 12.31%  |
| Italy                  | 8        | 6.15%   |
| Russia                 | 5        | 3.85%   |
| Poland                 | 5        | 3.85%   |
| Canada                 | 5        | 3.85%   |
| Argentina              | 5        | 3.85%   |
| UK                     | 4        | 3.08%   |
| Sweden                 | 4        | 3.08%   |
| Australia              | 4        | 3.08%   |
| Venezuela              | 3        | 2.31%   |
| Switzerland            | 3        | 2.31%   |
| Spain                  | 3        | 2.31%   |
| India                  | 3        | 2.31%   |
| France                 | 3        | 2.31%   |
| Finland                | 3        | 2.31%   |
| Singapore              | 2        | 1.54%   |
| Mexico                 | 2        | 1.54%   |
| Greece                 | 2        | 1.54%   |
| Brazil                 | 2        | 1.54%   |
| Ukraine                | 1        | 0.77%   |
| South Africa           | 1        | 0.77%   |
| Slovakia               | 1        | 0.77%   |
| Romania                | 1        | 0.77%   |
| New Zealand            | 1        | 0.77%   |
| Netherlands            | 1        | 0.77%   |
| Lithuania              | 1        | 0.77%   |
| Jamaica                | 1        | 0.77%   |
| Ireland                | 1        | 0.77%   |
| Indonesia              | 1        | 0.77%   |
| Hungary                | 1        | 0.77%   |
| French Guiana          | 1        | 0.77%   |
| Estonia                | 1        | 0.77%   |
| Denmark                | 1        | 0.77%   |
| Croatia                | 1        | 0.77%   |
| Colombia               | 1        | 0.77%   |
| Bosnia and Herzegovina | 1        | 0.77%   |
| Belgium                | 1        | 0.77%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Sydney                | 3        | 2.31%   |
| Moscow                | 3        | 2.31%   |
| Toronto               | 2        | 1.54%   |
| Singapore             | 2        | 1.54%   |
| Mesquite              | 2        | 1.54%   |
| Krakow                | 2        | 1.54%   |
| Houston               | 2        | 1.54%   |
| Ettingen              | 2        | 1.54%   |
| Córdoba              | 2        | 1.54%   |
| Berlin                | 2        | 1.54%   |
| Bengaluru             | 2        | 1.54%   |
| Alma                  | 2        | 1.54%   |
| Zagreb                | 1        | 0.77%   |
| Volos                 | 1        | 0.77%   |
| Voghera               | 1        | 0.77%   |
| Vilnius               | 1        | 0.77%   |
| Vilhelmina            | 1        | 0.77%   |
| Vasco da Gama         | 1        | 0.77%   |
| Vaidasoo              | 1        | 0.77%   |
| Tuglie                | 1        | 0.77%   |
| Tlalnepantla          | 1        | 0.77%   |
| Tampere               | 1        | 0.77%   |
| Surrey                | 1        | 0.77%   |
| Stockholm             | 1        | 0.77%   |
| Stevens Point         | 1        | 0.77%   |
| Stafford              | 1        | 0.77%   |
| St Petersburg         | 1        | 0.77%   |
| Spanish Town          | 1        | 0.77%   |
| Sollentuna            | 1        | 0.77%   |
| Seelbach              | 1        | 0.77%   |
| Seattle               | 1        | 0.77%   |
| Santa Rita do Sapucai | 1        | 0.77%   |
| San Fernando          | 1        | 0.77%   |
| San Diego             | 1        | 0.77%   |
| Rzeszów              | 1        | 0.77%   |
| Rosporden             | 1        | 0.77%   |
| Reno                  | 1        | 0.77%   |
| Rathenow              | 1        | 0.77%   |
| Puebla City           | 1        | 0.77%   |
| Portland              | 1        | 0.77%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Samsung Electronics       | 46       | 74     | 18.25%  |
| WDC                       | 43       | 55     | 17.06%  |
| Seagate                   | 43       | 66     | 17.06%  |
| Kingston                  | 23       | 24     | 9.13%   |
| SanDisk                   | 14       | 16     | 5.56%   |
| Toshiba                   | 11       | 12     | 4.37%   |
| China                     | 10       | 11     | 3.97%   |
| Crucial                   | 8        | 8      | 3.17%   |
| Unknown                   | 5        | 9      | 1.98%   |
| PNY                       | 5        | 6      | 1.98%   |
| Hitachi                   | 5        | 6      | 1.98%   |
| Corsair                   | 3        | 3      | 1.19%   |
| Transcend                 | 2        | 2      | 0.79%   |
| Team                      | 2        | 2      | 0.79%   |
| Silicon Motion            | 2        | 2      | 0.79%   |
| Intel                     | 2        | 3      | 0.79%   |
| GOODRAM                   | 2        | 2      | 0.79%   |
| Apacer                    | 2        | 2      | 0.79%   |
| A-DATA Technology         | 2        | 2      | 0.79%   |
| XPG                       | 1        | 1      | 0.4%    |
| WALRAM                    | 1        | 1      | 0.4%    |
| Vaseky                    | 1        | 1      | 0.4%    |
| SPCC                      | 1        | 1      | 0.4%    |
| Rogueware                 | 1        | 2      | 0.4%    |
| Phison Electronics        | 1        | 1      | 0.4%    |
| Phison                    | 1        | 1      | 0.4%    |
| Patriot                   | 1        | 1      | 0.4%    |
| OCZ                       | 1        | 1      | 0.4%    |
| Mushkin                   | 1        | 1      | 0.4%    |
| Micron/Crucial Technology | 1        | 1      | 0.4%    |
| Micron Technology         | 1        | 1      | 0.4%    |
| Maxtor                    | 1        | 1      | 0.4%    |
| Lexar                     | 1        | 1      | 0.4%    |
| KingSpec                  | 1        | 1      | 0.4%    |
| JMicron Technology        | 1        | 1      | 0.4%    |
| HGST                      | 1        | 1      | 0.4%    |
| Gigabyte Technology       | 1        | 1      | 0.4%    |
| External                  | 1        | 1      | 0.4%    |
| CT1000P3                  | 1        | 1      | 0.4%    |
| Avant                     | 1        | 1      | 0.4%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Kingston SA400S37480G 480GB SSD  | 7        | 2.33%   |
| Samsung SSD 850 EVO 250GB        | 6        | 2%      |
| Kingston SV300S37A240G 240GB SSD | 5        | 1.67%   |
| Seagate ST2000DM008-2FR102 2TB   | 4        | 1.33%   |
| Samsung SSD 970 EVO Plus 1TB     | 4        | 1.33%   |
| Seagate ST500LM021-1KJ152 500GB  | 3        | 1%      |
| Seagate ST4000DM004-2CV104 4TB   | 3        | 1%      |
| Seagate ST3500413AS 500GB        | 3        | 1%      |
| Seagate ST2000DM001-1ER164 2TB   | 3        | 1%      |
| SanDisk SDSSDA240G 240GB         | 3        | 1%      |
| SanDisk NVMe SSD Drive 1TB       | 3        | 1%      |
| Samsung SSD 980 PRO 1TB          | 3        | 1%      |
| Samsung SSD 970 EVO Plus 500GB   | 3        | 1%      |
| Samsung SSD 850 EVO 1TB          | 3        | 1%      |
| Samsung SSD 840 Series 120GB     | 3        | 1%      |
| Kingston SA400S37240G 240GB SSD  | 3        | 1%      |
| WDC WD3200AAKS-75B3A0 320GB      | 2        | 0.67%   |
| WDC WD10EZEX-00BN5A0 1TB         | 2        | 0.67%   |
| WDC WD10EZEX-00BBHA0 1TB         | 2        | 0.67%   |
| Unknown SD/MMC/MS PRO 128GB      | 2        | 0.67%   |
| Unknown SD/MMC 1073GB            | 2        | 0.67%   |
| Unknown M.S./M.S.Pro/HG 16GB     | 2        | 0.67%   |
| Unknown Compact Flash 977MB      | 2        | 0.67%   |
| Toshiba HDWD110 1TB              | 2        | 0.67%   |
| Toshiba DT01ACA100 1TB           | 2        | 0.67%   |
| Seagate ST500DM002-1BD142 500GB  | 2        | 0.67%   |
| Seagate ST250DM000-1BD141 250GB  | 2        | 0.67%   |
| Seagate ST1000DM010-2EP102 1TB   | 2        | 0.67%   |
| Seagate ST1000DM003-1CH162 1TB   | 2        | 0.67%   |
| Seagate Expansion 1TB            | 2        | 0.67%   |
| SanDisk SDSSDA120G 120GB         | 2        | 0.67%   |
| Samsung SSD 980 500GB            | 2        | 0.67%   |
| Samsung SSD 970 PRO 512GB        | 2        | 0.67%   |
| Samsung SSD 870 QVO 1TB          | 2        | 0.67%   |
| Samsung SSD 870 EVO 500GB        | 2        | 0.67%   |
| Samsung SSD 860 EVO 500GB        | 2        | 0.67%   |
| Samsung SSD 860 EVO 250GB        | 2        | 0.67%   |
| Samsung SSD 850 EVO 500GB        | 2        | 0.67%   |
| Samsung HD501LJ 500GB            | 2        | 0.67%   |
| Samsung HD103SI 1TB              | 2        | 0.67%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 43       | 66     | 39.45%  |
| WDC                 | 39       | 51     | 35.78%  |
| Toshiba             | 11       | 12     | 10.09%  |
| Samsung Electronics | 6        | 8      | 5.5%    |
| Hitachi             | 5        | 6      | 4.59%   |
| Unknown             | 2        | 2      | 1.83%   |
| Maxtor              | 1        | 1      | 0.92%   |
| HGST                | 1        | 1      | 0.92%   |
| External            | 1        | 1      | 0.92%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 30       | 38     | 29.41%  |
| Kingston            | 20       | 21     | 19.61%  |
| China               | 10       | 11     | 9.8%    |
| SanDisk             | 9        | 10     | 8.82%   |
| Crucial             | 6        | 6      | 5.88%   |
| PNY                 | 4        | 4      | 3.92%   |
| WDC                 | 2        | 2      | 1.96%   |
| Transcend           | 2        | 2      | 1.96%   |
| Team                | 2        | 2      | 1.96%   |
| GOODRAM             | 2        | 2      | 1.96%   |
| A-DATA Technology   | 2        | 2      | 1.96%   |
| WALRAM              | 1        | 1      | 0.98%   |
| Vaseky              | 1        | 1      | 0.98%   |
| SPCC                | 1        | 1      | 0.98%   |
| Rogueware           | 1        | 2      | 0.98%   |
| Patriot             | 1        | 1      | 0.98%   |
| OCZ                 | 1        | 1      | 0.98%   |
| Mushkin             | 1        | 1      | 0.98%   |
| Micron Technology   | 1        | 1      | 0.98%   |
| KingSpec            | 1        | 1      | 0.98%   |
| Intel               | 1        | 1      | 0.98%   |
| Avant               | 1        | 1      | 0.98%   |
| Apacer              | 1        | 1      | 0.98%   |
| Acer                | 1        | 1      | 0.98%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 85       | 148    | 39.72%  |
| SSD     | 83       | 114    | 38.79%  |
| NVMe    | 42       | 58     | 19.63%  |
| Unknown | 3        | 7      | 1.4%    |
| MMC     | 1        | 1      | 0.47%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 115      | 250    | 67.65%  |
| NVMe | 42       | 57     | 24.71%  |
| SAS  | 12       | 20     | 7.06%   |
| MMC  | 1        | 1      | 0.59%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 90       | 141    | 49.72%  |
| 0.51-1.0   | 51       | 62     | 28.18%  |
| 1.01-2.0   | 23       | 31     | 12.71%  |
| 3.01-4.0   | 7        | 8      | 3.87%   |
| 2.01-3.0   | 4        | 5      | 2.21%   |
| 4.01-10.0  | 4        | 11     | 2.21%   |
| 10.01-20.0 | 2        | 4      | 1.1%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 31       | 23.66%  |
| 251-500        | 26       | 19.85%  |
| 501-1000       | 17       | 12.98%  |
| 1001-2000      | 15       | 11.45%  |
| More than 3000 | 13       | 9.92%   |
| 2001-3000      | 12       | 9.16%   |
| 51-100         | 10       | 7.63%   |
| 1-20           | 4        | 3.05%   |
| 21-50          | 2        | 1.53%   |
| Unknown        | 1        | 0.76%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 32       | 24.24%  |
| 21-50          | 22       | 16.67%  |
| 101-250        | 22       | 16.67%  |
| 51-100         | 17       | 12.88%  |
| 1001-2000      | 11       | 8.33%   |
| 251-500        | 9        | 6.82%   |
| 501-1000       | 8        | 6.06%   |
| More than 3000 | 7        | 5.3%    |
| 2001-3000      | 3        | 2.27%   |
| Unknown        | 1        | 0.76%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| China SSD 512GB                          | 2        | 2      | 4.88%   |
| WDC WDS100T2B0A-00SM50 1TB SSD           | 1        | 1      | 2.44%   |
| WDC WD3200AAKS-00UU3A0 320GB             | 1        | 1      | 2.44%   |
| WDC WD3200AAJS-00L7A0 320GB              | 1        | 1      | 2.44%   |
| WDC WD3200AAJS-00B4A0 320GB              | 1        | 1      | 2.44%   |
| WDC WD2500AAJS-00B4A0 250GB              | 1        | 1      | 2.44%   |
| WDC WD20EFRX-68EUZN0 2TB                 | 1        | 2      | 2.44%   |
| WDC WD20EARS-00J99B0 2TB                 | 1        | 1      | 2.44%   |
| WDC WD10EZRZ-00HTKB0 1TB                 | 1        | 1      | 2.44%   |
| WDC WD10EADS-98M2B0 1TB                  | 1        | 1      | 2.44%   |
| WDC WD10EADS-00M2B0 1TB                  | 1        | 1      | 2.44%   |
| Toshiba MQ01ABF050 500GB                 | 1        | 1      | 2.44%   |
| Toshiba MK1234GSX 120GB                  | 1        | 1      | 2.44%   |
| Seagate ST500LT012-9WS142 500GB          | 1        | 1      | 2.44%   |
| Seagate ST500LM021-1KJ152 500GB          | 1        | 1      | 2.44%   |
| Seagate ST500DM002-1BD142 500GB          | 1        | 1      | 2.44%   |
| Seagate ST380815AS 80GB                  | 1        | 1      | 2.44%   |
| Seagate ST3500413AS 500GB                | 1        | 1      | 2.44%   |
| Seagate ST3360320AS 360GB                | 1        | 1      | 2.44%   |
| Seagate ST3320418AS 320GB                | 1        | 1      | 2.44%   |
| Seagate ST320LT020-9YG142 320GB          | 1        | 1      | 2.44%   |
| Seagate ST320LT012-1DG14C 320GB          | 1        | 2      | 2.44%   |
| Seagate ST250DM000-1BD141 250GB          | 1        | 1      | 2.44%   |
| Seagate ST2000DM001-1ER164 2TB           | 1        | 1      | 2.44%   |
| Seagate ST1000VM002-1CT162 1TB           | 1        | 1      | 2.44%   |
| Seagate ST1000DM003-9YN162 1TB           | 1        | 1      | 2.44%   |
| SanDisk SDSSDX120GG25 120GB              | 1        | 1      | 2.44%   |
| Samsung Electronics SSD 870 EVO 500GB    | 1        | 2      | 2.44%   |
| Samsung Electronics SSD 850 EVO 500GB    | 1        | 1      | 2.44%   |
| Samsung Electronics SSD 850 EVO 1TB      | 1        | 2      | 2.44%   |
| Samsung Electronics SSD 840 Series 120GB | 1        | 1      | 2.44%   |
| Samsung Electronics HD103SI 1TB          | 1        | 1      | 2.44%   |
| Maxtor 4K040H2 40GB                      | 1        | 1      | 2.44%   |
| Lexar 500GB SSD                          | 1        | 1      | 2.44%   |
| Kingston SA400S37480G 480GB SSD          | 1        | 1      | 2.44%   |
| KingSpec P4-960 960GB                    | 1        | 1      | 2.44%   |
| Hitachi HTS545050A7E380 500GB            | 1        | 1      | 2.44%   |
| Hitachi HDS721050CLA362 500GB            | 1        | 1      | 2.44%   |
| HGST HTS545050A7E380 500GB               | 1        | 1      | 2.44%   |
| GOODRAM SSDPR-CL100-480-G3 480GB         | 1        | 1      | 2.44%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 13       | 14     | 32.5%   |
| WDC                 | 10       | 11     | 25%     |
| Samsung Electronics | 5        | 7      | 12.5%   |
| Toshiba             | 2        | 2      | 5%      |
| China               | 2        | 2      | 5%      |
| SanDisk             | 1        | 1      | 2.5%    |
| Maxtor              | 1        | 1      | 2.5%    |
| Lexar               | 1        | 1      | 2.5%    |
| Kingston            | 1        | 1      | 2.5%    |
| KingSpec            | 1        | 1      | 2.5%    |
| Hitachi             | 1        | 2      | 2.5%    |
| HGST                | 1        | 1      | 2.5%    |
| GOODRAM             | 1        | 1      | 2.5%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 13       | 14     | 46.43%  |
| WDC                 | 9        | 10     | 32.14%  |
| Toshiba             | 2        | 2      | 7.14%   |
| Samsung Electronics | 1        | 1      | 3.57%   |
| Maxtor              | 1        | 1      | 3.57%   |
| Hitachi             | 1        | 2      | 3.57%   |
| HGST                | 1        | 1      | 3.57%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 26       | 31     | 70.27%  |
| SSD  | 10       | 13     | 27.03%  |
| NVMe | 1        | 1      | 2.7%    |

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
| Works    | 119      | 250    | 68.39%  |
| Malfunc  | 37       | 45     | 21.26%  |
| Detected | 18       | 33     | 10.34%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 90       | 45.23%  |
| AMD                         | 37       | 18.59%  |
| Samsung Electronics         | 18       | 9.05%   |
| ASMedia Technology          | 11       | 5.53%   |
| Phison Electronics          | 8        | 4.02%   |
| SanDisk                     | 7        | 3.52%   |
| Marvell Technology Group    | 4        | 2.01%   |
| JMicron Technology          | 4        | 2.01%   |
| Silicon Motion              | 3        | 1.51%   |
| Micron/Crucial Technology   | 3        | 1.51%   |
| LSI Logic / Symbios Logic   | 3        | 1.51%   |
| Kingston Technology Company | 3        | 1.51%   |
| VIA Technologies            | 2        | 1.01%   |
| Nvidia                      | 2        | 1.01%   |
| ULi Electronics             | 1        | 0.5%    |
| Silicon Image               | 1        | 0.5%    |
| MAXIO Technology (Hangzhou) | 1        | 0.5%    |
| ADATA Technology            | 1        | 0.5%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 12       | 4.96%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 12       | 4.96%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 12       | 4.96%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 10       | 4.13%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 7        | 2.89%   |
| AMD 500 Series Chipset SATA Controller                                                  | 7        | 2.89%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 6        | 2.48%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 6        | 2.48%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 2.07%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5        | 2.07%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5        | 2.07%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4        | 1.65%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 1.65%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4        | 1.65%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4        | 1.65%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 4        | 1.65%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4        | 1.65%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 4        | 1.65%   |
| AMD 600 Series Chipset SATA Controller                                                  | 4        | 1.65%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 3        | 1.24%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                                   | 3        | 1.24%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 3        | 1.24%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 3        | 1.24%   |
| Phison E12 NVMe Controller                                                              | 3        | 1.24%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 3        | 1.24%   |
| Intel SATA Controller [RAID mode]                                                       | 3        | 1.24%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3        | 1.24%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 3        | 1.24%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 1.24%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 1.24%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3        | 1.24%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 3        | 1.24%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 3        | 1.24%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 3        | 1.24%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3        | 1.24%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3        | 1.24%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)               | 2        | 0.83%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 0.83%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 0.83%   |
| Nvidia MCP61 IDE                                                                        | 2        | 0.83%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 115      | 58.97%  |
| NVMe | 41       | 21.03%  |
| IDE  | 30       | 15.38%  |
| RAID | 7        | 3.59%   |
| SAS  | 1        | 0.51%   |
| SCSI | 1        | 0.51%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 91       | 70%     |
| AMD    | 39       | 30%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 4        | 3.08%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 3        | 2.31%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 3        | 2.31%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 3        | 2.31%   |
| Intel Core i7-5820K CPU @ 3.30GHz           | 2        | 1.54%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 1.54%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 2        | 1.54%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2        | 1.54%   |
| Intel Core i7 CPU 870 @ 2.93GHz             | 2        | 1.54%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 2        | 1.54%   |
| Intel Core i5-4690K CPU @ 3.50GHz           | 2        | 1.54%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 2        | 1.54%   |
| Intel Core i5-3350P CPU @ 3.10GHz           | 2        | 1.54%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 2        | 1.54%   |
| Intel 12th Gen Core i7-12700                | 2        | 1.54%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz      | 2        | 1.54%   |
| AMD Ryzen 9 7900X 12-Core Processor         | 2        | 1.54%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 2        | 1.54%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 2        | 1.54%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 2        | 1.54%   |
| AMD Athlon II X4 630 Processor              | 2        | 1.54%   |
| Intel Xeon W-2123 CPU @ 3.60GHz             | 1        | 0.77%   |
| Intel Xeon CPU W3565 @ 3.20GHz              | 1        | 0.77%   |
| Intel Xeon CPU E5520 @ 2.27GHz              | 1        | 0.77%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz         | 1        | 0.77%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz          | 1        | 0.77%   |
| Intel Pentium Gold G7400                    | 1        | 0.77%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 1        | 0.77%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1        | 0.77%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1        | 0.77%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz      | 1        | 0.77%   |
| Intel Pentium D CPU 2.80GHz                 | 1        | 0.77%   |
| Intel Pentium CPU 2030M @ 2.50GHz           | 1        | 0.77%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1        | 0.77%   |
| Intel Pentium 4 CPU 2.80GHz                 | 1        | 0.77%   |
| Intel Core M-5Y10c CPU @ 0.80GHz            | 1        | 0.77%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1        | 0.77%   |
| Intel Core i9-10850K CPU @ 3.60GHz          | 1        | 0.77%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1        | 0.77%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 0.77%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 25       | 19.23%  |
| Intel Core i7           | 18       | 13.85%  |
| Intel Core i3           | 11       | 8.46%   |
| AMD Ryzen 5             | 10       | 7.69%   |
| Intel Core 2 Duo        | 8        | 6.15%   |
| Other                   | 7        | 5.38%   |
| AMD Ryzen 7             | 7        | 5.38%   |
| Intel Xeon              | 5        | 3.85%   |
| Intel Celeron           | 5        | 3.85%   |
| AMD Ryzen 9             | 3        | 2.31%   |
| AMD Phenom II X4        | 3        | 2.31%   |
| AMD Athlon II X4        | 3        | 2.31%   |
| Intel Pentium Dual-Core | 2        | 1.54%   |
| Intel Pentium Dual      | 2        | 1.54%   |
| Intel Pentium 4         | 2        | 1.54%   |
| Intel Core i9           | 2        | 1.54%   |
| AMD Ryzen Threadripper  | 2        | 1.54%   |
| AMD Ryzen 3             | 2        | 1.54%   |
| AMD Phenom              | 2        | 1.54%   |
| AMD FX                  | 2        | 1.54%   |
| Intel Pentium Gold      | 1        | 0.77%   |
| Intel Pentium D         | 1        | 0.77%   |
| Intel Pentium           | 1        | 0.77%   |
| Intel Core M            | 1        | 0.77%   |
| AMD Ryzen 5 PRO         | 1        | 0.77%   |
| AMD Phenom II X6        | 1        | 0.77%   |
| AMD Athlon              | 1        | 0.77%   |
| AMD A8                  | 1        | 0.77%   |
| AMD A4                  | 1        | 0.77%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 54       | 41.54%  |
| 2      | 32       | 24.62%  |
| 6      | 16       | 12.31%  |
| 8      | 13       | 10%     |
| 12     | 7        | 5.38%   |
| 1      | 3        | 2.31%   |
| 16     | 2        | 1.54%   |
| 10     | 2        | 1.54%   |
| 3      | 1        | 0.77%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 129      | 99.23%  |
| 2      | 1        | 0.77%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 71       | 54.62%  |
| 1      | 59       | 45.38%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 129      | 99.23%  |
| 32-bit         | 1        | 0.77%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 15       | 11.54%  |
| 0x306c3    | 14       | 10.77%  |
| 0x306a9    | 7        | 5.38%   |
| 0x206a7    | 7        | 5.38%   |
| 0x1067a    | 6        | 4.62%   |
| 0xa0653    | 4        | 3.08%   |
| 0x906ed    | 4        | 3.08%   |
| 0x6fd      | 4        | 3.08%   |
| 0x506e3    | 4        | 3.08%   |
| 0x106e5    | 4        | 3.08%   |
| 0x0800820d | 4        | 3.08%   |
| 0x0a601203 | 3        | 2.31%   |
| 0x08701021 | 3        | 2.31%   |
| 0x08108109 | 3        | 2.31%   |
| 0x010000db | 3        | 2.31%   |
| 0xa0671    | 2        | 1.54%   |
| 0x306f2    | 2        | 1.54%   |
| 0x20655    | 2        | 1.54%   |
| 0x0a20120a | 2        | 1.54%   |
| 0x010000dc | 2        | 1.54%   |
| 0x01000083 | 2        | 1.54%   |
| 0xf49      | 1        | 0.77%   |
| 0xf47      | 1        | 0.77%   |
| 0xf34      | 1        | 0.77%   |
| 0xb0671    | 1        | 0.77%   |
| 0xa0655    | 1        | 0.77%   |
| 0x906ea    | 1        | 0.77%   |
| 0x906e9    | 1        | 0.77%   |
| 0x906c0    | 1        | 0.77%   |
| 0x906a4    | 1        | 0.77%   |
| 0x90675    | 1        | 0.77%   |
| 0x90672    | 1        | 0.77%   |
| 0x706a8    | 1        | 0.77%   |
| 0x706a1    | 1        | 0.77%   |
| 0x506c9    | 1        | 0.77%   |
| 0x50654    | 1        | 0.77%   |
| 0x406c3    | 1        | 0.77%   |
| 0x40651    | 1        | 0.77%   |
| 0x306d4    | 1        | 0.77%   |
| 0x206d7    | 1        | 0.77%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 21       | 16.15%  |
| SandyBridge      | 9        | 6.92%   |
| K10              | 9        | 6.92%   |
| Zen+             | 8        | 6.15%   |
| Penryn           | 8        | 6.15%   |
| Unknown          | 8        | 6.15%   |
| IvyBridge        | 7        | 5.38%   |
| Zen 3            | 6        | 4.62%   |
| Skylake          | 6        | 4.62%   |
| Nehalem          | 6        | 4.62%   |
| KabyLake         | 6        | 4.62%   |
| Zen 2            | 5        | 3.85%   |
| CometLake        | 5        | 3.85%   |
| Core             | 4        | 3.08%   |
| Zen              | 3        | 2.31%   |
| NetBurst         | 3        | 2.31%   |
| Westmere         | 2        | 1.54%   |
| Icelake          | 2        | 1.54%   |
| Goldmont plus    | 2        | 1.54%   |
| Alderlake Hybrid | 2        | 1.54%   |
| Tremont          | 1        | 0.77%   |
| Steamroller      | 1        | 0.77%   |
| Silvermont       | 1        | 0.77%   |
| Piledriver       | 1        | 0.77%   |
| K10 Llano        | 1        | 0.77%   |
| Goldmont         | 1        | 0.77%   |
| Bulldozer        | 1        | 0.77%   |
| Broadwell        | 1        | 0.77%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 53       | 36.81%  |
| Intel  | 48       | 33.33%  |
| AMD    | 43       | 29.86%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 6        | 4.11%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 6        | 4.11%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 5        | 3.42%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 5        | 3.42%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 4        | 2.74%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 4        | 2.74%   |
| AMD Raphael                                                                 | 4        | 2.74%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 4        | 2.74%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 3        | 2.05%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3        | 2.05%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 2.05%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 3        | 2.05%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 2.05%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 2.05%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 3        | 2.05%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 1.37%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 1.37%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 1.37%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 1.37%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 2        | 1.37%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 2        | 1.37%   |
| Intel HD Graphics 530                                                       | 2        | 1.37%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 2        | 1.37%   |
| Intel Core Processor Integrated Graphics Controller                         | 2        | 1.37%   |
| Intel AlderLake-S GT1                                                       | 2        | 1.37%   |
| AMD RS880 [Radeon HD 4200]                                                  | 2        | 1.37%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 2        | 1.37%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 1.37%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 1.37%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 0.68%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 0.68%   |
| Nvidia NV44A [GeForce 6200]                                                 | 1        | 0.68%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 0.68%   |
| Nvidia GP107GL [Quadro P620]                                                | 1        | 0.68%   |
| Nvidia GP107GL [Quadro P1000]                                               | 1        | 0.68%   |
| Nvidia GM107GL [Quadro K620]                                                | 1        | 0.68%   |
| Nvidia GK208 [GeForce GT 635]                                               | 1        | 0.68%   |
| Nvidia GK110 [GeForce GTX 780]                                              | 1        | 0.68%   |
| Nvidia GK107GL [Quadro K600]                                                | 1        | 0.68%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Nvidia   | 48       | 36.64%  |
| 1 x Intel    | 39       | 29.77%  |
| 1 x AMD      | 37       | 28.24%  |
| AMD + Nvidia | 5        | 3.82%   |
| Intel + AMD  | 2        | 1.53%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 93       | 71.54%  |
| Proprietary | 31       | 23.85%  |
| Unknown     | 6        | 4.62%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 48       | 36.64%  |
| 1.01-2.0   | 24       | 18.32%  |
| 3.01-4.0   | 14       | 10.69%  |
| 7.01-8.0   | 13       | 9.92%   |
| 0.51-1.0   | 13       | 9.92%   |
| 0.01-0.5   | 10       | 7.63%   |
| 8.01-16.0  | 6        | 4.58%   |
| 2.01-3.0   | 2        | 1.53%   |
| 5.01-6.0   | 1        | 0.76%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 19       | 13.67%  |
| Dell                 | 15       | 10.79%  |
| Acer                 | 15       | 10.79%  |
| Hewlett-Packard      | 9        | 6.47%   |
| AOC                  | 9        | 6.47%   |
| Philips              | 7        | 5.04%   |
| Goldstar             | 7        | 5.04%   |
| Sony                 | 6        | 4.32%   |
| BenQ                 | 6        | 4.32%   |
| Ancor Communications | 6        | 4.32%   |
| ViewSonic            | 4        | 2.88%   |
| Fujitsu Siemens      | 4        | 2.88%   |
| Medion               | 3        | 2.16%   |
| Lenovo               | 3        | 2.16%   |
| Iiyama               | 3        | 2.16%   |
| Eizo                 | 3        | 2.16%   |
| Vestel Elektronik    | 2        | 1.44%   |
| MSI                  | 2        | 1.44%   |
| ASUSTek Computer     | 2        | 1.44%   |
| Xiaomi               | 1        | 0.72%   |
| Vizio                | 1        | 0.72%   |
| Sangyo               | 1        | 0.72%   |
| SAC                  | 1        | 0.72%   |
| RTK                  | 1        | 0.72%   |
| Panasonic            | 1        | 0.72%   |
| NEC Computers        | 1        | 0.72%   |
| MiTAC                | 1        | 0.72%   |
| LG Electronics       | 1        | 0.72%   |
| Hitachi              | 1        | 0.72%   |
| HannStar             | 1        | 0.72%   |
| Grundig              | 1        | 0.72%   |
| Gigabyte Technology  | 1        | 0.72%   |
| CTV                  | 1        | 0.72%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| ViewSonic VX1935wm-3 VSCB81E 1440x900 410x256mm 19.0-inch             | 2        | 1.37%   |
| Vestel Elektronik 49FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch | 2        | 1.37%   |
| Sony SDM-M81 SNY0480 1280x1024 359x287mm 18.1-inch                    | 2        | 1.37%   |
| Samsung Electronics C32JG5x SAM0FE0 2560x1440 697x392mm 31.5-inch     | 2        | 1.37%   |
| MSI G27C4S2 MSI5CA9 1920x1080 597x336mm 27.0-inch                     | 2        | 1.37%   |
| Medion MD22322 MEB8101 2560x1440 699x393mm 31.6-inch                  | 2        | 1.37%   |
| Fujitsu Siemens B22W-7 LED FUS0838 1680x1050 470x300mm 22.0-inch      | 2        | 1.37%   |
| Xiaomi Mi TV XMD004A 1920x1080 708x398mm 32.0-inch                    | 1        | 0.68%   |
| Vizio E260MV VIZ0062 1920x1080 509x286mm 23.0-inch                    | 1        | 0.68%   |
| ViewSonic VX2433wm VSC3822 1920x1080 520x290mm 23.4-inch              | 1        | 0.68%   |
| ViewSonic VA2012wSERIES VSC6A1C 1680x1050 433x271mm 20.1-inch         | 1        | 0.68%   |
| Sony TV SNY0801 1360x768                                              | 1        | 0.68%   |
| Sony TV *30 SNY7105 3840x2160 952x535mm 43.0-inch                     | 1        | 0.68%   |
| Sony SDM-HS74P SNY3170 1280x1024 338x270mm 17.0-inch                  | 1        | 0.68%   |
| Sony SDM-HS53 SNY2250 1024x768 304x228mm 15.0-inch                    | 1        | 0.68%   |
| Sangyo LCD Monitor M27A3 1920x1080                                    | 1        | 0.68%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch     | 1        | 0.68%   |
| Samsung Electronics U28H75x SAM0DFE 3840x2160 608x345mm 27.5-inch     | 1        | 0.68%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 1        | 0.68%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                      | 1        | 0.68%   |
| Samsung Electronics SyncMaster SAM0594 1680x1050 459x296mm 21.5-inch  | 1        | 0.68%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch  | 1        | 0.68%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch   | 1        | 0.68%   |
| Samsung Electronics SyncMaster SAM0286 1280x720 372x209mm 16.8-inch   | 1        | 0.68%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch  | 1        | 0.68%   |
| Samsung Electronics SyncMaster SAM0117 1280x1024 312x234mm 15.4-inch  | 1        | 0.68%   |
| Samsung Electronics SMB2030 SAM063C 1600x900 443x249mm 20.0-inch      | 1        | 0.68%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1        | 0.68%   |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x287mm 23.0-inch     | 1        | 0.68%   |
| Samsung Electronics LCD Monitor SMT24A550                             | 1        | 0.68%   |
| Samsung Electronics LCD Monitor SAM0DF6 3840x2160 890x500mm 40.2-inch | 1        | 0.68%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 1        | 0.68%   |
| Samsung Electronics LCD Monitor C32R50x 3840x1080                     | 1        | 0.68%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch     | 1        | 0.68%   |
| SAC DM-MONG2750 SAC2700 2560x1440 597x336mm 27.0-inch                 | 1        | 0.68%   |
| RTK FHD HDR RTKBC32 1920x1080 597x336mm 27.0-inch                     | 1        | 0.68%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch              | 1        | 0.68%   |
| Philips PHL 276E8V PHLC18F 3840x2160 600x340mm 27.2-inch              | 1        | 0.68%   |
| Philips PHL 271E1 PHLC208 1920x1080 598x336mm 27.0-inch               | 1        | 0.68%   |
| Philips 226VL PHLC081 1920x1080 480x268mm 21.6-inch                   | 1        | 0.68%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 59       | 43.38%  |
| 3840x2160 (4K)     | 15       | 11.03%  |
| 2560x1440 (QHD)    | 13       | 9.56%   |
| 1680x1050 (WSXGA+) | 12       | 8.82%   |
| 1280x1024 (SXGA)   | 11       | 8.09%   |
| 1440x900 (WXGA+)   | 5        | 3.68%   |
| 1366x768 (WXGA)    | 5        | 3.68%   |
| 3440x1440          | 2        | 1.47%   |
| 1920x1200 (WUXGA)  | 2        | 1.47%   |
| 1600x900 (HD+)     | 2        | 1.47%   |
| 1360x768           | 2        | 1.47%   |
| 1280x720 (HD)      | 2        | 1.47%   |
| Unknown            | 2        | 1.47%   |
| 3840x1080          | 1        | 0.74%   |
| 2560x1080          | 1        | 0.74%   |
| 1920x1440          | 1        | 0.74%   |
| 1024x768 (XGA)     | 1        | 0.74%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 21       | 15.22%  |
| 23      | 19       | 13.77%  |
| 24      | 17       | 12.32%  |
| 21      | 13       | 9.42%   |
| 31      | 11       | 7.97%   |
| 22      | 11       | 7.97%   |
| 19      | 7        | 5.07%   |
| Unknown | 7        | 5.07%   |
| 17      | 6        | 4.35%   |
| 18      | 5        | 3.62%   |
| 84      | 3        | 2.17%   |
| 34      | 3        | 2.17%   |
| 15      | 3        | 2.17%   |
| 54      | 2        | 1.45%   |
| 20      | 2        | 1.45%   |
| 75      | 1        | 0.72%   |
| 72      | 1        | 0.72%   |
| 65      | 1        | 0.72%   |
| 61      | 1        | 0.72%   |
| 52      | 1        | 0.72%   |
| 40      | 1        | 0.72%   |
| 26      | 1        | 0.72%   |
| 16      | 1        | 0.72%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 52       | 38.52%  |
| 401-500     | 33       | 24.44%  |
| 601-700     | 14       | 10.37%  |
| 301-350     | 8        | 5.93%   |
| 351-400     | 7        | 5.19%   |
| Unknown     | 7        | 5.19%   |
| 1501-2000   | 5        | 3.7%    |
| 1001-1500   | 5        | 3.7%    |
| 701-800     | 3        | 2.22%   |
| 801-900     | 1        | 0.74%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 86       | 66.15%  |
| 16/10   | 21       | 16.15%  |
| 5/4     | 10       | 7.69%   |
| Unknown | 6        | 4.62%   |
| 4/3     | 3        | 2.31%   |
| 21/9    | 3        | 2.31%   |
| 3/2     | 1        | 0.77%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 46       | 34.07%  |
| 301-350        | 21       | 15.56%  |
| 151-200        | 18       | 13.33%  |
| 351-500        | 14       | 10.37%  |
| More than 1000 | 10       | 7.41%   |
| 251-300        | 7        | 5.19%   |
| 141-150        | 7        | 5.19%   |
| Unknown        | 7        | 5.19%   |
| 121-130        | 1        | 0.74%   |
| 111-120        | 1        | 0.74%   |
| 101-110        | 1        | 0.74%   |
| 501-1000       | 1        | 0.74%   |
| 91-100         | 1        | 0.74%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 87       | 65.91%  |
| 101-120 | 23       | 17.42%  |
| 1-50    | 8        | 6.06%   |
| Unknown | 7        | 5.3%    |
| 121-160 | 6        | 4.55%   |
| 161-240 | 1        | 0.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 104      | 80%     |
| 2     | 20       | 15.38%  |
| 0     | 4        | 3.08%   |
| 3     | 2        | 1.54%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 78       | 39.2%   |
| Intel                           | 59       | 29.65%  |
| Qualcomm Atheros                | 12       | 6.03%   |
| Ralink Technology               | 7        | 3.52%   |
| MediaTek                        | 7        | 3.52%   |
| TP-Link                         | 6        | 3.02%   |
| Broadcom Limited                | 5        | 2.51%   |
| Broadcom                        | 3        | 1.51%   |
| Ralink                          | 2        | 1.01%   |
| OPPO Electronics                | 2        | 1.01%   |
| Nvidia                          | 2        | 1.01%   |
| Microsoft                       | 2        | 1.01%   |
| Linksys                         | 2        | 1.01%   |
| Xiaomi                          | 1        | 0.5%    |
| VIA Technologies                | 1        | 0.5%    |
| Samsung Electronics             | 1        | 0.5%    |
| Qualcomm Atheros Communications | 1        | 0.5%    |
| Mercucys                        | 1        | 0.5%    |
| JMicron Technology              | 1        | 0.5%    |
| IMC Networks                    | 1        | 0.5%    |
| Edimax Technology               | 1        | 0.5%    |
| D-Link System                   | 1        | 0.5%    |
| D-Link                          | 1        | 0.5%    |
| AVM                             | 1        | 0.5%    |
| Aquantia                        | 1        | 0.5%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 55       | 24.55%  |
| Intel Ethernet Controller I225-V                                       | 9        | 4.02%   |
| Realtek RTL8125 2.5GbE Controller                                      | 8        | 3.57%   |
| Ralink MT7601U Wireless Adapter                                        | 5        | 2.23%   |
| Intel I211 Gigabit Network Connection                                  | 5        | 2.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 5        | 2.23%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 5        | 2.23%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 4        | 1.79%   |
| Intel Ethernet Connection I217-LM                                      | 4        | 1.79%   |
| Intel Ethernet Connection (2) I219-V                                   | 4        | 1.79%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 3        | 1.34%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 3        | 1.34%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 3        | 1.34%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 3        | 1.34%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 3        | 1.34%   |
| Intel Wi-Fi 6 AX200                                                    | 3        | 1.34%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 3        | 1.34%   |
| Intel Ethernet Connection I217-V                                       | 3        | 1.34%   |
| Intel Ethernet Connection (2) I218-V                                   | 3        | 1.34%   |
| Intel Ethernet Connection (14) I219-V                                  | 3        | 1.34%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 2        | 0.89%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                 | 2        | 0.89%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                        | 2        | 0.89%   |
| Realtek 802.11ac NIC                                                   | 2        | 0.89%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                             | 2        | 0.89%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 2        | 0.89%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 2        | 0.89%   |
| OPPO OnePlus Nord 4                                                    | 2        | 0.89%   |
| Nvidia MCP61 Ethernet                                                  | 2        | 0.89%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 2        | 0.89%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 2        | 0.89%   |
| Intel 82578DM Gigabit Network Connection                               | 2        | 0.89%   |
| Intel 82578DC Gigabit Network Connection                               | 2        | 0.89%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 2        | 0.89%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1        | 0.45%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 1        | 0.45%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                  | 1        | 0.45%   |
| TP-Link 802.11n NIC                                                    | 1        | 0.45%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1        | 0.45%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 1        | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 23       | 28.05%  |
| Intel                           | 17       | 20.73%  |
| Ralink Technology               | 7        | 8.54%   |
| MediaTek                        | 7        | 8.54%   |
| TP-Link                         | 6        | 7.32%   |
| Qualcomm Atheros                | 6        | 7.32%   |
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
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                      | 3        | 3.61%   |
| Intel Wi-Fi 6 AX200                                                            | 3        | 3.61%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                        | 3        | 3.61%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                   | 2        | 2.41%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                         | 2        | 2.41%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                | 2        | 2.41%   |
| Realtek 802.11ac NIC                                                           | 2        | 2.41%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                               | 2        | 2.41%   |
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
| Realtek B1610311068                                                            | 1        | 1.2%    |
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
| Realtek Semiconductor | 65       | 47.45%  |
| Intel                 | 53       | 38.69%  |
| Qualcomm Atheros      | 6        | 4.38%   |
| Broadcom Limited      | 3        | 2.19%   |
| OPPO Electronics      | 2        | 1.46%   |
| Nvidia                | 2        | 1.46%   |
| Broadcom              | 2        | 1.46%   |
| Xiaomi                | 1        | 0.73%   |
| VIA Technologies      | 1        | 0.73%   |
| JMicron Technology    | 1        | 0.73%   |
| Aquantia              | 1        | 0.73%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 55       | 39.29%  |
| Intel Ethernet Controller I225-V                                               | 9        | 6.43%   |
| Realtek RTL8125 2.5GbE Controller                                              | 8        | 5.71%   |
| Intel I211 Gigabit Network Connection                                          | 5        | 3.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 5        | 3.57%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 5        | 3.57%   |
| Intel Ethernet Connection I217-LM                                              | 4        | 2.86%   |
| Intel Ethernet Connection (2) I219-V                                           | 4        | 2.86%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 3        | 2.14%   |
| Intel Ethernet Connection I217-V                                               | 3        | 2.14%   |
| Intel Ethernet Connection (2) I218-V                                           | 3        | 2.14%   |
| Intel Ethernet Connection (14) I219-V                                          | 3        | 2.14%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                     | 2        | 1.43%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2        | 1.43%   |
| OPPO OnePlus Nord 4                                                            | 2        | 1.43%   |
| Nvidia MCP61 Ethernet                                                          | 2        | 1.43%   |
| Intel 82578DM Gigabit Network Connection                                       | 2        | 1.43%   |
| Intel 82578DC Gigabit Network Connection                                       | 2        | 1.43%   |
| Intel 82566DM-2 Gigabit Network Connection                                     | 2        | 1.43%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1        | 0.71%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 1        | 0.71%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1        | 0.71%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1        | 0.71%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1        | 0.71%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1        | 0.71%   |
| Intel NM10/ICH7 Family LAN Controller                                          | 1        | 0.71%   |
| Intel I210 Gigabit Network Connection                                          | 1        | 0.71%   |
| Intel Ethernet Connection I218-V                                               | 1        | 0.71%   |
| Intel Ethernet Connection (7) I219-V                                           | 1        | 0.71%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1        | 0.71%   |
| Intel Ethernet Connection (17) I219-V                                          | 1        | 0.71%   |
| Intel Ethernet Connection (17) I219-LM                                         | 1        | 0.71%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 1        | 0.71%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 1        | 0.71%   |
| Broadcom Limited NetXtreme BCM5782 Gigabit Ethernet                            | 1        | 0.71%   |
| Broadcom Limited NetXtreme BCM5754 Gigabit Ethernet PCI Express                | 1        | 0.71%   |
| Broadcom Limited NetXtreme BCM5722 Gigabit Ethernet PCI Express                | 1        | 0.71%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 1        | 0.71%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 129      | 64.5%   |
| WiFi     | 70       | 35%     |
| Modem    | 1        | 0.5%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 89       | 65.44%  |
| WiFi     | 47       | 34.56%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 81       | 62.31%  |
| 2     | 43       | 33.08%  |
| 3     | 6        | 4.62%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 95       | 73.08%  |
| Yes  | 35       | 26.92%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 14       | 32.56%  |
| Cambridge Silicon Radio | 8        | 18.6%   |
| Realtek Semiconductor   | 5        | 11.63%  |
| MediaTek                | 5        | 11.63%  |
| Broadcom                | 4        | 9.3%    |
| TP-Link                 | 2        | 4.65%   |
| Foxconn / Hon Hai       | 2        | 4.65%   |
| ASUSTek Computer        | 2        | 4.65%   |
| Apple                   | 1        | 2.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 8        | 18.6%   |
| Realtek Bluetooth Radio                               | 5        | 11.63%  |
| MediaTek Wireless_Device                              | 5        | 11.63%  |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 4        | 9.3%    |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 3        | 6.98%   |
| Intel Bluetooth wireless interface                    | 3        | 6.98%   |
| Intel AX200 Bluetooth                                 | 3        | 6.98%   |
| TP-Link TP-Link Bluetooth USB Adapter                 | 2        | 4.65%   |
| Intel AX210 Bluetooth                                 | 2        | 4.65%   |
| Foxconn / Hon Hai Bluetooth Device                    | 2        | 4.65%   |
| Intel Wireless-AC 3168 Bluetooth                      | 1        | 2.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 1        | 2.33%   |
| Intel AX211 Bluetooth                                 | 1        | 2.33%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 1        | 2.33%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 2.33%   |
| Apple Bluetooth Host Controller                       | 1        | 2.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 88       | 39.11%  |
| AMD                     | 53       | 23.56%  |
| Nvidia                  | 47       | 20.89%  |
| C-Media Electronics     | 8        | 3.56%   |
| Creative Labs           | 5        | 2.22%   |
| VIA Technologies        | 2        | 0.89%   |
| Texas Instruments       | 2        | 0.89%   |
| ROCCAT                  | 2        | 0.89%   |
| Generalplus Technology  | 2        | 0.89%   |
| TerraTec Electronic     | 1        | 0.44%   |
| Tenx Technology         | 1        | 0.44%   |
| Setek Elektronik        | 1        | 0.44%   |
| Schiit Audio            | 1        | 0.44%   |
| Razer USA               | 1        | 0.44%   |
| M-Audio                 | 1        | 0.44%   |
| Kingston Technology     | 1        | 0.44%   |
| JMTek                   | 1        | 0.44%   |
| Jieli Technology        | 1        | 0.44%   |
| GYROCOM C&C             | 1        | 0.44%   |
| GN Netcom               | 1        | 0.44%   |
| Giga-Byte Technology    | 1        | 0.44%   |
| Ensoniq                 | 1        | 0.44%   |
| Digidesign              | 1        | 0.44%   |
| Cambridge Silicon Radio | 1        | 0.44%   |
| BEHRINGER International | 1        | 0.44%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                           | Desktops | Percent |
|-------------------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                             | 12       | 4.63%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                      | 12       | 4.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                | 9        | 3.47%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                      | 9        | 3.47%   |
| AMD SBx00 Azalia (Intel HDA)                                                                    | 9        | 3.47%   |
| Nvidia GP107GL High Definition Audio Controller                                                 | 7        | 2.7%    |
| AMD Starship/Matisse HD Audio Controller                                                        | 7        | 2.7%    |
| Nvidia GP104 High Definition Audio Controller                                                   | 6        | 2.32%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                             | 6        | 2.32%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                        | 6        | 2.32%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                             | 6        | 2.32%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                      | 6        | 2.32%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                         | 5        | 1.93%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                             | 5        | 1.93%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                             | 5        | 1.93%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                         | 5        | 1.93%   |
| Nvidia GP108 High Definition Audio Controller                                                   | 4        | 1.54%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                   | 4        | 1.54%   |
| Intel Cannon Lake PCH cAVS                                                                      | 4        | 1.54%   |
| Intel Alder Lake-S HD Audio Controller                                                          | 4        | 1.54%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                 | 4        | 1.54%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                               | 4        | 1.54%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                           | 4        | 1.54%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                           | 3        | 1.16%   |
| Intel Smart Sound Technology (SST) Audio Controller                                             | 3        | 1.16%   |
| Intel C610/X99 series chipset HD Audio Controller                                               | 3        | 1.16%   |
| Intel 9 Series Chipset Family HD Audio Controller                                               | 3        | 1.16%   |
| Intel 200 Series PCH HD Audio                                                                   | 3        | 1.16%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 3        | 1.16%   |
| AMD Renoir Radeon High Definition Audio Controller                                              | 3        | 1.16%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                         | 3        | 1.16%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                          | 3        | 1.16%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]               | 3        | 1.16%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                    | 3        | 1.16%   |
| Texas Instruments PCM2902 Audio Codec                                                           | 2        | 0.77%   |
| ROCCAT Khan AIMO                                                                                | 2        | 0.77%   |
| Nvidia TU104 HD Audio Controller                                                                | 2        | 0.77%   |
| Nvidia MCP61 High Definition Audio                                                              | 2        | 0.77%   |
| Nvidia GM206 High Definition Audio Controller                                                   | 2        | 0.77%   |
| Nvidia GK107 HDMI Audio Controller                                                              | 2        | 0.77%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 22       | 14.86%  |
| Unknown             | 20       | 13.51%  |
| Samsung Electronics | 18       | 12.16%  |
| Corsair             | 18       | 12.16%  |
| SK hynix            | 10       | 6.76%   |
| G.Skill             | 10       | 6.76%   |
| Crucial             | 10       | 6.76%   |
| Ramaxel Technology  | 7        | 4.73%   |
| A-DATA Technology   | 7        | 4.73%   |
| Nanya Technology    | 6        | 4.05%   |
| Unknown (ABCD)      | 3        | 2.03%   |
| Micron Technology   | 3        | 2.03%   |
| Transcend           | 2        | 1.35%   |
| Unknown             | 2        | 1.35%   |
| Unknown (AB)        | 1        | 0.68%   |
| Unknown (0x0E9D)    | 1        | 0.68%   |
| Unifosa             | 1        | 0.68%   |
| Patriot             | 1        | 0.68%   |
| Lexar Co Limited    | 1        | 0.68%   |
| Golden Empire       | 1        | 0.68%   |
| Elpida              | 1        | 0.68%   |
| CSX                 | 1        | 0.68%   |
| Avant               | 1        | 0.68%   |
| Apacer              | 1        | 0.68%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 4        | 2.52%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM DDR3 2400MT/s     | 3        | 1.89%   |
| Unknown RAM Module 4GB DIMM SDRAM                                | 2        | 1.26%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                         | 2        | 1.26%   |
| Unknown RAM Module 2GB DIMM 667MT/s                              | 2        | 1.26%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM 1333MT/s                  | 2        | 1.26%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s              | 2        | 1.26%   |
| Kingston RAM 9905471-006.A00LF 4GB DIMM DDR3 1333MT/s            | 2        | 1.26%   |
| G.Skill RAM F4-4000C18-16GTZR 16GB DIMM DDR4 2667MT/s            | 2        | 1.26%   |
| Crucial RAM BLS8G4D32AESBK.M8FE1 8GB DIMM DDR4 3600MT/s          | 2        | 1.26%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1800MT/s            | 2        | 1.26%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1800MT/s              | 2        | 1.26%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3800MT/s           | 2        | 1.26%   |
| Unknown                                                          | 2        | 1.26%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 1        | 0.63%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 1        | 0.63%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1        | 0.63%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                        | 1        | 0.63%   |
| Unknown RAM Module 4GB DIMM DDR2 533MT/s                         | 1        | 0.63%   |
| Unknown RAM Module 4GB DIMM 667MT/s                              | 1        | 0.63%   |
| Unknown RAM Module 4GB DIMM                                      | 1        | 0.63%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 1        | 0.63%   |
| Unknown RAM Module 2GB DIMM DDR2 1067MT/s                        | 1        | 0.63%   |
| Unknown RAM Module 2GB DIMM DDR2                                 | 1        | 0.63%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 1        | 0.63%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 1        | 0.63%   |
| Unknown RAM Module 1GB DIMM SDRAM                                | 1        | 0.63%   |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s                         | 1        | 0.63%   |
| Unknown (AB) RAM Module 2GB DIMM LPDDR3 1333MT/s                 | 1        | 0.63%   |
| Unknown (0x0E9D) RAM KINSOTIN8GB2666MHZ 8GB SODIMM DDR4 2667MT/s | 1        | 0.63%   |
| Unifosa RAM Module 2GB DIMM DDR3 1333MT/s                        | 1        | 0.63%   |
| Transcend RAM JM800QLU-2G 2GB DIMM DDR2 2048MT/s                 | 1        | 0.63%   |
| Transcend RAM JM1333KLN-8GK 4GB DIMM DDR3 1333MT/s               | 1        | 0.63%   |
| SK hynix RAM HMT451U6AFR8A-PB 4GB DIMM DDR3 1600MT/s             | 1        | 0.63%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1        | 0.63%   |
| SK hynix RAM HMT41GU6MFR8C 8GB DIMM DDR3 1866MT/s                | 1        | 0.63%   |
| SK hynix RAM HMT41GU6BFR8C-PB 8GB DIMM DDR3 1600MT/s             | 1        | 0.63%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1        | 0.63%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1        | 0.63%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM 1600MT/s                  | 1        | 0.63%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 51       | 37.5%   |
| DDR3    | 47       | 34.56%  |
| SDRAM   | 10       | 7.35%   |
| DDR2    | 10       | 7.35%   |
| Unknown | 8        | 5.88%   |
| DDR5    | 5        | 3.68%   |
| LPDDR4  | 3        | 2.21%   |
| LPDDR3  | 1        | 0.74%   |
| DDR     | 1        | 0.74%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 117      | 91.41%  |
| SODIMM | 11       | 8.59%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 39       | 28.06%  |
| 8192  | 33       | 23.74%  |
| 16384 | 28       | 20.14%  |
| 2048  | 24       | 17.27%  |
| 32768 | 7        | 5.04%   |
| 1024  | 7        | 5.04%   |
| 256   | 1        | 0.72%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1333    | 22       | 15.6%   |
| 1600    | 21       | 14.89%  |
| 3600    | 13       | 9.22%   |
| 3200    | 12       | 8.51%   |
| 2667    | 9        | 6.38%   |
| 2400    | 8        | 5.67%   |
| 1800    | 5        | 3.55%   |
| 800     | 5        | 3.55%   |
| 667     | 5        | 3.55%   |
| Unknown | 5        | 3.55%   |
| 6000    | 3        | 2.13%   |
| 3000    | 3        | 2.13%   |
| 3800    | 2        | 1.42%   |
| 2933    | 2        | 1.42%   |
| 2666    | 2        | 1.42%   |
| 2133    | 2        | 1.42%   |
| 2048    | 2        | 1.42%   |
| 1866    | 2        | 1.42%   |
| 1067    | 2        | 1.42%   |
| 533     | 2        | 1.42%   |
| 333     | 2        | 1.42%   |
| 5800    | 1        | 0.71%   |
| 4800    | 1        | 0.71%   |
| 4133    | 1        | 0.71%   |
| 3866    | 1        | 0.71%   |
| 3733    | 1        | 0.71%   |
| 3266    | 1        | 0.71%   |
| 3066    | 1        | 0.71%   |
| 2200    | 1        | 0.71%   |
| 2000    | 1        | 0.71%   |
| 1867    | 1        | 0.71%   |
| 1066    | 1        | 0.71%   |
| 400     | 1        | 0.71%   |

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
| Logitech                      | 11       | 39.29%  |
| Microdia                      | 4        | 14.29%  |
| Sunplus Innovation Technology | 3        | 10.71%  |
| Microsoft                     | 3        | 10.71%  |
| Chicony Electronics           | 2        | 7.14%   |
| Sonix Technology              | 1        | 3.57%   |
| Pixart Imaging                | 1        | 3.57%   |
| Hewlett-Packard               | 1        | 3.57%   |
| Generalplus Technology        | 1        | 3.57%   |
| Arkmicro Technologies         | 1        | 3.57%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Logitech Webcam C270                 | 4        | 14.29%  |
| Logitech Webcam C930e                | 3        | 10.71%  |
| Sunplus HD 720P webcam               | 2        | 7.14%   |
| Microsoft LifeCam HD-3000            | 2        | 7.14%   |
| Sunplus USB Camera                   | 1        | 3.57%   |
| Sonix HDF Webcam USB                 | 1        | 3.57%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro | 1        | 3.57%   |
| Microsoft LifeCam VX-500 [1357]      | 1        | 3.57%   |
| Microdia USB 2.0 Camera              | 1        | 3.57%   |
| Microdia Sonix USB 2.0 Camera        | 1        | 3.57%   |
| Microdia Integrated Camera           | 1        | 3.57%   |
| Microdia Camera                      | 1        | 3.57%   |
| Logitech Webcam C600                 | 1        | 3.57%   |
| Logitech Webcam C310                 | 1        | 3.57%   |
| Logitech Webcam C110                 | 1        | 3.57%   |
| Logitech HD Webcam C615              | 1        | 3.57%   |
| HP HP Webcam HD 2300                 | 1        | 3.57%   |
| Generalplus GENERAL WEBCAM           | 1        | 3.57%   |
| Chicony HP Prem AF Webcam KQ245AA    | 1        | 3.57%   |
| Chicony HD Webcam                    | 1        | 3.57%   |
| Arkmicro USB2.0 PC CAMERA            | 1        | 3.57%   |

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
| 0     | 103      | 79.23%  |
| 1     | 24       | 18.46%  |
| 2     | 2        | 1.54%   |
| 3     | 1        | 0.77%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 13       | 44.83%  |
| Net/wireless             | 7        | 24.14%  |
| Unassigned class         | 3        | 10.34%  |
| Communication controller | 3        | 10.34%  |
| Fingerprint reader       | 1        | 3.45%   |
| Dvb card                 | 1        | 3.45%   |
| Card reader              | 1        | 3.45%   |

