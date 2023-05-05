Debian - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for Debian.

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

Total: 5108

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 2B38                        | [bf99202e8b](https://linux-hardware.org/?probe=bf99202e8b) | May 01, 2023 |
| Dell          | 0NC2VH A01                  | [7fb1708706](https://linux-hardware.org/?probe=7fb1708706) | May 01, 2023 |
| HP            | 2B38                        | [6942eb2544](https://linux-hardware.org/?probe=6942eb2544) | May 01, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [d85b7a2592](https://linux-hardware.org/?probe=d85b7a2592) | Apr 30, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [ccb46c2a2b](https://linux-hardware.org/?probe=ccb46c2a2b) | Apr 30, 2023 |
| Hardkernel    | ODROID-H3                   | [139d61e128](https://linux-hardware.org/?probe=139d61e128) | Apr 29, 2023 |
| HP            | 3397                        | [8b84766d3d](https://linux-hardware.org/?probe=8b84766d3d) | Apr 29, 2023 |
| Medion        | MS-7708                     | [af2020cd9c](https://linux-hardware.org/?probe=af2020cd9c) | Apr 28, 2023 |
| Medion        | MS-7708                     | [424c4ca2db](https://linux-hardware.org/?probe=424c4ca2db) | Apr 28, 2023 |
| Intel         | H61 V124                    | [1fa0b34b3c](https://linux-hardware.org/?probe=1fa0b34b3c) | Apr 28, 2023 |
| Unknown       | iKoolCore R1 iKoolCore R... | [429d6f994a](https://linux-hardware.org/?probe=429d6f994a) | Apr 28, 2023 |
| ASUSTek       | B150-PRO D3                 | [35fa6f9a33](https://linux-hardware.org/?probe=35fa6f9a33) | Apr 28, 2023 |
| ASRock        | X470 Master SLI             | [cded55a936](https://linux-hardware.org/?probe=cded55a936) | Apr 28, 2023 |
| BESSTAR Te... | HM80                        | [476c573547](https://linux-hardware.org/?probe=476c573547) | Apr 28, 2023 |
| Unknown       | Unknown                     | [5f5809c40f](https://linux-hardware.org/?probe=5f5809c40f) | Apr 27, 2023 |
| Shenzhen M... | F6BFC                       | [e2f7b853b1](https://linux-hardware.org/?probe=e2f7b853b1) | Apr 27, 2023 |
| Unknown       | Unknown                     | [e9f8ff6596](https://linux-hardware.org/?probe=e9f8ff6596) | Apr 27, 2023 |
| ASUSTek       | Z97M-PLUS/BR                | [3255acf414](https://linux-hardware.org/?probe=3255acf414) | Apr 27, 2023 |
| ASRock        | A320M-HDV R3.0              | [d395c6168d](https://linux-hardware.org/?probe=d395c6168d) | Apr 27, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [2dcf65cf8e](https://linux-hardware.org/?probe=2dcf65cf8e) | Apr 26, 2023 |
| MSI           | MS-B0A21                    | [646d14f7b0](https://linux-hardware.org/?probe=646d14f7b0) | Apr 26, 2023 |
| HP            | 8309                        | [cde28bd710](https://linux-hardware.org/?probe=cde28bd710) | Apr 26, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | [a343d9158a](https://linux-hardware.org/?probe=a343d9158a) | Apr 26, 2023 |
| HP            | 1632                        | [ace6df6aee](https://linux-hardware.org/?probe=ace6df6aee) | Apr 25, 2023 |
| ASUSTek       | Z170-A                      | [fa21ed6900](https://linux-hardware.org/?probe=fa21ed6900) | Apr 25, 2023 |
| Dell          | 0KYJ8C A00                  | [1e8226d149](https://linux-hardware.org/?probe=1e8226d149) | Apr 25, 2023 |
| ASRock        | 960GC-GS FX                 | [1cd850e8af](https://linux-hardware.org/?probe=1cd850e8af) | Apr 25, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [c5f2fa1c5a](https://linux-hardware.org/?probe=c5f2fa1c5a) | Apr 25, 2023 |
| ASUSTek       | PRIME Z590-P                | [5d03070db6](https://linux-hardware.org/?probe=5d03070db6) | Apr 24, 2023 |
| Dell          | 08HPGT A02                  | [04f68362d5](https://linux-hardware.org/?probe=04f68362d5) | Apr 24, 2023 |
| Dell          | 08HPGT A02                  | [d352ecf4ed](https://linux-hardware.org/?probe=d352ecf4ed) | Apr 24, 2023 |
| HP            | 8056                        | [a7686ee1af](https://linux-hardware.org/?probe=a7686ee1af) | Apr 24, 2023 |
| AZW           | MINI S                      | [d71153ae6e](https://linux-hardware.org/?probe=d71153ae6e) | Apr 24, 2023 |
| Intel         | SE7320EP2 D11950-402        | [ad1a126878](https://linux-hardware.org/?probe=ad1a126878) | Apr 24, 2023 |
| MSI           | Z87-G43                     | [4d908cb615](https://linux-hardware.org/?probe=4d908cb615) | Apr 24, 2023 |
| Dell          | 0N0992 A01                  | [a8e8000610](https://linux-hardware.org/?probe=a8e8000610) | Apr 24, 2023 |
| Biostar       | B350ET2                     | [47289e48eb](https://linux-hardware.org/?probe=47289e48eb) | Apr 23, 2023 |
| ASRock        | B560 Pro4                   | [3a9f7b19fa](https://linux-hardware.org/?probe=3a9f7b19fa) | Apr 23, 2023 |
| MSI           | Z390-A PRO                  | [74cf7ef6e5](https://linux-hardware.org/?probe=74cf7ef6e5) | Apr 23, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [78c1951456](https://linux-hardware.org/?probe=78c1951456) | Apr 23, 2023 |
| ASRock        | B560 Pro4                   | [965aa93228](https://linux-hardware.org/?probe=965aa93228) | Apr 23, 2023 |
| Unknown       | Unknown                     | [0605faa66d](https://linux-hardware.org/?probe=0605faa66d) | Apr 23, 2023 |
| AZW           | U59                         | [8921a6910d](https://linux-hardware.org/?probe=8921a6910d) | Apr 23, 2023 |
| Shuttle       | DS20U                       | [2e8e79b5ff](https://linux-hardware.org/?probe=2e8e79b5ff) | Apr 23, 2023 |
| HP            | 845A                        | [41a0cad635](https://linux-hardware.org/?probe=41a0cad635) | Apr 23, 2023 |
| Gigabyte      | B550 VISION D-P             | [ccb49b32a0](https://linux-hardware.org/?probe=ccb49b32a0) | Apr 23, 2023 |
| Gigabyte      | B550 VISION D-P             | [2651f47f8c](https://linux-hardware.org/?probe=2651f47f8c) | Apr 23, 2023 |
| MSI           | X370 GAMING PLUS            | [5d61deb4d4](https://linux-hardware.org/?probe=5d61deb4d4) | Apr 23, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [9c3e15de68](https://linux-hardware.org/?probe=9c3e15de68) | Apr 22, 2023 |
| ASUSTek       | P5N-D                       | [c1af2b9a2c](https://linux-hardware.org/?probe=c1af2b9a2c) | Apr 22, 2023 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | [03a331aa44](https://linux-hardware.org/?probe=03a331aa44) | Apr 22, 2023 |
| ASUSTek       | PRIME B650M-A AX            | [0a90dc180c](https://linux-hardware.org/?probe=0a90dc180c) | Apr 22, 2023 |
| MW            | GMLK-2_5G4L                 | [b5ffb4ee22](https://linux-hardware.org/?probe=b5ffb4ee22) | Apr 22, 2023 |
| Gigabyte      | B550M DS3H                  | [e98b4fdd23](https://linux-hardware.org/?probe=e98b4fdd23) | Apr 21, 2023 |
| ASUSTek       | B85M-G                      | [4392c46287](https://linux-hardware.org/?probe=4392c46287) | Apr 20, 2023 |
| Gigabyte      | Z77-DS3H                    | [cde1ecf1c6](https://linux-hardware.org/?probe=cde1ecf1c6) | Apr 20, 2023 |
| Shuttle       | FS81                        | [051b7f4753](https://linux-hardware.org/?probe=051b7f4753) | Apr 20, 2023 |
| HP            | ProLiant ML150 G6           | [76dc3db16a](https://linux-hardware.org/?probe=76dc3db16a) | Apr 20, 2023 |
| ASRock        | B550 Pro4                   | [2d4578e52a](https://linux-hardware.org/?probe=2d4578e52a) | Apr 20, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [4abfcb4ab3](https://linux-hardware.org/?probe=4abfcb4ab3) | Apr 19, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [e93357961f](https://linux-hardware.org/?probe=e93357961f) | Apr 19, 2023 |
| MSI           | MPG Z590 GAMING EDGE WIF... | [97860c01ca](https://linux-hardware.org/?probe=97860c01ca) | Apr 19, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | [e1da556a0b](https://linux-hardware.org/?probe=e1da556a0b) | Apr 19, 2023 |
| ASRock        | J3455-ITX                   | [895abaa15e](https://linux-hardware.org/?probe=895abaa15e) | Apr 19, 2023 |
| ASRock        | J3455-ITX                   | [f70d811bbd](https://linux-hardware.org/?probe=f70d811bbd) | Apr 19, 2023 |
| MSI           | H110M PRO-VD                | [d04a1b7f36](https://linux-hardware.org/?probe=d04a1b7f36) | Apr 19, 2023 |
| ASUSTek       | P8B75-V                     | [8957c4fdd0](https://linux-hardware.org/?probe=8957c4fdd0) | Apr 19, 2023 |
| ASUSTek       | PRIME A320M-K               | [fd82dc08dc](https://linux-hardware.org/?probe=fd82dc08dc) | Apr 18, 2023 |
| MSI           | MAG Z390M MORTAR            | [121237b9c1](https://linux-hardware.org/?probe=121237b9c1) | Apr 17, 2023 |
| MSI           | MPG B650I EDGE WIFI         | [11f85df48e](https://linux-hardware.org/?probe=11f85df48e) | Apr 17, 2023 |
| ASRock        | H310M-STX                   | [438e774de5](https://linux-hardware.org/?probe=438e774de5) | Apr 17, 2023 |
| HP            | 0AECh D                     | [f6c67d337e](https://linux-hardware.org/?probe=f6c67d337e) | Apr 17, 2023 |
| ASUSTek       | K30BF_M32BF                 | [6ea01fad49](https://linux-hardware.org/?probe=6ea01fad49) | Apr 17, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [7f5feb82ab](https://linux-hardware.org/?probe=7f5feb82ab) | Apr 17, 2023 |
| Gigabyte      | Z690 AORUS ULTRA            | [a4bb147f89](https://linux-hardware.org/?probe=a4bb147f89) | Apr 17, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [c4d3eabb55](https://linux-hardware.org/?probe=c4d3eabb55) | Apr 17, 2023 |
| ASUSTek       | P8H77-M                     | [6364dbb93a](https://linux-hardware.org/?probe=6364dbb93a) | Apr 16, 2023 |
| Dell          | 0HHV7N A00                  | [4443ff9154](https://linux-hardware.org/?probe=4443ff9154) | Apr 16, 2023 |
| HP            | 18E7                        | [6c2c248eec](https://linux-hardware.org/?probe=6c2c248eec) | Apr 16, 2023 |
| ASUSTek       | PRIME X570-P                | [1f02ee3393](https://linux-hardware.org/?probe=1f02ee3393) | Apr 16, 2023 |
| Biostar       | A10N-8800E                  | [31557d5e8c](https://linux-hardware.org/?probe=31557d5e8c) | Apr 15, 2023 |
| ASUSTek       | Z87-A                       | [3e96076874](https://linux-hardware.org/?probe=3e96076874) | Apr 15, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [7d9278e08a](https://linux-hardware.org/?probe=7d9278e08a) | Apr 15, 2023 |
| ASRock        | H61M-DGS                    | [e0b2a066ee](https://linux-hardware.org/?probe=e0b2a066ee) | Apr 15, 2023 |
| Acer          | WG43M                       | [a3a49836f9](https://linux-hardware.org/?probe=a3a49836f9) | Apr 15, 2023 |
| Medion        | TJ4125                      | [887d24e023](https://linux-hardware.org/?probe=887d24e023) | Apr 14, 2023 |
| Intel         | Alder Lake-H PCH E1.0G      | [0ec41c7bd8](https://linux-hardware.org/?probe=0ec41c7bd8) | Apr 14, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d7768947bc](https://linux-hardware.org/?probe=d7768947bc) | Apr 14, 2023 |
| ASUSTek       | P11C-X Series               | [2ab6f2745c](https://linux-hardware.org/?probe=2ab6f2745c) | Apr 14, 2023 |
| ASUSTek       | P11C-X Series               | [55f8d9f172](https://linux-hardware.org/?probe=55f8d9f172) | Apr 14, 2023 |
| Unknown       | Unknown                     | [6925c48705](https://linux-hardware.org/?probe=6925c48705) | Apr 14, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [f4cbe67033](https://linux-hardware.org/?probe=f4cbe67033) | Apr 14, 2023 |
| ASRock        | H81M-VG4 R2.0               | [cc951809ed](https://linux-hardware.org/?probe=cc951809ed) | Apr 14, 2023 |
| Lenovo        | ThinkStation D30 42234T7    | [7730eb04fa](https://linux-hardware.org/?probe=7730eb04fa) | Apr 14, 2023 |
| Gigabyte      | B75M-D3H                    | [6106a2c31f](https://linux-hardware.org/?probe=6106a2c31f) | Apr 13, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [70e0ac9475](https://linux-hardware.org/?probe=70e0ac9475) | Apr 13, 2023 |
| Fujitsu       | D3403-A1 S26361-D3403-A1    | [5be961705c](https://linux-hardware.org/?probe=5be961705c) | Apr 13, 2023 |
| IceWhale T... | ZimaBoard 216 ZMB           | [33a7fad816](https://linux-hardware.org/?probe=33a7fad816) | Apr 13, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [721a60ff30](https://linux-hardware.org/?probe=721a60ff30) | Apr 13, 2023 |
| Intel         | Alder Lake-H PCH E1.0G      | [9cf22928fb](https://linux-hardware.org/?probe=9cf22928fb) | Apr 13, 2023 |
| ASRock        | H410M-HVS R2.0              | [7f388965d7](https://linux-hardware.org/?probe=7f388965d7) | Apr 13, 2023 |
| HP            | 21EF                        | [d2b3751fd1](https://linux-hardware.org/?probe=d2b3751fd1) | Apr 13, 2023 |
| Unknown       | Unknown                     | [158dacc1ce](https://linux-hardware.org/?probe=158dacc1ce) | Apr 13, 2023 |
| Unknown       | Unknown                     | [52aeca6f98](https://linux-hardware.org/?probe=52aeca6f98) | Apr 13, 2023 |
| Dell          | 0XD433 A00                  | [e0a30bf441](https://linux-hardware.org/?probe=e0a30bf441) | Apr 12, 2023 |
| Dell          | 03V7GF A01                  | [c309233437](https://linux-hardware.org/?probe=c309233437) | Apr 12, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [108725a205](https://linux-hardware.org/?probe=108725a205) | Apr 12, 2023 |
| Dell          | 03V7GF A02                  | [cb72d83566](https://linux-hardware.org/?probe=cb72d83566) | Apr 12, 2023 |
| MSI           | Z370 PC PRO                 | [fb3078d5c3](https://linux-hardware.org/?probe=fb3078d5c3) | Apr 12, 2023 |
| Intel         | H61 V124                    | [28b73b97b3](https://linux-hardware.org/?probe=28b73b97b3) | Apr 12, 2023 |
| Dell          | 01XK1W A00                  | [4eb8c9f372](https://linux-hardware.org/?probe=4eb8c9f372) | Apr 12, 2023 |
| MSI           | MS-7060                     | [d78aaad9ec](https://linux-hardware.org/?probe=d78aaad9ec) | Apr 12, 2023 |
| HP            | 1589                        | [c04488f359](https://linux-hardware.org/?probe=c04488f359) | Apr 11, 2023 |
| Gigabyte      | H61M-DS2                    | [e0b6eda111](https://linux-hardware.org/?probe=e0b6eda111) | Apr 11, 2023 |
| Lenovo        | 32E6 NOK                    | [c1d51dba1d](https://linux-hardware.org/?probe=c1d51dba1d) | Apr 11, 2023 |
| ASUSTek       | PRIME Z590-P                | [e4299a2ce6](https://linux-hardware.org/?probe=e4299a2ce6) | Apr 11, 2023 |
| ASUSTek       | P7H55                       | [8ee190d352](https://linux-hardware.org/?probe=8ee190d352) | Apr 11, 2023 |
| HP            | 1589                        | [e52c705c13](https://linux-hardware.org/?probe=e52c705c13) | Apr 11, 2023 |
| ASUSTek       | PRIME Z370-A                | [64759fca72](https://linux-hardware.org/?probe=64759fca72) | Apr 10, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [5b0601fc42](https://linux-hardware.org/?probe=5b0601fc42) | Apr 09, 2023 |
| Medion        | TJ4125                      | [5c5f39a8fd](https://linux-hardware.org/?probe=5c5f39a8fd) | Apr 09, 2023 |
| Techvision    | TVI7309X B0                 | [d24ce5fa44](https://linux-hardware.org/?probe=d24ce5fa44) | Apr 09, 2023 |
| HP            | 2B29                        | [b909d3c46d](https://linux-hardware.org/?probe=b909d3c46d) | Apr 09, 2023 |
| HP            | 2B29                        | [1fd9cd3d7c](https://linux-hardware.org/?probe=1fd9cd3d7c) | Apr 09, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [3b665833d1](https://linux-hardware.org/?probe=3b665833d1) | Apr 09, 2023 |
| HP            | 83E9                        | [4e62f72ee2](https://linux-hardware.org/?probe=4e62f72ee2) | Apr 08, 2023 |
| HP            | 83E9                        | [36fdd064cc](https://linux-hardware.org/?probe=36fdd064cc) | Apr 08, 2023 |
| AMI           | Intel                       | [48c620d141](https://linux-hardware.org/?probe=48c620d141) | Apr 08, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [36c87da9d9](https://linux-hardware.org/?probe=36c87da9d9) | Apr 07, 2023 |
| Inventec      | D CLASS A02                 | [3d53baddbf](https://linux-hardware.org/?probe=3d53baddbf) | Apr 07, 2023 |
| Inventec      | VXC Class A02               | [3ff1b18b81](https://linux-hardware.org/?probe=3ff1b18b81) | Apr 07, 2023 |
| ASUSTek       | P7H55                       | [89966b216e](https://linux-hardware.org/?probe=89966b216e) | Apr 07, 2023 |
| Dell          | 01XK1W A00                  | [023a578b76](https://linux-hardware.org/?probe=023a578b76) | Apr 07, 2023 |
| QTQD          | Unknown                     | [5cb163c75a](https://linux-hardware.org/?probe=5cb163c75a) | Apr 06, 2023 |
| MSI           | MS-7253                     | [1b9074e1ac](https://linux-hardware.org/?probe=1b9074e1ac) | Apr 06, 2023 |
| Foxconn       | 2A8C                        | [f202bac0de](https://linux-hardware.org/?probe=f202bac0de) | Apr 06, 2023 |
| MSI           | Z68A-GD65                   | [a8939164e7](https://linux-hardware.org/?probe=a8939164e7) | Apr 06, 2023 |
| Huanan        | X99-F8D PLUS V1.1           | [6d7db3d917](https://linux-hardware.org/?probe=6d7db3d917) | Apr 06, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [ca1cdc7f46](https://linux-hardware.org/?probe=ca1cdc7f46) | Apr 06, 2023 |
| MSI           | MS-B1831                    | [9ea2ec4f47](https://linux-hardware.org/?probe=9ea2ec4f47) | Apr 06, 2023 |
| Gigabyte      | F2A88XN-WIFI                | [ea7a921618](https://linux-hardware.org/?probe=ea7a921618) | Apr 06, 2023 |
| Gigabyte      | F2A88XN-WIFI                | [125f93468e](https://linux-hardware.org/?probe=125f93468e) | Apr 06, 2023 |
| Gigabyte      | B550 UD AC                  | [a639dfd228](https://linux-hardware.org/?probe=a639dfd228) | Apr 06, 2023 |
| HP            | 895C                        | [27de3e2244](https://linux-hardware.org/?probe=27de3e2244) | Apr 06, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | [55ea8a957b](https://linux-hardware.org/?probe=55ea8a957b) | Apr 06, 2023 |
| Huanan        | X99-F8D PLUS V1.1           | [9c6a3de994](https://linux-hardware.org/?probe=9c6a3de994) | Apr 05, 2023 |
| HP            | 895C                        | [3c87e6de19](https://linux-hardware.org/?probe=3c87e6de19) | Apr 05, 2023 |
| ASUSTek       | PRIME A320M-K               | [6dbb59e2fc](https://linux-hardware.org/?probe=6dbb59e2fc) | Apr 05, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [eadee78860](https://linux-hardware.org/?probe=eadee78860) | Apr 05, 2023 |
| ASUSTek       | VM42                        | [84f848ea21](https://linux-hardware.org/?probe=84f848ea21) | Apr 05, 2023 |
| ASUSTek       | Z170-K                      | [d9ab0a1946](https://linux-hardware.org/?probe=d9ab0a1946) | Apr 05, 2023 |
| ASUSTek       | PRIME B250M-PLUS            | [6f4013d94e](https://linux-hardware.org/?probe=6f4013d94e) | Apr 05, 2023 |
| Gigabyte      | Z97X-UD3H-BK-CF             | [2783ec6da9](https://linux-hardware.org/?probe=2783ec6da9) | Apr 05, 2023 |
| Shenzhen M... | F7BFD                       | [7f6103b394](https://linux-hardware.org/?probe=7f6103b394) | Apr 05, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [5f9965b18e](https://linux-hardware.org/?probe=5f9965b18e) | Apr 05, 2023 |
| Shenzhen M... | F7BFD                       | [ac039ed7e6](https://linux-hardware.org/?probe=ac039ed7e6) | Apr 05, 2023 |
| HP            | 1790                        | [55e3d423e0](https://linux-hardware.org/?probe=55e3d423e0) | Apr 05, 2023 |
| Inventec      | D CLASS A02                 | [58cf8c28ff](https://linux-hardware.org/?probe=58cf8c28ff) | Apr 05, 2023 |
| Inventec      | D CLASS A02                 | [7f904181ea](https://linux-hardware.org/?probe=7f904181ea) | Apr 04, 2023 |
| Gigabyte      | Z68A-D3-B3                  | [6fb463806f](https://linux-hardware.org/?probe=6fb463806f) | Apr 04, 2023 |
| ASUSTek       | PRIME B250M-PLUS            | [0401a50bac](https://linux-hardware.org/?probe=0401a50bac) | Apr 04, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | [b5106f816a](https://linux-hardware.org/?probe=b5106f816a) | Apr 04, 2023 |
| Gigabyte      | H61M-DS2                    | [5a83d4ef1e](https://linux-hardware.org/?probe=5a83d4ef1e) | Apr 04, 2023 |
| Acer          | WG43M                       | [10bf0c0d1a](https://linux-hardware.org/?probe=10bf0c0d1a) | Apr 04, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [739f49ff7e](https://linux-hardware.org/?probe=739f49ff7e) | Apr 04, 2023 |
| MSI           | MAG B460 TORPEDO            | [62a628da55](https://linux-hardware.org/?probe=62a628da55) | Apr 04, 2023 |
| Unknown       | Q-790                       | [5f41d7d182](https://linux-hardware.org/?probe=5f41d7d182) | Apr 04, 2023 |
| ASUSTek       | P8Z77-M                     | [ec9901fcd5](https://linux-hardware.org/?probe=ec9901fcd5) | Apr 04, 2023 |
| Pegatron      | Benicia                     | [96ba9b6040](https://linux-hardware.org/?probe=96ba9b6040) | Apr 04, 2023 |
| Techvision    | TVI7309X B0                 | [dbbe4bbbc5](https://linux-hardware.org/?probe=dbbe4bbbc5) | Apr 03, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [849adee9bf](https://linux-hardware.org/?probe=849adee9bf) | Apr 03, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [6b554016fe](https://linux-hardware.org/?probe=6b554016fe) | Apr 03, 2023 |
| Fujitsu       | D3403-A1 S26361-D3403-A1    | [aaa2e273c1](https://linux-hardware.org/?probe=aaa2e273c1) | Apr 03, 2023 |
| Dell          | 07N90W A02                  | [fd992821e0](https://linux-hardware.org/?probe=fd992821e0) | Apr 03, 2023 |
| Unknown       | Unknown                     | [cdd67e12ca](https://linux-hardware.org/?probe=cdd67e12ca) | Apr 03, 2023 |
| ASUSTek       | PRIME B450M-A               | [1b35a0e9f7](https://linux-hardware.org/?probe=1b35a0e9f7) | Apr 03, 2023 |
| Unknown       | Unknown                     | [cbcfbb8783](https://linux-hardware.org/?probe=cbcfbb8783) | Apr 03, 2023 |
| BESSTAR Te... | HM90                        | [722013016f](https://linux-hardware.org/?probe=722013016f) | Apr 03, 2023 |
| Shuttle       | FH370                       | [29b2ad6149](https://linux-hardware.org/?probe=29b2ad6149) | Apr 03, 2023 |
| ASUSTek       | PRIME B450M-A               | [734efd13d3](https://linux-hardware.org/?probe=734efd13d3) | Apr 03, 2023 |
| ASRock        | X470 Gaming-ITX/ac          | [48f07855d1](https://linux-hardware.org/?probe=48f07855d1) | Apr 02, 2023 |
| ASUSTek       | ROG Rampage VI EXTREME      | [03fe72ba57](https://linux-hardware.org/?probe=03fe72ba57) | Apr 02, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [6844d471e4](https://linux-hardware.org/?probe=6844d471e4) | Apr 02, 2023 |
| Unknown       | Unknown                     | [077bed9951](https://linux-hardware.org/?probe=077bed9951) | Apr 02, 2023 |
| Google        | Panther                     | [73f3ed3c65](https://linux-hardware.org/?probe=73f3ed3c65) | Apr 02, 2023 |
| MSI           | MS-7318                     | [3d02816b24](https://linux-hardware.org/?probe=3d02816b24) | Apr 01, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [2a597d7a33](https://linux-hardware.org/?probe=2a597d7a33) | Apr 01, 2023 |
| Dell          | 040DDP A00                  | [0771f1547e](https://linux-hardware.org/?probe=0771f1547e) | Apr 01, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [32c0716bfa](https://linux-hardware.org/?probe=32c0716bfa) | Apr 01, 2023 |
| Medion        | TJ4125                      | [2627cc2d42](https://linux-hardware.org/?probe=2627cc2d42) | Apr 01, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [6fd833b58c](https://linux-hardware.org/?probe=6fd833b58c) | Apr 01, 2023 |
| Gigabyte      | A320M-H-CF                  | [a5c21e7892](https://linux-hardware.org/?probe=a5c21e7892) | Apr 01, 2023 |
| Gigabyte      | A320M-H-CF                  | [4b873550ab](https://linux-hardware.org/?probe=4b873550ab) | Apr 01, 2023 |
| ASUSTek       | TS10                        | [054de4f36a](https://linux-hardware.org/?probe=054de4f36a) | Mar 31, 2023 |
| Gigabyte      | H61M-DS2                    | [35e4f876ca](https://linux-hardware.org/?probe=35e4f876ca) | Mar 31, 2023 |
| Gigabyte      | H61M-DS2                    | [fca09d31a2](https://linux-hardware.org/?probe=fca09d31a2) | Mar 31, 2023 |
| Lenovo        | ThinkStation D30 42234T7    | [47f6f4653b](https://linux-hardware.org/?probe=47f6f4653b) | Mar 31, 2023 |
| ASRock        | B760M Pro RS/D4             | [6a63402e9c](https://linux-hardware.org/?probe=6a63402e9c) | Mar 31, 2023 |
| ASUSTek       | P8H67-M                     | [3806b33cae](https://linux-hardware.org/?probe=3806b33cae) | Mar 31, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [624d23335b](https://linux-hardware.org/?probe=624d23335b) | Mar 31, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [d6b6c88578](https://linux-hardware.org/?probe=d6b6c88578) | Mar 31, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [704145641e](https://linux-hardware.org/?probe=704145641e) | Mar 31, 2023 |
| Fujitsu       | D3417-B2 S26361-D3417-B2    | [56c886069b](https://linux-hardware.org/?probe=56c886069b) | Mar 31, 2023 |
| Unknown       | iKoolCore R1 iKoolCore R... | [050875ba5f](https://linux-hardware.org/?probe=050875ba5f) | Mar 30, 2023 |
| AZW           | U59                         | [c87edfe3b6](https://linux-hardware.org/?probe=c87edfe3b6) | Mar 30, 2023 |
| ASUSTek       | ROG STRIX TRX40-E GAMING    | [fbcdd4ed13](https://linux-hardware.org/?probe=fbcdd4ed13) | Mar 30, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [de5bf4239c](https://linux-hardware.org/?probe=de5bf4239c) | Mar 30, 2023 |
| ASUSTek       | P5G41T-M LX2/GB             | [f310910b0e](https://linux-hardware.org/?probe=f310910b0e) | Mar 30, 2023 |
| ASRock        | X670E PG Lightning          | [6078dd3087](https://linux-hardware.org/?probe=6078dd3087) | Mar 30, 2023 |
| Gigabyte      | H61M-S1                     | [76e79f5f19](https://linux-hardware.org/?probe=76e79f5f19) | Mar 30, 2023 |
| Gigabyte      | H61M-S1                     | [78d1316a55](https://linux-hardware.org/?probe=78d1316a55) | Mar 30, 2023 |
| Fujitsu Si... | D2764-A1 S26361-D2764-A1    | [08af010307](https://linux-hardware.org/?probe=08af010307) | Mar 30, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [244ffc8736](https://linux-hardware.org/?probe=244ffc8736) | Mar 30, 2023 |
| ASUSTek       | F2A85-M                     | [4d6ae3ef0f](https://linux-hardware.org/?probe=4d6ae3ef0f) | Mar 30, 2023 |
| HP            | 213D A01                    | [d5fb38a71b](https://linux-hardware.org/?probe=d5fb38a71b) | Mar 30, 2023 |
| HP            | 213D A01                    | [79d8e1b64f](https://linux-hardware.org/?probe=79d8e1b64f) | Mar 30, 2023 |
| HP            | 3048h                       | [1a4d86fca8](https://linux-hardware.org/?probe=1a4d86fca8) | Mar 30, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [82118905ba](https://linux-hardware.org/?probe=82118905ba) | Mar 30, 2023 |
| ASUSTek       | TUF Z270 MARK 2             | [4976f6b6b2](https://linux-hardware.org/?probe=4976f6b6b2) | Mar 30, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [6cc34607d1](https://linux-hardware.org/?probe=6cc34607d1) | Mar 30, 2023 |
| MSI           | B450 TOMAHAWK               | [9251f2d561](https://linux-hardware.org/?probe=9251f2d561) | Mar 30, 2023 |
| MSI           | B450 TOMAHAWK               | [2d28ba397e](https://linux-hardware.org/?probe=2d28ba397e) | Mar 29, 2023 |
| Fujitsu       | D3401-A1 S26361-D3401-A1    | [e772d0e916](https://linux-hardware.org/?probe=e772d0e916) | Mar 29, 2023 |
| AZW           | U59                         | [3776cd7fb3](https://linux-hardware.org/?probe=3776cd7fb3) | Mar 29, 2023 |
| AZW           | U59                         | [f7958b8f39](https://linux-hardware.org/?probe=f7958b8f39) | Mar 29, 2023 |
| Medion        | TJ4125                      | [e03693b0f0](https://linux-hardware.org/?probe=e03693b0f0) | Mar 29, 2023 |
| ASRockRack    | X470D4U2-2T                 | [38e3ecfb84](https://linux-hardware.org/?probe=38e3ecfb84) | Mar 29, 2023 |
| Intel         | 945GCT-M                    | [d7e65e945e](https://linux-hardware.org/?probe=d7e65e945e) | Mar 29, 2023 |
| HP            | 1495                        | [75702f8b1d](https://linux-hardware.org/?probe=75702f8b1d) | Mar 29, 2023 |
| HP            | 1495                        | [c342260a77](https://linux-hardware.org/?probe=c342260a77) | Mar 29, 2023 |
| ECS           | G31T-M                      | [d6149cbd0d](https://linux-hardware.org/?probe=d6149cbd0d) | Mar 29, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [dadeec8815](https://linux-hardware.org/?probe=dadeec8815) | Mar 29, 2023 |
| Dell          | 01XK1W A00                  | [bf9252a1ac](https://linux-hardware.org/?probe=bf9252a1ac) | Mar 29, 2023 |
| HP            | 89B4 A                      | [cb8136a176](https://linux-hardware.org/?probe=cb8136a176) | Mar 28, 2023 |
| ASUSTek       | PRIME B450M-A II            | [4fe0ddab4b](https://linux-hardware.org/?probe=4fe0ddab4b) | Mar 28, 2023 |
| Pegatron      | Maureen                     | [0fdcf4a5bc](https://linux-hardware.org/?probe=0fdcf4a5bc) | Mar 28, 2023 |
| Unknown       | FT2000plus Generic Borad... | [43ec5396f3](https://linux-hardware.org/?probe=43ec5396f3) | Mar 28, 2023 |
| Unknown       | FT2000plus Generic Borad... | [c305aa7562](https://linux-hardware.org/?probe=c305aa7562) | Mar 28, 2023 |
| Unknown       | Unknown                     | [8f1561c37b](https://linux-hardware.org/?probe=8f1561c37b) | Mar 28, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [5969fea8f0](https://linux-hardware.org/?probe=5969fea8f0) | Mar 28, 2023 |
| MSI           | MAG B660M MORTAR WIFI DD... | [11cb22743c](https://linux-hardware.org/?probe=11cb22743c) | Mar 27, 2023 |
| Gigabyte      | H97M-HD3                    | [1b531d5ada](https://linux-hardware.org/?probe=1b531d5ada) | Mar 27, 2023 |
| ASRock        | 770 Extreme3                | [9cd5d1485c](https://linux-hardware.org/?probe=9cd5d1485c) | Mar 27, 2023 |
| HP            | 18E6                        | [a406dc2463](https://linux-hardware.org/?probe=a406dc2463) | Mar 27, 2023 |
| Medion        | TJ4125                      | [571b476915](https://linux-hardware.org/?probe=571b476915) | Mar 27, 2023 |
| ASRock        | FM2A88X+ Killer             | [6180e562dd](https://linux-hardware.org/?probe=6180e562dd) | Mar 27, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [ebed945eae](https://linux-hardware.org/?probe=ebed945eae) | Mar 27, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [fd16b858df](https://linux-hardware.org/?probe=fd16b858df) | Mar 27, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [33608bbcda](https://linux-hardware.org/?probe=33608bbcda) | Mar 27, 2023 |
| HP            | 895D                        | [1cba23395d](https://linux-hardware.org/?probe=1cba23395d) | Mar 27, 2023 |
| Lenovo        | ThinkStation D30 42234T7    | [cfb8c9d396](https://linux-hardware.org/?probe=cfb8c9d396) | Mar 27, 2023 |
| ASRockRack    | D1541D4U-2T8R               | [012c10ae8c](https://linux-hardware.org/?probe=012c10ae8c) | Mar 27, 2023 |
| ASUSTek       | P8Z77-V LE                  | [b6a0d45508](https://linux-hardware.org/?probe=b6a0d45508) | Mar 26, 2023 |
| Gigabyte      | B550 AORUS MASTER           | [a4f4013e4e](https://linux-hardware.org/?probe=a4f4013e4e) | Mar 26, 2023 |
| Gigabyte      | B550 AORUS MASTER           | [af88fa64c6](https://linux-hardware.org/?probe=af88fa64c6) | Mar 26, 2023 |
| Dell          | 0HY9JP A00                  | [d1c982b241](https://linux-hardware.org/?probe=d1c982b241) | Mar 26, 2023 |
| HP            | 83E2                        | [00f64e69cd](https://linux-hardware.org/?probe=00f64e69cd) | Mar 26, 2023 |
| Medion        | TJ4125                      | [74b96baec4](https://linux-hardware.org/?probe=74b96baec4) | Mar 25, 2023 |
| HP            | 1497                        | [fb8706575a](https://linux-hardware.org/?probe=fb8706575a) | Mar 25, 2023 |
| MSI           | B450M PRO-VDH MAX           | [76338f95ea](https://linux-hardware.org/?probe=76338f95ea) | Mar 25, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [6e459078e7](https://linux-hardware.org/?probe=6e459078e7) | Mar 25, 2023 |
| HP            | 83E2                        | [cd40c6aa18](https://linux-hardware.org/?probe=cd40c6aa18) | Mar 25, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [b9d321c70e](https://linux-hardware.org/?probe=b9d321c70e) | Mar 25, 2023 |
| ASUSTek       | PRIME X470-PRO              | [a05e768cca](https://linux-hardware.org/?probe=a05e768cca) | Mar 25, 2023 |
| Dell          | 0PU052                      | [ccea2ad8e8](https://linux-hardware.org/?probe=ccea2ad8e8) | Mar 25, 2023 |
| Gigabyte      | Z690 AORUS PRO              | [9b8ddda3c3](https://linux-hardware.org/?probe=9b8ddda3c3) | Mar 24, 2023 |
| Gigabyte      | H61M-DS2                    | [cea1787057](https://linux-hardware.org/?probe=cea1787057) | Mar 24, 2023 |
| Gigabyte      | B550 AORUS MASTER           | [1f7c1bfa41](https://linux-hardware.org/?probe=1f7c1bfa41) | Mar 24, 2023 |
| AZW           | U59                         | [b4058b773d](https://linux-hardware.org/?probe=b4058b773d) | Mar 24, 2023 |
| Iskratel, ... | IN6011AX                    | [037350830e](https://linux-hardware.org/?probe=037350830e) | Mar 23, 2023 |
| ASUSTek       | PRIME Z690-P                | [6b3cdb2b1a](https://linux-hardware.org/?probe=6b3cdb2b1a) | Mar 23, 2023 |
| ASRockRack    | E3C242D4U2-2T               | [05eb6d08bd](https://linux-hardware.org/?probe=05eb6d08bd) | Mar 23, 2023 |
| ECS           | G31T-M9                     | [e314bf5403](https://linux-hardware.org/?probe=e314bf5403) | Mar 23, 2023 |
| Dell          | 0J3C2F A02                  | [cb6e3973c8](https://linux-hardware.org/?probe=cb6e3973c8) | Mar 23, 2023 |
| HP            | 0A68h                       | [527cad6ad0](https://linux-hardware.org/?probe=527cad6ad0) | Mar 23, 2023 |
| Gigabyte      | H97M-HD3                    | [ab4dce8483](https://linux-hardware.org/?probe=ab4dce8483) | Mar 22, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [e2fe65e540](https://linux-hardware.org/?probe=e2fe65e540) | Mar 22, 2023 |
| Dell          | 0HHV7N A00                  | [7b10e71784](https://linux-hardware.org/?probe=7b10e71784) | Mar 22, 2023 |
| HP            | 3048h                       | [5163f9de22](https://linux-hardware.org/?probe=5163f9de22) | Mar 22, 2023 |
| Techvision    | TVI7309X B0                 | [468588ab96](https://linux-hardware.org/?probe=468588ab96) | Mar 21, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [57a69bcf57](https://linux-hardware.org/?probe=57a69bcf57) | Mar 21, 2023 |
| Gigabyte      | EX38-DS4                    | [6dd3e18637](https://linux-hardware.org/?probe=6dd3e18637) | Mar 21, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [6b25c70b9f](https://linux-hardware.org/?probe=6b25c70b9f) | Mar 21, 2023 |
| Gigabyte      | Z77X-UD3H                   | [3b06195ff0](https://linux-hardware.org/?probe=3b06195ff0) | Mar 21, 2023 |
| Google        | Teemo                       | [3e60b11752](https://linux-hardware.org/?probe=3e60b11752) | Mar 21, 2023 |
| Supermicro    | X10DRi-T4+                  | [3aa5aebaee](https://linux-hardware.org/?probe=3aa5aebaee) | Mar 20, 2023 |
| HP            | 1825                        | [73a2e18f3a](https://linux-hardware.org/?probe=73a2e18f3a) | Mar 20, 2023 |
| Techvision    | TVI7309X B0                 | [67b681a703](https://linux-hardware.org/?probe=67b681a703) | Mar 20, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | [1a21f25ce5](https://linux-hardware.org/?probe=1a21f25ce5) | Mar 20, 2023 |
| ASUSTek       | A88X-PRO                    | [ea415770cb](https://linux-hardware.org/?probe=ea415770cb) | Mar 20, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [b5d9053f1c](https://linux-hardware.org/?probe=b5d9053f1c) | Mar 19, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [660ae0f7ed](https://linux-hardware.org/?probe=660ae0f7ed) | Mar 19, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [d7b27c1822](https://linux-hardware.org/?probe=d7b27c1822) | Mar 19, 2023 |
| Intel         | STK2M3W64CC H89289-506      | [5386cc221b](https://linux-hardware.org/?probe=5386cc221b) | Mar 19, 2023 |
| ASUSTek       | PRIME Z690-P D4             | [5308592de8](https://linux-hardware.org/?probe=5308592de8) | Mar 19, 2023 |
| Intel         | 945GCT-M                    | [ac83eeefb9](https://linux-hardware.org/?probe=ac83eeefb9) | Mar 19, 2023 |
| ASRock        | Z590M-ITX/ax                | [715b1e5c6b](https://linux-hardware.org/?probe=715b1e5c6b) | Mar 18, 2023 |
| Medion        | TJ4125                      | [6895b929a4](https://linux-hardware.org/?probe=6895b929a4) | Mar 18, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [1e96b578fa](https://linux-hardware.org/?probe=1e96b578fa) | Mar 18, 2023 |
| Gigabyte      | Q270M-D3H                   | [b244f2a8fd](https://linux-hardware.org/?probe=b244f2a8fd) | Mar 18, 2023 |
| ASRock        | X570 PG Velocita            | [bc3f2240b9](https://linux-hardware.org/?probe=bc3f2240b9) | Mar 18, 2023 |
| Techvision    | TVI7309X B0                 | [d1a16fdb17](https://linux-hardware.org/?probe=d1a16fdb17) | Mar 18, 2023 |
| Fujitsu       | D3601-A1 S26361-D3601-A1    | [ec47c2dcb7](https://linux-hardware.org/?probe=ec47c2dcb7) | Mar 18, 2023 |
| Techvision    | TVI7309X B0                 | [08572d5e7c](https://linux-hardware.org/?probe=08572d5e7c) | Mar 18, 2023 |
| Techvision    | TVI7309X B0                 | [82914cf856](https://linux-hardware.org/?probe=82914cf856) | Mar 18, 2023 |
| Lenovo        | ThinkServer TS440           | [f34d8572e9](https://linux-hardware.org/?probe=f34d8572e9) | Mar 18, 2023 |
| HP            | 198E                        | [23e214216d](https://linux-hardware.org/?probe=23e214216d) | Mar 17, 2023 |
| HP            | 198E                        | [d5d5af66a8](https://linux-hardware.org/?probe=d5d5af66a8) | Mar 17, 2023 |
| Dell          | PowerEdge M620              | [c628cb7f90](https://linux-hardware.org/?probe=c628cb7f90) | Mar 17, 2023 |
| Gigabyte      | M52L-S3P                    | [89660a09c2](https://linux-hardware.org/?probe=89660a09c2) | Mar 17, 2023 |
| MSI           | MPG Z690 EDGE TI WIFI DD... | [b42850eb13](https://linux-hardware.org/?probe=b42850eb13) | Mar 17, 2023 |
| Gigabyte      | AX370-Gaming 5              | [97d434b3b5](https://linux-hardware.org/?probe=97d434b3b5) | Mar 16, 2023 |
| Gigabyte      | AX370-Gaming 5              | [dd101b4b05](https://linux-hardware.org/?probe=dd101b4b05) | Mar 16, 2023 |
| ASUSTek       | M4A88T-M                    | [372deb4bed](https://linux-hardware.org/?probe=372deb4bed) | Mar 16, 2023 |
| ASUSTek       | M4A88T-M                    | [d8e1601e65](https://linux-hardware.org/?probe=d8e1601e65) | Mar 16, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [0b9755873a](https://linux-hardware.org/?probe=0b9755873a) | Mar 16, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [4e61f760cb](https://linux-hardware.org/?probe=4e61f760cb) | Mar 16, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [b7671cbae5](https://linux-hardware.org/?probe=b7671cbae5) | Mar 16, 2023 |
| Gigabyte      | Q270M-D3H                   | [8841b23ef7](https://linux-hardware.org/?probe=8841b23ef7) | Mar 16, 2023 |
| ASRock        | X570 PG Velocita            | [bd8bc5740e](https://linux-hardware.org/?probe=bd8bc5740e) | Mar 16, 2023 |
| ASRock        | B450M Pro4                  | [108d237ebe](https://linux-hardware.org/?probe=108d237ebe) | Mar 16, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [b843a727ce](https://linux-hardware.org/?probe=b843a727ce) | Mar 15, 2023 |
| Gigabyte      | Z77X-UD3H                   | [a22bba0e53](https://linux-hardware.org/?probe=a22bba0e53) | Mar 15, 2023 |
| Cincoze       | P1101.01.001                | [9443379d5e](https://linux-hardware.org/?probe=9443379d5e) | Mar 15, 2023 |
| iEi           | SAT3 V1.03                  | [2d3c739ac5](https://linux-hardware.org/?probe=2d3c739ac5) | Mar 15, 2023 |
| iEi           | SAT3 V1.03                  | [f6f29a0f8a](https://linux-hardware.org/?probe=f6f29a0f8a) | Mar 15, 2023 |
| ASUSTek       | B85M-G                      | [ea280402ca](https://linux-hardware.org/?probe=ea280402ca) | Mar 15, 2023 |
| ASUSTek       | B85M-G                      | [513385d981](https://linux-hardware.org/?probe=513385d981) | Mar 15, 2023 |
| ASUSTek       | PRIME Z370-P                | [82e7940a77](https://linux-hardware.org/?probe=82e7940a77) | Mar 15, 2023 |
| Unknown       | Unknown                     | [0eb13c3117](https://linux-hardware.org/?probe=0eb13c3117) | Mar 15, 2023 |
| Unknown       | Unknown                     | [6e24f7a3c1](https://linux-hardware.org/?probe=6e24f7a3c1) | Mar 15, 2023 |
| Gigabyte      | B450M DS3H V2               | [b952483e9a](https://linux-hardware.org/?probe=b952483e9a) | Mar 15, 2023 |
| HP            | 1495                        | [72769abb34](https://linux-hardware.org/?probe=72769abb34) | Mar 15, 2023 |
| Gigabyte      | H97M-HD3                    | [6831505433](https://linux-hardware.org/?probe=6831505433) | Mar 14, 2023 |
| HP            | ProLiant SL4540 Gen8        | [fb493ce600](https://linux-hardware.org/?probe=fb493ce600) | Mar 14, 2023 |
| Intel         | D945GCPE AAD97209-201       | [7733f89d7d](https://linux-hardware.org/?probe=7733f89d7d) | Mar 14, 2023 |
| Unknown       | Unknown                     | [3c314ab1c2](https://linux-hardware.org/?probe=3c314ab1c2) | Mar 14, 2023 |
| Unknown       | Unknown                     | [eff328db22](https://linux-hardware.org/?probe=eff328db22) | Mar 14, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [9793c62af0](https://linux-hardware.org/?probe=9793c62af0) | Mar 13, 2023 |
| MSI           | H110M PRO-VH PLUS           | [088b681bdd](https://linux-hardware.org/?probe=088b681bdd) | Mar 13, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [5545b43cf0](https://linux-hardware.org/?probe=5545b43cf0) | Mar 13, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [0211c6712f](https://linux-hardware.org/?probe=0211c6712f) | Mar 13, 2023 |
| Gigabyte      | H61M-DS2                    | [0cee087c15](https://linux-hardware.org/?probe=0cee087c15) | Mar 13, 2023 |
| Gigabyte      | X570 UD                     | [839a069bc4](https://linux-hardware.org/?probe=839a069bc4) | Mar 13, 2023 |
| ASRock        | 970M Pro3                   | [a35e76c9bf](https://linux-hardware.org/?probe=a35e76c9bf) | Mar 13, 2023 |
| ASUSTek       | PRIME B450M-A               | [881e48f258](https://linux-hardware.org/?probe=881e48f258) | Mar 13, 2023 |
| ASUSTek       | PRIME B450M-A               | [6ddc564b5d](https://linux-hardware.org/?probe=6ddc564b5d) | Mar 12, 2023 |
| HP            | 1825                        | [85011ed37d](https://linux-hardware.org/?probe=85011ed37d) | Mar 12, 2023 |
| Medion        | TJ4125                      | [5b8893bf40](https://linux-hardware.org/?probe=5b8893bf40) | Mar 12, 2023 |
| ASRock        | B450 Pro4                   | [4dd7be5be9](https://linux-hardware.org/?probe=4dd7be5be9) | Mar 12, 2023 |
| ASRock        | B450 Pro4                   | [ce0343a044](https://linux-hardware.org/?probe=ce0343a044) | Mar 12, 2023 |
| Gigabyte      | B760M AORUS ELITE AX        | [daf687f0a1](https://linux-hardware.org/?probe=daf687f0a1) | Mar 12, 2023 |
| Medion        | TJ4125                      | [a93f645a7b](https://linux-hardware.org/?probe=a93f645a7b) | Mar 11, 2023 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | [c91efb0de0](https://linux-hardware.org/?probe=c91efb0de0) | Mar 11, 2023 |
| MSI           | MS-B1831                    | [a9bfb4f294](https://linux-hardware.org/?probe=a9bfb4f294) | Mar 11, 2023 |
| ASRock        | 970M Pro3                   | [988d270005](https://linux-hardware.org/?probe=988d270005) | Mar 11, 2023 |
| ASRock        | B660M-STX                   | [2d0fdf6553](https://linux-hardware.org/?probe=2d0fdf6553) | Mar 11, 2023 |
| ASRock        | B660M-STX                   | [34a92205b4](https://linux-hardware.org/?probe=34a92205b4) | Mar 11, 2023 |
| MSI           | B560M PRO-VDH WIFI [CEC]    | [eff63861e7](https://linux-hardware.org/?probe=eff63861e7) | Mar 11, 2023 |
| ASRock        | Z790 Taichi Carrara         | [629adaf380](https://linux-hardware.org/?probe=629adaf380) | Mar 11, 2023 |
| HP            | 8076 MVB,A                  | [20150077f5](https://linux-hardware.org/?probe=20150077f5) | Mar 11, 2023 |
| Dell          | 01XK1W A00                  | [f8e050789f](https://linux-hardware.org/?probe=f8e050789f) | Mar 11, 2023 |
| ASUSTek       | AT3N7A-I                    | [59de62aac5](https://linux-hardware.org/?probe=59de62aac5) | Mar 11, 2023 |
| Gigabyte      | Z77X-UD3H                   | [823c3530a1](https://linux-hardware.org/?probe=823c3530a1) | Mar 10, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | [35ab0f32c5](https://linux-hardware.org/?probe=35ab0f32c5) | Mar 10, 2023 |
| Gigabyte      | B360M D2V                   | [dd67a26e98](https://linux-hardware.org/?probe=dd67a26e98) | Mar 10, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [cfacdb386a](https://linux-hardware.org/?probe=cfacdb386a) | Mar 09, 2023 |
| GoWin Solu... | R86S                        | [495614211e](https://linux-hardware.org/?probe=495614211e) | Mar 09, 2023 |
| ASRock        | G31M-VS2                    | [c098fa3ee0](https://linux-hardware.org/?probe=c098fa3ee0) | Mar 09, 2023 |
| AZW           | MINI S                      | [e304668a70](https://linux-hardware.org/?probe=e304668a70) | Mar 09, 2023 |
| ASRock        | 990FX Killer                | [326cdc81b2](https://linux-hardware.org/?probe=326cdc81b2) | Mar 09, 2023 |
| ASUSTek       | PRIME X570-P                | [588a008ee1](https://linux-hardware.org/?probe=588a008ee1) | Mar 08, 2023 |
| ASUSTek       | P5G41T-M LX                 | [4f55573ba6](https://linux-hardware.org/?probe=4f55573ba6) | Mar 08, 2023 |
| Intel         | JSL MRD                     | [ac75dbf1f6](https://linux-hardware.org/?probe=ac75dbf1f6) | Mar 08, 2023 |
| HP            | 0AACh                       | [2f4ba72670](https://linux-hardware.org/?probe=2f4ba72670) | Mar 08, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [69dd85d8cf](https://linux-hardware.org/?probe=69dd85d8cf) | Mar 07, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [ced1079ce2](https://linux-hardware.org/?probe=ced1079ce2) | Mar 07, 2023 |
| ASRock        | B450M-HDV                   | [cca3440ed3](https://linux-hardware.org/?probe=cca3440ed3) | Mar 07, 2023 |
| MSI           | 880GM-E43                   | [f4027fb865](https://linux-hardware.org/?probe=f4027fb865) | Mar 07, 2023 |
| Lenovo        | MAHOBAY                     | [e4e709f69a](https://linux-hardware.org/?probe=e4e709f69a) | Mar 07, 2023 |
| Gigabyte      | B360M DS3H                  | [5a1521197e](https://linux-hardware.org/?probe=5a1521197e) | Mar 07, 2023 |
| Dell          | 0F5C5X A00                  | [5f0ab2a253](https://linux-hardware.org/?probe=5f0ab2a253) | Mar 06, 2023 |
| ASUSTek       | M4N68T-M-LE-V2              | [a0bccf2d2b](https://linux-hardware.org/?probe=a0bccf2d2b) | Mar 06, 2023 |
| HP            | ProLiant MicroServer Gen... | [ae0bbd2f73](https://linux-hardware.org/?probe=ae0bbd2f73) | Mar 06, 2023 |
| ASRock        | B450M Pro4 R2.0             | [31376d711e](https://linux-hardware.org/?probe=31376d711e) | Mar 06, 2023 |
| ASUSTek       | M4N68T-M-LE-V2              | [2f63b318f6](https://linux-hardware.org/?probe=2f63b318f6) | Mar 06, 2023 |
| Gigabyte      | Z68X-UD3-B3                 | [f2be73745e](https://linux-hardware.org/?probe=f2be73745e) | Mar 06, 2023 |
| AZW           | MINI S                      | [cb0b08973d](https://linux-hardware.org/?probe=cb0b08973d) | Mar 06, 2023 |
| ASRock        | 990FX Extreme4              | [641d1c6a8f](https://linux-hardware.org/?probe=641d1c6a8f) | Mar 05, 2023 |
| Gigabyte      | H55M-S2H                    | [545e7119e9](https://linux-hardware.org/?probe=545e7119e9) | Mar 04, 2023 |
| HP            | 82B4                        | [47d445cfa6](https://linux-hardware.org/?probe=47d445cfa6) | Mar 04, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [ae03ade800](https://linux-hardware.org/?probe=ae03ade800) | Mar 04, 2023 |
| Unknown       | i855-W83627HF               | [e60d4877f4](https://linux-hardware.org/?probe=e60d4877f4) | Mar 04, 2023 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | [a9c39c2b82](https://linux-hardware.org/?probe=a9c39c2b82) | Mar 04, 2023 |
| MSI           | B250M MORTAR                | [a4e8543fe2](https://linux-hardware.org/?probe=a4e8543fe2) | Mar 03, 2023 |
| ASUSTek       | P5KPL-AM                    | [7471275fc7](https://linux-hardware.org/?probe=7471275fc7) | Mar 03, 2023 |
| ASUSTek       | M4N68T-M-LE-V2              | [31fc7e49b2](https://linux-hardware.org/?probe=31fc7e49b2) | Mar 03, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [7adf1c211e](https://linux-hardware.org/?probe=7adf1c211e) | Mar 03, 2023 |
| ASUSTek       | PRIME H510M-K               | [1a83a85925](https://linux-hardware.org/?probe=1a83a85925) | Mar 03, 2023 |
| Win elemen... | M600                        | [36ce350e0c](https://linux-hardware.org/?probe=36ce350e0c) | Mar 03, 2023 |
| Dell          | 0D6H9T A02                  | [0027e59622](https://linux-hardware.org/?probe=0027e59622) | Mar 02, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [8f61a5507b](https://linux-hardware.org/?probe=8f61a5507b) | Mar 02, 2023 |
| AMI           | Intel                       | [b6d932a0ed](https://linux-hardware.org/?probe=b6d932a0ed) | Mar 02, 2023 |
| ASUSTek       | M5A97 R2.0                  | [0e66878368](https://linux-hardware.org/?probe=0e66878368) | Mar 02, 2023 |
| ASRockRack    | B450D4U-V1L                 | [93e91a76bf](https://linux-hardware.org/?probe=93e91a76bf) | Mar 02, 2023 |
| ASRockRack    | B450D4U-V1L                 | [1774000cc4](https://linux-hardware.org/?probe=1774000cc4) | Mar 02, 2023 |
| HPE           | ProLiant MicroServer Gen... | [11c1bf8316](https://linux-hardware.org/?probe=11c1bf8316) | Mar 02, 2023 |
| ECS           | G31T-M9                     | [88447490cb](https://linux-hardware.org/?probe=88447490cb) | Mar 02, 2023 |
| Supermicro    | X9DR3-F                     | [977be97551](https://linux-hardware.org/?probe=977be97551) | Mar 02, 2023 |
| Supermicro    | X9DR3-F                     | [2191c9e96a](https://linux-hardware.org/?probe=2191c9e96a) | Mar 02, 2023 |
| Supermicro    | X9DR3-F                     | [5b8c79ac33](https://linux-hardware.org/?probe=5b8c79ac33) | Mar 02, 2023 |
| Supermicro    | X9DR3-F                     | [80644bb1ec](https://linux-hardware.org/?probe=80644bb1ec) | Mar 02, 2023 |
| Gigabyte      | H310M H x.x                 | [f6b780ae7e](https://linux-hardware.org/?probe=f6b780ae7e) | Mar 01, 2023 |
| CWWK          | CW-J6-6L                    | [aea23f5903](https://linux-hardware.org/?probe=aea23f5903) | Mar 01, 2023 |
| Gigabyte      | H310M H x.x                 | [25112e4f96](https://linux-hardware.org/?probe=25112e4f96) | Mar 01, 2023 |
| Unknown       | J3160-4L                    | [8089ba23b4](https://linux-hardware.org/?probe=8089ba23b4) | Mar 01, 2023 |
| Gigabyte      | B650M DS3H                  | [6e5e4d848d](https://linux-hardware.org/?probe=6e5e4d848d) | Mar 01, 2023 |
| AZW           | MINI S                      | [2206d30a53](https://linux-hardware.org/?probe=2206d30a53) | Mar 01, 2023 |
| HP            | 8433 11                     | [15dccf1191](https://linux-hardware.org/?probe=15dccf1191) | Mar 01, 2023 |
| Medion        | TJ4125                      | [2024916642](https://linux-hardware.org/?probe=2024916642) | Feb 28, 2023 |
| CWWK          | CW-J6-6L                    | [46c17d2c14](https://linux-hardware.org/?probe=46c17d2c14) | Feb 28, 2023 |
| ASUSTek       | AT4NM10T-I                  | [921aebe62a](https://linux-hardware.org/?probe=921aebe62a) | Feb 28, 2023 |
| Unknown       | Unknown                     | [89822406cc](https://linux-hardware.org/?probe=89822406cc) | Feb 28, 2023 |
| HP            | 83E2                        | [fdbe4ec1cb](https://linux-hardware.org/?probe=fdbe4ec1cb) | Feb 28, 2023 |
| Gigabyte      | A320M-S2H-CF                | [19fd766ea6](https://linux-hardware.org/?probe=19fd766ea6) | Feb 28, 2023 |
| ASUSTek       | P8B75-V                     | [17fcfc2758](https://linux-hardware.org/?probe=17fcfc2758) | Feb 28, 2023 |
| AZW           | MINI S                      | [e65b0d1ef6](https://linux-hardware.org/?probe=e65b0d1ef6) | Feb 28, 2023 |
| Gigabyte      | H61M-DS2                    | [49205269e7](https://linux-hardware.org/?probe=49205269e7) | Feb 28, 2023 |
| Intel         | D945GCPE AAD97209-201       | [672684e416](https://linux-hardware.org/?probe=672684e416) | Feb 28, 2023 |
| ASUSTek       | AT4NM10T-I                  | [fa2df8125a](https://linux-hardware.org/?probe=fa2df8125a) | Feb 28, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [8cadddf432](https://linux-hardware.org/?probe=8cadddf432) | Feb 28, 2023 |
| Intel         | D945GCPE AAD97209-201       | [edf2240a74](https://linux-hardware.org/?probe=edf2240a74) | Feb 28, 2023 |
| ASRock        | N68C-S UCC                  | [a5469adf59](https://linux-hardware.org/?probe=a5469adf59) | Feb 28, 2023 |
| ASRockRack    | X470D4U2-2T                 | [4d3d5e02a1](https://linux-hardware.org/?probe=4d3d5e02a1) | Feb 28, 2023 |
| ASRock        | X370 Professional Gaming    | [3a670fbd63](https://linux-hardware.org/?probe=3a670fbd63) | Feb 27, 2023 |
| HP            | 3397                        | [8081d24eb1](https://linux-hardware.org/?probe=8081d24eb1) | Feb 27, 2023 |
| Dell          | 0MH651                      | [7921e9f8bc](https://linux-hardware.org/?probe=7921e9f8bc) | Feb 27, 2023 |
| Aquarius      | AQH310CM                    | [a2f4d0f77e](https://linux-hardware.org/?probe=a2f4d0f77e) | Feb 27, 2023 |
| ASUSTek       | P8B75-V                     | [7a8e478900](https://linux-hardware.org/?probe=7a8e478900) | Feb 27, 2023 |
| ASUSTek       | H61M-E                      | [ee5b36d127](https://linux-hardware.org/?probe=ee5b36d127) | Feb 27, 2023 |
| Dell          | 0NW6H5 A00                  | [b4485b65b3](https://linux-hardware.org/?probe=b4485b65b3) | Feb 27, 2023 |
| Dell          | 0NW6H5 A00                  | [a52e16df32](https://linux-hardware.org/?probe=a52e16df32) | Feb 27, 2023 |
| ASRock        | 970M Pro3                   | [787ddfd44c](https://linux-hardware.org/?probe=787ddfd44c) | Feb 26, 2023 |
| Gigabyte      | B550 GAMING X V2            | [9c64d6366e](https://linux-hardware.org/?probe=9c64d6366e) | Feb 26, 2023 |
| ASUSTek       | PRIME X370-PRO              | [aaa112feae](https://linux-hardware.org/?probe=aaa112feae) | Feb 26, 2023 |
| MSI           | B85M-E45                    | [a7748c0e8b](https://linux-hardware.org/?probe=a7748c0e8b) | Feb 25, 2023 |
| Medion        | TJ4125                      | [bde9228741](https://linux-hardware.org/?probe=bde9228741) | Feb 25, 2023 |
| Unknown       | Unknown                     | [3d8e9cb31b](https://linux-hardware.org/?probe=3d8e9cb31b) | Feb 24, 2023 |
| Intel         | JSL MRD                     | [84a33f3c84](https://linux-hardware.org/?probe=84a33f3c84) | Feb 24, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [7fe6e0dcde](https://linux-hardware.org/?probe=7fe6e0dcde) | Feb 24, 2023 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | [f5b4a5da72](https://linux-hardware.org/?probe=f5b4a5da72) | Feb 24, 2023 |
| HP            | 82F2 A01                    | [efc9b2fdbf](https://linux-hardware.org/?probe=efc9b2fdbf) | Feb 24, 2023 |
| HP            | 82F2 A01                    | [24dc4341d3](https://linux-hardware.org/?probe=24dc4341d3) | Feb 24, 2023 |
| Unknown       | Unknown                     | [5070b384cc](https://linux-hardware.org/?probe=5070b384cc) | Feb 24, 2023 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | [1989031eb6](https://linux-hardware.org/?probe=1989031eb6) | Feb 24, 2023 |
| Dell          | 0CNWVK A02                  | [1fd825c3df](https://linux-hardware.org/?probe=1fd825c3df) | Feb 24, 2023 |
| MSI           | MPG Z690 CARBON WIFI        | [52b14c9235](https://linux-hardware.org/?probe=52b14c9235) | Feb 24, 2023 |
| MSI           | MPG Z690 CARBON WIFI        | [a09d17dd16](https://linux-hardware.org/?probe=a09d17dd16) | Feb 24, 2023 |
| Dell          | 0GY6Y8 A01                  | [0806dcb9ca](https://linux-hardware.org/?probe=0806dcb9ca) | Feb 24, 2023 |
| Dell          | 0GY6Y8 A01                  | [e3cdd0b411](https://linux-hardware.org/?probe=e3cdd0b411) | Feb 24, 2023 |
| Gigabyte      | H610M S2H DDR4              | [e44618f1c3](https://linux-hardware.org/?probe=e44618f1c3) | Feb 23, 2023 |
| ASUSTek       | KRPA-U16 Series             | [e417ffd8e7](https://linux-hardware.org/?probe=e417ffd8e7) | Feb 23, 2023 |
| ASUSTek       | PRIME B560-PLUS             | [4f19f71811](https://linux-hardware.org/?probe=4f19f71811) | Feb 23, 2023 |
| ASUSTek       | P8H67-M                     | [a3ea522d78](https://linux-hardware.org/?probe=a3ea522d78) | Feb 23, 2023 |
| Intel         | H61                         | [de757dd659](https://linux-hardware.org/?probe=de757dd659) | Feb 23, 2023 |
| AZW           | U59                         | [9289537f45](https://linux-hardware.org/?probe=9289537f45) | Feb 22, 2023 |
| ASRockRack    | X470D4U2-2T                 | [9d233c96b5](https://linux-hardware.org/?probe=9d233c96b5) | Feb 22, 2023 |
| ASUSTek       | P8B75-V                     | [fb050eaf3c](https://linux-hardware.org/?probe=fb050eaf3c) | Feb 22, 2023 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [1d2132b142](https://linux-hardware.org/?probe=1d2132b142) | Feb 22, 2023 |
| AZW           | U59                         | [368562790b](https://linux-hardware.org/?probe=368562790b) | Feb 22, 2023 |
| ASUSTek       | PRIME X399-A                | [4009d82fc8](https://linux-hardware.org/?probe=4009d82fc8) | Feb 22, 2023 |
| Unknown       | Unknown                     | [5cf4127d47](https://linux-hardware.org/?probe=5cf4127d47) | Feb 21, 2023 |
| MSI           | MAG Z590 TORPEDO            | [30f09c71a1](https://linux-hardware.org/?probe=30f09c71a1) | Feb 21, 2023 |
| ASUSTek       | P8B75-V                     | [de56e36164](https://linux-hardware.org/?probe=de56e36164) | Feb 21, 2023 |
| HP            | ProLiant ML110 G7           | [56cbaf4274](https://linux-hardware.org/?probe=56cbaf4274) | Feb 21, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | [211cd972f0](https://linux-hardware.org/?probe=211cd972f0) | Feb 20, 2023 |
| Lenovo        | ThinkCentre M58e 7269E3S    | [6b30da3a31](https://linux-hardware.org/?probe=6b30da3a31) | Feb 20, 2023 |
| Dell          | 073MMW A02                  | [aa198228bc](https://linux-hardware.org/?probe=aa198228bc) | Feb 19, 2023 |
| Dell          | 0T065F A01                  | [c8b1f8651a](https://linux-hardware.org/?probe=c8b1f8651a) | Feb 19, 2023 |
| Gigabyte      | X299 UD4 Pro-CF             | [d442995b00](https://linux-hardware.org/?probe=d442995b00) | Feb 19, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | [34681494ec](https://linux-hardware.org/?probe=34681494ec) | Feb 18, 2023 |
| Pegatron      | 2AB6                        | [537c2d1b64](https://linux-hardware.org/?probe=537c2d1b64) | Feb 18, 2023 |
| Intel         | JSL MRD                     | [5e021f6a92](https://linux-hardware.org/?probe=5e021f6a92) | Feb 18, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | [a2cdf7d471](https://linux-hardware.org/?probe=a2cdf7d471) | Feb 18, 2023 |
| Gigabyte      | GA-A55M-DS2                 | [3159aede6c](https://linux-hardware.org/?probe=3159aede6c) | Feb 17, 2023 |
| ASUSTek       | H110M-R                     | [bd6636c99d](https://linux-hardware.org/?probe=bd6636c99d) | Feb 17, 2023 |
| Intel         | H61                         | [90e4a9358f](https://linux-hardware.org/?probe=90e4a9358f) | Feb 17, 2023 |
| MSI           | X399 SLI PLUS               | [8741094cd9](https://linux-hardware.org/?probe=8741094cd9) | Feb 17, 2023 |
| Lenovo        | 3164 NOK                    | [f69ff4a8c8](https://linux-hardware.org/?probe=f69ff4a8c8) | Feb 16, 2023 |
| MSI           | Z270 TOMAHAWK ARCTIC        | [cfdcc68921](https://linux-hardware.org/?probe=cfdcc68921) | Feb 16, 2023 |
| MSI           | Z270 TOMAHAWK ARCTIC        | [7bb3c6268f](https://linux-hardware.org/?probe=7bb3c6268f) | Feb 16, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [8f202b88fa](https://linux-hardware.org/?probe=8f202b88fa) | Feb 16, 2023 |
| ASRock        | B550 Pro4                   | [9ad890517a](https://linux-hardware.org/?probe=9ad890517a) | Feb 16, 2023 |
| ASRock        | X370 Gaming X               | [cda38b5b9b](https://linux-hardware.org/?probe=cda38b5b9b) | Feb 16, 2023 |
| ASUSTek       | P7H55-M SI                  | [387881f288](https://linux-hardware.org/?probe=387881f288) | Feb 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [bbce6ba3b1](https://linux-hardware.org/?probe=bbce6ba3b1) | Feb 16, 2023 |
| Lenovo        | 1030 SDK0J40705 WIN 3425... | [daed0124f0](https://linux-hardware.org/?probe=daed0124f0) | Feb 16, 2023 |
| Gigabyte      | H270M-D3H-CF                | [7a58ceb644](https://linux-hardware.org/?probe=7a58ceb644) | Feb 15, 2023 |
| ASUSTek       | F2A85-M PRO                 | [c5b8952fdb](https://linux-hardware.org/?probe=c5b8952fdb) | Feb 15, 2023 |
| ASRock        | X300M-STX                   | [2b25f214e9](https://linux-hardware.org/?probe=2b25f214e9) | Feb 15, 2023 |
| ASRock        | X300M-STX                   | [5bf8aa635c](https://linux-hardware.org/?probe=5bf8aa635c) | Feb 15, 2023 |
| Gigabyte      | EP43-S3L                    | [82730ed699](https://linux-hardware.org/?probe=82730ed699) | Feb 15, 2023 |
| Itautec       | ST 4265                     | [84023fa8ac](https://linux-hardware.org/?probe=84023fa8ac) | Feb 15, 2023 |
| ASUSTek       | P5GD1 PRO                   | [043021ca86](https://linux-hardware.org/?probe=043021ca86) | Feb 15, 2023 |
| ASRock        | Z77 Extreme6                | [48328ab864](https://linux-hardware.org/?probe=48328ab864) | Feb 15, 2023 |
| Unknown       | Unknown                     | [fe12f077df](https://linux-hardware.org/?probe=fe12f077df) | Feb 15, 2023 |
| Gigabyte      | B450M H                     | [5ebd73227b](https://linux-hardware.org/?probe=5ebd73227b) | Feb 14, 2023 |
| Unknown       | Unknown                     | [0ac84e31dd](https://linux-hardware.org/?probe=0ac84e31dd) | Feb 14, 2023 |
| Dell          | 0RN474                      | [5c1bf45372](https://linux-hardware.org/?probe=5c1bf45372) | Feb 14, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [27fa84ce56](https://linux-hardware.org/?probe=27fa84ce56) | Feb 14, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [8895a873ab](https://linux-hardware.org/?probe=8895a873ab) | Feb 14, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [fb00615692](https://linux-hardware.org/?probe=fb00615692) | Feb 14, 2023 |
| Gigabyte      | X570 UD                     | [ae563f7bfe](https://linux-hardware.org/?probe=ae563f7bfe) | Feb 14, 2023 |
| HP            | 3648h                       | [18eb122bc9](https://linux-hardware.org/?probe=18eb122bc9) | Feb 14, 2023 |
| Shenzhen M... | F6BFC                       | [67b141272c](https://linux-hardware.org/?probe=67b141272c) | Feb 14, 2023 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | [c69ee15636](https://linux-hardware.org/?probe=c69ee15636) | Feb 14, 2023 |
| Dell          | 0RN474                      | [20f3c37dc2](https://linux-hardware.org/?probe=20f3c37dc2) | Feb 14, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | [34ad4bac16](https://linux-hardware.org/?probe=34ad4bac16) | Feb 13, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | [55e684c121](https://linux-hardware.org/?probe=55e684c121) | Feb 13, 2023 |
| Unknown       | Unknown                     | [c49317ce12](https://linux-hardware.org/?probe=c49317ce12) | Feb 13, 2023 |
| MSI           | H97 GAMING 3                | [855634fadc](https://linux-hardware.org/?probe=855634fadc) | Feb 13, 2023 |
| Unknown       | Unknown                     | [b1d1f36f51](https://linux-hardware.org/?probe=b1d1f36f51) | Feb 13, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [517a5a9e81](https://linux-hardware.org/?probe=517a5a9e81) | Feb 13, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | [e83cd923a5](https://linux-hardware.org/?probe=e83cd923a5) | Feb 13, 2023 |
| Gigabyte      | B450M H                     | [124d65cd04](https://linux-hardware.org/?probe=124d65cd04) | Feb 12, 2023 |
| Gigabyte      | H81M-S2V                    | [09dff429cd](https://linux-hardware.org/?probe=09dff429cd) | Feb 12, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | [52674d23ad](https://linux-hardware.org/?probe=52674d23ad) | Feb 12, 2023 |
| ASRock        | X300M-STX                   | [4829b991be](https://linux-hardware.org/?probe=4829b991be) | Feb 12, 2023 |
| ASRock        | A320M-DVS R4.0              | [1589cfe790](https://linux-hardware.org/?probe=1589cfe790) | Feb 11, 2023 |
| ASRock        | A320M-DVS R4.0              | [22fdde82eb](https://linux-hardware.org/?probe=22fdde82eb) | Feb 11, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | [ed3233c97b](https://linux-hardware.org/?probe=ed3233c97b) | Feb 11, 2023 |
| ASUSTek       | P5VD2-X                     | [32a509e760](https://linux-hardware.org/?probe=32a509e760) | Feb 11, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | [2695a9350a](https://linux-hardware.org/?probe=2695a9350a) | Feb 11, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [d003016397](https://linux-hardware.org/?probe=d003016397) | Feb 11, 2023 |
| AZW           | U59                         | [24ccf521f0](https://linux-hardware.org/?probe=24ccf521f0) | Feb 11, 2023 |
| Dell          | 0J3C2F A00                  | [a3f08d08aa](https://linux-hardware.org/?probe=a3f08d08aa) | Feb 11, 2023 |
| MSI           | H110M PRO-VD                | [5483d83053](https://linux-hardware.org/?probe=5483d83053) | Feb 11, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [7b6a31ec69](https://linux-hardware.org/?probe=7b6a31ec69) | Feb 11, 2023 |
| AMD           | CM-iGLX Platform Board R... | [c256a73072](https://linux-hardware.org/?probe=c256a73072) | Feb 11, 2023 |
| Maxtang       | EHL30 V1.0                  | [4d133c615c](https://linux-hardware.org/?probe=4d133c615c) | Feb 10, 2023 |
| ASRockRack    | X570D4U                     | [bb2c98768e](https://linux-hardware.org/?probe=bb2c98768e) | Feb 10, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [65e66dbf71](https://linux-hardware.org/?probe=65e66dbf71) | Feb 10, 2023 |
| Intel         | H61                         | [e07896a0a6](https://linux-hardware.org/?probe=e07896a0a6) | Feb 10, 2023 |
| ASUSTek       | M4N78                       | [34ddf02a41](https://linux-hardware.org/?probe=34ddf02a41) | Feb 10, 2023 |
| Gigabyte      | B550 GAMING X V2            | [8c4ab545de](https://linux-hardware.org/?probe=8c4ab545de) | Feb 09, 2023 |
| Acer          | Veriton N4630G              | [262d8ec347](https://linux-hardware.org/?probe=262d8ec347) | Feb 09, 2023 |
| MSI           | H97 GAMING 3                | [209d4693fe](https://linux-hardware.org/?probe=209d4693fe) | Feb 09, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [82173d3b08](https://linux-hardware.org/?probe=82173d3b08) | Feb 09, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | [a0132107aa](https://linux-hardware.org/?probe=a0132107aa) | Feb 08, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | [6231dbe6d4](https://linux-hardware.org/?probe=6231dbe6d4) | Feb 08, 2023 |
| Gigabyte      | GA-MA78GM-S2H               | [bbaa8165e4](https://linux-hardware.org/?probe=bbaa8165e4) | Feb 08, 2023 |
| Lenovo        | 3164 NOK                    | [750d30cb48](https://linux-hardware.org/?probe=750d30cb48) | Feb 08, 2023 |
| Intel         | DH67CL AAG10212-208         | [e53a89d83d](https://linux-hardware.org/?probe=e53a89d83d) | Feb 08, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | [8fb3a20b27](https://linux-hardware.org/?probe=8fb3a20b27) | Feb 08, 2023 |
| ASUSTek       | PRIME H610M-A WIFI D4       | [1b800ff8c2](https://linux-hardware.org/?probe=1b800ff8c2) | Feb 07, 2023 |
| ASUSTek       | PRIME H610M-A WIFI D4       | [69f96bffa5](https://linux-hardware.org/?probe=69f96bffa5) | Feb 07, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | [83380dcad6](https://linux-hardware.org/?probe=83380dcad6) | Feb 07, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [4b19274da1](https://linux-hardware.org/?probe=4b19274da1) | Feb 06, 2023 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | [bc5b9a2c5d](https://linux-hardware.org/?probe=bc5b9a2c5d) | Feb 06, 2023 |
| HP            | 3397                        | [2fb7638874](https://linux-hardware.org/?probe=2fb7638874) | Feb 06, 2023 |
| Intel         | DH77EB AAG39073-304         | [b3169f788f](https://linux-hardware.org/?probe=b3169f788f) | Feb 06, 2023 |
| AZW           | U59                         | [b97c4f6277](https://linux-hardware.org/?probe=b97c4f6277) | Feb 06, 2023 |
| MSI           | MPG Z690 CARBON WIFI        | [db292bc714](https://linux-hardware.org/?probe=db292bc714) | Feb 05, 2023 |
| HP            | 0A64h                       | [40ef639345](https://linux-hardware.org/?probe=40ef639345) | Feb 05, 2023 |
| Huanan        | X99-T8D V1.2                | [cb7e750cee](https://linux-hardware.org/?probe=cb7e750cee) | Feb 05, 2023 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | [55402fea35](https://linux-hardware.org/?probe=55402fea35) | Feb 05, 2023 |
| Gigabyte      | H61MA-D2V                   | [b708cdc12f](https://linux-hardware.org/?probe=b708cdc12f) | Feb 05, 2023 |
| Gigabyte      | B450M S2H                   | [c3891f43b5](https://linux-hardware.org/?probe=c3891f43b5) | Feb 05, 2023 |
| Gigabyte      | Z77X-UD3H                   | [6023defc83](https://linux-hardware.org/?probe=6023defc83) | Feb 05, 2023 |
| HP            | 2B36                        | [dde1352d90](https://linux-hardware.org/?probe=dde1352d90) | Feb 05, 2023 |
| Unknown       | Unknown                     | [5a491991ef](https://linux-hardware.org/?probe=5a491991ef) | Feb 05, 2023 |
| MSI           | A320M PRO-M2                | [3fa2ac81f2](https://linux-hardware.org/?probe=3fa2ac81f2) | Feb 05, 2023 |
| Dell          | 0D4MD1 A00                  | [7198c3d131](https://linux-hardware.org/?probe=7198c3d131) | Feb 05, 2023 |
| ECS           | H61H2-MV                    | [e0a93d257b](https://linux-hardware.org/?probe=e0a93d257b) | Feb 05, 2023 |
| OEM           | Intel H81                   | [806280459d](https://linux-hardware.org/?probe=806280459d) | Feb 05, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | [f2423d1d75](https://linux-hardware.org/?probe=f2423d1d75) | Feb 05, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [2543adebba](https://linux-hardware.org/?probe=2543adebba) | Feb 05, 2023 |
| HP            | 1589                        | [7b3a0cf51b](https://linux-hardware.org/?probe=7b3a0cf51b) | Feb 04, 2023 |
| ASRock        | 4X4-4000 Series             | [4ed27fe851](https://linux-hardware.org/?probe=4ed27fe851) | Feb 04, 2023 |
| Gigabyte      | MZBSWMP-00                  | [018b3728ea](https://linux-hardware.org/?probe=018b3728ea) | Feb 04, 2023 |
| Gigabyte      | MZBSWMP-00                  | [52bb20e0b2](https://linux-hardware.org/?probe=52bb20e0b2) | Feb 04, 2023 |
| ECS           | A780GM-A                    | [2cb7086ff1](https://linux-hardware.org/?probe=2cb7086ff1) | Feb 04, 2023 |
| ECS           | A780GM-A                    | [6f6599f880](https://linux-hardware.org/?probe=6f6599f880) | Feb 04, 2023 |
| HP            | 3048h                       | [03b28af2be](https://linux-hardware.org/?probe=03b28af2be) | Feb 03, 2023 |
| AZW           | MINI S                      | [6c746a5f95](https://linux-hardware.org/?probe=6c746a5f95) | Feb 03, 2023 |
| ASUSTek       | M5A97 R2.0                  | [c0c511ec65](https://linux-hardware.org/?probe=c0c511ec65) | Feb 03, 2023 |
| Dell          | 05WNJ2 A02                  | [4619f572c5](https://linux-hardware.org/?probe=4619f572c5) | Feb 03, 2023 |
| BESSTAR Te... | TH50                        | [6d39ef2792](https://linux-hardware.org/?probe=6d39ef2792) | Feb 03, 2023 |
| Intel         | SKYBAY                      | [a75cb78ad9](https://linux-hardware.org/?probe=a75cb78ad9) | Feb 02, 2023 |
| NEC Comput... | MS9666 011                  | [26a38770fe](https://linux-hardware.org/?probe=26a38770fe) | Feb 02, 2023 |
| ASUSTek       | Z170-DELUXE                 | [2cb0ec3b98](https://linux-hardware.org/?probe=2cb0ec3b98) | Feb 01, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [203e3fe693](https://linux-hardware.org/?probe=203e3fe693) | Feb 01, 2023 |
| ASUSTek       | P9X79                       | [01e8662b39](https://linux-hardware.org/?probe=01e8662b39) | Feb 01, 2023 |
| Gigabyte      | X299 AORUS Gaming 3-CF      | [775a993b3a](https://linux-hardware.org/?probe=775a993b3a) | Feb 01, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [142f5fcb2d](https://linux-hardware.org/?probe=142f5fcb2d) | Feb 01, 2023 |
| ASRock        | X570 Pro4                   | [81b19ff917](https://linux-hardware.org/?probe=81b19ff917) | Feb 01, 2023 |
| Gigabyte      | Z690M DS3H DDR4             | [8f858cb9b9](https://linux-hardware.org/?probe=8f858cb9b9) | Jan 31, 2023 |
| MSI           | 870A-G54                    | [0aaa012de5](https://linux-hardware.org/?probe=0aaa012de5) | Jan 31, 2023 |
| Gigabyte      | P85-D3                      | [7e25d19fae](https://linux-hardware.org/?probe=7e25d19fae) | Jan 31, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [a2c87504d6](https://linux-hardware.org/?probe=a2c87504d6) | Jan 31, 2023 |
| ASRock        | G31M-VS2                    | [e12dd528ea](https://linux-hardware.org/?probe=e12dd528ea) | Jan 31, 2023 |
| MSI           | H81M-E34                    | [19b8f90522](https://linux-hardware.org/?probe=19b8f90522) | Jan 31, 2023 |
| ASUSTek       | PRIME B250-A                | [c686d3d123](https://linux-hardware.org/?probe=c686d3d123) | Jan 31, 2023 |
| ASRock        | X570 Pro4                   | [37999411ed](https://linux-hardware.org/?probe=37999411ed) | Jan 31, 2023 |
| ASUSTek       | H61M-A/BR                   | [b6a73bd22e](https://linux-hardware.org/?probe=b6a73bd22e) | Jan 30, 2023 |
| ASUSTek       | H61M-A/BR                   | [0ae96c2bbc](https://linux-hardware.org/?probe=0ae96c2bbc) | Jan 30, 2023 |
| NetGear       | ReadyDATA 5200              | [74a68eba33](https://linux-hardware.org/?probe=74a68eba33) | Jan 30, 2023 |
| ASUSTek       | P8H61-MX                    | [f13f4da766](https://linux-hardware.org/?probe=f13f4da766) | Jan 30, 2023 |
| HP            | 0A64h                       | [da7b36ad47](https://linux-hardware.org/?probe=da7b36ad47) | Jan 30, 2023 |
| Dell          | 02YRK5 A02                  | [d6faeebd74](https://linux-hardware.org/?probe=d6faeebd74) | Jan 29, 2023 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | [55c3e9597c](https://linux-hardware.org/?probe=55c3e9597c) | Jan 29, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | [6b634c85e8](https://linux-hardware.org/?probe=6b634c85e8) | Jan 29, 2023 |
| ASUSTek       | P8H67                       | [c6163491b5](https://linux-hardware.org/?probe=c6163491b5) | Jan 29, 2023 |
| Medion        | TJ4125                      | [5fb5d01ae9](https://linux-hardware.org/?probe=5fb5d01ae9) | Jan 29, 2023 |
| Gigabyte      | 8IPE1000-G/L                | [6f83e8b57d](https://linux-hardware.org/?probe=6f83e8b57d) | Jan 29, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [eb551b5ec0](https://linux-hardware.org/?probe=eb551b5ec0) | Jan 29, 2023 |
| Gigabyte      | M61PME-S2                   | [8227150e0d](https://linux-hardware.org/?probe=8227150e0d) | Jan 29, 2023 |
| Gigabyte      | M61PME-S2                   | [813f01976d](https://linux-hardware.org/?probe=813f01976d) | Jan 29, 2023 |
| ASRock        | B550 Pro4                   | [eaed78d213](https://linux-hardware.org/?probe=eaed78d213) | Jan 28, 2023 |
| Dell          | 0F8098                      | [d6066c739e](https://linux-hardware.org/?probe=d6066c739e) | Jan 28, 2023 |
| Gigabyte      | Z97M-DS3H                   | [e9fc2c87df](https://linux-hardware.org/?probe=e9fc2c87df) | Jan 28, 2023 |
| ASRock        | B550 Pro4                   | [5fa28ba14d](https://linux-hardware.org/?probe=5fa28ba14d) | Jan 28, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [6e55ab69b8](https://linux-hardware.org/?probe=6e55ab69b8) | Jan 28, 2023 |
| HP            | 1998                        | [81da484cc4](https://linux-hardware.org/?probe=81da484cc4) | Jan 28, 2023 |
| ASUSTek       | B85M-G                      | [4a83dc2dc2](https://linux-hardware.org/?probe=4a83dc2dc2) | Jan 27, 2023 |
| MSI           | B365M PRO-VDH               | [d5bbfc18d5](https://linux-hardware.org/?probe=d5bbfc18d5) | Jan 27, 2023 |
| AZW           | MINI S                      | [ce5e6b1504](https://linux-hardware.org/?probe=ce5e6b1504) | Jan 26, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [0093f9df93](https://linux-hardware.org/?probe=0093f9df93) | Jan 26, 2023 |
| HP            | 805D                        | [b1996094a9](https://linux-hardware.org/?probe=b1996094a9) | Jan 26, 2023 |
| Inventec      | D CLASS A02                 | [2e70086887](https://linux-hardware.org/?probe=2e70086887) | Jan 25, 2023 |
| ASUSTek       | P8H61-M LX2                 | [dee0143024](https://linux-hardware.org/?probe=dee0143024) | Jan 25, 2023 |
| Gigabyte      | B450M DS3H V2               | [90d383c54e](https://linux-hardware.org/?probe=90d383c54e) | Jan 25, 2023 |
| ASUSTek       | H110M-R                     | [e4b50b33a2](https://linux-hardware.org/?probe=e4b50b33a2) | Jan 25, 2023 |
| MSI           | H110M PRO-VD                | [e0eefbde94](https://linux-hardware.org/?probe=e0eefbde94) | Jan 25, 2023 |
| Gigabyte      | B450M DS3H-CF               | [e2d354b9c5](https://linux-hardware.org/?probe=e2d354b9c5) | Jan 25, 2023 |
| Dell          | 0K3CM7 A00                  | [d3cc219bf7](https://linux-hardware.org/?probe=d3cc219bf7) | Jan 24, 2023 |
| MSI           | H97 PC Mate                 | [d00ec3c042](https://linux-hardware.org/?probe=d00ec3c042) | Jan 24, 2023 |
| ECS           | G31T-M9                     | [59747c81ca](https://linux-hardware.org/?probe=59747c81ca) | Jan 24, 2023 |
| HP            | 82B4                        | [29e2d03c1a](https://linux-hardware.org/?probe=29e2d03c1a) | Jan 24, 2023 |
| HP            | 82B4                        | [3df98736a1](https://linux-hardware.org/?probe=3df98736a1) | Jan 24, 2023 |
| ASRock        | 990FX Killer                | [b6bd3a3bdb](https://linux-hardware.org/?probe=b6bd3a3bdb) | Jan 23, 2023 |
| MSI           | 870A-G54                    | [b1baf04990](https://linux-hardware.org/?probe=b1baf04990) | Jan 23, 2023 |
| Dell          | 09M8Y8 A01                  | [3f3b6c888d](https://linux-hardware.org/?probe=3f3b6c888d) | Jan 23, 2023 |
| Gigabyte      | P85-D3                      | [69164f2a61](https://linux-hardware.org/?probe=69164f2a61) | Jan 23, 2023 |
| ASUSTek       | PRIME X399-A                | [4687e8d062](https://linux-hardware.org/?probe=4687e8d062) | Jan 22, 2023 |
| Intel         | JSL MRD                     | [39dc5a7f96](https://linux-hardware.org/?probe=39dc5a7f96) | Jan 22, 2023 |
| Lenovo        | ThinkCentre M57e 7066W57    | [3ddcdbb616](https://linux-hardware.org/?probe=3ddcdbb616) | Jan 22, 2023 |
| MSI           | B350 TOMAHAWK               | [91ef58d8a0](https://linux-hardware.org/?probe=91ef58d8a0) | Jan 22, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [0c65146f4c](https://linux-hardware.org/?probe=0c65146f4c) | Jan 21, 2023 |
| Dell          | 0KRC95 A02                  | [ef532b60e6](https://linux-hardware.org/?probe=ef532b60e6) | Jan 21, 2023 |
| Biostar       | H310MHP                     | [21de314a44](https://linux-hardware.org/?probe=21de314a44) | Jan 21, 2023 |
| ASUSTek       | H170I-PLUS D3               | [b8d373b07e](https://linux-hardware.org/?probe=b8d373b07e) | Jan 21, 2023 |
| ASRock        | H61M-VG3                    | [c9d6e1cbb1](https://linux-hardware.org/?probe=c9d6e1cbb1) | Jan 21, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [046504c970](https://linux-hardware.org/?probe=046504c970) | Jan 21, 2023 |
| DFI           | CR101-CST                   | [604ce5b10f](https://linux-hardware.org/?probe=604ce5b10f) | Jan 21, 2023 |
| ASUSTek       | P5QL PRO                    | [9f700f7e19](https://linux-hardware.org/?probe=9f700f7e19) | Jan 21, 2023 |
| Intel         | DH77EB AAG39073-304         | [4af2ea2f7f](https://linux-hardware.org/?probe=4af2ea2f7f) | Jan 20, 2023 |
| Dell          | 0VC8RJ X02                  | [313ea92e9c](https://linux-hardware.org/?probe=313ea92e9c) | Jan 20, 2023 |
| Gigabyte      | H410M H V2                  | [5767b63675](https://linux-hardware.org/?probe=5767b63675) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | [28e6aeb27a](https://linux-hardware.org/?probe=28e6aeb27a) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | [beec5d3864](https://linux-hardware.org/?probe=beec5d3864) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | [6ff84d12be](https://linux-hardware.org/?probe=6ff84d12be) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | [002a38370c](https://linux-hardware.org/?probe=002a38370c) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | [bbfb85788c](https://linux-hardware.org/?probe=bbfb85788c) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | [9d6c73b1c1](https://linux-hardware.org/?probe=9d6c73b1c1) | Jan 20, 2023 |
| HP            | 3397                        | [39391f23c4](https://linux-hardware.org/?probe=39391f23c4) | Jan 20, 2023 |
| HP            | 3397                        | [7b05c1fdf9](https://linux-hardware.org/?probe=7b05c1fdf9) | Jan 20, 2023 |
| AZW           | SEi                         | [257b104c3a](https://linux-hardware.org/?probe=257b104c3a) | Jan 20, 2023 |
| Gigabyte      | Z690I A ULTRA LITE D4       | [f7cac38f4a](https://linux-hardware.org/?probe=f7cac38f4a) | Jan 20, 2023 |
| AZW           | SEi                         | [481932390b](https://linux-hardware.org/?probe=481932390b) | Jan 20, 2023 |
| ASUSTek       | P5KPL-CM                    | [b9f1f115ba](https://linux-hardware.org/?probe=b9f1f115ba) | Jan 20, 2023 |
| Gigabyte      | Z690I A ULTRA LITE D4       | [abcfca9ea7](https://linux-hardware.org/?probe=abcfca9ea7) | Jan 20, 2023 |
| Lenovo        | 7033EW4                     | [fd4303de2e](https://linux-hardware.org/?probe=fd4303de2e) | Jan 20, 2023 |
| Gigabyte      | H81M-S2V                    | [76be7bde5d](https://linux-hardware.org/?probe=76be7bde5d) | Jan 19, 2023 |
| ASUSTek       | P6T                         | [ac42d5a147](https://linux-hardware.org/?probe=ac42d5a147) | Jan 19, 2023 |
| Gigabyte      | B85M-D3V                    | [285dc35475](https://linux-hardware.org/?probe=285dc35475) | Jan 19, 2023 |
| ASUSTek       | P5AD2-E-Premium             | [285c0f23f1](https://linux-hardware.org/?probe=285c0f23f1) | Jan 19, 2023 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | [e3d0558aee](https://linux-hardware.org/?probe=e3d0558aee) | Jan 19, 2023 |
| ASUSTek       | P8H61-M                     | [1ffe9344ff](https://linux-hardware.org/?probe=1ffe9344ff) | Jan 18, 2023 |
| Medion        | TJ4125                      | [b4f48c3140](https://linux-hardware.org/?probe=b4f48c3140) | Jan 18, 2023 |
| Lenovo        | 7033EW4                     | [df0d8cd728](https://linux-hardware.org/?probe=df0d8cd728) | Jan 18, 2023 |
| ASRock        | A300M-STX                   | [4d726dcf9b](https://linux-hardware.org/?probe=4d726dcf9b) | Jan 17, 2023 |
| Huanan        | B75 V10.1 376               | [2703c87348](https://linux-hardware.org/?probe=2703c87348) | Jan 17, 2023 |
| ASUSTek       | PRIME H510M-K               | [f9f926e910](https://linux-hardware.org/?probe=f9f926e910) | Jan 17, 2023 |
| MSI           | H81M-E34                    | [db4a6791a0](https://linux-hardware.org/?probe=db4a6791a0) | Jan 17, 2023 |
| ASUSTek       | P5G41T-M LE                 | [31b369770d](https://linux-hardware.org/?probe=31b369770d) | Jan 17, 2023 |
| Foxconn       | nT-A3000 series FAB         | [0bdefb0a4f](https://linux-hardware.org/?probe=0bdefb0a4f) | Jan 17, 2023 |
| ASUSTek       | M2N-SLI DELUXE              | [d31aea19b2](https://linux-hardware.org/?probe=d31aea19b2) | Jan 16, 2023 |
| Intel         | DH67BL AAG10189-206         | [23e07704eb](https://linux-hardware.org/?probe=23e07704eb) | Jan 16, 2023 |
| ASRock        | J3455-ITX                   | [6746dfae39](https://linux-hardware.org/?probe=6746dfae39) | Jan 16, 2023 |
| Intel         | JSL MRD                     | [edbaf7bb5d](https://linux-hardware.org/?probe=edbaf7bb5d) | Jan 16, 2023 |
| Lenovo        | 370A SDK0J40697 WIN 3305... | [deb2b560bc](https://linux-hardware.org/?probe=deb2b560bc) | Jan 16, 2023 |
| ASRock        | J3455-ITX                   | [457c7ea5a4](https://linux-hardware.org/?probe=457c7ea5a4) | Jan 16, 2023 |
| Intel         | DH77EB AAG39073-304         | [cb3c4b1eb4](https://linux-hardware.org/?probe=cb3c4b1eb4) | Jan 16, 2023 |
| HP            | 8643 SMVB                   | [4572999070](https://linux-hardware.org/?probe=4572999070) | Jan 16, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [3b4a530695](https://linux-hardware.org/?probe=3b4a530695) | Jan 15, 2023 |
| MSI           | MS-B1711                    | [730b1e7f90](https://linux-hardware.org/?probe=730b1e7f90) | Jan 15, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [202535bce7](https://linux-hardware.org/?probe=202535bce7) | Jan 15, 2023 |
| ASUSTek       | PRIME X570-P                | [ab5933911d](https://linux-hardware.org/?probe=ab5933911d) | Jan 15, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [d1e2f08907](https://linux-hardware.org/?probe=d1e2f08907) | Jan 14, 2023 |
| HP            | ProLiant MicroServer Gen... | [8a79dd9e27](https://linux-hardware.org/?probe=8a79dd9e27) | Jan 13, 2023 |
| ASRock        | H110M-HDV R3.0              | [bed628ce8a](https://linux-hardware.org/?probe=bed628ce8a) | Jan 13, 2023 |
| Lenovo        | ThinkCentre M58p 6234A1U    | [63d74a9021](https://linux-hardware.org/?probe=63d74a9021) | Jan 13, 2023 |
| MSI           | PRO X670-P WIFI             | [8cffa1360f](https://linux-hardware.org/?probe=8cffa1360f) | Jan 13, 2023 |
| ASRock        | 970M Pro3                   | [ed62a9383e](https://linux-hardware.org/?probe=ed62a9383e) | Jan 13, 2023 |
| Medion        | TJ4125                      | [700f862aa6](https://linux-hardware.org/?probe=700f862aa6) | Jan 13, 2023 |
| HC            | HCAR357-MI V1.0             | [516f1ed052](https://linux-hardware.org/?probe=516f1ed052) | Jan 13, 2023 |
| Vestel        | 14MB24A                     | [56ee8713e8](https://linux-hardware.org/?probe=56ee8713e8) | Jan 13, 2023 |
| Vestel        | 14MB24A                     | [02c99c8c38](https://linux-hardware.org/?probe=02c99c8c38) | Jan 13, 2023 |
| ASUSTek       | PRIME Z790-P                | [a4fb531cc9](https://linux-hardware.org/?probe=a4fb531cc9) | Jan 13, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [d7c612580f](https://linux-hardware.org/?probe=d7c612580f) | Jan 13, 2023 |
| AZW           | Green G3                    | [be99013601](https://linux-hardware.org/?probe=be99013601) | Jan 13, 2023 |
| HP            | 21EF                        | [0d5e3a9354](https://linux-hardware.org/?probe=0d5e3a9354) | Jan 12, 2023 |
| HP            | 21EF                        | [cdeab03273](https://linux-hardware.org/?probe=cdeab03273) | Jan 12, 2023 |
| ASUSTek       | P5G41T-M LX V2              | [36a8e226c5](https://linux-hardware.org/?probe=36a8e226c5) | Jan 12, 2023 |
| ASUSTek       | PRIME Z690M-PLUS D4         | [4687ae7d43](https://linux-hardware.org/?probe=4687ae7d43) | Jan 12, 2023 |
| Gigabyte      | X570 GAMING X               | [bb85f0bdc7](https://linux-hardware.org/?probe=bb85f0bdc7) | Jan 12, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d93218978e](https://linux-hardware.org/?probe=d93218978e) | Jan 12, 2023 |
| MSI           | B350 PC MATE                | [f235ff785b](https://linux-hardware.org/?probe=f235ff785b) | Jan 12, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [25bd789598](https://linux-hardware.org/?probe=25bd789598) | Jan 12, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [c040acffcf](https://linux-hardware.org/?probe=c040acffcf) | Jan 12, 2023 |
| MSI           | X470 GAMING PLUS            | [ba153350d8](https://linux-hardware.org/?probe=ba153350d8) | Jan 11, 2023 |
| ASRock        | X300-ITX                    | [9e74676ba4](https://linux-hardware.org/?probe=9e74676ba4) | Jan 11, 2023 |
| ASRockRack    | X470D4U                     | [b60a38ae60](https://linux-hardware.org/?probe=b60a38ae60) | Jan 11, 2023 |
| Gigabyte      | X570 GAMING X               | [204a5e8a8e](https://linux-hardware.org/?probe=204a5e8a8e) | Jan 11, 2023 |
| ASRockRack    | X470D4U2/1N1                | [ee2147214c](https://linux-hardware.org/?probe=ee2147214c) | Jan 11, 2023 |
| Dell          | 01XK1W A00                  | [54793acf7e](https://linux-hardware.org/?probe=54793acf7e) | Jan 11, 2023 |
| Medion        | TJ4125                      | [a82000e2e9](https://linux-hardware.org/?probe=a82000e2e9) | Jan 10, 2023 |
| Gigabyte      | H510M H                     | [81a8002b99](https://linux-hardware.org/?probe=81a8002b99) | Jan 10, 2023 |
| Gigabyte      | H61M-DS2                    | [69ceed18f7](https://linux-hardware.org/?probe=69ceed18f7) | Jan 10, 2023 |
| Gigabyte      | H510M H                     | [286d590fda](https://linux-hardware.org/?probe=286d590fda) | Jan 10, 2023 |
| Lenovo        | 1059 SDK0T76538 WIN 3556... | [a2660dcbfb](https://linux-hardware.org/?probe=a2660dcbfb) | Jan 09, 2023 |
| ASUSTek       | M2N-E                       | [2a7342c2cb](https://linux-hardware.org/?probe=2a7342c2cb) | Jan 09, 2023 |
| ASUSTek       | P8H61-MX R2.0               | [d5c81ffaec](https://linux-hardware.org/?probe=d5c81ffaec) | Jan 09, 2023 |
| Techvision    | TVI7309X B0                 | [e336a260d6](https://linux-hardware.org/?probe=e336a260d6) | Jan 09, 2023 |
| Techvision    | TVI7309X B0                 | [43cc06ef1d](https://linux-hardware.org/?probe=43cc06ef1d) | Jan 09, 2023 |
| ASRockRack    | X470D4U                     | [0e51eb7caa](https://linux-hardware.org/?probe=0e51eb7caa) | Jan 09, 2023 |
| Dell          | 0HD5W2 A01                  | [a14e62fdf8](https://linux-hardware.org/?probe=a14e62fdf8) | Jan 09, 2023 |
| Acer          | Predator G3-710             | [d47ca88192](https://linux-hardware.org/?probe=d47ca88192) | Jan 09, 2023 |
| HP            | 8053                        | [b377deb121](https://linux-hardware.org/?probe=b377deb121) | Jan 09, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [92205d303f](https://linux-hardware.org/?probe=92205d303f) | Jan 08, 2023 |
| Gigabyte      | B365M DS3H                  | [0e302b3507](https://linux-hardware.org/?probe=0e302b3507) | Jan 08, 2023 |
| Gigabyte      | X570S I AORUS PRO AX        | [2b8206db29](https://linux-hardware.org/?probe=2b8206db29) | Jan 08, 2023 |
| Gigabyte      | X570S I AORUS PRO AX        | [68fe02a04c](https://linux-hardware.org/?probe=68fe02a04c) | Jan 08, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [0f0b86d738](https://linux-hardware.org/?probe=0f0b86d738) | Jan 07, 2023 |
| ASRock        | Q1900-ITX                   | [ac7df499e8](https://linux-hardware.org/?probe=ac7df499e8) | Jan 07, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [4ceeb719c2](https://linux-hardware.org/?probe=4ceeb719c2) | Jan 06, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [d930da3de0](https://linux-hardware.org/?probe=d930da3de0) | Jan 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [1608711aa0](https://linux-hardware.org/?probe=1608711aa0) | Jan 06, 2023 |
| MSI           | Z97 GAMING 5                | [1edff66d1a](https://linux-hardware.org/?probe=1edff66d1a) | Jan 06, 2023 |
| ASUSTek       | M5A97 R2.0                  | [982de9c98d](https://linux-hardware.org/?probe=982de9c98d) | Jan 06, 2023 |
| Dell          | 01XK1W A00                  | [bb487db79f](https://linux-hardware.org/?probe=bb487db79f) | Jan 05, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [b063be9f2e](https://linux-hardware.org/?probe=b063be9f2e) | Jan 04, 2023 |
| ASUSTek       | PRIME B650M-A AX            | [872a58377f](https://linux-hardware.org/?probe=872a58377f) | Jan 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [8f519746c2](https://linux-hardware.org/?probe=8f519746c2) | Jan 04, 2023 |
| ELSKY         | M219FN-6C                   | [95862529f8](https://linux-hardware.org/?probe=95862529f8) | Jan 04, 2023 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | [b1771ee07c](https://linux-hardware.org/?probe=b1771ee07c) | Jan 03, 2023 |
| MSI           | MS-7519                     | [3239304aa0](https://linux-hardware.org/?probe=3239304aa0) | Jan 03, 2023 |
| Pegatron      | Maureen                     | [071cde04e9](https://linux-hardware.org/?probe=071cde04e9) | Jan 03, 2023 |
| ASUSTek       | Z170-DELUXE                 | [4a37b87ecf](https://linux-hardware.org/?probe=4a37b87ecf) | Jan 02, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [c96c7d74fe](https://linux-hardware.org/?probe=c96c7d74fe) | Jan 02, 2023 |
| Gigabyte      | AX370-Gaming K5-CF          | [8b0b477726](https://linux-hardware.org/?probe=8b0b477726) | Jan 02, 2023 |
| Lenovo        | SHARKBAY NOK                | [7c72451666](https://linux-hardware.org/?probe=7c72451666) | Jan 01, 2023 |
| MSI           | B450M-A PRO MAX             | [8726e38f02](https://linux-hardware.org/?probe=8726e38f02) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [b1dc879a16](https://linux-hardware.org/?probe=b1dc879a16) | Jan 01, 2023 |
| ASUSTek       | TUF Z390-PRO GAMING         | [de65f4b654](https://linux-hardware.org/?probe=de65f4b654) | Dec 31, 2022 |
| Google        | Teemo                       | [6f6671a40e](https://linux-hardware.org/?probe=6f6671a40e) | Dec 31, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [500ce7ae28](https://linux-hardware.org/?probe=500ce7ae28) | Dec 31, 2022 |
| Google        | Teemo                       | [e3c39f29da](https://linux-hardware.org/?probe=e3c39f29da) | Dec 31, 2022 |
| ASRock        | A320M-DGS                   | [a9df519d4f](https://linux-hardware.org/?probe=a9df519d4f) | Dec 31, 2022 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [b1220a23ad](https://linux-hardware.org/?probe=b1220a23ad) | Dec 31, 2022 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [31343e35f0](https://linux-hardware.org/?probe=31343e35f0) | Dec 31, 2022 |
| Gigabyte      | H61M-DS2                    | [dff8a56537](https://linux-hardware.org/?probe=dff8a56537) | Dec 30, 2022 |
| ASRock        | J3455-ITX                   | [4f45d532ac](https://linux-hardware.org/?probe=4f45d532ac) | Dec 30, 2022 |
| Gigabyte      | H61M-DS2                    | [4ea88219d8](https://linux-hardware.org/?probe=4ea88219d8) | Dec 30, 2022 |
| Lenovo        | ThinkStation C20 4263BA7    | [7b55955e2a](https://linux-hardware.org/?probe=7b55955e2a) | Dec 30, 2022 |
| HP            | 339A                        | [8e0b785427](https://linux-hardware.org/?probe=8e0b785427) | Dec 29, 2022 |
| ASUSTek       | PRIME B360M-C               | [c38ca6386e](https://linux-hardware.org/?probe=c38ca6386e) | Dec 29, 2022 |
| Gigabyte      | H61M-DS2                    | [50149bf9e3](https://linux-hardware.org/?probe=50149bf9e3) | Dec 29, 2022 |
| Gigabyte      | H61M-DS2                    | [b0a40a3ac0](https://linux-hardware.org/?probe=b0a40a3ac0) | Dec 29, 2022 |
| Unknown       | Unknown                     | [34b6109940](https://linux-hardware.org/?probe=34b6109940) | Dec 29, 2022 |
| ASRock        | X570 Taichi                 | [c1e5e82fbb](https://linux-hardware.org/?probe=c1e5e82fbb) | Dec 29, 2022 |
| HP            | ProLiant ML30 Gen9          | [174e7e831b](https://linux-hardware.org/?probe=174e7e831b) | Dec 28, 2022 |
| ASUSTek       | PRIME B450M-A               | [422238387a](https://linux-hardware.org/?probe=422238387a) | Dec 28, 2022 |
| HP            | 158A                        | [c80bfd7c30](https://linux-hardware.org/?probe=c80bfd7c30) | Dec 28, 2022 |
| ASRock        | X470 Gaming-ITX/ac          | [c4d1d971d1](https://linux-hardware.org/?probe=c4d1d971d1) | Dec 28, 2022 |
| Lenovo        | 0B98401 WIN                 | [0f71bbaf67](https://linux-hardware.org/?probe=0f71bbaf67) | Dec 28, 2022 |
| ASRock        | J3455-ITX                   | [6e628aeb01](https://linux-hardware.org/?probe=6e628aeb01) | Dec 28, 2022 |
| ASUSTek       | PRIME B360M-K               | [48f161dfc8](https://linux-hardware.org/?probe=48f161dfc8) | Dec 27, 2022 |
| Dell          | 0M017G A00                  | [5c41315695](https://linux-hardware.org/?probe=5c41315695) | Dec 27, 2022 |
| ASRock        | H470M-HVS                   | [210f0c0375](https://linux-hardware.org/?probe=210f0c0375) | Dec 27, 2022 |
| Gigabyte      | 990FXA-UD3 R5               | [734c3742b1](https://linux-hardware.org/?probe=734c3742b1) | Dec 27, 2022 |
| Gigabyte      | 990FXA-UD3 R5               | [bb6dddc780](https://linux-hardware.org/?probe=bb6dddc780) | Dec 27, 2022 |
| ASRock        | Brazos                      | [f5183b395b](https://linux-hardware.org/?probe=f5183b395b) | Dec 27, 2022 |
| Dell          | 02YRK5 A02                  | [56dc5ff1b9](https://linux-hardware.org/?probe=56dc5ff1b9) | Dec 26, 2022 |
| Gigabyte      | B660M GAMING DDR4           | [2618b85414](https://linux-hardware.org/?probe=2618b85414) | Dec 26, 2022 |
| Lenovo        | ThinkStation D30 42234T7    | [6ad649ad46](https://linux-hardware.org/?probe=6ad649ad46) | Dec 26, 2022 |
| Gigabyte      | B360M H                     | [2f0d1b1c8d](https://linux-hardware.org/?probe=2f0d1b1c8d) | Dec 26, 2022 |
| ASUSTek       | PRIME A320M-K               | [d90a9cdcd3](https://linux-hardware.org/?probe=d90a9cdcd3) | Dec 26, 2022 |
| ASUSTek       | PRIME A320M-K               | [fc0eac877c](https://linux-hardware.org/?probe=fc0eac877c) | Dec 26, 2022 |
| ASUSTek       | M3A32-MVP DELUXE            | [0fa5809533](https://linux-hardware.org/?probe=0fa5809533) | Dec 26, 2022 |
| Matrox Ele... | 4GPMOBIL 7449-03-0          | [c02a37a124](https://linux-hardware.org/?probe=c02a37a124) | Dec 26, 2022 |
| Lenovo        | ThinkStation D30 42234T7    | [6ac63aca4f](https://linux-hardware.org/?probe=6ac63aca4f) | Dec 25, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [8855d29d69](https://linux-hardware.org/?probe=8855d29d69) | Dec 25, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | [4d19273307](https://linux-hardware.org/?probe=4d19273307) | Dec 24, 2022 |
| HP            | ProLiant MicroServer        | [b95892f2dc](https://linux-hardware.org/?probe=b95892f2dc) | Dec 24, 2022 |
| ASUSTek       | WS C422 DC                  | [7be7c81575](https://linux-hardware.org/?probe=7be7c81575) | Dec 24, 2022 |
| ASUSTek       | WS C422 DC                  | [526414fd8f](https://linux-hardware.org/?probe=526414fd8f) | Dec 24, 2022 |
| ASRock        | B450 Pro4                   | [70ff83271a](https://linux-hardware.org/?probe=70ff83271a) | Dec 24, 2022 |
| HP            | 876C SMVB                   | [988b03aae5](https://linux-hardware.org/?probe=988b03aae5) | Dec 23, 2022 |
| MSI           | B550-A PRO                  | [a54a0884ce](https://linux-hardware.org/?probe=a54a0884ce) | Dec 23, 2022 |
| ASRock        | X300M-STX                   | [3d90b10b72](https://linux-hardware.org/?probe=3d90b10b72) | Dec 22, 2022 |
| Gigabyte      | B450M DS3H-CF               | [fe4ef75450](https://linux-hardware.org/?probe=fe4ef75450) | Dec 21, 2022 |
| HP            | ProLiant MicroServer Gen... | [57182d09ed](https://linux-hardware.org/?probe=57182d09ed) | Dec 21, 2022 |
| Intel         | DQ77CP AAG67261-300         | [908f619aa7](https://linux-hardware.org/?probe=908f619aa7) | Dec 21, 2022 |
| Gigabyte      | M68MT-S2P                   | [363c106fa2](https://linux-hardware.org/?probe=363c106fa2) | Dec 21, 2022 |
| Gigabyte      | M68MT-S2P                   | [ed29442d39](https://linux-hardware.org/?probe=ed29442d39) | Dec 21, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [c4719bd0ac](https://linux-hardware.org/?probe=c4719bd0ac) | Dec 21, 2022 |
| MSI           | MS-7318                     | [4622016059](https://linux-hardware.org/?probe=4622016059) | Dec 21, 2022 |
| Gigabyte      | B450M DS3H-CF               | [827c7f9bd3](https://linux-hardware.org/?probe=827c7f9bd3) | Dec 21, 2022 |
| Intel         | DG35EC AAE29266-205         | [3cee3ad865](https://linux-hardware.org/?probe=3cee3ad865) | Dec 20, 2022 |
| Dell          | 0MN1TX A00                  | [f2ae430663](https://linux-hardware.org/?probe=f2ae430663) | Dec 20, 2022 |
| Gigabyte      | P75-D3P                     | [ff2420e759](https://linux-hardware.org/?probe=ff2420e759) | Dec 19, 2022 |
| Dell          | 09KPNV A01                  | [a4c5e58eec](https://linux-hardware.org/?probe=a4c5e58eec) | Dec 19, 2022 |
| ASRock        | B550M Pro4                  | [6bfb0295df](https://linux-hardware.org/?probe=6bfb0295df) | Dec 19, 2022 |
| ASRock        | N68-GS3 UCC                 | [19dad9b5b2](https://linux-hardware.org/?probe=19dad9b5b2) | Dec 19, 2022 |
| Gigabyte      | G41MT-ES2L                  | [d23b58b5da](https://linux-hardware.org/?probe=d23b58b5da) | Dec 19, 2022 |
| MSI           | A320M-A PRO MAX             | [30aec905c0](https://linux-hardware.org/?probe=30aec905c0) | Dec 19, 2022 |
| GIFA Indus... | TM-J3355-2G2L               | [526697a9d0](https://linux-hardware.org/?probe=526697a9d0) | Dec 19, 2022 |
| Apple         | Mac-F221BEC8                | [493ddb6998](https://linux-hardware.org/?probe=493ddb6998) | Dec 19, 2022 |
| IceWhale T... | ZimaBoard 216 ZMB           | [647bf0e2a7](https://linux-hardware.org/?probe=647bf0e2a7) | Dec 19, 2022 |
| Dell          | 0UY894 A02                  | [904ee2bb12](https://linux-hardware.org/?probe=904ee2bb12) | Dec 18, 2022 |
| Dell          | 06JWJY A00                  | [89ac693c2c](https://linux-hardware.org/?probe=89ac693c2c) | Dec 18, 2022 |
| ASUSTek       | M51BC                       | [78a6f49d22](https://linux-hardware.org/?probe=78a6f49d22) | Dec 18, 2022 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | [0886e650a3](https://linux-hardware.org/?probe=0886e650a3) | Dec 18, 2022 |
| Gigabyte      | X570S AERO G                | [1ec932aa3a](https://linux-hardware.org/?probe=1ec932aa3a) | Dec 17, 2022 |
| ASUSTek       | P8H67-M                     | [cf6fc033d6](https://linux-hardware.org/?probe=cf6fc033d6) | Dec 17, 2022 |
| Dell          | 0V8F20 A01                  | [d9e3649f12](https://linux-hardware.org/?probe=d9e3649f12) | Dec 16, 2022 |
| ASUSTek       | PRIME B560M-A               | [abfa3437b3](https://linux-hardware.org/?probe=abfa3437b3) | Dec 16, 2022 |
| Gigabyte      | B550M DS3H                  | [7b3f9b5af0](https://linux-hardware.org/?probe=7b3f9b5af0) | Dec 16, 2022 |
| Dell          | 0M5DCD A00                  | [f58cc5bcba](https://linux-hardware.org/?probe=f58cc5bcba) | Dec 16, 2022 |
| ASUSTek       | PRIME B560M-A               | [f43049fe6d](https://linux-hardware.org/?probe=f43049fe6d) | Dec 16, 2022 |
| HP            | 876C SMVB                   | [e214378eea](https://linux-hardware.org/?probe=e214378eea) | Dec 16, 2022 |
| ASUSTek       | Z170-DELUXE                 | [3a524796f6](https://linux-hardware.org/?probe=3a524796f6) | Dec 16, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [138cbfa0ba](https://linux-hardware.org/?probe=138cbfa0ba) | Dec 16, 2022 |
| MSI           | AM1I                        | [0ebd00e848](https://linux-hardware.org/?probe=0ebd00e848) | Dec 16, 2022 |
| MSI           | AM1I                        | [97dfa5ebf8](https://linux-hardware.org/?probe=97dfa5ebf8) | Dec 16, 2022 |
| ASRock        | X570 Pro4                   | [713a2bcaf4](https://linux-hardware.org/?probe=713a2bcaf4) | Dec 15, 2022 |
| HP            | 876C SMVB                   | [c704265799](https://linux-hardware.org/?probe=c704265799) | Dec 15, 2022 |
| HP            | 876C SMVB                   | [3a6fdcc184](https://linux-hardware.org/?probe=3a6fdcc184) | Dec 15, 2022 |
| ASRock        | H470M-HVS                   | [3c6c7c5eb5](https://linux-hardware.org/?probe=3c6c7c5eb5) | Dec 15, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [4651fa0db3](https://linux-hardware.org/?probe=4651fa0db3) | Dec 14, 2022 |
| ASRockRack    | X470D4U2-2T                 | [47c18717db](https://linux-hardware.org/?probe=47c18717db) | Dec 14, 2022 |
| ASRock        | B550M Steel Legend          | [516d6f7f12](https://linux-hardware.org/?probe=516d6f7f12) | Dec 14, 2022 |
| Dell          | 0N185P A02                  | [32d47ba775](https://linux-hardware.org/?probe=32d47ba775) | Dec 14, 2022 |
| Dell          | 0N185P A02                  | [ee28e5efa8](https://linux-hardware.org/?probe=ee28e5efa8) | Dec 14, 2022 |
| Gigabyte      | GA-MA785GMT-UD2H            | [9e8ad3aefd](https://linux-hardware.org/?probe=9e8ad3aefd) | Dec 14, 2022 |
| Dell          | 0H8367                      | [7fff4bfffc](https://linux-hardware.org/?probe=7fff4bfffc) | Dec 14, 2022 |
| Gigabyte      | GA-MA785GMT-UD2H            | [bdbf3d8792](https://linux-hardware.org/?probe=bdbf3d8792) | Dec 14, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [049fef0294](https://linux-hardware.org/?probe=049fef0294) | Dec 14, 2022 |
| Pro-B         | INSYS                       | [40650eefcc](https://linux-hardware.org/?probe=40650eefcc) | Dec 14, 2022 |
| Gigabyte      | Z87M-D3H                    | [88c6ca8956](https://linux-hardware.org/?probe=88c6ca8956) | Dec 14, 2022 |
| MSI           | MS-7318                     | [420ae8857b](https://linux-hardware.org/?probe=420ae8857b) | Dec 13, 2022 |
| ASUSTek       | A88XM-A                     | [64176404e2](https://linux-hardware.org/?probe=64176404e2) | Dec 13, 2022 |
| MSI           | MS-B1591                    | [33cb107fb9](https://linux-hardware.org/?probe=33cb107fb9) | Dec 13, 2022 |
| ASUSTek       | P7H55-M SI                  | [973e367765](https://linux-hardware.org/?probe=973e367765) | Dec 13, 2022 |
| AZW           | SEi                         | [1ae245a379](https://linux-hardware.org/?probe=1ae245a379) | Dec 13, 2022 |
| AZW           | SEi                         | [18219c432d](https://linux-hardware.org/?probe=18219c432d) | Dec 13, 2022 |
| NetGear       | ReadyDATA 5200              | [2db45cfb13](https://linux-hardware.org/?probe=2db45cfb13) | Dec 13, 2022 |
| Fujitsu       | D3417-B1 S26361-D3417-B1    | [fd77b80943](https://linux-hardware.org/?probe=fd77b80943) | Dec 12, 2022 |
| ASUSTek       | STRIX H270F GAMING          | [3b9b8bb589](https://linux-hardware.org/?probe=3b9b8bb589) | Dec 12, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [d1b0bc1c03](https://linux-hardware.org/?probe=d1b0bc1c03) | Dec 12, 2022 |
| HP            | 1850                        | [af4f26481a](https://linux-hardware.org/?probe=af4f26481a) | Dec 11, 2022 |
| HP            | 1850                        | [28b194e897](https://linux-hardware.org/?probe=28b194e897) | Dec 11, 2022 |
| Gigabyte      | A320M-H-CF                  | [7d4b5e1c20](https://linux-hardware.org/?probe=7d4b5e1c20) | Dec 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [822e79aa3e](https://linux-hardware.org/?probe=822e79aa3e) | Dec 11, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [e3cecbe4be](https://linux-hardware.org/?probe=e3cecbe4be) | Dec 11, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [32e7431c24](https://linux-hardware.org/?probe=32e7431c24) | Dec 11, 2022 |
| Supermicro    | C7SIM-Q                     | [76cf2b62db](https://linux-hardware.org/?probe=76cf2b62db) | Dec 11, 2022 |
| ASRock        | X370 Killer SLI/ac          | [83fc85f9e5](https://linux-hardware.org/?probe=83fc85f9e5) | Dec 10, 2022 |
| Dell          | 0VHWTR A02                  | [b489057ccc](https://linux-hardware.org/?probe=b489057ccc) | Dec 10, 2022 |
| HP            | 1998                        | [b5e04c4f4c](https://linux-hardware.org/?probe=b5e04c4f4c) | Dec 10, 2022 |
| HP            | 876C SMVB                   | [d6211ccceb](https://linux-hardware.org/?probe=d6211ccceb) | Dec 10, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [9a14eb6994](https://linux-hardware.org/?probe=9a14eb6994) | Dec 10, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [7c41dddf3f](https://linux-hardware.org/?probe=7c41dddf3f) | Dec 10, 2022 |
| HP            | 339A                        | [ca1d494630](https://linux-hardware.org/?probe=ca1d494630) | Dec 10, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [a80714c4ec](https://linux-hardware.org/?probe=a80714c4ec) | Dec 09, 2022 |
| ASRock        | X570 Pro4                   | [347fc5c7ec](https://linux-hardware.org/?probe=347fc5c7ec) | Dec 09, 2022 |
| Gigabyte      | B450 AORUS M                | [bb3d3b636f](https://linux-hardware.org/?probe=bb3d3b636f) | Dec 09, 2022 |
| Gigabyte      | 990FXA-UD3                  | [b2aa17a680](https://linux-hardware.org/?probe=b2aa17a680) | Dec 09, 2022 |
| Gigabyte      | 990FXA-UD3                  | [416ad70d66](https://linux-hardware.org/?probe=416ad70d66) | Dec 08, 2022 |
| Acer          | Veriton N2620G              | [2c4bd5a093](https://linux-hardware.org/?probe=2c4bd5a093) | Dec 08, 2022 |
| Dell          | 0VHWTR A02                  | [5b85a90055](https://linux-hardware.org/?probe=5b85a90055) | Dec 08, 2022 |
| ASRock        | H470M-HVS                   | [2f4b3b1185](https://linux-hardware.org/?probe=2f4b3b1185) | Dec 08, 2022 |
| Unknown       | Unknown                     | [3a5aa82738](https://linux-hardware.org/?probe=3a5aa82738) | Dec 07, 2022 |
| Dell          | 0RM5DR A00                  | [cd67b584bb](https://linux-hardware.org/?probe=cd67b584bb) | Dec 07, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [611fd80398](https://linux-hardware.org/?probe=611fd80398) | Dec 07, 2022 |
| Unknown       | Unknown                     | [4d8d2c3a47](https://linux-hardware.org/?probe=4d8d2c3a47) | Dec 07, 2022 |
| ASUSTek       | STRIX Z270F GAMING          | [7766e8d043](https://linux-hardware.org/?probe=7766e8d043) | Dec 07, 2022 |
| MSI           | B550-A PRO                  | [eb1b8bc98a](https://linux-hardware.org/?probe=eb1b8bc98a) | Dec 06, 2022 |
| ASUSTek       | PRIME B450M-K II            | [2a7f909902](https://linux-hardware.org/?probe=2a7f909902) | Dec 06, 2022 |
| ASRock        | B75M R2.0                   | [93dc9d7b3e](https://linux-hardware.org/?probe=93dc9d7b3e) | Dec 06, 2022 |
| Dell          | 0XHGV1 A00                  | [9b9778c525](https://linux-hardware.org/?probe=9b9778c525) | Dec 06, 2022 |
| ASUSTek       | P5K                         | [8e3fef0d6b](https://linux-hardware.org/?probe=8e3fef0d6b) | Dec 06, 2022 |
| ASUSTek       | CM1530                      | [3990cff263](https://linux-hardware.org/?probe=3990cff263) | Dec 06, 2022 |
| Dell          | 01XK1W A00                  | [e2ec28bd7c](https://linux-hardware.org/?probe=e2ec28bd7c) | Dec 06, 2022 |
| MSI           | H110M PRO-VD                | [64c80c03cf](https://linux-hardware.org/?probe=64c80c03cf) | Dec 05, 2022 |
| Gigabyte      | Z97-HD3                     | [9b7999b50d](https://linux-hardware.org/?probe=9b7999b50d) | Dec 05, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [b7b2f976e8](https://linux-hardware.org/?probe=b7b2f976e8) | Dec 05, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [4d38cbb41a](https://linux-hardware.org/?probe=4d38cbb41a) | Dec 04, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [7428311d73](https://linux-hardware.org/?probe=7428311d73) | Dec 04, 2022 |
| BESSTAR Te... | HM90                        | [b53efc176f](https://linux-hardware.org/?probe=b53efc176f) | Dec 04, 2022 |
| Dell          | 0K3CM7 A00                  | [9ee4df50e7](https://linux-hardware.org/?probe=9ee4df50e7) | Dec 04, 2022 |
| ASUSTek       | LEUCITE3                    | [4f28bb5933](https://linux-hardware.org/?probe=4f28bb5933) | Dec 04, 2022 |
| HP            | 339A                        | [91ed08d2a9](https://linux-hardware.org/?probe=91ed08d2a9) | Dec 04, 2022 |
| ASUSTek       | PRIME A320M-A               | [91d50f0379](https://linux-hardware.org/?probe=91d50f0379) | Dec 03, 2022 |
| Lenovo        | SHARKBAY NOK                | [c7cf7a1604](https://linux-hardware.org/?probe=c7cf7a1604) | Dec 03, 2022 |
| Lenovo        | SHARKBAY NOK                | [67c278b32e](https://linux-hardware.org/?probe=67c278b32e) | Dec 03, 2022 |
| MSI           | B450M BAZOOKA PLUS          | [dc890ad363](https://linux-hardware.org/?probe=dc890ad363) | Dec 03, 2022 |
| MSI           | B450M BAZOOKA PLUS          | [a087ddb18f](https://linux-hardware.org/?probe=a087ddb18f) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [61e955b5a6](https://linux-hardware.org/?probe=61e955b5a6) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [dc9c0686e7](https://linux-hardware.org/?probe=dc9c0686e7) | Dec 03, 2022 |
| Dell          | 0GY6Y8 A01                  | [f86e02dee0](https://linux-hardware.org/?probe=f86e02dee0) | Dec 03, 2022 |
| ASUSTek       | Z170I PRO GAMING            | [bf8f5e2683](https://linux-hardware.org/?probe=bf8f5e2683) | Dec 03, 2022 |
| Intel         | DP45SG AAE27733-401         | [bc19b3f6a3](https://linux-hardware.org/?probe=bc19b3f6a3) | Dec 02, 2022 |
| Lenovo        | 3753 SDK0T76479 WIN 3423... | [5476b73cb7](https://linux-hardware.org/?probe=5476b73cb7) | Dec 02, 2022 |
| Lenovo        | 3753 SDK0T76479 WIN 3423... | [6d07106192](https://linux-hardware.org/?probe=6d07106192) | Dec 02, 2022 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | [51cf6d10e7](https://linux-hardware.org/?probe=51cf6d10e7) | Dec 01, 2022 |
| Lenovo        | SHARKBAY NOK                | [e03c6b53ed](https://linux-hardware.org/?probe=e03c6b53ed) | Dec 01, 2022 |
| ASUSTek       | P5B                         | [44f13beada](https://linux-hardware.org/?probe=44f13beada) | Dec 01, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [f5a5a30379](https://linux-hardware.org/?probe=f5a5a30379) | Dec 01, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [0f27e558f3](https://linux-hardware.org/?probe=0f27e558f3) | Dec 01, 2022 |
| Gigabyte      | Z390 M GAMING-CF            | [f0dba35258](https://linux-hardware.org/?probe=f0dba35258) | Dec 01, 2022 |
| Gigabyte      | Z390 M GAMING-CF            | [baa969bf8b](https://linux-hardware.org/?probe=baa969bf8b) | Nov 30, 2022 |
| Pegatron      | BYT-X1                      | [edadb85201](https://linux-hardware.org/?probe=edadb85201) | Nov 30, 2022 |
| Pegatron      | BYT-X1                      | [b248df8671](https://linux-hardware.org/?probe=b248df8671) | Nov 30, 2022 |
| ASUSTek       | ROG STRIX Z490-A GAMING     | [dc5ec6eb84](https://linux-hardware.org/?probe=dc5ec6eb84) | Nov 30, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [6b21f343c3](https://linux-hardware.org/?probe=6b21f343c3) | Nov 30, 2022 |
| Gigabyte      | B450M DS3H-CF               | [952c3681c0](https://linux-hardware.org/?probe=952c3681c0) | Nov 30, 2022 |
| Gigabyte      | B450 AORUS M                | [3e3ccd1471](https://linux-hardware.org/?probe=3e3ccd1471) | Nov 30, 2022 |
| MSI           | B560M-A PRO                 | [81bf84e7e5](https://linux-hardware.org/?probe=81bf84e7e5) | Nov 29, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [9dd6019148](https://linux-hardware.org/?probe=9dd6019148) | Nov 29, 2022 |
| BESSTAR Te... | UM700                       | [a97334be81](https://linux-hardware.org/?probe=a97334be81) | Nov 29, 2022 |
| Gigabyte      | B450M DS3H-CF               | [eae94e440a](https://linux-hardware.org/?probe=eae94e440a) | Nov 29, 2022 |
| ASUSTek       | P5KPL-CM                    | [a20e18af73](https://linux-hardware.org/?probe=a20e18af73) | Nov 29, 2022 |
| ASRock        | H510M-HDV                   | [03a1675c85](https://linux-hardware.org/?probe=03a1675c85) | Nov 29, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [a95de3b373](https://linux-hardware.org/?probe=a95de3b373) | Nov 29, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [262228b1fb](https://linux-hardware.org/?probe=262228b1fb) | Nov 29, 2022 |
| Gigabyte      | F2A55M-HD2                  | [8b3da34947](https://linux-hardware.org/?probe=8b3da34947) | Nov 28, 2022 |
| ASRock        | B450M Pro4-F                | [8d0514a0df](https://linux-hardware.org/?probe=8d0514a0df) | Nov 28, 2022 |
| ECS           | H61H2-M13                   | [88988d4d0d](https://linux-hardware.org/?probe=88988d4d0d) | Nov 28, 2022 |
| Dell          | 0K3CM7 A00                  | [076eeadd80](https://linux-hardware.org/?probe=076eeadd80) | Nov 28, 2022 |
| HP            | 212B                        | [53471968c2](https://linux-hardware.org/?probe=53471968c2) | Nov 28, 2022 |
| Dell          | 05XGC8 A00                  | [e0e0efb9be](https://linux-hardware.org/?probe=e0e0efb9be) | Nov 27, 2022 |
| Dell          | 0D24M8 A00                  | [c58c83e367](https://linux-hardware.org/?probe=c58c83e367) | Nov 26, 2022 |
| Dell          | 0D24M8 A00                  | [85b508d6d3](https://linux-hardware.org/?probe=85b508d6d3) | Nov 26, 2022 |
| Dell          | 05XGC8 A00                  | [6ea1a60122](https://linux-hardware.org/?probe=6ea1a60122) | Nov 26, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [68e1087fde](https://linux-hardware.org/?probe=68e1087fde) | Nov 25, 2022 |
| Gigabyte      | B250-FinTech-CF             | [fcc81ea02b](https://linux-hardware.org/?probe=fcc81ea02b) | Nov 24, 2022 |
| Gigabyte      | A320M-S2H-CF                | [4246d4813a](https://linux-hardware.org/?probe=4246d4813a) | Nov 24, 2022 |
| Gigabyte      | A320M-S2H-CF                | [76f6ba932f](https://linux-hardware.org/?probe=76f6ba932f) | Nov 24, 2022 |
| ASUSTek       | ROG ZENITH EXTREME ALPHA    | [1d224863f2](https://linux-hardware.org/?probe=1d224863f2) | Nov 24, 2022 |
| ASUSTek       | P5Q3                        | [655065ee03](https://linux-hardware.org/?probe=655065ee03) | Nov 24, 2022 |
| Lenovo        | 312A NOK                    | [94cdaff2c9](https://linux-hardware.org/?probe=94cdaff2c9) | Nov 24, 2022 |
| Gigabyte      | 990FXA-UD3                  | [38aca80776](https://linux-hardware.org/?probe=38aca80776) | Nov 24, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [c0ce9a3ff3](https://linux-hardware.org/?probe=c0ce9a3ff3) | Nov 23, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [6c797b4554](https://linux-hardware.org/?probe=6c797b4554) | Nov 23, 2022 |
| MSI           | MAG B550 TORPEDO            | [ca3bcfa403](https://linux-hardware.org/?probe=ca3bcfa403) | Nov 23, 2022 |
| Gigabyte      | G31M-ES2L                   | [e8ab5ad410](https://linux-hardware.org/?probe=e8ab5ad410) | Nov 23, 2022 |
| ASRock        | H410M-HVS R2.0              | [3f381f9fa3](https://linux-hardware.org/?probe=3f381f9fa3) | Nov 23, 2022 |
| Gigabyte      | B650M DS3H                  | [fc9449798a](https://linux-hardware.org/?probe=fc9449798a) | Nov 23, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [9cbe89c328](https://linux-hardware.org/?probe=9cbe89c328) | Nov 22, 2022 |
| ASUSTek       | PRIME Z270-P                | [0e778da8b6](https://linux-hardware.org/?probe=0e778da8b6) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | [6d50058ef8](https://linux-hardware.org/?probe=6d50058ef8) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | [f6a783a27a](https://linux-hardware.org/?probe=f6a783a27a) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | [423fbc1fa0](https://linux-hardware.org/?probe=423fbc1fa0) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | [debc5b7ab9](https://linux-hardware.org/?probe=debc5b7ab9) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | [dc53077baa](https://linux-hardware.org/?probe=dc53077baa) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | [856bb3def2](https://linux-hardware.org/?probe=856bb3def2) | Nov 22, 2022 |
| Foxconn       | H61MXL/H61MXL-K             | [d140a0f503](https://linux-hardware.org/?probe=d140a0f503) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | [ee55108218](https://linux-hardware.org/?probe=ee55108218) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | [ec03d1b050](https://linux-hardware.org/?probe=ec03d1b050) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | [1f2a4089cc](https://linux-hardware.org/?probe=1f2a4089cc) | Nov 22, 2022 |
| Intel         | JSL MRD                     | [31ffd9d911](https://linux-hardware.org/?probe=31ffd9d911) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | [4190bbb2d8](https://linux-hardware.org/?probe=4190bbb2d8) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | [570a11d74b](https://linux-hardware.org/?probe=570a11d74b) | Nov 22, 2022 |
| Gigabyte      | G41M-ES2L                   | [404927f4cc](https://linux-hardware.org/?probe=404927f4cc) | Nov 22, 2022 |
| ASUSTek       | M4A78T-E                    | [aef32a0e69](https://linux-hardware.org/?probe=aef32a0e69) | Nov 22, 2022 |
| Dell          | 05DN3X A00                  | [f15eef78fa](https://linux-hardware.org/?probe=f15eef78fa) | Nov 22, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [910d921a9d](https://linux-hardware.org/?probe=910d921a9d) | Nov 20, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [dba99c363e](https://linux-hardware.org/?probe=dba99c363e) | Nov 20, 2022 |
| Intel         | JSL MRD                     | [469567b71f](https://linux-hardware.org/?probe=469567b71f) | Nov 20, 2022 |
| Dell          | 0WPMFG A00                  | [8b3a3dc37f](https://linux-hardware.org/?probe=8b3a3dc37f) | Nov 20, 2022 |
| Acer          | Nitro N50-620               | [ecd8e9ec1b](https://linux-hardware.org/?probe=ecd8e9ec1b) | Nov 20, 2022 |
| Intel         | JSL MRD                     | [e8171566d3](https://linux-hardware.org/?probe=e8171566d3) | Nov 19, 2022 |
| Gigabyte      | G31M-ES2L                   | [3e3d8f727c](https://linux-hardware.org/?probe=3e3d8f727c) | Nov 19, 2022 |
| ASRock        | Z790 PG Riptide             | [c852740256](https://linux-hardware.org/?probe=c852740256) | Nov 19, 2022 |
| Dell          | 02YRK5 A02                  | [da08e08dec](https://linux-hardware.org/?probe=da08e08dec) | Nov 18, 2022 |
| MSI           | H510M-A PRO                 | [e913feb821](https://linux-hardware.org/?probe=e913feb821) | Nov 18, 2022 |
| MSI           | MAG B550M MORTAR            | [57c6327e27](https://linux-hardware.org/?probe=57c6327e27) | Nov 18, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d1d9ddf9f3](https://linux-hardware.org/?probe=d1d9ddf9f3) | Nov 18, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Debian 11               | 2251     | 61.25%  |
| Debian 10               | 739      | 20.11%  |
| Debian Testing          | 231      | 6.29%   |
| Debian 9                | 146      | 3.97%   |
| Debian Unstable         | 116      | 3.16%   |
| Debian                  | 96       | 2.61%   |
| Debian 12               | 46       | 1.25%   |
| Debian 8                | 25       | 0.68%   |
| Debian 11-updates       | 16       | 0.44%   |
| Debian 7                | 5        | 0.14%   |
| Debian Testing/unstable | 2        | 0.05%   |
| Debian Sid              | 1        | 0.03%   |
| Debian 6                | 1        | 0.03%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Debian | 3561     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Desktops | Percent |
|-----------------------|----------|---------|
| 5.10.0-7-amd64        | 513      | 12.77%  |
| 5.10.0-8-amd64        | 239      | 5.95%   |
| 5.10.0-21-amd64       | 176      | 4.38%   |
| 5.10.0-9-amd64        | 123      | 3.06%   |
| 5.10.0-2-amd64        | 118      | 2.94%   |
| 5.10.0-19-amd64       | 101      | 2.51%   |
| 5.10.0-20-amd64       | 91       | 2.27%   |
| 5.10.0-13-amd64       | 86       | 2.14%   |
| 5.10.0-18-amd64       | 80       | 1.99%   |
| 5.10.0-11-amd64       | 73       | 1.82%   |
| 5.10.0-10-amd64       | 72       | 1.79%   |
| 5.10.0-16-amd64       | 68       | 1.69%   |
| 4.19.0-6-amd64        | 56       | 1.39%   |
| 4.19.0-16-amd64       | 52       | 1.29%   |
| 4.19.0-14-amd64       | 52       | 1.29%   |
| 5.10.0-14-amd64       | 50       | 1.24%   |
| 4.19.0-13-amd64       | 50       | 1.24%   |
| 4.19.0-9-amd64        | 48       | 1.19%   |
| 4.19.0-17-amd64       | 48       | 1.19%   |
| 4.19.0-8-amd64        | 47       | 1.17%   |
| 5.10.0-17-amd64       | 43       | 1.07%   |
| 5.10.0-15-amd64       | 41       | 1.02%   |
| 4.19.0-12-amd64       | 38       | 0.95%   |
| 5.15.0-2-amd64        | 36       | 0.9%    |
| 4.9.0-8-amd64         | 31       | 0.77%   |
| 5.10.0-12-amd64       | 29       | 0.72%   |
| 4.19.0-10-amd64       | 29       | 0.72%   |
| 5.6.0-2-amd64         | 28       | 0.7%    |
| 6.1.0-7-amd64         | 25       | 0.62%   |
| 5.18.0-2-amd64        | 20       | 0.5%    |
| 6.0.0-0.deb11.6-amd64 | 19       | 0.47%   |
| 5.7.0-1-amd64         | 19       | 0.47%   |
| 5.10.0-6-amd64        | 19       | 0.47%   |
| 4.9.0-9-amd64         | 19       | 0.47%   |
| 6.0.0-6-amd64         | 18       | 0.45%   |
| 5.4.0-4-amd64         | 18       | 0.45%   |
| 5.13.19-6-pve         | 18       | 0.45%   |
| 4.9.0-11-amd64        | 18       | 0.45%   |
| 4.19.0-5-amd64        | 18       | 0.45%   |
| 5.16.0-0.bpo.4-amd64  | 17       | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.10.0   | 1950     | 50.98%  |
| 4.19.0   | 509      | 13.31%  |
| 4.9.0    | 109      | 2.85%   |
| 6.1.0    | 94       | 2.46%   |
| 6.0.0    | 88       | 2.3%    |
| 5.18.0   | 78       | 2.04%   |
| 5.9.0    | 59       | 1.54%   |
| 5.16.0   | 56       | 1.46%   |
| 5.15.0   | 56       | 1.46%   |
| 5.8.0    | 55       | 1.44%   |
| 5.7.0    | 54       | 1.41%   |
| 5.6.0    | 48       | 1.25%   |
| 5.4.0    | 45       | 1.18%   |
| 5.13.19  | 44       | 1.15%   |
| 5.19.0   | 40       | 1.05%   |
| 5.14.0   | 33       | 0.86%   |
| 5.17.0   | 25       | 0.65%   |
| 5.11.22  | 19       | 0.5%    |
| 5.3.0    | 18       | 0.47%   |
| 5.5.0    | 14       | 0.37%   |
| 5.15.83  | 14       | 0.37%   |
| 5.15.74  | 14       | 0.37%   |
| 5.15.39  | 13       | 0.34%   |
| 5.15.35  | 13       | 0.34%   |
| 5.15.85  | 11       | 0.29%   |
| 5.15.30  | 11       | 0.29%   |
| 5.15.53  | 10       | 0.26%   |
| 5.15.102 | 10       | 0.26%   |
| 3.16.0   | 10       | 0.26%   |
| 5.4.106  | 9        | 0.24%   |
| 4.18.0   | 9        | 0.24%   |
| 5.2.0    | 8        | 0.21%   |
| 5.15.104 | 8        | 0.21%   |
| 5.4.44   | 7        | 0.18%   |
| 4.15.18  | 7        | 0.18%   |
| 4.1.42   | 7        | 0.18%   |
| 5.4.65   | 6        | 0.16%   |
| 4.17.0   | 5        | 0.13%   |
| 6.2.9    | 4        | 0.1%    |
| 6.0.8    | 4        | 0.1%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 1978     | 52.04%  |
| 4.19    | 520      | 13.68%  |
| 5.15    | 170      | 4.47%   |
| 4.9     | 115      | 3.03%   |
| 6.1     | 104      | 2.74%   |
| 6.0     | 98       | 2.58%   |
| 5.4     | 98       | 2.58%   |
| 5.18    | 83       | 2.18%   |
| 5.9     | 62       | 1.63%   |
| 5.8     | 61       | 1.6%    |
| 5.16    | 61       | 1.6%    |
| 5.7     | 58       | 1.53%   |
| 5.13    | 54       | 1.42%   |
| 5.6     | 52       | 1.37%   |
| 5.19    | 48       | 1.26%   |
| 5.14    | 36       | 0.95%   |
| 5.11    | 31       | 0.82%   |
| 5.3     | 30       | 0.79%   |
| 5.17    | 29       | 0.76%   |
| 5.5     | 17       | 0.45%   |
| 6.2     | 12       | 0.32%   |
| 4.15    | 11       | 0.29%   |
| 4.18    | 10       | 0.26%   |
| 3.16    | 10       | 0.26%   |
| 5.2     | 8        | 0.21%   |
| 5.0     | 8        | 0.21%   |
| 4.1     | 7        | 0.18%   |
| 4.17    | 5        | 0.13%   |
| 5.12    | 3        | 0.08%   |
| 5.1     | 3        | 0.08%   |
| 4.16    | 3        | 0.08%   |
| 4.20    | 2        | 0.05%   |
| 4.14    | 2        | 0.05%   |
| 4.13    | 2        | 0.05%   |
| 2.6     | 2        | 0.05%   |
| 6.3     | 1        | 0.03%   |
| 4.6     | 1        | 0.03%   |
| 4.5     | 1        | 0.03%   |
| 4.4     | 1        | 0.03%   |
| 4.3     | 1        | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 3443     | 96.66%  |
| i686    | 90       | 2.53%   |
| ppc64   | 7        | 0.2%    |
| riscv64 | 6        | 0.17%   |
| armv7l  | 5        | 0.14%   |
| ppc64le | 2        | 0.06%   |
| mips64  | 2        | 0.06%   |
| i586    | 2        | 0.06%   |
| aarch64 | 2        | 0.06%   |
| sparc64 | 1        | 0.03%   |
| sh4a    | 1        | 0.03%   |
| armv6l  | 1        | 0.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Unknown           | 1329     | 36.45%  |
| GNOME             | 661      | 18.13%  |
| XFCE              | 441      | 12.1%   |
| KDE5              | 418      | 11.46%  |
| MATE              | 169      | 4.64%   |
| X-Cinnamon        | 132      | 3.62%   |
| Cinnamon          | 106      | 2.91%   |
| LXDE              | 90       | 2.47%   |
| KDE               | 77       | 2.11%   |
| LXQt              | 59       | 1.62%   |
| i3                | 33       | 0.91%   |
| openbox           | 31       | 0.85%   |
| GNOME Flashback   | 20       | 0.55%   |
| lightdm-xsession  | 18       | 0.49%   |
| trinity           | 13       | 0.36%   |
| GNOME Classic     | 11       | 0.3%    |
| Budgie            | 11       | 0.3%    |
| awesome           | 5        | 0.14%   |
| KDE4              | 4        | 0.11%   |
| fluxbox           | 4        | 0.11%   |
| sway              | 3        | 0.08%   |
| Enlightenment     | 2        | 0.05%   |
| xmonad            | 1        | 0.03%   |
| UKUI              | 1        | 0.03%   |
| i3-with-shmlog    | 1        | 0.03%   |
| GNUstep           | 1        | 0.03%   |
| gnome-xorg        | 1        | 0.03%   |
| e16-session       | 1        | 0.03%   |
| DWM               | 1        | 0.03%   |
| default           | 1        | 0.03%   |
| /etc/X11/Xsession | 1        | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| X11         | 1934     | 53.38%  |
| Unknown     | 788      | 21.75%  |
| Tty         | 553      | 15.26%  |
| Wayland     | 345      | 9.52%   |
| Web         | 2        | 0.06%   |
| Unspecified | 1        | 0.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1844     | 50.76%  |
| LightDM | 536      | 14.75%  |
| GDM     | 451      | 12.41%  |
| SDDM    | 400      | 11.01%  |
| TDM     | 250      | 6.88%   |
| GDM3    | 101      | 2.78%   |
| XDM     | 16       | 0.44%   |
| SLiM    | 16       | 0.44%   |
| NODM    | 9        | 0.25%   |
| KDM     | 5        | 0.14%   |
| LXDM    | 2        | 0.06%   |
| WDM     | 1        | 0.03%   |
| SU      | 1        | 0.03%   |
| Ly      | 1        | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 1204     | 33.35%  |
| ru_RU   | 754      | 20.89%  |
| Unknown | 279      | 7.73%   |
| de_DE   | 205      | 5.68%   |
| fr_FR   | 170      | 4.71%   |
| en_GB   | 162      | 4.49%   |
| pt_BR   | 110      | 3.05%   |
| es_ES   | 104      | 2.88%   |
| it_IT   | 76       | 2.11%   |
| en_CA   | 57       | 1.58%   |
| C       | 55       | 1.52%   |
| en_AU   | 53       | 1.47%   |
| pl_PL   | 34       | 0.94%   |
| en_IN   | 18       | 0.5%    |
| en_IE   | 18       | 0.5%    |
| zh_CN   | 17       | 0.47%   |
| ja_JP   | 17       | 0.47%   |
| hu_HU   | 17       | 0.47%   |
| es_AR   | 16       | 0.44%   |
| de_AT   | 16       | 0.44%   |
| es_VE   | 14       | 0.39%   |
| es_MX   | 13       | 0.36%   |
| pt_PT   | 11       | 0.3%    |
| nl_BE   | 11       | 0.3%    |
| nl_NL   | 10       | 0.28%   |
| cs_CZ   | 10       | 0.28%   |
| en_NZ   | 8        | 0.22%   |
| de_CH   | 8        | 0.22%   |
| es_CL   | 7        | 0.19%   |
| en_ZA   | 7        | 0.19%   |
| sv_SE   | 6        | 0.17%   |
| ru_UA   | 6        | 0.17%   |
| uk_UA   | 5        | 0.14%   |
| fr_BE   | 5        | 0.14%   |
| en_DK   | 5        | 0.14%   |
| ca_ES   | 5        | 0.14%   |
| ro_RO   | 4        | 0.11%   |
| hr_HR   | 4        | 0.11%   |
| fr_CH   | 4        | 0.11%   |
| eu_ES   | 4        | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 2274     | 62.89%  |
| EFI  | 1342     | 37.11%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type       | Desktops | Percent |
|------------|----------|---------|
| Ext4       | 2483     | 68.97%  |
| Overlay    | 686      | 19.06%  |
| Btrfs      | 140      | 3.89%   |
| Zfs        | 89       | 2.47%   |
| Unknown    | 81       | 2.25%   |
| Xfs        | 63       | 1.75%   |
| Ext3       | 23       | 0.64%   |
| Ext2       | 9        | 0.25%   |
| Rootfs     | 8        | 0.22%   |
| Tmpfs      | 7        | 0.19%   |
| Aufs       | 4        | 0.11%   |
| XXXXXXX    | 2        | 0.06%   |
| Jfs        | 2        | 0.06%   |
| F2fs       | 2        | 0.06%   |
| Fuse.sshfs | 1        | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 1692     | 46.48%  |
| MBR     | 1240     | 34.07%  |
| Unknown | 708      | 19.45%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 2898     | 80.3%   |
| Yes       | 711      | 19.7%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 2222     | 61.64%  |
| Yes       | 1383     | 38.36%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 977      | 27.44%  |
| Gigabyte Technology                  | 594      | 16.68%  |
| ASRock                               | 369      | 10.36%  |
| MSI                                  | 366      | 10.28%  |
| Dell                                 | 235      | 6.6%    |
| Hewlett-Packard                      | 222      | 6.23%   |
| Intel                                | 114      | 3.2%    |
| Lenovo                               | 103      | 2.89%   |
| Unknown                              | 72       | 2.02%   |
| ECS                                  | 54       | 1.52%   |
| Foxconn                              | 38       | 1.07%   |
| Fujitsu                              | 36       | 1.01%   |
| AZW                                  | 30       | 0.84%   |
| Acer                                 | 29       | 0.81%   |
| ASRockRack                           | 27       | 0.76%   |
| Supermicro                           | 25       | 0.7%    |
| Pegatron                             | 21       | 0.59%   |
| Biostar                              | 21       | 0.59%   |
| Huanan                               | 13       | 0.37%   |
| Shuttle                              | 11       | 0.31%   |
| Fujitsu Siemens                      | 11       | 0.31%   |
| Positivo                             | 10       | 0.28%   |
| Inventec                             | 10       | 0.28%   |
| Apple                                | 10       | 0.28%   |
| Medion                               | 9        | 0.25%   |
| Google                               | 8        | 0.22%   |
| BESSTAR Tech                         | 8        | 0.22%   |
| Hardkernel                           | 5        | 0.14%   |
| Techvision                           | 4        | 0.11%   |
| Packard Bell                         | 4        | 0.11%   |
| IceWhale Technology                  | 4        | 0.11%   |
| Gateway                              | 4        | 0.11%   |
| Alienware                            | 4        | 0.11%   |
| Wistron                              | 3        | 0.08%   |
| Shenzhen Meigao Electronic Equipment | 3        | 0.08%   |
| PCWare                               | 3        | 0.08%   |
| PC Engines                           | 3        | 0.08%   |
| Itautec                              | 3        | 0.08%   |
| HPE                                  | 3        | 0.08%   |
| Aquarius                             | 3        | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| ASUS All Series              | 118      | 3.31%   |
| Unknown                      | 77       | 2.16%   |
| ASUS S20 K29                 | 55       | 1.54%   |
| MSI MS-7996                  | 39       | 1.1%    |
| MSI MS-7817                  | 23       | 0.65%   |
| ECS G31T-M9                  | 23       | 0.65%   |
| ASRock H470M-HVS             | 20       | 0.56%   |
| Dell OptiPlex 7010           | 19       | 0.53%   |
| ASUS PRIME H510M-A           | 19       | 0.53%   |
| Gigabyte H81M-S2V            | 18       | 0.51%   |
| Gigabyte H410M S2H           | 16       | 0.45%   |
| Gigabyte B450M DS3H          | 16       | 0.45%   |
| ECS H61H2-M13                | 16       | 0.45%   |
| ASUS P8H61-M LX3 R2.0        | 15       | 0.42%   |
| ASUS TUF Gaming X570-PLUS    | 14       | 0.39%   |
| ASUS PRIME A320M-K           | 14       | 0.39%   |
| ASRock B450M Pro4            | 14       | 0.39%   |
| ASUS PRIME B450M-A           | 13       | 0.37%   |
| MSI MS-7C56                  | 12       | 0.34%   |
| Gigabyte B450M S2H           | 11       | 0.31%   |
| MSI MS-7C02                  | 10       | 0.28%   |
| MSI MS-7B79                  | 10       | 0.28%   |
| HP Z420 Workstation          | 10       | 0.28%   |
| HP Compaq Elite 8300 SFF     | 10       | 0.28%   |
| ASUS PRIME X370-PRO          | 10       | 0.28%   |
| ASUS PRIME B450-PLUS         | 10       | 0.28%   |
| ASUS P8H67-M                 | 10       | 0.28%   |
| ASUS H110M-R                 | 10       | 0.28%   |
| ASRock B450 Pro4             | 10       | 0.28%   |
| HP ProLiant MicroServer Gen8 | 9        | 0.25%   |
| HP ProLiant MicroServer      | 9        | 0.25%   |
| Gigabyte H61M-S2PV           | 9        | 0.25%   |
| Gigabyte GA-78LMT-USB3       | 9        | 0.25%   |
| Dell OptiPlex 3020           | 9        | 0.25%   |
| ASRock H61M-VG4              | 9        | 0.25%   |
| MSI MS-7C91                  | 8        | 0.22%   |
| MSI MS-7C84                  | 8        | 0.22%   |
| MSI MS-7A34                  | 8        | 0.22%   |
| MSI MS-7721                  | 8        | 0.22%   |
| Gigabyte B360M H             | 8        | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 197      | 5.53%   |
| Dell OptiPlex          | 128      | 3.59%   |
| ASUS All               | 118      | 3.31%   |
| ASUS ROG               | 78       | 2.19%   |
| Unknown                | 77       | 2.16%   |
| HP Compaq              | 60       | 1.68%   |
| Lenovo ThinkCentre     | 56       | 1.57%   |
| ASUS TUF               | 56       | 1.57%   |
| ASUS S20               | 55       | 1.54%   |
| Dell Precision         | 45       | 1.26%   |
| MSI MS-7996            | 39       | 1.1%    |
| Gigabyte B450M         | 36       | 1.01%   |
| ASUS P8H61-M           | 34       | 0.95%   |
| HP EliteDesk           | 29       | 0.81%   |
| HP ProLiant            | 28       | 0.79%   |
| ASUS PRO               | 24       | 0.67%   |
| ASRock B450M           | 24       | 0.67%   |
| MSI MS-7817            | 23       | 0.65%   |
| Gigabyte X570          | 23       | 0.65%   |
| ECS G31T-M9            | 23       | 0.65%   |
| ASRock H470M-HVS       | 20       | 0.56%   |
| Gigabyte H410M         | 19       | 0.53%   |
| Gigabyte B550          | 19       | 0.53%   |
| ASRock B450            | 19       | 0.53%   |
| Acer Aspire            | 19       | 0.53%   |
| Gigabyte H81M-S2V      | 18       | 0.51%   |
| ASUS M5A78L-M          | 18       | 0.51%   |
| Lenovo ThinkStation    | 17       | 0.48%   |
| HP ProDesk             | 17       | 0.48%   |
| Fujitsu ESPRIMO        | 17       | 0.48%   |
| ECS H61H2-M13          | 16       | 0.45%   |
| ASUS P5G41T-M          | 16       | 0.45%   |
| Gigabyte GA-78LMT-USB3 | 15       | 0.42%   |
| Dell Vostro            | 15       | 0.42%   |
| ASUS M5A97             | 15       | 0.42%   |
| Gigabyte B450          | 14       | 0.39%   |
| Dell XPS               | 14       | 0.39%   |
| ASUS P8H67-M           | 14       | 0.39%   |
| ASRock X570            | 14       | 0.39%   |
| Lenovo IdeaCentre      | 13       | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 349      | 9.8%    |
| 2012    | 341      | 9.58%   |
| 2020    | 333      | 9.35%   |
| 2013    | 289      | 8.12%   |
| 2019    | 255      | 7.16%   |
| 2011    | 229      | 6.43%   |
| 2021    | 228      | 6.4%    |
| 2014    | 201      | 5.64%   |
| 2017    | 192      | 5.39%   |
| 2009    | 188      | 5.28%   |
| 2015    | 178      | 5%      |
| 2010    | 166      | 4.66%   |
| 2016    | 142      | 3.99%   |
| 2008    | 130      | 3.65%   |
| 2022    | 120      | 3.37%   |
| 2007    | 96       | 2.7%    |
| 2006    | 45       | 1.26%   |
| Unknown | 26       | 0.73%   |
| 2005    | 25       | 0.7%    |
| 2023    | 9        | 0.25%   |
| 2004    | 8        | 0.22%   |
| 2003    | 5        | 0.14%   |
| 2001    | 3        | 0.08%   |
| 2000    | 2        | 0.06%   |
| 2002    | 1        | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 3561     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 3508     | 98.29%  |
| Enabled  | 61       | 1.71%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 3544     | 99.52%  |
| Yes  | 17       | 0.48%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 722      | 19.98%  |
| 4.01-8.0        | 581      | 16.08%  |
| 3.01-4.0        | 567      | 15.69%  |
| 8.01-16.0       | 564      | 15.61%  |
| 32.01-64.0      | 509      | 14.09%  |
| 64.01-256.0     | 295      | 8.16%   |
| 1.01-2.0        | 150      | 4.15%   |
| 24.01-32.0      | 96       | 2.66%   |
| 2.01-3.0        | 61       | 1.69%   |
| 0.51-1.0        | 23       | 0.64%   |
| More than 256.0 | 16       | 0.44%   |
| Unknown         | 15       | 0.42%   |
| 0.01-0.5        | 13       | 0.36%   |
| 0               | 1        | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB         | Desktops | Percent |
|-----------------|----------|---------|
| 0.51-1.0        | 865      | 22.43%  |
| 1.01-2.0        | 783      | 20.31%  |
| 2.01-3.0        | 634      | 16.44%  |
| 4.01-8.0        | 575      | 14.91%  |
| 3.01-4.0        | 374      | 9.7%    |
| 8.01-16.0       | 248      | 6.43%   |
| 0.01-0.5        | 157      | 4.07%   |
| 16.01-24.0      | 101      | 2.62%   |
| 32.01-64.0      | 49       | 1.27%   |
| 24.01-32.0      | 36       | 0.93%   |
| Unknown         | 18       | 0.47%   |
| 64.01-256.0     | 15       | 0.39%   |
| More than 256.0 | 1        | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 1602     | 43.69%  |
| 2       | 844      | 23.02%  |
| 3       | 482      | 13.14%  |
| 4       | 328      | 8.94%   |
| 5       | 157      | 4.28%   |
| 6       | 87       | 2.37%   |
| 7       | 48       | 1.31%   |
| 8       | 38       | 1.04%   |
| 0       | 20       | 0.55%   |
| 9       | 17       | 0.46%   |
| 10      | 13       | 0.35%   |
| 11      | 7        | 0.19%   |
| 13      | 6        | 0.16%   |
| 12      | 5        | 0.14%   |
| 14      | 2        | 0.05%   |
| Unknown | 2        | 0.05%   |
| 46      | 1        | 0.03%   |
| 29      | 1        | 0.03%   |
| 28      | 1        | 0.03%   |
| 27      | 1        | 0.03%   |
| 22      | 1        | 0.03%   |
| 21      | 1        | 0.03%   |
| 18      | 1        | 0.03%   |
| 17      | 1        | 0.03%   |
| 16      | 1        | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2294     | 63.83%  |
| Yes       | 1300     | 36.17%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 3532     | 99.19%  |
| No        | 29       | 0.81%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2484     | 69.23%  |
| Yes       | 1104     | 30.77%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2713     | 75.4%   |
| Yes       | 885      | 24.6%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Russia       | 836      | 23.44%  |
| USA          | 522      | 14.63%  |
| Germany      | 350      | 9.81%   |
| France       | 221      | 6.2%    |
| Brazil       | 173      | 4.85%   |
| Spain        | 151      | 4.23%   |
| Italy        | 118      | 3.31%   |
| UK           | 115      | 3.22%   |
| Canada       | 95       | 2.66%   |
| Australia    | 72       | 2.02%   |
| Poland       | 62       | 1.74%   |
| Netherlands  | 56       | 1.57%   |
| China        | 42       | 1.18%   |
| Switzerland  | 41       | 1.15%   |
| Austria      | 38       | 1.07%   |
| Ukraine      | 36       | 1.01%   |
| Hungary      | 35       | 0.98%   |
| Belgium      | 34       | 0.95%   |
| Finland      | 28       | 0.78%   |
| Sweden       | 26       | 0.73%   |
| Mexico       | 25       | 0.7%    |
| Argentina    | 24       | 0.67%   |
| India        | 23       | 0.64%   |
| Romania      | 22       | 0.62%   |
| Czechia      | 22       | 0.62%   |
| Portugal     | 21       | 0.59%   |
| Bulgaria     | 21       | 0.59%   |
| Norway       | 20       | 0.56%   |
| Japan        | 20       | 0.56%   |
| Venezuela    | 18       | 0.5%    |
| Turkey       | 15       | 0.42%   |
| Belarus      | 15       | 0.42%   |
| Denmark      | 14       | 0.39%   |
| South Africa | 11       | 0.31%   |
| New Zealand  | 11       | 0.31%   |
| Malaysia     | 11       | 0.31%   |
| Taiwan       | 10       | 0.28%   |
| Slovakia     | 9        | 0.25%   |
| Pakistan     | 9        | 0.25%   |
| Ireland      | 9        | 0.25%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Voronezh          | 585      | 15.85%  |
| Moscow            | 64       | 1.73%   |
| St Petersburg     | 45       | 1.22%   |
| Paris             | 31       | 0.84%   |
| Vienna            | 29       | 0.79%   |
| Sao Paulo         | 28       | 0.76%   |
| Berlin            | 26       | 0.7%    |
| Falkenstein       | 22       | 0.6%    |
| Madrid            | 21       | 0.57%   |
| Seville           | 20       | 0.54%   |
| Barcelona         | 20       | 0.54%   |
| Rio de Janeiro    | 17       | 0.46%   |
| Amsterdam         | 17       | 0.46%   |
| Toronto           | 16       | 0.43%   |
| Melbourne         | 15       | 0.41%   |
| Yekaterinburg     | 14       | 0.38%   |
| Sydney            | 14       | 0.38%   |
| Milan             | 14       | 0.38%   |
| Brisbane          | 14       | 0.38%   |
| London            | 13       | 0.35%   |
| Budapest          | 13       | 0.35%   |
| Zurich            | 12       | 0.33%   |
| Warsaw            | 12       | 0.33%   |
| Munich            | 12       | 0.33%   |
| Hamburg           | 12       | 0.33%   |
| Bangor            | 12       | 0.33%   |
| Perm              | 11       | 0.3%    |
| New York          | 11       | 0.3%    |
| Kyiv              | 11       | 0.3%    |
| Dallas            | 11       | 0.3%    |
| Chicago           | 11       | 0.3%    |
| Minsk             | 10       | 0.27%   |
| Gladbeck          | 10       | 0.27%   |
| Dover-Foxcroft    | 10       | 0.27%   |
| Cologne           | 10       | 0.27%   |
| Kuala Lumpur      | 9        | 0.24%   |
| Frankfurt am Main | 9        | 0.24%   |
| Brasília         | 9        | 0.24%   |
| Valencia          | 8        | 0.22%   |
| Stockholm         | 8        | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 1183     | 2174   | 18.66%  |
| Seagate                   | 1158     | 2085   | 18.27%  |
| Samsung Electronics       | 927      | 1493   | 14.62%  |
| Kingston                  | 443      | 587    | 6.99%   |
| Toshiba                   | 423      | 770    | 6.67%   |
| Crucial                   | 346      | 467    | 5.46%   |
| Hitachi                   | 222      | 329    | 3.5%    |
| SanDisk                   | 216      | 298    | 3.41%   |
| Intel                     | 123      | 171    | 1.94%   |
| A-DATA Technology         | 100      | 137    | 1.58%   |
| HGST                      | 89       | 160    | 1.4%    |
| China                     | 83       | 99     | 1.31%   |
| Unknown                   | 76       | 112    | 1.2%    |
| SPCC                      | 52       | 57     | 0.82%   |
| Phison                    | 48       | 69     | 0.76%   |
| Corsair                   | 44       | 62     | 0.69%   |
| OCZ                       | 43       | 54     | 0.68%   |
| Maxtor                    | 43       | 50     | 0.68%   |
| PNY                       | 41       | 75     | 0.65%   |
| Transcend                 | 40       | 43     | 0.63%   |
| Hewlett-Packard           | 37       | 66     | 0.58%   |
| Micron Technology         | 29       | 35     | 0.46%   |
| Patriot                   | 28       | 36     | 0.44%   |
| Netac                     | 27       | 86     | 0.43%   |
| SK hynix                  | 26       | 40     | 0.41%   |
| Intenso                   | 24       | 33     | 0.38%   |
| Gigabyte Technology       | 24       | 28     | 0.38%   |
| GOODRAM                   | 22       | 38     | 0.35%   |
| Unknown                   | 17       | 18     | 0.27%   |
| Apacer                    | 16       | 18     | 0.25%   |
| XPG                       | 15       | 26     | 0.24%   |
| JMicron Technology        | 14       | 16     | 0.22%   |
| Plextor                   | 13       | 19     | 0.21%   |
| LITEON                    | 13       | 16     | 0.21%   |
| Silicon Motion            | 12       | 17     | 0.19%   |
| KingDian                  | 12       | 13     | 0.19%   |
| Team                      | 10       | 14     | 0.16%   |
| Micron/Crucial Technology | 9        | 13     | 0.14%   |
| Hajaan                    | 8        | 12     | 0.13%   |
| ASMT                      | 8        | 11     | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 106      | 1.41%   |
| Kingston SA400S37240G 240GB SSD  | 104      | 1.38%   |
| Seagate ST1000DM010-2EP102 1TB   | 79       | 1.05%   |
| Crucial CT480BX500SSD1 480GB     | 74       | 0.98%   |
| Toshiba DT01ACA050 500GB         | 72       | 0.96%   |
| Kingston SV300S37A120G 120GB SSD | 59       | 0.78%   |
| Kingston SA400S37480G 480GB SSD  | 56       | 0.74%   |
| Toshiba DT01ACA100 1TB           | 54       | 0.72%   |
| Samsung SSD 860 EVO 500GB        | 54       | 0.72%   |
| Samsung SSD 860 EVO 1TB          | 52       | 0.69%   |
| Samsung SSD 860 EVO 250GB        | 50       | 0.66%   |
| WDC WD10EZEX-08WN4A0 1TB         | 49       | 0.65%   |
| Samsung SSD 850 EVO 250GB        | 49       | 0.65%   |
| Kingston SA400S37120G 120GB SSD  | 49       | 0.65%   |
| Toshiba HDWD110 1TB              | 45       | 0.6%    |
| Seagate ST2000DM008-2FR102 2TB   | 44       | 0.59%   |
| Samsung SSD 970 EVO Plus 500GB   | 44       | 0.59%   |
| Samsung SSD 850 EVO 500GB        | 43       | 0.57%   |
| Seagate ST1000DM003-1ER162 1TB   | 40       | 0.53%   |
| Samsung SSD 970 EVO Plus 1TB     | 40       | 0.53%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 39       | 0.52%   |
| Seagate ST1000DM003-1CH162 1TB   | 39       | 0.52%   |
| Crucial CT240BX500SSD1 240GB     | 38       | 0.51%   |
| Hitachi HDS721050CLA362 500GB    | 37       | 0.49%   |
| Crucial CT500MX500SSD1 500GB     | 37       | 0.49%   |
| Seagate ST4000DM004-2CV104 4TB   | 36       | 0.48%   |
| Crucial CT1000MX500SSD1 1TB      | 36       | 0.48%   |
| Toshiba DT01ACA200 2TB           | 30       | 0.4%    |
| Seagate ST2000DM001-1ER164 2TB   | 29       | 0.39%   |
| Samsung SSD 980 PRO 1TB          | 29       | 0.39%   |
| Seagate ST3500418AS 500GB        | 27       | 0.36%   |
| WDC WD20EFRX-68EUZN0 2TB         | 26       | 0.35%   |
| Seagate ST2000DM006-2DM164 2TB   | 26       | 0.35%   |
| WDC WD10EZEX-00BN5A0 1TB         | 25       | 0.33%   |
| WDC WD30EFRX-68EUZN0 3TB         | 24       | 0.32%   |
| Crucial CT250MX500SSD1 250GB     | 24       | 0.32%   |
| WDC WD40EFRX-68N32N0 4TB         | 23       | 0.31%   |
| Toshiba DT01ACA300 3TB           | 23       | 0.31%   |
| Seagate ST31000528AS 1TB         | 23       | 0.31%   |
| Seagate ST3250318AS 250GB        | 22       | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1135     | 2030   | 36.01%  |
| WDC                 | 1038     | 1928   | 32.93%  |
| Toshiba             | 386      | 705    | 12.25%  |
| Hitachi             | 222      | 329    | 7.04%   |
| Samsung Electronics | 148      | 200    | 4.7%    |
| HGST                | 89       | 160    | 2.82%   |
| Maxtor              | 42       | 49     | 1.33%   |
| Unknown             | 16       | 23     | 0.51%   |
| JMicron Technology  | 10       | 12     | 0.32%   |
| Hewlett-Packard     | 9        | 24     | 0.29%   |
| Fujitsu             | 6        | 7      | 0.19%   |
| ASMT                | 6        | 9      | 0.19%   |
| Intenso             | 4        | 5      | 0.13%   |
| HPE                 | 4        | 9      | 0.13%   |
| Apple               | 4        | 5      | 0.13%   |
| ASMedia             | 3        | 3      | 0.1%    |
| QNAP                | 2        | 3      | 0.06%   |
| USB 3.0             | 1        | 2      | 0.03%   |
| Synology            | 1        | 1      | 0.03%   |
| StoreJet            | 1        | 1      | 0.03%   |
| SD                  | 1        | 1      | 0.03%   |
| SABRENT             | 1        | 2      | 0.03%   |
| RSH-319             | 1        | 1      | 0.03%   |
| Quantum             | 1        | 1      | 0.03%   |
| pqi                 | 1        | 1      | 0.03%   |
| Pear 2TB            | 1        | 1      | 0.03%   |
| NAS                 | 1        | 10     | 0.03%   |
| MaxDigital          | 1        | 4      | 0.03%   |
| MARSHAL             | 1        | 1      | 0.03%   |
| Magnetic Data       | 1        | 1      | 0.03%   |
| LIO-ORG             | 1        | 8      | 0.03%   |
| LaCie               | 1        | 1      | 0.03%   |
| Innodisk            | 1        | 1      | 0.03%   |
| Inateck             | 1        | 1      | 0.03%   |
| IBM/Hitachi         | 1        | 1      | 0.03%   |
| IBM H0              | 1        | 1      | 0.03%   |
| Hajaan              | 1        | 1      | 0.03%   |
| H/W                 | 1        | 3      | 0.03%   |
| ExcelStor           | 1        | 1      | 0.03%   |
| DAS                 | 1        | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 521      | 763    | 22.56%  |
| Kingston            | 399      | 521    | 17.28%  |
| Crucial             | 310      | 417    | 13.43%  |
| SanDisk             | 154      | 211    | 6.67%   |
| WDC                 | 126      | 154    | 5.46%   |
| China               | 81       | 97     | 3.51%   |
| A-DATA Technology   | 77       | 102    | 3.33%   |
| Intel               | 65       | 86     | 2.82%   |
| SPCC                | 45       | 48     | 1.95%   |
| OCZ                 | 43       | 54     | 1.86%   |
| Transcend           | 36       | 39     | 1.56%   |
| Toshiba             | 32       | 41     | 1.39%   |
| PNY                 | 30       | 61     | 1.3%    |
| Netac               | 26       | 85     | 1.13%   |
| Patriot             | 21       | 25     | 0.91%   |
| GOODRAM             | 19       | 26     | 0.82%   |
| Intenso             | 18       | 24     | 0.78%   |
| Corsair             | 18       | 23     | 0.78%   |
| Micron Technology   | 17       | 21     | 0.74%   |
| Hewlett-Packard     | 12       | 16     | 0.52%   |
| Gigabyte Technology | 12       | 14     | 0.52%   |
| Apacer              | 12       | 12     | 0.52%   |
| KingDian            | 11       | 12     | 0.48%   |
| Seagate             | 10       | 12     | 0.43%   |
| Plextor             | 10       | 16     | 0.43%   |
| SK hynix            | 9        | 10     | 0.39%   |
| LITEON              | 9        | 12     | 0.39%   |
| Unknown             | 9        | 10     | 0.39%   |
| Unknown             | 8        | 11     | 0.35%   |
| Team                | 8        | 11     | 0.35%   |
| Hajaan              | 8        | 11     | 0.35%   |
| Mushkin             | 7        | 8      | 0.3%    |
| LITEONIT            | 7        | 11     | 0.3%    |
| Xinhaike            | 5        | 8      | 0.22%   |
| NGFF                | 5        | 5      | 0.22%   |
| T-FORCE             | 4        | 5      | 0.17%   |
| Smartbuy            | 4        | 4      | 0.17%   |
| Hoodisk             | 4        | 4      | 0.17%   |
| Foxline             | 4        | 4      | 0.17%   |
| Drevo               | 4        | 4      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 2410     | 5555   | 45.46%  |
| SSD     | 1922     | 3129   | 36.26%  |
| NVMe    | 861      | 1360   | 16.24%  |
| Unknown | 68       | 124    | 1.28%   |
| MMC     | 40       | 47     | 0.75%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 3239     | 8340   | 74.32%  |
| NVMe | 854      | 1347   | 19.6%   |
| SAS  | 225      | 481    | 5.16%   |
| MMC  | 40       | 47     | 0.92%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives  | Percent |
|------------|----------|---------|---------|
| 0.01-0.5   | 2511     | 4247    | 51.54%  |
| 0.51-1.0   | 1171     | 1943    | 24.04%  |
| 1.01-2.0   | 503      | 887     | 10.32%  |
| 3.01-4.0   | 262      | 547     | 5.38%   |
| 4.01-10.0  | 206      | 524     | 4.23%   |
| 2.01-3.0   | 156      | 293     | 3.2%    |
| 10.01-20.0 | 61       | 242     | 1.25%   |
| 20.01-50.0 | 1        | 1       | 0.02%   |
| 0          | 1        | Unknown | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 766      | 20.74%  |
| 101-250        | 587      | 15.89%  |
| 251-500        | 492      | 13.32%  |
| 501-1000       | 464      | 12.56%  |
| More than 3000 | 428      | 11.59%  |
| 1001-2000      | 337      | 9.13%   |
| 51-100         | 198      | 5.36%   |
| 2001-3000      | 172      | 4.66%   |
| 1-20           | 133      | 3.6%    |
| 21-50          | 116      | 3.14%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 950      | 25.17%  |
| Unknown        | 766      | 20.3%   |
| 101-250        | 372      | 9.86%   |
| 21-50          | 317      | 8.4%    |
| 251-500        | 290      | 7.68%   |
| 51-100         | 282      | 7.47%   |
| 501-1000       | 280      | 7.42%   |
| 1001-2000      | 216      | 5.72%   |
| More than 3000 | 190      | 5.03%   |
| 2001-3000      | 102      | 2.7%    |
| 0              | 9        | 0.24%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 26       | 37     | 3.08%   |
| WDC WD5000AAKX-60U6AA0 500GB      | 20       | 24     | 2.37%   |
| Kingston SV300S37A120G 120GB SSD  | 19       | 19     | 2.25%   |
| Hitachi HDS721050CLA362 500GB     | 11       | 11     | 1.3%    |
| Seagate ST1000DM003-9YN162 1TB    | 9        | 10     | 1.07%   |
| WDC WD5000AAKX-08U6AA0 500GB      | 8        | 8      | 0.95%   |
| Seagate ST31500341AS 1TB          | 8        | 14     | 0.95%   |
| Seagate ST31000528AS 1TB          | 8        | 9      | 0.95%   |
| Toshiba DT01ACA100 1TB            | 7        | 9      | 0.83%   |
| Toshiba DT01ACA050 500GB          | 7        | 8      | 0.83%   |
| Seagate ST3500418AS 500GB         | 7        | 12     | 0.83%   |
| Seagate ST3250318AS 250GB         | 7        | 8      | 0.83%   |
| Seagate ST250DM000-1BD141 250GB   | 7        | 7      | 0.83%   |
| Seagate ST1000DM003-1CH162 1TB    | 7        | 7      | 0.83%   |
| WDC WD5000AAKX-001CA0 500GB       | 6        | 8      | 0.71%   |
| Seagate ST3320613AS 320GB         | 6        | 6      | 0.71%   |
| Seagate ST3160815AS 160GB         | 6        | 8      | 0.71%   |
| Hitachi HDS721050DLE630 500GB     | 6        | 11     | 0.71%   |
| WDC WD5000AAKX-00ERMA0 500GB      | 5        | 6      | 0.59%   |
| WDC WD20EFRX-68EUZN0 2TB          | 5        | 16     | 0.59%   |
| WDC WD20EARX-00PASB0 2TB          | 5        | 7      | 0.59%   |
| WDC WD10EZEX-08WN4A0 1TB          | 5        | 5      | 0.59%   |
| WDC WD10EARS-00Y5B1 1TB           | 5        | 5      | 0.59%   |
| WDC WD10EADS-00M2B0 1TB           | 5        | 5      | 0.59%   |
| Seagate ST3500413AS 500GB         | 5        | 6      | 0.59%   |
| Seagate ST31000524AS 1TB          | 5        | 5      | 0.59%   |
| Samsung Electronics HD103UJ 1TB   | 5        | 6      | 0.59%   |
| WDC WDS120G2G0A-00JH30 120GB SSD  | 4        | 4      | 0.47%   |
| WDC WD20EARS-00MVWB0 2TB          | 4        | 4      | 0.47%   |
| Seagate ST9500325AS 500GB         | 4        | 6      | 0.47%   |
| Seagate ST3320620AS 320GB         | 4        | 6      | 0.47%   |
| Seagate ST3250410AS 250GB         | 4        | 5      | 0.47%   |
| Seagate ST2000DM001-1ER164 2TB    | 4        | 4      | 0.47%   |
| Seagate ST2000DM001-1CH164 2TB    | 4        | 5      | 0.47%   |
| Seagate ST2000DL003-9VT166 2TB    | 4        | 4      | 0.47%   |
| Seagate ST1000DM010-2EP102 1TB    | 4        | 5      | 0.47%   |
| Samsung Electronics HD103SJ 1TB   | 4        | 4      | 0.47%   |
| Maxtor STM3250310AS 250GB         | 4        | 4      | 0.47%   |
| A-DATA Technology SU800 256GB SSD | 4        | 7      | 0.47%   |
| WDC WDS240G2G0A-00JH30 240GB SSD  | 3        | 3      | 0.36%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 247      | 348    | 30.84%  |
| WDC                 | 227      | 310    | 28.34%  |
| Samsung Electronics | 71       | 80     | 8.86%   |
| Hitachi             | 55       | 77     | 6.87%   |
| Toshiba             | 38       | 48     | 4.74%   |
| Kingston            | 36       | 42     | 4.49%   |
| Intel               | 22       | 26     | 2.75%   |
| Crucial             | 16       | 22     | 2%      |
| A-DATA Technology   | 15       | 22     | 1.87%   |
| Maxtor              | 14       | 15     | 1.75%   |
| HGST                | 9        | 10     | 1.12%   |
| SanDisk             | 8        | 11     | 1%      |
| OCZ                 | 7        | 8      | 0.87%   |
| China               | 5        | 5      | 0.62%   |
| SK hynix            | 4        | 8      | 0.5%    |
| KingDian            | 4        | 4      | 0.5%    |
| Micron Technology   | 3        | 3      | 0.37%   |
| LITEONIT            | 2        | 2      | 0.25%   |
| Hewlett-Packard     | 2        | 3      | 0.25%   |
| Corsair             | 2        | 2      | 0.25%   |
| Apacer              | 2        | 2      | 0.25%   |
| Unknown             | 1        | 1      | 0.12%   |
| Transcend           | 1        | 1      | 0.12%   |
| Teclast             | 1        | 1      | 0.12%   |
| SPCC                | 1        | 1      | 0.12%   |
| ShiJi               | 1        | 1      | 0.12%   |
| PNY                 | 1        | 1      | 0.12%   |
| Plextor             | 1        | 2      | 0.12%   |
| LITEON              | 1        | 1      | 0.12%   |
| Hypertec            | 1        | 1      | 0.12%   |
| HP Phison           | 1        | 1      | 0.12%   |
| Fujitsu             | 1        | 2      | 0.12%   |
| ASMT                | 1        | 2      | 0.12%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 247      | 348    | 39.14%  |
| WDC                 | 220      | 302    | 34.87%  |
| Hitachi             | 55       | 77     | 8.72%   |
| Samsung Electronics | 44       | 49     | 6.97%   |
| Toshiba             | 37       | 47     | 5.86%   |
| Maxtor              | 14       | 15     | 2.22%   |
| HGST                | 9        | 10     | 1.43%   |
| Hewlett-Packard     | 2        | 3      | 0.32%   |
| Unknown             | 1        | 1      | 0.16%   |
| Fujitsu             | 1        | 2      | 0.16%   |
| ASMT                | 1        | 2      | 0.16%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 573      | 856    | 77.22%  |
| SSD  | 150      | 182    | 20.22%  |
| NVMe | 19       | 25     | 2.56%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Desktops | Drives | Percent |
|--------------------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                  | 2        | 3      | 11.76%  |
| WDC WD4001FFSX-68JNUN0 4TB                       | 1        | 1      | 5.88%   |
| WDC WD30EZRS-00J99B0 3TB                         | 1        | 1      | 5.88%   |
| Seagate ST500DM005 HD502HJ 500GB                 | 1        | 1      | 5.88%   |
| Seagate ST3500830AS 500GB                        | 1        | 1      | 5.88%   |
| Seagate ST3500630A 500GB                         | 1        | 1      | 5.88%   |
| Samsung Electronics SSD 980 1TB                  | 1        | 1      | 5.88%   |
| Samsung Electronics SP0802N 80GB                 | 1        | 1      | 5.88%   |
| Samsung Electronics MZ7LN512HAJQ-00000 512GB SSD | 1        | 2      | 5.88%   |
| Samsung Electronics HD253GJ 250GB                | 1        | 1      | 5.88%   |
| Samsung Electronics HD103SJ 1TB                  | 1        | 1      | 5.88%   |
| Inland SATA SSD 128GB                            | 1        | 1      | 5.88%   |
| HGST HUH728080ALN600 8TB                         | 1        | 1      | 5.88%   |
| HGST HDN724040ALE640 4TB                         | 1        | 1      | 5.88%   |
| Hewlett-Packard SSD S700 500GB                   | 1        | 2      | 5.88%   |
| Crucial CT1000P1SSD8 1TB                         | 1        | 1      | 5.88%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5        | 6      | 29.41%  |
| Samsung Electronics | 5        | 6      | 29.41%  |
| WDC                 | 2        | 2      | 11.76%  |
| HGST                | 2        | 2      | 11.76%  |
| Inland              | 1        | 1      | 5.88%   |
| Hewlett-Packard     | 1        | 2      | 5.88%   |
| Crucial             | 1        | 1      | 5.88%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 2570     | 6500   | 60.86%  |
| Detected | 927      | 2631   | 21.95%  |
| Malfunc  | 708      | 1063   | 16.77%  |
| Failed   | 17       | 20     | 0.4%    |
| Limited  | 1        | 1      | 0.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 2370     | 47.31%  |
| AMD                              | 1040     | 20.76%  |
| Samsung Electronics              | 363      | 7.25%   |
| ASMedia Technology               | 190      | 3.79%   |
| Marvell Technology Group         | 140      | 2.79%   |
| SanDisk                          | 131      | 2.62%   |
| Phison Electronics               | 117      | 2.34%   |
| JMicron Technology               | 101      | 2.02%   |
| Nvidia                           | 87       | 1.74%   |
| Kingston Technology Company      | 56       | 1.12%   |
| Micron/Crucial Technology        | 50       | 1%      |
| LSI Logic / Symbios Logic        | 45       | 0.9%    |
| VIA Technologies                 | 43       | 0.86%   |
| Silicon Motion                   | 40       | 0.8%    |
| ADATA Technology                 | 37       | 0.74%   |
| Broadcom / LSI                   | 34       | 0.68%   |
| Silicon Image                    | 20       | 0.4%    |
| Toshiba America Info Systems     | 15       | 0.3%    |
| SK hynix                         | 15       | 0.3%    |
| Adaptec                          | 15       | 0.3%    |
| Micron Technology                | 13       | 0.26%   |
| Realtek Semiconductor            | 11       | 0.22%   |
| KIOXIA                           | 11       | 0.22%   |
| Seagate Technology               | 10       | 0.2%    |
| Lite-On Technology               | 9        | 0.18%   |
| MAXIO Technology (Hangzhou)      | 7        | 0.14%   |
| IBM                              | 5        | 0.1%    |
| Hewlett-Packard                  | 5        | 0.1%    |
| Silicon Integrated Systems [SiS] | 4        | 0.08%   |
| Integrated Technology Express    | 4        | 0.08%   |
| INNOGRIT                         | 3        | 0.06%   |
| Mylex                            | 2        | 0.04%   |
| HighPoint Technologies           | 2        | 0.04%   |
| Biwin Storage Technology         | 2        | 0.04%   |
| 3ware                            | 2        | 0.04%   |
| ULi Electronics                  | 1        | 0.02%   |
| Tekram Technology                | 1        | 0.02%   |
| Shenzhen Longsys Electronics     | 1        | 0.02%   |
| OCZ Technology Group             | 1        | 0.02%   |
| Netac Technology                 | 1        | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 620      | 9.81%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 287      | 4.54%   |
| AMD 400 Series Chipset SATA Controller                                                  | 230      | 3.64%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 218      | 3.45%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 185      | 2.93%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 184      | 2.91%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 183      | 2.9%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 172      | 2.72%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 168      | 2.66%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 145      | 2.3%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 143      | 2.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 139      | 2.2%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 120      | 1.9%    |
| AMD 500 Series Chipset SATA Controller                                                  | 120      | 1.9%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 89       | 1.41%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 88       | 1.39%   |
| Intel SATA Controller [RAID mode]                                                       | 87       | 1.38%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 87       | 1.38%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 83       | 1.31%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 77       | 1.22%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 69       | 1.09%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 64       | 1.01%   |
| Phison E12 NVMe Controller                                                              | 59       | 0.93%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 55       | 0.87%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 55       | 0.87%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 55       | 0.87%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 55       | 0.87%   |
| AMD FCH SATA Controller D                                                               | 51       | 0.81%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 50       | 0.79%   |
| Nvidia MCP61 SATA Controller                                                            | 47       | 0.74%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 46       | 0.73%   |
| AMD 300 Series Chipset SATA Controller                                                  | 46       | 0.73%   |
| Nvidia MCP61 IDE                                                                        | 42       | 0.66%   |
| AMD X370 Series Chipset SATA Controller                                                 | 41       | 0.65%   |
| Samsung NVMe SSD Controller 980                                                         | 38       | 0.6%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 38       | 0.6%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 37       | 0.59%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 37       | 0.59%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 35       | 0.55%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 33       | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 2858     | 57.69%  |
| IDE  | 909      | 18.35%  |
| NVMe | 858      | 17.32%  |
| RAID | 219      | 4.42%   |
| SAS  | 79       | 1.59%   |
| SCSI | 31       | 0.63%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 2395     | 67.26%  |
| AMD                   | 1133     | 31.82%  |
| Unknown               | 7        | 0.2%    |
| CentaurHauls          | 6        | 0.17%   |
| CHRP IBM,8233-E8B     | 5        | 0.14%   |
| ARM                   | 5        | 0.14%   |
| sifive,bullet0        | 3        | 0.08%   |
| sifive,u74-mc         | 2        | 0.06%   |
| CHRP IBM,9131-52A     | 2        | 0.06%   |
| PowerNV FP5466G2      | 1        | 0.03%   |
| PowerNV C829UAG3      | 1        | 0.03%   |
| Marvell Semiconductor | 1        | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-9400 CPU @ 2.90GHz            | 64       | 1.79%   |
| AMD Ryzen 5 3600 6-Core Processor           | 60       | 1.68%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 40       | 1.12%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 38       | 1.07%   |
| Intel Pentium CPU G3420 @ 3.20GHz           | 37       | 1.04%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 34       | 0.95%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 34       | 0.95%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 33       | 0.92%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 32       | 0.9%    |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 31       | 0.87%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 30       | 0.84%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 29       | 0.81%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 29       | 0.81%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 29       | 0.81%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 29       | 0.81%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 29       | 0.81%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 28       | 0.78%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 28       | 0.78%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 28       | 0.78%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 27       | 0.76%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 27       | 0.76%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 27       | 0.76%   |
| AMD FX-8350 Eight-Core Processor            | 27       | 0.76%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 25       | 0.7%    |
| AMD Ryzen 7 2700X Eight-Core Processor      | 25       | 0.7%    |
| Intel Pentium CPU G3220 @ 3.00GHz           | 24       | 0.67%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 23       | 0.64%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 22       | 0.62%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 22       | 0.62%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 22       | 0.62%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 22       | 0.62%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 22       | 0.62%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 22       | 0.62%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 21       | 0.59%   |
| Intel Celeron N5105 @ 2.00GHz               | 21       | 0.59%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 20       | 0.56%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 20       | 0.56%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 20       | 0.56%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 20       | 0.56%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 19       | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 550      | 15.43%  |
| Intel Core i7           | 355      | 9.96%   |
| Intel Core i3           | 307      | 8.61%   |
| AMD Ryzen 5             | 250      | 7.01%   |
| Intel Xeon              | 228      | 6.4%    |
| AMD Ryzen 7             | 198      | 5.55%   |
| Intel Celeron           | 196      | 5.5%    |
| Intel Pentium           | 193      | 5.41%   |
| Intel Core 2 Duo        | 143      | 4.01%   |
| Other                   | 139      | 3.9%    |
| AMD Ryzen 9             | 115      | 3.23%   |
| AMD FX                  | 114      | 3.2%    |
| Intel Pentium Dual-Core | 66       | 1.85%   |
| Intel Core 2 Quad       | 62       | 1.74%   |
| AMD Ryzen 3             | 56       | 1.57%   |
| AMD Ryzen Threadripper  | 37       | 1.04%   |
| Intel Atom              | 35       | 0.98%   |
| Intel Core i9           | 32       | 0.9%    |
| AMD Phenom II X4        | 32       | 0.9%    |
| AMD Athlon II X2        | 32       | 0.9%    |
| AMD Athlon 64 X2        | 31       | 0.87%   |
| AMD A10                 | 28       | 0.79%   |
| Intel Core 2            | 27       | 0.76%   |
| AMD Athlon              | 27       | 0.76%   |
| Intel Pentium 4         | 26       | 0.73%   |
| Intel Pentium Gold      | 25       | 0.7%    |
| AMD A8                  | 25       | 0.7%    |
| AMD Phenom II X6        | 17       | 0.48%   |
| AMD GX                  | 16       | 0.45%   |
| Intel Pentium Dual      | 15       | 0.42%   |
| AMD Ryzen 5 PRO         | 15       | 0.42%   |
| AMD Sempron             | 13       | 0.36%   |
| AMD Athlon II X4        | 13       | 0.36%   |
| Intel Pentium D         | 11       | 0.31%   |
| AMD Phenom              | 11       | 0.31%   |
| Intel Pentium Silver    | 10       | 0.28%   |
| AMD Athlon 64           | 10       | 0.28%   |
| AMD E                   | 9        | 0.25%   |
| AMD A6                  | 9        | 0.25%   |
| AMD A4                  | 9        | 0.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 1215     | 34.05%  |
| 2       | 1072     | 30.04%  |
| 6       | 506      | 14.18%  |
| 8       | 338      | 9.47%   |
| 1       | 120      | 3.36%   |
| 16      | 101      | 2.83%   |
| 12      | 99       | 2.77%   |
| 3       | 40       | 1.12%   |
| 10      | 26       | 0.73%   |
| 32      | 13       | 0.36%   |
| 24      | 11       | 0.31%   |
| Unknown | 8        | 0.22%   |
| 18      | 4        | 0.11%   |
| 64      | 3        | 0.08%   |
| 44      | 3        | 0.08%   |
| 20      | 3        | 0.08%   |
| 22      | 2        | 0.06%   |
| 14      | 2        | 0.06%   |
| 36      | 1        | 0.03%   |
| 28      | 1        | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 3490     | 97.95%  |
| 2       | 64       | 1.8%    |
| Unknown | 8        | 0.22%   |
| 16      | 1        | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 1892     | 53.06%  |
| 1       | 1659     | 46.52%  |
| Unknown | 8        | 0.22%   |
| 4       | 6        | 0.17%   |
| 8       | 1        | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 3450     | 96.72%  |
| Unknown        | 79       | 2.21%   |
| 32-bit         | 38       | 1.07%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 798      | 21.81%  |
| 0x306c3    | 296      | 8.09%   |
| 0x206a7    | 187      | 5.11%   |
| 0x1067a    | 176      | 4.81%   |
| 0x306a9    | 173      | 4.73%   |
| 0x506e3    | 134      | 3.66%   |
| 0x906ea    | 126      | 3.44%   |
| 0x08701021 | 117      | 3.2%    |
| 0xa0653    | 80       | 2.19%   |
| 0x906e9    | 71       | 1.94%   |
| 0x0800820d | 64       | 1.75%   |
| 0x0a201016 | 53       | 1.45%   |
| 0xa0655    | 51       | 1.39%   |
| 0x08108109 | 50       | 1.37%   |
| 0x08701013 | 40       | 1.09%   |
| 0x010000c8 | 40       | 1.09%   |
| 0xa0671    | 38       | 1.04%   |
| 0x906c0    | 36       | 0.98%   |
| 0x90672    | 31       | 0.85%   |
| 0x206d7    | 30       | 0.82%   |
| 0x906ed    | 28       | 0.77%   |
| 0x6fd      | 28       | 0.77%   |
| 0x08101016 | 28       | 0.77%   |
| 0x08001137 | 28       | 0.77%   |
| 0x06000852 | 28       | 0.77%   |
| 0x06003106 | 27       | 0.74%   |
| 0x306f2    | 26       | 0.71%   |
| 0x306e4    | 25       | 0.68%   |
| 0x906eb    | 24       | 0.66%   |
| 0x6fb      | 24       | 0.66%   |
| 0x0a201009 | 21       | 0.57%   |
| 0x08001138 | 21       | 0.57%   |
| 0x0a50000c | 20       | 0.55%   |
| 0x206c2    | 19       | 0.52%   |
| 0x10676    | 19       | 0.52%   |
| 0x106a5    | 18       | 0.49%   |
| 0x08600106 | 18       | 0.49%   |
| 0x06001119 | 18       | 0.49%   |
| 0x20655    | 17       | 0.46%   |
| 0x06000822 | 17       | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 420      | 11.77%  |
| KabyLake         | 321      | 9%      |
| SandyBridge      | 264      | 7.4%    |
| Penryn           | 244      | 6.84%   |
| IvyBridge        | 241      | 6.76%   |
| Zen 2            | 227      | 6.36%   |
| Skylake          | 185      | 5.19%   |
| Zen+             | 171      | 4.79%   |
| Zen 3            | 164      | 4.6%    |
| CometLake        | 148      | 4.15%   |
| K10              | 130      | 3.64%   |
| Zen              | 123      | 3.45%   |
| Unknown          | 118      | 3.31%   |
| Piledriver       | 110      | 3.08%   |
| Core             | 110      | 3.08%   |
| Westmere         | 59       | 1.65%   |
| Silvermont       | 55       | 1.54%   |
| K8 Hammer        | 54       | 1.51%   |
| Nehalem          | 47       | 1.32%   |
| NetBurst         | 46       | 1.29%   |
| Tremont          | 40       | 1.12%   |
| Steamroller      | 35       | 0.98%   |
| Goldmont plus    | 31       | 0.87%   |
| Alderlake Hybrid | 31       | 0.87%   |
| Bulldozer        | 29       | 0.81%   |
| Bonnell          | 26       | 0.73%   |
| Goldmont         | 24       | 0.67%   |
| Broadwell        | 21       | 0.59%   |
| Jaguar           | 17       | 0.48%   |
| Excavator        | 17       | 0.48%   |
| Bobcat           | 16       | 0.45%   |
| Icelake          | 12       | 0.34%   |
| Puma             | 10       | 0.28%   |
| K6               | 6        | 0.17%   |
| P6               | 5        | 0.14%   |
| K10 Llano        | 5        | 0.14%   |
| TigerLake        | 4        | 0.11%   |
| Geode            | 1        | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1453     | 38.59%  |
| Nvidia                           | 1247     | 33.12%  |
| AMD                              | 945      | 25.1%   |
| ASPEED Technology                | 62       | 1.65%   |
| Matrox Electronics Systems       | 41       | 1.09%   |
| VIA Technologies                 | 10       | 0.27%   |
| Silicon Integrated Systems [SiS] | 2        | 0.05%   |
| Silicon Motion                   | 1        | 0.03%   |
| Loongson Technology              | 1        | 0.03%   |
| Cirrus Logic                     | 1        | 0.03%   |
| ATI Technologies                 | 1        | 0.03%   |
| 3DLabs                           | 1        | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 207      | 5.36%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 136      | 3.52%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 131      | 3.39%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 124      | 3.21%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 95       | 2.46%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 85       | 2.2%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 85       | 2.2%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 77       | 2%      |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 73       | 1.89%   |
| Intel HD Graphics 530                                                                    | 68       | 1.76%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 68       | 1.76%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 62       | 1.61%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 60       | 1.55%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 57       | 1.48%   |
| Intel HD Graphics 630                                                                    | 49       | 1.27%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 45       | 1.17%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 45       | 1.17%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 44       | 1.14%   |
| Nvidia GT218 [GeForce 210]                                                               | 42       | 1.09%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 41       | 1.06%   |
| Intel JasperLake [UHD Graphics]                                                          | 38       | 0.98%   |
| Intel HD Graphics 510                                                                    | 38       | 0.98%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 34       | 0.88%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 34       | 0.88%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 33       | 0.86%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 32       | 0.83%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 31       | 0.8%    |
| Nvidia GM204 [GeForce GTX 970]                                                           | 30       | 0.78%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 29       | 0.75%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 28       | 0.73%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 28       | 0.73%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 27       | 0.7%    |
| Nvidia GM206 [GeForce GTX 960]                                                           | 26       | 0.67%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 26       | 0.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 25       | 0.65%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 25       | 0.65%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 23       | 0.6%    |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 23       | 0.6%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 22       | 0.57%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 22       | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| 1 x Intel                         | 1306     | 36.23%  |
| 1 x Nvidia                        | 1138     | 31.57%  |
| 1 x AMD                           | 844      | 23.41%  |
| Intel + Nvidia                    | 55       | 1.53%   |
| 1 x ASPEED                        | 46       | 1.28%   |
| 2 x AMD                           | 42       | 1.17%   |
| 1 x Matrox                        | 39       | 1.08%   |
| Other                             | 33       | 0.92%   |
| AMD + Nvidia                      | 26       | 0.72%   |
| Intel + AMD                       | 20       | 0.55%   |
| 2 x Nvidia                        | 14       | 0.39%   |
| 1 x VIA                           | 10       | 0.28%   |
| Nvidia + ASPEED                   | 9        | 0.25%   |
| AMD + ASPEED                      | 5        | 0.14%   |
| AMD + Matrox                      | 4        | 0.11%   |
| Intel + 2 x Nvidia                | 3        | 0.08%   |
| 2 x Intel                         | 2        | 0.06%   |
| 1 x SiS                           | 2        | 0.06%   |
| 3 x AMD                           | 1        | 0.03%   |
| 2 x Nvidia + 1 x ASPEED           | 1        | 0.03%   |
| 2 x Loongson Technology           | 1        | 0.03%   |
| 2 x AMD + 1 x Nvidia + 1 x ASPEED | 1        | 0.03%   |
| 1 x Silicon Motion                | 1        | 0.03%   |
| 1 x Cirrus Logic                  | 1        | 0.03%   |
| AMD + 3DLabs                      | 1        | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 2031     | 56.34%  |
| Unknown     | 937      | 25.99%  |
| Proprietary | 637      | 17.67%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 2177     | 59.74%  |
| 1.01-2.0   | 338      | 9.28%   |
| 0.51-1.0   | 265      | 7.27%   |
| 0.01-0.5   | 232      | 6.37%   |
| 3.01-4.0   | 221      | 6.06%   |
| 7.01-8.0   | 201      | 5.52%   |
| 5.01-6.0   | 100      | 2.74%   |
| 8.01-16.0  | 54       | 1.48%   |
| 2.01-3.0   | 38       | 1.04%   |
| 16.01-24.0 | 13       | 0.36%   |
| 4.01-5.0   | 4        | 0.11%   |
| 24.01-32.0 | 1        | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 449      | 15.81%  |
| Dell                 | 336      | 11.83%  |
| Goldstar             | 273      | 9.61%   |
| Acer                 | 183      | 6.44%   |
| Hewlett-Packard      | 180      | 6.34%   |
| BenQ                 | 178      | 6.27%   |
| Philips              | 151      | 5.32%   |
| AOC                  | 141      | 4.96%   |
| Ancor Communications | 118      | 4.15%   |
| Iiyama               | 72       | 2.54%   |
| Unknown              | 62       | 2.18%   |
| ViewSonic            | 61       | 2.15%   |
| LG Electronics       | 43       | 1.51%   |
| ASUSTek Computer     | 43       | 1.51%   |
| Lenovo               | 41       | 1.44%   |
| Eizo                 | 33       | 1.16%   |
| Sony                 | 26       | 0.92%   |
| NEC Computers        | 23       | 0.81%   |
| Fujitsu Siemens      | 17       | 0.6%    |
| Medion               | 16       | 0.56%   |
| Unknown              | 16       | 0.56%   |
| Vestel Elektronik    | 13       | 0.46%   |
| Vizio                | 12       | 0.42%   |
| MSI                  | 10       | 0.35%   |
| Belinea              | 10       | 0.35%   |
| Idek Iiyama          | 9        | 0.32%   |
| HPN                  | 9        | 0.32%   |
| Toshiba              | 8        | 0.28%   |
| Hitachi              | 8        | 0.28%   |
| HannStar             | 8        | 0.28%   |
| Sceptre Tech         | 7        | 0.25%   |
| Panasonic            | 7        | 0.25%   |
| Apple                | 7        | 0.25%   |
| ONN                  | 6        | 0.21%   |
| Lenovo Group Limited | 6        | 0.21%   |
| CHR                  | 6        | 0.21%   |
| AUS                  | 6        | 0.21%   |
| Targa Visionary      | 5        | 0.18%   |
| RTK                  | 5        | 0.18%   |
| ___                  | 4        | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 28       | 0.92%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 25       | 0.82%   |
| Unknown                                                                | 16       | 0.53%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 13       | 0.43%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 12       | 0.39%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 10       | 0.33%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch      | 9        | 0.3%    |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch   | 9        | 0.3%    |
| Samsung Electronics LCD Monitor SyncMaster                             | 9        | 0.3%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 9        | 0.3%    |
| BenQ PD2700U BNQ802E 3840x2160 597x336mm 27.0-inch                     | 9        | 0.3%    |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 8        | 0.26%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 8        | 0.26%   |
| ViewSonic VG730m VSC951E 1280x1024 338x270mm 17.0-inch                 | 7        | 0.23%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch   | 7        | 0.23%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 7        | 0.23%   |
| Philips 190SW PHL086D 1440x900 408x255mm 18.9-inch                     | 7        | 0.23%   |
| Dell U2518D DEL413A 2560x1440 553x311mm 25.0-inch                      | 7        | 0.23%   |
| BenQ LCD BNQ801B 2560x1440 527x296mm 23.8-inch                         | 7        | 0.23%   |
| Ancor Communications VE228 ACI22FA 1920x1080 477x268mm 21.5-inch       | 7        | 0.23%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 6        | 0.2%    |
| Dell U2414H DELA0A4 1920x1080 527x296mm 23.8-inch                      | 6        | 0.2%    |
| CHR CH7511B CHR7511 1920x1080 519x324mm 24.1-inch                      | 6        | 0.2%    |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                      | 6        | 0.2%    |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                      | 6        | 0.2%    |
| BenQ G2220HD BNQ7821 1920x1080 477x268mm 21.5-inch                     | 6        | 0.2%    |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                        | 6        | 0.2%    |
| AOC 1950W AOC1950 1366x768 410x230mm 18.5-inch                         | 6        | 0.2%    |
| Ancor Communications VE248 ACI2494 1920x1080 531x299mm 24.0-inch       | 6        | 0.2%    |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch  | 6        | 0.2%    |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch  | 6        | 0.2%    |
| Unknown LCD Monitor SAMSUNG 3840x2160                                  | 5        | 0.16%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch   | 5        | 0.16%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch               | 5        | 0.16%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                | 5        | 0.16%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                | 5        | 0.16%   |
| Goldstar W2243 GSM56FE 1920x1080 477x268mm 21.5-inch                   | 5        | 0.16%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                    | 5        | 0.16%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                | 5        | 0.16%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                  | 5        | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1144     | 40.58%  |
| 3840x2160 (4K)     | 258      | 9.15%   |
| 1280x1024 (SXGA)   | 252      | 8.94%   |
| 2560x1440 (QHD)    | 203      | 7.2%    |
| 1680x1050 (WSXGA+) | 151      | 5.36%   |
| 1920x1200 (WUXGA)  | 107      | 3.8%    |
| Unknown            | 106      | 3.76%   |
| 1366x768 (WXGA)    | 92       | 3.26%   |
| 1440x900 (WXGA+)   | 75       | 2.66%   |
| 1600x900 (HD+)     | 74       | 2.63%   |
| 2560x1080          | 50       | 1.77%   |
| 3440x1440          | 42       | 1.49%   |
| 3840x1080          | 35       | 1.24%   |
| 1360x768           | 32       | 1.14%   |
| 2288x1287          | 30       | 1.06%   |
| 1600x1200          | 27       | 0.96%   |
| 1024x768 (XGA)     | 27       | 0.96%   |
| 1920x540           | 13       | 0.46%   |
| 2560x1600          | 9        | 0.32%   |
| 4480x1440          | 8        | 0.28%   |
| 3200x1080          | 7        | 0.25%   |
| 5760x2160          | 6        | 0.21%   |
| 5760x1080          | 6        | 0.21%   |
| 1280x720 (HD)      | 6        | 0.21%   |
| 7680x2160          | 4        | 0.14%   |
| 3840x1600          | 4        | 0.14%   |
| 3840x1200          | 3        | 0.11%   |
| 3360x1050          | 3        | 0.11%   |
| 1400x1050          | 3        | 0.11%   |
| 6400x2160          | 2        | 0.07%   |
| 5760x1200          | 2        | 0.07%   |
| 5360x1440          | 2        | 0.07%   |
| 2560x1024          | 2        | 0.07%   |
| 2048x1536          | 2        | 0.07%   |
| 2048x1152          | 2        | 0.07%   |
| 1280x800 (WXGA)    | 2        | 0.07%   |
| 7680x4320          | 1        | 0.04%   |
| 7680x1440          | 1        | 0.04%   |
| 6400x1440          | 1        | 0.04%   |
| 6160x1440          | 1        | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 394      | 14.09%  |
| 27      | 353      | 12.62%  |
| 23      | 331      | 11.83%  |
| Unknown | 311      | 11.12%  |
| 21      | 269      | 9.62%   |
| 19      | 189      | 6.76%   |
| 17      | 120      | 4.29%   |
| 18      | 107      | 3.83%   |
| 22      | 98       | 3.5%    |
| 31      | 94       | 3.36%   |
| 20      | 87       | 3.11%   |
| 34      | 70       | 2.5%    |
| 15      | 58       | 2.07%   |
| 84      | 40       | 1.43%   |
| 25      | 31       | 1.11%   |
| 142     | 28       | 1%      |
| 72      | 25       | 0.89%   |
| 32      | 22       | 0.79%   |
| 54      | 19       | 0.68%   |
| 26      | 19       | 0.68%   |
| 40      | 16       | 0.57%   |
| 28      | 11       | 0.39%   |
| 52      | 10       | 0.36%   |
| 29      | 10       | 0.36%   |
| 48      | 7        | 0.25%   |
| 65      | 6        | 0.21%   |
| 39      | 6        | 0.21%   |
| 16      | 6        | 0.21%   |
| 43      | 5        | 0.18%   |
| 42      | 5        | 0.18%   |
| 35      | 5        | 0.18%   |
| 13      | 5        | 0.18%   |
| 37      | 4        | 0.14%   |
| 36      | 4        | 0.14%   |
| 75      | 3        | 0.11%   |
| 38      | 3        | 0.11%   |
| 33      | 3        | 0.11%   |
| 55      | 2        | 0.07%   |
| 49      | 2        | 0.07%   |
| 47      | 2        | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 1002     | 36.92%  |
| 401-500        | 623      | 22.96%  |
| Unknown        | 311      | 11.46%  |
| 301-350        | 172      | 6.34%   |
| 601-700        | 164      | 6.04%   |
| 351-400        | 136      | 5.01%   |
| 701-800        | 97       | 3.57%   |
| 1501-2000      | 69       | 2.54%   |
| 1001-1500      | 55       | 2.03%   |
| 801-900        | 33       | 1.22%   |
| More than 2000 | 29       | 1.07%   |
| 901-1000       | 11       | 0.41%   |
| 201-300        | 10       | 0.37%   |
| 101-200        | 2        | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 1536     | 58.65%  |
| 16/10   | 340      | 12.98%  |
| Unknown | 276      | 10.54%  |
| 5/4     | 231      | 8.82%   |
| 21/9    | 86       | 3.28%   |
| 4/3     | 71       | 2.71%   |
| 1.00    | 30       | 1.15%   |
| 3/2     | 23       | 0.88%   |
| 6/5     | 13       | 0.5%    |
| 32/9    | 6        | 0.23%   |
| 2.00    | 2        | 0.08%   |
| 1.96    | 2        | 0.08%   |
| 2.65    | 1        | 0.04%   |
| 11/10   | 1        | 0.04%   |
| 0.56    | 1        | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 872      | 31.81%  |
| 301-350        | 364      | 13.28%  |
| 151-200        | 357      | 13.02%  |
| Unknown        | 311      | 11.35%  |
| 351-500        | 209      | 7.62%   |
| 141-150        | 186      | 6.79%   |
| 251-300        | 165      | 6.02%   |
| More than 1000 | 144      | 5.25%   |
| 501-1000       | 50       | 1.82%   |
| 101-110        | 48       | 1.75%   |
| 131-140        | 10       | 0.36%   |
| 111-120        | 9        | 0.33%   |
| 71-80          | 5        | 0.18%   |
| 121-130        | 5        | 0.18%   |
| 81-90          | 2        | 0.07%   |
| 1-40           | 2        | 0.07%   |
| 41-50          | 1        | 0.04%   |
| 91-100         | 1        | 0.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 1573     | 60.18%  |
| 101-120       | 443      | 16.95%  |
| Unknown       | 312      | 11.94%  |
| 121-160       | 123      | 4.71%   |
| 1-50          | 107      | 4.09%   |
| 161-240       | 53       | 2.03%   |
| More than 240 | 3        | 0.11%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1976     | 54.62%  |
| 0     | 1106     | 30.57%  |
| 2     | 479      | 13.24%  |
| 3     | 53       | 1.46%   |
| 4     | 4        | 0.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 2177     | 45.53%  |
| Intel                             | 1439     | 30.1%   |
| Qualcomm Atheros                  | 275      | 5.75%   |
| Broadcom                          | 136      | 2.84%   |
| Ralink Technology                 | 86       | 1.8%    |
| Nvidia                            | 73       | 1.53%   |
| TP-Link                           | 50       | 1.05%   |
| Ralink                            | 39       | 0.82%   |
| Broadcom Limited                  | 35       | 0.73%   |
| MediaTek                          | 34       | 0.71%   |
| Marvell Technology Group          | 32       | 0.67%   |
| Aquantia                          | 31       | 0.65%   |
| D-Link System                     | 23       | 0.48%   |
| Mellanox Technologies             | 20       | 0.42%   |
| ASIX Electronics                  | 20       | 0.42%   |
| Qualcomm Atheros Communications   | 19       | 0.4%    |
| Samsung Electronics               | 18       | 0.38%   |
| VIA Technologies                  | 16       | 0.33%   |
| Microsoft                         | 15       | 0.31%   |
| Huawei Technologies               | 14       | 0.29%   |
| ASUSTek Computer                  | 14       | 0.29%   |
| D-Link                            | 13       | 0.27%   |
| NetGear                           | 11       | 0.23%   |
| American Megatrends               | 10       | 0.21%   |
| Edimax Technology                 | 9        | 0.19%   |
| 3Com                              | 9        | 0.19%   |
| Gemtek                            | 7        | 0.15%   |
| Xiaomi                            | 6        | 0.13%   |
| Sigma Designs                     | 6        | 0.13%   |
| Belkin Components                 | 6        | 0.13%   |
| Sundance Technology Inc / IC Plus | 5        | 0.1%    |
| IMC Networks                      | 5        | 0.1%    |
| IBM                               | 5        | 0.1%    |
| Texas Instruments                 | 4        | 0.08%   |
| Silicon Integrated Systems [SiS]  | 4        | 0.08%   |
| QLogic                            | 4        | 0.08%   |
| Linksys                           | 4        | 0.08%   |
| Dresden Elektronik                | 4        | 0.08%   |
| DisplayLink                       | 4        | 0.08%   |
| ZTE WCDMA Technologies MSM        | 3        | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1772     | 33.17%  |
| Intel I211 Gigabit Network Connection                             | 195      | 3.65%   |
| Realtek RTL8125 2.5GbE Controller                                 | 158      | 2.96%   |
| Intel Wi-Fi 6 AX200                                               | 118      | 2.21%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 113      | 2.12%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 106      | 1.98%   |
| Intel Ethernet Connection (2) I219-V                              | 103      | 1.93%   |
| Intel Ethernet Controller I225-V                                  | 81       | 1.52%   |
| Intel I210 Gigabit Network Connection                             | 68       | 1.27%   |
| Intel 82579V Gigabit Network Connection                           | 65       | 1.22%   |
| Intel Ethernet Connection I217-LM                                 | 63       | 1.18%   |
| Intel 82574L Gigabit Network Connection                           | 58       | 1.09%   |
| Intel Ethernet Connection (7) I219-V                              | 50       | 0.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 49       | 0.92%   |
| Nvidia MCP61 Ethernet                                             | 44       | 0.82%   |
| Intel Ethernet Connection (14) I219-V                             | 42       | 0.79%   |
| Intel Wireless 3165                                               | 41       | 0.77%   |
| Intel Ethernet Connection I217-V                                  | 41       | 0.77%   |
| Intel Wireless-AC 9260                                            | 40       | 0.75%   |
| Intel Ethernet Connection (2) I218-V                              | 40       | 0.75%   |
| Intel Ethernet Connection (2) I219-LM                             | 38       | 0.71%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 34       | 0.64%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 33       | 0.62%   |
| Ralink MT7601U Wireless Adapter                                   | 33       | 0.62%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 33       | 0.62%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 33       | 0.62%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 29       | 0.54%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 27       | 0.51%   |
| Intel I350 Gigabit Network Connection                             | 26       | 0.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 25       | 0.47%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 22       | 0.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 22       | 0.41%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 21       | 0.39%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 21       | 0.39%   |
| Ralink RT5370 Wireless Adapter                                    | 21       | 0.39%   |
| Intel Wireless 7260                                               | 21       | 0.39%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 21       | 0.39%   |
| Realtek 802.11ac NIC                                              | 20       | 0.37%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 20       | 0.37%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 20       | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 428      | 36.64%  |
| Realtek Semiconductor                 | 231      | 19.78%  |
| Qualcomm Atheros                      | 135      | 11.56%  |
| Ralink Technology                     | 86       | 7.36%   |
| TP-Link                               | 46       | 3.94%   |
| Broadcom                              | 41       | 3.51%   |
| Ralink                                | 39       | 3.34%   |
| MediaTek                              | 31       | 2.65%   |
| Qualcomm Atheros Communications       | 19       | 1.63%   |
| ASUSTek Computer                      | 14       | 1.2%    |
| D-Link                                | 13       | 1.11%   |
| Microsoft                             | 12       | 1.03%   |
| D-Link System                         | 12       | 1.03%   |
| NetGear                               | 11       | 0.94%   |
| Edimax Technology                     | 9        | 0.77%   |
| Belkin Components                     | 6        | 0.51%   |
| IMC Networks                          | 5        | 0.43%   |
| Gemtek                                | 5        | 0.43%   |
| Broadcom Limited                      | 5        | 0.43%   |
| Linksys                               | 4        | 0.34%   |
| Wilocity                              | 2        | 0.17%   |
| Marvell Technology Group              | 2        | 0.17%   |
| AVM                                   | 2        | 0.17%   |
| ZyDAS                                 | 1        | 0.09%   |
| TRENDnet                              | 1        | 0.09%   |
| Tenda                                 | 1        | 0.09%   |
| Sitecom Europe                        | 1        | 0.09%   |
| PLANEX                                | 1        | 0.09%   |
| Micro Star International              | 1        | 0.09%   |
| Fiberline                             | 1        | 0.09%   |
| CyberTAN Technology                   | 1        | 0.09%   |
| BUFFALO                               | 1        | 0.09%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 118      | 10.03%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 49       | 4.16%   |
| Intel Wireless 3165                                            | 41       | 3.48%   |
| Intel Wireless-AC 9260                                         | 40       | 3.4%    |
| Ralink MT7601U Wireless Adapter                                | 33       | 2.8%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 33       | 2.8%    |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 27       | 2.29%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 25       | 2.12%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 22       | 1.87%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 21       | 1.78%   |
| Ralink RT5370 Wireless Adapter                                 | 21       | 1.78%   |
| Intel Wireless 7260                                            | 21       | 1.78%   |
| Realtek 802.11ac NIC                                           | 20       | 1.7%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 20       | 1.7%    |
| Intel Alder Lake-S PCH CNVi WiFi                               | 20       | 1.7%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 20       | 1.7%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 17       | 1.44%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 16       | 1.36%   |
| Qualcomm Atheros AR9271 802.11n                                | 16       | 1.36%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 15       | 1.27%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 15       | 1.27%   |
| Intel Wireless 7265                                            | 15       | 1.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 15       | 1.27%   |
| Intel Wireless 8260                                            | 13       | 1.1%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 13       | 1.1%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 12       | 1.02%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 12       | 1.02%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 12       | 1.02%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 10       | 0.85%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 10       | 0.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 10       | 0.85%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 10       | 0.85%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 9        | 0.76%   |
| Intel Wireless 8265 / 8275                                     | 9        | 0.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 8        | 0.68%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 8        | 0.68%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 7        | 0.59%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 7        | 0.59%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 7        | 0.59%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 7        | 0.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 2091     | 53.56%  |
| Intel                                  | 1212     | 31.05%  |
| Qualcomm Atheros                       | 152      | 3.89%   |
| Broadcom                               | 99       | 2.54%   |
| Nvidia                                 | 73       | 1.87%   |
| Marvell Technology Group               | 31       | 0.79%   |
| Aquantia                               | 31       | 0.79%   |
| Broadcom Limited                       | 30       | 0.77%   |
| ASIX Electronics                       | 20       | 0.51%   |
| Mellanox Technologies                  | 18       | 0.46%   |
| VIA Technologies                       | 16       | 0.41%   |
| Samsung Electronics                    | 13       | 0.33%   |
| D-Link System                          | 11       | 0.28%   |
| Huawei Technologies                    | 10       | 0.26%   |
| American Megatrends                    | 10       | 0.26%   |
| 3Com                                   | 9        | 0.23%   |
| Xiaomi                                 | 6        | 0.15%   |
| Sundance Technology Inc / IC Plus      | 5        | 0.13%   |
| IBM                                    | 5        | 0.13%   |
| TP-Link                                | 4        | 0.1%    |
| Silicon Integrated Systems [SiS]       | 4        | 0.1%    |
| QLogic                                 | 4        | 0.1%    |
| DisplayLink                            | 4        | 0.1%    |
| Qualcomm                               | 3        | 0.08%   |
| Microsoft                              | 3        | 0.08%   |
| Emulex                                 | 3        | 0.08%   |
| ZTE WCDMA Technologies MSM             | 2        | 0.05%   |
| SysKonnect                             | 2        | 0.05%   |
| Sony Ericsson Mobile Communications AB | 2        | 0.05%   |
| OPPO Electronics                       | 2        | 0.05%   |
| Motorola PCS                           | 2        | 0.05%   |
| MediaTek                               | 2        | 0.05%   |
| Lenovo                                 | 2        | 0.05%   |
| JMicron Technology                     | 2        | 0.05%   |
| ICS Advent                             | 2        | 0.05%   |
| Google                                 | 2        | 0.05%   |
| Gemtek                                 | 2        | 0.05%   |
| ADMtek                                 | 2        | 0.05%   |
| Tehuti Networks                        | 1        | 0.03%   |
| Spreadtrum Communications              | 1        | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1772     | 43.34%  |
| Intel I211 Gigabit Network Connection                             | 195      | 4.77%   |
| Realtek RTL8125 2.5GbE Controller                                 | 158      | 3.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 113      | 2.76%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 106      | 2.59%   |
| Intel Ethernet Connection (2) I219-V                              | 103      | 2.52%   |
| Intel Ethernet Controller I225-V                                  | 81       | 1.98%   |
| Intel I210 Gigabit Network Connection                             | 68       | 1.66%   |
| Intel 82579V Gigabit Network Connection                           | 65       | 1.59%   |
| Intel Ethernet Connection I217-LM                                 | 63       | 1.54%   |
| Intel 82574L Gigabit Network Connection                           | 58       | 1.42%   |
| Intel Ethernet Connection (7) I219-V                              | 50       | 1.22%   |
| Nvidia MCP61 Ethernet                                             | 44       | 1.08%   |
| Intel Ethernet Connection (14) I219-V                             | 42       | 1.03%   |
| Intel Ethernet Connection I217-V                                  | 41       | 1%      |
| Intel Ethernet Connection (2) I218-V                              | 40       | 0.98%   |
| Intel Ethernet Connection (2) I219-LM                             | 38       | 0.93%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 34       | 0.83%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 33       | 0.81%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 33       | 0.81%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 29       | 0.71%   |
| Intel I350 Gigabit Network Connection                             | 26       | 0.64%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 22       | 0.54%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 21       | 0.51%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 21       | 0.51%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 20       | 0.49%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 19       | 0.46%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 19       | 0.46%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 18       | 0.44%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 18       | 0.44%   |
| Intel Ethernet Controller X550                                    | 16       | 0.39%   |
| Intel Ethernet Connection (7) I219-LM                             | 15       | 0.37%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 14       | 0.34%   |
| Intel Ethernet Connection (5) I219-LM                             | 14       | 0.34%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 14       | 0.34%   |
| ASIX AX88179 Gigabit Ethernet                                     | 14       | 0.34%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 13       | 0.32%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 13       | 0.32%   |
| Mellanox MT27500 Family [ConnectX-3]                              | 11       | 0.27%   |
| Intel Ethernet Connection (2) I218-LM                             | 11       | 0.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 3532     | 75.09%  |
| WiFi     | 1100     | 23.38%  |
| Modem    | 65       | 1.38%   |
| Unknown  | 7        | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 3094     | 86.62%  |
| WiFi     | 477      | 13.35%  |
| Modem    | 1        | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 2303     | 64.31%  |
| 2     | 941      | 26.28%  |
| 3     | 205      | 5.72%   |
| 4     | 50       | 1.4%    |
| 0     | 28       | 0.78%   |
| 6     | 20       | 0.56%   |
| 5     | 20       | 0.56%   |
| 8     | 6        | 0.17%   |
| 9     | 2        | 0.06%   |
| 7     | 2        | 0.06%   |
| 21    | 1        | 0.03%   |
| 17    | 1        | 0.03%   |
| 13    | 1        | 0.03%   |
| 12    | 1        | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Desktops | Percent |
|---------|----------|---------|
| No      | 3059     | 84.88%  |
| Yes     | 544      | 15.09%  |
| Unknown | 1        | 0.03%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 405      | 44.26%  |
| Cambridge Silicon Radio         | 201      | 21.97%  |
| ASUSTek Computer                | 66       | 7.21%   |
| Realtek Semiconductor           | 63       | 6.89%   |
| Broadcom                        | 55       | 6.01%   |
| Qualcomm Atheros Communications | 36       | 3.93%   |
| MediaTek                        | 22       | 2.4%    |
| IMC Networks                    | 21       | 2.3%    |
| Apple                           | 9        | 0.98%   |
| TP-Link                         | 8        | 0.87%   |
| Foxconn / Hon Hai               | 5        | 0.55%   |
| Belkin Components               | 4        | 0.44%   |
| Lite-On Technology              | 3        | 0.33%   |
| Micro Star International        | 2        | 0.22%   |
| Integrated System Solution      | 2        | 0.22%   |
| Edimax Technology               | 2        | 0.22%   |
| Toshiba                         | 1        | 0.11%   |
| Sitecom Europe                  | 1        | 0.11%   |
| SINO WEALTH                     | 1        | 0.11%   |
| Realtek                         | 1        | 0.11%   |
| Qcom                            | 1        | 0.11%   |
| Microsoft                       | 1        | 0.11%   |
| Kensington                      | 1        | 0.11%   |
| Hewlett-Packard                 | 1        | 0.11%   |
| Dynex                           | 1        | 0.11%   |
| Com One                         | 1        | 0.11%   |
| Unknown                         | 1        | 0.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 201      | 21.94%  |
| Intel AX200 Bluetooth                                 | 116      | 12.66%  |
| Intel Bluetooth wireless interface                    | 99       | 10.81%  |
| Realtek Bluetooth Radio                               | 50       | 5.46%   |
| Intel Wireless-AC 3168 Bluetooth                      | 48       | 5.24%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 41       | 4.48%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 35       | 3.82%   |
| Intel AX201 Bluetooth                                 | 31       | 3.38%   |
| Intel AX210 Bluetooth                                 | 30       | 3.28%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 25       | 2.73%   |
| MediaTek Wireless_Device                              | 22       | 2.4%    |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 19       | 2.07%   |
| Qualcomm Atheros  Bluetooth Device                    | 17       | 1.86%   |
| IMC Networks Bluetooth Radio                          | 11       | 1.2%    |
| ASUS Bluetooth Adapter                                | 11       | 1.2%    |
| Intel Bluetooth Device                                | 10       | 1.09%   |
| ASUS Bluetooth Radio                                  | 10       | 1.09%   |
| TP-Link UB500 Adapter                                 | 8        | 0.87%   |
| ASUS ASUS USB-BT500                                   | 8        | 0.87%   |
| Realtek  Bluetooth 4.2 Adapter                        | 7        | 0.76%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 7        | 0.76%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 6        | 0.66%   |
| IMC Networks Bluetooth Device                         | 6        | 0.66%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 5        | 0.55%   |
| Broadcom BCM43142A0 Bluetooth 4.0                     | 5        | 0.55%   |
| Qualcomm Atheros Bluetooth USB Host Controller        | 4        | 0.44%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)       | 4        | 0.44%   |
| ASUS Qualcomm Bluetooth 4.1                           | 4        | 0.44%   |
| ASUS BCM20702A0                                       | 4        | 0.44%   |
| Apple Bluetooth Host Controller                       | 4        | 0.44%   |
| Realtek RTL8821A Bluetooth                            | 3        | 0.33%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 3        | 0.33%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 3        | 0.33%   |
| Foxconn / Hon Hai Wireless_Device                     | 3        | 0.33%   |
| Broadcom Bluetooth 3.0 Dongle                         | 3        | 0.33%   |
| ASUS Bluetooth Device                                 | 3        | 0.33%   |
| Realtek Bluetooth 5.1 Radio                           | 2        | 0.22%   |
| Lite-On Bluetooth Device                              | 2        | 0.22%   |
| IMC Networks Wireless_Device                          | 2        | 0.22%   |
| Broadcom HP Portable Bumble Bee                       | 2        | 0.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 2185     | 41.03%  |
| AMD                                          | 1276     | 23.96%  |
| Nvidia                                       | 1166     | 21.89%  |
| C-Media Electronics                          | 116      | 2.18%   |
| Creative Labs                                | 59       | 1.11%   |
| Logitech                                     | 54       | 1.01%   |
| ASUSTek Computer                             | 32       | 0.6%    |
| Texas Instruments                            | 25       | 0.47%   |
| GN Netcom                                    | 22       | 0.41%   |
| Generalplus Technology                       | 21       | 0.39%   |
| Micro Star International                     | 19       | 0.36%   |
| VIA Technologies                             | 18       | 0.34%   |
| Focusrite-Novation                           | 18       | 0.34%   |
| KTMicro                                      | 17       | 0.32%   |
| Kingston Technology                          | 17       | 0.32%   |
| JMTek                                        | 17       | 0.32%   |
| Creative Technology                          | 17       | 0.32%   |
| Plantronics                                  | 14       | 0.26%   |
| Dell                                         | 11       | 0.21%   |
| SteelSeries ApS                              | 10       | 0.19%   |
| GYROCOM C&C                                  | 9        | 0.17%   |
| BEHRINGER International                      | 9        | 0.17%   |
| RODE Microphones                             | 8        | 0.15%   |
| Corsair                                      | 8        | 0.15%   |
| Blue Microphones                             | 8        | 0.15%   |
| Razer USA                                    | 7        | 0.13%   |
| Yamaha                                       | 6        | 0.11%   |
| Realtek Semiconductor                        | 6        | 0.11%   |
| Tenx Technology                              | 5        | 0.09%   |
| Samson Technologies                          | 5        | 0.09%   |
| Microsoft                                    | 5        | 0.09%   |
| M-Audio                                      | 5        | 0.09%   |
| Giga-Byte Technology                         | 5        | 0.09%   |
| Cambridge Silicon Radio                      | 5        | 0.09%   |
| Zoran Co. Personal Media Division (Nogatech) | 4        | 0.08%   |
| Silicon Integrated Systems [SiS]             | 4        | 0.08%   |
| Sennheiser Communications                    | 4        | 0.08%   |
| Samsung Electronics                          | 4        | 0.08%   |
| Musical Fidelity                             | 4        | 0.08%   |
| XMOS                                         | 3        | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 303      | 4.87%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 300      | 4.82%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 258      | 4.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 239      | 3.84%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 217      | 3.49%   |
| Intel 200 Series PCH HD Audio                                              | 190      | 3.05%   |
| AMD Family 17h/19h HD Audio Controller                                     | 189      | 3.04%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 185      | 2.97%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 168      | 2.7%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 167      | 2.68%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 147      | 2.36%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 136      | 2.19%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 107      | 1.72%   |
| Nvidia GP107GL High Definition Audio Controller                            | 103      | 1.66%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 103      | 1.66%   |
| Nvidia GF108 High Definition Audio Controller                              | 98       | 1.58%   |
| AMD FCH Azalia Controller                                                  | 94       | 1.51%   |
| Intel Cannon Lake PCH cAVS                                                 | 88       | 1.41%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 79       | 1.27%   |
| Nvidia GP106 High Definition Audio Controller                              | 75       | 1.21%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 75       | 1.21%   |
| Nvidia High Definition Audio Controller                                    | 67       | 1.08%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 64       | 1.03%   |
| Intel Comet Lake PCH cAVS                                                  | 62       | 1%      |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 62       | 1%      |
| Intel C600/X79 series chipset High Definition Audio Controller             | 57       | 0.92%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 57       | 0.92%   |
| Nvidia TU116 High Definition Audio Controller                              | 56       | 0.9%    |
| Nvidia GP104 High Definition Audio Controller                              | 55       | 0.88%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 55       | 0.88%   |
| Nvidia TU106 High Definition Audio Controller                              | 51       | 0.82%   |
| Intel Alder Lake-S HD Audio Controller                                     | 50       | 0.8%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 50       | 0.8%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 49       | 0.79%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 47       | 0.76%   |
| Nvidia MCP61 High Definition Audio                                         | 45       | 0.72%   |
| Nvidia GP108 High Definition Audio Controller                              | 45       | 0.72%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 43       | 0.69%   |
| AMD Navi 10 HDMI Audio                                                     | 43       | 0.69%   |
| Nvidia GF119 HDMI Audio Controller                                         | 41       | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 622      | 18.79%  |
| Unknown                      | 535      | 16.16%  |
| Crucial                      | 379      | 11.45%  |
| Samsung Electronics          | 327      | 9.88%   |
| Corsair                      | 300      | 9.06%   |
| SK hynix                     | 276      | 8.34%   |
| G.Skill                      | 228      | 6.89%   |
| Micron Technology            | 128      | 3.87%   |
| Patriot                      | 77       | 2.33%   |
| A-DATA Technology            | 50       | 1.51%   |
| Unknown                      | 33       | 1%      |
| Team                         | 29       | 0.88%   |
| Ramaxel Technology           | 26       | 0.79%   |
| AMD                          | 24       | 0.72%   |
| Unknown (ABCD)               | 23       | 0.69%   |
| Nanya Technology             | 22       | 0.66%   |
| Hikvision                    | 21       | 0.63%   |
| Elpida                       | 19       | 0.57%   |
| Transcend                    | 17       | 0.51%   |
| Smart                        | 12       | 0.36%   |
| Apacer                       | 10       | 0.3%    |
| Hewlett-Packard              | 9        | 0.27%   |
| GOODRAM                      | 9        | 0.27%   |
| GeIL                         | 8        | 0.24%   |
| Qimonda                      | 7        | 0.21%   |
| Timetec                      | 6        | 0.18%   |
| Patriot Memory (PDP Systems) | 4        | 0.12%   |
| Avant                        | 4        | 0.12%   |
| 48spaces                     | 4        | 0.12%   |
| Unknown (AB)                 | 3        | 0.09%   |
| Unknown (0x5846)             | 3        | 0.09%   |
| Unifosa                      | 3        | 0.09%   |
| Toshiba                      | 3        | 0.09%   |
| Silicon Power                | 3        | 0.09%   |
| PNY                          | 3        | 0.09%   |
| Kingmax                      | 3        | 0.09%   |
| Kimtigo                      | 3        | 0.09%   |
| Goldkey                      | 3        | 0.09%   |
| Wilk Elektronik              | 2        | 0.06%   |
| Wilk                         | 2        | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM SDRAM                              | 45       | 1.23%   |
| Kingston RAM 99U5584-010.A00LF 4GB DIMM DDR3 1866MT/s          | 36       | 0.98%   |
| Unknown                                                        | 33       | 0.9%    |
| Crucial RAM CT8G4DFRA266.M16FG 8GB DIMM DDR4 2666MT/s          | 31       | 0.85%   |
| Crucial RAM CT4G4DFS8213.C8FAR2 4GB DIMM DDR4 2133MT/s         | 30       | 0.82%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 29       | 0.79%   |
| Unknown RAM Module 1GB DIMM SDRAM                              | 27       | 0.74%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 24       | 0.66%   |
| Crucial RAM CT8G4DFRA266.C8FN 8GB DIMM DDR4 2866MT/s           | 24       | 0.66%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 23       | 0.63%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 23       | 0.63%   |
| Unknown RAM Module 2GB DIMM 800MT/s                            | 21       | 0.57%   |
| Hikvision RAM HKED4161DAA1D0MA1 16GB DIMM DDR4 2667MT/s        | 20       | 0.55%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 19       | 0.52%   |
| SK hynix RAM HMA82GU6JJR8N-VK 16GB DIMM DDR4 2667MT/s          | 18       | 0.49%   |
| Corsair RAM CMK16GX4M2B3000C15 8192MB DIMM DDR4 3200MT/s       | 18       | 0.49%   |
| Patriot RAM PSD34G160081 4GB DIMM DDR3 1600MT/s                | 16       | 0.44%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s           | 16       | 0.44%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                    | 15       | 0.41%   |
| Unknown RAM Module 1GB DIMM 800MT/s                            | 15       | 0.41%   |
| Patriot RAM PSD32G13332 2048MB DIMM DDR3 1333MT/s              | 15       | 0.41%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s              | 15       | 0.41%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s            | 15       | 0.41%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s          | 15       | 0.41%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                        | 14       | 0.38%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s         | 14       | 0.38%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s         | 14       | 0.38%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s           | 13       | 0.36%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s              | 13       | 0.36%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s            | 13       | 0.36%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s          | 13       | 0.36%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s            | 12       | 0.33%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s            | 12       | 0.33%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s          | 12       | 0.33%   |
| Crucial RAM CT8G4DFRA32A.M4FE 8GB DIMM DDR4 3200MT/s           | 12       | 0.33%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3100MT/s         | 12       | 0.33%   |
| Unknown RAM Module 2GB DIMM 1066MT/s                           | 11       | 0.3%    |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s            | 11       | 0.3%    |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                      | 10       | 0.27%   |
| Unknown RAM Module 2GB DIMM                                    | 10       | 0.27%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind         | Desktops | Percent |
|--------------|----------|---------|
| DDR4         | 1312     | 44.29%  |
| DDR3         | 1007     | 34%     |
| Unknown      | 215      | 7.26%   |
| DDR2         | 163      | 5.5%    |
| SDRAM        | 161      | 5.44%   |
| DDR          | 35       | 1.18%   |
| LPDDR4       | 33       | 1.11%   |
| DDR5         | 30       | 1.01%   |
| DRAM         | 4        | 0.14%   |
| LPDDR3       | 1        | 0.03%   |
| DDR2 FB-DIMM | 1        | 0.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 2661     | 91.19%  |
| SODIMM       | 228      | 7.81%   |
| Row Of Chips | 10       | 0.34%   |
| FB-DIMM      | 8        | 0.27%   |
| RIMM         | 6        | 0.21%   |
| Unknown      | 4        | 0.14%   |
| Chip         | 1        | 0.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Desktops | Percent |
|---------|----------|---------|
| 8192    | 1025     | 31.82%  |
| 4096    | 745      | 23.13%  |
| 2048    | 529      | 16.42%  |
| 16384   | 522      | 16.21%  |
| 32768   | 190      | 5.9%    |
| 1024    | 161      | 5%      |
| 512     | 34       | 1.06%   |
| 256     | 6        | 0.19%   |
| 65536   | 4        | 0.12%   |
| 128     | 2        | 0.06%   |
| 1536    | 1        | 0.03%   |
| 64      | 1        | 0.03%   |
| Unknown | 1        | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 607      | 18.85%  |
| 1333    | 356      | 11.05%  |
| 3200    | 259      | 8.04%   |
| 2667    | 237      | 7.36%   |
| 2400    | 196      | 6.09%   |
| 2133    | 175      | 5.43%   |
| 3600    | 171      | 5.31%   |
| 800     | 146      | 4.53%   |
| Unknown | 112      | 3.48%   |
| 667     | 91       | 2.83%   |
| 1866    | 82       | 2.55%   |
| 2666    | 75       | 2.33%   |
| 3400    | 50       | 1.55%   |
| 1867    | 46       | 1.43%   |
| 3000    | 44       | 1.37%   |
| 2933    | 43       | 1.33%   |
| 1066    | 43       | 1.33%   |
| 3466    | 37       | 1.15%   |
| 3733    | 34       | 1.06%   |
| 2866    | 27       | 0.84%   |
| 1067    | 26       | 0.81%   |
| 3800    | 23       | 0.71%   |
| 1800    | 23       | 0.71%   |
| 4800    | 21       | 0.65%   |
| 3266    | 19       | 0.59%   |
| 533     | 19       | 0.59%   |
| 400     | 19       | 0.59%   |
| 1334    | 15       | 0.47%   |
| 3866    | 14       | 0.43%   |
| 3100    | 12       | 0.37%   |
| 2048    | 12       | 0.37%   |
| 3666    | 10       | 0.31%   |
| 3534    | 10       | 0.31%   |
| 2800    | 10       | 0.31%   |
| 3500    | 9        | 0.28%   |
| 1648    | 9        | 0.28%   |
| 333     | 8        | 0.25%   |
| 4333    | 7        | 0.22%   |
| 3933    | 7        | 0.22%   |
| 3334    | 7        | 0.22%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 46       | 31.29%  |
| Brother Industries    | 31       | 21.09%  |
| Canon                 | 18       | 12.24%  |
| Samsung Electronics   | 12       | 8.16%   |
| Seiko Epson           | 6        | 4.08%   |
| Dymo-CoStar           | 5        | 3.4%    |
| Zebra                 | 4        | 2.72%   |
| Prolific Technology   | 4        | 2.72%   |
| Xerox                 | 3        | 2.04%   |
| Lexmark International | 3        | 2.04%   |
| QinHeng Electronics   | 2        | 1.36%   |
| Pantum                | 2        | 1.36%   |
| Kyocera               | 2        | 1.36%   |
| STMicroelectronics    | 1        | 0.68%   |
| Ricoh                 | 1        | 0.68%   |
| Printer               | 1        | 0.68%   |
| Oki Data              | 1        | 0.68%   |
| Konica Minolta        | 1        | 0.68%   |
| GODEX INTERNATIONAL   | 1        | 0.68%   |
| Dell                  | 1        | 0.68%   |
| Datamax-O'Neil        | 1        | 0.68%   |
| Apple                 | 1        | 0.68%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| HP LaserJet 1020                                          | 6        | 4.08%   |
| Prolific PL2305 Parallel Port                             | 4        | 2.72%   |
| Xerox B205                                                | 3        | 2.04%   |
| Samsung ML-1660 Series                                    | 3        | 2.04%   |
| HP LaserJet M101-M106                                     | 3        | 2.04%   |
| HP LaserJet 1200                                          | 3        | 2.04%   |
| Brother HL-52x0 series                                    | 3        | 2.04%   |
| Samsung ML-216x Series Laser Printer                      | 2        | 1.36%   |
| QinHeng CH340S                                            | 2        | 1.36%   |
| Lexmark International CS417dn                             | 2        | 1.36%   |
| HP LaserJet Pro M404-M405                                 | 2        | 1.36%   |
| HP LaserJet P1005                                         | 2        | 1.36%   |
| HP LaserJet M14-M17                                       | 2        | 1.36%   |
| HP LaserJet 400 M401a                                     | 2        | 1.36%   |
| HP ENVY Photo 6200 series                                 | 2        | 1.36%   |
| HP ENVY 4520 series                                       | 2        | 1.36%   |
| HP DeskJet 2130 series                                    | 2        | 1.36%   |
| Dymo-CoStar LabelWriter 450                               | 2        | 1.36%   |
| Canon PIXMA MG3600 Series                                 | 2        | 1.36%   |
| Canon MF4410                                              | 2        | 1.36%   |
| Brother HL-3040CN series                                  | 2        | 1.36%   |
| Brother HL-1110 series                                    | 2        | 1.36%   |
| Zebra ZTC ZP 500 (ZPL)                                    | 1        | 0.68%   |
| Zebra ZTC ZD420-203dpi ZPL                                | 1        | 0.68%   |
| Zebra ZTC S4M-200dpi ZPL                                  | 1        | 0.68%   |
| Zebra Printer                                             | 1        | 0.68%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1        | 0.68%   |
| Seiko Epson XP-200 Series                                 | 1        | 0.68%   |
| Seiko Epson XP-15000 Series                               | 1        | 0.68%   |
| Seiko Epson Printer                                       | 1        | 0.68%   |
| Seiko Epson L396 Series                                   | 1        | 0.68%   |
| Seiko Epson L3150 Series                                  | 1        | 0.68%   |
| Seiko Epson ET-2700 Series                                | 1        | 0.68%   |
| Samsung SCX-4x26 Series                                   | 1        | 0.68%   |
| Samsung SCX-4650 4x21S Series                             | 1        | 0.68%   |
| Samsung SCX-4600 Series                                   | 1        | 0.68%   |
| Samsung SCX-4200 series                                   | 1        | 0.68%   |
| Samsung SCX-3400 Series                                   | 1        | 0.68%   |
| Samsung SCX-3200 Series                                   | 1        | 0.68%   |
| Samsung M2020 Series                                      | 1        | 0.68%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 26       | 61.9%   |
| Seiko Epson        | 8        | 19.05%  |
| Hewlett-Packard    | 4        | 9.52%   |
| AGFA-Gevaert NV    | 2        | 4.76%   |
| Ultima Electronics | 1        | 2.38%   |
| Mustek Systems     | 1        | 2.38%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 110                                                               | 7        | 16.67%  |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 6        | 14.29%  |
| Canon CanoScan LiDE 220                                                               | 3        | 7.14%   |
| Canon CanoScan LiDE 210                                                               | 3        | 7.14%   |
| Canon CanoScan N1240U/LiDE 30                                                         | 2        | 4.76%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                                                    | 2        | 4.76%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1        | 2.38%   |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 1        | 2.38%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 1        | 2.38%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 1        | 2.38%   |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                                          | 1        | 2.38%   |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO]                         | 1        | 2.38%   |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO]                           | 1        | 2.38%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]                                     | 1        | 2.38%   |
| Seiko Epson GT-6600U [Perfection 610]                                                 | 1        | 2.38%   |
| Mustek Systems BearPaw 2448 TA Pro                                                    | 1        | 2.38%   |
| HP ScanJet Pro 2500 f1                                                                | 1        | 2.38%   |
| HP ScanJet 82x0C                                                                      | 1        | 2.38%   |
| HP ScanJet 3970c                                                                      | 1        | 2.38%   |
| HP Scanjet 300                                                                        | 1        | 2.38%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 1        | 2.38%   |
| Canon CanoScan LIDE 25                                                                | 1        | 2.38%   |
| Canon CanoScan 9000F Mark II                                                          | 1        | 2.38%   |
| Canon CanoScan 8800F                                                                  | 1        | 2.38%   |
| Canon CanoScan 5600F                                                                  | 1        | 2.38%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 238      | 43.83%  |
| Microdia                               | 41       | 7.55%   |
| Microsoft                              | 31       | 5.71%   |
| Samsung Electronics                    | 23       | 4.24%   |
| Generalplus Technology                 | 21       | 3.87%   |
| Sunplus Innovation Technology          | 19       | 3.5%    |
| Creative Technology                    | 14       | 2.58%   |
| Apple                                  | 12       | 2.21%   |
| Z-Star Microelectronics                | 11       | 2.03%   |
| Jieli Technology                       | 11       | 2.03%   |
| GEMBIRD                                | 10       | 1.84%   |
| KYE Systems (Mouse Systems)            | 9        | 1.66%   |
| ARC International                      | 9        | 1.66%   |
| Chicony Electronics                    | 6        | 1.1%    |
| Realtek Semiconductor                  | 5        | 0.92%   |
| MacroSilicon                           | 4        | 0.74%   |
| Huawei Technologies                    | 4        | 0.74%   |
| Hewlett-Packard                        | 4        | 0.74%   |
| Genesys Logic                          | 4        | 0.74%   |
| Cubeternet                             | 4        | 0.74%   |
| Novatek Microelectronics               | 3        | 0.55%   |
| Google                                 | 3        | 0.55%   |
| Cheng Uei Precision Industry (Foxlink) | 3        | 0.55%   |
| Xiongmai                               | 2        | 0.37%   |
| ValueHD                                | 2        | 0.37%   |
| Trust                                  | 2        | 0.37%   |
| Syntek                                 | 2        | 0.37%   |
| Sunplus IT                             | 2        | 0.37%   |
| Razer USA                              | 2        | 0.37%   |
| Quanta                                 | 2        | 0.37%   |
| Nintendo                               | 2        | 0.37%   |
| AVerMedia Technologies                 | 2        | 0.37%   |
| Aveo Technology                        | 2        | 0.37%   |
| Arkmicro Technologies                  | 2        | 0.37%   |
| 2M UVC CAMERA                          | 2        | 0.37%   |
| Xiaomi                                 | 1        | 0.18%   |
| WaveRider Communications               | 1        | 0.18%   |
| Valve Software                         | 1        | 0.18%   |
| Unknown                                | 1        | 0.18%   |
| Tobii Technology AB                    | 1        | 0.18%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Logitech Webcam C270                            | 66       | 12.09%  |
| Logitech HD Pro Webcam C920                     | 31       | 5.68%   |
| Samsung Galaxy series, misc. (MTP mode)         | 22       | 4.03%   |
| Logitech C922 Pro Stream Webcam                 | 21       | 3.85%   |
| Microsoft LifeCam HD-3000                       | 17       | 3.11%   |
| Logitech HD Webcam C525                         | 15       | 2.75%   |
| Logitech Webcam C170                            | 14       | 2.56%   |
| Microdia USB 2.0 Camera                         | 13       | 2.38%   |
| Generalplus GENERAL WEBCAM                      | 13       | 2.38%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                 | 12       | 2.2%    |
| Microdia Webcam Vitade AF                       | 11       | 2.01%   |
| Logitech Webcam C310                            | 11       | 2.01%   |
| Jieli USB PHY 2.0                               | 11       | 2.01%   |
| GEMBIRD USB2.0 PC CAMERA                        | 10       | 1.83%   |
| Logitech HD Webcam C910                         | 8        | 1.47%   |
| Sunplus Canyon CNS-CWC5 Webcam                  | 7        | 1.28%   |
| Logitech HD Webcam C615                         | 7        | 1.28%   |
| Logitech C920 PRO HD Webcam                     | 7        | 1.28%   |
| Z-Star Venus USB2.0 Camera                      | 6        | 1.1%    |
| Logitech BRIO Ultra HD Webcam                   | 6        | 1.1%    |
| Generalplus 808 Camera                          | 6        | 1.1%    |
| ARC International Camera                        | 6        | 1.1%    |
| KYE Systems (Mouse Systems) JOYACCESS JA-Webcam | 5        | 0.92%   |
| Microdia Integrated Camera                      | 4        | 0.73%   |
| Microdia Camera                                 | 4        | 0.73%   |
| Logitech Webcam C925e                           | 4        | 0.73%   |
| Logitech Webcam C210                            | 4        | 0.73%   |
| Huawei HiCamera                                 | 4        | 0.73%   |
| Creative Live! Cam Chat HD [VF0700/VF0790]      | 4        | 0.73%   |
| Sunplus FHD Camera Microphone                   | 3        | 0.55%   |
| Novatek HP High Definition 2MP Webcam           | 3        | 0.55%   |
| Microsoft LifeCam VX-500 [1357]                 | 3        | 0.55%   |
| Microsoft LifeCam HD-5000                       | 3        | 0.55%   |
| Microdia Sonix USB 2.0 Camera                   | 3        | 0.55%   |
| MacroSilicon USB Video                          | 3        | 0.55%   |
| Logitech Webcam Pro 9000                        | 3        | 0.55%   |
| Logitech Webcam C930e                           | 3        | 0.55%   |
| Logitech StreamCam                              | 3        | 0.55%   |
| Logitech QuickCam Pro 9000                      | 3        | 0.55%   |
| Logitech Logi Webcam C920e                      | 3        | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Validity Sensors      | 1        | 33.33%  |
| Synaptics             | 1        | 33.33%  |
| Elan Microelectronics | 1        | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor | 1        | 33.33%  |
| Synaptics  WBDI Fingerprint Reader - USB 052 | 1        | 33.33%  |
| Elan fingerprint sensor [FeinTech FPS00200]  | 1        | 33.33%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| SCM Microsystems           | 5        | 14.29%  |
| Alcor Micro                | 5        | 14.29%  |
| Gemalto (was Gemplus)      | 4        | 11.43%  |
| Realtek Semiconductor      | 3        | 8.57%   |
| Clay Logic                 | 3        | 8.57%   |
| Cherry                     | 3        | 8.57%   |
| Yubico.com                 | 2        | 5.71%   |
| Chicony Electronics        | 2        | 5.71%   |
| Aladdin Knowledge Systems  | 2        | 5.71%   |
| Advanced Card Systems      | 2        | 5.71%   |
| Reiner SCT Kartensysteme   | 1        | 2.86%   |
| Lenovo                     | 1        | 2.86%   |
| Feitian Technologies       | 1        | 2.86%   |
| Athena Smartcard Solutions | 1        | 2.86%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                        | 4        | 11.43%  |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                     | 3        | 8.57%   |
| Realtek Semiconductor Smart Card Reader Interface                          | 3        | 8.57%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                          | 3        | 8.57%   |
| Clay Logic Nitrokey Pro                                                    | 2        | 5.71%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                       | 2        | 5.71%   |
| Aladdin Knowledge Systems Token JC                                         | 2        | 5.71%   |
| Yubico.com Yubikey 4/5 CCID                                                | 1        | 2.86%   |
| Yubico.com Yubikey 4 U2F+CCID                                              | 1        | 2.86%   |
| SCM Microsystems uTrust 3512 SAM slot Token                                | 1        | 2.86%   |
| SCM Microsystems SCR335 SmartCard Reader                                   | 1        | 2.86%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 1        | 2.86%   |
| Lenovo Smartcard Keyboard                                                  | 1        | 2.86%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                           | 1        | 2.86%   |
| Feitian Technologies SCR301                                                | 1        | 2.86%   |
| Clay Logic Nitrokey Start                                                  | 1        | 2.86%   |
| Cherry SmartTerminal XX1X                                                  | 1        | 2.86%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                | 1        | 2.86%   |
| Cherry Cherry GmbH CHERRY SECURE BOARD 1.0                                 | 1        | 2.86%   |
| Athena Smartcard Solutions ASEDrive CCID                                   | 1        | 2.86%   |
| Alcor Micro Watchdata W 1981                                               | 1        | 2.86%   |
| Advanced Card Systems ACR39U                                               | 1        | 2.86%   |
| Advanced Card Systems ACR38 SmartCard Reader                               | 1        | 2.86%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 2403     | 66.53%  |
| 1     | 1030     | 28.52%  |
| 2     | 157      | 4.35%   |
| 3     | 15       | 0.42%   |
| 6     | 2        | 0.06%   |
| 5     | 2        | 0.06%   |
| 4     | 2        | 0.06%   |
| 7     | 1        | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 931      | 70.32%  |
| Net/wireless             | 108      | 8.16%   |
| Communication controller | 68       | 5.14%   |
| Unassigned class         | 59       | 4.46%   |
| Multimedia controller    | 28       | 2.11%   |
| Sound                    | 27       | 2.04%   |
| Net/ethernet             | 16       | 1.21%   |
| Bluetooth                | 16       | 1.21%   |
| Chipcard                 | 15       | 1.13%   |
| Camera                   | 14       | 1.06%   |
| Card reader              | 11       | 0.83%   |
| Storage/raid             | 6        | 0.45%   |
| Storage/ide              | 5        | 0.38%   |
| Network                  | 5        | 0.38%   |
| Modem                    | 4        | 0.3%    |
| Tv card                  | 3        | 0.23%   |
| Fingerprint reader       | 3        | 0.23%   |
| Dvb card                 | 3        | 0.23%   |
| Storage                  | 2        | 0.15%   |

