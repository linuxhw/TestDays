Manjaro - Tested Hardware & Statistics (Desktops)
-------------------------------------------------

A project to collect tested hardware configurations for Manjaro.

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

Total: 4065

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | B550 GAMING X V2            | [1f4aa5bf97](https://linux-hardware.org/?probe=1f4aa5bf97) | Aug 12, 2023 |
| Gigabyte      | M720-US3                    | [222bc02e4f](https://linux-hardware.org/?probe=222bc02e4f) | Aug 11, 2023 |
| HP            | 83E8                        | [a782638343](https://linux-hardware.org/?probe=a782638343) | Aug 11, 2023 |
| Gigabyte      | X570S AERO G                | [22916d4c12](https://linux-hardware.org/?probe=22916d4c12) | Aug 10, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [0521e62bf9](https://linux-hardware.org/?probe=0521e62bf9) | Aug 10, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [198fcb1fc2](https://linux-hardware.org/?probe=198fcb1fc2) | Aug 10, 2023 |
| MSI           | X370 GAMING M7 ACK          | [00bb870b78](https://linux-hardware.org/?probe=00bb870b78) | Aug 09, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [4a7cc2835f](https://linux-hardware.org/?probe=4a7cc2835f) | Aug 09, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | [f50b51555f](https://linux-hardware.org/?probe=f50b51555f) | Aug 09, 2023 |
| ASUSTek       | M5A97 PLUS                  | [0c755e3349](https://linux-hardware.org/?probe=0c755e3349) | Aug 09, 2023 |
| Gigabyte      | B550M DS3H                  | [7889f62638](https://linux-hardware.org/?probe=7889f62638) | Aug 08, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [121b892fa8](https://linux-hardware.org/?probe=121b892fa8) | Aug 08, 2023 |
| MSI           | B550-A PRO                  | [61c59e48d2](https://linux-hardware.org/?probe=61c59e48d2) | Aug 08, 2023 |
| AZW           | U59                         | [d7b7b7641b](https://linux-hardware.org/?probe=d7b7b7641b) | Aug 07, 2023 |
| Gigabyte      | F2A68HM-H                   | [4323af2ade](https://linux-hardware.org/?probe=4323af2ade) | Aug 07, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [164e109040](https://linux-hardware.org/?probe=164e109040) | Aug 06, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [230032816b](https://linux-hardware.org/?probe=230032816b) | Aug 06, 2023 |
| Gigabyte      | Z370 HD3-CF                 | [97505d521e](https://linux-hardware.org/?probe=97505d521e) | Aug 06, 2023 |
| Gigabyte      | X570 GAMING X               | [34dc1bc754](https://linux-hardware.org/?probe=34dc1bc754) | Aug 06, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [66d6565a06](https://linux-hardware.org/?probe=66d6565a06) | Aug 05, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [70aa79986f](https://linux-hardware.org/?probe=70aa79986f) | Aug 05, 2023 |
| HP            | 8055                        | [21c8e1fdc2](https://linux-hardware.org/?probe=21c8e1fdc2) | Aug 03, 2023 |
| ASRock        | B650M PG Riptide            | [2e309e76d7](https://linux-hardware.org/?probe=2e309e76d7) | Aug 03, 2023 |
| HP            | 2215                        | [f0589325fc](https://linux-hardware.org/?probe=f0589325fc) | Aug 03, 2023 |
| Unknown       | Unknown                     | [92f3b39535](https://linux-hardware.org/?probe=92f3b39535) | Aug 02, 2023 |
| MSI           | X570-A PRO                  | [1acfa69d70](https://linux-hardware.org/?probe=1acfa69d70) | Aug 02, 2023 |
| ASUSTek       | P8Z77-V                     | [65dcccd422](https://linux-hardware.org/?probe=65dcccd422) | Jul 30, 2023 |
| MSI           | PRO X670-P WIFI             | [19b97459c1](https://linux-hardware.org/?probe=19b97459c1) | Jul 30, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [c8116c748a](https://linux-hardware.org/?probe=c8116c748a) | Jul 29, 2023 |
| Dell          | 0PU052                      | [f51bdc3bf5](https://linux-hardware.org/?probe=f51bdc3bf5) | Jul 28, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [06731541dd](https://linux-hardware.org/?probe=06731541dd) | Jul 28, 2023 |
| ASUSTek       | PRIME X570-P                | [fd41467554](https://linux-hardware.org/?probe=fd41467554) | Jul 28, 2023 |
| ASUSTek       | P8Z77-V                     | [e550626a11](https://linux-hardware.org/?probe=e550626a11) | Jul 27, 2023 |
| Gigabyte      | B360M HD3                   | [900f299e10](https://linux-hardware.org/?probe=900f299e10) | Jul 26, 2023 |
| ASRock        | X570 Pro4                   | [96dcaad094](https://linux-hardware.org/?probe=96dcaad094) | Jul 26, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [cfdb26e14f](https://linux-hardware.org/?probe=cfdb26e14f) | Jul 25, 2023 |
| MSI           | ZH77A-G41                   | [8528da5360](https://linux-hardware.org/?probe=8528da5360) | Jul 24, 2023 |
| MSI           | PRO Z690-A WIFI             | [8f3dc1cb65](https://linux-hardware.org/?probe=8f3dc1cb65) | Jul 24, 2023 |
| ASUSTek       | P8Z77-V                     | [a8f7397fcf](https://linux-hardware.org/?probe=a8f7397fcf) | Jul 23, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [6094ce5501](https://linux-hardware.org/?probe=6094ce5501) | Jul 23, 2023 |
| Gigabyte      | X570 GAMING X               | [b0e064a98a](https://linux-hardware.org/?probe=b0e064a98a) | Jul 23, 2023 |
| MSI           | B450 TOMAHAWK               | [bda4392623](https://linux-hardware.org/?probe=bda4392623) | Jul 22, 2023 |
| AMI           | Intel                       | [fe2999b2aa](https://linux-hardware.org/?probe=fe2999b2aa) | Jul 22, 2023 |
| Lenovo        | ThinkCentre M58e 7303AZ2    | [6285ba6300](https://linux-hardware.org/?probe=6285ba6300) | Jul 22, 2023 |
| ASUSTek       | PRIME A320M-K               | [42fc5ff144](https://linux-hardware.org/?probe=42fc5ff144) | Jul 21, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [65972dbe80](https://linux-hardware.org/?probe=65972dbe80) | Jul 21, 2023 |
| ASRock        | B450 Pro4                   | [6df8743ac8](https://linux-hardware.org/?probe=6df8743ac8) | Jul 21, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [2dbb6f2466](https://linux-hardware.org/?probe=2dbb6f2466) | Jul 20, 2023 |
| ASUSTek       | SABERTOOTH X99              | [3014bea7d8](https://linux-hardware.org/?probe=3014bea7d8) | Jul 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | [765ac65603](https://linux-hardware.org/?probe=765ac65603) | Jul 20, 2023 |
| ASUSTek       | PRIME X570-P                | [e6bbbc4d41](https://linux-hardware.org/?probe=e6bbbc4d41) | Jul 20, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [3d605ad77f](https://linux-hardware.org/?probe=3d605ad77f) | Jul 19, 2023 |
| ASRock        | B450 Gaming K4              | [ad2c07dc8e](https://linux-hardware.org/?probe=ad2c07dc8e) | Jul 17, 2023 |
| HP            | 83E0                        | [35abf30fff](https://linux-hardware.org/?probe=35abf30fff) | Jul 16, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [a01053a59a](https://linux-hardware.org/?probe=a01053a59a) | Jul 15, 2023 |
| ASUSTek       | PRIME Z690-P D4             | [b8b0b27baf](https://linux-hardware.org/?probe=b8b0b27baf) | Jul 14, 2023 |
| ASRock        | B760M PG Riptide            | [4092f45d41](https://linux-hardware.org/?probe=4092f45d41) | Jul 14, 2023 |
| ASRock        | B760M PG Riptide            | [1ee27caac4](https://linux-hardware.org/?probe=1ee27caac4) | Jul 14, 2023 |
| HP            | 3397                        | [d20efc761c](https://linux-hardware.org/?probe=d20efc761c) | Jul 13, 2023 |
| ASRock        | B450 Gaming K4              | [1c43d30f02](https://linux-hardware.org/?probe=1c43d30f02) | Jul 13, 2023 |
| Dell          | 0T10XW A01                  | [51cf410b69](https://linux-hardware.org/?probe=51cf410b69) | Jul 12, 2023 |
| MSI           | X370 GAMING M7 ACK          | [e62935623d](https://linux-hardware.org/?probe=e62935623d) | Jul 12, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [611ea83c30](https://linux-hardware.org/?probe=611ea83c30) | Jul 11, 2023 |
| Gigabyte      | Z390 AORUS PRO-CF           | [8aadac9d4b](https://linux-hardware.org/?probe=8aadac9d4b) | Jul 11, 2023 |
| ASUSTek       | SABERTOOTH X99              | [1473d3cd3b](https://linux-hardware.org/?probe=1473d3cd3b) | Jul 10, 2023 |
| ASUSTek       | P8Z77-V                     | [1e5cf5e071](https://linux-hardware.org/?probe=1e5cf5e071) | Jul 10, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [2d5d457159](https://linux-hardware.org/?probe=2d5d457159) | Jul 09, 2023 |
| ASUSTek       | B75M-A                      | [9120c3aa90](https://linux-hardware.org/?probe=9120c3aa90) | Jul 09, 2023 |
| ASUSTek       | B75M-A                      | [b48f49fab3](https://linux-hardware.org/?probe=b48f49fab3) | Jul 09, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | [290c9aca96](https://linux-hardware.org/?probe=290c9aca96) | Jul 09, 2023 |
| ASUSTek       | P5Q PRO TURBO               | [362fd95251](https://linux-hardware.org/?probe=362fd95251) | Jul 08, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [e394b88e49](https://linux-hardware.org/?probe=e394b88e49) | Jul 08, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | [2378ebea87](https://linux-hardware.org/?probe=2378ebea87) | Jul 07, 2023 |
| MSI           | MPG X670E CARBON WIFI       | [b67973ece1](https://linux-hardware.org/?probe=b67973ece1) | Jul 04, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [7aaa5d2eec](https://linux-hardware.org/?probe=7aaa5d2eec) | Jul 03, 2023 |
| ASUSTek       | PRIME A320M-K               | [b66a2be1fe](https://linux-hardware.org/?probe=b66a2be1fe) | Jul 03, 2023 |
| HP            | 8918                        | [da7b695c7b](https://linux-hardware.org/?probe=da7b695c7b) | Jul 02, 2023 |
| ASUSTek       | Crosshair V Formula         | [e0810c9450](https://linux-hardware.org/?probe=e0810c9450) | Jul 02, 2023 |
| Gigabyte      | P55M-UD2                    | [babec703df](https://linux-hardware.org/?probe=babec703df) | Jul 02, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [277a9bb8e4](https://linux-hardware.org/?probe=277a9bb8e4) | Jul 02, 2023 |
| MSI           | H61MA-E35                   | [a5b11bc53c](https://linux-hardware.org/?probe=a5b11bc53c) | Jul 01, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [292b7f6f0f](https://linux-hardware.org/?probe=292b7f6f0f) | Jun 30, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [661dc06ef7](https://linux-hardware.org/?probe=661dc06ef7) | Jun 30, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [265cbaedcc](https://linux-hardware.org/?probe=265cbaedcc) | Jun 30, 2023 |
| HP            | 89B5 A                      | [f0330163de](https://linux-hardware.org/?probe=f0330163de) | Jun 30, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [b94582735c](https://linux-hardware.org/?probe=b94582735c) | Jun 28, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [81bbfe3459](https://linux-hardware.org/?probe=81bbfe3459) | Jun 28, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [ebb41279ae](https://linux-hardware.org/?probe=ebb41279ae) | Jun 28, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [32e4f74711](https://linux-hardware.org/?probe=32e4f74711) | Jun 28, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [6f96789257](https://linux-hardware.org/?probe=6f96789257) | Jun 27, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [f46408c9b6](https://linux-hardware.org/?probe=f46408c9b6) | Jun 27, 2023 |
| ASRock        | Z270 Gaming K6              | [f94b4ddd1b](https://linux-hardware.org/?probe=f94b4ddd1b) | Jun 27, 2023 |
| ASRock        | H370M-ITX/ac                | [5e1d8d04f2](https://linux-hardware.org/?probe=5e1d8d04f2) | Jun 26, 2023 |
| HP            | 1493                        | [b22e0342bc](https://linux-hardware.org/?probe=b22e0342bc) | Jun 25, 2023 |
| Gigabyte      | B450M DS3H-CF               | [14bd8b577f](https://linux-hardware.org/?probe=14bd8b577f) | Jun 25, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [bd418c39bf](https://linux-hardware.org/?probe=bd418c39bf) | Jun 25, 2023 |
| HP            | 8437                        | [477b6d5623](https://linux-hardware.org/?probe=477b6d5623) | Jun 24, 2023 |
| Gigabyte      | B560M AORUS PRO AX          | [090549881a](https://linux-hardware.org/?probe=090549881a) | Jun 24, 2023 |
| ASUSTek       | PRIME B450M-A II            | [85221c654f](https://linux-hardware.org/?probe=85221c654f) | Jun 24, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | [74b9f1b367](https://linux-hardware.org/?probe=74b9f1b367) | Jun 24, 2023 |
| MSI           | Z170A GAMING M3             | [96c2d6503c](https://linux-hardware.org/?probe=96c2d6503c) | Jun 24, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [0e23ab4ba9](https://linux-hardware.org/?probe=0e23ab4ba9) | Jun 24, 2023 |
| ASUSTek       | Z170M-PLUS                  | [a3a840a283](https://linux-hardware.org/?probe=a3a840a283) | Jun 23, 2023 |
| Gigabyte      | B650I AORUS ULTRA           | [e72c8358c4](https://linux-hardware.org/?probe=e72c8358c4) | Jun 22, 2023 |
| ASRock        | B760M PG Riptide            | [08974b3246](https://linux-hardware.org/?probe=08974b3246) | Jun 22, 2023 |
| ASRock        | B760M PG Riptide            | [a6a3ed2eae](https://linux-hardware.org/?probe=a6a3ed2eae) | Jun 21, 2023 |
| ASRock        | B450 Gaming K4              | [edf3326608](https://linux-hardware.org/?probe=edf3326608) | Jun 21, 2023 |
| ASUSTek       | P8P67 PRO                   | [ba4e83abed](https://linux-hardware.org/?probe=ba4e83abed) | Jun 20, 2023 |
| ASRock        | Z590M-ITX/ax                | [5160dd29d0](https://linux-hardware.org/?probe=5160dd29d0) | Jun 20, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [5a51d4431b](https://linux-hardware.org/?probe=5a51d4431b) | Jun 20, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [bfe09e12f0](https://linux-hardware.org/?probe=bfe09e12f0) | Jun 18, 2023 |
| Positivo      | POS-EIQ87CY POSITIVO        | [b4cd8c843f](https://linux-hardware.org/?probe=b4cd8c843f) | Jun 17, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [bcb3a62b53](https://linux-hardware.org/?probe=bcb3a62b53) | Jun 17, 2023 |
| ASRock        | 970M Pro3                   | [777a9e4f49](https://linux-hardware.org/?probe=777a9e4f49) | Jun 17, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | [8124f64b22](https://linux-hardware.org/?probe=8124f64b22) | Jun 16, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [c5491fb02f](https://linux-hardware.org/?probe=c5491fb02f) | Jun 16, 2023 |
| MSI           | X299 GAMING PRO CARBON A... | [6385c09651](https://linux-hardware.org/?probe=6385c09651) | Jun 15, 2023 |
| Fujitsu       | D3162-C1 S26361-D3162-C1    | [31d4ce59c3](https://linux-hardware.org/?probe=31d4ce59c3) | Jun 15, 2023 |
| ASUSTek       | M5A97 R2.0                  | [da6bfc34aa](https://linux-hardware.org/?probe=da6bfc34aa) | Jun 15, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [f6175fd764](https://linux-hardware.org/?probe=f6175fd764) | Jun 14, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [09b0f43143](https://linux-hardware.org/?probe=09b0f43143) | Jun 14, 2023 |
| Foxconn       | 2ADA                        | [4402afe7ad](https://linux-hardware.org/?probe=4402afe7ad) | Jun 14, 2023 |
| Foxconn       | 2ADA                        | [78c4871863](https://linux-hardware.org/?probe=78c4871863) | Jun 14, 2023 |
| ASRock        | B450 Gaming K4              | [9ef5114c59](https://linux-hardware.org/?probe=9ef5114c59) | Jun 14, 2023 |
| Gigabyte      | 970A-D3                     | [1c62ecb77d](https://linux-hardware.org/?probe=1c62ecb77d) | Jun 14, 2023 |
| ASUSTek       | PRIME B560M-K               | [e18c667ddc](https://linux-hardware.org/?probe=e18c667ddc) | Jun 13, 2023 |
| ASUSTek       | M5A97 R2.0                  | [cda9f3da9c](https://linux-hardware.org/?probe=cda9f3da9c) | Jun 13, 2023 |
| ASRock        | X370 Gaming-ITX/ac          | [9347870cd0](https://linux-hardware.org/?probe=9347870cd0) | Jun 13, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [3918c9dc55](https://linux-hardware.org/?probe=3918c9dc55) | Jun 12, 2023 |
| Gigabyte      | X570S I AORUS PRO AX        | [5275807836](https://linux-hardware.org/?probe=5275807836) | Jun 11, 2023 |
| Gigabyte      | A520M H                     | [af18d05812](https://linux-hardware.org/?probe=af18d05812) | Jun 10, 2023 |
| MSI           | X370 GAMING M7 ACK          | [450b8ab5a7](https://linux-hardware.org/?probe=450b8ab5a7) | Jun 10, 2023 |
| Dell          | 0KC9NP A01                  | [ab5b79d6fd](https://linux-hardware.org/?probe=ab5b79d6fd) | Jun 10, 2023 |
| Unknown       | Unknown                     | [4c9c3d929b](https://linux-hardware.org/?probe=4c9c3d929b) | Jun 10, 2023 |
| Gigabyte      | B550 GAMING X V2            | [03ef8fea42](https://linux-hardware.org/?probe=03ef8fea42) | Jun 10, 2023 |
| HP            | 82C9                        | [b696990030](https://linux-hardware.org/?probe=b696990030) | Jun 09, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | [f4f543eaa6](https://linux-hardware.org/?probe=f4f543eaa6) | Jun 09, 2023 |
| HP            | 3397                        | [c754fea198](https://linux-hardware.org/?probe=c754fea198) | Jun 08, 2023 |
| ASRock        | Z270 Gaming K6              | [31a7447d8b](https://linux-hardware.org/?probe=31a7447d8b) | Jun 08, 2023 |
| ASRock        | Z270 Gaming K6              | [267154b0d2](https://linux-hardware.org/?probe=267154b0d2) | Jun 08, 2023 |
| Gigabyte      | A520M H                     | [302bb0628a](https://linux-hardware.org/?probe=302bb0628a) | Jun 08, 2023 |
| HP            | 3397                        | [d86a6fc258](https://linux-hardware.org/?probe=d86a6fc258) | Jun 07, 2023 |
| HP            | 2B36                        | [45ee697eed](https://linux-hardware.org/?probe=45ee697eed) | Jun 07, 2023 |
| HP            | 2B36                        | [0f36ecaa7e](https://linux-hardware.org/?probe=0f36ecaa7e) | Jun 07, 2023 |
| DIEBOLD       | B85H3-M5                    | [7e56b1fd68](https://linux-hardware.org/?probe=7e56b1fd68) | Jun 07, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [ae164f9998](https://linux-hardware.org/?probe=ae164f9998) | Jun 06, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [6ae325ff9d](https://linux-hardware.org/?probe=6ae325ff9d) | Jun 06, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [77e1fa9533](https://linux-hardware.org/?probe=77e1fa9533) | Jun 06, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [c33bc572fd](https://linux-hardware.org/?probe=c33bc572fd) | Jun 06, 2023 |
| ASUSTek       | PRIME H370M-PLUS            | [bbbe24d6b6](https://linux-hardware.org/?probe=bbbe24d6b6) | Jun 06, 2023 |
| HP            | 8918                        | [6f94c9caa9](https://linux-hardware.org/?probe=6f94c9caa9) | Jun 06, 2023 |
| Dell          | 055H3G A01                  | [3fc296df33](https://linux-hardware.org/?probe=3fc296df33) | Jun 05, 2023 |
| MSI           | GF615M-P33                  | [84f237f434](https://linux-hardware.org/?probe=84f237f434) | Jun 04, 2023 |
| HP            | 8643 SMVB                   | [88fbd57dac](https://linux-hardware.org/?probe=88fbd57dac) | Jun 04, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [06752ca793](https://linux-hardware.org/?probe=06752ca793) | Jun 04, 2023 |
| Biostar       | B450MX-S                    | [ccc6b5c4b5](https://linux-hardware.org/?probe=ccc6b5c4b5) | Jun 03, 2023 |
| Biostar       | B450MX-S                    | [6a01df1d69](https://linux-hardware.org/?probe=6a01df1d69) | Jun 03, 2023 |
| HP            | 3397                        | [530b98edd5](https://linux-hardware.org/?probe=530b98edd5) | Jun 03, 2023 |
| HP            | 8918                        | [b03f8a6eb3](https://linux-hardware.org/?probe=b03f8a6eb3) | Jun 02, 2023 |
| Pegatron      | H81-M1                      | [cdb426bfb4](https://linux-hardware.org/?probe=cdb426bfb4) | Jun 02, 2023 |
| Pegatron      | H81-M1                      | [35eb509619](https://linux-hardware.org/?probe=35eb509619) | Jun 02, 2023 |
| ASRock        | B450 Gaming K4              | [24ccc7665f](https://linux-hardware.org/?probe=24ccc7665f) | Jun 01, 2023 |
| ASRock        | B450 Gaming K4              | [af6c8f3355](https://linux-hardware.org/?probe=af6c8f3355) | Jun 01, 2023 |
| MSI           | P55-GD55                    | [1400fdf705](https://linux-hardware.org/?probe=1400fdf705) | May 31, 2023 |
| MSI           | PRO X670-P WIFI             | [10f4ef3e86](https://linux-hardware.org/?probe=10f4ef3e86) | May 31, 2023 |
| MSI           | PRO Z790-A WIFI             | [676d83919f](https://linux-hardware.org/?probe=676d83919f) | May 30, 2023 |
| HP            | 0B54h D                     | [c7813156eb](https://linux-hardware.org/?probe=c7813156eb) | May 30, 2023 |
| HP            | 2B36                        | [8e4fc0d41f](https://linux-hardware.org/?probe=8e4fc0d41f) | May 29, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | [e29eb3dfcc](https://linux-hardware.org/?probe=e29eb3dfcc) | May 29, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | [40ba623a3e](https://linux-hardware.org/?probe=40ba623a3e) | May 28, 2023 |
| MSI           | A520M-A PRO                 | [c78b5e28f1](https://linux-hardware.org/?probe=c78b5e28f1) | May 28, 2023 |
| ASUSTek       | ROG STRIX X399-E GAMING     | [4f1ff269d2](https://linux-hardware.org/?probe=4f1ff269d2) | May 28, 2023 |
| ASUSTek       | PRIME H510M-A               | [4945ea3fba](https://linux-hardware.org/?probe=4945ea3fba) | May 26, 2023 |
| Intel         | DN2820FYK H24582-204        | [1987af2458](https://linux-hardware.org/?probe=1987af2458) | May 25, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [5c4649a83e](https://linux-hardware.org/?probe=5c4649a83e) | May 24, 2023 |
| Unknown       | Unknown                     | [957b9f9de8](https://linux-hardware.org/?probe=957b9f9de8) | May 23, 2023 |
| HP            | 8876 11                     | [889144e990](https://linux-hardware.org/?probe=889144e990) | May 23, 2023 |
| AMI           | Intel                       | [9ddb291be3](https://linux-hardware.org/?probe=9ddb291be3) | May 22, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [781e226978](https://linux-hardware.org/?probe=781e226978) | May 22, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [68caefd4e9](https://linux-hardware.org/?probe=68caefd4e9) | May 22, 2023 |
| Lenovo        | 3753 NOK                    | [f2971c14a7](https://linux-hardware.org/?probe=f2971c14a7) | May 21, 2023 |
| AMI           | Intel                       | [13f87e64f1](https://linux-hardware.org/?probe=13f87e64f1) | May 21, 2023 |
| Positivo      | POS-EIQ87CY POSITIVO        | [2a95b22ac3](https://linux-hardware.org/?probe=2a95b22ac3) | May 21, 2023 |
| Unknown       | HX90                        | [d640a32296](https://linux-hardware.org/?probe=d640a32296) | May 21, 2023 |
| Lenovo        | 3714 NOK                    | [0da1ff78c6](https://linux-hardware.org/?probe=0da1ff78c6) | May 20, 2023 |
| MSI           | X370 GAMING M7 ACK          | [c59f2a4b1e](https://linux-hardware.org/?probe=c59f2a4b1e) | May 19, 2023 |
| MSI           | GF615M-P33                  | [09ae9aca26](https://linux-hardware.org/?probe=09ae9aca26) | May 19, 2023 |
| ASRock        | 890FX Deluxe4               | [c00eb20149](https://linux-hardware.org/?probe=c00eb20149) | May 18, 2023 |
| Gigabyte      | A520M H                     | [a776d86dad](https://linux-hardware.org/?probe=a776d86dad) | May 17, 2023 |
| Gigabyte      | X99-Gaming 5                | [81eee33114](https://linux-hardware.org/?probe=81eee33114) | May 17, 2023 |
| Dell          | 0W0CHX A00                  | [a74974308d](https://linux-hardware.org/?probe=a74974308d) | May 16, 2023 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [9dd2c4cbee](https://linux-hardware.org/?probe=9dd2c4cbee) | May 16, 2023 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [dfc49eb820](https://linux-hardware.org/?probe=dfc49eb820) | May 16, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [a4cbf66286](https://linux-hardware.org/?probe=a4cbf66286) | May 16, 2023 |
| MSI           | B450 TOMAHAWK               | [a1d85d1caf](https://linux-hardware.org/?probe=a1d85d1caf) | May 16, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [aeb8c0e04f](https://linux-hardware.org/?probe=aeb8c0e04f) | May 16, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | [9ed74f5d63](https://linux-hardware.org/?probe=9ed74f5d63) | May 15, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | [b4ffbbf7d3](https://linux-hardware.org/?probe=b4ffbbf7d3) | May 15, 2023 |
| MSI           | 760GM-P23                   | [970443eea3](https://linux-hardware.org/?probe=970443eea3) | May 14, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [beb403e4e0](https://linux-hardware.org/?probe=beb403e4e0) | May 14, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | [65374a707a](https://linux-hardware.org/?probe=65374a707a) | May 14, 2023 |
| Intel         | X79F1 V2.0                  | [a2446b63b3](https://linux-hardware.org/?probe=a2446b63b3) | May 14, 2023 |
| Intel         | H61 V1.1                    | [f5cbf650c3](https://linux-hardware.org/?probe=f5cbf650c3) | May 14, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [58c658819c](https://linux-hardware.org/?probe=58c658819c) | May 13, 2023 |
| MSI           | MAG B550M BAZOOKA           | [ef9c6905f1](https://linux-hardware.org/?probe=ef9c6905f1) | May 13, 2023 |
| ASRock        | H370M-ITX/ac                | [7f4f38aeb1](https://linux-hardware.org/?probe=7f4f38aeb1) | May 13, 2023 |
| HP            | 3047h                       | [bb0087d307](https://linux-hardware.org/?probe=bb0087d307) | May 12, 2023 |
| ASUSTek       | F1A75-M PRO/CSM             | [f9a67e4a1f](https://linux-hardware.org/?probe=f9a67e4a1f) | May 11, 2023 |
| Gigabyte      | B550 GAMING X V2            | [4d4946eec9](https://linux-hardware.org/?probe=4d4946eec9) | May 11, 2023 |
| ASUSTek       | F1A75-M PRO/CSM             | [18a4110763](https://linux-hardware.org/?probe=18a4110763) | May 11, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [ec8e4b5f19](https://linux-hardware.org/?probe=ec8e4b5f19) | May 11, 2023 |
| Lenovo        | ThinkCentre M71z 1761E4U    | [a865f3d92e](https://linux-hardware.org/?probe=a865f3d92e) | May 11, 2023 |
| Gigabyte      | 970A-DS3P                   | [1e4f2a0daf](https://linux-hardware.org/?probe=1e4f2a0daf) | May 10, 2023 |
| Gigabyte      | Z97X-SLI-CF                 | [5921d78ceb](https://linux-hardware.org/?probe=5921d78ceb) | May 10, 2023 |
| Gigabyte      | Z590 UD AC                  | [532e5b78de](https://linux-hardware.org/?probe=532e5b78de) | May 09, 2023 |
| MSI           | B85-G43                     | [878fbbb243](https://linux-hardware.org/?probe=878fbbb243) | May 09, 2023 |
| Gigabyte      | AX370-Gaming 5              | [462a9b182b](https://linux-hardware.org/?probe=462a9b182b) | May 09, 2023 |
| ASRock        | N68-S3 UCC                  | [8a1fbe8e3c](https://linux-hardware.org/?probe=8a1fbe8e3c) | May 09, 2023 |
| Gateway       | RS780                       | [e04207a390](https://linux-hardware.org/?probe=e04207a390) | May 07, 2023 |
| Gigabyte      | B450 AORUS M                | [87e972803c](https://linux-hardware.org/?probe=87e972803c) | May 07, 2023 |
| Intel         | H61                         | [c359f42a22](https://linux-hardware.org/?probe=c359f42a22) | May 07, 2023 |
| ASRock        | X670E Steel Legend          | [0c0ad48cc6](https://linux-hardware.org/?probe=0c0ad48cc6) | May 07, 2023 |
| Positivo      | POS-EIQ87CY POSITIVO        | [812ae9a763](https://linux-hardware.org/?probe=812ae9a763) | May 06, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [4d21a72bfb](https://linux-hardware.org/?probe=4d21a72bfb) | May 05, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [ffab85a31a](https://linux-hardware.org/?probe=ffab85a31a) | May 05, 2023 |
| Gigabyte      | X99-Gaming 5                | [e1d1bdef81](https://linux-hardware.org/?probe=e1d1bdef81) | May 04, 2023 |
| ASUSTek       | ProArt B550-CREATOR         | [5989cc1ac0](https://linux-hardware.org/?probe=5989cc1ac0) | May 03, 2023 |
| ASUSTek       | ProArt B550-CREATOR         | [9258699383](https://linux-hardware.org/?probe=9258699383) | May 03, 2023 |
| ASRock        | A320M-HDV R4.0              | [1909560f36](https://linux-hardware.org/?probe=1909560f36) | May 02, 2023 |
| ASUSTek       | ROG STRIX X299-E GAMING     | [553a101cf8](https://linux-hardware.org/?probe=553a101cf8) | May 02, 2023 |
| ASRock        | A320M-HDV R4.0              | [17097573de](https://linux-hardware.org/?probe=17097573de) | May 02, 2023 |
| Dell          | 073MMW A02                  | [09a404ced5](https://linux-hardware.org/?probe=09a404ced5) | May 02, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [7ffccfda78](https://linux-hardware.org/?probe=7ffccfda78) | May 01, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [cf6a478eb1](https://linux-hardware.org/?probe=cf6a478eb1) | May 01, 2023 |
| ASRock        | B650 LiveMixer              | [aecb4b61b4](https://linux-hardware.org/?probe=aecb4b61b4) | May 01, 2023 |
| Shuttle       | DL20N                       | [3f97bcaa08](https://linux-hardware.org/?probe=3f97bcaa08) | Apr 30, 2023 |
| Positivo      | POS-EIQ87CY POSITIVO        | [2e2b57b3ae](https://linux-hardware.org/?probe=2e2b57b3ae) | Apr 30, 2023 |
| Gigabyte      | X399 DESIGNARE EX-CF        | [e47ae2080c](https://linux-hardware.org/?probe=e47ae2080c) | Apr 29, 2023 |
| MSI           | B450M MORTAR MAX            | [3586d79ce4](https://linux-hardware.org/?probe=3586d79ce4) | Apr 29, 2023 |
| HP            | 845A                        | [d0aa2a4a7a](https://linux-hardware.org/?probe=d0aa2a4a7a) | Apr 29, 2023 |
| HP            | 845A                        | [f8bc4601ef](https://linux-hardware.org/?probe=f8bc4601ef) | Apr 29, 2023 |
| Pegatron      | Benicia                     | [930452646c](https://linux-hardware.org/?probe=930452646c) | Apr 28, 2023 |
| ASUSTek       | ROG STRIX Z370-I GAMING     | [e8886a7521](https://linux-hardware.org/?probe=e8886a7521) | Apr 28, 2023 |
| Apple         | Mac-F221BEC8                | [3342a295e8](https://linux-hardware.org/?probe=3342a295e8) | Apr 28, 2023 |
| Dell          | 0200DY A02                  | [2499c633a5](https://linux-hardware.org/?probe=2499c633a5) | Apr 27, 2023 |
| Gigabyte      | H61MA-D3V                   | [3a1d89d5a0](https://linux-hardware.org/?probe=3a1d89d5a0) | Apr 27, 2023 |
| ASUSTek       | ROG STRIX B760-I GAMING ... | [6dec479f55](https://linux-hardware.org/?probe=6dec479f55) | Apr 25, 2023 |
| ASUSTek       | Z170I PRO GAMING            | [a2875a31b2](https://linux-hardware.org/?probe=a2875a31b2) | Apr 25, 2023 |
| Biostar       | B450MX-S                    | [5ac7debff3](https://linux-hardware.org/?probe=5ac7debff3) | Apr 25, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [25ac3a297e](https://linux-hardware.org/?probe=25ac3a297e) | Apr 24, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | [0e85243397](https://linux-hardware.org/?probe=0e85243397) | Apr 23, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [e5c6fc2738](https://linux-hardware.org/?probe=e5c6fc2738) | Apr 23, 2023 |
| HUAWEI        | PUM-WDX9-PCB-B1 M1060       | [2c8835f2e2](https://linux-hardware.org/?probe=2c8835f2e2) | Apr 22, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [519c11a569](https://linux-hardware.org/?probe=519c11a569) | Apr 21, 2023 |
| MSI           | B450-A PRO MAX              | [51ef82c2fd](https://linux-hardware.org/?probe=51ef82c2fd) | Apr 21, 2023 |
| Dell          | 0WN7Y6 A01                  | [cc1233b9b9](https://linux-hardware.org/?probe=cc1233b9b9) | Apr 21, 2023 |
| Lenovo        | 102F SDK0J40705 WIN 3425... | [15cc4335c7](https://linux-hardware.org/?probe=15cc4335c7) | Apr 21, 2023 |
| Gigabyte      | A320M-H-CF                  | [b0b94f2462](https://linux-hardware.org/?probe=b0b94f2462) | Apr 21, 2023 |
| Gigabyte      | A320M-H-CF                  | [d429a2c865](https://linux-hardware.org/?probe=d429a2c865) | Apr 21, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [5a9a6c553f](https://linux-hardware.org/?probe=5a9a6c553f) | Apr 20, 2023 |
| ASRock        | FM2A68M-DG3+                | [f8519c5a20](https://linux-hardware.org/?probe=f8519c5a20) | Apr 20, 2023 |
| Gigabyte      | B550 GAMING X               | [a815ec2fa2](https://linux-hardware.org/?probe=a815ec2fa2) | Apr 19, 2023 |
| ASRock        | FM2A68M-DG3+                | [701110cf4e](https://linux-hardware.org/?probe=701110cf4e) | Apr 19, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [023e96a6fd](https://linux-hardware.org/?probe=023e96a6fd) | Apr 18, 2023 |
| Dell          | 0200DY A02                  | [6041b126fa](https://linux-hardware.org/?probe=6041b126fa) | Apr 18, 2023 |
| ASRock        | 970 Pro3 R2.0               | [e816e4de38](https://linux-hardware.org/?probe=e816e4de38) | Apr 18, 2023 |
| ASRock        | Z790 Taichi                 | [0d25cf28bc](https://linux-hardware.org/?probe=0d25cf28bc) | Apr 17, 2023 |
| MSI           | MS-B0A41                    | [5950f6e73c](https://linux-hardware.org/?probe=5950f6e73c) | Apr 17, 2023 |
| ASUSTek       | X99-PRO/USB                 | [058029e9f7](https://linux-hardware.org/?probe=058029e9f7) | Apr 17, 2023 |
| Dell          | 0P01GV A03                  | [ed2675881e](https://linux-hardware.org/?probe=ed2675881e) | Apr 17, 2023 |
| ASUSTek       | Z170I PRO GAMING            | [286c8ef93c](https://linux-hardware.org/?probe=286c8ef93c) | Apr 16, 2023 |
| HP            | 158A                        | [56694ce9a3](https://linux-hardware.org/?probe=56694ce9a3) | Apr 16, 2023 |
| ASUSTek       | PRIME Z490-A                | [3924bb4eb5](https://linux-hardware.org/?probe=3924bb4eb5) | Apr 16, 2023 |
| ASUSTek       | PRIME A320M-K               | [2eb96e4d6e](https://linux-hardware.org/?probe=2eb96e4d6e) | Apr 16, 2023 |
| ASUSTek       | PRIME A320M-K               | [7d34909c86](https://linux-hardware.org/?probe=7d34909c86) | Apr 16, 2023 |
| HP            | 802E                        | [d6a1c8ad74](https://linux-hardware.org/?probe=d6a1c8ad74) | Apr 15, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [3a6ad12afa](https://linux-hardware.org/?probe=3a6ad12afa) | Apr 15, 2023 |
| ASUSTek       | GR6                         | [9cccf46449](https://linux-hardware.org/?probe=9cccf46449) | Apr 15, 2023 |
| MSI           | Z97 GAMING 5                | [988cd72346](https://linux-hardware.org/?probe=988cd72346) | Apr 15, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [8aa8fd23c6](https://linux-hardware.org/?probe=8aa8fd23c6) | Apr 15, 2023 |
| MSI           | X399 GAMING PRO CARBON A... | [c99626b458](https://linux-hardware.org/?probe=c99626b458) | Apr 14, 2023 |
| MSI           | B85-G43                     | [0363360efa](https://linux-hardware.org/?probe=0363360efa) | Apr 14, 2023 |
| Gigabyte      | F2A68HM-S1                  | [b5ce8ee6ec](https://linux-hardware.org/?probe=b5ce8ee6ec) | Apr 13, 2023 |
| ASUSTek       | PRIME A320M-K               | [bbc081e43e](https://linux-hardware.org/?probe=bbc081e43e) | Apr 13, 2023 |
| ASUSTek       | PRIME A320M-K               | [a59a28162e](https://linux-hardware.org/?probe=a59a28162e) | Apr 13, 2023 |
| Intel         | H61 V1.1                    | [1b97e4ffc5](https://linux-hardware.org/?probe=1b97e4ffc5) | Apr 12, 2023 |
| Intel         | H61 V1.1                    | [402a94b1c0](https://linux-hardware.org/?probe=402a94b1c0) | Apr 12, 2023 |
| Gigabyte      | X570S UD                    | [2d599510b8](https://linux-hardware.org/?probe=2d599510b8) | Apr 12, 2023 |
| Daten Tecn... | DH110MXV                    | [6a1c34f539](https://linux-hardware.org/?probe=6a1c34f539) | Apr 12, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [1429799ca6](https://linux-hardware.org/?probe=1429799ca6) | Apr 11, 2023 |
| HP            | 1495                        | [762886dcb0](https://linux-hardware.org/?probe=762886dcb0) | Apr 11, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [8b8b7e1e4e](https://linux-hardware.org/?probe=8b8b7e1e4e) | Apr 11, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [192ca29359](https://linux-hardware.org/?probe=192ca29359) | Apr 11, 2023 |
| Dell          | 0K240Y A01                  | [1daf1b0ff6](https://linux-hardware.org/?probe=1daf1b0ff6) | Apr 10, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [1dad85ccf1](https://linux-hardware.org/?probe=1dad85ccf1) | Apr 10, 2023 |
| Intel         | H61 V1.1                    | [1c3cfd94a3](https://linux-hardware.org/?probe=1c3cfd94a3) | Apr 09, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [6aae769b7a](https://linux-hardware.org/?probe=6aae769b7a) | Apr 09, 2023 |
| Intel         | H61 V1.1                    | [e553db41a3](https://linux-hardware.org/?probe=e553db41a3) | Apr 08, 2023 |
| Huanan        | X99-F8                      | [4b020d6c5a](https://linux-hardware.org/?probe=4b020d6c5a) | Apr 08, 2023 |
| Gigabyte      | B450M DS3H-CF               | [15c7f69a52](https://linux-hardware.org/?probe=15c7f69a52) | Apr 07, 2023 |
| ASUSTek       | Z170M-PLUS                  | [be741560b8](https://linux-hardware.org/?probe=be741560b8) | Apr 06, 2023 |
| HP            | 21D0                        | [be69723341](https://linux-hardware.org/?probe=be69723341) | Apr 06, 2023 |
| ASUSTek       | PRIME Z490M-PLUS            | [1190aa9be8](https://linux-hardware.org/?probe=1190aa9be8) | Apr 06, 2023 |
| HP            | 84FD                        | [7e80c3baf0](https://linux-hardware.org/?probe=7e80c3baf0) | Apr 05, 2023 |
| Gigabyte      | H61MA-D3V                   | [ba4ee67415](https://linux-hardware.org/?probe=ba4ee67415) | Apr 05, 2023 |
| ASUSTek       | X99-A II                    | [882dc981fb](https://linux-hardware.org/?probe=882dc981fb) | Apr 04, 2023 |
| Foxconn       | 2ADA                        | [0d1d784767](https://linux-hardware.org/?probe=0d1d784767) | Apr 04, 2023 |
| Dell          | 042P49 A02                  | [74a232499a](https://linux-hardware.org/?probe=74a232499a) | Apr 04, 2023 |
| MSI           | H81M-E34                    | [5e24c6a44a](https://linux-hardware.org/?probe=5e24c6a44a) | Apr 03, 2023 |
| MSI           | B450-A PRO                  | [c487bcedab](https://linux-hardware.org/?probe=c487bcedab) | Apr 03, 2023 |
| ASRock        | B550M Pro4                  | [161e53a104](https://linux-hardware.org/?probe=161e53a104) | Apr 03, 2023 |
| MSI           | GF615M-P33                  | [022324033e](https://linux-hardware.org/?probe=022324033e) | Apr 02, 2023 |
| ASRock        | B550M Pro4                  | [9ccae5a498](https://linux-hardware.org/?probe=9ccae5a498) | Apr 02, 2023 |
| ASUSTek       | M5A97 R2.0                  | [fe4d7e3bd0](https://linux-hardware.org/?probe=fe4d7e3bd0) | Apr 02, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [bb490db4a9](https://linux-hardware.org/?probe=bb490db4a9) | Apr 02, 2023 |
| ASRock        | B550 Taichi                 | [cff286981b](https://linux-hardware.org/?probe=cff286981b) | Apr 01, 2023 |
| ASRock        | B550 Taichi                 | [01517a396d](https://linux-hardware.org/?probe=01517a396d) | Apr 01, 2023 |
| HP            | 1495                        | [96ea87fbce](https://linux-hardware.org/?probe=96ea87fbce) | Apr 01, 2023 |
| MSI           | X570-A PRO                  | [3093c50d3d](https://linux-hardware.org/?probe=3093c50d3d) | Mar 31, 2023 |
| Intel         | H61 V1.1                    | [e670f092d7](https://linux-hardware.org/?probe=e670f092d7) | Mar 31, 2023 |
| ASRock        | H61M-HVS                    | [0672578da7](https://linux-hardware.org/?probe=0672578da7) | Mar 30, 2023 |
| Intel         | X99 V1.0                    | [13c66b0e69](https://linux-hardware.org/?probe=13c66b0e69) | Mar 30, 2023 |
| MSI           | H81M-E34                    | [ac06c6037f](https://linux-hardware.org/?probe=ac06c6037f) | Mar 30, 2023 |
| MSI           | X570-A PRO                  | [0921fd9096](https://linux-hardware.org/?probe=0921fd9096) | Mar 28, 2023 |
| ASRock        | B550 Taichi                 | [94d97c5e0c](https://linux-hardware.org/?probe=94d97c5e0c) | Mar 28, 2023 |
| Intel         | H61 V1.1                    | [497266ad29](https://linux-hardware.org/?probe=497266ad29) | Mar 28, 2023 |
| ASRock        | FM2A55M-HD+ R2.0            | [a45bc637c9](https://linux-hardware.org/?probe=a45bc637c9) | Mar 27, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [aaae412a63](https://linux-hardware.org/?probe=aaae412a63) | Mar 26, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | [9e318501f5](https://linux-hardware.org/?probe=9e318501f5) | Mar 25, 2023 |
| Lenovo        | 30D2 NOK                    | [dc62baadff](https://linux-hardware.org/?probe=dc62baadff) | Mar 25, 2023 |
| MSI           | GF615M-P33                  | [51276a5f00](https://linux-hardware.org/?probe=51276a5f00) | Mar 25, 2023 |
| Intel         | H61 V1.1                    | [e678dd580c](https://linux-hardware.org/?probe=e678dd580c) | Mar 25, 2023 |
| Dell          | 08NPPY A00                  | [38079fceb0](https://linux-hardware.org/?probe=38079fceb0) | Mar 24, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [4731c6e59f](https://linux-hardware.org/?probe=4731c6e59f) | Mar 23, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [127173d60b](https://linux-hardware.org/?probe=127173d60b) | Mar 23, 2023 |
| Intel         | H61 V1.1                    | [f1292785cd](https://linux-hardware.org/?probe=f1292785cd) | Mar 23, 2023 |
| Dell          | 0X9M3X A01                  | [38f83864e4](https://linux-hardware.org/?probe=38f83864e4) | Mar 22, 2023 |
| OEM           | H110 Ver:2.21               | [4b80817d4b](https://linux-hardware.org/?probe=4b80817d4b) | Mar 22, 2023 |
| OEM           | H110 Ver:2.21               | [9c01b0ee80](https://linux-hardware.org/?probe=9c01b0ee80) | Mar 22, 2023 |
| Lenovo        | Dory CRB                    | [821914dc88](https://linux-hardware.org/?probe=821914dc88) | Mar 22, 2023 |
| ASUSTek       | Z170M-PLUS                  | [a1e76aa5c1](https://linux-hardware.org/?probe=a1e76aa5c1) | Mar 21, 2023 |
| MSI           | PRO B660M-A WIFI            | [2184cf01f3](https://linux-hardware.org/?probe=2184cf01f3) | Mar 21, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [cd12accab0](https://linux-hardware.org/?probe=cd12accab0) | Mar 21, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [5eee23b1db](https://linux-hardware.org/?probe=5eee23b1db) | Mar 20, 2023 |
| ASUSTek       | PRIME Z370-P II             | [3b81f87409](https://linux-hardware.org/?probe=3b81f87409) | Mar 20, 2023 |
| ASRock        | X570 Taichi                 | [a6fa212cf2](https://linux-hardware.org/?probe=a6fa212cf2) | Mar 19, 2023 |
| ASRock        | B360M Pro4                  | [e5be65dd5e](https://linux-hardware.org/?probe=e5be65dd5e) | Mar 19, 2023 |
| HP            | 8056                        | [fa7f589aea](https://linux-hardware.org/?probe=fa7f589aea) | Mar 19, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [add9634ad5](https://linux-hardware.org/?probe=add9634ad5) | Mar 19, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [e2cfab15ef](https://linux-hardware.org/?probe=e2cfab15ef) | Mar 19, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [75dd9244fb](https://linux-hardware.org/?probe=75dd9244fb) | Mar 18, 2023 |
| Gigabyte      | GA-970A-DS3                 | [8a94a38026](https://linux-hardware.org/?probe=8a94a38026) | Mar 18, 2023 |
| Gigabyte      | GA-970A-DS3                 | [31851c4e15](https://linux-hardware.org/?probe=31851c4e15) | Mar 18, 2023 |
| HP            | 1495                        | [d83e879ba0](https://linux-hardware.org/?probe=d83e879ba0) | Mar 18, 2023 |
| HP            | 1495                        | [b7b5d46ce0](https://linux-hardware.org/?probe=b7b5d46ce0) | Mar 18, 2023 |
| Dell          | 0GY6Y8 A01                  | [3b10072541](https://linux-hardware.org/?probe=3b10072541) | Mar 18, 2023 |
| HP            | 2B36                        | [85c11ec746](https://linux-hardware.org/?probe=85c11ec746) | Mar 17, 2023 |
| ASUSTek       | PRIME B450M-A               | [fbf7dd9d94](https://linux-hardware.org/?probe=fbf7dd9d94) | Mar 17, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [e41f82bcfd](https://linux-hardware.org/?probe=e41f82bcfd) | Mar 16, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [d6def0b0aa](https://linux-hardware.org/?probe=d6def0b0aa) | Mar 16, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [abe67692b9](https://linux-hardware.org/?probe=abe67692b9) | Mar 16, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [1a4e62a4a5](https://linux-hardware.org/?probe=1a4e62a4a5) | Mar 16, 2023 |
| Dell          | 0WR7PY A01                  | [b34a55307e](https://linux-hardware.org/?probe=b34a55307e) | Mar 16, 2023 |
| Intel         | H61 V1.1                    | [175eb36378](https://linux-hardware.org/?probe=175eb36378) | Mar 16, 2023 |
| Dell          | 0WR7PY A01                  | [73a4a38e57](https://linux-hardware.org/?probe=73a4a38e57) | Mar 15, 2023 |
| Intel         | H61 V1.1                    | [eaa24cb538](https://linux-hardware.org/?probe=eaa24cb538) | Mar 15, 2023 |
| MSI           | X570-A PRO                  | [c4be4f7d67](https://linux-hardware.org/?probe=c4be4f7d67) | Mar 14, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [39ded01df5](https://linux-hardware.org/?probe=39ded01df5) | Mar 14, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [529e83761c](https://linux-hardware.org/?probe=529e83761c) | Mar 14, 2023 |
| ASRock        | Z270 Gaming K6              | [3afad06d79](https://linux-hardware.org/?probe=3afad06d79) | Mar 14, 2023 |
| Gigabyte      | P55M-UD2                    | [74cdc2f679](https://linux-hardware.org/?probe=74cdc2f679) | Mar 14, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [e1fc53bd25](https://linux-hardware.org/?probe=e1fc53bd25) | Mar 13, 2023 |
| ASUSTek       | B85M-G                      | [22ae0716b2](https://linux-hardware.org/?probe=22ae0716b2) | Mar 13, 2023 |
| Biostar       | A960D+V3                    | [e18f6a3a84](https://linux-hardware.org/?probe=e18f6a3a84) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [abb73d2e5f](https://linux-hardware.org/?probe=abb73d2e5f) | Mar 13, 2023 |
| ASUSTek       | P5Q PRO TURBO               | [44fc80c7d5](https://linux-hardware.org/?probe=44fc80c7d5) | Mar 13, 2023 |
| Huanan        | X99-F8                      | [2bd21ce3b3](https://linux-hardware.org/?probe=2bd21ce3b3) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [8f1fe0703b](https://linux-hardware.org/?probe=8f1fe0703b) | Mar 12, 2023 |
| ASUSTek       | PRIME B450M-K               | [d5a4dbf55c](https://linux-hardware.org/?probe=d5a4dbf55c) | Mar 12, 2023 |
| EVGA          | X570 FTW WIFI.0             | [ebb7252eb5](https://linux-hardware.org/?probe=ebb7252eb5) | Mar 12, 2023 |
| EVGA          | X570 FTW WIFI.0             | [74001bfcc3](https://linux-hardware.org/?probe=74001bfcc3) | Mar 12, 2023 |
| ASUSTek       | X99-PRO/USB                 | [f4d8b766a9](https://linux-hardware.org/?probe=f4d8b766a9) | Mar 12, 2023 |
| HP            | 212B                        | [0d3860ffc6](https://linux-hardware.org/?probe=0d3860ffc6) | Mar 11, 2023 |
| MSI           | X99A SLI PLUS               | [77566542fd](https://linux-hardware.org/?probe=77566542fd) | Mar 11, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [e7682656f1](https://linux-hardware.org/?probe=e7682656f1) | Mar 11, 2023 |
| Gigabyte      | Z370 HD3-CF                 | [b53c65e6c9](https://linux-hardware.org/?probe=b53c65e6c9) | Mar 10, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [29a2c22865](https://linux-hardware.org/?probe=29a2c22865) | Mar 09, 2023 |
| Gigabyte      | B550M DS3H                  | [dba3d6498b](https://linux-hardware.org/?probe=dba3d6498b) | Mar 09, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [add9ea7c34](https://linux-hardware.org/?probe=add9ea7c34) | Mar 09, 2023 |
| MSI           | B75MA-P45                   | [f066452d7d](https://linux-hardware.org/?probe=f066452d7d) | Mar 08, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | [4cc3cc4c17](https://linux-hardware.org/?probe=4cc3cc4c17) | Mar 08, 2023 |
| Dell          | 0TTDMJ A00                  | [3d321d8069](https://linux-hardware.org/?probe=3d321d8069) | Mar 07, 2023 |
| ASRock        | H97 Pro4                    | [9ef8ff0b68](https://linux-hardware.org/?probe=9ef8ff0b68) | Mar 06, 2023 |
| ASUSTek       | PRIME A520M-E               | [be51d02a20](https://linux-hardware.org/?probe=be51d02a20) | Mar 06, 2023 |
| ASRock        | AB350 Gaming K4             | [896ea5798f](https://linux-hardware.org/?probe=896ea5798f) | Mar 06, 2023 |
| HP            | 8597                        | [17c1e6efd7](https://linux-hardware.org/?probe=17c1e6efd7) | Mar 05, 2023 |
| MSI           | B450-A PRO MAX              | [ec707b621c](https://linux-hardware.org/?probe=ec707b621c) | Mar 05, 2023 |
| MSI           | B450-A PRO MAX              | [36699f94c9](https://linux-hardware.org/?probe=36699f94c9) | Mar 05, 2023 |
| ASUSTek       | PRIME Z390-A                | [859a660d90](https://linux-hardware.org/?probe=859a660d90) | Mar 05, 2023 |
| ASUSTek       | PRIME X470-PRO              | [cb13decef3](https://linux-hardware.org/?probe=cb13decef3) | Mar 05, 2023 |
| ASUSTek       | PRIME Z390-P                | [ab48c17484](https://linux-hardware.org/?probe=ab48c17484) | Mar 04, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [ce8df757cc](https://linux-hardware.org/?probe=ce8df757cc) | Mar 04, 2023 |
| Biostar       | B450MX-S                    | [7dfed91b1f](https://linux-hardware.org/?probe=7dfed91b1f) | Mar 03, 2023 |
| HP            | 212B                        | [45dec8a39c](https://linux-hardware.org/?probe=45dec8a39c) | Mar 03, 2023 |
| Gigabyte      | B550M DS3H                  | [150a75757b](https://linux-hardware.org/?probe=150a75757b) | Mar 02, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [8bc604606b](https://linux-hardware.org/?probe=8bc604606b) | Mar 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [d209549d77](https://linux-hardware.org/?probe=d209549d77) | Mar 02, 2023 |
| ASUSTek       | PRO A320M-R WI-FI           | [2b64b38f7a](https://linux-hardware.org/?probe=2b64b38f7a) | Mar 01, 2023 |
| Dell          | 08NPPY A00                  | [66b1256bd3](https://linux-hardware.org/?probe=66b1256bd3) | Feb 27, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [4630f9a67c](https://linux-hardware.org/?probe=4630f9a67c) | Feb 27, 2023 |
| Gigabyte      | B450M S2H                   | [4f55a08266](https://linux-hardware.org/?probe=4f55a08266) | Feb 27, 2023 |
| Kllisre       | X79 V2.72S                  | [eb7e4b521c](https://linux-hardware.org/?probe=eb7e4b521c) | Feb 26, 2023 |
| ASRock        | B450M Steel Legend          | [f80e5503fc](https://linux-hardware.org/?probe=f80e5503fc) | Feb 25, 2023 |
| MSI           | B450M PRO-M2                | [e63cbac447](https://linux-hardware.org/?probe=e63cbac447) | Feb 25, 2023 |
| MSI           | B450M PRO-M2                | [4af0524a44](https://linux-hardware.org/?probe=4af0524a44) | Feb 25, 2023 |
| Gigabyte      | Z77M-D3H-MVP                | [e27e1cd0e8](https://linux-hardware.org/?probe=e27e1cd0e8) | Feb 24, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [fea6031cfe](https://linux-hardware.org/?probe=fea6031cfe) | Feb 24, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [4cf00365ff](https://linux-hardware.org/?probe=4cf00365ff) | Feb 24, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [79aa51c612](https://linux-hardware.org/?probe=79aa51c612) | Feb 23, 2023 |
| ASRock        | H370M-ITX/ac                | [300d88af87](https://linux-hardware.org/?probe=300d88af87) | Feb 23, 2023 |
| Positivo      | POS-EIH61CE POSITIVO        | [f3bb3aa940](https://linux-hardware.org/?probe=f3bb3aa940) | Feb 23, 2023 |
| Positivo      | POS-EIH61CE POSITIVO        | [7d1b0e3db5](https://linux-hardware.org/?probe=7d1b0e3db5) | Feb 23, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [af2a414265](https://linux-hardware.org/?probe=af2a414265) | Feb 23, 2023 |
| Dell          | 0200DY A02                  | [a39eba7e6a](https://linux-hardware.org/?probe=a39eba7e6a) | Feb 22, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [64b7226700](https://linux-hardware.org/?probe=64b7226700) | Feb 21, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [c61a513a81](https://linux-hardware.org/?probe=c61a513a81) | Feb 20, 2023 |
| ASUSTek       | H81M-K                      | [cb6168e276](https://linux-hardware.org/?probe=cb6168e276) | Feb 20, 2023 |
| ASUSTek       | X99-M WS                    | [69eb540783](https://linux-hardware.org/?probe=69eb540783) | Feb 20, 2023 |
| ASRock        | X570 Taichi Razer Editio... | [3f44c52c3e](https://linux-hardware.org/?probe=3f44c52c3e) | Feb 20, 2023 |
| ASUSTek       | PRIME X370-PRO              | [35d0544ea5](https://linux-hardware.org/?probe=35d0544ea5) | Feb 19, 2023 |
| ASUSTek       | BT6130                      | [470ceee356](https://linux-hardware.org/?probe=470ceee356) | Feb 19, 2023 |
| ASUSTek       | PRIME X370-PRO              | [703cc27199](https://linux-hardware.org/?probe=703cc27199) | Feb 19, 2023 |
| MSI           | B85M-P33 V2                 | [b78aee1c5a](https://linux-hardware.org/?probe=b78aee1c5a) | Feb 19, 2023 |
| ASUSTek       | X99-PRO/USB                 | [45631ae666](https://linux-hardware.org/?probe=45631ae666) | Feb 18, 2023 |
| Dell          | 0X9M3X A04                  | [9b13a670c5](https://linux-hardware.org/?probe=9b13a670c5) | Feb 18, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [ab3e07326a](https://linux-hardware.org/?probe=ab3e07326a) | Feb 18, 2023 |
| ASRock        | B450 Pro4                   | [d6b212b427](https://linux-hardware.org/?probe=d6b212b427) | Feb 18, 2023 |
| ASUSTek       | PRIME Z270-K                | [5ecce23878](https://linux-hardware.org/?probe=5ecce23878) | Feb 18, 2023 |
| MSI           | B450-A PRO MAX              | [13485dcee3](https://linux-hardware.org/?probe=13485dcee3) | Feb 18, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [06d9c4427a](https://linux-hardware.org/?probe=06d9c4427a) | Feb 18, 2023 |
| Intel         | H61                         | [c1a0ccd450](https://linux-hardware.org/?probe=c1a0ccd450) | Feb 17, 2023 |
| MSI           | 970A-G43                    | [e02e6e5509](https://linux-hardware.org/?probe=e02e6e5509) | Feb 17, 2023 |
| HP            | 8053                        | [adbabb5537](https://linux-hardware.org/?probe=adbabb5537) | Feb 17, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [7e8c7de460](https://linux-hardware.org/?probe=7e8c7de460) | Feb 17, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [dc2acd10eb](https://linux-hardware.org/?probe=dc2acd10eb) | Feb 17, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [e01cd81ae1](https://linux-hardware.org/?probe=e01cd81ae1) | Feb 16, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [d98e6087da](https://linux-hardware.org/?probe=d98e6087da) | Feb 16, 2023 |
| ASRock        | Z77 Extreme3                | [baa2750a13](https://linux-hardware.org/?probe=baa2750a13) | Feb 16, 2023 |
| Dell          | 0W2F8G A00                  | [aa7bf98168](https://linux-hardware.org/?probe=aa7bf98168) | Feb 16, 2023 |
| ASUSTek       | P5QPL-AM                    | [a3b4daa09d](https://linux-hardware.org/?probe=a3b4daa09d) | Feb 16, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [e8dc5253a3](https://linux-hardware.org/?probe=e8dc5253a3) | Feb 15, 2023 |
| MSI           | Z390-A PRO                  | [713f522b92](https://linux-hardware.org/?probe=713f522b92) | Feb 14, 2023 |
| Acer          | H410H6-M17 P21-A1           | [beaef7f0ab](https://linux-hardware.org/?probe=beaef7f0ab) | Feb 14, 2023 |
| ASUSTek       | PRIME B560-PLUS             | [348fef3dbb](https://linux-hardware.org/?probe=348fef3dbb) | Feb 13, 2023 |
| Shuttle       | FX79R                       | [b1631ebb53](https://linux-hardware.org/?probe=b1631ebb53) | Feb 13, 2023 |
| ASUSTek       | PRIME H510M-A               | [8583704242](https://linux-hardware.org/?probe=8583704242) | Feb 13, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [88b290f249](https://linux-hardware.org/?probe=88b290f249) | Feb 13, 2023 |
| ASRock        | B460 Phantom Gaming 4       | [785e6e2876](https://linux-hardware.org/?probe=785e6e2876) | Feb 12, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [35781b31c5](https://linux-hardware.org/?probe=35781b31c5) | Feb 12, 2023 |
| HP            | 3397                        | [b22590d882](https://linux-hardware.org/?probe=b22590d882) | Feb 11, 2023 |
| ASRock        | B460M-HDV                   | [cb5573dd52](https://linux-hardware.org/?probe=cb5573dd52) | Feb 11, 2023 |
| Dell          | 0T568R A00                  | [fedf0db748](https://linux-hardware.org/?probe=fedf0db748) | Feb 10, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | [e6bcd546ae](https://linux-hardware.org/?probe=e6bcd546ae) | Feb 10, 2023 |
| ASRock        | B450M Steel Legend          | [2a39868a05](https://linux-hardware.org/?probe=2a39868a05) | Feb 10, 2023 |
| ASRock        | Z77 Extreme3                | [0efa8164b3](https://linux-hardware.org/?probe=0efa8164b3) | Feb 10, 2023 |
| Gigabyte      | Z690 AORUS PRO              | [7a116a53c6](https://linux-hardware.org/?probe=7a116a53c6) | Feb 09, 2023 |
| Gigabyte      | Z87N-WIFI                   | [530627f086](https://linux-hardware.org/?probe=530627f086) | Feb 09, 2023 |
| ASUSTek       | B85M-G                      | [7f27fb0a83](https://linux-hardware.org/?probe=7f27fb0a83) | Feb 09, 2023 |
| MSI           | X570-A PRO                  | [9decf03532](https://linux-hardware.org/?probe=9decf03532) | Feb 09, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [157c2ef73f](https://linux-hardware.org/?probe=157c2ef73f) | Feb 09, 2023 |
| ASUSTek       | X99-PRO/USB                 | [29e3ebe102](https://linux-hardware.org/?probe=29e3ebe102) | Feb 09, 2023 |
| ASRock        | B460M-HDV                   | [dd0daa720e](https://linux-hardware.org/?probe=dd0daa720e) | Feb 08, 2023 |
| ASRock        | B460M-HDV                   | [4684c0511e](https://linux-hardware.org/?probe=4684c0511e) | Feb 08, 2023 |
| ASUSTek       | X99-PRO/USB                 | [d1f6f6da3a](https://linux-hardware.org/?probe=d1f6f6da3a) | Feb 08, 2023 |
| ASRock        | B450 Gaming K4              | [dd8fbe3d62](https://linux-hardware.org/?probe=dd8fbe3d62) | Feb 08, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [9d81046c8b](https://linux-hardware.org/?probe=9d81046c8b) | Feb 07, 2023 |
| Dell          | 0W2F8G A00                  | [b0694cfc5c](https://linux-hardware.org/?probe=b0694cfc5c) | Feb 06, 2023 |
| HP            | 3397                        | [a8f8381e48](https://linux-hardware.org/?probe=a8f8381e48) | Feb 05, 2023 |
| HP            | 3397                        | [c41ab8c19e](https://linux-hardware.org/?probe=c41ab8c19e) | Feb 05, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [add74ba4b4](https://linux-hardware.org/?probe=add74ba4b4) | Feb 05, 2023 |
| Shenzhen M... | F7BFC                       | [4d3066b96e](https://linux-hardware.org/?probe=4d3066b96e) | Feb 05, 2023 |
| Acer          | Aspire TC-885 V:1.1         | [898b87361c](https://linux-hardware.org/?probe=898b87361c) | Feb 05, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [66a494b2ec](https://linux-hardware.org/?probe=66a494b2ec) | Feb 04, 2023 |
| MSI           | MEG Z390 ACE                | [0528b7476a](https://linux-hardware.org/?probe=0528b7476a) | Feb 04, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [3f0bf3e580](https://linux-hardware.org/?probe=3f0bf3e580) | Feb 04, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [1998f6f225](https://linux-hardware.org/?probe=1998f6f225) | Feb 04, 2023 |
| Intel         | H61                         | [4189171d59](https://linux-hardware.org/?probe=4189171d59) | Feb 03, 2023 |
| ASUSTek       | P5G41T-M LX                 | [62882a0c3e](https://linux-hardware.org/?probe=62882a0c3e) | Feb 03, 2023 |
| ASUSTek       | PRIME B450M-A               | [19b6a074e8](https://linux-hardware.org/?probe=19b6a074e8) | Feb 03, 2023 |
| Gigabyte      | Z77M-D3H-MVP                | [9b2f47d039](https://linux-hardware.org/?probe=9b2f47d039) | Feb 02, 2023 |
| Gigabyte      | Z690 AORUS ELITE AX DDR4    | [115de2faed](https://linux-hardware.org/?probe=115de2faed) | Feb 01, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [4e438c4768](https://linux-hardware.org/?probe=4e438c4768) | Jan 31, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [66459fc07c](https://linux-hardware.org/?probe=66459fc07c) | Jan 31, 2023 |
| Gigabyte      | 945GCM-S2C                  | [41ad246a0b](https://linux-hardware.org/?probe=41ad246a0b) | Jan 31, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [f2a2476d45](https://linux-hardware.org/?probe=f2a2476d45) | Jan 31, 2023 |
| Gigabyte      | Z390 DESIGNARE-CF           | [02c8ae01d1](https://linux-hardware.org/?probe=02c8ae01d1) | Jan 30, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [070a09add8](https://linux-hardware.org/?probe=070a09add8) | Jan 30, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [8cca3cb036](https://linux-hardware.org/?probe=8cca3cb036) | Jan 30, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [02580dd501](https://linux-hardware.org/?probe=02580dd501) | Jan 30, 2023 |
| ASUSTek       | P5Q PRO TURBO               | [72e0a3fde5](https://linux-hardware.org/?probe=72e0a3fde5) | Jan 28, 2023 |
| ASUSTek       | P5Q PRO TURBO               | [a1cb8edb5a](https://linux-hardware.org/?probe=a1cb8edb5a) | Jan 28, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [8b5c80cad4](https://linux-hardware.org/?probe=8b5c80cad4) | Jan 28, 2023 |
| ASRock        | Z97 Killer                  | [2658d00cd2](https://linux-hardware.org/?probe=2658d00cd2) | Jan 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [31bda5eb31](https://linux-hardware.org/?probe=31bda5eb31) | Jan 28, 2023 |
| ASRock        | Z97 Killer                  | [d4c609c373](https://linux-hardware.org/?probe=d4c609c373) | Jan 27, 2023 |
| ASUSTek       | PRIME B450M-A               | [4a33dd0b76](https://linux-hardware.org/?probe=4a33dd0b76) | Jan 27, 2023 |
| ASRock        | X570 Taichi                 | [bdfb4aecf9](https://linux-hardware.org/?probe=bdfb4aecf9) | Jan 27, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | [65e298b3ee](https://linux-hardware.org/?probe=65e298b3ee) | Jan 27, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [5269e78083](https://linux-hardware.org/?probe=5269e78083) | Jan 26, 2023 |
| Lenovo        | NO DPK                      | [b1e29a464f](https://linux-hardware.org/?probe=b1e29a464f) | Jan 26, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | [5c55d923ff](https://linux-hardware.org/?probe=5c55d923ff) | Jan 26, 2023 |
| Intel         | DG965SS AAD41678-306        | [fde41db330](https://linux-hardware.org/?probe=fde41db330) | Jan 26, 2023 |
| ASUSTek       | PRIME B560M-A               | [78a1bfaac7](https://linux-hardware.org/?probe=78a1bfaac7) | Jan 25, 2023 |
| Gigabyte      | B550 AORUS ELITE AX         | [026efbc485](https://linux-hardware.org/?probe=026efbc485) | Jan 25, 2023 |
| Gigabyte      | B550 AORUS ELITE AX         | [184de230c5](https://linux-hardware.org/?probe=184de230c5) | Jan 25, 2023 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [996a0567b6](https://linux-hardware.org/?probe=996a0567b6) | Jan 23, 2023 |
| ASUSTek       | PRIME X570-PRO              | [b67d126993](https://linux-hardware.org/?probe=b67d126993) | Jan 23, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [7f1bb5c3c3](https://linux-hardware.org/?probe=7f1bb5c3c3) | Jan 23, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [f74d2ca84b](https://linux-hardware.org/?probe=f74d2ca84b) | Jan 23, 2023 |
| ASUSTek       | A68HM-PLUS                  | [3afbe94c21](https://linux-hardware.org/?probe=3afbe94c21) | Jan 23, 2023 |
| Gigabyte      | GA-970A-UD3                 | [a8d203f94b](https://linux-hardware.org/?probe=a8d203f94b) | Jan 23, 2023 |
| ASUSTek       | PRIME B450M-K               | [8a68388e16](https://linux-hardware.org/?probe=8a68388e16) | Jan 22, 2023 |
| Dell          | 0D28YY A00                  | [394be1956b](https://linux-hardware.org/?probe=394be1956b) | Jan 22, 2023 |
| ASUSTek       | Z97-K                       | [1261e08a8a](https://linux-hardware.org/?probe=1261e08a8a) | Jan 22, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [d1e0b2e009](https://linux-hardware.org/?probe=d1e0b2e009) | Jan 22, 2023 |
| Gigabyte      | Z97X-Gaming 7               | [a51b58dfbb](https://linux-hardware.org/?probe=a51b58dfbb) | Jan 22, 2023 |
| Shenzhen M... | F6BFC                       | [21f62b0eac](https://linux-hardware.org/?probe=21f62b0eac) | Jan 21, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [be39389c7f](https://linux-hardware.org/?probe=be39389c7f) | Jan 21, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [0d8275b0de](https://linux-hardware.org/?probe=0d8275b0de) | Jan 21, 2023 |
| Gigabyte      | Z87N-WIFI                   | [d77592ccf0](https://linux-hardware.org/?probe=d77592ccf0) | Jan 20, 2023 |
| ASUSTek       | M5A97 R2.0                  | [19eabab270](https://linux-hardware.org/?probe=19eabab270) | Jan 19, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [d0a387f425](https://linux-hardware.org/?probe=d0a387f425) | Jan 18, 2023 |
| Gigabyte      | H77-D3H                     | [15da5de3ae](https://linux-hardware.org/?probe=15da5de3ae) | Jan 18, 2023 |
| MSI           | H81I                        | [f51db4589d](https://linux-hardware.org/?probe=f51db4589d) | Jan 18, 2023 |
| Gigabyte      | 990FXA-UD3                  | [39591416ac](https://linux-hardware.org/?probe=39591416ac) | Jan 18, 2023 |
| Gigabyte      | Z87N-WIFI                   | [b796ac9a1d](https://linux-hardware.org/?probe=b796ac9a1d) | Jan 17, 2023 |
| Gigabyte      | F2A68HM-H                   | [d8d6e517e0](https://linux-hardware.org/?probe=d8d6e517e0) | Jan 17, 2023 |
| HP            | 805A                        | [0f9521809b](https://linux-hardware.org/?probe=0f9521809b) | Jan 17, 2023 |
| HP            | 805A                        | [4061c209e2](https://linux-hardware.org/?probe=4061c209e2) | Jan 17, 2023 |
| ASUSTek       | PRIME B560M-A AC            | [8cd20f181b](https://linux-hardware.org/?probe=8cd20f181b) | Jan 16, 2023 |
| Biostar       | A320MH                      | [1736406da7](https://linux-hardware.org/?probe=1736406da7) | Jan 16, 2023 |
| Intel         | X99                         | [9c0ea1f762](https://linux-hardware.org/?probe=9c0ea1f762) | Jan 16, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [02178066f5](https://linux-hardware.org/?probe=02178066f5) | Jan 16, 2023 |
| ASUSTek       | GD30CI                      | [7d1227f25f](https://linux-hardware.org/?probe=7d1227f25f) | Jan 15, 2023 |
| ASUSTek       | GD30CI                      | [2ed7e76dbe](https://linux-hardware.org/?probe=2ed7e76dbe) | Jan 15, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [ebe7fa8c2a](https://linux-hardware.org/?probe=ebe7fa8c2a) | Jan 14, 2023 |
| Dell          | 00V62H A01                  | [47aa34eddd](https://linux-hardware.org/?probe=47aa34eddd) | Jan 14, 2023 |
| Gigabyte      | B450M S2H                   | [e92f01ff78](https://linux-hardware.org/?probe=e92f01ff78) | Jan 14, 2023 |
| ASRock        | B450 Gaming K4              | [5bcda073b3](https://linux-hardware.org/?probe=5bcda073b3) | Jan 13, 2023 |
| Shuttle       | FS61                        | [9034ce313b](https://linux-hardware.org/?probe=9034ce313b) | Jan 12, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [4cb06b24fd](https://linux-hardware.org/?probe=4cb06b24fd) | Jan 11, 2023 |
| Gigabyte      | A320M-S2H-CF                | [d26bcd74b2](https://linux-hardware.org/?probe=d26bcd74b2) | Jan 10, 2023 |
| Gigabyte      | A320M-S2H-CF                | [faf7e2eae9](https://linux-hardware.org/?probe=faf7e2eae9) | Jan 10, 2023 |
| ASRock        | Z87M Extreme4               | [4aa4793173](https://linux-hardware.org/?probe=4aa4793173) | Jan 10, 2023 |
| ASUSTek       | PRIME Z270-A                | [b4c192526f](https://linux-hardware.org/?probe=b4c192526f) | Jan 08, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [874ab2d9a6](https://linux-hardware.org/?probe=874ab2d9a6) | Jan 07, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [f09e26eaa3](https://linux-hardware.org/?probe=f09e26eaa3) | Jan 07, 2023 |
| Intel         | DG35EC AAE29266-205         | [29654c0c64](https://linux-hardware.org/?probe=29654c0c64) | Jan 06, 2023 |
| Gigabyte      | B450M S2H                   | [bf90b7d77d](https://linux-hardware.org/?probe=bf90b7d77d) | Jan 06, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [f188e7e419](https://linux-hardware.org/?probe=f188e7e419) | Jan 04, 2023 |
| Lenovo        | 31900058 STD or WIN         | [21cdab1361](https://linux-hardware.org/?probe=21cdab1361) | Jan 03, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [32e666defa](https://linux-hardware.org/?probe=32e666defa) | Jan 03, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [c2c723d7b2](https://linux-hardware.org/?probe=c2c723d7b2) | Jan 03, 2023 |
| ASUSTek       | PRIME B550M-K               | [395606c638](https://linux-hardware.org/?probe=395606c638) | Jan 03, 2023 |
| ASUSTek       | B85M-E/BR                   | [88f7654113](https://linux-hardware.org/?probe=88f7654113) | Jan 02, 2023 |
| Lenovo        | Dory CRB                    | [c87645ef7b](https://linux-hardware.org/?probe=c87645ef7b) | Jan 02, 2023 |
| MSI           | A520M-A PRO                 | [28a0c6dda9](https://linux-hardware.org/?probe=28a0c6dda9) | Jan 02, 2023 |
| ASRock        | B450M Pro4                  | [7b9bc5bc99](https://linux-hardware.org/?probe=7b9bc5bc99) | Jan 02, 2023 |
| Dell          | 0PU052                      | [82740aac1d](https://linux-hardware.org/?probe=82740aac1d) | Jan 02, 2023 |
| Dell          | 0PU052                      | [e40981850d](https://linux-hardware.org/?probe=e40981850d) | Jan 02, 2023 |
| Dell          | 04YP6J A02                  | [ee7f6ddcc1](https://linux-hardware.org/?probe=ee7f6ddcc1) | Jan 01, 2023 |
| ASUSTek       | M5A97 R2.0                  | [e877a9f9e3](https://linux-hardware.org/?probe=e877a9f9e3) | Jan 01, 2023 |
| AZW           | GTR V02                     | [5c08e4403a](https://linux-hardware.org/?probe=5c08e4403a) | Jan 01, 2023 |
| ASRock        | B550M Pro4                  | [ddab7428a1](https://linux-hardware.org/?probe=ddab7428a1) | Jan 01, 2023 |
| ASRock        | B550M Pro4                  | [7389925566](https://linux-hardware.org/?probe=7389925566) | Jan 01, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [7e22db9b23](https://linux-hardware.org/?probe=7e22db9b23) | Dec 31, 2022 |
| ASRock        | B550 Steel Legend           | [8705e10ac6](https://linux-hardware.org/?probe=8705e10ac6) | Dec 31, 2022 |
| ASUSTek       | PRIME X670-P WIFI           | [cecef0575d](https://linux-hardware.org/?probe=cecef0575d) | Dec 30, 2022 |
| Gigabyte      | Z87-HD3                     | [97f08bd689](https://linux-hardware.org/?probe=97f08bd689) | Dec 30, 2022 |
| Gigabyte      | H510M H                     | [24574296e5](https://linux-hardware.org/?probe=24574296e5) | Dec 29, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [7a7f335c4a](https://linux-hardware.org/?probe=7a7f335c4a) | Dec 29, 2022 |
| MSI           | X370 GAMING M7 ACK          | [60fe0d0b31](https://linux-hardware.org/?probe=60fe0d0b31) | Dec 29, 2022 |
| MSI           | PRO B660M-A DDR4            | [dbc37ff826](https://linux-hardware.org/?probe=dbc37ff826) | Dec 29, 2022 |
| Dell          | 0TTDMJ A00                  | [198e723dc2](https://linux-hardware.org/?probe=198e723dc2) | Dec 28, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [6d56c4c392](https://linux-hardware.org/?probe=6d56c4c392) | Dec 27, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [d6a12148ec](https://linux-hardware.org/?probe=d6a12148ec) | Dec 27, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [bd232cd937](https://linux-hardware.org/?probe=bd232cd937) | Dec 27, 2022 |
| Gigabyte      | Z370 HD3-CF                 | [ac6571db76](https://linux-hardware.org/?probe=ac6571db76) | Dec 27, 2022 |
| ASRock        | Z690 Taichi                 | [4a4e2975d2](https://linux-hardware.org/?probe=4a4e2975d2) | Dec 27, 2022 |
| ASUSTek       | M5A78L-M LX3                | [a6c0667059](https://linux-hardware.org/?probe=a6c0667059) | Dec 27, 2022 |
| ASUSTek       | M5A78L-M LX3                | [ad94a727ab](https://linux-hardware.org/?probe=ad94a727ab) | Dec 27, 2022 |
| ASRock        | AB350M-HDV                  | [666ea6d820](https://linux-hardware.org/?probe=666ea6d820) | Dec 26, 2022 |
| ASUSTek       | M5A97 R2.0                  | [be1ace7f20](https://linux-hardware.org/?probe=be1ace7f20) | Dec 26, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [82de75771e](https://linux-hardware.org/?probe=82de75771e) | Dec 25, 2022 |
| ASRock        | X670E Pro RS                | [b7a0a3d703](https://linux-hardware.org/?probe=b7a0a3d703) | Dec 24, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [e3e2773bde](https://linux-hardware.org/?probe=e3e2773bde) | Dec 24, 2022 |
| Gigabyte      | H510M H                     | [d592546f0a](https://linux-hardware.org/?probe=d592546f0a) | Dec 23, 2022 |
| Gigabyte      | H510M H                     | [52f1e32fc8](https://linux-hardware.org/?probe=52f1e32fc8) | Dec 23, 2022 |
| Dell          | 0GY6Y8 A02                  | [1044231936](https://linux-hardware.org/?probe=1044231936) | Dec 22, 2022 |
| HP            | 8053                        | [38b3012a7c](https://linux-hardware.org/?probe=38b3012a7c) | Dec 22, 2022 |
| ASRock        | X670E Taichi                | [e1b13226a4](https://linux-hardware.org/?probe=e1b13226a4) | Dec 21, 2022 |
| ASRock        | AB350 Pro4                  | [c7005e1e89](https://linux-hardware.org/?probe=c7005e1e89) | Dec 21, 2022 |
| Gigabyte      | Z690 AORUS PRO              | [dbefd12c1c](https://linux-hardware.org/?probe=dbefd12c1c) | Dec 19, 2022 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | [9fb0357e3e](https://linux-hardware.org/?probe=9fb0357e3e) | Dec 19, 2022 |
| ASRock        | Z390 Pro4                   | [478165e478](https://linux-hardware.org/?probe=478165e478) | Dec 18, 2022 |
| Gigabyte      | B550M DS3H                  | [d868b73cfb](https://linux-hardware.org/?probe=d868b73cfb) | Dec 18, 2022 |
| Gigabyte      | B460M AORUS PRO             | [6deb38fb48](https://linux-hardware.org/?probe=6deb38fb48) | Dec 17, 2022 |
| MSI           | X370 GAMING M7 ACK          | [71dabd9e44](https://linux-hardware.org/?probe=71dabd9e44) | Dec 17, 2022 |
| MSI           | A68HM-E33                   | [0df6f80110](https://linux-hardware.org/?probe=0df6f80110) | Dec 17, 2022 |
| MSI           | X370 GAMING M7 ACK          | [3b245437e5](https://linux-hardware.org/?probe=3b245437e5) | Dec 17, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [d2dce9cbfd](https://linux-hardware.org/?probe=d2dce9cbfd) | Dec 16, 2022 |
| Gigabyte      | H510M H                     | [ccb746cd73](https://linux-hardware.org/?probe=ccb746cd73) | Dec 15, 2022 |
| ZOTAC         | ION                         | [f02f6b8382](https://linux-hardware.org/?probe=f02f6b8382) | Dec 15, 2022 |
| Dell          | 0D6H9T A02                  | [6266999282](https://linux-hardware.org/?probe=6266999282) | Dec 15, 2022 |
| Gigabyte      | B450M H                     | [c888c743e3](https://linux-hardware.org/?probe=c888c743e3) | Dec 15, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [7d15ecff86](https://linux-hardware.org/?probe=7d15ecff86) | Dec 15, 2022 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [72175490ae](https://linux-hardware.org/?probe=72175490ae) | Dec 15, 2022 |
| MSI           | B250 GAMING M3              | [cf050915a5](https://linux-hardware.org/?probe=cf050915a5) | Dec 14, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [39d58ec9aa](https://linux-hardware.org/?probe=39d58ec9aa) | Dec 13, 2022 |
| ASUSTek       | X99-A II                    | [a6e0258bbe](https://linux-hardware.org/?probe=a6e0258bbe) | Dec 13, 2022 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [8fd3c60681](https://linux-hardware.org/?probe=8fd3c60681) | Dec 13, 2022 |
| Intel         | Eaglelake Fab D             | [ed5c44a200](https://linux-hardware.org/?probe=ed5c44a200) | Dec 13, 2022 |
| MSI           | B450I GAMING PLUS MAX WI... | [0973466d88](https://linux-hardware.org/?probe=0973466d88) | Dec 13, 2022 |
| MSI           | B450I GAMING PLUS MAX WI... | [9d2ef8adf1](https://linux-hardware.org/?probe=9d2ef8adf1) | Dec 13, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [c5501c208c](https://linux-hardware.org/?probe=c5501c208c) | Dec 11, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [6964e348d6](https://linux-hardware.org/?probe=6964e348d6) | Dec 11, 2022 |
| ASUSTek       | X99-A II                    | [09f8da551c](https://linux-hardware.org/?probe=09f8da551c) | Dec 11, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [23be4288bb](https://linux-hardware.org/?probe=23be4288bb) | Dec 11, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [121359234c](https://linux-hardware.org/?probe=121359234c) | Dec 11, 2022 |
| ASUSTek       | PRIME X570-P                | [6b00f35a38](https://linux-hardware.org/?probe=6b00f35a38) | Dec 10, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [deab1a46db](https://linux-hardware.org/?probe=deab1a46db) | Dec 10, 2022 |
| ASUSTek       | PRIME B550M-A               | [e843a9c61d](https://linux-hardware.org/?probe=e843a9c61d) | Dec 10, 2022 |
| Gigabyte      | Z170-HD3P-CF                | [27fdfb657e](https://linux-hardware.org/?probe=27fdfb657e) | Dec 09, 2022 |
| Gigabyte      | B550M S2H                   | [5e56097f25](https://linux-hardware.org/?probe=5e56097f25) | Dec 08, 2022 |
| MSI           | PRO B650-P WIFI             | [b74866314e](https://linux-hardware.org/?probe=b74866314e) | Dec 08, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [d6666dccec](https://linux-hardware.org/?probe=d6666dccec) | Dec 08, 2022 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | [c6895362e6](https://linux-hardware.org/?probe=c6895362e6) | Dec 07, 2022 |
| Lenovo        | ThinkStation S20 4157DT6    | [7c45cf5115](https://linux-hardware.org/?probe=7c45cf5115) | Dec 07, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | [037c8e9cbc](https://linux-hardware.org/?probe=037c8e9cbc) | Dec 06, 2022 |
| Gigabyte      | F2A58M-HD2                  | [61c23e2501](https://linux-hardware.org/?probe=61c23e2501) | Dec 06, 2022 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | [689479ce87](https://linux-hardware.org/?probe=689479ce87) | Dec 06, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [f11d4ebe40](https://linux-hardware.org/?probe=f11d4ebe40) | Dec 05, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [ddd1487d81](https://linux-hardware.org/?probe=ddd1487d81) | Dec 05, 2022 |
| HP            | 8053                        | [5fad592ef3](https://linux-hardware.org/?probe=5fad592ef3) | Dec 05, 2022 |
| Gigabyte      | B550M S2H                   | [dd012c9f92](https://linux-hardware.org/?probe=dd012c9f92) | Dec 04, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [9eb248d38e](https://linux-hardware.org/?probe=9eb248d38e) | Dec 04, 2022 |
| ASUSTek       | M5A97 R2.0                  | [b3b5eb90e5](https://linux-hardware.org/?probe=b3b5eb90e5) | Dec 03, 2022 |
| ASRock        | Z87 Extreme4                | [422dde5ae5](https://linux-hardware.org/?probe=422dde5ae5) | Dec 03, 2022 |
| MSI           | B450I GAMING PLUS AC        | [366f9ae2aa](https://linux-hardware.org/?probe=366f9ae2aa) | Dec 03, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [ec36ceb3fd](https://linux-hardware.org/?probe=ec36ceb3fd) | Dec 02, 2022 |
| MSI           | A68HM-E33                   | [4e2313d8b7](https://linux-hardware.org/?probe=4e2313d8b7) | Dec 02, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [8cf4925f08](https://linux-hardware.org/?probe=8cf4925f08) | Dec 01, 2022 |
| ASRock        | X300M-STX                   | [97ceee65f3](https://linux-hardware.org/?probe=97ceee65f3) | Dec 01, 2022 |
| ASRock        | X300M-STX                   | [5b7f983a24](https://linux-hardware.org/?probe=5b7f983a24) | Dec 01, 2022 |
| ASRock        | X300M-STX                   | [42ddb2463e](https://linux-hardware.org/?probe=42ddb2463e) | Dec 01, 2022 |
| Gigabyte      | Z370 HD3-CF                 | [ece7618688](https://linux-hardware.org/?probe=ece7618688) | Nov 30, 2022 |
| ASRock        | B550M Pro4                  | [f48969af69](https://linux-hardware.org/?probe=f48969af69) | Nov 29, 2022 |
| Dell          | 09WH54 A00                  | [2700be5b4a](https://linux-hardware.org/?probe=2700be5b4a) | Nov 28, 2022 |
| Gigabyte      | M61PME-S2P                  | [4aa3d8ee32](https://linux-hardware.org/?probe=4aa3d8ee32) | Nov 27, 2022 |
| HP            | 3397                        | [e264b68f30](https://linux-hardware.org/?probe=e264b68f30) | Nov 27, 2022 |
| Gigabyte      | 970A-DS3P FX                | [4ded1fb943](https://linux-hardware.org/?probe=4ded1fb943) | Nov 26, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [bb0d4b34af](https://linux-hardware.org/?probe=bb0d4b34af) | Nov 26, 2022 |
| Gigabyte      | A320M-H-CF                  | [5f1188d448](https://linux-hardware.org/?probe=5f1188d448) | Nov 26, 2022 |
| ASRock        | B550M Pro4                  | [0828e5929e](https://linux-hardware.org/?probe=0828e5929e) | Nov 26, 2022 |
| Gigabyte      | A320M-H-CF                  | [771019bcc6](https://linux-hardware.org/?probe=771019bcc6) | Nov 26, 2022 |
| Gigabyte      | B550M S2H                   | [8ea3c120c6](https://linux-hardware.org/?probe=8ea3c120c6) | Nov 23, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [6cd720c62c](https://linux-hardware.org/?probe=6cd720c62c) | Nov 23, 2022 |
| MSI           | PRO Z690-A DDR4             | [fc53a66047](https://linux-hardware.org/?probe=fc53a66047) | Nov 22, 2022 |
| ASUSTek       | Maximus VI GENE             | [62b0cb4c94](https://linux-hardware.org/?probe=62b0cb4c94) | Nov 22, 2022 |
| ASUSTek       | Maximus VI GENE             | [26e7d04331](https://linux-hardware.org/?probe=26e7d04331) | Nov 22, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [a22e271ac2](https://linux-hardware.org/?probe=a22e271ac2) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [64cff39a82](https://linux-hardware.org/?probe=64cff39a82) | Nov 21, 2022 |
| ASRock        | B550M Pro4                  | [7d1d0390ba](https://linux-hardware.org/?probe=7d1d0390ba) | Nov 20, 2022 |
| MSI           | 970A-G43                    | [6c04d813ff](https://linux-hardware.org/?probe=6c04d813ff) | Nov 20, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [d40491a06a](https://linux-hardware.org/?probe=d40491a06a) | Nov 19, 2022 |
| Intel         | DH55PJ AAE93812-303         | [bebe890c96](https://linux-hardware.org/?probe=bebe890c96) | Nov 19, 2022 |
| ASUSTek       | PRIME A320M-K               | [6d02e2a960](https://linux-hardware.org/?probe=6d02e2a960) | Nov 19, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [598f8e7c34](https://linux-hardware.org/?probe=598f8e7c34) | Nov 19, 2022 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | [c8fc039301](https://linux-hardware.org/?probe=c8fc039301) | Nov 19, 2022 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | [1ffee02fee](https://linux-hardware.org/?probe=1ffee02fee) | Nov 19, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [312da35b57](https://linux-hardware.org/?probe=312da35b57) | Nov 17, 2022 |
| ASUSTek       | Maximus VIII GENE           | [8b542ffc42](https://linux-hardware.org/?probe=8b542ffc42) | Nov 17, 2022 |
| MSI           | X79A-GD45                   | [7f7b7354b8](https://linux-hardware.org/?probe=7f7b7354b8) | Nov 17, 2022 |
| MSI           | X79A-GD45                   | [42d08e1136](https://linux-hardware.org/?probe=42d08e1136) | Nov 17, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [f5fd3e9e4b](https://linux-hardware.org/?probe=f5fd3e9e4b) | Nov 16, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [07d80f1783](https://linux-hardware.org/?probe=07d80f1783) | Nov 16, 2022 |
| Gigabyte      | GA-A75M-UD2H                | [4da8ff348a](https://linux-hardware.org/?probe=4da8ff348a) | Nov 15, 2022 |
| ASRock        | A320M-HDV R4.0              | [7764c0fea2](https://linux-hardware.org/?probe=7764c0fea2) | Nov 15, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [c8c74ea1ec](https://linux-hardware.org/?probe=c8c74ea1ec) | Nov 15, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [567b81705d](https://linux-hardware.org/?probe=567b81705d) | Nov 15, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [389d8cf0e0](https://linux-hardware.org/?probe=389d8cf0e0) | Nov 15, 2022 |
| ASUSTek       | PRIME B350M-A               | [aabc2148da](https://linux-hardware.org/?probe=aabc2148da) | Nov 15, 2022 |
| MSI           | Z97A GAMING 7               | [275a1c28dd](https://linux-hardware.org/?probe=275a1c28dd) | Nov 13, 2022 |
| ASUSTek       | PRIME X470-PRO              | [370fb87faa](https://linux-hardware.org/?probe=370fb87faa) | Nov 13, 2022 |
| MSI           | B85M-P33 V2                 | [d633461307](https://linux-hardware.org/?probe=d633461307) | Nov 13, 2022 |
| ASRock        | X300M-STX                   | [6b2e935e07](https://linux-hardware.org/?probe=6b2e935e07) | Nov 12, 2022 |
| ASRock        | X300M-STX                   | [b071af765d](https://linux-hardware.org/?probe=b071af765d) | Nov 12, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [87b7416681](https://linux-hardware.org/?probe=87b7416681) | Nov 12, 2022 |
| ASUSTek       | PRIME A320M-K               | [f4ed581802](https://linux-hardware.org/?probe=f4ed581802) | Nov 11, 2022 |
| ASUSTek       | PRIME A320M-K               | [e06ab9c0b9](https://linux-hardware.org/?probe=e06ab9c0b9) | Nov 11, 2022 |
| Gigabyte      | H410M S2H V3                | [2172ca7325](https://linux-hardware.org/?probe=2172ca7325) | Nov 11, 2022 |
| MSI           | X79A-GD45                   | [cb82895374](https://linux-hardware.org/?probe=cb82895374) | Nov 11, 2022 |
| Gigabyte      | Z690 AORUS PRO              | [8dcd548e89](https://linux-hardware.org/?probe=8dcd548e89) | Nov 10, 2022 |
| Gigabyte      | Z690 AORUS PRO              | [e95608162f](https://linux-hardware.org/?probe=e95608162f) | Nov 10, 2022 |
| ASUSTek       | H110M-A                     | [4868cf87f5](https://linux-hardware.org/?probe=4868cf87f5) | Nov 09, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [9571026291](https://linux-hardware.org/?probe=9571026291) | Nov 08, 2022 |
| ASRock        | X300M-STX                   | [1fee3f08a9](https://linux-hardware.org/?probe=1fee3f08a9) | Nov 07, 2022 |
| MSI           | B550-A PRO                  | [6c4ff211d1](https://linux-hardware.org/?probe=6c4ff211d1) | Nov 07, 2022 |
| HP            | 844C                        | [5b8b05d13d](https://linux-hardware.org/?probe=5b8b05d13d) | Nov 07, 2022 |
| ASRock        | AB350M                      | [fae0de4ece](https://linux-hardware.org/?probe=fae0de4ece) | Nov 07, 2022 |
| Pegatron      | 2AB6                        | [c55efc41db](https://linux-hardware.org/?probe=c55efc41db) | Nov 06, 2022 |
| HP            | 828A                        | [42d15a94b0](https://linux-hardware.org/?probe=42d15a94b0) | Nov 06, 2022 |
| ASRock        | H310CM-HDV                  | [cb1cecc5e1](https://linux-hardware.org/?probe=cb1cecc5e1) | Nov 05, 2022 |
| ASUSTek       | P8H61-M LE/CSM              | [fb29e83d2d](https://linux-hardware.org/?probe=fb29e83d2d) | Nov 05, 2022 |
| ASUSTek       | P8H67                       | [0d98e4b3b3](https://linux-hardware.org/?probe=0d98e4b3b3) | Nov 05, 2022 |
| Lenovo        | 3728 SDK0J40700 WIN 3258... | [6700909ef7](https://linux-hardware.org/?probe=6700909ef7) | Nov 03, 2022 |
| ASUSTek       | M5A97 R2.0                  | [fecd8f06dd](https://linux-hardware.org/?probe=fecd8f06dd) | Nov 02, 2022 |
| HP            | 8054                        | [0f866b3605](https://linux-hardware.org/?probe=0f866b3605) | Nov 02, 2022 |
| ASUSTek       | P5K-E                       | [6b48759d1d](https://linux-hardware.org/?probe=6b48759d1d) | Nov 02, 2022 |
| MSI           | Z370 GAMING PLUS            | [527c779cfb](https://linux-hardware.org/?probe=527c779cfb) | Nov 01, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [8ce0b9271b](https://linux-hardware.org/?probe=8ce0b9271b) | Nov 01, 2022 |
| MSI           | MAG B660M MORTAR WIFI DD... | [115e9027d0](https://linux-hardware.org/?probe=115e9027d0) | Nov 01, 2022 |
| Acer          | H410H6-M17 P21-A1           | [9333be5120](https://linux-hardware.org/?probe=9333be5120) | Nov 01, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [6e577f6de5](https://linux-hardware.org/?probe=6e577f6de5) | Nov 01, 2022 |
| HP            | 3397                        | [942cfa2a25](https://linux-hardware.org/?probe=942cfa2a25) | Oct 31, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [f497e98b58](https://linux-hardware.org/?probe=f497e98b58) | Oct 31, 2022 |
| Gigabyte      | Z77M-D3H                    | [83cd207e4e](https://linux-hardware.org/?probe=83cd207e4e) | Oct 30, 2022 |
| ASRock        | X570 Pro4                   | [d2407c253b](https://linux-hardware.org/?probe=d2407c253b) | Oct 30, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [7d6c392e74](https://linux-hardware.org/?probe=7d6c392e74) | Oct 29, 2022 |
| Gigabyte      | Z370 HD3-CF                 | [06cb3f01ba](https://linux-hardware.org/?probe=06cb3f01ba) | Oct 29, 2022 |
| ASUSTek       | PRIME A320M-K               | [25caeb6d9e](https://linux-hardware.org/?probe=25caeb6d9e) | Oct 29, 2022 |
| ASUSTek       | PRIME B365M-C               | [ccf9650f9a](https://linux-hardware.org/?probe=ccf9650f9a) | Oct 29, 2022 |
| Acer          | Aspire TC-885 V:1.1         | [81ccab7297](https://linux-hardware.org/?probe=81ccab7297) | Oct 29, 2022 |
| ASUSTek       | PRIME A320M-K               | [5876a2f3d6](https://linux-hardware.org/?probe=5876a2f3d6) | Oct 28, 2022 |
| ASUSTek       | P9X79-WS-SYS                | [8b10d380a5](https://linux-hardware.org/?probe=8b10d380a5) | Oct 28, 2022 |
| ASRock        | B550M Pro4                  | [b21b6b2908](https://linux-hardware.org/?probe=b21b6b2908) | Oct 27, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2227bb9824](https://linux-hardware.org/?probe=2227bb9824) | Oct 25, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | [1f3561258a](https://linux-hardware.org/?probe=1f3561258a) | Oct 25, 2022 |
| Unknown       | 1.0                         | [cf3a9de207](https://linux-hardware.org/?probe=cf3a9de207) | Oct 25, 2022 |
| MSI           | H97 PC Mate                 | [1916f5c048](https://linux-hardware.org/?probe=1916f5c048) | Oct 25, 2022 |
| Acer          | Aspire MC605 v1.0           | [9544ff7787](https://linux-hardware.org/?probe=9544ff7787) | Oct 24, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [4b88876126](https://linux-hardware.org/?probe=4b88876126) | Oct 24, 2022 |
| HP            | 828A                        | [2123f2610c](https://linux-hardware.org/?probe=2123f2610c) | Oct 24, 2022 |
| MSI           | Z68MA-G45                   | [3f398756eb](https://linux-hardware.org/?probe=3f398756eb) | Oct 23, 2022 |
| MSI           | Z68MA-G45                   | [d96627943d](https://linux-hardware.org/?probe=d96627943d) | Oct 23, 2022 |
| Lenovo        | ThinkCentre A57 9851CDF     | [8910fecc7d](https://linux-hardware.org/?probe=8910fecc7d) | Oct 23, 2022 |
| Gigabyte      | Z690 AORUS PRO              | [7cb3500943](https://linux-hardware.org/?probe=7cb3500943) | Oct 22, 2022 |
| Gigabyte      | B365M DS3H                  | [d5f16dde87](https://linux-hardware.org/?probe=d5f16dde87) | Oct 22, 2022 |
| ASUSTek       | P8Z68-V GEN3                | [e1dedae10a](https://linux-hardware.org/?probe=e1dedae10a) | Oct 22, 2022 |
| ASRock        | H310CM-HDV                  | [afe54b52c9](https://linux-hardware.org/?probe=afe54b52c9) | Oct 21, 2022 |
| ASUSTek       | ROG STRIX B360-G GAMING     | [eaad7f0757](https://linux-hardware.org/?probe=eaad7f0757) | Oct 20, 2022 |
| Gigabyte      | H61M-S2V-B3                 | [9e7b79bfbb](https://linux-hardware.org/?probe=9e7b79bfbb) | Oct 20, 2022 |
| ASUSTek       | Pro WS X570-ACE             | [7f069e1021](https://linux-hardware.org/?probe=7f069e1021) | Oct 20, 2022 |
| ASUSTek       | H110M-K                     | [a43f7f6601](https://linux-hardware.org/?probe=a43f7f6601) | Oct 19, 2022 |
| ASUSTek       | H170 PRO GAMING             | [cb86d1ba99](https://linux-hardware.org/?probe=cb86d1ba99) | Oct 18, 2022 |
| ASRock        | X670E PG Lightning          | [c3ce6dce01](https://linux-hardware.org/?probe=c3ce6dce01) | Oct 18, 2022 |
| Foxconn       | 2ABF                        | [ac2c9383c0](https://linux-hardware.org/?probe=ac2c9383c0) | Oct 18, 2022 |
| ASRock        | H310CM-HDV                  | [2426012acb](https://linux-hardware.org/?probe=2426012acb) | Oct 18, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [98024d1066](https://linux-hardware.org/?probe=98024d1066) | Oct 17, 2022 |
| MACHINIST     | X79 V2.82H                  | [5d99fbefc1](https://linux-hardware.org/?probe=5d99fbefc1) | Oct 17, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [7de3eff9df](https://linux-hardware.org/?probe=7de3eff9df) | Oct 16, 2022 |
| Gigabyte      | X399 AORUS PRO-CF           | [93e82a30ac](https://linux-hardware.org/?probe=93e82a30ac) | Oct 16, 2022 |
| Gigabyte      | X399 AORUS PRO-CF           | [eb9b7e329b](https://linux-hardware.org/?probe=eb9b7e329b) | Oct 16, 2022 |
| ASUSTek       | P8H77-V                     | [d6af5204e6](https://linux-hardware.org/?probe=d6af5204e6) | Oct 14, 2022 |
| Gigabyte      | H510M H                     | [28a0b7d55f](https://linux-hardware.org/?probe=28a0b7d55f) | Oct 14, 2022 |
| HP            | 802E                        | [6231a344aa](https://linux-hardware.org/?probe=6231a344aa) | Oct 14, 2022 |
| Dell          | 0HN7XN A01                  | [a71fb08b36](https://linux-hardware.org/?probe=a71fb08b36) | Oct 14, 2022 |
| Dell          | 0HN7XN A01                  | [abf7c780d2](https://linux-hardware.org/?probe=abf7c780d2) | Oct 13, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [f55bb836c3](https://linux-hardware.org/?probe=f55bb836c3) | Oct 13, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [8e2b577a03](https://linux-hardware.org/?probe=8e2b577a03) | Oct 13, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [dd9695948c](https://linux-hardware.org/?probe=dd9695948c) | Oct 11, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [d006fa9a19](https://linux-hardware.org/?probe=d006fa9a19) | Oct 11, 2022 |
| Gigabyte      | B450M H                     | [36fc5f2c90](https://linux-hardware.org/?probe=36fc5f2c90) | Oct 10, 2022 |
| Gigabyte      | B450M H                     | [c3dc2e33df](https://linux-hardware.org/?probe=c3dc2e33df) | Oct 10, 2022 |
| HP            | 8460                        | [08601807cc](https://linux-hardware.org/?probe=08601807cc) | Oct 10, 2022 |
| HP            | 8460                        | [5be586f271](https://linux-hardware.org/?probe=5be586f271) | Oct 10, 2022 |
| ASUSTek       | P6X58-E-WS                  | [786a8ba316](https://linux-hardware.org/?probe=786a8ba316) | Oct 09, 2022 |
| Dell          | 0TTDMJ A00                  | [656b9369be](https://linux-hardware.org/?probe=656b9369be) | Oct 09, 2022 |
| ASRock        | B550M Steel Legend          | [740a5f78d8](https://linux-hardware.org/?probe=740a5f78d8) | Oct 09, 2022 |
| Gigabyte      | B450 GAMING X               | [a297c351ed](https://linux-hardware.org/?probe=a297c351ed) | Oct 09, 2022 |
| Dell          | 0NW73C A00                  | [2b0a3f91ea](https://linux-hardware.org/?probe=2b0a3f91ea) | Oct 08, 2022 |
| Dell          | 0M9KCM A01                  | [6fa93f6da5](https://linux-hardware.org/?probe=6fa93f6da5) | Oct 07, 2022 |
| Gigabyte      | P55M-UD2                    | [e9627c4c34](https://linux-hardware.org/?probe=e9627c4c34) | Oct 07, 2022 |
| Dell          | 0D24M8 A00                  | [8130af2fab](https://linux-hardware.org/?probe=8130af2fab) | Oct 06, 2022 |
| HP            | 87D6 SMVB                   | [03cf885086](https://linux-hardware.org/?probe=03cf885086) | Oct 05, 2022 |
| Gigabyte      | H510M H                     | [a4c0e2324f](https://linux-hardware.org/?probe=a4c0e2324f) | Oct 04, 2022 |
| HP            | 21D0                        | [6815e2bba2](https://linux-hardware.org/?probe=6815e2bba2) | Oct 04, 2022 |
| Dell          | 0HN7XN A00                  | [77776da6f7](https://linux-hardware.org/?probe=77776da6f7) | Oct 03, 2022 |
| Dell          | 0HN7XN A00                  | [84d4748b3e](https://linux-hardware.org/?probe=84d4748b3e) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [668ad3e30a](https://linux-hardware.org/?probe=668ad3e30a) | Oct 02, 2022 |
| ASRock        | B450 Pro4                   | [402a7995c4](https://linux-hardware.org/?probe=402a7995c4) | Oct 02, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [15a068e26b](https://linux-hardware.org/?probe=15a068e26b) | Oct 01, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [3a9d882d91](https://linux-hardware.org/?probe=3a9d882d91) | Oct 01, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [dda857d7e6](https://linux-hardware.org/?probe=dda857d7e6) | Oct 01, 2022 |
| Gigabyte      | Z170X-Gaming GT             | [991ea6c93f](https://linux-hardware.org/?probe=991ea6c93f) | Oct 01, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [32a742b50d](https://linux-hardware.org/?probe=32a742b50d) | Oct 01, 2022 |
| Dell          | 07PR60 A01                  | [812cb18129](https://linux-hardware.org/?probe=812cb18129) | Sep 30, 2022 |
| Dell          | 0HN7XN A00                  | [c9126cd382](https://linux-hardware.org/?probe=c9126cd382) | Sep 30, 2022 |
| ASRock        | X399M Taichi                | [b7943d1645](https://linux-hardware.org/?probe=b7943d1645) | Sep 29, 2022 |
| Gigabyte      | Z690 GAMING X DDR4          | [b372f8126f](https://linux-hardware.org/?probe=b372f8126f) | Sep 29, 2022 |
| ASRock        | J3160DC-ITX                 | [7e1818288f](https://linux-hardware.org/?probe=7e1818288f) | Sep 29, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [c83049a0f6](https://linux-hardware.org/?probe=c83049a0f6) | Sep 29, 2022 |
| ASRock        | Z97 Pro3                    | [7b34a50df8](https://linux-hardware.org/?probe=7b34a50df8) | Sep 28, 2022 |
| ASRock        | B450 Pro4                   | [6a9066019c](https://linux-hardware.org/?probe=6a9066019c) | Sep 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [76aac25208](https://linux-hardware.org/?probe=76aac25208) | Sep 28, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [27ce89f701](https://linux-hardware.org/?probe=27ce89f701) | Sep 28, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [30507c8461](https://linux-hardware.org/?probe=30507c8461) | Sep 27, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [e5b4fe8914](https://linux-hardware.org/?probe=e5b4fe8914) | Sep 25, 2022 |
| ASUSTek       | Rampage V EDITION 10        | [c65cbf84dc](https://linux-hardware.org/?probe=c65cbf84dc) | Sep 25, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [e47b2b85dc](https://linux-hardware.org/?probe=e47b2b85dc) | Sep 24, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [719b20fd4e](https://linux-hardware.org/?probe=719b20fd4e) | Sep 24, 2022 |
| Huanan        | X99-TF                      | [1361d73bcd](https://linux-hardware.org/?probe=1361d73bcd) | Sep 22, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [1faf714086](https://linux-hardware.org/?probe=1faf714086) | Sep 21, 2022 |
| Minix         | NEO G41V-4 Max              | [a1640603ca](https://linux-hardware.org/?probe=a1640603ca) | Sep 20, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [6c7d6ef178](https://linux-hardware.org/?probe=6c7d6ef178) | Sep 20, 2022 |
| Dell          | 040DDP A01                  | [635c6895e1](https://linux-hardware.org/?probe=635c6895e1) | Sep 20, 2022 |
| Intel         | X99 V1.0                    | [02bfe94d24](https://linux-hardware.org/?probe=02bfe94d24) | Sep 19, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [25d7dc8f0d](https://linux-hardware.org/?probe=25d7dc8f0d) | Sep 19, 2022 |
| Gigabyte      | A320M-H-CF                  | [a3e30957c7](https://linux-hardware.org/?probe=a3e30957c7) | Sep 19, 2022 |
| HP            | 212B                        | [c823e0060e](https://linux-hardware.org/?probe=c823e0060e) | Sep 19, 2022 |
| MSI           | B250M PRO-VDH               | [b0836f0c26](https://linux-hardware.org/?probe=b0836f0c26) | Sep 19, 2022 |
| ASRock        | X399 Phantom Gaming 6       | [a28b408f4a](https://linux-hardware.org/?probe=a28b408f4a) | Sep 19, 2022 |
| MSI           | B250M PRO-VDH               | [3b6b90fee6](https://linux-hardware.org/?probe=3b6b90fee6) | Sep 18, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [d11c4e27df](https://linux-hardware.org/?probe=d11c4e27df) | Sep 18, 2022 |
| Intel         | X99 V1.0                    | [735c794db9](https://linux-hardware.org/?probe=735c794db9) | Sep 17, 2022 |
| Foxconn       | 2ADA                        | [b136916fb3](https://linux-hardware.org/?probe=b136916fb3) | Sep 16, 2022 |
| BESSTAR Te... | UM700                       | [f6ccaeed5e](https://linux-hardware.org/?probe=f6ccaeed5e) | Sep 16, 2022 |
| ASRock        | B450M Pro4                  | [19a46a2f8e](https://linux-hardware.org/?probe=19a46a2f8e) | Sep 16, 2022 |
| ASUSTek       | PRIME H410M-E               | [91f1fdc978](https://linux-hardware.org/?probe=91f1fdc978) | Sep 14, 2022 |
| Exo           | H310CH5-M2                  | [9154b5149b](https://linux-hardware.org/?probe=9154b5149b) | Sep 14, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [4a436fb179](https://linux-hardware.org/?probe=4a436fb179) | Sep 14, 2022 |
| ASUSTek       | X99-DELUXE II               | [8c9013ec12](https://linux-hardware.org/?probe=8c9013ec12) | Sep 13, 2022 |
| Dell          | 04YP6J A00                  | [ef4ae2baac](https://linux-hardware.org/?probe=ef4ae2baac) | Sep 13, 2022 |
| Gigabyte      | H77M-D3H                    | [3767b84078](https://linux-hardware.org/?probe=3767b84078) | Sep 12, 2022 |
| Foxconn       | 2ADA                        | [1b43b0d291](https://linux-hardware.org/?probe=1b43b0d291) | Sep 11, 2022 |
| MSI           | B350M BAZOOKA               | [ff7d2e74a5](https://linux-hardware.org/?probe=ff7d2e74a5) | Sep 11, 2022 |
| ASRock        | J3160DC-ITX                 | [e854b82ab9](https://linux-hardware.org/?probe=e854b82ab9) | Sep 10, 2022 |
| Gigabyte      | B450M DS3H-CF               | [6248f4732d](https://linux-hardware.org/?probe=6248f4732d) | Sep 10, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [70f5e3d77c](https://linux-hardware.org/?probe=70f5e3d77c) | Sep 08, 2022 |
| HP            | 3397                        | [0ebeef29bf](https://linux-hardware.org/?probe=0ebeef29bf) | Sep 07, 2022 |
| Intel         | Unknown                     | [2758407d23](https://linux-hardware.org/?probe=2758407d23) | Sep 07, 2022 |
| ASUSTek       | PRIME B360-PLUS             | [d35810173c](https://linux-hardware.org/?probe=d35810173c) | Sep 07, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [038f57c2d8](https://linux-hardware.org/?probe=038f57c2d8) | Sep 06, 2022 |
| MSI           | Z87-G41 PC Mate             | [775e007fc8](https://linux-hardware.org/?probe=775e007fc8) | Sep 05, 2022 |
| Intel         | B75                         | [eca0b46101](https://linux-hardware.org/?probe=eca0b46101) | Sep 05, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [43267285d4](https://linux-hardware.org/?probe=43267285d4) | Sep 04, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [518aa50eb0](https://linux-hardware.org/?probe=518aa50eb0) | Sep 04, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [4a27f8b033](https://linux-hardware.org/?probe=4a27f8b033) | Sep 04, 2022 |
| HP            | 8054                        | [878115f808](https://linux-hardware.org/?probe=878115f808) | Sep 04, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [65562b09e0](https://linux-hardware.org/?probe=65562b09e0) | Sep 03, 2022 |
| BESSTAR Te... | UM700                       | [f1198508de](https://linux-hardware.org/?probe=f1198508de) | Sep 03, 2022 |
| Dell          | 07PR60 A01                  | [d37a4374eb](https://linux-hardware.org/?probe=d37a4374eb) | Sep 02, 2022 |
| ASUSTek       | P6X58D-E                    | [cf774b3e03](https://linux-hardware.org/?probe=cf774b3e03) | Sep 02, 2022 |
| HP            | 8054                        | [1586ce33d1](https://linux-hardware.org/?probe=1586ce33d1) | Sep 02, 2022 |
| ASRock        | N68-S                       | [df5d34428a](https://linux-hardware.org/?probe=df5d34428a) | Sep 01, 2022 |
| ASUSTek       | M5A78L-M LX3                | [5ba264dfb2](https://linux-hardware.org/?probe=5ba264dfb2) | Sep 01, 2022 |
| ASUSTek       | M5A78L-M LX3                | [169c9af937](https://linux-hardware.org/?probe=169c9af937) | Sep 01, 2022 |
| Lenovo        | SHARKBAY NO DPK             | [f872d36cd5](https://linux-hardware.org/?probe=f872d36cd5) | Sep 01, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | [37695eb7e5](https://linux-hardware.org/?probe=37695eb7e5) | Aug 31, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d816d2ade0](https://linux-hardware.org/?probe=d816d2ade0) | Aug 30, 2022 |
| ASRock        | N68-S                       | [6aabf89438](https://linux-hardware.org/?probe=6aabf89438) | Aug 30, 2022 |
| ASUSTek       | PRIME Z590-P                | [e05dcd4a08](https://linux-hardware.org/?probe=e05dcd4a08) | Aug 29, 2022 |
| ASRock        | FM2A58M-VG3+ R2.0           | [422af9d6b5](https://linux-hardware.org/?probe=422af9d6b5) | Aug 29, 2022 |
| ASRock        | N68-S                       | [4fff0a6104](https://linux-hardware.org/?probe=4fff0a6104) | Aug 29, 2022 |
| ASUSTek       | ProArt B550-CREATOR         | [ec9f8ea30e](https://linux-hardware.org/?probe=ec9f8ea30e) | Aug 28, 2022 |
| ASRock        | B550M Pro4                  | [8c6b85a46c](https://linux-hardware.org/?probe=8c6b85a46c) | Aug 27, 2022 |
| ASRock        | B450M Pro4                  | [f4fe5fd168](https://linux-hardware.org/?probe=f4fe5fd168) | Aug 27, 2022 |
| Gigabyte      | B550 GAMING X V2            | [94e2f7cedc](https://linux-hardware.org/?probe=94e2f7cedc) | Aug 27, 2022 |
| Dell          | 0KWVT8 A02                  | [3f9c00b0da](https://linux-hardware.org/?probe=3f9c00b0da) | Aug 27, 2022 |
| ASRock        | X99 WS                      | [d16d59fab2](https://linux-hardware.org/?probe=d16d59fab2) | Aug 26, 2022 |
| ASUSTek       | Z170-P                      | [0bd08aee88](https://linux-hardware.org/?probe=0bd08aee88) | Aug 24, 2022 |
| Gigabyte      | B550M S2H                   | [8b5fe2494e](https://linux-hardware.org/?probe=8b5fe2494e) | Aug 23, 2022 |
| ASUSTek       | PRIME B450M-A               | [bfdd1ab294](https://linux-hardware.org/?probe=bfdd1ab294) | Aug 23, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [0dbe2c5dfd](https://linux-hardware.org/?probe=0dbe2c5dfd) | Aug 22, 2022 |
| MACHINIST     | H81M-PRO S1 V2.0            | [12be75fa90](https://linux-hardware.org/?probe=12be75fa90) | Aug 21, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [3b799e56c6](https://linux-hardware.org/?probe=3b799e56c6) | Aug 21, 2022 |
| MSI           | P55-GD55                    | [89f2c92fa1](https://linux-hardware.org/?probe=89f2c92fa1) | Aug 21, 2022 |
| ASUSTek       | PRIME B365M-C               | [8ae386a7a0](https://linux-hardware.org/?probe=8ae386a7a0) | Aug 20, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [1d1f39fd1b](https://linux-hardware.org/?probe=1d1f39fd1b) | Aug 19, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [d59342b7a4](https://linux-hardware.org/?probe=d59342b7a4) | Aug 19, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [e61c3cee8a](https://linux-hardware.org/?probe=e61c3cee8a) | Aug 18, 2022 |
| ASRock        | B550M Pro4                  | [41b271c4e7](https://linux-hardware.org/?probe=41b271c4e7) | Aug 17, 2022 |
| Gigabyte      | H61M-S2P                    | [49aedf1cf8](https://linux-hardware.org/?probe=49aedf1cf8) | Aug 17, 2022 |
| Gigabyte      | B550M S2H                   | [e04617befa](https://linux-hardware.org/?probe=e04617befa) | Aug 17, 2022 |
| MSI           | Z87-G41 PC Mate             | [08e79a0a1c](https://linux-hardware.org/?probe=08e79a0a1c) | Aug 16, 2022 |
| MSI           | X470 GAMING PRO             | [52b08fd4ba](https://linux-hardware.org/?probe=52b08fd4ba) | Aug 16, 2022 |
| ASRock        | Z77 Extreme4                | [07e825ed5b](https://linux-hardware.org/?probe=07e825ed5b) | Aug 16, 2022 |
| VS Company    | H61H2                       | [a0b88242a4](https://linux-hardware.org/?probe=a0b88242a4) | Aug 16, 2022 |
| Gigabyte      | B450 AORUS M                | [bdf5ba285f](https://linux-hardware.org/?probe=bdf5ba285f) | Aug 15, 2022 |
| Gigabyte      | B550M S2H                   | [db7b7b3126](https://linux-hardware.org/?probe=db7b7b3126) | Aug 15, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | [2fb0eea98c](https://linux-hardware.org/?probe=2fb0eea98c) | Aug 15, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [76e185a2e5](https://linux-hardware.org/?probe=76e185a2e5) | Aug 15, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [59b6bdadd3](https://linux-hardware.org/?probe=59b6bdadd3) | Aug 14, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | [45ddbf814d](https://linux-hardware.org/?probe=45ddbf814d) | Aug 14, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [e63db5769a](https://linux-hardware.org/?probe=e63db5769a) | Aug 14, 2022 |
| ASRock        | 990FX Extreme3              | [646169ae62](https://linux-hardware.org/?probe=646169ae62) | Aug 14, 2022 |
| HP            | 82A2                        | [bc3d667d42](https://linux-hardware.org/?probe=bc3d667d42) | Aug 13, 2022 |
| MSI           | B350M PRO-VD PLUS           | [ba65d9b67e](https://linux-hardware.org/?probe=ba65d9b67e) | Aug 13, 2022 |
| MSI           | 970A SLI Krait Edition      | [a94fe940b1](https://linux-hardware.org/?probe=a94fe940b1) | Aug 13, 2022 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [41560e8e13](https://linux-hardware.org/?probe=41560e8e13) | Aug 12, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [f82761570b](https://linux-hardware.org/?probe=f82761570b) | Aug 12, 2022 |
| AZW           | U59                         | [344d4587f6](https://linux-hardware.org/?probe=344d4587f6) | Aug 12, 2022 |
| ASRock        | 990FX Extreme3              | [e3006f6ca1](https://linux-hardware.org/?probe=e3006f6ca1) | Aug 11, 2022 |
| ASUSTek       | Z87-PRO                     | [f8a688c41e](https://linux-hardware.org/?probe=f8a688c41e) | Aug 11, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [3219cc3946](https://linux-hardware.org/?probe=3219cc3946) | Aug 10, 2022 |
| HP            | 8053                        | [db80dc0ee1](https://linux-hardware.org/?probe=db80dc0ee1) | Aug 10, 2022 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | [48b0dfdee0](https://linux-hardware.org/?probe=48b0dfdee0) | Aug 10, 2022 |
| Unknown       | Unknown                     | [e4c7906333](https://linux-hardware.org/?probe=e4c7906333) | Aug 09, 2022 |
| Lenovo        | Bantry CRB NOK              | [fbeb21c99a](https://linux-hardware.org/?probe=fbeb21c99a) | Aug 09, 2022 |
| ASUSTek       | G10DK                       | [2401d4af44](https://linux-hardware.org/?probe=2401d4af44) | Aug 08, 2022 |
| MSI           | MAG B550M MORTAR            | [7cf010b820](https://linux-hardware.org/?probe=7cf010b820) | Aug 08, 2022 |
| ASRock        | B450 Pro4                   | [b87492e7c7](https://linux-hardware.org/?probe=b87492e7c7) | Aug 08, 2022 |
| Gigabyte      | B150M-D3H-CF                | [5235533a87](https://linux-hardware.org/?probe=5235533a87) | Aug 07, 2022 |
| MSI           | B550-A PRO                  | [a3aa8d0879](https://linux-hardware.org/?probe=a3aa8d0879) | Aug 05, 2022 |
| Dell          | 0XR1GT A00                  | [2e069ba5c2](https://linux-hardware.org/?probe=2e069ba5c2) | Aug 04, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [e963ce265b](https://linux-hardware.org/?probe=e963ce265b) | Aug 04, 2022 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [22b43d3149](https://linux-hardware.org/?probe=22b43d3149) | Aug 04, 2022 |
| ECS           | H61H2-MV                    | [6b2a77a281](https://linux-hardware.org/?probe=6b2a77a281) | Aug 02, 2022 |
| MSI           | B450 GAMING PRO CARBON M... | [5951f66289](https://linux-hardware.org/?probe=5951f66289) | Aug 02, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [30e0a23365](https://linux-hardware.org/?probe=30e0a23365) | Aug 01, 2022 |
| ASUSTek       | F2A55-M LK2                 | [97a5e9c390](https://linux-hardware.org/?probe=97a5e9c390) | Aug 01, 2022 |
| Dell          | 0D24M8 A00                  | [6367e245e6](https://linux-hardware.org/?probe=6367e245e6) | Jul 31, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [9ea9e6f737](https://linux-hardware.org/?probe=9ea9e6f737) | Jul 30, 2022 |
| MSI           | X470 GAMING PRO MAX         | [5651db0a63](https://linux-hardware.org/?probe=5651db0a63) | Jul 30, 2022 |
| ASRock        | H81M-VG4                    | [1fd9e0ca3a](https://linux-hardware.org/?probe=1fd9e0ca3a) | Jul 30, 2022 |
| ASRock        | H81M-VG4                    | [309df31c47](https://linux-hardware.org/?probe=309df31c47) | Jul 30, 2022 |
| ASUSTek       | PRIME Z590-P                | [fa38197b4d](https://linux-hardware.org/?probe=fa38197b4d) | Jul 29, 2022 |
| Lenovo        | 3133 SDK0J40675 WIN 3305... | [4434d4d78a](https://linux-hardware.org/?probe=4434d4d78a) | Jul 29, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [f666b16fde](https://linux-hardware.org/?probe=f666b16fde) | Jul 28, 2022 |
| Gigabyte      | H97-Gaming 3                | [90656d8ef4](https://linux-hardware.org/?probe=90656d8ef4) | Jul 27, 2022 |
| Lenovo        | 3717 SDK0J40697 WIN 3305... | [701f519b4c](https://linux-hardware.org/?probe=701f519b4c) | Jul 27, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [b41540a078](https://linux-hardware.org/?probe=b41540a078) | Jul 26, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [331a99ef9a](https://linux-hardware.org/?probe=331a99ef9a) | Jul 26, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [1f3433b9e1](https://linux-hardware.org/?probe=1f3433b9e1) | Jul 26, 2022 |
| Gigabyte      | 990XA-UD3                   | [803bd277e7](https://linux-hardware.org/?probe=803bd277e7) | Jul 26, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [0c310749f1](https://linux-hardware.org/?probe=0c310749f1) | Jul 26, 2022 |
| Gigabyte      | H61M-D2P-B3                 | [8f0769b485](https://linux-hardware.org/?probe=8f0769b485) | Jul 25, 2022 |
| Gigabyte      | Z68P-DS3                    | [b03f1fee53](https://linux-hardware.org/?probe=b03f1fee53) | Jul 24, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [e512b2f9f2](https://linux-hardware.org/?probe=e512b2f9f2) | Jul 23, 2022 |
| Dell          | 0GM819                      | [8c617c1c3f](https://linux-hardware.org/?probe=8c617c1c3f) | Jul 23, 2022 |
| BESSTAR Te... | HM90                        | [cb4da5b649](https://linux-hardware.org/?probe=cb4da5b649) | Jul 23, 2022 |
| MSI           | B450M PRO-VDH MAX           | [9002ca2e54](https://linux-hardware.org/?probe=9002ca2e54) | Jul 23, 2022 |
| ASUSTek       | Maximus Formula             | [2e71fca3d5](https://linux-hardware.org/?probe=2e71fca3d5) | Jul 22, 2022 |
| BESSTAR Te... | HM90                        | [380230bbf6](https://linux-hardware.org/?probe=380230bbf6) | Jul 22, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [51c2b5bc3b](https://linux-hardware.org/?probe=51c2b5bc3b) | Jul 22, 2022 |
| MACHINIST     | X79 V2.82H                  | [da4a098248](https://linux-hardware.org/?probe=da4a098248) | Jul 22, 2022 |
| MACHINIST     | X79 V2.82H                  | [0e06f3fdf5](https://linux-hardware.org/?probe=0e06f3fdf5) | Jul 22, 2022 |
| ASUSTek       | P9X79                       | [5ff04691ce](https://linux-hardware.org/?probe=5ff04691ce) | Jul 21, 2022 |
| ASUSTek       | P9X79                       | [1bcee43b6e](https://linux-hardware.org/?probe=1bcee43b6e) | Jul 21, 2022 |
| ASRock        | Z77 Extreme4                | [492529f973](https://linux-hardware.org/?probe=492529f973) | Jul 21, 2022 |
| PCWare        | IPMH81G1                    | [cb66716a63](https://linux-hardware.org/?probe=cb66716a63) | Jul 21, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [1a28383fee](https://linux-hardware.org/?probe=1a28383fee) | Jul 19, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [63489ff6e5](https://linux-hardware.org/?probe=63489ff6e5) | Jul 19, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [fd46c32d92](https://linux-hardware.org/?probe=fd46c32d92) | Jul 19, 2022 |
| ASUSTek       | Maximus Formula             | [3c600cafa6](https://linux-hardware.org/?probe=3c600cafa6) | Jul 17, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [b28f8248b4](https://linux-hardware.org/?probe=b28f8248b4) | Jul 17, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [84d62872f5](https://linux-hardware.org/?probe=84d62872f5) | Jul 17, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [3b1f082065](https://linux-hardware.org/?probe=3b1f082065) | Jul 16, 2022 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [3605f29c73](https://linux-hardware.org/?probe=3605f29c73) | Jul 16, 2022 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [533392d790](https://linux-hardware.org/?probe=533392d790) | Jul 16, 2022 |
| Gigabyte      | A520M S2H                   | [dfc64d417f](https://linux-hardware.org/?probe=dfc64d417f) | Jul 15, 2022 |
| ASUSTek       | M5A97 R2.0                  | [06992e615b](https://linux-hardware.org/?probe=06992e615b) | Jul 15, 2022 |
| BESSTAR Te... | TL50                        | [c77ff65710](https://linux-hardware.org/?probe=c77ff65710) | Jul 15, 2022 |
| ASRock        | B550M Pro4                  | [dcdc04db9f](https://linux-hardware.org/?probe=dcdc04db9f) | Jul 14, 2022 |
| Gigabyte      | Z97-D3H-CF                  | [55f956b817](https://linux-hardware.org/?probe=55f956b817) | Jul 14, 2022 |
| MSI           | A320M-A PRO MAX             | [31127e76f8](https://linux-hardware.org/?probe=31127e76f8) | Jul 14, 2022 |
| MSI           | X470 GAMING PRO             | [716dd72eeb](https://linux-hardware.org/?probe=716dd72eeb) | Jul 13, 2022 |
| ASUSTek       | Maximus Formula             | [cd81bcaf19](https://linux-hardware.org/?probe=cd81bcaf19) | Jul 13, 2022 |
| MSI           | A320M-A PRO MAX             | [ed83060c1a](https://linux-hardware.org/?probe=ed83060c1a) | Jul 13, 2022 |
| ASUSTek       | M5A97 R2.0                  | [8bdaa5b844](https://linux-hardware.org/?probe=8bdaa5b844) | Jul 13, 2022 |
| BESSTAR Te... | UM350                       | [7437e30da5](https://linux-hardware.org/?probe=7437e30da5) | Jul 11, 2022 |
| MSI           | Z77A-G45                    | [ff2bae4518](https://linux-hardware.org/?probe=ff2bae4518) | Jul 11, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [5c8deeb62c](https://linux-hardware.org/?probe=5c8deeb62c) | Jul 10, 2022 |
| MSI           | H110M PRO-VH PLUS           | [02cbc3a4ae](https://linux-hardware.org/?probe=02cbc3a4ae) | Jul 10, 2022 |
| MSI           | Z77A-G45                    | [2d4a011972](https://linux-hardware.org/?probe=2d4a011972) | Jul 10, 2022 |
| Gigabyte      | B365M DS3H                  | [8c2d8a89d0](https://linux-hardware.org/?probe=8c2d8a89d0) | Jul 10, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [5dc09a66d8](https://linux-hardware.org/?probe=5dc09a66d8) | Jul 08, 2022 |
| ASUSTek       | M5A97 R2.0                  | [b46404cc89](https://linux-hardware.org/?probe=b46404cc89) | Jul 07, 2022 |
| Dell          | 0NK5PH A00                  | [6e17948aa5](https://linux-hardware.org/?probe=6e17948aa5) | Jul 07, 2022 |
| Dell          | 0NK5PH A00                  | [56b772ade4](https://linux-hardware.org/?probe=56b772ade4) | Jul 07, 2022 |
| ASRock        | B450M Pro4 R2.0             | [d9dc513be7](https://linux-hardware.org/?probe=d9dc513be7) | Jul 06, 2022 |
| Fujitsu       | D2981-A1 S26361-D2981-A1    | [5e40d26a2b](https://linux-hardware.org/?probe=5e40d26a2b) | Jul 06, 2022 |
| Inventec      | D CLASS A02                 | [ac1652fd54](https://linux-hardware.org/?probe=ac1652fd54) | Jul 06, 2022 |
| ASUSTek       | PRIME B550M-A               | [a5e8e3a046](https://linux-hardware.org/?probe=a5e8e3a046) | Jul 05, 2022 |
| ASRock        | B550M Pro4                  | [39803eaf94](https://linux-hardware.org/?probe=39803eaf94) | Jul 04, 2022 |
| ASRock        | B550M Pro4                  | [747051c1fc](https://linux-hardware.org/?probe=747051c1fc) | Jul 04, 2022 |
| MSI           | B250M PRO-VDH               | [fb76db49bd](https://linux-hardware.org/?probe=fb76db49bd) | Jul 04, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [327086a8b8](https://linux-hardware.org/?probe=327086a8b8) | Jul 04, 2022 |
| ASRock        | IMB-1213                    | [6e1ba0ba69](https://linux-hardware.org/?probe=6e1ba0ba69) | Jul 04, 2022 |
| HP            | 0A9Ch                       | [3dafdd1a3f](https://linux-hardware.org/?probe=3dafdd1a3f) | Jul 03, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [6918411ee2](https://linux-hardware.org/?probe=6918411ee2) | Jul 03, 2022 |
| ASUSTek       | PRIME A320M-K               | [a381b573f6](https://linux-hardware.org/?probe=a381b573f6) | Jul 03, 2022 |
| ASUSTek       | PRIME X570-P                | [1a729c627d](https://linux-hardware.org/?probe=1a729c627d) | Jul 03, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [c633887935](https://linux-hardware.org/?probe=c633887935) | Jul 02, 2022 |
| MSI           | X370 GAMING PRO CARBON      | [5763cb4576](https://linux-hardware.org/?probe=5763cb4576) | Jul 01, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [21dd020507](https://linux-hardware.org/?probe=21dd020507) | Jul 01, 2022 |
| MSI           | PRESTIGE X570 CREATION      | [7f17faf180](https://linux-hardware.org/?probe=7f17faf180) | Jun 30, 2022 |
| HP            | 0B54h D                     | [bef89f554e](https://linux-hardware.org/?probe=bef89f554e) | Jun 30, 2022 |
| Gigabyte      | B450M DS3H-CF               | [6a2f1d22f1](https://linux-hardware.org/?probe=6a2f1d22f1) | Jun 29, 2022 |
| Gigabyte      | B450M DS3H-CF               | [0a976062da](https://linux-hardware.org/?probe=0a976062da) | Jun 29, 2022 |
| ASRock        | H61M-ITX                    | [e8d5e4ff14](https://linux-hardware.org/?probe=e8d5e4ff14) | Jun 29, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Manjaro/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Manjaro           | 1195     | 41.97%  |
| Manjaro 20.1      | 135      | 4.74%   |
| Manjaro 20.2.1    | 108      | 3.79%   |
| Manjaro 22.0.0    | 102      | 3.58%   |
| Manjaro 20.2      | 89       | 3.13%   |
| Manjaro 20.0.3    | 81       | 2.85%   |
| Manjaro 18.1.5    | 56       | 1.97%   |
| Manjaro 21.2.6    | 53       | 1.86%   |
| Manjaro 21.2.5    | 53       | 1.86%   |
| Manjaro 21.1.0    | 53       | 1.86%   |
| Manjaro 18.0.4    | 46       | 1.62%   |
| Manjaro 21.2.0    | 45       | 1.58%   |
| Manjaro 20.0      | 45       | 1.58%   |
| Manjaro 23.0.0    | 39       | 1.37%   |
| Manjaro 21.1.6    | 38       | 1.33%   |
| Manjaro 21.0.7    | 36       | 1.26%   |
| Manjaro 21.0.5    | 35       | 1.23%   |
| Manjaro 21.0      | 35       | 1.23%   |
| Manjaro 19.0.2    | 31       | 1.09%   |
| Manjaro 20.1.2    | 29       | 1.02%   |
| Manjaro 20.0.1    | 29       | 1.02%   |
| Manjaro 21.2.3    | 27       | 0.95%   |
| Manjaro 22.1.0    | 25       | 0.88%   |
| Manjaro 20.1.1    | 24       | 0.84%   |
| Manjaro 21.2.1    | 23       | 0.81%   |
| Manjaro 21.3.7    | 20       | 0.7%    |
| Manjaro 21.3.6    | 18       | 0.63%   |
| Manjaro 22.0.4    | 16       | 0.56%   |
| Manjaro 21.0.4    | 16       | 0.56%   |
| Manjaro 21.0.1    | 14       | 0.49%   |
| Manjaro 21.0.2    | 13       | 0.46%   |
| Manjaro 22.1.1    | 12       | 0.42%   |
| Manjaro 21.2rc    | 12       | 0.42%   |
| Manjaro 21.2.4    | 12       | 0.42%   |
| Manjaro 21.1.2    | 12       | 0.42%   |
| Manjaro 21.0.3    | 12       | 0.42%   |
| Manjaro 18.0.0-rc | 12       | 0.42%   |
| Manjaro 22.0      | 11       | 0.39%   |
| Manjaro 21.3.1    | 11       | 0.39%   |
| Manjaro 21.1.5    | 11       | 0.39%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Manjaro | 2614     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.9.16-1-MANJARO  | 115      | 3.62%   |
| 5.8.6-1-MANJARO   | 68       | 2.14%   |
| 5.13.19-2-MANJARO | 66       | 2.07%   |
| 5.15.28-1-MANJARO | 49       | 1.54%   |
| 5.9.11-3-MANJARO  | 48       | 1.51%   |
| 5.8.11-1-MANJARO  | 46       | 1.45%   |
| 5.10.42-1-MANJARO | 40       | 1.26%   |
| 6.1.1-1-MANJARO   | 38       | 1.19%   |
| 5.8.18-1-MANJARO  | 38       | 1.19%   |
| 6.1.12-1-MANJARO  | 32       | 1.01%   |
| 5.15.32-1-MANJARO | 32       | 1.01%   |
| 6.1.31-2-MANJARO  | 31       | 0.97%   |
| 5.6.16-1-MANJARO  | 31       | 0.97%   |
| 5.15.60-1-MANJARO | 30       | 0.94%   |
| 5.10.36-2-MANJARO | 30       | 0.94%   |
| 5.7.9-1-MANJARO   | 29       | 0.91%   |
| 5.15.12-1-MANJARO | 29       | 0.91%   |
| 5.8.3-2-MANJARO   | 25       | 0.79%   |
| 5.8.16-2-MANJARO  | 25       | 0.79%   |
| 5.6.19-2-MANJARO  | 24       | 0.75%   |
| 5.6.15-1-MANJARO  | 24       | 0.75%   |
| 5.17.1-3-MANJARO  | 24       | 0.75%   |
| 5.7.0-3-MANJARO   | 23       | 0.72%   |
| 5.10.2-2-MANJARO  | 23       | 0.72%   |
| 5.6.7-1-MANJARO   | 22       | 0.69%   |
| 5.6.12-1-MANJARO  | 22       | 0.69%   |
| 5.16.14-1-MANJARO | 22       | 0.69%   |
| 5.15.2-2-MANJARO  | 22       | 0.69%   |
| 5.10.23-1-MANJARO | 22       | 0.69%   |
| 5.9.1-1-MANJARO   | 21       | 0.66%   |
| 5.11.6-1-MANJARO  | 21       | 0.66%   |
| 5.4.15-2-MANJARO  | 20       | 0.63%   |
| 5.7.17-2-MANJARO  | 19       | 0.6%    |
| 5.4.6-2-MANJARO   | 19       | 0.6%    |
| 5.10.7-3-MANJARO  | 19       | 0.6%    |
| 5.10.15-1-MANJARO | 19       | 0.6%    |
| 5.14.10-1-MANJARO | 17       | 0.53%   |
| 5.11.2-1-MANJARO  | 17       | 0.53%   |
| 5.10.53-1-MANJARO | 17       | 0.53%   |
| 5.9.3-1-MANJARO   | 16       | 0.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.9.16  | 115      | 3.62%   |
| 5.8.6   | 68       | 2.14%   |
| 5.13.19 | 66       | 2.08%   |
| 5.9.11  | 51       | 1.6%    |
| 5.15.28 | 49       | 1.54%   |
| 5.8.11  | 47       | 1.48%   |
| 5.10.42 | 40       | 1.26%   |
| 6.1.1   | 38       | 1.2%    |
| 5.8.18  | 38       | 1.2%    |
| 6.1.31  | 32       | 1.01%   |
| 6.1.12  | 32       | 1.01%   |
| 5.15.32 | 32       | 1.01%   |
| 5.6.16  | 31       | 0.98%   |
| 5.15.60 | 30       | 0.94%   |
| 5.10.36 | 30       | 0.94%   |
| 5.7.9   | 29       | 0.91%   |
| 5.7.0   | 29       | 0.91%   |
| 5.17.1  | 29       | 0.91%   |
| 5.15.12 | 29       | 0.91%   |
| 5.9.1   | 28       | 0.88%   |
| 5.6.19  | 27       | 0.85%   |
| 5.8.3   | 26       | 0.82%   |
| 5.8.16  | 25       | 0.79%   |
| 5.6.15  | 24       | 0.75%   |
| 5.6.12  | 23       | 0.72%   |
| 5.15.2  | 23       | 0.72%   |
| 5.10.2  | 23       | 0.72%   |
| 5.6.7   | 22       | 0.69%   |
| 5.16.14 | 22       | 0.69%   |
| 5.10.23 | 22       | 0.69%   |
| 5.11.6  | 21       | 0.66%   |
| 5.7.17  | 20       | 0.63%   |
| 5.4.15  | 20       | 0.63%   |
| 5.10.7  | 20       | 0.63%   |
| 5.4.6   | 19       | 0.6%    |
| 5.10.15 | 19       | 0.6%    |
| 5.15.7  | 17       | 0.53%   |
| 5.14.10 | 17       | 0.53%   |
| 5.14.0  | 17       | 0.53%   |
| 5.11.2  | 17       | 0.53%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 447      | 15.06%  |
| 5.10    | 362      | 12.2%   |
| 5.4     | 253      | 8.52%   |
| 5.9     | 230      | 7.75%   |
| 5.8     | 228      | 7.68%   |
| 6.1     | 224      | 7.55%   |
| 5.6     | 172      | 5.8%    |
| 5.13    | 126      | 4.25%   |
| 5.7     | 109      | 3.67%   |
| 5.11    | 91       | 3.07%   |
| 4.19    | 66       | 2.22%   |
| 5.17    | 64       | 2.16%   |
| 5.16    | 64       | 2.16%   |
| 6.0     | 61       | 2.06%   |
| 5.14    | 61       | 2.06%   |
| 5.18    | 55       | 1.85%   |
| 5.19    | 53       | 1.79%   |
| 5.12    | 49       | 1.65%   |
| 5.5     | 39       | 1.31%   |
| 6.3     | 38       | 1.28%   |
| 6.2     | 37       | 1.25%   |
| 4.14    | 33       | 1.11%   |
| 5.3     | 23       | 0.77%   |
| 6.4     | 19       | 0.64%   |
| 5.2     | 17       | 0.57%   |
| 5.1     | 13       | 0.44%   |
| 5.0     | 11       | 0.37%   |
| 4.20    | 5        | 0.17%   |
| 4.18    | 5        | 0.17%   |
| 4.17    | 3        | 0.1%    |
| 4.16    | 3        | 0.1%    |
| 4.9     | 2        | 0.07%   |
| 4.7     | 2        | 0.07%   |
| 4.4     | 2        | 0.07%   |
| 6.5     | 1        | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 2614     | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| KDE5                     | 1048     | 38.33%  |
| XFCE                     | 579      | 21.18%  |
| GNOME                    | 514      | 18.8%   |
| KDE                      | 247      | 9.03%   |
| Unknown                  | 106      | 3.88%   |
| X-Cinnamon               | 83       | 3.04%   |
| i3                       | 46       | 1.68%   |
| MATE                     | 23       | 0.84%   |
| Cinnamon                 | 22       | 0.8%    |
| Deepin                   | 21       | 0.77%   |
| Budgie                   | 14       | 0.51%   |
| LXQt                     | 8        | 0.29%   |
| awesome                  | 5        | 0.18%   |
| sway                     | 4        | 0.15%   |
| bspwm                    | 3        | 0.11%   |
| ICEWM                    | 2        | 0.07%   |
| GNOME Classic            | 2        | 0.07%   |
| Yaru:ubuntu:GNOME        | 1        | 0.04%   |
| qtile                    | 1        | 0.04%   |
| openbox                  | 1        | 0.04%   |
| LXDE                     | 1        | 0.04%   |
| Enlightenment            | 1        | 0.04%   |
| DWM                      | 1        | 0.04%   |
| /usr/bin/openbox-session | 1        | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 2376     | 89.22%  |
| Wayland | 218      | 8.19%   |
| Unknown | 42       | 1.58%   |
| Tty     | 27       | 1.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1190     | 44.12%  |
| SDDM    | 671      | 24.88%  |
| LightDM | 446      | 16.54%  |
| GDM     | 289      | 10.72%  |
| TDM     | 89       | 3.3%    |
| LXDM    | 5        | 0.19%   |
| GREETD  | 3        | 0.11%   |
| SLiM    | 2        | 0.07%   |
| XDM     | 1        | 0.04%   |
| LYNDE   | 1        | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 1054     | 39.68%  |
| de_DE   | 233      | 8.77%   |
| ru_RU   | 199      | 7.49%   |
| en_GB   | 165      | 6.21%   |
| Unknown | 156      | 5.87%   |
| pt_BR   | 114      | 4.29%   |
| fr_FR   | 76       | 2.86%   |
| en_CA   | 71       | 2.67%   |
| es_ES   | 64       | 2.41%   |
| it_IT   | 59       | 2.22%   |
| pl_PL   | 49       | 1.84%   |
| en_AU   | 39       | 1.47%   |
| nl_NL   | 21       | 0.79%   |
| en_IN   | 21       | 0.79%   |
| de_AT   | 21       | 0.79%   |
| ru_UA   | 18       | 0.68%   |
| es_AR   | 18       | 0.68%   |
| sv_SE   | 15       | 0.56%   |
| es_MX   | 15       | 0.56%   |
| zh_CN   | 14       | 0.53%   |
| fi_FI   | 13       | 0.49%   |
| fr_CA   | 11       | 0.41%   |
| en_IE   | 11       | 0.41%   |
| hu_HU   | 10       | 0.38%   |
| en_PH   | 10       | 0.38%   |
| en_ZA   | 9        | 0.34%   |
| da_DK   | 9        | 0.34%   |
| cs_CZ   | 9        | 0.34%   |
| en_NZ   | 8        | 0.3%    |
| pt_PT   | 7        | 0.26%   |
| es_CL   | 7        | 0.26%   |
| uk_UA   | 6        | 0.23%   |
| ja_JP   | 6        | 0.23%   |
| es_UY   | 6        | 0.23%   |
| en_IL   | 6        | 0.23%   |
| en_DK   | 6        | 0.23%   |
| de_CH   | 6        | 0.23%   |
| tr_TR   | 5        | 0.19%   |
| fr_BE   | 5        | 0.19%   |
| es_PE   | 5        | 0.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 1672     | 62.6%   |
| EFI  | 999      | 37.4%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 2204     | 82.73%  |
| Btrfs   | 286      | 10.74%  |
| Xfs     | 44       | 1.65%   |
| Unknown | 40       | 1.5%    |
| Overlay | 37       | 1.39%   |
| Tmpfs   | 30       | 1.13%   |
| F2fs    | 12       | 0.45%   |
| Zfs     | 4        | 0.15%   |
| Ext2    | 3        | 0.11%   |
| Ext3    | 2        | 0.08%   |
| XXXX    | 1        | 0.04%   |
| XXXfs   | 1        | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1287     | 47.99%  |
| GPT     | 1123     | 41.87%  |
| MBR     | 272      | 10.14%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 2210     | 82.77%  |
| Yes       | 460      | 17.23%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1692     | 63.39%  |
| Yes       | 977      | 36.61%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 770      | 29.46%  |
| Gigabyte Technology                  | 536      | 20.5%   |
| MSI                                  | 424      | 16.22%  |
| ASRock                               | 285      | 10.9%   |
| Dell                                 | 135      | 5.16%   |
| Hewlett-Packard                      | 129      | 4.93%   |
| Intel                                | 62       | 2.37%   |
| Lenovo                               | 54       | 2.07%   |
| Acer                                 | 27       | 1.03%   |
| Unknown                              | 23       | 0.88%   |
| Biostar                              | 20       | 0.77%   |
| Pegatron                             | 16       | 0.61%   |
| Huanan                               | 13       | 0.5%    |
| Foxconn                              | 11       | 0.42%   |
| Apple                                | 9        | 0.34%   |
| Medion                               | 8        | 0.31%   |
| Fujitsu                              | 8        | 0.31%   |
| ECS                                  | 7        | 0.27%   |
| Shuttle                              | 5        | 0.19%   |
| Positivo                             | 5        | 0.19%   |
| BESSTAR Tech                         | 5        | 0.19%   |
| AZW                                  | 5        | 0.19%   |
| Alienware                            | 4        | 0.15%   |
| PCWare                               | 3        | 0.11%   |
| ZOTAC                                | 2        | 0.08%   |
| Shenzhen Meigao Electronic Equipment | 2        | 0.08%   |
| OEM                                  | 2        | 0.08%   |
| Minix                                | 2        | 0.08%   |
| MACHINIST                            | 2        | 0.08%   |
| Inventec                             | 2        | 0.08%   |
| Google                               | 2        | 0.08%   |
| Gateway                              | 2        | 0.08%   |
| Fujitsu Siemens                      | 2        | 0.08%   |
| XFX                                  | 1        | 0.04%   |
| VS Company                           | 1        | 0.04%   |
| TPV-INVENTA                          | 1        | 0.04%   |
| SYWZ                                 | 1        | 0.04%   |
| System76                             | 1        | 0.04%   |
| Supermicro                           | 1        | 0.04%   |
| SiYW                                 | 1        | 0.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| ASUS All Series                  | 72       | 2.75%   |
| MSI MS-7C37                      | 32       | 1.22%   |
| MSI MS-7C02                      | 27       | 1.03%   |
| Gigabyte B450M DS3H              | 27       | 1.03%   |
| Unknown                          | 25       | 0.96%   |
| ASUS TUF Gaming X570-PLUS        | 24       | 0.92%   |
| MSI MS-7C91                      | 19       | 0.73%   |
| ASUS PRIME A320M-K               | 19       | 0.73%   |
| MSI MS-7B86                      | 17       | 0.65%   |
| ASRock B450M Pro4                | 16       | 0.61%   |
| MSI MS-7B79                      | 15       | 0.57%   |
| ASUS ROG STRIX B450-F GAMING     | 15       | 0.57%   |
| Gigabyte X570 AORUS ELITE        | 14       | 0.54%   |
| ASUS ROG STRIX B550-F GAMING     | 13       | 0.5%    |
| MSI MS-7A38                      | 12       | 0.46%   |
| Dell OptiPlex 9020               | 12       | 0.46%   |
| ASUS TUF Gaming B550M-PLUS       | 12       | 0.46%   |
| ASUS PRIME B450M-A               | 12       | 0.46%   |
| Gigabyte B450 AORUS M            | 11       | 0.42%   |
| Gigabyte 970A-DS3P               | 11       | 0.42%   |
| Dell OptiPlex 7010               | 11       | 0.42%   |
| ASUS PRIME B350-PLUS             | 11       | 0.42%   |
| MSI MS-7B89                      | 10       | 0.38%   |
| Gigabyte X570 AORUS MASTER       | 10       | 0.38%   |
| Gigabyte X470 AORUS ULTRA GAMING | 10       | 0.38%   |
| ASUS ROG STRIX X570-E GAMING     | 10       | 0.38%   |
| MSI MS-7817                      | 9        | 0.34%   |
| MSI MS-7693                      | 9        | 0.34%   |
| Gigabyte B450 AORUS ELITE        | 9        | 0.34%   |
| ASUS ROG CROSSHAIR VIII HERO     | 9        | 0.34%   |
| ASUS PRIME X470-PRO              | 9        | 0.34%   |
| ASUS PRIME B450-PLUS             | 9        | 0.34%   |
| MSI MS-7C94                      | 8        | 0.31%   |
| MSI MS-7A34                      | 8        | 0.31%   |
| ASUS PRIME X570-P                | 8        | 0.31%   |
| ASUS PRIME X370-PRO              | 8        | 0.31%   |
| ASUS PRIME B350M-A               | 8        | 0.31%   |
| ASRock B450M Steel Legend        | 8        | 0.31%   |
| ASRock B450 Pro4                 | 8        | 0.31%   |
| MSI MS-7C84                      | 7        | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ASUS PRIME            | 165      | 6.31%   |
| ASUS ROG              | 151      | 5.78%   |
| Dell OptiPlex         | 84       | 3.21%   |
| ASUS TUF              | 84       | 3.21%   |
| ASUS All              | 72       | 2.75%   |
| Gigabyte X570         | 49       | 1.87%   |
| Gigabyte B450M        | 44       | 1.68%   |
| HP Compaq             | 37       | 1.42%   |
| Gigabyte B450         | 35       | 1.34%   |
| MSI MS-7C37           | 32       | 1.22%   |
| MSI MS-7C02           | 27       | 1.03%   |
| ASRock B450M          | 26       | 0.99%   |
| Lenovo ThinkCentre    | 25       | 0.96%   |
| Unknown               | 25       | 0.96%   |
| HP EliteDesk          | 22       | 0.84%   |
| Dell Precision        | 22       | 0.84%   |
| Gigabyte B550         | 21       | 0.8%    |
| ASRock X570           | 20       | 0.77%   |
| MSI MS-7C91           | 19       | 0.73%   |
| ASRock B450           | 19       | 0.73%   |
| MSI MS-7B86           | 17       | 0.65%   |
| ASUS M5A97            | 17       | 0.65%   |
| ASUS M5A78L-M         | 17       | 0.65%   |
| Acer Aspire           | 17       | 0.65%   |
| ASUS P8Z77-V          | 16       | 0.61%   |
| MSI MS-7B79           | 15       | 0.57%   |
| Gigabyte Z390         | 15       | 0.57%   |
| MSI MS-7A38           | 12       | 0.46%   |
| Gigabyte X470         | 12       | 0.46%   |
| Gigabyte 970A-DS3P    | 12       | 0.46%   |
| ASUS Maximus          | 12       | 0.46%   |
| Gigabyte B550M        | 11       | 0.42%   |
| ASUS P8H61-M          | 11       | 0.42%   |
| MSI MS-7B89           | 10       | 0.38%   |
| HP Pavilion           | 10       | 0.38%   |
| MSI MS-7817           | 9        | 0.34%   |
| MSI MS-7693           | 9        | 0.34%   |
| Lenovo ThinkStation   | 9        | 0.34%   |
| Gigabyte AB350-Gaming | 9        | 0.34%   |
| ASRock X470           | 9        | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 424      | 16.22%  |
| 2019    | 329      | 12.59%  |
| 2020    | 287      | 10.98%  |
| 2017    | 217      | 8.3%    |
| 2012    | 210      | 8.03%   |
| 2013    | 181      | 6.92%   |
| 2014    | 152      | 5.81%   |
| 2011    | 146      | 5.59%   |
| 2015    | 116      | 4.44%   |
| 2016    | 112      | 4.28%   |
| 2021    | 103      | 3.94%   |
| 2010    | 88       | 3.37%   |
| 2009    | 79       | 3.02%   |
| 2022    | 57       | 2.18%   |
| 2008    | 46       | 1.76%   |
| 2007    | 44       | 1.68%   |
| 2006    | 12       | 0.46%   |
| 2023    | 6        | 0.23%   |
| 2005    | 4        | 0.15%   |
| Unknown | 1        | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 2614     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 2612     | 99.89%  |
| Enabled  | 3        | 0.11%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2612     | 99.92%  |
| Yes  | 2        | 0.08%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 943      | 35.38%  |
| 32.01-64.0  | 562      | 21.09%  |
| 8.01-16.0   | 471      | 17.67%  |
| 4.01-8.0    | 252      | 9.46%   |
| 3.01-4.0    | 169      | 6.34%   |
| 64.01-256.0 | 138      | 5.18%   |
| 24.01-32.0  | 93       | 3.49%   |
| 1.01-2.0    | 30       | 1.13%   |
| 2.01-3.0    | 7        | 0.26%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 763      | 25.72%  |
| 2.01-3.0    | 662      | 22.32%  |
| 1.01-2.0    | 645      | 21.75%  |
| 3.01-4.0    | 486      | 16.39%  |
| 8.01-16.0   | 253      | 8.53%   |
| 0.51-1.0    | 74       | 2.49%   |
| 16.01-24.0  | 48       | 1.62%   |
| 24.01-32.0  | 14       | 0.47%   |
| 0.01-0.5    | 11       | 0.37%   |
| 32.01-64.0  | 9        | 0.3%    |
| 64.01-256.0 | 1        | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 825      | 30.02%  |
| 1      | 646      | 23.51%  |
| 3      | 555      | 20.2%   |
| 4      | 357      | 12.99%  |
| 5      | 203      | 7.39%   |
| 6      | 77       | 2.8%    |
| 7      | 36       | 1.31%   |
| 8      | 17       | 0.62%   |
| 0      | 11       | 0.4%    |
| 9      | 10       | 0.36%   |
| 11     | 5        | 0.18%   |
| 10     | 3        | 0.11%   |
| 12     | 2        | 0.07%   |
| 20     | 1        | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1757     | 66.25%  |
| Yes       | 895      | 33.75%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 2585     | 98.89%  |
| No        | 29       | 1.11%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1408     | 53.09%  |
| Yes       | 1244     | 46.91%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1555     | 58.48%  |
| Yes       | 1104     | 41.52%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 510      | 19.37%  |
| Germany      | 320      | 12.15%  |
| Russia       | 235      | 8.93%   |
| Brazil       | 159      | 6.04%   |
| Canada       | 107      | 4.06%   |
| France       | 100      | 3.8%    |
| Spain        | 85       | 3.23%   |
| UK           | 83       | 3.15%   |
| Italy        | 82       | 3.11%   |
| Poland       | 78       | 2.96%   |
| Ukraine      | 54       | 2.05%   |
| Netherlands  | 53       | 2.01%   |
| Sweden       | 45       | 1.71%   |
| Australia    | 41       | 1.56%   |
| Austria      | 38       | 1.44%   |
| Finland      | 31       | 1.18%   |
| Argentina    | 27       | 1.03%   |
| Belgium      | 26       | 0.99%   |
| Romania      | 25       | 0.95%   |
| Mexico       | 25       | 0.95%   |
| India        | 25       | 0.95%   |
| Greece       | 20       | 0.76%   |
| Switzerland  | 19       | 0.72%   |
| Norway       | 19       | 0.72%   |
| Hungary      | 19       | 0.72%   |
| Bulgaria     | 19       | 0.72%   |
| Portugal     | 18       | 0.68%   |
| Denmark      | 18       | 0.68%   |
| South Africa | 15       | 0.57%   |
| Czechia      | 14       | 0.53%   |
| China        | 14       | 0.53%   |
| Israel       | 13       | 0.49%   |
| Belarus      | 13       | 0.49%   |
| Turkey       | 12       | 0.46%   |
| Lithuania    | 11       | 0.42%   |
| Saudi Arabia | 10       | 0.38%   |
| Philippines  | 10       | 0.38%   |
| New Zealand  | 10       | 0.38%   |
| Ireland      | 10       | 0.38%   |
| Chile        | 9        | 0.34%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Moscow            | 55       | 1.98%   |
| St Petersburg     | 25       | 0.9%    |
| Warsaw            | 20       | 0.72%   |
| Berlin            | 19       | 0.68%   |
| Vienna            | 18       | 0.65%   |
| Kyiv              | 17       | 0.61%   |
| Toronto           | 15       | 0.54%   |
| Sao Paulo         | 15       | 0.54%   |
| Madrid            | 15       | 0.54%   |
| Athens            | 14       | 0.5%    |
| Amsterdam         | 14       | 0.5%    |
| Rome              | 13       | 0.47%   |
| Stockholm         | 12       | 0.43%   |
| Rio de Janeiro    | 12       | 0.43%   |
| Frankfurt am Main | 12       | 0.43%   |
| Sydney            | 11       | 0.4%    |
| Paris             | 11       | 0.4%    |
| Helsinki          | 11       | 0.4%    |
| Hamburg           | 11       | 0.4%    |
| Portland          | 10       | 0.36%   |
| Milan             | 10       | 0.36%   |
| Melbourne         | 10       | 0.36%   |
| Krakow            | 10       | 0.36%   |
| Bucharest         | 10       | 0.36%   |
| Barcelona         | 10       | 0.36%   |
| Stuttgart         | 9        | 0.32%   |
| Sofia             | 9        | 0.32%   |
| Montreal          | 9        | 0.32%   |
| Dallas            | 9        | 0.32%   |
| Copenhagen        | 9        | 0.32%   |
| Yekaterinburg     | 8        | 0.29%   |
| New York          | 8        | 0.29%   |
| Minsk             | 8        | 0.29%   |
| Miami             | 8        | 0.29%   |
| Indianapolis      | 8        | 0.29%   |
| Austin            | 8        | 0.29%   |
| Vilnius           | 7        | 0.25%   |
| Seattle           | 7        | 0.25%   |
| Oslo              | 7        | 0.25%   |
| Omsk              | 7        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 1015     | 1725   | 17.69%  |
| Seagate                     | 990      | 1611   | 17.25%  |
| Samsung Electronics         | 957      | 1700   | 16.68%  |
| Kingston                    | 358      | 509    | 6.24%   |
| Toshiba                     | 312      | 419    | 5.44%   |
| SanDisk                     | 297      | 407    | 5.18%   |
| Crucial                     | 294      | 449    | 5.12%   |
| Hitachi                     | 138      | 199    | 2.41%   |
| Intel                       | 116      | 157    | 2.02%   |
| A-DATA Technology           | 88       | 127    | 1.53%   |
| Phison                      | 84       | 112    | 1.46%   |
| HGST                        | 66       | 103    | 1.15%   |
| China                       | 57       | 83     | 0.99%   |
| Silicon Motion              | 52       | 72     | 0.91%   |
| Micron/Crucial Technology   | 45       | 55     | 0.78%   |
| PNY                         | 44       | 66     | 0.77%   |
| OCZ                         | 40       | 56     | 0.7%    |
| Unknown                     | 39       | 69     | 0.68%   |
| Phison Electronics          | 38       | 43     | 0.66%   |
| SPCC                        | 37       | 44     | 0.64%   |
| Patriot                     | 35       | 44     | 0.61%   |
| Intenso                     | 35       | 51     | 0.61%   |
| SK hynix                    | 33       | 37     | 0.58%   |
| XPG                         | 32       | 36     | 0.56%   |
| Corsair                     | 27       | 38     | 0.47%   |
| Micron Technology           | 26       | 33     | 0.45%   |
| Transcend                   | 23       | 23     | 0.4%    |
| Realtek Semiconductor       | 23       | 29     | 0.4%    |
| Team                        | 22       | 28     | 0.38%   |
| Plextor                     | 21       | 25     | 0.37%   |
| JMicron Technology          | 21       | 27     | 0.37%   |
| GOODRAM                     | 21       | 27     | 0.37%   |
| Lexar                       | 19       | 22     | 0.33%   |
| Kingston Technology Company | 16       | 18     | 0.28%   |
| Apacer                      | 15       | 17     | 0.26%   |
| Maxtor                      | 13       | 15     | 0.23%   |
| Gigabyte Technology         | 13       | 23     | 0.23%   |
| ADATA Technology            | 13       | 17     | 0.23%   |
| Hewlett-Packard             | 11       | 15     | 0.19%   |
| ASMT                        | 11       | 18     | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung SSD 860 EVO 500GB                           | 90       | 1.31%   |
| Kingston SA400S37240G 240GB SSD                     | 90       | 1.31%   |
| Seagate ST1000DM010-2EP102 1TB                      | 81       | 1.18%   |
| Seagate ST2000DM008-2FR102 2TB                      | 76       | 1.11%   |
| Samsung SSD 850 EVO 500GB                           | 69       | 1.01%   |
| Samsung SSD 850 EVO 250GB                           | 64       | 0.93%   |
| Samsung NVMe SSD Drive 500GB                        | 63       | 0.92%   |
| Toshiba DT01ACA100 1TB                              | 59       | 0.86%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 58       | 0.85%   |
| Kingston SA400S37120G 120GB SSD                     | 55       | 0.8%    |
| Crucial CT500MX500SSD1 500GB                        | 52       | 0.76%   |
| Samsung SSD 860 EVO 1TB                             | 50       | 0.73%   |
| Samsung NVMe SSD Drive 1TB                          | 49       | 0.72%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 46       | 0.67%   |
| Seagate ST500DM002-1BD142 500GB                     | 44       | 0.64%   |
| Crucial CT1000MX500SSD1 1TB                         | 43       | 0.63%   |
| Seagate ST2000DM006-2DM164 2TB                      | 42       | 0.61%   |
| Seagate ST1000DM003-1ER162 1TB                      | 41       | 0.6%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 41       | 0.6%    |
| Samsung SSD 860 EVO 250GB                           | 40       | 0.58%   |
| Kingston SA400S37480G 480GB SSD                     | 40       | 0.58%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 38       | 0.55%   |
| Toshiba HDWD110 1TB                                 | 38       | 0.55%   |
| Crucial CT240BX500SSD1 240GB                        | 37       | 0.54%   |
| Seagate ST1000DM003-1CH162 1TB                      | 36       | 0.53%   |
| Seagate ST2000DM001-1ER164 2TB                      | 32       | 0.47%   |
| Seagate ST3500418AS 500GB                           | 31       | 0.45%   |
| SanDisk NVMe SSD Drive 500GB                        | 31       | 0.45%   |
| Kingston SV300S37A120G 120GB SSD                    | 31       | 0.45%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 29       | 0.42%   |
| Toshiba DT01ACA200 2TB                              | 29       | 0.42%   |
| Seagate Expansion 1TB                               | 29       | 0.42%   |
| Seagate ST4000DM004-2CV104 4TB                      | 28       | 0.41%   |
| Toshiba DT01ACA050 500GB                            | 26       | 0.38%   |
| Seagate ST2000DM001-1CH164 2TB                      | 26       | 0.38%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 25       | 0.36%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 24       | 0.35%   |
| Seagate ST31000524AS 1TB                            | 24       | 0.35%   |
| Samsung SSD 980 1TB                                 | 24       | 0.35%   |
| Samsung SSD 970 EVO Plus 500GB                      | 24       | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 968      | 1565   | 37.36%  |
| WDC                 | 900      | 1482   | 34.74%  |
| Toshiba             | 279      | 369    | 10.77%  |
| Samsung Electronics | 142      | 219    | 5.48%   |
| Hitachi             | 138      | 199    | 5.33%   |
| HGST                | 65       | 102    | 2.51%   |
| Unknown             | 18       | 27     | 0.69%   |
| Maxtor              | 13       | 15     | 0.5%    |
| JMicron Technology  | 11       | 15     | 0.42%   |
| Fujitsu             | 9        | 11     | 0.35%   |
| ASMT                | 8        | 11     | 0.31%   |
| Intenso             | 6        | 10     | 0.23%   |
| USB3.0              | 5        | 5      | 0.19%   |
| Apple               | 5        | 8      | 0.19%   |
| External            | 4        | 5      | 0.15%   |
| MaxDigital          | 3        | 3      | 0.12%   |
| HGST HTS            | 3        | 3      | 0.12%   |
| Hewlett-Packard     | 3        | 3      | 0.12%   |
| ASMedia             | 3        | 3      | 0.12%   |
| USB                 | 2        | 2      | 0.08%   |
| Maxone              | 2        | 2      | 0.08%   |
| SABRENT             | 1        | 1      | 0.04%   |
| Lenovo              | 1        | 1      | 0.04%   |
| Initio              | 1        | 1      | 0.04%   |
| IBM/Hitachi         | 1        | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 567      | 878    | 26.51%  |
| Kingston            | 309      | 430    | 14.45%  |
| Crucial             | 267      | 413    | 12.48%  |
| SanDisk             | 175      | 229    | 8.18%   |
| WDC                 | 139      | 197    | 6.5%    |
| A-DATA Technology   | 74       | 108    | 3.46%   |
| Intel               | 56       | 75     | 2.62%   |
| China               | 56       | 82     | 2.62%   |
| OCZ                 | 40       | 56     | 1.87%   |
| PNY                 | 39       | 61     | 1.82%   |
| Patriot             | 33       | 42     | 1.54%   |
| SPCC                | 31       | 38     | 1.45%   |
| Toshiba             | 23       | 34     | 1.08%   |
| Intenso             | 21       | 31     | 0.98%   |
| GOODRAM             | 20       | 26     | 0.94%   |
| Plextor             | 19       | 23     | 0.89%   |
| Lexar               | 19       | 22     | 0.89%   |
| Corsair             | 19       | 28     | 0.89%   |
| Transcend           | 18       | 18     | 0.84%   |
| Team                | 18       | 24     | 0.84%   |
| Micron Technology   | 17       | 20     | 0.79%   |
| Apacer              | 15       | 17     | 0.7%    |
| SK hynix            | 11       | 12     | 0.51%   |
| Gigabyte Technology | 11       | 16     | 0.51%   |
| Seagate             | 10       | 13     | 0.47%   |
| Leven               | 10       | 10     | 0.47%   |
| KingDian            | 10       | 10     | 0.47%   |
| KingSpec            | 8        | 10     | 0.37%   |
| LITEONIT            | 5        | 8      | 0.23%   |
| LITEON              | 5        | 9      | 0.23%   |
| Apple               | 5        | 5      | 0.23%   |
| Verbatim            | 4        | 5      | 0.19%   |
| NGFF                | 4        | 4      | 0.19%   |
| Mushkin             | 4        | 4      | 0.19%   |
| Hoodisk             | 4        | 4      | 0.19%   |
| TO Exter            | 3        | 4      | 0.14%   |
| Netac               | 3        | 4      | 0.14%   |
| Kingmax             | 3        | 4      | 0.14%   |
| Hewlett-Packard     | 3        | 4      | 0.14%   |
| ASMT                | 3        | 7      | 0.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1879     | 4063   | 40.59%  |
| SSD     | 1669     | 3067   | 36.06%  |
| NVMe    | 989      | 1588   | 21.37%  |
| Unknown | 87       | 129    | 1.88%   |
| MMC     | 5        | 5      | 0.11%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 2396     | 6883   | 66.15%  |
| NVMe | 985      | 1580   | 27.19%  |
| SAS  | 236      | 384    | 6.52%   |
| MMC  | 5        | 5      | 0.14%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 1767     | 3446   | 43.8%   |
| 0.51-1.0   | 1258     | 2098   | 31.18%  |
| 1.01-2.0   | 548      | 814    | 13.58%  |
| 3.01-4.0   | 178      | 283    | 4.41%   |
| 4.01-10.0  | 134      | 250    | 3.32%   |
| 2.01-3.0   | 132      | 206    | 3.27%   |
| 10.01-20.0 | 17       | 33     | 0.42%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 475      | 17.02%  |
| 501-1000       | 471      | 16.88%  |
| 101-250        | 470      | 16.84%  |
| 1001-2000      | 464      | 16.62%  |
| More than 3000 | 399      | 14.3%   |
| 2001-3000      | 241      | 8.63%   |
| 51-100         | 98       | 3.51%   |
| Unknown        | 97       | 3.48%   |
| 1-20           | 43       | 1.54%   |
| 21-50          | 33       | 1.18%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 451      | 15.52%  |
| 1-20           | 412      | 14.18%  |
| 501-1000       | 374      | 12.87%  |
| 251-500        | 351      | 12.08%  |
| 21-50          | 348      | 11.98%  |
| 51-100         | 315      | 10.84%  |
| 1001-2000      | 286      | 9.84%   |
| More than 3000 | 161      | 5.54%   |
| 2001-3000      | 110      | 3.79%   |
| Unknown        | 97       | 3.34%   |
| 0              | 1        | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 7        | 9      | 2.08%   |
| WDC WD5000AAKX-001CA0 500GB           | 5        | 7      | 1.49%   |
| WDC WD10EARS-00Y5B1 1TB               | 5        | 5      | 1.49%   |
| Samsung Electronics HD103SJ 1TB       | 5        | 5      | 1.49%   |
| Hitachi HDS721010CLA332 1TB           | 5        | 5      | 1.49%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 4        | 4      | 1.19%   |
| Seagate ST3500413AS 500GB             | 4        | 5      | 1.19%   |
| Seagate ST1000DX001-1CM162 1TB        | 4        | 6      | 1.19%   |
| Samsung Electronics SSD 960 EVO 250GB | 4        | 5      | 1.19%   |
| Samsung Electronics HD103UJ 1TB       | 4        | 6      | 1.19%   |
| WDC WD20EARS-00MVWB0 2TB              | 3        | 3      | 0.89%   |
| WDC WD15EARS-00MVWB0 1TB              | 3        | 3      | 0.89%   |
| WDC WD10EZEX-00RKKA0 1TB              | 3        | 3      | 0.89%   |
| WDC WD10EZEX-00BN5A0 1TB              | 3        | 3      | 0.89%   |
| WDC WD10EARX-00N0YB0 1TB              | 3        | 4      | 0.89%   |
| Toshiba MQ01ABD050 500GB              | 3        | 3      | 0.89%   |
| Seagate ST4000DM000-1F2168 4TB        | 3        | 11     | 0.89%   |
| Seagate ST31000524AS 1TB              | 3        | 5      | 0.89%   |
| Seagate ST2000DM001-1CH164 2TB        | 3        | 3      | 0.89%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 3        | 3      | 0.89%   |
| Samsung Electronics SSD 870 EVO 1TB   | 3        | 3      | 0.89%   |
| Kingston SV300S37A120G 120GB SSD      | 3        | 3      | 0.89%   |
| Kingston SA400S37240G 240GB SSD       | 3        | 3      | 0.89%   |
| Crucial CT525MX300SSD1 528GB          | 3        | 3      | 0.89%   |
| WDC WD5000AAKX-00ERMA0 500GB          | 2        | 2      | 0.6%    |
| WDC WD5000AAKX-003CA0 500GB           | 2        | 2      | 0.6%    |
| WDC WD5000AACS-00G8B1 500GB           | 2        | 2      | 0.6%    |
| WDC WD40EFRX-68WT0N0 4TB              | 2        | 3      | 0.6%    |
| WDC WD30EZRZ-00Z5HB0 3TB              | 2        | 2      | 0.6%    |
| WDC WD30EFRX-68EUZN0 3TB              | 2        | 2      | 0.6%    |
| WDC WD20EARX-00PASB0 2TB              | 2        | 2      | 0.6%    |
| Seagate ST3250318AS 250GB             | 2        | 2      | 0.6%    |
| Seagate ST3250310AS 250GB             | 2        | 2      | 0.6%    |
| Seagate ST31000528AS 1TB              | 2        | 4      | 0.6%    |
| Seagate ST31000340NS 1TB              | 2        | 3      | 0.6%    |
| Seagate ST2000DX001-1CM164 2TB        | 2        | 2      | 0.6%    |
| Seagate ST2000DM008-2FR102 2TB        | 2        | 2      | 0.6%    |
| Seagate ST2000DM006-2DM164 2TB        | 2        | 2      | 0.6%    |
| Seagate ST2000DM001-1ER164 2TB        | 2        | 7      | 0.6%    |
| Seagate ST1000DX001-1NS162 1TB        | 2        | 3      | 0.6%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 104      | 121    | 32.1%   |
| Seagate             | 91       | 131    | 28.09%  |
| Samsung Electronics | 30       | 36     | 9.26%   |
| Hitachi             | 19       | 21     | 5.86%   |
| Toshiba             | 12       | 15     | 3.7%    |
| Kingston            | 12       | 12     | 3.7%    |
| SanDisk             | 9        | 12     | 2.78%   |
| Intel               | 9        | 10     | 2.78%   |
| HGST                | 7        | 7      | 2.16%   |
| Crucial             | 7        | 7      | 2.16%   |
| A-DATA Technology   | 5        | 5      | 1.54%   |
| OCZ                 | 2        | 2      | 0.62%   |
| Apacer              | 2        | 2      | 0.62%   |
| Transcend           | 1        | 1      | 0.31%   |
| SPCC                | 1        | 1      | 0.31%   |
| SK hynix            | 1        | 2      | 0.31%   |
| Phison              | 1        | 2      | 0.31%   |
| Patriot             | 1        | 1      | 0.31%   |
| Micron Technology   | 1        | 1      | 0.31%   |
| Maxtor              | 1        | 1      | 0.31%   |
| MaxDigital          | 1        | 1      | 0.31%   |
| KingSpec            | 1        | 2      | 0.31%   |
| Intenso             | 1        | 4      | 0.31%   |
| Hewlett-Packard     | 1        | 1      | 0.31%   |
| Fujitsu             | 1        | 1      | 0.31%   |
| Drevo               | 1        | 1      | 0.31%   |
| Corsair             | 1        | 5      | 0.31%   |
| ASMT                | 1        | 5      | 0.31%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 103      | 120    | 40.71%  |
| Seagate             | 90       | 128    | 35.57%  |
| Samsung Electronics | 19       | 24     | 7.51%   |
| Hitachi             | 19       | 21     | 7.51%   |
| Toshiba             | 12       | 15     | 4.74%   |
| HGST                | 7        | 7      | 2.77%   |
| Maxtor              | 1        | 1      | 0.4%    |
| MaxDigital          | 1        | 1      | 0.4%    |
| Fujitsu             | 1        | 1      | 0.4%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 233      | 318    | 77.15%  |
| SSD  | 58       | 79     | 19.21%  |
| NVMe | 11       | 13     | 3.64%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WDS256G1X0C-00ENX0 256GB      | 1        | 1      | 8.33%   |
| WDC WD3200BPVT-24ZEST0 320GB      | 1        | 1      | 8.33%   |
| WDC WD1600AAJS-65WAA0 160GB       | 1        | 1      | 8.33%   |
| Toshiba MQ01ABF050 500GB          | 1        | 1      | 8.33%   |
| Toshiba MK1059GSM 1TB             | 1        | 1      | 8.33%   |
| Seagate ST9640320AS 640GB         | 1        | 1      | 8.33%   |
| Seagate ST3500418AS 500GB         | 1        | 1      | 8.33%   |
| Seagate ST3250318AS 250GB         | 1        | 1      | 8.33%   |
| Seagate ST31000524AS 1TB          | 1        | 2      | 8.33%   |
| Samsung Electronics HD321HJ 320GB | 1        | 1      | 8.33%   |
| Kingston SV300S37A120G 120GB SSD  | 1        | 1      | 8.33%   |
| Hitachi HDS721010CLA332 1TB       | 1        | 1      | 8.33%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 4        | 5      | 33.33%  |
| WDC                 | 3        | 3      | 25%     |
| Toshiba             | 2        | 2      | 16.67%  |
| Samsung Electronics | 1        | 1      | 8.33%   |
| Kingston            | 1        | 1      | 8.33%   |
| Hitachi             | 1        | 1      | 8.33%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 1733     | 5578   | 57.29%  |
| Works    | 993      | 2851   | 32.83%  |
| Malfunc  | 287      | 410    | 9.49%   |
| Failed   | 12       | 13     | 0.4%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1366     | 33.54%  |
| AMD                              | 1235     | 30.32%  |
| Samsung Electronics              | 414      | 10.16%  |
| ASMedia Technology               | 172      | 4.22%   |
| SanDisk                          | 160      | 3.93%   |
| Phison Electronics               | 134      | 3.29%   |
| Micron/Crucial Technology        | 74       | 1.82%   |
| Marvell Technology Group         | 73       | 1.79%   |
| Kingston Technology Company      | 71       | 1.74%   |
| Silicon Motion                   | 68       | 1.67%   |
| JMicron Technology               | 61       | 1.5%    |
| ADATA Technology                 | 46       | 1.13%   |
| Nvidia                           | 38       | 0.93%   |
| Realtek Semiconductor            | 34       | 0.83%   |
| SK hynix                         | 22       | 0.54%   |
| Toshiba America Info Systems     | 11       | 0.27%   |
| Seagate Technology               | 10       | 0.25%   |
| LSI Logic / Symbios Logic        | 10       | 0.25%   |
| Micron Technology                | 9        | 0.22%   |
| KIOXIA                           | 9        | 0.22%   |
| VIA Technologies                 | 8        | 0.2%    |
| Lite-On Technology               | 6        | 0.15%   |
| Broadcom / LSI                   | 6        | 0.15%   |
| Silicon Image                    | 5        | 0.12%   |
| Shenzhen Longsys Electronics     | 4        | 0.1%    |
| Adaptec                          | 4        | 0.1%    |
| MAXIO Technology (Hangzhou)      | 3        | 0.07%   |
| Integrated Technology Express    | 3        | 0.07%   |
| INNOGRIT                         | 3        | 0.07%   |
| Yangtze Memory Technologies      | 1        | 0.02%   |
| Union Memory (Shenzhen)          | 1        | 0.02%   |
| Transcend                        | 1        | 0.02%   |
| Solidigm                         | 1        | 0.02%   |
| Silicon Integrated Systems [SiS] | 1        | 0.02%   |
| Promise Technology               | 1        | 0.02%   |
| PMC-Sierra                       | 1        | 0.02%   |
| OCZ Technology Group             | 1        | 0.02%   |
| Lenovo                           | 1        | 0.02%   |
| HighPoint Technologies           | 1        | 0.02%   |
| Dell                             | 1        | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 825      | 16.27%  |
| AMD 400 Series Chipset SATA Controller                                                  | 348      | 6.86%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 243      | 4.79%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 169      | 3.33%   |
| AMD 500 Series Chipset SATA Controller                                                  | 162      | 3.19%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 158      | 3.12%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 133      | 2.62%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 116      | 2.29%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 113      | 2.23%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 111      | 2.19%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 105      | 2.07%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 104      | 2.05%   |
| AMD 300 Series Chipset SATA Controller                                                  | 88       | 1.74%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 87       | 1.72%   |
| Intel SATA Controller [RAID mode]                                                       | 85       | 1.68%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 71       | 1.4%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 71       | 1.4%    |
| Phison E12 NVMe Controller                                                              | 68       | 1.34%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 67       | 1.32%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 54       | 1.06%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 54       | 1.06%   |
| AMD FCH SATA Controller D                                                               | 54       | 1.06%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 44       | 0.87%   |
| AMD X370 Series Chipset SATA Controller                                                 | 44       | 0.87%   |
| Samsung NVMe SSD Controller 980                                                         | 43       | 0.85%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 43       | 0.85%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 42       | 0.83%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 42       | 0.83%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 41       | 0.81%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 40       | 0.79%   |
| Kingston Company A2000 NVMe SSD                                                         | 38       | 0.75%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 37       | 0.73%   |
| Intel SSD 660P Series                                                                   | 37       | 0.73%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 36       | 0.71%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 35       | 0.69%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 34       | 0.67%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 33       | 0.65%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 32       | 0.63%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 30       | 0.59%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 29       | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 2323     | 59.99%  |
| NVMe | 991      | 25.59%  |
| IDE  | 388      | 10.02%  |
| RAID | 146      | 3.77%   |
| SAS  | 21       | 0.54%   |
| SCSI | 3        | 0.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 1341     | 51.28%  |
| AMD    | 1274     | 48.72%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 134      | 5.1%    |
| AMD Ryzen 7 3700X 8-Core Processor          | 81       | 3.08%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 64       | 2.43%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 64       | 2.43%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 45       | 1.71%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 36       | 1.37%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 34       | 1.29%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 31       | 1.18%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 29       | 1.1%    |
| AMD Ryzen 9 5900X 12-Core Processor         | 28       | 1.07%   |
| AMD FX-8350 Eight-Core Processor            | 28       | 1.07%   |
| AMD FX-6300 Six-Core Processor              | 28       | 1.07%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 27       | 1.03%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 25       | 0.95%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 25       | 0.95%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 24       | 0.91%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 24       | 0.91%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 23       | 0.87%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 23       | 0.87%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 23       | 0.87%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 23       | 0.87%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 22       | 0.84%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 22       | 0.84%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 21       | 0.8%    |
| AMD Ryzen 5 5600G with Radeon Graphics      | 21       | 0.8%    |
| Intel Core i7-6700 CPU @ 3.40GHz            | 20       | 0.76%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 20       | 0.76%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 20       | 0.76%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 19       | 0.72%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 19       | 0.72%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 19       | 0.72%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 18       | 0.68%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 18       | 0.68%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 18       | 0.68%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 18       | 0.68%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 18       | 0.68%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 17       | 0.65%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 16       | 0.61%   |
| AMD Ryzen 7 1700X Eight-Core Processor      | 16       | 0.61%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 16       | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 437      | 16.65%  |
| AMD Ryzen 5             | 432      | 16.46%  |
| Intel Core i7           | 356      | 13.57%  |
| AMD Ryzen 7             | 312      | 11.89%  |
| Intel Core i3           | 135      | 5.14%   |
| AMD Ryzen 9             | 130      | 4.95%   |
| Intel Xeon              | 126      | 4.8%    |
| AMD FX                  | 117      | 4.46%   |
| Other                   | 63       | 2.4%    |
| AMD Ryzen 3             | 48       | 1.83%   |
| Intel Core 2 Duo        | 43       | 1.64%   |
| Intel Celeron           | 36       | 1.37%   |
| Intel Pentium           | 32       | 1.22%   |
| AMD Ryzen Threadripper  | 29       | 1.11%   |
| AMD Phenom II X4        | 29       | 1.11%   |
| Intel Core 2 Quad       | 27       | 1.03%   |
| Intel Core i9           | 24       | 0.91%   |
| Intel Pentium Dual-Core | 23       | 0.88%   |
| AMD Athlon II X2        | 21       | 0.8%    |
| AMD A8                  | 19       | 0.72%   |
| AMD A10                 | 19       | 0.72%   |
| AMD A4                  | 16       | 0.61%   |
| AMD Athlon              | 14       | 0.53%   |
| AMD Phenom II X6        | 12       | 0.46%   |
| AMD Athlon 64 X2        | 12       | 0.46%   |
| Intel Core 2            | 11       | 0.42%   |
| AMD Ryzen 5 PRO         | 9        | 0.34%   |
| AMD Athlon X4           | 9        | 0.34%   |
| AMD Athlon II X4        | 9        | 0.34%   |
| Intel Atom              | 8        | 0.3%    |
| AMD Phenom              | 7        | 0.27%   |
| Intel Pentium Gold      | 6        | 0.23%   |
| Intel Pentium Dual      | 6        | 0.23%   |
| AMD Ryzen 7 PRO         | 6        | 0.23%   |
| Intel Genuine           | 5        | 0.19%   |
| AMD Athlon II X3        | 5        | 0.19%   |
| Intel Pentium D         | 4        | 0.15%   |
| AMD Sempron             | 4        | 0.15%   |
| AMD Phenom II X2        | 3        | 0.11%   |
| AMD E1                  | 3        | 0.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 897      | 34.18%  |
| 6       | 618      | 23.55%  |
| 8       | 408      | 15.55%  |
| 2       | 394      | 15.02%  |
| 12      | 118      | 4.5%    |
| 16      | 77       | 2.93%   |
| 3       | 49       | 1.87%   |
| 1       | 28       | 1.07%   |
| 10      | 18       | 0.69%   |
| 24      | 7        | 0.27%   |
| 32      | 3        | 0.11%   |
| 14      | 3        | 0.11%   |
| 20      | 2        | 0.08%   |
| Unknown | 2        | 0.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 2592     | 99.16%  |
| 2      | 22       | 0.84%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 1784     | 68.04%  |
| 1       | 836      | 31.88%  |
| Unknown | 2        | 0.08%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 2586     | 98.74%  |
| Unknown        | 33       | 1.26%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1367     | 50.46%  |
| 0x08701021 | 139      | 5.13%   |
| 0x306c3    | 103      | 3.8%    |
| 0x0800820d | 103      | 3.8%    |
| 0x08701013 | 76       | 2.81%   |
| 0x306a9    | 68       | 2.51%   |
| 0x206a7    | 63       | 2.33%   |
| 0x906ea    | 57       | 2.1%    |
| 0x506e3    | 51       | 1.88%   |
| 0x06000852 | 49       | 1.81%   |
| 0x1067a    | 35       | 1.29%   |
| 0x08001138 | 32       | 1.18%   |
| 0x906e9    | 28       | 1.03%   |
| 0x010000c8 | 24       | 0.89%   |
| 0x306f2    | 23       | 0.85%   |
| 0x0a201016 | 23       | 0.85%   |
| 0x0a201009 | 22       | 0.81%   |
| 0x206d7    | 20       | 0.74%   |
| 0x08108109 | 20       | 0.74%   |
| 0x08001137 | 20       | 0.74%   |
| 0x0a601203 | 17       | 0.63%   |
| 0x0a20120a | 16       | 0.59%   |
| 0x08101016 | 16       | 0.59%   |
| 0x06003106 | 15       | 0.55%   |
| 0x90672    | 14       | 0.52%   |
| 0xa0655    | 13       | 0.48%   |
| 0x906ed    | 13       | 0.48%   |
| 0x06001119 | 13       | 0.48%   |
| 0x106e5    | 12       | 0.44%   |
| 0x0a50000d | 11       | 0.41%   |
| 0x0a50000c | 11       | 0.41%   |
| 0x08600106 | 11       | 0.41%   |
| 0x08001129 | 9        | 0.33%   |
| 0xa0671    | 8        | 0.3%    |
| 0xa0653    | 8        | 0.3%    |
| 0x906ec    | 8        | 0.3%    |
| 0x906eb    | 8        | 0.3%    |
| 0x6fd      | 8        | 0.3%    |
| 0x206c2    | 8        | 0.3%    |
| 0x406f1    | 7        | 0.26%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 369      | 14.05%  |
| Haswell          | 268      | 10.21%  |
| KabyLake         | 258      | 9.82%   |
| Zen+             | 243      | 9.25%   |
| Zen 3            | 175      | 6.66%   |
| Zen              | 167      | 6.36%   |
| SandyBridge      | 163      | 6.21%   |
| IvyBridge        | 162      | 6.17%   |
| Piledriver       | 129      | 4.91%   |
| Skylake          | 119      | 4.53%   |
| Penryn           | 90       | 3.43%   |
| K10              | 87       | 3.31%   |
| Unknown          | 69       | 2.63%   |
| CometLake        | 58       | 2.21%   |
| Core             | 40       | 1.52%   |
| Nehalem          | 33       | 1.26%   |
| Westmere         | 32       | 1.22%   |
| Steamroller      | 27       | 1.03%   |
| Broadwell        | 19       | 0.72%   |
| Bulldozer        | 18       | 0.69%   |
| Alderlake Hybrid | 18       | 0.69%   |
| K8 Hammer        | 15       | 0.57%   |
| Icelake          | 8        | 0.3%    |
| Excavator        | 8        | 0.3%    |
| Silvermont       | 7        | 0.27%   |
| Goldmont plus    | 7        | 0.27%   |
| Bonnell          | 7        | 0.27%   |
| NetBurst         | 6        | 0.23%   |
| Goldmont         | 6        | 0.23%   |
| K10 Llano        | 5        | 0.19%   |
| Jaguar           | 4        | 0.15%   |
| Bobcat           | 4        | 0.15%   |
| TigerLake        | 2        | 0.08%   |
| Puma             | 2        | 0.08%   |
| Tremont          | 1        | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 1315     | 46.57%  |
| AMD                        | 1017     | 36.01%  |
| Intel                      | 490      | 17.35%  |
| Matrox Electronics Systems | 1        | 0.04%   |
| ATI Technologies           | 1        | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 243      | 8.34%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 96       | 3.29%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 91       | 3.12%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 87       | 2.98%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 86       | 2.95%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 63       | 2.16%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 58       | 1.99%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 55       | 1.89%   |
| Nvidia GK208B [GeForce GT 710]                                              | 53       | 1.82%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 51       | 1.75%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 44       | 1.51%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 41       | 1.41%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 41       | 1.41%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 41       | 1.41%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 38       | 1.3%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 36       | 1.23%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 36       | 1.23%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 35       | 1.2%    |
| Intel HD Graphics 530                                                       | 35       | 1.2%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 33       | 1.13%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 31       | 1.06%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 31       | 1.06%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 31       | 1.06%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 30       | 1.03%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 28       | 0.96%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 26       | 0.89%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 25       | 0.86%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 25       | 0.86%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 25       | 0.86%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 25       | 0.86%   |
| Intel HD Graphics 630                                                       | 24       | 0.82%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 23       | 0.79%   |
| Nvidia GK208B [GeForce GT 730]                                              | 22       | 0.75%   |
| AMD Raphael                                                                 | 22       | 0.75%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 21       | 0.72%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 21       | 0.72%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 20       | 0.69%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 20       | 0.69%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 20       | 0.69%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 19       | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| 1 x Nvidia         | 1194     | 44.94%  |
| 1 x AMD            | 918      | 34.55%  |
| 1 x Intel          | 362      | 13.62%  |
| Intel + Nvidia     | 49       | 1.84%   |
| AMD + Nvidia       | 47       | 1.77%   |
| 2 x AMD            | 44       | 1.66%   |
| 2 x Nvidia         | 26       | 0.98%   |
| Intel + AMD        | 14       | 0.53%   |
| 1 x Matrox         | 1        | 0.04%   |
| Intel + 2 x Nvidia | 1        | 0.04%   |
| Intel + 2 x AMD    | 1        | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1563     | 59.03%  |
| Proprietary | 1072     | 40.48%  |
| Unknown     | 13       | 0.49%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1086     | 40.24%  |
| 7.01-8.0   | 410      | 15.19%  |
| 1.01-2.0   | 314      | 11.63%  |
| 3.01-4.0   | 280      | 10.37%  |
| 5.01-6.0   | 180      | 6.67%   |
| 0.51-1.0   | 159      | 5.89%   |
| 8.01-16.0  | 116      | 4.3%    |
| 0.01-0.5   | 85       | 3.15%   |
| 2.01-3.0   | 48       | 1.78%   |
| 16.01-24.0 | 19       | 0.7%    |
| 4.01-5.0   | 2        | 0.07%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 489      | 15.64%  |
| Goldstar             | 335      | 10.71%  |
| Dell                 | 291      | 9.31%   |
| Acer                 | 250      | 7.99%   |
| AOC                  | 192      | 6.14%   |
| Ancor Communications | 183      | 5.85%   |
| BenQ                 | 179      | 5.72%   |
| Hewlett-Packard      | 149      | 4.76%   |
| Philips              | 129      | 4.13%   |
| LG Electronics       | 101      | 3.23%   |
| ViewSonic            | 73       | 2.33%   |
| ASUSTek Computer     | 67       | 2.14%   |
| Lenovo               | 50       | 1.6%    |
| Iiyama               | 45       | 1.44%   |
| Unknown              | 44       | 1.41%   |
| Unknown              | 34       | 1.09%   |
| Sony                 | 29       | 0.93%   |
| Vizio                | 21       | 0.67%   |
| MSI                  | 21       | 0.67%   |
| Eizo                 | 18       | 0.58%   |
| AUS                  | 17       | 0.54%   |
| Gigabyte Technology  | 16       | 0.51%   |
| Fujitsu Siemens      | 16       | 0.51%   |
| Sceptre Tech         | 15       | 0.48%   |
| NEC Computers        | 15       | 0.48%   |
| Idek Iiyama          | 15       | 0.48%   |
| Medion               | 12       | 0.38%   |
| Sharp                | 10       | 0.32%   |
| Panasonic            | 9        | 0.29%   |
| Vestel Elektronik    | 8        | 0.26%   |
| Microstep            | 8        | 0.26%   |
| Lenovo Group Limited | 8        | 0.26%   |
| HannStar             | 8        | 0.26%   |
| Toshiba              | 7        | 0.22%   |
| Pixio                | 7        | 0.22%   |
| KTC                  | 6        | 0.19%   |
| HPN                  | 6        | 0.19%   |
| Apple                | 6        | 0.19%   |
| VIZ                  | 5        | 0.16%   |
| Vestel               | 5        | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Unknown                                                               | 34       | 1%      |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 21       | 0.62%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 20       | 0.59%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 19       | 0.56%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 14       | 0.41%   |
| AOC Q27G2SG4 AOC2702 2560x1440 597x336mm 27.0-inch                    | 13       | 0.38%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 12       | 0.35%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 10       | 0.29%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 9        | 0.26%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 9        | 0.26%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                    | 9        | 0.26%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                      | 8        | 0.23%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch            | 8        | 0.23%   |
| Goldstar HDR WFHD GSM7715 2560x1080 798x334mm 34.1-inch               | 8        | 0.23%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                     | 8        | 0.23%   |
| AOC Q27P1B AOC2701 2560x1440 597x336mm 27.0-inch                      | 8        | 0.23%   |
| AOC 2460 AOC2460 1920x1080 531x299mm 24.0-inch                        | 8        | 0.23%   |
| Ancor Communications VG248 ACI24A4 1920x1080 531x299mm 24.0-inch      | 8        | 0.23%   |
| Samsung Electronics LCD Monitor SyncMaster                            | 7        | 0.21%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch               | 7        | 0.21%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 7        | 0.21%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                     | 7        | 0.21%   |
| AOC 24P1W1 AOC2401 1920x1080 527x296mm 23.8-inch                      | 7        | 0.21%   |
| AOC 24B2W1 AOC2402 1920x1080 527x296mm 23.8-inch                      | 7        | 0.21%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch      | 7        | 0.21%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                       | 6        | 0.18%   |
| Goldstar MP59G GSM5B35 1920x1080 480x270mm 21.7-inch                  | 6        | 0.18%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                | 6        | 0.18%   |
| Goldstar E2350 GSM5791 1920x1080 510x290mm 23.1-inch                  | 6        | 0.18%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                | 6        | 0.18%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 6        | 0.18%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                     | 6        | 0.18%   |
| ASUSTek Computer VA326 AUS32FA 1920x1080 698x393mm 31.5-inch          | 6        | 0.18%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                        | 6        | 0.18%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch      | 6        | 0.18%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch | 6        | 0.18%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 6        | 0.18%   |
| Ancor Communications ASUS MG279 ACI27A7 2560x1440 597x336mm 27.0-inch | 6        | 0.18%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch  | 5        | 0.15%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch     | 5        | 0.15%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1321     | 43.3%   |
| 2560x1440 (QHD)    | 305      | 10%     |
| 3840x2160 (4K)     | 288      | 9.44%   |
| Unknown            | 174      | 5.7%    |
| 1280x1024 (SXGA)   | 123      | 4.03%   |
| 1680x1050 (WSXGA+) | 119      | 3.9%    |
| 3440x1440          | 81       | 2.65%   |
| 1920x1200 (WUXGA)  | 79       | 2.59%   |
| 1366x768 (WXGA)    | 79       | 2.59%   |
| 1440x900 (WXGA+)   | 74       | 2.43%   |
| 2560x1080          | 70       | 2.29%   |
| 3840x1080          | 66       | 2.16%   |
| 1600x900 (HD+)     | 59       | 1.93%   |
| 1360x768           | 27       | 0.88%   |
| 5120x1440          | 12       | 0.39%   |
| 4480x1440          | 12       | 0.39%   |
| 1920x540           | 11       | 0.36%   |
| 1280x720 (HD)      | 11       | 0.36%   |
| 5760x1080          | 10       | 0.33%   |
| 1024x768 (XGA)     | 9        | 0.29%   |
| 5760x2160          | 7        | 0.23%   |
| 3600x1080          | 7        | 0.23%   |
| 2560x1600          | 7        | 0.23%   |
| 3840x1600          | 6        | 0.2%    |
| 3360x1080          | 5        | 0.16%   |
| 3200x1080          | 5        | 0.16%   |
| 1600x1200          | 5        | 0.16%   |
| 7680x2160          | 4        | 0.13%   |
| 6400x2160          | 4        | 0.13%   |
| 3840x1200          | 4        | 0.13%   |
| 3520x1080          | 4        | 0.13%   |
| 3360x1050          | 3        | 0.1%    |
| 3286x1080          | 3        | 0.1%    |
| 7680x1080          | 2        | 0.07%   |
| 6000x1440          | 2        | 0.07%   |
| 5504x1440          | 2        | 0.07%   |
| 5120x1080          | 2        | 0.07%   |
| 4480x1080          | 2        | 0.07%   |
| 4240x1440          | 2        | 0.07%   |
| 2960x900           | 2        | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 531      | 17.66%  |
| 27      | 430      | 14.3%   |
| 24      | 424      | 14.11%  |
| 23      | 341      | 11.34%  |
| 21      | 304      | 10.11%  |
| 19      | 129      | 4.29%   |
| 31      | 126      | 4.19%   |
| 34      | 116      | 3.86%   |
| 22      | 80       | 2.66%   |
| 18      | 73       | 2.43%   |
| 20      | 65       | 2.16%   |
| 17      | 56       | 1.86%   |
| 84      | 35       | 1.16%   |
| 72      | 23       | 0.77%   |
| 40      | 22       | 0.73%   |
| 32      | 21       | 0.7%    |
| 25      | 20       | 0.67%   |
| 54      | 19       | 0.63%   |
| 15      | 16       | 0.53%   |
| 28      | 15       | 0.5%    |
| 65      | 13       | 0.43%   |
| 48      | 11       | 0.37%   |
| 49      | 10       | 0.33%   |
| 33      | 9        | 0.3%    |
| 43      | 8        | 0.27%   |
| 37      | 8        | 0.27%   |
| 46      | 7        | 0.23%   |
| 42      | 7        | 0.23%   |
| 29      | 7        | 0.23%   |
| 26      | 7        | 0.23%   |
| 14      | 7        | 0.23%   |
| 12      | 7        | 0.23%   |
| 39      | 6        | 0.2%    |
| 35      | 6        | 0.2%    |
| 47      | 5        | 0.17%   |
| 36      | 5        | 0.17%   |
| 60      | 4        | 0.13%   |
| 52      | 4        | 0.13%   |
| 16      | 4        | 0.13%   |
| 74      | 3        | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 1068     | 37.11%  |
| 401-500     | 564      | 19.6%   |
| Unknown     | 531      | 18.45%  |
| 601-700     | 189      | 6.57%   |
| 701-800     | 151      | 5.25%   |
| 351-400     | 85       | 2.95%   |
| 1001-1500   | 77       | 2.68%   |
| 301-350     | 68       | 2.36%   |
| 1501-2000   | 65       | 2.26%   |
| 801-900     | 47       | 1.63%   |
| 201-300     | 17       | 0.59%   |
| 901-1000    | 16       | 0.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 1647     | 60.42%  |
| Unknown | 498      | 18.27%  |
| 16/10   | 266      | 9.76%   |
| 21/9    | 128      | 4.7%    |
| 5/4     | 116      | 4.26%   |
| 4/3     | 29       | 1.06%   |
| 3/2     | 18       | 0.66%   |
| 32/9    | 12       | 0.44%   |
| 6/5     | 5        | 0.18%   |
| 1.96    | 2        | 0.07%   |
| 3.20    | 1        | 0.04%   |
| 1.03    | 1        | 0.04%   |
| 1.00    | 1        | 0.04%   |
| 0.80    | 1        | 0.04%   |
| 0.56    | 1        | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 920      | 31.28%  |
| Unknown        | 531      | 18.06%  |
| 301-350        | 432      | 14.69%  |
| 351-500        | 293      | 9.96%   |
| 151-200        | 262      | 8.91%   |
| 251-300        | 149      | 5.07%   |
| More than 1000 | 120      | 4.08%   |
| 141-150        | 104      | 3.54%   |
| 501-1000       | 84       | 2.86%   |
| 101-110        | 20       | 0.68%   |
| 131-140        | 9        | 0.31%   |
| 71-80          | 7        | 0.24%   |
| 81-90          | 3        | 0.1%    |
| 51-60          | 2        | 0.07%   |
| 111-120        | 2        | 0.07%   |
| 91-100         | 2        | 0.07%   |
| 121-130        | 1        | 0.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 1476     | 52.88%  |
| 101-120 | 531      | 19.03%  |
| Unknown | 531      | 19.03%  |
| 121-160 | 104      | 3.73%   |
| 1-50    | 96       | 3.44%   |
| 161-240 | 53       | 1.9%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1929     | 72.03%  |
| 2     | 617      | 23.04%  |
| 3     | 89       | 3.32%   |
| 0     | 36       | 1.34%   |
| 4     | 7        | 0.26%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 1610     | 42.92%  |
| Intel                                  | 1178     | 31.4%   |
| Qualcomm Atheros                       | 194      | 5.17%   |
| Broadcom                               | 102      | 2.72%   |
| Ralink Technology                      | 93       | 2.48%   |
| TP-Link                                | 92       | 2.45%   |
| MediaTek                               | 46       | 1.23%   |
| Microsoft                              | 45       | 1.2%    |
| Nvidia                                 | 31       | 0.83%   |
| Aquantia                               | 31       | 0.83%   |
| Ralink                                 | 26       | 0.69%   |
| Samsung Electronics                    | 25       | 0.67%   |
| Qualcomm Atheros Communications        | 25       | 0.67%   |
| Xiaomi                                 | 19       | 0.51%   |
| ASUSTek Computer                       | 17       | 0.45%   |
| NetGear                                | 16       | 0.43%   |
| Marvell Technology Group               | 16       | 0.43%   |
| D-Link                                 | 16       | 0.43%   |
| Huawei Technologies                    | 13       | 0.35%   |
| Broadcom Limited                       | 12       | 0.32%   |
| Linksys                                | 11       | 0.29%   |
| D-Link System                          | 9        | 0.24%   |
| Microchip Technology                   | 8        | 0.21%   |
| Mellanox Technologies                  | 8        | 0.21%   |
| Edimax Technology                      | 7        | 0.19%   |
| Motorola PCS                           | 6        | 0.16%   |
| ASIX Electronics                       | 5        | 0.13%   |
| ZyXEL Communications                   | 4        | 0.11%   |
| OPPO Electronics                       | 4        | 0.11%   |
| InterBiometrics                        | 4        | 0.11%   |
| T & A Mobile Phones                    | 3        | 0.08%   |
| Sony Ericsson Mobile Communications AB | 3        | 0.08%   |
| SEGGER                                 | 3        | 0.08%   |
| Qualcomm                               | 3        | 0.08%   |
| OnePlus Technology (Shenzhen)          | 3        | 0.08%   |
| JMicron Technology                     | 3        | 0.08%   |
| IMC Networks                           | 3        | 0.08%   |
| Google                                 | 3        | 0.08%   |
| Belkin Components                      | 3        | 0.08%   |
| 802.11g Adapter [Linksys WUSB54GC v3]  | 3        | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1306     | 30.22%  |
| Intel I211 Gigabit Network Connection                             | 292      | 6.76%   |
| Intel Wi-Fi 6 AX200                                               | 197      | 4.56%   |
| Realtek RTL8125 2.5GbE Controller                                 | 161      | 3.73%   |
| Intel Ethernet Connection (2) I219-V                              | 125      | 2.89%   |
| Intel Ethernet Controller I225-V                                  | 89       | 2.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 82       | 1.9%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 65       | 1.5%    |
| Intel Ethernet Connection (7) I219-V                              | 58       | 1.34%   |
| Intel Wireless-AC 9260                                            | 52       | 1.2%    |
| Intel 82579V Gigabit Network Connection                           | 48       | 1.11%   |
| Intel Ethernet Connection (2) I218-V                              | 44       | 1.02%   |
| Intel Ethernet Connection I217-LM                                 | 39       | 0.9%    |
| Intel Ethernet Connection I217-V                                  | 38       | 0.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 33       | 0.76%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 32       | 0.74%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 32       | 0.74%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 31       | 0.72%   |
| Ralink MT7601U Wireless Adapter                                   | 30       | 0.69%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 29       | 0.67%   |
| Realtek 802.11ac NIC                                              | 27       | 0.62%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 27       | 0.62%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 25       | 0.58%   |
| Qualcomm Atheros AR9271 802.11n                                   | 25       | 0.58%   |
| Microsoft Xbox 360 Wireless Adapter                               | 25       | 0.58%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 23       | 0.53%   |
| Intel Wireless 8265 / 8275                                        | 23       | 0.53%   |
| Intel Wireless 7265                                               | 23       | 0.53%   |
| Intel 82574L Gigabit Network Connection                           | 23       | 0.53%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 21       | 0.49%   |
| Microsoft Xbox Wireless Adapter for Windows                       | 21       | 0.49%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 21       | 0.49%   |
| Nvidia MCP61 Ethernet                                             | 20       | 0.46%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 19       | 0.44%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 19       | 0.44%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 18       | 0.42%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 18       | 0.42%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 18       | 0.42%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 18       | 0.42%   |
| Ralink RT5370 Wireless Adapter                                    | 17       | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 489      | 36.33%  |
| Realtek Semiconductor                 | 269      | 19.99%  |
| Qualcomm Atheros                      | 98       | 7.28%   |
| Ralink Technology                     | 93       | 6.91%   |
| TP-Link                               | 91       | 6.76%   |
| Broadcom                              | 65       | 4.83%   |
| Microsoft                             | 45       | 3.34%   |
| MediaTek                              | 40       | 2.97%   |
| Ralink                                | 26       | 1.93%   |
| Qualcomm Atheros Communications       | 25       | 1.86%   |
| ASUSTek Computer                      | 17       | 1.26%   |
| NetGear                               | 16       | 1.19%   |
| D-Link                                | 16       | 1.19%   |
| Linksys                               | 11       | 0.82%   |
| Edimax Technology                     | 7        | 0.52%   |
| D-Link System                         | 6        | 0.45%   |
| Broadcom Limited                      | 5        | 0.37%   |
| ZyXEL Communications                  | 4        | 0.3%    |
| IMC Networks                          | 3        | 0.22%   |
| Belkin Components                     | 3        | 0.22%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3        | 0.22%   |
| ZyDAS                                 | 2        | 0.15%   |
| Mercucys                              | 2        | 0.15%   |
| AVM                                   | 2        | 0.15%   |
| Xiaomi                                | 1        | 0.07%   |
| Wacom                                 | 1        | 0.07%   |
| Senao                                 | 1        | 0.07%   |
| Samsung Electronics                   | 1        | 0.07%   |
| Philips (or NXP)                      | 1        | 0.07%   |
| Marvell Technology Group              | 1        | 0.07%   |
| Fujitsu Siemens Computers             | 1        | 0.07%   |
| Encore Electronics                    | 1        | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 197      | 14.5%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 65       | 4.78%   |
| Intel Wireless-AC 9260                                         | 52       | 3.83%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 32       | 2.35%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 32       | 2.35%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 31       | 2.28%   |
| Ralink MT7601U Wireless Adapter                                | 30       | 2.21%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 29       | 2.13%   |
| Realtek 802.11ac NIC                                           | 27       | 1.99%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 25       | 1.84%   |
| Qualcomm Atheros AR9271 802.11n                                | 25       | 1.84%   |
| Microsoft Xbox 360 Wireless Adapter                            | 25       | 1.84%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 23       | 1.69%   |
| Intel Wireless 8265 / 8275                                     | 23       | 1.69%   |
| Intel Wireless 7265                                            | 23       | 1.69%   |
| Microsoft Xbox Wireless Adapter for Windows                    | 21       | 1.55%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 21       | 1.55%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 19       | 1.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 18       | 1.32%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 18       | 1.32%   |
| Ralink RT5370 Wireless Adapter                                 | 17       | 1.25%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 17       | 1.25%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 16       | 1.18%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 16       | 1.18%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 16       | 1.18%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 14       | 1.03%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 13       | 0.96%   |
| Intel Wireless 3165                                            | 13       | 0.96%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 12       | 0.88%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 12       | 0.88%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 11       | 0.81%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 11       | 0.81%   |
| Intel Wireless 7260                                            | 11       | 0.81%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 10       | 0.74%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 10       | 0.74%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 9        | 0.66%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 9        | 0.66%   |
| TP-Link 802.11ac NIC                                           | 9        | 0.66%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 9        | 0.66%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 9        | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 1517     | 54%     |
| Intel                                  | 952      | 33.89%  |
| Qualcomm Atheros                       | 111      | 3.95%   |
| Broadcom                               | 40       | 1.42%   |
| Nvidia                                 | 31       | 1.1%    |
| Aquantia                               | 31       | 1.1%    |
| Xiaomi                                 | 18       | 0.64%   |
| Marvell Technology Group               | 15       | 0.53%   |
| Samsung Electronics                    | 14       | 0.5%    |
| Huawei Technologies                    | 11       | 0.39%   |
| Mellanox Technologies                  | 8        | 0.28%   |
| Broadcom Limited                       | 7        | 0.25%   |
| ASIX Electronics                       | 5        | 0.18%   |
| OPPO Electronics                       | 4        | 0.14%   |
| MediaTek                               | 4        | 0.14%   |
| Sony Ericsson Mobile Communications AB | 3        | 0.11%   |
| Motorola PCS                           | 3        | 0.11%   |
| JMicron Technology                     | 3        | 0.11%   |
| Google                                 | 3        | 0.11%   |
| D-Link System                          | 3        | 0.11%   |
| Tenda                                  | 2        | 0.07%   |
| T & A Mobile Phones                    | 2        | 0.07%   |
| Sundance Technology Inc / IC Plus      | 2        | 0.07%   |
| Qualcomm                               | 2        | 0.07%   |
| OnePlus Technology (Shenzhen)          | 2        | 0.07%   |
| National Semiconductor                 | 2        | 0.07%   |
| HMD Global                             | 2        | 0.07%   |
| ZTE WCDMA Technologies MSM             | 1        | 0.04%   |
| VIA Technologies                       | 1        | 0.04%   |
| TP-Link                                | 1        | 0.04%   |
| Silicon Integrated Systems [SiS]       | 1        | 0.04%   |
| NetXen Incorporated                    | 1        | 0.04%   |
| LG Electronics                         | 1        | 0.04%   |
| ICS Advent                             | 1        | 0.04%   |
| Foxconn / Hon Hai                      | 1        | 0.04%   |
| DisplayLink                            | 1        | 0.04%   |
| Apple                                  | 1        | 0.04%   |
| Accton Technology                      | 1        | 0.04%   |
| 3Com                                   | 1        | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1306     | 44.91%  |
| Intel I211 Gigabit Network Connection                             | 292      | 10.04%  |
| Realtek RTL8125 2.5GbE Controller                                 | 161      | 5.54%   |
| Intel Ethernet Connection (2) I219-V                              | 125      | 4.3%    |
| Intel Ethernet Controller I225-V                                  | 89       | 3.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 82       | 2.82%   |
| Intel Ethernet Connection (7) I219-V                              | 58       | 1.99%   |
| Intel 82579V Gigabit Network Connection                           | 48       | 1.65%   |
| Intel Ethernet Connection (2) I218-V                              | 44       | 1.51%   |
| Intel Ethernet Connection I217-LM                                 | 39       | 1.34%   |
| Intel Ethernet Connection I217-V                                  | 38       | 1.31%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 33       | 1.13%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 27       | 0.93%   |
| Intel 82574L Gigabit Network Connection                           | 23       | 0.79%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 21       | 0.72%   |
| Nvidia MCP61 Ethernet                                             | 20       | 0.69%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 19       | 0.65%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 18       | 0.62%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 18       | 0.62%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 16       | 0.55%   |
| Intel Ethernet Connection (2) I219-LM                             | 16       | 0.55%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 14       | 0.48%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 14       | 0.48%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 14       | 0.48%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 14       | 0.48%   |
| Intel I210 Gigabit Network Connection                             | 13       | 0.45%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 11       | 0.38%   |
| Intel Ethernet Connection (7) I219-LM                             | 11       | 0.38%   |
| Intel Ethernet Connection (14) I219-V                             | 11       | 0.38%   |
| Intel Ethernet Connection (11) I219-V                             | 10       | 0.34%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 10       | 0.34%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 9        | 0.31%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 9        | 0.31%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 8        | 0.28%   |
| Intel Ethernet Connection (2) I218-LM                             | 8        | 0.28%   |
| Intel Ethernet Connection (12) I219-V                             | 7        | 0.24%   |
| Huawei WLZ-AN00                                                   | 7        | 0.24%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 7        | 0.24%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 6        | 0.21%   |
| Intel 82578DC Gigabit Network Connection                          | 6        | 0.21%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2586     | 66.62%  |
| WiFi     | 1244     | 32.05%  |
| Modem    | 44       | 1.13%   |
| Unknown  | 8        | 0.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2084     | 76.45%  |
| WiFi     | 641      | 23.51%  |
| Modem    | 1        | 0.04%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1641     | 62.18%  |
| 2     | 841      | 31.87%  |
| 3     | 117      | 4.43%   |
| 0     | 22       | 0.83%   |
| 5     | 8        | 0.3%    |
| 4     | 8        | 0.3%    |
| 8     | 1        | 0.04%   |
| 7     | 1        | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2176     | 81.68%  |
| Yes  | 488      | 18.32%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 461      | 40.23%  |
| Cambridge Silicon Radio         | 314      | 27.4%   |
| ASUSTek Computer                | 104      | 9.08%   |
| Realtek Semiconductor           | 78       | 6.81%   |
| Broadcom                        | 53       | 4.62%   |
| MediaTek                        | 18       | 1.57%   |
| Qualcomm Atheros Communications | 16       | 1.4%    |
| IMC Networks                    | 16       | 1.4%    |
| TP-Link                         | 15       | 1.31%   |
| Apple                           | 14       | 1.22%   |
| Foxconn / Hon Hai               | 10       | 0.87%   |
| Edimax Technology               | 9        | 0.79%   |
| Dynex                           | 6        | 0.52%   |
| Realtek                         | 5        | 0.44%   |
| HTC (High Tech Computer)        | 5        | 0.44%   |
| Lite-On Technology              | 4        | 0.35%   |
| Conwise Technology              | 4        | 0.35%   |
| SINO WEALTH                     | 3        | 0.26%   |
| Integrated System Solution      | 3        | 0.26%   |
| Belkin Components               | 3        | 0.26%   |
| Ralink                          | 2        | 0.17%   |
| Sitecom Europe                  | 1        | 0.09%   |
| Micro Star International        | 1        | 0.09%   |
| D-Link                          | 1        | 0.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 314      | 27.28%  |
| Intel AX200 Bluetooth                                                | 182      | 15.81%  |
| Intel Bluetooth wireless interface                                   | 77       | 6.69%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 64       | 5.56%   |
| Realtek Bluetooth Radio                                              | 61       | 5.3%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 52       | 4.52%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 39       | 3.39%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 35       | 3.04%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 34       | 2.95%   |
| Intel AX201 Bluetooth                                                | 26       | 2.26%   |
| Intel AX210 Bluetooth                                                | 19       | 1.65%   |
| MediaTek Wireless_Device                                             | 18       | 1.56%   |
| ASUS ASUS USB-BT500                                                  | 18       | 1.56%   |
| ASUS Bluetooth Radio                                                 | 17       | 1.48%   |
| TP-Link UB500 Adapter                                                | 15       | 1.3%    |
| ASUS Bluetooth Adapter                                               | 13       | 1.13%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 11       | 0.96%   |
| IMC Networks Bluetooth Radio                                         | 10       | 0.87%   |
| ASUS BCM20702A0                                                      | 10       | 0.87%   |
| Qualcomm Atheros  Bluetooth Device                                   | 7        | 0.61%   |
| Intel Bluetooth Device                                               | 7        | 0.61%   |
| Edimax Bluetooth Adapter                                             | 7        | 0.61%   |
| Apple Bluetooth USB Host Controller                                  | 7        | 0.61%   |
| Foxconn / Hon Hai Wireless_Device                                    | 6        | 0.52%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 6        | 0.52%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 6        | 0.52%   |
| Realtek Bluetooth 5.1 Radio                                          | 5        | 0.43%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 5        | 0.43%   |
| Realtek Bluetooth Radio                                              | 4        | 0.35%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 4        | 0.35%   |
| Conwise CW6622                                                       | 4        | 0.35%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 4        | 0.35%   |
| SINO WEALTH RK Bluetooth Keyboar                                     | 3        | 0.26%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 3        | 0.26%   |
| IMC Networks Wireless_Device                                         | 3        | 0.26%   |
| Broadcom Bluetooth 2.0+eDR dongle                                    | 3        | 0.26%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 3        | 0.26%   |
| Apple Bluetooth HCI MacBookPro (HID mode)                            | 3        | 0.26%   |
| Ralink RT3290 Bluetooth                                              | 2        | 0.17%   |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 2        | 0.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| AMD                       | 1505     | 29.51%  |
| Intel                     | 1297     | 25.43%  |
| Nvidia                    | 1260     | 24.71%  |
| C-Media Electronics       | 185      | 3.63%   |
| Logitech                  | 73       | 1.43%   |
| Creative Labs             | 71       | 1.39%   |
| Kingston Technology       | 50       | 0.98%   |
| Texas Instruments         | 39       | 0.76%   |
| JMTek                     | 39       | 0.76%   |
| Corsair                   | 34       | 0.67%   |
| SteelSeries ApS           | 31       | 0.61%   |
| ASUSTek Computer          | 31       | 0.61%   |
| Creative Technology       | 30       | 0.59%   |
| Razer USA                 | 27       | 0.53%   |
| Blue Microphones          | 26       | 0.51%   |
| Focusrite-Novation        | 25       | 0.49%   |
| Generalplus Technology    | 24       | 0.47%   |
| BEHRINGER International   | 21       | 0.41%   |
| Plantronics               | 15       | 0.29%   |
| Sony                      | 14       | 0.27%   |
| GYROCOM C&C               | 12       | 0.24%   |
| Realtek Semiconductor     | 11       | 0.22%   |
| VIA Technologies          | 9        | 0.18%   |
| Micro Star International  | 9        | 0.18%   |
| M-Audio                   | 9        | 0.18%   |
| GN Netcom                 | 9        | 0.18%   |
| Turtle Beach              | 8        | 0.16%   |
| Samson Technologies       | 8        | 0.16%   |
| RODE Microphones          | 8        | 0.16%   |
| Giga-Byte Technology      | 8        | 0.16%   |
| Audio-Technica            | 8        | 0.16%   |
| XMOS                      | 7        | 0.14%   |
| Sennheiser Communications | 7        | 0.14%   |
| SAVITECH                  | 7        | 0.14%   |
| Dell                      | 7        | 0.14%   |
| Yamaha                    | 6        | 0.12%   |
| Scarlett                  | 6        | 0.12%   |
| Elgato Systems            | 6        | 0.12%   |
| Astro Gaming              | 6        | 0.12%   |
| Valve Software            | 5        | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 457      | 7.63%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 306      | 5.11%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 245      | 4.09%   |
| AMD Family 17h/19h HD Audio Controller                                     | 178      | 2.97%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 176      | 2.94%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 166      | 2.77%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 159      | 2.65%   |
| Intel 200 Series PCH HD Audio                                              | 140      | 2.34%   |
| Nvidia GP104 High Definition Audio Controller                              | 128      | 2.14%   |
| Nvidia GP106 High Definition Audio Controller                              | 126      | 2.1%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 117      | 1.95%   |
| AMD Navi 10 HDMI Audio                                                     | 116      | 1.94%   |
| Nvidia GP107GL High Definition Audio Controller                            | 114      | 1.9%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 112      | 1.87%   |
| Intel Cannon Lake PCH cAVS                                                 | 104      | 1.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 94       | 1.57%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 92       | 1.54%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 78       | 1.3%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 74       | 1.24%   |
| Nvidia TU116 High Definition Audio Controller                              | 72       | 1.2%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 71       | 1.19%   |
| AMD FCH Azalia Controller                                                  | 70       | 1.17%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 65       | 1.08%   |
| Nvidia GM204 High Definition Audio Controller                              | 64       | 1.07%   |
| Nvidia TU104 HD Audio Controller                                           | 62       | 1.03%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 62       | 1.03%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 62       | 1.03%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 59       | 0.98%   |
| Nvidia TU106 High Definition Audio Controller                              | 56       | 0.93%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 53       | 0.88%   |
| Nvidia GA104 High Definition Audio Controller                              | 50       | 0.83%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 47       | 0.78%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 45       | 0.75%   |
| Nvidia GP108 High Definition Audio Controller                              | 44       | 0.73%   |
| Nvidia GM206 High Definition Audio Controller                              | 44       | 0.73%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 42       | 0.7%    |
| Nvidia GK104 HDMI Audio Controller                                         | 41       | 0.68%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 37       | 0.62%   |
| Nvidia GP102 HDMI Audio Controller                                         | 35       | 0.58%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 34       | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Corsair                      | 314      | 18.86%  |
| Kingston                     | 296      | 17.78%  |
| G.Skill                      | 236      | 14.17%  |
| Unknown                      | 198      | 11.89%  |
| Crucial                      | 150      | 9.01%   |
| Samsung Electronics          | 97       | 5.83%   |
| SK hynix                     | 61       | 3.66%   |
| Micron Technology            | 54       | 3.24%   |
| Team                         | 43       | 2.58%   |
| A-DATA Technology            | 42       | 2.52%   |
| Patriot                      | 32       | 1.92%   |
| GOODRAM                      | 12       | 0.72%   |
| Nanya Technology             | 11       | 0.66%   |
| Elpida                       | 10       | 0.6%    |
| Unknown                      | 9        | 0.54%   |
| Ramaxel Technology           | 8        | 0.48%   |
| Unknown (ABCD)               | 7        | 0.42%   |
| Kllisre                      | 5        | 0.3%    |
| GeIL                         | 5        | 0.3%    |
| Transcend                    | 4        | 0.24%   |
| Smart                        | 4        | 0.24%   |
| Silicon Power                | 4        | 0.24%   |
| PNY                          | 4        | 0.24%   |
| AMD                          | 4        | 0.24%   |
| Patriot Memory (PDP Systems) | 3        | 0.18%   |
| Neo Forza                    | 3        | 0.18%   |
| Kingmax                      | 3        | 0.18%   |
| CSX                          | 3        | 0.18%   |
| Apacer                       | 3        | 0.18%   |
| Unknown (08C8)               | 2        | 0.12%   |
| Qumo                         | 2        | 0.12%   |
| Patriot Memory               | 2        | 0.12%   |
| Wilk Elektronik              | 1        | 0.06%   |
| Unknown (AB)                 | 1        | 0.06%   |
| Unknown (0xAD44594E45540000) | 1        | 0.06%   |
| Unknown (0x8551)             | 1        | 0.06%   |
| Unknown (0x0416)             | 1        | 0.06%   |
| TwinMOS                      | 1        | 0.06%   |
| Thermaltake                  | 1        | 0.06%   |
| TEXTORM                      | 1        | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s             | 45       | 2.45%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s             | 32       | 1.74%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s               | 22       | 1.2%    |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                 | 20       | 1.09%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s               | 17       | 0.92%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s              | 17       | 0.92%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s               | 17       | 0.92%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s              | 14       | 0.76%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s                 | 14       | 0.76%   |
| Corsair RAM CMK32GX4M2B3200C16 16384MB DIMM DDR4 3400MT/s         | 14       | 0.76%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                              | 13       | 0.71%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s                | 12       | 0.65%   |
| Patriot RAM 3200 C16 Series 8192MB DIMM DDR4 3266MT/s             | 11       | 0.6%    |
| Unknown RAM Module 4096MB DIMM 1333MT/s                           | 10       | 0.54%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s               | 10       | 0.54%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s             | 10       | 0.54%   |
| A-DATA RAM DDR4 3000 16GB DIMM DDR4 3600MT/s                      | 10       | 0.54%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s            | 9        | 0.49%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s               | 9        | 0.49%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s               | 9        | 0.49%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1800MT/s               | 9        | 0.49%   |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3200MT/s             | 9        | 0.49%   |
| Unknown                                                           | 9        | 0.49%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                         | 8        | 0.44%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s                | 8        | 0.44%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s             | 8        | 0.44%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                           | 7        | 0.38%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 7        | 0.38%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s               | 7        | 0.38%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s             | 7        | 0.38%   |
| G.Skill RAM F4-3200C16-8GVGB 8GB DIMM DDR4 3200MT/s               | 7        | 0.38%   |
| G.Skill RAM F4-3200C16-8GTZR 8GB DIMM DDR4 3200MT/s               | 7        | 0.38%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s            | 7        | 0.38%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                       | 6        | 0.33%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s             | 6        | 0.33%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s               | 6        | 0.33%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s               | 6        | 0.33%   |
| Kingston RAM KHX2666C15D4/4G 4GB DIMM DDR4 3200MT/s               | 6        | 0.33%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s                | 6        | 0.33%   |
| G.Skill RAM F4-3200C14-8GFX 8GB DIMM DDR4 3733MT/s                | 6        | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 871      | 58.14%  |
| DDR3    | 416      | 27.77%  |
| Unknown | 81       | 5.41%   |
| DDR2    | 43       | 2.87%   |
| SDRAM   | 39       | 2.6%    |
| DDR5    | 28       | 1.87%   |
| DDR     | 11       | 0.73%   |
| LPDDR4  | 7        | 0.47%   |
| LPDDR3  | 1        | 0.07%   |
| DRAM    | 1        | 0.07%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 1436     | 96.96%  |
| SODIMM  | 39       | 2.63%   |
| RIMM    | 3        | 0.2%    |
| FB-DIMM | 3        | 0.2%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 713      | 44.01%  |
| 4096  | 326      | 20.12%  |
| 16384 | 312      | 19.26%  |
| 2048  | 144      | 8.89%   |
| 32768 | 81       | 5%      |
| 1024  | 39       | 2.41%   |
| 512   | 4        | 0.25%   |
| 3072  | 1        | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 226      | 13.54%  |
| 3200    | 207      | 12.4%   |
| 3600    | 182      | 10.9%   |
| 1333    | 143      | 8.57%   |
| 2400    | 93       | 5.57%   |
| 2133    | 72       | 4.31%   |
| 2667    | 71       | 4.25%   |
| 3400    | 53       | 3.18%   |
| 1867    | 52       | 3.12%   |
| 3000    | 50       | 3%      |
| 800     | 46       | 2.76%   |
| 3800    | 33       | 1.98%   |
| 3533    | 33       | 1.98%   |
| 1866    | 33       | 1.98%   |
| 667     | 30       | 1.8%    |
| 3866    | 29       | 1.74%   |
| 3733    | 27       | 1.62%   |
| 3466    | 25       | 1.5%    |
| 1800    | 24       | 1.44%   |
| 2933    | 19       | 1.14%   |
| 3266    | 17       | 1.02%   |
| Unknown | 17       | 1.02%   |
| 2666    | 16       | 0.96%   |
| 2800    | 15       | 0.9%    |
| 1066    | 14       | 0.84%   |
| 3666    | 11       | 0.66%   |
| 6000    | 8        | 0.48%   |
| 3534    | 8        | 0.48%   |
| 4800    | 7        | 0.42%   |
| 1334    | 7        | 0.42%   |
| 5200    | 6        | 0.36%   |
| 3334    | 6        | 0.36%   |
| 2448    | 6        | 0.36%   |
| 3100    | 5        | 0.3%    |
| 1067    | 5        | 0.3%    |
| 333     | 5        | 0.3%    |
| 3500    | 4        | 0.24%   |
| 2048    | 4        | 0.24%   |
| 1648    | 4        | 0.24%   |
| 400     | 4        | 0.24%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 47       | 40.52%  |
| Brother Industries    | 22       | 18.97%  |
| Canon                 | 15       | 12.93%  |
| Seiko Epson           | 7        | 6.03%   |
| Samsung Electronics   | 6        | 5.17%   |
| Pantum                | 3        | 2.59%   |
| Apple                 | 3        | 2.59%   |
| Xerox                 | 2        | 1.72%   |
| Ricoh                 | 2        | 1.72%   |
| Prolific Technology   | 2        | 1.72%   |
| Zebra                 | 1        | 0.86%   |
| STMicroelectronics    | 1        | 0.86%   |
| QinHeng Electronics   | 1        | 0.86%   |
| Oki Data              | 1        | 0.86%   |
| Lexmark International | 1        | 0.86%   |
| Graphtec America      | 1        | 0.86%   |
| Dymo-CoStar           | 1        | 0.86%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| HP OfficeJet 5200 series                                  | 4        | 3.42%   |
| HP LaserJet 1300                                          | 3        | 2.56%   |
| Apple Gamesir-T1s 2.0b                                    | 3        | 2.56%   |
| Xerox Phaser 3020                                         | 2        | 1.71%   |
| Seiko Epson L120 Series                                   | 2        | 1.71%   |
| Samsung ML-1640 Series Laser Printer                      | 2        | 1.71%   |
| Prolific PL2305 Parallel Port                             | 2        | 1.71%   |
| HP Officejet 2620 series                                  | 2        | 1.71%   |
| HP DeskJet 4530 series                                    | 2        | 1.71%   |
| HP DeskJet 3630 series                                    | 2        | 1.71%   |
| HP DeskJet 2620 All-in-One Printer                        | 2        | 1.71%   |
| HP DeskJet 2130 series                                    | 2        | 1.71%   |
| HP Color LaserJet Pro M453-4                              | 2        | 1.71%   |
| Canon PIXMA MX340                                         | 2        | 1.71%   |
| Canon PIXMA MG2500 Series                                 | 2        | 1.71%   |
| Canon MG5700 series                                       | 2        | 1.71%   |
| Canon G3010 series                                        | 2        | 1.71%   |
| Brother HL-5370DW series                                  | 2        | 1.71%   |
| Brother DCP-7040                                          | 2        | 1.71%   |
| Zebra ZTC ZC100                                           | 1        | 0.85%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1        | 0.85%   |
| Seiko Epson XP-4100 Series                                | 1        | 0.85%   |
| Seiko Epson Stylus NX230/SX235W Series                    | 1        | 0.85%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]              | 1        | 0.85%   |
| Seiko Epson L805 Series                                   | 1        | 0.85%   |
| Seiko Epson ET-4760 Series                                | 1        | 0.85%   |
| Seiko Epson ET-3850 Series                                | 1        | 0.85%   |
| Samsung ML-1660 Series                                    | 1        | 0.85%   |
| Samsung M2020 Series                                      | 1        | 0.85%   |
| Samsung CLX-3300 Series                                   | 1        | 0.85%   |
| Samsung CLP-310 Color Laser Printer                       | 1        | 0.85%   |
| Ricoh SP 112SU                                            | 1        | 0.85%   |
| Ricoh Printing Support                                    | 1        | 0.85%   |
| QinHeng CH340S                                            | 1        | 0.85%   |
| Pantum P2500W series                                      | 1        | 0.85%   |
| Pantum P2200 series                                       | 1        | 0.85%   |
| Pantum M6500 series                                       | 1        | 0.85%   |
| Oki Data USB Device                                       | 1        | 0.85%   |
| Lexmark International Lexmark MS312dn                     | 1        | 0.85%   |
| HP Smart Install                                          | 1        | 0.85%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 12       | 52.17%  |
| Seiko Epson        | 5        | 21.74%  |
| Hewlett-Packard    | 2        | 8.7%    |
| Visioneer          | 1        | 4.35%   |
| Ultima Electronics | 1        | 4.35%   |
| Mustek Systems     | 1        | 4.35%   |
| AGFA-Gevaert NV    | 1        | 4.35%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 110                                                               | 4        | 17.39%  |
| Canon CanoScan LiDE 220                                                               | 3        | 13.04%  |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 2        | 8.7%    |
| Canon CanoScan LIDE 25                                                                | 2        | 8.7%    |
| Visioneer OneTouch 5300 USB                                                           | 1        | 4.35%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1        | 4.35%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 1        | 4.35%   |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                                          | 1        | 4.35%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]                                     | 1        | 4.35%   |
| Mustek Systems ScanExpress A3 USB 1200 PRO                                            | 1        | 4.35%   |
| HP ScanJet 3500c                                                                      | 1        | 4.35%   |
| HP ScanJet 3400cse                                                                    | 1        | 4.35%   |
| Canon CanoScan LiDE 90                                                                | 1        | 4.35%   |
| Canon CanoScan LiDE 210                                                               | 1        | 4.35%   |
| Canon CanoScan LiDE 120                                                               | 1        | 4.35%   |
| AGFA-Gevaert NV SnapScan e26                                                          | 1        | 4.35%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 259      | 41.31%  |
| Microdia                      | 51       | 8.13%   |
| Microsoft                     | 49       | 7.81%   |
| Samsung Electronics           | 23       | 3.67%   |
| Z-Star Microelectronics       | 20       | 3.19%   |
| Sunplus Innovation Technology | 16       | 2.55%   |
| Creative Technology           | 12       | 1.91%   |
| Apple                         | 11       | 1.75%   |
| MacroSilicon                  | 9        | 1.44%   |
| GEMBIRD                       | 9        | 1.44%   |
| Generalplus Technology        | 8        | 1.28%   |
| Cubeternet                    | 8        | 1.28%   |
| Realtek Semiconductor         | 7        | 1.12%   |
| ARC International             | 7        | 1.12%   |
| LG Electronics                | 6        | 0.96%   |
| Google                        | 6        | 0.96%   |
| Chicony Electronics           | 6        | 0.96%   |
| Valve Software                | 5        | 0.8%    |
| KYE Systems (Mouse Systems)   | 5        | 0.8%    |
| Huawei Technologies           | 5        | 0.8%    |
| Genesys Logic                 | 5        | 0.8%    |
| Aveo Technology               | 5        | 0.8%    |
| 2M UVC CAMERA                 | 5        | 0.8%    |
| Pixart Imaging                | 4        | 0.64%   |
| Jieli Technology              | 4        | 0.64%   |
| Alcor Micro                   | 4        | 0.64%   |
| Xiongmai                      | 3        | 0.48%   |
| WCM_USB                       | 3        | 0.48%   |
| Sunplus IT                    | 3        | 0.48%   |
| Sonix Technology              | 3        | 0.48%   |
| SHENZHEN EMEET TECHNOLOGY     | 3        | 0.48%   |
| Razer USA                     | 3        | 0.48%   |
| Philips (or NXP)              | 3        | 0.48%   |
| Linux Foundation              | 3        | 0.48%   |
| Elgato Systems                | 3        | 0.48%   |
| AVerMedia Technologies        | 3        | 0.48%   |
| Arkmicro Technologies         | 3        | 0.48%   |
| Xiaomi                        | 2        | 0.32%   |
| WaveRider Communications      | 2        | 0.32%   |
| Silicon Motion                | 2        | 0.32%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Logitech Webcam C270                                  | 61       | 9.67%   |
| Logitech HD Pro Webcam C920                           | 48       | 7.61%   |
| Samsung Galaxy series, misc. (MTP mode)               | 23       | 3.65%   |
| Microsoft LifeCam HD-3000                             | 21       | 3.33%   |
| Logitech C922 Pro Stream Webcam                       | 20       | 3.17%   |
| Microdia Webcam Vitade AF                             | 18       | 2.85%   |
| Microdia USB 2.0 Camera                               | 14       | 2.22%   |
| Z-Star Venus USB2.0 Camera                            | 11       | 1.74%   |
| Logitech Webcam C310                                  | 11       | 1.74%   |
| Logitech HD Webcam C615                               | 11       | 1.74%   |
| MacroSilicon USB Video                                | 9        | 1.43%   |
| Logitech C920 PRO HD Webcam                           | 9        | 1.43%   |
| Logitech BRIO Ultra HD Webcam                         | 9        | 1.43%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                       | 9        | 1.43%   |
| Logitech Webcam C930e                                 | 8        | 1.27%   |
| Logitech Webcam C170                                  | 8        | 1.27%   |
| Logitech HD Webcam C525                               | 8        | 1.27%   |
| Sunplus 1080P Webcam                                  | 7        | 1.11%   |
| Microsoft LifeCam VX-2000                             | 6        | 0.95%   |
| Logitech StreamCam                                    | 6        | 0.95%   |
| Logitech HD Webcam C510                               | 6        | 0.95%   |
| Logitech B525 HD Webcam                               | 6        | 0.95%   |
| GEMBIRD USB2.0 PC CAMERA                              | 6        | 0.95%   |
| ARC International Camera                              | 6        | 0.95%   |
| Valve Software 3D Camera                              | 5        | 0.79%   |
| Sunplus papalook AF 925                               | 5        | 0.79%   |
| Microsoft LifeCam Cinema                              | 5        | 0.79%   |
| Logitech Webcam Pro 9000                              | 5        | 0.79%   |
| Logitech HD Webcam C910                               | 5        | 0.79%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 5        | 0.79%   |
| Huawei HiCamera                                       | 5        | 0.79%   |
| 2M UVC CAMERA Web Camera                              | 5        | 0.79%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro                  | 4        | 0.63%   |
| Logitech BRIO 4K Stream Edition                       | 4        | 0.63%   |
| Jieli USB PHY 2.0                                     | 4        | 0.63%   |
| Google Nexus/Pixel Device (MTP + debug)               | 4        | 0.63%   |
| Generalplus 808 Camera #9 (web-cam mode)              | 4        | 0.63%   |
| Creative Live! Cam Chat HD [VF0700/VF0790]            | 4        | 0.63%   |
| Z-Star Vimicro USB Camera (Altair)                    | 3        | 0.48%   |
| Z-Star Integrated Camera                              | 3        | 0.48%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Elan Microelectronics | 3        | 42.86%  |
| STMicroelectronics    | 1        | 14.29%  |
| LighTuning Technology | 1        | 14.29%  |
| Futronic Technology   | 1        | 14.29%  |
| AuthenTec             | 1        | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Elan fingerprint sensor [FeinTech FPS00200] | 3        | 42.86%  |
| STMicroelectronics Fingerprint Reader       | 1        | 14.29%  |
| LighTuning Fingerprint Sensor               | 1        | 14.29%  |
| Futronic FS81 Fingerprint Scanner Module    | 1        | 14.29%  |
| AuthenTec AES1600                           | 1        | 14.29%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Gemalto (was Gemplus)             | 5        | 20.83%  |
| Alcor Micro                       | 5        | 20.83%  |
| VASCO Data Security International | 4        | 16.67%  |
| Realtek Semiconductor             | 4        | 16.67%  |
| OmniKey                           | 2        | 8.33%   |
| Yubico.com                        | 1        | 4.17%   |
| SCM Microsystems                  | 1        | 4.17%   |
| Cherry                            | 1        | 4.17%   |
| BIT4ID                            | 1        | 4.17%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader               | 5        | 20.83%  |
| Realtek Semiconductor Smart Card Reader Interface               | 4        | 16.67%  |
| Alcor Micro AU9540 Smartcard Reader                             | 4        | 16.67%  |
| VASCO Data Security International Digipass 905 SmartCard Reader | 2        | 8.33%   |
| OmniKey 3x21 Smart Card Reader                                  | 2        | 8.33%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                 | 1        | 4.17%   |
| VASCO Data Security International DIGIPASS 920                  | 1        | 4.17%   |
| VASCO Data Security International DIGIPASS 870                  | 1        | 4.17%   |
| SCM Microsystems SCR331 SmartCard Reader                        | 1        | 4.17%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                     | 1        | 4.17%   |
| BIT4ID miniLector EVO                                           | 1        | 4.17%   |
| Alcor Micro Watchdata W 1981                                    | 1        | 4.17%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 2291     | 85.87%  |
| 1     | 340      | 12.74%  |
| 2     | 34       | 1.27%   |
| 3     | 3        | 0.11%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 157      | 39.35%  |
| Graphics card            | 56       | 14.04%  |
| Unassigned class         | 54       | 13.53%  |
| Camera                   | 20       | 5.01%   |
| Multimedia controller    | 15       | 3.76%   |
| Chipcard                 | 15       | 3.76%   |
| Net/ethernet             | 13       | 3.26%   |
| Communication controller | 13       | 3.26%   |
| Sound                    | 12       | 3.01%   |
| Bluetooth                | 10       | 2.51%   |
| Dvb card                 | 9        | 2.26%   |
| Storage/raid             | 6        | 1.5%    |
| Network                  | 6        | 1.5%    |
| Fingerprint reader       | 6        | 1.5%    |
| Storage/ide              | 2        | 0.5%    |
| Video                    | 1        | 0.25%   |
| Tv card                  | 1        | 0.25%   |
| Storage/ata              | 1        | 0.25%   |
| Storage                  | 1        | 0.25%   |
| Modem                    | 1        | 0.25%   |

