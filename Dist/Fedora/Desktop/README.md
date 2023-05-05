Fedora - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for Fedora.

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

Total: 6032

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | PRIME B550M-A               | [9146d12231](https://linux-hardware.org/?probe=9146d12231) | May 01, 2023 |
| MSI           | X99A RAIDER                 | [f2c73a1fbb](https://linux-hardware.org/?probe=f2c73a1fbb) | May 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | [be8b69e1b4](https://linux-hardware.org/?probe=be8b69e1b4) | May 01, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [2fcc250a35](https://linux-hardware.org/?probe=2fcc250a35) | May 01, 2023 |
| ASRock        | A520M-ITX/ac                | [5a9f58bcc0](https://linux-hardware.org/?probe=5a9f58bcc0) | Apr 30, 2023 |
| Gigabyte      | 970A-DS3P                   | [c1fe7a5f87](https://linux-hardware.org/?probe=c1fe7a5f87) | Apr 30, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [01311e320c](https://linux-hardware.org/?probe=01311e320c) | Apr 30, 2023 |
| ASRock        | FM2A88X Extreme6+           | [c33288abe2](https://linux-hardware.org/?probe=c33288abe2) | Apr 30, 2023 |
| MSI           | X99A RAIDER                 | [606b173cab](https://linux-hardware.org/?probe=606b173cab) | Apr 30, 2023 |
| MSI           | MPG B650I EDGE WIFI         | [eda4874295](https://linux-hardware.org/?probe=eda4874295) | Apr 30, 2023 |
| ASRock        | 970 Extreme4                | [96fd3e62de](https://linux-hardware.org/?probe=96fd3e62de) | Apr 29, 2023 |
| ASUSTek       | X99-A                       | [6505e46b86](https://linux-hardware.org/?probe=6505e46b86) | Apr 29, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [80ea529a18](https://linux-hardware.org/?probe=80ea529a18) | Apr 29, 2023 |
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
| ASRock        | FM2A88X Extreme6+           | [853016bfe3](https://linux-hardware.org/?probe=853016bfe3) | Apr 27, 2023 |
| MSI           | X99A RAIDER                 | [d6bf052a2f](https://linux-hardware.org/?probe=d6bf052a2f) | Apr 27, 2023 |
| Lenovo        | SHARKBAY NOK                | [e694779b17](https://linux-hardware.org/?probe=e694779b17) | Apr 26, 2023 |
| Lenovo        | SHARKBAY NOK                | [1e07e42dd3](https://linux-hardware.org/?probe=1e07e42dd3) | Apr 26, 2023 |
| MSI           | X470 GAMING PLUS            | [a5d42a7b78](https://linux-hardware.org/?probe=a5d42a7b78) | Apr 26, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | [474c43577f](https://linux-hardware.org/?probe=474c43577f) | Apr 26, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [e14205d01a](https://linux-hardware.org/?probe=e14205d01a) | Apr 26, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [f1f2ad2731](https://linux-hardware.org/?probe=f1f2ad2731) | Apr 26, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [5ce448176d](https://linux-hardware.org/?probe=5ce448176d) | Apr 26, 2023 |
| Gigabyte      | EX58-EXTREME                | [3b263c29fc](https://linux-hardware.org/?probe=3b263c29fc) | Apr 26, 2023 |
| ASUSTek       | PRIME H610M-A D4            | [a7e77375d4](https://linux-hardware.org/?probe=a7e77375d4) | Apr 26, 2023 |
| ASUSTek       | PRIME B550M-A               | [ba83f4a4f7](https://linux-hardware.org/?probe=ba83f4a4f7) | Apr 26, 2023 |
| ASRock        | FM2A88X Extreme6+           | [909ad37ab0](https://linux-hardware.org/?probe=909ad37ab0) | Apr 26, 2023 |
| MSI           | X99A RAIDER                 | [71983d0574](https://linux-hardware.org/?probe=71983d0574) | Apr 26, 2023 |
| ASUSTek       | P8H61-M LE                  | [a7a9d5069c](https://linux-hardware.org/?probe=a7a9d5069c) | Apr 26, 2023 |
| ASUSTek       | P8H61-M LE                  | [cd60dbbd6a](https://linux-hardware.org/?probe=cd60dbbd6a) | Apr 26, 2023 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [8c9b08bcab](https://linux-hardware.org/?probe=8c9b08bcab) | Apr 26, 2023 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [6007547b60](https://linux-hardware.org/?probe=6007547b60) | Apr 25, 2023 |
| HP            | 0AECh D                     | [c9e99b3f8c](https://linux-hardware.org/?probe=c9e99b3f8c) | Apr 25, 2023 |
| ASRock        | X300M-STX                   | [4a8d662bee](https://linux-hardware.org/?probe=4a8d662bee) | Apr 25, 2023 |
| Dell          | 040DDP A00                  | [8595139862](https://linux-hardware.org/?probe=8595139862) | Apr 25, 2023 |
| Dell          | 0YXT71 A03                  | [abc091f5c0](https://linux-hardware.org/?probe=abc091f5c0) | Apr 25, 2023 |
| Intel         | DQ67OW AAG12528-307         | [28245ea080](https://linux-hardware.org/?probe=28245ea080) | Apr 25, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [f878b7d23a](https://linux-hardware.org/?probe=f878b7d23a) | Apr 25, 2023 |
| Gigabyte      | Z77MX-D3H                   | [373372bf75](https://linux-hardware.org/?probe=373372bf75) | Apr 25, 2023 |
| ASRock        | H310M-STX                   | [9988bc063a](https://linux-hardware.org/?probe=9988bc063a) | Apr 25, 2023 |
| ASUSTek       | PRIME B550M-A               | [8fbbad22fa](https://linux-hardware.org/?probe=8fbbad22fa) | Apr 25, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [98ffa037d9](https://linux-hardware.org/?probe=98ffa037d9) | Apr 24, 2023 |
| ASUSTek       | A88XM-A/USB                 | [f4a215fc46](https://linux-hardware.org/?probe=f4a215fc46) | Apr 24, 2023 |
| Dell          | 08WXMX A02                  | [5f68c6a285](https://linux-hardware.org/?probe=5f68c6a285) | Apr 24, 2023 |
| Gigabyte      | X570S I AORUS PRO AX        | [9c37fa5192](https://linux-hardware.org/?probe=9c37fa5192) | Apr 24, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [1cc955413f](https://linux-hardware.org/?probe=1cc955413f) | Apr 23, 2023 |
| HP            | 18E7                        | [c5bc4d9c7f](https://linux-hardware.org/?probe=c5bc4d9c7f) | Apr 23, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [88036a75ec](https://linux-hardware.org/?probe=88036a75ec) | Apr 23, 2023 |
| Gigabyte      | F2A88X-UP4                  | [06859fe586](https://linux-hardware.org/?probe=06859fe586) | Apr 23, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [b9496d6431](https://linux-hardware.org/?probe=b9496d6431) | Apr 23, 2023 |
| HP            | 8062                        | [37cde2dc48](https://linux-hardware.org/?probe=37cde2dc48) | Apr 23, 2023 |
| Dell          | 0HD5W2 A00                  | [336c1b5da9](https://linux-hardware.org/?probe=336c1b5da9) | Apr 23, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [a82d805ad2](https://linux-hardware.org/?probe=a82d805ad2) | Apr 22, 2023 |
| Pegatron      | Benicia                     | [362a3ff341](https://linux-hardware.org/?probe=362a3ff341) | Apr 22, 2023 |
| Gigabyte      | B550M DS3H                  | [1950979b24](https://linux-hardware.org/?probe=1950979b24) | Apr 22, 2023 |
| MSI           | B450M MORTAR MAX            | [7560923404](https://linux-hardware.org/?probe=7560923404) | Apr 22, 2023 |
| Dell          | 0CRH6C A00                  | [cbb78e1785](https://linux-hardware.org/?probe=cbb78e1785) | Apr 22, 2023 |
| Gigabyte      | E3000N                      | [a6d7a7356a](https://linux-hardware.org/?probe=a6d7a7356a) | Apr 22, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | [3c0a66f0fc](https://linux-hardware.org/?probe=3c0a66f0fc) | Apr 22, 2023 |
| AZW           | GTR V02                     | [104badc0d7](https://linux-hardware.org/?probe=104badc0d7) | Apr 22, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [079c071335](https://linux-hardware.org/?probe=079c071335) | Apr 22, 2023 |
| MSI           | Z370M MORTAR                | [9ed0395d2c](https://linux-hardware.org/?probe=9ed0395d2c) | Apr 22, 2023 |
| Gigabyte      | H77N-WIFI                   | [80312ab34c](https://linux-hardware.org/?probe=80312ab34c) | Apr 22, 2023 |
| Techvision    | TVI7309X B0                 | [26e981dab3](https://linux-hardware.org/?probe=26e981dab3) | Apr 22, 2023 |
| ASUSTek       | PRIME A320M-K               | [fb1f9f0d16](https://linux-hardware.org/?probe=fb1f9f0d16) | Apr 21, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [a898476ffa](https://linux-hardware.org/?probe=a898476ffa) | Apr 21, 2023 |
| ASRock        | AD2700-ITX                  | [e688e656cd](https://linux-hardware.org/?probe=e688e656cd) | Apr 21, 2023 |
| HP            | 843F                        | [0060103f89](https://linux-hardware.org/?probe=0060103f89) | Apr 21, 2023 |
| Lenovo        | 3753 SDK0T76461 WIN 3422... | [65c9942c32](https://linux-hardware.org/?probe=65c9942c32) | Apr 21, 2023 |
| Lenovo        | 3753 SDK0T76461 WIN 3422... | [607dbbf4d8](https://linux-hardware.org/?probe=607dbbf4d8) | Apr 21, 2023 |
| ASUSTek       | PRIME A320M-K               | [ebdd0f2a6a](https://linux-hardware.org/?probe=ebdd0f2a6a) | Apr 20, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [81334f294e](https://linux-hardware.org/?probe=81334f294e) | Apr 20, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [cebfbef6d8](https://linux-hardware.org/?probe=cebfbef6d8) | Apr 20, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [8e7095e453](https://linux-hardware.org/?probe=8e7095e453) | Apr 20, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [f7ca0a552d](https://linux-hardware.org/?probe=f7ca0a552d) | Apr 20, 2023 |
| ASUSTek       | CG8270                      | [3f390ff38e](https://linux-hardware.org/?probe=3f390ff38e) | Apr 20, 2023 |
| ASUSTek       | CG8270                      | [a4f54ca55b](https://linux-hardware.org/?probe=a4f54ca55b) | Apr 20, 2023 |
| Gigabyte      | A320M-S2H-CF                | [063b4867ba](https://linux-hardware.org/?probe=063b4867ba) | Apr 20, 2023 |
| Gigabyte      | Z270XP-SLI-CF               | [1383ab9981](https://linux-hardware.org/?probe=1383ab9981) | Apr 20, 2023 |
| ASUSTek       | PRIME B360-PLUS             | [00b1045cf9](https://linux-hardware.org/?probe=00b1045cf9) | Apr 20, 2023 |
| Gigabyte      | B85-HD3                     | [07ecc38bef](https://linux-hardware.org/?probe=07ecc38bef) | Apr 20, 2023 |
| HP            | 89D8 SMVB                   | [c4c1d8086c](https://linux-hardware.org/?probe=c4c1d8086c) | Apr 20, 2023 |
| ASUSTek       | TUF B450-PRO GAMING         | [990cf467d8](https://linux-hardware.org/?probe=990cf467d8) | Apr 19, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [4fbb42afa0](https://linux-hardware.org/?probe=4fbb42afa0) | Apr 19, 2023 |
| Unknown       | Unknown                     | [85700f4804](https://linux-hardware.org/?probe=85700f4804) | Apr 19, 2023 |
| Dell          | 08NPPY A00                  | [6780931a5d](https://linux-hardware.org/?probe=6780931a5d) | Apr 19, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | [96f6b41a5c](https://linux-hardware.org/?probe=96f6b41a5c) | Apr 19, 2023 |
| AMI           | Intel                       | [3f1890d683](https://linux-hardware.org/?probe=3f1890d683) | Apr 19, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [2a80be40e3](https://linux-hardware.org/?probe=2a80be40e3) | Apr 19, 2023 |
| Gigabyte      | B85M-D3V-A                  | [84dbb8ae74](https://linux-hardware.org/?probe=84dbb8ae74) | Apr 19, 2023 |
| Dell          | 0GXM1W A00                  | [3060afd7f7](https://linux-hardware.org/?probe=3060afd7f7) | Apr 19, 2023 |
| Intel         | X79M-S                      | [0c51f5a0e0](https://linux-hardware.org/?probe=0c51f5a0e0) | Apr 19, 2023 |
| Alienware     | 0K9TKY A00                  | [22582f8d3e](https://linux-hardware.org/?probe=22582f8d3e) | Apr 19, 2023 |
| MSI           | Z170A GAMING PRO CARBON     | [cf13c3781c](https://linux-hardware.org/?probe=cf13c3781c) | Apr 18, 2023 |
| Dell          | 08NPPY A00                  | [7fcc7d1b34](https://linux-hardware.org/?probe=7fcc7d1b34) | Apr 18, 2023 |
| ASRock        | Z170 Gaming K4              | [cbd09f0f67](https://linux-hardware.org/?probe=cbd09f0f67) | Apr 18, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [cb1db50c6c](https://linux-hardware.org/?probe=cb1db50c6c) | Apr 18, 2023 |
| Intel         | DZ68DB AAG27985-105         | [aa030a4054](https://linux-hardware.org/?probe=aa030a4054) | Apr 18, 2023 |
| ASUSTek       | B85-PRO GAMER               | [bbe3e437d6](https://linux-hardware.org/?probe=bbe3e437d6) | Apr 17, 2023 |
| ASUSTek       | PRIME B550M-A               | [4b953003cc](https://linux-hardware.org/?probe=4b953003cc) | Apr 17, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | [07a49303af](https://linux-hardware.org/?probe=07a49303af) | Apr 17, 2023 |
| ASUSTek       | PRIME H410M-E               | [a537c2bd18](https://linux-hardware.org/?probe=a537c2bd18) | Apr 17, 2023 |
| ASRock        | A520M-HVS                   | [264d99482b](https://linux-hardware.org/?probe=264d99482b) | Apr 17, 2023 |
| MSI           | H310M PRO-VD PLUS           | [bff38bc725](https://linux-hardware.org/?probe=bff38bc725) | Apr 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [c8513ddcf3](https://linux-hardware.org/?probe=c8513ddcf3) | Apr 16, 2023 |
| Gigabyte      | GA-880GM-UD2H               | [1fa07cd218](https://linux-hardware.org/?probe=1fa07cd218) | Apr 16, 2023 |
| ASUSTek       | PRIME B360-PLUS             | [c228cbe8e1](https://linux-hardware.org/?probe=c228cbe8e1) | Apr 16, 2023 |
| Gigabyte      | B85-HD3                     | [25e7d545ae](https://linux-hardware.org/?probe=25e7d545ae) | Apr 16, 2023 |
| ASRock        | A520M-HVS                   | [a0d799e140](https://linux-hardware.org/?probe=a0d799e140) | Apr 16, 2023 |
| HP            | 212B                        | [c8f86eb8a4](https://linux-hardware.org/?probe=c8f86eb8a4) | Apr 15, 2023 |
| Lenovo        | ThinkCentre M58p 7220A72    | [2be395131f](https://linux-hardware.org/?probe=2be395131f) | Apr 15, 2023 |
| Lenovo        | ThinkCentre M58p 7220A72    | [0ca4b7045e](https://linux-hardware.org/?probe=0ca4b7045e) | Apr 15, 2023 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | [2e601ecae8](https://linux-hardware.org/?probe=2e601ecae8) | Apr 15, 2023 |
| MSI           | H310M PRO-VD PLUS           | [9f6209111c](https://linux-hardware.org/?probe=9f6209111c) | Apr 14, 2023 |
| ASRock        | B550M Pro4                  | [ec08193576](https://linux-hardware.org/?probe=ec08193576) | Apr 14, 2023 |
| Gigabyte      | 970A-DS3P                   | [e2f136f068](https://linux-hardware.org/?probe=e2f136f068) | Apr 14, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [c7ca0e9fd1](https://linux-hardware.org/?probe=c7ca0e9fd1) | Apr 14, 2023 |
| MSI           | MS-7388                     | [4efa2b04da](https://linux-hardware.org/?probe=4efa2b04da) | Apr 14, 2023 |
| Gigabyte      | B560M H                     | [c59729f9d2](https://linux-hardware.org/?probe=c59729f9d2) | Apr 14, 2023 |
| ASRock        | 970 Pro3 R2.0               | [1d6ace19a5](https://linux-hardware.org/?probe=1d6ace19a5) | Apr 13, 2023 |
| Gigabyte      | X79-UD3                     | [d2fbfe344c](https://linux-hardware.org/?probe=d2fbfe344c) | Apr 12, 2023 |
| MSI           | MS-7388                     | [d7f892b3e2](https://linux-hardware.org/?probe=d7f892b3e2) | Apr 12, 2023 |
| ASUSTek       | E3M-ET V5 SERIES            | [7e0735056c](https://linux-hardware.org/?probe=7e0735056c) | Apr 12, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [c279e7b8fe](https://linux-hardware.org/?probe=c279e7b8fe) | Apr 11, 2023 |
| Dell          | 0J3C2F A00                  | [12f634cf42](https://linux-hardware.org/?probe=12f634cf42) | Apr 11, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | [e8645a51dc](https://linux-hardware.org/?probe=e8645a51dc) | Apr 11, 2023 |
| HP            | 225E                        | [46f665e085](https://linux-hardware.org/?probe=46f665e085) | Apr 11, 2023 |
| MSI           | X99A RAIDER                 | [35d855a901](https://linux-hardware.org/?probe=35d855a901) | Apr 10, 2023 |
| ASRock        | FM2A88X Extreme6+           | [6fe9dfd9a6](https://linux-hardware.org/?probe=6fe9dfd9a6) | Apr 10, 2023 |
| ECS           | H61H2-M12                   | [f3e8f5eb22](https://linux-hardware.org/?probe=f3e8f5eb22) | Apr 10, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [621eb9522f](https://linux-hardware.org/?probe=621eb9522f) | Apr 09, 2023 |
| MSI           | X99A RAIDER                 | [3f8d1c6a26](https://linux-hardware.org/?probe=3f8d1c6a26) | Apr 09, 2023 |
| ASRock        | FM2A88X Extreme6+           | [87f9a72b18](https://linux-hardware.org/?probe=87f9a72b18) | Apr 09, 2023 |
| Dell          | 0M5DCD A00                  | [f65d106f65](https://linux-hardware.org/?probe=f65d106f65) | Apr 08, 2023 |
| MSI           | B450I GAMING PLUS AC        | [e34683f5f0](https://linux-hardware.org/?probe=e34683f5f0) | Apr 07, 2023 |
| MSI           | B450M MORTAR MAX            | [e9281d0364](https://linux-hardware.org/?probe=e9281d0364) | Apr 06, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [fb8ef4b4af](https://linux-hardware.org/?probe=fb8ef4b4af) | Apr 06, 2023 |
| MSI           | B450I GAMING PLUS AC        | [adda27b48e](https://linux-hardware.org/?probe=adda27b48e) | Apr 06, 2023 |
| Gigabyte      | H610M S2H DDR4              | [b34f7e7ea6](https://linux-hardware.org/?probe=b34f7e7ea6) | Apr 05, 2023 |
| HP            | 1495                        | [c0665ecb23](https://linux-hardware.org/?probe=c0665ecb23) | Apr 04, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [53fc9d8c25](https://linux-hardware.org/?probe=53fc9d8c25) | Apr 04, 2023 |
| Pegatron      | 2ACB                        | [f35bc7fec6](https://linux-hardware.org/?probe=f35bc7fec6) | Apr 04, 2023 |
| Dell          | 00V62H A00                  | [f801258fa5](https://linux-hardware.org/?probe=f801258fa5) | Apr 04, 2023 |
| Itautec       | ST 4265 ST-4265 Padrao 0... | [26e8d46d94](https://linux-hardware.org/?probe=26e8d46d94) | Apr 03, 2023 |
| ASUSTek       | PRIME B550M-A               | [84c709f5f9](https://linux-hardware.org/?probe=84c709f5f9) | Apr 03, 2023 |
| Unknown       | Unknown                     | [02a35c15b7](https://linux-hardware.org/?probe=02a35c15b7) | Apr 03, 2023 |
| Unknown       | Unknown                     | [9a44a4b80a](https://linux-hardware.org/?probe=9a44a4b80a) | Apr 03, 2023 |
| Gigabyte      | B85M-D3V-A                  | [1789a17694](https://linux-hardware.org/?probe=1789a17694) | Apr 03, 2023 |
| ASUSTek       | PRIME B550M-A               | [e65532d978](https://linux-hardware.org/?probe=e65532d978) | Apr 03, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [36f91bbb2d](https://linux-hardware.org/?probe=36f91bbb2d) | Apr 02, 2023 |
| Medion        | MS-7728                     | [83f7f01bde](https://linux-hardware.org/?probe=83f7f01bde) | Apr 02, 2023 |
| Gigabyte      | X570S AERO G                | [30e0bd8317](https://linux-hardware.org/?probe=30e0bd8317) | Apr 02, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [f3b1797500](https://linux-hardware.org/?probe=f3b1797500) | Apr 02, 2023 |
| ASRock        | FM2A88X Extreme6+           | [94df0605ae](https://linux-hardware.org/?probe=94df0605ae) | Apr 02, 2023 |
| MSI           | X99A RAIDER                 | [d6f7c92fc7](https://linux-hardware.org/?probe=d6f7c92fc7) | Apr 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [9148a1d487](https://linux-hardware.org/?probe=9148a1d487) | Apr 02, 2023 |
| ASRock        | J3160DC-ITX                 | [7735423853](https://linux-hardware.org/?probe=7735423853) | Apr 02, 2023 |
| ASUSTek       | PRIME B250M-A               | [575a0650aa](https://linux-hardware.org/?probe=575a0650aa) | Apr 01, 2023 |
| Gigabyte      | Z170-D3H-CF                 | [f278e6aad0](https://linux-hardware.org/?probe=f278e6aad0) | Apr 01, 2023 |
| Gigabyte      | GA-970A-UD3                 | [30d25bdb17](https://linux-hardware.org/?probe=30d25bdb17) | Apr 01, 2023 |
| ASUSTek       | PRIME B250M-A               | [dc5fce2825](https://linux-hardware.org/?probe=dc5fce2825) | Apr 01, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [b4a624599e](https://linux-hardware.org/?probe=b4a624599e) | Apr 01, 2023 |
| Intel         | DH77EB AAG39073-304         | [f0d73d9284](https://linux-hardware.org/?probe=f0d73d9284) | Apr 01, 2023 |
| MSI           | MAG B660M MORTAR WIFI DD... | [c512f4cdd9](https://linux-hardware.org/?probe=c512f4cdd9) | Apr 01, 2023 |
| ASUSTek       | PRIME B550M-A               | [79d44a9e66](https://linux-hardware.org/?probe=79d44a9e66) | Apr 01, 2023 |
| MSI           | MAG B660M MORTAR WIFI DD... | [e615755655](https://linux-hardware.org/?probe=e615755655) | Apr 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | [4a9aebc7f0](https://linux-hardware.org/?probe=4a9aebc7f0) | Apr 01, 2023 |
| MSI           | X99A RAIDER                 | [50e745e72a](https://linux-hardware.org/?probe=50e745e72a) | Apr 01, 2023 |
| ASUSTek       | Leonite2                    | [41353f6a59](https://linux-hardware.org/?probe=41353f6a59) | Apr 01, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [acfff71638](https://linux-hardware.org/?probe=acfff71638) | Mar 31, 2023 |
| Gigabyte      | Z270P-D3-CF                 | [8ce3dc1981](https://linux-hardware.org/?probe=8ce3dc1981) | Mar 31, 2023 |
| Gigabyte      | B550M DS3H AC               | [4693b65922](https://linux-hardware.org/?probe=4693b65922) | Mar 31, 2023 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [8d4ef602e5](https://linux-hardware.org/?probe=8d4ef602e5) | Mar 31, 2023 |
| Dell          | 0PP150 A00                  | [fdc879a486](https://linux-hardware.org/?probe=fdc879a486) | Mar 31, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [1417777bbc](https://linux-hardware.org/?probe=1417777bbc) | Mar 30, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | [70efcb81e9](https://linux-hardware.org/?probe=70efcb81e9) | Mar 30, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [2ac52b4538](https://linux-hardware.org/?probe=2ac52b4538) | Mar 30, 2023 |
| HP            | 18E7                        | [6b64a1639b](https://linux-hardware.org/?probe=6b64a1639b) | Mar 30, 2023 |
| ASUSTek       | Leonite2                    | [21eb6fba07](https://linux-hardware.org/?probe=21eb6fba07) | Mar 30, 2023 |
| Gigabyte      | J1900M-D2P                  | [881f70cb12](https://linux-hardware.org/?probe=881f70cb12) | Mar 30, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [bc798d371a](https://linux-hardware.org/?probe=bc798d371a) | Mar 30, 2023 |
| System76      | Thelio Mira thelio-mira-... | [4915a172bd](https://linux-hardware.org/?probe=4915a172bd) | Mar 29, 2023 |
| Gigabyte      | B85M-D3V-A                  | [06ad8e8099](https://linux-hardware.org/?probe=06ad8e8099) | Mar 29, 2023 |
| Gigabyte      | Z270P-D3-CF                 | [a091222ad4](https://linux-hardware.org/?probe=a091222ad4) | Mar 29, 2023 |
| Acer          | Veriton N4630G              | [fab3140b7b](https://linux-hardware.org/?probe=fab3140b7b) | Mar 29, 2023 |
| Gigabyte      | P55-UD6-C                   | [7c56c30e23](https://linux-hardware.org/?probe=7c56c30e23) | Mar 29, 2023 |
| Gigabyte      | P55-UD6-C                   | [010ed7a818](https://linux-hardware.org/?probe=010ed7a818) | Mar 29, 2023 |
| MSI           | B450M MORTAR                | [7febdf82c0](https://linux-hardware.org/?probe=7febdf82c0) | Mar 28, 2023 |
| Dell          | 0WR7PY A01                  | [5f0453caf8](https://linux-hardware.org/?probe=5f0453caf8) | Mar 28, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [151a527b35](https://linux-hardware.org/?probe=151a527b35) | Mar 28, 2023 |
| ASUSTek       | PRIME B550M-A               | [4b0ae8033f](https://linux-hardware.org/?probe=4b0ae8033f) | Mar 28, 2023 |
| MSI           | B550-A PRO                  | [999219f420](https://linux-hardware.org/?probe=999219f420) | Mar 28, 2023 |
| Lenovo        | ThinkServer TS130           | [2a36fc5043](https://linux-hardware.org/?probe=2a36fc5043) | Mar 28, 2023 |
| ASUSTek       | PRIME B350M-A               | [7e04c0e7cd](https://linux-hardware.org/?probe=7e04c0e7cd) | Mar 27, 2023 |
| Dell          | 08HPGT A01                  | [451ccd93f2](https://linux-hardware.org/?probe=451ccd93f2) | Mar 27, 2023 |
| Dell          | 08HPGT A01                  | [e38a63e793](https://linux-hardware.org/?probe=e38a63e793) | Mar 27, 2023 |
| Huanan        | X99-F8D V2.6                | [65f96586ec](https://linux-hardware.org/?probe=65f96586ec) | Mar 27, 2023 |
| ASUSTek       | PRIME B550M-K               | [81dc7d8f53](https://linux-hardware.org/?probe=81dc7d8f53) | Mar 27, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | [14380327b0](https://linux-hardware.org/?probe=14380327b0) | Mar 27, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [79dc82b50b](https://linux-hardware.org/?probe=79dc82b50b) | Mar 27, 2023 |
| ASUSTek       | Maximus VIII HERO           | [23ee1856bc](https://linux-hardware.org/?probe=23ee1856bc) | Mar 27, 2023 |
| MSI           | X99A RAIDER                 | [761f7d71db](https://linux-hardware.org/?probe=761f7d71db) | Mar 27, 2023 |
| ASRock        | FM2A88X Extreme6+           | [6b00de6bed](https://linux-hardware.org/?probe=6b00de6bed) | Mar 27, 2023 |
| Acer          | Aspire M3910                | [8cc87c48d1](https://linux-hardware.org/?probe=8cc87c48d1) | Mar 27, 2023 |
| Dell          | 07PR60 A01                  | [f312d049e0](https://linux-hardware.org/?probe=f312d049e0) | Mar 27, 2023 |
| ASRock        | B450M-HDV R4.0              | [e069fb2622](https://linux-hardware.org/?probe=e069fb2622) | Mar 26, 2023 |
| Acer          | Veriton M2631 V:1.0         | [4a4f12631a](https://linux-hardware.org/?probe=4a4f12631a) | Mar 26, 2023 |
| MSI           | X79A-GD45 Plus              | [0a5446e862](https://linux-hardware.org/?probe=0a5446e862) | Mar 26, 2023 |
| MSI           | X99A RAIDER                 | [dd6b3f7e44](https://linux-hardware.org/?probe=dd6b3f7e44) | Mar 26, 2023 |
| ASRock        | FM2A88X Extreme6+           | [a607ac616d](https://linux-hardware.org/?probe=a607ac616d) | Mar 26, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [3711318620](https://linux-hardware.org/?probe=3711318620) | Mar 26, 2023 |
| BESSTAR Te... | F6BFC                       | [881c531ee5](https://linux-hardware.org/?probe=881c531ee5) | Mar 25, 2023 |
| ASUSTek       | PRIME B450M-K               | [95b0768bfc](https://linux-hardware.org/?probe=95b0768bfc) | Mar 25, 2023 |
| MSI           | 2AE0                        | [43a4a75176](https://linux-hardware.org/?probe=43a4a75176) | Mar 25, 2023 |
| Lenovo        | SHARKBAY No DPK             | [2941abc936](https://linux-hardware.org/?probe=2941abc936) | Mar 25, 2023 |
| ASRock        | AD525PV3                    | [84545fd0ea](https://linux-hardware.org/?probe=84545fd0ea) | Mar 25, 2023 |
| MSI           | A320M-A PRO MAX             | [505777b9b6](https://linux-hardware.org/?probe=505777b9b6) | Mar 25, 2023 |
| Gigabyte      | J1900M-D2P                  | [5acd2b0492](https://linux-hardware.org/?probe=5acd2b0492) | Mar 25, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [518cef7fe4](https://linux-hardware.org/?probe=518cef7fe4) | Mar 24, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [cce19de050](https://linux-hardware.org/?probe=cce19de050) | Mar 24, 2023 |
| Gigabyte      | H77N-WIFI                   | [1503a33123](https://linux-hardware.org/?probe=1503a33123) | Mar 24, 2023 |
| ASRock        | X670E Pro RS                | [8437e47a82](https://linux-hardware.org/?probe=8437e47a82) | Mar 24, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [b2cdf1deb7](https://linux-hardware.org/?probe=b2cdf1deb7) | Mar 24, 2023 |
| PCWare        | IPMH310G                    | [3cc2e91e56](https://linux-hardware.org/?probe=3cc2e91e56) | Mar 24, 2023 |
| Itautec       | ST 4265                     | [4671d7c30e](https://linux-hardware.org/?probe=4671d7c30e) | Mar 23, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [4731315325](https://linux-hardware.org/?probe=4731315325) | Mar 23, 2023 |
| ASUSTek       | P8P67 PRO                   | [7ed577df49](https://linux-hardware.org/?probe=7ed577df49) | Mar 23, 2023 |
| Gigabyte      | A520M S2H                   | [50931f533e](https://linux-hardware.org/?probe=50931f533e) | Mar 23, 2023 |
| ASRock        | AD525PV3                    | [0749ec7b44](https://linux-hardware.org/?probe=0749ec7b44) | Mar 23, 2023 |
| ASUSTek       | PRIME Z590M-PLUS            | [0027308e3d](https://linux-hardware.org/?probe=0027308e3d) | Mar 23, 2023 |
| ASRock        | X79 Extreme6                | [1287699f09](https://linux-hardware.org/?probe=1287699f09) | Mar 23, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [bf24fe6112](https://linux-hardware.org/?probe=bf24fe6112) | Mar 23, 2023 |
| MSI           | PRO B650M-A WIFI            | [457915fe10](https://linux-hardware.org/?probe=457915fe10) | Mar 23, 2023 |
| Lenovo        | SDK0F82993 WIN              | [fbff3ec47c](https://linux-hardware.org/?probe=fbff3ec47c) | Mar 23, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | [1159055040](https://linux-hardware.org/?probe=1159055040) | Mar 23, 2023 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [299072c37e](https://linux-hardware.org/?probe=299072c37e) | Mar 22, 2023 |
| ASUSTek       | B85M-G                      | [e973d0294d](https://linux-hardware.org/?probe=e973d0294d) | Mar 22, 2023 |
| HP            | 158A                        | [4bcb73e1bf](https://linux-hardware.org/?probe=4bcb73e1bf) | Mar 22, 2023 |
| ASUSTek       | PRIME B550M-A               | [aede16096d](https://linux-hardware.org/?probe=aede16096d) | Mar 22, 2023 |
| Gigabyte      | X570 AORUS PRO              | [825332bfce](https://linux-hardware.org/?probe=825332bfce) | Mar 21, 2023 |
| NZXT          | N7 B550                     | [8ca9bc3db9](https://linux-hardware.org/?probe=8ca9bc3db9) | Mar 21, 2023 |
| MSI           | Z370-A PRO                  | [87bce00c67](https://linux-hardware.org/?probe=87bce00c67) | Mar 21, 2023 |
| MSI           | X570-A PRO                  | [a9c58c1f47](https://linux-hardware.org/?probe=a9c58c1f47) | Mar 21, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [e7ff5cdaae](https://linux-hardware.org/?probe=e7ff5cdaae) | Mar 21, 2023 |
| Shuttle       | SH570                       | [3ef2bf52b7](https://linux-hardware.org/?probe=3ef2bf52b7) | Mar 21, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [3298f3c951](https://linux-hardware.org/?probe=3298f3c951) | Mar 20, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [cb21d30b9e](https://linux-hardware.org/?probe=cb21d30b9e) | Mar 20, 2023 |
| MSI           | PRO Z790-P WIFI             | [038bd3a32b](https://linux-hardware.org/?probe=038bd3a32b) | Mar 20, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [4483bfa54d](https://linux-hardware.org/?probe=4483bfa54d) | Mar 20, 2023 |
| Win elemen... | M600                        | [eb40c2a7fc](https://linux-hardware.org/?probe=eb40c2a7fc) | Mar 20, 2023 |
| ASRock        | H81M-HG4 R4.0               | [ef87ac1a64](https://linux-hardware.org/?probe=ef87ac1a64) | Mar 20, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [53a3d14aa0](https://linux-hardware.org/?probe=53a3d14aa0) | Mar 20, 2023 |
| Dell          | 0YXT71 A00                  | [7a4669a603](https://linux-hardware.org/?probe=7a4669a603) | Mar 19, 2023 |
| ASRock        | FM2A88X Extreme6+           | [93ff9f0891](https://linux-hardware.org/?probe=93ff9f0891) | Mar 19, 2023 |
| MSI           | X99A RAIDER                 | [8892fdfdf9](https://linux-hardware.org/?probe=8892fdfdf9) | Mar 19, 2023 |
| ASRock        | B450M-HDV R4.0              | [dca0487261](https://linux-hardware.org/?probe=dca0487261) | Mar 19, 2023 |
| ASUSTek       | PRIME Z690-P                | [923aa59ad5](https://linux-hardware.org/?probe=923aa59ad5) | Mar 19, 2023 |
| ASUSTek       | PRIME B550M-A               | [b63ad62fc2](https://linux-hardware.org/?probe=b63ad62fc2) | Mar 18, 2023 |
| ASUSTek       | PRIME B550M-A               | [783a968012](https://linux-hardware.org/?probe=783a968012) | Mar 18, 2023 |
| MSI           | B365M PRO-VDH               | [3332cb54e5](https://linux-hardware.org/?probe=3332cb54e5) | Mar 18, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [501c72715a](https://linux-hardware.org/?probe=501c72715a) | Mar 18, 2023 |
| ASRock        | FM2A88X Extreme6+           | [280e67175b](https://linux-hardware.org/?probe=280e67175b) | Mar 18, 2023 |
| MSI           | X99A RAIDER                 | [f842840cc9](https://linux-hardware.org/?probe=f842840cc9) | Mar 18, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [def0907a23](https://linux-hardware.org/?probe=def0907a23) | Mar 18, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [674c4a159e](https://linux-hardware.org/?probe=674c4a159e) | Mar 18, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [bd119c8898](https://linux-hardware.org/?probe=bd119c8898) | Mar 17, 2023 |
| ZOTAC         | H67ITX-C-E                  | [1da59d5440](https://linux-hardware.org/?probe=1da59d5440) | Mar 17, 2023 |
| Gigabyte      | A320M-S2H-CF                | [35505ab2bf](https://linux-hardware.org/?probe=35505ab2bf) | Mar 17, 2023 |
| ASUSTek       | WS Z390 PRO                 | [b09959cc0b](https://linux-hardware.org/?probe=b09959cc0b) | Mar 17, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [261bcbfc32](https://linux-hardware.org/?probe=261bcbfc32) | Mar 17, 2023 |
| ASUSTek       | M2N-E SLI                   | [bf5b0c4406](https://linux-hardware.org/?probe=bf5b0c4406) | Mar 17, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [fc2a6e486c](https://linux-hardware.org/?probe=fc2a6e486c) | Mar 17, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [4d82c078c8](https://linux-hardware.org/?probe=4d82c078c8) | Mar 16, 2023 |
| Gigabyte      | G41MT-D3                    | [b4483fd4e2](https://linux-hardware.org/?probe=b4483fd4e2) | Mar 16, 2023 |
| Gigabyte      | H81M-H                      | [0ac96925cd](https://linux-hardware.org/?probe=0ac96925cd) | Mar 16, 2023 |
| Pegatron      | 2ACB                        | [d36124f8d9](https://linux-hardware.org/?probe=d36124f8d9) | Mar 16, 2023 |
| Gigabyte      | H410M H V3                  | [6023b7ce1d](https://linux-hardware.org/?probe=6023b7ce1d) | Mar 16, 2023 |
| ASRock        | H310M-STX                   | [ea6af9ac0b](https://linux-hardware.org/?probe=ea6af9ac0b) | Mar 16, 2023 |
| Lenovo        | 32E6 SDK0T76530 WIN 3556... | [69cb363858](https://linux-hardware.org/?probe=69cb363858) | Mar 16, 2023 |
| ASRock        | H310M-STX                   | [56c7261b06](https://linux-hardware.org/?probe=56c7261b06) | Mar 16, 2023 |
| Lenovo        | 32E6 SDK0T76530 WIN 3556... | [c9e4cb7c2e](https://linux-hardware.org/?probe=c9e4cb7c2e) | Mar 16, 2023 |
| ASUSTek       | PRIME B550M-A               | [f48398a1e2](https://linux-hardware.org/?probe=f48398a1e2) | Mar 16, 2023 |
| Gigabyte      | Z77X-UD3H                   | [c483268c88](https://linux-hardware.org/?probe=c483268c88) | Mar 16, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [679da48c41](https://linux-hardware.org/?probe=679da48c41) | Mar 16, 2023 |
| Gigabyte      | B550 AORUS PRO              | [b72b91fd00](https://linux-hardware.org/?probe=b72b91fd00) | Mar 16, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [897879b2c7](https://linux-hardware.org/?probe=897879b2c7) | Mar 16, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [bf303c0c16](https://linux-hardware.org/?probe=bf303c0c16) | Mar 16, 2023 |
| MSI           | H81M-P33                    | [cb3d11f591](https://linux-hardware.org/?probe=cb3d11f591) | Mar 15, 2023 |
| MSI           | B450M MORTAR                | [14a4314e39](https://linux-hardware.org/?probe=14a4314e39) | Mar 15, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [79c13317c6](https://linux-hardware.org/?probe=79c13317c6) | Mar 15, 2023 |
| Dell          | 0NC2VH A01                  | [e6fd051ae8](https://linux-hardware.org/?probe=e6fd051ae8) | Mar 14, 2023 |
| Huanan        | X99-QD4 V1.0                | [800c597040](https://linux-hardware.org/?probe=800c597040) | Mar 14, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | [b324afc6f8](https://linux-hardware.org/?probe=b324afc6f8) | Mar 14, 2023 |
| ASRock        | H170M Pro4                  | [c34ef2441a](https://linux-hardware.org/?probe=c34ef2441a) | Mar 14, 2023 |
| Dell          | 0C96W1 A03                  | [171959ac44](https://linux-hardware.org/?probe=171959ac44) | Mar 14, 2023 |
| Dell          | 0C96W1 A03                  | [9456c9ff8e](https://linux-hardware.org/?probe=9456c9ff8e) | Mar 14, 2023 |
| ASUSTek       | PRIME Z270-A                | [047e561901](https://linux-hardware.org/?probe=047e561901) | Mar 14, 2023 |
| ASUSTek       | Rampage V EXTREME           | [e186537a7e](https://linux-hardware.org/?probe=e186537a7e) | Mar 14, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | [532c5768ad](https://linux-hardware.org/?probe=532c5768ad) | Mar 14, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [c59a00db09](https://linux-hardware.org/?probe=c59a00db09) | Mar 13, 2023 |
| MSI           | PRO B550M-VC WIFI           | [c3a62d14b3](https://linux-hardware.org/?probe=c3a62d14b3) | Mar 13, 2023 |
| Gigabyte      | B650 AORUS PRO AX           | [e245557641](https://linux-hardware.org/?probe=e245557641) | Mar 13, 2023 |
| Gigabyte      | 990FXA-UD5 R5               | [532bf1dca2](https://linux-hardware.org/?probe=532bf1dca2) | Mar 13, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [89e2967e3c](https://linux-hardware.org/?probe=89e2967e3c) | Mar 12, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [e45386803e](https://linux-hardware.org/?probe=e45386803e) | Mar 12, 2023 |
| ASUSTek       | PRIME Z690-P                | [76054930ac](https://linux-hardware.org/?probe=76054930ac) | Mar 12, 2023 |
| ASUSTek       | PRIME Z690-P                | [a925c8a320](https://linux-hardware.org/?probe=a925c8a320) | Mar 12, 2023 |
| ASRock        | FM2A88X Extreme6+           | [5434188010](https://linux-hardware.org/?probe=5434188010) | Mar 12, 2023 |
| MSI           | X99A RAIDER                 | [c919e2da37](https://linux-hardware.org/?probe=c919e2da37) | Mar 12, 2023 |
| MSI           | A320M-A PRO MAX             | [07ebf171d6](https://linux-hardware.org/?probe=07ebf171d6) | Mar 12, 2023 |
| ASUSTek       | PRIME A520M-E               | [d2b4cffe84](https://linux-hardware.org/?probe=d2b4cffe84) | Mar 11, 2023 |
| ASUSTek       | H170-PRO                    | [c3e0b5bc1d](https://linux-hardware.org/?probe=c3e0b5bc1d) | Mar 11, 2023 |
| ASUSTek       | PRIME B550M-A               | [b7a4968bcd](https://linux-hardware.org/?probe=b7a4968bcd) | Mar 11, 2023 |
| Gigabyte      | Z170X-UD3 Ultra-CF          | [fa2be7de30](https://linux-hardware.org/?probe=fa2be7de30) | Mar 11, 2023 |
| Unknown       | Unknown                     | [7e7927f2dd](https://linux-hardware.org/?probe=7e7927f2dd) | Mar 11, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [1d552cfca2](https://linux-hardware.org/?probe=1d552cfca2) | Mar 11, 2023 |
| Lenovo        | SHARKBAY NOK                | [d674283cb0](https://linux-hardware.org/?probe=d674283cb0) | Mar 11, 2023 |
| ASRock        | X570M Pro4                  | [d3ac8dd45f](https://linux-hardware.org/?probe=d3ac8dd45f) | Mar 11, 2023 |
| Acer          | Veriton X4620G v1.0         | [fc27bc474e](https://linux-hardware.org/?probe=fc27bc474e) | Mar 11, 2023 |
| ASRock        | 990FX Killer                | [23bd30e79e](https://linux-hardware.org/?probe=23bd30e79e) | Mar 11, 2023 |
| MSI           | X99A RAIDER                 | [089cafb799](https://linux-hardware.org/?probe=089cafb799) | Mar 11, 2023 |
| ASRock        | FM2A88X Extreme6+           | [0f9de03c50](https://linux-hardware.org/?probe=0f9de03c50) | Mar 11, 2023 |
| MSI           | X370 XPOWER GAMING TITAN... | [abebd8a5c2](https://linux-hardware.org/?probe=abebd8a5c2) | Mar 11, 2023 |
| ASUSTek       | PRIME B550M-A               | [e9af5c4cb2](https://linux-hardware.org/?probe=e9af5c4cb2) | Mar 10, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | [ca937e17a7](https://linux-hardware.org/?probe=ca937e17a7) | Mar 10, 2023 |
| Gigabyte      | G41MT-D3                    | [e27d91ea6f](https://linux-hardware.org/?probe=e27d91ea6f) | Mar 09, 2023 |
| Gigabyte      | G41MT-D3                    | [790877da61](https://linux-hardware.org/?probe=790877da61) | Mar 09, 2023 |
| ASUSTek       | P8Z77-V DELUXE              | [a63cd6d4aa](https://linux-hardware.org/?probe=a63cd6d4aa) | Mar 09, 2023 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [9cd2cf85c7](https://linux-hardware.org/?probe=9cd2cf85c7) | Mar 09, 2023 |
| ASRock        | Z370M Pro4                  | [c4bb8436ac](https://linux-hardware.org/?probe=c4bb8436ac) | Mar 08, 2023 |
| MSI           | MAG B460M MORTAR            | [233700c52d](https://linux-hardware.org/?probe=233700c52d) | Mar 08, 2023 |
| Gigabyte      | J1900M-D2P                  | [dfe7f75406](https://linux-hardware.org/?probe=dfe7f75406) | Mar 08, 2023 |
| Gigabyte      | H77N-WIFI                   | [ffaa232ea2](https://linux-hardware.org/?probe=ffaa232ea2) | Mar 08, 2023 |
| Gigabyte      | Z77MX-D3H                   | [916862cd66](https://linux-hardware.org/?probe=916862cd66) | Mar 08, 2023 |
| ASUSTek       | PRIME B550M-A               | [62800640af](https://linux-hardware.org/?probe=62800640af) | Mar 07, 2023 |
| AZW           | GTR V02                     | [030dde937b](https://linux-hardware.org/?probe=030dde937b) | Mar 07, 2023 |
| Lenovo        | Bantry CRB SDK0J40709 WI... | [0dd36bc615](https://linux-hardware.org/?probe=0dd36bc615) | Mar 07, 2023 |
| MSI           | X99A RAIDER                 | [2246ef48c8](https://linux-hardware.org/?probe=2246ef48c8) | Mar 07, 2023 |
| ASRock        | FM2A88X Extreme6+           | [bac7bd817d](https://linux-hardware.org/?probe=bac7bd817d) | Mar 07, 2023 |
| ASUSTek       | PRIME B550M-A               | [5750b514a0](https://linux-hardware.org/?probe=5750b514a0) | Mar 06, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [6735fc94ae](https://linux-hardware.org/?probe=6735fc94ae) | Mar 06, 2023 |
| Gigabyte      | Z170-D3H-CF                 | [3fb642aac7](https://linux-hardware.org/?probe=3fb642aac7) | Mar 06, 2023 |
| MSI           | MAG B460M MORTAR            | [de44275a2c](https://linux-hardware.org/?probe=de44275a2c) | Mar 06, 2023 |
| Dell          | 0RY007                      | [1aff8f499e](https://linux-hardware.org/?probe=1aff8f499e) | Mar 06, 2023 |
| ASRock        | FM2A88X Extreme6+           | [d725cc57f0](https://linux-hardware.org/?probe=d725cc57f0) | Mar 06, 2023 |
| MSI           | X99A RAIDER                 | [46d39caf5c](https://linux-hardware.org/?probe=46d39caf5c) | Mar 06, 2023 |
| ASUSTek       | PRIME X570-P                | [14eb2d295d](https://linux-hardware.org/?probe=14eb2d295d) | Mar 06, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | [e6421e9301](https://linux-hardware.org/?probe=e6421e9301) | Mar 06, 2023 |
| Huanan        | X99-TF                      | [99a3729e53](https://linux-hardware.org/?probe=99a3729e53) | Mar 05, 2023 |
| ASUSTek       | TUF Gaming B660M-E D4       | [5d94a30450](https://linux-hardware.org/?probe=5d94a30450) | Mar 05, 2023 |
| MSI           | B550M PRO                   | [6d904e2413](https://linux-hardware.org/?probe=6d904e2413) | Mar 05, 2023 |
| HP            | 2B05                        | [deb075440f](https://linux-hardware.org/?probe=deb075440f) | Mar 05, 2023 |
| HP            | 2B05                        | [f21bd9cc58](https://linux-hardware.org/?probe=f21bd9cc58) | Mar 05, 2023 |
| ASUSTek       | P8P67 DELUXE                | [31e4b3ada8](https://linux-hardware.org/?probe=31e4b3ada8) | Mar 05, 2023 |
| Gigabyte      | H77N-WIFI                   | [dfc84acc1a](https://linux-hardware.org/?probe=dfc84acc1a) | Mar 05, 2023 |
| Gigabyte      | Z87X-UD3H-CF                | [f0b9f4e39f](https://linux-hardware.org/?probe=f0b9f4e39f) | Mar 05, 2023 |
| ASRock        | B560M-ITX/ac                | [0bbfe90659](https://linux-hardware.org/?probe=0bbfe90659) | Mar 05, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [08f74aef46](https://linux-hardware.org/?probe=08f74aef46) | Mar 05, 2023 |
| ASUSTek       | P7H55-M LX                  | [79e06d188d](https://linux-hardware.org/?probe=79e06d188d) | Mar 04, 2023 |
| ASRock        | X470 Taichi                 | [59392dfa37](https://linux-hardware.org/?probe=59392dfa37) | Mar 04, 2023 |
| ASUSTek       | PRIME B550M-K               | [91fab60d63](https://linux-hardware.org/?probe=91fab60d63) | Mar 04, 2023 |
| MSI           | MEG Z390 GODLIKE            | [b61241e05e](https://linux-hardware.org/?probe=b61241e05e) | Mar 04, 2023 |
| MSI           | B350 TOMAHAWK ARCTIC        | [06063736c6](https://linux-hardware.org/?probe=06063736c6) | Mar 04, 2023 |
| ASRock        | FM2A88X Extreme6+           | [b4110d0e0b](https://linux-hardware.org/?probe=b4110d0e0b) | Mar 04, 2023 |
| MSI           | X99A RAIDER                 | [b20cfbdfa1](https://linux-hardware.org/?probe=b20cfbdfa1) | Mar 04, 2023 |
| MSI           | MEG Z390 GODLIKE            | [871c72708d](https://linux-hardware.org/?probe=871c72708d) | Mar 04, 2023 |
| MSI           | MAG B460M MORTAR WIFI       | [4b9b04ef26](https://linux-hardware.org/?probe=4b9b04ef26) | Mar 03, 2023 |
| MSI           | MAG B460M MORTAR WIFI       | [b6535fad6b](https://linux-hardware.org/?probe=b6535fad6b) | Mar 03, 2023 |
| MSI           | X99A RAIDER                 | [989eed6d5f](https://linux-hardware.org/?probe=989eed6d5f) | Mar 03, 2023 |
| ASRock        | FM2A88X Extreme6+           | [7efed287ee](https://linux-hardware.org/?probe=7efed287ee) | Mar 03, 2023 |
| Dell          | 00V62H A01                  | [191bd6ec28](https://linux-hardware.org/?probe=191bd6ec28) | Mar 03, 2023 |
| Dell          | 00V62H A01                  | [391c255a97](https://linux-hardware.org/?probe=391c255a97) | Mar 03, 2023 |
| ASUSTek       | TUF Gaming B660M-E D4       | [277d16fb2a](https://linux-hardware.org/?probe=277d16fb2a) | Mar 02, 2023 |
| ASUSTek       | Maximus VII RANGER          | [3934b91be7](https://linux-hardware.org/?probe=3934b91be7) | Mar 02, 2023 |
| ASUSTek       | PRIME B550M-K               | [8ef1c9b71d](https://linux-hardware.org/?probe=8ef1c9b71d) | Mar 02, 2023 |
| MSI           | B350 TOMAHAWK               | [e699d6bb6e](https://linux-hardware.org/?probe=e699d6bb6e) | Mar 02, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [883911a8df](https://linux-hardware.org/?probe=883911a8df) | Mar 02, 2023 |
| AZW           | SEi                         | [eb876ab2f4](https://linux-hardware.org/?probe=eb876ab2f4) | Mar 02, 2023 |
| AZW           | SEi                         | [7184a124c7](https://linux-hardware.org/?probe=7184a124c7) | Mar 02, 2023 |
| Dell          | 0KRC95 A02                  | [3bb7b686ec](https://linux-hardware.org/?probe=3bb7b686ec) | Mar 02, 2023 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | [420e6e6325](https://linux-hardware.org/?probe=420e6e6325) | Mar 01, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [50520b2cf0](https://linux-hardware.org/?probe=50520b2cf0) | Mar 01, 2023 |
| Gigabyte      | B365M GAMING HD             | [1b3d15d8f6](https://linux-hardware.org/?probe=1b3d15d8f6) | Mar 01, 2023 |
| Gigabyte      | B365M GAMING HD             | [0485a3d508](https://linux-hardware.org/?probe=0485a3d508) | Mar 01, 2023 |
| ASUSTek       | PRIME B550M-A               | [9d6539b8f6](https://linux-hardware.org/?probe=9d6539b8f6) | Mar 01, 2023 |
| ASUSTek       | PRIME B550M-K               | [588ac214ef](https://linux-hardware.org/?probe=588ac214ef) | Mar 01, 2023 |
| HP            | 834F                        | [96631603b3](https://linux-hardware.org/?probe=96631603b3) | Mar 01, 2023 |
| MSI           | A320M GRENADE               | [1a5ffd0fc4](https://linux-hardware.org/?probe=1a5ffd0fc4) | Mar 01, 2023 |
| Packard Be... | IMEDIA S3840                | [d0ce638961](https://linux-hardware.org/?probe=d0ce638961) | Mar 01, 2023 |
| ASUSTek       | PRIME B550M-A               | [713781f44e](https://linux-hardware.org/?probe=713781f44e) | Mar 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | [833b6835b6](https://linux-hardware.org/?probe=833b6835b6) | Mar 01, 2023 |
| MSI           | X99A RAIDER                 | [ba4afa4d3b](https://linux-hardware.org/?probe=ba4afa4d3b) | Mar 01, 2023 |
| Dell          | 0KRC95 A02                  | [5cf1539621](https://linux-hardware.org/?probe=5cf1539621) | Mar 01, 2023 |
| ASUSTek       | PRIME B550M-A               | [48c5c743c9](https://linux-hardware.org/?probe=48c5c743c9) | Feb 28, 2023 |
| ASRock        | H61M-VS                     | [04d5b9593e](https://linux-hardware.org/?probe=04d5b9593e) | Feb 28, 2023 |
| HP            | 158A                        | [64f3590183](https://linux-hardware.org/?probe=64f3590183) | Feb 28, 2023 |
| ASRock        | FM2A88X Extreme6+           | [1b5fd0df61](https://linux-hardware.org/?probe=1b5fd0df61) | Feb 28, 2023 |
| MSI           | X99A RAIDER                 | [f27314deb8](https://linux-hardware.org/?probe=f27314deb8) | Feb 28, 2023 |
| ASRock        | H81M-HG4 R4.0               | [47ed7baef0](https://linux-hardware.org/?probe=47ed7baef0) | Feb 28, 2023 |
| Fujitsu       | D3224-P1 S26361-D3224-P1    | [53649a9546](https://linux-hardware.org/?probe=53649a9546) | Feb 28, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [3cd0e65d1f](https://linux-hardware.org/?probe=3cd0e65d1f) | Feb 27, 2023 |
| ASUSTek       | PRIME Q270M-C               | [3a9683fbb7](https://linux-hardware.org/?probe=3a9683fbb7) | Feb 27, 2023 |
| Gigabyte      | Z490 VISION D               | [cbea73a793](https://linux-hardware.org/?probe=cbea73a793) | Feb 27, 2023 |
| Gigabyte      | Z490 VISION D               | [3e9f2feeaa](https://linux-hardware.org/?probe=3e9f2feeaa) | Feb 27, 2023 |
| Gigabyte      | Z170MX-Gaming 5             | [1f0e9197f9](https://linux-hardware.org/?probe=1f0e9197f9) | Feb 26, 2023 |
| ASUSTek       | PRIME B550M-A               | [a121d0545a](https://linux-hardware.org/?probe=a121d0545a) | Feb 26, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c56cf68cef](https://linux-hardware.org/?probe=c56cf68cef) | Feb 26, 2023 |
| Gigabyte      | EX58-UD5                    | [85ed1d43c7](https://linux-hardware.org/?probe=85ed1d43c7) | Feb 26, 2023 |
| Gigabyte      | H510M S2                    | [24ea8468ca](https://linux-hardware.org/?probe=24ea8468ca) | Feb 26, 2023 |
| ASUSTek       | PRIME A320M-K               | [c204192a4b](https://linux-hardware.org/?probe=c204192a4b) | Feb 26, 2023 |
| Gigabyte      | H310M D3H                   | [058fac57c2](https://linux-hardware.org/?probe=058fac57c2) | Feb 25, 2023 |
| ASUSTek       | PRIME B450M-A II            | [420520e3ab](https://linux-hardware.org/?probe=420520e3ab) | Feb 25, 2023 |
| Dell          | 0W2F8G A01                  | [1d0d54843b](https://linux-hardware.org/?probe=1d0d54843b) | Feb 25, 2023 |
| ASRock        | FM2A88X Extreme6+           | [87c5af58f5](https://linux-hardware.org/?probe=87c5af58f5) | Feb 25, 2023 |
| MSI           | X99A RAIDER                 | [d6c6778bb7](https://linux-hardware.org/?probe=d6c6778bb7) | Feb 25, 2023 |
| Gigabyte      | H310M S2 x.x                | [27fa5a62b6](https://linux-hardware.org/?probe=27fa5a62b6) | Feb 24, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [4a0d65f6b5](https://linux-hardware.org/?probe=4a0d65f6b5) | Feb 24, 2023 |
| MSI           | B350M PRO-VDH               | [748d109cb3](https://linux-hardware.org/?probe=748d109cb3) | Feb 24, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | [5d901ddc4e](https://linux-hardware.org/?probe=5d901ddc4e) | Feb 24, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [2312252934](https://linux-hardware.org/?probe=2312252934) | Feb 24, 2023 |
| MSI           | X99A RAIDER                 | [7b4981d722](https://linux-hardware.org/?probe=7b4981d722) | Feb 24, 2023 |
| ASRock        | FM2A88X Extreme6+           | [6e57f3a472](https://linux-hardware.org/?probe=6e57f3a472) | Feb 24, 2023 |
| MSI           | Z170A PC MATE               | [5ee58b9271](https://linux-hardware.org/?probe=5ee58b9271) | Feb 24, 2023 |
| MSI           | Z87M GAMING                 | [0603accd89](https://linux-hardware.org/?probe=0603accd89) | Feb 24, 2023 |
| ASUSTek       | PRIME B550M-A               | [acdea94715](https://linux-hardware.org/?probe=acdea94715) | Feb 23, 2023 |
| MSI           | MEG Z390 GODLIKE            | [5f091de01b](https://linux-hardware.org/?probe=5f091de01b) | Feb 23, 2023 |
| Gateway       | SX2185                      | [32ab171e53](https://linux-hardware.org/?probe=32ab171e53) | Feb 23, 2023 |
| ASRock        | B450M Pro4                  | [193a97dfb1](https://linux-hardware.org/?probe=193a97dfb1) | Feb 23, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [eade3920d9](https://linux-hardware.org/?probe=eade3920d9) | Feb 23, 2023 |
| ASUSTek       | P5L-MX                      | [cc19e49d3c](https://linux-hardware.org/?probe=cc19e49d3c) | Feb 23, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [b82d73c832](https://linux-hardware.org/?probe=b82d73c832) | Feb 22, 2023 |
| ASUSTek       | P5L-MX                      | [9eb9ca3cfb](https://linux-hardware.org/?probe=9eb9ca3cfb) | Feb 22, 2023 |
| MSI           | MEG Z390 GODLIKE            | [974ae4135b](https://linux-hardware.org/?probe=974ae4135b) | Feb 22, 2023 |
| Acer          | Veriton N4630G              | [eb6a551e75](https://linux-hardware.org/?probe=eb6a551e75) | Feb 22, 2023 |
| ASRock        | AB350 Pro4                  | [aaad317fe4](https://linux-hardware.org/?probe=aaad317fe4) | Feb 22, 2023 |
| ASRockRack    | X470D4U                     | [162a5279bc](https://linux-hardware.org/?probe=162a5279bc) | Feb 21, 2023 |
| Gigabyte      | A320M-S2H-CF                | [67ba988b20](https://linux-hardware.org/?probe=67ba988b20) | Feb 21, 2023 |
| Gigabyte      | J1900M-D2P                  | [edd5640ca7](https://linux-hardware.org/?probe=edd5640ca7) | Feb 21, 2023 |
| MSI           | H410M PRO-VH                | [669d124e33](https://linux-hardware.org/?probe=669d124e33) | Feb 21, 2023 |
| ASRock        | B550M Steel Legend          | [c3f49d4cee](https://linux-hardware.org/?probe=c3f49d4cee) | Feb 20, 2023 |
| ASUSTek       | PRIME B550M-A               | [8fd85f724b](https://linux-hardware.org/?probe=8fd85f724b) | Feb 20, 2023 |
| Lenovo        | ThinkCentre M58 8910B4U     | [03c8e6d135](https://linux-hardware.org/?probe=03c8e6d135) | Feb 19, 2023 |
| ASUSTek       | SABERTOOTH X99              | [422b14d8d7](https://linux-hardware.org/?probe=422b14d8d7) | Feb 19, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [2af589c6e9](https://linux-hardware.org/?probe=2af589c6e9) | Feb 19, 2023 |
| ASRock        | X670E Pro RS                | [906d11e2a3](https://linux-hardware.org/?probe=906d11e2a3) | Feb 19, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [42099690a6](https://linux-hardware.org/?probe=42099690a6) | Feb 19, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [f9314a0aa9](https://linux-hardware.org/?probe=f9314a0aa9) | Feb 19, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [6eda9f2592](https://linux-hardware.org/?probe=6eda9f2592) | Feb 19, 2023 |
| ASUSTek       | P5Q SE2                     | [37b0d0609f](https://linux-hardware.org/?probe=37b0d0609f) | Feb 18, 2023 |
| ASRock        | H110 Pro BTC+               | [bce117c4dc](https://linux-hardware.org/?probe=bce117c4dc) | Feb 18, 2023 |
| MSI           | Z170A KRAIT GAMING          | [27dcbbe1d7](https://linux-hardware.org/?probe=27dcbbe1d7) | Feb 18, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [831d4806fb](https://linux-hardware.org/?probe=831d4806fb) | Feb 18, 2023 |
| MSI           | H410M PRO-VH                | [ccc1cbf2fa](https://linux-hardware.org/?probe=ccc1cbf2fa) | Feb 18, 2023 |
| ASRock        | FM2A88X Extreme6+           | [f14a791491](https://linux-hardware.org/?probe=f14a791491) | Feb 18, 2023 |
| MSI           | X99A RAIDER                 | [8dabbaa31c](https://linux-hardware.org/?probe=8dabbaa31c) | Feb 18, 2023 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | [5fe0f2c1fe](https://linux-hardware.org/?probe=5fe0f2c1fe) | Feb 18, 2023 |
| ASUSTek       | PRIME B550M-A               | [f9fb638882](https://linux-hardware.org/?probe=f9fb638882) | Feb 17, 2023 |
| ASUSTek       | PRIME Z690M-PLUS D4         | [750c0f6337](https://linux-hardware.org/?probe=750c0f6337) | Feb 17, 2023 |
| ASRock        | X470 Taichi                 | [71685845fe](https://linux-hardware.org/?probe=71685845fe) | Feb 17, 2023 |
| MSI           | X99A RAIDER                 | [991b8b4361](https://linux-hardware.org/?probe=991b8b4361) | Feb 17, 2023 |
| ASRock        | FM2A88X Extreme6+           | [8c3926e125](https://linux-hardware.org/?probe=8c3926e125) | Feb 17, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [8e3bad7795](https://linux-hardware.org/?probe=8e3bad7795) | Feb 17, 2023 |
| Gigabyte      | A320M-S2H-CF                | [add68ac711](https://linux-hardware.org/?probe=add68ac711) | Feb 16, 2023 |
| ASUSTek       | PRIME B550M-A               | [a19a7a2edd](https://linux-hardware.org/?probe=a19a7a2edd) | Feb 16, 2023 |
| ASUSTek       | EX-H310M-V3 R2.0            | [d42c40dd2e](https://linux-hardware.org/?probe=d42c40dd2e) | Feb 16, 2023 |
| ASRock        | Z370 Pro4                   | [bafba5486b](https://linux-hardware.org/?probe=bafba5486b) | Feb 16, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [f4e8b0e952](https://linux-hardware.org/?probe=f4e8b0e952) | Feb 16, 2023 |
| ASUSTek       | P8Z77-V PRO/THUNDERBOLT     | [a370fca217](https://linux-hardware.org/?probe=a370fca217) | Feb 15, 2023 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [ca54397755](https://linux-hardware.org/?probe=ca54397755) | Feb 15, 2023 |
| Supermicro    | X10DRG-Q                    | [5af331bc84](https://linux-hardware.org/?probe=5af331bc84) | Feb 15, 2023 |
| MSI           | FM2-A75MA-E35               | [a7f2ca398d](https://linux-hardware.org/?probe=a7f2ca398d) | Feb 15, 2023 |
| Gigabyte      | H410M DS2V                  | [b2e8c15dc4](https://linux-hardware.org/?probe=b2e8c15dc4) | Feb 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [7d8c3e7e48](https://linux-hardware.org/?probe=7d8c3e7e48) | Feb 14, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [e718a6af67](https://linux-hardware.org/?probe=e718a6af67) | Feb 14, 2023 |
| ASRock        | X370 Gaming X               | [2b9a026876](https://linux-hardware.org/?probe=2b9a026876) | Feb 14, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [0033422c4d](https://linux-hardware.org/?probe=0033422c4d) | Feb 14, 2023 |
| HP            | 8714                        | [19a66b5101](https://linux-hardware.org/?probe=19a66b5101) | Feb 14, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [43dff5bee7](https://linux-hardware.org/?probe=43dff5bee7) | Feb 14, 2023 |
| Gigabyte      | B550 GAMING X V2            | [10c8101c9b](https://linux-hardware.org/?probe=10c8101c9b) | Feb 14, 2023 |
| MSI           | X99A RAIDER                 | [387ec47efe](https://linux-hardware.org/?probe=387ec47efe) | Feb 14, 2023 |
| ASUSTek       | Z170-A                      | [6cf7a75c9e](https://linux-hardware.org/?probe=6cf7a75c9e) | Feb 13, 2023 |
| MSI           | X99A SLI PLUS               | [98447ce3dd](https://linux-hardware.org/?probe=98447ce3dd) | Feb 13, 2023 |
| Dell          | 0KWVT8 A03                  | [eec95070bb](https://linux-hardware.org/?probe=eec95070bb) | Feb 13, 2023 |
| Dell          | 0R6PCT A01                  | [4126ed8507](https://linux-hardware.org/?probe=4126ed8507) | Feb 13, 2023 |
| Pegatron      | 2AB6                        | [65b3bb622e](https://linux-hardware.org/?probe=65b3bb622e) | Feb 12, 2023 |
| MSI           | 2A9Ch                       | [934ca9b130](https://linux-hardware.org/?probe=934ca9b130) | Feb 12, 2023 |
| MSI           | 2A9Ch                       | [1a76baff0f](https://linux-hardware.org/?probe=1a76baff0f) | Feb 12, 2023 |
| ASRock        | FM2A88X Extreme6+           | [a5469c55ac](https://linux-hardware.org/?probe=a5469c55ac) | Feb 12, 2023 |
| ASUSTek       | PRIME B550M-A               | [2d63c8d887](https://linux-hardware.org/?probe=2d63c8d887) | Feb 12, 2023 |
| Pegatron      | 2AB6                        | [1f727ee133](https://linux-hardware.org/?probe=1f727ee133) | Feb 11, 2023 |
| ASUSTek       | Z97-P                       | [004535fd1c](https://linux-hardware.org/?probe=004535fd1c) | Feb 11, 2023 |
| ASRock        | Z790 Pro RS WiFi            | [c530bf4283](https://linux-hardware.org/?probe=c530bf4283) | Feb 11, 2023 |
| ASRock        | FM2A88X Extreme6+           | [6474c43d80](https://linux-hardware.org/?probe=6474c43d80) | Feb 11, 2023 |
| ASRock        | A300M-STX                   | [79266ec6c7](https://linux-hardware.org/?probe=79266ec6c7) | Feb 10, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [9a2b8045de](https://linux-hardware.org/?probe=9a2b8045de) | Feb 10, 2023 |
| HP            | 8714                        | [3938395f75](https://linux-hardware.org/?probe=3938395f75) | Feb 10, 2023 |
| ASUSTek       | PRIME H410M-K               | [c3a837a320](https://linux-hardware.org/?probe=c3a837a320) | Feb 09, 2023 |
| ASUSTek       | PRIME B550M-A               | [70b81f3738](https://linux-hardware.org/?probe=70b81f3738) | Feb 09, 2023 |
| MSI           | B250 GAMING PRO CARBON      | [0b05e41c64](https://linux-hardware.org/?probe=0b05e41c64) | Feb 09, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [1adfd2bb79](https://linux-hardware.org/?probe=1adfd2bb79) | Feb 09, 2023 |
| Intel         | LADPNVMO AAE76523-300       | [6ced92edc7](https://linux-hardware.org/?probe=6ced92edc7) | Feb 09, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [3482c24991](https://linux-hardware.org/?probe=3482c24991) | Feb 08, 2023 |
| MSI           | H110M PRO-VD PLUS           | [c296dedf74](https://linux-hardware.org/?probe=c296dedf74) | Feb 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [69c30e6f7b](https://linux-hardware.org/?probe=69c30e6f7b) | Feb 08, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [a12cca2eeb](https://linux-hardware.org/?probe=a12cca2eeb) | Feb 08, 2023 |
| ASUSTek       | PRIME B550M-A               | [b02b8779fc](https://linux-hardware.org/?probe=b02b8779fc) | Feb 08, 2023 |
| ASRock        | FM2A88X Extreme6+           | [5c5d5d4304](https://linux-hardware.org/?probe=5c5d5d4304) | Feb 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [147b5315c5](https://linux-hardware.org/?probe=147b5315c5) | Feb 08, 2023 |
| ASUSTek       | SABERTOOTH X79              | [21910f6687](https://linux-hardware.org/?probe=21910f6687) | Feb 08, 2023 |
| ASRock        | H81M-HG4 R4.0               | [127269499d](https://linux-hardware.org/?probe=127269499d) | Feb 07, 2023 |
| Lenovo        | ThinkServer TS140           | [1bac17097f](https://linux-hardware.org/?probe=1bac17097f) | Feb 07, 2023 |
| ASUSTek       | SABERTOOTH X79              | [ace0ce95b9](https://linux-hardware.org/?probe=ace0ce95b9) | Feb 07, 2023 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [47153e938c](https://linux-hardware.org/?probe=47153e938c) | Feb 07, 2023 |
| BESSTAR Te... | B550                        | [49e414926e](https://linux-hardware.org/?probe=49e414926e) | Feb 07, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [0376f0c65f](https://linux-hardware.org/?probe=0376f0c65f) | Feb 07, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [e82192ba4c](https://linux-hardware.org/?probe=e82192ba4c) | Feb 07, 2023 |
| ASRock        | FM2A88X Extreme6+           | [d91fe3e151](https://linux-hardware.org/?probe=d91fe3e151) | Feb 07, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [31a56f80dd](https://linux-hardware.org/?probe=31a56f80dd) | Feb 06, 2023 |
| ASUSTek       | PRIME B550M-A               | [ff01db5c9a](https://linux-hardware.org/?probe=ff01db5c9a) | Feb 06, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [f1e58aba53](https://linux-hardware.org/?probe=f1e58aba53) | Feb 06, 2023 |
| ASUSTek       | PRIME B450M-A II            | [10cf328828](https://linux-hardware.org/?probe=10cf328828) | Feb 06, 2023 |
| Gigabyte      | B450M DS3H V2               | [781dc9da09](https://linux-hardware.org/?probe=781dc9da09) | Feb 06, 2023 |
| Compal        | DIP00                       | [632d4c313a](https://linux-hardware.org/?probe=632d4c313a) | Feb 06, 2023 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [522dd694da](https://linux-hardware.org/?probe=522dd694da) | Feb 05, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | [99d0ce5421](https://linux-hardware.org/?probe=99d0ce5421) | Feb 05, 2023 |
| HP            | 1589                        | [1872d63c2b](https://linux-hardware.org/?probe=1872d63c2b) | Feb 05, 2023 |
| HP            | 1589                        | [69c0ab962c](https://linux-hardware.org/?probe=69c0ab962c) | Feb 05, 2023 |
| Intel         | X99                         | [e8790caf8d](https://linux-hardware.org/?probe=e8790caf8d) | Feb 05, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [944149e350](https://linux-hardware.org/?probe=944149e350) | Feb 04, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [9f5df7e4e0](https://linux-hardware.org/?probe=9f5df7e4e0) | Feb 04, 2023 |
| Gigabyte      | Z790 GAMING X AX            | [1c6725b5eb](https://linux-hardware.org/?probe=1c6725b5eb) | Feb 04, 2023 |
| Gigabyte      | Z77MX-D3H                   | [a17959ea9b](https://linux-hardware.org/?probe=a17959ea9b) | Feb 04, 2023 |
| ASRock        | FM2A88X Extreme6+           | [3633683d62](https://linux-hardware.org/?probe=3633683d62) | Feb 04, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [f2578f11e1](https://linux-hardware.org/?probe=f2578f11e1) | Feb 03, 2023 |
| ASRock        | FM2A88X Extreme6+           | [5e9c75d478](https://linux-hardware.org/?probe=5e9c75d478) | Feb 03, 2023 |
| ASUSTek       | PRIME B550M-A               | [e680a7484e](https://linux-hardware.org/?probe=e680a7484e) | Feb 03, 2023 |
| HP            | 8714                        | [b8abceccbc](https://linux-hardware.org/?probe=b8abceccbc) | Feb 03, 2023 |
| Pegatron      | IPXSB-H61                   | [a694854d87](https://linux-hardware.org/?probe=a694854d87) | Feb 02, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [09811b1f20](https://linux-hardware.org/?probe=09811b1f20) | Feb 02, 2023 |
| Acer          | Veriton M2631 V:1.0         | [28e1975b51](https://linux-hardware.org/?probe=28e1975b51) | Feb 02, 2023 |
| MSI           | X99S SLI PLUS               | [6b007d74de](https://linux-hardware.org/?probe=6b007d74de) | Feb 02, 2023 |
| ASRock        | FM2A88X Extreme6+           | [9b8d82dfcd](https://linux-hardware.org/?probe=9b8d82dfcd) | Feb 02, 2023 |
| Gigabyte      | J1900M-D2P                  | [c7b6222f08](https://linux-hardware.org/?probe=c7b6222f08) | Feb 02, 2023 |
| ASRock        | Z77 Extreme4                | [6598bc47dd](https://linux-hardware.org/?probe=6598bc47dd) | Feb 02, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [15c523ee98](https://linux-hardware.org/?probe=15c523ee98) | Feb 02, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [f2919f7135](https://linux-hardware.org/?probe=f2919f7135) | Feb 01, 2023 |
| ASRock        | B450M Pro4 R2.0             | [28f4fb8e15](https://linux-hardware.org/?probe=28f4fb8e15) | Feb 01, 2023 |
| ASUSTek       | H81M-A/BR                   | [7d271a8235](https://linux-hardware.org/?probe=7d271a8235) | Feb 01, 2023 |
| ASUSTek       | PRIME B550M-A               | [d35cf58f46](https://linux-hardware.org/?probe=d35cf58f46) | Feb 01, 2023 |
| MSI           | MAG Z590 TORPEDO            | [431a6c7a3a](https://linux-hardware.org/?probe=431a6c7a3a) | Feb 01, 2023 |
| MSI           | Z170A PC MATE               | [ff305089b2](https://linux-hardware.org/?probe=ff305089b2) | Feb 01, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [ffe1cabad7](https://linux-hardware.org/?probe=ffe1cabad7) | Feb 01, 2023 |
| ASUSTek       | PRIME B550M-A               | [779b723b67](https://linux-hardware.org/?probe=779b723b67) | Feb 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | [79c11af9ac](https://linux-hardware.org/?probe=79c11af9ac) | Feb 01, 2023 |
| ASUSTek       | ROG STRIX Z490-A GAMING     | [5f2948351d](https://linux-hardware.org/?probe=5f2948351d) | Feb 01, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [4f8642280f](https://linux-hardware.org/?probe=4f8642280f) | Feb 01, 2023 |
| AZW           | U59                         | [9b73123be3](https://linux-hardware.org/?probe=9b73123be3) | Feb 01, 2023 |
| AZW           | U59                         | [74f028454a](https://linux-hardware.org/?probe=74f028454a) | Feb 01, 2023 |
| Gigabyte      | G41MT-D3                    | [99127d4bed](https://linux-hardware.org/?probe=99127d4bed) | Feb 01, 2023 |
| Gigabyte      | H97M-D3H                    | [3ccdc4fa2b](https://linux-hardware.org/?probe=3ccdc4fa2b) | Jan 31, 2023 |
| ASUSTek       | PRIME B550M-A               | [318b0a5ecb](https://linux-hardware.org/?probe=318b0a5ecb) | Jan 31, 2023 |
| ASRock        | FM2A88X Extreme6+           | [73bc9212a3](https://linux-hardware.org/?probe=73bc9212a3) | Jan 31, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [6e7d6aae31](https://linux-hardware.org/?probe=6e7d6aae31) | Jan 31, 2023 |
| ASRock        | AD2700-ITX                  | [2f14c18867](https://linux-hardware.org/?probe=2f14c18867) | Jan 31, 2023 |
| ASRock        | 890GM Pro3                  | [b2bb32cbbc](https://linux-hardware.org/?probe=b2bb32cbbc) | Jan 31, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [67262a8155](https://linux-hardware.org/?probe=67262a8155) | Jan 30, 2023 |
| Dell          | 0Y2K8N A01                  | [6a4a26884d](https://linux-hardware.org/?probe=6a4a26884d) | Jan 30, 2023 |
| Dell          | 0Y2K8N A01                  | [8e4f1d2ed2](https://linux-hardware.org/?probe=8e4f1d2ed2) | Jan 30, 2023 |
| ASUSTek       | PRIME B550M-A               | [585c3c8f85](https://linux-hardware.org/?probe=585c3c8f85) | Jan 30, 2023 |
| ASRock        | FM2A88X Extreme6+           | [24402e3d42](https://linux-hardware.org/?probe=24402e3d42) | Jan 30, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [9b6a9a4ab5](https://linux-hardware.org/?probe=9b6a9a4ab5) | Jan 30, 2023 |
| ASRock        | N68-S UCC                   | [e8f09a159a](https://linux-hardware.org/?probe=e8f09a159a) | Jan 29, 2023 |
| ASUSTek       | GA15DH                      | [767fe59cb7](https://linux-hardware.org/?probe=767fe59cb7) | Jan 29, 2023 |
| ASUSTek       | PRIME B450M-A II            | [104fb04e91](https://linux-hardware.org/?probe=104fb04e91) | Jan 29, 2023 |
| ASUSTek       | PRIME B550M-A               | [ef43edeee5](https://linux-hardware.org/?probe=ef43edeee5) | Jan 29, 2023 |
| ASRock        | FM2A88X Extreme6+           | [f9a823cb38](https://linux-hardware.org/?probe=f9a823cb38) | Jan 29, 2023 |
| ASRock        | X570M Pro4                  | [e72f7f2fb1](https://linux-hardware.org/?probe=e72f7f2fb1) | Jan 29, 2023 |
| Acer          | FMP55                       | [d091fbc8d3](https://linux-hardware.org/?probe=d091fbc8d3) | Jan 29, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | [d9f9d4bc89](https://linux-hardware.org/?probe=d9f9d4bc89) | Jan 27, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ff5e2b673e](https://linux-hardware.org/?probe=ff5e2b673e) | Jan 27, 2023 |
| ASRock        | 970 Pro3 R2.0               | [676f900958](https://linux-hardware.org/?probe=676f900958) | Jan 27, 2023 |
| ASUSTek       | PRIME B550M-A               | [e619db262a](https://linux-hardware.org/?probe=e619db262a) | Jan 27, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [c0ea09ef3c](https://linux-hardware.org/?probe=c0ea09ef3c) | Jan 27, 2023 |
| Gigabyte      | Z87-D3HP-CF                 | [812c00440c](https://linux-hardware.org/?probe=812c00440c) | Jan 26, 2023 |
| ASRock        | AD2700-ITX                  | [7b711bee4f](https://linux-hardware.org/?probe=7b711bee4f) | Jan 26, 2023 |
| Gigabyte      | J1900M-D2P                  | [4213c95d3d](https://linux-hardware.org/?probe=4213c95d3d) | Jan 26, 2023 |
| Gigabyte      | J1900M-D2P                  | [b44aa465bc](https://linux-hardware.org/?probe=b44aa465bc) | Jan 26, 2023 |
| ASRock        | FM2A88X Extreme6+           | [415b96672b](https://linux-hardware.org/?probe=415b96672b) | Jan 26, 2023 |
| ASRock        | B450M Steel Legend          | [f69047309d](https://linux-hardware.org/?probe=f69047309d) | Jan 26, 2023 |
| ASUSTek       | ROG STRIX H370-I GAMING     | [decfe6ab97](https://linux-hardware.org/?probe=decfe6ab97) | Jan 25, 2023 |
| Dell          | 0XFWHV A00                  | [52ee3df163](https://linux-hardware.org/?probe=52ee3df163) | Jan 25, 2023 |
| ASRock        | FM2A88X Extreme6+           | [82c3a80b93](https://linux-hardware.org/?probe=82c3a80b93) | Jan 25, 2023 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | [8ac6e901d5](https://linux-hardware.org/?probe=8ac6e901d5) | Jan 24, 2023 |
| Lenovo        | 36E9 SDK0T08861 WIN 3305... | [82705366d7](https://linux-hardware.org/?probe=82705366d7) | Jan 24, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [d1c6e3c96f](https://linux-hardware.org/?probe=d1c6e3c96f) | Jan 24, 2023 |
| ASRock        | FM2A88X Extreme6+           | [43c26544a9](https://linux-hardware.org/?probe=43c26544a9) | Jan 24, 2023 |
| Dell          | 0X30MX A00                  | [c323a1a215](https://linux-hardware.org/?probe=c323a1a215) | Jan 24, 2023 |
| ASUSTek       | PRIME X370-PRO              | [1887a95d31](https://linux-hardware.org/?probe=1887a95d31) | Jan 23, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [7572089dc3](https://linux-hardware.org/?probe=7572089dc3) | Jan 23, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | [2f215e1ce7](https://linux-hardware.org/?probe=2f215e1ce7) | Jan 23, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | [aa16eaced0](https://linux-hardware.org/?probe=aa16eaced0) | Jan 23, 2023 |
| ASRock        | FM2A88X Extreme6+           | [279452d293](https://linux-hardware.org/?probe=279452d293) | Jan 23, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [3a42df71d0](https://linux-hardware.org/?probe=3a42df71d0) | Jan 22, 2023 |
| Dell          | 0Y56T3 A00                  | [7078ea91e9](https://linux-hardware.org/?probe=7078ea91e9) | Jan 22, 2023 |
| MSI           | H510M PRO                   | [309f1bc61b](https://linux-hardware.org/?probe=309f1bc61b) | Jan 22, 2023 |
| ECS           | H61H2-MV                    | [92d2b62680](https://linux-hardware.org/?probe=92d2b62680) | Jan 22, 2023 |
| ASRock        | J3455B-ITX                  | [b4419e8fce](https://linux-hardware.org/?probe=b4419e8fce) | Jan 22, 2023 |
| MSI           | B450-A PRO                  | [e9c7c42a8b](https://linux-hardware.org/?probe=e9c7c42a8b) | Jan 22, 2023 |
| Gigabyte      | Z170-D3H-CF                 | [9792de46ad](https://linux-hardware.org/?probe=9792de46ad) | Jan 22, 2023 |
| ECS           | H61H2-MV                    | [292ff62f4c](https://linux-hardware.org/?probe=292ff62f4c) | Jan 22, 2023 |
| ASRock        | FM2A88X Extreme6+           | [b3d64d2496](https://linux-hardware.org/?probe=b3d64d2496) | Jan 22, 2023 |
| ASUSTek       | H61M-A/BR                   | [43aaf27a04](https://linux-hardware.org/?probe=43aaf27a04) | Jan 22, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [6856fa4741](https://linux-hardware.org/?probe=6856fa4741) | Jan 21, 2023 |
| AZW           | GTR V02                     | [3616feeeac](https://linux-hardware.org/?probe=3616feeeac) | Jan 21, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [7a067fe264](https://linux-hardware.org/?probe=7a067fe264) | Jan 21, 2023 |
| ASRock        | FM2A88X Extreme6+           | [20c0f69bb7](https://linux-hardware.org/?probe=20c0f69bb7) | Jan 21, 2023 |
| Gigabyte      | Z170-D3H-CF                 | [04d36be1ec](https://linux-hardware.org/?probe=04d36be1ec) | Jan 20, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [3432d7c1f5](https://linux-hardware.org/?probe=3432d7c1f5) | Jan 20, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [2f6bd134ae](https://linux-hardware.org/?probe=2f6bd134ae) | Jan 20, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [5bbd614c0f](https://linux-hardware.org/?probe=5bbd614c0f) | Jan 20, 2023 |
| HP            | 0AECh D                     | [b2ea95f507](https://linux-hardware.org/?probe=b2ea95f507) | Jan 20, 2023 |
| ASRock        | FM2A88X Extreme6+           | [5f1447f874](https://linux-hardware.org/?probe=5f1447f874) | Jan 20, 2023 |
| MSI           | X99A RAIDER                 | [7f36411ac1](https://linux-hardware.org/?probe=7f36411ac1) | Jan 20, 2023 |
| Dell          | 0GY6Y8 A02                  | [33b364ed89](https://linux-hardware.org/?probe=33b364ed89) | Jan 19, 2023 |
| ASRock        | Z690 PG Riptide             | [582e3e3026](https://linux-hardware.org/?probe=582e3e3026) | Jan 19, 2023 |
| ASRock        | X300M-STX                   | [8303a9c2a0](https://linux-hardware.org/?probe=8303a9c2a0) | Jan 18, 2023 |
| Dell          | 0XFRWW A00                  | [2b96d4b6f6](https://linux-hardware.org/?probe=2b96d4b6f6) | Jan 18, 2023 |
| ASUSTek       | PRIME X370-PRO              | [011b9a41cd](https://linux-hardware.org/?probe=011b9a41cd) | Jan 18, 2023 |
| MSI           | X99A RAIDER                 | [8da5286795](https://linux-hardware.org/?probe=8da5286795) | Jan 18, 2023 |
| ASRock        | FM2A88X Extreme6+           | [ec05dd5768](https://linux-hardware.org/?probe=ec05dd5768) | Jan 18, 2023 |
| Dell          | 0KRC95 A02                  | [01cf6039d0](https://linux-hardware.org/?probe=01cf6039d0) | Jan 18, 2023 |
| ASRock        | B550 Extreme4               | [e5599ac616](https://linux-hardware.org/?probe=e5599ac616) | Jan 18, 2023 |
| ASRock        | Z170 Gaming K4              | [44a3d49ef1](https://linux-hardware.org/?probe=44a3d49ef1) | Jan 18, 2023 |
| ASUSTek       | Z97-K                       | [8e21ef4b91](https://linux-hardware.org/?probe=8e21ef4b91) | Jan 17, 2023 |
| Gigabyte      | 990FXA-UD5 R5               | [8753bd8277](https://linux-hardware.org/?probe=8753bd8277) | Jan 17, 2023 |
| Gigabyte      | G41MT-D3                    | [16be0552b2](https://linux-hardware.org/?probe=16be0552b2) | Jan 17, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [16c9b323c6](https://linux-hardware.org/?probe=16c9b323c6) | Jan 17, 2023 |
| ASRock        | FM2A88X Extreme6+           | [aeb9ac591c](https://linux-hardware.org/?probe=aeb9ac591c) | Jan 17, 2023 |
| MSI           | X99A RAIDER                 | [9f280d24f5](https://linux-hardware.org/?probe=9f280d24f5) | Jan 17, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [f26dbd644c](https://linux-hardware.org/?probe=f26dbd644c) | Jan 17, 2023 |
| Gigabyte      | Z170-D3H-CF                 | [d0a00b398c](https://linux-hardware.org/?probe=d0a00b398c) | Jan 16, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [d5843b83af](https://linux-hardware.org/?probe=d5843b83af) | Jan 16, 2023 |
| Lenovo        | 32E9 SDK0T76461 WIN 3422... | [5480333c5b](https://linux-hardware.org/?probe=5480333c5b) | Jan 16, 2023 |
| Gigabyte      | 990FXA-UD5 R5               | [dd16b56d30](https://linux-hardware.org/?probe=dd16b56d30) | Jan 16, 2023 |
| Gigabyte      | B550M DS3H                  | [d24e1142ef](https://linux-hardware.org/?probe=d24e1142ef) | Jan 16, 2023 |
| Gigabyte      | B550M DS3H                  | [84d86434e8](https://linux-hardware.org/?probe=84d86434e8) | Jan 16, 2023 |
| Dell          | 0M863N A01                  | [1dff7cb016](https://linux-hardware.org/?probe=1dff7cb016) | Jan 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [b68ce1375d](https://linux-hardware.org/?probe=b68ce1375d) | Jan 15, 2023 |
| MSI           | B450 TOMAHAWK               | [978682daa6](https://linux-hardware.org/?probe=978682daa6) | Jan 15, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [a15e06403a](https://linux-hardware.org/?probe=a15e06403a) | Jan 15, 2023 |
| AZW           | GTR V02                     | [074c3ab42f](https://linux-hardware.org/?probe=074c3ab42f) | Jan 14, 2023 |
| Gigabyte      | Z77X-D3H                    | [4ef76b2644](https://linux-hardware.org/?probe=4ef76b2644) | Jan 14, 2023 |
| Dell          | 0W2F8G A01                  | [999fcca032](https://linux-hardware.org/?probe=999fcca032) | Jan 14, 2023 |
| ASRock        | FM2A88X Extreme6+           | [03f0709b21](https://linux-hardware.org/?probe=03f0709b21) | Jan 14, 2023 |
| MSI           | X99A RAIDER                 | [7e67b2b3a0](https://linux-hardware.org/?probe=7e67b2b3a0) | Jan 14, 2023 |
| HP            | 8753                        | [5cdf3ef632](https://linux-hardware.org/?probe=5cdf3ef632) | Jan 14, 2023 |
| ASUSTek       | STRIX B250F GAMING          | [40acaf3525](https://linux-hardware.org/?probe=40acaf3525) | Jan 13, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [c1e0fd9216](https://linux-hardware.org/?probe=c1e0fd9216) | Jan 13, 2023 |
| ASUSTek       | Z87-K                       | [61b7459a43](https://linux-hardware.org/?probe=61b7459a43) | Jan 13, 2023 |
| ASUSTek       | P8Z77-V LK                  | [f954b55a5c](https://linux-hardware.org/?probe=f954b55a5c) | Jan 13, 2023 |
| ASRock        | FM2A88X Extreme6+           | [d4b0530f79](https://linux-hardware.org/?probe=d4b0530f79) | Jan 13, 2023 |
| MSI           | X99A RAIDER                 | [3128a21a3a](https://linux-hardware.org/?probe=3128a21a3a) | Jan 13, 2023 |
| ASUSTek       | H170 PRO GAMING             | [4cf36f7404](https://linux-hardware.org/?probe=4cf36f7404) | Jan 13, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [f9846c0e18](https://linux-hardware.org/?probe=f9846c0e18) | Jan 13, 2023 |
| HP            | 3047h                       | [5eb46c9039](https://linux-hardware.org/?probe=5eb46c9039) | Jan 12, 2023 |
| HP            | 3047h                       | [0c035c1a04](https://linux-hardware.org/?probe=0c035c1a04) | Jan 12, 2023 |
| Gigabyte      | A320M-S2H-CF                | [f38e5f2a4e](https://linux-hardware.org/?probe=f38e5f2a4e) | Jan 12, 2023 |
| ASRock        | X570 Steel Legend           | [600094ae29](https://linux-hardware.org/?probe=600094ae29) | Jan 12, 2023 |
| MSI           | B450M PRO-VDH MAX           | [ffd5ad6744](https://linux-hardware.org/?probe=ffd5ad6744) | Jan 12, 2023 |
| Unknown       | X79                         | [62bf02da9d](https://linux-hardware.org/?probe=62bf02da9d) | Jan 12, 2023 |
| Unknown       | X79                         | [aed457b56c](https://linux-hardware.org/?probe=aed457b56c) | Jan 12, 2023 |
| MSI           | B550-A PRO                  | [28d13d17ba](https://linux-hardware.org/?probe=28d13d17ba) | Jan 12, 2023 |
| Pegatron      | 2AC3                        | [3cfb7d9e7c](https://linux-hardware.org/?probe=3cfb7d9e7c) | Jan 12, 2023 |
| ASUSTek       | GA15DH                      | [e480a3bfa3](https://linux-hardware.org/?probe=e480a3bfa3) | Jan 11, 2023 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [eec3fcf9ff](https://linux-hardware.org/?probe=eec3fcf9ff) | Jan 11, 2023 |
| ASRock        | Z87 Extreme6                | [49e3d87de4](https://linux-hardware.org/?probe=49e3d87de4) | Jan 11, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [18e82e414a](https://linux-hardware.org/?probe=18e82e414a) | Jan 11, 2023 |
| ASUSTek       | Z97-PRO GAMER               | [a4ab96067d](https://linux-hardware.org/?probe=a4ab96067d) | Jan 10, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | [760cc2eaed](https://linux-hardware.org/?probe=760cc2eaed) | Jan 10, 2023 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | [0a5f45ca97](https://linux-hardware.org/?probe=0a5f45ca97) | Jan 10, 2023 |
| MSI           | B450M PRO-VDH MAX           | [b65fef1f25](https://linux-hardware.org/?probe=b65fef1f25) | Jan 10, 2023 |
| ASUSTek       | PRIME B450M-A II            | [7c7c8175c0](https://linux-hardware.org/?probe=7c7c8175c0) | Jan 09, 2023 |
| Gigabyte      | H77N-WIFI                   | [95cfb68187](https://linux-hardware.org/?probe=95cfb68187) | Jan 09, 2023 |
| ASUSTek       | P8H61-M LX                  | [8ec4c19bf3](https://linux-hardware.org/?probe=8ec4c19bf3) | Jan 09, 2023 |
| AZW           | GTR V02                     | [b7a911ab61](https://linux-hardware.org/?probe=b7a911ab61) | Jan 09, 2023 |
| Gigabyte      | B85M-D3V-A                  | [d30caadc06](https://linux-hardware.org/?probe=d30caadc06) | Jan 09, 2023 |
| ASRock        | FM2A88X Extreme6+           | [d7820d12e5](https://linux-hardware.org/?probe=d7820d12e5) | Jan 09, 2023 |
| MSI           | X99A RAIDER                 | [9eac6e2b97](https://linux-hardware.org/?probe=9eac6e2b97) | Jan 09, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | [6fd945d3cd](https://linux-hardware.org/?probe=6fd945d3cd) | Jan 09, 2023 |
| MSI           | MEG X570 ACE                | [853f3c06ce](https://linux-hardware.org/?probe=853f3c06ce) | Jan 08, 2023 |
| MSI           | X570-A PRO                  | [d3e35671cd](https://linux-hardware.org/?probe=d3e35671cd) | Jan 08, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | [afd852d260](https://linux-hardware.org/?probe=afd852d260) | Jan 08, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | [5f3e927024](https://linux-hardware.org/?probe=5f3e927024) | Jan 08, 2023 |
| ASUSTek       | Z97-PRO GAMER               | [e85dcf8a22](https://linux-hardware.org/?probe=e85dcf8a22) | Jan 08, 2023 |
| ASRock        | FM2A88X Extreme6+           | [b0a36f054e](https://linux-hardware.org/?probe=b0a36f054e) | Jan 08, 2023 |
| MSI           | X99A RAIDER                 | [b8ac11cfd3](https://linux-hardware.org/?probe=b8ac11cfd3) | Jan 08, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [34259527c2](https://linux-hardware.org/?probe=34259527c2) | Jan 07, 2023 |
| ASUSTek       | PRIME B350M-A               | [df845fe4a9](https://linux-hardware.org/?probe=df845fe4a9) | Jan 07, 2023 |
| Acer          | FMCP7A-ION-LE               | [84a2abec03](https://linux-hardware.org/?probe=84a2abec03) | Jan 07, 2023 |
| ASRock        | FM2A88X Extreme6+           | [82052bbfcb](https://linux-hardware.org/?probe=82052bbfcb) | Jan 07, 2023 |
| MSI           | X99A RAIDER                 | [c8a281879a](https://linux-hardware.org/?probe=c8a281879a) | Jan 07, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [99e2769927](https://linux-hardware.org/?probe=99e2769927) | Jan 07, 2023 |
| ASUSTek       | H61M-C                      | [494e552521](https://linux-hardware.org/?probe=494e552521) | Jan 07, 2023 |
| Lenovo        | 32E9 SDK0T76461 WIN 3422... | [fcc2d12f0d](https://linux-hardware.org/?probe=fcc2d12f0d) | Jan 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [68e299de33](https://linux-hardware.org/?probe=68e299de33) | Jan 06, 2023 |
| MSI           | PRO Z690-A DDR4             | [0b9a54a591](https://linux-hardware.org/?probe=0b9a54a591) | Jan 06, 2023 |
| ASRock        | FM2A88X Extreme6+           | [bcc4cba81a](https://linux-hardware.org/?probe=bcc4cba81a) | Jan 06, 2023 |
| MSI           | X99A RAIDER                 | [94d61ca559](https://linux-hardware.org/?probe=94d61ca559) | Jan 06, 2023 |
| Dell          | 02YRK5 A02                  | [e417e45252](https://linux-hardware.org/?probe=e417e45252) | Jan 06, 2023 |
| Dell          | 02YRK5 A02                  | [e7b27ba60c](https://linux-hardware.org/?probe=e7b27ba60c) | Jan 06, 2023 |
| Gigabyte      | B450M S2H                   | [a559464349](https://linux-hardware.org/?probe=a559464349) | Jan 05, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | [0ae0a8d91b](https://linux-hardware.org/?probe=0ae0a8d91b) | Jan 05, 2023 |
| Gigabyte      | B550M DS3H                  | [24d21ee9f1](https://linux-hardware.org/?probe=24d21ee9f1) | Jan 05, 2023 |
| MSI           | X99A RAIDER                 | [01b93cba09](https://linux-hardware.org/?probe=01b93cba09) | Jan 05, 2023 |
| ASRock        | FM2A88X Extreme6+           | [1964dbc8e7](https://linux-hardware.org/?probe=1964dbc8e7) | Jan 05, 2023 |
| Positivo      | POS-PIQ57BQA                | [4453ef0d86](https://linux-hardware.org/?probe=4453ef0d86) | Jan 04, 2023 |
| ASUSTek       | SABERTOOTH Z77              | [5c352967e4](https://linux-hardware.org/?probe=5c352967e4) | Jan 04, 2023 |
| ASUSTek       | PRIME B550M-K               | [0c4e0afd97](https://linux-hardware.org/?probe=0c4e0afd97) | Jan 04, 2023 |
| Gigabyte      | B450M S2H                   | [6d6e710ac3](https://linux-hardware.org/?probe=6d6e710ac3) | Jan 04, 2023 |
| Gigabyte      | Z690 UD DDR4                | [583ea447a9](https://linux-hardware.org/?probe=583ea447a9) | Jan 04, 2023 |
| Dell          | 0N4YC8 A00                  | [0968211c5b](https://linux-hardware.org/?probe=0968211c5b) | Jan 04, 2023 |
| Dell          | 0N4YC8 A00                  | [4195800fa5](https://linux-hardware.org/?probe=4195800fa5) | Jan 04, 2023 |
| Gigabyte      | J1900M-D2P                  | [ad776cdf84](https://linux-hardware.org/?probe=ad776cdf84) | Jan 04, 2023 |
| Dell          | 0KRC95 A02                  | [8e30a9a43e](https://linux-hardware.org/?probe=8e30a9a43e) | Jan 04, 2023 |
| Positivo      | POS-PIQ57BQA                | [e03b53cc0e](https://linux-hardware.org/?probe=e03b53cc0e) | Jan 04, 2023 |
| HP            | 8459                        | [18f44a4e07](https://linux-hardware.org/?probe=18f44a4e07) | Jan 03, 2023 |
| Gigabyte      | H410M H V3                  | [abdf0ab0b9](https://linux-hardware.org/?probe=abdf0ab0b9) | Jan 03, 2023 |
| Gigabyte      | H410M H V3                  | [5c14d6ea96](https://linux-hardware.org/?probe=5c14d6ea96) | Jan 03, 2023 |
| Positivo      | POS-EIB85CZ                 | [639f5a2bf7](https://linux-hardware.org/?probe=639f5a2bf7) | Jan 03, 2023 |
| ASUSTek       | PRIME X570-P                | [f1962e0076](https://linux-hardware.org/?probe=f1962e0076) | Jan 03, 2023 |
| ASUSTek       | PRIME B550M-K               | [43ff03b36f](https://linux-hardware.org/?probe=43ff03b36f) | Jan 03, 2023 |
| Dell          | 0KRC95 A02                  | [d7c57c2bae](https://linux-hardware.org/?probe=d7c57c2bae) | Jan 03, 2023 |
| ASUSTek       | PRIME B550M-A               | [386eb7bc28](https://linux-hardware.org/?probe=386eb7bc28) | Jan 02, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | [7c98c0b00d](https://linux-hardware.org/?probe=7c98c0b00d) | Jan 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [bbd09c7b2c](https://linux-hardware.org/?probe=bbd09c7b2c) | Jan 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [013b1e7816](https://linux-hardware.org/?probe=013b1e7816) | Jan 02, 2023 |
| ASUSTek       | SABERTOOTH Z77              | [f85aeab3e5](https://linux-hardware.org/?probe=f85aeab3e5) | Jan 02, 2023 |
| ASUSTek       | PRIME B350M-E               | [f39e3e8350](https://linux-hardware.org/?probe=f39e3e8350) | Jan 02, 2023 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [4e900247e4](https://linux-hardware.org/?probe=4e900247e4) | Jan 02, 2023 |
| ASRock        | Z77 Professional            | [bf09b21dc7](https://linux-hardware.org/?probe=bf09b21dc7) | Jan 02, 2023 |
| ASRock        | FM2A88M-HD+ R2.0            | [8e9080dc74](https://linux-hardware.org/?probe=8e9080dc74) | Jan 01, 2023 |
| ASUSTek       | H81M-PLUS                   | [752fe53b7c](https://linux-hardware.org/?probe=752fe53b7c) | Jan 01, 2023 |
| Intel         | DG41TY AAE47335-300         | [11f3804cb6](https://linux-hardware.org/?probe=11f3804cb6) | Jan 01, 2023 |
| ASUSTek       | P8Z68-V GEN3                | [3b6d1593c8](https://linux-hardware.org/?probe=3b6d1593c8) | Jan 01, 2023 |
| MSI           | X99A RAIDER                 | [178dcba2a5](https://linux-hardware.org/?probe=178dcba2a5) | Jan 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | [54089a466b](https://linux-hardware.org/?probe=54089a466b) | Jan 01, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [f16b55ea54](https://linux-hardware.org/?probe=f16b55ea54) | Dec 31, 2022 |
| Shuttle       | SH570                       | [09994766ed](https://linux-hardware.org/?probe=09994766ed) | Dec 31, 2022 |
| Shuttle       | SH570                       | [f4d5ef752c](https://linux-hardware.org/?probe=f4d5ef752c) | Dec 31, 2022 |
| ASRock        | A320M-DVS R4.0              | [f82bf510be](https://linux-hardware.org/?probe=f82bf510be) | Dec 31, 2022 |
| MSI           | X99A RAIDER                 | [8582096251](https://linux-hardware.org/?probe=8582096251) | Dec 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | [c45e0f54fd](https://linux-hardware.org/?probe=c45e0f54fd) | Dec 31, 2022 |
| MAXSUN        | MS-TZZ A320M.2-VH           | [8f06578f10](https://linux-hardware.org/?probe=8f06578f10) | Dec 31, 2022 |
| Shuttle       | SH570                       | [2d7f57de8f](https://linux-hardware.org/?probe=2d7f57de8f) | Dec 31, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [1347eaedb9](https://linux-hardware.org/?probe=1347eaedb9) | Dec 31, 2022 |
| ASRock        | X79 Extreme6                | [5ea31811b4](https://linux-hardware.org/?probe=5ea31811b4) | Dec 30, 2022 |
| MSI           | H510M-A PRO                 | [4dba3b7c55](https://linux-hardware.org/?probe=4dba3b7c55) | Dec 30, 2022 |
| ASUSTek       | PRIME X670-P WIFI           | [498c8c83e2](https://linux-hardware.org/?probe=498c8c83e2) | Dec 30, 2022 |
| ASRock        | B450M Pro4                  | [4393041949](https://linux-hardware.org/?probe=4393041949) | Dec 30, 2022 |
| Gigabyte      | Z390 UD                     | [70dc568eae](https://linux-hardware.org/?probe=70dc568eae) | Dec 30, 2022 |
| Intel         | LADPNVMO AAE76523-300       | [4e6065532f](https://linux-hardware.org/?probe=4e6065532f) | Dec 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | [8289d108fb](https://linux-hardware.org/?probe=8289d108fb) | Dec 30, 2022 |
| MSI           | X99A RAIDER                 | [3b0d4e8973](https://linux-hardware.org/?probe=3b0d4e8973) | Dec 30, 2022 |
| ASUSTek       | Z87-PRO                     | [eafab9edba](https://linux-hardware.org/?probe=eafab9edba) | Dec 30, 2022 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [bdc5158ffb](https://linux-hardware.org/?probe=bdc5158ffb) | Dec 29, 2022 |
| Dell          | 0KRC95 A02                  | [4cf9d40c0d](https://linux-hardware.org/?probe=4cf9d40c0d) | Dec 29, 2022 |
| Dell          | 0KRC95 A02                  | [7e53808767](https://linux-hardware.org/?probe=7e53808767) | Dec 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | [12c052156c](https://linux-hardware.org/?probe=12c052156c) | Dec 29, 2022 |
| MSI           | X99A RAIDER                 | [daf7777113](https://linux-hardware.org/?probe=daf7777113) | Dec 29, 2022 |
| ASUSTek       | M5A78L/USB3                 | [b89e7eb1c9](https://linux-hardware.org/?probe=b89e7eb1c9) | Dec 28, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [24b822291e](https://linux-hardware.org/?probe=24b822291e) | Dec 28, 2022 |
| Gigabyte      | B365M DS3H                  | [0dc3c192fd](https://linux-hardware.org/?probe=0dc3c192fd) | Dec 28, 2022 |
| BESSTAR Te... | F6BFC                       | [7c6adb6279](https://linux-hardware.org/?probe=7c6adb6279) | Dec 28, 2022 |
| Dell          | 0N4YC8 A00                  | [fc766b2a1b](https://linux-hardware.org/?probe=fc766b2a1b) | Dec 28, 2022 |
| BESSTAR Te... | F6BFC                       | [59b38f9b63](https://linux-hardware.org/?probe=59b38f9b63) | Dec 28, 2022 |
| ASUSTek       | PRIME Z790-P WIFI           | [7bb247e453](https://linux-hardware.org/?probe=7bb247e453) | Dec 28, 2022 |
| Gigabyte      | B365M D2V                   | [93f7c010a2](https://linux-hardware.org/?probe=93f7c010a2) | Dec 28, 2022 |
| ASRock        | FM2A88X Extreme6+           | [f5ac2a0028](https://linux-hardware.org/?probe=f5ac2a0028) | Dec 28, 2022 |
| MSI           | X99A RAIDER                 | [2d572d06d7](https://linux-hardware.org/?probe=2d572d06d7) | Dec 28, 2022 |
| MSI           | Z97 GAMING 3                | [7aab4546f6](https://linux-hardware.org/?probe=7aab4546f6) | Dec 28, 2022 |
| ASRock        | Z370M-ITX/ac                | [f87fbed6a1](https://linux-hardware.org/?probe=f87fbed6a1) | Dec 28, 2022 |
| Gigabyte      | B650I AORUS ULTRA           | [3c25f43c23](https://linux-hardware.org/?probe=3c25f43c23) | Dec 28, 2022 |
| Itautec       | ST 4265                     | [38e4a07f9a](https://linux-hardware.org/?probe=38e4a07f9a) | Dec 27, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [f2751df7ec](https://linux-hardware.org/?probe=f2751df7ec) | Dec 27, 2022 |
| MSI           | Z390-A PRO                  | [e2feef912f](https://linux-hardware.org/?probe=e2feef912f) | Dec 27, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [731f916db1](https://linux-hardware.org/?probe=731f916db1) | Dec 27, 2022 |
| ASRock        | AD2700-ITX                  | [d4fff49f31](https://linux-hardware.org/?probe=d4fff49f31) | Dec 27, 2022 |
| Itautec       | ST 4265                     | [8323542129](https://linux-hardware.org/?probe=8323542129) | Dec 26, 2022 |
| ASRock        | FM2A88X Extreme6+           | [8d1181c71b](https://linux-hardware.org/?probe=8d1181c71b) | Dec 26, 2022 |
| MSI           | X99A RAIDER                 | [cbe4c82d15](https://linux-hardware.org/?probe=cbe4c82d15) | Dec 26, 2022 |
| HP            | 3397                        | [c546bb007b](https://linux-hardware.org/?probe=c546bb007b) | Dec 26, 2022 |
| HP            | 3397                        | [4286520907](https://linux-hardware.org/?probe=4286520907) | Dec 26, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [4c97c87b61](https://linux-hardware.org/?probe=4c97c87b61) | Dec 25, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | [8762b5f41f](https://linux-hardware.org/?probe=8762b5f41f) | Dec 25, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [628cefc78a](https://linux-hardware.org/?probe=628cefc78a) | Dec 25, 2022 |
| ASRock        | FM2A88X Extreme6+           | [b6def743ea](https://linux-hardware.org/?probe=b6def743ea) | Dec 25, 2022 |
| MSI           | X99A RAIDER                 | [8636b69474](https://linux-hardware.org/?probe=8636b69474) | Dec 25, 2022 |
| Gigabyte      | Z690 AORUS ULTRA            | [46705eb79f](https://linux-hardware.org/?probe=46705eb79f) | Dec 25, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [04b76a7e78](https://linux-hardware.org/?probe=04b76a7e78) | Dec 24, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [c7d8ce8f80](https://linux-hardware.org/?probe=c7d8ce8f80) | Dec 24, 2022 |
| ASUSTek       | PRIME Z790-P WIFI           | [e853f645cf](https://linux-hardware.org/?probe=e853f645cf) | Dec 24, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [82f8802857](https://linux-hardware.org/?probe=82f8802857) | Dec 24, 2022 |
| MSI           | Z270M MORTAR                | [70564a2846](https://linux-hardware.org/?probe=70564a2846) | Dec 24, 2022 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [bf8f02ac85](https://linux-hardware.org/?probe=bf8f02ac85) | Dec 24, 2022 |
| ASRock        | FM2A88X Extreme6+           | [f5fa069144](https://linux-hardware.org/?probe=f5fa069144) | Dec 24, 2022 |
| MSI           | X99A RAIDER                 | [a375cc62c7](https://linux-hardware.org/?probe=a375cc62c7) | Dec 24, 2022 |
| Gigabyte      | Z690 AORUS ULTRA            | [926850a516](https://linux-hardware.org/?probe=926850a516) | Dec 24, 2022 |
| ASRock        | FM2A88X Extreme6+           | [88df914367](https://linux-hardware.org/?probe=88df914367) | Dec 23, 2022 |
| MSI           | X99A RAIDER                 | [c36553b2b8](https://linux-hardware.org/?probe=c36553b2b8) | Dec 23, 2022 |
| ASUSTek       | B85-PLUS                    | [16b14098bf](https://linux-hardware.org/?probe=16b14098bf) | Dec 22, 2022 |
| ASRock        | H470M Pro4                  | [b69ccc3353](https://linux-hardware.org/?probe=b69ccc3353) | Dec 22, 2022 |
| Gigabyte      | X570S I AORUS PRO AX        | [3f3c7b0e92](https://linux-hardware.org/?probe=3f3c7b0e92) | Dec 22, 2022 |
| ASRock        | FM2A88X Extreme6+           | [6eb006d2d4](https://linux-hardware.org/?probe=6eb006d2d4) | Dec 22, 2022 |
| MSI           | X99A RAIDER                 | [bfe7b1ec1d](https://linux-hardware.org/?probe=bfe7b1ec1d) | Dec 22, 2022 |
| ASUSTek       | B85-PLUS                    | [cbad10e284](https://linux-hardware.org/?probe=cbad10e284) | Dec 21, 2022 |
| Dell          | 0T10XW A02                  | [f39488c597](https://linux-hardware.org/?probe=f39488c597) | Dec 21, 2022 |
| Dell          | 0T10XW A02                  | [0243df6ce4](https://linux-hardware.org/?probe=0243df6ce4) | Dec 21, 2022 |
| HP            | 8266                        | [321dbc66bf](https://linux-hardware.org/?probe=321dbc66bf) | Dec 21, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [8428e68855](https://linux-hardware.org/?probe=8428e68855) | Dec 21, 2022 |
| ASRock        | FM2A88X Extreme6+           | [bd7ed31b20](https://linux-hardware.org/?probe=bd7ed31b20) | Dec 21, 2022 |
| MSI           | X99A RAIDER                 | [3832e7e0af](https://linux-hardware.org/?probe=3832e7e0af) | Dec 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [cb70181c3a](https://linux-hardware.org/?probe=cb70181c3a) | Dec 21, 2022 |
| Dell          | 02YRK5 A02                  | [f5f6093483](https://linux-hardware.org/?probe=f5f6093483) | Dec 21, 2022 |
| Intel         | H81                         | [747dd5e27a](https://linux-hardware.org/?probe=747dd5e27a) | Dec 20, 2022 |
| ASRock        | Z790 Pro RS WiFi            | [d54c198ec8](https://linux-hardware.org/?probe=d54c198ec8) | Dec 20, 2022 |
| ASUSTek       | TUF Gaming B650M-PLUS       | [ef5cd85ef3](https://linux-hardware.org/?probe=ef5cd85ef3) | Dec 20, 2022 |
| Gigabyte      | GA-A75M-UD2H                | [f7e97a6c6c](https://linux-hardware.org/?probe=f7e97a6c6c) | Dec 20, 2022 |
| MSI           | X99A RAIDER                 | [8a7ee1147b](https://linux-hardware.org/?probe=8a7ee1147b) | Dec 20, 2022 |
| ASRock        | FM2A88X Extreme6+           | [9451dc3035](https://linux-hardware.org/?probe=9451dc3035) | Dec 20, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | [60dbf09ee4](https://linux-hardware.org/?probe=60dbf09ee4) | Dec 20, 2022 |
| Gigabyte      | H61M-USB3V                  | [3161a64c4b](https://linux-hardware.org/?probe=3161a64c4b) | Dec 19, 2022 |
| Gigabyte      | B85M-D3V-A                  | [6a964b9d6b](https://linux-hardware.org/?probe=6a964b9d6b) | Dec 19, 2022 |
| MSI           | Boston                      | [8587c9cf45](https://linux-hardware.org/?probe=8587c9cf45) | Dec 19, 2022 |
| Gigabyte      | X79-UP4                     | [900fd62aaf](https://linux-hardware.org/?probe=900fd62aaf) | Dec 19, 2022 |
| Gigabyte      | X79-UP4                     | [b34721e6cb](https://linux-hardware.org/?probe=b34721e6cb) | Dec 19, 2022 |
| Gigabyte      | A520M DS3H                  | [4251c08b5d](https://linux-hardware.org/?probe=4251c08b5d) | Dec 18, 2022 |
| Dell          | 0KRC95 A02                  | [e7bb083869](https://linux-hardware.org/?probe=e7bb083869) | Dec 18, 2022 |
| MSI           | Z87M GAMING                 | [bf27014217](https://linux-hardware.org/?probe=bf27014217) | Dec 18, 2022 |
| ASUSTek       | P8H77-V LE                  | [3f76e320c0](https://linux-hardware.org/?probe=3f76e320c0) | Dec 18, 2022 |
| Gigabyte      | B360M D3H-CF                | [fed4383ac0](https://linux-hardware.org/?probe=fed4383ac0) | Dec 18, 2022 |
| MSI           | B550-A PRO                  | [53c582a7f6](https://linux-hardware.org/?probe=53c582a7f6) | Dec 18, 2022 |
| MSI           | X99A RAIDER                 | [b4d6964157](https://linux-hardware.org/?probe=b4d6964157) | Dec 18, 2022 |
| ASRock        | FM2A88X Extreme6+           | [561aa4411a](https://linux-hardware.org/?probe=561aa4411a) | Dec 18, 2022 |
| ASUSTek       | PRIME B550M-K               | [0c496cdb01](https://linux-hardware.org/?probe=0c496cdb01) | Dec 17, 2022 |
| MSI           | A88XM-E35                   | [2e3cc90610](https://linux-hardware.org/?probe=2e3cc90610) | Dec 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [3db1266e41](https://linux-hardware.org/?probe=3db1266e41) | Dec 17, 2022 |
| ASUSTek       | P8H77-M LE                  | [d9eba2d52f](https://linux-hardware.org/?probe=d9eba2d52f) | Dec 17, 2022 |
| Gigabyte      | J1900M-D2P                  | [26ecfabc95](https://linux-hardware.org/?probe=26ecfabc95) | Dec 17, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [6dddb93518](https://linux-hardware.org/?probe=6dddb93518) | Dec 17, 2022 |
| ASUSTek       | TUF Z270 MARK 2             | [1bb7d1bffe](https://linux-hardware.org/?probe=1bb7d1bffe) | Dec 17, 2022 |
| ASRock        | FM2A88X Extreme6+           | [88d55eced8](https://linux-hardware.org/?probe=88d55eced8) | Dec 17, 2022 |
| MSI           | X99A RAIDER                 | [be93cca77c](https://linux-hardware.org/?probe=be93cca77c) | Dec 17, 2022 |
| MSI           | A88XM-E35                   | [f0efaa3c30](https://linux-hardware.org/?probe=f0efaa3c30) | Dec 17, 2022 |
| ASUSTek       | PRIME H670-PLUS D4          | [54132f7285](https://linux-hardware.org/?probe=54132f7285) | Dec 17, 2022 |
| HP            | 82F2 A01                    | [859d719a2a](https://linux-hardware.org/?probe=859d719a2a) | Dec 16, 2022 |
| Gigabyte      | Z77MX-D3H                   | [50ba321b50](https://linux-hardware.org/?probe=50ba321b50) | Dec 16, 2022 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | [f048f7fcdb](https://linux-hardware.org/?probe=f048f7fcdb) | Dec 16, 2022 |
| ASRock        | FM2A88X Extreme6+           | [04bbc083d7](https://linux-hardware.org/?probe=04bbc083d7) | Dec 16, 2022 |
| MSI           | X99A RAIDER                 | [9caae58821](https://linux-hardware.org/?probe=9caae58821) | Dec 16, 2022 |
| ASUSTek       | PRIME B550M-K               | [5148fddbd1](https://linux-hardware.org/?probe=5148fddbd1) | Dec 15, 2022 |
| ASUSTek       | PRIME B450M-K               | [a6dfbac9f9](https://linux-hardware.org/?probe=a6dfbac9f9) | Dec 15, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [83c2de0b09](https://linux-hardware.org/?probe=83c2de0b09) | Dec 15, 2022 |
| Lenovo        | 31900003 STD                | [81dea8d96e](https://linux-hardware.org/?probe=81dea8d96e) | Dec 15, 2022 |
| ASRock        | X670E Steel Legend          | [fec86201de](https://linux-hardware.org/?probe=fec86201de) | Dec 15, 2022 |
| MSI           | B550-A PRO B02              | [3a1ebe10f8](https://linux-hardware.org/?probe=3a1ebe10f8) | Dec 15, 2022 |
| ASRock        | FM2A88X Extreme6+           | [2e9fac9df4](https://linux-hardware.org/?probe=2e9fac9df4) | Dec 15, 2022 |
| MSI           | X99A RAIDER                 | [5a071587fb](https://linux-hardware.org/?probe=5a071587fb) | Dec 15, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [572f0231a5](https://linux-hardware.org/?probe=572f0231a5) | Dec 15, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [a0d17e1d50](https://linux-hardware.org/?probe=a0d17e1d50) | Dec 15, 2022 |
| ASUSTek       | PRIME H410M-E               | [cb7bfc231e](https://linux-hardware.org/?probe=cb7bfc231e) | Dec 15, 2022 |
| ASUSTek       | PRIME A320M-K               | [e647deca28](https://linux-hardware.org/?probe=e647deca28) | Dec 14, 2022 |
| Intel         | DQ67SW AAG12527-309         | [3b826b42e0](https://linux-hardware.org/?probe=3b826b42e0) | Dec 14, 2022 |
| Dell          | 0XJ8C4 A00                  | [c7ce3d7180](https://linux-hardware.org/?probe=c7ce3d7180) | Dec 14, 2022 |
| ASUSTek       | Z97-A                       | [fa4afa166d](https://linux-hardware.org/?probe=fa4afa166d) | Dec 14, 2022 |
| Dell          | 0XJ8C4 A00                  | [b136ecfff3](https://linux-hardware.org/?probe=b136ecfff3) | Dec 14, 2022 |
| ASUSTek       | Z97-A                       | [5cde0cdcc4](https://linux-hardware.org/?probe=5cde0cdcc4) | Dec 14, 2022 |
| HP            | 18E4                        | [fece9d45b4](https://linux-hardware.org/?probe=fece9d45b4) | Dec 14, 2022 |
| Dell          | 0M5DCD A00                  | [61c4e63c2d](https://linux-hardware.org/?probe=61c4e63c2d) | Dec 14, 2022 |
| ASUSTek       | PRIME X670E-PRO WIFI        | [b7fa78df7a](https://linux-hardware.org/?probe=b7fa78df7a) | Dec 14, 2022 |
| MSI           | X370 SLI PLUS               | [7c32d0f453](https://linux-hardware.org/?probe=7c32d0f453) | Dec 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [1ccd39b328](https://linux-hardware.org/?probe=1ccd39b328) | Dec 14, 2022 |
| ASRock        | FM2A88X Extreme6+           | [b20a4554c5](https://linux-hardware.org/?probe=b20a4554c5) | Dec 14, 2022 |
| MSI           | X99A RAIDER                 | [c8ffea5473](https://linux-hardware.org/?probe=c8ffea5473) | Dec 14, 2022 |
| Dell          | 0YJMC0 A01                  | [59de758672](https://linux-hardware.org/?probe=59de758672) | Dec 14, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [1800fc9efb](https://linux-hardware.org/?probe=1800fc9efb) | Dec 14, 2022 |
| Intel         | DB75EN AAG39650-400         | [72b3306c33](https://linux-hardware.org/?probe=72b3306c33) | Dec 13, 2022 |
| Gigabyte      | B550M DS3H                  | [bf6f0c23a2](https://linux-hardware.org/?probe=bf6f0c23a2) | Dec 13, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [466ea5976d](https://linux-hardware.org/?probe=466ea5976d) | Dec 13, 2022 |
| MSI           | PRO B650M-A WIFI            | [485240a680](https://linux-hardware.org/?probe=485240a680) | Dec 13, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [469dfe26a6](https://linux-hardware.org/?probe=469dfe26a6) | Dec 13, 2022 |
| MSI           | MEG B550 UNIFY              | [e9a996b54a](https://linux-hardware.org/?probe=e9a996b54a) | Dec 12, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [9b02acceb3](https://linux-hardware.org/?probe=9b02acceb3) | Dec 12, 2022 |
| Gigabyte      | J1900M-D2P                  | [8111a18c7c](https://linux-hardware.org/?probe=8111a18c7c) | Dec 12, 2022 |
| ASRock        | X79 Extreme6                | [8ef84e95c1](https://linux-hardware.org/?probe=8ef84e95c1) | Dec 11, 2022 |
| Gigabyte      | H370M DS3H-CF               | [8c1901e5d6](https://linux-hardware.org/?probe=8c1901e5d6) | Dec 11, 2022 |
| ASRock        | 760GM-HD                    | [03fdf6453b](https://linux-hardware.org/?probe=03fdf6453b) | Dec 11, 2022 |
| MSI           | B450M PRO-VDH MAX           | [6bf96cf0fc](https://linux-hardware.org/?probe=6bf96cf0fc) | Dec 11, 2022 |
| Intel         | DB75EN AAG39650-400         | [01decbbb6d](https://linux-hardware.org/?probe=01decbbb6d) | Dec 10, 2022 |
| ASUSTek       | P5K Deluxe                  | [6f97813144](https://linux-hardware.org/?probe=6f97813144) | Dec 10, 2022 |
| ASUSTek       | PRIME H310I-PLUS R2.0       | [5749b67534](https://linux-hardware.org/?probe=5749b67534) | Dec 10, 2022 |
| Lenovo        | ThinkStation S30 056851U    | [8c7b6cfca0](https://linux-hardware.org/?probe=8c7b6cfca0) | Dec 10, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [4f1f6fde97](https://linux-hardware.org/?probe=4f1f6fde97) | Dec 10, 2022 |
| MSI           | H97M-G43                    | [c62f2a0b49](https://linux-hardware.org/?probe=c62f2a0b49) | Dec 10, 2022 |
| ASUSTek       | PRIME X670E-PRO WIFI        | [a9351a042f](https://linux-hardware.org/?probe=a9351a042f) | Dec 10, 2022 |
| Gigabyte      | A520I AC                    | [39d35f8e37](https://linux-hardware.org/?probe=39d35f8e37) | Dec 10, 2022 |
| MSI           | PRO Z690-A                  | [3e5339eeae](https://linux-hardware.org/?probe=3e5339eeae) | Dec 10, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [7d6b3699e7](https://linux-hardware.org/?probe=7d6b3699e7) | Dec 10, 2022 |
| ASRock        | X670E Steel Legend          | [11df680f78](https://linux-hardware.org/?probe=11df680f78) | Dec 09, 2022 |
| Gigabyte      | G31_ICH7                    | [d433eed3f1](https://linux-hardware.org/?probe=d433eed3f1) | Dec 09, 2022 |
| Dell          | 0GU083 A00                  | [1f3f73a41c](https://linux-hardware.org/?probe=1f3f73a41c) | Dec 09, 2022 |
| Gigabyte      | Z77MX-D3H                   | [b77b64cc48](https://linux-hardware.org/?probe=b77b64cc48) | Dec 09, 2022 |
| ASRock        | FM2A88X Extreme6+           | [bcb55a7e4c](https://linux-hardware.org/?probe=bcb55a7e4c) | Dec 09, 2022 |
| MSI           | X99A RAIDER                 | [ea91fc57ae](https://linux-hardware.org/?probe=ea91fc57ae) | Dec 09, 2022 |
| Gigabyte      | B550 AORUS ELITE            | [b80c17a638](https://linux-hardware.org/?probe=b80c17a638) | Dec 09, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [bddf744d58](https://linux-hardware.org/?probe=bddf744d58) | Dec 09, 2022 |
| MSI           | X470 GAMING PRO CARBON      | [a875eabf3d](https://linux-hardware.org/?probe=a875eabf3d) | Dec 09, 2022 |
| Apple         | Mac-F221BEC8                | [6ab58fe686](https://linux-hardware.org/?probe=6ab58fe686) | Dec 09, 2022 |
| Apple         | Mac-F221BEC8                | [07e4a8072a](https://linux-hardware.org/?probe=07e4a8072a) | Dec 09, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [42f14a38dd](https://linux-hardware.org/?probe=42f14a38dd) | Dec 09, 2022 |
| ASRock        | 970 Extreme3 R2.0           | [d52b5053b2](https://linux-hardware.org/?probe=d52b5053b2) | Dec 09, 2022 |
| Gigabyte      | A320M-S2H-CF                | [5544994d11](https://linux-hardware.org/?probe=5544994d11) | Dec 08, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [527789fc7d](https://linux-hardware.org/?probe=527789fc7d) | Dec 08, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [172c6c1300](https://linux-hardware.org/?probe=172c6c1300) | Dec 08, 2022 |
| MSI           | X370 XPOWER GAMING TITAN... | [cb246bfc71](https://linux-hardware.org/?probe=cb246bfc71) | Dec 08, 2022 |
| MSI           | X370 XPOWER GAMING TITAN... | [1b0ddaccb8](https://linux-hardware.org/?probe=1b0ddaccb8) | Dec 08, 2022 |
| Shenzhen M... | HX90G                       | [83a892b661](https://linux-hardware.org/?probe=83a892b661) | Dec 08, 2022 |
| Gigabyte      | A520I AC                    | [cbdee77af1](https://linux-hardware.org/?probe=cbdee77af1) | Dec 08, 2022 |
| MSI           | H97M-G43                    | [53754acfcb](https://linux-hardware.org/?probe=53754acfcb) | Dec 08, 2022 |
| ASRock        | FM2A88X Extreme6+           | [e40a7efd61](https://linux-hardware.org/?probe=e40a7efd61) | Dec 08, 2022 |
| Gigabyte      | G41MT-S2                    | [f69d93aece](https://linux-hardware.org/?probe=f69d93aece) | Dec 08, 2022 |
| MSI           | X99A RAIDER                 | [2d35fb5bbb](https://linux-hardware.org/?probe=2d35fb5bbb) | Dec 08, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [551e0142a8](https://linux-hardware.org/?probe=551e0142a8) | Dec 08, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | [6f715ffe60](https://linux-hardware.org/?probe=6f715ffe60) | Dec 08, 2022 |
| Gigabyte      | B450M AORUS ELITE           | [7f45781139](https://linux-hardware.org/?probe=7f45781139) | Dec 08, 2022 |
| MSI           | B550-A PRO                  | [804710787d](https://linux-hardware.org/?probe=804710787d) | Dec 08, 2022 |
| Gigabyte      | EP45-DS3P                   | [6844d4578b](https://linux-hardware.org/?probe=6844d4578b) | Dec 07, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [61a9d5f84c](https://linux-hardware.org/?probe=61a9d5f84c) | Dec 07, 2022 |
| ASRock        | FM2A88X Extreme6+           | [d655b34178](https://linux-hardware.org/?probe=d655b34178) | Dec 07, 2022 |
| Gigabyte      | X570 GAMING X               | [811b0e1a71](https://linux-hardware.org/?probe=811b0e1a71) | Dec 06, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [5be32d156a](https://linux-hardware.org/?probe=5be32d156a) | Dec 06, 2022 |
| ASUSTek       | PRIME B450M-A               | [f8e78fbf31](https://linux-hardware.org/?probe=f8e78fbf31) | Dec 06, 2022 |
| HP            | 8767 A                      | [1d4dc77fa3](https://linux-hardware.org/?probe=1d4dc77fa3) | Dec 06, 2022 |
| Acer          | FMP55                       | [78aabc71bf](https://linux-hardware.org/?probe=78aabc71bf) | Dec 05, 2022 |
| Unknown       | HX90                        | [9f3f9dec0b](https://linux-hardware.org/?probe=9f3f9dec0b) | Dec 05, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [57b6a24933](https://linux-hardware.org/?probe=57b6a24933) | Dec 05, 2022 |
| HP            | 8860 A                      | [23fde1381a](https://linux-hardware.org/?probe=23fde1381a) | Dec 05, 2022 |
| Acer          | Aspire TC-885 V:1.1         | [73d037e031](https://linux-hardware.org/?probe=73d037e031) | Dec 05, 2022 |
| MSI           | X370 SLI PLUS               | [e6941ba491](https://linux-hardware.org/?probe=e6941ba491) | Dec 05, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [ce36bcdf8b](https://linux-hardware.org/?probe=ce36bcdf8b) | Dec 05, 2022 |
| Dell          | 0M017G A00                  | [d6b5487094](https://linux-hardware.org/?probe=d6b5487094) | Dec 05, 2022 |
| ASUSTek       | P8Z77-V PRO                 | [b5c74add87](https://linux-hardware.org/?probe=b5c74add87) | Dec 04, 2022 |
| Gigabyte      | B650E AORUS MASTER se2      | [101ea2715c](https://linux-hardware.org/?probe=101ea2715c) | Dec 04, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [db7cd6f0dc](https://linux-hardware.org/?probe=db7cd6f0dc) | Dec 04, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [cff58a3529](https://linux-hardware.org/?probe=cff58a3529) | Dec 04, 2022 |
| ASRock        | X300-ITX                    | [77d8c41481](https://linux-hardware.org/?probe=77d8c41481) | Dec 04, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [d6829bfb6d](https://linux-hardware.org/?probe=d6829bfb6d) | Dec 04, 2022 |
| HP            | 158B                        | [5652b24e0d](https://linux-hardware.org/?probe=5652b24e0d) | Dec 04, 2022 |
| HP            | 158B                        | [015085e084](https://linux-hardware.org/?probe=015085e084) | Dec 04, 2022 |
| MSI           | X470 GAMING PRO CARBON      | [0a626fffe5](https://linux-hardware.org/?probe=0a626fffe5) | Dec 04, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | [cbb4692837](https://linux-hardware.org/?probe=cbb4692837) | Dec 04, 2022 |
| Gigabyte      | GA-970A-DS3                 | [8c06e98cf8](https://linux-hardware.org/?probe=8c06e98cf8) | Dec 03, 2022 |
| Dell          | 0N826N A02                  | [e9f0634dd6](https://linux-hardware.org/?probe=e9f0634dd6) | Dec 03, 2022 |
| ASUSTek       | P8H67-M PRO                 | [05131558b5](https://linux-hardware.org/?probe=05131558b5) | Dec 03, 2022 |
| ASUSTek       | P8H67-M PRO                 | [9fcc18738b](https://linux-hardware.org/?probe=9fcc18738b) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [80bba2043d](https://linux-hardware.org/?probe=80bba2043d) | Dec 03, 2022 |
| Unknown       | HX90                        | [40847bd89b](https://linux-hardware.org/?probe=40847bd89b) | Dec 03, 2022 |
| MSI           | B450I GAMING PLUS AC        | [9b1ef89e7e](https://linux-hardware.org/?probe=9b1ef89e7e) | Dec 02, 2022 |
| HP            | 0A98h                       | [e1413607aa](https://linux-hardware.org/?probe=e1413607aa) | Dec 02, 2022 |
| MSI           | X99A RAIDER                 | [8b85688e36](https://linux-hardware.org/?probe=8b85688e36) | Dec 02, 2022 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | [07a15db1a6](https://linux-hardware.org/?probe=07a15db1a6) | Dec 02, 2022 |
| Itautec       | ST 4265                     | [6c18ee8479](https://linux-hardware.org/?probe=6c18ee8479) | Dec 02, 2022 |
| Itautec       | ST 4265                     | [d31a6b4c0f](https://linux-hardware.org/?probe=d31a6b4c0f) | Dec 01, 2022 |
| Positivo      | POS-PIQ57BQA                | [8403658c27](https://linux-hardware.org/?probe=8403658c27) | Dec 01, 2022 |
| MSI           | X470 GAMING PRO CARBON      | [9cd70143b5](https://linux-hardware.org/?probe=9cd70143b5) | Dec 01, 2022 |
| HP            | 0A98h                       | [f2b620c220](https://linux-hardware.org/?probe=f2b620c220) | Dec 01, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [42932dd5fd](https://linux-hardware.org/?probe=42932dd5fd) | Dec 01, 2022 |
| ASUSTek       | PRIME X370-PRO              | [aa87dfdc13](https://linux-hardware.org/?probe=aa87dfdc13) | Dec 01, 2022 |
| MSI           | X99A RAIDER                 | [0e87a76042](https://linux-hardware.org/?probe=0e87a76042) | Dec 01, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [8a4813eec4](https://linux-hardware.org/?probe=8a4813eec4) | Nov 30, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [80b8b349f8](https://linux-hardware.org/?probe=80b8b349f8) | Nov 30, 2022 |
| Gigabyte      | X570 GAMING X               | [7ea2de1a3b](https://linux-hardware.org/?probe=7ea2de1a3b) | Nov 30, 2022 |
| Unknown       | X99H                        | [b9e2236de7](https://linux-hardware.org/?probe=b9e2236de7) | Nov 30, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [a6a71120f2](https://linux-hardware.org/?probe=a6a71120f2) | Nov 30, 2022 |
| GALAX         | B365M G10b                  | [9eabacd766](https://linux-hardware.org/?probe=9eabacd766) | Nov 30, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [da83c13da3](https://linux-hardware.org/?probe=da83c13da3) | Nov 30, 2022 |
| GALAX         | B365M G10b                  | [9f7438d5a3](https://linux-hardware.org/?probe=9f7438d5a3) | Nov 30, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [459c2ba743](https://linux-hardware.org/?probe=459c2ba743) | Nov 30, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| Fedora 36 | 676      | 16.68%  |
| Fedora 33 | 566      | 13.96%  |
| Fedora 37 | 565      | 13.94%  |
| Fedora 35 | 534      | 13.18%  |
| Fedora 34 | 518      | 12.78%  |
| Fedora 32 | 518      | 12.78%  |
| Fedora 31 | 343      | 8.46%   |
| Fedora 30 | 132      | 3.26%   |
| Fedora 38 | 94       | 2.32%   |
| Fedora 29 | 75       | 1.85%   |
| Fedora 28 | 14       | 0.35%   |
| Fedora 27 | 9        | 0.22%   |
| Fedora 25 | 2        | 0.05%   |
| Fedora 24 | 2        | 0.05%   |
| Fedora 4  | 1        | 0.02%   |
| Fedora 39 | 1        | 0.02%   |
| Fedora 21 | 1        | 0.02%   |
| Fedora 17 | 1        | 0.02%   |
| Fedora 14 | 1        | 0.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Fedora | 3495     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Desktops | Percent |
|-------------------------|----------|---------|
| 5.9.16-200.fc33.x86_64  | 58       | 1.25%   |
| 5.16.18-200.fc35.x86_64 | 57       | 1.23%   |
| 5.17.5-300.fc36.x86_64  | 49       | 1.05%   |
| 6.0.15-300.fc37.x86_64  | 45       | 0.97%   |
| 6.0.12-300.fc37.x86_64  | 44       | 0.95%   |
| 5.18.13-200.fc36.x86_64 | 42       | 0.9%    |
| 5.19.16-200.fc36.x86_64 | 40       | 0.86%   |
| 5.13.12-200.fc34.x86_64 | 39       | 0.84%   |
| 5.14.10-300.fc35.x86_64 | 37       | 0.8%    |
| 6.0.7-301.fc37.x86_64   | 35       | 0.75%   |
| 6.0.5-200.fc36.x86_64   | 35       | 0.75%   |
| 5.11.12-300.fc34.x86_64 | 35       | 0.75%   |
| 6.1.18-200.fc37.x86_64  | 33       | 0.71%   |
| 5.8.4-200.fc32.x86_64   | 33       | 0.71%   |
| 5.8.15-301.fc33.x86_64  | 33       | 0.71%   |
| 5.18.16-200.fc36.x86_64 | 32       | 0.69%   |
| 6.2.11-300.fc38.x86_64  | 31       | 0.67%   |
| 6.0.11-300.fc37.x86_64  | 31       | 0.67%   |
| 5.19.9-200.fc36.x86_64  | 31       | 0.67%   |
| 5.18.11-200.fc36.x86_64 | 31       | 0.67%   |
| 5.6.19-300.fc32.x86_64  | 30       | 0.64%   |
| 5.18.5-200.fc36.x86_64  | 30       | 0.64%   |
| 5.12.13-300.fc34.x86_64 | 30       | 0.64%   |
| 5.8.18-300.fc33.x86_64  | 29       | 0.62%   |
| 5.15.6-200.fc35.x86_64  | 29       | 0.62%   |
| 5.8.16-300.fc33.x86_64  | 28       | 0.6%    |
| 6.0.9-300.fc37.x86_64   | 27       | 0.58%   |
| 6.0.8-300.fc37.x86_64   | 27       | 0.58%   |
| 5.9.11-200.fc33.x86_64  | 26       | 0.56%   |
| 5.3.16-300.fc31.x86_64  | 26       | 0.56%   |
| 6.1.14-200.fc37.x86_64  | 25       | 0.54%   |
| 5.7.10-201.fc32.x86_64  | 25       | 0.54%   |
| 5.16.16-200.fc35.x86_64 | 25       | 0.54%   |
| 5.11.11-200.fc33.x86_64 | 25       | 0.54%   |
| 5.9.8-200.fc33.x86_64   | 24       | 0.52%   |
| 5.11.16-300.fc34.x86_64 | 24       | 0.52%   |
| 5.19.6-200.fc36.x86_64  | 23       | 0.49%   |
| 5.17.6-300.fc36.x86_64  | 23       | 0.49%   |
| 5.14.9-200.fc34.x86_64  | 23       | 0.49%   |
| 5.12.8-300.fc34.x86_64  | 23       | 0.49%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.9.16  | 67       | 1.44%   |
| 5.17.5  | 65       | 1.4%    |
| 5.16.18 | 65       | 1.4%    |
| 5.19.16 | 59       | 1.27%   |
| 5.8.15  | 53       | 1.14%   |
| 6.0.12  | 51       | 1.1%    |
| 6.0.15  | 50       | 1.08%   |
| 6.0.7   | 48       | 1.03%   |
| 5.8.18  | 47       | 1.01%   |
| 5.18.13 | 43       | 0.92%   |
| 5.8.16  | 40       | 0.86%   |
| 5.13.12 | 40       | 0.86%   |
| 6.0.8   | 39       | 0.84%   |
| 5.19.9  | 39       | 0.84%   |
| 5.14.10 | 39       | 0.84%   |
| 6.0.5   | 38       | 0.82%   |
| 6.0.9   | 37       | 0.8%    |
| 5.11.12 | 37       | 0.8%    |
| 5.11.11 | 37       | 0.8%    |
| 6.1.18  | 36       | 0.77%   |
| 5.18.5  | 35       | 0.75%   |
| 6.2.11  | 34       | 0.73%   |
| 6.0.11  | 34       | 0.73%   |
| 5.8.4   | 33       | 0.71%   |
| 5.18.16 | 33       | 0.71%   |
| 5.14.18 | 33       | 0.71%   |
| 5.18.11 | 32       | 0.69%   |
| 5.12.13 | 32       | 0.69%   |
| 5.6.19  | 31       | 0.67%   |
| 6.0.10  | 30       | 0.65%   |
| 5.12.8  | 30       | 0.65%   |
| 5.15.6  | 29       | 0.62%   |
| 6.1.14  | 28       | 0.6%    |
| 5.9.11  | 28       | 0.6%    |
| 5.19.6  | 28       | 0.6%    |
| 5.17.6  | 28       | 0.6%    |
| 5.14.9  | 28       | 0.6%    |
| 6.2.9   | 27       | 0.58%   |
| 6.2.7   | 27       | 0.58%   |
| 5.6.6   | 27       | 0.58%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.0     | 352      | 7.99%   |
| 5.8     | 307      | 6.96%   |
| 5.11    | 257      | 5.83%   |
| 5.19    | 256      | 5.81%   |
| 5.18    | 252      | 5.72%   |
| 5.17    | 247      | 5.6%    |
| 6.1     | 233      | 5.29%   |
| 5.16    | 224      | 5.08%   |
| 5.9     | 209      | 4.74%   |
| 5.10    | 206      | 4.67%   |
| 5.14    | 204      | 4.63%   |
| 5.6     | 195      | 4.42%   |
| 5.13    | 191      | 4.33%   |
| 5.15    | 179      | 4.06%   |
| 5.12    | 176      | 3.99%   |
| 5.7     | 171      | 3.88%   |
| 6.2     | 170      | 3.86%   |
| 5.4     | 135      | 3.06%   |
| 5.5     | 121      | 2.75%   |
| 5.3     | 115      | 2.61%   |
| 5.2     | 55       | 1.25%   |
| 5.0     | 48       | 1.09%   |
| 5.1     | 25       | 0.57%   |
| 4.19    | 22       | 0.5%    |
| 4.18    | 19       | 0.43%   |
| 4.20    | 18       | 0.41%   |
| 4.16    | 5        | 0.11%   |
| 4.15    | 3        | 0.07%   |
| 4.17    | 2        | 0.05%   |
| 4.13    | 2        | 0.05%   |
| 4.11    | 2        | 0.05%   |
| 6.3     | 1        | 0.02%   |
| 4.14    | 1        | 0.02%   |
| 4.1     | 1        | 0.02%   |
| 3.9     | 1        | 0.02%   |
| 3.17    | 1        | 0.02%   |
| 2.6.35  | 1        | 0.02%   |
| Unknown | 1        | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 3492     | 99.89%  |
| i686    | 3        | 0.09%   |
| Unknown | 1        | 0.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| GNOME                        | 2388     | 66.31%  |
| KDE5                         | 469      | 13.02%  |
| Unknown                      | 259      | 7.19%   |
| KDE                          | 116      | 3.22%   |
| XFCE                         | 90       | 2.5%    |
| X-Cinnamon                   | 69       | 1.92%   |
| MATE                         | 60       | 1.67%   |
| Cinnamon                     | 59       | 1.64%   |
| GNOME Classic                | 27       | 0.75%   |
| LXQt                         | 11       | 0.31%   |
| Deepin                       | 11       | 0.31%   |
| LXDE                         | 10       | 0.28%   |
| i3                           | 8        | 0.22%   |
| KDE4                         | 6        | 0.17%   |
| awesome                      | 3        | 0.08%   |
| sway                         | 2        | 0.06%   |
| qtile                        | 2        | 0.06%   |
| openbox                      | 2        | 0.06%   |
| DWM                          | 2        | 0.06%   |
| bspwm                        | 2        | 0.06%   |
| Pantheon                     | 1        | 0.03%   |
| NsCDE                        | 1        | 0.03%   |
| GNUstep                      | 1        | 0.03%   |
| GNOME Flashback              | 1        | 0.03%   |
| ${XDG_CURRENT_DESKTOP:-sway} | 1        | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 1852     | 50.35%  |
| X11     | 1561     | 42.44%  |
| Unknown | 137      | 3.72%   |
| Tty     | 123      | 3.34%   |
| Web     | 5        | 0.14%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 2002     | 55.63%  |
| GDM     | 1054     | 29.29%  |
| SDDM    | 291      | 8.09%   |
| LightDM | 162      | 4.5%    |
| TDM     | 73       | 2.03%   |
| XDM     | 7        | 0.19%   |
| KDM     | 7        | 0.19%   |
| LXDM    | 2        | 0.06%   |
| SLiM    | 1        | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 1651     | 46.31%  |
| en_GB   | 248      | 6.96%   |
| Unknown | 248      | 6.96%   |
| pt_BR   | 176      | 4.94%   |
| ru_RU   | 173      | 4.85%   |
| de_DE   | 157      | 4.4%    |
| fr_FR   | 114      | 3.2%    |
| en_AU   | 104      | 2.92%   |
| en_CA   | 103      | 2.89%   |
| it_IT   | 76       | 2.13%   |
| pl_PL   | 55       | 1.54%   |
| es_ES   | 51       | 1.43%   |
| cs_CZ   | 26       | 0.73%   |
| en_IN   | 23       | 0.65%   |
| en_NZ   | 21       | 0.59%   |
| es_MX   | 20       | 0.56%   |
| es_AR   | 15       | 0.42%   |
| ja_JP   | 14       | 0.39%   |
| nl_BE   | 13       | 0.36%   |
| fi_FI   | 13       | 0.36%   |
| en_IE   | 13       | 0.36%   |
| es_CO   | 12       | 0.34%   |
| sv_SE   | 11       | 0.31%   |
| nl_NL   | 11       | 0.31%   |
| uk_UA   | 10       | 0.28%   |
| tr_TR   | 10       | 0.28%   |
| de_AT   | 10       | 0.28%   |
| C       | 10       | 0.28%   |
| hu_HU   | 9        | 0.25%   |
| zh_CN   | 8        | 0.22%   |
| ru_UA   | 8        | 0.22%   |
| fr_CH   | 8        | 0.22%   |
| es_CL   | 8        | 0.22%   |
| pt_PT   | 7        | 0.2%    |
| ko_KR   | 7        | 0.2%    |
| en_DK   | 7        | 0.2%    |
| sk_SK   | 6        | 0.17%   |
| nb_NO   | 5        | 0.14%   |
| fr_CA   | 5        | 0.14%   |
| fr_BE   | 5        | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 2249     | 63.23%  |
| BIOS | 1308     | 36.77%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Desktops | Percent |
|---------------------|----------|---------|
| Btrfs               | 1885     | 52.49%  |
| Ext4                | 1387     | 38.62%  |
| Xfs                 | 171      | 4.76%   |
| Unknown             | 132      | 3.68%   |
| Overlay             | 6        | 0.17%   |
| Ext3                | 4        | 0.11%   |
| Zfs                 | 3        | 0.08%   |
| F2fs                | 2        | 0.06%   |
| Fuse.fuse-overlayfs | 1        | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1955     | 54.2%   |
| GPT     | 1287     | 35.68%  |
| MBR     | 365      | 10.12%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 3030     | 84.57%  |
| Yes       | 553      | 15.43%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 2807     | 78.83%  |
| Yes       | 754      | 21.17%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 1031     | 29.5%   |
| Gigabyte Technology | 689      | 19.71%  |
| MSI                 | 521      | 14.91%  |
| ASRock              | 361      | 10.33%  |
| Dell                | 242      | 6.92%   |
| Hewlett-Packard     | 184      | 5.26%   |
| Lenovo              | 100      | 2.86%   |
| Intel               | 57       | 1.63%   |
| Unknown             | 41       | 1.17%   |
| Acer                | 36       | 1.03%   |
| Pegatron            | 19       | 0.54%   |
| Biostar             | 17       | 0.49%   |
| ECS                 | 16       | 0.46%   |
| BESSTAR Tech        | 15       | 0.43%   |
| Huanan              | 14       | 0.4%    |
| Fujitsu             | 12       | 0.34%   |
| Supermicro          | 11       | 0.31%   |
| Foxconn             | 11       | 0.31%   |
| Shuttle             | 8        | 0.23%   |
| Apple               | 8        | 0.23%   |
| Alienware           | 8        | 0.23%   |
| Positivo            | 7        | 0.2%    |
| PCWare              | 5        | 0.14%   |
| Medion              | 5        | 0.14%   |
| System76            | 4        | 0.11%   |
| Packard Bell        | 4        | 0.11%   |
| Itautec             | 4        | 0.11%   |
| EVGA                | 4        | 0.11%   |
| AZW                 | 4        | 0.11%   |
| ZOTAC               | 3        | 0.09%   |
| MACHINIST           | 3        | 0.09%   |
| eMachines           | 3        | 0.09%   |
| AMI                 | 3        | 0.09%   |
| ABIT                | 3        | 0.09%   |
| XFX                 | 2        | 0.06%   |
| OEM                 | 2        | 0.06%   |
| NZXT                | 2        | 0.06%   |
| JINGSHA             | 2        | 0.06%   |
| Google              | 2        | 0.06%   |
| Gateway             | 2        | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| ASUS All Series                | 106      | 3.03%   |
| Unknown                        | 44       | 1.26%   |
| MSI MS-7C37                    | 40       | 1.14%   |
| ASUS TUF Gaming X570-PLUS      | 28       | 0.8%    |
| Gigabyte B450M DS3H            | 23       | 0.66%   |
| MSI MS-7C02                    | 21       | 0.6%    |
| MSI MS-7A38                    | 21       | 0.6%    |
| Dell OptiPlex 7010             | 21       | 0.6%    |
| MSI MS-7B86                    | 18       | 0.52%   |
| MSI MS-7C56                    | 16       | 0.46%   |
| ASUS ROG STRIX B550-F GAMING   | 16       | 0.46%   |
| MSI MS-7C91                    | 15       | 0.43%   |
| MSI MS-7B79                    | 15       | 0.43%   |
| Dell OptiPlex 9020             | 15       | 0.43%   |
| ASUS PRIME X370-PRO            | 15       | 0.43%   |
| ASUS ROG STRIX X570-F GAMING   | 14       | 0.4%    |
| ASUS ROG STRIX B450-F GAMING   | 14       | 0.4%    |
| MSI MS-7C84                    | 13       | 0.37%   |
| Gigabyte 970A-DS3P             | 13       | 0.37%   |
| ASUS TUF Gaming B550M-PLUS     | 13       | 0.37%   |
| ASUS PRIME A320M-K             | 13       | 0.37%   |
| MSI MS-7B89                    | 12       | 0.34%   |
| MSI MS-7A34                    | 12       | 0.34%   |
| Gigabyte B450 AORUS ELITE      | 12       | 0.34%   |
| Gigabyte A320M-S2H             | 12       | 0.34%   |
| ASUS ROG STRIX X570-E GAMING   | 12       | 0.34%   |
| ASUS ROG STRIX B550-I GAMING   | 12       | 0.34%   |
| ASUS PRIME X470-PRO            | 12       | 0.34%   |
| ASRock B450M Pro4              | 12       | 0.34%   |
| Gigabyte X570 I AORUS PRO WIFI | 11       | 0.31%   |
| Gigabyte B450 AORUS M          | 11       | 0.31%   |
| Dell OptiPlex 3020             | 11       | 0.31%   |
| ASUS ROG CROSSHAIR VII HERO    | 11       | 0.31%   |
| MSI MS-7C52                    | 10       | 0.29%   |
| Gigabyte X570 AORUS MASTER     | 10       | 0.29%   |
| Gigabyte X570 AORUS ELITE      | 10       | 0.29%   |
| Gigabyte AB350-Gaming 3        | 10       | 0.29%   |
| ASUS Z170-A                    | 10       | 0.29%   |
| ASUS Z170 PRO GAMING           | 10       | 0.29%   |
| ASUS TUF Gaming B550-PLUS      | 10       | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ASUS PRIME         | 207      | 5.92%   |
| ASUS ROG           | 206      | 5.89%   |
| Dell OptiPlex      | 128      | 3.66%   |
| ASUS TUF           | 117      | 3.35%   |
| ASUS All           | 106      | 3.03%   |
| Gigabyte X570      | 63       | 1.8%    |
| Lenovo ThinkCentre | 55       | 1.57%   |
| Dell Precision     | 45       | 1.29%   |
| Unknown            | 44       | 1.26%   |
| HP Compaq          | 43       | 1.23%   |
| Gigabyte B450      | 43       | 1.23%   |
| MSI MS-7C37        | 40       | 1.14%   |
| Gigabyte B450M     | 37       | 1.06%   |
| HP EliteDesk       | 33       | 0.94%   |
| Dell Inspiron      | 26       | 0.74%   |
| Dell XPS           | 25       | 0.72%   |
| ASRock B450M       | 25       | 0.72%   |
| Acer Aspire        | 25       | 0.72%   |
| ASRock X570        | 24       | 0.69%   |
| Gigabyte B550      | 23       | 0.66%   |
| HP ProDesk         | 22       | 0.63%   |
| MSI MS-7C02        | 21       | 0.6%    |
| MSI MS-7A38        | 21       | 0.6%    |
| MSI MS-7B86        | 18       | 0.52%   |
| ASRock B450        | 18       | 0.52%   |
| ASUS P8Z77-V       | 17       | 0.49%   |
| MSI MS-7C56        | 16       | 0.46%   |
| MSI MS-7C91        | 15       | 0.43%   |
| MSI MS-7B79        | 15       | 0.43%   |
| Gigabyte B550M     | 15       | 0.43%   |
| ASUS M5A78L-M      | 15       | 0.43%   |
| Gigabyte Z390      | 14       | 0.4%    |
| Gigabyte A320M-S2H | 14       | 0.4%    |
| Gigabyte 970A-DS3P | 14       | 0.4%    |
| ASUS SABERTOOTH    | 14       | 0.4%    |
| ASUS Maximus       | 14       | 0.4%    |
| ASUS M5A97         | 14       | 0.4%    |
| MSI MS-7C84        | 13       | 0.37%   |
| ASUS ProArt        | 13       | 0.37%   |
| ASUS P8Z68-V       | 13       | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 478      | 13.68%  |
| 2019    | 422      | 12.07%  |
| 2020    | 362      | 10.36%  |
| 2017    | 303      | 8.67%   |
| 2012    | 272      | 7.78%   |
| 2013    | 245      | 7.01%   |
| 2014    | 223      | 6.38%   |
| 2021    | 202      | 5.78%   |
| 2011    | 179      | 5.12%   |
| 2015    | 173      | 4.95%   |
| 2016    | 159      | 4.55%   |
| 2009    | 117      | 3.35%   |
| 2010    | 116      | 3.32%   |
| 2022    | 87       | 2.49%   |
| 2008    | 86       | 2.46%   |
| 2007    | 38       | 1.09%   |
| 2006    | 19       | 0.54%   |
| 2023    | 7        | 0.2%    |
| 2005    | 4        | 0.11%   |
| Unknown | 3        | 0.09%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 3495     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 3300     | 93.56%  |
| Enabled  | 227      | 6.44%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 3493     | 99.94%  |
| Yes  | 2        | 0.06%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 1094     | 30.54%  |
| 32.01-64.0      | 819      | 22.86%  |
| 8.01-16.0       | 610      | 17.03%  |
| 4.01-8.0        | 391      | 10.92%  |
| 64.01-256.0     | 274      | 7.65%   |
| 3.01-4.0        | 222      | 6.2%    |
| 24.01-32.0      | 128      | 3.57%   |
| 1.01-2.0        | 20       | 0.56%   |
| 2.01-3.0        | 17       | 0.47%   |
| Unknown         | 4        | 0.11%   |
| More than 256.0 | 2        | 0.06%   |
| 0.51-1.0        | 1        | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 1135     | 27.89%  |
| 2.01-3.0    | 1019     | 25.04%  |
| 3.01-4.0    | 799      | 19.64%  |
| 1.01-2.0    | 549      | 13.49%  |
| 8.01-16.0   | 374      | 9.19%   |
| 16.01-24.0  | 71       | 1.74%   |
| 0.51-1.0    | 57       | 1.4%    |
| 24.01-32.0  | 29       | 0.71%   |
| 32.01-64.0  | 14       | 0.34%   |
| 0.01-0.5    | 13       | 0.32%   |
| Unknown     | 6        | 0.15%   |
| 64.01-256.0 | 3        | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 1141     | 30.75%  |
| 1      | 1006     | 27.12%  |
| 3      | 746      | 20.11%  |
| 4      | 400      | 10.78%  |
| 5      | 197      | 5.31%   |
| 6      | 100      | 2.7%    |
| 7      | 51       | 1.37%   |
| 8      | 25       | 0.67%   |
| 9      | 12       | 0.32%   |
| 0      | 10       | 0.27%   |
| 10     | 6        | 0.16%   |
| 11     | 5        | 0.13%   |
| 12     | 3        | 0.08%   |
| 15     | 2        | 0.05%   |
| 14     | 2        | 0.05%   |
| 27     | 1        | 0.03%   |
| 24     | 1        | 0.03%   |
| 18     | 1        | 0.03%   |
| 13     | 1        | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2276     | 64.18%  |
| Yes       | 1270     | 35.82%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 3474     | 99.37%  |
| No        | 22       | 0.63%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1863     | 52.46%  |
| Yes       | 1688     | 47.54%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2092     | 58.65%  |
| Yes       | 1475     | 41.35%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 837      | 23.81%  |
| Germany     | 269      | 7.65%   |
| Brazil      | 254      | 7.23%   |
| Russia      | 230      | 6.54%   |
| Canada      | 146      | 4.15%   |
| UK          | 139      | 3.95%   |
| France      | 135      | 3.84%   |
| Italy       | 125      | 3.56%   |
| Australia   | 114      | 3.24%   |
| Poland      | 102      | 2.9%    |
| Spain       | 86       | 2.45%   |
| Sweden      | 59       | 1.68%   |
| Netherlands | 56       | 1.59%   |
| India       | 53       | 1.51%   |
| Czechia     | 50       | 1.42%   |
| Switzerland | 47       | 1.34%   |
| Belgium     | 40       | 1.14%   |
| Ukraine     | 39       | 1.11%   |
| Finland     | 36       | 1.02%   |
| Mexico      | 34       | 0.97%   |
| Austria     | 34       | 0.97%   |
| Romania     | 31       | 0.88%   |
| Norway      | 31       | 0.88%   |
| Argentina   | 31       | 0.88%   |
| Turkey      | 30       | 0.85%   |
| New Zealand | 23       | 0.65%   |
| Greece      | 23       | 0.65%   |
| Portugal    | 22       | 0.63%   |
| Japan       | 22       | 0.63%   |
| Hungary     | 21       | 0.6%    |
| Colombia    | 18       | 0.51%   |
| Indonesia   | 17       | 0.48%   |
| Denmark     | 16       | 0.46%   |
| Chile       | 15       | 0.43%   |
| Philippines | 14       | 0.4%    |
| Belarus     | 13       | 0.37%   |
| South Korea | 12       | 0.34%   |
| Slovakia    | 12       | 0.34%   |
| Israel      | 12       | 0.34%   |
| Ireland     | 11       | 0.31%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Moscow         | 58       | 1.54%   |
| Sydney         | 46       | 1.22%   |
| Berlin         | 31       | 0.82%   |
| St Petersburg  | 29       | 0.77%   |
| Warsaw         | 26       | 0.69%   |
| Sao Paulo      | 25       | 0.66%   |
| Vienna         | 22       | 0.58%   |
| Brisbane       | 19       | 0.5%    |
| Toronto        | 18       | 0.48%   |
| Paris          | 18       | 0.48%   |
| Melbourne      | 18       | 0.48%   |
| Hamburg        | 17       | 0.45%   |
| Auckland       | 17       | 0.45%   |
| Rome           | 16       | 0.42%   |
| Zurich         | 15       | 0.4%    |
| Prague         | 15       | 0.4%    |
| Athens         | 15       | 0.4%    |
| Rio de Janeiro | 14       | 0.37%   |
| Munich         | 14       | 0.37%   |
| Madrid         | 14       | 0.37%   |
| London         | 14       | 0.37%   |
| Helsinki       | 14       | 0.37%   |
| Yekaterinburg  | 13       | 0.34%   |
| Seattle        | 13       | 0.34%   |
| Porto Alegre   | 13       | 0.34%   |
| Buenos Aires   | 13       | 0.34%   |
| Amsterdam      | 13       | 0.34%   |
| Wroclaw        | 12       | 0.32%   |
| Istanbul       | 12       | 0.32%   |
| Belo Horizonte | 12       | 0.32%   |
| Vancouver      | 11       | 0.29%   |
| Milan          | 11       | 0.29%   |
| Krakow         | 11       | 0.29%   |
| Cologne        | 11       | 0.29%   |
| Budapest       | 11       | 0.29%   |
| Montreal       | 10       | 0.27%   |
| Los Angeles    | 10       | 0.27%   |
| Dallas         | 10       | 0.27%   |
| Bucharest      | 10       | 0.27%   |
| Austin         | 10       | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Samsung Electronics       | 1306     | 2595   | 18.27%  |
| WDC                       | 1293     | 2520   | 18.09%  |
| Seagate                   | 1172     | 2152   | 16.4%   |
| Kingston                  | 489      | 739    | 6.84%   |
| Crucial                   | 376      | 587    | 5.26%   |
| Toshiba                   | 372      | 573    | 5.2%    |
| SanDisk                   | 354      | 506    | 4.95%   |
| Hitachi                   | 185      | 305    | 2.59%   |
| Intel                     | 161      | 281    | 2.25%   |
| A-DATA Technology         | 125      | 171    | 1.75%   |
| Phison                    | 108      | 151    | 1.51%   |
| HGST                      | 69       | 138    | 0.97%   |
| Corsair                   | 55       | 84     | 0.77%   |
| Unknown                   | 53       | 85     | 0.74%   |
| SPCC                      | 53       | 83     | 0.74%   |
| Micron/Crucial Technology | 52       | 70     | 0.73%   |
| China                     | 49       | 66     | 0.69%   |
| SK hynix                  | 46       | 53     | 0.64%   |
| Phison Electronics        | 42       | 68     | 0.59%   |
| Silicon Motion            | 41       | 54     | 0.57%   |
| PNY                       | 39       | 55     | 0.55%   |
| OCZ                       | 37       | 48     | 0.52%   |
| Micron Technology         | 36       | 51     | 0.5%    |
| Patriot                   | 34       | 53     | 0.48%   |
| XPG                       | 25       | 35     | 0.35%   |
| Maxtor                    | 24       | 28     | 0.34%   |
| Transcend                 | 21       | 28     | 0.29%   |
| Team                      | 20       | 30     | 0.28%   |
| Plextor                   | 20       | 28     | 0.28%   |
| Intenso                   | 20       | 28     | 0.28%   |
| Gigabyte Technology       | 20       | 35     | 0.28%   |
| ASMT                      | 20       | 23     | 0.28%   |
| Hewlett-Packard           | 18       | 22     | 0.25%   |
| GOODRAM                   | 17       | 27     | 0.24%   |
| Realtek Semiconductor     | 16       | 21     | 0.22%   |
| Apacer                    | 16       | 29     | 0.22%   |
| SABRENT                   | 15       | 18     | 0.21%   |
| KingSpec                  | 14       | 23     | 0.2%    |
| JMicron Technology        | 13       | 19     | 0.18%   |
| LITEON                    | 12       | 15     | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Samsung SSD 850 EVO 250GB                          | 124      | 1.44%   |
| Kingston SA400S37240G 240GB SSD                    | 103      | 1.19%   |
| Samsung SSD 860 EVO 500GB                          | 101      | 1.17%   |
| Seagate ST1000DM010-2EP102 1TB                     | 96       | 1.11%   |
| Samsung NVMe SSD Drive 500GB                       | 91       | 1.05%   |
| Seagate ST2000DM008-2FR102 2TB                     | 90       | 1.04%   |
| Samsung SSD 850 EVO 500GB                          | 88       | 1.02%   |
| Samsung SSD 860 EVO 1TB                            | 85       | 0.98%   |
| Seagate ST500DM002-1BD142 500GB                    | 75       | 0.87%   |
| Samsung NVMe SSD Drive 1TB                         | 69       | 0.8%    |
| WDC WD10EZEX-08WN4A0 1TB                           | 65       | 0.75%   |
| Kingston SA400S37120G 120GB SSD                    | 65       | 0.75%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 64       | 0.74%   |
| Toshiba DT01ACA100 1TB                             | 63       | 0.73%   |
| Kingston SA400S37480G 480GB SSD                    | 61       | 0.71%   |
| Crucial CT500MX500SSD1 500GB                       | 58       | 0.67%   |
| Crucial CT1000MX500SSD1 1TB                        | 51       | 0.59%   |
| Samsung SSD 970 EVO Plus 500GB                     | 45       | 0.52%   |
| Seagate ST1000DM003-1ER162 1TB                     | 44       | 0.51%   |
| Samsung SSD 860 EVO 250GB                          | 44       | 0.51%   |
| Toshiba HDWD110 1TB                                | 42       | 0.49%   |
| SanDisk NVMe SSD Drive 1TB                         | 42       | 0.49%   |
| SanDisk NVMe SSD Drive 500GB                       | 41       | 0.47%   |
| Seagate ST4000DM004-2CV104 4TB                     | 40       | 0.46%   |
| Seagate ST2000DM001-1ER164 2TB                     | 40       | 0.46%   |
| Kingston SV300S37A120G 120GB SSD                   | 40       | 0.46%   |
| Toshiba DT01ACA200 2TB                             | 38       | 0.44%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                   | 36       | 0.42%   |
| WDC WD10EZEX-00BN5A0 1TB                           | 36       | 0.42%   |
| Seagate ST1000DM003-1CH162 1TB                     | 36       | 0.42%   |
| Samsung SSD 970 EVO Plus 1TB                       | 35       | 0.41%   |
| Samsung SSD 840 EVO 250GB                          | 35       | 0.41%   |
| Samsung SSD 860 QVO 1TB                            | 34       | 0.39%   |
| Crucial CT240BX500SSD1 240GB                       | 34       | 0.39%   |
| Seagate ST3500418AS 500GB                          | 33       | 0.38%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB             | 33       | 0.38%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 32       | 0.37%   |
| WDC WD20EZRZ-00Z5HB0 2TB                           | 31       | 0.36%   |
| Seagate ST31000528AS 1TB                           | 31       | 0.36%   |
| Samsung SSD 980 PRO 1TB                            | 31       | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1140     | 2085   | 37.15%  |
| WDC                 | 1106     | 2127   | 36.04%  |
| Toshiba             | 321      | 476    | 10.46%  |
| Hitachi             | 185      | 305    | 6.03%   |
| Samsung Electronics | 136      | 219    | 4.43%   |
| HGST                | 69       | 138    | 2.25%   |
| Maxtor              | 23       | 26     | 0.75%   |
| Unknown             | 16       | 22     | 0.52%   |
| ASMT                | 10       | 12     | 0.33%   |
| JMicron Technology  | 9        | 15     | 0.29%   |
| Fujitsu             | 9        | 11     | 0.29%   |
| Hewlett-Packard     | 5        | 6      | 0.16%   |
| Intenso             | 4        | 7      | 0.13%   |
| Apple               | 4        | 4      | 0.13%   |
| MaxDigital          | 3        | 3      | 0.1%    |
| Inateck             | 3        | 8      | 0.1%    |
| USB3.0              | 2        | 2      | 0.07%   |
| USB                 | 2        | 2      | 0.07%   |
| Synology            | 2        | 3      | 0.07%   |
| LaCie               | 2        | 4      | 0.07%   |
| H/W                 | 2        | 4      | 0.07%   |
| ASMT109x            | 2        | 2      | 0.07%   |
| ASMedia             | 2        | 2      | 0.07%   |
| USB 3.0             | 1        | 3      | 0.03%   |
| SAGE                | 1        | 1      | 0.03%   |
| RSH-339             | 1        | 1      | 0.03%   |
| PHD 3.0             | 1        | 1      | 0.03%   |
| MARVELL             | 1        | 1      | 0.03%   |
| Magnetic Data       | 1        | 1      | 0.03%   |
| KESU                | 1        | 1      | 0.03%   |
| IET                 | 1        | 1      | 0.03%   |
| External            | 1        | 1      | 0.03%   |
| ExcelStor           | 1        | 1      | 0.03%   |
| ASMT106x            | 1        | 2      | 0.03%   |
| Unknown             | 1        | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 779      | 1400   | 28.42%  |
| Kingston            | 403      | 609    | 14.7%   |
| Crucial             | 340      | 535    | 12.4%   |
| SanDisk             | 208      | 268    | 7.59%   |
| WDC                 | 187      | 279    | 6.82%   |
| A-DATA Technology   | 105      | 143    | 3.83%   |
| Intel               | 76       | 144    | 2.77%   |
| China               | 49       | 66     | 1.79%   |
| SPCC                | 42       | 63     | 1.53%   |
| PNY                 | 39       | 54     | 1.42%   |
| OCZ                 | 37       | 48     | 1.35%   |
| Toshiba             | 33       | 47     | 1.2%    |
| Patriot             | 31       | 49     | 1.13%   |
| Corsair             | 30       | 46     | 1.09%   |
| Micron Technology   | 27       | 39     | 0.99%   |
| Transcend           | 21       | 28     | 0.77%   |
| SK hynix            | 19       | 20     | 0.69%   |
| Plextor             | 18       | 25     | 0.66%   |
| Team                | 17       | 27     | 0.62%   |
| GOODRAM             | 17       | 27     | 0.62%   |
| Seagate             | 14       | 17     | 0.51%   |
| KingSpec            | 14       | 23     | 0.51%   |
| Apacer              | 14       | 26     | 0.51%   |
| Intenso             | 13       | 18     | 0.47%   |
| Gigabyte Technology | 13       | 21     | 0.47%   |
| LITEON              | 12       | 15     | 0.44%   |
| KingDian            | 11       | 12     | 0.4%    |
| Verbatim            | 9        | 12     | 0.33%   |
| Unknown             | 9        | 9      | 0.33%   |
| Mushkin             | 9        | 13     | 0.33%   |
| LITEONIT            | 9        | 10     | 0.33%   |
| Hewlett-Packard     | 8        | 9      | 0.29%   |
| ASMT                | 8        | 9      | 0.29%   |
| Lexar               | 7        | 11     | 0.26%   |
| Leven               | 7        | 8      | 0.26%   |
| OWC                 | 4        | 6      | 0.15%   |
| KingFast            | 4        | 4      | 0.15%   |
| Drevo               | 4        | 4      | 0.15%   |
| AMD                 | 4        | 7      | 0.15%   |
| Smartbuy            | 3        | 3      | 0.11%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 2325     | 5498   | 38.89%  |
| SSD     | 2199     | 4263   | 36.78%  |
| NVMe    | 1349     | 2379   | 22.57%  |
| Unknown | 97       | 138    | 1.62%   |
| MMC     | 8        | 9      | 0.13%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 3124     | 9470   | 65.71%  |
| NVMe | 1339     | 2354   | 28.17%  |
| SAS  | 283      | 454    | 5.95%   |
| MMC  | 8        | 9      | 0.17%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 2285     | 4673   | 44.81%  |
| 0.51-1.0   | 1543     | 2723   | 30.26%  |
| 1.01-2.0   | 633      | 1043   | 12.41%  |
| 3.01-4.0   | 277      | 518    | 5.43%   |
| 2.01-3.0   | 167      | 338    | 3.28%   |
| 4.01-10.0  | 150      | 376    | 2.94%   |
| 10.01-20.0 | 44       | 90     | 0.86%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 687      | 18.22%  |
| 1001-2000      | 676      | 17.93%  |
| More than 3000 | 576      | 15.28%  |
| 251-500        | 576      | 15.28%  |
| 101-250        | 488      | 12.94%  |
| 2001-3000      | 312      | 8.28%   |
| 1-20           | 174      | 4.62%   |
| Unknown        | 149      | 3.95%   |
| 51-100         | 94       | 2.49%   |
| 21-50          | 38       | 1.01%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 686      | 17.32%  |
| 101-250        | 540      | 13.64%  |
| 21-50          | 509      | 12.85%  |
| 501-1000       | 488      | 12.32%  |
| 251-500        | 487      | 12.3%   |
| 51-100         | 425      | 10.73%  |
| 1001-2000      | 354      | 8.94%   |
| More than 3000 | 184      | 4.65%   |
| Unknown        | 149      | 3.76%   |
| 2001-3000      | 137      | 3.46%   |
| 0              | 1        | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 17       | 42     | 3.29%   |
| WDC WD10EZEX-00BN5A0 1TB            | 7        | 7      | 1.36%   |
| Seagate ST3500418AS 500GB           | 7        | 13     | 1.36%   |
| Seagate ST31000528AS 1TB            | 7        | 9      | 1.36%   |
| Samsung Electronics SSD 870 EVO 1TB | 7        | 8      | 1.36%   |
| Seagate ST31000524AS 1TB            | 6        | 6      | 1.16%   |
| Toshiba MQ01ABD050 500GB            | 5        | 6      | 0.97%   |
| Seagate ST31500341AS 1TB            | 5        | 5      | 0.97%   |
| Seagate ST1000DM010-2EP102 1TB      | 5        | 5      | 0.97%   |
| Samsung Electronics HD322HJ 320GB   | 5        | 7      | 0.97%   |
| Intel SSDSC2CT120A3 120GB           | 5        | 27     | 0.97%   |
| Seagate ST2000DM001-1CH164 2TB      | 4        | 4      | 0.78%   |
| Samsung Electronics HD501LJ 500GB   | 4        | 31     | 0.78%   |
| Crucial CT275MX300SSD1 275GB        | 4        | 5      | 0.78%   |
| Crucial CT240M500SSD1 240GB         | 4        | 4      | 0.78%   |
| Crucial CT128MX100SSD1 128GB        | 4        | 6      | 0.78%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 3        | 3      | 0.58%   |
| WDC WD20EZRX-00D8PB0 2TB            | 3        | 4      | 0.58%   |
| WDC WD10EZEX-08WN4A0 1TB            | 3        | 4      | 0.58%   |
| WDC WD10EZEX-00WN4A0 1TB            | 3        | 3      | 0.58%   |
| WDC WD1002FAEX-00Z3A0 1TB           | 3        | 3      | 0.58%   |
| Toshiba DT01ACA100 1TB              | 3        | 3      | 0.58%   |
| Seagate ST500LT012-1DG142 500GB     | 3        | 3      | 0.58%   |
| Seagate ST3000DM008-2DM166 3TB      | 3        | 4      | 0.58%   |
| Seagate ST2000DM001-1ER164 2TB      | 3        | 3      | 0.58%   |
| Seagate ST2000DL003-9VT166 2TB      | 3        | 3      | 0.58%   |
| SanDisk SSD PLUS 480GB              | 3        | 3      | 0.58%   |
| Kingston SV300S37A120G 120GB SSD    | 3        | 3      | 0.58%   |
| Kingston SA400S37240G 240GB SSD     | 3        | 3      | 0.58%   |
| Hitachi HDS721010DLE630 1TB         | 3        | 5      | 0.58%   |
| Hitachi HDS721010CLA332 1TB         | 3        | 3      | 0.58%   |
| Hitachi HDP725050GLA360 500GB       | 3        | 3      | 0.58%   |
| WDC WD5000AAKX-753CA1 500GB         | 2        | 2      | 0.39%   |
| WDC WD5000AAKX-603CA0 500GB         | 2        | 2      | 0.39%   |
| WDC WD5000AAKX-003CA0 500GB         | 2        | 2      | 0.39%   |
| WDC WD5000AADS-00S9B0 500GB         | 2        | 2      | 0.39%   |
| WDC WD40PURZ-85AKKY0 4TB            | 2        | 2      | 0.39%   |
| WDC WD40EFRX-68WT0N0 4TB            | 2        | 2      | 0.39%   |
| WDC WD30EZRX-00D8PB0 3TB            | 2        | 2      | 0.39%   |
| WDC WD30EFRX-68AX9N0 3TB            | 2        | 2      | 0.39%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 130      | 207    | 26.75%  |
| WDC                 | 125      | 182    | 25.72%  |
| Samsung Electronics | 44       | 80     | 9.05%   |
| Hitachi             | 35       | 48     | 7.2%    |
| Toshiba             | 30       | 35     | 6.17%   |
| Crucial             | 21       | 25     | 4.32%   |
| Intel               | 20       | 44     | 4.12%   |
| SanDisk             | 16       | 16     | 3.29%   |
| Kingston            | 11       | 12     | 2.26%   |
| A-DATA Technology   | 9        | 9      | 1.85%   |
| Maxtor              | 6        | 6      | 1.23%   |
| Corsair             | 6        | 9      | 1.23%   |
| OCZ                 | 4        | 5      | 0.82%   |
| SK hynix            | 3        | 3      | 0.62%   |
| LITEON              | 3        | 3      | 0.62%   |
| HGST                | 3        | 5      | 0.62%   |
| SPCC                | 2        | 3      | 0.41%   |
| OCZ-VERTEX3         | 2        | 2      | 0.41%   |
| Fujitsu             | 2        | 2      | 0.41%   |
| Verbatim            | 1        | 1      | 0.21%   |
| Unknown             | 1        | 1      | 0.21%   |
| Team                | 1        | 4      | 0.21%   |
| PNY                 | 1        | 1      | 0.21%   |
| ORICO               | 1        | 1      | 0.21%   |
| Micron Technology   | 1        | 1      | 0.21%   |
| KingSpec            | 1        | 1      | 0.21%   |
| KingDian            | 1        | 1      | 0.21%   |
| Hewlett-Packard     | 1        | 1      | 0.21%   |
| BIWIN               | 1        | 1      | 0.21%   |
| ASMT                | 1        | 1      | 0.21%   |
| ASMedia             | 1        | 1      | 0.21%   |
| Apacer              | 1        | 1      | 0.21%   |
| AMD                 | 1        | 2      | 0.21%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 130      | 207    | 36.31%  |
| WDC                 | 123      | 180    | 34.36%  |
| Hitachi             | 35       | 48     | 9.78%   |
| Toshiba             | 30       | 35     | 8.38%   |
| Samsung Electronics | 26       | 59     | 7.26%   |
| Maxtor              | 6        | 6      | 1.68%   |
| HGST                | 3        | 5      | 0.84%   |
| Fujitsu             | 2        | 2      | 0.56%   |
| Hewlett-Packard     | 1        | 1      | 0.28%   |
| ASMT                | 1        | 1      | 0.28%   |
| ASMedia             | 1        | 1      | 0.28%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 325      | 545    | 72.06%  |
| SSD  | 116      | 159    | 25.72%  |
| NVMe | 10       | 10     | 2.22%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD5000BEVT-00ZAT0 500GB       | 1        | 2      | 12.5%   |
| Toshiba HDWD130 3TB               | 1        | 1      | 12.5%   |
| SPCC M.2 PCIe SSD 2TB             | 1        | 1      | 12.5%   |
| Seagate ST3320613AS 320GB         | 1        | 1      | 12.5%   |
| Seagate ST31000528AS 1TB          | 1        | 2      | 12.5%   |
| Samsung Electronics SSD 980 500GB | 1        | 2      | 12.5%   |
| Samsung Electronics HD321HJ 320GB | 1        | 2      | 12.5%   |
| Hitachi HDS721010DLE630 1TB       | 1        | 6      | 12.5%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 2        | 3      | 25%     |
| Samsung Electronics | 2        | 4      | 25%     |
| WDC                 | 1        | 2      | 12.5%   |
| Toshiba             | 1        | 1      | 12.5%   |
| SPCC                | 1        | 1      | 12.5%   |
| Hitachi             | 1        | 6      | 12.5%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 2063     | 6893   | 50.6%   |
| Works    | 1571     | 4663   | 38.53%  |
| Malfunc  | 436      | 714    | 10.69%  |
| Failed   | 7        | 17     | 0.17%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 1974     | 36.09%  |
| AMD                            | 1485     | 27.15%  |
| Samsung Electronics            | 602      | 11.01%  |
| ASMedia Technology             | 233      | 4.26%   |
| SanDisk                        | 224      | 4.1%    |
| Phison Electronics             | 180      | 3.29%   |
| Marvell Technology Group       | 112      | 2.05%   |
| Kingston Technology Company    | 109      | 1.99%   |
| Micron/Crucial Technology      | 87       | 1.59%   |
| JMicron Technology             | 85       | 1.55%   |
| Silicon Motion                 | 52       | 0.95%   |
| Nvidia                         | 51       | 0.93%   |
| ADATA Technology               | 44       | 0.8%    |
| SK hynix                       | 27       | 0.49%   |
| Toshiba America Info Systems   | 26       | 0.48%   |
| Realtek Semiconductor          | 25       | 0.46%   |
| LSI Logic / Symbios Logic      | 22       | 0.4%    |
| Broadcom / LSI                 | 19       | 0.35%   |
| Seagate Technology             | 15       | 0.27%   |
| Silicon Image                  | 12       | 0.22%   |
| MAXIO Technology (Hangzhou)    | 12       | 0.22%   |
| Micron Technology              | 11       | 0.2%    |
| VIA Technologies               | 10       | 0.18%   |
| Lite-On Technology             | 9        | 0.16%   |
| KIOXIA                         | 9        | 0.16%   |
| Adaptec                        | 6        | 0.11%   |
| Integrated Technology Express  | 4        | 0.07%   |
| Netac Technology               | 3        | 0.05%   |
| INNOGRIT                       | 3        | 0.05%   |
| Hewlett-Packard                | 3        | 0.05%   |
| 3ware                          | 3        | 0.05%   |
| ULi Electronics                | 2        | 0.04%   |
| Solid State Storage Technology | 2        | 0.04%   |
| Lite-On IT Corp. / Plextor     | 2        | 0.04%   |
| HighPoint Technologies         | 2        | 0.04%   |
| Union Memory (Shenzhen)        | 1        | 0.02%   |
| Solidigm                       | 1        | 0.02%   |
| Shenzhen Longsys Electronics   | 1        | 0.02%   |
| PMC-Sierra                     | 1        | 0.02%   |
| Biwin Storage Technology       | 1        | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 974      | 14.56%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 371      | 5.54%   |
| AMD 400 Series Chipset SATA Controller                                                  | 364      | 5.44%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 231      | 3.45%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 223      | 3.33%   |
| AMD 500 Series Chipset SATA Controller                                                  | 217      | 3.24%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 200      | 2.99%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 194      | 2.9%    |
| Intel SATA Controller [RAID mode]                                                       | 149      | 2.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 146      | 2.18%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 144      | 2.15%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 131      | 1.96%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 128      | 1.91%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 125      | 1.87%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 110      | 1.64%   |
| Phison E12 NVMe Controller                                                              | 101      | 1.51%   |
| AMD 300 Series Chipset SATA Controller                                                  | 101      | 1.51%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 91       | 1.36%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 90       | 1.35%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 77       | 1.15%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 73       | 1.09%   |
| AMD FCH SATA Controller D                                                               | 63       | 0.94%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 62       | 0.93%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 56       | 0.84%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 56       | 0.84%   |
| AMD X370 Series Chipset SATA Controller                                                 | 54       | 0.81%   |
| Samsung NVMe SSD Controller 980                                                         | 47       | 0.7%    |
| Intel Volume Management Device NVMe RAID Controller                                     | 47       | 0.7%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 46       | 0.69%   |
| Intel SSD 660P Series                                                                   | 44       | 0.66%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 43       | 0.64%   |
| Kingston Company A2000 NVMe SSD                                                         | 43       | 0.64%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 43       | 0.64%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 43       | 0.64%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 43       | 0.64%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 39       | 0.58%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 38       | 0.57%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 37       | 0.55%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 36       | 0.54%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 35       | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 3046     | 58.16%  |
| NVMe | 1340     | 25.59%  |
| IDE  | 531      | 10.14%  |
| RAID | 268      | 5.12%   |
| SAS  | 41       | 0.78%   |
| SCSI | 11       | 0.21%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 1957     | 55.99%  |
| AMD    | 1538     | 44.01%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 125      | 3.55%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 92       | 2.61%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 69       | 1.96%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 60       | 1.71%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 57       | 1.62%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 55       | 1.56%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 50       | 1.42%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 49       | 1.39%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 49       | 1.39%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 46       | 1.31%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 44       | 1.25%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 43       | 1.22%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 38       | 1.08%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 37       | 1.05%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 36       | 1.02%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 35       | 0.99%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 34       | 0.97%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 34       | 0.97%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 34       | 0.97%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 34       | 0.97%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 33       | 0.94%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 33       | 0.94%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 32       | 0.91%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 31       | 0.88%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 30       | 0.85%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 29       | 0.82%   |
| AMD FX-6300 Six-Core Processor              | 29       | 0.82%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 28       | 0.8%    |
| AMD FX-8350 Eight-Core Processor            | 27       | 0.77%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 26       | 0.74%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 26       | 0.74%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 26       | 0.74%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 25       | 0.71%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 25       | 0.71%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 25       | 0.71%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 24       | 0.68%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 23       | 0.65%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 23       | 0.65%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 22       | 0.63%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 21       | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 596      | 16.99%  |
| Intel Core i7           | 567      | 16.16%  |
| AMD Ryzen 5             | 503      | 14.34%  |
| AMD Ryzen 7             | 347      | 9.89%   |
| AMD Ryzen 9             | 208      | 5.93%   |
| Intel Core i3           | 187      | 5.33%   |
| Intel Xeon              | 185      | 5.27%   |
| AMD FX                  | 128      | 3.65%   |
| Other                   | 113      | 3.22%   |
| Intel Core 2 Duo        | 70       | 2%      |
| AMD Ryzen 3             | 54       | 1.54%   |
| Intel Core 2 Quad       | 48       | 1.37%   |
| Intel Core i9           | 46       | 1.31%   |
| Intel Pentium           | 44       | 1.25%   |
| AMD Ryzen Threadripper  | 42       | 1.2%    |
| Intel Celeron           | 40       | 1.14%   |
| AMD Phenom II X4        | 33       | 0.94%   |
| AMD A10                 | 29       | 0.83%   |
| AMD A8                  | 26       | 0.74%   |
| Intel Pentium Dual-Core | 24       | 0.68%   |
| AMD A6                  | 20       | 0.57%   |
| AMD Athlon II X2        | 18       | 0.51%   |
| AMD Athlon              | 17       | 0.48%   |
| AMD Phenom II X6        | 16       | 0.46%   |
| Intel Core 2            | 14       | 0.4%    |
| Intel Atom              | 12       | 0.34%   |
| AMD Phenom              | 12       | 0.34%   |
| AMD Athlon 64 X2        | 12       | 0.34%   |
| AMD Ryzen 7 PRO         | 10       | 0.29%   |
| AMD A4                  | 10       | 0.29%   |
| AMD Ryzen 5 PRO         | 8        | 0.23%   |
| AMD Athlon X4           | 8        | 0.23%   |
| AMD Athlon II X4        | 7        | 0.2%    |
| AMD Phenom II X2        | 6        | 0.17%   |
| Intel Pentium Gold      | 4        | 0.11%   |
| Intel Pentium Dual      | 4        | 0.11%   |
| Intel Genuine           | 4        | 0.11%   |
| AMD Athlon Dual Core    | 4        | 0.11%   |
| Intel Pentium D         | 3        | 0.09%   |
| AMD E2                  | 3        | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 1308     | 37.26%  |
| 6      | 736      | 20.97%  |
| 2      | 517      | 14.73%  |
| 8      | 497      | 14.16%  |
| 12     | 191      | 5.44%   |
| 16     | 110      | 3.13%   |
| 3      | 49       | 1.4%    |
| 10     | 38       | 1.08%   |
| 1      | 30       | 0.85%   |
| 24     | 15       | 0.43%   |
| 32     | 10       | 0.28%   |
| 14     | 6        | 0.17%   |
| 28     | 1        | 0.03%   |
| 20     | 1        | 0.03%   |
| 18     | 1        | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 3451     | 98.74%  |
| 2      | 44       | 1.26%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 2399     | 68.46%  |
| 1      | 1105     | 31.54%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 3407     | 97.01%  |
| Unknown        | 105      | 2.99%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 317      | 8.78%   |
| Unknown    | 286      | 7.92%   |
| 0x08701021 | 271      | 7.5%    |
| 0x306a9    | 185      | 5.12%   |
| 0x506e3    | 173      | 4.79%   |
| 0x0800820d | 144      | 3.99%   |
| 0x206a7    | 137      | 3.79%   |
| 0x906ea    | 134      | 3.71%   |
| 0x906e9    | 118      | 3.27%   |
| 0x08701013 | 116      | 3.21%   |
| 0x1067a    | 88       | 2.44%   |
| 0x0a201016 | 75       | 2.08%   |
| 0x06000852 | 74       | 2.05%   |
| 0x0a201009 | 64       | 1.77%   |
| 0x08001138 | 60       | 1.66%   |
| 0x906ed    | 57       | 1.58%   |
| 0x08108109 | 49       | 1.36%   |
| 0x90672    | 48       | 1.33%   |
| 0x08001137 | 47       | 1.3%    |
| 0x0a50000c | 46       | 1.27%   |
| 0x306f2    | 45       | 1.25%   |
| 0xa0655    | 44       | 1.22%   |
| 0xa0653    | 41       | 1.14%   |
| 0x010000c8 | 41       | 1.14%   |
| 0x08101016 | 39       | 1.08%   |
| 0x206d7    | 33       | 0.91%   |
| 0x06001119 | 33       | 0.91%   |
| 0x0a50000d | 29       | 0.8%    |
| 0x20655    | 28       | 0.78%   |
| 0x0a20120a | 28       | 0.78%   |
| 0x106a5    | 27       | 0.75%   |
| 0xa0671    | 26       | 0.72%   |
| 0x6fb      | 26       | 0.72%   |
| 0x106e5    | 26       | 0.72%   |
| 0x10676    | 26       | 0.72%   |
| 0x906eb    | 25       | 0.69%   |
| 0x906ec    | 22       | 0.61%   |
| 0x0a601203 | 22       | 0.61%   |
| 0x0800820b | 22       | 0.61%   |
| 0x06003106 | 21       | 0.58%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 431      | 12.28%  |
| KabyLake         | 395      | 11.25%  |
| Haswell          | 391      | 11.14%  |
| Zen 3            | 289      | 8.23%   |
| Zen+             | 245      | 6.98%   |
| IvyBridge        | 221      | 6.29%   |
| Skylake          | 203      | 5.78%   |
| Zen              | 199      | 5.67%   |
| SandyBridge      | 192      | 5.47%   |
| Piledriver       | 141      | 4.02%   |
| Penryn           | 129      | 3.67%   |
| K10              | 97       | 2.76%   |
| CometLake        | 88       | 2.51%   |
| Alderlake Hybrid | 75       | 2.14%   |
| Nehalem          | 60       | 1.71%   |
| Westmere         | 57       | 1.62%   |
| Core             | 55       | 1.57%   |
| Unknown          | 38       | 1.08%   |
| Steamroller      | 30       | 0.85%   |
| Icelake          | 28       | 0.8%    |
| Excavator        | 22       | 0.63%   |
| Bulldozer        | 22       | 0.63%   |
| K8 Hammer        | 19       | 0.54%   |
| Silvermont       | 15       | 0.43%   |
| Broadwell        | 15       | 0.43%   |
| Bonnell          | 10       | 0.28%   |
| K10 Llano        | 8        | 0.23%   |
| NetBurst         | 7        | 0.2%    |
| Jaguar           | 7        | 0.2%    |
| Bobcat           | 5        | 0.14%   |
| Puma             | 4        | 0.11%   |
| Goldmont plus    | 4        | 0.11%   |
| Goldmont         | 4        | 0.11%   |
| Tremont          | 3        | 0.09%   |
| TigerLake        | 2        | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 1521     | 39.85%  |
| AMD                        | 1426     | 37.36%  |
| Intel                      | 853      | 22.35%  |
| ASPEED Technology          | 9        | 0.24%   |
| Matrox Electronics Systems | 7        | 0.18%   |
| S3 Graphics                | 1        | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 291      | 7.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 148      | 3.75%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 124      | 3.14%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 98       | 2.48%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 97       | 2.46%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 94       | 2.38%   |
| Intel HD Graphics 530                                                       | 91       | 2.31%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 79       | 2%      |
| Intel HD Graphics 630                                                       | 67       | 1.7%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 65       | 1.65%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 64       | 1.62%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 61       | 1.55%   |
| Nvidia GK208B [GeForce GT 710]                                              | 59       | 1.5%    |
| Nvidia GP104 [GeForce GTX 1070]                                             | 51       | 1.29%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 50       | 1.27%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 50       | 1.27%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 50       | 1.27%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 49       | 1.24%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 46       | 1.17%   |
| Nvidia GT218 [GeForce 210]                                                  | 44       | 1.12%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 43       | 1.09%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 42       | 1.06%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 41       | 1.04%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 41       | 1.04%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 40       | 1.01%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 39       | 0.99%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 39       | 0.99%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 37       | 0.94%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 37       | 0.94%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 36       | 0.91%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 35       | 0.89%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 34       | 0.86%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 33       | 0.84%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 31       | 0.79%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 31       | 0.79%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 29       | 0.74%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 27       | 0.68%   |
| Nvidia GK208B [GeForce GT 730]                                              | 27       | 0.68%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 26       | 0.66%   |
| Intel AlderLake-S GT1                                                       | 26       | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 1373     | 38.67%  |
| 1 x AMD                  | 1303     | 36.69%  |
| 1 x Intel                | 632      | 17.8%   |
| Intel + Nvidia           | 76       | 2.14%   |
| 2 x AMD                  | 49       | 1.38%   |
| AMD + Nvidia             | 43       | 1.21%   |
| Intel + AMD              | 27       | 0.76%   |
| 2 x Nvidia               | 21       | 0.59%   |
| 1 x ASPEED               | 5        | 0.14%   |
| 1 x Matrox               | 4        | 0.11%   |
| 2 x Intel                | 3        | 0.08%   |
| Nvidia + Matrox          | 2        | 0.06%   |
| Nvidia + ASPEED          | 2        | 0.06%   |
| Intel + AMD + 1 x Nvidia | 2        | 0.06%   |
| Other                    | 1        | 0.03%   |
| 3 x AMD                  | 1        | 0.03%   |
| 2 x Nvidia + 1 x ASPEED  | 1        | 0.03%   |
| 1 x S3 Graphics          | 1        | 0.03%   |
| Intel + 2 x Nvidia       | 1        | 0.03%   |
| Intel + 2 x AMD          | 1        | 0.03%   |
| AMD + 2 x Nvidia         | 1        | 0.03%   |
| AMD + Matrox             | 1        | 0.03%   |
| AMD + ASPEED             | 1        | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 2611     | 73.22%  |
| Proprietary | 856      | 24%     |
| Unknown     | 99       | 2.78%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1212     | 33.17%  |
| 7.01-8.0   | 571      | 15.63%  |
| 1.01-2.0   | 470      | 12.86%  |
| 3.01-4.0   | 397      | 10.86%  |
| 0.51-1.0   | 352      | 9.63%   |
| 0.01-0.5   | 247      | 6.76%   |
| 5.01-6.0   | 172      | 4.71%   |
| 8.01-16.0  | 171      | 4.68%   |
| 2.01-3.0   | 50       | 1.37%   |
| 16.01-24.0 | 12       | 0.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 613      | 14.95%  |
| Dell                 | 560      | 13.66%  |
| Goldstar             | 502      | 12.24%  |
| Acer                 | 291      | 7.1%    |
| AOC                  | 245      | 5.98%   |
| Hewlett-Packard      | 243      | 5.93%   |
| BenQ                 | 231      | 5.63%   |
| Ancor Communications | 208      | 5.07%   |
| Philips              | 165      | 4.02%   |
| ViewSonic            | 108      | 2.63%   |
| Lenovo               | 90       | 2.2%    |
| Iiyama               | 89       | 2.17%   |
| ASUSTek Computer     | 86       | 2.1%    |
| Sony                 | 41       | 1%      |
| MSI                  | 40       | 0.98%   |
| Sceptre Tech         | 38       | 0.93%   |
| Eizo                 | 37       | 0.9%    |
| Unknown              | 32       | 0.78%   |
| Gigabyte Technology  | 29       | 0.71%   |
| HannStar             | 28       | 0.68%   |
| NEC Computers        | 25       | 0.61%   |
| Vizio                | 20       | 0.49%   |
| Insignia             | 15       | 0.37%   |
| Mi                   | 14       | 0.34%   |
| LG Electronics       | 13       | 0.32%   |
| ___                  | 11       | 0.27%   |
| Panasonic            | 11       | 0.27%   |
| Fujitsu Siemens      | 11       | 0.27%   |
| Pixio                | 10       | 0.24%   |
| Gateway              | 10       | 0.24%   |
| Vestel Elektronik    | 7        | 0.17%   |
| Unknown (XXX)        | 7        | 0.17%   |
| RTK                  | 7        | 0.17%   |
| ONN                  | 7        | 0.17%   |
| Hitachi              | 7        | 0.17%   |
| Toshiba              | 6        | 0.15%   |
| Sharp                | 6        | 0.15%   |
| Medion               | 6        | 0.15%   |
| Apple                | 6        | 0.15%   |
| Planar               | 5        | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 34       | 0.76%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 28       | 0.63%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 23       | 0.52%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                       | 23       | 0.52%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 22       | 0.49%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 18       | 0.4%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 17       | 0.38%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 17       | 0.38%   |
| AOC 24P2W1DG5 AOC2402 1920x1080 527x296mm 23.8-inch                    | 16       | 0.36%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch      | 15       | 0.34%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch       | 15       | 0.34%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch  | 15       | 0.34%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 14       | 0.31%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                      | 14       | 0.31%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                       | 14       | 0.31%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 13       | 0.29%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                        | 13       | 0.29%   |
| Samsung Electronics SyncMaster SAM01D3 1440x900 408x225mm 18.3-inch    | 11       | 0.25%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch     | 11       | 0.25%   |
| Dell U2515H DELD06F 2560x1440 553x311mm 25.0-inch                      | 11       | 0.25%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                      | 11       | 0.25%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                      | 11       | 0.25%   |
| AOC 2460G5 AOC2460 1920x1080 531x299mm 24.0-inch                       | 11       | 0.25%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                       | 10       | 0.22%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                  | 10       | 0.22%   |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                  | 10       | 0.22%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch               | 9        | 0.2%    |
| Hewlett-Packard 24fw HPN3545 1920x1080 527x296mm 23.8-inch             | 9        | 0.2%    |
| ASUSTek Computer VG27A AUS2722 2560x1440 597x336mm 27.0-inch           | 9        | 0.2%    |
| AOC 2269WM AOC2269 1920x1080 477x268mm 21.5-inch                       | 9        | 0.2%    |
| Acer SB220Q ACR06AB 1920x1080 476x268mm 21.5-inch                      | 9        | 0.2%    |
| MSI MAG341CQ MSI1462 3440x1440 797x333mm 34.0-inch                     | 8        | 0.18%   |
| Goldstar ULTRAWIDE GSM76E4 3440x1440 800x335mm 34.1-inch               | 8        | 0.18%   |
| Dell U2417H DEL40E8 1920x1080 527x296mm 23.8-inch                      | 8        | 0.18%   |
| Dell U2414H DELA0A4 1920x1080 527x296mm 23.8-inch                      | 8        | 0.18%   |
| Ancor Communications ASUS PB278 ACI27A3 2560x1440 597x336mm 27.0-inch  | 8        | 0.18%   |
| ___ LCDTV16 ___0101 1360x768                                           | 7        | 0.16%   |
| ViewSonic VA2226w-3 VSC2051 1680x1050 490x290mm 22.4-inch              | 7        | 0.16%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 7        | 0.16%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 890x500mm 40.2-inch  | 7        | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1779     | 45.27%  |
| 2560x1440 (QHD)    | 484      | 12.32%  |
| 3840x2160 (4K)     | 446      | 11.35%  |
| 1280x1024 (SXGA)   | 162      | 4.12%   |
| 1680x1050 (WSXGA+) | 153      | 3.89%   |
| 1920x1200 (WUXGA)  | 137      | 3.49%   |
| 3440x1440          | 127      | 3.23%   |
| 1366x768 (WXGA)    | 111      | 2.82%   |
| 1440x900 (WXGA+)   | 101      | 2.57%   |
| 2560x1080          | 93       | 2.37%   |
| 1600x900 (HD+)     | 80       | 2.04%   |
| 1360x768           | 44       | 1.12%   |
| Unknown            | 37       | 0.94%   |
| 3840x1080          | 36       | 0.92%   |
| 1600x1200          | 22       | 0.56%   |
| 2288x1287          | 15       | 0.38%   |
| 1024x768 (XGA)     | 15       | 0.38%   |
| 2560x1600          | 14       | 0.36%   |
| 1920x540           | 14       | 0.36%   |
| 2048x1152          | 8        | 0.2%    |
| 1280x720 (HD)      | 7        | 0.18%   |
| 3840x1600          | 5        | 0.13%   |
| 1280x960           | 5        | 0.13%   |
| 2160x1200          | 3        | 0.08%   |
| 5760x2160          | 2        | 0.05%   |
| 3840x1200          | 2        | 0.05%   |
| 1280x768           | 2        | 0.05%   |
| 7680x2160          | 1        | 0.03%   |
| 7680x1440          | 1        | 0.03%   |
| 7120x1080          | 1        | 0.03%   |
| 6784x2160          | 1        | 0.03%   |
| 6400x2160          | 1        | 0.03%   |
| 6400x1080          | 1        | 0.03%   |
| 5760x1200          | 1        | 0.03%   |
| 5760x1080          | 1        | 0.03%   |
| 5120x1440          | 1        | 0.03%   |
| 4864x2160          | 1        | 0.03%   |
| 4480x1200          | 1        | 0.03%   |
| 4480x1080          | 1        | 0.03%   |
| 4160x1440          | 1        | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 767      | 18.54%  |
| 24      | 718      | 17.35%  |
| 23      | 513      | 12.4%   |
| 21      | 471      | 11.38%  |
| 31      | 208      | 5.03%   |
| 34      | 191      | 4.62%   |
| 19      | 186      | 4.49%   |
| 18      | 135      | 3.26%   |
| 22      | 134      | 3.24%   |
| Unknown | 120      | 2.9%    |
| 20      | 102      | 2.46%   |
| 17      | 60       | 1.45%   |
| 32      | 54       | 1.3%    |
| 72      | 51       | 1.23%   |
| 25      | 48       | 1.16%   |
| 84      | 46       | 1.11%   |
| 40      | 34       | 0.82%   |
| 15      | 32       | 0.77%   |
| 48      | 29       | 0.7%    |
| 54      | 24       | 0.58%   |
| 26      | 21       | 0.51%   |
| 42      | 19       | 0.46%   |
| 142     | 13       | 0.31%   |
| 29      | 13       | 0.31%   |
| 28      | 13       | 0.31%   |
| 16      | 11       | 0.27%   |
| 52      | 10       | 0.24%   |
| 49      | 10       | 0.24%   |
| 46      | 10       | 0.24%   |
| 36      | 10       | 0.24%   |
| 35      | 9        | 0.22%   |
| 65      | 8        | 0.19%   |
| 37      | 8        | 0.19%   |
| 13      | 8        | 0.19%   |
| 69      | 6        | 0.14%   |
| 39      | 6        | 0.14%   |
| 43      | 5        | 0.12%   |
| 30      | 5        | 0.12%   |
| 33      | 4        | 0.1%    |
| 12      | 4        | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 1791     | 45.77%  |
| 401-500        | 876      | 22.39%  |
| 601-700        | 321      | 8.2%    |
| 701-800        | 258      | 6.59%   |
| 351-400        | 138      | 3.53%   |
| Unknown        | 120      | 3.07%   |
| 1501-2000      | 105      | 2.68%   |
| 1001-1500      | 101      | 2.58%   |
| 301-350        | 92       | 2.35%   |
| 801-900        | 56       | 1.43%   |
| 901-1000       | 29       | 0.74%   |
| More than 2000 | 15       | 0.38%   |
| 201-300        | 11       | 0.28%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 2602     | 71.56%  |
| 16/10   | 450      | 12.38%  |
| 21/9    | 212      | 5.83%   |
| 5/4     | 160      | 4.4%    |
| Unknown | 84       | 2.31%   |
| 4/3     | 57       | 1.57%   |
| 32/9    | 28       | 0.77%   |
| 6/5     | 13       | 0.36%   |
| 1.00    | 13       | 0.36%   |
| 3/2     | 9        | 0.25%   |
| 1.96    | 5        | 0.14%   |
| 3.20    | 1        | 0.03%   |
| 0.89    | 1        | 0.03%   |
| 0.80    | 1        | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 1382     | 34.58%  |
| 301-350        | 782      | 19.57%  |
| 351-500        | 471      | 11.79%  |
| 151-200        | 442      | 11.06%  |
| 251-300        | 277      | 6.93%   |
| More than 1000 | 175      | 4.38%   |
| 141-150        | 152      | 3.8%    |
| 501-1000       | 129      | 3.23%   |
| Unknown        | 120      | 3%      |
| 101-110        | 28       | 0.7%    |
| 131-140        | 11       | 0.28%   |
| 71-80          | 6        | 0.15%   |
| 111-120        | 6        | 0.15%   |
| 91-100         | 6        | 0.15%   |
| 121-130        | 5        | 0.13%   |
| 81-90          | 4        | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 2232     | 59.14%  |
| 101-120 | 951      | 25.2%   |
| 121-160 | 218      | 5.78%   |
| 1-50    | 153      | 4.05%   |
| Unknown | 120      | 3.18%   |
| 161-240 | 100      | 2.65%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 2504     | 69.23%  |
| 2     | 859      | 23.75%  |
| 0     | 125      | 3.46%   |
| 3     | 110      | 3.04%   |
| 4     | 15       | 0.41%   |
| 5     | 4        | 0.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 2051     | 40.55%  |
| Intel                           | 1761     | 34.82%  |
| Qualcomm Atheros                | 283      | 5.6%    |
| Broadcom                        | 132      | 2.61%   |
| TP-Link                         | 105      | 2.08%   |
| Ralink Technology               | 99       | 1.96%   |
| MediaTek                        | 55       | 1.09%   |
| Ralink                          | 48       | 0.95%   |
| Microsoft                       | 47       | 0.93%   |
| Aquantia                        | 45       | 0.89%   |
| Nvidia                          | 42       | 0.83%   |
| Qualcomm Atheros Communications | 32       | 0.63%   |
| ASUSTek Computer                | 28       | 0.55%   |
| Marvell Technology Group        | 22       | 0.43%   |
| D-Link                          | 22       | 0.43%   |
| NetGear                         | 21       | 0.42%   |
| Xiaomi                          | 20       | 0.4%    |
| Samsung Electronics             | 18       | 0.36%   |
| Edimax Technology               | 15       | 0.3%    |
| ASIX Electronics                | 12       | 0.24%   |
| Mellanox Technologies           | 11       | 0.22%   |
| Huawei Technologies             | 11       | 0.22%   |
| Google                          | 10       | 0.2%    |
| Broadcom Limited                | 10       | 0.2%    |
| D-Link System                   | 9        | 0.18%   |
| Motorola PCS                    | 8        | 0.16%   |
| Linksys                         | 8        | 0.16%   |
| Arduino SA                      | 8        | 0.16%   |
| Belkin Components               | 7        | 0.14%   |
| Apple                           | 7        | 0.14%   |
| ICS Advent                      | 6        | 0.12%   |
| DisplayLink                     | 6        | 0.12%   |
| Qualcomm                        | 5        | 0.1%    |
| InterBiometrics                 | 5        | 0.1%    |
| HMD Global                      | 5        | 0.1%    |
| AVM                             | 5        | 0.1%    |
| Wilocity                        | 4        | 0.08%   |
| OPPO Electronics                | 4        | 0.08%   |
| Microchip Technology            | 4        | 0.08%   |
| OpenMoko                        | 3        | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1613     | 27.46%  |
| Intel I211 Gigabit Network Connection                             | 368      | 6.26%   |
| Intel Wi-Fi 6 AX200                                               | 341      | 5.81%   |
| Realtek RTL8125 2.5GbE Controller                                 | 227      | 3.86%   |
| Intel Ethernet Connection (2) I219-V                              | 208      | 3.54%   |
| Intel Ethernet Controller I225-V                                  | 149      | 2.54%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 115      | 1.96%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 102      | 1.74%   |
| Intel Ethernet Connection (7) I219-V                              | 85       | 1.45%   |
| Intel Ethernet Connection I217-LM                                 | 72       | 1.23%   |
| Intel Wireless-AC 9260                                            | 66       | 1.12%   |
| Intel Ethernet Connection (2) I218-V                              | 66       | 1.12%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 58       | 0.99%   |
| Intel 82579V Gigabit Network Connection                           | 50       | 0.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 48       | 0.82%   |
| Intel 82574L Gigabit Network Connection                           | 47       | 0.8%    |
| Intel Ethernet Connection (2) I219-LM                             | 46       | 0.78%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 45       | 0.77%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 41       | 0.7%    |
| Ralink MT7601U Wireless Adapter                                   | 38       | 0.65%   |
| Intel Ethernet Connection I217-V                                  | 37       | 0.63%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 36       | 0.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 34       | 0.58%   |
| Intel Wireless 7260                                               | 34       | 0.58%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 34       | 0.58%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 31       | 0.53%   |
| Intel Wireless 8260                                               | 30       | 0.51%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 26       | 0.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 25       | 0.43%   |
| Qualcomm Atheros AR9271 802.11n                                   | 24       | 0.41%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 23       | 0.39%   |
| Intel Wireless 7265                                               | 23       | 0.39%   |
| Intel I210 Gigabit Network Connection                             | 23       | 0.39%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 23       | 0.39%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 23       | 0.39%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 22       | 0.37%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 21       | 0.36%   |
| Realtek 802.11ac NIC                                              | 21       | 0.36%   |
| Ralink RT5370 Wireless Adapter                                    | 21       | 0.36%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 21       | 0.36%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 800      | 44.05%  |
| Realtek Semiconductor                 | 286      | 15.75%  |
| Qualcomm Atheros                      | 150      | 8.26%   |
| TP-Link                               | 103      | 5.67%   |
| Ralink Technology                     | 99       | 5.45%   |
| Broadcom                              | 67       | 3.69%   |
| MediaTek                              | 54       | 2.97%   |
| Ralink                                | 48       | 2.64%   |
| Microsoft                             | 46       | 2.53%   |
| Qualcomm Atheros Communications       | 32       | 1.76%   |
| ASUSTek Computer                      | 26       | 1.43%   |
| NetGear                               | 20       | 1.1%    |
| D-Link                                | 18       | 0.99%   |
| Edimax Technology                     | 15       | 0.83%   |
| Linksys                               | 8        | 0.44%   |
| Belkin Components                     | 7        | 0.39%   |
| D-Link System                         | 6        | 0.33%   |
| AVM                                   | 5        | 0.28%   |
| Wilocity                              | 4        | 0.22%   |
| IMC Networks                          | 3        | 0.17%   |
| Broadcom Limited                      | 3        | 0.17%   |
| Xiaomi                                | 2        | 0.11%   |
| BUFFALO                               | 2        | 0.11%   |
| AboCom Systems                        | 2        | 0.11%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2        | 0.11%   |
| ZTE WCDMA Technologies MSM            | 1        | 0.06%   |
| Toshiba                               | 1        | 0.06%   |
| Sitecom Europe                        | 1        | 0.06%   |
| Sierra Wireless                       | 1        | 0.06%   |
| Samsung Electronics                   | 1        | 0.06%   |
| PLANEX                                | 1        | 0.06%   |
| Mercucys                              | 1        | 0.06%   |
| Gemtek                                | 1        | 0.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 341      | 18.58%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 102      | 5.56%   |
| Intel Wireless-AC 9260                                         | 66       | 3.6%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 58       | 3.16%   |
| Ralink MT7601U Wireless Adapter                                | 38       | 2.07%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 36       | 1.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 34       | 1.85%   |
| Intel Wireless 7260                                            | 34       | 1.85%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 34       | 1.85%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 31       | 1.69%   |
| Intel Wireless 8260                                            | 30       | 1.63%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 26       | 1.42%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 25       | 1.36%   |
| Qualcomm Atheros AR9271 802.11n                                | 24       | 1.31%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 23       | 1.25%   |
| Intel Wireless 7265                                            | 23       | 1.25%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 21       | 1.14%   |
| Realtek 802.11ac NIC                                           | 21       | 1.14%   |
| Ralink RT5370 Wireless Adapter                                 | 21       | 1.14%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 21       | 1.14%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 21       | 1.14%   |
| Intel Wireless 8265 / 8275                                     | 21       | 1.14%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 20       | 1.09%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 20       | 1.09%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 20       | 1.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 19       | 1.04%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 19       | 1.04%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 18       | 0.98%   |
| Microsoft Xbox 360 Wireless Adapter                            | 18       | 0.98%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 17       | 0.93%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 17       | 0.93%   |
| Intel Wireless 3165                                            | 17       | 0.93%   |
| Microsoft Xbox Wireless Adapter for Windows                    | 16       | 0.87%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 13       | 0.71%   |
| Intel Wireless 3160                                            | 13       | 0.71%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 13       | 0.71%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 12       | 0.65%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 12       | 0.65%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 12       | 0.65%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 12       | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 1929     | 50.54%  |
| Intel                                  | 1404     | 36.78%  |
| Qualcomm Atheros                       | 149      | 3.9%    |
| Broadcom                               | 66       | 1.73%   |
| Aquantia                               | 45       | 1.18%   |
| Nvidia                                 | 42       | 1.1%    |
| Marvell Technology Group               | 22       | 0.58%   |
| Xiaomi                                 | 18       | 0.47%   |
| Samsung Electronics                    | 16       | 0.42%   |
| ASIX Electronics                       | 12       | 0.31%   |
| Mellanox Technologies                  | 10       | 0.26%   |
| Google                                 | 10       | 0.26%   |
| Motorola PCS                           | 8        | 0.21%   |
| Broadcom Limited                       | 7        | 0.18%   |
| Apple                                  | 7        | 0.18%   |
| ICS Advent                             | 6        | 0.16%   |
| Huawei Technologies                    | 6        | 0.16%   |
| DisplayLink                            | 6        | 0.16%   |
| Qualcomm                               | 5        | 0.13%   |
| HMD Global                             | 5        | 0.13%   |
| OPPO Electronics                       | 4        | 0.1%    |
| D-Link                                 | 4        | 0.1%    |
| D-Link System                          | 3        | 0.08%   |
| ADMtek                                 | 3        | 0.08%   |
| VIA Technologies                       | 2        | 0.05%   |
| TP-Link                                | 2        | 0.05%   |
| Sundance Technology Inc / IC Plus      | 2        | 0.05%   |
| OnePlus Technology (Shenzhen)          | 2        | 0.05%   |
| Lenovo                                 | 2        | 0.05%   |
| Davicom Semiconductor                  | 2        | 0.05%   |
| ASUSTek Computer                       | 2        | 0.05%   |
| Accton Technology                      | 2        | 0.05%   |
| 3Com                                   | 2        | 0.05%   |
| ZTE WCDMA Technologies MSM             | 1        | 0.03%   |
| Xilinx                                 | 1        | 0.03%   |
| vivo                                   | 1        | 0.03%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.03%   |
| QNAP System                            | 1        | 0.03%   |
| OpenMoko                               | 1        | 0.03%   |
| NetXen Incorporated                    | 1        | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 1613     | 40.46%  |
| Intel I211 Gigabit Network Connection                                         | 368      | 9.23%   |
| Realtek RTL8125 2.5GbE Controller                                             | 227      | 5.69%   |
| Intel Ethernet Connection (2) I219-V                                          | 208      | 5.22%   |
| Intel Ethernet Controller I225-V                                              | 149      | 3.74%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 115      | 2.88%   |
| Intel Ethernet Connection (7) I219-V                                          | 85       | 2.13%   |
| Intel Ethernet Connection I217-LM                                             | 72       | 1.81%   |
| Intel Ethernet Connection (2) I218-V                                          | 66       | 1.66%   |
| Intel 82579V Gigabit Network Connection                                       | 50       | 1.25%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 48       | 1.2%    |
| Intel 82574L Gigabit Network Connection                                       | 47       | 1.18%   |
| Intel Ethernet Connection (2) I219-LM                                         | 46       | 1.15%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 45       | 1.13%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 41       | 1.03%   |
| Intel Ethernet Connection I217-V                                              | 37       | 0.93%   |
| Intel I210 Gigabit Network Connection                                         | 23       | 0.58%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 23       | 0.58%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 23       | 0.58%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 22       | 0.55%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 20       | 0.5%    |
| Nvidia MCP61 Ethernet                                                         | 19       | 0.48%   |
| Intel Ethernet Connection (7) I219-LM                                         | 17       | 0.43%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 16       | 0.4%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 16       | 0.4%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 15       | 0.38%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 14       | 0.35%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 14       | 0.35%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 14       | 0.35%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 13       | 0.33%   |
| Intel 82578DM Gigabit Network Connection                                      | 12       | 0.3%    |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]           | 12       | 0.3%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 11       | 0.28%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 11       | 0.28%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 11       | 0.28%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 11       | 0.28%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 11       | 0.28%   |
| Intel Ethernet Controller X550                                                | 10       | 0.25%   |
| Intel Ethernet Connection (2) I218-LM                                         | 10       | 0.25%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 10       | 0.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 3472     | 66.63%  |
| WiFi     | 1688     | 32.39%  |
| Modem    | 46       | 0.88%   |
| Unknown  | 5        | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2793     | 75.26%  |
| WiFi     | 917      | 24.71%  |
| Modem    | 1        | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 2025     | 57.06%  |
| 2     | 1237     | 34.85%  |
| 3     | 214      | 6.03%   |
| 4     | 28       | 0.79%   |
| 0     | 21       | 0.59%   |
| 5     | 15       | 0.42%   |
| 6     | 6        | 0.17%   |
| 9     | 2        | 0.06%   |
| 8     | 1        | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Desktops | Percent |
|---------|----------|---------|
| No      | 2938     | 82%     |
| Yes     | 642      | 17.92%  |
| Unknown | 3        | 0.08%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 742      | 48.72%  |
| Cambridge Silicon Radio         | 327      | 21.47%  |
| ASUSTek Computer                | 110      | 7.22%   |
| Realtek Semiconductor           | 85       | 5.58%   |
| Broadcom                        | 77       | 5.06%   |
| MediaTek                        | 34       | 2.23%   |
| Qualcomm Atheros Communications | 33       | 2.17%   |
| TP-Link                         | 23       | 1.51%   |
| IMC Networks                    | 20       | 1.31%   |
| Apple                           | 16       | 1.05%   |
| Foxconn / Hon Hai               | 9        | 0.59%   |
| Belkin Components               | 8        | 0.53%   |
| HTC (High Tech Computer)        | 6        | 0.39%   |
| Edimax Technology               | 6        | 0.39%   |
| Lite-On Technology              | 4        | 0.26%   |
| Integrated System Solution      | 4        | 0.26%   |
| Dynex                           | 4        | 0.26%   |
| Toshiba                         | 3        | 0.2%    |
| Dell                            | 3        | 0.2%    |
| SINO WEALTH                     | 2        | 0.13%   |
| Hewlett-Packard                 | 2        | 0.13%   |
| Kensington                      | 1        | 0.07%   |
| D-Link System                   | 1        | 0.07%   |
| D-Link                          | 1        | 0.07%   |
| Creative Technology             | 1        | 0.07%   |
| BUFFALO                         | 1        | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 327      | 21.4%   |
| Intel AX200 Bluetooth                                                | 319      | 20.88%  |
| Intel Bluetooth wireless interface                                   | 126      | 8.25%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 100      | 6.54%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 62       | 4.06%   |
| Realtek Bluetooth Radio                                              | 61       | 3.99%   |
| Intel AX210 Bluetooth                                                | 54       | 3.53%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 54       | 3.53%   |
| Intel AX201 Bluetooth                                                | 48       | 3.14%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 42       | 2.75%   |
| MediaTek Wireless_Device                                             | 34       | 2.23%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 26       | 1.7%    |
| TP-Link UB500 Adapter                                                | 23       | 1.51%   |
| ASUS Bluetooth Radio                                                 | 20       | 1.31%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 14       | 0.92%   |
| Qualcomm Atheros  Bluetooth Device                                   | 14       | 0.92%   |
| ASUS Bluetooth Adapter                                               | 14       | 0.92%   |
| ASUS ASUS USB-BT500                                                  | 13       | 0.85%   |
| Apple Bluetooth Host Controller                                      | 11       | 0.72%   |
| ASUS BCM20702A0                                                      | 8        | 0.52%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 7        | 0.46%   |
| Intel Bluetooth Device                                               | 7        | 0.46%   |
| IMC Networks Bluetooth Radio                                         | 7        | 0.46%   |
| Foxconn / Hon Hai Wireless_Device                                    | 7        | 0.46%   |
| Realtek RTL8821A Bluetooth                                           | 6        | 0.39%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 6        | 0.39%   |
| IMC Networks Bluetooth Device                                        | 6        | 0.39%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 6        | 0.39%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                     | 6        | 0.39%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 6        | 0.39%   |
| ASUS Bluetooth Device                                                | 6        | 0.39%   |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 5        | 0.33%   |
| Edimax Bluetooth Adapter                                             | 5        | 0.33%   |
| Lite-On Bluetooth Device                                             | 4        | 0.26%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 4        | 0.26%   |
| IMC Networks Wireless_Device                                         | 4        | 0.26%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 4        | 0.26%   |
| Broadcom BCM2045 Bluetooth                                           | 4        | 0.26%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                | 4        | 0.26%   |
| Integrated System Solution Bluetooth Device                          | 3        | 0.2%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 1918     | 29.2%   |
| Intel                                | 1880     | 28.62%  |
| Nvidia                               | 1462     | 22.26%  |
| C-Media Electronics                  | 222      | 3.38%   |
| Logitech                             | 106      | 1.61%   |
| Creative Labs                        | 71       | 1.08%   |
| Kingston Technology                  | 47       | 0.72%   |
| JMTek                                | 47       | 0.72%   |
| SteelSeries ApS                      | 44       | 0.67%   |
| Texas Instruments                    | 43       | 0.65%   |
| Focusrite-Novation                   | 43       | 0.65%   |
| Corsair                              | 42       | 0.64%   |
| Razer USA                            | 39       | 0.59%   |
| Creative Technology                  | 38       | 0.58%   |
| ASUSTek Computer                     | 30       | 0.46%   |
| Generalplus Technology               | 27       | 0.41%   |
| Plantronics                          | 24       | 0.37%   |
| GN Netcom                            | 24       | 0.37%   |
| Blue Microphones                     | 24       | 0.37%   |
| GYROCOM C&C                          | 20       | 0.3%    |
| Realtek Semiconductor                | 19       | 0.29%   |
| Sony                                 | 17       | 0.26%   |
| Samson Technologies                  | 16       | 0.24%   |
| XMOS                                 | 13       | 0.2%    |
| RODE Microphones                     | 13       | 0.2%    |
| Micro Star International             | 12       | 0.18%   |
| Giga-Byte Technology                 | 12       | 0.18%   |
| Tenx Technology                      | 11       | 0.17%   |
| Cambridge Silicon Radio              | 11       | 0.17%   |
| Dell                                 | 10       | 0.15%   |
| VIA Technologies                     | 9        | 0.14%   |
| Schiit Audio                         | 9        | 0.14%   |
| Yamaha                               | 8        | 0.12%   |
| SAVITECH                             | 8        | 0.12%   |
| FiiO Electronics Technology          | 8        | 0.12%   |
| DSEA A/S                             | 8        | 0.12%   |
| Thesycon Systemsoftware & Consulting | 7        | 0.11%   |
| Sennheiser Communications            | 7        | 0.11%   |
| M-Audio                              | 7        | 0.11%   |
| Lenovo                               | 7        | 0.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 592      | 7.58%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 319      | 4.08%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 294      | 3.76%   |
| AMD Family 17h/19h HD Audio Controller                                     | 246      | 3.15%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 241      | 3.09%   |
| Intel 200 Series PCH HD Audio                                              | 218      | 2.79%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 207      | 2.65%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 195      | 2.5%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 190      | 2.43%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 178      | 2.28%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 166      | 2.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 164      | 2.1%    |
| AMD Navi 10 HDMI Audio                                                     | 149      | 1.91%   |
| Intel Cannon Lake PCH cAVS                                                 | 146      | 1.87%   |
| Nvidia GP107GL High Definition Audio Controller                            | 144      | 1.84%   |
| Nvidia GP106 High Definition Audio Controller                              | 135      | 1.73%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 133      | 1.7%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 110      | 1.41%   |
| Nvidia GP104 High Definition Audio Controller                              | 103      | 1.32%   |
| Nvidia TU116 High Definition Audio Controller                              | 101      | 1.29%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 95       | 1.22%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 95       | 1.22%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 95       | 1.22%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 93       | 1.19%   |
| AMD FCH Azalia Controller                                                  | 86       | 1.1%    |
| Nvidia TU106 High Definition Audio Controller                              | 75       | 0.96%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 74       | 0.95%   |
| Intel Alder Lake-S HD Audio Controller                                     | 70       | 0.9%    |
| Nvidia GA104 High Definition Audio Controller                              | 65       | 0.83%   |
| Nvidia TU104 HD Audio Controller                                           | 63       | 0.81%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 63       | 0.81%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 63       | 0.81%   |
| Nvidia High Definition Audio Controller                                    | 60       | 0.77%   |
| Nvidia GM204 High Definition Audio Controller                              | 57       | 0.73%   |
| Nvidia GM206 High Definition Audio Controller                              | 55       | 0.7%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 55       | 0.7%    |
| Intel C610/X99 series chipset HD Audio Controller                          | 53       | 0.68%   |
| Nvidia GP108 High Definition Audio Controller                              | 49       | 0.63%   |
| Nvidia GK107 HDMI Audio Controller                                         | 47       | 0.6%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 43       | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 358      | 18.91%  |
| Corsair             | 319      | 16.85%  |
| G.Skill             | 241      | 12.73%  |
| Unknown             | 197      | 10.41%  |
| Crucial             | 152      | 8.03%   |
| Samsung Electronics | 145      | 7.66%   |
| SK hynix            | 131      | 6.92%   |
| Micron Technology   | 79       | 4.17%   |
| A-DATA Technology   | 41       | 2.17%   |
| Team                | 34       | 1.8%    |
| Patriot             | 34       | 1.8%    |
| Ramaxel Technology  | 14       | 0.74%   |
| Nanya Technology    | 13       | 0.69%   |
| Unknown             | 12       | 0.63%   |
| Elpida              | 9        | 0.48%   |
| Smart               | 8        | 0.42%   |
| GeIL                | 8        | 0.42%   |
| GOODRAM             | 7        | 0.37%   |
| AMD                 | 7        | 0.37%   |
| Silicon Power       | 6        | 0.32%   |
| PNY                 | 6        | 0.32%   |
| Transcend           | 5        | 0.26%   |
| Qumo                | 4        | 0.21%   |
| Qimonda             | 4        | 0.21%   |
| Avant               | 4        | 0.21%   |
| Unifosa             | 3        | 0.16%   |
| CSX                 | 3        | 0.16%   |
| Apacer              | 3        | 0.16%   |
| Unknown (ABCD)      | 2        | 0.11%   |
| Patriot Memory      | 2        | 0.11%   |
| OCZ                 | 2        | 0.11%   |
| MINPO               | 2        | 0.11%   |
| Goldkey             | 2        | 0.11%   |
| Golden Empire       | 2        | 0.11%   |
| Gold Key            | 2        | 0.11%   |
| zApacer             | 1        | 0.05%   |
| V-GeN               | 1        | 0.05%   |
| V-Color             | 1        | 0.05%   |
| Unknown (AB)        | 1        | 0.05%   |
| Unknown (9B)        | 1        | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s     | 34       | 1.65%   |
| Corsair RAM CMK16GX4M2B3000C15 8192MB DIMM DDR4 3200MT/s  | 25       | 1.21%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s      | 21       | 1.02%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s      | 18       | 0.87%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s         | 17       | 0.83%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s       | 16       | 0.78%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s       | 16       | 0.78%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s    | 15       | 0.73%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                      | 13       | 0.63%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s       | 13       | 0.63%   |
| Unknown                                                   | 12       | 0.58%   |
| SK hynix RAM HMT451U6AFR8C-PB 4096MB DIMM DDR3 1600MT/s   | 11       | 0.53%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s    | 11       | 0.53%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                  | 10       | 0.49%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3266MT/s        | 10       | 0.49%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s         | 10       | 0.49%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s       | 10       | 0.49%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3800MT/s    | 10       | 0.49%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                 | 9        | 0.44%   |
| Unknown RAM Module 2GB DIMM 800MT/s                       | 9        | 0.44%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s     | 9        | 0.44%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s     | 9        | 0.44%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s      | 8        | 0.39%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s    | 8        | 0.39%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s       | 8        | 0.39%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s     | 8        | 0.39%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s        | 8        | 0.39%   |
| G.Skill RAM F4-2400C15-8GVR 8GB DIMM DDR4 3200MT/s        | 8        | 0.39%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s    | 8        | 0.39%   |
| Unknown RAM Module 2GB DIMM SDRAM                         | 7        | 0.34%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s      | 7        | 0.34%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s       | 7        | 0.34%   |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 3200MT/s      | 7        | 0.34%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s         | 7        | 0.34%   |
| G.Skill RAM F3-12800CL10-8GBXL 8GB DIMM DDR3 1600MT/s     | 7        | 0.34%   |
| Corsair RAM CMK32GX4M2B3000C15 16384MB DIMM DDR4 3000MT/s | 7        | 0.34%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3100MT/s    | 7        | 0.34%   |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3200MT/s     | 7        | 0.34%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                      | 6        | 0.29%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                      | 6        | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 970      | 57.36%  |
| DDR3    | 486      | 28.74%  |
| Unknown | 86       | 5.09%   |
| DDR2    | 62       | 3.67%   |
| SDRAM   | 40       | 2.37%   |
| DDR5    | 32       | 1.89%   |
| DDR     | 10       | 0.59%   |
| LPDDR3  | 3        | 0.18%   |
| LPDDR4  | 2        | 0.12%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 1587     | 94.92%  |
| SODIMM       | 72       | 4.31%   |
| RIMM         | 8        | 0.48%   |
| FB-DIMM      | 3        | 0.18%   |
| Row Of Chips | 2        | 0.12%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 745      | 40.96%  |
| 16384 | 384      | 21.11%  |
| 4096  | 374      | 20.56%  |
| 2048  | 170      | 9.35%   |
| 32768 | 105      | 5.77%   |
| 1024  | 36       | 1.98%   |
| 512   | 4        | 0.22%   |
| 256   | 1        | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 283      | 15.27%  |
| 3200    | 230      | 12.41%  |
| 3600    | 181      | 9.77%   |
| 1333    | 156      | 8.42%   |
| 2400    | 122      | 6.58%   |
| 2133    | 96       | 5.18%   |
| 2667    | 78       | 4.21%   |
| 800     | 56       | 3.02%   |
| 3000    | 49       | 2.64%   |
| 3400    | 48       | 2.59%   |
| 3466    | 47       | 2.54%   |
| 667     | 40       | 2.16%   |
| 1867    | 39       | 2.1%    |
| 3800    | 30       | 1.62%   |
| 2666    | 28       | 1.51%   |
| 3733    | 27       | 1.46%   |
| 1866    | 26       | 1.4%    |
| 3866    | 25       | 1.35%   |
| Unknown | 23       | 1.24%   |
| 2800    | 22       | 1.19%   |
| 2933    | 21       | 1.13%   |
| 1066    | 18       | 0.97%   |
| 4800    | 17       | 0.92%   |
| 1800    | 15       | 0.81%   |
| 3666    | 14       | 0.76%   |
| 3266    | 12       | 0.65%   |
| 1067    | 11       | 0.59%   |
| 5200    | 8        | 0.43%   |
| 3333    | 8        | 0.43%   |
| 3100    | 8        | 0.43%   |
| 1334    | 8        | 0.43%   |
| 3334    | 6        | 0.32%   |
| 533     | 6        | 0.32%   |
| 2733    | 5        | 0.27%   |
| 2000    | 5        | 0.27%   |
| 400     | 5        | 0.27%   |
| 3534    | 4        | 0.22%   |
| 3151    | 4        | 0.22%   |
| 333     | 4        | 0.22%   |
| 6000    | 3        | 0.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 62       | 38.04%  |
| Brother Industries    | 41       | 25.15%  |
| Canon                 | 17       | 10.43%  |
| Seiko Epson           | 12       | 7.36%   |
| Samsung Electronics   | 12       | 7.36%   |
| Prolific Technology   | 5        | 3.07%   |
| Lexmark International | 4        | 2.45%   |
| Xerox                 | 2        | 1.23%   |
| Kyocera               | 2        | 1.23%   |
| Star Micronics        | 1        | 0.61%   |
| QinHeng Electronics   | 1        | 0.61%   |
| Graphtec America      | 1        | 0.61%   |
| Dymo-CoStar           | 1        | 0.61%   |
| Dell                  | 1        | 0.61%   |
| Boca Systems          | 1        | 0.61%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Prolific PL2305 Parallel Port                | 5        | 3.05%   |
| Samsung M2070 Series                         | 4        | 2.44%   |
| HP LaserJet Professional P 1102w             | 4        | 2.44%   |
| Brother HL-L2340D series                     | 4        | 2.44%   |
| HP ENVY 5000 series                          | 3        | 1.83%   |
| HP ENVY 4520 series                          | 3        | 1.83%   |
| HP DeskJet F300 series                       | 3        | 1.83%   |
| Brother Printer                              | 3        | 1.83%   |
| Brother HL-1110 series                       | 3        | 1.83%   |
| Seiko Epson WF-2860 Series                   | 2        | 1.22%   |
| Seiko Epson Printer                          | 2        | 1.22%   |
| Samsung ML-216x Series Laser Printer         | 2        | 1.22%   |
| HP OfficeJet 6950                            | 2        | 1.22%   |
| HP DeskJet 3700 series                       | 2        | 1.22%   |
| HP DeskJet 3630 series                       | 2        | 1.22%   |
| HP DeskJet 2620 All-in-One Printer           | 2        | 1.22%   |
| HP DeskJet 2130 series                       | 2        | 1.22%   |
| Canon TS3300 series                          | 2        | 1.22%   |
| Canon TR4500 series                          | 2        | 1.22%   |
| Canon LiDE 300                               | 2        | 1.22%   |
| Brother MFC-9330CDW                          | 2        | 1.22%   |
| Brother HL-2230 series                       | 2        | 1.22%   |
| Brother HL-2030 Laser Printer                | 2        | 1.22%   |
| Xerox Phaser 6500DN                          | 1        | 0.61%   |
| Xerox Phaser 3010                            | 1        | 0.61%   |
| Star Micronics TUP592 (STR_T-001)            | 1        | 0.61%   |
| Seiko Epson XP-100 Series                    | 1        | 0.61%   |
| Seiko Epson WP-4020 Series                   | 1        | 0.61%   |
| Seiko Epson WF-2510 Series                   | 1        | 0.61%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1        | 0.61%   |
| Seiko Epson L3110 Series                     | 1        | 0.61%   |
| Seiko Epson L300 Series                      | 1        | 0.61%   |
| Seiko Epson L222 Series                      | 1        | 0.61%   |
| Seiko Epson L100 Series                      | 1        | 0.61%   |
| Samsung Xerox Phaser 3117 Laser Printer      | 1        | 0.61%   |
| Samsung SCX-4623 Series                      | 1        | 0.61%   |
| Samsung SCX-4300 Series                      | 1        | 0.61%   |
| Samsung ML-2855 Series                       | 1        | 0.61%   |
| Samsung ML-2010P Mono Laser Printer          | 1        | 0.61%   |
| Samsung ML-1640 Series Laser Printer         | 1        | 0.61%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 22       | 53.66%  |
| Seiko Epson     | 13       | 31.71%  |
| Hewlett-Packard | 4        | 9.76%   |
| UMAX            | 1        | 2.44%   |
| Mustek Systems  | 1        | 2.44%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Seiko Epson GT-X770 [Perfection V500]                    | 5        | 12.2%   |
| Canon CanoScan LiDE 210                                  | 4        | 9.76%   |
| Canon CanoScan LIDE 25                                   | 3        | 7.32%   |
| Canon CanoScan LiDE 220                                  | 3        | 7.32%   |
| Canon CanoScan LiDE 100                                  | 3        | 7.32%   |
| Seiko Epson GT-6600U [Perfection 610]                    | 2        | 4.88%   |
| Canon CanoScan N670U/N676U/LiDE 20                       | 2        | 4.88%   |
| Canon CanoScan LiDE 110                                  | 2        | 4.88%   |
| UMAX Astra 2200/2200SU                                   | 1        | 2.44%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]              | 1        | 2.44%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]              | 1        | 2.44%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo]  | 1        | 2.44%   |
| Seiko Epson GT-F670 [Perfection V200 Photo]              | 1        | 2.44%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1        | 2.44%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]            | 1        | 2.44%   |
| Mustek Systems BearPaw 2448 TA Plus                      | 1        | 2.44%   |
| HP ScanJet G4050                                         | 1        | 2.44%   |
| HP ScanJet 5590                                          | 1        | 2.44%   |
| HP ScanJet 3400cse                                       | 1        | 2.44%   |
| HP ScanJet 2400c                                         | 1        | 2.44%   |
| Canon CanoScan N1240U/LiDE 30                            | 1        | 2.44%   |
| Canon CanoScan LiDE 70                                   | 1        | 2.44%   |
| Canon CanoScan LiDE 200                                  | 1        | 2.44%   |
| Canon CanoScan LiDE 120                                  | 1        | 2.44%   |
| Canon CanoScan 4400F                                     | 1        | 2.44%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 426      | 46.3%   |
| Microsoft                     | 74       | 8.04%   |
| Microdia                      | 53       | 5.76%   |
| Samsung Electronics           | 32       | 3.48%   |
| Apple                         | 31       | 3.37%   |
| Sunplus Innovation Technology | 28       | 3.04%   |
| KYE Systems (Mouse Systems)   | 20       | 2.17%   |
| Realtek Semiconductor         | 19       | 2.07%   |
| Chicony Electronics           | 17       | 1.85%   |
| Creative Technology           | 15       | 1.63%   |
| Generalplus Technology        | 13       | 1.41%   |
| Cubeternet                    | 13       | 1.41%   |
| ARC International             | 12       | 1.3%    |
| Z-Star Microelectronics       | 10       | 1.09%   |
| 2M UVC CAMERA                 | 9        | 0.98%   |
| Razer USA                     | 8        | 0.87%   |
| Jieli Technology              | 8        | 0.87%   |
| Lenovo                        | 7        | 0.76%   |
| Hewlett-Packard               | 7        | 0.76%   |
| GEMBIRD                       | 7        | 0.76%   |
| AVerMedia Technologies        | 7        | 0.76%   |
| Trust                         | 6        | 0.65%   |
| MacroSilicon                  | 6        | 0.65%   |
| LG Electronics                | 5        | 0.54%   |
| Arkmicro Technologies         | 5        | 0.54%   |
| Sunplus IT                    | 4        | 0.43%   |
| Aveo Technology               | 4        | 0.43%   |
| YGTek                         | 3        | 0.33%   |
| Unknown                       | 3        | 0.33%   |
| OmniVision Technologies       | 3        | 0.33%   |
| Huawei Technologies           | 3        | 0.33%   |
| Genesys Logic                 | 3        | 0.33%   |
| Asuscom Network               | 3        | 0.33%   |
| Alcor Micro                   | 3        | 0.33%   |
| A4Tech                        | 3        | 0.33%   |
| WaveRider Communications      | 2        | 0.22%   |
| Valve Software                | 2        | 0.22%   |
| SunplusIT                     | 2        | 0.22%   |
| Sonix Technology              | 2        | 0.22%   |
| Pixart Imaging                | 2        | 0.22%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                | 97       | 10.39%  |
| Logitech Webcam C270                       | 91       | 9.74%   |
| Samsung Galaxy series, misc. (MTP mode)    | 31       | 3.32%   |
| Logitech HD Webcam C525                    | 28       | 3%      |
| Microsoft LifeCam HD-3000                  | 26       | 2.78%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X            | 26       | 2.78%   |
| Logitech C922 Pro Stream Webcam            | 23       | 2.46%   |
| Microdia Webcam Vitade AF                  | 21       | 2.25%   |
| Logitech HD Webcam C615                    | 21       | 2.25%   |
| Logitech Webcam C310                       | 18       | 1.93%   |
| Microsoft LifeCam Cinema                   | 17       | 1.82%   |
| Logitech Webcam Pro 9000                   | 14       | 1.5%    |
| Logitech BRIO Ultra HD Webcam              | 14       | 1.5%    |
| Logitech Webcam C925e                      | 13       | 1.39%   |
| Logitech Webcam C170                       | 13       | 1.39%   |
| ARC International Camera                   | 12       | 1.28%   |
| Microdia USB 2.0 Camera                    | 11       | 1.18%   |
| Logitech Webcam C930e                      | 11       | 1.18%   |
| Logitech StreamCam                         | 10       | 1.07%   |
| Logitech C920 PRO HD Webcam                | 10       | 1.07%   |
| 2M UVC CAMERA NexiGo N60 FHD Webcam        | 9        | 0.96%   |
| Sunplus HD 720P webcam                     | 8        | 0.86%   |
| Logitech QuickCam Pro 9000                 | 8        | 0.86%   |
| Jieli USB PHY 2.0                          | 8        | 0.86%   |
| Realtek Full HD webcam                     | 7        | 0.75%   |
| Microdia Camera                            | 7        | 0.75%   |
| Logitech BRIO 4K Stream Edition            | 7        | 0.75%   |
| GEMBIRD USB2.0 PC CAMERA                   | 7        | 0.75%   |
| Razer USA Gaming Webcam [Kiyo]             | 6        | 0.64%   |
| Microsoft LifeCam VX-5000                  | 6        | 0.64%   |
| Generalplus GENERAL WEBCAM                 | 6        | 0.64%   |
| Sunplus Canyon CNS-CWC5 Webcam             | 5        | 0.54%   |
| Microsoft LifeCam Studio                   | 5        | 0.54%   |
| MacroSilicon USB Video                     | 5        | 0.54%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera | 5        | 0.54%   |
| Creative Live! Cam Sync HD [VF0770]        | 5        | 0.54%   |
| Creative Live! Cam Sync 1080p              | 5        | 0.54%   |
| Realtek FULL HD WEB CAM                    | 4        | 0.43%   |
| Microsoft MicrosoftÂ LifeCam Cinema       | 4        | 0.43%   |
| Microsoft LifeCam VX-500 [1357]            | 4        | 0.43%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| DigitalPersona        | 3        | 25%     |
| LighTuning Technology | 2        | 16.67%  |
| Elan Microelectronics | 2        | 16.67%  |
| AuthenTec             | 2        | 16.67%  |
| Synaptics             | 1        | 8.33%   |
| Microsoft             | 1        | 8.33%   |
| Dell                  | 1        | 8.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| DigitalPersona Fingerprint Reader              | 3        | 25%     |
| Elan fingerprint sensor [FeinTech FPS00200]    | 2        | 16.67%  |
| Synaptics  WBDI Fingerprint Reader - USB 052   | 1        | 8.33%   |
| Microsoft Fingerprint Reader                   | 1        | 8.33%   |
| LighTuning Fingerprint Sensor                  | 1        | 8.33%   |
| LighTuning EgisTec Touch Fingerprint Sensor    | 1        | 8.33%   |
| Dell MS819 Wired Mouse With Fingerprint Reader | 1        | 8.33%   |
| AuthenTec Fingerprint Sensor                   | 1        | 8.33%   |
| AuthenTec AES1600                              | 1        | 8.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Yubico.com                        | 5        | 13.51%  |
| Realtek Semiconductor             | 5        | 13.51%  |
| Alcor Micro                       | 5        | 13.51%  |
| SCM Microsystems                  | 4        | 10.81%  |
| VASCO Data Security International | 3        | 8.11%   |
| OmniKey                           | 3        | 8.11%   |
| Gemalto (was Gemplus)             | 2        | 5.41%   |
| Aktiv                             | 2        | 5.41%   |
| Reiner SCT Kartensysteme          | 1        | 2.7%    |
| Fujitsu Siemens Computers         | 1        | 2.7%    |
| Feitian Technologies              | 1        | 2.7%    |
| Clay Logic                        | 1        | 2.7%    |
| Chicony Electronics               | 1        | 2.7%    |
| Cherry                            | 1        | 2.7%    |
| Bit4id                            | 1        | 2.7%    |
| Advanced Card Systems             | 1        | 2.7%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface                          | 5        | 13.51%  |
| Yubico.com Yubikey 4 U2F+CCID                                              | 3        | 8.11%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                     | 3        | 8.11%   |
| Alcor Micro AU9540 Smartcard Reader                                        | 3        | 8.11%   |
| VASCO Data Security International Digipass 905 SmartCard Reader            | 2        | 5.41%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                          | 2        | 5.41%   |
| Alcor Micro Watchdata W 1981                                               | 2        | 5.41%   |
| Aktiv Rutoken lite                                                         | 2        | 5.41%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                        | 1        | 2.7%    |
| Yubico.com Yubikey 4/5 CCID                                                | 1        | 2.7%    |
| VASCO Data Security International DIGIPASS 870                             | 1        | 2.7%    |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                 | 1        | 2.7%    |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 1        | 2.7%    |
| OmniKey CardMan 3121 (HID Technologies)                                    | 1        | 2.7%    |
| OmniKey CardMan 3021 / 3121                                                | 1        | 2.7%    |
| OmniKey CardMan 1021                                                       | 1        | 2.7%    |
| Fujitsu Siemens Computers SmartCard Reader 2A                              | 1        | 2.7%    |
| Feitian Technologies FT SCR310                                             | 1        | 2.7%    |
| Clay Logic Nitrokey Pro                                                    | 1        | 2.7%    |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                       | 1        | 2.7%    |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                | 1        | 2.7%    |
| Bit4id miniLector EVO                                                      | 1        | 2.7%    |
| Advanced Card Systems ACR122U                                              | 1        | 2.7%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 3066     | 85.67%  |
| 1     | 442      | 12.35%  |
| 2     | 49       | 1.37%   |
| 3     | 11       | 0.31%   |
| 4     | 5        | 0.14%   |
| 5     | 4        | 0.11%   |
| 8     | 1        | 0.03%   |
| 6     | 1        | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 168      | 29.37%  |
| Graphics card            | 152      | 26.57%  |
| Unassigned class         | 58       | 10.14%  |
| Sound                    | 34       | 5.94%   |
| Multimedia controller    | 30       | 5.24%   |
| Communication controller | 30       | 5.24%   |
| Camera                   | 29       | 5.07%   |
| Storage/raid             | 11       | 1.92%   |
| Network                  | 11       | 1.92%   |
| Fingerprint reader       | 11       | 1.92%   |
| Bluetooth                | 9        | 1.57%   |
| Net/ethernet             | 6        | 1.05%   |
| Modem                    | 5        | 0.87%   |
| Chipcard                 | 5        | 0.87%   |
| Card reader              | 5        | 0.87%   |
| Firewire controller      | 2        | 0.35%   |
| Dvb card                 | 2        | 0.35%   |
| Wireless                 | 1        | 0.17%   |
| Tv card                  | 1        | 0.17%   |
| Storage/ata              | 1        | 0.17%   |
| Storage                  | 1        | 0.17%   |

