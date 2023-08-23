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

Total: 165

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 6        | 5.17%   |
| Ubuntu 18.04                 | 6        | 5.17%   |
| ROSA R10                     | 6        | 5.17%   |
| ROSA R11                     | 5        | 4.31%   |
| KDE neon 20.04               | 5        | 4.31%   |
| Ubuntu 22.04                 | 4        | 3.45%   |
| Linux Mint 20.1              | 4        | 3.45%   |
| Arch Rolling                 | 4        | 3.45%   |
| Xubuntu 20.04                | 3        | 2.59%   |
| ROSA R9                      | 3        | 2.59%   |
| Linux Mint 21.1              | 3        | 2.59%   |
| Linux Mint 20.2              | 3        | 2.59%   |
| Fedora 37                    | 3        | 2.59%   |
| ROSA R8.1                    | 2        | 1.72%   |
| ROSA 12.2                    | 2        | 1.72%   |
| OpenMandriva 4.50            | 2        | 1.72%   |
| OpenMandriva 4.2             | 2        | 1.72%   |
| OpenMandriva 23.01           | 2        | 1.72%   |
| Linux Mint 20.3              | 2        | 1.72%   |
| Linux Mint 19.3              | 2        | 1.72%   |
| Fedora 35                    | 2        | 1.72%   |
| Fedora 30                    | 2        | 1.72%   |
| Debian Testing               | 2        | 1.72%   |
| Debian 11                    | 2        | 1.72%   |
| Zorin 16                     | 1        | 0.86%   |
| Xubuntu 18.04                | 1        | 0.86%   |
| Ubuntu 22.10                 | 1        | 0.86%   |
| Ubuntu 19.10                 | 1        | 0.86%   |
| Ubuntu 16.04                 | 1        | 0.86%   |
| SteamOS 3.4                  | 1        | 0.86%   |
| SteamOS 3.3                  | 1        | 0.86%   |
| ROSA R8                      | 1        | 0.86%   |
| ROSA R11.1                   | 1        | 0.86%   |
| Puppy 9                      | 1        | 0.86%   |
| Pop!_OS 22.04                | 1        | 0.86%   |
| Pop!_OS 21.04                | 1        | 0.86%   |
| openSUSE Tumbleweed-XXXXXXXX | 1        | 0.86%   |
| OpenMandriva 4.3             | 1        | 0.86%   |
| OpenMandriva 23.03           | 1        | 0.86%   |
| Manjaro 20.2.1               | 1        | 0.86%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 19       | 17.76%  |
| ROSA         | 18       | 16.82%  |
| Linux Mint   | 16       | 14.95%  |
| Fedora       | 9        | 8.41%   |
| OpenMandriva | 8        | 7.48%   |
| KDE neon     | 5        | 4.67%   |
| Arch         | 5        | 4.67%   |
| Xubuntu      | 4        | 3.74%   |
| Debian       | 4        | 3.74%   |
| Pop!_OS      | 2        | 1.87%   |
| Manjaro      | 2        | 1.87%   |
| Kubuntu      | 2        | 1.87%   |
| Garuda Linux | 2        | 1.87%   |
| Clear Linux  | 2        | 1.87%   |
| Zorin        | 1        | 0.93%   |
| SteamOS      | 1        | 0.93%   |
| Puppy        | 1        | 0.93%   |
| openSUSE     | 1        | 0.93%   |
| Lubuntu      | 1        | 0.93%   |
| LMDE         | 1        | 0.93%   |
| Kali         | 1        | 0.93%   |
| Endless      | 1        | 0.93%   |
| EndeavourOS  | 1        | 0.93%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Desktops | Percent |
|---------------------------------|----------|---------|
| 4.9.60-nrj-desktop-1rosa-x86_64 | 5        | 3.94%   |
| 5.4.0-58-generic                | 4        | 3.15%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 4        | 3.15%   |
| 5.4.0-132-generic               | 3        | 2.36%   |
| 5.4.0-122-generic               | 3        | 2.36%   |
| 4.15.0-desktop-45.1rosa-x86_64  | 3        | 2.36%   |
| 6.1.1-desktop-1omv2290          | 2        | 1.57%   |
| 5.4.0-66-generic                | 2        | 1.57%   |
| 5.4.0-54-generic                | 2        | 1.57%   |
| 5.13.0-39-generic               | 2        | 1.57%   |
| 5.12.4-desktop-1omv4050         | 2        | 1.57%   |
| 5.10.14-desktop-1omv4002        | 2        | 1.57%   |
| 5.0.0-37-generic                | 2        | 1.57%   |
| 6.3.7-200.fc38.x86_64           | 1        | 0.79%   |
| 6.2.6-desktop-1omv2390          | 1        | 0.79%   |
| 6.2.6-76060206-generic          | 1        | 0.79%   |
| 6.2.0-060200rc5-generic         | 1        | 0.79%   |
| 6.1.9-200.fc37.x86_64           | 1        | 0.79%   |
| 6.1.1-arch1-1                   | 1        | 0.79%   |
| 6.1.0-7-amd64                   | 1        | 0.79%   |
| 6.0.7-1-default                 | 1        | 0.79%   |
| 6.0.16-300.fc37.x86_64          | 1        | 0.79%   |
| 6.0.13-300.fc37.x86_64          | 1        | 0.79%   |
| 6.0.11-AMD-znver2               | 1        | 0.79%   |
| 5.9.13-1006.native              | 1        | 0.79%   |
| 5.9.0-kali1-amd64               | 1        | 0.79%   |
| 5.8.12-arch1-1                  | 1        | 0.79%   |
| 5.8.0-50-generic                | 1        | 0.79%   |
| 5.8.0-44-generic                | 1        | 0.79%   |
| 5.8.0-25-generic                | 1        | 0.79%   |
| 5.6.3-arch1-1                   | 1        | 0.79%   |
| 5.4.83-generic-2rosa-x86_64     | 1        | 0.79%   |
| 5.4.53                          | 1        | 0.79%   |
| 5.4.18-902.native               | 1        | 0.79%   |
| 5.4.0-80-generic                | 1        | 0.79%   |
| 5.4.0-70-generic                | 1        | 0.79%   |
| 5.4.0-67-generic                | 1        | 0.79%   |
| 5.4.0-62-generic                | 1        | 0.79%   |
| 5.4.0-59-generic                | 1        | 0.79%   |
| 5.4.0-52-generic                | 1        | 0.79%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 19       | 16.24%  |
| 4.15.0  | 10       | 8.55%   |
| 5.15.0  | 9        | 7.69%   |
| 5.13.0  | 5        | 4.27%   |
| 4.9.60  | 5        | 4.27%   |
| 4.9.20  | 5        | 4.27%   |
| 5.3.0   | 4        | 3.42%   |
| 6.1.1   | 3        | 2.56%   |
| 5.8.0   | 3        | 2.56%   |
| 5.19.0  | 3        | 2.56%   |
| 5.11.0  | 3        | 2.56%   |
| 6.2.6   | 2        | 1.71%   |
| 5.12.4  | 2        | 1.71%   |
| 5.10.14 | 2        | 1.71%   |
| 5.10.0  | 2        | 1.71%   |
| 5.0.0   | 2        | 1.71%   |
| 6.3.7   | 1        | 0.85%   |
| 6.2.0   | 1        | 0.85%   |
| 6.1.9   | 1        | 0.85%   |
| 6.1.0   | 1        | 0.85%   |
| 6.0.7   | 1        | 0.85%   |
| 6.0.16  | 1        | 0.85%   |
| 6.0.13  | 1        | 0.85%   |
| 6.0.11  | 1        | 0.85%   |
| 5.9.13  | 1        | 0.85%   |
| 5.9.0   | 1        | 0.85%   |
| 5.8.12  | 1        | 0.85%   |
| 5.6.3   | 1        | 0.85%   |
| 5.4.83  | 1        | 0.85%   |
| 5.4.53  | 1        | 0.85%   |
| 5.4.18  | 1        | 0.85%   |
| 5.2.9   | 1        | 0.85%   |
| 5.2.14  | 1        | 0.85%   |
| 5.19.10 | 1        | 0.85%   |
| 5.18.1  | 1        | 0.85%   |
| 5.17.5  | 1        | 0.85%   |
| 5.17.0  | 1        | 0.85%   |
| 5.16.7  | 1        | 0.85%   |
| 5.16.18 | 1        | 0.85%   |
| 5.16.15 | 1        | 0.85%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 22       | 18.97%  |
| 4.9     | 11       | 9.48%   |
| 4.15    | 10       | 8.62%   |
| 5.15    | 9        | 7.76%   |
| 5.11    | 7        | 6.03%   |
| 5.10    | 7        | 6.03%   |
| 5.13    | 6        | 5.17%   |
| 6.1     | 5        | 4.31%   |
| 6.0     | 4        | 3.45%   |
| 5.8     | 4        | 3.45%   |
| 5.3     | 4        | 3.45%   |
| 5.19    | 4        | 3.45%   |
| 6.2     | 3        | 2.59%   |
| 5.16    | 3        | 2.59%   |
| 5.9     | 2        | 1.72%   |
| 5.2     | 2        | 1.72%   |
| 5.17    | 2        | 1.72%   |
| 5.12    | 2        | 1.72%   |
| 5.0     | 2        | 1.72%   |
| 6.3     | 1        | 0.86%   |
| 5.6     | 1        | 0.86%   |
| 5.18    | 1        | 0.86%   |
| 5.14    | 1        | 0.86%   |
| 4.8     | 1        | 0.86%   |
| 4.18    | 1        | 0.86%   |
| 4.1     | 1        | 0.86%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 96       | 96%     |
| i686   | 4        | 4%      |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 30       | 27.52%  |
| KDE5       | 23       | 21.1%   |
| X-Cinnamon | 12       | 11.01%  |
| Unknown    | 11       | 10.09%  |
| KDE4       | 10       | 9.17%   |
| XFCE       | 8        | 7.34%   |
| MATE       | 5        | 4.59%   |
| KDE        | 5        | 4.59%   |
| Deepin     | 2        | 1.83%   |
| Cinnamon   | 2        | 1.83%   |
| LXQt       | 1        | 0.92%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 82       | 81.19%  |
| Wayland | 14       | 13.86%  |
| Unknown | 3        | 2.97%   |
| Tty     | 2        | 1.98%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 51       | 46.79%  |
| SDDM    | 21       | 19.27%  |
| KDM     | 10       | 9.17%   |
| GDM     | 9        | 8.26%   |
| LightDM | 8        | 7.34%   |
| GDM3    | 6        | 5.5%    |
| TDM     | 4        | 3.67%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| en_US       | 41       | 37.96%  |
| Unknown     | 22       | 20.37%  |
| ru_RU       | 16       | 14.81%  |
| lv_LV       | 14       | 12.96%  |
| en_GB       | 7        | 6.48%   |
| C           | 4        | 3.7%    |
| ru_RU.UTF_8 | 1        | 0.93%   |
| osa_US      | 1        | 0.93%   |
| de_DE       | 1        | 0.93%   |
| cv_RU       | 1        | 0.93%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 67       | 67%     |
| EFI  | 33       | 33%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 72       | 67.92%  |
| Unknown | 12       | 11.32%  |
| Btrfs   | 10       | 9.43%   |
| Overlay | 8        | 7.55%   |
| Xfs     | 1        | 0.94%   |
| Tmpfs   | 1        | 0.94%   |
| Ext3    | 1        | 0.94%   |
| Aufs    | 1        | 0.94%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 55       | 51.89%  |
| GPT     | 27       | 25.47%  |
| MBR     | 24       | 22.64%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 88       | 83.02%  |
| Yes       | 18       | 16.98%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 74       | 69.81%  |
| Yes       | 32       | 30.19%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 29       | 29%     |
| Gigabyte Technology | 21       | 21%     |
| MSI                 | 12       | 12%     |
| ASRock              | 11       | 11%     |
| Dell                | 7        | 7%      |
| Hewlett-Packard     | 5        | 5%      |
| Intel               | 3        | 3%      |
| Acer                | 3        | 3%      |
| Biostar             | 2        | 2%      |
| Lenovo              | 1        | 1%      |
| IBM                 | 1        | 1%      |
| Hardkernel          | 1        | 1%      |
| Fujitsu Siemens     | 1        | 1%      |
| Foxconn             | 1        | 1%      |
| Acidanthera         | 1        | 1%      |
| ABIT                | 1        | 1%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| ASUS All Series                    | 6        | 6%      |
| MSI MS-7721                        | 2        | 2%      |
| Gigabyte G33M-S2                   | 2        | 2%      |
| Gigabyte B550 AORUS PRO V2         | 2        | 2%      |
| Gigabyte 946GMX-S2                 | 2        | 2%      |
| Dell OptiPlex 7020                 | 2        | 2%      |
| ASUS TUF Gaming X570-PLUS          | 2        | 2%      |
| MSI MS-7C52                        | 1        | 1%      |
| MSI MS-7B46                        | 1        | 1%      |
| MSI MS-7B33                        | 1        | 1%      |
| MSI MS-7996                        | 1        | 1%      |
| MSI MS-7850                        | 1        | 1%      |
| MSI MS-7846                        | 1        | 1%      |
| MSI MS-7758                        | 1        | 1%      |
| MSI MS-7693                        | 1        | 1%      |
| MSI MS-7583                        | 1        | 1%      |
| MSI MS-7519                        | 1        | 1%      |
| Lenovo Legion T5 26AMR5 90RC018LBX | 1        | 1%      |
| Intel DQ87PG AAG74154-403          | 1        | 1%      |
| Intel DH77EB AAG39073-304          | 1        | 1%      |
| Intel DB85FL AAG89861-201          | 1        | 1%      |
| IBM 8215ZCL                        | 1        | 1%      |
| HP ProDesk 600 G1 TWR              | 1        | 1%      |
| HP Compaq dc7800 Small Form Factor | 1        | 1%      |
| HP Compaq dc5700 Microtower        | 1        | 1%      |
| HP Compaq 8100 Elite CMT PC        | 1        | 1%      |
| HP 310-1205uk                      | 1        | 1%      |
| Hardkernel ODROID-H2               | 1        | 1%      |
| Gigabyte Z87P-D3                   | 1        | 1%      |
| Gigabyte Z87-HD3                   | 1        | 1%      |
| Gigabyte Z790 GAMING X AX          | 1        | 1%      |
| Gigabyte X570 AORUS ELITE          | 1        | 1%      |
| Gigabyte M61PME-S2                 | 1        | 1%      |
| Gigabyte H97-D3H                   | 1        | 1%      |
| Gigabyte H61MA-D2V                 | 1        | 1%      |
| Gigabyte H61M-S2-B3                | 1        | 1%      |
| Gigabyte H55M-D2H                  | 1        | 1%      |
| Gigabyte GA-970A-UD3               | 1        | 1%      |
| Gigabyte G41M-ES2L                 | 1        | 1%      |
| Gigabyte G31M-ES2L                 | 1        | 1%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Dell OptiPlex        | 7        | 7%      |
| ASUS All             | 6        | 6%      |
| ASUS PRIME           | 5        | 5%      |
| HP Compaq            | 3        | 3%      |
| ASUS ROG             | 3        | 3%      |
| MSI MS-7721          | 2        | 2%      |
| Gigabyte G33M-S2     | 2        | 2%      |
| Gigabyte B550        | 2        | 2%      |
| Gigabyte 946GMX-S2   | 2        | 2%      |
| ASUS TUF             | 2        | 2%      |
| ASUS P5Q             | 2        | 2%      |
| Acer Aspire          | 2        | 2%      |
| MSI MS-7C52          | 1        | 1%      |
| MSI MS-7B46          | 1        | 1%      |
| MSI MS-7B33          | 1        | 1%      |
| MSI MS-7996          | 1        | 1%      |
| MSI MS-7850          | 1        | 1%      |
| MSI MS-7846          | 1        | 1%      |
| MSI MS-7758          | 1        | 1%      |
| MSI MS-7693          | 1        | 1%      |
| MSI MS-7583          | 1        | 1%      |
| MSI MS-7519          | 1        | 1%      |
| Lenovo Legion        | 1        | 1%      |
| Intel DQ87PG         | 1        | 1%      |
| Intel DH77EB         | 1        | 1%      |
| Intel DB85FL         | 1        | 1%      |
| IBM 8215ZCL          | 1        | 1%      |
| HP ProDesk           | 1        | 1%      |
| HP 310-1205uk        | 1        | 1%      |
| Hardkernel ODROID-H2 | 1        | 1%      |
| Gigabyte Z87P-D3     | 1        | 1%      |
| Gigabyte Z87-HD3     | 1        | 1%      |
| Gigabyte Z790        | 1        | 1%      |
| Gigabyte X570        | 1        | 1%      |
| Gigabyte M61PME-S2   | 1        | 1%      |
| Gigabyte H97-D3H     | 1        | 1%      |
| Gigabyte H61MA-D2V   | 1        | 1%      |
| Gigabyte H61M-S2-B3  | 1        | 1%      |
| Gigabyte H55M-D2H    | 1        | 1%      |
| Gigabyte GA-970A-UD3 | 1        | 1%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 13       | 13%     |
| 2007 | 13       | 13%     |
| 2012 | 10       | 10%     |
| 2008 | 9        | 9%      |
| 2018 | 7        | 7%      |
| 2009 | 7        | 7%      |
| 2019 | 6        | 6%      |
| 2017 | 5        | 5%      |
| 2015 | 5        | 5%      |
| 2014 | 5        | 5%      |
| 2011 | 5        | 5%      |
| 2006 | 4        | 4%      |
| 2022 | 2        | 2%      |
| 2021 | 2        | 2%      |
| 2020 | 2        | 2%      |
| 2010 | 2        | 2%      |
| 2023 | 1        | 1%      |
| 2016 | 1        | 1%      |
| 2004 | 1        | 1%      |

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
| Disabled | 100      | 100%    |

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


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 3.01-4.0        | 23       | 22.12%  |
| 8.01-16.0       | 23       | 22.12%  |
| 4.01-8.0        | 15       | 14.42%  |
| 32.01-64.0      | 15       | 14.42%  |
| 16.01-24.0      | 14       | 13.46%  |
| 1.01-2.0        | 6        | 5.77%   |
| 24.01-32.0      | 3        | 2.88%   |
| 2.01-3.0        | 3        | 2.88%   |
| More than 256.0 | 1        | 0.96%   |
| 64.01-256.0     | 1        | 0.96%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 39       | 33.62%  |
| 2.01-3.0   | 24       | 20.69%  |
| 0.51-1.0   | 20       | 17.24%  |
| 4.01-8.0   | 17       | 14.66%  |
| 3.01-4.0   | 11       | 9.48%   |
| 8.01-16.0  | 4        | 3.45%   |
| 16.01-24.0 | 1        | 0.86%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 47       | 43.12%  |
| 2      | 26       | 23.85%  |
| 3      | 20       | 18.35%  |
| 4      | 10       | 9.17%   |
| 5      | 3        | 2.75%   |
| 6      | 2        | 1.83%   |
| 7      | 1        | 0.92%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 58       | 56.86%  |
| Yes       | 44       | 43.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 99       | 99%     |
| No        | 1        | 1%      |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 68       | 67.33%  |
| Yes       | 33       | 32.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 81       | 80.2%   |
| Yes       | 20       | 19.8%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Latvia  | 100      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City       | Desktops | Percent |
|------------|----------|---------|
| Riga       | 72       | 68.57%  |
| Ventspils  | 5        | 4.76%   |
| Salaspils  | 4        | 3.81%   |
| Jelgava    | 3        | 2.86%   |
| Talsi      | 2        | 1.9%    |
| Jūrmala   | 2        | 1.9%    |
| Daugavpils | 2        | 1.9%    |
| Adazi      | 2        | 1.9%    |
| Ragana     | 1        | 0.95%   |
| Ogre       | 1        | 0.95%   |
| Mirnijs    | 1        | 0.95%   |
| Limbaži   | 1        | 0.95%   |
| Liepāja   | 1        | 0.95%   |
| Lielvārde | 1        | 0.95%   |
| Kuldīga   | 1        | 0.95%   |
| Jēkabpils | 1        | 0.95%   |
| Iecava     | 1        | 0.95%   |
| Dreilini   | 1        | 0.95%   |
| Carnikava  | 1        | 0.95%   |
| Brankas    | 1        | 0.95%   |
| Bauska     | 1        | 0.95%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| WDC                          | 41       | 65     | 22.4%   |
| Seagate                      | 40       | 62     | 21.86%  |
| Samsung Electronics          | 31       | 60     | 16.94%  |
| Kingston                     | 13       | 23     | 7.1%    |
| Crucial                      | 11       | 20     | 6.01%   |
| Intel                        | 6        | 11     | 3.28%   |
| Hitachi                      | 6        | 8      | 3.28%   |
| Toshiba                      | 5        | 7      | 2.73%   |
| HGST                         | 3        | 3      | 1.64%   |
| GOODRAM                      | 3        | 8      | 1.64%   |
| Transcend                    | 2        | 2      | 1.09%   |
| OCZ                          | 2        | 3      | 1.09%   |
| A-DATA Technology            | 2        | 3      | 1.09%   |
| Unknown                      | 1        | 1      | 0.55%   |
| SPCC                         | 1        | 3      | 0.55%   |
| Silicon Motion               | 1        | 1      | 0.55%   |
| Shenzhen Longsys Electronics | 1        | 1      | 0.55%   |
| Realtek Semiconductor        | 1        | 1      | 0.55%   |
| Patriot                      | 1        | 1      | 0.55%   |
| Netac                        | 1        | 1      | 0.55%   |
| Mushkin                      | 1        | 2      | 0.55%   |
| Maxtor                       | 1        | 1      | 0.55%   |
| Lite-On Technology           | 1        | 1      | 0.55%   |
| KIOXIA-EXCERIA               | 1        | 1      | 0.55%   |
| KingFast                     | 1        | 2      | 0.55%   |
| Intenso                      | 1        | 1      | 0.55%   |
| IBM/Hitachi                  | 1        | 1      | 0.55%   |
| HS-SSD-E100                  | 1        | 1      | 0.55%   |
| GLOWAY                       | 1        | 2      | 0.55%   |
| CHN25SATAS1                  | 1        | 1      | 0.55%   |
| ADATA Technology             | 1        | 2      | 0.55%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 6        | 2.8%    |
| Seagate ST1000DM010-2EP102 1TB                      | 4        | 1.87%   |
| Crucial CT500MX500SSD1 500GB                        | 4        | 1.87%   |
| Crucial CT1000MX500SSD1 1TB                         | 4        | 1.87%   |
| WDC WD2000JD-00HBB0 200GB                           | 3        | 1.4%    |
| Seagate ST500DM005 HD502HJ 500GB                    | 3        | 1.4%    |
| Seagate ST3500418AS 500GB                           | 3        | 1.4%    |
| Samsung NVMe SSD Drive 500GB                        | 3        | 1.4%    |
| Kingston SV300S37A240G 240GB SSD                    | 3        | 1.4%    |
| WDC WD6003FZBX-00K5WB0 6TB                          | 2        | 0.93%   |
| WDC WD5002AALX-00J37A0 500GB                        | 2        | 0.93%   |
| WDC WD5000AAKX-22ERMA0 500GB                        | 2        | 0.93%   |
| WDC WD5000AAKX-00ERMA0 500GB                        | 2        | 0.93%   |
| WDC WD5000AAKX-001CA0 500GB                         | 2        | 0.93%   |
| WDC WD20EARX-00PASB0 2TB                            | 2        | 0.93%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 2        | 0.93%   |
| Seagate ST3500413AS 500GB                           | 2        | 0.93%   |
| Seagate ST3320620AS 320GB                           | 2        | 0.93%   |
| Seagate ST3250824AS 250GB                           | 2        | 0.93%   |
| Seagate ST250DM000-1BD141 250GB                     | 2        | 0.93%   |
| Seagate ST2000DM001-1CH164 2TB                      | 2        | 0.93%   |
| Seagate ST1000DX001-1CM162 1TB                      | 2        | 0.93%   |
| Seagate ST1000DM003-1SB102 1TB                      | 2        | 0.93%   |
| Samsung SSD 970 EVO Plus 500GB                      | 2        | 0.93%   |
| Samsung SSD 860 EVO 500GB                           | 2        | 0.93%   |
| Samsung SSD 860 EVO 1TB                             | 2        | 0.93%   |
| Samsung SSD 850 EVO 500GB                           | 2        | 0.93%   |
| Samsung SSD 850 EVO 250GB                           | 2        | 0.93%   |
| Samsung SSD 650 120GB                               | 2        | 0.93%   |
| Samsung SP2504C 250GB                               | 2        | 0.93%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 2        | 0.93%   |
| Samsung HD501LJ 500GB                               | 2        | 0.93%   |
| Samsung HD103UJ 1TB                                 | 2        | 0.93%   |
| Intel SSDSA2CW120G3 120GB                           | 2        | 0.93%   |
| HGST HTS541010A9E680 1TB                            | 2        | 0.93%   |
| GOODRAM SSDPR-CX400-128-G2 128GB                    | 2        | 0.93%   |
| Crucial CT480BX500SSD1 480GB                        | 2        | 0.93%   |
| Crucial CT120BX500SSD1 120GB                        | 2        | 0.93%   |
| WDC WDS500G3X0C-00SJG0 500GB                        | 1        | 0.47%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 1        | 0.47%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 40       | 62     | 38.46%  |
| WDC                 | 36       | 56     | 34.62%  |
| Samsung Electronics | 12       | 19     | 11.54%  |
| Hitachi             | 6        | 8      | 5.77%   |
| Toshiba             | 5        | 7      | 4.81%   |
| HGST                | 3        | 3      | 2.88%   |
| Maxtor              | 1        | 1      | 0.96%   |
| IBM/Hitachi         | 1        | 1      | 0.96%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 13       | 23     | 20.63%  |
| Kingston            | 13       | 23     | 20.63%  |
| Crucial             | 11       | 20     | 17.46%  |
| WDC                 | 5        | 6      | 7.94%   |
| Intel               | 4        | 9      | 6.35%   |
| GOODRAM             | 3        | 8      | 4.76%   |
| Transcend           | 2        | 2      | 3.17%   |
| OCZ                 | 2        | 3      | 3.17%   |
| A-DATA Technology   | 2        | 3      | 3.17%   |
| SPCC                | 1        | 3      | 1.59%   |
| Patriot             | 1        | 1      | 1.59%   |
| Mushkin             | 1        | 2      | 1.59%   |
| KIOXIA-EXCERIA      | 1        | 1      | 1.59%   |
| KingFast            | 1        | 2      | 1.59%   |
| Intenso             | 1        | 1      | 1.59%   |
| GLOWAY              | 1        | 2      | 1.59%   |
| CHN25SATAS1         | 1        | 1      | 1.59%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 77       | 157    | 52.74%  |
| SSD     | 47       | 110    | 32.19%  |
| NVMe    | 20       | 30     | 13.7%   |
| MMC     | 1        | 1      | 0.68%   |
| Unknown | 1        | 1      | 0.68%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 94       | 265    | 79.66%  |
| NVMe | 20       | 30     | 16.95%  |
| SAS  | 3        | 3      | 2.54%   |
| MMC  | 1        | 1      | 0.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 78       | 172    | 60%     |
| 0.51-1.0   | 36       | 65     | 27.69%  |
| 1.01-2.0   | 9        | 21     | 6.92%   |
| 2.01-3.0   | 3        | 5      | 2.31%   |
| 4.01-10.0  | 3        | 3      | 2.31%   |
| 3.01-4.0   | 1        | 1      | 0.77%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 34       | 30.91%  |
| 1001-2000      | 14       | 12.73%  |
| 251-500        | 13       | 11.82%  |
| 501-1000       | 11       | 10%     |
| 51-100         | 10       | 9.09%   |
| More than 3000 | 8        | 7.27%   |
| 21-50          | 7        | 6.36%   |
| 2001-3000      | 6        | 5.45%   |
| 1-20           | 6        | 5.45%   |
| Unknown        | 1        | 0.91%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 43       | 36.13%  |
| 101-250        | 17       | 14.29%  |
| 21-50          | 15       | 12.61%  |
| 251-500        | 12       | 10.08%  |
| 51-100         | 12       | 10.08%  |
| 501-1000       | 11       | 9.24%   |
| 1001-2000      | 5        | 4.2%    |
| 2001-3000      | 2        | 1.68%   |
| More than 3000 | 1        | 0.84%   |
| Unknown        | 1        | 0.84%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD20EARX-00PASB0 2TB              | 2        | 4      | 6.25%   |
| WDC WD2000JD-00HBB0 200GB             | 2        | 4      | 6.25%   |
| Seagate ST1000DM003-1SB102 1TB        | 2        | 7      | 6.25%   |
| Samsung Electronics SP2504C 250GB     | 2        | 2      | 6.25%   |
| Samsung Electronics HD501LJ 500GB     | 2        | 7      | 6.25%   |
| WDC WDS500G3X0C-00SJG0 500GB          | 1        | 1      | 3.13%   |
| WDC WD800JD-60MSA1 80GB               | 1        | 1      | 3.13%   |
| WDC WD5002AALX-00J37A0 500GB          | 1        | 1      | 3.13%   |
| WDC WD5001AALS-00L3B2 500GB           | 1        | 1      | 3.13%   |
| WDC WD5001AALS-00E3A0 500GB           | 1        | 1      | 3.13%   |
| WDC WD2500AAKS-60L9A0 250GB           | 1        | 1      | 3.13%   |
| WDC WD1600AAJS-00B4A0 160GB           | 1        | 1      | 3.13%   |
| Toshiba DT01ACA100 1TB                | 1        | 1      | 3.13%   |
| Seagate ST3500820AS 500GB             | 1        | 1      | 3.13%   |
| Seagate ST3500413AS 500GB             | 1        | 1      | 3.13%   |
| Seagate ST3500312CS 500GB             | 1        | 1      | 3.13%   |
| Seagate ST340016A 40GB                | 1        | 1      | 3.13%   |
| Seagate ST3250620AS 250GB             | 1        | 1      | 3.13%   |
| Seagate ST3250312AS 250GB             | 1        | 1      | 3.13%   |
| Seagate ST31000528AS 1TB              | 1        | 1      | 3.13%   |
| Seagate ST3000DM001-9YN166 3TB        | 1        | 1      | 3.13%   |
| Seagate ST1000DX001-1CM162 1TB        | 1        | 1      | 3.13%   |
| Samsung Electronics SSD 970 EVO 500GB | 1        | 1      | 3.13%   |
| Kingston SV300S37A60G 64GB SSD        | 1        | 1      | 3.13%   |
| Hitachi HTS542525K9A300 250GB         | 1        | 1      | 3.13%   |
| CHN25SATAS1 SSD 128 128GB             | 1        | 1      | 3.13%   |
| A-DATA Technology SU800NS38 512GB SSD | 1        | 2      | 3.13%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 10       | 15     | 33.33%  |
| Seagate             | 10       | 16     | 33.33%  |
| Samsung Electronics | 5        | 10     | 16.67%  |
| Toshiba             | 1        | 1      | 3.33%   |
| Kingston            | 1        | 1      | 3.33%   |
| Hitachi             | 1        | 1      | 3.33%   |
| CHN25SATAS1         | 1        | 1      | 3.33%   |
| A-DATA Technology   | 1        | 2      | 3.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 10       | 16     | 40%     |
| WDC                 | 9        | 14     | 36%     |
| Samsung Electronics | 4        | 9      | 16%     |
| Toshiba             | 1        | 1      | 4%      |
| Hitachi             | 1        | 1      | 4%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 18       | 41     | 78.26%  |
| SSD  | 3        | 4      | 13.04%  |
| NVMe | 2        | 2      | 8.7%    |

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
| Detected | 58       | 143    | 47.93%  |
| Works    | 41       | 109    | 33.88%  |
| Malfunc  | 22       | 47     | 18.18%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 66       | 48.89%  |
| AMD                              | 29       | 21.48%  |
| Samsung Electronics              | 12       | 8.89%   |
| JMicron Technology               | 7        | 5.19%   |
| Nvidia                           | 5        | 3.7%    |
| Marvell Technology Group         | 5        | 3.7%    |
| ASMedia Technology               | 3        | 2.22%   |
| SanDisk                          | 2        | 1.48%   |
| Silicon Motion                   | 1        | 0.74%   |
| Silicon Integrated Systems [SiS] | 1        | 0.74%   |
| Shenzhen Longsys Electronics     | 1        | 0.74%   |
| Realtek Semiconductor            | 1        | 0.74%   |
| Lite-On Technology               | 1        | 0.74%   |
| ADATA Technology                 | 1        | 0.74%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 15       | 8.38%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 12       | 6.7%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 10       | 5.59%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 9        | 5.03%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 7        | 3.91%   |
| JMicron JMB368 IDE controller                                                  | 5        | 2.79%   |
| AMD 500 Series Chipset SATA Controller                                         | 5        | 2.79%   |
| Nvidia MCP61 SATA Controller                                                   | 4        | 2.23%   |
| Nvidia MCP61 IDE                                                               | 4        | 2.23%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4        | 2.23%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 4        | 2.23%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 4        | 2.23%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 4        | 2.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4        | 2.23%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4        | 2.23%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4        | 2.23%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3        | 1.68%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 3        | 1.68%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 3        | 1.68%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 3        | 1.68%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 3        | 1.68%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3        | 1.68%   |
| AMD FCH IDE Controller                                                         | 3        | 1.68%   |
| AMD 300 Series Chipset SATA Controller                                         | 3        | 1.68%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                      | 2        | 1.12%   |
| JMicron JMB363 SATA/IDE Controller                                             | 2        | 1.12%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2        | 1.12%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 2        | 1.12%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]            | 2        | 1.12%   |
| Intel 82801IB (ICH9) 4 port SATA Controller [AHCI mode]                        | 2        | 1.12%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]            | 2        | 1.12%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                   | 2        | 1.12%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2        | 1.12%   |
| AMD 400 Series Chipset SATA Controller                                         | 2        | 1.12%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1        | 0.56%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 1        | 0.56%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 1        | 0.56%   |
| Shenzhen Longsys Lexar NM760 NVME SSD (DRAM-less)                              | 1        | 0.56%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1        | 0.56%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1        | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 69       | 53.08%  |
| IDE  | 40       | 30.77%  |
| NVMe | 20       | 15.38%  |
| RAID | 1        | 0.77%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 66       | 66%     |
| AMD    | 34       | 34%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Intel Core i5-4570 CPU @ 3.20GHz              | 4        | 4%      |
| Intel Core i5-4460 CPU @ 3.20GHz              | 3        | 3%      |
| Intel Core i3-3220 CPU @ 3.30GHz              | 3        | 3%      |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 3        | 3%      |
| AMD Ryzen 5 5600X 6-Core Processor            | 3        | 3%      |
| Intel Pentium Dual CPU E2200 @ 2.20GHz        | 2        | 2%      |
| Intel Pentium D CPU 3.40GHz                   | 2        | 2%      |
| Intel Pentium D CPU 2.80GHz                   | 2        | 2%      |
| Intel Core i7-8700K CPU @ 3.70GHz             | 2        | 2%      |
| Intel Core i7-4770 CPU @ 3.40GHz              | 2        | 2%      |
| Intel Core i5 CPU 650 @ 3.20GHz               | 2        | 2%      |
| Intel Core i3-2120 CPU @ 3.30GHz              | 2        | 2%      |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz         | 2        | 2%      |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz          | 2        | 2%      |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz          | 2        | 2%      |
| Intel Core 2 CPU 6300 @ 1.86GHz               | 2        | 2%      |
| AMD Ryzen 5 3600 6-Core Processor             | 2        | 2%      |
| AMD A8-7600 Radeon R7, 10 Compute Cores 4C+6G | 2        | 2%      |
| AMD A8-6600K APU with Radeon HD Graphics      | 2        | 2%      |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz   | 1        | 1%      |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 1        | 1%      |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz   | 1        | 1%      |
| Intel Pentium Dual CPU E2220 @ 2.40GHz        | 1        | 1%      |
| Intel Pentium D CPU 3.00GHz                   | 1        | 1%      |
| Intel Pentium CPU G620 @ 2.60GHz              | 1        | 1%      |
| Intel Pentium 4 CPU 2.66GHz                   | 1        | 1%      |
| Intel Core i7-9700K CPU @ 3.60GHz             | 1        | 1%      |
| Intel Core i7-8700T CPU @ 2.40GHz             | 1        | 1%      |
| Intel Core i7-6700K CPU @ 4.00GHz             | 1        | 1%      |
| Intel Core i7-4770K CPU @ 3.50GHz             | 1        | 1%      |
| Intel Core i7-4765T CPU @ 2.00GHz             | 1        | 1%      |
| Intel Core i7-3930K CPU @ 3.20GHz             | 1        | 1%      |
| Intel Core i7-2700K CPU @ 3.50GHz             | 1        | 1%      |
| Intel Core i7 CPU 860 @ 2.80GHz               | 1        | 1%      |
| Intel Core i5-8600K CPU @ 3.60GHz             | 1        | 1%      |
| Intel Core i5-8400 CPU @ 2.80GHz              | 1        | 1%      |
| Intel Core i5-7600K CPU @ 3.80GHz             | 1        | 1%      |
| Intel Core i5-4670K CPU @ 3.40GHz             | 1        | 1%      |
| Intel Core i5-2500K CPU @ 3.30GHz             | 1        | 1%      |
| Intel Core i5-2400 CPU @ 3.10GHz              | 1        | 1%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 15       | 15%     |
| Intel Core i7           | 12       | 12%     |
| Intel Core i3           | 10       | 10%     |
| AMD Ryzen 5             | 9        | 9%      |
| Intel Core 2 Duo        | 7        | 7%      |
| Intel Pentium D         | 5        | 5%      |
| Intel Core 2 Quad       | 5        | 5%      |
| AMD A8                  | 5        | 5%      |
| AMD FX                  | 4        | 4%      |
| Intel Pentium Dual-Core | 3        | 3%      |
| Intel Pentium Dual      | 3        | 3%      |
| AMD Ryzen 9             | 3        | 3%      |
| AMD Ryzen 7             | 3        | 3%      |
| AMD Athlon 64 X2        | 3        | 3%      |
| Intel Core 2            | 2        | 2%      |
| AMD Ryzen Threadripper  | 2        | 2%      |
| AMD Athlon II X2        | 2        | 2%      |
| Other                   | 1        | 1%      |
| Intel Pentium 4         | 1        | 1%      |
| Intel Pentium           | 1        | 1%      |
| Intel Celeron           | 1        | 1%      |
| AMD Sempron             | 1        | 1%      |
| AMD Athlon II X3        | 1        | 1%      |
| AMD Athlon              | 1        | 1%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 40       | 39.6%   |
| 4       | 29       | 28.71%  |
| 6       | 13       | 12.87%  |
| 3       | 5        | 4.95%   |
| 8       | 4        | 3.96%   |
| 16      | 3        | 2.97%   |
| 1       | 3        | 2.97%   |
| 12      | 2        | 1.98%   |
| 24      | 1        | 0.99%   |
| Unknown | 1        | 0.99%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 100      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 52       | 51.49%  |
| 2       | 48       | 47.52%  |
| Unknown | 1        | 0.99%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 99       | 99%     |
| Unknown        | 1        | 1%      |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 17       | 16.83%  |
| 0x306c3    | 12       | 11.88%  |
| 0x1067a    | 8        | 7.92%   |
| 0x206a7    | 5        | 4.95%   |
| 0x906ea    | 4        | 3.96%   |
| 0x10676    | 4        | 3.96%   |
| 0x08701021 | 4        | 3.96%   |
| 0x6fd      | 3        | 2.97%   |
| 0x6fb      | 3        | 2.97%   |
| 0x06001119 | 3        | 2.97%   |
| 0x06000852 | 3        | 2.97%   |
| 0xf65      | 2        | 1.98%   |
| 0xf47      | 2        | 1.98%   |
| 0x6f2      | 2        | 1.98%   |
| 0x506e3    | 2        | 1.98%   |
| 0x306a9    | 2        | 1.98%   |
| 0x0a201009 | 2        | 1.98%   |
| 0x06003106 | 2        | 1.98%   |
| 0x010000c8 | 2        | 1.98%   |
| 0xf64      | 1        | 0.99%   |
| 0xf41      | 1        | 0.99%   |
| 0xb0671    | 1        | 0.99%   |
| 0x906ed    | 1        | 0.99%   |
| 0x906e9    | 1        | 0.99%   |
| 0x706a1    | 1        | 0.99%   |
| 0x206d6    | 1        | 0.99%   |
| 0x20655    | 1        | 0.99%   |
| 0x20652    | 1        | 0.99%   |
| 0x106e5    | 1        | 0.99%   |
| 0x0a50000d | 1        | 0.99%   |
| 0x0a20120a | 1        | 0.99%   |
| 0x0a201016 | 1        | 0.99%   |
| 0x0800820d | 1        | 0.99%   |
| 0x08001138 | 1        | 0.99%   |
| 0x08001137 | 1        | 0.99%   |
| 0x08001126 | 1        | 0.99%   |
| 0x0700010f | 1        | 0.99%   |
| 0x0600063e | 1        | 0.99%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 15       | 15%     |
| Penryn           | 12       | 12%     |
| KabyLake         | 8        | 8%      |
| Core             | 8        | 8%      |
| Zen 3            | 7        | 7%      |
| SandyBridge      | 7        | 7%      |
| Zen 2            | 6        | 6%      |
| Piledriver       | 6        | 6%      |
| NetBurst         | 6        | 6%      |
| K8 Hammer        | 4        | 4%      |
| Zen              | 3        | 3%      |
| K10              | 3        | 3%      |
| IvyBridge        | 3        | 3%      |
| Westmere         | 2        | 2%      |
| Steamroller      | 2        | 2%      |
| Skylake          | 2        | 2%      |
| Zen+             | 1        | 1%      |
| Nehalem          | 1        | 1%      |
| Jaguar           | 1        | 1%      |
| Goldmont plus    | 1        | 1%      |
| Bulldozer        | 1        | 1%      |
| Alderlake Hybrid | 1        | 1%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 48       | 44.04%  |
| AMD    | 33       | 30.28%  |
| Intel  | 28       | 25.69%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5        | 4.42%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 4        | 3.54%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 3        | 2.65%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 2.65%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 2        | 1.77%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 1.77%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 2        | 1.77%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 1.77%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 1.77%   |
| Nvidia GF106 [GeForce GTS 450]                                              | 2        | 1.77%   |
| Nvidia G84 [GeForce 8600 GT]                                                | 2        | 1.77%   |
| Nvidia G72 [GeForce 7300 GS]                                                | 2        | 1.77%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 1.77%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 2        | 1.77%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 2        | 1.77%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.77%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 2        | 1.77%   |
| AMD Richland [Radeon HD 8570D]                                              | 2        | 1.77%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 2        | 1.77%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 1.77%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 2        | 1.77%   |
| AMD Bonaire XTX [Radeon R7 260X/360]                                        | 2        | 1.77%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.88%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 0.88%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 0.88%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 1        | 0.88%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 1        | 0.88%   |
| Nvidia NV44 [GeForce 6200 SE TurboCache]                                    | 1        | 0.88%   |
| Nvidia GT216 [GeForce GT 220]                                               | 1        | 0.88%   |
| Nvidia GT200 [GeForce GTX 260]                                              | 1        | 0.88%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 0.88%   |
| Nvidia GP106 [GeForce GTX 1060 6GB Rev. 2]                                  | 1        | 0.88%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 0.88%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 0.88%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 0.88%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 0.88%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 1        | 0.88%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 0.88%   |
| Nvidia GK208B [GeForce GT 720]                                              | 1        | 0.88%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 1        | 0.88%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 44       | 43.14%  |
| 1 x AMD        | 28       | 27.45%  |
| 1 x Intel      | 22       | 21.57%  |
| 2 x AMD        | 3        | 2.94%   |
| Intel + Nvidia | 3        | 2.94%   |
| 2 x Nvidia     | 1        | 0.98%   |
| Intel + AMD    | 1        | 0.98%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 70       | 68.63%  |
| Proprietary | 27       | 26.47%  |
| Unknown     | 5        | 4.9%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 32       | 31.37%  |
| 0.01-0.5   | 21       | 20.59%  |
| 0.51-1.0   | 15       | 14.71%  |
| 3.01-4.0   | 9        | 8.82%   |
| 1.01-2.0   | 9        | 8.82%   |
| 5.01-6.0   | 7        | 6.86%   |
| 7.01-8.0   | 4        | 3.92%   |
| 8.01-16.0  | 3        | 2.94%   |
| 2.01-3.0   | 1        | 0.98%   |
| 16.01-24.0 | 1        | 0.98%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 18       | 17.82%  |
| Goldstar             | 18       | 17.82%  |
| Philips              | 9        | 8.91%   |
| Dell                 | 8        | 7.92%   |
| BenQ                 | 7        | 6.93%   |
| AOC                  | 7        | 6.93%   |
| Ancor Communications | 6        | 5.94%   |
| Hewlett-Packard      | 5        | 4.95%   |
| Lenovo               | 4        | 3.96%   |
| LG Electronics       | 3        | 2.97%   |
| ViewSonic            | 2        | 1.98%   |
| Unknown              | 2        | 1.98%   |
| NEC Computers        | 2        | 1.98%   |
| Arnos Instruments    | 2        | 1.98%   |
| Wacom                | 1        | 0.99%   |
| Plain Tree Systems   | 1        | 0.99%   |
| IBM                  | 1        | 0.99%   |
| HYO                  | 1        | 0.99%   |
| FUS                  | 1        | 0.99%   |
| AUS                  | 1        | 0.99%   |
| ASUSTek Computer     | 1        | 0.99%   |
| Unknown              | 1        | 0.99%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar L194WT GSM4B06 1440x900 408x255mm 18.9-inch                  | 3        | 2.78%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch              | 2        | 1.85%   |
| LG Electronics LCD Monitor LG TV 1920x1080                            | 2        | 1.85%   |
| Lenovo P24q-10 LEN61A5 2560x1440 527x296mm 23.8-inch                  | 2        | 1.85%   |
| BenQ XL2411Z BNQ7F31 1920x1080 530x300mm 24.0-inch                    | 2        | 1.85%   |
| AOC U2879G6 AOC2879 3840x2160 621x341mm 27.9-inch                     | 2        | 1.85%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch | 2        | 1.85%   |
| Wacom CintiqPro24P WAC1063 3840x2160 522x293mm 23.6-inch              | 1        | 0.93%   |
| ViewSonic VA703-3Series VSC631E 1280x1024 338x270mm 17.0-inch         | 1        | 0.93%   |
| ViewSonic VA503 SERIES VSCEF1D 1024x768 304x228mm 15.0-inch           | 1        | 0.93%   |
| Unknown LCD Monitor Sharp LL-S201A 1920x1080                          | 1        | 0.93%   |
| Unknown LCD Monitor HYO DUAL-DVI 2560x1440                            | 1        | 0.93%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch  | 1        | 0.93%   |
| Samsung Electronics SyncMaster SAM036C 1920x1200 550x343mm 25.5-inch  | 1        | 0.93%   |
| Samsung Electronics SyncMaster SAM02F6 1280x1024 340x270mm 17.1-inch  | 1        | 0.93%   |
| Samsung Electronics SyncMaster SAM0273 1440x900 410x257mm 19.1-inch   | 1        | 0.93%   |
| Samsung Electronics SyncMaster SAM026E 1280x1024 376x301mm 19.0-inch  | 1        | 0.93%   |
| Samsung Electronics SyncMaster SAM0259 1280x1024 376x301mm 19.0-inch  | 1        | 0.93%   |
| Samsung Electronics SyncMaster SAM0217 1280x1024 376x301mm 19.0-inch  | 1        | 0.93%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch  | 1        | 0.93%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch  | 1        | 0.93%   |
| Samsung Electronics SyncMaster SAM006B 1280x1024 338x270mm 17.0-inch  | 1        | 0.93%   |
| Samsung Electronics SA300/SA350 SAM0793 1920x1080 531x299mm 24.0-inch | 1        | 0.93%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1        | 0.93%   |
| Samsung Electronics S24E391 SAM0C12 1920x1080 521x293mm 23.5-inch     | 1        | 0.93%   |
| Samsung Electronics S24E390 SAM0C1A 1920x1080 521x293mm 23.5-inch     | 1        | 0.93%   |
| Samsung Electronics S23B350 SAM08D5 1920x1080 510x287mm 23.0-inch     | 1        | 0.93%   |
| Samsung Electronics LF24T450F SAM7094 1920x1080 527x296mm 23.8-inch   | 1        | 0.93%   |
| Samsung Electronics LCD Monitor SyncMaster                            | 1        | 0.93%   |
| Samsung Electronics LCD Monitor SAM03D4 1280x720                      | 1        | 0.93%   |
| Plain Tree Systems 782 PTS1017 1280x1024 337x270mm 17.0-inch          | 1        | 0.93%   |
| Philips PHL 246V5 PHLC0C5 1920x1080 531x299mm 24.0-inch               | 1        | 0.93%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 1        | 0.93%   |
| Philips 227E4Q PHLC0A9 1920x1080 477x268mm 21.5-inch                  | 1        | 0.93%   |
| Philips 220VW PHL0853 1680x1050 474x296mm 22.0-inch                   | 1        | 0.93%   |
| Philips 220S4L PHL08BE 1680x1050 474x296mm 22.0-inch                  | 1        | 0.93%   |
| Philips 206VL PHLC08C 1600x900 443x249mm 20.0-inch                    | 1        | 0.93%   |
| Philips 200WB PHL0842 1680x1050 433x271mm 20.1-inch                   | 1        | 0.93%   |
| NEC Computers LCD Monitor LCD22WV 1680x1050                           | 1        | 0.93%   |
| NEC Computers LCD Monitor LCD1770NX                                   | 1        | 0.93%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 30       | 30%     |
| 1280x1024 (SXGA)   | 14       | 14%     |
| 2560x1440 (QHD)    | 9        | 9%      |
| 1680x1050 (WSXGA+) | 9        | 9%      |
| 3840x2160 (4K)     | 8        | 8%      |
| 1440x900 (WXGA+)   | 7        | 7%      |
| 2560x1080          | 5        | 5%      |
| Unknown            | 4        | 4%      |
| 1600x900 (HD+)     | 3        | 3%      |
| 4480x1440          | 2        | 2%      |
| 1920x1200 (WUXGA)  | 2        | 2%      |
| 1024x768 (XGA)     | 2        | 2%      |
| 3840x1080          | 1        | 1%      |
| 3520x1200          | 1        | 1%      |
| 2960x1050          | 1        | 1%      |
| 1360x768           | 1        | 1%      |
| 1280x960           | 1        | 1%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 14       | 14.29%  |
| 27      | 13       | 13.27%  |
| 24      | 13       | 13.27%  |
| 23      | 10       | 10.2%   |
| 19      | 10       | 10.2%   |
| 17      | 8        | 8.16%   |
| 22      | 6        | 6.12%   |
| 34      | 5        | 5.1%    |
| 20      | 5        | 5.1%    |
| 25      | 4        | 4.08%   |
| 21      | 4        | 4.08%   |
| 18      | 3        | 3.06%   |
| 15      | 2        | 2.04%   |
| 33      | 1        | 1.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 34       | 36.56%  |
| 401-500     | 20       | 21.51%  |
| Unknown     | 14       | 15.05%  |
| 301-350     | 10       | 10.75%  |
| 351-400     | 7        | 7.53%   |
| 701-800     | 6        | 6.45%   |
| 601-700     | 2        | 2.15%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 40       | 43.48%  |
| 16/10   | 17       | 18.48%  |
| 5/4     | 15       | 16.3%   |
| Unknown | 13       | 14.13%  |
| 21/9    | 5        | 5.43%   |
| 4/3     | 2        | 2.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 30       | 31.25%  |
| 151-200        | 18       | 18.75%  |
| Unknown        | 14       | 14.58%  |
| 301-350        | 13       | 13.54%  |
| 141-150        | 8        | 8.33%   |
| 351-500        | 6        | 6.25%   |
| 251-300        | 5        | 5.21%   |
| 101-110        | 2        | 2.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 62       | 65.96%  |
| Unknown | 14       | 14.89%  |
| 101-120 | 11       | 11.7%   |
| 121-160 | 4        | 4.26%   |
| 161-240 | 3        | 3.19%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 89       | 87.25%  |
| 2     | 9        | 8.82%   |
| 0     | 3        | 2.94%   |
| 3     | 1        | 0.98%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 56       | 42.11%  |
| Intel                             | 31       | 23.31%  |
| Qualcomm Atheros                  | 8        | 6.02%   |
| Broadcom                          | 6        | 4.51%   |
| TP-Link                           | 4        | 3.01%   |
| Ralink Technology                 | 4        | 3.01%   |
| Ralink                            | 4        | 3.01%   |
| Nvidia                            | 4        | 3.01%   |
| Qualcomm Atheros Communications   | 2        | 1.5%    |
| Marvell Technology Group          | 2        | 1.5%    |
| Broadcom Limited                  | 2        | 1.5%    |
| ASIX Electronics                  | 2        | 1.5%    |
| Xiaomi                            | 1        | 0.75%   |
| Wilocity                          | 1        | 0.75%   |
| vivo                              | 1        | 0.75%   |
| Sundance Technology Inc / IC Plus | 1        | 0.75%   |
| Silicon Integrated Systems [SiS]  | 1        | 0.75%   |
| Samsung Electronics               | 1        | 0.75%   |
| Aquantia                          | 1        | 0.75%   |
| 3Com                              | 1        | 0.75%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 46       | 31.08%  |
| Realtek RTL8125 2.5GbE Controller                                          | 6        | 4.05%   |
| Intel I211 Gigabit Network Connection                                      | 5        | 3.38%   |
| Intel Ethernet Connection I217-LM                                          | 4        | 2.7%    |
| Intel Ethernet Connection (2) I219-V                                       | 4        | 2.7%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 3        | 2.03%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 3        | 2.03%   |
| Nvidia MCP61 Ethernet                                                      | 3        | 2.03%   |
| Intel Wi-Fi 6 AX200                                                        | 3        | 2.03%   |
| Intel Ethernet Connection I217-V                                           | 3        | 2.03%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                | 2        | 1.35%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 2        | 1.35%   |
| Ralink RT5370 Wireless Adapter                                             | 2        | 1.35%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                  | 2        | 1.35%   |
| Qualcomm Atheros AR9271 802.11n                                            | 2        | 1.35%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                    | 2        | 1.35%   |
| Intel Wireless 8260                                                        | 2        | 1.35%   |
| Intel Ethernet Connection (7) I219-V                                       | 2        | 1.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 2        | 1.35%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express                    | 2        | 1.35%   |
| ASIX AX88772B                                                              | 2        | 1.35%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 1        | 0.68%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                         | 1        | 0.68%   |
| vivo 1820                                                                  | 1        | 0.68%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                        | 1        | 0.68%   |
| TP-Link 802.11ac WLAN Adapter                                              | 1        | 0.68%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.68%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter              | 1        | 0.68%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 1        | 0.68%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                   | 1        | 0.68%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                            | 1        | 0.68%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                 | 1        | 0.68%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                     | 1        | 0.68%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                      | 1        | 0.68%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 1        | 0.68%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 1        | 0.68%   |
| Ralink RT2870/RT3070 Wireless Adapter                                      | 1        | 0.68%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                          | 1        | 0.68%   |
| Ralink MT7601U Wireless Adapter                                            | 1        | 0.68%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                  | 1        | 0.68%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 9        | 25.71%  |
| Realtek Semiconductor           | 6        | 17.14%  |
| TP-Link                         | 4        | 11.43%  |
| Ralink Technology               | 4        | 11.43%  |
| Ralink                          | 4        | 11.43%  |
| Qualcomm Atheros Communications | 2        | 5.71%   |
| Qualcomm Atheros                | 2        | 5.71%   |
| Broadcom                        | 2        | 5.71%   |
| Wilocity                        | 1        | 2.86%   |
| Broadcom Limited                | 1        | 2.86%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                        | 3        | 8.33%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                | 2        | 5.56%   |
| Ralink RT5370 Wireless Adapter                             | 2        | 5.56%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                  | 2        | 5.56%   |
| Qualcomm Atheros AR9271 802.11n                            | 2        | 5.56%   |
| Intel Wireless 8260                                        | 2        | 5.56%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter         | 1        | 2.78%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                        | 1        | 2.78%   |
| TP-Link 802.11ac WLAN Adapter                              | 1        | 2.78%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter   | 1        | 2.78%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter            | 1        | 2.78%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                 | 1        | 2.78%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                     | 1        | 2.78%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter      | 1        | 2.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 1        | 2.78%   |
| Ralink RT2870/RT3070 Wireless Adapter                      | 1        | 2.78%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter          | 1        | 2.78%   |
| Ralink MT7601U Wireless Adapter                            | 1        | 2.78%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                  | 1        | 2.78%   |
| Ralink RT2561/RT61 rev B 802.11g                           | 1        | 2.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 1        | 2.78%   |
| Qualcomm Atheros AR922X Wireless Network Adapter           | 1        | 2.78%   |
| Intel Wireless-AC 9260                                     | 1        | 2.78%   |
| Intel Wireless 7265                                        | 1        | 2.78%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 1        | 2.78%   |
| Intel Cannon Lake PCH CNVi WiFi                            | 1        | 2.78%   |
| Broadcom Network controller                                | 1        | 2.78%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter | 1        | 2.78%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter         | 1        | 2.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 53       | 50.48%  |
| Intel                             | 26       | 24.76%  |
| Qualcomm Atheros                  | 6        | 5.71%   |
| Nvidia                            | 4        | 3.81%   |
| Broadcom                          | 4        | 3.81%   |
| Marvell Technology Group          | 2        | 1.9%    |
| ASIX Electronics                  | 2        | 1.9%    |
| Xiaomi                            | 1        | 0.95%   |
| vivo                              | 1        | 0.95%   |
| Sundance Technology Inc / IC Plus | 1        | 0.95%   |
| Silicon Integrated Systems [SiS]  | 1        | 0.95%   |
| Samsung Electronics               | 1        | 0.95%   |
| Broadcom Limited                  | 1        | 0.95%   |
| Aquantia                          | 1        | 0.95%   |
| 3Com                              | 1        | 0.95%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 46       | 41.07%  |
| Realtek RTL8125 2.5GbE Controller                                          | 6        | 5.36%   |
| Intel I211 Gigabit Network Connection                                      | 5        | 4.46%   |
| Intel Ethernet Connection I217-LM                                          | 4        | 3.57%   |
| Intel Ethernet Connection (2) I219-V                                       | 4        | 3.57%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 3        | 2.68%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 3        | 2.68%   |
| Nvidia MCP61 Ethernet                                                      | 3        | 2.68%   |
| Intel Ethernet Connection I217-V                                           | 3        | 2.68%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 2        | 1.79%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                    | 2        | 1.79%   |
| Intel Ethernet Connection (7) I219-V                                       | 2        | 1.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 2        | 1.79%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express                    | 2        | 1.79%   |
| ASIX AX88772B                                                              | 2        | 1.79%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 1        | 0.89%   |
| vivo 1820                                                                  | 1        | 0.89%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.89%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter              | 1        | 0.89%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 1        | 0.89%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 1        | 0.89%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                  | 1        | 0.89%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 1        | 0.89%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                   | 1        | 0.89%   |
| Nvidia MCP67 Ethernet                                                      | 1        | 0.89%   |
| Intel 82579V Gigabit Network Connection                                    | 1        | 0.89%   |
| Intel 82578DM Gigabit Network Connection                                   | 1        | 0.89%   |
| Intel 82574L Gigabit Network Connection                                    | 1        | 0.89%   |
| Intel 82573E Gigabit Ethernet Controller (Copper)                          | 1        | 0.89%   |
| Intel 82567V-2 Gigabit Network Connection                                  | 1        | 0.89%   |
| Intel 82567LF-3 Gigabit Network Connection                                 | 1        | 0.89%   |
| Intel 82566DM-2 Gigabit Network Connection                                 | 1        | 0.89%   |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller              | 1        | 0.89%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                    | 1        | 0.89%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                            | 1        | 0.89%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express            | 1        | 0.89%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]          | 1        | 0.89%   |
| 3Com 3c940 10/100/1000Base-T [Marvell]                                     | 1        | 0.89%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 99       | 75%     |
| WiFi     | 33       | 25%     |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 82       | 79.61%  |
| WiFi     | 21       | 20.39%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 70       | 70%     |
| 2     | 24       | 24%     |
| 3     | 4        | 4%      |
| 0     | 2        | 2%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 98       | 98%     |
| Yes  | 2        | 2%      |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 9        | 45%     |
| Cambridge Silicon Radio | 6        | 30%     |
| Realtek Semiconductor   | 2        | 10%     |
| ASUSTek Computer        | 2        | 10%     |
| Apple                   | 1        | 5%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6        | 30%     |
| Intel Bluetooth wireless interface                  | 3        | 15%     |
| Intel AX200 Bluetooth                               | 3        | 15%     |
| Realtek Bluetooth Radio                             | 2        | 10%     |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 5%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 5%      |
| Intel AX210 Bluetooth                               | 1        | 5%      |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 5%      |
| ASUS Bluetooth Device                               | 1        | 5%      |
| Apple Bluetooth USB Host Controller                 | 1        | 5%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 64       | 38.1%   |
| AMD                              | 41       | 24.4%   |
| Nvidia                           | 40       | 23.81%  |
| C-Media Electronics              | 5        | 2.98%   |
| Yamaha                           | 2        | 1.19%   |
| Focusrite-Novation               | 2        | 1.19%   |
| Creative Technology              | 2        | 1.19%   |
| Creative Labs                    | 2        | 1.19%   |
| Texas Instruments                | 1        | 0.6%    |
| Syntek                           | 1        | 0.6%    |
| SteelSeries ApS                  | 1        | 0.6%    |
| Silicon Integrated Systems [SiS] | 1        | 0.6%    |
| RODE Microphones                 | 1        | 0.6%    |
| Realtek Semiconductor            | 1        | 0.6%    |
| Logitech                         | 1        | 0.6%    |
| JMTek                            | 1        | 0.6%    |
| FIFINE 683 Microphone            | 1        | 0.6%    |
| ASRock                           | 1        | 0.6%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 12       | 6.22%   |
| AMD Starship/Matisse HD Audio Controller                                   | 12       | 6.22%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 8        | 4.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 7        | 3.63%   |
| Nvidia TU116 High Definition Audio Controller                              | 6        | 3.11%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 6        | 3.11%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6        | 3.11%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5        | 2.59%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5        | 2.59%   |
| AMD FCH Azalia Controller                                                  | 5        | 2.59%   |
| Nvidia MCP61 High Definition Audio                                         | 4        | 2.07%   |
| Intel Cannon Lake PCH cAVS                                                 | 4        | 2.07%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4        | 2.07%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 4        | 2.07%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 4        | 2.07%   |
| Nvidia GP106 High Definition Audio Controller                              | 3        | 1.55%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 3        | 1.55%   |
| Intel 200 Series PCH HD Audio                                              | 3        | 1.55%   |
| Yamaha Steinberg UR22mkII                                                  | 2        | 1.04%   |
| Nvidia TU106 High Definition Audio Controller                              | 2        | 1.04%   |
| Nvidia TU104 HD Audio Controller                                           | 2        | 1.04%   |
| Nvidia High Definition Audio Controller                                    | 2        | 1.04%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 1.04%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2        | 1.04%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2        | 1.04%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2        | 1.04%   |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 1.04%   |
| Nvidia GF106 High Definition Audio Controller                              | 2        | 1.04%   |
| Nvidia GA104 High Definition Audio Controller                              | 2        | 1.04%   |
| Nvidia GA102 High Definition Audio Controller                              | 2        | 1.04%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2        | 1.04%   |
| Intel 82801G (ICH7 Family) AC'97 Audio Controller                          | 2        | 1.04%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2        | 1.04%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 1.04%   |
| C-Media Electronics MDB-USB                                                | 2        | 1.04%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 2        | 1.04%   |
| AMD Trinity HDMI Audio Controller                                          | 2        | 1.04%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                         | 2        | 1.04%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 2        | 1.04%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2        | 1.04%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 18       | 28.57%  |
| Kingston            | 16       | 25.4%   |
| Crucial             | 9        | 14.29%  |
| Corsair             | 6        | 9.52%   |
| G.Skill             | 5        | 7.94%   |
| SK hynix            | 2        | 3.17%   |
| Micron Technology   | 2        | 3.17%   |
| Team                | 1        | 1.59%   |
| Samsung Electronics | 1        | 1.59%   |
| Ramos Technology    | 1        | 1.59%   |
| A-DATA Technology   | 1        | 1.59%   |
| Unknown             | 1        | 1.59%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                | 2        | 2.56%   |
| Unknown RAM Module 2048MB DIMM SDRAM                    | 2        | 2.56%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                  | 2        | 2.56%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                  | 2        | 2.56%   |
| Kingston RAM KHX3466C16D4/16GX 16GB DIMM DDR4 3466MT/s  | 2        | 2.56%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s     | 2        | 2.56%   |
| Kingston RAM KHX1600C10D3/8GX 8GB DIMM DDR3 1600MT/s    | 2        | 2.56%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 1        | 1.28%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                    | 1        | 1.28%   |
| Unknown RAM Module 4096MB DIMM DDR3 667MT/s             | 1        | 1.28%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s            | 1        | 1.28%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                 | 1        | 1.28%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                | 1        | 1.28%   |
| Unknown RAM Module 2048MB DIMM SDRAM 1333MT/s           | 1        | 1.28%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s             | 1        | 1.28%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                  | 1        | 1.28%   |
| Unknown RAM Module 2048MB DIMM 1066MT/s                 | 1        | 1.28%   |
| Unknown RAM Module 2048MB DIMM                          | 1        | 1.28%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                | 1        | 1.28%   |
| Unknown RAM Module 1024MB DIMM SDRAM                    | 1        | 1.28%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s             | 1        | 1.28%   |
| Unknown RAM Module 1024MB DIMM DDR 667MT/s              | 1        | 1.28%   |
| Unknown RAM Module 1024MB DIMM DDR 533MT/s              | 1        | 1.28%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                  | 1        | 1.28%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s      | 1        | 1.28%   |
| SK hynix RAM HYMP564U64CP8-Y5 512MB DIMM DDR2 667MT/s   | 1        | 1.28%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s    | 1        | 1.28%   |
| Samsung RAM M3 78T2863QZS-CE6 1GB DIMM DDR2 1639MT/s    | 1        | 1.28%   |
| Ramos RAM RMB2GE484CA5-13HC 2048MB DIMM 533MT/s         | 1        | 1.28%   |
| Micron RAM 8JTF25664AZ-1G6M1 2GB DIMM DDR3 1600MT/s     | 1        | 1.28%   |
| Micron RAM 8HTF12864AY-667E1 1024MB DIMM DDR2 667MT/s   | 1        | 1.28%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s  | 1        | 1.28%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s | 1        | 1.28%   |
| Kingston RAM KHX2133C11D3/4GX 4GB DIMM DDR3 2134MT/s    | 1        | 1.28%   |
| Kingston RAM KHX1600C9D3/8GX 8GB DIMM DDR3 2133MT/s     | 1        | 1.28%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s     | 1        | 1.28%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s     | 1        | 1.28%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3              | 1        | 1.28%   |
| Kingston RAM KF3600C16D4/8GX 8GB DIMM DDR4 3600MT/s     | 1        | 1.28%   |
| Kingston RAM HX316C10F/4 4GB DIMM DDR3 1600MT/s         | 1        | 1.28%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 18       | 33.33%  |
| DDR4    | 17       | 31.48%  |
| Unknown | 8        | 14.81%  |
| DDR2    | 5        | 9.26%   |
| SDRAM   | 4        | 7.41%   |
| DDR     | 2        | 3.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 52       | 98.11%  |
| SODIMM | 1        | 1.89%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 16       | 24.62%  |
| 2048  | 16       | 24.62%  |
| 8192  | 15       | 23.08%  |
| 1024  | 8        | 12.31%  |
| 16384 | 6        | 9.23%   |
| 32768 | 3        | 4.62%   |
| 512   | 1        | 1.54%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 10       | 14.71%  |
| 667     | 9        | 13.24%  |
| 1333    | 7        | 10.29%  |
| 2133    | 6        | 8.82%   |
| 3200    | 4        | 5.88%   |
| 800     | 4        | 5.88%   |
| Unknown | 3        | 4.41%   |
| 3600    | 2        | 2.94%   |
| 3466    | 2        | 2.94%   |
| 3000    | 2        | 2.94%   |
| 2667    | 2        | 2.94%   |
| 2400    | 2        | 2.94%   |
| 1867    | 2        | 2.94%   |
| 1800    | 2        | 2.94%   |
| 1066    | 2        | 2.94%   |
| 533     | 2        | 2.94%   |
| 3866    | 1        | 1.47%   |
| 3800    | 1        | 1.47%   |
| 3533    | 1        | 1.47%   |
| 2448    | 1        | 1.47%   |
| 2134    | 1        | 1.47%   |
| 1866    | 1        | 1.47%   |
| 1639    | 1        | 1.47%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 3        | 42.86%  |
| Seiko Epson         | 1        | 14.29%  |
| Samsung Electronics | 1        | 14.29%  |
| Canon               | 1        | 14.29%  |
| Brother Industries  | 1        | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Desktops | Percent |
|---------------------------|----------|---------|
| Seiko Epson L3110 Series  | 1        | 14.29%  |
| Samsung SCX-4216F Scanner | 1        | 14.29%  |
| HP Officejet 4500 G510g-m | 1        | 14.29%  |
| HP LaserJet 1010          | 1        | 14.29%  |
| HP DeskJet 5940           | 1        | 14.29%  |
| Canon PIXMA MG3000 series | 1        | 14.29%  |
| Brother DCP-L2510D series | 1        | 14.29%  |

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
| Logitech                    | 11       | 42.31%  |
| Z-Star Microelectronics     | 3        | 11.54%  |
| Apple                       | 2        | 7.69%   |
| Tobii Technology AB         | 1        | 3.85%   |
| Samsung Electronics         | 1        | 3.85%   |
| Razer USA                   | 1        | 3.85%   |
| Pixart Imaging              | 1        | 3.85%   |
| Microdia                    | 1        | 3.85%   |
| KYE Systems (Mouse Systems) | 1        | 3.85%   |
| Genesys Logic               | 1        | 3.85%   |
| GEMBIRD                     | 1        | 3.85%   |
| Cubeternet                  | 1        | 3.85%   |
| Chicony Electronics         | 1        | 3.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Logitech Webcam C270                        | 3        | 11.54%  |
| Z-Star A4 TECH HD PC Camera                 | 2        | 7.69%   |
| Logitech Webcam C170                        | 2        | 7.69%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X             | 2        | 7.69%   |
| Z-Star Vega USB 2.0 Camera                  | 1        | 3.85%   |
| Tobii AB EyeChip                            | 1        | 3.85%   |
| Samsung Galaxy series, misc. (MTP mode)     | 1        | 3.85%   |
| Razer USA Gaming Webcam [Kiyo]              | 1        | 3.85%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro        | 1        | 3.85%   |
| Microdia Defender G-Lens 2577 HD720p Camera | 1        | 3.85%   |
| Logitech Webcam C310                        | 1        | 3.85%   |
| Logitech Webcam C250                        | 1        | 3.85%   |
| Logitech Webcam C210                        | 1        | 3.85%   |
| Logitech QuickCam Pro 9000                  | 1        | 3.85%   |
| Logitech HD Webcam C525                     | 1        | 3.85%   |
| Logitech HD Webcam C510                     | 1        | 3.85%   |
| KYE Systems (Mouse Systems) eFace 2050AF    | 1        | 3.85%   |
| Genesys Logic Camera                        | 1        | 3.85%   |
| GEMBIRD USB2.0 PC CAMERA                    | 1        | 3.85%   |
| Cubeternet USB2.0 Camera                    | 1        | 3.85%   |
| Chicony HP High Definition Webcam           | 1        | 3.85%   |

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
| 0     | 90       | 89.11%  |
| 1     | 10       | 9.9%    |
| 2     | 1        | 0.99%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 5        | 41.67%  |
| Net/wireless             | 2        | 16.67%  |
| Communication controller | 2        | 16.67%  |
| Storage/raid             | 1        | 8.33%   |
| Net/ethernet             | 1        | 8.33%   |
| Chipcard                 | 1        | 8.33%   |

