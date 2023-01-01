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

Total: 139

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 6        | 6.12%   |
| Ubuntu 18.04                 | 6        | 6.12%   |
| ROSA R10                     | 6        | 6.12%   |
| ROSA R11                     | 5        | 5.1%    |
| KDE neon 20.04               | 5        | 5.1%    |
| Linux Mint 20.1              | 4        | 4.08%   |
| Ubuntu 22.04                 | 3        | 3.06%   |
| ROSA R9                      | 3        | 3.06%   |
| Linux Mint 20.2              | 3        | 3.06%   |
| Arch Rolling                 | 3        | 3.06%   |
| Xubuntu 20.04                | 2        | 2.04%   |
| ROSA R8.1                    | 2        | 2.04%   |
| ROSA 12.2                    | 2        | 2.04%   |
| OpenMandriva 4.50            | 2        | 2.04%   |
| OpenMandriva 4.2             | 2        | 2.04%   |
| Linux Mint 20.3              | 2        | 2.04%   |
| Linux Mint 19.3              | 2        | 2.04%   |
| Fedora 35                    | 2        | 2.04%   |
| Fedora 30                    | 2        | 2.04%   |
| Debian Testing               | 2        | 2.04%   |
| Zorin 16                     | 1        | 1.02%   |
| Xubuntu 18.04                | 1        | 1.02%   |
| Ubuntu 19.10                 | 1        | 1.02%   |
| Ubuntu 16.04                 | 1        | 1.02%   |
| SteamOS 3.4                  | 1        | 1.02%   |
| SteamOS 3.3                  | 1        | 1.02%   |
| ROSA R8                      | 1        | 1.02%   |
| ROSA R11.1                   | 1        | 1.02%   |
| Puppy 9                      | 1        | 1.02%   |
| Pop!_OS 21.04                | 1        | 1.02%   |
| openSUSE Tumbleweed-XXXXXXXX | 1        | 1.02%   |
| Manjaro 20.2.1               | 1        | 1.02%   |
| Manjaro                      | 1        | 1.02%   |
| Lubuntu 22.04                | 1        | 1.02%   |
| Lubuntu 21.10                | 1        | 1.02%   |
| LMDE 5                       | 1        | 1.02%   |
| Linux Mint 20                | 1        | 1.02%   |
| Linux Mint 19.1              | 1        | 1.02%   |
| Linux Mint 19                | 1        | 1.02%   |
| Linux Mint 18.2              | 1        | 1.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| ROSA         | 18       | 20%     |
| Ubuntu       | 17       | 18.89%  |
| Linux Mint   | 13       | 14.44%  |
| Fedora       | 6        | 6.67%   |
| KDE neon     | 5        | 5.56%   |
| OpenMandriva | 4        | 4.44%   |
| Arch         | 4        | 4.44%   |
| Xubuntu      | 3        | 3.33%   |
| Manjaro      | 2        | 2.22%   |
| Kubuntu      | 2        | 2.22%   |
| Garuda Linux | 2        | 2.22%   |
| Debian       | 2        | 2.22%   |
| Clear Linux  | 2        | 2.22%   |
| Zorin        | 1        | 1.11%   |
| SteamOS      | 1        | 1.11%   |
| Puppy        | 1        | 1.11%   |
| Pop!_OS      | 1        | 1.11%   |
| openSUSE     | 1        | 1.11%   |
| Lubuntu      | 1        | 1.11%   |
| LMDE         | 1        | 1.11%   |
| Kali         | 1        | 1.11%   |
| Endless      | 1        | 1.11%   |
| EndeavourOS  | 1        | 1.11%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Desktops | Percent |
|---------------------------------|----------|---------|
| 4.9.60-nrj-desktop-1rosa-x86_64 | 5        | 4.72%   |
| 5.4.0-58-generic                | 4        | 3.77%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 4        | 3.77%   |
| 5.4.0-132-generic               | 3        | 2.83%   |
| 5.4.0-122-generic               | 3        | 2.83%   |
| 4.15.0-desktop-45.1rosa-x86_64  | 3        | 2.83%   |
| 5.4.0-66-generic                | 2        | 1.89%   |
| 5.4.0-54-generic                | 2        | 1.89%   |
| 5.13.0-39-generic               | 2        | 1.89%   |
| 5.12.4-desktop-1omv4050         | 2        | 1.89%   |
| 5.10.14-desktop-1omv4002        | 2        | 1.89%   |
| 5.0.0-37-generic                | 2        | 1.89%   |
| 6.0.7-1-default                 | 1        | 0.94%   |
| 6.0.13-300.fc37.x86_64          | 1        | 0.94%   |
| 6.0.11-AMD-znver2               | 1        | 0.94%   |
| 5.9.13-1006.native              | 1        | 0.94%   |
| 5.9.0-kali1-amd64               | 1        | 0.94%   |
| 5.8.12-arch1-1                  | 1        | 0.94%   |
| 5.8.0-50-generic                | 1        | 0.94%   |
| 5.8.0-44-generic                | 1        | 0.94%   |
| 5.8.0-25-generic                | 1        | 0.94%   |
| 5.6.3-arch1-1                   | 1        | 0.94%   |
| 5.4.83-generic-2rosa-x86_64     | 1        | 0.94%   |
| 5.4.53                          | 1        | 0.94%   |
| 5.4.18-902.native               | 1        | 0.94%   |
| 5.4.0-80-generic                | 1        | 0.94%   |
| 5.4.0-70-generic                | 1        | 0.94%   |
| 5.4.0-67-generic                | 1        | 0.94%   |
| 5.4.0-62-generic                | 1        | 0.94%   |
| 5.4.0-59-generic                | 1        | 0.94%   |
| 5.4.0-52-generic                | 1        | 0.94%   |
| 5.4.0-48-generic                | 1        | 0.94%   |
| 5.4.0-42-generic                | 1        | 0.94%   |
| 5.4.0-121-generic               | 1        | 0.94%   |
| 5.4.0-100-generic               | 1        | 0.94%   |
| 5.3.0-53-generic                | 1        | 0.94%   |
| 5.3.0-42-generic                | 1        | 0.94%   |
| 5.3.0-28-generic                | 1        | 0.94%   |
| 5.3.0-23-generic                | 1        | 0.94%   |
| 5.2.9-200.fc30.x86_64           | 1        | 0.94%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.4.0    | 18       | 18.37%  |
| 4.15.0   | 10       | 10.2%   |
| 5.15.0   | 5        | 5.1%    |
| 5.13.0   | 5        | 5.1%    |
| 4.9.60   | 5        | 5.1%    |
| 4.9.20   | 5        | 5.1%    |
| 5.3.0    | 4        | 4.08%   |
| 5.8.0    | 3        | 3.06%   |
| 5.11.0   | 3        | 3.06%   |
| 5.12.4   | 2        | 2.04%   |
| 5.10.14  | 2        | 2.04%   |
| 5.0.0    | 2        | 2.04%   |
| 6.0.7    | 1        | 1.02%   |
| 6.0.13   | 1        | 1.02%   |
| 6.0.11   | 1        | 1.02%   |
| 5.9.13   | 1        | 1.02%   |
| 5.9.0    | 1        | 1.02%   |
| 5.8.12   | 1        | 1.02%   |
| 5.6.3    | 1        | 1.02%   |
| 5.4.83   | 1        | 1.02%   |
| 5.4.53   | 1        | 1.02%   |
| 5.4.18   | 1        | 1.02%   |
| 5.2.9    | 1        | 1.02%   |
| 5.2.14   | 1        | 1.02%   |
| 5.19.10  | 1        | 1.02%   |
| 5.19.0   | 1        | 1.02%   |
| 5.18.1   | 1        | 1.02%   |
| 5.17.5   | 1        | 1.02%   |
| 5.17.0   | 1        | 1.02%   |
| 5.16.18  | 1        | 1.02%   |
| 5.16.15  | 1        | 1.02%   |
| 5.14.0   | 1        | 1.02%   |
| 5.13.19  | 1        | 1.02%   |
| 5.11.6   | 1        | 1.02%   |
| 5.11.22  | 1        | 1.02%   |
| 5.11.2   | 1        | 1.02%   |
| 5.11.11  | 1        | 1.02%   |
| 5.10.74  | 1        | 1.02%   |
| 5.10.16  | 1        | 1.02%   |
| 5.10.118 | 1        | 1.02%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 21       | 21.65%  |
| 4.9     | 11       | 11.34%  |
| 4.15    | 10       | 10.31%  |
| 5.11    | 7        | 7.22%   |
| 5.13    | 6        | 6.19%   |
| 5.10    | 6        | 6.19%   |
| 5.15    | 5        | 5.15%   |
| 5.8     | 4        | 4.12%   |
| 5.3     | 4        | 4.12%   |
| 6.0     | 3        | 3.09%   |
| 5.9     | 2        | 2.06%   |
| 5.2     | 2        | 2.06%   |
| 5.19    | 2        | 2.06%   |
| 5.17    | 2        | 2.06%   |
| 5.16    | 2        | 2.06%   |
| 5.12    | 2        | 2.06%   |
| 5.0     | 2        | 2.06%   |
| 5.6     | 1        | 1.03%   |
| 5.18    | 1        | 1.03%   |
| 5.14    | 1        | 1.03%   |
| 4.8     | 1        | 1.03%   |
| 4.18    | 1        | 1.03%   |
| 4.1     | 1        | 1.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 81       | 95.29%  |
| i686   | 4        | 4.71%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 25       | 26.88%  |
| KDE5       | 20       | 21.51%  |
| KDE4       | 10       | 10.75%  |
| Unknown    | 10       | 10.75%  |
| X-Cinnamon | 8        | 8.6%    |
| XFCE       | 5        | 5.38%   |
| MATE       | 5        | 5.38%   |
| KDE        | 5        | 5.38%   |
| Deepin     | 2        | 2.15%   |
| Cinnamon   | 2        | 2.15%   |
| LXQt       | 1        | 1.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 72       | 83.72%  |
| Wayland | 10       | 11.63%  |
| Unknown | 3        | 3.49%   |
| Tty     | 1        | 1.16%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 43       | 45.74%  |
| SDDM    | 19       | 20.21%  |
| KDM     | 10       | 10.64%  |
| GDM     | 7        | 7.45%   |
| GDM3    | 6        | 6.38%   |
| LightDM | 5        | 5.32%   |
| TDM     | 4        | 4.26%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| en_US       | 31       | 34.07%  |
| Unknown     | 22       | 24.18%  |
| ru_RU       | 13       | 14.29%  |
| lv_LV       | 12       | 13.19%  |
| en_GB       | 6        | 6.59%   |
| C           | 3        | 3.3%    |
| ru_RU.UTF_8 | 1        | 1.1%    |
| osa_US      | 1        | 1.1%    |
| de_DE       | 1        | 1.1%    |
| cv_RU       | 1        | 1.1%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 60       | 70.59%  |
| EFI  | 25       | 29.41%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 63       | 70%     |
| Unknown | 12       | 13.33%  |
| Btrfs   | 8        | 8.89%   |
| Overlay | 4        | 4.44%   |
| Xfs     | 1        | 1.11%   |
| Ext3    | 1        | 1.11%   |
| Aufs    | 1        | 1.11%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 48       | 53.33%  |
| GPT     | 22       | 24.44%  |
| MBR     | 20       | 22.22%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 76       | 84.44%  |
| Yes       | 14       | 15.56%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 60       | 67.42%  |
| Yes       | 29       | 32.58%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 21       | 24.71%  |
| Gigabyte Technology | 20       | 23.53%  |
| MSI                 | 12       | 14.12%  |
| ASRock              | 8        | 9.41%   |
| Dell                | 6        | 7.06%   |
| Hewlett-Packard     | 4        | 4.71%   |
| Intel               | 3        | 3.53%   |
| Acer                | 3        | 3.53%   |
| Lenovo              | 1        | 1.18%   |
| IBM                 | 1        | 1.18%   |
| Hardkernel          | 1        | 1.18%   |
| Fujitsu Siemens     | 1        | 1.18%   |
| Foxconn             | 1        | 1.18%   |
| Biostar             | 1        | 1.18%   |
| Acidanthera         | 1        | 1.18%   |
| ABIT                | 1        | 1.18%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| ASUS All Series                    | 5        | 5.88%   |
| MSI MS-7721                        | 2        | 2.35%   |
| Gigabyte G33M-S2                   | 2        | 2.35%   |
| Gigabyte B550 AORUS PRO V2         | 2        | 2.35%   |
| Gigabyte 946GMX-S2                 | 2        | 2.35%   |
| Dell OptiPlex 7020                 | 2        | 2.35%   |
| MSI MS-7C52                        | 1        | 1.18%   |
| MSI MS-7B46                        | 1        | 1.18%   |
| MSI MS-7B33                        | 1        | 1.18%   |
| MSI MS-7996                        | 1        | 1.18%   |
| MSI MS-7850                        | 1        | 1.18%   |
| MSI MS-7846                        | 1        | 1.18%   |
| MSI MS-7758                        | 1        | 1.18%   |
| MSI MS-7693                        | 1        | 1.18%   |
| MSI MS-7583                        | 1        | 1.18%   |
| MSI MS-7519                        | 1        | 1.18%   |
| Lenovo Legion T5 26AMR5 90RC018LBX | 1        | 1.18%   |
| Intel DQ87PG AAG74154-403          | 1        | 1.18%   |
| Intel DH77EB AAG39073-304          | 1        | 1.18%   |
| Intel DB85FL AAG89861-201          | 1        | 1.18%   |
| IBM 8215ZCL                        | 1        | 1.18%   |
| HP ProDesk 600 G1 TWR              | 1        | 1.18%   |
| HP Compaq dc5700 Microtower        | 1        | 1.18%   |
| HP Compaq 8100 Elite CMT PC        | 1        | 1.18%   |
| HP 310-1205uk                      | 1        | 1.18%   |
| Hardkernel ODROID-H2               | 1        | 1.18%   |
| Gigabyte Z87P-D3                   | 1        | 1.18%   |
| Gigabyte Z87-HD3                   | 1        | 1.18%   |
| Gigabyte X570 AORUS ELITE          | 1        | 1.18%   |
| Gigabyte M61PME-S2                 | 1        | 1.18%   |
| Gigabyte H97-D3H                   | 1        | 1.18%   |
| Gigabyte H61MA-D2V                 | 1        | 1.18%   |
| Gigabyte H61M-S2-B3                | 1        | 1.18%   |
| Gigabyte H55M-D2H                  | 1        | 1.18%   |
| Gigabyte GA-970A-UD3               | 1        | 1.18%   |
| Gigabyte G41M-ES2L                 | 1        | 1.18%   |
| Gigabyte G31M-ES2L                 | 1        | 1.18%   |
| Gigabyte B550I AORUS PRO AX        | 1        | 1.18%   |
| Gigabyte B450 GAMING X             | 1        | 1.18%   |
| Gigabyte AB350M-DS3H V2            | 1        | 1.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Dell OptiPlex        | 6        | 7.06%   |
| ASUS All             | 5        | 5.88%   |
| ASUS PRIME           | 4        | 4.71%   |
| MSI MS-7721          | 2        | 2.35%   |
| HP Compaq            | 2        | 2.35%   |
| Gigabyte G33M-S2     | 2        | 2.35%   |
| Gigabyte B550        | 2        | 2.35%   |
| Gigabyte 946GMX-S2   | 2        | 2.35%   |
| ASUS P5Q             | 2        | 2.35%   |
| Acer Aspire          | 2        | 2.35%   |
| MSI MS-7C52          | 1        | 1.18%   |
| MSI MS-7B46          | 1        | 1.18%   |
| MSI MS-7B33          | 1        | 1.18%   |
| MSI MS-7996          | 1        | 1.18%   |
| MSI MS-7850          | 1        | 1.18%   |
| MSI MS-7846          | 1        | 1.18%   |
| MSI MS-7758          | 1        | 1.18%   |
| MSI MS-7693          | 1        | 1.18%   |
| MSI MS-7583          | 1        | 1.18%   |
| MSI MS-7519          | 1        | 1.18%   |
| Lenovo Legion        | 1        | 1.18%   |
| Intel DQ87PG         | 1        | 1.18%   |
| Intel DH77EB         | 1        | 1.18%   |
| Intel DB85FL         | 1        | 1.18%   |
| IBM 8215ZCL          | 1        | 1.18%   |
| HP ProDesk           | 1        | 1.18%   |
| HP 310-1205uk        | 1        | 1.18%   |
| Hardkernel ODROID-H2 | 1        | 1.18%   |
| Gigabyte Z87P-D3     | 1        | 1.18%   |
| Gigabyte Z87-HD3     | 1        | 1.18%   |
| Gigabyte X570        | 1        | 1.18%   |
| Gigabyte M61PME-S2   | 1        | 1.18%   |
| Gigabyte H97-D3H     | 1        | 1.18%   |
| Gigabyte H61MA-D2V   | 1        | 1.18%   |
| Gigabyte H61M-S2-B3  | 1        | 1.18%   |
| Gigabyte H55M-D2H    | 1        | 1.18%   |
| Gigabyte GA-970A-UD3 | 1        | 1.18%   |
| Gigabyte G41M-ES2L   | 1        | 1.18%   |
| Gigabyte G31M-ES2L   | 1        | 1.18%   |
| Gigabyte B550I       | 1        | 1.18%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 12       | 14.12%  |
| 2007 | 12       | 14.12%  |
| 2012 | 8        | 9.41%   |
| 2008 | 8        | 9.41%   |
| 2009 | 7        | 8.24%   |
| 2018 | 6        | 7.06%   |
| 2015 | 5        | 5.88%   |
| 2019 | 4        | 4.71%   |
| 2014 | 4        | 4.71%   |
| 2011 | 4        | 4.71%   |
| 2006 | 4        | 4.71%   |
| 2017 | 3        | 3.53%   |
| 2021 | 2        | 2.35%   |
| 2020 | 2        | 2.35%   |
| 2010 | 2        | 2.35%   |
| 2016 | 1        | 1.18%   |
| 2004 | 1        | 1.18%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 85       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 85       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 85       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 3.01-4.0    | 21       | 23.86%  |
| 8.01-16.0   | 17       | 19.32%  |
| 4.01-8.0    | 14       | 15.91%  |
| 32.01-64.0  | 12       | 13.64%  |
| 16.01-24.0  | 11       | 12.5%   |
| 1.01-2.0    | 6        | 6.82%   |
| 24.01-32.0  | 3        | 3.41%   |
| 2.01-3.0    | 3        | 3.41%   |
| 64.01-256.0 | 1        | 1.14%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 34       | 34%     |
| 2.01-3.0   | 21       | 21%     |
| 0.51-1.0   | 19       | 19%     |
| 4.01-8.0   | 12       | 12%     |
| 3.01-4.0   | 10       | 10%     |
| 8.01-16.0  | 3        | 3%      |
| 16.01-24.0 | 1        | 1%      |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 39       | 42.86%  |
| 2      | 23       | 25.27%  |
| 3      | 16       | 17.58%  |
| 4      | 9        | 9.89%   |
| 6      | 2        | 2.2%    |
| 7      | 1        | 1.1%    |
| 5      | 1        | 1.1%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 47       | 54.65%  |
| Yes       | 39       | 45.35%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 84       | 98.82%  |
| No        | 1        | 1.18%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 59       | 68.6%   |
| Yes       | 27       | 31.4%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 72       | 83.72%  |
| Yes       | 14       | 16.28%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Latvia  | 85       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City       | Desktops | Percent |
|------------|----------|---------|
| Riga       | 60       | 67.42%  |
| Ventspils  | 4        | 4.49%   |
| Salaspils  | 3        | 3.37%   |
| Jelgava    | 3        | 3.37%   |
| Talsi      | 2        | 2.25%   |
| Jūrmala   | 2        | 2.25%   |
| Daugavpils | 2        | 2.25%   |
| Adazi      | 2        | 2.25%   |
| Ragana     | 1        | 1.12%   |
| Ogre       | 1        | 1.12%   |
| Limbaži   | 1        | 1.12%   |
| Liepāja   | 1        | 1.12%   |
| Lielvārde | 1        | 1.12%   |
| Kuldīga   | 1        | 1.12%   |
| Iecava     | 1        | 1.12%   |
| Dreilini   | 1        | 1.12%   |
| Carnikava  | 1        | 1.12%   |
| Brankas    | 1        | 1.12%   |
| Bauska     | 1        | 1.12%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| WDC                   | 36       | 58     | 23.38%  |
| Seagate               | 36       | 54     | 23.38%  |
| Samsung Electronics   | 26       | 47     | 16.88%  |
| Kingston              | 12       | 20     | 7.79%   |
| Crucial               | 10       | 17     | 6.49%   |
| Hitachi               | 6        | 8      | 3.9%    |
| Toshiba               | 5        | 6      | 3.25%   |
| Intel                 | 4        | 7      | 2.6%    |
| GOODRAM               | 3        | 6      | 1.95%   |
| OCZ                   | 2        | 3      | 1.3%    |
| Unknown               | 1        | 1      | 0.65%   |
| SPCC                  | 1        | 2      | 0.65%   |
| Silicon Motion        | 1        | 1      | 0.65%   |
| Realtek Semiconductor | 1        | 1      | 0.65%   |
| Patriot               | 1        | 1      | 0.65%   |
| Netac                 | 1        | 1      | 0.65%   |
| Mushkin               | 1        | 2      | 0.65%   |
| Maxtor                | 1        | 1      | 0.65%   |
| KingFast              | 1        | 2      | 0.65%   |
| IBM/Hitachi           | 1        | 1      | 0.65%   |
| HS-SSD-E100           | 1        | 1      | 0.65%   |
| GLOWAY                | 1        | 1      | 0.65%   |
| ADATA Technology      | 1        | 2      | 0.65%   |
| A-DATA Technology     | 1        | 2      | 0.65%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD  | 5        | 2.76%   |
| Seagate ST1000DM010-2EP102 1TB   | 4        | 2.21%   |
| Crucial CT500MX500SSD1 500GB     | 4        | 2.21%   |
| WDC WD2000JD-00HBB0 200GB        | 3        | 1.66%   |
| Seagate ST500DM005 HD502HJ 500GB | 3        | 1.66%   |
| Samsung NVMe SSD Drive 500GB     | 3        | 1.66%   |
| Crucial CT1000MX500SSD1 1TB      | 3        | 1.66%   |
| WDC WD5002AALX-00J37A0 500GB     | 2        | 1.1%    |
| WDC WD5000AAKX-22ERMA0 500GB     | 2        | 1.1%    |
| WDC WD5000AAKX-00ERMA0 500GB     | 2        | 1.1%    |
| WDC WD5000AAKX-001CA0 500GB      | 2        | 1.1%    |
| WDC WD20EARX-00PASB0 2TB         | 2        | 1.1%    |
| WDC WD10EZEX-00BN5A0 1TB         | 2        | 1.1%    |
| Seagate ST3500418AS 500GB        | 2        | 1.1%    |
| Seagate ST3250824AS 250GB        | 2        | 1.1%    |
| Seagate ST250DM000-1BD141 250GB  | 2        | 1.1%    |
| Seagate ST2000DM001-1CH164 2TB   | 2        | 1.1%    |
| Seagate ST1000DX001-1CM162 1TB   | 2        | 1.1%    |
| Seagate ST1000DM003-1SB102 1TB   | 2        | 1.1%    |
| Samsung SSD 970 EVO Plus 500GB   | 2        | 1.1%    |
| Samsung SSD 860 EVO 500GB        | 2        | 1.1%    |
| Samsung SSD 860 EVO 1TB          | 2        | 1.1%    |
| Samsung SSD 650 120GB            | 2        | 1.1%    |
| Samsung SP2504C 250GB            | 2        | 1.1%    |
| Samsung HD501LJ 500GB            | 2        | 1.1%    |
| Samsung HD103UJ 1TB              | 2        | 1.1%    |
| Kingston SV300S37A240G 240GB SSD | 2        | 1.1%    |
| GOODRAM SSDPR-CX400-128-G2 128GB | 2        | 1.1%    |
| Crucial CT480BX500SSD1 480GB     | 2        | 1.1%    |
| WDC WDS500G3X0C-00SJG0 500GB     | 1        | 0.55%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 1        | 0.55%   |
| WDC WDS480G2G0A-00JH30 480GB SSD | 1        | 0.55%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD | 1        | 0.55%   |
| WDC WDS100T2B0C-00PXH0 1TB       | 1        | 0.55%   |
| WDC WDS100T2B0B-00YS70 1TB SSD   | 1        | 0.55%   |
| WDC WDS100T2B0A-00SM50 1TB SSD   | 1        | 0.55%   |
| WDC WD800JD-60MSA1 80GB          | 1        | 0.55%   |
| WDC WD6003FZBX-00K5WB0 6TB       | 1        | 0.55%   |
| WDC WD5001AALS-00E3A0 500GB      | 1        | 0.55%   |
| WDC WD5000AAKX-08U6AA0 500GB     | 1        | 0.55%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 36       | 54     | 39.56%  |
| WDC                 | 31       | 49     | 34.07%  |
| Samsung Electronics | 11       | 16     | 12.09%  |
| Hitachi             | 6        | 8      | 6.59%   |
| Toshiba             | 5        | 6      | 5.49%   |
| Maxtor              | 1        | 1      | 1.1%    |
| IBM/Hitachi         | 1        | 1      | 1.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 12       | 20     | 23.08%  |
| Samsung Electronics | 11       | 18     | 21.15%  |
| Crucial             | 10       | 17     | 19.23%  |
| WDC                 | 5        | 6      | 9.62%   |
| Intel               | 3        | 6      | 5.77%   |
| GOODRAM             | 3        | 6      | 5.77%   |
| OCZ                 | 2        | 3      | 3.85%   |
| SPCC                | 1        | 2      | 1.92%   |
| Patriot             | 1        | 1      | 1.92%   |
| Mushkin             | 1        | 2      | 1.92%   |
| KingFast            | 1        | 2      | 1.92%   |
| GLOWAY              | 1        | 1      | 1.92%   |
| A-DATA Technology   | 1        | 2      | 1.92%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 68       | 135    | 54.84%  |
| SSD     | 40       | 86     | 32.26%  |
| NVMe    | 14       | 22     | 11.29%  |
| MMC     | 1        | 1      | 0.81%   |
| Unknown | 1        | 1      | 0.81%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 82       | 220    | 82.83%  |
| NVMe | 14       | 22     | 14.14%  |
| SAS  | 2        | 2      | 2.02%   |
| MMC  | 1        | 1      | 1.01%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 68       | 145    | 58.62%  |
| 0.51-1.0   | 32       | 51     | 27.59%  |
| 1.01-2.0   | 9        | 17     | 7.76%   |
| 2.01-3.0   | 3        | 4      | 2.59%   |
| 3.01-4.0   | 2        | 2      | 1.72%   |
| 4.01-10.0  | 2        | 2      | 1.72%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 31       | 32.63%  |
| 1001-2000      | 12       | 12.63%  |
| 251-500        | 11       | 11.58%  |
| 501-1000       | 10       | 10.53%  |
| 51-100         | 9        | 9.47%   |
| More than 3000 | 6        | 6.32%   |
| 21-50          | 6        | 6.32%   |
| 2001-3000      | 6        | 6.32%   |
| 1-20           | 3        | 3.16%   |
| Unknown        | 1        | 1.05%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 38       | 37.25%  |
| 101-250        | 15       | 14.71%  |
| 51-100         | 12       | 11.76%  |
| 251-500        | 11       | 10.78%  |
| 21-50          | 11       | 10.78%  |
| 501-1000       | 6        | 5.88%   |
| 1001-2000      | 5        | 4.9%    |
| 2001-3000      | 2        | 1.96%   |
| More than 3000 | 1        | 0.98%   |
| Unknown        | 1        | 0.98%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD20EARX-00PASB0 2TB              | 2        | 4      | 6.67%   |
| WDC WD2000JD-00HBB0 200GB             | 2        | 4      | 6.67%   |
| Seagate ST1000DM003-1SB102 1TB        | 2        | 5      | 6.67%   |
| Samsung Electronics SP2504C 250GB     | 2        | 2      | 6.67%   |
| Samsung Electronics HD501LJ 500GB     | 2        | 5      | 6.67%   |
| WDC WDS500G3X0C-00SJG0 500GB          | 1        | 1      | 3.33%   |
| WDC WD800JD-60MSA1 80GB               | 1        | 1      | 3.33%   |
| WDC WD5002AALX-00J37A0 500GB          | 1        | 1      | 3.33%   |
| WDC WD5001AALS-00E3A0 500GB           | 1        | 1      | 3.33%   |
| WDC WD2500AAKS-60L9A0 250GB           | 1        | 1      | 3.33%   |
| WDC WD1600AAJS-00B4A0 160GB           | 1        | 1      | 3.33%   |
| Toshiba DT01ACA100 1TB                | 1        | 1      | 3.33%   |
| Seagate ST3500820AS 500GB             | 1        | 1      | 3.33%   |
| Seagate ST3500413AS 500GB             | 1        | 1      | 3.33%   |
| Seagate ST3500312CS 500GB             | 1        | 1      | 3.33%   |
| Seagate ST340016A 40GB                | 1        | 1      | 3.33%   |
| Seagate ST3250620AS 250GB             | 1        | 1      | 3.33%   |
| Seagate ST3250312AS 250GB             | 1        | 1      | 3.33%   |
| Seagate ST31000528AS 1TB              | 1        | 1      | 3.33%   |
| Seagate ST3000DM001-9YN166 3TB        | 1        | 1      | 3.33%   |
| Seagate ST1000DX001-1CM162 1TB        | 1        | 1      | 3.33%   |
| Samsung Electronics SSD 970 EVO 500GB | 1        | 1      | 3.33%   |
| Kingston SV300S37A60G 64GB SSD        | 1        | 1      | 3.33%   |
| Hitachi HTS542525K9A300 250GB         | 1        | 1      | 3.33%   |
| A-DATA Technology SU800NS38 512GB SSD | 1        | 2      | 3.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 10       | 14     | 35.71%  |
| WDC                 | 9        | 14     | 32.14%  |
| Samsung Electronics | 5        | 8      | 17.86%  |
| Toshiba             | 1        | 1      | 3.57%   |
| Kingston            | 1        | 1      | 3.57%   |
| Hitachi             | 1        | 1      | 3.57%   |
| A-DATA Technology   | 1        | 2      | 3.57%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 10       | 14     | 41.67%  |
| WDC                 | 8        | 13     | 33.33%  |
| Samsung Electronics | 4        | 7      | 16.67%  |
| Toshiba             | 1        | 1      | 4.17%   |
| Hitachi             | 1        | 1      | 4.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 17       | 36     | 80.95%  |
| NVMe | 2        | 2      | 9.52%   |
| SSD  | 2        | 3      | 9.52%   |

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
| Detected | 49       | 114    | 46.67%  |
| Works    | 36       | 90     | 34.29%  |
| Malfunc  | 20       | 41     | 19.05%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 58       | 52.25%  |
| AMD                              | 21       | 18.92%  |
| Samsung Electronics              | 9        | 8.11%   |
| JMicron Technology               | 7        | 6.31%   |
| Nvidia                           | 5        | 4.5%    |
| Marvell Technology Group         | 5        | 4.5%    |
| SanDisk                          | 2        | 1.8%    |
| Silicon Motion                   | 1        | 0.9%    |
| Silicon Integrated Systems [SiS] | 1        | 0.9%    |
| Realtek Semiconductor            | 1        | 0.9%    |
| ADATA Technology                 | 1        | 0.9%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 12       | 8.11%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 10       | 6.76%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 9        | 6.08%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 7        | 4.73%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 6        | 4.05%   |
| JMicron JMB368 IDE controller                                                  | 5        | 3.38%   |
| Nvidia MCP61 SATA Controller                                                   | 4        | 2.7%    |
| Nvidia MCP61 IDE                                                               | 4        | 2.7%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 4        | 2.7%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 4        | 2.7%    |
| AMD 500 Series Chipset SATA Controller                                         | 4        | 2.7%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 3        | 2.03%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 3        | 2.03%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3        | 2.03%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 3        | 2.03%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 3        | 2.03%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 3        | 2.03%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3        | 2.03%   |
| AMD FCH IDE Controller                                                         | 3        | 2.03%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                      | 2        | 1.35%   |
| JMicron JMB363 SATA/IDE Controller                                             | 2        | 1.35%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2        | 1.35%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 2        | 1.35%   |
| Intel 82801IB (ICH9) 4 port SATA Controller [AHCI mode]                        | 2        | 1.35%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 2        | 1.35%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]            | 2        | 1.35%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                   | 2        | 1.35%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2        | 1.35%   |
| AMD 400 Series Chipset SATA Controller                                         | 2        | 1.35%   |
| AMD 300 Series Chipset SATA Controller                                         | 2        | 1.35%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1        | 0.68%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 1        | 0.68%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 1        | 0.68%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1        | 0.68%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1        | 0.68%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 0.68%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1        | 0.68%   |
| Realtek Realtek Non-Volatile memory controller                                 | 1        | 0.68%   |
| Nvidia MCP67 IDE Controller                                                    | 1        | 0.68%   |
| Nvidia MCP67 AHCI Controller                                                   | 1        | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 56       | 51.85%  |
| IDE  | 37       | 34.26%  |
| NVMe | 14       | 12.96%  |
| RAID | 1        | 0.93%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 59       | 69.41%  |
| AMD    | 26       | 30.59%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Intel Core i5-4570 CPU @ 3.20GHz              | 4        | 4.71%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 3        | 3.53%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 3        | 3.53%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 3        | 3.53%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz        | 2        | 2.35%   |
| Intel Pentium D CPU 3.40GHz                   | 2        | 2.35%   |
| Intel Pentium D CPU 2.80GHz                   | 2        | 2.35%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 2        | 2.35%   |
| Intel Core i5 CPU 650 @ 3.20GHz               | 2        | 2.35%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz         | 2        | 2.35%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 2        | 2.35%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz          | 2        | 2.35%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz          | 2        | 2.35%   |
| Intel Core 2 CPU 6300 @ 1.86GHz               | 2        | 2.35%   |
| AMD Ryzen 5 3600 6-Core Processor             | 2        | 2.35%   |
| AMD A8-7600 Radeon R7, 10 Compute Cores 4C+6G | 2        | 2.35%   |
| AMD A8-6600K APU with Radeon HD Graphics      | 2        | 2.35%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz   | 1        | 1.18%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 1        | 1.18%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz   | 1        | 1.18%   |
| Intel Pentium Dual CPU E2220 @ 2.40GHz        | 1        | 1.18%   |
| Intel Pentium D CPU 3.00GHz                   | 1        | 1.18%   |
| Intel Pentium CPU G620 @ 2.60GHz              | 1        | 1.18%   |
| Intel Pentium 4 CPU 2.66GHz                   | 1        | 1.18%   |
| Intel Core i7-9700K CPU @ 3.60GHz             | 1        | 1.18%   |
| Intel Core i7-8700T CPU @ 2.40GHz             | 1        | 1.18%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 1        | 1.18%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 1        | 1.18%   |
| Intel Core i7-4770K CPU @ 3.50GHz             | 1        | 1.18%   |
| Intel Core i7-4765T CPU @ 2.00GHz             | 1        | 1.18%   |
| Intel Core i7-3930K CPU @ 3.20GHz             | 1        | 1.18%   |
| Intel Core i7-2700K CPU @ 3.50GHz             | 1        | 1.18%   |
| Intel Core i7 CPU 860 @ 2.80GHz               | 1        | 1.18%   |
| Intel Core i5-8600K CPU @ 3.60GHz             | 1        | 1.18%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 1        | 1.18%   |
| Intel Core i5-7600K CPU @ 3.80GHz             | 1        | 1.18%   |
| Intel Core i5-4670K CPU @ 3.40GHz             | 1        | 1.18%   |
| Intel Core i5-2500K CPU @ 3.30GHz             | 1        | 1.18%   |
| Intel Core i3-6100 CPU @ 3.70GHz              | 1        | 1.18%   |
| Intel Core i3-4170 CPU @ 3.70GHz              | 1        | 1.18%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 14       | 16.47%  |
| Intel Core i7           | 11       | 12.94%  |
| Intel Core i3           | 8        | 9.41%   |
| AMD Ryzen 5             | 8        | 9.41%   |
| Intel Core 2 Duo        | 6        | 7.06%   |
| Intel Pentium D         | 5        | 5.88%   |
| AMD A8                  | 5        | 5.88%   |
| Intel Core 2 Quad       | 4        | 4.71%   |
| Intel Pentium Dual-Core | 3        | 3.53%   |
| Intel Pentium Dual      | 3        | 3.53%   |
| AMD Athlon 64 X2        | 3        | 3.53%   |
| Intel Core 2            | 2        | 2.35%   |
| AMD Ryzen 7             | 2        | 2.35%   |
| AMD FX                  | 2        | 2.35%   |
| AMD Athlon II X2        | 2        | 2.35%   |
| Intel Pentium 4         | 1        | 1.18%   |
| Intel Pentium           | 1        | 1.18%   |
| Intel Celeron           | 1        | 1.18%   |
| AMD Ryzen Threadripper  | 1        | 1.18%   |
| AMD Ryzen 9             | 1        | 1.18%   |
| AMD Athlon II X3        | 1        | 1.18%   |
| AMD Athlon              | 1        | 1.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 38       | 44.19%  |
| 4       | 24       | 27.91%  |
| 6       | 11       | 12.79%  |
| 3       | 4        | 4.65%   |
| 8       | 3        | 3.49%   |
| 1       | 3        | 3.49%   |
| 24      | 1        | 1.16%   |
| 12      | 1        | 1.16%   |
| Unknown | 1        | 1.16%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 85       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 47       | 54.65%  |
| 2       | 38       | 44.19%  |
| Unknown | 1        | 1.16%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 84       | 98.82%  |
| Unknown        | 1        | 1.18%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 14       | 16.28%  |
| 0x306c3    | 12       | 13.95%  |
| 0x1067a    | 7        | 8.14%   |
| 0x206a7    | 4        | 4.65%   |
| 0x10676    | 4        | 4.65%   |
| 0x08701021 | 4        | 4.65%   |
| 0x906ea    | 3        | 3.49%   |
| 0x6fd      | 3        | 3.49%   |
| 0x06001119 | 3        | 3.49%   |
| 0xf65      | 2        | 2.33%   |
| 0xf47      | 2        | 2.33%   |
| 0x6fb      | 2        | 2.33%   |
| 0x6f2      | 2        | 2.33%   |
| 0x506e3    | 2        | 2.33%   |
| 0x306a9    | 2        | 2.33%   |
| 0x0a201009 | 2        | 2.33%   |
| 0x06003106 | 2        | 2.33%   |
| 0x010000c8 | 2        | 2.33%   |
| 0xf64      | 1        | 1.16%   |
| 0xf41      | 1        | 1.16%   |
| 0x906ed    | 1        | 1.16%   |
| 0x906e9    | 1        | 1.16%   |
| 0x706a1    | 1        | 1.16%   |
| 0x206d6    | 1        | 1.16%   |
| 0x20655    | 1        | 1.16%   |
| 0x20652    | 1        | 1.16%   |
| 0x106e5    | 1        | 1.16%   |
| 0x0a20120a | 1        | 1.16%   |
| 0x08001137 | 1        | 1.16%   |
| 0x08001126 | 1        | 1.16%   |
| 0x06000852 | 1        | 1.16%   |
| 0x0600063e | 1        | 1.16%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 15       | 17.65%  |
| Penryn        | 11       | 12.94%  |
| Core          | 7        | 8.24%   |
| Zen 2         | 6        | 7.06%   |
| NetBurst      | 6        | 7.06%   |
| KabyLake      | 6        | 7.06%   |
| SandyBridge   | 5        | 5.88%   |
| Zen 3         | 4        | 4.71%   |
| Piledriver    | 4        | 4.71%   |
| K8 Hammer     | 4        | 4.71%   |
| K10           | 3        | 3.53%   |
| IvyBridge     | 3        | 3.53%   |
| Zen           | 2        | 2.35%   |
| Westmere      | 2        | 2.35%   |
| Steamroller   | 2        | 2.35%   |
| Skylake       | 2        | 2.35%   |
| Nehalem       | 1        | 1.18%   |
| Goldmont plus | 1        | 1.18%   |
| Bulldozer     | 1        | 1.18%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 43       | 46.24%  |
| AMD    | 27       | 29.03%  |
| Intel  | 23       | 24.73%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5        | 5.15%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 3.09%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 2        | 2.06%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 2.06%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 2        | 2.06%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 2.06%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 2.06%   |
| Nvidia GF106 [GeForce GTS 450]                                              | 2        | 2.06%   |
| Nvidia G84 [GeForce 8600 GT]                                                | 2        | 2.06%   |
| Nvidia G72 [GeForce 7300 GS]                                                | 2        | 2.06%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 2.06%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 2.06%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 2        | 2.06%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2        | 2.06%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 2        | 2.06%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 2.06%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 2        | 2.06%   |
| AMD Richland [Radeon HD 8570D]                                              | 2        | 2.06%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 2        | 2.06%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 2.06%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 2        | 2.06%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 1.03%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 1.03%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 1.03%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 1        | 1.03%   |
| Nvidia NV44 [GeForce 6200 SE TurboCache]                                    | 1        | 1.03%   |
| Nvidia GT216 [GeForce GT 220]                                               | 1        | 1.03%   |
| Nvidia GT200 [GeForce GTX 260]                                              | 1        | 1.03%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 1.03%   |
| Nvidia GP106 [GeForce GTX 1060 6GB Rev. 2]                                  | 1        | 1.03%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 1.03%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 1.03%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 1.03%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 1.03%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 1        | 1.03%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.03%   |
| Nvidia GK208B [GeForce GT 720]                                              | 1        | 1.03%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 1        | 1.03%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 1.03%   |
| Nvidia GF114 [GeForce GTX 560]                                              | 1        | 1.03%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 40       | 45.98%  |
| 1 x AMD        | 22       | 25.29%  |
| 1 x Intel      | 18       | 20.69%  |
| 2 x AMD        | 3        | 3.45%   |
| Intel + Nvidia | 2        | 2.3%    |
| 2 x Nvidia     | 1        | 1.15%   |
| Intel + AMD    | 1        | 1.15%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 60       | 68.97%  |
| Proprietary | 23       | 26.44%  |
| Unknown     | 4        | 4.6%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 26       | 29.89%  |
| 0.01-0.5   | 20       | 22.99%  |
| 0.51-1.0   | 14       | 16.09%  |
| 5.01-6.0   | 7        | 8.05%   |
| 3.01-4.0   | 7        | 8.05%   |
| 1.01-2.0   | 7        | 8.05%   |
| 7.01-8.0   | 3        | 3.45%   |
| 2.01-3.0   | 1        | 1.15%   |
| 16.01-24.0 | 1        | 1.15%   |
| 8.01-16.0  | 1        | 1.15%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 15       | 17.65%  |
| Goldstar             | 15       | 17.65%  |
| Philips              | 8        | 9.41%   |
| BenQ                 | 7        | 8.24%   |
| Dell                 | 6        | 7.06%   |
| Ancor Communications | 6        | 7.06%   |
| Hewlett-Packard      | 5        | 5.88%   |
| AOC                  | 5        | 5.88%   |
| LG Electronics       | 3        | 3.53%   |
| ViewSonic            | 2        | 2.35%   |
| Unknown              | 2        | 2.35%   |
| NEC Computers        | 2        | 2.35%   |
| Lenovo               | 2        | 2.35%   |
| Arnos Instruments    | 2        | 2.35%   |
| Wacom                | 1        | 1.18%   |
| Plain Tree Systems   | 1        | 1.18%   |
| IBM                  | 1        | 1.18%   |
| HYO                  | 1        | 1.18%   |
| FUS                  | 1        | 1.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar L194WT GSM4B06 1440x900 408x255mm 18.9-inch                  | 3        | 3.26%   |
| Philips PHL 276E8V PHLC18F 3840x2160 600x340mm 27.2-inch              | 2        | 2.17%   |
| LG Electronics LCD Monitor LG TV 1920x1080                            | 2        | 2.17%   |
| BenQ XL2411Z BNQ7F31 1920x1080 531x298mm 24.0-inch                    | 2        | 2.17%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch | 2        | 2.17%   |
| Wacom CintiqPro24P WAC1063 3840x2160 522x293mm 23.6-inch              | 1        | 1.09%   |
| ViewSonic VA703-3Series VSC631E 1280x1024 338x270mm 17.0-inch         | 1        | 1.09%   |
| ViewSonic VA503 SERIES VSCEF1D 1024x768 304x228mm 15.0-inch           | 1        | 1.09%   |
| Unknown LCD Monitor Sharp LL-S201A 1920x1080                          | 1        | 1.09%   |
| Unknown LCD Monitor HYO DUAL-DVI 2560x1440                            | 1        | 1.09%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch  | 1        | 1.09%   |
| Samsung Electronics SyncMaster SAM036C 1920x1200 550x343mm 25.5-inch  | 1        | 1.09%   |
| Samsung Electronics SyncMaster SAM02F6 1280x1024 340x270mm 17.1-inch  | 1        | 1.09%   |
| Samsung Electronics SyncMaster SAM026E 1280x1024 376x301mm 19.0-inch  | 1        | 1.09%   |
| Samsung Electronics SyncMaster SAM0259 1280x1024 376x301mm 19.0-inch  | 1        | 1.09%   |
| Samsung Electronics SyncMaster SAM0217 1280x1024 376x301mm 19.0-inch  | 1        | 1.09%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch  | 1        | 1.09%   |
| Samsung Electronics SyncMaster SAM006B 1280x1024 338x270mm 17.0-inch  | 1        | 1.09%   |
| Samsung Electronics SA300/SA350 SAM0793 1920x1080 531x299mm 24.0-inch | 1        | 1.09%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch     | 1        | 1.09%   |
| Samsung Electronics S24E391 SAM0C12 1920x1080 521x293mm 23.5-inch     | 1        | 1.09%   |
| Samsung Electronics S24E390 SAM0C1A 1920x1080 521x293mm 23.5-inch     | 1        | 1.09%   |
| Samsung Electronics S23B350 SAM08D5 1920x1080 510x287mm 23.0-inch     | 1        | 1.09%   |
| Samsung Electronics LCD Monitor SyncMaster                            | 1        | 1.09%   |
| Samsung Electronics LCD Monitor SAM03D4 1360x768                      | 1        | 1.09%   |
| Plain Tree Systems 782 PTS1017 1280x1024 337x270mm 17.0-inch          | 1        | 1.09%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 1        | 1.09%   |
| Philips 227E4Q PHLC0A9 1920x1080 477x268mm 21.5-inch                  | 1        | 1.09%   |
| Philips 220VW PHL0853 1680x1050 474x296mm 22.0-inch                   | 1        | 1.09%   |
| Philips 220S4L PHL08BE 1680x1050 474x296mm 22.0-inch                  | 1        | 1.09%   |
| Philips 206VL PHLC08C 1600x900 443x249mm 20.0-inch                    | 1        | 1.09%   |
| Philips 200WB PHL0842 1680x1050 433x271mm 20.1-inch                   | 1        | 1.09%   |
| NEC Computers LCD Monitor LCD22WV 1680x1050                           | 1        | 1.09%   |
| NEC Computers LCD Monitor LCD1770NX                                   | 1        | 1.09%   |
| LG Electronics LCD Monitor LG TV 3840x2160                            | 1        | 1.09%   |
| LG Electronics LCD Monitor L192WS 1440x900                            | 1        | 1.09%   |
| Lenovo P24q-10 LEN61A5 2560x1440 527x296mm 23.8-inch                  | 1        | 1.09%   |
| Lenovo LEN L174 LEN240B 1280x1024 340x270mm 17.1-inch                 | 1        | 1.09%   |
| IBM L180p IBM23DC 1280x1024 359x287mm 18.1-inch                       | 1        | 1.09%   |
| HYO DVI HYO049B 2560x1440 600x340mm 27.2-inch                         | 1        | 1.09%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 25       | 29.41%  |
| 1280x1024 (SXGA)   | 13       | 15.29%  |
| 1680x1050 (WSXGA+) | 9        | 10.59%  |
| 3840x2160 (4K)     | 7        | 8.24%   |
| 2560x1440 (QHD)    | 7        | 8.24%   |
| 1440x900 (WXGA+)   | 6        | 7.06%   |
| 1600x900 (HD+)     | 3        | 3.53%   |
| Unknown            | 3        | 3.53%   |
| 2560x1080          | 2        | 2.35%   |
| 1920x1200 (WUXGA)  | 2        | 2.35%   |
| 1024x768 (XGA)     | 2        | 2.35%   |
| 4480x1440          | 1        | 1.18%   |
| 3840x1080          | 1        | 1.18%   |
| 3520x1200          | 1        | 1.18%   |
| 2960x1050          | 1        | 1.18%   |
| 1360x768           | 1        | 1.18%   |
| 1280x960           | 1        | 1.18%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 12       | 14.46%  |
| Unknown | 12       | 14.46%  |
| 23      | 9        | 10.84%  |
| 24      | 8        | 9.64%   |
| 19      | 8        | 9.64%   |
| 17      | 8        | 9.64%   |
| 22      | 6        | 7.23%   |
| 20      | 5        | 6.02%   |
| 21      | 4        | 4.82%   |
| 25      | 3        | 3.61%   |
| 18      | 3        | 3.61%   |
| 34      | 2        | 2.41%   |
| 15      | 2        | 2.41%   |
| 33      | 1        | 1.2%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 27       | 34.62%  |
| 401-500     | 19       | 24.36%  |
| Unknown     | 12       | 15.38%  |
| 301-350     | 10       | 12.82%  |
| 351-400     | 6        | 7.69%   |
| 701-800     | 3        | 3.85%   |
| 601-700     | 1        | 1.28%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 33       | 42.86%  |
| 16/10   | 15       | 19.48%  |
| 5/4     | 14       | 18.18%  |
| Unknown | 11       | 14.29%  |
| 4/3     | 2        | 2.6%    |
| 21/9    | 2        | 2.6%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 25       | 30.86%  |
| 151-200        | 16       | 19.75%  |
| 301-350        | 12       | 14.81%  |
| Unknown        | 12       | 14.81%  |
| 141-150        | 8        | 9.88%   |
| 351-500        | 3        | 3.7%    |
| 251-300        | 3        | 3.7%    |
| 101-110        | 2        | 2.47%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 52       | 65.82%  |
| Unknown | 12       | 15.19%  |
| 101-120 | 10       | 12.66%  |
| 161-240 | 3        | 3.8%    |
| 121-160 | 2        | 2.53%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 76       | 87.36%  |
| 2     | 8        | 9.2%    |
| 0     | 2        | 2.3%    |
| 3     | 1        | 1.15%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 47       | 41.96%  |
| Intel                             | 24       | 21.43%  |
| Broadcom                          | 6        | 5.36%   |
| Qualcomm Atheros                  | 5        | 4.46%   |
| TP-Link                           | 4        | 3.57%   |
| Ralink Technology                 | 4        | 3.57%   |
| Ralink                            | 4        | 3.57%   |
| Nvidia                            | 4        | 3.57%   |
| Qualcomm Atheros Communications   | 2        | 1.79%   |
| Marvell Technology Group          | 2        | 1.79%   |
| Broadcom Limited                  | 2        | 1.79%   |
| ASIX Electronics                  | 2        | 1.79%   |
| Xiaomi                            | 1        | 0.89%   |
| Sundance Technology Inc / IC Plus | 1        | 0.89%   |
| Silicon Integrated Systems [SiS]  | 1        | 0.89%   |
| Samsung Electronics               | 1        | 0.89%   |
| Aquantia                          | 1        | 0.89%   |
| 3Com                              | 1        | 0.89%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 38       | 30.65%  |
| Realtek RTL8125 2.5GbE Controller                                          | 5        | 4.03%   |
| Intel Ethernet Connection I217-LM                                          | 4        | 3.23%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 3        | 2.42%   |
| Nvidia MCP61 Ethernet                                                      | 3        | 2.42%   |
| Intel Wi-Fi 6 AX200                                                        | 3        | 2.42%   |
| Intel I211 Gigabit Network Connection                                      | 3        | 2.42%   |
| Intel Ethernet Connection I217-V                                           | 3        | 2.42%   |
| Intel Ethernet Connection (2) I219-V                                       | 3        | 2.42%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                | 2        | 1.61%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 2        | 1.61%   |
| Ralink RT5370 Wireless Adapter                                             | 2        | 1.61%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                  | 2        | 1.61%   |
| Qualcomm Atheros AR9271 802.11n                                            | 2        | 1.61%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 2        | 1.61%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                    | 2        | 1.61%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express                    | 2        | 1.61%   |
| ASIX AX88772B                                                              | 2        | 1.61%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 1        | 0.81%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                        | 1        | 0.81%   |
| TP-Link 802.11ac WLAN Adapter                                              | 1        | 0.81%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.81%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter              | 1        | 0.81%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 1        | 0.81%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                   | 1        | 0.81%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                            | 1        | 0.81%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                 | 1        | 0.81%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                     | 1        | 0.81%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                      | 1        | 0.81%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 1        | 0.81%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 1        | 0.81%   |
| Ralink RT2870/RT3070 Wireless Adapter                                      | 1        | 0.81%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                          | 1        | 0.81%   |
| Ralink MT7601U Wireless Adapter                                            | 1        | 0.81%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                  | 1        | 0.81%   |
| Ralink RT2561/RT61 rev B 802.11g                                           | 1        | 0.81%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                  | 1        | 0.81%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 1        | 0.81%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                   | 1        | 0.81%   |
| Nvidia MCP67 Ethernet                                                      | 1        | 0.81%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 6        | 21.43%  |
| Intel                           | 5        | 17.86%  |
| TP-Link                         | 4        | 14.29%  |
| Ralink Technology               | 4        | 14.29%  |
| Ralink                          | 4        | 14.29%  |
| Qualcomm Atheros Communications | 2        | 7.14%   |
| Broadcom                        | 2        | 7.14%   |
| Broadcom Limited                | 1        | 3.57%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                        | 3        | 10.34%  |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                | 2        | 6.9%    |
| Ralink RT5370 Wireless Adapter                             | 2        | 6.9%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                  | 2        | 6.9%    |
| Qualcomm Atheros AR9271 802.11n                            | 2        | 6.9%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                        | 1        | 3.45%   |
| TP-Link 802.11ac WLAN Adapter                              | 1        | 3.45%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter   | 1        | 3.45%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter            | 1        | 3.45%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                 | 1        | 3.45%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                     | 1        | 3.45%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter      | 1        | 3.45%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 1        | 3.45%   |
| Ralink RT2870/RT3070 Wireless Adapter                      | 1        | 3.45%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter          | 1        | 3.45%   |
| Ralink MT7601U Wireless Adapter                            | 1        | 3.45%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                  | 1        | 3.45%   |
| Ralink RT2561/RT61 rev B 802.11g                           | 1        | 3.45%   |
| Intel Wireless 8260                                        | 1        | 3.45%   |
| Intel Wireless 7265                                        | 1        | 3.45%   |
| Broadcom Network controller                                | 1        | 3.45%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter | 1        | 3.45%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter         | 1        | 3.45%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 44       | 49.44%  |
| Intel                             | 21       | 23.6%   |
| Qualcomm Atheros                  | 5        | 5.62%   |
| Nvidia                            | 4        | 4.49%   |
| Broadcom                          | 4        | 4.49%   |
| Marvell Technology Group          | 2        | 2.25%   |
| ASIX Electronics                  | 2        | 2.25%   |
| Xiaomi                            | 1        | 1.12%   |
| Sundance Technology Inc / IC Plus | 1        | 1.12%   |
| Silicon Integrated Systems [SiS]  | 1        | 1.12%   |
| Samsung Electronics               | 1        | 1.12%   |
| Broadcom Limited                  | 1        | 1.12%   |
| Aquantia                          | 1        | 1.12%   |
| 3Com                              | 1        | 1.12%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 38       | 40%     |
| Realtek RTL8125 2.5GbE Controller                                          | 5        | 5.26%   |
| Intel Ethernet Connection I217-LM                                          | 4        | 4.21%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 3        | 3.16%   |
| Nvidia MCP61 Ethernet                                                      | 3        | 3.16%   |
| Intel I211 Gigabit Network Connection                                      | 3        | 3.16%   |
| Intel Ethernet Connection I217-V                                           | 3        | 3.16%   |
| Intel Ethernet Connection (2) I219-V                                       | 3        | 3.16%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 2        | 2.11%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 2        | 2.11%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                    | 2        | 2.11%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express                    | 2        | 2.11%   |
| ASIX AX88772B                                                              | 2        | 2.11%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 1        | 1.05%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 1.05%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter              | 1        | 1.05%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 1        | 1.05%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 1        | 1.05%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                  | 1        | 1.05%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 1        | 1.05%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                   | 1        | 1.05%   |
| Nvidia MCP67 Ethernet                                                      | 1        | 1.05%   |
| Intel Ethernet Connection (7) I219-V                                       | 1        | 1.05%   |
| Intel 82579V Gigabit Network Connection                                    | 1        | 1.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 1        | 1.05%   |
| Intel 82578DM Gigabit Network Connection                                   | 1        | 1.05%   |
| Intel 82574L Gigabit Network Connection                                    | 1        | 1.05%   |
| Intel 82573E Gigabit Ethernet Controller (Copper)                          | 1        | 1.05%   |
| Intel 82567V-2 Gigabit Network Connection                                  | 1        | 1.05%   |
| Intel 82567LF-3 Gigabit Network Connection                                 | 1        | 1.05%   |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller              | 1        | 1.05%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                    | 1        | 1.05%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                            | 1        | 1.05%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express            | 1        | 1.05%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]          | 1        | 1.05%   |
| 3Com 3c940 10/100/1000Base-T [Marvell]                                     | 1        | 1.05%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 84       | 75.68%  |
| WiFi     | 27       | 24.32%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 70       | 80.46%  |
| WiFi     | 17       | 19.54%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 61       | 71.76%  |
| 2     | 20       | 23.53%  |
| 3     | 2        | 2.35%   |
| 0     | 2        | 2.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 83       | 97.65%  |
| Yes  | 2        | 2.35%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 5        | 35.71%  |
| Cambridge Silicon Radio | 5        | 35.71%  |
| Realtek Semiconductor   | 2        | 14.29%  |
| ASUSTek Computer        | 1        | 7.14%   |
| Apple                   | 1        | 7.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5        | 35.71%  |
| Intel AX200 Bluetooth                               | 3        | 21.43%  |
| Realtek Bluetooth Radio                             | 2        | 14.29%  |
| Intel Bluetooth wireless interface                  | 2        | 14.29%  |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 7.14%   |
| Apple Bluetooth USB Host Controller                 | 1        | 7.14%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 58       | 40.56%  |
| Nvidia                           | 35       | 24.48%  |
| AMD                              | 33       | 23.08%  |
| C-Media Electronics              | 5        | 3.5%    |
| Yamaha                           | 2        | 1.4%    |
| Creative Labs                    | 2        | 1.4%    |
| Unknown                          | 1        | 0.7%    |
| Syntek                           | 1        | 0.7%    |
| SteelSeries ApS                  | 1        | 0.7%    |
| Silicon Integrated Systems [SiS] | 1        | 0.7%    |
| Realtek Semiconductor            | 1        | 0.7%    |
| JMTek                            | 1        | 0.7%    |
| FIFINE 683 Microphone            | 1        | 0.7%    |
| Creative Technology              | 1        | 0.7%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 12       | 7.41%   |
| AMD Starship/Matisse HD Audio Controller                                   | 10       | 6.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 7        | 4.32%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 7        | 4.32%   |
| Nvidia TU116 High Definition Audio Controller                              | 6        | 3.7%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 6        | 3.7%    |
| Nvidia MCP61 High Definition Audio                                         | 4        | 2.47%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4        | 2.47%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 2.47%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4        | 2.47%   |
| AMD FCH Azalia Controller                                                  | 4        | 2.47%   |
| Nvidia GP106 High Definition Audio Controller                              | 3        | 1.85%   |
| Intel Cannon Lake PCH cAVS                                                 | 3        | 1.85%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 3        | 1.85%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3        | 1.85%   |
| Intel 200 Series PCH HD Audio                                              | 3        | 1.85%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3        | 1.85%   |
| Yamaha Steinberg UR22mkII                                                  | 2        | 1.23%   |
| Nvidia TU106 High Definition Audio Controller                              | 2        | 1.23%   |
| Nvidia TU104 HD Audio Controller                                           | 2        | 1.23%   |
| Nvidia High Definition Audio Controller                                    | 2        | 1.23%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 1.23%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2        | 1.23%   |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 1.23%   |
| Nvidia GF106 High Definition Audio Controller                              | 2        | 1.23%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2        | 1.23%   |
| Intel 82801G (ICH7 Family) AC'97 Audio Controller                          | 2        | 1.23%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2        | 1.23%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 1.23%   |
| C-Media Electronics ARCANO MARK-HI                                         | 2        | 1.23%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 2        | 1.23%   |
| AMD Trinity HDMI Audio Controller                                          | 2        | 1.23%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 2        | 1.23%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 2        | 1.23%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2        | 1.23%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2        | 1.23%   |
| Unknown USB Audio                                                          | 1        | 0.62%   |
| Syntek STK1160 Video Capture Device                                        | 1        | 0.62%   |
| SteelSeries ApS SteelSeries Arctis 7                                       | 1        | 0.62%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 1        | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 16       | 29.63%  |
| Kingston            | 15       | 27.78%  |
| Crucial             | 7        | 12.96%  |
| Corsair             | 5        | 9.26%   |
| G.Skill             | 3        | 5.56%   |
| SK hynix            | 2        | 3.7%    |
| Micron Technology   | 2        | 3.7%    |
| Team                | 1        | 1.85%   |
| Samsung Electronics | 1        | 1.85%   |
| Ramos Technology    | 1        | 1.85%   |
| A-DATA Technology   | 1        | 1.85%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                | 2        | 2.99%   |
| Unknown RAM Module 2048MB DIMM SDRAM                    | 2        | 2.99%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                  | 2        | 2.99%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                  | 2        | 2.99%   |
| Kingston RAM KHX3466C16D4/16GX 16GB DIMM DDR4 3466MT/s  | 2        | 2.99%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s     | 2        | 2.99%   |
| Kingston RAM KHX1600C10D3/8GX 8192MB DIMM DDR3 1600MT/s | 2        | 2.99%   |
| Unknown RAM Module 4096MB DIMM DDR3 667MT/s             | 1        | 1.49%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s            | 1        | 1.49%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                 | 1        | 1.49%   |
| Unknown RAM Module 2048MB DIMM SDRAM 1333MT/s           | 1        | 1.49%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s             | 1        | 1.49%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                  | 1        | 1.49%   |
| Unknown RAM Module 2048MB DIMM 1066MT/s                 | 1        | 1.49%   |
| Unknown RAM Module 2048MB DIMM                          | 1        | 1.49%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                | 1        | 1.49%   |
| Unknown RAM Module 1024MB DIMM SDRAM                    | 1        | 1.49%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s             | 1        | 1.49%   |
| Unknown RAM Module 1024MB DIMM DDR 667MT/s              | 1        | 1.49%   |
| Unknown RAM Module 1024MB DIMM DDR 533MT/s              | 1        | 1.49%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                  | 1        | 1.49%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s     | 1        | 1.49%   |
| SK hynix RAM HYMP564U64CP8-Y5 512MB DIMM DDR2 667MT/s   | 1        | 1.49%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s | 1        | 1.49%   |
| Samsung RAM M3 78T2863QZS-CE6 1GB DIMM SDRAM 1639MT/s   | 1        | 1.49%   |
| Ramos RAM RMB2GE484CA5-13HC 2048MB DIMM 533MT/s         | 1        | 1.49%   |
| Micron RAM 8JTF25664AZ-1G6M1 2GB DIMM DDR3 1600MT/s     | 1        | 1.49%   |
| Micron RAM 8HTF12864AY-667E1 1GB DIMM DDR2 667MT/s      | 1        | 1.49%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s  | 1        | 1.49%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s | 1        | 1.49%   |
| Kingston RAM KHX2133C11D3/4GX 4096MB DIMM DDR3 2134MT/s | 1        | 1.49%   |
| Kingston RAM KHX1600C9D3/8GX 8192MB DIMM DDR3 2133MT/s  | 1        | 1.49%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s     | 1        | 1.49%   |
| Kingston RAM KHX1600C10D3/8G 8192MB DIMM DDR3 1600MT/s  | 1        | 1.49%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1866MT/s     | 1        | 1.49%   |
| Kingston RAM HX316C10F/4 4GB DIMM DDR3 1600MT/s         | 1        | 1.49%   |
| Kingston RAM 99U5431-004.A00LF 1024MB DIMM DDR 533MT/s  | 1        | 1.49%   |
| Kingston RAM 99U5403-046.A00LF 4GB DIMM DDR3 1333MT/s   | 1        | 1.49%   |
| Kingston RAM 9965525-134.A00LF 8GB DIMM DDR3 1333MT/s   | 1        | 1.49%   |
| Kingston RAM 9965525-055.A00LF 8GB DIMM DDR3 1600MT/s   | 1        | 1.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 15       | 33.33%  |
| DDR4    | 14       | 31.11%  |
| Unknown | 7        | 15.56%  |
| SDRAM   | 4        | 8.89%   |
| DDR2    | 3        | 6.67%   |
| DDR     | 2        | 4.44%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 44       | 97.78%  |
| SODIMM | 1        | 2.22%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 14       | 25%     |
| 8192  | 13       | 23.21%  |
| 4096  | 13       | 23.21%  |
| 1024  | 8        | 14.29%  |
| 16384 | 5        | 8.93%   |
| 32768 | 2        | 3.57%   |
| 512   | 1        | 1.79%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 667     | 9        | 15.25%  |
| 1600    | 8        | 13.56%  |
| 2133    | 6        | 10.17%  |
| 1333    | 6        | 10.17%  |
| 3466    | 3        | 5.08%   |
| 800     | 3        | 5.08%   |
| Unknown | 3        | 5.08%   |
| 3200    | 2        | 3.39%   |
| 3000    | 2        | 3.39%   |
| 2667    | 2        | 3.39%   |
| 2400    | 2        | 3.39%   |
| 1867    | 2        | 3.39%   |
| 533     | 2        | 3.39%   |
| 3866    | 1        | 1.69%   |
| 3800    | 1        | 1.69%   |
| 3600    | 1        | 1.69%   |
| 2448    | 1        | 1.69%   |
| 2134    | 1        | 1.69%   |
| 1866    | 1        | 1.69%   |
| 1800    | 1        | 1.69%   |
| 1639    | 1        | 1.69%   |
| 1066    | 1        | 1.69%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 3        | 50%     |
| Samsung Electronics | 1        | 16.67%  |
| Canon               | 1        | 16.67%  |
| Brother Industries  | 1        | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Desktops | Percent |
|---------------------------|----------|---------|
| Samsung SCX-4216F Scanner | 1        | 16.67%  |
| HP Officejet 4500 G510g-m | 1        | 16.67%  |
| HP LaserJet 1010          | 1        | 16.67%  |
| HP DeskJet 5940           | 1        | 16.67%  |
| Canon PIXMA MG3000 series | 1        | 16.67%  |
| Brother DCP-L2510D series | 1        | 16.67%  |

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


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Logitech                    | 9        | 39.13%  |
| Z-Star Microelectronics     | 3        | 13.04%  |
| Apple                       | 2        | 8.7%    |
| Tobii Technology AB         | 1        | 4.35%   |
| Samsung Electronics         | 1        | 4.35%   |
| Pixart Imaging              | 1        | 4.35%   |
| Microdia                    | 1        | 4.35%   |
| KYE Systems (Mouse Systems) | 1        | 4.35%   |
| Genesys Logic               | 1        | 4.35%   |
| GEMBIRD                     | 1        | 4.35%   |
| Cubeternet                  | 1        | 4.35%   |
| Chicony Electronics         | 1        | 4.35%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Z-Star A4 TECH HD PC Camera                 | 2        | 8.7%    |
| Logitech Webcam C270                        | 2        | 8.7%    |
| Logitech Webcam C170                        | 2        | 8.7%    |
| Apple iPhone5/5C/5S/6                       | 2        | 8.7%    |
| Z-Star Vega USB 2.0 Camera                  | 1        | 4.35%   |
| Tobii AB EyeChip                            | 1        | 4.35%   |
| Samsung Galaxy A5 (MTP)                     | 1        | 4.35%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro        | 1        | 4.35%   |
| Microdia Defender G-Lens 2577 HD720p Camera | 1        | 4.35%   |
| Logitech Webcam C310                        | 1        | 4.35%   |
| Logitech Webcam C250                        | 1        | 4.35%   |
| Logitech Webcam C210                        | 1        | 4.35%   |
| Logitech HD Webcam C525                     | 1        | 4.35%   |
| Logitech HD Webcam C510                     | 1        | 4.35%   |
| KYE Systems (Mouse Systems) eFace 2050AF    | 1        | 4.35%   |
| Genesys Logic Camera                        | 1        | 4.35%   |
| GEMBIRD USB2.0 PC CAMERA                    | 1        | 4.35%   |
| Cubeternet USB2.0 Camera                    | 1        | 4.35%   |
| Chicony HP High Definition Webcam           | 1        | 4.35%   |

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


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Alcor Micro | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 78       | 90.7%   |
| 1     | 7        | 8.14%   |
| 2     | 1        | 1.16%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 4        | 44.44%  |
| Net/wireless             | 2        | 22.22%  |
| Storage/raid             | 1        | 11.11%  |
| Net/ethernet             | 1        | 11.11%  |
| Communication controller | 1        | 11.11%  |

