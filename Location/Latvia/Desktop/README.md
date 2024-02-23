Linux in Latvia - Tested Hardware & Statistics (Desktops)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Latvia.

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

Total: 181

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 8055                        | [ee3ece9007](https://linux-hardware.org/?probe=ee3ece9007) | Jan 05, 2024 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [84d4572994](https://linux-hardware.org/?probe=84d4572994) | Dec 12, 2023 |
| MSI           | H61M-E33                    | [ed1dc1d923](https://linux-hardware.org/?probe=ed1dc1d923) | Dec 09, 2023 |
| Biostar       | B450MH                      | [e490dfb129](https://linux-hardware.org/?probe=e490dfb129) | Dec 02, 2023 |
| ASRock        | B550M-HDV                   | [68c7c96b9b](https://linux-hardware.org/?probe=68c7c96b9b) | Dec 02, 2023 |
| MSI           | Z390-A PRO                  | [1f07a66db1](https://linux-hardware.org/?probe=1f07a66db1) | Nov 22, 2023 |
| MSI           | X370 SLI PLUS               | [2ac0a2ecc8](https://linux-hardware.org/?probe=2ac0a2ecc8) | Oct 23, 2023 |
| ASRock        | H610M-HVS/M.2 R2.0          | [74df5e1893](https://linux-hardware.org/?probe=74df5e1893) | Oct 21, 2023 |
| Intel         | DH55HC AAE70933-505         | [f1bc373847](https://linux-hardware.org/?probe=f1bc373847) | Oct 19, 2023 |
| Shenzhen M... | F6BFC                       | [007ce9ca02](https://linux-hardware.org/?probe=007ce9ca02) | Oct 14, 2023 |
| Shenzhen M... | F6BFC                       | [e71b9295ca](https://linux-hardware.org/?probe=e71b9295ca) | Oct 11, 2023 |
| Shenzhen M... | F6BFC                       | [ca89a07b9e](https://linux-hardware.org/?probe=ca89a07b9e) | Sep 10, 2023 |
| Shenzhen M... | F6BFC                       | [a33ec74b50](https://linux-hardware.org/?probe=a33ec74b50) | Sep 05, 2023 |
| Shenzhen M... | F6BFC                       | [d5cd8916d0](https://linux-hardware.org/?probe=d5cd8916d0) | Sep 05, 2023 |
| HP            | 0A9Ch                       | [f5d07e235d](https://linux-hardware.org/?probe=f5d07e235d) | Aug 24, 2023 |
| MSI           | B450M PRO-VDH MAX           | [1d9653f23a](https://linux-hardware.org/?probe=1d9653f23a) | Aug 13, 2023 |
| Gigabyte      | G33M-S2                     | [cf3b586958](https://linux-hardware.org/?probe=cf3b586958) | Jul 22, 2023 |
| Gigabyte      | G33M-S2                     | [ce4d4f4137](https://linux-hardware.org/?probe=ce4d4f4137) | Jul 22, 2023 |
| ASRock        | Z370 Gaming K6              | [cc05c0d021](https://linux-hardware.org/?probe=cc05c0d021) | Jul 09, 2023 |
| ASUSTek       | ROG ZENITH EXTREME          | [5dc49896e5](https://linux-hardware.org/?probe=5dc49896e5) | Jun 16, 2023 |
| Gigabyte      | Z87-HD3                     | [228a46e465](https://linux-hardware.org/?probe=228a46e465) | Jun 04, 2023 |
| Gigabyte      | G33M-S2                     | [17ed1704c5](https://linux-hardware.org/?probe=17ed1704c5) | Jun 04, 2023 |
| Gigabyte      | G33M-S2                     | [82bab4dd6d](https://linux-hardware.org/?probe=82bab4dd6d) | Jun 04, 2023 |
| ASRock        | 960GC-GS FX                 | [1cd850e8af](https://linux-hardware.org/?probe=1cd850e8af) | Apr 25, 2023 |
| ASUSTek       | AM1M-A                      | [120f5780bd](https://linux-hardware.org/?probe=120f5780bd) | Apr 09, 2023 |
| Biostar       | B550MX/E PRO                | [cffcb0a2a6](https://linux-hardware.org/?probe=cffcb0a2a6) | Mar 30, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [78046d9b99](https://linux-hardware.org/?probe=78046d9b99) | Mar 29, 2023 |
| HP            | 0AA8h                       | [fecbec6708](https://linux-hardware.org/?probe=fecbec6708) | Mar 19, 2023 |
| ASRock        | B75 Pro3-M                  | [3574e6c0f8](https://linux-hardware.org/?probe=3574e6c0f8) | Mar 04, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [3e3368d913](https://linux-hardware.org/?probe=3e3368d913) | Feb 28, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [7fe6e0dcde](https://linux-hardware.org/?probe=7fe6e0dcde) | Feb 24, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [455b0e1401](https://linux-hardware.org/?probe=455b0e1401) | Feb 23, 2023 |
| MSI           | B75A-G43                    | [bf426ce3c3](https://linux-hardware.org/?probe=bf426ce3c3) | Feb 18, 2023 |
| Gigabyte      | H55M-D2H                    | [652695efb0](https://linux-hardware.org/?probe=652695efb0) | Feb 06, 2023 |
| Gigabyte      | Z790 GAMING X AX            | [1c6725b5eb](https://linux-hardware.org/?probe=1c6725b5eb) | Feb 04, 2023 |
| ASUSTek       | ROG STRIX B360-I GAMING     | [8f81628b59](https://linux-hardware.org/?probe=8f81628b59) | Jan 27, 2023 |
| ASRock        | B75 Pro3-M                  | [4f28b4be44](https://linux-hardware.org/?probe=4f28b4be44) | Jan 15, 2023 |
| ASRock        | B75 Pro3-M                  | [4884803279](https://linux-hardware.org/?probe=4884803279) | Jan 10, 2023 |
| ASRock        | B75 Pro3-M                  | [49b7bb70f3](https://linux-hardware.org/?probe=49b7bb70f3) | Jan 10, 2023 |
| ASUSTek       | P5KPL-CM                    | [625bf5665f](https://linux-hardware.org/?probe=625bf5665f) | Jan 07, 2023 |
| ASUSTek       | PRIME B350M-A               | [df845fe4a9](https://linux-hardware.org/?probe=df845fe4a9) | Jan 07, 2023 |
| Dell          | 0HY9JP A01                  | [0532ee0c1e](https://linux-hardware.org/?probe=0532ee0c1e) | Jan 05, 2023 |
| ASUSTek       | B85-PLUS                    | [cbad10e284](https://linux-hardware.org/?probe=cbad10e284) | Dec 21, 2022 |
| Dell          | 02YYK5 A00                  | [1168ac14f5](https://linux-hardware.org/?probe=1168ac14f5) | Dec 09, 2022 |
| MSI           | B450M-A PRO MAX             | [46a6e9e722](https://linux-hardware.org/?probe=46a6e9e722) | Dec 07, 2022 |
| Gigabyte      | Z87-HD3                     | [d9a78cb529](https://linux-hardware.org/?probe=d9a78cb529) | Nov 30, 2022 |
| Gigabyte      | G33M-S2                     | [3d6a965dd4](https://linux-hardware.org/?probe=3d6a965dd4) | Nov 30, 2022 |
| Gigabyte      | 946GMX-S2                   | [6c97b310fb](https://linux-hardware.org/?probe=6c97b310fb) | Nov 29, 2022 |
| Gigabyte      | M61PME-S2                   | [4768ab429e](https://linux-hardware.org/?probe=4768ab429e) | Nov 23, 2022 |
| ASUSTek       | PRIME X470-PRO              | [e4470c4bda](https://linux-hardware.org/?probe=e4470c4bda) | Nov 12, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [7712ce88c4](https://linux-hardware.org/?probe=7712ce88c4) | Oct 30, 2022 |
| ASUSTek       | P5Q SE2                     | [7d576ac245](https://linux-hardware.org/?probe=7d576ac245) | Oct 29, 2022 |
| Gigabyte      | G41M-ES2L                   | [e267cad212](https://linux-hardware.org/?probe=e267cad212) | Oct 20, 2022 |
| Gigabyte      | G41M-ES2L                   | [69adb866e0](https://linux-hardware.org/?probe=69adb866e0) | Oct 20, 2022 |
| Gigabyte      | 946GMX-S2                   | [491d0c69ca](https://linux-hardware.org/?probe=491d0c69ca) | Oct 12, 2022 |
| Gigabyte      | 946GMX-S2                   | [09ee887f3a](https://linux-hardware.org/?probe=09ee887f3a) | Oct 12, 2022 |
| ASRock        | N68C-S UCC                  | [734baf54fa](https://linux-hardware.org/?probe=734baf54fa) | Oct 04, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [46e48bc4c1](https://linux-hardware.org/?probe=46e48bc4c1) | Sep 28, 2022 |
| Gigabyte      | B450 GAMING X               | [982d41c1eb](https://linux-hardware.org/?probe=982d41c1eb) | Sep 25, 2022 |
| Gigabyte      | B450 GAMING X               | [a5d5950e29](https://linux-hardware.org/?probe=a5d5950e29) | Sep 25, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [8d8440548e](https://linux-hardware.org/?probe=8d8440548e) | Sep 20, 2022 |
| Gigabyte      | G33M-S2                     | [5bd6c356cd](https://linux-hardware.org/?probe=5bd6c356cd) | Aug 03, 2022 |
| Gigabyte      | Z87-HD3                     | [83936d3cf0](https://linux-hardware.org/?probe=83936d3cf0) | Jul 31, 2022 |
| Gigabyte      | G33M-S2                     | [0a96778f7c](https://linux-hardware.org/?probe=0a96778f7c) | Jul 30, 2022 |
| Gigabyte      | G33M-S2                     | [c6c4a561e1](https://linux-hardware.org/?probe=c6c4a561e1) | Jul 17, 2022 |
| Gigabyte      | H97-D3H-CF                  | [e9aa6d6be1](https://linux-hardware.org/?probe=e9aa6d6be1) | Jul 06, 2022 |
| Gigabyte      | G33M-S2                     | [1acedf0aa3](https://linux-hardware.org/?probe=1acedf0aa3) | Jun 26, 2022 |
| Gigabyte      | G33M-S2                     | [949fb9a5e7](https://linux-hardware.org/?probe=949fb9a5e7) | Jun 24, 2022 |
| MSI           | A68HM-E33 V2                | [b473ea12dc](https://linux-hardware.org/?probe=b473ea12dc) | Jun 12, 2022 |
| Foxconn       | 2ADA                        | [1242ad2894](https://linux-hardware.org/?probe=1242ad2894) | Jun 06, 2022 |
| Lenovo        | 3716 SDK0T76463 WIN 3422... | [cd15058963](https://linux-hardware.org/?probe=cd15058963) | May 16, 2022 |
| Lenovo        | 3716 SDK0T76463 WIN 3422... | [4043d7e26a](https://linux-hardware.org/?probe=4043d7e26a) | May 11, 2022 |
| Dell          | 02YYK5 A01                  | [19dd091f8b](https://linux-hardware.org/?probe=19dd091f8b) | May 01, 2022 |
| HP            | 2AAC                        | [1f6b08507e](https://linux-hardware.org/?probe=1f6b08507e) | May 01, 2022 |
| ASRock        | X79 Extreme9                | [e483a6e634](https://linux-hardware.org/?probe=e483a6e634) | Apr 19, 2022 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | [cadff96ec0](https://linux-hardware.org/?probe=cadff96ec0) | Apr 11, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [fe293471a7](https://linux-hardware.org/?probe=fe293471a7) | Apr 08, 2022 |
| Acer          | WG43M                       | [c7cb6ee141](https://linux-hardware.org/?probe=c7cb6ee141) | Apr 08, 2022 |
| ASUSTek       | P8P67 LE                    | [f7eb22bcfc](https://linux-hardware.org/?probe=f7eb22bcfc) | Mar 27, 2022 |
| ABIT          | IP35-E                      | [9d6e95572e](https://linux-hardware.org/?probe=9d6e95572e) | Mar 21, 2022 |
| ABIT          | IP35-E                      | [3d93ef42c9](https://linux-hardware.org/?probe=3d93ef42c9) | Mar 21, 2022 |
| MSI           | H110M PRO-VD                | [83df25aace](https://linux-hardware.org/?probe=83df25aace) | Feb 18, 2022 |
| ASRock        | X79 Extreme9                | [9dfc1ac601](https://linux-hardware.org/?probe=9dfc1ac601) | Feb 12, 2022 |
| ASRock        | X79 Extreme9                | [0848fdb73f](https://linux-hardware.org/?probe=0848fdb73f) | Feb 12, 2022 |
| ASUSTek       | P5Q-EM                      | [834bc65728](https://linux-hardware.org/?probe=834bc65728) | Feb 04, 2022 |
| ASUSTek       | P5Q-EM                      | [887e40e6c7](https://linux-hardware.org/?probe=887e40e6c7) | Feb 04, 2022 |
| Dell          | 02YYK5 A01                  | [e41c34594e](https://linux-hardware.org/?probe=e41c34594e) | Jan 11, 2022 |
| MSI           | P55-GD65                    | [37da95512b](https://linux-hardware.org/?probe=37da95512b) | Dec 28, 2021 |
| ASRock        | FM2A88X Extreme4+           | [a864c07042](https://linux-hardware.org/?probe=a864c07042) | Dec 05, 2021 |
| HP            | 304Bh                       | [643a84ae14](https://linux-hardware.org/?probe=643a84ae14) | Oct 26, 2021 |
| HP            | 304Bh                       | [b7bd300808](https://linux-hardware.org/?probe=b7bd300808) | Oct 22, 2021 |
| MSI           | B450M-A PRO MAX             | [4148046f02](https://linux-hardware.org/?probe=4148046f02) | Oct 17, 2021 |
| ASUSTek       | P5Q-EM                      | [7f6f4bedd3](https://linux-hardware.org/?probe=7f6f4bedd3) | Sep 14, 2021 |
| Intel         | DH77EB AAG39073-304         | [7e44f2ff81](https://linux-hardware.org/?probe=7e44f2ff81) | Sep 06, 2021 |
| ASUSTek       | Z97-K/USB                   | [071ad478e7](https://linux-hardware.org/?probe=071ad478e7) | Aug 30, 2021 |
| ASRock        | ALiveXFire-eSATA2           | [5b32c9197c](https://linux-hardware.org/?probe=5b32c9197c) | Aug 28, 2021 |
| ASRock        | ALiveXFire-eSATA2           | [8cd8b7faa5](https://linux-hardware.org/?probe=8cd8b7faa5) | Aug 28, 2021 |
| Intel         | DH77EB AAG39073-304         | [13fb44b235](https://linux-hardware.org/?probe=13fb44b235) | Aug 13, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [bc618727f4](https://linux-hardware.org/?probe=bc618727f4) | Aug 10, 2021 |
| Dell          | 0GXM1W A00                  | [6aa52c9eb8](https://linux-hardware.org/?probe=6aa52c9eb8) | Aug 02, 2021 |
| MSI           | H310M PRO-VD                | [42ade7f952](https://linux-hardware.org/?probe=42ade7f952) | Jun 10, 2021 |
| ASUSTek       | Z97-K R2.0                  | [25a9c64af7](https://linux-hardware.org/?probe=25a9c64af7) | May 29, 2021 |
| MSI           | H81M-E35                    | [2d479e2946](https://linux-hardware.org/?probe=2d479e2946) | May 15, 2021 |
| MSI           | H81M-E35                    | [621d19b1f1](https://linux-hardware.org/?probe=621d19b1f1) | May 15, 2021 |
| ASUSTek       | Z97-K R2.0                  | [796bb8e1b8](https://linux-hardware.org/?probe=796bb8e1b8) | May 12, 2021 |
| MSI           | B450M-A PRO MAX             | [4d87fd7e46](https://linux-hardware.org/?probe=4d87fd7e46) | Apr 13, 2021 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | [817d1bb360](https://linux-hardware.org/?probe=817d1bb360) | Apr 03, 2021 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | [ca1692012f](https://linux-hardware.org/?probe=ca1692012f) | Apr 03, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [d2a175100f](https://linux-hardware.org/?probe=d2a175100f) | Mar 22, 2021 |
| ASUSTek       | PRIME Z270-P                | [344b4339b4](https://linux-hardware.org/?probe=344b4339b4) | Mar 17, 2021 |
| Gigabyte      | B550 AORUS PRO V2           | [1194a50093](https://linux-hardware.org/?probe=1194a50093) | Mar 16, 2021 |
| HP            | 18E7                        | [d0fb912292](https://linux-hardware.org/?probe=d0fb912292) | Mar 09, 2021 |
| Acer          | F671CR R01-C0               | [7a4637f10b](https://linux-hardware.org/?probe=7a4637f10b) | Mar 06, 2021 |
| Dell          | 0HH807                      | [0ac539b524](https://linux-hardware.org/?probe=0ac539b524) | Mar 04, 2021 |
| Dell          | 0HH807                      | [dbde42fa23](https://linux-hardware.org/?probe=dbde42fa23) | Mar 04, 2021 |
| HP            | 304Bh                       | [a49a1ff054](https://linux-hardware.org/?probe=a49a1ff054) | Feb 27, 2021 |
| HP            | 304Bh                       | [92c6653702](https://linux-hardware.org/?probe=92c6653702) | Feb 27, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [3bc6f280d8](https://linux-hardware.org/?probe=3bc6f280d8) | Feb 19, 2021 |
| Gigabyte      | B550 AORUS PRO V2           | [0cfdd76052](https://linux-hardware.org/?probe=0cfdd76052) | Feb 08, 2021 |
| ASUSTek       | P5GD1-VM                    | [863b2fd0bf](https://linux-hardware.org/?probe=863b2fd0bf) | Jan 22, 2021 |
| Gigabyte      | G31M-ES2L                   | [5b1abefa3c](https://linux-hardware.org/?probe=5b1abefa3c) | Jan 07, 2021 |
| MSI           | B75A-G43                    | [23c8b4ee0a](https://linux-hardware.org/?probe=23c8b4ee0a) | Jan 06, 2021 |
| MSI           | 970A-G46                    | [e734d18206](https://linux-hardware.org/?probe=e734d18206) | Jan 06, 2021 |
| MSI           | 970A-G46                    | [b85445cf41](https://linux-hardware.org/?probe=b85445cf41) | Jan 06, 2021 |
| Gigabyte      | G31M-ES2L                   | [81b3dbf5fd](https://linux-hardware.org/?probe=81b3dbf5fd) | Jan 02, 2021 |
| Gigabyte      | G31M-ES2L                   | [c3b94fff22](https://linux-hardware.org/?probe=c3b94fff22) | Dec 31, 2020 |
| Gigabyte      | GA-970A-UD3                 | [2eede62ff5](https://linux-hardware.org/?probe=2eede62ff5) | Dec 26, 2020 |
| Gigabyte      | GA-970A-UD3                 | [8cf512e3a9](https://linux-hardware.org/?probe=8cf512e3a9) | Dec 26, 2020 |
| ASUSTek       | P5K PRO                     | [0e58a56cfb](https://linux-hardware.org/?probe=0e58a56cfb) | Dec 26, 2020 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | [bb01071f16](https://linux-hardware.org/?probe=bb01071f16) | Dec 15, 2020 |
| ASRock        | TRX40 Creator               | [dd14b01c46](https://linux-hardware.org/?probe=dd14b01c46) | Dec 13, 2020 |
| Intel         | DB85FL AAG89861-201         | [936daa5428](https://linux-hardware.org/?probe=936daa5428) | Nov 25, 2020 |
| MSI           | B75A-G43                    | [3674b1e802](https://linux-hardware.org/?probe=3674b1e802) | Nov 16, 2020 |
| MSI           | B75A-G43                    | [5f68cce112](https://linux-hardware.org/?probe=5f68cce112) | Nov 16, 2020 |
| Gigabyte      | AB350M-DS3H V2-CF           | [f2ff00472b](https://linux-hardware.org/?probe=f2ff00472b) | Nov 07, 2020 |
| ASUSTek       | P5Q-EM                      | [5139c9e029](https://linux-hardware.org/?probe=5139c9e029) | Nov 01, 2020 |
| Gigabyte      | AB350M-DS3H V2-CF           | [7ac6a6dab5](https://linux-hardware.org/?probe=7ac6a6dab5) | Oct 27, 2020 |
| ASUSTek       | PRIME H310T                 | [a37fe628b4](https://linux-hardware.org/?probe=a37fe628b4) | Oct 04, 2020 |
| ASUSTek       | PRIME H310T                 | [c6cf49892e](https://linux-hardware.org/?probe=c6cf49892e) | Oct 04, 2020 |
| Gigabyte      | AB350M-DS3H V2-CF           | [a6c2ba4977](https://linux-hardware.org/?probe=a6c2ba4977) | Oct 04, 2020 |
| Gigabyte      | B550I AORUS PRO AX          | [ebefa289ab](https://linux-hardware.org/?probe=ebefa289ab) | Sep 30, 2020 |
| Biostar       | NF61D-A2                    | [177f17803c](https://linux-hardware.org/?probe=177f17803c) | Aug 24, 2020 |
| Gigabyte      | H61MA-D2V                   | [625d32881c](https://linux-hardware.org/?probe=625d32881c) | May 29, 2020 |
| ASRock        | FM2A85X-ITX                 | [31631f3ea5](https://linux-hardware.org/?probe=31631f3ea5) | Apr 23, 2020 |
| Biostar       | NF61D-A2                    | [8f1f828d49](https://linux-hardware.org/?probe=8f1f828d49) | Apr 14, 2020 |
| ASUSTek       | P5QL-E                      | [95e2b82808](https://linux-hardware.org/?probe=95e2b82808) | Mar 26, 2020 |
| ASUSTek       | P5QL-E                      | [9fcf5501fb](https://linux-hardware.org/?probe=9fcf5501fb) | Mar 26, 2020 |
| IBM           | 8215ZCL                     | [8f44ceaa1e](https://linux-hardware.org/?probe=8f44ceaa1e) | Mar 26, 2020 |
| ASRock        | N68C-GS FX                  | [2d568b2e9d](https://linux-hardware.org/?probe=2d568b2e9d) | Feb 19, 2020 |
| MSI           | Z370 SLI PLUS               | [c76ba1a6d0](https://linux-hardware.org/?probe=c76ba1a6d0) | Feb 08, 2020 |
| Gigabyte      | H97-D3H-CF                  | [9deccd0d74](https://linux-hardware.org/?probe=9deccd0d74) | Jan 24, 2020 |
| ASUSTek       | Maximus VIII RANGER         | [e005197c6c](https://linux-hardware.org/?probe=e005197c6c) | Jan 09, 2020 |
| Intel         | DQ87PG AAG74154-403         | [5af3a0243a](https://linux-hardware.org/?probe=5af3a0243a) | Jan 06, 2020 |
| ASUSTek       | Maximus VIII RANGER         | [70297101fe](https://linux-hardware.org/?probe=70297101fe) | Dec 31, 2019 |
| Dell          | 0RJ290                      | [21ae6dbdf0](https://linux-hardware.org/?probe=21ae6dbdf0) | Dec 16, 2019 |
| ASUSTek       | Z87-DELUXE                  | [bab2716ff6](https://linux-hardware.org/?probe=bab2716ff6) | Dec 02, 2019 |
| Hardkernel    | ODROID-H2                   | [a6d137277e](https://linux-hardware.org/?probe=a6d137277e) | Sep 18, 2019 |
| Intel         | DQ87PG AAG74154-403         | [2fc2bdd742](https://linux-hardware.org/?probe=2fc2bdd742) | Sep 14, 2019 |
| Intel         | DQ87PG AAG74154-403         | [5110001e92](https://linux-hardware.org/?probe=5110001e92) | Sep 14, 2019 |
| Gigabyte      | Z87P-D3                     | [a7e732af2a](https://linux-hardware.org/?probe=a7e732af2a) | Aug 26, 2019 |
| MSI           | H310M PRO-VD                | [5c290c18c9](https://linux-hardware.org/?probe=5c290c18c9) | Aug 18, 2019 |
| HP            | 0A60h                       | [b031cf2f9c](https://linux-hardware.org/?probe=b031cf2f9c) | Jul 30, 2019 |
| MSI           | FM2-A55M-E33                | [426ae68b93](https://linux-hardware.org/?probe=426ae68b93) | Jun 29, 2019 |
| MSI           | B85-G41 PC Mate             | [0f3dccfe4e](https://linux-hardware.org/?probe=0f3dccfe4e) | Jun 26, 2019 |
| ASRock        | FM2A88X Extreme4+           | [5e414bc536](https://linux-hardware.org/?probe=5e414bc536) | Mar 14, 2019 |
| ASUSTek       | M2N-VM DVI                  | [3437fc1ab6](https://linux-hardware.org/?probe=3437fc1ab6) | Feb 12, 2019 |
| MSI           | H310M PRO-VD                | [f08ce9bd47](https://linux-hardware.org/?probe=f08ce9bd47) | Jan 09, 2019 |
| Dell          | 0WK833                      | [17e742f811](https://linux-hardware.org/?probe=17e742f811) | Jul 11, 2018 |
| Dell          | 0WK833                      | [d118bf168b](https://linux-hardware.org/?probe=d118bf168b) | Jun 28, 2018 |
| Dell          | 0WK833                      | [0e39368786](https://linux-hardware.org/?probe=0e39368786) | Jun 28, 2018 |
| ASRock        | FM2A88X Extreme4+           | [c401108ba6](https://linux-hardware.org/?probe=c401108ba6) | Jun 20, 2018 |
| Gigabyte      | H55M-D2H                    | [e4e92393a0](https://linux-hardware.org/?probe=e4e92393a0) | Mar 08, 2018 |
| ASUSTek       | H81M-K                      | [f4d998043d](https://linux-hardware.org/?probe=f4d998043d) | Jan 29, 2018 |
| ASUSTek       | A88XM-A                     | [f7b8e36550](https://linux-hardware.org/?probe=f7b8e36550) | Jan 21, 2018 |
| Acer          | F671CR R01-C0               | [a5b92562b9](https://linux-hardware.org/?probe=a5b92562b9) | Dec 26, 2017 |
| MSI           | MS-7519                     | [81563b0ef8](https://linux-hardware.org/?probe=81563b0ef8) | Nov 18, 2017 |
| MSI           | MS-7519                     | [5e4728fda0](https://linux-hardware.org/?probe=5e4728fda0) | Sep 17, 2017 |
| ASRock        | G31M-GS                     | [7a4eee4480](https://linux-hardware.org/?probe=7a4eee4480) | May 31, 2017 |
| Gigabyte      | H61M-S2-B3                  | [bfab333807](https://linux-hardware.org/?probe=bfab333807) | May 03, 2017 |
| Acer          | EG31M R01-A2                | [018dafc2d0](https://linux-hardware.org/?probe=018dafc2d0) | Apr 27, 2017 |
| ASUSTek       | P5Q                         | [26e2520232](https://linux-hardware.org/?probe=26e2520232) | Nov 11, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 6        | 4.65%   |
| Ubuntu 18.04                 | 6        | 4.65%   |
| ROSA R10                     | 6        | 4.65%   |
| Ubuntu 22.04                 | 5        | 3.88%   |
| ROSA R11                     | 5        | 3.88%   |
| KDE neon 20.04               | 5        | 3.88%   |
| Arch Rolling                 | 5        | 3.88%   |
| Linux Mint 20.1              | 4        | 3.1%    |
| Xubuntu 20.04                | 3        | 2.33%   |
| ROSA R9                      | 3        | 2.33%   |
| Linux Mint 21.1              | 3        | 2.33%   |
| Linux Mint 20.2              | 3        | 2.33%   |
| Fedora 38                    | 3        | 2.33%   |
| Fedora 37                    | 3        | 2.33%   |
| Zorin 16                     | 2        | 1.55%   |
| ROSA R8.1                    | 2        | 1.55%   |
| ROSA 12.2                    | 2        | 1.55%   |
| Pop!_OS 22.04                | 2        | 1.55%   |
| OpenMandriva 4.50            | 2        | 1.55%   |
| OpenMandriva 4.2             | 2        | 1.55%   |
| OpenMandriva 23.01           | 2        | 1.55%   |
| Linux Mint 20.3              | 2        | 1.55%   |
| Linux Mint 19.3              | 2        | 1.55%   |
| Fedora 39                    | 2        | 1.55%   |
| Fedora 35                    | 2        | 1.55%   |
| Fedora 30                    | 2        | 1.55%   |
| Debian Testing               | 2        | 1.55%   |
| Debian 11                    | 2        | 1.55%   |
| Xubuntu 18.04                | 1        | 0.78%   |
| Ubuntu 23.10                 | 1        | 0.78%   |
| Ubuntu 22.10                 | 1        | 0.78%   |
| Ubuntu 19.10                 | 1        | 0.78%   |
| Ubuntu 16.04                 | 1        | 0.78%   |
| SteamOS 3.4                  | 1        | 0.78%   |
| SteamOS 3.3                  | 1        | 0.78%   |
| ROSA R8                      | 1        | 0.78%   |
| ROSA R11.1                   | 1        | 0.78%   |
| Puppy 9                      | 1        | 0.78%   |
| Pop!_OS 21.04                | 1        | 0.78%   |
| openSUSE Tumbleweed-XXXXXXXX | 1        | 0.78%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 21       | 17.5%   |
| ROSA         | 18       | 15%     |
| Linux Mint   | 16       | 13.33%  |
| Fedora       | 13       | 10.83%  |
| OpenMandriva | 9        | 7.5%    |
| KDE neon     | 6        | 5%      |
| Arch         | 6        | 5%      |
| Xubuntu      | 4        | 3.33%   |
| Debian       | 4        | 3.33%   |
| Pop!_OS      | 3        | 2.5%    |
| Kubuntu      | 3        | 2.5%    |
| Zorin        | 2        | 1.67%   |
| Manjaro      | 2        | 1.67%   |
| Garuda Linux | 2        | 1.67%   |
| Clear Linux  | 2        | 1.67%   |
| SteamOS      | 1        | 0.83%   |
| Puppy        | 1        | 0.83%   |
| openSUSE     | 1        | 0.83%   |
| Lubuntu      | 1        | 0.83%   |
| LMDE         | 1        | 0.83%   |
| Kali         | 1        | 0.83%   |
| Endless      | 1        | 0.83%   |
| EndeavourOS  | 1        | 0.83%   |
| ALT Linux    | 1        | 0.83%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Desktops | Percent |
|---------------------------------|----------|---------|
| 4.9.60-nrj-desktop-1rosa-x86_64 | 5        | 3.57%   |
| 5.4.0-58-generic                | 4        | 2.86%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 4        | 2.86%   |
| 5.4.0-132-generic               | 3        | 2.14%   |
| 5.4.0-122-generic               | 3        | 2.14%   |
| 4.15.0-desktop-45.1rosa-x86_64  | 3        | 2.14%   |
| 6.5.7-200.fc38.x86_64           | 2        | 1.43%   |
| 6.1.1-desktop-1omv2290          | 2        | 1.43%   |
| 5.4.0-66-generic                | 2        | 1.43%   |
| 5.4.0-54-generic                | 2        | 1.43%   |
| 5.13.0-39-generic               | 2        | 1.43%   |
| 5.12.4-desktop-1omv4050         | 2        | 1.43%   |
| 5.10.14-desktop-1omv4002        | 2        | 1.43%   |
| 5.0.0-37-generic                | 2        | 1.43%   |
| 6.6.9-200.fc39.x86_64           | 1        | 0.71%   |
| 6.6.3-arch1-1                   | 1        | 0.71%   |
| 6.6.2-201.fc39.x86_64           | 1        | 0.71%   |
| 6.5.0-14-generic                | 1        | 0.71%   |
| 6.4.6-76060406-generic          | 1        | 0.71%   |
| 6.4.11-desktop-1omv2390         | 1        | 0.71%   |
| 6.3.7-200.fc38.x86_64           | 1        | 0.71%   |
| 6.2.6-desktop-1omv2390          | 1        | 0.71%   |
| 6.2.6-76060206-generic          | 1        | 0.71%   |
| 6.2.0-26-generic                | 1        | 0.71%   |
| 6.2.0-060200rc5-generic         | 1        | 0.71%   |
| 6.1.9-200.fc37.x86_64           | 1        | 0.71%   |
| 6.1.66-std-def-alt1             | 1        | 0.71%   |
| 6.1.1-arch1-1                   | 1        | 0.71%   |
| 6.1.0-7-amd64                   | 1        | 0.71%   |
| 6.0.7-1-default                 | 1        | 0.71%   |
| 6.0.16-300.fc37.x86_64          | 1        | 0.71%   |
| 6.0.13-300.fc37.x86_64          | 1        | 0.71%   |
| 6.0.11-AMD-znver2               | 1        | 0.71%   |
| 5.9.13-1006.native              | 1        | 0.71%   |
| 5.9.0-kali1-amd64               | 1        | 0.71%   |
| 5.8.12-arch1-1                  | 1        | 0.71%   |
| 5.8.0-50-generic                | 1        | 0.71%   |
| 5.8.0-44-generic                | 1        | 0.71%   |
| 5.8.0-25-generic                | 1        | 0.71%   |
| 5.6.3-arch1-1                   | 1        | 0.71%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 19       | 14.62%  |
| 5.15.0  | 11       | 8.46%   |
| 4.15.0  | 10       | 7.69%   |
| 5.13.0  | 5        | 3.85%   |
| 4.9.60  | 5        | 3.85%   |
| 4.9.20  | 5        | 3.85%   |
| 5.3.0   | 4        | 3.08%   |
| 5.19.0  | 4        | 3.08%   |
| 6.1.1   | 3        | 2.31%   |
| 5.8.0   | 3        | 2.31%   |
| 5.11.0  | 3        | 2.31%   |
| 6.5.7   | 2        | 1.54%   |
| 6.2.6   | 2        | 1.54%   |
| 6.2.0   | 2        | 1.54%   |
| 5.12.4  | 2        | 1.54%   |
| 5.10.14 | 2        | 1.54%   |
| 5.10.0  | 2        | 1.54%   |
| 5.0.0   | 2        | 1.54%   |
| 6.6.9   | 1        | 0.77%   |
| 6.6.3   | 1        | 0.77%   |
| 6.6.2   | 1        | 0.77%   |
| 6.5.0   | 1        | 0.77%   |
| 6.4.6   | 1        | 0.77%   |
| 6.4.11  | 1        | 0.77%   |
| 6.3.7   | 1        | 0.77%   |
| 6.1.9   | 1        | 0.77%   |
| 6.1.66  | 1        | 0.77%   |
| 6.1.0   | 1        | 0.77%   |
| 6.0.7   | 1        | 0.77%   |
| 6.0.16  | 1        | 0.77%   |
| 6.0.13  | 1        | 0.77%   |
| 6.0.11  | 1        | 0.77%   |
| 5.9.13  | 1        | 0.77%   |
| 5.9.0   | 1        | 0.77%   |
| 5.8.12  | 1        | 0.77%   |
| 5.6.3   | 1        | 0.77%   |
| 5.4.83  | 1        | 0.77%   |
| 5.4.53  | 1        | 0.77%   |
| 5.4.18  | 1        | 0.77%   |
| 5.2.9   | 1        | 0.77%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 22       | 17.05%  |
| 5.15    | 11       | 8.53%   |
| 4.9     | 11       | 8.53%   |
| 4.15    | 10       | 7.75%   |
| 5.11    | 7        | 5.43%   |
| 5.10    | 7        | 5.43%   |
| 6.1     | 6        | 4.65%   |
| 5.13    | 6        | 4.65%   |
| 5.19    | 5        | 3.88%   |
| 6.2     | 4        | 3.1%    |
| 6.0     | 4        | 3.1%    |
| 5.8     | 4        | 3.1%    |
| 5.3     | 4        | 3.1%    |
| 6.6     | 3        | 2.33%   |
| 6.5     | 3        | 2.33%   |
| 5.16    | 3        | 2.33%   |
| 6.4     | 2        | 1.55%   |
| 5.9     | 2        | 1.55%   |
| 5.2     | 2        | 1.55%   |
| 5.17    | 2        | 1.55%   |
| 5.12    | 2        | 1.55%   |
| 5.0     | 2        | 1.55%   |
| 6.3     | 1        | 0.78%   |
| 5.6     | 1        | 0.78%   |
| 5.18    | 1        | 0.78%   |
| 5.14    | 1        | 0.78%   |
| 4.8     | 1        | 0.78%   |
| 4.18    | 1        | 0.78%   |
| 4.1     | 1        | 0.78%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 108      | 96.43%  |
| i686   | 4        | 3.57%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 37       | 30.33%  |
| KDE5       | 29       | 23.77%  |
| X-Cinnamon | 12       | 9.84%   |
| Unknown    | 11       | 9.02%   |
| KDE4       | 10       | 8.2%    |
| XFCE       | 8        | 6.56%   |
| MATE       | 5        | 4.1%    |
| KDE        | 5        | 4.1%    |
| Deepin     | 2        | 1.64%   |
| Cinnamon   | 2        | 1.64%   |
| LXQt       | 1        | 0.82%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 89       | 78.76%  |
| Wayland | 19       | 16.81%  |
| Unknown | 3        | 2.65%   |
| Tty     | 2        | 1.77%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 58       | 47.54%  |
| SDDM    | 25       | 20.49%  |
| KDM     | 10       | 8.2%    |
| LightDM | 9        | 7.38%   |
| GDM     | 9        | 7.38%   |
| GDM3    | 7        | 5.74%   |
| TDM     | 4        | 3.28%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| en_US       | 46       | 38.02%  |
| Unknown     | 22       | 18.18%  |
| ru_RU       | 19       | 15.7%   |
| lv_LV       | 17       | 14.05%  |
| en_GB       | 8        | 6.61%   |
| C           | 4        | 3.31%   |
| ru_RU.UTF_8 | 1        | 0.83%   |
| osa_US      | 1        | 0.83%   |
| en_AG       | 1        | 0.83%   |
| de_DE       | 1        | 0.83%   |
| cv_RU       | 1        | 0.83%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 74       | 66.07%  |
| EFI  | 38       | 33.93%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 78       | 65.55%  |
| Btrfs   | 14       | 11.76%  |
| Unknown | 12       | 10.08%  |
| Overlay | 9        | 7.56%   |
| Tmpfs   | 3        | 2.52%   |
| Xfs     | 1        | 0.84%   |
| Ext3    | 1        | 0.84%   |
| Aufs    | 1        | 0.84%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 62       | 52.1%   |
| GPT     | 31       | 26.05%  |
| MBR     | 26       | 21.85%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 96       | 81.36%  |
| Yes       | 22       | 18.64%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 84       | 70.59%  |
| Yes       | 35       | 29.41%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 30       | 26.79%  |
| Gigabyte Technology                  | 21       | 18.75%  |
| MSI                                  | 16       | 14.29%  |
| ASRock                               | 13       | 11.61%  |
| Hewlett-Packard                      | 7        | 6.25%   |
| Dell                                 | 7        | 6.25%   |
| Intel                                | 4        | 3.57%   |
| Biostar                              | 3        | 2.68%   |
| Acer                                 | 3        | 2.68%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.89%   |
| Lenovo                               | 1        | 0.89%   |
| IBM                                  | 1        | 0.89%   |
| Hardkernel                           | 1        | 0.89%   |
| Fujitsu Siemens                      | 1        | 0.89%   |
| Foxconn                              | 1        | 0.89%   |
| Acidanthera                          | 1        | 0.89%   |
| ABIT                                 | 1        | 0.89%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS All Series                            | 6        | 5.36%   |
| MSI MS-7721                                | 2        | 1.79%   |
| Gigabyte G33M-S2                           | 2        | 1.79%   |
| Gigabyte B550 AORUS PRO V2                 | 2        | 1.79%   |
| Gigabyte 946GMX-S2                         | 2        | 1.79%   |
| Dell OptiPlex 7020                         | 2        | 1.79%   |
| ASUS TUF Gaming X570-PLUS                  | 2        | 1.79%   |
| Shenzhen Meigao Electronic Equipment UM450 | 1        | 0.89%   |
| MSI MS-7C52                                | 1        | 0.89%   |
| MSI MS-7B98                                | 1        | 0.89%   |
| MSI MS-7B46                                | 1        | 0.89%   |
| MSI MS-7B33                                | 1        | 0.89%   |
| MSI MS-7A38                                | 1        | 0.89%   |
| MSI MS-7A33                                | 1        | 0.89%   |
| MSI MS-7996                                | 1        | 0.89%   |
| MSI MS-7850                                | 1        | 0.89%   |
| MSI MS-7846                                | 1        | 0.89%   |
| MSI MS-7758                                | 1        | 0.89%   |
| MSI MS-7693                                | 1        | 0.89%   |
| MSI MS-7680                                | 1        | 0.89%   |
| MSI MS-7583                                | 1        | 0.89%   |
| MSI MS-7519                                | 1        | 0.89%   |
| Lenovo Legion T5 26AMR5 90RC018LBX         | 1        | 0.89%   |
| Intel DQ87PG AAG74154-403                  | 1        | 0.89%   |
| Intel DH77EB AAG39073-304                  | 1        | 0.89%   |
| Intel DH55HC AAE70933-505                  | 1        | 0.89%   |
| Intel DB85FL AAG89861-201                  | 1        | 0.89%   |
| IBM 8215ZCL                                | 1        | 0.89%   |
| HP xw6600 Workstation                      | 1        | 0.89%   |
| HP ProDesk 600 G1 TWR                      | 1        | 0.89%   |
| HP EliteDesk 800 G2 DM 35W                 | 1        | 0.89%   |
| HP Compaq dc7800 Small Form Factor         | 1        | 0.89%   |
| HP Compaq dc5700 Microtower                | 1        | 0.89%   |
| HP Compaq 8100 Elite CMT PC                | 1        | 0.89%   |
| HP 310-1205uk                              | 1        | 0.89%   |
| Hardkernel ODROID-H2                       | 1        | 0.89%   |
| Gigabyte Z87P-D3                           | 1        | 0.89%   |
| Gigabyte Z87-HD3                           | 1        | 0.89%   |
| Gigabyte Z790 GAMING X AX                  | 1        | 0.89%   |
| Gigabyte X570 AORUS ELITE                  | 1        | 0.89%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Dell OptiPlex                              | 7        | 6.25%   |
| ASUS All                                   | 6        | 5.36%   |
| ASUS PRIME                                 | 5        | 4.46%   |
| ASUS ROG                                   | 4        | 3.57%   |
| HP Compaq                                  | 3        | 2.68%   |
| MSI MS-7721                                | 2        | 1.79%   |
| Gigabyte G33M-S2                           | 2        | 1.79%   |
| Gigabyte B550                              | 2        | 1.79%   |
| Gigabyte 946GMX-S2                         | 2        | 1.79%   |
| ASUS TUF                                   | 2        | 1.79%   |
| ASUS P5Q                                   | 2        | 1.79%   |
| Acer Aspire                                | 2        | 1.79%   |
| Shenzhen Meigao Electronic Equipment UM450 | 1        | 0.89%   |
| MSI MS-7C52                                | 1        | 0.89%   |
| MSI MS-7B98                                | 1        | 0.89%   |
| MSI MS-7B46                                | 1        | 0.89%   |
| MSI MS-7B33                                | 1        | 0.89%   |
| MSI MS-7A38                                | 1        | 0.89%   |
| MSI MS-7A33                                | 1        | 0.89%   |
| MSI MS-7996                                | 1        | 0.89%   |
| MSI MS-7850                                | 1        | 0.89%   |
| MSI MS-7846                                | 1        | 0.89%   |
| MSI MS-7758                                | 1        | 0.89%   |
| MSI MS-7693                                | 1        | 0.89%   |
| MSI MS-7680                                | 1        | 0.89%   |
| MSI MS-7583                                | 1        | 0.89%   |
| MSI MS-7519                                | 1        | 0.89%   |
| Lenovo Legion                              | 1        | 0.89%   |
| Intel DQ87PG                               | 1        | 0.89%   |
| Intel DH77EB                               | 1        | 0.89%   |
| Intel DH55HC                               | 1        | 0.89%   |
| Intel DB85FL                               | 1        | 0.89%   |
| IBM 8215ZCL                                | 1        | 0.89%   |
| HP xw6600                                  | 1        | 0.89%   |
| HP ProDesk                                 | 1        | 0.89%   |
| HP EliteDesk                               | 1        | 0.89%   |
| HP 310-1205uk                              | 1        | 0.89%   |
| Hardkernel ODROID-H2                       | 1        | 0.89%   |
| Gigabyte Z87P-D3                           | 1        | 0.89%   |
| Gigabyte Z87-HD3                           | 1        | 0.89%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 13       | 11.61%  |
| 2007 | 13       | 11.61%  |
| 2012 | 11       | 9.82%   |
| 2008 | 10       | 8.93%   |
| 2019 | 8        | 7.14%   |
| 2018 | 8        | 7.14%   |
| 2009 | 7        | 6.25%   |
| 2017 | 6        | 5.36%   |
| 2015 | 6        | 5.36%   |
| 2011 | 6        | 5.36%   |
| 2014 | 5        | 4.46%   |
| 2022 | 4        | 3.57%   |
| 2006 | 4        | 3.57%   |
| 2010 | 3        | 2.68%   |
| 2023 | 2        | 1.79%   |
| 2021 | 2        | 1.79%   |
| 2020 | 2        | 1.79%   |
| 2016 | 1        | 0.89%   |
| 2004 | 1        | 0.89%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 112      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 110      | 98.21%  |
| Enabled  | 2        | 1.79%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 112      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 24       | 20.69%  |
| 3.01-4.0        | 23       | 19.83%  |
| 16.01-24.0      | 20       | 17.24%  |
| 32.01-64.0      | 18       | 15.52%  |
| 4.01-8.0        | 16       | 13.79%  |
| 1.01-2.0        | 6        | 5.17%   |
| 24.01-32.0      | 3        | 2.59%   |
| 2.01-3.0        | 3        | 2.59%   |
| 64.01-256.0     | 2        | 1.72%   |
| More than 256.0 | 1        | 0.86%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 40       | 31.25%  |
| 2.01-3.0   | 27       | 21.09%  |
| 4.01-8.0   | 21       | 16.41%  |
| 0.51-1.0   | 20       | 15.63%  |
| 3.01-4.0   | 14       | 10.94%  |
| 8.01-16.0  | 5        | 3.91%   |
| 16.01-24.0 | 1        | 0.78%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 52       | 42.98%  |
| 2      | 28       | 23.14%  |
| 3      | 24       | 19.83%  |
| 4      | 10       | 8.26%   |
| 5      | 4        | 3.31%   |
| 6      | 2        | 1.65%   |
| 7      | 1        | 0.83%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 63       | 55.26%  |
| Yes       | 51       | 44.74%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 111      | 99.11%  |
| No        | 1        | 0.89%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 74       | 65.49%  |
| Yes       | 39       | 34.51%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 90       | 79.65%  |
| Yes       | 23       | 20.35%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Latvia  | 112      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City       | Desktops | Percent |
|------------|----------|---------|
| Riga       | 81       | 69.23%  |
| Ventspils  | 5        | 4.27%   |
| Salaspils  | 4        | 3.42%   |
| Jelgava    | 3        | 2.56%   |
| Talsi      | 2        | 1.71%   |
| Ogre       | 2        | 1.71%   |
| Liepāja   | 2        | 1.71%   |
| Jūrmala   | 2        | 1.71%   |
| Daugavpils | 2        | 1.71%   |
| Adazi      | 2        | 1.71%   |
| Roya       | 1        | 0.85%   |
| Ragana     | 1        | 0.85%   |
| Mirnijs    | 1        | 0.85%   |
| Limbaži   | 1        | 0.85%   |
| Lielvārde | 1        | 0.85%   |
| Kuldīga   | 1        | 0.85%   |
| Jēkabpils | 1        | 0.85%   |
| Iecava     | 1        | 0.85%   |
| Dreilini   | 1        | 0.85%   |
| Carnikava  | 1        | 0.85%   |
| Brankas    | 1        | 0.85%   |
| Bauska     | 1        | 0.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| WDC                          | 44       | 70     | 21.26%  |
| Seagate                      | 43       | 65     | 20.77%  |
| Samsung Electronics          | 32       | 61     | 15.46%  |
| Kingston                     | 14       | 24     | 6.76%   |
| Crucial                      | 12       | 21     | 5.8%    |
| Toshiba                      | 6        | 8      | 2.9%    |
| Intel                        | 6        | 11     | 2.9%    |
| Hitachi                      | 6        | 8      | 2.9%    |
| SPCC                         | 3        | 5      | 1.45%   |
| Kingston Technology Company  | 3        | 3      | 1.45%   |
| HGST                         | 3        | 3      | 1.45%   |
| GOODRAM                      | 3        | 8      | 1.45%   |
| A-DATA Technology            | 3        | 4      | 1.45%   |
| Transcend                    | 2        | 2      | 0.97%   |
| Shenzhen Longsys Electronics | 2        | 2      | 0.97%   |
| Phison Electronics           | 2        | 3      | 0.97%   |
| OCZ                          | 2        | 3      | 0.97%   |
| Intenso                      | 2        | 2      | 0.97%   |
| XPG                          | 1        | 1      | 0.48%   |
| Unknown                      | 1        | 1      | 0.48%   |
| Silicon Motion               | 1        | 1      | 0.48%   |
| RSH-338H                     | 1        | 2      | 0.48%   |
| Realtek Semiconductor        | 1        | 1      | 0.48%   |
| Patriot                      | 1        | 1      | 0.48%   |
| Netac                        | 1        | 1      | 0.48%   |
| Mushkin                      | 1        | 2      | 0.48%   |
| Maxtor                       | 1        | 1      | 0.48%   |
| Lite-On Technology           | 1        | 1      | 0.48%   |
| KIOXIA-EXCERIA               | 1        | 1      | 0.48%   |
| KingFast                     | 1        | 2      | 0.48%   |
| JMicron Technology           | 1        | 2      | 0.48%   |
| IBM/Hitachi                  | 1        | 1      | 0.48%   |
| HS-SSD-E100                  | 1        | 1      | 0.48%   |
| Hewlett-Packard              | 1        | 1      | 0.48%   |
| GLOWAY                       | 1        | 2      | 0.48%   |
| CHN25SATAS1                  | 1        | 1      | 0.48%   |
| ADATA Technology             | 1        | 2      | 0.48%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD                   | 6        | 2.5%    |
| Seagate ST1000DM010-2EP102 1TB                    | 5        | 2.08%   |
| Crucial CT500MX500SSD1 500GB                      | 4        | 1.67%   |
| Crucial CT1000MX500SSD1 1TB                       | 4        | 1.67%   |
| WDC WD2000JD-00HBB0 200GB                         | 3        | 1.25%   |
| Seagate ST500DM005 HD502HJ 500GB                  | 3        | 1.25%   |
| Seagate ST3500418AS 500GB                         | 3        | 1.25%   |
| Samsung NVMe SSD Drive 500GB                      | 3        | 1.25%   |
| Kingston SV300S37A240G 240GB SSD                  | 3        | 1.25%   |
| Crucial CT480BX500SSD1 480GB                      | 3        | 1.25%   |
| WDC WD6003FZBX-00K5WB0 6TB                        | 2        | 0.83%   |
| WDC WD5002AALX-00J37A0 500GB                      | 2        | 0.83%   |
| WDC WD5000AAKX-22ERMA0 500GB                      | 2        | 0.83%   |
| WDC WD5000AAKX-00ERMA0 500GB                      | 2        | 0.83%   |
| WDC WD5000AAKX-001CA0 500GB                       | 2        | 0.83%   |
| WDC WD20EARX-00PASB0 2TB                          | 2        | 0.83%   |
| WDC WD10EZEX-00BN5A0 1TB                          | 2        | 0.83%   |
| Toshiba DT01ACA100 1TB                            | 2        | 0.83%   |
| Seagate ST3500413AS 500GB                         | 2        | 0.83%   |
| Seagate ST3320620AS 320GB                         | 2        | 0.83%   |
| Seagate ST3250824AS 250GB                         | 2        | 0.83%   |
| Seagate ST250DM000-1BD141 250GB                   | 2        | 0.83%   |
| Seagate ST2000DM001-1CH164 2TB                    | 2        | 0.83%   |
| Seagate ST1000DX001-1CM162 1TB                    | 2        | 0.83%   |
| Seagate ST1000DM003-1SB102 1TB                    | 2        | 0.83%   |
| Samsung SSD 970 EVO Plus 500GB                    | 2        | 0.83%   |
| Samsung SSD 860 EVO 500GB                         | 2        | 0.83%   |
| Samsung SSD 860 EVO 1TB                           | 2        | 0.83%   |
| Samsung SSD 850 EVO 500GB                         | 2        | 0.83%   |
| Samsung SSD 850 EVO 250GB                         | 2        | 0.83%   |
| Samsung SSD 650 120GB                             | 2        | 0.83%   |
| Samsung SP2504C 250GB                             | 2        | 0.83%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 2        | 0.83%   |
| Samsung HD501LJ 500GB                             | 2        | 0.83%   |
| Samsung HD103UJ 1TB                               | 2        | 0.83%   |
| Phison PS5013 E13 NVMe Controller 256GB           | 2        | 0.83%   |
| Intel SSDSA2CW120G3 120GB                         | 2        | 0.83%   |
| HGST HTS541010A9E680 1TB                          | 2        | 0.83%   |
| GOODRAM SSDPR-CX400-128-G2 128GB                  | 2        | 0.83%   |
| Crucial CT120BX500SSD1 120GB                      | 2        | 0.83%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 43       | 65     | 38.74%  |
| WDC                 | 38       | 58     | 34.23%  |
| Samsung Electronics | 12       | 19     | 10.81%  |
| Toshiba             | 6        | 8      | 5.41%   |
| Hitachi             | 6        | 8      | 5.41%   |
| HGST                | 3        | 3      | 2.7%    |
| Maxtor              | 1        | 1      | 0.9%    |
| JMicron Technology  | 1        | 2      | 0.9%    |
| IBM/Hitachi         | 1        | 1      | 0.9%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 14       | 24     | 19.18%  |
| Kingston            | 14       | 24     | 19.18%  |
| Crucial             | 12       | 21     | 16.44%  |
| WDC                 | 8        | 9      | 10.96%  |
| Intel               | 4        | 9      | 5.48%   |
| SPCC                | 3        | 5      | 4.11%   |
| GOODRAM             | 3        | 8      | 4.11%   |
| A-DATA Technology   | 3        | 4      | 4.11%   |
| Transcend           | 2        | 2      | 2.74%   |
| OCZ                 | 2        | 3      | 2.74%   |
| Intenso             | 2        | 2      | 2.74%   |
| Patriot             | 1        | 1      | 1.37%   |
| Mushkin             | 1        | 2      | 1.37%   |
| KIOXIA-EXCERIA      | 1        | 1      | 1.37%   |
| KingFast            | 1        | 2      | 1.37%   |
| GLOWAY              | 1        | 2      | 1.37%   |
| CHN25SATAS1         | 1        | 1      | 1.37%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 82       | 165    | 48.52%  |
| SSD     | 57       | 120    | 33.73%  |
| NVMe    | 27       | 39     | 15.98%  |
| Unknown | 2        | 3      | 1.18%   |
| MMC     | 1        | 1      | 0.59%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 104      | 281    | 76.47%  |
| NVMe | 27       | 39     | 19.85%  |
| SAS  | 4        | 7      | 2.94%   |
| MMC  | 1        | 1      | 0.74%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 86       | 181    | 59.31%  |
| 0.51-1.0   | 40       | 71     | 27.59%  |
| 1.01-2.0   | 11       | 23     | 7.59%   |
| 2.01-3.0   | 3        | 5      | 2.07%   |
| 4.01-10.0  | 3        | 3      | 2.07%   |
| 3.01-4.0   | 2        | 2      | 1.38%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 36       | 29.27%  |
| 251-500        | 16       | 13.01%  |
| 1001-2000      | 15       | 12.2%   |
| 501-1000       | 12       | 9.76%   |
| 51-100         | 12       | 9.76%   |
| More than 3000 | 10       | 8.13%   |
| 21-50          | 7        | 5.69%   |
| 2001-3000      | 7        | 5.69%   |
| 1-20           | 7        | 5.69%   |
| Unknown        | 1        | 0.81%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 49       | 37.12%  |
| 101-250        | 17       | 12.88%  |
| 21-50          | 16       | 12.12%  |
| 251-500        | 14       | 10.61%  |
| 51-100         | 13       | 9.85%   |
| 501-1000       | 11       | 8.33%   |
| 1001-2000      | 7        | 5.3%    |
| 2001-3000      | 3        | 2.27%   |
| More than 3000 | 1        | 0.76%   |
| Unknown        | 1        | 0.76%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD20EARX-00PASB0 2TB              | 2        | 4      | 5.71%   |
| WDC WD2000JD-00HBB0 200GB             | 2        | 4      | 5.71%   |
| Seagate ST1000DM003-1SB102 1TB        | 2        | 7      | 5.71%   |
| Samsung Electronics SP2504C 250GB     | 2        | 2      | 5.71%   |
| Samsung Electronics HD501LJ 500GB     | 2        | 7      | 5.71%   |
| WDC WDS500G3X0C-00SJG0 500GB          | 1        | 1      | 2.86%   |
| WDC WD800JD-60MSA1 80GB               | 1        | 1      | 2.86%   |
| WDC WD5002AALX-00J37A0 500GB          | 1        | 1      | 2.86%   |
| WDC WD5001AALS-00L3B2 500GB           | 1        | 1      | 2.86%   |
| WDC WD5001AALS-00E3A0 500GB           | 1        | 1      | 2.86%   |
| WDC WD5000LPVX-00V0TT0 500GB          | 1        | 1      | 2.86%   |
| WDC WD2500AAKS-60L9A0 250GB           | 1        | 1      | 2.86%   |
| WDC WD1600AAJS-00B4A0 160GB           | 1        | 1      | 2.86%   |
| WDC WD Green 2.5 1000GB SSD           | 1        | 1      | 2.86%   |
| Toshiba DT01ACA100 1TB                | 1        | 1      | 2.86%   |
| Seagate ST3500820AS 500GB             | 1        | 1      | 2.86%   |
| Seagate ST3500413AS 500GB             | 1        | 1      | 2.86%   |
| Seagate ST3500312CS 500GB             | 1        | 1      | 2.86%   |
| Seagate ST340016A 40GB                | 1        | 1      | 2.86%   |
| Seagate ST3250620AS 250GB             | 1        | 1      | 2.86%   |
| Seagate ST3250312AS 250GB             | 1        | 1      | 2.86%   |
| Seagate ST31000528AS 1TB              | 1        | 1      | 2.86%   |
| Seagate ST3000DM001-9YN166 3TB        | 1        | 1      | 2.86%   |
| Seagate ST2000LM007-1R8174 2TB        | 1        | 1      | 2.86%   |
| Seagate ST1000DX001-1CM162 1TB        | 1        | 1      | 2.86%   |
| Samsung Electronics SSD 970 EVO 500GB | 1        | 1      | 2.86%   |
| Kingston SV300S37A60G 64GB SSD        | 1        | 1      | 2.86%   |
| Hitachi HTS542525K9A300 250GB         | 1        | 1      | 2.86%   |
| CHN25SATAS1 SSD 128 128GB             | 1        | 1      | 2.86%   |
| A-DATA Technology SU800NS38 512GB SSD | 1        | 2      | 2.86%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 11       | 17     | 34.38%  |
| Seagate             | 11       | 17     | 34.38%  |
| Samsung Electronics | 5        | 10     | 15.63%  |
| Toshiba             | 1        | 1      | 3.13%   |
| Kingston            | 1        | 1      | 3.13%   |
| Hitachi             | 1        | 1      | 3.13%   |
| CHN25SATAS1         | 1        | 1      | 3.13%   |
| A-DATA Technology   | 1        | 2      | 3.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 11       | 17     | 40.74%  |
| WDC                 | 10       | 15     | 37.04%  |
| Samsung Electronics | 4        | 9      | 14.81%  |
| Toshiba             | 1        | 1      | 3.7%    |
| Hitachi             | 1        | 1      | 3.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 19       | 43     | 76%     |
| SSD  | 4        | 5      | 16%     |
| NVMe | 2        | 2      | 8%      |

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
| Detected | 65       | 157    | 48.51%  |
| Works    | 46       | 121    | 34.33%  |
| Malfunc  | 23       | 50     | 17.16%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 72       | 46.45%  |
| AMD                              | 35       | 22.58%  |
| Samsung Electronics              | 12       | 7.74%   |
| JMicron Technology               | 7        | 4.52%   |
| Nvidia                           | 5        | 3.23%   |
| Marvell Technology Group         | 5        | 3.23%   |
| Kingston Technology Company      | 3        | 1.94%   |
| ASMedia Technology               | 3        | 1.94%   |
| Shenzhen Longsys Electronics     | 2        | 1.29%   |
| SanDisk                          | 2        | 1.29%   |
| Phison Electronics               | 2        | 1.29%   |
| ADATA Technology                 | 2        | 1.29%   |
| Silicon Motion                   | 1        | 0.65%   |
| Silicon Integrated Systems [SiS] | 1        | 0.65%   |
| Realtek Semiconductor            | 1        | 0.65%   |
| MAXIO Technology (Hangzhou)      | 1        | 0.65%   |
| Lite-On Technology               | 1        | 0.65%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 19       | 9.27%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 12       | 5.85%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 10       | 4.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 9        | 4.39%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 7        | 3.41%   |
| AMD 500 Series Chipset SATA Controller                                                  | 6        | 2.93%   |
| JMicron JMB368 IDE controller                                                           | 5        | 2.44%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5        | 2.44%   |
| Nvidia MCP61 SATA Controller                                                            | 4        | 1.95%   |
| Nvidia MCP61 IDE                                                                        | 4        | 1.95%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 4        | 1.95%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 4        | 1.95%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4        | 1.95%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4        | 1.95%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4        | 1.95%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4        | 1.95%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4        | 1.95%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3        | 1.46%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3        | 1.46%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3        | 1.46%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 3        | 1.46%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 3        | 1.46%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 3        | 1.46%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 3        | 1.46%   |
| AMD FCH IDE Controller                                                                  | 3        | 1.46%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 1.46%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 2        | 0.98%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                               | 2        | 0.98%   |
| Kingston Company NV2 NVMe SSD SM2267XT (DRAM-less)                                      | 2        | 0.98%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2        | 0.98%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2        | 0.98%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 2        | 0.98%   |
| Intel 82801IB (ICH9) 4 port SATA Controller [AHCI mode]                                 | 2        | 0.98%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 2        | 0.98%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 2        | 0.98%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 0.98%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 0.98%   |
| AMD X370 Series Chipset SATA Controller                                                 | 2        | 0.98%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 0.98%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 1        | 0.49%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 79       | 52.32%  |
| IDE  | 43       | 28.48%  |
| NVMe | 27       | 17.88%  |
| RAID | 2        | 1.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 72       | 64.29%  |
| AMD    | 40       | 35.71%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Intel Core i5-4570 CPU @ 3.20GHz              | 4        | 3.57%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 3        | 2.68%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 3        | 2.68%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 3        | 2.68%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 3        | 2.68%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 3        | 2.68%   |
| AMD Ryzen 5 3600 6-Core Processor             | 3        | 2.68%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz        | 2        | 1.79%   |
| Intel Pentium D CPU 3.40GHz                   | 2        | 1.79%   |
| Intel Pentium D CPU 2.80GHz                   | 2        | 1.79%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 2        | 1.79%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 2        | 1.79%   |
| Intel Core i5 CPU 650 @ 3.20GHz               | 2        | 1.79%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz         | 2        | 1.79%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz          | 2        | 1.79%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz          | 2        | 1.79%   |
| Intel Core 2 CPU 6300 @ 1.86GHz               | 2        | 1.79%   |
| AMD Ryzen 7 1700 Eight-Core Processor         | 2        | 1.79%   |
| AMD A8-7600 Radeon R7, 10 Compute Cores 4C+6G | 2        | 1.79%   |
| AMD A8-6600K APU with Radeon HD Graphics      | 2        | 1.79%   |
| Intel Xeon CPU E5420 @ 2.50GHz                | 1        | 0.89%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz   | 1        | 0.89%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 1        | 0.89%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz   | 1        | 0.89%   |
| Intel Pentium Dual CPU E2220 @ 2.40GHz        | 1        | 0.89%   |
| Intel Pentium D CPU 3.00GHz                   | 1        | 0.89%   |
| Intel Pentium CPU G620 @ 2.60GHz              | 1        | 0.89%   |
| Intel Pentium 4 CPU 2.66GHz                   | 1        | 0.89%   |
| Intel Core i7-9700K CPU @ 3.60GHz             | 1        | 0.89%   |
| Intel Core i7-8700T CPU @ 2.40GHz             | 1        | 0.89%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 1        | 0.89%   |
| Intel Core i7-4770K CPU @ 3.50GHz             | 1        | 0.89%   |
| Intel Core i7-4765T CPU @ 2.00GHz             | 1        | 0.89%   |
| Intel Core i7-3930K CPU @ 3.20GHz             | 1        | 0.89%   |
| Intel Core i7-2700K CPU @ 3.50GHz             | 1        | 0.89%   |
| Intel Core i7 CPU 860 @ 2.80GHz               | 1        | 0.89%   |
| Intel Core i5-9600K CPU @ 3.70GHz             | 1        | 0.89%   |
| Intel Core i5-8600K CPU @ 3.60GHz             | 1        | 0.89%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 1        | 0.89%   |
| Intel Core i5-7600K CPU @ 3.80GHz             | 1        | 0.89%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 18       | 16.07%  |
| Intel Core i7           | 12       | 10.71%  |
| AMD Ryzen 5             | 12       | 10.71%  |
| Intel Core i3           | 11       | 9.82%   |
| Intel Core 2 Duo        | 7        | 6.25%   |
| Intel Pentium D         | 5        | 4.46%   |
| Intel Core 2 Quad       | 5        | 4.46%   |
| AMD A8                  | 5        | 4.46%   |
| AMD Ryzen 9             | 4        | 3.57%   |
| AMD Ryzen 7             | 4        | 3.57%   |
| AMD FX                  | 4        | 3.57%   |
| Intel Pentium Dual-Core | 3        | 2.68%   |
| Intel Pentium Dual      | 3        | 2.68%   |
| AMD Athlon 64 X2        | 3        | 2.68%   |
| Other                   | 2        | 1.79%   |
| Intel Core 2            | 2        | 1.79%   |
| AMD Ryzen Threadripper  | 2        | 1.79%   |
| AMD Athlon II X2        | 2        | 1.79%   |
| Intel Xeon              | 1        | 0.89%   |
| Intel Pentium 4         | 1        | 0.89%   |
| Intel Pentium           | 1        | 0.89%   |
| Intel Celeron           | 1        | 0.89%   |
| AMD Sempron             | 1        | 0.89%   |
| AMD Ryzen 5 PRO         | 1        | 0.89%   |
| AMD Athlon II X3        | 1        | 0.89%   |
| AMD Athlon              | 1        | 0.89%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 41       | 36.28%  |
| 4       | 31       | 27.43%  |
| 6       | 18       | 15.93%  |
| 8       | 6        | 5.31%   |
| 3       | 5        | 4.42%   |
| 16      | 3        | 2.65%   |
| 12      | 3        | 2.65%   |
| 1       | 3        | 2.65%   |
| 24      | 1        | 0.88%   |
| 10      | 1        | 0.88%   |
| Unknown | 1        | 0.88%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 111      | 99.11%  |
| 2      | 1        | 0.89%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 57       | 50.44%  |
| 2       | 55       | 48.67%  |
| Unknown | 1        | 0.88%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 111      | 99.11%  |
| Unknown        | 1        | 0.89%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 24       | 21.24%  |
| 0x306c3    | 12       | 10.62%  |
| 0x1067a    | 8        | 7.08%   |
| 0x206a7    | 5        | 4.42%   |
| 0x08701021 | 5        | 4.42%   |
| 0x906ea    | 4        | 3.54%   |
| 0x10676    | 4        | 3.54%   |
| 0x6fd      | 3        | 2.65%   |
| 0x6fb      | 3        | 2.65%   |
| 0x06001119 | 3        | 2.65%   |
| 0x06000852 | 3        | 2.65%   |
| 0xf65      | 2        | 1.77%   |
| 0xf47      | 2        | 1.77%   |
| 0x6f2      | 2        | 1.77%   |
| 0x506e3    | 2        | 1.77%   |
| 0x306a9    | 2        | 1.77%   |
| 0x0a50000d | 2        | 1.77%   |
| 0x0a201009 | 2        | 1.77%   |
| 0x08001137 | 2        | 1.77%   |
| 0x06003106 | 2        | 1.77%   |
| 0x010000c8 | 2        | 1.77%   |
| 0xf64      | 1        | 0.88%   |
| 0xf41      | 1        | 0.88%   |
| 0xb0671    | 1        | 0.88%   |
| 0x906ed    | 1        | 0.88%   |
| 0x906ec    | 1        | 0.88%   |
| 0x906e9    | 1        | 0.88%   |
| 0x706a1    | 1        | 0.88%   |
| 0x206d6    | 1        | 0.88%   |
| 0x20655    | 1        | 0.88%   |
| 0x20652    | 1        | 0.88%   |
| 0x106e5    | 1        | 0.88%   |
| 0x0a601206 | 1        | 0.88%   |
| 0x0a20120a | 1        | 0.88%   |
| 0x0a201016 | 1        | 0.88%   |
| 0x0800820d | 1        | 0.88%   |
| 0x08001138 | 1        | 0.88%   |
| 0x08001126 | 1        | 0.88%   |
| 0x0700010f | 1        | 0.88%   |
| 0x0600063e | 1        | 0.88%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 15       | 13.39%  |
| Penryn           | 13       | 11.61%  |
| Zen 2            | 9        | 8.04%   |
| KabyLake         | 9        | 8.04%   |
| Zen 3            | 8        | 7.14%   |
| SandyBridge      | 8        | 7.14%   |
| Core             | 8        | 7.14%   |
| Piledriver       | 6        | 5.36%   |
| NetBurst         | 6        | 5.36%   |
| Zen              | 4        | 3.57%   |
| K8 Hammer        | 4        | 3.57%   |
| Skylake          | 3        | 2.68%   |
| K10              | 3        | 2.68%   |
| IvyBridge        | 3        | 2.68%   |
| Westmere         | 2        | 1.79%   |
| Steamroller      | 2        | 1.79%   |
| Nehalem          | 2        | 1.79%   |
| Alderlake Hybrid | 2        | 1.79%   |
| Zen+             | 1        | 0.89%   |
| Jaguar           | 1        | 0.89%   |
| Goldmont plus    | 1        | 0.89%   |
| Bulldozer        | 1        | 0.89%   |
| Unknown          | 1        | 0.89%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 53       | 43.44%  |
| AMD    | 40       | 32.79%  |
| Intel  | 29       | 23.77%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5        | 3.97%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 4        | 3.17%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 3        | 2.38%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 2.38%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 3        | 2.38%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3        | 2.38%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 2        | 1.59%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 1.59%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 2        | 1.59%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 1.59%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 1.59%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 1.59%   |
| Nvidia GF106 [GeForce GTS 450]                                              | 2        | 1.59%   |
| Nvidia G84 [GeForce 8600 GT]                                                | 2        | 1.59%   |
| Nvidia G72 [GeForce 7300 GS]                                                | 2        | 1.59%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 1.59%   |
| Intel HD Graphics 530                                                       | 2        | 1.59%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 2        | 1.59%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 2        | 1.59%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.59%   |
| AMD Richland [Radeon HD 8570D]                                              | 2        | 1.59%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 2        | 1.59%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 2        | 1.59%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 2        | 1.59%   |
| AMD Bonaire XTX [Radeon R7 260X/360]                                        | 2        | 1.59%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.79%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 0.79%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 0.79%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 1        | 0.79%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 1        | 0.79%   |
| Nvidia NV44 [GeForce 6200 SE TurboCache]                                    | 1        | 0.79%   |
| Nvidia GT216 [GeForce GT 220]                                               | 1        | 0.79%   |
| Nvidia GT200 [GeForce GTX 260]                                              | 1        | 0.79%   |
| Nvidia GP106 [GeForce GTX 1060 6GB Rev. 2]                                  | 1        | 0.79%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 0.79%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 0.79%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 0.79%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 0.79%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 0.79%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 1        | 0.79%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 48       | 42.11%  |
| 1 x AMD        | 34       | 29.82%  |
| 1 x Intel      | 23       | 20.18%  |
| 2 x AMD        | 3        | 2.63%   |
| Intel + Nvidia | 3        | 2.63%   |
| 2 x Nvidia     | 1        | 0.88%   |
| Intel + AMD    | 1        | 0.88%   |
| AMD + Nvidia   | 1        | 0.88%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 79       | 69.3%   |
| Proprietary | 30       | 26.32%  |
| Unknown     | 5        | 4.39%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 36       | 31.58%  |
| 0.01-0.5   | 22       | 19.3%   |
| 0.51-1.0   | 16       | 14.04%  |
| 1.01-2.0   | 10       | 8.77%   |
| 3.01-4.0   | 9        | 7.89%   |
| 7.01-8.0   | 8        | 7.02%   |
| 5.01-6.0   | 8        | 7.02%   |
| 8.01-16.0  | 3        | 2.63%   |
| 2.01-3.0   | 1        | 0.88%   |
| 16.01-24.0 | 1        | 0.88%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 20       | 17.54%  |
| Goldstar             | 20       | 17.54%  |
| Philips              | 9        | 7.89%   |
| Dell                 | 9        | 7.89%   |
| BenQ                 | 9        | 7.89%   |
| AOC                  | 8        | 7.02%   |
| Hewlett-Packard      | 7        | 6.14%   |
| Ancor Communications | 7        | 6.14%   |
| Lenovo               | 4        | 3.51%   |
| Unknown              | 3        | 2.63%   |
| LG Electronics       | 3        | 2.63%   |
| ViewSonic            | 2        | 1.75%   |
| NEC Computers        | 2        | 1.75%   |
| Arnos Instruments    | 2        | 1.75%   |
| Wacom                | 1        | 0.88%   |
| Plain Tree Systems   | 1        | 0.88%   |
| IBM                  | 1        | 0.88%   |
| HYO                  | 1        | 0.88%   |
| FUS                  | 1        | 0.88%   |
| AUS                  | 1        | 0.88%   |
| ASUSTek Computer     | 1        | 0.88%   |
| Acer                 | 1        | 0.88%   |
| Unknown              | 1        | 0.88%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar L194WT GSM4B06 1440x900 408x255mm 18.9-inch                  | 3        | 2.48%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch              | 2        | 1.65%   |
| LG Electronics LCD Monitor LG TV 1920x1080                            | 2        | 1.65%   |
| Lenovo P24q-10 LEN61A5 2560x1440 527x296mm 23.8-inch                  | 2        | 1.65%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 2        | 1.65%   |
| BenQ ZOWIE XL LCD BNQ7F31 1920x1080 531x298mm 24.0-inch               | 2        | 1.65%   |
| AOC U2879G6 AOC2879 3840x2160 621x341mm 27.9-inch                     | 2        | 1.65%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch | 2        | 1.65%   |
| Wacom CintiqPro24P WAC1063 3840x2160 522x293mm 23.6-inch              | 1        | 0.83%   |
| ViewSonic VA703-3Series VSC631E 1280x1024 338x270mm 17.0-inch         | 1        | 0.83%   |
| ViewSonic VA503 SERIES VSCEF1D 1024x768 304x228mm 15.0-inch           | 1        | 0.83%   |
| Unknown LCD Monitor Sharp LL-S201A 1920x1080                          | 1        | 0.83%   |
| Unknown LCD Monitor HYO DUAL-DVI 2560x1440                            | 1        | 0.83%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1        | 0.83%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch  | 1        | 0.83%   |
| Samsung Electronics SyncMaster SAM036C 1920x1200 550x340mm 25.5-inch  | 1        | 0.83%   |
| Samsung Electronics SyncMaster SAM02F6 1280x1024 340x270mm 17.1-inch  | 1        | 0.83%   |
| Samsung Electronics SyncMaster SAM0273 1440x900 410x257mm 19.1-inch   | 1        | 0.83%   |
| Samsung Electronics SyncMaster SAM026E 1280x1024 376x301mm 19.0-inch  | 1        | 0.83%   |
| Samsung Electronics SyncMaster SAM0259 1280x1024 376x301mm 19.0-inch  | 1        | 0.83%   |
| Samsung Electronics SyncMaster SAM0217 1280x1024 376x301mm 19.0-inch  | 1        | 0.83%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 380x300mm 19.1-inch  | 1        | 0.83%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch  | 1        | 0.83%   |
| Samsung Electronics SyncMaster SAM006B 1280x1024 338x270mm 17.0-inch  | 1        | 0.83%   |
| Samsung Electronics SA300/SA350 SAM0793 1920x1080 531x299mm 24.0-inch | 1        | 0.83%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1        | 0.83%   |
| Samsung Electronics S24E391 SAM0C12 1920x1080 521x293mm 23.5-inch     | 1        | 0.83%   |
| Samsung Electronics S24E390 SAM0C1A 1920x1080 521x293mm 23.5-inch     | 1        | 0.83%   |
| Samsung Electronics S23B350 SAM08D5 1920x1080 510x287mm 23.0-inch     | 1        | 0.83%   |
| Samsung Electronics LS24AG32x SAM71DA 1920x1080 527x296mm 23.8-inch   | 1        | 0.83%   |
| Samsung Electronics LF24T450F SAM7094 1920x1080 527x296mm 23.8-inch   | 1        | 0.83%   |
| Samsung Electronics LCD Monitor SyncMaster                            | 1        | 0.83%   |
| Samsung Electronics LCD Monitor SAM03D4 1280x720                      | 1        | 0.83%   |
| Samsung Electronics LCD Monitor S24D330 1920x1080                     | 1        | 0.83%   |
| Plain Tree Systems 782 PTS1017 1280x1024 337x270mm 17.0-inch          | 1        | 0.83%   |
| Philips PHL 246V5 PHLC0C5 1920x1080 531x299mm 24.0-inch               | 1        | 0.83%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 1        | 0.83%   |
| Philips 227E4Q PHLC0A9 1920x1080 477x268mm 21.5-inch                  | 1        | 0.83%   |
| Philips 220VW PHL0853 1680x1050 474x296mm 22.0-inch                   | 1        | 0.83%   |
| Philips 220S4L PHL08BE 1680x1050 474x296mm 22.0-inch                  | 1        | 0.83%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 37       | 33.04%  |
| 1280x1024 (SXGA)   | 14       | 12.5%   |
| 3840x2160 (4K)     | 11       | 9.82%   |
| 2560x1440 (QHD)    | 10       | 8.93%   |
| 1680x1050 (WSXGA+) | 9        | 8.04%   |
| 1440x900 (WXGA+)   | 7        | 6.25%   |
| 2560x1080          | 5        | 4.46%   |
| Unknown            | 4        | 3.57%   |
| 1600x900 (HD+)     | 3        | 2.68%   |
| 4480x1440          | 2        | 1.79%   |
| 1920x1200 (WUXGA)  | 2        | 1.79%   |
| 1024x768 (XGA)     | 2        | 1.79%   |
| 3840x1080          | 1        | 0.89%   |
| 3520x1200          | 1        | 0.89%   |
| 2960x1050          | 1        | 0.89%   |
| 2288x1287          | 1        | 0.89%   |
| 1360x768           | 1        | 0.89%   |
| 1280x960           | 1        | 0.89%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 17       | 15.32%  |
| Unknown | 16       | 14.41%  |
| 27      | 12       | 10.81%  |
| 23      | 11       | 9.91%   |
| 19      | 10       | 9.01%   |
| 17      | 8        | 7.21%   |
| 22      | 6        | 5.41%   |
| 34      | 5        | 4.5%    |
| 21      | 5        | 4.5%    |
| 20      | 5        | 4.5%    |
| 25      | 4        | 3.6%    |
| 18      | 3        | 2.7%    |
| 40      | 2        | 1.8%    |
| 31      | 2        | 1.8%    |
| 15      | 2        | 1.8%    |
| 142     | 1        | 0.9%    |
| 33      | 1        | 0.9%    |
| 26      | 1        | 0.9%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 40       | 37.38%  |
| 401-500        | 21       | 19.63%  |
| Unknown        | 16       | 14.95%  |
| 301-350        | 10       | 9.35%   |
| 351-400        | 7        | 6.54%   |
| 701-800        | 6        | 5.61%   |
| 601-700        | 4        | 3.74%   |
| 801-900        | 2        | 1.87%   |
| More than 2000 | 1        | 0.93%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 47       | 45.19%  |
| 16/10   | 19       | 18.27%  |
| 5/4     | 15       | 14.42%  |
| Unknown | 15       | 14.42%  |
| 21/9    | 5        | 4.81%   |
| 4/3     | 2        | 1.92%   |
| 1.00    | 1        | 0.96%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 35       | 32.11%  |
| 151-200        | 18       | 16.51%  |
| Unknown        | 16       | 14.68%  |
| 301-350        | 12       | 11.01%  |
| 351-500        | 8        | 7.34%   |
| 141-150        | 8        | 7.34%   |
| 251-300        | 7        | 6.42%   |
| 101-110        | 2        | 1.83%   |
| 501-1000       | 2        | 1.83%   |
| More than 1000 | 1        | 0.92%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 70       | 66.67%  |
| Unknown | 16       | 15.24%  |
| 101-120 | 11       | 10.48%  |
| 121-160 | 6        | 5.71%   |
| 1-50    | 1        | 0.95%   |
| 161-240 | 1        | 0.95%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 100      | 87.72%  |
| 2     | 9        | 7.89%   |
| 0     | 3        | 2.63%   |
| 3     | 2        | 1.75%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 61       | 39.87%  |
| Intel                             | 36       | 23.53%  |
| Qualcomm Atheros                  | 8        | 5.23%   |
| TP-Link                           | 7        | 4.58%   |
| Broadcom                          | 7        | 4.58%   |
| Ralink Technology                 | 4        | 2.61%   |
| Ralink                            | 4        | 2.61%   |
| Nvidia                            | 4        | 2.61%   |
| Xiaomi                            | 2        | 1.31%   |
| Samsung Electronics               | 2        | 1.31%   |
| Qualcomm Atheros Communications   | 2        | 1.31%   |
| MediaTek                          | 2        | 1.31%   |
| Marvell Technology Group          | 2        | 1.31%   |
| Broadcom Limited                  | 2        | 1.31%   |
| ASIX Electronics                  | 2        | 1.31%   |
| Wilocity                          | 1        | 0.65%   |
| vivo                              | 1        | 0.65%   |
| U-Blox                            | 1        | 0.65%   |
| Sundance Technology Inc / IC Plus | 1        | 0.65%   |
| Silicon Integrated Systems [SiS]  | 1        | 0.65%   |
| Huawei Technologies               | 1        | 0.65%   |
| Aquantia                          | 1        | 0.65%   |
| 3Com                              | 1        | 0.65%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller     | 51       | 30.18%  |
| Realtek RTL8125 2.5GbE Controller                                          | 6        | 3.55%   |
| Intel I211 Gigabit Network Connection                                      | 5        | 2.96%   |
| Intel Ethernet Connection I217-LM                                          | 4        | 2.37%   |
| Intel Ethernet Connection (2) I219-V                                       | 4        | 2.37%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 3        | 1.78%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 3        | 1.78%   |
| Nvidia MCP61 Ethernet                                                      | 3        | 1.78%   |
| Intel Wireless 8260                                                        | 3        | 1.78%   |
| Intel Wi-Fi 6 AX200                                                        | 3        | 1.78%   |
| Intel Ethernet Connection I217-V                                           | 3        | 1.78%   |
| Intel Ethernet Connection (7) I219-V                                       | 3        | 1.78%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                | 2        | 1.18%   |
| TP-Link 802.11ac WLAN Adapter                                              | 2        | 1.18%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 2        | 1.18%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 2        | 1.18%   |
| Ralink RT5370 Wireless Adapter                                             | 2        | 1.18%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                  | 2        | 1.18%   |
| Qualcomm Atheros AR9271 802.11n                                            | 2        | 1.18%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                    | 2        | 1.18%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                    | 2        | 1.18%   |
| Intel Ethernet Controller I225-V                                           | 2        | 1.18%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 2        | 1.18%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express                    | 2        | 1.18%   |
| ASIX AX88772B                                                              | 2        | 1.18%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 1        | 0.59%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                       | 1        | 0.59%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                         | 1        | 0.59%   |
| vivo 1820                                                                  | 1        | 0.59%   |
| U-Blox [u-blox 7]                                                          | 1        | 0.59%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                        | 1        | 0.59%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                               | 1        | 0.59%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                        | 1        | 0.59%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.59%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter              | 1        | 0.59%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                   | 1        | 0.59%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                            | 1        | 0.59%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                 | 1        | 0.59%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                     | 1        | 0.59%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                      | 1        | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 10       | 24.39%  |
| TP-Link                         | 7        | 17.07%  |
| Realtek Semiconductor           | 6        | 14.63%  |
| Ralink Technology               | 4        | 9.76%   |
| Ralink                          | 4        | 9.76%   |
| Qualcomm Atheros Communications | 2        | 4.88%   |
| Qualcomm Atheros                | 2        | 4.88%   |
| MediaTek                        | 2        | 4.88%   |
| Broadcom                        | 2        | 4.88%   |
| Wilocity                        | 1        | 2.44%   |
| Broadcom Limited                | 1        | 2.44%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel Wireless 8260                                                  | 3        | 7.14%   |
| Intel Wi-Fi 6 AX200                                                  | 3        | 7.14%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 2        | 4.76%   |
| TP-Link 802.11ac WLAN Adapter                                        | 2        | 4.76%   |
| Ralink RT5370 Wireless Adapter                                       | 2        | 4.76%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                            | 2        | 4.76%   |
| Qualcomm Atheros AR9271 802.11n                                      | 2        | 4.76%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                              | 2        | 4.76%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                   | 1        | 2.38%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                  | 1        | 2.38%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 1        | 2.38%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                  | 1        | 2.38%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 1        | 2.38%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                      | 1        | 2.38%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                           | 1        | 2.38%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                               | 1        | 2.38%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 1        | 2.38%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 1        | 2.38%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 1        | 2.38%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                    | 1        | 2.38%   |
| Ralink MT7601U Wireless Adapter                                      | 1        | 2.38%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                            | 1        | 2.38%   |
| Ralink RT2561/RT61 rev B 802.11g                                     | 1        | 2.38%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 1        | 2.38%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                     | 1        | 2.38%   |
| Intel Wireless 7265                                                  | 1        | 2.38%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 1        | 2.38%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 1        | 2.38%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 1        | 2.38%   |
| Broadcom Network controller                                          | 1        | 2.38%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 1        | 2.38%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter         | 1        | 2.38%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 58       | 49.15%  |
| Intel                             | 31       | 26.27%  |
| Qualcomm Atheros                  | 6        | 5.08%   |
| Broadcom                          | 5        | 4.24%   |
| Nvidia                            | 4        | 3.39%   |
| Xiaomi                            | 2        | 1.69%   |
| Samsung Electronics               | 2        | 1.69%   |
| Marvell Technology Group          | 2        | 1.69%   |
| ASIX Electronics                  | 2        | 1.69%   |
| vivo                              | 1        | 0.85%   |
| Sundance Technology Inc / IC Plus | 1        | 0.85%   |
| Silicon Integrated Systems [SiS]  | 1        | 0.85%   |
| Broadcom Limited                  | 1        | 0.85%   |
| Aquantia                          | 1        | 0.85%   |
| 3Com                              | 1        | 0.85%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller     | 51       | 40.8%   |
| Realtek RTL8125 2.5GbE Controller                                          | 6        | 4.8%    |
| Intel I211 Gigabit Network Connection                                      | 5        | 4%      |
| Intel Ethernet Connection I217-LM                                          | 4        | 3.2%    |
| Intel Ethernet Connection (2) I219-V                                       | 4        | 3.2%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 3        | 2.4%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 3        | 2.4%    |
| Nvidia MCP61 Ethernet                                                      | 3        | 2.4%    |
| Intel Ethernet Connection I217-V                                           | 3        | 2.4%    |
| Intel Ethernet Connection (7) I219-V                                       | 3        | 2.4%    |
| Samsung Galaxy series, misc. (tethering mode)                              | 2        | 1.6%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 2        | 1.6%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                    | 2        | 1.6%    |
| Intel Ethernet Controller I225-V                                           | 2        | 1.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 2        | 1.6%    |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express                    | 2        | 1.6%    |
| ASIX AX88772B                                                              | 2        | 1.6%    |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 1        | 0.8%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                       | 1        | 0.8%    |
| vivo 1820                                                                  | 1        | 0.8%    |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.8%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter              | 1        | 0.8%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 1        | 0.8%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                  | 1        | 0.8%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 1        | 0.8%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                   | 1        | 0.8%    |
| Nvidia MCP67 Ethernet                                                      | 1        | 0.8%    |
| Intel Ethernet Connection (2) I219-LM                                      | 1        | 0.8%    |
| Intel 82579V Gigabit Network Connection                                    | 1        | 0.8%    |
| Intel 82578DM Gigabit Network Connection                                   | 1        | 0.8%    |
| Intel 82578DC Gigabit Network Connection                                   | 1        | 0.8%    |
| Intel 82574L Gigabit Network Connection                                    | 1        | 0.8%    |
| Intel 82573E Gigabit Ethernet Controller (Copper)                          | 1        | 0.8%    |
| Intel 82567V-2 Gigabit Network Connection                                  | 1        | 0.8%    |
| Intel 82567LF-3 Gigabit Network Connection                                 | 1        | 0.8%    |
| Intel 82566DM-2 Gigabit Network Connection                                 | 1        | 0.8%    |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller              | 1        | 0.8%    |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                    | 1        | 0.8%    |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                    | 1        | 0.8%    |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                            | 1        | 0.8%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 111      | 73.03%  |
| WiFi     | 39       | 25.66%  |
| Modem    | 2        | 1.32%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 90       | 78.26%  |
| WiFi     | 25       | 21.74%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 78       | 69.64%  |
| 2     | 27       | 24.11%  |
| 3     | 4        | 3.57%   |
| 0     | 3        | 2.68%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 109      | 97.32%  |
| Yes  | 3        | 2.68%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 10       | 43.48%  |
| Cambridge Silicon Radio | 7        | 30.43%  |
| Realtek Semiconductor   | 2        | 8.7%    |
| ASUSTek Computer        | 2        | 8.7%    |
| MediaTek                | 1        | 4.35%   |
| Apple                   | 1        | 4.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7        | 30.43%  |
| Intel Bluetooth wireless interface                  | 4        | 17.39%  |
| Intel AX200 Bluetooth                               | 3        | 13.04%  |
| Realtek Bluetooth Radio                             | 2        | 8.7%    |
| MediaTek Wireless_Device                            | 1        | 4.35%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 4.35%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 4.35%   |
| Intel AX210 Bluetooth                               | 1        | 4.35%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 4.35%   |
| ASUS Bluetooth Device                               | 1        | 4.35%   |
| Apple Bluetooth Host Controller                     | 1        | 4.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 69       | 36.32%  |
| AMD                              | 48       | 25.26%  |
| Nvidia                           | 44       | 23.16%  |
| C-Media Electronics              | 7        | 3.68%   |
| Creative Technology              | 3        | 1.58%   |
| Yamaha                           | 2        | 1.05%   |
| Focusrite-Novation               | 2        | 1.05%   |
| Creative Labs                    | 2        | 1.05%   |
| Texas Instruments                | 1        | 0.53%   |
| Syntek                           | 1        | 0.53%   |
| SteelSeries ApS                  | 1        | 0.53%   |
| Silicon Integrated Systems [SiS] | 1        | 0.53%   |
| RODE Microphones                 | 1        | 0.53%   |
| Realtek Semiconductor            | 1        | 0.53%   |
| Logitech                         | 1        | 0.53%   |
| Kingston Technology              | 1        | 0.53%   |
| JMTek                            | 1        | 0.53%   |
| FIFINE 683 Microphone            | 1        | 0.53%   |
| AudioQuest                       | 1        | 0.53%   |
| ASUSTek Computer                 | 1        | 0.53%   |
| ASRock                           | 1        | 0.53%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 13       | 5.91%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 12       | 5.45%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 8        | 3.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 7        | 3.18%   |
| Nvidia TU116 High Definition Audio Controller                              | 6        | 2.73%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 6        | 2.73%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6        | 2.73%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6        | 2.73%   |
| Intel Cannon Lake PCH cAVS                                                 | 5        | 2.27%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5        | 2.27%   |
| AMD FCH Azalia Controller                                                  | 5        | 2.27%   |
| Nvidia MCP61 High Definition Audio                                         | 4        | 1.82%   |
| Nvidia GP106 High Definition Audio Controller                              | 4        | 1.82%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4        | 1.82%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4        | 1.82%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 4        | 1.82%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4        | 1.82%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 4        | 1.82%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4        | 1.82%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3        | 1.36%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 3        | 1.36%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 1.36%   |
| Intel 200 Series PCH HD Audio                                              | 3        | 1.36%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3        | 1.36%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 3        | 1.36%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3        | 1.36%   |
| Yamaha Steinberg UR22mkII                                                  | 2        | 0.91%   |
| Nvidia TU106 High Definition Audio Controller                              | 2        | 0.91%   |
| Nvidia TU104 HD Audio Controller                                           | 2        | 0.91%   |
| Nvidia High Definition Audio Controller                                    | 2        | 0.91%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 0.91%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2        | 0.91%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2        | 0.91%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2        | 0.91%   |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 0.91%   |
| Nvidia GF106 High Definition Audio Controller                              | 2        | 0.91%   |
| Nvidia GA104 High Definition Audio Controller                              | 2        | 0.91%   |
| Nvidia GA102 High Definition Audio Controller                              | 2        | 0.91%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2        | 0.91%   |
| Intel 82801G (ICH7 Family) AC'97 Audio Controller                          | 2        | 0.91%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 18       | 26.09%  |
| Kingston            | 16       | 23.19%  |
| Crucial             | 11       | 15.94%  |
| Corsair             | 7        | 10.14%  |
| G.Skill             | 6        | 8.7%    |
| SK hynix            | 2        | 2.9%    |
| Micron Technology   | 2        | 2.9%    |
| GOODRAM             | 2        | 2.9%    |
| Team                | 1        | 1.45%   |
| Samsung Electronics | 1        | 1.45%   |
| Ramos Technology    | 1        | 1.45%   |
| A-DATA Technology   | 1        | 1.45%   |
| Unknown             | 1        | 1.45%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                | 2        | 2.35%   |
| Unknown RAM Module 2048MB DIMM SDRAM                    | 2        | 2.35%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                  | 2        | 2.35%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                  | 2        | 2.35%   |
| Kingston RAM KHX3466C16D4/16GX 16GB DIMM DDR4 3466MT/s  | 2        | 2.35%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1923MT/s     | 2        | 2.35%   |
| Kingston RAM KHX1600C10D3/8GX 8GB DIMM DDR3 1600MT/s    | 2        | 2.35%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 1        | 1.18%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                    | 1        | 1.18%   |
| Unknown RAM Module 4096MB DIMM DDR3 667MT/s             | 1        | 1.18%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s            | 1        | 1.18%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                 | 1        | 1.18%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                | 1        | 1.18%   |
| Unknown RAM Module 2048MB DIMM SDRAM 1333MT/s           | 1        | 1.18%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s             | 1        | 1.18%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                  | 1        | 1.18%   |
| Unknown RAM Module 2048MB DIMM 1066MT/s                 | 1        | 1.18%   |
| Unknown RAM Module 2048MB DIMM                          | 1        | 1.18%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                | 1        | 1.18%   |
| Unknown RAM Module 1024MB DIMM SDRAM                    | 1        | 1.18%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s             | 1        | 1.18%   |
| Unknown RAM Module 1024MB DIMM DDR 667MT/s              | 1        | 1.18%   |
| Unknown RAM Module 1024MB DIMM DDR 533MT/s              | 1        | 1.18%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                  | 1        | 1.18%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s     | 1        | 1.18%   |
| SK hynix RAM HYMP564U64CP8-Y5 512MB DIMM DDR 667MT/s    | 1        | 1.18%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s    | 1        | 1.18%   |
| Samsung RAM M3 78T2863QZS-CE6 1GB DIMM DDR2 1639MT/s    | 1        | 1.18%   |
| Ramos RAM RMB2GE484CA5-13HC 2048MB DIMM 533MT/s         | 1        | 1.18%   |
| Micron RAM 8JTF25664AZ-1G6M1 2GB DIMM DDR3 1600MT/s     | 1        | 1.18%   |
| Micron RAM 8HTF12864AY-667E1 1GB DIMM DDR 667MT/s       | 1        | 1.18%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s  | 1        | 1.18%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s | 1        | 1.18%   |
| Kingston RAM KHX2133C11D3/4GX 4GB DIMM DDR3 2134MT/s    | 1        | 1.18%   |
| Kingston RAM KHX1600C9D3/8GX 8192MB DIMM DDR3 2133MT/s  | 1        | 1.18%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s     | 1        | 1.18%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s     | 1        | 1.18%   |
| Kingston RAM KHX1600C10D3/4G 4096MB DIMM DDR3 1600MT/s  | 1        | 1.18%   |
| Kingston RAM KF3600C16D4/8GX 8GB DIMM DDR4 3600MT/s     | 1        | 1.18%   |
| Kingston RAM HX316C10F/4 4GB DIMM DDR3 1600MT/s         | 1        | 1.18%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 20       | 33.9%   |
| DDR4    | 19       | 32.2%   |
| Unknown | 8        | 13.56%  |
| DDR2    | 5        | 8.47%   |
| SDRAM   | 4        | 6.78%   |
| DDR     | 2        | 3.39%   |
| DDR5    | 1        | 1.69%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 57       | 98.28%  |
| SODIMM | 1        | 1.72%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 18       | 25%     |
| 4096  | 17       | 23.61%  |
| 2048  | 17       | 23.61%  |
| 1024  | 8        | 11.11%  |
| 16384 | 7        | 9.72%   |
| 32768 | 4        | 5.56%   |
| 512   | 1        | 1.39%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 10       | 13.33%  |
| 1333    | 9        | 12%     |
| 667     | 9        | 12%     |
| 3200    | 6        | 8%      |
| 2133    | 6        | 8%      |
| 800     | 4        | 5.33%   |
| 3600    | 3        | 4%      |
| Unknown | 3        | 4%      |
| 3466    | 2        | 2.67%   |
| 3000    | 2        | 2.67%   |
| 2667    | 2        | 2.67%   |
| 2400    | 2        | 2.67%   |
| 1867    | 2        | 2.67%   |
| 1800    | 2        | 2.67%   |
| 1066    | 2        | 2.67%   |
| 533     | 2        | 2.67%   |
| 5200    | 1        | 1.33%   |
| 3866    | 1        | 1.33%   |
| 3800    | 1        | 1.33%   |
| 3533    | 1        | 1.33%   |
| 2666    | 1        | 1.33%   |
| 2134    | 1        | 1.33%   |
| 1866    | 1        | 1.33%   |
| 1639    | 1        | 1.33%   |
| 1632    | 1        | 1.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 3        | 37.5%   |
| Samsung Electronics | 2        | 25%     |
| Seiko Epson         | 1        | 12.5%   |
| Canon               | 1        | 12.5%   |
| Brother Industries  | 1        | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Desktops | Percent |
|---------------------------|----------|---------|
| Seiko Epson L3110 Series  | 1        | 12.5%   |
| Samsung SCX-4216F Scanner | 1        | 12.5%   |
| Samsung Composite Device  | 1        | 12.5%   |
| HP Officejet 4500 G510g-m | 1        | 12.5%   |
| HP LaserJet 1010          | 1        | 12.5%   |
| HP DeskJet 5940           | 1        | 12.5%   |
| Canon PIXMA MG3000 series | 1        | 12.5%   |
| Brother DCP-L2510D series | 1        | 12.5%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| Mustek Systems | 2        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Mustek Systems ScanExpress 1200 UB | 2        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Logitech                    | 11       | 36.67%  |
| Z-Star Microelectronics     | 3        | 10%     |
| Microdia                    | 3        | 10%     |
| Apple                       | 3        | 10%     |
| Tobii Technology AB         | 1        | 3.33%   |
| Samsung Electronics         | 1        | 3.33%   |
| Razer USA                   | 1        | 3.33%   |
| Pixart Imaging              | 1        | 3.33%   |
| KYE Systems (Mouse Systems) | 1        | 3.33%   |
| Genesys Logic               | 1        | 3.33%   |
| GEMBIRD                     | 1        | 3.33%   |
| Cubeternet                  | 1        | 3.33%   |
| Chicony Electronics         | 1        | 3.33%   |
| A4Tech                      | 1        | 3.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Logitech Webcam C270                        | 3        | 10%     |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR          | 3        | 10%     |
| Z-Star A4 TECH HD PC Camera                 | 2        | 6.67%   |
| Logitech Webcam C170                        | 2        | 6.67%   |
| Z-Star Vega USB 2.0 Camera                  | 1        | 3.33%   |
| Tobii AB EyeChip                            | 1        | 3.33%   |
| Samsung Galaxy series, misc. (MTP mode)     | 1        | 3.33%   |
| Razer USA Gaming Webcam [Kiyo]              | 1        | 3.33%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro        | 1        | 3.33%   |
| Microdia USB 2.0 Camera                     | 1        | 3.33%   |
| Microdia Defender G-Lens 2577 HD720p Camera | 1        | 3.33%   |
| Microdia Camera                             | 1        | 3.33%   |
| Logitech Webcam C310                        | 1        | 3.33%   |
| Logitech Webcam C250                        | 1        | 3.33%   |
| Logitech Webcam C210                        | 1        | 3.33%   |
| Logitech QuickCam Pro 9000                  | 1        | 3.33%   |
| Logitech HD Webcam C525                     | 1        | 3.33%   |
| Logitech HD Webcam C510                     | 1        | 3.33%   |
| KYE Systems (Mouse Systems) eFace 2050AF    | 1        | 3.33%   |
| Genesys Logic Camera                        | 1        | 3.33%   |
| GEMBIRD USB2.0 PC CAMERA                    | 1        | 3.33%   |
| Cubeternet USB2.0 Camera                    | 1        | 3.33%   |
| Chicony HP High Definition Webcam           | 1        | 3.33%   |
| A4Tech A4tech FHD 1080P PC Camera           | 1        | 3.33%   |

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
| Alcor Micro      | 1        | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 1        | 50%     |
| Alcor Micro AU9540 Smartcard Reader                    | 1        | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 98       | 86.73%  |
| 1     | 14       | 12.39%  |
| 2     | 1        | 0.88%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 7        | 43.75%  |
| Net/wireless             | 3        | 18.75%  |
| Communication controller | 2        | 12.5%   |
| Storage/raid             | 1        | 6.25%   |
| Net/ethernet             | 1        | 6.25%   |
| Multimedia controller    | 1        | 6.25%   |
| Chipcard                 | 1        | 6.25%   |

