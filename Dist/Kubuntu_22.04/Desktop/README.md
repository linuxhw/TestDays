Kubuntu 22.04 - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for Kubuntu 22.04.

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

Total: 341

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | EB1036                      | [955d389e06](https://linux-hardware.org/?probe=955d389e06) | Mar 30, 2023 |
| Dell          | 0200DY A01                  | [722b28547b](https://linux-hardware.org/?probe=722b28547b) | Mar 28, 2023 |
| MSI           | B85-G43                     | [3dac8c76c2](https://linux-hardware.org/?probe=3dac8c76c2) | Mar 28, 2023 |
| Lenovo        | SHARKBAY SDK0J40709 WIN ... | [22e3e1831c](https://linux-hardware.org/?probe=22e3e1831c) | Mar 28, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [6553d2c85a](https://linux-hardware.org/?probe=6553d2c85a) | Mar 26, 2023 |
| ASUSTek       | PRIME Z590-A                | [9a8b9b917f](https://linux-hardware.org/?probe=9a8b9b917f) | Mar 24, 2023 |
| ASUSTek       | P8Z77-V LE                  | [c50deee021](https://linux-hardware.org/?probe=c50deee021) | Mar 24, 2023 |
| Lenovo        | SHARKBAY NOK                | [84f93bfcf1](https://linux-hardware.org/?probe=84f93bfcf1) | Mar 23, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [d9c0447b0d](https://linux-hardware.org/?probe=d9c0447b0d) | Mar 21, 2023 |
| HP            | 21F5                        | [865a85e5bc](https://linux-hardware.org/?probe=865a85e5bc) | Mar 20, 2023 |
| Intel         | DH67BL AAG10189-208         | [420f476f82](https://linux-hardware.org/?probe=420f476f82) | Mar 19, 2023 |
| Gigabyte      | B450 AORUS M                | [efaf7d4a30](https://linux-hardware.org/?probe=efaf7d4a30) | Mar 18, 2023 |
| Acer          | Aspire XC600 v1.0           | [ef3e267972](https://linux-hardware.org/?probe=ef3e267972) | Mar 18, 2023 |
| HP            | 8266                        | [8bac7f79e8](https://linux-hardware.org/?probe=8bac7f79e8) | Mar 17, 2023 |
| ASUSTek       | H81M-K                      | [9ca1015389](https://linux-hardware.org/?probe=9ca1015389) | Mar 16, 2023 |
| ASUSTek       | PRIME H510M-D               | [d1edfbc4b3](https://linux-hardware.org/?probe=d1edfbc4b3) | Mar 16, 2023 |
| Acer          | Aspire M3920                | [bb2e9ec8a1](https://linux-hardware.org/?probe=bb2e9ec8a1) | Mar 16, 2023 |
| Supermicro    | X9DRD-C/iT+                 | [57c78aa4db](https://linux-hardware.org/?probe=57c78aa4db) | Mar 15, 2023 |
| ASUSTek       | PRIME Z590-P                | [f424a1dc42](https://linux-hardware.org/?probe=f424a1dc42) | Mar 14, 2023 |
| ASUSTek       | H61M-K                      | [783ff991d4](https://linux-hardware.org/?probe=783ff991d4) | Mar 14, 2023 |
| MSI           | B85-G43                     | [7e9ce07cb8](https://linux-hardware.org/?probe=7e9ce07cb8) | Mar 13, 2023 |
| MSI           | B85-G43                     | [9a9a70ade3](https://linux-hardware.org/?probe=9a9a70ade3) | Mar 13, 2023 |
| Gigabyte      | B560M DS3H V2               | [77b7a9348b](https://linux-hardware.org/?probe=77b7a9348b) | Mar 12, 2023 |
| MSI           | MAG B660M BAZOOKA DDR4      | [cb1be19cd3](https://linux-hardware.org/?probe=cb1be19cd3) | Mar 11, 2023 |
| MSI           | B85-G43                     | [47ac638c2e](https://linux-hardware.org/?probe=47ac638c2e) | Mar 11, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [d039d459d7](https://linux-hardware.org/?probe=d039d459d7) | Mar 10, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | [fdc9f52c81](https://linux-hardware.org/?probe=fdc9f52c81) | Mar 08, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | [7bd6e95116](https://linux-hardware.org/?probe=7bd6e95116) | Mar 08, 2023 |
| Gigabyte      | B365M DS3H                  | [22569ee1f4](https://linux-hardware.org/?probe=22569ee1f4) | Mar 07, 2023 |
| Gigabyte      | EX58-UD5                    | [8805f0bce5](https://linux-hardware.org/?probe=8805f0bce5) | Mar 05, 2023 |
| Gigabyte      | B365M DS3H                  | [7d43df02db](https://linux-hardware.org/?probe=7d43df02db) | Mar 04, 2023 |
| ASUSTek       | P9X79                       | [9a3c215b30](https://linux-hardware.org/?probe=9a3c215b30) | Mar 03, 2023 |
| Gigabyte      | H410M H V3                  | [fdee05953f](https://linux-hardware.org/?probe=fdee05953f) | Mar 03, 2023 |
| ASRock        | B550M Steel Legend          | [8fd450db03](https://linux-hardware.org/?probe=8fd450db03) | Feb 28, 2023 |
| ASUSTek       | PRIME B450M-K               | [575e6a8c55](https://linux-hardware.org/?probe=575e6a8c55) | Feb 26, 2023 |
| ASRock        | H97 Pro4                    | [f703af2e6b](https://linux-hardware.org/?probe=f703af2e6b) | Feb 25, 2023 |
| ASRock        | M3A770DE                    | [b025c7a092](https://linux-hardware.org/?probe=b025c7a092) | Feb 24, 2023 |
| Gigabyte      | B365M DS3H                  | [463265c999](https://linux-hardware.org/?probe=463265c999) | Feb 24, 2023 |
| Gigabyte      | B365M DS3H                  | [4aec81f692](https://linux-hardware.org/?probe=4aec81f692) | Feb 24, 2023 |
| MSI           | B85-G43                     | [62273631b2](https://linux-hardware.org/?probe=62273631b2) | Feb 21, 2023 |
| ASRock        | 960GC-GS FX                 | [39718b8983](https://linux-hardware.org/?probe=39718b8983) | Feb 20, 2023 |
| Gigabyte      | X99-Ultra Gaming-CF         | [031c13ea35](https://linux-hardware.org/?probe=031c13ea35) | Feb 19, 2023 |
| ASUSTek       | H97-PLUS                    | [6824ee9944](https://linux-hardware.org/?probe=6824ee9944) | Feb 19, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [25c9923614](https://linux-hardware.org/?probe=25c9923614) | Feb 18, 2023 |
| ASRock        | B550M Steel Legend          | [b3c5c043ea](https://linux-hardware.org/?probe=b3c5c043ea) | Feb 18, 2023 |
| ASRock        | B550M Steel Legend          | [1c1470c8a2](https://linux-hardware.org/?probe=1c1470c8a2) | Feb 18, 2023 |
| MSI           | MAG B560 TOMAHAWK WIFI      | [6538791548](https://linux-hardware.org/?probe=6538791548) | Feb 17, 2023 |
| MSI           | MAG B560 TOMAHAWK WIFI      | [2da59271fe](https://linux-hardware.org/?probe=2da59271fe) | Feb 17, 2023 |
| Dell          | 0DF42J A00                  | [e192547cd3](https://linux-hardware.org/?probe=e192547cd3) | Feb 17, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [695abe8c65](https://linux-hardware.org/?probe=695abe8c65) | Feb 14, 2023 |
| ASUSTek       | Z10PE-D16 WS                | [d517411fc5](https://linux-hardware.org/?probe=d517411fc5) | Feb 13, 2023 |
| Gigabyte      | B560 HD3                    | [067646f7f8](https://linux-hardware.org/?probe=067646f7f8) | Feb 12, 2023 |
| HP            | 3397                        | [cc5cdaf09b](https://linux-hardware.org/?probe=cc5cdaf09b) | Feb 12, 2023 |
| ASUSTek       | Z10PE-D16 WS                | [b2c120d8d7](https://linux-hardware.org/?probe=b2c120d8d7) | Feb 11, 2023 |
| ASUSTek       | Z10PE-D16 WS                | [a19717f948](https://linux-hardware.org/?probe=a19717f948) | Feb 10, 2023 |
| Gigabyte      | B560 HD3                    | [b4fa86401f](https://linux-hardware.org/?probe=b4fa86401f) | Feb 09, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [ee5a11ee81](https://linux-hardware.org/?probe=ee5a11ee81) | Feb 08, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [5df3b5ad7e](https://linux-hardware.org/?probe=5df3b5ad7e) | Feb 08, 2023 |
| ASUSTek       | PRIME Z490-P                | [be25e0c930](https://linux-hardware.org/?probe=be25e0c930) | Feb 07, 2023 |
| ASUSTek       | PRIME Z490-P                | [d139473252](https://linux-hardware.org/?probe=d139473252) | Feb 07, 2023 |
| Dell          | 0WR7PY A02                  | [7dcb345b45](https://linux-hardware.org/?probe=7dcb345b45) | Feb 06, 2023 |
| Dell          | 0WR7PY A02                  | [8c3dd4055e](https://linux-hardware.org/?probe=8c3dd4055e) | Feb 06, 2023 |
| ASRock        | X300M-STX                   | [c614e44344](https://linux-hardware.org/?probe=c614e44344) | Feb 05, 2023 |
| ASRock        | X300M-STX                   | [ad59fdb4e4](https://linux-hardware.org/?probe=ad59fdb4e4) | Feb 05, 2023 |
| Lenovo        | NO DPK                      | [0abc762f30](https://linux-hardware.org/?probe=0abc762f30) | Jan 28, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [1a9e67408e](https://linux-hardware.org/?probe=1a9e67408e) | Jan 28, 2023 |
| ASUSTek       | PRIME H510M-E               | [fa464af5fb](https://linux-hardware.org/?probe=fa464af5fb) | Jan 27, 2023 |
| HP            | 3397                        | [764f737fcf](https://linux-hardware.org/?probe=764f737fcf) | Jan 27, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | [b7dea81a92](https://linux-hardware.org/?probe=b7dea81a92) | Jan 25, 2023 |
| ASRock        | B450M Pro4                  | [6462d71b74](https://linux-hardware.org/?probe=6462d71b74) | Jan 25, 2023 |
| Gigabyte      | X570S AORUS MASTER          | [a6f80e64b2](https://linux-hardware.org/?probe=a6f80e64b2) | Jan 21, 2023 |
| Gigabyte      | B365M DS3H                  | [29d770594e](https://linux-hardware.org/?probe=29d770594e) | Jan 21, 2023 |
| Dell          | 0WR7PY A02                  | [0072a47bce](https://linux-hardware.org/?probe=0072a47bce) | Jan 20, 2023 |
| ASUSTek       | P8Z68-V LX                  | [49f0bb23ea](https://linux-hardware.org/?probe=49f0bb23ea) | Jan 20, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [2b7ce5b726](https://linux-hardware.org/?probe=2b7ce5b726) | Jan 20, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [3dfd98d007](https://linux-hardware.org/?probe=3dfd98d007) | Jan 17, 2023 |
| Dell          | 0D881F A05                  | [0426ee9130](https://linux-hardware.org/?probe=0426ee9130) | Jan 17, 2023 |
| ASUSTek       | H110M-K                     | [dcbf101b59](https://linux-hardware.org/?probe=dcbf101b59) | Jan 17, 2023 |
| ASUSTek       | H110M-K                     | [3964c82d71](https://linux-hardware.org/?probe=3964c82d71) | Jan 17, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [86039b3063](https://linux-hardware.org/?probe=86039b3063) | Jan 15, 2023 |
| ASRock        | A320M-HDV R4.0              | [aa35c556bc](https://linux-hardware.org/?probe=aa35c556bc) | Jan 13, 2023 |
| ASUSTek       | Z97-P                       | [709045636c](https://linux-hardware.org/?probe=709045636c) | Jan 13, 2023 |
| ASUSTek       | G10AJ                       | [e300c19806](https://linux-hardware.org/?probe=e300c19806) | Jan 13, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | [1a619ff898](https://linux-hardware.org/?probe=1a619ff898) | Jan 10, 2023 |
| ASUSTek       | PRIME B450M-A II            | [c7a6fdbf55](https://linux-hardware.org/?probe=c7a6fdbf55) | Jan 06, 2023 |
| MSI           | MEG Z490 UNIFY              | [cb25b352e0](https://linux-hardware.org/?probe=cb25b352e0) | Jan 06, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | [e4f0b0506b](https://linux-hardware.org/?probe=e4f0b0506b) | Jan 06, 2023 |
| ASRock        | A320M-HDV R4.0              | [78ab02a131](https://linux-hardware.org/?probe=78ab02a131) | Jan 05, 2023 |
| Dell          | 0WPMFG A00                  | [02a8ab8bdc](https://linux-hardware.org/?probe=02a8ab8bdc) | Jan 05, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | [efb1372825](https://linux-hardware.org/?probe=efb1372825) | Jan 05, 2023 |
| Dell          | 096JG8 A01                  | [1c58ea8841](https://linux-hardware.org/?probe=1c58ea8841) | Jan 05, 2023 |
| Dell          | 096JG8 A01                  | [90cbbe6b1d](https://linux-hardware.org/?probe=90cbbe6b1d) | Jan 04, 2023 |
| Dell          | 096JG8 A01                  | [2e047c3ad5](https://linux-hardware.org/?probe=2e047c3ad5) | Jan 04, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [54403a8bbf](https://linux-hardware.org/?probe=54403a8bbf) | Jan 02, 2023 |
| ASUSTek       | G10DK                       | [e75694d9a6](https://linux-hardware.org/?probe=e75694d9a6) | Jan 02, 2023 |
| Gigabyte      | Z590 UD AC                  | [9346b2e1bc](https://linux-hardware.org/?probe=9346b2e1bc) | Jan 01, 2023 |
| Dell          | 0PTTT9 A00                  | [7f2851fcf5](https://linux-hardware.org/?probe=7f2851fcf5) | Dec 31, 2022 |
| HP            | 8399                        | [204c8c0a3f](https://linux-hardware.org/?probe=204c8c0a3f) | Dec 29, 2022 |
| Acer          | Aspire X3960                | [f045d61192](https://linux-hardware.org/?probe=f045d61192) | Dec 29, 2022 |
| Acer          | Aspire X3960                | [75e053c90f](https://linux-hardware.org/?probe=75e053c90f) | Dec 29, 2022 |
| Dell          | 0KWVT8 A03                  | [9d2542cf36](https://linux-hardware.org/?probe=9d2542cf36) | Dec 27, 2022 |
| Dell          | 0KWVT8 A03                  | [f2998cdede](https://linux-hardware.org/?probe=f2998cdede) | Dec 27, 2022 |
| Gigabyte      | 970-GAMING                  | [4a2d0b56d6](https://linux-hardware.org/?probe=4a2d0b56d6) | Dec 27, 2022 |
| Gigabyte      | 970-GAMING                  | [9df04c213d](https://linux-hardware.org/?probe=9df04c213d) | Dec 26, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [8d9b11c617](https://linux-hardware.org/?probe=8d9b11c617) | Dec 25, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [d66772a936](https://linux-hardware.org/?probe=d66772a936) | Dec 25, 2022 |
| Gigabyte      | 970-GAMING                  | [ef0c06d132](https://linux-hardware.org/?probe=ef0c06d132) | Dec 25, 2022 |
| Gigabyte      | 970-GAMING                  | [9de3d146ff](https://linux-hardware.org/?probe=9de3d146ff) | Dec 25, 2022 |
| ASUSTek       | X99-DELUXE                  | [3d538213fc](https://linux-hardware.org/?probe=3d538213fc) | Dec 25, 2022 |
| BESSTAR Te... | HM90                        | [3672c73d5a](https://linux-hardware.org/?probe=3672c73d5a) | Dec 24, 2022 |
| ASRock        | X570 Steel Legend           | [7b79249b18](https://linux-hardware.org/?probe=7b79249b18) | Dec 23, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | [841b610817](https://linux-hardware.org/?probe=841b610817) | Dec 23, 2022 |
| Gigabyte      | Z97M-DS3H                   | [dca79c9d6d](https://linux-hardware.org/?probe=dca79c9d6d) | Dec 21, 2022 |
| MSI           | X470 GAMING PLUS            | [44cdfa03bf](https://linux-hardware.org/?probe=44cdfa03bf) | Dec 19, 2022 |
| MSI           | B450M PRO-VDH MAX           | [d5d8eaf2b9](https://linux-hardware.org/?probe=d5d8eaf2b9) | Dec 19, 2022 |
| Dell          | 084J0R A00                  | [dabf78159d](https://linux-hardware.org/?probe=dabf78159d) | Dec 15, 2022 |
| Lenovo        | NOK                         | [01d1b7fdb7](https://linux-hardware.org/?probe=01d1b7fdb7) | Dec 15, 2022 |
| MSI           | A320M PRO-VD/S              | [9e9573c0c5](https://linux-hardware.org/?probe=9e9573c0c5) | Dec 14, 2022 |
| Lenovo        | ThinkCentre A70 7844H9G     | [aad5a91184](https://linux-hardware.org/?probe=aad5a91184) | Dec 14, 2022 |
| MSI           | A320M PRO-VD/S              | [c428800285](https://linux-hardware.org/?probe=c428800285) | Dec 14, 2022 |
| ASUSTek       | H170-PRO                    | [0a28fbd557](https://linux-hardware.org/?probe=0a28fbd557) | Dec 12, 2022 |
| Gigabyte      | B550M DS3H                  | [13434876df](https://linux-hardware.org/?probe=13434876df) | Dec 11, 2022 |
| ASRock        | B450M Pro4                  | [36ef5b0deb](https://linux-hardware.org/?probe=36ef5b0deb) | Dec 04, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [23f903a61d](https://linux-hardware.org/?probe=23f903a61d) | Dec 03, 2022 |
| Dell          | 084J0R A00                  | [57b5a73c5d](https://linux-hardware.org/?probe=57b5a73c5d) | Dec 01, 2022 |
| System76      | Thelio thelio-r1            | [76343aa234](https://linux-hardware.org/?probe=76343aa234) | Dec 01, 2022 |
| ASRock        | B75M-DGS                    | [ca277bb16c](https://linux-hardware.org/?probe=ca277bb16c) | Nov 30, 2022 |
| MSI           | Z370 GAMING PLUS            | [bd1c91dba9](https://linux-hardware.org/?probe=bd1c91dba9) | Nov 30, 2022 |
| ASRock        | A320M-HDV R4.0              | [3a64631617](https://linux-hardware.org/?probe=3a64631617) | Nov 30, 2022 |
| ASRock        | A320M-HDV R4.0              | [12492cb99a](https://linux-hardware.org/?probe=12492cb99a) | Nov 29, 2022 |
| Gigabyte      | H97-HD3                     | [7c2db201dc](https://linux-hardware.org/?probe=7c2db201dc) | Nov 24, 2022 |
| MSI           | B350 PC MATE                | [601fd47da1](https://linux-hardware.org/?probe=601fd47da1) | Nov 24, 2022 |
| Gigabyte      | H110M-S2H-CF                | [87c95f019e](https://linux-hardware.org/?probe=87c95f019e) | Nov 20, 2022 |
| Unknown       | Unknown                     | [554da2ef73](https://linux-hardware.org/?probe=554da2ef73) | Nov 18, 2022 |
| ASUSTek       | PRIME H510M-D               | [3491c5eef1](https://linux-hardware.org/?probe=3491c5eef1) | Nov 17, 2022 |
| ASRock        | B560M-ITX/ac                | [c8f725f9cd](https://linux-hardware.org/?probe=c8f725f9cd) | Nov 17, 2022 |
| ASUSTek       | STRIX Z270E GAMING          | [8e4ab9c969](https://linux-hardware.org/?probe=8e4ab9c969) | Nov 16, 2022 |
| Gigabyte      | H97-HD3                     | [b99ae215e4](https://linux-hardware.org/?probe=b99ae215e4) | Nov 14, 2022 |
| Gigabyte      | BOLD E3032                  | [9d013ae9aa](https://linux-hardware.org/?probe=9d013ae9aa) | Nov 14, 2022 |
| Gigabyte      | B660M GAMING DDR4           | [d22c86a486](https://linux-hardware.org/?probe=d22c86a486) | Nov 14, 2022 |
| Gigabyte      | GA-MA790FX-DS5              | [63bba2efec](https://linux-hardware.org/?probe=63bba2efec) | Nov 14, 2022 |
| Supermicro    | X9DAL                       | [56d4bd9f26](https://linux-hardware.org/?probe=56d4bd9f26) | Nov 13, 2022 |
| Foxconn       | 2ADA                        | [4ddae3c3a0](https://linux-hardware.org/?probe=4ddae3c3a0) | Nov 13, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [733739e049](https://linux-hardware.org/?probe=733739e049) | Nov 12, 2022 |
| Dell          | 0HY9JP A00                  | [fed46e3161](https://linux-hardware.org/?probe=fed46e3161) | Nov 12, 2022 |
| ASRock        | B75M                        | [7da4910326](https://linux-hardware.org/?probe=7da4910326) | Nov 12, 2022 |
| ASRock        | X99 Extreme4                | [00da120cde](https://linux-hardware.org/?probe=00da120cde) | Nov 11, 2022 |
| Dell          | 0773VG A00                  | [2ffe6c18f7](https://linux-hardware.org/?probe=2ffe6c18f7) | Nov 10, 2022 |
| Gigabyte      | B660M D3H DDR4              | [64aed4564c](https://linux-hardware.org/?probe=64aed4564c) | Nov 07, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [8ef47e1adb](https://linux-hardware.org/?probe=8ef47e1adb) | Nov 06, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [40a3de202d](https://linux-hardware.org/?probe=40a3de202d) | Nov 03, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [db852ba394](https://linux-hardware.org/?probe=db852ba394) | Nov 03, 2022 |
| ASUSTek       | M5A78L-M LX V2              | [50bd7a7436](https://linux-hardware.org/?probe=50bd7a7436) | Nov 01, 2022 |
| Shuttle       | FH61R                       | [26f86947ef](https://linux-hardware.org/?probe=26f86947ef) | Oct 30, 2022 |
| ASRock        | H61M-VS                     | [9a48b2a679](https://linux-hardware.org/?probe=9a48b2a679) | Oct 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [ac3b0eaf36](https://linux-hardware.org/?probe=ac3b0eaf36) | Oct 28, 2022 |
| HP            | 844C                        | [7e994c50c9](https://linux-hardware.org/?probe=7e994c50c9) | Oct 27, 2022 |
| ASUSTek       | M5A78L-M LE                 | [6954f669c5](https://linux-hardware.org/?probe=6954f669c5) | Oct 27, 2022 |
| ASUSTek       | PRIME X570-P                | [7910e04e13](https://linux-hardware.org/?probe=7910e04e13) | Oct 25, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | [bd3a8063b3](https://linux-hardware.org/?probe=bd3a8063b3) | Oct 25, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [285e8cd1a5](https://linux-hardware.org/?probe=285e8cd1a5) | Oct 25, 2022 |
| Gigabyte      | B365M D2V                   | [c852b8f3f7](https://linux-hardware.org/?probe=c852b8f3f7) | Oct 24, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [638c72b105](https://linux-hardware.org/?probe=638c72b105) | Oct 24, 2022 |
| ASUSTek       | STRIX Z270E GAMING          | [ca0e86eb6b](https://linux-hardware.org/?probe=ca0e86eb6b) | Oct 22, 2022 |
| MSI           | A320M PRO-M2 V2             | [7524f39579](https://linux-hardware.org/?probe=7524f39579) | Oct 19, 2022 |
| MSI           | H110M PRO-D                 | [d0580b46f2](https://linux-hardware.org/?probe=d0580b46f2) | Oct 18, 2022 |
| Lenovo        | ThinkCentre A70 7844H9G     | [1b0e52eddb](https://linux-hardware.org/?probe=1b0e52eddb) | Oct 18, 2022 |
| JWIPC         | A320I S1                    | [44689a88d8](https://linux-hardware.org/?probe=44689a88d8) | Oct 16, 2022 |
| Gigabyte      | Z68XP-UD3                   | [b36220c65b](https://linux-hardware.org/?probe=b36220c65b) | Oct 13, 2022 |
| ASRock        | A320M-HDV R4.0              | [20eebb7b05](https://linux-hardware.org/?probe=20eebb7b05) | Oct 12, 2022 |
| Gigabyte      | P55-US3L                    | [59843156e8](https://linux-hardware.org/?probe=59843156e8) | Oct 11, 2022 |
| ASRock        | Z170 Extreme4               | [b88e8a8b49](https://linux-hardware.org/?probe=b88e8a8b49) | Oct 11, 2022 |
| Gigabyte      | Z370P D3-CF                 | [71c916389e](https://linux-hardware.org/?probe=71c916389e) | Oct 09, 2022 |
| Acer          | Aspire G7750                | [bd21d9c12b](https://linux-hardware.org/?probe=bd21d9c12b) | Oct 09, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | [691aa10e89](https://linux-hardware.org/?probe=691aa10e89) | Oct 09, 2022 |
| Apple         | Mac-F221BEC8                | [51442982cd](https://linux-hardware.org/?probe=51442982cd) | Oct 07, 2022 |
| ASUSTek       | PRIME B450M-K II            | [1bf20fe68c](https://linux-hardware.org/?probe=1bf20fe68c) | Oct 05, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [99ed468a82](https://linux-hardware.org/?probe=99ed468a82) | Oct 05, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [e8b8141f03](https://linux-hardware.org/?probe=e8b8141f03) | Oct 05, 2022 |
| Dell          | 042P49 A02                  | [1ba8422c66](https://linux-hardware.org/?probe=1ba8422c66) | Oct 04, 2022 |
| MSI           | B450I GAMING PLUS AC        | [e857a28ed2](https://linux-hardware.org/?probe=e857a28ed2) | Oct 04, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [bc03e42377](https://linux-hardware.org/?probe=bc03e42377) | Oct 03, 2022 |
| Lenovo        | ThinkCentre M90p 5498A2U    | [61d1e2102b](https://linux-hardware.org/?probe=61d1e2102b) | Oct 03, 2022 |
| Lenovo        | ThinkCentre M90p 5498A2U    | [f05b832b90](https://linux-hardware.org/?probe=f05b832b90) | Oct 01, 2022 |
| Lenovo        | ThinkCentre M90p 5498A2U    | [d638b38369](https://linux-hardware.org/?probe=d638b38369) | Sep 30, 2022 |
| Dell          | 0GY6Y8 A02                  | [dad71b5547](https://linux-hardware.org/?probe=dad71b5547) | Sep 28, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [19fe9ebfb6](https://linux-hardware.org/?probe=19fe9ebfb6) | Sep 27, 2022 |
| ASRock        | 990FX Extreme9              | [c7522b70ba](https://linux-hardware.org/?probe=c7522b70ba) | Sep 27, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [3e14df6c26](https://linux-hardware.org/?probe=3e14df6c26) | Sep 27, 2022 |
| Gigabyte      | X399 AORUS XTREME-CF        | [762ad6e460](https://linux-hardware.org/?probe=762ad6e460) | Sep 26, 2022 |
| MSI           | Z590-A PRO                  | [72bd6750e5](https://linux-hardware.org/?probe=72bd6750e5) | Sep 25, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [60635ca9bc](https://linux-hardware.org/?probe=60635ca9bc) | Sep 24, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [2a7c09d404](https://linux-hardware.org/?probe=2a7c09d404) | Sep 24, 2022 |
| Gigabyte      | X570 GAMING X               | [07f9a5063e](https://linux-hardware.org/?probe=07f9a5063e) | Sep 23, 2022 |
| Biostar       | TA75MH2                     | [e76fb13311](https://linux-hardware.org/?probe=e76fb13311) | Sep 23, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [384ab44e0a](https://linux-hardware.org/?probe=384ab44e0a) | Sep 23, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [24c7d626c8](https://linux-hardware.org/?probe=24c7d626c8) | Sep 23, 2022 |
| ASUSTek       | Z97-PRO GAMER               | [f6e7ad269e](https://linux-hardware.org/?probe=f6e7ad269e) | Sep 22, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [256ff04106](https://linux-hardware.org/?probe=256ff04106) | Sep 20, 2022 |
| MSI           | Z390-A PRO                  | [9b0dd73d61](https://linux-hardware.org/?probe=9b0dd73d61) | Sep 20, 2022 |
| Supermicro    | SKAGIT09                    | [b7dcf8a06c](https://linux-hardware.org/?probe=b7dcf8a06c) | Sep 20, 2022 |
| Acer          | Aspire G7750                | [c54e28dc84](https://linux-hardware.org/?probe=c54e28dc84) | Sep 18, 2022 |
| Gigabyte      | B560M D3H                   | [515d75e6b7](https://linux-hardware.org/?probe=515d75e6b7) | Sep 17, 2022 |
| ASUSTek       | Z97-K                       | [3f362093da](https://linux-hardware.org/?probe=3f362093da) | Sep 16, 2022 |
| Gigabyte      | B450M DS3H-CF               | [ea2264656c](https://linux-hardware.org/?probe=ea2264656c) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [d79d03b7ef](https://linux-hardware.org/?probe=d79d03b7ef) | Sep 11, 2022 |
| ASRock        | H470M-HVS                   | [17e4855f90](https://linux-hardware.org/?probe=17e4855f90) | Sep 09, 2022 |
| Supermicro    | SKAGIT09                    | [d3f42d0c24](https://linux-hardware.org/?probe=d3f42d0c24) | Sep 08, 2022 |
| Gigabyte      | B450M DS3H-CF               | [557860ffbd](https://linux-hardware.org/?probe=557860ffbd) | Sep 07, 2022 |
| MSI           | B350 PC MATE                | [1f4f30c013](https://linux-hardware.org/?probe=1f4f30c013) | Sep 06, 2022 |
| MSI           | B450-A PRO MAX              | [0c89daf254](https://linux-hardware.org/?probe=0c89daf254) | Sep 03, 2022 |
| ASRock        | A320M-HDV                   | [5a9342d8e9](https://linux-hardware.org/?probe=5a9342d8e9) | Sep 03, 2022 |
| Dell          | 02YYK5 A00                  | [742579c33d](https://linux-hardware.org/?probe=742579c33d) | Sep 03, 2022 |
| OEM           | G41 775 ICH7 8712           | [4c9041cf15](https://linux-hardware.org/?probe=4c9041cf15) | Sep 03, 2022 |
| MSI           | 970 GAMING                  | [296c04b276](https://linux-hardware.org/?probe=296c04b276) | Sep 02, 2022 |
| MSI           | MAG B550M BAZOOKA           | [a1b5555512](https://linux-hardware.org/?probe=a1b5555512) | Sep 02, 2022 |
| Gigabyte      | B85M-HD3                    | [dcb5e7a20c](https://linux-hardware.org/?probe=dcb5e7a20c) | Aug 29, 2022 |
| Supermicro    | SKAGIT09                    | [3f4c6a4d48](https://linux-hardware.org/?probe=3f4c6a4d48) | Aug 29, 2022 |
| Pegatron      | 2AB6                        | [93af020634](https://linux-hardware.org/?probe=93af020634) | Aug 27, 2022 |
| ASRock        | B450M/ac R2.0               | [ede2f61f08](https://linux-hardware.org/?probe=ede2f61f08) | Aug 26, 2022 |
| MSI           | B450-A PRO                  | [36f10ad555](https://linux-hardware.org/?probe=36f10ad555) | Aug 24, 2022 |
| ASUSTek       | B85-PLUS                    | [1eba4b558d](https://linux-hardware.org/?probe=1eba4b558d) | Aug 23, 2022 |
| Gigabyte      | BOLD E3032                  | [4b70fe47a2](https://linux-hardware.org/?probe=4b70fe47a2) | Aug 23, 2022 |
| Gigabyte      | H410M S2 V2                 | [cb43b7a4cf](https://linux-hardware.org/?probe=cb43b7a4cf) | Aug 22, 2022 |
| Gigabyte      | H97-Gaming 3                | [c084ff3123](https://linux-hardware.org/?probe=c084ff3123) | Aug 22, 2022 |
| Supermicro    | SKAGIT09                    | [1ae2767db3](https://linux-hardware.org/?probe=1ae2767db3) | Aug 22, 2022 |
| MSI           | B350 PC MATE                | [e058dec94d](https://linux-hardware.org/?probe=e058dec94d) | Aug 19, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [dd98185972](https://linux-hardware.org/?probe=dd98185972) | Aug 16, 2022 |
| ASUSTek       | H170M-PLUS/BR               | [feb4e50ec5](https://linux-hardware.org/?probe=feb4e50ec5) | Aug 16, 2022 |
| Lenovo        | Bantry CRB SDK0J40700 WI... | [792eb4143f](https://linux-hardware.org/?probe=792eb4143f) | Aug 16, 2022 |
| MSI           | B350 PC MATE                | [646d091037](https://linux-hardware.org/?probe=646d091037) | Aug 15, 2022 |
| HP            | 805D                        | [54f4e0fdb0](https://linux-hardware.org/?probe=54f4e0fdb0) | Aug 14, 2022 |
| Dell          | 0C2XKD A01                  | [cfad241ca0](https://linux-hardware.org/?probe=cfad241ca0) | Aug 12, 2022 |
| Positivo      | POS-PARS760GCD POSITIVO     | [dc6e65929f](https://linux-hardware.org/?probe=dc6e65929f) | Aug 12, 2022 |
| HP            | 8459                        | [677ca01f4f](https://linux-hardware.org/?probe=677ca01f4f) | Aug 11, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | [d2f7a86fd8](https://linux-hardware.org/?probe=d2f7a86fd8) | Aug 11, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | [6eac3041ec](https://linux-hardware.org/?probe=6eac3041ec) | Aug 07, 2022 |
| MSI           | B550-A PRO                  | [fb01882d07](https://linux-hardware.org/?probe=fb01882d07) | Aug 06, 2022 |
| MSI           | Z97 GAMING 7                | [01cf6a0897](https://linux-hardware.org/?probe=01cf6a0897) | Aug 06, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | [1340311493](https://linux-hardware.org/?probe=1340311493) | Aug 06, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [6fa2b142e4](https://linux-hardware.org/?probe=6fa2b142e4) | Aug 06, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [e5e72c1264](https://linux-hardware.org/?probe=e5e72c1264) | Aug 05, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [d725206bff](https://linux-hardware.org/?probe=d725206bff) | Aug 04, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [42469385bc](https://linux-hardware.org/?probe=42469385bc) | Aug 04, 2022 |
| ASUSTek       | P8H67                       | [b1b842e547](https://linux-hardware.org/?probe=b1b842e547) | Jul 29, 2022 |
| ASUSTek       | GRYPHON Z87                 | [73b9d340d2](https://linux-hardware.org/?probe=73b9d340d2) | Jul 28, 2022 |
| ASUSTek       | PRIME X370-PRO              | [ee8688ecdb](https://linux-hardware.org/?probe=ee8688ecdb) | Jul 26, 2022 |
| ASRock        | Z270 Gaming K4              | [63612e20b4](https://linux-hardware.org/?probe=63612e20b4) | Jul 26, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [5658129aa4](https://linux-hardware.org/?probe=5658129aa4) | Jul 24, 2022 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | [ba1841221c](https://linux-hardware.org/?probe=ba1841221c) | Jul 24, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [021e469888](https://linux-hardware.org/?probe=021e469888) | Jul 23, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [ea90d78c53](https://linux-hardware.org/?probe=ea90d78c53) | Jul 23, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [6e6e65c711](https://linux-hardware.org/?probe=6e6e65c711) | Jul 23, 2022 |
| Gigabyte      | P35-DS3L                    | [4ae76fafc9](https://linux-hardware.org/?probe=4ae76fafc9) | Jul 22, 2022 |
| Shuttle       | NC01U V1.0                  | [827d6c81ae](https://linux-hardware.org/?probe=827d6c81ae) | Jul 22, 2022 |
| Shuttle       | NC01U V1.0                  | [fecfaf6008](https://linux-hardware.org/?probe=fecfaf6008) | Jul 21, 2022 |
| HP            | 18E9                        | [f15b2671b0](https://linux-hardware.org/?probe=f15b2671b0) | Jul 21, 2022 |
| ASRock        | B550 Extreme4               | [226924706f](https://linux-hardware.org/?probe=226924706f) | Jul 20, 2022 |
| Gigabyte      | P35-DS3L                    | [cabd591648](https://linux-hardware.org/?probe=cabd591648) | Jul 20, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | [0e3950303c](https://linux-hardware.org/?probe=0e3950303c) | Jul 18, 2022 |
| ASRock        | Z170 Extreme4               | [4f4b63a026](https://linux-hardware.org/?probe=4f4b63a026) | Jul 18, 2022 |
| Acer          | Predator PO3-620            | [f3e22c0e6d](https://linux-hardware.org/?probe=f3e22c0e6d) | Jul 18, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [01d595926f](https://linux-hardware.org/?probe=01d595926f) | Jul 15, 2022 |
| MSI           | X99A XPOWER GAMING TITAN... | [e764729eeb](https://linux-hardware.org/?probe=e764729eeb) | Jul 13, 2022 |
| ASRock        | Z170 Extreme4               | [7ecf3ad1b7](https://linux-hardware.org/?probe=7ecf3ad1b7) | Jul 13, 2022 |
| ASRock        | B550 Extreme4               | [6106db3d9a](https://linux-hardware.org/?probe=6106db3d9a) | Jul 12, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | [fafb6deae6](https://linux-hardware.org/?probe=fafb6deae6) | Jul 12, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | [d6531258d0](https://linux-hardware.org/?probe=d6531258d0) | Jul 11, 2022 |
| ASRock        | B550 Taichi                 | [61fe809791](https://linux-hardware.org/?probe=61fe809791) | Jul 10, 2022 |
| Gigabyte      | Z77-D3H                     | [f9e15346d3](https://linux-hardware.org/?probe=f9e15346d3) | Jul 10, 2022 |
| ASUSTek       | P9X79 PRO                   | [d7e1136386](https://linux-hardware.org/?probe=d7e1136386) | Jul 07, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | [7d5d5c1a7e](https://linux-hardware.org/?probe=7d5d5c1a7e) | Jul 02, 2022 |
| HP            | 8459                        | [f43fdff127](https://linux-hardware.org/?probe=f43fdff127) | Jul 01, 2022 |
| ASUSTek       | ET2400A                     | [8801791f80](https://linux-hardware.org/?probe=8801791f80) | Jul 01, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [33c8a42a4d](https://linux-hardware.org/?probe=33c8a42a4d) | Jun 29, 2022 |
| Gigabyte      | X570 AORUS PRO              | [757741fe0d](https://linux-hardware.org/?probe=757741fe0d) | Jun 29, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [efb8cff806](https://linux-hardware.org/?probe=efb8cff806) | Jun 28, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [a6555d107c](https://linux-hardware.org/?probe=a6555d107c) | Jun 27, 2022 |
| ASRock        | A320M Pro4                  | [e1918d8aab](https://linux-hardware.org/?probe=e1918d8aab) | Jun 25, 2022 |
| Huanan        | X99-F8 GAMING V5.0          | [2688876fc9](https://linux-hardware.org/?probe=2688876fc9) | Jun 25, 2022 |
| ASRock        | A320M Pro4                  | [f4f2e68e79](https://linux-hardware.org/?probe=f4f2e68e79) | Jun 24, 2022 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [04e6f0ee4a](https://linux-hardware.org/?probe=04e6f0ee4a) | Jun 24, 2022 |
| ABIT          | IP35 Pro                    | [a5f262c233](https://linux-hardware.org/?probe=a5f262c233) | Jun 23, 2022 |
| ASUSTek       | P8P67 LE                    | [8e1bc37281](https://linux-hardware.org/?probe=8e1bc37281) | Jun 19, 2022 |
| ASRock        | X570M Pro4                  | [bbb784f2df](https://linux-hardware.org/?probe=bbb784f2df) | Jun 18, 2022 |
| Dell          | 0YNVJG A01                  | [b75bebfda2](https://linux-hardware.org/?probe=b75bebfda2) | Jun 18, 2022 |
| ASUSTek       | X99-A/USB                   | [3ad17f6d78](https://linux-hardware.org/?probe=3ad17f6d78) | Jun 16, 2022 |
| ASUSTek       | P5QC                        | [b9a53514e1](https://linux-hardware.org/?probe=b9a53514e1) | Jun 16, 2022 |
| MSI           | Z270 GAMING M5              | [d5f742022e](https://linux-hardware.org/?probe=d5f742022e) | Jun 16, 2022 |
| MSI           | Z270 GAMING M5              | [6c352cf792](https://linux-hardware.org/?probe=6c352cf792) | Jun 16, 2022 |
| Gigabyte      | B450M DS3H-CF               | [2b307211cd](https://linux-hardware.org/?probe=2b307211cd) | Jun 14, 2022 |
| Dell          | 0KC9NP A01                  | [c573376df6](https://linux-hardware.org/?probe=c573376df6) | Jun 11, 2022 |
| Gigabyte      | Z270-HD3P-CF                | [317ae1383a](https://linux-hardware.org/?probe=317ae1383a) | Jun 10, 2022 |
| ASRock        | X570M Pro4                  | [4f6d06171b](https://linux-hardware.org/?probe=4f6d06171b) | Jun 10, 2022 |
| AZW           | Gemini J45                  | [f4d7238f95](https://linux-hardware.org/?probe=f4d7238f95) | Jun 08, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [15f48b1e64](https://linux-hardware.org/?probe=15f48b1e64) | Jun 08, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [9bc79127f3](https://linux-hardware.org/?probe=9bc79127f3) | Jun 06, 2022 |
| Dell          | 0Y2MRG A00                  | [11bba01e79](https://linux-hardware.org/?probe=11bba01e79) | Jun 06, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | [70f49afd95](https://linux-hardware.org/?probe=70f49afd95) | Jun 04, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | [95173b9d90](https://linux-hardware.org/?probe=95173b9d90) | Jun 04, 2022 |
| ASUSTek       | M5A78L LE                   | [8eda28a8d4](https://linux-hardware.org/?probe=8eda28a8d4) | May 30, 2022 |
| ASUSTek       | P7H55-M LE                  | [4f55b87c44](https://linux-hardware.org/?probe=4f55b87c44) | May 28, 2022 |
| Gigabyte      | B85M-D2V                    | [2bc6293c6a](https://linux-hardware.org/?probe=2bc6293c6a) | May 19, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [93b08c2d75](https://linux-hardware.org/?probe=93b08c2d75) | May 19, 2022 |
| ASRock        | B560M Pro4                  | [ba3b29db98](https://linux-hardware.org/?probe=ba3b29db98) | May 18, 2022 |
| Gigabyte      | B85M-D2V                    | [da9da96cda](https://linux-hardware.org/?probe=da9da96cda) | May 17, 2022 |
| ASUSTek       | M5A78L LE                   | [697a89162e](https://linux-hardware.org/?probe=697a89162e) | May 16, 2022 |
| Dell          | 0KJCC5 A00                  | [bb68e24835](https://linux-hardware.org/?probe=bb68e24835) | May 15, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [0ec606b729](https://linux-hardware.org/?probe=0ec606b729) | May 14, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [6fdf1cd28c](https://linux-hardware.org/?probe=6fdf1cd28c) | May 14, 2022 |
| MSI           | B450M PRO-M2                | [0bb720a248](https://linux-hardware.org/?probe=0bb720a248) | May 14, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [fb2a9c9ddf](https://linux-hardware.org/?probe=fb2a9c9ddf) | May 13, 2022 |
| MSI           | B450M MORTAR TITANIUM       | [b03899e10b](https://linux-hardware.org/?probe=b03899e10b) | May 13, 2022 |
| Lenovo        | SHARKBAY NOK                | [7923c29010](https://linux-hardware.org/?probe=7923c29010) | May 11, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | [76cc09b228](https://linux-hardware.org/?probe=76cc09b228) | May 10, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | [6500cb78c3](https://linux-hardware.org/?probe=6500cb78c3) | May 10, 2022 |
| HP            | 1998                        | [7f82a04d73](https://linux-hardware.org/?probe=7f82a04d73) | May 10, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [5f90cb38d2](https://linux-hardware.org/?probe=5f90cb38d2) | May 07, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [0b27354c9c](https://linux-hardware.org/?probe=0b27354c9c) | May 05, 2022 |
| Gigabyte      | Z370P D3-CF                 | [8a561e2442](https://linux-hardware.org/?probe=8a561e2442) | May 05, 2022 |
| Gigabyte      | X570 GAMING X               | [53a75b2d5c](https://linux-hardware.org/?probe=53a75b2d5c) | May 04, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [62f9f79f7c](https://linux-hardware.org/?probe=62f9f79f7c) | May 03, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [afce1937fe](https://linux-hardware.org/?probe=afce1937fe) | May 03, 2022 |
| ASUSTek       | P8B75-M                     | [dadde1bbc0](https://linux-hardware.org/?probe=dadde1bbc0) | May 02, 2022 |
| Supermicro    | X8ST3                       | [a94462f4b5](https://linux-hardware.org/?probe=a94462f4b5) | May 02, 2022 |
| ASUSTek       | PRIME B550M-K               | [92c09fc927](https://linux-hardware.org/?probe=92c09fc927) | Apr 30, 2022 |
| ASRock        | B550 Extreme4               | [7a90a198f5](https://linux-hardware.org/?probe=7a90a198f5) | Apr 30, 2022 |
| ASUSTek       | M5A78L LE                   | [9328531b5a](https://linux-hardware.org/?probe=9328531b5a) | Apr 30, 2022 |
| Lenovo        | 36C5 SDK0J40700 WIN 3258... | [d9ac32b17d](https://linux-hardware.org/?probe=d9ac32b17d) | Apr 30, 2022 |
| Biostar       | A68N-2100K                  | [db9760ae3a](https://linux-hardware.org/?probe=db9760ae3a) | Apr 27, 2022 |
| Biostar       | A68N-2100K                  | [87d629883f](https://linux-hardware.org/?probe=87d629883f) | Apr 27, 2022 |
| HP            | 0AACh                       | [f9e511945d](https://linux-hardware.org/?probe=f9e511945d) | Apr 25, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [4b41ff5fb9](https://linux-hardware.org/?probe=4b41ff5fb9) | Apr 24, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [3d513e3c6c](https://linux-hardware.org/?probe=3d513e3c6c) | Mar 24, 2022 |
| Dell          | 0K240Y A02                  | [b5783c7fa0](https://linux-hardware.org/?probe=b5783c7fa0) | Mar 03, 2022 |
| Gigabyte      | H410M S2H V3                | [e5da146c8e](https://linux-hardware.org/?probe=e5da146c8e) | Feb 27, 2022 |
| Gigabyte      | B550M DS3H                  | [21a8a676d1](https://linux-hardware.org/?probe=21a8a676d1) | Dec 28, 2021 |
| Gigabyte      | B550M DS3H                  | [61561f50ba](https://linux-hardware.org/?probe=61561f50ba) | Dec 28, 2021 |
| Gigabyte      | P35-DS3L                    | [e13fea24e4](https://linux-hardware.org/?probe=e13fea24e4) | Dec 27, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [1c12810a81](https://linux-hardware.org/?probe=1c12810a81) | Dec 06, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [acadafa3aa](https://linux-hardware.org/?probe=acadafa3aa) | Nov 30, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 5.15.0-56-generic      | 22       | 8.03%   |
| 5.15.0-52-generic      | 19       | 6.93%   |
| 5.15.0-43-generic      | 18       | 6.57%   |
| 5.15.0-48-generic      | 14       | 5.11%   |
| 5.15.0-46-generic      | 13       | 4.74%   |
| 5.19.0-35-generic      | 12       | 4.38%   |
| 5.15.0-47-generic      | 12       | 4.38%   |
| 5.15.0-27-generic      | 12       | 4.38%   |
| 5.15.0-40-generic      | 11       | 4.01%   |
| 5.15.0-67-generic      | 10       | 3.65%   |
| 5.15.0-58-generic      | 10       | 3.65%   |
| 5.15.0-41-generic      | 10       | 3.65%   |
| 5.15.0-53-generic      | 9        | 3.28%   |
| 5.15.0-25-generic      | 9        | 3.28%   |
| 5.15.0-60-generic      | 8        | 2.92%   |
| 5.15.0-50-generic      | 7        | 2.55%   |
| 5.15.0-30-generic      | 6        | 2.19%   |
| 5.15.0-48-lowlatency   | 5        | 1.82%   |
| 5.15.0-56-lowlatency   | 4        | 1.46%   |
| 5.15.0-37-generic      | 4        | 1.46%   |
| 5.15.0-33-generic      | 4        | 1.46%   |
| 5.19.0-32-generic      | 3        | 1.09%   |
| 5.15.0-57-generic      | 3        | 1.09%   |
| 5.15.0-27-lowlatency   | 3        | 1.09%   |
| 5.15.0-69-generic      | 2        | 0.73%   |
| 5.15.0-58-lowlatency   | 2        | 0.73%   |
| 5.15.0-52-lowlatency   | 2        | 0.73%   |
| 5.15.0-47-lowlatency   | 2        | 0.73%   |
| 5.15.0-43-lowlatency   | 2        | 0.73%   |
| 5.15.0-39-generic      | 2        | 0.73%   |
| 6.1.5-x64v3-xanmod1    | 1        | 0.36%   |
| 6.1.5-060105-generic   | 1        | 0.36%   |
| 6.0.1-060001-generic   | 1        | 0.36%   |
| 6.0.0                  | 1        | 0.36%   |
| 5.4.0-122-generic      | 1        | 0.36%   |
| 5.19.12-xanmod1        | 1        | 0.36%   |
| 5.19.0-38-generic      | 1        | 0.36%   |
| 5.18.4-xanmod1         | 1        | 0.36%   |
| 5.18.4-vitodoc         | 1        | 0.36%   |
| 5.18.19-051819-generic | 1        | 0.36%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 225      | 86.21%  |
| 5.19.0  | 15       | 5.75%   |
| 5.17.0  | 4        | 1.53%   |
| 6.1.5   | 2        | 0.77%   |
| 5.18.4  | 2        | 0.77%   |
| 5.13.0  | 2        | 0.77%   |
| 6.0.1   | 1        | 0.38%   |
| 6.0.0   | 1        | 0.38%   |
| 5.4.0   | 1        | 0.38%   |
| 5.19.12 | 1        | 0.38%   |
| 5.18.19 | 1        | 0.38%   |
| 5.18.12 | 1        | 0.38%   |
| 5.18.10 | 1        | 0.38%   |
| 5.17.6  | 1        | 0.38%   |
| 5.17.14 | 1        | 0.38%   |
| 5.16.0  | 1        | 0.38%   |
| 5.15.13 | 1        | 0.38%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 226      | 86.59%  |
| 5.19    | 16       | 6.13%   |
| 5.17    | 6        | 2.3%    |
| 5.18    | 5        | 1.92%   |
| 6.1     | 2        | 0.77%   |
| 6.0     | 2        | 0.77%   |
| 5.13    | 2        | 0.77%   |
| 5.4     | 1        | 0.38%   |
| 5.16    | 1        | 0.38%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 257      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| KDE5   | 253      | 98.44%  |
| GNOME  | 2        | 0.78%   |
| KDE    | 1        | 0.39%   |
| Budgie | 1        | 0.39%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 246      | 95.72%  |
| Wayland | 6        | 2.33%   |
| Tty     | 4        | 1.56%   |
| Web     | 1        | 0.39%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 178      | 68.73%  |
| Unknown | 53       | 20.46%  |
| GDM3    | 20       | 7.72%   |
| LightDM | 7        | 2.7%    |
| GDM     | 1        | 0.39%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang   | Desktops | Percent |
|--------|----------|---------|
| en_US  | 115      | 44.75%  |
| fr_FR  | 24       | 9.34%   |
| de_DE  | 23       | 8.95%   |
| ru_RU  | 14       | 5.45%   |
| it_IT  | 13       | 5.06%   |
| en_GB  | 9        | 3.5%    |
| pt_BR  | 8        | 3.11%   |
| en_AU  | 8        | 3.11%   |
| pl_PL  | 6        | 2.33%   |
| en_CA  | 4        | 1.56%   |
| nl_NL  | 3        | 1.17%   |
| es_ES  | 3        | 1.17%   |
| es_AR  | 2        | 0.78%   |
| en_ZA  | 2        | 0.78%   |
| en_PH  | 2        | 0.78%   |
| en_NZ  | 2        | 0.78%   |
| en_IN  | 2        | 0.78%   |
| de_CH  | 2        | 0.78%   |
| cs_CZ  | 2        | 0.78%   |
| C      | 2        | 0.78%   |
| sl_SI  | 1        | 0.39%   |
| osa_US | 1        | 0.39%   |
| fr_BE  | 1        | 0.39%   |
| fi_FI  | 1        | 0.39%   |
| es_VE  | 1        | 0.39%   |
| es_CO  | 1        | 0.39%   |
| en_IL  | 1        | 0.39%   |
| en_AG  | 1        | 0.39%   |
| el_GR  | 1        | 0.39%   |
| de_LU  | 1        | 0.39%   |
| de_AT  | 1        | 0.39%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 148      | 57.36%  |
| EFI  | 110      | 42.64%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 230      | 89.49%  |
| Btrfs   | 13       | 5.06%   |
| Overlay | 12       | 4.67%   |
| Xfs     | 1        | 0.39%   |
| Ext3    | 1        | 0.39%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 152      | 58.24%  |
| Unknown | 83       | 31.8%   |
| MBR     | 26       | 9.96%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 219      | 84.23%  |
| Yes       | 41       | 15.77%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 155      | 60.31%  |
| Yes       | 102      | 39.69%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 70       | 27.24%  |
| Gigabyte Technology | 52       | 20.23%  |
| MSI                 | 35       | 13.62%  |
| ASRock              | 26       | 10.12%  |
| Dell                | 21       | 8.17%   |
| Lenovo              | 13       | 5.06%   |
| Hewlett-Packard     | 11       | 4.28%   |
| Supermicro          | 5        | 1.95%   |
| Acer                | 5        | 1.95%   |
| Shuttle             | 2        | 0.78%   |
| Fujitsu             | 2        | 0.78%   |
| Biostar             | 2        | 0.78%   |
| Apple               | 2        | 0.78%   |
| Positivo            | 1        | 0.39%   |
| Pegatron            | 1        | 0.39%   |
| OEM                 | 1        | 0.39%   |
| JWIPC               | 1        | 0.39%   |
| Intel               | 1        | 0.39%   |
| Huanan              | 1        | 0.39%   |
| Foxconn             | 1        | 0.39%   |
| BESSTAR Tech        | 1        | 0.39%   |
| AZW                 | 1        | 0.39%   |
| ABIT                | 1        | 0.39%   |
| Unknown             | 1        | 0.39%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| ASUS All Series                | 9        | 3.5%    |
| ASUS ROG STRIX B550-F GAMING   | 5        | 1.95%   |
| MSI MS-7B79                    | 4        | 1.56%   |
| Gigabyte B450M DS3H            | 3        | 1.17%   |
| Dell OptiPlex 7010             | 3        | 1.17%   |
| Supermicro SKAGIT09            | 2        | 0.78%   |
| MSI MS-7C95                    | 2        | 0.78%   |
| MSI MS-7C56                    | 2        | 0.78%   |
| MSI MS-7B86                    | 2        | 0.78%   |
| MSI MS-7B84                    | 2        | 0.78%   |
| HP Compaq Elite 8300 SFF       | 2        | 0.78%   |
| Gigabyte X570 GAMING X         | 2        | 0.78%   |
| Gigabyte B450 I AORUS PRO WIFI | 2        | 0.78%   |
| Dell OptiPlex 7040             | 2        | 0.78%   |
| ASUS STRIX Z270E GAMING        | 2        | 0.78%   |
| ASUS ROG ZENITH EXTREME        | 2        | 0.78%   |
| ASUS ROG STRIX X570-E GAMING   | 2        | 0.78%   |
| ASUS ROG STRIX B550-I GAMING   | 2        | 0.78%   |
| ASRock B450M Pro4              | 2        | 0.78%   |
| ASRock A320M-HDV R4.0          | 2        | 0.78%   |
| Supermicro X9DAL               | 1        | 0.39%   |
| Supermicro X8ST3               | 1        | 0.39%   |
| Supermicro PIO-1UDP10-01-AI036 | 1        | 0.39%   |
| Shuttle SH61R                  | 1        | 0.39%   |
| Shuttle NC01U                  | 1        | 0.39%   |
| Positivo POS-PARS760GCD        | 1        | 0.39%   |
| Pegatron p6740la               | 1        | 0.39%   |
| OEM G41 775 ICH7 8712          | 1        | 0.39%   |
| MSI MS-7D75                    | 1        | 0.39%   |
| MSI MS-7D54                    | 1        | 0.39%   |
| MSI MS-7D43                    | 1        | 0.39%   |
| MSI MS-7D15                    | 1        | 0.39%   |
| MSI MS-7D09                    | 1        | 0.39%   |
| MSI MS-7C80                    | 1        | 0.39%   |
| MSI MS-7C71                    | 1        | 0.39%   |
| MSI MS-7C37                    | 1        | 0.39%   |
| MSI MS-7B98                    | 1        | 0.39%   |
| MSI MS-7B89                    | 1        | 0.39%   |
| MSI MS-7B61                    | 1        | 0.39%   |
| MSI MS-7B17                    | 1        | 0.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| ASUS ROG                       | 18       | 7%      |
| ASUS PRIME                     | 13       | 5.06%   |
| Dell OptiPlex                  | 11       | 4.28%   |
| ASUS All                       | 9        | 3.5%    |
| Lenovo ThinkCentre             | 8        | 3.11%   |
| ASUS TUF                       | 6        | 2.33%   |
| MSI MS-7B79                    | 4        | 1.56%   |
| Lenovo IdeaCentre              | 4        | 1.56%   |
| Gigabyte X570                  | 4        | 1.56%   |
| Gigabyte B450                  | 4        | 1.56%   |
| Dell XPS                       | 4        | 1.56%   |
| Dell Precision                 | 4        | 1.56%   |
| Acer Aspire                    | 4        | 1.56%   |
| HP ProDesk                     | 3        | 1.17%   |
| HP Compaq                      | 3        | 1.17%   |
| Gigabyte H410M                 | 3        | 1.17%   |
| Gigabyte B450M                 | 3        | 1.17%   |
| ASUS STRIX                     | 3        | 1.17%   |
| ASUS M5A78L-M                  | 3        | 1.17%   |
| ASRock B450M                   | 3        | 1.17%   |
| ASRock A320M-HDV               | 3        | 1.17%   |
| Supermicro SKAGIT09            | 2        | 0.78%   |
| MSI MS-7C95                    | 2        | 0.78%   |
| MSI MS-7C56                    | 2        | 0.78%   |
| MSI MS-7B86                    | 2        | 0.78%   |
| MSI MS-7B84                    | 2        | 0.78%   |
| HP EliteDesk                   | 2        | 0.78%   |
| Gigabyte Z390                  | 2        | 0.78%   |
| Gigabyte B660M                 | 2        | 0.78%   |
| Gigabyte B560M                 | 2        | 0.78%   |
| Gigabyte B365M                 | 2        | 0.78%   |
| Fujitsu ESPRIMO                | 2        | 0.78%   |
| Dell Inspiron                  | 2        | 0.78%   |
| ASUS P9X79                     | 2        | 0.78%   |
| ASRock B550                    | 2        | 0.78%   |
| Supermicro X9DAL               | 1        | 0.39%   |
| Supermicro X8ST3               | 1        | 0.39%   |
| Supermicro PIO-1UDP10-01-AI036 | 1        | 0.39%   |
| Shuttle SH61R                  | 1        | 0.39%   |
| Shuttle NC01U                  | 1        | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 38       | 14.79%  |
| 2020 | 32       | 12.45%  |
| 2019 | 27       | 10.51%  |
| 2021 | 26       | 10.12%  |
| 2014 | 19       | 7.39%   |
| 2012 | 17       | 6.61%   |
| 2015 | 16       | 6.23%   |
| 2013 | 16       | 6.23%   |
| 2017 | 15       | 5.84%   |
| 2016 | 15       | 5.84%   |
| 2011 | 11       | 4.28%   |
| 2010 | 8        | 3.11%   |
| 2022 | 6        | 2.33%   |
| 2009 | 5        | 1.95%   |
| 2008 | 3        | 1.17%   |
| 2007 | 3        | 1.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 257      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 251      | 97.67%  |
| Enabled  | 6        | 2.33%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 257      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 82       | 31.78%  |
| 32.01-64.0      | 66       | 25.58%  |
| 8.01-16.0       | 39       | 15.12%  |
| 4.01-8.0        | 23       | 8.91%   |
| 64.01-256.0     | 22       | 8.53%   |
| 3.01-4.0        | 15       | 5.81%   |
| 24.01-32.0      | 10       | 3.88%   |
| More than 256.0 | 1        | 0.39%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 77       | 28.73%  |
| 4.01-8.0   | 68       | 25.37%  |
| 1.01-2.0   | 45       | 16.79%  |
| 3.01-4.0   | 44       | 16.42%  |
| 8.01-16.0  | 22       | 8.21%   |
| 16.01-24.0 | 6        | 2.24%   |
| 0.51-1.0   | 4        | 1.49%   |
| 32.01-64.0 | 2        | 0.75%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 81       | 31.27%  |
| 1      | 69       | 26.64%  |
| 3      | 53       | 20.46%  |
| 4      | 23       | 8.88%   |
| 5      | 14       | 5.41%   |
| 6      | 9        | 3.47%   |
| 7      | 6        | 2.32%   |
| 9      | 2        | 0.77%   |
| 11     | 1        | 0.39%   |
| 8      | 1        | 0.39%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 151      | 58.53%  |
| Yes       | 107      | 41.47%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 255      | 99.22%  |
| No        | 2        | 0.78%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 138      | 53.49%  |
| No        | 120      | 46.51%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 145      | 56.42%  |
| Yes       | 112      | 43.58%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 56       | 21.79%  |
| Germany      | 30       | 11.67%  |
| France       | 22       | 8.56%   |
| Italy        | 16       | 6.23%   |
| Russia       | 14       | 5.45%   |
| Brazil       | 13       | 5.06%   |
| UK           | 11       | 4.28%   |
| Poland       | 10       | 3.89%   |
| Netherlands  | 8        | 3.11%   |
| Australia    | 7        | 2.72%   |
| Canada       | 6        | 2.33%   |
| Spain        | 5        | 1.95%   |
| Switzerland  | 4        | 1.56%   |
| Finland      | 4        | 1.56%   |
| New Zealand  | 3        | 1.17%   |
| India        | 3        | 1.17%   |
| Bulgaria     | 3        | 1.17%   |
| Belgium      | 3        | 1.17%   |
| Argentina    | 3        | 1.17%   |
| Thailand     | 2        | 0.78%   |
| South Africa | 2        | 0.78%   |
| Slovenia     | 2        | 0.78%   |
| Serbia       | 2        | 0.78%   |
| Portugal     | 2        | 0.78%   |
| Philippines  | 2        | 0.78%   |
| Iran         | 2        | 0.78%   |
| Czechia      | 2        | 0.78%   |
| Austria      | 2        | 0.78%   |
| Vietnam      | 1        | 0.39%   |
| Venezuela    | 1        | 0.39%   |
| Ukraine      | 1        | 0.39%   |
| Turkey       | 1        | 0.39%   |
| Sweden       | 1        | 0.39%   |
| Romania      | 1        | 0.39%   |
| Mexico       | 1        | 0.39%   |
| Malta        | 1        | 0.39%   |
| Malaysia     | 1        | 0.39%   |
| Luxembourg   | 1        | 0.39%   |
| Kazakhstan   | 1        | 0.39%   |
| Israel       | 1        | 0.39%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Berlin                 | 5        | 1.92%   |
| Munich                 | 4        | 1.53%   |
| Moscow                 | 4        | 1.53%   |
| Rio de Janeiro         | 3        | 1.15%   |
| Montreal               | 3        | 1.15%   |
| Milan                  | 3        | 1.15%   |
| London                 | 3        | 1.15%   |
| Dallas                 | 3        | 1.15%   |
| Wroclaw                | 2        | 0.77%   |
| Washington             | 2        | 0.77%   |
| Vienna                 | 2        | 0.77%   |
| Turku                  | 2        | 0.77%   |
| Sydney                 | 2        | 0.77%   |
| Sofia                  | 2        | 0.77%   |
| Prague                 | 2        | 0.77%   |
| Pittsburgh             | 2        | 0.77%   |
| New York               | 2        | 0.77%   |
| Melbourne              | 2        | 0.77%   |
| Katowice               | 2        | 0.77%   |
| Columbus               | 2        | 0.77%   |
| Caruaru                | 2        | 0.77%   |
| Canberra               | 2        | 0.77%   |
| Brasília              | 2        | 0.77%   |
| Bougival               | 2        | 0.77%   |
| Belgrade               | 2        | 0.77%   |
| Auckland               | 2        | 0.77%   |
| Amsterdam              | 2        | 0.77%   |
| Zaandam                | 1        | 0.38%   |
| Yerevan                | 1        | 0.38%   |
| Wheaton                | 1        | 0.38%   |
| Whangarei              | 1        | 0.38%   |
| Wembley                | 1        | 0.38%   |
| Waukee                 | 1        | 0.38%   |
| Vrhnika                | 1        | 0.38%   |
| Voronezh               | 1        | 0.38%   |
| Volgograd              | 1        | 0.38%   |
| Vladivostok            | 1        | 0.38%   |
| Vitebsk                | 1        | 0.38%   |
| Villingen-Schwenningen | 1        | 0.38%   |
| Villa Nueva            | 1        | 0.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 92       | 133    | 17.46%  |
| Samsung Electronics         | 91       | 137    | 17.27%  |
| Seagate                     | 82       | 138    | 15.56%  |
| Kingston                    | 36       | 43     | 6.83%   |
| Toshiba                     | 32       | 37     | 6.07%   |
| Sandisk                     | 24       | 28     | 4.55%   |
| Crucial                     | 23       | 28     | 4.36%   |
| Hitachi                     | 19       | 19     | 3.61%   |
| Intel                       | 9        | 12     | 1.71%   |
| A-DATA Technology           | 8        | 9      | 1.52%   |
| Phison                      | 7        | 7      | 1.33%   |
| Unknown                     | 6        | 9      | 1.14%   |
| Patriot                     | 6        | 8      | 1.14%   |
| Maxtor                      | 5        | 6      | 0.95%   |
| HGST                        | 5        | 9      | 0.95%   |
| PNY                         | 4        | 5      | 0.76%   |
| Phison Electronics          | 4        | 4      | 0.76%   |
| Lexar                       | 4        | 4      | 0.76%   |
| China                       | 4        | 5      | 0.76%   |
| Transcend                   | 3        | 4      | 0.57%   |
| OCZ                         | 3        | 3      | 0.57%   |
| Micron Technology           | 3        | 3      | 0.57%   |
| Intenso                     | 3        | 4      | 0.57%   |
| Corsair                     | 3        | 4      | 0.57%   |
| Verbatim                    | 2        | 2      | 0.38%   |
| T-FORCE                     | 2        | 2      | 0.38%   |
| SPCC                        | 2        | 2      | 0.38%   |
| Smartbuy                    | 2        | 2      | 0.38%   |
| SK hynix                    | 2        | 4      | 0.38%   |
| SABRENT                     | 2        | 2      | 0.38%   |
| Micron/Crucial Technology   | 2        | 2      | 0.38%   |
| KODAK                       | 2        | 2      | 0.38%   |
| Kingston Technology Company | 2        | 3      | 0.38%   |
| GOODRAM                     | 2        | 2      | 0.38%   |
| Emtec                       | 2        | 2      | 0.38%   |
| Apple                       | 2        | 2      | 0.38%   |
| XPG                         | 1        | 1      | 0.19%   |
| ValueTech                   | 1        | 1      | 0.19%   |
| USB3.0                      | 1        | 1      | 0.19%   |
| Team                        | 1        | 1      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 10       | 1.63%   |
| Seagate ST4000DM004-2CV104 4TB                      | 8        | 1.31%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 7        | 1.14%   |
| Samsung SSD 850 EVO 500GB                           | 6        | 0.98%   |
| Toshiba DT01ACA100 1TB                              | 5        | 0.82%   |
| SanDisk NVMe SSD Drive 500GB                        | 5        | 0.82%   |
| Samsung SSD 860 EVO 500GB                           | 5        | 0.82%   |
| Samsung SSD 860 EVO 1TB                             | 5        | 0.82%   |
| Kingston SA400S37480G 480GB SSD                     | 5        | 0.82%   |
| Crucial CT240BX500SSD1 240GB                        | 5        | 0.82%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 4        | 0.65%   |
| Toshiba HDWD110 1TB                                 | 4        | 0.65%   |
| Samsung SSD 970 EVO Plus 1TB                        | 4        | 0.65%   |
| Samsung NVMe SSD Drive 500GB                        | 4        | 0.65%   |
| Kingston SA2000M81000G 1TB                          | 4        | 0.65%   |
| WDC WD20EZRX-00D8PB0 2TB                            | 3        | 0.49%   |
| WDC WD20EARX-00PASB0 2TB                            | 3        | 0.49%   |
| WDC WD10EZEX-22MFCA0 1TB                            | 3        | 0.49%   |
| Seagate ST500DM002-1BD142 500GB                     | 3        | 0.49%   |
| Seagate ST4000VN008-2DR166 4TB                      | 3        | 0.49%   |
| Seagate ST2000DM008-2FR102 2TB                      | 3        | 0.49%   |
| Seagate ST2000DM001-1ER164 2TB                      | 3        | 0.49%   |
| Seagate ST1000DM003-1CH162 1TB                      | 3        | 0.49%   |
| SanDisk NVMe SSD Drive 1TB                          | 3        | 0.49%   |
| Samsung SSD 980 500GB                               | 3        | 0.49%   |
| Samsung SSD 980 1TB                                 | 3        | 0.49%   |
| Samsung SSD 970 EVO Plus 2TB                        | 3        | 0.49%   |
| Samsung SSD 870 EVO 1TB                             | 3        | 0.49%   |
| Samsung SSD 860 EVO 250GB                           | 3        | 0.49%   |
| Samsung SSD 850 EVO 120GB                           | 3        | 0.49%   |
| Samsung SSD 840 PRO Series 128GB                    | 3        | 0.49%   |
| Samsung HD103SI 1TB                                 | 3        | 0.49%   |
| Kingston SA400S37120G 120GB SSD                     | 3        | 0.49%   |
| Hitachi HTS547550A9E384 500GB                       | 3        | 0.49%   |
| Crucial CT500MX500SSD1 500GB                        | 3        | 0.49%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 2        | 0.33%   |
| WDC WDBNCE5000PNC 500GB SSD                         | 2        | 0.33%   |
| WDC WD80EFBX-68AZZN0 8TB                            | 2        | 0.33%   |
| WDC WD60EZAZ-00SF3B0 6TB                            | 2        | 0.33%   |
| WDC WD5000AAKX-753CA1 500GB                         | 2        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 84       | 113    | 35.29%  |
| Seagate             | 77       | 128    | 32.35%  |
| Toshiba             | 27       | 31     | 11.34%  |
| Hitachi             | 19       | 19     | 7.98%   |
| Samsung Electronics | 15       | 16     | 6.3%    |
| HGST                | 5        | 9      | 2.1%    |
| Maxtor              | 4        | 5      | 1.68%   |
| SABRENT             | 2        | 2      | 0.84%   |
| USB3.0              | 1        | 1      | 0.42%   |
| Unknown             | 1        | 1      | 0.42%   |
| JMicron Technology  | 1        | 1      | 0.42%   |
| IET                 | 1        | 1      | 0.42%   |
| Apple               | 1        | 1      | 0.42%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 52       | 73     | 27.08%  |
| Kingston            | 29       | 31     | 15.1%   |
| Crucial             | 19       | 22     | 9.9%    |
| SanDisk             | 13       | 13     | 6.77%   |
| WDC                 | 11       | 14     | 5.73%   |
| Patriot             | 6        | 8      | 3.13%   |
| A-DATA Technology   | 6        | 7      | 3.13%   |
| Intel               | 5        | 8      | 2.6%    |
| PNY                 | 4        | 5      | 2.08%   |
| Lexar               | 4        | 4      | 2.08%   |
| China               | 4        | 5      | 2.08%   |
| Toshiba             | 3        | 3      | 1.56%   |
| OCZ                 | 3        | 3      | 1.56%   |
| Micron Technology   | 3        | 3      | 1.56%   |
| Verbatim            | 2        | 2      | 1.04%   |
| Transcend           | 2        | 2      | 1.04%   |
| KODAK               | 2        | 2      | 1.04%   |
| Intenso             | 2        | 2      | 1.04%   |
| GOODRAM             | 2        | 2      | 1.04%   |
| ValueTech           | 1        | 1      | 0.52%   |
| Team                | 1        | 1      | 0.52%   |
| T-FORCE             | 1        | 1      | 0.52%   |
| SPCC                | 1        | 1      | 0.52%   |
| Smartbuy            | 1        | 1      | 0.52%   |
| Seagate             | 1        | 1      | 0.52%   |
| Plextor             | 1        | 1      | 0.52%   |
| Mushkin             | 1        | 2      | 0.52%   |
| Maxtor              | 1        | 1      | 0.52%   |
| LITEONIT            | 1        | 1      | 0.52%   |
| KIOXIA-EXCERIA      | 1        | 2      | 0.52%   |
| KingFast            | 1        | 1      | 0.52%   |
| INNOVATION IT       | 1        | 1      | 0.52%   |
| INDMEM              | 1        | 1      | 0.52%   |
| Hewlett-Packard     | 1        | 1      | 0.52%   |
| Drevo               | 1        | 1      | 0.52%   |
| Apple               | 1        | 1      | 0.52%   |
| Apacer              | 1        | 1      | 0.52%   |
| Aireye              | 1        | 1      | 0.52%   |
| ADATA SU            | 1        | 1      | 0.52%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 178      | 328    | 40.18%  |
| SSD     | 158      | 231    | 35.67%  |
| NVMe    | 94       | 138    | 21.22%  |
| Unknown | 12       | 17     | 2.71%   |
| MMC     | 1        | 1      | 0.23%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 234      | 535    | 65.92%  |
| NVMe | 94       | 138    | 26.48%  |
| SAS  | 26       | 41     | 7.32%   |
| MMC  | 1        | 1      | 0.28%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 166      | 261    | 44.5%   |
| 0.51-1.0   | 99       | 138    | 26.54%  |
| 1.01-2.0   | 48       | 61     | 12.87%  |
| 3.01-4.0   | 31       | 57     | 8.31%   |
| 4.01-10.0  | 16       | 27     | 4.29%   |
| 2.01-3.0   | 11       | 13     | 2.95%   |
| 10.01-20.0 | 2        | 2      | 0.54%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 50       | 19.08%  |
| More than 3000 | 45       | 17.18%  |
| 1001-2000      | 44       | 16.79%  |
| 251-500        | 40       | 15.27%  |
| 101-250        | 34       | 12.98%  |
| 2001-3000      | 33       | 12.6%   |
| 1-20           | 11       | 4.2%    |
| 51-100         | 4        | 1.53%   |
| Unknown        | 1        | 0.38%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 41       | 15.53%  |
| 101-250        | 38       | 14.39%  |
| 501-1000       | 38       | 14.39%  |
| 1-20           | 34       | 12.88%  |
| 51-100         | 29       | 10.98%  |
| 1001-2000      | 26       | 9.85%   |
| 21-50          | 24       | 9.09%   |
| More than 3000 | 22       | 8.33%   |
| 2001-3000      | 11       | 4.17%   |
| Unknown        | 1        | 0.38%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Desktops | Drives | Percent |
|------------------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                | 2        | 2      | 4.35%   |
| Crucial CT525MX300SSD1 528GB                   | 2        | 2      | 4.35%   |
| WDC WD5000AZRX-00A3KB0 500GB                   | 1        | 1      | 2.17%   |
| WDC WD5000AVVS-63M8B0 500GB                    | 1        | 1      | 2.17%   |
| WDC WD5000AAKS-00V1A0 500GB                    | 1        | 1      | 2.17%   |
| WDC WD10EZRX-00L4HB0 1TB                       | 1        | 1      | 2.17%   |
| WDC WD10EZEX-22MFCA0 1TB                       | 1        | 1      | 2.17%   |
| WDC WD10EZEX-08M2NA0 1TB                       | 1        | 1      | 2.17%   |
| WDC WD10EURX-73C57Y0 1TB                       | 1        | 1      | 2.17%   |
| WDC WD10EARS-00MVWB0 1TB                       | 1        | 1      | 2.17%   |
| WDC WD10EADS-00L5B1 1TB                        | 1        | 1      | 2.17%   |
| WDC WD10EACS-65D6B0 1TB                        | 1        | 1      | 2.17%   |
| Toshiba MQ01ABF032 320GB                       | 1        | 1      | 2.17%   |
| T-FORCE SSD 512GB                              | 1        | 1      | 2.17%   |
| Seagate ST500LT012-9WS142 500GB                | 1        | 1      | 2.17%   |
| Seagate ST500LM012 HN-M500MBB 500GB            | 1        | 1      | 2.17%   |
| Seagate ST4000VN008-2DR166 4TB                 | 1        | 2      | 2.17%   |
| Seagate ST3500630AS 500GB                      | 1        | 1      | 2.17%   |
| Seagate ST3250310AS 250GB                      | 1        | 1      | 2.17%   |
| Seagate ST3160827AS 160GB                      | 1        | 1      | 2.17%   |
| Seagate ST3160023A 160GB                       | 1        | 1      | 2.17%   |
| Seagate ST31500341AS 1TB                       | 1        | 1      | 2.17%   |
| Seagate ST31000524AS 1TB                       | 1        | 2      | 2.17%   |
| Seagate ST2000DX001-1NS164 2TB                 | 1        | 1      | 2.17%   |
| Seagate ST1000DM003-1SB102 1TB                 | 1        | 1      | 2.17%   |
| Seagate ST1000DM003-1CH162 1TB                 | 1        | 1      | 2.17%   |
| SanDisk SDSSDX240GG25 240GB                    | 1        | 1      | 2.17%   |
| Samsung Electronics SSD 870 EVO 1TB            | 1        | 1      | 2.17%   |
| Samsung Electronics SSD 840 Series 250GB       | 1        | 1      | 2.17%   |
| Samsung Electronics SSD 840 Series 120GB       | 1        | 1      | 2.17%   |
| Samsung Electronics HM321HI 320GB              | 1        | 1      | 2.17%   |
| Samsung Electronics HD103SI 1TB                | 1        | 1      | 2.17%   |
| Micron Technology 5100_MTFDDAV960TCB 960GB SSD | 1        | 1      | 2.17%   |
| Maxtor 6V160E0 160GB                           | 1        | 1      | 2.17%   |
| LITEONIT LMT-128M3M 128GB SSD                  | 1        | 1      | 2.17%   |
| Kingston SA400S37480G 480GB SSD                | 1        | 1      | 2.17%   |
| Intel SSDSC2KW010X6 1TB                        | 1        | 4      | 2.17%   |
| Hitachi HTS547550A9E384 500GB                  | 1        | 1      | 2.17%   |
| Hitachi HDS721010CLA630 1TB                    | 1        | 1      | 2.17%   |
| Hitachi HDP725050GLA360 500GB                  | 1        | 1      | 2.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 12       | 16     | 27.91%  |
| WDC                 | 9        | 10     | 20.93%  |
| Samsung Electronics | 5        | 5      | 11.63%  |
| Hitachi             | 4        | 4      | 9.3%    |
| Crucial             | 4        | 4      | 9.3%    |
| Toshiba             | 1        | 1      | 2.33%   |
| T-FORCE             | 1        | 1      | 2.33%   |
| SanDisk             | 1        | 1      | 2.33%   |
| Micron Technology   | 1        | 1      | 2.33%   |
| Maxtor              | 1        | 1      | 2.33%   |
| LITEONIT            | 1        | 1      | 2.33%   |
| Kingston            | 1        | 1      | 2.33%   |
| Intel               | 1        | 4      | 2.33%   |
| HGST                | 1        | 1      | 2.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 12       | 16     | 40%     |
| WDC                 | 9        | 10     | 30%     |
| Hitachi             | 4        | 4      | 13.33%  |
| Samsung Electronics | 2        | 2      | 6.67%   |
| Toshiba             | 1        | 1      | 3.33%   |
| Maxtor              | 1        | 1      | 3.33%   |
| HGST                | 1        | 1      | 3.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 27       | 35     | 67.5%   |
| SSD  | 13       | 16     | 32.5%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Samsung Electronics HD502IJ 500GB | 1        | 1      | 50%     |
| Hitachi HTS547550A9E384 500GB     | 1        | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 1        | 1      | 50%     |
| Hitachi             | 1        | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 136      | 333    | 44.16%  |
| Detected | 132      | 329    | 42.86%  |
| Malfunc  | 39       | 51     | 12.66%  |
| Failed   | 1        | 2      | 0.32%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 153      | 38.83%  |
| AMD                          | 103      | 26.14%  |
| Samsung Electronics          | 38       | 9.64%   |
| SanDisk                      | 16       | 4.06%   |
| ASMedia Technology           | 16       | 4.06%   |
| Phison Electronics           | 15       | 3.81%   |
| Kingston Technology Company  | 11       | 2.79%   |
| Micron/Crucial Technology    | 7        | 1.78%   |
| JMicron Technology           | 7        | 1.78%   |
| Marvell Technology Group     | 4        | 1.02%   |
| ADATA Technology             | 4        | 1.02%   |
| Seagate Technology           | 3        | 0.76%   |
| LSI Logic / Symbios Logic    | 3        | 0.76%   |
| SK hynix                     | 2        | 0.51%   |
| KIOXIA                       | 2        | 0.51%   |
| VIA Technologies             | 1        | 0.25%   |
| Toshiba America Info Systems | 1        | 0.25%   |
| Silicon Motion               | 1        | 0.25%   |
| Silicon Image                | 1        | 0.25%   |
| Realtek Semiconductor        | 1        | 0.25%   |
| OCZ Technology Group         | 1        | 0.25%   |
| O2 Micro                     | 1        | 0.25%   |
| Netac Technology             | 1        | 0.25%   |
| INNOGRIT                     | 1        | 0.25%   |
| Broadcom / LSI               | 1        | 0.25%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 63       | 13.24%  |
| AMD 400 Series Chipset SATA Controller                                         | 29       | 6.09%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 22       | 4.62%   |
| AMD 500 Series Chipset SATA Controller                                         | 20       | 4.2%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 16       | 3.36%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 15       | 3.15%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 14       | 2.94%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 14       | 2.94%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 13       | 2.73%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 11       | 2.31%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 11       | 2.31%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 10       | 2.1%    |
| Intel SATA Controller [RAID mode]                                              | 9        | 1.89%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 8        | 1.68%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 8        | 1.68%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 8        | 1.68%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 7        | 1.47%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 7        | 1.47%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 7        | 1.47%   |
| AMD FCH SATA Controller D                                                      | 7        | 1.47%   |
| Samsung NVMe SSD Controller 980                                                | 6        | 1.26%   |
| Phison E12 NVMe Controller                                                     | 6        | 1.26%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 6        | 1.26%   |
| Kingston Company A2000 NVMe SSD                                                | 6        | 1.26%   |
| Intel Comet Lake SATA AHCI Controller                                          | 6        | 1.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 6        | 1.26%   |
| SanDisk Non-Volatile memory controller                                         | 5        | 1.05%   |
| JMicron JMB363 SATA/IDE Controller                                             | 5        | 1.05%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 5        | 1.05%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 5        | 1.05%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 5        | 1.05%   |
| Intel SSD 660P Series                                                          | 4        | 0.84%   |
| AMD 300 Series Chipset SATA Controller                                         | 4        | 0.84%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 3        | 0.63%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3        | 0.63%   |
| Phison PS5013 E13 NVMe Controller                                              | 3        | 0.63%   |
| Kingston Company NVMe Controller                                               | 3        | 0.63%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 3        | 0.63%   |
| AMD X399 Series Chipset SATA Controller                                        | 3        | 0.63%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 3        | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 234      | 62.4%   |
| NVMe | 93       | 24.8%   |
| IDE  | 28       | 7.47%   |
| RAID | 17       | 4.53%   |
| SAS  | 2        | 0.53%   |
| SCSI | 1        | 0.27%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 153      | 59.53%  |
| AMD    | 104      | 40.47%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| AMD Ryzen 5 5600X 6-Core Processor             | 8        | 3.11%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 5        | 1.95%   |
| Intel Core i7-3770 CPU @ 3.40GHz               | 5        | 1.95%   |
| Intel Core i5-10400F CPU @ 2.90GHz             | 5        | 1.95%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 5        | 1.95%   |
| AMD Ryzen 5 2600X Six-Core Processor           | 5        | 1.95%   |
| Intel Core i7-6700 CPU @ 3.40GHz               | 4        | 1.56%   |
| Intel Core i5-9600K CPU @ 3.70GHz              | 4        | 1.56%   |
| Intel Core i3-10100F CPU @ 3.60GHz             | 4        | 1.56%   |
| AMD Ryzen 9 5950X 16-Core Processor            | 4        | 1.56%   |
| AMD Ryzen 7 5700G with Radeon Graphics         | 4        | 1.56%   |
| AMD Ryzen 7 2700X Eight-Core Processor         | 4        | 1.56%   |
| AMD Ryzen 5 5600G with Radeon Graphics         | 4        | 1.56%   |
| AMD Ryzen 5 3600 6-Core Processor              | 4        | 1.56%   |
| Intel Core i7-7700K CPU @ 4.20GHz              | 3        | 1.17%   |
| Intel Core i7-4790K CPU @ 4.00GHz              | 3        | 1.17%   |
| Intel Core i7-3770K CPU @ 3.50GHz              | 3        | 1.17%   |
| Intel Core i5-4590 CPU @ 3.30GHz               | 3        | 1.17%   |
| Intel Core i3-4130 CPU @ 3.40GHz               | 3        | 1.17%   |
| AMD Ryzen 7 5700X 8-Core Processor             | 3        | 1.17%   |
| AMD Ryzen 7 3700X 8-Core Processor             | 3        | 1.17%   |
| AMD Ryzen 7 2700 Eight-Core Processor          | 3        | 1.17%   |
| Intel Pentium CPU G2020 @ 2.90GHz              | 2        | 0.78%   |
| Intel Core i7-8700K CPU @ 3.70GHz              | 2        | 0.78%   |
| Intel Core i7-8700 CPU @ 3.20GHz               | 2        | 0.78%   |
| Intel Core i7-5820K CPU @ 3.30GHz              | 2        | 0.78%   |
| Intel Core i7 CPU 920 @ 2.67GHz                | 2        | 0.78%   |
| Intel Core i5-8400 CPU @ 2.80GHz               | 2        | 0.78%   |
| Intel Core i5-7500 CPU @ 3.40GHz               | 2        | 0.78%   |
| Intel Core i5-3350P CPU @ 3.10GHz              | 2        | 0.78%   |
| Intel Core i5-2400 CPU @ 3.10GHz               | 2        | 0.78%   |
| Intel Core i5-2300 CPU @ 2.80GHz               | 2        | 0.78%   |
| Intel Core i3-6100T CPU @ 3.20GHz              | 2        | 0.78%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz           | 2        | 0.78%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz        | 2        | 0.78%   |
| Intel 11th Gen Core i5-11600K @ 3.90GHz        | 2        | 0.78%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz         | 2        | 0.78%   |
| AMD Ryzen Threadripper 1950X 16-Core Processor | 2        | 0.78%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 2        | 0.78%   |
| AMD Ryzen 7 PRO 4750G with Radeon Graphics     | 2        | 0.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i7          | 47       | 18.29%  |
| Intel Core i5          | 40       | 15.56%  |
| AMD Ryzen 5            | 33       | 12.84%  |
| AMD Ryzen 7            | 22       | 8.56%   |
| Intel Core i3          | 18       | 7%      |
| AMD Ryzen 9            | 16       | 6.23%   |
| Intel Xeon             | 14       | 5.45%   |
| Other                  | 12       | 4.67%   |
| Intel Pentium          | 8        | 3.11%   |
| Intel Core 2 Duo       | 5        | 1.95%   |
| AMD Ryzen 3            | 5        | 1.95%   |
| AMD FX                 | 5        | 1.95%   |
| Intel Celeron          | 4        | 1.56%   |
| Intel Core i9          | 3        | 1.17%   |
| AMD Ryzen Threadripper | 3        | 1.17%   |
| AMD A6                 | 3        | 1.17%   |
| Intel Core 2 Quad      | 2        | 0.78%   |
| AMD Ryzen 7 PRO        | 2        | 0.78%   |
| AMD Phenom II X4       | 2        | 0.78%   |
| AMD Phenom II X2       | 2        | 0.78%   |
| AMD Opteron            | 2        | 0.78%   |
| Intel Pentium Gold     | 1        | 0.39%   |
| AMD PRO A10            | 1        | 0.39%   |
| AMD Phenom II X6       | 1        | 0.39%   |
| AMD Phenom             | 1        | 0.39%   |
| AMD E1                 | 1        | 0.39%   |
| AMD Athlon II X2       | 1        | 0.39%   |
| AMD Athlon 64 X2       | 1        | 0.39%   |
| AMD A8                 | 1        | 0.39%   |
| AMD A4                 | 1        | 0.39%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 91       | 35.41%  |
| 6      | 61       | 23.74%  |
| 2      | 40       | 15.56%  |
| 8      | 37       | 14.4%   |
| 16     | 11       | 4.28%   |
| 12     | 9        | 3.5%    |
| 10     | 3        | 1.17%   |
| 1      | 2        | 0.78%   |
| 36     | 1        | 0.39%   |
| 14     | 1        | 0.39%   |
| 3      | 1        | 0.39%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 254      | 98.83%  |
| 2      | 3        | 1.17%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 182      | 70.82%  |
| 1      | 75       | 29.18%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 257      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 111      | 42.53%  |
| 0x306c3    | 13       | 4.98%   |
| 0x08701021 | 10       | 3.83%   |
| 0xa0653    | 7        | 2.68%   |
| 0x0800820d | 7        | 2.68%   |
| 0x506e3    | 6        | 2.3%    |
| 0x306a9    | 6        | 2.3%    |
| 0x0a50000c | 6        | 2.3%    |
| 0xa0655    | 5        | 1.92%   |
| 0x906e9    | 5        | 1.92%   |
| 0x206a7    | 5        | 1.92%   |
| 0x0a201205 | 5        | 1.92%   |
| 0x010000c8 | 5        | 1.92%   |
| 0x906ed    | 4        | 1.53%   |
| 0x906ea    | 4        | 1.53%   |
| 0x406f1    | 4        | 1.53%   |
| 0x90672    | 3        | 1.15%   |
| 0x306e4    | 3        | 1.15%   |
| 0x1067a    | 3        | 1.15%   |
| 0x0a201016 | 3        | 1.15%   |
| 0x08001138 | 3        | 1.15%   |
| 0xa0671    | 2        | 0.77%   |
| 0x306f2    | 2        | 0.77%   |
| 0x206d7    | 2        | 0.77%   |
| 0x106a5    | 2        | 0.77%   |
| 0x0a601203 | 2        | 0.77%   |
| 0x0a50000d | 2        | 0.77%   |
| 0x0a20120a | 2        | 0.77%   |
| 0x0a201204 | 2        | 0.77%   |
| 0x0a201009 | 2        | 0.77%   |
| 0x0600611a | 2        | 0.77%   |
| 0x06000852 | 2        | 0.77%   |
| 0xb0671    | 1        | 0.38%   |
| 0x906ec    | 1        | 0.38%   |
| 0x806ea    | 1        | 0.38%   |
| 0x6fb      | 1        | 0.38%   |
| 0x30673    | 1        | 0.38%   |
| 0x206d6    | 1        | 0.38%   |
| 0x106e5    | 1        | 0.38%   |
| 0x0a201005 | 1        | 0.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 33       | 12.79%  |
| Haswell          | 33       | 12.79%  |
| KabyLake         | 25       | 9.69%   |
| IvyBridge        | 23       | 8.91%   |
| Zen 2            | 18       | 6.98%   |
| Zen+             | 17       | 6.59%   |
| CometLake        | 16       | 6.2%    |
| SandyBridge      | 12       | 4.65%   |
| Zen              | 11       | 4.26%   |
| Skylake          | 11       | 4.26%   |
| Unknown          | 9        | 3.49%   |
| Piledriver       | 8        | 3.1%    |
| K10              | 8        | 3.1%    |
| Nehalem          | 6        | 2.33%   |
| Penryn           | 5        | 1.94%   |
| Excavator        | 5        | 1.94%   |
| Broadwell        | 5        | 1.94%   |
| Alderlake Hybrid | 3        | 1.16%   |
| Westmere         | 2        | 0.78%   |
| Icelake          | 2        | 0.78%   |
| Core             | 2        | 0.78%   |
| Silvermont       | 1        | 0.39%   |
| Puma             | 1        | 0.39%   |
| K8 Hammer        | 1        | 0.39%   |
| Goldmont         | 1        | 0.39%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 132      | 46.81%  |
| AMD                        | 89       | 31.56%  |
| Intel                      | 57       | 20.21%  |
| Matrox Electronics Systems | 3        | 1.06%   |
| ASPEED Technology          | 1        | 0.35%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 12       | 4.24%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 12       | 4.24%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 12       | 4.24%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 7        | 2.47%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 6        | 2.12%   |
| Nvidia GK208B [GeForce GT 710]                                              | 6        | 2.12%   |
| Intel HD Graphics 530                                                       | 6        | 2.12%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 6        | 2.12%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 5        | 1.77%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 5        | 1.77%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 5        | 1.77%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 5        | 1.77%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 5        | 1.77%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 5        | 1.77%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 4        | 1.41%   |
| Intel HD Graphics 630                                                       | 4        | 1.41%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 4        | 1.41%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4        | 1.41%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 4        | 1.41%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 4        | 1.41%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 3        | 1.06%   |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 1.06%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 1.06%   |
| Nvidia GK208B [GeForce GT 730]                                              | 3        | 1.06%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 3        | 1.06%   |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 3        | 1.06%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                    | 3        | 1.06%   |
| AMD RS780L [Radeon 3000]                                                    | 3        | 1.06%   |
| AMD Renoir                                                                  | 3        | 1.06%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 3        | 1.06%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 3        | 1.06%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 2        | 0.71%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 2        | 0.71%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 2        | 0.71%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 2        | 0.71%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 0.71%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 0.71%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 0.71%   |
| Nvidia GM107 [GeForce GTX 745]                                              | 2        | 0.71%   |
| Nvidia GK208B [GeForce GT 720]                                              | 2        | 0.71%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 125      | 48.64%  |
| 1 x AMD                  | 80       | 31.13%  |
| 1 x Intel                | 39       | 15.18%  |
| Intel + AMD              | 3        | 1.17%   |
| Intel + Nvidia           | 2        | 0.78%   |
| AMD + Matrox             | 2        | 0.78%   |
| 2 x Nvidia               | 1        | 0.39%   |
| 2 x AMD                  | 1        | 0.39%   |
| Nvidia + Matrox          | 1        | 0.39%   |
| Nvidia + ASPEED          | 1        | 0.39%   |
| Intel + AMD + 1 x Nvidia | 1        | 0.39%   |
| AMD + Nvidia             | 1        | 0.39%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 150      | 58.37%  |
| Proprietary | 99       | 38.52%  |
| Unknown     | 8        | 3.11%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 113      | 43.13%  |
| 1.01-2.0   | 32       | 12.21%  |
| 7.01-8.0   | 29       | 11.07%  |
| 3.01-4.0   | 26       | 9.92%   |
| 0.51-1.0   | 20       | 7.63%   |
| 5.01-6.0   | 16       | 6.11%   |
| 0.01-0.5   | 13       | 4.96%   |
| 8.01-16.0  | 9        | 3.44%   |
| 16.01-24.0 | 2        | 0.76%   |
| 4.01-5.0   | 1        | 0.38%   |
| 2.01-3.0   | 1        | 0.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 56       | 18.67%  |
| Dell                 | 39       | 13%     |
| Goldstar             | 32       | 10.67%  |
| Hewlett-Packard      | 22       | 7.33%   |
| Acer                 | 20       | 6.67%   |
| Philips              | 16       | 5.33%   |
| AOC                  | 16       | 5.33%   |
| BenQ                 | 15       | 5%      |
| Ancor Communications | 11       | 3.67%   |
| Iiyama               | 10       | 3.33%   |
| ASUSTek Computer     | 7        | 2.33%   |
| Sony                 | 6        | 2%      |
| ViewSonic            | 5        | 1.67%   |
| NEC Computers        | 3        | 1%      |
| Idek Iiyama          | 3        | 1%      |
| Vizio                | 2        | 0.67%   |
| LG Electronics       | 2        | 0.67%   |
| Gigabyte Technology  | 2        | 0.67%   |
| Fujitsu Siemens      | 2        | 0.67%   |
| Denver               | 2        | 0.67%   |
| Xiaomi               | 1        | 0.33%   |
| Vita                 | 1        | 0.33%   |
| Vestel Elektronik    | 1        | 0.33%   |
| Unknown              | 1        | 0.33%   |
| Sunplus              | 1        | 0.33%   |
| STD                  | 1        | 0.33%   |
| Sceptre Tech         | 1        | 0.33%   |
| RTK                  | 1        | 0.33%   |
| QUS                  | 1        | 0.33%   |
| Planar               | 1        | 0.33%   |
| Pixio                | 1        | 0.33%   |
| PAR                  | 1        | 0.33%   |
| Panasonic            | 1        | 0.33%   |
| MVD                  | 1        | 0.33%   |
| MSI                  | 1        | 0.33%   |
| Mi                   | 1        | 0.33%   |
| Medion               | 1        | 0.33%   |
| Lenovo               | 1        | 0.33%   |
| JINGLITAI            | 1        | 0.33%   |
| HKC                  | 1        | 0.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 3        | 0.94%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 3        | 0.94%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 3        | 0.94%   |
| AOC 27B2G5 AOC2702 1920x1080 598x336mm 27.0-inch                       | 3        | 0.94%   |
| Samsung Electronics SyncMaster SAM0587 1920x1200 518x324mm 24.1-inch   | 2        | 0.63%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 518x324mm 24.1-inch    | 2        | 0.63%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 2        | 0.63%   |
| Samsung Electronics LC27G5xT SAM7079 2560x1440 597x336mm 27.0-inch     | 2        | 0.63%   |
| Hewlett-Packard 24w HPN3431 1920x1080 527x296mm 23.8-inch              | 2        | 0.63%   |
| Hewlett-Packard 2311 HWP2939 1920x1080 509x286mm 23.0-inch             | 2        | 0.63%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 2        | 0.63%   |
| Goldstar IPS FULLHD GSM5AB7 1920x1080 480x270mm 21.7-inch              | 2        | 0.63%   |
| Goldstar 22EA53 GSM59A5 1920x1080 477x268mm 21.5-inch                  | 2        | 0.63%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 2        | 0.63%   |
| Dell S3422DW DELD102 3440x1440 797x334mm 34.0-inch                     | 2        | 0.63%   |
| Dell P2719H DEL4184 1920x1080 600x340mm 27.2-inch                      | 2        | 0.63%   |
| Dell P2214H DELA098 1920x1080 477x268mm 21.5-inch                      | 2        | 0.63%   |
| Dell 2408WFP DELA02B 1920x1200 519x320mm 24.0-inch                     | 2        | 0.63%   |
| AOC U3277WB AOC3277 3840x2160 698x393mm 31.5-inch                      | 2        | 0.63%   |
| Acer VG240Y ACR06BF 1920x1080 527x296mm 23.8-inch                      | 2        | 0.63%   |
| Xiaomi Mi TV XMD00E2 3840x2160 800x450mm 36.1-inch                     | 1        | 0.31%   |
| Vizio M55Q6-J01 VIZ1039 3840x2160 1209x680mm 54.6-inch                 | 1        | 0.31%   |
| Vizio D32hn-D0 VIZ1007 1366x768 697x392mm 31.5-inch                    | 1        | 0.31%   |
| Vita VT988 VIT03DC 1280x1024 376x301mm 19.0-inch                       | 1        | 0.31%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch             | 1        | 0.31%   |
| ViewSonic VX2439wm VSC3D24 1920x1080 520x290mm 23.4-inch               | 1        | 0.31%   |
| ViewSonic VA2261 Series VSC0F30 1920x1080 477x268mm 21.5-inch          | 1        | 0.31%   |
| ViewSonic LCD Monitor VX2270 SERIES 3840x1080                          | 1        | 0.31%   |
| ViewSonic LCD Monitor VX2270 SERIES                                    | 1        | 0.31%   |
| ViewSonic LCD Monitor VSCD62F 1920x1080 620x340mm 27.8-inch            | 1        | 0.31%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 1        | 0.31%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 1        | 0.31%   |
| Sunplus Monitor TV SPVFFFF 1360x768 708x398mm 32.0-inch                | 1        | 0.31%   |
| STD LED STD0001 1920x1080 480x260mm 21.5-inch                          | 1        | 0.31%   |
| Sony TV SNYEE01 1920x1080                                              | 1        | 0.31%   |
| Sony TV SNYEA01 1920x1080                                              | 1        | 0.31%   |
| Sony TV SNYD301 1360x768                                               | 1        | 0.31%   |
| Sony TV SNYC901 1920x1080                                              | 1        | 0.31%   |
| Sony TV SNY7702 1920x1080 708x398mm 32.0-inch                          | 1        | 0.31%   |
| Sony TV *02 SNY9403 1920x1080 1218x685mm 55.0-inch                     | 1        | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 143      | 50%     |
| 3840x2160 (4K)     | 32       | 11.19%  |
| 2560x1440 (QHD)    | 19       | 6.64%   |
| 1920x1200 (WUXGA)  | 16       | 5.59%   |
| 1680x1050 (WSXGA+) | 13       | 4.55%   |
| 1280x1024 (SXGA)   | 12       | 4.2%    |
| 1366x768 (WXGA)    | 11       | 3.85%   |
| 3440x1440          | 8        | 2.8%    |
| 2560x1080          | 5        | 1.75%   |
| 1600x900 (HD+)     | 4        | 1.4%    |
| 1440x900 (WXGA+)   | 4        | 1.4%    |
| Unknown            | 4        | 1.4%    |
| 3840x1080          | 3        | 1.05%   |
| 1360x768           | 3        | 1.05%   |
| 1280x720 (HD)      | 2        | 0.7%    |
| 6160x1440          | 1        | 0.35%   |
| 5760x1080          | 1        | 0.35%   |
| 3840x1600          | 1        | 0.35%   |
| 3840x1200          | 1        | 0.35%   |
| 3600x1200          | 1        | 0.35%   |
| 2288x1287          | 1        | 0.35%   |
| 1600x1200          | 1        | 0.35%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 55       | 18.46%  |
| 27      | 42       | 14.09%  |
| 23      | 41       | 13.76%  |
| 21      | 36       | 12.08%  |
| 31      | 20       | 6.71%   |
| Unknown | 15       | 5.03%   |
| 34      | 13       | 4.36%   |
| 19      | 11       | 3.69%   |
| 22      | 10       | 3.36%   |
| 18      | 8        | 2.68%   |
| 72      | 5        | 1.68%   |
| 32      | 5        | 1.68%   |
| 40      | 4        | 1.34%   |
| 17      | 4        | 1.34%   |
| 46      | 3        | 1.01%   |
| 36      | 3        | 1.01%   |
| 25      | 3        | 1.01%   |
| 20      | 3        | 1.01%   |
| 84      | 2        | 0.67%   |
| 142     | 1        | 0.34%   |
| 69      | 1        | 0.34%   |
| 65      | 1        | 0.34%   |
| 60      | 1        | 0.34%   |
| 55      | 1        | 0.34%   |
| 54      | 1        | 0.34%   |
| 49      | 1        | 0.34%   |
| 48      | 1        | 0.34%   |
| 43      | 1        | 0.34%   |
| 38      | 1        | 0.34%   |
| 37      | 1        | 0.34%   |
| 33      | 1        | 0.34%   |
| 28      | 1        | 0.34%   |
| 26      | 1        | 0.34%   |
| 15      | 1        | 0.34%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 118      | 41.7%   |
| 401-500        | 62       | 21.91%  |
| 601-700        | 30       | 10.6%   |
| 701-800        | 22       | 7.77%   |
| Unknown        | 15       | 5.3%    |
| 1001-1500      | 9        | 3.18%   |
| 1501-2000      | 8        | 2.83%   |
| 801-900        | 6        | 2.12%   |
| 351-400        | 6        | 2.12%   |
| 301-350        | 5        | 1.77%   |
| More than 2000 | 1        | 0.35%   |
| 901-1000       | 1        | 0.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 188      | 72.31%  |
| 16/10   | 32       | 12.31%  |
| 21/9    | 14       | 5.38%   |
| Unknown | 12       | 4.62%   |
| 5/4     | 10       | 3.85%   |
| 32/9    | 2        | 0.77%   |
| 3/2     | 1        | 0.38%   |
| 1.00    | 1        | 0.38%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 101      | 35.31%  |
| 301-350        | 43       | 15.03%  |
| 351-500        | 39       | 13.64%  |
| 151-200        | 27       | 9.44%   |
| 251-300        | 21       | 7.34%   |
| 501-1000       | 15       | 5.24%   |
| Unknown        | 15       | 5.24%   |
| More than 1000 | 13       | 4.55%   |
| 141-150        | 11       | 3.85%   |
| 101-110        | 1        | 0.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 159      | 60.69%  |
| 101-120 | 50       | 19.08%  |
| 1-50    | 17       | 6.49%   |
| 121-160 | 17       | 6.49%   |
| Unknown | 15       | 5.73%   |
| 161-240 | 4        | 1.53%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 170      | 65.89%  |
| 2     | 71       | 27.52%  |
| 0     | 11       | 4.26%   |
| 3     | 5        | 1.94%   |
| 4     | 1        | 0.39%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 166      | 42.78%  |
| Intel                           | 121      | 31.19%  |
| Qualcomm Atheros                | 22       | 5.67%   |
| Broadcom                        | 13       | 3.35%   |
| Ralink Technology               | 11       | 2.84%   |
| TP-Link                         | 8        | 2.06%   |
| Aquantia                        | 8        | 2.06%   |
| MediaTek                        | 5        | 1.29%   |
| Ralink                          | 4        | 1.03%   |
| Huawei Technologies             | 4        | 1.03%   |
| Samsung Electronics             | 3        | 0.77%   |
| Xiaomi                          | 2        | 0.52%   |
| D-Link                          | 2        | 0.52%   |
| ASUSTek Computer                | 2        | 0.52%   |
| ASIX Electronics                | 2        | 0.52%   |
| ZyXEL Communications            | 1        | 0.26%   |
| Wilocity                        | 1        | 0.26%   |
| VIA Technologies                | 1        | 0.26%   |
| U-Blox                          | 1        | 0.26%   |
| Qualcomm Atheros Communications | 1        | 0.26%   |
| NetGear                         | 1        | 0.26%   |
| Microsoft                       | 1        | 0.26%   |
| Mercucys                        | 1        | 0.26%   |
| Linksys                         | 1        | 0.26%   |
| LG Electronics                  | 1        | 0.26%   |
| Edimax Technology               | 1        | 0.26%   |
| DisplayLink                     | 1        | 0.26%   |
| D-Link System                   | 1        | 0.26%   |
| Bose                            | 1        | 0.26%   |
| Belkin Components               | 1        | 0.26%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 123      | 27.7%   |
| Realtek RTL8125 2.5GbE Controller                                 | 19       | 4.28%   |
| Intel I211 Gigabit Network Connection                             | 16       | 3.6%    |
| Intel Ethernet Controller I225-V                                  | 16       | 3.6%    |
| Intel Wi-Fi 6 AX200                                               | 14       | 3.15%   |
| Intel Ethernet Connection (2) I219-V                              | 9        | 2.03%   |
| Realtek 802.11ac NIC                                              | 8        | 1.8%    |
| Intel Ethernet Connection I217-LM                                 | 8        | 1.8%    |
| Intel Ethernet Connection (7) I219-V                              | 8        | 1.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7        | 1.58%   |
| Intel Ethernet Connection (2) I218-V                              | 6        | 1.35%   |
| Intel Ethernet Connection (14) I219-V                             | 6        | 1.35%   |
| Intel 82579V Gigabit Network Connection                           | 6        | 1.35%   |
| Intel 82574L Gigabit Network Connection                           | 6        | 1.35%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 6        | 1.35%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 6        | 1.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5        | 1.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 5        | 1.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5        | 1.13%   |
| Ralink RT5370 Wireless Adapter                                    | 4        | 0.9%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 4        | 0.9%    |
| Intel Wireless-AC 9260                                            | 4        | 0.9%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4        | 0.9%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4        | 0.9%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 3        | 0.68%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 3        | 0.68%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 3        | 0.68%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 0.68%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3        | 0.68%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 3        | 0.68%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 3        | 0.68%   |
| Intel Wireless 7260                                               | 3        | 0.68%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3        | 0.68%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3        | 0.68%   |
| Huawei ANA-NX9                                                    | 3        | 0.68%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 0.45%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 2        | 0.45%   |
| TP-Link 802.11ac NIC                                              | 2        | 0.45%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.45%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 2        | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 45       | 30.61%  |
| Realtek Semiconductor           | 36       | 24.49%  |
| Qualcomm Atheros                | 13       | 8.84%   |
| Ralink Technology               | 11       | 7.48%   |
| Broadcom                        | 11       | 7.48%   |
| TP-Link                         | 8        | 5.44%   |
| Ralink                          | 4        | 2.72%   |
| MediaTek                        | 4        | 2.72%   |
| D-Link                          | 2        | 1.36%   |
| ASUSTek Computer                | 2        | 1.36%   |
| ZyXEL Communications            | 1        | 0.68%   |
| Wilocity                        | 1        | 0.68%   |
| Qualcomm Atheros Communications | 1        | 0.68%   |
| NetGear                         | 1        | 0.68%   |
| Microsoft                       | 1        | 0.68%   |
| Mercucys                        | 1        | 0.68%   |
| Linksys                         | 1        | 0.68%   |
| LG Electronics                  | 1        | 0.68%   |
| Edimax Technology               | 1        | 0.68%   |
| D-Link System                   | 1        | 0.68%   |
| Belkin Components               | 1        | 0.68%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                        | 14       | 9.33%   |
| Realtek 802.11ac NIC                                       | 8        | 5.33%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter         | 6        | 4%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 5        | 3.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 5        | 3.33%   |
| Ralink RT5370 Wireless Adapter                             | 4        | 2.67%   |
| Intel Wireless-AC 9260                                     | 4        | 2.67%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 4        | 2.67%   |
| Intel Cannon Lake PCH CNVi WiFi                            | 4        | 2.67%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter   | 3        | 2%      |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                 | 3        | 2%      |
| Realtek RTL8192EE PCIe Wireless Network Adapter            | 3        | 2%      |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 3        | 2%      |
| Qualcomm Atheros AR93xx Wireless Network Adapter           | 3        | 2%      |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                    | 3        | 2%      |
| Intel Wireless 7260                                        | 3        | 2%      |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 3        | 2%      |
| Intel Comet Lake PCH CNVi WiFi                             | 3        | 2%      |
| TP-Link Archer T3U [Realtek RTL8812BU]                     | 2        | 1.33%   |
| TP-Link 802.11ac NIC                                       | 2        | 1.33%   |
| Ralink RT2870/RT3070 Wireless Adapter                      | 2        | 1.33%   |
| Ralink MT7601U Wireless Adapter                            | 2        | 1.33%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                  | 2        | 1.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 2        | 1.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter           | 2        | 1.33%   |
| Intel Wireless 8260                                        | 2        | 1.33%   |
| Intel Wireless 3165                                        | 2        | 1.33%   |
| Intel Tiger Lake PCH CNVi WiFi                             | 2        | 1.33%   |
| ZyXEL ZyAIR G-202 802.11bg                                 | 1        | 0.67%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter         | 1        | 0.67%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                | 1        | 0.67%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                        | 1        | 0.67%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                 | 1        | 0.67%   |
| TP-Link 802.11ac WLAN Adapter                              | 1        | 0.67%   |
| Realtek RTL88x2bu [AC1200 Techkey]                         | 1        | 0.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 1        | 0.67%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter    | 1        | 0.67%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                 | 1        | 0.67%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter            | 1        | 0.67%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                     | 1        | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 149      | 51.92%  |
| Intel                 | 102      | 35.54%  |
| Qualcomm Atheros      | 10       | 3.48%   |
| Aquantia              | 8        | 2.79%   |
| Huawei Technologies   | 4        | 1.39%   |
| Broadcom              | 4        | 1.39%   |
| Samsung Electronics   | 3        | 1.05%   |
| Xiaomi                | 2        | 0.7%    |
| ASIX Electronics      | 2        | 0.7%    |
| VIA Technologies      | 1        | 0.35%   |
| MediaTek              | 1        | 0.35%   |
| DisplayLink           | 1        | 0.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 123      | 42.12%  |
| Realtek RTL8125 2.5GbE Controller                                 | 19       | 6.51%   |
| Intel I211 Gigabit Network Connection                             | 16       | 5.48%   |
| Intel Ethernet Controller I225-V                                  | 16       | 5.48%   |
| Intel Ethernet Connection (2) I219-V                              | 9        | 3.08%   |
| Intel Ethernet Connection I217-LM                                 | 8        | 2.74%   |
| Intel Ethernet Connection (7) I219-V                              | 8        | 2.74%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7        | 2.4%    |
| Intel Ethernet Connection (2) I218-V                              | 6        | 2.05%   |
| Intel Ethernet Connection (14) I219-V                             | 6        | 2.05%   |
| Intel 82579V Gigabit Network Connection                           | 6        | 2.05%   |
| Intel 82574L Gigabit Network Connection                           | 6        | 2.05%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 6        | 2.05%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5        | 1.71%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 4        | 1.37%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 1.03%   |
| Huawei ANA-NX9                                                    | 3        | 1.03%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 0.68%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.68%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2        | 0.68%   |
| Intel I210 Gigabit Network Connection                             | 2        | 0.68%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 0.68%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 0.68%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2        | 0.68%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1        | 0.34%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 0.34%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.34%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.34%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1        | 0.34%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.34%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.34%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.34%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.34%   |
| MediaTek U318AA                                                   | 1        | 0.34%   |
| Intel I350 Gigabit Network Connection                             | 1        | 0.34%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1        | 0.34%   |
| Intel Ethernet Connection I218-LM                                 | 1        | 0.34%   |
| Intel Ethernet Connection I217-V                                  | 1        | 0.34%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.34%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 255      | 64.56%  |
| WiFi     | 138      | 34.94%  |
| Modem    | 2        | 0.51%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 192      | 73%     |
| WiFi     | 71       | 27%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 153      | 59.53%  |
| 2     | 88       | 34.24%  |
| 3     | 13       | 5.06%   |
| 4     | 2        | 0.78%   |
| 6     | 1        | 0.39%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 176      | 68.22%  |
| Yes  | 82       | 31.78%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 41       | 34.75%  |
| Cambridge Silicon Radio         | 33       | 27.97%  |
| Realtek Semiconductor           | 12       | 10.17%  |
| ASUSTek Computer                | 10       | 8.47%   |
| MediaTek                        | 5        | 4.24%   |
| Broadcom                        | 4        | 3.39%   |
| Qualcomm Atheros Communications | 3        | 2.54%   |
| IMC Networks                    | 3        | 2.54%   |
| Edimax Technology               | 3        | 2.54%   |
| TP-Link                         | 2        | 1.69%   |
| Conwise Technology              | 1        | 0.85%   |
| Apple                           | 1        | 0.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)     | 33       | 27.73%  |
| Intel AX200 Bluetooth                                   | 14       | 11.76%  |
| Realtek Bluetooth Radio                                 | 9        | 7.56%   |
| Intel Bluetooth wireless interface                      | 7        | 5.88%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)          | 6        | 5.04%   |
| MediaTek Wireless_Device                                | 5        | 4.2%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                | 4        | 3.36%   |
| Intel Wireless-AC 3168 Bluetooth                        | 4        | 3.36%   |
| ASUS ASUS USB-BT500                                     | 4        | 3.36%   |
| Realtek  Bluetooth 4.2 Adapter                          | 3        | 2.52%   |
| Qualcomm Atheros  Bluetooth Device                      | 3        | 2.52%   |
| Intel AX210 Bluetooth                                   | 3        | 2.52%   |
| Intel AX201 Bluetooth                                   | 3        | 2.52%   |
| IMC Networks Bluetooth Radio                            | 3        | 2.52%   |
| Broadcom BCM20702A0 Bluetooth 4.0                       | 3        | 2.52%   |
| TP-Link UB500 Adapter                                   | 2        | 1.68%   |
| ASUS Qualcomm Bluetooth 4.1                             | 2        | 1.68%   |
| Intel Bluetooth Device                                  | 1        | 0.84%   |
| Edimax Wi-Fi AC600 Bluetooth4.0 USB Adapter             | 1        | 0.84%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter | 1        | 0.84%   |
| Edimax Bluetooth Adapter                                | 1        | 0.84%   |
| Conwise CW6622                                          | 1        | 0.84%   |
| Broadcom BCM43142 Bluetooth 4.0                         | 1        | 0.84%   |
| ASUS Broadcom BCM20702A0 Bluetooth                      | 1        | 0.84%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE   | 1        | 0.84%   |
| ASUS Bluetooth Device                                   | 1        | 0.84%   |
| ASUS Bluetooth Adapter                                  | 1        | 0.84%   |
| Apple Bluetooth Host Controller                         | 1        | 0.84%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 147      | 29.4%   |
| AMD                      | 135      | 27%     |
| Nvidia                   | 128      | 25.6%   |
| C-Media Electronics      | 14       | 2.8%    |
| GN Netcom                | 7        | 1.4%    |
| JMTek                    | 4        | 0.8%    |
| Generalplus Technology   | 4        | 0.8%    |
| Creative Labs            | 4        | 0.8%    |
| VIA Technologies         | 3        | 0.6%    |
| Texas Instruments        | 3        | 0.6%    |
| Tenx Technology          | 3        | 0.6%    |
| Razer USA                | 3        | 0.6%    |
| Kingston Technology      | 3        | 0.6%    |
| Blue Microphones         | 3        | 0.6%    |
| SteelSeries ApS          | 2        | 0.4%    |
| Micro Star International | 2        | 0.4%    |
| M-Audio                  | 2        | 0.4%    |
| KORG                     | 2        | 0.4%    |
| BY EDIFIER               | 2        | 0.4%    |
| ASUSTek Computer         | 2        | 0.4%    |
| ZOOM                     | 1        | 0.2%    |
| Yamaha                   | 1        | 0.2%    |
| Veho                     | 1        | 0.2%    |
| Unknown (ABC)            | 1        | 0.2%    |
| Unknown                  | 1        | 0.2%    |
| TerraTec Electronic      | 1        | 0.2%    |
| Samson Technologies      | 1        | 0.2%    |
| Roland                   | 1        | 0.2%    |
| QinHeng Electronics      | 1        | 0.2%    |
| Philips (or NXP)         | 1        | 0.2%    |
| Nordic Semiconductor ASA | 1        | 0.2%    |
| Microsoft                | 1        | 0.2%    |
| Microdia                 | 1        | 0.2%    |
| Mark of the Unicorn      | 1        | 0.2%    |
| Logitech                 | 1        | 0.2%    |
| Lenovo                   | 1        | 0.2%    |
| Hangzhou Worlde          | 1        | 0.2%    |
| Focusrite-Novation       | 1        | 0.2%    |
| DSEA A/S                 | 1        | 0.2%    |
| Dell                     | 1        | 0.2%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 37       | 6.42%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 23       | 3.99%   |
| AMD Family 17h/19h HD Audio Controller                                     | 20       | 3.47%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 17       | 2.95%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 17       | 2.95%   |
| Nvidia GP107GL High Definition Audio Controller                            | 14       | 2.43%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 14       | 2.43%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 14       | 2.43%   |
| Intel 200 Series PCH HD Audio                                              | 13       | 2.26%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 13       | 2.26%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 13       | 2.26%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 12       | 2.08%   |
| Nvidia TU116 High Definition Audio Controller                              | 11       | 1.91%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 11       | 1.91%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 11       | 1.91%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 10       | 1.74%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 10       | 1.74%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 9        | 1.56%   |
| Intel Cannon Lake PCH cAVS                                                 | 9        | 1.56%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 9        | 1.56%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 9        | 1.56%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 8        | 1.39%   |
| Nvidia GP106 High Definition Audio Controller                              | 7        | 1.22%   |
| Nvidia GP104 High Definition Audio Controller                              | 7        | 1.22%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 7        | 1.22%   |
| Nvidia TU104 HD Audio Controller                                           | 6        | 1.04%   |
| Nvidia GP108 High Definition Audio Controller                              | 6        | 1.04%   |
| Nvidia GA104 High Definition Audio Controller                              | 6        | 1.04%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 6        | 1.04%   |
| Intel Comet Lake PCH cAVS                                                  | 6        | 1.04%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 5        | 0.87%   |
| Nvidia High Definition Audio Controller                                    | 5        | 0.87%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 5        | 0.87%   |
| Intel Alder Lake-S HD Audio Controller                                     | 5        | 0.87%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 5        | 0.87%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 5        | 0.87%   |
| Nvidia TU106 High Definition Audio Controller                              | 4        | 0.69%   |
| Nvidia TU102 High Definition Audio Controller                              | 4        | 0.69%   |
| Nvidia GM204 High Definition Audio Controller                              | 4        | 0.69%   |
| Nvidia GF119 HDMI Audio Controller                                         | 4        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 39       | 22.29%  |
| Corsair             | 27       | 15.43%  |
| G.Skill             | 23       | 13.14%  |
| Crucial             | 15       | 8.57%   |
| Unknown             | 11       | 6.29%   |
| Samsung Electronics | 11       | 6.29%   |
| SK hynix            | 9        | 5.14%   |
| Micron Technology   | 9        | 5.14%   |
| Team                | 5        | 2.86%   |
| Ramaxel Technology  | 4        | 2.29%   |
| Patriot             | 3        | 1.71%   |
| AMD                 | 3        | 1.71%   |
| Unknown             | 3        | 1.71%   |
| PNY                 | 2        | 1.14%   |
| Unifosa             | 1        | 0.57%   |
| Smart               | 1        | 0.57%   |
| Silicon Power       | 1        | 0.57%   |
| Qumo                | 1        | 0.57%   |
| Neo Forza           | 1        | 0.57%   |
| Nanya Technology    | 1        | 0.57%   |
| Lexar               | 1        | 0.57%   |
| Kingmax             | 1        | 0.57%   |
| Avant               | 1        | 0.57%   |
| Atermiter           | 1        | 0.57%   |
| A-DATA Technology   | 1        | 0.57%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 3        | 1.57%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s | 3        | 1.57%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s  | 3        | 1.57%   |
| Unknown                                                | 3        | 1.57%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s    | 2        | 1.05%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2400MT/s  | 2        | 1.05%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s    | 2        | 1.05%   |
| Ramaxel RAM RMR5040ED58E9W1600 4GB DIMM 1600MT/s       | 2        | 1.05%   |
| Micron RAM 8ATF1G64AZ-2G6E1 8GB DIMM DDR4 2667MT/s     | 2        | 1.05%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s  | 2        | 1.05%   |
| Kingston RAM 9905471-079.A00LF 8GB DIMM DDR3 1600MT/s  | 2        | 1.05%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s    | 2        | 1.05%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s    | 2        | 1.05%   |
| Crucial RAM CT8G4DFRA266.C8FE 8GB DIMM DDR4 2933MT/s   | 2        | 1.05%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s  | 2        | 1.05%   |
| Corsair RAM CMK32GX4M2Z3600C18 16GB DIMM DDR4 3800MT/s | 2        | 1.05%   |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3200MT/s  | 2        | 1.05%   |
| AMD RAM R9S48G3206U2S 8GB DIMM DDR4 3333MT/s           | 2        | 1.05%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s              | 1        | 0.52%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s              | 1        | 0.52%   |
| Unknown RAM Module 8GB DIMM 400MT/s                    | 1        | 0.52%   |
| Unknown RAM Module 4GB DIMM 667MT/s                    | 1        | 0.52%   |
| Unknown RAM Module 2GB DIMM SDRAM 1066MT/s             | 1        | 0.52%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                   | 1        | 0.52%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s               | 1        | 0.52%   |
| Unknown RAM Module 16GB DIMM DDR4 2667MT/s             | 1        | 0.52%   |
| Unknown RAM 3600 C20 Series 32GB DIMM DDR4 3666MT/s    | 1        | 0.52%   |
| Unifosa RAM Module 2GB DIMM DDR3 1333MT/s              | 1        | 0.52%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s     | 1        | 0.52%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s     | 1        | 0.52%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3000MT/s     | 1        | 0.52%   |
| Smart RAM Module 8GB SODIMM DDR4 2133MT/s              | 1        | 0.52%   |
| SK hynix RAM Module 8GB DIMM DDR4 2133MT/s             | 1        | 0.52%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s   | 1        | 0.52%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1648MT/s   | 1        | 0.52%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s   | 1        | 0.52%   |
| SK hynix RAM HMT451U6AFR8A-PB 4GB DIMM DDR3 1600MT/s   | 1        | 0.52%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB DIMM DDR3 1600MT/s   | 1        | 0.52%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s   | 1        | 0.52%   |
| SK hynix RAM HMT351R7CFR8C-PB 4GB DIMM DDR3 1600MT/s   | 1        | 0.52%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 104      | 64.2%   |
| DDR3    | 40       | 24.69%  |
| Unknown | 6        | 3.7%    |
| SDRAM   | 5        | 3.09%   |
| DDR5    | 4        | 2.47%   |
| DDR2    | 3        | 1.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 151      | 94.97%  |
| SODIMM | 7        | 4.4%    |
| RIMM   | 1        | 0.63%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 75       | 43.86%  |
| 16384 | 44       | 25.73%  |
| 4096  | 26       | 15.2%   |
| 2048  | 13       | 7.6%    |
| 32768 | 12       | 7.02%   |
| 1024  | 1        | 0.58%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 27       | 15.43%  |
| 3600  | 19       | 10.86%  |
| 3200  | 19       | 10.86%  |
| 2667  | 15       | 8.57%   |
| 1333  | 15       | 8.57%   |
| 2400  | 11       | 6.29%   |
| 2133  | 10       | 5.71%   |
| 3800  | 5        | 2.86%   |
| 3000  | 5        | 2.86%   |
| 2666  | 5        | 2.86%   |
| 1867  | 4        | 2.29%   |
| 3333  | 3        | 1.71%   |
| 3266  | 3        | 1.71%   |
| 3066  | 3        | 1.71%   |
| 1066  | 3        | 1.71%   |
| 6000  | 2        | 1.14%   |
| 3866  | 2        | 1.14%   |
| 3666  | 2        | 1.14%   |
| 3466  | 2        | 1.14%   |
| 2933  | 2        | 1.14%   |
| 52217 | 1        | 0.57%   |
| 5800  | 1        | 0.57%   |
| 4800  | 1        | 0.57%   |
| 4133  | 1        | 0.57%   |
| 4000  | 1        | 0.57%   |
| 3733  | 1        | 0.57%   |
| 3467  | 1        | 0.57%   |
| 3400  | 1        | 0.57%   |
| 3334  | 1        | 0.57%   |
| 2800  | 1        | 0.57%   |
| 2448  | 1        | 0.57%   |
| 2176  | 1        | 0.57%   |
| 2134  | 1        | 0.57%   |
| 1866  | 1        | 0.57%   |
| 1648  | 1        | 0.57%   |
| 800   | 1        | 0.57%   |
| 667   | 1        | 0.57%   |
| 400   | 1        | 0.57%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 7        | 35%     |
| Seiko Epson         | 3        | 15%     |
| Samsung Electronics | 2        | 10%     |
| Canon               | 2        | 10%     |
| Brother Industries  | 2        | 10%     |
| Xerox               | 1        | 5%      |
| Kyocera             | 1        | 5%      |
| Dymo-CoStar         | 1        | 5%      |
| Datamax-O'Neil      | 1        | 5%      |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Samsung M2070 Series                  | 2        | 10%     |
| Xerox Phaser 3140 and 3155            | 1        | 5%      |
| Seiko Epson XP-3100 Series            | 1        | 5%      |
| Seiko Epson L3110 Series              | 1        | 5%      |
| Seiko Epson L220 Series               | 1        | 5%      |
| Kyocera Mita FS-820                   | 1        | 5%      |
| HP OfficeJet 5500 series              | 1        | 5%      |
| HP LaserJet P2015 series              | 1        | 5%      |
| HP LaserJet 1022                      | 1        | 5%      |
| HP ENVY 4500 series                   | 1        | 5%      |
| HP DeskJet D2300                      | 1        | 5%      |
| HP DeskJet 3630 series                | 1        | 5%      |
| HP ColorLaserJet M253-M254            | 1        | 5%      |
| Dymo-CoStar LabelWriter 450           | 1        | 5%      |
| Datamax-O'Neil Datamax E-4304         | 1        | 5%      |
| Canon PIXMA MX470 Series              | 1        | 5%      |
| Canon LaserShot LBP-1120 Printer      | 1        | 5%      |
| Brother PT-P700 P-touch Label Printer | 1        | 5%      |
| Brother MFC-J460DW                    | 1        | 5%      |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| Canon          | 5        | 71.43%  |
| Seiko Epson    | 1        | 14.29%  |
| Mustek Systems | 1        | 14.29%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40      | 2        | 28.57%  |
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1        | 14.29%  |
| Mustek Systems ScanExpress A3 USB 1200 PRO  | 1        | 14.29%  |
| Canon CanoScan N670U/N676U/LiDE 20          | 1        | 14.29%  |
| Canon CanoScan LiDE 220                     | 1        | 14.29%  |
| Canon CanoScan LiDE 210                     | 1        | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 27       | 41.54%  |
| Microdia                      | 7        | 10.77%  |
| Sunplus Innovation Technology | 3        | 4.62%   |
| Microsoft                     | 3        | 4.62%   |
| Generalplus Technology        | 3        | 4.62%   |
| Unknown                       | 2        | 3.08%   |
| Samsung Electronics           | 2        | 3.08%   |
| Realtek Semiconductor         | 2        | 3.08%   |
| KYE Systems (Mouse Systems)   | 2        | 3.08%   |
| Jieli Technology              | 2        | 3.08%   |
| Alcor Micro                   | 2        | 3.08%   |
| YGTek                         | 1        | 1.54%   |
| Silicon Motion                | 1        | 1.54%   |
| Razer USA                     | 1        | 1.54%   |
| IMC Networks                  | 1        | 1.54%   |
| Hewlett-Packard               | 1        | 1.54%   |
| Google                        | 1        | 1.54%   |
| Cubeternet                    | 1        | 1.54%   |
| Creative Technology           | 1        | 1.54%   |
| Asuscom Network               | 1        | 1.54%   |
| ARC International             | 1        | 1.54%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                                         | 7        | 10.77%  |
| Logitech Webcam C270                                                | 6        | 9.23%   |
| Logitech C920 PRO HD Webcam                                         | 3        | 4.62%   |
| Unknown HD camera                                                   | 2        | 3.08%   |
| Samsung Galaxy A5 (MTP)                                             | 2        | 3.08%   |
| Microdia Webcam Vitade AF                                           | 2        | 3.08%   |
| Microdia Integrated Camera                                          | 2        | 3.08%   |
| Logitech Webcam C170                                                | 2        | 3.08%   |
| Logitech HD Webcam C910                                             | 2        | 3.08%   |
| Logitech HD Webcam C525                                             | 2        | 3.08%   |
| Jieli USB PHY 2.0                                                   | 2        | 3.08%   |
| Generalplus GENERAL WEBCAM                                          | 2        | 3.08%   |
| Alcor Micro USB 2.0 PC Camera                                       | 2        | 3.08%   |
| YGTek Webcam                                                        | 1        | 1.54%   |
| Sunplus UC40M Audio                                                 | 1        | 1.54%   |
| Sunplus SPCA2281 Web Camera                                         | 1        | 1.54%   |
| Sunplus ezcap U3 capture-04                                         | 1        | 1.54%   |
| Silicon Motion 300k Pixel Camera                                    | 1        | 1.54%   |
| Realtek USB Camera                                                  | 1        | 1.54%   |
| Realtek HK 2M CAM                                                   | 1        | 1.54%   |
| Razer USA Razer Kiyo Pro                                            | 1        | 1.54%   |
| Microsoft MicrosoftÂ LifeCam Studio                                | 1        | 1.54%   |
| Microsoft LifeCam HD-3000                                           | 1        | 1.54%   |
| Microsoft LifeCam Cinema                                            | 1        | 1.54%   |
| Microdia USB 2.0 Camera                                             | 1        | 1.54%   |
| Microdia PC Microscope camera                                       | 1        | 1.54%   |
| Microdia Camera                                                     | 1        | 1.54%   |
| Logitech Webcam C310                                                | 1        | 1.54%   |
| Logitech QuickCam Pro for Notebooks                                 | 1        | 1.54%   |
| Logitech HD Webcam C615                                             | 1        | 1.54%   |
| Logitech C922 Pro Stream Webcam                                     | 1        | 1.54%   |
| Logitech BRIO Ultra HD Webcam                                       | 1        | 1.54%   |
| KYE Systems (Mouse Systems) PC-W3 Camera                            | 1        | 1.54%   |
| KYE Systems (Mouse Systems) eFace 2025                              | 1        | 1.54%   |
| IMC Networks UVC VGA Webcam                                         | 1        | 1.54%   |
| HP Webcam 1300                                                      | 1        | 1.54%   |
| Google Nexus/Pixel Device (MTP + debug)                             | 1        | 1.54%   |
| Generalplus 808 Camera #9 (web-cam mode)                            | 1        | 1.54%   |
| Cubeternet EtronTech CMOS based eSP570 WebCam [Onyx Titanium TC101] | 1        | 1.54%   |
| Creative Live! Cam Sync 1080p                                       | 1        | 1.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor    | Desktops | Percent |
|-----------|----------|---------|
| Synaptics | 2        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Synaptics  WBDI Fingerprint Reader - USB 052 | 2        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| SCM Microsystems      | 1        | 25%     |
| OmniKey               | 1        | 25%     |
| Gemalto (was Gemplus) | 1        | 25%     |
| BIT4ID                | 1        | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| SCM Microsystems SCR331 SmartCard Reader          | 1        | 25%     |
| OmniKey CardMan 1021                              | 1        | 25%     |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 1        | 25%     |
| BIT4ID miniLector EVO                             | 1        | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 207      | 79.92%  |
| 1     | 42       | 16.22%  |
| 2     | 7        | 2.7%    |
| 3     | 3        | 1.16%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 18       | 29.51%  |
| Graphics card            | 14       | 22.95%  |
| Unassigned class         | 9        | 14.75%  |
| Multimedia controller    | 3        | 4.92%   |
| Communication controller | 3        | 4.92%   |
| Chipcard                 | 3        | 4.92%   |
| Camera                   | 3        | 4.92%   |
| Bluetooth                | 3        | 4.92%   |
| Sound                    | 2        | 3.28%   |
| Fingerprint reader       | 2        | 3.28%   |
| Net/ethernet             | 1        | 1.64%   |

