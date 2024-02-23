Linux in Spain - Tested Hardware & Statistics (Desktops)
--------------------------------------------------------

A project to collect tested hardware configurations for Linux in Spain.

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

Total: 3443

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | M4N72-E                     | [815b251540](https://linux-hardware.org/?probe=815b251540) | Feb 02, 2024 |
| Gigabyte      | AB350M-Gaming 3-CF          | [ef41c12950](https://linux-hardware.org/?probe=ef41c12950) | Feb 02, 2024 |
| Intel         | X99-P4 V5.1                 | [092e51b68e](https://linux-hardware.org/?probe=092e51b68e) | Feb 02, 2024 |
| Gigabyte      | H61M-S1                     | [e7f247621c](https://linux-hardware.org/?probe=e7f247621c) | Feb 02, 2024 |
| ASUSTek       | H110M-D                     | [287648c7d3](https://linux-hardware.org/?probe=287648c7d3) | Feb 01, 2024 |
| ASRock        | X370M-HDV                   | [64edf5f2dc](https://linux-hardware.org/?probe=64edf5f2dc) | Feb 01, 2024 |
| Gigabyte      | B75M-D3H                    | [b1b2694b98](https://linux-hardware.org/?probe=b1b2694b98) | Jan 30, 2024 |
| ASUSTek       | ROG Maximus Z790 DARK HE... | [64433c2a96](https://linux-hardware.org/?probe=64433c2a96) | Jan 29, 2024 |
| ASUSTek       | PRIME Z590-A                | [907099b1e7](https://linux-hardware.org/?probe=907099b1e7) | Jan 29, 2024 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | [29fcd258c7](https://linux-hardware.org/?probe=29fcd258c7) | Jan 28, 2024 |
| ASRock        | Z690 Phantom Gaming-ITX/... | [fe3286f6e5](https://linux-hardware.org/?probe=fe3286f6e5) | Jan 28, 2024 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [26c552f089](https://linux-hardware.org/?probe=26c552f089) | Jan 27, 2024 |
| Gigabyte      | AX370-Gaming 5              | [579b4a4daa](https://linux-hardware.org/?probe=579b4a4daa) | Jan 26, 2024 |
| ASUSTek       | ROG Maximus Z790 DARK HE... | [aa9e38d0e2](https://linux-hardware.org/?probe=aa9e38d0e2) | Jan 26, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | [c0bdeb8655](https://linux-hardware.org/?probe=c0bdeb8655) | Jan 25, 2024 |
| MSI           | B560M PRO-VDH               | [e64338286f](https://linux-hardware.org/?probe=e64338286f) | Jan 24, 2024 |
| Dell          | 00V62H A01                  | [83f7e8b344](https://linux-hardware.org/?probe=83f7e8b344) | Jan 24, 2024 |
| Intel         | Unknown                     | [8427ffd0dc](https://linux-hardware.org/?probe=8427ffd0dc) | Jan 23, 2024 |
| HP            | 0A5Ch                       | [f886596563](https://linux-hardware.org/?probe=f886596563) | Jan 23, 2024 |
| MSI           | B350M MORTAR                | [f728e7ad76](https://linux-hardware.org/?probe=f728e7ad76) | Jan 22, 2024 |
| ASUSTek       | PRIME B550M-A               | [ed85e4518e](https://linux-hardware.org/?probe=ed85e4518e) | Jan 22, 2024 |
| ASUSTek       | B85M-G                      | [3941eb54fd](https://linux-hardware.org/?probe=3941eb54fd) | Jan 21, 2024 |
| ASUSTek       | TUF Gaming X570-PRO         | [248ddfc03e](https://linux-hardware.org/?probe=248ddfc03e) | Jan 21, 2024 |
| ASUSTek       | TUF Gaming X570-PRO         | [5e268775c9](https://linux-hardware.org/?probe=5e268775c9) | Jan 21, 2024 |
| Foxconn       | 2A8C                        | [591fafe62b](https://linux-hardware.org/?probe=591fafe62b) | Jan 21, 2024 |
| Dell          | 00V62H A01                  | [7104f7e7cf](https://linux-hardware.org/?probe=7104f7e7cf) | Jan 21, 2024 |
| Intel         | X99                         | [44d8693e2b](https://linux-hardware.org/?probe=44d8693e2b) | Jan 18, 2024 |
| ASUSTek       | PRIME H310M-E               | [6674d084a8](https://linux-hardware.org/?probe=6674d084a8) | Jan 18, 2024 |
| Gigabyte      | Z77-DS3H                    | [08a4e7960a](https://linux-hardware.org/?probe=08a4e7960a) | Jan 18, 2024 |
| MSI           | B560M PRO-VDH               | [cc460a0905](https://linux-hardware.org/?probe=cc460a0905) | Jan 16, 2024 |
| HP            | 8750                        | [6dd29a1c24](https://linux-hardware.org/?probe=6dd29a1c24) | Jan 16, 2024 |
| Lenovo        | 30D9 SDK0J40697 WIN 3305... | [eddee431eb](https://linux-hardware.org/?probe=eddee431eb) | Jan 16, 2024 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [6b8df5e5f8](https://linux-hardware.org/?probe=6b8df5e5f8) | Jan 16, 2024 |
| MSI           | B85-G41 PC Mate             | [a31032a308](https://linux-hardware.org/?probe=a31032a308) | Jan 15, 2024 |
| Gigabyte      | X99-UD4-CF                  | [662828b0e7](https://linux-hardware.org/?probe=662828b0e7) | Jan 15, 2024 |
| Intel         | X99-P4 V5.0                 | [574a971f93](https://linux-hardware.org/?probe=574a971f93) | Jan 14, 2024 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [c4edc08fb7](https://linux-hardware.org/?probe=c4edc08fb7) | Jan 14, 2024 |
| MSI           | A320M-A PRO                 | [4f2655db6f](https://linux-hardware.org/?probe=4f2655db6f) | Jan 14, 2024 |
| Gigabyte      | AX370-Gaming 5              | [44ec140279](https://linux-hardware.org/?probe=44ec140279) | Jan 14, 2024 |
| ASUSTek       | P8H61-M2 USB3               | [705185dd25](https://linux-hardware.org/?probe=705185dd25) | Jan 13, 2024 |
| Gigabyte      | H510M H V2                  | [1340d91b43](https://linux-hardware.org/?probe=1340d91b43) | Jan 13, 2024 |
| MSI           | H97 PC Mate                 | [b9df3e4a61](https://linux-hardware.org/?probe=b9df3e4a61) | Jan 12, 2024 |
| Acer          | Veriton X490G               | [1110362d9a](https://linux-hardware.org/?probe=1110362d9a) | Jan 11, 2024 |
| ASRock        | 970 Pro3 R2.0               | [ca8734dc63](https://linux-hardware.org/?probe=ca8734dc63) | Jan 11, 2024 |
| MSI           | B450M MORTAR TITANIUM       | [03202bdde9](https://linux-hardware.org/?probe=03202bdde9) | Jan 10, 2024 |
| ASUSTek       | M4N78                       | [b9b072474d](https://linux-hardware.org/?probe=b9b072474d) | Jan 10, 2024 |
| MSI           | MPG B550 GAMING PLUS        | [757c6f2826](https://linux-hardware.org/?probe=757c6f2826) | Jan 10, 2024 |
| MSI           | B450M MORTAR TITANIUM       | [cd8ee8db1f](https://linux-hardware.org/?probe=cd8ee8db1f) | Jan 09, 2024 |
| Intel         | X99H                        | [b0bb3cb105](https://linux-hardware.org/?probe=b0bb3cb105) | Jan 09, 2024 |
| Gigabyte      | H510M S2H V2                | [48ba042e53](https://linux-hardware.org/?probe=48ba042e53) | Jan 08, 2024 |
| ASRock        | J5040-ITX                   | [2dc9e2367b](https://linux-hardware.org/?probe=2dc9e2367b) | Jan 07, 2024 |
| Cisco Syst... | UCSC-C220-M3S 74-10442-0... | [2bc5f49245](https://linux-hardware.org/?probe=2bc5f49245) | Jan 07, 2024 |
| Apple         | Mac-F221BEC8                | [c172686fae](https://linux-hardware.org/?probe=c172686fae) | Jan 06, 2024 |
| Apple         | Mac-F221BEC8                | [a36307cb4c](https://linux-hardware.org/?probe=a36307cb4c) | Jan 06, 2024 |
| Unknown       | Unknown                     | [dd6b7a2d69](https://linux-hardware.org/?probe=dd6b7a2d69) | Jan 05, 2024 |
| ASRock        | J5040-ITX                   | [18b422e05b](https://linux-hardware.org/?probe=18b422e05b) | Jan 04, 2024 |
| MSI           | MPG X570 GAMING PRO CARB... | [d8329e0062](https://linux-hardware.org/?probe=d8329e0062) | Jan 04, 2024 |
| Gigabyte      | A320M-S2H V2-CF             | [f4db017a3f](https://linux-hardware.org/?probe=f4db017a3f) | Jan 03, 2024 |
| HP            | 2B34                        | [cecedd0691](https://linux-hardware.org/?probe=cecedd0691) | Jan 02, 2024 |
| Unknown       | X99H                        | [61c57cb006](https://linux-hardware.org/?probe=61c57cb006) | Jan 01, 2024 |
| ASUSTek       | M4N72-E                     | [7d21517ee3](https://linux-hardware.org/?probe=7d21517ee3) | Dec 31, 2023 |
| Gigabyte      | B450M DS3H-CF               | [08f5647277](https://linux-hardware.org/?probe=08f5647277) | Dec 31, 2023 |
| ASRock        | B75M-DGS                    | [3a2df88d60](https://linux-hardware.org/?probe=3a2df88d60) | Dec 31, 2023 |
| Huanan        | X58 V1.0                    | [d13c9b1573](https://linux-hardware.org/?probe=d13c9b1573) | Dec 31, 2023 |
| QIYIDA        | X99-H9 V2.0                 | [af479728a3](https://linux-hardware.org/?probe=af479728a3) | Dec 30, 2023 |
| Gigabyte      | H81M-S2H                    | [a3a0b274d0](https://linux-hardware.org/?probe=a3a0b274d0) | Dec 29, 2023 |
| MSI           | B450M PRO-VDH V2            | [7efa5db123](https://linux-hardware.org/?probe=7efa5db123) | Dec 29, 2023 |
| MSI           | MEG X570S ACE MAX           | [e0e92720cb](https://linux-hardware.org/?probe=e0e92720cb) | Dec 29, 2023 |
| HP            | 8719                        | [91c89a31b5](https://linux-hardware.org/?probe=91c89a31b5) | Dec 29, 2023 |
| Dell          | 0K216C                      | [203ef6afde](https://linux-hardware.org/?probe=203ef6afde) | Dec 28, 2023 |
| MSI           | Z170A GAMING PRO CARBON     | [dfdfad519d](https://linux-hardware.org/?probe=dfdfad519d) | Dec 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [37fe922c9d](https://linux-hardware.org/?probe=37fe922c9d) | Dec 28, 2023 |
| AZW           | EQ                          | [1300ad3a67](https://linux-hardware.org/?probe=1300ad3a67) | Dec 27, 2023 |
| Gigabyte      | B760M DS3H DDR4             | [10fa4fd32b](https://linux-hardware.org/?probe=10fa4fd32b) | Dec 27, 2023 |
| HP            | 3397                        | [d7bbeccfe9](https://linux-hardware.org/?probe=d7bbeccfe9) | Dec 27, 2023 |
| MSI           | MS-B1591                    | [8baf11e980](https://linux-hardware.org/?probe=8baf11e980) | Dec 27, 2023 |
| Intel         | X99-P4 V5.0                 | [875d756d73](https://linux-hardware.org/?probe=875d756d73) | Dec 26, 2023 |
| Gigabyte      | B560M DS3H V2               | [af65354320](https://linux-hardware.org/?probe=af65354320) | Dec 26, 2023 |
| Lenovo        | MAHOBAY NOK                 | [f85a8a3b68](https://linux-hardware.org/?probe=f85a8a3b68) | Dec 25, 2023 |
| HP            | 1497                        | [c17c12a021](https://linux-hardware.org/?probe=c17c12a021) | Dec 24, 2023 |
| HP            | 1497                        | [9d5244b557](https://linux-hardware.org/?probe=9d5244b557) | Dec 23, 2023 |
| ASRock        | X370 Taichi                 | [689d51f57e](https://linux-hardware.org/?probe=689d51f57e) | Dec 23, 2023 |
| Huanan        | X58 V1.0                    | [ac62468ad1](https://linux-hardware.org/?probe=ac62468ad1) | Dec 21, 2023 |
| Foxconn       | 2ADA                        | [735572694e](https://linux-hardware.org/?probe=735572694e) | Dec 21, 2023 |
| ASUSTek       | PRIME B250M-A               | [11628f388e](https://linux-hardware.org/?probe=11628f388e) | Dec 20, 2023 |
| ASUSTek       | V6-P5G31E                   | [83a8408a7e](https://linux-hardware.org/?probe=83a8408a7e) | Dec 20, 2023 |
| ASUSTek       | Pro B550M-C                 | [4e3b422400](https://linux-hardware.org/?probe=4e3b422400) | Dec 19, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | [619bbec719](https://linux-hardware.org/?probe=619bbec719) | Dec 19, 2023 |
| ASUSTek       | Pro B550M-C                 | [1cd7c1b629](https://linux-hardware.org/?probe=1cd7c1b629) | Dec 19, 2023 |
| ASUSTek       | H110M-D                     | [c26e0d3896](https://linux-hardware.org/?probe=c26e0d3896) | Dec 18, 2023 |
| ASUSTek       | TUF Gaming B660M-E D4       | [ff5da894f9](https://linux-hardware.org/?probe=ff5da894f9) | Dec 18, 2023 |
| Gigabyte      | H510M H V2                  | [3228539880](https://linux-hardware.org/?probe=3228539880) | Dec 18, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [def7de5871](https://linux-hardware.org/?probe=def7de5871) | Dec 17, 2023 |
| ASRock        | H310M-STX                   | [df11c23d7c](https://linux-hardware.org/?probe=df11c23d7c) | Dec 17, 2023 |
| ASUSTek       | PRIME B460M-A               | [28b95cc0b7](https://linux-hardware.org/?probe=28b95cc0b7) | Dec 16, 2023 |
| HP            | 3647h                       | [4feaf76045](https://linux-hardware.org/?probe=4feaf76045) | Dec 16, 2023 |
| AMI           | Intel                       | [9564eaaec0](https://linux-hardware.org/?probe=9564eaaec0) | Dec 16, 2023 |
| ASRock        | AB350M-HDV                  | [945274527c](https://linux-hardware.org/?probe=945274527c) | Dec 13, 2023 |
| ASUSTek       | PRIME B450M-A               | [5a65590bed](https://linux-hardware.org/?probe=5a65590bed) | Dec 13, 2023 |
| Intel         | MIR1 RVP7                   | [eade46459a](https://linux-hardware.org/?probe=eade46459a) | Dec 13, 2023 |
| ASUSTek       | M3A78                       | [d2c14973f1](https://linux-hardware.org/?probe=d2c14973f1) | Dec 10, 2023 |
| Gigabyte      | EP41-UD3L                   | [9b40e5889d](https://linux-hardware.org/?probe=9b40e5889d) | Dec 10, 2023 |
| MSI           | B560M PRO-VDH               | [4a2deac69b](https://linux-hardware.org/?probe=4a2deac69b) | Dec 10, 2023 |
| Packard Be... | MCP73PV                     | [9d707e64d4](https://linux-hardware.org/?probe=9d707e64d4) | Dec 10, 2023 |
| Gigabyte      | B450 AORUS ELITE V2         | [505f85e4d4](https://linux-hardware.org/?probe=505f85e4d4) | Dec 10, 2023 |
| MSI           | B450-A PRO MAX              | [c576c4fbae](https://linux-hardware.org/?probe=c576c4fbae) | Dec 09, 2023 |
| Unknown       | Unknown                     | [c652e80145](https://linux-hardware.org/?probe=c652e80145) | Dec 08, 2023 |
| Gigabyte      | GA-MA770-DS3                | [66917779ad](https://linux-hardware.org/?probe=66917779ad) | Dec 07, 2023 |
| AMI           | Intel                       | [d2e7be0ff3](https://linux-hardware.org/?probe=d2e7be0ff3) | Dec 07, 2023 |
| ASUSTek       | Pro B560M-C                 | [116dce4b93](https://linux-hardware.org/?probe=116dce4b93) | Dec 07, 2023 |
| MSI           | Z490-A PRO                  | [8d3648a498](https://linux-hardware.org/?probe=8d3648a498) | Dec 07, 2023 |
| ASRock        | A320M-HDV R4.0              | [ca5df22812](https://linux-hardware.org/?probe=ca5df22812) | Dec 06, 2023 |
| MSI           | Z490-A PRO                  | [443436c7ab](https://linux-hardware.org/?probe=443436c7ab) | Dec 05, 2023 |
| MSI           | H510I PRO WIFI              | [b0e2df98b4](https://linux-hardware.org/?probe=b0e2df98b4) | Dec 05, 2023 |
| Gigabyte      | B550M DS3H                  | [ddb2183d6c](https://linux-hardware.org/?probe=ddb2183d6c) | Dec 05, 2023 |
| ASUSTek       | P8Z68-V PRO                 | [fde3c9253f](https://linux-hardware.org/?probe=fde3c9253f) | Dec 04, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | [c492be4899](https://linux-hardware.org/?probe=c492be4899) | Dec 04, 2023 |
| HP            | 2B46                        | [5bfce44b96](https://linux-hardware.org/?probe=5bfce44b96) | Dec 03, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [fb15da06c7](https://linux-hardware.org/?probe=fb15da06c7) | Dec 03, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [ece8f86f29](https://linux-hardware.org/?probe=ece8f86f29) | Dec 02, 2023 |
| Acer          | IPXHW-RL                    | [aa0f30e67f](https://linux-hardware.org/?probe=aa0f30e67f) | Dec 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [16215b0c85](https://linux-hardware.org/?probe=16215b0c85) | Dec 02, 2023 |
| HP            | 8459                        | [b7a22ecb3f](https://linux-hardware.org/?probe=b7a22ecb3f) | Dec 01, 2023 |
| Intel         | H61 V1.5                    | [45487af3d7](https://linux-hardware.org/?probe=45487af3d7) | Dec 01, 2023 |
| Acer          | Extensa M2610 V:1.0         | [e4c1bd6f51](https://linux-hardware.org/?probe=e4c1bd6f51) | Nov 30, 2023 |
| ASUSTek       | P5N-MX                      | [c586157333](https://linux-hardware.org/?probe=c586157333) | Nov 30, 2023 |
| Gigabyte      | GA-73PVM-S2H                | [0d85f5e172](https://linux-hardware.org/?probe=0d85f5e172) | Nov 30, 2023 |
| HP            | 304Ah                       | [03437e0238](https://linux-hardware.org/?probe=03437e0238) | Nov 29, 2023 |
| HP            | 8298                        | [f66cb29dd1](https://linux-hardware.org/?probe=f66cb29dd1) | Nov 29, 2023 |
| MSI           | Z170A PC MATE               | [913553eac4](https://linux-hardware.org/?probe=913553eac4) | Nov 29, 2023 |
| MSI           | MS-B1591                    | [1f97b0b293](https://linux-hardware.org/?probe=1f97b0b293) | Nov 28, 2023 |
| HP            | 18E5                        | [a9c04bd2c7](https://linux-hardware.org/?probe=a9c04bd2c7) | Nov 28, 2023 |
| MSI           | MS-B1591                    | [d5ff2835f3](https://linux-hardware.org/?probe=d5ff2835f3) | Nov 28, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [e5509bd1ba](https://linux-hardware.org/?probe=e5509bd1ba) | Nov 28, 2023 |
| Lenovo        | 30BC SDK0J40705 WIN 3425... | [d16f76117d](https://linux-hardware.org/?probe=d16f76117d) | Nov 28, 2023 |
| Gigabyte      | Z590I VISION D              | [cb4704c5ba](https://linux-hardware.org/?probe=cb4704c5ba) | Nov 27, 2023 |
| ASUSTek       | H81M-K                      | [121db7e081](https://linux-hardware.org/?probe=121db7e081) | Nov 27, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | [d3e69f25a6](https://linux-hardware.org/?probe=d3e69f25a6) | Nov 26, 2023 |
| HP            | 339A                        | [5cad333081](https://linux-hardware.org/?probe=5cad333081) | Nov 26, 2023 |
| MSI           | B650 GAMING PLUS WIFI       | [c25e140976](https://linux-hardware.org/?probe=c25e140976) | Nov 26, 2023 |
| Gigabyte      | X58A-UD3R                   | [91001125ab](https://linux-hardware.org/?probe=91001125ab) | Nov 25, 2023 |
| Gigabyte      | X58A-UD3R                   | [c22007e726](https://linux-hardware.org/?probe=c22007e726) | Nov 25, 2023 |
| ASUSTek       | ROG STRIX B460-I GAMING     | [7a0adaf9f3](https://linux-hardware.org/?probe=7a0adaf9f3) | Nov 25, 2023 |
| ASUSTek       | ROG STRIX B460-I GAMING     | [b96e460a4f](https://linux-hardware.org/?probe=b96e460a4f) | Nov 25, 2023 |
| ASUSTek       | P8H77-M LE                  | [39919b75ba](https://linux-hardware.org/?probe=39919b75ba) | Nov 24, 2023 |
| ASUSTek       | M3A78                       | [c4895d59da](https://linux-hardware.org/?probe=c4895d59da) | Nov 23, 2023 |
| AZW           | SEi V1.0                    | [d18296a25c](https://linux-hardware.org/?probe=d18296a25c) | Nov 23, 2023 |
| Gigabyte      | MZBAYAP-00                  | [101c96a0c0](https://linux-hardware.org/?probe=101c96a0c0) | Nov 22, 2023 |
| Gigabyte      | MZBAYAP-00                  | [f990b64367](https://linux-hardware.org/?probe=f990b64367) | Nov 22, 2023 |
| ASRock        | J4105-ITX                   | [d5a155c906](https://linux-hardware.org/?probe=d5a155c906) | Nov 22, 2023 |
| ASUSTek       | PRIME X570-PRO              | [936b04414c](https://linux-hardware.org/?probe=936b04414c) | Nov 21, 2023 |
| Dell          | 062TCH A00                  | [6df960f264](https://linux-hardware.org/?probe=6df960f264) | Nov 21, 2023 |
| Shenzhen M... | F7BFC                       | [bd7cd76d26](https://linux-hardware.org/?probe=bd7cd76d26) | Nov 20, 2023 |
| HP            | ProLiant MicroServer Gen... | [885444b8af](https://linux-hardware.org/?probe=885444b8af) | Nov 20, 2023 |
| Dell          | 062TCH A00                  | [895c93e639](https://linux-hardware.org/?probe=895c93e639) | Nov 20, 2023 |
| ASRock        | H81M-ITX/WiFi               | [e4b1bf4519](https://linux-hardware.org/?probe=e4b1bf4519) | Nov 20, 2023 |
| ASUSTek       | M3A78                       | [a6392d3aae](https://linux-hardware.org/?probe=a6392d3aae) | Nov 19, 2023 |
| ASRock        | B550M-ITX/ac                | [c9b5f09ea5](https://linux-hardware.org/?probe=c9b5f09ea5) | Nov 19, 2023 |
| ASRock        | B550M-ITX/ac                | [c76562a6ce](https://linux-hardware.org/?probe=c76562a6ce) | Nov 19, 2023 |
| Lenovo        | 314F SDK0J40697 WIN 3305... | [a4523c2cf4](https://linux-hardware.org/?probe=a4523c2cf4) | Nov 19, 2023 |
| HP            | 0A54h                       | [7b3cd2dc7a](https://linux-hardware.org/?probe=7b3cd2dc7a) | Nov 19, 2023 |
| Acer          | Extensa M2610 V:1.0         | [7b70ac1965](https://linux-hardware.org/?probe=7b70ac1965) | Nov 19, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [beae506a63](https://linux-hardware.org/?probe=beae506a63) | Nov 18, 2023 |
| Acer          | Aspire TC-780               | [76cc38fcb0](https://linux-hardware.org/?probe=76cc38fcb0) | Nov 17, 2023 |
| Intel         | D34010WYK H14771-304        | [b3c1feb070](https://linux-hardware.org/?probe=b3c1feb070) | Nov 17, 2023 |
| AMI           | Intel                       | [36c0765b5c](https://linux-hardware.org/?probe=36c0765b5c) | Nov 17, 2023 |
| Apple         | Mac-F221BEC8                | [23bd3ec971](https://linux-hardware.org/?probe=23bd3ec971) | Nov 16, 2023 |
| Dell          | 062TCH A00                  | [5e674f81ca](https://linux-hardware.org/?probe=5e674f81ca) | Nov 15, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | [2e59ea85e9](https://linux-hardware.org/?probe=2e59ea85e9) | Nov 15, 2023 |
| Shenzhen M... | F7BSC                       | [23cc4e28d3](https://linux-hardware.org/?probe=23cc4e28d3) | Nov 13, 2023 |
| Unknown       | T3 MRD                      | [ae1a1c1e9b](https://linux-hardware.org/?probe=ae1a1c1e9b) | Nov 13, 2023 |
| Shenzhen M... | F7BFC                       | [b375ae991a](https://linux-hardware.org/?probe=b375ae991a) | Nov 12, 2023 |
| MSI           | Z490-A PRO                  | [1291055857](https://linux-hardware.org/?probe=1291055857) | Nov 12, 2023 |
| Apple         | Mac-F221BEC8                | [e89b871c81](https://linux-hardware.org/?probe=e89b871c81) | Nov 12, 2023 |
| ASUSTek       | Z170-A                      | [332413e83b](https://linux-hardware.org/?probe=332413e83b) | Nov 11, 2023 |
| Gigabyte      | H61M-DS2                    | [26a111bc63](https://linux-hardware.org/?probe=26a111bc63) | Nov 11, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [ca677ba9c3](https://linux-hardware.org/?probe=ca677ba9c3) | Nov 10, 2023 |
| ASUSTek       | H110M-D                     | [6e0b13392e](https://linux-hardware.org/?probe=6e0b13392e) | Nov 10, 2023 |
| ASUSTek       | H110M-D                     | [d4e6049883](https://linux-hardware.org/?probe=d4e6049883) | Nov 10, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [2adf99d3df](https://linux-hardware.org/?probe=2adf99d3df) | Nov 09, 2023 |
| MSI           | Z170-A PRO                  | [2bdf6b2a2f](https://linux-hardware.org/?probe=2bdf6b2a2f) | Nov 09, 2023 |
| MSI           | B360M PRO-VDH               | [536865249c](https://linux-hardware.org/?probe=536865249c) | Nov 08, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [7ecc25dda7](https://linux-hardware.org/?probe=7ecc25dda7) | Nov 08, 2023 |
| Gigabyte      | Z690 UD DDR4                | [ef9e91fdbf](https://linux-hardware.org/?probe=ef9e91fdbf) | Nov 08, 2023 |
| Gigabyte      | H61M-DS2                    | [5a6cfb8bce](https://linux-hardware.org/?probe=5a6cfb8bce) | Nov 07, 2023 |
| Dell          | 062TCH A00                  | [ac7ca2b01b](https://linux-hardware.org/?probe=ac7ca2b01b) | Nov 07, 2023 |
| ASUSTek       | H81M-K                      | [3de6cf8221](https://linux-hardware.org/?probe=3de6cf8221) | Nov 07, 2023 |
| AZW           | EQ                          | [50c0310d2e](https://linux-hardware.org/?probe=50c0310d2e) | Nov 06, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [980eb7c13d](https://linux-hardware.org/?probe=980eb7c13d) | Nov 06, 2023 |
| AZW           | EQ                          | [161d2abf24](https://linux-hardware.org/?probe=161d2abf24) | Nov 06, 2023 |
| MSI           | H55M-E33                    | [09ba697574](https://linux-hardware.org/?probe=09ba697574) | Nov 06, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [9e50325ddd](https://linux-hardware.org/?probe=9e50325ddd) | Nov 06, 2023 |
| Gigabyte      | B450M S2H                   | [b40c43c829](https://linux-hardware.org/?probe=b40c43c829) | Nov 05, 2023 |
| Gigabyte      | B450M S2H                   | [67a1ec0ae8](https://linux-hardware.org/?probe=67a1ec0ae8) | Nov 05, 2023 |
| MSI           | MEG Z590 UNIFY              | [1f84fe45f8](https://linux-hardware.org/?probe=1f84fe45f8) | Nov 05, 2023 |
| MSI           | B560M PRO-VDH               | [82bf4f530a](https://linux-hardware.org/?probe=82bf4f530a) | Nov 05, 2023 |
| Shuttle       | FH87                        | [1488ef29c3](https://linux-hardware.org/?probe=1488ef29c3) | Nov 05, 2023 |
| Dell          | 062TCH A00                  | [b82fbd03d5](https://linux-hardware.org/?probe=b82fbd03d5) | Nov 05, 2023 |
| Gigabyte      | B450M DS3H-CF               | [fefb7e12d2](https://linux-hardware.org/?probe=fefb7e12d2) | Nov 05, 2023 |
| MSI           | B560M PRO-VDH               | [04e96e2742](https://linux-hardware.org/?probe=04e96e2742) | Nov 04, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [dade20f823](https://linux-hardware.org/?probe=dade20f823) | Nov 04, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [20ffbbc165](https://linux-hardware.org/?probe=20ffbbc165) | Nov 04, 2023 |
| Dell          | 062TCH A00                  | [b964b2c6be](https://linux-hardware.org/?probe=b964b2c6be) | Nov 04, 2023 |
| ASUSTek       | H110M-D                     | [03303fa6ed](https://linux-hardware.org/?probe=03303fa6ed) | Nov 04, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [89a9c53f3a](https://linux-hardware.org/?probe=89a9c53f3a) | Nov 02, 2023 |
| ASUSTek       | P5G41T-M LX                 | [ae6c835796](https://linux-hardware.org/?probe=ae6c835796) | Nov 02, 2023 |
| Intel         | X99                         | [b740510fc0](https://linux-hardware.org/?probe=b740510fc0) | Nov 02, 2023 |
| MSI           | Z170A GAMING M7             | [9ba4f50201](https://linux-hardware.org/?probe=9ba4f50201) | Nov 02, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [993d985e9e](https://linux-hardware.org/?probe=993d985e9e) | Nov 01, 2023 |
| MSI           | Z170A GAMING M7             | [a613aa5a0f](https://linux-hardware.org/?probe=a613aa5a0f) | Nov 01, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [bb9a00e5b5](https://linux-hardware.org/?probe=bb9a00e5b5) | Nov 01, 2023 |
| MSI           | H110M ECO                   | [d2f60e8bc9](https://linux-hardware.org/?probe=d2f60e8bc9) | Nov 01, 2023 |
| HP            | 8054                        | [b667e30b0e](https://linux-hardware.org/?probe=b667e30b0e) | Nov 01, 2023 |
| Gigabyte      | GA-MA770-DS3                | [968cf90d9a](https://linux-hardware.org/?probe=968cf90d9a) | Nov 01, 2023 |
| Gigabyte      | P67A-D3-B3                  | [0c51ffc039](https://linux-hardware.org/?probe=0c51ffc039) | Nov 01, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [7b6fe38982](https://linux-hardware.org/?probe=7b6fe38982) | Oct 31, 2023 |
| ASUSTek       | B85M-G                      | [e4b4cf1229](https://linux-hardware.org/?probe=e4b4cf1229) | Oct 30, 2023 |
| MSI           | B550-A PRO                  | [d03daf3967](https://linux-hardware.org/?probe=d03daf3967) | Oct 30, 2023 |
| HP            | 8436                        | [4fe5c2e03c](https://linux-hardware.org/?probe=4fe5c2e03c) | Oct 30, 2023 |
| Gigabyte      | H81M-HD3                    | [1be6955dfc](https://linux-hardware.org/?probe=1be6955dfc) | Oct 30, 2023 |
| ASUSTek       | P5G41T-M LX                 | [e741e073e0](https://linux-hardware.org/?probe=e741e073e0) | Oct 30, 2023 |
| Apple         | Mac-F221BEC8                | [4db0be5324](https://linux-hardware.org/?probe=4db0be5324) | Oct 29, 2023 |
| Koloe         | X58                         | [91fbabe04c](https://linux-hardware.org/?probe=91fbabe04c) | Oct 29, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [dee4ef8a3b](https://linux-hardware.org/?probe=dee4ef8a3b) | Oct 29, 2023 |
| HP            | 18E4                        | [b192ce4f35](https://linux-hardware.org/?probe=b192ce4f35) | Oct 28, 2023 |
| MSI           | H110M PRO-D                 | [96710ad70e](https://linux-hardware.org/?probe=96710ad70e) | Oct 28, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [9207de9b44](https://linux-hardware.org/?probe=9207de9b44) | Oct 25, 2023 |
| Foxconn       | 2ABF                        | [50abb592dd](https://linux-hardware.org/?probe=50abb592dd) | Oct 25, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [61ec26bc75](https://linux-hardware.org/?probe=61ec26bc75) | Oct 24, 2023 |
| Gigabyte      | B85M-D3V Plus               | [845b1f10ef](https://linux-hardware.org/?probe=845b1f10ef) | Oct 24, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [918cd67301](https://linux-hardware.org/?probe=918cd67301) | Oct 22, 2023 |
| Gigabyte      | GA-MA790XT-UD4P             | [ad17620d9f](https://linux-hardware.org/?probe=ad17620d9f) | Oct 21, 2023 |
| Gigabyte      | Z390 UD                     | [edf8acb455](https://linux-hardware.org/?probe=edf8acb455) | Oct 21, 2023 |
| ASRock        | N68C-S UCC                  | [6468bd6335](https://linux-hardware.org/?probe=6468bd6335) | Oct 21, 2023 |
| Gigabyte      | GA-MA790XT-UD4P             | [9286fa6477](https://linux-hardware.org/?probe=9286fa6477) | Oct 21, 2023 |
| ASUSTek       | PRIME B250M-A               | [ff0d8bbab4](https://linux-hardware.org/?probe=ff0d8bbab4) | Oct 21, 2023 |
| Packard Be... | IMEDIA S3840                | [3cc1398528](https://linux-hardware.org/?probe=3cc1398528) | Oct 21, 2023 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [2d07542448](https://linux-hardware.org/?probe=2d07542448) | Oct 20, 2023 |
| MSI           | B450-A PRO MAX              | [e02418f8c1](https://linux-hardware.org/?probe=e02418f8c1) | Oct 20, 2023 |
| MSI           | B450-A PRO MAX              | [17b8a78644](https://linux-hardware.org/?probe=17b8a78644) | Oct 20, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [0fa5f53ce0](https://linux-hardware.org/?probe=0fa5f53ce0) | Oct 19, 2023 |
| ASUSTek       | M4A78LT-M                   | [cc8d1f7fb2](https://linux-hardware.org/?probe=cc8d1f7fb2) | Oct 19, 2023 |
| ASRock        | H110M-HDV R3.0              | [491538303f](https://linux-hardware.org/?probe=491538303f) | Oct 19, 2023 |
| HP            | 2B52                        | [b14a00a196](https://linux-hardware.org/?probe=b14a00a196) | Oct 18, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [2530967a90](https://linux-hardware.org/?probe=2530967a90) | Oct 17, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [200b756e67](https://linux-hardware.org/?probe=200b756e67) | Oct 17, 2023 |
| ASUSTek       | X500MA                      | [2ffe0522e1](https://linux-hardware.org/?probe=2ffe0522e1) | Oct 17, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d519c10989](https://linux-hardware.org/?probe=d519c10989) | Oct 16, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [374a5bf116](https://linux-hardware.org/?probe=374a5bf116) | Oct 15, 2023 |
| MSI           | MAG B550 TORPEDO            | [2bb3baf0f6](https://linux-hardware.org/?probe=2bb3baf0f6) | Oct 14, 2023 |
| Intel         | JSL MRD                     | [a39b6e2f92](https://linux-hardware.org/?probe=a39b6e2f92) | Oct 14, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [5ee0d65118](https://linux-hardware.org/?probe=5ee0d65118) | Oct 13, 2023 |
| HP            | 1998                        | [e8d3c2b8ef](https://linux-hardware.org/?probe=e8d3c2b8ef) | Oct 12, 2023 |
| Dell          | 00V62H A01                  | [4957e141ac](https://linux-hardware.org/?probe=4957e141ac) | Oct 12, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [0cbd266486](https://linux-hardware.org/?probe=0cbd266486) | Oct 11, 2023 |
| Dell          | 09CKT0 A03                  | [27c33c2ec5](https://linux-hardware.org/?probe=27c33c2ec5) | Oct 11, 2023 |
| ASRock        | X79 Extreme9                | [4a0805a07a](https://linux-hardware.org/?probe=4a0805a07a) | Oct 11, 2023 |
| Intel         | X99                         | [c025563ec2](https://linux-hardware.org/?probe=c025563ec2) | Oct 10, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [68372adfc5](https://linux-hardware.org/?probe=68372adfc5) | Oct 10, 2023 |
| AZW           | Green G5                    | [cb5efe1873](https://linux-hardware.org/?probe=cb5efe1873) | Oct 10, 2023 |
| HP            | 8054                        | [66ad5550d1](https://linux-hardware.org/?probe=66ad5550d1) | Oct 10, 2023 |
| MSI           | MS-7125                     | [2e6837be6d](https://linux-hardware.org/?probe=2e6837be6d) | Oct 10, 2023 |
| HP            | 89B5 A                      | [746fef0fc7](https://linux-hardware.org/?probe=746fef0fc7) | Oct 10, 2023 |
| MSI           | B450M BAZOOKA V2            | [3b598550c2](https://linux-hardware.org/?probe=3b598550c2) | Oct 10, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [333535db5f](https://linux-hardware.org/?probe=333535db5f) | Oct 10, 2023 |
| Gigabyte      | H310M S2H x.x               | [fd3c1d1196](https://linux-hardware.org/?probe=fd3c1d1196) | Oct 08, 2023 |
| Lenovo        | 370A SDK0J40709 WIN 3259... | [38c0c97684](https://linux-hardware.org/?probe=38c0c97684) | Oct 07, 2023 |
| Pegatron      | EVANS                       | [f798f24c90](https://linux-hardware.org/?probe=f798f24c90) | Oct 07, 2023 |
| Packard Be... | MCP73PV                     | [dc24306f2f](https://linux-hardware.org/?probe=dc24306f2f) | Oct 05, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [377e8e1994](https://linux-hardware.org/?probe=377e8e1994) | Oct 05, 2023 |
| ASUSTek       | A88XM-E                     | [cef182f4e0](https://linux-hardware.org/?probe=cef182f4e0) | Oct 04, 2023 |
| Gigabyte      | B550M DS3H                  | [6c95b1e3b2](https://linux-hardware.org/?probe=6c95b1e3b2) | Oct 04, 2023 |
| Packard Be... | MCP73PV                     | [2ecd860fef](https://linux-hardware.org/?probe=2ecd860fef) | Oct 03, 2023 |
| ASUSTek       | PRIME H510M-D               | [e583e35b95](https://linux-hardware.org/?probe=e583e35b95) | Oct 03, 2023 |
| ASUSTek       | PRIME H510M-D               | [538889d79f](https://linux-hardware.org/?probe=538889d79f) | Oct 03, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c77065abde](https://linux-hardware.org/?probe=c77065abde) | Oct 03, 2023 |
| Pegatron      | EVANS                       | [3f2a4fe53e](https://linux-hardware.org/?probe=3f2a4fe53e) | Oct 03, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [8fd9631bea](https://linux-hardware.org/?probe=8fd9631bea) | Oct 03, 2023 |
| ASUSTek       | P8H77-M PRO                 | [bc03d7f758](https://linux-hardware.org/?probe=bc03d7f758) | Oct 02, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [76c5466daa](https://linux-hardware.org/?probe=76c5466daa) | Oct 02, 2023 |
| HP            | 3397                        | [fac50277cc](https://linux-hardware.org/?probe=fac50277cc) | Oct 01, 2023 |
| ASUSTek       | PRIME B365M-A               | [279922964e](https://linux-hardware.org/?probe=279922964e) | Oct 01, 2023 |
| Dell          | 0Y56T3 A01                  | [bfc1d1dd13](https://linux-hardware.org/?probe=bfc1d1dd13) | Sep 30, 2023 |
| ASUSTek       | PRIME B450M-A               | [3c9f4d4aef](https://linux-hardware.org/?probe=3c9f4d4aef) | Sep 29, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [41f0f8666c](https://linux-hardware.org/?probe=41f0f8666c) | Sep 27, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [14cbad7097](https://linux-hardware.org/?probe=14cbad7097) | Sep 26, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [1e61c0fb6b](https://linux-hardware.org/?probe=1e61c0fb6b) | Sep 26, 2023 |
| ASUSTek       | TUF B360-PRO GAMING WIFI    | [16c22d9ead](https://linux-hardware.org/?probe=16c22d9ead) | Sep 25, 2023 |
| BESSTAR Te... | HM90                        | [a85d516a80](https://linux-hardware.org/?probe=a85d516a80) | Sep 25, 2023 |
| Gigabyte      | X99-UD4-CF                  | [c50564e3bb](https://linux-hardware.org/?probe=c50564e3bb) | Sep 25, 2023 |
| ASRock        | 970 Extreme4                | [4b78e93dff](https://linux-hardware.org/?probe=4b78e93dff) | Sep 25, 2023 |
| ASRock        | 970 Extreme4                | [e05aa71be7](https://linux-hardware.org/?probe=e05aa71be7) | Sep 25, 2023 |
| Biostar       | A68N-2100K                  | [38a92e23c8](https://linux-hardware.org/?probe=38a92e23c8) | Sep 24, 2023 |
| Dell          | 0T10XW A02                  | [5df1a942d9](https://linux-hardware.org/?probe=5df1a942d9) | Sep 24, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [54ed40361d](https://linux-hardware.org/?probe=54ed40361d) | Sep 23, 2023 |
| ASUSTek       | H81M-K                      | [30a324bad7](https://linux-hardware.org/?probe=30a324bad7) | Sep 23, 2023 |
| Gigabyte      | H61M-S2PV                   | [fd5d5651ce](https://linux-hardware.org/?probe=fd5d5651ce) | Sep 22, 2023 |
| HP            | 18E7                        | [ba0cb8996d](https://linux-hardware.org/?probe=ba0cb8996d) | Sep 21, 2023 |
| HP            | 1495                        | [ad97ea883d](https://linux-hardware.org/?probe=ad97ea883d) | Sep 21, 2023 |
| ASUSTek       | PRIME X670E-PRO WIFI        | [f87766b547](https://linux-hardware.org/?probe=f87766b547) | Sep 21, 2023 |
| ASUSTek       | B150M-A                     | [d2e741051e](https://linux-hardware.org/?probe=d2e741051e) | Sep 21, 2023 |
| ASUSTek       | H81M-K                      | [03c9da6c46](https://linux-hardware.org/?probe=03c9da6c46) | Sep 20, 2023 |
| MSI           | Indio                       | [330a2c9640](https://linux-hardware.org/?probe=330a2c9640) | Sep 20, 2023 |
| Intel         | DG31PR AAD97573-205         | [a25329cfdb](https://linux-hardware.org/?probe=a25329cfdb) | Sep 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | [8b6f78da91](https://linux-hardware.org/?probe=8b6f78da91) | Sep 20, 2023 |
| ASUSTek       | PRIME Z590-A                | [a2f44141ba](https://linux-hardware.org/?probe=a2f44141ba) | Sep 20, 2023 |
| ASUSTek       | P5K-E                       | [233a59e640](https://linux-hardware.org/?probe=233a59e640) | Sep 18, 2023 |
| Biostar       | A68N-2100K                  | [56340d8ed4](https://linux-hardware.org/?probe=56340d8ed4) | Sep 18, 2023 |
| ASUSTek       | A88XM-PLUS                  | [ab79a26993](https://linux-hardware.org/?probe=ab79a26993) | Sep 18, 2023 |
| ASUSTek       | B85M-G                      | [1398fa87b2](https://linux-hardware.org/?probe=1398fa87b2) | Sep 17, 2023 |
| ASRock        | 960GC-GS FX                 | [513b6982f2](https://linux-hardware.org/?probe=513b6982f2) | Sep 16, 2023 |
| ASUSTek       | P5G41T-M LX                 | [020deea6d9](https://linux-hardware.org/?probe=020deea6d9) | Sep 15, 2023 |
| MSI           | MPG Z590 GAMING PLUS        | [cfa86cec4f](https://linux-hardware.org/?probe=cfa86cec4f) | Sep 15, 2023 |
| Gigabyte      | 970A-DS3P                   | [fa347b6b46](https://linux-hardware.org/?probe=fa347b6b46) | Sep 15, 2023 |
| Gigabyte      | B450M DS3H-CF               | [f48f6375b2](https://linux-hardware.org/?probe=f48f6375b2) | Sep 15, 2023 |
| ASUSTek       | M2N-E SLI                   | [21e27c3e56](https://linux-hardware.org/?probe=21e27c3e56) | Sep 14, 2023 |
| Gigabyte      | B365M H                     | [b57846d1cb](https://linux-hardware.org/?probe=b57846d1cb) | Sep 12, 2023 |
| Gigabyte      | B450M S2H                   | [9099ebc0a7](https://linux-hardware.org/?probe=9099ebc0a7) | Sep 12, 2023 |
| Intel         | DG31PR AAD97573-205         | [486d89ed3a](https://linux-hardware.org/?probe=486d89ed3a) | Sep 11, 2023 |
| MSI           | MPG Z490 GAMING PLUS        | [f5b3cd74bc](https://linux-hardware.org/?probe=f5b3cd74bc) | Sep 11, 2023 |
| MSI           | B450M BAZOOKA V2            | [a98de00f8f](https://linux-hardware.org/?probe=a98de00f8f) | Sep 11, 2023 |
| BESSTAR Te... | HX90                        | [f8c66085b0](https://linux-hardware.org/?probe=f8c66085b0) | Sep 08, 2023 |
| SLIMBOOK      | ONE-AM5                     | [0c8c554ff5](https://linux-hardware.org/?probe=0c8c554ff5) | Sep 08, 2023 |
| HP            | 0B4Ch D                     | [1a2a0eef04](https://linux-hardware.org/?probe=1a2a0eef04) | Sep 06, 2023 |
| HP            | 0B4Ch D                     | [e6c990ad64](https://linux-hardware.org/?probe=e6c990ad64) | Sep 06, 2023 |
| MSI           | PRO B650-P WIFI             | [507d1bd39c](https://linux-hardware.org/?probe=507d1bd39c) | Sep 06, 2023 |
| MSI           | Boston                      | [f4749c6ef7](https://linux-hardware.org/?probe=f4749c6ef7) | Sep 06, 2023 |
| Gigabyte      | X99-UD4-CF                  | [ee70bf217a](https://linux-hardware.org/?probe=ee70bf217a) | Sep 06, 2023 |
| Gigabyte      | H310M S2H x.x               | [7c39e7227e](https://linux-hardware.org/?probe=7c39e7227e) | Sep 04, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [c4acf7ebb9](https://linux-hardware.org/?probe=c4acf7ebb9) | Sep 02, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [1ae5cc8cf9](https://linux-hardware.org/?probe=1ae5cc8cf9) | Sep 02, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [c03e79d6e1](https://linux-hardware.org/?probe=c03e79d6e1) | Sep 02, 2023 |
| Intel         | SHARKBAY                    | [cc7fea9c3a](https://linux-hardware.org/?probe=cc7fea9c3a) | Sep 01, 2023 |
| ASUSTek       | H110M-D                     | [b0127b4bff](https://linux-hardware.org/?probe=b0127b4bff) | Sep 01, 2023 |
| Lenovo        | NOK                         | [3b2d750004](https://linux-hardware.org/?probe=3b2d750004) | Aug 31, 2023 |
| Lenovo        | NOK                         | [0e10fff36a](https://linux-hardware.org/?probe=0e10fff36a) | Aug 31, 2023 |
| HP            | 339A                        | [1ac5cd4af8](https://linux-hardware.org/?probe=1ac5cd4af8) | Aug 31, 2023 |
| Intel         | HM570                       | [d7c97890f9](https://linux-hardware.org/?probe=d7c97890f9) | Aug 31, 2023 |
| Gigabyte      | MTGU5AB-00                  | [2501ea0755](https://linux-hardware.org/?probe=2501ea0755) | Aug 31, 2023 |
| MSI           | MS-B1421                    | [65d24e365e](https://linux-hardware.org/?probe=65d24e365e) | Aug 31, 2023 |
| MSI           | A520M-A PRO                 | [d672293a11](https://linux-hardware.org/?probe=d672293a11) | Aug 31, 2023 |
| HP            | 8768 A                      | [3b19eaee36](https://linux-hardware.org/?probe=3b19eaee36) | Aug 31, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [17e971c3fb](https://linux-hardware.org/?probe=17e971c3fb) | Aug 31, 2023 |
| HP            | 876C SMVB                   | [25176eb482](https://linux-hardware.org/?probe=25176eb482) | Aug 30, 2023 |
| Gigabyte      | H61M-DS2                    | [0817c6178e](https://linux-hardware.org/?probe=0817c6178e) | Aug 29, 2023 |
| Gigabyte      | H61M-DS2                    | [0a2adee694](https://linux-hardware.org/?probe=0a2adee694) | Aug 29, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | [5b896ea45c](https://linux-hardware.org/?probe=5b896ea45c) | Aug 29, 2023 |
| Huanan        | H97-ZD3 V2.1                | [0587a85214](https://linux-hardware.org/?probe=0587a85214) | Aug 28, 2023 |
| MSI           | Z170A GAMING M3             | [cdbff2ba81](https://linux-hardware.org/?probe=cdbff2ba81) | Aug 28, 2023 |
| Gigabyte      | EX58-UD5                    | [8c1bc17ecf](https://linux-hardware.org/?probe=8c1bc17ecf) | Aug 28, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [b70096c6f9](https://linux-hardware.org/?probe=b70096c6f9) | Aug 28, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [01a0f80107](https://linux-hardware.org/?probe=01a0f80107) | Aug 27, 2023 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [d03d50ea3c](https://linux-hardware.org/?probe=d03d50ea3c) | Aug 27, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [7a67556942](https://linux-hardware.org/?probe=7a67556942) | Aug 27, 2023 |
| MSI           | MAG B550 TORPEDO            | [01062889f6](https://linux-hardware.org/?probe=01062889f6) | Aug 26, 2023 |
| HP            | 18E4                        | [e209d700ef](https://linux-hardware.org/?probe=e209d700ef) | Aug 25, 2023 |
| Packard Be... | GA-T671MG                   | [ba401056e8](https://linux-hardware.org/?probe=ba401056e8) | Aug 24, 2023 |
| Packard Be... | GA-T671MG                   | [d51fb378a1](https://linux-hardware.org/?probe=d51fb378a1) | Aug 24, 2023 |
| ASUSTek       | B85M-G                      | [5f108773ec](https://linux-hardware.org/?probe=5f108773ec) | Aug 24, 2023 |
| Acer          | Aspire TC-605               | [03cff37b1a](https://linux-hardware.org/?probe=03cff37b1a) | Aug 24, 2023 |
| HP            | 8835                        | [6d48f6a632](https://linux-hardware.org/?probe=6d48f6a632) | Aug 23, 2023 |
| HP            | 8835                        | [01d495ff7c](https://linux-hardware.org/?probe=01d495ff7c) | Aug 23, 2023 |
| GEEKOM        | GM08i3T                     | [36ea06968d](https://linux-hardware.org/?probe=36ea06968d) | Aug 23, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [e9c7a12d52](https://linux-hardware.org/?probe=e9c7a12d52) | Aug 21, 2023 |
| Medion        | MS-7728                     | [f548540f0c](https://linux-hardware.org/?probe=f548540f0c) | Aug 19, 2023 |
| ASUSTek       | PRIME H410M-R               | [809590bdb0](https://linux-hardware.org/?probe=809590bdb0) | Aug 17, 2023 |
| Dell          | 0M6C7G A00                  | [50731e7c54](https://linux-hardware.org/?probe=50731e7c54) | Aug 16, 2023 |
| Unknown       | Unknown                     | [d2b1d6e9ad](https://linux-hardware.org/?probe=d2b1d6e9ad) | Aug 16, 2023 |
| ASUSTek       | Pro B550M-C                 | [712bd65558](https://linux-hardware.org/?probe=712bd65558) | Aug 16, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [4907b10657](https://linux-hardware.org/?probe=4907b10657) | Aug 15, 2023 |
| Gigabyte      | B550M DS3H                  | [e2a4a35103](https://linux-hardware.org/?probe=e2a4a35103) | Aug 15, 2023 |
| Gigabyte      | X299 AORUS Ultra Gaming ... | [5a3c9080d8](https://linux-hardware.org/?probe=5a3c9080d8) | Aug 14, 2023 |
| Gigabyte      | GA-MA770T-UD3               | [4dc7a0831b](https://linux-hardware.org/?probe=4dc7a0831b) | Aug 14, 2023 |
| MSI           | A78M-E45                    | [2affb76a98](https://linux-hardware.org/?probe=2affb76a98) | Aug 13, 2023 |
| MSI           | 2AE0                        | [b8a2a0eb5c](https://linux-hardware.org/?probe=b8a2a0eb5c) | Aug 12, 2023 |
| MSI           | MPG B650I EDGE WIFI         | [504746e40c](https://linux-hardware.org/?probe=504746e40c) | Aug 12, 2023 |
| Gigabyte      | H61M-DS2                    | [3181a592ac](https://linux-hardware.org/?probe=3181a592ac) | Aug 12, 2023 |
| Gigabyte      | Z170-HD3P-CF                | [7ef87af541](https://linux-hardware.org/?probe=7ef87af541) | Aug 12, 2023 |
| Unknown       | AB07H                       | [d0b6bc1fce](https://linux-hardware.org/?probe=d0b6bc1fce) | Aug 09, 2023 |
| Gigabyte      | H61M-DS2                    | [939205ed85](https://linux-hardware.org/?probe=939205ed85) | Aug 09, 2023 |
| MSI           | A78M-E45                    | [d39f224497](https://linux-hardware.org/?probe=d39f224497) | Aug 09, 2023 |
| MSI           | B450 GAMING PLUS            | [c8553cabce](https://linux-hardware.org/?probe=c8553cabce) | Aug 08, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [e703e9ae63](https://linux-hardware.org/?probe=e703e9ae63) | Aug 07, 2023 |
| Gigabyte      | H81M-S2H                    | [f895d0afe3](https://linux-hardware.org/?probe=f895d0afe3) | Aug 07, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [e6955ee04c](https://linux-hardware.org/?probe=e6955ee04c) | Aug 07, 2023 |
| Acer          | Aspire TC-605               | [f3bac278d5](https://linux-hardware.org/?probe=f3bac278d5) | Aug 07, 2023 |
| ASRock        | N68C-S UCC                  | [ebe7ed3f69](https://linux-hardware.org/?probe=ebe7ed3f69) | Aug 07, 2023 |
| Acer          | Aspire XC-705               | [37bf6e8191](https://linux-hardware.org/?probe=37bf6e8191) | Aug 06, 2023 |
| ASUSTek       | PRIME H310T R2.0            | [458a26f70c](https://linux-hardware.org/?probe=458a26f70c) | Aug 06, 2023 |
| MSI           | Z490-A PRO                  | [151339db32](https://linux-hardware.org/?probe=151339db32) | Aug 06, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | [7979e7ce95](https://linux-hardware.org/?probe=7979e7ce95) | Aug 05, 2023 |
| MSI           | A78M-E45                    | [988c1f5878](https://linux-hardware.org/?probe=988c1f5878) | Aug 05, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [eabd86788e](https://linux-hardware.org/?probe=eabd86788e) | Aug 04, 2023 |
| HP            | 83E8                        | [0d285189b9](https://linux-hardware.org/?probe=0d285189b9) | Aug 04, 2023 |
| MSI           | Z490-A PRO                  | [71e97069b6](https://linux-hardware.org/?probe=71e97069b6) | Aug 04, 2023 |
| Gigabyte      | F2A88XM-D3HP                | [42ac042892](https://linux-hardware.org/?probe=42ac042892) | Aug 03, 2023 |
| ASUSTek       | H97-PLUS                    | [485793f801](https://linux-hardware.org/?probe=485793f801) | Aug 02, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [a08886d394](https://linux-hardware.org/?probe=a08886d394) | Aug 02, 2023 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [13d25503d7](https://linux-hardware.org/?probe=13d25503d7) | Aug 01, 2023 |
| ASRock        | A320M-DVS R4.0              | [648421ac0a](https://linux-hardware.org/?probe=648421ac0a) | Aug 01, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [2ca9767252](https://linux-hardware.org/?probe=2ca9767252) | Jul 31, 2023 |
| ASUSTek       | H110M-D                     | [9669adfa57](https://linux-hardware.org/?probe=9669adfa57) | Jul 29, 2023 |
| ASUSTek       | PRIME H510M-K R2.0          | [7b5aebd006](https://linux-hardware.org/?probe=7b5aebd006) | Jul 28, 2023 |
| Gigabyte      | A320M-H-CF                  | [2e2b9a12a6](https://linux-hardware.org/?probe=2e2b9a12a6) | Jul 28, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [2af263d1b7](https://linux-hardware.org/?probe=2af263d1b7) | Jul 27, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [60d9839bbe](https://linux-hardware.org/?probe=60d9839bbe) | Jul 27, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [45149f899d](https://linux-hardware.org/?probe=45149f899d) | Jul 26, 2023 |
| ASUSTek       | PRIME H510M-K R2.0          | [c7ec8db97e](https://linux-hardware.org/?probe=c7ec8db97e) | Jul 26, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [865eacc7bb](https://linux-hardware.org/?probe=865eacc7bb) | Jul 25, 2023 |
| HP            | 1495                        | [99072e94e8](https://linux-hardware.org/?probe=99072e94e8) | Jul 25, 2023 |
| HP            | 8719                        | [68870aa596](https://linux-hardware.org/?probe=68870aa596) | Jul 24, 2023 |
| ASUSTek       | PRIME H510M-K R2.0          | [ffee60fde7](https://linux-hardware.org/?probe=ffee60fde7) | Jul 24, 2023 |
| Medion        | H110H4-EM2                  | [443b61cb44](https://linux-hardware.org/?probe=443b61cb44) | Jul 22, 2023 |
| ASUSTek       | Z77-A                       | [4c5a8d18b9](https://linux-hardware.org/?probe=4c5a8d18b9) | Jul 22, 2023 |
| Unknown       | Unknown                     | [06099a3fdd](https://linux-hardware.org/?probe=06099a3fdd) | Jul 21, 2023 |
| Pegatron      | 2AB5                        | [0c95406e21](https://linux-hardware.org/?probe=0c95406e21) | Jul 21, 2023 |
| Pegatron      | 2AB5                        | [b3f1259905](https://linux-hardware.org/?probe=b3f1259905) | Jul 21, 2023 |
| ASRock        | G41C-GS R2.0                | [3ed4a6a897](https://linux-hardware.org/?probe=3ed4a6a897) | Jul 19, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [3428acceaf](https://linux-hardware.org/?probe=3428acceaf) | Jul 19, 2023 |
| MSI           | H81M-E33                    | [dc821e7080](https://linux-hardware.org/?probe=dc821e7080) | Jul 19, 2023 |
| Gigabyte      | B75-D3V                     | [ad01a23df5](https://linux-hardware.org/?probe=ad01a23df5) | Jul 19, 2023 |
| MSI           | B450M MORTAR MAX            | [22bbaa5937](https://linux-hardware.org/?probe=22bbaa5937) | Jul 19, 2023 |
| HP            | 889C                        | [3124074b5a](https://linux-hardware.org/?probe=3124074b5a) | Jul 18, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | [649fb482b4](https://linux-hardware.org/?probe=649fb482b4) | Jul 15, 2023 |
| MSI           | Z97 GAMING 3                | [c8c107c355](https://linux-hardware.org/?probe=c8c107c355) | Jul 15, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | [b84898fc8a](https://linux-hardware.org/?probe=b84898fc8a) | Jul 15, 2023 |
| MSI           | Z97 GAMING 3                | [3841eb7ba0](https://linux-hardware.org/?probe=3841eb7ba0) | Jul 15, 2023 |
| Lenovo        | SHARKBAY NOK                | [66c5696981](https://linux-hardware.org/?probe=66c5696981) | Jul 12, 2023 |
| Gigabyte      | B450 AORUS M                | [500fee1ce5](https://linux-hardware.org/?probe=500fee1ce5) | Jul 11, 2023 |
| Dell          | 0T10XW A01                  | [58fb207824](https://linux-hardware.org/?probe=58fb207824) | Jul 11, 2023 |
| Intel         | DG31PR AAD97573-205         | [0095feba57](https://linux-hardware.org/?probe=0095feba57) | Jul 10, 2023 |
| Intel         | DG31PR AAD97573-205         | [6b4434fd14](https://linux-hardware.org/?probe=6b4434fd14) | Jul 10, 2023 |
| Gigabyte      | Z390 GAMING X-CF            | [ca812ae8ad](https://linux-hardware.org/?probe=ca812ae8ad) | Jul 10, 2023 |
| Gigabyte      | Z170X-Gaming 3              | [a4650f89f7](https://linux-hardware.org/?probe=a4650f89f7) | Jul 10, 2023 |
| Gigabyte      | B560 HD3                    | [437e2c44d9](https://linux-hardware.org/?probe=437e2c44d9) | Jul 09, 2023 |
| ASUSTek       | P5Q PRO TURBO               | [362fd95251](https://linux-hardware.org/?probe=362fd95251) | Jul 08, 2023 |
| ASRock        | A75M-HVS                    | [a0359f0f09](https://linux-hardware.org/?probe=a0359f0f09) | Jul 07, 2023 |
| ASRock        | A75M-HVS                    | [83bbe4315f](https://linux-hardware.org/?probe=83bbe4315f) | Jul 07, 2023 |
| ASUSTek       | PRIME H310T R2.0            | [28b2f72ea7](https://linux-hardware.org/?probe=28b2f72ea7) | Jul 07, 2023 |
| ASRock        | X399 Phantom Gaming 6       | [a2728115f2](https://linux-hardware.org/?probe=a2728115f2) | Jul 05, 2023 |
| Shenzhen M... | F6BFC                       | [f4f1e6f9ff](https://linux-hardware.org/?probe=f4f1e6f9ff) | Jul 05, 2023 |
| Dell          | 0WK833                      | [bf1756a33c](https://linux-hardware.org/?probe=bf1756a33c) | Jul 05, 2023 |
| ASUSTek       | SABERTOOTH P67              | [7acafd9528](https://linux-hardware.org/?probe=7acafd9528) | Jul 04, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [293008463e](https://linux-hardware.org/?probe=293008463e) | Jul 03, 2023 |
| Unknown       | AB07H                       | [868ad2b334](https://linux-hardware.org/?probe=868ad2b334) | Jul 03, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [ff0f73c325](https://linux-hardware.org/?probe=ff0f73c325) | Jul 02, 2023 |
| Gigabyte      | 970A-DS3P                   | [97ebfed554](https://linux-hardware.org/?probe=97ebfed554) | Jul 02, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [488ebd160a](https://linux-hardware.org/?probe=488ebd160a) | Jul 02, 2023 |
| HP            | 8054                        | [30c45def21](https://linux-hardware.org/?probe=30c45def21) | Jul 01, 2023 |
| HP            | 8054                        | [edf94b1f66](https://linux-hardware.org/?probe=edf94b1f66) | Jul 01, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [9f8e4c6a70](https://linux-hardware.org/?probe=9f8e4c6a70) | Jun 30, 2023 |
| Gigabyte      | GA-MA770-DS3                | [5b7bc3205d](https://linux-hardware.org/?probe=5b7bc3205d) | Jun 29, 2023 |
| ASUSTek       | P8Z68-V PRO                 | [a3de72d73c](https://linux-hardware.org/?probe=a3de72d73c) | Jun 29, 2023 |
| MSI           | H61M-P31                    | [9012219f61](https://linux-hardware.org/?probe=9012219f61) | Jun 29, 2023 |
| Dell          | 0WK833                      | [fd4a07e088](https://linux-hardware.org/?probe=fd4a07e088) | Jun 28, 2023 |
| Dell          | 0WK833                      | [39a5ca93a7](https://linux-hardware.org/?probe=39a5ca93a7) | Jun 27, 2023 |
| MSI           | PRO B660M-B DDR4            | [09f4e0e86a](https://linux-hardware.org/?probe=09f4e0e86a) | Jun 27, 2023 |
| Pegatron      | 2AB5                        | [8aaaef4a62](https://linux-hardware.org/?probe=8aaaef4a62) | Jun 27, 2023 |
| MW            | NVR-N5105                   | [36ee490ef2](https://linux-hardware.org/?probe=36ee490ef2) | Jun 26, 2023 |
| Dell          | 0KJCC5 A00                  | [3ec1b71f5c](https://linux-hardware.org/?probe=3ec1b71f5c) | Jun 25, 2023 |
| ASRock        | G31M-GS                     | [f58c462a34](https://linux-hardware.org/?probe=f58c462a34) | Jun 25, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [a8c0f33ffe](https://linux-hardware.org/?probe=a8c0f33ffe) | Jun 25, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [9a30b63c87](https://linux-hardware.org/?probe=9a30b63c87) | Jun 25, 2023 |
| MSI           | A320M-A PRO                 | [2eeb463035](https://linux-hardware.org/?probe=2eeb463035) | Jun 25, 2023 |
| MSI           | A320M-A PRO                 | [ef129b5a6c](https://linux-hardware.org/?probe=ef129b5a6c) | Jun 25, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [785d3130e7](https://linux-hardware.org/?probe=785d3130e7) | Jun 24, 2023 |
| MSI           | B550M-A PRO                 | [68b591e6d8](https://linux-hardware.org/?probe=68b591e6d8) | Jun 24, 2023 |
| ASUSTek       | PRIME H410M-A               | [39d5409264](https://linux-hardware.org/?probe=39d5409264) | Jun 23, 2023 |
| ASUSTek       | M5A88-V EVO                 | [3708ae400f](https://linux-hardware.org/?probe=3708ae400f) | Jun 23, 2023 |
| ASUSTek       | M5A88-V EVO                 | [d447bb1029](https://linux-hardware.org/?probe=d447bb1029) | Jun 23, 2023 |
| Foxconn       | ETON                        | [ae0d87abfb](https://linux-hardware.org/?probe=ae0d87abfb) | Jun 21, 2023 |
| MSI           | X99A SLI Krait Edition      | [2e86965134](https://linux-hardware.org/?probe=2e86965134) | Jun 21, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [5fbfa89321](https://linux-hardware.org/?probe=5fbfa89321) | Jun 21, 2023 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [a1e0b61e89](https://linux-hardware.org/?probe=a1e0b61e89) | Jun 20, 2023 |
| ASRock        | Z590M-ITX/ax                | [5160dd29d0](https://linux-hardware.org/?probe=5160dd29d0) | Jun 20, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [5cbbd51d7f](https://linux-hardware.org/?probe=5cbbd51d7f) | Jun 20, 2023 |
| ASUSTek       | Z170-P                      | [39ed83a165](https://linux-hardware.org/?probe=39ed83a165) | Jun 19, 2023 |
| MSI           | Z170A GAMING M7             | [49e7c6d51b](https://linux-hardware.org/?probe=49e7c6d51b) | Jun 19, 2023 |
| Gigabyte      | H110M-S2H-CF                | [e33558044f](https://linux-hardware.org/?probe=e33558044f) | Jun 18, 2023 |
| ASUSTek       | PRIME B550M-A               | [9b5c44b13a](https://linux-hardware.org/?probe=9b5c44b13a) | Jun 17, 2023 |
| Lenovo        | 3140 SDK0J40700 WIN 3258... | [eebb6ba229](https://linux-hardware.org/?probe=eebb6ba229) | Jun 17, 2023 |
| MSI           | B450 GAMING PLUS            | [8a480175f8](https://linux-hardware.org/?probe=8a480175f8) | Jun 16, 2023 |
| Dell          | 00V62H A00                  | [da12f0d8e3](https://linux-hardware.org/?probe=da12f0d8e3) | Jun 16, 2023 |
| MSI           | B450 GAMING PLUS            | [8a3d74a5fa](https://linux-hardware.org/?probe=8a3d74a5fa) | Jun 16, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [f52a0ddf99](https://linux-hardware.org/?probe=f52a0ddf99) | Jun 16, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [7b9388df1b](https://linux-hardware.org/?probe=7b9388df1b) | Jun 16, 2023 |
| Gigabyte      | H97-HD3                     | [24a487274f](https://linux-hardware.org/?probe=24a487274f) | Jun 16, 2023 |
| Pegatron      | 2A73h                       | [a96d9ae076](https://linux-hardware.org/?probe=a96d9ae076) | Jun 15, 2023 |
| ASUSTek       | ROG STRIX Z590-A GAMING ... | [851020a59f](https://linux-hardware.org/?probe=851020a59f) | Jun 15, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | [7ee7ee0f67](https://linux-hardware.org/?probe=7ee7ee0f67) | Jun 14, 2023 |
| HP            | 3397                        | [e67824996f](https://linux-hardware.org/?probe=e67824996f) | Jun 14, 2023 |
| AMI           | Intel                       | [72c570c2fa](https://linux-hardware.org/?probe=72c570c2fa) | Jun 14, 2023 |
| MW            | NVR-N5105                   | [7481711a2f](https://linux-hardware.org/?probe=7481711a2f) | Jun 13, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [1364983b69](https://linux-hardware.org/?probe=1364983b69) | Jun 12, 2023 |
| MSI           | PRO Z790-A WIFI DDR4        | [0e3bbb5b14](https://linux-hardware.org/?probe=0e3bbb5b14) | Jun 11, 2023 |
| MSI           | B550M-A PRO                 | [c8e822d0d7](https://linux-hardware.org/?probe=c8e822d0d7) | Jun 10, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [1f8c419c47](https://linux-hardware.org/?probe=1f8c419c47) | Jun 10, 2023 |
| MSI           | Boston                      | [cc58f8cdf3](https://linux-hardware.org/?probe=cc58f8cdf3) | Jun 09, 2023 |
| Gigabyte      | H61M-DS2                    | [8b8c6949b6](https://linux-hardware.org/?probe=8b8c6949b6) | Jun 09, 2023 |
| HP            | 3397                        | [c754fea198](https://linux-hardware.org/?probe=c754fea198) | Jun 08, 2023 |
| Gigabyte      | H81M-S2H                    | [fc60082dfe](https://linux-hardware.org/?probe=fc60082dfe) | Jun 08, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [b9e1c5e320](https://linux-hardware.org/?probe=b9e1c5e320) | Jun 08, 2023 |
| Gigabyte      | H81M-S2H                    | [5533070ec1](https://linux-hardware.org/?probe=5533070ec1) | Jun 08, 2023 |
| MSI           | B450M-A PRO MAX             | [230465c003](https://linux-hardware.org/?probe=230465c003) | Jun 08, 2023 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [74f55613b5](https://linux-hardware.org/?probe=74f55613b5) | Jun 08, 2023 |
| HP            | 3397                        | [d86a6fc258](https://linux-hardware.org/?probe=d86a6fc258) | Jun 07, 2023 |
| HP            | 3396                        | [ca540b449f](https://linux-hardware.org/?probe=ca540b449f) | Jun 07, 2023 |
| Gigabyte      | X670 GAMING X AX            | [05d49007a4](https://linux-hardware.org/?probe=05d49007a4) | Jun 07, 2023 |
| MSI           | B550M-A PRO                 | [5fb7d63e80](https://linux-hardware.org/?probe=5fb7d63e80) | Jun 06, 2023 |
| Dell          | 0D24M8 A00                  | [92fe930ecf](https://linux-hardware.org/?probe=92fe930ecf) | Jun 05, 2023 |
| Gigabyte      | H470M DS3H                  | [e7bbac1b14](https://linux-hardware.org/?probe=e7bbac1b14) | Jun 04, 2023 |
| SYWZ          | S200 Series                 | [577c490fb7](https://linux-hardware.org/?probe=577c490fb7) | Jun 04, 2023 |
| ASUSTek       | M4N72-E                     | [51d39945ec](https://linux-hardware.org/?probe=51d39945ec) | Jun 04, 2023 |
| Intel         | X99 V102                    | [ed5a67e8a5](https://linux-hardware.org/?probe=ed5a67e8a5) | Jun 03, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [9966a3f6d1](https://linux-hardware.org/?probe=9966a3f6d1) | Jun 03, 2023 |
| HP            | 3397                        | [530b98edd5](https://linux-hardware.org/?probe=530b98edd5) | Jun 03, 2023 |
| ASUSTek       | PRIME Z390-P                | [64c321d474](https://linux-hardware.org/?probe=64c321d474) | Jun 03, 2023 |
| HP            | 3397                        | [046df77f81](https://linux-hardware.org/?probe=046df77f81) | Jun 02, 2023 |
| MSI           | B450M PRO-VDH PLUS          | [9a0f40789b](https://linux-hardware.org/?probe=9a0f40789b) | Jun 02, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [07e5342fb8](https://linux-hardware.org/?probe=07e5342fb8) | Jun 02, 2023 |
| MSI           | H81M-E33                    | [50f664d550](https://linux-hardware.org/?probe=50f664d550) | Jun 01, 2023 |
| MSI           | H81M-E33                    | [eb2a33204c](https://linux-hardware.org/?probe=eb2a33204c) | Jun 01, 2023 |
| Gigabyte      | H410M S2H V3                | [78e4d7a22b](https://linux-hardware.org/?probe=78e4d7a22b) | Jun 01, 2023 |
| HP            | 2820h                       | [d326b49f48](https://linux-hardware.org/?probe=d326b49f48) | May 29, 2023 |
| ASUSTek       | PRIME Z590-A                | [b5e36f87e6](https://linux-hardware.org/?probe=b5e36f87e6) | May 28, 2023 |
| ASRock        | A320M-HDV R4.0              | [3e43db6ab5](https://linux-hardware.org/?probe=3e43db6ab5) | May 27, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO ... | [24d62f2da3](https://linux-hardware.org/?probe=24d62f2da3) | May 25, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [4f91b6897e](https://linux-hardware.org/?probe=4f91b6897e) | May 24, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [5c4649a83e](https://linux-hardware.org/?probe=5c4649a83e) | May 24, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [21ee588e1c](https://linux-hardware.org/?probe=21ee588e1c) | May 24, 2023 |
| Acer          | Aspire XC-330               | [5d462a687d](https://linux-hardware.org/?probe=5d462a687d) | May 23, 2023 |
| ASUSTek       | PRIME X299-DELUXE           | [c13217076b](https://linux-hardware.org/?probe=c13217076b) | May 23, 2023 |
| ASUSTek       | Z170-PRO                    | [27819563b9](https://linux-hardware.org/?probe=27819563b9) | May 23, 2023 |
| Unknown       | 1.0                         | [54d3a069a4](https://linux-hardware.org/?probe=54d3a069a4) | May 22, 2023 |
| ASRock        | X99 Extreme6/ac             | [8e255dc13b](https://linux-hardware.org/?probe=8e255dc13b) | May 22, 2023 |
| Gigabyte      | X99-UD4-CF                  | [89e6088290](https://linux-hardware.org/?probe=89e6088290) | May 20, 2023 |
| Dell          | 09KPNV A00                  | [118adf4d65](https://linux-hardware.org/?probe=118adf4d65) | May 20, 2023 |
| ASRock        | Z390 Phantom Gaming SLI     | [d17f4a61d7](https://linux-hardware.org/?probe=d17f4a61d7) | May 20, 2023 |
| ASRock        | Z390 Phantom Gaming SLI     | [0362a8829c](https://linux-hardware.org/?probe=0362a8829c) | May 20, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [2afc4ee693](https://linux-hardware.org/?probe=2afc4ee693) | May 18, 2023 |
| Medion        | MS-7675                     | [4890b5bbf9](https://linux-hardware.org/?probe=4890b5bbf9) | May 16, 2023 |
| MSI           | H170A PC MATE               | [389ab53539](https://linux-hardware.org/?probe=389ab53539) | May 15, 2023 |
| Gigabyte      | H310M S2H x.x               | [8f36de95ee](https://linux-hardware.org/?probe=8f36de95ee) | May 15, 2023 |
| Gigabyte      | H310M S2H x.x               | [975de0cf0d](https://linux-hardware.org/?probe=975de0cf0d) | May 15, 2023 |
| Gigabyte      | GA-MA790XT-UD4P             | [dc1d9d7e15](https://linux-hardware.org/?probe=dc1d9d7e15) | May 14, 2023 |
| Acer          | Aspire TC-605               | [f9ccb88980](https://linux-hardware.org/?probe=f9ccb88980) | May 12, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [3d43aab6fd](https://linux-hardware.org/?probe=3d43aab6fd) | May 12, 2023 |
| Gigabyte      | MW51-HP0-00                 | [ed263fdd1b](https://linux-hardware.org/?probe=ed263fdd1b) | May 12, 2023 |
| Gigabyte      | X670 GAMING X AX            | [ebd2a32ce2](https://linux-hardware.org/?probe=ebd2a32ce2) | May 12, 2023 |
| Gigabyte      | X670 GAMING X AX            | [352c0902e9](https://linux-hardware.org/?probe=352c0902e9) | May 11, 2023 |
| Medion        | MS-7848                     | [e5e1e75529](https://linux-hardware.org/?probe=e5e1e75529) | May 11, 2023 |
| Acer          | Aspire TC-605               | [d4846b3b14](https://linux-hardware.org/?probe=d4846b3b14) | May 10, 2023 |
| HP            | 304Ah                       | [7c6a6b156f](https://linux-hardware.org/?probe=7c6a6b156f) | May 09, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [83741a7884](https://linux-hardware.org/?probe=83741a7884) | May 09, 2023 |
| ASRock        | A55M-DGS                    | [528232ffb1](https://linux-hardware.org/?probe=528232ffb1) | May 09, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [b76481d6a9](https://linux-hardware.org/?probe=b76481d6a9) | May 09, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [228e778389](https://linux-hardware.org/?probe=228e778389) | May 09, 2023 |
| Gigabyte      | X99-UD4-CF                  | [9e3f14cf8d](https://linux-hardware.org/?probe=9e3f14cf8d) | May 08, 2023 |
| Acer          | Aspire XC-330               | [9369acb33c](https://linux-hardware.org/?probe=9369acb33c) | May 07, 2023 |
| Gigabyte      | P43-ES3G                    | [1095d1ef7f](https://linux-hardware.org/?probe=1095d1ef7f) | May 06, 2023 |
| ASUSTek       | P8H61-M LX                  | [6c96dbe3f3](https://linux-hardware.org/?probe=6c96dbe3f3) | May 05, 2023 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [421f2de1c3](https://linux-hardware.org/?probe=421f2de1c3) | May 05, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [7dabc9fc5c](https://linux-hardware.org/?probe=7dabc9fc5c) | May 05, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [18895a52d4](https://linux-hardware.org/?probe=18895a52d4) | May 05, 2023 |
| Gigabyte      | EX58-UD5                    | [1f8f3c96a5](https://linux-hardware.org/?probe=1f8f3c96a5) | May 05, 2023 |
| Gigabyte      | EX58-UD5                    | [43f32e7ed8](https://linux-hardware.org/?probe=43f32e7ed8) | May 05, 2023 |
| ASUSTek       | H81M-K                      | [e146c82a49](https://linux-hardware.org/?probe=e146c82a49) | May 03, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [caf5cbc634](https://linux-hardware.org/?probe=caf5cbc634) | May 03, 2023 |
| ASUSTek       | B150M-A/M.2                 | [cd68a79e95](https://linux-hardware.org/?probe=cd68a79e95) | May 03, 2023 |
| Unknown       | Intel X79                   | [6b1ddbd923](https://linux-hardware.org/?probe=6b1ddbd923) | May 03, 2023 |
| Gigabyte      | X99-UD4-CF                  | [c2dcdb892d](https://linux-hardware.org/?probe=c2dcdb892d) | May 01, 2023 |
| Gigabyte      | H61M-D2H-USB3               | [9098e5d498](https://linux-hardware.org/?probe=9098e5d498) | May 01, 2023 |
| NEC Comput... | ECS-945G                    | [5f6daf506f](https://linux-hardware.org/?probe=5f6daf506f) | May 01, 2023 |
| HP            | 1495                        | [d6e629523f](https://linux-hardware.org/?probe=d6e629523f) | May 01, 2023 |
| Medion        | D3F3-EM                     | [6b9e38ad6c](https://linux-hardware.org/?probe=6b9e38ad6c) | Apr 30, 2023 |
| Gigabyte      | B365M D3H-CF                | [8c4352985e](https://linux-hardware.org/?probe=8c4352985e) | Apr 29, 2023 |
| ASUSTek       | H110M-D                     | [81cff8a578](https://linux-hardware.org/?probe=81cff8a578) | Apr 29, 2023 |
| Gigabyte      | AX370-Gaming 5              | [a418b302b9](https://linux-hardware.org/?probe=a418b302b9) | Apr 28, 2023 |
| MSI           | Z270 GAMING PRO CARBON      | [852dac1035](https://linux-hardware.org/?probe=852dac1035) | Apr 28, 2023 |
| MSI           | 970 GAMING                  | [44c5943019](https://linux-hardware.org/?probe=44c5943019) | Apr 27, 2023 |
| Acer          | Aspire TC-605               | [b9dcc7f752](https://linux-hardware.org/?probe=b9dcc7f752) | Apr 26, 2023 |
| HP            | 8055                        | [a897208085](https://linux-hardware.org/?probe=a897208085) | Apr 26, 2023 |
| MSI           | B250M PRO-VH                | [f132c966f5](https://linux-hardware.org/?probe=f132c966f5) | Apr 25, 2023 |
| ASRock        | H81M-VG4 R2.0               | [09c7ae9819](https://linux-hardware.org/?probe=09c7ae9819) | Apr 25, 2023 |
| Gigabyte      | H61MA-D3V                   | [a37deef915](https://linux-hardware.org/?probe=a37deef915) | Apr 24, 2023 |
| Gigabyte      | EX58-UD5                    | [3d8d7c49f8](https://linux-hardware.org/?probe=3d8d7c49f8) | Apr 24, 2023 |
| Dell          | 08HPGT A02                  | [04f68362d5](https://linux-hardware.org/?probe=04f68362d5) | Apr 24, 2023 |
| Dell          | 08HPGT A02                  | [d352ecf4ed](https://linux-hardware.org/?probe=d352ecf4ed) | Apr 24, 2023 |
| ASUSTek       | A88XM-A/USB                 | [f4a215fc46](https://linux-hardware.org/?probe=f4a215fc46) | Apr 24, 2023 |
| Gigabyte      | EX58-UD5                    | [e9a3b8f1d1](https://linux-hardware.org/?probe=e9a3b8f1d1) | Apr 24, 2023 |
| Gigabyte      | Z390 GAMING X-CF            | [c11ea1fc19](https://linux-hardware.org/?probe=c11ea1fc19) | Apr 23, 2023 |
| Gigabyte      | Z370 HD3P-CF                | [7609d632a4](https://linux-hardware.org/?probe=7609d632a4) | Apr 23, 2023 |
| Gigabyte      | Z390 GAMING X-CF            | [1a316c62a1](https://linux-hardware.org/?probe=1a316c62a1) | Apr 23, 2023 |
| HP            | 0AA8h                       | [b927834a03](https://linux-hardware.org/?probe=b927834a03) | Apr 23, 2023 |
| Shuttle       | FG45 V10                    | [b5a9d7b1e4](https://linux-hardware.org/?probe=b5a9d7b1e4) | Apr 21, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [81334f294e](https://linux-hardware.org/?probe=81334f294e) | Apr 20, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [cebfbef6d8](https://linux-hardware.org/?probe=cebfbef6d8) | Apr 20, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [5a9a6c553f](https://linux-hardware.org/?probe=5a9a6c553f) | Apr 20, 2023 |
| ASUSTek       | Z170-PRO                    | [970c4dfa6f](https://linux-hardware.org/?probe=970c4dfa6f) | Apr 20, 2023 |
| Gigabyte      | B365M DS3H                  | [3193403ef5](https://linux-hardware.org/?probe=3193403ef5) | Apr 19, 2023 |
| Gigabyte      | B365M DS3H                  | [80ee2192b6](https://linux-hardware.org/?probe=80ee2192b6) | Apr 19, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [8858427eed](https://linux-hardware.org/?probe=8858427eed) | Apr 19, 2023 |
| ASUSTek       | PRIME Z390-P                | [fdb308cd9f](https://linux-hardware.org/?probe=fdb308cd9f) | Apr 19, 2023 |
| HP            | 212A                        | [178f3b9c05](https://linux-hardware.org/?probe=178f3b9c05) | Apr 17, 2023 |
| MSI           | H310M PRO-VDH               | [01452c33d1](https://linux-hardware.org/?probe=01452c33d1) | Apr 16, 2023 |
| Lenovo        | SHARKBAY SDK0J40700 WIN ... | [00b59d56cd](https://linux-hardware.org/?probe=00b59d56cd) | Apr 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [3faf4e88e1](https://linux-hardware.org/?probe=3faf4e88e1) | Apr 16, 2023 |
| AMI           | Intel                       | [b7a63bbfc7](https://linux-hardware.org/?probe=b7a63bbfc7) | Apr 15, 2023 |
| BESSTAR Te... | UM700                       | [8c450d2469](https://linux-hardware.org/?probe=8c450d2469) | Apr 15, 2023 |
| AMI           | Intel                       | [ec0a5e657e](https://linux-hardware.org/?probe=ec0a5e657e) | Apr 14, 2023 |
| ASRock        | H81M-VG4 R2.0               | [cc951809ed](https://linux-hardware.org/?probe=cc951809ed) | Apr 14, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [d5212d6298](https://linux-hardware.org/?probe=d5212d6298) | Apr 13, 2023 |
| Gigabyte      | AX370-Gaming 5              | [0ba5f3a06e](https://linux-hardware.org/?probe=0ba5f3a06e) | Apr 12, 2023 |
| HP            | 3396                        | [25eac72561](https://linux-hardware.org/?probe=25eac72561) | Apr 12, 2023 |
| HP            | 1589                        | [c04488f359](https://linux-hardware.org/?probe=c04488f359) | Apr 11, 2023 |
| Gigabyte      | B75-D3V                     | [fe025c9491](https://linux-hardware.org/?probe=fe025c9491) | Apr 11, 2023 |
| ASUSTek       | P5K                         | [36bc294c5b](https://linux-hardware.org/?probe=36bc294c5b) | Apr 11, 2023 |
| Gigabyte      | X299 AORUS Ultra Gaming ... | [415b7ce80b](https://linux-hardware.org/?probe=415b7ce80b) | Apr 10, 2023 |
| BESSTAR Te... | HX90                        | [2639d597e8](https://linux-hardware.org/?probe=2639d597e8) | Apr 10, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [7f052050d9](https://linux-hardware.org/?probe=7f052050d9) | Apr 10, 2023 |
| HP            | 1998                        | [3974cfbb0c](https://linux-hardware.org/?probe=3974cfbb0c) | Apr 09, 2023 |
| MSI           | A68HM-E33 V2                | [05fc2725cf](https://linux-hardware.org/?probe=05fc2725cf) | Apr 09, 2023 |
| Dell          | 0M5DCD A00                  | [f65d106f65](https://linux-hardware.org/?probe=f65d106f65) | Apr 08, 2023 |
| AMI           | Intel                       | [48c620d141](https://linux-hardware.org/?probe=48c620d141) | Apr 08, 2023 |
| Gigabyte      | F2A68HM-H                   | [98bc626360](https://linux-hardware.org/?probe=98bc626360) | Apr 07, 2023 |
| HP            | 1998                        | [50421ddca5](https://linux-hardware.org/?probe=50421ddca5) | Apr 07, 2023 |
| Packard Be... | IMEDIA S2870 V1.0           | [61e1ab6733](https://linux-hardware.org/?probe=61e1ab6733) | Apr 06, 2023 |
| ASUSTek       | PRIME Z490M-PLUS            | [1190aa9be8](https://linux-hardware.org/?probe=1190aa9be8) | Apr 06, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [03db223af4](https://linux-hardware.org/?probe=03db223af4) | Apr 06, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [f8c2ffcd09](https://linux-hardware.org/?probe=f8c2ffcd09) | Apr 06, 2023 |
| ASUSTek       | PRIME A320M-K               | [6dbb59e2fc](https://linux-hardware.org/?probe=6dbb59e2fc) | Apr 05, 2023 |
| HP            | 1998                        | [4830678f31](https://linux-hardware.org/?probe=4830678f31) | Apr 05, 2023 |
| ASUSTek       | VM42                        | [84f848ea21](https://linux-hardware.org/?probe=84f848ea21) | Apr 05, 2023 |
| ASUSTek       | Z170-K                      | [d9ab0a1946](https://linux-hardware.org/?probe=d9ab0a1946) | Apr 05, 2023 |
| ASUSTek       | PRIME B250M-PLUS            | [6f4013d94e](https://linux-hardware.org/?probe=6f4013d94e) | Apr 05, 2023 |
| HP            | 3397                        | [175b460d57](https://linux-hardware.org/?probe=175b460d57) | Apr 05, 2023 |
| HP            | 3397                        | [b512b25055](https://linux-hardware.org/?probe=b512b25055) | Apr 05, 2023 |
| Dell          | 042P49 A02                  | [74a232499a](https://linux-hardware.org/?probe=74a232499a) | Apr 04, 2023 |
| ASUSTek       | PRIME B250M-PLUS            | [0401a50bac](https://linux-hardware.org/?probe=0401a50bac) | Apr 04, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [151ffca106](https://linux-hardware.org/?probe=151ffca106) | Apr 04, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [fb78fdb60c](https://linux-hardware.org/?probe=fb78fdb60c) | Apr 04, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [849adee9bf](https://linux-hardware.org/?probe=849adee9bf) | Apr 03, 2023 |
| MSI           | A320M-A PRO MAX             | [54fbd647bc](https://linux-hardware.org/?probe=54fbd647bc) | Apr 02, 2023 |
| Gigabyte      | EX58-UD5                    | [0fbed59931](https://linux-hardware.org/?probe=0fbed59931) | Apr 02, 2023 |
| Gigabyte      | Z390 UD                     | [fabc275714](https://linux-hardware.org/?probe=fabc275714) | Apr 01, 2023 |
| ASUSTek       | PRIME A320M-K               | [5919c1d671](https://linux-hardware.org/?probe=5919c1d671) | Apr 01, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [e3a13c69ef](https://linux-hardware.org/?probe=e3a13c69ef) | Apr 01, 2023 |
| Gigabyte      | F2A88XM-HD3                 | [39bc576f7f](https://linux-hardware.org/?probe=39bc576f7f) | Apr 01, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [369bd03522](https://linux-hardware.org/?probe=369bd03522) | Apr 01, 2023 |
| MSI           | PRO X670-P WIFI             | [bb72de54b6](https://linux-hardware.org/?probe=bb72de54b6) | Mar 31, 2023 |
| HP            | 1998                        | [c47c52dfc6](https://linux-hardware.org/?probe=c47c52dfc6) | Mar 31, 2023 |
| Gigabyte      | B250M-DS3H-CF               | [d72978731a](https://linux-hardware.org/?probe=d72978731a) | Mar 30, 2023 |
| Gigabyte      | A520 AORUS ELITE            | [f7f74305ba](https://linux-hardware.org/?probe=f7f74305ba) | Mar 30, 2023 |
| MSI           | B450M BAZOOKA V2            | [7888e091f7](https://linux-hardware.org/?probe=7888e091f7) | Mar 30, 2023 |
| MSI           | PRO X670-P WIFI             | [ed35fbea6c](https://linux-hardware.org/?probe=ed35fbea6c) | Mar 30, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [244ffc8736](https://linux-hardware.org/?probe=244ffc8736) | Mar 30, 2023 |
| HP            | 1495                        | [75702f8b1d](https://linux-hardware.org/?probe=75702f8b1d) | Mar 29, 2023 |
| HP            | 1495                        | [c342260a77](https://linux-hardware.org/?probe=c342260a77) | Mar 29, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [307a8bce3e](https://linux-hardware.org/?probe=307a8bce3e) | Mar 29, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [b924b0ff06](https://linux-hardware.org/?probe=b924b0ff06) | Mar 28, 2023 |
| Acer          | Veriton M4630G V:1.0        | [7fba52ef43](https://linux-hardware.org/?probe=7fba52ef43) | Mar 27, 2023 |
| MSI           | G41M-P33 Combo              | [6a3fedcc68](https://linux-hardware.org/?probe=6a3fedcc68) | Mar 26, 2023 |
| Gigabyte      | GA-MA790XT-UD4P             | [8a0cc5a4cb](https://linux-hardware.org/?probe=8a0cc5a4cb) | Mar 24, 2023 |
| HP            | 1790                        | [1a468c1b1c](https://linux-hardware.org/?probe=1a468c1b1c) | Mar 24, 2023 |
| ASRock        | H110M-HDV                   | [cfe369e6b8](https://linux-hardware.org/?probe=cfe369e6b8) | Mar 24, 2023 |
| Gigabyte      | B450M DS3H-CF               | [81273bd2b0](https://linux-hardware.org/?probe=81273bd2b0) | Mar 24, 2023 |
| Gigabyte      | B450M DS3H-CF               | [2db2fb4a5a](https://linux-hardware.org/?probe=2db2fb4a5a) | Mar 24, 2023 |
| Gigabyte      | B450M DS3H-CF               | [79cbdbc9c1](https://linux-hardware.org/?probe=79cbdbc9c1) | Mar 24, 2023 |
| ASUSTek       | PRIME Z690-P                | [6b3cdb2b1a](https://linux-hardware.org/?probe=6b3cdb2b1a) | Mar 23, 2023 |
| ASUSTek       | PRIME H510M-E               | [fc5894dcb4](https://linux-hardware.org/?probe=fc5894dcb4) | Mar 23, 2023 |
| ASUSTek       | PB60                        | [ec438486aa](https://linux-hardware.org/?probe=ec438486aa) | Mar 22, 2023 |
| MSI           | MEG X570 ACE                | [c2bab115eb](https://linux-hardware.org/?probe=c2bab115eb) | Mar 22, 2023 |
| Gigabyte      | Z77X-D3H                    | [aab84f14ed](https://linux-hardware.org/?probe=aab84f14ed) | Mar 21, 2023 |
| ASUSTek       | Maximus VI HERO             | [deaf7b9049](https://linux-hardware.org/?probe=deaf7b9049) | Mar 21, 2023 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | [293e9a941a](https://linux-hardware.org/?probe=293e9a941a) | Mar 20, 2023 |
| MSI           | PRO Z790-P WIFI             | [038bd3a32b](https://linux-hardware.org/?probe=038bd3a32b) | Mar 20, 2023 |
| HP            | 158A                        | [61467de4d5](https://linux-hardware.org/?probe=61467de4d5) | Mar 19, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [f048ae8dec](https://linux-hardware.org/?probe=f048ae8dec) | Mar 19, 2023 |
| ASRock        | H110M-HDV                   | [5228141efd](https://linux-hardware.org/?probe=5228141efd) | Mar 16, 2023 |
| Acer          | FIH57                       | [ee8c95f841](https://linux-hardware.org/?probe=ee8c95f841) | Mar 16, 2023 |
| Intel         | Unknown                     | [b4b73aafa0](https://linux-hardware.org/?probe=b4b73aafa0) | Mar 15, 2023 |
| ASUSTek       | H110M-D                     | [c436834b30](https://linux-hardware.org/?probe=c436834b30) | Mar 14, 2023 |
| ASUSTek       | P5Q PRO TURBO               | [44fc80c7d5](https://linux-hardware.org/?probe=44fc80c7d5) | Mar 13, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [39d0e8595c](https://linux-hardware.org/?probe=39d0e8595c) | Mar 12, 2023 |
| ASUSTek       | PRIME H510M-E               | [cf5cbabe11](https://linux-hardware.org/?probe=cf5cbabe11) | Mar 12, 2023 |
| ASUSTek       | PRIME Z590-A                | [751bedd6a9](https://linux-hardware.org/?probe=751bedd6a9) | Mar 12, 2023 |
| Gigabyte      | B760M AORUS ELITE AX        | [daf687f0a1](https://linux-hardware.org/?probe=daf687f0a1) | Mar 12, 2023 |
| MSI           | MS-B1831                    | [a9bfb4f294](https://linux-hardware.org/?probe=a9bfb4f294) | Mar 11, 2023 |
| ASUSTek       | PRIME Z270-P                | [8f2b6b3bc1](https://linux-hardware.org/?probe=8f2b6b3bc1) | Mar 11, 2023 |
| Gigabyte      | B760M DS3H DDR4             | [5df81d1297](https://linux-hardware.org/?probe=5df81d1297) | Mar 09, 2023 |
| Gigabyte      | H61M-DS2                    | [a40a70a964](https://linux-hardware.org/?probe=a40a70a964) | Mar 09, 2023 |
| Dell          | 0JP3NX A01                  | [946f48cdf6](https://linux-hardware.org/?probe=946f48cdf6) | Mar 09, 2023 |
| ASUSTek       | PRIME A320M-K               | [93875c7518](https://linux-hardware.org/?probe=93875c7518) | Mar 09, 2023 |
| ASUSTek       | P5G41T-M LX                 | [4f55573ba6](https://linux-hardware.org/?probe=4f55573ba6) | Mar 08, 2023 |
| Intel         | JSL MRD                     | [ac75dbf1f6](https://linux-hardware.org/?probe=ac75dbf1f6) | Mar 08, 2023 |
| HP            | 0AACh                       | [2f4ba72670](https://linux-hardware.org/?probe=2f4ba72670) | Mar 08, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [7c17068a98](https://linux-hardware.org/?probe=7c17068a98) | Mar 08, 2023 |
| HP            | 0AA8h                       | [6552e8b371](https://linux-hardware.org/?probe=6552e8b371) | Mar 07, 2023 |
| Intel         | DH55TC AAE70932-303         | [4e2cd40175](https://linux-hardware.org/?probe=4e2cd40175) | Mar 07, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [c6bb0ba4a6](https://linux-hardware.org/?probe=c6bb0ba4a6) | Mar 05, 2023 |
| ASUSTek       | P8P67 DELUXE                | [31e4b3ada8](https://linux-hardware.org/?probe=31e4b3ada8) | Mar 05, 2023 |
| Gigabyte      | EX58-UD5                    | [8805f0bce5](https://linux-hardware.org/?probe=8805f0bce5) | Mar 05, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [f4cf2185ea](https://linux-hardware.org/?probe=f4cf2185ea) | Mar 04, 2023 |
| ASUSTek       | P7H55-M LX                  | [79e06d188d](https://linux-hardware.org/?probe=79e06d188d) | Mar 04, 2023 |
| Gigabyte      | H61M-DS2                    | [49462bd855](https://linux-hardware.org/?probe=49462bd855) | Mar 04, 2023 |
| Gigabyte      | B85M-DS3H-A                 | [914a9990c4](https://linux-hardware.org/?probe=914a9990c4) | Mar 04, 2023 |
| Gigabyte      | H61M-DS2                    | [c7cee84058](https://linux-hardware.org/?probe=c7cee84058) | Mar 04, 2023 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | [a9c39c2b82](https://linux-hardware.org/?probe=a9c39c2b82) | Mar 04, 2023 |
| MSI           | B250M MORTAR                | [a4e8543fe2](https://linux-hardware.org/?probe=a4e8543fe2) | Mar 03, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [5033b7233d](https://linux-hardware.org/?probe=5033b7233d) | Mar 03, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [8f61a5507b](https://linux-hardware.org/?probe=8f61a5507b) | Mar 02, 2023 |
| ASUSTek       | M5A97 R2.0                  | [0e66878368](https://linux-hardware.org/?probe=0e66878368) | Mar 02, 2023 |
| HPE           | ProLiant MicroServer Gen... | [11c1bf8316](https://linux-hardware.org/?probe=11c1bf8316) | Mar 02, 2023 |
| Intel         | X79 V2.72A                  | [ae4efdfbc5](https://linux-hardware.org/?probe=ae4efdfbc5) | Mar 02, 2023 |
| Gigabyte      | H81M-S1                     | [0a38248462](https://linux-hardware.org/?probe=0a38248462) | Mar 02, 2023 |
| ASRock        | Q1900M Pro3                 | [ef9e90045e](https://linux-hardware.org/?probe=ef9e90045e) | Mar 01, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [50520b2cf0](https://linux-hardware.org/?probe=50520b2cf0) | Mar 01, 2023 |
| Lenovo        | Bantry CRB 31900058 STD     | [268413a47c](https://linux-hardware.org/?probe=268413a47c) | Mar 01, 2023 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | [84a1a2c71e](https://linux-hardware.org/?probe=84a1a2c71e) | Mar 01, 2023 |
| Lenovo        | Bantry CRB 31900058 STD     | [169e938f25](https://linux-hardware.org/?probe=169e938f25) | Mar 01, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [8f8eaa9d53](https://linux-hardware.org/?probe=8f8eaa9d53) | Mar 01, 2023 |
| ASUSTek       | Z170-A                      | [a4d77f98eb](https://linux-hardware.org/?probe=a4d77f98eb) | Feb 28, 2023 |
| ASUSTek       | AT4NM10T-I                  | [921aebe62a](https://linux-hardware.org/?probe=921aebe62a) | Feb 28, 2023 |
| ASUSTek       | AT4NM10T-I                  | [fa2df8125a](https://linux-hardware.org/?probe=fa2df8125a) | Feb 28, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [8cadddf432](https://linux-hardware.org/?probe=8cadddf432) | Feb 28, 2023 |
| AMI           | Cherry Trail CR             | [24952b3b19](https://linux-hardware.org/?probe=24952b3b19) | Feb 27, 2023 |
| ASRock        | A320M-HDV R4.0              | [319e003280](https://linux-hardware.org/?probe=319e003280) | Feb 26, 2023 |
| BESSTAR Te... | B550                        | [6a77bfec73](https://linux-hardware.org/?probe=6a77bfec73) | Feb 26, 2023 |
| BESSTAR Te... | B550                        | [d3e84076c7](https://linux-hardware.org/?probe=d3e84076c7) | Feb 25, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [32453b16fb](https://linux-hardware.org/?probe=32453b16fb) | Feb 25, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [2e7905f753](https://linux-hardware.org/?probe=2e7905f753) | Feb 24, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [cbadc857a2](https://linux-hardware.org/?probe=cbadc857a2) | Feb 24, 2023 |
| ASUSTek       | P5QL PRO                    | [c7477f1aca](https://linux-hardware.org/?probe=c7477f1aca) | Feb 24, 2023 |
| ASUSTek       | H61M-K                      | [9d39d13682](https://linux-hardware.org/?probe=9d39d13682) | Feb 23, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [af2a414265](https://linux-hardware.org/?probe=af2a414265) | Feb 23, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [3c27f298a3](https://linux-hardware.org/?probe=3c27f298a3) | Feb 23, 2023 |
| HP            | 0AA8h                       | [8bb60bdebb](https://linux-hardware.org/?probe=8bb60bdebb) | Feb 22, 2023 |
| Gigabyte      | H81M-S2H                    | [d8bafec2da](https://linux-hardware.org/?probe=d8bafec2da) | Feb 22, 2023 |
| Dell          | 0WMJ54 A01                  | [e7175cb8fe](https://linux-hardware.org/?probe=e7175cb8fe) | Feb 22, 2023 |
| HP            | ProLiant ML110 G7           | [56cbaf4274](https://linux-hardware.org/?probe=56cbaf4274) | Feb 21, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [f75f800bd4](https://linux-hardware.org/?probe=f75f800bd4) | Feb 20, 2023 |
| Gigabyte      | H81M-S2H                    | [a4b049c92b](https://linux-hardware.org/?probe=a4b049c92b) | Feb 20, 2023 |
| Acer          | H57M01                      | [5e5e9d03a4](https://linux-hardware.org/?probe=5e5e9d03a4) | Feb 19, 2023 |
| Gigabyte      | H77-DS3H                    | [3f26c5e55c](https://linux-hardware.org/?probe=3f26c5e55c) | Feb 19, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [84e946f098](https://linux-hardware.org/?probe=84e946f098) | Feb 18, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [eff21e4d65](https://linux-hardware.org/?probe=eff21e4d65) | Feb 18, 2023 |
| Acer          | Aspire TC-895 V:1.0         | [cbe7b5e34f](https://linux-hardware.org/?probe=cbe7b5e34f) | Feb 18, 2023 |
| Gigabyte      | P31-ES3G                    | [2c3eb25bc4](https://linux-hardware.org/?probe=2c3eb25bc4) | Feb 18, 2023 |
| MSI           | H270 PC MATE                | [6581748d54](https://linux-hardware.org/?probe=6581748d54) | Feb 17, 2023 |
| Dell          | 0T10XW A02                  | [0f6c993491](https://linux-hardware.org/?probe=0f6c993491) | Feb 17, 2023 |
| Intel         | DH77DF AAG40293-301         | [f44579d8b4](https://linux-hardware.org/?probe=f44579d8b4) | Feb 17, 2023 |
| Gigabyte      | H81M-S2H                    | [db4fef5830](https://linux-hardware.org/?probe=db4fef5830) | Feb 17, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS            | [5d03d010f4](https://linux-hardware.org/?probe=5d03d010f4) | Feb 16, 2023 |
| Intel         | X79M-S                      | [2d3579e9b7](https://linux-hardware.org/?probe=2d3579e9b7) | Feb 15, 2023 |
| Gigabyte      | G41MT-D3V                   | [8a7ce6b005](https://linux-hardware.org/?probe=8a7ce6b005) | Feb 15, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [e5b971a4b0](https://linux-hardware.org/?probe=e5b971a4b0) | Feb 14, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [4211a6a7f4](https://linux-hardware.org/?probe=4211a6a7f4) | Feb 14, 2023 |
| Gigabyte      | B450M DS3H-CF               | [f3e396ccc3](https://linux-hardware.org/?probe=f3e396ccc3) | Feb 14, 2023 |
| ASUSTek       | PRIME Z590-A                | [926e34c5a9](https://linux-hardware.org/?probe=926e34c5a9) | Feb 14, 2023 |
| Gigabyte      | H81M-S2H                    | [7458415afe](https://linux-hardware.org/?probe=7458415afe) | Feb 13, 2023 |
| MSI           | Z270 GAMING M3              | [39b7eef9e8](https://linux-hardware.org/?probe=39b7eef9e8) | Feb 12, 2023 |
| ASUSTek       | P5VD2-X                     | [32a509e760](https://linux-hardware.org/?probe=32a509e760) | Feb 11, 2023 |
| MSI           | Z370 GAMING PLUS            | [9621fdeccb](https://linux-hardware.org/?probe=9621fdeccb) | Feb 11, 2023 |
| MSI           | Z370 GAMING PLUS            | [523c8db418](https://linux-hardware.org/?probe=523c8db418) | Feb 11, 2023 |
| ASRock        | X399 Phantom Gaming 6       | [7b2f03d111](https://linux-hardware.org/?probe=7b2f03d111) | Feb 10, 2023 |
| Dell          | 03NVJ6 A00                  | [f7df102318](https://linux-hardware.org/?probe=f7df102318) | Feb 10, 2023 |
| Lenovo        | 3741 NOK                    | [eeb2a331be](https://linux-hardware.org/?probe=eeb2a331be) | Feb 08, 2023 |
| Gigabyte      | H61MA-D2V                   | [380eb0d0e1](https://linux-hardware.org/?probe=380eb0d0e1) | Feb 08, 2023 |
| BESSTAR Te... | B550                        | [49e414926e](https://linux-hardware.org/?probe=49e414926e) | Feb 07, 2023 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | [bc5b9a2c5d](https://linux-hardware.org/?probe=bc5b9a2c5d) | Feb 06, 2023 |
| Unknown       | Intel X79                   | [2ad659fd7a](https://linux-hardware.org/?probe=2ad659fd7a) | Feb 06, 2023 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | [55402fea35](https://linux-hardware.org/?probe=55402fea35) | Feb 05, 2023 |
| Gigabyte      | F2A88XM-DS2                 | [d9313ff1c1](https://linux-hardware.org/?probe=d9313ff1c1) | Feb 05, 2023 |
| Gigabyte      | B450M S2H                   | [c3891f43b5](https://linux-hardware.org/?probe=c3891f43b5) | Feb 05, 2023 |
| Shenzhen M... | F7BFC                       | [4d3066b96e](https://linux-hardware.org/?probe=4d3066b96e) | Feb 05, 2023 |
| SLIMBOOK      | ONE-AMD-M4                  | [dc948f9e70](https://linux-hardware.org/?probe=dc948f9e70) | Feb 05, 2023 |
| Cisco Syst... | UCSC-C220-M3S 74-10442-0... | [9e8c261333](https://linux-hardware.org/?probe=9e8c261333) | Feb 05, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [bede5aa93c](https://linux-hardware.org/?probe=bede5aa93c) | Feb 05, 2023 |
| Supermicro    | X9DBL-3F/X9DBL-iF           | [280dd65788](https://linux-hardware.org/?probe=280dd65788) | Feb 04, 2023 |
| Supermicro    | X9DBL-3F/X9DBL-iF           | [8f0808edd3](https://linux-hardware.org/?probe=8f0808edd3) | Feb 04, 2023 |
| Supermicro    | H12DSU-iN                   | [0bd8186d9e](https://linux-hardware.org/?probe=0bd8186d9e) | Feb 04, 2023 |
| HP            | 805D                        | [109d9e2356](https://linux-hardware.org/?probe=109d9e2356) | Feb 04, 2023 |
| MSI           | H270 PC MATE                | [dafdc36e54](https://linux-hardware.org/?probe=dafdc36e54) | Feb 03, 2023 |
| HP            | 805D                        | [ed417f3a04](https://linux-hardware.org/?probe=ed417f3a04) | Feb 03, 2023 |
| HP            | 805D                        | [7a8522045b](https://linux-hardware.org/?probe=7a8522045b) | Feb 03, 2023 |
| Gigabyte      | Z690M DS3H DDR4             | [8f858cb9b9](https://linux-hardware.org/?probe=8f858cb9b9) | Jan 31, 2023 |
| Jetway        | I61G-ITX                    | [24cf6ad56e](https://linux-hardware.org/?probe=24cf6ad56e) | Jan 31, 2023 |
| Gigabyte      | B450M DS3H V2               | [b5f1f3cb42](https://linux-hardware.org/?probe=b5f1f3cb42) | Jan 30, 2023 |
| HP            | 339A                        | [3bc7df3921](https://linux-hardware.org/?probe=3bc7df3921) | Jan 30, 2023 |
| Acer          | Aspire TC-895 V:1.0         | [190e9b4aee](https://linux-hardware.org/?probe=190e9b4aee) | Jan 30, 2023 |
| ASUSTek       | P8H67                       | [c6163491b5](https://linux-hardware.org/?probe=c6163491b5) | Jan 29, 2023 |
| ASUSTek       | P5Q PRO TURBO               | [72e0a3fde5](https://linux-hardware.org/?probe=72e0a3fde5) | Jan 28, 2023 |
| ASUSTek       | P5Q PRO TURBO               | [a1cb8edb5a](https://linux-hardware.org/?probe=a1cb8edb5a) | Jan 28, 2023 |
| Gigabyte      | Z97M-DS3H                   | [e9fc2c87df](https://linux-hardware.org/?probe=e9fc2c87df) | Jan 28, 2023 |
| MSI           | B560M PRO-VDH               | [cd55d1ec5d](https://linux-hardware.org/?probe=cd55d1ec5d) | Jan 28, 2023 |
| Gigabyte      | F2A88XM-D3H                 | [1605fbe62a](https://linux-hardware.org/?probe=1605fbe62a) | Jan 28, 2023 |
| HP            | 3397                        | [764f737fcf](https://linux-hardware.org/?probe=764f737fcf) | Jan 27, 2023 |
| Medion        | MS-7675                     | [1d9d209dbf](https://linux-hardware.org/?probe=1d9d209dbf) | Jan 27, 2023 |
| HP            | 3397                        | [10b6614763](https://linux-hardware.org/?probe=10b6614763) | Jan 26, 2023 |
| MSI           | MS-7383                     | [d47659fcf8](https://linux-hardware.org/?probe=d47659fcf8) | Jan 25, 2023 |
| MSI           | MS-7383                     | [b848100b0e](https://linux-hardware.org/?probe=b848100b0e) | Jan 25, 2023 |
| ASUSTek       | B85M-G                      | [73bef1464f](https://linux-hardware.org/?probe=73bef1464f) | Jan 25, 2023 |
| ASRock        | G31M-S                      | [e1d742770d](https://linux-hardware.org/?probe=e1d742770d) | Jan 25, 2023 |
| MSI           | MS-B1831                    | [64348a9180](https://linux-hardware.org/?probe=64348a9180) | Jan 24, 2023 |
| MSI           | H97 PC Mate                 | [d00ec3c042](https://linux-hardware.org/?probe=d00ec3c042) | Jan 24, 2023 |
| HP            | 2B34                        | [ca97840b4b](https://linux-hardware.org/?probe=ca97840b4b) | Jan 24, 2023 |
| Gigabyte      | Z690 UD DDR4                | [872cd0446b](https://linux-hardware.org/?probe=872cd0446b) | Jan 23, 2023 |
| Gigabyte      | H81M-S2H                    | [b2aecb083b](https://linux-hardware.org/?probe=b2aecb083b) | Jan 23, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [73779874bd](https://linux-hardware.org/?probe=73779874bd) | Jan 23, 2023 |
| ASRock        | 960GM/U3S3 FX               | [39f5980c8d](https://linux-hardware.org/?probe=39f5980c8d) | Jan 22, 2023 |
| ASUSTek       | PRIME X399-A                | [4687e8d062](https://linux-hardware.org/?probe=4687e8d062) | Jan 22, 2023 |
| Pegatron      | 2AD5                        | [88d7926aef](https://linux-hardware.org/?probe=88d7926aef) | Jan 22, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [05c0d355e1](https://linux-hardware.org/?probe=05c0d355e1) | Jan 22, 2023 |
| Eii           | GB01                        | [eb73cef296](https://linux-hardware.org/?probe=eb73cef296) | Jan 22, 2023 |
| Eii           | GB01                        | [0b5b540112](https://linux-hardware.org/?probe=0b5b540112) | Jan 22, 2023 |
| AZW           | U59                         | [de70883bbf](https://linux-hardware.org/?probe=de70883bbf) | Jan 20, 2023 |
| MSI           | H170 GAMING M3              | [2fe05693b8](https://linux-hardware.org/?probe=2fe05693b8) | Jan 20, 2023 |
| ECS           | APLD-MINI                   | [78e90e4760](https://linux-hardware.org/?probe=78e90e4760) | Jan 20, 2023 |
| ASRock        | H97M Pro4                   | [bb86adb1ed](https://linux-hardware.org/?probe=bb86adb1ed) | Jan 18, 2023 |
| Gigabyte      | B460M DS3H                  | [4d510de3d8](https://linux-hardware.org/?probe=4d510de3d8) | Jan 18, 2023 |
| MSI           | H510M-A PRO                 | [9f9fa2e0be](https://linux-hardware.org/?probe=9f9fa2e0be) | Jan 18, 2023 |
| ASUSTek       | PRIME B450M-K II            | [7f1cfd2c02](https://linux-hardware.org/?probe=7f1cfd2c02) | Jan 18, 2023 |
| Gigabyte      | MZBSWMP-00                  | [8f292282cb](https://linux-hardware.org/?probe=8f292282cb) | Jan 18, 2023 |
| MSI           | B560M-A PRO                 | [8b665c7b84](https://linux-hardware.org/?probe=8b665c7b84) | Jan 18, 2023 |
| ASRock        | H110M-HDV R3.0              | [70c0fea989](https://linux-hardware.org/?probe=70c0fea989) | Jan 18, 2023 |
| Gigabyte      | Z370 HD3-CF                 | [273e93cce5](https://linux-hardware.org/?probe=273e93cce5) | Jan 18, 2023 |
| Eii           | GB01                        | [35c7a7739d](https://linux-hardware.org/?probe=35c7a7739d) | Jan 18, 2023 |
| ASUSTek       | PRIME B450M-K II            | [e44a974b71](https://linux-hardware.org/?probe=e44a974b71) | Jan 17, 2023 |
| ASUSTek       | PRIME B450M-K II            | [04e8f0fb25](https://linux-hardware.org/?probe=04e8f0fb25) | Jan 17, 2023 |
| HP            | 3047h                       | [ad1e495439](https://linux-hardware.org/?probe=ad1e495439) | Jan 17, 2023 |
| MSI           | H510M-A PRO                 | [7d05783196](https://linux-hardware.org/?probe=7d05783196) | Jan 17, 2023 |
| ASUSTek       | M4N68T-M-V2                 | [53b9512a96](https://linux-hardware.org/?probe=53b9512a96) | Jan 17, 2023 |
| Gigabyte      | H410M S2H V3                | [0e4dd4c424](https://linux-hardware.org/?probe=0e4dd4c424) | Jan 17, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [92f9f48219](https://linux-hardware.org/?probe=92f9f48219) | Jan 16, 2023 |
| MSI           | MS-B1711                    | [730b1e7f90](https://linux-hardware.org/?probe=730b1e7f90) | Jan 15, 2023 |
| Gigabyte      | EP43-DS3L                   | [b6b45a8594](https://linux-hardware.org/?probe=b6b45a8594) | Jan 15, 2023 |
| Unknown       | Unknown                     | [a69d4b7b4f](https://linux-hardware.org/?probe=a69d4b7b4f) | Jan 15, 2023 |
| ASUSTek       | PRIME H310M-E               | [7732b2e5e1](https://linux-hardware.org/?probe=7732b2e5e1) | Jan 14, 2023 |
| Unknown       | Unknown                     | [9cb802849a](https://linux-hardware.org/?probe=9cb802849a) | Jan 14, 2023 |
| NEC Comput... | ECS-945G                    | [8226ffab22](https://linux-hardware.org/?probe=8226ffab22) | Jan 14, 2023 |
| Gigabyte      | P55A-UD3                    | [af87fe7cb0](https://linux-hardware.org/?probe=af87fe7cb0) | Jan 14, 2023 |
| Gigabyte      | B85M-D3H                    | [c54bd7b409](https://linux-hardware.org/?probe=c54bd7b409) | Jan 14, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [4f439c171e](https://linux-hardware.org/?probe=4f439c171e) | Jan 14, 2023 |
| HP            | 8433 11                     | [bc44066299](https://linux-hardware.org/?probe=bc44066299) | Jan 13, 2023 |
| HP            | 212A                        | [92f32467ec](https://linux-hardware.org/?probe=92f32467ec) | Jan 13, 2023 |
| Biostar       | B250MHC                     | [100bfd62e6](https://linux-hardware.org/?probe=100bfd62e6) | Jan 13, 2023 |
| Unknown       | Unknown                     | [0402d5609b](https://linux-hardware.org/?probe=0402d5609b) | Jan 13, 2023 |
| Unknown       | Unknown                     | [287fab2142](https://linux-hardware.org/?probe=287fab2142) | Jan 13, 2023 |
| Gigabyte      | H110M-S2H-CF                | [bd4173beb3](https://linux-hardware.org/?probe=bd4173beb3) | Jan 12, 2023 |
| Lenovo        | 3102 SDK0K17763 WIN 1801... | [a3ce2fe598](https://linux-hardware.org/?probe=a3ce2fe598) | Jan 12, 2023 |
| Dell          | 0FM586                      | [529bc38dd7](https://linux-hardware.org/?probe=529bc38dd7) | Jan 12, 2023 |
| ASRock        | X570 Steel Legend           | [600094ae29](https://linux-hardware.org/?probe=600094ae29) | Jan 12, 2023 |
| ASRock        | H170M Pro4                  | [15648a0bb0](https://linux-hardware.org/?probe=15648a0bb0) | Jan 12, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | [64d4a8c163](https://linux-hardware.org/?probe=64d4a8c163) | Jan 11, 2023 |
| Gigabyte      | X79-UP4                     | [89397e1c47](https://linux-hardware.org/?probe=89397e1c47) | Jan 10, 2023 |
| MSI           | PRO A320M-B                 | [3ffa3cf6f0](https://linux-hardware.org/?probe=3ffa3cf6f0) | Jan 10, 2023 |
| Gigabyte      | B85M-DS3H-A                 | [60f83cacd0](https://linux-hardware.org/?probe=60f83cacd0) | Jan 10, 2023 |
| MSI           | MS-B0A21                    | [1905ffef34](https://linux-hardware.org/?probe=1905ffef34) | Jan 09, 2023 |
| MSI           | B450M MORTAR MAX            | [3698ce3c60](https://linux-hardware.org/?probe=3698ce3c60) | Jan 09, 2023 |
| ASUSTek       | PRIME X570-P                | [95c21fc90e](https://linux-hardware.org/?probe=95c21fc90e) | Jan 09, 2023 |
| Pyramid       | CPYSKI0002 A                | [0b20d79be6](https://linux-hardware.org/?probe=0b20d79be6) | Jan 09, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | [10efec9ea3](https://linux-hardware.org/?probe=10efec9ea3) | Jan 09, 2023 |
| Gigabyte      | B365M DS3H                  | [0e302b3507](https://linux-hardware.org/?probe=0e302b3507) | Jan 08, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [0f0b86d738](https://linux-hardware.org/?probe=0f0b86d738) | Jan 07, 2023 |
| ASRock        | H110M-HDV                   | [deff7fc898](https://linux-hardware.org/?probe=deff7fc898) | Jan 07, 2023 |
| Gigabyte      | B450M DS3H V2               | [ef473bb212](https://linux-hardware.org/?probe=ef473bb212) | Jan 07, 2023 |
| Gigabyte      | B450M DS3H-CF               | [28ed8a48bd](https://linux-hardware.org/?probe=28ed8a48bd) | Jan 06, 2023 |
| Intel         | DH55TC AAE70932-303         | [7831fb0431](https://linux-hardware.org/?probe=7831fb0431) | Jan 06, 2023 |
| Gigabyte      | B450M DS3H-CF               | [4947d17a2b](https://linux-hardware.org/?probe=4947d17a2b) | Jan 06, 2023 |
| ASUSTek       | P5SD2-VM                    | [46c8437a45](https://linux-hardware.org/?probe=46c8437a45) | Jan 05, 2023 |
| ASUSTek       | M5A97 PRO                   | [7921dc0197](https://linux-hardware.org/?probe=7921dc0197) | Jan 05, 2023 |
| Dell          | 0FM586                      | [7e181126bc](https://linux-hardware.org/?probe=7e181126bc) | Jan 03, 2023 |
| Dell          | 0FM586                      | [fff469554f](https://linux-hardware.org/?probe=fff469554f) | Jan 03, 2023 |
| Gigabyte      | B450M DS3H-CF               | [b557b201c4](https://linux-hardware.org/?probe=b557b201c4) | Jan 03, 2023 |
| Gigabyte      | B550M DS3H                  | [509cc939cc](https://linux-hardware.org/?probe=509cc939cc) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | [b0e7bc419b](https://linux-hardware.org/?probe=b0e7bc419b) | Jan 01, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [c4eccac7c7](https://linux-hardware.org/?probe=c4eccac7c7) | Dec 31, 2022 |
| MSI           | Boston                      | [a5fd252dc2](https://linux-hardware.org/?probe=a5fd252dc2) | Dec 30, 2022 |
| Gigabyte      | Z390 UD                     | [70dc568eae](https://linux-hardware.org/?probe=70dc568eae) | Dec 30, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [328cfe3747](https://linux-hardware.org/?probe=328cfe3747) | Dec 28, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [305018336b](https://linux-hardware.org/?probe=305018336b) | Dec 26, 2022 |
| ASUSTek       | M5A78L-M LX3                | [aef3959b18](https://linux-hardware.org/?probe=aef3959b18) | Dec 26, 2022 |
| ASUSTek       | SABERTOOTH 990FX            | [d759e5fe02](https://linux-hardware.org/?probe=d759e5fe02) | Dec 25, 2022 |
| MSI           | MS-B1421                    | [58968767bd](https://linux-hardware.org/?probe=58968767bd) | Dec 24, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [ba498df129](https://linux-hardware.org/?probe=ba498df129) | Dec 23, 2022 |
| MSI           | 2A9C                        | [031afb1b20](https://linux-hardware.org/?probe=031afb1b20) | Dec 22, 2022 |
| Gigabyte      | B85M-DS3H-A                 | [d2c931919d](https://linux-hardware.org/?probe=d2c931919d) | Dec 20, 2022 |
| MSI           | Z370 PC PRO                 | [e048dd7a4e](https://linux-hardware.org/?probe=e048dd7a4e) | Dec 20, 2022 |
| HP            | 8597                        | [5a7ae7c6d7](https://linux-hardware.org/?probe=5a7ae7c6d7) | Dec 19, 2022 |
| Intel         | D34010WYK H14771-304        | [c47ff5ba34](https://linux-hardware.org/?probe=c47ff5ba34) | Dec 19, 2022 |
| Intel         | DH55TC AAE70932-303         | [631f80f725](https://linux-hardware.org/?probe=631f80f725) | Dec 18, 2022 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | [0886e650a3](https://linux-hardware.org/?probe=0886e650a3) | Dec 18, 2022 |
| Gigabyte      | Z390 UD                     | [3af8ddb8cc](https://linux-hardware.org/?probe=3af8ddb8cc) | Dec 17, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [83c2de0b09](https://linux-hardware.org/?probe=83c2de0b09) | Dec 15, 2022 |
| Dell          | 0KJCC5 A00                  | [7d1ece638c](https://linux-hardware.org/?probe=7d1ece638c) | Dec 14, 2022 |
| Gigabyte      | B75-D3V                     | [f46b869c82](https://linux-hardware.org/?probe=f46b869c82) | Dec 14, 2022 |
| Pro-B         | INSYS                       | [40650eefcc](https://linux-hardware.org/?probe=40650eefcc) | Dec 14, 2022 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [8fd3c60681](https://linux-hardware.org/?probe=8fd3c60681) | Dec 13, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [9d665864a0](https://linux-hardware.org/?probe=9d665864a0) | Dec 13, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [0af09d12d5](https://linux-hardware.org/?probe=0af09d12d5) | Dec 13, 2022 |
| Intel         | Eaglelake Fab D             | [ed5c44a200](https://linux-hardware.org/?probe=ed5c44a200) | Dec 13, 2022 |
| Gigabyte      | Z370M DS3H-CF               | [238bda76a3](https://linux-hardware.org/?probe=238bda76a3) | Dec 13, 2022 |
| ASUSTek       | STRIX H270F GAMING          | [3b9b8bb589](https://linux-hardware.org/?probe=3b9b8bb589) | Dec 12, 2022 |
| Dell          | 0P67HD A00                  | [67f13377be](https://linux-hardware.org/?probe=67f13377be) | Dec 12, 2022 |
| Gigabyte      | Z97-HD3                     | [7870cee549](https://linux-hardware.org/?probe=7870cee549) | Dec 12, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [deab1a46db](https://linux-hardware.org/?probe=deab1a46db) | Dec 10, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [560e61c57f](https://linux-hardware.org/?probe=560e61c57f) | Dec 10, 2022 |
| MSI           | PRO Z690-A                  | [3e5339eeae](https://linux-hardware.org/?probe=3e5339eeae) | Dec 10, 2022 |
| Gigabyte      | B550 AORUS ELITE            | [b80c17a638](https://linux-hardware.org/?probe=b80c17a638) | Dec 09, 2022 |
| Gigabyte      | B450 AORUS M                | [bb3d3b636f](https://linux-hardware.org/?probe=bb3d3b636f) | Dec 09, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [527789fc7d](https://linux-hardware.org/?probe=527789fc7d) | Dec 08, 2022 |
| MSI           | B450M PRO-M2                | [4be2d528de](https://linux-hardware.org/?probe=4be2d528de) | Dec 06, 2022 |
| MSI           | B450M PRO-M2                | [787a504fd5](https://linux-hardware.org/?probe=787a504fd5) | Dec 06, 2022 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | [689479ce87](https://linux-hardware.org/?probe=689479ce87) | Dec 06, 2022 |
| Gigabyte      | H510M S2H V2                | [b0b53bc408](https://linux-hardware.org/?probe=b0b53bc408) | Dec 05, 2022 |
| Gigabyte      | GA-880GA-UD3H               | [0a028304a1](https://linux-hardware.org/?probe=0a028304a1) | Dec 05, 2022 |
| MSI           | A320M-A PRO                 | [1b37803020](https://linux-hardware.org/?probe=1b37803020) | Dec 04, 2022 |
| ASUSTek       | M4A785TD-V EVO              | [88e60fc0ba](https://linux-hardware.org/?probe=88e60fc0ba) | Dec 04, 2022 |
| ASRock        | B75 Pro3-M                  | [db7e5686f3](https://linux-hardware.org/?probe=db7e5686f3) | Dec 03, 2022 |
| HP            | 2AE2                        | [549eacfc3d](https://linux-hardware.org/?probe=549eacfc3d) | Dec 03, 2022 |
| Medion        | D3F3-EM2                    | [e46ba957f0](https://linux-hardware.org/?probe=e46ba957f0) | Dec 02, 2022 |
| HP            | 8648                        | [79673ee467](https://linux-hardware.org/?probe=79673ee467) | Dec 02, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [85eab170d2](https://linux-hardware.org/?probe=85eab170d2) | Dec 02, 2022 |
| MSI           | B450I GAMING PLUS AC        | [9b1ef89e7e](https://linux-hardware.org/?probe=9b1ef89e7e) | Dec 02, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [0f27e558f3](https://linux-hardware.org/?probe=0f27e558f3) | Dec 01, 2022 |
| Medion        | D3F3-EM                     | [ae428a6a6a](https://linux-hardware.org/?probe=ae428a6a6a) | Nov 29, 2022 |
| MSI           | B560M PRO-VDH               | [cee0622b1f](https://linux-hardware.org/?probe=cee0622b1f) | Nov 29, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [a95de3b373](https://linux-hardware.org/?probe=a95de3b373) | Nov 29, 2022 |
| ASUSTek       | PRIME H410M-R               | [b680eec959](https://linux-hardware.org/?probe=b680eec959) | Nov 26, 2022 |
| Foxconn       | 2ABF                        | [d95233ff31](https://linux-hardware.org/?probe=d95233ff31) | Nov 26, 2022 |
| Gigabyte      | 970A-DS3P FX                | [4ded1fb943](https://linux-hardware.org/?probe=4ded1fb943) | Nov 26, 2022 |
| MSI           | Z170A GAMING M3             | [982d7f7d0b](https://linux-hardware.org/?probe=982d7f7d0b) | Nov 25, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [fc5f72597d](https://linux-hardware.org/?probe=fc5f72597d) | Nov 25, 2022 |
| ASUSTek       | PRIME Z270-K                | [e311874280](https://linux-hardware.org/?probe=e311874280) | Nov 24, 2022 |
| Lenovo        | 312A NOK                    | [94cdaff2c9](https://linux-hardware.org/?probe=94cdaff2c9) | Nov 24, 2022 |
| ASRock        | B75 Pro3                    | [e359d0bd70](https://linux-hardware.org/?probe=e359d0bd70) | Nov 24, 2022 |
| Lenovo        | 30BE SDK0J40697 WIN 3305... | [1deb081598](https://linux-hardware.org/?probe=1deb081598) | Nov 23, 2022 |
| ASUSTek       | PRIME A320M-E               | [5f50e13ad0](https://linux-hardware.org/?probe=5f50e13ad0) | Nov 21, 2022 |
| ASUSTek       | PRIME A320M-E               | [81c02af38c](https://linux-hardware.org/?probe=81c02af38c) | Nov 21, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [934f31fcac](https://linux-hardware.org/?probe=934f31fcac) | Nov 21, 2022 |
| Gigabyte      | B450M DS3H-CF               | [8de96e0012](https://linux-hardware.org/?probe=8de96e0012) | Nov 20, 2022 |
| Gigabyte      | H97M-D3H                    | [4e0102dff6](https://linux-hardware.org/?probe=4e0102dff6) | Nov 20, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [71b3224c4d](https://linux-hardware.org/?probe=71b3224c4d) | Nov 19, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [9d276a36d8](https://linux-hardware.org/?probe=9d276a36d8) | Nov 19, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [362cf69f1f](https://linux-hardware.org/?probe=362cf69f1f) | Nov 19, 2022 |
| Gigabyte      | B550M DS3H                  | [469ead98f8](https://linux-hardware.org/?probe=469ead98f8) | Nov 17, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [567b81705d](https://linux-hardware.org/?probe=567b81705d) | Nov 15, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [389d8cf0e0](https://linux-hardware.org/?probe=389d8cf0e0) | Nov 15, 2022 |
| HP            | 0AA8h                       | [0f88d64eeb](https://linux-hardware.org/?probe=0f88d64eeb) | Nov 14, 2022 |
| HP            | 1495                        | [f588871a3a](https://linux-hardware.org/?probe=f588871a3a) | Nov 14, 2022 |
| HP            | 1495                        | [5086b0aa3e](https://linux-hardware.org/?probe=5086b0aa3e) | Nov 14, 2022 |
| Gigabyte      | B550M DS3H                  | [c16c0f7d8f](https://linux-hardware.org/?probe=c16c0f7d8f) | Nov 13, 2022 |
| ASUSTek       | M4N72-E                     | [092c39d271](https://linux-hardware.org/?probe=092c39d271) | Nov 13, 2022 |
| Gigabyte      | B550M S2H                   | [ea1d9a2fa4](https://linux-hardware.org/?probe=ea1d9a2fa4) | Nov 11, 2022 |
| Unknown       | Unknown                     | [e0b38a3d54](https://linux-hardware.org/?probe=e0b38a3d54) | Nov 11, 2022 |
| Gigabyte      | H110M-S2V-CF                | [1117e533c3](https://linux-hardware.org/?probe=1117e533c3) | Nov 11, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | [4b5ec389d9](https://linux-hardware.org/?probe=4b5ec389d9) | Nov 09, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | [292caf8ccf](https://linux-hardware.org/?probe=292caf8ccf) | Nov 09, 2022 |
| ASUSTek       | A88XM-PLUS                  | [e6eee311ea](https://linux-hardware.org/?probe=e6eee311ea) | Nov 08, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | [0aad7f7578](https://linux-hardware.org/?probe=0aad7f7578) | Nov 07, 2022 |
| ASUSTek       | X99-DELUXE                  | [ab4089c760](https://linux-hardware.org/?probe=ab4089c760) | Nov 04, 2022 |
| HP            | 8459                        | [378537c13c](https://linux-hardware.org/?probe=378537c13c) | Nov 04, 2022 |
| HP            | 1998                        | [ba48cbeebe](https://linux-hardware.org/?probe=ba48cbeebe) | Nov 04, 2022 |
| ASUSTek       | M3A78 PRO                   | [93b2e9aea5](https://linux-hardware.org/?probe=93b2e9aea5) | Nov 04, 2022 |
| ASUSTek       | M3A78 PRO                   | [5466838c04](https://linux-hardware.org/?probe=5466838c04) | Nov 03, 2022 |
| Dell          | 0X9M3X A04                  | [3bec3377a8](https://linux-hardware.org/?probe=3bec3377a8) | Nov 03, 2022 |
| Dell          | 0D24M8 A01                  | [347b32510b](https://linux-hardware.org/?probe=347b32510b) | Nov 03, 2022 |
| Gigabyte      | Z270-HD3P-CF                | [8b8ec08876](https://linux-hardware.org/?probe=8b8ec08876) | Nov 02, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | [f0db98f6bb](https://linux-hardware.org/?probe=f0db98f6bb) | Nov 01, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | [fc832e8881](https://linux-hardware.org/?probe=fc832e8881) | Nov 01, 2022 |
| Gigabyte      | H410M S2H V3                | [202065a62d](https://linux-hardware.org/?probe=202065a62d) | Oct 30, 2022 |
| ASUSTek       | PRIME B560M-K               | [416db8870a](https://linux-hardware.org/?probe=416db8870a) | Oct 30, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [7d6c392e74](https://linux-hardware.org/?probe=7d6c392e74) | Oct 29, 2022 |
| MSI           | B560M PRO-VDH               | [ab324c3cdd](https://linux-hardware.org/?probe=ab324c3cdd) | Oct 29, 2022 |
| Gigabyte      | B550M DS3H                  | [4234f1fe02](https://linux-hardware.org/?probe=4234f1fe02) | Oct 29, 2022 |
| Gigabyte      | B550M DS3H                  | [6ab822b64c](https://linux-hardware.org/?probe=6ab822b64c) | Oct 29, 2022 |
| MSI           | P45 Platinum                | [5507d45c35](https://linux-hardware.org/?probe=5507d45c35) | Oct 29, 2022 |
| Dell          | 0D24M8 A01                  | [55aa58c274](https://linux-hardware.org/?probe=55aa58c274) | Oct 29, 2022 |
| ASRock        | H81M-ITX                    | [56f93814ea](https://linux-hardware.org/?probe=56f93814ea) | Oct 28, 2022 |
| ASUSTek       | Z170I PRO GAMING            | [2ae55c9228](https://linux-hardware.org/?probe=2ae55c9228) | Oct 27, 2022 |
| ASUSTek       | PRIME X570-PRO              | [ea04a21af7](https://linux-hardware.org/?probe=ea04a21af7) | Oct 27, 2022 |
| Dell          | 09KPNV A00                  | [c25493f420](https://linux-hardware.org/?probe=c25493f420) | Oct 27, 2022 |
| Intel         | H410M-E                     | [854c3ec5b1](https://linux-hardware.org/?probe=854c3ec5b1) | Oct 27, 2022 |
| ASUSTek       | PRIME B660-PLUS D4          | [5b6d2d2922](https://linux-hardware.org/?probe=5b6d2d2922) | Oct 27, 2022 |
| Gigabyte      | EP43-DS3L                   | [f9e114a7e9](https://linux-hardware.org/?probe=f9e114a7e9) | Oct 26, 2022 |
| Intel         | H410M-E                     | [69d7d07e13](https://linux-hardware.org/?probe=69d7d07e13) | Oct 26, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [696c30d8c3](https://linux-hardware.org/?probe=696c30d8c3) | Oct 25, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [c05a08e1af](https://linux-hardware.org/?probe=c05a08e1af) | Oct 25, 2022 |
| Unknown       | SKYBAY                      | [63f22191e8](https://linux-hardware.org/?probe=63f22191e8) | Oct 24, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [936e43f0bc](https://linux-hardware.org/?probe=936e43f0bc) | Oct 24, 2022 |
| MSI           | B560M PRO-VDH               | [0a2cbff604](https://linux-hardware.org/?probe=0a2cbff604) | Oct 24, 2022 |
| ASUSTek       | PRIME X570-P                | [5558f9e3f7](https://linux-hardware.org/?probe=5558f9e3f7) | Oct 23, 2022 |
| Gigabyte      | Z97-HD3                     | [f79eb0cbb0](https://linux-hardware.org/?probe=f79eb0cbb0) | Oct 23, 2022 |
| Gigabyte      | B560M H                     | [cce3979970](https://linux-hardware.org/?probe=cce3979970) | Oct 22, 2022 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [6105b0d3a9](https://linux-hardware.org/?probe=6105b0d3a9) | Oct 22, 2022 |
| Gigabyte      | B365M DS3H                  | [d5f16dde87](https://linux-hardware.org/?probe=d5f16dde87) | Oct 22, 2022 |
| HP            | 8459                        | [c2ebcf9e20](https://linux-hardware.org/?probe=c2ebcf9e20) | Oct 21, 2022 |
| HP            | 8459                        | [d8ec2e7ee9](https://linux-hardware.org/?probe=d8ec2e7ee9) | Oct 20, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | [18c1a4a04d](https://linux-hardware.org/?probe=18c1a4a04d) | Oct 19, 2022 |
| MSI           | H81M-E33                    | [ff6334ee8f](https://linux-hardware.org/?probe=ff6334ee8f) | Oct 19, 2022 |
| ASUSTek       | A88XM-A                     | [9622704d8f](https://linux-hardware.org/?probe=9622704d8f) | Oct 18, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Spain/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 296      | 11.81%  |
| Ubuntu 18.04                 | 230      | 9.18%   |
| Ubuntu 22.04                 | 126      | 5.03%   |
| Debian 11                    | 101      | 4.03%   |
| OpenMandriva 4.2             | 88       | 3.51%   |
| OpenMandriva 4.3             | 54       | 2.15%   |
| Arch Rolling                 | 49       | 1.96%   |
| Manjaro                      | 44       | 1.76%   |
| KDE neon 20.04               | 42       | 1.68%   |
| Debian 10                    | 42       | 1.68%   |
| OpenMandriva 23.01           | 41       | 1.64%   |
| Linux Mint 20.3              | 35       | 1.4%    |
| Zorin 16                     | 33       | 1.32%   |
| Debian 12                    | 32       | 1.28%   |
| Linux Mint 19.3              | 31       | 1.24%   |
| Linux Mint 21.1              | 30       | 1.2%    |
| Fedora 38                    | 29       | 1.16%   |
| Ubuntu 19.04                 | 27       | 1.08%   |
| OpenMandriva 23.08           | 27       | 1.08%   |
| Linux Mint 20.1              | 27       | 1.08%   |
| OpenMandriva 23.03           | 24       | 0.96%   |
| Arch                         | 24       | 0.96%   |
| Ubuntu 19.10                 | 23       | 0.92%   |
| openSUSE Tumbleweed-XXXXXXXX | 23       | 0.92%   |
| Linux Mint 21.2              | 23       | 0.92%   |
| ArcoLinux Rolling            | 22       | 0.88%   |
| Ubuntu 20.10                 | 21       | 0.84%   |
| ROSA R10                     | 21       | 0.84%   |
| Linux Mint 20                | 20       | 0.8%    |
| Xubuntu 20.04                | 19       | 0.76%   |
| Xubuntu 18.04                | 19       | 0.76%   |
| Fedora 37                    | 19       | 0.76%   |
| Fedora 36                    | 19       | 0.76%   |
| KDE neon 22.04               | 18       | 0.72%   |
| Fedora 35                    | 18       | 0.72%   |
| Ubuntu 21.04                 | 17       | 0.68%   |
| Linux Mint 20.2              | 17       | 0.68%   |
| Pop!_OS 22.04                | 16       | 0.64%   |
| Pop!_OS 20.04                | 15       | 0.6%    |
| Kubuntu 20.04                | 15       | 0.6%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Ubuntu           | 765      | 32.85%  |
| OpenMandriva     | 239      | 10.26%  |
| Linux Mint       | 211      | 9.06%   |
| Debian           | 196      | 8.42%   |
| Fedora           | 125      | 5.37%   |
| Manjaro          | 89       | 3.82%   |
| Arch             | 72       | 3.09%   |
| KDE neon         | 66       | 2.83%   |
| Zorin            | 51       | 2.19%   |
| ROSA             | 49       | 2.1%    |
| Kubuntu          | 48       | 2.06%   |
| Xubuntu          | 46       | 1.98%   |
| Pop!_OS          | 44       | 1.89%   |
| openSUSE         | 32       | 1.37%   |
| Gentoo           | 29       | 1.25%   |
| ArcoLinux        | 28       | 1.2%    |
| Ubuntu MATE      | 22       | 0.94%   |
| Elementary       | 20       | 0.86%   |
| Endless          | 16       | 0.69%   |
| Lubuntu          | 15       | 0.64%   |
| Ubuntu Unity     | 14       | 0.6%    |
| MX               | 12       | 0.52%   |
| BlackPanther     | 12       | 0.52%   |
| Nobara           | 11       | 0.47%   |
| Kali             | 10       | 0.43%   |
| EndeavourOS      | 10       | 0.43%   |
| Garuda Linux     | 9        | 0.39%   |
| LMDE             | 8        | 0.34%   |
| Clear Linux      | 7        | 0.3%    |
| Ubuntu Budgie    | 6        | 0.26%   |
| Parrot           | 6        | 0.26%   |
| Reborn OS        | 5        | 0.21%   |
| org.kde.Platform | 4        | 0.17%   |
| Xero             | 3        | 0.13%   |
| Ubuntu Studio    | 3        | 0.13%   |
| Slackware        | 3        | 0.13%   |
| RHEL             | 3        | 0.13%   |
| SteamOS          | 2        | 0.09%   |
| Solus            | 2        | 0.09%   |
| LFS              | 2        | 0.09%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Desktops | Percent |
|---------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002        | 86       | 3.12%   |
| 5.16.7-desktop-1omv4003         | 53       | 1.92%   |
| 6.1.1-desktop-1omv2290          | 40       | 1.45%   |
| 5.4.0-42-generic                | 40       | 1.45%   |
| 5.15.0-56-generic               | 25       | 0.91%   |
| 5.4.0-58-generic                | 24       | 0.87%   |
| 6.2.6-desktop-1omv2390          | 23       | 0.83%   |
| 6.4.11-desktop-1omv2390         | 22       | 0.8%    |
| 5.4.0-52-generic                | 22       | 0.8%    |
| 5.4.0-48-generic                | 19       | 0.69%   |
| 5.10.0-8-amd64                  | 19       | 0.69%   |
| 5.4.0-54-generic                | 17       | 0.62%   |
| 5.4.0-29-generic                | 17       | 0.62%   |
| 5.4.0-26-generic                | 17       | 0.62%   |
| 5.13.0-30-generic               | 17       | 0.62%   |
| 5.10.0-21-amd64                 | 16       | 0.58%   |
| 5.3.0-40-generic                | 15       | 0.54%   |
| 5.15.0-58-generic               | 15       | 0.54%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 15       | 0.54%   |
| 5.4.0-47-generic                | 14       | 0.51%   |
| 5.15.0-60-generic               | 14       | 0.51%   |
| 4.15.0-72-generic               | 14       | 0.51%   |
| 5.4.0-37-generic                | 13       | 0.47%   |
| 5.4.0-28-generic                | 13       | 0.47%   |
| 5.19.0-38-generic               | 13       | 0.47%   |
| 5.11.0-43-generic               | 13       | 0.47%   |
| 5.11.0-27-generic               | 13       | 0.47%   |
| 6.2.0-36-generic                | 12       | 0.43%   |
| 5.0.0-37-generic                | 12       | 0.43%   |
| 6.6.2-desktop-1omv2390          | 11       | 0.4%    |
| 6.1.0-13-amd64                  | 11       | 0.4%    |
| 5.4.0-72-generic                | 11       | 0.4%    |
| 5.19.0-35-generic               | 11       | 0.4%    |
| 5.15.0-91-generic               | 11       | 0.4%    |
| 5.15.0-52-generic               | 11       | 0.4%    |
| 5.15.0-50-generic               | 11       | 0.4%    |
| 5.13.0-39-generic               | 11       | 0.4%    |
| 5.11.0-37-generic               | 11       | 0.4%    |
| 5.0.0-23-generic                | 11       | 0.4%    |
| 4.15.0-47-generic               | 11       | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 371      | 14.37%  |
| 4.15.0  | 198      | 7.67%   |
| 5.15.0  | 190      | 7.36%   |
| 5.10.0  | 115      | 4.46%   |
| 5.8.0   | 93       | 3.6%    |
| 5.3.0   | 90       | 3.49%   |
| 5.13.0  | 88       | 3.41%   |
| 5.11.0  | 88       | 3.41%   |
| 5.10.14 | 87       | 3.37%   |
| 5.0.0   | 74       | 2.87%   |
| 5.19.0  | 69       | 2.67%   |
| 6.2.0   | 57       | 2.21%   |
| 5.16.7  | 53       | 2.05%   |
| 6.1.1   | 41       | 1.59%   |
| 4.19.0  | 41       | 1.59%   |
| 6.1.0   | 39       | 1.51%   |
| 4.18.0  | 38       | 1.47%   |
| 6.5.0   | 35       | 1.36%   |
| 6.2.6   | 27       | 1.05%   |
| 6.4.11  | 24       | 0.93%   |
| 4.9.60  | 18       | 0.7%    |
| 6.4.8   | 13       | 0.5%    |
| 6.6.2   | 12       | 0.46%   |
| 4.18.16 | 9        | 0.35%   |
| 6.3.5   | 8        | 0.31%   |
| 6.0.0   | 8        | 0.31%   |
| 6.5.6   | 7        | 0.27%   |
| 5.18.0  | 7        | 0.27%   |
| 5.17.5  | 7        | 0.27%   |
| 5.15.6  | 7        | 0.27%   |
| 4.4.0   | 7        | 0.27%   |
| 6.5.5   | 6        | 0.23%   |
| 6.3.7   | 6        | 0.23%   |
| 6.0.8   | 6        | 0.23%   |
| 5.9.0   | 6        | 0.23%   |
| 5.8.11  | 6        | 0.23%   |
| 5.7.0   | 6        | 0.23%   |
| 5.6.0   | 6        | 0.23%   |
| 5.14.0  | 6        | 0.23%   |
| 5.10.74 | 6        | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 398      | 15.59%  |
| 5.15    | 238      | 9.32%   |
| 5.10    | 234      | 9.17%   |
| 4.15    | 198      | 7.76%   |
| 5.8     | 122      | 4.78%   |
| 6.1     | 117      | 4.58%   |
| 5.11    | 113      | 4.43%   |
| 6.2     | 105      | 4.11%   |
| 5.13    | 104      | 4.07%   |
| 5.3     | 103      | 4.03%   |
| 5.19    | 93       | 3.64%   |
| 5.16    | 77       | 3.02%   |
| 5.0     | 76       | 2.98%   |
| 6.5     | 67       | 2.62%   |
| 6.4     | 61       | 2.39%   |
| 4.18    | 48       | 1.88%   |
| 4.19    | 46       | 1.8%    |
| 6.6     | 40       | 1.57%   |
| 6.0     | 39       | 1.53%   |
| 4.9     | 36       | 1.41%   |
| 6.3     | 33       | 1.29%   |
| 5.14    | 32       | 1.25%   |
| 5.18    | 26       | 1.02%   |
| 5.6     | 24       | 0.94%   |
| 5.7     | 19       | 0.74%   |
| 5.12    | 19       | 0.74%   |
| 5.9     | 18       | 0.71%   |
| 5.17    | 15       | 0.59%   |
| 5.5     | 11       | 0.43%   |
| 4.4     | 9        | 0.35%   |
| 4.1     | 5        | 0.2%    |
| 5.2     | 4        | 0.16%   |
| 5.1     | 4        | 0.16%   |
| 6.7     | 3        | 0.12%   |
| 4.17    | 3        | 0.12%   |
| 4.14    | 3        | 0.12%   |
| 4.8     | 2        | 0.08%   |
| 3.16    | 2        | 0.08%   |
| 3.10    | 2        | 0.08%   |
| 4.20    | 1        | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 2177     | 97.62%  |
| i686   | 53       | 2.38%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 945      | 40.04%  |
| KDE5            | 482      | 20.42%  |
| Unknown         | 291      | 12.33%  |
| X-Cinnamon      | 168      | 7.12%   |
| XFCE            | 157      | 6.65%   |
| MATE            | 72       | 3.05%   |
| KDE             | 72       | 3.05%   |
| LXQt            | 31       | 1.31%   |
| KDE4            | 21       | 0.89%   |
| Pantheon        | 19       | 0.81%   |
| Cinnamon        | 16       | 0.68%   |
| Unity           | 14       | 0.59%   |
| Budgie          | 14       | 0.59%   |
| i3              | 13       | 0.55%   |
| Deepin          | 11       | 0.47%   |
| LXDE            | 6        | 0.25%   |
| openbox         | 4        | 0.17%   |
| qtile           | 3        | 0.13%   |
| GNOME Flashback | 3        | 0.13%   |
| xmonad          | 2        | 0.08%   |
| ICEWM           | 2        | 0.08%   |
| Hyprland        | 2        | 0.08%   |
| GNOME Classic   | 2        | 0.08%   |
| bspwm           | 2        | 0.08%   |
| Trinity         | 1        | 0.04%   |
| sway            | 1        | 0.04%   |
| LeftWM          | 1        | 0.04%   |
| KDE6            | 1        | 0.04%   |
| i3-with-shmlog  | 1        | 0.04%   |
| fvwm            | 1        | 0.04%   |
| DWM             | 1        | 0.04%   |
| chadwm          | 1        | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 1794     | 77.23%  |
| Wayland | 335      | 14.42%  |
| Unknown | 139      | 5.98%   |
| Tty     | 55       | 2.37%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1191     | 51.25%  |
| SDDM    | 434      | 18.67%  |
| GDM3    | 234      | 10.07%  |
| GDM     | 193      | 8.3%    |
| LightDM | 176      | 7.57%   |
| TDM     | 55       | 2.37%   |
| KDM     | 21       | 0.9%    |
| LXDM    | 8        | 0.34%   |
| XDM     | 6        | 0.26%   |
| SLiM    | 2        | 0.09%   |
| Ly      | 2        | 0.09%   |
| WDM     | 1        | 0.04%   |
| NODM    | 1        | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang             | Desktops | Percent |
|------------------|----------|---------|
| es_ES            | 1415     | 61.1%   |
| en_US            | 350      | 15.11%  |
| Unknown          | 279      | 12.05%  |
| ca_ES            | 69       | 2.98%   |
| en_GB            | 34       | 1.47%   |
| C                | 26       | 1.12%   |
| gl_ES            | 25       | 1.08%   |
| de_DE            | 16       | 0.69%   |
| eu_ES            | 14       | 0.6%    |
| fr_FR            | 9        | 0.39%   |
| ru_RU            | 8        | 0.35%   |
| it_IT            | 7        | 0.3%    |
| es_ES.UTF8       | 5        | 0.22%   |
| es_AR            | 5        | 0.22%   |
| ca_ES@valencia   | 5        | 0.22%   |
| ro_RO            | 4        | 0.17%   |
| pt_PT            | 4        | 0.17%   |
| en_IE            | 4        | 0.17%   |
| C.UTF8           | 4        | 0.17%   |
| pt_BR            | 3        | 0.13%   |
| es_MX            | 3        | 0.13%   |
| ca_AD            | 3        | 0.13%   |
| an_ES            | 3        | 0.13%   |
| POSIX            | 2        | 0.09%   |
| pl_PL            | 2        | 0.09%   |
| en_DK            | 2        | 0.09%   |
| bg_BG            | 2        | 0.09%   |
| spanish          | 1        | 0.04%   |
| nl_NL            | 1        | 0.04%   |
| es_GT            | 1        | 0.04%   |
| es_ES@euro       | 1        | 0.04%   |
| es_ES.utf-8      | 1        | 0.04%   |
| es_ES.ISO-8859-1 | 1        | 0.04%   |
| es_EC            | 1        | 0.04%   |
| es_DO            | 1        | 0.04%   |
| es_CL            | 1        | 0.04%   |
| eo               | 1        | 0.04%   |
| en_AU            | 1        | 0.04%   |
| de_AT            | 1        | 0.04%   |
| ca_FR            | 1        | 0.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 1369     | 59.78%  |
| EFI  | 921      | 40.22%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 1646     | 71.32%  |
| Overlay  | 225      | 9.75%   |
| Btrfs    | 189      | 8.19%   |
| Unknown  | 95       | 4.12%   |
| Tmpfs    | 66       | 2.86%   |
| Xfs      | 38       | 1.65%   |
| Ext3     | 30       | 1.3%    |
| Zfs      | 9        | 0.39%   |
| Ext2     | 6        | 0.26%   |
| Reiserfs | 4        | 0.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1256     | 54.54%  |
| GPT     | 759      | 32.96%  |
| MBR     | 288      | 12.51%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1749     | 75.88%  |
| Yes       | 556      | 24.12%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1410     | 61.71%  |
| Yes       | 875      | 38.29%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 610      | 27.37%  |
| Gigabyte Technology                  | 468      | 21%     |
| MSI                                  | 314      | 14.09%  |
| Hewlett-Packard                      | 176      | 7.9%    |
| ASRock                               | 144      | 6.46%   |
| Dell                                 | 86       | 3.86%   |
| Lenovo                               | 77       | 3.45%   |
| Acer                                 | 57       | 2.56%   |
| Intel                                | 51       | 2.29%   |
| Unknown                              | 36       | 1.62%   |
| Medion                               | 25       | 1.12%   |
| Pegatron                             | 21       | 0.94%   |
| ECS                                  | 17       | 0.76%   |
| Foxconn                              | 15       | 0.67%   |
| Packard Bell                         | 12       | 0.54%   |
| Huanan                               | 12       | 0.54%   |
| BESSTAR Tech                         | 10       | 0.45%   |
| AMI                                  | 9        | 0.4%    |
| Shuttle                              | 8        | 0.36%   |
| Fujitsu                              | 7        | 0.31%   |
| eMachines                            | 7        | 0.31%   |
| AZW                                  | 7        | 0.31%   |
| NEC Computers                        | 4        | 0.18%   |
| Biostar                              | 4        | 0.18%   |
| Supermicro                           | 3        | 0.13%   |
| Shenzhen Meigao Electronic Equipment | 3        | 0.13%   |
| Apple                                | 3        | 0.13%   |
| Wistron                              | 2        | 0.09%   |
| SLIMBOOK                             | 2        | 0.09%   |
| Minix                                | 2        | 0.09%   |
| MACHINIST                            | 2        | 0.09%   |
| Koloe                                | 2        | 0.09%   |
| IBM                                  | 2        | 0.09%   |
| Gateway                              | 2        | 0.09%   |
| Toshiba                              | 1        | 0.04%   |
| TEKNOSERVICE                         | 1        | 0.04%   |
| T-bao                                | 1        | 0.04%   |
| SYWZ                                 | 1        | 0.04%   |
| SiYW                                 | 1        | 0.04%   |
| Seco                                 | 1        | 0.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| ASUS All Series                   | 60       | 2.69%   |
| Unknown                           | 40       | 1.79%   |
| Lenovo ThinkCentre E73 10DR0033SP | 22       | 0.99%   |
| Gigabyte B450M DS3H               | 16       | 0.72%   |
| ASUS H110M-D                      | 13       | 0.58%   |
| MSI MS-7B79                       | 12       | 0.54%   |
| MSI MS-7817                       | 12       | 0.54%   |
| Gigabyte 970A-DS3P                | 12       | 0.54%   |
| ASUS P5G41T-M LX                  | 12       | 0.54%   |
| MSI MS-7C37                       | 11       | 0.49%   |
| HP Compaq Elite 8300 SFF          | 11       | 0.49%   |
| MSI MS-7C91                       | 10       | 0.45%   |
| MSI MS-7B86                       | 10       | 0.45%   |
| Gigabyte H81M-S2H                 | 10       | 0.45%   |
| Gigabyte H61M-DS2                 | 10       | 0.45%   |
| ASUS TUF Gaming X570-PLUS         | 10       | 0.45%   |
| HP EliteDesk 800 G1 SFF           | 9        | 0.4%    |
| Gigabyte H110M-S2H                | 9        | 0.4%    |
| Gigabyte B450 AORUS M             | 9        | 0.4%    |
| ASUS PRIME B450M-A                | 9        | 0.4%    |
| ASUS PRIME A320M-K                | 9        | 0.4%    |
| MSI MS-7C02                       | 8        | 0.36%   |
| MSI MS-7A38                       | 8        | 0.36%   |
| HP Compaq 8200 Elite SFF PC       | 8        | 0.36%   |
| MSI MS-7B89                       | 7        | 0.31%   |
| Gigabyte B450M S2H                | 7        | 0.31%   |
| ASUS TUF Gaming B550-PLUS         | 7        | 0.31%   |
| ASUS TUF B450-PLUS GAMING         | 7        | 0.31%   |
| ASUS P5K                          | 7        | 0.31%   |
| MSI MS-7C52                       | 6        | 0.27%   |
| MSI MS-7B49                       | 6        | 0.27%   |
| Gigabyte H61M-S2PV                | 6        | 0.27%   |
| Gigabyte H310M S2H 2.0            | 6        | 0.27%   |
| Gigabyte A320M-S2H V2             | 6        | 0.27%   |
| Dell OptiPlex 3050                | 6        | 0.27%   |
| ASUS M4A785TD-V EVO               | 6        | 0.27%   |
| AMI Intel                         | 6        | 0.27%   |
| MSI MS-7C56                       | 5        | 0.22%   |
| MSI MS-7C51                       | 5        | 0.22%   |
| MSI MS-7B84                       | 5        | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ASUS PRIME         | 102      | 4.58%   |
| HP Compaq          | 71       | 3.19%   |
| ASUS TUF           | 64       | 2.87%   |
| Lenovo ThinkCentre | 62       | 2.78%   |
| ASUS All           | 60       | 2.69%   |
| Dell OptiPlex      | 59       | 2.65%   |
| ASUS ROG           | 53       | 2.38%   |
| Acer Aspire        | 40       | 1.79%   |
| Unknown            | 40       | 1.79%   |
| HP EliteDesk       | 27       | 1.21%   |
| Gigabyte B450M     | 27       | 1.21%   |
| Gigabyte X570      | 23       | 1.03%   |
| Gigabyte B450      | 17       | 0.76%   |
| HP ProDesk         | 16       | 0.72%   |
| Dell Precision     | 16       | 0.72%   |
| Gigabyte 970A-DS3P | 13       | 0.58%   |
| ASUS H110M-D       | 13       | 0.58%   |
| MSI MS-7B79        | 12       | 0.54%   |
| MSI MS-7817        | 12       | 0.54%   |
| ASUS P5KPL-AM      | 12       | 0.54%   |
| ASUS P5G41T-M      | 12       | 0.54%   |
| MSI MS-7C37        | 11       | 0.49%   |
| Gigabyte H61M-DS2  | 11       | 0.49%   |
| ASUS P8H61-M       | 11       | 0.49%   |
| MSI MS-7C91        | 10       | 0.45%   |
| MSI MS-7B86        | 10       | 0.45%   |
| Gigabyte H81M-S2H  | 10       | 0.45%   |
| ASUS SABERTOOTH    | 10       | 0.45%   |
| ASUS M5A78L-M      | 10       | 0.45%   |
| Gigabyte Z390      | 9        | 0.4%    |
| Gigabyte H110M-S2H | 9        | 0.4%    |
| ASUS P8Z77-V       | 9        | 0.4%    |
| Acer Veriton       | 9        | 0.4%    |
| MSI MS-7C02        | 8        | 0.36%   |
| MSI MS-7A38        | 8        | 0.36%   |
| Lenovo IdeaCentre  | 8        | 0.36%   |
| Gigabyte H310M     | 8        | 0.36%   |
| Gigabyte B550M     | 8        | 0.36%   |
| Gigabyte A320M-S2H | 8        | 0.36%   |
| ASUS P5K           | 8        | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 222      | 9.96%   |
| 2012 | 194      | 8.7%    |
| 2014 | 181      | 8.12%   |
| 2013 | 181      | 8.12%   |
| 2019 | 176      | 7.9%    |
| 2020 | 155      | 6.95%   |
| 2009 | 127      | 5.7%    |
| 2011 | 117      | 5.25%   |
| 2017 | 115      | 5.16%   |
| 2010 | 115      | 5.16%   |
| 2015 | 109      | 4.89%   |
| 2021 | 108      | 4.85%   |
| 2016 | 99       | 4.44%   |
| 2008 | 94       | 4.22%   |
| 2007 | 81       | 3.63%   |
| 2022 | 59       | 2.65%   |
| 2006 | 55       | 2.47%   |
| 2023 | 23       | 1.03%   |
| 2005 | 13       | 0.58%   |
| 2004 | 2        | 0.09%   |
| 2024 | 1        | 0.04%   |
| 2002 | 1        | 0.04%   |
| 2001 | 1        | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 2229     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 2174     | 97.14%  |
| Enabled  | 64       | 2.86%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2229     | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 608      | 26.45%  |
| 8.01-16.0       | 418      | 18.18%  |
| 3.01-4.0        | 367      | 15.96%  |
| 4.01-8.0        | 360      | 15.66%  |
| 32.01-64.0      | 303      | 13.18%  |
| 1.01-2.0        | 78       | 3.39%   |
| 64.01-256.0     | 75       | 3.26%   |
| 24.01-32.0      | 47       | 2.04%   |
| 2.01-3.0        | 31       | 1.35%   |
| 0.51-1.0        | 8        | 0.35%   |
| More than 256.0 | 3        | 0.13%   |
| Unknown         | 1        | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 935      | 37.24%  |
| 2.01-3.0   | 601      | 23.93%  |
| 4.01-8.0   | 351      | 13.98%  |
| 3.01-4.0   | 314      | 12.5%   |
| 0.51-1.0   | 164      | 6.53%   |
| 8.01-16.0  | 94       | 3.74%   |
| 0.01-0.5   | 29       | 1.15%   |
| 16.01-24.0 | 12       | 0.48%   |
| 24.01-32.0 | 7        | 0.28%   |
| 32.01-64.0 | 3        | 0.12%   |
| Unknown    | 1        | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 814      | 34.3%   |
| 2      | 746      | 31.44%  |
| 3      | 406      | 17.11%  |
| 4      | 213      | 8.98%   |
| 5      | 94       | 3.96%   |
| 6      | 42       | 1.77%   |
| 0      | 16       | 0.67%   |
| 7      | 14       | 0.59%   |
| 9      | 9        | 0.38%   |
| 8      | 8        | 0.34%   |
| 10     | 5        | 0.21%   |
| 12     | 2        | 0.08%   |
| 11     | 2        | 0.08%   |
| 18     | 1        | 0.04%   |
| 13     | 1        | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1163     | 51.19%  |
| Yes       | 1109     | 48.81%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 2218     | 99.51%  |
| No        | 11       | 0.49%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1322     | 58.11%  |
| Yes       | 953      | 41.89%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1546     | 67.9%   |
| Yes       | 731      | 32.1%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Spain   | 2229     | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Desktops | Percent |
|----------------------------|----------|---------|
| Madrid                     | 340      | 13.87%  |
| Barcelona                  | 226      | 9.22%   |
| Valencia                   | 97       | 3.96%   |
| Seville                    | 77       | 3.14%   |
| Zaragoza                   | 38       | 1.55%   |
| Málaga                    | 37       | 1.51%   |
| Granada                    | 31       | 1.26%   |
| Valladolid                 | 29       | 1.18%   |
| Ourense                    | 29       | 1.18%   |
| Bilbao                     | 29       | 1.18%   |
| Las Palmas de Gran Canaria | 28       | 1.14%   |
| Córdoba                   | 25       | 1.02%   |
| Vigo                       | 23       | 0.94%   |
| Palma                      | 22       | 0.9%    |
| Santa Cruz de Tenerife     | 20       | 0.82%   |
| Sabadell                   | 20       | 0.82%   |
| Murcia                     | 19       | 0.78%   |
| Alicante                   | 18       | 0.73%   |
| Alcobendas                 | 18       | 0.73%   |
| Oviedo                     | 17       | 0.69%   |
| A Coruña                  | 16       | 0.65%   |
| Santiago de Compostela     | 15       | 0.61%   |
| Donostia / San Sebastian   | 15       | 0.61%   |
| Almería                   | 15       | 0.61%   |
| Gijón                     | 14       | 0.57%   |
| Lugo                       | 13       | 0.53%   |
| Torrejón de Ardoz         | 12       | 0.49%   |
| Santander                  | 12       | 0.49%   |
| Salamanca                  | 12       | 0.49%   |
| Fuenlabrada                | 12       | 0.49%   |
| Alcalá de Henares         | 12       | 0.49%   |
| Pamplona                   | 11       | 0.45%   |
| Girona                     | 11       | 0.45%   |
| San Fernando               | 10       | 0.41%   |
| Mostoles                   | 10       | 0.41%   |
| Mataró                    | 10       | 0.41%   |
| Logroño                   | 10       | 0.41%   |
| Burgos                     | 10       | 0.41%   |
| Barakaldo                  | 10       | 0.41%   |
| Badalona                   | 10       | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 983      | 1666   | 23.13%  |
| WDC                         | 694      | 1156   | 16.33%  |
| Kingston                    | 545      | 799    | 12.83%  |
| Samsung Electronics         | 511      | 894    | 12.03%  |
| Toshiba                     | 264      | 489    | 6.21%   |
| Crucial                     | 205      | 308    | 4.82%   |
| SanDisk                     | 200      | 306    | 4.71%   |
| Hitachi                     | 114      | 145    | 2.68%   |
| China                       | 46       | 62     | 1.08%   |
| Unknown                     | 45       | 55     | 1.06%   |
| Maxtor                      | 41       | 59     | 0.96%   |
| Intel                       | 38       | 50     | 0.89%   |
| Micron/Crucial Technology   | 36       | 49     | 0.85%   |
| Silicon Motion              | 29       | 36     | 0.68%   |
| OCZ                         | 26       | 39     | 0.61%   |
| Phison                      | 24       | 28     | 0.56%   |
| KIOXIA-EXCERIA              | 24       | 35     | 0.56%   |
| Phison Electronics          | 21       | 34     | 0.49%   |
| HGST                        | 21       | 28     | 0.49%   |
| Corsair                     | 19       | 23     | 0.45%   |
| SK hynix                    | 17       | 24     | 0.4%    |
| JMicron Technology          | 16       | 19     | 0.38%   |
| Transcend                   | 15       | 33     | 0.35%   |
| Kingston Technology Company | 14       | 17     | 0.33%   |
| Emtec                       | 14       | 20     | 0.33%   |
| PNY                         | 13       | 18     | 0.31%   |
| KIOXIA                      | 13       | 16     | 0.31%   |
| KingDian                    | 13       | 20     | 0.31%   |
| Intenso                     | 12       | 16     | 0.28%   |
| Fujitsu                     | 12       | 16     | 0.28%   |
| Unknown                     | 11       | 13     | 0.26%   |
| Micron Technology           | 10       | 12     | 0.24%   |
| A-DATA Technology           | 10       | 19     | 0.24%   |
| Patriot                     | 9        | 17     | 0.21%   |
| USB30                       | 8        | 25     | 0.19%   |
| KingSpec                    | 8        | 10     | 0.19%   |
| Drevo                       | 8        | 11     | 0.19%   |
| KingFast                    | 7        | 8      | 0.16%   |
| SPCC                        | 6        | 6      | 0.14%   |
| Realtek Semiconductor       | 6        | 7      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD                   | 170      | 3.42%   |
| Seagate ST1000DM010-2EP102 1TB                    | 110      | 2.21%   |
| Kingston SA400S37480G 480GB SSD                   | 94       | 1.89%   |
| Seagate ST500DM002-1BD142 500GB                   | 92       | 1.85%   |
| Kingston SA400S37120G 120GB SSD                   | 71       | 1.43%   |
| Seagate ST3500418AS 500GB                         | 68       | 1.37%   |
| Kingston SV300S37A120G 120GB SSD                  | 68       | 1.37%   |
| Seagate ST1000DM003-1ER162 1TB                    | 61       | 1.23%   |
| Seagate ST2000DM008-2FR102 2TB                    | 57       | 1.15%   |
| Seagate ST1000DM003-1CH162 1TB                    | 50       | 1.01%   |
| Toshiba DT01ACA100 1TB                            | 49       | 0.99%   |
| Samsung SSD 860 EVO 500GB                         | 47       | 0.95%   |
| Crucial CT500MX500SSD1 500GB                      | 39       | 0.79%   |
| Seagate ST31000528AS 1TB                          | 35       | 0.7%    |
| Samsung SSD 850 EVO 250GB                         | 34       | 0.68%   |
| Samsung SSD 850 EVO 500GB                         | 32       | 0.64%   |
| Samsung NVMe SSD Drive 500GB                      | 32       | 0.64%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 30       | 0.6%    |
| WDC WD20EARX-00PASB0 2TB                          | 29       | 0.58%   |
| Toshiba DT01ACA050 500GB                          | 28       | 0.56%   |
| Seagate ST4000DM004-2CV104 4TB                    | 27       | 0.54%   |
| WDC WD5000AAKX-08U6AA0 500GB                      | 26       | 0.52%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 26       | 0.52%   |
| Seagate ST2000DM001-1ER164 2TB                    | 26       | 0.52%   |
| Seagate ST1000DM003-1SB102 1TB                    | 26       | 0.52%   |
| SanDisk SSD PLUS 480GB                            | 26       | 0.52%   |
| Kingston SV300S37A240G 240GB SSD                  | 26       | 0.52%   |
| SanDisk NVMe SSD Drive 500GB                      | 25       | 0.5%    |
| Crucial CT1000MX500SSD1 1TB                       | 24       | 0.48%   |
| Toshiba TR200 240GB SSD                           | 23       | 0.46%   |
| Seagate ST2000DM001-1CH164 2TB                    | 23       | 0.46%   |
| Kingston SUV400S37240G 240GB SSD                  | 23       | 0.46%   |
| Toshiba DT01ACA300 3TB                            | 22       | 0.44%   |
| Seagate ST2000DM006-2DM164 2TB                    | 22       | 0.44%   |
| Seagate ST1000DM003-1SB10C 1TB                    | 22       | 0.44%   |
| Crucial CT480BX500SSD1 480GB                      | 22       | 0.44%   |
| WDC WD20EZRZ-00Z5HB0 2TB                          | 21       | 0.42%   |
| Unknown SD/MMC/MS PRO 256GB                       | 21       | 0.42%   |
| Toshiba DT01ACA200 2TB                            | 21       | 0.42%   |
| Samsung SSD 970 EVO Plus 500GB                    | 20       | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 976      | 1650   | 45.56%  |
| WDC                 | 613      | 984    | 28.62%  |
| Toshiba             | 210      | 344    | 9.8%    |
| Hitachi             | 114      | 145    | 5.32%   |
| Samsung Electronics | 106      | 136    | 4.95%   |
| Maxtor              | 37       | 52     | 1.73%   |
| Unknown             | 21       | 23     | 0.98%   |
| HGST                | 21       | 28     | 0.98%   |
| JMicron Technology  | 12       | 13     | 0.56%   |
| Fujitsu             | 11       | 15     | 0.51%   |
| ASMT                | 4        | 7      | 0.19%   |
| Hewlett-Packard     | 3        | 4      | 0.14%   |
| Apple               | 3        | 4      | 0.14%   |
| Intenso             | 2        | 3      | 0.09%   |
| TO Exter            | 1        | 1      | 0.05%   |
| Quantum             | 1        | 1      | 0.05%   |
| Inateck             | 1        | 1      | 0.05%   |
| HPE                 | 1        | 2      | 0.05%   |
| HGST HTS            | 1        | 1      | 0.05%   |
| External            | 1        | 1      | 0.05%   |
| CIRAGO              | 1        | 1      | 0.05%   |
| China               | 1        | 1      | 0.05%   |
| Unknown             | 1        | 3      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 515      | 743    | 32.8%   |
| Samsung Electronics | 276      | 426    | 17.58%  |
| Crucial             | 185      | 278    | 11.78%  |
| SanDisk             | 130      | 179    | 8.28%   |
| WDC                 | 88       | 140    | 5.61%   |
| Toshiba             | 58       | 138    | 3.69%   |
| China               | 44       | 60     | 2.8%    |
| OCZ                 | 26       | 39     | 1.66%   |
| KIOXIA-EXCERIA      | 17       | 22     | 1.08%   |
| Transcend           | 15       | 33     | 0.96%   |
| KingDian            | 13       | 20     | 0.83%   |
| Intel               | 13       | 18     | 0.83%   |
| Emtec               | 13       | 18     | 0.83%   |
| Intenso             | 11       | 13     | 0.7%    |
| PNY                 | 10       | 15     | 0.64%   |
| Patriot             | 9        | 17     | 0.57%   |
| A-DATA Technology   | 9        | 18     | 0.57%   |
| USB30               | 8        | 25     | 0.51%   |
| KingSpec            | 8        | 10     | 0.51%   |
| Unknown             | 8        | 8      | 0.51%   |
| Drevo               | 7        | 9      | 0.45%   |
| Corsair             | 7        | 9      | 0.45%   |
| Fanxiang            | 6        | 8      | 0.38%   |
| SABRENT             | 5        | 5      | 0.32%   |
| GOODRAM             | 5        | 7      | 0.32%   |
| SK hynix            | 4        | 4      | 0.25%   |
| Maxtor              | 4        | 7      | 0.25%   |
| BAITITON            | 4        | 5      | 0.25%   |
| SPCC                | 3        | 3      | 0.19%   |
| Micron Technology   | 3        | 4      | 0.19%   |
| Lexar               | 3        | 3      | 0.19%   |
| KODAK               | 3        | 3      | 0.19%   |
| KingFast            | 3        | 3      | 0.19%   |
| Kimtigo             | 3        | 3      | 0.19%   |
| Gigabyte Technology | 3        | 3      | 0.19%   |
| ValueTech           | 2        | 2      | 0.13%   |
| Netac               | 2        | 2      | 0.13%   |
| LITEON              | 2        | 2      | 0.13%   |
| Kingchuxing         | 2        | 2      | 0.13%   |
| Hewlett-Packard     | 2        | 2      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1650     | 3420   | 47.45%  |
| SSD     | 1234     | 2357   | 35.49%  |
| NVMe    | 530      | 901    | 15.24%  |
| Unknown | 44       | 56     | 1.27%   |
| MMC     | 19       | 23     | 0.55%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 2054     | 5634   | 75.02%  |
| NVMe | 529      | 900    | 19.32%  |
| SAS  | 136      | 200    | 4.97%   |
| MMC  | 19       | 23     | 0.69%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| 0.01-0.5        | 1621     | 3257   | 52.16%  |
| 0.51-1.0        | 889      | 1478   | 28.6%   |
| 1.01-2.0        | 354      | 593    | 11.39%  |
| 3.01-4.0        | 101      | 175    | 3.25%   |
| 2.01-3.0        | 91       | 149    | 2.93%   |
| 4.01-10.0       | 48       | 120    | 1.54%   |
| 10.01-20.0      | 3        | 3      | 0.1%    |
| More than 100.0 | 1        | 2      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 539      | 22.03%  |
| 251-500        | 428      | 17.49%  |
| 501-1000       | 388      | 15.86%  |
| 1001-2000      | 264      | 10.79%  |
| More than 3000 | 218      | 8.91%   |
| 1-20           | 182      | 7.44%   |
| 2001-3000      | 164      | 6.7%    |
| 51-100         | 121      | 4.94%   |
| Unknown        | 72       | 2.94%   |
| 21-50          | 71       | 2.9%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 830      | 33.19%  |
| 21-50          | 361      | 14.43%  |
| 101-250        | 294      | 11.76%  |
| 51-100         | 240      | 9.6%    |
| 251-500        | 203      | 8.12%   |
| 501-1000       | 198      | 7.92%   |
| 1001-2000      | 153      | 6.12%   |
| More than 3000 | 85       | 3.4%    |
| Unknown        | 72       | 2.88%   |
| 2001-3000      | 64       | 2.56%   |
| 0              | 1        | 0.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 19       | 19     | 5.23%   |
| Seagate ST3500418AS 500GB           | 17       | 23     | 4.68%   |
| Kingston SV300S37A120G 120GB SSD    | 11       | 17     | 3.03%   |
| Seagate ST31000528AS 1TB            | 8        | 9      | 2.2%    |
| Seagate ST3500320AS 500GB           | 6        | 10     | 1.65%   |
| Seagate ST1000DM010-2EP102 1TB      | 6        | 8      | 1.65%   |
| Seagate ST1000DM003-1CH162 1TB      | 6        | 7      | 1.65%   |
| SanDisk SSD PLUS 480GB              | 5        | 6      | 1.38%   |
| WDC WD5000AAKX-001CA0 500GB         | 4        | 6      | 1.1%    |
| WDC WD20EARX-00PASB0 2TB            | 4        | 7      | 1.1%    |
| Seagate ST9500325AS 500GB           | 4        | 5      | 1.1%    |
| Seagate ST31500341AS 1TB            | 4        | 4      | 1.1%    |
| Seagate ST1000DM003-1ER162 1TB      | 4        | 7      | 1.1%    |
| Drevo X1 SSD 480GB                  | 4        | 6      | 1.1%    |
| WDC WD20PURZ-85GU6Y0 2TB            | 3        | 5      | 0.83%   |
| WDC WD20EZRX-00DC0B0 2TB            | 3        | 3      | 0.83%   |
| Toshiba DT01ACA100 1TB              | 3        | 7      | 0.83%   |
| Toshiba DT01ACA050 500GB            | 3        | 4      | 0.83%   |
| Seagate ST500LT012-1DG142 500GB     | 3        | 3      | 0.83%   |
| Seagate ST3500830AS 500GB           | 3        | 4      | 0.83%   |
| Seagate ST3250310AS 250GB           | 3        | 3      | 0.83%   |
| Seagate ST3200822A 200GB            | 3        | 3      | 0.83%   |
| Seagate ST2000DL003-9VT166 2TB      | 3        | 4      | 0.83%   |
| Samsung Electronics SSD 870 EVO 1TB | 3        | 4      | 0.83%   |
| Samsung Electronics HD501LJ 500GB   | 3        | 3      | 0.83%   |
| WDC WD6400AAKS-22A7B0 640GB         | 2        | 2      | 0.55%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 2        | 2      | 0.55%   |
| WDC WD5000AAKS-00YGA0 500GB         | 2        | 2      | 0.55%   |
| WDC WD40EZRX-00SPEB0 4TB            | 2        | 3      | 0.55%   |
| WDC WD40EFRX-68WT0N0 4TB            | 2        | 2      | 0.55%   |
| WDC WD2500AAJS-00B4A0 250GB         | 2        | 2      | 0.55%   |
| WDC WD20PURX-64P6ZY0 2TB            | 2        | 2      | 0.55%   |
| WDC WD20EFRX-68EUZN0 2TB            | 2        | 2      | 0.55%   |
| WDC WD20EARS-00MVWB0 2TB            | 2        | 5      | 0.55%   |
| WDC WD10EARS-00Y5B1 1TB             | 2        | 2      | 0.55%   |
| WDC WD1002FAEX-00Z3A0 1TB           | 2        | 2      | 0.55%   |
| Transcend TS1TSSD230S 1TB           | 2        | 9      | 0.55%   |
| Seagate ST4000DM004-2CV104 4TB      | 2        | 2      | 0.55%   |
| Seagate ST3500820AS 500GB           | 2        | 2      | 0.55%   |
| Seagate ST3500312CS 500GB           | 2        | 2      | 0.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 133      | 180    | 38.22%  |
| WDC                 | 78       | 101    | 22.41%  |
| Samsung Electronics | 25       | 28     | 7.18%   |
| Kingston            | 21       | 32     | 6.03%   |
| Toshiba             | 14       | 19     | 4.02%   |
| SanDisk             | 12       | 13     | 3.45%   |
| Hitachi             | 12       | 13     | 3.45%   |
| Maxtor              | 9        | 11     | 2.59%   |
| Crucial             | 9        | 9      | 2.59%   |
| Drevo               | 5        | 7      | 1.44%   |
| China               | 4        | 5      | 1.15%   |
| Transcend           | 2        | 9      | 0.57%   |
| OCZ                 | 2        | 2      | 0.57%   |
| KingDian            | 2        | 3      | 0.57%   |
| Intenso             | 2        | 2      | 0.57%   |
| Intel               | 2        | 4      | 0.57%   |
| HGST                | 2        | 2      | 0.57%   |
| Fujitsu             | 2        | 3      | 0.57%   |
| SPCC                | 1        | 1      | 0.29%   |
| Patriot             | 1        | 1      | 0.29%   |
| Micron Technology   | 1        | 1      | 0.29%   |
| KingSpec            | 1        | 1      | 0.29%   |
| JMicron Technology  | 1        | 1      | 0.29%   |
| Hypertec            | 1        | 1      | 0.29%   |
| HPE                 | 1        | 2      | 0.29%   |
| Dogfish             | 1        | 2      | 0.29%   |
| Corsair             | 1        | 1      | 0.29%   |
| ASMT                | 1        | 2      | 0.29%   |
| A-DATA Technology   | 1        | 1      | 0.29%   |
| Unknown             | 1        | 1      | 0.29%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 133      | 180    | 49.26%  |
| WDC                 | 78       | 101    | 28.89%  |
| Samsung Electronics | 16       | 18     | 5.93%   |
| Toshiba             | 14       | 19     | 5.19%   |
| Hitachi             | 12       | 13     | 4.44%   |
| Maxtor              | 9        | 11     | 3.33%   |
| HGST                | 2        | 2      | 0.74%   |
| Fujitsu             | 2        | 3      | 0.74%   |
| JMicron Technology  | 1        | 1      | 0.37%   |
| HPE                 | 1        | 2      | 0.37%   |
| China               | 1        | 1      | 0.37%   |
| ASMT                | 1        | 2      | 0.37%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 240      | 353    | 76.68%  |
| SSD  | 66       | 97     | 21.09%  |
| NVMe | 7        | 8      | 2.24%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST3500418AS 500GB         | 2        | 2      | 14.29%  |
| WDC WD5000BEVT-60ZAT1 500GB       | 1        | 1      | 7.14%   |
| Toshiba DT01ACA200 2TB            | 1        | 1      | 7.14%   |
| Toshiba DT01ACA050 500GB          | 1        | 1      | 7.14%   |
| Seagate ST3500830AS 500GB         | 1        | 1      | 7.14%   |
| Seagate ST31000528AS 1TB          | 1        | 1      | 7.14%   |
| Seagate ST31000520AS 1TB          | 1        | 1      | 7.14%   |
| Seagate ST31000333AS 1TB          | 1        | 1      | 7.14%   |
| Samsung Electronics SSD 980 500GB | 1        | 1      | 7.14%   |
| Samsung Electronics SSD 980 1TB   | 1        | 1      | 7.14%   |
| Samsung Electronics HD253GJ 250GB | 1        | 1      | 7.14%   |
| Samsung Electronics HD103SJ 1TB   | 1        | 2      | 7.14%   |
| Hitachi HDS721010DLE630 1TB       | 1        | 1      | 7.14%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 6        | 6      | 42.86%  |
| Samsung Electronics | 4        | 5      | 28.57%  |
| Toshiba             | 2        | 2      | 14.29%  |
| WDC                 | 1        | 1      | 7.14%   |
| Hitachi             | 1        | 1      | 7.14%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 1421     | 3962   | 55.33%  |
| Works    | 841      | 2322   | 32.75%  |
| Malfunc  | 292      | 458    | 11.37%  |
| Failed   | 14       | 15     | 0.55%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1480     | 48.05%  |
| AMD                              | 636      | 20.65%  |
| Samsung Electronics              | 183      | 5.94%   |
| SanDisk                          | 103      | 3.34%   |
| ASMedia Technology               | 94       | 3.05%   |
| JMicron Technology               | 90       | 2.92%   |
| Nvidia                           | 76       | 2.47%   |
| Marvell Technology Group         | 71       | 2.31%   |
| Phison Electronics               | 64       | 2.08%   |
| Kingston Technology Company      | 58       | 1.88%   |
| Micron/Crucial Technology        | 57       | 1.85%   |
| Silicon Motion                   | 33       | 1.07%   |
| VIA Technologies                 | 28       | 0.91%   |
| KIOXIA                           | 22       | 0.71%   |
| SK hynix                         | 12       | 0.39%   |
| Silicon Integrated Systems [SiS] | 9        | 0.29%   |
| Micron Technology                | 9        | 0.29%   |
| Realtek Semiconductor            | 7        | 0.23%   |
| LSI Logic / Symbios Logic        | 7        | 0.23%   |
| MAXIO Technology (Hangzhou)      | 6        | 0.19%   |
| Seagate Technology               | 5        | 0.16%   |
| Silicon Image                    | 4        | 0.13%   |
| Integrated Technology Express    | 3        | 0.1%    |
| Adaptec                          | 3        | 0.1%    |
| Union Memory (Shenzhen)          | 2        | 0.06%   |
| Toshiba America Info Systems     | 2        | 0.06%   |
| Shenzhen Longsys Electronics     | 2        | 0.06%   |
| HighPoint Technologies           | 2        | 0.06%   |
| Broadcom / LSI                   | 2        | 0.06%   |
| ADATA Technology                 | 2        | 0.06%   |
| ULi Electronics                  | 1        | 0.03%   |
| Swissbit                         | 1        | 0.03%   |
| OCZ Technology Group             | 1        | 0.03%   |
| Lite-On Technology               | 1        | 0.03%   |
| INNOGRIT                         | 1        | 0.03%   |
| Hewlett-Packard                  | 1        | 0.03%   |
| Dell                             | 1        | 0.03%   |
| 3ware                            | 1        | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 367      | 9.33%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 212      | 5.39%   |
| AMD 400 Series Chipset SATA Controller                                                  | 155      | 3.94%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 124      | 3.15%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 124      | 3.15%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 120      | 3.05%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 107      | 2.72%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 98       | 2.49%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 96       | 2.44%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 89       | 2.26%   |
| Intel SATA Controller [RAID mode]                                                       | 84       | 2.14%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 79       | 2.01%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 75       | 1.91%   |
| AMD 500 Series Chipset SATA Controller                                                  | 72       | 1.83%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 66       | 1.68%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 64       | 1.63%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 56       | 1.42%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 56       | 1.42%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 56       | 1.42%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 46       | 1.17%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 41       | 1.04%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 39       | 0.99%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 39       | 0.99%   |
| AMD 300 Series Chipset SATA Controller                                                  | 37       | 0.94%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 34       | 0.86%   |
| Nvidia MCP61 SATA Controller                                                            | 32       | 0.81%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 31       | 0.79%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 31       | 0.79%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 30       | 0.76%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 30       | 0.76%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 30       | 0.76%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 29       | 0.74%   |
| Phison E12 NVMe Controller                                                              | 28       | 0.71%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 28       | 0.71%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 28       | 0.71%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                             | 27       | 0.69%   |
| AMD FCH SATA Controller D                                                               | 27       | 0.69%   |
| Nvidia MCP61 IDE                                                                        | 26       | 0.66%   |
| JMicron JMB368 IDE controller                                                           | 26       | 0.66%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 25       | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 1726     | 56.87%  |
| IDE  | 612      | 20.16%  |
| NVMe | 536      | 17.66%  |
| RAID | 142      | 4.68%   |
| SAS  | 11       | 0.36%   |
| SCSI | 8        | 0.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 1534     | 68.82%  |
| AMD    | 695      | 31.18%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 41       | 1.83%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 34       | 1.52%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 30       | 1.34%   |
| Intel Core i3-4150 CPU @ 3.50GHz            | 28       | 1.25%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 26       | 1.16%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 26       | 1.16%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 26       | 1.16%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 26       | 1.16%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 25       | 1.12%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 25       | 1.12%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 22       | 0.98%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 21       | 0.94%   |
| AMD FX-8350 Eight-Core Processor            | 21       | 0.94%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 20       | 0.89%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 20       | 0.89%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 18       | 0.8%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 18       | 0.8%    |
| Intel Core i7-8700 CPU @ 3.20GHz            | 17       | 0.76%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 17       | 0.76%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 17       | 0.76%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 17       | 0.76%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 17       | 0.76%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 16       | 0.71%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 15       | 0.67%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 15       | 0.67%   |
| Intel Core i3-4170 CPU @ 3.70GHz            | 15       | 0.67%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 15       | 0.67%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 15       | 0.67%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 14       | 0.62%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 14       | 0.62%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 14       | 0.62%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 14       | 0.62%   |
| Intel Core i5-4440 CPU @ 3.10GHz            | 13       | 0.58%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 13       | 0.58%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 13       | 0.58%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 12       | 0.54%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 12       | 0.54%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 12       | 0.54%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 12       | 0.54%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 12       | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 388      | 17.33%  |
| Intel Core i7           | 290      | 12.95%  |
| Intel Core i3           | 205      | 9.16%   |
| AMD Ryzen 5             | 188      | 8.4%    |
| AMD Ryzen 7             | 127      | 5.67%   |
| Intel Xeon              | 103      | 4.6%    |
| Intel Celeron           | 83       | 3.71%   |
| Intel Core 2 Quad       | 77       | 3.44%   |
| Intel Core 2 Duo        | 69       | 3.08%   |
| Other                   | 65       | 2.9%    |
| Intel Pentium           | 62       | 2.77%   |
| AMD FX                  | 62       | 2.77%   |
| AMD Ryzen 9             | 53       | 2.37%   |
| Intel Pentium Dual-Core | 46       | 2.05%   |
| AMD Ryzen 3             | 34       | 1.52%   |
| Intel Core 2            | 31       | 1.38%   |
| AMD A10                 | 28       | 1.25%   |
| AMD Athlon 64 X2        | 27       | 1.21%   |
| Intel Pentium Dual      | 25       | 1.12%   |
| Intel Core i9           | 25       | 1.12%   |
| AMD Athlon II X2        | 23       | 1.03%   |
| Intel Pentium 4         | 21       | 0.94%   |
| AMD A4                  | 19       | 0.85%   |
| Intel Atom              | 16       | 0.71%   |
| AMD Phenom II X4        | 16       | 0.71%   |
| AMD A8                  | 14       | 0.63%   |
| AMD Phenom              | 12       | 0.54%   |
| AMD Athlon              | 12       | 0.54%   |
| AMD A6                  | 12       | 0.54%   |
| Intel Pentium D         | 10       | 0.45%   |
| Intel Pentium Gold      | 9        | 0.4%    |
| Intel Genuine           | 9        | 0.4%    |
| AMD Phenom II X6        | 9        | 0.4%    |
| AMD Ryzen Threadripper  | 8        | 0.36%   |
| AMD Athlon II X4        | 8        | 0.36%   |
| AMD Athlon 64           | 7        | 0.31%   |
| AMD Sempron             | 6        | 0.27%   |
| AMD Ryzen 5 PRO         | 6        | 0.27%   |
| Intel Pentium Silver    | 5        | 0.22%   |
| AMD Phenom II X2        | 4        | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 840      | 37.43%  |
| 2       | 642      | 28.61%  |
| 6       | 324      | 14.44%  |
| 8       | 216      | 9.63%   |
| 1       | 72       | 3.21%   |
| 12      | 62       | 2.76%   |
| 16      | 28       | 1.25%   |
| 3       | 23       | 1.02%   |
| 10      | 18       | 0.8%    |
| Unknown | 6        | 0.27%   |
| 24      | 4        | 0.18%   |
| 14      | 4        | 0.18%   |
| 32      | 2        | 0.09%   |
| 64      | 1        | 0.04%   |
| 36      | 1        | 0.04%   |
| 20      | 1        | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 2203     | 98.79%  |
| 2      | 27       | 1.21%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 1227     | 54.73%  |
| 1       | 1008     | 44.96%  |
| Unknown | 6        | 0.27%   |
| 4       | 1        | 0.04%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 2188     | 97.5%   |
| Unknown        | 33       | 1.47%   |
| 64-bit         | 17       | 0.76%   |
| 32-bit         | 6        | 0.27%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 621      | 26.49%  |
| 0x306c3    | 205      | 8.75%   |
| 0x306a9    | 99       | 4.22%   |
| 0x1067a    | 98       | 4.18%   |
| 0x206a7    | 96       | 4.1%    |
| 0x506e3    | 80       | 3.41%   |
| 0x08701021 | 59       | 2.52%   |
| 0x906ea    | 53       | 2.26%   |
| 0x0800820d | 51       | 2.18%   |
| 0x906e9    | 47       | 2.01%   |
| 0x6fb      | 40       | 1.71%   |
| 0x08108109 | 39       | 1.66%   |
| 0x06000852 | 36       | 1.54%   |
| 0x6fd      | 31       | 1.32%   |
| 0x08701013 | 29       | 1.24%   |
| 0x06001119 | 29       | 1.24%   |
| 0x010000c8 | 29       | 1.24%   |
| 0xa0653    | 28       | 1.19%   |
| 0x906ed    | 23       | 0.98%   |
| 0x20655    | 20       | 0.85%   |
| 0x106e5    | 20       | 0.85%   |
| 0xa0655    | 19       | 0.81%   |
| 0x906eb    | 19       | 0.81%   |
| 0x6f6      | 19       | 0.81%   |
| 0x0a201016 | 19       | 0.81%   |
| 0x306f2    | 17       | 0.73%   |
| 0xa0671    | 16       | 0.68%   |
| 0x206d7    | 16       | 0.68%   |
| 0x20652    | 16       | 0.68%   |
| 0x10677    | 16       | 0.68%   |
| 0x10676    | 16       | 0.68%   |
| 0x06003106 | 16       | 0.68%   |
| 0x08001138 | 15       | 0.64%   |
| 0x08001137 | 15       | 0.64%   |
| 0x08101016 | 14       | 0.6%    |
| 0x906ec    | 12       | 0.51%   |
| 0x0a50000c | 12       | 0.51%   |
| 0x0a201009 | 12       | 0.51%   |
| 0x0810100b | 12       | 0.51%   |
| 0x506c9    | 11       | 0.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 294      | 13.11%  |
| KabyLake         | 222      | 9.9%    |
| Penryn           | 155      | 6.91%   |
| SandyBridge      | 144      | 6.42%   |
| IvyBridge        | 141      | 6.29%   |
| Zen+             | 129      | 5.75%   |
| Skylake          | 122      | 5.44%   |
| Core             | 122      | 5.44%   |
| Zen 2            | 121      | 5.39%   |
| Piledriver       | 91       | 4.06%   |
| Zen 3            | 90       | 4.01%   |
| K10              | 82       | 3.66%   |
| Zen              | 70       | 3.12%   |
| CometLake        | 67       | 2.99%   |
| Westmere         | 55       | 2.45%   |
| K8 Hammer        | 42       | 1.87%   |
| Nehalem          | 40       | 1.78%   |
| Unknown          | 38       | 1.69%   |
| NetBurst         | 33       | 1.47%   |
| Steamroller      | 24       | 1.07%   |
| Alderlake Hybrid | 24       | 1.07%   |
| Silvermont       | 22       | 0.98%   |
| IceLake          | 21       | 0.94%   |
| Goldmont plus    | 17       | 0.76%   |
| Broadwell        | 15       | 0.67%   |
| Goldmont         | 11       | 0.49%   |
| Bonnell          | 9        | 0.4%    |
| K10 Llano        | 8        | 0.36%   |
| Bulldozer        | 8        | 0.36%   |
| Excavator        | 7        | 0.31%   |
| Puma             | 5        | 0.22%   |
| Tremont          | 4        | 0.18%   |
| TigerLake        | 4        | 0.18%   |
| Jaguar           | 3        | 0.13%   |
| K6               | 1        | 0.04%   |
| Gracemont        | 1        | 0.04%   |
| Bobcat           | 1        | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Nvidia                                       | 1009     | 42.25%  |
| Intel                                        | 741      | 31.03%  |
| AMD                                          | 610      | 25.54%  |
| Matrox Electronics Systems                   | 8        | 0.34%   |
| Silicon Integrated Systems [SiS]             | 6        | 0.25%   |
| ASPEED Technology                            | 6        | 0.25%   |
| VIA Technologies                             | 5        | 0.21%   |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 0.04%   |
| Silicon Motion                               | 1        | 0.04%   |
| ATI Technologies                             | 1        | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 122      | 4.95%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 114      | 4.62%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 86       | 3.49%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 75       | 3.04%   |
| Nvidia GT218 [GeForce 210]                                                               | 71       | 2.88%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 58       | 2.35%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 53       | 2.15%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 47       | 1.91%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 46       | 1.87%   |
| Intel HD Graphics 530                                                                    | 44       | 1.78%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 42       | 1.7%    |
| Nvidia GP108 [GeForce GT 1030]                                                           | 36       | 1.46%   |
| Intel HD Graphics 630                                                                    | 36       | 1.46%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 35       | 1.42%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 34       | 1.38%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 30       | 1.22%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 30       | 1.22%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 28       | 1.14%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 26       | 1.05%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 24       | 0.97%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 23       | 0.93%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 22       | 0.89%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 22       | 0.89%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 22       | 0.89%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 21       | 0.85%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 21       | 0.85%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 20       | 0.81%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 19       | 0.77%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 19       | 0.77%   |
| Intel Core Processor Integrated Graphics Controller                                      | 18       | 0.73%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 17       | 0.69%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 17       | 0.69%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 16       | 0.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 15       | 0.61%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 15       | 0.61%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 14       | 0.57%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 14       | 0.57%   |
| AMD Raphael                                                                              | 13       | 0.53%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 13       | 0.53%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 13       | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| 1 x Nvidia             | 931      | 41.07%  |
| 1 x Intel              | 629      | 27.75%  |
| 1 x AMD                | 551      | 24.31%  |
| Intel + Nvidia         | 50       | 2.21%   |
| 2 x AMD                | 35       | 1.54%   |
| AMD + Nvidia           | 18       | 0.79%   |
| 2 x Nvidia             | 12       | 0.53%   |
| Intel + AMD            | 8        | 0.35%   |
| 1 x Matrox             | 7        | 0.31%   |
| 1 x SiS                | 6        | 0.26%   |
| 1 x VIA                | 5        | 0.22%   |
| 1 x ASPEED             | 5        | 0.22%   |
| Other                  | 2        | 0.09%   |
| 3 x AMD                | 1        | 0.04%   |
| 2 x Intel              | 1        | 0.04%   |
| 1 x XGI                | 1        | 0.04%   |
| 1 x Silicon Motion     | 1        | 0.04%   |
| Nvidia + Matrox        | 1        | 0.04%   |
| Nvidia + ASPEED        | 1        | 0.04%   |
| 1 x Intel + 3 x Nvidia | 1        | 0.04%   |
| Intel + 2 x AMD        | 1        | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1646     | 72.13%  |
| Proprietary | 536      | 23.49%  |
| Unknown     | 100      | 4.38%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 955      | 40.97%  |
| 1.01-2.0   | 379      | 16.26%  |
| 0.51-1.0   | 234      | 10.04%  |
| 0.01-0.5   | 228      | 9.78%   |
| 3.01-4.0   | 202      | 8.67%   |
| 7.01-8.0   | 194      | 8.32%   |
| 5.01-6.0   | 65       | 2.79%   |
| 8.01-16.0  | 36       | 1.54%   |
| 2.01-3.0   | 26       | 1.12%   |
| 16.01-24.0 | 10       | 0.43%   |
| 32.01-64.0 | 1        | 0.04%   |
| 4.01-5.0   | 1        | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 371      | 15.82%  |
| Goldstar                | 320      | 13.65%  |
| Hewlett-Packard         | 219      | 9.34%   |
| BenQ                    | 177      | 7.55%   |
| Acer                    | 173      | 7.38%   |
| Dell                    | 147      | 6.27%   |
| Ancor Communications    | 136      | 5.8%    |
| Philips                 | 135      | 5.76%   |
| AOC                     | 110      | 4.69%   |
| LG Electronics          | 58       | 2.47%   |
| Unknown                 | 44       | 1.88%   |
| Lenovo                  | 40       | 1.71%   |
| Sony                    | 35       | 1.49%   |
| ASUSTek Computer        | 29       | 1.24%   |
| HannStar                | 26       | 1.11%   |
| ViewSonic               | 25       | 1.07%   |
| MSI                     | 16       | 0.68%   |
| OEM                     | 12       | 0.51%   |
| Eizo                    | 12       | 0.51%   |
| Packard Bell            | 10       | 0.43%   |
| Fujitsu Siemens         | 10       | 0.43%   |
| Xiaomi                  | 9        | 0.38%   |
| Vestel Elektronik       | 9        | 0.38%   |
| Iiyama                  | 9        | 0.38%   |
| Chi Mei Optoelectronics | 9        | 0.38%   |
| Unknown                 | 9        | 0.38%   |
| ___                     | 8        | 0.34%   |
| NEC Computers           | 8        | 0.34%   |
| RTK                     | 6        | 0.26%   |
| Hitachi                 | 6        | 0.26%   |
| Toshiba                 | 5        | 0.21%   |
| Plain Tree Systems      | 5        | 0.21%   |
| Mi                      | 5        | 0.21%   |
| HPN                     | 5        | 0.21%   |
| HKC                     | 5        | 0.21%   |
| Gigabyte Technology     | 5        | 0.21%   |
| AGO                     | 5        | 0.21%   |
| MStar                   | 4        | 0.17%   |
| Microstep               | 4        | 0.17%   |
| Lenovo Group Limited    | 4        | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 13       | 0.52%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 13       | 0.52%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                | 12       | 0.48%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                       | 12       | 0.48%   |
| Ancor Communications ASUS VX239 ACI23E1 1920x1080 509x286mm 23.0-inch | 12       | 0.48%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch     | 11       | 0.44%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 11       | 0.44%   |
| Goldstar FULL HD GSM5AB9 1920x1080 480x270mm 21.7-inch                | 11       | 0.44%   |
| AOC 24G2W1G4 AOC2402 1920x1080 527x296mm 23.8-inch                    | 11       | 0.44%   |
| Samsung Electronics SyncMaster SAM03D0 1440x900 410x257mm 19.1-inch   | 10       | 0.4%    |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 10       | 0.4%    |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 10       | 0.4%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 10       | 0.4%    |
| BenQ GW2270 BNQ78DB 1920x1080 480x270mm 21.7-inch                     | 10       | 0.4%    |
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x400mm 31.7-inch  | 9        | 0.36%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 9        | 0.36%   |
| OEM 19W_LCD_TV OEM3700 1920x540                                       | 9        | 0.36%   |
| Unknown                                                               | 9        | 0.36%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 8        | 0.32%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch               | 8        | 0.32%   |
| Hewlett-Packard 27w HPN3494 1920x1080 598x336mm 27.0-inch             | 8        | 0.32%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                      | 8        | 0.32%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 7        | 0.28%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 7        | 0.28%   |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch     | 7        | 0.28%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch              | 7        | 0.28%   |
| AOC 27G2G8 AOC2702 1920x1080 598x336mm 27.0-inch                      | 7        | 0.28%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 6        | 0.24%   |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 885x498mm 40.0-inch | 6        | 0.24%   |
| LG Electronics LCD Monitor LG TV 1920x1080                            | 6        | 0.24%   |
| Hewlett-Packard L1740 HWP2648 1280x1024 337x270mm 17.0-inch           | 6        | 0.24%   |
| Hewlett-Packard 24fw HPN3545 1920x1080 527x296mm 23.8-inch            | 6        | 0.24%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                  | 6        | 0.24%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 6        | 0.24%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 6        | 0.24%   |
| BenQ LCD BNQ801B 2560x1440 527x296mm 23.8-inch                        | 6        | 0.24%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                     | 6        | 0.24%   |
| Ancor Communications VX229 ACI22E5 1920x1080 476x268mm 21.5-inch      | 6        | 0.24%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch      | 6        | 0.24%   |
| Ancor Communications ASUS VS229 ACI22C2 1920x1080 477x268mm 21.5-inch | 6        | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1050     | 45.79%  |
| 1280x1024 (SXGA)   | 200      | 8.72%   |
| 3840x2160 (4K)     | 180      | 7.85%   |
| 2560x1440 (QHD)    | 152      | 6.63%   |
| 1680x1050 (WSXGA+) | 120      | 5.23%   |
| 1366x768 (WXGA)    | 97       | 4.23%   |
| 1440x900 (WXGA+)   | 90       | 3.92%   |
| Unknown            | 60       | 2.62%   |
| 2560x1080          | 50       | 2.18%   |
| 1920x1200 (WUXGA)  | 46       | 2.01%   |
| 1360x768           | 46       | 2.01%   |
| 1600x900 (HD+)     | 43       | 1.88%   |
| 3440x1440          | 23       | 1%      |
| 3840x1080          | 22       | 0.96%   |
| 1024x768 (XGA)     | 19       | 0.83%   |
| 1600x1200          | 12       | 0.52%   |
| 1920x540           | 11       | 0.48%   |
| 2288x1287          | 6        | 0.26%   |
| 3200x1080          | 5        | 0.22%   |
| 4480x1080          | 4        | 0.17%   |
| 2560x1600          | 4        | 0.17%   |
| 3600x1080          | 3        | 0.13%   |
| 3360x1080          | 3        | 0.13%   |
| 2960x1050          | 3        | 0.13%   |
| 2944x1080          | 3        | 0.13%   |
| 2560x1024          | 3        | 0.13%   |
| 2048x1152          | 3        | 0.13%   |
| 1280x720 (HD)      | 3        | 0.13%   |
| 7680x2160          | 2        | 0.09%   |
| 5760x2160          | 2        | 0.09%   |
| 4480x1440          | 2        | 0.09%   |
| 3840x1600          | 2        | 0.09%   |
| 3840x1200          | 2        | 0.09%   |
| 3520x1080          | 2        | 0.09%   |
| 1280x960           | 2        | 0.09%   |
| 800x480            | 1        | 0.04%   |
| 7920x1440          | 1        | 0.04%   |
| 5760x1200          | 1        | 0.04%   |
| 5560x2300          | 1        | 0.04%   |
| 5520x1080          | 1        | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 309      | 13.24%  |
| 24      | 306      | 13.11%  |
| 27      | 296      | 12.68%  |
| Unknown | 278      | 11.91%  |
| 23      | 241      | 10.33%  |
| 19      | 153      | 6.56%   |
| 18      | 117      | 5.01%   |
| 17      | 111      | 4.76%   |
| 22      | 86       | 3.68%   |
| 31      | 62       | 2.66%   |
| 34      | 60       | 2.57%   |
| 20      | 57       | 2.44%   |
| 84      | 33       | 1.41%   |
| 15      | 29       | 1.24%   |
| 54      | 24       | 1.03%   |
| 32      | 23       | 0.99%   |
| 72      | 17       | 0.73%   |
| 25      | 17       | 0.73%   |
| 40      | 14       | 0.6%    |
| 26      | 14       | 0.6%    |
| 28      | 10       | 0.43%   |
| 48      | 8        | 0.34%   |
| 12      | 7        | 0.3%    |
| 142     | 6        | 0.26%   |
| 65      | 6        | 0.26%   |
| 46      | 6        | 0.26%   |
| 52      | 5        | 0.21%   |
| 42      | 5        | 0.21%   |
| 33      | 5        | 0.21%   |
| 29      | 5        | 0.21%   |
| 60      | 4        | 0.17%   |
| 36      | 3        | 0.13%   |
| 75      | 2        | 0.09%   |
| 49      | 2        | 0.09%   |
| 43      | 2        | 0.09%   |
| 39      | 2        | 0.09%   |
| 37      | 2        | 0.09%   |
| 13      | 2        | 0.09%   |
| 85      | 1        | 0.04%   |
| 63      | 1        | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 767      | 33.98%  |
| 401-500        | 639      | 28.31%  |
| Unknown        | 278      | 12.32%  |
| 301-350        | 137      | 6.07%   |
| 601-700        | 113      | 5.01%   |
| 701-800        | 87       | 3.85%   |
| 351-400        | 84       | 3.72%   |
| 1001-1500      | 57       | 2.53%   |
| 1501-2000      | 53       | 2.35%   |
| 801-900        | 19       | 0.84%   |
| 201-300        | 9        | 0.4%    |
| 901-1000       | 7        | 0.31%   |
| More than 2000 | 6        | 0.27%   |
| 1-100          | 1        | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 1366     | 62.72%  |
| 16/10   | 250      | 11.48%  |
| Unknown | 239      | 10.97%  |
| 5/4     | 180      | 8.26%   |
| 21/9    | 66       | 3.03%   |
| 4/3     | 44       | 2.02%   |
| 3/2     | 11       | 0.51%   |
| 6/5     | 8        | 0.37%   |
| 32/9    | 7        | 0.32%   |
| 1.00    | 6        | 0.28%   |
| 2.00    | 1        | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 773      | 33.77%  |
| 301-350        | 303      | 13.24%  |
| 151-200        | 296      | 12.93%  |
| Unknown        | 278      | 12.15%  |
| 141-150        | 206      | 9%      |
| 351-500        | 154      | 6.73%   |
| More than 1000 | 103      | 4.5%    |
| 251-300        | 95       | 4.15%   |
| 501-1000       | 41       | 1.79%   |
| 101-110        | 19       | 0.83%   |
| 111-120        | 8        | 0.35%   |
| 71-80          | 6        | 0.26%   |
| 61-70          | 2        | 0.09%   |
| 121-130        | 2        | 0.09%   |
| 81-90          | 1        | 0.04%   |
| 1-40           | 1        | 0.04%   |
| 91-100         | 1        | 0.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 1304     | 59.63%  |
| 101-120       | 419      | 19.16%  |
| Unknown       | 278      | 12.71%  |
| 121-160       | 79       | 3.61%   |
| 1-50          | 76       | 3.48%   |
| 161-240       | 30       | 1.37%   |
| More than 240 | 1        | 0.05%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1798     | 78.41%  |
| 2     | 338      | 14.74%  |
| 0     | 124      | 5.41%   |
| 3     | 31       | 1.35%   |
| 4     | 2        | 0.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 1453     | 46.41%  |
| Intel                                  | 803      | 25.65%  |
| Qualcomm Atheros                       | 220      | 7.03%   |
| Ralink Technology                      | 87       | 2.78%   |
| TP-Link                                | 83       | 2.65%   |
| Broadcom                               | 72       | 2.3%    |
| Nvidia                                 | 66       | 2.11%   |
| Ralink                                 | 36       | 1.15%   |
| Qualcomm Atheros Communications        | 35       | 1.12%   |
| Marvell Technology Group               | 31       | 0.99%   |
| MediaTek                               | 27       | 0.86%   |
| D-Link                                 | 21       | 0.67%   |
| Samsung Electronics                    | 14       | 0.45%   |
| D-Link System                          | 14       | 0.45%   |
| Xiaomi                                 | 13       | 0.42%   |
| VIA Technologies                       | 13       | 0.42%   |
| ASUSTek Computer                       | 13       | 0.42%   |
| Microsoft                              | 12       | 0.38%   |
| Broadcom Limited                       | 11       | 0.35%   |
| Belkin Components                      | 10       | 0.32%   |
| ASIX Electronics                       | 8        | 0.26%   |
| ZyDAS                                  | 7        | 0.22%   |
| Silicon Integrated Systems [SiS]       | 6        | 0.19%   |
| Qualcomm                               | 6        | 0.19%   |
| DisplayLink                            | 6        | 0.19%   |
| Aquantia                               | 6        | 0.19%   |
| Edimax Technology                      | 4        | 0.13%   |
| Texas Instruments                      | 3        | 0.1%    |
| Huawei Technologies                    | 3        | 0.1%    |
| Gemtek                                 | 3        | 0.1%    |
| ZTE WCDMA Technologies MSM             | 2        | 0.06%   |
| Tenda                                  | 2        | 0.06%   |
| Sony Ericsson Mobile Communications AB | 2        | 0.06%   |
| NetGear                                | 2        | 0.06%   |
| Microchip Technology                   | 2        | 0.06%   |
| Arduino SA                             | 2        | 0.06%   |
| Apple                                  | 2        | 0.06%   |
| Accton Technology                      | 2        | 0.06%   |
| 3Com                                   | 2        | 0.06%   |
| ZyXEL Communications                   | 1        | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 1175     | 33.61%  |
| Realtek RTL8125 2.5GbE Controller                                      | 101      | 2.89%   |
| Intel Wi-Fi 6 AX200                                                    | 95       | 2.72%   |
| Intel I211 Gigabit Network Connection                                  | 94       | 2.69%   |
| Intel Ethernet Connection (2) I219-V                                   | 93       | 2.66%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 71       | 2.03%   |
| Intel Ethernet Controller I225-V                                       | 53       | 1.52%   |
| Intel Ethernet Connection I217-LM                                      | 42       | 1.2%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 39       | 1.12%   |
| Intel Ethernet Connection (7) I219-V                                   | 38       | 1.09%   |
| Qualcomm Atheros AR9271 802.11n                                        | 31       | 0.89%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 30       | 0.86%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 30       | 0.86%   |
| Nvidia MCP61 Ethernet                                                  | 29       | 0.83%   |
| Intel 82579V Gigabit Network Connection                                | 29       | 0.83%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 27       | 0.77%   |
| Intel Ethernet Connection (2) I218-V                                   | 27       | 0.77%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 26       | 0.74%   |
| Realtek 802.11ac NIC                                                   | 25       | 0.72%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                        | 23       | 0.66%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 23       | 0.66%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 22       | 0.63%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 21       | 0.6%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 21       | 0.6%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 20       | 0.57%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 20       | 0.57%   |
| Intel Wireless 3165                                                    | 20       | 0.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 19       | 0.54%   |
| Intel Wireless 7265                                                    | 19       | 0.54%   |
| Intel Ethernet Connection (2) I219-LM                                  | 19       | 0.54%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 19       | 0.54%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 18       | 0.51%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 18       | 0.51%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                 | 17       | 0.49%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 17       | 0.49%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                       | 17       | 0.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 17       | 0.49%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 17       | 0.49%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter               | 16       | 0.46%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 16       | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 272      | 26.43%  |
| Realtek Semiconductor                 | 252      | 24.49%  |
| Qualcomm Atheros                      | 110      | 10.69%  |
| Ralink Technology                     | 87       | 8.45%   |
| TP-Link                               | 80       | 7.77%   |
| Ralink                                | 36       | 3.5%    |
| Qualcomm Atheros Communications       | 35       | 3.4%    |
| Broadcom                              | 33       | 3.21%   |
| MediaTek                              | 25       | 2.43%   |
| D-Link                                | 20       | 1.94%   |
| ASUSTek Computer                      | 13       | 1.26%   |
| Microsoft                             | 12       | 1.17%   |
| Belkin Components                     | 10       | 0.97%   |
| ZyDAS                                 | 7        | 0.68%   |
| D-Link System                         | 7        | 0.68%   |
| Edimax Technology                     | 4        | 0.39%   |
| Broadcom Limited                      | 4        | 0.39%   |
| Texas Instruments                     | 3        | 0.29%   |
| Gemtek                                | 3        | 0.29%   |
| Tenda                                 | 2        | 0.19%   |
| NetGear                               | 2        | 0.19%   |
| ZyXEL Communications                  | 1        | 0.1%    |
| Xiaomi                                | 1        | 0.1%    |
| Wilocity                              | 1        | 0.1%    |
| Wacom                                 | 1        | 0.1%    |
| TRENDnet                              | 1        | 0.1%    |
| Standard Microsystems                 | 1        | 0.1%    |
| Sitecom Europe                        | 1        | 0.1%    |
| Samsung Electronics                   | 1        | 0.1%    |
| Marvell Technology Group              | 1        | 0.1%    |
| Linksys                               | 1        | 0.1%    |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.1%    |
| 3Com                                  | 1        | 0.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 95       | 9.11%   |
| Qualcomm Atheros AR9271 802.11n                                | 31       | 2.97%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 30       | 2.88%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 30       | 2.88%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 27       | 2.59%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 26       | 2.49%   |
| Realtek 802.11ac NIC                                           | 25       | 2.4%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 23       | 2.21%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 22       | 2.11%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 21       | 2.01%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 21       | 2.01%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 20       | 1.92%   |
| Intel Wireless 3165                                            | 20       | 1.92%   |
| Intel Wireless 7265                                            | 19       | 1.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 18       | 1.73%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 18       | 1.73%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 17       | 1.63%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 17       | 1.63%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 16       | 1.53%   |
| Ralink MT7601U Wireless Adapter                                | 15       | 1.44%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 13       | 1.25%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 12       | 1.15%   |
| Realtek RTL8187 Wireless Adapter                               | 12       | 1.15%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter              | 12       | 1.15%   |
| TP-Link 802.11ac NIC                                           | 11       | 1.05%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 11       | 1.05%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 11       | 1.05%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter   | 11       | 1.05%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 10       | 0.96%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter     | 10       | 0.96%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 10       | 0.96%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 9        | 0.86%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 9        | 0.86%   |
| Ralink RT5370 Wireless Adapter                                 | 9        | 0.86%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 9        | 0.86%   |
| Ralink RT2561/RT61 rev B 802.11g                               | 8        | 0.77%   |
| Microsoft Xbox Wireless Adapter for Windows                    | 8        | 0.77%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 8        | 0.77%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 8        | 0.77%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 8        | 0.77%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 1355     | 57.15%  |
| Intel                                  | 649      | 27.37%  |
| Qualcomm Atheros                       | 121      | 5.1%    |
| Nvidia                                 | 66       | 2.78%   |
| Broadcom                               | 39       | 1.64%   |
| Marvell Technology Group               | 31       | 1.31%   |
| VIA Technologies                       | 13       | 0.55%   |
| Samsung Electronics                    | 13       | 0.55%   |
| Xiaomi                                 | 12       | 0.51%   |
| ASIX Electronics                       | 8        | 0.34%   |
| D-Link System                          | 7        | 0.3%    |
| Broadcom Limited                       | 7        | 0.3%    |
| Silicon Integrated Systems [SiS]       | 6        | 0.25%   |
| Qualcomm                               | 6        | 0.25%   |
| DisplayLink                            | 6        | 0.25%   |
| Aquantia                               | 6        | 0.25%   |
| TP-Link                                | 3        | 0.13%   |
| ZTE WCDMA Technologies MSM             | 2        | 0.08%   |
| Sony Ericsson Mobile Communications AB | 2        | 0.08%   |
| Huawei Technologies                    | 2        | 0.08%   |
| Apple                                  | 2        | 0.08%   |
| Accton Technology                      | 2        | 0.08%   |
| Tehuti Networks                        | 1        | 0.04%   |
| Spreadtrum Communications              | 1        | 0.04%   |
| MosChip Semiconductor                  | 1        | 0.04%   |
| Microchip Technology                   | 1        | 0.04%   |
| Meizu                                  | 1        | 0.04%   |
| MediaTek                               | 1        | 0.04%   |
| Lenovo                                 | 1        | 0.04%   |
| HTC (High Tech Computer)               | 1        | 0.04%   |
| Davicom Semiconductor                  | 1        | 0.04%   |
| D-Link                                 | 1        | 0.04%   |
| American Megatrends                    | 1        | 0.04%   |
| ADMtek                                 | 1        | 0.04%   |
| 3Com                                   | 1        | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 1175     | 48.23%  |
| Realtek RTL8125 2.5GbE Controller                                      | 101      | 4.15%   |
| Intel I211 Gigabit Network Connection                                  | 94       | 3.86%   |
| Intel Ethernet Connection (2) I219-V                                   | 93       | 3.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 71       | 2.91%   |
| Intel Ethernet Controller I225-V                                       | 53       | 2.18%   |
| Intel Ethernet Connection I217-LM                                      | 42       | 1.72%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 39       | 1.6%    |
| Intel Ethernet Connection (7) I219-V                                   | 38       | 1.56%   |
| Nvidia MCP61 Ethernet                                                  | 29       | 1.19%   |
| Intel 82579V Gigabit Network Connection                                | 29       | 1.19%   |
| Intel Ethernet Connection (2) I218-V                                   | 27       | 1.11%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 23       | 0.94%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 20       | 0.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 19       | 0.78%   |
| Intel Ethernet Connection (2) I219-LM                                  | 19       | 0.78%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 19       | 0.78%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 17       | 0.7%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 17       | 0.7%    |
| Intel 82567LM-3 Gigabit Network Connection                             | 17       | 0.7%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 16       | 0.66%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 15       | 0.62%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 15       | 0.62%   |
| Intel Ethernet Connection I217-V                                       | 15       | 0.62%   |
| Intel 82574L Gigabit Network Connection                                | 14       | 0.57%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 12       | 0.49%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 12       | 0.49%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 12       | 0.49%   |
| Intel 82578DC Gigabit Network Connection                               | 12       | 0.49%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 11       | 0.45%   |
| Nvidia MCP73 Ethernet                                                  | 11       | 0.45%   |
| Intel I210 Gigabit Network Connection                                  | 11       | 0.45%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 10       | 0.41%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 10       | 0.41%   |
| Intel Ethernet Connection (14) I219-V                                  | 10       | 0.41%   |
| Nvidia MCP77 Ethernet                                                  | 9        | 0.37%   |
| Intel 82578DM Gigabit Network Connection                               | 9        | 0.37%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                             | 8        | 0.33%   |
| Intel Ethernet Connection (11) I219-V                                  | 8        | 0.33%   |
| Intel NM10/ICH7 Family LAN Controller                                  | 7        | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2218     | 69.68%  |
| WiFi     | 949      | 29.81%  |
| Modem    | 13       | 0.41%   |
| Unknown  | 3        | 0.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1777     | 76.1%   |
| WiFi     | 558      | 23.9%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1523     | 67.54%  |
| 2     | 650      | 28.82%  |
| 3     | 58       | 2.57%   |
| 0     | 13       | 0.58%   |
| 4     | 6        | 0.27%   |
| 5     | 5        | 0.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2142     | 95.45%  |
| Yes  | 102      | 4.55%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 255      | 33.46%  |
| Intel                           | 253      | 33.2%   |
| Realtek Semiconductor           | 82       | 10.76%  |
| ASUSTek Computer                | 40       | 5.25%   |
| Broadcom                        | 29       | 3.81%   |
| IMC Networks                    | 21       | 2.76%   |
| MediaTek                        | 13       | 1.71%   |
| Belkin Components               | 11       | 1.44%   |
| Qualcomm Atheros Communications | 10       | 1.31%   |
| TP-Link                         | 9        | 1.18%   |
| Integrated System Solution      | 8        | 1.05%   |
| Apple                           | 8        | 1.05%   |
| Foxconn / Hon Hai               | 5        | 0.66%   |
| Lite-On Technology              | 4        | 0.52%   |
| Edimax Technology               | 3        | 0.39%   |
| Actions                         | 3        | 0.39%   |
| Roper                           | 2        | 0.26%   |
| Dell                            | 2        | 0.26%   |
| Sitecom Europe                  | 1        | 0.13%   |
| Realtek                         | 1        | 0.13%   |
| Logitech                        | 1        | 0.13%   |
| Corsair                         | 1        | 0.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 255      | 33.42%  |
| Intel AX200 Bluetooth                                 | 90       | 11.8%   |
| Realtek Bluetooth Radio                               | 73       | 9.57%   |
| Intel Bluetooth wireless interface                    | 50       | 6.55%   |
| Intel AX210 Bluetooth                                 | 25       | 3.28%   |
| Intel AX201 Bluetooth                                 | 24       | 3.15%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 21       | 2.75%   |
| Intel Wireless-AC 3168 Bluetooth                      | 21       | 2.75%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 17       | 2.23%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 14       | 1.83%   |
| MediaTek Wireless_Device                              | 13       | 1.7%    |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 13       | 1.7%    |
| IMC Networks Bluetooth Radio                          | 11       | 1.44%   |
| TP-Link UB500 Adapter                                 | 9        | 1.18%   |
| Realtek  Bluetooth 4.2 Adapter                        | 9        | 1.18%   |
| Integrated System Solution Bluetooth Device           | 8        | 1.05%   |
| ASUS Bluetooth Radio                                  | 7        | 0.92%   |
| Intel Bluetooth Device                                | 6        | 0.79%   |
| IMC Networks Wireless_Device                          | 5        | 0.66%   |
| Foxconn / Hon Hai Wireless_Device                     | 4        | 0.52%   |
| Belkin Components Bluetooth Mini Dongle               | 4        | 0.52%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 4        | 0.52%   |
| Apple Bluetooth Host Controller                       | 4        | 0.52%   |
| Qualcomm Atheros  Bluetooth Device                    | 3        | 0.39%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 3        | 0.39%   |
| Lite-On Bluetooth Device                              | 3        | 0.39%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 3        | 0.39%   |
| IMC Networks BCM20702A0                               | 3        | 0.39%   |
| Broadcom Bluetooth 3.0 Dongle                         | 3        | 0.39%   |
| Broadcom BCM2045 Bluetooth                            | 3        | 0.39%   |
| Broadcom BCM2035 Bluetooth dongle                     | 3        | 0.39%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter | 3        | 0.39%   |
| ASUS Qualcomm Bluetooth 4.1                           | 3        | 0.39%   |
| ASUS BCM20702A0                                       | 3        | 0.39%   |
| Actions general adapter                               | 3        | 0.39%   |
| Roper Class 1 Bluetooth Dongle                        | 2        | 0.26%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 2        | 0.26%   |
| IMC Networks Bluetooth Device                         | 2        | 0.26%   |
| Broadcom Bluetooth Controller                         | 2        | 0.26%   |
| Belkin Components Bluetooth Device with trace filter  | 2        | 0.26%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 1451     | 39.26%  |
| Nvidia                                       | 921      | 24.92%  |
| AMD                                          | 830      | 22.46%  |
| C-Media Electronics                          | 93       | 2.52%   |
| Creative Labs                                | 42       | 1.14%   |
| Logitech                                     | 29       | 0.78%   |
| Texas Instruments                            | 24       | 0.65%   |
| JMTek                                        | 23       | 0.62%   |
| ASUSTek Computer                             | 20       | 0.54%   |
| Focusrite-Novation                           | 15       | 0.41%   |
| Corsair                                      | 15       | 0.41%   |
| VIA Technologies                             | 14       | 0.38%   |
| Kingston Technology                          | 14       | 0.38%   |
| Micro Star International                     | 11       | 0.3%    |
| Creative Technology                          | 10       | 0.27%   |
| SteelSeries ApS                              | 9        | 0.24%   |
| Silicon Integrated Systems [SiS]             | 9        | 0.24%   |
| Plantronics                                  | 9        | 0.24%   |
| GN Netcom                                    | 8        | 0.22%   |
| Generalplus Technology                       | 8        | 0.22%   |
| Dell                                         | 8        | 0.22%   |
| Sennheiser Communications                    | 7        | 0.19%   |
| Razer USA                                    | 6        | 0.16%   |
| M-Audio                                      | 6        | 0.16%   |
| Ensoniq                                      | 6        | 0.16%   |
| BEHRINGER International                      | 6        | 0.16%   |
| Tenx Technology                              | 5        | 0.14%   |
| Yamaha                                       | 4        | 0.11%   |
| Realtek Semiconductor                        | 4        | 0.11%   |
| Hewlett-Packard                              | 4        | 0.11%   |
| XMOS                                         | 3        | 0.08%   |
| SAVITECH                                     | 3        | 0.08%   |
| RODE Microphones                             | 3        | 0.08%   |
| QinHeng Electronics                          | 3        | 0.08%   |
| Zoran Co. Personal Media Division (Nogatech) | 2        | 0.05%   |
| Unknown                                      | 2        | 0.05%   |
| Thesycon Systemsoftware & Consulting         | 2        | 0.05%   |
| Sony                                         | 2        | 0.05%   |
| PreSonus Audio Electronics                   | 2        | 0.05%   |
| Native Instruments                           | 2        | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 224      | 5.22%   |
| AMD Starship/Matisse HD Audio Controller                                   | 166      | 3.87%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 160      | 3.73%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 152      | 3.54%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 134      | 3.12%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 132      | 3.08%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 124      | 2.89%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 124      | 2.89%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 123      | 2.87%   |
| Intel 200 Series PCH HD Audio                                              | 121      | 2.82%   |
| AMD Family 17h/19h HD Audio Controller                                     | 120      | 2.8%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 120      | 2.8%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 105      | 2.45%   |
| Nvidia GP107GL High Definition Audio Controller                            | 97       | 2.26%   |
| Nvidia High Definition Audio Controller                                    | 87       | 2.03%   |
| AMD FCH Azalia Controller                                                  | 75       | 1.75%   |
| Intel Cannon Lake PCH cAVS                                                 | 68       | 1.59%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 64       | 1.49%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 59       | 1.38%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 56       | 1.31%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 53       | 1.24%   |
| Nvidia GP106 High Definition Audio Controller                              | 50       | 1.17%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 43       | 1%      |
| Intel 9 Series Chipset Family HD Audio Controller                          | 43       | 1%      |
| Nvidia GP104 High Definition Audio Controller                              | 40       | 0.93%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 37       | 0.86%   |
| Nvidia TU116 High Definition Audio Controller                              | 36       | 0.84%   |
| Nvidia GP108 High Definition Audio Controller                              | 36       | 0.84%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 36       | 0.84%   |
| AMD Navi 10 HDMI Audio                                                     | 36       | 0.84%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 35       | 0.82%   |
| Nvidia GF119 HDMI Audio Controller                                         | 34       | 0.79%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 34       | 0.79%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 33       | 0.77%   |
| Nvidia MCP61 High Definition Audio                                         | 31       | 0.72%   |
| Nvidia GF108 High Definition Audio Controller                              | 31       | 0.72%   |
| Nvidia GM206 High Definition Audio Controller                              | 30       | 0.7%    |
| Nvidia GA104 High Definition Audio Controller                              | 28       | 0.65%   |
| Intel Comet Lake PCH cAVS                                                  | 27       | 0.63%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 26       | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 327      | 26.89%  |
| Unknown                      | 177      | 14.56%  |
| Corsair                      | 143      | 11.76%  |
| Crucial                      | 123      | 10.12%  |
| Samsung Electronics          | 110      | 9.05%   |
| G.Skill                      | 86       | 7.07%   |
| SK hynix                     | 80       | 6.58%   |
| Micron Technology            | 39       | 3.21%   |
| Team                         | 12       | 0.99%   |
| Unknown (ABCD)               | 11       | 0.9%    |
| Nanya Technology             | 11       | 0.9%    |
| Elpida                       | 10       | 0.82%   |
| Unknown                      | 10       | 0.82%   |
| A-DATA Technology            | 8        | 0.66%   |
| Ramaxel Technology           | 7        | 0.58%   |
| Unifosa                      | 5        | 0.41%   |
| Silicon Power                | 5        | 0.41%   |
| Apacer                       | 5        | 0.41%   |
| Transcend                    | 4        | 0.33%   |
| GOODRAM                      | 4        | 0.33%   |
| Kllisre                      | 3        | 0.25%   |
| ASint Technology             | 3        | 0.25%   |
| Wodposit                     | 2        | 0.16%   |
| Unknown (AB)                 | 2        | 0.16%   |
| Patriot                      | 2        | 0.16%   |
| Exceleram                    | 2        | 0.16%   |
| Atermiter                    | 2        | 0.16%   |
| Wilk                         | 1        | 0.08%   |
| Unknown (0x5846)             | 1        | 0.08%   |
| Unknown (0x0B45)             | 1        | 0.08%   |
| Unknown (0x0B15)             | 1        | 0.08%   |
| Unknown (07FB)               | 1        | 0.08%   |
| Timetec                      | 1        | 0.08%   |
| Thermaltake                  | 1        | 0.08%   |
| Qimonda                      | 1        | 0.08%   |
| PNY                          | 1        | 0.08%   |
| Pioneer                      | 1        | 0.08%   |
| Patriot Memory (PDP Systems) | 1        | 0.08%   |
| Patriot Memory               | 1        | 0.08%   |
| Netac                        | 1        | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s          | 21       | 1.53%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 17       | 1.24%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s            | 16       | 1.17%   |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3200MT/s          | 13       | 0.95%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s           | 12       | 0.87%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s            | 12       | 0.87%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 11       | 0.8%    |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s          | 11       | 0.8%    |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s            | 10       | 0.73%   |
| Kingston RAM 99U5471-020.A00LF 4GB DIMM DDR3 1600MT/s          | 10       | 0.73%   |
| Unknown                                                        | 10       | 0.73%   |
| Unknown RAM Module 2GB DIMM 800MT/s                            | 9        | 0.66%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s         | 9        | 0.66%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                        | 8        | 0.58%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                       | 8        | 0.58%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                    | 8        | 0.58%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s              | 8        | 0.58%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                      | 7        | 0.51%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 7        | 0.51%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 7        | 0.51%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                        | 7        | 0.51%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s              | 7        | 0.51%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s            | 7        | 0.51%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3933MT/s          | 7        | 0.51%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s          | 7        | 0.51%   |
| G.Skill RAM F4-2400C15-8GIS 8GB DIMM DDR4 2400MT/s             | 7        | 0.51%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s         | 7        | 0.51%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 6        | 0.44%   |
| G.Skill RAM F4-3200C16-8GTZR 8GB DIMM DDR4 3200MT/s            | 6        | 0.44%   |
| Crucial RAM CT4G4DFS824A.C8FBD2 4GB DIMM DDR4 2733MT/s         | 6        | 0.44%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3733MT/s          | 6        | 0.44%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                         | 5        | 0.36%   |
| Kingston RAM KHX1600C10D3/4G 4096MB DIMM DDR3 1600MT/s         | 5        | 0.36%   |
| Kingston RAM 99U5474-028.A00LF 4GB DIMM DDR3 1333MT/s          | 5        | 0.36%   |
| Kingston RAM 99U5474-026.A00LF 4GB DIMM DDR3 1333MT/s          | 5        | 0.36%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s          | 5        | 0.36%   |
| G.Skill RAM F3-12800CL9-4GBXL 4GB DIMM DDR3 1867MT/s           | 5        | 0.36%   |
| Crucial RAM CT8G4DFS824A.C8FDD1 8GB DIMM DDR4 3200MT/s         | 5        | 0.36%   |
| Crucial RAM CT8G4DFD824A.C16FF 8GB DIMM DDR4 2733MT/s          | 5        | 0.36%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 4        | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 522      | 47.37%  |
| DDR3    | 346      | 31.4%   |
| Unknown | 76       | 6.9%    |
| DDR2    | 60       | 5.44%   |
| SDRAM   | 52       | 4.72%   |
| DDR5    | 21       | 1.91%   |
| LPDDR4  | 11       | 1%      |
| DDR     | 10       | 0.91%   |
| DRAM    | 3        | 0.27%   |
| LPDDR3  | 1        | 0.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 993      | 92.03%  |
| SODIMM  | 82       | 7.6%    |
| RIMM    | 2        | 0.19%   |
| FB-DIMM | 2        | 0.19%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 448      | 37.4%   |
| 4096  | 285      | 23.79%  |
| 2048  | 182      | 15.19%  |
| 16384 | 177      | 14.77%  |
| 1024  | 60       | 5.01%   |
| 32768 | 40       | 3.34%   |
| 512   | 4        | 0.33%   |
| 65536 | 2        | 0.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 185      | 15.24%  |
| 1333    | 127      | 10.46%  |
| 2400    | 116      | 9.56%   |
| 3200    | 107      | 8.81%   |
| 3600    | 70       | 5.77%   |
| 800     | 62       | 5.11%   |
| 2667    | 58       | 4.78%   |
| 2133    | 56       | 4.61%   |
| 1867    | 37       | 3.05%   |
| 667     | 31       | 2.55%   |
| 3733    | 29       | 2.39%   |
| 1866    | 25       | 2.06%   |
| Unknown | 23       | 1.89%   |
| 3400    | 22       | 1.81%   |
| 2933    | 22       | 1.81%   |
| 3533    | 21       | 1.73%   |
| 3800    | 18       | 1.48%   |
| 3000    | 17       | 1.4%    |
| 2733    | 15       | 1.24%   |
| 2666    | 12       | 0.99%   |
| 1800    | 10       | 0.82%   |
| 1334    | 10       | 0.82%   |
| 1066    | 10       | 0.82%   |
| 4800    | 8        | 0.66%   |
| 3534    | 8        | 0.66%   |
| 3933    | 7        | 0.58%   |
| 3466    | 7        | 0.58%   |
| 400     | 7        | 0.58%   |
| 2800    | 6        | 0.49%   |
| 3666    | 5        | 0.41%   |
| 2048    | 5        | 0.41%   |
| 1639    | 5        | 0.41%   |
| 5600    | 4        | 0.33%   |
| 5200    | 4        | 0.33%   |
| 3866    | 4        | 0.33%   |
| 3500    | 4        | 0.33%   |
| 3266    | 4        | 0.33%   |
| 3066    | 4        | 0.33%   |
| 1331    | 4        | 0.33%   |
| 533     | 4        | 0.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Hewlett-Packard          | 53       | 47.75%  |
| Brother Industries       | 20       | 18.02%  |
| Canon                    | 10       | 9.01%   |
| Samsung Electronics      | 9        | 8.11%   |
| Seiko Epson              | 4        | 3.6%    |
| Oki Data                 | 4        | 3.6%    |
| Dymo-CoStar              | 2        | 1.8%    |
| STMicroelectronics       | 1        | 0.9%    |
| Ricoh                    | 1        | 0.9%    |
| QinHeng Electronics      | 1        | 0.9%    |
| Prolific Technology      | 1        | 0.9%    |
| Magic Control Technology | 1        | 0.9%    |
| Lexmark International    | 1        | 0.9%    |
| Kyocera                  | 1        | 0.9%    |
| Konica Minolta           | 1        | 0.9%    |
| Apple                    | 1        | 0.9%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| HP LaserJet 1018                                | 5        | 4.46%   |
| HP DeskJet 2600 series                          | 4        | 3.57%   |
| Brother HL-2030 Laser Printer                   | 4        | 3.57%   |
| HP DeskJet 3630 series                          | 3        | 2.68%   |
| Samsung M262x/M282x Xpress Series Laser Printer | 2        | 1.79%   |
| Samsung M2070 Series                            | 2        | 1.79%   |
| Oki Data USB Device                             | 2        | 1.79%   |
| Oki Data MC363 Multifunction Printer            | 2        | 1.79%   |
| HP LaserJet 1010                                | 2        | 1.79%   |
| HP ENVY 5540 series                             | 2        | 1.79%   |
| HP ENVY 5000 series                             | 2        | 1.79%   |
| HP ENVY 4520 series                             | 2        | 1.79%   |
| HP ENVY 4500 series                             | 2        | 1.79%   |
| HP DeskJet F2492 All-in-One                     | 2        | 1.79%   |
| HP DeskJet 5550                                 | 2        | 1.79%   |
| HP DeskJet 2700 series                          | 2        | 1.79%   |
| HP Deskjet 1050 J410                            | 2        | 1.79%   |
| Dymo-CoStar LabelWriter 450                     | 2        | 1.79%   |
| Canon LiDE 400                                  | 2        | 1.79%   |
| Canon CanoScan LiDE 300                         | 2        | 1.79%   |
| Brother Printer                                 | 2        | 1.79%   |
| Brother DCP-1510                                | 2        | 1.79%   |
| STMicroelectronics USB Printer P                | 1        | 0.89%   |
| Seiko Epson XP-255 257 Series                   | 1        | 0.89%   |
| Seiko Epson XP-225 Series                       | 1        | 0.89%   |
| Seiko Epson WF-2830 Series                      | 1        | 0.89%   |
| Seiko Epson L1300 Series                        | 1        | 0.89%   |
| Samsung SCX-4300 Series                         | 1        | 0.89%   |
| Samsung SCX-3400 Series                         | 1        | 0.89%   |
| Samsung SCX-3200 Series                         | 1        | 0.89%   |
| Samsung ML-1640 Series Laser Printer            | 1        | 0.89%   |
| Samsung M267x 287x Series                       | 1        | 0.89%   |
| Ricoh SP 112                                    | 1        | 0.89%   |
| QinHeng CH340S                                  | 1        | 0.89%   |
| Prolific PL2305 Parallel Port                   | 1        | 0.89%   |
| Magic Control BAY-3U1S1P Parallel Port          | 1        | 0.89%   |
| Lexmark International B2236dw                   | 1        | 0.89%   |
| Kyocera ECOSYS M5521cdn                         | 1        | 0.89%   |
| Konica Minolta PagePro 1380MF                   | 1        | 0.89%   |
| HP PSC-1315/PSC-1317                            | 1        | 0.89%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Canon                       | 13       | 41.94%  |
| Seiko Epson                 | 7        | 22.58%  |
| Hewlett-Packard             | 7        | 22.58%  |
| Acer Peripherals (now BenQ) | 2        | 6.45%   |
| Mustek Systems              | 1        | 3.23%   |
| KYE Systems (Mouse Systems) | 1        | 3.23%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20                       | 3        | 9.68%   |
| Canon CanoScan LiDE 210                                  | 3        | 9.68%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]       | 2        | 6.45%   |
| HP Scanjet 300                                           | 2        | 6.45%   |
| Canon CanoScan N650U/N656U                               | 2        | 6.45%   |
| Canon CanoScan N1240U/LiDE 30                            | 2        | 6.45%   |
| Acer Peripherals (now BenQ) S2W 3300U/4300U              | 2        | 6.45%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]              | 1        | 3.23%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]        | 1        | 3.23%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1        | 3.23%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]        | 1        | 3.23%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]        | 1        | 3.23%   |
| Mustek Systems ScanExpress 1200 CU                       | 1        | 3.23%   |
| KYE Systems (Mouse Systems) ColorPage-Vivid4             | 1        | 3.23%   |
| HP Scanjet N6010                                         | 1        | 3.23%   |
| HP ScanJet 5200c                                         | 1        | 3.23%   |
| HP ScanJet 4570c                                         | 1        | 3.23%   |
| HP ScanJet 3570c                                         | 1        | 3.23%   |
| HP ScanJet 3300c                                         | 1        | 3.23%   |
| Canon CanoScan LiDE 700F                                 | 1        | 3.23%   |
| Canon CanoScan LIDE 25                                   | 1        | 3.23%   |
| Canon CanoScan LiDE 220                                  | 1        | 3.23%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 130      | 33.33%  |
| Microdia                      | 37       | 9.49%   |
| Sunplus Innovation Technology | 25       | 6.41%   |
| Creative Technology           | 18       | 4.62%   |
| Realtek Semiconductor         | 14       | 3.59%   |
| Microsoft                     | 13       | 3.33%   |
| Samsung Electronics           | 11       | 2.82%   |
| Generalplus Technology        | 11       | 2.82%   |
| Chicony Electronics           | 9        | 2.31%   |
| Z-Star Microelectronics       | 8        | 2.05%   |
| Cubeternet                    | 7        | 1.79%   |
| webcamvendor                  | 6        | 1.54%   |
| GEMBIRD                       | 6        | 1.54%   |
| ARC International             | 6        | 1.54%   |
| Jieli Technology              | 5        | 1.28%   |
| Alcor Micro                   | 5        | 1.28%   |
| Trust                         | 4        | 1.03%   |
| Arkmicro Technologies         | 4        | 1.03%   |
| Apple                         | 4        | 1.03%   |
| WCM_USB                       | 3        | 0.77%   |
| SunplusIT                     | 3        | 0.77%   |
| SJ-180517-N                   | 3        | 0.77%   |
| KYE Systems (Mouse Systems)   | 3        | 0.77%   |
| Huawei Technologies           | 3        | 0.77%   |
| Guillemot                     | 3        | 0.77%   |
| Aveo Technology               | 3        | 0.77%   |
| Xiongmai                      | 2        | 0.51%   |
| Panasonic (Matsushita)        | 2        | 0.51%   |
| OPPO Electronics              | 2        | 0.51%   |
| MacroSilicon                  | 2        | 0.51%   |
| IMC Networks                  | 2        | 0.51%   |
| Google                        | 2        | 0.51%   |
| Genesys Logic                 | 2        | 0.51%   |
| FPL-2053-191010               | 2        | 0.51%   |
| AVerMedia Technologies        | 2        | 0.51%   |
| Xiaomi                        | 1        | 0.26%   |
| WaveRider Communications      | 1        | 0.26%   |
| ValueHD                       | 1        | 0.26%   |
| Unknown                       | 1        | 0.26%   |
| TANDBERG                      | 1        | 0.26%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 33       | 8.4%    |
| Logitech HD Pro Webcam C920                       | 16       | 4.07%   |
| Microdia Webcam Vitade AF                         | 14       | 3.56%   |
| Logitech Webcam C170                              | 14       | 3.56%   |
| Samsung Galaxy series, misc. (MTP mode)           | 11       | 2.8%    |
| Logitech Webcam C310                              | 10       | 2.54%   |
| Sunplus Full HD webcam                            | 8        | 2.04%   |
| Microsoft LifeCam HD-3000                         | 8        | 2.04%   |
| Logitech Webcam C200                              | 8        | 2.04%   |
| Generalplus GENERAL WEBCAM                        | 8        | 2.04%   |
| Realtek Full HD webcam                            | 7        | 1.78%   |
| Logitech HD Webcam C525                           | 7        | 1.78%   |
| Creative Live! Cam Sync HD [VF0770]               | 7        | 1.78%   |
| webcamvendor webcamproduct                        | 6        | 1.53%   |
| ARC International Camera                          | 6        | 1.53%   |
| Microdia USB 2.0 Camera                           | 5        | 1.27%   |
| Jieli USB PHY 2.0                                 | 5        | 1.27%   |
| Creative Live! Cam Chat HD [VF0700/VF0790]        | 5        | 1.27%   |
| Sunplus USB Camera                                | 4        | 1.02%   |
| Microdia Camera                                   | 4        | 1.02%   |
| Logitech HD Webcam C615                           | 4        | 1.02%   |
| Logitech C922 Pro Stream Webcam                   | 4        | 1.02%   |
| Logitech C920 PRO HD Webcam                       | 4        | 1.02%   |
| Cubeternet USB2.0 Camera                          | 4        | 1.02%   |
| Alcor Micro USB 2.0 PC Camera                     | 4        | 1.02%   |
| Z-Star Venus USB2.0 Camera                        | 3        | 0.76%   |
| WCM_USB WEB CAM                                   | 3        | 0.76%   |
| Trust USB Camera                                  | 3        | 0.76%   |
| Sunplus FHD Camera                                | 3        | 0.76%   |
| SJ-180517-N 1080P Webcam                          | 3        | 0.76%   |
| Microdia Integrated Camera                        | 3        | 0.76%   |
| Logitech Webcam C210                              | 3        | 0.76%   |
| Logitech QuickCam Pro 9000                        | 3        | 0.76%   |
| Logitech QuickCam E 3500                          | 3        | 0.76%   |
| KYE Systems (Mouse Systems) Genius Webcam         | 3        | 0.76%   |
| Huawei HiCamera                                   | 3        | 0.76%   |
| Generalplus 808 Camera                            | 3        | 0.76%   |
| GEMBIRD USB2.0 PC CAMERA                          | 3        | 0.76%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 3        | 0.76%   |
| Creative Live! Cam Sync 1080p V2                  | 3        | 0.76%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| LighTuning Fingerprint Sensor | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Alcor Micro               | 17       | 34.69%  |
| Chicony Electronics       | 7        | 14.29%  |
| Advanced Card Systems     | 7        | 14.29%  |
| SCM Microsystems          | 3        | 6.12%   |
| Realtek Semiconductor     | 3        | 6.12%   |
| Cherry                    | 3        | 6.12%   |
| OmniKey                   | 2        | 4.08%   |
| Hewlett-Packard           | 2        | 4.08%   |
| C3PO                      | 2        | 4.08%   |
| Gemalto (was Gemplus)     | 1        | 2.04%   |
| Fujitsu Siemens Computers | 1        | 2.04%   |
| Bit4id                    | 1        | 2.04%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Alcor Micro AU9540 Smartcard Reader                    | 12       | 24.49%  |
| Chicony Electronics HP Skylab USB Smartcard Keyboard   | 7        | 14.29%  |
| Alcor Micro Watchdata W 1981                           | 5        | 10.2%   |
| Advanced Card Systems ACR38 SmartCard Reader           | 5        | 10.2%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 3        | 6.12%   |
| Realtek Semiconductor Smart Card Reader Interface      | 3        | 6.12%   |
| OmniKey CardMan 3021 / 3121                            | 2        | 4.08%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)          | 2        | 4.08%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC            | 2        | 4.08%   |
| C3PO LTC31v2                                           | 2        | 4.08%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader      | 1        | 2.04%   |
| Fujitsu Siemens Computers SmartCard Reader 2A          | 1        | 2.04%   |
| Cherry SmartTerminal XX1X                              | 1        | 2.04%   |
| Bit4id miniLector-s                                    | 1        | 2.04%   |
| Advanced Card Systems ACR39U                           | 1        | 2.04%   |
| Advanced Card Systems ACR122U                          | 1        | 2.04%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 1931     | 84.51%  |
| 1     | 306      | 13.39%  |
| 2     | 37       | 1.62%   |
| 3     | 5        | 0.22%   |
| 5     | 2        | 0.09%   |
| 4     | 2        | 0.09%   |
| 9     | 1        | 0.04%   |
| 6     | 1        | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 133      | 33.08%  |
| Net/wireless             | 84       | 20.9%   |
| Unassigned class         | 37       | 9.2%    |
| Chipcard                 | 28       | 6.97%   |
| Communication controller | 21       | 5.22%   |
| Multimedia controller    | 19       | 4.73%   |
| Sound                    | 16       | 3.98%   |
| Bluetooth                | 13       | 3.23%   |
| Camera                   | 12       | 2.99%   |
| Network                  | 10       | 2.49%   |
| Net/ethernet             | 7        | 1.74%   |
| Card reader              | 5        | 1.24%   |
| Storage/raid             | 4        | 1%      |
| Firewire controller      | 4        | 1%      |
| Storage/nvme             | 2        | 0.5%    |
| Dvb card                 | 2        | 0.5%    |
| Tv card                  | 1        | 0.25%   |
| Storage/ide              | 1        | 0.25%   |
| Storage                  | 1        | 0.25%   |
| Modem                    | 1        | 0.25%   |
| Fingerprint reader       | 1        | 0.25%   |

