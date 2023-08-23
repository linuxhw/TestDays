Fedora 38 - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for Fedora 38.

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

Total: 756

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | X99A RAIDER                 | [90816726b0](https://linux-hardware.org/?probe=90816726b0) | Aug 12, 2023 |
| MSI           | PRO Z790-P WIFI             | [5b9aef438f](https://linux-hardware.org/?probe=5b9aef438f) | Aug 12, 2023 |
| MSI           | PRO Z790-P WIFI             | [1f3f8a869b](https://linux-hardware.org/?probe=1f3f8a869b) | Aug 12, 2023 |
| Gigabyte      | Z170-HD3P-CF                | [7ef87af541](https://linux-hardware.org/?probe=7ef87af541) | Aug 12, 2023 |
| ASUSTek       | PRIME A520M-E               | [92f4e14369](https://linux-hardware.org/?probe=92f4e14369) | Aug 11, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | [d4b93affe2](https://linux-hardware.org/?probe=d4b93affe2) | Aug 11, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | [7a8e32eb89](https://linux-hardware.org/?probe=7a8e32eb89) | Aug 11, 2023 |
| Unknown       | Unknown                     | [4b174f07d2](https://linux-hardware.org/?probe=4b174f07d2) | Aug 11, 2023 |
| Lenovo        | IdeaCentre B320             | [175fb6f041](https://linux-hardware.org/?probe=175fb6f041) | Aug 11, 2023 |
| Gigabyte      | Z170N-WIFI-CF               | [2ee88f0ec0](https://linux-hardware.org/?probe=2ee88f0ec0) | Aug 11, 2023 |
| MSI           | X99A RAIDER                 | [ee1a7cb0aa](https://linux-hardware.org/?probe=ee1a7cb0aa) | Aug 11, 2023 |
| ASUSTek       | P8Z68-V LE                  | [a88d7e81e5](https://linux-hardware.org/?probe=a88d7e81e5) | Aug 11, 2023 |
| ASUSTek       | PRIME B550M-A               | [7da6954bc5](https://linux-hardware.org/?probe=7da6954bc5) | Aug 10, 2023 |
| Dell          | 0MGK50 A01                  | [ac0ed4109e](https://linux-hardware.org/?probe=ac0ed4109e) | Aug 10, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [c5491b8e9f](https://linux-hardware.org/?probe=c5491b8e9f) | Aug 10, 2023 |
| Unknown       | Unknown                     | [09037ac346](https://linux-hardware.org/?probe=09037ac346) | Aug 09, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [466419add0](https://linux-hardware.org/?probe=466419add0) | Aug 09, 2023 |
| Huanan        | X99-TF-Q GAMING V1.2        | [da612198cc](https://linux-hardware.org/?probe=da612198cc) | Aug 09, 2023 |
| Unknown       | HX90                        | [7a14bb927e](https://linux-hardware.org/?probe=7a14bb927e) | Aug 09, 2023 |
| ASRock        | AB350 Pro4                  | [1aa926149a](https://linux-hardware.org/?probe=1aa926149a) | Aug 09, 2023 |
| Dell          | 06CJMN A00                  | [cead9bd601](https://linux-hardware.org/?probe=cead9bd601) | Aug 09, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | [ee7bcf8fe1](https://linux-hardware.org/?probe=ee7bcf8fe1) | Aug 08, 2023 |
| MSI           | B450 GAMING PLUS            | [c8553cabce](https://linux-hardware.org/?probe=c8553cabce) | Aug 08, 2023 |
| Gigabyte      | H510M S2H                   | [72eb04ca17](https://linux-hardware.org/?probe=72eb04ca17) | Aug 08, 2023 |
| MSI           | Z170A GAMING M9 ACK         | [8839aa58c4](https://linux-hardware.org/?probe=8839aa58c4) | Aug 08, 2023 |
| HP            | 3397                        | [d7edc80c00](https://linux-hardware.org/?probe=d7edc80c00) | Aug 08, 2023 |
| ASUSTek       | PHOENIX                     | [388bcf4158](https://linux-hardware.org/?probe=388bcf4158) | Aug 08, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | [ee8f18e185](https://linux-hardware.org/?probe=ee8f18e185) | Aug 07, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [04e63e59bd](https://linux-hardware.org/?probe=04e63e59bd) | Aug 07, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [3d4073bb1d](https://linux-hardware.org/?probe=3d4073bb1d) | Aug 07, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [c3df1aaae9](https://linux-hardware.org/?probe=c3df1aaae9) | Aug 06, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | [c003e20331](https://linux-hardware.org/?probe=c003e20331) | Aug 06, 2023 |
| ASRock        | X470 Taichi                 | [f9d29dca0d](https://linux-hardware.org/?probe=f9d29dca0d) | Aug 06, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [932391bfea](https://linux-hardware.org/?probe=932391bfea) | Aug 06, 2023 |
| Gateway       | SX2185                      | [a6df16b355](https://linux-hardware.org/?probe=a6df16b355) | Aug 05, 2023 |
| ASUSTek       | Z97-K                       | [4c1ef04fe9](https://linux-hardware.org/?probe=4c1ef04fe9) | Aug 05, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [40bc2f506a](https://linux-hardware.org/?probe=40bc2f506a) | Aug 05, 2023 |
| MSI           | X99A RAIDER                 | [87fc943eb1](https://linux-hardware.org/?probe=87fc943eb1) | Aug 05, 2023 |
| ASUSTek       | PRIME B450M-A               | [d2d45c853b](https://linux-hardware.org/?probe=d2d45c853b) | Aug 05, 2023 |
| ASUSTek       | PRIME B450M-A               | [f18b2ff744](https://linux-hardware.org/?probe=f18b2ff744) | Aug 05, 2023 |
| ASUSTek       | PRIME B550M-A               | [364b15d850](https://linux-hardware.org/?probe=364b15d850) | Aug 05, 2023 |
| Intel         | B75                         | [9411dd987c](https://linux-hardware.org/?probe=9411dd987c) | Aug 05, 2023 |
| ASUSTek       | PHOENIX                     | [193262b7ea](https://linux-hardware.org/?probe=193262b7ea) | Aug 05, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | [5dc4c594ea](https://linux-hardware.org/?probe=5dc4c594ea) | Aug 05, 2023 |
| MSI           | PRO H610M-G WIFI DDR4       | [d8b172537e](https://linux-hardware.org/?probe=d8b172537e) | Aug 04, 2023 |
| AZW           | GTR V02                     | [b2afc2c53e](https://linux-hardware.org/?probe=b2afc2c53e) | Aug 04, 2023 |
| Gigabyte      | GA-MA785G-UD3H              | [a02f0405a3](https://linux-hardware.org/?probe=a02f0405a3) | Aug 04, 2023 |
| Dell          | 05XGC8 A01                  | [de1c7d119e](https://linux-hardware.org/?probe=de1c7d119e) | Aug 04, 2023 |
| MSI           | X99A RAIDER                 | [4077d11575](https://linux-hardware.org/?probe=4077d11575) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [a260479012](https://linux-hardware.org/?probe=a260479012) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [3c3d90d709](https://linux-hardware.org/?probe=3c3d90d709) | Aug 04, 2023 |
| ASUSTek       | PRIME B550M-A               | [c0a4bb6c7e](https://linux-hardware.org/?probe=c0a4bb6c7e) | Aug 03, 2023 |
| Gigabyte      | Z68P-DS3                    | [aa6b646b24](https://linux-hardware.org/?probe=aa6b646b24) | Aug 03, 2023 |
| HP            | 1791                        | [61285d3724](https://linux-hardware.org/?probe=61285d3724) | Aug 03, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | [2d10ecdff1](https://linux-hardware.org/?probe=2d10ecdff1) | Aug 03, 2023 |
| ASUSTek       | PRIME Z270-P                | [219278bb56](https://linux-hardware.org/?probe=219278bb56) | Aug 03, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | [a449d60316](https://linux-hardware.org/?probe=a449d60316) | Aug 03, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [3f5df1b569](https://linux-hardware.org/?probe=3f5df1b569) | Aug 03, 2023 |
| ASRock        | Z170 Gaming K4              | [2c10cb0378](https://linux-hardware.org/?probe=2c10cb0378) | Aug 02, 2023 |
| Gigabyte      | B450M DS3H-CF               | [c66b1ed22c](https://linux-hardware.org/?probe=c66b1ed22c) | Aug 02, 2023 |
| MSI           | B560M PRO-E                 | [b10154befd](https://linux-hardware.org/?probe=b10154befd) | Aug 02, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [883a115efd](https://linux-hardware.org/?probe=883a115efd) | Aug 02, 2023 |
| Gigabyte      | H410M H V3                  | [2d1e78ec7e](https://linux-hardware.org/?probe=2d1e78ec7e) | Aug 02, 2023 |
| ASRock        | B450M Pro4 R2.0             | [5bbfe225b6](https://linux-hardware.org/?probe=5bbfe225b6) | Aug 02, 2023 |
| ASRock        | A320M-HDV R4.0              | [2ff30156cf](https://linux-hardware.org/?probe=2ff30156cf) | Aug 02, 2023 |
| ASRock        | B450M Pro4 R2.0             | [8c9bca1e79](https://linux-hardware.org/?probe=8c9bca1e79) | Aug 02, 2023 |
| MSI           | B450M BAZOOKA V2            | [f37f2f707b](https://linux-hardware.org/?probe=f37f2f707b) | Aug 02, 2023 |
| Gigabyte      | B550 GAMING X V2            | [8353d48977](https://linux-hardware.org/?probe=8353d48977) | Aug 01, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [abe7173905](https://linux-hardware.org/?probe=abe7173905) | Aug 01, 2023 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [13d25503d7](https://linux-hardware.org/?probe=13d25503d7) | Aug 01, 2023 |
| ASRock        | H61M/U3S3                   | [33c887e577](https://linux-hardware.org/?probe=33c887e577) | Aug 01, 2023 |
| Unknown       | Unknown                     | [7a5ef06c39](https://linux-hardware.org/?probe=7a5ef06c39) | Aug 01, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [afbf5d75c1](https://linux-hardware.org/?probe=afbf5d75c1) | Jul 31, 2023 |
| ASRock        | H110M-HG4                   | [7584e2db20](https://linux-hardware.org/?probe=7584e2db20) | Jul 31, 2023 |
| MSI           | B450M PRO-VDH MAX           | [a7cf8e8ef1](https://linux-hardware.org/?probe=a7cf8e8ef1) | Jul 31, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [a3bbf1ecd0](https://linux-hardware.org/?probe=a3bbf1ecd0) | Jul 31, 2023 |
| Gigabyte      | GA-880GM-UD2H               | [bb88f3afdc](https://linux-hardware.org/?probe=bb88f3afdc) | Jul 31, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS        | [7890c76098](https://linux-hardware.org/?probe=7890c76098) | Jul 31, 2023 |
| HP            | 8056                        | [3a98a11778](https://linux-hardware.org/?probe=3a98a11778) | Jul 30, 2023 |
| HP            | 0AECh D                     | [50c84d005e](https://linux-hardware.org/?probe=50c84d005e) | Jul 30, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | [6bf2e91f31](https://linux-hardware.org/?probe=6bf2e91f31) | Jul 30, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | [0f9accc3e8](https://linux-hardware.org/?probe=0f9accc3e8) | Jul 30, 2023 |
| HP            | 8617                        | [0c3ee28cd8](https://linux-hardware.org/?probe=0c3ee28cd8) | Jul 30, 2023 |
| MSI           | Z87-G45 GAMING              | [6c5528a787](https://linux-hardware.org/?probe=6c5528a787) | Jul 30, 2023 |
| Gigabyte      | H77N-WIFI                   | [4fb6a46f65](https://linux-hardware.org/?probe=4fb6a46f65) | Jul 30, 2023 |
| ASRock        | X570 Phantom Gaming X       | [df34eb4472](https://linux-hardware.org/?probe=df34eb4472) | Jul 30, 2023 |
| MSI           | A320M PRO-VH PLUS           | [f5cc7a2d00](https://linux-hardware.org/?probe=f5cc7a2d00) | Jul 30, 2023 |
| ASRock        | X570 Phantom Gaming X       | [0449350f3d](https://linux-hardware.org/?probe=0449350f3d) | Jul 30, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | [9469c1037c](https://linux-hardware.org/?probe=9469c1037c) | Jul 29, 2023 |
| HP            | 3397                        | [98e4e362d9](https://linux-hardware.org/?probe=98e4e362d9) | Jul 29, 2023 |
| ASUSTek       | H110M-D                     | [9669adfa57](https://linux-hardware.org/?probe=9669adfa57) | Jul 29, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | [580c4fb755](https://linux-hardware.org/?probe=580c4fb755) | Jul 29, 2023 |
| MSI           | A520M-A PRO                 | [733695ae93](https://linux-hardware.org/?probe=733695ae93) | Jul 29, 2023 |
| MSI           | A320M PRO-VH                | [0728a96775](https://linux-hardware.org/?probe=0728a96775) | Jul 29, 2023 |
| ASRock        | H110M-HG4                   | [205f3a047f](https://linux-hardware.org/?probe=205f3a047f) | Jul 28, 2023 |
| Gigabyte      | B550 GAMING X V2            | [dcd24dfdc7](https://linux-hardware.org/?probe=dcd24dfdc7) | Jul 28, 2023 |
| ASUSTek       | WS C246 PRO                 | [cfffc2ba92](https://linux-hardware.org/?probe=cfffc2ba92) | Jul 28, 2023 |
| Gigabyte      | B550M DS3H AC               | [2e0e88694a](https://linux-hardware.org/?probe=2e0e88694a) | Jul 28, 2023 |
| Gigabyte      | J1900M-D2P                  | [7864dbf54c](https://linux-hardware.org/?probe=7864dbf54c) | Jul 28, 2023 |
| Gigabyte      | B550M DS3H AC               | [f7c6565b62](https://linux-hardware.org/?probe=f7c6565b62) | Jul 28, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [49daa98623](https://linux-hardware.org/?probe=49daa98623) | Jul 28, 2023 |
| MSI           | Z270 GAMING PLUS            | [cc489fad92](https://linux-hardware.org/?probe=cc489fad92) | Jul 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [e46fa3639e](https://linux-hardware.org/?probe=e46fa3639e) | Jul 27, 2023 |
| Gigabyte      | H77N-WIFI                   | [abf0e5979c](https://linux-hardware.org/?probe=abf0e5979c) | Jul 27, 2023 |
| ASUSTek       | PHOENIX                     | [aad7b03818](https://linux-hardware.org/?probe=aad7b03818) | Jul 27, 2023 |
| ASUSTek       | PRIME B550M-A               | [02cf19407b](https://linux-hardware.org/?probe=02cf19407b) | Jul 26, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [aed4f431ec](https://linux-hardware.org/?probe=aed4f431ec) | Jul 26, 2023 |
| Lenovo        | SDK0E50510 WIN              | [f375185ce4](https://linux-hardware.org/?probe=f375185ce4) | Jul 26, 2023 |
| MSI           | X99A RAIDER                 | [9b1ae569c1](https://linux-hardware.org/?probe=9b1ae569c1) | Jul 26, 2023 |
| MSI           | A520M-A PRO                 | [b731684f10](https://linux-hardware.org/?probe=b731684f10) | Jul 25, 2023 |
| Gigabyte      | B365M H                     | [12902831a7](https://linux-hardware.org/?probe=12902831a7) | Jul 25, 2023 |
| Gigabyte      | J1900M-D2P                  | [31b7924358](https://linux-hardware.org/?probe=31b7924358) | Jul 25, 2023 |
| ASUSTek       | PRIME B550M-A               | [0ecaae8a05](https://linux-hardware.org/?probe=0ecaae8a05) | Jul 25, 2023 |
| MSI           | X99A RAIDER                 | [7ee6422d01](https://linux-hardware.org/?probe=7ee6422d01) | Jul 25, 2023 |
| Unknown       | Unknown                     | [a7d120e20a](https://linux-hardware.org/?probe=a7d120e20a) | Jul 24, 2023 |
| ASUSTek       | PHOENIX                     | [66ab03991c](https://linux-hardware.org/?probe=66ab03991c) | Jul 24, 2023 |
| Gigabyte      | B75M-D2V                    | [60b9e2fbc9](https://linux-hardware.org/?probe=60b9e2fbc9) | Jul 24, 2023 |
| ASUSTek       | PRIME B550M-A               | [b892c011a8](https://linux-hardware.org/?probe=b892c011a8) | Jul 24, 2023 |
| ASRock        | Z690 Pro RS                 | [2afa2c2afe](https://linux-hardware.org/?probe=2afa2c2afe) | Jul 23, 2023 |
| Gigabyte      | H510M S2H V2                | [95290b34e3](https://linux-hardware.org/?probe=95290b34e3) | Jul 23, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | [e1f3c75353](https://linux-hardware.org/?probe=e1f3c75353) | Jul 23, 2023 |
| MSI           | Z170A SLI PLUS              | [a3ccd7aece](https://linux-hardware.org/?probe=a3ccd7aece) | Jul 23, 2023 |
| Gigabyte      | B550M DS3H                  | [04982390e0](https://linux-hardware.org/?probe=04982390e0) | Jul 23, 2023 |
| Gigabyte      | B550M DS3H                  | [b13bb2310f](https://linux-hardware.org/?probe=b13bb2310f) | Jul 23, 2023 |
| ASUSTek       | PRIME Z370-A                | [9a2136d9ef](https://linux-hardware.org/?probe=9a2136d9ef) | Jul 23, 2023 |
| Gigabyte      | B360M D2V                   | [eef08e2598](https://linux-hardware.org/?probe=eef08e2598) | Jul 22, 2023 |
| Dell          | 06D7TR A00                  | [b957598d8e](https://linux-hardware.org/?probe=b957598d8e) | Jul 22, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [51ca7593a6](https://linux-hardware.org/?probe=51ca7593a6) | Jul 22, 2023 |
| Kllisre       | X99-B5 V1.1                 | [b132b3f39c](https://linux-hardware.org/?probe=b132b3f39c) | Jul 21, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [8c79a454ff](https://linux-hardware.org/?probe=8c79a454ff) | Jul 21, 2023 |
| MACHINIST     | E5-D8-MAX V1.1              | [ea68d9762b](https://linux-hardware.org/?probe=ea68d9762b) | Jul 21, 2023 |
| Shenzhen M... | HX90G                       | [355ac636c1](https://linux-hardware.org/?probe=355ac636c1) | Jul 21, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | [e8249dc6d6](https://linux-hardware.org/?probe=e8249dc6d6) | Jul 21, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | [37132be6bd](https://linux-hardware.org/?probe=37132be6bd) | Jul 21, 2023 |
| MSI           | A320M PRO-VH PLUS           | [689b191bae](https://linux-hardware.org/?probe=689b191bae) | Jul 21, 2023 |
| MSI           | PRO B550-VC                 | [5439295c30](https://linux-hardware.org/?probe=5439295c30) | Jul 20, 2023 |
| ASUSTek       | PRIME Z270-P                | [e9c650988e](https://linux-hardware.org/?probe=e9c650988e) | Jul 20, 2023 |
| ASRock        | B450M Pro4 R2.0             | [b3a1dbc5d0](https://linux-hardware.org/?probe=b3a1dbc5d0) | Jul 19, 2023 |
| MSI           | B450M MORTAR MAX            | [22bbaa5937](https://linux-hardware.org/?probe=22bbaa5937) | Jul 19, 2023 |
| ASUSTek       | TUF B360-PLUS GAMING        | [173929b667](https://linux-hardware.org/?probe=173929b667) | Jul 19, 2023 |
| Dell          | 0MN1TX A01                  | [696072cf7c](https://linux-hardware.org/?probe=696072cf7c) | Jul 18, 2023 |
| LattePanda    | 3 Delta LP-BS-7-S70JR120... | [0296e5fd5c](https://linux-hardware.org/?probe=0296e5fd5c) | Jul 18, 2023 |
| Gigabyte      | Z270XP-SLI-CF               | [14478a9226](https://linux-hardware.org/?probe=14478a9226) | Jul 18, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [3618885533](https://linux-hardware.org/?probe=3618885533) | Jul 18, 2023 |
| Gigabyte      | B450M GAMING                | [d0fff20fb0](https://linux-hardware.org/?probe=d0fff20fb0) | Jul 18, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | [d2c6c9bcba](https://linux-hardware.org/?probe=d2c6c9bcba) | Jul 18, 2023 |
| ASUSTek       | M11AD                       | [4019d4eb57](https://linux-hardware.org/?probe=4019d4eb57) | Jul 18, 2023 |
| MSI           | IONA                        | [7b8b6c38e1](https://linux-hardware.org/?probe=7b8b6c38e1) | Jul 18, 2023 |
| ASRock        | X570M Pro4                  | [bb84df2364](https://linux-hardware.org/?probe=bb84df2364) | Jul 18, 2023 |
| ASRock        | X570M Pro4                  | [b8caf7c9a3](https://linux-hardware.org/?probe=b8caf7c9a3) | Jul 18, 2023 |
| HP            | 3048h                       | [ad7b0d8c8d](https://linux-hardware.org/?probe=ad7b0d8c8d) | Jul 17, 2023 |
| Gigabyte      | B550 GAMING X V2            | [60d7a077dc](https://linux-hardware.org/?probe=60d7a077dc) | Jul 17, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [62238aaf82](https://linux-hardware.org/?probe=62238aaf82) | Jul 17, 2023 |
| ASRock        | H510M-HDV/M.2               | [4c07b0b74c](https://linux-hardware.org/?probe=4c07b0b74c) | Jul 17, 2023 |
| ASUSTek       | Maximus VIII HERO           | [49e298a314](https://linux-hardware.org/?probe=49e298a314) | Jul 17, 2023 |
| ASUSTek       | Maximus VIII HERO           | [d8595efd58](https://linux-hardware.org/?probe=d8595efd58) | Jul 17, 2023 |
| ASRock        | B450M Pro4 R2.0             | [6039e0f3c4](https://linux-hardware.org/?probe=6039e0f3c4) | Jul 17, 2023 |
| Dell          | 0WMJ54 A01                  | [07161141b4](https://linux-hardware.org/?probe=07161141b4) | Jul 16, 2023 |
| MSI           | PRO B650-P WIFI             | [65afe9f74b](https://linux-hardware.org/?probe=65afe9f74b) | Jul 16, 2023 |
| MSI           | 2A9C                        | [eaaf1d2a5a](https://linux-hardware.org/?probe=eaaf1d2a5a) | Jul 16, 2023 |
| HP            | ProLiant ML110 G7           | [2278b34727](https://linux-hardware.org/?probe=2278b34727) | Jul 16, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | [5bf40815d5](https://linux-hardware.org/?probe=5bf40815d5) | Jul 16, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [b7992c5de7](https://linux-hardware.org/?probe=b7992c5de7) | Jul 16, 2023 |
| ASRock        | Z690 Pro RS                 | [3becbb23af](https://linux-hardware.org/?probe=3becbb23af) | Jul 15, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [14bae4d3e7](https://linux-hardware.org/?probe=14bae4d3e7) | Jul 15, 2023 |
| Gateway       | SX2185                      | [1fe932f485](https://linux-hardware.org/?probe=1fe932f485) | Jul 15, 2023 |
| Gateway       | SX2185                      | [00e7bb0f9f](https://linux-hardware.org/?probe=00e7bb0f9f) | Jul 15, 2023 |
| ASRock        | X670E Steel Legend          | [f25464fb37](https://linux-hardware.org/?probe=f25464fb37) | Jul 15, 2023 |
| ASUSTek       | A88XM-A                     | [c58d69659f](https://linux-hardware.org/?probe=c58d69659f) | Jul 14, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [4e78c933e4](https://linux-hardware.org/?probe=4e78c933e4) | Jul 14, 2023 |
| ASUSTek       | A88XM-A                     | [e34b3f4c71](https://linux-hardware.org/?probe=e34b3f4c71) | Jul 14, 2023 |
| ASUSTek       | PRIME B365M-A               | [62099e9da7](https://linux-hardware.org/?probe=62099e9da7) | Jul 14, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [065aed3358](https://linux-hardware.org/?probe=065aed3358) | Jul 14, 2023 |
| ASUSTek       | PRIME B550M-A AC            | [ed49c9c5e0](https://linux-hardware.org/?probe=ed49c9c5e0) | Jul 14, 2023 |
| ASUSTek       | X99-DELUXE II               | [d132761a85](https://linux-hardware.org/?probe=d132761a85) | Jul 14, 2023 |
| ASUSTek       | X99-DELUXE II               | [70345fff08](https://linux-hardware.org/?probe=70345fff08) | Jul 14, 2023 |
| MSI           | MPG Z690 EDGE WIFI DDR4     | [96921926b1](https://linux-hardware.org/?probe=96921926b1) | Jul 14, 2023 |
| Gigabyte      | H77N-WIFI                   | [8ee665fb8f](https://linux-hardware.org/?probe=8ee665fb8f) | Jul 14, 2023 |
| GALAX         | A320M G10g                  | [730e46d4f0](https://linux-hardware.org/?probe=730e46d4f0) | Jul 14, 2023 |
| Gigabyte      | P75-D3P                     | [0a7c65caae](https://linux-hardware.org/?probe=0a7c65caae) | Jul 13, 2023 |
| ASUSTek       | PRIME X570-P                | [ab0a96405e](https://linux-hardware.org/?probe=ab0a96405e) | Jul 13, 2023 |
| Gigabyte      | GA-A55M-S2V                 | [fadd5eeba6](https://linux-hardware.org/?probe=fadd5eeba6) | Jul 13, 2023 |
| Dell          | 0GY6Y8 A01                  | [144711a0e0](https://linux-hardware.org/?probe=144711a0e0) | Jul 13, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [cd3de89b97](https://linux-hardware.org/?probe=cd3de89b97) | Jul 12, 2023 |
| MSI           | MAG B550M BAZOOKA           | [4271ad9e9b](https://linux-hardware.org/?probe=4271ad9e9b) | Jul 12, 2023 |
| MSI           | 970A-G46                    | [09496b3221](https://linux-hardware.org/?probe=09496b3221) | Jul 12, 2023 |
| MSI           | A320M PRO-VH PLUS           | [e99992afd5](https://linux-hardware.org/?probe=e99992afd5) | Jul 12, 2023 |
| ASRock        | B550M Pro4                  | [18a8fc202c](https://linux-hardware.org/?probe=18a8fc202c) | Jul 12, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [30d6b8bfde](https://linux-hardware.org/?probe=30d6b8bfde) | Jul 11, 2023 |
| MSI           | B350M MORTAR                | [069cf3a06d](https://linux-hardware.org/?probe=069cf3a06d) | Jul 11, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [5c12592f23](https://linux-hardware.org/?probe=5c12592f23) | Jul 11, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [2b544082c2](https://linux-hardware.org/?probe=2b544082c2) | Jul 11, 2023 |
| Gigabyte      | J1900M-D2P                  | [a9e19d3887](https://linux-hardware.org/?probe=a9e19d3887) | Jul 11, 2023 |
| Pegatron      | IPMH61P1                    | [9aa934f232](https://linux-hardware.org/?probe=9aa934f232) | Jul 11, 2023 |
| ASUSTek       | PRIME B250M-D               | [304630d909](https://linux-hardware.org/?probe=304630d909) | Jul 11, 2023 |
| Gigabyte      | B75M-D2V                    | [2749c7cf78](https://linux-hardware.org/?probe=2749c7cf78) | Jul 11, 2023 |
| Pegatron      | 2AD5                        | [04c6c9ba2b](https://linux-hardware.org/?probe=04c6c9ba2b) | Jul 10, 2023 |
| ASUSTek       | PRIME X470-PRO              | [eca6eabcb2](https://linux-hardware.org/?probe=eca6eabcb2) | Jul 10, 2023 |
| Gigabyte      | Z77MX-D3H                   | [ac8df9628d](https://linux-hardware.org/?probe=ac8df9628d) | Jul 10, 2023 |
| MSI           | MEG Z390 GODLIKE            | [b904121800](https://linux-hardware.org/?probe=b904121800) | Jul 10, 2023 |
| MSI           | MPG B650I EDGE WIFI         | [dcf418007d](https://linux-hardware.org/?probe=dcf418007d) | Jul 10, 2023 |
| MSI           | MPG B650I EDGE WIFI         | [b515a2980e](https://linux-hardware.org/?probe=b515a2980e) | Jul 10, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [a2f3950062](https://linux-hardware.org/?probe=a2f3950062) | Jul 10, 2023 |
| GALAX         | A320M G10g                  | [8ab8387585](https://linux-hardware.org/?probe=8ab8387585) | Jul 10, 2023 |
| MSI           | B450M-A PRO MAX             | [ceccedafbd](https://linux-hardware.org/?probe=ceccedafbd) | Jul 10, 2023 |
| ASUSTek       | PHOENIX                     | [88c02f40e7](https://linux-hardware.org/?probe=88c02f40e7) | Jul 09, 2023 |
| Gigabyte      | B365M DS3H WIFI             | [150b2a2675](https://linux-hardware.org/?probe=150b2a2675) | Jul 09, 2023 |
| Gigabyte      | B365M DS3H WIFI             | [a887a01dd7](https://linux-hardware.org/?probe=a887a01dd7) | Jul 09, 2023 |
| ASUSTek       | PRIME H310M-K               | [e7c0c87a14](https://linux-hardware.org/?probe=e7c0c87a14) | Jul 09, 2023 |
| Lenovo        | SHARKBAY NOK                | [fbeae7b57e](https://linux-hardware.org/?probe=fbeae7b57e) | Jul 09, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [d9880a123f](https://linux-hardware.org/?probe=d9880a123f) | Jul 09, 2023 |
| MSI           | PRO B650-P WIFI             | [7d98a62bcc](https://linux-hardware.org/?probe=7d98a62bcc) | Jul 09, 2023 |
| MSI           | B250M PRO-VD                | [f9c2ea463a](https://linux-hardware.org/?probe=f9c2ea463a) | Jul 09, 2023 |
| Dell          | 00F82W A00                  | [603d370b5c](https://linux-hardware.org/?probe=603d370b5c) | Jul 09, 2023 |
| MSI           | Z97 GUARD-PRO               | [298da90a40](https://linux-hardware.org/?probe=298da90a40) | Jul 09, 2023 |
| MSI           | PRO Z690-A DDR4             | [f8aa10b5cb](https://linux-hardware.org/?probe=f8aa10b5cb) | Jul 08, 2023 |
| MSI           | PRO Z690-A DDR4             | [1027217195](https://linux-hardware.org/?probe=1027217195) | Jul 08, 2023 |
| ECS           | P43T-AD3                    | [bdbd07c719](https://linux-hardware.org/?probe=bdbd07c719) | Jul 08, 2023 |
| GALAX         | A320M G10g                  | [21dab37c75](https://linux-hardware.org/?probe=21dab37c75) | Jul 08, 2023 |
| HP            | 0AECh D                     | [c3d2867e48](https://linux-hardware.org/?probe=c3d2867e48) | Jul 08, 2023 |
| ASRock        | X670E Pro RS                | [d41838c540](https://linux-hardware.org/?probe=d41838c540) | Jul 08, 2023 |
| Gigabyte      | GA-A55M-S2V                 | [6cac69cac1](https://linux-hardware.org/?probe=6cac69cac1) | Jul 08, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [4bcab5adb1](https://linux-hardware.org/?probe=4bcab5adb1) | Jul 08, 2023 |
| MSI           | MPG B650I EDGE WIFI         | [bdaa09e52c](https://linux-hardware.org/?probe=bdaa09e52c) | Jul 08, 2023 |
| ASUSTek       | PRIME B550M-A               | [09c80a40ac](https://linux-hardware.org/?probe=09c80a40ac) | Jul 07, 2023 |
| ASUSTek       | PHOENIX                     | [f12b531ae3](https://linux-hardware.org/?probe=f12b531ae3) | Jul 07, 2023 |
| Gigabyte      | H170-HD3-CF                 | [f2203ae88e](https://linux-hardware.org/?probe=f2203ae88e) | Jul 07, 2023 |
| Gigabyte      | H170-HD3-CF                 | [e2adf09ecf](https://linux-hardware.org/?probe=e2adf09ecf) | Jul 07, 2023 |
| ASUSTek       | PHOENIX                     | [cc54a5a0bf](https://linux-hardware.org/?probe=cc54a5a0bf) | Jul 07, 2023 |
| HP            | 3397                        | [45bc734b0b](https://linux-hardware.org/?probe=45bc734b0b) | Jul 07, 2023 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | [bdf5ce2163](https://linux-hardware.org/?probe=bdf5ce2163) | Jul 07, 2023 |
| ASRock        | Z370 Professional Gaming... | [9101223f5e](https://linux-hardware.org/?probe=9101223f5e) | Jul 07, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | [2eb6b1bb05](https://linux-hardware.org/?probe=2eb6b1bb05) | Jul 07, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [4068c56cd3](https://linux-hardware.org/?probe=4068c56cd3) | Jul 07, 2023 |
| Gigabyte      | X570 AORUS PRO              | [2802b7951e](https://linux-hardware.org/?probe=2802b7951e) | Jul 06, 2023 |
| MSI           | MS-7142                     | [3247a2f71c](https://linux-hardware.org/?probe=3247a2f71c) | Jul 06, 2023 |
| MSI           | H510M PRO-E                 | [598f789eb0](https://linux-hardware.org/?probe=598f789eb0) | Jul 06, 2023 |
| Gigabyte      | X399 AORUS PRO-CF           | [4122f6e73c](https://linux-hardware.org/?probe=4122f6e73c) | Jul 06, 2023 |
| HP            | 82FE 11                     | [fcac934bde](https://linux-hardware.org/?probe=fcac934bde) | Jul 06, 2023 |
| AZW           | U59                         | [0b59408438](https://linux-hardware.org/?probe=0b59408438) | Jul 06, 2023 |
| MSI           | B150 GAMING M3              | [a8018be55a](https://linux-hardware.org/?probe=a8018be55a) | Jul 06, 2023 |
| Dell          | 06D7TR A00                  | [27f1fe9389](https://linux-hardware.org/?probe=27f1fe9389) | Jul 06, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | [3af1e33a01](https://linux-hardware.org/?probe=3af1e33a01) | Jul 06, 2023 |
| Gigabyte      | Z87X-UD5H-CF                | [ed520a330d](https://linux-hardware.org/?probe=ed520a330d) | Jul 06, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | [a98b1d131d](https://linux-hardware.org/?probe=a98b1d131d) | Jul 06, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | [eb913300f2](https://linux-hardware.org/?probe=eb913300f2) | Jul 06, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [dd020d65e5](https://linux-hardware.org/?probe=dd020d65e5) | Jul 05, 2023 |
| Gigabyte      | B660M DS3H DDR4             | [c997aced4e](https://linux-hardware.org/?probe=c997aced4e) | Jul 05, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [06b0f38502](https://linux-hardware.org/?probe=06b0f38502) | Jul 05, 2023 |
| ASUSTek       | PRIME H310M-K               | [65cc87f2f0](https://linux-hardware.org/?probe=65cc87f2f0) | Jul 05, 2023 |
| Shenzhen M... | F7BFC                       | [bb708e03aa](https://linux-hardware.org/?probe=bb708e03aa) | Jul 05, 2023 |
| ASUSTek       | CROSSBLADE RANGER           | [d816bd723e](https://linux-hardware.org/?probe=d816bd723e) | Jul 05, 2023 |
| Lenovo        | 30D0 SDK0J40700 WIN 3258... | [2bb5ca7ea2](https://linux-hardware.org/?probe=2bb5ca7ea2) | Jul 05, 2023 |
| Gigabyte      | P85-D3                      | [6b4a40a1db](https://linux-hardware.org/?probe=6b4a40a1db) | Jul 04, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [fea629b2e8](https://linux-hardware.org/?probe=fea629b2e8) | Jul 04, 2023 |
| HP            | 212B                        | [5c022be621](https://linux-hardware.org/?probe=5c022be621) | Jul 04, 2023 |
| Gigabyte      | G41MT-D3                    | [da0ca66579](https://linux-hardware.org/?probe=da0ca66579) | Jul 04, 2023 |
| ASUSTek       | H110M-E/M.2                 | [234c36d2ba](https://linux-hardware.org/?probe=234c36d2ba) | Jul 04, 2023 |
| MSI           | PRO Z690-A DDR4             | [d36574de10](https://linux-hardware.org/?probe=d36574de10) | Jul 03, 2023 |
| Kupi deshe... | X99Z-V102 Date 27052020     | [0cdbbfe5b3](https://linux-hardware.org/?probe=0cdbbfe5b3) | Jul 03, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [293008463e](https://linux-hardware.org/?probe=293008463e) | Jul 03, 2023 |
| HP            | 861A                        | [0531675f82](https://linux-hardware.org/?probe=0531675f82) | Jul 03, 2023 |
| ASUSTek       | PRIME B550M-A               | [dc77810d67](https://linux-hardware.org/?probe=dc77810d67) | Jul 03, 2023 |
| MSI           | A320M PRO-VH PLUS           | [a7c8848746](https://linux-hardware.org/?probe=a7c8848746) | Jul 03, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [bdbf0fa0c3](https://linux-hardware.org/?probe=bdbf0fa0c3) | Jul 03, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [590efa4873](https://linux-hardware.org/?probe=590efa4873) | Jul 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [a6ceaae01b](https://linux-hardware.org/?probe=a6ceaae01b) | Jul 02, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [69c34bf001](https://linux-hardware.org/?probe=69c34bf001) | Jul 02, 2023 |
| ASUSTek       | X99-M WS                    | [4f9ad96681](https://linux-hardware.org/?probe=4f9ad96681) | Jul 02, 2023 |
| AZW           | MINI S                      | [fb96f8d7bf](https://linux-hardware.org/?probe=fb96f8d7bf) | Jul 02, 2023 |
| ASUSTek       | PRIME B550M-A               | [740a0dad30](https://linux-hardware.org/?probe=740a0dad30) | Jul 02, 2023 |
| Gigabyte      | X570 AORUS PRO              | [0a9e5c0979](https://linux-hardware.org/?probe=0a9e5c0979) | Jul 02, 2023 |
| Gigabyte      | A320M-S2H-CF                | [d0ab54293f](https://linux-hardware.org/?probe=d0ab54293f) | Jul 02, 2023 |
| ASRock        | B560M-ITX/ac                | [4c5f8f3d95](https://linux-hardware.org/?probe=4c5f8f3d95) | Jul 01, 2023 |
| ASRock        | A620M Pro RS WiFi           | [f771aedc9c](https://linux-hardware.org/?probe=f771aedc9c) | Jul 01, 2023 |
| HP            | 8061                        | [429534fab2](https://linux-hardware.org/?probe=429534fab2) | Jul 01, 2023 |
| HP            | 8054                        | [30c45def21](https://linux-hardware.org/?probe=30c45def21) | Jul 01, 2023 |
| HP            | 8054                        | [edf94b1f66](https://linux-hardware.org/?probe=edf94b1f66) | Jul 01, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | [6c1829f43d](https://linux-hardware.org/?probe=6c1829f43d) | Jul 01, 2023 |
| ASUSTek       | PRIME B550M-A               | [246d688f1c](https://linux-hardware.org/?probe=246d688f1c) | Jul 01, 2023 |
| MSI           | MPG Z390M GAMING EDGE AC    | [cfdff3114c](https://linux-hardware.org/?probe=cfdff3114c) | Jul 01, 2023 |
| Gigabyte      | H410M S2H V3                | [e539937c27](https://linux-hardware.org/?probe=e539937c27) | Jun 30, 2023 |
| Acer          | Predator PO5-640            | [416b01c954](https://linux-hardware.org/?probe=416b01c954) | Jun 30, 2023 |
| Gigabyte      | Z87X-UD5H-CF                | [3749bda51b](https://linux-hardware.org/?probe=3749bda51b) | Jun 30, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [3c3556dd33](https://linux-hardware.org/?probe=3c3556dd33) | Jun 30, 2023 |
| Gigabyte      | Z87X-UD5H-CF                | [6ee8476c0e](https://linux-hardware.org/?probe=6ee8476c0e) | Jun 30, 2023 |
| AZW           | MINI S 10                   | [84eec8c276](https://linux-hardware.org/?probe=84eec8c276) | Jun 29, 2023 |
| AZW           | MINI S 10                   | [d1795fbf64](https://linux-hardware.org/?probe=d1795fbf64) | Jun 29, 2023 |
| Gigabyte      | H310M H                     | [0ad496c06d](https://linux-hardware.org/?probe=0ad496c06d) | Jun 29, 2023 |
| Gigabyte      | H410M H V3                  | [5496b9130e](https://linux-hardware.org/?probe=5496b9130e) | Jun 29, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [95fb20193a](https://linux-hardware.org/?probe=95fb20193a) | Jun 29, 2023 |
| ASUSTek       | PRIME B550M-A               | [5bb4af3f8b](https://linux-hardware.org/?probe=5bb4af3f8b) | Jun 29, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | [3f9d0da410](https://linux-hardware.org/?probe=3f9d0da410) | Jun 28, 2023 |
| Gigabyte      | B560M DS3H V2               | [aa24aa071b](https://linux-hardware.org/?probe=aa24aa071b) | Jun 28, 2023 |
| MSI           | 880GM-E41                   | [91a2474332](https://linux-hardware.org/?probe=91a2474332) | Jun 28, 2023 |
| Fill By OE... | Q7700                       | [93c7c01ecb](https://linux-hardware.org/?probe=93c7c01ecb) | Jun 28, 2023 |
| ASRock        | H510M-HVS                   | [b90f532588](https://linux-hardware.org/?probe=b90f532588) | Jun 28, 2023 |
| HP            | 802F                        | [585f9bf338](https://linux-hardware.org/?probe=585f9bf338) | Jun 27, 2023 |
| HP            | 802F                        | [efceba0028](https://linux-hardware.org/?probe=efceba0028) | Jun 27, 2023 |
| Intel         | LADPNVMO AAE76523-300       | [76cc7bbb86](https://linux-hardware.org/?probe=76cc7bbb86) | Jun 27, 2023 |
| Fill By OE... | Q7700                       | [32ac9cb839](https://linux-hardware.org/?probe=32ac9cb839) | Jun 27, 2023 |
| Dell          | 0R6PCT A01                  | [2fd7aa28db](https://linux-hardware.org/?probe=2fd7aa28db) | Jun 27, 2023 |
| Gigabyte      | B450M DS3H-CF               | [b21d5b2e0a](https://linux-hardware.org/?probe=b21d5b2e0a) | Jun 26, 2023 |
| Gigabyte      | MZBAYAB-00                  | [a44397603c](https://linux-hardware.org/?probe=a44397603c) | Jun 26, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [3486e43434](https://linux-hardware.org/?probe=3486e43434) | Jun 25, 2023 |
| Gigabyte      | H110M-H-CF                  | [7baa53c127](https://linux-hardware.org/?probe=7baa53c127) | Jun 25, 2023 |
| ASUSTek       | P9X79 PRO                   | [3d1eeda7fa](https://linux-hardware.org/?probe=3d1eeda7fa) | Jun 24, 2023 |
| Dell          | 088DT1 A01                  | [755d1f8c03](https://linux-hardware.org/?probe=755d1f8c03) | Jun 24, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [1c0d2d86f3](https://linux-hardware.org/?probe=1c0d2d86f3) | Jun 24, 2023 |
| ASUSTek       | P8Z77-V LK                  | [bcfc1fe2de](https://linux-hardware.org/?probe=bcfc1fe2de) | Jun 23, 2023 |
| ASRock        | B450 Pro4                   | [a5f281a10e](https://linux-hardware.org/?probe=a5f281a10e) | Jun 23, 2023 |
| ASUSTek       | M4A77                       | [67e6b51c63](https://linux-hardware.org/?probe=67e6b51c63) | Jun 23, 2023 |
| MSI           | B450M PRO-M2 V2             | [af46eedb6f](https://linux-hardware.org/?probe=af46eedb6f) | Jun 23, 2023 |
| ASUSTek       | PRIME B350M-A               | [efb0264470](https://linux-hardware.org/?probe=efb0264470) | Jun 23, 2023 |
| ASUSTek       | Maximus VIII RANGER Modi... | [d24120bc4e](https://linux-hardware.org/?probe=d24120bc4e) | Jun 22, 2023 |
| MSI           | PRO B550M-VC WIFI           | [c9f86c15b7](https://linux-hardware.org/?probe=c9f86c15b7) | Jun 22, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [52bcb712ec](https://linux-hardware.org/?probe=52bcb712ec) | Jun 22, 2023 |
| Lenovo        | SHARKBAY NOK                | [c0f250b2f9](https://linux-hardware.org/?probe=c0f250b2f9) | Jun 22, 2023 |
| Unknown       | Unknown                     | [172c84a53d](https://linux-hardware.org/?probe=172c84a53d) | Jun 22, 2023 |
| Dell          | 09KPNV A01                  | [eaa3017d03](https://linux-hardware.org/?probe=eaa3017d03) | Jun 21, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [30f85c0f2e](https://linux-hardware.org/?probe=30f85c0f2e) | Jun 21, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [fd367d0725](https://linux-hardware.org/?probe=fd367d0725) | Jun 21, 2023 |
| ASUSTek       | PRIME B550M-A               | [a5e833c54e](https://linux-hardware.org/?probe=a5e833c54e) | Jun 21, 2023 |
| ASUSTek       | Z87-A                       | [ca84827c75](https://linux-hardware.org/?probe=ca84827c75) | Jun 21, 2023 |
| ASUSTek       | Z87-A                       | [a30c01fab8](https://linux-hardware.org/?probe=a30c01fab8) | Jun 21, 2023 |
| ASUSTek       | TUF B360-PRO GAMING WIFI    | [52e2d1b77a](https://linux-hardware.org/?probe=52e2d1b77a) | Jun 21, 2023 |
| Pegatron      | IPMIP-H55-INSPUR            | [176a1c3e01](https://linux-hardware.org/?probe=176a1c3e01) | Jun 21, 2023 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [a1e0b61e89](https://linux-hardware.org/?probe=a1e0b61e89) | Jun 20, 2023 |
| MSI           | X570-A PRO                  | [b968cb073e](https://linux-hardware.org/?probe=b968cb073e) | Jun 20, 2023 |
| ASUSTek       | Rampage V EXTREME           | [e7bb42d6d4](https://linux-hardware.org/?probe=e7bb42d6d4) | Jun 20, 2023 |
| ASUSTek       | Rampage V EXTREME           | [2fe4bf8ad2](https://linux-hardware.org/?probe=2fe4bf8ad2) | Jun 20, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [b154e92f35](https://linux-hardware.org/?probe=b154e92f35) | Jun 20, 2023 |
| MSI           | B75MA-P45                   | [2d8b92b0e6](https://linux-hardware.org/?probe=2d8b92b0e6) | Jun 20, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [ee8a4e18c4](https://linux-hardware.org/?probe=ee8a4e18c4) | Jun 20, 2023 |
| Itautec       | ST 4265 ST-4265 Padrao 0... | [689b10e4be](https://linux-hardware.org/?probe=689b10e4be) | Jun 19, 2023 |
| Gigabyte      | B365M D2V                   | [e16cbf315f](https://linux-hardware.org/?probe=e16cbf315f) | Jun 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [b3e34f06a4](https://linux-hardware.org/?probe=b3e34f06a4) | Jun 19, 2023 |
| Gigabyte      | GA-MA785G-UD3H              | [e5740353af](https://linux-hardware.org/?probe=e5740353af) | Jun 19, 2023 |
| Dell          | 0C2XKD A01                  | [15331b91ed](https://linux-hardware.org/?probe=15331b91ed) | Jun 18, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | [5ff46d41fd](https://linux-hardware.org/?probe=5ff46d41fd) | Jun 18, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [924b6e8d54](https://linux-hardware.org/?probe=924b6e8d54) | Jun 18, 2023 |
| Lenovo        | SHARKBAY NOK                | [73a438e6b8](https://linux-hardware.org/?probe=73a438e6b8) | Jun 18, 2023 |
| MSI           | X470 GAMING PLUS            | [17c61c0aee](https://linux-hardware.org/?probe=17c61c0aee) | Jun 18, 2023 |
| Gigabyte      | GA-880GM-UD2H               | [fdbe50b1d6](https://linux-hardware.org/?probe=fdbe50b1d6) | Jun 18, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [231a3aeb2e](https://linux-hardware.org/?probe=231a3aeb2e) | Jun 18, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [cd87a6b19f](https://linux-hardware.org/?probe=cd87a6b19f) | Jun 17, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [ae4661e26f](https://linux-hardware.org/?probe=ae4661e26f) | Jun 17, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E EXTR... | [c555238190](https://linux-hardware.org/?probe=c555238190) | Jun 17, 2023 |
| ASUSTek       | PRIME B550M-A               | [7e135be518](https://linux-hardware.org/?probe=7e135be518) | Jun 17, 2023 |
| ASUSTek       | ROG ZENITH EXTREME          | [5dc49896e5](https://linux-hardware.org/?probe=5dc49896e5) | Jun 16, 2023 |
| MSI           | B85-G43 GAMING              | [93da970965](https://linux-hardware.org/?probe=93da970965) | Jun 16, 2023 |
| MSI           | B450 GAMING PLUS            | [8a480175f8](https://linux-hardware.org/?probe=8a480175f8) | Jun 16, 2023 |
| ASUSTek       | ROG STRIX B550-XE GAMING... | [84b103464e](https://linux-hardware.org/?probe=84b103464e) | Jun 16, 2023 |
| MSI           | B450M MORTAR TITANIUM       | [3b83e2ea48](https://linux-hardware.org/?probe=3b83e2ea48) | Jun 16, 2023 |
| MSI           | B450 GAMING PLUS            | [8a3d74a5fa](https://linux-hardware.org/?probe=8a3d74a5fa) | Jun 16, 2023 |
| ASRock        | X399 Phantom Gaming 6       | [aad3ead710](https://linux-hardware.org/?probe=aad3ead710) | Jun 16, 2023 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | [9c3bb21706](https://linux-hardware.org/?probe=9c3bb21706) | Jun 16, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | [29ff056f4a](https://linux-hardware.org/?probe=29ff056f4a) | Jun 16, 2023 |
| MSI           | Z170A GAMING M5             | [a0d460b4a3](https://linux-hardware.org/?probe=a0d460b4a3) | Jun 16, 2023 |
| Gigabyte      | H97-HD3                     | [24a487274f](https://linux-hardware.org/?probe=24a487274f) | Jun 16, 2023 |
| MSI           | MAG B550M MORTAR            | [9604c6211e](https://linux-hardware.org/?probe=9604c6211e) | Jun 15, 2023 |
| Itautec       | ST 4265 ST-4265 Padrao 0... | [ecc8c7d2d0](https://linux-hardware.org/?probe=ecc8c7d2d0) | Jun 15, 2023 |
| Itautec       | ST 4265 ST-4265 Padrao 0... | [4cad282848](https://linux-hardware.org/?probe=4cad282848) | Jun 15, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [5a1e944af2](https://linux-hardware.org/?probe=5a1e944af2) | Jun 15, 2023 |
| MSI           | PRO B550M-VC WIFI           | [64e0ce279b](https://linux-hardware.org/?probe=64e0ce279b) | Jun 15, 2023 |
| Gigabyte      | B85M-D3V-A                  | [bbcb31d079](https://linux-hardware.org/?probe=bbcb31d079) | Jun 14, 2023 |
| ASUSTek       | P5G41C-M LX                 | [7ae654d4e2](https://linux-hardware.org/?probe=7ae654d4e2) | Jun 14, 2023 |
| Kllisre       | X99-B5 V1.1                 | [5e22a31b3e](https://linux-hardware.org/?probe=5e22a31b3e) | Jun 14, 2023 |
| Gigabyte      | D525TUD                     | [2d854be38a](https://linux-hardware.org/?probe=2d854be38a) | Jun 14, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [ddb9fc5a43](https://linux-hardware.org/?probe=ddb9fc5a43) | Jun 14, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [4fac659113](https://linux-hardware.org/?probe=4fac659113) | Jun 13, 2023 |
| MSI           | H510M PRO                   | [08e44766fe](https://linux-hardware.org/?probe=08e44766fe) | Jun 13, 2023 |
| MSI           | IONA                        | [86535af79b](https://linux-hardware.org/?probe=86535af79b) | Jun 13, 2023 |
| MSI           | Z77A-G45                    | [db1a941e2c](https://linux-hardware.org/?probe=db1a941e2c) | Jun 13, 2023 |
| Gigabyte      | A520M DS3H                  | [0f5b161a60](https://linux-hardware.org/?probe=0f5b161a60) | Jun 13, 2023 |
| ASUSTek       | P5G41C-M LX                 | [1361d3551c](https://linux-hardware.org/?probe=1361d3551c) | Jun 12, 2023 |
| Gigabyte      | B560M DS3H V2               | [1b8ad811e0](https://linux-hardware.org/?probe=1b8ad811e0) | Jun 12, 2023 |
| ASRock        | Z390 Pro4                   | [067d0e5da5](https://linux-hardware.org/?probe=067d0e5da5) | Jun 12, 2023 |
| Shenzhen M... | F7BFD                       | [8f43ad0e76](https://linux-hardware.org/?probe=8f43ad0e76) | Jun 12, 2023 |
| ASUSTek       | PRIME H310M-K               | [f1614bb08f](https://linux-hardware.org/?probe=f1614bb08f) | Jun 11, 2023 |
| ASUSTek       | PRIME Z270-P                | [57fcd66521](https://linux-hardware.org/?probe=57fcd66521) | Jun 11, 2023 |
| MSI           | PRO Z790-A WIFI DDR4        | [0e3bbb5b14](https://linux-hardware.org/?probe=0e3bbb5b14) | Jun 11, 2023 |
| MSI           | PRO B660M-A DDR4            | [e3311e26b6](https://linux-hardware.org/?probe=e3311e26b6) | Jun 11, 2023 |
| Gigabyte      | Z87X-UD4H-CF                | [abd31d2f92](https://linux-hardware.org/?probe=abd31d2f92) | Jun 10, 2023 |
| Lenovo        | 32E9 SDK0T76465 WIN 3422... | [2ac8db1b4c](https://linux-hardware.org/?probe=2ac8db1b4c) | Jun 10, 2023 |
| Dell          | 0N4YC8 A00                  | [bc832400b4](https://linux-hardware.org/?probe=bc832400b4) | Jun 10, 2023 |
| MSI           | MS-7388                     | [6d3a406400](https://linux-hardware.org/?probe=6d3a406400) | Jun 10, 2023 |
| HP            | 339B                        | [bc6de07e07](https://linux-hardware.org/?probe=bc6de07e07) | Jun 09, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | [f02bc23dd0](https://linux-hardware.org/?probe=f02bc23dd0) | Jun 09, 2023 |
| ASRock        | AB350M Pro4                 | [8f0087d741](https://linux-hardware.org/?probe=8f0087d741) | Jun 09, 2023 |
| MSI           | 760GM-P23                   | [abc3a3d8a1](https://linux-hardware.org/?probe=abc3a3d8a1) | Jun 09, 2023 |
| MSI           | 760GM-P23                   | [fc826b3cb1](https://linux-hardware.org/?probe=fc826b3cb1) | Jun 09, 2023 |
| ASUSTek       | STRIX B250F GAMING          | [c0fd33b9cc](https://linux-hardware.org/?probe=c0fd33b9cc) | Jun 09, 2023 |
| ASUSTek       | STRIX B250F GAMING          | [76c3e6625b](https://linux-hardware.org/?probe=76c3e6625b) | Jun 09, 2023 |
| Dell          | 0FDY5C A00                  | [1caf029f79](https://linux-hardware.org/?probe=1caf029f79) | Jun 09, 2023 |
| ASRock        | A320M-HD                    | [9e88454384](https://linux-hardware.org/?probe=9e88454384) | Jun 09, 2023 |
| ASUSTek       | Z97M-PLUS                   | [24f6f6e727](https://linux-hardware.org/?probe=24f6f6e727) | Jun 08, 2023 |
| ASUSTek       | Z97M-PLUS                   | [8d4e2bedde](https://linux-hardware.org/?probe=8d4e2bedde) | Jun 08, 2023 |
| Colorful T... | A520M-K PRO V14             | [48c4aa3d8c](https://linux-hardware.org/?probe=48c4aa3d8c) | Jun 08, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [b9e1c5e320](https://linux-hardware.org/?probe=b9e1c5e320) | Jun 08, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [bf2fc7d3b7](https://linux-hardware.org/?probe=bf2fc7d3b7) | Jun 08, 2023 |
| MSI           | B450M PRO-VDH MAX           | [c96be9f4cd](https://linux-hardware.org/?probe=c96be9f4cd) | Jun 08, 2023 |
| Gigabyte      | B75M-D3H                    | [65e06561cf](https://linux-hardware.org/?probe=65e06561cf) | Jun 08, 2023 |
| Gigabyte      | Z77MX-D3H                   | [e1fdfde650](https://linux-hardware.org/?probe=e1fdfde650) | Jun 08, 2023 |
| HPE           | ProLiant MicroServer Gen... | [e95900bc0c](https://linux-hardware.org/?probe=e95900bc0c) | Jun 08, 2023 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [74f55613b5](https://linux-hardware.org/?probe=74f55613b5) | Jun 08, 2023 |
| Gigabyte      | Z390 GAMING SLI-CF          | [5f0e8ab63a](https://linux-hardware.org/?probe=5f0e8ab63a) | Jun 07, 2023 |
| Gigabyte      | Z87X-UD5H-CF                | [fd156e669f](https://linux-hardware.org/?probe=fd156e669f) | Jun 07, 2023 |
| Lenovo        | SHARKBAY NOK                | [cf560e91e7](https://linux-hardware.org/?probe=cf560e91e7) | Jun 07, 2023 |
| HP            | 339B                        | [a1739aa36b](https://linux-hardware.org/?probe=a1739aa36b) | Jun 07, 2023 |
| Gigabyte      | H77N-WIFI                   | [1c8078b748](https://linux-hardware.org/?probe=1c8078b748) | Jun 07, 2023 |
| Gigabyte      | B550 VISION D               | [94cf7f5675](https://linux-hardware.org/?probe=94cf7f5675) | Jun 07, 2023 |
| MSI           | B350M GAMING PRO            | [eb3fbddd2c](https://linux-hardware.org/?probe=eb3fbddd2c) | Jun 06, 2023 |
| Gigabyte      | B250-FinTech-CF             | [022138ad16](https://linux-hardware.org/?probe=022138ad16) | Jun 06, 2023 |
| Dell          | 0427JK A00                  | [addb15771e](https://linux-hardware.org/?probe=addb15771e) | Jun 06, 2023 |
| Dell          | 0NW6H5 A00                  | [631e6bba84](https://linux-hardware.org/?probe=631e6bba84) | Jun 06, 2023 |
| Dell          | 06X1TJ A00                  | [c3f02841f4](https://linux-hardware.org/?probe=c3f02841f4) | Jun 06, 2023 |
| Dell          | 06X1TJ A00                  | [4cec4f0517](https://linux-hardware.org/?probe=4cec4f0517) | Jun 06, 2023 |
| HP            | 83E1                        | [227e410c6f](https://linux-hardware.org/?probe=227e410c6f) | Jun 06, 2023 |
| Lenovo        | 30D0 NOK                    | [045b011b7a](https://linux-hardware.org/?probe=045b011b7a) | Jun 06, 2023 |
| HP            | 8918                        | [917b8c425f](https://linux-hardware.org/?probe=917b8c425f) | Jun 06, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [91ee57c108](https://linux-hardware.org/?probe=91ee57c108) | Jun 05, 2023 |
| Gigabyte      | B250-FinTech-CF             | [e22c496628](https://linux-hardware.org/?probe=e22c496628) | Jun 05, 2023 |
| Unknown       | Unknown                     | [292269611c](https://linux-hardware.org/?probe=292269611c) | Jun 05, 2023 |
| MSI           | B360M PRO-VH                | [8e4ad66edc](https://linux-hardware.org/?probe=8e4ad66edc) | Jun 05, 2023 |
| ASUSTek       | PRIME B350M-A               | [3a0576b177](https://linux-hardware.org/?probe=3a0576b177) | Jun 05, 2023 |
| ASUSTek       | PRIME B550M-A               | [d6befa925e](https://linux-hardware.org/?probe=d6befa925e) | Jun 04, 2023 |
| Dell          | 09D7F7 A00                  | [9b80703b01](https://linux-hardware.org/?probe=9b80703b01) | Jun 04, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [5b35735d26](https://linux-hardware.org/?probe=5b35735d26) | Jun 04, 2023 |
| MSI           | X470 GAMING PLUS            | [7af9263ba9](https://linux-hardware.org/?probe=7af9263ba9) | Jun 04, 2023 |
| MSI           | X470 GAMING PLUS            | [ae24cbf98d](https://linux-hardware.org/?probe=ae24cbf98d) | Jun 04, 2023 |
| Lenovo        | 32E9 SDK0T76465 WIN 3422... | [fa41f1f3c2](https://linux-hardware.org/?probe=fa41f1f3c2) | Jun 04, 2023 |
| Dell          | 0KRC95 A02                  | [3fb87e5a0e](https://linux-hardware.org/?probe=3fb87e5a0e) | Jun 03, 2023 |
| MSI           | A320M PRO-VH PLUS           | [8ba76b1e88](https://linux-hardware.org/?probe=8ba76b1e88) | Jun 03, 2023 |
| MSI           | MAG B550M MORTAR            | [3d911ac9c9](https://linux-hardware.org/?probe=3d911ac9c9) | Jun 03, 2023 |
| Gigabyte      | B650M GAMING X AX           | [610ba5871f](https://linux-hardware.org/?probe=610ba5871f) | Jun 03, 2023 |
| Gigabyte      | Z590 UD AC                  | [da5b2056e4](https://linux-hardware.org/?probe=da5b2056e4) | Jun 02, 2023 |
| ASUSTek       | P8Z77-V LK                  | [d50ca19dc3](https://linux-hardware.org/?probe=d50ca19dc3) | Jun 02, 2023 |
| Gigabyte      | B85-HD3                     | [9931f8e663](https://linux-hardware.org/?probe=9931f8e663) | Jun 02, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [5562bc75b8](https://linux-hardware.org/?probe=5562bc75b8) | Jun 02, 2023 |
| MSI           | PRO X670-P WIFI             | [714ed7283d](https://linux-hardware.org/?probe=714ed7283d) | Jun 02, 2023 |
| MSI           | PRO X670-P WIFI             | [bb2776b990](https://linux-hardware.org/?probe=bb2776b990) | Jun 02, 2023 |
| MSI           | MS-7388                     | [fc12ac6b90](https://linux-hardware.org/?probe=fc12ac6b90) | Jun 02, 2023 |
| Alienware     | 0N43JM A00                  | [047bfb6e8e](https://linux-hardware.org/?probe=047bfb6e8e) | Jun 02, 2023 |
| Dell          | 04Y8V0 A02                  | [ce749a8df5](https://linux-hardware.org/?probe=ce749a8df5) | Jun 02, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [def2c6020b](https://linux-hardware.org/?probe=def2c6020b) | Jun 01, 2023 |
| ASUSTek       | PRIME X570-P                | [cde4aaef3e](https://linux-hardware.org/?probe=cde4aaef3e) | Jun 01, 2023 |
| Itautec       | ST 4265 ST-4265 Padrao 0... | [7ac5ec7c05](https://linux-hardware.org/?probe=7ac5ec7c05) | Jun 01, 2023 |
| ASRock        | H310M-HDV                   | [3dc5138ecd](https://linux-hardware.org/?probe=3dc5138ecd) | Jun 01, 2023 |
| HP            | 845A                        | [b68054952b](https://linux-hardware.org/?probe=b68054952b) | Jun 01, 2023 |
| Lenovo        | SHARKBAY NOK                | [108cb2ce17](https://linux-hardware.org/?probe=108cb2ce17) | Jun 01, 2023 |
| HP            | 339A                        | [24ab8463bb](https://linux-hardware.org/?probe=24ab8463bb) | Jun 01, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [9afffc17a1](https://linux-hardware.org/?probe=9afffc17a1) | Jun 01, 2023 |
| ASUSTek       | PRIME B550M-A               | [8799da8513](https://linux-hardware.org/?probe=8799da8513) | Jun 01, 2023 |
| Gigabyte      | J1900M-D2P                  | [0e89db7255](https://linux-hardware.org/?probe=0e89db7255) | Jun 01, 2023 |
| ASUSTek       | PRIME H510M-K               | [f6f91b620c](https://linux-hardware.org/?probe=f6f91b620c) | May 31, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [3718997542](https://linux-hardware.org/?probe=3718997542) | May 31, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [ad79be40f5](https://linux-hardware.org/?probe=ad79be40f5) | May 31, 2023 |
| Gigabyte      | B250-FinTech-CF             | [1903d991a3](https://linux-hardware.org/?probe=1903d991a3) | May 30, 2023 |
| Shenzhen M... | F7BFC                       | [c496e8a74f](https://linux-hardware.org/?probe=c496e8a74f) | May 30, 2023 |
| ASUSTek       | PRIME B550M-A               | [349eb108ab](https://linux-hardware.org/?probe=349eb108ab) | May 30, 2023 |
| ASRock        | B450M Steel Legend          | [87c3dbc5df](https://linux-hardware.org/?probe=87c3dbc5df) | May 30, 2023 |
| ASRock        | A320M-DVS R4.0              | [611b47056d](https://linux-hardware.org/?probe=611b47056d) | May 30, 2023 |
| HP            | 8307                        | [c8d0506eda](https://linux-hardware.org/?probe=c8d0506eda) | May 30, 2023 |
| ASRock        | B560M-ITX/ac                | [e643aa0f5d](https://linux-hardware.org/?probe=e643aa0f5d) | May 30, 2023 |
| Itautec       | ST 4265                     | [8814373cb4](https://linux-hardware.org/?probe=8814373cb4) | May 29, 2023 |
| Lenovo        | SHARKBAY NOK                | [a199dc360d](https://linux-hardware.org/?probe=a199dc360d) | May 29, 2023 |
| MSI           | X370 XPOWER GAMING TITAN... | [3ecf79af69](https://linux-hardware.org/?probe=3ecf79af69) | May 29, 2023 |
| Itautec       | ST 4265                     | [b89c45a31d](https://linux-hardware.org/?probe=b89c45a31d) | May 29, 2023 |
| Gigabyte      | B550M DS3H AC               | [6dca0624e2](https://linux-hardware.org/?probe=6dca0624e2) | May 29, 2023 |
| HP            | 2820h                       | [d326b49f48](https://linux-hardware.org/?probe=d326b49f48) | May 29, 2023 |
| MSI           | B350M GAMING PRO            | [52517395ca](https://linux-hardware.org/?probe=52517395ca) | May 29, 2023 |
| ASUSTek       | PRIME H510M-K               | [0c7bfc7977](https://linux-hardware.org/?probe=0c7bfc7977) | May 28, 2023 |
| ASRock        | B550M Phantom Gaming 4      | [773f0d5242](https://linux-hardware.org/?probe=773f0d5242) | May 28, 2023 |
| Dell          | 0W2F8G A00                  | [f5a76aaf01](https://linux-hardware.org/?probe=f5a76aaf01) | May 28, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [4e1ad3c652](https://linux-hardware.org/?probe=4e1ad3c652) | May 28, 2023 |
| Dell          | 0W2F8G A00                  | [419c0c7359](https://linux-hardware.org/?probe=419c0c7359) | May 28, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [db3d362e28](https://linux-hardware.org/?probe=db3d362e28) | May 28, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [94fe283791](https://linux-hardware.org/?probe=94fe283791) | May 28, 2023 |
| Intel         | X99                         | [6826d78921](https://linux-hardware.org/?probe=6826d78921) | May 28, 2023 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | [906e585809](https://linux-hardware.org/?probe=906e585809) | May 27, 2023 |
| Huanan        | X79 249PC V2.2              | [0723379042](https://linux-hardware.org/?probe=0723379042) | May 27, 2023 |
| Huanan        | X79 249PC V2.2              | [ef1a056412](https://linux-hardware.org/?probe=ef1a056412) | May 27, 2023 |
| MSI           | X370 GAMING PRO CARBON A... | [ffbc308836](https://linux-hardware.org/?probe=ffbc308836) | May 27, 2023 |
| HP            | 8307                        | [94cad3911e](https://linux-hardware.org/?probe=94cad3911e) | May 27, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [9a3691f3f2](https://linux-hardware.org/?probe=9a3691f3f2) | May 27, 2023 |
| Gigabyte      | P75-D3P                     | [c341cbff1b](https://linux-hardware.org/?probe=c341cbff1b) | May 26, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [ecf6ecb00d](https://linux-hardware.org/?probe=ecf6ecb00d) | May 26, 2023 |
| ASUSTek       | PRIME B550M-A               | [424078f376](https://linux-hardware.org/?probe=424078f376) | May 26, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [16d7a61394](https://linux-hardware.org/?probe=16d7a61394) | May 26, 2023 |
| HP            | 0AECh D                     | [30868178ea](https://linux-hardware.org/?probe=30868178ea) | May 26, 2023 |
| Gigabyte      | J1900M-D2P                  | [f0c2fede02](https://linux-hardware.org/?probe=f0c2fede02) | May 25, 2023 |
| Gigabyte      | B560M AORUS ELITE           | [c2d85ba655](https://linux-hardware.org/?probe=c2d85ba655) | May 25, 2023 |
| Gigabyte      | J1900M-D2P                  | [a167562cba](https://linux-hardware.org/?probe=a167562cba) | May 25, 2023 |
| Foxconn       | 2ABF                        | [8472aba19b](https://linux-hardware.org/?probe=8472aba19b) | May 25, 2023 |
| ASUSTek       | PRIME Z390-P                | [909becff79](https://linux-hardware.org/?probe=909becff79) | May 24, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [d6ec4cc9bc](https://linux-hardware.org/?probe=d6ec4cc9bc) | May 24, 2023 |
| MSI           | 2A9C                        | [acaff65dda](https://linux-hardware.org/?probe=acaff65dda) | May 24, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [bcb5af2775](https://linux-hardware.org/?probe=bcb5af2775) | May 24, 2023 |
| HP            | 8307                        | [6797c02e08](https://linux-hardware.org/?probe=6797c02e08) | May 24, 2023 |
| ASUSTek       | ROG ZENITH EXTREME          | [402231776b](https://linux-hardware.org/?probe=402231776b) | May 23, 2023 |
| Gigabyte      | B250-FinTech-CF             | [d8d33293ef](https://linux-hardware.org/?probe=d8d33293ef) | May 23, 2023 |
| MSI           | B460M PRO                   | [94ce62125f](https://linux-hardware.org/?probe=94ce62125f) | May 23, 2023 |
| HP            | 3647h                       | [fc8cf5c799](https://linux-hardware.org/?probe=fc8cf5c799) | May 23, 2023 |
| ASRock        | B450M Pro4                  | [2d42a4443c](https://linux-hardware.org/?probe=2d42a4443c) | May 23, 2023 |
| ASUSTek       | PRIME B550M-A               | [de335816aa](https://linux-hardware.org/?probe=de335816aa) | May 22, 2023 |
| ASRock        | B550 Taichi                 | [175272b7e0](https://linux-hardware.org/?probe=175272b7e0) | May 22, 2023 |
| Gigabyte      | GA-880GM-UD2H               | [e110548f6e](https://linux-hardware.org/?probe=e110548f6e) | May 22, 2023 |
| MSI           | X370 GAMING PRO CARBON A... | [71730fa381](https://linux-hardware.org/?probe=71730fa381) | May 22, 2023 |
| Lenovo        | ThinkCentre M58p 7220A72    | [c2965aff69](https://linux-hardware.org/?probe=c2965aff69) | May 22, 2023 |
| ASUSTek       | PRIME B550M-A               | [63b100e342](https://linux-hardware.org/?probe=63b100e342) | May 22, 2023 |
| HP            | 1589                        | [a7d56849a5](https://linux-hardware.org/?probe=a7d56849a5) | May 22, 2023 |
| Unknown       | Unknown                     | [9cc7b8d0a8](https://linux-hardware.org/?probe=9cc7b8d0a8) | May 22, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [94c7ddea69](https://linux-hardware.org/?probe=94c7ddea69) | May 21, 2023 |
| Fujitsu Si... | D2831-S1 S26361-D2831-S1    | [0d2426a070](https://linux-hardware.org/?probe=0d2426a070) | May 21, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [2ae04bd0d4](https://linux-hardware.org/?probe=2ae04bd0d4) | May 21, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [2adc02040e](https://linux-hardware.org/?probe=2adc02040e) | May 21, 2023 |
| ASRock        | B550M-ITX/ac                | [b03cb56dfa](https://linux-hardware.org/?probe=b03cb56dfa) | May 21, 2023 |
| ASUSTek       | G10DK                       | [b19380fb21](https://linux-hardware.org/?probe=b19380fb21) | May 21, 2023 |
| Acer          | Aspire XC-705               | [bdd393edd7](https://linux-hardware.org/?probe=bdd393edd7) | May 21, 2023 |
| ASRock        | H310CM-HG4                  | [6f698f47d8](https://linux-hardware.org/?probe=6f698f47d8) | May 21, 2023 |
| ASUSTek       | PRIME Z370-P                | [b3564ca1cf](https://linux-hardware.org/?probe=b3564ca1cf) | May 20, 2023 |
| ASUSTek       | P5B                         | [3effc437bb](https://linux-hardware.org/?probe=3effc437bb) | May 20, 2023 |
| ASRock        | A320M-HD                    | [1a05e80ee5](https://linux-hardware.org/?probe=1a05e80ee5) | May 20, 2023 |
| Gigabyte      | B550M S2H                   | [04dac52364](https://linux-hardware.org/?probe=04dac52364) | May 19, 2023 |
| MSI           | 2A9C                        | [78d54a3ebf](https://linux-hardware.org/?probe=78d54a3ebf) | May 19, 2023 |
| ASRock        | X470 Taichi                 | [a6755db2c4](https://linux-hardware.org/?probe=a6755db2c4) | May 19, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [52bfbb69ee](https://linux-hardware.org/?probe=52bfbb69ee) | May 19, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [6d04bdb08d](https://linux-hardware.org/?probe=6d04bdb08d) | May 19, 2023 |
| Lenovo        | 314F SDK0J40697 WIN 3305... | [ebe436d0b5](https://linux-hardware.org/?probe=ebe436d0b5) | May 18, 2023 |
| ASRock        | B85M-HDS                    | [411344a862](https://linux-hardware.org/?probe=411344a862) | May 18, 2023 |
| ASRock        | B85M-HDS                    | [868d98e4f4](https://linux-hardware.org/?probe=868d98e4f4) | May 18, 2023 |
| Gigabyte      | X99-UD4-CF                  | [0eec4b5bbe](https://linux-hardware.org/?probe=0eec4b5bbe) | May 18, 2023 |
| MSI           | MPG B650I EDGE WIFI         | [c15ff8f4c4](https://linux-hardware.org/?probe=c15ff8f4c4) | May 18, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [4c72848255](https://linux-hardware.org/?probe=4c72848255) | May 18, 2023 |
| Lenovo        | MAHOBAY NOK                 | [a33efd912c](https://linux-hardware.org/?probe=a33efd912c) | May 18, 2023 |
| Gigabyte      | Z790 GAMING X AX            | [09f9f2e231](https://linux-hardware.org/?probe=09f9f2e231) | May 17, 2023 |
| HP            | 3048h                       | [9e65995057](https://linux-hardware.org/?probe=9e65995057) | May 17, 2023 |
| ASUSTek       | M5A97 R2.0                  | [5d77e9825a](https://linux-hardware.org/?probe=5d77e9825a) | May 17, 2023 |
| Dell          | 0D6H9T A00                  | [e4787e9b05](https://linux-hardware.org/?probe=e4787e9b05) | May 17, 2023 |
| ASUSTek       | PRIME Z490-A                | [c3f3d961bb](https://linux-hardware.org/?probe=c3f3d961bb) | May 17, 2023 |
| ASUSTek       | PRIME Z370-A                | [cf08703fd3](https://linux-hardware.org/?probe=cf08703fd3) | May 17, 2023 |
| ASUSTek       | D700SC                      | [eab212a67d](https://linux-hardware.org/?probe=eab212a67d) | May 17, 2023 |
| HP            | 8055                        | [0efb5c8b5d](https://linux-hardware.org/?probe=0efb5c8b5d) | May 17, 2023 |
| ASUSTek       | PRIME B550M-A               | [d4b209ad20](https://linux-hardware.org/?probe=d4b209ad20) | May 17, 2023 |
| HP            | 8055                        | [d660088965](https://linux-hardware.org/?probe=d660088965) | May 17, 2023 |
| ASRock        | B450M Pro4                  | [c05d5e127e](https://linux-hardware.org/?probe=c05d5e127e) | May 16, 2023 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | [9b29aafd95](https://linux-hardware.org/?probe=9b29aafd95) | May 16, 2023 |
| MSI           | MAG B560M MORTAR            | [2323128fd2](https://linux-hardware.org/?probe=2323128fd2) | May 16, 2023 |
| iRU           | A231                        | [0b35bba039](https://linux-hardware.org/?probe=0b35bba039) | May 16, 2023 |
| Gigabyte      | GA-990FX-GAMING             | [d7503c22b2](https://linux-hardware.org/?probe=d7503c22b2) | May 16, 2023 |
| Dell          | 09KPNV A01                  | [15b4320ae1](https://linux-hardware.org/?probe=15b4320ae1) | May 16, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [294fe7853f](https://linux-hardware.org/?probe=294fe7853f) | May 15, 2023 |
| Gigabyte      | GA-990FX-GAMING             | [cc42c4e227](https://linux-hardware.org/?probe=cc42c4e227) | May 15, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [4529ae76bb](https://linux-hardware.org/?probe=4529ae76bb) | May 15, 2023 |
| Gigabyte      | H310M S2H x.x               | [8f36de95ee](https://linux-hardware.org/?probe=8f36de95ee) | May 15, 2023 |
| Gigabyte      | H310M S2H x.x               | [975de0cf0d](https://linux-hardware.org/?probe=975de0cf0d) | May 15, 2023 |
| Gigabyte      | B450M S2H                   | [5a28a0c505](https://linux-hardware.org/?probe=5a28a0c505) | May 15, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [14a0c32722](https://linux-hardware.org/?probe=14a0c32722) | May 15, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | [58f493d242](https://linux-hardware.org/?probe=58f493d242) | May 15, 2023 |
| AMI           | Intel                       | [05850f17d5](https://linux-hardware.org/?probe=05850f17d5) | May 14, 2023 |
| iRU           | A231                        | [8c941b1457](https://linux-hardware.org/?probe=8c941b1457) | May 14, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [71acd5de88](https://linux-hardware.org/?probe=71acd5de88) | May 14, 2023 |
| ASRock        | B450M Pro4                  | [1f657b2f59](https://linux-hardware.org/?probe=1f657b2f59) | May 14, 2023 |
| Gigabyte      | A320M-S2H-CF                | [f5fa402f37](https://linux-hardware.org/?probe=f5fa402f37) | May 14, 2023 |
| ASRock        | AD2700-ITX                  | [fe80771d2e](https://linux-hardware.org/?probe=fe80771d2e) | May 14, 2023 |
| ASUSTek       | PRIME B450M-A               | [784de41090](https://linux-hardware.org/?probe=784de41090) | May 14, 2023 |
| ASUSTek       | PRIME B450M-A               | [e3dedcbd6a](https://linux-hardware.org/?probe=e3dedcbd6a) | May 14, 2023 |
| MSI           | 990XA-GD55                  | [98693ec64b](https://linux-hardware.org/?probe=98693ec64b) | May 14, 2023 |
| Gigabyte      | B550M DS3H                  | [f2d7d4ba58](https://linux-hardware.org/?probe=f2d7d4ba58) | May 14, 2023 |
| ASUSTek       | PRIME H310M-K               | [12b97cd9b6](https://linux-hardware.org/?probe=12b97cd9b6) | May 13, 2023 |
| Gigabyte      | A320M-S2H-CF                | [fd2bd3be00](https://linux-hardware.org/?probe=fd2bd3be00) | May 13, 2023 |
| ASRock        | H55M-LE                     | [e31e211aa2](https://linux-hardware.org/?probe=e31e211aa2) | May 13, 2023 |
| ASRock        | H55M-LE                     | [8f2f79fb45](https://linux-hardware.org/?probe=8f2f79fb45) | May 13, 2023 |
| Gigabyte      | B550 GAMING X V2            | [68573d1b85](https://linux-hardware.org/?probe=68573d1b85) | May 13, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [efab80e399](https://linux-hardware.org/?probe=efab80e399) | May 13, 2023 |
| ASUSTek       | P5Q-E                       | [9efa5d994b](https://linux-hardware.org/?probe=9efa5d994b) | May 12, 2023 |
| Gigabyte      | Z87X-OC-CF                  | [068ef24174](https://linux-hardware.org/?probe=068ef24174) | May 12, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | [b9a3dfd029](https://linux-hardware.org/?probe=b9a3dfd029) | May 12, 2023 |
| Biostar       | A320MH                      | [d30baf9379](https://linux-hardware.org/?probe=d30baf9379) | May 12, 2023 |
| Huanan        | B75 V10.1 376               | [3c8b5aefd8](https://linux-hardware.org/?probe=3c8b5aefd8) | May 11, 2023 |
| ASUSTek       | Z170-P                      | [17d57b61d7](https://linux-hardware.org/?probe=17d57b61d7) | May 11, 2023 |
| Gigabyte      | G41MT-D3                    | [393b2da4bc](https://linux-hardware.org/?probe=393b2da4bc) | May 11, 2023 |
| ASUSTek       | PRIME B550M-A               | [d03175163f](https://linux-hardware.org/?probe=d03175163f) | May 11, 2023 |
| MSI           | PRO H610M-E DDR4            | [ceff5a622d](https://linux-hardware.org/?probe=ceff5a622d) | May 11, 2023 |
| ASUSTek       | PRIME Z270-P                | [e826ca7941](https://linux-hardware.org/?probe=e826ca7941) | May 11, 2023 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [cb4250603d](https://linux-hardware.org/?probe=cb4250603d) | May 10, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | [d9f5e85b9b](https://linux-hardware.org/?probe=d9f5e85b9b) | May 10, 2023 |
| AOpen         | aA70Mx-VW R1.01 55DE8100... | [400b616f1c](https://linux-hardware.org/?probe=400b616f1c) | May 10, 2023 |
| ASUSTek       | PRIME B550M-A               | [ea1c5040a8](https://linux-hardware.org/?probe=ea1c5040a8) | May 10, 2023 |
| ASUSTek       | E3M-ET V5 SERIES            | [64f08f10f3](https://linux-hardware.org/?probe=64f08f10f3) | May 10, 2023 |
| Dell          | 04Y8V0 A02                  | [d21ef87b63](https://linux-hardware.org/?probe=d21ef87b63) | May 10, 2023 |
| Dell          | 0VXN67 A01                  | [0985b52dee](https://linux-hardware.org/?probe=0985b52dee) | May 09, 2023 |
| Dell          | 0VXN67 A01                  | [b7fd2a3e2f](https://linux-hardware.org/?probe=b7fd2a3e2f) | May 09, 2023 |
| ASUSTek       | B85M-GAMER                  | [2f0a5430a3](https://linux-hardware.org/?probe=2f0a5430a3) | May 09, 2023 |
| Dell          | 08NPPY A00                  | [6c55bc2118](https://linux-hardware.org/?probe=6c55bc2118) | May 09, 2023 |
| ASUSTek       | PRIME X570-PRO              | [249e9efecb](https://linux-hardware.org/?probe=249e9efecb) | May 08, 2023 |
| Gigabyte      | GA-78LMT-S2                 | [631317f909](https://linux-hardware.org/?probe=631317f909) | May 08, 2023 |
| ASRock        | Z87 Pro4                    | [e3971068b6](https://linux-hardware.org/?probe=e3971068b6) | May 08, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [e6ead6e953](https://linux-hardware.org/?probe=e6ead6e953) | May 08, 2023 |
| ASUSTek       | PRIME B550M-A               | [e7f4395ed8](https://linux-hardware.org/?probe=e7f4395ed8) | May 08, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [76748da9cd](https://linux-hardware.org/?probe=76748da9cd) | May 08, 2023 |
| Lenovo        | SHARKBAY NOK                | [e35b234e43](https://linux-hardware.org/?probe=e35b234e43) | May 07, 2023 |
| HPE           | ProLiant ML30 Gen10 Plus    | [3a75fa5c03](https://linux-hardware.org/?probe=3a75fa5c03) | May 07, 2023 |
| Dell          | 042P49 A02                  | [de394c8663](https://linux-hardware.org/?probe=de394c8663) | May 07, 2023 |
| MSI           | PRO B660M-A DDR4            | [13e08da76d](https://linux-hardware.org/?probe=13e08da76d) | May 07, 2023 |
| ASRock        | X570 Phantom Gaming X       | [4681975f9d](https://linux-hardware.org/?probe=4681975f9d) | May 07, 2023 |
| ASRock        | B360M IB-R1                 | [ac982522ab](https://linux-hardware.org/?probe=ac982522ab) | May 07, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [bdafbe06aa](https://linux-hardware.org/?probe=bdafbe06aa) | May 07, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [98008481eb](https://linux-hardware.org/?probe=98008481eb) | May 07, 2023 |
| ASUSTek       | P5Q SE/R                    | [4d78dbbdc6](https://linux-hardware.org/?probe=4d78dbbdc6) | May 06, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [e5488a0dc9](https://linux-hardware.org/?probe=e5488a0dc9) | May 06, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [d9a3afa732](https://linux-hardware.org/?probe=d9a3afa732) | May 06, 2023 |
| Gigabyte      | J1900M-D2P                  | [f743e9293e](https://linux-hardware.org/?probe=f743e9293e) | May 06, 2023 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [421f2de1c3](https://linux-hardware.org/?probe=421f2de1c3) | May 05, 2023 |
| ASUSTek       | PRIME B350M-A               | [c5a8cec4f6](https://linux-hardware.org/?probe=c5a8cec4f6) | May 05, 2023 |
| Dell          | 0YXT71 A01                  | [bbe145a1a2](https://linux-hardware.org/?probe=bbe145a1a2) | May 05, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [c15634ffe4](https://linux-hardware.org/?probe=c15634ffe4) | May 05, 2023 |
| ASRock        | H81M-HG4 R4.0               | [cc6641b5d9](https://linux-hardware.org/?probe=cc6641b5d9) | May 04, 2023 |
| Lenovo        | SHARKBAY NOK                | [2ebe14f5d0](https://linux-hardware.org/?probe=2ebe14f5d0) | May 04, 2023 |
| MSI           | MAG B660M MORTAR MAX WIF... | [826499629c](https://linux-hardware.org/?probe=826499629c) | May 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [c490e68d59](https://linux-hardware.org/?probe=c490e68d59) | May 03, 2023 |
| Gigabyte      | B85-HD3                     | [1e7a8a2576](https://linux-hardware.org/?probe=1e7a8a2576) | May 03, 2023 |
| MSI           | B450M MORTAR MAX            | [91f2551511](https://linux-hardware.org/?probe=91f2551511) | May 03, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [f8d80b7cf0](https://linux-hardware.org/?probe=f8d80b7cf0) | May 03, 2023 |
| MSI           | MS-7388                     | [948e1d2358](https://linux-hardware.org/?probe=948e1d2358) | May 03, 2023 |
| Lenovo        | SHARKBAY NOK                | [71bf54960f](https://linux-hardware.org/?probe=71bf54960f) | May 02, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [3a39bf574b](https://linux-hardware.org/?probe=3a39bf574b) | May 02, 2023 |
| MSI           | A520M PRO                   | [c87539eaec](https://linux-hardware.org/?probe=c87539eaec) | May 02, 2023 |
| Gigabyte      | GA-880GM-UD2H               | [a23cace014](https://linux-hardware.org/?probe=a23cace014) | May 02, 2023 |
| ASUSTek       | PRIME B550M-A               | [fb9d21e345](https://linux-hardware.org/?probe=fb9d21e345) | May 02, 2023 |
| ASRock        | H61M-VS                     | [4946cab965](https://linux-hardware.org/?probe=4946cab965) | May 01, 2023 |
| ASUSTek       | PRIME A320M-K               | [c2b7a8dbe1](https://linux-hardware.org/?probe=c2b7a8dbe1) | May 01, 2023 |
| Gigabyte      | B550 GAMING X V2            | [15c40bae27](https://linux-hardware.org/?probe=15c40bae27) | May 01, 2023 |
| ASRock        | B550 Taichi                 | [826fd3bad0](https://linux-hardware.org/?probe=826fd3bad0) | May 01, 2023 |
| MSI           | MS-7388                     | [ec819aca80](https://linux-hardware.org/?probe=ec819aca80) | May 01, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [a1b8584d65](https://linux-hardware.org/?probe=a1b8584d65) | May 01, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [d02d21f47a](https://linux-hardware.org/?probe=d02d21f47a) | May 01, 2023 |
| ASUSTek       | PRIME B550M-A               | [9146d12231](https://linux-hardware.org/?probe=9146d12231) | May 01, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [2fcc250a35](https://linux-hardware.org/?probe=2fcc250a35) | May 01, 2023 |
| ASRock        | A520M-ITX/ac                | [5a9f58bcc0](https://linux-hardware.org/?probe=5a9f58bcc0) | Apr 30, 2023 |
| Gigabyte      | 970A-DS3P                   | [c1fe7a5f87](https://linux-hardware.org/?probe=c1fe7a5f87) | Apr 30, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [01311e320c](https://linux-hardware.org/?probe=01311e320c) | Apr 30, 2023 |
| MSI           | MPG B650I EDGE WIFI         | [eda4874295](https://linux-hardware.org/?probe=eda4874295) | Apr 30, 2023 |
| ASUSTek       | X99-A                       | [6505e46b86](https://linux-hardware.org/?probe=6505e46b86) | Apr 29, 2023 |
| ASUSTek       | P5B-Deluxe                  | [d0d3458299](https://linux-hardware.org/?probe=d0d3458299) | Apr 29, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [4b47a4606b](https://linux-hardware.org/?probe=4b47a4606b) | Apr 29, 2023 |
| MSI           | B450 TOMAHAWK               | [1404923301](https://linux-hardware.org/?probe=1404923301) | Apr 28, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [e65094a8f6](https://linux-hardware.org/?probe=e65094a8f6) | Apr 28, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E GENE    | [c416a3f44a](https://linux-hardware.org/?probe=c416a3f44a) | Apr 28, 2023 |
| Dell          | 0VHWTR A01                  | [1a73639c02](https://linux-hardware.org/?probe=1a73639c02) | Apr 28, 2023 |
| ASUSTek       | PRIME A520M-E               | [048fda2c60](https://linux-hardware.org/?probe=048fda2c60) | Apr 28, 2023 |
| Unknown       | HX90                        | [8454daed68](https://linux-hardware.org/?probe=8454daed68) | Apr 28, 2023 |
| Dell          | 0VHWTR A01                  | [6f56840307](https://linux-hardware.org/?probe=6f56840307) | Apr 28, 2023 |
| HP            | 83E9                        | [ac8ad5d3d5](https://linux-hardware.org/?probe=ac8ad5d3d5) | Apr 28, 2023 |
| HP            | 8062                        | [61c4685659](https://linux-hardware.org/?probe=61c4685659) | Apr 27, 2023 |
| ASUSTek       | PRIME A320M-K               | [155ce08a00](https://linux-hardware.org/?probe=155ce08a00) | Apr 27, 2023 |
| MSI           | X570-A PRO                  | [15b900cf50](https://linux-hardware.org/?probe=15b900cf50) | Apr 27, 2023 |
| MSI           | X570-A PRO                  | [d5b1ec921a](https://linux-hardware.org/?probe=d5b1ec921a) | Apr 27, 2023 |
| ASUSTek       | PRIME Z490-A                | [9088ae517a](https://linux-hardware.org/?probe=9088ae517a) | Apr 27, 2023 |
| Lenovo        | SHARKBAY NOK                | [e694779b17](https://linux-hardware.org/?probe=e694779b17) | Apr 26, 2023 |
| Lenovo        | SHARKBAY NOK                | [1e07e42dd3](https://linux-hardware.org/?probe=1e07e42dd3) | Apr 26, 2023 |
| MSI           | X470 GAMING PLUS            | [a5d42a7b78](https://linux-hardware.org/?probe=a5d42a7b78) | Apr 26, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | [474c43577f](https://linux-hardware.org/?probe=474c43577f) | Apr 26, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [e14205d01a](https://linux-hardware.org/?probe=e14205d01a) | Apr 26, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [f1f2ad2731](https://linux-hardware.org/?probe=f1f2ad2731) | Apr 26, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [5ce448176d](https://linux-hardware.org/?probe=5ce448176d) | Apr 26, 2023 |
| ASUSTek       | PRIME H610M-A D4            | [a7e77375d4](https://linux-hardware.org/?probe=a7e77375d4) | Apr 26, 2023 |
| ASUSTek       | PRIME B550M-A               | [ba83f4a4f7](https://linux-hardware.org/?probe=ba83f4a4f7) | Apr 26, 2023 |
| ASUSTek       | P8H61-M LE                  | [a7a9d5069c](https://linux-hardware.org/?probe=a7a9d5069c) | Apr 26, 2023 |
| ASUSTek       | P8H61-M LE                  | [cd60dbbd6a](https://linux-hardware.org/?probe=cd60dbbd6a) | Apr 26, 2023 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [8c9b08bcab](https://linux-hardware.org/?probe=8c9b08bcab) | Apr 26, 2023 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [6007547b60](https://linux-hardware.org/?probe=6007547b60) | Apr 25, 2023 |
| ASRock        | X300M-STX                   | [4a8d662bee](https://linux-hardware.org/?probe=4a8d662bee) | Apr 25, 2023 |
| Dell          | 040DDP A00                  | [8595139862](https://linux-hardware.org/?probe=8595139862) | Apr 25, 2023 |
| Dell          | 0YXT71 A03                  | [abc091f5c0](https://linux-hardware.org/?probe=abc091f5c0) | Apr 25, 2023 |
| Intel         | DQ67OW AAG12528-307         | [28245ea080](https://linux-hardware.org/?probe=28245ea080) | Apr 25, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [f878b7d23a](https://linux-hardware.org/?probe=f878b7d23a) | Apr 25, 2023 |
| ASRock        | H310M-STX                   | [9988bc063a](https://linux-hardware.org/?probe=9988bc063a) | Apr 25, 2023 |
| ASUSTek       | PRIME B550M-A               | [8fbbad22fa](https://linux-hardware.org/?probe=8fbbad22fa) | Apr 25, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [98ffa037d9](https://linux-hardware.org/?probe=98ffa037d9) | Apr 24, 2023 |
| Dell          | 08WXMX A02                  | [5f68c6a285](https://linux-hardware.org/?probe=5f68c6a285) | Apr 24, 2023 |
| HP            | 18E7                        | [c5bc4d9c7f](https://linux-hardware.org/?probe=c5bc4d9c7f) | Apr 23, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [88036a75ec](https://linux-hardware.org/?probe=88036a75ec) | Apr 23, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [b9496d6431](https://linux-hardware.org/?probe=b9496d6431) | Apr 23, 2023 |
| HP            | 8062                        | [37cde2dc48](https://linux-hardware.org/?probe=37cde2dc48) | Apr 23, 2023 |
| Dell          | 0HD5W2 A00                  | [336c1b5da9](https://linux-hardware.org/?probe=336c1b5da9) | Apr 23, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [a82d805ad2](https://linux-hardware.org/?probe=a82d805ad2) | Apr 22, 2023 |
| Pegatron      | Benicia                     | [362a3ff341](https://linux-hardware.org/?probe=362a3ff341) | Apr 22, 2023 |
| Gigabyte      | B550M DS3H                  | [1950979b24](https://linux-hardware.org/?probe=1950979b24) | Apr 22, 2023 |
| MSI           | B450M MORTAR MAX            | [7560923404](https://linux-hardware.org/?probe=7560923404) | Apr 22, 2023 |
| Dell          | 0CRH6C A00                  | [cbb78e1785](https://linux-hardware.org/?probe=cbb78e1785) | Apr 22, 2023 |
| Gigabyte      | E3000N                      | [a6d7a7356a](https://linux-hardware.org/?probe=a6d7a7356a) | Apr 22, 2023 |
| AZW           | GTR V02                     | [104badc0d7](https://linux-hardware.org/?probe=104badc0d7) | Apr 22, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [079c071335](https://linux-hardware.org/?probe=079c071335) | Apr 22, 2023 |
| Techvision    | TVI7309X B0                 | [26e981dab3](https://linux-hardware.org/?probe=26e981dab3) | Apr 22, 2023 |
| ASUSTek       | PRIME A320M-K               | [fb1f9f0d16](https://linux-hardware.org/?probe=fb1f9f0d16) | Apr 21, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [a898476ffa](https://linux-hardware.org/?probe=a898476ffa) | Apr 21, 2023 |
| ASRock        | AD2700-ITX                  | [e688e656cd](https://linux-hardware.org/?probe=e688e656cd) | Apr 21, 2023 |
| HP            | 843F                        | [0060103f89](https://linux-hardware.org/?probe=0060103f89) | Apr 21, 2023 |
| Lenovo        | 3753 SDK0T76461 WIN 3422... | [65c9942c32](https://linux-hardware.org/?probe=65c9942c32) | Apr 21, 2023 |
| Lenovo        | 3753 SDK0T76461 WIN 3422... | [607dbbf4d8](https://linux-hardware.org/?probe=607dbbf4d8) | Apr 21, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [8e7095e453](https://linux-hardware.org/?probe=8e7095e453) | Apr 20, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [f7ca0a552d](https://linux-hardware.org/?probe=f7ca0a552d) | Apr 20, 2023 |
| ASUSTek       | CG8270                      | [3f390ff38e](https://linux-hardware.org/?probe=3f390ff38e) | Apr 20, 2023 |
| ASUSTek       | CG8270                      | [a4f54ca55b](https://linux-hardware.org/?probe=a4f54ca55b) | Apr 20, 2023 |
| Gigabyte      | A320M-S2H-CF                | [063b4867ba](https://linux-hardware.org/?probe=063b4867ba) | Apr 20, 2023 |
| ASUSTek       | PRIME B360-PLUS             | [00b1045cf9](https://linux-hardware.org/?probe=00b1045cf9) | Apr 20, 2023 |
| Gigabyte      | B85-HD3                     | [07ecc38bef](https://linux-hardware.org/?probe=07ecc38bef) | Apr 20, 2023 |
| HP            | 89D8 SMVB                   | [c4c1d8086c](https://linux-hardware.org/?probe=c4c1d8086c) | Apr 20, 2023 |
| Dell          | 08NPPY A00                  | [6780931a5d](https://linux-hardware.org/?probe=6780931a5d) | Apr 19, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | [96f6b41a5c](https://linux-hardware.org/?probe=96f6b41a5c) | Apr 19, 2023 |
| AMI           | Intel                       | [3f1890d683](https://linux-hardware.org/?probe=3f1890d683) | Apr 19, 2023 |
| Gigabyte      | B85M-D3V-A                  | [84dbb8ae74](https://linux-hardware.org/?probe=84dbb8ae74) | Apr 19, 2023 |
| Dell          | 0GXM1W A00                  | [3060afd7f7](https://linux-hardware.org/?probe=3060afd7f7) | Apr 19, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [cb1db50c6c](https://linux-hardware.org/?probe=cb1db50c6c) | Apr 18, 2023 |
| Gigabyte      | 970A-DS3P                   | [e2f136f068](https://linux-hardware.org/?probe=e2f136f068) | Apr 14, 2023 |
| MSI           | MS-7388                     | [4efa2b04da](https://linux-hardware.org/?probe=4efa2b04da) | Apr 14, 2023 |
| Gigabyte      | X79-UD3                     | [d2fbfe344c](https://linux-hardware.org/?probe=d2fbfe344c) | Apr 12, 2023 |
| ASUSTek       | E3M-ET V5 SERIES            | [7e0735056c](https://linux-hardware.org/?probe=7e0735056c) | Apr 12, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [fb8ef4b4af](https://linux-hardware.org/?probe=fb8ef4b4af) | Apr 06, 2023 |
| MSI           | B450I GAMING PLUS AC        | [adda27b48e](https://linux-hardware.org/?probe=adda27b48e) | Apr 06, 2023 |
| Gigabyte      | H610M S2H DDR4              | [b34f7e7ea6](https://linux-hardware.org/?probe=b34f7e7ea6) | Apr 05, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [53fc9d8c25](https://linux-hardware.org/?probe=53fc9d8c25) | Apr 04, 2023 |
| Pegatron      | 2ACB                        | [f35bc7fec6](https://linux-hardware.org/?probe=f35bc7fec6) | Apr 04, 2023 |
| Unknown       | Unknown                     | [02a35c15b7](https://linux-hardware.org/?probe=02a35c15b7) | Apr 03, 2023 |
| Gigabyte      | B85M-D3V-A                  | [1789a17694](https://linux-hardware.org/?probe=1789a17694) | Apr 03, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [36f91bbb2d](https://linux-hardware.org/?probe=36f91bbb2d) | Apr 02, 2023 |
| ASUSTek       | PRIME B250M-A               | [575a0650aa](https://linux-hardware.org/?probe=575a0650aa) | Apr 01, 2023 |
| ASUSTek       | PRIME B250M-A               | [dc5fce2825](https://linux-hardware.org/?probe=dc5fce2825) | Apr 01, 2023 |
| HP            | 18E7                        | [6b64a1639b](https://linux-hardware.org/?probe=6b64a1639b) | Mar 30, 2023 |
| Gigabyte      | B85M-D3V-A                  | [06ad8e8099](https://linux-hardware.org/?probe=06ad8e8099) | Mar 29, 2023 |
| ASUSTek       | PRIME B550M-K               | [81dc7d8f53](https://linux-hardware.org/?probe=81dc7d8f53) | Mar 27, 2023 |
| Acer          | Aspire M3910                | [8cc87c48d1](https://linux-hardware.org/?probe=8cc87c48d1) | Mar 27, 2023 |
| PCWare        | IPMH310G                    | [3cc2e91e56](https://linux-hardware.org/?probe=3cc2e91e56) | Mar 24, 2023 |
| MSI           | Z370-A PRO                  | [87bce00c67](https://linux-hardware.org/?probe=87bce00c67) | Mar 21, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [e7ff5cdaae](https://linux-hardware.org/?probe=e7ff5cdaae) | Mar 21, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [fc2a6e486c](https://linux-hardware.org/?probe=fc2a6e486c) | Mar 17, 2023 |
| Gigabyte      | H81M-H                      | [0ac96925cd](https://linux-hardware.org/?probe=0ac96925cd) | Mar 16, 2023 |
| Pegatron      | 2ACB                        | [d36124f8d9](https://linux-hardware.org/?probe=d36124f8d9) | Mar 16, 2023 |
| ASRock        | H310M-STX                   | [ea6af9ac0b](https://linux-hardware.org/?probe=ea6af9ac0b) | Mar 16, 2023 |
| ASRock        | H310M-STX                   | [56c7261b06](https://linux-hardware.org/?probe=56c7261b06) | Mar 16, 2023 |
| Gigabyte      | Z77X-UD3H                   | [c483268c88](https://linux-hardware.org/?probe=c483268c88) | Mar 16, 2023 |
| ASUSTek       | PRIME Z270-A                | [047e561901](https://linux-hardware.org/?probe=047e561901) | Mar 14, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [89e2967e3c](https://linux-hardware.org/?probe=89e2967e3c) | Mar 12, 2023 |
| ASUSTek       | TUF Gaming B660M-E D4       | [5d94a30450](https://linux-hardware.org/?probe=5d94a30450) | Mar 05, 2023 |
| ASUSTek       | PRIME B550M-K               | [91fab60d63](https://linux-hardware.org/?probe=91fab60d63) | Mar 04, 2023 |
| MSI           | MEG Z390 GODLIKE            | [b61241e05e](https://linux-hardware.org/?probe=b61241e05e) | Mar 04, 2023 |
| MSI           | MEG Z390 GODLIKE            | [871c72708d](https://linux-hardware.org/?probe=871c72708d) | Mar 04, 2023 |
| ASRock        | H81M-HG4 R4.0               | [47ed7baef0](https://linux-hardware.org/?probe=47ed7baef0) | Feb 28, 2023 |
| MSI           | MEG Z390 GODLIKE            | [5f091de01b](https://linux-hardware.org/?probe=5f091de01b) | Feb 23, 2023 |
| MSI           | MEG Z390 GODLIKE            | [974ae4135b](https://linux-hardware.org/?probe=974ae4135b) | Feb 22, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [731f916db1](https://linux-hardware.org/?probe=731f916db1) | Dec 27, 2022 |
| MSI           | FM2-A55M-E33                | [1fe306ae1e](https://linux-hardware.org/?probe=1fe306ae1e) | Oct 13, 2022 |
| MSI           | FM2-A55M-E33                | [4867faffbf](https://linux-hardware.org/?probe=4867faffbf) | Sep 23, 2022 |
| Biostar       | A780L3G                     | [e53730ab48](https://linux-hardware.org/?probe=e53730ab48) | Sep 09, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora_38/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                                | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| 6.3.8-200.fc38.x86_64                                  | 71       | 12.18%  |
| 6.2.15-300.fc38.x86_64                                 | 69       | 11.84%  |
| 6.2.9-300.fc38.x86_64                                  | 60       | 10.29%  |
| 6.2.14-300.fc38.x86_64                                 | 46       | 7.89%   |
| 6.3.12-200.fc38.x86_64                                 | 39       | 6.69%   |
| 6.2.11-300.fc38.x86_64                                 | 33       | 5.66%   |
| 6.3.11-200.fc38.x86_64                                 | 31       | 5.32%   |
| 6.4.6-200.fc38.x86_64                                  | 27       | 4.63%   |
| 6.3.5-200.fc38.x86_64                                  | 24       | 4.12%   |
| 6.3.4-201.fc38.x86_64                                  | 22       | 3.77%   |
| 6.2.12-300.fc38.x86_64                                 | 22       | 3.77%   |
| 6.4.7-200.fc38.x86_64                                  | 21       | 3.6%    |
| 6.3.7-200.fc38.x86_64                                  | 19       | 3.26%   |
| 6.4.4-200.fc38.x86_64                                  | 17       | 2.92%   |
| 6.2.13-300.fc38.x86_64                                 | 17       | 2.92%   |
| 6.3.6-200.fc38.x86_64                                  | 13       | 2.23%   |
| 6.2.8-300.fc38.x86_64                                  | 4        | 0.69%   |
| 6.2.6-300.fc38.x86_64                                  | 4        | 0.69%   |
| 6.2.15-703.inttf.fc38.x86_64                           | 4        | 0.69%   |
| 6.4.9-200.fc38.x86_64                                  | 3        | 0.51%   |
| 6.4.8-200.fc38.x86_64                                  | 3        | 0.51%   |
| 6.3.3-200.fc38.x86_64                                  | 3        | 0.51%   |
| 6.2.7-300.fc38.x86_64                                  | 3        | 0.51%   |
| 6.3.10-200.fc38.x86_64                                 | 2        | 0.34%   |
| 6.2.2-300.fc38.x86_64                                  | 2        | 0.34%   |
| 6.2.10-300.fc38.x86_64                                 | 2        | 0.34%   |
| 6.2.0-63.fc38.x86_64                                   | 2        | 0.34%   |
| 6.5.0-0.rc2.20230721gitf7e3a1bafdea.20.fc39.x86_64     | 1        | 0.17%   |
| 6.4.4-202.fsync.fc38.x86_64                            | 1        | 0.17%   |
| 6.4.2-201.fc38.x86_64                                  | 1        | 0.17%   |
| 6.4.0-0.rc5.20230607gta4d7d701.342.vanilla.fc38.x86_64 | 1        | 0.17%   |
| 6.4.0-0.rc2.23.fc39.ppc64le                            | 1        | 0.17%   |
| 6.3.8-400.unixcart.fc38.x86_64                         | 1        | 0.17%   |
| 6.3.1-200.fc38.x86_64                                  | 1        | 0.17%   |
| 6.2.5-300.fc38.x86_64                                  | 1        | 0.17%   |
| 6.2.3-300.fc38.x86_64                                  | 1        | 0.17%   |
| 6.2.2-301.fc38.x86_64                                  | 1        | 0.17%   |
| 6.2.1-300.fc38.x86_64                                  | 1        | 0.17%   |
| 6.2.0-0.rc1.14.fc38.x86_64+debug                       | 1        | 0.17%   |
| 6.1.38-hardened1-1-hardened                            | 1        | 0.17%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2.15  | 73       | 12.52%  |
| 6.3.8   | 72       | 12.35%  |
| 6.2.9   | 60       | 10.29%  |
| 6.2.14  | 46       | 7.89%   |
| 6.3.12  | 39       | 6.69%   |
| 6.2.11  | 33       | 5.66%   |
| 6.3.11  | 31       | 5.32%   |
| 6.4.6   | 27       | 4.63%   |
| 6.3.5   | 24       | 4.12%   |
| 6.3.4   | 22       | 3.77%   |
| 6.2.12  | 22       | 3.77%   |
| 6.4.7   | 21       | 3.6%    |
| 6.3.7   | 19       | 3.26%   |
| 6.4.4   | 18       | 3.09%   |
| 6.2.13  | 17       | 2.92%   |
| 6.3.6   | 13       | 2.23%   |
| 6.2.8   | 4        | 0.69%   |
| 6.2.6   | 4        | 0.69%   |
| 6.4.9   | 3        | 0.51%   |
| 6.4.8   | 3        | 0.51%   |
| 6.3.3   | 3        | 0.51%   |
| 6.2.7   | 3        | 0.51%   |
| 6.2.2   | 3        | 0.51%   |
| 6.2.0   | 3        | 0.51%   |
| 6.4.0   | 2        | 0.34%   |
| 6.3.10  | 2        | 0.34%   |
| 6.2.10  | 2        | 0.34%   |
| 6.5.0   | 1        | 0.17%   |
| 6.4.2   | 1        | 0.17%   |
| 6.3.1   | 1        | 0.17%   |
| 6.2.5   | 1        | 0.17%   |
| 6.2.3   | 1        | 0.17%   |
| 6.2.1   | 1        | 0.17%   |
| 6.1.38  | 1        | 0.17%   |
| 6.1.31  | 1        | 0.17%   |
| 6.1.26  | 1        | 0.17%   |
| 6.1.18  | 1        | 0.17%   |
| 6.1.0   | 1        | 0.17%   |
| 6.0.7   | 1        | 0.17%   |
| 6.0.0   | 1        | 0.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2     | 257      | 46.14%  |
| 6.3     | 216      | 38.78%  |
| 6.4     | 75       | 13.46%  |
| 6.1     | 5        | 0.9%    |
| 6.0     | 2        | 0.36%   |
| 6.5     | 1        | 0.18%   |
| 5.19    | 1        | 0.18%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 521      | 99.81%  |
| ppc64le | 1        | 0.19%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 387      | 73.71%  |
| KDE5          | 86       | 16.38%  |
| Unknown       | 13       | 2.48%   |
| Cinnamon      | 12       | 2.29%   |
| XFCE          | 6        | 1.14%   |
| X-Cinnamon    | 5        | 0.95%   |
| GNOME Classic | 5        | 0.95%   |
| sway          | 4        | 0.76%   |
| MATE          | 1        | 0.19%   |
| LXQt          | 1        | 0.19%   |
| LXDE          | 1        | 0.19%   |
| KDE           | 1        | 0.19%   |
| Hyprland      | 1        | 0.19%   |
| Deepin        | 1        | 0.19%   |
| Budgie        | 1        | 0.19%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 392      | 74.24%  |
| X11     | 105      | 19.89%  |
| Tty     | 27       | 5.11%   |
| Unknown | 4        | 0.76%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 347      | 66.1%   |
| GDM     | 108      | 20.57%  |
| SDDM    | 44       | 8.38%   |
| LightDM | 25       | 4.76%   |
| LXDM    | 1        | 0.19%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 250      | 47.53%  |
| ru_RU | 32       | 6.08%   |
| en_AU | 32       | 6.08%   |
| de_DE | 27       | 5.13%   |
| pt_BR | 26       | 4.94%   |
| en_GB | 25       | 4.75%   |
| en_CA | 24       | 4.56%   |
| fr_FR | 13       | 2.47%   |
| it_IT | 12       | 2.28%   |
| es_ES | 10       | 1.9%    |
| pl_PL | 6        | 1.14%   |
| es_MX | 6        | 1.14%   |
| es_AR | 5        | 0.95%   |
| tr_TR | 4        | 0.76%   |
| es_CO | 4        | 0.76%   |
| fi_FI | 3        | 0.57%   |
| en_IN | 3        | 0.57%   |
| en_DK | 3        | 0.57%   |
| zh_TW | 2        | 0.38%   |
| sv_SE | 2        | 0.38%   |
| pt_PT | 2        | 0.38%   |
| hr_HR | 2        | 0.38%   |
| fr_CA | 2        | 0.38%   |
| en_NZ | 2        | 0.38%   |
| en_IE | 2        | 0.38%   |
| de_CH | 2        | 0.38%   |
| de_AT | 2        | 0.38%   |
| da_DK | 2        | 0.38%   |
| zh_SG | 1        | 0.19%   |
| sr_RS | 1        | 0.19%   |
| pa_IN | 1        | 0.19%   |
| nl_NL | 1        | 0.19%   |
| ja_JP | 1        | 0.19%   |
| id_ID | 1        | 0.19%   |
| ia_FR | 1        | 0.19%   |
| hu_HU | 1        | 0.19%   |
| gl_ES | 1        | 0.19%   |
| fr_BE | 1        | 0.19%   |
| es_VE | 1        | 0.19%   |
| es_PE | 1        | 0.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 383      | 73.09%  |
| BIOS | 141      | 26.91%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Btrfs   | 414      | 79.01%  |
| Ext4    | 87       | 16.6%   |
| Xfs     | 19       | 3.63%   |
| Overlay | 2        | 0.38%   |
| Zfs     | 1        | 0.19%   |
| F2fs    | 1        | 0.19%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 334      | 63.62%  |
| GPT     | 170      | 32.38%  |
| MBR     | 21       | 4%      |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 468      | 88.97%  |
| Yes       | 58       | 11.03%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 437      | 83.56%  |
| Yes       | 86       | 16.44%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 139      | 26.63%  |
| Gigabyte Technology                  | 101      | 19.35%  |
| MSI                                  | 98       | 18.77%  |
| ASRock                               | 47       | 9%      |
| Dell                                 | 33       | 6.32%   |
| Hewlett-Packard                      | 32       | 6.13%   |
| Lenovo                               | 14       | 2.68%   |
| Unknown                              | 8        | 1.53%   |
| Pegatron                             | 5        | 0.96%   |
| Itautec                              | 4        | 0.77%   |
| Intel                                | 4        | 0.77%   |
| Huanan                               | 4        | 0.77%   |
| AZW                                  | 4        | 0.77%   |
| Shenzhen Meigao Electronic Equipment | 3        | 0.57%   |
| Acer                                 | 3        | 0.57%   |
| HPE                                  | 2        | 0.38%   |
| Fujitsu                              | 2        | 0.38%   |
| Biostar                              | 2        | 0.38%   |
| Techvision                           | 1        | 0.19%   |
| PCWare                               | 1        | 0.19%   |
| MACHINIST                            | 1        | 0.19%   |
| LattePanda                           | 1        | 0.19%   |
| Kupi deshego edition                 | 1        | 0.19%   |
| Kllisre                              | 1        | 0.19%   |
| iRU                                  | 1        | 0.19%   |
| Gateway                              | 1        | 0.19%   |
| GALAX                                | 1        | 0.19%   |
| Fujitsu Siemens                      | 1        | 0.19%   |
| Foxconn                              | 1        | 0.19%   |
| Fill By OEM                          | 1        | 0.19%   |
| ECS                                  | 1        | 0.19%   |
| Colorful Technology                  | 1        | 0.19%   |
| AOpen                                | 1        | 0.19%   |
| AMI                                  | 1        | 0.19%   |
| Alienware                            | 1        | 0.19%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS All Series                            | 8        | 1.53%   |
| Unknown                                    | 8        | 1.53%   |
| Dell OptiPlex 7010                         | 6        | 1.15%   |
| MSI MS-7C37                                | 5        | 0.96%   |
| Gigabyte B550 GAMING X V2                  | 5        | 0.96%   |
| MSI MS-7C02                                | 4        | 0.77%   |
| MSI MS-7B89                                | 4        | 0.77%   |
| ASUS ROG STRIX B550-I GAMING               | 4        | 0.77%   |
| MSI MS-7C95                                | 3        | 0.57%   |
| MSI MS-7B79                                | 3        | 0.57%   |
| MSI MS-7B17                                | 3        | 0.57%   |
| MSI MS-7A38                                | 3        | 0.57%   |
| Itautec Infoway ST-4265                    | 3        | 0.57%   |
| HP Z800 Workstation                        | 3        | 0.57%   |
| Gigabyte X570 I AORUS PRO WIFI             | 3        | 0.57%   |
| Gigabyte B550M DS3H                        | 3        | 0.57%   |
| Gigabyte B450 I AORUS PRO WIFI             | 3        | 0.57%   |
| Dell OptiPlex 3020                         | 3        | 0.57%   |
| ASUS TUF Gaming X570-PLUS                  | 3        | 0.57%   |
| ASRock B450M Pro4                          | 3        | 0.57%   |
| Shenzhen Meigao Electronic Equipment UM690 | 2        | 0.38%   |
| MSI MS-7D54                                | 2        | 0.38%   |
| MSI MS-7D43                                | 2        | 0.38%   |
| MSI MS-7D25                                | 2        | 0.38%   |
| MSI MS-7D22                                | 2        | 0.38%   |
| MSI MS-7C96                                | 2        | 0.38%   |
| MSI MS-7C94                                | 2        | 0.38%   |
| MSI MS-7C84                                | 2        | 0.38%   |
| MSI MS-7C52                                | 2        | 0.38%   |
| MSI MS-7B85                                | 2        | 0.38%   |
| MSI MS-7B78                                | 2        | 0.38%   |
| MSI MS-7A39                                | 2        | 0.38%   |
| HP ProDesk 600 G1 SFF                      | 2        | 0.38%   |
| HP Compaq Elite 8300 SFF                   | 2        | 0.38%   |
| Gigabyte X570S AORUS ELITE AX              | 2        | 0.38%   |
| Gigabyte J1900M-D2P                        | 2        | 0.38%   |
| Gigabyte GA-880GM-UD2H                     | 2        | 0.38%   |
| Gigabyte GA-78LMT-USB3 6.0                 | 2        | 0.38%   |
| Gigabyte B550M DS3H AC                     | 2        | 0.38%   |
| Gigabyte B450M DS3H                        | 2        | 0.38%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS PRIME                                 | 39       | 7.47%   |
| ASUS ROG                                   | 32       | 6.13%   |
| Dell OptiPlex                              | 24       | 4.6%    |
| ASUS TUF                                   | 23       | 4.41%   |
| Lenovo ThinkCentre                         | 9        | 1.72%   |
| ASUS All                                   | 8        | 1.53%   |
| Unknown                                    | 8        | 1.53%   |
| HP EliteDesk                               | 7        | 1.34%   |
| HP Compaq                                  | 7        | 1.34%   |
| Gigabyte B550M                             | 7        | 1.34%   |
| Gigabyte B550                              | 7        | 1.34%   |
| Gigabyte X570                              | 6        | 1.15%   |
| MSI MS-7C37                                | 5        | 0.96%   |
| HP ProDesk                                 | 5        | 0.96%   |
| Gigabyte B450                              | 5        | 0.96%   |
| ASRock B450M                               | 5        | 0.96%   |
| MSI MS-7C02                                | 4        | 0.77%   |
| MSI MS-7B89                                | 4        | 0.77%   |
| Gigabyte B450M                             | 4        | 0.77%   |
| MSI MS-7C95                                | 3        | 0.57%   |
| MSI MS-7B79                                | 3        | 0.57%   |
| MSI MS-7B17                                | 3        | 0.57%   |
| MSI MS-7A38                                | 3        | 0.57%   |
| Itautec Infoway                            | 3        | 0.57%   |
| HP Z800                                    | 3        | 0.57%   |
| Gigabyte GA-78LMT-USB3                     | 3        | 0.57%   |
| Gigabyte B365M                             | 3        | 0.57%   |
| Gigabyte AB350-Gaming                      | 3        | 0.57%   |
| Dell Precision                             | 3        | 0.57%   |
| ASUS ProArt                                | 3        | 0.57%   |
| Shenzhen Meigao Electronic Equipment UM690 | 2        | 0.38%   |
| MSI MS-7D54                                | 2        | 0.38%   |
| MSI MS-7D43                                | 2        | 0.38%   |
| MSI MS-7D25                                | 2        | 0.38%   |
| MSI MS-7D22                                | 2        | 0.38%   |
| MSI MS-7C96                                | 2        | 0.38%   |
| MSI MS-7C94                                | 2        | 0.38%   |
| MSI MS-7C84                                | 2        | 0.38%   |
| MSI MS-7C52                                | 2        | 0.38%   |
| MSI MS-7B85                                | 2        | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 79       | 15.13%  |
| 2020    | 64       | 12.26%  |
| 2021    | 57       | 10.92%  |
| 2022    | 53       | 10.15%  |
| 2019    | 47       | 9%      |
| 2013    | 36       | 6.9%    |
| 2017    | 33       | 6.32%   |
| 2012    | 29       | 5.56%   |
| 2015    | 20       | 3.83%   |
| 2016    | 19       | 3.64%   |
| 2010    | 19       | 3.64%   |
| 2011    | 17       | 3.26%   |
| 2014    | 16       | 3.07%   |
| 2023    | 15       | 2.87%   |
| 2008    | 6        | 1.15%   |
| 2009    | 5        | 0.96%   |
| 2006    | 3        | 0.57%   |
| 2007    | 2        | 0.38%   |
| 2005    | 1        | 0.19%   |
| Unknown | 1        | 0.19%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 522      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 454      | 86.31%  |
| Enabled  | 72       | 13.69%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 522      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 166      | 31.26%  |
| 32.01-64.0      | 135      | 25.42%  |
| 4.01-8.0        | 62       | 11.68%  |
| 8.01-16.0       | 61       | 11.49%  |
| 64.01-256.0     | 53       | 9.98%   |
| 24.01-32.0      | 27       | 5.08%   |
| 3.01-4.0        | 22       | 4.14%   |
| 1.01-2.0        | 3        | 0.56%   |
| More than 256.0 | 1        | 0.19%   |
| 2.01-3.0        | 1        | 0.19%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 173      | 31.12%  |
| 2.01-3.0   | 140      | 25.18%  |
| 3.01-4.0   | 123      | 22.12%  |
| 1.01-2.0   | 48       | 8.63%   |
| 8.01-16.0  | 47       | 8.45%   |
| 0.51-1.0   | 12       | 2.16%   |
| 16.01-24.0 | 9        | 1.62%   |
| 32.01-64.0 | 4        | 0.72%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 187      | 34.89%  |
| 1      | 155      | 28.92%  |
| 3      | 97       | 18.1%   |
| 4      | 58       | 10.82%  |
| 5      | 20       | 3.73%   |
| 6      | 12       | 2.24%   |
| 7      | 3        | 0.56%   |
| 11     | 1        | 0.19%   |
| 10     | 1        | 0.19%   |
| 8      | 1        | 0.19%   |
| 0      | 1        | 0.19%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 375      | 71.56%  |
| Yes       | 149      | 28.44%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 517      | 98.85%  |
| No        | 6        | 1.15%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 286      | 54.68%  |
| No        | 237      | 45.32%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 274      | 52.39%  |
| Yes       | 249      | 47.61%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 105      | 20.08%  |
| Brazil      | 43       | 8.22%   |
| Russia      | 34       | 6.5%    |
| Australia   | 34       | 6.5%    |
| Germany     | 30       | 5.74%   |
| Canada      | 27       | 5.16%   |
| Italy       | 19       | 3.63%   |
| UK          | 15       | 2.87%   |
| France      | 15       | 2.87%   |
| Netherlands | 14       | 2.68%   |
| Spain       | 12       | 2.29%   |
| Poland      | 12       | 2.29%   |
| Mexico      | 11       | 2.1%    |
| Sweden      | 10       | 1.91%   |
| Colombia    | 7        | 1.34%   |
| Austria     | 7        | 1.34%   |
| Argentina   | 7        | 1.34%   |
| India       | 6        | 1.15%   |
| Hungary     | 6        | 1.15%   |
| Turkey      | 5        | 0.96%   |
| Thailand    | 5        | 0.96%   |
| Serbia      | 5        | 0.96%   |
| Norway      | 5        | 0.96%   |
| Belarus     | 5        | 0.96%   |
| Switzerland | 4        | 0.76%   |
| Portugal    | 4        | 0.76%   |
| Indonesia   | 4        | 0.76%   |
| Denmark     | 4        | 0.76%   |
| Belgium     | 4        | 0.76%   |
| Taiwan      | 3        | 0.57%   |
| Singapore   | 3        | 0.57%   |
| New Zealand | 3        | 0.57%   |
| Ireland     | 3        | 0.57%   |
| Finland     | 3        | 0.57%   |
| Chile       | 3        | 0.57%   |
| Bulgaria    | 3        | 0.57%   |
| Venezuela   | 2        | 0.38%   |
| Ukraine     | 2        | 0.38%   |
| Romania     | 2        | 0.38%   |
| Philippines | 2        | 0.38%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Sydney                 | 21       | 3.95%   |
| Moscow                 | 8        | 1.5%    |
| Vienna                 | 6        | 1.13%   |
| St Petersburg          | 5        | 0.94%   |
| Seattle                | 5        | 0.94%   |
| Palmas                 | 5        | 0.94%   |
| Minsk                  | 5        | 0.94%   |
| Warsaw                 | 4        | 0.75%   |
| Sao Paulo              | 4        | 0.75%   |
| Rio de Janeiro         | 4        | 0.75%   |
| Ottawa                 | 4        | 0.75%   |
| Los Angeles            | 4        | 0.75%   |
| Brisbane               | 4        | 0.75%   |
| Belgrade               | 4        | 0.75%   |
| Amsterdam              | 4        | 0.75%   |
| Winnipeg               | 3        | 0.56%   |
| Toronto                | 3        | 0.56%   |
| Singapore              | 3        | 0.56%   |
| Santiago               | 3        | 0.56%   |
| Rochester              | 3        | 0.56%   |
| Porto Alegre           | 3        | 0.56%   |
| Milan                  | 3        | 0.56%   |
| Mexico City            | 3        | 0.56%   |
| Melbourne              | 3        | 0.56%   |
| Istanbul               | 3        | 0.56%   |
| Helsinki               | 3        | 0.56%   |
| Budapest               | 3        | 0.56%   |
| Brussels               | 3        | 0.56%   |
| Brasília              | 3        | 0.56%   |
| Bangkok                | 3        | 0.56%   |
| Alliston               | 3        | 0.56%   |
| Adelaide               | 3        | 0.56%   |
| Woodstock              | 2        | 0.38%   |
| White Rock             | 2        | 0.38%   |
| Victoria               | 2        | 0.38%   |
| Verona                 | 2        | 0.38%   |
| The Hague              | 2        | 0.38%   |
| Tampa                  | 2        | 0.38%   |
| South Bend             | 2        | 0.38%   |
| Santiago de Compostela | 2        | 0.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| Samsung Electronics          | 195      | 335    | 19.12%  |
| Seagate                      | 142      | 192    | 13.92%  |
| WDC                          | 129      | 190    | 12.65%  |
| SanDisk                      | 71       | 89     | 6.96%   |
| Kingston                     | 65       | 73     | 6.37%   |
| Crucial                      | 54       | 75     | 5.29%   |
| Toshiba                      | 52       | 62     | 5.1%    |
| Intel                        | 26       | 36     | 2.55%   |
| Phison Electronics           | 22       | 36     | 2.16%   |
| Hitachi                      | 19       | 28     | 1.86%   |
| A-DATA Technology            | 19       | 22     | 1.86%   |
| Micron/Crucial Technology    | 17       | 18     | 1.67%   |
| Silicon Motion               | 14       | 17     | 1.37%   |
| Patriot                      | 10       | 14     | 0.98%   |
| Kingston Technology Company  | 10       | 11     | 0.98%   |
| SPCC                         | 8        | 9      | 0.78%   |
| China                        | 8        | 13     | 0.78%   |
| SK hynix                     | 7        | 9      | 0.69%   |
| PNY                          | 7        | 10     | 0.69%   |
| Netac                        | 7        | 7      | 0.69%   |
| Micron Technology            | 7        | 7      | 0.69%   |
| MAXIO Technology (Hangzhou)  | 7        | 9      | 0.69%   |
| ADATA Technology             | 7        | 7      | 0.69%   |
| Unknown                      | 5        | 6      | 0.49%   |
| Realtek Semiconductor        | 5        | 9      | 0.49%   |
| KingSpec                     | 5        | 5      | 0.49%   |
| Intenso                      | 5        | 5      | 0.49%   |
| HGST                         | 5        | 5      | 0.49%   |
| OCZ                          | 4        | 6      | 0.39%   |
| AMD                          | 4        | 4      | 0.39%   |
| Transcend                    | 3        | 3      | 0.29%   |
| Seagate Technology           | 3        | 4      | 0.29%   |
| Maxtor                       | 3        | 3      | 0.29%   |
| Lexar                        | 3        | 3      | 0.29%   |
| JMicron Technology           | 3        | 3      | 0.29%   |
| ASMT                         | 3        | 4      | 0.29%   |
| Unknown                      | 3        | 5      | 0.29%   |
| TO Exter                     | 2        | 2      | 0.2%    |
| Team                         | 2        | 2      | 0.2%    |
| Shenzhen Longsys Electronics | 2        | 2      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB   | 46       | 3.93%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 36       | 3.07%   |
| Crucial CT500MX500SSD1 500GB                          | 15       | 1.28%   |
| Samsung SSD 850 EVO 250GB                             | 14       | 1.2%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 500GB | 12       | 1.02%   |
| Samsung SSD 860 EVO 500GB                             | 12       | 1.02%   |
| Samsung SSD 860 EVO 1TB                               | 12       | 1.02%   |
| Seagate ST1000DM010-2EP102 1TB                        | 11       | 0.94%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB   | 11       | 0.94%   |
| Phison E12 NVMe Controller 2TB                        | 11       | 0.94%   |
| Kingston SA400S37120G 120GB SSD                       | 10       | 0.85%   |
| Toshiba DT01ACA100 1TB                                | 9        | 0.77%   |
| Seagate ST2000DM006-2DM164 2TB                        | 9        | 0.77%   |
| Seagate ST1000DM003-1CH162 1TB                        | 9        | 0.77%   |
| Samsung SSD 980 1TB                                   | 9        | 0.77%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                   | 9        | 0.77%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                      | 8        | 0.68%   |
| Seagate ST500DM002-1BD142 500GB                       | 8        | 0.68%   |
| Samsung SSD 850 EVO 500GB                             | 8        | 0.68%   |
| Kingston SA400S37240G 240GB SSD                       | 8        | 0.68%   |
| Seagate ST2000DM008-2FR102 2TB                        | 7        | 0.6%    |
| Seagate ST2000DM001-1ER164 2TB                        | 7        | 0.6%    |
| Sandisk WD Blue SN550 NVMe SSD 250GB                  | 7        | 0.6%    |
| Samsung SSD 870 EVO 1TB                               | 7        | 0.6%    |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 256GB    | 7        | 0.6%    |
| Crucial CT240BX500SSD1 240GB                          | 7        | 0.6%    |
| Crucial CT1000MX500SSD1 1TB                           | 7        | 0.6%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 6        | 0.51%   |
| Toshiba MQ01ABD100 1TB                                | 6        | 0.51%   |
| Seagate ST31000524AS 1TB                              | 6        | 0.51%   |
| Phison E16 PCIe4 NVMe Controller 1TB                  | 6        | 0.51%   |
| Kingston SA400S37480G 480GB SSD                       | 6        | 0.51%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 5        | 0.43%   |
| Toshiba DT01ACA050 500GB                              | 5        | 0.43%   |
| Seagate ST1000DM003-1ER162 1TB                        | 5        | 0.43%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB     | 5        | 0.43%   |
| Samsung SSD 870 QVO 2TB                               | 5        | 0.43%   |
| Samsung SSD 860 EVO 250GB                             | 5        | 0.43%   |
| Kingston SV300S37A120G 120GB SSD                      | 5        | 0.43%   |
| Crucial CT2000MX500SSD1 2TB                           | 5        | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 136      | 182    | 40.6%   |
| WDC                 | 107      | 154    | 31.94%  |
| Toshiba             | 44       | 49     | 13.13%  |
| Hitachi             | 19       | 28     | 5.67%   |
| Samsung Electronics | 13       | 15     | 3.88%   |
| HGST                | 5        | 5      | 1.49%   |
| Unknown             | 3        | 3      | 0.9%    |
| QNAP                | 2        | 2      | 0.6%    |
| Maxtor              | 2        | 2      | 0.6%    |
| JMicron Technology  | 2        | 2      | 0.6%    |
| USB                 | 1        | 1      | 0.3%    |
| ASMT                | 1        | 2      | 0.3%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 103      | 157    | 25.43%  |
| Crucial             | 53       | 72     | 13.09%  |
| Kingston            | 45       | 49     | 11.11%  |
| WDC                 | 30       | 34     | 7.41%   |
| SanDisk             | 26       | 33     | 6.42%   |
| A-DATA Technology   | 19       | 22     | 4.69%   |
| Intel               | 16       | 24     | 3.95%   |
| Patriot             | 10       | 14     | 2.47%   |
| SPCC                | 8        | 9      | 1.98%   |
| China               | 8        | 13     | 1.98%   |
| PNY                 | 7        | 10     | 1.73%   |
| Toshiba             | 5        | 9      | 1.23%   |
| Micron Technology   | 5        | 5      | 1.23%   |
| KingSpec            | 5        | 5      | 1.23%   |
| OCZ                 | 4        | 6      | 0.99%   |
| AMD                 | 4        | 4      | 0.99%   |
| Transcend           | 3        | 3      | 0.74%   |
| Netac               | 3        | 3      | 0.74%   |
| Lexar               | 3        | 3      | 0.74%   |
| Intenso             | 3        | 3      | 0.74%   |
| TO Exter            | 2        | 2      | 0.49%   |
| Team                | 2        | 2      | 0.49%   |
| NGFF                | 2        | 2      | 0.49%   |
| Mushkin             | 2        | 2      | 0.49%   |
| LITEONIT            | 2        | 2      | 0.49%   |
| GOODRAM             | 2        | 3      | 0.49%   |
| Fanxiang            | 2        | 2      | 0.49%   |
| Acer                | 2        | 5      | 0.49%   |
| Unknown             | 2        | 4      | 0.49%   |
| ZOTAC               | 1        | 1      | 0.25%   |
| XrayDisk            | 1        | 1      | 0.25%   |
| TAMMUZ              | 1        | 1      | 0.25%   |
| Supersonic          | 1        | 2      | 0.25%   |
| SK hynix            | 1        | 1      | 0.25%   |
| Seagate             | 1        | 1      | 0.25%   |
| Ramaxel Technology  | 1        | 1      | 0.25%   |
| Quaroni             | 1        | 1      | 0.25%   |
| Phison              | 1        | 1      | 0.25%   |
| Palit               | 1        | 1      | 0.25%   |
| MSI                 | 1        | 1      | 0.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 331      | 533    | 36.98%  |
| HDD     | 274      | 445    | 30.61%  |
| NVMe    | 270      | 406    | 30.17%  |
| Unknown | 19       | 21     | 2.12%   |
| MMC     | 1        | 1      | 0.11%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 436      | 955    | 58.6%   |
| NVMe | 268      | 403    | 36.02%  |
| SAS  | 39       | 47     | 5.24%   |
| MMC  | 1        | 1      | 0.13%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 297      | 498    | 46.26%  |
| 0.51-1.0   | 198      | 276    | 30.84%  |
| 1.01-2.0   | 89       | 116    | 13.86%  |
| 3.01-4.0   | 28       | 36     | 4.36%   |
| 4.01-10.0  | 19       | 38     | 2.96%   |
| 2.01-3.0   | 9        | 9      | 1.4%    |
| 10.01-20.0 | 2        | 5      | 0.31%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 115      | 21.38%  |
| 501-1000       | 100      | 18.59%  |
| More than 3000 | 74       | 13.75%  |
| 251-500        | 74       | 13.75%  |
| 101-250        | 64       | 11.9%   |
| 2001-3000      | 44       | 8.18%   |
| 1-20           | 23       | 4.28%   |
| Unknown        | 18       | 3.35%   |
| 51-100         | 15       | 2.79%   |
| 21-50          | 10       | 1.86%   |
| 0              | 1        | 0.19%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 123      | 22.53%  |
| 21-50          | 95       | 17.4%   |
| 101-250        | 63       | 11.54%  |
| 251-500        | 62       | 11.36%  |
| 501-1000       | 57       | 10.44%  |
| 51-100         | 56       | 10.26%  |
| 1001-2000      | 39       | 7.14%   |
| Unknown        | 18       | 3.3%    |
| More than 3000 | 16       | 2.93%   |
| 2001-3000      | 16       | 2.93%   |
| 0              | 1        | 0.18%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                          | Desktops | Drives | Percent |
|----------------------------------------------------------------|----------|--------|---------|
| Toshiba MQ01ABD100 1TB                                         | 2        | 2      | 3.7%    |
| Seagate ST500DM002-1BD142 500GB                                | 2        | 2      | 3.7%    |
| Seagate ST31000524AS 1TB                                       | 2        | 2      | 3.7%    |
| Intel SSDSC2CT120A3 120GB                                      | 2        | 4      | 3.7%    |
| Crucial CT120M500SSD1 120GB                                    | 2        | 5      | 3.7%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                               | 1        | 1      | 1.85%   |
| WDC WDS100T2G0A-00JH30 1TB SSD                                 | 1        | 1      | 1.85%   |
| WDC WD5000AVCS-632DY1 500GB                                    | 1        | 1      | 1.85%   |
| WDC WD5000AADS-00S9B0 500GB                                    | 1        | 1      | 1.85%   |
| WDC WD2500BEVT-80A23T0 250GB                                   | 1        | 1      | 1.85%   |
| WDC WD20EZRX-00D8PB0 2TB                                       | 1        | 1      | 1.85%   |
| WDC WD10JPVT-60A1YT0 1TB                                       | 1        | 1      | 1.85%   |
| WDC WD10EZRZ-00HTKB0 1TB                                       | 1        | 1      | 1.85%   |
| WDC WD1002FAEX-00Y9A0 1TB                                      | 1        | 1      | 1.85%   |
| Toshiba MQ02ABD100H 1TB                                        | 1        | 1      | 1.85%   |
| SPCC Solid State Disk 128GB                                    | 1        | 1      | 1.85%   |
| Seagate ST9250827AS 250GB                                      | 1        | 1      | 1.85%   |
| Seagate ST9160412AS 160GB                                      | 1        | 1      | 1.85%   |
| Seagate ST3750528AS 752GB                                      | 1        | 1      | 1.85%   |
| Seagate ST3500630NS 500GB                                      | 1        | 1      | 1.85%   |
| Seagate ST3500418AS 500GB                                      | 1        | 2      | 1.85%   |
| Seagate ST3320613AS 320GB                                      | 1        | 1      | 1.85%   |
| Seagate ST2000VX000-1CU164 2TB                                 | 1        | 1      | 1.85%   |
| Seagate ST2000DM008-2FR102 2TB                                 | 1        | 1      | 1.85%   |
| Seagate ST1000LX015-1U7172 1TB                                 | 1        | 1      | 1.85%   |
| Seagate ST1000DX002-2DV162 1TB                                 | 1        | 1      | 1.85%   |
| SanDisk SSD PLUS 480GB                                         | 1        | 1      | 1.85%   |
| SanDisk SSD PLUS 120 GB                                        | 1        | 1      | 1.85%   |
| SanDisk SD8SBAT256G1122 256GB SSD                              | 1        | 1      | 1.85%   |
| Samsung Electronics SSD 870 EVO 250GB                          | 1        | 1      | 1.85%   |
| Samsung Electronics SSD 870 EVO 1TB                            | 1        | 1      | 1.85%   |
| Samsung Electronics SSD 850 EVO 250GB                          | 1        | 2      | 1.85%   |
| Samsung Electronics SSD 840 EVO 250GB                          | 1        | 1      | 1.85%   |
| Samsung Electronics NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 1        | 1      | 1.85%   |
| Samsung Electronics HD322GJ 320GB                              | 1        | 2      | 1.85%   |
| Micron Technology MTFDDAK128MAM-1J1 128GB SSD                  | 1        | 1      | 1.85%   |
| Maxtor 6Y080L0 82GB                                            | 1        | 1      | 1.85%   |
| MAXIO Technology (Hangzhou) NVMe SSD Controller MAP1202 256GB  | 1        | 1      | 1.85%   |
| LITEONIT LMT-256M3M 256GB SSD                                  | 1        | 1      | 1.85%   |
| Kingston SHPM2280P2 240G SSD                                   | 1        | 1      | 1.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 13       | 15     | 25.49%  |
| WDC                         | 7        | 9      | 13.73%  |
| Samsung Electronics         | 6        | 8      | 11.76%  |
| Intel                       | 4        | 6      | 7.84%   |
| Toshiba                     | 3        | 3      | 5.88%   |
| SanDisk                     | 3        | 3      | 5.88%   |
| Kingston                    | 3        | 4      | 5.88%   |
| Crucial                     | 2        | 5      | 3.92%   |
| A-DATA Technology           | 2        | 2      | 3.92%   |
| SPCC                        | 1        | 1      | 1.96%   |
| Micron Technology           | 1        | 1      | 1.96%   |
| Maxtor                      | 1        | 1      | 1.96%   |
| MAXIO Technology (Hangzhou) | 1        | 1      | 1.96%   |
| LITEONIT                    | 1        | 1      | 1.96%   |
| Intenso                     | 1        | 1      | 1.96%   |
| HPE                         | 1        | 1      | 1.96%   |
| Hitachi                     | 1        | 1      | 1.96%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 13       | 15     | 52%     |
| WDC                 | 6        | 7      | 24%     |
| Toshiba             | 3        | 3      | 12%     |
| Samsung Electronics | 1        | 2      | 4%      |
| Maxtor              | 1        | 1      | 4%      |
| Hitachi             | 1        | 1      | 4%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 25       | 29     | 50%     |
| SSD  | 23       | 32     | 46%     |
| NVMe | 2        | 2      | 4%      |

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
| Detected | 353      | 897    | 61.28%  |
| Works    | 177      | 446    | 30.73%  |
| Malfunc  | 46       | 63     | 7.99%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 288      | 32.88%  |
| AMD                          | 228      | 26.03%  |
| Samsung Electronics          | 116      | 13.24%  |
| SanDisk                      | 49       | 5.59%   |
| Kingston Technology Company  | 32       | 3.65%   |
| ASMedia Technology           | 30       | 3.42%   |
| Phison Electronics           | 23       | 2.63%   |
| Micron/Crucial Technology    | 18       | 2.05%   |
| Silicon Motion               | 14       | 1.6%    |
| Marvell Technology Group     | 14       | 1.6%    |
| MAXIO Technology (Hangzhou)  | 7        | 0.8%    |
| ADATA Technology             | 7        | 0.8%    |
| SK hynix                     | 6        | 0.68%   |
| Seagate Technology           | 6        | 0.68%   |
| JMicron Technology           | 6        | 0.68%   |
| Realtek Semiconductor        | 5        | 0.57%   |
| Netac Technology             | 4        | 0.46%   |
| Toshiba America Info Systems | 3        | 0.34%   |
| LSI Logic / Symbios Logic    | 3        | 0.34%   |
| VIA Technologies             | 2        | 0.23%   |
| Silicon Image                | 2        | 0.23%   |
| Shenzhen Longsys Electronics | 2        | 0.23%   |
| Micron Technology            | 2        | 0.23%   |
| Adaptec                      | 2        | 0.23%   |
| Union Memory (Shenzhen)      | 1        | 0.11%   |
| ULi Electronics              | 1        | 0.11%   |
| PMC-Sierra                   | 1        | 0.11%   |
| Nvidia                       | 1        | 0.11%   |
| KIOXIA                       | 1        | 0.11%   |
| INNOGRIT                     | 1        | 0.11%   |
| Broadcom / LSI               | 1        | 0.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 126      | 12.54%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 52       | 5.17%   |
| AMD 500 Series Chipset SATA Controller                                         | 52       | 5.17%   |
| AMD 400 Series Chipset SATA Controller                                         | 48       | 4.78%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 40       | 3.98%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 31       | 3.08%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 28       | 2.79%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 28       | 2.79%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 28       | 2.79%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 28       | 2.79%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 27       | 2.69%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 27       | 2.69%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 18       | 1.79%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 17       | 1.69%   |
| Samsung NVMe SSD Controller 980                                                | 16       | 1.59%   |
| Intel SATA Controller [RAID mode]                                              | 16       | 1.59%   |
| Intel Volume Management Device NVMe RAID Controller                            | 13       | 1.29%   |
| AMD 300 Series Chipset SATA Controller                                         | 13       | 1.29%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 12       | 1.19%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 12       | 1.19%   |
| AMD FCH SATA Controller D                                                      | 12       | 1.19%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 11       | 1.09%   |
| Phison E12 NVMe Controller                                                     | 11       | 1.09%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 11       | 1.09%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 10       | 1%      |
| Kingston Company KC3000/Renegade NVMe SSD                                      | 10       | 1%      |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 10       | 1%      |
| Kingston Company Company Non-Volatile memory controller                        | 8        | 0.8%    |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 7        | 0.7%    |
| Phison E16 PCIe4 NVMe Controller                                               | 7        | 0.7%    |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                   | 7        | 0.7%    |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 7        | 0.7%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 7        | 0.7%    |
| Sandisk Western Digital WD Black SN850X NVMe SSD                               | 6        | 0.6%    |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 6        | 0.6%    |
| Kingston Company NVMe Controller                                               | 6        | 0.6%    |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 5        | 0.5%    |
| SanDisk WD Green SN350 NVMe SSD 240GB (DRAM-less)                              | 5        | 0.5%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 5        | 0.5%    |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 5        | 0.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 476      | 57.07%  |
| NVMe | 268      | 32.13%  |
| RAID | 42       | 5.04%   |
| IDE  | 41       | 4.92%   |
| SCSI | 4        | 0.48%   |
| SAS  | 3        | 0.36%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 287      | 54.98%  |
| AMD                      | 234      | 44.83%  |
| PowerNV C1P9S01 REV 1.01 | 1        | 0.19%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 5600X 6-Core Processor          | 20       | 3.83%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 12       | 2.3%    |
| AMD Ryzen 5 3600 6-Core Processor           | 12       | 2.3%    |
| AMD Ryzen 5 2600 Six-Core Processor         | 11       | 2.11%   |
| AMD Ryzen 9 7950X 16-Core Processor         | 10       | 1.92%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 10       | 1.92%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 9        | 1.72%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 9        | 1.72%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 9        | 1.72%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 8        | 1.53%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 7        | 1.34%   |
| AMD Ryzen 7 5800X3D 8-Core Processor        | 7        | 1.34%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 7        | 1.34%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 6        | 1.15%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 6        | 1.15%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 5        | 0.96%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 5        | 0.96%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 5        | 0.96%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 5        | 0.96%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 5        | 0.96%   |
| Intel Core i3-9100F CPU @ 3.60GHz           | 5        | 0.96%   |
| Intel 12th Gen Core i5-12600K               | 5        | 0.96%   |
| AMD Ryzen 7 5700X 8-Core Processor          | 5        | 0.96%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 5        | 0.96%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 5        | 0.96%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 4        | 0.77%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 4        | 0.77%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 4        | 0.77%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 4        | 0.77%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 4        | 0.77%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 4        | 0.77%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 4        | 0.77%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 4        | 0.77%   |
| Intel 12th Gen Core i5-12400F               | 4        | 0.77%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 4        | 0.77%   |
| AMD Ryzen 7 7700X 8-Core Processor          | 4        | 0.77%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 4        | 0.77%   |
| AMD FX-6300 Six-Core Processor              | 4        | 0.77%   |
| Intel Xeon CPU X5675 @ 3.07GHz              | 3        | 0.57%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 83       | 15.9%   |
| AMD Ryzen 5             | 80       | 15.33%  |
| Intel Core i7           | 69       | 13.22%  |
| AMD Ryzen 7             | 56       | 10.73%  |
| AMD Ryzen 9             | 45       | 8.62%   |
| Other                   | 44       | 8.43%   |
| Intel Xeon              | 28       | 5.36%   |
| Intel Core i3           | 24       | 4.6%    |
| AMD FX                  | 13       | 2.49%   |
| Intel Celeron           | 11       | 2.11%   |
| Intel Core i9           | 9        | 1.72%   |
| Intel Core 2 Quad       | 7        | 1.34%   |
| AMD Ryzen 3             | 6        | 1.15%   |
| AMD Phenom II X4        | 6        | 1.15%   |
| AMD Ryzen Threadripper  | 5        | 0.96%   |
| Intel Pentium           | 4        | 0.77%   |
| Intel Core 2 Duo        | 3        | 0.57%   |
| AMD Athlon              | 3        | 0.57%   |
| AMD A8                  | 3        | 0.57%   |
| Intel Pentium Gold      | 2        | 0.38%   |
| Intel Atom              | 2        | 0.38%   |
| AMD Ryzen 5 PRO         | 2        | 0.38%   |
| AMD Phenom II X2        | 2        | 0.38%   |
| AMD A4                  | 2        | 0.38%   |
| AMD A10                 | 2        | 0.38%   |
| Intel Pentium Dual-Core | 1        | 0.19%   |
| Intel Pentium Dual      | 1        | 0.19%   |
| Intel Genuine           | 1        | 0.19%   |
| AMD Turion 64 X2 Mobile | 1        | 0.19%   |
| AMD Sempron             | 1        | 0.19%   |
| AMD Phenom II X6        | 1        | 0.19%   |
| AMD Opteron             | 1        | 0.19%   |
| AMD E2                  | 1        | 0.19%   |
| AMD Athlon II X2        | 1        | 0.19%   |
| AMD Athlon 64 X2        | 1        | 0.19%   |
| AMD A6                  | 1        | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 173      | 33.14%  |
| 6      | 127      | 24.33%  |
| 8      | 84       | 16.09%  |
| 2      | 53       | 10.15%  |
| 12     | 31       | 5.94%   |
| 16     | 30       | 5.75%   |
| 10     | 10       | 1.92%   |
| 3      | 5        | 0.96%   |
| 14     | 3        | 0.57%   |
| 24     | 2        | 0.38%   |
| 1      | 2        | 0.38%   |
| 32     | 1        | 0.19%   |
| 18     | 1        | 0.19%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 516      | 98.85%  |
| 2      | 6        | 1.15%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 371      | 71.07%  |
| 1      | 150      | 28.74%  |
| 4      | 1        | 0.19%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 521      | 99.81%  |
| Unknown        | 1        | 0.19%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 301      | 57.44%  |
| 0x0a20120a | 29       | 5.53%   |
| 0x08701021 | 25       | 4.77%   |
| 0x0a601203 | 20       | 3.82%   |
| 0x0800820d | 18       | 3.44%   |
| 0x0a50000d | 13       | 2.48%   |
| 0x0a201016 | 13       | 2.48%   |
| 0x08108109 | 11       | 2.1%    |
| 0x08701030 | 9        | 1.72%   |
| 0x0a50000c | 8        | 1.53%   |
| 0x06000822 | 8        | 1.53%   |
| 0x0a201025 | 6        | 1.15%   |
| 0x010000c8 | 6        | 1.15%   |
| 0x0a404102 | 3        | 0.57%   |
| 0x0a201205 | 3        | 0.57%   |
| 0x0a201009 | 3        | 0.57%   |
| 0x08701013 | 3        | 0.57%   |
| 0x08600106 | 3        | 0.57%   |
| 0x0800820c | 3        | 0.57%   |
| 0x08001138 | 3        | 0.57%   |
| 0x08001137 | 3        | 0.57%   |
| 0x0600611a | 3        | 0.57%   |
| 0x0a601201 | 2        | 0.38%   |
| 0x0a201204 | 2        | 0.38%   |
| 0x08101016 | 2        | 0.38%   |
| 0x06001119 | 2        | 0.38%   |
| 0x06000629 | 2        | 0.38%   |
| 0x010000bf | 2        | 0.38%   |
| 0x010000b6 | 2        | 0.38%   |
| 0x906ea    | 1        | 0.19%   |
| 0x0a201005 | 1        | 0.19%   |
| 0x0a008203 | 1        | 0.19%   |
| 0x08108102 | 1        | 0.19%   |
| 0x08001129 | 1        | 0.19%   |
| 0x08001126 | 1        | 0.19%   |
| 0x0700010f | 1        | 0.19%   |
| 0x0700010b | 1        | 0.19%   |
| 0x06003106 | 1        | 0.19%   |
| 0x0600110f | 1        | 0.19%   |
| 0x06000852 | 1        | 0.19%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 84       | 16.09%  |
| KabyLake         | 69       | 13.22%  |
| Zen 2            | 41       | 7.85%   |
| Haswell          | 39       | 7.47%   |
| Zen+             | 34       | 6.51%   |
| IvyBridge        | 34       | 6.51%   |
| Alderlake Hybrid | 32       | 6.13%   |
| Unknown          | 29       | 5.56%   |
| Skylake          | 25       | 4.79%   |
| CometLake        | 19       | 3.64%   |
| SandyBridge      | 16       | 3.07%   |
| Piledriver       | 13       | 2.49%   |
| Zen              | 11       | 2.11%   |
| Westmere         | 11       | 2.11%   |
| K10              | 10       | 1.92%   |
| Penryn           | 9        | 1.72%   |
| Icelake          | 9        | 1.72%   |
| Broadwell        | 6        | 1.15%   |
| Core             | 4        | 0.77%   |
| Tremont          | 3        | 0.57%   |
| Silvermont       | 3        | 0.57%   |
| K8 Hammer        | 3        | 0.57%   |
| Excavator        | 3        | 0.57%   |
| Bulldozer        | 3        | 0.57%   |
| Bonnell          | 3        | 0.57%   |
| K10 Llano        | 2        | 0.38%   |
| Jaguar           | 2        | 0.38%   |
| Gracemont        | 2        | 0.38%   |
| TigerLake        | 1        | 0.19%   |
| Steamroller      | 1        | 0.19%   |
| Nehalem          | 1        | 0.19%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| AMD                        | 232      | 40.63%  |
| Nvidia                     | 202      | 35.38%  |
| Intel                      | 133      | 23.29%  |
| Matrox Electronics Systems | 2        | 0.35%   |
| VIA Technologies           | 1        | 0.18%   |
| ASPEED Technology          | 1        | 0.18%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 35       | 5.86%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 26       | 4.36%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 19       | 3.18%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 18       | 3.02%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 17       | 2.85%   |
| AMD Raphael                                                                 | 17       | 2.85%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 17       | 2.85%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 16       | 2.68%   |
| Intel HD Graphics 530                                                       | 15       | 2.51%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 15       | 2.51%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 15       | 2.51%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 11       | 1.84%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX]                                    | 11       | 1.84%   |
| Nvidia GT218 [GeForce 210]                                                  | 9        | 1.51%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 9        | 1.51%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 9        | 1.51%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 8        | 1.34%   |
| Intel HD Graphics 630                                                       | 8        | 1.34%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 7        | 1.17%   |
| Intel AlderLake-S GT1                                                       | 7        | 1.17%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 6        | 1.01%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 6        | 1.01%   |
| Nvidia GK208B [GeForce GT 730]                                              | 6        | 1.01%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 6        | 1.01%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 5        | 0.84%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 5        | 0.84%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 5        | 0.84%   |
| Nvidia GK208B [GeForce GT 710]                                              | 5        | 0.84%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                   | 5        | 0.84%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5        | 0.84%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 5        | 0.84%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 5        | 0.84%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 4        | 0.67%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 4        | 0.67%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 4        | 0.67%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 4        | 0.67%   |
| Nvidia GA104 [GeForce RTX 3070 Ti]                                          | 4        | 0.67%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                              | 4        | 0.67%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                  | 4        | 0.67%   |
| Intel JasperLake [UHD Graphics]                                             | 4        | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x AMD         | 195      | 37.14%  |
| 1 x Nvidia      | 170      | 32.38%  |
| 1 x Intel       | 96       | 18.29%  |
| 2 x AMD         | 18       | 3.43%   |
| Intel + Nvidia  | 15       | 2.86%   |
| AMD + Nvidia    | 11       | 2.1%    |
| Intel + AMD     | 9        | 1.71%   |
| 2 x Nvidia      | 5        | 0.95%   |
| 2 x Intel       | 2        | 0.38%   |
| 1 x VIA         | 1        | 0.19%   |
| Nvidia + Matrox | 1        | 0.19%   |
| 1 x Matrox      | 1        | 0.19%   |
| 1 x ASPEED      | 1        | 0.19%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 414      | 78.41%  |
| Proprietary | 94       | 17.8%   |
| Unknown     | 20       | 3.79%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 173      | 32.7%   |
| 7.01-8.0   | 106      | 20.04%  |
| 3.01-4.0   | 55       | 10.4%   |
| 1.01-2.0   | 53       | 10.02%  |
| 8.01-16.0  | 45       | 8.51%   |
| 0.51-1.0   | 36       | 6.81%   |
| 0.01-0.5   | 34       | 6.43%   |
| 5.01-6.0   | 12       | 2.27%   |
| 16.01-24.0 | 10       | 1.89%   |
| 2.01-3.0   | 5        | 0.95%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 94       | 15.91%  |
| Goldstar             | 90       | 15.23%  |
| Dell                 | 87       | 14.72%  |
| Hewlett-Packard      | 34       | 5.75%   |
| Acer                 | 31       | 5.25%   |
| Philips              | 28       | 4.74%   |
| AOC                  | 25       | 4.23%   |
| BenQ                 | 20       | 3.38%   |
| ASUSTek Computer     | 18       | 3.05%   |
| Ancor Communications | 18       | 3.05%   |
| Lenovo               | 14       | 2.37%   |
| ViewSonic            | 9        | 1.52%   |
| Gigabyte Technology  | 9        | 1.52%   |
| Sceptre Tech         | 7        | 1.18%   |
| MSI                  | 7        | 1.18%   |
| Iiyama               | 7        | 1.18%   |
| Unknown              | 6        | 1.02%   |
| Sony                 | 6        | 1.02%   |
| Mi                   | 6        | 1.02%   |
| Fujitsu Siemens      | 4        | 0.68%   |
| Toshiba              | 3        | 0.51%   |
| Eizo                 | 3        | 0.51%   |
| Belinea              | 3        | 0.51%   |
| Vestel Elektronik    | 2        | 0.34%   |
| Unknown (XXX)        | 2        | 0.34%   |
| TCT                  | 2        | 0.34%   |
| STD                  | 2        | 0.34%   |
| SGT                  | 2        | 0.34%   |
| LG Electronics       | 2        | 0.34%   |
| HUAWEI               | 2        | 0.34%   |
| Hitachi              | 2        | 0.34%   |
| GDH                  | 2        | 0.34%   |
| Denver               | 2        | 0.34%   |
| CHO                  | 2        | 0.34%   |
| ___                  | 1        | 0.17%   |
| Yamaha               | 1        | 0.17%   |
| Wacom                | 1        | 0.17%   |
| Vizio                | 1        | 0.17%   |
| Valve                | 1        | 0.17%   |
| UGD                  | 1        | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 7        | 1.11%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                  | 5        | 0.8%    |
| Dell S3220DGF DELD0F4 2560x1440 697x392mm 31.5-inch                    | 5        | 0.8%    |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 4        | 0.64%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 4        | 0.64%   |
| Goldstar ULTRAGEAR GSM5BD3 2560x1440 697x392mm 31.5-inch               | 4        | 0.64%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 597x336mm 27.0-inch                 | 4        | 0.64%   |
| Samsung Electronics LC32G7xT SAM7058 2560x1440 698x393mm 31.5-inch     | 3        | 0.48%   |
| Samsung Electronics LC27G5xT SAM7079 2560x1440 597x336mm 27.0-inch     | 3        | 0.48%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 3        | 0.48%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch           | 3        | 0.48%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                  | 3        | 0.48%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                 | 3        | 0.48%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch         | 3        | 0.48%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                      | 3        | 0.48%   |
| AOC Q27G2SG4 AOC2702 2560x1440 597x336mm 27.0-inch                     | 3        | 0.48%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                       | 2        | 0.32%   |
| TCT DP1080P60 TCT0270 2560x1600 480x270mm 21.7-inch                    | 2        | 0.32%   |
| STD LCD STD2022 1440x900 420x240mm 19.0-inch                           | 2        | 0.32%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch      | 2        | 0.32%   |
| Samsung Electronics T22B300 SAM092D 1920x1080 477x268mm 21.5-inch      | 2        | 0.32%   |
| Samsung Electronics SE790C SAM0BFD 3440x1440 797x333mm 34.0-inch       | 2        | 0.32%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 2        | 0.32%   |
| Samsung Electronics S24D332 SAM0F5E 1920x1080 531x299mm 24.0-inch      | 2        | 0.32%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch      | 2        | 0.32%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 1060x626mm 48.5-inch | 2        | 0.32%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 2        | 0.32%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch               | 2        | 0.32%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                | 2        | 0.32%   |
| Philips PHL 227E6 PHLC0E5 1920x1080 477x268mm 21.5-inch                | 2        | 0.32%   |
| Mi Monitor XMI2701 2560x1440 597x335mm 27.0-inch                       | 2        | 0.32%   |
| Lenovo LEN L28u-30 LEN65FA 3840x2160 621x341mm 27.9-inch               | 2        | 0.32%   |
| Lenovo LEN L1711pC LEN13B7 1280x1024 360x300mm 18.4-inch               | 2        | 0.32%   |
| Iiyama PL2530H IVM6133 1920x1080 544x303mm 24.5-inch                   | 2        | 0.32%   |
| Hewlett-Packard Z24n HWP320E 1920x1200 518x324mm 24.1-inch             | 2        | 0.32%   |
| Hewlett-Packard 24fw HPN3545 1920x1080 527x296mm 23.8-inch             | 2        | 0.32%   |
| Goldstar ULTRAGEAR GSM774B 3440x1440 800x335mm 34.1-inch               | 2        | 0.32%   |
| Goldstar ULTRAFINE GSM5BC2 3840x2160 697x392mm 31.5-inch               | 2        | 0.32%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch             | 2        | 0.32%   |
| Goldstar IPS FULLHD GSM5AB7 1920x1080 480x270mm 21.7-inch              | 2        | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 228      | 39.31%  |
| 2560x1440 (QHD)    | 91       | 15.69%  |
| 3840x2160 (4K)     | 83       | 14.31%  |
| 3440x1440          | 28       | 4.83%   |
| 1680x1050 (WSXGA+) | 24       | 4.14%   |
| 1280x1024 (SXGA)   | 20       | 3.45%   |
| 1600x900 (HD+)     | 17       | 2.93%   |
| 1920x1200 (WUXGA)  | 15       | 2.59%   |
| 1366x768 (WXGA)    | 15       | 2.59%   |
| 2560x1080          | 13       | 2.24%   |
| 1440x900 (WXGA+)   | 12       | 2.07%   |
| 1360x768           | 10       | 1.72%   |
| 3840x1080          | 4        | 0.69%   |
| 2288x1287          | 4        | 0.69%   |
| 1920x540           | 3        | 0.52%   |
| 1600x1200          | 3        | 0.52%   |
| 2048x1152          | 2        | 0.34%   |
| 1024x768 (XGA)     | 2        | 0.34%   |
| Unknown            | 2        | 0.34%   |
| 3840x2560          | 1        | 0.17%   |
| 3840x1600          | 1        | 0.17%   |
| 1280x960           | 1        | 0.17%   |
| 1280x720 (HD)      | 1        | 0.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 129      | 21.43%  |
| 24      | 86       | 14.29%  |
| 21      | 62       | 10.3%   |
| 23      | 54       | 8.97%   |
| 31      | 53       | 8.8%    |
| 34      | 36       | 5.98%   |
| 19      | 24       | 3.99%   |
| 20      | 22       | 3.65%   |
| 22      | 20       | 3.32%   |
| 18      | 12       | 1.99%   |
| Unknown | 12       | 1.99%   |
| 32      | 10       | 1.66%   |
| 84      | 7        | 1.16%   |
| 72      | 7        | 1.16%   |
| 17      | 7        | 1.16%   |
| 15      | 7        | 1.16%   |
| 35      | 6        | 1%      |
| 28      | 6        | 1%      |
| 40      | 5        | 0.83%   |
| 142     | 4        | 0.66%   |
| 54      | 4        | 0.66%   |
| 48      | 4        | 0.66%   |
| 26      | 4        | 0.66%   |
| 52      | 3        | 0.5%    |
| 25      | 3        | 0.5%    |
| 65      | 2        | 0.33%   |
| 63      | 2        | 0.33%   |
| 49      | 2        | 0.33%   |
| 42      | 2        | 0.33%   |
| 13      | 2        | 0.33%   |
| 39      | 1        | 0.17%   |
| 38      | 1        | 0.17%   |
| 37      | 1        | 0.17%   |
| 29      | 1        | 0.17%   |
| 14      | 1        | 0.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 236      | 41.04%  |
| 401-500        | 122      | 21.22%  |
| 601-700        | 79       | 13.74%  |
| 701-800        | 45       | 7.83%   |
| 1001-1500      | 17       | 2.96%   |
| 801-900        | 15       | 2.61%   |
| 351-400        | 14       | 2.43%   |
| 1501-2000      | 14       | 2.43%   |
| 301-350        | 13       | 2.26%   |
| Unknown        | 12       | 2.09%   |
| More than 2000 | 4        | 0.7%    |
| 201-300        | 2        | 0.35%   |
| 901-1000       | 2        | 0.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 397      | 73.79%  |
| 16/10   | 57       | 10.59%  |
| 21/9    | 42       | 7.81%   |
| 5/4     | 18       | 3.35%   |
| 4/3     | 6        | 1.12%   |
| 1.00    | 5        | 0.93%   |
| 32/9    | 4        | 0.74%   |
| Unknown | 4        | 0.74%   |
| 6/5     | 3        | 0.56%   |
| 3/2     | 1        | 0.19%   |
| 2.12    | 1        | 0.19%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 163      | 27.63%  |
| 301-350        | 130      | 22.03%  |
| 351-500        | 110      | 18.64%  |
| 151-200        | 70       | 11.86%  |
| 251-300        | 34       | 5.76%   |
| More than 1000 | 32       | 5.42%   |
| 141-150        | 16       | 2.71%   |
| 501-1000       | 13       | 2.2%    |
| Unknown        | 12       | 2.03%   |
| 101-110        | 8        | 1.36%   |
| 81-90          | 1        | 0.17%   |
| 71-80          | 1        | 0.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 311      | 55.94%  |
| 101-120       | 144      | 25.9%   |
| 121-160       | 37       | 6.65%   |
| 1-50          | 31       | 5.58%   |
| 161-240       | 19       | 3.42%   |
| Unknown       | 12       | 2.16%   |
| More than 240 | 2        | 0.36%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 377      | 71.27%  |
| 2     | 123      | 23.25%  |
| 0     | 19       | 3.59%   |
| 3     | 8        | 1.51%   |
| 4     | 2        | 0.38%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 317      | 41.17%  |
| Intel                                  | 257      | 33.38%  |
| Qualcomm Atheros                       | 40       | 5.19%   |
| MediaTek                               | 28       | 3.64%   |
| Broadcom                               | 21       | 2.73%   |
| TP-Link                                | 14       | 1.82%   |
| Ralink Technology                      | 11       | 1.43%   |
| Microsoft                              | 11       | 1.43%   |
| Aquantia                               | 11       | 1.43%   |
| Ralink                                 | 9        | 1.17%   |
| Qualcomm Atheros Communications        | 4        | 0.52%   |
| Mellanox Technologies                  | 4        | 0.52%   |
| Samsung Electronics                    | 3        | 0.39%   |
| NetGear                                | 3        | 0.39%   |
| Marvell Technology Group               | 3        | 0.39%   |
| ASUSTek Computer                       | 3        | 0.39%   |
| Xiaomi                                 | 2        | 0.26%   |
| Wilocity                               | 2        | 0.26%   |
| STMicroelectronics                     | 2        | 0.26%   |
| ICS Advent                             | 2        | 0.26%   |
| Google                                 | 2        | 0.26%   |
| D-Link                                 | 2        | 0.26%   |
| ASIX Electronics                       | 2        | 0.26%   |
| ZyDAS                                  | 1        | 0.13%   |
| VIA Technologies                       | 1        | 0.13%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.13%   |
| Qualcomm                               | 1        | 0.13%   |
| Nvidia                                 | 1        | 0.13%   |
| Motorola PCS                           | 1        | 0.13%   |
| Microchip Technology                   | 1        | 0.13%   |
| MCS                                    | 1        | 0.13%   |
| Huawei Technologies                    | 1        | 0.13%   |
| HMD Global                             | 1        | 0.13%   |
| DisplayLink                            | 1        | 0.13%   |
| Broadcom Limited                       | 1        | 0.13%   |
| Belkin Components                      | 1        | 0.13%   |
| AVM                                    | 1        | 0.13%   |
| Adafruit                               | 1        | 0.13%   |
| 3Com                                   | 1        | 0.13%   |
| Unknown                                | 1        | 0.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 248      | 27.49%  |
| Intel Wi-Fi 6 AX200                                                 | 52       | 5.76%   |
| Realtek RTL8125 2.5GbE Controller                                   | 46       | 5.1%    |
| Intel Ethernet Controller I225-V                                    | 44       | 4.88%   |
| Intel I211 Gigabit Network Connection                               | 38       | 4.21%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 19       | 2.11%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 18       | 2%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 17       | 1.88%   |
| Intel Ethernet Connection (2) I219-V                                | 14       | 1.55%   |
| Intel Alder Lake-S PCH CNVi WiFi                                    | 14       | 1.55%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter       | 12       | 1.33%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                             | 12       | 1.33%   |
| Intel Ethernet Connection (7) I219-V                                | 11       | 1.22%   |
| Microsoft Xbox Wireless Adapter for Windows                         | 10       | 1.11%   |
| Intel Ethernet Connection I217-LM                                   | 8        | 0.89%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                  | 8        | 0.89%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 7        | 0.78%   |
| Intel Wireless-AC 9260                                              | 7        | 0.78%   |
| Intel Ethernet Connection (2) I219-LM                               | 7        | 0.78%   |
| Intel Ethernet Connection (2) I218-V                                | 7        | 0.78%   |
| Intel Ethernet Connection (14) I219-V                               | 7        | 0.78%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                    | 6        | 0.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                     | 6        | 0.67%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 6        | 0.67%   |
| Realtek 802.11ac NIC                                                | 5        | 0.55%   |
| Ralink MT7601U Wireless Adapter                                     | 5        | 0.55%   |
| Ralink RT2800 802.11n PCI                                           | 5        | 0.55%   |
| Intel Wireless 3165                                                 | 5        | 0.55%   |
| Intel Ethernet Connection I217-V                                    | 5        | 0.55%   |
| Intel Ethernet Connection (7) I219-LM                               | 5        | 0.55%   |
| TP-Link Archer T4U ver.3                                            | 4        | 0.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 4        | 0.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 4        | 0.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter          | 4        | 0.44%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller           | 4        | 0.44%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter       | 4        | 0.44%   |
| Intel Ethernet Connection (17) I219-V                               | 4        | 0.44%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 4        | 0.44%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                 | 3        | 0.33%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 3        | 0.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 138      | 45.25%  |
| Realtek Semiconductor           | 42       | 13.77%  |
| MediaTek                        | 28       | 9.18%   |
| Qualcomm Atheros                | 26       | 8.52%   |
| TP-Link                         | 14       | 4.59%   |
| Ralink Technology               | 11       | 3.61%   |
| Microsoft                       | 11       | 3.61%   |
| Broadcom                        | 10       | 3.28%   |
| Ralink                          | 9        | 2.95%   |
| Qualcomm Atheros Communications | 4        | 1.31%   |
| NetGear                         | 3        | 0.98%   |
| ASUSTek Computer                | 3        | 0.98%   |
| Wilocity                        | 2        | 0.66%   |
| ZyDAS                           | 1        | 0.33%   |
| Broadcom Limited                | 1        | 0.33%   |
| Belkin Components               | 1        | 0.33%   |
| AVM                             | 1        | 0.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                           | 52       | 16.94%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 18       | 5.86%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 17       | 5.54%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                              | 14       | 4.56%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                                 | 12       | 3.91%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                       | 12       | 3.91%   |
| Microsoft Xbox Wireless Adapter for Windows                                                   | 10       | 3.26%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 8        | 2.61%   |
| Intel Wireless-AC 9260                                                                        | 7        | 2.28%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                              | 6        | 1.95%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 6        | 1.95%   |
| Realtek 802.11ac NIC                                                                          | 5        | 1.63%   |
| Ralink MT7601U Wireless Adapter                                                               | 5        | 1.63%   |
| Ralink RT2800 802.11n PCI                                                                     | 5        | 1.63%   |
| Intel Wireless 3165                                                                           | 5        | 1.63%   |
| TP-Link Archer T4U ver.3                                                                      | 4        | 1.3%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 4        | 1.3%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 4        | 1.3%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 4        | 1.3%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                 | 4        | 1.3%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                           | 3        | 0.98%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 3        | 0.98%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 3        | 0.98%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 3        | 0.98%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 3        | 0.98%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 3        | 0.98%   |
| Ralink RT5372 Wireless Adapter                                                                | 3        | 0.98%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 3        | 0.98%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 3        | 0.98%   |
| Intel Wireless 7265                                                                           | 3        | 0.98%   |
| Intel Centrino Wireless-N 2230                                                                | 3        | 0.98%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                                            | 2        | 0.65%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 2        | 0.65%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                                   | 2        | 0.65%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 2        | 0.65%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                       | 2        | 0.65%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 2        | 0.65%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 2        | 0.65%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 2        | 0.65%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 2        | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 304      | 53.62%  |
| Intel                                  | 197      | 34.74%  |
| Qualcomm Atheros                       | 17       | 3%      |
| Broadcom                               | 11       | 1.94%   |
| Aquantia                               | 11       | 1.94%   |
| Mellanox Technologies                  | 3        | 0.53%   |
| Marvell Technology Group               | 3        | 0.53%   |
| Xiaomi                                 | 2        | 0.35%   |
| Samsung Electronics                    | 2        | 0.35%   |
| ICS Advent                             | 2        | 0.35%   |
| Google                                 | 2        | 0.35%   |
| D-Link                                 | 2        | 0.35%   |
| ASIX Electronics                       | 2        | 0.35%   |
| VIA Technologies                       | 1        | 0.18%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.18%   |
| Qualcomm                               | 1        | 0.18%   |
| Nvidia                                 | 1        | 0.18%   |
| Motorola PCS                           | 1        | 0.18%   |
| Huawei Technologies                    | 1        | 0.18%   |
| HMD Global                             | 1        | 0.18%   |
| DisplayLink                            | 1        | 0.18%   |
| 3Com                                   | 1        | 0.18%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 248      | 42.25%  |
| Realtek RTL8125 2.5GbE Controller                                   | 46       | 7.84%   |
| Intel Ethernet Controller I225-V                                    | 44       | 7.5%    |
| Intel I211 Gigabit Network Connection                               | 38       | 6.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 19       | 3.24%   |
| Intel Ethernet Connection (2) I219-V                                | 14       | 2.39%   |
| Intel Ethernet Connection (7) I219-V                                | 11       | 1.87%   |
| Intel Ethernet Connection I217-LM                                   | 8        | 1.36%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 7        | 1.19%   |
| Intel Ethernet Connection (2) I219-LM                               | 7        | 1.19%   |
| Intel Ethernet Connection (2) I218-V                                | 7        | 1.19%   |
| Intel Ethernet Connection (14) I219-V                               | 7        | 1.19%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 6        | 1.02%   |
| Intel Ethernet Connection I217-V                                    | 5        | 0.85%   |
| Intel Ethernet Connection (7) I219-LM                               | 5        | 0.85%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller           | 4        | 0.68%   |
| Intel Ethernet Connection (17) I219-V                               | 4        | 0.68%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 4        | 0.68%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                     | 3        | 0.51%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter               | 3        | 0.51%   |
| Realtek Killer E3000 2.5GbE Controller                              | 3        | 0.51%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 3        | 0.51%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 3        | 0.51%   |
| Intel I210 Gigabit Network Connection                               | 3        | 0.51%   |
| Intel 82579V Gigabit Network Connection                             | 3        | 0.51%   |
| Intel 82575EB Gigabit Network Connection                            | 3        | 0.51%   |
| Intel 82574L Gigabit Network Connection                             | 3        | 0.51%   |
| Intel 82567LM-3 Gigabit Network Connection                          | 3        | 0.51%   |
| Intel 82546GB Gigabit Ethernet Controller                           | 3        | 0.51%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                   | 3        | 0.51%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 2        | 0.34%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 2        | 0.34%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet      | 2        | 0.34%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                   | 2        | 0.34%   |
| Intel Ethernet Connection (2) I218-LM                               | 2        | 0.34%   |
| Intel Ethernet Connection (11) I219-V                               | 2        | 0.34%   |
| Intel Ethernet Connection (10) I219-V                               | 2        | 0.34%   |
| ICS Advent DM9601 Fast Ethernet Adapter                             | 2        | 0.34%   |
| Google Pixel 7                                                      | 2        | 0.34%   |
| D-Link DUB-1312 Gigabit Ethernet Adapter                            | 2        | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 515      | 63.58%  |
| WiFi     | 287      | 35.43%  |
| Modem    | 7        | 0.86%   |
| Unknown  | 1        | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 388      | 70.29%  |
| WiFi     | 164      | 29.71%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 263      | 50%     |
| 2     | 218      | 41.44%  |
| 3     | 30       | 5.7%    |
| 4     | 9        | 1.71%   |
| 0     | 4        | 0.76%   |
| 6     | 1        | 0.19%   |
| 5     | 1        | 0.19%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 370      | 69.94%  |
| Yes  | 159      | 30.06%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 132      | 51.56%  |
| Cambridge Silicon Radio         | 37       | 14.45%  |
| MediaTek                        | 18       | 7.03%   |
| Realtek Semiconductor           | 17       | 6.64%   |
| Broadcom                        | 11       | 4.3%    |
| ASUSTek Computer                | 11       | 4.3%    |
| IMC Networks                    | 7        | 2.73%   |
| Qualcomm Atheros Communications | 6        | 2.34%   |
| TP-Link                         | 4        | 1.56%   |
| Foxconn / Hon Hai               | 4        | 1.56%   |
| Lite-On Technology              | 3        | 1.17%   |
| Unknown                         | 2        | 0.78%   |
| Hewlett-Packard                 | 1        | 0.39%   |
| Foxconn International           | 1        | 0.39%   |
| Edimax Technology               | 1        | 0.39%   |
| D-Link                          | 1        | 0.39%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                 | 50       | 19.53%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 37       | 14.45%  |
| MediaTek Wireless_Device                              | 18       | 7.03%   |
| Intel AX210 Bluetooth                                 | 18       | 7.03%   |
| Intel Wireless-AC 3168 Bluetooth                      | 17       | 6.64%   |
| Realtek Bluetooth Radio                               | 14       | 5.47%   |
| Intel AX201 Bluetooth                                 | 13       | 5.08%   |
| Intel Bluetooth wireless interface                    | 11       | 4.3%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 8        | 3.13%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 7        | 2.73%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 6        | 2.34%   |
| Intel Bluetooth Device                                | 5        | 1.95%   |
| TP-Link UB500 Adapter                                 | 4        | 1.56%   |
| Qualcomm Atheros  Bluetooth Device                    | 4        | 1.56%   |
| IMC Networks Wireless_Device                          | 4        | 1.56%   |
| Foxconn / Hon Hai Wireless_Device                     | 4        | 1.56%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 3        | 1.17%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 3        | 1.17%   |
| ASUS ASUS USB-BT500                                   | 3        | 1.17%   |
| Realtek  Bluetooth 4.2 Adapter                        | 2        | 0.78%   |
| IMC Networks Bluetooth Device                         | 2        | 0.78%   |
| Broadcom Bluetooth 3.0 USB Dongle                     | 2        | 0.78%   |
| ASUS Bluetooth Radio                                  | 2        | 0.78%   |
| ASUS Bluetooth Device                                 | 2        | 0.78%   |
| Unknown                                               | 2        | 0.78%   |
| Realtek Bluetooth 5.1 Radio                           | 1        | 0.39%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 1        | 0.39%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 1        | 0.39%   |
| Lite-On Bluetooth Radio                               | 1        | 0.39%   |
| Lite-On Bluetooth Device                              | 1        | 0.39%   |
| Lite-On Atheros AR3012 Bluetooth                      | 1        | 0.39%   |
| IMC Networks Bluetooth Radio                          | 1        | 0.39%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]         | 1        | 0.39%   |
| Foxconn International BCM43142A0 Bluetooth module     | 1        | 0.39%   |
| Edimax Bluetooth Adapter                              | 1        | 0.39%   |
| D-Link DBT-122 Bluetooth adapter                      | 1        | 0.39%   |
| Broadcom BCM2070B0                                    | 1        | 0.39%   |
| Broadcom BCM20702A0                                   | 1        | 0.39%   |
| Broadcom BCM2045 Bluetooth                            | 1        | 0.39%   |
| ASUS Bluetooth Adapter                                | 1        | 0.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD                                             | 289      | 29.7%   |
| Intel                                           | 271      | 27.85%  |
| Nvidia                                          | 193      | 19.84%  |
| C-Media Electronics                             | 34       | 3.49%   |
| Logitech                                        | 14       | 1.44%   |
| ASUSTek Computer                                | 13       | 1.34%   |
| Creative Labs                                   | 10       | 1.03%   |
| SteelSeries ApS                                 | 9        | 0.92%   |
| Micro Star International                        | 9        | 0.92%   |
| Kingston Technology                             | 9        | 0.92%   |
| Generalplus Technology                          | 9        | 0.92%   |
| JMTek                                           | 7        | 0.72%   |
| Razer USA                                       | 6        | 0.62%   |
| Corsair                                         | 6        | 0.62%   |
| Realtek Semiconductor                           | 5        | 0.51%   |
| Focusrite-Novation                              | 5        | 0.51%   |
| Creative Technology                             | 5        | 0.51%   |
| Sony                                            | 4        | 0.41%   |
| RODE Microphones                                | 4        | 0.41%   |
| Texas Instruments                               | 3        | 0.31%   |
| Schiit Audio                                    | 3        | 0.31%   |
| KTMicro                                         | 3        | 0.31%   |
| Hewlett-Packard                                 | 3        | 0.31%   |
| fifine Microphones                              | 3        | 0.31%   |
| Dell                                            | 3        | 0.31%   |
| Zoran Co. Personal Media Division (Nogatech)    | 2        | 0.21%   |
| Yamaha                                          | 2        | 0.21%   |
| VIA Technologies                                | 2        | 0.21%   |
| Unknown                                         | 2        | 0.21%   |
| Scarlett                                        | 2        | 0.21%   |
| Samson Technologies                             | 2        | 0.21%   |
| Licensed by Sony Computer Entertainment America | 2        | 0.21%   |
| JBL                                             | 2        | 0.21%   |
| GN Netcom                                       | 2        | 0.21%   |
| BEHRINGER International                         | 2        | 0.21%   |
| Audio-Technica                                  | 2        | 0.21%   |
| XMOS                                            | 1        | 0.1%    |
| Weltrend Semiconductor                          | 1        | 0.1%    |
| Vitana                                          | 1        | 0.1%    |
| Valve Software                                  | 1        | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 97       | 8.26%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 67       | 5.7%    |
| AMD Family 17h/19h HD Audio Controller                                     | 56       | 4.77%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 38       | 3.23%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 32       | 2.72%   |
| Intel 200 Series PCH HD Audio                                              | 32       | 2.72%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 30       | 2.55%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 30       | 2.55%   |
| Intel Cannon Lake PCH cAVS                                                 | 28       | 2.38%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 28       | 2.38%   |
| Intel Alder Lake-S HD Audio Controller                                     | 27       | 2.3%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 24       | 2.04%   |
| Nvidia GA104 High Definition Audio Controller                              | 23       | 1.96%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 23       | 1.96%   |
| Nvidia GP107GL High Definition Audio Controller                            | 22       | 1.87%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 20       | 1.7%    |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 20       | 1.7%    |
| AMD Navi 10 HDMI Audio                                                     | 17       | 1.45%   |
| Nvidia TU116 High Definition Audio Controller                              | 15       | 1.28%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 15       | 1.28%   |
| Nvidia GP104 High Definition Audio Controller                              | 14       | 1.19%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 14       | 1.19%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 13       | 1.11%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 13       | 1.11%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 12       | 1.02%   |
| Nvidia GA106 High Definition Audio Controller                              | 12       | 1.02%   |
| ASUSTek Computer USB Audio                                                 | 12       | 1.02%   |
| Nvidia High Definition Audio Controller                                    | 11       | 0.94%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 11       | 0.94%   |
| C-Media Electronics USB Audio Device                                       | 10       | 0.85%   |
| Nvidia GP106 High Definition Audio Controller                              | 9        | 0.77%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 9        | 0.77%   |
| Generalplus Technology USB Audio Device                                    | 9        | 0.77%   |
| Nvidia GP108 High Definition Audio Controller                              | 8        | 0.68%   |
| Micro Star International USB Audio                                         | 8        | 0.68%   |
| AMD FCH Azalia Controller                                                  | 8        | 0.68%   |
| Kingston Technology HyperX 7.1 Audio                                       | 7        | 0.6%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 7        | 0.6%    |
| Nvidia TU104 HD Audio Controller                                           | 6        | 0.51%   |
| Nvidia GK107 HDMI Audio Controller                                         | 6        | 0.51%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 40       | 18.18%  |
| Corsair                      | 38       | 17.27%  |
| G.Skill                      | 28       | 12.73%  |
| Unknown                      | 18       | 8.18%   |
| Samsung Electronics          | 18       | 8.18%   |
| Crucial                      | 16       | 7.27%   |
| A-DATA Technology            | 11       | 5%      |
| SK hynix                     | 9        | 4.09%   |
| Micron Technology            | 6        | 2.73%   |
| Smart                        | 5        | 2.27%   |
| Unknown                      | 5        | 2.27%   |
| Team                         | 4        | 1.82%   |
| PNY                          | 2        | 0.91%   |
| GOODRAM                      | 2        | 0.91%   |
| Apacer                       | 2        | 0.91%   |
| Unknown (0x0E9D)             | 1        | 0.45%   |
| Timetec                      | 1        | 0.45%   |
| Silicon Power                | 1        | 0.45%   |
| Sesame                       | 1        | 0.45%   |
| Ramaxel Technology           | 1        | 0.45%   |
| Qumo                         | 1        | 0.45%   |
| Patriot Memory (PDP Systems) | 1        | 0.45%   |
| Nanya Technology             | 1        | 0.45%   |
| Mushkin                      | 1        | 0.45%   |
| Lexar                        | 1        | 0.45%   |
| GIGA-BYTE                    | 1        | 0.45%   |
| EVGA                         | 1        | 0.45%   |
| CSX                          | 1        | 0.45%   |
| Atermiter                    | 1        | 0.45%   |
| AMD                          | 1        | 0.45%   |
| 89450000830B                 | 1        | 0.45%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 5        | 2.12%   |
| Unknown                                                          | 5        | 2.12%   |
| Smart RAM SH564128FH8N0TNSDR 4GB DIMM DDR3 1600MT/s              | 4        | 1.69%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s             | 4        | 1.69%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s           | 4        | 1.69%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s              | 3        | 1.27%   |
| A-DATA RAM DDR4 3200 16GB DIMM DDR4 3600MT/s                     | 3        | 1.27%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 2        | 0.85%   |
| SK hynix RAM HMT112U6TFR8C-H9 1GB DIMM DDR3 1333MT/s             | 2        | 0.85%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s              | 2        | 0.85%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s              | 2        | 0.85%   |
| Kingston RAM KHX2400C15/16G 16GB DIMM DDR4 3334MT/s              | 2        | 0.85%   |
| Kingston RAM 99U5471-001.A01LF 2GB DIMM DDR3 1333MT/s            | 2        | 0.85%   |
| Corsair RAM CMK32GX4M2B3200C16 16384MB DIMM DDR4 3400MT/s        | 2        | 0.85%   |
| A-DATA RAM DDR4 3600 16GB DIMM DDR4 3800MT/s                     | 2        | 0.85%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 1        | 0.42%   |
| Unknown RAM Module 8GB DIMM 667MT/s                              | 1        | 0.42%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                             | 1        | 0.42%   |
| Unknown RAM Module 8GB DIMM                                      | 1        | 0.42%   |
| Unknown RAM Module 4GB DIMM 400MT/s                              | 1        | 0.42%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 1        | 0.42%   |
| Unknown RAM Module 2GB DIMM DDR3 1067MT/s                        | 1        | 0.42%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                         | 1        | 0.42%   |
| Unknown RAM Module 2GB DIMM DDR2 1067MT/s                        | 1        | 0.42%   |
| Unknown RAM Module 2GB DIMM 667MT/s                              | 1        | 0.42%   |
| Unknown RAM Module 2GB DIMM 533MT/s                              | 1        | 0.42%   |
| Unknown RAM Module 2GB DIMM 400MT/s                              | 1        | 0.42%   |
| Unknown RAM Module 1GB DIMM DDR2                                 | 1        | 0.42%   |
| Unknown RAM Module 1GB DIMM DDR 333MT/s                          | 1        | 0.42%   |
| Unknown RAM CL18-22-22 D4-3600 16384MB DIMM DDR4 3600MT/s        | 1        | 0.42%   |
| Unknown RAM 3600 C20 Series 32GB DIMM DDR4 3666MT/s              | 1        | 0.42%   |
| Unknown (0x0E9D) RAM KINSOTIN8GB2666MHZ 8GB SODIMM DDR4 2667MT/s | 1        | 0.42%   |
| Timetec RAM SD3-1600 8GB SODIMM DDR3 1600MT/s                    | 1        | 0.42%   |
| Team RAM UD5-5600 16GB DIMM DDR5 12800MT/s                       | 1        | 0.42%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s               | 1        | 0.42%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s              | 1        | 0.42%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s               | 1        | 0.42%   |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s              | 1        | 0.42%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 1        | 0.42%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2667MT/s                    | 1        | 0.42%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 120      | 61.86%  |
| DDR3    | 39       | 20.1%   |
| DDR5    | 16       | 8.25%   |
| Unknown | 7        | 3.61%   |
| DDR2    | 6        | 3.09%   |
| SDRAM   | 5        | 2.58%   |
| DDR     | 1        | 0.52%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 176      | 92.15%  |
| SODIMM | 14       | 7.33%   |
| RIMM   | 1        | 0.52%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 88       | 41.71%  |
| 16384 | 48       | 22.75%  |
| 4096  | 29       | 13.74%  |
| 32768 | 23       | 10.9%   |
| 2048  | 16       | 7.58%   |
| 1024  | 7        | 3.32%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 37       | 17.05%  |
| 3600    | 29       | 13.36%  |
| 1600    | 25       | 11.52%  |
| 2667    | 13       | 5.99%   |
| 2400    | 12       | 5.53%   |
| 2133    | 10       | 4.61%   |
| 1333    | 10       | 4.61%   |
| 4800    | 7        | 3.23%   |
| 3400    | 6        | 2.76%   |
| 3800    | 5        | 2.3%    |
| 667     | 5        | 2.3%    |
| 3534    | 4        | 1.84%   |
| 1867    | 4        | 1.84%   |
| 1866    | 4        | 1.84%   |
| 3000    | 3        | 1.38%   |
| Unknown | 3        | 1.38%   |
| 6400    | 2        | 0.92%   |
| 6000    | 2        | 0.92%   |
| 5200    | 2        | 0.92%   |
| 3334    | 2        | 0.92%   |
| 3266    | 2        | 0.92%   |
| 2933    | 2        | 0.92%   |
| 2800    | 2        | 0.92%   |
| 2666    | 2        | 0.92%   |
| 2448    | 2        | 0.92%   |
| 1800    | 2        | 0.92%   |
| 1639    | 2        | 0.92%   |
| 1400    | 2        | 0.92%   |
| 1067    | 2        | 0.92%   |
| 800     | 2        | 0.92%   |
| 400     | 2        | 0.92%   |
| 12800   | 1        | 0.46%   |
| 5800    | 1        | 0.46%   |
| 5600    | 1        | 0.46%   |
| 3933    | 1        | 0.46%   |
| 3866    | 1        | 0.46%   |
| 3733    | 1        | 0.46%   |
| 3666    | 1        | 0.46%   |
| 2733    | 1        | 0.46%   |
| 533     | 1        | 0.46%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 8        | 53.33%  |
| Seiko Epson         | 2        | 13.33%  |
| Brother Industries  | 2        | 13.33%  |
| Samsung Electronics | 1        | 6.67%   |
| Dymo-CoStar         | 1        | 6.67%   |
| Canon               | 1        | 6.67%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Seiko Epson WF-2860 Series             | 1        | 6.67%   |
| Seiko Epson L120 Series                | 1        | 6.67%   |
| Samsung M2070 Series                   | 1        | 6.67%   |
| HP LaserJet Professional P1102w        | 1        | 6.67%   |
| HP LaserJet 1020                       | 1        | 6.67%   |
| HP LaserJet 1010                       | 1        | 6.67%   |
| HP ENVY Photo 7800 series              | 1        | 6.67%   |
| HP ENVY Inspire 7200 series            | 1        | 6.67%   |
| HP ENVY 5000 series                    | 1        | 6.67%   |
| HP DeskJet 3700 series                 | 1        | 6.67%   |
| HP Deskjet 2050 J510                   | 1        | 6.67%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo | 1        | 6.67%   |
| Canon TR4500 series                    | 1        | 6.67%   |
| Brother HL-2130 series                 | 1        | 6.67%   |
| Brother HL-1440 Laser Printer          | 1        | 6.67%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Canon       | 2        | 66.67%  |
| Seiko Epson | 1        | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Seiko Epson GT-X770 [Perfection V500] | 1        | 33.33%  |
| Canon CanoScan LiDE 210               | 1        | 33.33%  |
| Canon CanoScan 4400F                  | 1        | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 57       | 44.88%  |
| Microdia                               | 9        | 7.09%   |
| Microsoft                              | 8        | 6.3%    |
| Apple                                  | 4        | 3.15%   |
| Samsung Electronics                    | 3        | 2.36%   |
| Razer USA                              | 3        | 2.36%   |
| Google                                 | 3        | 2.36%   |
| AVerMedia Technologies                 | 3        | 2.36%   |
| Trust                                  | 2        | 1.57%   |
| Tobii Technology AB                    | 2        | 1.57%   |
| Sunplus Innovation Technology          | 2        | 1.57%   |
| Realtek Semiconductor                  | 2        | 1.57%   |
| KYE Systems (Mouse Systems)            | 2        | 1.57%   |
| Generalplus Technology                 | 2        | 1.57%   |
| Chicony Electronics                    | 2        | 1.57%   |
| ARC International                      | 2        | 1.57%   |
| 2M UVC CAMERA                          | 2        | 1.57%   |
| Z-Star Microelectronics                | 1        | 0.79%   |
| XHT-211220-ZW                          | 1        | 0.79%   |
| Valve Software                         | 1        | 0.79%   |
| Sonix Technology                       | 1        | 0.79%   |
| Pixart Imaging                         | 1        | 0.79%   |
| LG Electronics                         | 1        | 0.79%   |
| Jieli Technology                       | 1        | 0.79%   |
| Insta360                               | 1        | 0.79%   |
| Hewlett-Packard                        | 1        | 0.79%   |
| ezcap                                  | 1        | 0.79%   |
| Elecom                                 | 1        | 0.79%   |
| Dell                                   | 1        | 0.79%   |
| Cubeternet                             | 1        | 0.79%   |
| Cheng Uei Precision Industry (Foxlink) | 1        | 0.79%   |
| Bison Electronics                      | 1        | 0.79%   |
| Aveo Technology                        | 1        | 0.79%   |
| Asuscom Network                        | 1        | 0.79%   |
| Alpha Imaging Technology               | 1        | 0.79%   |
| Alcor Micro                            | 1        | 0.79%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920             | 9        | 7.09%   |
| Logitech Webcam C270                    | 6        | 4.72%   |
| Logitech BRIO Ultra HD Webcam           | 6        | 4.72%   |
| Logitech Webcam C170                    | 5        | 3.94%   |
| Logitech HD Webcam C525                 | 5        | 3.94%   |
| Logitech C920 PRO HD Webcam             | 5        | 3.94%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X         | 4        | 3.15%   |
| Samsung Galaxy series, misc. (MTP mode) | 3        | 2.36%   |
| Microdia Integrated Camera              | 3        | 2.36%   |
| Logitech HD Webcam C615                 | 3        | 2.36%   |
| AVerMedia Live Streamer CAM 313         | 3        | 2.36%   |
| Tobii AB EyeChip                        | 2        | 1.57%   |
| Razer USA Gaming Webcam [Kiyo]          | 2        | 1.57%   |
| Microsoft MicrosoftÂ LifeCam Studio    | 2        | 1.57%   |
| Microsoft LifeCam HD-3000               | 2        | 1.57%   |
| Microdia Webcam Vitade AF               | 2        | 1.57%   |
| Microdia USB 2.0 Camera                 | 2        | 1.57%   |
| Logitech Webcam C925e                   | 2        | 1.57%   |
| Logitech Webcam B500                    | 2        | 1.57%   |
| Logitech HD Webcam C910                 | 2        | 1.57%   |
| Logitech C922 Pro Stream Webcam         | 2        | 1.57%   |
| Logitech C505 HD Webcam                 | 2        | 1.57%   |
| Logitech BRIO 4K Stream Edition         | 2        | 1.57%   |
| Google HD USB Camera                    | 2        | 1.57%   |
| Generalplus GENERAL WEBCAM              | 2        | 1.57%   |
| ARC International Camera                | 2        | 1.57%   |
| 2M UVC CAMERA Web Camera                | 2        | 1.57%   |
| Z-Star Lenovo IdeaCentre Web Camera     | 1        | 0.79%   |
| XHT-211220-ZW Photry PC230A QHD Webcam  | 1        | 0.79%   |
| Valve Software 3D Camera                | 1        | 0.79%   |
| Trust USB Camera                        | 1        | 0.79%   |
| Trust Full HD Webcam                    | 1        | 0.79%   |
| Sunplus papalook AF 925                 | 1        | 0.79%   |
| Sunplus ezcap U3 capture-04             | 1        | 0.79%   |
| Sonix USB Camera                        | 1        | 0.79%   |
| Realtek HD 720P Webcam                  | 1        | 0.79%   |
| Realtek FULL HD 1080P Webcam            | 1        | 0.79%   |
| Razer USA Razer Kiyo Pro                | 1        | 0.79%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro    | 1        | 0.79%   |
| Microsoft MicrosoftÂ LifeCam Cinema    | 1        | 0.79%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Synaptics             | 1        | 25%     |
| LighTuning Technology | 1        | 25%     |
| Elan Microelectronics | 1        | 25%     |
| AuthenTec             | 1        | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Synaptics  WBDI Fingerprint Reader - USB 052 | 1        | 25%     |
| LighTuning Fingerprint Sensor                | 1        | 25%     |
| Elan fingerprint sensor [FeinTech FPS00200]  | 1        | 25%     |
| AuthenTec Fingerprint Sensor                 | 1        | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Yubico.com            | 1        | 33.33%  |
| Gemalto (was Gemplus) | 1        | 33.33%  |
| BIT4ID                | 1        | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Yubico.com Yubikey 4/5 U2F+CCID                   | 1        | 33.33%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 1        | 33.33%  |
| BIT4ID miniLector EVO                             | 1        | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 442      | 83.87%  |
| 1     | 72       | 13.66%  |
| 2     | 9        | 1.71%   |
| 4     | 2        | 0.38%   |
| 3     | 2        | 0.38%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 31       | 32.63%  |
| Net/wireless             | 26       | 27.37%  |
| Unassigned class         | 10       | 10.53%  |
| Multimedia controller    | 6        | 6.32%   |
| Camera                   | 5        | 5.26%   |
| Sound                    | 4        | 4.21%   |
| Fingerprint reader       | 4        | 4.21%   |
| Communication controller | 4        | 4.21%   |
| Net/ethernet             | 2        | 2.11%   |
| Storage/nvme             | 1        | 1.05%   |
| Card reader              | 1        | 1.05%   |
| Bluetooth                | 1        | 1.05%   |

