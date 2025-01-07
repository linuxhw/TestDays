Elementary - Tested Hardware & Statistics (Desktops)
----------------------------------------------------

A project to collect tested hardware configurations for Elementary.

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

Total: 878

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | G31TM-P21                   | [7f868dd6f9](https://linux-hardware.org/?probe=7f868dd6f9) | Jan 06, 2025 |
| ASUSTek       | PRIME H310M-E R2.0          | [79752b904b](https://linux-hardware.org/?probe=79752b904b) | Jan 04, 2025 |
| Intel         | H61                         | [0f76193421](https://linux-hardware.org/?probe=0f76193421) | Jan 02, 2025 |
| MSI           | A88XM-E35 V2                | [d3df8a394a](https://linux-hardware.org/?probe=d3df8a394a) | Dec 30, 2024 |
| ASUSTek       | H110M-D                     | [a61b42dd42](https://linux-hardware.org/?probe=a61b42dd42) | Dec 29, 2024 |
| ASRock        | X570 Extreme4               | [65cad1da61](https://linux-hardware.org/?probe=65cad1da61) | Dec 26, 2024 |
| Gigabyte      | B85M-HD3                    | [83d5947a2c](https://linux-hardware.org/?probe=83d5947a2c) | Dec 24, 2024 |
| Gigabyte      | B560 DS3H AC-Y1             | [4e79bebde8](https://linux-hardware.org/?probe=4e79bebde8) | Dec 24, 2024 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [89e8e5ad41](https://linux-hardware.org/?probe=89e8e5ad41) | Dec 24, 2024 |
| MSI           | PRO B760M-P DDR4            | [a649caaa82](https://linux-hardware.org/?probe=a649caaa82) | Dec 23, 2024 |
| MSI           | PRO B760-P WIFI DDR4        | [59c289d5b9](https://linux-hardware.org/?probe=59c289d5b9) | Dec 22, 2024 |
| Dell          | 0MWYPT A00                  | [98cc5ad973](https://linux-hardware.org/?probe=98cc5ad973) | Dec 22, 2024 |
| Dell          | 0MWYPT A00                  | [dd73af7555](https://linux-hardware.org/?probe=dd73af7555) | Dec 22, 2024 |
| Gigabyte      | B560 DS3H AC-Y1             | [4c934647d2](https://linux-hardware.org/?probe=4c934647d2) | Dec 21, 2024 |
| Dell          | 00V62H A01                  | [8e8317c6a6](https://linux-hardware.org/?probe=8e8317c6a6) | Dec 19, 2024 |
| Gigabyte      | Z77-D3H                     | [9a64691207](https://linux-hardware.org/?probe=9a64691207) | Dec 17, 2024 |
| ASUSTek       | P8H67-M PRO                 | [987844d0b8](https://linux-hardware.org/?probe=987844d0b8) | Dec 17, 2024 |
| HP            | 8266                        | [ccd7d6b235](https://linux-hardware.org/?probe=ccd7d6b235) | Dec 17, 2024 |
| GEEKOM        | A8                          | [821fae98e5](https://linux-hardware.org/?probe=821fae98e5) | Dec 17, 2024 |
| Huanan        | X99-F8 GAMING V5.0          | [28d3412139](https://linux-hardware.org/?probe=28d3412139) | Dec 17, 2024 |
| HP            | 83E8                        | [77d40d025a](https://linux-hardware.org/?probe=77d40d025a) | Dec 16, 2024 |
| Intel         | Unknown                     | [fcbbdc5c06](https://linux-hardware.org/?probe=fcbbdc5c06) | Dec 16, 2024 |
| Dell          | 0F6X5P A00                  | [059cf0cd47](https://linux-hardware.org/?probe=059cf0cd47) | Dec 15, 2024 |
| Dell          | 0F6X5P A00                  | [f9eae65d13](https://linux-hardware.org/?probe=f9eae65d13) | Dec 14, 2024 |
| HP            | 8299                        | [44a762b74e](https://linux-hardware.org/?probe=44a762b74e) | Dec 14, 2024 |
| HP            | 8299                        | [f0c7982d81](https://linux-hardware.org/?probe=f0c7982d81) | Dec 14, 2024 |
| ASUSTek       | PRIME B450M-A               | [262a2aa975](https://linux-hardware.org/?probe=262a2aa975) | Dec 13, 2024 |
| Intel         | B75 V1.1                    | [d6aad9d651](https://linux-hardware.org/?probe=d6aad9d651) | Dec 03, 2024 |
| Dell          | 00V62H A01                  | [a12ee189e3](https://linux-hardware.org/?probe=a12ee189e3) | Dec 02, 2024 |
| Intel         | X99-P4 V5.11                | [b5079a1a8d](https://linux-hardware.org/?probe=b5079a1a8d) | Dec 02, 2024 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | [ffa565d696](https://linux-hardware.org/?probe=ffa565d696) | Dec 02, 2024 |
| Intel         | D945GCL AAD75361-301        | [f04b1a58c2](https://linux-hardware.org/?probe=f04b1a58c2) | Dec 01, 2024 |
| Intel         | D945GCL AAD75361-301        | [fc715bb336](https://linux-hardware.org/?probe=fc715bb336) | Dec 01, 2024 |
| ASRock        | H310CM-HG4                  | [86f4d79f62](https://linux-hardware.org/?probe=86f4d79f62) | Dec 01, 2024 |
| Huanan        | X99-F8 GAMING V5.0          | [dbc6940414](https://linux-hardware.org/?probe=dbc6940414) | Nov 29, 2024 |
| HP            | 3647h                       | [de1eb15f76](https://linux-hardware.org/?probe=de1eb15f76) | Nov 28, 2024 |
| Lenovo        | ThinkCentre M81 7517A2F     | [51de0395d0](https://linux-hardware.org/?probe=51de0395d0) | Nov 27, 2024 |
| Lenovo        | ThinkCentre M81 7517A2F     | [6ae2f479e0](https://linux-hardware.org/?probe=6ae2f479e0) | Nov 26, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [0b3205081d](https://linux-hardware.org/?probe=0b3205081d) | Nov 22, 2024 |
| ASRock        | 945GCM-S                    | [c1060979e3](https://linux-hardware.org/?probe=c1060979e3) | Nov 21, 2024 |
| ASRock        | X570 Phantom Gaming 4       | [b5f2062c2c](https://linux-hardware.org/?probe=b5f2062c2c) | Nov 18, 2024 |
| HP            | 1998                        | [021e8262ce](https://linux-hardware.org/?probe=021e8262ce) | Nov 16, 2024 |
| HP            | 212B                        | [35097b8ab0](https://linux-hardware.org/?probe=35097b8ab0) | Nov 15, 2024 |
| ASUSTek       | PRIME B365M-A               | [fc06ee6598](https://linux-hardware.org/?probe=fc06ee6598) | Nov 10, 2024 |
| MSI           | Z390-A PRO                  | [68c27eb24c](https://linux-hardware.org/?probe=68c27eb24c) | Nov 10, 2024 |
| MSI           | Z390-A PRO                  | [a6930afc53](https://linux-hardware.org/?probe=a6930afc53) | Nov 10, 2024 |
| ASRock        | B450M Pro4                  | [41cbe4313e](https://linux-hardware.org/?probe=41cbe4313e) | Nov 06, 2024 |
| Lenovo        | SHARKBAY NOK                | [f37b129292](https://linux-hardware.org/?probe=f37b129292) | Nov 05, 2024 |
| Gigabyte      | B550 UD AC-Y1               | [f146362156](https://linux-hardware.org/?probe=f146362156) | Nov 04, 2024 |
| ASRock        | Z390 Phantom Gaming-ITX/... | [0e0a0fd3c5](https://linux-hardware.org/?probe=0e0a0fd3c5) | Oct 30, 2024 |
| ASRock        | B450M Steel Legend          | [ee7a3727e4](https://linux-hardware.org/?probe=ee7a3727e4) | Oct 23, 2024 |
| ASUSTek       | PRIME B365M-A               | [25dc97604a](https://linux-hardware.org/?probe=25dc97604a) | Oct 22, 2024 |
| ASUSTek       | PRIME B460-PLUS             | [c16cede43b](https://linux-hardware.org/?probe=c16cede43b) | Oct 18, 2024 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [043f4904ae](https://linux-hardware.org/?probe=043f4904ae) | Oct 15, 2024 |
| ASRock        | B450M Steel Legend          | [0615e499e7](https://linux-hardware.org/?probe=0615e499e7) | Oct 13, 2024 |
| Dell          | 0P096C A00                  | [29a648fa32](https://linux-hardware.org/?probe=29a648fa32) | Oct 05, 2024 |
| Dell          | 0P096C A00                  | [5a4a3dac5c](https://linux-hardware.org/?probe=5a4a3dac5c) | Oct 05, 2024 |
| Intel         | JSL MRD                     | [6be233c711](https://linux-hardware.org/?probe=6be233c711) | Oct 02, 2024 |
| MSI           | Z270 GAMING PRO CARBON      | [add5dd6115](https://linux-hardware.org/?probe=add5dd6115) | Sep 29, 2024 |
| Intel         | IPC-ADN2L                   | [7aaa04ef0f](https://linux-hardware.org/?probe=7aaa04ef0f) | Sep 27, 2024 |
| MSI           | Z97S SLI Krait Edition      | [a44bd15d85](https://linux-hardware.org/?probe=a44bd15d85) | Sep 17, 2024 |
| MSI           | Z97S SLI Krait Edition      | [f73ff9c739](https://linux-hardware.org/?probe=f73ff9c739) | Sep 16, 2024 |
| Lenovo        | SHARKBAY NOK                | [7a6f092e7a](https://linux-hardware.org/?probe=7a6f092e7a) | Sep 13, 2024 |
| ASUSTek       | ET2700I                     | [0faf2541ce](https://linux-hardware.org/?probe=0faf2541ce) | Sep 11, 2024 |
| Intel         | IPC-ADN2L                   | [274c57803d](https://linux-hardware.org/?probe=274c57803d) | Sep 09, 2024 |
| Pegatron      | 2A94h                       | [5a721a5edc](https://linux-hardware.org/?probe=5a721a5edc) | Sep 08, 2024 |
| Gigabyte      | H81M-S2H                    | [8c3768316c](https://linux-hardware.org/?probe=8c3768316c) | Sep 05, 2024 |
| Lenovo        | ThinkCentre Edge71 1607R... | [29cdb0e2f5](https://linux-hardware.org/?probe=29cdb0e2f5) | Sep 02, 2024 |
| ASRock        | J5040-ITX                   | [fcfa738334](https://linux-hardware.org/?probe=fcfa738334) | Sep 01, 2024 |
| MSI           | H77MA-G43                   | [73df0e9be3](https://linux-hardware.org/?probe=73df0e9be3) | Aug 28, 2024 |
| MSI           | H77MA-G43                   | [c3687b0959](https://linux-hardware.org/?probe=c3687b0959) | Aug 28, 2024 |
| Gigabyte      | Z790 UD                     | [fd328d5314](https://linux-hardware.org/?probe=fd328d5314) | Aug 28, 2024 |
| Gigabyte      | Z790 UD                     | [01f402c213](https://linux-hardware.org/?probe=01f402c213) | Aug 28, 2024 |
| ASUSTek       | ET2700I                     | [46b00a17dd](https://linux-hardware.org/?probe=46b00a17dd) | Aug 28, 2024 |
| ASUSTek       | ET2700I                     | [69b47ec3cd](https://linux-hardware.org/?probe=69b47ec3cd) | Aug 28, 2024 |
| ASRock        | B450M/ac R2.0               | [0946b4faad](https://linux-hardware.org/?probe=0946b4faad) | Aug 28, 2024 |
| HP            | 0B54h D                     | [3e361ce6dd](https://linux-hardware.org/?probe=3e361ce6dd) | Aug 27, 2024 |
| Pegatron      | 2A94h                       | [6ec199373b](https://linux-hardware.org/?probe=6ec199373b) | Aug 25, 2024 |
| ASRock        | B450M/ac R2.0               | [0026cbe5e3](https://linux-hardware.org/?probe=0026cbe5e3) | Aug 25, 2024 |
| HP            | 1495                        | [76595d0137](https://linux-hardware.org/?probe=76595d0137) | Aug 24, 2024 |
| HP            | 1495                        | [d7f96fb46e](https://linux-hardware.org/?probe=d7f96fb46e) | Aug 24, 2024 |
| Dell          | 0PU052                      | [95f1504d6a](https://linux-hardware.org/?probe=95f1504d6a) | Aug 22, 2024 |
| Dell          | 0VG93V A00                  | [b81443c816](https://linux-hardware.org/?probe=b81443c816) | Aug 18, 2024 |
| ASRock        | H61M-VG3                    | [a377e590da](https://linux-hardware.org/?probe=a377e590da) | Aug 18, 2024 |
| Dell          | 0VG93V A00                  | [c6be5f6727](https://linux-hardware.org/?probe=c6be5f6727) | Aug 17, 2024 |
| ASUSTek       | B85M-E/BR                   | [9b3874ab72](https://linux-hardware.org/?probe=9b3874ab72) | Aug 13, 2024 |
| ASRock        | B450M Steel Legend          | [48b9938f65](https://linux-hardware.org/?probe=48b9938f65) | Aug 08, 2024 |
| ASRock        | H81M-DGS R2.0               | [d3e0797e5b](https://linux-hardware.org/?probe=d3e0797e5b) | Aug 07, 2024 |
| ASRock        | H81M-DGS R2.0               | [2b569bdccd](https://linux-hardware.org/?probe=2b569bdccd) | Aug 07, 2024 |
| Gigabyte      | H81M-S2H                    | [66bcb40057](https://linux-hardware.org/?probe=66bcb40057) | Aug 05, 2024 |
| Gigabyte      | H81M-S2H                    | [dcf87ade71](https://linux-hardware.org/?probe=dcf87ade71) | Aug 03, 2024 |
| ASUSTek       | P5G41-M LX                  | [b3b334d874](https://linux-hardware.org/?probe=b3b334d874) | Aug 01, 2024 |
| Dell          | 0MG3PY A00                  | [558c13f467](https://linux-hardware.org/?probe=558c13f467) | Aug 01, 2024 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [1d828595b9](https://linux-hardware.org/?probe=1d828595b9) | Jul 30, 2024 |
| AZW           | MINI S                      | [d8754c0201](https://linux-hardware.org/?probe=d8754c0201) | Jul 25, 2024 |
| Gigabyte      | H310M H x.x                 | [c89938fbbb](https://linux-hardware.org/?probe=c89938fbbb) | Jul 25, 2024 |
| ASRock        | B360M-HDV                   | [94cbafc49e](https://linux-hardware.org/?probe=94cbafc49e) | Jul 24, 2024 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [2c279e3d69](https://linux-hardware.org/?probe=2c279e3d69) | Jul 22, 2024 |
| Gigabyte      | B550 AORUS ELITE            | [8f90dcefce](https://linux-hardware.org/?probe=8f90dcefce) | Jul 19, 2024 |
| ASUSTek       | P8B75-M LX                  | [7c793c4a04](https://linux-hardware.org/?probe=7c793c4a04) | Jul 18, 2024 |
| ASUSTek       | P8B75-M LX                  | [64685a555f](https://linux-hardware.org/?probe=64685a555f) | Jul 18, 2024 |
| AMI           | Intel                       | [461763ad20](https://linux-hardware.org/?probe=461763ad20) | Jul 17, 2024 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [a675a84975](https://linux-hardware.org/?probe=a675a84975) | Jul 12, 2024 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [d7d8b022c8](https://linux-hardware.org/?probe=d7d8b022c8) | Jul 12, 2024 |
| ASRock        | A320M-HDV R4.0              | [be9af5afe2](https://linux-hardware.org/?probe=be9af5afe2) | Jul 08, 2024 |
| Dell          | 0K240Y A03                  | [fd2e6133c8](https://linux-hardware.org/?probe=fd2e6133c8) | Jul 07, 2024 |
| Dell          | 0K240Y A03                  | [7409d9aee8](https://linux-hardware.org/?probe=7409d9aee8) | Jul 07, 2024 |
| Dell          | 0K240Y A03                  | [25538a3377](https://linux-hardware.org/?probe=25538a3377) | Jul 06, 2024 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [605b774f63](https://linux-hardware.org/?probe=605b774f63) | Jul 02, 2024 |
| ASUSTek       | H110M-A/M.2                 | [ef55e011c4](https://linux-hardware.org/?probe=ef55e011c4) | Jun 28, 2024 |
| HP            | 0B54h D                     | [a1df6af082](https://linux-hardware.org/?probe=a1df6af082) | Jun 27, 2024 |
| MSI           | B365M PRO-VDH               | [bf340a8641](https://linux-hardware.org/?probe=bf340a8641) | Jun 25, 2024 |
| ECS           | H110M-C3D/C3V               | [0029341c8c](https://linux-hardware.org/?probe=0029341c8c) | Jun 18, 2024 |
| MSI           | MS-7267                     | [59fc27aa13](https://linux-hardware.org/?probe=59fc27aa13) | Jun 17, 2024 |
| MSI           | MS-7267                     | [02fc0d7625](https://linux-hardware.org/?probe=02fc0d7625) | Jun 17, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [f5a682fbe7](https://linux-hardware.org/?probe=f5a682fbe7) | Jun 16, 2024 |
| ASUSTek       | 970 PRO GAMING/AURA         | [8d51939a60](https://linux-hardware.org/?probe=8d51939a60) | Jun 16, 2024 |
| ASUSTek       | 970 PRO GAMING/AURA         | [8eac8a90fb](https://linux-hardware.org/?probe=8eac8a90fb) | Jun 15, 2024 |
| Gigabyte      | B760M DS3H AX DDR4          | [b1067e137b](https://linux-hardware.org/?probe=b1067e137b) | Jun 11, 2024 |
| Gigabyte      | GA-990FX-GAMING             | [af3d2280af](https://linux-hardware.org/?probe=af3d2280af) | Jun 10, 2024 |
| Dell          | 00V62H A01                  | [6cc3abff8f](https://linux-hardware.org/?probe=6cc3abff8f) | Jun 06, 2024 |
| ASUSTek       | PRIME H510M-K R2.0          | [2f2a24345a](https://linux-hardware.org/?probe=2f2a24345a) | Jun 05, 2024 |
| ASUSTek       | PRIME H510M-K R2.0          | [a15ecb15f8](https://linux-hardware.org/?probe=a15ecb15f8) | Jun 05, 2024 |
| ASUSTek       | H110M-A/M.2                 | [0e706f4bcd](https://linux-hardware.org/?probe=0e706f4bcd) | May 30, 2024 |
| Gigabyte      | H310M H x.x                 | [6c986e95fa](https://linux-hardware.org/?probe=6c986e95fa) | May 17, 2024 |
| Lenovo        | ThinkCentre A58 761179G     | [0f92c56231](https://linux-hardware.org/?probe=0f92c56231) | May 17, 2024 |
| Dell          | 08VX12 A00                  | [da62c2beb8](https://linux-hardware.org/?probe=da62c2beb8) | May 14, 2024 |
| ASUSTek       | STRIX Z270F GAMING          | [2fadb82e07](https://linux-hardware.org/?probe=2fadb82e07) | May 14, 2024 |
| Dell          | 0GY6Y8 A02                  | [7982277925](https://linux-hardware.org/?probe=7982277925) | May 13, 2024 |
| ASUSTek       | PRIME B460M-K               | [fea6956058](https://linux-hardware.org/?probe=fea6956058) | May 08, 2024 |
| ASUSTek       | PRIME H510M-A               | [e475e36ab0](https://linux-hardware.org/?probe=e475e36ab0) | May 06, 2024 |
| ASUSTek       | PRIME A320M-K               | [0f43840d58](https://linux-hardware.org/?probe=0f43840d58) | May 06, 2024 |
| HP            | 0B4Ch D                     | [29d73efd4a](https://linux-hardware.org/?probe=29d73efd4a) | Apr 30, 2024 |
| ASUSTek       | PRIME A320M-K               | [022ece0282](https://linux-hardware.org/?probe=022ece0282) | Apr 30, 2024 |
| Medion        | MS-7797                     | [a72c95890e](https://linux-hardware.org/?probe=a72c95890e) | Apr 28, 2024 |
| Gigabyte      | B250M-D2VX-SI-CF            | [5c277491cf](https://linux-hardware.org/?probe=5c277491cf) | Apr 27, 2024 |
| ASUSTek       | TUF X470-PLUS GAMING        | [6609c77480](https://linux-hardware.org/?probe=6609c77480) | Apr 26, 2024 |
| ASUSTek       | P8H77-M PRO                 | [ee55351883](https://linux-hardware.org/?probe=ee55351883) | Apr 25, 2024 |
| ASUSTek       | PRIME H510M-A               | [c12789125b](https://linux-hardware.org/?probe=c12789125b) | Apr 24, 2024 |
| Medion        | MS-7797                     | [810a7d7810](https://linux-hardware.org/?probe=810a7d7810) | Apr 22, 2024 |
| ECS           | H110M-C3D/C3V               | [7fffccead5](https://linux-hardware.org/?probe=7fffccead5) | Apr 17, 2024 |
| Dell          | 0D24M8 A02                  | [96b0ae2f86](https://linux-hardware.org/?probe=96b0ae2f86) | Apr 16, 2024 |
| Gigabyte      | F2A68HM-S1                  | [32237e05f1](https://linux-hardware.org/?probe=32237e05f1) | Apr 15, 2024 |
| Medion        | Z370H4-EM                   | [39cb6c0afb](https://linux-hardware.org/?probe=39cb6c0afb) | Apr 13, 2024 |
| MSI           | MEG Z590 UNIFY              | [88f634c670](https://linux-hardware.org/?probe=88f634c670) | Apr 11, 2024 |
| MSI           | MEG Z590 UNIFY              | [2336b3cd38](https://linux-hardware.org/?probe=2336b3cd38) | Apr 11, 2024 |
| HP            | 18E7                        | [467ac72efe](https://linux-hardware.org/?probe=467ac72efe) | Apr 07, 2024 |
| Gigabyte      | 945GME-DS2                  | [37085a5c3f](https://linux-hardware.org/?probe=37085a5c3f) | Apr 06, 2024 |
| HP            | 18E7                        | [9dadc64d70](https://linux-hardware.org/?probe=9dadc64d70) | Apr 03, 2024 |
| ASUSTek       | EX-B150M-V3                 | [0c643b047e](https://linux-hardware.org/?probe=0c643b047e) | Apr 01, 2024 |
| ASUSTek       | EX-B150M-V3                 | [c6772f244f](https://linux-hardware.org/?probe=c6772f244f) | Apr 01, 2024 |
| ASUSTek       | P8H77-M PRO                 | [f30dd46998](https://linux-hardware.org/?probe=f30dd46998) | Mar 29, 2024 |
| MSI           | MAG B660M MORTAR WIFI DD... | [a87aa51bf9](https://linux-hardware.org/?probe=a87aa51bf9) | Mar 29, 2024 |
| MSI           | A68HM-E33 V2                | [22b44252e3](https://linux-hardware.org/?probe=22b44252e3) | Mar 28, 2024 |
| Lenovo        | ThinkCentre Edge91 1895B... | [991944129e](https://linux-hardware.org/?probe=991944129e) | Mar 26, 2024 |
| Gigabyte      | A320M-S2H-CF                | [30717fbd15](https://linux-hardware.org/?probe=30717fbd15) | Mar 25, 2024 |
| ASUSTek       | M4A87TD/USB3                | [9a817cbe67](https://linux-hardware.org/?probe=9a817cbe67) | Mar 24, 2024 |
| ASUSTek       | H81M-P PLUS                 | [92aa3b7c70](https://linux-hardware.org/?probe=92aa3b7c70) | Mar 24, 2024 |
| ASUSTek       | H81M-P PLUS                 | [57ee067ff2](https://linux-hardware.org/?probe=57ee067ff2) | Mar 24, 2024 |
| HP            | 0B54h D                     | [7b38927e17](https://linux-hardware.org/?probe=7b38927e17) | Mar 23, 2024 |
| Unknown       | Unknown                     | [5af36d3a4e](https://linux-hardware.org/?probe=5af36d3a4e) | Mar 22, 2024 |
| HP            | 0B54h D                     | [0af537dbcd](https://linux-hardware.org/?probe=0af537dbcd) | Mar 22, 2024 |
| ASRock        | X570 Extreme4               | [f7bd9e9cce](https://linux-hardware.org/?probe=f7bd9e9cce) | Mar 21, 2024 |
| MSI           | A68HM-E33 V2                | [52b29bf885](https://linux-hardware.org/?probe=52b29bf885) | Mar 12, 2024 |
| ASRock        | H110M-HDS                   | [0b9ca9c2ca](https://linux-hardware.org/?probe=0b9ca9c2ca) | Mar 12, 2024 |
| ASRock        | H110M-HDS                   | [0d754901a3](https://linux-hardware.org/?probe=0d754901a3) | Mar 12, 2024 |
| Dell          | 0D24M8 A02                  | [70a8364913](https://linux-hardware.org/?probe=70a8364913) | Mar 11, 2024 |
| Dell          | 0M6C7G A00                  | [666c6ad495](https://linux-hardware.org/?probe=666c6ad495) | Mar 10, 2024 |
| Biostar       | B350GT5                     | [61f8cce525](https://linux-hardware.org/?probe=61f8cce525) | Mar 08, 2024 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [16b3359307](https://linux-hardware.org/?probe=16b3359307) | Mar 07, 2024 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [4d569e557d](https://linux-hardware.org/?probe=4d569e557d) | Mar 07, 2024 |
| Acer          | FIH57                       | [4b9a9a43f3](https://linux-hardware.org/?probe=4b9a9a43f3) | Mar 02, 2024 |
| HP            | 8434 11                     | [aa98b6327d](https://linux-hardware.org/?probe=aa98b6327d) | Mar 02, 2024 |
| HP            | 8434 11                     | [5b25b65016](https://linux-hardware.org/?probe=5b25b65016) | Mar 01, 2024 |
| Apple         | Mac-F221BEC8                | [10c92b676a](https://linux-hardware.org/?probe=10c92b676a) | Feb 29, 2024 |
| Dell          | 0D24M8 A02                  | [d67f57356b](https://linux-hardware.org/?probe=d67f57356b) | Feb 28, 2024 |
| Intel         | X79Turbo V1.x               | [09f942e7f4](https://linux-hardware.org/?probe=09f942e7f4) | Feb 26, 2024 |
| Gigabyte      | AB350-Gaming 3-CF           | [082b9f50ab](https://linux-hardware.org/?probe=082b9f50ab) | Feb 23, 2024 |
| Gigabyte      | H110N-CF                    | [c6a69fce12](https://linux-hardware.org/?probe=c6a69fce12) | Feb 10, 2024 |
| ASUSTek       | P5G41T-M LX3                | [fd10cd8983](https://linux-hardware.org/?probe=fd10cd8983) | Feb 09, 2024 |
| ASUSTek       | P5G41T-M LX3                | [ae6f0a23e2](https://linux-hardware.org/?probe=ae6f0a23e2) | Feb 09, 2024 |
| ASUSTek       | P8Z68-V PRO GEN3            | [d099546e70](https://linux-hardware.org/?probe=d099546e70) | Feb 07, 2024 |
| Intel         | X79Turbo V1.x               | [35c4b20053](https://linux-hardware.org/?probe=35c4b20053) | Feb 07, 2024 |
| Dell          | 0GDG8Y A00                  | [2cca1daa38](https://linux-hardware.org/?probe=2cca1daa38) | Feb 01, 2024 |
| ASRock        | B75M-DGS R2.0               | [cff86cc0d9](https://linux-hardware.org/?probe=cff86cc0d9) | Jan 27, 2024 |
| Dell          | 00V62H A01                  | [83f7e8b344](https://linux-hardware.org/?probe=83f7e8b344) | Jan 24, 2024 |
| Gigabyte      | EP43-UD3L                   | [6a2153a6b9](https://linux-hardware.org/?probe=6a2153a6b9) | Jan 21, 2024 |
| Dell          | 00V62H A01                  | [7104f7e7cf](https://linux-hardware.org/?probe=7104f7e7cf) | Jan 21, 2024 |
| Gigabyte      | B560M DS3H                  | [8ffb8f68ca](https://linux-hardware.org/?probe=8ffb8f68ca) | Jan 19, 2024 |
| Gigabyte      | EP43-UD3L                   | [8dc280e4fc](https://linux-hardware.org/?probe=8dc280e4fc) | Jan 13, 2024 |
| ASRock        | Z390 Phantom Gaming-ITX/... | [62374d5cbd](https://linux-hardware.org/?probe=62374d5cbd) | Jan 11, 2024 |
| ASRock        | Z390 Phantom Gaming-ITX/... | [f24b7483b8](https://linux-hardware.org/?probe=f24b7483b8) | Jan 11, 2024 |
| HP            | 3397                        | [3339eb00ce](https://linux-hardware.org/?probe=3339eb00ce) | Jan 03, 2024 |
| HP            | 0AA8h                       | [49435a98d1](https://linux-hardware.org/?probe=49435a98d1) | Dec 19, 2023 |
| HP            | 3397                        | [7b379848f1](https://linux-hardware.org/?probe=7b379848f1) | Dec 16, 2023 |
| HP            | 0AA8h                       | [5264c3d3e1](https://linux-hardware.org/?probe=5264c3d3e1) | Dec 16, 2023 |
| HP            | 0AA8h                       | [e20c0fc21b](https://linux-hardware.org/?probe=e20c0fc21b) | Dec 16, 2023 |
| ECS           | G41T-M                      | [a0017f196c](https://linux-hardware.org/?probe=a0017f196c) | Dec 14, 2023 |
| ASUSTek       | Z97-AR                      | [70936627e8](https://linux-hardware.org/?probe=70936627e8) | Dec 05, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [cfc7698579](https://linux-hardware.org/?probe=cfc7698579) | Dec 04, 2023 |
| ASUSTek       | PRIME A320M-K               | [5bbcf82cf2](https://linux-hardware.org/?probe=5bbcf82cf2) | Nov 30, 2023 |
| Jetway        | TI61M5                      | [dff0fcc796](https://linux-hardware.org/?probe=dff0fcc796) | Nov 25, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [541efb8e16](https://linux-hardware.org/?probe=541efb8e16) | Nov 24, 2023 |
| Jetway        | TI61M5                      | [968d83ba14](https://linux-hardware.org/?probe=968d83ba14) | Nov 21, 2023 |
| Dell          | 0XPDFK A01                  | [8b3abafe9b](https://linux-hardware.org/?probe=8b3abafe9b) | Nov 19, 2023 |
| Gigabyte      | B550M DS3H                  | [8def310709](https://linux-hardware.org/?probe=8def310709) | Nov 16, 2023 |
| Dell          | 03KWTV A00                  | [794f73f426](https://linux-hardware.org/?probe=794f73f426) | Nov 16, 2023 |
| ASUSTek       | PRIME A320M-K               | [5ddcb0cf64](https://linux-hardware.org/?probe=5ddcb0cf64) | Nov 15, 2023 |
| Intel         | DH67BL AAG10189-206         | [334569cac2](https://linux-hardware.org/?probe=334569cac2) | Nov 15, 2023 |
| MSI           | H77MA-G43                   | [f191f17f2a](https://linux-hardware.org/?probe=f191f17f2a) | Nov 14, 2023 |
| Gigabyte      | B550M DS3H                  | [882de5a591](https://linux-hardware.org/?probe=882de5a591) | Nov 13, 2023 |
| MSI           | H77MA-G43                   | [a814c93afe](https://linux-hardware.org/?probe=a814c93afe) | Nov 09, 2023 |
| HC Technol... | HCAR5000-MI                 | [ab41e88ca3](https://linux-hardware.org/?probe=ab41e88ca3) | Nov 07, 2023 |
| ASUSTek       | PRIME A320M-K               | [99b0c9edcf](https://linux-hardware.org/?probe=99b0c9edcf) | Nov 06, 2023 |
| ASUSTek       | H110M-A/M.2                 | [2cc662a279](https://linux-hardware.org/?probe=2cc662a279) | Nov 05, 2023 |
| Dell          | 0T7D40 A00                  | [2053de6443](https://linux-hardware.org/?probe=2053de6443) | Nov 05, 2023 |
| Dell          | 0T7D40 A00                  | [a81d5bbd02](https://linux-hardware.org/?probe=a81d5bbd02) | Nov 03, 2023 |
| HP            | 0B54h D                     | [4ec7776a76](https://linux-hardware.org/?probe=4ec7776a76) | Nov 02, 2023 |
| ASUSTek       | ROG STRIX B360-F GAMING     | [72a5b8f06a](https://linux-hardware.org/?probe=72a5b8f06a) | Nov 02, 2023 |
| Dell          | 0J3C2F A00                  | [a9ed160c1c](https://linux-hardware.org/?probe=a9ed160c1c) | Nov 01, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | [b5e0b9a020](https://linux-hardware.org/?probe=b5e0b9a020) | Oct 27, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | [38ed4f25af](https://linux-hardware.org/?probe=38ed4f25af) | Oct 27, 2023 |
| MACHINIST     | H81M-PRO S1 V2.0            | [b9ec438e43](https://linux-hardware.org/?probe=b9ec438e43) | Oct 27, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [3b82b142b1](https://linux-hardware.org/?probe=3b82b142b1) | Oct 26, 2023 |
| ASUSTek       | P5G41-M LX2/GB              | [ffc0782186](https://linux-hardware.org/?probe=ffc0782186) | Oct 23, 2023 |
| Gigabyte      | B560M DS3H                  | [2100dab18e](https://linux-hardware.org/?probe=2100dab18e) | Oct 23, 2023 |
| Acer          | G33T-AM                     | [7b42f4db1d](https://linux-hardware.org/?probe=7b42f4db1d) | Oct 23, 2023 |
| Acer          | G33T-AM                     | [70f67a6f11](https://linux-hardware.org/?probe=70f67a6f11) | Oct 22, 2023 |
| MACHINIST     | X79 Z9-D7 V1.2              | [7ad6760006](https://linux-hardware.org/?probe=7ad6760006) | Oct 19, 2023 |
| Dell          | 0GDG8Y A00                  | [78164f9bcc](https://linux-hardware.org/?probe=78164f9bcc) | Oct 18, 2023 |
| MACHINIST     | X79 Z9-D7 V1.2              | [bc7e7d2817](https://linux-hardware.org/?probe=bc7e7d2817) | Oct 17, 2023 |
| MSI           | Z270 GAMING PRO CARBON      | [47f6f3760d](https://linux-hardware.org/?probe=47f6f3760d) | Oct 17, 2023 |
| MSI           | Z270 GAMING PRO CARBON      | [23c3f61285](https://linux-hardware.org/?probe=23c3f61285) | Oct 14, 2023 |
| ASUSTek       | P8H61-MX R2.0               | [a654820b23](https://linux-hardware.org/?probe=a654820b23) | Oct 13, 2023 |
| ASUSTek       | P8H61-MX R2.0               | [b756b81d33](https://linux-hardware.org/?probe=b756b81d33) | Oct 12, 2023 |
| Dell          | 0GTK4K A02                  | [05d87a2b59](https://linux-hardware.org/?probe=05d87a2b59) | Oct 08, 2023 |
| Dell          | 0GTK4K A02                  | [7480d29d9f](https://linux-hardware.org/?probe=7480d29d9f) | Oct 07, 2023 |
| ASUSTek       | P5G41T-M LX                 | [21ec0f4129](https://linux-hardware.org/?probe=21ec0f4129) | Oct 06, 2023 |
| Gigabyte      | H110M-S2H-CF                | [3513d5bcf3](https://linux-hardware.org/?probe=3513d5bcf3) | Sep 28, 2023 |
| Gigabyte      | GA-MA790XT-UD4P             | [945e2bc260](https://linux-hardware.org/?probe=945e2bc260) | Sep 24, 2023 |
| HP            | 2ADC                        | [b4794f247b](https://linux-hardware.org/?probe=b4794f247b) | Sep 21, 2023 |
| HP            | 2ADC                        | [7e9eb06b31](https://linux-hardware.org/?probe=7e9eb06b31) | Sep 21, 2023 |
| ASUSTek       | PRIME X370-PRO              | [603ddfc4cf](https://linux-hardware.org/?probe=603ddfc4cf) | Sep 18, 2023 |
| ASUSTek       | VM42                        | [ca9a3b42d0](https://linux-hardware.org/?probe=ca9a3b42d0) | Sep 17, 2023 |
| ASUSTek       | M3A78-CM                    | [5a47ad5c25](https://linux-hardware.org/?probe=5a47ad5c25) | Sep 15, 2023 |
| ASUSTek       | M3A78-CM                    | [876175ae24](https://linux-hardware.org/?probe=876175ae24) | Sep 15, 2023 |
| HP            | 339A                        | [a9eaaaeeb0](https://linux-hardware.org/?probe=a9eaaaeeb0) | Sep 12, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | [b4c93a8e2e](https://linux-hardware.org/?probe=b4c93a8e2e) | Sep 12, 2023 |
| Lenovo        | NO DPK                      | [0a25a3d2af](https://linux-hardware.org/?probe=0a25a3d2af) | Sep 12, 2023 |
| HP            | 339A                        | [18bb44efa6](https://linux-hardware.org/?probe=18bb44efa6) | Sep 10, 2023 |
| Gigabyte      | 970A-DS3P                   | [ef1d9bfdab](https://linux-hardware.org/?probe=ef1d9bfdab) | Sep 08, 2023 |
| Gigabyte      | 970A-DS3P                   | [2ce7b78a76](https://linux-hardware.org/?probe=2ce7b78a76) | Sep 06, 2023 |
| Dell          | 0J3C2F A00                  | [9374424bbd](https://linux-hardware.org/?probe=9374424bbd) | Aug 30, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [2a2adfdc2e](https://linux-hardware.org/?probe=2a2adfdc2e) | Aug 30, 2023 |
| Unknown       | IPMSB-H61                   | [c104b6462e](https://linux-hardware.org/?probe=c104b6462e) | Aug 26, 2023 |
| ASRock        | X370 Pro4                   | [190a0f1eee](https://linux-hardware.org/?probe=190a0f1eee) | Aug 23, 2023 |
| HP            | 18E7                        | [0bd07157fb](https://linux-hardware.org/?probe=0bd07157fb) | Aug 20, 2023 |
| ASUSTek       | P8Z68-V PRO GEN3            | [d05585906d](https://linux-hardware.org/?probe=d05585906d) | Aug 18, 2023 |
| Dell          | 0KP561                      | [2b6a6b6139](https://linux-hardware.org/?probe=2b6a6b6139) | Aug 17, 2023 |
| Gigabyte      | B560M H                     | [663f9e62db](https://linux-hardware.org/?probe=663f9e62db) | Aug 08, 2023 |
| Acer          | Aspire TC-710 V:1.1         | [f6af1382fd](https://linux-hardware.org/?probe=f6af1382fd) | Aug 08, 2023 |
| Dell          | 0NKW6Y A02                  | [09ae57bb9a](https://linux-hardware.org/?probe=09ae57bb9a) | Aug 05, 2023 |
| Dell          | 0NKW6Y A02                  | [21460cac53](https://linux-hardware.org/?probe=21460cac53) | Aug 05, 2023 |
| Pegatron      | 2A94h                       | [9d5490fb82](https://linux-hardware.org/?probe=9d5490fb82) | Aug 04, 2023 |
| MSI           | A320M-A PRO MAX             | [36dda4bbfa](https://linux-hardware.org/?probe=36dda4bbfa) | Jul 28, 2023 |
| MSI           | A320M-A PRO MAX             | [10fa87c167](https://linux-hardware.org/?probe=10fa87c167) | Jul 28, 2023 |
| ASRock        | X570 Extreme4               | [5b1a74fc68](https://linux-hardware.org/?probe=5b1a74fc68) | Jul 27, 2023 |
| Acer          | Aspire TC-380               | [94f5f10ff2](https://linux-hardware.org/?probe=94f5f10ff2) | Jul 14, 2023 |
| Wortmann      | TERRA_PC                    | [60ece53188](https://linux-hardware.org/?probe=60ece53188) | Jul 13, 2023 |
| ASRock        | X370 Pro4                   | [4e8926a95b](https://linux-hardware.org/?probe=4e8926a95b) | Jul 11, 2023 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [784f886357](https://linux-hardware.org/?probe=784f886357) | Jul 10, 2023 |
| Apple         | Mac-F221BEC8                | [881754a433](https://linux-hardware.org/?probe=881754a433) | Jul 09, 2023 |
| Alienware     | 07HV66 A00                  | [41d4d9ae84](https://linux-hardware.org/?probe=41d4d9ae84) | Jul 05, 2023 |
| Alienware     | 07HV66 A00                  | [2712110727](https://linux-hardware.org/?probe=2712110727) | Jul 05, 2023 |
| HP            | 0B54h D                     | [c13f21ea22](https://linux-hardware.org/?probe=c13f21ea22) | Jun 29, 2023 |
| Gigabyte      | H81M-S2V                    | [38ae545c1c](https://linux-hardware.org/?probe=38ae545c1c) | Jun 23, 2023 |
| MSI           | B450M PRO-M2 V2             | [4f5e2f9201](https://linux-hardware.org/?probe=4f5e2f9201) | Jun 21, 2023 |
| Pegatron      | IPMIP-GS                    | [fb51893272](https://linux-hardware.org/?probe=fb51893272) | Jun 15, 2023 |
| ECS           | G41T-M                      | [2c148573fc](https://linux-hardware.org/?probe=2c148573fc) | Jun 11, 2023 |
| Acer          | Veriton X2631G V:1.0        | [99f3070065](https://linux-hardware.org/?probe=99f3070065) | Jun 11, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [08114e8a97](https://linux-hardware.org/?probe=08114e8a97) | Jun 10, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [93555cfd25](https://linux-hardware.org/?probe=93555cfd25) | Jun 10, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [2e6d82c14f](https://linux-hardware.org/?probe=2e6d82c14f) | Jun 10, 2023 |
| Gigabyte      | B450M GAMING                | [8ab2ec8df4](https://linux-hardware.org/?probe=8ab2ec8df4) | Jun 09, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | [ddefeff960](https://linux-hardware.org/?probe=ddefeff960) | Jun 08, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | [77fe6db865](https://linux-hardware.org/?probe=77fe6db865) | Jun 06, 2023 |
| Gigabyte      | GA-E6010N                   | [563074319d](https://linux-hardware.org/?probe=563074319d) | May 31, 2023 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [01076d8e8b](https://linux-hardware.org/?probe=01076d8e8b) | May 30, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [16b9dfbbe0](https://linux-hardware.org/?probe=16b9dfbbe0) | May 29, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [e29fb14e81](https://linux-hardware.org/?probe=e29fb14e81) | May 26, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [84d0d9807f](https://linux-hardware.org/?probe=84d0d9807f) | May 26, 2023 |
| ASUSTek       | P8H61-MX R2.0               | [3776285fc1](https://linux-hardware.org/?probe=3776285fc1) | May 16, 2023 |
| HP            | 1998                        | [b806151d9f](https://linux-hardware.org/?probe=b806151d9f) | May 12, 2023 |
| HP            | 225E                        | [06c72d2ecd](https://linux-hardware.org/?probe=06c72d2ecd) | May 10, 2023 |
| Intel         | JSL MRD                     | [76ff5c3bd7](https://linux-hardware.org/?probe=76ff5c3bd7) | May 05, 2023 |
| Dell          | 02N3WF A02                  | [3f10b3ca43](https://linux-hardware.org/?probe=3f10b3ca43) | May 04, 2023 |
| HP            | 1998                        | [6f816ac95a](https://linux-hardware.org/?probe=6f816ac95a) | Apr 29, 2023 |
| HP            | 8055                        | [a897208085](https://linux-hardware.org/?probe=a897208085) | Apr 26, 2023 |
| ASRock        | B660M-C                     | [849fc5d462](https://linux-hardware.org/?probe=849fc5d462) | Apr 25, 2023 |
| Gigabyte      | H410M H V3                  | [8fd18554d1](https://linux-hardware.org/?probe=8fd18554d1) | Apr 24, 2023 |
| MACHINIST     | E5-MR9A PRO V1.1            | [eebce73217](https://linux-hardware.org/?probe=eebce73217) | Apr 23, 2023 |
| ASUSTek       | PRIME Z390-A                | [50a18b5e94](https://linux-hardware.org/?probe=50a18b5e94) | Apr 19, 2023 |
| Foxconn       | A76GMV                      | [bafa62c759](https://linux-hardware.org/?probe=bafa62c759) | Apr 18, 2023 |
| Foxconn       | A76GMV                      | [f129cb2de1](https://linux-hardware.org/?probe=f129cb2de1) | Apr 18, 2023 |
| ASUSTek       | PRIME Z390-A                | [e311d21def](https://linux-hardware.org/?probe=e311d21def) | Apr 13, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | [8e05a5e529](https://linux-hardware.org/?probe=8e05a5e529) | Apr 13, 2023 |
| Gigabyte      | Z270-Gaming K3              | [0c03014734](https://linux-hardware.org/?probe=0c03014734) | Apr 12, 2023 |
| HP            | 0B54h D                     | [59e9cd0741](https://linux-hardware.org/?probe=59e9cd0741) | Apr 06, 2023 |
| MSI           | B450M PRO-M2 MAX            | [5a83c18a3e](https://linux-hardware.org/?probe=5a83c18a3e) | Apr 01, 2023 |
| MSI           | B450M PRO-M2 MAX            | [94f75ee798](https://linux-hardware.org/?probe=94f75ee798) | Apr 01, 2023 |
| Unknown       | Unknown                     | [fb22157f03](https://linux-hardware.org/?probe=fb22157f03) | Mar 28, 2023 |
| AZW           | U59                         | [7674bb8dc9](https://linux-hardware.org/?probe=7674bb8dc9) | Mar 27, 2023 |
| ASUSTek       | M4A785TD-V EVO              | [1674c37cf9](https://linux-hardware.org/?probe=1674c37cf9) | Mar 16, 2023 |
| HP            | 805A                        | [5401e12606](https://linux-hardware.org/?probe=5401e12606) | Mar 14, 2023 |
| HP            | 3033h                       | [ab5e388ea9](https://linux-hardware.org/?probe=ab5e388ea9) | Mar 14, 2023 |
| HP            | 3033h                       | [38ac77726b](https://linux-hardware.org/?probe=38ac77726b) | Mar 13, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [39d0e8595c](https://linux-hardware.org/?probe=39d0e8595c) | Mar 12, 2023 |
| Dell          | 0T7D40 A01                  | [c2174a1837](https://linux-hardware.org/?probe=c2174a1837) | Mar 12, 2023 |
| MSI           | B365M PRO-VH                | [023f42d6d1](https://linux-hardware.org/?probe=023f42d6d1) | Mar 12, 2023 |
| Acer          | Aspire TC-380               | [563bd52487](https://linux-hardware.org/?probe=563bd52487) | Mar 10, 2023 |
| Inventec      | Z CLASS A02                 | [c45e770987](https://linux-hardware.org/?probe=c45e770987) | Mar 06, 2023 |
| ASUSTek       | BT6130                      | [dabd3e0232](https://linux-hardware.org/?probe=dabd3e0232) | Mar 01, 2023 |
| Unknown       | Unknown                     | [1c5f8fef49](https://linux-hardware.org/?probe=1c5f8fef49) | Feb 28, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [216ad20179](https://linux-hardware.org/?probe=216ad20179) | Feb 28, 2023 |
| Acer          | Predator G3620              | [72f3382b60](https://linux-hardware.org/?probe=72f3382b60) | Feb 27, 2023 |
| Gigabyte      | Z77X-UD5H                   | [2071bc50ce](https://linux-hardware.org/?probe=2071bc50ce) | Feb 27, 2023 |
| Gigabyte      | Z77X-UD5H                   | [472c035387](https://linux-hardware.org/?probe=472c035387) | Feb 27, 2023 |
| Dell          | 0J584C                      | [5f16a97f99](https://linux-hardware.org/?probe=5f16a97f99) | Feb 27, 2023 |
| Dell          | 07PR60 A01                  | [c071b7ef1c](https://linux-hardware.org/?probe=c071b7ef1c) | Feb 27, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | [ce9dda227f](https://linux-hardware.org/?probe=ce9dda227f) | Feb 25, 2023 |
| Gigabyte      | Z77MX-D3H                   | [bfd1042a82](https://linux-hardware.org/?probe=bfd1042a82) | Feb 25, 2023 |
| Dell          | 0J584C                      | [f0c7703e3c](https://linux-hardware.org/?probe=f0c7703e3c) | Feb 23, 2023 |
| Dell          | 0J584C                      | [003da08b72](https://linux-hardware.org/?probe=003da08b72) | Feb 22, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | [c1936488f5](https://linux-hardware.org/?probe=c1936488f5) | Feb 20, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [13a132516b](https://linux-hardware.org/?probe=13a132516b) | Feb 18, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | [76ab936a75](https://linux-hardware.org/?probe=76ab936a75) | Feb 16, 2023 |
| ASUSTek       | H110M-A/M.2                 | [68f0415788](https://linux-hardware.org/?probe=68f0415788) | Feb 16, 2023 |
| ASUSTek       | H110M-A/M.2                 | [2560ba7644](https://linux-hardware.org/?probe=2560ba7644) | Feb 16, 2023 |
| Foxconn       | 2ADA                        | [e0f89bbca1](https://linux-hardware.org/?probe=e0f89bbca1) | Feb 16, 2023 |
| HP            | 805D                        | [217784712c](https://linux-hardware.org/?probe=217784712c) | Feb 14, 2023 |
| MSI           | B85-G43 GAMING              | [b2b66e40e1](https://linux-hardware.org/?probe=b2b66e40e1) | Feb 14, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | [f0899499e5](https://linux-hardware.org/?probe=f0899499e5) | Feb 13, 2023 |
| ASUSTek       | H110M-A/M.2                 | [76711a4e32](https://linux-hardware.org/?probe=76711a4e32) | Feb 10, 2023 |
| ASUSTek       | M4A785TD-V EVO              | [aaa509fed7](https://linux-hardware.org/?probe=aaa509fed7) | Feb 09, 2023 |
| ASUSTek       | H110M-A/M.2                 | [73b3c1c661](https://linux-hardware.org/?probe=73b3c1c661) | Feb 06, 2023 |
| Gigabyte      | F2A88XM-DS2                 | [d9313ff1c1](https://linux-hardware.org/?probe=d9313ff1c1) | Feb 05, 2023 |
| ASUSTek       | P7P55 LX                    | [3786e7a211](https://linux-hardware.org/?probe=3786e7a211) | Feb 04, 2023 |
| Unknown       | IPMSB-H61                   | [7e13c996bd](https://linux-hardware.org/?probe=7e13c996bd) | Feb 02, 2023 |
| BESSTAR Te... | UM350                       | [ee1ba0e588](https://linux-hardware.org/?probe=ee1ba0e588) | Jan 30, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [c2a4529e33](https://linux-hardware.org/?probe=c2a4529e33) | Jan 30, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [e5f6f546d4](https://linux-hardware.org/?probe=e5f6f546d4) | Jan 29, 2023 |
| EVGA          | E689 $                      | [9d4b1aeaa9](https://linux-hardware.org/?probe=9d4b1aeaa9) | Jan 29, 2023 |
| EVGA          | E689 $                      | [be99ae882b](https://linux-hardware.org/?probe=be99ae882b) | Jan 28, 2023 |
| Gigabyte      | GA-990FXA-UD3               | [6e5884ec0c](https://linux-hardware.org/?probe=6e5884ec0c) | Jan 26, 2023 |
| ASUSTek       | Z87-A                       | [755bed02ff](https://linux-hardware.org/?probe=755bed02ff) | Jan 25, 2023 |
| ASUSTek       | Z87-A                       | [6ccfafe0d6](https://linux-hardware.org/?probe=6ccfafe0d6) | Jan 24, 2023 |
| Dell          | 0G261D A00                  | [ac4e94394e](https://linux-hardware.org/?probe=ac4e94394e) | Jan 24, 2023 |
| Unknown       | G41T-M7                     | [026810c423](https://linux-hardware.org/?probe=026810c423) | Jan 22, 2023 |
| Gigabyte      | Z77MX-D3H                   | [2142d5e771](https://linux-hardware.org/?probe=2142d5e771) | Jan 22, 2023 |
| Gigabyte      | Z77MX-D3H                   | [80d8c352b9](https://linux-hardware.org/?probe=80d8c352b9) | Jan 22, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [b8df2d6479](https://linux-hardware.org/?probe=b8df2d6479) | Jan 11, 2023 |
| Intel         | JSL MRD                     | [d1b9dbaae0](https://linux-hardware.org/?probe=d1b9dbaae0) | Jan 11, 2023 |
| HP            | 8643 SMVB                   | [5187413460](https://linux-hardware.org/?probe=5187413460) | Jan 07, 2023 |
| Acer          | Veriton M2631G V:1.0        | [ebbcc0dda8](https://linux-hardware.org/?probe=ebbcc0dda8) | Jan 07, 2023 |
| Unknown       | HX90                        | [af144f98b6](https://linux-hardware.org/?probe=af144f98b6) | Jan 05, 2023 |
| ASRock        | H110 Pro BTC+               | [a7ccef79ad](https://linux-hardware.org/?probe=a7ccef79ad) | Dec 30, 2022 |
| Gigabyte      | H61M-S2V-B3                 | [b3970a8e5a](https://linux-hardware.org/?probe=b3970a8e5a) | Dec 29, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [bc58be5546](https://linux-hardware.org/?probe=bc58be5546) | Dec 27, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [f9bde62142](https://linux-hardware.org/?probe=f9bde62142) | Dec 27, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [c545cf1f08](https://linux-hardware.org/?probe=c545cf1f08) | Dec 25, 2022 |
| Lenovo        | ThinkCentre M71e 3129C3G    | [cb9f99f1cf](https://linux-hardware.org/?probe=cb9f99f1cf) | Dec 23, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [2fa8510855](https://linux-hardware.org/?probe=2fa8510855) | Dec 19, 2022 |
| Foxconn       | 2ABF                        | [10e579b77e](https://linux-hardware.org/?probe=10e579b77e) | Dec 18, 2022 |
| Dell          | 08WKV3 A00                  | [f58a0ffbc3](https://linux-hardware.org/?probe=f58a0ffbc3) | Dec 13, 2022 |
| MSI           | B350 TOMAHAWK               | [0ce6563922](https://linux-hardware.org/?probe=0ce6563922) | Dec 11, 2022 |
| ASUSTek       | Z170-P                      | [5180b907e3](https://linux-hardware.org/?probe=5180b907e3) | Dec 10, 2022 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | [5ca8db90bb](https://linux-hardware.org/?probe=5ca8db90bb) | Dec 10, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [906e4966a6](https://linux-hardware.org/?probe=906e4966a6) | Dec 07, 2022 |
| ASRock        | H55M-LE                     | [9d2066a479](https://linux-hardware.org/?probe=9d2066a479) | Dec 03, 2022 |
| Fujitsu       | D3602-A1 S26361-D3602-A1    | [6f57ed994c](https://linux-hardware.org/?probe=6f57ed994c) | Dec 03, 2022 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | [62b19626ce](https://linux-hardware.org/?probe=62b19626ce) | Dec 03, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [19d93a0122](https://linux-hardware.org/?probe=19d93a0122) | Dec 03, 2022 |
| Lenovo        | ThinkCentre M70e 0809D1Y    | [0cd85fa9f3](https://linux-hardware.org/?probe=0cd85fa9f3) | Nov 30, 2022 |
| Dell          | 0TP406                      | [3eceea61d2](https://linux-hardware.org/?probe=3eceea61d2) | Nov 30, 2022 |
| Dell          | 0TP406                      | [d22689331c](https://linux-hardware.org/?probe=d22689331c) | Nov 30, 2022 |
| MSI           | IONA                        | [255f7f8dc4](https://linux-hardware.org/?probe=255f7f8dc4) | Nov 28, 2022 |
| MSI           | IONA                        | [94841f2b61](https://linux-hardware.org/?probe=94841f2b61) | Nov 28, 2022 |
| LattePanda    | Alpha                       | [be819160d5](https://linux-hardware.org/?probe=be819160d5) | Nov 26, 2022 |
| LattePanda    | Alpha                       | [b3c831db4d](https://linux-hardware.org/?probe=b3c831db4d) | Nov 26, 2022 |
| MSI           | IONA                        | [280083cfa1](https://linux-hardware.org/?probe=280083cfa1) | Nov 22, 2022 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | [4f230635de](https://linux-hardware.org/?probe=4f230635de) | Nov 19, 2022 |
| Dell          | 0RW199                      | [df40ccbcdb](https://linux-hardware.org/?probe=df40ccbcdb) | Nov 15, 2022 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [4629fb5e08](https://linux-hardware.org/?probe=4629fb5e08) | Nov 13, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | [ddca3f4758](https://linux-hardware.org/?probe=ddca3f4758) | Nov 06, 2022 |
| Gigabyte      | H310M S2H                   | [521297d21c](https://linux-hardware.org/?probe=521297d21c) | Nov 03, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [919fad100f](https://linux-hardware.org/?probe=919fad100f) | Oct 31, 2022 |
| ASUSTek       | PRIME X570-PRO              | [6d4b1d0bb3](https://linux-hardware.org/?probe=6d4b1d0bb3) | Oct 25, 2022 |
| HP            | 805D                        | [916b6f09ac](https://linux-hardware.org/?probe=916b6f09ac) | Oct 23, 2022 |
| MSI           | Z370 GAMING PLUS            | [ce623178a2](https://linux-hardware.org/?probe=ce623178a2) | Oct 16, 2022 |
| Dell          | 0D28YY A00                  | [435831fd5b](https://linux-hardware.org/?probe=435831fd5b) | Oct 15, 2022 |
| Kraftway      | KWQ67                       | [8346fc15e3](https://linux-hardware.org/?probe=8346fc15e3) | Oct 13, 2022 |
| Kraftway      | KWQ67                       | [d57d34be64](https://linux-hardware.org/?probe=d57d34be64) | Oct 13, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [88772ad191](https://linux-hardware.org/?probe=88772ad191) | Oct 11, 2022 |
| ASRock        | X370 Taichi                 | [d86c708401](https://linux-hardware.org/?probe=d86c708401) | Sep 30, 2022 |
| Gigabyte      | G41MT-S2                    | [c0b1c8ad8f](https://linux-hardware.org/?probe=c0b1c8ad8f) | Sep 27, 2022 |
| Packard Be... | IMEDIA S1300                | [13b1f0e28e](https://linux-hardware.org/?probe=13b1f0e28e) | Sep 24, 2022 |
| Packard Be... | IMEDIA S1300                | [fae2bea6f3](https://linux-hardware.org/?probe=fae2bea6f3) | Sep 19, 2022 |
| Apple         | Mac-F221BEC8                | [b5f851bd15](https://linux-hardware.org/?probe=b5f851bd15) | Sep 12, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | [335a8a059b](https://linux-hardware.org/?probe=335a8a059b) | Sep 12, 2022 |
| Gigabyte      | F2A88XM-D3HP                | [3d269171e7](https://linux-hardware.org/?probe=3d269171e7) | Sep 11, 2022 |
| ASUSTek       | P8H77-V LE                  | [ae533c2bdf](https://linux-hardware.org/?probe=ae533c2bdf) | Sep 07, 2022 |
| Acer          | Aspire X1420G               | [e48b081560](https://linux-hardware.org/?probe=e48b081560) | Sep 04, 2022 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [3a8803f198](https://linux-hardware.org/?probe=3a8803f198) | Sep 01, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | [413bd5a721](https://linux-hardware.org/?probe=413bd5a721) | Aug 29, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [9274f5e876](https://linux-hardware.org/?probe=9274f5e876) | Aug 29, 2022 |
| ASUSTek       | M2N68-AM SE2                | [0f71a52e11](https://linux-hardware.org/?probe=0f71a52e11) | Aug 28, 2022 |
| Gigabyte      | H61M-S1                     | [6bf1dafdbc](https://linux-hardware.org/?probe=6bf1dafdbc) | Aug 27, 2022 |
| Apple         | Mac-F221BEC8                | [9ffe8ee96e](https://linux-hardware.org/?probe=9ffe8ee96e) | Aug 24, 2022 |
| Apple         | Mac-F221BEC8                | [4709584652](https://linux-hardware.org/?probe=4709584652) | Aug 24, 2022 |
| MSI           | MEG Z490I UNIFY             | [34d2d4f66e](https://linux-hardware.org/?probe=34d2d4f66e) | Aug 24, 2022 |
| Foxconn       | 2ABF                        | [6d7ce1962d](https://linux-hardware.org/?probe=6d7ce1962d) | Aug 24, 2022 |
| ASRock        | N68-VGS3 FX                 | [1d2367ccf7](https://linux-hardware.org/?probe=1d2367ccf7) | Aug 23, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [595bf9c8a7](https://linux-hardware.org/?probe=595bf9c8a7) | Aug 23, 2022 |
| ASUSTek       | P7H55-M LX                  | [b545a0cf4f](https://linux-hardware.org/?probe=b545a0cf4f) | Aug 19, 2022 |
| Gigabyte      | H81M-DS2                    | [e0abb12052](https://linux-hardware.org/?probe=e0abb12052) | Aug 16, 2022 |
| HP            | 2AF7                        | [ca8820daa4](https://linux-hardware.org/?probe=ca8820daa4) | Aug 16, 2022 |
| ASUSTek       | P5B                         | [1c5cafd185](https://linux-hardware.org/?probe=1c5cafd185) | Aug 15, 2022 |
| Gigabyte      | H81M-DS2                    | [5ae2bc3c12](https://linux-hardware.org/?probe=5ae2bc3c12) | Aug 14, 2022 |
| Acer          | Aspire X1420G               | [7be7ab2e7e](https://linux-hardware.org/?probe=7be7ab2e7e) | Jul 31, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [e99805635f](https://linux-hardware.org/?probe=e99805635f) | Jul 29, 2022 |
| MSI           | B450M PRO-M2 MAX            | [ab8af10726](https://linux-hardware.org/?probe=ab8af10726) | Jul 28, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [d0a69fba02](https://linux-hardware.org/?probe=d0a69fba02) | Jul 23, 2022 |
| Dell          | 0GM819                      | [373772e538](https://linux-hardware.org/?probe=373772e538) | Jul 21, 2022 |
| Dell          | 00V62H A01                  | [ae809bb317](https://linux-hardware.org/?probe=ae809bb317) | Jul 19, 2022 |
| ASUSTek       | ROG STRIX B360-H GAMING     | [4cc1f4384c](https://linux-hardware.org/?probe=4cc1f4384c) | Jul 12, 2022 |
| Acer          | Aspire X1420G               | [0b7a9cbc2a](https://linux-hardware.org/?probe=0b7a9cbc2a) | Jul 12, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | [3db9c636d0](https://linux-hardware.org/?probe=3db9c636d0) | Jul 09, 2022 |
| MSI           | B450M PRO-VDH MAX           | [b8c450d5fa](https://linux-hardware.org/?probe=b8c450d5fa) | Jul 08, 2022 |
| Intel         | X79Turbo V1.x               | [e4b17550d0](https://linux-hardware.org/?probe=e4b17550d0) | Jul 06, 2022 |
| Gigabyte      | Z87X-OC-CF                  | [654459e245](https://linux-hardware.org/?probe=654459e245) | Jul 03, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | [80a981f992](https://linux-hardware.org/?probe=80a981f992) | Jul 01, 2022 |
| Gigabyte      | Z690 AORUS MASTER           | [a8073316f6](https://linux-hardware.org/?probe=a8073316f6) | Jun 26, 2022 |
| ASRock        | Z490 Pro4                   | [f84c8a756c](https://linux-hardware.org/?probe=f84c8a756c) | Jun 25, 2022 |
| MSI           | B85I                        | [886f971d22](https://linux-hardware.org/?probe=886f971d22) | Jun 25, 2022 |
| HP            | 339A                        | [822467af7f](https://linux-hardware.org/?probe=822467af7f) | Jun 25, 2022 |
| T-bao         | MINI PC                     | [6b18c66487](https://linux-hardware.org/?probe=6b18c66487) | Jun 18, 2022 |
| Pegatron      | 2ACD                        | [8c8275099b](https://linux-hardware.org/?probe=8c8275099b) | Jun 16, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [5b8ae292bf](https://linux-hardware.org/?probe=5b8ae292bf) | Jun 14, 2022 |
| ASUSTek       | SABERTOOTH X58              | [4cc4a7c1b3](https://linux-hardware.org/?probe=4cc4a7c1b3) | Jun 11, 2022 |
| HP            | 2B43                        | [6f36772b0c](https://linux-hardware.org/?probe=6f36772b0c) | Jun 10, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [9756188040](https://linux-hardware.org/?probe=9756188040) | Jun 07, 2022 |
| MSI           | MPG X570S CARBON MAX WIF... | [0d57c069a8](https://linux-hardware.org/?probe=0d57c069a8) | Jun 05, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN 2625... | [16f3fff6ad](https://linux-hardware.org/?probe=16f3fff6ad) | Jun 05, 2022 |
| Dell          | 0T7D40 A01                  | [812b41fe55](https://linux-hardware.org/?probe=812b41fe55) | Jun 04, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN 2625... | [b3d970d061](https://linux-hardware.org/?probe=b3d970d061) | Jun 04, 2022 |
| MSI           | B85I                        | [5f29683d93](https://linux-hardware.org/?probe=5f29683d93) | Jun 03, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | [9f4aa60f60](https://linux-hardware.org/?probe=9f4aa60f60) | Jun 02, 2022 |
| ASUSTek       | P5B                         | [12554af571](https://linux-hardware.org/?probe=12554af571) | May 31, 2022 |
| MSI           | MPG X570S CARBON MAX WIF... | [a4f2a9b24b](https://linux-hardware.org/?probe=a4f2a9b24b) | May 27, 2022 |
| MSI           | MPG X570S CARBON MAX WIF... | [3143793e8f](https://linux-hardware.org/?probe=3143793e8f) | May 27, 2022 |
| ASUSTek       | P5KPL-VM/S                  | [66223d6ef0](https://linux-hardware.org/?probe=66223d6ef0) | May 25, 2022 |
| ASUSTek       | P5KPL-VM/S                  | [d44e9d6290](https://linux-hardware.org/?probe=d44e9d6290) | May 25, 2022 |
| ASUSTek       | P8H61                       | [5514e95c95](https://linux-hardware.org/?probe=5514e95c95) | May 24, 2022 |
| ASUSTek       | P8H61                       | [873dd31f8e](https://linux-hardware.org/?probe=873dd31f8e) | May 23, 2022 |
| MSI           | H97M-P35                    | [2b5866b09d](https://linux-hardware.org/?probe=2b5866b09d) | May 23, 2022 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | [2e27b6fac9](https://linux-hardware.org/?probe=2e27b6fac9) | May 23, 2022 |
| Biostar       | GF8200C M2+                 | [b80588cbea](https://linux-hardware.org/?probe=b80588cbea) | May 21, 2022 |
| ASUSTek       | P8H61-M LE/USB3             | [6f6a104d35](https://linux-hardware.org/?probe=6f6a104d35) | May 21, 2022 |
| MSI           | B85I                        | [c822196290](https://linux-hardware.org/?probe=c822196290) | May 18, 2022 |
| MSI           | MEG X570 UNIFY              | [4d00452dcb](https://linux-hardware.org/?probe=4d00452dcb) | May 15, 2022 |
| ASUSTek       | SABERTOOTH X58              | [c276639676](https://linux-hardware.org/?probe=c276639676) | May 08, 2022 |
| ASUSTek       | H81M-K                      | [753c7be679](https://linux-hardware.org/?probe=753c7be679) | May 05, 2022 |
| ASRock        | X570 Extreme4               | [98e5f20999](https://linux-hardware.org/?probe=98e5f20999) | May 04, 2022 |
| Gigabyte      | GA-880GMA-UD2H              | [09d9f58ee7](https://linux-hardware.org/?probe=09d9f58ee7) | May 02, 2022 |
| HP            | 0B48h                       | [4c6e5824f2](https://linux-hardware.org/?probe=4c6e5824f2) | Apr 30, 2022 |
| ASUSTek       | P8Z77-V                     | [b3506ef75d](https://linux-hardware.org/?probe=b3506ef75d) | Apr 29, 2022 |
| Dell          | 0J3C2F A00                  | [464c70eb8d](https://linux-hardware.org/?probe=464c70eb8d) | Apr 27, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [1f10d820f8](https://linux-hardware.org/?probe=1f10d820f8) | Apr 27, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [dfadead480](https://linux-hardware.org/?probe=dfadead480) | Apr 27, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [dbaaf867f6](https://linux-hardware.org/?probe=dbaaf867f6) | Apr 25, 2022 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [1b0a41c232](https://linux-hardware.org/?probe=1b0a41c232) | Apr 25, 2022 |
| AZW           | GTi                         | [e2d4a0da2e](https://linux-hardware.org/?probe=e2d4a0da2e) | Apr 23, 2022 |
| AZW           | GTi                         | [cde74551bf](https://linux-hardware.org/?probe=cde74551bf) | Apr 23, 2022 |
| ECS           | H61H2-MV                    | [939f87564f](https://linux-hardware.org/?probe=939f87564f) | Apr 21, 2022 |
| MSI           | X99A SLI PLUS               | [0b935aadb3](https://linux-hardware.org/?probe=0b935aadb3) | Apr 19, 2022 |
| Inventec      | D CLASS A02                 | [d00d37285b](https://linux-hardware.org/?probe=d00d37285b) | Apr 19, 2022 |
| ASRock        | Z490 Pro4                   | [67071d11a1](https://linux-hardware.org/?probe=67071d11a1) | Apr 18, 2022 |
| Dell          | 0KV62T A01                  | [0c6e50ed20](https://linux-hardware.org/?probe=0c6e50ed20) | Apr 17, 2022 |
| Dell          | 0KV62T A01                  | [7bed7782c4](https://linux-hardware.org/?probe=7bed7782c4) | Apr 17, 2022 |
| MSI           | B450M PRO-VDH MAX           | [e28ee0bd42](https://linux-hardware.org/?probe=e28ee0bd42) | Apr 16, 2022 |
| HP            | 1494                        | [6ad3ca1745](https://linux-hardware.org/?probe=6ad3ca1745) | Apr 16, 2022 |
| Gigabyte      | H61M-D2H-USB3               | [016243a675](https://linux-hardware.org/?probe=016243a675) | Apr 15, 2022 |
| Fujitsu       | D3531-A1 S26361-D3531-A1    | [46dd533a5e](https://linux-hardware.org/?probe=46dd533a5e) | Apr 14, 2022 |
| ASUSTek       | B85M-G                      | [c6dd82e724](https://linux-hardware.org/?probe=c6dd82e724) | Apr 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [dff6de5032](https://linux-hardware.org/?probe=dff6de5032) | Apr 14, 2022 |
| ASUSTek       | B85M-G                      | [e525a26ca8](https://linux-hardware.org/?probe=e525a26ca8) | Apr 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [6a2c5f12fd](https://linux-hardware.org/?probe=6a2c5f12fd) | Apr 13, 2022 |
| Dell          | 0K240Y A01                  | [76d4fbf0a6](https://linux-hardware.org/?probe=76d4fbf0a6) | Apr 13, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | [3440d2dd8c](https://linux-hardware.org/?probe=3440d2dd8c) | Apr 12, 2022 |
| Lenovo        | 3178 SDK0J40700 WIN 3258... | [637023ab6d](https://linux-hardware.org/?probe=637023ab6d) | Apr 11, 2022 |
| ASUSTek       | PRIME Z390-A                | [21767e12e4](https://linux-hardware.org/?probe=21767e12e4) | Apr 11, 2022 |
| Pegatron      | IPMH61P1                    | [1adcf74c4f](https://linux-hardware.org/?probe=1adcf74c4f) | Apr 10, 2022 |
| ASUSTek       | H110I-PLUS                  | [e367ac99ce](https://linux-hardware.org/?probe=e367ac99ce) | Apr 10, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [1c357065cb](https://linux-hardware.org/?probe=1c357065cb) | Apr 07, 2022 |
| ASRock        | C226 WS                     | [7c11c1ec43](https://linux-hardware.org/?probe=7c11c1ec43) | Apr 07, 2022 |
| ASUSTek       | STRIKER II FORMULA          | [5dfea21930](https://linux-hardware.org/?probe=5dfea21930) | Apr 07, 2022 |
| ASUSTek       | STRIKER II FORMULA          | [040990b3fc](https://linux-hardware.org/?probe=040990b3fc) | Apr 07, 2022 |
| Gigabyte      | B450M DS3H-CF               | [0bc837ffef](https://linux-hardware.org/?probe=0bc837ffef) | Apr 06, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [7419ad6a76](https://linux-hardware.org/?probe=7419ad6a76) | Apr 02, 2022 |
| Lenovo        | ThinkCentre M58 6258D3G     | [b67f1750b8](https://linux-hardware.org/?probe=b67f1750b8) | Mar 31, 2022 |
| Lenovo        | ThinkCentre M58 6258D3G     | [1cd22c83f1](https://linux-hardware.org/?probe=1cd22c83f1) | Mar 31, 2022 |
| MSI           | H97 GAMING 3                | [97f38615e3](https://linux-hardware.org/?probe=97f38615e3) | Mar 31, 2022 |
| MSI           | MEG X570 ACE                | [55572b8a7e](https://linux-hardware.org/?probe=55572b8a7e) | Mar 31, 2022 |
| HP            | 18E7                        | [ead4fcc358](https://linux-hardware.org/?probe=ead4fcc358) | Mar 29, 2022 |
| ASUSTek       | Rampage IV GENE             | [c067a4d0e7](https://linux-hardware.org/?probe=c067a4d0e7) | Mar 29, 2022 |
| Dell          | 0C522T A00                  | [33ae998152](https://linux-hardware.org/?probe=33ae998152) | Mar 26, 2022 |
| Dell          | 0C522T A00                  | [90242bb090](https://linux-hardware.org/?probe=90242bb090) | Mar 26, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [7577679057](https://linux-hardware.org/?probe=7577679057) | Mar 25, 2022 |
| Gigabyte      | A320M-S2H-CF                | [a237859a86](https://linux-hardware.org/?probe=a237859a86) | Mar 24, 2022 |
| Intel         | X79Turbo V1.x               | [18b126a753](https://linux-hardware.org/?probe=18b126a753) | Mar 24, 2022 |
| AMI           | Cherry Trail CR             | [bbea34ce64](https://linux-hardware.org/?probe=bbea34ce64) | Mar 22, 2022 |
| AMI           | Cherry Trail CR             | [bc5a34ef7e](https://linux-hardware.org/?probe=bc5a34ef7e) | Mar 20, 2022 |
| ASUSTek       | Rampage IV GENE             | [7f5053b061](https://linux-hardware.org/?probe=7f5053b061) | Mar 16, 2022 |
| ASUSTek       | Rampage IV GENE             | [7ff55a3ca6](https://linux-hardware.org/?probe=7ff55a3ca6) | Mar 16, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [eda8848760](https://linux-hardware.org/?probe=eda8848760) | Mar 15, 2022 |
| AOpen         | D1009 A1A4                  | [a7375d4581](https://linux-hardware.org/?probe=a7375d4581) | Mar 13, 2022 |
| MSI           | B85I                        | [d134c8451b](https://linux-hardware.org/?probe=d134c8451b) | Mar 12, 2022 |
| ASRock        | B450M Pro4                  | [12459fc7ea](https://linux-hardware.org/?probe=12459fc7ea) | Mar 11, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [a64818ccea](https://linux-hardware.org/?probe=a64818ccea) | Mar 10, 2022 |
| Biostar       | N68S3B                      | [aa1e6a4c82](https://linux-hardware.org/?probe=aa1e6a4c82) | Mar 10, 2022 |
| Dell          | 0HMX8D A01                  | [cfff92df80](https://linux-hardware.org/?probe=cfff92df80) | Mar 09, 2022 |
| ASUSTek       | M11AD                       | [8bb5baaa5a](https://linux-hardware.org/?probe=8bb5baaa5a) | Mar 09, 2022 |
| Biostar       | H61MLV2                     | [d5c330bad8](https://linux-hardware.org/?probe=d5c330bad8) | Mar 08, 2022 |
| HP            | 2ADC                        | [ed0714a64a](https://linux-hardware.org/?probe=ed0714a64a) | Mar 07, 2022 |
| MSI           | B85I                        | [39926596b7](https://linux-hardware.org/?probe=39926596b7) | Mar 07, 2022 |
| Dell          | 0PU052                      | [766b0e4665](https://linux-hardware.org/?probe=766b0e4665) | Mar 06, 2022 |
| Dell          | 0PU052                      | [a8e19bd112](https://linux-hardware.org/?probe=a8e19bd112) | Mar 06, 2022 |
| HP            | 1589                        | [88876808e9](https://linux-hardware.org/?probe=88876808e9) | Mar 05, 2022 |
| HP            | 802E                        | [14c73a40e0](https://linux-hardware.org/?probe=14c73a40e0) | Mar 05, 2022 |
| ASRock        | FM2A58M-DG3+                | [0b7875b1b5](https://linux-hardware.org/?probe=0b7875b1b5) | Mar 05, 2022 |
| ASUSTek       | M4N72-E                     | [c3fe570b4d](https://linux-hardware.org/?probe=c3fe570b4d) | Feb 28, 2022 |
| ASUSTek       | H81-PLUS                    | [e8956dc4ec](https://linux-hardware.org/?probe=e8956dc4ec) | Feb 27, 2022 |
| ASUSTek       | H81-PLUS                    | [9c68dfb511](https://linux-hardware.org/?probe=9c68dfb511) | Feb 26, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [a6d5cc0368](https://linux-hardware.org/?probe=a6d5cc0368) | Feb 26, 2022 |
| Gigabyte      | Z390 UD                     | [7ea66813f3](https://linux-hardware.org/?probe=7ea66813f3) | Feb 23, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [73b31ddab0](https://linux-hardware.org/?probe=73b31ddab0) | Feb 20, 2022 |
| Intel         | DH61BE AAG14062-210         | [00566bb73f](https://linux-hardware.org/?probe=00566bb73f) | Feb 19, 2022 |
| ASUSTek       | M11AD                       | [035887c4ab](https://linux-hardware.org/?probe=035887c4ab) | Feb 18, 2022 |
| ASUSTek       | P5B                         | [fa4c095fd7](https://linux-hardware.org/?probe=fa4c095fd7) | Feb 17, 2022 |
| Intel         | H61                         | [a70c59ad0e](https://linux-hardware.org/?probe=a70c59ad0e) | Feb 17, 2022 |
| ASUSTek       | PRIME Z590-A                | [6beda6e2da](https://linux-hardware.org/?probe=6beda6e2da) | Feb 16, 2022 |
| Biostar       | A68MD PRO                   | [da42cc4da7](https://linux-hardware.org/?probe=da42cc4da7) | Feb 16, 2022 |
| ASUSTek       | PRIME B250-PRO              | [be377c733e](https://linux-hardware.org/?probe=be377c733e) | Feb 14, 2022 |
| ASUSTek       | PRIME Z590-A                | [825734953d](https://linux-hardware.org/?probe=825734953d) | Feb 13, 2022 |
| MSI           | B85I                        | [898dced271](https://linux-hardware.org/?probe=898dced271) | Feb 13, 2022 |
| Gigabyte      | F2A68HM-H                   | [a2a41e039c](https://linux-hardware.org/?probe=a2a41e039c) | Feb 13, 2022 |
| Gigabyte      | F2A68HM-H                   | [2f3941c9cb](https://linux-hardware.org/?probe=2f3941c9cb) | Feb 12, 2022 |
| ASUSTek       | PRIME A320M-K               | [5f4de1e2b0](https://linux-hardware.org/?probe=5f4de1e2b0) | Feb 12, 2022 |
| ASUSTek       | PRIME B360M-K               | [698e174402](https://linux-hardware.org/?probe=698e174402) | Feb 09, 2022 |
| ASUSTek       | H110M-C                     | [82f3d6edf9](https://linux-hardware.org/?probe=82f3d6edf9) | Feb 09, 2022 |
| MSI           | B450I GAMING PLUS AC        | [a2af859752](https://linux-hardware.org/?probe=a2af859752) | Feb 09, 2022 |
| ECS           | H55H-M                      | [856a42d74b](https://linux-hardware.org/?probe=856a42d74b) | Feb 07, 2022 |
| Lenovo        | NO DPK                      | [4bb7cedbd8](https://linux-hardware.org/?probe=4bb7cedbd8) | Feb 06, 2022 |
| HP            | 802E                        | [31e2fe159c](https://linux-hardware.org/?probe=31e2fe159c) | Feb 05, 2022 |
| ASUSTek       | H110M-C                     | [6ba127c715](https://linux-hardware.org/?probe=6ba127c715) | Feb 04, 2022 |
| ASUSTek       | P5B                         | [9b661f64dd](https://linux-hardware.org/?probe=9b661f64dd) | Feb 04, 2022 |
| Foxconn       | NETBOX nT-435/535 Ver       | [c7d50db62b](https://linux-hardware.org/?probe=c7d50db62b) | Feb 03, 2022 |
| Foxconn       | NETBOX nT-435/535 Ver       | [2ee2be7ccf](https://linux-hardware.org/?probe=2ee2be7ccf) | Feb 03, 2022 |
| HP            | ProLiant ML110 G7           | [2e1dcafe6c](https://linux-hardware.org/?probe=2e1dcafe6c) | Feb 03, 2022 |
| HP            | 339A                        | [cf9dca84ff](https://linux-hardware.org/?probe=cf9dca84ff) | Feb 02, 2022 |
| Unknown       | Unknown                     | [629972c689](https://linux-hardware.org/?probe=629972c689) | Feb 01, 2022 |
| HP            | 805D                        | [19295e5827](https://linux-hardware.org/?probe=19295e5827) | Feb 01, 2022 |
| ASUSTek       | H110I-PLUS                  | [ebeaf681e3](https://linux-hardware.org/?probe=ebeaf681e3) | Feb 01, 2022 |
| Gigabyte      | B75M-D3H                    | [18717f0712](https://linux-hardware.org/?probe=18717f0712) | Feb 01, 2022 |
| MSI           | Z270 KRAIT GAMING           | [17ccbf9c76](https://linux-hardware.org/?probe=17ccbf9c76) | Jan 28, 2022 |
| Gigabyte      | H61M-DS2                    | [e800b95c58](https://linux-hardware.org/?probe=e800b95c58) | Jan 26, 2022 |
| ASRock        | H61M-HVS                    | [8fdf1980ee](https://linux-hardware.org/?probe=8fdf1980ee) | Jan 25, 2022 |
| ASRock        | H61M-HVS                    | [5d19dff1e4](https://linux-hardware.org/?probe=5d19dff1e4) | Jan 25, 2022 |
| Acer          | ConceptD CM100-51A V:1.1    | [663bbd709d](https://linux-hardware.org/?probe=663bbd709d) | Jan 24, 2022 |
| FIRICH        | J1900                       | [937e24af64](https://linux-hardware.org/?probe=937e24af64) | Jan 22, 2022 |
| ASUSTek       | ROG STRIX B360-H GAMING     | [d1505fe489](https://linux-hardware.org/?probe=d1505fe489) | Jan 21, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [75d67cd8a4](https://linux-hardware.org/?probe=75d67cd8a4) | Jan 20, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [7a14d864d4](https://linux-hardware.org/?probe=7a14d864d4) | Jan 20, 2022 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [ec51f5ca3e](https://linux-hardware.org/?probe=ec51f5ca3e) | Jan 19, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [488d339e77](https://linux-hardware.org/?probe=488d339e77) | Jan 19, 2022 |
| MSI           | B450M-A PRO MAX             | [e7225dad8e](https://linux-hardware.org/?probe=e7225dad8e) | Jan 17, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [a76b9e67bb](https://linux-hardware.org/?probe=a76b9e67bb) | Jan 14, 2022 |
| ASUSTek       | H61M-CS                     | [8855875fbd](https://linux-hardware.org/?probe=8855875fbd) | Jan 14, 2022 |
| Unknown       | T3 MRD                      | [33392a90ce](https://linux-hardware.org/?probe=33392a90ce) | Jan 13, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [00a00c3cac](https://linux-hardware.org/?probe=00a00c3cac) | Jan 13, 2022 |
| ASUSTek       | M5A78L-M LX3                | [39f3687349](https://linux-hardware.org/?probe=39f3687349) | Jan 12, 2022 |
| Foxconn       | 2AB1                        | [07faf9a309](https://linux-hardware.org/?probe=07faf9a309) | Jan 12, 2022 |
| ASUSTek       | H110M-C                     | [be4291793d](https://linux-hardware.org/?probe=be4291793d) | Jan 10, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [7ce29e0c54](https://linux-hardware.org/?probe=7ce29e0c54) | Jan 09, 2022 |
| HP            | 8597                        | [09ed815dd0](https://linux-hardware.org/?probe=09ed815dd0) | Jan 08, 2022 |
| Gigabyte      | GA-970A-D3                  | [b1c9832ce6](https://linux-hardware.org/?probe=b1c9832ce6) | Jan 07, 2022 |
| ASRock        | Z370 Pro4                   | [51cba69624](https://linux-hardware.org/?probe=51cba69624) | Jan 06, 2022 |
| ASRock        | B450M-HDV R4.0              | [20dfc25b62](https://linux-hardware.org/?probe=20dfc25b62) | Jan 05, 2022 |
| ASRock        | H97M Pro4                   | [92a6f429b5](https://linux-hardware.org/?probe=92a6f429b5) | Jan 05, 2022 |
| ASRock        | AB350M Pro4                 | [2886b84cc0](https://linux-hardware.org/?probe=2886b84cc0) | Jan 04, 2022 |
| Gigabyte      | B85M-DS3H-A                 | [cd6abb9f49](https://linux-hardware.org/?probe=cd6abb9f49) | Jan 03, 2022 |
| MSI           | 2A9C                        | [8d08f7f383](https://linux-hardware.org/?probe=8d08f7f383) | Dec 31, 2021 |
| HP            | 3397                        | [323dc8992b](https://linux-hardware.org/?probe=323dc8992b) | Dec 31, 2021 |
| ASUSTek       | X79-DELUXE                  | [00b9dd3788](https://linux-hardware.org/?probe=00b9dd3788) | Dec 30, 2021 |
| HP            | 1589                        | [d123a8de64](https://linux-hardware.org/?probe=d123a8de64) | Dec 30, 2021 |
| Foxconn       | 2AB1                        | [bcd6fc46cc](https://linux-hardware.org/?probe=bcd6fc46cc) | Dec 30, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [5f67c759fe](https://linux-hardware.org/?probe=5f67c759fe) | Dec 28, 2021 |
| Gigabyte      | Z390 UD                     | [2399fa64ba](https://linux-hardware.org/?probe=2399fa64ba) | Dec 26, 2021 |
| ASRock        | Z590 Phantom Gaming 4/ac    | [b52ca671f7](https://linux-hardware.org/?probe=b52ca671f7) | Dec 24, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | [783618fe4b](https://linux-hardware.org/?probe=783618fe4b) | Dec 23, 2021 |
| ASUSTek       | H97-PLUS                    | [cba91c2ad2](https://linux-hardware.org/?probe=cba91c2ad2) | Dec 22, 2021 |
| MSI           | B450-A PRO MAX              | [f14eef1ae6](https://linux-hardware.org/?probe=f14eef1ae6) | Dec 20, 2021 |
| Gigabyte      | H310M S2P                   | [a931eb10f0](https://linux-hardware.org/?probe=a931eb10f0) | Dec 19, 2021 |
| Foxconn       | 2AB1                        | [b789981cc4](https://linux-hardware.org/?probe=b789981cc4) | Dec 17, 2021 |
| Gigabyte      | Z590 AORUS ELITE AX         | [c068e358e8](https://linux-hardware.org/?probe=c068e358e8) | Dec 16, 2021 |
| ASUSTek       | M5A78L-M LX3                | [720cc7a45f](https://linux-hardware.org/?probe=720cc7a45f) | Dec 15, 2021 |
| Pegatron      | IPMH61P1                    | [1ba6ea2ee9](https://linux-hardware.org/?probe=1ba6ea2ee9) | Dec 14, 2021 |
| Acer          | ConceptD CM100-51A V:1.1    | [0b3e5753fc](https://linux-hardware.org/?probe=0b3e5753fc) | Dec 13, 2021 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [5c0550c1e8](https://linux-hardware.org/?probe=5c0550c1e8) | Dec 09, 2021 |
| ASUSTek       | PRIME A320M-K               | [fc49eed81d](https://linux-hardware.org/?probe=fc49eed81d) | Dec 09, 2021 |
| ASUSTek       | H81M-C                      | [0b0241baf7](https://linux-hardware.org/?probe=0b0241baf7) | Dec 08, 2021 |
| Dell          | 0MGK50 A02                  | [df4bb96e67](https://linux-hardware.org/?probe=df4bb96e67) | Dec 08, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | [5c46f5e832](https://linux-hardware.org/?probe=5c46f5e832) | Dec 07, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | [a8e4016566](https://linux-hardware.org/?probe=a8e4016566) | Dec 06, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | [ebfed157e7](https://linux-hardware.org/?probe=ebfed157e7) | Dec 06, 2021 |
| Acer          | Aspire X3990                | [e291d06394](https://linux-hardware.org/?probe=e291d06394) | Dec 05, 2021 |
| MSI           | Z370 KRAIT GAMING           | [b213dc07b8](https://linux-hardware.org/?probe=b213dc07b8) | Dec 04, 2021 |
| MSI           | Z370 KRAIT GAMING           | [b562e90f75](https://linux-hardware.org/?probe=b562e90f75) | Dec 04, 2021 |
| ASRock        | Z370 Pro4                   | [4ada22b406](https://linux-hardware.org/?probe=4ada22b406) | Dec 04, 2021 |
| Pegatron      | Benicia                     | [51dae15bcd](https://linux-hardware.org/?probe=51dae15bcd) | Dec 03, 2021 |
| HP            | 8653 A                      | [85d1730019](https://linux-hardware.org/?probe=85d1730019) | Dec 01, 2021 |
| Gigabyte      | B85M-DS3H-A                 | [fbe4820444](https://linux-hardware.org/?probe=fbe4820444) | Dec 01, 2021 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | [500f9c8851](https://linux-hardware.org/?probe=500f9c8851) | Dec 01, 2021 |
| ASUSTek       | PRIME B365M-A               | [c7cbb50843](https://linux-hardware.org/?probe=c7cbb50843) | Nov 30, 2021 |
| Biostar       | TH55XE                      | [9e420cc495](https://linux-hardware.org/?probe=9e420cc495) | Nov 28, 2021 |
| MSI           | H81M-P33                    | [8812103632](https://linux-hardware.org/?probe=8812103632) | Nov 28, 2021 |
| HP            | 1497                        | [6f042fb99c](https://linux-hardware.org/?probe=6f042fb99c) | Nov 28, 2021 |
| ASUSTek       | PRIME X470-PRO              | [2845eaa223](https://linux-hardware.org/?probe=2845eaa223) | Nov 27, 2021 |
| Acer          | Aspire X3990                | [5559b2d988](https://linux-hardware.org/?probe=5559b2d988) | Nov 27, 2021 |
| Foxconn       | 2AB1                        | [09a8a91f9e](https://linux-hardware.org/?probe=09a8a91f9e) | Nov 26, 2021 |
| HP            | 1825                        | [3648c360a9](https://linux-hardware.org/?probe=3648c360a9) | Nov 26, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [ee1387e206](https://linux-hardware.org/?probe=ee1387e206) | Nov 26, 2021 |
| Gigabyte      | Z390 GAMING X-CF            | [34e71f1e27](https://linux-hardware.org/?probe=34e71f1e27) | Nov 25, 2021 |
| Gigabyte      | B450M DS3H-CF               | [0fccfea38c](https://linux-hardware.org/?probe=0fccfea38c) | Nov 25, 2021 |
| ASUSTek       | P8H61-MX R2.0               | [1e15277ce2](https://linux-hardware.org/?probe=1e15277ce2) | Nov 22, 2021 |
| Biostar       | TA790GXE 128M               | [93ff10a9c2](https://linux-hardware.org/?probe=93ff10a9c2) | Nov 21, 2021 |
| Gigabyte      | B85M-D3V-A                  | [12bcc06e6e](https://linux-hardware.org/?probe=12bcc06e6e) | Nov 21, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [9e7d926319](https://linux-hardware.org/?probe=9e7d926319) | Nov 19, 2021 |
| HP            | 0AECh D                     | [c81bcc92ca](https://linux-hardware.org/?probe=c81bcc92ca) | Nov 19, 2021 |
| Foxconn       | 2AB1                        | [f965bf0bd8](https://linux-hardware.org/?probe=f965bf0bd8) | Nov 18, 2021 |
| Apple         | Mac-F4208DC8 PVT            | [3369764322](https://linux-hardware.org/?probe=3369764322) | Nov 17, 2021 |
| Gigabyte      | EP43T-USB3                  | [a24bb09910](https://linux-hardware.org/?probe=a24bb09910) | Nov 15, 2021 |
| Gigabyte      | H81M-H                      | [a895ed29e0](https://linux-hardware.org/?probe=a895ed29e0) | Nov 14, 2021 |
| ASRock        | X570 Extreme4               | [e49fdf2db4](https://linux-hardware.org/?probe=e49fdf2db4) | Nov 13, 2021 |
| MSI           | 970A-G43                    | [19714dd1a0](https://linux-hardware.org/?probe=19714dd1a0) | Nov 08, 2021 |
| Gigabyte      | Z270X-Gaming 5              | [5244244701](https://linux-hardware.org/?probe=5244244701) | Nov 08, 2021 |
| Intel         | DG35EC AAE29266-205         | [89c665e43d](https://linux-hardware.org/?probe=89c665e43d) | Nov 02, 2021 |
| Intel         | DG35EC AAE29266-205         | [1046b28a41](https://linux-hardware.org/?probe=1046b28a41) | Nov 02, 2021 |
| ASRock        | P67 Extreme4                | [a70eb2d3f8](https://linux-hardware.org/?probe=a70eb2d3f8) | Oct 29, 2021 |
| ASRock        | P67 Extreme4                | [0a07f4c735](https://linux-hardware.org/?probe=0a07f4c735) | Oct 29, 2021 |
| MSI           | 2A9Ch                       | [2f752a1a3e](https://linux-hardware.org/?probe=2f752a1a3e) | Oct 28, 2021 |
| Foxconn       | 2AB1                        | [49aef5b72e](https://linux-hardware.org/?probe=49aef5b72e) | Oct 26, 2021 |
| HP            | 158B                        | [24399f4e69](https://linux-hardware.org/?probe=24399f4e69) | Oct 20, 2021 |
| HP            | 339A                        | [d9c6208191](https://linux-hardware.org/?probe=d9c6208191) | Oct 16, 2021 |
| Dell          | 0M9KCM A02                  | [a925b0f3d1](https://linux-hardware.org/?probe=a925b0f3d1) | Oct 12, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | [f6e75d0258](https://linux-hardware.org/?probe=f6e75d0258) | Oct 09, 2021 |
| MSI           | B460M PRO-VDH WIFI          | [05711b548f](https://linux-hardware.org/?probe=05711b548f) | Oct 03, 2021 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [de0f051658](https://linux-hardware.org/?probe=de0f051658) | Oct 02, 2021 |
| Shuttle       | FS61                        | [b25047a516](https://linux-hardware.org/?probe=b25047a516) | Oct 01, 2021 |
| Gigabyte      | H67A-USB3-B3                | [9440c234ae](https://linux-hardware.org/?probe=9440c234ae) | Sep 28, 2021 |
| Apple         | Mac-F221BEC8                | [1754c64091](https://linux-hardware.org/?probe=1754c64091) | Sep 27, 2021 |
| ASUSTek       | P7H55-M                     | [3367bc011a](https://linux-hardware.org/?probe=3367bc011a) | Sep 25, 2021 |
| Dell          | 0Y5DDC A00                  | [df95ea94b8](https://linux-hardware.org/?probe=df95ea94b8) | Sep 25, 2021 |
| Dell          | 0Y5DDC A00                  | [10ee1abc07](https://linux-hardware.org/?probe=10ee1abc07) | Sep 25, 2021 |
| ASRock        | M3A790GXH/128M              | [818ec10ec8](https://linux-hardware.org/?probe=818ec10ec8) | Sep 24, 2021 |
| Gigabyte      | H67A-USB3-B3                | [0aab60dbc8](https://linux-hardware.org/?probe=0aab60dbc8) | Sep 24, 2021 |
| Intel         | X79 V1.x                    | [19223e911c](https://linux-hardware.org/?probe=19223e911c) | Sep 22, 2021 |
| Gigabyte      | H67A-USB3-B3                | [772b49f342](https://linux-hardware.org/?probe=772b49f342) | Sep 21, 2021 |
| ASUSTek       | M4N78-AM                    | [3d8e0efc00](https://linux-hardware.org/?probe=3d8e0efc00) | Sep 21, 2021 |
| ASRock        | A320M-HDV                   | [24bb7c7d18](https://linux-hardware.org/?probe=24bb7c7d18) | Sep 17, 2021 |
| Gigabyte      | Z68P-DS3                    | [1ddd2fcf1d](https://linux-hardware.org/?probe=1ddd2fcf1d) | Sep 14, 2021 |
| Intel         | H61                         | [0010dbcb5e](https://linux-hardware.org/?probe=0010dbcb5e) | Sep 10, 2021 |
| HP            | 8767 A                      | [7f022c67ac](https://linux-hardware.org/?probe=7f022c67ac) | Sep 09, 2021 |
| Gigabyte      | B450M DS3H V2               | [633441bc2b](https://linux-hardware.org/?probe=633441bc2b) | Sep 05, 2021 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [c9476d5d06](https://linux-hardware.org/?probe=c9476d5d06) | Sep 02, 2021 |
| Gigabyte      | F2A55M-HD2                  | [0c05ab5b21](https://linux-hardware.org/?probe=0c05ab5b21) | Aug 30, 2021 |
| ASRock        | H81TM-ITX R2.0              | [4f04e7309e](https://linux-hardware.org/?probe=4f04e7309e) | Aug 30, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | [d0ff1c6977](https://linux-hardware.org/?probe=d0ff1c6977) | Aug 25, 2021 |
| ASUSTek       | P6X58D-E                    | [db1ef28e92](https://linux-hardware.org/?probe=db1ef28e92) | Aug 20, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [1176a287c7](https://linux-hardware.org/?probe=1176a287c7) | Aug 19, 2021 |
| ASUSTek       | TUF Gaming B450M-PRO II     | [73beb900ea](https://linux-hardware.org/?probe=73beb900ea) | Aug 15, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [e302074e5e](https://linux-hardware.org/?probe=e302074e5e) | Aug 14, 2021 |
| Gigabyte      | H310M M.2 x.x               | [69e2e83b95](https://linux-hardware.org/?probe=69e2e83b95) | Aug 10, 2021 |
| Gigabyte      | H310M M.2 x.x               | [86d69a15b9](https://linux-hardware.org/?probe=86d69a15b9) | Aug 10, 2021 |
| Acer          | Aspire XC-603G              | [8a37f28ecc](https://linux-hardware.org/?probe=8a37f28ecc) | Jul 31, 2021 |
| ASUSTek       | P5KPL-AM SE                 | [a97fc63d3d](https://linux-hardware.org/?probe=a97fc63d3d) | Jul 23, 2021 |
| Biostar       | H61MH                       | [adca68749a](https://linux-hardware.org/?probe=adca68749a) | Jul 23, 2021 |
| Biostar       | H61MH                       | [2c690e433f](https://linux-hardware.org/?probe=2c690e433f) | Jul 23, 2021 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | [9e27318e84](https://linux-hardware.org/?probe=9e27318e84) | Jul 14, 2021 |
| ASRock        | B450 Pro4                   | [c5d0611f79](https://linux-hardware.org/?probe=c5d0611f79) | Jun 13, 2021 |
| ASUSTek       | PRIME A320M-K               | [5e0580b431](https://linux-hardware.org/?probe=5e0580b431) | Jun 08, 2021 |
| ASUSTek       | H81M-K                      | [52fa7c5a31](https://linux-hardware.org/?probe=52fa7c5a31) | May 30, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [63da02a979](https://linux-hardware.org/?probe=63da02a979) | May 19, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [223234378e](https://linux-hardware.org/?probe=223234378e) | May 04, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [a208e8a358](https://linux-hardware.org/?probe=a208e8a358) | May 01, 2021 |
| Gigabyte      | AB350M-DS3H V2-CF           | [98d6e8f2d2](https://linux-hardware.org/?probe=98d6e8f2d2) | Apr 15, 2021 |
| ASUSTek       | SABERTOOTH Z87              | [542d0b7163](https://linux-hardware.org/?probe=542d0b7163) | Apr 13, 2021 |
| Dell          | 06NWYK A01                  | [304541ce36](https://linux-hardware.org/?probe=304541ce36) | Apr 08, 2021 |
| Dell          | 06NWYK A01                  | [47766de8d9](https://linux-hardware.org/?probe=47766de8d9) | Apr 07, 2021 |
| MSI           | H61M-P31                    | [867b109a0b](https://linux-hardware.org/?probe=867b109a0b) | Apr 07, 2021 |
| HP            | 843F                        | [d5b68ba3fb](https://linux-hardware.org/?probe=d5b68ba3fb) | Apr 07, 2021 |
| MSI           | B450M PRO-VDH MAX           | [9a1463fd59](https://linux-hardware.org/?probe=9a1463fd59) | Mar 22, 2021 |
| Gigabyte      | H61M-S2PV                   | [bbe4962b33](https://linux-hardware.org/?probe=bbe4962b33) | Mar 22, 2021 |
| HP            | 843F                        | [a4fc49c430](https://linux-hardware.org/?probe=a4fc49c430) | Mar 09, 2021 |
| MSI           | B450M PRO-VDH MAX           | [65c7806bad](https://linux-hardware.org/?probe=65c7806bad) | Mar 09, 2021 |
| MSI           | B450M PRO-VDH MAX           | [e1289a40a1](https://linux-hardware.org/?probe=e1289a40a1) | Feb 28, 2021 |
| Lenovo        | MAHOBAY NOK                 | [e3c14a6397](https://linux-hardware.org/?probe=e3c14a6397) | Feb 25, 2021 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [268b9f895a](https://linux-hardware.org/?probe=268b9f895a) | Feb 10, 2021 |
| Gigabyte      | Z77-DS3H                    | [a5a556b691](https://linux-hardware.org/?probe=a5a556b691) | Feb 09, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | [ea93e4d3cd](https://linux-hardware.org/?probe=ea93e4d3cd) | Feb 09, 2021 |
| MSI           | B450M PRO-VDH MAX           | [895ec88c20](https://linux-hardware.org/?probe=895ec88c20) | Feb 08, 2021 |
| ASRock        | Z75 Pro3                    | [f2d919b5c5](https://linux-hardware.org/?probe=f2d919b5c5) | Feb 03, 2021 |
| Biostar       | Hi-Fi A70U3P                | [c2727e98b9](https://linux-hardware.org/?probe=c2727e98b9) | Feb 02, 2021 |
| Biostar       | Hi-Fi A70U3P                | [2c11d020c7](https://linux-hardware.org/?probe=2c11d020c7) | Feb 02, 2021 |
| MSI           | B450M PRO-VDH MAX           | [98cc7a4bca](https://linux-hardware.org/?probe=98cc7a4bca) | Jan 15, 2021 |
| Gigabyte      | GA-MA78GM-S2H               | [d40272076d](https://linux-hardware.org/?probe=d40272076d) | Jan 13, 2021 |
| Gigabyte      | GA-MA78GM-S2H               | [d31c109973](https://linux-hardware.org/?probe=d31c109973) | Jan 13, 2021 |
| EVGA          | 132-CK-NF79 2               | [44c54ae3df](https://linux-hardware.org/?probe=44c54ae3df) | Jan 09, 2021 |
| MSI           | P35 Platinum                | [105ebcfc8d](https://linux-hardware.org/?probe=105ebcfc8d) | Jan 08, 2021 |
| Gigabyte      | G31M-ES2L                   | [4e7d5b4879](https://linux-hardware.org/?probe=4e7d5b4879) | Jan 07, 2021 |
| ASUSTek       | M5A97                       | [0f975cd5e6](https://linux-hardware.org/?probe=0f975cd5e6) | Jan 03, 2021 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [721dd0a694](https://linux-hardware.org/?probe=721dd0a694) | Jan 03, 2021 |
| MSI           | B450M PRO-VDH MAX           | [7197a45b8a](https://linux-hardware.org/?probe=7197a45b8a) | Dec 30, 2020 |
| Dell          | 0T656F A02                  | [1830ce642b](https://linux-hardware.org/?probe=1830ce642b) | Dec 29, 2020 |
| ASUSTek       | M5A97                       | [800aa16703](https://linux-hardware.org/?probe=800aa16703) | Dec 29, 2020 |
| HP            | 18EA                        | [67e2e927b6](https://linux-hardware.org/?probe=67e2e927b6) | Dec 27, 2020 |
| MSI           | B450M PRO-VDH MAX           | [803e6b6194](https://linux-hardware.org/?probe=803e6b6194) | Dec 25, 2020 |
| ASUSTek       | M5A99X EVO R2.0             | [f7d949f5a7](https://linux-hardware.org/?probe=f7d949f5a7) | Dec 23, 2020 |
| Biostar       | TA785G3 HD                  | [ed91ded9e9](https://linux-hardware.org/?probe=ed91ded9e9) | Dec 23, 2020 |
| ASRock        | Z87E-ITX                    | [861b40ea1d](https://linux-hardware.org/?probe=861b40ea1d) | Dec 21, 2020 |
| Dell          | 0GN723                      | [a952bf5fa6](https://linux-hardware.org/?probe=a952bf5fa6) | Dec 20, 2020 |
| HP            | 8433 11                     | [691ef58a05](https://linux-hardware.org/?probe=691ef58a05) | Dec 09, 2020 |
| ASUSTek       | PRIME H310M-E R2.0          | [3070faaf5e](https://linux-hardware.org/?probe=3070faaf5e) | Dec 03, 2020 |
| Gigabyte      | H61M-DS2                    | [49263df7ee](https://linux-hardware.org/?probe=49263df7ee) | Dec 02, 2020 |
| HP            | 304Bh                       | [d30d065810](https://linux-hardware.org/?probe=d30d065810) | Nov 30, 2020 |
| Gigabyte      | Z77M-D3H                    | [47c75561ac](https://linux-hardware.org/?probe=47c75561ac) | Nov 21, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [10e9d31bdb](https://linux-hardware.org/?probe=10e9d31bdb) | Nov 20, 2020 |
| ASUSTek       | PRIME Z270-A                | [d47493ecae](https://linux-hardware.org/?probe=d47493ecae) | Nov 16, 2020 |
| Gigabyte      | H81M-S2H                    | [54fd3c5678](https://linux-hardware.org/?probe=54fd3c5678) | Nov 15, 2020 |
| MSI           | B450M PRO-M2 MAX            | [f2face0a01](https://linux-hardware.org/?probe=f2face0a01) | Nov 07, 2020 |
| ASUSTek       | PRIME A320I-K               | [6bfc04099a](https://linux-hardware.org/?probe=6bfc04099a) | Nov 06, 2020 |
| eMachines     | EL1358G                     | [9aabea4465](https://linux-hardware.org/?probe=9aabea4465) | Oct 28, 2020 |
| HP            | 8433 11                     | [670028bf54](https://linux-hardware.org/?probe=670028bf54) | Oct 16, 2020 |
| MSI           | P35 Platinum                | [232a14759f](https://linux-hardware.org/?probe=232a14759f) | Oct 14, 2020 |
| MSI           | MAG B550M MORTAR            | [653a4a9f6e](https://linux-hardware.org/?probe=653a4a9f6e) | Oct 11, 2020 |
| HP            | 304Ah                       | [5143880fd9](https://linux-hardware.org/?probe=5143880fd9) | Oct 09, 2020 |
| ASUSTek       | PRIME A320M-K               | [55e4fca971](https://linux-hardware.org/?probe=55e4fca971) | Oct 08, 2020 |
| ASUSTek       | TUF B360-PLUS GAMING        | [1779589a19](https://linux-hardware.org/?probe=1779589a19) | Oct 08, 2020 |
| Gigabyte      | Z390 DESIGNARE-CF           | [f304a2629f](https://linux-hardware.org/?probe=f304a2629f) | Oct 04, 2020 |
| Acer          | WMCP78M                     | [2510b2bc49](https://linux-hardware.org/?probe=2510b2bc49) | Oct 02, 2020 |
| Intel         | DG41RQ AAE54511-204         | [651cef3c94](https://linux-hardware.org/?probe=651cef3c94) | Sep 29, 2020 |
| MSI           | FM2-A55M-E33                | [50d8cc3e2d](https://linux-hardware.org/?probe=50d8cc3e2d) | Sep 28, 2020 |
| ASUSTek       | Z170-DELUXE                 | [8eef95cd00](https://linux-hardware.org/?probe=8eef95cd00) | Sep 12, 2020 |
| MSI           | B450 TOMAHAWK MAX           | [73d7e76e09](https://linux-hardware.org/?probe=73d7e76e09) | Sep 11, 2020 |
| Dell          | 0Y958C A00                  | [253e97e06c](https://linux-hardware.org/?probe=253e97e06c) | Sep 10, 2020 |
| Gigabyte      | F2A88XN-WIFI                | [3b51467541](https://linux-hardware.org/?probe=3b51467541) | Sep 06, 2020 |
| Lenovo        | MAHOBAY NOK                 | [d95b985658](https://linux-hardware.org/?probe=d95b985658) | Sep 01, 2020 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [78ec970ee1](https://linux-hardware.org/?probe=78ec970ee1) | Aug 29, 2020 |
| ASUSTek       | STRIX Z270H GAMING          | [ce54993f5d](https://linux-hardware.org/?probe=ce54993f5d) | Aug 29, 2020 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [40f5f91c4e](https://linux-hardware.org/?probe=40f5f91c4e) | Aug 26, 2020 |
| HP            | 81B4                        | [6747078a67](https://linux-hardware.org/?probe=6747078a67) | Aug 24, 2020 |
| HP            | 81B4                        | [ff66e031e4](https://linux-hardware.org/?probe=ff66e031e4) | Aug 18, 2020 |
| ASUSTek       | SABERTOOTH Z87              | [86ff4005e2](https://linux-hardware.org/?probe=86ff4005e2) | Aug 15, 2020 |
| MSI           | B450M PRO-VDH MAX           | [ae51610784](https://linux-hardware.org/?probe=ae51610784) | Aug 09, 2020 |
| ASUSTek       | H81I-PLUS                   | [7259e07174](https://linux-hardware.org/?probe=7259e07174) | Aug 07, 2020 |
| SYS           | H310CH5-TI2                 | [fb33742784](https://linux-hardware.org/?probe=fb33742784) | Aug 06, 2020 |
| Gigabyte      | Z97-D3H-CF                  | [fd308ae7e8](https://linux-hardware.org/?probe=fd308ae7e8) | Aug 03, 2020 |
| ASUSTek       | P8H61-M LX3 R2.0            | [6cf9ba1da5](https://linux-hardware.org/?probe=6cf9ba1da5) | Jul 24, 2020 |
| ASUSTek       | P8H61-M LX3 R2.0            | [9372988884](https://linux-hardware.org/?probe=9372988884) | Jul 24, 2020 |
| Dell          | 08NPPY A00                  | [ca6080756b](https://linux-hardware.org/?probe=ca6080756b) | Jul 24, 2020 |
| Dell          | 08NPPY A00                  | [41e1632a84](https://linux-hardware.org/?probe=41e1632a84) | Jul 24, 2020 |
| HP            | 2ADC                        | [2faf91f855](https://linux-hardware.org/?probe=2faf91f855) | Jul 02, 2020 |
| MSI           | B450M PRO-VDH MAX           | [9159f538a0](https://linux-hardware.org/?probe=9159f538a0) | Jun 28, 2020 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [f7a297ae2c](https://linux-hardware.org/?probe=f7a297ae2c) | Jun 23, 2020 |
| Gigabyte      | G31M-ES2L                   | [f9f7ec4c96](https://linux-hardware.org/?probe=f9f7ec4c96) | May 27, 2020 |
| ASUSTek       | P8Z77-V LX                  | [aa53a3eba5](https://linux-hardware.org/?probe=aa53a3eba5) | May 26, 2020 |
| MSI           | B450M PRO-VDH MAX           | [0e7c8d0cdc](https://linux-hardware.org/?probe=0e7c8d0cdc) | May 25, 2020 |
| Acer          | EQ45M                       | [a682473a39](https://linux-hardware.org/?probe=a682473a39) | May 23, 2020 |
| ASUSTek       | PRIME A320M-K               | [14dfb9eb8c](https://linux-hardware.org/?probe=14dfb9eb8c) | May 22, 2020 |
| ASUSTek       | PRIME A320M-K               | [299eb96cce](https://linux-hardware.org/?probe=299eb96cce) | May 22, 2020 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [cb10b79124](https://linux-hardware.org/?probe=cb10b79124) | May 16, 2020 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [592e93d734](https://linux-hardware.org/?probe=592e93d734) | May 16, 2020 |
| MSI           | GF615M-P33 V2               | [e6c02461aa](https://linux-hardware.org/?probe=e6c02461aa) | May 14, 2020 |
| ASRock        | B450M-HDV R4.0              | [484cc8fd5a](https://linux-hardware.org/?probe=484cc8fd5a) | May 07, 2020 |
| ASRock        | B450M-HDV R4.0              | [dbbea9cdaf](https://linux-hardware.org/?probe=dbbea9cdaf) | May 07, 2020 |
| Intel         | DG33FB AAD81072-306         | [2c0b3102ba](https://linux-hardware.org/?probe=2c0b3102ba) | May 01, 2020 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [7a18707ff5](https://linux-hardware.org/?probe=7a18707ff5) | Apr 26, 2020 |
| Acer          | EQ45M                       | [03e154e2dc](https://linux-hardware.org/?probe=03e154e2dc) | Apr 21, 2020 |
| eMachines     | EL1358G                     | [0ec6f0c0df](https://linux-hardware.org/?probe=0ec6f0c0df) | Apr 20, 2020 |
| ASUSTek       | ROG STRIX B360-I GAMING     | [7fa6504e44](https://linux-hardware.org/?probe=7fa6504e44) | Apr 18, 2020 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [21eac3f5ab](https://linux-hardware.org/?probe=21eac3f5ab) | Apr 14, 2020 |
| MSI           | H110M PRO-VD                | [a69e76d844](https://linux-hardware.org/?probe=a69e76d844) | Apr 11, 2020 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [fb24b9471a](https://linux-hardware.org/?probe=fb24b9471a) | Apr 08, 2020 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [9ba07d6518](https://linux-hardware.org/?probe=9ba07d6518) | Apr 08, 2020 |
| ASUSTek       | P5K                         | [60860911b6](https://linux-hardware.org/?probe=60860911b6) | Apr 03, 2020 |
| MSI           | MPG Z390 GAMING PRO CARB... | [d69e7b9642](https://linux-hardware.org/?probe=d69e7b9642) | Apr 02, 2020 |
| ECS           | H55H-M                      | [1673d5808e](https://linux-hardware.org/?probe=1673d5808e) | Mar 31, 2020 |
| ASRock        | Z77 Extreme4                | [1ea076e57b](https://linux-hardware.org/?probe=1ea076e57b) | Mar 19, 2020 |
| MSI           | B450 GAMING PLUS MAX        | [642694d59f](https://linux-hardware.org/?probe=642694d59f) | Mar 19, 2020 |
| ASUSTek       | P5K                         | [64c435a307](https://linux-hardware.org/?probe=64c435a307) | Mar 17, 2020 |
| ASUSTek       | P5K                         | [d532983f25](https://linux-hardware.org/?probe=d532983f25) | Mar 17, 2020 |
| MSI           | B450 GAMING PLUS MAX        | [86896f4c65](https://linux-hardware.org/?probe=86896f4c65) | Mar 17, 2020 |
| ASRock        | Z77 Extreme4                | [847badc92c](https://linux-hardware.org/?probe=847badc92c) | Mar 17, 2020 |
| ASRock        | B85M Pro3                   | [765094a989](https://linux-hardware.org/?probe=765094a989) | Mar 10, 2020 |
| MSI           | Z170A PC MATE               | [201d14e45c](https://linux-hardware.org/?probe=201d14e45c) | Mar 09, 2020 |
| ASUSTek       | P8B75-M                     | [56ae5142e3](https://linux-hardware.org/?probe=56ae5142e3) | Feb 24, 2020 |
| ASUSTek       | SABERTOOTH 990FX/GEN3 R2... | [9c21c6ca8e](https://linux-hardware.org/?probe=9c21c6ca8e) | Feb 17, 2020 |
| ASUSTek       | SABERTOOTH 990FX/GEN3 R2... | [8eb7f19502](https://linux-hardware.org/?probe=8eb7f19502) | Feb 17, 2020 |
| ASUSTek       | Maximus V FORMULA           | [713f5c5aaf](https://linux-hardware.org/?probe=713f5c5aaf) | Feb 14, 2020 |
| Gigabyte      | H67M-D2-B3                  | [8b9d4bcb86](https://linux-hardware.org/?probe=8b9d4bcb86) | Feb 01, 2020 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [03eef2b7d3](https://linux-hardware.org/?probe=03eef2b7d3) | Feb 01, 2020 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [cd4d0236ad](https://linux-hardware.org/?probe=cd4d0236ad) | Jan 30, 2020 |
| MSI           | FM2-A55M-E33                | [4587ab8edd](https://linux-hardware.org/?probe=4587ab8edd) | Jan 25, 2020 |
| MSI           | FM2-A55M-E33                | [93fb1697b5](https://linux-hardware.org/?probe=93fb1697b5) | Jan 25, 2020 |
| Gigabyte      | H97-HD3                     | [80245136bd](https://linux-hardware.org/?probe=80245136bd) | Jan 18, 2020 |
| ASRock        | Z87 Extreme6                | [ffb3f65bcd](https://linux-hardware.org/?probe=ffb3f65bcd) | Jan 18, 2020 |
| Dell          | 0KWVT8 A00                  | [55b5255c24](https://linux-hardware.org/?probe=55b5255c24) | Jan 18, 2020 |
| ASRock        | N68-GS4/USB3 FX R2.0        | [1a903c9d61](https://linux-hardware.org/?probe=1a903c9d61) | Jan 14, 2020 |
| Pegatron      | IPMH61P1                    | [2a47818e18](https://linux-hardware.org/?probe=2a47818e18) | Jan 06, 2020 |
| ASRock        | H87M Pro4                   | [40dee920a9](https://linux-hardware.org/?probe=40dee920a9) | Dec 25, 2019 |
| Gigabyte      | Z390 GAMING SLI-CF          | [41795f04de](https://linux-hardware.org/?probe=41795f04de) | Dec 24, 2019 |
| MSI           | A320M PRO-VD PLUS           | [805e960aa9](https://linux-hardware.org/?probe=805e960aa9) | Dec 18, 2019 |
| ASRock        | X399 Phantom Gaming 6       | [b89b031eb9](https://linux-hardware.org/?probe=b89b031eb9) | Dec 14, 2019 |
| MSI           | B150M BAZOOKA               | [3afe42946d](https://linux-hardware.org/?probe=3afe42946d) | Dec 12, 2019 |
| Gigabyte      | H61M-S1                     | [2302b497cc](https://linux-hardware.org/?probe=2302b497cc) | Dec 11, 2019 |
| Intel         | DH67BL AAG10189-208         | [c9400c1fcb](https://linux-hardware.org/?probe=c9400c1fcb) | Dec 11, 2019 |
| Intel         | DH67BL AAG10189-208         | [18d758491c](https://linux-hardware.org/?probe=18d758491c) | Dec 11, 2019 |
| Gigabyte      | H61M-S1                     | [cfbe6b0f33](https://linux-hardware.org/?probe=cfbe6b0f33) | Dec 11, 2019 |
| Gigabyte      | H61M-S1                     | [c5b3e3f258](https://linux-hardware.org/?probe=c5b3e3f258) | Dec 11, 2019 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [a548b448e7](https://linux-hardware.org/?probe=a548b448e7) | Dec 09, 2019 |
| MSI           | PH67A-C43                   | [35ffc61791](https://linux-hardware.org/?probe=35ffc61791) | Dec 06, 2019 |
| MSI           | PH67A-C43                   | [1a5faa8a98](https://linux-hardware.org/?probe=1a5faa8a98) | Dec 05, 2019 |
| Lenovo        | ThinkCentre M55E 9632BU8    | [209a9171b1](https://linux-hardware.org/?probe=209a9171b1) | Dec 04, 2019 |
| HP            | 18EA                        | [101b838d0e](https://linux-hardware.org/?probe=101b838d0e) | Nov 10, 2019 |
| ASUSTek       | SABERTOOTH Z77              | [889648300b](https://linux-hardware.org/?probe=889648300b) | Oct 04, 2019 |
| ASUSTek       | SABERTOOTH Z77              | [28d0871f17](https://linux-hardware.org/?probe=28d0871f17) | Oct 02, 2019 |
| ASUSTek       | SABERTOOTH Z77              | [22a74597d5](https://linux-hardware.org/?probe=22a74597d5) | Oct 02, 2019 |
| ASUSTek       | SABERTOOTH Z77              | [31f72c0672](https://linux-hardware.org/?probe=31f72c0672) | Oct 02, 2019 |
| Dell          | 048DY8 A00                  | [500dc4f9f5](https://linux-hardware.org/?probe=500dc4f9f5) | Sep 11, 2019 |
| ASRock        | H97M Pro4                   | [168644ddd0](https://linux-hardware.org/?probe=168644ddd0) | Sep 04, 2019 |
| Gigabyte      | H310M S2P                   | [6fffbe0439](https://linux-hardware.org/?probe=6fffbe0439) | Sep 02, 2019 |
| MSI           | Z97A GAMING 6               | [6a9086bf86](https://linux-hardware.org/?probe=6a9086bf86) | Jul 06, 2019 |
| ASUSTek       | PRIME A320M-K               | [0f2ef33214](https://linux-hardware.org/?probe=0f2ef33214) | Jun 27, 2019 |
| Dell          | 09KPNV A00                  | [b1769092a2](https://linux-hardware.org/?probe=b1769092a2) | Jun 22, 2019 |
| Dell          | 01TKCC A01                  | [c133935d4f](https://linux-hardware.org/?probe=c133935d4f) | Jun 19, 2019 |
| ASUSTek       | STRIKER II NSE              | [13d6ead175](https://linux-hardware.org/?probe=13d6ead175) | May 22, 2019 |
| ASRock        | H97M Pro4                   | [410a594809](https://linux-hardware.org/?probe=410a594809) | May 21, 2019 |
| ASUSTek       | ROG Maximus X HERO          | [d7d3d4f56b](https://linux-hardware.org/?probe=d7d3d4f56b) | May 19, 2019 |
| MSI           | B450 TOMAHAWK               | [336d0df071](https://linux-hardware.org/?probe=336d0df071) | May 03, 2019 |
| Intel         | DG35EC AAE29266-205         | [1ddb0e459f](https://linux-hardware.org/?probe=1ddb0e459f) | Apr 26, 2019 |
| Intel         | SHARKBAY                    | [d411643b19](https://linux-hardware.org/?probe=d411643b19) | Apr 23, 2019 |
| Dell          | 01TKCC A01                  | [3cfa230457](https://linux-hardware.org/?probe=3cfa230457) | Apr 12, 2019 |
| Dell          | 01TKCC A01                  | [94e2e60839](https://linux-hardware.org/?probe=94e2e60839) | Apr 11, 2019 |
| MSI           | Z87M-G43                    | [cbb0c4be39](https://linux-hardware.org/?probe=cbb0c4be39) | Apr 11, 2019 |
| MSI           | Z87M-G43                    | [6fb3422b8b](https://linux-hardware.org/?probe=6fb3422b8b) | Apr 11, 2019 |
| HP            | 158A                        | [61be039d0f](https://linux-hardware.org/?probe=61be039d0f) | Apr 02, 2019 |
| Intel         | DH55HC AAE70933-502         | [8f109c807c](https://linux-hardware.org/?probe=8f109c807c) | Feb 15, 2019 |
| Intel         | DH55HC AAE70933-502         | [be7548c062](https://linux-hardware.org/?probe=be7548c062) | Feb 15, 2019 |
| Wibtek        | H61-M HDMI2                 | [6f082a4f2d](https://linux-hardware.org/?probe=6f082a4f2d) | Feb 12, 2019 |
| Wibtek        | H61-M HDMI2                 | [3a44341e10](https://linux-hardware.org/?probe=3a44341e10) | Feb 12, 2019 |
| ECS           | H61H2-M2                    | [ed1e345718](https://linux-hardware.org/?probe=ed1e345718) | Feb 02, 2019 |
| ECS           | H61H2-M2                    | [554a16077e](https://linux-hardware.org/?probe=554a16077e) | Feb 01, 2019 |
| Gigabyte      | G31M-ES2L                   | [8531feefb2](https://linux-hardware.org/?probe=8531feefb2) | Jan 07, 2019 |
| Gigabyte      | A320M-S2H-CF                | [a72d5458ff](https://linux-hardware.org/?probe=a72d5458ff) | Nov 23, 2018 |
| Gigabyte      | B85M-D3H                    | [d206454b5f](https://linux-hardware.org/?probe=d206454b5f) | Aug 27, 2018 |
| ASUSTek       | P5GD1 PRO                   | [7f52004043](https://linux-hardware.org/?probe=7f52004043) | Aug 02, 2018 |
| ECS           | H61H2-M2                    | [765806fe73](https://linux-hardware.org/?probe=765806fe73) | Jun 01, 2018 |
| Gigabyte      | GA-990FXA-UD3               | [2e67236dbb](https://linux-hardware.org/?probe=2e67236dbb) | Feb 23, 2018 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Elementary/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Elementary 6.1   | 187      | 30.26%  |
| Elementary 7.1   | 129      | 20.87%  |
| Elementary 5.1.7 | 72       | 11.65%  |
| Elementary 7     | 68       | 11%     |
| Elementary 6     | 66       | 10.68%  |
| Elementary 8     | 21       | 3.4%    |
| Elementary 5.1   | 17       | 2.75%   |
| Elementary 5.0   | 17       | 2.75%   |
| Elementary 5.1.2 | 10       | 1.62%   |
| Elementary 5.1.4 | 7        | 1.13%   |
| Elementary 5.1.3 | 7        | 1.13%   |
| Elementary 0.4.1 | 7        | 1.13%   |
| Elementary 5.1.6 | 6        | 0.97%   |
| Elementary 6.0   | 2        | 0.32%   |
| Elementary 5.1.5 | 2        | 0.32%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Elementary | 584      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.11.0-43-generic | 36       | 5.31%   |
| 5.15.0-58-generic | 25       | 3.69%   |
| 5.11.0-41-generic | 19       | 2.8%    |
| 6.2.0-33-generic  | 18       | 2.65%   |
| 5.11.0-40-generic | 17       | 2.51%   |
| 5.13.0-39-generic | 16       | 2.36%   |
| 5.13.0-28-generic | 16       | 2.36%   |
| 6.8.0-49-generic  | 15       | 2.21%   |
| 5.15.0-46-generic | 13       | 1.92%   |
| 6.5.0-26-generic  | 12       | 1.77%   |
| 6.8.0-40-generic  | 11       | 1.62%   |
| 5.0.0-37-generic  | 11       | 1.62%   |
| 6.5.0-35-generic  | 10       | 1.47%   |
| 5.13.0-27-generic | 10       | 1.47%   |
| 5.11.0-27-generic | 10       | 1.47%   |
| 5.4.0-42-generic  | 9        | 1.33%   |
| 5.19.0-32-generic | 9        | 1.33%   |
| 5.15.0-56-generic | 9        | 1.33%   |
| 5.13.0-40-generic | 9        | 1.33%   |
| 5.13.0-30-generic | 9        | 1.33%   |
| 6.8.0-51-generic  | 8        | 1.18%   |
| 6.2.0-36-generic  | 8        | 1.18%   |
| 5.4.0-48-generic  | 8        | 1.18%   |
| 6.5.0-41-generic  | 7        | 1.03%   |
| 6.5.0-28-generic  | 7        | 1.03%   |
| 5.13.0-35-generic | 7        | 1.03%   |
| 5.11.0-37-generic | 7        | 1.03%   |
| 6.2.0-35-generic  | 6        | 0.88%   |
| 5.4.0-65-generic  | 6        | 0.88%   |
| 5.4.0-58-generic  | 6        | 0.88%   |
| 5.19.0-35-generic | 6        | 0.88%   |
| 5.13.0-37-generic | 6        | 0.88%   |
| 5.11.0-25-generic | 6        | 0.88%   |
| 6.8.0-50-generic  | 5        | 0.74%   |
| 6.8.0-48-generic  | 5        | 0.74%   |
| 6.8.0-45-generic  | 5        | 0.74%   |
| 6.5.0-44-generic  | 5        | 0.74%   |
| 6.2.0-39-generic  | 5        | 0.74%   |
| 5.4.0-54-generic  | 5        | 0.74%   |
| 5.3.0-46-generic  | 5        | 0.74%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11.0  | 105      | 16.88%  |
| 5.13.0  | 86       | 13.83%  |
| 5.15.0  | 80       | 12.86%  |
| 5.4.0   | 68       | 10.93%  |
| 6.5.0   | 58       | 9.32%   |
| 6.8.0   | 52       | 8.36%   |
| 6.2.0   | 51       | 8.2%    |
| 5.19.0  | 34       | 5.47%   |
| 5.3.0   | 24       | 3.86%   |
| 4.15.0  | 24       | 3.86%   |
| 5.0.0   | 15       | 2.41%   |
| 5.8.0   | 5        | 0.8%    |
| 4.18.0  | 3        | 0.48%   |
| 4.4.0   | 2        | 0.32%   |
| 6.7.10  | 1        | 0.16%   |
| 6.4.5   | 1        | 0.16%   |
| 6.12.6  | 1        | 0.16%   |
| 6.11.5  | 1        | 0.16%   |
| 6.1.8   | 1        | 0.16%   |
| 5.2.11  | 1        | 0.16%   |
| 5.17.3  | 1        | 0.16%   |
| 5.17.0  | 1        | 0.16%   |
| 5.16.15 | 1        | 0.16%   |
| 5.15.36 | 1        | 0.16%   |
| 5.15.12 | 1        | 0.16%   |
| 5.15.1  | 1        | 0.16%   |
| 5.14.0  | 1        | 0.16%   |
| 5.0.11  | 1        | 0.16%   |
| 4.10.0  | 1        | 0.16%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11    | 105      | 16.88%  |
| 5.13    | 86       | 13.83%  |
| 5.15    | 83       | 13.34%  |
| 5.4     | 68       | 10.93%  |
| 6.5     | 58       | 9.32%   |
| 6.8     | 52       | 8.36%   |
| 6.2     | 51       | 8.2%    |
| 5.19    | 34       | 5.47%   |
| 5.3     | 24       | 3.86%   |
| 4.15    | 24       | 3.86%   |
| 5.0     | 16       | 2.57%   |
| 5.8     | 5        | 0.8%    |
| 4.18    | 3        | 0.48%   |
| 5.17    | 2        | 0.32%   |
| 4.4     | 2        | 0.32%   |
| 6.7     | 1        | 0.16%   |
| 6.4     | 1        | 0.16%   |
| 6.12    | 1        | 0.16%   |
| 6.11    | 1        | 0.16%   |
| 6.1     | 1        | 0.16%   |
| 5.2     | 1        | 0.16%   |
| 5.16    | 1        | 0.16%   |
| 5.14    | 1        | 0.16%   |
| 4.10    | 1        | 0.16%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 584      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| Pantheon | 561      | 94.92%  |
| Unknown  | 26       | 4.4%    |
| GNOME    | 3        | 0.51%   |
| MATE     | 1        | 0.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 582      | 99.66%  |
| Wayland | 1        | 0.17%   |
| Unknown | 1        | 0.17%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 501      | 84.2%   |
| LightDM | 76       | 12.77%  |
| TDM     | 16       | 2.69%   |
| SDDM    | 1        | 0.17%   |
| GDM     | 1        | 0.17%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 230      | 38.59%  |
| de_DE   | 66       | 11.07%  |
| es_ES   | 53       | 8.89%   |
| ru_RU   | 33       | 5.54%   |
| pt_BR   | 27       | 4.53%   |
| Unknown | 24       | 4.03%   |
| fr_FR   | 23       | 3.86%   |
| en_GB   | 21       | 3.52%   |
| it_IT   | 18       | 3.02%   |
| en_CA   | 14       | 2.35%   |
| pl_PL   | 11       | 1.85%   |
| pt_PT   | 7        | 1.17%   |
| hu_HU   | 7        | 1.17%   |
| tr_TR   | 6        | 1.01%   |
| en_AU   | 6        | 1.01%   |
| sv_SE   | 5        | 0.84%   |
| ja_JP   | 4        | 0.67%   |
| nl_NL   | 3        | 0.5%    |
| es_MX   | 3        | 0.5%    |
| de_CH   | 3        | 0.5%    |
| cs_CZ   | 3        | 0.5%    |
| zh_CN   | 2        | 0.34%   |
| fr_CA   | 2        | 0.34%   |
| fi_FI   | 2        | 0.34%   |
| en_IN   | 2        | 0.34%   |
| zh_TW   | 1        | 0.17%   |
| uk_UA   | 1        | 0.17%   |
| sr_RS   | 1        | 0.17%   |
| nb_NO   | 1        | 0.17%   |
| id_ID   | 1        | 0.17%   |
| hr_HR   | 1        | 0.17%   |
| gl_ES   | 1        | 0.17%   |
| fr_BE   | 1        | 0.17%   |
| es_VE   | 1        | 0.17%   |
| es_SV   | 1        | 0.17%   |
| es_PA   | 1        | 0.17%   |
| es_EC   | 1        | 0.17%   |
| en_ZA   | 1        | 0.17%   |
| en_PH   | 1        | 0.17%   |
| en_IE   | 1        | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 395      | 66.5%   |
| EFI  | 199      | 33.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 551      | 93.39%  |
| Btrfs    | 17       | 2.88%   |
| Xfs      | 7        | 1.19%   |
| Tmpfs    | 6        | 1.02%   |
| Unknown  | 6        | 1.02%   |
| Overlay  | 2        | 0.34%   |
| Reiserfs | 1        | 0.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 513      | 86.66%  |
| GPT     | 52       | 8.78%   |
| MBR     | 27       | 4.56%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 556      | 94.88%  |
| Yes       | 30       | 5.12%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 523      | 88.79%  |
| Yes       | 66       | 11.21%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 143      | 24.49%  |
| Gigabyte Technology | 97       | 16.61%  |
| MSI                 | 63       | 10.79%  |
| Hewlett-Packard     | 52       | 8.9%    |
| Dell                | 50       | 8.56%   |
| ASRock              | 44       | 7.53%   |
| Intel               | 21       | 3.6%    |
| Lenovo              | 19       | 3.25%   |
| Acer                | 13       | 2.23%   |
| Biostar             | 10       | 1.71%   |
| Foxconn             | 7        | 1.2%    |
| Apple               | 7        | 1.2%    |
| Unknown             | 7        | 1.2%    |
| Pegatron            | 6        | 1.03%   |
| Fujitsu             | 5        | 0.86%   |
| ECS                 | 5        | 0.86%   |
| MACHINIST           | 3        | 0.51%   |
| AZW                 | 3        | 0.51%   |
| Wibtek              | 2        | 0.34%   |
| Medion              | 2        | 0.34%   |
| Inventec            | 2        | 0.34%   |
| EVGA                | 2        | 0.34%   |
| AMI                 | 2        | 0.34%   |
| Wortmann AG         | 1        | 0.17%   |
| T-bao               | 1        | 0.17%   |
| SYS                 | 1        | 0.17%   |
| Shuttle             | 1        | 0.17%   |
| Packard Bell        | 1        | 0.17%   |
| LORD ELECTRONICS    | 1        | 0.17%   |
| LattePanda          | 1        | 0.17%   |
| Kraftway            | 1        | 0.17%   |
| Jetway              | 1        | 0.17%   |
| IceWhale Technology | 1        | 0.17%   |
| Huanan              | 1        | 0.17%   |
| HC Technology.      | 1        | 0.17%   |
| GEEKOM              | 1        | 0.17%   |
| Fujitsu Siemens     | 1        | 0.17%   |
| FIRICH              | 1        | 0.17%   |
| eMachines           | 1        | 0.17%   |
| BESSTAR Tech        | 1        | 0.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| ASUS All Series                   | 12       | 2.05%   |
| Unknown                           | 8        | 1.37%   |
| ASUS PRIME A320M-K                | 6        | 1.03%   |
| MSI MS-7C02                       | 4        | 0.68%   |
| MSI MS-7721                       | 4        | 0.68%   |
| HP ProDesk 600 G1 SFF             | 4        | 0.68%   |
| Dell OptiPlex 9020                | 4        | 0.68%   |
| Dell OptiPlex 790                 | 4        | 0.68%   |
| ASUS P8H61-M LX3 R2.0             | 4        | 0.68%   |
| MSI MS-7B84                       | 3        | 0.51%   |
| Intel Jasper Lake Client Platform | 3        | 0.51%   |
| Intel H61                         | 3        | 0.51%   |
| Gigabyte AB350-Gaming 3           | 3        | 0.51%   |
| ASUS ROG STRIX B350-F GAMING      | 3        | 0.51%   |
| ASUS PRIME H310M-E R2.0           | 3        | 0.51%   |
| Apple MacPro5,1                   | 3        | 0.51%   |
| Wibtek H61-M HDMI2                | 2        | 0.34%   |
| Pegatron IPMH61P1                 | 2        | 0.34%   |
| MSI MS-7C52                       | 2        | 0.34%   |
| MSI MS-7C35                       | 2        | 0.34%   |
| MSI MS-7B86                       | 2        | 0.34%   |
| MSI MS-7B17                       | 2        | 0.34%   |
| MSI MS-7A63                       | 2        | 0.34%   |
| MSI MS-7817                       | 2        | 0.34%   |
| Intel X79                         | 2        | 0.34%   |
| HP Compaq Pro 6300 MT             | 2        | 0.34%   |
| HP Compaq Elite 8300 SFF          | 2        | 0.34%   |
| Gigabyte Z390 UD                  | 2        | 0.34%   |
| Gigabyte H61M-S1                  | 2        | 0.34%   |
| Gigabyte H61M-DS2                 | 2        | 0.34%   |
| Gigabyte GA-990FXA-UD3            | 2        | 0.34%   |
| Gigabyte B550 AORUS ELITE         | 2        | 0.34%   |
| Gigabyte A320M-S2H V2             | 2        | 0.34%   |
| Gigabyte A320M-S2H                | 2        | 0.34%   |
| ECS H55H-M                        | 2        | 0.34%   |
| Dell Precision WorkStation T3500  | 2        | 0.34%   |
| Dell Precision Tower 5810         | 2        | 0.34%   |
| Dell OptiPlex 960                 | 2        | 0.34%   |
| Dell OptiPlex 9010                | 2        | 0.34%   |
| Dell OptiPlex 755                 | 2        | 0.34%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| Dell OptiPlex         | 31       | 5.31%   |
| ASUS PRIME            | 31       | 5.31%   |
| ASUS ROG              | 19       | 3.25%   |
| Lenovo ThinkCentre    | 17       | 2.91%   |
| HP Compaq             | 13       | 2.23%   |
| ASUS TUF              | 13       | 2.23%   |
| ASUS All              | 12       | 2.05%   |
| HP EliteDesk          | 8        | 1.37%   |
| Dell Precision        | 8        | 1.37%   |
| Acer Aspire           | 8        | 1.37%   |
| Unknown               | 8        | 1.37%   |
| HP ProDesk            | 6        | 1.03%   |
| ASUS P8H61-M          | 6        | 1.03%   |
| Gigabyte Z390         | 5        | 0.86%   |
| Fujitsu ESPRIMO       | 5        | 0.86%   |
| ASUS SABERTOOTH       | 5        | 0.86%   |
| MSI MS-7C02           | 4        | 0.68%   |
| MSI MS-7721           | 4        | 0.68%   |
| Gigabyte H310M        | 4        | 0.68%   |
| Gigabyte A320M-S2H    | 4        | 0.68%   |
| ASRock B450M          | 4        | 0.68%   |
| MSI MS-7B84           | 3        | 0.51%   |
| Intel Jasper          | 3        | 0.51%   |
| Intel H61             | 3        | 0.51%   |
| HP Pavilion           | 3        | 0.51%   |
| Gigabyte X570         | 3        | 0.51%   |
| Gigabyte B550         | 3        | 0.51%   |
| Gigabyte B450M        | 3        | 0.51%   |
| Gigabyte AB350-Gaming | 3        | 0.51%   |
| Dell Vostro           | 3        | 0.51%   |
| Dell Inspiron         | 3        | 0.51%   |
| ASUS M5A78L-M         | 3        | 0.51%   |
| Apple MacPro5         | 3        | 0.51%   |
| Acer Veriton          | 3        | 0.51%   |
| Wibtek H61-M          | 2        | 0.34%   |
| Pegatron IPMH61P1     | 2        | 0.34%   |
| MSI MS-7C52           | 2        | 0.34%   |
| MSI MS-7C35           | 2        | 0.34%   |
| MSI MS-7B86           | 2        | 0.34%   |
| MSI MS-7B17           | 2        | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 70       | 11.99%  |
| 2012 | 62       | 10.62%  |
| 2013 | 59       | 10.1%   |
| 2011 | 44       | 7.53%   |
| 2010 | 39       | 6.68%   |
| 2017 | 38       | 6.51%   |
| 2019 | 37       | 6.34%   |
| 2014 | 33       | 5.65%   |
| 2020 | 30       | 5.14%   |
| 2009 | 30       | 5.14%   |
| 2015 | 29       | 4.97%   |
| 2016 | 27       | 4.62%   |
| 2021 | 26       | 4.45%   |
| 2008 | 19       | 3.25%   |
| 2022 | 16       | 2.74%   |
| 2007 | 10       | 1.71%   |
| 2023 | 7        | 1.2%    |
| 2024 | 4        | 0.68%   |
| 2006 | 3        | 0.51%   |
| 2005 | 1        | 0.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 584      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 568      | 97.26%  |
| Enabled  | 16       | 2.74%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 584      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 144      | 24.41%  |
| 8.01-16.0   | 117      | 19.83%  |
| 4.01-8.0    | 110      | 18.64%  |
| 32.01-64.0  | 94       | 15.93%  |
| 3.01-4.0    | 76       | 12.88%  |
| 64.01-256.0 | 19       | 3.22%   |
| 24.01-32.0  | 12       | 2.03%   |
| 1.01-2.0    | 11       | 1.86%   |
| 2.01-3.0    | 7        | 1.19%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 215      | 32.82%  |
| 2.01-3.0   | 202      | 30.84%  |
| 4.01-8.0   | 107      | 16.34%  |
| 3.01-4.0   | 102      | 15.57%  |
| 8.01-16.0  | 16       | 2.44%   |
| 0.51-1.0   | 12       | 1.83%   |
| 32.01-64.0 | 1        | 0.15%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 226      | 37.42%  |
| 2      | 210      | 34.77%  |
| 3      | 88       | 14.57%  |
| 4      | 40       | 6.62%   |
| 5      | 20       | 3.31%   |
| 6      | 9        | 1.49%   |
| 7      | 6        | 0.99%   |
| 9      | 2        | 0.33%   |
| 0      | 2        | 0.33%   |
| 8      | 1        | 0.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 347      | 58.03%  |
| Yes       | 251      | 41.97%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 577      | 98.8%   |
| No        | 7        | 1.2%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 302      | 50.93%  |
| No        | 291      | 49.07%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 379      | 64.02%  |
| Yes       | 213      | 35.98%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 83       | 14.12%  |
| Germany     | 61       | 10.37%  |
| Brazil      | 42       | 7.14%   |
| Russia      | 35       | 5.95%   |
| Spain       | 28       | 4.76%   |
| UK          | 26       | 4.42%   |
| Canada      | 24       | 4.08%   |
| Italy       | 21       | 3.57%   |
| France      | 21       | 3.57%   |
| Mexico      | 15       | 2.55%   |
| Poland      | 14       | 2.38%   |
| Argentina   | 13       | 2.21%   |
| Indonesia   | 12       | 2.04%   |
| Netherlands | 11       | 1.87%   |
| India       | 10       | 1.7%    |
| Austria     | 10       | 1.7%    |
| Australia   | 10       | 1.7%    |
| Turkey      | 8        | 1.36%   |
| Sweden      | 7        | 1.19%   |
| Portugal    | 7        | 1.19%   |
| Hungary     | 7        | 1.19%   |
| Greece      | 7        | 1.19%   |
| Switzerland | 6        | 1.02%   |
| Czechia     | 6        | 1.02%   |
| Venezuela   | 5        | 0.85%   |
| Japan       | 5        | 0.85%   |
| Finland     | 5        | 0.85%   |
| Egypt       | 5        | 0.85%   |
| Ukraine     | 4        | 0.68%   |
| Malaysia    | 4        | 0.68%   |
| Colombia    | 4        | 0.68%   |
| Romania     | 3        | 0.51%   |
| Philippines | 3        | 0.51%   |
| Israel      | 3        | 0.51%   |
| Hong Kong   | 3        | 0.51%   |
| Chile       | 3        | 0.51%   |
| Bulgaria    | 3        | 0.51%   |
| Belgium     | 3        | 0.51%   |
| Vietnam     | 2        | 0.34%   |
| Thailand    | 2        | 0.34%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Moscow         | 11       | 1.76%   |
| Warsaw         | 7        | 1.12%   |
| Berlin         | 7        | 1.12%   |
| Vienna         | 5        | 0.8%    |
| Rio de Janeiro | 5        | 0.8%    |
| Paris          | 5        | 0.8%    |
| Munich         | 5        | 0.8%    |
| Sao Paulo      | 4        | 0.64%   |
| Melbourne      | 4        | 0.64%   |
| Madrid         | 4        | 0.64%   |
| Los Angeles    | 4        | 0.64%   |
| Fortaleza      | 4        | 0.64%   |
| Athens         | 4        | 0.64%   |
| Toronto        | 3        | 0.48%   |
| Sofia          | 3        | 0.48%   |
| Santiago       | 3        | 0.48%   |
| Novosibirsk    | 3        | 0.48%   |
| Montreal       | 3        | 0.48%   |
| Istanbul       | 3        | 0.48%   |
| Hamburg        | 3        | 0.48%   |
| Caslano        | 3        | 0.48%   |
| Brisbane       | 3        | 0.48%   |
| Amsterdam      | 3        | 0.48%   |
| Tucson         | 2        | 0.32%   |
| Tangerang      | 2        | 0.32%   |
| Tampere        | 2        | 0.32%   |
| Sydney         | 2        | 0.32%   |
| Stuttgart      | 2        | 0.32%   |
| St Petersburg  | 2        | 0.32%   |
| Spokane        | 2        | 0.32%   |
| Saskatoon      | 2        | 0.32%   |
| Sarajevo       | 2        | 0.32%   |
| Sao Vicente    | 2        | 0.32%   |
| Rome           | 2        | 0.32%   |
| Petah Tikva    | 2        | 0.32%   |
| Nuremberg      | 2        | 0.32%   |
| New York       | 2        | 0.32%   |
| Nairobi        | 2        | 0.32%   |
| Morwell        | 2        | 0.32%   |
| Morelia        | 2        | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 187      | 277    | 17.61%  |
| Seagate                     | 183      | 266    | 17.23%  |
| Samsung Electronics         | 130      | 225    | 12.24%  |
| Kingston                    | 78       | 110    | 7.34%   |
| Sandisk                     | 53       | 61     | 4.99%   |
| Toshiba                     | 52       | 80     | 4.9%    |
| Crucial                     | 46       | 61     | 4.33%   |
| Hitachi                     | 27       | 31     | 2.54%   |
| China                       | 20       | 29     | 1.88%   |
| A-DATA Technology           | 17       | 19     | 1.6%    |
| Intel                       | 15       | 19     | 1.41%   |
| Unknown                     | 14       | 32     | 1.32%   |
| Micron/Crucial Technology   | 14       | 21     | 1.32%   |
| PNY                         | 12       | 18     | 1.13%   |
| Micron Technology           | 11       | 12     | 1.04%   |
| HGST                        | 11       | 15     | 1.04%   |
| Transcend                   | 8        | 9      | 0.75%   |
| Team                        | 8        | 11     | 0.75%   |
| Silicon Motion              | 8        | 9      | 0.75%   |
| Phison                      | 7        | 8      | 0.66%   |
| Patriot                     | 7        | 8      | 0.66%   |
| OCZ                         | 7        | 12     | 0.66%   |
| Maxtor                      | 6        | 6      | 0.56%   |
| MAXIO Technology (Hangzhou) | 6        | 8      | 0.56%   |
| Intenso                     | 6        | 8      | 0.56%   |
| Corsair                     | 6        | 6      | 0.56%   |
| SPCC                        | 5        | 5      | 0.47%   |
| Realtek Semiconductor       | 5        | 6      | 0.47%   |
| Netac                       | 5        | 6      | 0.47%   |
| Unknown                     | 5        | 5      | 0.47%   |
| SK hynix                    | 4        | 4      | 0.38%   |
| LITEON                      | 4        | 4      | 0.38%   |
| KingFast                    | 4        | 4      | 0.38%   |
| JMicron Technology          | 4        | 4      | 0.38%   |
| HUSKY                       | 4        | 9      | 0.38%   |
| Gigabyte Technology         | 4        | 4      | 0.38%   |
| ADATA Technology            | 4        | 5      | 0.38%   |
| Plextor                     | 3        | 5      | 0.28%   |
| Kingston Technology Company | 3        | 3      | 0.28%   |
| HS-SSD-C100                 | 3        | 3      | 0.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD                       | 27       | 2.24%   |
| Seagate ST500DM002-1BD142 500GB                       | 16       | 1.33%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 14       | 1.16%   |
| Samsung SSD 850 EVO 250GB                             | 13       | 1.08%   |
| Samsung NVMe SSD Drive 500GB                          | 12       | 1%      |
| Seagate ST1000DM010-2EP102 1TB                        | 11       | 0.91%   |
| Kingston SA400S37120G 120GB SSD                       | 11       | 0.91%   |
| Toshiba DT01ACA100 1TB                                | 10       | 0.83%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB   | 10       | 0.83%   |
| Toshiba DT01ACA050 500GB                              | 9        | 0.75%   |
| Seagate ST1000DM003-1ER162 1TB                        | 9        | 0.75%   |
| Samsung SSD 860 EVO 1TB                               | 9        | 0.75%   |
| Crucial CT240BX500SSD1 240GB                          | 9        | 0.75%   |
| Samsung SSD 860 EVO 500GB                             | 8        | 0.66%   |
| Kingston SV300S37A120G 120GB SSD                      | 8        | 0.66%   |
| Samsung NVMe SSD Drive 1TB                            | 7        | 0.58%   |
| Kingston SA400S37480G 480GB SSD                       | 7        | 0.58%   |
| WDC WD10EZEX-60WN4A0 1TB                              | 6        | 0.5%    |
| Toshiba HDWD110 1TB                                   | 6        | 0.5%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 6        | 0.5%    |
| Seagate ST3500418AS 500GB                             | 6        | 0.5%    |
| Seagate ST31000528AS 1TB                              | 6        | 0.5%    |
| Seagate ST2000DM008-2FR102 2TB                        | 6        | 0.5%    |
| SanDisk NVMe SSD Drive 500GB                          | 6        | 0.5%    |
| Samsung SSD 860 EVO 250GB                             | 6        | 0.5%    |
| Samsung SSD 840 EVO 250GB                             | 6        | 0.5%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 5        | 0.41%   |
| WDC WD5000AAKX-00ERMA0 500GB                          | 5        | 0.41%   |
| WDC WD10EZEX-22MFCA0 1TB                              | 5        | 0.41%   |
| Unknown SD/MMC 1073GB                                 | 5        | 0.41%   |
| Unknown M.S./M.S.Pro/HG 16GB                          | 5        | 0.41%   |
| Unknown Compact Flash 977MB                           | 5        | 0.41%   |
| Seagate ST3500312CS 500GB                             | 5        | 0.41%   |
| Seagate ST1000DM003-1CH162 1TB                        | 5        | 0.41%   |
| Samsung SSD 870 QVO 1TB                               | 5        | 0.41%   |
| Samsung SSD 850 EVO 500GB                             | 5        | 0.41%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                 | 5        | 0.41%   |
| Crucial CT500MX500SSD1 500GB                          | 5        | 0.41%   |
| Unknown                                               | 5        | 0.41%   |
| WDC WD5000AAKX-60U6AA0 500GB                          | 4        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 180      | 257    | 37.82%  |
| WDC                 | 163      | 233    | 34.24%  |
| Toshiba             | 49       | 76     | 10.29%  |
| Samsung Electronics | 27       | 31     | 5.67%   |
| Hitachi             | 27       | 31     | 5.67%   |
| HGST                | 11       | 15     | 2.31%   |
| Maxtor              | 5        | 5      | 1.05%   |
| Unknown             | 3        | 4      | 0.63%   |
| JMicron Technology  | 2        | 2      | 0.42%   |
| Hewlett-Packard     | 2        | 2      | 0.42%   |
| ASMT                | 2        | 2      | 0.42%   |
| SABRENT             | 1        | 1      | 0.21%   |
| Fujitsu             | 1        | 1      | 0.21%   |
| FC-1307             | 1        | 1      | 0.21%   |
| Apple               | 1        | 1      | 0.21%   |
| Unknown             | 1        | 1      | 0.21%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 76       | 123    | 17.84%  |
| Kingston            | 71       | 89     | 16.67%  |
| Crucial             | 44       | 58     | 10.33%  |
| SanDisk             | 36       | 40     | 8.45%   |
| WDC                 | 25       | 36     | 5.87%   |
| China               | 20       | 29     | 4.69%   |
| A-DATA Technology   | 16       | 18     | 3.76%   |
| PNY                 | 12       | 18     | 2.82%   |
| Transcend           | 8        | 9      | 1.88%   |
| Team                | 8        | 11     | 1.88%   |
| Intel               | 8        | 11     | 1.88%   |
| Patriot             | 7        | 8      | 1.64%   |
| OCZ                 | 7        | 12     | 1.64%   |
| Intenso             | 6        | 8      | 1.41%   |
| Corsair             | 6        | 6      | 1.41%   |
| SPCC                | 5        | 5      | 1.17%   |
| Micron Technology   | 5        | 5      | 1.17%   |
| LITEON              | 4        | 4      | 0.94%   |
| HUSKY               | 4        | 9      | 0.94%   |
| Plextor             | 3        | 5      | 0.7%    |
| Netac               | 3        | 3      | 0.7%    |
| GOODRAM             | 3        | 6      | 0.7%    |
| Gigabyte Technology | 3        | 3      | 0.7%    |
| Unknown             | 3        | 3      | 0.7%    |
| Toshiba             | 2        | 2      | 0.47%   |
| SK hynix            | 2        | 2      | 0.47%   |
| Seagate             | 2        | 4      | 0.47%   |
| KingSpec            | 2        | 2      | 0.47%   |
| GeIL                | 2        | 2      | 0.47%   |
| Apacer              | 2        | 2      | 0.47%   |
| XrayDisk            | 1        | 2      | 0.23%   |
| WDC WDS             | 1        | 1      | 0.23%   |
| WALRAM              | 1        | 1      | 0.23%   |
| Verbatim            | 1        | 1      | 0.23%   |
| tigo                | 1        | 1      | 0.23%   |
| SD                  | 1        | 1      | 0.23%   |
| ROG                 | 1        | 1      | 0.23%   |
| OWC                 | 1        | 1      | 0.23%   |
| OCZ-VERTEX3         | 1        | 1      | 0.23%   |
| OCZ-VERTEX2         | 1        | 5      | 0.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 377      | 663    | 41.8%   |
| SSD     | 352      | 571    | 39.02%  |
| NVMe    | 136      | 213    | 15.08%  |
| Unknown | 34       | 59     | 3.77%   |
| MMC     | 3        | 3      | 0.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 542      | 1230   | 75.38%  |
| NVMe | 136      | 213    | 18.92%  |
| SAS  | 38       | 63     | 5.29%   |
| MMC  | 3        | 3      | 0.42%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 431      | 757    | 58.4%   |
| 0.51-1.0   | 197      | 317    | 26.69%  |
| 1.01-2.0   | 53       | 77     | 7.18%   |
| 2.01-3.0   | 24       | 42     | 3.25%   |
| 3.01-4.0   | 20       | 23     | 2.71%   |
| 4.01-10.0  | 12       | 17     | 1.63%   |
| 10.01-20.0 | 1        | 1      | 0.14%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 208      | 33.93%  |
| 251-500        | 139      | 22.68%  |
| 501-1000       | 103      | 16.8%   |
| 1001-2000      | 54       | 8.81%   |
| 51-100         | 36       | 5.87%   |
| More than 3000 | 27       | 4.4%    |
| 21-50          | 23       | 3.75%   |
| 2001-3000      | 19       | 3.1%    |
| 1-20           | 4        | 0.65%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 241      | 36.85%  |
| 21-50          | 140      | 21.41%  |
| 101-250        | 78       | 11.93%  |
| 51-100         | 78       | 11.93%  |
| 251-500        | 41       | 6.27%   |
| 501-1000       | 36       | 5.5%    |
| 1001-2000      | 26       | 3.98%   |
| More than 3000 | 8        | 1.22%   |
| 2001-3000      | 6        | 0.92%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WDS120G2G0A-00JH30 120GB SSD  | 1        | 1      | 3.45%   |
| WDC WD5000AAKX-22ERMA0 500GB      | 1        | 1      | 3.45%   |
| WDC WD5000AAKX-221CA1 500GB       | 1        | 1      | 3.45%   |
| WDC WD5000AAKX-00ERMA0 500GB      | 1        | 1      | 3.45%   |
| WDC WD5000AAKS-00UU3A0 500GB      | 1        | 1      | 3.45%   |
| WDC WD3200AAJS-56B4A0 320GB       | 1        | 1      | 3.45%   |
| WDC WD10EZEX-00KUWA0 1TB          | 1        | 1      | 3.45%   |
| WDC WD1003FZEX-00MK2A0 1TB        | 1        | 1      | 3.45%   |
| Seagate ST500DM002-1BD142 500GB   | 1        | 1      | 3.45%   |
| Seagate ST3500414CS 500GB         | 1        | 2      | 3.45%   |
| Seagate ST3500312CS 500GB         | 1        | 1      | 3.45%   |
| Seagate ST3320613AS 320GB         | 1        | 1      | 3.45%   |
| Seagate ST3250820AS 250GB         | 1        | 1      | 3.45%   |
| Seagate ST3250312AS 250GB         | 1        | 1      | 3.45%   |
| Seagate ST3160813AS 160GB         | 1        | 1      | 3.45%   |
| Seagate ST3160318AS 160GB         | 1        | 1      | 3.45%   |
| Seagate ST2000DM006-2DM164 2TB    | 1        | 1      | 3.45%   |
| SanDisk SSD PLUS 240GB            | 1        | 1      | 3.45%   |
| Samsung Electronics HD322GJ 320GB | 1        | 1      | 3.45%   |
| Samsung Electronics HD204UI 2TB   | 1        | 1      | 3.45%   |
| Samsung Electronics HD160JJ 160GB | 1        | 1      | 3.45%   |
| OCZ VECTOR150 240GB SSD           | 1        | 1      | 3.45%   |
| Kingston SA400S37120G 120GB SSD   | 1        | 1      | 3.45%   |
| Hitachi HTS725050A7E630 500GB     | 1        | 1      | 3.45%   |
| Hitachi HTS542525K9SA00 250GB     | 1        | 1      | 3.45%   |
| Hitachi HDT721064SLA360 640GB     | 1        | 1      | 3.45%   |
| Hitachi HDS721010CLA332 1TB       | 1        | 1      | 3.45%   |
| HGST HUS724030ALA640 3TB          | 1        | 1      | 3.45%   |
| Crucial CT256M550SSD1 256GB       | 1        | 1      | 3.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 9        | 10     | 31.03%  |
| WDC                 | 8        | 8      | 27.59%  |
| Hitachi             | 4        | 4      | 13.79%  |
| Samsung Electronics | 3        | 3      | 10.34%  |
| SanDisk             | 1        | 1      | 3.45%   |
| OCZ                 | 1        | 1      | 3.45%   |
| Kingston            | 1        | 1      | 3.45%   |
| HGST                | 1        | 1      | 3.45%   |
| Crucial             | 1        | 1      | 3.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 9        | 10     | 37.5%   |
| WDC                 | 7        | 7      | 29.17%  |
| Hitachi             | 4        | 4      | 16.67%  |
| Samsung Electronics | 3        | 3      | 12.5%   |
| HGST                | 1        | 1      | 4.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 21       | 25     | 80.77%  |
| SSD  | 5        | 5      | 19.23%  |

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
| Detected | 531      | 1353   | 86.34%  |
| Works    | 59       | 126    | 9.59%   |
| Malfunc  | 25       | 30     | 4.07%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 415      | 52.6%   |
| AMD                          | 149      | 18.88%  |
| Samsung Electronics          | 53       | 6.72%   |
| ASMedia Technology           | 23       | 2.92%   |
| SanDisk                      | 21       | 2.66%   |
| Micron/Crucial Technology    | 16       | 2.03%   |
| Nvidia                       | 15       | 1.9%    |
| JMicron Technology           | 14       | 1.77%   |
| Marvell Technology Group     | 13       | 1.65%   |
| Kingston Technology Company  | 11       | 1.39%   |
| Phison Electronics           | 9        | 1.14%   |
| Silicon Motion               | 8        | 1.01%   |
| MAXIO Technology (Hangzhou)  | 7        | 0.89%   |
| Realtek Semiconductor        | 6        | 0.76%   |
| Micron Technology            | 6        | 0.76%   |
| ADATA Technology             | 6        | 0.76%   |
| LSI Logic / Symbios Logic    | 3        | 0.38%   |
| VIA Technologies             | 2        | 0.25%   |
| Toshiba America Info Systems | 2        | 0.25%   |
| SK hynix                     | 2        | 0.25%   |
| Silicon Image                | 2        | 0.25%   |
| Seagate Technology           | 2        | 0.25%   |
| Shenzhen Longsys Electronics | 1        | 0.13%   |
| KIOXIA                       | 1        | 0.13%   |
| INNOGRIT                     | 1        | 0.13%   |
| Broadcom / LSI               | 1        | 0.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 90       | 9.11%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 51       | 5.16%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 50       | 5.06%   |
| AMD 400 Series Chipset SATA Controller                                                  | 36       | 3.64%   |
| Intel SATA Controller [RAID Mode]                                                       | 32       | 3.24%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 31       | 3.14%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 29       | 2.94%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 28       | 2.83%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 28       | 2.83%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 25       | 2.53%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 23       | 2.33%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 22       | 2.23%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 22       | 2.23%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 22       | 2.23%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 18       | 1.82%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 18       | 1.82%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 17       | 1.72%   |
| AMD 300 Series Chipset SATA Controller                                                  | 16       | 1.62%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 14       | 1.42%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 13       | 1.32%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 11       | 1.11%   |
| AMD 500 Series Chipset SATA Controller                                                  | 10       | 1.01%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 9        | 0.91%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 9        | 0.91%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 9        | 0.91%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 8        | 0.81%   |
| Nvidia MCP61 SATA Controller                                                            | 8        | 0.81%   |
| JMicron JMB368 IDE controller                                                           | 8        | 0.81%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 8        | 0.81%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 7        | 0.71%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 7        | 0.71%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 7        | 0.71%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 7        | 0.71%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 7        | 0.71%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 7        | 0.71%   |
| Kingston Company A2000 NVMe SSD [SM2263EN]                                              | 6        | 0.61%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 6        | 0.61%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                | 5        | 0.51%   |
| Intel SSD 660P Series                                                                   | 5        | 0.51%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 5        | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 457      | 58.89%  |
| NVMe | 137      | 17.65%  |
| IDE  | 131      | 16.88%  |
| RAID | 46       | 5.93%   |
| SAS  | 3        | 0.39%   |
| SCSI | 2        | 0.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 421      | 72.09%  |
| AMD    | 163      | 27.91%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-2400 CPU @ 3.10GHz            | 14       | 2.39%   |
| AMD Ryzen 5 3600 6-Core Processor           | 13       | 2.22%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 8        | 1.37%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 8        | 1.37%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 7        | 1.2%    |
| Intel Core i5-4570 CPU @ 3.20GHz            | 7        | 1.2%    |
| Intel Core i5-3470 CPU @ 3.20GHz            | 7        | 1.2%    |
| Intel Core i7-4790K CPU @ 4.00GHz           | 6        | 1.03%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 6        | 1.03%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 6        | 1.03%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 6        | 1.03%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 6        | 1.03%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 5        | 0.85%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 5        | 0.85%   |
| Intel Core i7-3770S CPU @ 3.10GHz           | 5        | 0.85%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 5        | 0.85%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 5        | 0.85%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 5        | 0.85%   |
| Intel Core i3 CPU 530 @ 2.93GHz             | 5        | 0.85%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 5        | 0.85%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 5        | 0.85%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 4        | 0.68%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 4        | 0.68%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 4        | 0.68%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 4        | 0.68%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 4        | 0.68%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 4        | 0.68%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 4        | 0.68%   |
| Intel Core i5-3330S CPU @ 2.70GHz           | 4        | 0.68%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 4        | 0.68%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 4        | 0.68%   |
| Intel Core i3-9100 CPU @ 3.60GHz            | 4        | 0.68%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 4        | 0.68%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 4        | 0.68%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 4        | 0.68%   |
| Intel Celeron N5105 @ 2.00GHz               | 4        | 0.68%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 4        | 0.68%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 4        | 0.68%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 4        | 0.68%   |
| AMD Phenom II X4 965 Processor              | 4        | 0.68%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 125      | 21.37%  |
| Intel Core i7           | 85       | 14.53%  |
| Intel Core i3           | 50       | 8.55%   |
| AMD Ryzen 5             | 44       | 7.52%   |
| Intel Xeon              | 41       | 7.01%   |
| Other                   | 24       | 4.1%    |
| Intel Celeron           | 23       | 3.93%   |
| AMD Ryzen 7             | 21       | 3.59%   |
| Intel Core 2 Duo        | 17       | 2.91%   |
| AMD FX                  | 17       | 2.91%   |
| Intel Core 2 Quad       | 15       | 2.56%   |
| AMD Ryzen 9             | 15       | 2.56%   |
| Intel Pentium           | 12       | 2.05%   |
| Intel Pentium Dual-Core | 11       | 1.88%   |
| AMD Ryzen 3             | 11       | 1.88%   |
| AMD Phenom II X4        | 10       | 1.71%   |
| AMD A8                  | 9        | 1.54%   |
| Intel Core i9           | 7        | 1.2%    |
| AMD Athlon II X4        | 4        | 0.68%   |
| AMD Athlon II X2        | 4        | 0.68%   |
| Intel Pentium Dual      | 3        | 0.51%   |
| Intel Atom              | 3        | 0.51%   |
| AMD Athlon              | 3        | 0.51%   |
| AMD A4                  | 3        | 0.51%   |
| AMD A10                 | 3        | 0.51%   |
| Intel Pentium Gold      | 2        | 0.34%   |
| Intel Pentium D         | 2        | 0.34%   |
| AMD Ryzen 5 PRO         | 2        | 0.34%   |
| AMD Phenom              | 2        | 0.34%   |
| AMD G                   | 2        | 0.34%   |
| AMD A6                  | 2        | 0.34%   |
| Intel Pentium Silver    | 1        | 0.17%   |
| Intel Pentium 4         | 1        | 0.17%   |
| Intel Core m3           | 1        | 0.17%   |
| Intel Core 2            | 1        | 0.17%   |
| AMD Sempron             | 1        | 0.17%   |
| AMD Ryzen Threadripper  | 1        | 0.17%   |
| AMD PRO A8              | 1        | 0.17%   |
| AMD PRO A10             | 1        | 0.17%   |
| AMD Phenom II X6        | 1        | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 274      | 46.68%  |
| 2      | 130      | 22.15%  |
| 6      | 77       | 13.12%  |
| 8      | 55       | 9.37%   |
| 12     | 17       | 2.9%    |
| 1      | 12       | 2.04%   |
| 3      | 8        | 1.36%   |
| 16     | 7        | 1.19%   |
| 10     | 4        | 0.68%   |
| 20     | 1        | 0.17%   |
| 18     | 1        | 0.17%   |
| 5      | 1        | 0.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 576      | 98.63%  |
| 2      | 8        | 1.37%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 314      | 53.49%  |
| 1      | 273      | 46.51%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 580      | 99.15%  |
| Unknown        | 5        | 0.85%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 227      | 37.9%   |
| 0x206a7    | 44       | 7.35%   |
| 0x306c3    | 43       | 7.18%   |
| 0x306a9    | 30       | 5.01%   |
| 0x08701021 | 18       | 3.01%   |
| 0x1067a    | 14       | 2.34%   |
| 0x906ea    | 13       | 2.17%   |
| 0x906e9    | 12       | 2%      |
| 0x506e3    | 11       | 1.84%   |
| 0x0800820d | 10       | 1.67%   |
| 0x906ed    | 9        | 1.5%    |
| 0x08108109 | 9        | 1.5%    |
| 0x906eb    | 8        | 1.34%   |
| 0x06000852 | 8        | 1.34%   |
| 0x010000c8 | 8        | 1.34%   |
| 0x6fb      | 7        | 1.17%   |
| 0x106e5    | 6        | 1%      |
| 0x206d7    | 5        | 0.83%   |
| 0x20652    | 5        | 0.83%   |
| 0x10676    | 5        | 0.83%   |
| 0x0a201016 | 5        | 0.83%   |
| 0x08701013 | 5        | 0.83%   |
| 0x06003106 | 5        | 0.83%   |
| 0xa0671    | 4        | 0.67%   |
| 0xa0655    | 4        | 0.67%   |
| 0x106a5    | 4        | 0.67%   |
| 0x08001138 | 4        | 0.67%   |
| 0x06001119 | 4        | 0.67%   |
| 0x0600063e | 4        | 0.67%   |
| 0x010000db | 4        | 0.67%   |
| 0xa0653    | 3        | 0.5%    |
| 0x306e4    | 3        | 0.5%    |
| 0x206c2    | 3        | 0.5%    |
| 0x20655    | 3        | 0.5%    |
| 0x0810100b | 3        | 0.5%    |
| 0x0600611a | 3        | 0.5%    |
| 0x906ec    | 2        | 0.33%   |
| 0x906c0    | 2        | 0.33%   |
| 0x6fd      | 2        | 0.33%   |
| 0x406c4    | 2        | 0.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 74       | 12.67%  |
| KabyLake         | 71       | 12.16%  |
| SandyBridge      | 65       | 11.13%  |
| IvyBridge        | 51       | 8.73%   |
| Penryn           | 31       | 5.31%   |
| Zen 2            | 28       | 4.79%   |
| Zen+             | 27       | 4.62%   |
| Skylake          | 24       | 4.11%   |
| K10              | 23       | 3.94%   |
| Unknown          | 22       | 3.77%   |
| Zen              | 20       | 3.42%   |
| Zen 3            | 19       | 3.25%   |
| Core             | 19       | 3.25%   |
| Piledriver       | 17       | 2.91%   |
| Nehalem          | 15       | 2.57%   |
| Westmere         | 14       | 2.4%    |
| CometLake        | 13       | 2.23%   |
| Steamroller      | 9        | 1.54%   |
| Excavator        | 7        | 1.2%    |
| Icelake          | 5        | 0.86%   |
| Bulldozer        | 5        | 0.86%   |
| Silvermont       | 4        | 0.68%   |
| Goldmont plus    | 4        | 0.68%   |
| NetBurst         | 3        | 0.51%   |
| Tremont          | 2        | 0.34%   |
| Broadwell        | 2        | 0.34%   |
| Bobcat           | 2        | 0.34%   |
| Alderlake Hybrid | 2        | 0.34%   |
| TigerLake        | 1        | 0.17%   |
| Puma             | 1        | 0.17%   |
| K8 Hammer        | 1        | 0.17%   |
| K10 Llano        | 1        | 0.17%   |
| Goldmont         | 1        | 0.17%   |
| Bonnell          | 1        | 0.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Nvidia           | 237      | 37.21%  |
| Intel            | 207      | 32.5%   |
| AMD              | 191      | 29.98%  |
| Conexant Systems | 1        | 0.16%   |
| ATI Technologies | 1        | 0.16%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 35       | 5.33%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 33       | 5.02%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 31       | 4.72%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 21       | 3.2%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 14       | 2.13%   |
| Intel HD Graphics 530                                                       | 13       | 1.98%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 13       | 1.98%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 10       | 1.52%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 9        | 1.37%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 9        | 1.37%   |
| Nvidia GK208B [GeForce GT 710]                                              | 9        | 1.37%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 9        | 1.37%   |
| Nvidia GT218 [GeForce 210]                                                  | 8        | 1.22%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 8        | 1.22%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 8        | 1.22%   |
| Intel HD Graphics 630                                                       | 8        | 1.22%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 8        | 1.22%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 8        | 1.22%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 8        | 1.22%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 7        | 1.07%   |
| Nvidia GK208B [GeForce GT 730]                                              | 7        | 1.07%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 7        | 1.07%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 7        | 1.07%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 7        | 1.07%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 6        | 0.91%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 6        | 0.91%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 6        | 0.91%   |
| Nvidia GF119 [GeForce GT 610]                                               | 6        | 0.91%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 6        | 0.91%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 5        | 0.76%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 5        | 0.76%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 5        | 0.76%   |
| Intel JasperLake [UHD Graphics]                                             | 5        | 0.76%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 5        | 0.76%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 5        | 0.76%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 5        | 0.76%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 4        | 0.61%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 4        | 0.61%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 4        | 0.61%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 4        | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| 1 x Nvidia                     | 214      | 36.21%  |
| 1 x AMD                        | 171      | 28.93%  |
| 1 x Intel                      | 168      | 28.43%  |
| Intel + Nvidia                 | 13       | 2.2%    |
| 2 x AMD                        | 8        | 1.35%   |
| Intel + AMD                    | 5        | 0.85%   |
| AMD + Nvidia                   | 5        | 0.85%   |
| 2 x Nvidia                     | 4        | 0.68%   |
| Intel + 2 x AMD                | 2        | 0.34%   |
| 2 x AMD + 1 x Conexant Systems | 1        | 0.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 460      | 77.97%  |
| Proprietary | 114      | 19.32%  |
| Unknown     | 16       | 2.71%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 300      | 50%     |
| 1.01-2.0   | 78       | 13%     |
| 0.51-1.0   | 57       | 9.5%    |
| 3.01-4.0   | 51       | 8.5%    |
| 7.01-8.0   | 43       | 7.17%   |
| 0.01-0.5   | 33       | 5.5%    |
| 5.01-6.0   | 19       | 3.17%   |
| 8.01-16.0  | 12       | 2%      |
| 2.01-3.0   | 6        | 1%      |
| 16.01-24.0 | 1        | 0.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 94       | 15.28%  |
| Goldstar             | 74       | 12.03%  |
| Dell                 | 58       | 9.43%   |
| Hewlett-Packard      | 52       | 8.46%   |
| Acer                 | 48       | 7.8%    |
| AOC                  | 39       | 6.34%   |
| Philips              | 28       | 4.55%   |
| BenQ                 | 23       | 3.74%   |
| Ancor Communications | 23       | 3.74%   |
| LG Electronics       | 16       | 2.6%    |
| Lenovo               | 14       | 2.28%   |
| ViewSonic            | 12       | 1.95%   |
| Vizio                | 9        | 1.46%   |
| Unknown              | 8        | 1.3%    |
| NEC Computers        | 6        | 0.98%   |
| Fujitsu Siemens      | 6        | 0.98%   |
| Sony                 | 5        | 0.81%   |
| ASUSTek Computer     | 5        | 0.81%   |
| Sharp                | 4        | 0.65%   |
| Iiyama               | 4        | 0.65%   |
| HKC                  | 4        | 0.65%   |
| ___                  | 3        | 0.49%   |
| Sceptre Tech         | 3        | 0.49%   |
| MSI                  | 3        | 0.49%   |
| HPN                  | 3        | 0.49%   |
| HannStar             | 3        | 0.49%   |
| Eizo                 | 3        | 0.49%   |
| Denver               | 3        | 0.49%   |
| AUS                  | 3        | 0.49%   |
| Apple                | 3        | 0.49%   |
| Vestel               | 2        | 0.33%   |
| SAC                  | 2        | 0.33%   |
| Panasonic            | 2        | 0.33%   |
| Mi                   | 2        | 0.33%   |
| Hitachi              | 2        | 0.33%   |
| Grundig              | 2        | 0.33%   |
| CVT                  | 2        | 0.33%   |
| CHR                  | 2        | 0.33%   |
| Unknown              | 2        | 0.33%   |
| Vestel Elektronik    | 1        | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 5        | 0.76%   |
| AOC Q27G2WG4 AOC2702 2560x1440 597x336mm 27.0-inch                    | 5        | 0.76%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch     | 4        | 0.61%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 4        | 0.61%   |
| Goldstar 20EN33 GSM4EE1 1600x900 443x249mm 20.0-inch                  | 4        | 0.61%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch  | 3        | 0.46%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 3        | 0.46%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                   | 3        | 0.46%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 3        | 0.46%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 3        | 0.46%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                      | 3        | 0.46%   |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                       | 3        | 0.46%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 3        | 0.46%   |
| Vizio E421VO VIZ0070 1920x1080 930x523mm 42.0-inch                    | 2        | 0.31%   |
| Vizio E320i-A0 VIZ1002 1366x768 698x392mm 31.5-inch                   | 2        | 0.31%   |
| ViewSonic VA2719 Series VSCC132 1920x1080 598x336mm 27.0-inch         | 2        | 0.31%   |
| ViewSonic VA1931 Series VSCAC25 1366x768 410x230mm 18.5-inch          | 2        | 0.31%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 2        | 0.31%   |
| Sharp HDMI SHP1048 1920x1080 820x460mm 37.0-inch                      | 2        | 0.31%   |
| Samsung Electronics SyncMaster SAM0423 1920x1080                      | 2        | 0.31%   |
| Samsung Electronics SA300/SA350 SAM078B 1600x900 443x249mm 20.0-inch  | 2        | 0.31%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 700x390mm 31.5-inch  | 2        | 0.31%   |
| Samsung Electronics LCD Monitor C32F391 1920x1080                     | 2        | 0.31%   |
| Philips LCD Monitor PHL 276E8V 3840x2160                              | 2        | 0.31%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                       | 2        | 0.31%   |
| Lenovo LI2215sD LEN65CC 1920x1080 476x267mm 21.5-inch                 | 2        | 0.31%   |
| Lenovo LEN LT2252pwA LEN0A0C 1680x1050 474x296mm 22.0-inch            | 2        | 0.31%   |
| HKC 22N1 HKCB215 1920x1080 476x268mm 21.5-inch                        | 2        | 0.31%   |
| Hewlett-Packard w2207 HWP26A9 1680x1050 473x296mm 22.0-inch           | 2        | 0.31%   |
| Hewlett-Packard HPQ 8300 AiO HWP4211 1920x1080 510x287mm 23.0-inch    | 2        | 0.31%   |
| Hewlett-Packard 27fw HPN354C 1920x1080 598x336mm 27.0-inch            | 2        | 0.31%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch             | 2        | 0.31%   |
| Grundig WXGA GRU4448 1600x1200                                        | 2        | 0.31%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch              | 2        | 0.31%   |
| Goldstar ULTRAGEAR GSM7766 2560x1440 697x392mm 31.5-inch              | 2        | 0.31%   |
| Goldstar L1753T GSM4434 1280x1024 338x270mm 17.0-inch                 | 2        | 0.31%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                | 2        | 0.31%   |
| Goldstar E2211 GSM5838 1920x1080 477x268mm 21.5-inch                  | 2        | 0.31%   |
| Goldstar 2D HD TV GSM59C8 1366x768 509x286mm 23.0-inch                | 2        | 0.31%   |
| Goldstar 25UM58G GSM5B98 2560x1080 673x284mm 28.8-inch                | 2        | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 277      | 45.86%  |
| 3840x2160 (4K)     | 52       | 8.61%   |
| 2560x1440 (QHD)    | 42       | 6.95%   |
| 1680x1050 (WSXGA+) | 39       | 6.46%   |
| 1366x768 (WXGA)    | 30       | 4.97%   |
| 1280x1024 (SXGA)   | 29       | 4.8%    |
| 1600x900 (HD+)     | 25       | 4.14%   |
| Unknown            | 15       | 2.48%   |
| 1440x900 (WXGA+)   | 13       | 2.15%   |
| 2560x1080          | 12       | 1.99%   |
| 1920x1200 (WUXGA)  | 12       | 1.99%   |
| 1360x768           | 11       | 1.82%   |
| 3440x1440          | 10       | 1.66%   |
| 3840x1080          | 9        | 1.49%   |
| 5120x1440          | 3        | 0.5%    |
| 2560x1600          | 3        | 0.5%    |
| 1600x1200          | 3        | 0.5%    |
| 3840x1200          | 2        | 0.33%   |
| 2288x1287          | 2        | 0.33%   |
| 2048x1152          | 2        | 0.33%   |
| 1280x720 (HD)      | 2        | 0.33%   |
| 7680x2160          | 1        | 0.17%   |
| 7680x1600          | 1        | 0.17%   |
| 5760x2160          | 1        | 0.17%   |
| 5760x1080          | 1        | 0.17%   |
| 4480x1440          | 1        | 0.17%   |
| 3968x1280          | 1        | 0.17%   |
| 3840x1600          | 1        | 0.17%   |
| 3600x1080          | 1        | 0.17%   |
| 2048x1536          | 1        | 0.17%   |
| 1920x540           | 1        | 0.17%   |
| 1024x768 (XGA)     | 1        | 0.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 86       | 14.03%  |
| 27      | 74       | 12.07%  |
| 24      | 67       | 10.93%  |
| 23      | 62       | 10.11%  |
| 21      | 58       | 9.46%   |
| 19      | 31       | 5.06%   |
| 22      | 30       | 4.89%   |
| 31      | 29       | 4.73%   |
| 18      | 23       | 3.75%   |
| 20      | 21       | 3.43%   |
| 34      | 17       | 2.77%   |
| 17      | 17       | 2.77%   |
| 32      | 13       | 2.12%   |
| 54      | 8        | 1.31%   |
| 84      | 7        | 1.14%   |
| 72      | 7        | 1.14%   |
| 15      | 7        | 1.14%   |
| 40      | 6        | 0.98%   |
| 36      | 5        | 0.82%   |
| 26      | 5        | 0.82%   |
| 49      | 4        | 0.65%   |
| 42      | 4        | 0.65%   |
| 29      | 4        | 0.65%   |
| 48      | 3        | 0.49%   |
| 64      | 2        | 0.33%   |
| 60      | 2        | 0.33%   |
| 55      | 2        | 0.33%   |
| 43      | 2        | 0.33%   |
| 39      | 2        | 0.33%   |
| 38      | 2        | 0.33%   |
| 33      | 2        | 0.33%   |
| 28      | 2        | 0.33%   |
| 25      | 2        | 0.33%   |
| 142     | 1        | 0.16%   |
| 65      | 1        | 0.16%   |
| 57      | 1        | 0.16%   |
| 46      | 1        | 0.16%   |
| 37      | 1        | 0.16%   |
| 35      | 1        | 0.16%   |
| 14      | 1        | 0.16%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 191      | 32.1%   |
| 401-500        | 148      | 24.87%  |
| Unknown        | 86       | 14.45%  |
| 601-700        | 41       | 6.89%   |
| 701-800        | 36       | 6.05%   |
| 1001-1500      | 24       | 4.03%   |
| 301-350        | 22       | 3.7%    |
| 351-400        | 14       | 2.35%   |
| 1501-2000      | 14       | 2.35%   |
| 801-900        | 12       | 2.02%   |
| 901-1000       | 5        | 0.84%   |
| More than 2000 | 1        | 0.17%   |
| 201-300        | 1        | 0.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 360      | 63.72%  |
| Unknown | 78       | 13.81%  |
| 16/10   | 64       | 11.33%  |
| 5/4     | 25       | 4.42%   |
| 21/9    | 21       | 3.72%   |
| 4/3     | 5        | 0.88%   |
| 32/9    | 4        | 0.71%   |
| 3/2     | 4        | 0.71%   |
| 6/5     | 2        | 0.35%   |
| 3.20    | 1        | 0.18%   |
| 1.00    | 1        | 0.18%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 173      | 28.74%  |
| Unknown        | 86       | 14.29%  |
| 301-350        | 76       | 12.62%  |
| 151-200        | 67       | 11.13%  |
| 351-500        | 65       | 10.8%   |
| 141-150        | 36       | 5.98%   |
| More than 1000 | 33       | 5.48%   |
| 251-300        | 29       | 4.82%   |
| 501-1000       | 27       | 4.49%   |
| 101-110        | 6        | 1%      |
| 131-140        | 2        | 0.33%   |
| 111-120        | 1        | 0.17%   |
| 91-100         | 1        | 0.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 336      | 58.54%  |
| 101-120 | 98       | 17.07%  |
| Unknown | 86       | 14.98%  |
| 1-50    | 33       | 5.75%   |
| 121-160 | 17       | 2.96%   |
| 161-240 | 4        | 0.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 480      | 80.67%  |
| 2     | 89       | 14.96%  |
| 0     | 14       | 2.35%   |
| 3     | 12       | 2.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 374      | 43.04%  |
| Intel                             | 230      | 26.47%  |
| Qualcomm Atheros                  | 43       | 4.95%   |
| Broadcom                          | 37       | 4.26%   |
| TP-Link                           | 34       | 3.91%   |
| Ralink Technology                 | 25       | 2.88%   |
| Nvidia                            | 12       | 1.38%   |
| Samsung Electronics               | 11       | 1.27%   |
| Xiaomi                            | 10       | 1.15%   |
| Ralink                            | 9        | 1.04%   |
| Marvell Technology Group          | 9        | 1.04%   |
| MediaTek                          | 8        | 0.92%   |
| Qualcomm Atheros Communications   | 6        | 0.69%   |
| Broadcom Limited                  | 6        | 0.69%   |
| D-Link System                     | 5        | 0.58%   |
| Microsoft                         | 4        | 0.46%   |
| Linksys                           | 4        | 0.46%   |
| NetGear                           | 3        | 0.35%   |
| Huawei Technologies               | 3        | 0.35%   |
| ASUSTek Computer                  | 3        | 0.35%   |
| OPPO Electronics                  | 2        | 0.23%   |
| Mercucys                          | 2        | 0.23%   |
| Edimax Technology                 | 2        | 0.23%   |
| D-Link                            | 2        | 0.23%   |
| Belkin Components                 | 2        | 0.23%   |
| ASIX Electronics                  | 2        | 0.23%   |
| Aquantia                          | 2        | 0.23%   |
| ZyXEL Communications              | 1        | 0.12%   |
| vivo                              | 1        | 0.12%   |
| VIA Technologies                  | 1        | 0.12%   |
| TRENDnet                          | 1        | 0.12%   |
| Sundance Technology Inc / IC Plus | 1        | 0.12%   |
| Qualcomm                          | 1        | 0.12%   |
| Oculus VR                         | 1        | 0.12%   |
| Motorola PCS                      | 1        | 0.12%   |
| LG Electronics                    | 1        | 0.12%   |
| Input Club                        | 1        | 0.12%   |
| ICS Advent                        | 1        | 0.12%   |
| Google                            | 1        | 0.12%   |
| Exar                              | 1        | 0.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 291      | 29.51%  |
| Intel I211 Gigabit Network Connection                                  | 27       | 2.74%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 27       | 2.74%   |
| Realtek RTL8125 2.5GbE Controller                                      | 24       | 2.43%   |
| Intel Ethernet Connection (2) I219-V                                   | 21       | 2.13%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 18       | 1.83%   |
| Intel Ethernet Connection (7) I219-V                                   | 18       | 1.83%   |
| Intel Wi-Fi 6 AX200                                                    | 17       | 1.72%   |
| Intel Ethernet Connection I217-LM                                      | 17       | 1.72%   |
| Ralink MT7601U Wireless Adapter                                        | 16       | 1.62%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 15       | 1.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 14       | 1.42%   |
| Realtek 802.11ac NIC                                                   | 13       | 1.32%   |
| Intel Ethernet Controller I225-V                                       | 13       | 1.32%   |
| Intel 82579V Gigabit Network Connection                                | 12       | 1.22%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 9        | 0.91%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 9        | 0.91%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 9        | 0.91%   |
| Intel 82574L Gigabit Network Connection                                | 9        | 0.91%   |
| Intel Ethernet Connection I217-V                                       | 8        | 0.81%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 8        | 0.81%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 7        | 0.71%   |
| Nvidia MCP61 Ethernet                                                  | 7        | 0.71%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 7        | 0.71%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                    | 6        | 0.61%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 6        | 0.61%   |
| Qualcomm Atheros AR9271 802.11n                                        | 6        | 0.61%   |
| Intel Wireless 3165                                                    | 6        | 0.61%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 6        | 0.61%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 5        | 0.51%   |
| TP-Link 802.11ac NIC                                                   | 5        | 0.51%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 5        | 0.51%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 5        | 0.51%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 5        | 0.51%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 5        | 0.51%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 5        | 0.51%   |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 5        | 0.51%   |
| Broadcom BCM43228 802.11a/b/g/n                                        | 5        | 0.51%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 4        | 0.41%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                             | 4        | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 91       | 27.58%  |
| Intel                           | 77       | 23.33%  |
| TP-Link                         | 33       | 10%     |
| Ralink Technology               | 25       | 7.58%   |
| Broadcom                        | 22       | 6.67%   |
| Qualcomm Atheros                | 20       | 6.06%   |
| Ralink                          | 9        | 2.73%   |
| Qualcomm Atheros Communications | 6        | 1.82%   |
| MediaTek                        | 5        | 1.52%   |
| Broadcom Limited                | 5        | 1.52%   |
| Microsoft                       | 4        | 1.21%   |
| Linksys                         | 4        | 1.21%   |
| D-Link System                   | 4        | 1.21%   |
| NetGear                         | 3        | 0.91%   |
| Marvell Technology Group        | 3        | 0.91%   |
| ASUSTek Computer                | 3        | 0.91%   |
| Mercucys                        | 2        | 0.61%   |
| Edimax Technology               | 2        | 0.61%   |
| D-Link                          | 2        | 0.61%   |
| Belkin Components               | 2        | 0.61%   |
| ZyXEL Communications            | 1        | 0.3%    |
| TRENDnet                        | 1        | 0.3%    |
| LG Electronics                  | 1        | 0.3%    |
| BUFFALO                         | 1        | 0.3%    |
| AVM                             | 1        | 0.3%    |
| AirTies Wireless Networks       | 1        | 0.3%    |
| Accton Technology               | 1        | 0.3%    |
| AboCom Systems                  | 1        | 0.3%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                          | 17       | 5.07%   |
| Ralink MT7601U Wireless Adapter                              | 16       | 4.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter     | 15       | 4.48%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter          | 14       | 4.18%   |
| Realtek 802.11ac NIC                                         | 13       | 3.88%   |
| Realtek RTL88x2bu [AC1200 Techkey]                           | 9        | 2.69%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]    | 9        | 2.69%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter | 8        | 2.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter             | 7        | 2.09%   |
| Intel Cannon Lake PCH CNVi WiFi                              | 7        | 2.09%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                          | 6        | 1.79%   |
| Qualcomm Atheros AR9271 802.11n                              | 6        | 1.79%   |
| Intel Wireless 3165                                          | 6        | 1.79%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]   | 5        | 1.49%   |
| TP-Link 802.11ac NIC                                         | 5        | 1.49%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter        | 5        | 1.49%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]      | 5        | 1.49%   |
| Intel Alder Lake-S PCH CNVi WiFi                             | 5        | 1.49%   |
| Broadcom BCM43228 802.11a/b/g/n                              | 5        | 1.49%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                  | 4        | 1.19%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                   | 4        | 1.19%   |
| Intel Wireless 7265                                          | 4        | 1.19%   |
| Intel Wireless 7260                                          | 4        | 1.19%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]             | 4        | 1.19%   |
| Intel Comet Lake PCH CNVi WiFi                               | 4        | 1.19%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter | 4        | 1.19%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                 | 3        | 0.9%    |
| TP-Link Archer T4U ver.3                                     | 3        | 0.9%    |
| TP-Link 802.11ac WLAN Adapter                                | 3        | 0.9%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter     | 3        | 0.9%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter              | 3        | 0.9%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                      | 3        | 0.9%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                   | 3        | 0.9%    |
| Realtek RTL8187 Wireless Adapter                             | 3        | 0.9%    |
| Microsoft Xbox 360 Wireless Adapter                          | 3        | 0.9%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                      | 3        | 0.9%    |
| Intel Wireless 8260                                          | 3        | 0.9%    |
| Broadcom Limited BCM4321 802.11a/b/g/n                       | 3        | 0.9%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter     | 2        | 0.6%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter      | 2        | 0.6%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 341      | 54.13%  |
| Intel                             | 193      | 30.63%  |
| Qualcomm Atheros                  | 25       | 3.97%   |
| Broadcom                          | 16       | 2.54%   |
| Nvidia                            | 12       | 1.9%    |
| Xiaomi                            | 10       | 1.59%   |
| Marvell Technology Group          | 6        | 0.95%   |
| Samsung Electronics               | 5        | 0.79%   |
| MediaTek                          | 3        | 0.48%   |
| Huawei Technologies               | 3        | 0.48%   |
| OPPO Electronics                  | 2        | 0.32%   |
| ASIX Electronics                  | 2        | 0.32%   |
| Aquantia                          | 2        | 0.32%   |
| vivo                              | 1        | 0.16%   |
| VIA Technologies                  | 1        | 0.16%   |
| TP-Link                           | 1        | 0.16%   |
| Sundance Technology Inc / IC Plus | 1        | 0.16%   |
| Qualcomm                          | 1        | 0.16%   |
| Motorola PCS                      | 1        | 0.16%   |
| ICS Advent                        | 1        | 0.16%   |
| Google                            | 1        | 0.16%   |
| D-Link System                     | 1        | 0.16%   |
| Broadcom Limited                  | 1        | 0.16%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 291      | 45.4%   |
| Intel I211 Gigabit Network Connection                                  | 27       | 4.21%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 27       | 4.21%   |
| Realtek RTL8125 2.5GbE Controller                                      | 24       | 3.74%   |
| Intel Ethernet Connection (2) I219-V                                   | 21       | 3.28%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 18       | 2.81%   |
| Intel Ethernet Connection (7) I219-V                                   | 18       | 2.81%   |
| Intel Ethernet Connection I217-LM                                      | 17       | 2.65%   |
| Intel Ethernet Controller I225-V                                       | 13       | 2.03%   |
| Intel 82579V Gigabit Network Connection                                | 12       | 1.87%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 9        | 1.4%    |
| Intel 82574L Gigabit Network Connection                                | 9        | 1.4%    |
| Intel Ethernet Connection I217-V                                       | 8        | 1.25%   |
| Nvidia MCP61 Ethernet                                                  | 7        | 1.09%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 6        | 0.94%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 5        | 0.78%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 5        | 0.78%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 5        | 0.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 4        | 0.62%   |
| Intel Ethernet Connection (2) I219-LM                                  | 4        | 0.62%   |
| Intel Ethernet Connection (2) I218-V                                   | 4        | 0.62%   |
| Intel 82578DM Gigabit Network Connection                               | 4        | 0.62%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 3        | 0.47%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 3        | 0.47%   |
| Nvidia MCP77 Ethernet                                                  | 3        | 0.47%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                | 3        | 0.47%   |
| Intel Ethernet Connection (7) I219-LM                                  | 3        | 0.47%   |
| Intel Ethernet Connection (14) I219-V                                  | 3        | 0.47%   |
| Intel 82578DC Gigabit Network Connection                               | 3        | 0.47%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 3        | 0.47%   |
| Huawei FOA-LX9                                                         | 3        | 0.47%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 3        | 0.47%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                       | 3        | 0.47%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 2        | 0.31%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2        | 0.31%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 2        | 0.31%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 2        | 0.31%   |
| OPPO OnePlus Nord 4                                                    | 2        | 0.31%   |
| Nvidia MCP55 Ethernet                                                  | 2        | 0.31%   |
| MediaTek Infinix SMART 5                                               | 2        | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 578      | 64.87%  |
| WiFi     | 304      | 34.12%  |
| Modem    | 8        | 0.9%    |
| Unknown  | 1        | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 423      | 70.85%  |
| WiFi     | 173      | 28.98%  |
| Modem    | 1        | 0.17%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 381      | 64.8%   |
| 2     | 173      | 29.42%  |
| 3     | 26       | 4.42%   |
| 0     | 6        | 1.02%   |
| 4     | 2        | 0.34%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 433      | 73.14%  |
| Yes  | 159      | 26.86%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 74       | 33.94%  |
| Cambridge Silicon Radio         | 60       | 27.52%  |
| Realtek Semiconductor           | 26       | 11.93%  |
| Broadcom                        | 12       | 5.5%    |
| ASUSTek Computer                | 12       | 5.5%    |
| Apple                           | 9        | 4.13%   |
| IMC Networks                    | 5        | 2.29%   |
| Qualcomm Atheros Communications | 4        | 1.83%   |
| TP-Link                         | 3        | 1.38%   |
| MediaTek                        | 3        | 1.38%   |
| Belkin Components               | 2        | 0.92%   |
| Unknown                         | 2        | 0.92%   |
| Ralink                          | 1        | 0.46%   |
| Qcom                            | 1        | 0.46%   |
| Foxconn / Hon Hai               | 1        | 0.46%   |
| Edimax Technology               | 1        | 0.46%   |
| Actions                         | 1        | 0.46%   |
| 3Com                            | 1        | 0.46%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 60       | 27.52%  |
| Realtek Bluetooth Radio                               | 22       | 10.09%  |
| Intel Bluetooth wireless interface                    | 20       | 9.17%   |
| Intel AX200 Bluetooth                                 | 16       | 7.34%   |
| Intel AX210 Bluetooth                                 | 10       | 4.59%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 9        | 4.13%   |
| Intel AX201 Bluetooth                                 | 8        | 3.67%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 6        | 2.75%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 4        | 1.83%   |
| Intel Wireless-AC 3168 Bluetooth                      | 4        | 1.83%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                  | 4        | 1.83%   |
| TP-Link TP-Link Bluetooth USB Adapter                 | 3        | 1.38%   |
| Realtek  Bluetooth 4.2 Adapter                        | 3        | 1.38%   |
| MediaTek Wireless_Device                              | 3        | 1.38%   |
| Intel AX211 Bluetooth                                 | 3        | 1.38%   |
| Broadcom HP Portable Bumble Bee                       | 3        | 1.38%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 3        | 1.38%   |
| Qualcomm Atheros  Bluetooth Device                    | 2        | 0.92%   |
| IMC Networks Bluetooth Radio                          | 2        | 0.92%   |
| IMC Networks BCM20702A0                               | 2        | 0.92%   |
| Broadcom Bluetooth 3.0 Dongle                         | 2        | 0.92%   |
| Belkin Components Bluetooth Mini Dongle               | 2        | 0.92%   |
| ASUS Bluetooth Radio                                  | 2        | 0.92%   |
| ASUS BCM20702A0                                       | 2        | 0.92%   |
| Apple Bluetooth USB Host Controller                   | 2        | 0.92%   |
| Apple Bluetooth Host Controller                       | 2        | 0.92%   |
| Unknown                                               | 2        | 0.92%   |
| Realtek Bluetooth 5.3 Radio                           | 1        | 0.46%   |
| Ralink RT3290 Bluetooth                               | 1        | 0.46%   |
| Qualcomm Atheros Bluetooth USB Host Controller        | 1        | 0.46%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 1        | 0.46%   |
| Qcom Bluetooth USB                                    | 1        | 0.46%   |
| IMC Networks Wireless_Device                          | 1        | 0.46%   |
| Foxconn / Hon Hai Wireless_Device                     | 1        | 0.46%   |
| Edimax Bluetooth Adapter                              | 1        | 0.46%   |
| Broadcom Bluetooth dongle                             | 1        | 0.46%   |
| Broadcom Bluetooth Controller                         | 1        | 0.46%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter      | 1        | 0.46%   |
| Broadcom BCM43142A0 Bluetooth 4.0                     | 1        | 0.46%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 0.46%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 403      | 39.36%  |
| AMD                                          | 237      | 23.14%  |
| Nvidia                                       | 230      | 22.46%  |
| C-Media Electronics                          | 42       | 4.1%    |
| Creative Labs                                | 17       | 1.66%   |
| Logitech                                     | 14       | 1.37%   |
| JMTek                                        | 7        | 0.68%   |
| Generalplus Technology                       | 7        | 0.68%   |
| Texas Instruments                            | 5        | 0.49%   |
| Razer USA                                    | 5        | 0.49%   |
| GN Netcom                                    | 4        | 0.39%   |
| Creative Technology                          | 4        | 0.39%   |
| Corsair                                      | 4        | 0.39%   |
| ASUSTek Computer                             | 3        | 0.29%   |
| Micro Star International                     | 2        | 0.2%    |
| M-Audio                                      | 2        | 0.2%    |
| KTMicro                                      | 2        | 0.2%    |
| Jieli Technology                             | 2        | 0.2%    |
| Hewlett-Packard                              | 2        | 0.2%    |
| Focusrite-Novation                           | 2        | 0.2%    |
| Cambridge Silicon Radio                      | 2        | 0.2%    |
| BEHRINGER International                      | 2        | 0.2%    |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.1%    |
| VIA Technologies                             | 1        | 0.1%    |
| Thesycon Systemsoftware & Consulting         | 1        | 0.1%    |
| Tenx Technology                              | 1        | 0.1%    |
| Sony                                         | 1        | 0.1%    |
| Samson Technologies                          | 1        | 0.1%    |
| Realtek Semiconductor                        | 1        | 0.1%    |
| PreSonus Audio Electronics                   | 1        | 0.1%    |
| Plantronics                                  | 1        | 0.1%    |
| Philips Speech Processing                    | 1        | 0.1%    |
| Nordic Semiconductor ASA                     | 1        | 0.1%    |
| Native Instruments                           | 1        | 0.1%    |
| Microsoft                                    | 1        | 0.1%    |
| Kingston Technology                          | 1        | 0.1%    |
| iCreate Technologies                         | 1        | 0.1%    |
| Goldvish                                     | 1        | 0.1%    |
| Fortemedia                                   | 1        | 0.1%    |
| fifine Microphones                           | 1        | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 73       | 6.21%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 56       | 4.76%   |
| AMD Starship/Matisse HD Audio Controller                                          | 38       | 3.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 37       | 3.15%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 33       | 2.81%   |
| Intel 200 Series PCH HD Audio                                                     | 33       | 2.81%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 33       | 2.81%   |
| Intel Cannon Lake PCH cAVS                                                        | 32       | 2.72%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 30       | 2.55%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                        | 30       | 2.55%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 25       | 2.13%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 24       | 2.04%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 24       | 2.04%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 20       | 1.7%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 20       | 1.7%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 18       | 1.53%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 17       | 1.45%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 17       | 1.45%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 17       | 1.45%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 17       | 1.45%   |
| AMD FCH Azalia Controller                                                         | 17       | 1.45%   |
| Nvidia GF108 High Definition Audio Controller                                     | 14       | 1.19%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 14       | 1.19%   |
| Nvidia TU116 High Definition Audio Controller                                     | 13       | 1.11%   |
| Nvidia GP106 High Definition Audio Controller                                     | 13       | 1.11%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 13       | 1.11%   |
| Nvidia GP104 High Definition Audio Controller                                     | 12       | 1.02%   |
| Nvidia High Definition Audio Controller                                           | 11       | 0.94%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 10       | 0.85%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 10       | 0.85%   |
| Nvidia TU106 High Definition Audio Controller                                     | 9        | 0.77%   |
| Nvidia TU104 HD Audio Controller                                                  | 9        | 0.77%   |
| Nvidia GP108 High Definition Audio Controller                                     | 9        | 0.77%   |
| Nvidia GM204 High Definition Audio Controller                                     | 9        | 0.77%   |
| Nvidia GA104 High Definition Audio Controller                                     | 9        | 0.77%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 9        | 0.77%   |
| Nvidia MCP61 High Definition Audio                                                | 8        | 0.68%   |
| Nvidia GA102 High Definition Audio Controller                                     | 8        | 0.68%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 8        | 0.68%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 8        | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 37       | 25.87%  |
| Samsung Electronics | 19       | 13.29%  |
| Unknown             | 16       | 11.19%  |
| Corsair             | 11       | 7.69%   |
| Crucial             | 10       | 6.99%   |
| SK hynix            | 9        | 6.29%   |
| G.Skill             | 9        | 6.29%   |
| Micron Technology   | 5        | 3.5%    |
| Nanya Technology    | 4        | 2.8%    |
| Ramaxel Technology  | 3        | 2.1%    |
| Patriot             | 3        | 2.1%    |
| A-DATA Technology   | 3        | 2.1%    |
| Transcend           | 2        | 1.4%    |
| Apacer              | 2        | 1.4%    |
| Unknown             | 2        | 1.4%    |
| Unknown (82B5)      | 1        | 0.7%    |
| Unknown (0x5846)    | 1        | 0.7%    |
| Unknown (0x038A)    | 1        | 0.7%    |
| Timetec             | 1        | 0.7%    |
| Team                | 1        | 0.7%    |
| PNY                 | 1        | 0.7%    |
| Neo Forza           | 1        | 0.7%    |
| CSX                 | 1        | 0.7%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Unknown RAM Module 8GB DIMM 1333MT/s                            | 2        | 1.33%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                            | 2        | 1.33%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                    | 2        | 1.33%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                     | 2        | 1.33%   |
| SK hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s            | 2        | 1.33%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s           | 2        | 1.33%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s             | 2        | 1.33%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1923MT/s             | 2        | 1.33%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 3066MT/s            | 2        | 1.33%   |
| Unknown                                                         | 2        | 1.33%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                       | 1        | 0.67%   |
| Unknown RAM Module 8GB DIMM DDR3 1066MT/s                       | 1        | 0.67%   |
| Unknown RAM Module 8192MB DIMM DDR3 1066MT/s                    | 1        | 0.67%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                         | 1        | 0.67%   |
| Unknown RAM Module 8192MB DIMM 1066MT/s                         | 1        | 0.67%   |
| Unknown RAM Module 512MB DIMM SDRAM                             | 1        | 0.67%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                       | 1        | 0.67%   |
| Unknown RAM Module 2GB DIMM SDRAM 800MT/s                       | 1        | 0.67%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                            | 1        | 0.67%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                     | 1        | 0.67%   |
| Unknown RAM Module 2048MB DIMM DDR 133MT/s                      | 1        | 0.67%   |
| Unknown RAM Module 16GB DIMM DDR4 2667MT/s                      | 1        | 0.67%   |
| Unknown RAM Module 1024MB DIMM SDRAM                            | 1        | 0.67%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                     | 1        | 0.67%   |
| Unknown (82B5) RAM OP 117100 05/14 2M 4096MB DIMM DDR3 1333MT/s | 1        | 0.67%   |
| Unknown (0x5846) RAM DDR4 NB 8G 2666 8GB SODIMM DDR4 2667MT/s   | 1        | 0.67%   |
| Unknown (0x038A) RAM Module 4GB DIMM DDR3 1066MT/s              | 1        | 0.67%   |
| Transcend RAM JM800QSU-2G 2GB SODIMM DDR2 800MT/s               | 1        | 0.67%   |
| Transcend RAM JM1333KLN-2G 2GB DIMM 1333MT/s                    | 1        | 0.67%   |
| Timetec RAM U8G-1333 8GB DIMM DDR3 1333MT/s                     | 1        | 0.67%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s              | 1        | 0.67%   |
| SK hynix RAM HYMP112U64CP8-Y5 1GB DIMM DDR2 1639MT/s            | 1        | 0.67%   |
| SK hynix RAM HMT42GR7BMR4C 16GB DIMM DDR3 1066MT/s              | 1        | 0.67%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s            | 1        | 0.67%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s            | 1        | 0.67%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s            | 1        | 0.67%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s          | 1        | 0.67%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s            | 1        | 0.67%   |
| Samsung RAM Module 8GB DIMM DDR3 1333MT/s                       | 1        | 0.67%   |
| Samsung RAM Module 8192MB Row Of Chips LPDDR4 3733MT/s          | 1        | 0.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 51       | 45.13%  |
| DDR4    | 37       | 32.74%  |
| SDRAM   | 8        | 7.08%   |
| DDR2    | 8        | 7.08%   |
| Unknown | 7        | 6.19%   |
| LPDDR4  | 1        | 0.88%   |
| DDR     | 1        | 0.88%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 101      | 90.99%  |
| SODIMM       | 8        | 7.21%   |
| Row Of Chips | 1        | 0.9%    |
| FB-DIMM      | 1        | 0.9%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 50       | 39.06%  |
| 4096  | 33       | 25.78%  |
| 2048  | 20       | 15.63%  |
| 16384 | 16       | 12.5%   |
| 1024  | 6        | 4.69%   |
| 32768 | 2        | 1.56%   |
| 512   | 1        | 0.78%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1333    | 24       | 18.46%  |
| 1600    | 23       | 17.69%  |
| 2400    | 8        | 6.15%   |
| 3600    | 6        | 4.62%   |
| 3200    | 6        | 4.62%   |
| 667     | 6        | 4.62%   |
| 2667    | 5        | 3.85%   |
| 800     | 5        | 3.85%   |
| 1867    | 4        | 3.08%   |
| 1800    | 4        | 3.08%   |
| 1066    | 4        | 3.08%   |
| 3733    | 3        | 2.31%   |
| 2133    | 3        | 2.31%   |
| 1866    | 3        | 2.31%   |
| 3466    | 2        | 1.54%   |
| 3066    | 2        | 1.54%   |
| 2933    | 2        | 1.54%   |
| 1639    | 2        | 1.54%   |
| 4800    | 1        | 0.77%   |
| 4000    | 1        | 0.77%   |
| 3866    | 1        | 0.77%   |
| 3400    | 1        | 0.77%   |
| 3334    | 1        | 0.77%   |
| 3266    | 1        | 0.77%   |
| 3007    | 1        | 0.77%   |
| 3000    | 1        | 0.77%   |
| 2934    | 1        | 0.77%   |
| 2800    | 1        | 0.77%   |
| 2733    | 1        | 0.77%   |
| 2666    | 1        | 0.77%   |
| 2200    | 1        | 0.77%   |
| 2000    | 1        | 0.77%   |
| 975     | 1        | 0.77%   |
| 533     | 1        | 0.77%   |
| 133     | 1        | 0.77%   |
| Unknown | 1        | 0.77%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 13       | 41.94%  |
| Canon                 | 5        | 16.13%  |
| Brother Industries    | 5        | 16.13%  |
| Samsung Electronics   | 3        | 9.68%   |
| Lexmark International | 2        | 6.45%   |
| Seiko Epson           | 1        | 3.23%   |
| QUIN                  | 1        | 3.23%   |
| Dymo-CoStar           | 1        | 3.23%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Seiko Epson XP-4100 Series                 | 1        | 3.23%   |
| Samsung M288x Series                       | 1        | 3.23%   |
| Samsung M2070 Series                       | 1        | 3.23%   |
| Samsung M2020 Series                       | 1        | 3.23%   |
| QUIN Label Printer                         | 1        | 3.23%   |
| Lexmark International Laser Printer E210   | 1        | 3.23%   |
| Lexmark International InkJet Color Printer | 1        | 3.23%   |
| HP Smart Tank 580-590 series               | 1        | 3.23%   |
| HP Printing Support                        | 1        | 3.23%   |
| HP OfficeJet 5200 series                   | 1        | 3.23%   |
| HP LaserJet Pro M201dw                     | 1        | 3.23%   |
| HP LaserJet M101-M106                      | 1        | 3.23%   |
| HP LaserJet 1320                           | 1        | 3.23%   |
| HP LaserJet 1300                           | 1        | 3.23%   |
| HP LaserJet 1020                           | 1        | 3.23%   |
| HP Ink Tank 110 series                     | 1        | 3.23%   |
| HP Deskjet 3520 series                     | 1        | 3.23%   |
| HP DeskJet 2700 series                     | 1        | 3.23%   |
| HP Deskjet 2050 J510                       | 1        | 3.23%   |
| HP Deskjet 1000 J110 series                | 1        | 3.23%   |
| Dymo-CoStar LabelWriter 450                | 1        | 3.23%   |
| Canon TR8500 series                        | 1        | 3.23%   |
| Canon PIXMA MX390 Series                   | 1        | 3.23%   |
| Canon PIXMA MG3600 Series                  | 1        | 3.23%   |
| Canon MF4320-4350                          | 1        | 3.23%   |
| Canon CanoScan LiDE 300                    | 1        | 3.23%   |
| Brother MFC-T910DW                         | 1        | 3.23%   |
| Brother MFC-J5335DW                        | 1        | 3.23%   |
| Brother MFC-J5330DW                        | 1        | 3.23%   |
| Brother HL-4140CN series                   | 1        | 3.23%   |
| Brother DCP-L2550DN series                 | 1        | 3.23%   |

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
| Canon CanoScan LIDE 25             | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 36       | 32.14%  |
| Microdia                      | 10       | 8.93%   |
| Microsoft                     | 9        | 8.04%   |
| Apple                         | 6        | 5.36%   |
| Chicony Electronics           | 5        | 4.46%   |
| Z-Star Microelectronics       | 4        | 3.57%   |
| Generalplus Technology        | 4        | 3.57%   |
| Sunplus Innovation Technology | 3        | 2.68%   |
| Samsung Electronics           | 3        | 2.68%   |
| SunplusIT                     | 2        | 1.79%   |
| KYE Systems (Mouse Systems)   | 2        | 1.79%   |
| GEMBIRD                       | 2        | 1.79%   |
| Cubeternet                    | 2        | 1.79%   |
| Alcor Micro                   | 2        | 1.79%   |
| WaveRider Communications      | 1        | 0.89%   |
| USB 4K Camera                 | 1        | 0.89%   |
| UltraSemi                     | 1        | 0.89%   |
| Trust                         | 1        | 0.89%   |
| Teslong Camera                | 1        | 0.89%   |
| Syntek                        | 1        | 0.89%   |
| Sunplus IT                    | 1        | 0.89%   |
| Silicon Motion                | 1        | 0.89%   |
| Realtek Semiconductor         | 1        | 0.89%   |
| Razer USA                     | 1        | 0.89%   |
| Pixart Imaging                | 1        | 0.89%   |
| Philips (or NXP)              | 1        | 0.89%   |
| OmniVision Technologies       | 1        | 0.89%   |
| LG Electronics                | 1        | 0.89%   |
| Jieli Technology              | 1        | 0.89%   |
| Hewlett-Packard               | 1        | 0.89%   |
| HD USB Camera                 | 1        | 0.89%   |
| Guillemot                     | 1        | 0.89%   |
| Creative Technology           | 1        | 0.89%   |
| AVerMedia Technologies        | 1        | 0.89%   |
| Arkmicro Technologies         | 1        | 0.89%   |
| ANYKA                         | 1        | 0.89%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920             | 11       | 9.82%   |
| Logitech Webcam C270                    | 5        | 4.46%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR      | 5        | 4.46%   |
| Microsoft LifeCam HD-3000               | 4        | 3.57%   |
| Generalplus GENERAL WEBCAM              | 4        | 3.57%   |
| Samsung Galaxy series, misc. (MTP mode) | 3        | 2.68%   |
| Microdia USB 2.0 Camera                 | 3        | 2.68%   |
| Microdia Integrated Camera              | 3        | 2.68%   |
| Logitech HD Webcam C615                 | 3        | 2.68%   |
| Logitech C922 Pro Stream Webcam         | 3        | 2.68%   |
| Chicony HP High Definition 1MP Webcam   | 3        | 2.68%   |
| Microsoft LifeCam VX-800                | 2        | 1.79%   |
| Logitech Logitech Webcam C925e          | 2        | 1.79%   |
| Logitech BRIO 4K Stream Edition         | 2        | 1.79%   |
| Logitech B525 HD Webcam                 | 2        | 1.79%   |
| GEMBIRD USB2.0 PC CAMERA                | 2        | 1.79%   |
| Cubeternet GL-UPC822 UVC WebCam         | 2        | 1.79%   |
| Z-Star Venus USB2.0 Camera              | 1        | 0.89%   |
| Z-Star Vega USB 2.0 Camera              | 1        | 0.89%   |
| Z-Star Sirius USB2.0 Camera             | 1        | 0.89%   |
| Z-Star Integrated Camera                | 1        | 0.89%   |
| WaveRider USB 2.0 Camera                | 1        | 0.89%   |
| USB 4K Camera                           | 1        | 0.89%   |
| UltraSemi USB3 Video                    | 1        | 0.89%   |
| Trust Trust USB Camera                  | 1        | 0.89%   |
| Teslong Camera                          | 1        | 0.89%   |
| Syntek USB Video Device                 | 1        | 0.89%   |
| SunplusIT USB IR Camera                 | 1        | 0.89%   |
| SunplusIT USB camera                    | 1        | 0.89%   |
| Sunplus IT PC Camera                    | 1        | 0.89%   |
| Sunplus USB Camera                      | 1        | 0.89%   |
| Sunplus USB 2.0 Camera                  | 1        | 0.89%   |
| Sunplus DICOTA 4K                       | 1        | 0.89%   |
| Silicon Motion Silicon Motion Camera    | 1        | 0.89%   |
| Realtek FULL HD 1080P Webcam            | 1        | 0.89%   |
| Razer USA Razer Kiyo Pro                | 1        | 0.89%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro    | 1        | 0.89%   |
| Philips (or NXP) SPZ2500                | 1        | 0.89%   |
| OmniVision Monitor Webcam               | 1        | 0.89%   |
| Microsoft Xbox NUI Camera               | 1        | 0.89%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| LighTuning Fingerprint Sensor | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Alcor Micro          | 2        | 40%     |
| OmniKey              | 1        | 20%     |
| Feitian Technologies | 1        | 20%     |
| Chicony Electronics  | 1        | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Alcor Micro AU9540 Smartcard Reader                  | 2        | 40%     |
| OmniKey CardMan 3121 (HID Technologies)              | 1        | 20%     |
| Feitian Technologies SCR301                          | 1        | 20%     |
| Chicony Electronics HP Skylab USB Smartcard Keyboard | 1        | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 501      | 83.78%  |
| 1     | 80       | 13.38%  |
| 2     | 14       | 2.34%   |
| 3     | 2        | 0.33%   |
| 4     | 1        | 0.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 46       | 41.44%  |
| Graphics card            | 25       | 22.52%  |
| Sound                    | 7        | 6.31%   |
| Unassigned class         | 6        | 5.41%   |
| Network                  | 4        | 3.6%    |
| Multimedia controller    | 4        | 3.6%    |
| Chipcard                 | 4        | 3.6%    |
| Communication controller | 3        | 2.7%    |
| Card reader              | 3        | 2.7%    |
| Bluetooth                | 3        | 2.7%    |
| Camera                   | 2        | 1.8%    |
| Storage/raid             | 1        | 0.9%    |
| Storage/ide              | 1        | 0.9%    |
| Net/ethernet             | 1        | 0.9%    |
| Fingerprint reader       | 1        | 0.9%    |

