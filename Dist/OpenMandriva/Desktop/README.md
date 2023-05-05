OpenMandriva - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for OpenMandriva.

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

Total: 6509

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | SABERTOOTH 990FX R2.0       | [41e9bb9584](https://linux-hardware.org/?probe=41e9bb9584) | May 01, 2023 |
| HP            | 822A                        | [b373ff6def](https://linux-hardware.org/?probe=b373ff6def) | May 01, 2023 |
| Dell          | 06D7TR A00                  | [e7905065dd](https://linux-hardware.org/?probe=e7905065dd) | Apr 30, 2023 |
| MSI           | B450M PRO-M2                | [b650f0a26e](https://linux-hardware.org/?probe=b650f0a26e) | Apr 30, 2023 |
| DIEBOLD       | NM70-I                      | [c01a40d58c](https://linux-hardware.org/?probe=c01a40d58c) | Apr 30, 2023 |
| HP            | ProLiant ML310e Gen8 v2     | [501d26e477](https://linux-hardware.org/?probe=501d26e477) | Apr 30, 2023 |
| ASRock        | 760GM-HD                    | [db79e93331](https://linux-hardware.org/?probe=db79e93331) | Apr 30, 2023 |
| Gigabyte      | Z77M-D3H                    | [a3d2b3dcd3](https://linux-hardware.org/?probe=a3d2b3dcd3) | Apr 30, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [ac7894081f](https://linux-hardware.org/?probe=ac7894081f) | Apr 30, 2023 |
| Medion        | D3F3-EM                     | [6b9e38ad6c](https://linux-hardware.org/?probe=6b9e38ad6c) | Apr 30, 2023 |
| MSI           | A68HM GRENADE               | [938aa1cb46](https://linux-hardware.org/?probe=938aa1cb46) | Apr 30, 2023 |
| Gigabyte      | H77-DS3H                    | [6750e5f83d](https://linux-hardware.org/?probe=6750e5f83d) | Apr 30, 2023 |
| Acer          | E661GXM                     | [d5433b46bd](https://linux-hardware.org/?probe=d5433b46bd) | Apr 30, 2023 |
| Acer          | Aspire X3950                | [406366d5c1](https://linux-hardware.org/?probe=406366d5c1) | Apr 30, 2023 |
| T-bao         | MINI PC V1.0                | [8e77950434](https://linux-hardware.org/?probe=8e77950434) | Apr 30, 2023 |
| Intel         | H61                         | [167616bc61](https://linux-hardware.org/?probe=167616bc61) | Apr 30, 2023 |
| Dell          | 0GXM1W A02                  | [7dcb847a6c](https://linux-hardware.org/?probe=7dcb847a6c) | Apr 30, 2023 |
| Dell          | 0773VG A02                  | [a684ad4938](https://linux-hardware.org/?probe=a684ad4938) | Apr 29, 2023 |
| ASUSTek       | H81M-C/BR                   | [32942be783](https://linux-hardware.org/?probe=32942be783) | Apr 29, 2023 |
| ASRock        | 890FX Deluxe4               | [327a1a2b37](https://linux-hardware.org/?probe=327a1a2b37) | Apr 29, 2023 |
| ASUSTek       | Z97-P                       | [8ea78b28f1](https://linux-hardware.org/?probe=8ea78b28f1) | Apr 29, 2023 |
| Foxconn       | 2AB7                        | [01e7b05d2a](https://linux-hardware.org/?probe=01e7b05d2a) | Apr 29, 2023 |
| ASRock        | A320M-DVS R4.0              | [7e7da68aa3](https://linux-hardware.org/?probe=7e7da68aa3) | Apr 28, 2023 |
| AZW           | MINI S 10                   | [12ba32f977](https://linux-hardware.org/?probe=12ba32f977) | Apr 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [92be2563a8](https://linux-hardware.org/?probe=92be2563a8) | Apr 28, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [2beb48be05](https://linux-hardware.org/?probe=2beb48be05) | Apr 27, 2023 |
| MSI           | H81M-P33                    | [2099cafe74](https://linux-hardware.org/?probe=2099cafe74) | Apr 27, 2023 |
| ASUSTek       | P5GC-VM/SI                  | [abf277ec59](https://linux-hardware.org/?probe=abf277ec59) | Apr 27, 2023 |
| ASRock        | H510M-HDV R2.0              | [91930613cb](https://linux-hardware.org/?probe=91930613cb) | Apr 27, 2023 |
| MSI           | A78M-E35 V2                 | [5eb0f9d104](https://linux-hardware.org/?probe=5eb0f9d104) | Apr 27, 2023 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [6601cb2397](https://linux-hardware.org/?probe=6601cb2397) | Apr 26, 2023 |
| Lenovo        | SHARKBAY NOK                | [54dea0607f](https://linux-hardware.org/?probe=54dea0607f) | Apr 26, 2023 |
| ASUSTek       | AM1M-A                      | [ab3c4ea199](https://linux-hardware.org/?probe=ab3c4ea199) | Apr 26, 2023 |
| ASUSTek       | PRIME B250M-C               | [aca5bf366f](https://linux-hardware.org/?probe=aca5bf366f) | Apr 26, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | [238598d9ab](https://linux-hardware.org/?probe=238598d9ab) | Apr 26, 2023 |
| Biostar       | H610MH                      | [935928c60d](https://linux-hardware.org/?probe=935928c60d) | Apr 26, 2023 |
| Acer          | Aspire TC-605               | [b9dcc7f752](https://linux-hardware.org/?probe=b9dcc7f752) | Apr 26, 2023 |
| Gigabyte      | B75M-D3H                    | [4f1e4da37e](https://linux-hardware.org/?probe=4f1e4da37e) | Apr 26, 2023 |
| Intel         | H81                         | [9a14132581](https://linux-hardware.org/?probe=9a14132581) | Apr 26, 2023 |
| HP            | 83E2                        | [f10d975821](https://linux-hardware.org/?probe=f10d975821) | Apr 26, 2023 |
| ASUSTek       | PRIME H270-PLUS             | [8a0cd0bb6e](https://linux-hardware.org/?probe=8a0cd0bb6e) | Apr 26, 2023 |
| HP            | 3029h                       | [35be4d25c4](https://linux-hardware.org/?probe=35be4d25c4) | Apr 25, 2023 |
| ASUSTek       | P8P67 LE                    | [e46f340908](https://linux-hardware.org/?probe=e46f340908) | Apr 25, 2023 |
| ASRock        | AB350M-HDV                  | [44ac797451](https://linux-hardware.org/?probe=44ac797451) | Apr 25, 2023 |
| MSI           | B250M PRO-VH                | [f132c966f5](https://linux-hardware.org/?probe=f132c966f5) | Apr 25, 2023 |
| ASUSTek       | A68HM-K                     | [ae90303c3a](https://linux-hardware.org/?probe=ae90303c3a) | Apr 25, 2023 |
| ASUSTek       | J1800I-C                    | [0a58f3fa51](https://linux-hardware.org/?probe=0a58f3fa51) | Apr 25, 2023 |
| Lenovo        | ThinkCentre A70z 0401G6G    | [b1b8bf3df6](https://linux-hardware.org/?probe=b1b8bf3df6) | Apr 25, 2023 |
| Dell          | 0773VG A01                  | [40cf2f15c2](https://linux-hardware.org/?probe=40cf2f15c2) | Apr 25, 2023 |
| HP            | 18E9                        | [b9bb679cca](https://linux-hardware.org/?probe=b9bb679cca) | Apr 25, 2023 |
| ASUSTek       | PRIME A520M-K               | [a437a858a4](https://linux-hardware.org/?probe=a437a858a4) | Apr 25, 2023 |
| Lenovo        | SHARKBAY NOK                | [c5adfbd376](https://linux-hardware.org/?probe=c5adfbd376) | Apr 25, 2023 |
| Gigabyte      | 945GCM-S2L                  | [405bcbb43c](https://linux-hardware.org/?probe=405bcbb43c) | Apr 25, 2023 |
| ASRock        | H81M-VG4 R2.0               | [09c7ae9819](https://linux-hardware.org/?probe=09c7ae9819) | Apr 25, 2023 |
| Gigabyte      | Z77M-D3H                    | [915147a191](https://linux-hardware.org/?probe=915147a191) | Apr 25, 2023 |
| Gigabyte      | Z77M-D3H                    | [92a968e58d](https://linux-hardware.org/?probe=92a968e58d) | Apr 25, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [d9ad034d8c](https://linux-hardware.org/?probe=d9ad034d8c) | Apr 24, 2023 |
| ASUSTek       | P7P55D-E                    | [0e79aaac72](https://linux-hardware.org/?probe=0e79aaac72) | Apr 24, 2023 |
| ASRock        | H97M Anniversary            | [fdcfb2bde7](https://linux-hardware.org/?probe=fdcfb2bde7) | Apr 24, 2023 |
| ASUSTek       | PRIME Z590-P                | [ebe492b020](https://linux-hardware.org/?probe=ebe492b020) | Apr 24, 2023 |
| ASRock        | X570 Taichi                 | [0842334fa2](https://linux-hardware.org/?probe=0842334fa2) | Apr 24, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [6531aafbfe](https://linux-hardware.org/?probe=6531aafbfe) | Apr 24, 2023 |
| Gigabyte      | GA-970A-UD3                 | [6f3f14d26d](https://linux-hardware.org/?probe=6f3f14d26d) | Apr 23, 2023 |
| ASUSTek       | Z170-K                      | [538ebf1f96](https://linux-hardware.org/?probe=538ebf1f96) | Apr 23, 2023 |
| HP            | 0AA8h                       | [b927834a03](https://linux-hardware.org/?probe=b927834a03) | Apr 23, 2023 |
| Gigabyte      | B550 GAMING X V2            | [22594512d1](https://linux-hardware.org/?probe=22594512d1) | Apr 23, 2023 |
| Shenzhen M... | F6CQW                       | [c2be3dd62b](https://linux-hardware.org/?probe=c2be3dd62b) | Apr 23, 2023 |
| Gigabyte      | H61M-S2PH                   | [ec36f4ada2](https://linux-hardware.org/?probe=ec36f4ada2) | Apr 23, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [cc80f06375](https://linux-hardware.org/?probe=cc80f06375) | Apr 23, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | [3fa24b1a91](https://linux-hardware.org/?probe=3fa24b1a91) | Apr 23, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [93790f1835](https://linux-hardware.org/?probe=93790f1835) | Apr 23, 2023 |
| Gigabyte      | 990FXA-UD3                  | [bf1dbf49a8](https://linux-hardware.org/?probe=bf1dbf49a8) | Apr 22, 2023 |
| Gigabyte      | EP45-UD3                    | [5d45f63468](https://linux-hardware.org/?probe=5d45f63468) | Apr 22, 2023 |
| ASUSTek       | P8H77-I                     | [e2276c080b](https://linux-hardware.org/?probe=e2276c080b) | Apr 22, 2023 |
| Biostar       | A75MG                       | [50cb5c256e](https://linux-hardware.org/?probe=50cb5c256e) | Apr 22, 2023 |
| Gigabyte      | B550M S2H                   | [485f002152](https://linux-hardware.org/?probe=485f002152) | Apr 22, 2023 |
| Fujitsu       | FJNB037                     | [00e5e30f9b](https://linux-hardware.org/?probe=00e5e30f9b) | Apr 22, 2023 |
| Dell          | 0K240Y A02                  | [2d1b73d846](https://linux-hardware.org/?probe=2d1b73d846) | Apr 22, 2023 |
| ECS           | APLD-MINI                   | [8f3546722b](https://linux-hardware.org/?probe=8f3546722b) | Apr 22, 2023 |
| ASUSTek       | PRIME H510M-K               | [820acdb913](https://linux-hardware.org/?probe=820acdb913) | Apr 22, 2023 |
| MSI           | B360M BAZOOKA               | [46516c6f3a](https://linux-hardware.org/?probe=46516c6f3a) | Apr 22, 2023 |
| Fujitsu Si... | D2156-A1 S26361-D2156-A1    | [617f821f9a](https://linux-hardware.org/?probe=617f821f9a) | Apr 22, 2023 |
| Intel         | DG41RQ AAE54511-203         | [6a17fe6ead](https://linux-hardware.org/?probe=6a17fe6ead) | Apr 21, 2023 |
| ASRock        | H310CM-HG4                  | [6f49f4b883](https://linux-hardware.org/?probe=6f49f4b883) | Apr 21, 2023 |
| Intel         | DB65AL AAG12530-310         | [c625f3747a](https://linux-hardware.org/?probe=c625f3747a) | Apr 21, 2023 |
| Gigabyte      | B75M-HD3                    | [cde822d71c](https://linux-hardware.org/?probe=cde822d71c) | Apr 21, 2023 |
| HP            | 18E5                        | [0437b3deb1](https://linux-hardware.org/?probe=0437b3deb1) | Apr 21, 2023 |
| ASUSTek       | F2A85-V                     | [422eb87f07](https://linux-hardware.org/?probe=422eb87f07) | Apr 21, 2023 |
| Dell          | 0GDG8Y A00                  | [a315eaa776](https://linux-hardware.org/?probe=a315eaa776) | Apr 21, 2023 |
| Dell          | 040DDP A01                  | [6720e15331](https://linux-hardware.org/?probe=6720e15331) | Apr 21, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [fd91075868](https://linux-hardware.org/?probe=fd91075868) | Apr 21, 2023 |
| MouseCompu... | Z87-S01                     | [8caff0d2f2](https://linux-hardware.org/?probe=8caff0d2f2) | Apr 21, 2023 |
| ASRock        | P43DE                       | [8f2c0ecc69](https://linux-hardware.org/?probe=8f2c0ecc69) | Apr 21, 2023 |
| ASRock        | Z270 Taichi                 | [faf3402431](https://linux-hardware.org/?probe=faf3402431) | Apr 21, 2023 |
| Intel         | DG965RY AAD41691-301        | [0a153df418](https://linux-hardware.org/?probe=0a153df418) | Apr 20, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [5f1a1c6abd](https://linux-hardware.org/?probe=5f1a1c6abd) | Apr 20, 2023 |
| MSI           | B550-A PRO                  | [f2fc6a5da5](https://linux-hardware.org/?probe=f2fc6a5da5) | Apr 20, 2023 |
| Intel         | DG43GT AAE62768-301         | [643ed4ce33](https://linux-hardware.org/?probe=643ed4ce33) | Apr 20, 2023 |
| Gigabyte      | H61M-DS2                    | [8c43353ee9](https://linux-hardware.org/?probe=8c43353ee9) | Apr 20, 2023 |
| Acer          | Aspire XC-710 V:1.1         | [a09ea158cc](https://linux-hardware.org/?probe=a09ea158cc) | Apr 20, 2023 |
| HP            | 0B4Ch D                     | [69c613b55f](https://linux-hardware.org/?probe=69c613b55f) | Apr 20, 2023 |
| ASUSTek       | P5K SE                      | [eeff4cd84c](https://linux-hardware.org/?probe=eeff4cd84c) | Apr 20, 2023 |
| Gigabyte      | H81N                        | [5729c6c6a9](https://linux-hardware.org/?probe=5729c6c6a9) | Apr 20, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [561b87c8b4](https://linux-hardware.org/?probe=561b87c8b4) | Apr 20, 2023 |
| Gigabyte      | G31M-S2C                    | [0c45fc6929](https://linux-hardware.org/?probe=0c45fc6929) | Apr 20, 2023 |
| Intel         | H61S                        | [e29d71587a](https://linux-hardware.org/?probe=e29d71587a) | Apr 20, 2023 |
| HP            | 18E4                        | [1bd96a017f](https://linux-hardware.org/?probe=1bd96a017f) | Apr 19, 2023 |
| ASRock        | B560M-HDV                   | [b835e48fad](https://linux-hardware.org/?probe=b835e48fad) | Apr 19, 2023 |
| Dell          | 0NDYHG A01                  | [9c7e865b56](https://linux-hardware.org/?probe=9c7e865b56) | Apr 19, 2023 |
| Foxconn       | 2ABF                        | [53d3a8d066](https://linux-hardware.org/?probe=53d3a8d066) | Apr 19, 2023 |
| ECS           | BSW-MINI                    | [5d3161092f](https://linux-hardware.org/?probe=5d3161092f) | Apr 19, 2023 |
| ASRock        | B550M Pro4                  | [5fa6c74be4](https://linux-hardware.org/?probe=5fa6c74be4) | Apr 19, 2023 |
| MSI           | 0B58h                       | [6473456480](https://linux-hardware.org/?probe=6473456480) | Apr 19, 2023 |
| ECS           | H61H2-CM                    | [4396b0b045](https://linux-hardware.org/?probe=4396b0b045) | Apr 19, 2023 |
| HP            | 8309                        | [d82a6a4488](https://linux-hardware.org/?probe=d82a6a4488) | Apr 19, 2023 |
| MSI           | MS-7235                     | [efaeac524b](https://linux-hardware.org/?probe=efaeac524b) | Apr 18, 2023 |
| Fujitsu       | D2778-C1 S26361-D2778-C1    | [10693010af](https://linux-hardware.org/?probe=10693010af) | Apr 18, 2023 |
| Biostar       | A960D+V2                    | [34c47b4141](https://linux-hardware.org/?probe=34c47b4141) | Apr 18, 2023 |
| MSI           | B450 TOMAHAWK               | [fb3d31599f](https://linux-hardware.org/?probe=fb3d31599f) | Apr 18, 2023 |
| Dell          | 0KRC95 A00                  | [99ea2c7790](https://linux-hardware.org/?probe=99ea2c7790) | Apr 18, 2023 |
| NEC Comput... | MS-7451VM                   | [dc094ceba3](https://linux-hardware.org/?probe=dc094ceba3) | Apr 18, 2023 |
| ASRock        | B450M Pro4                  | [4c6abc2653](https://linux-hardware.org/?probe=4c6abc2653) | Apr 18, 2023 |
| ASUSTek       | P5QC                        | [7d47aa511b](https://linux-hardware.org/?probe=7d47aa511b) | Apr 18, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [dc707578c9](https://linux-hardware.org/?probe=dc707578c9) | Apr 18, 2023 |
| ASUSTek       | P8H67-M PRO                 | [9eb59318e2](https://linux-hardware.org/?probe=9eb59318e2) | Apr 18, 2023 |
| Acer          | FQ965M MP                   | [9be9793747](https://linux-hardware.org/?probe=9be9793747) | Apr 18, 2023 |
| HP            | 18E9                        | [8c36235f13](https://linux-hardware.org/?probe=8c36235f13) | Apr 18, 2023 |
| Gigabyte      | H370 AORUS GAMING 3-CF      | [8b585cf135](https://linux-hardware.org/?probe=8b585cf135) | Apr 18, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [8944559c50](https://linux-hardware.org/?probe=8944559c50) | Apr 17, 2023 |
| Gigabyte      | G31M-ES2L                   | [0244194778](https://linux-hardware.org/?probe=0244194778) | Apr 17, 2023 |
| HP            | 1850                        | [fa2fa68792](https://linux-hardware.org/?probe=fa2fa68792) | Apr 17, 2023 |
| HP            | 8062                        | [a2558d47e8](https://linux-hardware.org/?probe=a2558d47e8) | Apr 17, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [4174faae23](https://linux-hardware.org/?probe=4174faae23) | Apr 17, 2023 |
| ASRock        | H61M-DGS R2.0               | [695446a864](https://linux-hardware.org/?probe=695446a864) | Apr 17, 2023 |
| ASRock        | X99 Extreme4                | [e375be2ea6](https://linux-hardware.org/?probe=e375be2ea6) | Apr 17, 2023 |
| Medion        | MS-7728                     | [1da2d605db](https://linux-hardware.org/?probe=1da2d605db) | Apr 16, 2023 |
| Acer          | Aspire X3950                | [5a9abbd85f](https://linux-hardware.org/?probe=5a9abbd85f) | Apr 16, 2023 |
| eMachines     | E945GCU                     | [4e6aa4be24](https://linux-hardware.org/?probe=4e6aa4be24) | Apr 16, 2023 |
| ASUSTek       | X99-A/USB                   | [d686a4d03c](https://linux-hardware.org/?probe=d686a4d03c) | Apr 16, 2023 |
| MSI           | H310M PRO-VDH               | [01452c33d1](https://linux-hardware.org/?probe=01452c33d1) | Apr 16, 2023 |
| Gigabyte      | H61M-D2H-USB3               | [0134b33f82](https://linux-hardware.org/?probe=0134b33f82) | Apr 16, 2023 |
| ASRock        | N68-GS4 FX                  | [19a6cddfe0](https://linux-hardware.org/?probe=19a6cddfe0) | Apr 16, 2023 |
| Lenovo        | 3704 SDK0R32862 WIN 3258... | [4d3cbcc4d9](https://linux-hardware.org/?probe=4d3cbcc4d9) | Apr 16, 2023 |
| Dell          | 0RF705                      | [32dbb3206b](https://linux-hardware.org/?probe=32dbb3206b) | Apr 16, 2023 |
| ASUSTek       | PRIME A320M-K               | [a2596e8d06](https://linux-hardware.org/?probe=a2596e8d06) | Apr 16, 2023 |
| ASRock        | B650M PG Riptide            | [71643d03ec](https://linux-hardware.org/?probe=71643d03ec) | Apr 16, 2023 |
| ASUSTek       | PRIME H410M-E               | [fedecfd9ff](https://linux-hardware.org/?probe=fedecfd9ff) | Apr 16, 2023 |
| Foxconn       | ALOE                        | [702f958604](https://linux-hardware.org/?probe=702f958604) | Apr 16, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [980c6d63d6](https://linux-hardware.org/?probe=980c6d63d6) | Apr 16, 2023 |
| Lenovo        | SHARKBAY SDK0J40700 WIN ... | [00b59d56cd](https://linux-hardware.org/?probe=00b59d56cd) | Apr 16, 2023 |
| ASUSTek       | PRIME X299-DELUXE II        | [fad0ef7fef](https://linux-hardware.org/?probe=fad0ef7fef) | Apr 16, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [0853728b34](https://linux-hardware.org/?probe=0853728b34) | Apr 16, 2023 |
| MSI           | B150A GAMING PRO            | [26432a7622](https://linux-hardware.org/?probe=26432a7622) | Apr 16, 2023 |
| ASUSTek       | PRIME X570-P                | [337102cd4c](https://linux-hardware.org/?probe=337102cd4c) | Apr 15, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | [7ac461b735](https://linux-hardware.org/?probe=7ac461b735) | Apr 15, 2023 |
| Gigabyte      | F2A85XN-WIFI                | [80a8d69a06](https://linux-hardware.org/?probe=80a8d69a06) | Apr 15, 2023 |
| Foxconn       | 2A8C                        | [8a75d034c7](https://linux-hardware.org/?probe=8a75d034c7) | Apr 15, 2023 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | [e17175b9ac](https://linux-hardware.org/?probe=e17175b9ac) | Apr 15, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [83d43e489d](https://linux-hardware.org/?probe=83d43e489d) | Apr 15, 2023 |
| Lenovo        | ThinkCentre M58p 6234CZ6    | [e412c388d8](https://linux-hardware.org/?probe=e412c388d8) | Apr 15, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | [82abb09c06](https://linux-hardware.org/?probe=82abb09c06) | Apr 15, 2023 |
| Gigabyte      | GA-870A-UD3                 | [a359e8f3ea](https://linux-hardware.org/?probe=a359e8f3ea) | Apr 15, 2023 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | [8a5b5b102c](https://linux-hardware.org/?probe=8a5b5b102c) | Apr 14, 2023 |
| Gigabyte      | GA-990XA-UD3                | [d5669e92ed](https://linux-hardware.org/?probe=d5669e92ed) | Apr 14, 2023 |
| Gigabyte      | P55-UD3R                    | [5e8538987d](https://linux-hardware.org/?probe=5e8538987d) | Apr 14, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [3741318176](https://linux-hardware.org/?probe=3741318176) | Apr 14, 2023 |
| HP            | 1791                        | [c87bf6d0e1](https://linux-hardware.org/?probe=c87bf6d0e1) | Apr 13, 2023 |
| ASUSTek       | PRIME A320M-K               | [1bf207dfca](https://linux-hardware.org/?probe=1bf207dfca) | Apr 13, 2023 |
| Dell          | 0GXM1W A00                  | [f96d907026](https://linux-hardware.org/?probe=f96d907026) | Apr 13, 2023 |
| Lenovo        | 30C0 SDK0J40705 WIN 3425... | [490a059818](https://linux-hardware.org/?probe=490a059818) | Apr 13, 2023 |
| HP            | 1589                        | [b1ca06250e](https://linux-hardware.org/?probe=b1ca06250e) | Apr 13, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [d79266b94f](https://linux-hardware.org/?probe=d79266b94f) | Apr 13, 2023 |
| HP            | 3397                        | [0e4d29ffcd](https://linux-hardware.org/?probe=0e4d29ffcd) | Apr 13, 2023 |
| Gigabyte      | Z77M-D3H                    | [ffdcd55e2e](https://linux-hardware.org/?probe=ffdcd55e2e) | Apr 13, 2023 |
| Gigabyte      | H61M-HD2                    | [ea4bae8ef7](https://linux-hardware.org/?probe=ea4bae8ef7) | Apr 13, 2023 |
| MSI           | MS-7360                     | [48bee654fc](https://linux-hardware.org/?probe=48bee654fc) | Apr 13, 2023 |
| HP            | 1998                        | [8f0fef0b77](https://linux-hardware.org/?probe=8f0fef0b77) | Apr 12, 2023 |
| HP            | 805D                        | [f12230e709](https://linux-hardware.org/?probe=f12230e709) | Apr 12, 2023 |
| ASRock        | Z97M Pro4                   | [d98390c8a7](https://linux-hardware.org/?probe=d98390c8a7) | Apr 12, 2023 |
| Dell          | 02K9CR A01                  | [45c419b8d6](https://linux-hardware.org/?probe=45c419b8d6) | Apr 12, 2023 |
| Gigabyte      | A320M-H-CF                  | [6ac890debf](https://linux-hardware.org/?probe=6ac890debf) | Apr 12, 2023 |
| ASRock        | M3N78D FX                   | [618073d9e9](https://linux-hardware.org/?probe=618073d9e9) | Apr 12, 2023 |
| Gigabyte      | H310M S2H x.x               | [203aeef6a1](https://linux-hardware.org/?probe=203aeef6a1) | Apr 12, 2023 |
| Unknown       | SKYBAY                      | [9cd0292459](https://linux-hardware.org/?probe=9cd0292459) | Apr 12, 2023 |
| Gigabyte      | B450M DS3H V2               | [63c52bc5db](https://linux-hardware.org/?probe=63c52bc5db) | Apr 12, 2023 |
| ABIT          | NF-M2S                      | [30e3a2e8c4](https://linux-hardware.org/?probe=30e3a2e8c4) | Apr 11, 2023 |
| ASUSTek       | P5LD2-X/1333                | [e0e655f63c](https://linux-hardware.org/?probe=e0e655f63c) | Apr 11, 2023 |
| Unknown       | Unknown                     | [c67c78ba10](https://linux-hardware.org/?probe=c67c78ba10) | Apr 11, 2023 |
| MSI           | 970A GAMING PRO CARBON      | [b6cae4ec58](https://linux-hardware.org/?probe=b6cae4ec58) | Apr 11, 2023 |
| Acer          | Aspire TC-780               | [ce8b386e5b](https://linux-hardware.org/?probe=ce8b386e5b) | Apr 11, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [ad8009e647](https://linux-hardware.org/?probe=ad8009e647) | Apr 11, 2023 |
| Lenovo        | Dory CRB                    | [cab4258e1b](https://linux-hardware.org/?probe=cab4258e1b) | Apr 11, 2023 |
| Dell          | 0WR7PY A02                  | [2cec768fe1](https://linux-hardware.org/?probe=2cec768fe1) | Apr 11, 2023 |
| HP            | 805B                        | [591658775d](https://linux-hardware.org/?probe=591658775d) | Apr 11, 2023 |
| MSI           | B450M MORTAR MAX            | [e2cffb810b](https://linux-hardware.org/?probe=e2cffb810b) | Apr 10, 2023 |
| Biostar       | H61MHV                      | [13b4632c72](https://linux-hardware.org/?probe=13b4632c72) | Apr 10, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [35f953cfe0](https://linux-hardware.org/?probe=35f953cfe0) | Apr 10, 2023 |
| ASUSTek       | P5KPL-AM SE                 | [979e7ab8f3](https://linux-hardware.org/?probe=979e7ab8f3) | Apr 10, 2023 |
| ASRock        | B550M-ITX/ac                | [e043c1c94c](https://linux-hardware.org/?probe=e043c1c94c) | Apr 10, 2023 |
| Gigabyte      | H61M-D2-B3                  | [bf18b5af69](https://linux-hardware.org/?probe=bf18b5af69) | Apr 10, 2023 |
| HP            | 3032h                       | [824604840a](https://linux-hardware.org/?probe=824604840a) | Apr 10, 2023 |
| Lanix         | ChiefRiver                  | [ef23ac88e4](https://linux-hardware.org/?probe=ef23ac88e4) | Apr 10, 2023 |
| Biostar       | H81MHV3L                    | [8638a242be](https://linux-hardware.org/?probe=8638a242be) | Apr 10, 2023 |
| Biostar       | A320MH                      | [a2aef00c0c](https://linux-hardware.org/?probe=a2aef00c0c) | Apr 09, 2023 |
| ASRock        | X570 Pro4                   | [feb08fab62](https://linux-hardware.org/?probe=feb08fab62) | Apr 09, 2023 |
| Fujitsu Si... | D2312-A3 S26361-D2312-A3    | [54fabc7712](https://linux-hardware.org/?probe=54fabc7712) | Apr 09, 2023 |
| MACHINIST     | X99-k9 V1.0                 | [650acc25ef](https://linux-hardware.org/?probe=650acc25ef) | Apr 09, 2023 |
| ASRock        | Q1900M                      | [6ff7177033](https://linux-hardware.org/?probe=6ff7177033) | Apr 09, 2023 |
| Pegatron      | 2A73h                       | [5de48bf7df](https://linux-hardware.org/?probe=5de48bf7df) | Apr 09, 2023 |
| ECS           | H61H2-M17                   | [a2860baaee](https://linux-hardware.org/?probe=a2860baaee) | Apr 09, 2023 |
| HP            | 1998                        | [3974cfbb0c](https://linux-hardware.org/?probe=3974cfbb0c) | Apr 09, 2023 |
| Dell          | 0TTDMJ A00                  | [2b039ea053](https://linux-hardware.org/?probe=2b039ea053) | Apr 09, 2023 |
| ASUSTek       | AM1M-A                      | [120f5780bd](https://linux-hardware.org/?probe=120f5780bd) | Apr 09, 2023 |
| ASUSTek       | B85M-E                      | [fe9976de62](https://linux-hardware.org/?probe=fe9976de62) | Apr 09, 2023 |
| Gigabyte      | H370 HD3-CF                 | [b2c9afc61f](https://linux-hardware.org/?probe=b2c9afc61f) | Apr 09, 2023 |
| MSI           | B350M MORTAR                | [03960a3def](https://linux-hardware.org/?probe=03960a3def) | Apr 09, 2023 |
| Lenovo        | ThinkCentre M90p 5536W67    | [f67448dd99](https://linux-hardware.org/?probe=f67448dd99) | Apr 09, 2023 |
| Unknown       | Unknown                     | [2765290b8c](https://linux-hardware.org/?probe=2765290b8c) | Apr 09, 2023 |
| Dell          | 0Y2MRG A01                  | [d512dee0ba](https://linux-hardware.org/?probe=d512dee0ba) | Apr 09, 2023 |
| ASUSTek       | P5K                         | [00a17a60bf](https://linux-hardware.org/?probe=00a17a60bf) | Apr 09, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [4644a0ea43](https://linux-hardware.org/?probe=4644a0ea43) | Apr 09, 2023 |
| ASUSTek       | P8H61-M LE/USB3             | [0f364f6e82](https://linux-hardware.org/?probe=0f364f6e82) | Apr 09, 2023 |
| Lenovo        | 318E SDK0J40697 WIN 3305... | [436d55c73e](https://linux-hardware.org/?probe=436d55c73e) | Apr 09, 2023 |
| ASRock        | X300-ITX                    | [dbdef76cc2](https://linux-hardware.org/?probe=dbdef76cc2) | Apr 09, 2023 |
| SYWZ          | S210H Series                | [5989537064](https://linux-hardware.org/?probe=5989537064) | Apr 09, 2023 |
| AZW           | U59                         | [404036be4e](https://linux-hardware.org/?probe=404036be4e) | Apr 09, 2023 |
| ASRock        | B150 Combo                  | [c4acc08020](https://linux-hardware.org/?probe=c4acc08020) | Apr 09, 2023 |
| ASUSTek       | PRIME Z590-P WIFI           | [e579aabfdb](https://linux-hardware.org/?probe=e579aabfdb) | Apr 09, 2023 |
| MSI           | A68HM-E33 V2                | [05fc2725cf](https://linux-hardware.org/?probe=05fc2725cf) | Apr 09, 2023 |
| Dell          | 0PU052                      | [8f8c7f3a02](https://linux-hardware.org/?probe=8f8c7f3a02) | Apr 09, 2023 |
| Intel         | DH67BL AAG10189-207         | [1f13dff346](https://linux-hardware.org/?probe=1f13dff346) | Apr 08, 2023 |
| MSI           | B350 PC MATE                | [5c6c535e4d](https://linux-hardware.org/?probe=5c6c535e4d) | Apr 08, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [3fe1220d26](https://linux-hardware.org/?probe=3fe1220d26) | Apr 08, 2023 |
| HP            | 1459                        | [201dc05036](https://linux-hardware.org/?probe=201dc05036) | Apr 08, 2023 |
| ASRock        | 4X4-R1000                   | [56af110ee1](https://linux-hardware.org/?probe=56af110ee1) | Apr 08, 2023 |
| ASUSTek       | P8Z77-V PRO                 | [e1d6888ead](https://linux-hardware.org/?probe=e1d6888ead) | Apr 08, 2023 |
| Gigabyte      | GA-73PVM-S2                 | [2149d942b3](https://linux-hardware.org/?probe=2149d942b3) | Apr 08, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [e657bedde3](https://linux-hardware.org/?probe=e657bedde3) | Apr 08, 2023 |
| ASUSTek       | A88XM-A                     | [52728f9e37](https://linux-hardware.org/?probe=52728f9e37) | Apr 08, 2023 |
| ASUSTek       | P5KPL-AM SE                 | [4b4e5dfe24](https://linux-hardware.org/?probe=4b4e5dfe24) | Apr 08, 2023 |
| ASUSTek       | P5K                         | [ea3489709c](https://linux-hardware.org/?probe=ea3489709c) | Apr 08, 2023 |
| Fujitsu       | D3603-A1 S26361-D3603-A1    | [9cd5518f53](https://linux-hardware.org/?probe=9cd5518f53) | Apr 08, 2023 |
| Gigabyte      | B450M S2H                   | [f08d8d6bbd](https://linux-hardware.org/?probe=f08d8d6bbd) | Apr 08, 2023 |
| ASUSTek       | P8P67                       | [a62766f42e](https://linux-hardware.org/?probe=a62766f42e) | Apr 08, 2023 |
| MSI           | B550M-A PRO                 | [e3fcf877c0](https://linux-hardware.org/?probe=e3fcf877c0) | Apr 08, 2023 |
| Acer          | Aspire X3990                | [4d4816d6f8](https://linux-hardware.org/?probe=4d4816d6f8) | Apr 08, 2023 |
| ASRock        | 960GC-GS FX                 | [90cb74d9f0](https://linux-hardware.org/?probe=90cb74d9f0) | Apr 08, 2023 |
| ASRock        | 970 Pro3 R2.0               | [375bb1794b](https://linux-hardware.org/?probe=375bb1794b) | Apr 08, 2023 |
| ASUSTek       | A68HM-K                     | [55d971a67f](https://linux-hardware.org/?probe=55d971a67f) | Apr 08, 2023 |
| Lenovo        | No DPK                      | [7028629b85](https://linux-hardware.org/?probe=7028629b85) | Apr 08, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [c2132caa73](https://linux-hardware.org/?probe=c2132caa73) | Apr 08, 2023 |
| Biostar       | A520MH                      | [9cf296886b](https://linux-hardware.org/?probe=9cf296886b) | Apr 07, 2023 |
| ASRock        | B550 Phantom Gaming 4/ac    | [fa161c8db8](https://linux-hardware.org/?probe=fa161c8db8) | Apr 07, 2023 |
| ASRock        | B360M/OEM                   | [d1feabb956](https://linux-hardware.org/?probe=d1feabb956) | Apr 07, 2023 |
| ASUSTek       | H110M-R                     | [d4e3e5d85c](https://linux-hardware.org/?probe=d4e3e5d85c) | Apr 07, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [2d355e87d7](https://linux-hardware.org/?probe=2d355e87d7) | Apr 07, 2023 |
| Dell          | 0KRC95 A01                  | [9300a95302](https://linux-hardware.org/?probe=9300a95302) | Apr 07, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [bd1dc31213](https://linux-hardware.org/?probe=bd1dc31213) | Apr 07, 2023 |
| ASRock        | H97M Pro4                   | [904fc9e194](https://linux-hardware.org/?probe=904fc9e194) | Apr 07, 2023 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | [c76171c0a7](https://linux-hardware.org/?probe=c76171c0a7) | Apr 07, 2023 |
| ASRock        | 970A-G                      | [819194bd46](https://linux-hardware.org/?probe=819194bd46) | Apr 07, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [0f3e23c7ce](https://linux-hardware.org/?probe=0f3e23c7ce) | Apr 07, 2023 |
| Gigabyte      | GA-78LMT-S2PT               | [10c9b38ed6](https://linux-hardware.org/?probe=10c9b38ed6) | Apr 07, 2023 |
| Gigabyte      | B75M-D3H                    | [bf0c0bb982](https://linux-hardware.org/?probe=bf0c0bb982) | Apr 07, 2023 |
| Gigabyte      | H61M-S2PV                   | [8c4f851451](https://linux-hardware.org/?probe=8c4f851451) | Apr 07, 2023 |
| HP            | 82A2                        | [68d2b054d7](https://linux-hardware.org/?probe=68d2b054d7) | Apr 07, 2023 |
| Gigabyte      | Z77M-D3H                    | [d76bd92923](https://linux-hardware.org/?probe=d76bd92923) | Apr 07, 2023 |
| ASUSTek       | M4N98TD EVO                 | [8a2a2cf1ce](https://linux-hardware.org/?probe=8a2a2cf1ce) | Apr 07, 2023 |
| Alienware     | 0TYR0X A01                  | [35c94d7cd4](https://linux-hardware.org/?probe=35c94d7cd4) | Apr 07, 2023 |
| ASRock        | Z370 Taichi                 | [49aced4300](https://linux-hardware.org/?probe=49aced4300) | Apr 07, 2023 |
| MSI           | KA790GX                     | [c3dfb7614d](https://linux-hardware.org/?probe=c3dfb7614d) | Apr 07, 2023 |
| HP            | 1998                        | [50421ddca5](https://linux-hardware.org/?probe=50421ddca5) | Apr 07, 2023 |
| Biostar       | G41D3                       | [969695eafd](https://linux-hardware.org/?probe=969695eafd) | Apr 06, 2023 |
| Dell          | 0DFRFW A01                  | [773a0244a1](https://linux-hardware.org/?probe=773a0244a1) | Apr 06, 2023 |
| ASUSTek       | P8H61-M LX                  | [df6a8a3453](https://linux-hardware.org/?probe=df6a8a3453) | Apr 06, 2023 |
| Dell          | 04GJJT A00                  | [5c7df0085d](https://linux-hardware.org/?probe=5c7df0085d) | Apr 06, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | [4a0aa9f6d0](https://linux-hardware.org/?probe=4a0aa9f6d0) | Apr 06, 2023 |
| MSI           | J1800I                      | [983e4f18d4](https://linux-hardware.org/?probe=983e4f18d4) | Apr 06, 2023 |
| ASRock        | A320M-DVS R4.0              | [c6e30ff3cc](https://linux-hardware.org/?probe=c6e30ff3cc) | Apr 06, 2023 |
| Dell          | 0HD5W2 A01                  | [294131b150](https://linux-hardware.org/?probe=294131b150) | Apr 06, 2023 |
| ASRock        | H61M-DGS                    | [e2dd28ca36](https://linux-hardware.org/?probe=e2dd28ca36) | Apr 06, 2023 |
| Biostar       | G31D-M7                     | [9d1a5129bd](https://linux-hardware.org/?probe=9d1a5129bd) | Apr 06, 2023 |
| Gigabyte      | A320M-S2H-CF                | [e04829aef9](https://linux-hardware.org/?probe=e04829aef9) | Apr 06, 2023 |
| Gigabyte      | F2A55M-DS2                  | [fea5792a8b](https://linux-hardware.org/?probe=fea5792a8b) | Apr 06, 2023 |
| MSI           | A88XM-E35 V2                | [bf4c16404e](https://linux-hardware.org/?probe=bf4c16404e) | Apr 06, 2023 |
| ASUSTek       | PRIME B450M-A               | [122c9d0ae2](https://linux-hardware.org/?probe=122c9d0ae2) | Apr 06, 2023 |
| ASUSTek       | H170-PRO                    | [8756f8891c](https://linux-hardware.org/?probe=8756f8891c) | Apr 06, 2023 |
| ASUSTek       | A68HM-E                     | [0c9ae9bcd7](https://linux-hardware.org/?probe=0c9ae9bcd7) | Apr 06, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [9e99b4150b](https://linux-hardware.org/?probe=9e99b4150b) | Apr 06, 2023 |
| eMachines     | EL1352                      | [ccd83551e0](https://linux-hardware.org/?probe=ccd83551e0) | Apr 06, 2023 |
| ASUSTek       | P5B                         | [a2a4936e2c](https://linux-hardware.org/?probe=a2a4936e2c) | Apr 06, 2023 |
| Gigabyte      | Z690 UD DDR4                | [7644d4a8fa](https://linux-hardware.org/?probe=7644d4a8fa) | Apr 06, 2023 |
| Dell          | 0HHV7N A00                  | [73cc9e48a0](https://linux-hardware.org/?probe=73cc9e48a0) | Apr 06, 2023 |
| ASUSTek       | PRIME A320M-K               | [8b92d25f91](https://linux-hardware.org/?probe=8b92d25f91) | Apr 06, 2023 |
| Dell          | 0F5C5X A00                  | [0e0a176bf8](https://linux-hardware.org/?probe=0e0a176bf8) | Apr 06, 2023 |
| HP            | 830C                        | [ab6399decd](https://linux-hardware.org/?probe=ab6399decd) | Apr 06, 2023 |
| Dell          | 0GXM1W A02                  | [3fae5e4d5c](https://linux-hardware.org/?probe=3fae5e4d5c) | Apr 05, 2023 |
| Gigabyte      | B560 DS3H AC-Y1             | [0893f3016e](https://linux-hardware.org/?probe=0893f3016e) | Apr 05, 2023 |
| Gigabyte      | X570 GAMING X               | [83132b245e](https://linux-hardware.org/?probe=83132b245e) | Apr 05, 2023 |
| Dell          | 0HN7XN A01                  | [43469cea83](https://linux-hardware.org/?probe=43469cea83) | Apr 05, 2023 |
| MSI           | A320M-A PRO MAX             | [8c33d7498d](https://linux-hardware.org/?probe=8c33d7498d) | Apr 05, 2023 |
| HP            | 3397                        | [2c3fa64234](https://linux-hardware.org/?probe=2c3fa64234) | Apr 05, 2023 |
| Gigabyte      | H97-HD3                     | [caf5563d44](https://linux-hardware.org/?probe=caf5563d44) | Apr 05, 2023 |
| Acer          | Aspire XC-330               | [a0e2b31c08](https://linux-hardware.org/?probe=a0e2b31c08) | Apr 05, 2023 |
| Acer          | EG31M R01-C3                | [a548c9e661](https://linux-hardware.org/?probe=a548c9e661) | Apr 05, 2023 |
| ASRock        | A320M-DVS R4.0              | [6da0293a4b](https://linux-hardware.org/?probe=6da0293a4b) | Apr 05, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [0e7d453676](https://linux-hardware.org/?probe=0e7d453676) | Apr 05, 2023 |
| ASUSTek       | P5KPL-CM                    | [78c525b19b](https://linux-hardware.org/?probe=78c525b19b) | Apr 05, 2023 |
| Gigabyte      | F2A75M-HD2                  | [04694eb1f9](https://linux-hardware.org/?probe=04694eb1f9) | Apr 05, 2023 |
| MSI           | B150 PC MATE                | [da2d2d3d5c](https://linux-hardware.org/?probe=da2d2d3d5c) | Apr 05, 2023 |
| ASRock        | B450 Steel Legend           | [62bdbae29c](https://linux-hardware.org/?probe=62bdbae29c) | Apr 05, 2023 |
| HP            | 2AA2                        | [28c42fc95f](https://linux-hardware.org/?probe=28c42fc95f) | Apr 05, 2023 |
| ASRock        | B75 Pro3-M                  | [81b76a458e](https://linux-hardware.org/?probe=81b76a458e) | Apr 05, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [5881a47fd0](https://linux-hardware.org/?probe=5881a47fd0) | Apr 05, 2023 |
| Gigabyte      | GA-A75M-UD2H                | [7f4b812a58](https://linux-hardware.org/?probe=7f4b812a58) | Apr 05, 2023 |
| MSI           | Z97 GAMING 5                | [41a5c82c1e](https://linux-hardware.org/?probe=41a5c82c1e) | Apr 05, 2023 |
| Gigabyte      | B660M DS3H DDR4             | [59d486f5bd](https://linux-hardware.org/?probe=59d486f5bd) | Apr 05, 2023 |
| ASUSTek       | K30BF_M32BF_A_F_K31BF_6     | [4505cd8ddc](https://linux-hardware.org/?probe=4505cd8ddc) | Apr 05, 2023 |
| ASUSTek       | PRIME B360M-K               | [caa685db91](https://linux-hardware.org/?probe=caa685db91) | Apr 05, 2023 |
| ASUSTek       | PRIME Z370M-PLUS II         | [9fc5c6f8a7](https://linux-hardware.org/?probe=9fc5c6f8a7) | Apr 05, 2023 |
| Dell          | 0V8WGR A02                  | [3b8d266671](https://linux-hardware.org/?probe=3b8d266671) | Apr 05, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [540d1f11a6](https://linux-hardware.org/?probe=540d1f11a6) | Apr 05, 2023 |
| HP            | 18E5                        | [71c68a2c6a](https://linux-hardware.org/?probe=71c68a2c6a) | Apr 05, 2023 |
| ASRock        | H61MV-ITX                   | [c721707e0a](https://linux-hardware.org/?probe=c721707e0a) | Apr 05, 2023 |
| MSI           | MS-7529                     | [2c6cdf6397](https://linux-hardware.org/?probe=2c6cdf6397) | Apr 04, 2023 |
| ASUSTek       | P8Z77-I DELUXE              | [d8dc8a37b1](https://linux-hardware.org/?probe=d8dc8a37b1) | Apr 04, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [f43197a66f](https://linux-hardware.org/?probe=f43197a66f) | Apr 04, 2023 |
| ASUSTek       | A68HM-PLUS                  | [4246e4df2b](https://linux-hardware.org/?probe=4246e4df2b) | Apr 04, 2023 |
| Gigabyte      | GA-A75M-D2H                 | [9885a8adee](https://linux-hardware.org/?probe=9885a8adee) | Apr 04, 2023 |
| MSI           | Z390-A PRO                  | [60583d2cb0](https://linux-hardware.org/?probe=60583d2cb0) | Apr 04, 2023 |
| Acer          | Aspire M1470                | [d0120a6452](https://linux-hardware.org/?probe=d0120a6452) | Apr 04, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [1eae1b3796](https://linux-hardware.org/?probe=1eae1b3796) | Apr 04, 2023 |
| ASUSTek       | PRIME A320M-C R2.0          | [70b2a73996](https://linux-hardware.org/?probe=70b2a73996) | Apr 04, 2023 |
| Dell          | 040DDP A00                  | [af03c6afe4](https://linux-hardware.org/?probe=af03c6afe4) | Apr 04, 2023 |
| MSI           | B450-A PRO MAX              | [31d10a7e98](https://linux-hardware.org/?probe=31d10a7e98) | Apr 04, 2023 |
| Lenovo        | 3140 NOK                    | [207d400267](https://linux-hardware.org/?probe=207d400267) | Apr 04, 2023 |
| Fujitsu       | D3236-S1 S26361-D3236-S1    | [89962b2435](https://linux-hardware.org/?probe=89962b2435) | Apr 04, 2023 |
| ASUSTek       | A55BM-E                     | [3e174ff8a3](https://linux-hardware.org/?probe=3e174ff8a3) | Apr 04, 2023 |
| ECS           | Iris8                       | [f86927f9ff](https://linux-hardware.org/?probe=f86927f9ff) | Apr 04, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [e13bc4c0b8](https://linux-hardware.org/?probe=e13bc4c0b8) | Apr 04, 2023 |
| Intel         | B75                         | [8d116f68cf](https://linux-hardware.org/?probe=8d116f68cf) | Apr 04, 2023 |
| Dell          | 00F82W A00                  | [a78ce73463](https://linux-hardware.org/?probe=a78ce73463) | Apr 04, 2023 |
| Dell          | 0D6H9T A01                  | [dd49afbf3f](https://linux-hardware.org/?probe=dd49afbf3f) | Apr 04, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [8db8b523f3](https://linux-hardware.org/?probe=8db8b523f3) | Apr 04, 2023 |
| ASUSTek       | PRIME Q270M-C               | [a3d5910e8e](https://linux-hardware.org/?probe=a3d5910e8e) | Apr 04, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [f637374c21](https://linux-hardware.org/?probe=f637374c21) | Apr 03, 2023 |
| ASRock        | 990FX Extreme3              | [013cd9b246](https://linux-hardware.org/?probe=013cd9b246) | Apr 03, 2023 |
| Intel         | DZ87KLT75K AAG74721-304     | [4f97ce0a4b](https://linux-hardware.org/?probe=4f97ce0a4b) | Apr 03, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | [de861c6d3f](https://linux-hardware.org/?probe=de861c6d3f) | Apr 03, 2023 |
| ASRock        | FM2A68M-DG3+                | [47c6d88922](https://linux-hardware.org/?probe=47c6d88922) | Apr 03, 2023 |
| MSI           | H81M-E33                    | [34b04c305a](https://linux-hardware.org/?probe=34b04c305a) | Apr 03, 2023 |
| ASRock        | A55M-HVS                    | [426d150c30](https://linux-hardware.org/?probe=426d150c30) | Apr 03, 2023 |
| MSI           | 760GM-P23                   | [7c446415d8](https://linux-hardware.org/?probe=7c446415d8) | Apr 03, 2023 |
| Foxconn       | H67MP-S/-V/H67MP            | [08612f7258](https://linux-hardware.org/?probe=08612f7258) | Apr 03, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [65668a06ad](https://linux-hardware.org/?probe=65668a06ad) | Apr 03, 2023 |
| ASUSTek       | ROG STRIX Z590-A GAMING ... | [2cbd354a8f](https://linux-hardware.org/?probe=2cbd354a8f) | Apr 03, 2023 |
| Pegatron      | JESSE                       | [60c37e2dda](https://linux-hardware.org/?probe=60c37e2dda) | Apr 03, 2023 |
| Dell          | 09KPNV A00                  | [2296872799](https://linux-hardware.org/?probe=2296872799) | Apr 03, 2023 |
| Gigabyte      | B360M H                     | [cc5feeb3eb](https://linux-hardware.org/?probe=cc5feeb3eb) | Apr 03, 2023 |
| ASUSTek       | H61M-K                      | [f4b76d1e01](https://linux-hardware.org/?probe=f4b76d1e01) | Apr 03, 2023 |
| Gigabyte      | H61M-S2P                    | [6d808d8c4d](https://linux-hardware.org/?probe=6d808d8c4d) | Apr 03, 2023 |
| MSI           | B450M MORTAR MAX            | [53ace0533c](https://linux-hardware.org/?probe=53ace0533c) | Apr 03, 2023 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | [8566b9511a](https://linux-hardware.org/?probe=8566b9511a) | Apr 02, 2023 |
| Gigabyte      | B450 AORUS ELITE V2         | [07089aebf5](https://linux-hardware.org/?probe=07089aebf5) | Apr 02, 2023 |
| Lenovo        | ThinkCentre M91p 4518RH1    | [ead0ecfb3a](https://linux-hardware.org/?probe=ead0ecfb3a) | Apr 02, 2023 |
| MSI           | A88XM-E35                   | [fb40e13d92](https://linux-hardware.org/?probe=fb40e13d92) | Apr 02, 2023 |
| HP            | 2215                        | [9e43555613](https://linux-hardware.org/?probe=9e43555613) | Apr 02, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | [f9d9946012](https://linux-hardware.org/?probe=f9d9946012) | Apr 02, 2023 |
| ASRock        | Q1900M                      | [dfae44d3f6](https://linux-hardware.org/?probe=dfae44d3f6) | Apr 02, 2023 |
| ASUSTek       | Z97-K                       | [d56ea84c5f](https://linux-hardware.org/?probe=d56ea84c5f) | Apr 02, 2023 |
| Gigabyte      | GA-880GM-UD2H               | [f46913bb86](https://linux-hardware.org/?probe=f46913bb86) | Apr 02, 2023 |
| MSI           | H510M-A PRO                 | [f580fda8f1](https://linux-hardware.org/?probe=f580fda8f1) | Apr 02, 2023 |
| MSI           | FM2-A75IA-E53               | [f8092c0da9](https://linux-hardware.org/?probe=f8092c0da9) | Apr 02, 2023 |
| ASRock        | H81M-VG4 R2.0               | [f811a203a0](https://linux-hardware.org/?probe=f811a203a0) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [3a8d512ae4](https://linux-hardware.org/?probe=3a8d512ae4) | Apr 02, 2023 |
| MSI           | MPG Z590 GAMING CARBON W... | [d0006b7678](https://linux-hardware.org/?probe=d0006b7678) | Apr 02, 2023 |
| HP            | 2AF3                        | [fe33aa7257](https://linux-hardware.org/?probe=fe33aa7257) | Apr 02, 2023 |
| MSI           | A320M-A PRO MAX             | [54fbd647bc](https://linux-hardware.org/?probe=54fbd647bc) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [024be9ff96](https://linux-hardware.org/?probe=024be9ff96) | Apr 02, 2023 |
| Gigabyte      | H410M S2 V3                 | [b908036588](https://linux-hardware.org/?probe=b908036588) | Apr 02, 2023 |
| HP            | 3397                        | [04943f0d5f](https://linux-hardware.org/?probe=04943f0d5f) | Apr 02, 2023 |
| ASUSTek       | B150M-K D3                  | [08df6b50be](https://linux-hardware.org/?probe=08df6b50be) | Apr 02, 2023 |
| Dell          | 096JG8 A01                  | [d016e78eab](https://linux-hardware.org/?probe=d016e78eab) | Apr 02, 2023 |
| Acer          | Veriton X2632G V:1.0        | [f5eafafc96](https://linux-hardware.org/?probe=f5eafafc96) | Apr 02, 2023 |
| Dell          | 0GDG8Y A02                  | [83110b2400](https://linux-hardware.org/?probe=83110b2400) | Apr 02, 2023 |
| ULTRATOP      | C2017-LIVA-ZE               | [96d0c389b8](https://linux-hardware.org/?probe=96d0c389b8) | Apr 02, 2023 |
| Acer          | EQ45LM                      | [5bafe47784](https://linux-hardware.org/?probe=5bafe47784) | Apr 02, 2023 |
| Intel         | B75                         | [caad7f240a](https://linux-hardware.org/?probe=caad7f240a) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [7ccbfd0fd3](https://linux-hardware.org/?probe=7ccbfd0fd3) | Apr 02, 2023 |
| Dell          | 02YYK5 A01                  | [ecfba44652](https://linux-hardware.org/?probe=ecfba44652) | Apr 02, 2023 |
| Unknown       | Unknown                     | [089fc02d40](https://linux-hardware.org/?probe=089fc02d40) | Apr 01, 2023 |
| Nvidia        | MCP7A 2                     | [26ab83ffcb](https://linux-hardware.org/?probe=26ab83ffcb) | Apr 01, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | [d645276b0a](https://linux-hardware.org/?probe=d645276b0a) | Apr 01, 2023 |
| Acer          | RS880M05                    | [bddd902030](https://linux-hardware.org/?probe=bddd902030) | Apr 01, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [4f9739adf7](https://linux-hardware.org/?probe=4f9739adf7) | Apr 01, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | [b7848305ec](https://linux-hardware.org/?probe=b7848305ec) | Apr 01, 2023 |
| Gigabyte      | H410M DS2V                  | [67b081e859](https://linux-hardware.org/?probe=67b081e859) | Apr 01, 2023 |
| Gigabyte      | Z68X-UD4-B3                 | [79bcb88c5b](https://linux-hardware.org/?probe=79bcb88c5b) | Apr 01, 2023 |
| ASUSTek       | PRIME A320M-K               | [5919c1d671](https://linux-hardware.org/?probe=5919c1d671) | Apr 01, 2023 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | [217bb72a30](https://linux-hardware.org/?probe=217bb72a30) | Apr 01, 2023 |
| Biostar       | H61MLV                      | [db9714357e](https://linux-hardware.org/?probe=db9714357e) | Apr 01, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [b272d7b271](https://linux-hardware.org/?probe=b272d7b271) | Apr 01, 2023 |
| ASUSTek       | PRIME Z490-P                | [bbbfbb2dfc](https://linux-hardware.org/?probe=bbbfbb2dfc) | Apr 01, 2023 |
| Intel         | DB75EN AAG39650-303         | [50d4a766a6](https://linux-hardware.org/?probe=50d4a766a6) | Apr 01, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [3f218796ae](https://linux-hardware.org/?probe=3f218796ae) | Apr 01, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [5ef1391fb2](https://linux-hardware.org/?probe=5ef1391fb2) | Apr 01, 2023 |
| Lenovo        | 317E SDK0K17763 WIN 1801... | [a4cad34ac9](https://linux-hardware.org/?probe=a4cad34ac9) | Apr 01, 2023 |
| ASUSTek       | PRIME X470-PRO              | [96fcc41161](https://linux-hardware.org/?probe=96fcc41161) | Apr 01, 2023 |
| ASRock        | B450 Pro4 R2.0              | [046d59655e](https://linux-hardware.org/?probe=046d59655e) | Apr 01, 2023 |
| ASUSTek       | B250 MINING EXPERT          | [da86fa8f75](https://linux-hardware.org/?probe=da86fa8f75) | Apr 01, 2023 |
| MSI           | MEG X670E ACE               | [2b9356529f](https://linux-hardware.org/?probe=2b9356529f) | Apr 01, 2023 |
| Lenovo        | SHARKBAY NOK                | [091d2eda88](https://linux-hardware.org/?probe=091d2eda88) | Apr 01, 2023 |
| MSI           | MAG X570S TORPEDO MAX       | [664da8ff45](https://linux-hardware.org/?probe=664da8ff45) | Apr 01, 2023 |
| Gigabyte      | MZGLKDP-00                  | [c9427f4873](https://linux-hardware.org/?probe=c9427f4873) | Apr 01, 2023 |
| Gigabyte      | F2A78M-DS2                  | [0528b2df2b](https://linux-hardware.org/?probe=0528b2df2b) | Apr 01, 2023 |
| ASUSTek       | PRIME B350M-A               | [f8afb163dc](https://linux-hardware.org/?probe=f8afb163dc) | Apr 01, 2023 |
| ASRock        | B460M Pro4                  | [1f3b96d1a0](https://linux-hardware.org/?probe=1f3b96d1a0) | Apr 01, 2023 |
| Acer          | Aspire XC-780               | [206239c162](https://linux-hardware.org/?probe=206239c162) | Apr 01, 2023 |
| MSI           | H97M-G43                    | [b93caf26e4](https://linux-hardware.org/?probe=b93caf26e4) | Apr 01, 2023 |
| Fujitsu       | D3432-A1 S26361-D3432-A1    | [86241cd6ad](https://linux-hardware.org/?probe=86241cd6ad) | Apr 01, 2023 |
| HP            | 304Ah                       | [14d92e85a2](https://linux-hardware.org/?probe=14d92e85a2) | Apr 01, 2023 |
| HP            | 84FD                        | [79367d5f7d](https://linux-hardware.org/?probe=79367d5f7d) | Apr 01, 2023 |
| Gigabyte      | B450 AORUS M                | [c1a0385d07](https://linux-hardware.org/?probe=c1a0385d07) | Apr 01, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | [ad3ead1116](https://linux-hardware.org/?probe=ad3ead1116) | Apr 01, 2023 |
| ASUSTek       | PRIME A320M-K               | [16f87cd333](https://linux-hardware.org/?probe=16f87cd333) | Apr 01, 2023 |
| Gigabyte      | B360 AORUS GAMING 3-CF      | [f54ccba86f](https://linux-hardware.org/?probe=f54ccba86f) | Apr 01, 2023 |
| ASUSTek       | P8Z77-V PREMIUM             | [d774a892d1](https://linux-hardware.org/?probe=d774a892d1) | Apr 01, 2023 |
| Dell          | 0TTDMJ A00                  | [5d6606235d](https://linux-hardware.org/?probe=5d6606235d) | Apr 01, 2023 |
| Dell          | 0M5DCD A00                  | [91cc314380](https://linux-hardware.org/?probe=91cc314380) | Apr 01, 2023 |
| Gigabyte      | F2A88XM-HD3                 | [39bc576f7f](https://linux-hardware.org/?probe=39bc576f7f) | Apr 01, 2023 |
| HP            | 8053                        | [6c887800bb](https://linux-hardware.org/?probe=6c887800bb) | Apr 01, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [369bd03522](https://linux-hardware.org/?probe=369bd03522) | Apr 01, 2023 |
| Pegatron      | 2AC2                        | [ca0b0464d7](https://linux-hardware.org/?probe=ca0b0464d7) | Apr 01, 2023 |
| Dell          | 04YP6J A02                  | [0223f7bb3e](https://linux-hardware.org/?probe=0223f7bb3e) | Mar 31, 2023 |
| ECS           | GeForce 8000 series         | [32e951a2ca](https://linux-hardware.org/?probe=32e951a2ca) | Mar 31, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [9e09a54915](https://linux-hardware.org/?probe=9e09a54915) | Mar 31, 2023 |
| HP            | 2AFA                        | [d177838277](https://linux-hardware.org/?probe=d177838277) | Mar 31, 2023 |
| ASRock        | Z87 Extreme6                | [675d214cbe](https://linux-hardware.org/?probe=675d214cbe) | Mar 31, 2023 |
| Dell          | 0JP3NX A00                  | [016632c560](https://linux-hardware.org/?probe=016632c560) | Mar 31, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | [1ac381c18f](https://linux-hardware.org/?probe=1ac381c18f) | Mar 31, 2023 |
| MSI           | H81M-P33                    | [e2442d5cac](https://linux-hardware.org/?probe=e2442d5cac) | Mar 31, 2023 |
| Gigabyte      | Z77-DS3H                    | [79e2cfa0f1](https://linux-hardware.org/?probe=79e2cfa0f1) | Mar 31, 2023 |
| Fujitsu Si... | MS-7504VP-PV                | [32c138c982](https://linux-hardware.org/?probe=32c138c982) | Mar 31, 2023 |
| Gigabyte      | B250M-DS3H-CF               | [a025953f4c](https://linux-hardware.org/?probe=a025953f4c) | Mar 31, 2023 |
| Dell          | 0WMJ54 A00                  | [d11328af2a](https://linux-hardware.org/?probe=d11328af2a) | Mar 31, 2023 |
| MSI           | B550-A PRO                  | [ab4f36e0fa](https://linux-hardware.org/?probe=ab4f36e0fa) | Mar 31, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [c27e3be5ba](https://linux-hardware.org/?probe=c27e3be5ba) | Mar 31, 2023 |
| Wistron       | ProLiant ML110 G5           | [925759c41c](https://linux-hardware.org/?probe=925759c41c) | Mar 31, 2023 |
| Dell          | 0HMX8D A01                  | [36b8532260](https://linux-hardware.org/?probe=36b8532260) | Mar 31, 2023 |
| MSI           | Z270-A PRO                  | [a5d218b9a6](https://linux-hardware.org/?probe=a5d218b9a6) | Mar 31, 2023 |
| Gigabyte      | Z68XP-UD3                   | [029afd6a5c](https://linux-hardware.org/?probe=029afd6a5c) | Mar 31, 2023 |
| Fujitsu       | D3600-A1 S26361-D3600-A1    | [fc9a42e387](https://linux-hardware.org/?probe=fc9a42e387) | Mar 31, 2023 |
| ASUSTek       | TUF Z270 MARK 2             | [6bd60aa5f0](https://linux-hardware.org/?probe=6bd60aa5f0) | Mar 31, 2023 |
| ASUSTek       | P8Z77-V                     | [498726ce78](https://linux-hardware.org/?probe=498726ce78) | Mar 31, 2023 |
| Dell          | 042P49 A02                  | [46dc3b9655](https://linux-hardware.org/?probe=46dc3b9655) | Mar 31, 2023 |
| Medion        | MS-7728                     | [cf66e81623](https://linux-hardware.org/?probe=cf66e81623) | Mar 31, 2023 |
| ASUSTek       | H110M-R                     | [bd1a48e47d](https://linux-hardware.org/?probe=bd1a48e47d) | Mar 31, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [7a0f5608b2](https://linux-hardware.org/?probe=7a0f5608b2) | Mar 31, 2023 |
| ASRock        | Z97 Anniversary             | [c23aeb60ba](https://linux-hardware.org/?probe=c23aeb60ba) | Mar 31, 2023 |
| HP            | 3397                        | [5a25984320](https://linux-hardware.org/?probe=5a25984320) | Mar 31, 2023 |
| Gigabyte      | B85M-HD3                    | [3d24b75a10](https://linux-hardware.org/?probe=3d24b75a10) | Mar 31, 2023 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | [e84598d67c](https://linux-hardware.org/?probe=e84598d67c) | Mar 31, 2023 |
| Dell          | 00V62H A01                  | [05d42527df](https://linux-hardware.org/?probe=05d42527df) | Mar 31, 2023 |
| HP            | 1998                        | [c47c52dfc6](https://linux-hardware.org/?probe=c47c52dfc6) | Mar 31, 2023 |
| ASRock        | H61M                        | [29327171c4](https://linux-hardware.org/?probe=29327171c4) | Mar 31, 2023 |
| HP            | 8767 A                      | [186bad76b7](https://linux-hardware.org/?probe=186bad76b7) | Mar 31, 2023 |
| Gigabyte      | H310M A-CF                  | [c26786d423](https://linux-hardware.org/?probe=c26786d423) | Mar 31, 2023 |
| ASUSTek       | H97-PLUS                    | [5f163f6a24](https://linux-hardware.org/?probe=5f163f6a24) | Mar 31, 2023 |
| ASUSTek       | UN65U                       | [70d0f8f069](https://linux-hardware.org/?probe=70d0f8f069) | Mar 31, 2023 |
| Gigabyte      | EP43-DS3L                   | [b7594db73b](https://linux-hardware.org/?probe=b7594db73b) | Mar 31, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | [1fa3e0934f](https://linux-hardware.org/?probe=1fa3e0934f) | Mar 31, 2023 |
| ASUSTek       | PRIME J4005I-C              | [193d27ceac](https://linux-hardware.org/?probe=193d27ceac) | Mar 31, 2023 |
| MSI           | H110M PRO-VH PLUS           | [0992e2d8d8](https://linux-hardware.org/?probe=0992e2d8d8) | Mar 31, 2023 |
| OEM_MB        | NARRA3                      | [75050a4d2e](https://linux-hardware.org/?probe=75050a4d2e) | Mar 31, 2023 |
| ASUSTek       | M5A78L-M LX3                | [6ff0a3cb3f](https://linux-hardware.org/?probe=6ff0a3cb3f) | Mar 31, 2023 |
| Foxconn       | 2ABF                        | [8daf4bf0a5](https://linux-hardware.org/?probe=8daf4bf0a5) | Mar 30, 2023 |
| ASRock        | H310CM-HDV                  | [a9a41a38ed](https://linux-hardware.org/?probe=a9a41a38ed) | Mar 30, 2023 |
| ASUSTek       | PRIME A320M-K               | [3670f0a6ed](https://linux-hardware.org/?probe=3670f0a6ed) | Mar 30, 2023 |
| HP            | 843F                        | [862f573134](https://linux-hardware.org/?probe=862f573134) | Mar 30, 2023 |
| ASRock        | 970 Extreme3                | [906f9d6d04](https://linux-hardware.org/?probe=906f9d6d04) | Mar 30, 2023 |
| Gigabyte      | P41T-D3P                    | [c8cadc8a94](https://linux-hardware.org/?probe=c8cadc8a94) | Mar 30, 2023 |
| DFI           | LP UT X58                   | [cd706d90d3](https://linux-hardware.org/?probe=cd706d90d3) | Mar 30, 2023 |
| Gigabyte      | B250M-DS3H-CF               | [d72978731a](https://linux-hardware.org/?probe=d72978731a) | Mar 30, 2023 |
| MSI           | Z370-A PRO                  | [9aba047596](https://linux-hardware.org/?probe=9aba047596) | Mar 30, 2023 |
| Gigabyte      | A520 AORUS ELITE            | [f7f74305ba](https://linux-hardware.org/?probe=f7f74305ba) | Mar 30, 2023 |
| Intel         | B75A                        | [b7b1423f34](https://linux-hardware.org/?probe=b7b1423f34) | Mar 30, 2023 |
| Biostar       | B550MX/E PRO                | [cffcb0a2a6](https://linux-hardware.org/?probe=cffcb0a2a6) | Mar 30, 2023 |
| Gigabyte      | H410M S2H V2                | [cf13162657](https://linux-hardware.org/?probe=cf13162657) | Mar 30, 2023 |
| ASRock        | FM2A88X Extreme6+           | [ad1392d8c0](https://linux-hardware.org/?probe=ad1392d8c0) | Mar 30, 2023 |
| HP            | 82B4                        | [9712d04ab5](https://linux-hardware.org/?probe=9712d04ab5) | Mar 30, 2023 |
| Dell          | 0T7D40 A01                  | [dc44647f41](https://linux-hardware.org/?probe=dc44647f41) | Mar 30, 2023 |
| ASUSTek       | B85M-E                      | [7c7f9d0e36](https://linux-hardware.org/?probe=7c7f9d0e36) | Mar 30, 2023 |
| Packard Be... | FIH57                       | [f1336c6cc4](https://linux-hardware.org/?probe=f1336c6cc4) | Mar 30, 2023 |
| Pegatron      | 2ADC                        | [1326ad508e](https://linux-hardware.org/?probe=1326ad508e) | Mar 30, 2023 |
| Packard Be... | MCP73PV                     | [2082d90602](https://linux-hardware.org/?probe=2082d90602) | Mar 30, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [4ccaa78b43](https://linux-hardware.org/?probe=4ccaa78b43) | Mar 30, 2023 |
| MSI           | B450M BAZOOKA V2            | [7888e091f7](https://linux-hardware.org/?probe=7888e091f7) | Mar 30, 2023 |
| Gigabyte      | GA-880GA-UD3H               | [393fc00a5d](https://linux-hardware.org/?probe=393fc00a5d) | Mar 30, 2023 |
| Medion        | B250H4-EM                   | [f569d44749](https://linux-hardware.org/?probe=f569d44749) | Mar 30, 2023 |
| ASUSTek       | P8H77-V                     | [1869e23c56](https://linux-hardware.org/?probe=1869e23c56) | Mar 30, 2023 |
| MSI           | H97 PC Mate                 | [37c098e51a](https://linux-hardware.org/?probe=37c098e51a) | Mar 30, 2023 |
| Gigabyte      | Z390 UD                     | [558d551d9a](https://linux-hardware.org/?probe=558d551d9a) | Mar 30, 2023 |
| ASRock        | B85M Pro4                   | [d237bcc0a2](https://linux-hardware.org/?probe=d237bcc0a2) | Mar 30, 2023 |
| Gigabyte      | B75M-D3V                    | [d3ae118e3b](https://linux-hardware.org/?probe=d3ae118e3b) | Mar 30, 2023 |
| Shuttle       | FH270                       | [83c990d212](https://linux-hardware.org/?probe=83c990d212) | Mar 30, 2023 |
| MSI           | H81M-P33                    | [4606b5b93d](https://linux-hardware.org/?probe=4606b5b93d) | Mar 29, 2023 |
| Dell          | 042P49 A01                  | [9a4f4be1ab](https://linux-hardware.org/?probe=9a4f4be1ab) | Mar 29, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | [fb2605e6fa](https://linux-hardware.org/?probe=fb2605e6fa) | Mar 29, 2023 |
| Dell          | 0TP412                      | [f9f3e5cc04](https://linux-hardware.org/?probe=f9f3e5cc04) | Mar 29, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [599577c3b4](https://linux-hardware.org/?probe=599577c3b4) | Mar 29, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [3b7fe31c07](https://linux-hardware.org/?probe=3b7fe31c07) | Mar 29, 2023 |
| EPoX Compu... | nForce3 DDR: 8KDA7I Seri... | [38e3c2378c](https://linux-hardware.org/?probe=38e3c2378c) | Mar 29, 2023 |
| Dell          | 0T2HR0 A02                  | [bf959f65d2](https://linux-hardware.org/?probe=bf959f65d2) | Mar 29, 2023 |
| Gigabyte      | B550M DS3H                  | [612dd1dba2](https://linux-hardware.org/?probe=612dd1dba2) | Mar 29, 2023 |
| Lenovo        | 30D2 NOK                    | [e4d898e37d](https://linux-hardware.org/?probe=e4d898e37d) | Mar 29, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [634c2e1e74](https://linux-hardware.org/?probe=634c2e1e74) | Mar 29, 2023 |
| ASRock        | B450 Pro4                   | [c77fc70f0c](https://linux-hardware.org/?probe=c77fc70f0c) | Mar 29, 2023 |
| Acer          | Predator G3-605             | [8a1a55a1da](https://linux-hardware.org/?probe=8a1a55a1da) | Mar 29, 2023 |
| HP            | 0A60h                       | [6ad65f4f2b](https://linux-hardware.org/?probe=6ad65f4f2b) | Mar 28, 2023 |
| WinFast       | 6100M2MA FAB1.0             | [bed481b8ce](https://linux-hardware.org/?probe=bed481b8ce) | Mar 28, 2023 |
| HP            | 3047h                       | [c4f4f0c51d](https://linux-hardware.org/?probe=c4f4f0c51d) | Mar 28, 2023 |
| ASRock        | J5040-ITX                   | [799a14a5d5](https://linux-hardware.org/?probe=799a14a5d5) | Mar 28, 2023 |
| MSI           | B450-A PRO MAX              | [f3ebf80a3d](https://linux-hardware.org/?probe=f3ebf80a3d) | Mar 28, 2023 |
| Gigabyte      | H310M S2 x.x                | [21504643b4](https://linux-hardware.org/?probe=21504643b4) | Mar 28, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [4807db08a9](https://linux-hardware.org/?probe=4807db08a9) | Mar 28, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [ad5969356b](https://linux-hardware.org/?probe=ad5969356b) | Mar 28, 2023 |
| Gigabyte      | GA-780T-D3L                 | [4f523c6409](https://linux-hardware.org/?probe=4f523c6409) | Mar 28, 2023 |
| Lenovo        | 3178 SDK0J40700 WIN 3258... | [1c14b29af5](https://linux-hardware.org/?probe=1c14b29af5) | Mar 28, 2023 |
| Lenovo        | 36D9 SDK0J40700 WIN 3258... | [16db0eb166](https://linux-hardware.org/?probe=16db0eb166) | Mar 28, 2023 |
| ASUSTek       | P5G41T-M LX                 | [3f2f66842c](https://linux-hardware.org/?probe=3f2f66842c) | Mar 28, 2023 |
| Gigabyte      | H61M-S2P-R3                 | [428dc61d58](https://linux-hardware.org/?probe=428dc61d58) | Mar 28, 2023 |
| Dell          | 0R5KF8 A03                  | [decf0f5193](https://linux-hardware.org/?probe=decf0f5193) | Mar 28, 2023 |
| Gigabyte      | H55M-USB3                   | [140b984b9f](https://linux-hardware.org/?probe=140b984b9f) | Mar 28, 2023 |
| Lenovo        | NO DPK                      | [220c640743](https://linux-hardware.org/?probe=220c640743) | Mar 28, 2023 |
| MSI           | H87-G41 PC Mate             | [0d1345af82](https://linux-hardware.org/?probe=0d1345af82) | Mar 28, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | [8e7d5a0eb8](https://linux-hardware.org/?probe=8e7d5a0eb8) | Mar 28, 2023 |
| Lenovo        | ThinkStation S30 0568E8G    | [ea3855cca5](https://linux-hardware.org/?probe=ea3855cca5) | Mar 28, 2023 |
| Lenovo        | SHARKBAY 31900058 STD       | [5064a5267e](https://linux-hardware.org/?probe=5064a5267e) | Mar 28, 2023 |
| ASRock        | X470 Taichi                 | [79d0ee9715](https://linux-hardware.org/?probe=79d0ee9715) | Mar 28, 2023 |
| ASUSTek       | PRIME X570-P                | [8234cd55a8](https://linux-hardware.org/?probe=8234cd55a8) | Mar 28, 2023 |
| Intel         | H61                         | [56437a0e05](https://linux-hardware.org/?probe=56437a0e05) | Mar 28, 2023 |
| Gigabyte      | H61M-S1                     | [9af85c78cb](https://linux-hardware.org/?probe=9af85c78cb) | Mar 28, 2023 |
| Gigabyte      | A320M-H-CF                  | [6b4122e888](https://linux-hardware.org/?probe=6b4122e888) | Mar 28, 2023 |
| Lenovo        | 0x36A017AA SDK0J40709 WI... | [562426633d](https://linux-hardware.org/?probe=562426633d) | Mar 28, 2023 |
| ASUSTek       | Z170-P                      | [03e9908048](https://linux-hardware.org/?probe=03e9908048) | Mar 28, 2023 |
| Dell          | 0G261D A00                  | [f63f67f28f](https://linux-hardware.org/?probe=f63f67f28f) | Mar 28, 2023 |
| Acer          | Predator G3-605             | [8caea0f833](https://linux-hardware.org/?probe=8caea0f833) | Mar 27, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [face5f2ef3](https://linux-hardware.org/?probe=face5f2ef3) | Mar 27, 2023 |
| ASRock        | Z77 Extreme6                | [365cc196f2](https://linux-hardware.org/?probe=365cc196f2) | Mar 27, 2023 |
| Gigabyte      | Z370 AORUS Gaming 7         | [91a63afb10](https://linux-hardware.org/?probe=91a63afb10) | Mar 27, 2023 |
| Gigabyte      | B450M S2H                   | [0901eb1e27](https://linux-hardware.org/?probe=0901eb1e27) | Mar 27, 2023 |
| Lenovo        | 36C5 SDK0J40700 WIN 3258... | [8d039976c9](https://linux-hardware.org/?probe=8d039976c9) | Mar 27, 2023 |
| Pegatron      | 2AD5                        | [502ff745d4](https://linux-hardware.org/?probe=502ff745d4) | Mar 27, 2023 |
| ASUSTek       | PRIME Z590-P                | [ab55adbf68](https://linux-hardware.org/?probe=ab55adbf68) | Mar 27, 2023 |
| Gigabyte      | H81M-H                      | [709242697d](https://linux-hardware.org/?probe=709242697d) | Mar 27, 2023 |
| HP            | 1998                        | [82adc9926e](https://linux-hardware.org/?probe=82adc9926e) | Mar 27, 2023 |
| Dell          | 0G919G A00                  | [139207e1a7](https://linux-hardware.org/?probe=139207e1a7) | Mar 27, 2023 |
| Lenovo        | 102F NO DPK                 | [85a4bbf301](https://linux-hardware.org/?probe=85a4bbf301) | Mar 27, 2023 |
| ASUSTek       | P7H55                       | [40158bca43](https://linux-hardware.org/?probe=40158bca43) | Mar 27, 2023 |
| Gigabyte      | H310M H                     | [16ba0fa199](https://linux-hardware.org/?probe=16ba0fa199) | Mar 27, 2023 |
| Lenovo        | ThinkCentre M71e 3157AE2    | [a71ced0077](https://linux-hardware.org/?probe=a71ced0077) | Mar 27, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [bcd49e85cb](https://linux-hardware.org/?probe=bcd49e85cb) | Mar 27, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | [fa7272f576](https://linux-hardware.org/?probe=fa7272f576) | Mar 27, 2023 |
| ASRock        | A320M-HDV                   | [9685e81600](https://linux-hardware.org/?probe=9685e81600) | Mar 27, 2023 |
| Gigabyte      | H87M-D3H                    | [b277bc971f](https://linux-hardware.org/?probe=b277bc971f) | Mar 27, 2023 |
| Acer          | Veriton M4630G V:1.0        | [7fba52ef43](https://linux-hardware.org/?probe=7fba52ef43) | Mar 27, 2023 |
| ASUSTek       | P8Z77-V LK                  | [6b088adaf9](https://linux-hardware.org/?probe=6b088adaf9) | Mar 27, 2023 |
| Lenovo        | 36EB SDK0R32862 WIN 3258... | [943075edf7](https://linux-hardware.org/?probe=943075edf7) | Mar 27, 2023 |
| ASRock        | B450M Pro4                  | [a6bb6f959c](https://linux-hardware.org/?probe=a6bb6f959c) | Mar 27, 2023 |
| Unknown       | Unknown                     | [ecf55ab179](https://linux-hardware.org/?probe=ecf55ab179) | Mar 27, 2023 |
| Gigabyte      | G31M-ES2C                   | [fcd077e70a](https://linux-hardware.org/?probe=fcd077e70a) | Mar 27, 2023 |
| HP            | 844C                        | [8270d682a8](https://linux-hardware.org/?probe=8270d682a8) | Mar 27, 2023 |
| Unknown       | 1.0                         | [e09cc1385b](https://linux-hardware.org/?probe=e09cc1385b) | Mar 27, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | [8af0f96567](https://linux-hardware.org/?probe=8af0f96567) | Mar 27, 2023 |
| ASUSTek       | P8H61-MX R2.0               | [9064f6704d](https://linux-hardware.org/?probe=9064f6704d) | Mar 27, 2023 |
| ASUSTek       | Z97-K R2.0                  | [b1e1f4d711](https://linux-hardware.org/?probe=b1e1f4d711) | Mar 27, 2023 |
| MSI           | H410M PRO-C                 | [95cb5acf9e](https://linux-hardware.org/?probe=95cb5acf9e) | Mar 27, 2023 |
| Dell          | 01TJ2K A03                  | [f390eb34f6](https://linux-hardware.org/?probe=f390eb34f6) | Mar 27, 2023 |
| ASUSTek       | PRIME B450M-A               | [2077f4f3ab](https://linux-hardware.org/?probe=2077f4f3ab) | Mar 27, 2023 |
| HP            | 1998                        | [2d5e0737e5](https://linux-hardware.org/?probe=2d5e0737e5) | Mar 27, 2023 |
| ASUSTek       | M4A78-HTPC                  | [be398d5786](https://linux-hardware.org/?probe=be398d5786) | Mar 27, 2023 |
| HP            | 8704                        | [ab934a36cb](https://linux-hardware.org/?probe=ab934a36cb) | Mar 26, 2023 |
| Gigabyte      | B85M-HD3                    | [36c8e41310](https://linux-hardware.org/?probe=36c8e41310) | Mar 26, 2023 |
| Fujitsu Si... | MS-7504VP-PV                | [83448b2d9b](https://linux-hardware.org/?probe=83448b2d9b) | Mar 26, 2023 |
| ASUSTek       | PRIME A320M-K               | [8d0ef2d912](https://linux-hardware.org/?probe=8d0ef2d912) | Mar 26, 2023 |
| ASRock        | X300-ITX                    | [34402bbf9b](https://linux-hardware.org/?probe=34402bbf9b) | Mar 26, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | [8decb2b6c4](https://linux-hardware.org/?probe=8decb2b6c4) | Mar 26, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [bf08e5eecd](https://linux-hardware.org/?probe=bf08e5eecd) | Mar 26, 2023 |
| Medion        | P2A4-EM                     | [45e86dd60d](https://linux-hardware.org/?probe=45e86dd60d) | Mar 26, 2023 |
| ASUSTek       | P8H67                       | [3b9e638ecb](https://linux-hardware.org/?probe=3b9e638ecb) | Mar 26, 2023 |
| PCWare        | IPMH61R3                    | [2fbd1f3f64](https://linux-hardware.org/?probe=2fbd1f3f64) | Mar 26, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [b527095c8c](https://linux-hardware.org/?probe=b527095c8c) | Mar 26, 2023 |
| Chuwi         | RZBOX                       | [14ef8add03](https://linux-hardware.org/?probe=14ef8add03) | Mar 26, 2023 |
| ASUSTek       | PRIME H510M-K               | [54e2f18738](https://linux-hardware.org/?probe=54e2f18738) | Mar 26, 2023 |
| ASUSTek       | PRIME A520M-K               | [f01520e14a](https://linux-hardware.org/?probe=f01520e14a) | Mar 26, 2023 |
| Lenovo        | 30C7 SDK0J40700 WIN 3258... | [0730a39a3a](https://linux-hardware.org/?probe=0730a39a3a) | Mar 26, 2023 |
| Lenovo        | ThinkCentre M58p 6137A2U    | [cc740804d7](https://linux-hardware.org/?probe=cc740804d7) | Mar 25, 2023 |
| ASUSTek       | P8H77-M                     | [6fc56d2339](https://linux-hardware.org/?probe=6fc56d2339) | Mar 25, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | [e6219e18b1](https://linux-hardware.org/?probe=e6219e18b1) | Mar 25, 2023 |
| HP            | 8433 11                     | [1f76e1dc62](https://linux-hardware.org/?probe=1f76e1dc62) | Mar 25, 2023 |
| MSI           | A520M PRO                   | [c27ea21be5](https://linux-hardware.org/?probe=c27ea21be5) | Mar 25, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [3ce94dae13](https://linux-hardware.org/?probe=3ce94dae13) | Mar 25, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [76d02ffbf0](https://linux-hardware.org/?probe=76d02ffbf0) | Mar 25, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [227aba28f2](https://linux-hardware.org/?probe=227aba28f2) | Mar 25, 2023 |
| Dell          | 0654JC A01                  | [3771b8bf2e](https://linux-hardware.org/?probe=3771b8bf2e) | Mar 25, 2023 |
| Gigabyte      | F2A78M-HD2                  | [c7bf2c9968](https://linux-hardware.org/?probe=c7bf2c9968) | Mar 25, 2023 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [ca8bcc6073](https://linux-hardware.org/?probe=ca8bcc6073) | Mar 25, 2023 |
| Gigabyte      | H310N                       | [33a905038c](https://linux-hardware.org/?probe=33a905038c) | Mar 24, 2023 |
| HP            | 212A                        | [df28b0fdb0](https://linux-hardware.org/?probe=df28b0fdb0) | Mar 24, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [5c811e496f](https://linux-hardware.org/?probe=5c811e496f) | Mar 24, 2023 |
| Gigabyte      | M52S-S3P                    | [c9ac6eb940](https://linux-hardware.org/?probe=c9ac6eb940) | Mar 24, 2023 |
| Gigabyte      | H410M S2                    | [08b36ebc25](https://linux-hardware.org/?probe=08b36ebc25) | Mar 24, 2023 |
| Lenovo        | SDK0E50519 WIN              | [2fb6bb5874](https://linux-hardware.org/?probe=2fb6bb5874) | Mar 24, 2023 |
| Dell          | 0NK5PH A00                  | [f76bc64ee4](https://linux-hardware.org/?probe=f76bc64ee4) | Mar 24, 2023 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [b03324de35](https://linux-hardware.org/?probe=b03324de35) | Mar 24, 2023 |
| ASUSTek       | M4N98TD EVO                 | [9cb4b84924](https://linux-hardware.org/?probe=9cb4b84924) | Mar 24, 2023 |
| Intel         | HURONRIVER                  | [5bac43b2f0](https://linux-hardware.org/?probe=5bac43b2f0) | Mar 24, 2023 |
| ASUSTek       | GRYPHON Z87                 | [befbe47acc](https://linux-hardware.org/?probe=befbe47acc) | Mar 23, 2023 |
| HP            | 1497                        | [2238b69c99](https://linux-hardware.org/?probe=2238b69c99) | Mar 23, 2023 |
| Dell          | 0NDYHG A01                  | [93bc601af0](https://linux-hardware.org/?probe=93bc601af0) | Mar 23, 2023 |
| Biostar       | G41D3+                      | [ebb9a17568](https://linux-hardware.org/?probe=ebb9a17568) | Mar 23, 2023 |
| Gigabyte      | H61M-DS2                    | [fba2a4dffc](https://linux-hardware.org/?probe=fba2a4dffc) | Mar 23, 2023 |
| MSI           | MS-7255                     | [7322068101](https://linux-hardware.org/?probe=7322068101) | Mar 23, 2023 |
| Digiboard     | NM70-TI                     | [d654b9738a](https://linux-hardware.org/?probe=d654b9738a) | Mar 23, 2023 |
| ASRock        | H61M-HVGS                   | [5e9cf8fb44](https://linux-hardware.org/?probe=5e9cf8fb44) | Mar 22, 2023 |
| HP            | 339A                        | [a09a5bd5a9](https://linux-hardware.org/?probe=a09a5bd5a9) | Mar 22, 2023 |
| HP            | 802F                        | [89dadeeea6](https://linux-hardware.org/?probe=89dadeeea6) | Mar 22, 2023 |
| BESSTAR Te... | UM700                       | [32116dbba8](https://linux-hardware.org/?probe=32116dbba8) | Mar 21, 2023 |
| MSI           | B450M PRO-M2 MAX            | [bdfe7a3498](https://linux-hardware.org/?probe=bdfe7a3498) | Mar 21, 2023 |
| Dell          | 0NK70N A03                  | [7c5f606c7d](https://linux-hardware.org/?probe=7c5f606c7d) | Mar 21, 2023 |
| Gigabyte      | B75N                        | [8a16ffed3b](https://linux-hardware.org/?probe=8a16ffed3b) | Mar 21, 2023 |
| Dell          | 0C2KJT A00                  | [54bdc4bbd0](https://linux-hardware.org/?probe=54bdc4bbd0) | Mar 21, 2023 |
| Dell          | 0D441T A03                  | [926d18b722](https://linux-hardware.org/?probe=926d18b722) | Mar 20, 2023 |
| Gigabyte      | A520I AC                    | [a9e094374a](https://linux-hardware.org/?probe=a9e094374a) | Mar 20, 2023 |
| Gigabyte      | GA-990FX-GAMING             | [7f1e3cf271](https://linux-hardware.org/?probe=7f1e3cf271) | Mar 20, 2023 |
| Dell          | 0F6X5P A00                  | [258c8aa62c](https://linux-hardware.org/?probe=258c8aa62c) | Mar 20, 2023 |
| Acer          | Veriton M4610G              | [fed7efcecb](https://linux-hardware.org/?probe=fed7efcecb) | Mar 20, 2023 |
| Gigabyte      | Z68A-D3H-B3                 | [6c420d8fba](https://linux-hardware.org/?probe=6c420d8fba) | Mar 20, 2023 |
| Gigabyte      | P43-ES3G                    | [60a7dc4c2e](https://linux-hardware.org/?probe=60a7dc4c2e) | Mar 20, 2023 |
| Unknown       | Unknown                     | [dfcc73f24d](https://linux-hardware.org/?probe=dfcc73f24d) | Mar 20, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | [db3e17d5f1](https://linux-hardware.org/?probe=db3e17d5f1) | Mar 20, 2023 |
| ASUSTek       | PRIME B350M-A               | [9ee81ffe32](https://linux-hardware.org/?probe=9ee81ffe32) | Mar 20, 2023 |
| ASUSTek       | PRIME H510M-E               | [8c46e42391](https://linux-hardware.org/?probe=8c46e42391) | Mar 20, 2023 |
| ASRock        | 970A-G                      | [52b0aa69ba](https://linux-hardware.org/?probe=52b0aa69ba) | Mar 20, 2023 |
| HP            | 18E7                        | [9e4b5010d8](https://linux-hardware.org/?probe=9e4b5010d8) | Mar 20, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | [32d80303b6](https://linux-hardware.org/?probe=32d80303b6) | Mar 20, 2023 |
| HP            | 3646h                       | [812e12695b](https://linux-hardware.org/?probe=812e12695b) | Mar 19, 2023 |
| ASRock        | G31M-GS                     | [abef6c6862](https://linux-hardware.org/?probe=abef6c6862) | Mar 19, 2023 |
| ASUSTek       | M51BC                       | [65db0797b0](https://linux-hardware.org/?probe=65db0797b0) | Mar 19, 2023 |
| Gigabyte      | A520M H                     | [a3cee7c278](https://linux-hardware.org/?probe=a3cee7c278) | Mar 19, 2023 |
| Gigabyte      | 990FXA-UD5                  | [0daa99f732](https://linux-hardware.org/?probe=0daa99f732) | Mar 19, 2023 |
| ASUSTek       | P8H61-M LX PLUS             | [cdf57a039e](https://linux-hardware.org/?probe=cdf57a039e) | Mar 19, 2023 |
| HP            | 3397                        | [3f0b2c8e5b](https://linux-hardware.org/?probe=3f0b2c8e5b) | Mar 19, 2023 |
| Dell          | 0MM599                      | [df3a1bd31b](https://linux-hardware.org/?probe=df3a1bd31b) | Mar 18, 2023 |
| Intel         | H55                         | [2b6fdbe93c](https://linux-hardware.org/?probe=2b6fdbe93c) | Mar 18, 2023 |
| Gigabyte      | 970A-DS3P                   | [727e5c46b7](https://linux-hardware.org/?probe=727e5c46b7) | Mar 18, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [d8004fdcde](https://linux-hardware.org/?probe=d8004fdcde) | Mar 18, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [2a1291ac22](https://linux-hardware.org/?probe=2a1291ac22) | Mar 18, 2023 |
| Dell          | 07N90W A02                  | [267dad60ba](https://linux-hardware.org/?probe=267dad60ba) | Mar 18, 2023 |
| MSI           | H55M-P31                    | [e95e62df99](https://linux-hardware.org/?probe=e95e62df99) | Mar 18, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [b346ffbe8e](https://linux-hardware.org/?probe=b346ffbe8e) | Mar 18, 2023 |
| MSI           | MS-7360                     | [6c8cb5d98f](https://linux-hardware.org/?probe=6c8cb5d98f) | Mar 18, 2023 |
| HP            | 1589                        | [5c483a16fc](https://linux-hardware.org/?probe=5c483a16fc) | Mar 18, 2023 |
| Unknown       | Unknown                     | [d91eb1923c](https://linux-hardware.org/?probe=d91eb1923c) | Mar 17, 2023 |
| Medion        | H81H3-EM2 H81EM2W08.217     | [1e1a430355](https://linux-hardware.org/?probe=1e1a430355) | Mar 17, 2023 |
| Gigabyte      | G41MT-D3                    | [9a4ac88209](https://linux-hardware.org/?probe=9a4ac88209) | Mar 17, 2023 |
| Dell          | 0HN7XN A01                  | [4ce2092fe2](https://linux-hardware.org/?probe=4ce2092fe2) | Mar 17, 2023 |
| Gigabyte      | G41MT-S2P                   | [abb09d2f8e](https://linux-hardware.org/?probe=abb09d2f8e) | Mar 17, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | [452349c032](https://linux-hardware.org/?probe=452349c032) | Mar 17, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [0125449b9f](https://linux-hardware.org/?probe=0125449b9f) | Mar 17, 2023 |
| Dell          | 0T1D10 A01                  | [c640b09a8b](https://linux-hardware.org/?probe=c640b09a8b) | Mar 17, 2023 |
| Lenovo        | ThinkCentre A58 7522M4J     | [ba0a303be5](https://linux-hardware.org/?probe=ba0a303be5) | Mar 17, 2023 |
| ASUSTek       | P7H55-M PRO                 | [0c7a43b36b](https://linux-hardware.org/?probe=0c7a43b36b) | Mar 17, 2023 |
| Acer          | Batman A01                  | [0d7671ef18](https://linux-hardware.org/?probe=0d7671ef18) | Mar 17, 2023 |
| Fujitsu       | D3012-A1 S26361-D3012-A1    | [14c33dda50](https://linux-hardware.org/?probe=14c33dda50) | Mar 16, 2023 |
| ASUSTek       | P5W DH Deluxe               | [761d6accb1](https://linux-hardware.org/?probe=761d6accb1) | Mar 16, 2023 |
| Pegatron      | 2AB5                        | [7ab2e7b0ab](https://linux-hardware.org/?probe=7ab2e7b0ab) | Mar 16, 2023 |
| Gigabyte      | F2A68HM-DS2                 | [293b961af2](https://linux-hardware.org/?probe=293b961af2) | Mar 16, 2023 |
| ASUSTek       | CG5290                      | [e0ab58dbfe](https://linux-hardware.org/?probe=e0ab58dbfe) | Mar 16, 2023 |
| ASUSTek       | P5QPL-AM                    | [e89d2059c0](https://linux-hardware.org/?probe=e89d2059c0) | Mar 16, 2023 |
| Gigabyte      | F2A88XM-D3H                 | [c7a98e4c15](https://linux-hardware.org/?probe=c7a98e4c15) | Mar 16, 2023 |
| OEM           | B85 JHS359                  | [1d5d7e95fc](https://linux-hardware.org/?probe=1d5d7e95fc) | Mar 16, 2023 |
| HP            | 8299                        | [59417ae66d](https://linux-hardware.org/?probe=59417ae66d) | Mar 16, 2023 |
| Acer          | FIH57                       | [ee8c95f841](https://linux-hardware.org/?probe=ee8c95f841) | Mar 16, 2023 |
| Biostar       | A10N-8800E                  | [1f081ed675](https://linux-hardware.org/?probe=1f081ed675) | Mar 16, 2023 |
| HP            | 0B40h                       | [b26ab9fc5d](https://linux-hardware.org/?probe=b26ab9fc5d) | Mar 16, 2023 |
| Intel         | Unknown                     | [b4b73aafa0](https://linux-hardware.org/?probe=b4b73aafa0) | Mar 15, 2023 |
| ASUSTek       | P9X79-E WS                  | [e16021b874](https://linux-hardware.org/?probe=e16021b874) | Mar 15, 2023 |
| Pegatron      | 2ACF                        | [7e97ed3ca3](https://linux-hardware.org/?probe=7e97ed3ca3) | Mar 15, 2023 |
| ASUSTek       | VC62B                       | [9bf2d226a8](https://linux-hardware.org/?probe=9bf2d226a8) | Mar 15, 2023 |
| Gigabyte      | B550 VISION D-P             | [4707dc8ed6](https://linux-hardware.org/?probe=4707dc8ed6) | Mar 15, 2023 |
| PCWare        | IPX4105G Pro                | [f685771047](https://linux-hardware.org/?probe=f685771047) | Mar 15, 2023 |
| Dell          | 0773VG A00                  | [320dab99e7](https://linux-hardware.org/?probe=320dab99e7) | Mar 15, 2023 |
| ASUSTek       | M5A88-M                     | [4b1712febb](https://linux-hardware.org/?probe=4b1712febb) | Mar 15, 2023 |
| MSI           | H61M-P20                    | [8129a4f5a4](https://linux-hardware.org/?probe=8129a4f5a4) | Mar 15, 2023 |
| MSI           | FM2-A55M-E33                | [d6106fe9e3](https://linux-hardware.org/?probe=d6106fe9e3) | Mar 14, 2023 |
| ASRock        | A320M-HDV R4.0              | [723cb09007](https://linux-hardware.org/?probe=723cb09007) | Mar 14, 2023 |
| Packard Be... | IMEDIA S3840                | [b54abceafe](https://linux-hardware.org/?probe=b54abceafe) | Mar 14, 2023 |
| ASUSTek       | P5KR                        | [613bbd6934](https://linux-hardware.org/?probe=613bbd6934) | Mar 14, 2023 |
| ASRock        | G31M-S                      | [7672cc15a2](https://linux-hardware.org/?probe=7672cc15a2) | Mar 13, 2023 |
| ASUSTek       | B75M-A                      | [8ca3a8801d](https://linux-hardware.org/?probe=8ca3a8801d) | Mar 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | [05da6b812c](https://linux-hardware.org/?probe=05da6b812c) | Mar 13, 2023 |
| Pegatron      | 2AB6                        | [8feb2e38c0](https://linux-hardware.org/?probe=8feb2e38c0) | Mar 13, 2023 |
| ASUSTek       | PRIME H410M-A               | [1f67ba4519](https://linux-hardware.org/?probe=1f67ba4519) | Mar 13, 2023 |
| HP            | 8767 A                      | [1e76ecbaa7](https://linux-hardware.org/?probe=1e76ecbaa7) | Mar 12, 2023 |
| Gigabyte      | B85M-D3H-A                  | [4265744c52](https://linux-hardware.org/?probe=4265744c52) | Mar 12, 2023 |
| Dell          | 00V62H A01                  | [a45ebd1b85](https://linux-hardware.org/?probe=a45ebd1b85) | Mar 12, 2023 |
| HP            | 1998                        | [68d7c4350d](https://linux-hardware.org/?probe=68d7c4350d) | Mar 12, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [964377c32c](https://linux-hardware.org/?probe=964377c32c) | Mar 12, 2023 |
| Pegatron      | 2AC2                        | [a6084e8904](https://linux-hardware.org/?probe=a6084e8904) | Mar 11, 2023 |
| ASUSTek       | A88X-PLUS                   | [3624df5386](https://linux-hardware.org/?probe=3624df5386) | Mar 11, 2023 |
| ASUSTek       | PRIME Z270-P                | [8f2b6b3bc1](https://linux-hardware.org/?probe=8f2b6b3bc1) | Mar 11, 2023 |
| Gigabyte      | H81M-H                      | [fd3c999c22](https://linux-hardware.org/?probe=fd3c999c22) | Mar 11, 2023 |
| Gigabyte      | P55-UD3R                    | [e720741a00](https://linux-hardware.org/?probe=e720741a00) | Mar 11, 2023 |
| HP            | 8433 11                     | [51a4dbf83e](https://linux-hardware.org/?probe=51a4dbf83e) | Mar 11, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [c5950249eb](https://linux-hardware.org/?probe=c5950249eb) | Mar 11, 2023 |
| Gigabyte      | 970A-UD3P                   | [2da8e75f5c](https://linux-hardware.org/?probe=2da8e75f5c) | Mar 11, 2023 |
| ASUSTek       | P7P55D DELUXE               | [d2b402f3c0](https://linux-hardware.org/?probe=d2b402f3c0) | Mar 11, 2023 |
| MSI           | Z170-A PRO                  | [a83243223a](https://linux-hardware.org/?probe=a83243223a) | Mar 10, 2023 |
| MSI           | A68HM-E33 V2                | [7cad3dc309](https://linux-hardware.org/?probe=7cad3dc309) | Mar 10, 2023 |
| MSI           | G31TM-P21                   | [262750077e](https://linux-hardware.org/?probe=262750077e) | Mar 10, 2023 |
| HP            | 0AA0h                       | [f86f0bc187](https://linux-hardware.org/?probe=f86f0bc187) | Mar 10, 2023 |
| Dell          | 0G2DM9 A02                  | [e6d8fa1563](https://linux-hardware.org/?probe=e6d8fa1563) | Mar 10, 2023 |
| Acer          | Veriton X4640G V:1.1        | [dd3e15feee](https://linux-hardware.org/?probe=dd3e15feee) | Mar 10, 2023 |
| HP            | 1850                        | [1b56ff36d2](https://linux-hardware.org/?probe=1b56ff36d2) | Mar 10, 2023 |
| Gigabyte      | B450M DS3H-CF               | [bf4c797c87](https://linux-hardware.org/?probe=bf4c797c87) | Mar 10, 2023 |
| Inventec      | D CLASS A02                 | [b9e49da1f7](https://linux-hardware.org/?probe=b9e49da1f7) | Mar 10, 2023 |
| MSI           | 970A-G46                    | [322eb2bdf0](https://linux-hardware.org/?probe=322eb2bdf0) | Mar 09, 2023 |
| Fujitsu       | D2912-A1 S26361-D2912-A1    | [fcb5d30135](https://linux-hardware.org/?probe=fcb5d30135) | Mar 09, 2023 |
| ASRock        | H61M-ITX                    | [ab7e81c6ca](https://linux-hardware.org/?probe=ab7e81c6ca) | Mar 09, 2023 |
| ASRock        | A320M-DVS R4.0              | [8e02302d63](https://linux-hardware.org/?probe=8e02302d63) | Mar 09, 2023 |
| Gigabyte      | GA-M55PLUS-S3G              | [dfd0b3e3de](https://linux-hardware.org/?probe=dfd0b3e3de) | Mar 08, 2023 |
| ASUSTek       | P5W DH Deluxe               | [df3b5da4ce](https://linux-hardware.org/?probe=df3b5da4ce) | Mar 08, 2023 |
| Lenovo        | MAHOBAY                     | [c756678fad](https://linux-hardware.org/?probe=c756678fad) | Mar 08, 2023 |
| ASUSTek       | B85M-G                      | [70f4bed81b](https://linux-hardware.org/?probe=70f4bed81b) | Mar 08, 2023 |
| Lenovo        | 3102 SDK0K13476 WIN 3306... | [b1a69ac03b](https://linux-hardware.org/?probe=b1a69ac03b) | Mar 08, 2023 |
| ECS           | MCP61PM-GM                  | [ac561937e3](https://linux-hardware.org/?probe=ac561937e3) | Mar 08, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [971feb34e4](https://linux-hardware.org/?probe=971feb34e4) | Mar 07, 2023 |
| Dell          | 0T1D10 A01                  | [ef67915ff3](https://linux-hardware.org/?probe=ef67915ff3) | Mar 07, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [c5809ffd96](https://linux-hardware.org/?probe=c5809ffd96) | Mar 07, 2023 |
| Gigabyte      | B450M DS3H-CF               | [c6f9f5a58d](https://linux-hardware.org/?probe=c6f9f5a58d) | Mar 06, 2023 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | [349f7731c8](https://linux-hardware.org/?probe=349f7731c8) | Mar 06, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [0c133c161b](https://linux-hardware.org/?probe=0c133c161b) | Mar 06, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [98f8bd8557](https://linux-hardware.org/?probe=98f8bd8557) | Mar 06, 2023 |
| ASUSTek       | PRIME A320M-K               | [38cb86265f](https://linux-hardware.org/?probe=38cb86265f) | Mar 06, 2023 |
| ASUSTek       | M5A97 R2.0                  | [0cda9f83b1](https://linux-hardware.org/?probe=0cda9f83b1) | Mar 06, 2023 |
| Gigabyte      | P35-DS3L                    | [31aeecfcb9](https://linux-hardware.org/?probe=31aeecfcb9) | Mar 06, 2023 |
| ASUSTek       | PRIME X370-PRO              | [9b72e94139](https://linux-hardware.org/?probe=9b72e94139) | Mar 06, 2023 |
| ASUSTek       | M5A78L-M LE/USB3            | [2891c31951](https://linux-hardware.org/?probe=2891c31951) | Mar 06, 2023 |
| MSI           | H110M PRO-VH PLUS           | [e4e66a8215](https://linux-hardware.org/?probe=e4e66a8215) | Mar 06, 2023 |
| Dell          | 06D7TR A00                  | [375809fb93](https://linux-hardware.org/?probe=375809fb93) | Mar 06, 2023 |
| Dell          | 0VRWRC A00                  | [4810cd01e3](https://linux-hardware.org/?probe=4810cd01e3) | Mar 06, 2023 |
| HP            | 212A                        | [faacd553af](https://linux-hardware.org/?probe=faacd553af) | Mar 06, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [c89683aeed](https://linux-hardware.org/?probe=c89683aeed) | Mar 06, 2023 |
| Gigabyte      | B450M GAMING                | [168b8db115](https://linux-hardware.org/?probe=168b8db115) | Mar 06, 2023 |
| Gigabyte      | B450M S2H V2                | [a2242be67c](https://linux-hardware.org/?probe=a2242be67c) | Mar 05, 2023 |
| Gigabyte      | H370 HD3-CF                 | [30365cbef7](https://linux-hardware.org/?probe=30365cbef7) | Mar 05, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [91fc2d53f8](https://linux-hardware.org/?probe=91fc2d53f8) | Mar 05, 2023 |
| MSI           | MS-6702E                    | [e17662e6c0](https://linux-hardware.org/?probe=e17662e6c0) | Mar 05, 2023 |
| HP            | 18E5                        | [969462a8a0](https://linux-hardware.org/?probe=969462a8a0) | Mar 05, 2023 |
| Lenovo        | ThinkCentre XXXX 739527G    | [c3e39b21f9](https://linux-hardware.org/?probe=c3e39b21f9) | Mar 05, 2023 |
| ASRock        | A300M-STX                   | [d920a52e51](https://linux-hardware.org/?probe=d920a52e51) | Mar 05, 2023 |
| Gigabyte      | MZBAYAP-00                  | [b090a8b795](https://linux-hardware.org/?probe=b090a8b795) | Mar 05, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [92b81bb3a1](https://linux-hardware.org/?probe=92b81bb3a1) | Mar 05, 2023 |
| ASUSTek       | H110M-A/M.2                 | [3c4bf3c1bd](https://linux-hardware.org/?probe=3c4bf3c1bd) | Mar 05, 2023 |
| ASUSTek       | H81M-E                      | [fc1a09013d](https://linux-hardware.org/?probe=fc1a09013d) | Mar 05, 2023 |
| ASUSTek       | P8H61-M LX3 R2.0            | [17da5ff761](https://linux-hardware.org/?probe=17da5ff761) | Mar 05, 2023 |
| Gigabyte      | Z370M D3H-CF                | [d000dc6718](https://linux-hardware.org/?probe=d000dc6718) | Mar 04, 2023 |
| Gigabyte      | A320M-S2H-CF                | [b531e1a7a8](https://linux-hardware.org/?probe=b531e1a7a8) | Mar 04, 2023 |
| Gigabyte      | G31M-ES2C                   | [5358a49423](https://linux-hardware.org/?probe=5358a49423) | Mar 04, 2023 |
| ASUSTek       | P7P55D                      | [1c2701a81c](https://linux-hardware.org/?probe=1c2701a81c) | Mar 04, 2023 |
| PCWare        | APM-A320G                   | [2bc24b8935](https://linux-hardware.org/?probe=2bc24b8935) | Mar 04, 2023 |
| Dell          | 084J0R A00                  | [dcde5e81ed](https://linux-hardware.org/?probe=dcde5e81ed) | Mar 04, 2023 |
| ASUSTek       | P8H67                       | [99008935e9](https://linux-hardware.org/?probe=99008935e9) | Mar 04, 2023 |
| Gigabyte      | GA-E7AUM-DS2H               | [825b26708c](https://linux-hardware.org/?probe=825b26708c) | Mar 04, 2023 |
| Gigabyte      | B85M-DS3H-A                 | [914a9990c4](https://linux-hardware.org/?probe=914a9990c4) | Mar 04, 2023 |
| Dell          | 0PC5F7 A03                  | [0f0a0b4911](https://linux-hardware.org/?probe=0f0a0b4911) | Mar 03, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | [6b3d496b96](https://linux-hardware.org/?probe=6b3d496b96) | Mar 03, 2023 |
| ASUSTek       | PRIME B450M-A II            | [ac3640b913](https://linux-hardware.org/?probe=ac3640b913) | Mar 03, 2023 |
| Gigabyte      | B450M DS3H-CF               | [84e37e870d](https://linux-hardware.org/?probe=84e37e870d) | Mar 03, 2023 |
| ASRock        | Z68 Extreme7 Gen3           | [133f8a8bef](https://linux-hardware.org/?probe=133f8a8bef) | Mar 03, 2023 |
| Foxconn       | 2A8C                        | [1cf53baf99](https://linux-hardware.org/?probe=1cf53baf99) | Mar 03, 2023 |
| Intel         | DH61WW AAG23116-204         | [c9b32e7136](https://linux-hardware.org/?probe=c9b32e7136) | Mar 03, 2023 |
| Gigabyte      | A520M DS3H                  | [f3defb812b](https://linux-hardware.org/?probe=f3defb812b) | Mar 03, 2023 |
| Gigabyte      | H55M-S2H                    | [196ff8d0dc](https://linux-hardware.org/?probe=196ff8d0dc) | Mar 03, 2023 |
| ASUSTek       | PRIME A520M-K               | [3be3c8d79d](https://linux-hardware.org/?probe=3be3c8d79d) | Mar 03, 2023 |
| ASUSTek       | PRIME B250M-K               | [e9b7260885](https://linux-hardware.org/?probe=e9b7260885) | Mar 03, 2023 |
| HP            | 8062                        | [b3adfec9fb](https://linux-hardware.org/?probe=b3adfec9fb) | Mar 03, 2023 |
| ASUSTek       | M2N68-AM SE2                | [f4292f5622](https://linux-hardware.org/?probe=f4292f5622) | Mar 03, 2023 |
| Intel         | DB75EN AAG39650-302         | [e828686fc3](https://linux-hardware.org/?probe=e828686fc3) | Mar 03, 2023 |
| ASUSTek       | Z97-PRO GAMER               | [1da5b61697](https://linux-hardware.org/?probe=1da5b61697) | Mar 02, 2023 |
| HP            | 8053                        | [c48153fe6d](https://linux-hardware.org/?probe=c48153fe6d) | Mar 02, 2023 |
| Dell          | 0KC9NP A00                  | [45397750b4](https://linux-hardware.org/?probe=45397750b4) | Mar 02, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | [41d9c3d9ed](https://linux-hardware.org/?probe=41d9c3d9ed) | Mar 02, 2023 |
| ASRock        | 970A-G                      | [4a8ff8612a](https://linux-hardware.org/?probe=4a8ff8612a) | Mar 02, 2023 |
| ASUSTek       | PRIME H410M-E               | [9cd0a2ea25](https://linux-hardware.org/?probe=9cd0a2ea25) | Mar 01, 2023 |
| Foxconn       | 2ABF                        | [9e63190b6f](https://linux-hardware.org/?probe=9e63190b6f) | Mar 01, 2023 |
| ASRock        | N68C-GS FX                  | [d36a0aa45c](https://linux-hardware.org/?probe=d36a0aa45c) | Mar 01, 2023 |
| ASUSTek       | PRIME B450M-K II            | [203ab85b69](https://linux-hardware.org/?probe=203ab85b69) | Mar 01, 2023 |
| HP            | 3396                        | [2da0f889cb](https://linux-hardware.org/?probe=2da0f889cb) | Mar 01, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [903b322b17](https://linux-hardware.org/?probe=903b322b17) | Mar 01, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [4e701d495f](https://linux-hardware.org/?probe=4e701d495f) | Mar 01, 2023 |
| ASUSTek       | F2A85-V PRO                 | [aa7d308d7e](https://linux-hardware.org/?probe=aa7d308d7e) | Mar 01, 2023 |
| ASRock        | B650E PG Riptide WiFi       | [a637650ff7](https://linux-hardware.org/?probe=a637650ff7) | Mar 01, 2023 |
| Gigabyte      | GA-880GA-UD3H               | [483db5a7bd](https://linux-hardware.org/?probe=483db5a7bd) | Feb 28, 2023 |
| ASRock        | 760GM-HDV                   | [c420a55609](https://linux-hardware.org/?probe=c420a55609) | Feb 28, 2023 |
| Acer          | Aspire X3995                | [eccac5b752](https://linux-hardware.org/?probe=eccac5b752) | Feb 28, 2023 |
| Fujitsu       | D2990-A3 S26361-D2990-A3    | [6f1de5f17c](https://linux-hardware.org/?probe=6f1de5f17c) | Feb 28, 2023 |
| ASUSTek       | PRIME B250-PRO              | [cd58d8a863](https://linux-hardware.org/?probe=cd58d8a863) | Feb 28, 2023 |
| HP            | 18E7                        | [a4fb4affcf](https://linux-hardware.org/?probe=a4fb4affcf) | Feb 28, 2023 |
| HP            | 87D6 SMVB                   | [423aac2b6f](https://linux-hardware.org/?probe=423aac2b6f) | Feb 28, 2023 |
| ASUSTek       | PRIME B550M-A               | [a6af4042ea](https://linux-hardware.org/?probe=a6af4042ea) | Feb 28, 2023 |
| ASUSTek       | P8B75-V                     | [cf4c7357eb](https://linux-hardware.org/?probe=cf4c7357eb) | Feb 28, 2023 |
| ASUSTek       | B150M-C                     | [e675a40455](https://linux-hardware.org/?probe=e675a40455) | Feb 28, 2023 |
| ASRock        | A320M-HDV                   | [5ba575539c](https://linux-hardware.org/?probe=5ba575539c) | Feb 28, 2023 |
| Foxconn       | G31MX Series                | [79ee8e5da3](https://linux-hardware.org/?probe=79ee8e5da3) | Feb 28, 2023 |
| ASUSTek       | PRIME H370-PLUS             | [43afa90be1](https://linux-hardware.org/?probe=43afa90be1) | Feb 28, 2023 |
| Intel         | DG41RQ AAE54511-205         | [0cf17a3787](https://linux-hardware.org/?probe=0cf17a3787) | Feb 27, 2023 |
| ASUSTek       | AM1I-A                      | [b5fe605f8b](https://linux-hardware.org/?probe=b5fe605f8b) | Feb 27, 2023 |
| ASUSTek       | M4N68T-M-V2                 | [051b66987e](https://linux-hardware.org/?probe=051b66987e) | Feb 27, 2023 |
| MSI           | B450M MORTAR MAX            | [0335729036](https://linux-hardware.org/?probe=0335729036) | Feb 27, 2023 |
| Intel         | H61                         | [b61ef1ed65](https://linux-hardware.org/?probe=b61ef1ed65) | Feb 27, 2023 |
| MSI           | NF750-G55                   | [f279251ffa](https://linux-hardware.org/?probe=f279251ffa) | Feb 27, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [8fc8fee94a](https://linux-hardware.org/?probe=8fc8fee94a) | Feb 27, 2023 |
| Unknown       | HX90                        | [bc8bed9135](https://linux-hardware.org/?probe=bc8bed9135) | Feb 27, 2023 |
| MSI           | A320M PRO-VH                | [e1266ebf79](https://linux-hardware.org/?probe=e1266ebf79) | Feb 27, 2023 |
| Lenovo        | 3098 SDK0E50510 WIN         | [f15e5303f6](https://linux-hardware.org/?probe=f15e5303f6) | Feb 27, 2023 |
| Acer          | EG43M                       | [d533c457eb](https://linux-hardware.org/?probe=d533c457eb) | Feb 26, 2023 |
| ASUSTek       | M5A78L                      | [693582be4e](https://linux-hardware.org/?probe=693582be4e) | Feb 26, 2023 |
| ASUSTek       | PRIME Q270M-C               | [edf748dbbb](https://linux-hardware.org/?probe=edf748dbbb) | Feb 26, 2023 |
| HP            | 3032h                       | [007bbeffa0](https://linux-hardware.org/?probe=007bbeffa0) | Feb 26, 2023 |
| ASRock        | A320M-HDV R4.0              | [319e003280](https://linux-hardware.org/?probe=319e003280) | Feb 26, 2023 |
| Gigabyte      | M68M-S2P                    | [15b2fe94ae](https://linux-hardware.org/?probe=15b2fe94ae) | Feb 26, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [724039adf2](https://linux-hardware.org/?probe=724039adf2) | Feb 26, 2023 |
| Lenovo        | 102F SDK0J40705 WIN 3425... | [484e0755de](https://linux-hardware.org/?probe=484e0755de) | Feb 26, 2023 |
| ASRock        | H110M-HG4                   | [0a5dfbb9e6](https://linux-hardware.org/?probe=0a5dfbb9e6) | Feb 26, 2023 |
| ASRock        | 960GM-VGS3 FX               | [66ea6164bf](https://linux-hardware.org/?probe=66ea6164bf) | Feb 25, 2023 |
| Dell          | 0YJHYD A00                  | [5029039f0e](https://linux-hardware.org/?probe=5029039f0e) | Feb 25, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [782598981d](https://linux-hardware.org/?probe=782598981d) | Feb 25, 2023 |
| Dell          | 0YF8P5 A00                  | [b387faf4ee](https://linux-hardware.org/?probe=b387faf4ee) | Feb 25, 2023 |
| ASRock        | H67M-GE/HT                  | [3410887193](https://linux-hardware.org/?probe=3410887193) | Feb 25, 2023 |
| HP            | 18E7                        | [7b52dfac52](https://linux-hardware.org/?probe=7b52dfac52) | Feb 25, 2023 |
| ASUSTek       | H81M-E                      | [25a3002df1](https://linux-hardware.org/?probe=25a3002df1) | Feb 25, 2023 |
| Gigabyte      | G31M-S2L                    | [563101d2b2](https://linux-hardware.org/?probe=563101d2b2) | Feb 25, 2023 |
| MSI           | 970A GAMING PRO CARBON      | [0649eea8a9](https://linux-hardware.org/?probe=0649eea8a9) | Feb 25, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [d6fea43eb5](https://linux-hardware.org/?probe=d6fea43eb5) | Feb 25, 2023 |
| Dell          | 0T1D10 A01                  | [87f49d1c7e](https://linux-hardware.org/?probe=87f49d1c7e) | Feb 25, 2023 |
| ASRock        | FM2A58M-VG3+ R2.0           | [92ac86c31b](https://linux-hardware.org/?probe=92ac86c31b) | Feb 25, 2023 |
| Unknown       | 1.0                         | [69594c956a](https://linux-hardware.org/?probe=69594c956a) | Feb 25, 2023 |
| Dell          | 088DT1 A01                  | [129ed2a520](https://linux-hardware.org/?probe=129ed2a520) | Feb 25, 2023 |
| Dell          | 0VHWTR A01                  | [ab8247e106](https://linux-hardware.org/?probe=ab8247e106) | Feb 24, 2023 |
| MSI           | B360M PRO-VH                | [fad0bd20e1](https://linux-hardware.org/?probe=fad0bd20e1) | Feb 24, 2023 |
| ASUSTek       | P5B                         | [60cb8319db](https://linux-hardware.org/?probe=60cb8319db) | Feb 24, 2023 |
| ASUSTek       | P5QL PRO                    | [c7477f1aca](https://linux-hardware.org/?probe=c7477f1aca) | Feb 24, 2023 |
| ASUSTek       | B150M-A D3                  | [01caadaee0](https://linux-hardware.org/?probe=01caadaee0) | Feb 24, 2023 |
| MSI           | G41M-P33 Combo              | [91c8d45121](https://linux-hardware.org/?probe=91c8d45121) | Feb 24, 2023 |
| ASUSTek       | M4A77T/USB3                 | [6bf574175a](https://linux-hardware.org/?probe=6bf574175a) | Feb 24, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [9171567db4](https://linux-hardware.org/?probe=9171567db4) | Feb 24, 2023 |
| ASUSTek       | P8H61-M LX R2.0             | [b410c9f493](https://linux-hardware.org/?probe=b410c9f493) | Feb 24, 2023 |
| ASUSTek       | A68HM-K                     | [5c7e454884](https://linux-hardware.org/?probe=5c7e454884) | Feb 24, 2023 |
| HP            | 1998                        | [145c009f05](https://linux-hardware.org/?probe=145c009f05) | Feb 24, 2023 |
| ASUSTek       | M2N-MX SE Plus              | [21aa20cd64](https://linux-hardware.org/?probe=21aa20cd64) | Feb 24, 2023 |
| ASRock        | A88M-G                      | [917526ad4d](https://linux-hardware.org/?probe=917526ad4d) | Feb 24, 2023 |
| ASRock        | H81M-HDS                    | [d4a6916e4f](https://linux-hardware.org/?probe=d4a6916e4f) | Feb 24, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | [2a8b727725](https://linux-hardware.org/?probe=2a8b727725) | Feb 24, 2023 |
| ASRock        | 990FX Killer                | [acfa772cc6](https://linux-hardware.org/?probe=acfa772cc6) | Feb 24, 2023 |
| Gigabyte      | B85M-HD3 R4                 | [db83755f3f](https://linux-hardware.org/?probe=db83755f3f) | Feb 24, 2023 |
| Gigabyte      | Z97-HD3                     | [016a51a4af](https://linux-hardware.org/?probe=016a51a4af) | Feb 23, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [bf6fc4a9d6](https://linux-hardware.org/?probe=bf6fc4a9d6) | Feb 23, 2023 |
| MSI           | X370 GAMING PLUS            | [4d45d5880b](https://linux-hardware.org/?probe=4d45d5880b) | Feb 23, 2023 |
| MSI           | H110M PRO-VH PLUS           | [de05d0d3f6](https://linux-hardware.org/?probe=de05d0d3f6) | Feb 23, 2023 |
| ASUSTek       | P5K                         | [f564dd9ac5](https://linux-hardware.org/?probe=f564dd9ac5) | Feb 23, 2023 |
| Gigabyte      | G1.Sniper A88X-CF           | [cfe5ecec44](https://linux-hardware.org/?probe=cfe5ecec44) | Feb 23, 2023 |
| Gigabyte      | H61M-S1                     | [ca76e62a1e](https://linux-hardware.org/?probe=ca76e62a1e) | Feb 23, 2023 |
| ASUSTek       | H61M-K                      | [9d39d13682](https://linux-hardware.org/?probe=9d39d13682) | Feb 23, 2023 |
| Biostar       | N68S3B                      | [4572b3d965](https://linux-hardware.org/?probe=4572b3d965) | Feb 23, 2023 |
| ASRock        | N68-VGS3 FX                 | [b9fbaca53d](https://linux-hardware.org/?probe=b9fbaca53d) | Feb 23, 2023 |
| Foxconn       | 2ADA                        | [75b2eb9c1f](https://linux-hardware.org/?probe=75b2eb9c1f) | Feb 23, 2023 |
| Biostar       | B450MH                      | [7bd9274f23](https://linux-hardware.org/?probe=7bd9274f23) | Feb 23, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | [fd084cb513](https://linux-hardware.org/?probe=fd084cb513) | Feb 23, 2023 |
| ASRock        | B450M Pro4                  | [ccd3d2932f](https://linux-hardware.org/?probe=ccd3d2932f) | Feb 22, 2023 |
| ASUSTek       | A_F_K20CE                   | [2dffc350dd](https://linux-hardware.org/?probe=2dffc350dd) | Feb 22, 2023 |
| ASRock        | B660M Pro RS                | [13560ab66d](https://linux-hardware.org/?probe=13560ab66d) | Feb 22, 2023 |
| Gigabyte      | H81M-S2PV                   | [ad365efca1](https://linux-hardware.org/?probe=ad365efca1) | Feb 22, 2023 |
| Gigabyte      | X570 GAMING X               | [4803e8ee01](https://linux-hardware.org/?probe=4803e8ee01) | Feb 22, 2023 |
| ASUSTek       | P8Z68-V PRO GEN3            | [ad957d0b05](https://linux-hardware.org/?probe=ad957d0b05) | Feb 22, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [2d36b57c9c](https://linux-hardware.org/?probe=2d36b57c9c) | Feb 22, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [9523a0ccc2](https://linux-hardware.org/?probe=9523a0ccc2) | Feb 22, 2023 |
| MSI           | GF615M-P33                  | [c9cad5f4fa](https://linux-hardware.org/?probe=c9cad5f4fa) | Feb 22, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [186b84313d](https://linux-hardware.org/?probe=186b84313d) | Feb 22, 2023 |
| ASUSTek       | PRIME X399-A                | [bfe434ab92](https://linux-hardware.org/?probe=bfe434ab92) | Feb 22, 2023 |
| ASRock        | Z690 Extreme                | [16e67a28e4](https://linux-hardware.org/?probe=16e67a28e4) | Feb 22, 2023 |
| ASUSTek       | M2NPV-MX                    | [06d857e2ff](https://linux-hardware.org/?probe=06d857e2ff) | Feb 22, 2023 |
| ASUSTek       | AM1M-A/BR                   | [d1c356a1c7](https://linux-hardware.org/?probe=d1c356a1c7) | Feb 21, 2023 |
| ASUSTek       | M5A78L/USB3                 | [b4288b76ee](https://linux-hardware.org/?probe=b4288b76ee) | Feb 21, 2023 |
| ASUSTek       | P5Q-E                       | [1fd091bff9](https://linux-hardware.org/?probe=1fd091bff9) | Feb 21, 2023 |
| MSI           | Z170A XPOWER GAMING TITA... | [b644019f77](https://linux-hardware.org/?probe=b644019f77) | Feb 21, 2023 |
| Gigabyte      | H410M S2 V3                 | [b517bb25cc](https://linux-hardware.org/?probe=b517bb25cc) | Feb 21, 2023 |
| MSI           | H510M-A PRO                 | [bbef057c8f](https://linux-hardware.org/?probe=bbef057c8f) | Feb 21, 2023 |
| MSI           | A88XI AC V2                 | [42c0cd5d37](https://linux-hardware.org/?probe=42c0cd5d37) | Feb 21, 2023 |
| Dell          | 02YYK5 A00                  | [cff33d0b1e](https://linux-hardware.org/?probe=cff33d0b1e) | Feb 20, 2023 |
| ASUSTek       | PRIME Z390-P                | [d81ff5358a](https://linux-hardware.org/?probe=d81ff5358a) | Feb 20, 2023 |
| MSI           | G41M-P23                    | [04211b9202](https://linux-hardware.org/?probe=04211b9202) | Feb 20, 2023 |
| ASRock        | AM1B-MH                     | [d67d348d90](https://linux-hardware.org/?probe=d67d348d90) | Feb 20, 2023 |
| ASUSTek       | Z97-K                       | [59931c7434](https://linux-hardware.org/?probe=59931c7434) | Feb 20, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | [119e106d80](https://linux-hardware.org/?probe=119e106d80) | Feb 20, 2023 |
| Gigabyte      | Z270N-WIFI-CF               | [32ed66a6f9](https://linux-hardware.org/?probe=32ed66a6f9) | Feb 20, 2023 |
| Gigabyte      | G31M-ES2L                   | [7415192b86](https://linux-hardware.org/?probe=7415192b86) | Feb 20, 2023 |
| Gigabyte      | GA-78LMT-S2                 | [29758ea823](https://linux-hardware.org/?probe=29758ea823) | Feb 20, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [576314ab03](https://linux-hardware.org/?probe=576314ab03) | Feb 20, 2023 |
| Gigabyte      | B560M DS3H                  | [72891de86c](https://linux-hardware.org/?probe=72891de86c) | Feb 20, 2023 |
| MSI           | X370 GAMING PLUS            | [a180732a9f](https://linux-hardware.org/?probe=a180732a9f) | Feb 19, 2023 |
| ASRock        | 880GM-LE FX                 | [db290cd703](https://linux-hardware.org/?probe=db290cd703) | Feb 19, 2023 |
| Dell          | 0C27VV A00                  | [1b522f9105](https://linux-hardware.org/?probe=1b522f9105) | Feb 19, 2023 |
| Acer          | G43T-AM3                    | [5ec1aa8af7](https://linux-hardware.org/?probe=5ec1aa8af7) | Feb 19, 2023 |
| Acer          | EG43M                       | [080dfdf76f](https://linux-hardware.org/?probe=080dfdf76f) | Feb 19, 2023 |
| ASRock        | X300M-STX                   | [f689e279bc](https://linux-hardware.org/?probe=f689e279bc) | Feb 19, 2023 |
| ASUSTek       | G10AC                       | [8a367bb885](https://linux-hardware.org/?probe=8a367bb885) | Feb 19, 2023 |
| Biostar       | A520MH                      | [ebdd012874](https://linux-hardware.org/?probe=ebdd012874) | Feb 19, 2023 |
| Gigabyte      | B75M-D2V                    | [fe04dfeaac](https://linux-hardware.org/?probe=fe04dfeaac) | Feb 19, 2023 |
| Gigabyte      | B460 AORUS PRO AC           | [dc6b25dcef](https://linux-hardware.org/?probe=dc6b25dcef) | Feb 19, 2023 |
| Acer          | H57M01                      | [5e5e9d03a4](https://linux-hardware.org/?probe=5e5e9d03a4) | Feb 19, 2023 |
| MSI           | Z97M GAMING                 | [e983a3704e](https://linux-hardware.org/?probe=e983a3704e) | Feb 19, 2023 |
| ASUSTek       | PRIME B560M-A               | [0a015cdb94](https://linux-hardware.org/?probe=0a015cdb94) | Feb 18, 2023 |
| ASRock        | AB350 Pro4                  | [908d615f00](https://linux-hardware.org/?probe=908d615f00) | Feb 18, 2023 |
| Gigabyte      | GA-MA785GMT-UD2H            | [c67a2ae3c5](https://linux-hardware.org/?probe=c67a2ae3c5) | Feb 18, 2023 |
| Gigabyte      | P31-ES3G                    | [2c3eb25bc4](https://linux-hardware.org/?probe=2c3eb25bc4) | Feb 18, 2023 |
| ASUSTek       | STRIX X99 GAMING            | [8dd1992835](https://linux-hardware.org/?probe=8dd1992835) | Feb 18, 2023 |
| ASRock        | 880GM-LE FX                 | [1d45a444a3](https://linux-hardware.org/?probe=1d45a444a3) | Feb 18, 2023 |
| Gigabyte      | G31M-S2L                    | [78e184862a](https://linux-hardware.org/?probe=78e184862a) | Feb 17, 2023 |
| ASUSTek       | P5G41T-M LX2/GB             | [da12f4a29b](https://linux-hardware.org/?probe=da12f4a29b) | Feb 17, 2023 |
| Foxconn       | H67M-S/H67M-V/H67M          | [78dc1c5856](https://linux-hardware.org/?probe=78dc1c5856) | Feb 17, 2023 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [3ed988e135](https://linux-hardware.org/?probe=3ed988e135) | Feb 17, 2023 |
| ASRock        | B450M Pro4-F R2.0           | [f1082dcffa](https://linux-hardware.org/?probe=f1082dcffa) | Feb 17, 2023 |
| Gigabyte      | A320M-S2H-CF                | [b4b87d47fb](https://linux-hardware.org/?probe=b4b87d47fb) | Feb 17, 2023 |
| Gigabyte      | H87M-HD3                    | [778b7898e3](https://linux-hardware.org/?probe=778b7898e3) | Feb 17, 2023 |
| AOpen         | iBDWMt-WBOP R1.00H 55WB3... | [c524d923e6](https://linux-hardware.org/?probe=c524d923e6) | Feb 17, 2023 |
| ASUSTek       | Rampage Formula             | [61fd1aefee](https://linux-hardware.org/?probe=61fd1aefee) | Feb 17, 2023 |
| EVGA          | 151-IB-E699                 | [9e975c7966](https://linux-hardware.org/?probe=9e975c7966) | Feb 17, 2023 |
| ASUSTek       | P8Z77-V                     | [f8dca6a264](https://linux-hardware.org/?probe=f8dca6a264) | Feb 17, 2023 |
| ASRock        | FM2A58M-VG3+ R2.0           | [27501ca342](https://linux-hardware.org/?probe=27501ca342) | Feb 17, 2023 |
| Hardkernel    | ODROID-H2                   | [0b85baa5ee](https://linux-hardware.org/?probe=0b85baa5ee) | Feb 17, 2023 |
| Pegatron      | IPM31G                      | [42d112d7e0](https://linux-hardware.org/?probe=42d112d7e0) | Feb 17, 2023 |
| Acer          | Veriton M4610G              | [7c5f2f584e](https://linux-hardware.org/?probe=7c5f2f584e) | Feb 17, 2023 |
| Gigabyte      | GA-MA790X-UD3P              | [8efdbecd75](https://linux-hardware.org/?probe=8efdbecd75) | Feb 17, 2023 |
| HP            | 2820h                       | [552bdc9930](https://linux-hardware.org/?probe=552bdc9930) | Feb 17, 2023 |
| MSI           | B450-A PRO MAX              | [92901492fc](https://linux-hardware.org/?probe=92901492fc) | Feb 16, 2023 |
| ASRock        | J3355M                      | [9118f960dd](https://linux-hardware.org/?probe=9118f960dd) | Feb 16, 2023 |
| Gigabyte      | EP35-DS4                    | [00d960f926](https://linux-hardware.org/?probe=00d960f926) | Feb 16, 2023 |
| MSI           | H61M-E33                    | [f0c902ce04](https://linux-hardware.org/?probe=f0c902ce04) | Feb 16, 2023 |
| MSI           | A78M-E35                    | [30c75db366](https://linux-hardware.org/?probe=30c75db366) | Feb 16, 2023 |
| HP            | 1495                        | [6bc4b54027](https://linux-hardware.org/?probe=6bc4b54027) | Feb 16, 2023 |
| ASUSTek       | M4N68T-M LE                 | [7b5fe965fd](https://linux-hardware.org/?probe=7b5fe965fd) | Feb 16, 2023 |
| MSI           | Z97-G45 GAMING              | [c6a7d3a755](https://linux-hardware.org/?probe=c6a7d3a755) | Feb 16, 2023 |
| Gigabyte      | MZAPLBP-00                  | [b043125d6e](https://linux-hardware.org/?probe=b043125d6e) | Feb 16, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [92a61cd4ee](https://linux-hardware.org/?probe=92a61cd4ee) | Feb 16, 2023 |
| Gigabyte      | GA-MA790XT-UD4P             | [3ce39f40e7](https://linux-hardware.org/?probe=3ce39f40e7) | Feb 16, 2023 |
| MSI           | B350M PRO-VD PLUS           | [63789621e0](https://linux-hardware.org/?probe=63789621e0) | Feb 16, 2023 |
| Lenovo        | ThinkCentre M91 4518E4S     | [91b1fb7e03](https://linux-hardware.org/?probe=91b1fb7e03) | Feb 16, 2023 |
| Dell          | 03NVJ6 A00                  | [d118fe4ba2](https://linux-hardware.org/?probe=d118fe4ba2) | Feb 16, 2023 |
| Philco        | DTC-A55                     | [e957b8f1cf](https://linux-hardware.org/?probe=e957b8f1cf) | Feb 16, 2023 |
| Foxconn       | 2ABF                        | [41f9974254](https://linux-hardware.org/?probe=41f9974254) | Feb 16, 2023 |
| Gigabyte      | F2A78M-HD2                  | [9f9cc6f9e2](https://linux-hardware.org/?probe=9f9cc6f9e2) | Feb 16, 2023 |
| MSI           | Z170A KRAIT GAMING 3X       | [8e521a2efc](https://linux-hardware.org/?probe=8e521a2efc) | Feb 16, 2023 |
| ASUSTek       | P5G41T-M LE                 | [3ebf4858b8](https://linux-hardware.org/?probe=3ebf4858b8) | Feb 16, 2023 |
| ASUSTek       | H81T                        | [51aa090e9a](https://linux-hardware.org/?probe=51aa090e9a) | Feb 16, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [e927a19203](https://linux-hardware.org/?probe=e927a19203) | Feb 16, 2023 |
| HP            | 3031h                       | [2b0cc2bd6e](https://linux-hardware.org/?probe=2b0cc2bd6e) | Feb 16, 2023 |
| ASUSTek       | P5K                         | [7767ce777f](https://linux-hardware.org/?probe=7767ce777f) | Feb 16, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [b19c73e236](https://linux-hardware.org/?probe=b19c73e236) | Feb 15, 2023 |
| MSI           | B450M PRO-M2                | [eb1d201d1c](https://linux-hardware.org/?probe=eb1d201d1c) | Feb 15, 2023 |
| HP            | 1494                        | [fd47ccde98](https://linux-hardware.org/?probe=fd47ccde98) | Feb 15, 2023 |
| MSI           | MS-7235                     | [519f3742a3](https://linux-hardware.org/?probe=519f3742a3) | Feb 15, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [5b6ce8f332](https://linux-hardware.org/?probe=5b6ce8f332) | Feb 15, 2023 |
| Gigabyte      | H410M H V3                  | [59f88fb4d0](https://linux-hardware.org/?probe=59f88fb4d0) | Feb 15, 2023 |
| BESSTAR Te... | DMAF5 V1.0                  | [af47a30d6a](https://linux-hardware.org/?probe=af47a30d6a) | Feb 15, 2023 |
| HP            | 8434 11                     | [2f4023e5f3](https://linux-hardware.org/?probe=2f4023e5f3) | Feb 15, 2023 |
| Dell          | 0NK5PH A00                  | [5455b577db](https://linux-hardware.org/?probe=5455b577db) | Feb 15, 2023 |
| Gigabyte      | P43-ES3G                    | [528ffce1c7](https://linux-hardware.org/?probe=528ffce1c7) | Feb 15, 2023 |
| ASUSTek       | PRIME B365M-K               | [20b88dda19](https://linux-hardware.org/?probe=20b88dda19) | Feb 15, 2023 |
| Gigabyte      | G41MT-D3V                   | [8a7ce6b005](https://linux-hardware.org/?probe=8a7ce6b005) | Feb 15, 2023 |
| HP            | 8433 11                     | [3f4ea738b6](https://linux-hardware.org/?probe=3f4ea738b6) | Feb 15, 2023 |
| Dell          | 0GXM1W A00                  | [3ab6d305fc](https://linux-hardware.org/?probe=3ab6d305fc) | Feb 15, 2023 |
| MSI           | Z68MA-ED55                  | [e2bd6f0fb4](https://linux-hardware.org/?probe=e2bd6f0fb4) | Feb 15, 2023 |
| Dell          | 0MGK50 A02                  | [43bd1ca5e1](https://linux-hardware.org/?probe=43bd1ca5e1) | Feb 15, 2023 |
| HP            | 0AA8h                       | [e7bbc5903b](https://linux-hardware.org/?probe=e7bbc5903b) | Feb 15, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | [a572ac5ed3](https://linux-hardware.org/?probe=a572ac5ed3) | Feb 15, 2023 |
| MSI           | MPG B550 GAMING CARBON W... | [f0d6ada218](https://linux-hardware.org/?probe=f0d6ada218) | Feb 15, 2023 |
| ASUSTek       | PRIME X399-A                | [0676daa5b0](https://linux-hardware.org/?probe=0676daa5b0) | Feb 14, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | [b30e6a84c8](https://linux-hardware.org/?probe=b30e6a84c8) | Feb 14, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ac367ae940](https://linux-hardware.org/?probe=ac367ae940) | Feb 14, 2023 |
| Gigabyte      | H55M-USB3                   | [08b959d9ec](https://linux-hardware.org/?probe=08b959d9ec) | Feb 14, 2023 |
| Medion        | MS-7800                     | [7827888ac6](https://linux-hardware.org/?probe=7827888ac6) | Feb 14, 2023 |
| HP            | 3396                        | [fbff77d7cc](https://linux-hardware.org/?probe=fbff77d7cc) | Feb 14, 2023 |
| MSI           | H310M PRO-D                 | [ce2d236a2d](https://linux-hardware.org/?probe=ce2d236a2d) | Feb 14, 2023 |
| HP            | ProLiant ML310e Gen8 v2     | [3569214674](https://linux-hardware.org/?probe=3569214674) | Feb 14, 2023 |
| MSI           | Z97-G45 GAMING              | [f9318d4390](https://linux-hardware.org/?probe=f9318d4390) | Feb 14, 2023 |
| Gigabyte      | B450M S2H                   | [eb04bfdc84](https://linux-hardware.org/?probe=eb04bfdc84) | Feb 14, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | [49f47896e6](https://linux-hardware.org/?probe=49f47896e6) | Feb 14, 2023 |
| Gigabyte      | H87-D3H-CF                  | [2914a1866d](https://linux-hardware.org/?probe=2914a1866d) | Feb 14, 2023 |
| Gigabyte      | Z68X-UD3H-B3                | [0ad0fe310f](https://linux-hardware.org/?probe=0ad0fe310f) | Feb 14, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/OpenMandriva/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| OpenMandriva 4.2    | 2261     | 35.74%  |
| OpenMandriva 4.3    | 2041     | 32.26%  |
| OpenMandriva 23.01  | 882      | 13.94%  |
| OpenMandriva 23.03  | 501      | 7.92%   |
| OpenMandriva 4.50   | 406      | 6.42%   |
| OpenMandriva 4.90   | 155      | 2.45%   |
| OpenMandriva 22.12  | 43       | 0.68%   |
| OpenMandriva 23.90  | 16       | 0.25%   |
| OpenMandriva 4.1    | 10       | 0.16%   |
| OpenMandriva 22.11  | 5        | 0.08%   |
| OpenMandriva 2014.0 | 3        | 0.05%   |
| OpenMandriva 4.0    | 2        | 0.03%   |
| OpenMandriva 4.0.1  | 1        | 0.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| OpenMandriva | 6039     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Desktops | Percent |
|--------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002       | 2193     | 34.36%  |
| 5.16.7-desktop-1omv4003        | 1926     | 30.17%  |
| 6.1.1-desktop-1omv2290         | 797      | 12.49%  |
| 6.2.6-desktop-1omv2390         | 467      | 7.32%   |
| 5.12.4-desktop-1omv4050        | 205      | 3.21%   |
| 5.18.12-desktop-3omv4090       | 144      | 2.26%   |
| 5.16.13-desktop-1omv4003       | 129      | 2.02%   |
| 5.11.12-desktop-1omv4002       | 88       | 1.38%   |
| 5.19.5-desktop-1omv4090        | 79       | 1.24%   |
| 6.1.4-desktop-1omv2301         | 72       | 1.13%   |
| 5.19.12-desktop-2omv4090       | 54       | 0.85%   |
| 6.0.10-desktop-2omv22090       | 42       | 0.66%   |
| 5.14.7-desktop-1omv4050        | 22       | 0.34%   |
| 6.2.2-desktop-1omv2390         | 19       | 0.3%    |
| 6.2.1-desktop-1omv2390         | 11       | 0.17%   |
| 5.19.11-desktop-2omv4090       | 10       | 0.16%   |
| 5.12.7-desktop-1omv4003        | 10       | 0.16%   |
| 5.5.12-desktop-1omv4001        | 9        | 0.14%   |
| 5.14.14-desktop-1omv4050       | 8        | 0.13%   |
| 6.1.2-desktop-1omv2301         | 7        | 0.11%   |
| 6.2.0-desktop-0.rc2.1omv2301   | 5        | 0.08%   |
| 6.1.11-desktop-1omv2390        | 5        | 0.08%   |
| 5.11.0-desktop-clang-1omv4002  | 5        | 0.08%   |
| 5.10.13-desktop-1omv4002       | 5        | 0.08%   |
| 5.17.1-desktop-2omv4050        | 4        | 0.06%   |
| 5.16.3-desktop-2omv4050        | 4        | 0.06%   |
| 6.2.8-desktop-1omv2390         | 3        | 0.05%   |
| 5.19.0-desktop-1omv4090        | 3        | 0.05%   |
| 6.1.9-desktop-1omv2390         | 2        | 0.03%   |
| 6.1.4-desktop-gcc-1omv2301     | 2        | 0.03%   |
| 5.18.9-desktop-gcc-1omv4090    | 2        | 0.03%   |
| 5.17.7-desktop-1omv4090        | 2        | 0.03%   |
| 5.16.5-desktop-2omv4003        | 2        | 0.03%   |
| 5.13.2-desktop-clang-1omv4050  | 2        | 0.03%   |
| 5.12.7-desktop-clang-1omv4003  | 2        | 0.03%   |
| 5.11.11-desktop-clang-1omv4050 | 2        | 0.03%   |
| 4.1.12-nrj-server-1omv         | 2        | 0.03%   |
| 6.3.0-desktop-1omv2390         | 1        | 0.02%   |
| 6.2.0-desktop-0.rc8.1omv2390   | 1        | 0.02%   |
| 6.1.8-desktop-1omv2390         | 1        | 0.02%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.14 | 2193     | 34.36%  |
| 5.16.7  | 1927     | 30.19%  |
| 6.1.1   | 797      | 12.49%  |
| 6.2.6   | 467      | 7.32%   |
| 5.12.4  | 205      | 3.21%   |
| 5.18.12 | 144      | 2.26%   |
| 5.16.13 | 130      | 2.04%   |
| 5.11.12 | 88       | 1.38%   |
| 5.19.5  | 79       | 1.24%   |
| 6.1.4   | 74       | 1.16%   |
| 5.19.12 | 55       | 0.86%   |
| 6.0.10  | 42       | 0.66%   |
| 5.14.7  | 22       | 0.34%   |
| 6.2.2   | 19       | 0.3%    |
| 5.12.7  | 12       | 0.19%   |
| 6.2.1   | 11       | 0.17%   |
| 5.19.11 | 11       | 0.17%   |
| 5.5.12  | 9        | 0.14%   |
| 5.14.14 | 8        | 0.13%   |
| 6.1.2   | 7        | 0.11%   |
| 6.2.0   | 6        | 0.09%   |
| 6.1.11  | 5        | 0.08%   |
| 5.11.0  | 5        | 0.08%   |
| 5.10.13 | 5        | 0.08%   |
| 5.17.1  | 4        | 0.06%   |
| 5.16.3  | 4        | 0.06%   |
| 6.2.8   | 3        | 0.05%   |
| 6.0.9   | 3        | 0.05%   |
| 6.0.0   | 3        | 0.05%   |
| 5.19.0  | 3        | 0.05%   |
| 5.16.5  | 3        | 0.05%   |
| 5.13.2  | 3        | 0.05%   |
| 6.1.9   | 2        | 0.03%   |
| 5.18.9  | 2        | 0.03%   |
| 5.17.7  | 2        | 0.03%   |
| 5.11.11 | 2        | 0.03%   |
| 4.1.12  | 2        | 0.03%   |
| 6.3.0   | 1        | 0.02%   |
| 6.1.8   | 1        | 0.02%   |
| 6.1.5   | 1        | 0.02%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 2202     | 34.64%  |
| 5.16    | 2041     | 32.11%  |
| 6.1     | 887      | 13.95%  |
| 6.2     | 506      | 7.96%   |
| 5.12    | 221      | 3.48%   |
| 5.19    | 150      | 2.36%   |
| 5.18    | 148      | 2.33%   |
| 5.11    | 95       | 1.49%   |
| 6.0     | 49       | 0.77%   |
| 5.14    | 31       | 0.49%   |
| 5.5     | 10       | 0.16%   |
| 5.17    | 6        | 0.09%   |
| 5.13    | 3        | 0.05%   |
| 4.1     | 3        | 0.05%   |
| 5.1     | 2        | 0.03%   |
| 6.3     | 1        | 0.02%   |
| 5.8     | 1        | 0.02%   |
| 5.3     | 1        | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 6039     | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| KDE5     | 5828     | 96.03%  |
| GNOME    | 175      | 2.88%   |
| LXQt     | 42       | 0.69%   |
| Unknown  | 11       | 0.18%   |
| Budgie   | 6        | 0.1%    |
| Cinnamon | 3        | 0.05%   |
| XFCE     | 2        | 0.03%   |
| KDE4     | 1        | 0.02%   |
| KDE      | 1        | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 5842     | 96.37%  |
| Wayland | 218      | 3.6%    |
| Unknown | 2        | 0.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 5875     | 96.95%  |
| GDM     | 175      | 2.89%   |
| Unknown | 5        | 0.08%   |
| LightDM | 4        | 0.07%   |
| KDM     | 1        | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 3297     | 53.52%  |
| de_DE   | 489      | 7.94%   |
| ru_RU   | 437      | 7.09%   |
| fr_FR   | 340      | 5.52%   |
| pt_BR   | 255      | 4.14%   |
| pl_PL   | 186      | 3.02%   |
| it_IT   | 160      | 2.6%    |
| es_ES   | 136      | 2.21%   |
| en_GB   | 127      | 2.06%   |
| cs_CZ   | 65       | 1.06%   |
| es_AR   | 55       | 0.89%   |
| hu_HU   | 53       | 0.86%   |
| de_AT   | 51       | 0.83%   |
| es_MX   | 50       | 0.81%   |
| en_CA   | 43       | 0.7%    |
| en_AU   | 38       | 0.62%   |
| nl_NL   | 30       | 0.49%   |
| fr_CA   | 28       | 0.45%   |
| en_IN   | 24       | 0.39%   |
| de_CH   | 24       | 0.39%   |
| tr_TR   | 18       | 0.29%   |
| ru_UA   | 18       | 0.29%   |
| es_VE   | 18       | 0.29%   |
| es_CO   | 18       | 0.29%   |
| pt_PT   | 15       | 0.24%   |
| fr_BE   | 14       | 0.23%   |
| es_CL   | 14       | 0.23%   |
| da_DK   | 14       | 0.23%   |
| Unknown | 13       | 0.21%   |
| en_HK   | 10       | 0.16%   |
| ro_RO   | 8        | 0.13%   |
| es_PE   | 8        | 0.13%   |
| en_IL   | 8        | 0.13%   |
| nl_BE   | 7        | 0.11%   |
| en_ZA   | 7        | 0.11%   |
| uk_UA   | 6        | 0.1%    |
| nb_NO   | 5        | 0.08%   |
| ja_JP   | 5        | 0.08%   |
| es_UY   | 5        | 0.08%   |
| es_SV   | 5        | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 3448     | 56.72%  |
| EFI  | 2631     | 43.28%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Overlay  | 4835     | 77.24%  |
| Ext4     | 1318     | 21.05%  |
| Btrfs    | 61       | 0.97%   |
| Xfs      | 20       | 0.32%   |
| F2fs     | 9        | 0.14%   |
| Ext3     | 5        | 0.08%   |
| Jfs      | 4        | 0.06%   |
| Unknown  | 4        | 0.06%   |
| Reiserfs | 2        | 0.03%   |
| Tmpfs    | 1        | 0.02%   |
| Ext2     | 1        | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 3768     | 61.74%  |
| MBR     | 2307     | 37.8%   |
| Unknown | 28       | 0.46%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 3794     | 61.88%  |
| No        | 2337     | 38.12%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 3301     | 54.11%  |
| No        | 2799     | 45.89%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 1471     | 24.36%  |
| Gigabyte Technology | 1083     | 17.93%  |
| MSI                 | 660      | 10.93%  |
| ASRock              | 564      | 9.34%   |
| Hewlett-Packard     | 500      | 8.28%   |
| Dell                | 482      | 7.98%   |
| Lenovo              | 238      | 3.94%   |
| Intel               | 165      | 2.73%   |
| Acer                | 141      | 2.33%   |
| Fujitsu             | 82       | 1.36%   |
| Pegatron            | 75       | 1.24%   |
| Biostar             | 75       | 1.24%   |
| Foxconn             | 73       | 1.21%   |
| ECS                 | 50       | 0.83%   |
| Medion              | 46       | 0.76%   |
| Unknown             | 44       | 0.73%   |
| Positivo            | 20       | 0.33%   |
| Fujitsu Siemens     | 16       | 0.26%   |
| BESSTAR Tech        | 15       | 0.25%   |
| AZW                 | 15       | 0.25%   |
| Shuttle             | 12       | 0.2%    |
| PCWare              | 12       | 0.2%    |
| Packard Bell        | 12       | 0.2%    |
| Alienware           | 10       | 0.17%   |
| Supermicro          | 9        | 0.15%   |
| MACHINIST           | 9        | 0.15%   |
| Gateway             | 9        | 0.15%   |
| OEM                 | 8        | 0.13%   |
| Inventec            | 6        | 0.1%    |
| Huanan              | 6        | 0.1%    |
| eMachines           | 6        | 0.1%    |
| Apple               | 6        | 0.1%    |
| Semp Toshiba        | 5        | 0.08%   |
| Itautec             | 5        | 0.08%   |
| Wistron             | 4        | 0.07%   |
| Philco              | 4        | 0.07%   |
| MouseComputer       | 4        | 0.07%   |
| ABIT                | 4        | 0.07%   |
| Login Informatica   | 3        | 0.05%   |
| AMD                 | 3        | 0.05%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| ASUS All Series              | 128      | 2.12%   |
| Unknown                      | 49       | 0.81%   |
| Dell OptiPlex 7010           | 44       | 0.73%   |
| Dell OptiPlex 780            | 37       | 0.61%   |
| ASUS PRIME A320M-K           | 31       | 0.51%   |
| Gigabyte H410M H V3          | 27       | 0.45%   |
| HP EliteDesk 800 G1 SFF      | 24       | 0.4%    |
| Dell OptiPlex 9020           | 24       | 0.4%    |
| Intel H61                    | 23       | 0.38%   |
| Gigabyte 970A-DS3P           | 23       | 0.38%   |
| Dell OptiPlex 3020           | 22       | 0.36%   |
| MSI MS-7817                  | 21       | 0.35%   |
| MSI MS-7721                  | 21       | 0.35%   |
| ASUS TUF Gaming X570-PLUS    | 21       | 0.35%   |
| HP Compaq Pro 6300 SFF       | 20       | 0.33%   |
| Gigabyte B450M DS3H          | 20       | 0.33%   |
| ASUS SABERTOOTH Z77          | 20       | 0.33%   |
| ASUS PRIME B450M-A           | 20       | 0.33%   |
| MSI MS-7C37                  | 19       | 0.31%   |
| Gigabyte A320M-S2H           | 19       | 0.31%   |
| Dell OptiPlex 790            | 19       | 0.31%   |
| MSI MS-7C02                  | 18       | 0.3%    |
| ASUS M5A78L-M/USB3           | 18       | 0.3%    |
| Dell OptiPlex 380            | 16       | 0.26%   |
| HP Compaq 8200 Elite SFF PC  | 15       | 0.25%   |
| ASUS TUF Gaming B550-PLUS    | 15       | 0.25%   |
| ASUS PRIME B450M-A II        | 15       | 0.25%   |
| ASUS M5A97 R2.0              | 15       | 0.25%   |
| MSI MS-7C56                  | 14       | 0.23%   |
| MSI MS-7B86                  | 14       | 0.23%   |
| Gigabyte GA-78LMT-USB3 6.0   | 14       | 0.23%   |
| Gigabyte G31M-ES2L           | 14       | 0.23%   |
| Gigabyte B75M-D3H            | 14       | 0.23%   |
| ASUS ROG STRIX B550-F GAMING | 14       | 0.23%   |
| ASRock B450M Pro4            | 14       | 0.23%   |
| MSI MS-7C91                  | 13       | 0.22%   |
| MSI MS-7C52                  | 13       | 0.22%   |
| MSI MS-7A38                  | 13       | 0.22%   |
| MSI MS-7693                  | 13       | 0.22%   |
| MSI MS-7641                  | 13       | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 328      | 5.43%   |
| ASUS PRIME             | 283      | 4.69%   |
| HP Compaq              | 178      | 2.95%   |
| Lenovo ThinkCentre     | 146      | 2.42%   |
| ASUS All               | 128      | 2.12%   |
| ASUS ROG               | 107      | 1.77%   |
| ASUS TUF               | 97       | 1.61%   |
| Acer Aspire            | 95       | 1.57%   |
| HP EliteDesk           | 82       | 1.36%   |
| Fujitsu ESPRIMO        | 71       | 1.18%   |
| ASUS M5A78L-M          | 62       | 1.03%   |
| HP ProDesk             | 61       | 1.01%   |
| Unknown                | 49       | 0.81%   |
| Gigabyte B450M         | 46       | 0.76%   |
| Dell Precision         | 46       | 0.76%   |
| Dell Inspiron          | 42       | 0.7%    |
| ASUS P8H61-M           | 41       | 0.68%   |
| Lenovo IdeaCentre      | 38       | 0.63%   |
| Dell Vostro            | 38       | 0.63%   |
| ASUS SABERTOOTH        | 37       | 0.61%   |
| HP Pavilion            | 36       | 0.6%    |
| Gigabyte H410M         | 36       | 0.6%    |
| Gigabyte B450          | 36       | 0.6%    |
| Gigabyte X570          | 34       | 0.56%   |
| Acer Veriton           | 34       | 0.56%   |
| ASUS M5A97             | 33       | 0.55%   |
| ASUS P8Z77-V           | 30       | 0.5%    |
| ASRock B450M           | 29       | 0.48%   |
| Gigabyte GA-78LMT-USB3 | 28       | 0.46%   |
| Intel H61              | 25       | 0.41%   |
| Gigabyte A320M-S2H     | 23       | 0.38%   |
| Gigabyte 970A-DS3P     | 23       | 0.38%   |
| ASUS P5K               | 23       | 0.38%   |
| MSI MS-7817            | 21       | 0.35%   |
| MSI MS-7721            | 21       | 0.35%   |
| Gigabyte B550          | 20       | 0.33%   |
| MSI MS-7C37            | 19       | 0.31%   |
| Gigabyte Z390          | 19       | 0.31%   |
| MSI MS-7C02            | 18       | 0.3%    |
| Gigabyte B550M         | 18       | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 666      | 11.03%  |
| 2013 | 559      | 9.26%   |
| 2018 | 538      | 8.91%   |
| 2011 | 476      | 7.88%   |
| 2014 | 420      | 6.95%   |
| 2010 | 390      | 6.46%   |
| 2020 | 389      | 6.44%   |
| 2009 | 367      | 6.08%   |
| 2019 | 360      | 5.96%   |
| 2017 | 332      | 5.5%    |
| 2021 | 301      | 4.98%   |
| 2008 | 288      | 4.77%   |
| 2015 | 277      | 4.59%   |
| 2016 | 251      | 4.16%   |
| 2007 | 191      | 3.16%   |
| 2006 | 129      | 2.14%   |
| 2022 | 75       | 1.24%   |
| 2005 | 20       | 0.33%   |
| 2023 | 5        | 0.08%   |
| 2004 | 5        | 0.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 6039     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 6039     | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 6038     | 99.98%  |
| Yes  | 1        | 0.02%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 1381     | 22.68%  |
| 16.01-24.0      | 1288     | 21.15%  |
| 4.01-8.0        | 1198     | 19.67%  |
| 3.01-4.0        | 1165     | 19.13%  |
| 32.01-64.0      | 565      | 9.28%   |
| 1.01-2.0        | 185      | 3.04%   |
| 24.01-32.0      | 119      | 1.95%   |
| 64.01-256.0     | 113      | 1.86%   |
| 2.01-3.0        | 59       | 0.97%   |
| 0.51-1.0        | 11       | 0.18%   |
| More than 256.0 | 5        | 0.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 4308     | 69.27%  |
| 0.51-1.0   | 913      | 14.68%  |
| 2.01-3.0   | 688      | 11.06%  |
| 0.01-0.5   | 161      | 2.59%   |
| 3.01-4.0   | 95       | 1.53%   |
| 4.01-8.0   | 38       | 0.61%   |
| 8.01-16.0  | 14       | 0.23%   |
| 16.01-24.0 | 2        | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 2633     | 42.86%  |
| 2      | 1644     | 26.76%  |
| 3      | 870      | 14.16%  |
| 4      | 493      | 8.03%   |
| 5      | 207      | 3.37%   |
| 0      | 124      | 2.02%   |
| 6      | 85       | 1.38%   |
| 7      | 38       | 0.62%   |
| 8      | 29       | 0.47%   |
| 9      | 8        | 0.13%   |
| 12     | 3        | 0.05%   |
| 15     | 2        | 0.03%   |
| 11     | 2        | 0.03%   |
| 10     | 2        | 0.03%   |
| 18     | 1        | 0.02%   |
| 17     | 1        | 0.02%   |
| 13     | 1        | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 3593     | 59.19%  |
| No        | 2477     | 40.81%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 5978     | 98.99%  |
| No        | 61       | 1.01%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 3935     | 64.81%  |
| Yes       | 2137     | 35.19%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 4662     | 76.84%  |
| Yes       | 1405     | 23.16%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 766      | 12.67%  |
| Germany     | 698      | 11.55%  |
| Russia      | 554      | 9.17%   |
| France      | 432      | 7.15%   |
| Brazil      | 399      | 6.6%    |
| Poland      | 291      | 4.81%   |
| Italy       | 266      | 4.4%    |
| UK          | 196      | 3.24%   |
| Spain       | 191      | 3.16%   |
| Canada      | 190      | 3.14%   |
| Australia   | 116      | 1.92%   |
| Mexico      | 89       | 1.47%   |
| Hungary     | 86       | 1.42%   |
| Czechia     | 83       | 1.37%   |
| Netherlands | 77       | 1.27%   |
| Ukraine     | 76       | 1.26%   |
| India       | 76       | 1.26%   |
| Japan       | 74       | 1.22%   |
| Argentina   | 73       | 1.21%   |
| Finland     | 70       | 1.16%   |
| Austria     | 70       | 1.16%   |
| Switzerland | 50       | 0.83%   |
| Romania     | 48       | 0.79%   |
| Sweden      | 46       | 0.76%   |
| Belgium     | 44       | 0.73%   |
| Serbia      | 42       | 0.69%   |
| Portugal    | 41       | 0.68%   |
| Greece      | 41       | 0.68%   |
| Indonesia   | 38       | 0.63%   |
| Slovakia    | 37       | 0.61%   |
| Turkey      | 34       | 0.56%   |
| Israel      | 32       | 0.53%   |
| Bulgaria    | 31       | 0.51%   |
| Venezuela   | 30       | 0.5%    |
| Egypt       | 28       | 0.46%   |
| China       | 26       | 0.43%   |
| Taiwan      | 24       | 0.4%    |
| Malaysia    | 24       | 0.4%    |
| Denmark     | 24       | 0.4%    |
| Colombia    | 24       | 0.4%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Moscow           | 105      | 1.69%   |
| Sao Paulo        | 50       | 0.81%   |
| Warsaw           | 45       | 0.73%   |
| Berlin           | 44       | 0.71%   |
| St Petersburg    | 38       | 0.61%   |
| Vienna           | 34       | 0.55%   |
| Milan            | 34       | 0.55%   |
| Rio de Janeiro   | 33       | 0.53%   |
| Paris            | 33       | 0.53%   |
| Helsinki         | 30       | 0.48%   |
| Mexico City      | 29       | 0.47%   |
| Rome             | 27       | 0.44%   |
| Nizhniy Novgorod | 24       | 0.39%   |
| Sydney           | 23       | 0.37%   |
| Melbourne        | 23       | 0.37%   |
| Madrid           | 23       | 0.37%   |
| Gonikoppal       | 22       | 0.36%   |
| Budapest         | 22       | 0.36%   |
| Hamburg          | 21       | 0.34%   |
| Yekaterinburg    | 19       | 0.31%   |
| Prague           | 19       | 0.31%   |
| Munich           | 19       | 0.31%   |
| Strzyzow         | 18       | 0.29%   |
| Novosibirsk      | 17       | 0.27%   |
| Cairo            | 17       | 0.27%   |
| Brisbane         | 17       | 0.27%   |
| Porto Alegre     | 16       | 0.26%   |
| Buenos Aires     | 16       | 0.26%   |
| Belgrade         | 16       | 0.26%   |
| Athens           | 16       | 0.26%   |
| Nuremberg        | 15       | 0.24%   |
| Montreal         | 15       | 0.24%   |
| Barcelona        | 15       | 0.24%   |
| Stuttgart        | 13       | 0.21%   |
| San José        | 13       | 0.21%   |
| Marseille        | 13       | 0.21%   |
| Caracas          | 13       | 0.21%   |
| Poznan           | 12       | 0.19%   |
| New Taipei       | 12       | 0.19%   |
| Kyiv             | 12       | 0.19%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 2156     | 2946   | 20.53%  |
| Seagate             | 2023     | 2659   | 19.26%  |
| Samsung Electronics | 1277     | 1772   | 12.16%  |
| Kingston            | 668      | 795    | 6.36%   |
| Toshiba             | 596      | 701    | 5.67%   |
| Crucial             | 521      | 643    | 4.96%   |
| Hitachi             | 390      | 441    | 3.71%   |
| SanDisk             | 375      | 450    | 3.57%   |
| A-DATA Technology   | 248      | 281    | 2.36%   |
| China               | 143      | 164    | 1.36%   |
| Unknown             | 128      | 163    | 1.22%   |
| Intel               | 106      | 118    | 1.01%   |
| Maxtor              | 104      | 118    | 0.99%   |
| PNY                 | 97       | 115    | 0.92%   |
| SPCC                | 92       | 107    | 0.88%   |
| Patriot             | 85       | 92     | 0.81%   |
| Intenso             | 75       | 86     | 0.71%   |
| GOODRAM             | 75       | 89     | 0.71%   |
| HGST                | 71       | 94     | 0.68%   |
| Apacer              | 64       | 70     | 0.61%   |
| Phison              | 54       | 71     | 0.51%   |
| OCZ                 | 54       | 58     | 0.51%   |
| Corsair             | 51       | 55     | 0.49%   |
| Transcend           | 50       | 52     | 0.48%   |
| Gigabyte Technology | 43       | 50     | 0.41%   |
| Team                | 40       | 42     | 0.38%   |
| JMicron Technology  | 40       | 43     | 0.38%   |
| Hewlett-Packard     | 37       | 42     | 0.35%   |
| SK hynix            | 35       | 37     | 0.33%   |
| Unknown             | 35       | 37     | 0.33%   |
| Netac               | 34       | 35     | 0.32%   |
| Micron Technology   | 33       | 36     | 0.31%   |
| Silicon Motion      | 31       | 33     | 0.3%    |
| XPG                 | 27       | 37     | 0.26%   |
| ASMT                | 27       | 29     | 0.26%   |
| KIOXIA-EXCERIA      | 23       | 23     | 0.22%   |
| KingSpec            | 21       | 21     | 0.2%    |
| Plextor             | 19       | 22     | 0.18%   |
| Fujitsu             | 19       | 19     | 0.18%   |
| LITEON              | 18       | 18     | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 198      | 1.64%   |
| Seagate ST1000DM010-2EP102 1TB   | 158      | 1.31%   |
| Kingston SA400S37240G 240GB SSD  | 157      | 1.3%    |
| Toshiba DT01ACA100 1TB           | 120      | 0.99%   |
| Seagate ST2000DM008-2FR102 2TB   | 107      | 0.89%   |
| WDC WD10EZEX-08WN4A0 1TB         | 94       | 0.78%   |
| Toshiba DT01ACA050 500GB         | 86       | 0.71%   |
| Seagate ST3500418AS 500GB        | 81       | 0.67%   |
| Kingston SA400S37480G 480GB SSD  | 80       | 0.66%   |
| Samsung SSD 860 EVO 500GB        | 78       | 0.65%   |
| Crucial CT500MX500SSD1 500GB     | 76       | 0.63%   |
| Kingston SA400S37120G 120GB SSD  | 75       | 0.62%   |
| Seagate ST1000DM003-1ER162 1TB   | 73       | 0.6%    |
| Kingston SV300S37A120G 120GB SSD | 73       | 0.6%    |
| Samsung SSD 860 EVO 250GB        | 67       | 0.55%   |
| Unknown SD/MMC/MS PRO 249GB      | 66       | 0.55%   |
| Samsung SSD 850 EVO 250GB        | 63       | 0.52%   |
| Crucial CT240BX500SSD1 240GB     | 63       | 0.52%   |
| Crucial CT1000MX500SSD1 1TB      | 62       | 0.51%   |
| Toshiba HDWD110 1TB              | 59       | 0.49%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 55       | 0.46%   |
| WDC WD10EZEX-00BN5A0 1TB         | 54       | 0.45%   |
| Toshiba DT01ACA200 2TB           | 54       | 0.45%   |
| Seagate ST3500413AS 500GB        | 52       | 0.43%   |
| Samsung SSD 970 EVO Plus 500GB   | 51       | 0.42%   |
| Samsung SSD 850 EVO 500GB        | 51       | 0.42%   |
| Seagate ST2000DM001-1ER164 2TB   | 49       | 0.41%   |
| Seagate ST1000DM003-1SB102 1TB   | 49       | 0.41%   |
| Crucial CT480BX500SSD1 480GB     | 49       | 0.41%   |
| Seagate ST1000DM003-1CH162 1TB   | 48       | 0.4%    |
| WDC WD20EZRZ-00Z5HB0 2TB         | 42       | 0.35%   |
| Samsung SSD 860 EVO 1TB          | 42       | 0.35%   |
| Seagate ST2000DM001-1CH164 2TB   | 41       | 0.34%   |
| Seagate ST31000528AS 1TB         | 38       | 0.31%   |
| Samsung SSD 970 EVO Plus 1TB     | 38       | 0.31%   |
| Samsung HD502HJ 500GB            | 37       | 0.31%   |
| Samsung HD103SJ 1TB              | 37       | 0.31%   |
| Seagate ST2000DM006-2DM164 2TB   | 36       | 0.3%    |
| Seagate Expansion 4TB            | 35       | 0.29%   |
| Unknown                          | 35       | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1998     | 2614   | 35.63%  |
| WDC                 | 1878     | 2471   | 33.49%  |
| Toshiba             | 542      | 638    | 9.67%   |
| Samsung Electronics | 413      | 478    | 7.37%   |
| Hitachi             | 390      | 441    | 6.96%   |
| Maxtor              | 102      | 116    | 1.82%   |
| HGST                | 71       | 94     | 1.27%   |
| Unknown             | 70       | 73     | 1.25%   |
| JMicron Technology  | 26       | 28     | 0.46%   |
| Fujitsu             | 18       | 18     | 0.32%   |
| Hewlett-Packard     | 12       | 12     | 0.21%   |
| Intenso             | 8        | 8      | 0.14%   |
| WD MediaMax         | 7        | 10     | 0.12%   |
| USB3.0              | 7        | 7      | 0.12%   |
| Apple               | 7        | 7      | 0.12%   |
| IBM/Hitachi         | 5        | 6      | 0.09%   |
| HPE                 | 5        | 5      | 0.09%   |
| ExcelStor           | 5        | 5      | 0.09%   |
| Quantum             | 4        | 4      | 0.07%   |
| ASMT                | 4        | 5      | 0.07%   |
| ASMedia             | 4        | 4      | 0.07%   |
| Unknown             | 3        | 3      | 0.05%   |
| StoreJet            | 2        | 2      | 0.04%   |
| RSH-319             | 2        | 2      | 0.04%   |
| MDT                 | 2        | 2      | 0.04%   |
| Magnetic Data       | 2        | 2      | 0.04%   |
| Inateck             | 2        | 2      | 0.04%   |
| HGST HTS            | 2        | 2      | 0.04%   |
| China               | 2        | 3      | 0.04%   |
| USB 3.0             | 1        | 2      | 0.02%   |
| USB                 | 1        | 2      | 0.02%   |
| TPH00800640GB       | 1        | 1      | 0.02%   |
| T-CREATE            | 1        | 1      | 0.02%   |
| Super Talent        | 1        | 1      | 0.02%   |
| SABRENT             | 1        | 1      | 0.02%   |
| RSH-339             | 1        | 1      | 0.02%   |
| Promise             | 1        | 1      | 0.02%   |
| MARVELL             | 1        | 1      | 0.02%   |
| KESU                | 1        | 2      | 0.02%   |
| IB                  | 1        | 2      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 643      | 847    | 16.67%  |
| Kingston            | 566      | 666    | 14.67%  |
| Crucial             | 431      | 527    | 11.17%  |
| SanDisk             | 332      | 394    | 8.61%   |
| WDC                 | 267      | 308    | 6.92%   |
| A-DATA Technology   | 209      | 232    | 5.42%   |
| China               | 141      | 161    | 3.66%   |
| PNY                 | 88       | 104    | 2.28%   |
| Patriot             | 75       | 82     | 1.94%   |
| SPCC                | 73       | 84     | 1.89%   |
| GOODRAM             | 72       | 83     | 1.87%   |
| Intenso             | 65       | 74     | 1.69%   |
| Intel               | 56       | 60     | 1.45%   |
| Apacer              | 56       | 61     | 1.45%   |
| OCZ                 | 54       | 58     | 1.4%    |
| Toshiba             | 48       | 50     | 1.24%   |
| Transcend           | 43       | 44     | 1.11%   |
| Team                | 34       | 35     | 0.88%   |
| Unknown             | 30       | 32     | 0.78%   |
| Micron Technology   | 29       | 32     | 0.75%   |
| Netac               | 26       | 27     | 0.67%   |
| Gigabyte Technology | 25       | 27     | 0.65%   |
| Corsair             | 25       | 27     | 0.65%   |
| ASMT                | 23       | 24     | 0.6%    |
| KingSpec            | 20       | 20     | 0.52%   |
| KIOXIA-EXCERIA      | 16       | 16     | 0.41%   |
| Hewlett-Packard     | 16       | 18     | 0.41%   |
| XrayDisk            | 15       | 15     | 0.39%   |
| Unknown             | 15       | 16     | 0.39%   |
| LITEON              | 15       | 15     | 0.39%   |
| Plextor             | 13       | 15     | 0.34%   |
| KingFast            | 13       | 15     | 0.34%   |
| SK hynix            | 12       | 13     | 0.31%   |
| Lexar               | 12       | 12     | 0.31%   |
| Leven               | 11       | 11     | 0.29%   |
| Seagate             | 10       | 12     | 0.26%   |
| KingDian            | 10       | 11     | 0.26%   |
| TO Exter            | 9        | 9      | 0.23%   |
| Emtec               | 9        | 10     | 0.23%   |
| Verbatim            | 8        | 8      | 0.21%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 4344     | 7080   | 50.72%  |
| SSD     | 3034     | 4508   | 35.42%  |
| NVMe    | 1071     | 1477   | 12.5%   |
| Unknown | 97       | 132    | 1.13%   |
| MMC     | 19       | 21     | 0.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 5652     | 11152  | 78.55%  |
| NVMe | 1063     | 1451   | 14.77%  |
| SAS  | 461      | 594    | 6.41%   |
| MMC  | 19       | 21     | 0.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 4472     | 6950   | 56.44%  |
| 0.51-1.0   | 2159     | 2971   | 27.25%  |
| 1.01-2.0   | 758      | 957    | 9.57%   |
| 3.01-4.0   | 194      | 264    | 2.45%   |
| 2.01-3.0   | 184      | 232    | 2.32%   |
| 4.01-10.0  | 125      | 177    | 1.58%   |
| 10.01-20.0 | 32       | 37     | 0.4%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 2907     | 46.21%  |
| Unknown        | 944      | 15.01%  |
| 101-250        | 824      | 13.1%   |
| 251-500        | 550      | 8.74%   |
| 501-1000       | 326      | 5.18%   |
| 51-100         | 253      | 4.02%   |
| 21-50          | 241      | 3.83%   |
| 1001-2000      | 140      | 2.23%   |
| More than 3000 | 56       | 0.89%   |
| 2001-3000      | 50       | 0.79%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 4578     | 73.73%  |
| Unknown        | 944      | 15.2%   |
| 101-250        | 151      | 2.43%   |
| 21-50          | 148      | 2.38%   |
| 51-100         | 118      | 1.9%    |
| 251-500        | 108      | 1.74%   |
| 501-1000       | 93       | 1.5%    |
| 1001-2000      | 40       | 0.64%   |
| 2001-3000      | 16       | 0.26%   |
| More than 3000 | 13       | 0.21%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 85       | 88     | 3.75%   |
| Seagate ST3500418AS 500GB         | 38       | 42     | 1.68%   |
| Toshiba DT01ACA100 1TB            | 19       | 20     | 0.84%   |
| Seagate ST31000528AS 1TB          | 19       | 20     | 0.84%   |
| Seagate ST31000524AS 1TB          | 19       | 19     | 0.84%   |
| Seagate ST1000DM010-2EP102 1TB    | 18       | 19     | 0.8%    |
| Kingston SV300S37A120G 120GB SSD  | 18       | 19     | 0.8%    |
| WDC WD5000AAKX-75U6AA0 500GB      | 17       | 17     | 0.75%   |
| WDC WD5000AAKX-001CA0 500GB       | 17       | 20     | 0.75%   |
| Toshiba DT01ACA050 500GB          | 17       | 19     | 0.75%   |
| Seagate ST9500325AS 500GB         | 17       | 18     | 0.75%   |
| Seagate ST3500413AS 500GB         | 16       | 16     | 0.71%   |
| Samsung Electronics HD322HJ 320GB | 16       | 18     | 0.71%   |
| Seagate ST2000DM001-1CH164 2TB    | 15       | 15     | 0.66%   |
| Seagate ST1000DM003-9YN162 1TB    | 15       | 16     | 0.66%   |
| Seagate ST3320418AS 320GB         | 14       | 15     | 0.62%   |
| Samsung Electronics HD502HJ 500GB | 14       | 14     | 0.62%   |
| Samsung Electronics HD161HJ 160GB | 13       | 13     | 0.57%   |
| Samsung Electronics HD103SJ 1TB   | 13       | 14     | 0.57%   |
| Hitachi HDS721050CLA362 500GB     | 13       | 16     | 0.57%   |
| Seagate ST250DM000-1BD141 250GB   | 12       | 12     | 0.53%   |
| Samsung Electronics HD103SI 1TB   | 12       | 12     | 0.53%   |
| Hitachi HDS721010CLA332 1TB       | 12       | 12     | 0.53%   |
| WDC WD5000AADS-00S9B0 500GB       | 11       | 11     | 0.49%   |
| Seagate ST1000DM003-1CH162 1TB    | 11       | 13     | 0.49%   |
| Samsung Electronics HD103UJ 1TB   | 11       | 13     | 0.49%   |
| Maxtor STM3250310AS 250GB         | 11       | 11     | 0.49%   |
| WDC WD3200AAJS-00L7A0 320GB       | 10       | 10     | 0.44%   |
| WDC WD20EARS-00MVWB0 2TB          | 10       | 12     | 0.44%   |
| Seagate ST3250318AS 250GB         | 10       | 10     | 0.44%   |
| Seagate ST3250310AS 250GB         | 10       | 11     | 0.44%   |
| Seagate ST2000DL003-9VT166 2TB    | 10       | 11     | 0.44%   |
| WDC WDS240G2G0A-00JH30 240GB SSD  | 9        | 11     | 0.4%    |
| WDC WD5000AAKX-003CA0 500GB       | 9        | 9      | 0.4%    |
| WDC WD20EZRZ-00Z5HB0 2TB          | 9        | 10     | 0.4%    |
| WDC WD10EARS-00Y5B1 1TB           | 9        | 12     | 0.4%    |
| Seagate ST3320613AS 320GB         | 9        | 10     | 0.4%    |
| Seagate ST3250820AS 250GB         | 9        | 10     | 0.4%    |
| Seagate ST31500341AS 1TB          | 9        | 9      | 0.4%    |
| Hitachi HDS721680PLA380 82GB      | 9        | 10     | 0.4%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 665      | 749    | 30.92%  |
| WDC                 | 627      | 730    | 29.15%  |
| Samsung Electronics | 225      | 250    | 10.46%  |
| Hitachi             | 170      | 189    | 7.9%    |
| Toshiba             | 81       | 85     | 3.77%   |
| Maxtor              | 68       | 72     | 3.16%   |
| Kingston            | 64       | 68     | 2.98%   |
| SanDisk             | 33       | 36     | 1.53%   |
| Crucial             | 22       | 24     | 1.02%   |
| HGST                | 21       | 26     | 0.98%   |
| A-DATA Technology   | 18       | 19     | 0.84%   |
| Intel               | 16       | 16     | 0.74%   |
| China               | 13       | 13     | 0.6%    |
| Hewlett-Packard     | 8        | 8      | 0.37%   |
| OCZ                 | 7        | 7      | 0.33%   |
| GOODRAM             | 7        | 7      | 0.33%   |
| Fujitsu             | 7        | 7      | 0.33%   |
| ASMT                | 7        | 7      | 0.33%   |
| Unknown             | 6        | 6      | 0.28%   |
| SPCC                | 5        | 5      | 0.23%   |
| Netac               | 5        | 5      | 0.23%   |
| Corsair             | 5        | 5      | 0.23%   |
| Patriot             | 4        | 4      | 0.19%   |
| Micron Technology   | 4        | 5      | 0.19%   |
| SK hynix            | 3        | 3      | 0.14%   |
| KingSpec            | 3        | 3      | 0.14%   |
| Intenso             | 3        | 3      | 0.14%   |
| IBM/Hitachi         | 3        | 4      | 0.14%   |
| XPG                 | 2        | 2      | 0.09%   |
| WD MediaMax         | 2        | 2      | 0.09%   |
| USB3.0              | 2        | 2      | 0.09%   |
| Team                | 2        | 2      | 0.09%   |
| LITEON              | 2        | 2      | 0.09%   |
| Initio              | 2        | 2      | 0.09%   |
| HPE                 | 2        | 2      | 0.09%   |
| Apacer              | 2        | 3      | 0.09%   |
| XSTAR               | 1        | 1      | 0.05%   |
| XrayDisk            | 1        | 1      | 0.05%   |
| WDC WDS2            | 1        | 1      | 0.05%   |
| Transcend           | 1        | 1      | 0.05%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 665      | 749    | 36.28%  |
| WDC                 | 603      | 699    | 32.9%   |
| Samsung Electronics | 195      | 217    | 10.64%  |
| Hitachi             | 170      | 189    | 9.27%   |
| Toshiba             | 80       | 84     | 4.36%   |
| Maxtor              | 68       | 72     | 3.71%   |
| HGST                | 21       | 26     | 1.15%   |
| Fujitsu             | 7        | 7      | 0.38%   |
| Hewlett-Packard     | 6        | 6      | 0.33%   |
| IBM/Hitachi         | 3        | 4      | 0.16%   |
| WD MediaMax         | 2        | 2      | 0.11%   |
| USB3.0              | 2        | 2      | 0.11%   |
| HPE                 | 2        | 2      | 0.11%   |
| RSH-339             | 1        | 1      | 0.05%   |
| RSH-319             | 1        | 1      | 0.05%   |
| Quantum             | 1        | 1      | 0.05%   |
| IB                  | 1        | 1      | 0.05%   |
| ExcelStor           | 1        | 1      | 0.05%   |
| China               | 1        | 1      | 0.05%   |
| ASMT                | 1        | 1      | 0.05%   |
| ASMedia             | 1        | 1      | 0.05%   |
| Unknown             | 1        | 1      | 0.05%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1621     | 2068   | 83.69%  |
| SSD     | 289      | 313    | 14.92%  |
| NVMe    | 26       | 27     | 1.34%   |
| Unknown | 1        | 1      | 0.05%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Desktops | Drives | Percent |
|--------------------------------------------------|----------|--------|---------|
| Seagate ST3500418AS 500GB                        | 3        | 4      | 5.08%   |
| Seagate ST3250318AS 250GB                        | 3        | 3      | 5.08%   |
| Samsung Electronics HD103SJ 1TB                  | 3        | 3      | 5.08%   |
| Apple HDD HTS541010A9E662 1TB                    | 3        | 3      | 5.08%   |
| WDC WD800JD-00LSA0 80GB                          | 2        | 3      | 3.39%   |
| WDC WD20EZRX-00D8PB0 2TB                         | 2        | 2      | 3.39%   |
| Seagate ST500DM002-1BD142 500GB                  | 2        | 2      | 3.39%   |
| Samsung Electronics HD502HJ 500GB                | 2        | 2      | 3.39%   |
| Samsung Electronics HD103UJ 1TB                  | 2        | 3      | 3.39%   |
| WDC WD800JD-75MSA3 80GB                          | 1        | 1      | 1.69%   |
| WDC WD7501AALS-00J7B0 752GB                      | 1        | 1      | 1.69%   |
| WDC WD7500BPVT-22HXZT3 752GB                     | 1        | 1      | 1.69%   |
| WDC WD5000AAKS-00C8A0 500GB                      | 1        | 1      | 1.69%   |
| WDC WD3200AAJS-60Z0A0 320GB                      | 1        | 1      | 1.69%   |
| WDC WD20EARS-00MVWB0 2TB                         | 1        | 1      | 1.69%   |
| WDC WD1600YS-23SHB0 160GB                        | 1        | 1      | 1.69%   |
| WDC WD10JPVT-75A1YT0 1TB                         | 1        | 1      | 1.69%   |
| WDC WD10EALX-759BA1 1TB                          | 1        | 1      | 1.69%   |
| TPH00800640GB 640GB                              | 1        | 1      | 1.69%   |
| Toshiba MQ01ABD050 500GB                         | 1        | 1      | 1.69%   |
| Toshiba MK3256GSY 320GB                          | 1        | 1      | 1.69%   |
| Toshiba DT01ACA100 1TB                           | 1        | 1      | 1.69%   |
| Seagate STM3250318AS 250GB                       | 1        | 1      | 1.69%   |
| Seagate STM31000528AS 1TB                        | 1        | 1      | 1.69%   |
| Seagate ST980811AS 80GB                          | 1        | 1      | 1.69%   |
| Seagate ST9320423AS 320GB                        | 1        | 1      | 1.69%   |
| Seagate ST3750640NS 752GB                        | 1        | 1      | 1.69%   |
| Seagate ST3320418AS 320GB                        | 1        | 1      | 1.69%   |
| Seagate ST3250820AS 250GB                        | 1        | 1      | 1.69%   |
| Seagate ST3160215A 160GB                         | 1        | 1      | 1.69%   |
| Seagate ST31000528AS 1TB                         | 1        | 1      | 1.69%   |
| Samsung Electronics SSD 980 500GB                | 1        | 1      | 1.69%   |
| Samsung Electronics SSD 980 1TB                  | 1        | 1      | 1.69%   |
| Samsung Electronics MZNTY128HDHP-00000 128GB SSD | 1        | 1      | 1.69%   |
| Samsung Electronics MZ7TY128HDHP-000L1 128GB SSD | 1        | 1      | 1.69%   |
| Samsung Electronics HM160HI 160GB                | 1        | 1      | 1.69%   |
| Samsung Electronics HD753LJ 752GB                | 1        | 1      | 1.69%   |
| Samsung Electronics HD501LJ 500GB                | 1        | 1      | 1.69%   |
| Samsung Electronics HD252HJ 250GB                | 1        | 1      | 1.69%   |
| Maxtor STM3500320AS 500GB                        | 1        | 1      | 1.69%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 17       | 18     | 28.81%  |
| Samsung Electronics | 15       | 16     | 25.42%  |
| WDC                 | 13       | 14     | 22.03%  |
| Hitachi             | 4        | 4      | 6.78%   |
| Toshiba             | 3        | 3      | 5.08%   |
| Apple               | 3        | 3      | 5.08%   |
| TPH00800640GB       | 1        | 1      | 1.69%   |
| Maxtor              | 1        | 1      | 1.69%   |
| Kingston            | 1        | 1      | 1.69%   |
| GOODRAM             | 1        | 1      | 1.69%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 4881     | 9869   | 65.45%  |
| Malfunc  | 1875     | 2409   | 25.14%  |
| Detected | 645      | 878    | 8.65%   |
| Failed   | 57       | 62     | 0.76%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 3854     | 48.52%  |
| AMD                              | 1950     | 24.55%  |
| Samsung Electronics              | 353      | 4.44%   |
| ASMedia Technology               | 235      | 2.96%   |
| JMicron Technology               | 216      | 2.72%   |
| Nvidia                           | 209      | 2.63%   |
| Marvell Technology Group         | 183      | 2.3%    |
| SanDisk                          | 182      | 2.29%   |
| Phison Electronics               | 151      | 1.9%    |
| Kingston Technology Company      | 119      | 1.5%    |
| Micron/Crucial Technology        | 96       | 1.21%   |
| Silicon Motion                   | 90       | 1.13%   |
| VIA Technologies                 | 60       | 0.76%   |
| ADATA Technology                 | 42       | 0.53%   |
| Realtek Semiconductor            | 27       | 0.34%   |
| SK hynix                         | 20       | 0.25%   |
| Seagate Technology               | 16       | 0.2%    |
| Toshiba America Info Systems     | 14       | 0.18%   |
| Silicon Image                    | 14       | 0.18%   |
| Micron Technology                | 12       | 0.15%   |
| MAXIO Technology (Hangzhou)      | 12       | 0.15%   |
| KIOXIA                           | 11       | 0.14%   |
| LSI Logic / Symbios Logic        | 10       | 0.13%   |
| Integrated Technology Express    | 10       | 0.13%   |
| Broadcom / LSI                   | 10       | 0.13%   |
| Lite-On Technology               | 8        | 0.1%    |
| Shenzhen Longsys Electronics     | 7        | 0.09%   |
| Promise Technology               | 5        | 0.06%   |
| Lite-On IT Corp. / Plextor       | 4        | 0.05%   |
| Silicon Integrated Systems [SiS] | 3        | 0.04%   |
| Hewlett-Packard                  | 3        | 0.04%   |
| Biwin Storage Technology         | 3        | 0.04%   |
| Adaptec                          | 3        | 0.04%   |
| Union Memory (Shenzhen)          | 2        | 0.03%   |
| Netac Technology                 | 2        | 0.03%   |
| INNOGRIT                         | 2        | 0.03%   |
| 3ware                            | 2        | 0.03%   |
| Yangtze Memory Technologies      | 1        | 0.01%   |
| Solid State Storage Technology   | 1        | 0.01%   |
| OCZ Technology Group             | 1        | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 1030     | 9.98%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 520      | 5.04%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 369      | 3.57%   |
| AMD 400 Series Chipset SATA Controller                                                  | 365      | 3.54%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 363      | 3.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 341      | 3.3%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 303      | 2.94%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 282      | 2.73%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 269      | 2.61%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 258      | 2.5%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 249      | 2.41%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 220      | 2.13%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 212      | 2.05%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 201      | 1.95%   |
| AMD 500 Series Chipset SATA Controller                                                  | 196      | 1.9%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 182      | 1.76%   |
| Intel SATA Controller [RAID mode]                                                       | 181      | 1.75%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 180      | 1.74%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 172      | 1.67%   |
| AMD FCH SATA Controller D                                                               | 138      | 1.34%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 129      | 1.25%   |
| Nvidia MCP61 SATA Controller                                                            | 120      | 1.16%   |
| Nvidia MCP61 IDE                                                                        | 109      | 1.06%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 108      | 1.05%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 98       | 0.95%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 96       | 0.93%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 95       | 0.92%   |
| AMD 300 Series Chipset SATA Controller                                                  | 92       | 0.89%   |
| AMD FCH IDE Controller                                                                  | 87       | 0.84%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 76       | 0.74%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 74       | 0.72%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 72       | 0.7%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 70       | 0.68%   |
| Phison E12 NVMe Controller                                                              | 69       | 0.67%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 68       | 0.66%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 66       | 0.64%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 63       | 0.61%   |
| Samsung NVMe SSD Controller 980                                                         | 62       | 0.6%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 62       | 0.6%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 61       | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 4636     | 58.68%  |
| IDE  | 1888     | 23.9%   |
| NVMe | 1057     | 13.38%  |
| RAID | 286      | 3.62%   |
| SAS  | 22       | 0.28%   |
| SCSI | 12       | 0.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 3905     | 64.66%  |
| AMD    | 2134     | 35.34%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 93       | 1.54%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 86       | 1.42%   |
| AMD Ryzen 5 3600 6-Core Processor           | 81       | 1.34%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 71       | 1.17%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 67       | 1.11%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 65       | 1.07%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 64       | 1.06%   |
| AMD FX-8350 Eight-Core Processor            | 61       | 1.01%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 59       | 0.97%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 59       | 0.97%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 58       | 0.96%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 58       | 0.96%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 55       | 0.91%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 54       | 0.89%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 54       | 0.89%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 51       | 0.84%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 50       | 0.83%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 49       | 0.81%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 46       | 0.76%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 45       | 0.74%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 44       | 0.73%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 43       | 0.71%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 42       | 0.69%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 42       | 0.69%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 41       | 0.68%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 40       | 0.66%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 38       | 0.63%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 37       | 0.61%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 36       | 0.59%   |
| AMD FX-6300 Six-Core Processor              | 36       | 0.59%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 35       | 0.58%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 35       | 0.58%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 35       | 0.58%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 34       | 0.56%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 32       | 0.53%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 31       | 0.51%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 31       | 0.51%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 30       | 0.5%    |
| Intel Core i7-6700 CPU @ 3.40GHz            | 30       | 0.5%    |
| Intel Core i5-9400F CPU @ 2.90GHz           | 30       | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 1116     | 18.44%  |
| Intel Core i3           | 611      | 10.1%   |
| Intel Core i7           | 580      | 9.58%   |
| AMD Ryzen 5             | 459      | 7.58%   |
| Intel Core 2 Duo        | 287      | 4.74%   |
| AMD FX                  | 253      | 4.18%   |
| AMD Ryzen 7             | 242      | 4%      |
| Intel Pentium           | 232      | 3.83%   |
| Intel Celeron           | 222      | 3.67%   |
| Intel Core 2 Quad       | 179      | 2.96%   |
| Intel Xeon              | 174      | 2.88%   |
| Intel Pentium Dual-Core | 140      | 2.31%   |
| AMD Ryzen 3             | 121      | 2%      |
| Other                   | 113      | 1.87%   |
| AMD A8                  | 107      | 1.77%   |
| AMD Athlon II X2        | 97       | 1.6%    |
| AMD Ryzen 9             | 91       | 1.5%    |
| AMD Phenom II X4        | 88       | 1.45%   |
| AMD A10                 | 77       | 1.27%   |
| AMD Athlon 64 X2        | 74       | 1.22%   |
| AMD A4                  | 66       | 1.09%   |
| Intel Core 2            | 64       | 1.06%   |
| AMD Athlon              | 59       | 0.97%   |
| AMD A6                  | 53       | 0.88%   |
| Intel Pentium Dual      | 47       | 0.78%   |
| AMD Athlon II X4        | 41       | 0.68%   |
| AMD Phenom II X6        | 35       | 0.58%   |
| AMD Phenom              | 33       | 0.55%   |
| Intel Pentium 4         | 29       | 0.48%   |
| Intel Core i9           | 29       | 0.48%   |
| Intel Pentium Gold      | 28       | 0.46%   |
| Intel Pentium D         | 28       | 0.46%   |
| Intel Atom              | 26       | 0.43%   |
| AMD Athlon II X3        | 26       | 0.43%   |
| AMD Sempron             | 22       | 0.36%   |
| AMD Athlon X4           | 21       | 0.35%   |
| AMD Ryzen 5 PRO         | 20       | 0.33%   |
| AMD Phenom II X2        | 17       | 0.28%   |
| AMD Athlon 64           | 17       | 0.28%   |
| AMD Ryzen Threadripper  | 13       | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 2350     | 38.82%  |
| 2       | 2132     | 35.22%  |
| 6       | 749      | 12.37%  |
| 8       | 365      | 6.03%   |
| 1       | 186      | 3.07%   |
| 3       | 103      | 1.7%    |
| 12      | 83       | 1.37%   |
| 16      | 44       | 0.73%   |
| 10      | 22       | 0.36%   |
| 14      | 6        | 0.1%    |
| 24      | 5        | 0.08%   |
| 28      | 3        | 0.05%   |
| 32      | 2        | 0.03%   |
| 20      | 2        | 0.03%   |
| 44      | 1        | 0.02%   |
| Unknown | 1        | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 6008     | 99.49%  |
| 2      | 31       | 0.51%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 3031     | 50.12%  |
| 2       | 3004     | 49.67%  |
| 4       | 7        | 0.12%   |
| 12      | 2        | 0.03%   |
| 8       | 2        | 0.03%   |
| 6       | 1        | 0.02%   |
| Unknown | 1        | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 6036     | 99.95%  |
| Unknown        | 3        | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 599      | 9.76%   |
| Unknown    | 529      | 8.62%   |
| 0x306a9    | 459      | 7.48%   |
| 0x1067a    | 431      | 7.02%   |
| 0x206a7    | 401      | 6.53%   |
| 0x08701021 | 218      | 3.55%   |
| 0x506e3    | 195      | 3.18%   |
| 0x906ea    | 158      | 2.57%   |
| 0x906e9    | 144      | 2.35%   |
| 0x06001119 | 131      | 2.13%   |
| 0x010000c8 | 120      | 1.96%   |
| 0x0800820d | 119      | 1.94%   |
| 0x08101016 | 91       | 1.48%   |
| 0x08108109 | 90       | 1.47%   |
| 0xa0653    | 86       | 1.4%    |
| 0x06000822 | 85       | 1.38%   |
| 0x6fb      | 81       | 1.32%   |
| 0x6fd      | 75       | 1.22%   |
| 0xa0655    | 73       | 1.19%   |
| 0x06003106 | 70       | 1.14%   |
| 0x10676    | 61       | 0.99%   |
| 0x08001138 | 61       | 0.99%   |
| 0x106e5    | 59       | 0.96%   |
| 0x010000b6 | 53       | 0.86%   |
| 0x906eb    | 51       | 0.83%   |
| 0x20655    | 51       | 0.83%   |
| 0x0a201016 | 50       | 0.81%   |
| 0x0a50000c | 48       | 0.78%   |
| 0x0a50000d | 45       | 0.73%   |
| 0xa0671    | 43       | 0.7%    |
| 0x0600081c | 41       | 0.67%   |
| 0x906ed    | 39       | 0.64%   |
| 0x08600106 | 37       | 0.6%    |
| 0x106a5    | 36       | 0.59%   |
| 0x6f6      | 35       | 0.57%   |
| 0x0600611a | 35       | 0.57%   |
| 0x10677    | 33       | 0.54%   |
| 0x08701013 | 33       | 0.54%   |
| 0x010000bf | 33       | 0.54%   |
| 0x20652    | 31       | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 699      | 11.57%  |
| Penryn           | 545      | 9.02%   |
| IvyBridge        | 521      | 8.62%   |
| KabyLake         | 486      | 8.04%   |
| SandyBridge      | 457      | 7.56%   |
| K10              | 360      | 5.96%   |
| Piledriver       | 348      | 5.76%   |
| Zen 2            | 306      | 5.06%   |
| Zen+             | 252      | 4.17%   |
| Core             | 243      | 4.02%   |
| Skylake          | 233      | 3.86%   |
| Zen              | 231      | 3.82%   |
| Zen 3            | 214      | 3.54%   |
| CometLake        | 175      | 2.9%    |
| K8 Hammer        | 112      | 1.85%   |
| Nehalem          | 104      | 1.72%   |
| Westmere         | 101      | 1.67%   |
| Steamroller      | 85       | 1.41%   |
| Silvermont       | 68       | 1.13%   |
| NetBurst         | 64       | 1.06%   |
| Bulldozer        | 54       | 0.89%   |
| Excavator        | 53       | 0.88%   |
| Alderlake Hybrid | 47       | 0.78%   |
| K10 Llano        | 41       | 0.68%   |
| Icelake          | 40       | 0.66%   |
| Goldmont plus    | 37       | 0.61%   |
| Jaguar           | 33       | 0.55%   |
| Puma             | 23       | 0.38%   |
| Bonnell          | 23       | 0.38%   |
| Broadwell        | 21       | 0.35%   |
| Bobcat           | 20       | 0.33%   |
| Goldmont         | 19       | 0.31%   |
| Unknown          | 15       | 0.25%   |
| Tremont          | 12       | 0.2%    |
| TigerLake        | 2        | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 2235     | 35.67%  |
| Intel                      | 2091     | 33.38%  |
| AMD                        | 1916     | 30.58%  |
| Matrox Electronics Systems | 12       | 0.19%   |
| VIA Technologies           | 6        | 0.1%    |
| ATI Technologies           | 3        | 0.05%   |
| Conexant Systems           | 1        | 0.02%   |
| ASPEED Technology          | 1        | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 346      | 5.43%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 255      | 4%      |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 228      | 3.58%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 208      | 3.26%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 182      | 2.85%   |
| Nvidia GK208B [GeForce GT 710]                                              | 168      | 2.63%   |
| Nvidia GT218 [GeForce 210]                                                  | 128      | 2.01%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 128      | 2.01%   |
| Intel HD Graphics 530                                                       | 121      | 1.9%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 120      | 1.88%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 103      | 1.62%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 100      | 1.57%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 98       | 1.54%   |
| Nvidia GK208B [GeForce GT 730]                                              | 95       | 1.49%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 93       | 1.46%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 88       | 1.38%   |
| Intel HD Graphics 630                                                       | 81       | 1.27%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 73       | 1.14%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 70       | 1.1%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 65       | 1.02%   |
| Nvidia GF119 [GeForce GT 610]                                               | 58       | 0.91%   |
| AMD RS780L [Radeon 3000]                                                    | 57       | 0.89%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 55       | 0.86%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 55       | 0.86%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 54       | 0.85%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 54       | 0.85%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 53       | 0.83%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 53       | 0.83%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 52       | 0.82%   |
| Nvidia GF108 [GeForce GT 630]                                               | 45       | 0.71%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 45       | 0.71%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 45       | 0.71%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 44       | 0.69%   |
| Intel Core Processor Integrated Graphics Controller                         | 43       | 0.67%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 40       | 0.63%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 39       | 0.61%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 37       | 0.58%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 37       | 0.58%   |
| AMD Renoir                                                                  | 36       | 0.56%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 34       | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 2123     | 34.95%  |
| 1 x Intel                | 1884     | 31.01%  |
| 1 x AMD                  | 1786     | 29.4%   |
| 2 x AMD                  | 75       | 1.23%   |
| Intel + Nvidia           | 73       | 1.2%    |
| 2 x Intel                | 38       | 0.63%   |
| Intel + AMD              | 32       | 0.53%   |
| AMD + Nvidia             | 26       | 0.43%   |
| 2 x Nvidia               | 14       | 0.23%   |
| 1 x Matrox               | 11       | 0.18%   |
| 1 x VIA                  | 6        | 0.1%    |
| Intel + 2 x Nvidia       | 2        | 0.03%   |
| 3 x AMD                  | 1        | 0.02%   |
| Nvidia + Matrox          | 1        | 0.02%   |
| Nvidia + ASPEED          | 1        | 0.02%   |
| Intel + Conexant Systems | 1        | 0.02%   |
| Intel + AMD + 1 x Nvidia | 1        | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 5814     | 96%     |
| Unknown     | 200      | 3.3%    |
| Proprietary | 42       | 0.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 2075     | 34.12%  |
| 1.01-2.0   | 1070     | 17.59%  |
| 0.51-1.0   | 967      | 15.9%   |
| 0.01-0.5   | 815      | 13.4%   |
| 3.01-4.0   | 455      | 7.48%   |
| 7.01-8.0   | 384      | 6.31%   |
| 5.01-6.0   | 171      | 2.81%   |
| 8.01-16.0  | 72       | 1.18%   |
| 2.01-3.0   | 61       | 1%      |
| 16.01-24.0 | 9        | 0.15%   |
| 4.01-5.0   | 3        | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 1050     | 17.65%  |
| Goldstar             | 710      | 11.93%  |
| Dell                 | 519      | 8.72%   |
| Hewlett-Packard      | 515      | 8.66%   |
| Acer                 | 463      | 7.78%   |
| Philips              | 363      | 6.1%    |
| AOC                  | 344      | 5.78%   |
| BenQ                 | 275      | 4.62%   |
| Ancor Communications | 234      | 3.93%   |
| ViewSonic            | 152      | 2.55%   |
| Iiyama               | 128      | 2.15%   |
| ASUSTek Computer     | 93       | 1.56%   |
| Lenovo               | 73       | 1.23%   |
| Sony                 | 62       | 1.04%   |
| Fujitsu Siemens      | 61       | 1.03%   |
| Eizo                 | 54       | 0.91%   |
| NEC Computers        | 48       | 0.81%   |
| HannStar             | 39       | 0.66%   |
| Medion               | 31       | 0.52%   |
| Sceptre Tech         | 27       | 0.45%   |
| Unknown              | 26       | 0.44%   |
| Panasonic            | 26       | 0.44%   |
| Toshiba              | 24       | 0.4%    |
| Vizio                | 22       | 0.37%   |
| Vestel Elektronik    | 21       | 0.35%   |
| MSI                  | 20       | 0.34%   |
| Sharp                | 17       | 0.29%   |
| Hitachi              | 16       | 0.27%   |
| Belinea              | 16       | 0.27%   |
| MStar                | 14       | 0.24%   |
| Packard Bell         | 13       | 0.22%   |
| Gigabyte Technology  | 13       | 0.22%   |
| Unknown (XXX)        | 12       | 0.2%    |
| ___                  | 11       | 0.18%   |
| IOD                  | 10       | 0.17%   |
| Insignia             | 10       | 0.17%   |
| HKC                  | 10       | 0.17%   |
| Gateway              | 10       | 0.17%   |
| Mi                   | 9        | 0.15%   |
| CHD                  | 9        | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 42       | 0.69%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 29       | 0.48%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 27       | 0.44%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 23       | 0.38%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                        | 23       | 0.38%   |
| Dell D1918H DEL2005 1366x768 410x230mm 18.5-inch                       | 22       | 0.36%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 21       | 0.35%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 21       | 0.35%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                       | 20       | 0.33%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                | 19       | 0.31%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                | 17       | 0.28%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 17       | 0.28%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch  | 17       | 0.28%   |
| Hewlett-Packard w1907 HWP26A2 1440x900 408x255mm 18.9-inch             | 15       | 0.25%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch  | 15       | 0.25%   |
| Philips 273PQPY PHLC096 1920x1080 597x336mm 27.0-inch                  | 14       | 0.23%   |
| Panasonic TV MEIA296 1280x1024 698x392mm 31.5-inch                     | 14       | 0.23%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch      | 13       | 0.21%   |
| Goldstar W2243 GSM56FE 1920x1080 477x268mm 21.5-inch                   | 13       | 0.21%   |
| AOC 24P2W1DG5 AOC2402 1920x1080 527x296mm 23.8-inch                    | 13       | 0.21%   |
| AOC 2460G5 AOC2460 1920x1080 531x299mm 24.0-inch                       | 13       | 0.21%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch      | 12       | 0.2%    |
| MStar Demo MST0030 1366x768 708x398mm 32.0-inch                        | 12       | 0.2%    |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                    | 12       | 0.2%    |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch                | 12       | 0.2%    |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 12       | 0.2%    |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                    | 12       | 0.2%    |
| Acer G246HL ACR02FF 1920x1080 531x299mm 24.0-inch                      | 12       | 0.2%    |
| AOC 936W AOC1936 1366x768 410x230mm 18.5-inch                          | 11       | 0.18%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch   | 10       | 0.16%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch   | 10       | 0.16%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch      | 10       | 0.16%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 10       | 0.16%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 10       | 0.16%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                      | 10       | 0.16%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                       | 10       | 0.16%   |
| Ancor Communications VS278 ACI27A1 1920x1080 598x336mm 27.0-inch       | 10       | 0.16%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch   | 9        | 0.15%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch   | 9        | 0.15%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch               | 9        | 0.15%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 2916     | 49.85%  |
| 1280x1024 (SXGA)   | 537      | 9.18%   |
| 3840x2160 (4K)     | 433      | 7.4%    |
| 1680x1050 (WSXGA+) | 390      | 6.67%   |
| 1366x768 (WXGA)    | 312      | 5.33%   |
| 2560x1440 (QHD)    | 276      | 4.72%   |
| 1440x900 (WXGA+)   | 259      | 4.43%   |
| 1600x900 (HD+)     | 194      | 3.32%   |
| 1920x1200 (WUXGA)  | 150      | 2.56%   |
| 1360x768           | 109      | 1.86%   |
| 3440x1440          | 59       | 1.01%   |
| 2560x1080          | 49       | 0.84%   |
| 1920x540           | 31       | 0.53%   |
| 1024x768 (XGA)     | 30       | 0.51%   |
| 1600x1200          | 21       | 0.36%   |
| 1280x720 (HD)      | 15       | 0.26%   |
| 1280x960           | 12       | 0.21%   |
| 2560x1600          | 9        | 0.15%   |
| 2288x1287          | 8        | 0.14%   |
| 2048x1152          | 7        | 0.12%   |
| 3840x1080          | 6        | 0.1%    |
| Unknown            | 6        | 0.1%    |
| 1280x768           | 5        | 0.09%   |
| 3840x1600          | 3        | 0.05%   |
| 1152x864           | 2        | 0.03%   |
| 6000x1440          | 1        | 0.02%   |
| 5760x2160          | 1        | 0.02%   |
| 5120x1440          | 1        | 0.02%   |
| 4480x2023          | 1        | 0.02%   |
| 3840x1200          | 1        | 0.02%   |
| 3200x1080          | 1        | 0.02%   |
| 2048x1536          | 1        | 0.02%   |
| 1536x2048          | 1        | 0.02%   |
| 1400x1050          | 1        | 0.02%   |
| 1024x600           | 1        | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 892      | 14.96%  |
| 21      | 824      | 13.82%  |
| 27      | 718      | 12.04%  |
| 24      | 701      | 11.76%  |
| 19      | 523      | 8.77%   |
| 18      | 352      | 5.9%    |
| 22      | 289      | 4.85%   |
| 17      | 283      | 4.75%   |
| 31      | 239      | 4.01%   |
| 20      | 219      | 3.67%   |
| Unknown | 107      | 1.79%   |
| 34      | 101      | 1.69%   |
| 84      | 89       | 1.49%   |
| 15      | 89       | 1.49%   |
| 32      | 64       | 1.07%   |
| 40      | 53       | 0.89%   |
| 72      | 49       | 0.82%   |
| 54      | 45       | 0.75%   |
| 25      | 39       | 0.65%   |
| 26      | 29       | 0.49%   |
| 52      | 25       | 0.42%   |
| 28      | 20       | 0.34%   |
| 65      | 17       | 0.29%   |
| 48      | 14       | 0.23%   |
| 37      | 14       | 0.23%   |
| 35      | 13       | 0.22%   |
| 33      | 13       | 0.22%   |
| 46      | 12       | 0.2%    |
| 29      | 12       | 0.2%    |
| 39      | 11       | 0.18%   |
| 42      | 10       | 0.17%   |
| 36      | 8        | 0.13%   |
| 142     | 7        | 0.12%   |
| 60      | 7        | 0.12%   |
| 47      | 7        | 0.12%   |
| 43      | 7        | 0.12%   |
| 16      | 7        | 0.12%   |
| 12      | 7        | 0.12%   |
| 74      | 6        | 0.1%    |
| 55      | 6        | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 2184     | 37.4%   |
| 401-500        | 1927     | 33%     |
| 301-350        | 359      | 6.15%   |
| 601-700        | 348      | 5.96%   |
| 351-400        | 302      | 5.17%   |
| 701-800        | 186      | 3.19%   |
| 1001-1500      | 149      | 2.55%   |
| 1501-2000      | 147      | 2.52%   |
| Unknown        | 107      | 1.83%   |
| 801-900        | 92       | 1.58%   |
| 901-1000       | 20       | 0.34%   |
| 201-300        | 11       | 0.19%   |
| More than 2000 | 7        | 0.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 4055     | 70.63%  |
| 16/10   | 836      | 14.56%  |
| 5/4     | 524      | 9.13%   |
| 21/9    | 113      | 1.97%   |
| 4/3     | 93       | 1.62%   |
| 3/2     | 44       | 0.77%   |
| Unknown | 39       | 0.68%   |
| 6/5     | 13       | 0.23%   |
| 32/9    | 10       | 0.17%   |
| 1.00    | 7        | 0.12%   |
| 2.12    | 2        | 0.03%   |
| 3.20    | 1        | 0.02%   |
| 2.01    | 1        | 0.02%   |
| 1.96    | 1        | 0.02%   |
| 0.75    | 1        | 0.02%   |
| 0.56    | 1        | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 2208     | 37.49%  |
| 151-200        | 1032     | 17.52%  |
| 301-350        | 739      | 12.55%  |
| 141-150        | 550      | 9.34%   |
| 351-500        | 437      | 7.42%   |
| More than 1000 | 277      | 4.7%    |
| 251-300        | 275      | 4.67%   |
| 501-1000       | 143      | 2.43%   |
| Unknown        | 107      | 1.82%   |
| 101-110        | 66       | 1.12%   |
| 111-120        | 22       | 0.37%   |
| 131-140        | 15       | 0.25%   |
| 71-80          | 7        | 0.12%   |
| 91-100         | 5        | 0.08%   |
| 121-130        | 3        | 0.05%   |
| 81-90          | 2        | 0.03%   |
| 51-60          | 1        | 0.02%   |
| 41-50          | 1        | 0.02%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 4098     | 71.16%  |
| 101-120 | 1092     | 18.96%  |
| 1-50    | 243      | 4.22%   |
| 121-160 | 153      | 2.66%   |
| Unknown | 107      | 1.86%   |
| 161-240 | 66       | 1.15%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 5488     | 90.52%  |
| 2     | 427      | 7.04%   |
| 0     | 107      | 1.76%   |
| 3     | 35       | 0.58%   |
| 4     | 4        | 0.07%   |
| 7     | 1        | 0.02%   |
| 5     | 1        | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 3907     | 49.13%  |
| Intel                                 | 1975     | 24.83%  |
| Qualcomm Atheros                      | 588      | 7.39%   |
| Ralink Technology                     | 212      | 2.67%   |
| Broadcom                              | 191      | 2.4%    |
| Nvidia                                | 176      | 2.21%   |
| Ralink                                | 107      | 1.35%   |
| TP-Link                               | 90       | 1.13%   |
| Qualcomm Atheros Communications       | 63       | 0.79%   |
| Marvell Technology Group              | 63       | 0.79%   |
| Broadcom Limited                      | 57       | 0.72%   |
| MediaTek                              | 39       | 0.49%   |
| D-Link System                         | 36       | 0.45%   |
| D-Link                                | 32       | 0.4%    |
| Huawei Technologies                   | 30       | 0.38%   |
| ASUSTek Computer                      | 29       | 0.36%   |
| VIA Technologies                      | 27       | 0.34%   |
| NetGear                               | 26       | 0.33%   |
| Belkin Components                     | 23       | 0.29%   |
| Samsung Electronics                   | 20       | 0.25%   |
| Microsoft                             | 19       | 0.24%   |
| Aquantia                              | 19       | 0.24%   |
| ASIX Electronics                      | 15       | 0.19%   |
| ZTE WCDMA Technologies MSM            | 14       | 0.18%   |
| IMC Networks                          | 14       | 0.18%   |
| Motorola PCS                          | 13       | 0.16%   |
| Edimax Technology                     | 13       | 0.16%   |
| 3Com                                  | 12       | 0.15%   |
| Xiaomi                                | 10       | 0.13%   |
| Linksys                               | 10       | 0.13%   |
| AVM                                   | 10       | 0.13%   |
| OPPO Electronics                      | 7        | 0.09%   |
| Mercucys                              | 5        | 0.06%   |
| JMicron Technology                    | 5        | 0.06%   |
| DisplayLink                           | 5        | 0.06%   |
| ZyDAS                                 | 4        | 0.05%   |
| Wilocity                              | 4        | 0.05%   |
| Qualcomm                              | 4        | 0.05%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 4        | 0.05%   |
| T & A Mobile Phones                   | 3        | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3292     | 37.56%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 236      | 2.69%   |
| Intel I211 Gigabit Network Connection                             | 193      | 2.2%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 182      | 2.08%   |
| Intel Ethernet Connection I217-LM                                 | 172      | 1.96%   |
| Realtek RTL8125 2.5GbE Controller                                 | 170      | 1.94%   |
| Intel Wi-Fi 6 AX200                                               | 166      | 1.89%   |
| Intel Ethernet Connection (2) I219-V                              | 156      | 1.78%   |
| Intel 82579V Gigabit Network Connection                           | 113      | 1.29%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 112      | 1.28%   |
| Nvidia MCP61 Ethernet                                             | 105      | 1.2%    |
| Ralink MT7601U Wireless Adapter                                   | 100      | 1.14%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 87       | 0.99%   |
| Intel Ethernet Controller I225-V                                  | 83       | 0.95%   |
| Intel Ethernet Connection (7) I219-V                              | 82       | 0.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 81       | 0.92%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 78       | 0.89%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 66       | 0.75%   |
| Intel Ethernet Connection I217-V                                  | 55       | 0.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 54       | 0.62%   |
| Qualcomm Atheros AR9271 802.11n                                   | 52       | 0.59%   |
| Intel Wireless-AC 9260                                            | 52       | 0.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 48       | 0.55%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 46       | 0.52%   |
| Intel Ethernet Connection (2) I218-V                              | 43       | 0.49%   |
| Intel Ethernet Connection (2) I219-LM                             | 42       | 0.48%   |
| Intel 82574L Gigabit Network Connection                           | 41       | 0.47%   |
| Intel Wireless 3165                                               | 40       | 0.46%   |
| Ralink RT5370 Wireless Adapter                                    | 39       | 0.44%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 38       | 0.43%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 37       | 0.42%   |
| Intel Wireless 7260                                               | 37       | 0.42%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 36       | 0.41%   |
| Intel Wireless 7265                                               | 36       | 0.41%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 35       | 0.4%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 35       | 0.4%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 35       | 0.4%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 35       | 0.4%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 34       | 0.39%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 33       | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 600      | 26.95%  |
| Realtek Semiconductor                 | 562      | 25.25%  |
| Qualcomm Atheros                      | 284      | 12.76%  |
| Ralink Technology                     | 212      | 9.52%   |
| Ralink                                | 107      | 4.81%   |
| TP-Link                               | 87       | 3.91%   |
| Qualcomm Atheros Communications       | 63       | 2.83%   |
| Broadcom                              | 47       | 2.11%   |
| D-Link                                | 32       | 1.44%   |
| MediaTek                              | 29       | 1.3%    |
| ASUSTek Computer                      | 29       | 1.3%    |
| NetGear                               | 24       | 1.08%   |
| Belkin Components                     | 23       | 1.03%   |
| Microsoft                             | 19       | 0.85%   |
| D-Link System                         | 15       | 0.67%   |
| IMC Networks                          | 14       | 0.63%   |
| Edimax Technology                     | 13       | 0.58%   |
| Linksys                               | 10       | 0.45%   |
| AVM                                   | 10       | 0.45%   |
| Broadcom Limited                      | 6        | 0.27%   |
| Mercucys                              | 5        | 0.22%   |
| ZyDAS                                 | 4        | 0.18%   |
| Wilocity                              | 4        | 0.18%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 4        | 0.18%   |
| ZyXEL Communications                  | 2        | 0.09%   |
| Wacom                                 | 2        | 0.09%   |
| PLANEX                                | 2        | 0.09%   |
| Philips (or NXP)                      | 2        | 0.09%   |
| Guillemot                             | 2        | 0.09%   |
| Chu Yuen Enterprise                   | 2        | 0.09%   |
| VIA Technologies                      | 1        | 0.04%   |
| TRENDnet                              | 1        | 0.04%   |
| Tenda                                 | 1        | 0.04%   |
| Sweex                                 | 1        | 0.04%   |
| Sitecom Europe                        | 1        | 0.04%   |
| Senao                                 | 1        | 0.04%   |
| Micro Star International              | 1        | 0.04%   |
| Logitec                               | 1        | 0.04%   |
| LG Electronics                        | 1        | 0.04%   |
| Gemtek                                | 1        | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 166      | 7.4%    |
| Ralink MT7601U Wireless Adapter                                | 100      | 4.46%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 87       | 3.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 81       | 3.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 54       | 2.41%   |
| Qualcomm Atheros AR9271 802.11n                                | 52       | 2.32%   |
| Intel Wireless-AC 9260                                         | 52       | 2.32%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 48       | 2.14%   |
| Intel Wireless 3165                                            | 40       | 1.78%   |
| Ralink RT5370 Wireless Adapter                                 | 39       | 1.74%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 38       | 1.69%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 37       | 1.65%   |
| Intel Wireless 7260                                            | 37       | 1.65%   |
| Intel Wireless 7265                                            | 36       | 1.61%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 35       | 1.56%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 35       | 1.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 35       | 1.56%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 33       | 1.47%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 32       | 1.43%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 30       | 1.34%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 30       | 1.34%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 28       | 1.25%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 27       | 1.2%    |
| Realtek 802.11ac NIC                                           | 27       | 1.2%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 26       | 1.16%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 26       | 1.16%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 24       | 1.07%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 23       | 1.03%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 22       | 0.98%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 21       | 0.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 20       | 0.89%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 20       | 0.89%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 20       | 0.89%   |
| Intel Wireless 8260                                            | 20       | 0.89%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 18       | 0.8%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 17       | 0.76%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 16       | 0.71%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 15       | 0.67%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 15       | 0.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 14       | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 3731     | 58.84%  |
| Intel                             | 1609     | 25.37%  |
| Qualcomm Atheros                  | 326      | 5.14%   |
| Nvidia                            | 176      | 2.78%   |
| Broadcom                          | 145      | 2.29%   |
| Marvell Technology Group          | 63       | 0.99%   |
| Broadcom Limited                  | 51       | 0.8%    |
| Huawei Technologies               | 28       | 0.44%   |
| VIA Technologies                  | 24       | 0.38%   |
| D-Link System                     | 21       | 0.33%   |
| Aquantia                          | 19       | 0.3%    |
| Samsung Electronics               | 18       | 0.28%   |
| ASIX Electronics                  | 15       | 0.24%   |
| ZTE WCDMA Technologies MSM        | 13       | 0.21%   |
| 3Com                              | 12       | 0.19%   |
| Xiaomi                            | 10       | 0.16%   |
| MediaTek                          | 10       | 0.16%   |
| OPPO Electronics                  | 7        | 0.11%   |
| Motorola PCS                      | 7        | 0.11%   |
| TP-Link                           | 5        | 0.08%   |
| JMicron Technology                | 5        | 0.08%   |
| DisplayLink                       | 5        | 0.08%   |
| Qualcomm                          | 4        | 0.06%   |
| T & A Mobile Phones               | 3        | 0.05%   |
| Silicon Integrated Systems [SiS]  | 3        | 0.05%   |
| Mellanox Technologies             | 3        | 0.05%   |
| HTC (High Tech Computer)          | 3        | 0.05%   |
| Sundance Technology Inc / IC Plus | 2        | 0.03%   |
| Spreadtrum Communications         | 2        | 0.03%   |
| OnePlus Technology (Shenzhen)     | 2        | 0.03%   |
| NetGear                           | 2        | 0.03%   |
| LG Electronics                    | 2        | 0.03%   |
| ICS Advent                        | 2        | 0.03%   |
| HMD Global                        | 2        | 0.03%   |
| vivo                              | 1        | 0.02%   |
| SysKonnect                        | 1        | 0.02%   |
| Netchip Technology                | 1        | 0.02%   |
| Lenovo                            | 1        | 0.02%   |
| IBM                               | 1        | 0.02%   |
| Foxconn / Hon Hai                 | 1        | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3292     | 50.71%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 236      | 3.64%   |
| Intel I211 Gigabit Network Connection                             | 193      | 2.97%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 182      | 2.8%    |
| Intel Ethernet Connection I217-LM                                 | 172      | 2.65%   |
| Realtek RTL8125 2.5GbE Controller                                 | 170      | 2.62%   |
| Intel Ethernet Connection (2) I219-V                              | 156      | 2.4%    |
| Intel 82579V Gigabit Network Connection                           | 113      | 1.74%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 112      | 1.73%   |
| Nvidia MCP61 Ethernet                                             | 105      | 1.62%   |
| Intel Ethernet Controller I225-V                                  | 83       | 1.28%   |
| Intel Ethernet Connection (7) I219-V                              | 82       | 1.26%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 78       | 1.2%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 66       | 1.02%   |
| Intel Ethernet Connection I217-V                                  | 55       | 0.85%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 46       | 0.71%   |
| Intel Ethernet Connection (2) I218-V                              | 43       | 0.66%   |
| Intel Ethernet Connection (2) I219-LM                             | 42       | 0.65%   |
| Intel 82574L Gigabit Network Connection                           | 41       | 0.63%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 36       | 0.55%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 35       | 0.54%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 34       | 0.52%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 31       | 0.48%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 30       | 0.46%   |
| Intel 82578DM Gigabit Network Connection                          | 27       | 0.42%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 27       | 0.42%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 26       | 0.4%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 26       | 0.4%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 26       | 0.4%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 24       | 0.37%   |
| Intel 82578DC Gigabit Network Connection                          | 23       | 0.35%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 23       | 0.35%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 20       | 0.31%   |
| Intel Ethernet Connection (14) I219-V                             | 20       | 0.31%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 19       | 0.29%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 18       | 0.28%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 16       | 0.25%   |
| Intel Ethernet Connection (2) I218-LM                             | 16       | 0.25%   |
| Intel Ethernet Connection (11) I219-V                             | 16       | 0.25%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 15       | 0.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 5979     | 73.39%  |
| WiFi     | 2137     | 26.23%  |
| Modem    | 18       | 0.22%   |
| Unknown  | 13       | 0.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 5052     | 84.58%  |
| WiFi     | 921      | 15.42%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 4321     | 71.39%  |
| 2     | 1537     | 25.39%  |
| 3     | 133      | 2.2%    |
| 0     | 43       | 0.71%   |
| 4     | 15       | 0.25%   |
| 5     | 2        | 0.03%   |
| 7     | 1        | 0.02%   |
| 6     | 1        | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Desktops | Percent |
|---------|----------|---------|
| No      | 4450     | 73.01%  |
| Yes     | 1644     | 26.97%  |
| Unknown | 1        | 0.02%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 546      | 38.32%  |
| Cambridge Silicon Radio         | 399      | 28%     |
| Realtek Semiconductor           | 122      | 8.56%   |
| ASUSTek Computer                | 91       | 6.39%   |
| Broadcom                        | 71       | 4.98%   |
| Qualcomm Atheros Communications | 52       | 3.65%   |
| IMC Networks                    | 40       | 2.81%   |
| MediaTek                        | 17       | 1.19%   |
| Lite-On Technology              | 12       | 0.84%   |
| Integrated System Solution      | 11       | 0.77%   |
| TP-Link                         | 9        | 0.63%   |
| Belkin Components               | 9        | 0.63%   |
| Apple                           | 9        | 0.63%   |
| Dynex                           | 6        | 0.42%   |
| Primax Electronics              | 5        | 0.35%   |
| Ralink                          | 4        | 0.28%   |
| Realtek                         | 3        | 0.21%   |
| Foxconn / Hon Hai               | 3        | 0.21%   |
| Micro Star International        | 2        | 0.14%   |
| Hewlett-Packard                 | 2        | 0.14%   |
| Edimax Technology               | 2        | 0.14%   |
| Dell                            | 2        | 0.14%   |
| Accel Semiconductor             | 2        | 0.14%   |
| Unknown                         | 2        | 0.14%   |
| Unknown                         | 1        | 0.07%   |
| SINO WEALTH                     | 1        | 0.07%   |
| Qcom                            | 1        | 0.07%   |
| i.Tech Dynamic Limited          | 1        | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 399      | 27.96%  |
| Intel AX200 Bluetooth                                    | 154      | 10.79%  |
| Intel Bluetooth wireless interface                       | 148      | 10.37%  |
| Intel Wireless-AC 3168 Bluetooth                         | 77       | 5.4%    |
| Realtek Bluetooth Radio                                  | 75       | 5.26%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 45       | 3.15%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 41       | 2.87%   |
| Intel AX201 Bluetooth                                    | 36       | 2.52%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 36       | 2.52%   |
| Realtek  Bluetooth 4.2 Adapter                           | 34       | 2.38%   |
| Intel AX210 Bluetooth                                    | 32       | 2.24%   |
| Qualcomm Atheros  Bluetooth Device                       | 29       | 2.03%   |
| IMC Networks Bluetooth Radio                             | 29       | 2.03%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 26       | 1.82%   |
| ASUS ASUS USB-BT500                                      | 18       | 1.26%   |
| MediaTek Wireless_Device                                 | 17       | 1.19%   |
| ASUS Bluetooth Radio                                     | 14       | 0.98%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 10       | 0.7%    |
| TP-Link UB500 Adapter                                    | 9        | 0.63%   |
| Qualcomm Atheros AR3011 Bluetooth                        | 9        | 0.63%   |
| Lite-On Bluetooth Device                                 | 8        | 0.56%   |
| Integrated System Solution Bluetooth Device              | 8        | 0.56%   |
| ASUS Qualcomm Bluetooth 4.1                              | 8        | 0.56%   |
| ASUS Bluetooth Adapter                                   | 8        | 0.56%   |
| Qualcomm Atheros AR9462 Bluetooth                        | 7        | 0.49%   |
| Belkin Components Bluetooth Mini Dongle                  | 7        | 0.49%   |
| ASUS Bluetooth Device                                    | 7        | 0.49%   |
| Realtek RTL8821A Bluetooth                               | 6        | 0.42%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 6        | 0.42%   |
| Broadcom BCM2045 Bluetooth                               | 6        | 0.42%   |
| Primax Rocketfish RF-FLBTAD Bluetooth Adapter            | 5        | 0.35%   |
| IMC Networks Wireless_Device                             | 5        | 0.35%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE    | 5        | 0.35%   |
| ASUS BCM20702A0                                          | 5        | 0.35%   |
| Ralink RT3290 Bluetooth                                  | 4        | 0.28%   |
| Qualcomm Atheros Bluetooth USB Host Controller           | 4        | 0.28%   |
| Intel Bluetooth Device                                   | 4        | 0.28%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                  | 3        | 0.21%   |
| Realtek Bluetooth 5.1 Radio                              | 3        | 0.21%   |
| Realtek Bluetooth Radio                                  | 3        | 0.21%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 3755     | 40.49%  |
| AMD                                  | 2490     | 26.85%  |
| Nvidia                               | 2083     | 22.46%  |
| C-Media Electronics                  | 215      | 2.32%   |
| Creative Labs                        | 168      | 1.81%   |
| Logitech                             | 62       | 0.67%   |
| Texas Instruments                    | 41       | 0.44%   |
| JMTek                                | 33       | 0.36%   |
| Generalplus Technology               | 29       | 0.31%   |
| Creative Technology                  | 29       | 0.31%   |
| VIA Technologies                     | 27       | 0.29%   |
| ASUSTek Computer                     | 24       | 0.26%   |
| Razer USA                            | 16       | 0.17%   |
| Tenx Technology                      | 15       | 0.16%   |
| GN Netcom                            | 12       | 0.13%   |
| Kingston Technology                  | 10       | 0.11%   |
| Focusrite-Novation                   | 10       | 0.11%   |
| KTMicro                              | 9        | 0.1%    |
| XMOS                                 | 8        | 0.09%   |
| Plantronics                          | 8        | 0.09%   |
| Giga-Byte Technology                 | 8        | 0.09%   |
| Micro Star International             | 7        | 0.08%   |
| Dell                                 | 7        | 0.08%   |
| SteelSeries ApS                      | 6        | 0.06%   |
| Corsair                              | 6        | 0.06%   |
| Blue Microphones                     | 6        | 0.06%   |
| Yamaha                               | 5        | 0.05%   |
| Thesycon Systemsoftware & Consulting | 5        | 0.05%   |
| Sony                                 | 5        | 0.05%   |
| SAVITECH                             | 5        | 0.05%   |
| Samson Technologies                  | 5        | 0.05%   |
| PreSonus Audio Electronics           | 5        | 0.05%   |
| M-Audio                              | 5        | 0.05%   |
| Hewlett-Packard                      | 5        | 0.05%   |
| GYROCOM C&C                          | 5        | 0.05%   |
| FiiO Electronics Technology          | 5        | 0.05%   |
| Ensoniq                              | 5        | 0.05%   |
| BEHRINGER International              | 5        | 0.05%   |
| Trust                                | 4        | 0.04%   |
| ROCCAT                               | 4        | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 541      | 4.93%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 532      | 4.85%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 522      | 4.76%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 395      | 3.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 393      | 3.58%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 365      | 3.33%   |
| AMD Family 17h/19h HD Audio Controller                                            | 361      | 3.29%   |
| AMD Starship/Matisse HD Audio Controller                                          | 354      | 3.23%   |
| AMD FCH Azalia Controller                                                         | 335      | 3.05%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 285      | 2.6%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 263      | 2.4%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 254      | 2.32%   |
| Intel 200 Series PCH HD Audio                                                     | 234      | 2.13%   |
| Nvidia High Definition Audio Controller                                           | 200      | 1.82%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 190      | 1.73%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 190      | 1.73%   |
| Intel Cannon Lake PCH cAVS                                                        | 183      | 1.67%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 183      | 1.67%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 160      | 1.46%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 157      | 1.43%   |
| Nvidia GF108 High Definition Audio Controller                                     | 144      | 1.31%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 143      | 1.3%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 140      | 1.28%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 123      | 1.12%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 118      | 1.08%   |
| Nvidia MCP61 High Definition Audio                                                | 116      | 1.06%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 115      | 1.05%   |
| Nvidia GF119 HDMI Audio Controller                                                | 111      | 1.01%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 104      | 0.95%   |
| Nvidia TU116 High Definition Audio Controller                                     | 100      | 0.91%   |
| Nvidia GP108 High Definition Audio Controller                                     | 100      | 0.91%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 99       | 0.9%    |
| Nvidia GP106 High Definition Audio Controller                                     | 94       | 0.86%   |
| Nvidia GK107 HDMI Audio Controller                                                | 90       | 0.82%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 85       | 0.77%   |
| AMD Trinity HDMI Audio Controller                                                 | 80       | 0.73%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 80       | 0.73%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 80       | 0.73%   |
| AMD Navi 10 HDMI Audio                                                            | 77       | 0.7%    |
| AMD Kabini HDMI/DP Audio                                                          | 73       | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 1365     | 19.25%  |
| Kingston            | 1284     | 18.11%  |
| Samsung Electronics | 727      | 10.25%  |
| Corsair             | 573      | 8.08%   |
| SK hynix            | 567      | 8%      |
| Crucial             | 514      | 7.25%   |
| G.Skill             | 426      | 6.01%   |
| Micron Technology   | 366      | 5.16%   |
| A-DATA Technology   | 152      | 2.14%   |
| Nanya Technology    | 102      | 1.44%   |
| Patriot             | 88       | 1.24%   |
| Team                | 87       | 1.23%   |
| Unknown             | 82       | 1.16%   |
| Ramaxel Technology  | 69       | 0.97%   |
| GOODRAM             | 63       | 0.89%   |
| Elpida              | 59       | 0.83%   |
| Transcend           | 37       | 0.52%   |
| Smart               | 33       | 0.47%   |
| Apacer              | 31       | 0.44%   |
| AMD                 | 30       | 0.42%   |
| Kingmax             | 24       | 0.34%   |
| GeIL                | 22       | 0.31%   |
| Unifosa             | 20       | 0.28%   |
| Silicon Power       | 19       | 0.27%   |
| Unknown (ABCD)      | 18       | 0.25%   |
| Qimonda             | 14       | 0.2%    |
| PNY                 | 12       | 0.17%   |
| Multilaser          | 12       | 0.17%   |
| Avant               | 12       | 0.17%   |
| Toshiba             | 8        | 0.11%   |
| Teikon              | 8        | 0.11%   |
| CSX                 | 7        | 0.1%    |
| Atermiter           | 7        | 0.1%    |
| Timetec             | 6        | 0.08%   |
| OCZ                 | 6        | 0.08%   |
| Kllisre             | 6        | 0.08%   |
| KLEVV               | 6        | 0.08%   |
| Goldkey             | 6        | 0.08%   |
| TakeMS              | 5        | 0.07%   |
| Super Talent        | 5        | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM 800MT/s                      | 99       | 1.26%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                 | 92       | 1.17%   |
| Unknown RAM Module 2GB DIMM SDRAM                        | 89       | 1.13%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 88       | 1.12%   |
| Unknown                                                  | 82       | 1.04%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                | 66       | 0.84%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                     | 60       | 0.76%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s    | 55       | 0.7%    |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s      | 48       | 0.61%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s      | 47       | 0.6%    |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                 | 46       | 0.58%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                     | 45       | 0.57%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s      | 45       | 0.57%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s      | 45       | 0.57%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s     | 43       | 0.55%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                | 41       | 0.52%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s      | 41       | 0.52%   |
| Unknown RAM Module 1GB DIMM SDRAM                        | 39       | 0.5%    |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                 | 37       | 0.47%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s        | 35       | 0.44%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s      | 35       | 0.44%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                | 32       | 0.41%   |
| Unknown RAM Module 2GB DIMM 400MT/s                      | 32       | 0.41%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s      | 31       | 0.39%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s      | 31       | 0.39%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s        | 30       | 0.38%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                 | 29       | 0.37%   |
| Unknown RAM Module 1GB DIMM 800MT/s                      | 29       | 0.37%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s      | 29       | 0.37%   |
| Corsair RAM CMK16GX4M2B3000C15 8192MB DIMM DDR4 3200MT/s | 29       | 0.37%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                     | 28       | 0.36%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                | 27       | 0.34%   |
| Unknown RAM Module 4GB DIMM SDRAM                        | 27       | 0.34%   |
| SK hynix RAM HMT451U6AFR8C-PB 4096MB DIMM DDR3 1600MT/s  | 27       | 0.34%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s   | 27       | 0.34%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                | 26       | 0.33%   |
| Unknown RAM Module 1GB DIMM 667MT/s                      | 26       | 0.33%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s      | 26       | 0.33%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s     | 26       | 0.33%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s      | 26       | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 2488     | 40.58%  |
| DDR4    | 2069     | 33.75%  |
| Unknown | 568      | 9.26%   |
| DDR2    | 464      | 7.57%   |
| SDRAM   | 413      | 6.74%   |
| DDR     | 90       | 1.47%   |
| LPDDR4  | 21       | 0.34%   |
| DDR5    | 13       | 0.21%   |
| DRAM    | 3        | 0.05%   |
| LPDDR3  | 2        | 0.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 5616     | 94.01%  |
| SODIMM       | 340      | 5.69%   |
| RIMM         | 10       | 0.17%   |
| FB-DIMM      | 7        | 0.12%   |
| Row Of Chips | 1        | 0.02%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 2174     | 32.03%  |
| 4096  | 2093     | 30.84%  |
| 2048  | 1394     | 20.54%  |
| 16384 | 527      | 7.76%   |
| 1024  | 424      | 6.25%   |
| 32768 | 112      | 1.65%   |
| 512   | 58       | 0.85%   |
| 256   | 2        | 0.03%   |
| 3072  | 1        | 0.01%   |
| 64    | 1        | 0.01%   |
| 32    | 1        | 0.01%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 1498     | 21.79%  |
| 1333    | 1063     | 15.46%  |
| 800     | 405      | 5.89%   |
| 2400    | 379      | 5.51%   |
| 3200    | 345      | 5.02%   |
| 2667    | 321      | 4.67%   |
| 3600    | 306      | 4.45%   |
| 2133    | 277      | 4.03%   |
| 667     | 270      | 3.93%   |
| Unknown | 221      | 3.21%   |
| 1867    | 157      | 2.28%   |
| 1866    | 122      | 1.77%   |
| 2666    | 103      | 1.5%    |
| 3400    | 96       | 1.4%    |
| 1066    | 93       | 1.35%   |
| 3000    | 88       | 1.28%   |
| 2933    | 80       | 1.16%   |
| 400     | 80       | 1.16%   |
| 1800    | 77       | 1.12%   |
| 1067    | 65       | 0.95%   |
| 3466    | 61       | 0.89%   |
| 533     | 57       | 0.83%   |
| 3800    | 39       | 0.57%   |
| 3733    | 39       | 0.57%   |
| 2800    | 39       | 0.57%   |
| 1334    | 39       | 0.57%   |
| 3866    | 38       | 0.55%   |
| 3266    | 35       | 0.51%   |
| 2048    | 32       | 0.47%   |
| 3666    | 27       | 0.39%   |
| 2000    | 25       | 0.36%   |
| 333     | 22       | 0.32%   |
| 49926   | 20       | 0.29%   |
| 3066    | 20       | 0.29%   |
| 1648    | 20       | 0.29%   |
| 2200    | 18       | 0.26%   |
| 1639    | 18       | 0.26%   |
| 3333    | 15       | 0.22%   |
| 3500    | 14       | 0.2%    |
| 3151    | 14       | 0.2%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 148      | 39.26%  |
| Brother Industries    | 80       | 21.22%  |
| Canon                 | 52       | 13.79%  |
| Samsung Electronics   | 33       | 8.75%   |
| Seiko Epson           | 32       | 8.49%   |
| Lexmark International | 8        | 2.12%   |
| QinHeng Electronics   | 5        | 1.33%   |
| Prolific Technology   | 5        | 1.33%   |
| Kyocera               | 3        | 0.8%    |
| Dymo-CoStar           | 3        | 0.8%    |
| Xerox                 | 2        | 0.53%   |
| Ricoh                 | 2        | 0.53%   |
| Zebra                 | 1        | 0.27%   |
| Oki Data              | 1        | 0.27%   |
| NXP Semiconductors    | 1        | 0.27%   |
| Citizen               | 1        | 0.27%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| HP DeskJet 2620 All-in-One Printer   | 7        | 1.83%   |
| HP ENVY 4520 series                  | 6        | 1.57%   |
| HP DeskJet 2700 series               | 6        | 1.57%   |
| Samsung M2020 Series                 | 5        | 1.31%   |
| QinHeng CH340S                       | 5        | 1.31%   |
| Prolific PL2305 Parallel Port        | 5        | 1.31%   |
| HP DeskJet 3630 series               | 5        | 1.31%   |
| Brother HL-L2390DW                   | 5        | 1.31%   |
| Samsung ML-1640 Series Laser Printer | 4        | 1.04%   |
| Samsung M2070 Series                 | 4        | 1.04%   |
| HP LaserJet P1006                    | 4        | 1.04%   |
| HP LaserJet P1005                    | 4        | 1.04%   |
| HP LaserJet 1018                     | 4        | 1.04%   |
| HP Ink Tank Wireless 410 series      | 4        | 1.04%   |
| HP DeskJet 2130 series               | 4        | 1.04%   |
| Canon PIXMA MX920 Series             | 4        | 1.04%   |
| Brother Printer                      | 4        | 1.04%   |
| Seiko Epson L120 Series              | 3        | 0.78%   |
| HP LaserJet Pro M148f-M149f          | 3        | 0.78%   |
| HP LaserJet 1020                     | 3        | 0.78%   |
| HP LaserJet 1010                     | 3        | 0.78%   |
| HP Deskjet 1050 J410                 | 3        | 0.78%   |
| Canon TS5100 series                  | 3        | 0.78%   |
| Canon PIXMA MG3600 Series            | 3        | 0.78%   |
| Canon LiDE 300                       | 3        | 0.78%   |
| Brother MFC-L2710DW series           | 3        | 0.78%   |
| Brother MFC-J470DW                   | 3        | 0.78%   |
| Brother HL-L2360D series             | 3        | 0.78%   |
| Brother HL-3140CW series             | 3        | 0.78%   |
| Seiko Epson XP-243 245 247 Series    | 2        | 0.52%   |
| Seiko Epson WF-2510 Series           | 2        | 0.52%   |
| Seiko Epson L6160 Series             | 2        | 0.52%   |
| Seiko Epson L365 Series              | 2        | 0.52%   |
| Seiko Epson L3150 Series             | 2        | 0.52%   |
| Seiko Epson ET-4760 Series           | 2        | 0.52%   |
| Samsung SCX-3400 Series              | 2        | 0.52%   |
| Samsung ML-2010P Mono Laser Printer  | 2        | 0.52%   |
| Samsung M267x 287x Series            | 2        | 0.52%   |
| Samsung CLP-310 Color Laser Printer  | 2        | 0.52%   |
| HP OfficeJet Pro 7720 series         | 2        | 0.52%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Canon                       | 42       | 54.55%  |
| Hewlett-Packard             | 11       | 14.29%  |
| Seiko Epson                 | 9        | 11.69%  |
| Mustek Systems              | 7        | 9.09%   |
| AGFA-Gevaert NV             | 3        | 3.9%    |
| KYE Systems (Mouse Systems) | 2        | 2.6%    |
| Plustek                     | 1        | 1.3%    |
| Fujitsu                     | 1        | 1.3%    |
| Acer Peripherals (now BenQ) | 1        | 1.3%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 210                                  | 6        | 7.79%   |
| Canon CanoScan LiDE 110                                  | 6        | 7.79%   |
| Canon CanoScan LiDE 100                                  | 6        | 7.79%   |
| Canon CanoScan LiDE 120                                  | 4        | 5.19%   |
| Mustek Systems ScanExpress 1200 UB                       | 3        | 3.9%    |
| Canon CanoScan LIDE 25                                   | 3        | 3.9%    |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]            | 2        | 2.6%    |
| HP ScanJet 4500C/5550C                                   | 2        | 2.6%    |
| Canon CanoScan N670U/N676U/LiDE 20                       | 2        | 2.6%    |
| Canon CanoScan N1240U/LiDE 30                            | 2        | 2.6%    |
| Canon CanoScan LiDE 70                                   | 2        | 2.6%    |
| Canon CanoScan LiDE 60                                   | 2        | 2.6%    |
| Canon CanoScan LiDE 220                                  | 2        | 2.6%    |
| Canon CanoScan LiDE 200                                  | 2        | 2.6%    |
| AGFA-Gevaert NV SnapScan e20                             | 2        | 2.6%    |
| Seiko Epson GT-X820 [Perfection V600 Photo]              | 1        | 1.3%    |
| Seiko Epson GT-X770 [Perfection V500]                    | 1        | 1.3%    |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]  | 1        | 1.3%    |
| Seiko Epson GT-F700 [Perfection V350]                    | 1        | 1.3%    |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]        | 1        | 1.3%    |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1        | 1.3%    |
| Seiko Epson GT-7400U [Perfection 1270]                   | 1        | 1.3%    |
| Plustek 600DPI USB Scanner                               | 1        | 1.3%    |
| Mustek Systems SNAPSCAN e22                              | 1        | 1.3%    |
| Mustek Systems ScanExpress 1200 CU                       | 1        | 1.3%    |
| Mustek Systems BearPaw 2448 CU Pro                       | 1        | 1.3%    |
| Mustek Systems BearPaw 1200 CU Plus                      | 1        | 1.3%    |
| KYE Systems (Mouse Systems) ColorPage-Vivid4             | 1        | 1.3%    |
| KYE Systems (Mouse Systems) ColorPage-Vivid 1200 XE      | 1        | 1.3%    |
| HP ScanJet G4010                                         | 1        | 1.3%    |
| HP ScanJet 4570c                                         | 1        | 1.3%    |
| HP ScanJet 4370                                          | 1        | 1.3%    |
| HP ScanJet 3800c                                         | 1        | 1.3%    |
| HP ScanJet 3670                                          | 1        | 1.3%    |
| HP ScanJet 2400c                                         | 1        | 1.3%    |
| HP ScanJet 2300c                                         | 1        | 1.3%    |
| HP ScanJet 2200c                                         | 1        | 1.3%    |
| HP PSC 1200                                              | 1        | 1.3%    |
| Fujitsu ScanSnap SV600                                   | 1        | 1.3%    |
| Canon CanoScan N650U/N656U                               | 1        | 1.3%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 308      | 36.89%  |
| Microdia                               | 70       | 8.38%   |
| Microsoft                              | 56       | 6.71%   |
| Chicony Electronics                    | 30       | 3.59%   |
| Z-Star Microelectronics                | 28       | 3.35%   |
| Realtek Semiconductor                  | 20       | 2.4%    |
| Generalplus Technology                 | 19       | 2.28%   |
| GEMBIRD                                | 19       | 2.28%   |
| Sunplus Innovation Technology          | 18       | 2.16%   |
| Samsung Electronics                    | 16       | 1.92%   |
| KYE Systems (Mouse Systems)            | 16       | 1.92%   |
| Aveo Technology                        | 16       | 1.92%   |
| Creative Technology                    | 15       | 1.8%    |
| Cubeternet                             | 13       | 1.56%   |
| ARC International                      | 13       | 1.56%   |
| Apple                                  | 12       | 1.44%   |
| Jieli Technology                       | 11       | 1.32%   |
| Hewlett-Packard                        | 11       | 1.32%   |
| Huawei Technologies                    | 9        | 1.08%   |
| Trust                                  | 8        | 0.96%   |
| Alcor Micro                            | 7        | 0.84%   |
| Genesys Logic                          | 6        | 0.72%   |
| Arkmicro Technologies                  | 6        | 0.72%   |
| WaveRider Communications               | 5        | 0.6%    |
| Unknown                                | 5        | 0.6%    |
| Pixart Imaging                         | 5        | 0.6%    |
| MacroSilicon                           | 5        | 0.6%    |
| A4Tech                                 | 5        | 0.6%    |
| 2M UVC CAMERA                          | 5        | 0.6%    |
| Sonix Technology                       | 4        | 0.48%   |
| Razer USA                              | 4        | 0.48%   |
| IMC Networks                           | 4        | 0.48%   |
| AVerMedia Technologies                 | 4        | 0.48%   |
| WCM_USB                                | 3        | 0.36%   |
| Silicon Motion                         | 3        | 0.36%   |
| LG Electronics                         | 3        | 0.36%   |
| Guillemot                              | 3        | 0.36%   |
| Cheng Uei Precision Industry (Foxlink) | 3        | 0.36%   |
| USB3.0 HD Audio Capture                | 2        | 0.24%   |
| Tobii Technology AB                    | 2        | 0.24%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech Webcam C270                    | 75       | 8.96%   |
| Logitech HD Pro Webcam C920             | 38       | 4.54%   |
| Logitech Webcam C310                    | 31       | 3.7%    |
| Logitech HD Webcam C525                 | 26       | 3.11%   |
| Microsoft LifeCam HD-3000               | 21       | 2.51%   |
| Logitech Webcam C170                    | 19       | 2.27%   |
| GEMBIRD USB2.0 PC CAMERA                | 19       | 2.27%   |
| Samsung Galaxy series, misc. (MTP mode) | 16       | 1.91%   |
| Microdia Camera                         | 16       | 1.91%   |
| Generalplus GENERAL WEBCAM              | 15       | 1.79%   |
| Microdia USB 2.0 Camera                 | 14       | 1.67%   |
| ARC International Camera                | 13       | 1.55%   |
| Microdia Webcam Vitade AF               | 12       | 1.43%   |
| Aveo USB2.0 Camera                      | 12       | 1.43%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X         | 12       | 1.43%   |
| Logitech QuickCam Pro 9000              | 11       | 1.31%   |
| Logitech HD Webcam C615                 | 11       | 1.31%   |
| Jieli USB PHY 2.0                       | 11       | 1.31%   |
| Microdia Sonix USB 2.0 Camera           | 9        | 1.08%   |
| Logitech C922 Pro Stream Webcam         | 9        | 1.08%   |
| Huawei HiCamera                         | 9        | 1.08%   |
| Z-Star Vimicro USB Camera (Altair)      | 8        | 0.96%   |
| Microdia Integrated Camera              | 8        | 0.96%   |
| Logitech HD Webcam C910                 | 8        | 0.96%   |
| Cubeternet USB2.0 Camera                | 8        | 0.96%   |
| Sunplus Canyon CNS-CWC5 Webcam          | 7        | 0.84%   |
| Microsoft LifeCam Cinema                | 7        | 0.84%   |
| Z-Star Venus USB2.0 Camera              | 6        | 0.72%   |
| Realtek Full HD webcam                  | 6        | 0.72%   |
| Logitech Webcam C930e                   | 6        | 0.72%   |
| Logitech Webcam C250                    | 6        | 0.72%   |
| Logitech HD Webcam C510                 | 6        | 0.72%   |
| Creative Live! Cam Sync HD [VF0770]     | 6        | 0.72%   |
| Chicony HP High Definition 1MP Webcam   | 6        | 0.72%   |
| Alcor Micro USB 2.0 PC Camera           | 6        | 0.72%   |
| Z-Star A4 TECH USB2.0 PC Camera J       | 5        | 0.6%    |
| WaveRider USB 2.0 Camera                | 5        | 0.6%    |
| Microsoft LifeCam VX-5000               | 5        | 0.6%    |
| Microsoft LifeCam Studio                | 5        | 0.6%    |
| Microsoft LifeCam HD-5000               | 5        | 0.6%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| AuthenTec             | 3        | 37.5%   |
| Upek                  | 2        | 25%     |
| Validity Sensors      | 1        | 12.5%   |
| LighTuning Technology | 1        | 12.5%   |
| DigitalPersona        | 1        | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2        | 25%     |
| AuthenTec AES1600                                      | 2        | 25%     |
| Validity Sensors VFS 5011 fingerprint sensor           | 1        | 12.5%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1        | 12.5%   |
| DigitalPersona Fingerprint Reader                      | 1        | 12.5%   |
| AuthenTec Fingerprint Sensor                           | 1        | 12.5%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Alcor Micro                       | 6        | 19.35%  |
| SCM Microsystems                  | 5        | 16.13%  |
| Gemalto (was Gemplus)             | 4        | 12.9%   |
| Realtek Semiconductor             | 3        | 9.68%   |
| Bit4id                            | 3        | 9.68%   |
| Reiner SCT Kartensysteme          | 2        | 6.45%   |
| OmniKey                           | 2        | 6.45%   |
| Advanced Card Systems             | 2        | 6.45%   |
| VASCO Data Security International | 1        | 3.23%   |
| Fujitsu Siemens Computers         | 1        | 3.23%   |
| Cherry                            | 1        | 3.23%   |
| Castles Technology                | 1        | 3.23%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                        | 4        | 12.9%   |
| Realtek Semiconductor Smart Card Reader Interface                          | 3        | 9.68%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                          | 3        | 9.68%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 2        | 6.45%   |
| Bit4id miniLector EVO                                                      | 2        | 6.45%   |
| Alcor Micro Watchdata W 1981                                               | 2        | 6.45%   |
| Advanced Card Systems ACR38 SmartCard Reader                               | 2        | 6.45%   |
| VASCO Data Security International Digipass 905 SmartCard Reader            | 1        | 3.23%   |
| SCM Microsystems uTrust 3700 F CL Reader                                   | 1        | 3.23%   |
| SCM Microsystems SCR335 SmartCard Reader                                   | 1        | 3.23%   |
| SCM Microsystems SCR333 SmartCard Reader                                   | 1        | 3.23%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                     | 1        | 3.23%   |
| SCM Microsystems CLOUD 2700 F Smart Card Reader                            | 1        | 3.23%   |
| OmniKey CardMan 3021 / 3121                                                | 1        | 3.23%   |
| OmniKey CardMan 1021                                                       | 1        | 3.23%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                           | 1        | 3.23%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                              | 1        | 3.23%   |
| Cherry Smart Terminal XX44                                                 | 1        | 3.23%   |
| Castles Technology EZC                                                     | 1        | 3.23%   |
| BIT4ID miniLector AIR NFC v3                                               | 1        | 3.23%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 5504     | 90.84%  |
| 1     | 515      | 8.5%    |
| 2     | 33       | 0.54%   |
| 3     | 4        | 0.07%   |
| 7     | 1        | 0.02%   |
| 6     | 1        | 0.02%   |
| 4     | 1        | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 260      | 43.62%  |
| Net/wireless             | 130      | 21.81%  |
| Unassigned class         | 44       | 7.38%   |
| Communication controller | 34       | 5.7%    |
| Multimedia controller    | 33       | 5.54%   |
| Chipcard                 | 29       | 4.87%   |
| Camera                   | 16       | 2.68%   |
| Bluetooth                | 13       | 2.18%   |
| Fingerprint reader       | 8        | 1.34%   |
| Network                  | 6        | 1.01%   |
| Card reader              | 5        | 0.84%   |
| Sound                    | 4        | 0.67%   |
| Wireless                 | 3        | 0.5%    |
| Net/ethernet             | 3        | 0.5%    |
| Modem                    | 3        | 0.5%    |
| Storage/raid             | 2        | 0.34%   |
| Storage/ata              | 2        | 0.34%   |
| Unclassified device      | 1        | 0.17%   |

