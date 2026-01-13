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

Total: 253

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | B85M-D3H                    | [14b591528c](https://linux-hardware.org/?probe=14b591528c) | Dec 29, 2025 |
| ASRock        | B650M-H/M.2+ WiFi           | [cc16ae3bde](https://linux-hardware.org/?probe=cc16ae3bde) | Dec 24, 2025 |
| ASRock        | B450M/ac R2.0               | [6f49fcddc4](https://linux-hardware.org/?probe=6f49fcddc4) | Dec 07, 2025 |
| Gigabyte      | H610M H DDR4                | [bd47172ed6](https://linux-hardware.org/?probe=bd47172ed6) | Nov 29, 2025 |
| Dell          | 0DR845                      | [28c91f5307](https://linux-hardware.org/?probe=28c91f5307) | Nov 10, 2025 |
| ASUSTek       | M5A97 LE R2.0               | [17dc001954](https://linux-hardware.org/?probe=17dc001954) | Nov 08, 2025 |
| ASUSTek       | ROG STRIX B460-G GAMING     | [33099b6a91](https://linux-hardware.org/?probe=33099b6a91) | Nov 05, 2025 |
| ASUSTek       | M5A97 LE R2.0               | [669bfef40a](https://linux-hardware.org/?probe=669bfef40a) | Oct 25, 2025 |
| Gigabyte      | B550M DS3H                  | [093709474e](https://linux-hardware.org/?probe=093709474e) | Oct 07, 2025 |
| ASUSTek       | ROG STRIX B360-I GAMING     | [dec122256d](https://linux-hardware.org/?probe=dec122256d) | Oct 02, 2025 |
| Gigabyte      | Z87-HD3                     | [42956eee0f](https://linux-hardware.org/?probe=42956eee0f) | Sep 01, 2025 |
| ASRock        | FM2A68M-HD+                 | [5c018c4f36](https://linux-hardware.org/?probe=5c018c4f36) | Aug 29, 2025 |
| Gigabyte      | A520 AORUS ELITE            | [3c6021fdb6](https://linux-hardware.org/?probe=3c6021fdb6) | Aug 26, 2025 |
| ASUSTek       | ROG STRIX B360-I GAMING     | [ee4d76641e](https://linux-hardware.org/?probe=ee4d76641e) | Aug 21, 2025 |
| MSI           | PRO B660M-A WIFI DDR4       | [5d8f6578ef](https://linux-hardware.org/?probe=5d8f6578ef) | Aug 18, 2025 |
| MSI           | MS-B1831                    | [bde9c9eb55](https://linux-hardware.org/?probe=bde9c9eb55) | Aug 07, 2025 |
| MSI           | PRO B650-S WIFI             | [d65bae84e5](https://linux-hardware.org/?probe=d65bae84e5) | Jul 21, 2025 |
| Gigabyte      | Z87-HD3                     | [fd3c126462](https://linux-hardware.org/?probe=fd3c126462) | Jul 16, 2025 |
| MSI           | PRO Z790-A MAX WIFI         | [c51eb911e6](https://linux-hardware.org/?probe=c51eb911e6) | Jul 08, 2025 |
| Gigabyte      | G33M-S2                     | [52ba2940e8](https://linux-hardware.org/?probe=52ba2940e8) | Jul 02, 2025 |
| Gigabyte      | Z87-HD3                     | [eb9d8cc1af](https://linux-hardware.org/?probe=eb9d8cc1af) | Jun 24, 2025 |
| Intel         | DH77EB AAG39073-304         | [e024f2b9bf](https://linux-hardware.org/?probe=e024f2b9bf) | Jun 18, 2025 |
| Intel         | DH77EB AAG39073-304         | [a18c0863f9](https://linux-hardware.org/?probe=a18c0863f9) | Jun 17, 2025 |
| Gigabyte      | Z87-HD3                     | [b98c194131](https://linux-hardware.org/?probe=b98c194131) | Jun 17, 2025 |
| Amentmen      | X99-A4-B V6.1               | [2196799925](https://linux-hardware.org/?probe=2196799925) | Jun 17, 2025 |
| Gigabyte      | G33M-S2                     | [6652eebf6e](https://linux-hardware.org/?probe=6652eebf6e) | Jun 17, 2025 |
| Intel         | DH77EB AAG39073-304         | [0a28426cb5](https://linux-hardware.org/?probe=0a28426cb5) | Jun 17, 2025 |
| Gigabyte      | PA65-UD3-B3                 | [cabd8fffc7](https://linux-hardware.org/?probe=cabd8fffc7) | Jun 15, 2025 |
| Gigabyte      | H97M-HD3                    | [fbb6ccee12](https://linux-hardware.org/?probe=fbb6ccee12) | Jun 10, 2025 |
| Gigabyte      | H97M-HD3                    | [e50a3f02d8](https://linux-hardware.org/?probe=e50a3f02d8) | May 29, 2025 |
| Gigabyte      | H97M-HD3                    | [cebf0e792a](https://linux-hardware.org/?probe=cebf0e792a) | May 25, 2025 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [dd5cd37d09](https://linux-hardware.org/?probe=dd5cd37d09) | May 17, 2025 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [88e89b6853](https://linux-hardware.org/?probe=88e89b6853) | May 17, 2025 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [a90e40e113](https://linux-hardware.org/?probe=a90e40e113) | May 02, 2025 |
| ASUSTek       | PRIME B550M-K               | [0cc3bd3408](https://linux-hardware.org/?probe=0cc3bd3408) | Apr 20, 2025 |
| Gigabyte      | B450 AORUS PRO-CF           | [3e8feff1c3](https://linux-hardware.org/?probe=3e8feff1c3) | Apr 20, 2025 |
| ASUSTek       | PRIME B550M-K               | [bca325fe54](https://linux-hardware.org/?probe=bca325fe54) | Apr 19, 2025 |
| ASRock        | B450M Pro4                  | [f24f404ff7](https://linux-hardware.org/?probe=f24f404ff7) | Apr 19, 2025 |
| ASRock        | FM2A68M-HD+                 | [ae517862d8](https://linux-hardware.org/?probe=ae517862d8) | Apr 13, 2025 |
| MSI           | B450M MORTAR MAX            | [d3e5417e61](https://linux-hardware.org/?probe=d3e5417e61) | Mar 23, 2025 |
| Gigabyte      | H97M-HD3                    | [74513aa704](https://linux-hardware.org/?probe=74513aa704) | Mar 12, 2025 |
| ASRock        | D1800B-ITX                  | [9848b27e2e](https://linux-hardware.org/?probe=9848b27e2e) | Mar 09, 2025 |
| ASRock        | D1800B-ITX                  | [2365183934](https://linux-hardware.org/?probe=2365183934) | Mar 09, 2025 |
| ASUSTek       | H97M-E                      | [c9c4b49789](https://linux-hardware.org/?probe=c9c4b49789) | Feb 27, 2025 |
| ASRock        | Z97M Pro4                   | [2f3c0a3f43](https://linux-hardware.org/?probe=2f3c0a3f43) | Feb 01, 2025 |
| ASRock        | FM2A68M-HD+                 | [f2bb2bd6da](https://linux-hardware.org/?probe=f2bb2bd6da) | Dec 30, 2024 |
| MSI           | MPG X870E CARBON WIFI       | [5a55b1482a](https://linux-hardware.org/?probe=5a55b1482a) | Dec 17, 2024 |
| Biostar       | B550MX/E PRO                | [30e7b6d1fa](https://linux-hardware.org/?probe=30e7b6d1fa) | Dec 12, 2024 |
| Gigabyte      | Z97X-Gaming 3               | [3f5e65f8fc](https://linux-hardware.org/?probe=3f5e65f8fc) | Dec 08, 2024 |
| Gigabyte      | H61M-S2PV                   | [6a961e6e3e](https://linux-hardware.org/?probe=6a961e6e3e) | Nov 23, 2024 |
| Gigabyte      | X570S AERO G                | [616f53f4b7](https://linux-hardware.org/?probe=616f53f4b7) | Nov 01, 2024 |
| Gigabyte      | B360M-D3P-WG-CF             | [221fc17cd6](https://linux-hardware.org/?probe=221fc17cd6) | Oct 29, 2024 |
| ASRock        | B450M Steel Legend          | [e3ebc39bd6](https://linux-hardware.org/?probe=e3ebc39bd6) | Sep 26, 2024 |
| ASRock        | B450M Steel Legend          | [f44ffefe98](https://linux-hardware.org/?probe=f44ffefe98) | Aug 24, 2024 |
| ASUSTek       | M4N68T-M LE                 | [356a623cc0](https://linux-hardware.org/?probe=356a623cc0) | Aug 05, 2024 |
| ASUSTek       | PRIME B350-PLUS             | [bce7bed769](https://linux-hardware.org/?probe=bce7bed769) | Jul 31, 2024 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [ad50fcf9b4](https://linux-hardware.org/?probe=ad50fcf9b4) | Jul 25, 2024 |
| Gigabyte      | H410M S2                    | [41aa39c9f1](https://linux-hardware.org/?probe=41aa39c9f1) | Jul 15, 2024 |
| Gigabyte      | Z87-HD3                     | [fb68936c67](https://linux-hardware.org/?probe=fb68936c67) | Jul 12, 2024 |
| Gigabyte      | G33M-S2                     | [56fa3abc84](https://linux-hardware.org/?probe=56fa3abc84) | Jul 04, 2024 |
| Biostar       | H81MHV3                     | [f4fbb470c2](https://linux-hardware.org/?probe=f4fbb470c2) | Jun 22, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c957fc0c93](https://linux-hardware.org/?probe=c957fc0c93) | Jun 03, 2024 |
| ASUSTek       | PRIME H270-PRO              | [a0d3b25d66](https://linux-hardware.org/?probe=a0d3b25d66) | Jun 01, 2024 |
| ASRock        | X79 Extreme9                | [a65acf43f1](https://linux-hardware.org/?probe=a65acf43f1) | May 06, 2024 |
| ASUSTek       | PRIME H510M-K               | [8ae1401a90](https://linux-hardware.org/?probe=8ae1401a90) | Apr 14, 2024 |
| Unknown       | Unknown                     | [a2dd90b9c9](https://linux-hardware.org/?probe=a2dd90b9c9) | Apr 07, 2024 |
| MSI           | PRO B550M-P GEN3            | [79c408e0e7](https://linux-hardware.org/?probe=79c408e0e7) | Mar 30, 2024 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [5912d4041d](https://linux-hardware.org/?probe=5912d4041d) | Mar 16, 2024 |
| Unknown       | Unknown                     | [8b5831baf8](https://linux-hardware.org/?probe=8b5831baf8) | Feb 15, 2024 |
| Gigabyte      | X670E AORUS MASTER          | [833f48af30](https://linux-hardware.org/?probe=833f48af30) | Feb 12, 2024 |
| ASRock        | FM2A88X Extreme4+           | [b30121b1f1](https://linux-hardware.org/?probe=b30121b1f1) | Feb 11, 2024 |
| ASRock        | FM2A88X Extreme4+           | [49efdd6436](https://linux-hardware.org/?probe=49efdd6436) | Feb 08, 2024 |
| HP            | 8055                        | [ee3ece9007](https://linux-hardware.org/?probe=ee3ece9007) | Jan 05, 2024 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [84d4572994](https://linux-hardware.org/?probe=84d4572994) | Dec 12, 2023 |
| MSI           | H61M-E33                    | [ed1dc1d923](https://linux-hardware.org/?probe=ed1dc1d923) | Dec 09, 2023 |
| Biostar       | B450MH                      | [e490dfb129](https://linux-hardware.org/?probe=e490dfb129) | Dec 02, 2023 |
| ASRock        | B550M-HDV                   | [68c7c96b9b](https://linux-hardware.org/?probe=68c7c96b9b) | Dec 02, 2023 |
| MSI           | Z390-A PRO                  | [1f07a66db1](https://linux-hardware.org/?probe=1f07a66db1) | Nov 22, 2023 |
| MSI           | X370 SLI PLUS               | [2ac0a2ecc8](https://linux-hardware.org/?probe=2ac0a2ecc8) | Oct 23, 2023 |
| ASRock        | H610M-HVS/M.2 R2.0          | [74df5e1893](https://linux-hardware.org/?probe=74df5e1893) | Oct 21, 2023 |
| Intel         | DH55HC AAE70933-505         | [f1bc373847](https://linux-hardware.org/?probe=f1bc373847) | Oct 19, 2023 |
| Shenzhen M... | F6BFC                       | [007ce9ca02](https://linux-hardware.org/?probe=007ce9ca02) | Oct 14, 2023 |
| Shenzhen M... | F6BFC                       | [e71b9295ca](https://linux-hardware.org/?probe=e71b9295ca) | Oct 11, 2023 |
| Shenzhen M... | F6BFC                       | [ca89a07b9e](https://linux-hardware.org/?probe=ca89a07b9e) | Sep 10, 2023 |
| Shenzhen M... | F6BFC                       | [a33ec74b50](https://linux-hardware.org/?probe=a33ec74b50) | Sep 05, 2023 |
| Shenzhen M... | F6BFC                       | [d5cd8916d0](https://linux-hardware.org/?probe=d5cd8916d0) | Sep 05, 2023 |
| HP            | 0A9Ch                       | [f5d07e235d](https://linux-hardware.org/?probe=f5d07e235d) | Aug 24, 2023 |
| MSI           | B450M PRO-VDH MAX           | [1d9653f23a](https://linux-hardware.org/?probe=1d9653f23a) | Aug 13, 2023 |
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
| Arch Rolling                 | 10       | 5.38%   |
| Ubuntu 22.04                 | 7        | 3.76%   |
| Ubuntu 20.04                 | 6        | 3.23%   |
| Ubuntu 18.04                 | 6        | 3.23%   |
| ROSA R10                     | 6        | 3.23%   |
| ROSA R11                     | 5        | 2.69%   |
| KDE neon 20.04               | 5        | 2.69%   |
| Debian 12                    | 5        | 2.69%   |
| openSUSE Tumbleweed-XXXXXXXX | 4        | 2.15%   |
| Linux Mint 22.1              | 4        | 2.15%   |
| Linux Mint 20.1              | 4        | 2.15%   |
| Xubuntu 20.04                | 3        | 1.61%   |
| ROSA R9                      | 3        | 1.61%   |
| Pop!_OS 22.04                | 3        | 1.61%   |
| OpenMandriva 24.12           | 3        | 1.61%   |
| Linux Mint 21.1              | 3        | 1.61%   |
| Linux Mint 20.2              | 3        | 1.61%   |
| Fedora 39                    | 3        | 1.61%   |
| Fedora 38                    | 3        | 1.61%   |
| Fedora 37                    | 3        | 1.61%   |
| Zorin 16                     | 2        | 1.08%   |
| Ubuntu 23.10                 | 2        | 1.08%   |
| ROSA R8.1                    | 2        | 1.08%   |
| ROSA 12.2                    | 2        | 1.08%   |
| OpenMandriva 4.50            | 2        | 1.08%   |
| OpenMandriva 4.2             | 2        | 1.08%   |
| OpenMandriva 23.01           | 2        | 1.08%   |
| Linux Mint 21.3              | 2        | 1.08%   |
| Linux Mint 20.3              | 2        | 1.08%   |
| Linux Mint 19.3              | 2        | 1.08%   |
| KDE neon 22.04               | 2        | 1.08%   |
| Fedora 42                    | 2        | 1.08%   |
| Fedora 35                    | 2        | 1.08%   |
| Fedora 30                    | 2        | 1.08%   |
| Debian Testing               | 2        | 1.08%   |
| Debian 11                    | 2        | 1.08%   |
| ArcoLinux Rolling            | 2        | 1.08%   |
| Zorin 18                     | 1        | 0.54%   |
| Zorin 17                     | 1        | 0.54%   |
| Xubuntu 18.04                | 1        | 0.54%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 23       | 13.61%  |
| ROSA         | 21       | 12.43%  |
| Linux Mint   | 21       | 12.43%  |
| Fedora       | 18       | 10.65%  |
| OpenMandriva | 14       | 8.28%   |
| Arch         | 11       | 6.51%   |
| KDE neon     | 8        | 4.73%   |
| Debian       | 8        | 4.73%   |
| Pop!_OS      | 5        | 2.96%   |
| Zorin        | 4        | 2.37%   |
| Xubuntu      | 4        | 2.37%   |
| openSUSE     | 4        | 2.37%   |
| Kubuntu      | 4        | 2.37%   |
| Manjaro      | 2        | 1.18%   |
| Gentoo       | 2        | 1.18%   |
| Garuda Linux | 2        | 1.18%   |
| Clear Linux  | 2        | 1.18%   |
| CachyOS      | 2        | 1.18%   |
| ArcoLinux    | 2        | 1.18%   |
| ALT Linux    | 2        | 1.18%   |
| Void Linux   | 1        | 0.59%   |
| SteamOS      | 1        | 0.59%   |
| Puppy        | 1        | 0.59%   |
| Nobara       | 1        | 0.59%   |
| Lubuntu      | 1        | 0.59%   |
| LMDE         | 1        | 0.59%   |
| Kali         | 1        | 0.59%   |
| Endless      | 1        | 0.59%   |
| EndeavourOS  | 1        | 0.59%   |
| Artix        | 1        | 0.59%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Desktops | Percent |
|-------------------------------------|----------|---------|
| 4.9.60-nrj-desktop-1rosa-x86_64     | 5        | 2.45%   |
| 5.4.0-58-generic                    | 4        | 1.96%   |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 4        | 1.96%   |
| 6.12.1-desktop-1omv2490             | 3        | 1.47%   |
| 5.4.0-132-generic                   | 3        | 1.47%   |
| 5.4.0-122-generic                   | 3        | 1.47%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 3        | 1.47%   |
| 6.5.7-200.fc38.x86_64               | 2        | 0.98%   |
| 6.11.0-26-generic                   | 2        | 0.98%   |
| 6.1.1-desktop-1omv2290              | 2        | 0.98%   |
| 6.1.0-37-amd64                      | 2        | 0.98%   |
| 5.4.0-66-generic                    | 2        | 0.98%   |
| 5.4.0-54-generic                    | 2        | 0.98%   |
| 5.13.0-39-generic                   | 2        | 0.98%   |
| 5.12.4-desktop-1omv4050             | 2        | 0.98%   |
| 5.10.14-desktop-1omv4002            | 2        | 0.98%   |
| 5.0.0-37-generic                    | 2        | 0.98%   |
| 6.9.9-zen1-1-zen                    | 1        | 0.49%   |
| 6.9.9-arch1-1                       | 1        | 0.49%   |
| 6.9.3-1-default                     | 1        | 0.49%   |
| 6.8.6-200.fc39.x86_64               | 1        | 0.49%   |
| 6.8.2-arch2-1                       | 1        | 0.49%   |
| 6.8.12-8-pve                        | 1        | 0.49%   |
| 6.8.0-79-generic                    | 1        | 0.49%   |
| 6.8.0-76060800daily20240311-generic | 1        | 0.49%   |
| 6.8.0-63-generic                    | 1        | 0.49%   |
| 6.8.0-60-generic                    | 1        | 0.49%   |
| 6.8.0-57-generic                    | 1        | 0.49%   |
| 6.8.0-52-generic                    | 1        | 0.49%   |
| 6.8.0-50-generic                    | 1        | 0.49%   |
| 6.8.0-39-generic                    | 1        | 0.49%   |
| 6.8.0-060800-generic                | 1        | 0.49%   |
| 6.7.9-zen1-1-zen                    | 1        | 0.49%   |
| 6.7.4-gentoo-dist                   | 1        | 0.49%   |
| 6.6.9-200.fc39.x86_64               | 1        | 0.49%   |
| 6.6.8-200.fsync.fc38.x86_64         | 1        | 0.49%   |
| 6.6.47-generic-1rosa2021.1-x86_64   | 1        | 0.49%   |
| 6.6.3-arch1-1                       | 1        | 0.49%   |
| 6.6.21-generic-8rosa2021.1-x86_64   | 1        | 0.49%   |
| 6.6.2-201.fc39.x86_64               | 1        | 0.49%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 19       | 10.05%  |
| 5.15.0  | 14       | 7.41%   |
| 4.15.0  | 10       | 5.29%   |
| 6.8.0   | 7        | 3.7%    |
| 5.13.0  | 5        | 2.65%   |
| 4.9.60  | 5        | 2.65%   |
| 4.9.20  | 5        | 2.65%   |
| 6.1.0   | 4        | 2.12%   |
| 5.3.0   | 4        | 2.12%   |
| 5.19.0  | 4        | 2.12%   |
| 6.5.0   | 3        | 1.59%   |
| 6.14.0  | 3        | 1.59%   |
| 6.12.1  | 3        | 1.59%   |
| 6.11.0  | 3        | 1.59%   |
| 6.1.1   | 3        | 1.59%   |
| 5.8.0   | 3        | 1.59%   |
| 5.11.0  | 3        | 1.59%   |
| 6.9.9   | 2        | 1.06%   |
| 6.5.7   | 2        | 1.06%   |
| 6.2.6   | 2        | 1.06%   |
| 6.2.0   | 2        | 1.06%   |
| 6.16.1  | 2        | 1.06%   |
| 6.14.6  | 2        | 1.06%   |
| 5.12.4  | 2        | 1.06%   |
| 5.10.14 | 2        | 1.06%   |
| 5.10.0  | 2        | 1.06%   |
| 5.0.0   | 2        | 1.06%   |
| 6.9.3   | 1        | 0.53%   |
| 6.8.6   | 1        | 0.53%   |
| 6.8.2   | 1        | 0.53%   |
| 6.8.12  | 1        | 0.53%   |
| 6.7.9   | 1        | 0.53%   |
| 6.7.4   | 1        | 0.53%   |
| 6.6.9   | 1        | 0.53%   |
| 6.6.8   | 1        | 0.53%   |
| 6.6.47  | 1        | 0.53%   |
| 6.6.3   | 1        | 0.53%   |
| 6.6.21  | 1        | 0.53%   |
| 6.6.2   | 1        | 0.53%   |
| 6.4.6   | 1        | 0.53%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 22       | 11.7%   |
| 5.15    | 15       | 7.98%   |
| 4.9     | 11       | 5.85%   |
| 6.8     | 10       | 5.32%   |
| 6.1     | 10       | 5.32%   |
| 4.15    | 10       | 5.32%   |
| 6.12    | 8        | 4.26%   |
| 5.11    | 7        | 3.72%   |
| 5.10    | 7        | 3.72%   |
| 6.6     | 6        | 3.19%   |
| 6.17    | 6        | 3.19%   |
| 6.14    | 6        | 3.19%   |
| 5.13    | 6        | 3.19%   |
| 6.5     | 5        | 2.66%   |
| 6.11    | 5        | 2.66%   |
| 5.19    | 5        | 2.66%   |
| 6.2     | 4        | 2.13%   |
| 6.0     | 4        | 2.13%   |
| 5.8     | 4        | 2.13%   |
| 5.3     | 4        | 2.13%   |
| 6.9     | 3        | 1.6%    |
| 6.16    | 3        | 1.6%    |
| 5.16    | 3        | 1.6%    |
| 6.7     | 2        | 1.06%   |
| 6.4     | 2        | 1.06%   |
| 6.13    | 2        | 1.06%   |
| 5.9     | 2        | 1.06%   |
| 5.2     | 2        | 1.06%   |
| 5.17    | 2        | 1.06%   |
| 5.12    | 2        | 1.06%   |
| 5.0     | 2        | 1.06%   |
| 6.3     | 1        | 0.53%   |
| 6.15    | 1        | 0.53%   |
| 5.6     | 1        | 0.53%   |
| 5.18    | 1        | 0.53%   |
| 5.14    | 1        | 0.53%   |
| 4.8     | 1        | 0.53%   |
| 4.18    | 1        | 0.53%   |
| 4.1     | 1        | 0.53%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 154      | 97.47%  |
| i686   | 4        | 2.53%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 51       | 30%     |
| KDE5       | 33       | 19.41%  |
| KDE6       | 19       | 11.18%  |
| X-Cinnamon | 15       | 8.82%   |
| Unknown    | 12       | 7.06%   |
| XFCE       | 11       | 6.47%   |
| KDE4       | 10       | 5.88%   |
| MATE       | 6        | 3.53%   |
| KDE        | 6        | 3.53%   |
| Cinnamon   | 3        | 1.76%   |
| Deepin     | 2        | 1.18%   |
| LXQt       | 1        | 0.59%   |
| COSMIC     | 1        | 0.59%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 109      | 66.87%  |
| Wayland | 47       | 28.83%  |
| Unknown | 4        | 2.45%   |
| Tty     | 3        | 1.84%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 83       | 48.26%  |
| SDDM    | 41       | 23.84%  |
| LightDM | 13       | 7.56%   |
| GDM     | 11       | 6.4%    |
| KDM     | 10       | 5.81%   |
| GDM3    | 10       | 5.81%   |
| TDM     | 4        | 2.33%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| en_US       | 76       | 44.97%  |
| ru_RU       | 30       | 17.75%  |
| Unknown     | 22       | 13.02%  |
| lv_LV       | 19       | 11.24%  |
| en_GB       | 10       | 5.92%   |
| C           | 7        | 4.14%   |
| ru_RU.UTF_8 | 1        | 0.59%   |
| osa_US      | 1        | 0.59%   |
| en_AG       | 1        | 0.59%   |
| de_DE       | 1        | 0.59%   |
| cv_RU       | 1        | 0.59%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 104      | 64.2%   |
| EFI  | 58       | 35.8%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 104      | 61.54%  |
| Btrfs   | 29       | 17.16%  |
| Overlay | 12       | 7.1%    |
| Unknown | 12       | 7.1%    |
| Tmpfs   | 7        | 4.14%   |
| Xfs     | 2        | 1.18%   |
| F2fs    | 1        | 0.59%   |
| Ext3    | 1        | 0.59%   |
| Aufs    | 1        | 0.59%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 86       | 50.59%  |
| GPT     | 54       | 31.76%  |
| MBR     | 30       | 17.65%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 131      | 79.39%  |
| Yes       | 34       | 20.61%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 116      | 68.64%  |
| Yes       | 53       | 31.36%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 40       | 25.32%  |
| Gigabyte Technology                  | 35       | 22.15%  |
| MSI                                  | 23       | 14.56%  |
| ASRock                               | 21       | 13.29%  |
| Dell                                 | 8        | 5.06%   |
| Hewlett-Packard                      | 7        | 4.43%   |
| Intel                                | 6        | 3.8%    |
| Biostar                              | 4        | 2.53%   |
| Acer                                 | 3        | 1.9%    |
| Unknown                              | 2        | 1.27%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.63%   |
| Lenovo                               | 1        | 0.63%   |
| IBM                                  | 1        | 0.63%   |
| Hardkernel                           | 1        | 0.63%   |
| Fujitsu Siemens                      | 1        | 0.63%   |
| Foxconn                              | 1        | 0.63%   |
| Amentmen                             | 1        | 0.63%   |
| Acidanthera                          | 1        | 0.63%   |
| ABIT                                 | 1        | 0.63%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS All Series                            | 7        | 4.43%   |
| Intel DH77EB AAG39073-304                  | 3        | 1.9%    |
| MSI MS-7721                                | 2        | 1.27%   |
| Gigabyte G33M-S2                           | 2        | 1.27%   |
| Gigabyte B550 AORUS PRO V2                 | 2        | 1.27%   |
| Gigabyte 946GMX-S2                         | 2        | 1.27%   |
| Dell OptiPlex 7020                         | 2        | 1.27%   |
| ASUS TUF Gaming X570-PLUS                  | 2        | 1.27%   |
| ASUS TUF Gaming B650-PLUS WIFI             | 2        | 1.27%   |
| ASRock FM2A68M-HD+                         | 2        | 1.27%   |
| Unknown                                    | 2        | 1.27%   |
| Shenzhen Meigao Electronic Equipment UM450 | 1        | 0.63%   |
| MSI MS-7E49                                | 1        | 0.63%   |
| MSI MS-7E26                                | 1        | 0.63%   |
| MSI MS-7E07                                | 1        | 0.63%   |
| MSI MS-7D95                                | 1        | 0.63%   |
| MSI MS-7D43                                | 1        | 0.63%   |
| MSI MS-7C52                                | 1        | 0.63%   |
| MSI MS-7B98                                | 1        | 0.63%   |
| MSI MS-7B89                                | 1        | 0.63%   |
| MSI MS-7B46                                | 1        | 0.63%   |
| MSI MS-7B33                                | 1        | 0.63%   |
| MSI MS-7A38                                | 1        | 0.63%   |
| MSI MS-7A33                                | 1        | 0.63%   |
| MSI MS-7996                                | 1        | 0.63%   |
| MSI MS-7850                                | 1        | 0.63%   |
| MSI MS-7846                                | 1        | 0.63%   |
| MSI MS-7758                                | 1        | 0.63%   |
| MSI MS-7693                                | 1        | 0.63%   |
| MSI MS-7680                                | 1        | 0.63%   |
| MSI MS-7583                                | 1        | 0.63%   |
| MSI MS-7519                                | 1        | 0.63%   |
| MSI CML-U PRO Cubi 5 (MS-B183)             | 1        | 0.63%   |
| Lenovo Legion T5 26AMR5 90RC018LBX         | 1        | 0.63%   |
| Intel DQ87PG AAG74154-403                  | 1        | 0.63%   |
| Intel DH55HC AAE70933-505                  | 1        | 0.63%   |
| Intel DB85FL AAG89861-201                  | 1        | 0.63%   |
| IBM 8215ZCL                                | 1        | 0.63%   |
| HP xw6600 Workstation                      | 1        | 0.63%   |
| HP ProDesk 600 G1 TWR                      | 1        | 0.63%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Dell OptiPlex                              | 8        | 5.06%   |
| ASUS PRIME                                 | 8        | 5.06%   |
| ASUS All                                   | 7        | 4.43%   |
| ASUS TUF                                   | 5        | 3.16%   |
| ASUS ROG                                   | 5        | 3.16%   |
| Intel DH77EB                               | 3        | 1.9%    |
| HP Compaq                                  | 3        | 1.9%    |
| ASRock B450M                               | 3        | 1.9%    |
| MSI MS-7721                                | 2        | 1.27%   |
| Gigabyte G33M-S2                           | 2        | 1.27%   |
| Gigabyte B550                              | 2        | 1.27%   |
| Gigabyte B450                              | 2        | 1.27%   |
| Gigabyte 946GMX-S2                         | 2        | 1.27%   |
| ASUS P5Q                                   | 2        | 1.27%   |
| ASRock FM2A68M-HD+                         | 2        | 1.27%   |
| Acer Aspire                                | 2        | 1.27%   |
| Unknown                                    | 2        | 1.27%   |
| Shenzhen Meigao Electronic Equipment UM450 | 1        | 0.63%   |
| MSI MS-7E49                                | 1        | 0.63%   |
| MSI MS-7E26                                | 1        | 0.63%   |
| MSI MS-7E07                                | 1        | 0.63%   |
| MSI MS-7D95                                | 1        | 0.63%   |
| MSI MS-7D43                                | 1        | 0.63%   |
| MSI MS-7C52                                | 1        | 0.63%   |
| MSI MS-7B98                                | 1        | 0.63%   |
| MSI MS-7B89                                | 1        | 0.63%   |
| MSI MS-7B46                                | 1        | 0.63%   |
| MSI MS-7B33                                | 1        | 0.63%   |
| MSI MS-7A38                                | 1        | 0.63%   |
| MSI MS-7A33                                | 1        | 0.63%   |
| MSI MS-7996                                | 1        | 0.63%   |
| MSI MS-7850                                | 1        | 0.63%   |
| MSI MS-7846                                | 1        | 0.63%   |
| MSI MS-7758                                | 1        | 0.63%   |
| MSI MS-7693                                | 1        | 0.63%   |
| MSI MS-7680                                | 1        | 0.63%   |
| MSI MS-7583                                | 1        | 0.63%   |
| MSI MS-7519                                | 1        | 0.63%   |
| MSI CML-U                                  | 1        | 0.63%   |
| Lenovo Legion                              | 1        | 0.63%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 16       | 10.13%  |
| 2007 | 15       | 9.49%   |
| 2014 | 14       | 8.86%   |
| 2013 | 13       | 8.23%   |
| 2018 | 11       | 6.96%   |
| 2019 | 10       | 6.33%   |
| 2008 | 9        | 5.7%    |
| 2022 | 8        | 5.06%   |
| 2020 | 8        | 5.06%   |
| 2021 | 7        | 4.43%   |
| 2017 | 7        | 4.43%   |
| 2011 | 7        | 4.43%   |
| 2009 | 7        | 4.43%   |
| 2015 | 6        | 3.8%    |
| 2023 | 5        | 3.16%   |
| 2010 | 5        | 3.16%   |
| 2006 | 4        | 2.53%   |
| 2024 | 2        | 1.27%   |
| 2016 | 2        | 1.27%   |
| 2025 | 1        | 0.63%   |
| 2004 | 1        | 0.63%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 158      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 154      | 97.47%  |
| Enabled  | 4        | 2.53%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 158      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 35       | 21.6%   |
| 8.01-16.0       | 30       | 18.52%  |
| 32.01-64.0      | 29       | 17.9%   |
| 3.01-4.0        | 26       | 16.05%  |
| 4.01-8.0        | 18       | 11.11%  |
| 64.01-256.0     | 8        | 4.94%   |
| 1.01-2.0        | 7        | 4.32%   |
| 24.01-32.0      | 4        | 2.47%   |
| 2.01-3.0        | 4        | 2.47%   |
| More than 256.0 | 1        | 0.62%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 49       | 26.92%  |
| 4.01-8.0   | 38       | 20.88%  |
| 2.01-3.0   | 35       | 19.23%  |
| 3.01-4.0   | 26       | 14.29%  |
| 0.51-1.0   | 21       | 11.54%  |
| 8.01-16.0  | 11       | 6.04%   |
| 32.01-64.0 | 1        | 0.55%   |
| 16.01-24.0 | 1        | 0.55%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 60       | 35.71%  |
| 2      | 43       | 25.6%   |
| 3      | 36       | 21.43%  |
| 4      | 17       | 10.12%  |
| 5      | 7        | 4.17%   |
| 7      | 2        | 1.19%   |
| 6      | 2        | 1.19%   |
| 8      | 1        | 0.6%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 105      | 65.22%  |
| Yes       | 56       | 34.78%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 157      | 99.37%  |
| No        | 1        | 0.63%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 101      | 63.13%  |
| Yes       | 59       | 36.88%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 114      | 70.81%  |
| Yes       | 47       | 29.19%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Latvia  | 158      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City       | Desktops | Percent |
|------------|----------|---------|
| Riga       | 114      | 68.67%  |
| Liepāja   | 6        | 3.61%   |
| Ventspils  | 5        | 3.01%   |
| Salaspils  | 4        | 2.41%   |
| Jelgava    | 4        | 2.41%   |
| Ogre       | 3        | 1.81%   |
| Jaunolaine | 3        | 1.81%   |
| Talsi      | 2        | 1.2%    |
| Kuldīga   | 2        | 1.2%    |
| Jūrmala   | 2        | 1.2%    |
| Daugavpils | 2        | 1.2%    |
| Adazi      | 2        | 1.2%    |
| Roya       | 1        | 0.6%    |
| Ragana     | 1        | 0.6%    |
| Pļaviņas | 1        | 0.6%    |
| Pinki      | 1        | 0.6%    |
| Mirnijs    | 1        | 0.6%    |
| Limbaži   | 1        | 0.6%    |
| Lielvārde | 1        | 0.6%    |
| Krāslava  | 1        | 0.6%    |
| Katlakalns | 1        | 0.6%    |
| Kārsava   | 1        | 0.6%    |
| Jēkabpils | 1        | 0.6%    |
| Jaunmarupe | 1        | 0.6%    |
| Iecava     | 1        | 0.6%    |
| Dreilini   | 1        | 0.6%    |
| Carnikava  | 1        | 0.6%    |
| Brankas    | 1        | 0.6%    |
| Bauska     | 1        | 0.6%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| WDC                          | 62       | 99     | 19.81%  |
| Seagate                      | 58       | 97     | 18.53%  |
| Samsung Electronics          | 44       | 84     | 14.06%  |
| Kingston                     | 27       | 40     | 8.63%   |
| Crucial                      | 15       | 33     | 4.79%   |
| Toshiba                      | 10       | 20     | 3.19%   |
| Intel                        | 8        | 14     | 2.56%   |
| Hitachi                      | 7        | 9      | 2.24%   |
| GOODRAM                      | 7        | 16     | 2.24%   |
| A-DATA Technology            | 7        | 8      | 2.24%   |
| Phison Electronics           | 6        | 8      | 1.92%   |
| SPCC                         | 4        | 6      | 1.28%   |
| OCZ                          | 4        | 6      | 1.28%   |
| HGST                         | 4        | 4      | 1.28%   |
| Shenzhen Longsys Electronics | 3        | 3      | 0.96%   |
| Sandisk                      | 3        | 5      | 0.96%   |
| Patriot                      | 3        | 4      | 0.96%   |
| Kingston Technology Company  | 3        | 3      | 0.96%   |
| ADATA Technology             | 3        | 4      | 0.96%   |
| Transcend                    | 2        | 4      | 0.64%   |
| Silicon Motion               | 2        | 3      | 0.64%   |
| Realtek Semiconductor        | 2        | 2      | 0.64%   |
| MAXIO Technology (Hangzhou)  | 2        | 2      | 0.64%   |
| Lexar                        | 2        | 2      | 0.64%   |
| KingSpec                     | 2        | 2      | 0.64%   |
| Intenso                      | 2        | 2      | 0.64%   |
| China                        | 2        | 2      | 0.64%   |
| XPG                          | 1        | 1      | 0.32%   |
| Unknown                      | 1        | 1      | 0.32%   |
| Team                         | 1        | 1      | 0.32%   |
| RSH-338H                     | 1        | 2      | 0.32%   |
| Netac                        | 1        | 1      | 0.32%   |
| Mushkin                      | 1        | 3      | 0.32%   |
| Maxtor                       | 1        | 1      | 0.32%   |
| LuminouTek                   | 1        | 1      | 0.32%   |
| Lite-On Technology           | 1        | 3      | 0.32%   |
| Lite-On                      | 1        | 1      | 0.32%   |
| KIOXIA-EXCERIA               | 1        | 1      | 0.32%   |
| KingFast                     | 1        | 4      | 0.32%   |
| JMicron Technology           | 1        | 2      | 0.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD                   | 10       | 2.74%   |
| Seagate ST1000DM010-2EP102 1TB                    | 8        | 2.19%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 5        | 1.37%   |
| Crucial CT500MX500SSD1 500GB                      | 5        | 1.37%   |
| Samsung SSD 850 EVO 250GB                         | 4        | 1.1%    |
| Kingston SA400S37480G 480GB SSD                   | 4        | 1.1%    |
| Crucial CT1000MX500SSD1 1TB                       | 4        | 1.1%    |
| WDC WD2000JD-00HBB0 200GB                         | 3        | 0.82%   |
| WDC WD10EZEX-00BN5A0 1TB                          | 3        | 0.82%   |
| Seagate ST500DM005 HD502HJ 500GB                  | 3        | 0.82%   |
| Seagate ST3500418AS 500GB                         | 3        | 0.82%   |
| Samsung NVMe SSD Drive 500GB                      | 3        | 0.82%   |
| Phison PS5013 E13 NVMe Controller 500GB           | 3        | 0.82%   |
| Kingston SV300S37A240G 240GB SSD                  | 3        | 0.82%   |
| GOODRAM SSDPR-CX400-512-G2 512GB                  | 3        | 0.82%   |
| Crucial CT480BX500SSD1 480GB                      | 3        | 0.82%   |
| WDC WDS500G2B0A-00SM50 500GB                      | 2        | 0.55%   |
| WDC WDS250G2B0A-00SM50 250GB SSD                  | 2        | 0.55%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                    | 2        | 0.55%   |
| WDC WD6003FZBX-00K5WB0 6TB                        | 2        | 0.55%   |
| WDC WD5002AALX-00J37A0 500GB                      | 2        | 0.55%   |
| WDC WD5000AAKX-22ERMA0 500GB                      | 2        | 0.55%   |
| WDC WD5000AAKX-00U6AA0 500GB                      | 2        | 0.55%   |
| WDC WD5000AAKX-00ERMA0 500GB                      | 2        | 0.55%   |
| WDC WD5000AAKX-001CA0 500GB                       | 2        | 0.55%   |
| WDC WD20EARX-00PASB0 2TB                          | 2        | 0.55%   |
| WDC WD10EALX-009BA0 1TB                           | 2        | 0.55%   |
| Toshiba DT01ACA100 1TB                            | 2        | 0.55%   |
| SPCC Solid State Disk 2TB                         | 2        | 0.55%   |
| Seagate ST500DM002-1BD142 500GB                   | 2        | 0.55%   |
| Seagate ST3750640AS 752GB                         | 2        | 0.55%   |
| Seagate ST3500413AS 500GB                         | 2        | 0.55%   |
| Seagate ST3320620AS 320GB                         | 2        | 0.55%   |
| Seagate ST3250824AS 250GB                         | 2        | 0.55%   |
| Seagate ST250DM000-1BD141 250GB                   | 2        | 0.55%   |
| Seagate ST2000DM001-1CH164 2TB                    | 2        | 0.55%   |
| Seagate ST1000DX001-1CM162 1TB                    | 2        | 0.55%   |
| Seagate ST1000DM003-1SB102 1TB                    | 2        | 0.55%   |
| Seagate ST1000DM003-1ER162 1TB                    | 2        | 0.55%   |
| Seagate Expansion 2TB                             | 2        | 0.55%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 58       | 96     | 39.73%  |
| WDC                 | 51       | 80     | 34.93%  |
| Samsung Electronics | 13       | 25     | 8.9%    |
| Toshiba             | 10       | 20     | 6.85%   |
| Hitachi             | 7        | 9      | 4.79%   |
| HGST                | 4        | 4      | 2.74%   |
| Maxtor              | 1        | 1      | 0.68%   |
| JMicron Technology  | 1        | 2      | 0.68%   |
| IBM/Hitachi         | 1        | 1      | 0.68%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 25       | 38     | 21.01%  |
| Samsung Electronics | 16       | 28     | 13.45%  |
| Crucial             | 15       | 33     | 12.61%  |
| WDC                 | 13       | 16     | 10.92%  |
| GOODRAM             | 7        | 16     | 5.88%   |
| A-DATA Technology   | 7        | 8      | 5.88%   |
| Intel               | 5        | 11     | 4.2%    |
| SPCC                | 4        | 6      | 3.36%   |
| OCZ                 | 4        | 6      | 3.36%   |
| Patriot             | 3        | 4      | 2.52%   |
| Transcend           | 2        | 4      | 1.68%   |
| Lexar               | 2        | 2      | 1.68%   |
| KingSpec            | 2        | 2      | 1.68%   |
| Intenso             | 2        | 2      | 1.68%   |
| China               | 2        | 2      | 1.68%   |
| Team                | 1        | 1      | 0.84%   |
| Seagate             | 1        | 1      | 0.84%   |
| SanDisk             | 1        | 1      | 0.84%   |
| Mushkin             | 1        | 3      | 0.84%   |
| LuminouTek          | 1        | 1      | 0.84%   |
| Lite-On             | 1        | 1      | 0.84%   |
| KIOXIA-EXCERIA      | 1        | 1      | 0.84%   |
| KingFast            | 1        | 4      | 0.84%   |
| GLOWAY              | 1        | 2      | 0.84%   |
| CHN25SATAS1         | 1        | 1      | 0.84%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 110      | 238    | 43.48%  |
| SSD     | 89       | 194    | 35.18%  |
| NVMe    | 50       | 74     | 19.76%  |
| Unknown | 3        | 4      | 1.19%   |
| MMC     | 1        | 1      | 0.4%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 145      | 426    | 71.43%  |
| NVMe | 50       | 74     | 24.63%  |
| SAS  | 7        | 10     | 3.45%   |
| MMC  | 1        | 1      | 0.49%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 117      | 257    | 55.45%  |
| 0.51-1.0   | 62       | 121    | 29.38%  |
| 1.01-2.0   | 19       | 32     | 9%      |
| 2.01-3.0   | 5        | 11     | 2.37%   |
| 4.01-10.0  | 5        | 6      | 2.37%   |
| 3.01-4.0   | 3        | 5      | 1.42%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 50       | 28.74%  |
| 251-500        | 23       | 13.22%  |
| 1001-2000      | 23       | 13.22%  |
| More than 3000 | 22       | 12.64%  |
| 501-1000       | 17       | 9.77%   |
| 51-100         | 12       | 6.9%    |
| 1-20           | 9        | 5.17%   |
| 21-50          | 8        | 4.6%    |
| 2001-3000      | 7        | 4.02%   |
| Unknown        | 3        | 1.72%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 56       | 29.79%  |
| 101-250        | 27       | 14.36%  |
| 21-50          | 26       | 13.83%  |
| 251-500        | 22       | 11.7%   |
| 51-100         | 17       | 9.04%   |
| 501-1000       | 15       | 7.98%   |
| 1001-2000      | 11       | 5.85%   |
| 2001-3000      | 8        | 4.26%   |
| More than 3000 | 3        | 1.6%    |
| Unknown        | 3        | 1.6%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD20EARX-00PASB0 2TB              | 2        | 4      | 5.41%   |
| WDC WD2000JD-00HBB0 200GB             | 2        | 4      | 5.41%   |
| Seagate ST1000DM003-1SB102 1TB        | 2        | 8      | 5.41%   |
| Samsung Electronics SP2504C 250GB     | 2        | 2      | 5.41%   |
| Samsung Electronics HD501LJ 500GB     | 2        | 8      | 5.41%   |
| WDC WDS500G3X0C-00SJG0 500GB          | 1        | 1      | 2.7%    |
| WDC WD800JD-60MSA1 80GB               | 1        | 1      | 2.7%    |
| WDC WD5002AALX-00J37A0 500GB          | 1        | 1      | 2.7%    |
| WDC WD5001AALS-00L3B2 500GB           | 1        | 1      | 2.7%    |
| WDC WD5001AALS-00E3A0 500GB           | 1        | 1      | 2.7%    |
| WDC WD5000LPVX-00V0TT0 500GB          | 1        | 1      | 2.7%    |
| WDC WD2500AAKS-60L9A0 250GB           | 1        | 1      | 2.7%    |
| WDC WD1600AAJS-00B4A0 160GB           | 1        | 1      | 2.7%    |
| WDC WD Green 2.5 1000GB               | 1        | 1      | 2.7%    |
| Toshiba DT01ACA100 1TB                | 1        | 1      | 2.7%    |
| Seagate ST3500820AS 500GB             | 1        | 1      | 2.7%    |
| Seagate ST3500413AS 500GB             | 1        | 1      | 2.7%    |
| Seagate ST3500312CS 500GB             | 1        | 1      | 2.7%    |
| Seagate ST340016A 40GB                | 1        | 1      | 2.7%    |
| Seagate ST3250620AS 250GB             | 1        | 1      | 2.7%    |
| Seagate ST3250312AS 250GB             | 1        | 1      | 2.7%    |
| Seagate ST31000528AS 1TB              | 1        | 1      | 2.7%    |
| Seagate ST3000DM001-9YN166 3TB        | 1        | 1      | 2.7%    |
| Seagate ST2000LM007-1R8174 2TB        | 1        | 1      | 2.7%    |
| Seagate ST1500DL003-9VT16L 1TB        | 1        | 1      | 2.7%    |
| Seagate ST1000DX001-1CM162 1TB        | 1        | 1      | 2.7%    |
| Samsung Electronics SSD 980 1TB       | 1        | 1      | 2.7%    |
| Samsung Electronics SSD 970 EVO 500GB | 1        | 1      | 2.7%    |
| Kingston SV300S37A60G 64GB SSD        | 1        | 1      | 2.7%    |
| Hitachi HTS542525K9A300 250GB         | 1        | 1      | 2.7%    |
| CHN25SATAS1 SSD 128 128GB             | 1        | 1      | 2.7%    |
| A-DATA Technology SU800NS38 512GB SSD | 1        | 2      | 2.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 12       | 19     | 35.29%  |
| WDC                 | 11       | 17     | 32.35%  |
| Samsung Electronics | 6        | 12     | 17.65%  |
| Toshiba             | 1        | 1      | 2.94%   |
| Kingston            | 1        | 1      | 2.94%   |
| Hitachi             | 1        | 1      | 2.94%   |
| CHN25SATAS1         | 1        | 1      | 2.94%   |
| A-DATA Technology   | 1        | 2      | 2.94%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 12       | 19     | 42.86%  |
| WDC                 | 10       | 15     | 35.71%  |
| Samsung Electronics | 4        | 10     | 14.29%  |
| Toshiba             | 1        | 1      | 3.57%   |
| Hitachi             | 1        | 1      | 3.57%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 20       | 46     | 74.07%  |
| SSD  | 4        | 5      | 14.81%  |
| NVMe | 3        | 3      | 11.11%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                                         | Desktops | Drives | Percent |
|---------------------------------------------------------------|----------|--------|---------|
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 1TB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 92       | 267    | 48.94%  |
| Works    | 70       | 189    | 37.23%  |
| Malfunc  | 25       | 54     | 13.3%   |
| Failed   | 1        | 1      | 0.53%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 98       | 43.17%  |
| AMD                              | 54       | 23.79%  |
| Samsung Electronics              | 21       | 9.25%   |
| Marvell Technology Group         | 7        | 3.08%   |
| JMicron Technology               | 7        | 3.08%   |
| Phison Electronics               | 6        | 2.64%   |
| Nvidia                           | 6        | 2.64%   |
| Kingston Technology Company      | 5        | 2.2%    |
| SanDisk                          | 4        | 1.76%   |
| ADATA Technology                 | 4        | 1.76%   |
| Shenzhen Longsys Electronics     | 3        | 1.32%   |
| MAXIO Technology (Hangzhou)      | 3        | 1.32%   |
| ASMedia Technology               | 3        | 1.32%   |
| Silicon Motion                   | 2        | 0.88%   |
| Realtek Semiconductor            | 2        | 0.88%   |
| Silicon Integrated Systems [SiS] | 1        | 0.44%   |
| Lite-On Technology               | 1        | 0.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                                              | Desktops | Percent |
|--------------------------------------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                                                | 25       | 8.71%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]                                     | 14       | 4.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                                                      | 12       | 4.18%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                                                  | 11       | 3.83%   |
| AMD 500 Series Chipset SATA Controller                                                                             | 10       | 3.48%   |
| AMD 400 Series Chipset SATA Controller                                                                             | 9        | 3.14%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                                                         | 7        | 2.44%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                                                          | 7        | 2.44%   |
| Intel 82801G (ICH7 Family) IDE Controller                                                                          | 7        | 2.44%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]                                       | 6        | 2.09%   |
| AMD 600 Series Chipset SATA Controller                                                                             | 6        | 2.09%   |
| Nvidia MCP61 SATA Controller                                                                                       | 5        | 1.74%   |
| Nvidia MCP61 IDE                                                                                                   | 5        | 1.74%   |
| JMicron JMB368 IDE controller                                                                                      | 5        | 1.74%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller                                      | 5        | 1.74%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                                                   | 5        | 1.74%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                                                  | 5        | 1.74%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                                                     | 4        | 1.39%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                                                         | 4        | 1.39%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                                                         | 4        | 1.39%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                                                        | 3        | 1.05%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                                                | 3        | 1.05%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                                           | 3        | 1.05%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]                                      | 3        | 1.05%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                                                 | 3        | 1.05%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                                                       | 3        | 1.05%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5)                            | 3        | 1.05%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3)                            | 3        | 1.05%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                                                      | 3        | 1.05%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                                                      | 3        | 1.05%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                                                      | 3        | 1.05%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                                               | 3        | 1.05%   |
| AMD FCH IDE Controller                                                                                             | 3        | 1.05%   |
| AMD 300 Series Chipset SATA Controller                                                                             | 3        | 1.05%   |
| Shenzhen Longsys FORESEE XP1000 / Lexar Professional CFexpress Type B Gold series, NM620 PCIe NVME SSD (DRAM-less) | 2        | 0.7%    |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)                                          | 2        | 0.7%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                                                      | 2        | 0.7%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                                                        | 2        | 0.7%    |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                                                       | 2        | 0.7%    |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                                                          | 2        | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 121      | 54.75%  |
| NVMe | 50       | 22.62%  |
| IDE  | 48       | 21.72%  |
| RAID | 2        | 0.9%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 97       | 61.39%  |
| AMD    | 61       | 38.61%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Intel Core i5-4570 CPU @ 3.20GHz              | 6        | 3.8%    |
| AMD Ryzen 5 3600 6-Core Processor             | 4        | 2.53%   |
| Intel Core i7-9700K CPU @ 3.60GHz             | 3        | 1.9%    |
| Intel Core i5-4460 CPU @ 3.20GHz              | 3        | 1.9%    |
| Intel Core i3-3220 CPU @ 3.30GHz              | 3        | 1.9%    |
| Intel Core i3-2120 CPU @ 3.30GHz              | 3        | 1.9%    |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 3        | 1.9%    |
| AMD Ryzen 7 3700X 8-Core Processor            | 3        | 1.9%    |
| AMD Ryzen 7 1700 Eight-Core Processor         | 3        | 1.9%    |
| AMD Ryzen 5 5600X 6-Core Processor            | 3        | 1.9%    |
| AMD Ryzen 5 5600G with Radeon Graphics        | 3        | 1.9%    |
| Intel Pentium Dual CPU E2200 @ 2.20GHz        | 2        | 1.27%   |
| Intel Pentium D CPU 3.40GHz                   | 2        | 1.27%   |
| Intel Pentium D CPU 2.80GHz                   | 2        | 1.27%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 2        | 1.27%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 2        | 1.27%   |
| Intel Core i5-7600K CPU @ 3.80GHz             | 2        | 1.27%   |
| Intel Core i5-2320 CPU @ 3.00GHz              | 2        | 1.27%   |
| Intel Core i5 CPU 650 @ 3.20GHz               | 2        | 1.27%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz         | 2        | 1.27%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz          | 2        | 1.27%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz          | 2        | 1.27%   |
| Intel Core 2 CPU 6300 @ 1.86GHz               | 2        | 1.27%   |
| Intel 12th Gen Core i3-12100F                 | 2        | 1.27%   |
| AMD Ryzen 9 7900X 12-Core Processor           | 2        | 1.27%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 2        | 1.27%   |
| AMD Ryzen 5 5500                              | 2        | 1.27%   |
| AMD FX-8350 Eight-Core Processor              | 2        | 1.27%   |
| AMD FX-6300 Six-Core Processor                | 2        | 1.27%   |
| AMD A8-7600 Radeon R7, 10 Compute Cores 4C+6G | 2        | 1.27%   |
| AMD A8-6600K APU with Radeon HD Graphics      | 2        | 1.27%   |
| AMD A4-6320 APU with Radeon HD Graphics       | 2        | 1.27%   |
| Intel Xeon CPU E5420 @ 2.50GHz                | 1        | 0.63%   |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz           | 1        | 0.63%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz   | 1        | 0.63%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz   | 1        | 0.63%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 1        | 0.63%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz   | 1        | 0.63%   |
| Intel Pentium Dual CPU E2220 @ 2.40GHz        | 1        | 0.63%   |
| Intel Pentium D CPU 3.00GHz                   | 1        | 0.63%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 26       | 16.46%  |
| AMD Ryzen 5             | 19       | 12.03%  |
| Intel Core i7           | 16       | 10.13%  |
| Intel Core i3           | 15       | 9.49%   |
| AMD Ryzen 7             | 9        | 5.7%    |
| Intel Core 2 Duo        | 8        | 5.06%   |
| AMD Ryzen 9             | 7        | 4.43%   |
| AMD FX                  | 6        | 3.8%    |
| Other                   | 5        | 3.16%   |
| Intel Pentium D         | 5        | 3.16%   |
| Intel Core 2 Quad       | 5        | 3.16%   |
| AMD A8                  | 5        | 3.16%   |
| Intel Pentium Dual-Core | 4        | 2.53%   |
| Intel Pentium Dual      | 3        | 1.9%    |
| AMD Athlon II X2        | 3        | 1.9%    |
| AMD Athlon 64 X2        | 3        | 1.9%    |
| Intel Xeon              | 2        | 1.27%   |
| Intel Core i9           | 2        | 1.27%   |
| Intel Core 2            | 2        | 1.27%   |
| Intel Celeron           | 2        | 1.27%   |
| AMD Ryzen Threadripper  | 2        | 1.27%   |
| AMD A4                  | 2        | 1.27%   |
| Intel Pentium 4         | 1        | 0.63%   |
| Intel Pentium           | 1        | 0.63%   |
| AMD Sempron             | 1        | 0.63%   |
| AMD Ryzen 5 PRO         | 1        | 0.63%   |
| AMD Ryzen 3             | 1        | 0.63%   |
| AMD Athlon II X3        | 1        | 0.63%   |
| AMD Athlon              | 1        | 0.63%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 50       | 31.45%  |
| 4       | 45       | 28.3%   |
| 6       | 27       | 16.98%  |
| 8       | 14       | 8.81%   |
| 12      | 6        | 3.77%   |
| 3       | 5        | 3.14%   |
| 16      | 4        | 2.52%   |
| 1       | 3        | 1.89%   |
| 24      | 2        | 1.26%   |
| 10      | 2        | 1.26%   |
| Unknown | 1        | 0.63%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 157      | 99.37%  |
| 2      | 1        | 0.63%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 84       | 52.83%  |
| 1       | 74       | 46.54%  |
| Unknown | 1        | 0.63%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 157      | 99.37%  |
| Unknown        | 1        | 0.63%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 68       | 41.98%  |
| 0x306c3    | 12       | 7.41%   |
| 0x1067a    | 8        | 4.94%   |
| 0x206a7    | 5        | 3.09%   |
| 0x08701021 | 5        | 3.09%   |
| 0x906ea    | 4        | 2.47%   |
| 0x10676    | 4        | 2.47%   |
| 0x6fd      | 3        | 1.85%   |
| 0x6fb      | 3        | 1.85%   |
| 0x306a9    | 3        | 1.85%   |
| 0x06001119 | 3        | 1.85%   |
| 0x06000852 | 3        | 1.85%   |
| 0xf65      | 2        | 1.23%   |
| 0xf47      | 2        | 1.23%   |
| 0x906ec    | 2        | 1.23%   |
| 0x6f2      | 2        | 1.23%   |
| 0x506e3    | 2        | 1.23%   |
| 0x0a50000d | 2        | 1.23%   |
| 0x0a201009 | 2        | 1.23%   |
| 0x08001137 | 2        | 1.23%   |
| 0x06003106 | 2        | 1.23%   |
| 0x010000c8 | 2        | 1.23%   |
| 0xf64      | 1        | 0.62%   |
| 0xf41      | 1        | 0.62%   |
| 0xb0671    | 1        | 0.62%   |
| 0x906ed    | 1        | 0.62%   |
| 0x906e9    | 1        | 0.62%   |
| 0x706a1    | 1        | 0.62%   |
| 0x306f2    | 1        | 0.62%   |
| 0x206d6    | 1        | 0.62%   |
| 0x20655    | 1        | 0.62%   |
| 0x20652    | 1        | 0.62%   |
| 0x106e5    | 1        | 0.62%   |
| 0x0a60120c | 1        | 0.62%   |
| 0x0a601206 | 1        | 0.62%   |
| 0x0a50000f | 1        | 0.62%   |
| 0x0a20120a | 1        | 0.62%   |
| 0x0a201016 | 1        | 0.62%   |
| 0x0800820d | 1        | 0.62%   |
| 0x08001138 | 1        | 0.62%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 22       | 13.92%  |
| Penryn           | 15       | 9.49%   |
| Zen 2            | 14       | 8.86%   |
| KabyLake         | 13       | 8.23%   |
| Zen 3            | 12       | 7.59%   |
| SandyBridge      | 11       | 6.96%   |
| Piledriver       | 10       | 6.33%   |
| Unknown          | 9        | 5.7%    |
| Core             | 8        | 5.06%   |
| NetBurst         | 6        | 3.8%    |
| Zen              | 5        | 3.16%   |
| K8 Hammer        | 4        | 2.53%   |
| K10              | 4        | 2.53%   |
| IvyBridge        | 4        | 2.53%   |
| Skylake          | 3        | 1.9%    |
| CometLake        | 3        | 1.9%    |
| Alderlake Hybrid | 3        | 1.9%    |
| Westmere         | 2        | 1.27%   |
| Steamroller      | 2        | 1.27%   |
| Nehalem          | 2        | 1.27%   |
| Zen+             | 1        | 0.63%   |
| TigerLake        | 1        | 0.63%   |
| Silvermont       | 1        | 0.63%   |
| Jaguar           | 1        | 0.63%   |
| Goldmont plus    | 1        | 0.63%   |
| Bulldozer        | 1        | 0.63%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 75       | 44.12%  |
| AMD    | 56       | 32.94%  |
| Intel  | 39       | 22.94%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 7        | 3.89%   |
| AMD Raphael                                                                 | 6        | 3.33%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 5        | 2.78%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 2.22%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 4        | 2.22%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4        | 2.22%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 3        | 1.67%   |
| Nvidia GK208B [GeForce GT 730]                                              | 3        | 1.67%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 1.67%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 3        | 1.67%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 1.67%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 3        | 1.67%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 3        | 1.67%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                 | 3        | 1.67%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 2        | 1.11%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 2        | 1.11%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 1.11%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 1.11%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 1.11%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2        | 1.11%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 1.11%   |
| Nvidia GF106 [GeForce GTS 450]                                              | 2        | 1.11%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 2        | 1.11%   |
| Nvidia G86 [GeForce 8500 GT]                                                | 2        | 1.11%   |
| Nvidia G84 [GeForce 8600 GT]                                                | 2        | 1.11%   |
| Nvidia G72 [GeForce 7300 GS]                                                | 2        | 1.11%   |
| Intel Skylake-S GT2 [HD Graphics 530]                                       | 2        | 1.11%   |
| Intel DG2 [Arc A380]                                                        | 2        | 1.11%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 2        | 1.11%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 2        | 1.11%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 2        | 1.11%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.11%   |
| AMD Richland [Radeon HD 8570D]                                              | 2        | 1.11%   |
| AMD Navi 33 [Radeon RX 7600/7600 XT/7600M XT/7600S/7700S / PRO W7600]       | 2        | 1.11%   |
| AMD Navi 32 [Radeon RX 7700 XT / 7800 XT]                                   | 2        | 1.11%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900 GRE/7900M]                     | 2        | 1.11%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 2        | 1.11%   |
| AMD Juniper XT [Radeon HD 6770]                                             | 2        | 1.11%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 2        | 1.11%   |
| AMD Bonaire XTX [Radeon R7 260X/360]                                        | 2        | 1.11%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 69       | 42.86%  |
| 1 x AMD        | 46       | 28.57%  |
| 1 x Intel      | 31       | 19.25%  |
| 2 x AMD        | 7        | 4.35%   |
| Intel + Nvidia | 3        | 1.86%   |
| AMD + Nvidia   | 2        | 1.24%   |
| 2 x Nvidia     | 1        | 0.62%   |
| 2 x Intel      | 1        | 0.62%   |
| Intel + AMD    | 1        | 0.62%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 111      | 68.52%  |
| Proprietary | 42       | 25.93%  |
| Unknown     | 9        | 5.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 66       | 40.49%  |
| 0.01-0.5   | 23       | 14.11%  |
| 0.51-1.0   | 18       | 11.04%  |
| 1.01-2.0   | 14       | 8.59%   |
| 3.01-4.0   | 12       | 7.36%   |
| 7.01-8.0   | 11       | 6.75%   |
| 5.01-6.0   | 9        | 5.52%   |
| 16.01-24.0 | 4        | 2.45%   |
| 8.01-16.0  | 4        | 2.45%   |
| 2.01-3.0   | 2        | 1.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 33       | 19.64%  |
| Goldstar             | 25       | 14.88%  |
| Philips              | 17       | 10.12%  |
| Dell                 | 16       | 9.52%   |
| AOC                  | 12       | 7.14%   |
| Hewlett-Packard      | 10       | 5.95%   |
| BenQ                 | 10       | 5.95%   |
| Ancor Communications | 7        | 4.17%   |
| Unknown              | 4        | 2.38%   |
| LG Electronics       | 4        | 2.38%   |
| Lenovo               | 4        | 2.38%   |
| ASUSTek Computer     | 4        | 2.38%   |
| NEC Computers        | 3        | 1.79%   |
| ViewSonic            | 2        | 1.19%   |
| MSI                  | 2        | 1.19%   |
| Mi                   | 2        | 1.19%   |
| Arnos Instruments    | 2        | 1.19%   |
| Wacom                | 1        | 0.6%    |
| SKG                  | 1        | 0.6%    |
| Plain Tree Systems   | 1        | 0.6%    |
| IBM                  | 1        | 0.6%    |
| HYO                  | 1        | 0.6%    |
| Gigabyte Technology  | 1        | 0.6%    |
| FUS                  | 1        | 0.6%    |
| Fujitsu Siemens      | 1        | 0.6%    |
| AUS                  | 1        | 0.6%    |
| Acer                 | 1        | 0.6%    |
| Unknown              | 1        | 0.6%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch              | 3        | 1.68%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 3        | 1.68%   |
| Goldstar L194WT GSM4B06 1440x900 408x255mm 18.9-inch                  | 3        | 1.68%   |
| Samsung Electronics SyncMaster SAM0059 2048x1536 320x240mm 15.7-inch  | 2        | 1.12%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch     | 2        | 1.12%   |
| LG Electronics LCD Monitor LG TV 1920x1080                            | 2        | 1.12%   |
| Lenovo P24q-10 LEN61A5 2560x1440 527x296mm 23.8-inch                  | 2        | 1.12%   |
| Hewlett-Packard w19b/w19e HWP26A1 1440x900 410x256mm 19.0-inch        | 2        | 1.12%   |
| Goldstar ULTRAWIDE GSM59F2 2560x1080 677x290mm 29.0-inch              | 2        | 1.12%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 2        | 1.12%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 2        | 1.12%   |
| BenQ XL2411Z BNQ7F31 1920x1080 531x298mm 24.0-inch                    | 2        | 1.12%   |
| AOC U2879G6 AOC2879 3840x2160 621x341mm 27.9-inch                     | 2        | 1.12%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                        | 2        | 1.12%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch | 2        | 1.12%   |
| Wacom CintiqPro24P WAC1063 3840x2160 522x293mm 23.6-inch              | 1        | 0.56%   |
| ViewSonic VA703-3Series VSC631E 1280x1024 338x270mm 17.0-inch         | 1        | 0.56%   |
| ViewSonic VA503 SERIES VSCEF1D 1024x768 304x228mm 15.0-inch           | 1        | 0.56%   |
| Unknown LCD Monitor Sharp LL-S201A 1920x1080                          | 1        | 0.56%   |
| Unknown LCD Monitor HYO DUAL-DVI 2560x1440                            | 1        | 0.56%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1        | 0.56%   |
| Unknown LCD Monitor Dell S2417DG 2560x1440                            | 1        | 0.56%   |
| SKG DEXP DF27N1 SKG2713 1920x1080 597x336mm 27.0-inch                 | 1        | 0.56%   |
| Samsung Electronics T19C300 SAM0A98 1366x768 410x230mm 18.5-inch      | 1        | 0.56%   |
| Samsung Electronics SyncMaster SAM0485 1920x1080 520x320mm 24.0-inch  | 1        | 0.56%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch  | 1        | 0.56%   |
| Samsung Electronics SyncMaster SAM036C 1920x1200 550x343mm 25.5-inch  | 1        | 0.56%   |
| Samsung Electronics SyncMaster SAM02F6 1280x1024 340x270mm 17.1-inch  | 1        | 0.56%   |
| Samsung Electronics SyncMaster SAM0273 1440x900 410x257mm 19.1-inch   | 1        | 0.56%   |
| Samsung Electronics SyncMaster SAM026E 1280x1024 376x301mm 19.0-inch  | 1        | 0.56%   |
| Samsung Electronics SyncMaster SAM0259 1280x1024 376x301mm 19.0-inch  | 1        | 0.56%   |
| Samsung Electronics SyncMaster SAM0217 1280x1024 376x301mm 19.0-inch  | 1        | 0.56%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch  | 1        | 0.56%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 340x270mm 17.1-inch  | 1        | 0.56%   |
| Samsung Electronics SyncMaster SAM006B 1280x1024 338x270mm 17.0-inch  | 1        | 0.56%   |
| Samsung Electronics SA300/SA350 SAM0793 1920x1080 531x299mm 24.0-inch | 1        | 0.56%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1        | 0.56%   |
| Samsung Electronics S24E391 SAM0C12 1920x1080 521x293mm 23.5-inch     | 1        | 0.56%   |
| Samsung Electronics S24E390 SAM0C1A 1920x1080 521x293mm 23.5-inch     | 1        | 0.56%   |
| Samsung Electronics S23B350 SAM08D5 1920x1080 510x287mm 23.0-inch     | 1        | 0.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 56       | 34.57%  |
| 2560x1440 (QHD)    | 22       | 13.58%  |
| 3840x2160 (4K)     | 16       | 9.88%   |
| 1280x1024 (SXGA)   | 16       | 9.88%   |
| 1680x1050 (WSXGA+) | 9        | 5.56%   |
| 1440x900 (WXGA+)   | 9        | 5.56%   |
| 2560x1080          | 6        | 3.7%    |
| 1920x1200 (WUXGA)  | 4        | 2.47%   |
| 1366x768 (WXGA)    | 4        | 2.47%   |
| Unknown            | 4        | 2.47%   |
| 1600x900 (HD+)     | 3        | 1.85%   |
| 4480x1440          | 2        | 1.23%   |
| 2048x1536          | 2        | 1.23%   |
| 1024x768 (XGA)     | 2        | 1.23%   |
| 3840x1080          | 1        | 0.62%   |
| 3520x1200          | 1        | 0.62%   |
| 3440x1440          | 1        | 0.62%   |
| 2960x1050          | 1        | 0.62%   |
| 2288x1287          | 1        | 0.62%   |
| 1360x768           | 1        | 0.62%   |
| 1280x960           | 1        | 0.62%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 30       | 17.96%  |
| 27      | 22       | 13.17%  |
| Unknown | 18       | 10.78%  |
| 23      | 13       | 7.78%   |
| 19      | 13       | 7.78%   |
| 21      | 11       | 6.59%   |
| 18      | 8        | 4.79%   |
| 17      | 8        | 4.79%   |
| 34      | 7        | 4.19%   |
| 31      | 7        | 4.19%   |
| 22      | 6        | 3.59%   |
| 20      | 5        | 2.99%   |
| 25      | 4        | 2.4%    |
| 15      | 4        | 2.4%    |
| 40      | 3        | 1.8%    |
| 28      | 2        | 1.2%    |
| 26      | 2        | 1.2%    |
| 142     | 1        | 0.6%    |
| 84      | 1        | 0.6%    |
| 33      | 1        | 0.6%    |
| 14      | 1        | 0.6%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 61       | 38.61%  |
| 401-500        | 32       | 20.25%  |
| Unknown        | 18       | 11.39%  |
| 601-700        | 12       | 7.59%   |
| 301-350        | 12       | 7.59%   |
| 351-400        | 9        | 5.7%    |
| 701-800        | 8        | 5.06%   |
| 801-900        | 3        | 1.9%    |
| More than 2000 | 1        | 0.63%   |
| 201-300        | 1        | 0.63%   |
| 1501-2000      | 1        | 0.63%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 79       | 51.63%  |
| 16/10   | 27       | 17.65%  |
| 5/4     | 17       | 11.11%  |
| Unknown | 17       | 11.11%  |
| 21/9    | 7        | 4.58%   |
| 4/3     | 5        | 3.27%   |
| 1.00    | 1        | 0.65%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 48       | 29.27%  |
| 301-350        | 23       | 14.02%  |
| 151-200        | 22       | 13.41%  |
| Unknown        | 18       | 10.98%  |
| 351-500        | 17       | 10.37%  |
| 251-300        | 14       | 8.54%   |
| 141-150        | 12       | 7.32%   |
| 101-110        | 3        | 1.83%   |
| 501-1000       | 3        | 1.83%   |
| More than 1000 | 2        | 1.22%   |
| 111-120        | 2        | 1.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 98       | 62.42%  |
| 101-120 | 24       | 15.29%  |
| Unknown | 18       | 11.46%  |
| 121-160 | 12       | 7.64%   |
| 161-240 | 4        | 2.55%   |
| 1-50    | 1        | 0.64%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 133      | 83.13%  |
| 2     | 19       | 11.88%  |
| 0     | 6        | 3.75%   |
| 3     | 2        | 1.25%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 90       | 42.45%  |
| Intel                             | 53       | 25%     |
| TP-Link                           | 11       | 5.19%   |
| Qualcomm Atheros                  | 9        | 4.25%   |
| Broadcom                          | 7        | 3.3%    |
| Ralink Technology                 | 6        | 2.83%   |
| Ralink                            | 4        | 1.89%   |
| Nvidia                            | 4        | 1.89%   |
| Xiaomi                            | 3        | 1.42%   |
| Qualcomm Atheros Communications   | 3        | 1.42%   |
| MediaTek                          | 3        | 1.42%   |
| Samsung Electronics               | 2        | 0.94%   |
| Qualcomm Technologies             | 2        | 0.94%   |
| Marvell Technology Group          | 2        | 0.94%   |
| Broadcom Limited                  | 2        | 0.94%   |
| ASIX Electronics                  | 2        | 0.94%   |
| Wilocity                          | 1        | 0.47%   |
| vivo                              | 1        | 0.47%   |
| U-Blox                            | 1        | 0.47%   |
| Sundance Technology Inc / IC Plus | 1        | 0.47%   |
| Silicon Integrated Systems [SiS]  | 1        | 0.47%   |
| Huawei Technologies               | 1        | 0.47%   |
| DisplayLink                       | 1        | 0.47%   |
| Aquantia                          | 1        | 0.47%   |
| 3Com                              | 1        | 0.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 74       | 31.09%  |
| Realtek RTL8125 2.5GbE Controller                                      | 11       | 4.62%   |
| Intel I211 Gigabit Network Connection                                  | 6        | 2.52%   |
| Intel Wi-Fi 6 AX200                                                    | 5        | 2.1%    |
| Intel Ethernet Connection (7) I219-V                                   | 5        | 2.1%    |
| Intel Ethernet Connection (2) I219-V                                   | 5        | 2.1%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 4        | 1.68%   |
| Ralink RT5370 Wireless Adapter                                         | 4        | 1.68%   |
| Intel Ethernet Controller I225-V                                       | 4        | 1.68%   |
| Intel Ethernet Connection I217-LM                                      | 4        | 1.68%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 3        | 1.26%   |
| Qualcomm Atheros AR9271 802.11n                                        | 3        | 1.26%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 3        | 1.26%   |
| Nvidia MCP61 Ethernet                                                  | 3        | 1.26%   |
| Intel Wireless 8260                                                    | 3        | 1.26%   |
| Intel Ethernet Connection I217-V                                       | 3        | 1.26%   |
| Intel 82579V Gigabit Network Connection                                | 3        | 1.26%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 2        | 0.84%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 2        | 0.84%   |
| TP-Link 802.11ac WLAN Adapter                                          | 2        | 0.84%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2        | 0.84%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 2        | 0.84%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 2        | 0.84%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                             | 2        | 0.84%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                              | 2        | 0.84%   |
| Qualcomm WCN785x Wi-Fi 7(802.11be) 320MHz 2x2 [FastConnect 7800]       | 2        | 0.84%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 2        | 0.84%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 2        | 0.84%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 2        | 0.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2        | 0.84%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 2        | 0.84%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express                | 2        | 0.84%   |
| ASIX AX88772B                                                          | 2        | 0.84%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1        | 0.42%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                     | 1        | 0.42%   |
| vivo 1820                                                              | 1        | 0.42%   |
| U-Blox [u-blox 7]                                                      | 1        | 0.42%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                  | 1        | 0.42%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                    | 1        | 0.42%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                    | 1        | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 17       | 28.33%  |
| TP-Link                         | 11       | 18.33%  |
| Realtek Semiconductor           | 10       | 16.67%  |
| Ralink Technology               | 6        | 10%     |
| Ralink                          | 4        | 6.67%   |
| Qualcomm Atheros Communications | 3        | 5%      |
| MediaTek                        | 3        | 5%      |
| Qualcomm Atheros                | 2        | 3.33%   |
| Broadcom                        | 2        | 3.33%   |
| Wilocity                        | 1        | 1.67%   |
| Broadcom Limited                | 1        | 1.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 5        | 8.2%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 4        | 6.56%   |
| Ralink RT5370 Wireless Adapter                                       | 4        | 6.56%   |
| Qualcomm Atheros AR9271 802.11n                                      | 3        | 4.92%   |
| Intel Wireless 8260                                                  | 3        | 4.92%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 2        | 3.28%   |
| TP-Link 802.11ac WLAN Adapter                                        | 2        | 3.28%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 2        | 3.28%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                            | 2        | 3.28%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                              | 2        | 3.28%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 2        | 3.28%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                   | 1        | 1.64%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                | 1        | 1.64%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                  | 1        | 1.64%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                  | 1        | 1.64%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 1        | 1.64%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                      | 1        | 1.64%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                           | 1        | 1.64%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                               | 1        | 1.64%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 1        | 1.64%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 1        | 1.64%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 1        | 1.64%   |
| Realtek 802.11ac NIC                                                 | 1        | 1.64%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 1        | 1.64%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                    | 1        | 1.64%   |
| Ralink MT7601U Wireless Adapter                                      | 1        | 1.64%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                            | 1        | 1.64%   |
| Ralink RT2561/RT61 rev B 802.11g                                     | 1        | 1.64%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 1        | 1.64%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                     | 1        | 1.64%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 1        | 1.64%   |
| Intel Wireless 7265                                                  | 1        | 1.64%   |
| Intel WiFi Link 5100                                                 | 1        | 1.64%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 1        | 1.64%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 1        | 1.64%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 1        | 1.64%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 1        | 1.64%   |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 1        | 1.64%   |
| Broadcom Network controller                                          | 1        | 1.64%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 1        | 1.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 87       | 52.1%   |
| Intel                             | 46       | 27.54%  |
| Qualcomm Atheros                  | 7        | 4.19%   |
| Broadcom                          | 5        | 2.99%   |
| Nvidia                            | 4        | 2.4%    |
| Xiaomi                            | 3        | 1.8%    |
| Samsung Electronics               | 2        | 1.2%    |
| Qualcomm Technologies             | 2        | 1.2%    |
| Marvell Technology Group          | 2        | 1.2%    |
| ASIX Electronics                  | 2        | 1.2%    |
| vivo                              | 1        | 0.6%    |
| Sundance Technology Inc / IC Plus | 1        | 0.6%    |
| Silicon Integrated Systems [SiS]  | 1        | 0.6%    |
| DisplayLink                       | 1        | 0.6%    |
| Broadcom Limited                  | 1        | 0.6%    |
| Aquantia                          | 1        | 0.6%    |
| 3Com                              | 1        | 0.6%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller     | 74       | 42.29%  |
| Realtek RTL8125 2.5GbE Controller                                          | 11       | 6.29%   |
| Intel I211 Gigabit Network Connection                                      | 6        | 3.43%   |
| Intel Ethernet Connection (7) I219-V                                       | 5        | 2.86%   |
| Intel Ethernet Connection (2) I219-V                                       | 5        | 2.86%   |
| Intel Ethernet Controller I225-V                                           | 4        | 2.29%   |
| Intel Ethernet Connection I217-LM                                          | 4        | 2.29%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 3        | 1.71%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 3        | 1.71%   |
| Nvidia MCP61 Ethernet                                                      | 3        | 1.71%   |
| Intel Ethernet Connection I217-V                                           | 3        | 1.71%   |
| Intel 82579V Gigabit Network Connection                                    | 3        | 1.71%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                       | 2        | 1.14%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 2        | 1.14%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 2        | 1.14%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 2        | 1.14%   |
| Qualcomm WCN785x Wi-Fi 7(802.11be) 320MHz 2x2 [FastConnect 7800]           | 2        | 1.14%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                    | 2        | 1.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 2        | 1.14%   |
| Intel 82566DM-2 Gigabit Network Connection                                 | 2        | 1.14%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express                    | 2        | 1.14%   |
| ASIX AX88772B                                                              | 2        | 1.14%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 1        | 0.57%   |
| vivo 1820                                                                  | 1        | 0.57%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.57%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter              | 1        | 0.57%   |
| Realtek RTL8126 5GbE Controller                                            | 1        | 0.57%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                  | 1        | 0.57%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 1        | 0.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 1        | 0.57%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                   | 1        | 0.57%   |
| Nvidia MCP67 Ethernet                                                      | 1        | 0.57%   |
| Intel Ethernet Connection (6) I219-V                                       | 1        | 0.57%   |
| Intel Ethernet Connection (2) I219-LM                                      | 1        | 0.57%   |
| Intel Ethernet Connection (2) I218-V                                       | 1        | 0.57%   |
| Intel Ethernet Connection (17) I219-V                                      | 1        | 0.57%   |
| Intel Ethernet Connection (14) I219-V                                      | 1        | 0.57%   |
| Intel Ethernet Connection (13) I219-V                                      | 1        | 0.57%   |
| Intel Ethernet Connection (12) I219-V                                      | 1        | 0.57%   |
| Intel 82578DM Gigabit Network Connection                                   | 1        | 0.57%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 156      | 72.22%  |
| WiFi     | 58       | 26.85%  |
| Modem    | 2        | 0.93%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 126      | 77.78%  |
| WiFi     | 36       | 22.22%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 109      | 68.99%  |
| 2     | 41       | 25.95%  |
| 3     | 5        | 3.16%   |
| 0     | 3        | 1.9%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 152      | 96.2%   |
| Yes  | 6        | 3.8%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 16       | 34.04%  |
| Cambridge Silicon Radio | 12       | 25.53%  |
| Realtek Semiconductor   | 5        | 10.64%  |
| ASUSTek Computer        | 4        | 8.51%   |
| TP-Link                 | 3        | 6.38%   |
| MediaTek                | 2        | 4.26%   |
| IMC Networks            | 2        | 4.26%   |
| Foxconn / Hon Hai       | 2        | 4.26%   |
| Apple                   | 1        | 2.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 12       | 25.53%  |
| Intel AX200 Bluetooth                               | 5        | 10.64%  |
| Intel Bluetooth wireless interface                  | 4        | 8.51%   |
| TP-Link TP-T@- UB500 Adapter                        | 3        | 6.38%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3        | 6.38%   |
| Realtek Bluetooth Radio                             | 2        | 4.26%   |
| Realtek Bluetooth 5.3 Radio                         | 2        | 4.26%   |
| MediaTek Wireless_Device                            | 2        | 4.26%   |
| IMC Networks Bluetooth Radio                        | 2        | 4.26%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2        | 4.26%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2        | 4.26%   |
| Realtek Bluetooth 5.4 Radio                         | 1        | 2.13%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 2.13%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 2.13%   |
| Intel AX210 Bluetooth                               | 1        | 2.13%   |
| Intel AX201 Bluetooth                               | 1        | 2.13%   |
| ASUS Bluetooth Device                               | 1        | 2.13%   |
| ASUS ASUS USB-BT500                                 | 1        | 2.13%   |
| Apple Bluetooth Host Controller                     | 1        | 2.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 96       | 33.8%   |
| AMD                                          | 74       | 26.06%  |
| Nvidia                                       | 66       | 23.24%  |
| C-Media Electronics                          | 9        | 3.17%   |
| Logitech                                     | 4        | 1.41%   |
| Creative Technology                          | 3        | 1.06%   |
| Yamaha                                       | 2        | 0.7%    |
| Texas Instruments                            | 2        | 0.7%    |
| MV-SILICON                                   | 2        | 0.7%    |
| Micro Star International                     | 2        | 0.7%    |
| Hewlett-Packard                              | 2        | 0.7%    |
| Focusrite-Novation                           | 2        | 0.7%    |
| Creative Labs                                | 2        | 0.7%    |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.35%   |
| Trust                                        | 1        | 0.35%   |
| Syntek                                       | 1        | 0.35%   |
| SteelSeries ApS                              | 1        | 0.35%   |
| Silicon Integrated Systems [SiS]             | 1        | 0.35%   |
| RODE Microphones                             | 1        | 0.35%   |
| Realtek Semiconductor                        | 1        | 0.35%   |
| Razer USA                                    | 1        | 0.35%   |
| Patriot Memory                               | 1        | 0.35%   |
| KTMicro                                      | 1        | 0.35%   |
| Kingston Technology                          | 1        | 0.35%   |
| JMTek                                        | 1        | 0.35%   |
| FIFINE 683 Microphone                        | 1        | 0.35%   |
| BTD 600                                      | 1        | 0.35%   |
| AudioQuest                                   | 1        | 0.35%   |
| ASUSTek Computer                             | 1        | 0.35%   |
| ASRock                                       | 1        | 0.35%   |
| Unknown                                      | 1        | 0.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 17       | 5.09%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 14       | 4.19%   |
| AMD Ryzen HD Audio Controller                                              | 14       | 4.19%   |
| Nvidia TU116 High Definition Audio Controller                              | 9        | 2.69%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 9        | 2.69%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 9        | 2.69%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 9        | 2.69%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 8        | 2.4%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 8        | 2.4%    |
| Intel Cannon Lake PCH cAVS                                                 | 7        | 2.1%    |
| Intel 9 Series Chipset Family HD Audio Controller                          | 7        | 2.1%    |
| AMD FCH Azalia Controller                                                  | 7        | 2.1%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 6        | 1.8%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 6        | 1.8%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6        | 1.8%    |
| AMD Radeon High Definition Audio Controller                                | 6        | 1.8%    |
| AMD Navi 31 HDMI/DP Audio                                                  | 6        | 1.8%    |
| Nvidia MCP61 High Definition Audio                                         | 5        | 1.5%    |
| Nvidia GP106 High Definition Audio Controller                              | 5        | 1.5%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 5        | 1.5%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 5        | 1.5%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 5        | 1.5%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5        | 1.5%    |
| Nvidia GP107GL High Definition Audio Controller                            | 4        | 1.2%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4        | 1.2%    |
| Intel 200 Series PCH HD Audio                                              | 4        | 1.2%    |
| Nvidia TU106 High Definition Audio Controller                              | 3        | 0.9%    |
| Nvidia GA104 High Definition Audio Controller                              | 3        | 0.9%    |
| Intel Alder Lake-S HD Audio Controller                                     | 3        | 0.9%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 0.9%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3        | 0.9%    |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 3        | 0.9%    |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 3        | 0.9%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 3        | 0.9%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3        | 0.9%    |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                             | 3        | 0.9%    |
| Yamaha Steinberg UR22mkII                                                  | 2        | 0.6%    |
| Nvidia TU104 HD Audio Controller                                           | 2        | 0.6%    |
| Nvidia High Definition Audio Controller                                    | 2        | 0.6%    |
| Nvidia GP108 High Definition Audio Controller                              | 2        | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 24       | 24.74%  |
| Unknown                      | 19       | 19.59%  |
| Crucial                      | 13       | 13.4%   |
| G.Skill                      | 12       | 12.37%  |
| Corsair                      | 8        | 8.25%   |
| SK hynix                     | 3        | 3.09%   |
| GOODRAM                      | 3        | 3.09%   |
| A-DATA Technology            | 3        | 3.09%   |
| Samsung Electronics          | 2        | 2.06%   |
| Micron Technology            | 2        | 2.06%   |
| Team                         | 1        | 1.03%   |
| Ramos Technology             | 1        | 1.03%   |
| Patriot Memory (PDP Systems) | 1        | 1.03%   |
| Nanya Technology             | 1        | 1.03%   |
| Lexar                        | 1        | 1.03%   |
| Heoriady                     | 1        | 1.03%   |
| Apacer                       | 1        | 1.03%   |
| Unknown                      | 1        | 1.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                    | Desktops | Percent |
|--------------------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM 1333MT/s                                     | 2        | 1.75%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                                 | 2        | 1.75%   |
| Unknown RAM Module 2048MB DIMM SDRAM                                     | 2        | 1.75%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                                   | 2        | 1.75%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                                   | 2        | 1.75%   |
| Kingston RAM KHX3466C16D4/16GX 16GB DIMM DDR4 3466MT/s                   | 2        | 1.75%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s                      | 2        | 1.75%   |
| Kingston RAM KHX1600C9D3/8GX 8GB DIMM DDR3 2133MT/s                      | 2        | 1.75%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1867MT/s                      | 2        | 1.75%   |
| Kingston RAM KHX1600C10D3/8GX 8GB DIMM DDR3 1600MT/s                     | 2        | 1.75%   |
| G.Skill RAM F3-1600C11-8GIS 8GB DIMM DDR3 1600MT/s                       | 2        | 1.75%   |
| Crucial RAM BL8G32C16U4B.M8FE 8GB DIMM DDR4 4333MT/s                     | 2        | 1.75%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                                     | 1        | 0.88%   |
| Unknown RAM Module 4096MB DIMM DDR3 667MT/s                              | 1        | 0.88%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                             | 1        | 0.88%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                                  | 1        | 0.88%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                                 | 1        | 0.88%   |
| Unknown RAM Module 2048MB DIMM SDRAM 1333MT/s                            | 1        | 0.88%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                              | 1        | 0.88%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                                   | 1        | 0.88%   |
| Unknown RAM Module 2048MB DIMM 1066MT/s                                  | 1        | 0.88%   |
| Unknown RAM Module 2048MB DIMM                                           | 1        | 0.88%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                                 | 1        | 0.88%   |
| Unknown RAM Module 1024MB DIMM SDRAM                                     | 1        | 0.88%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                              | 1        | 0.88%   |
| Unknown RAM Module 1024MB DIMM DDR 667MT/s                               | 1        | 0.88%   |
| Unknown RAM Module 1024MB DIMM DDR 533MT/s                               | 1        | 0.88%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                                   | 1        | 0.88%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s                       | 1        | 0.88%   |
| SK hynix RAM HYMP564U64CP8-Y5 512MB DIMM DDR 667MT/s                     | 1        | 0.88%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB DIMM DDR3 1600MT/s                     | 1        | 0.88%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s                     | 1        | 0.88%   |
| Samsung RAM M393A1G40DB0-CPB 8GB DIMM DDR4 2667MT/s                      | 1        | 0.88%   |
| Samsung RAM M3 78T2863QZS-CE6 1GB DIMM DDR2 1639MT/s                     | 1        | 0.88%   |
| Ramos RAM RMB2GE484CA5-13HC 2048MB DIMM 533MT/s                          | 1        | 0.88%   |
| Patriot Memory (PDP Systems) RAM 3600 C18 Series 16GB DIMM DDR4 3600MT/s | 1        | 0.88%   |
| Nanya RAM M2X2G64CB88G7N-DG 2GB DIMM DDR3 1600MT/s                       | 1        | 0.88%   |
| Micron RAM 8JTF25664AZ-1G6M1 2GB DIMM DDR3 1600MT/s                      | 1        | 0.88%   |
| Micron RAM 8HTF12864AY-667E1 1GB DIMM DDR2 667MT/s                       | 1        | 0.88%   |
| Lexar RAM LD4AU008G-H2666GST 8GB DIMM DDR4 2667MT/s                      | 1        | 0.88%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 32       | 38.55%  |
| DDR3    | 25       | 30.12%  |
| Unknown | 9        | 10.84%  |
| DDR2    | 6        | 7.23%   |
| SDRAM   | 5        | 6.02%   |
| DDR5    | 4        | 4.82%   |
| DDR     | 2        | 2.41%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 80       | 97.56%  |
| SODIMM | 2        | 2.44%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 30       | 31.25%  |
| 4096  | 19       | 19.79%  |
| 2048  | 17       | 17.71%  |
| 16384 | 12       | 12.5%   |
| 1024  | 9        | 9.38%   |
| 32768 | 7        | 7.29%   |
| 49152 | 1        | 1.04%   |
| 512   | 1        | 1.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 14       | 13.86%  |
| 1333    | 10       | 9.9%    |
| 667     | 10       | 9.9%    |
| 3200    | 8        | 7.92%   |
| 3600    | 7        | 6.93%   |
| 2133    | 7        | 6.93%   |
| 2667    | 5        | 4.95%   |
| 800     | 5        | 4.95%   |
| 2400    | 4        | 3.96%   |
| 3466    | 3        | 2.97%   |
| Unknown | 3        | 2.97%   |
| 4333    | 2        | 1.98%   |
| 1800    | 2        | 1.98%   |
| 1066    | 2        | 1.98%   |
| 533     | 2        | 1.98%   |
| 6200    | 1        | 0.99%   |
| 6000    | 1        | 0.99%   |
| 5200    | 1        | 0.99%   |
| 4800    | 1        | 0.99%   |
| 3866    | 1        | 0.99%   |
| 3800    | 1        | 0.99%   |
| 3733    | 1        | 0.99%   |
| 3666    | 1        | 0.99%   |
| 3400    | 1        | 0.99%   |
| 3100    | 1        | 0.99%   |
| 3000    | 1        | 0.99%   |
| 2666    | 1        | 0.99%   |
| 2134    | 1        | 0.99%   |
| 1867    | 1        | 0.99%   |
| 1866    | 1        | 0.99%   |
| 1639    | 1        | 0.99%   |
| 1632    | 1        | 0.99%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 3        | 33.33%  |
| Samsung Electronics | 2        | 22.22%  |
| Canon               | 2        | 22.22%  |
| Seiko Epson         | 1        | 11.11%  |
| Brother Industries  | 1        | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Desktops | Percent |
|---------------------------|----------|---------|
| Seiko Epson L3110 Series  | 1        | 11.11%  |
| Samsung SCX-4216F Scanner | 1        | 11.11%  |
| Samsung Composite Device  | 1        | 11.11%  |
| HP Officejet 4500 G510g-m | 1        | 11.11%  |
| HP LaserJet 1010          | 1        | 11.11%  |
| HP DeskJet 5940           | 1        | 11.11%  |
| Canon PIXMA MG3000 series | 1        | 11.11%  |
| Canon MP140 ser           | 1        | 11.11%  |
| Brother DCP-L2510D series | 1        | 11.11%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| Mustek Systems | 2        | 66.67%  |
| Seiko Epson    | 1        | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Mustek Systems ScanExpress 1200 UB | 2        | 66.67%  |
| Seiko Epson Perfection V37/V370    | 1        | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Logitech                    | 15       | 38.46%  |
| Microdia                    | 4        | 10.26%  |
| Z-Star Microelectronics     | 3        | 7.69%   |
| Apple                       | 3        | 7.69%   |
| Tobii Technology AB         | 1        | 2.56%   |
| SunplusIT                   | 1        | 2.56%   |
| Samsung Electronics         | 1        | 2.56%   |
| Razer USA                   | 1        | 2.56%   |
| Pixart Imaging              | 1        | 2.56%   |
| Philips (or NXP)            | 1        | 2.56%   |
| Microsoft                   | 1        | 2.56%   |
| KYE Systems (Mouse Systems) | 1        | 2.56%   |
| Jieli Technology            | 1        | 2.56%   |
| Genesys Logic               | 1        | 2.56%   |
| GEMBIRD                     | 1        | 2.56%   |
| Cubeternet                  | 1        | 2.56%   |
| Chicony Electronics         | 1        | 2.56%   |
| A4Tech                      | 1        | 2.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Logitech Webcam C270                        | 3        | 7.69%   |
| Logitech Webcam C170                        | 3        | 7.69%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X             | 3        | 7.69%   |
| Z-Star Full HD 1080P PC Camera              | 2        | 5.13%   |
| Z-Star Vega USB 2.0 Camera                  | 1        | 2.56%   |
| Tobii AB EyeChip                            | 1        | 2.56%   |
| SunplusIT USB 2.0 Camera                    | 1        | 2.56%   |
| Samsung Galaxy series, misc. (MTP mode)     | 1        | 2.56%   |
| Razer USA Gaming Webcam [Kiyo]              | 1        | 2.56%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro        | 1        | 2.56%   |
| Philips (or NXP) SPZ5000 Webcam             | 1        | 2.56%   |
| Microsoft LifeCam Cinema                    | 1        | 2.56%   |
| Microdia Webcam Vitade AF                   | 1        | 2.56%   |
| Microdia Defender G-Lens 2577 HD720p Camera | 1        | 2.56%   |
| Microdia CyberTrack H7                      | 1        | 2.56%   |
| Microdia Camera                             | 1        | 2.56%   |
| Logitech Webcam C310                        | 1        | 2.56%   |
| Logitech Webcam C250                        | 1        | 2.56%   |
| Logitech Webcam C210                        | 1        | 2.56%   |
| Logitech QuickCam Pro 9000                  | 1        | 2.56%   |
| Logitech QuickCam Communicate MP/S5500      | 1        | 2.56%   |
| Logitech HD Webcam C615                     | 1        | 2.56%   |
| Logitech HD Webcam C525                     | 1        | 2.56%   |
| Logitech HD Webcam C510                     | 1        | 2.56%   |
| Logitech BRIO Ultra HD Webcam               | 1        | 2.56%   |
| KYE Systems (Mouse Systems) eFace 2050AF    | 1        | 2.56%   |
| Jieli USB Composite Device                  | 1        | 2.56%   |
| Genesys Logic Camera                        | 1        | 2.56%   |
| GEMBIRD USB2.0 PC CAMERA                    | 1        | 2.56%   |
| Cubeternet USB2.0 Camera                    | 1        | 2.56%   |
| Chicony HP High Definition Webcam           | 1        | 2.56%   |
| A4Tech A4tech FHD 1080P PC Camera           | 1        | 2.56%   |

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
| Alcor Micro      | 5        | 83.33%  |
| SCM Microsystems | 1        | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Alcor Micro AU9540 Smartcard Reader                    | 5        | 83.33%  |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 1        | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 135      | 83.85%  |
| 1     | 24       | 14.91%  |
| 2     | 2        | 1.24%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 10       | 37.04%  |
| Chipcard                 | 4        | 14.81%  |
| Net/wireless             | 3        | 11.11%  |
| Communication controller | 3        | 11.11%  |
| Unassigned class         | 1        | 3.7%    |
| Storage/raid             | 1        | 3.7%    |
| Sound                    | 1        | 3.7%    |
| Network                  | 1        | 3.7%    |
| Net/ethernet             | 1        | 3.7%    |
| Multimedia controller    | 1        | 3.7%    |
| Dvb card                 | 1        | 3.7%    |

