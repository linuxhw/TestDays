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

Total: 475

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                                | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| 6.2.15-300.fc38.x86_64                                 | 68       | 18.28%  |
| 6.2.14-300.fc38.x86_64                                 | 46       | 12.37%  |
| 6.2.9-300.fc38.x86_64                                  | 42       | 11.29%  |
| 6.3.8-200.fc38.x86_64                                  | 33       | 8.87%   |
| 6.2.11-300.fc38.x86_64                                 | 32       | 8.6%    |
| 6.3.5-200.fc38.x86_64                                  | 24       | 6.45%   |
| 6.3.4-201.fc38.x86_64                                  | 22       | 5.91%   |
| 6.2.12-300.fc38.x86_64                                 | 22       | 5.91%   |
| 6.3.7-200.fc38.x86_64                                  | 18       | 4.84%   |
| 6.2.13-300.fc38.x86_64                                 | 17       | 4.57%   |
| 6.3.6-200.fc38.x86_64                                  | 13       | 3.49%   |
| 6.2.8-300.fc38.x86_64                                  | 4        | 1.08%   |
| 6.2.6-300.fc38.x86_64                                  | 4        | 1.08%   |
| 6.2.7-300.fc38.x86_64                                  | 3        | 0.81%   |
| 6.3.3-200.fc38.x86_64                                  | 2        | 0.54%   |
| 6.2.2-300.fc38.x86_64                                  | 2        | 0.54%   |
| 6.2.10-300.fc38.x86_64                                 | 2        | 0.54%   |
| 6.2.0-63.fc38.x86_64                                   | 2        | 0.54%   |
| 6.4.0-0.rc5.20230607gta4d7d701.342.vanilla.fc38.x86_64 | 1        | 0.27%   |
| 6.4.0-0.rc2.23.fc39.ppc64le                            | 1        | 0.27%   |
| 6.3.1-200.fc38.x86_64                                  | 1        | 0.27%   |
| 6.2.5-300.fc38.x86_64                                  | 1        | 0.27%   |
| 6.2.3-300.fc38.x86_64                                  | 1        | 0.27%   |
| 6.2.2-301.fc38.x86_64                                  | 1        | 0.27%   |
| 6.2.15-703.inttf.fc38.x86_64                           | 1        | 0.27%   |
| 6.2.1-300.fc38.x86_64                                  | 1        | 0.27%   |
| 6.2.0-0.rc1.14.fc38.x86_64+debug                       | 1        | 0.27%   |
| 6.1.31-200.fc38.x86_64                                 | 1        | 0.27%   |
| 6.1.26-200.fc38.x86_64                                 | 1        | 0.27%   |
| 6.1.18-200.fc37.x86_64                                 | 1        | 0.27%   |
| 6.1.0-0.rc0.20221011git60bb8154d1d7.8.fc38.x86_64      | 1        | 0.27%   |
| 6.0.7-301.fc37.x86_64                                  | 1        | 0.27%   |
| 6.0.0-0.rc6.41.fc38.x86_64                             | 1        | 0.27%   |
| 5.19.7-200.fc36.x86_64                                 | 1        | 0.27%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2.15  | 69       | 18.55%  |
| 6.2.14  | 46       | 12.37%  |
| 6.2.9   | 42       | 11.29%  |
| 6.3.8   | 33       | 8.87%   |
| 6.2.11  | 32       | 8.6%    |
| 6.3.5   | 24       | 6.45%   |
| 6.3.4   | 22       | 5.91%   |
| 6.2.12  | 22       | 5.91%   |
| 6.3.7   | 18       | 4.84%   |
| 6.2.13  | 17       | 4.57%   |
| 6.3.6   | 13       | 3.49%   |
| 6.2.8   | 4        | 1.08%   |
| 6.2.6   | 4        | 1.08%   |
| 6.2.7   | 3        | 0.81%   |
| 6.2.2   | 3        | 0.81%   |
| 6.2.0   | 3        | 0.81%   |
| 6.4.0   | 2        | 0.54%   |
| 6.3.3   | 2        | 0.54%   |
| 6.2.10  | 2        | 0.54%   |
| 6.3.1   | 1        | 0.27%   |
| 6.2.5   | 1        | 0.27%   |
| 6.2.3   | 1        | 0.27%   |
| 6.2.1   | 1        | 0.27%   |
| 6.1.31  | 1        | 0.27%   |
| 6.1.26  | 1        | 0.27%   |
| 6.1.18  | 1        | 0.27%   |
| 6.1.0   | 1        | 0.27%   |
| 6.0.7   | 1        | 0.27%   |
| 6.0.0   | 1        | 0.27%   |
| 5.19.7  | 1        | 0.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2     | 235      | 65.83%  |
| 6.3     | 113      | 31.65%  |
| 6.1     | 4        | 1.12%   |
| 6.4     | 2        | 0.56%   |
| 6.0     | 2        | 0.56%   |
| 5.19    | 1        | 0.28%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 342      | 99.71%  |
| ppc64le | 1        | 0.29%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 252      | 73.26%  |
| KDE5          | 56       | 16.28%  |
| Cinnamon      | 11       | 3.2%    |
| Unknown       | 9        | 2.62%   |
| XFCE          | 4        | 1.16%   |
| X-Cinnamon    | 4        | 1.16%   |
| GNOME Classic | 2        | 0.58%   |
| sway          | 1        | 0.29%   |
| MATE          | 1        | 0.29%   |
| LXQt          | 1        | 0.29%   |
| LXDE          | 1        | 0.29%   |
| KDE           | 1        | 0.29%   |
| Deepin        | 1        | 0.29%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 253      | 73.12%  |
| X11     | 70       | 20.23%  |
| Tty     | 20       | 5.78%   |
| Unknown | 3        | 0.87%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 225      | 65.6%   |
| GDM     | 72       | 20.99%  |
| SDDM    | 26       | 7.58%   |
| LightDM | 19       | 5.54%   |
| LXDM    | 1        | 0.29%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 166      | 47.98%  |
| ru_RU | 21       | 6.07%   |
| en_AU | 20       | 5.78%   |
| en_CA | 17       | 4.91%   |
| pt_BR | 16       | 4.62%   |
| de_DE | 16       | 4.62%   |
| en_GB | 15       | 4.34%   |
| fr_FR | 9        | 2.6%    |
| es_ES | 8        | 2.31%   |
| it_IT | 7        | 2.02%   |
| pl_PL | 5        | 1.45%   |
| es_AR | 5        | 1.45%   |
| es_MX | 3        | 0.87%   |
| es_CO | 3        | 0.87%   |
| tr_TR | 2        | 0.58%   |
| pt_PT | 2        | 0.58%   |
| hr_HR | 2        | 0.58%   |
| fr_CA | 2        | 0.58%   |
| fi_FI | 2        | 0.58%   |
| en_NZ | 2        | 0.58%   |
| de_CH | 2        | 0.58%   |
| de_AT | 2        | 0.58%   |
| zh_TW | 1        | 0.29%   |
| zh_SG | 1        | 0.29%   |
| sv_SE | 1        | 0.29%   |
| pa_IN | 1        | 0.29%   |
| nl_NL | 1        | 0.29%   |
| ja_JP | 1        | 0.29%   |
| hu_HU | 1        | 0.29%   |
| fr_BE | 1        | 0.29%   |
| es_VE | 1        | 0.29%   |
| es_CL | 1        | 0.29%   |
| en_PH | 1        | 0.29%   |
| en_IL | 1        | 0.29%   |
| en_IE | 1        | 0.29%   |
| en_DK | 1        | 0.29%   |
| en_BW | 1        | 0.29%   |
| da_DK | 1        | 0.29%   |
| cs_CZ | 1        | 0.29%   |
| C     | 1        | 0.29%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 241      | 70.06%  |
| BIOS | 103      | 29.94%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Btrfs   | 273      | 79.59%  |
| Ext4    | 54       | 15.74%  |
| Xfs     | 12       | 3.5%    |
| Overlay | 2        | 0.58%   |
| Zfs     | 1        | 0.29%   |
| F2fs    | 1        | 0.29%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 215      | 62.68%  |
| GPT     | 111      | 32.36%  |
| MBR     | 17       | 4.96%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 302      | 87.79%  |
| Yes       | 42       | 12.21%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 285      | 82.85%  |
| Yes       | 59       | 17.15%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 97       | 28.28%  |
| Gigabyte Technology                  | 67       | 19.53%  |
| MSI                                  | 57       | 16.62%  |
| ASRock                               | 31       | 9.04%   |
| Dell                                 | 25       | 7.29%   |
| Hewlett-Packard                      | 19       | 5.54%   |
| Lenovo                               | 9        | 2.62%   |
| Unknown                              | 5        | 1.46%   |
| Itautec                              | 4        | 1.17%   |
| Pegatron                             | 3        | 0.87%   |
| Intel                                | 3        | 0.87%   |
| Acer                                 | 3        | 0.87%   |
| Huanan                               | 2        | 0.58%   |
| HPE                                  | 2        | 0.58%   |
| Biostar                              | 2        | 0.58%   |
| AZW                                  | 2        | 0.58%   |
| Techvision                           | 1        | 0.29%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.29%   |
| PCWare                               | 1        | 0.29%   |
| Kllisre                              | 1        | 0.29%   |
| iRU                                  | 1        | 0.29%   |
| Fujitsu Siemens                      | 1        | 0.29%   |
| Foxconn                              | 1        | 0.29%   |
| Fill By OEM                          | 1        | 0.29%   |
| Colorful Technology                  | 1        | 0.29%   |
| AOpen                                | 1        | 0.29%   |
| AMI                                  | 1        | 0.29%   |
| Alienware                            | 1        | 0.29%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS All Series                            | 5        | 1.46%   |
| Unknown                                    | 5        | 1.46%   |
| MSI MS-7C37                                | 4        | 1.17%   |
| Dell OptiPlex 7010                         | 4        | 1.17%   |
| MSI MS-7B89                                | 3        | 0.87%   |
| Itautec Infoway ST-4265                    | 3        | 0.87%   |
| Gigabyte X570 I AORUS PRO WIFI             | 3        | 0.87%   |
| ASUS ROG STRIX B550-I GAMING               | 3        | 0.87%   |
| ASRock B450M Pro4                          | 3        | 0.87%   |
| MSI MS-7D54                                | 2        | 0.58%   |
| MSI MS-7D43                                | 2        | 0.58%   |
| MSI MS-7C95                                | 2        | 0.58%   |
| MSI MS-7C94                                | 2        | 0.58%   |
| MSI MS-7C84                                | 2        | 0.58%   |
| MSI MS-7C02                                | 2        | 0.58%   |
| MSI MS-7B79                                | 2        | 0.58%   |
| MSI MS-7A39                                | 2        | 0.58%   |
| HP ProDesk 600 G1 SFF                      | 2        | 0.58%   |
| Gigabyte X570S AORUS ELITE AX              | 2        | 0.58%   |
| Gigabyte GA-78LMT-USB3 6.0                 | 2        | 0.58%   |
| Gigabyte B550M DS3H                        | 2        | 0.58%   |
| Gigabyte B550 GAMING X V2                  | 2        | 0.58%   |
| Gigabyte B450 I AORUS PRO WIFI             | 2        | 0.58%   |
| Gigabyte B450 AORUS ELITE                  | 2        | 0.58%   |
| Gigabyte 970A-DS3P                         | 2        | 0.58%   |
| Dell OptiPlex 9020                         | 2        | 0.58%   |
| Dell OptiPlex 3020                         | 2        | 0.58%   |
| ASUS TUF Gaming X570-PRO                   | 2        | 0.58%   |
| ASUS TUF Gaming B550M-PLUS                 | 2        | 0.58%   |
| ASUS ROG ZENITH EXTREME                    | 2        | 0.58%   |
| ASUS PRIME Z490-A                          | 2        | 0.58%   |
| ASUS PRIME H510M-K                         | 2        | 0.58%   |
| ASUS PRIME B550M-A                         | 2        | 0.58%   |
| ASUS PRIME B350M-A                         | 2        | 0.58%   |
| ASUS PRIME A320M-K                         | 2        | 0.58%   |
| ASUS P8Z77-V LK                            | 2        | 0.58%   |
| ASRock H310M-STX                           | 2        | 0.58%   |
| ASRock A320M-HD                            | 2        | 0.58%   |
| Techvision TVI7309X                        | 1        | 0.29%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1        | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 27       | 7.87%   |
| ASUS ROG               | 24       | 7%      |
| Dell OptiPlex          | 17       | 4.96%   |
| ASUS TUF               | 14       | 4.08%   |
| Lenovo ThinkCentre     | 6        | 1.75%   |
| HP Compaq              | 5        | 1.46%   |
| Gigabyte B550M         | 5        | 1.46%   |
| ASUS All               | 5        | 1.46%   |
| Unknown                | 5        | 1.46%   |
| MSI MS-7C37            | 4        | 1.17%   |
| HP EliteDesk           | 4        | 1.17%   |
| Gigabyte X570          | 4        | 1.17%   |
| Gigabyte B450          | 4        | 1.17%   |
| ASRock B450M           | 4        | 1.17%   |
| MSI MS-7B89            | 3        | 0.87%   |
| Itautec Infoway        | 3        | 0.87%   |
| HP ProDesk             | 3        | 0.87%   |
| Gigabyte B550          | 3        | 0.87%   |
| Dell Precision         | 3        | 0.87%   |
| MSI MS-7D54            | 2        | 0.58%   |
| MSI MS-7D43            | 2        | 0.58%   |
| MSI MS-7C95            | 2        | 0.58%   |
| MSI MS-7C94            | 2        | 0.58%   |
| MSI MS-7C84            | 2        | 0.58%   |
| MSI MS-7C02            | 2        | 0.58%   |
| MSI MS-7B79            | 2        | 0.58%   |
| MSI MS-7A39            | 2        | 0.58%   |
| Huanan X79             | 2        | 0.58%   |
| HPE ProLiant           | 2        | 0.58%   |
| HP OMEN                | 2        | 0.58%   |
| Gigabyte Z390          | 2        | 0.58%   |
| Gigabyte Z370          | 2        | 0.58%   |
| Gigabyte X570S         | 2        | 0.58%   |
| Gigabyte H410M         | 2        | 0.58%   |
| Gigabyte H310M         | 2        | 0.58%   |
| Gigabyte GA-78LMT-USB3 | 2        | 0.58%   |
| Gigabyte B560M         | 2        | 0.58%   |
| Gigabyte B450M         | 2        | 0.58%   |
| Gigabyte 970A-DS3P     | 2        | 0.58%   |
| Dell XPS               | 2        | 0.58%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 55       | 16.03%  |
| 2020    | 42       | 12.24%  |
| 2021    | 36       | 10.5%   |
| 2022    | 35       | 10.2%   |
| 2019    | 28       | 8.16%   |
| 2013    | 28       | 8.16%   |
| 2012    | 22       | 6.41%   |
| 2017    | 18       | 5.25%   |
| 2010    | 15       | 4.37%   |
| 2014    | 13       | 3.79%   |
| 2023    | 10       | 2.92%   |
| 2011    | 10       | 2.92%   |
| 2016    | 9        | 2.62%   |
| 2015    | 8        | 2.33%   |
| 2009    | 5        | 1.46%   |
| 2008    | 5        | 1.46%   |
| 2006    | 3        | 0.87%   |
| Unknown | 1        | 0.29%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 343      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 304      | 88.12%  |
| Enabled  | 41       | 11.88%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 343      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 107      | 30.84%  |
| 32.01-64.0      | 89       | 25.65%  |
| 8.01-16.0       | 42       | 12.1%   |
| 4.01-8.0        | 40       | 11.53%  |
| 64.01-256.0     | 34       | 9.8%    |
| 3.01-4.0        | 18       | 5.19%   |
| 24.01-32.0      | 15       | 4.32%   |
| More than 256.0 | 1        | 0.29%   |
| 1.01-2.0        | 1        | 0.29%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 113      | 31.48%  |
| 2.01-3.0   | 98       | 27.3%   |
| 3.01-4.0   | 77       | 21.45%  |
| 1.01-2.0   | 31       | 8.64%   |
| 8.01-16.0  | 22       | 6.13%   |
| 0.51-1.0   | 9        | 2.51%   |
| 16.01-24.0 | 6        | 1.67%   |
| 32.01-64.0 | 3        | 0.84%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 122      | 34.96%  |
| 1      | 108      | 30.95%  |
| 3      | 55       | 15.76%  |
| 4      | 37       | 10.6%   |
| 5      | 15       | 4.3%    |
| 6      | 8        | 2.29%   |
| 11     | 1        | 0.29%   |
| 10     | 1        | 0.29%   |
| 7      | 1        | 0.29%   |
| 0      | 1        | 0.29%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 241      | 70.06%  |
| Yes       | 103      | 29.94%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 340      | 99.13%  |
| No        | 3        | 0.87%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 190      | 55.23%  |
| No        | 154      | 44.77%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 182      | 53.06%  |
| Yes       | 161      | 46.94%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 75       | 21.8%   |
| Brazil      | 28       | 8.14%   |
| Russia      | 22       | 6.4%    |
| Canada      | 20       | 5.81%   |
| Australia   | 20       | 5.81%   |
| Germany     | 16       | 4.65%   |
| France      | 11       | 3.2%    |
| Poland      | 10       | 2.91%   |
| Italy       | 10       | 2.91%   |
| UK          | 9        | 2.62%   |
| Spain       | 7        | 2.03%   |
| Netherlands | 7        | 2.03%   |
| Mexico      | 6        | 1.74%   |
| Hungary     | 6        | 1.74%   |
| Argentina   | 6        | 1.74%   |
| Thailand    | 5        | 1.45%   |
| Sweden      | 5        | 1.45%   |
| Colombia    | 5        | 1.45%   |
| Belarus     | 5        | 1.45%   |
| Norway      | 4        | 1.16%   |
| Austria     | 4        | 1.16%   |
| Turkey      | 3        | 0.87%   |
| Switzerland | 3        | 0.87%   |
| Singapore   | 3        | 0.87%   |
| Serbia      | 3        | 0.87%   |
| Portugal    | 3        | 0.87%   |
| New Zealand | 3        | 0.87%   |
| Finland     | 3        | 0.87%   |
| Chile       | 3        | 0.87%   |
| Belgium     | 3        | 0.87%   |
| Ukraine     | 2        | 0.58%   |
| Taiwan      | 2        | 0.58%   |
| Romania     | 2        | 0.58%   |
| Ireland     | 2        | 0.58%   |
| Indonesia   | 2        | 0.58%   |
| India       | 2        | 0.58%   |
| Greece      | 2        | 0.58%   |
| Czechia     | 2        | 0.58%   |
| Bulgaria    | 2        | 0.58%   |
| Vietnam     | 1        | 0.29%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Sydney         | 14       | 4.03%   |
| Moscow         | 6        | 1.73%   |
| Palmas         | 5        | 1.44%   |
| Minsk          | 5        | 1.44%   |
| Seattle        | 4        | 1.15%   |
| Winnipeg       | 3        | 0.86%   |
| Warsaw         | 3        | 0.86%   |
| Vienna         | 3        | 0.86%   |
| St Petersburg  | 3        | 0.86%   |
| Singapore      | 3        | 0.86%   |
| Sao Paulo      | 3        | 0.86%   |
| Santiago       | 3        | 0.86%   |
| Ottawa         | 3        | 0.86%   |
| Los Angeles    | 3        | 0.86%   |
| Helsinki       | 3        | 0.86%   |
| Budapest       | 3        | 0.86%   |
| Brisbane       | 3        | 0.86%   |
| Bangkok        | 3        | 0.86%   |
| Alliston       | 3        | 0.86%   |
| Woodstock      | 2        | 0.58%   |
| White Rock     | 2        | 0.58%   |
| Toronto        | 2        | 0.58%   |
| Saint Paul     | 2        | 0.58%   |
| Rockville      | 2        | 0.58%   |
| Rochester      | 2        | 0.58%   |
| Rio de Janeiro | 2        | 0.58%   |
| Québec        | 2        | 0.58%   |
| Prague         | 2        | 0.58%   |
| Porto Alegre   | 2        | 0.58%   |
| Odessa         | 2        | 0.58%   |
| Ober-Morlen    | 2        | 0.58%   |
| Manchester     | 2        | 0.58%   |
| Kyiv           | 2        | 0.58%   |
| Kingston       | 2        | 0.58%   |
| Istanbul       | 2        | 0.58%   |
| Irkutsk        | 2        | 0.58%   |
| Flushing       | 2        | 0.58%   |
| Brussels       | 2        | 0.58%   |
| Brasília      | 2        | 0.58%   |
| Bogotá        | 2        | 0.58%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 127      | 210    | 19.1%   |
| WDC                         | 87       | 120    | 13.08%  |
| Seagate                     | 86       | 114    | 12.93%  |
| Sandisk                     | 50       | 59     | 7.52%   |
| Kingston                    | 44       | 46     | 6.62%   |
| Toshiba                     | 37       | 41     | 5.56%   |
| Crucial                     | 37       | 47     | 5.56%   |
| Phison Electronics          | 17       | 27     | 2.56%   |
| Intel                       | 17       | 20     | 2.56%   |
| A-DATA Technology           | 13       | 16     | 1.95%   |
| Hitachi                     | 12       | 18     | 1.8%    |
| Micron/Crucial Technology   | 9        | 10     | 1.35%   |
| Patriot                     | 8        | 10     | 1.2%    |
| Silicon Motion              | 7        | 8      | 1.05%   |
| China                       | 7        | 10     | 1.05%   |
| SPCC                        | 6        | 6      | 0.9%    |
| PNY                         | 6        | 8      | 0.9%    |
| SK hynix                    | 5        | 7      | 0.75%   |
| Netac                       | 5        | 5      | 0.75%   |
| Micron Technology           | 5        | 5      | 0.75%   |
| Kingston Technology Company | 5        | 6      | 0.75%   |
| ADATA Technology            | 4        | 4      | 0.6%    |
| Unknown                     | 3        | 4      | 0.45%   |
| Realtek Semiconductor       | 3        | 6      | 0.45%   |
| MAXIO Technology (Hangzhou) | 3        | 3      | 0.45%   |
| KingSpec                    | 3        | 3      | 0.45%   |
| Intenso                     | 3        | 3      | 0.45%   |
| HGST                        | 3        | 3      | 0.45%   |
| ASMT                        | 3        | 4      | 0.45%   |
| TO Exter                    | 2        | 2      | 0.3%    |
| Seagate Technology          | 2        | 3      | 0.3%    |
| SABRENT                     | 2        | 2      | 0.3%    |
| QNAP                        | 2        | 2      | 0.3%    |
| Maxtor                      | 2        | 2      | 0.3%    |
| GOODRAM                     | 2        | 3      | 0.3%    |
| AMD                         | 2        | 2      | 0.3%    |
| Acer                        | 2        | 4      | 0.3%    |
| Unknown                     | 2        | 3      | 0.3%    |
| Yeestor                     | 1        | 1      | 0.15%   |
| XPG                         | 1        | 1      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB   | 26       | 3.43%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB    | 24       | 3.17%   |
| Crucial CT500MX500SSD1 500GB                          | 12       | 1.59%   |
| Samsung SSD 860 EVO 1TB                               | 9        | 1.19%   |
| Kingston SA400S37120G 120GB SSD                       | 9        | 1.19%   |
| Toshiba DT01ACA100 1TB                                | 8        | 1.06%   |
| Phison E12 NVMe Controller 1TB                        | 8        | 1.06%   |
| Samsung SSD 850 EVO 250GB                             | 7        | 0.92%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB   | 7        | 0.92%   |
| Kingston SA400S37240G 240GB SSD                       | 7        | 0.92%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                      | 6        | 0.79%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 6        | 0.79%   |
| Seagate ST2000DM008-2FR102 2TB                        | 6        | 0.79%   |
| Seagate ST1000DM010-2EP102 1TB                        | 6        | 0.79%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                    | 6        | 0.79%   |
| Samsung SSD 870 EVO 1TB                               | 6        | 0.79%   |
| Samsung SSD 860 EVO 500GB                             | 6        | 0.79%   |
| Toshiba DT01ACA050 500GB                              | 5        | 0.66%   |
| Seagate ST2000DM006-2DM164 2TB                        | 5        | 0.66%   |
| Seagate ST1000DM003-1CH162 1TB                        | 5        | 0.66%   |
| Samsung SSD 860 EVO 250GB                             | 5        | 0.66%   |
| Phison E16 PCIe4 NVMe Controller 1TB                  | 5        | 0.66%   |
| Micron/Crucial P2 NVMe PCIe SSD 4TB                   | 5        | 0.66%   |
| WDC WD10EZEX-60WN4A0 1TB                              | 4        | 0.53%   |
| Seagate ST500DM002-1BD142 500GB                       | 4        | 0.53%   |
| Seagate ST3500418AS 500GB                             | 4        | 0.53%   |
| Seagate ST31000524AS 1TB                              | 4        | 0.53%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB      | 4        | 0.53%   |
| Samsung SSD 980 1TB                                   | 4        | 0.53%   |
| Kingston SV300S37A120G 120GB SSD                      | 4        | 0.53%   |
| Kingston SA400S37480G 480GB SSD                       | 4        | 0.53%   |
| Crucial CT240BX500SSD1 240GB                          | 4        | 0.53%   |
| Crucial CT1000MX500SSD1 1TB                           | 4        | 0.53%   |
| China SSD 120GB                                       | 4        | 0.53%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 3        | 0.4%    |
| WDC WD40EFRX-68N32N0 4TB                              | 3        | 0.4%    |
| WDC WD20EZRX-00D8PB0 2TB                              | 3        | 0.4%    |
| WDC WD10EZEX-08WN4A0 1TB                              | 3        | 0.4%    |
| Toshiba HDWD110 1TB                                   | 3        | 0.4%    |
| Toshiba DT01ACA200 2TB                                | 3        | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 82       | 106    | 37.79%  |
| WDC                 | 71       | 98     | 32.72%  |
| Toshiba             | 31       | 33     | 14.29%  |
| Hitachi             | 12       | 18     | 5.53%   |
| Samsung Electronics | 11       | 11     | 5.07%   |
| HGST                | 3        | 3      | 1.38%   |
| Unknown             | 2        | 2      | 0.92%   |
| QNAP                | 2        | 2      | 0.92%   |
| USB                 | 1        | 1      | 0.46%   |
| Maxtor              | 1        | 1      | 0.46%   |
| ASMT                | 1        | 2      | 0.46%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 66       | 97     | 24.63%  |
| Crucial             | 36       | 44     | 13.43%  |
| Kingston            | 31       | 32     | 11.57%  |
| SanDisk             | 22       | 25     | 8.21%   |
| WDC                 | 19       | 20     | 7.09%   |
| A-DATA Technology   | 13       | 16     | 4.85%   |
| Intel               | 10       | 13     | 3.73%   |
| Patriot             | 8        | 10     | 2.99%   |
| China               | 7        | 10     | 2.61%   |
| SPCC                | 6        | 6      | 2.24%   |
| PNY                 | 6        | 8      | 2.24%   |
| Micron Technology   | 4        | 4      | 1.49%   |
| Toshiba             | 3        | 4      | 1.12%   |
| KingSpec            | 3        | 3      | 1.12%   |
| TO Exter            | 2        | 2      | 0.75%   |
| Netac               | 2        | 2      | 0.75%   |
| GOODRAM             | 2        | 3      | 0.75%   |
| AMD                 | 2        | 2      | 0.75%   |
| Acer                | 2        | 4      | 0.75%   |
| Transcend           | 1        | 1      | 0.37%   |
| TAMMUZ              | 1        | 1      | 0.37%   |
| SK hynix            | 1        | 1      | 0.37%   |
| Seagate             | 1        | 1      | 0.37%   |
| Phison              | 1        | 1      | 0.37%   |
| Palit               | 1        | 1      | 0.37%   |
| OCZ                 | 1        | 3      | 0.37%   |
| Mushkin             | 1        | 1      | 0.37%   |
| Maxtor              | 1        | 1      | 0.37%   |
| LITEON              | 1        | 1      | 0.37%   |
| Lexar               | 1        | 1      | 0.37%   |
| KUIJIA              | 1        | 1      | 0.37%   |
| Kimtigo             | 1        | 1      | 0.37%   |
| Intenso             | 1        | 1      | 0.37%   |
| Gigabyte Technology | 1        | 2      | 0.37%   |
| FORESEE             | 1        | 1      | 0.37%   |
| Fanxiang            | 1        | 1      | 0.37%   |
| Dogfish             | 1        | 1      | 0.37%   |
| Digma               | 1        | 1      | 0.37%   |
| Colorful            | 1        | 1      | 0.37%   |
| ASMT                | 1        | 1      | 0.37%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 220      | 333    | 37.48%  |
| HDD     | 179      | 277    | 30.49%  |
| NVMe    | 176      | 259    | 29.98%  |
| Unknown | 12       | 14     | 2.04%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 285      | 595    | 59.01%  |
| NVMe | 173      | 256    | 35.82%  |
| SAS  | 25       | 32     | 5.18%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 189      | 306    | 45%     |
| 0.51-1.0   | 136      | 180    | 32.38%  |
| 1.01-2.0   | 56       | 71     | 13.33%  |
| 3.01-4.0   | 20       | 24     | 4.76%   |
| 4.01-10.0  | 11       | 18     | 2.62%   |
| 2.01-3.0   | 6        | 6      | 1.43%   |
| 10.01-20.0 | 2        | 5      | 0.48%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 71       | 20.29%  |
| 501-1000       | 66       | 18.86%  |
| 251-500        | 51       | 14.57%  |
| More than 3000 | 45       | 12.86%  |
| 101-250        | 43       | 12.29%  |
| 2001-3000      | 27       | 7.71%   |
| 1-20           | 17       | 4.86%   |
| Unknown        | 13       | 3.71%   |
| 51-100         | 10       | 2.86%   |
| 21-50          | 7        | 2%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 90       | 25.5%   |
| 21-50          | 61       | 17.28%  |
| 501-1000       | 40       | 11.33%  |
| 251-500        | 39       | 11.05%  |
| 51-100         | 37       | 10.48%  |
| 101-250        | 33       | 9.35%   |
| 1001-2000      | 24       | 6.8%    |
| Unknown        | 13       | 3.68%   |
| More than 3000 | 9        | 2.55%   |
| 2001-3000      | 7        | 1.98%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                         | Desktops | Drives | Percent |
|-----------------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB               | 2        | 2      | 5.56%   |
| Intel SSDSC2CT120A3 120GB                     | 2        | 3      | 5.56%   |
| Crucial CT120M500SSD1 120GB                   | 2        | 5      | 5.56%   |
| WDC WDS240G2G0A-00JH30 240GB SSD              | 1        | 1      | 2.78%   |
| WDC WDS100T2G0A-00JH30 1TB SSD                | 1        | 1      | 2.78%   |
| WDC WD5000AADS-00S9B0 500GB                   | 1        | 1      | 2.78%   |
| WDC WD20EZRX-00D8PB0 2TB                      | 1        | 1      | 2.78%   |
| WDC WD10JPVT-60A1YT0 1TB                      | 1        | 1      | 2.78%   |
| WDC WD1002FAEX-00Y9A0 1TB                     | 1        | 1      | 2.78%   |
| Toshiba MQ02ABD100H 1TB                       | 1        | 1      | 2.78%   |
| Toshiba MQ01ABD100 1TB                        | 1        | 1      | 2.78%   |
| Seagate ST9250827AS 250GB                     | 1        | 1      | 2.78%   |
| Seagate ST9160412AS 160GB                     | 1        | 1      | 2.78%   |
| Seagate ST3750528AS 752GB                     | 1        | 1      | 2.78%   |
| Seagate ST3500630NS 500GB                     | 1        | 1      | 2.78%   |
| Seagate ST3500418AS 500GB                     | 1        | 2      | 2.78%   |
| Seagate ST31000524AS 1TB                      | 1        | 1      | 2.78%   |
| Seagate ST2000VX000-1CU164 2TB                | 1        | 1      | 2.78%   |
| Seagate ST2000DM008-2FR102 2TB                | 1        | 1      | 2.78%   |
| Seagate ST1000LX015-1U7172 1TB                | 1        | 1      | 2.78%   |
| Seagate ST1000DX002-2DV162 1TB                | 1        | 1      | 2.78%   |
| SanDisk SSD PLUS 480GB                        | 1        | 1      | 2.78%   |
| SanDisk SSD PLUS 120 GB                       | 1        | 1      | 2.78%   |
| SanDisk SD8SBAT256G1122 256GB SSD             | 1        | 1      | 2.78%   |
| Samsung Electronics SSD 840 EVO 250GB         | 1        | 1      | 2.78%   |
| Samsung Electronics HD322GJ 320GB             | 1        | 1      | 2.78%   |
| Micron Technology MTFDDAK128MAM-1J1 128GB SSD | 1        | 1      | 2.78%   |
| Kingston SA400S37120G 120GB SSD               | 1        | 1      | 2.78%   |
| Intenso SSD 240GB                             | 1        | 1      | 2.78%   |
| Intel SSDSC2KG019T7R 2TB                      | 1        | 1      | 2.78%   |
| Intel SSDSC2BF240A5L 240GB                    | 1        | 1      | 2.78%   |
| A-DATA Technology SX900 256GB SSD             | 1        | 1      | 2.78%   |
| A-DATA Technology SU650 960GB SSD             | 1        | 1      | 2.78%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 11       | 13     | 33.33%  |
| WDC                 | 4        | 6      | 12.12%  |
| Intel               | 4        | 5      | 12.12%  |
| SanDisk             | 3        | 3      | 9.09%   |
| Toshiba             | 2        | 2      | 6.06%   |
| Samsung Electronics | 2        | 2      | 6.06%   |
| Crucial             | 2        | 5      | 6.06%   |
| A-DATA Technology   | 2        | 2      | 6.06%   |
| Micron Technology   | 1        | 1      | 3.03%   |
| Kingston            | 1        | 1      | 3.03%   |
| Intenso             | 1        | 1      | 3.03%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 11       | 13     | 64.71%  |
| WDC                 | 3        | 4      | 17.65%  |
| Toshiba             | 2        | 2      | 11.76%  |
| Samsung Electronics | 1        | 1      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 17       | 20     | 51.52%  |
| SSD  | 16       | 21     | 48.48%  |

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
| Detected | 231      | 575    | 61.6%   |
| Works    | 114      | 267    | 30.4%   |
| Malfunc  | 30       | 41     | 8%      |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 190      | 32.99%  |
| AMD                          | 150      | 26.04%  |
| Samsung Electronics          | 74       | 12.85%  |
| SanDisk                      | 32       | 5.56%   |
| ASMedia Technology           | 19       | 3.3%    |
| Phison Electronics           | 18       | 3.13%   |
| Kingston Technology Company  | 18       | 3.13%   |
| Marvell Technology Group     | 14       | 2.43%   |
| Micron/Crucial Technology    | 10       | 1.74%   |
| Silicon Motion               | 7        | 1.22%   |
| Seagate Technology           | 5        | 0.87%   |
| JMicron Technology           | 5        | 0.87%   |
| SK hynix                     | 4        | 0.69%   |
| ADATA Technology             | 4        | 0.69%   |
| Toshiba America Info Systems | 3        | 0.52%   |
| Realtek Semiconductor        | 3        | 0.52%   |
| Netac Technology             | 3        | 0.52%   |
| MAXIO Technology (Hangzhou)  | 3        | 0.52%   |
| Silicon Image                | 2        | 0.35%   |
| Adaptec                      | 2        | 0.35%   |
| VIA Technologies             | 1        | 0.17%   |
| Union Memory (Shenzhen)      | 1        | 0.17%   |
| ULi Electronics              | 1        | 0.17%   |
| Shenzhen Longsys Electronics | 1        | 0.17%   |
| PMC-Sierra                   | 1        | 0.17%   |
| Micron Technology            | 1        | 0.17%   |
| LSI Logic / Symbios Logic    | 1        | 0.17%   |
| KIOXIA                       | 1        | 0.17%   |
| INNOGRIT                     | 1        | 0.17%   |
| Broadcom / LSI               | 1        | 0.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 78       | 11.8%   |
| AMD 500 Series Chipset SATA Controller                                         | 36       | 5.45%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 32       | 4.84%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 28       | 4.24%   |
| AMD 400 Series Chipset SATA Controller                                         | 27       | 4.08%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 22       | 3.33%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 21       | 3.18%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 19       | 2.87%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 19       | 2.87%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 19       | 2.87%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 18       | 2.72%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 15       | 2.27%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 11       | 1.66%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 11       | 1.66%   |
| Intel Volume Management Device NVMe RAID Controller                            | 10       | 1.51%   |
| Intel SATA Controller [RAID mode]                                              | 10       | 1.51%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 10       | 1.51%   |
| Samsung NVMe SSD Controller 980                                                | 8        | 1.21%   |
| Phison E12 NVMe Controller                                                     | 8        | 1.21%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 8        | 1.21%   |
| AMD FCH SATA Controller D                                                      | 8        | 1.21%   |
| SanDisk Non-Volatile memory controller                                         | 7        | 1.06%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 7        | 1.06%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 7        | 1.06%   |
| Kingston Company FURY Renegade NVMe SSD                                        | 7        | 1.06%   |
| AMD 300 Series Chipset SATA Controller                                         | 7        | 1.06%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 6        | 0.91%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 6        | 0.91%   |
| Phison E16 PCIe4 NVMe Controller                                               | 6        | 0.91%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 6        | 0.91%   |
| Intel Comet Lake PCH-H RAID                                                    | 5        | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 5        | 0.76%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 4        | 0.61%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 4        | 0.61%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 4        | 0.61%   |
| Kingston Company Company Non-Volatile memory controller                        | 4        | 0.61%   |
| Kingston Company NVMe Controller                                               | 4        | 0.61%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                           | 4        | 0.61%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 4        | 0.61%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 3        | 0.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 312      | 56.32%  |
| NVMe | 173      | 31.23%  |
| IDE  | 33       | 5.96%   |
| RAID | 31       | 5.6%    |
| SAS  | 3        | 0.54%   |
| SCSI | 2        | 0.36%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 188      | 54.81%  |
| AMD                      | 154      | 44.9%   |
| PowerNV C1P9S01 REV 1.01 | 1        | 0.29%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 5600X 6-Core Processor          | 15       | 4.37%   |
| AMD Ryzen 5 3600 6-Core Processor           | 10       | 2.92%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 8        | 2.33%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 8        | 2.33%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 7        | 2.04%   |
| AMD Ryzen 9 7950X 16-Core Processor         | 6        | 1.75%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 6        | 1.75%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 6        | 1.75%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 5        | 1.46%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 4        | 1.17%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 4        | 1.17%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 4        | 1.17%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 4        | 1.17%   |
| Intel 12th Gen Core i5-12400F               | 4        | 1.17%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 4        | 1.17%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 4        | 1.17%   |
| AMD Ryzen 7 5700X 8-Core Processor          | 4        | 1.17%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 4        | 1.17%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 3        | 0.87%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 3        | 0.87%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 0.87%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 3        | 0.87%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 3        | 0.87%   |
| Intel Core i5-8500 CPU @ 3.00GHz            | 3        | 0.87%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 3        | 0.87%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 3        | 0.87%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 3        | 0.87%   |
| Intel Core i3-9100F CPU @ 3.60GHz           | 3        | 0.87%   |
| Intel Core i3 CPU 540 @ 3.07GHz             | 3        | 0.87%   |
| Intel 12th Gen Core i7-12700F               | 3        | 0.87%   |
| AMD Ryzen 7 5800X3D 8-Core Processor        | 3        | 0.87%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 3        | 0.87%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 3        | 0.87%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 3        | 0.87%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 3        | 0.87%   |
| AMD FX-6300 Six-Core Processor              | 3        | 0.87%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 2        | 0.58%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 2        | 0.58%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 2        | 0.58%   |
| Intel Core i7-3930K CPU @ 3.20GHz           | 2        | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 54       | 15.74%  |
| AMD Ryzen 5             | 52       | 15.16%  |
| Intel Core i7           | 44       | 12.83%  |
| AMD Ryzen 7             | 36       | 10.5%   |
| Other                   | 32       | 9.33%   |
| AMD Ryzen 9             | 28       | 8.16%   |
| Intel Core i3           | 15       | 4.37%   |
| Intel Xeon              | 14       | 4.08%   |
| AMD FX                  | 11       | 3.21%   |
| Intel Core i9           | 7        | 2.04%   |
| Intel Core 2 Quad       | 6        | 1.75%   |
| Intel Celeron           | 6        | 1.75%   |
| AMD Phenom II X4        | 5        | 1.46%   |
| AMD Ryzen Threadripper  | 4        | 1.17%   |
| AMD Ryzen 3             | 4        | 1.17%   |
| Intel Pentium           | 3        | 0.87%   |
| Intel Core 2 Duo        | 3        | 0.87%   |
| Intel Atom              | 2        | 0.58%   |
| AMD Phenom II X2        | 2        | 0.58%   |
| AMD Athlon              | 2        | 0.58%   |
| AMD A8                  | 2        | 0.58%   |
| Intel Pentium Gold      | 1        | 0.29%   |
| Intel Pentium Dual-Core | 1        | 0.29%   |
| Intel Pentium Dual      | 1        | 0.29%   |
| Intel Genuine           | 1        | 0.29%   |
| AMD Ryzen 5 PRO         | 1        | 0.29%   |
| AMD Phenom II X6        | 1        | 0.29%   |
| AMD Opteron             | 1        | 0.29%   |
| AMD E2                  | 1        | 0.29%   |
| AMD Athlon II X2        | 1        | 0.29%   |
| AMD Athlon 64 X2        | 1        | 0.29%   |
| AMD A4                  | 1        | 0.29%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 111      | 32.36%  |
| 6      | 85       | 24.78%  |
| 8      | 54       | 15.74%  |
| 2      | 40       | 11.66%  |
| 12     | 22       | 6.41%   |
| 16     | 16       | 4.66%   |
| 10     | 6        | 1.75%   |
| 3      | 4        | 1.17%   |
| 24     | 2        | 0.58%   |
| 14     | 2        | 0.58%   |
| 18     | 1        | 0.29%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 341      | 99.42%  |
| 2      | 2        | 0.58%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 242      | 70.55%  |
| 1      | 100      | 29.15%  |
| 4      | 1        | 0.29%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 342      | 99.71%  |
| Unknown        | 1        | 0.29%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 195      | 56.69%  |
| 0x08701021 | 20       | 5.81%   |
| 0x0a20120a | 19       | 5.52%   |
| 0x0800820d | 14       | 4.07%   |
| 0x0a601203 | 11       | 3.2%    |
| 0x0a201016 | 8        | 2.33%   |
| 0x08701030 | 6        | 1.74%   |
| 0x06000822 | 6        | 1.74%   |
| 0x0a50000c | 5        | 1.45%   |
| 0x08108109 | 5        | 1.45%   |
| 0x010000c8 | 5        | 1.45%   |
| 0x0a50000d | 4        | 1.16%   |
| 0x0a201025 | 4        | 1.16%   |
| 0x0800820c | 3        | 0.87%   |
| 0x0a404102 | 2        | 0.58%   |
| 0x0a201205 | 2        | 0.58%   |
| 0x0a201204 | 2        | 0.58%   |
| 0x0a201009 | 2        | 0.58%   |
| 0x08600106 | 2        | 0.58%   |
| 0x08101016 | 2        | 0.58%   |
| 0x08001138 | 2        | 0.58%   |
| 0x08001137 | 2        | 0.58%   |
| 0x0600611a | 2        | 0.58%   |
| 0x06000629 | 2        | 0.58%   |
| 0x010000bf | 2        | 0.58%   |
| 0x010000b6 | 2        | 0.58%   |
| 0x906ea    | 1        | 0.29%   |
| 0x0a601201 | 1        | 0.29%   |
| 0x0a201005 | 1        | 0.29%   |
| 0x0a008203 | 1        | 0.29%   |
| 0x08701013 | 1        | 0.29%   |
| 0x08108102 | 1        | 0.29%   |
| 0x08001126 | 1        | 0.29%   |
| 0x0700010b | 1        | 0.29%   |
| 0x06001119 | 1        | 0.29%   |
| 0x0600110f | 1        | 0.29%   |
| 0x0600081f | 1        | 0.29%   |
| 0x0600081c | 1        | 0.29%   |
| 0x0600063d | 1        | 0.29%   |
| 0x03000014 | 1        | 0.29%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 50       | 14.58%  |
| KabyLake         | 45       | 13.12%  |
| Zen 2            | 30       | 8.75%   |
| Haswell          | 29       | 8.45%   |
| IvyBridge        | 25       | 7.29%   |
| Zen+             | 23       | 6.71%   |
| Alderlake Hybrid | 21       | 6.12%   |
| Unknown          | 17       | 4.96%   |
| CometLake        | 12       | 3.5%    |
| Piledriver       | 10       | 2.92%   |
| Skylake          | 9        | 2.62%   |
| SandyBridge      | 9        | 2.62%   |
| K10              | 9        | 2.62%   |
| Zen              | 8        | 2.33%   |
| Westmere         | 8        | 2.33%   |
| Penryn           | 8        | 2.33%   |
| Icelake          | 8        | 2.33%   |
| Core             | 4        | 1.17%   |
| Bulldozer        | 3        | 0.87%   |
| Bonnell          | 3        | 0.87%   |
| Silvermont       | 2        | 0.58%   |
| Gracemont        | 2        | 0.58%   |
| Excavator        | 2        | 0.58%   |
| Tremont          | 1        | 0.29%   |
| TigerLake        | 1        | 0.29%   |
| Nehalem          | 1        | 0.29%   |
| K8 Hammer        | 1        | 0.29%   |
| K10 Llano        | 1        | 0.29%   |
| Jaguar           | 1        | 0.29%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| AMD                        | 150      | 40%     |
| Nvidia                     | 137      | 36.53%  |
| Intel                      | 86       | 22.93%  |
| Matrox Electronics Systems | 1        | 0.27%   |
| ASPEED Technology          | 1        | 0.27%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 25       | 6.41%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 18       | 4.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 15       | 3.85%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 13       | 3.33%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 11       | 2.82%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 9        | 2.31%   |
| AMD Raphael                                                                 | 9        | 2.31%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 9        | 2.31%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 9        | 2.31%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX]                                    | 8        | 2.05%   |
| Nvidia GT218 [GeForce 210]                                                  | 7        | 1.79%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 7        | 1.79%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 6        | 1.54%   |
| Intel HD Graphics 530                                                       | 6        | 1.54%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 6        | 1.54%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 6        | 1.54%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 5        | 1.28%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 5        | 1.28%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 5        | 1.28%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 5        | 1.28%   |
| Intel HD Graphics 630                                                       | 5        | 1.28%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 5        | 1.28%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 4        | 1.03%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 4        | 1.03%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 4        | 1.03%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 4        | 1.03%   |
| Nvidia GA104 [GeForce RTX 3070 Ti]                                          | 4        | 1.03%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 4        | 1.03%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 3        | 0.77%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 3        | 0.77%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 3        | 0.77%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 3        | 0.77%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 3        | 0.77%   |
| Nvidia GK208B [GeForce GT 730]                                              | 3        | 0.77%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                              | 3        | 0.77%   |
| Nvidia G86 [GeForce 8500 GT]                                                | 3        | 0.77%   |
| Intel Core Processor Integrated Graphics Controller                         | 3        | 0.77%   |
| Intel AlderLake-S GT1                                                       | 3        | 0.77%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 0.77%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 3        | 0.77%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 129      | 37.5%   |
| 1 x Nvidia     | 117      | 34.01%  |
| 1 x Intel      | 59       | 17.15%  |
| Intel + Nvidia | 10       | 2.91%   |
| 2 x AMD        | 8        | 2.33%   |
| Intel + AMD    | 7        | 2.03%   |
| AMD + Nvidia   | 6        | 1.74%   |
| 2 x Nvidia     | 4        | 1.16%   |
| 2 x Intel      | 2        | 0.58%   |
| 1 x Matrox     | 1        | 0.29%   |
| 1 x ASPEED     | 1        | 0.29%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 272      | 79.07%  |
| Proprietary | 62       | 18.02%  |
| Unknown     | 10       | 2.91%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 110      | 31.61%  |
| 7.01-8.0   | 70       | 20.11%  |
| 3.01-4.0   | 36       | 10.34%  |
| 1.01-2.0   | 32       | 9.2%    |
| 8.01-16.0  | 30       | 8.62%   |
| 0.51-1.0   | 26       | 7.47%   |
| 0.01-0.5   | 23       | 6.61%   |
| 5.01-6.0   | 11       | 3.16%   |
| 16.01-24.0 | 7        | 2.01%   |
| 2.01-3.0   | 3        | 0.86%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 68       | 17.48%  |
| Samsung Electronics  | 57       | 14.65%  |
| Dell                 | 56       | 14.4%   |
| Hewlett-Packard      | 21       | 5.4%    |
| Acer                 | 19       | 4.88%   |
| Philips              | 16       | 4.11%   |
| AOC                  | 15       | 3.86%   |
| ASUSTek Computer     | 14       | 3.6%    |
| Ancor Communications | 13       | 3.34%   |
| BenQ                 | 12       | 3.08%   |
| Lenovo               | 9        | 2.31%   |
| Gigabyte Technology  | 7        | 1.8%    |
| ViewSonic            | 6        | 1.54%   |
| Mi                   | 6        | 1.54%   |
| Sceptre Tech         | 5        | 1.29%   |
| MSI                  | 5        | 1.29%   |
| Iiyama               | 5        | 1.29%   |
| Unknown              | 4        | 1.03%   |
| Sony                 | 3        | 0.77%   |
| Fujitsu Siemens      | 3        | 0.77%   |
| Belinea              | 3        | 0.77%   |
| Vestel Elektronik    | 2        | 0.51%   |
| Toshiba              | 2        | 0.51%   |
| TCT                  | 2        | 0.51%   |
| HUAWEI               | 2        | 0.51%   |
| GDH                  | 2        | 0.51%   |
| Eizo                 | 2        | 0.51%   |
| ___                  | 1        | 0.26%   |
| Wacom                | 1        | 0.26%   |
| Vizio                | 1        | 0.26%   |
| Unknown (XXX)        | 1        | 0.26%   |
| SGT                  | 1        | 0.26%   |
| SANYO                | 1        | 0.26%   |
| SAC                  | 1        | 0.26%   |
| PZG                  | 1        | 0.26%   |
| Panasonic            | 1        | 0.26%   |
| NXG                  | 1        | 0.26%   |
| MYS                  | 1        | 0.26%   |
| LYC                  | 1        | 0.26%   |
| JVC                  | 1        | 0.26%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 5        | 1.22%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 4        | 0.98%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 4        | 0.98%   |
| Samsung Electronics LC27G5xT SAM7079 2560x1440 597x336mm 27.0-inch    | 3        | 0.73%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 3        | 0.73%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch        | 3        | 0.73%   |
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x400mm 31.7-inch  | 2        | 0.49%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 2        | 0.49%   |
| TCT DP1080P60 TCT0270 2560x1600 480x270mm 21.7-inch                   | 2        | 0.49%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch     | 2        | 0.49%   |
| Samsung Electronics SE790C SAM0BFD 3440x1440 797x333mm 34.0-inch      | 2        | 0.49%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 2        | 0.49%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 890x500mm 40.2-inch | 2        | 0.49%   |
| Samsung Electronics LC32G7xT SAM7058 2560x1440 698x393mm 31.5-inch    | 2        | 0.49%   |
| Mi Monitor XMI2701 2560x1440 597x335mm 27.0-inch                      | 2        | 0.49%   |
| Lenovo LEN L28u-30 LEN65FA 3840x2160 621x341mm 27.9-inch              | 2        | 0.49%   |
| Lenovo LEN L1711pC LEN13B7 1280x1024 360x300mm 18.4-inch              | 2        | 0.49%   |
| Iiyama PL2530H IVM6133 1920x1080 544x303mm 24.5-inch                  | 2        | 0.49%   |
| Hewlett-Packard Z24n HWP320E 1920x1200 518x324mm 24.1-inch            | 2        | 0.49%   |
| Goldstar ULTRAGEAR GSM5BD3 2560x1440 697x392mm 31.5-inch              | 2        | 0.49%   |
| Goldstar ULTRAGEAR GSM5B7F 2560x1440 597x336mm 27.0-inch              | 2        | 0.49%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 2        | 0.49%   |
| Goldstar IPS FULLHD GSM5AB7 1920x1080 480x270mm 21.7-inch             | 2        | 0.49%   |
| Goldstar HDR WQHD GSM7756 3440x1440 820x346mm 35.0-inch               | 2        | 0.49%   |
| Goldstar HDR QHD GSM5B96 2560x1440 698x392mm 31.5-inch                | 2        | 0.49%   |
| Goldstar E2011 GSM4ED4 1600x900 443x249mm 20.0-inch                   | 2        | 0.49%   |
| Goldstar E2011 GSM4ED3 1600x900 443x249mm 20.0-inch                   | 2        | 0.49%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                | 2        | 0.49%   |
| Gigabyte Technology M32U GBT3204 3840x2160 697x392mm 31.5-inch        | 2        | 0.49%   |
| Dell U3419W DELA12E 3440x1440 800x335mm 34.1-inch                     | 2        | 0.49%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                     | 2        | 0.49%   |
| Dell S2721DGF DEL41D9 2560x1440 597x336mm 27.0-inch                   | 2        | 0.49%   |
| Dell S2522HG DELA1C2 1920x1080 544x303mm 24.5-inch                    | 2        | 0.49%   |
| Dell P1917S DELD091 1280x1024 375x300mm 18.9-inch                     | 2        | 0.49%   |
| Dell E2011H DEL406B 1600x900 443x249mm 20.0-inch                      | 2        | 0.49%   |
| BenQ EX3501R BNQ7F5E 3440x1440 819x346mm 35.0-inch                    | 2        | 0.49%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                      | 2        | 0.49%   |
| Ancor Communications ASUS VX279 ACI27E4 1920x1080 621x341mm 27.9-inch | 2        | 0.49%   |
| ___ LCDTV16 ___9000 1360x768                                          | 1        | 0.24%   |
| Wacom Cintiq 16 WAC1071 1920x1080 344x193mm 15.5-inch                 | 1        | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 144      | 38.2%   |
| 2560x1440 (QHD)    | 64       | 16.98%  |
| 3840x2160 (4K)     | 50       | 13.26%  |
| 3440x1440          | 18       | 4.77%   |
| 1680x1050 (WSXGA+) | 16       | 4.24%   |
| 1280x1024 (SXGA)   | 16       | 4.24%   |
| 1600x900 (HD+)     | 12       | 3.18%   |
| 1366x768 (WXGA)    | 12       | 3.18%   |
| 1440x900 (WXGA+)   | 11       | 2.92%   |
| 2560x1080          | 9        | 2.39%   |
| 1920x1200 (WUXGA)  | 7        | 1.86%   |
| 1360x768           | 5        | 1.33%   |
| 3840x1080          | 2        | 0.53%   |
| 2288x1287          | 2        | 0.53%   |
| 2048x1152          | 2        | 0.53%   |
| 1600x1200          | 2        | 0.53%   |
| 3840x2560          | 1        | 0.27%   |
| 3840x1600          | 1        | 0.27%   |
| 1920x540           | 1        | 0.27%   |
| 1280x960           | 1        | 0.27%   |
| 1024x768 (XGA)     | 1        | 0.27%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 91       | 23.21%  |
| 24      | 57       | 14.54%  |
| 21      | 37       | 9.44%   |
| 23      | 33       | 8.42%   |
| 31      | 32       | 8.16%   |
| 34      | 23       | 5.87%   |
| 19      | 20       | 5.1%    |
| 20      | 15       | 3.83%   |
| 22      | 14       | 3.57%   |
| 18      | 10       | 2.55%   |
| 32      | 7        | 1.79%   |
| 84      | 6        | 1.53%   |
| 72      | 5        | 1.28%   |
| 17      | 5        | 1.28%   |
| 48      | 4        | 1.02%   |
| 35      | 4        | 1.02%   |
| Unknown | 4        | 1.02%   |
| 28      | 3        | 0.77%   |
| 26      | 3        | 0.77%   |
| 25      | 3        | 0.77%   |
| 15      | 3        | 0.77%   |
| 142     | 2        | 0.51%   |
| 54      | 2        | 0.51%   |
| 40      | 2        | 0.51%   |
| 65      | 1        | 0.26%   |
| 63      | 1        | 0.26%   |
| 52      | 1        | 0.26%   |
| 49      | 1        | 0.26%   |
| 42      | 1        | 0.26%   |
| 38      | 1        | 0.26%   |
| 37      | 1        | 0.26%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 159      | 42.51%  |
| 401-500        | 81       | 21.66%  |
| 601-700        | 49       | 13.1%   |
| 701-800        | 30       | 8.02%   |
| 351-400        | 12       | 3.21%   |
| 1501-2000      | 11       | 2.94%   |
| 1001-1500      | 10       | 2.67%   |
| 801-900        | 8        | 2.14%   |
| 301-350        | 7        | 1.87%   |
| Unknown        | 4        | 1.07%   |
| More than 2000 | 2        | 0.53%   |
| 901-1000       | 1        | 0.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 259      | 74%     |
| 16/10 | 38       | 10.86%  |
| 21/9  | 27       | 7.71%   |
| 5/4   | 14       | 4%      |
| 4/3   | 4        | 1.14%   |
| 6/5   | 3        | 0.86%   |
| 32/9  | 2        | 0.57%   |
| 1.00  | 2        | 0.57%   |
| 3/2   | 1        | 0.29%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 107      | 27.65%  |
| 301-350        | 92       | 23.77%  |
| 351-500        | 68       | 17.57%  |
| 151-200        | 50       | 12.92%  |
| 251-300        | 23       | 5.94%   |
| More than 1000 | 21       | 5.43%   |
| 141-150        | 12       | 3.1%    |
| 501-1000       | 7        | 1.81%   |
| Unknown        | 4        | 1.03%   |
| 101-110        | 3        | 0.78%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 208      | 57.62%  |
| 101-120 | 96       | 26.59%  |
| 121-160 | 25       | 6.93%   |
| 1-50    | 18       | 4.99%   |
| 161-240 | 10       | 2.77%   |
| Unknown | 4        | 1.11%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 252      | 73.47%  |
| 2     | 75       | 21.87%  |
| 0     | 9        | 2.62%   |
| 3     | 6        | 1.75%   |
| 4     | 1        | 0.29%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 215      | 42.24%  |
| Intel                                  | 167      | 32.81%  |
| Qualcomm Atheros                       | 26       | 5.11%   |
| MediaTek                               | 17       | 3.34%   |
| Broadcom                               | 13       | 2.55%   |
| TP-Link                                | 10       | 1.96%   |
| Aquantia                               | 8        | 1.57%   |
| Ralink Technology                      | 7        | 1.38%   |
| Ralink                                 | 7        | 1.38%   |
| Microsoft                              | 7        | 1.38%   |
| Qualcomm Atheros Communications        | 4        | 0.79%   |
| Marvell Technology Group               | 3        | 0.59%   |
| Wilocity                               | 2        | 0.39%   |
| Samsung Electronics                    | 2        | 0.39%   |
| NetGear                                | 2        | 0.39%   |
| Mellanox Technologies                  | 2        | 0.39%   |
| ICS Advent                             | 2        | 0.39%   |
| D-Link                                 | 2        | 0.39%   |
| ASUSTek Computer                       | 2        | 0.39%   |
| Xiaomi                                 | 1        | 0.2%    |
| Sony Ericsson Mobile Communications AB | 1        | 0.2%    |
| Motorola PCS                           | 1        | 0.2%    |
| Microchip Technology                   | 1        | 0.2%    |
| MCS                                    | 1        | 0.2%    |
| HMD Global                             | 1        | 0.2%    |
| DisplayLink                            | 1        | 0.2%    |
| Belkin Components                      | 1        | 0.2%    |
| AVM                                    | 1        | 0.2%    |
| ASIX Electronics                       | 1        | 0.2%    |
| 3Com                                   | 1        | 0.2%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 166      | 27.9%   |
| Intel Wi-Fi 6 AX200                                                 | 37       | 6.22%   |
| Realtek RTL8125 2.5GbE Controller                                   | 32       | 5.38%   |
| Intel Ethernet Controller I225-V                                    | 29       | 4.87%   |
| Intel I211 Gigabit Network Connection                               | 19       | 3.19%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 13       | 2.18%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 12       | 2.02%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 10       | 1.68%   |
| Intel Alder Lake-S PCH CNVi WiFi                                    | 10       | 1.68%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                             | 8        | 1.34%   |
| Intel Ethernet Connection (2) I219-V                                | 7        | 1.18%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter       | 6        | 1.01%   |
| Intel Ethernet Connection I217-LM                                   | 6        | 1.01%   |
| Intel Ethernet Connection (7) I219-V                                | 6        | 1.01%   |
| Intel Ethernet Connection (14) I219-V                               | 6        | 1.01%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 5        | 0.84%   |
| Microsoft Xbox Wireless Adapter for Windows                         | 5        | 0.84%   |
| Intel Ethernet Connection I217-V                                    | 5        | 0.84%   |
| Intel Ethernet Connection (2) I218-V                                | 5        | 0.84%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 5        | 0.84%   |
| Realtek 802.11ac NIC                                                | 4        | 0.67%   |
| Ralink RT2800 802.11n PCI                                           | 4        | 0.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 4        | 0.67%   |
| Intel Ethernet Connection (2) I219-LM                               | 4        | 0.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                     | 4        | 0.67%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                  | 4        | 0.67%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                 | 3        | 0.5%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter               | 3        | 0.5%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                 | 3        | 0.5%    |
| Realtek Killer E3000 2.5GbE Controller                              | 3        | 0.5%    |
| Ralink MT7601U Wireless Adapter                                     | 3        | 0.5%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter          | 3        | 0.5%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter          | 3        | 0.5%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter       | 3        | 0.5%    |
| Intel Wireless-AC 9260                                              | 3        | 0.5%    |
| Intel Wireless 3165                                                 | 3        | 0.5%    |
| Intel Ethernet Connection (7) I219-LM                               | 3        | 0.5%    |
| Intel Centrino Wireless-N 2230                                      | 3        | 0.5%    |
| Intel 82567LM-3 Gigabit Network Connection                          | 3        | 0.5%    |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                  | 2        | 0.34%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 92       | 45.1%   |
| Realtek Semiconductor           | 29       | 14.22%  |
| Qualcomm Atheros                | 18       | 8.82%   |
| MediaTek                        | 17       | 8.33%   |
| TP-Link                         | 10       | 4.9%    |
| Ralink Technology               | 7        | 3.43%   |
| Ralink                          | 7        | 3.43%   |
| Microsoft                       | 7        | 3.43%   |
| Broadcom                        | 5        | 2.45%   |
| Qualcomm Atheros Communications | 4        | 1.96%   |
| Wilocity                        | 2        | 0.98%   |
| NetGear                         | 2        | 0.98%   |
| ASUSTek Computer                | 2        | 0.98%   |
| Belkin Components               | 1        | 0.49%   |
| AVM                             | 1        | 0.49%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                | Desktops | Percent |
|--------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                  | 37       | 17.96%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                               | 13       | 6.31%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                     | 10       | 4.85%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                     | 10       | 4.85%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                              | 8        | 3.88%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                        | 6        | 2.91%   |
| Microsoft Xbox Wireless Adapter for Windows                                          | 5        | 2.43%   |
| Realtek 802.11ac NIC                                                                 | 4        | 1.94%   |
| Ralink RT2800 802.11n PCI                                                            | 4        | 1.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                           | 4        | 1.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                                      | 4        | 1.94%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                   | 4        | 1.94%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                  | 3        | 1.46%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                | 3        | 1.46%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 3        | 1.46%   |
| Ralink MT7601U Wireless Adapter                                                      | 3        | 1.46%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                           | 3        | 1.46%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                           | 3        | 1.46%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                        | 3        | 1.46%   |
| Intel Wireless-AC 9260                                                               | 3        | 1.46%   |
| Intel Wireless 3165                                                                  | 3        | 1.46%   |
| Intel Centrino Wireless-N 2230                                                       | 3        | 1.46%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                                   | 2        | 0.97%   |
| TP-Link Archer T4U ver.3                                                             | 2        | 0.97%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                   | 2        | 0.97%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                             | 2        | 0.97%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                             | 2        | 0.97%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                             | 2        | 0.97%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                               | 2        | 0.97%   |
| Ralink RT5372 Wireless Adapter                                                       | 2        | 0.97%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                            | 2        | 0.97%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 2        | 0.97%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                     | 2        | 0.97%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                       | 2        | 0.97%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]                          | 2        | 0.97%   |
| Microsoft Wireless XBox Controller Dongle                                            | 2        | 0.97%   |
| Intel Tiger Lake PCH CNVi WiFi                                                       | 2        | 0.97%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                                | 1        | 0.49%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                  | 1        | 0.49%   |
| TP-Link 802.11n NIC                                                                  | 1        | 0.49%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 206      | 54.79%  |
| Intel                                  | 127      | 33.78%  |
| Qualcomm Atheros                       | 9        | 2.39%   |
| Broadcom                               | 8        | 2.13%   |
| Aquantia                               | 8        | 2.13%   |
| Marvell Technology Group               | 3        | 0.8%    |
| Samsung Electronics                    | 2        | 0.53%   |
| Mellanox Technologies                  | 2        | 0.53%   |
| ICS Advent                             | 2        | 0.53%   |
| D-Link                                 | 2        | 0.53%   |
| Xiaomi                                 | 1        | 0.27%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.27%   |
| Motorola PCS                           | 1        | 0.27%   |
| HMD Global                             | 1        | 0.27%   |
| DisplayLink                            | 1        | 0.27%   |
| ASIX Electronics                       | 1        | 0.27%   |
| 3Com                                   | 1        | 0.27%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 166      | 42.89%  |
| Realtek RTL8125 2.5GbE Controller                                   | 32       | 8.27%   |
| Intel Ethernet Controller I225-V                                    | 29       | 7.49%   |
| Intel I211 Gigabit Network Connection                               | 19       | 4.91%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 12       | 3.1%    |
| Intel Ethernet Connection (2) I219-V                                | 7        | 1.81%   |
| Intel Ethernet Connection I217-LM                                   | 6        | 1.55%   |
| Intel Ethernet Connection (7) I219-V                                | 6        | 1.55%   |
| Intel Ethernet Connection (14) I219-V                               | 6        | 1.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 5        | 1.29%   |
| Intel Ethernet Connection I217-V                                    | 5        | 1.29%   |
| Intel Ethernet Connection (2) I218-V                                | 5        | 1.29%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 5        | 1.29%   |
| Intel Ethernet Connection (2) I219-LM                               | 4        | 1.03%   |
| Realtek Killer E3000 2.5GbE Controller                              | 3        | 0.78%   |
| Intel Ethernet Connection (7) I219-LM                               | 3        | 0.78%   |
| Intel 82567LM-3 Gigabit Network Connection                          | 3        | 0.78%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 2        | 0.52%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                     | 2        | 0.52%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 2        | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 2        | 0.52%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                   | 2        | 0.52%   |
| Intel Ethernet Connection (17) I219-V                               | 2        | 0.52%   |
| Intel 82579V Gigabit Network Connection                             | 2        | 0.52%   |
| Intel 82575EB Gigabit Network Connection                            | 2        | 0.52%   |
| Intel 82574L Gigabit Network Connection                             | 2        | 0.52%   |
| Intel 82546GB Gigabit Ethernet Controller                           | 2        | 0.52%   |
| ICS Advent DM9601 Fast Ethernet Adapter                             | 2        | 0.52%   |
| D-Link DUB-1312 Gigabit Ethernet Adapter                            | 2        | 0.52%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                    | 2        | 0.52%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                    | 2        | 0.52%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                    | 2        | 0.52%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 2        | 0.52%   |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 1        | 0.26%   |
| Sony Ericsson Mobile AB G3311                                       | 1        | 0.26%   |
| Realtek USB 10/100/1G/2.5G LAN                                      | 1        | 0.26%   |
| Realtek RTL8152 Fast Ethernet Adapter                               | 1        | 0.26%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter               | 1        | 0.26%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                    | 1        | 0.26%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller           | 1        | 0.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 338      | 63.65%  |
| WiFi     | 191      | 35.97%  |
| Modem    | 2        | 0.38%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 256      | 69.38%  |
| WiFi     | 113      | 30.62%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 172      | 50%     |
| 2     | 142      | 41.28%  |
| 3     | 20       | 5.81%   |
| 4     | 6        | 1.74%   |
| 0     | 2        | 0.58%   |
| 6     | 1        | 0.29%   |
| 5     | 1        | 0.29%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 243      | 70.23%  |
| Yes  | 103      | 29.77%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 87       | 52.41%  |
| Cambridge Silicon Radio         | 22       | 13.25%  |
| Realtek Semiconductor           | 11       | 6.63%   |
| MediaTek                        | 10       | 6.02%   |
| Broadcom                        | 7        | 4.22%   |
| IMC Networks                    | 6        | 3.61%   |
| ASUSTek Computer                | 6        | 3.61%   |
| Qualcomm Atheros Communications | 5        | 3.01%   |
| TP-Link                         | 3        | 1.81%   |
| Foxconn / Hon Hai               | 3        | 1.81%   |
| Lite-On Technology              | 2        | 1.2%    |
| Unknown                         | 2        | 1.2%    |
| Foxconn International           | 1        | 0.6%    |
| D-Link                          | 1        | 0.6%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                 | 36       | 21.69%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 22       | 13.25%  |
| Intel AX210 Bluetooth                                 | 13       | 7.83%   |
| MediaTek Wireless_Device                              | 10       | 6.02%   |
| Intel Wireless-AC 3168 Bluetooth                      | 10       | 6.02%   |
| Realtek Bluetooth Radio                               | 9        | 5.42%   |
| Intel AX201 Bluetooth                                 | 9        | 5.42%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 6        | 3.61%   |
| Qualcomm Atheros  Bluetooth Device                    | 4        | 2.41%   |
| Intel Bluetooth wireless interface                    | 4        | 2.41%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 4        | 2.41%   |
| TP-Link UB500 Adapter                                 | 3        | 1.81%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 3        | 1.81%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 3        | 1.81%   |
| Intel Bluetooth Device                                | 3        | 1.81%   |
| IMC Networks Wireless_Device                          | 3        | 1.81%   |
| Foxconn / Hon Hai Wireless_Device                     | 3        | 1.81%   |
| Realtek  Bluetooth 4.2 Adapter                        | 2        | 1.2%    |
| IMC Networks Bluetooth Device                         | 2        | 1.2%    |
| Broadcom Bluetooth 3.0 USB Dongle                     | 2        | 1.2%    |
| ASUS Bluetooth Device                                 | 2        | 1.2%    |
| Unknown                                               | 2        | 1.2%    |
| Qualcomm Atheros AR9462 Bluetooth                     | 1        | 0.6%    |
| Lite-On Bluetooth Radio                               | 1        | 0.6%    |
| Lite-On Atheros AR3012 Bluetooth                      | 1        | 0.6%    |
| IMC Networks Bluetooth Radio                          | 1        | 0.6%    |
| Foxconn International BCM43142A0 Bluetooth module     | 1        | 0.6%    |
| D-Link DBT-122 Bluetooth adapter                      | 1        | 0.6%    |
| Broadcom BCM2070B0                                    | 1        | 0.6%    |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 0.6%    |
| ASUS Bluetooth Radio                                  | 1        | 0.6%    |
| ASUS Bluetooth Adapter                                | 1        | 0.6%    |
| ASUS ASUS USB-BT500                                   | 1        | 0.6%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| AMD                                          | 196      | 30.25%  |
| Intel                                        | 179      | 27.62%  |
| Nvidia                                       | 131      | 20.22%  |
| C-Media Electronics                          | 22       | 3.4%    |
| Logitech                                     | 9        | 1.39%   |
| ASUSTek Computer                             | 9        | 1.39%   |
| Kingston Technology                          | 6        | 0.93%   |
| Generalplus Technology                       | 6        | 0.93%   |
| SteelSeries ApS                              | 5        | 0.77%   |
| Micro Star International                     | 5        | 0.77%   |
| JMTek                                        | 5        | 0.77%   |
| Creative Technology                          | 5        | 0.77%   |
| Razer USA                                    | 4        | 0.62%   |
| Focusrite-Novation                           | 4        | 0.62%   |
| Creative Labs                                | 4        | 0.62%   |
| RODE Microphones                             | 3        | 0.46%   |
| Realtek Semiconductor                        | 3        | 0.46%   |
| Corsair                                      | 3        | 0.46%   |
| Zoran Co. Personal Media Division (Nogatech) | 2        | 0.31%   |
| Yamaha                                       | 2        | 0.31%   |
| Texas Instruments                            | 2        | 0.31%   |
| Scarlett                                     | 2        | 0.31%   |
| Samson Technologies                          | 2        | 0.31%   |
| JBL                                          | 2        | 0.31%   |
| Hewlett-Packard                              | 2        | 0.31%   |
| FIFINE Microphones                           | 2        | 0.31%   |
| XMOS                                         | 1        | 0.15%   |
| Weltrend Semiconductor                       | 1        | 0.15%   |
| Vitana                                       | 1        | 0.15%   |
| VIA Technologies                             | 1        | 0.15%   |
| Unknown                                      | 1        | 0.15%   |
| Universal Audio                              | 1        | 0.15%   |
| ULi Electronics                              | 1        | 0.15%   |
| Trust                                        | 1        | 0.15%   |
| Tenx Technology                              | 1        | 0.15%   |
| Sony                                         | 1        | 0.15%   |
| Solid State Logic                            | 1        | 0.15%   |
| Schiit Audio                                 | 1        | 0.15%   |
| Plantronics                                  | 1        | 0.15%   |
| miniDSP                                      | 1        | 0.15%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 67       | 8.68%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 44       | 5.7%    |
| AMD Family 17h/19h HD Audio Controller                                     | 27       | 3.5%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 26       | 3.37%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 23       | 2.98%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 23       | 2.98%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 22       | 2.85%   |
| Intel 200 Series PCH HD Audio                                              | 21       | 2.72%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 20       | 2.59%   |
| Intel Cannon Lake PCH cAVS                                                 | 19       | 2.46%   |
| Nvidia GA104 High Definition Audio Controller                              | 18       | 2.33%   |
| Intel Alder Lake-S HD Audio Controller                                     | 17       | 2.2%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 16       | 2.07%   |
| Nvidia GP107GL High Definition Audio Controller                            | 13       | 1.68%   |
| Nvidia TU116 High Definition Audio Controller                              | 11       | 1.42%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 11       | 1.42%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 10       | 1.3%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 10       | 1.3%    |
| AMD Navi 10 HDMI Audio                                                     | 10       | 1.3%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 10       | 1.3%    |
| Nvidia GP104 High Definition Audio Controller                              | 9        | 1.17%   |
| Nvidia GA106 High Definition Audio Controller                              | 9        | 1.17%   |
| ASUSTek Computer USB Audio                                                 | 9        | 1.17%   |
| Nvidia High Definition Audio Controller                                    | 8        | 1.04%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8        | 1.04%   |
| AMD Navi 31 [Radeon RX 7000 HDMI Audio]                                    | 8        | 1.04%   |
| Nvidia GP108 High Definition Audio Controller                              | 7        | 0.91%   |
| Nvidia GP106 High Definition Audio Controller                              | 7        | 0.91%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7        | 0.91%   |
| C-Media Electronics USB Audio Device                                       | 7        | 0.91%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 6        | 0.78%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 6        | 0.78%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 6        | 0.78%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6        | 0.78%   |
| Generalplus Technology USB Audio Device                                    | 6        | 0.78%   |
| Nvidia TU104 HD Audio Controller                                           | 5        | 0.65%   |
| Micro Star International USB Audio                                         | 5        | 0.65%   |
| Kingston Technology HyperX 7.1 Audio                                       | 5        | 0.65%   |
| Intel Comet Lake PCH cAVS                                                  | 5        | 0.65%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4        | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 25       | 17.12%  |
| Kingston            | 23       | 15.75%  |
| G.Skill             | 19       | 13.01%  |
| Unknown             | 12       | 8.22%   |
| Samsung Electronics | 11       | 7.53%   |
| Crucial             | 11       | 7.53%   |
| A-DATA Technology   | 8        | 5.48%   |
| SK hynix            | 7        | 4.79%   |
| Smart               | 5        | 3.42%   |
| Micron Technology   | 4        | 2.74%   |
| Team                | 3        | 2.05%   |
| Apacer              | 2        | 1.37%   |
| Unknown             | 2        | 1.37%   |
| Unknown (0x0E9D)    | 1        | 0.68%   |
| Timetec             | 1        | 0.68%   |
| Silicon Power       | 1        | 0.68%   |
| Ramaxel Technology  | 1        | 0.68%   |
| Qumo                | 1        | 0.68%   |
| PNY                 | 1        | 0.68%   |
| Nanya Technology    | 1        | 0.68%   |
| Lexar               | 1        | 0.68%   |
| GOODRAM             | 1        | 0.68%   |
| GIGA-BYTE           | 1        | 0.68%   |
| EVGA                | 1        | 0.68%   |
| CSX                 | 1        | 0.68%   |
| AMD                 | 1        | 0.68%   |
| 89450000830B        | 1        | 0.68%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| Smart RAM SH564128FH8N0TNSDR 4GB DIMM DDR3 1600MT/s              | 4        | 2.48%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s           | 3        | 1.86%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s         | 3        | 1.86%   |
| SK hynix RAM HMT112U6TFR8C-H9 1GB DIMM DDR3 1333MT/s             | 2        | 1.24%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s              | 2        | 1.24%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s             | 2        | 1.24%   |
| Kingston RAM 99U5471-001.A01LF 2GB DIMM DDR3 1333MT/s            | 2        | 1.24%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 2        | 1.24%   |
| A-DATA RAM DDR4 3600 16GB DIMM DDR4 3800MT/s                     | 2        | 1.24%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s                      | 2        | 1.24%   |
| Unknown                                                          | 2        | 1.24%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                             | 1        | 0.62%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1        | 0.62%   |
| Unknown RAM Module 4GB DIMM 400MT/s                              | 1        | 0.62%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 1        | 0.62%   |
| Unknown RAM Module 2GB DIMM DDR3 1067MT/s                        | 1        | 0.62%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                         | 1        | 0.62%   |
| Unknown RAM Module 2GB DIMM DDR2 1067MT/s                        | 1        | 0.62%   |
| Unknown RAM Module 2GB DIMM 667MT/s                              | 1        | 0.62%   |
| Unknown RAM Module 2GB DIMM 533MT/s                              | 1        | 0.62%   |
| Unknown RAM Module 2GB DIMM 400MT/s                              | 1        | 0.62%   |
| Unknown RAM Module 1GB DIMM DDR 333MT/s                          | 1        | 0.62%   |
| Unknown RAM 3600 C20 Series 32GB DIMM DDR4 3666MT/s              | 1        | 0.62%   |
| Unknown (0x0E9D) RAM KINSOTIN8GB2666MHZ 8GB SODIMM DDR4 2667MT/s | 1        | 0.62%   |
| Timetec RAM SD3-1600 8GB SODIMM DDR3 1600MT/s                    | 1        | 0.62%   |
| Team RAM UD5-5600 16GB DIMM DDR5 12800MT/s                       | 1        | 0.62%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s               | 1        | 0.62%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s               | 1        | 0.62%   |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s              | 1        | 0.62%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 1        | 0.62%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2667MT/s                    | 1        | 0.62%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s             | 1        | 0.62%   |
| SK hynix RAM HMCG88MEBSA095N 32GB SODIMM DDR5 4800MT/s           | 1        | 0.62%   |
| SK hynix RAM HMA81GU6DJR8N-XN 8GB DIMM DDR4 3200MT/s             | 1        | 0.62%   |
| SK hynix RAM HMA81GS6MFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 1        | 0.62%   |
| SK hynix RAM 9905471-006.A00LF 4GB DIMM DDR3 1333MT/s            | 1        | 0.62%   |
| Silicon Power RAM Module 8GB DIMM DDR4 3200MT/s                  | 1        | 0.62%   |
| Samsung RAM M393B5773CH0-CH9 2GB DIMM DDR3 1333MT/s              | 1        | 0.62%   |
| Samsung RAM M393B5170GB0-CH9 4GB DIMM DDR3 1333MT/s              | 1        | 0.62%   |
| Samsung RAM M393B1K70DH0 8GB DIMM DDR3 1333MT/s                  | 1        | 0.62%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 72       | 55.81%  |
| DDR3    | 32       | 24.81%  |
| DDR5    | 10       | 7.75%   |
| DDR2    | 5        | 3.88%   |
| Unknown | 5        | 3.88%   |
| SDRAM   | 4        | 3.1%    |
| DDR     | 1        | 0.78%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 117      | 92.13%  |
| SODIMM | 10       | 7.87%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 52       | 36.62%  |
| 16384 | 28       | 19.72%  |
| 4096  | 23       | 16.2%   |
| 32768 | 17       | 11.97%  |
| 2048  | 16       | 11.27%  |
| 1024  | 6        | 4.23%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 28       | 19.18%  |
| 1600    | 20       | 13.7%   |
| 3600    | 15       | 10.27%  |
| 2667    | 8        | 5.48%   |
| 1333    | 8        | 5.48%   |
| 2400    | 6        | 4.11%   |
| 2133    | 6        | 4.11%   |
| 3800    | 5        | 3.42%   |
| 4800    | 4        | 2.74%   |
| 1866    | 4        | 2.74%   |
| 667     | 4        | 2.74%   |
| 3534    | 3        | 2.05%   |
| 3400    | 3        | 2.05%   |
| 5200    | 2        | 1.37%   |
| 3000    | 2        | 1.37%   |
| 2800    | 2        | 1.37%   |
| 2666    | 2        | 1.37%   |
| 1867    | 2        | 1.37%   |
| 1639    | 2        | 1.37%   |
| 1400    | 2        | 1.37%   |
| 1067    | 2        | 1.37%   |
| 800     | 2        | 1.37%   |
| 400     | 2        | 1.37%   |
| 12800   | 1        | 0.68%   |
| 6400    | 1        | 0.68%   |
| 6000    | 1        | 0.68%   |
| 5800    | 1        | 0.68%   |
| 3933    | 1        | 0.68%   |
| 3733    | 1        | 0.68%   |
| 3666    | 1        | 0.68%   |
| 3334    | 1        | 0.68%   |
| 1800    | 1        | 0.68%   |
| 533     | 1        | 0.68%   |
| 333     | 1        | 0.68%   |
| Unknown | 1        | 0.68%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Hewlett-Packard    | 7        | 58.33%  |
| Seiko Epson        | 2        | 16.67%  |
| Brother Industries | 2        | 16.67%  |
| Dymo-CoStar        | 1        | 8.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Seiko Epson WF-2860 Series             | 1        | 8.33%   |
| Seiko Epson L120 Series                | 1        | 8.33%   |
| HP LaserJet Professional P1102w        | 1        | 8.33%   |
| HP LaserJet 1020                       | 1        | 8.33%   |
| HP LaserJet 1010                       | 1        | 8.33%   |
| HP ENVY Inspire 7200 series            | 1        | 8.33%   |
| HP ENVY 5000 series                    | 1        | 8.33%   |
| HP DeskJet 3700 series                 | 1        | 8.33%   |
| HP Deskjet 2050 J510                   | 1        | 8.33%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo | 1        | 8.33%   |
| Brother HL-2130 series                 | 1        | 8.33%   |
| Brother HL-1440 Laser Printer          | 1        | 8.33%   |

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
| Logitech                               | 40       | 44.94%  |
| Microsoft                              | 7        | 7.87%   |
| Microdia                               | 5        | 5.62%   |
| Apple                                  | 3        | 3.37%   |
| Trust                                  | 2        | 2.25%   |
| Sunplus Innovation Technology          | 2        | 2.25%   |
| Samsung Electronics                    | 2        | 2.25%   |
| KYE Systems (Mouse Systems)            | 2        | 2.25%   |
| Google                                 | 2        | 2.25%   |
| Generalplus Technology                 | 2        | 2.25%   |
| Chicony Electronics                    | 2        | 2.25%   |
| AVerMedia Technologies                 | 2        | 2.25%   |
| ARC International                      | 2        | 2.25%   |
| 2M UVC CAMERA                          | 2        | 2.25%   |
| XHT-211220-ZW                          | 1        | 1.12%   |
| Tobii Technology AB                    | 1        | 1.12%   |
| Realtek Semiconductor                  | 1        | 1.12%   |
| Razer USA                              | 1        | 1.12%   |
| Pixart Imaging                         | 1        | 1.12%   |
| LG Electronics                         | 1        | 1.12%   |
| Insta360                               | 1        | 1.12%   |
| ezcap                                  | 1        | 1.12%   |
| Elecom                                 | 1        | 1.12%   |
| Cubeternet                             | 1        | 1.12%   |
| Cheng Uei Precision Industry (Foxlink) | 1        | 1.12%   |
| Aveo Technology                        | 1        | 1.12%   |
| Alpha Imaging Technology               | 1        | 1.12%   |
| Alcor Micro                            | 1        | 1.12%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech HD Webcam C525                | 5        | 5.62%   |
| Logitech HD Pro Webcam C920            | 5        | 5.62%   |
| Logitech Webcam C270                   | 4        | 4.49%   |
| Logitech Webcam C170                   | 4        | 4.49%   |
| Logitech HD Webcam C615                | 3        | 3.37%   |
| Logitech C920 PRO HD Webcam            | 3        | 3.37%   |
| Logitech BRIO Ultra HD Webcam          | 3        | 3.37%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X        | 3        | 3.37%   |
| Samsung Galaxy A5 (MTP)                | 2        | 2.25%   |
| Microsoft MicrosoftÂ LifeCam Studio   | 2        | 2.25%   |
| Microsoft LifeCam HD-3000              | 2        | 2.25%   |
| Microdia Integrated Camera             | 2        | 2.25%   |
| Logitech Webcam C925e                  | 2        | 2.25%   |
| Logitech Webcam B500                   | 2        | 2.25%   |
| Logitech C922 Pro Stream Webcam        | 2        | 2.25%   |
| Generalplus GENERAL WEBCAM             | 2        | 2.25%   |
| AVerMedia Live Streamer CAM 313        | 2        | 2.25%   |
| ARC International Camera               | 2        | 2.25%   |
| 2M UVC CAMERA NexiGo N660 FHD Webcam   | 2        | 2.25%   |
| XHT-211220-ZW Photry PC230A QHD Webcam | 1        | 1.12%   |
| Trust USB Camera                       | 1        | 1.12%   |
| Trust Full HD Webcam                   | 1        | 1.12%   |
| Tobii AB EyeChip                       | 1        | 1.12%   |
| Sunplus Full HD webcam                 | 1        | 1.12%   |
| Sunplus ezcap U3 capture-04            | 1        | 1.12%   |
| Realtek HD 720P Webcam                 | 1        | 1.12%   |
| Razer USA Gaming Webcam [Kiyo]         | 1        | 1.12%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro   | 1        | 1.12%   |
| Microsoft MicrosoftÂ LifeCam Cinema   | 1        | 1.12%   |
| Microsoft LifeCam VX-800               | 1        | 1.12%   |
| Microsoft LifeCam VX-2000              | 1        | 1.12%   |
| Microdia Webcam Vitade AF              | 1        | 1.12%   |
| Microdia USB 2.0 Camera                | 1        | 1.12%   |
| Microdia REDRAGON Live Camera Audio    | 1        | 1.12%   |
| Logitech StreamCam                     | 1        | 1.12%   |
| Logitech QuickCam Pro for Notebooks    | 1        | 1.12%   |
| Logitech QuickCam Communicate MP/S5500 | 1        | 1.12%   |
| Logitech HD Webcam C910                | 1        | 1.12%   |
| Logitech HD Webcam B910                | 1        | 1.12%   |
| Logitech C505 HD Webcam                | 1        | 1.12%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 1        | 33.33%  |
| Elan Microelectronics | 1        | 33.33%  |
| AuthenTec             | 1        | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| LighTuning Fingerprint Sensor               | 1        | 33.33%  |
| Elan fingerprint sensor [FeinTech FPS00200] | 1        | 33.33%  |
| AuthenTec Fingerprint Sensor                | 1        | 33.33%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| BIT4ID | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                 | Desktops | Percent |
|-----------------------|----------|---------|
| BIT4ID miniLector EVO | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 291      | 84.59%  |
| 1     | 46       | 13.37%  |
| 2     | 6        | 1.74%   |
| 4     | 1        | 0.29%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 18       | 31.03%  |
| Graphics card            | 18       | 31.03%  |
| Unassigned class         | 4        | 6.9%    |
| Camera                   | 4        | 6.9%    |
| Sound                    | 3        | 5.17%   |
| Fingerprint reader       | 3        | 5.17%   |
| Communication controller | 3        | 5.17%   |
| Net/ethernet             | 2        | 3.45%   |
| Multimedia controller    | 2        | 3.45%   |
| Storage/nvme             | 1        | 1.72%   |

