Fedora 35 - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for Fedora 35.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock        | FM2A88X Extreme6+           | [9d178352ca](https://linux-hardware.org/?probe=9d178352ca) | Mar 01, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [8a51a8730b](https://linux-hardware.org/?probe=8a51a8730b) | Feb 28, 2022 |
| ASRock        | FM2A88X Extreme6+           | [ffbae7cdf3](https://linux-hardware.org/?probe=ffbae7cdf3) | Feb 28, 2022 |
| ASRock        | FM2A88X Extreme6+           | [930b650263](https://linux-hardware.org/?probe=930b650263) | Feb 27, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [7ce556e43a](https://linux-hardware.org/?probe=7ce556e43a) | Feb 26, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [9cdd0eea43](https://linux-hardware.org/?probe=9cdd0eea43) | Feb 26, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | [03f2fa46f2](https://linux-hardware.org/?probe=03f2fa46f2) | Feb 26, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [f0692aebbe](https://linux-hardware.org/?probe=f0692aebbe) | Feb 25, 2022 |
| ASUSTek       | H97M-E                      | [d8dec986e8](https://linux-hardware.org/?probe=d8dec986e8) | Feb 25, 2022 |
| ASRock        | FM2A88X Extreme6+           | [eaa8067586](https://linux-hardware.org/?probe=eaa8067586) | Feb 25, 2022 |
| ASUSTek       | H97M-E                      | [7b58208c52](https://linux-hardware.org/?probe=7b58208c52) | Feb 25, 2022 |
| ASUSTek       | H97M-E                      | [03a5ed6072](https://linux-hardware.org/?probe=03a5ed6072) | Feb 24, 2022 |
| MSI           | B350 TOMAHAWK               | [e1ddcb9f9a](https://linux-hardware.org/?probe=e1ddcb9f9a) | Feb 24, 2022 |
| Gigabyte      | B450 AORUS M                | [b94d0c6e20](https://linux-hardware.org/?probe=b94d0c6e20) | Feb 24, 2022 |
| ASRock        | FM2A88X Extreme6+           | [eb017e14fa](https://linux-hardware.org/?probe=eb017e14fa) | Feb 24, 2022 |
| ASRock        | FM2A88X Extreme6+           | [88734fe9a0](https://linux-hardware.org/?probe=88734fe9a0) | Feb 23, 2022 |
| MSI           | B550-A PRO                  | [9d3f01a706](https://linux-hardware.org/?probe=9d3f01a706) | Feb 23, 2022 |
| MSI           | PRO Z690-A WIFI DDR4        | [228e9e9d0c](https://linux-hardware.org/?probe=228e9e9d0c) | Feb 23, 2022 |
| Lenovo        | 30D2 NOK                    | [108296cf9b](https://linux-hardware.org/?probe=108296cf9b) | Feb 22, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [d32c812d2b](https://linux-hardware.org/?probe=d32c812d2b) | Feb 22, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [0d69aa634e](https://linux-hardware.org/?probe=0d69aa634e) | Feb 22, 2022 |
| ASRock        | B450M Pro4                  | [5825d4fcaf](https://linux-hardware.org/?probe=5825d4fcaf) | Feb 22, 2022 |
| ASRock        | FM2A88X Extreme6+           | [67deab7343](https://linux-hardware.org/?probe=67deab7343) | Feb 22, 2022 |
| ASUSTek       | P5QL                        | [2714d59901](https://linux-hardware.org/?probe=2714d59901) | Feb 22, 2022 |
| Gigabyte      | Z690 UD DDR4                | [6c4ff21b02](https://linux-hardware.org/?probe=6c4ff21b02) | Feb 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [c8223731dc](https://linux-hardware.org/?probe=c8223731dc) | Feb 21, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [ebca133032](https://linux-hardware.org/?probe=ebca133032) | Feb 21, 2022 |
| Gigabyte      | A320M-S2H-CF                | [558ef9e9d4](https://linux-hardware.org/?probe=558ef9e9d4) | Feb 20, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [34e4b434b4](https://linux-hardware.org/?probe=34e4b434b4) | Feb 20, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [eccaa1c72e](https://linux-hardware.org/?probe=eccaa1c72e) | Feb 19, 2022 |
| Gateway       | DX4860                      | [d28784e189](https://linux-hardware.org/?probe=d28784e189) | Feb 19, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | [3d816cc71a](https://linux-hardware.org/?probe=3d816cc71a) | Feb 19, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [b2c662bad6](https://linux-hardware.org/?probe=b2c662bad6) | Feb 18, 2022 |
| Gigabyte      | F2A68HM-S1                  | [83e6228c44](https://linux-hardware.org/?probe=83e6228c44) | Feb 17, 2022 |
| MSI           | A520M-A PRO                 | [dbe8ddd097](https://linux-hardware.org/?probe=dbe8ddd097) | Feb 17, 2022 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | [f2d47f2d8b](https://linux-hardware.org/?probe=f2d47f2d8b) | Feb 17, 2022 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [a74d65bfe6](https://linux-hardware.org/?probe=a74d65bfe6) | Feb 16, 2022 |
| HP            | 82A2                        | [5efad9b732](https://linux-hardware.org/?probe=5efad9b732) | Feb 16, 2022 |
| MSI           | B450-A PRO MAX              | [538072f18d](https://linux-hardware.org/?probe=538072f18d) | Feb 16, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [e3eee22fef](https://linux-hardware.org/?probe=e3eee22fef) | Feb 16, 2022 |
| Dell          | 08HPGT A02                  | [a6c76eb5f6](https://linux-hardware.org/?probe=a6c76eb5f6) | Feb 15, 2022 |
| Dell          | 08HPGT A02                  | [6d024608a5](https://linux-hardware.org/?probe=6d024608a5) | Feb 15, 2022 |
| MSI           | B450M MORTAR MAX            | [68f6b7dd88](https://linux-hardware.org/?probe=68f6b7dd88) | Feb 15, 2022 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | [a82c9b223f](https://linux-hardware.org/?probe=a82c9b223f) | Feb 14, 2022 |
| MSI           | B450-A PRO MAX              | [4c61db4a18](https://linux-hardware.org/?probe=4c61db4a18) | Feb 13, 2022 |
| ECS           | A58F2P-M4                   | [bae5185ab0](https://linux-hardware.org/?probe=bae5185ab0) | Feb 13, 2022 |
| Gigabyte      | B450M DS3H-CF               | [84005ca8f9](https://linux-hardware.org/?probe=84005ca8f9) | Feb 12, 2022 |
| Biostar       | AM1ML                       | [54e50bd790](https://linux-hardware.org/?probe=54e50bd790) | Feb 12, 2022 |
| Biostar       | AM1ML                       | [e933dbc718](https://linux-hardware.org/?probe=e933dbc718) | Feb 12, 2022 |
| ASUSTek       | Maximus VIII HERO           | [359fac7afc](https://linux-hardware.org/?probe=359fac7afc) | Feb 12, 2022 |
| Gigabyte      | B550 GAMING X V2            | [60ee5faa6c](https://linux-hardware.org/?probe=60ee5faa6c) | Feb 10, 2022 |
| Gigabyte      | G41MT-D3                    | [ac4b2855c6](https://linux-hardware.org/?probe=ac4b2855c6) | Feb 10, 2022 |
| ASUSTek       | STRIX B250F GAMING          | [1b903af2df](https://linux-hardware.org/?probe=1b903af2df) | Feb 10, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | [87d3fd2916](https://linux-hardware.org/?probe=87d3fd2916) | Feb 09, 2022 |
| ASRock        | Z87 Pro3                    | [dea0b07f08](https://linux-hardware.org/?probe=dea0b07f08) | Feb 08, 2022 |
| ASUSTek       | TUF GAMING Z690-PLUS WIF... | [ab81e91207](https://linux-hardware.org/?probe=ab81e91207) | Feb 08, 2022 |
| Gigabyte      | B85M-D3V-A                  | [29ca9095c4](https://linux-hardware.org/?probe=29ca9095c4) | Feb 08, 2022 |
| ASUSTek       | PRIME B450M-K               | [24a7621237](https://linux-hardware.org/?probe=24a7621237) | Feb 08, 2022 |
| Gigabyte      | EP45-DS3L                   | [7966e303e6](https://linux-hardware.org/?probe=7966e303e6) | Feb 07, 2022 |
| ASRock        | X570 Taichi                 | [e7b3bb2161](https://linux-hardware.org/?probe=e7b3bb2161) | Feb 07, 2022 |
| ASRock        | X570 Taichi                 | [97a6c42f5f](https://linux-hardware.org/?probe=97a6c42f5f) | Feb 07, 2022 |
| Gigabyte      | H310M M.2 x.x               | [824af874a4](https://linux-hardware.org/?probe=824af874a4) | Feb 06, 2022 |
| ASRock        | B560M Steel Legend          | [e2a7b380d8](https://linux-hardware.org/?probe=e2a7b380d8) | Feb 06, 2022 |
| MSI           | B450-A PRO MAX              | [830c0232b6](https://linux-hardware.org/?probe=830c0232b6) | Feb 06, 2022 |
| MSI           | Z77A-GD65 GAMING            | [8d2cf11a20](https://linux-hardware.org/?probe=8d2cf11a20) | Feb 06, 2022 |
| Dell          | 0200DY A00                  | [5714dfdd29](https://linux-hardware.org/?probe=5714dfdd29) | Feb 06, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [d7796dd19f](https://linux-hardware.org/?probe=d7796dd19f) | Feb 05, 2022 |
| Supermicro    | X9DRW                       | [432d4db3ea](https://linux-hardware.org/?probe=432d4db3ea) | Feb 05, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [63a70836f3](https://linux-hardware.org/?probe=63a70836f3) | Feb 05, 2022 |
| Gigabyte      | D525TUD                     | [08962dc9f9](https://linux-hardware.org/?probe=08962dc9f9) | Feb 05, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [cd81e5ce82](https://linux-hardware.org/?probe=cd81e5ce82) | Feb 05, 2022 |
| Gigabyte      | GA-990FXA-UD3               | [cab5335d99](https://linux-hardware.org/?probe=cab5335d99) | Feb 04, 2022 |
| ASUSTek       | M5A97 R2.0                  | [548f756c0e](https://linux-hardware.org/?probe=548f756c0e) | Feb 04, 2022 |
| Gigabyte      | 970A-DS3P                   | [e799f33b3f](https://linux-hardware.org/?probe=e799f33b3f) | Feb 04, 2022 |
| ASUSTek       | H97M-E                      | [f10bee8b8f](https://linux-hardware.org/?probe=f10bee8b8f) | Feb 04, 2022 |
| ASUSTek       | PRIME B250M-A               | [9a45aba28e](https://linux-hardware.org/?probe=9a45aba28e) | Feb 03, 2022 |
| Lenovo        | ThinkCentre M58p 7220A72    | [4df88dcf23](https://linux-hardware.org/?probe=4df88dcf23) | Feb 03, 2022 |
| Gigabyte      | 970A-DS3P                   | [9da6b947f5](https://linux-hardware.org/?probe=9da6b947f5) | Feb 03, 2022 |
| Gigabyte      | D525TUD                     | [83678f76fc](https://linux-hardware.org/?probe=83678f76fc) | Feb 03, 2022 |
| ASUSTek       | H97M-E                      | [f37fe196d0](https://linux-hardware.org/?probe=f37fe196d0) | Feb 03, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [104c871438](https://linux-hardware.org/?probe=104c871438) | Feb 03, 2022 |
| Gigabyte      | GB-BRR7H-4800               | [dca1097e4a](https://linux-hardware.org/?probe=dca1097e4a) | Feb 02, 2022 |
| Dell          | 0X4H68 A00                  | [3ecad8d7e4](https://linux-hardware.org/?probe=3ecad8d7e4) | Feb 02, 2022 |
| Gigabyte      | Z270-HD3P-CF                | [813bec5fe7](https://linux-hardware.org/?probe=813bec5fe7) | Feb 02, 2022 |
| ASUSTek       | PRIME Z270-P                | [26a4917db5](https://linux-hardware.org/?probe=26a4917db5) | Feb 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [7ea870fff3](https://linux-hardware.org/?probe=7ea870fff3) | Feb 02, 2022 |
| ASRock        | A320M-HD R4.0               | [f2dfa50076](https://linux-hardware.org/?probe=f2dfa50076) | Feb 02, 2022 |
| ASUSTek       | P8Z77-V LK                  | [a6321e237c](https://linux-hardware.org/?probe=a6321e237c) | Feb 01, 2022 |
| ASUSTek       | PRIME B360M-A               | [c60e8a85c4](https://linux-hardware.org/?probe=c60e8a85c4) | Feb 01, 2022 |
| Gigabyte      | B450 AORUS M                | [fb9c5fac50](https://linux-hardware.org/?probe=fb9c5fac50) | Feb 01, 2022 |
| Fujitsu       | D3600-A1 S26361-D3600-A1    | [9ba4b1306f](https://linux-hardware.org/?probe=9ba4b1306f) | Jan 31, 2022 |
| ASUSTek       | H97M-E                      | [d8cbfade46](https://linux-hardware.org/?probe=d8cbfade46) | Jan 31, 2022 |
| MSI           | X99A GAMING PRO CARBON      | [49bd28cbf5](https://linux-hardware.org/?probe=49bd28cbf5) | Jan 31, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS_BR     | [dc652a6ac4](https://linux-hardware.org/?probe=dc652a6ac4) | Jan 30, 2022 |
| Dell          | 0X4H68 A00                  | [0e6a0c4725](https://linux-hardware.org/?probe=0e6a0c4725) | Jan 29, 2022 |
| ASUSTek       | TUF GAMING B550M-PLUS       | [83cdfa61a4](https://linux-hardware.org/?probe=83cdfa61a4) | Jan 28, 2022 |
| Gigabyte      | GB-BRR7H-4800               | [ed43351639](https://linux-hardware.org/?probe=ed43351639) | Jan 27, 2022 |
| Gigabyte      | Z270-HD3P-CF                | [e422d19fb3](https://linux-hardware.org/?probe=e422d19fb3) | Jan 27, 2022 |
| Gigabyte      | B85M-D3V-A                  | [2d778a328d](https://linux-hardware.org/?probe=2d778a328d) | Jan 27, 2022 |
| PCWare        | IPMH110G                    | [82ee6777f1](https://linux-hardware.org/?probe=82ee6777f1) | Jan 26, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [267ee0e693](https://linux-hardware.org/?probe=267ee0e693) | Jan 26, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [a72f036b05](https://linux-hardware.org/?probe=a72f036b05) | Jan 26, 2022 |
| Gigabyte      | P55A-UD7                    | [084f158a19](https://linux-hardware.org/?probe=084f158a19) | Jan 26, 2022 |
| MSI           | Z270M MORTAR                | [2493fd0195](https://linux-hardware.org/?probe=2493fd0195) | Jan 26, 2022 |
| ASUSTek       | PRIME B250M-A               | [875671a912](https://linux-hardware.org/?probe=875671a912) | Jan 25, 2022 |
| ASUSTek       | Z170 PRO GAMING             | [ec67e898bd](https://linux-hardware.org/?probe=ec67e898bd) | Jan 24, 2022 |
| Gigabyte      | B85M-D3V-A                  | [b812fc3ed2](https://linux-hardware.org/?probe=b812fc3ed2) | Jan 24, 2022 |
| HP            | 1497                        | [7761e5755c](https://linux-hardware.org/?probe=7761e5755c) | Jan 24, 2022 |
| MSI           | MEG Z390 GODLIKE            | [dd33a742c9](https://linux-hardware.org/?probe=dd33a742c9) | Jan 24, 2022 |
| Gigabyte      | H110M-H-CF                  | [f8afc9746e](https://linux-hardware.org/?probe=f8afc9746e) | Jan 24, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [3ceffb0902](https://linux-hardware.org/?probe=3ceffb0902) | Jan 24, 2022 |
| MSI           | B450M MORTAR MAX            | [619b081f40](https://linux-hardware.org/?probe=619b081f40) | Jan 23, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [79e2d3dc48](https://linux-hardware.org/?probe=79e2d3dc48) | Jan 23, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [937ad3940c](https://linux-hardware.org/?probe=937ad3940c) | Jan 23, 2022 |
| Gigabyte      | EP45-DS3L                   | [10b9d78b55](https://linux-hardware.org/?probe=10b9d78b55) | Jan 23, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [1bea66eb77](https://linux-hardware.org/?probe=1bea66eb77) | Jan 23, 2022 |
| Gigabyte      | GA-880GM-UD2H               | [38c5a8b4f6](https://linux-hardware.org/?probe=38c5a8b4f6) | Jan 23, 2022 |
| Gigabyte      | H77N-WIFI                   | [b006be0c8b](https://linux-hardware.org/?probe=b006be0c8b) | Jan 22, 2022 |
| Gigabyte      | D525TUD                     | [db0a0adc46](https://linux-hardware.org/?probe=db0a0adc46) | Jan 22, 2022 |
| Gigabyte      | GB-BRR7H-4800               | [992e0c224c](https://linux-hardware.org/?probe=992e0c224c) | Jan 22, 2022 |
| ASRock        | B550 Phantom Gaming 4/ac    | [ada27693c4](https://linux-hardware.org/?probe=ada27693c4) | Jan 21, 2022 |
| MSI           | H310M PRO-VH                | [68c71dac17](https://linux-hardware.org/?probe=68c71dac17) | Jan 21, 2022 |
| Gigabyte      | H97-D3H-CF                  | [8e39cc0d01](https://linux-hardware.org/?probe=8e39cc0d01) | Jan 21, 2022 |
| BESSTAR Te... | HM50                        | [ddc2e44fcc](https://linux-hardware.org/?probe=ddc2e44fcc) | Jan 21, 2022 |
| MSI           | PRO Z690-A WIFI DDR4        | [1b1004081a](https://linux-hardware.org/?probe=1b1004081a) | Jan 21, 2022 |
| Gigabyte      | H81M-S2H                    | [5a010a60d7](https://linux-hardware.org/?probe=5a010a60d7) | Jan 20, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [04926d5643](https://linux-hardware.org/?probe=04926d5643) | Jan 20, 2022 |
| ASUSTek       | ROG Maximus XI FORMULA      | [af3563e3e7](https://linux-hardware.org/?probe=af3563e3e7) | Jan 20, 2022 |
| Gigabyte      | B450 AORUS M                | [a846ee2ac3](https://linux-hardware.org/?probe=a846ee2ac3) | Jan 19, 2022 |
| MSI           | B450-A PRO MAX              | [72415f94c8](https://linux-hardware.org/?probe=72415f94c8) | Jan 19, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [87c1802929](https://linux-hardware.org/?probe=87c1802929) | Jan 19, 2022 |
| MSI           | B450-A PRO MAX              | [ab286ab82d](https://linux-hardware.org/?probe=ab286ab82d) | Jan 19, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [ca82eeb3d3](https://linux-hardware.org/?probe=ca82eeb3d3) | Jan 19, 2022 |
| MSI           | H310M PRO-VH                | [844791ed3e](https://linux-hardware.org/?probe=844791ed3e) | Jan 19, 2022 |
| Dell          | 0PP150 A00                  | [851a920599](https://linux-hardware.org/?probe=851a920599) | Jan 19, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [c4103d5c5a](https://linux-hardware.org/?probe=c4103d5c5a) | Jan 19, 2022 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | [3dd363739d](https://linux-hardware.org/?probe=3dd363739d) | Jan 18, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | [01e009ebd0](https://linux-hardware.org/?probe=01e009ebd0) | Jan 18, 2022 |
| ASUSTek       | Maximus IV GENE-Z           | [e4489c39b8](https://linux-hardware.org/?probe=e4489c39b8) | Jan 18, 2022 |
| Gigabyte      | Z590 AORUS MASTER           | [db8f93ad4a](https://linux-hardware.org/?probe=db8f93ad4a) | Jan 18, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [7451fd2f02](https://linux-hardware.org/?probe=7451fd2f02) | Jan 17, 2022 |
| HP            | 1494                        | [c03b887753](https://linux-hardware.org/?probe=c03b887753) | Jan 16, 2022 |
| ASUSTek       | PRIME B250-PLUS             | [6a024b63f0](https://linux-hardware.org/?probe=6a024b63f0) | Jan 16, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [01f17fdaa9](https://linux-hardware.org/?probe=01f17fdaa9) | Jan 16, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | [ef86d029ff](https://linux-hardware.org/?probe=ef86d029ff) | Jan 16, 2022 |
| Acer          | Veriton X6620G v1.0         | [8ef5b3632a](https://linux-hardware.org/?probe=8ef5b3632a) | Jan 16, 2022 |
| Dell          | 09M8Y8 A01                  | [d5bd08abac](https://linux-hardware.org/?probe=d5bd08abac) | Jan 16, 2022 |
| Gigabyte      | B250M-D3H-CF                | [339d7aa470](https://linux-hardware.org/?probe=339d7aa470) | Jan 15, 2022 |
| ASUSTek       | PRIME X299-DELUXE           | [6903f0230f](https://linux-hardware.org/?probe=6903f0230f) | Jan 15, 2022 |
| ASUSTek       | PRIME X299-DELUXE           | [c458fb3c47](https://linux-hardware.org/?probe=c458fb3c47) | Jan 15, 2022 |
| ASUSTek       | Q87M-E                      | [30309c0416](https://linux-hardware.org/?probe=30309c0416) | Jan 15, 2022 |
| Dell          | 0NDYHG A01                  | [cc3a8808e7](https://linux-hardware.org/?probe=cc3a8808e7) | Jan 15, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [4151d78b0a](https://linux-hardware.org/?probe=4151d78b0a) | Jan 14, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [322291a7b1](https://linux-hardware.org/?probe=322291a7b1) | Jan 14, 2022 |
| MSI           | B450-A PRO MAX              | [7bf06ab6f0](https://linux-hardware.org/?probe=7bf06ab6f0) | Jan 14, 2022 |
| Gigabyte      | Z490 AORUS MASTER           | [7de1f8971f](https://linux-hardware.org/?probe=7de1f8971f) | Jan 14, 2022 |
| ASUSTek       | Maximus IV GENE-Z           | [e1d5a4a319](https://linux-hardware.org/?probe=e1d5a4a319) | Jan 14, 2022 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [bef980429e](https://linux-hardware.org/?probe=bef980429e) | Jan 14, 2022 |
| Gigabyte      | F2A68HM-H                   | [f8b504601e](https://linux-hardware.org/?probe=f8b504601e) | Jan 13, 2022 |
| MSI           | MAG B550M MORTAR            | [c7567b5c29](https://linux-hardware.org/?probe=c7567b5c29) | Jan 13, 2022 |
| Gigabyte      | EP45-DS3L                   | [538e62155e](https://linux-hardware.org/?probe=538e62155e) | Jan 11, 2022 |
| Gigabyte      | GA-A55M-DS2                 | [f05cc95e99](https://linux-hardware.org/?probe=f05cc95e99) | Jan 11, 2022 |
| ASRock        | B360M IB-R1                 | [afb5a134ce](https://linux-hardware.org/?probe=afb5a134ce) | Jan 11, 2022 |
| ASUSTek       | Pro WS X570-ACE             | [63db2e4ecc](https://linux-hardware.org/?probe=63db2e4ecc) | Jan 10, 2022 |
| ASRock        | B450 Pro4                   | [3b3b0c2855](https://linux-hardware.org/?probe=3b3b0c2855) | Jan 10, 2022 |
| ASUSTek       | Pro WS X570-ACE             | [132d4e0b47](https://linux-hardware.org/?probe=132d4e0b47) | Jan 10, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [5d7aaea168](https://linux-hardware.org/?probe=5d7aaea168) | Jan 10, 2022 |
| ASUSTek       | H81-GAMER                   | [e123597c40](https://linux-hardware.org/?probe=e123597c40) | Jan 09, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [02fe041d02](https://linux-hardware.org/?probe=02fe041d02) | Jan 09, 2022 |
| MSI           | B350M MORTAR ARCTIC         | [8d51630dcf](https://linux-hardware.org/?probe=8d51630dcf) | Jan 09, 2022 |
| Lenovo        | 369A SDK0F82993 WIN         | [e1141045bf](https://linux-hardware.org/?probe=e1141045bf) | Jan 08, 2022 |
| Gigabyte      | X570S AERO G                | [fc3f2a485a](https://linux-hardware.org/?probe=fc3f2a485a) | Jan 08, 2022 |
| Dell          | 04Y8V0 A02                  | [fa29ca9b4b](https://linux-hardware.org/?probe=fa29ca9b4b) | Jan 08, 2022 |
| Dell          | 04Y8V0 A02                  | [2564a1e4de](https://linux-hardware.org/?probe=2564a1e4de) | Jan 08, 2022 |
| ASUSTek       | Maximus IX CODE             | [32c7db26bd](https://linux-hardware.org/?probe=32c7db26bd) | Jan 08, 2022 |
| Gigabyte      | B75M-D3V                    | [faa71fac97](https://linux-hardware.org/?probe=faa71fac97) | Jan 06, 2022 |
| ASUSTek       | PRIME B360M-A               | [3b6e3858d5](https://linux-hardware.org/?probe=3b6e3858d5) | Jan 06, 2022 |
| ASUSTek       | Z77-A                       | [627b0162be](https://linux-hardware.org/?probe=627b0162be) | Jan 06, 2022 |
| Gigabyte      | B450 AORUS M                | [9ebb75d7a4](https://linux-hardware.org/?probe=9ebb75d7a4) | Jan 06, 2022 |
| Gigabyte      | EP45-DS3L                   | [9a5e27cab0](https://linux-hardware.org/?probe=9a5e27cab0) | Jan 05, 2022 |
| XFX           | nForce 780i 3-Way SLI 1     | [b56f576ff8](https://linux-hardware.org/?probe=b56f576ff8) | Jan 05, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [75db843d7d](https://linux-hardware.org/?probe=75db843d7d) | Jan 04, 2022 |
| ASRock        | H110M-HDV R3.0              | [90fe76c900](https://linux-hardware.org/?probe=90fe76c900) | Jan 03, 2022 |
| HP            | 1495                        | [6298747a55](https://linux-hardware.org/?probe=6298747a55) | Jan 03, 2022 |
| ASRock        | H81M-HG4 R4.0               | [282277fa58](https://linux-hardware.org/?probe=282277fa58) | Jan 02, 2022 |
| MSI           | Z97S SLI Krait Edition      | [abff969a99](https://linux-hardware.org/?probe=abff969a99) | Jan 02, 2022 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | [b4049969e7](https://linux-hardware.org/?probe=b4049969e7) | Jan 02, 2022 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | [c5e569b5c7](https://linux-hardware.org/?probe=c5e569b5c7) | Jan 02, 2022 |
| ASRock        | B360M IB-R1                 | [f300f71e62](https://linux-hardware.org/?probe=f300f71e62) | Jan 02, 2022 |
| Gigabyte      | EP45-DS3L                   | [5d9026b1c0](https://linux-hardware.org/?probe=5d9026b1c0) | Jan 01, 2022 |
| Gigabyte      | G41MT-D3                    | [9c2f65c964](https://linux-hardware.org/?probe=9c2f65c964) | Jan 01, 2022 |
| Dell          | 0T7D40 A01                  | [4fce685dae](https://linux-hardware.org/?probe=4fce685dae) | Jan 01, 2022 |
| Dell          | 0T7D40 A01                  | [4ce7ea3bb0](https://linux-hardware.org/?probe=4ce7ea3bb0) | Dec 31, 2021 |
| Intel         | SKYBAY                      | [043f80cded](https://linux-hardware.org/?probe=043f80cded) | Dec 31, 2021 |
| ASUSTek       | PRIME B450M-A               | [58cb628601](https://linux-hardware.org/?probe=58cb628601) | Dec 31, 2021 |
| Gigabyte      | F2A88XM-DS2P                | [75eea6ae2f](https://linux-hardware.org/?probe=75eea6ae2f) | Dec 30, 2021 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [00f3b181b3](https://linux-hardware.org/?probe=00f3b181b3) | Dec 30, 2021 |
| MSI           | X370 GAMING PLUS            | [49f7093e8c](https://linux-hardware.org/?probe=49f7093e8c) | Dec 29, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [47edce55a4](https://linux-hardware.org/?probe=47edce55a4) | Dec 29, 2021 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [e3297eb51f](https://linux-hardware.org/?probe=e3297eb51f) | Dec 29, 2021 |
| Gigabyte      | TRX40 AORUS XTREME          | [cbf9ee4a86](https://linux-hardware.org/?probe=cbf9ee4a86) | Dec 28, 2021 |
| MSI           | H81M-E33                    | [a7e25b05e2](https://linux-hardware.org/?probe=a7e25b05e2) | Dec 27, 2021 |
| XFX           | nForce 780i 3-Way SLI 1     | [36da2e6d4e](https://linux-hardware.org/?probe=36da2e6d4e) | Dec 26, 2021 |
| ASUSTek       | M2N-E                       | [3a08145f4b](https://linux-hardware.org/?probe=3a08145f4b) | Dec 24, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | [ca0f62a716](https://linux-hardware.org/?probe=ca0f62a716) | Dec 24, 2021 |
| MSI           | MEG Z390 GODLIKE            | [f1e535b5ba](https://linux-hardware.org/?probe=f1e535b5ba) | Dec 24, 2021 |
| Gigabyte      | Z390 M-CF                   | [6efc5bede0](https://linux-hardware.org/?probe=6efc5bede0) | Dec 23, 2021 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [4cd052492e](https://linux-hardware.org/?probe=4cd052492e) | Dec 23, 2021 |
| MSI           | A320M PRO-VH PLUS           | [27379a7599](https://linux-hardware.org/?probe=27379a7599) | Dec 22, 2021 |
| MSI           | PRO Z690-A WIFI DDR4        | [51a7e08e9a](https://linux-hardware.org/?probe=51a7e08e9a) | Dec 22, 2021 |
| MSI           | X470 GAMING M7 AC           | [9b2acc6ea1](https://linux-hardware.org/?probe=9b2acc6ea1) | Dec 22, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [dd197ecb62](https://linux-hardware.org/?probe=dd197ecb62) | Dec 21, 2021 |
| ASUSTek       | P5G41-M                     | [09352ecc24](https://linux-hardware.org/?probe=09352ecc24) | Dec 21, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [03abaff4ae](https://linux-hardware.org/?probe=03abaff4ae) | Dec 21, 2021 |
| Gigabyte      | EP45-DS3L                   | [e0f736fe3b](https://linux-hardware.org/?probe=e0f736fe3b) | Dec 20, 2021 |
| Dell          | 0YJPT1 A00                  | [a92e152a7c](https://linux-hardware.org/?probe=a92e152a7c) | Dec 20, 2021 |
| ASRock        | X399 Taichi                 | [16e27617b9](https://linux-hardware.org/?probe=16e27617b9) | Dec 20, 2021 |
| Gigabyte      | H61M-USB3V                  | [d05d2fe462](https://linux-hardware.org/?probe=d05d2fe462) | Dec 20, 2021 |
| ASUSTek       | PRIME H270-PLUS             | [9c1cf57d74](https://linux-hardware.org/?probe=9c1cf57d74) | Dec 20, 2021 |
| Dell          | 0C522T A03                  | [58f36b9637](https://linux-hardware.org/?probe=58f36b9637) | Dec 20, 2021 |
| Dell          | 0YXT71 A03                  | [0a48d9579b](https://linux-hardware.org/?probe=0a48d9579b) | Dec 19, 2021 |
| MSI           | X370 SLI PLUS               | [adb27f9347](https://linux-hardware.org/?probe=adb27f9347) | Dec 19, 2021 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [e2ce1d7284](https://linux-hardware.org/?probe=e2ce1d7284) | Dec 19, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [6653477f61](https://linux-hardware.org/?probe=6653477f61) | Dec 18, 2021 |
| JINGSHA       | Unknown                     | [13da82798c](https://linux-hardware.org/?probe=13da82798c) | Dec 18, 2021 |
| Gigabyte      | H370 HD3-CF                 | [2497b24eda](https://linux-hardware.org/?probe=2497b24eda) | Dec 18, 2021 |
| Gigabyte      | F2A88XM-DS2P                | [c18ddabc8d](https://linux-hardware.org/?probe=c18ddabc8d) | Dec 18, 2021 |
| ASUSTek       | P5G41-M                     | [c073d4a4e9](https://linux-hardware.org/?probe=c073d4a4e9) | Dec 17, 2021 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | [b86150c4bd](https://linux-hardware.org/?probe=b86150c4bd) | Dec 16, 2021 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | [923f77a787](https://linux-hardware.org/?probe=923f77a787) | Dec 16, 2021 |
| HP            | 805D                        | [dfdc70512c](https://linux-hardware.org/?probe=dfdc70512c) | Dec 16, 2021 |
| ASUSTek       | Z97-PRO GAMER               | [45a411c9fe](https://linux-hardware.org/?probe=45a411c9fe) | Dec 15, 2021 |
| Gigabyte      | TRX40 AORUS MASTER          | [5915e986de](https://linux-hardware.org/?probe=5915e986de) | Dec 15, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | [60a7206b05](https://linux-hardware.org/?probe=60a7206b05) | Dec 15, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [660ce7fc74](https://linux-hardware.org/?probe=660ce7fc74) | Dec 15, 2021 |
| Dell          | 0RY007                      | [f3cb490147](https://linux-hardware.org/?probe=f3cb490147) | Dec 14, 2021 |
| Gigabyte      | Z270P-D3-CF                 | [b2dc7c9e05](https://linux-hardware.org/?probe=b2dc7c9e05) | Dec 14, 2021 |
| HP            | 2B2B                        | [bf929a4359](https://linux-hardware.org/?probe=bf929a4359) | Dec 14, 2021 |
| ASUSTek       | Z97-PRO GAMER               | [53523a4ea7](https://linux-hardware.org/?probe=53523a4ea7) | Dec 14, 2021 |
| MSI           | MPG B550 GAMING PLUS        | [3030fcf474](https://linux-hardware.org/?probe=3030fcf474) | Dec 13, 2021 |
| Gigabyte      | Z170-D3H-CF                 | [3616fc5b0e](https://linux-hardware.org/?probe=3616fc5b0e) | Dec 12, 2021 |
| Gigabyte      | B560M DS3H V2               | [169e6793c2](https://linux-hardware.org/?probe=169e6793c2) | Dec 12, 2021 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [021525201e](https://linux-hardware.org/?probe=021525201e) | Dec 12, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [bd4a0c5d2f](https://linux-hardware.org/?probe=bd4a0c5d2f) | Dec 12, 2021 |
| ASUSTek       | P6T                         | [b789a1151e](https://linux-hardware.org/?probe=b789a1151e) | Dec 11, 2021 |
| Gigabyte      | X570 AORUS PRO              | [8ae1043ce6](https://linux-hardware.org/?probe=8ae1043ce6) | Dec 10, 2021 |
| Gigabyte      | 990FXA-UD3                  | [b76ef07c59](https://linux-hardware.org/?probe=b76ef07c59) | Dec 10, 2021 |
| ASUSTek       | P6T                         | [71ce922273](https://linux-hardware.org/?probe=71ce922273) | Dec 09, 2021 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [bf533d0378](https://linux-hardware.org/?probe=bf533d0378) | Dec 09, 2021 |
| Gigabyte      | Z690 UD DDR4                | [d0070c39c4](https://linux-hardware.org/?probe=d0070c39c4) | Dec 09, 2021 |
| Gigabyte      | Z77-D3H                     | [c486c9645b](https://linux-hardware.org/?probe=c486c9645b) | Dec 09, 2021 |
| Dell          | 040DDP A01                  | [b8e92a4957](https://linux-hardware.org/?probe=b8e92a4957) | Dec 09, 2021 |
| ASUSTek       | P6T                         | [d04f9d16a8](https://linux-hardware.org/?probe=d04f9d16a8) | Dec 08, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [82926e68a4](https://linux-hardware.org/?probe=82926e68a4) | Dec 08, 2021 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | [bd8742e075](https://linux-hardware.org/?probe=bd8742e075) | Dec 08, 2021 |
| Apple         | Mac-F221BEC8                | [809152313d](https://linux-hardware.org/?probe=809152313d) | Dec 07, 2021 |
| ASUSTek       | SABERTOOTH X79              | [58c6a86730](https://linux-hardware.org/?probe=58c6a86730) | Dec 07, 2021 |
| Gigabyte      | Z97P-D3                     | [abc89c9b78](https://linux-hardware.org/?probe=abc89c9b78) | Dec 07, 2021 |
| XFX           | MI-A78S-8209 Ver1.1         | [5393b5ad7a](https://linux-hardware.org/?probe=5393b5ad7a) | Dec 06, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | [9e878d83a3](https://linux-hardware.org/?probe=9e878d83a3) | Dec 06, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | [0a06cba7c5](https://linux-hardware.org/?probe=0a06cba7c5) | Dec 06, 2021 |
| Lenovo        | 3642 SDK0J40700 WIN 3258... | [82cd98ea5a](https://linux-hardware.org/?probe=82cd98ea5a) | Dec 06, 2021 |
| Lenovo        | 3642 SDK0J40700 WIN 3258... | [07f484651e](https://linux-hardware.org/?probe=07f484651e) | Dec 06, 2021 |
| Gigabyte      | B450 AORUS M                | [18ae64d44d](https://linux-hardware.org/?probe=18ae64d44d) | Dec 05, 2021 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [b296e2a320](https://linux-hardware.org/?probe=b296e2a320) | Dec 05, 2021 |
| Dell          | 0M859N A00                  | [f254ee88c6](https://linux-hardware.org/?probe=f254ee88c6) | Dec 05, 2021 |
| MSI           | Z87M GAMING                 | [4ef67e0560](https://linux-hardware.org/?probe=4ef67e0560) | Dec 04, 2021 |
| ASUSTek       | Z87-A                       | [e7d4963834](https://linux-hardware.org/?probe=e7d4963834) | Dec 04, 2021 |
| XFX           | MI-A78S-8209 Ver1.1         | [ce556a2535](https://linux-hardware.org/?probe=ce556a2535) | Dec 04, 2021 |
| Dell          | 0J3C2F A00                  | [bfead2c865](https://linux-hardware.org/?probe=bfead2c865) | Dec 04, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | [511a349d7f](https://linux-hardware.org/?probe=511a349d7f) | Dec 03, 2021 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | [fd20b7fc56](https://linux-hardware.org/?probe=fd20b7fc56) | Dec 03, 2021 |
| Dell          | 06D7TR A00                  | [8c6244cb77](https://linux-hardware.org/?probe=8c6244cb77) | Dec 03, 2021 |
| MSI           | MEG Z390 GODLIKE            | [ca1727f54a](https://linux-hardware.org/?probe=ca1727f54a) | Dec 02, 2021 |
| Gateway       | SX2185                      | [70e907b207](https://linux-hardware.org/?probe=70e907b207) | Dec 02, 2021 |
| Dell          | 040DDP A01                  | [b108ae97c2](https://linux-hardware.org/?probe=b108ae97c2) | Dec 02, 2021 |
| MSI           | X370 XPOWER GAMING TITAN... | [56bd9b515c](https://linux-hardware.org/?probe=56bd9b515c) | Dec 02, 2021 |
| ASUSTek       | H81M-C                      | [ffecd77f3a](https://linux-hardware.org/?probe=ffecd77f3a) | Dec 02, 2021 |
| MSI           | B550M PRO-VDH WIFI          | [508352ad4a](https://linux-hardware.org/?probe=508352ad4a) | Dec 02, 2021 |
| Gigabyte      | B85M-D3V-A                  | [7304efa5d7](https://linux-hardware.org/?probe=7304efa5d7) | Dec 01, 2021 |
| Huanan        | X99-F8 V2.0                 | [1b4de261b3](https://linux-hardware.org/?probe=1b4de261b3) | Nov 30, 2021 |
| Gigabyte      | Z690 UD DDR4                | [7ad53e55ba](https://linux-hardware.org/?probe=7ad53e55ba) | Nov 30, 2021 |
| Apple         | Mac-F221BEC8                | [2ceb61c052](https://linux-hardware.org/?probe=2ceb61c052) | Nov 30, 2021 |
| Gigabyte      | EX58-UD3R                   | [8ece12c9e6](https://linux-hardware.org/?probe=8ece12c9e6) | Nov 28, 2021 |
| ECS           | H61H2-CM                    | [525be50825](https://linux-hardware.org/?probe=525be50825) | Nov 28, 2021 |
| Gigabyte      | H170-Gaming 3               | [e83680db56](https://linux-hardware.org/?probe=e83680db56) | Nov 28, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [d813ffb878](https://linux-hardware.org/?probe=d813ffb878) | Nov 28, 2021 |
| Gigabyte      | AB350M-DS3H V2-CF           | [5d5d624d8c](https://linux-hardware.org/?probe=5d5d624d8c) | Nov 27, 2021 |
| MSI           | B450-A PRO MAX              | [d949cb9963](https://linux-hardware.org/?probe=d949cb9963) | Nov 27, 2021 |
| Dell          | 06D7TR A00                  | [d980b32136](https://linux-hardware.org/?probe=d980b32136) | Nov 27, 2021 |
| ASRock        | H81M-HG4 R4.0               | [c23e7e890b](https://linux-hardware.org/?probe=c23e7e890b) | Nov 27, 2021 |
| ASUSTek       | M4A77T/USB3                 | [e23dea02cf](https://linux-hardware.org/?probe=e23dea02cf) | Nov 26, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | [1e4799819e](https://linux-hardware.org/?probe=1e4799819e) | Nov 26, 2021 |
| Gigabyte      | B550 AORUS ELITE            | [faf9c22988](https://linux-hardware.org/?probe=faf9c22988) | Nov 26, 2021 |
| ASUSTek       | Maximus IV GENE-Z           | [89729fef47](https://linux-hardware.org/?probe=89729fef47) | Nov 25, 2021 |
| Apple         | Mac-F221BEC8                | [f4f5c37779](https://linux-hardware.org/?probe=f4f5c37779) | Nov 25, 2021 |
| Gigabyte      | Z690 UD DDR4                | [b6ffc90d4e](https://linux-hardware.org/?probe=b6ffc90d4e) | Nov 25, 2021 |
| MSI           | B550-A PRO                  | [b90083da69](https://linux-hardware.org/?probe=b90083da69) | Nov 24, 2021 |
| Apple         | Mac-F221BEC8                | [e606757d4a](https://linux-hardware.org/?probe=e606757d4a) | Nov 24, 2021 |
| Dell          | 0C522T A03                  | [96fec5d214](https://linux-hardware.org/?probe=96fec5d214) | Nov 24, 2021 |
| Gigabyte      | B550 AORUS PRO              | [35801f40df](https://linux-hardware.org/?probe=35801f40df) | Nov 24, 2021 |
| Dell          | 0C522T A03                  | [79ee4911cb](https://linux-hardware.org/?probe=79ee4911cb) | Nov 24, 2021 |
| MSI           | A55M-E33                    | [e6616870b6](https://linux-hardware.org/?probe=e6616870b6) | Nov 24, 2021 |
| HP            | 1906                        | [8ec5c16fc7](https://linux-hardware.org/?probe=8ec5c16fc7) | Nov 24, 2021 |
| HP            | 83E1                        | [7598ac7e6c](https://linux-hardware.org/?probe=7598ac7e6c) | Nov 23, 2021 |
| ASUSTek       | Maximus IV GENE-Z           | [dab6e17223](https://linux-hardware.org/?probe=dab6e17223) | Nov 23, 2021 |
| Lenovo        | 3731 SDK0J40697 WIN 3305... | [c50601fb76](https://linux-hardware.org/?probe=c50601fb76) | Nov 23, 2021 |
| HP            | 0B4Ch D                     | [0c3c7c6bb3](https://linux-hardware.org/?probe=0c3c7c6bb3) | Nov 23, 2021 |
| HP            | 1906                        | [90499fe34d](https://linux-hardware.org/?probe=90499fe34d) | Nov 23, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [91a66a7648](https://linux-hardware.org/?probe=91a66a7648) | Nov 22, 2021 |
| Gigabyte      | GA-MA790X-UD4               | [0a19a35ac4](https://linux-hardware.org/?probe=0a19a35ac4) | Nov 22, 2021 |
| ASRock        | G41M-VS3                    | [35277b1155](https://linux-hardware.org/?probe=35277b1155) | Nov 22, 2021 |
| Pegatron      | 2AD5                        | [8fc4f44be5](https://linux-hardware.org/?probe=8fc4f44be5) | Nov 22, 2021 |
| Gigabyte      | F2A85XM-D3H                 | [1c41d8c34c](https://linux-hardware.org/?probe=1c41d8c34c) | Nov 22, 2021 |
| ASRock        | X570 Phantom Gaming 4       | [683697e6ee](https://linux-hardware.org/?probe=683697e6ee) | Nov 21, 2021 |
| MSI           | B450M-A PRO MAX             | [92375d0ecc](https://linux-hardware.org/?probe=92375d0ecc) | Nov 21, 2021 |
| Dell          | 0M859N A00                  | [2fa52f3236](https://linux-hardware.org/?probe=2fa52f3236) | Nov 21, 2021 |
| Gigabyte      | B450M DS3H-CF               | [faec9a8f8b](https://linux-hardware.org/?probe=faec9a8f8b) | Nov 21, 2021 |
| HP            | 3048h                       | [e38eb769b5](https://linux-hardware.org/?probe=e38eb769b5) | Nov 20, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [44d1a95b0b](https://linux-hardware.org/?probe=44d1a95b0b) | Nov 20, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | [3b34362c42](https://linux-hardware.org/?probe=3b34362c42) | Nov 19, 2021 |
| ASUSTek       | A68HM-K                     | [8bf7660808](https://linux-hardware.org/?probe=8bf7660808) | Nov 19, 2021 |
| ASUSTek       | H87-PRO                     | [02b2e4cb00](https://linux-hardware.org/?probe=02b2e4cb00) | Nov 19, 2021 |
| ASUSTek       | H87-PRO                     | [181c56512d](https://linux-hardware.org/?probe=181c56512d) | Nov 19, 2021 |
| Dell          | 0YNVJG A01                  | [00f5cc73fe](https://linux-hardware.org/?probe=00f5cc73fe) | Nov 19, 2021 |
| Dell          | 0YNVJG A01                  | [fbedd3af33](https://linux-hardware.org/?probe=fbedd3af33) | Nov 19, 2021 |
| Pegatron      | 2AD5                        | [839b5c24aa](https://linux-hardware.org/?probe=839b5c24aa) | Nov 19, 2021 |
| MSI           | B450 TOMAHAWK               | [6a1607ab9d](https://linux-hardware.org/?probe=6a1607ab9d) | Nov 18, 2021 |
| MSI           | MPG X570 GAMING PRO CARB... | [c8a6893780](https://linux-hardware.org/?probe=c8a6893780) | Nov 18, 2021 |
| MSI           | A320M-A PRO MAX             | [d9f71fda8f](https://linux-hardware.org/?probe=d9f71fda8f) | Nov 18, 2021 |
| Dell          | 0C27VV A01                  | [34aff3ab72](https://linux-hardware.org/?probe=34aff3ab72) | Nov 18, 2021 |
| Gigabyte      | B450M DS3H-CF               | [f35f04cabd](https://linux-hardware.org/?probe=f35f04cabd) | Nov 18, 2021 |
| ASUSTek       | ROG CROSSHAIR VI HERO       | [50535d277c](https://linux-hardware.org/?probe=50535d277c) | Nov 18, 2021 |
| ASUSTek       | PRIME B360M-K               | [3b2165faa8](https://linux-hardware.org/?probe=3b2165faa8) | Nov 18, 2021 |
| Gigabyte      | B550M DS3H                  | [93c3ab9ed1](https://linux-hardware.org/?probe=93c3ab9ed1) | Nov 18, 2021 |
| Gigabyte      | H97M-D3H                    | [f6dc8337e7](https://linux-hardware.org/?probe=f6dc8337e7) | Nov 18, 2021 |
| MSI           | Z77A-G43                    | [04db0a2350](https://linux-hardware.org/?probe=04db0a2350) | Nov 17, 2021 |
| ASRock        | X470 Master SLI             | [c48f95d233](https://linux-hardware.org/?probe=c48f95d233) | Nov 17, 2021 |
| Gigabyte      | H370M DS3H-CF               | [c69f79e654](https://linux-hardware.org/?probe=c69f79e654) | Nov 17, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [ddfb1c2b1a](https://linux-hardware.org/?probe=ddfb1c2b1a) | Nov 17, 2021 |
| Dell          | 0GY6Y8 A02                  | [61734716ea](https://linux-hardware.org/?probe=61734716ea) | Nov 16, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [9404dfb1fe](https://linux-hardware.org/?probe=9404dfb1fe) | Nov 16, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [3412d5cf0b](https://linux-hardware.org/?probe=3412d5cf0b) | Nov 16, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [bdd9599f2f](https://linux-hardware.org/?probe=bdd9599f2f) | Nov 16, 2021 |
| ASUSTek       | M2N-E                       | [8da42387a5](https://linux-hardware.org/?probe=8da42387a5) | Nov 15, 2021 |
| Gigabyte      | B560M DS3H                  | [97ed26b846](https://linux-hardware.org/?probe=97ed26b846) | Nov 15, 2021 |
| ASRock        | B450 Pro4                   | [098387cb9c](https://linux-hardware.org/?probe=098387cb9c) | Nov 15, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [bc6a3771aa](https://linux-hardware.org/?probe=bc6a3771aa) | Nov 13, 2021 |
| ASUSTek       | M3A78-EM                    | [e1cc8b1ee3](https://linux-hardware.org/?probe=e1cc8b1ee3) | Nov 13, 2021 |
| ASUSTek       | H61M-CS                     | [22858e9ab9](https://linux-hardware.org/?probe=22858e9ab9) | Nov 13, 2021 |
| Apple         | Mac-F221BEC8                | [5991ba5f44](https://linux-hardware.org/?probe=5991ba5f44) | Nov 12, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [e85856bbef](https://linux-hardware.org/?probe=e85856bbef) | Nov 12, 2021 |
| Dell          | 0DXJD9 A00                  | [e9abfeb7a2](https://linux-hardware.org/?probe=e9abfeb7a2) | Nov 11, 2021 |
| Intel         | D33217GKE G69901-205        | [a922d5f3fc](https://linux-hardware.org/?probe=a922d5f3fc) | Nov 10, 2021 |
| MSI           | Z390-A PRO                  | [ca1489298b](https://linux-hardware.org/?probe=ca1489298b) | Nov 10, 2021 |
| Gigabyte      | X570 UD                     | [c5ae0c1fca](https://linux-hardware.org/?probe=c5ae0c1fca) | Nov 09, 2021 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | [189e19c60d](https://linux-hardware.org/?probe=189e19c60d) | Nov 09, 2021 |
| Dell          | 040DDP A01                  | [3587a95d63](https://linux-hardware.org/?probe=3587a95d63) | Nov 09, 2021 |
| Intel         | D33217GKE G69901-205        | [dd1ddaf74f](https://linux-hardware.org/?probe=dd1ddaf74f) | Nov 09, 2021 |
| Dell          | 0HD5W2 A00                  | [09cae8a245](https://linux-hardware.org/?probe=09cae8a245) | Nov 09, 2021 |
| HP            | 2215                        | [4e65fa6078](https://linux-hardware.org/?probe=4e65fa6078) | Nov 09, 2021 |
| Gigabyte      | EP45-DS3L                   | [fdbec54288](https://linux-hardware.org/?probe=fdbec54288) | Nov 08, 2021 |
| Gigabyte      | H97M-D3H                    | [74b5acd6cd](https://linux-hardware.org/?probe=74b5acd6cd) | Nov 08, 2021 |
| ASRock        | A300M-STX                   | [a7510caa6d](https://linux-hardware.org/?probe=a7510caa6d) | Nov 08, 2021 |
| ASRock        | A300M-STX                   | [2eebb6842a](https://linux-hardware.org/?probe=2eebb6842a) | Nov 08, 2021 |
| Seco          | C40 C                       | [27bff03d0c](https://linux-hardware.org/?probe=27bff03d0c) | Nov 08, 2021 |
| MSI           | X570-A PRO                  | [0e47ec7819](https://linux-hardware.org/?probe=0e47ec7819) | Nov 08, 2021 |
| ASUSTek       | PRIME B550M-A               | [ef16e3ad0f](https://linux-hardware.org/?probe=ef16e3ad0f) | Nov 07, 2021 |
| Gigabyte      | EP45-DS3L                   | [3533adc65b](https://linux-hardware.org/?probe=3533adc65b) | Nov 07, 2021 |
| Dell          | 0C522T A03                  | [43d8e3d9d8](https://linux-hardware.org/?probe=43d8e3d9d8) | Nov 07, 2021 |
| ABIT          | AX78                        | [3d56ae3738](https://linux-hardware.org/?probe=3d56ae3738) | Nov 06, 2021 |
| MSI           | MEG X570 UNIFY              | [37685b5198](https://linux-hardware.org/?probe=37685b5198) | Nov 06, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [6cce11439f](https://linux-hardware.org/?probe=6cce11439f) | Nov 06, 2021 |
| ASUSTek       | M5A97                       | [f8ce8bca36](https://linux-hardware.org/?probe=f8ce8bca36) | Nov 05, 2021 |
| MSI           | Z97M-G43                    | [7b0e15a051](https://linux-hardware.org/?probe=7b0e15a051) | Nov 05, 2021 |
| ASUSTek       | Z170 PRO GAMING             | [ad6e327cf5](https://linux-hardware.org/?probe=ad6e327cf5) | Nov 05, 2021 |
| ASRock        | G41M-VS3                    | [bf54c2ee53](https://linux-hardware.org/?probe=bf54c2ee53) | Nov 04, 2021 |
| Gigabyte      | H97M-D3H                    | [fa84d0d544](https://linux-hardware.org/?probe=fa84d0d544) | Nov 04, 2021 |
| ASUSTek       | PRIME Z370-P                | [50301dd3e3](https://linux-hardware.org/?probe=50301dd3e3) | Nov 04, 2021 |
| Gigabyte      | B150M-D3H-CF                | [f5ef935897](https://linux-hardware.org/?probe=f5ef935897) | Nov 04, 2021 |
| Gigabyte      | H61M-S2V-B3                 | [5baf0ce3af](https://linux-hardware.org/?probe=5baf0ce3af) | Nov 04, 2021 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [14c9dda4cd](https://linux-hardware.org/?probe=14c9dda4cd) | Nov 04, 2021 |
| MSI           | B450M MORTAR                | [00a97d0eba](https://linux-hardware.org/?probe=00a97d0eba) | Nov 03, 2021 |
| Dell          | 0YNVJG A01                  | [0243b19a08](https://linux-hardware.org/?probe=0243b19a08) | Nov 03, 2021 |
| Dell          | 0YNVJG A01                  | [f7d58b572d](https://linux-hardware.org/?probe=f7d58b572d) | Nov 03, 2021 |
| ASUSTek       | P8Z77-V                     | [c7a18968cf](https://linux-hardware.org/?probe=c7a18968cf) | Nov 03, 2021 |
| ASUSTek       | Z87M-PLUS                   | [c26ea680eb](https://linux-hardware.org/?probe=c26ea680eb) | Nov 03, 2021 |
| Gigabyte      | Z170-D3H-CF                 | [3acf5c243f](https://linux-hardware.org/?probe=3acf5c243f) | Nov 03, 2021 |
| MSI           | MAG B550M MORTAR            | [10a45363fe](https://linux-hardware.org/?probe=10a45363fe) | Nov 03, 2021 |
| ASRock        | G41M-VS3                    | [2ee1cbdc82](https://linux-hardware.org/?probe=2ee1cbdc82) | Nov 03, 2021 |
| MSI           | B365M PRO-VH                | [c2976ad59c](https://linux-hardware.org/?probe=c2976ad59c) | Nov 03, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | [c8716ec9a6](https://linux-hardware.org/?probe=c8716ec9a6) | Nov 03, 2021 |
| MSI           | MPG X570 GAMING PRO CARB... | [93de1508cb](https://linux-hardware.org/?probe=93de1508cb) | Oct 31, 2021 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | [136c409f1a](https://linux-hardware.org/?probe=136c409f1a) | Oct 27, 2021 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | [ae8daa788a](https://linux-hardware.org/?probe=ae8daa788a) | Oct 27, 2021 |
| MSI           | B550-A PRO                  | [91c5853577](https://linux-hardware.org/?probe=91c5853577) | Oct 25, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | [fac95138dc](https://linux-hardware.org/?probe=fac95138dc) | Oct 23, 2021 |
| Foxconn       | H81MXV FAB A                | [b030daf542](https://linux-hardware.org/?probe=b030daf542) | Oct 20, 2021 |
| ASUSTek       | PRIME B460M-A               | [6db5e9be6b](https://linux-hardware.org/?probe=6db5e9be6b) | Oct 19, 2021 |
| ASUSTek       | ROG STRIX B560-G GAMING ... | [746401b748](https://linux-hardware.org/?probe=746401b748) | Oct 18, 2021 |
| MSI           | B350 PC MATE                | [bc716e921b](https://linux-hardware.org/?probe=bc716e921b) | Oct 15, 2021 |
| Dell          | 0WMJ54 A01                  | [01ce3b252c](https://linux-hardware.org/?probe=01ce3b252c) | Oct 14, 2021 |
| ASUSTek       | PRIME B550M-A               | [2ff2eb607a](https://linux-hardware.org/?probe=2ff2eb607a) | Oct 14, 2021 |
| ASUSTek       | PRIME A320I-K               | [eee2a960f5](https://linux-hardware.org/?probe=eee2a960f5) | Oct 11, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [7b26df9bc4](https://linux-hardware.org/?probe=7b26df9bc4) | Oct 10, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | [f850c51db9](https://linux-hardware.org/?probe=f850c51db9) | Oct 10, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | [cfbe862160](https://linux-hardware.org/?probe=cfbe862160) | Oct 10, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [a9ceb4591e](https://linux-hardware.org/?probe=a9ceb4591e) | Oct 09, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [7c210a60ab](https://linux-hardware.org/?probe=7c210a60ab) | Oct 09, 2021 |
| Gigabyte      | H61N-USB3                   | [43ded3a853](https://linux-hardware.org/?probe=43ded3a853) | Oct 09, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [b3d0295208](https://linux-hardware.org/?probe=b3d0295208) | Oct 08, 2021 |
| Gigabyte      | H61N-USB3                   | [75d34f09c4](https://linux-hardware.org/?probe=75d34f09c4) | Oct 06, 2021 |
| MSI           | B550-A PRO                  | [17a03c217e](https://linux-hardware.org/?probe=17a03c217e) | Oct 04, 2021 |
| Gigabyte      | Z170-D3H-CF                 | [103d2198a4](https://linux-hardware.org/?probe=103d2198a4) | Sep 30, 2021 |
| Gigabyte      | Z170-D3H-CF                 | [b6f5c877d4](https://linux-hardware.org/?probe=b6f5c877d4) | Sep 29, 2021 |
| Gigabyte      | H81M-S2H                    | [b8c27bd56c](https://linux-hardware.org/?probe=b8c27bd56c) | Sep 28, 2021 |
| ASRock        | B450M-HDV R4.0              | [2f771e8271](https://linux-hardware.org/?probe=2f771e8271) | Sep 24, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | [e75373a634](https://linux-hardware.org/?probe=e75373a634) | Sep 23, 2021 |
| ASUSTek       | ROG STRIX B360-I GAMING     | [3875512e39](https://linux-hardware.org/?probe=3875512e39) | Sep 14, 2021 |
| ASUSTek       | ROG STRIX B360-I GAMING     | [4fb9ed180b](https://linux-hardware.org/?probe=4fb9ed180b) | Sep 14, 2021 |
| Dell          | 0WMJ54 A01                  | [3231b34d4d](https://linux-hardware.org/?probe=3231b34d4d) | Aug 24, 2021 |
| Dell          | 0WMJ54 A01                  | [a94ad8a323](https://linux-hardware.org/?probe=a94ad8a323) | Aug 22, 2021 |
| HP            | 8055                        | [29f5b9a7ab](https://linux-hardware.org/?probe=29f5b9a7ab) | Aug 12, 2021 |
| Dell          | 0KC9NP A01                  | [142e0703fb](https://linux-hardware.org/?probe=142e0703fb) | Aug 12, 2021 |
| Dell          | 0KC9NP A01                  | [f48bc9ac9d](https://linux-hardware.org/?probe=f48bc9ac9d) | Aug 07, 2021 |
| ASUSTek       | Maximus V FORMULA           | [466ef3bd27](https://linux-hardware.org/?probe=466ef3bd27) | Jul 29, 2021 |
| Dell          | 0KC9NP A01                  | [7dcd16d3fd](https://linux-hardware.org/?probe=7dcd16d3fd) | Jul 14, 2021 |
| Dell          | 0KC9NP A01                  | [eedd464065](https://linux-hardware.org/?probe=eedd464065) | Jul 14, 2021 |
| Dell          | 0KC9NP A01                  | [8d1e68aad0](https://linux-hardware.org/?probe=8d1e68aad0) | Jul 07, 2021 |
| Dell          | 0KC9NP A01                  | [852a8a103d](https://linux-hardware.org/?probe=852a8a103d) | Jul 04, 2021 |
| Dell          | 0KC9NP A01                  | [3a0ca9b90c](https://linux-hardware.org/?probe=3a0ca9b90c) | Jul 01, 2021 |
| Dell          | 0KC9NP A01                  | [3ed1ee1f81](https://linux-hardware.org/?probe=3ed1ee1f81) | Jun 25, 2021 |
| Dell          | 0KC9NP A01                  | [f611d9ec88](https://linux-hardware.org/?probe=f611d9ec88) | Jun 23, 2021 |
| ASUSTek       | Maximus V FORMULA           | [95ba18d5da](https://linux-hardware.org/?probe=95ba18d5da) | Jun 23, 2021 |
| Dell          | 0KC9NP A01                  | [511e8019e0](https://linux-hardware.org/?probe=511e8019e0) | Jun 19, 2021 |
| Dell          | 0KC9NP A01                  | [6687380bd7](https://linux-hardware.org/?probe=6687380bd7) | Jun 18, 2021 |
| Gigabyte      | F2A88XN-WIFI                | [c22e6d8669](https://linux-hardware.org/?probe=c22e6d8669) | May 25, 2021 |
| ASUSTek       | Maximus V FORMULA           | [3e15dd7136](https://linux-hardware.org/?probe=3e15dd7136) | May 19, 2021 |
| ECS           | MCP61M-M3                   | [2e5b21af19](https://linux-hardware.org/?probe=2e5b21af19) | Apr 17, 2021 |
| ASUSTek       | PRIME X570-PRO              | [3f7cbcea74](https://linux-hardware.org/?probe=3f7cbcea74) | Apr 14, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                                       | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| 5.15.6-200.fc35.x86_64                                        | 29       | 8.43%   |
| 5.14.10-300.fc35.x86_64                                       | 23       | 6.69%   |
| 5.15.12-200.fc35.x86_64                                       | 21       | 6.1%    |
| 5.14.18-300.fc35.x86_64                                       | 20       | 5.81%   |
| 5.16.9-200.fc35.x86_64                                        | 19       | 5.52%   |
| 5.14.17-301.fc35.x86_64                                       | 17       | 4.94%   |
| 5.14.16-301.fc35.x86_64                                       | 17       | 4.94%   |
| 5.15.16-200.fc35.x86_64                                       | 16       | 4.65%   |
| 5.15.18-200.fc35.x86_64                                       | 15       | 4.36%   |
| 5.14.14-300.fc35.x86_64                                       | 14       | 4.07%   |
| 5.16.5-200.fc35.x86_64                                        | 13       | 3.78%   |
| 5.15.14-200.fc35.x86_64                                       | 13       | 3.78%   |
| 5.15.8-200.fc35.x86_64                                        | 12       | 3.49%   |
| 5.14.15-300.fc35.x86_64                                       | 11       | 3.2%    |
| 5.15.13-200.fc35.x86_64                                       | 10       | 2.91%   |
| 5.15.11-200.fc35.x86_64                                       | 9        | 2.62%   |
| 5.15.15-200.fc35.x86_64                                       | 7        | 2.03%   |
| 5.15.17-200.fc35.x86_64                                       | 6        | 1.74%   |
| 5.15.10-200.fc35.x86_64                                       | 6        | 1.74%   |
| 5.16.8-200.fc35.x86_64                                        | 5        | 1.45%   |
| 5.16.7-200.fc35.x86_64                                        | 5        | 1.45%   |
| 5.15.5-200.fc35.x86_64                                        | 5        | 1.45%   |
| 5.15.4-201.fc35.x86_64                                        | 5        | 1.45%   |
| 5.14.9-300.fc35.x86_64                                        | 5        | 1.45%   |
| 5.15.7-200.fc35.x86_64                                        | 4        | 1.16%   |
| 5.14.0-60.fc35.x86_64                                         | 3        | 0.87%   |
| 5.16.11-200.fc35.x86_64                                       | 2        | 0.58%   |
| 5.14.20-300.fc35.x86_64                                       | 2        | 0.58%   |
| 5.12.0-0.rc7.189.fc35.x86_64                                  | 2        | 0.58%   |
| 5.8.15-301.fc33.x86_64                                        | 1        | 0.29%   |
| 5.16.4-200.fc35.x86_64                                        | 1        | 0.29%   |
| 5.16.2-225.vanilla.1.fc35.x86_64                              | 1        | 0.29%   |
| 5.16.2-200.fc35.x86_64                                        | 1        | 0.29%   |
| 5.16.0-0.rc6.41.vanilla.1.fc35.x86_64                         | 1        | 0.29%   |
| 5.16.0-0.rc2.18.vanilla.1.fc35.x86_64                         | 1        | 0.29%   |
| 5.16.0-0.rc1.20211115git8ab774587903.14.vanilla.1.fc35.x86_64 | 1        | 0.29%   |
| 5.15.5-xm1tt.0.fc35.x86_64                                    | 1        | 0.29%   |
| 5.15.4-xm1.0.fc35.x86_64                                      | 1        | 0.29%   |
| 5.15.2_tkg_bmq                                                | 1        | 0.29%   |
| 5.15.0-500.chinfo.fc35.x86_64                                 | 1        | 0.29%   |
| 5.15.0-0.rc7.20211028git1fc596a56b33.56.vanilla.1.fc35.x86_64 | 1        | 0.29%   |
| 5.14.8-lqx1.0.fc35.x86_64                                     | 1        | 0.29%   |
| 5.14.7-300.fc35.x86_64                                        | 1        | 0.29%   |
| 5.14.6-300.fc35.x86_64                                        | 1        | 0.29%   |
| 5.14.18-301.fsync.fc35.x86_64                                 | 1        | 0.29%   |
| 5.14.13_MY                                                    | 1        | 0.29%   |
| 5.14.1-300.fc35.x86_64                                        | 1        | 0.29%   |
| 5.14.0-0.rc6.46.fc35.x86_64                                   | 1        | 0.29%   |
| 5.13.7-200.fc34.x86_64                                        | 1        | 0.29%   |
| 5.13.0-58.fc35.x86_64                                         | 1        | 0.29%   |
| 5.13.0-0.rc7.20210623git0c18f29aae7c.53.fc35.x86_64           | 1        | 0.29%   |
| 5.13.0-0.rc6.45.fc35.x86_64                                   | 1        | 0.29%   |
| 5.13.0-0.rc2.20210521git79a106fc6585.22.fc35.x86_64           | 1        | 0.29%   |
| 5.13.0-0.rc2.19.fc35.x86_64                                   | 1        | 0.29%   |
| 5.13.0-0.rc1.13.fc35.x86_64                                   | 1        | 0.29%   |
| 5.11.13-300.fc34.x86_64                                       | 1        | 0.29%   |
| 5.10.15-200.fc33.x86_64                                       | 1        | 0.29%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.6  | 29       | 8.53%   |
| 5.14.10 | 23       | 6.76%   |
| 5.15.12 | 21       | 6.18%   |
| 5.14.18 | 21       | 6.18%   |
| 5.16.9  | 19       | 5.59%   |
| 5.14.17 | 17       | 5%      |
| 5.14.16 | 17       | 5%      |
| 5.15.16 | 16       | 4.71%   |
| 5.15.18 | 15       | 4.41%   |
| 5.14.14 | 14       | 4.12%   |
| 5.16.5  | 13       | 3.82%   |
| 5.15.14 | 13       | 3.82%   |
| 5.15.8  | 12       | 3.53%   |
| 5.14.15 | 11       | 3.24%   |
| 5.15.13 | 10       | 2.94%   |
| 5.15.11 | 9        | 2.65%   |
| 5.15.15 | 7        | 2.06%   |
| 5.15.5  | 6        | 1.76%   |
| 5.15.4  | 6        | 1.76%   |
| 5.15.17 | 6        | 1.76%   |
| 5.15.10 | 6        | 1.76%   |
| 5.16.8  | 5        | 1.47%   |
| 5.16.7  | 5        | 1.47%   |
| 5.14.9  | 5        | 1.47%   |
| 5.15.7  | 4        | 1.18%   |
| 5.14.0  | 4        | 1.18%   |
| 5.13.0  | 3        | 0.88%   |
| 5.16.2  | 2        | 0.59%   |
| 5.16.11 | 2        | 0.59%   |
| 5.16.0  | 2        | 0.59%   |
| 5.15.0  | 2        | 0.59%   |
| 5.14.20 | 2        | 0.59%   |
| 5.12.0  | 2        | 0.59%   |
| 5.8.15  | 1        | 0.29%   |
| 5.16.4  | 1        | 0.29%   |
| 5.15.2  | 1        | 0.29%   |
| 5.14.8  | 1        | 0.29%   |
| 5.14.7  | 1        | 0.29%   |
| 5.14.6  | 1        | 0.29%   |
| 5.14.13 | 1        | 0.29%   |
| 5.14.1  | 1        | 0.29%   |
| 5.13.7  | 1        | 0.29%   |
| 5.11.13 | 1        | 0.29%   |
| 5.10.15 | 1        | 0.29%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 148      | 45.96%  |
| 5.14    | 117      | 36.34%  |
| 5.16    | 48       | 14.91%  |
| 5.13    | 4        | 1.24%   |
| 5.12    | 2        | 0.62%   |
| 5.8     | 1        | 0.31%   |
| 5.11    | 1        | 0.31%   |
| 5.10    | 1        | 0.31%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 307      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 229      | 74.11%  |
| KDE5          | 36       | 11.65%  |
| Unknown       | 15       | 4.85%   |
| X-Cinnamon    | 8        | 2.59%   |
| Cinnamon      | 7        | 2.27%   |
| MATE          | 5        | 1.62%   |
| XFCE          | 3        | 0.97%   |
| KDE           | 3        | 0.97%   |
| GNOME Classic | 2        | 0.65%   |
| LXDE          | 1        | 0.32%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 163      | 52.24%  |
| X11     | 126      | 40.38%  |
| Tty     | 15       | 4.81%   |
| Unknown | 8        | 2.56%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 167      | 54.4%   |
| GDM     | 96       | 31.27%  |
| SDDM    | 22       | 7.17%   |
| LightDM | 22       | 7.17%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_US      | 141      | 45.93%  |
| ru_RU      | 20       | 6.51%   |
| en_GB      | 19       | 6.19%   |
| pt_BR      | 17       | 5.54%   |
| de_DE      | 15       | 4.89%   |
| en_AU      | 11       | 3.58%   |
| fr_FR      | 10       | 3.26%   |
| es_ES      | 9        | 2.93%   |
| pl_PL      | 7        | 2.28%   |
| en_CA      | 5        | 1.63%   |
| it_IT      | 4        | 1.3%    |
| es_MX      | 4        | 1.3%    |
| es_CO      | 4        | 1.3%    |
| nl_BE      | 3        | 0.98%   |
| fr_CH      | 3        | 0.98%   |
| cs_CZ      | 3        | 0.98%   |
| ru_UA      | 2        | 0.65%   |
| es_CL      | 2        | 0.65%   |
| en_NZ      | 2        | 0.65%   |
| en_IE      | 2        | 0.65%   |
| de_AT      | 2        | 0.65%   |
| ar_SA      | 2        | 0.65%   |
| Unknown    | 2        | 0.65%   |
| tr_TR      | 1        | 0.33%   |
| sv_SE      | 1        | 0.33%   |
| sr_RS      | 1        | 0.33%   |
| ro_RO      | 1        | 0.33%   |
| pt_PT      | 1        | 0.33%   |
| pa_IN      | 1        | 0.33%   |
| nl_NL      | 1        | 0.33%   |
| ja_JP      | 1        | 0.33%   |
| hu_HU      | 1        | 0.33%   |
| fr_BE      | 1        | 0.33%   |
| es_VE      | 1        | 0.33%   |
| en_US.UTF8 | 1        | 0.33%   |
| en_IN      | 1        | 0.33%   |
| en_IL      | 1        | 0.33%   |
| el_GR      | 1        | 0.33%   |
| de_CH      | 1        | 0.33%   |
| ca_ES      | 1        | 0.33%   |
| C          | 1        | 0.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 205      | 66.13%  |
| BIOS | 105      | 33.87%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Btrfs   | 207      | 66.77%  |
| Ext4    | 87       | 28.06%  |
| Xfs     | 14       | 4.52%   |
| Overlay | 1        | 0.32%   |
| Ext3    | 1        | 0.32%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 166      | 53.72%  |
| GPT     | 116      | 37.54%  |
| MBR     | 27       | 8.74%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 263      | 85.39%  |
| Yes       | 45       | 14.61%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 236      | 75.64%  |
| Yes       | 76       | 24.36%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 83       | 27.04%  |
| Gigabyte Technology | 79       | 25.73%  |
| MSI                 | 55       | 17.92%  |
| Dell                | 22       | 7.17%   |
| ASRock              | 18       | 5.86%   |
| Hewlett-Packard     | 12       | 3.91%   |
| Lenovo              | 11       | 3.58%   |
| Fujitsu             | 4        | 1.3%    |
| ECS                 | 3        | 0.98%   |
| XFX                 | 2        | 0.65%   |
| Supermicro          | 2        | 0.65%   |
| Intel               | 2        | 0.65%   |
| Gateway             | 2        | 0.65%   |
| Apple               | 2        | 0.65%   |
| Seco                | 1        | 0.33%   |
| Pegatron            | 1        | 0.33%   |
| PCWare              | 1        | 0.33%   |
| JINGSHA             | 1        | 0.33%   |
| Huanan              | 1        | 0.33%   |
| Foxconn             | 1        | 0.33%   |
| Biostar             | 1        | 0.33%   |
| BESSTAR Tech        | 1        | 0.33%   |
| Acer                | 1        | 0.33%   |
| ABIT                | 1        | 0.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| ASUS All Series                  | 7        | 2.28%   |
| MSI MS-7C56                      | 4        | 1.3%    |
| MSI MS-7D25                      | 3        | 0.98%   |
| MSI MS-7C84                      | 3        | 0.98%   |
| MSI MS-7B89                      | 3        | 0.98%   |
| MSI MS-7B86                      | 3        | 0.98%   |
| Gigabyte B450M DS3H              | 3        | 0.98%   |
| Gigabyte B450 AORUS M            | 3        | 0.98%   |
| ASUS ROG STRIX B450-F GAMING     | 3        | 0.98%   |
| MSI MS-7C95                      | 2        | 0.65%   |
| MSI MS-7C94                      | 2        | 0.65%   |
| MSI MS-7C91                      | 2        | 0.65%   |
| MSI MS-7C52                      | 2        | 0.65%   |
| MSI MS-7B93                      | 2        | 0.65%   |
| MSI MS-7B85                      | 2        | 0.65%   |
| MSI MS-7B10                      | 2        | 0.65%   |
| MSI MS-7A34                      | 2        | 0.65%   |
| MSI MS-7A33                      | 2        | 0.65%   |
| Gigabyte Z690 UD DDR4            | 2        | 0.65%   |
| Gigabyte Z390 I AORUS PRO WIFI   | 2        | 0.65%   |
| Gigabyte Z390 AORUS MASTER       | 2        | 0.65%   |
| Gigabyte X570 AORUS MASTER       | 2        | 0.65%   |
| Gigabyte H97M-D3H                | 2        | 0.65%   |
| Dell OptiPlex 7010               | 2        | 0.65%   |
| Dell OptiPlex 3020               | 2        | 0.65%   |
| ASUS Z170 PRO GAMING             | 2        | 0.65%   |
| ASUS TUF GAMING B550M-PLUS       | 2        | 0.65%   |
| ASUS TUF GAMING B550-PLUS        | 2        | 0.65%   |
| ASUS ROG STRIX B550-F GAMING     | 2        | 0.65%   |
| ASUS ROG Maximus XI FORMULA      | 2        | 0.65%   |
| ASUS ROG CROSSHAIR VIII HERO     | 2        | 0.65%   |
| ASUS ROG CROSSHAIR VII HERO      | 2        | 0.65%   |
| ASRock B450 Pro4                 | 2        | 0.65%   |
| Apple MacPro5,1                  | 2        | 0.65%   |
| XFX nForce 780i 3-Way SLI        | 1        | 0.33%   |
| XFX MI-A78S-8209 Ver1.1          | 1        | 0.33%   |
| Supermicro X9DRW                 | 1        | 0.33%   |
| Supermicro PIO-617R-TLN4F+-ST031 | 1        | 0.33%   |
| Seco C40                         | 1        | 0.33%   |
| Pegatron h9-1350                 | 1        | 0.33%   |
| PCWare IPMH110G                  | 1        | 0.33%   |
| MSI MS-7C96                      | 1        | 0.33%   |
| MSI MS-7C37                      | 1        | 0.33%   |
| MSI MS-7C35                      | 1        | 0.33%   |
| MSI MS-7C31                      | 1        | 0.33%   |
| MSI MS-7C02                      | 1        | 0.33%   |
| MSI MS-7B98                      | 1        | 0.33%   |
| MSI MS-7B79                      | 1        | 0.33%   |
| MSI MS-7B77                      | 1        | 0.33%   |
| MSI MS-7B33                      | 1        | 0.33%   |
| MSI MS-7B07                      | 1        | 0.33%   |
| MSI MS-7A69                      | 1        | 0.33%   |
| MSI MS-7A37                      | 1        | 0.33%   |
| MSI MS-7A31                      | 1        | 0.33%   |
| MSI MS-7A20                      | 1        | 0.33%   |
| MSI MS-7924                      | 1        | 0.33%   |
| MSI MS-7922                      | 1        | 0.33%   |
| MSI MS-7866                      | 1        | 0.33%   |
| MSI MS-7817                      | 1        | 0.33%   |
| MSI MS-7758                      | 1        | 0.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| ASUS ROG                         | 24       | 7.82%   |
| ASUS PRIME                       | 17       | 5.54%   |
| Dell OptiPlex                    | 15       | 4.89%   |
| ASUS TUF                         | 10       | 3.26%   |
| Lenovo ThinkCentre               | 7        | 2.28%   |
| ASUS All                         | 7        | 2.28%   |
| Gigabyte X570                    | 6        | 1.95%   |
| Gigabyte Z390                    | 5        | 1.63%   |
| MSI MS-7C56                      | 4        | 1.3%    |
| Gigabyte B550                    | 4        | 1.3%    |
| Gigabyte B450                    | 4        | 1.3%    |
| ASUS Maximus                     | 4        | 1.3%    |
| MSI MS-7D25                      | 3        | 0.98%   |
| MSI MS-7C84                      | 3        | 0.98%   |
| MSI MS-7B89                      | 3        | 0.98%   |
| MSI MS-7B86                      | 3        | 0.98%   |
| HP EliteDesk                     | 3        | 0.98%   |
| HP Compaq                        | 3        | 0.98%   |
| Gigabyte B450M                   | 3        | 0.98%   |
| Fujitsu ESPRIMO                  | 3        | 0.98%   |
| Dell Precision                   | 3        | 0.98%   |
| MSI MS-7C95                      | 2        | 0.65%   |
| MSI MS-7C94                      | 2        | 0.65%   |
| MSI MS-7C91                      | 2        | 0.65%   |
| MSI MS-7C52                      | 2        | 0.65%   |
| MSI MS-7B93                      | 2        | 0.65%   |
| MSI MS-7B85                      | 2        | 0.65%   |
| MSI MS-7B10                      | 2        | 0.65%   |
| MSI MS-7A34                      | 2        | 0.65%   |
| MSI MS-7A33                      | 2        | 0.65%   |
| HP ProDesk                       | 2        | 0.65%   |
| Gigabyte Z690                    | 2        | 0.65%   |
| Gigabyte TRX40                   | 2        | 0.65%   |
| Gigabyte H97M-D3H                | 2        | 0.65%   |
| Dell XPS                         | 2        | 0.65%   |
| ASUS Z170                        | 2        | 0.65%   |
| ASUS P8Z77-V                     | 2        | 0.65%   |
| ASUS M5A97                       | 2        | 0.65%   |
| ASRock X570                      | 2        | 0.65%   |
| ASRock B450                      | 2        | 0.65%   |
| Apple MacPro5                    | 2        | 0.65%   |
| XFX nForce                       | 1        | 0.33%   |
| XFX MI-A78S-8209                 | 1        | 0.33%   |
| Supermicro X9DRW                 | 1        | 0.33%   |
| Supermicro PIO-617R-TLN4F+-ST031 | 1        | 0.33%   |
| Seco C40                         | 1        | 0.33%   |
| Pegatron h9-1350                 | 1        | 0.33%   |
| PCWare IPMH110G                  | 1        | 0.33%   |
| MSI MS-7C96                      | 1        | 0.33%   |
| MSI MS-7C37                      | 1        | 0.33%   |
| MSI MS-7C35                      | 1        | 0.33%   |
| MSI MS-7C31                      | 1        | 0.33%   |
| MSI MS-7C02                      | 1        | 0.33%   |
| MSI MS-7B98                      | 1        | 0.33%   |
| MSI MS-7B79                      | 1        | 0.33%   |
| MSI MS-7B77                      | 1        | 0.33%   |
| MSI MS-7B33                      | 1        | 0.33%   |
| MSI MS-7B07                      | 1        | 0.33%   |
| MSI MS-7A69                      | 1        | 0.33%   |
| MSI MS-7A37                      | 1        | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 42       | 13.68%  |
| 2020 | 40       | 13.03%  |
| 2019 | 39       | 12.7%   |
| 2021 | 30       | 9.77%   |
| 2014 | 27       | 8.79%   |
| 2017 | 24       | 7.82%   |
| 2013 | 23       | 7.49%   |
| 2012 | 15       | 4.89%   |
| 2016 | 14       | 4.56%   |
| 2015 | 13       | 4.23%   |
| 2011 | 11       | 3.58%   |
| 2010 | 11       | 3.58%   |
| 2009 | 8        | 2.61%   |
| 2008 | 7        | 2.28%   |
| 2006 | 2        | 0.65%   |
| 2007 | 1        | 0.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 307      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 288      | 93.51%  |
| Enabled  | 20       | 6.49%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 307      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 95       | 30.84%  |
| 32.01-64.0  | 73       | 23.7%   |
| 8.01-16.0   | 50       | 16.23%  |
| 4.01-8.0    | 33       | 10.71%  |
| 64.01-256.0 | 28       | 9.09%   |
| 3.01-4.0    | 20       | 6.49%   |
| 24.01-32.0  | 6        | 1.95%   |
| 2.01-3.0    | 2        | 0.65%   |
| 1.01-2.0    | 1        | 0.32%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 91       | 27.41%  |
| 4.01-8.0   | 89       | 26.81%  |
| 3.01-4.0   | 56       | 16.87%  |
| 1.01-2.0   | 45       | 13.55%  |
| 8.01-16.0  | 30       | 9.04%   |
| 0.51-1.0   | 8        | 2.41%   |
| 24.01-32.0 | 7        | 2.11%   |
| 16.01-24.0 | 5        | 1.51%   |
| 0.01-0.5   | 1        | 0.3%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 90       | 28.94%  |
| 1      | 83       | 26.69%  |
| 3      | 71       | 22.83%  |
| 4      | 25       | 8.04%   |
| 5      | 21       | 6.75%   |
| 6      | 12       | 3.86%   |
| 7      | 6        | 1.93%   |
| 14     | 1        | 0.32%   |
| 9      | 1        | 0.32%   |
| 8      | 1        | 0.32%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 207      | 66.99%  |
| Yes       | 102      | 33.01%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 306      | 99.35%  |
| No        | 2        | 0.65%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 162      | 52.77%  |
| Yes       | 145      | 47.23%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 171      | 55.52%  |
| Yes       | 137      | 44.48%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 63       | 20.45%  |
| Germany      | 23       | 7.47%   |
| Brazil       | 21       | 6.82%   |
| Russia       | 20       | 6.49%   |
| UK           | 13       | 4.22%   |
| Spain        | 13       | 4.22%   |
| France       | 13       | 4.22%   |
| Australia    | 13       | 4.22%   |
| Poland       | 11       | 3.57%   |
| Canada       | 11       | 3.57%   |
| Switzerland  | 7        | 2.27%   |
| Czechia      | 7        | 2.27%   |
| Ukraine      | 6        | 1.95%   |
| India        | 6        | 1.95%   |
| Belgium      | 6        | 1.95%   |
| Romania      | 5        | 1.62%   |
| Netherlands  | 5        | 1.62%   |
| Mexico       | 5        | 1.62%   |
| Italy        | 5        | 1.62%   |
| Turkey       | 4        | 1.3%    |
| Colombia     | 4        | 1.3%    |
| Belarus      | 4        | 1.3%    |
| Austria      | 4        | 1.3%    |
| Sweden       | 3        | 0.97%   |
| Norway       | 3        | 0.97%   |
| Hong Kong    | 3        | 0.97%   |
| Greece       | 3        | 0.97%   |
| Chile        | 3        | 0.97%   |
| Saudi Arabia | 2        | 0.65%   |
| Israel       | 2        | 0.65%   |
| Ireland      | 2        | 0.65%   |
| Indonesia    | 2        | 0.65%   |
| Hungary      | 2        | 0.65%   |
| Yemen        | 1        | 0.32%   |
| Venezuela    | 1        | 0.32%   |
| Thailand     | 1        | 0.32%   |
| Slovakia     | 1        | 0.32%   |
| New Zealand  | 1        | 0.32%   |
| Moldova      | 1        | 0.32%   |
| Kyrgyzstan   | 1        | 0.32%   |
| Kazakhstan   | 1        | 0.32%   |
| Japan        | 1        | 0.32%   |
| Estonia      | 1        | 0.32%   |
| Egypt        | 1        | 0.32%   |
| Cyprus       | 1        | 0.32%   |
| Bolivia      | 1        | 0.32%   |
| Argentina    | 1        | 0.32%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Sydney               | 8        | 2.55%   |
| Berlin               | 6        | 1.91%   |
| Moscow               | 5        | 1.59%   |
| Vienna               | 4        | 1.27%   |
| Minsk                | 3        | 0.96%   |
| Madrid               | 3        | 0.96%   |
| Kyiv                 | 3        | 0.96%   |
| Istanbul             | 3        | 0.96%   |
| Zurich               | 2        | 0.64%   |
| Weinsberg            | 2        | 0.64%   |
| Warsaw               | 2        | 0.64%   |
| Villavicencio        | 2        | 0.64%   |
| Ufa                  | 2        | 0.64%   |
| TimiÈ™oara        | 2        | 0.64%   |
| St Petersburg        | 2        | 0.64%   |
| SÃ£o Paulo         | 2        | 0.64%   |
| Rio de Janeiro       | 2        | 0.64%   |
| Raleigh              | 2        | 0.64%   |
| Pompano Beach        | 2        | 0.64%   |
| Pennsville           | 2        | 0.64%   |
| Los Angeles          | 2        | 0.64%   |
| Krakow               | 2        | 0.64%   |
| Dallas               | 2        | 0.64%   |
| Brussels             | 2        | 0.64%   |
| Brno                 | 2        | 0.64%   |
| Brisbane             | 2        | 0.64%   |
| BrasÃ­lia          | 2        | 0.64%   |
| Bainbridge Island    | 2        | 0.64%   |
| Athens               | 2        | 0.64%   |
| Amsterdam            | 2        | 0.64%   |
| ZlÃ­n              | 1        | 0.32%   |
| Zheleznogorsk        | 1        | 0.32%   |
| Zgorzelec            | 1        | 0.32%   |
| Zeven                | 1        | 0.32%   |
| Zaratamo             | 1        | 0.32%   |
| Zaporizhzhya         | 1        | 0.32%   |
| Zapopan              | 1        | 0.32%   |
| Yverdon-les-Bains    | 1        | 0.32%   |
| Yekaterinburg        | 1        | 0.32%   |
| Winterthur           | 1        | 0.32%   |
| Winchester           | 1        | 0.32%   |
| Wilmington           | 1        | 0.32%   |
| Willowbrook          | 1        | 0.32%   |
| Westerronfeld        | 1        | 0.32%   |
| Waynesville          | 1        | 0.32%   |
| Wateringen           | 1        | 0.32%   |
| Voronezh             | 1        | 0.32%   |
| Volgograd            | 1        | 0.32%   |
| VitÃ³ria           | 1        | 0.32%   |
| Vinnytsia            | 1        | 0.32%   |
| Verrieres-le-Buisson | 1        | 0.32%   |
| Veresegyhaz          | 1        | 0.32%   |
| Vecindario           | 1        | 0.32%   |
| Vancouver            | 1        | 0.32%   |
| Valkenswaard         | 1        | 0.32%   |
| Valencia             | 1        | 0.32%   |
| Vaellingby           | 1        | 0.32%   |
| Ulan-Ude             | 1        | 0.32%   |
| Udine                | 1        | 0.32%   |
| Tung Chung           | 1        | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 121      | 217    | 19.3%   |
| Seagate                     | 111      | 173    | 17.7%   |
| WDC                         | 105      | 171    | 16.75%  |
| Kingston                    | 41       | 51     | 6.54%   |
| Crucial                     | 39       | 45     | 6.22%   |
| SanDisk                     | 33       | 36     | 5.26%   |
| Toshiba                     | 24       | 34     | 3.83%   |
| A-DATA Technology           | 14       | 18     | 2.23%   |
| Phison                      | 13       | 21     | 2.07%   |
| Hitachi                     | 13       | 15     | 2.07%   |
| Intel                       | 12       | 17     | 1.91%   |
| SPCC                        | 10       | 12     | 1.59%   |
| Patriot                     | 8        | 10     | 1.28%   |
| XPG                         | 6        | 8      | 0.96%   |
| Corsair                     | 6        | 6      | 0.96%   |
| Unknown                     | 5        | 6      | 0.8%    |
| Silicon Motion              | 5        | 5      | 0.8%    |
| HGST                        | 5        | 9      | 0.8%    |
| SABRENT                     | 4        | 4      | 0.64%   |
| Micron/Crucial Technology   | 4        | 5      | 0.64%   |
| GOODRAM                     | 4        | 4      | 0.64%   |
| SK Hynix                    | 3        | 3      | 0.48%   |
| Lexar                       | 3        | 4      | 0.48%   |
| KingSpec                    | 3        | 3      | 0.48%   |
| Hewlett-Packard             | 3        | 3      | 0.48%   |
| China                       | 3        | 4      | 0.48%   |
| Verbatim                    | 2        | 2      | 0.32%   |
| Realtek Semiconductor       | 2        | 2      | 0.32%   |
| PNY                         | 2        | 3      | 0.32%   |
| MAXIO Technology (Hangzhou) | 2        | 2      | 0.32%   |
| Apacer                      | 2        | 3      | 0.32%   |
| USB 3.0                     | 1        | 2      | 0.16%   |
| Team                        | 1        | 2      | 0.16%   |
| T-FORCE                     | 1        | 1      | 0.16%   |
| SUNEAST                     | 1        | 1      | 0.16%   |
| PLEXTOR                     | 1        | 1      | 0.16%   |
| OWC                         | 1        | 1      | 0.16%   |
| Mushkin                     | 1        | 1      | 0.16%   |
| Micron Technology           | 1        | 1      | 0.16%   |
| MAXTOR                      | 1        | 1      | 0.16%   |
| LS600                       | 1        | 1      | 0.16%   |
| LITEON                      | 1        | 1      | 0.16%   |
| LDLC                        | 1        | 1      | 0.16%   |
| KIOXIA                      | 1        | 2      | 0.16%   |
| Intenso                     | 1        | 4      | 0.16%   |
| HS-SSD-C100                 | 1        | 1      | 0.16%   |
| Dahua                       | 1        | 1      | 0.16%   |
| BIWIN                       | 1        | 1      | 0.16%   |
| ASMT                        | 1        | 1      | 0.16%   |
| Unknown                     | 1        | 1      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Samsung NVMe SSD Drive 500GB        | 21       | 2.75%   |
| Samsung SSD 860 EVO 500GB           | 16       | 2.09%   |
| Seagate ST2000DM008-2FR102 2TB      | 12       | 1.57%   |
| Seagate ST1000DM010-2EP102 1TB      | 10       | 1.31%   |
| Kingston SA400S37480G 480GB SSD     | 9        | 1.18%   |
| Seagate ST3500418AS 500GB           | 8        | 1.05%   |
| Samsung SSD 850 EVO 250GB           | 8        | 1.05%   |
| Samsung NVMe SSD Drive 1TB          | 8        | 1.05%   |
| Seagate ST500DM002-1BD142 500GB     | 7        | 0.92%   |
| Samsung SSD 850 EVO 500GB           | 7        | 0.92%   |
| Kingston SA400S37240G 240GB SSD     | 7        | 0.92%   |
| Samsung SSD 860 EVO 1TB             | 6        | 0.79%   |
| Samsung NVMe SSD Drive 250GB        | 6        | 0.79%   |
| Crucial CT1000MX500SSD1 1TB         | 6        | 0.79%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 5        | 0.65%   |
| WDC WD30EFRX-68EUZN0 3TB            | 5        | 0.65%   |
| Seagate ST4000DM004-2CV104 4TB      | 5        | 0.65%   |
| Seagate ST1000DM003-1ER162 1TB      | 5        | 0.65%   |
| Seagate ST1000DM003-1CH162 1TB      | 5        | 0.65%   |
| Samsung SSD 970 EVO Plus 500GB      | 5        | 0.65%   |
| Samsung SSD 870 EVO 500GB           | 5        | 0.65%   |
| Samsung SSD 870 EVO 1TB             | 5        | 0.65%   |
| Samsung NVMe SSD Drive 2TB          | 5        | 0.65%   |
| Kingston SV300S37A120G 120GB SSD    | 5        | 0.65%   |
| Crucial CT500MX500SSD1 500GB        | 5        | 0.65%   |
| WDC WD10EZEX-08WN4A0 1TB            | 4        | 0.52%   |
| WDC WD10EZEX-00WN4A0 1TB            | 4        | 0.52%   |
| WDC WD1002FAEX-00Z3A0 1TB           | 4        | 0.52%   |
| Toshiba HDWD110 1TB                 | 4        | 0.52%   |
| Sandisk NVMe SSD Drive 1TB          | 4        | 0.52%   |
| Samsung SSD 970 EVO Plus 2TB        | 4        | 0.52%   |
| Samsung SSD 970 EVO Plus 1TB        | 4        | 0.52%   |
| Samsung SSD 970 EVO 250GB           | 4        | 0.52%   |
| Phison NVMe SSD Drive 2TB           | 4        | 0.52%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 3        | 0.39%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 3        | 0.39%   |
| WDC WDS100T3X0C-00SJG0 1TB          | 3        | 0.39%   |
| WDC WDS100T2B0A-00SM50 1TB SSD      | 3        | 0.39%   |
| WDC WDS100T1X0E-00AFY0 1TB          | 3        | 0.39%   |
| WDC WD5000AADS-00S9B0 500GB         | 3        | 0.39%   |
| Toshiba DT01ACA050 500GB            | 3        | 0.39%   |
| Seagate ST8000DM004-2CX188 8TB      | 3        | 0.39%   |
| Seagate ST4000DM005-2DP166 4TB      | 3        | 0.39%   |
| Seagate ST31000528AS 1TB            | 3        | 0.39%   |
| Seagate ST3000DM008-2DM166 3TB      | 3        | 0.39%   |
| Seagate ST2000DM001-1CH164 2TB      | 3        | 0.39%   |
| SanDisk SSD PLUS 240GB              | 3        | 0.39%   |
| Sandisk NVMe SSD Drive 500GB        | 3        | 0.39%   |
| Samsung SSD 870 QVO 2TB             | 3        | 0.39%   |
| Samsung SSD 860 EVO 250GB           | 3        | 0.39%   |
| Samsung HD103UJ 1TB                 | 3        | 0.39%   |
| SABRENT Disk 1TB                    | 3        | 0.39%   |
| Phison Sabrent 1TB                  | 3        | 0.39%   |
| Micron/Crucial NVMe SSD Drive 500GB | 3        | 0.39%   |
| Kingston SKC2500M81000G 1TB         | 3        | 0.39%   |
| Kingston SA2000M81000G 1TB          | 3        | 0.39%   |
| Crucial CT480BX500SSD1 480GB        | 3        | 0.39%   |
| XPG GAMMIX S11 Pro 1TB              | 2        | 0.26%   |
| WDC WDS200T2B0A-00SM50 2TB SSD      | 2        | 0.26%   |
| WDC WDBNCE0010PNC 1TB SSD           | 2        | 0.26%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 106      | 165    | 43.8%   |
| WDC                 | 83       | 133    | 34.3%   |
| Toshiba             | 21       | 29     | 8.68%   |
| Hitachi             | 13       | 15     | 5.37%   |
| Samsung Electronics | 7        | 9      | 2.89%   |
| HGST                | 5        | 9      | 2.07%   |
| SABRENT             | 3        | 3      | 1.24%   |
| USB 3.0             | 1        | 2      | 0.41%   |
| MAXTOR              | 1        | 1      | 0.41%   |
| Hewlett-Packard     | 1        | 1      | 0.41%   |
| ASMT                | 1        | 1      | 0.41%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 70       | 117    | 28.23%  |
| Crucial             | 32       | 37     | 12.9%   |
| Kingston            | 31       | 38     | 12.5%   |
| WDC                 | 22       | 28     | 8.87%   |
| SanDisk             | 22       | 23     | 8.87%   |
| A-DATA Technology   | 11       | 15     | 4.44%   |
| SPCC                | 7        | 8      | 2.82%   |
| Patriot             | 7        | 9      | 2.82%   |
| Intel               | 6        | 7      | 2.42%   |
| GOODRAM             | 4        | 4      | 1.61%   |
| KingSpec            | 3        | 3      | 1.21%   |
| China               | 3        | 4      | 1.21%   |
| Verbatim            | 2        | 2      | 0.81%   |
| Toshiba             | 2        | 2      | 0.81%   |
| PNY                 | 2        | 3      | 0.81%   |
| Lexar               | 2        | 2      | 0.81%   |
| Corsair             | 2        | 2      | 0.81%   |
| Apacer              | 2        | 3      | 0.81%   |
| XPG                 | 1        | 2      | 0.4%    |
| Unknown             | 1        | 1      | 0.4%    |
| Team                | 1        | 2      | 0.4%    |
| T-FORCE             | 1        | 1      | 0.4%    |
| SUNEAST             | 1        | 1      | 0.4%    |
| Seagate             | 1        | 2      | 0.4%    |
| SABRENT             | 1        | 1      | 0.4%    |
| PLEXTOR             | 1        | 1      | 0.4%    |
| OWC                 | 1        | 1      | 0.4%    |
| Mushkin             | 1        | 1      | 0.4%    |
| Micron Technology   | 1        | 1      | 0.4%    |
| LS600               | 1        | 1      | 0.4%    |
| LITEON              | 1        | 1      | 0.4%    |
| Intenso             | 1        | 4      | 0.4%    |
| HS-SSD-C100         | 1        | 1      | 0.4%    |
| Hewlett-Packard     | 1        | 1      | 0.4%    |
| Dahua               | 1        | 1      | 0.4%    |
| BIWIN               | 1        | 1      | 0.4%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 195      | 331    | 36.86%  |
| HDD     | 194      | 368    | 36.67%  |
| NVMe    | 129      | 208    | 24.39%  |
| Unknown | 8        | 11     | 1.51%   |
| MMC     | 3        | 3      | 0.57%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 264      | 686    | 63.46%  |
| NVMe | 129      | 208    | 31.01%  |
| SAS  | 20       | 24     | 4.81%   |
| MMC  | 3        | 3      | 0.72%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 196      | 324    | 43.85%  |
| 0.51-1.0   | 134      | 205    | 29.98%  |
| 1.01-2.0   | 54       | 66     | 12.08%  |
| 3.01-4.0   | 26       | 36     | 5.82%   |
| 2.01-3.0   | 16       | 36     | 3.58%   |
| 4.01-10.0  | 16       | 24     | 3.58%   |
| 10.01-20.0 | 5        | 8      | 1.12%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 63       | 20%     |
| 1001-2000      | 62       | 19.68%  |
| 251-500        | 44       | 13.97%  |
| More than 3000 | 43       | 13.65%  |
| 101-250        | 38       | 12.06%  |
| 2001-3000      | 26       | 8.25%   |
| 1-20           | 21       | 6.67%   |
| Unknown        | 10       | 3.17%   |
| 51-100         | 7        | 2.22%   |
| 21-50          | 1        | 0.32%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 63       | 19.57%  |
| 501-1000       | 44       | 13.66%  |
| 21-50          | 40       | 12.42%  |
| 251-500        | 38       | 11.8%   |
| 101-250        | 35       | 10.87%  |
| 51-100         | 34       | 10.56%  |
| 1001-2000      | 30       | 9.32%   |
| More than 3000 | 16       | 4.97%   |
| 2001-3000      | 12       | 3.73%   |
| Unknown        | 10       | 3.11%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Desktops | Drives | Percent |
|-----------------------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                     | 4        | 7      | 8.89%   |
| Seagate ST3500418AS 500GB                           | 3        | 3      | 6.67%   |
| Samsung Electronics SSD 870 EVO 500GB               | 2        | 2      | 4.44%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 1        | 1      | 2.22%   |
| WDC WD5000AAKS-00UU3A0 500GB                        | 1        | 1      | 2.22%   |
| WDC WD30EZRX-00MMMB0 3TB                            | 1        | 1      | 2.22%   |
| WDC WD2500AAKX-753CA1 250GB                         | 1        | 1      | 2.22%   |
| WDC WD15EARS-00S0XB0 1TB                            | 1        | 1      | 2.22%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 1        | 1      | 2.22%   |
| WDC WD10EFRX-68JCSN0 1TB                            | 1        | 1      | 2.22%   |
| WDC WD10EALX-009BA0 1TB                             | 1        | 1      | 2.22%   |
| WDC WD1003FBYX-01Y7B1 1TB                           | 1        | 1      | 2.22%   |
| WDC WD1002FAEX-00Z3A0 1TB                           | 1        | 1      | 2.22%   |
| Toshiba MK6476GSX 640GB                             | 1        | 1      | 2.22%   |
| Team T2535T480G 480GB SSD                           | 1        | 2      | 2.22%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 1        | 1      | 2.22%   |
| Seagate ST500LM000-1EJ162-SSHD 500GB                | 1        | 1      | 2.22%   |
| Seagate ST3500630AS 500GB                           | 1        | 1      | 2.22%   |
| Seagate ST3200822A 200GB                            | 1        | 1      | 2.22%   |
| Seagate ST31000528AS 1TB                            | 1        | 1      | 2.22%   |
| Seagate ST31000524AS 1TB                            | 1        | 1      | 2.22%   |
| Seagate ST3000DM001-1ER166 3TB                      | 1        | 1      | 2.22%   |
| Seagate ST3000DM001-1CH166 3TB                      | 1        | 2      | 2.22%   |
| Seagate ST2000DM001-1CH164 2TB                      | 1        | 1      | 2.22%   |
| Seagate ST2000DL003-9VT166 2TB                      | 1        | 1      | 2.22%   |
| Seagate ST1000DM010-2EP102 1TB                      | 1        | 1      | 2.22%   |
| Seagate ST1000DM003-1ER162 1TB                      | 1        | 1      | 2.22%   |
| SanDisk SD6PP4M-256G-1006 256GB SSD                 | 1        | 1      | 2.22%   |
| Samsung Electronics SSD 970 EVO 250GB               | 1        | 1      | 2.22%   |
| Samsung Electronics HD501LJ 500GB                   | 1        | 2      | 2.22%   |
| Samsung Electronics HD103UJ 1TB                     | 1        | 1      | 2.22%   |
| Micron Technology MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1        | 1      | 2.22%   |
| Kingston SV300S37A240G 240GB SSD                    | 1        | 1      | 2.22%   |
| Kingston SV300S37A120G 120GB SSD                    | 1        | 1      | 2.22%   |
| Intel SSDSC2CT120A3 120GB                           | 1        | 2      | 2.22%   |
| Hitachi HDS5C3020ALA632 2TB                         | 1        | 1      | 2.22%   |
| Crucial CT240M500SSD1 240GB                         | 1        | 1      | 2.22%   |
| Crucial CT128MX100SSD1 128GB                        | 1        | 1      | 2.22%   |
| A-DATA Technology SX8100NP 1TB                      | 1        | 1      | 2.22%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 19       | 23     | 42.22%  |
| WDC                 | 10       | 10     | 22.22%  |
| Samsung Electronics | 5        | 6      | 11.11%  |
| Kingston            | 2        | 2      | 4.44%   |
| Crucial             | 2        | 2      | 4.44%   |
| Toshiba             | 1        | 1      | 2.22%   |
| Team                | 1        | 2      | 2.22%   |
| SanDisk             | 1        | 1      | 2.22%   |
| Micron Technology   | 1        | 1      | 2.22%   |
| Intel               | 1        | 2      | 2.22%   |
| Hitachi             | 1        | 1      | 2.22%   |
| A-DATA Technology   | 1        | 1      | 2.22%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 19       | 23     | 59.38%  |
| WDC                 | 9        | 9      | 28.13%  |
| Samsung Electronics | 2        | 3      | 6.25%   |
| Toshiba             | 1        | 1      | 3.13%   |
| Hitachi             | 1        | 1      | 3.13%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 29       | 37     | 69.05%  |
| SSD  | 11       | 13     | 26.19%  |
| NVMe | 2        | 2      | 4.76%   |

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
| Detected | 174      | 502    | 48.6%   |
| Works    | 143      | 367    | 39.94%  |
| Malfunc  | 41       | 52     | 11.45%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 163      | 33.4%   |
| AMD                          | 139      | 28.48%  |
| Samsung Electronics          | 62       | 12.7%   |
| Sandisk                      | 19       | 3.89%   |
| Phison Electronics           | 18       | 3.69%   |
| ASMedia Technology           | 14       | 2.87%   |
| Kingston Technology Company  | 12       | 2.46%   |
| Micron/Crucial Technology    | 10       | 2.05%   |
| Marvell Technology Group     | 7        | 1.43%   |
| ADATA Technology             | 7        | 1.43%   |
| Silicon Motion               | 6        | 1.23%   |
| JMicron Technology           | 6        | 1.23%   |
| Nvidia                       | 5        | 1.02%   |
| SK Hynix                     | 3        | 0.61%   |
| Realtek Semiconductor        | 3        | 0.61%   |
| Toshiba America Info Systems | 2        | 0.41%   |
| Silicon Image                | 2        | 0.41%   |
| MAXIO Technology (Hangzhou)  | 2        | 0.41%   |
| LSI Logic / Symbios Logic    | 2        | 0.41%   |
| KIOXIA                       | 2        | 0.41%   |
| ULi Electronics              | 1        | 0.2%    |
| Seagate Technology           | 1        | 0.2%    |
| Micron Technology            | 1        | 0.2%    |
| Adaptec                      | 1        | 0.2%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 92       | 15.59%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 43       | 7.29%   |
| AMD 400 Series Chipset SATA Controller                                           | 35       | 5.93%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                         | 24       | 4.07%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 22       | 3.73%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 20       | 3.39%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 18       | 3.05%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 14       | 2.37%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 12       | 2.03%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 12       | 2.03%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 12       | 2.03%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 10       | 1.69%   |
| Phison E12 NVMe Controller                                                       | 10       | 1.69%   |
| Intel SATA Controller [RAID mode]                                                | 10       | 1.69%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                               | 9        | 1.53%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 9        | 1.53%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 8        | 1.36%   |
| AMD 300 Series Chipset SATA Controller                                           | 8        | 1.36%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 7        | 1.19%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 7        | 1.19%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 7        | 1.19%   |
| AMD FCH IDE Controller                                                           | 7        | 1.19%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 7        | 1.19%   |
| Samsung NVMe SSD Controller 980                                                  | 6        | 1.02%   |
| Kingston Company A2000 NVMe SSD                                                  | 6        | 1.02%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 6        | 1.02%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 6        | 1.02%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 5        | 0.85%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                       | 5        | 0.85%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 5        | 0.85%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 5        | 0.85%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 5        | 0.85%   |
| AMD FCH SATA Controller D                                                        | 5        | 0.85%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 4        | 0.68%   |
| JMicron JMB363 SATA/IDE Controller                                               | 4        | 0.68%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 4        | 0.68%   |
| AMD X370 Series Chipset SATA Controller                                          | 4        | 0.68%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 3        | 0.51%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                 | 3        | 0.51%   |
| Kingston Company KC2000 NVMe SSD                                                 | 3        | 0.51%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3        | 0.51%   |
| Intel SSD 660P Series                                                            | 3        | 0.51%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 3        | 0.51%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                              | 3        | 0.51%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                             | 3        | 0.51%   |
| Intel 4 Series Chipset PT IDER Controller                                        | 3        | 0.51%   |
| AMD FCH SATA Controller [IDE mode]                                               | 3        | 0.51%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 2        | 0.34%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                             | 2        | 0.34%   |
| Realtek RTS5763DL NVMe SSD Controller                                            | 2        | 0.34%   |
| Nvidia MCP55 SATA Controller                                                     | 2        | 0.34%   |
| Nvidia MCP55 IDE                                                                 | 2        | 0.34%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 2        | 0.34%   |
| Micron/Crucial Non-Volatile memory controller                                    | 2        | 0.34%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1001                                     | 2        | 0.34%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]          | 2        | 0.34%   |
| KIOXIA Non-Volatile memory controller                                            | 2        | 0.34%   |
| Intel SSD 600P Series                                                            | 2        | 0.34%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 2        | 0.34%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 2        | 0.34%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 283      | 59.45%  |
| NVMe | 129      | 27.1%   |
| IDE  | 42       | 8.82%   |
| RAID | 17       | 3.57%   |
| SAS  | 5        | 1.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 163      | 53.09%  |
| AMD    | 144      | 46.91%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor          | 11       | 3.58%   |
| AMD Ryzen 5 3600 6-Core Processor           | 8        | 2.61%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 7        | 2.28%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 7        | 2.28%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 7        | 2.28%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 7        | 2.28%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 6        | 1.95%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 6        | 1.95%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 6        | 1.95%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 6        | 1.95%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 5        | 1.63%   |
| Intel 12th Gen Core i5-12600K               | 4        | 1.3%    |
| AMD Ryzen 7 2700 Eight-Core Processor       | 4        | 1.3%    |
| AMD Ryzen 5 3600X 6-Core Processor          | 4        | 1.3%    |
| AMD Ryzen 5 2600X Six-Core Processor        | 4        | 1.3%    |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 4        | 1.3%    |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 0.98%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 3        | 0.98%   |
| Intel Core i5-7600K CPU @ 3.80GHz           | 3        | 0.98%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 3        | 0.98%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 3        | 0.98%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 0.98%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 3        | 0.98%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3        | 0.98%   |
| Intel 12th Gen Core i9-12900K               | 3        | 0.98%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 3        | 0.98%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 3        | 0.98%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 3        | 0.98%   |
| Intel Xeon CPU X5680 @ 3.33GHz              | 2        | 0.65%   |
| Intel Core i7-9700F CPU @ 3.00GHz           | 2        | 0.65%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 2        | 0.65%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 2        | 0.65%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 2        | 0.65%   |
| Intel Core i7 CPU 920 @ 2.67GHz             | 2        | 0.65%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 2        | 0.65%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 2        | 0.65%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 2        | 0.65%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2        | 0.65%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2        | 0.65%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 2        | 0.65%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 0.65%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 2        | 0.65%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 2        | 0.65%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 2        | 0.65%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz      | 2        | 0.65%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 2        | 0.65%   |
| AMD Ryzen 7 1700X Eight-Core Processor      | 2        | 0.65%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 2        | 0.65%   |
| AMD Ryzen 3 1200 Quad-Core Processor        | 2        | 0.65%   |
| AMD Phenom II X2 570 Processor              | 2        | 0.65%   |
| AMD FX-8350 Eight-Core Processor            | 2        | 0.65%   |
| AMD FX-8300 Eight-Core Processor            | 2        | 0.65%   |
| AMD Athlon II X2 250 Processor              | 2        | 0.65%   |
| AMD A4-5300 APU with Radeon HD Graphics     | 2        | 0.65%   |
| Intel Xeon CPU X5460 @ 3.16GHz              | 1        | 0.33%   |
| Intel Xeon CPU W3565 @ 3.20GHz              | 1        | 0.33%   |
| Intel Xeon CPU E5-2697 v2 @ 2.70GHz         | 1        | 0.33%   |
| Intel Xeon CPU E5-2673 v3 @ 2.40GHz         | 1        | 0.33%   |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz         | 1        | 0.33%   |
| Intel Xeon CPU E5-2650 0 @ 2.00GHz          | 1        | 0.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 55       | 17.92%  |
| AMD Ryzen 5             | 42       | 13.68%  |
| Intel Core i7           | 41       | 13.36%  |
| AMD Ryzen 7             | 35       | 11.4%   |
| AMD Ryzen 9             | 17       | 5.54%   |
| Intel Xeon              | 14       | 4.56%   |
| Other                   | 13       | 4.23%   |
| Intel Core i3           | 12       | 3.91%   |
| Intel Core i9           | 10       | 3.26%   |
| AMD Ryzen 3             | 7        | 2.28%   |
| AMD FX                  | 7        | 2.28%   |
| Intel Core 2 Duo        | 6        | 1.95%   |
| AMD Ryzen Threadripper  | 5        | 1.63%   |
| Intel Pentium           | 4        | 1.3%    |
| AMD A4                  | 4        | 1.3%    |
| AMD A10                 | 4        | 1.3%    |
| Intel Core 2 Quad       | 3        | 0.98%   |
| AMD Phenom              | 3        | 0.98%   |
| AMD Athlon              | 3        | 0.98%   |
| AMD A6                  | 3        | 0.98%   |
| AMD Phenom II X2        | 2        | 0.65%   |
| AMD Athlon X4           | 2        | 0.65%   |
| AMD Athlon II X2        | 2        | 0.65%   |
| AMD Athlon 64 X2        | 2        | 0.65%   |
| AMD A8                  | 2        | 0.65%   |
| Intel Pentium Gold      | 1        | 0.33%   |
| Intel Pentium Dual-Core | 1        | 0.33%   |
| Intel Core 2 Extreme    | 1        | 0.33%   |
| Intel Celeron           | 1        | 0.33%   |
| Intel Atom              | 1        | 0.33%   |
| AMD Ryzen Embedded      | 1        | 0.33%   |
| AMD Ryzen 7 PRO         | 1        | 0.33%   |
| AMD Phenom II X6        | 1        | 0.33%   |
| AMD Athlon X2           | 1        | 0.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 103      | 33.55%  |
| 6      | 67       | 21.82%  |
| 8      | 49       | 15.96%  |
| 2      | 43       | 14.01%  |
| 16     | 14       | 4.56%   |
| 12     | 12       | 3.91%   |
| 10     | 7        | 2.28%   |
| 1      | 5        | 1.63%   |
| 24     | 3        | 0.98%   |
| 3      | 3        | 0.98%   |
| 32     | 1        | 0.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 304      | 99.02%  |
| 2      | 3        | 0.98%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 208      | 67.75%  |
| 1      | 99       | 32.25%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 307      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 28       | 9.06%   |
| Unknown    | 26       | 8.41%   |
| 0x08701021 | 25       | 8.09%   |
| 0x906ea    | 15       | 4.85%   |
| 0x306a9    | 15       | 4.85%   |
| 0x506e3    | 13       | 4.21%   |
| 0x0a201016 | 12       | 3.88%   |
| 0x0800820d | 10       | 3.24%   |
| 0x206a7    | 9        | 2.91%   |
| 0x906ed    | 8        | 2.59%   |
| 0x906e9    | 8        | 2.59%   |
| 0x90672    | 8        | 2.59%   |
| 0x0a201009 | 8        | 2.59%   |
| 0x1067a    | 7        | 2.27%   |
| 0x08001138 | 7        | 2.27%   |
| 0x06001119 | 6        | 1.94%   |
| 0x906ec    | 5        | 1.62%   |
| 0x0a50000c | 5        | 1.62%   |
| 0x08701013 | 5        | 1.62%   |
| 0x0800820b | 5        | 1.62%   |
| 0x08001137 | 5        | 1.62%   |
| 0x06003106 | 5        | 1.62%   |
| 0x08101016 | 4        | 1.29%   |
| 0x08008206 | 4        | 1.29%   |
| 0xa0671    | 3        | 0.97%   |
| 0x306f2    | 3        | 0.97%   |
| 0x106a5    | 3        | 0.97%   |
| 0x10676    | 3        | 0.97%   |
| 0x0810100b | 3        | 0.97%   |
| 0x010000b6 | 3        | 0.97%   |
| 0x00000000 | 3        | 0.97%   |
| 0xa0655    | 2        | 0.65%   |
| 0xa0653    | 2        | 0.65%   |
| 0x306e4    | 2        | 0.65%   |
| 0x206d7    | 2        | 0.65%   |
| 0x206c2    | 2        | 0.65%   |
| 0x08108109 | 2        | 0.65%   |
| 0x06000822 | 2        | 0.65%   |
| 0x906eb    | 1        | 0.32%   |
| 0x806e9    | 1        | 0.32%   |
| 0x6fb      | 1        | 0.32%   |
| 0x40671    | 1        | 0.32%   |
| 0x20655    | 1        | 0.32%   |
| 0x106e5    | 1        | 0.32%   |
| 0x106ca    | 1        | 0.32%   |
| 0x10677    | 1        | 0.32%   |
| 0x0a50000b | 1        | 0.32%   |
| 0x0a201204 | 1        | 0.32%   |
| 0x0a201006 | 1        | 0.32%   |
| 0x08600106 | 1        | 0.32%   |
| 0x08600104 | 1        | 0.32%   |
| 0x08600103 | 1        | 0.32%   |
| 0x0830104d | 1        | 0.32%   |
| 0x08301025 | 1        | 0.32%   |
| 0x08101013 | 1        | 0.32%   |
| 0x0800820c | 1        | 0.32%   |
| 0x07030105 | 1        | 0.32%   |
| 0x0700010b | 1        | 0.32%   |
| 0x07000106 | 1        | 0.32%   |
| 0x0600611a | 1        | 0.32%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| KabyLake         | 43       | 14.01%  |
| Zen 2            | 36       | 11.73%  |
| Zen 3            | 32       | 10.42%  |
| Haswell          | 32       | 10.42%  |
| Zen+             | 22       | 7.17%   |
| Zen              | 20       | 6.51%   |
| IvyBridge        | 19       | 6.19%   |
| Skylake          | 16       | 5.21%   |
| SandyBridge      | 15       | 4.89%   |
| Piledriver       | 11       | 3.58%   |
| Penryn           | 11       | 3.58%   |
| K10              | 8        | 2.61%   |
| Alderlake Hybrid | 8        | 2.61%   |
| Steamroller      | 6        | 1.95%   |
| Nehalem          | 4        | 1.3%    |
| CometLake        | 4        | 1.3%    |
| Westmere         | 3        | 0.98%   |
| Icelake          | 3        | 0.98%   |
| K8 Hammer        | 2        | 0.65%   |
| Jaguar           | 2        | 0.65%   |
| Bulldozer        | 2        | 0.65%   |
| Unknown          | 2        | 0.65%   |
| Puma             | 1        | 0.33%   |
| K10 Llano        | 1        | 0.33%   |
| Excavator        | 1        | 0.33%   |
| Core             | 1        | 0.33%   |
| Broadwell        | 1        | 0.33%   |
| Bonnell          | 1        | 0.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 125      | 37.65%  |
| AMD                        | 119      | 35.84%  |
| Intel                      | 86       | 25.9%   |
| Matrox Electronics Systems | 1        | 0.3%    |
| ASPEED Technology          | 1        | 0.3%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 29       | 8.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 13       | 3.83%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 13       | 3.83%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 13       | 3.83%   |
| Intel HD Graphics 530                                                       | 12       | 3.54%   |
| Nvidia GK208B [GeForce GT 710]                                              | 10       | 2.95%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 9        | 2.65%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 7        | 2.06%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 7        | 2.06%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 7        | 2.06%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 7        | 2.06%   |
| AMD Cezanne                                                                 | 7        | 2.06%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 6        | 1.77%   |
| Intel AlderLake-S GT1                                                       | 6        | 1.77%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 6        | 1.77%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 6        | 1.77%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 6        | 1.77%   |
| Intel HD Graphics 630                                                       | 5        | 1.47%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 4        | 1.18%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 4        | 1.18%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 4        | 1.18%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 4        | 1.18%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 4        | 1.18%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 4        | 1.18%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 3        | 0.88%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 3        | 0.88%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 3        | 0.88%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 3        | 0.88%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3        | 0.88%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 3        | 0.88%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 3        | 0.88%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 0.59%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 2        | 0.59%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 0.59%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 2        | 0.59%   |
| Nvidia GP107GL [Quadro P1000]                                               | 2        | 0.59%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2        | 0.59%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 0.59%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 0.59%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 0.59%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 2        | 0.59%   |
| Nvidia GF108 [GeForce GT 630]                                               | 2        | 0.59%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 2        | 0.59%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 2        | 0.59%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 2        | 0.59%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                              | 2        | 0.59%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 2        | 0.59%   |
| Nvidia G92 [GeForce 9800 GT]                                                | 2        | 0.59%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller              | 2        | 0.59%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 2        | 0.59%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 2        | 0.59%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 0.59%   |
| AMD Tobago PRO [Radeon R7 360 / R9 360 OEM]                                 | 2        | 0.59%   |
| AMD Renoir                                                                  | 2        | 0.59%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2        | 0.59%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2        | 0.59%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 0.59%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 2        | 0.59%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                          | 2        | 0.59%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 0.29%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 115      | 37.46%  |
| 1 x AMD         | 112      | 36.48%  |
| 1 x Intel       | 62       | 20.2%   |
| Intel + Nvidia  | 7        | 2.28%   |
| 2 x AMD         | 5        | 1.63%   |
| Other           | 1        | 0.33%   |
| 2 x Nvidia      | 1        | 0.33%   |
| Nvidia + Matrox | 1        | 0.33%   |
| Intel + 2 x AMD | 1        | 0.33%   |
| 1 x ASPEED      | 1        | 0.33%   |
| AMD + Nvidia    | 1        | 0.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 225      | 73.05%  |
| Proprietary | 76       | 24.68%  |
| Unknown     | 7        | 2.27%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 122      | 39.23%  |
| 7.01-8.0   | 44       | 14.15%  |
| 1.01-2.0   | 40       | 12.86%  |
| 3.01-4.0   | 29       | 9.32%   |
| 0.51-1.0   | 25       | 8.04%   |
| 0.01-0.5   | 20       | 6.43%   |
| 8.01-16.0  | 15       | 4.82%   |
| 5.01-6.0   | 14       | 4.5%    |
| 2.01-3.0   | 2        | 0.64%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 56       | 15.86%  |
| Goldstar             | 45       | 12.75%  |
| Dell                 | 39       | 11.05%  |
| AOC                  | 24       | 6.8%    |
| Acer                 | 24       | 6.8%    |
| Hewlett-Packard      | 23       | 6.52%   |
| Ancor Communications | 16       | 4.53%   |
| ViewSonic            | 15       | 4.25%   |
| Philips              | 14       | 3.97%   |
| BenQ                 | 14       | 3.97%   |
| Lenovo               | 10       | 2.83%   |
| Iiyama               | 8        | 2.27%   |
| ASUSTek Computer     | 8        | 2.27%   |
| Eizo                 | 6        | 1.7%    |
| HannStar             | 5        | 1.42%   |
| Vizio                | 3        | 0.85%   |
| Unknown              | 3        | 0.85%   |
| Panasonic            | 3        | 0.85%   |
| MSI                  | 3        | 0.85%   |
| Fujitsu Siemens      | 3        | 0.85%   |
| ___                  | 2        | 0.57%   |
| Sony                 | 2        | 0.57%   |
| Mi                   | 2        | 0.57%   |
| Gigabyte Technology  | 2        | 0.57%   |
| YUK                  | 1        | 0.28%   |
| Westinghouse         | 1        | 0.28%   |
| Valve                | 1        | 0.28%   |
| Unknown (XXX)        | 1        | 0.28%   |
| Toshiba              | 1        | 0.28%   |
| TCL                  | 1        | 0.28%   |
| SHX                  | 1        | 0.28%   |
| Sceptre Tech         | 1        | 0.28%   |
| PRISM+               | 1        | 0.28%   |
| Plain Tree Systems   | 1        | 0.28%   |
| Pixio                | 1        | 0.28%   |
| Packard Bell         | 1        | 0.28%   |
| ONN                  | 1        | 0.28%   |
| NEC Computers        | 1        | 0.28%   |
| LG Electronics       | 1        | 0.28%   |
| Insignia             | 1        | 0.28%   |
| Haier                | 1        | 0.28%   |
| Denver               | 1        | 0.28%   |
| Daewoo               | 1        | 0.28%   |
| CHE                  | 1        | 0.28%   |
| Belinea              | 1        | 0.28%   |
| Arnos Instruments    | 1        | 0.28%   |
| Apple                | 1        | 0.28%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                              | Desktops | Percent |
|--------------------------------------------------------------------|----------|---------|
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch          | 5        | 1.33%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch              | 5        | 1.33%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch  | 3        | 0.8%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch  | 3        | 0.8%    |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                  | 3        | 0.8%    |
| Samsung Electronics S22C350 SAM0A32 1920x1080 477x268mm 21.5-inch  | 2        | 0.53%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch  | 2        | 0.53%   |
| Samsung Electronics C49HG9x SAM0E5D 3840x1080 1196x336mm 48.9-inch | 2        | 0.53%   |
| Samsung Electronics C32F391 SAM0D35 1920x1080 698x393mm 31.5-inch  | 2        | 0.53%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                   | 2        | 0.53%   |
| Iiyama PL2282H IVM5632 1920x1080 476x268mm 21.5-inch               | 2        | 0.53%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch          | 2        | 0.53%   |
| Goldstar ULTRAWIDE GSM76E4 3440x1440 800x335mm 34.1-inch           | 2        | 0.53%   |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch              | 2        | 0.53%   |
| Dell U2515H DELD06F 2560x1440 553x311mm 25.0-inch                  | 2        | 0.53%   |
| Dell U2417H DEL40E8 1920x1080 527x296mm 23.8-inch                  | 2        | 0.53%   |
| Dell P2415Q DELA0BE 3840x2160 527x296mm 23.8-inch                  | 2        | 0.53%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 531x299mm 24.0-inch       | 2        | 0.53%   |
| AOC U34G2G1 AOC3402 3440x1440 797x334mm 34.0-inch                  | 2        | 0.53%   |
| AOC 24B1W AOC2401 1920x1080 521x293mm 23.5-inch                    | 2        | 0.53%   |
| AOC 22B2WG5 AOC2202 1920x1080 477x268mm 21.5-inch                  | 2        | 0.53%   |
| AOC 22B1WG5 AOC2201 1920x1080 479x260mm 21.5-inch                  | 2        | 0.53%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch   | 2        | 0.53%   |
| Acer VG240Y ACR0673 1920x1080 527x296mm 23.8-inch                  | 2        | 0.53%   |
| ___ LCDTV16 ___9000 1360x768                                       | 1        | 0.27%   |
| ___ LCDTV16 ___0101 1360x768                                       | 1        | 0.27%   |
| YUK NexDock YUKBC34 1920x1080 293x165mm 13.2-inch                  | 1        | 0.27%   |
| Westinghouse EU24H1G1 WDT1D42 1366x768 1150x650mm 52.0-inch        | 1        | 0.27%   |
| Vizio E60-E3 VIZ1018 3840x2160 1330x748mm 60.1-inch                | 1        | 0.27%   |
| Vizio E390-A1 VIZ0098 1920x1080 853x480mm 38.5-inch                | 1        | 0.27%   |
| Vizio D32x-D1 VIZ1005 1920x1080 698x392mm 31.5-inch                | 1        | 0.27%   |
| ViewSonic XG2401 SERIES VSCBB31 1920x1080 531x299mm 24.0-inch      | 1        | 0.27%   |
| ViewSonic VX3258 SERIES VSCDE35 2560x1440 697x392mm 31.5-inch      | 1        | 0.27%   |
| ViewSonic VX2739wm VSC3F24 1920x1080 598x336mm 27.0-inch           | 1        | 0.27%   |
| ViewSonic VX2336 SERIES VSC402A 1920x1080 510x290mm 23.1-inch      | 1        | 0.27%   |
| ViewSonic VX2276 Series VSC2F32 1920x1080 476x268mm 21.5-inch      | 1        | 0.27%   |
| ViewSonic VX2268wm VSC0E23 1680x1050 474x296mm 22.0-inch           | 1        | 0.27%   |
| ViewSonic VX2260WM VSCFC21 1920x1080 477x268mm 21.5-inch           | 1        | 0.27%   |
| ViewSonic VX2250 SERIES VSCCB25 1920x1080 477x268mm 21.5-inch      | 1        | 0.27%   |
| ViewSonic VX2025wm VSCE51D 1680x1050 433x271mm 20.1-inch           | 1        | 0.27%   |
| ViewSonic VP2250wb VSC5320 1920x1080 465x291mm 21.6-inch           | 1        | 0.27%   |
| ViewSonic VA2419 Series VSC7B32 1920x1080 527x296mm 23.8-inch      | 1        | 0.27%   |
| ViewSonic VA1938 Series VSC0626 1366x768 410x230mm 18.5-inch       | 1        | 0.27%   |
| ViewSonic VA1926wSERIES VSC5920 1440x900 410x256mm 19.0-inch       | 1        | 0.27%   |
| ViewSonic NX1932w VSC6020 1440x900 410x230mm 18.5-inch             | 1        | 0.27%   |
| ViewSonic LCD Monitor VA2226w-3 1680x1050                          | 1        | 0.27%   |
| Valve Index HMD VLV91A8                                            | 1        | 0.27%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                 | 1        | 0.27%   |
| Unknown LCDTV16 0101 1920x1080 1600x900mm 72.3-inch                | 1        | 0.27%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                              | 1        | 0.27%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch     | 1        | 0.27%   |
| Toshiba TV TSB0212 1920x1080                                       | 1        | 0.27%   |
| TCL SMART TV TCL6586 3840x2160 1209x680mm 54.6-inch                | 1        | 0.27%   |
| Sony TV SNY4502 1920x1080 1600x900mm 72.3-inch                     | 1        | 0.27%   |
| Sony TV *00 SNY7C04 3840x2160 952x535mm 43.0-inch                  | 1        | 0.27%   |
| SHX SHX SHX0030 1920x1080 708x398mm 32.0-inch                      | 1        | 0.27%   |
| Sceptre Tech E24 SPT099D 1920x1080 409x230mm 18.5-inch             | 1        | 0.27%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 700x390mm 31.5-inch  | 1        | 0.27%   |
| Samsung Electronics U32H75x SAM0E02 3840x2160 697x392mm 31.5-inch  | 1        | 0.27%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch  | 1        | 0.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 159      | 46.36%  |
| 2560x1440 (QHD)    | 45       | 13.12%  |
| 3840x2160 (4K)     | 42       | 12.24%  |
| 1280x1024 (SXGA)   | 15       | 4.37%   |
| 1680x1050 (WSXGA+) | 13       | 3.79%   |
| 1920x1200 (WUXGA)  | 11       | 3.21%   |
| 3440x1440          | 10       | 2.92%   |
| 1440x900 (WXGA+)   | 10       | 2.92%   |
| 1600x900 (HD+)     | 8        | 2.33%   |
| 1366x768 (WXGA)    | 8        | 2.33%   |
| 2560x1080          | 5        | 1.46%   |
| 3840x1080          | 3        | 0.87%   |
| 1360x768           | 3        | 0.87%   |
| 2560x1600          | 2        | 0.58%   |
| Unknown            | 2        | 0.58%   |
| 4480x1080          | 1        | 0.29%   |
| 3840x1600          | 1        | 0.29%   |
| 1920x540           | 1        | 0.29%   |
| 1600x1200          | 1        | 0.29%   |
| 1280x960           | 1        | 0.29%   |
| 1280x720 (HD)      | 1        | 0.29%   |
| 1024x768 (XGA)     | 1        | 0.29%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 72       | 20.06%  |
| 24      | 64       | 17.83%  |
| 21      | 53       | 14.76%  |
| 23      | 34       | 9.47%   |
| 31      | 23       | 6.41%   |
| 34      | 15       | 4.18%   |
| 19      | 14       | 3.9%    |
| 22      | 11       | 3.06%   |
| 20      | 9        | 2.51%   |
| 18      | 9        | 2.51%   |
| 17      | 9        | 2.51%   |
| 25      | 5        | 1.39%   |
| Unknown | 5        | 1.39%   |
| 72      | 4        | 1.11%   |
| 42      | 4        | 1.11%   |
| 84      | 3        | 0.84%   |
| 54      | 3        | 0.84%   |
| 32      | 3        | 0.84%   |
| 49      | 2        | 0.56%   |
| 48      | 2        | 0.56%   |
| 47      | 2        | 0.56%   |
| 15      | 2        | 0.56%   |
| 74      | 1        | 0.28%   |
| 65      | 1        | 0.28%   |
| 52      | 1        | 0.28%   |
| 37      | 1        | 0.28%   |
| 35      | 1        | 0.28%   |
| 30      | 1        | 0.28%   |
| 29      | 1        | 0.28%   |
| 28      | 1        | 0.28%   |
| 26      | 1        | 0.28%   |
| 16      | 1        | 0.28%   |
| 13      | 1        | 0.28%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 159      | 45.82%  |
| 401-500     | 86       | 24.78%  |
| 601-700     | 31       | 8.93%   |
| 701-800     | 18       | 5.19%   |
| 351-400     | 12       | 3.46%   |
| 1001-1500   | 11       | 3.17%   |
| 301-350     | 10       | 2.88%   |
| 1501-2000   | 8        | 2.31%   |
| Unknown     | 5        | 1.44%   |
| 901-1000    | 4        | 1.15%   |
| 801-900     | 2        | 0.58%   |
| 201-300     | 1        | 0.29%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 233      | 73.73%  |
| 16/10   | 39       | 12.34%  |
| 5/4     | 16       | 5.06%   |
| 21/9    | 16       | 5.06%   |
| Unknown | 4        | 1.27%   |
| 4/3     | 3        | 0.95%   |
| 32/9    | 3        | 0.95%   |
| 6/5     | 2        | 0.63%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 119      | 33.71%  |
| 301-350        | 72       | 20.4%   |
| 351-500        | 44       | 12.46%  |
| 151-200        | 43       | 12.18%  |
| 251-300        | 24       | 6.8%    |
| 141-150        | 16       | 4.53%   |
| More than 1000 | 14       | 3.97%   |
| 501-1000       | 11       | 3.12%   |
| Unknown        | 5        | 1.42%   |
| 101-110        | 2        | 0.57%   |
| 71-80          | 1        | 0.28%   |
| 131-140        | 1        | 0.28%   |
| 121-130        | 1        | 0.28%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 192      | 58.01%  |
| 101-120 | 95       | 28.7%   |
| 121-160 | 17       | 5.14%   |
| 161-240 | 13       | 3.93%   |
| 1-50    | 9        | 2.72%   |
| Unknown | 5        | 1.51%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 214      | 69.26%  |
| 2     | 75       | 24.27%  |
| 0     | 13       | 4.21%   |
| 3     | 6        | 1.94%   |
| 4     | 1        | 0.32%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 183      | 42.07%  |
| Intel                           | 157      | 36.09%  |
| Qualcomm Atheros                | 21       | 4.83%   |
| TP-Link                         | 14       | 3.22%   |
| Ralink Technology               | 12       | 2.76%   |
| Broadcom                        | 8        | 1.84%   |
| Aquantia                        | 6        | 1.38%   |
| Nvidia                          | 4        | 0.92%   |
| NetGear                         | 3        | 0.69%   |
| Google                          | 3        | 0.69%   |
| Wilocity                        | 2        | 0.46%   |
| Microsoft                       | 2        | 0.46%   |
| Marvell Technology Group        | 2        | 0.46%   |
| Edimax Technology               | 2        | 0.46%   |
| Belkin Components               | 2        | 0.46%   |
| ASUSTek Computer                | 2        | 0.46%   |
| Xiaomi                          | 1        | 0.23%   |
| Winbond Electronics             | 1        | 0.23%   |
| Samsung Electronics             | 1        | 0.23%   |
| Qualcomm Atheros Communications | 1        | 0.23%   |
| Mellanox Technologies           | 1        | 0.23%   |
| Linksys                         | 1        | 0.23%   |
| ICS Advent                      | 1        | 0.23%   |
| Huawei Technologies             | 1        | 0.23%   |
| HMD Global                      | 1        | 0.23%   |
| D-Link                          | 1        | 0.23%   |
| AVM                             | 1        | 0.23%   |
| Apple                           | 1        | 0.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 144      | 28.46%  |
| Intel Wi-Fi 6 AX200                                               | 38       | 7.51%   |
| Intel I211 Gigabit Network Connection                             | 31       | 6.13%   |
| Realtek RTL8125 2.5GbE Controller                                 | 24       | 4.74%   |
| Intel Ethernet Connection (7) I219-V                              | 15       | 2.96%   |
| Intel Ethernet Connection (2) I219-V                              | 15       | 2.96%   |
| Intel Ethernet Controller I225-V                                  | 12       | 2.37%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10       | 1.98%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 9        | 1.78%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 8        | 1.58%   |
| TP-Link TL WN823N RTL8192EU                                       | 6        | 1.19%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6        | 1.19%   |
| Intel Ethernet Connection I217-LM                                 | 6        | 1.19%   |
| Intel Wireless-AC 9260                                            | 5        | 0.99%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 5        | 0.99%   |
| Intel 82579V Gigabit Network Connection                           | 5        | 0.99%   |
| Intel 82574L Gigabit Network Connection                           | 5        | 0.99%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 4        | 0.79%   |
| Ralink RT5370 Wireless Adapter                                    | 4        | 0.79%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4        | 0.79%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4        | 0.79%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 0.79%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 3        | 0.59%   |
| TP-Link 802.11ac NIC                                              | 3        | 0.59%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3        | 0.59%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3        | 0.59%   |
| Realtek 802.11ac NIC                                              | 3        | 0.59%   |
| Ralink RT5372 Wireless Adapter                                    | 3        | 0.59%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3        | 0.59%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3        | 0.59%   |
| Intel Wireless 8260                                               | 3        | 0.59%   |
| Intel Ethernet Connection (2) I219-LM                             | 3        | 0.59%   |
| Intel Ethernet Connection (2) I218-V                              | 3        | 0.59%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 3        | 0.59%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 3        | 0.59%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                | 2        | 0.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2        | 0.4%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 0.4%    |
| Ralink MT7601U Wireless Adapter                                   | 2        | 0.4%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 2        | 0.4%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2        | 0.4%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 0.4%    |
| Nvidia MCP55 Ethernet                                             | 2        | 0.4%    |
| Microsoft XBOX ACC                                                | 2        | 0.4%    |
| Intel I350 Gigabit Network Connection                             | 2        | 0.4%    |
| Intel Ethernet Connection I217-V                                  | 2        | 0.4%    |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 0.4%    |
| Intel Ethernet Connection (14) I219-LM                            | 2        | 0.4%    |
| Intel Centrino Wireless-N 2230                                    | 2        | 0.4%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)        | 2        | 0.4%    |
| Google Nexus/Pixel Device (tether+ debug)                         | 2        | 0.4%    |
| Broadcom BCM43228 802.11a/b/g/n                                   | 2        | 0.4%    |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2        | 0.4%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.2%    |
| Winbond Virtual Com Port                                          | 1        | 0.2%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 1        | 0.2%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1        | 0.2%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.2%    |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1        | 0.2%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1        | 0.2%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 82       | 50.93%  |
| Realtek Semiconductor           | 20       | 12.42%  |
| TP-Link                         | 14       | 8.7%    |
| Ralink Technology               | 12       | 7.45%   |
| Qualcomm Atheros                | 11       | 6.83%   |
| Broadcom                        | 6        | 3.73%   |
| NetGear                         | 3        | 1.86%   |
| Wilocity                        | 2        | 1.24%   |
| Microsoft                       | 2        | 1.24%   |
| Edimax Technology               | 2        | 1.24%   |
| Belkin Components               | 2        | 1.24%   |
| Qualcomm Atheros Communications | 1        | 0.62%   |
| Linksys                         | 1        | 0.62%   |
| D-Link                          | 1        | 0.62%   |
| AVM                             | 1        | 0.62%   |
| ASUSTek Computer                | 1        | 0.62%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                     | 38       | 23.31%  |
| Intel Cannon Lake PCH CNVi WiFi                                                         | 9        | 5.52%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                        | 8        | 4.91%   |
| TP-Link TL WN823N RTL8192EU                                                             | 6        | 3.68%   |
| Intel Wireless-AC 9260                                                                  | 5        | 3.07%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                        | 5        | 3.07%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                         | 4        | 2.45%   |
| Ralink RT5370 Wireless Adapter                                                          | 4        | 2.45%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                              | 4        | 2.45%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                  | 4        | 2.45%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                            | 3        | 1.84%   |
| TP-Link 802.11ac NIC                                                                    | 3        | 1.84%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                         | 3        | 1.84%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                     | 3        | 1.84%   |
| Realtek 802.11ac NIC                                                                    | 3        | 1.84%   |
| Ralink RT5372 Wireless Adapter                                                          | 3        | 1.84%   |
| Intel Wireless 8260                                                                     | 3        | 1.84%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                      | 3        | 1.84%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                                      | 2        | 1.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                | 2        | 1.23%   |
| Ralink MT7601U Wireless Adapter                                                         | 2        | 1.23%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                        | 2        | 1.23%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                          | 2        | 1.23%   |
| Microsoft XBOX ACC                                                                      | 2        | 1.23%   |
| Intel Centrino Wireless-N 2230                                                          | 2        | 1.23%   |
| Broadcom BCM43228 802.11a/b/g/n                                                         | 2        | 1.23%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                     | 1        | 0.61%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                              | 1        | 0.61%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                      | 1        | 0.61%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                | 1        | 0.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                         | 1        | 0.61%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                              | 1        | 0.61%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                  | 1        | 0.61%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                                  | 1        | 0.61%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                   | 1        | 0.61%   |
| Ralink RT2501/RT2573 Wireless Adapter                                                   | 1        | 0.61%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                       | 1        | 0.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                              | 1        | 0.61%   |
| Qualcomm Atheros AR5523                                                                 | 1        | 0.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                        | 1        | 0.61%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                        | 1        | 0.61%   |
| NetGear WNDA3100v1 802.11abgn [Atheros AR9170+AR9104]                                   | 1        | 0.61%   |
| NetGear WN111(v2) RangeMax Next Wireless [Atheros AR9170+AR9101]                        | 1        | 0.61%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU]               | 1        | 0.61%   |
| Linksys WUSB6300 802.11a/b/g/n/ac Wireless Adapter [Realtek RTL8812AU]                  | 1        | 0.61%   |
| Intel Wireless 8265 / 8275                                                              | 1        | 0.61%   |
| Intel Wireless 7260                                                                     | 1        | 0.61%   |
| Intel Wireless 3165                                                                     | 1        | 0.61%   |
| Intel Tiger Lake PCH CNVi WiFi                                                          | 1        | 0.61%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                         | 1        | 0.61%   |
| Intel Comet Lake PCH CNVi WiFi                                                          | 1        | 0.61%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                           | 1        | 0.61%   |
| Intel Centrino Ultimate-N 6300                                                          | 1        | 0.61%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                          | 1        | 0.61%   |
| Edimax EW-7612UAn V2 802.11n Wireless Adapter [Realtek RTL8192CU]                       | 1        | 0.61%   |
| D-Link 11ac adapter                                                                     | 1        | 0.61%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                      | 1        | 0.61%   |
| Broadcom BCM43225 802.11b/g/n                                                           | 1        | 0.61%   |
| Belkin Components F7D2102 802.11n N300 Micro Wireless Adapter v3000 [Realtek RTL8192CU] | 1        | 0.61%   |
| Belkin Components F5D8053 N Wireless USB Adapter v3000 [Ralink RT2870]                  | 1        | 0.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 173      | 53.07%  |
| Intel                    | 119      | 36.5%   |
| Qualcomm Atheros         | 11       | 3.37%   |
| Aquantia                 | 6        | 1.84%   |
| Nvidia                   | 4        | 1.23%   |
| Marvell Technology Group | 2        | 0.61%   |
| Broadcom                 | 2        | 0.61%   |
| Xiaomi                   | 1        | 0.31%   |
| Samsung Electronics      | 1        | 0.31%   |
| Mellanox Technologies    | 1        | 0.31%   |
| ICS Advent               | 1        | 0.31%   |
| Huawei Technologies      | 1        | 0.31%   |
| HMD Global               | 1        | 0.31%   |
| Google                   | 1        | 0.31%   |
| ASUSTek Computer         | 1        | 0.31%   |
| Apple                    | 1        | 0.31%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 144      | 42.48%  |
| Intel I211 Gigabit Network Connection                                         | 31       | 9.14%   |
| Realtek RTL8125 2.5GbE Controller                                             | 24       | 7.08%   |
| Intel Ethernet Connection (7) I219-V                                          | 15       | 4.42%   |
| Intel Ethernet Connection (2) I219-V                                          | 15       | 4.42%   |
| Intel Ethernet Controller I225-V                                              | 12       | 3.54%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 10       | 2.95%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 6        | 1.77%   |
| Intel Ethernet Connection I217-LM                                             | 6        | 1.77%   |
| Intel 82579V Gigabit Network Connection                                       | 5        | 1.47%   |
| Intel 82574L Gigabit Network Connection                                       | 5        | 1.47%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 4        | 1.18%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 3        | 0.88%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 3        | 0.88%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3        | 0.88%   |
| Intel Ethernet Connection (2) I218-V                                          | 3        | 0.88%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 3        | 0.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2        | 0.59%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 2        | 0.59%   |
| Nvidia MCP55 Ethernet                                                         | 2        | 0.59%   |
| Intel I350 Gigabit Network Connection                                         | 2        | 0.59%   |
| Intel Ethernet Connection I217-V                                              | 2        | 0.59%   |
| Intel Ethernet Connection (7) I219-LM                                         | 2        | 0.59%   |
| Intel Ethernet Connection (14) I219-LM                                        | 2        | 0.59%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 2        | 0.59%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 2        | 0.59%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 1        | 0.29%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 1        | 0.29%   |
| Realtek USB 10/100/1G/2.5G LAN                                                | 1        | 0.29%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.29%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 0.29%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 1        | 0.29%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1        | 0.29%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1        | 0.29%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1        | 0.29%   |
| Nvidia MCP61 Ethernet                                                         | 1        | 0.29%   |
| Nvidia MCP51 Ethernet Controller                                              | 1        | 0.29%   |
| Mellanox MT27500 Family [ConnectX-3]                                          | 1        | 0.29%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1        | 0.29%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                       | 1        | 0.29%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                             | 1        | 0.29%   |
| Intel Ethernet Controller 10G X550T                                           | 1        | 0.29%   |
| Intel 82578DM Gigabit Network Connection                                      | 1        | 0.29%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 1        | 0.29%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 0.29%   |
| Intel 82562V-2 10/100 Network Connection                                      | 1        | 0.29%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                       | 1        | 0.29%   |
| Huawei E353/E3131                                                             | 1        | 0.29%   |
| HMD Global SDM439-QRD _SN:13A316C0                                            | 1        | 0.29%   |
| Google Nexus/Pixel Device (tether)                                            | 1        | 0.29%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 1        | 0.29%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                              | 1        | 0.29%   |
| ASUS USB 10/100/1G/2.5G LAN                                                   | 1        | 0.29%   |
| Aquantia Ethernet controller                                                  | 1        | 0.29%   |
| Apple iPad 4/Mini1                                                            | 1        | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 305      | 67.18%  |
| WiFi     | 145      | 31.94%  |
| Modem    | 3        | 0.66%   |
| Unknown  | 1        | 0.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 283      | 72.19%  |
| WiFi     | 109      | 27.81%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 182      | 58.9%   |
| 2     | 101      | 32.69%  |
| 3     | 19       | 6.15%   |
| 4     | 3        | 0.97%   |
| 0     | 2        | 0.65%   |
| 6     | 1        | 0.32%   |
| 5     | 1        | 0.32%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 221      | 71.75%  |
| Yes  | 87       | 28.25%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 78       | 55.32%  |
| Cambridge Silicon Radio         | 30       | 21.28%  |
| ASUSTek Computer                | 12       | 8.51%   |
| Broadcom                        | 6        | 4.26%   |
| Realtek Semiconductor           | 5        | 3.55%   |
| Qualcomm Atheros Communications | 3        | 2.13%   |
| Apple                           | 3        | 2.13%   |
| TP-Link                         | 2        | 1.42%   |
| Lite-On Technology              | 1        | 0.71%   |
| Belkin Components               | 1        | 0.71%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 37       | 26.24%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 30       | 21.28%  |
| Intel Bluetooth Device                              | 18       | 12.77%  |
| Intel Wireless-AC 3168 Bluetooth                    | 8        | 5.67%   |
| Realtek Bluetooth Radio                             | 5        | 3.55%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 5        | 3.55%   |
| Intel AX201 Bluetooth                               | 5        | 3.55%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 4        | 2.84%   |
| ASUS Bluetooth Radio                                | 4        | 2.84%   |
| Intel Bluetooth wireless interface                  | 3        | 2.13%   |
| TP-Link UB500 Adapter                               | 2        | 1.42%   |
| Qualcomm Atheros  Bluetooth Device                  | 2        | 1.42%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2        | 1.42%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2        | 1.42%   |
| ASUS Bluetooth Device                               | 2        | 1.42%   |
| ASUS ASUS USB-BT500                                 | 2        | 1.42%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2        | 1.42%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1        | 0.71%   |
| Lite-On Bluetooth Device                            | 1        | 0.71%   |
| Broadcom HP Portable Bumble Bee                     | 1        | 0.71%   |
| Broadcom BCM2045 Bluetooth                          | 1        | 0.71%   |
| Belkin Components F8T012 Bluetooth Adapter          | 1        | 0.71%   |
| ASUS Qualcomm Bluetooth 4.1                         | 1        | 0.71%   |
| ASUS BCM20702A0                                     | 1        | 0.71%   |
| Apple Bluetooth USB Host Controller                 | 1        | 0.71%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| AMD                         | 167      | 28.99%  |
| Intel                       | 156      | 27.08%  |
| Nvidia                      | 120      | 20.83%  |
| C-Media Electronics         | 13       | 2.26%   |
| Creative Labs               | 9        | 1.56%   |
| Razer USA                   | 6        | 1.04%   |
| JMTek                       | 6        | 1.04%   |
| Texas Instruments           | 5        | 0.87%   |
| Plantronics                 | 5        | 0.87%   |
| Kingston Technology         | 5        | 0.87%   |
| GN Netcom                   | 5        | 0.87%   |
| Focusrite-Novation          | 5        | 0.87%   |
| Corsair                     | 5        | 0.87%   |
| Logitech                    | 4        | 0.69%   |
| Blue Microphones            | 4        | 0.69%   |
| SteelSeries ApS             | 3        | 0.52%   |
| Creative Technology         | 3        | 0.52%   |
| Unknown                     | 2        | 0.35%   |
| Tenx Technology             | 2        | 0.35%   |
| Sennheiser Communications   | 2        | 0.35%   |
| SAVITECH                    | 2        | 0.35%   |
| RODE Microphones            | 2        | 0.35%   |
| GYROCOM C&C                 | 2        | 0.35%   |
| Giga-Byte Technology        | 2        | 0.35%   |
| Generalplus Technology      | 2        | 0.35%   |
| Audio-Technica              | 2        | 0.35%   |
| ASUSTek Computer            | 2        | 0.35%   |
| Apple                       | 2        | 0.35%   |
| Apogee Electronics          | 2        | 0.35%   |
| Unknown                     | 2        | 0.35%   |
| Yamaha                      | 1        | 0.17%   |
| Valve Software              | 1        | 0.17%   |
| ULi Electronics             | 1        | 0.17%   |
| Thermaltake                 | 1        | 0.17%   |
| Sony                        | 1        | 0.17%   |
| Samson Technologies         | 1        | 0.17%   |
| Roland                      | 1        | 0.17%   |
| RME                         | 1        | 0.17%   |
| Quanta                      | 1        | 0.17%   |
| OLKB                        | 1        | 0.17%   |
| Native Instruments          | 1        | 0.17%   |
| Microsoft                   | 1        | 0.17%   |
| Microdia                    | 1        | 0.17%   |
| Mark of the Unicorn         | 1        | 0.17%   |
| Lenovo                      | 1        | 0.17%   |
| Huawei Technologies         | 1        | 0.17%   |
| HiFimeDIY Audio             | 1        | 0.17%   |
| Goldvish                    | 1        | 0.17%   |
| FiiO Electronics Technology | 1        | 0.17%   |
| Elite Silicon               | 1        | 0.17%   |
| DigiTech                    | 1        | 0.17%   |
| Digidesign                  | 1        | 0.17%   |
| Dell                        | 1        | 0.17%   |
| Cooler Master               | 1        | 0.17%   |
| Cambridge Silicon Radio     | 1        | 0.17%   |
| Best Buy                    | 1        | 0.17%   |
| Barco Display Systems       | 1        | 0.17%   |
| Arturia                     | 1        | 0.17%   |
| AKAI Professional M.I.      | 1        | 0.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 56       | 8.2%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 31       | 4.54%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 29       | 4.25%   |
| Intel Cannon Lake PCH cAVS                                                 | 25       | 3.66%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 21       | 3.07%   |
| AMD Family 17h/19h HD Audio Controller                                     | 19       | 2.78%   |
| Intel 200 Series PCH HD Audio                                              | 17       | 2.49%   |
| AMD Navi 21 HDMI Audio [Radeon RX 6800/6800 XT / 6900 XT]                  | 16       | 2.34%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 15       | 2.2%    |
| AMD Navi 10 HDMI Audio                                                     | 15       | 2.2%    |
| AMD FCH Azalia Controller                                                  | 15       | 2.2%    |
| Nvidia GP107GL High Definition Audio Controller                            | 14       | 2.05%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 14       | 2.05%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 14       | 2.05%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 14       | 2.05%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 13       | 1.9%    |
| Nvidia GP106 High Definition Audio Controller                              | 12       | 1.76%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 12       | 1.76%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 9        | 1.32%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 9        | 1.32%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 9        | 1.32%   |
| Nvidia TU106 High Definition Audio Controller                              | 8        | 1.17%   |
| Intel Alder Lake-S HD Audio Controller                                     | 8        | 1.17%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 8        | 1.17%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8        | 1.17%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 8        | 1.17%   |
| Nvidia TU104 HD Audio Controller                                           | 7        | 1.02%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 7        | 1.02%   |
| Nvidia TU116 High Definition Audio Controller                              | 6        | 0.88%   |
| Nvidia GK104 HDMI Audio Controller                                         | 5        | 0.73%   |
| Nvidia GA102 High Definition Audio Controller                              | 5        | 0.73%   |
| Nvidia GP108 High Definition Audio Controller                              | 4        | 0.59%   |
| Nvidia GP104 High Definition Audio Controller                              | 4        | 0.59%   |
| Nvidia GP102 HDMI Audio Controller                                         | 4        | 0.59%   |
| JMTek USB PnP Audio Device                                                 | 4        | 0.59%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4        | 0.59%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4        | 0.59%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 4        | 0.59%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 4        | 0.59%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 4        | 0.59%   |
| AMD Trinity HDMI Audio Controller                                          | 4        | 0.59%   |
| Texas Instruments PCM2902 Audio Codec                                      | 3        | 0.44%   |
| Nvidia High Definition Audio Controller                                    | 3        | 0.44%   |
| Nvidia GM206 High Definition Audio Controller                              | 3        | 0.44%   |
| Nvidia GM204 High Definition Audio Controller                              | 3        | 0.44%   |
| Nvidia GF108 High Definition Audio Controller                              | 3        | 0.44%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 3        | 0.44%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 3        | 0.44%   |
| C-Media Electronics SADES Hammer                                           | 3        | 0.44%   |
| Blue Microphones Yeti Stereo Microphone                                    | 3        | 0.44%   |
| AMD Kabini HDMI/DP Audio                                                   | 3        | 0.44%   |
| Tenx Technology USB AUDIO                                                  | 2        | 0.29%   |
| Razer USA Razer Seiren Mini                                                | 2        | 0.29%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2        | 0.29%   |
| Nvidia TU102 High Definition Audio Controller                              | 2        | 0.29%   |
| Nvidia MCP55 High Definition Audio                                         | 2        | 0.29%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2        | 0.29%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2        | 0.29%   |
| Nvidia GA104 High Definition Audio Controller                              | 2        | 0.29%   |
| Nvidia Audio device                                                        | 2        | 0.29%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 38       | 22.22%  |
| Corsair             | 34       | 19.88%  |
| Unknown             | 21       | 12.28%  |
| Crucial             | 21       | 12.28%  |
| G.Skill             | 15       | 8.77%   |
| SK Hynix            | 11       | 6.43%   |
| Samsung Electronics | 9        | 5.26%   |
| Team                | 4        | 2.34%   |
| Micron Technology   | 4        | 2.34%   |
| A-DATA Technology   | 3        | 1.75%   |
| Patriot             | 2        | 1.17%   |
| GOODRAM             | 2        | 1.17%   |
| V-GeN               | 1        | 0.58%   |
| Timetec             | 1        | 0.58%   |
| Ramaxel Technology  | 1        | 0.58%   |
| PLEXHD              | 1        | 0.58%   |
| OCZ                 | 1        | 0.58%   |
| Apacer              | 1        | 0.58%   |
| Unknown             | 1        | 0.58%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3533MT/s     | 3        | 1.63%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3200MT/s        | 3        | 1.63%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s      | 3        | 1.63%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s   | 3        | 1.63%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s | 3        | 1.63%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s    | 3        | 1.63%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                     | 2        | 1.09%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                | 2        | 1.09%   |
| Unknown RAM Module 4GB DIMM 800MT/s                      | 2        | 1.09%   |
| Unknown RAM Module 2GB DIMM 800MT/s                      | 2        | 1.09%   |
| SK Hynix RAM Module 4GB DIMM DDR3 1066MT/s               | 2        | 1.09%   |
| Samsung RAM M378A2K43CB1-CTD 16384MB DIMM DDR4 2667MT/s  | 2        | 1.09%   |
| Kingston RAM Module 4GB DIMM DDR3 1066MT/s               | 2        | 1.09%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s   | 2        | 1.09%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s      | 2        | 1.09%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1867MT/s      | 2        | 1.09%   |
| Kingston RAM KF3600C16D4/16GX 16GB DIMM DDR4 3600MT/s    | 2        | 1.09%   |
| Crucial RAM BLS16G4D32AESB.M16FE 16GB DIMM DDR4 3400MT/s | 2        | 1.09%   |
| Corsair RAM CMW16GX4M2C3000C15 8GB DIMM DDR4 3200MT/s    | 2        | 1.09%   |
| Corsair RAM CML16GX3M2A1600C9 8GB DIMM DDR3 2133MT/s     | 2        | 1.09%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3600MT/s   | 2        | 1.09%   |
| V-GeN RAM D4H8GL32A8TS 8GB DIMM DDR4 3200MT/s            | 1        | 0.54%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                | 1        | 0.54%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                | 1        | 0.54%   |
| Unknown RAM Module 4GB DIMM 400MT/s                      | 1        | 0.54%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 1        | 0.54%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                 | 1        | 0.54%   |
| Unknown RAM Module 2GB DIMM DDR2 1067MT/s                | 1        | 0.54%   |
| Unknown RAM Module 2GB DIMM 667MT/s                      | 1        | 0.54%   |
| Unknown RAM Module 2GB DIMM 400MT/s                      | 1        | 0.54%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                     | 1        | 0.54%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s             | 1        | 0.54%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                 | 1        | 0.54%   |
| Unknown RAM Module 1GB DIMM DDR 333MT/s                  | 1        | 0.54%   |
| Unknown RAM Module 16GB SODIMM DDR4 2667MT/s             | 1        | 0.54%   |
| Unknown RAM CL19-19-19 D4-2666 8192MB DIMM DDR4 2400MT/s | 1        | 0.54%   |
| Unknown RAM 3600 C17 Series 8GB DIMM DDR4 3200MT/s       | 1        | 0.54%   |
| TIMETEC RAM UD4-3600 32GB DIMM DDR4 3600MT/s             | 1        | 0.54%   |
| Timetec RAM 36NU1R8-8G 8GB DIMM DDR4 3600MT/s            | 1        | 0.54%   |
| Team RAM TEAMGROUP-UD4-4000 8GB DIMM DDR4 3200MT/s       | 1        | 0.54%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s       | 1        | 0.54%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3200MT/s      | 1        | 0.54%   |
| Team RAM TEAMGROUP-UD4-2400 8192MB DIMM DDR4 2400MT/s    | 1        | 0.54%   |
| SK Hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s     | 1        | 0.54%   |
| SK Hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s     | 1        | 0.54%   |
| SK Hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s     | 1        | 0.54%   |
| SK Hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1067MT/s     | 1        | 0.54%   |
| SK Hynix RAM HMT125U6BFR8C-H9 2GB DIMM DDR3 1067MT/s     | 1        | 0.54%   |
| SK Hynix RAM HMP125U6EFR8C-S6 2GB DIMM DDR2 800MT/s      | 1        | 0.54%   |
| SK Hynix RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2666MT/s     | 1        | 0.54%   |
| SK Hynix RAM HMA81GU6CJR8N-VK 8GB DIMM DDR4 2667MT/s     | 1        | 0.54%   |
| SK Hynix RAM HMA451U6AFR8N-TF 4096MB DIMM DDR4 2133MT/s  | 1        | 0.54%   |
| SK Hynix RAM HMA41GR7MFR4N-TF 8GB DIMM DDR4 2667MT/s     | 1        | 0.54%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s              | 1        | 0.54%   |
| Samsung RAM Module 4GB DIMM DDR4 2133MT/s                | 1        | 0.54%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s    | 1        | 0.54%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1866MT/s      | 1        | 0.54%   |
| Samsung RAM M378B1G73QH0-CK0 8GB DIMM DDR3 1600MT/s      | 1        | 0.54%   |
| Samsung RAM M378B1G73EB0-CK0 8GB DIMM DDR3 1600MT/s      | 1        | 0.54%   |
| Samsung RAM M378A2G43MX3-CWE 16GB DIMM DDR4 3200MT/s     | 1        | 0.54%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 95       | 61.69%  |
| DDR3    | 41       | 26.62%  |
| Unknown | 13       | 8.44%   |
| DDR2    | 4        | 2.6%    |
| DDR     | 1        | 0.65%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 148      | 96.73%  |
| SODIMM | 5        | 3.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 65       | 40.88%  |
| 16384 | 40       | 25.16%  |
| 4096  | 29       | 18.24%  |
| 2048  | 16       | 10.06%  |
| 32768 | 7        | 4.4%    |
| 1024  | 2        | 1.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 29       | 17.37%  |
| 1600  | 28       | 16.77%  |
| 3600  | 18       | 10.78%  |
| 1333  | 12       | 7.19%   |
| 2400  | 11       | 6.59%   |
| 2667  | 10       | 5.99%   |
| 2133  | 6        | 3.59%   |
| 800   | 6        | 3.59%   |
| 3400  | 5        | 2.99%   |
| 2933  | 5        | 2.99%   |
| 3466  | 4        | 2.4%    |
| 2666  | 4        | 2.4%    |
| 3533  | 3        | 1.8%    |
| 3000  | 3        | 1.8%    |
| 1067  | 3        | 1.8%    |
| 4800  | 2        | 1.2%    |
| 3733  | 2        | 1.2%    |
| 2800  | 2        | 1.2%    |
| 1867  | 2        | 1.2%    |
| 1066  | 2        | 1.2%    |
| 400   | 2        | 1.2%    |
| 3266  | 1        | 0.6%    |
| 3066  | 1        | 0.6%    |
| 2802  | 1        | 0.6%    |
| 2134  | 1        | 0.6%    |
| 1866  | 1        | 0.6%    |
| 1024  | 1        | 0.6%    |
| 667   | 1        | 0.6%    |
| 333   | 1        | 0.6%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Brother Industries  | 6        | 50%     |
| Hewlett-Packard     | 2        | 16.67%  |
| Canon               | 2        | 16.67%  |
| QinHeng Electronics | 1        | 8.33%   |
| Kyocera             | 1        | 8.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Brother HL-L2340D series      | 2        | 16.67%  |
| QinHeng CH340S                | 1        | 8.33%   |
| Kyocera ECOSYS M5521cdw       | 1        | 8.33%   |
| HP LaserJet CM1415fnw         | 1        | 8.33%   |
| HP DeskJet F300 series        | 1        | 8.33%   |
| Canon TR4500 series           | 1        | 8.33%   |
| Canon MF4010 series           | 1        | 8.33%   |
| Brother Printer               | 1        | 8.33%   |
| Brother MFC-J485DW            | 1        | 8.33%   |
| Brother HL-L2360D series      | 1        | 8.33%   |
| Brother HL-1440 Laser Printer | 1        | 8.33%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Canon       | 3        | 60%     |
| Seiko Epson | 2        | 40%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Seiko Epson GT-X770 [Perfection V500]       | 1        | 20%     |
| Seiko Epson GT-X750 [Perfection 4490 Photo] | 1        | 20%     |
| Canon CanoScan LiDE 220                     | 1        | 20%     |
| Canon CanoScan LiDE 210                     | 1        | 20%     |
| Canon CanoScan LiDE 120                     | 1        | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 41       | 55.41%  |
| Microsoft                              | 3        | 4.05%   |
| Microdia                               | 3        | 4.05%   |
| Apple                                  | 3        | 4.05%   |
| Z-Star Microelectronics                | 2        | 2.7%    |
| Trust                                  | 2        | 2.7%    |
| Sunplus Innovation Technology          | 2        | 2.7%    |
| Lenovo                                 | 2        | 2.7%    |
| KYE Systems (Mouse Systems)            | 2        | 2.7%    |
| Jieli Technology                       | 2        | 2.7%    |
| Generalplus Technology                 | 2        | 2.7%    |
| Samsung Electronics                    | 1        | 1.35%   |
| Quanta                                 | 1        | 1.35%   |
| Micro Star International               | 1        | 1.35%   |
| LG Electronics                         | 1        | 1.35%   |
| Hewlett-Packard                        | 1        | 1.35%   |
| Guillemot                              | 1        | 1.35%   |
| Genesys Logic                          | 1        | 1.35%   |
| Cubeternet                             | 1        | 1.35%   |
| Creative Technology                    | 1        | 1.35%   |
| Cheng Uei Precision Industry (Foxlink) | 1        | 1.35%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                                          | 13       | 17.57%  |
| Logitech Webcam C270                                                 | 8        | 10.81%  |
| Logitech StreamCam                                                   | 3        | 4.05%   |
| Logitech HD Webcam C615                                              | 3        | 4.05%   |
| Microdia Webcam Vitade AF                                            | 2        | 2.7%    |
| Logitech QuickCam Pro 9000                                           | 2        | 2.7%    |
| Logitech HD Webcam C525                                              | 2        | 2.7%    |
| Logitech C922 Pro Stream Webcam                                      | 2        | 2.7%    |
| Jieli USB PHY 2.0                                                    | 2        | 2.7%    |
| Generalplus GENERAL WEBCAM                                           | 2        | 2.7%    |
| Apple iPhone 5/5C/5S/6/SE                                            | 2        | 2.7%    |
| Z-Star Venus USB2.0 Camera                                           | 1        | 1.35%   |
| Z-Star Sirius USB 2.0 Camera                                         | 1        | 1.35%   |
| Trust USB Camera                                                     | 1        | 1.35%   |
| Trust Full HD Webcam                                                 | 1        | 1.35%   |
| Sunplus Full HD webcam                                               | 1        | 1.35%   |
| Sunplus ezcap U3 capture-04                                          | 1        | 1.35%   |
| Samsung Galaxy A5 (MTP)                                              | 1        | 1.35%   |
| Quanta HD Camera                                                     | 1        | 1.35%   |
| Microsoft Xbox NUI Camera                                            | 1        | 1.35%   |
| Microsoft LifeCam HD-3000                                            | 1        | 1.35%   |
| Microsoft LifeCam Cinema                                             | 1        | 1.35%   |
| Microdia CyberTrack H6                                               | 1        | 1.35%   |
| Micro Star International MSI USB Device                              | 1        | 1.35%   |
| Logitech Webcam Pro 9000                                             | 1        | 1.35%   |
| Logitech Webcam C930e                                                | 1        | 1.35%   |
| Logitech Webcam C310                                                 | 1        | 1.35%   |
| Logitech Webcam C170                                                 | 1        | 1.35%   |
| Logitech QuickCam Ultra Vision                                       | 1        | 1.35%   |
| Logitech QuickCam Communicate Deluxe                                 | 1        | 1.35%   |
| Logitech HD Webcam C510                                              | 1        | 1.35%   |
| Logitech BRIO Ultra HD Webcam                                        | 1        | 1.35%   |
| LG AN-VC500 Camera                                                   | 1        | 1.35%   |
| Lenovo FULL HD 1080P Webcam                                          | 1        | 1.35%   |
| Lenovo 500 RGB Camera                                                | 1        | 1.35%   |
| KYE Systems (Mouse Systems) Genius iSlim 330                         | 1        | 1.35%   |
| KYE Systems (Mouse Systems) FaceCam 1000X                            | 1        | 1.35%   |
| HP Webcam 1300                                                       | 1        | 1.35%   |
| Guillemot Hercules Dualpix Exchange                                  | 1        | 1.35%   |
| Genesys Logic Camera                                                 | 1        | 1.35%   |
| Cubeternet EtronTech CMOS based eSP570 WebCam [Onyx Titanium TC101]  | 1        | 1.35%   |
| Creative Live! Cam Sync HD [VF0770]                                  | 1        | 1.35%   |
| Cheng Uei Precision Industry (Foxlink) HP High Definition 1MP Webcam | 1        | 1.35%   |
| Apple iSight in LED Cinema Display                                   | 1        | 1.35%   |

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


| Vendor     | Desktops | Percent |
|------------|----------|---------|
| Yubico.com | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                       | Desktops | Percent |
|-----------------------------|----------|---------|
| Yubico.com Yubikey 4/5 CCID | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 280      | 89.17%  |
| 1     | 30       | 9.55%   |
| 2     | 2        | 0.64%   |
| 5     | 1        | 0.32%   |
| 3     | 1        | 0.32%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 12       | 32.43%  |
| Net/wireless             | 11       | 29.73%  |
| Communication controller | 5        | 13.51%  |
| Unassigned class         | 3        | 8.11%   |
| Camera                   | 3        | 8.11%   |
| Sound                    | 2        | 5.41%   |
| Firewire controller      | 1        | 2.7%    |

