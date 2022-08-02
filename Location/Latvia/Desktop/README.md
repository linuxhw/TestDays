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

Total: 120

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | Z87-HD3                     | [83936d3cf0](https://linux-hardware.org/?probe=83936d3cf0) | Jul 31, 2022 |
| Gigabyte      | G33M-S2                     | [219dd022c6](https://linux-hardware.org/?probe=219dd022c6) | Jul 31, 2022 |
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


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Ubuntu 20.04         | 6        | 7.06%   |
| Ubuntu 18.04         | 6        | 7.06%   |
| ROSA R10             | 6        | 7.06%   |
| ROSA R11             | 5        | 5.88%   |
| KDE neon 20.04       | 5        | 5.88%   |
| Linux Mint 20.1      | 4        | 4.71%   |
| ROSA R9              | 3        | 3.53%   |
| Linux Mint 20.2      | 3        | 3.53%   |
| Arch Rolling         | 3        | 3.53%   |
| Xubuntu 20.04        | 2        | 2.35%   |
| ROSA R8.1            | 2        | 2.35%   |
| OpenMandriva 4.50    | 2        | 2.35%   |
| OpenMandriva 4.2     | 2        | 2.35%   |
| Linux Mint 20.3      | 2        | 2.35%   |
| Fedora 35            | 2        | 2.35%   |
| Fedora 30            | 2        | 2.35%   |
| Debian Testing       | 2        | 2.35%   |
| Zorin 16             | 1        | 1.18%   |
| Xubuntu 18.04        | 1        | 1.18%   |
| Ubuntu 22.04         | 1        | 1.18%   |
| Ubuntu 19.10         | 1        | 1.18%   |
| Ubuntu 16.04         | 1        | 1.18%   |
| ROSA R8              | 1        | 1.18%   |
| ROSA R11.1           | 1        | 1.18%   |
| ROSA 12.2            | 1        | 1.18%   |
| Pop!_OS 21.04        | 1        | 1.18%   |
| Manjaro 20.2.1       | 1        | 1.18%   |
| Manjaro              | 1        | 1.18%   |
| Lubuntu 22.04        | 1        | 1.18%   |
| Lubuntu 21.10        | 1        | 1.18%   |
| LMDE 5               | 1        | 1.18%   |
| Linux Mint 20        | 1        | 1.18%   |
| Linux Mint 19.3      | 1        | 1.18%   |
| Linux Mint 19        | 1        | 1.18%   |
| Linux Mint 18.2      | 1        | 1.18%   |
| Kubuntu 20.04        | 1        | 1.18%   |
| KDE neon 18.04       | 1        | 1.18%   |
| Kali 2020.4          | 1        | 1.18%   |
| Garuda Linux Soaring | 1        | 1.18%   |
| Garuda Linux         | 1        | 1.18%   |
| Endless 3.7.8        | 1        | 1.18%   |
| Debian 11            | 1        | 1.18%   |
| Clear Linux 34080    | 1        | 1.18%   |
| Clear Linux 32260    | 1        | 1.18%   |
| Arch                 | 1        | 1.18%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| ROSA         | 17       | 21.79%  |
| Ubuntu       | 15       | 19.23%  |
| Linux Mint   | 11       | 14.1%   |
| KDE neon     | 5        | 6.41%   |
| OpenMandriva | 4        | 5.13%   |
| Fedora       | 4        | 5.13%   |
| Arch         | 4        | 5.13%   |
| Xubuntu      | 3        | 3.85%   |
| Manjaro      | 2        | 2.56%   |
| Garuda Linux | 2        | 2.56%   |
| Debian       | 2        | 2.56%   |
| Clear Linux  | 2        | 2.56%   |
| Zorin        | 1        | 1.28%   |
| Pop!_OS      | 1        | 1.28%   |
| Lubuntu      | 1        | 1.28%   |
| LMDE         | 1        | 1.28%   |
| Kubuntu      | 1        | 1.28%   |
| Kali         | 1        | 1.28%   |
| Endless      | 1        | 1.28%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Desktops | Percent |
|------------------------------------|----------|---------|
| 4.9.60-nrj-desktop-1rosa-x86_64    | 5        | 5.43%   |
| 5.4.0-58-generic                   | 4        | 4.35%   |
| 4.9.20-nrj-desktop-1rosa-x86_64    | 4        | 4.35%   |
| 5.4.0-122-generic                  | 3        | 3.26%   |
| 4.15.0-desktop-45.1rosa-x86_64     | 3        | 3.26%   |
| 5.4.0-66-generic                   | 2        | 2.17%   |
| 5.4.0-54-generic                   | 2        | 2.17%   |
| 5.13.0-39-generic                  | 2        | 2.17%   |
| 5.12.4-desktop-1omv4050            | 2        | 2.17%   |
| 5.10.14-desktop-1omv4002           | 2        | 2.17%   |
| 5.0.0-37-generic                   | 2        | 2.17%   |
| 5.9.13-1006.native                 | 1        | 1.09%   |
| 5.9.0-kali1-amd64                  | 1        | 1.09%   |
| 5.8.12-arch1-1                     | 1        | 1.09%   |
| 5.8.0-50-generic                   | 1        | 1.09%   |
| 5.8.0-44-generic                   | 1        | 1.09%   |
| 5.8.0-25-generic                   | 1        | 1.09%   |
| 5.6.3-arch1-1                      | 1        | 1.09%   |
| 5.4.83-generic-2rosa-x86_64        | 1        | 1.09%   |
| 5.4.18-902.native                  | 1        | 1.09%   |
| 5.4.0-80-generic                   | 1        | 1.09%   |
| 5.4.0-70-generic                   | 1        | 1.09%   |
| 5.4.0-67-generic                   | 1        | 1.09%   |
| 5.4.0-62-generic                   | 1        | 1.09%   |
| 5.4.0-59-generic                   | 1        | 1.09%   |
| 5.4.0-52-generic                   | 1        | 1.09%   |
| 5.4.0-48-generic                   | 1        | 1.09%   |
| 5.4.0-42-generic                   | 1        | 1.09%   |
| 5.4.0-121-generic                  | 1        | 1.09%   |
| 5.4.0-100-generic                  | 1        | 1.09%   |
| 5.3.0-53-generic                   | 1        | 1.09%   |
| 5.3.0-42-generic                   | 1        | 1.09%   |
| 5.3.0-28-generic                   | 1        | 1.09%   |
| 5.3.0-23-generic                   | 1        | 1.09%   |
| 5.2.9-200.fc30.x86_64              | 1        | 1.09%   |
| 5.2.14-200.fc30.x86_64             | 1        | 1.09%   |
| 5.17.5-zen1-2-zen                  | 1        | 1.09%   |
| 5.17.0-1-amd64                     | 1        | 1.09%   |
| 5.16.18-201.fsync.fc35.x86_64      | 1        | 1.09%   |
| 5.16.15-201.fc35.x86_64            | 1        | 1.09%   |
| 5.15.0-37-generic                  | 1        | 1.09%   |
| 5.15.0-3-amd64                     | 1        | 1.09%   |
| 5.15.0-27-generic                  | 1        | 1.09%   |
| 5.14.0-trunk-amd64                 | 1        | 1.09%   |
| 5.13.19-204-tkg-muqss              | 1        | 1.09%   |
| 5.13.0-52-generic                  | 1        | 1.09%   |
| 5.13.0-40-generic                  | 1        | 1.09%   |
| 5.13.0-28-generic                  | 1        | 1.09%   |
| 5.13.0-25-generic                  | 1        | 1.09%   |
| 5.11.6-137-tkg-pds                 | 1        | 1.09%   |
| 5.11.22-2-MANJARO                  | 1        | 1.09%   |
| 5.11.2-1-MANJARO                   | 1        | 1.09%   |
| 5.11.11-144-tkg-bmq                | 1        | 1.09%   |
| 5.11.0-7620-generic                | 1        | 1.09%   |
| 5.11.0-38-generic                  | 1        | 1.09%   |
| 5.11.0-051100rc7-generic           | 1        | 1.09%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 1        | 1.09%   |
| 5.10.16-arch1-1                    | 1        | 1.09%   |
| 5.10.0-13-amd64                    | 1        | 1.09%   |
| 5.0.0-27-generic                   | 1        | 1.09%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 17       | 19.77%  |
| 4.15.0  | 9        | 10.47%  |
| 5.13.0  | 5        | 5.81%   |
| 4.9.60  | 5        | 5.81%   |
| 4.9.20  | 5        | 5.81%   |
| 5.3.0   | 4        | 4.65%   |
| 5.8.0   | 3        | 3.49%   |
| 5.15.0  | 3        | 3.49%   |
| 5.11.0  | 3        | 3.49%   |
| 5.12.4  | 2        | 2.33%   |
| 5.10.14 | 2        | 2.33%   |
| 5.0.0   | 2        | 2.33%   |
| 5.9.13  | 1        | 1.16%   |
| 5.9.0   | 1        | 1.16%   |
| 5.8.12  | 1        | 1.16%   |
| 5.6.3   | 1        | 1.16%   |
| 5.4.83  | 1        | 1.16%   |
| 5.4.18  | 1        | 1.16%   |
| 5.2.9   | 1        | 1.16%   |
| 5.2.14  | 1        | 1.16%   |
| 5.17.5  | 1        | 1.16%   |
| 5.17.0  | 1        | 1.16%   |
| 5.16.18 | 1        | 1.16%   |
| 5.16.15 | 1        | 1.16%   |
| 5.14.0  | 1        | 1.16%   |
| 5.13.19 | 1        | 1.16%   |
| 5.11.6  | 1        | 1.16%   |
| 5.11.22 | 1        | 1.16%   |
| 5.11.2  | 1        | 1.16%   |
| 5.11.11 | 1        | 1.16%   |
| 5.10.74 | 1        | 1.16%   |
| 5.10.16 | 1        | 1.16%   |
| 5.10.0  | 1        | 1.16%   |
| 4.9.76  | 1        | 1.16%   |
| 4.9.155 | 1        | 1.16%   |
| 4.8.0   | 1        | 1.16%   |
| 4.18.0  | 1        | 1.16%   |
| 4.1.34  | 1        | 1.16%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 19       | 22.35%  |
| 4.9     | 11       | 12.94%  |
| 4.15    | 9        | 10.59%  |
| 5.11    | 7        | 8.24%   |
| 5.13    | 6        | 7.06%   |
| 5.10    | 5        | 5.88%   |
| 5.8     | 4        | 4.71%   |
| 5.3     | 4        | 4.71%   |
| 5.15    | 3        | 3.53%   |
| 5.9     | 2        | 2.35%   |
| 5.2     | 2        | 2.35%   |
| 5.17    | 2        | 2.35%   |
| 5.16    | 2        | 2.35%   |
| 5.12    | 2        | 2.35%   |
| 5.0     | 2        | 2.35%   |
| 5.6     | 1        | 1.18%   |
| 5.14    | 1        | 1.18%   |
| 4.8     | 1        | 1.18%   |
| 4.18    | 1        | 1.18%   |
| 4.1     | 1        | 1.18%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 70       | 94.59%  |
| i686   | 4        | 5.41%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 20       | 24.39%  |
| KDE5       | 17       | 20.73%  |
| KDE4       | 10       | 12.2%   |
| Unknown    | 9        | 10.98%  |
| X-Cinnamon | 7        | 8.54%   |
| XFCE       | 5        | 6.1%    |
| KDE        | 5        | 6.1%    |
| MATE       | 4        | 4.88%   |
| Deepin     | 2        | 2.44%   |
| Cinnamon   | 2        | 2.44%   |
| LXQt       | 1        | 1.22%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 66       | 88%     |
| Wayland | 5        | 6.67%   |
| Unknown | 3        | 4%      |
| Tty     | 1        | 1.33%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 37       | 44.58%  |
| SDDM    | 19       | 22.89%  |
| KDM     | 10       | 12.05%  |
| GDM     | 5        | 6.02%   |
| TDM     | 4        | 4.82%   |
| LightDM | 4        | 4.82%   |
| GDM3    | 4        | 4.82%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| en_US       | 25       | 31.65%  |
| Unknown     | 22       | 27.85%  |
| ru_RU       | 11       | 13.92%  |
| lv_LV       | 10       | 12.66%  |
| en_GB       | 4        | 5.06%   |
| C           | 3        | 3.8%    |
| ru_RU.UTF_8 | 1        | 1.27%   |
| osa_US      | 1        | 1.27%   |
| de_DE       | 1        | 1.27%   |
| cv_RU       | 1        | 1.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 52       | 70.27%  |
| EFI  | 22       | 29.73%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 57       | 72.15%  |
| Unknown | 12       | 15.19%  |
| Overlay | 4        | 5.06%   |
| Btrfs   | 4        | 5.06%   |
| Xfs     | 1        | 1.27%   |
| Ext3    | 1        | 1.27%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 43       | 54.43%  |
| GPT     | 19       | 24.05%  |
| MBR     | 17       | 21.52%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 66       | 83.54%  |
| Yes       | 13       | 16.46%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 51       | 65.38%  |
| Yes       | 27       | 34.62%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 17       | 22.97%  |
| Gigabyte Technology | 15       | 20.27%  |
| MSI                 | 12       | 16.22%  |
| ASRock              | 7        | 9.46%   |
| Dell                | 5        | 6.76%   |
| Hewlett-Packard     | 4        | 5.41%   |
| Intel               | 3        | 4.05%   |
| Acer                | 3        | 4.05%   |
| Lenovo              | 1        | 1.35%   |
| IBM                 | 1        | 1.35%   |
| Hardkernel          | 1        | 1.35%   |
| Fujitsu Siemens     | 1        | 1.35%   |
| Foxconn             | 1        | 1.35%   |
| Biostar             | 1        | 1.35%   |
| Acidanthera         | 1        | 1.35%   |
| ABIT                | 1        | 1.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| ASUS All Series                    | 4        | 5.41%   |
| MSI MS-7721                        | 2        | 2.7%    |
| Gigabyte G33M-S2                   | 2        | 2.7%    |
| Gigabyte B550 AORUS PRO V2         | 2        | 2.7%    |
| MSI MS-7C52                        | 1        | 1.35%   |
| MSI MS-7B46                        | 1        | 1.35%   |
| MSI MS-7B33                        | 1        | 1.35%   |
| MSI MS-7996                        | 1        | 1.35%   |
| MSI MS-7850                        | 1        | 1.35%   |
| MSI MS-7846                        | 1        | 1.35%   |
| MSI MS-7758                        | 1        | 1.35%   |
| MSI MS-7693                        | 1        | 1.35%   |
| MSI MS-7583                        | 1        | 1.35%   |
| MSI MS-7519                        | 1        | 1.35%   |
| Lenovo Legion T5 26AMR5 90RC018LBX | 1        | 1.35%   |
| Intel DQ87PG AAG74154-403          | 1        | 1.35%   |
| Intel DH77EB AAG39073-304          | 1        | 1.35%   |
| Intel DB85FL AAG89861-201          | 1        | 1.35%   |
| IBM 8215ZCL                        | 1        | 1.35%   |
| HP ProDesk 600 G1 TWR              | 1        | 1.35%   |
| HP Compaq dc5700 Microtower        | 1        | 1.35%   |
| HP Compaq 8100 Elite CMT PC        | 1        | 1.35%   |
| HP 310-1205uk                      | 1        | 1.35%   |
| Hardkernel ODROID-H2               | 1        | 1.35%   |
| Gigabyte Z87P-D3                   | 1        | 1.35%   |
| Gigabyte Z87-HD3                   | 1        | 1.35%   |
| Gigabyte X570 AORUS ELITE          | 1        | 1.35%   |
| Gigabyte H97-D3H                   | 1        | 1.35%   |
| Gigabyte H61MA-D2V                 | 1        | 1.35%   |
| Gigabyte H61M-S2-B3                | 1        | 1.35%   |
| Gigabyte H55M-D2H                  | 1        | 1.35%   |
| Gigabyte GA-970A-UD3               | 1        | 1.35%   |
| Gigabyte G31M-ES2L                 | 1        | 1.35%   |
| Gigabyte B550I AORUS PRO AX        | 1        | 1.35%   |
| Gigabyte AB350M-DS3H V2            | 1        | 1.35%   |
| Fujitsu Siemens ESPRIMO E5730      | 1        | 1.35%   |
| Foxconn p6-2260ea                  | 1        | 1.35%   |
| Dell OptiPlex GX620                | 1        | 1.35%   |
| Dell OptiPlex GX520                | 1        | 1.35%   |
| Dell OptiPlex 745                  | 1        | 1.35%   |
| Dell OptiPlex 7020                 | 1        | 1.35%   |
| Dell OptiPlex 7010                 | 1        | 1.35%   |
| Biostar NF61D-A2                   | 1        | 1.35%   |
| ASUS ROG STRIX Z370-E GAMING       | 1        | 1.35%   |
| ASUS PRIME Z270-P                  | 1        | 1.35%   |
| ASUS PRIME H310T                   | 1        | 1.35%   |
| ASUS PRIME B350-PLUS               | 1        | 1.35%   |
| ASUS P8P67 LE                      | 1        | 1.35%   |
| ASUS P5QL-E                        | 1        | 1.35%   |
| ASUS P5Q-EM                        | 1        | 1.35%   |
| ASUS P5Q                           | 1        | 1.35%   |
| ASUS P5K PRO                       | 1        | 1.35%   |
| ASUS P5GD1-VM                      | 1        | 1.35%   |
| ASUS Maximus VIII RANGER           | 1        | 1.35%   |
| ASUS M2N-VM DVI                    | 1        | 1.35%   |
| ASUS A88XM-A                       | 1        | 1.35%   |
| ASRock X79 Extreme9                | 1        | 1.35%   |
| ASRock TRX40 Creator               | 1        | 1.35%   |
| ASRock N68C-GS FX                  | 1        | 1.35%   |
| ASRock G31M-GS                     | 1        | 1.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| Dell OptiPlex            | 5        | 6.76%   |
| ASUS All                 | 4        | 5.41%   |
| ASUS PRIME               | 3        | 4.05%   |
| MSI MS-7721              | 2        | 2.7%    |
| HP Compaq                | 2        | 2.7%    |
| Gigabyte G33M-S2         | 2        | 2.7%    |
| Gigabyte B550            | 2        | 2.7%    |
| Acer Aspire              | 2        | 2.7%    |
| MSI MS-7C52              | 1        | 1.35%   |
| MSI MS-7B46              | 1        | 1.35%   |
| MSI MS-7B33              | 1        | 1.35%   |
| MSI MS-7996              | 1        | 1.35%   |
| MSI MS-7850              | 1        | 1.35%   |
| MSI MS-7846              | 1        | 1.35%   |
| MSI MS-7758              | 1        | 1.35%   |
| MSI MS-7693              | 1        | 1.35%   |
| MSI MS-7583              | 1        | 1.35%   |
| MSI MS-7519              | 1        | 1.35%   |
| Lenovo Legion            | 1        | 1.35%   |
| Intel DQ87PG             | 1        | 1.35%   |
| Intel DH77EB             | 1        | 1.35%   |
| Intel DB85FL             | 1        | 1.35%   |
| IBM 8215ZCL              | 1        | 1.35%   |
| HP ProDesk               | 1        | 1.35%   |
| HP 310-1205uk            | 1        | 1.35%   |
| Hardkernel ODROID-H2     | 1        | 1.35%   |
| Gigabyte Z87P-D3         | 1        | 1.35%   |
| Gigabyte Z87-HD3         | 1        | 1.35%   |
| Gigabyte X570            | 1        | 1.35%   |
| Gigabyte H97-D3H         | 1        | 1.35%   |
| Gigabyte H61MA-D2V       | 1        | 1.35%   |
| Gigabyte H61M-S2-B3      | 1        | 1.35%   |
| Gigabyte H55M-D2H        | 1        | 1.35%   |
| Gigabyte GA-970A-UD3     | 1        | 1.35%   |
| Gigabyte G31M-ES2L       | 1        | 1.35%   |
| Gigabyte B550I           | 1        | 1.35%   |
| Gigabyte AB350M-DS3H     | 1        | 1.35%   |
| Fujitsu Siemens ESPRIMO  | 1        | 1.35%   |
| Foxconn p6-2260ea        | 1        | 1.35%   |
| Biostar NF61D-A2         | 1        | 1.35%   |
| ASUS ROG                 | 1        | 1.35%   |
| ASUS P8P67               | 1        | 1.35%   |
| ASUS P5QL-E              | 1        | 1.35%   |
| ASUS P5Q-EM              | 1        | 1.35%   |
| ASUS P5Q                 | 1        | 1.35%   |
| ASUS P5K                 | 1        | 1.35%   |
| ASUS P5GD1-VM            | 1        | 1.35%   |
| ASUS Maximus             | 1        | 1.35%   |
| ASUS M2N-VM              | 1        | 1.35%   |
| ASUS A88XM-A             | 1        | 1.35%   |
| ASRock X79               | 1        | 1.35%   |
| ASRock TRX40             | 1        | 1.35%   |
| ASRock N68C-GS           | 1        | 1.35%   |
| ASRock G31M-GS           | 1        | 1.35%   |
| ASRock FM2A88X           | 1        | 1.35%   |
| ASRock FM2A85X-ITX       | 1        | 1.35%   |
| ASRock ALiveXFire-eSATA2 | 1        | 1.35%   |
| Acidanthera MacPro7      | 1        | 1.35%   |
| Acer Veriton             | 1        | 1.35%   |
| ABIT IP35-E              | 1        | 1.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 11       | 14.86%  |
| 2012 | 8        | 10.81%  |
| 2007 | 8        | 10.81%  |
| 2008 | 6        | 8.11%   |
| 2018 | 5        | 6.76%   |
| 2015 | 5        | 6.76%   |
| 2009 | 5        | 6.76%   |
| 2020 | 4        | 5.41%   |
| 2011 | 4        | 5.41%   |
| 2006 | 4        | 5.41%   |
| 2019 | 3        | 4.05%   |
| 2017 | 3        | 4.05%   |
| 2014 | 3        | 4.05%   |
| 2010 | 2        | 2.7%    |
| 2021 | 1        | 1.35%   |
| 2016 | 1        | 1.35%   |
| 2004 | 1        | 1.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 74       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 74       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 74       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 3.01-4.0    | 18       | 23.38%  |
| 8.01-16.0   | 16       | 20.78%  |
| 4.01-8.0    | 12       | 15.58%  |
| 32.01-64.0  | 10       | 12.99%  |
| 16.01-24.0  | 10       | 12.99%  |
| 1.01-2.0    | 4        | 5.19%   |
| 24.01-32.0  | 3        | 3.9%    |
| 2.01-3.0    | 3        | 3.9%    |
| 64.01-256.0 | 1        | 1.3%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 29       | 33.33%  |
| 2.01-3.0   | 18       | 20.69%  |
| 0.51-1.0   | 17       | 19.54%  |
| 4.01-8.0   | 10       | 11.49%  |
| 3.01-4.0   | 9        | 10.34%  |
| 8.01-16.0  | 3        | 3.45%   |
| 16.01-24.0 | 1        | 1.15%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 30       | 37.97%  |
| 2      | 23       | 29.11%  |
| 3      | 16       | 20.25%  |
| 4      | 8        | 10.13%  |
| 6      | 2        | 2.53%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 38       | 50.67%  |
| Yes       | 37       | 49.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 74       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 55       | 73.33%  |
| Yes       | 20       | 26.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 63       | 84%     |
| Yes       | 12       | 16%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Latvia  | 74       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City       | Desktops | Percent |
|------------|----------|---------|
| Riga       | 49       | 62.82%  |
| Ventspils  | 4        | 5.13%   |
| Salaspils  | 3        | 3.85%   |
| Jelgava    | 3        | 3.85%   |
| Talsi      | 2        | 2.56%   |
| Jūrmala   | 2        | 2.56%   |
| Daugavpils | 2        | 2.56%   |
| Adazi      | 2        | 2.56%   |
| Ragana     | 1        | 1.28%   |
| Ogre       | 1        | 1.28%   |
| Limbaži   | 1        | 1.28%   |
| Liepāja   | 1        | 1.28%   |
| Lielvārde | 1        | 1.28%   |
| Kuldīga   | 1        | 1.28%   |
| Iecava     | 1        | 1.28%   |
| Dreilini   | 1        | 1.28%   |
| Carnikava  | 1        | 1.28%   |
| Brankas    | 1        | 1.28%   |
| Bauska     | 1        | 1.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| WDC                   | 34       | 51     | 24.46%  |
| Seagate               | 32       | 47     | 23.02%  |
| Samsung Electronics   | 25       | 38     | 17.99%  |
| Kingston              | 10       | 17     | 7.19%   |
| Crucial               | 9        | 13     | 6.47%   |
| Hitachi               | 6        | 8      | 4.32%   |
| Toshiba               | 5        | 5      | 3.6%    |
| Intel                 | 4        | 7      | 2.88%   |
| GOODRAM               | 3        | 4      | 2.16%   |
| OCZ                   | 2        | 3      | 1.44%   |
| Unknown               | 1        | 1      | 0.72%   |
| Realtek Semiconductor | 1        | 1      | 0.72%   |
| Patriot               | 1        | 1      | 0.72%   |
| Mushkin               | 1        | 2      | 0.72%   |
| Maxtor                | 1        | 1      | 0.72%   |
| KingFast              | 1        | 2      | 0.72%   |
| IBM/Hitachi           | 1        | 1      | 0.72%   |
| GLOWAY                | 1        | 1      | 0.72%   |
| A-DATA Technology     | 1        | 2      | 0.72%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST1000DM010-2EP102 1TB   | 4        | 2.47%   |
| Kingston SA400S37240G 240GB SSD  | 4        | 2.47%   |
| WDC WD2000JD-00HBB0 200GB        | 3        | 1.85%   |
| Seagate ST500DM005 HD502HJ 500GB | 3        | 1.85%   |
| Samsung NVMe SSD Drive 500GB     | 3        | 1.85%   |
| Crucial CT500MX500SSD1 500GB     | 3        | 1.85%   |
| Crucial CT1000MX500SSD1 1TB      | 3        | 1.85%   |
| WDC WD5002AALX-00J37A0 500GB     | 2        | 1.23%   |
| WDC WD5000AAKX-22ERMA0 500GB     | 2        | 1.23%   |
| WDC WD5000AAKX-00ERMA0 500GB     | 2        | 1.23%   |
| WDC WD5000AAKX-001CA0 500GB      | 2        | 1.23%   |
| WDC WD20EARX-00PASB0 2TB         | 2        | 1.23%   |
| WDC WD10EZEX-00BN5A0 1TB         | 2        | 1.23%   |
| Seagate ST3500418AS 500GB        | 2        | 1.23%   |
| Seagate ST250DM000-1BD141 250GB  | 2        | 1.23%   |
| Seagate ST2000DM001-1CH164 2TB   | 2        | 1.23%   |
| Seagate ST1000DX001-1CM162 1TB   | 2        | 1.23%   |
| Seagate ST1000DM003-1SB102 1TB   | 2        | 1.23%   |
| Samsung SSD 970 EVO Plus 500GB   | 2        | 1.23%   |
| Samsung SSD 860 EVO 500GB        | 2        | 1.23%   |
| Samsung SSD 860 EVO 1TB          | 2        | 1.23%   |
| Samsung SSD 650 120GB            | 2        | 1.23%   |
| Samsung SP2504C 250GB            | 2        | 1.23%   |
| Samsung HD501LJ 500GB            | 2        | 1.23%   |
| Samsung HD103UJ 1TB              | 2        | 1.23%   |
| GOODRAM SSDPR-CX400-128-G2 128GB | 2        | 1.23%   |
| Crucial CT480BX500SSD1 480GB     | 2        | 1.23%   |
| WDC WDS500G3X0C-00SJG0 500GB     | 1        | 0.62%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 1        | 0.62%   |
| WDC WDS480G2G0A-00JH30 480GB SSD | 1        | 0.62%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD | 1        | 0.62%   |
| WDC WDS100T2B0C-00PXH0 1TB       | 1        | 0.62%   |
| WDC WDS100T2B0B-00YS70 1TB SSD   | 1        | 0.62%   |
| WDC WD800JD-60MSA1 80GB          | 1        | 0.62%   |
| WDC WD6003FZBX-00K5WB0 6TB       | 1        | 0.62%   |
| WDC WD5001AALS-00E3A0 500GB      | 1        | 0.62%   |
| WDC WD5000AAKX-08U6AA0 500GB     | 1        | 0.62%   |
| WDC WD5000AADS-00S9B0 500GB      | 1        | 0.62%   |
| WDC WD40EZRZ-00GXCB0 4TB         | 1        | 0.62%   |
| WDC WD2500KS-00MJB0 250GB        | 1        | 0.62%   |
| WDC WD2500AAKS-60L9A0 250GB      | 1        | 0.62%   |
| WDC WD2500AAJS-07M0A0 250GB      | 1        | 0.62%   |
| WDC WD1600AAJS-00B4A0 160GB      | 1        | 0.62%   |
| WDC WD10SPZX-21Z10T0 1TB         | 1        | 0.62%   |
| WDC WD10EZRX-00DC0B0 1TB         | 1        | 0.62%   |
| WDC WD10EZEX-75M2NA0 1TB         | 1        | 0.62%   |
| WDC WD10EZEX-00KUWA0 1TB         | 1        | 0.62%   |
| WDC WD10EARS-003BB1 1TB          | 1        | 0.62%   |
| WDC WD10EALX-759BA1 1TB          | 1        | 0.62%   |
| WDC WD10EADS-00P8B0 1TB          | 1        | 0.62%   |
| WDC WD101KRYZ-01JPDB1 10TB       | 1        | 0.62%   |
| WDC WD1005FBYZ-01YCBB2 1TB       | 1        | 0.62%   |
| WDC WD1003FZEX-00RLFA0 1TB       | 1        | 0.62%   |
| Unknown MMC Card  7GB            | 1        | 0.62%   |
| Toshiba MQ01ABD050 500GB         | 1        | 0.62%   |
| Toshiba MK3021GAS 32GB           | 1        | 0.62%   |
| Toshiba DT01ACA300 3TB           | 1        | 0.62%   |
| Toshiba DT01ACA100 1TB           | 1        | 0.62%   |
| Toshiba DT01ACA050 500GB         | 1        | 0.62%   |
| Seagate ST500DM002-1BD142 500GB  | 1        | 0.62%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 32       | 47     | 37.65%  |
| WDC                 | 29       | 43     | 34.12%  |
| Samsung Electronics | 11       | 14     | 12.94%  |
| Hitachi             | 6        | 8      | 7.06%   |
| Toshiba             | 5        | 5      | 5.88%   |
| Maxtor              | 1        | 1      | 1.18%   |
| IBM/Hitachi         | 1        | 1      | 1.18%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 10       | 13     | 21.74%  |
| Kingston            | 10       | 17     | 21.74%  |
| Crucial             | 9        | 13     | 19.57%  |
| WDC                 | 4        | 5      | 8.7%    |
| Intel               | 3        | 6      | 6.52%   |
| GOODRAM             | 3        | 4      | 6.52%   |
| OCZ                 | 2        | 3      | 4.35%   |
| Patriot             | 1        | 1      | 2.17%   |
| Mushkin             | 1        | 2      | 2.17%   |
| KingFast            | 1        | 2      | 2.17%   |
| GLOWAY              | 1        | 1      | 2.17%   |
| A-DATA Technology   | 1        | 2      | 2.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 62       | 119    | 56.36%  |
| SSD  | 36       | 69     | 32.73%  |
| NVMe | 11       | 16     | 10%     |
| MMC  | 1        | 1      | 0.91%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 72       | 186    | 83.72%  |
| NVMe | 11       | 16     | 12.79%  |
| SAS  | 2        | 2      | 2.33%   |
| MMC  | 1        | 1      | 1.16%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 60       | 129    | 58.82%  |
| 0.51-1.0   | 30       | 44     | 29.41%  |
| 1.01-2.0   | 7        | 10     | 6.86%   |
| 2.01-3.0   | 2        | 2      | 1.96%   |
| 4.01-10.0  | 2        | 2      | 1.96%   |
| 3.01-4.0   | 1        | 1      | 0.98%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 25       | 30.12%  |
| 251-500        | 11       | 13.25%  |
| 1001-2000      | 11       | 13.25%  |
| 51-100         | 9        | 10.84%  |
| 501-1000       | 8        | 9.64%   |
| More than 3000 | 5        | 6.02%   |
| 21-50          | 5        | 6.02%   |
| 2001-3000      | 5        | 6.02%   |
| 1-20           | 3        | 3.61%   |
| Unknown        | 1        | 1.2%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 34       | 38.64%  |
| 101-250   | 15       | 17.05%  |
| 251-500   | 11       | 12.5%   |
| 21-50     | 9        | 10.23%  |
| 51-100    | 7        | 7.95%   |
| 501-1000  | 6        | 6.82%   |
| 1001-2000 | 3        | 3.41%   |
| 2001-3000 | 2        | 2.27%   |
| Unknown   | 1        | 1.14%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD20EARX-00PASB0 2TB              | 2        | 3      | 6.9%    |
| WDC WD2000JD-00HBB0 200GB             | 2        | 3      | 6.9%    |
| Seagate ST1000DM003-1SB102 1TB        | 2        | 3      | 6.9%    |
| Samsung Electronics SP2504C 250GB     | 2        | 2      | 6.9%    |
| Samsung Electronics HD501LJ 500GB     | 2        | 3      | 6.9%    |
| WDC WDS500G3X0C-00SJG0 500GB          | 1        | 1      | 3.45%   |
| WDC WD800JD-60MSA1 80GB               | 1        | 1      | 3.45%   |
| WDC WD5002AALX-00J37A0 500GB          | 1        | 1      | 3.45%   |
| WDC WD5001AALS-00E3A0 500GB           | 1        | 1      | 3.45%   |
| WDC WD2500AAKS-60L9A0 250GB           | 1        | 1      | 3.45%   |
| WDC WD1600AAJS-00B4A0 160GB           | 1        | 1      | 3.45%   |
| Toshiba DT01ACA100 1TB                | 1        | 1      | 3.45%   |
| Seagate ST3500820AS 500GB             | 1        | 1      | 3.45%   |
| Seagate ST3500413AS 500GB             | 1        | 1      | 3.45%   |
| Seagate ST3500312CS 500GB             | 1        | 1      | 3.45%   |
| Seagate ST3250620AS 250GB             | 1        | 1      | 3.45%   |
| Seagate ST3250312AS 250GB             | 1        | 1      | 3.45%   |
| Seagate ST31000528AS 1TB              | 1        | 1      | 3.45%   |
| Seagate ST3000DM001-9YN166 3TB        | 1        | 1      | 3.45%   |
| Seagate ST1000DX001-1CM162 1TB        | 1        | 1      | 3.45%   |
| Samsung Electronics SSD 970 EVO 500GB | 1        | 1      | 3.45%   |
| Kingston SV300S37A60G 64GB SSD        | 1        | 1      | 3.45%   |
| Hitachi HTS542525K9A300 250GB         | 1        | 1      | 3.45%   |
| A-DATA Technology SU800NS38 512GB SSD | 1        | 2      | 3.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 9        | 12     | 33.33%  |
| Seagate             | 9        | 11     | 33.33%  |
| Samsung Electronics | 5        | 6      | 18.52%  |
| Toshiba             | 1        | 1      | 3.7%    |
| Kingston            | 1        | 1      | 3.7%    |
| Hitachi             | 1        | 1      | 3.7%    |
| A-DATA Technology   | 1        | 2      | 3.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 9        | 11     | 39.13%  |
| WDC                 | 8        | 11     | 34.78%  |
| Samsung Electronics | 4        | 5      | 17.39%  |
| Toshiba             | 1        | 1      | 4.35%   |
| Hitachi             | 1        | 1      | 4.35%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 16       | 29     | 80%     |
| NVMe | 2        | 2      | 10%     |
| SSD  | 2        | 3      | 10%     |

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
| Detected | 41       | 98     | 44.09%  |
| Works    | 33       | 73     | 35.48%  |
| Malfunc  | 19       | 34     | 20.43%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 52       | 54.17%  |
| AMD                              | 18       | 18.75%  |
| Samsung Electronics              | 8        | 8.33%   |
| JMicron Technology               | 7        | 7.29%   |
| Marvell Technology Group         | 4        | 4.17%   |
| Nvidia                           | 3        | 3.13%   |
| SanDisk                          | 2        | 2.08%   |
| Silicon Integrated Systems [SiS] | 1        | 1.04%   |
| Realtek Semiconductor            | 1        | 1.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 10       | 7.81%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 9        | 7.03%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 7        | 5.47%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6        | 4.69%   |
| JMicron JMB368 IDE controller                                                           | 5        | 3.91%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 3.91%   |
| AMD 500 Series Chipset SATA Controller                                                  | 4        | 3.13%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3        | 2.34%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3        | 2.34%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 3        | 2.34%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 3        | 2.34%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3        | 2.34%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3        | 2.34%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 3        | 2.34%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 3        | 2.34%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3        | 2.34%   |
| AMD FCH IDE Controller                                                                  | 3        | 2.34%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 1.56%   |
| Nvidia MCP61 IDE                                                                        | 2        | 1.56%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2        | 1.56%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 1.56%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2        | 1.56%   |
| Intel 82801IB (ICH9) 4 port SATA Controller [AHCI mode]                                 | 2        | 1.56%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 2        | 1.56%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 2        | 1.56%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 2        | 1.56%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2        | 1.56%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2        | 1.56%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                             | 1        | 0.78%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 1        | 0.78%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1        | 0.78%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 0.78%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.78%   |
| Realtek Realtek Non-Volatile memory controller                                          | 1        | 0.78%   |
| Nvidia MCP67 IDE Controller                                                             | 1        | 0.78%   |
| Nvidia MCP67 AHCI Controller                                                            | 1        | 0.78%   |
| Marvell Group 88SE9220 PCIe 2.0 x2 2-port SATA 6 Gb/s RAID Controller                   | 1        | 0.78%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 1        | 0.78%   |
| Marvell Group 88SE912x SATA 6Gb/s Controller [IDE mode]                                 | 1        | 0.78%   |
| Marvell Group 88SE912x IDE Controller                                                   | 1        | 0.78%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1        | 0.78%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                               | 1        | 0.78%   |
| Intel SSD 660P Series                                                                   | 1        | 0.78%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1        | 0.78%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 0.78%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 1        | 0.78%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 1        | 0.78%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 1        | 0.78%   |
| Intel 82801FB/FW (ICH6/ICH6W) SATA Controller                                           | 1        | 0.78%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                                | 1        | 0.78%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 0.78%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 0.78%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 1        | 0.78%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1        | 0.78%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1        | 0.78%   |
| AMD SB600 Non-Raid-5 SATA                                                               | 1        | 0.78%   |
| AMD SB600 IDE                                                                           | 1        | 0.78%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1        | 0.78%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 52       | 55.32%  |
| IDE  | 31       | 32.98%  |
| NVMe | 11       | 11.7%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 53       | 71.62%  |
| AMD    | 21       | 28.38%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Core i5-4570 CPU @ 3.20GHz               | 4        | 5.41%   |
| Intel Core i3-3220 CPU @ 3.30GHz               | 3        | 4.05%   |
| Intel Pentium D CPU 3.40GHz                    | 2        | 2.7%    |
| Intel Pentium D CPU 2.80GHz                    | 2        | 2.7%    |
| Intel Core i7-4770 CPU @ 3.40GHz               | 2        | 2.7%    |
| Intel Core i5-4460 CPU @ 3.20GHz               | 2        | 2.7%    |
| Intel Core i5 CPU 650 @ 3.20GHz                | 2        | 2.7%    |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz          | 2        | 2.7%    |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz           | 2        | 2.7%    |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz           | 2        | 2.7%    |
| Intel Core 2 CPU 6300 @ 1.86GHz                | 2        | 2.7%    |
| AMD Ryzen 5 5600X 6-Core Processor             | 2        | 2.7%    |
| AMD A8-7600 Radeon R7, 10 Compute Cores 4C+6G  | 2        | 2.7%    |
| AMD A8-6600K APU with Radeon HD Graphics       | 2        | 2.7%    |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz    | 1        | 1.35%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz    | 1        | 1.35%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz    | 1        | 1.35%   |
| Intel Pentium Dual CPU E2220 @ 2.40GHz         | 1        | 1.35%   |
| Intel Pentium CPU G620 @ 2.60GHz               | 1        | 1.35%   |
| Intel Pentium 4 CPU 2.66GHz                    | 1        | 1.35%   |
| Intel Core i7-9700K CPU @ 3.60GHz              | 1        | 1.35%   |
| Intel Core i7-8700T CPU @ 2.40GHz              | 1        | 1.35%   |
| Intel Core i7-8700K CPU @ 3.70GHz              | 1        | 1.35%   |
| Intel Core i7-6700K CPU @ 4.00GHz              | 1        | 1.35%   |
| Intel Core i7-4770K CPU @ 3.50GHz              | 1        | 1.35%   |
| Intel Core i7-4765T CPU @ 2.00GHz              | 1        | 1.35%   |
| Intel Core i7-3930K CPU @ 3.20GHz              | 1        | 1.35%   |
| Intel Core i7-2700K CPU @ 3.50GHz              | 1        | 1.35%   |
| Intel Core i7 CPU 860 @ 2.80GHz                | 1        | 1.35%   |
| Intel Core i5-8600K CPU @ 3.60GHz              | 1        | 1.35%   |
| Intel Core i5-8400 CPU @ 2.80GHz               | 1        | 1.35%   |
| Intel Core i5-7600K CPU @ 3.80GHz              | 1        | 1.35%   |
| Intel Core i5-4670K CPU @ 3.40GHz              | 1        | 1.35%   |
| Intel Core i5-2500K CPU @ 3.30GHz              | 1        | 1.35%   |
| Intel Core i3-6100 CPU @ 3.70GHz               | 1        | 1.35%   |
| Intel Core i3-4170 CPU @ 3.70GHz               | 1        | 1.35%   |
| Intel Core i3-4160 CPU @ 3.60GHz               | 1        | 1.35%   |
| Intel Core i3-2120 CPU @ 3.30GHz               | 1        | 1.35%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz          | 1        | 1.35%   |
| Intel Core 2 Duo CPU E8200 @ 2.66GHz           | 1        | 1.35%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz           | 1        | 1.35%   |
| Intel Celeron J4105 CPU @ 1.50GHz              | 1        | 1.35%   |
| AMD Ryzen Threadripper 3960X 24-Core Processor | 1        | 1.35%   |
| AMD Ryzen 7 5800 8-Core Processor              | 1        | 1.35%   |
| AMD Ryzen 7 3700X 8-Core Processor             | 1        | 1.35%   |
| AMD Ryzen 5 3600XT 6-Core Processor            | 1        | 1.35%   |
| AMD Ryzen 5 3600 6-Core Processor              | 1        | 1.35%   |
| AMD Ryzen 5 1600X Six-Core Processor           | 1        | 1.35%   |
| AMD Ryzen 5 1500X Quad-Core Processor          | 1        | 1.35%   |
| AMD FX-6350 Six-Core Processor                 | 1        | 1.35%   |
| AMD FX-6200 Six-Core Processor                 | 1        | 1.35%   |
| AMD Athlon II X2 260 Processor                 | 1        | 1.35%   |
| AMD Athlon II X2 245e Processor                | 1        | 1.35%   |
| AMD Athlon 64 X2 Dual Core Processor 6000+     | 1        | 1.35%   |
| AMD Athlon 64 X2 Dual Core Processor 5000+     | 1        | 1.35%   |
| AMD Athlon 64 X2 Dual Core Processor 4600+     | 1        | 1.35%   |
| AMD A8-5500 APU with Radeon HD Graphics        | 1        | 1.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 13       | 17.57%  |
| Intel Core i7           | 11       | 14.86%  |
| Intel Core i3           | 7        | 9.46%   |
| Intel Core 2 Duo        | 6        | 8.11%   |
| AMD Ryzen 5             | 6        | 8.11%   |
| AMD A8                  | 5        | 6.76%   |
| Intel Pentium D         | 4        | 5.41%   |
| Intel Pentium Dual-Core | 3        | 4.05%   |
| Intel Core 2 Quad       | 3        | 4.05%   |
| AMD Athlon 64 X2        | 3        | 4.05%   |
| Intel Core 2            | 2        | 2.7%    |
| AMD Ryzen 7             | 2        | 2.7%    |
| AMD FX                  | 2        | 2.7%    |
| AMD Athlon II X2        | 2        | 2.7%    |
| Intel Pentium Dual      | 1        | 1.35%   |
| Intel Pentium 4         | 1        | 1.35%   |
| Intel Pentium           | 1        | 1.35%   |
| Intel Celeron           | 1        | 1.35%   |
| AMD Ryzen Threadripper  | 1        | 1.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 34       | 45.33%  |
| 4       | 22       | 29.33%  |
| 6       | 9        | 12%     |
| 8       | 3        | 4%      |
| 3       | 3        | 4%      |
| 1       | 2        | 2.67%   |
| 24      | 1        | 1.33%   |
| Unknown | 1        | 1.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 74       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 40       | 53.33%  |
| 2       | 34       | 45.33%  |
| Unknown | 1        | 1.33%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 73       | 98.65%  |
| Unknown        | 1        | 1.35%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 11       | 14.67%  |
| Unknown    | 10       | 13.33%  |
| 0x1067a    | 7        | 9.33%   |
| 0x206a7    | 4        | 5.33%   |
| 0x10676    | 4        | 5.33%   |
| 0x906ea    | 3        | 4%      |
| 0x08701021 | 3        | 4%      |
| 0x06001119 | 3        | 4%      |
| 0xf47      | 2        | 2.67%   |
| 0x6f2      | 2        | 2.67%   |
| 0x506e3    | 2        | 2.67%   |
| 0x306a9    | 2        | 2.67%   |
| 0x0a201009 | 2        | 2.67%   |
| 0x06003106 | 2        | 2.67%   |
| 0x010000c8 | 2        | 2.67%   |
| 0xf65      | 1        | 1.33%   |
| 0xf64      | 1        | 1.33%   |
| 0xf41      | 1        | 1.33%   |
| 0x906ed    | 1        | 1.33%   |
| 0x906e9    | 1        | 1.33%   |
| 0x706a1    | 1        | 1.33%   |
| 0x6fd      | 1        | 1.33%   |
| 0x6fb      | 1        | 1.33%   |
| 0x206d6    | 1        | 1.33%   |
| 0x20655    | 1        | 1.33%   |
| 0x20652    | 1        | 1.33%   |
| 0x106e5    | 1        | 1.33%   |
| 0x08001137 | 1        | 1.33%   |
| 0x08001126 | 1        | 1.33%   |
| 0x06000852 | 1        | 1.33%   |
| 0x0600063e | 1        | 1.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 13       | 17.57%  |
| Penryn        | 11       | 14.86%  |
| KabyLake      | 6        | 8.11%   |
| SandyBridge   | 5        | 6.76%   |
| NetBurst      | 5        | 6.76%   |
| Zen 2         | 4        | 5.41%   |
| Piledriver    | 4        | 5.41%   |
| Core          | 4        | 5.41%   |
| Zen 3         | 3        | 4.05%   |
| K8 Hammer     | 3        | 4.05%   |
| IvyBridge     | 3        | 4.05%   |
| Zen           | 2        | 2.7%    |
| Westmere      | 2        | 2.7%    |
| Steamroller   | 2        | 2.7%    |
| Skylake       | 2        | 2.7%    |
| K10           | 2        | 2.7%    |
| Nehalem       | 1        | 1.35%   |
| Goldmont plus | 1        | 1.35%   |
| Bulldozer     | 1        | 1.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 35       | 43.21%  |
| AMD    | 24       | 29.63%  |
| Intel  | 22       | 27.16%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5        | 5.88%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 2        | 2.35%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 2        | 2.35%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 2.35%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 2.35%   |
| Nvidia GF106 [GeForce GTS 450]                                              | 2        | 2.35%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 2.35%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 2.35%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 2        | 2.35%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2        | 2.35%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 2        | 2.35%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 2.35%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 2.35%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 2        | 2.35%   |
| AMD Richland [Radeon HD 8570D]                                              | 2        | 2.35%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 2        | 2.35%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 2.35%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 2        | 2.35%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 1.18%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 1.18%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 1.18%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 1.18%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 1        | 1.18%   |
| Nvidia NV44 [GeForce 6200 SE TurboCache]                                    | 1        | 1.18%   |
| Nvidia GT216 [GeForce GT 220]                                               | 1        | 1.18%   |
| Nvidia GT200 [GeForce GTX 260]                                              | 1        | 1.18%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 1.18%   |
| Nvidia GP106 [GeForce GTX 1060 6GB Rev. 2]                                  | 1        | 1.18%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 1.18%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 1.18%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 1.18%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 1        | 1.18%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.18%   |
| Nvidia GK208B [GeForce GT 720]                                              | 1        | 1.18%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 1        | 1.18%   |
| Nvidia GF114 [GeForce GTX 560]                                              | 1        | 1.18%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 1.18%   |
| Nvidia GF108 [GeForce GT 430]                                               | 1        | 1.18%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 1        | 1.18%   |
| Nvidia G98 [Quadro NVS 450]                                                 | 1        | 1.18%   |
| Nvidia G94 [GeForce 9600 GT]                                                | 1        | 1.18%   |
| Nvidia G92 [GeForce 8800 GT]                                                | 1        | 1.18%   |
| Nvidia G84 [GeForce 8600 GT]                                                | 1        | 1.18%   |
| Nvidia G71GL [Quadro FX 3500]                                               | 1        | 1.18%   |
| Intel HD Graphics 530                                                       | 1        | 1.18%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 1.18%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 1.18%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 1        | 1.18%   |
| AMD Trinity [Radeon HD 7560D]                                               | 1        | 1.18%   |
| AMD RV730 PRO [Radeon HD 4650]                                              | 1        | 1.18%   |
| AMD RV710 [Radeon HD 4550]                                                  | 1        | 1.18%   |
| AMD RV635 [Radeon HD 3650/3750/4570/4580]                                   | 1        | 1.18%   |
| AMD RV610 [Radeon HD 2400 PRO/XT]                                           | 1        | 1.18%   |
| AMD RV560 [Radeon X1650 XT] (Secondary)                                     | 1        | 1.18%   |
| AMD RV560 [Radeon X1650 XT]                                                 | 1        | 1.18%   |
| AMD RV530 [Radeon X1600] (Secondary)                                        | 1        | 1.18%   |
| AMD RV530 [Radeon X1600 PRO]                                                | 1        | 1.18%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                   | 1        | 1.18%   |
| AMD R480 [Radeon X800 GTO2/XL] (Secondary)                                  | 1        | 1.18%   |
| AMD R480 [Radeon X800 GTO2/XL]                                              | 1        | 1.18%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 32       | 42.67%  |
| 1 x AMD        | 19       | 25.33%  |
| 1 x Intel      | 17       | 22.67%  |
| 2 x AMD        | 3        | 4%      |
| Intel + Nvidia | 2        | 2.67%   |
| 2 x Nvidia     | 1        | 1.33%   |
| Intel + AMD    | 1        | 1.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 54       | 72%     |
| Proprietary | 18       | 24%     |
| Unknown     | 3        | 4%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 20       | 26.32%  |
| 0.01-0.5   | 19       | 25%     |
| 0.51-1.0   | 13       | 17.11%  |
| 5.01-6.0   | 7        | 9.21%   |
| 3.01-4.0   | 7        | 9.21%   |
| 1.01-2.0   | 6        | 7.89%   |
| 7.01-8.0   | 3        | 3.95%   |
| 2.01-3.0   | 1        | 1.32%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 13       | 17.57%  |
| Goldstar             | 12       | 16.22%  |
| Philips              | 8        | 10.81%  |
| BenQ                 | 7        | 9.46%   |
| Dell                 | 6        | 8.11%   |
| Hewlett-Packard      | 5        | 6.76%   |
| AOC                  | 4        | 5.41%   |
| Ancor Communications | 4        | 5.41%   |
| ViewSonic            | 2        | 2.7%    |
| Unknown              | 2        | 2.7%    |
| NEC Computers        | 2        | 2.7%    |
| LG Electronics       | 2        | 2.7%    |
| Lenovo               | 2        | 2.7%    |
| Arnos Instruments    | 2        | 2.7%    |
| Plain Tree Systems   | 1        | 1.35%   |
| HYO                  | 1        | 1.35%   |
| FUS                  | 1        | 1.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar L194WT GSM4B06 1440x900 408x255mm 18.9-inch                  | 3        | 3.7%    |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch              | 2        | 2.47%   |
| LG Electronics LCD Monitor LG TV 1920x1080                            | 2        | 2.47%   |
| BenQ XL2411Z BNQ7F31 1920x1080 531x298mm 24.0-inch                    | 2        | 2.47%   |
| ViewSonic VA703-3Series VSC631E 1280x1024 338x270mm 17.0-inch         | 1        | 1.23%   |
| ViewSonic VA503 SERIES VSCEF1D 1024x768 304x228mm 15.0-inch           | 1        | 1.23%   |
| Unknown LCD Monitor Sharp LL-S201A 1920x1080                          | 1        | 1.23%   |
| Unknown LCD Monitor HYO DUAL-DVI 2560x1440                            | 1        | 1.23%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 470x300mm 22.0-inch  | 1        | 1.23%   |
| Samsung Electronics SyncMaster SAM036C 1920x1200 550x343mm 25.5-inch  | 1        | 1.23%   |
| Samsung Electronics SyncMaster SAM02F6 1280x1024 338x270mm 17.0-inch  | 1        | 1.23%   |
| Samsung Electronics SyncMaster SAM026E 1280x1024 376x301mm 19.0-inch  | 1        | 1.23%   |
| Samsung Electronics SyncMaster SAM0259 1280x1024 380x300mm 19.1-inch  | 1        | 1.23%   |
| Samsung Electronics SyncMaster SAM0217 1280x1024 376x301mm 19.0-inch  | 1        | 1.23%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch  | 1        | 1.23%   |
| Samsung Electronics SA300/SA350 SAM0793 1920x1080 531x299mm 24.0-inch | 1        | 1.23%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1        | 1.23%   |
| Samsung Electronics S24E391 SAM0C12 1920x1080 521x293mm 23.5-inch     | 1        | 1.23%   |
| Samsung Electronics S24E390 SAM0C1A 1920x1080 521x293mm 23.5-inch     | 1        | 1.23%   |
| Samsung Electronics S23B350 SAM08D5 1920x1080 510x287mm 23.0-inch     | 1        | 1.23%   |
| Samsung Electronics LCD Monitor SyncMaster                            | 1        | 1.23%   |
| Plain Tree Systems 782 PTS1017 1280x1024 337x270mm 17.0-inch          | 1        | 1.23%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 1        | 1.23%   |
| Philips 227E4Q PHLC0A9 1920x1080 477x268mm 21.5-inch                  | 1        | 1.23%   |
| Philips 220VW PHL0853 1680x1050 474x296mm 22.0-inch                   | 1        | 1.23%   |
| Philips 220S4L PHL08BE 1680x1050 474x296mm 22.0-inch                  | 1        | 1.23%   |
| Philips 206VL PHLC08C 1600x900 443x249mm 20.0-inch                    | 1        | 1.23%   |
| Philips 200WB PHL0842 1680x1050 433x271mm 20.1-inch                   | 1        | 1.23%   |
| NEC Computers LCD Monitor LCD22WV 1680x1050                           | 1        | 1.23%   |
| NEC Computers LCD Monitor LCD1770NX                                   | 1        | 1.23%   |
| LG Electronics LCD Monitor LG TV 3840x2160                            | 1        | 1.23%   |
| Lenovo P24q-10 LEN61A5 2560x1440 527x296mm 23.8-inch                  | 1        | 1.23%   |
| Lenovo LEN L171 LEN240B 1280x1024 340x270mm 17.1-inch                 | 1        | 1.23%   |
| HYO DUAL-DVI HYO049B 2560x1440 600x340mm 27.2-inch                    | 1        | 1.23%   |
| Hewlett-Packard TouchSmart HWP4109 1600x900 440x250mm 19.9-inch       | 1        | 1.23%   |
| Hewlett-Packard LE1711 HWP2856 1280x1024 340x270mm 17.1-inch          | 1        | 1.23%   |
| Hewlett-Packard L2245w HWP26FC 1680x1050 473x296mm 22.0-inch          | 1        | 1.23%   |
| Hewlett-Packard L1950 HWP26E8 1280x1024 380x300mm 19.1-inch           | 1        | 1.23%   |
| Hewlett-Packard 2311 HWP2939 1920x1080 509x286mm 23.0-inch            | 1        | 1.23%   |
| Goldstar W2600 GSM5675 1920x1200 550x340mm 25.5-inch                  | 1        | 1.23%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 1        | 1.23%   |
| Goldstar M2252D GSM60AC 1920x1080 531x299mm 24.0-inch                 | 1        | 1.23%   |
| Goldstar L222W GSM5664 1680x1050 474x296mm 22.0-inch                  | 1        | 1.23%   |
| Goldstar L192WS GSM4B32 1440x900 410x256mm 19.0-inch                  | 1        | 1.23%   |
| Goldstar L1753S GSM446F 1280x1024 338x270mm 17.0-inch                 | 1        | 1.23%   |
| Goldstar IPS234 GSM58D8 1920x1080 510x290mm 23.1-inch                 | 1        | 1.23%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 1        | 1.23%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 1        | 1.23%   |
| Goldstar DM2352 GSM58E6 1920x1080 509x286mm 23.0-inch                 | 1        | 1.23%   |
| Goldstar 27EA63 GSM598A 1920x1080 600x340mm 27.2-inch                 | 1        | 1.23%   |
| Goldstar 27EA63 GSM5989 1920x1080 600x340mm 27.2-inch                 | 1        | 1.23%   |
| FUS LCD Monitor SL27T-1 LED 1920x1080                                 | 1        | 1.23%   |
| Dell U2515H DELD072 2560x1440 553x311mm 25.0-inch                     | 1        | 1.23%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 1        | 1.23%   |
| Dell P2213 DELF042 1680x1050 473x296mm 22.0-inch                      | 1        | 1.23%   |
| Dell LCD Monitor U2722D                                               | 1        | 1.23%   |
| Dell LCD Monitor U2414H 3840x1080                                     | 1        | 1.23%   |
| Dell LCD Monitor U2414H                                               | 1        | 1.23%   |
| Dell LCD Monitor U2412M 4480x1440                                     | 1        | 1.23%   |
| Dell LCD Monitor U2412M 3520x1200                                     | 1        | 1.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 24       | 32.43%  |
| 1280x1024 (SXGA)   | 11       | 14.86%  |
| 1680x1050 (WSXGA+) | 8        | 10.81%  |
| 2560x1440 (QHD)    | 6        | 8.11%   |
| 3840x2160 (4K)     | 5        | 6.76%   |
| 1440x900 (WXGA+)   | 5        | 6.76%   |
| 1600x900 (HD+)     | 3        | 4.05%   |
| Unknown            | 3        | 4.05%   |
| 1920x1200 (WUXGA)  | 2        | 2.7%    |
| 1024x768 (XGA)     | 2        | 2.7%    |
| 4480x1440          | 1        | 1.35%   |
| 3840x1080          | 1        | 1.35%   |
| 3520x1200          | 1        | 1.35%   |
| 2960x1050          | 1        | 1.35%   |
| 1280x960           | 1        | 1.35%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 10       | 13.89%  |
| 27      | 9        | 12.5%   |
| 23      | 9        | 12.5%   |
| 19      | 8        | 11.11%  |
| 24      | 7        | 9.72%   |
| 17      | 7        | 9.72%   |
| 22      | 6        | 8.33%   |
| 21      | 4        | 5.56%   |
| 20      | 4        | 5.56%   |
| 25      | 3        | 4.17%   |
| 18      | 2        | 2.78%   |
| 15      | 2        | 2.78%   |
| 33      | 1        | 1.39%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 25       | 36.76%  |
| 401-500     | 18       | 26.47%  |
| Unknown     | 10       | 14.71%  |
| 301-350     | 9        | 13.24%  |
| 351-400     | 5        | 7.35%   |
| 701-800     | 1        | 1.47%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 29       | 43.28%  |
| 16/10   | 14       | 20.9%   |
| 5/4     | 12       | 17.91%  |
| Unknown | 10       | 14.93%  |
| 4/3     | 2        | 2.99%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 24       | 34.29%  |
| 151-200        | 14       | 20%     |
| Unknown        | 10       | 14.29%  |
| 301-350        | 9        | 12.86%  |
| 141-150        | 7        | 10%     |
| 251-300        | 3        | 4.29%   |
| 101-110        | 2        | 2.86%   |
| 351-500        | 1        | 1.43%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 46       | 67.65%  |
| Unknown | 10       | 14.71%  |
| 101-120 | 9        | 13.24%  |
| 161-240 | 2        | 2.94%   |
| 121-160 | 1        | 1.47%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 65       | 87.84%  |
| 2     | 7        | 9.46%   |
| 3     | 1        | 1.35%   |
| 0     | 1        | 1.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 41       | 42.71%  |
| Intel                            | 21       | 21.88%  |
| Qualcomm Atheros                 | 5        | 5.21%   |
| Broadcom                         | 5        | 5.21%   |
| Ralink                           | 4        | 4.17%   |
| TP-Link                          | 3        | 3.13%   |
| Nvidia                           | 3        | 3.13%   |
| Qualcomm Atheros Communications  | 2        | 2.08%   |
| Marvell Technology Group         | 2        | 2.08%   |
| Broadcom Limited                 | 2        | 2.08%   |
| ASIX Electronics                 | 2        | 2.08%   |
| Xiaomi                           | 1        | 1.04%   |
| Silicon Integrated Systems [SiS] | 1        | 1.04%   |
| Samsung Electronics              | 1        | 1.04%   |
| Ralink Technology                | 1        | 1.04%   |
| Aquantia                         | 1        | 1.04%   |
| 3Com                             | 1        | 1.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 35       | 33.65%  |
| Realtek RTL8125 2.5GbE Controller                                 | 5        | 4.81%   |
| Intel Ethernet Connection I217-V                                  | 3        | 2.88%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 2.88%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 2.88%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 2        | 1.92%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 2        | 1.92%   |
| Qualcomm Atheros AR9271 802.11n                                   | 2        | 1.92%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2        | 1.92%   |
| Nvidia MCP61 Ethernet                                             | 2        | 1.92%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 1.92%   |
| Intel Wi-Fi 6 AX200                                               | 2        | 1.92%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 2        | 1.92%   |
| ASIX AX88772B                                                     | 2        | 1.92%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.96%   |
| TP-Link 802.11ac WLAN Adapter                                     | 1        | 0.96%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1        | 0.96%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.96%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1        | 0.96%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 1        | 0.96%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 1        | 0.96%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1        | 0.96%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1        | 0.96%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.96%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.96%   |
| Ralink RT5370 Wireless Adapter                                    | 1        | 0.96%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1        | 0.96%   |
| Ralink RT2561/RT61 rev B 802.11g                                  | 1        | 0.96%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.96%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.96%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.96%   |
| Nvidia MCP67 Ethernet                                             | 1        | 0.96%   |
| Intel Wireless 8260                                               | 1        | 0.96%   |
| Intel Wireless 7265                                               | 1        | 0.96%   |
| Intel I211 Gigabit Network Connection                             | 1        | 0.96%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 0.96%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 0.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 0.96%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 0.96%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 0.96%   |
| Intel 82573E Gigabit Ethernet Controller (Copper)                 | 1        | 0.96%   |
| Intel 82567V-2 Gigabit Network Connection                         | 1        | 0.96%   |
| Intel 82567LF-3 Gigabit Network Connection                        | 1        | 0.96%   |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller     | 1        | 0.96%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 0.96%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 1        | 0.96%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 1        | 0.96%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 1        | 0.96%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 1        | 0.96%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.96%   |
| 3Com 3c940 10/100/1000Base-T [Marvell]                            | 1        | 0.96%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 5        | 23.81%  |
| Ralink                          | 4        | 19.05%  |
| Intel                           | 4        | 19.05%  |
| TP-Link                         | 3        | 14.29%  |
| Qualcomm Atheros Communications | 2        | 9.52%   |
| Ralink Technology               | 1        | 4.76%   |
| Broadcom Limited                | 1        | 4.76%   |
| Broadcom                        | 1        | 4.76%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                | 2        | 9.52%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                  | 2        | 9.52%   |
| Qualcomm Atheros AR9271 802.11n                            | 2        | 9.52%   |
| Intel Wi-Fi 6 AX200                                        | 2        | 9.52%   |
| TP-Link 802.11ac WLAN Adapter                              | 1        | 4.76%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter   | 1        | 4.76%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter            | 1        | 4.76%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                 | 1        | 4.76%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter      | 1        | 4.76%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 1        | 4.76%   |
| Ralink RT5370 Wireless Adapter                             | 1        | 4.76%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                  | 1        | 4.76%   |
| Ralink RT2561/RT61 rev B 802.11g                           | 1        | 4.76%   |
| Intel Wireless 8260                                        | 1        | 4.76%   |
| Intel Wireless 7265                                        | 1        | 4.76%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter | 1        | 4.76%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter         | 1        | 4.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 39       | 49.37%  |
| Intel                            | 18       | 22.78%  |
| Qualcomm Atheros                 | 5        | 6.33%   |
| Broadcom                         | 4        | 5.06%   |
| Nvidia                           | 3        | 3.8%    |
| Marvell Technology Group         | 2        | 2.53%   |
| ASIX Electronics                 | 2        | 2.53%   |
| Xiaomi                           | 1        | 1.27%   |
| Silicon Integrated Systems [SiS] | 1        | 1.27%   |
| Samsung Electronics              | 1        | 1.27%   |
| Broadcom Limited                 | 1        | 1.27%   |
| Aquantia                         | 1        | 1.27%   |
| 3Com                             | 1        | 1.27%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 35       | 42.17%  |
| Realtek RTL8125 2.5GbE Controller                                 | 5        | 6.02%   |
| Intel Ethernet Connection I217-V                                  | 3        | 3.61%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 3.61%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 3.61%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2        | 2.41%   |
| Nvidia MCP61 Ethernet                                             | 2        | 2.41%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 2.41%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 2        | 2.41%   |
| ASIX AX88772B                                                     | 2        | 2.41%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 1.2%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1        | 1.2%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 1.2%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.2%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 1.2%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 1.2%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 1.2%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 1.2%    |
| Nvidia MCP67 Ethernet                                             | 1        | 1.2%    |
| Intel I211 Gigabit Network Connection                             | 1        | 1.2%    |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.2%    |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.2%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 1.2%    |
| Intel 82578DM Gigabit Network Connection                          | 1        | 1.2%    |
| Intel 82574L Gigabit Network Connection                           | 1        | 1.2%    |
| Intel 82573E Gigabit Ethernet Controller (Copper)                 | 1        | 1.2%    |
| Intel 82567V-2 Gigabit Network Connection                         | 1        | 1.2%    |
| Intel 82567LF-3 Gigabit Network Connection                        | 1        | 1.2%    |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller     | 1        | 1.2%    |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 1.2%    |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 1        | 1.2%    |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 1        | 1.2%    |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.2%    |
| 3Com 3c940 10/100/1000Base-T [Marvell]                            | 1        | 1.2%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 74       | 78.72%  |
| WiFi     | 20       | 21.28%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 65       | 85.53%  |
| WiFi     | 11       | 14.47%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 55       | 74.32%  |
| 2     | 16       | 21.62%  |
| 3     | 2        | 2.7%    |
| 0     | 1        | 1.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 73       | 98.65%  |
| Yes  | 1        | 1.35%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 4        | 33.33%  |
| Cambridge Silicon Radio | 4        | 33.33%  |
| Realtek Semiconductor   | 2        | 16.67%  |
| ASUSTek Computer        | 1        | 8.33%   |
| Apple                   | 1        | 8.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4        | 33.33%  |
| Realtek Bluetooth Radio                             | 2        | 16.67%  |
| Intel Bluetooth wireless interface                  | 2        | 16.67%  |
| Intel AX200 Bluetooth                               | 2        | 16.67%  |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 8.33%   |
| Apple Bluetooth USB Host Controller                 | 1        | 8.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 52       | 41.6%   |
| Nvidia                           | 30       | 24%     |
| AMD                              | 28       | 22.4%   |
| C-Media Electronics              | 5        | 4%      |
| Yamaha                           | 2        | 1.6%    |
| Creative Labs                    | 2        | 1.6%    |
| Unknown                          | 1        | 0.8%    |
| Syntek                           | 1        | 0.8%    |
| SteelSeries ApS                  | 1        | 0.8%    |
| Silicon Integrated Systems [SiS] | 1        | 0.8%    |
| JMTek                            | 1        | 0.8%    |
| Creative Technology              | 1        | 0.8%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 10       | 7.09%   |
| AMD Starship/Matisse HD Audio Controller                                   | 7        | 4.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6        | 4.26%   |
| Nvidia TU116 High Definition Audio Controller                              | 5        | 3.55%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 5        | 3.55%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4        | 2.84%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4        | 2.84%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 2.84%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4        | 2.84%   |
| AMD FCH Azalia Controller                                                  | 4        | 2.84%   |
| Nvidia GP106 High Definition Audio Controller                              | 3        | 2.13%   |
| Intel Cannon Lake PCH cAVS                                                 | 3        | 2.13%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 3        | 2.13%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3        | 2.13%   |
| Intel 200 Series PCH HD Audio                                              | 3        | 2.13%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3        | 2.13%   |
| Yamaha Steinberg UR22mkII                                                  | 2        | 1.42%   |
| Nvidia TU106 High Definition Audio Controller                              | 2        | 1.42%   |
| Nvidia TU104 HD Audio Controller                                           | 2        | 1.42%   |
| Nvidia MCP61 High Definition Audio                                         | 2        | 1.42%   |
| Nvidia High Definition Audio Controller                                    | 2        | 1.42%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 1.42%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2        | 1.42%   |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 1.42%   |
| Nvidia GF106 High Definition Audio Controller                              | 2        | 1.42%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2        | 1.42%   |
| Intel 82801G (ICH7 Family) AC'97 Audio Controller                          | 2        | 1.42%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2        | 1.42%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 1.42%   |
| C-Media Electronics Trust USB microphone                                   | 2        | 1.42%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 2        | 1.42%   |
| AMD Trinity HDMI Audio Controller                                          | 2        | 1.42%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 2        | 1.42%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 2        | 1.42%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2        | 1.42%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2        | 1.42%   |
| Unknown USB Audio                                                          | 1        | 0.71%   |
| Syntek STK1160 Video Capture Device                                        | 1        | 0.71%   |
| SteelSeries ApS SteelSeries Arctis 7                                       | 1        | 0.71%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 1        | 0.71%   |
| Nvidia MCP67 High Definition Audio                                         | 1        | 0.71%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1        | 0.71%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1        | 0.71%   |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 0.71%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 0.71%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1        | 0.71%   |
| Nvidia GF114 HDMI Audio Controller                                         | 1        | 0.71%   |
| Nvidia GA104 High Definition Audio Controller                              | 1        | 0.71%   |
| JMTek Widget C                                                             | 1        | 0.71%   |
| Intel USB PnP Sound Device                                                 | 1        | 0.71%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1        | 0.71%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 1        | 0.71%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1        | 0.71%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller | 1        | 0.71%   |
| Creative Technology Sound Blaster Play! 3                                  | 1        | 0.71%   |
| Creative Labs EMU20k1 [Sound Blaster X-Fi Series]                          | 1        | 0.71%   |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]                 | 1        | 0.71%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 1        | 0.71%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 1        | 0.71%   |
| C-Media Electronics CM108 Audio Controller                                 | 1        | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 15       | 30%     |
| Unknown             | 14       | 28%     |
| Crucial             | 7        | 14%     |
| Corsair             | 4        | 8%      |
| G.Skill             | 3        | 6%      |
| SK hynix            | 2        | 4%      |
| Micron Technology   | 2        | 4%      |
| Samsung Electronics | 1        | 2%      |
| Ramos Technology    | 1        | 2%      |
| A-DATA Technology   | 1        | 2%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                    | 2        | 3.28%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                  | 2        | 3.28%   |
| Kingston RAM KHX3466C16D4/16GX 16GB DIMM DDR4 3466MT/s  | 2        | 3.28%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s     | 2        | 3.28%   |
| Kingston RAM KHX1600C10D3/8GX 8192MB DIMM DDR3 1600MT/s | 2        | 3.28%   |
| Unknown RAM Module 4096MB DIMM DDR3 667MT/s             | 1        | 1.64%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s            | 1        | 1.64%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                 | 1        | 1.64%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                | 1        | 1.64%   |
| Unknown RAM Module 2048MB DIMM SDRAM 1333MT/s           | 1        | 1.64%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s             | 1        | 1.64%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                  | 1        | 1.64%   |
| Unknown RAM Module 2048MB DIMM 1066MT/s                 | 1        | 1.64%   |
| Unknown RAM Module 2048MB DIMM                          | 1        | 1.64%   |
| Unknown RAM Module 1024MB DIMM SDRAM                    | 1        | 1.64%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s             | 1        | 1.64%   |
| Unknown RAM Module 1024MB DIMM DDR 667MT/s              | 1        | 1.64%   |
| Unknown RAM Module 1024MB DIMM DDR 533MT/s              | 1        | 1.64%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                  | 1        | 1.64%   |
| SK hynix RAM HYMP564U64CP8-Y5 512MB DIMM DDR2 667MT/s   | 1        | 1.64%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s | 1        | 1.64%   |
| Samsung RAM M3 78T2863QZS-CE6 1GB DIMM SDRAM 1639MT/s   | 1        | 1.64%   |
| Ramos RAM RMB2GE484CA5-13HC 2048MB DIMM 533MT/s         | 1        | 1.64%   |
| Micron RAM 8JTF25664AZ-1G6M1 2GB DIMM DDR3 1600MT/s     | 1        | 1.64%   |
| Micron RAM 8HTF12864AY-667E1 1GB DIMM DDR2 667MT/s      | 1        | 1.64%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s  | 1        | 1.64%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s | 1        | 1.64%   |
| Kingston RAM KHX2133C11D3/4GX 4GB DIMM DDR3 2134MT/s    | 1        | 1.64%   |
| Kingston RAM KHX1600C9D3/8GX 8192MB DIMM DDR3 2133MT/s  | 1        | 1.64%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s     | 1        | 1.64%   |
| Kingston RAM KHX1600C10D3/8G 4096MB DIMM DDR3 1600MT/s  | 1        | 1.64%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1866MT/s     | 1        | 1.64%   |
| Kingston RAM HX316C10F/4 4GB DIMM DDR3 1600MT/s         | 1        | 1.64%   |
| Kingston RAM 99U5431-004.A00LF 1024MB DIMM DDR 533MT/s  | 1        | 1.64%   |
| Kingston RAM 99U5403-046.A00LF 4GB DIMM DDR3 1333MT/s   | 1        | 1.64%   |
| Kingston RAM 9965525-134.A00LF 8GB DIMM DDR3 1333MT/s   | 1        | 1.64%   |
| Kingston RAM 9965525-055.A00LF 8GB DIMM DDR3 1600MT/s   | 1        | 1.64%   |
| Kingston RAM 9905403-559.A00LF 8GB DIMM DDR3 1600MT/s   | 1        | 1.64%   |
| Kingston RAM 9905402-670.A00LF 4GB DIMM DDR3 1333MT/s   | 1        | 1.64%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s   | 1        | 1.64%   |
| G.Skill RAM F3-17000CL11 4GB DIMM DDR3 2133MT/s         | 1        | 1.64%   |
| G.Skill RAM F3-10666CL8-2GBHK 2GB DIMM DDR3 1333MT/s    | 1        | 1.64%   |
| Crucial RAM Module 2GB DIMM DDR3 1333MT/s               | 1        | 1.64%   |
| Crucial RAM CT8G4DFS8266.M8FE 8GB DIMM DDR4 2667MT/s    | 1        | 1.64%   |
| Crucial RAM CT8G4DFS824A.C8FDD1 8GB DIMM DDR4 3200MT/s  | 1        | 1.64%   |
| Crucial RAM CT51264BA160BJ.C8F 4GB DIMM DDR3 1600MT/s   | 1        | 1.64%   |
| Crucial RAM CT51264BA160BJ.C8 4096MB DIMM DDR3 1600MT/s | 1        | 1.64%   |
| Crucial RAM BLT4G3D1869DT1TX0. 4GB DIMM DDR3 1867MT/s   | 1        | 1.64%   |
| Crucial RAM BLS8G4D240FSBK.8FD 8GB DIMM DDR4 2448MT/s   | 1        | 1.64%   |
| Crucial RAM BLS8G4D240FSB.16FBD2 8GB DIMM DDR4 2400MT/s | 1        | 1.64%   |
| Crucial RAM BL8G32C16U4B.M8FE 8192MB DIMM DDR4 3600MT/s | 1        | 1.64%   |
| Corsair RAM KHX2666C13/16GX 4GB DIMM DDR4 3000MT/s      | 1        | 1.64%   |
| Corsair RAM CMX4GX3M2A1600C9 2GB DIMM DDR3 1600MT/s     | 1        | 1.64%   |
| Corsair RAM CMK16GX4M4A2400C14 4GB DIMM DDR4 2133MT/s   | 1        | 1.64%   |
| Corsair RAM CMK16GX4M1D3000C16 16GB DIMM DDR4 3000MT/s  | 1        | 1.64%   |
| A-DATA RAM Module 4096MB DIMM DDR4 2133MT/s             | 1        | 1.64%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 15       | 36.59%  |
| DDR4    | 12       | 29.27%  |
| Unknown | 6        | 14.63%  |
| SDRAM   | 4        | 9.76%   |
| DDR2    | 2        | 4.88%   |
| DDR     | 2        | 4.88%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 40       | 97.56%  |
| SODIMM | 1        | 2.44%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 13       | 25.49%  |
| 2048  | 13       | 25.49%  |
| 8192  | 12       | 23.53%  |
| 1024  | 6        | 11.76%  |
| 16384 | 5        | 9.8%    |
| 32768 | 1        | 1.96%   |
| 512   | 1        | 1.96%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 8        | 14.81%  |
| 667     | 7        | 12.96%  |
| 2133    | 6        | 11.11%  |
| 1333    | 6        | 11.11%  |
| Unknown | 3        | 5.56%   |
| 3466    | 2        | 3.7%    |
| 3200    | 2        | 3.7%    |
| 3000    | 2        | 3.7%    |
| 2667    | 2        | 3.7%    |
| 2400    | 2        | 3.7%    |
| 1867    | 2        | 3.7%    |
| 800     | 2        | 3.7%    |
| 533     | 2        | 3.7%    |
| 3866    | 1        | 1.85%   |
| 3600    | 1        | 1.85%   |
| 2448    | 1        | 1.85%   |
| 2134    | 1        | 1.85%   |
| 1866    | 1        | 1.85%   |
| 1800    | 1        | 1.85%   |
| 1639    | 1        | 1.85%   |
| 1066    | 1        | 1.85%   |

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
| Logitech                    | 8        | 38.1%   |
| Z-Star Microelectronics     | 3        | 14.29%  |
| Apple                       | 2        | 9.52%   |
| Samsung Electronics         | 1        | 4.76%   |
| Pixart Imaging              | 1        | 4.76%   |
| Microdia                    | 1        | 4.76%   |
| KYE Systems (Mouse Systems) | 1        | 4.76%   |
| Genesys Logic               | 1        | 4.76%   |
| GEMBIRD                     | 1        | 4.76%   |
| Cubeternet                  | 1        | 4.76%   |
| Chicony Electronics         | 1        | 4.76%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Z-Star A4 TECH HD PC Camera                 | 2        | 9.52%   |
| Logitech Webcam C270                        | 2        | 9.52%   |
| Logitech Webcam C170                        | 2        | 9.52%   |
| Apple iPhone 5/5C/5S/6/SE                   | 2        | 9.52%   |
| Z-Star Vega USB 2.0 Camera                  | 1        | 4.76%   |
| Samsung Galaxy A5 (MTP)                     | 1        | 4.76%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro        | 1        | 4.76%   |
| Microdia Defender G-Lens 2577 HD720p Camera | 1        | 4.76%   |
| Logitech Webcam C310                        | 1        | 4.76%   |
| Logitech Webcam C250                        | 1        | 4.76%   |
| Logitech Webcam C210                        | 1        | 4.76%   |
| Logitech HD Webcam C510                     | 1        | 4.76%   |
| KYE Systems (Mouse Systems) eFace 2050AF    | 1        | 4.76%   |
| Genesys Logic Camera                        | 1        | 4.76%   |
| GEMBIRD USB2.0 PC CAMERA                    | 1        | 4.76%   |
| Cubeternet USB2.0 Camera                    | 1        | 4.76%   |
| Chicony HP High Definition Webcam           | 1        | 4.76%   |

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
| 0     | 69       | 92%     |
| 1     | 5        | 6.67%   |
| 2     | 1        | 1.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 3        | 42.86%  |
| Net/wireless             | 2        | 28.57%  |
| Net/ethernet             | 1        | 14.29%  |
| Communication controller | 1        | 14.29%  |

