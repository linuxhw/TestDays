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

Total: 217

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | M5A78L-M LX PLUS            | [7a2bce56b1](https://linux-hardware.org/?probe=7a2bce56b1) | Mar 26, 2023 |
| HP            | 8053                        | [82eb90837f](https://linux-hardware.org/?probe=82eb90837f) | Mar 21, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [40372e4af3](https://linux-hardware.org/?probe=40372e4af3) | Mar 19, 2023 |
| MSI           | B450-A PRO MAX              | [15f0543609](https://linux-hardware.org/?probe=15f0543609) | Mar 19, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [9d10f13efc](https://linux-hardware.org/?probe=9d10f13efc) | Mar 18, 2023 |
| HP            | 8053                        | [273a6c822b](https://linux-hardware.org/?probe=273a6c822b) | Mar 12, 2023 |
| HP            | 8053                        | [be27383efc](https://linux-hardware.org/?probe=be27383efc) | Mar 11, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [51b92fb276](https://linux-hardware.org/?probe=51b92fb276) | Mar 11, 2023 |
| Dell          | 0VYXHD A00                  | [d7618c5b6c](https://linux-hardware.org/?probe=d7618c5b6c) | Mar 08, 2023 |
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
| Garuda Linux Soaring | 76       | 49.67%  |
| Garuda Linux         | 54       | 35.29%  |
| Garuda Linux Rolling | 23       | 15.03%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Garuda Linux | 149      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Desktops | Percent |
|--------------------|----------|---------|
| 5.17.1-zen1-1-zen  | 6        | 3.57%   |
| 6.1.12-zen1-1-zen  | 4        | 2.38%   |
| 6.1.1-zen1-1-zen   | 4        | 2.38%   |
| 5.15.7-zen1-1-zen  | 4        | 2.38%   |
| 5.10.4-107-tkg-bmq | 4        | 2.38%   |
| 6.1.8-zen1-1-zen   | 3        | 1.79%   |
| 6.0.2-zen1-1-zen   | 3        | 1.79%   |
| 6.0.12-zen1-1-zen  | 3        | 1.79%   |
| 6.0.11-zen1-1-zen  | 3        | 1.79%   |
| 5.9.1-zen2-1-zen   | 3        | 1.79%   |
| 5.18.12-zen1-1-zen | 3        | 1.79%   |
| 5.18.1-zen1-1-zen  | 3        | 1.79%   |
| 5.16.4-zen1-1-zen  | 3        | 1.79%   |
| 5.15.2-zen1-1-zen  | 3        | 1.79%   |
| 5.15.13-zen1-1-zen | 3        | 1.79%   |
| 5.11.16-zen1-1-zen | 3        | 1.79%   |
| 6.2.2-zen2-1-zen   | 2        | 1.19%   |
| 6.1.4-zen2-1-zen   | 2        | 1.19%   |
| 6.1.3-zen1-1-zen   | 2        | 1.19%   |
| 6.0.8-zen1-1-zen   | 2        | 1.19%   |
| 5.9.11-zen2-1-zen  | 2        | 1.19%   |
| 5.9.10-zen1-1-zen  | 2        | 1.19%   |
| 5.8.14-zen1-1-zen  | 2        | 1.19%   |
| 5.19.9-zen1-1-zen  | 2        | 1.19%   |
| 5.19.5-zen1-1-zen  | 2        | 1.19%   |
| 5.18.16-zen1-1-zen | 2        | 1.19%   |
| 5.16.8-zen1-1-zen  | 2        | 1.19%   |
| 5.16.11-zen1-1-zen | 2        | 1.19%   |
| 5.16.10-zen1-1-zen | 2        | 1.19%   |
| 5.16.0-zen1-1-zen  | 2        | 1.19%   |
| 5.15.12-zen1-1-zen | 2        | 1.19%   |
| 5.15.10-zen1-1-zen | 2        | 1.19%   |
| 5.13.9-zen1-1-zen  | 2        | 1.19%   |
| 5.13.12-zen1-1-zen | 2        | 1.19%   |
| 5.12.4-zen1-2-zen  | 2        | 1.19%   |
| 5.10.8-112-tkg-bmq | 2        | 1.19%   |
| 6.2.7-zen1-1-zen   | 1        | 0.6%    |
| 6.2.6-zen1-1-zen   | 1        | 0.6%    |
| 6.2.2-zen1-1-zen   | 1        | 0.6%    |
| 6.1.9-zen1-2-zen   | 1        | 0.6%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.17.1  | 6        | 3.57%   |
| 6.1.12  | 4        | 2.38%   |
| 6.1.1   | 4        | 2.38%   |
| 5.15.7  | 4        | 2.38%   |
| 5.10.4  | 4        | 2.38%   |
| 6.2.2   | 3        | 1.79%   |
| 6.1.8   | 3        | 1.79%   |
| 6.1.4   | 3        | 1.79%   |
| 6.0.2   | 3        | 1.79%   |
| 6.0.12  | 3        | 1.79%   |
| 6.0.11  | 3        | 1.79%   |
| 5.9.1   | 3        | 1.79%   |
| 5.18.12 | 3        | 1.79%   |
| 5.18.1  | 3        | 1.79%   |
| 5.16.4  | 3        | 1.79%   |
| 5.15.2  | 3        | 1.79%   |
| 5.15.13 | 3        | 1.79%   |
| 5.12.13 | 3        | 1.79%   |
| 5.11.16 | 3        | 1.79%   |
| 6.1.3   | 2        | 1.19%   |
| 6.0.8   | 2        | 1.19%   |
| 5.9.11  | 2        | 1.19%   |
| 5.9.10  | 2        | 1.19%   |
| 5.8.14  | 2        | 1.19%   |
| 5.19.9  | 2        | 1.19%   |
| 5.19.5  | 2        | 1.19%   |
| 5.18.16 | 2        | 1.19%   |
| 5.17.5  | 2        | 1.19%   |
| 5.17.3  | 2        | 1.19%   |
| 5.16.8  | 2        | 1.19%   |
| 5.16.11 | 2        | 1.19%   |
| 5.16.10 | 2        | 1.19%   |
| 5.16.0  | 2        | 1.19%   |
| 5.15.12 | 2        | 1.19%   |
| 5.15.10 | 2        | 1.19%   |
| 5.14.12 | 2        | 1.19%   |
| 5.13.9  | 2        | 1.19%   |
| 5.13.12 | 2        | 1.19%   |
| 5.12.4  | 2        | 1.19%   |
| 5.12.12 | 2        | 1.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.1     | 19       | 11.66%  |
| 5.15    | 19       | 11.66%  |
| 5.10    | 16       | 9.82%   |
| 5.16    | 15       | 9.2%    |
| 5.18    | 14       | 8.59%   |
| 6.0     | 13       | 7.98%   |
| 5.17    | 10       | 6.13%   |
| 5.12    | 10       | 6.13%   |
| 5.11    | 10       | 6.13%   |
| 5.9     | 9        | 5.52%   |
| 5.19    | 7        | 4.29%   |
| 5.13    | 6        | 3.68%   |
| 6.2     | 5        | 3.07%   |
| 5.8     | 5        | 3.07%   |
| 5.14    | 5        | 3.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 149      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| KDE5       | 101      | 66.45%  |
| KDE        | 19       | 12.5%   |
| GNOME      | 18       | 11.84%  |
| X-Cinnamon | 3        | 1.97%   |
| xfce       | 2        | 1.32%   |
| sway       | 2        | 1.32%   |
| LXQt       | 2        | 1.32%   |
| MATE       | 1        | 0.66%   |
| i3         | 1        | 0.66%   |
| Deepin     | 1        | 0.66%   |
| Cinnamon   | 1        | 0.66%   |
| Unknown    | 1        | 0.66%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 135      | 90%     |
| Wayland | 7        | 4.67%   |
| Tty     | 5        | 3.33%   |
| Unknown | 3        | 2%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 71       | 47.33%  |
| SDDM    | 61       | 40.67%  |
| LightDM | 10       | 6.67%   |
| GDM     | 6        | 4%      |
| GREETD  | 2        | 1.33%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 78       | 52%     |
| de_DE | 16       | 10.67%  |
| en_GB | 13       | 8.67%   |
| es_ES | 5        | 3.33%   |
| en_CA | 4        | 2.67%   |
| en_AU | 4        | 2.67%   |
| pt_BR | 3        | 2%      |
| it_IT | 3        | 2%      |
| sk_SK | 2        | 1.33%   |
| ru_RU | 2        | 1.33%   |
| nl_NL | 2        | 1.33%   |
| fr_BE | 2        | 1.33%   |
| en_IN | 2        | 1.33%   |
| da_DK | 2        | 1.33%   |
| sv_SE | 1        | 0.67%   |
| nl_BE | 1        | 0.67%   |
| nb_NO | 1        | 0.67%   |
| iu_CA | 1        | 0.67%   |
| hu_HU | 1        | 0.67%   |
| fr_FR | 1        | 0.67%   |
| es_VE | 1        | 0.67%   |
| es_AR | 1        | 0.67%   |
| en_ZA | 1        | 0.67%   |
| en_DE | 1        | 0.67%   |
| el_GR | 1        | 0.67%   |
| cs_CZ | 1        | 0.67%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 78       | 52.35%  |
| BIOS | 71       | 47.65%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Btrfs   | 146      | 97.99%  |
| Ext4    | 2        | 1.34%   |
| Overlay | 1        | 0.67%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 74       | 49.33%  |
| Unknown | 71       | 47.33%  |
| MBR     | 5        | 3.33%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 122      | 80.79%  |
| Yes       | 29       | 19.21%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 103      | 68.67%  |
| Yes       | 47       | 31.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 44       | 29.53%  |
| MSI                 | 28       | 18.79%  |
| Gigabyte Technology | 24       | 16.11%  |
| ASRock              | 16       | 10.74%  |
| Hewlett-Packard     | 9        | 6.04%   |
| Dell                | 8        | 5.37%   |
| Lenovo              | 7        | 4.7%    |
| Pegatron            | 2        | 1.34%   |
| Intel               | 2        | 1.34%   |
| Acer                | 2        | 1.34%   |
| T-bao               | 1        | 0.67%   |
| OEM                 | 1        | 0.67%   |
| Medion              | 1        | 0.67%   |
| Fujitsu             | 1        | 0.67%   |
| Biostar             | 1        | 0.67%   |
| BESSTAR Tech        | 1        | 0.67%   |
| Alienware           | 1        | 0.67%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| ASUS TUF Gaming X570-PLUS          | 4        | 2.68%   |
| MSI MS-7B86                        | 3        | 2.01%   |
| MSI MS-7C91                        | 2        | 1.34%   |
| Gigabyte X570 AORUS PRO WIFI       | 2        | 1.34%   |
| Gigabyte AB350-Gaming 3            | 2        | 1.34%   |
| Dell Inspiron 3668                 | 2        | 1.34%   |
| ASUS ROG STRIX X570-E GAMING       | 2        | 1.34%   |
| ASUS ROG STRIX B550-F GAMING       | 2        | 1.34%   |
| ASUS PRIME X570-P                  | 2        | 1.34%   |
| ASUS All Series                    | 2        | 1.34%   |
| T-bao MINI PC                      | 1        | 0.67%   |
| Pegatron p7-1030                   | 1        | 0.67%   |
| Pegatron h9-1301es                 | 1        | 0.67%   |
| MSI MS-7D96                        | 1        | 0.67%   |
| MSI MS-7D75                        | 1        | 0.67%   |
| MSI MS-7D16                        | 1        | 0.67%   |
| MSI MS-7C90                        | 1        | 0.67%   |
| MSI MS-7C83                        | 1        | 0.67%   |
| MSI MS-7C56                        | 1        | 0.67%   |
| MSI MS-7C52                        | 1        | 0.67%   |
| MSI MS-7C37                        | 1        | 0.67%   |
| MSI MS-7C09                        | 1        | 0.67%   |
| MSI MS-7C02                        | 1        | 0.67%   |
| MSI MS-7B98                        | 1        | 0.67%   |
| MSI MS-7B89                        | 1        | 0.67%   |
| MSI MS-7B09                        | 1        | 0.67%   |
| MSI MS-7A78                        | 1        | 0.67%   |
| MSI MS-7A39                        | 1        | 0.67%   |
| MSI MS-7A38                        | 1        | 0.67%   |
| MSI MS-7A32                        | 1        | 0.67%   |
| MSI MS-7818                        | 1        | 0.67%   |
| MSI MS-7816                        | 1        | 0.67%   |
| MSI MS-7788                        | 1        | 0.67%   |
| MSI MS-7758                        | 1        | 0.67%   |
| MSI MS-7721                        | 1        | 0.67%   |
| MSI A320M-HDV R4.0                 | 1        | 0.67%   |
| Medion Akoya P5238 F/C395          | 1        | 0.67%   |
| Lenovo ThinkStation S20 4105O1U    | 1        | 0.67%   |
| Lenovo ThinkCentre M93p 10A90048US | 1        | 0.67%   |
| Lenovo ThinkCentre M93p 10A90016US | 1        | 0.67%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ASUS PRIME            | 12       | 8.05%   |
| ASUS ROG              | 10       | 6.71%   |
| ASUS TUF              | 6        | 4.03%   |
| Dell Inspiron         | 5        | 3.36%   |
| Lenovo ThinkCentre    | 4        | 2.68%   |
| Gigabyte X570         | 4        | 2.68%   |
| MSI MS-7B86           | 3        | 2.01%   |
| HP Pavilion           | 3        | 2.01%   |
| Gigabyte B550         | 3        | 2.01%   |
| Gigabyte B450         | 3        | 2.01%   |
| Dell OptiPlex         | 3        | 2.01%   |
| MSI MS-7C91           | 2        | 1.34%   |
| HP EliteDesk          | 2        | 1.34%   |
| Gigabyte AB350-Gaming | 2        | 1.34%   |
| ASUS Rampage          | 2        | 1.34%   |
| ASUS Maximus          | 2        | 1.34%   |
| ASUS All              | 2        | 1.34%   |
| Acer Aspire           | 2        | 1.34%   |
| T-bao MINI            | 1        | 0.67%   |
| Pegatron p7-1030      | 1        | 0.67%   |
| Pegatron h9-1301es    | 1        | 0.67%   |
| MSI MS-7D96           | 1        | 0.67%   |
| MSI MS-7D75           | 1        | 0.67%   |
| MSI MS-7D16           | 1        | 0.67%   |
| MSI MS-7C90           | 1        | 0.67%   |
| MSI MS-7C83           | 1        | 0.67%   |
| MSI MS-7C56           | 1        | 0.67%   |
| MSI MS-7C52           | 1        | 0.67%   |
| MSI MS-7C37           | 1        | 0.67%   |
| MSI MS-7C09           | 1        | 0.67%   |
| MSI MS-7C02           | 1        | 0.67%   |
| MSI MS-7B98           | 1        | 0.67%   |
| MSI MS-7B89           | 1        | 0.67%   |
| MSI MS-7B09           | 1        | 0.67%   |
| MSI MS-7A78           | 1        | 0.67%   |
| MSI MS-7A39           | 1        | 0.67%   |
| MSI MS-7A38           | 1        | 0.67%   |
| MSI MS-7A32           | 1        | 0.67%   |
| MSI MS-7818           | 1        | 0.67%   |
| MSI MS-7816           | 1        | 0.67%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 25       | 16.78%  |
| 2020 | 20       | 13.42%  |
| 2018 | 19       | 12.75%  |
| 2017 | 15       | 10.07%  |
| 2021 | 11       | 7.38%   |
| 2014 | 11       | 7.38%   |
| 2013 | 11       | 7.38%   |
| 2012 | 10       | 6.71%   |
| 2022 | 6        | 4.03%   |
| 2011 | 6        | 4.03%   |
| 2016 | 5        | 3.36%   |
| 2015 | 4        | 2.68%   |
| 2010 | 4        | 2.68%   |
| 2009 | 2        | 1.34%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 149      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 149      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 149      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 45       | 30%     |
| 32.01-64.0  | 41       | 27.33%  |
| 8.01-16.0   | 23       | 15.33%  |
| 4.01-8.0    | 16       | 10.67%  |
| 24.01-32.0  | 11       | 7.33%   |
| 64.01-256.0 | 10       | 6.67%   |
| 3.01-4.0    | 4        | 2.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 61       | 38.85%  |
| 3.01-4.0   | 31       | 19.75%  |
| 8.01-16.0  | 26       | 16.56%  |
| 2.01-3.0   | 22       | 14.01%  |
| 1.01-2.0   | 10       | 6.37%   |
| 16.01-24.0 | 6        | 3.82%   |
| 32.01-64.0 | 1        | 0.64%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 45       | 29.03%  |
| 3      | 35       | 22.58%  |
| 1      | 25       | 16.13%  |
| 4      | 24       | 15.48%  |
| 5      | 14       | 9.03%   |
| 6      | 5        | 3.23%   |
| 9      | 4        | 2.58%   |
| 18     | 1        | 0.65%   |
| 14     | 1        | 0.65%   |
| 7      | 1        | 0.65%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 104      | 69.33%  |
| Yes       | 46       | 30.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 147      | 98.66%  |
| No        | 2        | 1.34%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 83       | 54.25%  |
| No        | 70       | 45.75%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 77       | 50.66%  |
| Yes       | 75       | 49.34%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 47       | 31.54%  |
| Germany      | 21       | 14.09%  |
| Italy        | 7        | 4.7%    |
| UK           | 6        | 4.03%   |
| Spain        | 5        | 3.36%   |
| Canada       | 5        | 3.36%   |
| Brazil       | 5        | 3.36%   |
| Sweden       | 4        | 2.68%   |
| Belgium      | 4        | 2.68%   |
| Australia    | 4        | 2.68%   |
| Russia       | 3        | 2.01%   |
| Romania      | 3        | 2.01%   |
| Netherlands  | 3        | 2.01%   |
| India        | 3        | 2.01%   |
| Slovakia     | 2        | 1.34%   |
| Puerto Rico  | 2        | 1.34%   |
| Norway       | 2        | 1.34%   |
| Latvia       | 2        | 1.34%   |
| Greece       | 2        | 1.34%   |
| France       | 2        | 1.34%   |
| Denmark      | 2        | 1.34%   |
| Venezuela    | 1        | 0.67%   |
| Ukraine      | 1        | 0.67%   |
| South Africa | 1        | 0.67%   |
| Serbia       | 1        | 0.67%   |
| Poland       | 1        | 0.67%   |
| Philippines  | 1        | 0.67%   |
| Israel       | 1        | 0.67%   |
| Iceland      | 1        | 0.67%   |
| Hungary      | 1        | 0.67%   |
| Finland      | 1        | 0.67%   |
| Czechia      | 1        | 0.67%   |
| Chile        | 1        | 0.67%   |
| Bangladesh   | 1        | 0.67%   |
| Austria      | 1        | 0.67%   |
| Argentina    | 1        | 0.67%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| Milan                   | 3        | 1.92%   |
| Dallas                  | 3        | 1.92%   |
| Wasmes                  | 2        | 1.28%   |
| Sydney                  | 2        | 1.28%   |
| St Louis                | 2        | 1.28%   |
| Sao Paulo               | 2        | 1.28%   |
| Riga                    | 2        | 1.28%   |
| Oklahoma City           | 2        | 1.28%   |
| Melbourne               | 2        | 1.28%   |
| Mannheim                | 2        | 1.28%   |
| Kingsport               | 2        | 1.28%   |
| Berlin                  | 2        | 1.28%   |
| Algeciras               | 2        | 1.28%   |
| Zwickau                 | 1        | 0.64%   |
| York                    | 1        | 0.64%   |
| Weiterstadt             | 1        | 0.64%   |
| Weilen unter den Rinnen | 1        | 0.64%   |
| Voronezh                | 1        | 0.64%   |
| Volzhskiy               | 1        | 0.64%   |
| Västerås              | 1        | 0.64%   |
| Valence                 | 1        | 0.64%   |
| Urbandale               | 1        | 0.64%   |
| Ullerslev               | 1        | 0.64%   |
| Trecastelli             | 1        | 0.64%   |
| Timișoara              | 1        | 0.64%   |
| Taunusstein             | 1        | 0.64%   |
| Tampere                 | 1        | 0.64%   |
| Stockholm               | 1        | 0.64%   |
| Steyr                   | 1        | 0.64%   |
| Stavropol               | 1        | 0.64%   |
| Stanley                 | 1        | 0.64%   |
| Sindelfingen            | 1        | 0.64%   |
| Shreveport              | 1        | 0.64%   |
| Sherwood Park           | 1        | 0.64%   |
| Satu Mare               | 1        | 0.64%   |
| Sarasota                | 1        | 0.64%   |
| Santa Cruz de Tenerife  | 1        | 0.64%   |
| Sandviken               | 1        | 0.64%   |
| San Juan                | 1        | 0.64%   |
| San Jose                | 1        | 0.64%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 69       | 105    | 18.16%  |
| Seagate                     | 62       | 88     | 16.32%  |
| Samsung Electronics         | 61       | 112    | 16.05%  |
| Toshiba                     | 25       | 33     | 6.58%   |
| Crucial                     | 20       | 27     | 5.26%   |
| SanDisk                     | 17       | 25     | 4.47%   |
| Kingston                    | 17       | 26     | 4.47%   |
| Hitachi                     | 9        | 9      | 2.37%   |
| Silicon Motion              | 7        | 7      | 1.84%   |
| Phison                      | 7        | 8      | 1.84%   |
| Intel                       | 6        | 9      | 1.58%   |
| PNY                         | 5        | 5      | 1.32%   |
| Micron/Crucial Technology   | 5        | 8      | 1.32%   |
| A-DATA Technology           | 5        | 8      | 1.32%   |
| Unknown                     | 4        | 4      | 1.05%   |
| OCZ                         | 4        | 4      | 1.05%   |
| China                       | 4        | 6      | 1.05%   |
| XPG                         | 3        | 4      | 0.79%   |
| SPCC                        | 3        | 3      | 0.79%   |
| HGST                        | 3        | 9      | 0.79%   |
| Emtec                       | 3        | 5      | 0.79%   |
| Transcend                   | 2        | 2      | 0.53%   |
| TO Exter                    | 2        | 2      | 0.53%   |
| Team                        | 2        | 3      | 0.53%   |
| SK hynix                    | 2        | 2      | 0.53%   |
| LITEONIT                    | 2        | 2      | 0.53%   |
| Kingston Technology Company | 2        | 2      | 0.53%   |
| Intenso                     | 2        | 3      | 0.53%   |
| Hewlett-Packard             | 2        | 2      | 0.53%   |
| WD MediaMax                 | 1        | 1      | 0.26%   |
| USB30                       | 1        | 2      | 0.26%   |
| T-FORCE                     | 1        | 1      | 0.26%   |
| Realtek Semiconductor       | 1        | 1      | 0.26%   |
| Qumo                        | 1        | 1      | 0.26%   |
| Plextor                     | 1        | 1      | 0.26%   |
| Patriot                     | 1        | 1      | 0.26%   |
| Mushkin                     | 1        | 1      | 0.26%   |
| Micron Technology           | 1        | 1      | 0.26%   |
| MAXIO Technology (Hangzhou) | 1        | 1      | 0.26%   |
| LITEON                      | 1        | 1      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung SSD 850 EVO 250GB                           | 8        | 1.75%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 7        | 1.53%   |
| Samsung NVMe SSD Drive 1TB                          | 6        | 1.31%   |
| Crucial CT1000MX500SSD1 1TB                         | 6        | 1.31%   |
| Seagate ST2000DM008-2FR102 2TB                      | 5        | 1.09%   |
| Samsung SSD 970 EVO Plus 500GB                      | 5        | 1.09%   |
| Samsung SSD 860 EVO 500GB                           | 5        | 1.09%   |
| Seagate ST1000DM010-2EP102 1TB                      | 4        | 0.88%   |
| Samsung NVMe SSD Drive 500GB                        | 4        | 0.88%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 3        | 0.66%   |
| WDC WD10EZEX-60WN4A0 1TB                            | 3        | 0.66%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 3        | 0.66%   |
| WDC WD10EALX-009BA0 1TB                             | 3        | 0.66%   |
| Toshiba HDWD110 1TB                                 | 3        | 0.66%   |
| Toshiba DT01ACA100 1TB                              | 3        | 0.66%   |
| Toshiba DT01ACA050 500GB                            | 3        | 0.66%   |
| Seagate ST4000DM004-2CV104 4TB                      | 3        | 0.66%   |
| Seagate ST3320820AS 320GB                           | 3        | 0.66%   |
| Seagate ST3000DM001-1ER166 3TB                      | 3        | 0.66%   |
| Seagate ST2000DL003-9VT166 2TB                      | 3        | 0.66%   |
| Seagate Portable 2TB                                | 3        | 0.66%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                | 3        | 0.66%   |
| SanDisk SSD PLUS 1000GB                             | 3        | 0.66%   |
| SanDisk NVMe SSD Drive 1TB                          | 3        | 0.66%   |
| Samsung SSD 860 EVO 250GB                           | 3        | 0.66%   |
| Samsung SSD 860 EVO 1TB                             | 3        | 0.66%   |
| Samsung SSD 850 EVO 500GB                           | 3        | 0.66%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 3        | 0.66%   |
| PNY CS900 240GB SSD                                 | 3        | 0.66%   |
| XPG NVMe SSD Drive 512GB                            | 2        | 0.44%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 2        | 0.44%   |
| WDC WDS240G1G0A-00SS50 240GB SSD                    | 2        | 0.44%   |
| WDC WDS100T2B0C-00PXH0 1TB                          | 2        | 0.44%   |
| WDC WD60EZAZ-00SF3B0 6TB                            | 2        | 0.44%   |
| WDC WD20EARX-00PASB0 2TB                            | 2        | 0.44%   |
| WDC WD10EARS-00Y5B1 1TB                             | 2        | 0.44%   |
| WDC WD10EADS-00M2B0 1TB                             | 2        | 0.44%   |
| Unknown SD/MMC/MS PRO 64GB                          | 2        | 0.44%   |
| Toshiba TR150 480GB SSD                             | 2        | 0.44%   |
| Toshiba DT01ACA300 3TB                              | 2        | 0.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 60       | 85     | 37.27%  |
| WDC                 | 58       | 91     | 36.02%  |
| Toshiba             | 21       | 25     | 13.04%  |
| Hitachi             | 9        | 9      | 5.59%   |
| Samsung Electronics | 4        | 4      | 2.48%   |
| HGST                | 3        | 9      | 1.86%   |
| Unknown             | 2        | 2      | 1.24%   |
| Intenso             | 2        | 3      | 1.24%   |
| Hewlett-Packard     | 1        | 1      | 0.62%   |
| ASMedia             | 1        | 2      | 0.62%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 31       | 51     | 24.6%   |
| Crucial             | 16       | 21     | 12.7%   |
| Kingston            | 13       | 19     | 10.32%  |
| SanDisk             | 9        | 14     | 7.14%   |
| WDC                 | 8        | 8      | 6.35%   |
| A-DATA Technology   | 5        | 8      | 3.97%   |
| Toshiba             | 4        | 7      | 3.17%   |
| PNY                 | 4        | 4      | 3.17%   |
| OCZ                 | 4        | 4      | 3.17%   |
| China               | 4        | 6      | 3.17%   |
| SPCC                | 3        | 3      | 2.38%   |
| Emtec               | 3        | 5      | 2.38%   |
| Transcend           | 2        | 2      | 1.59%   |
| TO Exter            | 2        | 2      | 1.59%   |
| Team                | 2        | 3      | 1.59%   |
| SK hynix            | 2        | 2      | 1.59%   |
| LITEONIT            | 2        | 2      | 1.59%   |
| USB30               | 1        | 2      | 0.79%   |
| Unknown             | 1        | 1      | 0.79%   |
| T-FORCE             | 1        | 1      | 0.79%   |
| Qumo                | 1        | 1      | 0.79%   |
| Plextor             | 1        | 1      | 0.79%   |
| Mushkin             | 1        | 1      | 0.79%   |
| Micron Technology   | 1        | 1      | 0.79%   |
| LITEON              | 1        | 1      | 0.79%   |
| Inateck             | 1        | 1      | 0.79%   |
| HS-SSD-C100         | 1        | 1      | 0.79%   |
| Fanxiang            | 1        | 1      | 0.79%   |
| ADATA SU            | 1        | 1      | 0.79%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 113      | 231    | 38.44%  |
| SSD     | 90       | 174    | 30.61%  |
| NVMe    | 80       | 139    | 27.21%  |
| Unknown | 11       | 11     | 3.74%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 134      | 377    | 56.54%  |
| NVMe | 80       | 139    | 33.76%  |
| SAS  | 23       | 39     | 9.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 92       | 185    | 36.8%   |
| 0.51-1.0   | 75       | 108    | 30%     |
| 1.01-2.0   | 45       | 60     | 18%     |
| 2.01-3.0   | 13       | 21     | 5.2%    |
| 4.01-10.0  | 12       | 15     | 4.8%    |
| 3.01-4.0   | 11       | 13     | 4.4%    |
| 10.01-20.0 | 2        | 3      | 0.8%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 76       | 50.33%  |
| 1001-2000      | 27       | 17.88%  |
| 2001-3000      | 21       | 13.91%  |
| 501-1000       | 15       | 9.93%   |
| 251-500        | 8        | 5.3%    |
| Unknown        | 2        | 1.32%   |
| 101-250        | 1        | 0.66%   |
| 1-20           | 1        | 0.66%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 26       | 16.67%  |
| 101-250        | 25       | 16.03%  |
| 501-1000       | 25       | 16.03%  |
| More than 3000 | 23       | 14.74%  |
| 1001-2000      | 21       | 13.46%  |
| 2001-3000      | 19       | 12.18%  |
| 51-100         | 10       | 6.41%   |
| 21-50          | 3        | 1.92%   |
| 1-20           | 2        | 1.28%   |
| Unknown        | 2        | 1.28%   |

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
| Intenso USB 3.0 device 1TB         | 1        | 1      | 3.33%   |
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
| Detected | 91       | 305    | 48.92%  |
| Works    | 72       | 215    | 38.71%  |
| Malfunc  | 23       | 35     | 12.37%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| AMD                          | 79       | 31.35%  |
| Intel                        | 71       | 28.17%  |
| Samsung Electronics          | 36       | 14.29%  |
| SanDisk                      | 13       | 5.16%   |
| Silicon Motion               | 8        | 3.17%   |
| Phison Electronics           | 8        | 3.17%   |
| Micron/Crucial Technology    | 7        | 2.78%   |
| Kingston Technology Company  | 7        | 2.78%   |
| ASMedia Technology           | 7        | 2.78%   |
| Marvell Technology Group     | 5        | 1.98%   |
| ADATA Technology             | 3        | 1.19%   |
| Realtek Semiconductor        | 2        | 0.79%   |
| JMicron Technology           | 2        | 0.79%   |
| Union Memory (Shenzhen)      | 1        | 0.4%    |
| Toshiba America Info Systems | 1        | 0.4%    |
| Shenzhen Longsys Electronics | 1        | 0.4%    |
| MAXIO Technology (Hangzhou)  | 1        | 0.4%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 48       | 15.48%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 29       | 9.35%   |
| AMD 400 Series Chipset SATA Controller                                                  | 19       | 6.13%   |
| AMD 500 Series Chipset SATA Controller                                                  | 16       | 5.16%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 13       | 4.19%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 8        | 2.58%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 7        | 2.26%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 6        | 1.94%   |
| Phison E12 NVMe Controller                                                              | 6        | 1.94%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 6        | 1.94%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6        | 1.94%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 6        | 1.94%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 6        | 1.94%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 5        | 1.61%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 5        | 1.61%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 5        | 1.61%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5        | 1.61%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 1.61%   |
| AMD FCH SATA Controller D                                                               | 4        | 1.29%   |
| AMD 300 Series Chipset SATA Controller                                                  | 4        | 1.29%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 3        | 0.97%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 3        | 0.97%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 3        | 0.97%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 3        | 0.97%   |
| Intel SSD 660P Series                                                                   | 3        | 0.97%   |
| Intel SATA Controller [RAID mode]                                                       | 3        | 0.97%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 0.97%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 0.97%   |
| AMD X399 Series Chipset SATA Controller                                                 | 3        | 0.97%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3        | 0.97%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 3        | 0.97%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2        | 0.65%   |
| Samsung NVMe SSD Controller 980                                                         | 2        | 0.65%   |
| Realtek NVMe Controller                                                                 | 2        | 0.65%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2        | 0.65%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 2        | 0.65%   |
| Micron/Crucial NVMe Storage Controller                                                  | 2        | 0.65%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 2        | 0.65%   |
| Kingston Company NVMe Controller                                                        | 2        | 0.65%   |
| Kingston Company A2000 NVMe SSD                                                         | 2        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 135      | 56.49%  |
| NVMe | 81       | 33.89%  |
| IDE  | 14       | 5.86%   |
| RAID | 9        | 3.77%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 79       | 53.02%  |
| Intel  | 70       | 46.98%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 9 3900X 12-Core Processor         | 6        | 4.03%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 6        | 4.03%   |
| AMD Ryzen 5 3600 6-Core Processor           | 5        | 3.36%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 4        | 2.68%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 4        | 2.68%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 2.01%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 3        | 2.01%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 3        | 2.01%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 3        | 2.01%   |
| AMD FX-8350 Eight-Core Processor            | 3        | 2.01%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 2        | 1.34%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 2        | 1.34%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2        | 1.34%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 1.34%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 2        | 1.34%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2        | 1.34%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 1.34%   |
| Intel 12th Gen Core i5-12600K               | 2        | 1.34%   |
| AMD Ryzen 9 7900X 12-Core Processor         | 2        | 1.34%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 2        | 1.34%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 2        | 1.34%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 2        | 1.34%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 2        | 1.34%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 1.34%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 2        | 1.34%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 2        | 1.34%   |
| Intel Xeon CPU W3550 @ 3.07GHz              | 1        | 0.67%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz          | 1        | 0.67%   |
| Intel Xeon CPU E5-1680 v2 @ 3.00GHz         | 1        | 0.67%   |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz         | 1        | 0.67%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 1        | 0.67%   |
| Intel Core i9-10900K CPU @ 3.70GHz          | 1        | 0.67%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1        | 0.67%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1        | 0.67%   |
| Intel Core i7-6850K CPU @ 3.60GHz           | 1        | 0.67%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 0.67%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 0.67%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1        | 0.67%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 0.67%   |
| Intel Core i7-3930K CPU @ 3.20GHz           | 1        | 0.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 25       | 16.78%  |
| AMD Ryzen 7             | 23       | 15.44%  |
| AMD Ryzen 5             | 23       | 15.44%  |
| Intel Core i7           | 18       | 12.08%  |
| Intel Core i3           | 14       | 9.4%    |
| AMD Ryzen 9             | 12       | 8.05%   |
| AMD Ryzen 3             | 5        | 3.36%   |
| AMD FX                  | 5        | 3.36%   |
| Other                   | 4        | 2.68%   |
| Intel Xeon              | 4        | 2.68%   |
| AMD Ryzen Threadripper  | 3        | 2.01%   |
| Intel Celeron           | 2        | 1.34%   |
| AMD A10                 | 2        | 1.34%   |
| Intel Pentium Dual-Core | 1        | 0.67%   |
| Intel Core i9           | 1        | 0.67%   |
| Intel Core 2 Quad       | 1        | 0.67%   |
| AMD Phenom II X6        | 1        | 0.67%   |
| AMD Phenom II X4        | 1        | 0.67%   |
| AMD Phenom II X2        | 1        | 0.67%   |
| AMD Athlon X4           | 1        | 0.67%   |
| AMD Athlon              | 1        | 0.67%   |
| AMD A8                  | 1        | 0.67%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 51       | 34.23%  |
| 6      | 30       | 20.13%  |
| 8      | 28       | 18.79%  |
| 2      | 21       | 14.09%  |
| 12     | 10       | 6.71%   |
| 16     | 4        | 2.68%   |
| 10     | 3        | 2.01%   |
| 24     | 1        | 0.67%   |
| 3      | 1        | 0.67%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 149      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 113      | 75.84%  |
| 1      | 36       | 24.16%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 149      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 77       | 50.66%  |
| 0x08701021 | 9        | 5.92%   |
| 0x306c3    | 7        | 4.61%   |
| 0x0800820d | 6        | 3.95%   |
| 0x306a9    | 5        | 3.29%   |
| 0x206a7    | 4        | 2.63%   |
| 0x906ea    | 3        | 1.97%   |
| 0x0a50000c | 3        | 1.97%   |
| 0x08001137 | 3        | 1.97%   |
| 0xa0653    | 2        | 1.32%   |
| 0x906ed    | 2        | 1.32%   |
| 0x90672    | 2        | 1.32%   |
| 0x506e3    | 2        | 1.32%   |
| 0x0a201204 | 2        | 1.32%   |
| 0x0a201009 | 2        | 1.32%   |
| 0x08108109 | 2        | 1.32%   |
| 0x0810100b | 2        | 1.32%   |
| 0x06000852 | 2        | 1.32%   |
| 0xa0655    | 1        | 0.66%   |
| 0x906ec    | 1        | 0.66%   |
| 0x906eb    | 1        | 0.66%   |
| 0x906e9    | 1        | 0.66%   |
| 0x90675    | 1        | 0.66%   |
| 0x106a5    | 1        | 0.66%   |
| 0x1067a    | 1        | 0.66%   |
| 0x0a601203 | 1        | 0.66%   |
| 0x0a601201 | 1        | 0.66%   |
| 0x0a50000d | 1        | 0.66%   |
| 0x0a20120a | 1        | 0.66%   |
| 0x0a201016 | 1        | 0.66%   |
| 0x08701013 | 1        | 0.66%   |
| 0x08101016 | 1        | 0.66%   |
| 0x06003106 | 1        | 0.66%   |
| 0x010000dc | 1        | 0.66%   |
| 0x00000000 | 1        | 0.66%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 21       | 14.09%  |
| Zen 3            | 19       | 12.75%  |
| Zen+             | 16       | 10.74%  |
| KabyLake         | 16       | 10.74%  |
| Haswell          | 14       | 9.4%    |
| IvyBridge        | 11       | 7.38%   |
| Zen              | 9        | 6.04%   |
| SandyBridge      | 9        | 6.04%   |
| CometLake        | 7        | 4.7%    |
| Piledriver       | 6        | 4.03%   |
| Skylake          | 4        | 2.68%   |
| Steamroller      | 3        | 2.01%   |
| K10              | 3        | 2.01%   |
| Alderlake Hybrid | 3        | 2.01%   |
| Unknown          | 3        | 2.01%   |
| Penryn           | 2        | 1.34%   |
| Westmere         | 1        | 0.67%   |
| Nehalem          | 1        | 0.67%   |
| Broadwell        | 1        | 0.67%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 74       | 44.05%  |
| Nvidia | 63       | 37.5%   |
| Intel  | 31       | 18.45%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 15       | 8.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 9        | 5.17%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 8        | 4.6%    |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 7        | 4.02%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 6        | 3.45%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 5        | 2.87%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 5        | 2.87%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 4        | 2.3%    |
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 2.3%    |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 4        | 2.3%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 4        | 2.3%    |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 3        | 1.72%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 3        | 1.72%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 1.72%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 1.72%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3        | 1.72%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 1.15%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 2        | 1.15%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 1.15%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 1.15%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 1.15%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2        | 1.15%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 2        | 1.15%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 1.15%   |
| Nvidia GM204 [GeForce GTX 980]                                              | 2        | 1.15%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 2        | 1.15%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 2        | 1.15%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 2        | 1.15%   |
| Intel HD Graphics 630                                                       | 2        | 1.15%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 1.15%   |
| AMD Tahiti PRO [Radeon HD 7950/8950 OEM / R9 280]                           | 2        | 1.15%   |
| AMD RS780L [Radeon 3000]                                                    | 2        | 1.15%   |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                  | 2        | 1.15%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                            | 2        | 1.15%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 2        | 1.15%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 0.57%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 0.57%   |
| Nvidia TU106 [GeForce RTX 2060 12GB]                                        | 1        | 0.57%   |
| Nvidia TU104 [GeForce RTX 2080]                                             | 1        | 0.57%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 64       | 42.11%  |
| 1 x Nvidia     | 54       | 35.53%  |
| 1 x Intel      | 19       | 12.5%   |
| AMD + Nvidia   | 5        | 3.29%   |
| 2 x AMD        | 4        | 2.63%   |
| 2 x Nvidia     | 2        | 1.32%   |
| Intel + Nvidia | 2        | 1.32%   |
| Intel + AMD    | 2        | 1.32%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 96       | 63.58%  |
| Proprietary | 54       | 35.76%  |
| Unknown     | 1        | 0.66%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 60       | 39.22%  |
| 7.01-8.0   | 25       | 16.34%  |
| 3.01-4.0   | 18       | 11.76%  |
| 1.01-2.0   | 15       | 9.8%    |
| 8.01-16.0  | 12       | 7.84%   |
| 5.01-6.0   | 7        | 4.58%   |
| 0.51-1.0   | 7        | 4.58%   |
| 0.01-0.5   | 5        | 3.27%   |
| 2.01-3.0   | 2        | 1.31%   |
| 16.01-24.0 | 2        | 1.31%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 30       | 15.38%  |
| Goldstar             | 19       | 9.74%   |
| Dell                 | 19       | 9.74%   |
| Acer                 | 19       | 9.74%   |
| AOC                  | 13       | 6.67%   |
| Hewlett-Packard      | 12       | 6.15%   |
| BenQ                 | 10       | 5.13%   |
| Ancor Communications | 10       | 5.13%   |
| Unknown              | 6        | 3.08%   |
| ASUSTek Computer     | 6        | 3.08%   |
| Philips              | 4        | 2.05%   |
| MSI                  | 4        | 2.05%   |
| Iiyama               | 4        | 2.05%   |
| Gigabyte Technology  | 4        | 2.05%   |
| ViewSonic            | 3        | 1.54%   |
| Vizio                | 2        | 1.03%   |
| Toshiba              | 2        | 1.03%   |
| Sony                 | 2        | 1.03%   |
| NEC Computers        | 2        | 1.03%   |
| Mi                   | 2        | 1.03%   |
| LG Electronics       | 2        | 1.03%   |
| Xiaomi               | 1        | 0.51%   |
| Vestel               | 1        | 0.51%   |
| RTK                  | 1        | 0.51%   |
| Optoma               | 1        | 0.51%   |
| ONN                  | 1        | 0.51%   |
| MiTAC                | 1        | 0.51%   |
| Microstep            | 1        | 0.51%   |
| LTM                  | 1        | 0.51%   |
| Lenovo Group Limited | 1        | 0.51%   |
| Lenovo               | 1        | 0.51%   |
| Insignia             | 1        | 0.51%   |
| Idek Iiyama          | 1        | 0.51%   |
| HPN                  | 1        | 0.51%   |
| HKC                  | 1        | 0.51%   |
| Hitachi              | 1        | 0.51%   |
| Fujitsu Siemens      | 1        | 0.51%   |
| Element              | 1        | 0.51%   |
| AOpen                | 1        | 0.51%   |
| Alba                 | 1        | 0.51%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 3        | 1.42%   |
| Samsung Electronics S34J55x SAM0F72 3440x1440 797x333mm 34.0-inch      | 2        | 0.95%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch               | 2        | 0.95%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 2        | 0.95%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                    | 2        | 0.95%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 2        | 0.95%   |
| Dell 1909W DELA03C 1440x900 408x255mm 18.9-inch                        | 2        | 0.95%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                     | 2        | 0.95%   |
| Ancor Communications ASUS PB287Q ACI28A3 3840x2160 621x341mm 27.9-inch | 2        | 0.95%   |
| Acer X223W ACR0009 1680x1050 473x296mm 22.0-inch                       | 2        | 0.95%   |
| Xiaomi Mi TV XMD009A 2224x1668 341x192mm 15.4-inch                     | 1        | 0.47%   |
| Vizio P502ui-B1E VIZ1013 3840x2160 1095x616mm 49.5-inch                | 1        | 0.47%   |
| Vizio D320-B1 VIZ0095 1360x768 697x392mm 31.5-inch                     | 1        | 0.47%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch             | 1        | 0.47%   |
| ViewSonic VX3258 series VSCDE35 2560x1440 700x390mm 31.5-inch          | 1        | 0.47%   |
| ViewSonic VX2270 SERIES VSCE02C 1920x1080 476x267mm 21.5-inch          | 1        | 0.47%   |
| Vestel LCD Monitor 24W_LCD_TV 1920x1080                                | 1        | 0.47%   |
| Unknown LCD Monitor XXX AAA 1366x768                                   | 1        | 0.47%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                  | 1        | 0.47%   |
| Unknown LCD Monitor SAMSUNG                                            | 1        | 0.47%   |
| Unknown LCD Monitor RJT HDMI                                           | 1        | 0.47%   |
| Unknown LCD Monitor LHC 32-QHD-144-C 4480x1440                         | 1        | 0.47%   |
| Unknown LCD Monitor Hitachi/HINT W240D DVI                             | 1        | 0.47%   |
| Toshiba TV TSB0206 1920x1080                                           | 1        | 0.47%   |
| Toshiba TV TSB0105 1920x1080 708x398mm 32.0-inch                       | 1        | 0.47%   |
| Sony TV SNY1802 1920x1080                                              | 1        | 0.47%   |
| Sony TV SNY0801 1360x768                                               | 1        | 0.47%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch      | 1        | 0.47%   |
| Samsung Electronics U28E850 SAM0CCB 3840x2160 607x345mm 27.5-inch      | 1        | 0.47%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch      | 1        | 0.47%   |
| Samsung Electronics T24E390 SAM0C20 1920x1080 521x293mm 23.5-inch      | 1        | 0.47%   |
| Samsung Electronics SyncMaster SAM05B0 1920x1080                       | 1        | 0.47%   |
| Samsung Electronics SyncMaster SAM04D5 1920x1080                       | 1        | 0.47%   |
| Samsung Electronics SyncMaster SAM00BB 1280x1024 376x301mm 19.0-inch   | 1        | 0.47%   |
| Samsung Electronics SMS24A350H SAM07D6 1920x1080 531x299mm 24.0-inch   | 1        | 0.47%   |
| Samsung Electronics SMB2230 SAM063E 1920x1080 477x268mm 21.5-inch      | 1        | 0.47%   |
| Samsung Electronics S24R35xFZ SAM71A8 1920x1080 527x296mm 23.8-inch    | 1        | 0.47%   |
| Samsung Electronics S24E450 SAM0CA0 1920x1080 531x299mm 24.0-inch      | 1        | 0.47%   |
| Samsung Electronics S24D300 SAM0B45 1920x1080 521x293mm 23.5-inch      | 1        | 0.47%   |
| Samsung Electronics S24D300 SAM0B42 1920x1080 531x299mm 24.0-inch      | 1        | 0.47%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 87       | 46.77%  |
| 3840x2160 (4K)     | 23       | 12.37%  |
| 2560x1440 (QHD)    | 14       | 7.53%   |
| Unknown            | 9        | 4.84%   |
| 3440x1440          | 8        | 4.3%    |
| 2560x1080          | 6        | 3.23%   |
| 1680x1050 (WSXGA+) | 6        | 3.23%   |
| 1366x768 (WXGA)    | 6        | 3.23%   |
| 1280x1024 (SXGA)   | 5        | 2.69%   |
| 3840x1080          | 4        | 2.15%   |
| 1920x1200 (WUXGA)  | 3        | 1.61%   |
| 1600x900 (HD+)     | 3        | 1.61%   |
| 1440x900 (WXGA+)   | 3        | 1.61%   |
| 7680x2160          | 2        | 1.08%   |
| 1360x768           | 2        | 1.08%   |
| 9600x2160          | 1        | 0.54%   |
| 4480x1440          | 1        | 0.54%   |
| 3840x1200          | 1        | 0.54%   |
| 2048x1152          | 1        | 0.54%   |
| 1920x540           | 1        | 0.54%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 36       | 19.35%  |
| 24      | 30       | 16.13%  |
| Unknown | 28       | 15.05%  |
| 23      | 20       | 10.75%  |
| 31      | 11       | 5.91%   |
| 21      | 11       | 5.91%   |
| 34      | 9        | 4.84%   |
| 19      | 8        | 4.3%    |
| 22      | 6        | 3.23%   |
| 72      | 4        | 2.15%   |
| 20      | 3        | 1.61%   |
| 74      | 2        | 1.08%   |
| 49      | 2        | 1.08%   |
| 40      | 2        | 1.08%   |
| 28      | 2        | 1.08%   |
| 25      | 2        | 1.08%   |
| 18      | 2        | 1.08%   |
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
| 501-600     | 74       | 42.29%  |
| Unknown     | 28       | 16%     |
| 401-500     | 25       | 14.29%  |
| 601-700     | 18       | 10.29%  |
| 701-800     | 11       | 6.29%   |
| 1501-2000   | 6        | 3.43%   |
| 1001-1500   | 6        | 3.43%   |
| 351-400     | 4        | 2.29%   |
| 801-900     | 2        | 1.14%   |
| 301-350     | 1        | 0.57%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 105      | 63.64%  |
| Unknown | 26       | 15.76%  |
| 16/10   | 17       | 10.3%   |
| 21/9    | 10       | 6.06%   |
| 5/4     | 5        | 3.03%   |
| 32/9    | 2        | 1.21%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 52       | 29.05%  |
| 301-350        | 37       | 20.67%  |
| Unknown        | 28       | 15.64%  |
| 351-500        | 23       | 12.85%  |
| 151-200        | 12       | 6.7%    |
| More than 1000 | 10       | 5.59%   |
| 251-300        | 10       | 5.59%   |
| 501-1000       | 4        | 2.23%   |
| 141-150        | 3        | 1.68%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 91       | 55.49%  |
| Unknown | 28       | 17.07%  |
| 101-120 | 25       | 15.24%  |
| 121-160 | 9        | 5.49%   |
| 1-50    | 7        | 4.27%   |
| 161-240 | 4        | 2.44%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 93       | 61.18%  |
| 2     | 41       | 26.97%  |
| 3     | 14       | 9.21%   |
| 0     | 3        | 1.97%   |
| 4     | 1        | 0.66%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 103      | 44.59%  |
| Intel                 | 70       | 30.3%   |
| Qualcomm Atheros      | 12       | 5.19%   |
| MediaTek              | 5        | 2.16%   |
| Broadcom              | 5        | 2.16%   |
| Ralink Technology     | 4        | 1.73%   |
| NetGear               | 4        | 1.73%   |
| Linksys               | 4        | 1.73%   |
| TP-Link               | 3        | 1.3%    |
| Microsoft             | 3        | 1.3%    |
| Aquantia              | 3        | 1.3%    |
| Ralink                | 2        | 0.87%   |
| DisplayLink           | 2        | 0.87%   |
| Xiaomi                | 1        | 0.43%   |
| Sitecom Europe        | 1        | 0.43%   |
| Samsung Electronics   | 1        | 0.43%   |
| InterBiometrics       | 1        | 0.43%   |
| Holtek Semiconductor  | 1        | 0.43%   |
| D-Link                | 1        | 0.43%   |
| Belkin Components     | 1        | 0.43%   |
| AVM                   | 1        | 0.43%   |
| ASIX Electronics      | 1        | 0.43%   |
| Alteon Networks       | 1        | 0.43%   |
| Accton Technology     | 1        | 0.43%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 82       | 31.54%  |
| Intel I211 Gigabit Network Connection                               | 17       | 6.54%   |
| Realtek RTL8125 2.5GbE Controller                                   | 13       | 5%      |
| Intel Wi-Fi 6 AX200                                                 | 12       | 4.62%   |
| Intel Ethernet Controller I225-V                                    | 10       | 3.85%   |
| Intel Wireless-AC 9260                                              | 7        | 2.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 6        | 2.31%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 6        | 2.31%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 4        | 1.54%   |
| Intel Ethernet Connection I217-LM                                   | 4        | 1.54%   |
| Ralink RT2870/RT3070 Wireless Adapter                               | 3        | 1.15%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 3        | 1.15%   |
| Intel Wireless 7265                                                 | 3        | 1.15%   |
| Intel Ethernet Connection (2) I219-V                                | 3        | 1.15%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 3        | 1.15%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                     | 2        | 0.77%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 2        | 0.77%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 2        | 0.77%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 2        | 0.77%   |
| NetGear A6210                                                       | 2        | 0.77%   |
| Microsoft XBOX ACC                                                  | 2        | 0.77%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter       | 2        | 0.77%   |
| Linksys AE6000 802.11a/b/g/n/ac Wireless Adapter [MediaTek MT7610U] | 2        | 0.77%   |
| Intel Ethernet Connection (7) I219-V                                | 2        | 0.77%   |
| Intel 82579V Gigabit Network Connection                             | 2        | 0.77%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 2        | 0.77%   |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 1        | 0.38%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                         | 1        | 0.38%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                        | 1        | 0.38%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                          | 1        | 0.38%   |
| Sitecom Europe WLA-5000 802.11abgn [Ralink RT3572]                  | 1        | 0.38%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 1        | 0.38%   |
| Realtek USB 10/100/1G/2.5G LAN                                      | 1        | 0.38%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 1        | 0.38%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter            | 1        | 0.38%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                 | 1        | 0.38%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                              | 1        | 0.38%   |
| Realtek RTL8188RU 802.11n WLAN Adapter                              | 1        | 0.38%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter               | 1        | 0.38%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                 | 1        | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 38       | 42.22%  |
| Realtek Semiconductor | 17       | 18.89%  |
| Qualcomm Atheros      | 5        | 5.56%   |
| Ralink Technology     | 4        | 4.44%   |
| NetGear               | 4        | 4.44%   |
| Linksys               | 4        | 4.44%   |
| TP-Link               | 3        | 3.33%   |
| Microsoft             | 3        | 3.33%   |
| MediaTek              | 3        | 3.33%   |
| Broadcom              | 3        | 3.33%   |
| Ralink                | 2        | 2.22%   |
| Sitecom Europe        | 1        | 1.11%   |
| D-Link                | 1        | 1.11%   |
| AVM                   | 1        | 1.11%   |
| Accton Technology     | 1        | 1.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                       | 12       | 13.33%  |
| Intel Wireless-AC 9260                                                    | 7        | 7.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 6        | 6.67%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                          | 6        | 6.67%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                    | 4        | 4.44%   |
| Ralink RT2870/RT3070 Wireless Adapter                                     | 3        | 3.33%   |
| Intel Wireless 7265                                                       | 3        | 3.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                           | 2        | 2.22%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                | 2        | 2.22%   |
| NetGear A6210                                                             | 2        | 2.22%   |
| Microsoft XBOX ACC                                                        | 2        | 2.22%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter             | 2        | 2.22%   |
| Linksys AE6000 802.11a/b/g/n/ac Wireless Adapter [MediaTek MT7610U]       | 2        | 2.22%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                               | 1        | 1.11%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                              | 1        | 1.11%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                | 1        | 1.11%   |
| Sitecom Europe WLA-5000 802.11abgn [Ralink RT3572]                        | 1        | 1.11%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                        | 1        | 1.11%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                  | 1        | 1.11%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                       | 1        | 1.11%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                    | 1        | 1.11%   |
| Realtek RTL8188RU 802.11n WLAN Adapter                                    | 1        | 1.11%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                     | 1        | 1.11%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                       | 1        | 1.11%   |
| Realtek RTL8188EE Wireless Network Adapter                                | 1        | 1.11%   |
| Realtek 802.11n WLAN Adapter                                              | 1        | 1.11%   |
| Ralink Wireless Adapter Canyon CN-WF511                                   | 1        | 1.11%   |
| Ralink MT7601U Wireless Adapter                                           | 1        | 1.11%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                    | 1        | 1.11%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                | 1        | 1.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                | 1        | 1.11%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                          | 1        | 1.11%   |
| NetGear WNDA3100v1 802.11abgn [Atheros AR9170+AR9104]                     | 1        | 1.11%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1        | 1.11%   |
| Microsoft Wireless XBox Controller Dongle                                 | 1        | 1.11%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                   | 1        | 1.11%   |
| Linksys WUSB6300 V2                                                       | 1        | 1.11%   |
| Linksys WUSB54GC v1 802.11g Adapter [Ralink RT73]                         | 1        | 1.11%   |
| Intel Wireless 3165                                                       | 1        | 1.11%   |
| Intel Tiger Lake PCH CNVi WiFi                                            | 1        | 1.11%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 98       | 59.39%  |
| Intel                 | 45       | 27.27%  |
| Qualcomm Atheros      | 8        | 4.85%   |
| Aquantia              | 3        | 1.82%   |
| MediaTek              | 2        | 1.21%   |
| DisplayLink           | 2        | 1.21%   |
| Broadcom              | 2        | 1.21%   |
| Xiaomi                | 1        | 0.61%   |
| Samsung Electronics   | 1        | 0.61%   |
| Belkin Components     | 1        | 0.61%   |
| ASIX Electronics      | 1        | 0.61%   |
| Alteon Networks       | 1        | 0.61%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 82       | 48.81%  |
| Intel I211 Gigabit Network Connection                               | 17       | 10.12%  |
| Realtek RTL8125 2.5GbE Controller                                   | 13       | 7.74%   |
| Intel Ethernet Controller I225-V                                    | 10       | 5.95%   |
| Intel Ethernet Connection I217-LM                                   | 4        | 2.38%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 3        | 1.79%   |
| Intel Ethernet Connection (2) I219-V                                | 3        | 1.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 3        | 1.79%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 2        | 1.19%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 2        | 1.19%   |
| Intel Ethernet Connection (7) I219-V                                | 2        | 1.19%   |
| Intel 82579V Gigabit Network Connection                             | 2        | 1.19%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 2        | 1.19%   |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 1        | 0.6%    |
| Samsung Galaxy series, misc. (tethering mode)                       | 1        | 0.6%    |
| Realtek USB 10/100/1G/2.5G LAN                                      | 1        | 0.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 1        | 0.6%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter               | 1        | 0.6%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                    | 1        | 0.6%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller           | 1        | 0.6%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                          | 1        | 0.6%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet      | 1        | 0.6%    |
| MediaTek U318AA                                                     | 1        | 0.6%    |
| MediaTek KINGKONG_MINI                                              | 1        | 0.6%    |
| Intel Ethernet Connection I217-V                                    | 1        | 0.6%    |
| Intel Ethernet Connection (2) I219-LM                               | 1        | 0.6%    |
| Intel Ethernet Connection (2) I218-V                                | 1        | 0.6%    |
| Intel 82576 Gigabit Network Connection                              | 1        | 0.6%    |
| DisplayLink USB-C Hybrid UHD Video Dock                             | 1        | 0.6%    |
| DisplayLink ThinkPad USB 3.0 Dock                                   | 1        | 0.6%    |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express             | 1        | 0.6%    |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                     | 1        | 0.6%    |
| Belkin Components F5D5050 100Mbps Ethernet                          | 1        | 0.6%    |
| ASIX AX88179 Gigabit Ethernet                                       | 1        | 0.6%    |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.6%    |
| Alteon Networks Ethernet controller                                 | 1        | 0.6%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 147      | 63.64%  |
| WiFi     | 82       | 35.5%   |
| Modem    | 1        | 0.43%   |
| Unknown  | 1        | 0.43%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 113      | 72.9%   |
| WiFi     | 42       | 27.1%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 83       | 55.33%  |
| 2     | 55       | 36.67%  |
| 3     | 9        | 6%      |
| 0     | 2        | 1.33%   |
| 4     | 1        | 0.67%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 116      | 77.85%  |
| Yes  | 33       | 22.15%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 33       | 44%     |
| Cambridge Silicon Radio         | 14       | 18.67%  |
| Realtek Semiconductor           | 11       | 14.67%  |
| Qualcomm Atheros Communications | 5        | 6.67%   |
| ASUSTek Computer                | 5        | 6.67%   |
| Broadcom                        | 3        | 4%      |
| MediaTek                        | 2        | 2.67%   |
| IMC Networks                    | 1        | 1.33%   |
| Dynex                           | 1        | 1.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 14       | 18.67%  |
| Intel AX200 Bluetooth                                    | 11       | 14.67%  |
| Realtek Bluetooth Radio                                  | 8        | 10.67%  |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 7        | 9.33%   |
| Intel Wireless-AC 3168 Bluetooth                         | 6        | 8%      |
| Qualcomm Atheros  Bluetooth Device                       | 4        | 5.33%   |
| Realtek  Bluetooth 4.2 Adapter                           | 3        | 4%      |
| Intel Bluetooth wireless interface                       | 3        | 4%      |
| MediaTek Wireless_Device                                 | 2        | 2.67%   |
| Intel AX210 Bluetooth                                    | 2        | 2.67%   |
| Intel AX201 Bluetooth                                    | 2        | 2.67%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 2        | 2.67%   |
| ASUS Bluetooth Radio                                     | 2        | 2.67%   |
| Qualcomm Atheros AR3011 Bluetooth                        | 1        | 1.33%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 1        | 1.33%   |
| Intel Bluetooth Device                                   | 1        | 1.33%   |
| IMC Networks Bluetooth Radio                             | 1        | 1.33%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1        | 1.33%   |
| Broadcom BCM43142A0 Bluetooth Device                     | 1        | 1.33%   |
| ASUS Qualcomm Bluetooth 4.1                              | 1        | 1.33%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 1        | 1.33%   |
| ASUS ASUS USB-BT500                                      | 1        | 1.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| AMD                      | 94       | 32.19%  |
| Intel                    | 70       | 23.97%  |
| Nvidia                   | 63       | 21.58%  |
| C-Media Electronics      | 11       | 3.77%   |
| Logitech                 | 8        | 2.74%   |
| Kingston Technology      | 5        | 1.71%   |
| Texas Instruments        | 4        | 1.37%   |
| Trust                    | 3        | 1.03%   |
| Sony                     | 3        | 1.03%   |
| Blue Microphones         | 3        | 1.03%   |
| Yamaha                   | 2        | 0.68%   |
| JMTek                    | 2        | 0.68%   |
| Generalplus Technology   | 2        | 0.68%   |
| DSEA A/S                 | 2        | 0.68%   |
| Creative Labs            | 2        | 0.68%   |
| Tenx Technology          | 1        | 0.34%   |
| SteelSeries ApS          | 1        | 0.34%   |
| Samson Technologies      | 1        | 0.34%   |
| RODE Microphones         | 1        | 0.34%   |
| ROCCAT                   | 1        | 0.34%   |
| Razer USA                | 1        | 0.34%   |
| Plantronics              | 1        | 0.34%   |
| Micro Star International | 1        | 0.34%   |
| Hewlett-Packard          | 1        | 0.34%   |
| Harman International     | 1        | 0.34%   |
| Focusrite-Novation       | 1        | 0.34%   |
| EVGA                     | 1        | 0.34%   |
| DigiTech                 | 1        | 0.34%   |
| Digidesign               | 1        | 0.34%   |
| Creative Technology      | 1        | 0.34%   |
| Audio-Technica           | 1        | 0.34%   |
| Arturia                  | 1        | 0.34%   |
| Alesis                   | 1        | 0.34%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 34       | 9.37%   |
| AMD Family 17h/19h HD Audio Controller                                     | 17       | 4.68%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 15       | 4.13%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 15       | 4.13%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 13       | 3.58%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 11       | 3.03%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 11       | 3.03%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11       | 3.03%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 9        | 2.48%   |
| Nvidia GP104 High Definition Audio Controller                              | 8        | 2.2%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 8        | 2.2%    |
| AMD Navi 10 HDMI Audio                                                     | 8        | 2.2%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7        | 1.93%   |
| Intel 200 Series PCH HD Audio                                              | 7        | 1.93%   |
| Intel Cannon Lake PCH cAVS                                                 | 6        | 1.65%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 6        | 1.65%   |
| C-Media Electronics USB Audio Device                                       | 6        | 1.65%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 6        | 1.65%   |
| Nvidia TU116 High Definition Audio Controller                              | 5        | 1.38%   |
| Nvidia TU104 HD Audio Controller                                           | 5        | 1.38%   |
| Nvidia GM204 High Definition Audio Controller                              | 5        | 1.38%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 5        | 1.38%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 5        | 1.38%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 5        | 1.38%   |
| Texas Instruments PCM2902 Audio Codec                                      | 3        | 0.83%   |
| Sony DualShock 4 [CUH-ZCT2x]                                               | 3        | 0.83%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3        | 0.83%   |
| Nvidia GP106 High Definition Audio Controller                              | 3        | 0.83%   |
| Nvidia GP102 HDMI Audio Controller                                         | 3        | 0.83%   |
| Nvidia GM206 High Definition Audio Controller                              | 3        | 0.83%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 0.83%   |
| Nvidia GK106 HDMI Audio Controller                                         | 3        | 0.83%   |
| Nvidia GA104 High Definition Audio Controller                              | 3        | 0.83%   |
| Nvidia GA102 High Definition Audio Controller                              | 3        | 0.83%   |
| Kingston Technology HyperX QuadCast                                        | 3        | 0.83%   |
| Intel Comet Lake PCH-V cAVS                                                | 3        | 0.83%   |
| Intel Comet Lake PCH cAVS                                                  | 3        | 0.83%   |
| Blue Microphones Yeti Stereo Microphone                                    | 3        | 0.83%   |
| AMD FCH Azalia Controller                                                  | 3        | 0.83%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3        | 0.83%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| G.Skill                      | 22       | 25.29%  |
| Corsair                      | 14       | 16.09%  |
| Samsung Electronics          | 7        | 8.05%   |
| Kingston                     | 7        | 8.05%   |
| Crucial                      | 7        | 8.05%   |
| Unknown                      | 6        | 6.9%    |
| SK hynix                     | 6        | 6.9%    |
| Patriot                      | 6        | 6.9%    |
| Team                         | 2        | 2.3%    |
| Patriot Memory (PDP Systems) | 2        | 2.3%    |
| Micron Technology            | 2        | 2.3%    |
| A-DATA Technology            | 2        | 2.3%    |
| Unknown                      | 2        | 2.3%    |
| Ramaxel Technology           | 1        | 1.15%   |
| Apacer                       | 1        | 1.15%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                    | Desktops | Percent |
|--------------------------------------------------------------------------|----------|---------|
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s                     | 6        | 6.19%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s                    | 4        | 4.12%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s                      | 3        | 3.09%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s                     | 2        | 2.06%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s                     | 2        | 2.06%   |
| Patriot RAM 2666 C16 Series 4GB DIMM DDR4 2800MT/s                       | 2        | 2.06%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s                    | 2        | 2.06%   |
| Corsair RAM CMK32GX4M4B3200C16 8GB DIMM DDR4 3600MT/s                    | 2        | 2.06%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4                             | 2        | 2.06%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s                    | 2        | 2.06%   |
| Unknown                                                                  | 2        | 2.06%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                                | 1        | 1.03%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                                     | 1        | 1.03%   |
| Unknown RAM Module 8GB DIMM                                              | 1        | 1.03%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                                     | 1        | 1.03%   |
| Unknown RAM Module 4GB DIMM                                              | 1        | 1.03%   |
| Unknown RAM Module 1GB DIMM 1066MT/s                                     | 1        | 1.03%   |
| Unknown RAM 4400 C19 Series 8GB DIMM DDR4 2133MT/s                       | 1        | 1.03%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s                    | 1        | 1.03%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s                       | 1        | 1.03%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s                       | 1        | 1.03%   |
| SK hynix RAM HMT41GU6BFR8C-PB 8GB DIMM DDR3 1600MT/s                     | 1        | 1.03%   |
| SK hynix RAM HMAA2GU6CJR8N-XN 16GB DIMM DDR4 3200MT/s                    | 1        | 1.03%   |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s                                | 1        | 1.03%   |
| Samsung RAM Module 16GB DIMM DDR4 3200MT/s                               | 1        | 1.03%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s                    | 1        | 1.03%   |
| Samsung RAM M379B5273DH0-YK0 4GB DIMM DDR3 1600MT/s                      | 1        | 1.03%   |
| Samsung RAM M379B5273DH0-YK 4GB DIMM DDR3 1600MT/s                       | 1        | 1.03%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s                      | 1        | 1.03%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s                      | 1        | 1.03%   |
| Samsung RAM M378B1G73QH0-CK0 8GB DIMM DDR3 1600MT/s                      | 1        | 1.03%   |
| Samsung RAM M378B1G73EB0-CK0 8GB DIMM DDR3 1600MT/s                      | 1        | 1.03%   |
| Ramaxel RAM RMR5030MM58E8F1600 2GB DIMM DDR3 1600MT/s                    | 1        | 1.03%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s                           | 1        | 1.03%   |
| Patriot RAM Module 8GB DIMM DDR4 2666MT/s                                | 1        | 1.03%   |
| Patriot RAM 4000 C19 Series 8GB DIMM DDR4 4200MT/s                       | 1        | 1.03%   |
| Patriot RAM 2133 CL11 Series 8GB DIMM DDR3 2400MT/s                      | 1        | 1.03%   |
| Patriot RAM 1600 CL10 Series 8GB DIMM DDR3 1600MT/s                      | 1        | 1.03%   |
| Patriot Memory (PDP Systems) RAM 3600 C18 Series 16GB DIMM DDR4 3600MT/s | 1        | 1.03%   |
| Patriot Memory (PDP Systems) RAM 2666 C16 Series 4GB DIMM DDR4 2933MT/s  | 1        | 1.03%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 55       | 70.51%  |
| DDR3    | 17       | 21.79%  |
| Unknown | 4        | 5.13%   |
| DDR5    | 2        | 2.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 76       | 97.44%  |
| SODIMM | 2        | 2.56%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 46       | 51.69%  |
| 16384 | 21       | 23.6%   |
| 4096  | 15       | 16.85%  |
| 32768 | 5        | 5.62%   |
| 2048  | 1        | 1.12%   |
| 1024  | 1        | 1.12%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3600    | 16       | 18.18%  |
| 3200    | 9        | 10.23%  |
| 1600    | 9        | 10.23%  |
| 3466    | 6        | 6.82%   |
| 2400    | 6        | 6.82%   |
| 3666    | 5        | 5.68%   |
| 2666    | 4        | 4.55%   |
| 1333    | 4        | 4.55%   |
| 2667    | 3        | 3.41%   |
| 4800    | 2        | 2.27%   |
| 3866    | 2        | 2.27%   |
| 3800    | 2        | 2.27%   |
| 3000    | 2        | 2.27%   |
| 2933    | 2        | 2.27%   |
| 2800    | 2        | 2.27%   |
| 1800    | 2        | 2.27%   |
| 4266    | 1        | 1.14%   |
| 4200    | 1        | 1.14%   |
| 4000    | 1        | 1.14%   |
| 3733    | 1        | 1.14%   |
| 2200    | 1        | 1.14%   |
| 2133    | 1        | 1.14%   |
| 1867    | 1        | 1.14%   |
| 1866    | 1        | 1.14%   |
| 1200    | 1        | 1.14%   |
| 1066    | 1        | 1.14%   |
| 800     | 1        | 1.14%   |
| Unknown | 1        | 1.14%   |

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
| Logitech                      | 17       | 50%     |
| Microsoft                     | 5        | 14.71%  |
| Jieli Technology              | 3        | 8.82%   |
| Sunplus Innovation Technology | 2        | 5.88%   |
| Generalplus Technology        | 2        | 5.88%   |
| Z-Star Microelectronics       | 1        | 2.94%   |
| Trust                         | 1        | 2.94%   |
| Realtek Semiconductor         | 1        | 2.94%   |
| Razer USA                     | 1        | 2.94%   |
| MacroSilicon                  | 1        | 2.94%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Logitech Webcam C270              | 3        | 8.82%   |
| Logitech BRIO Ultra HD Webcam     | 3        | 8.82%   |
| Jieli USB PHY 2.0                 | 3        | 8.82%   |
| Sunplus FHD Camera                | 2        | 5.88%   |
| Microsoft LifeCam HD-5000         | 2        | 5.88%   |
| Logitech Webcam C930e             | 2        | 5.88%   |
| Logitech HD Webcam C910           | 2        | 5.88%   |
| Logitech HD Pro Webcam C920       | 2        | 5.88%   |
| Logitech C922 Pro Stream Webcam   | 2        | 5.88%   |
| Generalplus GENERAL WEBCAM        | 2        | 5.88%   |
| Z-Star A4 TECH USB2.0 PC Camera J | 1        | 2.94%   |
| Trust USB Camera                  | 1        | 2.94%   |
| Realtek FULL HD 1080P Webcam      | 1        | 2.94%   |
| Razer USA Razer Kiyo Pro          | 1        | 2.94%   |
| Microsoft Xbox NUI Camera         | 1        | 2.94%   |
| Microsoft LifeCam VX-2000         | 1        | 2.94%   |
| Microsoft LifeCam HD-3000         | 1        | 2.94%   |
| MacroSilicon USB Video            | 1        | 2.94%   |
| Logitech Webcam C925e             | 1        | 2.94%   |
| Logitech HD Webcam C510           | 1        | 2.94%   |
| Logitech C920 PRO HD Webcam       | 1        | 2.94%   |

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
| 0     | 74       | 49.01%  |
| 1     | 69       | 45.7%   |
| 2     | 7        | 4.64%   |
| 3     | 1        | 0.66%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 64       | 73.56%  |
| Net/wireless             | 10       | 11.49%  |
| Graphics card            | 8        | 9.2%    |
| Net/ethernet             | 3        | 3.45%   |
| Unassigned class         | 1        | 1.15%   |
| Multimedia controller    | 1        | 1.15%   |

