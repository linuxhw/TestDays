Garuda Linux - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for Garuda Linux.

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

Total: 208

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | BT6130                      | [3549cfad14](https://linux-hardware.org/?probe=3549cfad14) | Feb 27, 2023 |
| MSI           | MAG B760 TOMAHAWK WIFI D... | [575a7f4897](https://linux-hardware.org/?probe=575a7f4897) | Feb 26, 2023 |
| MSI           | MAG B760 TOMAHAWK WIFI D... | [466f8533fb](https://linux-hardware.org/?probe=466f8533fb) | Feb 26, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [fad109dc98](https://linux-hardware.org/?probe=fad109dc98) | Feb 25, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [a53235325f](https://linux-hardware.org/?probe=a53235325f) | Feb 23, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [bd6a746c89](https://linux-hardware.org/?probe=bd6a746c89) | Feb 20, 2023 |
| MSI           | B450-A PRO                  | [014bf5276e](https://linux-hardware.org/?probe=014bf5276e) | Feb 17, 2023 |
| ASUSTek       | BT6130                      | [db3b191eb2](https://linux-hardware.org/?probe=db3b191eb2) | Feb 13, 2023 |
| ASRock        | A520M-ITX/ac                | [a6e401a1d3](https://linux-hardware.org/?probe=a6e401a1d3) | Feb 09, 2023 |
| Intel         | X79M-S                      | [91ab5e33ed](https://linux-hardware.org/?probe=91ab5e33ed) | Feb 03, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [d6d4c6c38c](https://linux-hardware.org/?probe=d6d4c6c38c) | Jan 31, 2023 |
| ASUSTek       | PRIME Z490-A                | [91dbb8d045](https://linux-hardware.org/?probe=91dbb8d045) | Jan 26, 2023 |
| Intel         | X79M-S                      | [ccad523936](https://linux-hardware.org/?probe=ccad523936) | Jan 22, 2023 |
| ASUSTek       | PRIME A320M-A               | [918dbdb148](https://linux-hardware.org/?probe=918dbdb148) | Jan 22, 2023 |
| ASUSTek       | Rampage IV GENE             | [64553c4fd7](https://linux-hardware.org/?probe=64553c4fd7) | Jan 17, 2023 |
| MSI           | B450M PRO-VDH MAX           | [87e7a60bfa](https://linux-hardware.org/?probe=87e7a60bfa) | Jan 15, 2023 |
| ASUSTek       | CM6850                      | [7eac1c6a7a](https://linux-hardware.org/?probe=7eac1c6a7a) | Jan 13, 2023 |
| ASUSTek       | P8H61/USB3 R2.0             | [5e29a1afb7](https://linux-hardware.org/?probe=5e29a1afb7) | Jan 10, 2023 |
| ASUSTek       | P8H61/USB3 R2.0             | [8daa546122](https://linux-hardware.org/?probe=8daa546122) | Jan 09, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [919b259ea2](https://linux-hardware.org/?probe=919b259ea2) | Jan 09, 2023 |
| ASUSTek       | PRIME X570-P                | [95c21fc90e](https://linux-hardware.org/?probe=95c21fc90e) | Jan 09, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [d759bb7551](https://linux-hardware.org/?probe=d759bb7551) | Jan 08, 2023 |
| MSI           | H61M-E22/W8                 | [92280cb6ae](https://linux-hardware.org/?probe=92280cb6ae) | Jan 06, 2023 |
| ASUSTek       | PRIME B360M-C               | [7685480bf0](https://linux-hardware.org/?probe=7685480bf0) | Jan 05, 2023 |
| Intel         | X79M-S                      | [3b38d8023e](https://linux-hardware.org/?probe=3b38d8023e) | Jan 03, 2023 |
| Dell          | 0VHWTR A02                  | [0d9d6203e1](https://linux-hardware.org/?probe=0d9d6203e1) | Jan 03, 2023 |
| Intel         | X79M-S                      | [5c97a3976d](https://linux-hardware.org/?probe=5c97a3976d) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B660M-E D4       | [a294963db9](https://linux-hardware.org/?probe=a294963db9) | Jan 01, 2023 |
| Lenovo        | Win8 Pro DPK TPG            | [9561e51689](https://linux-hardware.org/?probe=9561e51689) | Dec 31, 2022 |
| Intel         | H61                         | [39f3cddffb](https://linux-hardware.org/?probe=39f3cddffb) | Dec 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [ee98173357](https://linux-hardware.org/?probe=ee98173357) | Dec 27, 2022 |
| ASRock        | X570 Taichi                 | [e48882ad67](https://linux-hardware.org/?probe=e48882ad67) | Dec 22, 2022 |
| ASUSTek       | PRIME Z390-P                | [1a9f9ac05f](https://linux-hardware.org/?probe=1a9f9ac05f) | Dec 22, 2022 |
| Lenovo        | Win8 Pro DPK TPG            | [7ce8a10de4](https://linux-hardware.org/?probe=7ce8a10de4) | Dec 21, 2022 |
| Lenovo        | Win8 Pro DPK TPG            | [a4c1397ad3](https://linux-hardware.org/?probe=a4c1397ad3) | Dec 21, 2022 |
| BESSTAR Te... | B550                        | [d9fbac807d](https://linux-hardware.org/?probe=d9fbac807d) | Dec 10, 2022 |
| ASRock        | Z77 Pro3                    | [a2e7958d4a](https://linux-hardware.org/?probe=a2e7958d4a) | Dec 08, 2022 |
| ASRock        | Z77 Pro3                    | [3184df2bf6](https://linux-hardware.org/?probe=3184df2bf6) | Dec 07, 2022 |
| Gigabyte      | 990FXA-UD3                  | [54d896b9ed](https://linux-hardware.org/?probe=54d896b9ed) | Dec 06, 2022 |
| MSI           | H510I PRO WIFI              | [f46e59c772](https://linux-hardware.org/?probe=f46e59c772) | Nov 27, 2022 |
| Dell          | 0K3CM7 A00                  | [27109cda18](https://linux-hardware.org/?probe=27109cda18) | Nov 20, 2022 |
| Dell          | 0K3CM7 A00                  | [6dbdd86e08](https://linux-hardware.org/?probe=6dbdd86e08) | Nov 20, 2022 |
| HP            | 8767 A                      | [375e0d4525](https://linux-hardware.org/?probe=375e0d4525) | Nov 19, 2022 |
| Gigabyte      | 990FXA-UD3                  | [985fb6d758](https://linux-hardware.org/?probe=985fb6d758) | Nov 16, 2022 |
| Dell          | 0K3CM7 A00                  | [3c426cb32b](https://linux-hardware.org/?probe=3c426cb32b) | Nov 14, 2022 |
| HP            | 2B2C                        | [6f90b1e25e](https://linux-hardware.org/?probe=6f90b1e25e) | Oct 26, 2022 |
| ASUSTek       | PRIME X570-P                | [5558f9e3f7](https://linux-hardware.org/?probe=5558f9e3f7) | Oct 23, 2022 |
| Acer          | Aspire TC-780               | [fd6c66dac7](https://linux-hardware.org/?probe=fd6c66dac7) | Oct 22, 2022 |
| ASUSTek       | PRIME X570-P                | [a7d6f0bd9e](https://linux-hardware.org/?probe=a7d6f0bd9e) | Oct 15, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [541e327f0f](https://linux-hardware.org/?probe=541e327f0f) | Oct 01, 2022 |
| ASUSTek       | PRIME X570-P                | [6647dc20ac](https://linux-hardware.org/?probe=6647dc20ac) | Sep 21, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [9d0697ec96](https://linux-hardware.org/?probe=9d0697ec96) | Sep 20, 2022 |
| ASRock        | A320M-HDV R4.0              | [afbb849b02](https://linux-hardware.org/?probe=afbb849b02) | Sep 11, 2022 |
| ASRock        | A320M-HDV R4.0              | [5e98f641f1](https://linux-hardware.org/?probe=5e98f641f1) | Sep 11, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [ac65980e25](https://linux-hardware.org/?probe=ac65980e25) | Sep 02, 2022 |
| Gigabyte      | F2A88XM-HD3                 | [44e355eb93](https://linux-hardware.org/?probe=44e355eb93) | Aug 30, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [57f1970999](https://linux-hardware.org/?probe=57f1970999) | Aug 20, 2022 |
| ASUSTek       | PRIME X570-P                | [fc5923b017](https://linux-hardware.org/?probe=fc5923b017) | Aug 15, 2022 |
| ASUSTek       | PRIME X570-P                | [e53bbe7c1b](https://linux-hardware.org/?probe=e53bbe7c1b) | Aug 14, 2022 |
| MSI           | A68HM-E33 V2                | [762f08a697](https://linux-hardware.org/?probe=762f08a697) | Aug 13, 2022 |
| ASRock        | A520M-HDV                   | [f23bdacb56](https://linux-hardware.org/?probe=f23bdacb56) | Aug 11, 2022 |
| ASUSTek       | Maximus IX FORMULA          | [2212732244](https://linux-hardware.org/?probe=2212732244) | Aug 01, 2022 |
| MSI           | B450M PRO-VDH MAX           | [941092ee95](https://linux-hardware.org/?probe=941092ee95) | Jul 26, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [dfe6047aa7](https://linux-hardware.org/?probe=dfe6047aa7) | Jul 21, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [f9996d6494](https://linux-hardware.org/?probe=f9996d6494) | Jul 21, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [92fe4c2ff3](https://linux-hardware.org/?probe=92fe4c2ff3) | Jul 03, 2022 |
| ASUSTek       | PRIME B550-PLUS AC-HES      | [dde2246ae8](https://linux-hardware.org/?probe=dde2246ae8) | Jul 01, 2022 |
| ASRock        | Z87M Extreme4               | [06504aecc5](https://linux-hardware.org/?probe=06504aecc5) | Jun 24, 2022 |
| Gigabyte      | Z77X-UD3H                   | [7d7828a253](https://linux-hardware.org/?probe=7d7828a253) | Jun 23, 2022 |
| MSI           | B550-A PRO                  | [a7a76f04f9](https://linux-hardware.org/?probe=a7a76f04f9) | Jun 19, 2022 |
| MSI           | B450M MORTAR MAX            | [e1f785770e](https://linux-hardware.org/?probe=e1f785770e) | Jun 11, 2022 |
| T-bao         | MINI PC V1.0                | [8108463ab7](https://linux-hardware.org/?probe=8108463ab7) | Jun 09, 2022 |
| ASRock        | Z87M Extreme4               | [5ca7bb09b0](https://linux-hardware.org/?probe=5ca7bb09b0) | Jun 05, 2022 |
| Lenovo        | 3716 SDK0T76463 WIN 3422... | [cd15058963](https://linux-hardware.org/?probe=cd15058963) | May 16, 2022 |
| Lenovo        | 3716 SDK0T76463 WIN 3422... | [4043d7e26a](https://linux-hardware.org/?probe=4043d7e26a) | May 11, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [8c34e423f4](https://linux-hardware.org/?probe=8c34e423f4) | May 04, 2022 |
| Dell          | 0WR7PY A01                  | [66c6e57421](https://linux-hardware.org/?probe=66c6e57421) | Apr 23, 2022 |
| ASRock        | B550M Pro4                  | [b82721163b](https://linux-hardware.org/?probe=b82721163b) | Apr 22, 2022 |
| ASRock        | X99X Killer                 | [c6d6bddd17](https://linux-hardware.org/?probe=c6d6bddd17) | Apr 18, 2022 |
| ASUSTek       | Z97-P                       | [bf54ec19d0](https://linux-hardware.org/?probe=bf54ec19d0) | Apr 16, 2022 |
| ASRock        | X99X Killer                 | [3be92995ff](https://linux-hardware.org/?probe=3be92995ff) | Apr 11, 2022 |
| ASUSTek       | P8B75-M                     | [808661699f](https://linux-hardware.org/?probe=808661699f) | Apr 07, 2022 |
| HP            | 8433 11                     | [30c5d1d62f](https://linux-hardware.org/?probe=30c5d1d62f) | Apr 03, 2022 |
| MSI           | B450-A PRO MAX              | [a47ab656ab](https://linux-hardware.org/?probe=a47ab656ab) | Apr 01, 2022 |
| Gigabyte      | B550 GAMING X V2            | [3d37374fae](https://linux-hardware.org/?probe=3d37374fae) | Apr 01, 2022 |
| ASUSTek       | A68HM-PLUS                  | [cd6ebcba97](https://linux-hardware.org/?probe=cd6ebcba97) | Mar 31, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [fc5cdc4595](https://linux-hardware.org/?probe=fc5cdc4595) | Mar 23, 2022 |
| MSI           | MPG B550 GAMING CARBON W... | [c1a26607fd](https://linux-hardware.org/?probe=c1a26607fd) | Mar 13, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [95b7c99a5a](https://linux-hardware.org/?probe=95b7c99a5a) | Mar 08, 2022 |
| ASRock        | B450 Gaming K4              | [504b20acce](https://linux-hardware.org/?probe=504b20acce) | Mar 04, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [336ddc137d](https://linux-hardware.org/?probe=336ddc137d) | Mar 01, 2022 |
| ASUSTek       | A68HM-PLUS                  | [edfa6eb6e3](https://linux-hardware.org/?probe=edfa6eb6e3) | Feb 28, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | [abc925b917](https://linux-hardware.org/?probe=abc925b917) | Feb 26, 2022 |
| ASUSTek       | M4A89TD PRO USB3            | [66c0fc8423](https://linux-hardware.org/?probe=66c0fc8423) | Feb 26, 2022 |
| HP            | 8767 A                      | [e048574911](https://linux-hardware.org/?probe=e048574911) | Feb 12, 2022 |
| ASUSTek       | ROG Maximus XII FORMULA     | [a63d909e46](https://linux-hardware.org/?probe=a63d909e46) | Feb 12, 2022 |
| HP            | 8767 A                      | [6cb1e6b72f](https://linux-hardware.org/?probe=6cb1e6b72f) | Feb 12, 2022 |
| ASUSTek       | ROG Maximus XII FORMULA     | [885617bdda](https://linux-hardware.org/?probe=885617bdda) | Feb 12, 2022 |
| ASRock        | B450M Pro4                  | [0d80dc8143](https://linux-hardware.org/?probe=0d80dc8143) | Feb 11, 2022 |
| Lenovo        | 31900058 STD                | [03540e9cb2](https://linux-hardware.org/?probe=03540e9cb2) | Feb 07, 2022 |
| Gigabyte      | MFLP3AP-00\2.x              | [b7441a0e94](https://linux-hardware.org/?probe=b7441a0e94) | Jan 31, 2022 |
| Gigabyte      | B85-HD3                     | [ad70601774](https://linux-hardware.org/?probe=ad70601774) | Jan 26, 2022 |
| ASRock        | 970M Pro3                   | [402a4f960e](https://linux-hardware.org/?probe=402a4f960e) | Jan 17, 2022 |
| ASUSTek       | ROG Maximus X CODE          | [8fac80f31d](https://linux-hardware.org/?probe=8fac80f31d) | Jan 16, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [9fab263b02](https://linux-hardware.org/?probe=9fab263b02) | Jan 11, 2022 |
| MSI           | Z270 GAMING M5              | [02d70182fd](https://linux-hardware.org/?probe=02d70182fd) | Jan 10, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [8a1167daea](https://linux-hardware.org/?probe=8a1167daea) | Jan 08, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [1a4570a458](https://linux-hardware.org/?probe=1a4570a458) | Jan 08, 2022 |
| Pegatron      | 2AD5                        | [91ee5ba1df](https://linux-hardware.org/?probe=91ee5ba1df) | Jan 08, 2022 |
| Gigabyte      | B460M DS3H                  | [40f4de9da7](https://linux-hardware.org/?probe=40f4de9da7) | Jan 07, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | [1b62246b10](https://linux-hardware.org/?probe=1b62246b10) | Dec 21, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [9e73346fb8](https://linux-hardware.org/?probe=9e73346fb8) | Dec 15, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [196b460373](https://linux-hardware.org/?probe=196b460373) | Dec 13, 2021 |
| ASRock        | H77M-ITX                    | [5e98a2fce2](https://linux-hardware.org/?probe=5e98a2fce2) | Dec 11, 2021 |
| ASRock        | B450M Pro4                  | [e4fb1e4fe4](https://linux-hardware.org/?probe=e4fb1e4fe4) | Dec 09, 2021 |
| Lenovo        | ThinkStation S20 4105O1U    | [731c890641](https://linux-hardware.org/?probe=731c890641) | Dec 08, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [f0df07c0e4](https://linux-hardware.org/?probe=f0df07c0e4) | Dec 06, 2021 |
| Acer          | Aspire TC-895 V:1.0         | [c743459a71](https://linux-hardware.org/?probe=c743459a71) | Dec 04, 2021 |
| ASUSTek       | H87M-E                      | [2b4abcf54f](https://linux-hardware.org/?probe=2b4abcf54f) | Dec 02, 2021 |
| ASUSTek       | H87M-E                      | [72cf0ed74d](https://linux-hardware.org/?probe=72cf0ed74d) | Dec 02, 2021 |
| Lenovo        | ThinkStation S20 4105O1U    | [f031548aac](https://linux-hardware.org/?probe=f031548aac) | Dec 01, 2021 |
| Lenovo        | ThinkStation S20 4105O1U    | [48f73af82d](https://linux-hardware.org/?probe=48f73af82d) | Nov 30, 2021 |
| ASUSTek       | Rampage IV EXTREME          | [50999d4796](https://linux-hardware.org/?probe=50999d4796) | Nov 14, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [cd295bb56c](https://linux-hardware.org/?probe=cd295bb56c) | Nov 04, 2021 |
| ASUSTek       | P8B75-M                     | [2130c28d33](https://linux-hardware.org/?probe=2130c28d33) | Oct 27, 2021 |
| MSI           | Z77A-G43                    | [3bd9604ae7](https://linux-hardware.org/?probe=3bd9604ae7) | Oct 20, 2021 |
| MSI           | B460M PRO-VDH WIFI          | [76071ec77b](https://linux-hardware.org/?probe=76071ec77b) | Oct 19, 2021 |
| MSI           | B450M-A PRO MAX             | [4148046f02](https://linux-hardware.org/?probe=4148046f02) | Oct 17, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | [fdd8f9dd8e](https://linux-hardware.org/?probe=fdd8f9dd8e) | Sep 17, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | [ab3ad8009e](https://linux-hardware.org/?probe=ab3ad8009e) | Sep 16, 2021 |
| ASUSTek       | PRIME B450M-K               | [b8b49f201f](https://linux-hardware.org/?probe=b8b49f201f) | Sep 14, 2021 |
| MSI           | H310M PRO-VDH PLUS          | [65fcfef06f](https://linux-hardware.org/?probe=65fcfef06f) | Aug 27, 2021 |
| Alienware     | 0TYR0X A00                  | [5ea23ebfb2](https://linux-hardware.org/?probe=5ea23ebfb2) | Aug 19, 2021 |
| ASRock        | X399 Professional Gaming    | [bb53a385c3](https://linux-hardware.org/?probe=bb53a385c3) | Aug 19, 2021 |
| Medion        | H110H4-EM2                  | [f4e01958e5](https://linux-hardware.org/?probe=f4e01958e5) | Aug 10, 2021 |
| MSI           | Z97 MPOWER                  | [dee7d3af4a](https://linux-hardware.org/?probe=dee7d3af4a) | Aug 06, 2021 |
| MSI           | Z97 MPOWER                  | [f30e5a3a86](https://linux-hardware.org/?probe=f30e5a3a86) | Aug 06, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [826edd51bc](https://linux-hardware.org/?probe=826edd51bc) | Jul 07, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [aa05cca9b7](https://linux-hardware.org/?probe=aa05cca9b7) | Jun 30, 2021 |
| Biostar       | H310MHP                     | [0d3f648f3e](https://linux-hardware.org/?probe=0d3f648f3e) | Jun 30, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [fb3d7de63c](https://linux-hardware.org/?probe=fb3d7de63c) | Jun 26, 2021 |
| MSI           | A320M-HDV R4.0              | [486775a989](https://linux-hardware.org/?probe=486775a989) | Jun 23, 2021 |
| MSI           | A320M-HDV R4.0              | [4629f86f56](https://linux-hardware.org/?probe=4629f86f56) | Jun 22, 2021 |
| MSI           | A320M-HDV R4.0              | [69dea4e3cf](https://linux-hardware.org/?probe=69dea4e3cf) | Jun 22, 2021 |
| MSI           | A320M-HDV R4.0              | [2fd89c951e](https://linux-hardware.org/?probe=2fd89c951e) | Jun 22, 2021 |
| MSI           | X370 GAMING PRO CARBON      | [9ead1e1bb5](https://linux-hardware.org/?probe=9ead1e1bb5) | Jun 22, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [8144c83b50](https://linux-hardware.org/?probe=8144c83b50) | Jun 22, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [376c0ff95d](https://linux-hardware.org/?probe=376c0ff95d) | Jun 15, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [34801a2f74](https://linux-hardware.org/?probe=34801a2f74) | Jun 12, 2021 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [51e1e33185](https://linux-hardware.org/?probe=51e1e33185) | May 20, 2021 |
| MSI           | B350M GAMING PRO            | [c04e6666e7](https://linux-hardware.org/?probe=c04e6666e7) | May 20, 2021 |
| Dell          | 0D28YY A02                  | [14edf3bd00](https://linux-hardware.org/?probe=14edf3bd00) | May 16, 2021 |
| Gigabyte      | A320M-S2H-CF                | [066f815622](https://linux-hardware.org/?probe=066f815622) | May 12, 2021 |
| HP            | 844C                        | [29f7cf64ce](https://linux-hardware.org/?probe=29f7cf64ce) | May 06, 2021 |
| HP            | 844C                        | [0534f06ec4](https://linux-hardware.org/?probe=0534f06ec4) | May 06, 2021 |
| ASUSTek       | PRIME Z590-A                | [cb3058760e](https://linux-hardware.org/?probe=cb3058760e) | May 04, 2021 |
| Gigabyte      | P67A-UD3-B3                 | [08ea956bfa](https://linux-hardware.org/?probe=08ea956bfa) | Apr 24, 2021 |
| MSI           | Z87 MPOWER                  | [ff6aa3811c](https://linux-hardware.org/?probe=ff6aa3811c) | Apr 08, 2021 |
| ASRock        | AB350M-HDV                  | [23502edac5](https://linux-hardware.org/?probe=23502edac5) | Apr 01, 2021 |
| ASRock        | AB350M-HDV                  | [13b2fdddc0](https://linux-hardware.org/?probe=13b2fdddc0) | Apr 01, 2021 |
| Dell          | 07KY25 A01                  | [8c4f2f9922](https://linux-hardware.org/?probe=8c4f2f9922) | Mar 31, 2021 |
| Dell          | 07KY25 A01                  | [1b9efb1b29](https://linux-hardware.org/?probe=1b9efb1b29) | Mar 24, 2021 |
| Gigabyte      | B450 AORUS M                | [097a0d616c](https://linux-hardware.org/?probe=097a0d616c) | Mar 18, 2021 |
| Gigabyte      | B450 AORUS M                | [22054ffd75](https://linux-hardware.org/?probe=22054ffd75) | Mar 18, 2021 |
| HP            | 2AF7                        | [e0639ea4a5](https://linux-hardware.org/?probe=e0639ea4a5) | Mar 11, 2021 |
| HP            | 2AF7                        | [fb8d76722c](https://linux-hardware.org/?probe=fb8d76722c) | Mar 11, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [c1f22a7521](https://linux-hardware.org/?probe=c1f22a7521) | Mar 05, 2021 |
| Gigabyte      | GA-MA790FXT-UD5P            | [404dab2464](https://linux-hardware.org/?probe=404dab2464) | Feb 27, 2021 |
| ASRock        | FM2A88X Extreme6+           | [13f9fc2ef3](https://linux-hardware.org/?probe=13f9fc2ef3) | Feb 18, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2e19f3b1af](https://linux-hardware.org/?probe=2e19f3b1af) | Feb 18, 2021 |
| Dell          | 0C2KJT A00                  | [f821a0035b](https://linux-hardware.org/?probe=f821a0035b) | Feb 12, 2021 |
| ASUSTek       | PRIME B360M-K               | [b73941c431](https://linux-hardware.org/?probe=b73941c431) | Feb 08, 2021 |
| HP            | 1825                        | [3b6b80db46](https://linux-hardware.org/?probe=3b6b80db46) | Jan 31, 2021 |
| HP            | 1825                        | [1df894dea4](https://linux-hardware.org/?probe=1df894dea4) | Jan 31, 2021 |
| ASRock        | X470 Master SLI             | [36eaf717e9](https://linux-hardware.org/?probe=36eaf717e9) | Jan 26, 2021 |
| ASRock        | X470 Master SLI             | [b1be9375c0](https://linux-hardware.org/?probe=b1be9375c0) | Jan 24, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [7332b50f98](https://linux-hardware.org/?probe=7332b50f98) | Jan 24, 2021 |
| ASUSTek       | PRIME H270-PLUS             | [3f895b585b](https://linux-hardware.org/?probe=3f895b585b) | Jan 22, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [61976e9745](https://linux-hardware.org/?probe=61976e9745) | Jan 18, 2021 |
| MSI           | X399 SLI PLUS               | [e392838a54](https://linux-hardware.org/?probe=e392838a54) | Jan 10, 2021 |
| ASUSTek       | CM5671                      | [069344a54e](https://linux-hardware.org/?probe=069344a54e) | Jan 07, 2021 |
| MSI           | B85-G43 GAMING              | [8fe013f04a](https://linux-hardware.org/?probe=8fe013f04a) | Jan 04, 2021 |
| ASRock        | G41M-VS3                    | [e1217b1871](https://linux-hardware.org/?probe=e1217b1871) | Jan 02, 2021 |
| Pegatron      | 2AC2A                       | [436a2ca3ce](https://linux-hardware.org/?probe=436a2ca3ce) | Dec 25, 2020 |
| Pegatron      | 2AC2A                       | [2df3b195c6](https://linux-hardware.org/?probe=2df3b195c6) | Dec 25, 2020 |
| ASUSTek       | PRIME Z370-P                | [35365be0e8](https://linux-hardware.org/?probe=35365be0e8) | Dec 19, 2020 |
| MSI           | Z390-A PRO                  | [ea7a52fdac](https://linux-hardware.org/?probe=ea7a52fdac) | Dec 16, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [62a5c95d51](https://linux-hardware.org/?probe=62a5c95d51) | Dec 14, 2020 |
| HP            | 8643 SMVB                   | [dccfba36f1](https://linux-hardware.org/?probe=dccfba36f1) | Dec 06, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [2a35d394f9](https://linux-hardware.org/?probe=2a35d394f9) | Dec 04, 2020 |
| MSI           | Z390-A PRO                  | [05e3eb32c9](https://linux-hardware.org/?probe=05e3eb32c9) | Dec 03, 2020 |
| MSI           | Z390-A PRO                  | [dc6ea9bfb8](https://linux-hardware.org/?probe=dc6ea9bfb8) | Nov 29, 2020 |
| ASUSTek       | M5A97 LE R2.0               | [d4b3f84c86](https://linux-hardware.org/?probe=d4b3f84c86) | Nov 28, 2020 |
| Gigabyte      | B450 AORUS M                | [a3d68dc126](https://linux-hardware.org/?probe=a3d68dc126) | Nov 19, 2020 |
| Gigabyte      | B450 AORUS M                | [d9faeae0d4](https://linux-hardware.org/?probe=d9faeae0d4) | Nov 19, 2020 |
| Gigabyte      | X570 AORUS PRO WIFI         | [11c79940a4](https://linux-hardware.org/?probe=11c79940a4) | Nov 19, 2020 |
| HP            | 18E7                        | [f84cbfd465](https://linux-hardware.org/?probe=f84cbfd465) | Nov 10, 2020 |
| Gigabyte      | X570 AORUS PRO WIFI         | [79608bd849](https://linux-hardware.org/?probe=79608bd849) | Nov 06, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [e80ddac12f](https://linux-hardware.org/?probe=e80ddac12f) | Nov 02, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [876b039494](https://linux-hardware.org/?probe=876b039494) | Nov 01, 2020 |
| Gigabyte      | X570 AORUS PRO WIFI         | [4e573bc6ff](https://linux-hardware.org/?probe=4e573bc6ff) | Oct 28, 2020 |
| MSI           | MPG B550 GAMING EDGE WIF... | [4b9d2b77cb](https://linux-hardware.org/?probe=4b9d2b77cb) | Oct 26, 2020 |
| ASUSTek       | PRIME X399-A                | [b7772d9ff8](https://linux-hardware.org/?probe=b7772d9ff8) | Oct 13, 2020 |
| Dell          | 0R6JMP A00                  | [c4cbec5b80](https://linux-hardware.org/?probe=c4cbec5b80) | Oct 11, 2020 |
| OEM           | Unknown                     | [2e7a212437](https://linux-hardware.org/?probe=2e7a212437) | Sep 26, 2020 |
| Lenovo        | ThinkCentre M91p 7033CG1    | [c08fed8ecb](https://linux-hardware.org/?probe=c08fed8ecb) | Sep 11, 2020 |
| ASUSTek       | Maximus VIII FORMULA        | [7b8babe846](https://linux-hardware.org/?probe=7b8babe846) | Aug 27, 2020 |
| ASUSTek       | Maximus VIII FORMULA        | [73462df387](https://linux-hardware.org/?probe=73462df387) | Aug 07, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Garuda Linux Soaring | 74       | 50%     |
| Garuda Linux         | 54       | 36.49%  |
| Garuda Linux Rolling | 20       | 13.51%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Garuda Linux | 144      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Desktops | Percent |
|---------------------------|----------|---------|
| 5.17.1-zen1-1-zen         | 6        | 3.68%   |
| 6.1.12-zen1-1-zen         | 4        | 2.45%   |
| 6.1.1-zen1-1-zen          | 4        | 2.45%   |
| 5.15.7-zen1-1-zen         | 4        | 2.45%   |
| 5.10.4-107-tkg-bmq        | 4        | 2.45%   |
| 6.1.8-zen1-1-zen          | 3        | 1.84%   |
| 6.0.2-zen1-1-zen          | 3        | 1.84%   |
| 6.0.12-zen1-1-zen         | 3        | 1.84%   |
| 6.0.11-zen1-1-zen         | 3        | 1.84%   |
| 5.9.1-zen2-1-zen          | 3        | 1.84%   |
| 5.18.12-zen1-1-zen        | 3        | 1.84%   |
| 5.18.1-zen1-1-zen         | 3        | 1.84%   |
| 5.16.4-zen1-1-zen         | 3        | 1.84%   |
| 5.15.2-zen1-1-zen         | 3        | 1.84%   |
| 5.15.13-zen1-1-zen        | 3        | 1.84%   |
| 5.11.16-zen1-1-zen        | 3        | 1.84%   |
| 6.1.4-zen2-1-zen          | 2        | 1.23%   |
| 6.1.3-zen1-1-zen          | 2        | 1.23%   |
| 6.0.8-zen1-1-zen          | 2        | 1.23%   |
| 5.9.11-zen2-1-zen         | 2        | 1.23%   |
| 5.9.10-zen1-1-zen         | 2        | 1.23%   |
| 5.8.14-zen1-1-zen         | 2        | 1.23%   |
| 5.19.9-zen1-1-zen         | 2        | 1.23%   |
| 5.19.5-zen1-1-zen         | 2        | 1.23%   |
| 5.18.16-zen1-1-zen        | 2        | 1.23%   |
| 5.16.8-zen1-1-zen         | 2        | 1.23%   |
| 5.16.11-zen1-1-zen        | 2        | 1.23%   |
| 5.16.10-zen1-1-zen        | 2        | 1.23%   |
| 5.16.0-zen1-1-zen         | 2        | 1.23%   |
| 5.15.12-zen1-1-zen        | 2        | 1.23%   |
| 5.15.10-zen1-1-zen        | 2        | 1.23%   |
| 5.13.9-zen1-1-zen         | 2        | 1.23%   |
| 5.13.12-zen1-1-zen        | 2        | 1.23%   |
| 5.12.4-zen1-2-zen         | 2        | 1.23%   |
| 5.10.8-112-tkg-bmq        | 2        | 1.23%   |
| 6.1.9-zen1-2-zen          | 1        | 0.61%   |
| 6.1.7-zen1-1-zen          | 1        | 0.61%   |
| 6.1.5-zen2-1-zen          | 1        | 0.61%   |
| 6.1.4-AMD                 | 1        | 0.61%   |
| 6.1.10-2-cachyos-bore-lto | 1        | 0.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.17.1  | 6        | 3.68%   |
| 6.1.12  | 4        | 2.45%   |
| 6.1.1   | 4        | 2.45%   |
| 5.15.7  | 4        | 2.45%   |
| 5.10.4  | 4        | 2.45%   |
| 6.1.8   | 3        | 1.84%   |
| 6.1.4   | 3        | 1.84%   |
| 6.0.2   | 3        | 1.84%   |
| 6.0.12  | 3        | 1.84%   |
| 6.0.11  | 3        | 1.84%   |
| 5.9.1   | 3        | 1.84%   |
| 5.18.12 | 3        | 1.84%   |
| 5.18.1  | 3        | 1.84%   |
| 5.16.4  | 3        | 1.84%   |
| 5.15.2  | 3        | 1.84%   |
| 5.15.13 | 3        | 1.84%   |
| 5.12.13 | 3        | 1.84%   |
| 5.11.16 | 3        | 1.84%   |
| 6.1.3   | 2        | 1.23%   |
| 6.0.8   | 2        | 1.23%   |
| 5.9.11  | 2        | 1.23%   |
| 5.9.10  | 2        | 1.23%   |
| 5.8.14  | 2        | 1.23%   |
| 5.19.9  | 2        | 1.23%   |
| 5.19.5  | 2        | 1.23%   |
| 5.18.16 | 2        | 1.23%   |
| 5.17.5  | 2        | 1.23%   |
| 5.17.3  | 2        | 1.23%   |
| 5.16.8  | 2        | 1.23%   |
| 5.16.11 | 2        | 1.23%   |
| 5.16.10 | 2        | 1.23%   |
| 5.16.0  | 2        | 1.23%   |
| 5.15.12 | 2        | 1.23%   |
| 5.15.10 | 2        | 1.23%   |
| 5.14.12 | 2        | 1.23%   |
| 5.13.9  | 2        | 1.23%   |
| 5.13.12 | 2        | 1.23%   |
| 5.12.4  | 2        | 1.23%   |
| 5.12.12 | 2        | 1.23%   |
| 5.10.8  | 2        | 1.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.1     | 19       | 12.03%  |
| 5.15    | 19       | 12.03%  |
| 5.10    | 16       | 10.13%  |
| 5.16    | 15       | 9.49%   |
| 5.18    | 14       | 8.86%   |
| 6.0     | 13       | 8.23%   |
| 5.17    | 10       | 6.33%   |
| 5.12    | 10       | 6.33%   |
| 5.11    | 10       | 6.33%   |
| 5.9     | 9        | 5.7%    |
| 5.19    | 7        | 4.43%   |
| 5.13    | 6        | 3.8%    |
| 5.8     | 5        | 3.16%   |
| 5.14    | 5        | 3.16%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 144      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| KDE5       | 97       | 65.99%  |
| KDE        | 19       | 12.93%  |
| GNOME      | 18       | 12.24%  |
| X-Cinnamon | 3        | 2.04%   |
| xfce       | 2        | 1.36%   |
| LXQt       | 2        | 1.36%   |
| sway       | 1        | 0.68%   |
| MATE       | 1        | 0.68%   |
| i3         | 1        | 0.68%   |
| Deepin     | 1        | 0.68%   |
| Cinnamon   | 1        | 0.68%   |
| Unknown    | 1        | 0.68%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 132      | 91.03%  |
| Wayland | 5        | 3.45%   |
| Tty     | 5        | 3.45%   |
| Unknown | 3        | 2.07%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 68       | 46.9%   |
| SDDM    | 60       | 41.38%  |
| LightDM | 10       | 6.9%    |
| GDM     | 6        | 4.14%   |
| GREETD  | 1        | 0.69%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 73       | 50.34%  |
| de_DE | 16       | 11.03%  |
| en_GB | 13       | 8.97%   |
| es_ES | 5        | 3.45%   |
| en_CA | 4        | 2.76%   |
| en_AU | 4        | 2.76%   |
| pt_BR | 3        | 2.07%   |
| it_IT | 3        | 2.07%   |
| sk_SK | 2        | 1.38%   |
| ru_RU | 2        | 1.38%   |
| nl_NL | 2        | 1.38%   |
| fr_BE | 2        | 1.38%   |
| en_IN | 2        | 1.38%   |
| da_DK | 2        | 1.38%   |
| sv_SE | 1        | 0.69%   |
| nl_BE | 1        | 0.69%   |
| nb_NO | 1        | 0.69%   |
| iu_CA | 1        | 0.69%   |
| hu_HU | 1        | 0.69%   |
| fr_FR | 1        | 0.69%   |
| es_VE | 1        | 0.69%   |
| es_AR | 1        | 0.69%   |
| en_ZA | 1        | 0.69%   |
| en_DE | 1        | 0.69%   |
| el_GR | 1        | 0.69%   |
| cs_CZ | 1        | 0.69%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 76       | 52.78%  |
| BIOS | 68       | 47.22%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Btrfs   | 141      | 97.92%  |
| Ext4    | 2        | 1.39%   |
| Overlay | 1        | 0.69%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 72       | 49.66%  |
| Unknown | 68       | 46.9%   |
| MBR     | 5        | 3.45%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 117      | 80.14%  |
| Yes       | 29       | 19.86%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 98       | 67.59%  |
| Yes       | 47       | 32.41%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 42       | 29.17%  |
| MSI                 | 27       | 18.75%  |
| Gigabyte Technology | 24       | 16.67%  |
| ASRock              | 16       | 11.11%  |
| Hewlett-Packard     | 8        | 5.56%   |
| Lenovo              | 7        | 4.86%   |
| Dell                | 7        | 4.86%   |
| Pegatron            | 2        | 1.39%   |
| Intel               | 2        | 1.39%   |
| Acer                | 2        | 1.39%   |
| T-bao               | 1        | 0.69%   |
| OEM                 | 1        | 0.69%   |
| Medion              | 1        | 0.69%   |
| Fujitsu             | 1        | 0.69%   |
| Biostar             | 1        | 0.69%   |
| BESSTAR Tech        | 1        | 0.69%   |
| Alienware           | 1        | 0.69%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| ASUS TUF Gaming X570-PLUS          | 4        | 2.78%   |
| MSI MS-7C91                        | 2        | 1.39%   |
| MSI MS-7B86                        | 2        | 1.39%   |
| Gigabyte X570 AORUS PRO WIFI       | 2        | 1.39%   |
| Gigabyte AB350-Gaming 3            | 2        | 1.39%   |
| Dell Inspiron 3668                 | 2        | 1.39%   |
| ASUS ROG STRIX X570-E GAMING       | 2        | 1.39%   |
| ASUS ROG STRIX B550-F GAMING       | 2        | 1.39%   |
| ASUS PRIME X570-P                  | 2        | 1.39%   |
| ASUS All Series                    | 2        | 1.39%   |
| T-bao MINI PC                      | 1        | 0.69%   |
| Pegatron p7-1030                   | 1        | 0.69%   |
| Pegatron h9-1301es                 | 1        | 0.69%   |
| MSI MS-7D96                        | 1        | 0.69%   |
| MSI MS-7D75                        | 1        | 0.69%   |
| MSI MS-7D16                        | 1        | 0.69%   |
| MSI MS-7C90                        | 1        | 0.69%   |
| MSI MS-7C83                        | 1        | 0.69%   |
| MSI MS-7C56                        | 1        | 0.69%   |
| MSI MS-7C52                        | 1        | 0.69%   |
| MSI MS-7C37                        | 1        | 0.69%   |
| MSI MS-7C09                        | 1        | 0.69%   |
| MSI MS-7C02                        | 1        | 0.69%   |
| MSI MS-7B98                        | 1        | 0.69%   |
| MSI MS-7B89                        | 1        | 0.69%   |
| MSI MS-7B09                        | 1        | 0.69%   |
| MSI MS-7A78                        | 1        | 0.69%   |
| MSI MS-7A39                        | 1        | 0.69%   |
| MSI MS-7A38                        | 1        | 0.69%   |
| MSI MS-7A32                        | 1        | 0.69%   |
| MSI MS-7818                        | 1        | 0.69%   |
| MSI MS-7816                        | 1        | 0.69%   |
| MSI MS-7788                        | 1        | 0.69%   |
| MSI MS-7758                        | 1        | 0.69%   |
| MSI MS-7721                        | 1        | 0.69%   |
| MSI A320M-HDV R4.0                 | 1        | 0.69%   |
| Medion Akoya P5238 F/C395          | 1        | 0.69%   |
| Lenovo ThinkStation S20 4105O1U    | 1        | 0.69%   |
| Lenovo ThinkCentre M93p 10A90048US | 1        | 0.69%   |
| Lenovo ThinkCentre M93p 10A90016US | 1        | 0.69%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ASUS PRIME            | 12       | 8.33%   |
| ASUS ROG              | 9        | 6.25%   |
| ASUS TUF              | 6        | 4.17%   |
| Lenovo ThinkCentre    | 4        | 2.78%   |
| Gigabyte X570         | 4        | 2.78%   |
| Dell Inspiron         | 4        | 2.78%   |
| HP Pavilion           | 3        | 2.08%   |
| Gigabyte B550         | 3        | 2.08%   |
| Gigabyte B450         | 3        | 2.08%   |
| Dell OptiPlex         | 3        | 2.08%   |
| MSI MS-7C91           | 2        | 1.39%   |
| MSI MS-7B86           | 2        | 1.39%   |
| Gigabyte AB350-Gaming | 2        | 1.39%   |
| ASUS Rampage          | 2        | 1.39%   |
| ASUS Maximus          | 2        | 1.39%   |
| ASUS All              | 2        | 1.39%   |
| Acer Aspire           | 2        | 1.39%   |
| T-bao MINI            | 1        | 0.69%   |
| Pegatron p7-1030      | 1        | 0.69%   |
| Pegatron h9-1301es    | 1        | 0.69%   |
| MSI MS-7D96           | 1        | 0.69%   |
| MSI MS-7D75           | 1        | 0.69%   |
| MSI MS-7D16           | 1        | 0.69%   |
| MSI MS-7C90           | 1        | 0.69%   |
| MSI MS-7C83           | 1        | 0.69%   |
| MSI MS-7C56           | 1        | 0.69%   |
| MSI MS-7C52           | 1        | 0.69%   |
| MSI MS-7C37           | 1        | 0.69%   |
| MSI MS-7C09           | 1        | 0.69%   |
| MSI MS-7C02           | 1        | 0.69%   |
| MSI MS-7B98           | 1        | 0.69%   |
| MSI MS-7B89           | 1        | 0.69%   |
| MSI MS-7B09           | 1        | 0.69%   |
| MSI MS-7A78           | 1        | 0.69%   |
| MSI MS-7A39           | 1        | 0.69%   |
| MSI MS-7A38           | 1        | 0.69%   |
| MSI MS-7A32           | 1        | 0.69%   |
| MSI MS-7818           | 1        | 0.69%   |
| MSI MS-7816           | 1        | 0.69%   |
| MSI MS-7788           | 1        | 0.69%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 24       | 16.67%  |
| 2020 | 20       | 13.89%  |
| 2018 | 18       | 12.5%   |
| 2017 | 16       | 11.11%  |
| 2021 | 11       | 7.64%   |
| 2014 | 11       | 7.64%   |
| 2013 | 11       | 7.64%   |
| 2012 | 10       | 6.94%   |
| 2022 | 5        | 3.47%   |
| 2011 | 5        | 3.47%   |
| 2015 | 4        | 2.78%   |
| 2010 | 4        | 2.78%   |
| 2016 | 3        | 2.08%   |
| 2009 | 2        | 1.39%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 144      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 144      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 144      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 42       | 28.97%  |
| 32.01-64.0  | 41       | 28.28%  |
| 8.01-16.0   | 23       | 15.86%  |
| 4.01-8.0    | 15       | 10.34%  |
| 24.01-32.0  | 10       | 6.9%    |
| 64.01-256.0 | 10       | 6.9%    |
| 3.01-4.0    | 4        | 2.76%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 60       | 39.47%  |
| 3.01-4.0   | 30       | 19.74%  |
| 8.01-16.0  | 26       | 17.11%  |
| 2.01-3.0   | 21       | 13.82%  |
| 1.01-2.0   | 8        | 5.26%   |
| 16.01-24.0 | 6        | 3.95%   |
| 32.01-64.0 | 1        | 0.66%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 44       | 29.33%  |
| 3      | 34       | 22.67%  |
| 4      | 24       | 16%     |
| 1      | 22       | 14.67%  |
| 5      | 14       | 9.33%   |
| 6      | 5        | 3.33%   |
| 9      | 4        | 2.67%   |
| 18     | 1        | 0.67%   |
| 14     | 1        | 0.67%   |
| 7      | 1        | 0.67%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 100      | 68.97%  |
| Yes       | 45       | 31.03%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 142      | 98.61%  |
| No        | 2        | 1.39%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 79       | 53.38%  |
| No        | 69       | 46.62%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 74       | 50.34%  |
| Yes       | 73       | 49.66%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 42       | 29.17%  |
| Germany      | 21       | 14.58%  |
| Italy        | 7        | 4.86%   |
| UK           | 6        | 4.17%   |
| Spain        | 5        | 3.47%   |
| Canada       | 5        | 3.47%   |
| Brazil       | 5        | 3.47%   |
| Sweden       | 4        | 2.78%   |
| Belgium      | 4        | 2.78%   |
| Australia    | 4        | 2.78%   |
| Russia       | 3        | 2.08%   |
| Romania      | 3        | 2.08%   |
| Netherlands  | 3        | 2.08%   |
| India        | 3        | 2.08%   |
| Slovakia     | 2        | 1.39%   |
| Puerto Rico  | 2        | 1.39%   |
| Norway       | 2        | 1.39%   |
| Latvia       | 2        | 1.39%   |
| Greece       | 2        | 1.39%   |
| France       | 2        | 1.39%   |
| Denmark      | 2        | 1.39%   |
| Venezuela    | 1        | 0.69%   |
| Ukraine      | 1        | 0.69%   |
| South Africa | 1        | 0.69%   |
| Serbia       | 1        | 0.69%   |
| Poland       | 1        | 0.69%   |
| Philippines  | 1        | 0.69%   |
| Israel       | 1        | 0.69%   |
| Iceland      | 1        | 0.69%   |
| Hungary      | 1        | 0.69%   |
| Finland      | 1        | 0.69%   |
| Czechia      | 1        | 0.69%   |
| Chile        | 1        | 0.69%   |
| Bangladesh   | 1        | 0.69%   |
| Austria      | 1        | 0.69%   |
| Argentina    | 1        | 0.69%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| Milan                   | 3        | 1.99%   |
| Dallas                  | 3        | 1.99%   |
| Wasmes                  | 2        | 1.32%   |
| Sydney                  | 2        | 1.32%   |
| St Louis                | 2        | 1.32%   |
| Sao Paulo               | 2        | 1.32%   |
| Riga                    | 2        | 1.32%   |
| Oklahoma City           | 2        | 1.32%   |
| Melbourne               | 2        | 1.32%   |
| Mannheim                | 2        | 1.32%   |
| Kingsport               | 2        | 1.32%   |
| Berlin                  | 2        | 1.32%   |
| Algeciras               | 2        | 1.32%   |
| Zwickau                 | 1        | 0.66%   |
| York                    | 1        | 0.66%   |
| Weiterstadt             | 1        | 0.66%   |
| Weilen unter den Rinnen | 1        | 0.66%   |
| Voronezh                | 1        | 0.66%   |
| Volzhskiy               | 1        | 0.66%   |
| Västerås              | 1        | 0.66%   |
| Valence                 | 1        | 0.66%   |
| Urbandale               | 1        | 0.66%   |
| Ullerslev               | 1        | 0.66%   |
| Trecastelli             | 1        | 0.66%   |
| Timișoara              | 1        | 0.66%   |
| Taunusstein             | 1        | 0.66%   |
| Tampere                 | 1        | 0.66%   |
| Stockholm               | 1        | 0.66%   |
| Steyr                   | 1        | 0.66%   |
| Stavropol               | 1        | 0.66%   |
| Stanley                 | 1        | 0.66%   |
| Sindelfingen            | 1        | 0.66%   |
| Shreveport              | 1        | 0.66%   |
| Sherwood Park           | 1        | 0.66%   |
| Satu Mare               | 1        | 0.66%   |
| Sarasota                | 1        | 0.66%   |
| Santa Cruz de Tenerife  | 1        | 0.66%   |
| Sandviken               | 1        | 0.66%   |
| San Juan                | 1        | 0.66%   |
| San Jose                | 1        | 0.66%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 68       | 104    | 18.28%  |
| Seagate                     | 61       | 87     | 16.4%   |
| Samsung Electronics         | 61       | 112    | 16.4%   |
| Toshiba                     | 24       | 32     | 6.45%   |
| Crucial                     | 19       | 26     | 5.11%   |
| Kingston                    | 17       | 26     | 4.57%   |
| Sandisk                     | 16       | 24     | 4.3%    |
| Hitachi                     | 9        | 9      | 2.42%   |
| Silicon Motion              | 7        | 7      | 1.88%   |
| Phison                      | 7        | 8      | 1.88%   |
| Intel                       | 6        | 9      | 1.61%   |
| Micron/Crucial Technology   | 5        | 8      | 1.34%   |
| A-DATA Technology           | 5        | 8      | 1.34%   |
| Unknown                     | 4        | 4      | 1.08%   |
| PNY                         | 4        | 4      | 1.08%   |
| OCZ                         | 4        | 4      | 1.08%   |
| China                       | 4        | 6      | 1.08%   |
| XPG                         | 3        | 4      | 0.81%   |
| SPCC                        | 3        | 3      | 0.81%   |
| HGST                        | 3        | 9      | 0.81%   |
| Emtec                       | 3        | 5      | 0.81%   |
| Transcend                   | 2        | 2      | 0.54%   |
| TO Exter                    | 2        | 2      | 0.54%   |
| Team                        | 2        | 3      | 0.54%   |
| LITEONIT                    | 2        | 2      | 0.54%   |
| Kingston Technology Company | 2        | 2      | 0.54%   |
| Intenso                     | 2        | 3      | 0.54%   |
| Hewlett-Packard             | 2        | 2      | 0.54%   |
| WD MediaMax                 | 1        | 1      | 0.27%   |
| USB30                       | 1        | 2      | 0.27%   |
| T-FORCE                     | 1        | 1      | 0.27%   |
| SK hynix                    | 1        | 1      | 0.27%   |
| Realtek Semiconductor       | 1        | 1      | 0.27%   |
| Qumo                        | 1        | 1      | 0.27%   |
| Plextor                     | 1        | 1      | 0.27%   |
| Patriot                     | 1        | 1      | 0.27%   |
| Mushkin                     | 1        | 1      | 0.27%   |
| Micron Technology           | 1        | 1      | 0.27%   |
| MAXIO Technology (Hangzhou) | 1        | 1      | 0.27%   |
| LITEON                      | 1        | 1      | 0.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Samsung SSD 850 EVO 250GB                            | 8        | 1.78%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB  | 7        | 1.56%   |
| Samsung NVMe SSD Drive 1TB                           | 6        | 1.34%   |
| Seagate ST2000DM008-2FR102 2TB                       | 5        | 1.11%   |
| Samsung SSD 970 EVO Plus 500GB                       | 5        | 1.11%   |
| Samsung SSD 860 EVO 500GB                            | 5        | 1.11%   |
| Crucial CT1000MX500SSD1 1TB                          | 5        | 1.11%   |
| Seagate ST1000DM010-2EP102 1TB                       | 4        | 0.89%   |
| Samsung NVMe SSD Drive 500GB                         | 4        | 0.89%   |
| WDC WD20EZRZ-00Z5HB0 2TB                             | 3        | 0.67%   |
| WDC WD10EZEX-60WN4A0 1TB                             | 3        | 0.67%   |
| WDC WD10EZEX-08WN4A0 1TB                             | 3        | 0.67%   |
| WDC WD10EALX-009BA0 1TB                              | 3        | 0.67%   |
| Toshiba HDWD110 1TB                                  | 3        | 0.67%   |
| Toshiba DT01ACA100 1TB                               | 3        | 0.67%   |
| Toshiba DT01ACA050 500GB                             | 3        | 0.67%   |
| Seagate ST4000DM004-2CV104 4TB                       | 3        | 0.67%   |
| Seagate ST3320820AS 320GB                            | 3        | 0.67%   |
| Seagate ST3000DM001-1ER166 3TB                       | 3        | 0.67%   |
| Seagate ST2000DL003-9VT166 2TB                       | 3        | 0.67%   |
| Seagate Portable 4TB                                 | 3        | 0.67%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                   | 3        | 0.67%   |
| SanDisk SSD PLUS 1000GB                              | 3        | 0.67%   |
| SanDisk NVMe SSD Drive 1TB                           | 3        | 0.67%   |
| Samsung SSD 860 EVO 250GB                            | 3        | 0.67%   |
| Samsung SSD 860 EVO 1TB                              | 3        | 0.67%   |
| Samsung SSD 850 EVO 500GB                            | 3        | 0.67%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 960GB | 3        | 0.67%   |
| XPG NVMe SSD Drive 512GB                             | 2        | 0.45%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                     | 2        | 0.45%   |
| WDC WDS240G1G0A-00SS50 240GB SSD                     | 2        | 0.45%   |
| WDC WDS100T2B0C-00PXH0 1TB                           | 2        | 0.45%   |
| WDC WD60EZAZ-00SF3B0 6TB                             | 2        | 0.45%   |
| WDC WD20EARX-00PASB0 2TB                             | 2        | 0.45%   |
| WDC WD10EARS-00Y5B1 1TB                              | 2        | 0.45%   |
| WDC WD10EADS-00M2B0 1TB                              | 2        | 0.45%   |
| Unknown SD/MMC/MS PRO 16GB                           | 2        | 0.45%   |
| Toshiba TR150 480GB SSD                              | 2        | 0.45%   |
| Toshiba DT01ACA300 3TB                               | 2        | 0.45%   |
| TO Exter nal USB 3.0 240GB                           | 2        | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 59       | 84     | 37.34%  |
| WDC                 | 57       | 90     | 36.08%  |
| Toshiba             | 20       | 24     | 12.66%  |
| Hitachi             | 9        | 9      | 5.7%    |
| Samsung Electronics | 4        | 4      | 2.53%   |
| HGST                | 3        | 9      | 1.9%    |
| Unknown             | 2        | 2      | 1.27%   |
| Intenso             | 2        | 3      | 1.27%   |
| Hewlett-Packard     | 1        | 1      | 0.63%   |
| ASMedia             | 1        | 2      | 0.63%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 31       | 51     | 25.2%   |
| Crucial             | 15       | 20     | 12.2%   |
| Kingston            | 13       | 19     | 10.57%  |
| SanDisk             | 9        | 14     | 7.32%   |
| WDC                 | 8        | 8      | 6.5%    |
| A-DATA Technology   | 5        | 8      | 4.07%   |
| Toshiba             | 4        | 7      | 3.25%   |
| OCZ                 | 4        | 4      | 3.25%   |
| China               | 4        | 6      | 3.25%   |
| SPCC                | 3        | 3      | 2.44%   |
| PNY                 | 3        | 3      | 2.44%   |
| Emtec               | 3        | 5      | 2.44%   |
| Transcend           | 2        | 2      | 1.63%   |
| TO Exter            | 2        | 2      | 1.63%   |
| Team                | 2        | 3      | 1.63%   |
| LITEONIT            | 2        | 2      | 1.63%   |
| USB30               | 1        | 2      | 0.81%   |
| Unknown             | 1        | 1      | 0.81%   |
| T-FORCE             | 1        | 1      | 0.81%   |
| SK hynix            | 1        | 1      | 0.81%   |
| Qumo                | 1        | 1      | 0.81%   |
| Plextor             | 1        | 1      | 0.81%   |
| Mushkin             | 1        | 1      | 0.81%   |
| Micron Technology   | 1        | 1      | 0.81%   |
| LITEON              | 1        | 1      | 0.81%   |
| Inateck             | 1        | 1      | 0.81%   |
| HS-SSD-C100         | 1        | 1      | 0.81%   |
| Fanxiang            | 1        | 1      | 0.81%   |
| ADATA SU            | 1        | 1      | 0.81%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 111      | 228    | 38.68%  |
| SSD     | 87       | 171    | 30.31%  |
| NVMe    | 79       | 138    | 27.53%  |
| Unknown | 10       | 10     | 3.48%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 130      | 370    | 56.03%  |
| NVMe | 79       | 138    | 34.05%  |
| SAS  | 23       | 39     | 9.91%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 92       | 187    | 37.4%   |
| 0.51-1.0   | 74       | 106    | 30.08%  |
| 1.01-2.0   | 44       | 57     | 17.89%  |
| 3.01-4.0   | 12       | 15     | 4.88%   |
| 2.01-3.0   | 12       | 19     | 4.88%   |
| 4.01-10.0  | 10       | 12     | 4.07%   |
| 10.01-20.0 | 2        | 3      | 0.81%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 73       | 50%     |
| 1001-2000      | 25       | 17.12%  |
| 2001-3000      | 21       | 14.38%  |
| 501-1000       | 15       | 10.27%  |
| 251-500        | 8        | 5.48%   |
| Unknown        | 2        | 1.37%   |
| 101-250        | 1        | 0.68%   |
| 1-20           | 1        | 0.68%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 25       | 16.56%  |
| 251-500        | 24       | 15.89%  |
| 101-250        | 24       | 15.89%  |
| More than 3000 | 22       | 14.57%  |
| 1001-2000      | 21       | 13.91%  |
| 2001-3000      | 18       | 11.92%  |
| 51-100         | 10       | 6.62%   |
| 21-50          | 3        | 1.99%   |
| 1-20           | 2        | 1.32%   |
| Unknown        | 2        | 1.32%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC WD6400AAKS-65A7B0 640GB        | 1        | 1      | 3.33%   |
| WDC WD5000AAKX-60U6AA0 500GB       | 1        | 1      | 3.33%   |
| WDC WD5000AAKS-00E4A0 500GB        | 1        | 1      | 3.33%   |
| WDC WD30EZRX-00DC0B0 3TB           | 1        | 1      | 3.33%   |
| WDC WD20EARX-00PASB0 2TB           | 1        | 1      | 3.33%   |
| WDC WD20EARS-00MVWB0 2TB           | 1        | 1      | 3.33%   |
| WDC WD10EZRX-00L4HB0 1TB           | 1        | 1      | 3.33%   |
| WDC WD10EZEX-60ZF5A0 1TB           | 1        | 1      | 3.33%   |
| WDC WD10EARS-00Y5B1 1TB            | 1        | 1      | 3.33%   |
| WDC WD10EALX-009BA0 1TB            | 1        | 1      | 3.33%   |
| WDC WD10EADS-22M2B0 1TB            | 1        | 1      | 3.33%   |
| WDC WD10EADS-00M2B0 1TB            | 1        | 1      | 3.33%   |
| Toshiba DT01ACA050 500GB           | 1        | 1      | 3.33%   |
| Seagate ST9250827AS 250GB          | 1        | 1      | 3.33%   |
| Seagate ST4000DM004-2CV104 4TB     | 1        | 1      | 3.33%   |
| Seagate ST3000DM003-1F216N 3TB     | 1        | 1      | 3.33%   |
| Seagate ST2000LM003 HN-M201RAD 2TB | 1        | 1      | 3.33%   |
| Seagate ST2000DL003-9VT166 2TB     | 1        | 1      | 3.33%   |
| SanDisk SD6SF1M128G1022I 128GB SSD | 1        | 1      | 3.33%   |
| OCZ TRION100 480GB SSD             | 1        | 1      | 3.33%   |
| Kingston SV300S37A120G 120GB SSD   | 1        | 1      | 3.33%   |
| Kingston SH103S3240G 240GB SSD     | 1        | 1      | 3.33%   |
| Intenso USB 3.0 device 2TB         | 1        | 1      | 3.33%   |
| Hitachi HTS543216L9A300 160GB      | 1        | 1      | 3.33%   |
| Hitachi HDT721032SLA360 320GB      | 1        | 1      | 3.33%   |
| HGST HTS725050A7E635 OPAL 500GB    | 1        | 3      | 3.33%   |
| HGST HTS725050A7E630 500GB         | 1        | 4      | 3.33%   |
| Hewlett-Packard SSD EX900 500GB    | 1        | 1      | 3.33%   |
| Crucial CT960M500SSD1 960GB        | 1        | 1      | 3.33%   |
| A-DATA Technology SU800 1TB SSD    | 1        | 1      | 3.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Desktops | Drives | Percent |
|-------------------|----------|--------|---------|
| WDC               | 10       | 12     | 37.04%  |
| Seagate           | 5        | 5      | 18.52%  |
| Kingston          | 2        | 2      | 7.41%   |
| Hitachi           | 2        | 2      | 7.41%   |
| Toshiba           | 1        | 1      | 3.7%    |
| SanDisk           | 1        | 1      | 3.7%    |
| OCZ               | 1        | 1      | 3.7%    |
| Intenso           | 1        | 1      | 3.7%    |
| HGST              | 1        | 7      | 3.7%    |
| Hewlett-Packard   | 1        | 1      | 3.7%    |
| Crucial           | 1        | 1      | 3.7%    |
| A-DATA Technology | 1        | 1      | 3.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 10       | 12     | 50%     |
| Seagate | 5        | 5      | 25%     |
| Hitachi | 2        | 2      | 10%     |
| Toshiba | 1        | 1      | 5%      |
| Intenso | 1        | 1      | 5%      |
| HGST    | 1        | 7      | 5%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 17       | 28     | 70.83%  |
| SSD  | 6        | 6      | 25%     |
| NVMe | 1        | 1      | 4.17%   |

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
| Detected | 87       | 298    | 48.07%  |
| Works    | 71       | 214    | 39.23%  |
| Malfunc  | 23       | 35     | 12.71%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| AMD                          | 75       | 30.49%  |
| Intel                        | 70       | 28.46%  |
| Samsung Electronics          | 36       | 14.63%  |
| SanDisk                      | 12       | 4.88%   |
| Silicon Motion               | 8        | 3.25%   |
| Phison Electronics           | 8        | 3.25%   |
| Micron/Crucial Technology    | 7        | 2.85%   |
| Kingston Technology Company  | 7        | 2.85%   |
| ASMedia Technology           | 7        | 2.85%   |
| Marvell Technology Group     | 5        | 2.03%   |
| ADATA Technology             | 3        | 1.22%   |
| Realtek Semiconductor        | 2        | 0.81%   |
| JMicron Technology           | 2        | 0.81%   |
| Union Memory (Shenzhen)      | 1        | 0.41%   |
| Toshiba America Info Systems | 1        | 0.41%   |
| Shenzhen Longsys Electronics | 1        | 0.41%   |
| MAXIO Technology (Hangzhou)  | 1        | 0.41%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 45       | 14.9%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 29       | 9.6%    |
| AMD 400 Series Chipset SATA Controller                                                  | 18       | 5.96%   |
| AMD 500 Series Chipset SATA Controller                                                  | 16       | 5.3%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 13       | 4.3%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 8        | 2.65%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 7        | 2.32%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 6        | 1.99%   |
| Phison E12 NVMe Controller                                                              | 6        | 1.99%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6        | 1.99%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 6        | 1.99%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 5        | 1.66%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 5        | 1.66%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 5        | 1.66%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5        | 1.66%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5        | 1.66%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5        | 1.66%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4        | 1.32%   |
| AMD FCH SATA Controller D                                                               | 4        | 1.32%   |
| AMD 300 Series Chipset SATA Controller                                                  | 4        | 1.32%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 3        | 0.99%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 3        | 0.99%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 3        | 0.99%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 3        | 0.99%   |
| Kingston Company Company Non-Volatile memory controller                                 | 3        | 0.99%   |
| Intel SSD 660P Series                                                                   | 3        | 0.99%   |
| Intel SATA Controller [RAID mode]                                                       | 3        | 0.99%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 0.99%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 0.99%   |
| AMD X399 Series Chipset SATA Controller                                                 | 3        | 0.99%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3        | 0.99%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 3        | 0.99%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2        | 0.66%   |
| Samsung NVMe SSD Controller 980                                                         | 2        | 0.66%   |
| Realtek Realtek Non-Volatile memory controller                                          | 2        | 0.66%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2        | 0.66%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 2        | 0.66%   |
| Micron/Crucial NVMe Controller                                                          | 2        | 0.66%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 2        | 0.66%   |
| Kingston Company A2000 NVMe SSD                                                         | 2        | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 130      | 56.03%  |
| NVMe | 80       | 34.48%  |
| IDE  | 13       | 5.6%    |
| RAID | 9        | 3.88%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 75       | 52.08%  |
| Intel  | 69       | 47.92%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 9 3900X 12-Core Processor         | 6        | 4.17%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 6        | 4.17%   |
| AMD Ryzen 5 3600 6-Core Processor           | 5        | 3.47%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 4        | 2.78%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 4        | 2.78%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 2.08%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 3        | 2.08%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 3        | 2.08%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 2        | 1.39%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 2        | 1.39%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2        | 1.39%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 1.39%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 2        | 1.39%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2        | 1.39%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 1.39%   |
| Intel 12th Gen Core i5-12600K               | 2        | 1.39%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 2        | 1.39%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 2        | 1.39%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 2        | 1.39%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 2        | 1.39%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 2        | 1.39%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 1.39%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 2        | 1.39%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 2        | 1.39%   |
| AMD FX-8350 Eight-Core Processor            | 2        | 1.39%   |
| Intel Xeon CPU W3550 @ 3.07GHz              | 1        | 0.69%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz          | 1        | 0.69%   |
| Intel Xeon CPU E5-1680 v2 @ 3.00GHz         | 1        | 0.69%   |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz         | 1        | 0.69%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 1        | 0.69%   |
| Intel Core i9-10900K CPU @ 3.70GHz          | 1        | 0.69%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1        | 0.69%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1        | 0.69%   |
| Intel Core i7-6850K CPU @ 3.60GHz           | 1        | 0.69%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 0.69%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 0.69%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1        | 0.69%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 0.69%   |
| Intel Core i7-3930K CPU @ 3.20GHz           | 1        | 0.69%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 1        | 0.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 24       | 16.67%  |
| AMD Ryzen 7             | 23       | 15.97%  |
| AMD Ryzen 5             | 21       | 14.58%  |
| Intel Core i7           | 18       | 12.5%   |
| Intel Core i3           | 14       | 9.72%   |
| AMD Ryzen 9             | 11       | 7.64%   |
| AMD Ryzen 3             | 5        | 3.47%   |
| Other                   | 4        | 2.78%   |
| Intel Xeon              | 4        | 2.78%   |
| AMD FX                  | 4        | 2.78%   |
| AMD Ryzen Threadripper  | 3        | 2.08%   |
| Intel Celeron           | 2        | 1.39%   |
| AMD A10                 | 2        | 1.39%   |
| Intel Pentium Dual-Core | 1        | 0.69%   |
| Intel Core i9           | 1        | 0.69%   |
| Intel Core 2 Quad       | 1        | 0.69%   |
| AMD Phenom II X6        | 1        | 0.69%   |
| AMD Phenom II X4        | 1        | 0.69%   |
| AMD Phenom II X2        | 1        | 0.69%   |
| AMD Athlon X4           | 1        | 0.69%   |
| AMD Athlon              | 1        | 0.69%   |
| AMD A8                  | 1        | 0.69%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 48       | 33.33%  |
| 6      | 29       | 20.14%  |
| 8      | 28       | 19.44%  |
| 2      | 21       | 14.58%  |
| 12     | 9        | 6.25%   |
| 16     | 4        | 2.78%   |
| 10     | 3        | 2.08%   |
| 24     | 1        | 0.69%   |
| 3      | 1        | 0.69%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 144      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 109      | 75.69%  |
| 1      | 35       | 24.31%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 144      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 74       | 50.34%  |
| 0x08701021 | 9        | 6.12%   |
| 0x306c3    | 7        | 4.76%   |
| 0x0800820d | 6        | 4.08%   |
| 0x306a9    | 5        | 3.4%    |
| 0x206a7    | 4        | 2.72%   |
| 0x906ea    | 3        | 2.04%   |
| 0x0a50000c | 3        | 2.04%   |
| 0xa0653    | 2        | 1.36%   |
| 0x906ed    | 2        | 1.36%   |
| 0x90672    | 2        | 1.36%   |
| 0x506e3    | 2        | 1.36%   |
| 0x0a201204 | 2        | 1.36%   |
| 0x0a201009 | 2        | 1.36%   |
| 0x08108109 | 2        | 1.36%   |
| 0x0810100b | 2        | 1.36%   |
| 0x08001137 | 2        | 1.36%   |
| 0x06000852 | 2        | 1.36%   |
| 0xa0655    | 1        | 0.68%   |
| 0x906ec    | 1        | 0.68%   |
| 0x906eb    | 1        | 0.68%   |
| 0x906e9    | 1        | 0.68%   |
| 0x90675    | 1        | 0.68%   |
| 0x106a5    | 1        | 0.68%   |
| 0x1067a    | 1        | 0.68%   |
| 0x0a601201 | 1        | 0.68%   |
| 0x0a50000d | 1        | 0.68%   |
| 0x0a20120a | 1        | 0.68%   |
| 0x0a201016 | 1        | 0.68%   |
| 0x08701013 | 1        | 0.68%   |
| 0x08101016 | 1        | 0.68%   |
| 0x06003106 | 1        | 0.68%   |
| 0x010000dc | 1        | 0.68%   |
| 0x00000000 | 1        | 0.68%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 21       | 14.58%  |
| Zen 3            | 18       | 12.5%   |
| Zen+             | 16       | 11.11%  |
| KabyLake         | 16       | 11.11%  |
| Haswell          | 14       | 9.72%   |
| IvyBridge        | 11       | 7.64%   |
| SandyBridge      | 9        | 6.25%   |
| Zen              | 8        | 5.56%   |
| CometLake        | 7        | 4.86%   |
| Piledriver       | 5        | 3.47%   |
| Steamroller      | 3        | 2.08%   |
| Skylake          | 3        | 2.08%   |
| K10              | 3        | 2.08%   |
| Alderlake Hybrid | 3        | 2.08%   |
| Penryn           | 2        | 1.39%   |
| Unknown          | 2        | 1.39%   |
| Westmere         | 1        | 0.69%   |
| Nehalem          | 1        | 0.69%   |
| Broadwell        | 1        | 0.69%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 69       | 42.59%  |
| Nvidia | 63       | 38.89%  |
| Intel  | 30       | 18.52%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 14       | 8.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 9        | 5.39%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 8        | 4.79%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 7        | 4.19%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 6        | 3.59%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 5        | 2.99%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 5        | 2.99%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 4        | 2.4%    |
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 2.4%    |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 4        | 2.4%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 4        | 2.4%    |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 3        | 1.8%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 3        | 1.8%    |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 1.8%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 1.8%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3        | 1.8%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 1.2%    |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 2        | 1.2%    |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 1.2%    |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 1.2%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 1.2%    |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2        | 1.2%    |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 2        | 1.2%    |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 1.2%    |
| Nvidia GM204 [GeForce GTX 980]                                              | 2        | 1.2%    |
| Nvidia GK106 [GeForce GTX 660]                                              | 2        | 1.2%    |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 2        | 1.2%    |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 2        | 1.2%    |
| Intel HD Graphics 630                                                       | 2        | 1.2%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 1.2%    |
| AMD Tahiti PRO [Radeon HD 7950/8950 OEM / R9 280]                           | 2        | 1.2%    |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                            | 2        | 1.2%    |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 2        | 1.2%    |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 0.6%    |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 0.6%    |
| Nvidia TU106 [GeForce RTX 2060 12GB]                                        | 1        | 0.6%    |
| Nvidia TU104 [GeForce RTX 2080]                                             | 1        | 0.6%    |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 0.6%    |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 0.6%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 61       | 41.5%   |
| 1 x Nvidia     | 54       | 36.73%  |
| 1 x Intel      | 18       | 12.24%  |
| AMD + Nvidia   | 5        | 3.4%    |
| 2 x AMD        | 3        | 2.04%   |
| 2 x Nvidia     | 2        | 1.36%   |
| Intel + Nvidia | 2        | 1.36%   |
| Intel + AMD    | 2        | 1.36%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 91       | 62.33%  |
| Proprietary | 54       | 36.99%  |
| Unknown     | 1        | 0.68%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 57       | 38.51%  |
| 7.01-8.0   | 25       | 16.89%  |
| 3.01-4.0   | 17       | 11.49%  |
| 1.01-2.0   | 15       | 10.14%  |
| 8.01-16.0  | 12       | 8.11%   |
| 5.01-6.0   | 7        | 4.73%   |
| 0.51-1.0   | 7        | 4.73%   |
| 0.01-0.5   | 5        | 3.38%   |
| 2.01-3.0   | 2        | 1.35%   |
| 16.01-24.0 | 1        | 0.68%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 30       | 15.63%  |
| Goldstar             | 19       | 9.9%    |
| Acer                 | 19       | 9.9%    |
| Dell                 | 18       | 9.38%   |
| AOC                  | 13       | 6.77%   |
| Hewlett-Packard      | 12       | 6.25%   |
| BenQ                 | 10       | 5.21%   |
| Ancor Communications | 10       | 5.21%   |
| Unknown              | 6        | 3.13%   |
| ASUSTek Computer     | 6        | 3.13%   |
| Philips              | 4        | 2.08%   |
| MSI                  | 4        | 2.08%   |
| Iiyama               | 4        | 2.08%   |
| Gigabyte Technology  | 4        | 2.08%   |
| ViewSonic            | 3        | 1.56%   |
| Vizio                | 2        | 1.04%   |
| Toshiba              | 2        | 1.04%   |
| Sony                 | 2        | 1.04%   |
| NEC Computers        | 2        | 1.04%   |
| Mi                   | 2        | 1.04%   |
| LG Electronics       | 2        | 1.04%   |
| Xiaomi               | 1        | 0.52%   |
| Vestel               | 1        | 0.52%   |
| RTK                  | 1        | 0.52%   |
| ONN                  | 1        | 0.52%   |
| MiTAC                | 1        | 0.52%   |
| Microstep            | 1        | 0.52%   |
| LTM                  | 1        | 0.52%   |
| Lenovo Group Limited | 1        | 0.52%   |
| Lenovo               | 1        | 0.52%   |
| Insignia             | 1        | 0.52%   |
| Idek Iiyama          | 1        | 0.52%   |
| HPN                  | 1        | 0.52%   |
| HKC                  | 1        | 0.52%   |
| Fujitsu Siemens      | 1        | 0.52%   |
| Element              | 1        | 0.52%   |
| AOpen                | 1        | 0.52%   |
| Alba                 | 1        | 0.52%   |
| Unknown              | 1        | 0.52%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 3        | 1.44%   |
| Samsung Electronics S34J55x SAM0F72 3440x1440 797x333mm 34.0-inch      | 2        | 0.96%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch               | 2        | 0.96%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch               | 2        | 0.96%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                    | 2        | 0.96%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 2        | 0.96%   |
| Dell 1909W DELA03C 1440x900 408x255mm 18.9-inch                        | 2        | 0.96%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                     | 2        | 0.96%   |
| Ancor Communications ASUS PB287Q ACI28A3 3840x2160 621x341mm 27.9-inch | 2        | 0.96%   |
| Acer X223W ACR0009 1680x1050 473x296mm 22.0-inch                       | 2        | 0.96%   |
| Xiaomi Woieyeks-4K XMD009A 2880x1800 480x270mm 21.7-inch               | 1        | 0.48%   |
| Vizio P502ui-B1E VIZ1013 3840x2160 1095x616mm 49.5-inch                | 1        | 0.48%   |
| Vizio E320-A1 VIZ0095 1360x768 697x392mm 31.5-inch                     | 1        | 0.48%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch             | 1        | 0.48%   |
| ViewSonic VX3258 series VSCDE35 2560x1440 700x390mm 31.5-inch          | 1        | 0.48%   |
| ViewSonic VX2270 SERIES VSCE02C 1920x1080 476x267mm 21.5-inch          | 1        | 0.48%   |
| Vestel LCD Monitor 24W_LCD_TV 1920x1080                                | 1        | 0.48%   |
| Unknown LCD Monitor XXX AAA 1366x768                                   | 1        | 0.48%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                  | 1        | 0.48%   |
| Unknown LCD Monitor SAMSUNG                                            | 1        | 0.48%   |
| Unknown LCD Monitor RJT HDMI                                           | 1        | 0.48%   |
| Unknown LCD Monitor LHC 32-QHD-144-C 4480x1440                         | 1        | 0.48%   |
| Unknown LCD Monitor Hitachi/HINT W240D DVI                             | 1        | 0.48%   |
| Toshiba TV TSB0206 1920x1080 886x498mm 40.0-inch                       | 1        | 0.48%   |
| Toshiba TV TSB0105 1920x1080 708x398mm 32.0-inch                       | 1        | 0.48%   |
| Sony TV SNY1802 1920x1080                                              | 1        | 0.48%   |
| Sony TV SNY0801 1360x768                                               | 1        | 0.48%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch      | 1        | 0.48%   |
| Samsung Electronics U28E850 SAM0CCB 3840x2160 607x345mm 27.5-inch      | 1        | 0.48%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch      | 1        | 0.48%   |
| Samsung Electronics T24E390 SAM0C20 1920x1080 521x293mm 23.5-inch      | 1        | 0.48%   |
| Samsung Electronics SyncMaster SAM05B0 1920x1080                       | 1        | 0.48%   |
| Samsung Electronics SyncMaster SAM04D5 1920x1080                       | 1        | 0.48%   |
| Samsung Electronics SyncMaster SAM00BB 1280x1024 376x301mm 19.0-inch   | 1        | 0.48%   |
| Samsung Electronics SMS24A350H SAM07D6 1920x1080 531x299mm 24.0-inch   | 1        | 0.48%   |
| Samsung Electronics S24R35xFZ SAM71A8 1920x1080 527x296mm 23.8-inch    | 1        | 0.48%   |
| Samsung Electronics S24E450 SAM0CA0 1920x1080 531x299mm 24.0-inch      | 1        | 0.48%   |
| Samsung Electronics S24D300 SAM0B45 1920x1080 521x293mm 23.5-inch      | 1        | 0.48%   |
| Samsung Electronics S24D300 SAM0B42 1920x1080 531x299mm 24.0-inch      | 1        | 0.48%   |
| Samsung Electronics LU28R55 SAM1016 3840x2160 632x360mm 28.6-inch      | 1        | 0.48%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 84       | 45.9%   |
| 3840x2160 (4K)     | 22       | 12.02%  |
| 2560x1440 (QHD)    | 14       | 7.65%   |
| Unknown            | 9        | 4.92%   |
| 3440x1440          | 8        | 4.37%   |
| 2560x1080          | 6        | 3.28%   |
| 1680x1050 (WSXGA+) | 6        | 3.28%   |
| 1366x768 (WXGA)    | 6        | 3.28%   |
| 3840x1080          | 5        | 2.73%   |
| 1280x1024 (SXGA)   | 5        | 2.73%   |
| 1920x1200 (WUXGA)  | 3        | 1.64%   |
| 1600x900 (HD+)     | 3        | 1.64%   |
| 1440x900 (WXGA+)   | 3        | 1.64%   |
| 7680x2160          | 2        | 1.09%   |
| 1360x768           | 2        | 1.09%   |
| 9600x2160          | 1        | 0.55%   |
| 4480x1440          | 1        | 0.55%   |
| 3840x1200          | 1        | 0.55%   |
| 2048x1152          | 1        | 0.55%   |
| 1920x540           | 1        | 0.55%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 35       | 19.02%  |
| 24      | 29       | 15.76%  |
| Unknown | 28       | 15.22%  |
| 23      | 20       | 10.87%  |
| 31      | 11       | 5.98%   |
| 21      | 10       | 5.43%   |
| 34      | 9        | 4.89%   |
| 19      | 8        | 4.35%   |
| 22      | 7        | 3.8%    |
| 72      | 4        | 2.17%   |
| 49      | 3        | 1.63%   |
| 20      | 3        | 1.63%   |
| 40      | 2        | 1.09%   |
| 28      | 2        | 1.09%   |
| 25      | 2        | 1.09%   |
| 18      | 2        | 1.09%   |
| 74      | 1        | 0.54%   |
| 58      | 1        | 0.54%   |
| 54      | 1        | 0.54%   |
| 48      | 1        | 0.54%   |
| 46      | 1        | 0.54%   |
| 33      | 1        | 0.54%   |
| 32      | 1        | 0.54%   |
| 26      | 1        | 0.54%   |
| 17      | 1        | 0.54%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 72       | 41.62%  |
| Unknown     | 28       | 16.18%  |
| 401-500     | 25       | 14.45%  |
| 601-700     | 18       | 10.4%   |
| 701-800     | 11       | 6.36%   |
| 1001-1500   | 7        | 4.05%   |
| 1501-2000   | 5        | 2.89%   |
| 351-400     | 4        | 2.31%   |
| 801-900     | 2        | 1.16%   |
| 301-350     | 1        | 0.58%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 101      | 62.35%  |
| Unknown | 26       | 16.05%  |
| 16/10   | 17       | 10.49%  |
| 21/9    | 10       | 6.17%   |
| 5/4     | 5        | 3.09%   |
| 32/9    | 3        | 1.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 50       | 28.41%  |
| 301-350        | 36       | 20.45%  |
| Unknown        | 28       | 15.91%  |
| 351-500        | 23       | 13.07%  |
| 151-200        | 12       | 6.82%   |
| 251-300        | 10       | 5.68%   |
| More than 1000 | 9        | 5.11%   |
| 501-1000       | 5        | 2.84%   |
| 141-150        | 3        | 1.7%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 88       | 54.66%  |
| Unknown | 28       | 17.39%  |
| 101-120 | 24       | 14.91%  |
| 121-160 | 9        | 5.59%   |
| 1-50    | 8        | 4.97%   |
| 161-240 | 4        | 2.48%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 88       | 59.86%  |
| 2     | 41       | 27.89%  |
| 3     | 14       | 9.52%   |
| 0     | 3        | 2.04%   |
| 4     | 1        | 0.68%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 99       | 44.59%  |
| Intel                 | 67       | 30.18%  |
| Qualcomm Atheros      | 11       | 4.95%   |
| Broadcom              | 5        | 2.25%   |
| Ralink Technology     | 4        | 1.8%    |
| NetGear               | 4        | 1.8%    |
| MediaTek              | 4        | 1.8%    |
| Linksys               | 4        | 1.8%    |
| TP-Link               | 3        | 1.35%   |
| Microsoft             | 3        | 1.35%   |
| Aquantia              | 3        | 1.35%   |
| Ralink                | 2        | 0.9%    |
| DisplayLink           | 2        | 0.9%    |
| Xiaomi                | 1        | 0.45%   |
| Sitecom Europe        | 1        | 0.45%   |
| Samsung Electronics   | 1        | 0.45%   |
| InterBiometrics       | 1        | 0.45%   |
| Holtek Semiconductor  | 1        | 0.45%   |
| D-Link                | 1        | 0.45%   |
| Belkin Components     | 1        | 0.45%   |
| AVM                   | 1        | 0.45%   |
| ASIX Electronics      | 1        | 0.45%   |
| Alteon Networks       | 1        | 0.45%   |
| Accton Technology     | 1        | 0.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 79       | 31.47%  |
| Intel I211 Gigabit Network Connection                               | 17       | 6.77%   |
| Realtek RTL8125 2.5GbE Controller                                   | 13       | 5.18%   |
| Intel Wi-Fi 6 AX200                                                 | 12       | 4.78%   |
| Intel Ethernet Controller I225-V                                    | 9        | 3.59%   |
| Intel Wireless-AC 9260                                              | 7        | 2.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 6        | 2.39%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 6        | 2.39%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 4        | 1.59%   |
| Intel Ethernet Connection I217-LM                                   | 4        | 1.59%   |
| Ralink RT2870/RT3070 Wireless Adapter                               | 3        | 1.2%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 3        | 1.2%    |
| Intel Ethernet Connection (2) I219-V                                | 3        | 1.2%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 3        | 1.2%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                     | 2        | 0.8%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 2        | 0.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 2        | 0.8%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 2        | 0.8%    |
| NetGear A6210                                                       | 2        | 0.8%    |
| Microsoft XBOX ACC                                                  | 2        | 0.8%    |
| Linksys AE6000 802.11a/b/g/n/ac Wireless Adapter [MediaTek MT7610U] | 2        | 0.8%    |
| Intel Wireless 7265                                                 | 2        | 0.8%    |
| Intel Ethernet Connection (7) I219-V                                | 2        | 0.8%    |
| Intel 82579V Gigabit Network Connection                             | 2        | 0.8%    |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 2        | 0.8%    |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 1        | 0.4%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                         | 1        | 0.4%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                        | 1        | 0.4%    |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                          | 1        | 0.4%    |
| Sitecom Europe WLA-5000 802.11abgn [Ralink RT3572]                  | 1        | 0.4%    |
| Samsung Galaxy series, misc. (tethering mode)                       | 1        | 0.4%    |
| Realtek USB 10/100/1G/2.5G LAN                                      | 1        | 0.4%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 1        | 0.4%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter            | 1        | 0.4%    |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                 | 1        | 0.4%    |
| Realtek RTL8191SU 802.11n WLAN Adapter                              | 1        | 0.4%    |
| Realtek RTL8188RU 802.11n WLAN Adapter                              | 1        | 0.4%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                 | 1        | 0.4%    |
| Realtek RTL8188EE Wireless Network Adapter                          | 1        | 0.4%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 1        | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 37       | 43.02%  |
| Realtek Semiconductor | 16       | 18.6%   |
| Ralink Technology     | 4        | 4.65%   |
| Qualcomm Atheros      | 4        | 4.65%   |
| NetGear               | 4        | 4.65%   |
| Linksys               | 4        | 4.65%   |
| TP-Link               | 3        | 3.49%   |
| Microsoft             | 3        | 3.49%   |
| Broadcom              | 3        | 3.49%   |
| Ralink                | 2        | 2.33%   |
| MediaTek              | 2        | 2.33%   |
| Sitecom Europe        | 1        | 1.16%   |
| D-Link                | 1        | 1.16%   |
| AVM                   | 1        | 1.16%   |
| Accton Technology     | 1        | 1.16%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                       | 12       | 13.95%  |
| Intel Wireless-AC 9260                                                    | 7        | 8.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 6        | 6.98%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                          | 6        | 6.98%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                    | 4        | 4.65%   |
| Ralink RT2870/RT3070 Wireless Adapter                                     | 3        | 3.49%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                           | 2        | 2.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                | 2        | 2.33%   |
| NetGear A6210                                                             | 2        | 2.33%   |
| Microsoft XBOX ACC                                                        | 2        | 2.33%   |
| Linksys AE6000 802.11a/b/g/n/ac Wireless Adapter [MediaTek MT7610U]       | 2        | 2.33%   |
| Intel Wireless 7265                                                       | 2        | 2.33%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                               | 1        | 1.16%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                              | 1        | 1.16%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                | 1        | 1.16%   |
| Sitecom Europe WLA-5000 802.11abgn [Ralink RT3572]                        | 1        | 1.16%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                        | 1        | 1.16%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                  | 1        | 1.16%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                       | 1        | 1.16%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                    | 1        | 1.16%   |
| Realtek RTL8188RU 802.11n WLAN Adapter                                    | 1        | 1.16%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                       | 1        | 1.16%   |
| Realtek RTL8188EE Wireless Network Adapter                                | 1        | 1.16%   |
| Realtek 802.11n WLAN Adapter                                              | 1        | 1.16%   |
| Ralink Wireless Adapter Canyon CN-WF511                                   | 1        | 1.16%   |
| Ralink MT7601U Wireless Adapter                                           | 1        | 1.16%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                    | 1        | 1.16%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                | 1        | 1.16%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                          | 1        | 1.16%   |
| NetGear WNDA3100v1 802.11abgn [Atheros AR9170+AR9104]                     | 1        | 1.16%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1        | 1.16%   |
| Microsoft Wireless XBox Controller Dongle                                 | 1        | 1.16%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter             | 1        | 1.16%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                   | 1        | 1.16%   |
| Linksys WUSB6300 V2                                                       | 1        | 1.16%   |
| Linksys WUSB54GC v1 802.11g Adapter [Ralink RT73]                         | 1        | 1.16%   |
| Intel WLAN controller                                                     | 1        | 1.16%   |
| Intel Wireless 3165                                                       | 1        | 1.16%   |
| Intel Tiger Lake PCH CNVi WiFi                                            | 1        | 1.16%   |
| Intel Comet Lake PCH CNVi WiFi                                            | 1        | 1.16%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 95       | 59.38%  |
| Intel                 | 43       | 26.88%  |
| Qualcomm Atheros      | 8        | 5%      |
| Aquantia              | 3        | 1.88%   |
| MediaTek              | 2        | 1.25%   |
| DisplayLink           | 2        | 1.25%   |
| Broadcom              | 2        | 1.25%   |
| Xiaomi                | 1        | 0.63%   |
| Samsung Electronics   | 1        | 0.63%   |
| Belkin Components     | 1        | 0.63%   |
| ASIX Electronics      | 1        | 0.63%   |
| Alteon Networks       | 1        | 0.63%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 79       | 48.47%  |
| Intel I211 Gigabit Network Connection                               | 17       | 10.43%  |
| Realtek RTL8125 2.5GbE Controller                                   | 13       | 7.98%   |
| Intel Ethernet Controller I225-V                                    | 9        | 5.52%   |
| Intel Ethernet Connection I217-LM                                   | 4        | 2.45%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 3        | 1.84%   |
| Intel Ethernet Connection (2) I219-V                                | 3        | 1.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 3        | 1.84%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 2        | 1.23%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 2        | 1.23%   |
| Intel Ethernet Connection (7) I219-V                                | 2        | 1.23%   |
| Intel 82579V Gigabit Network Connection                             | 2        | 1.23%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 2        | 1.23%   |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 1        | 0.61%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 1        | 0.61%   |
| Realtek USB 10/100/1G/2.5G LAN                                      | 1        | 0.61%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 1        | 0.61%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter               | 1        | 0.61%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                    | 1        | 0.61%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller           | 1        | 0.61%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                          | 1        | 0.61%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet      | 1        | 0.61%   |
| MediaTek moto e(6) plus                                             | 1        | 0.61%   |
| MediaTek Armor 8 Pro                                                | 1        | 0.61%   |
| Intel Ethernet Connection I217-V                                    | 1        | 0.61%   |
| Intel Ethernet Connection (2) I218-V                                | 1        | 0.61%   |
| Intel 82576 Gigabit Network Connection                              | 1        | 0.61%   |
| DisplayLink USB-C Triple-4K Dock                                    | 1        | 0.61%   |
| DisplayLink ThinkPad USB 3.0 Dock                                   | 1        | 0.61%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express             | 1        | 0.61%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                     | 1        | 0.61%   |
| Belkin Components F5D5050 100Mbps Ethernet                          | 1        | 0.61%   |
| ASIX AX88179 Gigabit Ethernet                                       | 1        | 0.61%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.61%   |
| Alteon Networks Ethernet controller                                 | 1        | 0.61%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 142      | 63.96%  |
| WiFi     | 78       | 35.14%  |
| Modem    | 1        | 0.45%   |
| Unknown  | 1        | 0.45%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 109      | 72.67%  |
| WiFi     | 41       | 27.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 81       | 55.86%  |
| 2     | 52       | 35.86%  |
| 3     | 9        | 6.21%   |
| 0     | 2        | 1.38%   |
| 4     | 1        | 0.69%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 113      | 78.47%  |
| Yes  | 31       | 21.53%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 32       | 43.84%  |
| Cambridge Silicon Radio         | 14       | 19.18%  |
| Realtek Semiconductor           | 11       | 15.07%  |
| ASUSTek Computer                | 5        | 6.85%   |
| Qualcomm Atheros Communications | 4        | 5.48%   |
| Broadcom                        | 3        | 4.11%   |
| MediaTek                        | 2        | 2.74%   |
| IMC Networks                    | 1        | 1.37%   |
| Dynex                           | 1        | 1.37%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 14       | 19.18%  |
| Intel AX200 Bluetooth                                    | 11       | 15.07%  |
| Realtek Bluetooth Radio                                  | 8        | 10.96%  |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 7        | 9.59%   |
| Intel Wireless-AC 3168 Bluetooth                         | 6        | 8.22%   |
| Realtek  Bluetooth 4.2 Adapter                           | 3        | 4.11%   |
| Qualcomm Atheros  Bluetooth Device                       | 3        | 4.11%   |
| MediaTek Wireless_Device                                 | 2        | 2.74%   |
| Intel Bluetooth wireless interface                       | 2        | 2.74%   |
| Intel AX210 Bluetooth                                    | 2        | 2.74%   |
| Intel AX201 Bluetooth                                    | 2        | 2.74%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 2        | 2.74%   |
| ASUS Bluetooth Radio                                     | 2        | 2.74%   |
| Qualcomm Atheros AR3011 Bluetooth                        | 1        | 1.37%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 1        | 1.37%   |
| Intel Bluetooth Device                                   | 1        | 1.37%   |
| IMC Networks Bluetooth Radio                             | 1        | 1.37%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1        | 1.37%   |
| Broadcom BCM43142A0 Bluetooth Device                     | 1        | 1.37%   |
| ASUS Qualcomm Bluetooth 4.1                              | 1        | 1.37%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 1        | 1.37%   |
| ASUS ASUS USB-BT500                                      | 1        | 1.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| AMD                      | 89       | 31.34%  |
| Intel                    | 69       | 24.3%   |
| Nvidia                   | 63       | 22.18%  |
| C-Media Electronics      | 11       | 3.87%   |
| Logitech                 | 7        | 2.46%   |
| Kingston Technology      | 5        | 1.76%   |
| Texas Instruments        | 4        | 1.41%   |
| Trust                    | 3        | 1.06%   |
| Blue Microphones         | 3        | 1.06%   |
| Yamaha                   | 2        | 0.7%    |
| Sony                     | 2        | 0.7%    |
| JMTek                    | 2        | 0.7%    |
| Generalplus Technology   | 2        | 0.7%    |
| DSEA A/S                 | 2        | 0.7%    |
| Creative Labs            | 2        | 0.7%    |
| Tenx Technology          | 1        | 0.35%   |
| SteelSeries ApS          | 1        | 0.35%   |
| Samson Technologies      | 1        | 0.35%   |
| RODE Microphones         | 1        | 0.35%   |
| ROCCAT                   | 1        | 0.35%   |
| Razer USA                | 1        | 0.35%   |
| Plantronics              | 1        | 0.35%   |
| Micro Star International | 1        | 0.35%   |
| Hewlett-Packard          | 1        | 0.35%   |
| Harman International     | 1        | 0.35%   |
| Focusrite-Novation       | 1        | 0.35%   |
| EVGA                     | 1        | 0.35%   |
| DigiTech                 | 1        | 0.35%   |
| Digidesign               | 1        | 0.35%   |
| Creative Technology      | 1        | 0.35%   |
| Audio-Technica           | 1        | 0.35%   |
| Arturia                  | 1        | 0.35%   |
| Alesis                   | 1        | 0.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 33       | 9.38%   |
| AMD Family 17h/19h HD Audio Controller                                     | 17       | 4.83%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 14       | 3.98%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 14       | 3.98%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 12       | 3.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 11       | 3.13%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 11       | 3.13%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11       | 3.13%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 9        | 2.56%   |
| Nvidia GP104 High Definition Audio Controller                              | 8        | 2.27%   |
| AMD Navi 10 HDMI Audio                                                     | 8        | 2.27%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7        | 1.99%   |
| Intel 200 Series PCH HD Audio                                              | 7        | 1.99%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 7        | 1.99%   |
| Intel Cannon Lake PCH cAVS                                                 | 6        | 1.7%    |
| C-Media Electronics USB Audio Device                                       | 6        | 1.7%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 6        | 1.7%    |
| Nvidia TU116 High Definition Audio Controller                              | 5        | 1.42%   |
| Nvidia TU104 HD Audio Controller                                           | 5        | 1.42%   |
| Nvidia GM204 High Definition Audio Controller                              | 5        | 1.42%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 5        | 1.42%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5        | 1.42%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 5        | 1.42%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 5        | 1.42%   |
| Texas Instruments PCM2902 Audio Codec                                      | 3        | 0.85%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3        | 0.85%   |
| Nvidia GP106 High Definition Audio Controller                              | 3        | 0.85%   |
| Nvidia GP102 HDMI Audio Controller                                         | 3        | 0.85%   |
| Nvidia GM206 High Definition Audio Controller                              | 3        | 0.85%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 0.85%   |
| Nvidia GK106 HDMI Audio Controller                                         | 3        | 0.85%   |
| Nvidia GA104 High Definition Audio Controller                              | 3        | 0.85%   |
| Nvidia GA102 High Definition Audio Controller                              | 3        | 0.85%   |
| Kingston Technology HyperX QuadCast                                        | 3        | 0.85%   |
| Intel Comet Lake PCH-V cAVS                                                | 3        | 0.85%   |
| Intel Comet Lake PCH cAVS                                                  | 3        | 0.85%   |
| Blue Microphones Yeti Stereo Microphone                                    | 3        | 0.85%   |
| AMD FCH Azalia Controller                                                  | 3        | 0.85%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3        | 0.85%   |
| Sony DualShock 4 [CUH-ZCT2x]                                               | 2        | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| G.Skill                      | 22       | 25.88%  |
| Corsair                      | 14       | 16.47%  |
| Samsung Electronics          | 7        | 8.24%   |
| Kingston                     | 7        | 8.24%   |
| Unknown                      | 6        | 7.06%   |
| SK hynix                     | 6        | 7.06%   |
| Patriot                      | 6        | 7.06%   |
| Crucial                      | 6        | 7.06%   |
| Team                         | 2        | 2.35%   |
| Patriot Memory (PDP Systems) | 2        | 2.35%   |
| Micron Technology            | 2        | 2.35%   |
| A-DATA Technology            | 2        | 2.35%   |
| Ramaxel Technology           | 1        | 1.18%   |
| Apacer                       | 1        | 1.18%   |
| Unknown                      | 1        | 1.18%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                    | Desktops | Percent |
|--------------------------------------------------------------------------|----------|---------|
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s                     | 6        | 6.32%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s                    | 4        | 4.21%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s                      | 3        | 3.16%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s                     | 2        | 2.11%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s                     | 2        | 2.11%   |
| Patriot RAM 2666 C16 Series 4GB DIMM DDR4 2800MT/s                       | 2        | 2.11%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s                    | 2        | 2.11%   |
| Corsair RAM CMK32GX4M4B3200C16 8GB DIMM DDR4 3600MT/s                    | 2        | 2.11%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4                             | 2        | 2.11%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s                    | 2        | 2.11%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                                | 1        | 1.05%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                                     | 1        | 1.05%   |
| Unknown RAM Module 8GB DIMM                                              | 1        | 1.05%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                                     | 1        | 1.05%   |
| Unknown RAM Module 4GB DIMM                                              | 1        | 1.05%   |
| Unknown RAM Module 1GB DIMM 1066MT/s                                     | 1        | 1.05%   |
| Unknown RAM 4400 C19 Series 8GB DIMM DDR4 2133MT/s                       | 1        | 1.05%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s                    | 1        | 1.05%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s                       | 1        | 1.05%   |
| Team RAM TEAMGROUP-UD4-3200 16384MB DIMM DDR4 3733MT/s                   | 1        | 1.05%   |
| SK hynix RAM HMT41GU6BFR8C-PB 8GB DIMM DDR3 1600MT/s                     | 1        | 1.05%   |
| SK hynix RAM HMAA2GU6CJR8N-XN 16GB DIMM DDR4 3200MT/s                    | 1        | 1.05%   |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s                                | 1        | 1.05%   |
| Samsung RAM Module 16GB DIMM DDR4 3200MT/s                               | 1        | 1.05%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s                    | 1        | 1.05%   |
| Samsung RAM M379B5273DH0-YK0 4GB DIMM DDR3 1600MT/s                      | 1        | 1.05%   |
| Samsung RAM M379B5273DH0-YK 4GB DIMM DDR3 1600MT/s                       | 1        | 1.05%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s                      | 1        | 1.05%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s                      | 1        | 1.05%   |
| Samsung RAM M378B1G73QH0-CK0 8GB DIMM DDR3 1600MT/s                      | 1        | 1.05%   |
| Samsung RAM M378B1G73EB0-CK0 8GB DIMM DDR3 1600MT/s                      | 1        | 1.05%   |
| Ramaxel RAM RMR5030MM58E8F1600 2GB DIMM DDR3 1600MT/s                    | 1        | 1.05%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s                           | 1        | 1.05%   |
| Patriot RAM Module 8GB DIMM DDR4 2666MT/s                                | 1        | 1.05%   |
| Patriot RAM 4000 C19 Series 8GB DIMM DDR4 4200MT/s                       | 1        | 1.05%   |
| Patriot RAM 2133 CL11 Series 4GB DIMM DDR3 2400MT/s                      | 1        | 1.05%   |
| Patriot RAM 1600 CL10 Series 8GB DIMM DDR3 1600MT/s                      | 1        | 1.05%   |
| Patriot Memory (PDP Systems) RAM 3600 C18 Series 16GB DIMM DDR4 3600MT/s | 1        | 1.05%   |
| Patriot Memory (PDP Systems) RAM 2666 C16 Series 4GB DIMM DDR4 2933MT/s  | 1        | 1.05%   |
| Micron RAM F6451U64F9333G 4GB DIMM DDR3 1333MT/s                         | 1        | 1.05%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 54       | 71.05%  |
| DDR3    | 17       | 22.37%  |
| Unknown | 4        | 5.26%   |
| DDR5    | 1        | 1.32%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 74       | 97.37%  |
| SODIMM | 2        | 2.63%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 45       | 51.72%  |
| 16384 | 20       | 22.99%  |
| 4096  | 15       | 17.24%  |
| 32768 | 5        | 5.75%   |
| 2048  | 1        | 1.15%   |
| 1024  | 1        | 1.15%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3600    | 16       | 18.6%   |
| 3200    | 9        | 10.47%  |
| 1600    | 9        | 10.47%  |
| 3466    | 6        | 6.98%   |
| 2400    | 6        | 6.98%   |
| 3666    | 4        | 4.65%   |
| 2666    | 4        | 4.65%   |
| 1333    | 4        | 4.65%   |
| 2667    | 3        | 3.49%   |
| 3866    | 2        | 2.33%   |
| 3800    | 2        | 2.33%   |
| 3000    | 2        | 2.33%   |
| 2933    | 2        | 2.33%   |
| 2800    | 2        | 2.33%   |
| 1800    | 2        | 2.33%   |
| 4800    | 1        | 1.16%   |
| 4266    | 1        | 1.16%   |
| 4200    | 1        | 1.16%   |
| 4000    | 1        | 1.16%   |
| 3733    | 1        | 1.16%   |
| 2200    | 1        | 1.16%   |
| 2133    | 1        | 1.16%   |
| 1867    | 1        | 1.16%   |
| 1866    | 1        | 1.16%   |
| 1200    | 1        | 1.16%   |
| 1066    | 1        | 1.16%   |
| 800     | 1        | 1.16%   |
| Unknown | 1        | 1.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 2        | 28.57%  |
| Dymo-CoStar         | 2        | 28.57%  |
| Samsung Electronics | 1        | 14.29%  |
| Fuji Xerox          | 1        | 14.29%  |
| Brother Industries  | 1        | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Dymo-CoStar LabelWriter 450      | 2        | 28.57%  |
| Samsung M267x 287x Series        | 1        | 14.29%  |
| HP OfficeJet Pro 8020 series     | 1        | 14.29%  |
| HP DeskJet Plus 4100 series      | 1        | 14.29%  |
| Fuji Xerox DocuPrint CM315/318 z | 1        | 14.29%  |
| Brother HL-5370DW series         | 1        | 14.29%  |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 17       | 51.52%  |
| Microsoft                     | 5        | 15.15%  |
| Sunplus Innovation Technology | 2        | 6.06%   |
| Jieli Technology              | 2        | 6.06%   |
| Generalplus Technology        | 2        | 6.06%   |
| Z-Star Microelectronics       | 1        | 3.03%   |
| Trust                         | 1        | 3.03%   |
| Realtek Semiconductor         | 1        | 3.03%   |
| Razer USA                     | 1        | 3.03%   |
| MacroSilicon                  | 1        | 3.03%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Logitech Webcam C270              | 3        | 9.09%   |
| Logitech BRIO Ultra HD Webcam     | 3        | 9.09%   |
| Sunplus FHD Camera                | 2        | 6.06%   |
| Microsoft LifeCam HD-5000         | 2        | 6.06%   |
| Logitech Webcam C930e             | 2        | 6.06%   |
| Logitech HD Webcam C910           | 2        | 6.06%   |
| Logitech HD Pro Webcam C920       | 2        | 6.06%   |
| Logitech C922 Pro Stream Webcam   | 2        | 6.06%   |
| Jieli USB PHY 2.0                 | 2        | 6.06%   |
| Z-Star A4 TECH USB2.0 PC Camera J | 1        | 3.03%   |
| Trust USB Camera                  | 1        | 3.03%   |
| Realtek FULL HD 1080P Webcam      | 1        | 3.03%   |
| Razer USA Razer Kiyo Pro          | 1        | 3.03%   |
| Microsoft Xbox NUI Camera         | 1        | 3.03%   |
| Microsoft LifeCam VX-2000         | 1        | 3.03%   |
| Microsoft LifeCam HD-3000         | 1        | 3.03%   |
| MacroSilicon USB Video            | 1        | 3.03%   |
| Logitech Webcam C925e             | 1        | 3.03%   |
| Logitech HD Webcam C510           | 1        | 3.03%   |
| Logitech C920 PRO HD Webcam       | 1        | 3.03%   |
| Generalplus WEB CAM               | 1        | 3.03%   |
| Generalplus GENERAL WEBCAM        | 1        | 3.03%   |

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
| 0     | 70       | 47.95%  |
| 1     | 68       | 46.58%  |
| 2     | 7        | 4.79%   |
| 3     | 1        | 0.68%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 63       | 73.26%  |
| Net/wireless             | 10       | 11.63%  |
| Graphics card            | 8        | 9.3%    |
| Net/ethernet             | 3        | 3.49%   |
| Unassigned class         | 1        | 1.16%   |
| Multimedia controller    | 1        | 1.16%   |

