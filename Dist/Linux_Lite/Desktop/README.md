Linux Lite - Tested Hardware & Statistics (Desktops)
----------------------------------------------------

A project to collect tested hardware configurations for Linux Lite.

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

Total: 118

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | GA-MA770T-UD3P              | [4544f05395](https://linux-hardware.org/?probe=4544f05395) | Nov 17, 2025 |
| ASRock        | B550M-ITX/ac                | [c94ad863b1](https://linux-hardware.org/?probe=c94ad863b1) | Oct 16, 2025 |
| MSI           | G41M-P23                    | [ef935d9e4d](https://linux-hardware.org/?probe=ef935d9e4d) | Oct 03, 2025 |
| MSI           | G41M-P23                    | [26f65abd84](https://linux-hardware.org/?probe=26f65abd84) | Sep 23, 2025 |
| Biostar       | A68N-2100                   | [6f9c53ce22](https://linux-hardware.org/?probe=6f9c53ce22) | Sep 13, 2025 |
| Dell          | 0DR845                      | [1b99b0c1fa](https://linux-hardware.org/?probe=1b99b0c1fa) | Aug 18, 2025 |
| ASUSTek       | H81M-PLUS                   | [994842d222](https://linux-hardware.org/?probe=994842d222) | Aug 16, 2025 |
| Acer          | FMP55                       | [574efa6d4b](https://linux-hardware.org/?probe=574efa6d4b) | Jul 03, 2025 |
| Gigabyte      | H61M-S1                     | [bb3fbb0ebb](https://linux-hardware.org/?probe=bb3fbb0ebb) | Jul 02, 2025 |
| Gigabyte      | H61M-S1                     | [b76d0aef1d](https://linux-hardware.org/?probe=b76d0aef1d) | Jun 29, 2025 |
| Dell          | 0FF3FN A00                  | [617b7a067a](https://linux-hardware.org/?probe=617b7a067a) | May 16, 2025 |
| Unknown       | Unknown                     | [a0e5e98e1f](https://linux-hardware.org/?probe=a0e5e98e1f) | May 14, 2025 |
| Acer          | Veriton X4110G              | [397841983c](https://linux-hardware.org/?probe=397841983c) | Apr 18, 2025 |
| Apple         | Mac-F4208DC8 PVT            | [8f2da6b759](https://linux-hardware.org/?probe=8f2da6b759) | Feb 15, 2025 |
| Gigabyte      | B650 GAMING X AX V2         | [f600e5a8a1](https://linux-hardware.org/?probe=f600e5a8a1) | Jan 19, 2025 |
| Dell          | 033FF6 A00                  | [d8f0132e52](https://linux-hardware.org/?probe=d8f0132e52) | Jan 01, 2025 |
| ASRock        | H110M-DGS R3.0              | [3c2cfc5412](https://linux-hardware.org/?probe=3c2cfc5412) | Oct 28, 2024 |
| ASRock        | B550M-ITX/ac                | [61f9e31812](https://linux-hardware.org/?probe=61f9e31812) | Sep 30, 2024 |
| ASRock        | B550M-ITX/ac                | [6d7efba0bf](https://linux-hardware.org/?probe=6d7efba0bf) | Sep 29, 2024 |
| ASRock        | 970A-G                      | [6d383b267d](https://linux-hardware.org/?probe=6d383b267d) | Aug 08, 2024 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | [49665d68a3](https://linux-hardware.org/?probe=49665d68a3) | Aug 05, 2024 |
| Acer          | ERC410M                     | [cdc03ce164](https://linux-hardware.org/?probe=cdc03ce164) | Jul 18, 2024 |
| HP            | 2B34                        | [9ee5932126](https://linux-hardware.org/?probe=9ee5932126) | Jul 13, 2024 |
| Gigabyte      | A320M-H-CF                  | [d707b04e42](https://linux-hardware.org/?probe=d707b04e42) | Jul 12, 2024 |
| Gigabyte      | Z690 AERO G DDR4            | [3ada57e9c6](https://linux-hardware.org/?probe=3ada57e9c6) | Jul 12, 2024 |
| Gigabyte      | MZBAYAP-00                  | [cd1e4598f1](https://linux-hardware.org/?probe=cd1e4598f1) | Jul 05, 2024 |
| HP            | 18E7                        | [b1e0cff114](https://linux-hardware.org/?probe=b1e0cff114) | Jun 02, 2024 |
| ASUSTek       | M4A88T-I DELUXE             | [98c3cc204a](https://linux-hardware.org/?probe=98c3cc204a) | May 04, 2024 |
| Gigabyte      | 970A-UD3P                   | [99f91f2965](https://linux-hardware.org/?probe=99f91f2965) | May 04, 2024 |
| Gigabyte      | 970A-UD3P                   | [519d12ee29](https://linux-hardware.org/?probe=519d12ee29) | May 04, 2024 |
| ASRock        | Wolfdale1333-D667           | [15e7baeeb3](https://linux-hardware.org/?probe=15e7baeeb3) | May 03, 2024 |
| ASUSTek       | Berkeley                    | [0192b193c3](https://linux-hardware.org/?probe=0192b193c3) | Feb 14, 2024 |
| ASRock        | J4125B-ITX                  | [663e605574](https://linux-hardware.org/?probe=663e605574) | Jan 17, 2024 |
| ASRock        | J4105M                      | [2e5352f371](https://linux-hardware.org/?probe=2e5352f371) | Jan 16, 2024 |
| Gigabyte      | A320M-S2H-CF                | [c4949cf710](https://linux-hardware.org/?probe=c4949cf710) | Nov 28, 2023 |
| ASRock        | J3455M                      | [6a3463b7e9](https://linux-hardware.org/?probe=6a3463b7e9) | Nov 15, 2023 |
| HP            | 3646h                       | [1cfad160f4](https://linux-hardware.org/?probe=1cfad160f4) | Nov 12, 2023 |
| Gigabyte      | H510M S2H                   | [75eb2afaca](https://linux-hardware.org/?probe=75eb2afaca) | Sep 09, 2023 |
| ASUSTek       | A8N32-SLI-Deluxe            | [26c288c533](https://linux-hardware.org/?probe=26c288c533) | Aug 30, 2023 |
| Gigabyte      | Z77X-D3H                    | [41ad8c7fc0](https://linux-hardware.org/?probe=41ad8c7fc0) | Jul 26, 2023 |
| Dell          | 0GN4PW A00                  | [8380b94e4f](https://linux-hardware.org/?probe=8380b94e4f) | Jul 06, 2023 |
| Lenovo        | 3740 NOK                    | [dff301aade](https://linux-hardware.org/?probe=dff301aade) | Jun 25, 2023 |
| AMI           | Intel                       | [72c570c2fa](https://linux-hardware.org/?probe=72c570c2fa) | Jun 14, 2023 |
| MSI           | H110M PRO-VH                | [d22b8a57cf](https://linux-hardware.org/?probe=d22b8a57cf) | Jun 13, 2023 |
| ASUSTek       | B85M-G                      | [72adb50172](https://linux-hardware.org/?probe=72adb50172) | May 20, 2023 |
| ASUSTek       | B85M-G                      | [50e85498e7](https://linux-hardware.org/?probe=50e85498e7) | May 20, 2023 |
| ASRock        | B550M-ITX/ac                | [b77341d8f0](https://linux-hardware.org/?probe=b77341d8f0) | May 01, 2023 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | [b971501e28](https://linux-hardware.org/?probe=b971501e28) | May 01, 2023 |
| Apple         | Mac-F4208DC8 PVT            | [cf325779ee](https://linux-hardware.org/?probe=cf325779ee) | Apr 08, 2023 |
| HP            | 0AE4h C                     | [fe2502088a](https://linux-hardware.org/?probe=fe2502088a) | Mar 21, 2023 |
| HP            | 0AE4h C                     | [71bdbbb36f](https://linux-hardware.org/?probe=71bdbbb36f) | Mar 19, 2023 |
| ASRock        | FM2A68M-DG3+                | [16b1b61892](https://linux-hardware.org/?probe=16b1b61892) | Mar 17, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | [cad4d19ab7](https://linux-hardware.org/?probe=cad4d19ab7) | Feb 02, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [4762c2a35b](https://linux-hardware.org/?probe=4762c2a35b) | Jan 31, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [b0289f0ef8](https://linux-hardware.org/?probe=b0289f0ef8) | Jan 22, 2023 |
| ASUSTek       | M4N72-E                     | [1902350147](https://linux-hardware.org/?probe=1902350147) | Dec 28, 2022 |
| Pegatron      | 2ACB                        | [f77ff3b9b5](https://linux-hardware.org/?probe=f77ff3b9b5) | Dec 19, 2022 |
| Braview       | BRW-BSWI-D2                 | [1568a74103](https://linux-hardware.org/?probe=1568a74103) | Dec 11, 2022 |
| Packard Be... | MCP73VT-PM                  | [e2e6da1ef3](https://linux-hardware.org/?probe=e2e6da1ef3) | Nov 27, 2022 |
| HP            | 1632                        | [f510159333](https://linux-hardware.org/?probe=f510159333) | Sep 19, 2022 |
| HP            | 1632                        | [f14389b9dd](https://linux-hardware.org/?probe=f14389b9dd) | Sep 10, 2022 |
| ASUSTek       | M51BC                       | [fd0a9ef1c8](https://linux-hardware.org/?probe=fd0a9ef1c8) | Jul 08, 2022 |
| ASUSTek       | M51BC                       | [cc2f84d5d3](https://linux-hardware.org/?probe=cc2f84d5d3) | Jul 08, 2022 |
| Lenovo        | 103D SDK0J40697 WIN 3305... | [03c6ee002e](https://linux-hardware.org/?probe=03c6ee002e) | Jun 07, 2022 |
| Acer          | Aspire TC-895 V:1.0         | [19a5c1de8e](https://linux-hardware.org/?probe=19a5c1de8e) | May 29, 2022 |
| Lenovo        | Remore CRB Win8 STD MM D... | [eb96be3541](https://linux-hardware.org/?probe=eb96be3541) | May 24, 2022 |
| Lenovo        | Remore CRB Win8 STD MM D... | [f1a79871f7](https://linux-hardware.org/?probe=f1a79871f7) | May 24, 2022 |
| HP            | 3047h                       | [cc184c817b](https://linux-hardware.org/?probe=cc184c817b) | May 16, 2022 |
| Lenovo        | ThinkCentre M91p 4518E2M    | [2553bf03d1](https://linux-hardware.org/?probe=2553bf03d1) | May 05, 2022 |
| Lenovo        | ThinkCentre M91p 4518E2M    | [03a7fc3c23](https://linux-hardware.org/?probe=03a7fc3c23) | May 05, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [f7838121d2](https://linux-hardware.org/?probe=f7838121d2) | Apr 23, 2022 |
| Dell          | 018D1Y A00                  | [0c6fc3cae4](https://linux-hardware.org/?probe=0c6fc3cae4) | Apr 07, 2022 |
| HP            | 2820h                       | [c4461b3710](https://linux-hardware.org/?probe=c4461b3710) | Apr 04, 2022 |
| Dell          | 0HY9JP A02                  | [693b66ce17](https://linux-hardware.org/?probe=693b66ce17) | Mar 27, 2022 |
| Gigabyte      | B450M DS3H-CF               | [badb9dcc14](https://linux-hardware.org/?probe=badb9dcc14) | Mar 26, 2022 |
| Gigabyte      | B450M DS3H-CF               | [32115c5548](https://linux-hardware.org/?probe=32115c5548) | Mar 26, 2022 |
| Dell          | 0HY9JP A02                  | [bc850554b2](https://linux-hardware.org/?probe=bc850554b2) | Mar 16, 2022 |
| Foxconn       | 2A8C                        | [80e5e3a26c](https://linux-hardware.org/?probe=80e5e3a26c) | Mar 15, 2022 |
| ABIT          | IP35-E                      | [67d9f7e94e](https://linux-hardware.org/?probe=67d9f7e94e) | Feb 17, 2022 |
| Pegatron      | 2ACB                        | [b7987fdaa7](https://linux-hardware.org/?probe=b7987fdaa7) | Feb 10, 2022 |
| Acer          | Aspire TC-895 V:1.0         | [4fe66f8af6](https://linux-hardware.org/?probe=4fe66f8af6) | Feb 09, 2022 |
| EVGA          | X58 SLI FTW3 Tylersburg     | [9e4639427d](https://linux-hardware.org/?probe=9e4639427d) | Jan 03, 2022 |
| EVGA          | X58 SLI FTW3 Tylersburg     | [d351220ea5](https://linux-hardware.org/?probe=d351220ea5) | Jan 02, 2022 |
| EVGA          | X58 SLI FTW3 Tylersburg     | [b2786130fb](https://linux-hardware.org/?probe=b2786130fb) | Jan 02, 2022 |
| ASRock        | H61M-VG3                    | [392a957541](https://linux-hardware.org/?probe=392a957541) | Dec 17, 2021 |
| Gigabyte      | GA-E350N                    | [10d55dd433](https://linux-hardware.org/?probe=10d55dd433) | Dec 02, 2021 |
| Biostar       | G41D3C                      | [433bc7cf78](https://linux-hardware.org/?probe=433bc7cf78) | Oct 10, 2021 |
| Biostar       | G41D3C                      | [90dc88db01](https://linux-hardware.org/?probe=90dc88db01) | Oct 02, 2021 |
| ASUSTek       | M5A78L LE                   | [ddb041ded0](https://linux-hardware.org/?probe=ddb041ded0) | Sep 15, 2021 |
| ASUSTek       | M5A78L LE                   | [a9335318aa](https://linux-hardware.org/?probe=a9335318aa) | Sep 15, 2021 |
| Intel         | DG31PR AAD97573-300         | [0a0a8059c2](https://linux-hardware.org/?probe=0a0a8059c2) | Aug 04, 2021 |
| Intel         | DG31PR AAD97573-300         | [6b7f5cdcc8](https://linux-hardware.org/?probe=6b7f5cdcc8) | Jul 21, 2021 |
| HP            | 0A98h                       | [9844591cd4](https://linux-hardware.org/?probe=9844591cd4) | Jul 02, 2021 |
| ECS           | Livermore                   | [91b29dad17](https://linux-hardware.org/?probe=91b29dad17) | Jun 23, 2021 |
| MSI           | Boston                      | [5cca21c281](https://linux-hardware.org/?probe=5cca21c281) | Apr 26, 2021 |
| MSI           | B75A-G43                    | [87a3e8d42c](https://linux-hardware.org/?probe=87a3e8d42c) | Apr 07, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [84cb4ded95](https://linux-hardware.org/?probe=84cb4ded95) | Dec 30, 2020 |
| Minix         | NEO Z83-4 V1.1              | [19e83c7c24](https://linux-hardware.org/?probe=19e83c7c24) | Dec 21, 2020 |
| Gigabyte      | X570 AORUS MASTER           | [77f93a017c](https://linux-hardware.org/?probe=77f93a017c) | Dec 21, 2020 |
| Gigabyte      | X570 AORUS MASTER           | [a6654cf4f1](https://linux-hardware.org/?probe=a6654cf4f1) | Dec 21, 2020 |
| Minix         | NEO Z83-4 V1.1              | [8f8f606051](https://linux-hardware.org/?probe=8f8f606051) | Dec 16, 2020 |
| HP            | 0ACCh                       | [7f4d2a2df4](https://linux-hardware.org/?probe=7f4d2a2df4) | Nov 23, 2020 |
| HP            | 0ACCh                       | [d28f3f3195](https://linux-hardware.org/?probe=d28f3f3195) | Nov 23, 2020 |
| Lenovo        | ThinkCentre M91p 4524RS6    | [cf9c213443](https://linux-hardware.org/?probe=cf9c213443) | Nov 21, 2020 |
| Lenovo        | ThinkCentre M91p 4524RS6    | [66d1757c3f](https://linux-hardware.org/?probe=66d1757c3f) | Nov 21, 2020 |
| HP            | 3032h                       | [1a10cb8912](https://linux-hardware.org/?probe=1a10cb8912) | Nov 20, 2020 |
| Intel         | H61M-S1                     | [f31ad89e75](https://linux-hardware.org/?probe=f31ad89e75) | Nov 02, 2020 |
| Intel         | H61M-S1                     | [f381b5e487](https://linux-hardware.org/?probe=f381b5e487) | Nov 02, 2020 |
| Lenovo        | ThinkCentre A55 9265BL7     | [1e00064286](https://linux-hardware.org/?probe=1e00064286) | Oct 30, 2020 |
| HP            | 2AA6 PVT                    | [3ee3ed2e83](https://linux-hardware.org/?probe=3ee3ed2e83) | Oct 06, 2020 |
| MSI           | Z77A-G43                    | [4420c076a7](https://linux-hardware.org/?probe=4420c076a7) | Sep 03, 2020 |
| ASRock        | N68C-S UCC                  | [a20482ea67](https://linux-hardware.org/?probe=a20482ea67) | Aug 12, 2020 |
| ASRock        | N68C-S UCC                  | [cb782efc58](https://linux-hardware.org/?probe=cb782efc58) | Aug 07, 2020 |
| Jetway        | I61MG4                      | [f677e427be](https://linux-hardware.org/?probe=f677e427be) | Jul 30, 2020 |
| Jetway        | I61MG4                      | [2e5f79f476](https://linux-hardware.org/?probe=2e5f79f476) | Jul 29, 2020 |
| Acer          | EQ35M                       | [f2dbd9e441](https://linux-hardware.org/?probe=f2dbd9e441) | Jun 23, 2020 |
| Acer          | EQ35M                       | [5ebf9a4f1a](https://linux-hardware.org/?probe=5ebf9a4f1a) | Jun 23, 2020 |
| Foxconn       | 45CMX/45GMX/45CMX-K         | [89182244dc](https://linux-hardware.org/?probe=89182244dc) | Jun 12, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| Linux Lite 5.8 | 13       | 14.94%  |
| Linux Lite 6.6 | 12       | 13.79%  |
| Linux Lite 6.4 | 8        | 9.2%    |
| Linux Lite 7.4 | 7        | 8.05%   |
| Linux Lite 5.6 | 7        | 8.05%   |
| Linux Lite 5.4 | 7        | 8.05%   |
| Linux Lite 5.2 | 7        | 8.05%   |
| Linux Lite 5.0 | 7        | 8.05%   |
| Linux Lite 7.0 | 6        | 6.9%    |
| Linux Lite 6.2 | 4        | 4.6%    |
| Linux Lite 7.6 | 3        | 3.45%   |
| Linux Lite 3.8 | 3        | 3.45%   |
| Linux Lite 6.0 | 2        | 2.3%    |
| Linux Lite 4.6 | 1        | 1.15%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Linux Lite | 84       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.4.0-96-generic  | 3        | 3.37%   |
| 5.4.0-91-generic  | 3        | 3.37%   |
| 4.4.0-112-generic | 3        | 3.37%   |
| 6.8.0-85-generic  | 2        | 2.25%   |
| 6.8.0-59-generic  | 2        | 2.25%   |
| 6.8.0-56-generic  | 2        | 2.25%   |
| 6.8.0-38-generic  | 2        | 2.25%   |
| 5.4.0-80-generic  | 2        | 2.25%   |
| 5.4.0-54-generic  | 2        | 2.25%   |
| 5.4.0-48-generic  | 2        | 2.25%   |
| 5.4.0-42-generic  | 2        | 2.25%   |
| 5.4.0-113-generic | 2        | 2.25%   |
| 5.4.0-104-generic | 2        | 2.25%   |
| 5.15.0-91-generic | 2        | 2.25%   |
| 5.15.0-82-generic | 2        | 2.25%   |
| 5.15.0-75-generic | 2        | 2.25%   |
| 5.15.0-71-generic | 2        | 2.25%   |
| 5.15.0-69-generic | 2        | 2.25%   |
| 5.15.0-58-generic | 2        | 2.25%   |
| 6.8.0-84-generic  | 1        | 1.12%   |
| 6.8.0-78-generic  | 1        | 1.12%   |
| 6.8.0-71-generic  | 1        | 1.12%   |
| 6.8.0-63-generic  | 1        | 1.12%   |
| 6.8.0-62-generic  | 1        | 1.12%   |
| 6.8.0-51-generic  | 1        | 1.12%   |
| 6.8.0-40-generic  | 1        | 1.12%   |
| 6.8.0-39-generic  | 1        | 1.12%   |
| 6.8.0-36-generic  | 1        | 1.12%   |
| 6.5.0-44-generic  | 1        | 1.12%   |
| 6.0.0-1.linuxlite | 1        | 1.12%   |
| 5.9.0             | 1        | 1.12%   |
| 5.4.0-99-generic  | 1        | 1.12%   |
| 5.4.0-88-generic  | 1        | 1.12%   |
| 5.4.0-72-generic  | 1        | 1.12%   |
| 5.4.0-70-generic  | 1        | 1.12%   |
| 5.4.0-58-generic  | 1        | 1.12%   |
| 5.4.0-52-generic  | 1        | 1.12%   |
| 5.4.0-45-generic  | 1        | 1.12%   |
| 5.4.0-37-generic  | 1        | 1.12%   |
| 5.4.0-33-generic  | 1        | 1.12%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 38       | 44.19%  |
| 5.15.0  | 24       | 27.91%  |
| 6.8.0   | 16       | 18.6%   |
| 4.4.0   | 3        | 3.49%   |
| 6.5.0   | 1        | 1.16%   |
| 6.0.0   | 1        | 1.16%   |
| 5.9.0   | 1        | 1.16%   |
| 5.13.0  | 1        | 1.16%   |
| 4.15.0  | 1        | 1.16%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 38       | 44.19%  |
| 5.15    | 24       | 27.91%  |
| 6.8     | 16       | 18.6%   |
| 4.4     | 3        | 3.49%   |
| 6.5     | 1        | 1.16%   |
| 6.0     | 1        | 1.16%   |
| 5.9     | 1        | 1.16%   |
| 5.13    | 1        | 1.16%   |
| 4.15    | 1        | 1.16%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 81       | 96.43%  |
| i686   | 3        | 3.57%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| XFCE       | 68       | 80.95%  |
| GNOME      | 15       | 17.86%  |
| X-Cinnamon | 1        | 1.19%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 82       | 97.62%  |
| Wayland | 1        | 1.19%   |
| Tty     | 1        | 1.19%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 56       | 66.67%  |
| Unknown | 18       | 21.43%  |
| TDM     | 10       | 11.9%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 37       | 44.05%  |
| pt_BR | 7        | 8.33%   |
| es_MX | 5        | 5.95%   |
| en_CA | 5        | 5.95%   |
| de_DE | 5        | 5.95%   |
| en_GB | 3        | 3.57%   |
| pl_PL | 2        | 2.38%   |
| nl_NL | 2        | 2.38%   |
| fr_FR | 2        | 2.38%   |
| es_ES | 2        | 2.38%   |
| sv_SE | 1        | 1.19%   |
| sr_RS | 1        | 1.19%   |
| ru_UA | 1        | 1.19%   |
| pt_PT | 1        | 1.19%   |
| hu_HU | 1        | 1.19%   |
| fr_CA | 1        | 1.19%   |
| es_CL | 1        | 1.19%   |
| es_AR | 1        | 1.19%   |
| en_NZ | 1        | 1.19%   |
| en_IE | 1        | 1.19%   |
| da_DK | 1        | 1.19%   |
| C     | 1        | 1.19%   |
| bg_BG | 1        | 1.19%   |
| ar_SA | 1        | 1.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 58       | 69.05%  |
| EFI  | 26       | 30.95%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 71       | 84.52%  |
| Overlay | 6        | 7.14%   |
| Tmpfs   | 5        | 5.95%   |
| Zfs     | 1        | 1.19%   |
| Ext3    | 1        | 1.19%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 38       | 45.24%  |
| MBR     | 23       | 27.38%  |
| Unknown | 23       | 27.38%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 69       | 82.14%  |
| Yes       | 15       | 17.86%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 60       | 71.43%  |
| Yes       | 24       | 28.57%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 13       | 15.48%  |
| Hewlett-Packard     | 11       | 13.1%   |
| ASUSTek Computer    | 9        | 10.71%  |
| ASRock              | 9        | 10.71%  |
| Lenovo              | 7        | 8.33%   |
| MSI                 | 6        | 7.14%   |
| Dell                | 5        | 5.95%   |
| Acer                | 5        | 5.95%   |
| Pegatron            | 2        | 2.38%   |
| Intel               | 2        | 2.38%   |
| Foxconn             | 2        | 2.38%   |
| Biostar             | 2        | 2.38%   |
| Packard Bell        | 1        | 1.19%   |
| Minix               | 1        | 1.19%   |
| Jetway              | 1        | 1.19%   |
| Fujitsu Siemens     | 1        | 1.19%   |
| Fujitsu             | 1        | 1.19%   |
| EVGA                | 1        | 1.19%   |
| Braview             | 1        | 1.19%   |
| Apple               | 1        | 1.19%   |
| AMI                 | 1        | 1.19%   |
| ABIT                | 1        | 1.19%   |
| Unknown             | 1        | 1.19%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Desktops | Percent |
|---------------------------------------------|----------|---------|
| MSI MS-7758                                 | 2        | 2.38%   |
| Pegatron 520-1135la                         | 1        | 1.19%   |
| Pegatron 520-1030a                          | 1        | 1.19%   |
| Packard Bell ISTART D2314                   | 1        | 1.19%   |
| MSI MS-7C95                                 | 1        | 1.19%   |
| MSI MS-7996                                 | 1        | 1.19%   |
| MSI MS-7592                                 | 1        | 1.19%   |
| MSI FZ079AA-ABF a6625fr                     | 1        | 1.19%   |
| Minix Z83-4                                 | 1        | 1.19%   |
| Lenovo V530S-07ICR 11BM0028MZ               | 1        | 1.19%   |
| Lenovo ThinkStation P320 30BH000BFR         | 1        | 1.19%   |
| Lenovo ThinkCentre neo 50t Gen 3 11SE00A7AX | 1        | 1.19%   |
| Lenovo ThinkCentre M91p 4524RS6             | 1        | 1.19%   |
| Lenovo ThinkCentre M91p 4518E2M             | 1        | 1.19%   |
| Lenovo ThinkCentre A55 9265BL7              | 1        | 1.19%   |
| Lenovo H505S 10107                          | 1        | 1.19%   |
| Jetway I61MG4                               | 1        | 1.19%   |
| Intel H61M-S1                               | 1        | 1.19%   |
| Intel DG31PR AAD97573-300                   | 1        | 1.19%   |
| HP Z400 Workstation                         | 1        | 1.19%   |
| HP xw8600 Workstation                       | 1        | 1.19%   |
| HP t5000 series                             | 1        | 1.19%   |
| HP rp5800                                   | 1        | 1.19%   |
| HP ProDesk 600 G1 TWR                       | 1        | 1.19%   |
| HP Compaq dc7900 Convertible Minitower      | 1        | 1.19%   |
| HP Compaq dc5800 Small Form Factor          | 1        | 1.19%   |
| HP Compaq 8000 Elite SFF PC                 | 1        | 1.19%   |
| HP Compaq 6005 Pro SFF PC                   | 1        | 1.19%   |
| HP 280 G1 MT                                | 1        | 1.19%   |
| HP 200-5320br                               | 1        | 1.19%   |
| Gigabyte Z77X-D3H                           | 1        | 1.19%   |
| Gigabyte Z690 AERO G DDR4                   | 1        | 1.19%   |
| Gigabyte X570 AORUS MASTER                  | 1        | 1.19%   |
| Gigabyte H61M-S1                            | 1        | 1.19%   |
| Gigabyte H510M S2H                          | 1        | 1.19%   |
| Gigabyte GB-BXBT-2807                       | 1        | 1.19%   |
| Gigabyte GA-MA770T-UD3P                     | 1        | 1.19%   |
| Gigabyte GA-E350N                           | 1        | 1.19%   |
| Gigabyte B650 GAMING X AX V2                | 1        | 1.19%   |
| Gigabyte B450M DS3H                         | 1        | 1.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Lenovo ThinkCentre      | 4        | 4.76%   |
| HP Compaq               | 4        | 4.76%   |
| Acer Aspire             | 3        | 3.57%   |
| MSI MS-7758             | 2        | 2.38%   |
| Dell OptiPlex           | 2        | 2.38%   |
| Dell Inspiron           | 2        | 2.38%   |
| Acer Veriton            | 2        | 2.38%   |
| Pegatron 520-1135la     | 1        | 1.19%   |
| Pegatron 520-1030a      | 1        | 1.19%   |
| Packard Bell ISTART     | 1        | 1.19%   |
| MSI MS-7C95             | 1        | 1.19%   |
| MSI MS-7996             | 1        | 1.19%   |
| MSI MS-7592             | 1        | 1.19%   |
| MSI FZ079AA-ABF         | 1        | 1.19%   |
| Minix Z83-4             | 1        | 1.19%   |
| Lenovo V530S-07ICR      | 1        | 1.19%   |
| Lenovo ThinkStation     | 1        | 1.19%   |
| Lenovo H505S            | 1        | 1.19%   |
| Jetway I61MG4           | 1        | 1.19%   |
| Intel H61M-S1           | 1        | 1.19%   |
| Intel DG31PR            | 1        | 1.19%   |
| HP Z400                 | 1        | 1.19%   |
| HP xw8600               | 1        | 1.19%   |
| HP t5000                | 1        | 1.19%   |
| HP rp5800               | 1        | 1.19%   |
| HP ProDesk              | 1        | 1.19%   |
| HP 280                  | 1        | 1.19%   |
| HP 200-5320br           | 1        | 1.19%   |
| Gigabyte Z77X-D3H       | 1        | 1.19%   |
| Gigabyte Z690           | 1        | 1.19%   |
| Gigabyte X570           | 1        | 1.19%   |
| Gigabyte H61M-S1        | 1        | 1.19%   |
| Gigabyte H510M          | 1        | 1.19%   |
| Gigabyte GB-BXBT-2807   | 1        | 1.19%   |
| Gigabyte GA-MA770T-UD3P | 1        | 1.19%   |
| Gigabyte GA-E350N       | 1        | 1.19%   |
| Gigabyte B650           | 1        | 1.19%   |
| Gigabyte B450M          | 1        | 1.19%   |
| Gigabyte A320M-S2H      | 1        | 1.19%   |
| Gigabyte A320M-H        | 1        | 1.19%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2011 | 11       | 13.1%   |
| 2012 | 9        | 10.71%  |
| 2010 | 8        | 9.52%   |
| 2008 | 8        | 9.52%   |
| 2007 | 7        | 8.33%   |
| 2009 | 6        | 7.14%   |
| 2018 | 5        | 5.95%   |
| 2021 | 4        | 4.76%   |
| 2020 | 4        | 4.76%   |
| 2015 | 4        | 4.76%   |
| 2017 | 3        | 3.57%   |
| 2014 | 3        | 3.57%   |
| 2013 | 3        | 3.57%   |
| 2022 | 2        | 2.38%   |
| 2016 | 2        | 2.38%   |
| 2005 | 2        | 2.38%   |
| 2025 | 1        | 1.19%   |
| 2023 | 1        | 1.19%   |
| 2019 | 1        | 1.19%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 84       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 82       | 97.62%  |
| Enabled  | 2        | 2.38%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 84       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 19       | 22.62%  |
| 3.01-4.0    | 19       | 22.62%  |
| 8.01-16.0   | 14       | 16.67%  |
| 16.01-24.0  | 10       | 11.9%   |
| 1.01-2.0    | 10       | 11.9%   |
| 32.01-64.0  | 7        | 8.33%   |
| 24.01-32.0  | 2        | 2.38%   |
| 2.01-3.0    | 2        | 2.38%   |
| 64.01-256.0 | 1        | 1.19%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 36       | 42.35%  |
| 2.01-3.0  | 21       | 24.71%  |
| 0.51-1.0  | 10       | 11.76%  |
| 4.01-8.0  | 9        | 10.59%  |
| 3.01-4.0  | 6        | 7.06%   |
| 8.01-16.0 | 3        | 3.53%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 48       | 57.14%  |
| 2      | 22       | 26.19%  |
| 3      | 7        | 8.33%   |
| 5      | 3        | 3.57%   |
| 4      | 2        | 2.38%   |
| 0      | 2        | 2.38%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 49       | 58.33%  |
| Yes       | 35       | 41.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 83       | 98.81%  |
| No        | 1        | 1.19%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 44       | 52.38%  |
| Yes       | 40       | 47.62%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 65       | 77.38%  |
| Yes       | 19       | 22.62%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country         | Desktops | Percent |
|-----------------|----------|---------|
| USA             | 16       | 19.05%  |
| Brazil          | 9        | 10.71%  |
| UK              | 6        | 7.14%   |
| Canada          | 6        | 7.14%   |
| Mexico          | 5        | 5.95%   |
| Germany         | 5        | 5.95%   |
| Poland          | 3        | 3.57%   |
| Peru            | 3        | 3.57%   |
| Netherlands     | 3        | 3.57%   |
| France          | 3        | 3.57%   |
| Serbia          | 2        | 2.38%   |
| Malaysia        | 2        | 2.38%   |
| Italy           | 2        | 2.38%   |
| Uzbekistan      | 1        | 1.19%   |
| Ukraine         | 1        | 1.19%   |
| Switzerland     | 1        | 1.19%   |
| Sweden          | 1        | 1.19%   |
| Spain           | 1        | 1.19%   |
| Saudi Arabia    | 1        | 1.19%   |
| Portugal        | 1        | 1.19%   |
| Pakistan        | 1        | 1.19%   |
| North Macedonia | 1        | 1.19%   |
| New Zealand     | 1        | 1.19%   |
| Ireland         | 1        | 1.19%   |
| Hungary         | 1        | 1.19%   |
| Greenland       | 1        | 1.19%   |
| Egypt           | 1        | 1.19%   |
| Colombia        | 1        | 1.19%   |
| Chile           | 1        | 1.19%   |
| Bulgaria        | 1        | 1.19%   |
| Australia       | 1        | 1.19%   |
| Argentina       | 1        | 1.19%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Würzburg      | 2        | 2.38%   |
| Toronto        | 2        | 2.38%   |
| Ottawa         | 2        | 2.38%   |
| Mexico City    | 2        | 2.38%   |
| Lima           | 2        | 2.38%   |
| Estacada       | 2        | 2.38%   |
| East Sussex    | 2        | 2.38%   |
| Zurich         | 1        | 1.19%   |
| Wellington     | 1        | 1.19%   |
| Waterbury      | 1        | 1.19%   |
| Warsaw         | 1        | 1.19%   |
| Wandsworth     | 1        | 1.19%   |
| Trujillo       | 1        | 1.19%   |
| Tilburg        | 1        | 1.19%   |
| Thetford-Mines | 1        | 1.19%   |
| The Hague      | 1        | 1.19%   |
| Tashkent       | 1        | 1.19%   |
| Sofia          | 1        | 1.19%   |
| Skopje         | 1        | 1.19%   |
| Sao Paulo      | 1        | 1.19%   |
| Salerno        | 1        | 1.19%   |
| Ruma           | 1        | 1.19%   |
| Ripi           | 1        | 1.19%   |
| Rio de Janeiro | 1        | 1.19%   |
| Purmerend      | 1        | 1.19%   |
| Porto Velho    | 1        | 1.19%   |
| Porto Alegre   | 1        | 1.19%   |
| Pearl City     | 1        | 1.19%   |
| Pabianice      | 1        | 1.19%   |
| Osasco         | 1        | 1.19%   |
| Oldenburg      | 1        | 1.19%   |
| Neuquén       | 1        | 1.19%   |
| Naugatuck      | 1        | 1.19%   |
| Nashville      | 1        | 1.19%   |
| Narbonne       | 1        | 1.19%   |
| Munster        | 1        | 1.19%   |
| Multan         | 1        | 1.19%   |
| Mazatlán      | 1        | 1.19%   |
| Makkah         | 1        | 1.19%   |
| Maineville     | 1        | 1.19%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 22       | 32     | 18.97%  |
| WDC                 | 21       | 28     | 18.1%   |
| Samsung Electronics | 11       | 11     | 9.48%   |
| Kingston            | 8        | 12     | 6.9%    |
| Hitachi             | 6        | 8      | 5.17%   |
| China               | 6        | 8      | 5.17%   |
| Toshiba             | 5        | 5      | 4.31%   |
| SanDisk             | 4        | 4      | 3.45%   |
| Maxtor              | 4        | 8      | 3.45%   |
| Crucial             | 3        | 3      | 2.59%   |
| Unknown             | 2        | 2      | 1.72%   |
| Team                | 2        | 2      | 1.72%   |
| MSI                 | 2        | 2      | 1.72%   |
| Intenso             | 2        | 2      | 1.72%   |
| A-DATA Technology   | 2        | 3      | 1.72%   |
| SPCC                | 1        | 1      | 0.86%   |
| SK hynix            | 1        | 1      | 0.86%   |
| PNY                 | 1        | 1      | 0.86%   |
| Phison              | 1        | 1      | 0.86%   |
| OCZ                 | 1        | 1      | 0.86%   |
| Mass                | 1        | 1      | 0.86%   |
| JMicron Technology  | 1        | 1      | 0.86%   |
| HPE                 | 1        | 1      | 0.86%   |
| HGST                | 1        | 1      | 0.86%   |
| Hewlett-Packard     | 1        | 1      | 0.86%   |
| GOODRAM             | 1        | 1      | 0.86%   |
| Gigabyte Technology | 1        | 1      | 0.86%   |
| Fujitsu             | 1        | 1      | 0.86%   |
| FORESEE             | 1        | 1      | 0.86%   |
| Fanxiang            | 1        | 2      | 0.86%   |
| Dogfish             | 1        | 1      | 0.86%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB    | 3        | 2.27%   |
| Samsung SSD 860 EVO 500GB          | 3        | 2.27%   |
| WDC WD5000AAKX-001CA0 500GB        | 2        | 1.52%   |
| Toshiba DT01ACA100 1TB             | 2        | 1.52%   |
| Seagate ST9500325AS 500GB          | 2        | 1.52%   |
| SanDisk SDSSDA240G 240GB           | 2        | 1.52%   |
| MSI S270 240GB                     | 2        | 1.52%   |
| Maxtor Z1 SSD 240GB                | 2        | 1.52%   |
| Kingston SV300S37A60G 64GB SSD     | 2        | 1.52%   |
| Kingston SA400S37480G 480GB SSD    | 2        | 1.52%   |
| A-DATA SU650 120GB SSD             | 2        | 1.52%   |
| WDC WDS250G2B0A 250GB SSD          | 1        | 0.76%   |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 1        | 0.76%   |
| WDC WD800JD-60LSA0 80GB            | 1        | 0.76%   |
| WDC WD800JD-00MSA1 80GB            | 1        | 0.76%   |
| WDC WD5000LPLX-21ZNTT0 500GB       | 1        | 0.76%   |
| WDC WD5000AAKX-003CA0 500GB        | 1        | 0.76%   |
| WDC WD5000AAKS-60WWPA0 500GB       | 1        | 0.76%   |
| WDC WD5000AADS-56S9B0 500GB        | 1        | 0.76%   |
| WDC WD5000AADS-00S9B0 500GB        | 1        | 0.76%   |
| WDC WD5000AACS-00G8B1 500GB        | 1        | 0.76%   |
| WDC WD40PURX-64NZ6Y0 4TB           | 1        | 0.76%   |
| WDC WD3200BEVT-60ZCT1 320GB        | 1        | 0.76%   |
| WDC WD3200BEVT-22ZCT0 320GB        | 1        | 0.76%   |
| WDC WD3200AVJS-63WDA0 320GB        | 1        | 0.76%   |
| WDC WD2500BEVS-22UST0 250GB        | 1        | 0.76%   |
| WDC WD20PURX-64PFUY0 2TB           | 1        | 0.76%   |
| WDC WD2005FBYZ-01YCBB2 2TB         | 1        | 0.76%   |
| WDC WD10JPVX-75JC3T0 1TB           | 1        | 0.76%   |
| WDC WD10JPVX-22JC3T0 1TB           | 1        | 0.76%   |
| WDC WD10EZEX-08WN4A0 1TB           | 1        | 0.76%   |
| WDC WD10EZEX-07WN4A0 1TB           | 1        | 0.76%   |
| WDC WD10EADS-00L5B1 1TB            | 1        | 0.76%   |
| WDC WD1003FBYX-01Y7B1 1TB          | 1        | 0.76%   |
| WDC PC SN730 SDBQNTY-1T00-1014 1TB | 1        | 0.76%   |
| Unknown MMC Card  64GB             | 1        | 0.76%   |
| Unknown MMC Card  32GB             | 1        | 0.76%   |
| Toshiba MK1059GSM 1TB              | 1        | 0.76%   |
| Toshiba HDWD110 1TB                | 1        | 0.76%   |
| Toshiba DT01ACA025 250GB           | 1        | 0.76%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 21       | 31     | 36.84%  |
| WDC                 | 19       | 23     | 33.33%  |
| Hitachi             | 6        | 8      | 10.53%  |
| Toshiba             | 5        | 5      | 8.77%   |
| Maxtor              | 2        | 6      | 3.51%   |
| Samsung Electronics | 1        | 1      | 1.75%   |
| HPE                 | 1        | 1      | 1.75%   |
| HGST                | 1        | 1      | 1.75%   |
| Fujitsu             | 1        | 1      | 1.75%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 8        | 8      | 17.78%  |
| Kingston            | 7        | 9      | 15.56%  |
| China               | 6        | 8      | 13.33%  |
| SanDisk             | 3        | 3      | 6.67%   |
| Crucial             | 3        | 3      | 6.67%   |
| WDC                 | 2        | 3      | 4.44%   |
| MSI                 | 2        | 2      | 4.44%   |
| Maxtor              | 2        | 2      | 4.44%   |
| A-DATA Technology   | 2        | 3      | 4.44%   |
| SPCC                | 1        | 1      | 2.22%   |
| Seagate             | 1        | 1      | 2.22%   |
| PNY                 | 1        | 1      | 2.22%   |
| OCZ                 | 1        | 1      | 2.22%   |
| Intenso             | 1        | 1      | 2.22%   |
| Hewlett-Packard     | 1        | 1      | 2.22%   |
| GOODRAM             | 1        | 1      | 2.22%   |
| Gigabyte Technology | 1        | 1      | 2.22%   |
| Fanxiang            | 1        | 2      | 2.22%   |
| Dogfish             | 1        | 1      | 2.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 49       | 77     | 46.23%  |
| SSD     | 43       | 52     | 40.57%  |
| NVMe    | 9        | 13     | 8.49%   |
| Unknown | 3        | 3      | 2.83%   |
| MMC     | 2        | 2      | 1.89%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 77       | 128    | 83.7%   |
| NVMe | 9        | 13     | 9.78%   |
| SAS  | 4        | 4      | 4.35%   |
| MMC  | 2        | 2      | 2.17%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 65       | 93     | 70.65%  |
| 0.51-1.0   | 22       | 30     | 23.91%  |
| 1.01-2.0   | 3        | 4      | 3.26%   |
| 3.01-4.0   | 1        | 1      | 1.09%   |
| 2.01-3.0   | 1        | 1      | 1.09%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 25       | 29.41%  |
| 251-500        | 15       | 17.65%  |
| 51-100         | 14       | 16.47%  |
| 501-1000       | 9        | 10.59%  |
| 1001-2000      | 7        | 8.24%   |
| 1-20           | 5        | 5.88%   |
| More than 3000 | 4        | 4.71%   |
| 21-50          | 3        | 3.53%   |
| 2001-3000      | 2        | 2.35%   |
| Unknown        | 1        | 1.18%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 33       | 37.93%  |
| 21-50     | 18       | 20.69%  |
| 51-100    | 10       | 11.49%  |
| 101-250   | 9        | 10.34%  |
| 251-500   | 6        | 6.9%    |
| 501-1000  | 6        | 6.9%    |
| 2001-3000 | 2        | 2.3%    |
| 1001-2000 | 2        | 2.3%    |
| Unknown   | 1        | 1.15%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                         | Desktops | Drives | Percent |
|-------------------------------|----------|--------|---------|
| WDC WD800JD-60LSA0 80GB       | 1        | 1      | 6.25%   |
| WDC WD800JD-00MSA1 80GB       | 1        | 1      | 6.25%   |
| WDC WD5000AAKX-001CA0 500GB   | 1        | 1      | 6.25%   |
| WDC WD5000AAKS-60WWPA0 500GB  | 1        | 1      | 6.25%   |
| Toshiba MK1059GSM 1TB         | 1        | 1      | 6.25%   |
| Toshiba DT01ACA100 1TB        | 1        | 1      | 6.25%   |
| Seagate ST980811AS 80GB       | 1        | 1      | 6.25%   |
| Seagate ST9500325AS 500GB     | 1        | 1      | 6.25%   |
| Seagate ST3750528AS 752GB     | 1        | 1      | 6.25%   |
| Seagate ST3120026A 120GB      | 1        | 1      | 6.25%   |
| Maxtor 6Y250M0 256GB          | 1        | 1      | 6.25%   |
| Maxtor 6V300F0 304GB          | 1        | 3      | 6.25%   |
| Hitachi HDS722020ALA330 2TB   | 1        | 1      | 6.25%   |
| Hitachi HDS721680PLA380 80GB  | 1        | 1      | 6.25%   |
| Hitachi HDS721616PLA380 160GB | 1        | 1      | 6.25%   |
| Hitachi HDP725032GLA360 320GB | 1        | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 4        | 4      | 26.67%  |
| Seagate | 4        | 4      | 26.67%  |
| Hitachi | 4        | 4      | 26.67%  |
| Toshiba | 2        | 2      | 13.33%  |
| Maxtor  | 1        | 4      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 4        | 4      | 26.67%  |
| Seagate | 4        | 4      | 26.67%  |
| Hitachi | 4        | 4      | 26.67%  |
| Toshiba | 2        | 2      | 13.33%  |
| Maxtor  | 1        | 4      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 13       | 18     | 100%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Intenso SSD SATAIII 512GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Intenso | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 44       | 68     | 47.83%  |
| Detected | 34       | 60     | 36.96%  |
| Malfunc  | 13       | 18     | 14.13%  |
| Failed   | 1        | 1      | 1.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 55       | 53.92%  |
| AMD                          | 23       | 22.55%  |
| Nvidia                       | 4        | 3.92%   |
| SanDisk                      | 2        | 1.96%   |
| Samsung Electronics          | 2        | 1.96%   |
| Marvell Technology Group     | 2        | 1.96%   |
| JMicron Technology           | 2        | 1.96%   |
| VIA Technologies             | 1        | 0.98%   |
| ULi Electronics              | 1        | 0.98%   |
| SK hynix                     | 1        | 0.98%   |
| Silicon Image                | 1        | 0.98%   |
| Shenzhen Longsys Electronics | 1        | 0.98%   |
| Phison Electronics           | 1        | 0.98%   |
| MAXIO Technology (Hangzhou)  | 1        | 0.98%   |
| LSI Logic / Symbios Logic    | 1        | 0.98%   |
| Kingston Technology Company  | 1        | 0.98%   |
| Hosin Global Electronics     | 1        | 0.98%   |
| Broadcom / LSI               | 1        | 0.98%   |
| ASMedia Technology           | 1        | 0.98%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                                              | Desktops | Percent |
|--------------------------------------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                                                  | 9        | 6.43%   |
| AMD FCH SATA Controller [AHCI mode]                                                                                | 8        | 5.71%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                                               | 7        | 5%      |
| Intel 82801G (ICH7 Family) IDE Controller                                                                          | 6        | 4.29%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller                                      | 5        | 3.57%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                                                  | 5        | 3.57%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                                                       | 4        | 2.86%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]                                     | 4        | 2.86%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                                                   | 4        | 2.86%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]                                      | 3        | 2.14%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                                               | 3        | 2.14%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]                                       | 3        | 2.14%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5)                            | 3        | 2.14%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3)                            | 3        | 2.14%   |
| Intel 4 Series Chipset PT IDER Controller                                                                          | 3        | 2.14%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                                             | 2        | 1.43%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                                           | 2        | 1.43%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                                             | 2        | 1.43%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                                                 | 2        | 1.43%   |
| Intel 82Q35 Express PT IDER Controller                                                                             | 2        | 1.43%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                                                  | 2        | 1.43%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                                                | 2        | 1.43%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                                             | 2        | 1.43%   |
| Intel 631xESB/632xESB IDE Controller                                                                               | 2        | 1.43%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                                                     | 2        | 1.43%   |
| AMD FCH SATA Controller [IDE mode]                                                                                 | 2        | 1.43%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                                                       | 2        | 1.43%   |
| AMD 500 Series Chipset SATA Controller                                                                             | 2        | 1.43%   |
| AMD 400 Series Chipset SATA Controller                                                                             | 2        | 1.43%   |
| VIA VT6421 IDE/SATA Controller                                                                                     | 1        | 0.71%   |
| ULi ULi 5287 SATA                                                                                                  | 1        | 0.71%   |
| ULi M5229 IDE                                                                                                      | 1        | 0.71%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                                               | 1        | 0.71%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                                                               | 1        | 0.71%   |
| Shenzhen Longsys FORESEE XP1000 / Lexar Professional CFexpress Type B Gold series, NM620 PCIe NVME SSD (DRAM-less) | 1        | 0.71%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                                                              | 1        | 0.71%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                                               | 1        | 0.71%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                                                      | 1        | 0.71%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                                                      | 1        | 0.71%   |
| Phison E16 PCIe4 NVMe Controller                                                                                   | 1        | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 60       | 53.57%  |
| IDE  | 38       | 33.93%  |
| NVMe | 9        | 8.04%   |
| RAID | 4        | 3.57%   |
| SCSI | 1        | 0.89%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 58       | 69.05%  |
| AMD    | 26       | 30.95%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 3        | 3.57%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 3        | 3.57%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 2        | 2.38%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2        | 2.38%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 2.38%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 2        | 2.38%   |
| Intel Xeon CPU X5680 @ 3.33GHz              | 1        | 1.19%   |
| Intel Xeon CPU E5450 @ 3.00GHz              | 1        | 1.19%   |
| Intel Xeon CPU E5410 @ 2.33GHz              | 1        | 1.19%   |
| Intel Xeon CPU 5150 @ 2.66GHz               | 1        | 1.19%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1        | 1.19%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1        | 1.19%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1        | 1.19%   |
| Intel Pentium D CPU 3.40GHz                 | 1        | 1.19%   |
| Intel Pentium D CPU 3.00GHz                 | 1        | 1.19%   |
| Intel Pentium CPU E5500 @ 2.80GHz           | 1        | 1.19%   |
| Intel N150                                  | 1        | 1.19%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 1.19%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 1.19%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 1        | 1.19%   |
| Intel Core i7 CPU 970 @ 3.20GHz             | 1        | 1.19%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 1.19%   |
| Intel Core i5-4690K CPU @ 3.50GHz           | 1        | 1.19%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 1        | 1.19%   |
| Intel Core i5-2310 CPU @ 2.90GHz            | 1        | 1.19%   |
| Intel Core i5-10500 CPU @ 3.10GHz           | 1        | 1.19%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 1        | 1.19%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 1        | 1.19%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 1        | 1.19%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 1        | 1.19%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 1        | 1.19%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 1        | 1.19%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 1        | 1.19%   |
| Intel Core i3 CPU 550 @ 3.20GHz             | 1        | 1.19%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 1        | 1.19%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 1        | 1.19%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 1        | 1.19%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 1        | 1.19%   |
| Intel Core 2 Duo CPU E8300 @ 2.83GHz        | 1        | 1.19%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz        | 1        | 1.19%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 11       | 13.1%   |
| Intel Celeron           | 9        | 10.71%  |
| Intel Core i3           | 8        | 9.52%   |
| Intel Core 2 Duo        | 6        | 7.14%   |
| Intel Xeon              | 4        | 4.76%   |
| Intel Pentium Dual-Core | 4        | 4.76%   |
| Intel Core i7           | 4        | 4.76%   |
| AMD Ryzen 5             | 4        | 4.76%   |
| Other                   | 3        | 3.57%   |
| AMD Ryzen 3             | 3        | 3.57%   |
| AMD FX                  | 3        | 3.57%   |
| Intel Pentium Dual      | 2        | 2.38%   |
| Intel Pentium D         | 2        | 2.38%   |
| Intel Core 2 Quad       | 2        | 2.38%   |
| AMD Phenom II X2        | 2        | 2.38%   |
| AMD E                   | 2        | 2.38%   |
| AMD Athlon II X2        | 2        | 2.38%   |
| AMD A6                  | 2        | 2.38%   |
| Intel Pentium           | 1        | 1.19%   |
| Intel Core 2            | 1        | 1.19%   |
| Intel Atom              | 1        | 1.19%   |
| AMD Turion 64 X2 Mobile | 1        | 1.19%   |
| AMD Sempron             | 1        | 1.19%   |
| AMD Ryzen 9             | 1        | 1.19%   |
| AMD Phenom II X6        | 1        | 1.19%   |
| AMD Phenom II X4        | 1        | 1.19%   |
| AMD E1                  | 1        | 1.19%   |
| AMD Athlon 64 X2        | 1        | 1.19%   |
| AMD A8                  | 1        | 1.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 40       | 47.62%  |
| 4      | 28       | 33.33%  |
| 6      | 10       | 11.9%   |
| 12     | 2        | 2.38%   |
| 1      | 2        | 2.38%   |
| 8      | 1        | 1.19%   |
| 3      | 1        | 1.19%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 82       | 97.62%  |
| 2      | 2        | 2.38%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 58       | 69.05%  |
| 2      | 26       | 30.95%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 84       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 27       | 31.76%  |
| 0x1067a    | 9        | 10.59%  |
| 0x206a7    | 7        | 8.24%   |
| 0x010000c8 | 3        | 3.53%   |
| 0x6fb      | 2        | 2.35%   |
| 0x506c9    | 2        | 2.35%   |
| 0x406c4    | 2        | 2.35%   |
| 0x306c3    | 2        | 2.35%   |
| 0x206c2    | 2        | 2.35%   |
| 0x10676    | 2        | 2.35%   |
| 0x06000852 | 2        | 2.35%   |
| 0x010000db | 2        | 2.35%   |
| 0xf64      | 1        | 1.18%   |
| 0xf44      | 1        | 1.18%   |
| 0xa0653    | 1        | 1.18%   |
| 0x906e9    | 1        | 1.18%   |
| 0x90672    | 1        | 1.18%   |
| 0x706a8    | 1        | 1.18%   |
| 0x706a1    | 1        | 1.18%   |
| 0x6fd      | 1        | 1.18%   |
| 0x6f6      | 1        | 1.18%   |
| 0x6f2      | 1        | 1.18%   |
| 0x506e3    | 1        | 1.18%   |
| 0x306a9    | 1        | 1.18%   |
| 0x30678    | 1        | 1.18%   |
| 0x20655    | 1        | 1.18%   |
| 0x0a50000d | 1        | 1.18%   |
| 0x0a50000c | 1        | 1.18%   |
| 0x08701013 | 1        | 1.18%   |
| 0x0810100b | 1        | 1.18%   |
| 0x0800820d | 1        | 1.18%   |
| 0x05000119 | 1        | 1.18%   |
| 0x05000029 | 1        | 1.18%   |
| 0x03000027 | 1        | 1.18%   |
| 0x010000c7 | 1        | 1.18%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Penryn           | 13       | 15.48%  |
| SandyBridge      | 8        | 9.52%   |
| K10              | 7        | 8.33%   |
| Core             | 7        | 8.33%   |
| Silvermont       | 4        | 4.76%   |
| Haswell          | 4        | 4.76%   |
| Zen              | 3        | 3.57%   |
| Westmere         | 3        | 3.57%   |
| Piledriver       | 3        | 3.57%   |
| KabyLake         | 3        | 3.57%   |
| IvyBridge        | 3        | 3.57%   |
| Zen 3            | 2        | 2.38%   |
| NetBurst         | 2        | 2.38%   |
| K8 Hammer        | 2        | 2.38%   |
| K10 Llano        | 2        | 2.38%   |
| Goldmont plus    | 2        | 2.38%   |
| Goldmont         | 2        | 2.38%   |
| CometLake        | 2        | 2.38%   |
| Bobcat           | 2        | 2.38%   |
| Unknown          | 2        | 2.38%   |
| Zen+             | 1        | 1.19%   |
| Zen 2            | 1        | 1.19%   |
| Steamroller      | 1        | 1.19%   |
| Skylake          | 1        | 1.19%   |
| Nehalem          | 1        | 1.19%   |
| Jaguar           | 1        | 1.19%   |
| Gracemont        | 1        | 1.19%   |
| Alderlake Hybrid | 1        | 1.19%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 31       | 36.05%  |
| AMD    | 28       | 32.56%  |
| Nvidia | 27       | 31.4%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 5        | 5.68%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3        | 3.41%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 3        | 3.41%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 3        | 3.41%   |
| Nvidia GT218 [GeForce 210]                                                               | 2        | 2.27%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2        | 2.27%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2        | 2.27%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 2        | 2.27%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2        | 2.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2        | 2.27%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2        | 2.27%   |
| Intel Apollo Lake GT1 [HD Graphics 500]                                                  | 2        | 2.27%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 2        | 2.27%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 2        | 2.27%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2        | 2.27%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2        | 2.27%   |
| AMD Caicos PRO [Radeon HD 7450]                                                          | 2        | 2.27%   |
| Nvidia TU117GL [T600]                                                                    | 1        | 1.14%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1        | 1.14%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 1        | 1.14%   |
| Nvidia TU116 [GeForce GTX 1650]                                                          | 1        | 1.14%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1        | 1.14%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1        | 1.14%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1        | 1.14%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1        | 1.14%   |
| Nvidia GK107 [NVS 510]                                                                   | 1        | 1.14%   |
| Nvidia GF104 [GeForce GTX 460]                                                           | 1        | 1.14%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                           | 1        | 1.14%   |
| Nvidia G94 [GeForce 9600 GT]                                                             | 1        | 1.14%   |
| Nvidia G86 [GeForce 8400 GS]                                                             | 1        | 1.14%   |
| Nvidia G84GL [Quadro FX 1700]                                                            | 1        | 1.14%   |
| Nvidia G84 [GeForce 8400 GS]                                                             | 1        | 1.14%   |
| Nvidia G73 [GeForce 7300 GT]                                                             | 1        | 1.14%   |
| Nvidia G72 [GeForce 7300 GS]                                                             | 1        | 1.14%   |
| Nvidia C73 [GeForce 7050 / nForce 610i]                                                  | 1        | 1.14%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 1        | 1.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1        | 1.14%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 1.14%   |
| Intel Skylake-S GT2 [HD Graphics 530]                                                    | 1        | 1.14%   |
| Intel Kaby Lake-S GT2 [HD Graphics 630]                                                  | 1        | 1.14%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 29       | 34.12%  |
| 1 x Nvidia     | 26       | 30.59%  |
| 1 x AMD        | 26       | 30.59%  |
| 2 x AMD        | 2        | 2.35%   |
| 2 x Intel      | 1        | 1.18%   |
| Intel + Nvidia | 1        | 1.18%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 68       | 80.95%  |
| Proprietary | 13       | 15.48%  |
| Unknown     | 3        | 3.57%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 43       | 50.59%  |
| 0.01-0.5   | 19       | 22.35%  |
| 1.01-2.0   | 7        | 8.24%   |
| 0.51-1.0   | 7        | 8.24%   |
| 3.01-4.0   | 4        | 4.71%   |
| 5.01-6.0   | 3        | 3.53%   |
| 7.01-8.0   | 1        | 1.18%   |
| 8.01-16.0  | 1        | 1.18%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 15       | 17.86%  |
| Hewlett-Packard         | 13       | 15.48%  |
| Goldstar                | 10       | 11.9%   |
| Ancor Communications    | 6        | 7.14%   |
| Acer                    | 6        | 7.14%   |
| Dell                    | 5        | 5.95%   |
| Vestel Elektronik       | 3        | 3.57%   |
| Sony                    | 3        | 3.57%   |
| NEC Computers           | 3        | 3.57%   |
| AOC                     | 3        | 3.57%   |
| ViewSonic               | 2        | 2.38%   |
| Philips                 | 2        | 2.38%   |
| Lenovo                  | 2        | 2.38%   |
| Unknown                 | 1        | 1.19%   |
| TSL                     | 1        | 1.19%   |
| Toshiba                 | 1        | 1.19%   |
| Sharp                   | 1        | 1.19%   |
| NCS                     | 1        | 1.19%   |
| MSI                     | 1        | 1.19%   |
| Hitachi                 | 1        | 1.19%   |
| Chi Mei Optoelectronics | 1        | 1.19%   |
| Belinea                 | 1        | 1.19%   |
| Apple                   | 1        | 1.19%   |
| Unknown                 | 1        | 1.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 880x500mm 39.8-inch | 3        | 3.33%   |
| Ancor Communications VE247 ACI2493 1920x1080 530x300mm 24.0-inch     | 3        | 3.33%   |
| Hewlett-Packard TouchSmart HWP4212 1920x1080 509x286mm 23.0-inch     | 2        | 2.22%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 2        | 2.22%   |
| Acer X193HQ ACR0069 1366x768 410x230mm 18.5-inch                     | 2        | 2.22%   |
| ViewSonic VP2365WB VSC7123 1920x1080 509x286mm 23.0-inch             | 1        | 1.11%   |
| ViewSonic VA1938 Series VSC0626 1366x768 410x230mm 18.5-inch         | 1        | 1.11%   |
| ViewSonic LCD Monitor VP2365WB 1920x1080                             | 1        | 1.11%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 1        | 1.11%   |
| TSL 24MT600BF TSL0758 1920x1080 530x299mm 24.0-inch                  | 1        | 1.11%   |
| Toshiba L705A LCD705A 1280x1024 340x270mm 17.1-inch                  | 1        | 1.11%   |
| Sony TV SNYDC01 1360x768                                             | 1        | 1.11%   |
| Sony TV SNY4803 1920x1080 1218x685mm 55.0-inch                       | 1        | 1.11%   |
| Sony TV SNY3002 1920x1080 886x498mm 40.0-inch                        | 1        | 1.11%   |
| Sharp HDMI SHP4192 1920x1080 708x398mm 32.0-inch                     | 1        | 1.11%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch    | 1        | 1.11%   |
| Samsung Electronics SyncMaster SAM055A 1920x1200 518x324mm 24.1-inch | 1        | 1.11%   |
| Samsung Electronics SyncMaster SAM0426 1920x1200                     | 1        | 1.11%   |
| Samsung Electronics SyncMaster SAM0424 1920x1200 520x320mm 24.0-inch | 1        | 1.11%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch | 1        | 1.11%   |
| Samsung Electronics SyncMaster SAM0193 1280x1024 376x301mm 19.0-inch | 1        | 1.11%   |
| Samsung Electronics S34J55x SAM0F72 3440x1440 797x333mm 34.0-inch    | 1        | 1.11%   |
| Samsung Electronics S27C450 SAM09D8 1920x1080 598x336mm 27.0-inch    | 1        | 1.11%   |
| Samsung Electronics S24D332 SAM0F5E 1920x1080 531x299mm 24.0-inch    | 1        | 1.11%   |
| Samsung Electronics S24C31x SAM7311 1920x1080 527x296mm 23.8-inch    | 1        | 1.11%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch     | 1        | 1.11%   |
| Samsung Electronics S19C300 SAM0A13 1366x768 410x230mm 18.5-inch     | 1        | 1.11%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch    | 1        | 1.11%   |
| Samsung Electronics LCD Monitor SyncMaster 5280x1080                 | 1        | 1.11%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                 | 1        | 1.11%   |
| Samsung Electronics LCD Monitor SyncMaster                           | 1        | 1.11%   |
| Samsung Electronics LCD Monitor SAM01D1 1360x768                     | 1        | 1.11%   |
| Philips 230W PHL0836 1920x1200 495x310mm 23.0-inch                   | 1        | 1.11%   |
| Philips 221V PHL0888 1920x1080 477x268mm 21.5-inch                   | 1        | 1.11%   |
| NEC Computers LCD1990SXi NEC66AC 1280x1024 376x301mm 19.0-inch       | 1        | 1.11%   |
| NEC Computers EA244WMi NEC68D7 1920x1200 519x324mm 24.1-inch         | 1        | 1.11%   |
| NEC Computers 20WGX2 NEC6699 1680x1050 433x270mm 20.1-inch           | 1        | 1.11%   |
| NCS LCD Monitor NCS2275 1920x1080 256x192mm 12.6-inch                | 1        | 1.11%   |
| MSI G271 MSI3CB5 1920x1080 598x336mm 27.0-inch                       | 1        | 1.11%   |
| Lenovo T2224pD LEN60CA 1920x1080 476x267mm 21.5-inch                 | 1        | 1.11%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 31       | 36.9%   |
| 3840x2160 (4K)     | 9        | 10.71%  |
| 1366x768 (WXGA)    | 7        | 8.33%   |
| 1280x1024 (SXGA)   | 7        | 8.33%   |
| 1680x1050 (WSXGA+) | 6        | 7.14%   |
| 1920x1200 (WUXGA)  | 5        | 5.95%   |
| 1600x900 (HD+)     | 5        | 5.95%   |
| 1440x900 (WXGA+)   | 3        | 3.57%   |
| 1360x768           | 3        | 3.57%   |
| 2560x1440 (QHD)    | 2        | 2.38%   |
| 5280x1080          | 1        | 1.19%   |
| 3440x1440          | 1        | 1.19%   |
| 2288x1287          | 1        | 1.19%   |
| 1280x720 (HD)      | 1        | 1.19%   |
| 1024x768 (XGA)     | 1        | 1.19%   |
| Unknown            | 1        | 1.19%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 14       | 16.47%  |
| 23      | 9        | 10.59%  |
| 27      | 7        | 8.24%   |
| 18      | 7        | 8.24%   |
| 20      | 6        | 7.06%   |
| 19      | 6        | 7.06%   |
| Unknown | 6        | 7.06%   |
| 17      | 5        | 5.88%   |
| 31      | 4        | 4.71%   |
| 22      | 4        | 4.71%   |
| 21      | 4        | 4.71%   |
| 84      | 3        | 3.53%   |
| 15      | 2        | 2.35%   |
| 142     | 1        | 1.18%   |
| 72      | 1        | 1.18%   |
| 60      | 1        | 1.18%   |
| 46      | 1        | 1.18%   |
| 34      | 1        | 1.18%   |
| 32      | 1        | 1.18%   |
| 28      | 1        | 1.18%   |
| 12      | 1        | 1.18%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 27       | 31.76%  |
| 401-500        | 26       | 30.59%  |
| 301-350        | 7        | 8.24%   |
| 601-700        | 6        | 7.06%   |
| Unknown        | 6        | 7.06%   |
| 1501-2000      | 4        | 4.71%   |
| 351-400        | 3        | 3.53%   |
| 701-800        | 2        | 2.35%   |
| 1001-1500      | 2        | 2.35%   |
| More than 2000 | 1        | 1.18%   |
| 201-300        | 1        | 1.18%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 52       | 64.2%   |
| 16/10   | 13       | 16.05%  |
| 5/4     | 8        | 9.88%   |
| Unknown | 4        | 4.94%   |
| 4/3     | 2        | 2.47%   |
| 21/9    | 1        | 1.23%   |
| 1.00    | 1        | 1.23%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 27       | 32.14%  |
| 151-200        | 14       | 16.67%  |
| 141-150        | 11       | 13.1%   |
| 351-500        | 7        | 8.33%   |
| 301-350        | 7        | 8.33%   |
| Unknown        | 6        | 7.14%   |
| More than 1000 | 5        | 5.95%   |
| 251-300        | 3        | 3.57%   |
| 101-110        | 2        | 2.38%   |
| 71-80          | 1        | 1.19%   |
| 501-1000       | 1        | 1.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 56       | 70%     |
| 101-120 | 9        | 11.25%  |
| Unknown | 6        | 7.5%    |
| 1-50    | 4        | 5%      |
| 121-160 | 4        | 5%      |
| 161-240 | 1        | 1.25%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 74       | 88.1%   |
| 2     | 9        | 10.71%  |
| 3     | 1        | 1.19%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 52       | 42.62%  |
| Intel                                 | 21       | 17.21%  |
| Broadcom                              | 7        | 5.74%   |
| Ralink Technology                     | 5        | 4.1%    |
| TP-Link                               | 4        | 3.28%   |
| Qualcomm Atheros                      | 4        | 3.28%   |
| ASUSTek Computer                      | 4        | 3.28%   |
| Ralink                                | 3        | 2.46%   |
| Nvidia                                | 3        | 2.46%   |
| MediaTek                              | 2        | 1.64%   |
| Marvell Technology Group              | 2        | 1.64%   |
| ZTE WCDMA Technologies MSM            | 1        | 0.82%   |
| Sundance Technology Inc / IC Plus     | 1        | 0.82%   |
| Sitecom Europe                        | 1        | 0.82%   |
| Samsung Electronics                   | 1        | 0.82%   |
| Qualcomm Atheros Communications       | 1        | 0.82%   |
| Microsoft                             | 1        | 0.82%   |
| Linksys                               | 1        | 0.82%   |
| Lenovo                                | 1        | 0.82%   |
| Huawei Technologies                   | 1        | 0.82%   |
| Gemtek                                | 1        | 0.82%   |
| Broadcom Limited                      | 1        | 0.82%   |
| Belkin Components                     | 1        | 0.82%   |
| ASIX Electronics                      | 1        | 0.82%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.82%   |
| 3Com                                  | 1        | 0.82%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller                        | 44       | 31.65%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 5        | 3.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 4        | 2.88%   |
| Ralink MT7601U Wireless Adapter                                                               | 3        | 2.16%   |
| Intel 82566DM-2 Gigabit Network Connection                                                    | 3        | 2.16%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 2        | 1.44%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                      | 2        | 1.44%   |
| Realtek RTL8125 2.5GbE Controller                                                             | 2        | 1.44%   |
| Realtek 802.11ac NIC                                                                          | 2        | 1.44%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 2        | 1.44%   |
| Intel Wi-Fi 6 AX200                                                                           | 2        | 1.44%   |
| Intel 82567LM-3 Gigabit Network Connection                                                    | 2        | 1.44%   |
| ZTE WCDMA MSM ZTE Blade A54                                                                   | 1        | 0.72%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 1        | 0.72%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                           | 1        | 0.72%   |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                                                       | 1        | 0.72%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 1        | 0.72%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY                    | 1        | 0.72%   |
| Sitecom Europe RTL8188S WLAN Adapter                                                          | 1        | 0.72%   |
| Samsung Galaxy series, misc. (tethering mode)                                                 | 1        | 0.72%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                                   | 1        | 0.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 0.72%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                       | 1        | 0.72%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 1        | 0.72%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 1        | 0.72%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1        | 0.72%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 1        | 0.72%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                                     | 1        | 0.72%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 0.72%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 1        | 0.72%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                     | 1        | 0.72%   |
| Ralink RT2561/RT61 802.11g PCI                                                                | 1        | 0.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 1        | 0.72%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 1        | 0.72%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                              | 1        | 0.72%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                                      | 1        | 0.72%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                                    | 1        | 0.72%   |
| Nvidia MCP77 Ethernet                                                                         | 1        | 0.72%   |
| Nvidia MCP61 Ethernet                                                                         | 1        | 0.72%   |
| Nvidia CK804 Ethernet Controller                                                              | 1        | 0.72%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 11       | 25.58%  |
| Ralink Technology                     | 5        | 11.63%  |
| TP-Link                               | 4        | 9.3%    |
| Intel                                 | 4        | 9.3%    |
| ASUSTek Computer                      | 4        | 9.3%    |
| Ralink                                | 3        | 6.98%   |
| Qualcomm Atheros                      | 2        | 4.65%   |
| Sitecom Europe                        | 1        | 2.33%   |
| Qualcomm Atheros Communications       | 1        | 2.33%   |
| Microsoft                             | 1        | 2.33%   |
| MediaTek                              | 1        | 2.33%   |
| Linksys                               | 1        | 2.33%   |
| Gemtek                                | 1        | 2.33%   |
| Broadcom Limited                      | 1        | 2.33%   |
| Broadcom                              | 1        | 2.33%   |
| Belkin Components                     | 1        | 2.33%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 2.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                                  | Desktops | Percent |
|--------------------------------------------------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                                                        | 3        | 6.98%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                               | 2        | 4.65%   |
| Realtek 802.11ac NIC                                                                                   | 2        | 4.65%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                                  | 2        | 4.65%   |
| Intel Wi-Fi 6 AX200                                                                                    | 2        | 4.65%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                            | 1        | 2.33%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                                    | 1        | 2.33%   |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                                                                | 1        | 2.33%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                             | 1        | 2.33%   |
| Sitecom Europe RTL8188S WLAN Adapter                                                                   | 1        | 2.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                               | 1        | 2.33%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                                | 1        | 2.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                                        | 1        | 2.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                                    | 1        | 2.33%   |
| Realtek RTL8188EE Wireless Network Adapter                                                             | 1        | 2.33%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                                              | 1        | 2.33%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz]          | 1        | 2.33%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                              | 1        | 2.33%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                              | 1        | 2.33%   |
| Ralink RT2561/RT61 802.11g PCI                                                                         | 1        | 2.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                             | 1        | 2.33%   |
| Qualcomm Atheros AR9271 802.11n                                                                        | 1        | 2.33%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                                       | 1        | 2.33%   |
| Microsoft Xbox 360 Wireless Adapter                                                                    | 1        | 2.33%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                                | 1        | 2.33%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter                                                    | 1        | 2.33%   |
| Intel Wireless 3160                                                                                    | 1        | 2.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                                       | 1        | 2.33%   |
| Gemtek WUBR-177G [Ralink RT2571W]                                                                      | 1        | 2.33%   |
| Broadcom Limited BCM4311 802.11b/g WLAN                                                                | 1        | 2.33%   |
| Broadcom BCM43225 802.11b/g/n                                                                          | 1        | 2.33%   |
| Belkin Components F5D7050 Wireless G Adapter v5000 [Realtek RTL8187B]                                  | 1        | 2.33%   |
| ASUS WL-167G v2 802.11g Adapter [Ralink RT2571W]                                                       | 1        | 2.33%   |
| ASUS USB-N14 802.11b/g/n (2x2) Wireless Adapter [Ralink RT5372]                                        | 1        | 2.33%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]                                              | 1        | 2.33%   |
| ASUS 802.11n Network Adapter                                                                           | 1        | 2.33%   |
| 802.11g Adapter [Linksys WUSB54GC v3] WUSB600N v2 Dual-Band Wireless-N Network Adapter [Ralink RT3572] | 1        | 2.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 51       | 56.04%  |
| Intel                             | 19       | 20.88%  |
| Broadcom                          | 6        | 6.59%   |
| Nvidia                            | 3        | 3.3%    |
| Qualcomm Atheros                  | 2        | 2.2%    |
| Marvell Technology Group          | 2        | 2.2%    |
| ZTE WCDMA Technologies MSM        | 1        | 1.1%    |
| Sundance Technology Inc / IC Plus | 1        | 1.1%    |
| Samsung Electronics               | 1        | 1.1%    |
| MediaTek                          | 1        | 1.1%    |
| Lenovo                            | 1        | 1.1%    |
| Huawei Technologies               | 1        | 1.1%    |
| ASIX Electronics                  | 1        | 1.1%    |
| 3Com                              | 1        | 1.1%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 44       | 45.83%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 5        | 5.21%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 4        | 4.17%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 3        | 3.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 2        | 2.08%   |
| Realtek RTL8125 2.5GbE Controller                                             | 2        | 2.08%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 2        | 2.08%   |
| ZTE WCDMA MSM ZTE Blade A54                                                   | 1        | 1.04%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY    | 1        | 1.04%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 1        | 1.04%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                   | 1        | 1.04%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 1        | 1.04%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 1        | 1.04%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1        | 1.04%   |
| Nvidia MCP77 Ethernet                                                         | 1        | 1.04%   |
| Nvidia MCP61 Ethernet                                                         | 1        | 1.04%   |
| Nvidia CK804 Ethernet Controller                                              | 1        | 1.04%   |
| MediaTek Infinix HOT 50i                                                      | 1        | 1.04%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1        | 1.04%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                             | 1        | 1.04%   |
| Lenovo Thinkpad LAN                                                           | 1        | 1.04%   |
| Intel I211 Gigabit Network Connection                                         | 1        | 1.04%   |
| Intel Ethernet Controller I225-V                                              | 1        | 1.04%   |
| Intel Ethernet Connection I217-LM                                             | 1        | 1.04%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1        | 1.04%   |
| Intel Ethernet Connection (17) I219-V                                         | 1        | 1.04%   |
| Intel 82578DC Gigabit Network Connection                                      | 1        | 1.04%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 1.04%   |
| Intel 82567LF-3 Gigabit Network Connection                                    | 1        | 1.04%   |
| Intel 82566DC-2 Gigabit Network Connection                                    | 1        | 1.04%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 1        | 1.04%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)                        | 1        | 1.04%   |
| Huawei FOA-LX9                                                                | 1        | 1.04%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 1        | 1.04%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 1        | 1.04%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                       | 1        | 1.04%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                        | 1        | 1.04%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                         | 1        | 1.04%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                               | 1        | 1.04%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 1        | 1.04%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 83       | 68.03%  |
| WiFi     | 39       | 31.97%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 62       | 70.45%  |
| WiFi     | 26       | 29.55%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 59       | 70.24%  |
| 2     | 21       | 25%     |
| 3     | 2        | 2.38%   |
| 4     | 1        | 1.19%   |
| 0     | 1        | 1.19%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 63       | 75%     |
| Yes  | 21       | 25%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 8        | 44.44%  |
| Intel                           | 4        | 22.22%  |
| Realtek Semiconductor           | 2        | 11.11%  |
| Qualcomm Atheros Communications | 1        | 5.56%   |
| Lite-On Technology              | 1        | 5.56%   |
| IMC Networks                    | 1        | 5.56%   |
| Broadcom                        | 1        | 5.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 8        | 44.44%  |
| Realtek Bluetooth Radio                             | 2        | 11.11%  |
| Intel AX200 Bluetooth                               | 2        | 11.11%  |
| Qualcomm Atheros AR3011 Bluetooth                   | 1        | 5.56%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1        | 5.56%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 5.56%   |
| Intel Bluetooth wireless interface                  | 1        | 5.56%   |
| IMC Networks Bluetooth Radio                        | 1        | 5.56%   |
| Broadcom HP Bluethunder                             | 1        | 5.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 55       | 43.31%  |
| AMD                   | 34       | 26.77%  |
| Nvidia                | 21       | 16.54%  |
| C-Media Electronics   | 5        | 3.94%   |
| JMTek                 | 2        | 1.57%   |
| Creative Labs         | 2        | 1.57%   |
| ULi Electronics       | 1        | 0.79%   |
| Texas Instruments     | 1        | 0.79%   |
| Realtek Semiconductor | 1        | 0.79%   |
| Logitech              | 1        | 0.79%   |
| Hewlett-Packard       | 1        | 0.79%   |
| GN Netcom             | 1        | 0.79%   |
| Giga-Byte Technology  | 1        | 0.79%   |
| Ensoniq               | 1        | 0.79%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                                      | 10       | 7.04%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 9        | 6.34%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 8        | 5.63%   |
| AMD Ryzen HD Audio Controller                                                     | 6        | 4.23%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 5        | 3.52%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 5        | 3.52%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 4        | 2.82%   |
| AMD FCH Azalia Controller                                                         | 4        | 2.82%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 3        | 2.11%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 3        | 2.11%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 3        | 2.11%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 3        | 2.11%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 3        | 2.11%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 3        | 2.11%   |
| Nvidia TU116 High Definition Audio Controller                                     | 2        | 1.41%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 2        | 1.41%   |
| Nvidia High Definition Audio Controller                                           | 2        | 1.41%   |
| Nvidia GP106 High Definition Audio Controller                                     | 2        | 1.41%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 2        | 1.41%   |
| Nvidia GF108 High Definition Audio Controller                                     | 2        | 1.41%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 2        | 1.41%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                 | 2        | 1.41%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 2        | 1.41%   |
| Intel Alder Lake-S HD Audio Controller                                            | 2        | 1.41%   |
| Intel 631xESB/632xESB High Definition Audio Controller                            | 2        | 1.41%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 2        | 1.41%   |
| C-Media Electronics CM108 Audio Controller                                        | 2        | 1.41%   |
| AMD Wrestler HDMI Audio                                                           | 2        | 1.41%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 2        | 1.41%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                       | 2        | 1.41%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 2        | 1.41%   |
| ULi Electronics HD Audio Controller                                               | 1        | 0.7%    |
| Texas Instruments PCM2902C Audio CODEC                                            | 1        | 0.7%    |
| Realtek Semiconductor Realtek USB2.0 Audio                                        | 1        | 0.7%    |
| Nvidia MCP73 High Definition Audio                                                | 1        | 0.7%    |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                         | 1        | 0.7%    |
| Nvidia MCP61 High Definition Audio                                                | 1        | 0.7%    |
| Nvidia GP108 High Definition Audio Controller                                     | 1        | 0.7%    |
| Nvidia GP107GL High Definition Audio Controller                                   | 1        | 0.7%    |
| Nvidia GP104 High Definition Audio Controller                                     | 1        | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 21       | 29.17%  |
| Kingston            | 11       | 15.28%  |
| Samsung Electronics | 7        | 9.72%   |
| Micron Technology   | 6        | 8.33%   |
| Corsair             | 5        | 6.94%   |
| SK hynix            | 4        | 5.56%   |
| Unknown             | 2        | 2.78%   |
| Unknown (ABCD)      | 1        | 1.39%   |
| Unknown (0x7F61)    | 1        | 1.39%   |
| Unknown (0x0080)    | 1        | 1.39%   |
| Unifosa             | 1        | 1.39%   |
| Qumo                | 1        | 1.39%   |
| Patriot             | 1        | 1.39%   |
| GOODRAM             | 1        | 1.39%   |
| GeIL                | 1        | 1.39%   |
| G.Skill             | 1        | 1.39%   |
| G Skil              | 1        | 1.39%   |
| Crucial             | 1        | 1.39%   |
| Avant               | 1        | 1.39%   |
| 2C0C1121390963FE    | 1        | 1.39%   |
| 2C0C1121390963FD    | 1        | 1.39%   |
| 2C0C1121390963F9    | 1        | 1.39%   |
| 2C0C1121390963F8    | 1        | 1.39%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 2        | 2.53%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 2        | 2.53%   |
| Samsung RAM M3 78T5663QZ3-CF7 2GB DIMM DDR2 800MT/s            | 2        | 2.53%   |
| Unknown                                                        | 2        | 2.53%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                      | 1        | 1.27%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                        | 1        | 1.27%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                      | 1        | 1.27%   |
| Unknown RAM Module 4GB DIMM DDR2 800MT/s                       | 1        | 1.27%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                        | 1        | 1.27%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                       | 1        | 1.27%   |
| Unknown RAM Module 2048MB SODIMM DDR2                          | 1        | 1.27%   |
| Unknown RAM Module 2048MB DIMM SDRAM                           | 1        | 1.27%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                    | 1        | 1.27%   |
| Unknown RAM Module 2048MB DIMM DDR2                            | 1        | 1.27%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                     | 1        | 1.27%   |
| Unknown RAM Module 2048MB DIMM DDR 133MT/s                     | 1        | 1.27%   |
| Unknown RAM Module 2048MB DIMM DDR                             | 1        | 1.27%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                         | 1        | 1.27%   |
| Unknown RAM Module 1GB DIMM DDR 400MT/s                        | 1        | 1.27%   |
| Unknown RAM Module 1024MB DIMM SDRAM                           | 1        | 1.27%   |
| Unknown RAM Module 1024MB DIMM DDR2                            | 1        | 1.27%   |
| Unknown RAM Module 1024MB DIMM DDR 133MT/s                     | 1        | 1.27%   |
| Unknown RAM Module 1024MB DIMM DDR                             | 1        | 1.27%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2133MT/s | 1        | 1.27%   |
| Unknown (0x7F61) RAM Module 1GB FB-DIMM DDR2 667MT/s           | 1        | 1.27%   |
| Unknown (0x0080) RAM Module 16GB SODIMM DDR4 3200MT/s          | 1        | 1.27%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s              | 1        | 1.27%   |
| Unifosa RAM GU502203EP0201 1GB DIMM DDR3 1333MT/s              | 1        | 1.27%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s          | 1        | 1.27%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s           | 1        | 1.27%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 1        | 1.27%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s           | 1        | 1.27%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s           | 1        | 1.27%   |
| SK hynix RAM HMT112U6TFR8C-H9 1GB DIMM DDR3 1333MT/s           | 1        | 1.27%   |
| Samsung RAM Module 4GB DIMM DDR3 1067MT/s                      | 1        | 1.27%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s            | 1        | 1.27%   |
| Samsung RAM M378B5173DB0-CK0 4096MB DIMM DDR3 1600MT/s         | 1        | 1.27%   |
| Samsung RAM M378B2873FH0-CH9 1GB DIMM DDR3 1333MT/s            | 1        | 1.27%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s            | 1        | 1.27%   |
| Qumo RAM Module 4096MB DIMM DDR3 1333MT/s                      | 1        | 1.27%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 16       | 26.23%  |
| DDR4    | 13       | 21.31%  |
| DDR2    | 11       | 18.03%  |
| SDRAM   | 9        | 14.75%  |
| Unknown | 6        | 9.84%   |
| DDR     | 4        | 6.56%   |
| LPDDR4  | 1        | 1.64%   |
| DDR5    | 1        | 1.64%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 55       | 90.16%  |
| SODIMM  | 4        | 6.56%   |
| FB-DIMM | 2        | 3.28%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 19       | 28.36%  |
| 2048  | 19       | 28.36%  |
| 1024  | 11       | 16.42%  |
| 16384 | 8        | 11.94%  |
| 8192  | 8        | 11.94%  |
| 32768 | 1        | 1.49%   |
| 512   | 1        | 1.49%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 11       | 16.92%  |
| 1333    | 9        | 13.85%  |
| Unknown | 8        | 12.31%  |
| 3200    | 5        | 7.69%   |
| 800     | 5        | 7.69%   |
| 667     | 4        | 6.15%   |
| 3400    | 2        | 3.08%   |
| 2400    | 2        | 3.08%   |
| 2133    | 2        | 3.08%   |
| 1639    | 2        | 3.08%   |
| 400     | 2        | 3.08%   |
| 49926   | 1        | 1.54%   |
| 19791   | 1        | 1.54%   |
| 6400    | 1        | 1.54%   |
| 3933    | 1        | 1.54%   |
| 3800    | 1        | 1.54%   |
| 3733    | 1        | 1.54%   |
| 3600    | 1        | 1.54%   |
| 3500    | 1        | 1.54%   |
| 2734    | 1        | 1.54%   |
| 1800    | 1        | 1.54%   |
| 1067    | 1        | 1.54%   |
| 1033    | 1        | 1.54%   |
| 133     | 1        | 1.54%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Canon G1020 series | 1        | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Mustek Systems  | 1        | 33.33%  |
| Hewlett-Packard | 1        | 33.33%  |
| Canon           | 1        | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Mustek Systems ScanExpress 1200 CU | 1        | 33.33%  |
| HP ScanJet 5200c                   | 1        | 33.33%  |
| Canon CanoScan LiDE 110            | 1        | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Chicony Electronics     | 3        | 21.43%  |
| Microdia                | 2        | 14.29%  |
| Logitech                | 2        | 14.29%  |
| Z-Star Microelectronics | 1        | 7.14%   |
| Sweex                   | 1        | 7.14%   |
| Sunplus IT              | 1        | 7.14%   |
| Microsoft               | 1        | 7.14%   |
| Jieli Technology        | 1        | 7.14%   |
| Hewlett-Packard         | 1        | 7.14%   |
| Generalplus Technology  | 1        | 7.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Chicony HP High Definition 1MP Webcam             | 2        | 14.29%  |
| Z-Star Venus USB2.0 Camera                        | 1        | 7.14%   |
| Sweex USB keyboard                                | 1        | 7.14%   |
| Sunplus IT PC Camera                              | 1        | 7.14%   |
| Microsoft Microsoft LifeCam HD-6000 for Notebooks | 1        | 7.14%   |
| Microdia USB 2.0 Camera                           | 1        | 7.14%   |
| Microdia CyberTrack H7                            | 1        | 7.14%   |
| Logitech Webcam C270                              | 1        | 7.14%   |
| Logitech Webcam C110                              | 1        | 7.14%   |
| Jieli USB PHY 2.0                                 | 1        | 7.14%   |
| HP Webcam HD 2300                                 | 1        | 7.14%   |
| Generalplus GENERAL WEBCAM                        | 1        | 7.14%   |
| Chicony HP Webcam                                 | 1        | 7.14%   |

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
| 0     | 73       | 85.88%  |
| 1     | 11       | 12.94%  |
| 2     | 1        | 1.18%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type             | Desktops | Percent |
|------------------|----------|---------|
| Graphics card    | 7        | 53.85%  |
| Net/wireless     | 4        | 30.77%  |
| Unassigned class | 1        | 7.69%   |
| Network          | 1        | 7.69%   |

